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

Total: 148

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 20        | 17.24%  |
| Ubuntu 18.04                 | 9         | 7.76%   |
| Ubuntu 21.04                 | 4         | 3.45%   |
| Linux Mint 20.3              | 4         | 3.45%   |
| Ubuntu 20.10                 | 3         | 2.59%   |
| Pop!_OS 21.04                | 3         | 2.59%   |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 2.59%   |
| OpenMandriva 4.2             | 3         | 2.59%   |
| Fedora 32                    | 3         | 2.59%   |
| Xubuntu 20.04                | 2         | 1.72%   |
| Ubuntu 22.04                 | 2         | 1.72%   |
| Ubuntu 18.10                 | 2         | 1.72%   |
| ROSA R9                      | 2         | 1.72%   |
| Pop!_OS 21.10                | 2         | 1.72%   |
| openSUSE Leap-15.2           | 2         | 1.72%   |
| OpenMandriva 4.90            | 2         | 1.72%   |
| LMDE 4                       | 2         | 1.72%   |
| Debian 10                    | 2         | 1.72%   |
| Xubuntu 18.04                | 1         | 0.86%   |
| Xubuntu 16.04                | 1         | 0.86%   |
| UbuntuDDE 20.04              | 1         | 0.86%   |
| Ubuntu MATE 21.10            | 1         | 0.86%   |
| Ubuntu MATE 20.04            | 1         | 0.86%   |
| Ubuntu 22.10                 | 1         | 0.86%   |
| Ubuntu 19.10                 | 1         | 0.86%   |
| RHEL 8                       | 1         | 0.86%   |
| Pop!_OS 22.04                | 1         | 0.86%   |
| Pop!_OS 20.10                | 1         | 0.86%   |
| Pop!_OS 20.04                | 1         | 0.86%   |
| Parrot 5.1                   | 1         | 0.86%   |
| openSUSE Leap-15.3           | 1         | 0.86%   |
| openSUSE Leap-15.1           | 1         | 0.86%   |
| OpenMandriva 4.3             | 1         | 0.86%   |
| Manjaro 21.2.6               | 1         | 0.86%   |
| Manjaro 21.1.0               | 1         | 0.86%   |
| Manjaro 19.0.2               | 1         | 0.86%   |
| Mageia 7                     | 1         | 0.86%   |
| Lubuntu 20.10                | 1         | 0.86%   |
| Lubuntu 20.04                | 1         | 0.86%   |
| Linux Mint 20.2              | 1         | 0.86%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 42        | 37.84%  |
| Pop!_OS      | 7         | 6.31%   |
| openSUSE     | 6         | 5.41%   |
| OpenMandriva | 6         | 5.41%   |
| Linux Mint   | 6         | 5.41%   |
| Fedora       | 6         | 5.41%   |
| Xubuntu      | 4         | 3.6%    |
| Manjaro      | 3         | 2.7%    |
| Kubuntu      | 3         | 2.7%    |
| Debian       | 3         | 2.7%    |
| Ubuntu MATE  | 2         | 1.8%    |
| ROSA         | 2         | 1.8%    |
| Lubuntu      | 2         | 1.8%    |
| LMDE         | 2         | 1.8%    |
| Endless      | 2         | 1.8%    |
| Elementary   | 2         | 1.8%    |
| Arch         | 2         | 1.8%    |
| UbuntuDDE    | 1         | 0.9%    |
| RHEL         | 1         | 0.9%    |
| Parrot       | 1         | 0.9%    |
| Mageia       | 1         | 0.9%    |
| KDE neon     | 1         | 0.9%    |
| Kali         | 1         | 0.9%    |
| Garuda Linux | 1         | 0.9%    |
| Clear Linux  | 1         | 0.9%    |
| CentOS       | 1         | 0.9%    |
| BlackPanther | 1         | 0.9%    |
| ArcoLinux    | 1         | 0.9%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.8.0-43-generic                | 3         | 2.5%    |
| 5.11.0-27-generic               | 3         | 2.5%    |
| 5.10.14-desktop-1omv4002        | 3         | 2.5%    |
| 5.8.0-59-generic                | 2         | 1.67%   |
| 5.4.0-96-generic                | 2         | 1.67%   |
| 5.4.0-90-generic                | 2         | 1.67%   |
| 5.4.0-47-generic                | 2         | 1.67%   |
| 5.4.0-42-generic                | 2         | 1.67%   |
| 5.4.0-122-generic               | 2         | 1.67%   |
| 5.3.0-46-generic                | 2         | 1.67%   |
| 5.18.12-desktop-3omv4090        | 2         | 1.67%   |
| 5.16.11-76051611-generic        | 2         | 1.67%   |
| 5.11.0-34-generic               | 2         | 1.67%   |
| 5.11.0-17-generic               | 2         | 1.67%   |
| 5.0.0-23-generic                | 2         | 1.67%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 2         | 1.67%   |
| 4.19.0-17-amd64                 | 2         | 1.67%   |
| 5.9.13-zen1-1-zen               | 1         | 0.83%   |
| 5.9.10-200.fc33.x86_64          | 1         | 0.83%   |
| 5.8.11-050811-generic           | 1         | 0.83%   |
| 5.8.0-63-generic                | 1         | 0.83%   |
| 5.8.0-55-generic                | 1         | 0.83%   |
| 5.8.0-44-generic                | 1         | 0.83%   |
| 5.8.0-31-generic                | 1         | 0.83%   |
| 5.8.0-26-generic                | 1         | 0.83%   |
| 5.8.0-20-generic                | 1         | 0.83%   |
| 5.8.0-14-generic                | 1         | 0.83%   |
| 5.7.6-201.fc32.x86_64           | 1         | 0.83%   |
| 5.7.19-desktop-3.mga7           | 1         | 0.83%   |
| 5.7.14-200.fc32.x86_64          | 1         | 0.83%   |
| 5.7.1-1-default                 | 1         | 0.83%   |
| 5.7.0-3-amd64                   | 1         | 0.83%   |
| 5.7.0-050700-generic            | 1         | 0.83%   |
| 5.6.3-935.native                | 1         | 0.83%   |
| 5.5.8-1-MANJARO                 | 1         | 0.83%   |
| 5.4.0-91-generic                | 1         | 0.83%   |
| 5.4.0-84-generic                | 1         | 0.83%   |
| 5.4.0-73-generic                | 1         | 0.83%   |
| 5.4.0-72-generic                | 1         | 0.83%   |
| 5.4.0-58-generic                | 1         | 0.83%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 19        | 16.81%  |
| 5.11.0  | 14        | 12.39%  |
| 5.8.0   | 10        | 8.85%   |
| 5.3.0   | 6         | 5.31%   |
| 5.15.0  | 6         | 5.31%   |
| 4.18.0  | 6         | 5.31%   |
| 5.13.0  | 4         | 3.54%   |
| 5.10.14 | 3         | 2.65%   |
| 5.0.0   | 3         | 2.65%   |
| 4.15.0  | 3         | 2.65%   |
| 5.7.0   | 2         | 1.77%   |
| 5.3.18  | 2         | 1.77%   |
| 5.18.12 | 2         | 1.77%   |
| 5.16.11 | 2         | 1.77%   |
| 5.10.0  | 2         | 1.77%   |
| 4.9.20  | 2         | 1.77%   |
| 4.19.0  | 2         | 1.77%   |
| 5.9.13  | 1         | 0.88%   |
| 5.9.10  | 1         | 0.88%   |
| 5.8.11  | 1         | 0.88%   |
| 5.7.6   | 1         | 0.88%   |
| 5.7.19  | 1         | 0.88%   |
| 5.7.14  | 1         | 0.88%   |
| 5.7.1   | 1         | 0.88%   |
| 5.6.3   | 1         | 0.88%   |
| 5.5.8   | 1         | 0.88%   |
| 5.19.0  | 1         | 0.88%   |
| 5.18.5  | 1         | 0.88%   |
| 5.18.0  | 1         | 0.88%   |
| 5.16.7  | 1         | 0.88%   |
| 5.16.2  | 1         | 0.88%   |
| 5.15.4  | 1         | 0.88%   |
| 5.15.32 | 1         | 0.88%   |
| 5.14.0  | 1         | 0.88%   |
| 5.13.4  | 1         | 0.88%   |
| 5.12.7  | 1         | 0.88%   |
| 5.12.13 | 1         | 0.88%   |
| 5.10.7  | 1         | 0.88%   |
| 5.10.26 | 1         | 0.88%   |
| 4.4.0   | 1         | 0.88%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 19        | 16.81%  |
| 5.11    | 14        | 12.39%  |
| 5.8     | 11        | 9.73%   |
| 5.3     | 8         | 7.08%   |
| 5.15    | 8         | 7.08%   |
| 5.10    | 7         | 6.19%   |
| 4.18    | 7         | 6.19%   |
| 5.7     | 6         | 5.31%   |
| 5.13    | 5         | 4.42%   |
| 5.18    | 4         | 3.54%   |
| 5.16    | 4         | 3.54%   |
| 5.0     | 3         | 2.65%   |
| 4.15    | 3         | 2.65%   |
| 5.9     | 2         | 1.77%   |
| 5.12    | 2         | 1.77%   |
| 4.9     | 2         | 1.77%   |
| 4.19    | 2         | 1.77%   |
| 5.6     | 1         | 0.88%   |
| 5.5     | 1         | 0.88%   |
| 5.19    | 1         | 0.88%   |
| 5.14    | 1         | 0.88%   |
| 4.4     | 1         | 0.88%   |
| 4.12    | 1         | 0.88%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 107       | 98.17%  |
| i686   | 2         | 1.83%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 51        | 45.13%  |
| KDE5            | 16        | 14.16%  |
| Unknown         | 14        | 12.39%  |
| X-Cinnamon      | 8         | 7.08%   |
| XFCE            | 6         | 5.31%   |
| KDE             | 5         | 4.42%   |
| MATE            | 3         | 2.65%   |
| Pantheon        | 2         | 1.77%   |
| LXQt            | 2         | 1.77%   |
| i3              | 2         | 1.77%   |
| Cinnamon        | 2         | 1.77%   |
| GNOME Flashback | 1         | 0.88%   |
| Deepin          | 1         | 0.88%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 86        | 77.48%  |
| Wayland | 12        | 10.81%  |
| Unknown | 9         | 8.11%   |
| Tty     | 4         | 3.6%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 58        | 50.88%  |
| GDM     | 18        | 15.79%  |
| SDDM    | 16        | 14.04%  |
| LightDM | 14        | 12.28%  |
| TDM     | 4         | 3.51%   |
| GDM3    | 4         | 3.51%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 46        | 41.44%  |
| Unknown | 13        | 11.71%  |
| fr_FR   | 8         | 7.21%   |
| de_LU   | 8         | 7.21%   |
| en_GB   | 7         | 6.31%   |
| de_DE   | 6         | 5.41%   |
| C       | 5         | 4.5%    |
| fr_LU   | 4         | 3.6%    |
| es_ES   | 3         | 2.7%    |
| nl_NL   | 2         | 1.8%    |
| unm_US  | 1         | 0.9%    |
| pt_PT   | 1         | 0.9%    |
| pt_BR   | 1         | 0.9%    |
| POSIX   | 1         | 0.9%    |
| lb_LU   | 1         | 0.9%    |
| it_IT   | 1         | 0.9%    |
| hr_HR   | 1         | 0.9%    |
| en_IE   | 1         | 0.9%    |
| de_CH   | 1         | 0.9%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 57        | 51.82%  |
| BIOS | 53        | 48.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 81        | 74.31%  |
| Overlay | 9         | 8.26%   |
| Btrfs   | 9         | 8.26%   |
| Xfs     | 5         | 4.59%   |
| Unknown | 4         | 3.67%   |
| Zfs     | 1         | 0.92%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 58        | 53.21%  |
| GPT     | 44        | 40.37%  |
| MBR     | 7         | 6.42%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 99        | 90%     |
| Yes       | 11        | 10%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 79        | 71.82%  |
| Yes       | 31        | 28.18%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 18        | 16.51%  |
| Hewlett-Packard     | 15        | 13.76%  |
| Lenovo              | 12        | 11.01%  |
| Dell                | 8         | 7.34%   |
| Sony                | 5         | 4.59%   |
| Intel               | 5         | 4.59%   |
| Gigabyte Technology | 5         | 4.59%   |
| Apple               | 5         | 4.59%   |
| MSI                 | 4         | 3.67%   |
| Medion              | 4         | 3.67%   |
| Acer                | 4         | 3.67%   |
| Wortmann AG         | 3         | 2.75%   |
| ASRock              | 3         | 2.75%   |
| win element         | 2         | 1.83%   |
| Samsung Electronics | 2         | 1.83%   |
| Fujitsu             | 2         | 1.83%   |
| Clevo               | 2         | 1.83%   |
| YJKC                | 1         | 0.92%   |
| TUXEDO              | 1         | 0.92%   |
| Toshiba             | 1         | 0.92%   |
| Timi                | 1         | 0.92%   |
| Packard Bell        | 1         | 0.92%   |
| Microsoft           | 1         | 0.92%   |
| LattePanda          | 1         | 0.92%   |
| JWIPC               | 1         | 0.92%   |
| HUAWEI              | 1         | 0.92%   |
| Foxconn             | 1         | 0.92%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| ASUS All Series                          | 3         | 2.75%   |
| win element MoreFine S500+               | 2         | 1.83%   |
| Dell Precision M3800                     | 2         | 1.83%   |
| YJKC vBook                               | 1         | 0.92%   |
| Wortmann AG TERRA_MOBILE_1749            | 1         | 0.92%   |
| Wortmann AG TERRA_MOBILE_1541H           | 1         | 0.92%   |
| Wortmann AG MS-1727                      | 1         | 0.92%   |
| TUXEDO Pulse 14 Gen1                     | 1         | 0.92%   |
| Toshiba Satellite C55-A-1N0              | 1         | 0.92%   |
| Timi RedmiBook 14 II                     | 1         | 0.92%   |
| Sony VPCP11S1R                           | 1         | 0.92%   |
| Sony VPCEB2E1E                           | 1         | 0.92%   |
| Sony VPCCA4E1E                           | 1         | 0.92%   |
| Sony VGN-NS30E_S                         | 1         | 0.92%   |
| Sony SVF1421E2EW                         | 1         | 0.92%   |
| Samsung Galaxy TabPro S LTE              | 1         | 0.92%   |
| Samsung 950QDB                           | 1         | 0.92%   |
| Packard Bell EasyNote TJ65               | 1         | 0.92%   |
| MSI MS-7C80                              | 1         | 0.92%   |
| MSI MS-7C08                              | 1         | 0.92%   |
| MSI MS-7578                              | 1         | 0.92%   |
| MSI GF72 8RD                             | 1         | 0.92%   |
| Microsoft Surface Book 2                 | 1         | 0.92%   |
| Medion P961x                             | 1         | 0.92%   |
| Medion P6685 MD61138                     | 1         | 0.92%   |
| Medion MS-7848                           | 1         | 0.92%   |
| Medion E4254 MD62100                     | 1         | 0.92%   |
| Lenovo ThinkPad X1 Carbon 7th 20QDCTO1WW | 1         | 0.92%   |
| Lenovo ThinkPad T590 20N4CTO1WW          | 1         | 0.92%   |
| Lenovo ThinkPad T490 20N3S5DV0S          | 1         | 0.92%   |
| Lenovo ThinkPad T480s 20L7001PFR         | 1         | 0.92%   |
| Lenovo ThinkPad T470s W10DG 20JTS0R800   | 1         | 0.92%   |
| Lenovo ThinkPad T440p 20AWS24B00         | 1         | 0.92%   |
| Lenovo ThinkPad P1 Gen 2 20QTCTO1WW      | 1         | 0.92%   |
| Lenovo ThinkPad L15 Gen 1 20U8S0AH00     | 1         | 0.92%   |
| Lenovo ThinkPad L15 Gen 1 20U7S05B00     | 1         | 0.92%   |
| Lenovo ThinkCentre M910s 10MKS02N04      | 1         | 0.92%   |
| Lenovo IdeaPad 330-15ICH 81FK            | 1         | 0.92%   |
| Lenovo G50-70 20351                      | 1         | 0.92%   |
| LattePanda 3 Delta                       | 1         | 0.92%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 9         | 8.26%   |
| HP EliteBook          | 4         | 3.67%   |
| Dell Precision        | 4         | 3.67%   |
| ASUS PRIME            | 4         | 3.67%   |
| HP ENVY               | 3         | 2.75%   |
| ASUS All              | 3         | 2.75%   |
| Acer Aspire           | 3         | 2.75%   |
| Wortmann AG TERRA     | 2         | 1.83%   |
| win element MoreFine  | 2         | 1.83%   |
| HP ProBook            | 2         | 1.83%   |
| HP Compaq             | 2         | 1.83%   |
| Dell XPS              | 2         | 1.83%   |
| ASUS VivoBook         | 2         | 1.83%   |
| ASUS TUF              | 2         | 1.83%   |
| ASUS ROG              | 2         | 1.83%   |
| YJKC vBook            | 1         | 0.92%   |
| Wortmann AG MS-1727   | 1         | 0.92%   |
| TUXEDO Pulse          | 1         | 0.92%   |
| Toshiba Satellite     | 1         | 0.92%   |
| Timi RedmiBook        | 1         | 0.92%   |
| Sony VPCP11S1R        | 1         | 0.92%   |
| Sony VPCEB2E1E        | 1         | 0.92%   |
| Sony VPCCA4E1E        | 1         | 0.92%   |
| Sony VGN-NS30E        | 1         | 0.92%   |
| Sony SVF1421E2EW      | 1         | 0.92%   |
| Samsung Galaxy        | 1         | 0.92%   |
| Samsung 950QDB        | 1         | 0.92%   |
| Packard Bell EasyNote | 1         | 0.92%   |
| MSI MS-7C80           | 1         | 0.92%   |
| MSI MS-7C08           | 1         | 0.92%   |
| MSI MS-7578           | 1         | 0.92%   |
| MSI GF72              | 1         | 0.92%   |
| Microsoft Surface     | 1         | 0.92%   |
| Medion P961x          | 1         | 0.92%   |
| Medion P6685          | 1         | 0.92%   |
| Medion MS-7848        | 1         | 0.92%   |
| Medion E4254          | 1         | 0.92%   |
| Lenovo ThinkCentre    | 1         | 0.92%   |
| Lenovo IdeaPad        | 1         | 0.92%   |
| Lenovo G50-70         | 1         | 0.92%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 14        | 12.84%  |
| 2018 | 14        | 12.84%  |
| 2017 | 11        | 10.09%  |
| 2013 | 11        | 10.09%  |
| 2020 | 10        | 9.17%   |
| 2014 | 9         | 8.26%   |
| 2010 | 9         | 8.26%   |
| 2021 | 6         | 5.5%    |
| 2016 | 6         | 5.5%    |
| 2015 | 5         | 4.59%   |
| 2011 | 5         | 4.59%   |
| 2012 | 3         | 2.75%   |
| 2009 | 3         | 2.75%   |
| 2022 | 1         | 0.92%   |
| 2008 | 1         | 0.92%   |
| 2007 | 1         | 0.92%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 67        | 61.47%  |
| Desktop     | 33        | 30.28%  |
| Mini pc     | 4         | 3.67%   |
| Tablet      | 2         | 1.83%   |
| Convertible | 2         | 1.83%   |
| All in one  | 1         | 0.92%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 100       | 91.74%  |
| Enabled  | 9         | 8.26%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 109       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 33        | 30.28%  |
| 8.01-16.0   | 23        | 21.1%   |
| 4.01-8.0    | 21        | 19.27%  |
| 3.01-4.0    | 16        | 14.68%  |
| 32.01-64.0  | 9         | 8.26%   |
| 64.01-256.0 | 3         | 2.75%   |
| 1.01-2.0    | 2         | 1.83%   |
| 24.01-32.0  | 1         | 0.92%   |
| 2.01-3.0    | 1         | 0.92%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 34        | 30.09%  |
| 1.01-2.0   | 32        | 28.32%  |
| 4.01-8.0   | 20        | 17.7%   |
| 3.01-4.0   | 13        | 11.5%   |
| 8.01-16.0  | 9         | 7.96%   |
| 0.51-1.0   | 3         | 2.65%   |
| 24.01-32.0 | 1         | 0.88%   |
| 0.01-0.5   | 1         | 0.88%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 63        | 56.76%  |
| 2      | 28        | 25.23%  |
| 3      | 11        | 9.91%   |
| 4      | 4         | 3.6%    |
| 5      | 2         | 1.8%    |
| 0      | 2         | 1.8%    |
| 7      | 1         | 0.9%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 69        | 63.3%   |
| Yes       | 40        | 36.7%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 93        | 85.32%  |
| No        | 16        | 14.68%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 90        | 81.82%  |
| No        | 20        | 18.18%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 75        | 68.81%  |
| No        | 34        | 31.19%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Computers | Percent |
|------------|-----------|---------|
| Luxembourg | 109       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Luxembourg        | 55        | 47.83%  |
| Strassen          | 9         | 7.83%   |
| Useldange         | 3         | 2.61%   |
| Schifflange       | 3         | 2.61%   |
| Schieren          | 3         | 2.61%   |
| Ehnen             | 3         | 2.61%   |
| Differdange       | 3         | 2.61%   |
| Wormeldange       | 2         | 1.74%   |
| Steinfort         | 2         | 1.74%   |
| Sanem             | 2         | 1.74%   |
| Esch-sur-Alzette  | 2         | 1.74%   |
| Bettange-sur-Mess | 2         | 1.74%   |
| Wiltz             | 1         | 0.87%   |
| Wecker            | 1         | 0.87%   |
| Wasserbillig      | 1         | 0.87%   |
| Vianden           | 1         | 0.87%   |
| Steinsel          | 1         | 0.87%   |
| Soleuvre          | 1         | 0.87%   |
| Roeser            | 1         | 0.87%   |
| Pontpierre        | 1         | 0.87%   |
| PerlГ©          | 1         | 0.87%   |
| Oberpallen        | 1         | 0.87%   |
| Niederanven       | 1         | 0.87%   |
| Leudelange        | 1         | 0.87%   |
| Kopstal           | 1         | 0.87%   |
| Junglinster       | 1         | 0.87%   |
| Itzig             | 1         | 0.87%   |
| Hunsdorf          | 1         | 0.87%   |
| Hosingen          | 1         | 0.87%   |
| Hesperange        | 1         | 0.87%   |
| Ettelbruck        | 1         | 0.87%   |
| Echternach        | 1         | 0.87%   |
| Diekirch          | 1         | 0.87%   |
| Bourscheid        | 1         | 0.87%   |
| Bettembourg       | 1         | 0.87%   |
| Belvaux           | 1         | 0.87%   |
| Beckerich         | 1         | 0.87%   |
| Aspelt            | 1         | 0.87%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 38        | 51     | 24.52%  |
| Seagate                   | 21        | 28     | 13.55%  |
| WDC                       | 18        | 28     | 11.61%  |
| Toshiba                   | 11        | 14     | 7.1%    |
| Crucial                   | 10        | 14     | 6.45%   |
| SanDisk                   | 9         | 12     | 5.81%   |
| Kingston                  | 8         | 11     | 5.16%   |
| Apple                     | 5         | 6      | 3.23%   |
| SK hynix                  | 3         | 3      | 1.94%   |
| Hitachi                   | 3         | 4      | 1.94%   |
| Transcend                 | 2         | 2      | 1.29%   |
| LITEONIT                  | 2         | 2      | 1.29%   |
| LITEON                    | 2         | 2      | 1.29%   |
| Intenso                   | 2         | 3      | 1.29%   |
| Intel                     | 2         | 2      | 1.29%   |
| HGST                      | 2         | 3      | 1.29%   |
| Unknown                   | 1         | 2      | 0.65%   |
| Union Memory (Shenzhen)   | 1         | 1      | 0.65%   |
| TCSUNBOW                  | 1         | 1      | 0.65%   |
| SABRENT                   | 1         | 1      | 0.65%   |
| Phison                    | 1         | 1      | 0.65%   |
| PHD 3.0                   | 1         | 1      | 0.65%   |
| OCZ                       | 1         | 1      | 0.65%   |
| Micron/Crucial Technology | 1         | 1      | 0.65%   |
| Micron Technology         | 1         | 2      | 0.65%   |
| Maxtor                    | 1         | 2      | 0.65%   |
| LaCie                     | 1         | 1      | 0.65%   |
| KingSpec                  | 1         | 1      | 0.65%   |
| KingDian                  | 1         | 1      | 0.65%   |
| Inateck                   | 1         | 1      | 0.65%   |
| Gigabyte Technology       | 1         | 1      | 0.65%   |
| FORESEE                   | 1         | 1      | 0.65%   |
| A-DATA Technology         | 1         | 1      | 0.65%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Seagate Expansion 2TB                  | 3         | 1.7%    |
| Samsung SSD 840 EVO 250GB              | 3         | 1.7%    |
| WDC WD10JPVX-22JC3T0 1TB               | 2         | 1.14%   |
| Toshiba MQ01ABF050 500GB               | 2         | 1.14%   |
| Seagate ST1000LM035-1RK172 1TB         | 2         | 1.14%   |
| SanDisk SD8SN8U128G1122 128GB SSD      | 2         | 1.14%   |
| SanDisk NVMe SSD Drive 1TB             | 2         | 1.14%   |
| Samsung SSD 860 QVO 1TB                | 2         | 1.14%   |
| Samsung SSD 860 EVO 250GB              | 2         | 1.14%   |
| Samsung SSD 850 EVO 250GB              | 2         | 1.14%   |
| Samsung SP2504C 250GB                  | 2         | 1.14%   |
| Samsung MZVLW256HEHP-000L7 256GB       | 2         | 1.14%   |
| LITEONIT LMT-256L9M-11 MSATA 256GB SSD | 2         | 1.14%   |
| Kingston SA400S37240G 240GB SSD        | 2         | 1.14%   |
| Crucial CT240BX500SSD1 240GB           | 2         | 1.14%   |
| Crucial CT1000P2SSD8 1TB               | 2         | 1.14%   |
| WDC WDS500G3X0C-00SJG0 500GB           | 1         | 0.57%   |
| WDC WDS250G2B0B-00YS70 250GB SSD       | 1         | 0.57%   |
| WDC WD5000AAVS-00ZTB0 500GB            | 1         | 0.57%   |
| WDC WD5000AAKS-60Z1A0 500GB            | 1         | 0.57%   |
| WDC WD40EZRZ-75GXCB0 4TB               | 1         | 0.57%   |
| WDC WD4000FYYZ-01UL1B2 4TB             | 1         | 0.57%   |
| WDC WD3200LPCX-00VHAT0 320GB           | 1         | 0.57%   |
| WDC WD3001FFSX-68JNUN0 3TB             | 1         | 0.57%   |
| WDC WD3000GLFS-01F8U0 304GB            | 1         | 0.57%   |
| WDC WD20EFAX-68FB5N0 2TB               | 1         | 0.57%   |
| WDC WD141KRYZ-01C66B0 14TB             | 1         | 0.57%   |
| WDC WD10SPZX-17Z10T0 1TB               | 1         | 0.57%   |
| WDC WD10SPCX-60HWST0 1TB               | 1         | 0.57%   |
| WDC WD10EZRX-00A8LB0 1TB               | 1         | 0.57%   |
| WDC WD10EZEX-60ZF5A0 1TB               | 1         | 0.57%   |
| WDC WD10EZEX-08WN4A0 1TB               | 1         | 0.57%   |
| WDC WD10EARS-00Y5B1 1TB                | 1         | 0.57%   |
| WDC WD10EACS-00D6B1 1TB                | 1         | 0.57%   |
| WDC WD1001FALS-00J7B0 1TB              | 1         | 0.57%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB   | 1         | 0.57%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB     | 1         | 0.57%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB   | 1         | 0.57%   |
| Unknown MMC Card  64GB                 | 1         | 0.57%   |
| Unknown DA4064  64GB                   | 1         | 0.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 26     | 35.19%  |
| WDC                 | 13        | 23     | 24.07%  |
| Toshiba             | 8         | 11     | 14.81%  |
| Samsung Electronics | 3         | 3      | 5.56%   |
| Hitachi             | 3         | 4      | 5.56%   |
| HGST                | 2         | 3      | 3.7%    |
| Apple               | 2         | 2      | 3.7%    |
| SABRENT             | 1         | 1      | 1.85%   |
| PHD 3.0             | 1         | 1      | 1.85%   |
| Intenso             | 1         | 1      | 1.85%   |
| Inateck             | 1         | 1      | 1.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 24        | 32     | 38.71%  |
| SanDisk             | 8         | 9      | 12.9%   |
| Crucial             | 8         | 12     | 12.9%   |
| Kingston            | 4         | 7      | 6.45%   |
| Transcend           | 2         | 2      | 3.23%   |
| LITEONIT            | 2         | 2      | 3.23%   |
| LITEON              | 2         | 2      | 3.23%   |
| WDC                 | 1         | 1      | 1.61%   |
| TCSUNBOW            | 1         | 1      | 1.61%   |
| SK hynix            | 1         | 1      | 1.61%   |
| OCZ                 | 1         | 1      | 1.61%   |
| Micron Technology   | 1         | 2      | 1.61%   |
| Maxtor              | 1         | 2      | 1.61%   |
| KingSpec            | 1         | 1      | 1.61%   |
| KingDian            | 1         | 1      | 1.61%   |
| Intenso             | 1         | 2      | 1.61%   |
| FORESEE             | 1         | 1      | 1.61%   |
| Apple               | 1         | 1      | 1.61%   |
| A-DATA Technology   | 1         | 1      | 1.61%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 51        | 81     | 35.66%  |
| HDD     | 49        | 76     | 34.27%  |
| NVMe    | 39        | 43     | 27.27%  |
| MMC     | 2         | 3      | 1.4%    |
| Unknown | 2         | 2      | 1.4%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 79        | 148    | 61.24%  |
| NVMe | 39        | 43     | 30.23%  |
| SAS  | 9         | 11     | 6.98%   |
| MMC  | 2         | 3      | 1.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 62        | 94     | 55.86%  |
| 0.51-1.0   | 34        | 46     | 30.63%  |
| 1.01-2.0   | 8         | 9      | 7.21%   |
| 3.01-4.0   | 4         | 4      | 3.6%    |
| 2.01-3.0   | 2         | 3      | 1.8%    |
| 10.01-20.0 | 1         | 1      | 0.9%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 31        | 28.18%  |
| 251-500        | 22        | 20%     |
| 501-1000       | 15        | 13.64%  |
| Unknown        | 10        | 9.09%   |
| 1001-2000      | 9         | 8.18%   |
| More than 3000 | 7         | 6.36%   |
| 2001-3000      | 5         | 4.55%   |
| 1-20           | 5         | 4.55%   |
| 51-100         | 5         | 4.55%   |
| 21-50          | 1         | 0.91%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 39        | 34.82%  |
| 101-250        | 17        | 15.18%  |
| 21-50          | 16        | 14.29%  |
| 51-100         | 10        | 8.93%   |
| Unknown        | 10        | 8.93%   |
| 501-1000       | 8         | 7.14%   |
| 251-500        | 6         | 5.36%   |
| 2001-3000      | 3         | 2.68%   |
| 1001-2000      | 2         | 1.79%   |
| More than 3000 | 1         | 0.89%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABF050 500GB              | 2         | 2      | 40%     |
| Toshiba MK2555GSX 250GB               | 1         | 1      | 20%     |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 20%     |
| Crucial CT128MX100SSD1 128GB          | 1         | 2      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Toshiba  | 3         | 3      | 60%     |
| SK hynix | 1         | 1      | 20%     |
| Crucial  | 1         | 2      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 3         | 3      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 60%     |
| SSD  | 2         | 3      | 40%     |

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
| Detected | 58        | 116    | 50.88%  |
| Works    | 51        | 83     | 44.74%  |
| Malfunc  | 5         | 6      | 4.39%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 77        | 57.04%  |
| AMD                          | 16        | 11.85%  |
| Samsung Electronics          | 15        | 11.11%  |
| SanDisk                      | 7         | 5.19%   |
| Kingston Technology Company  | 4         | 2.96%   |
| Toshiba America Info Systems | 3         | 2.22%   |
| Micron/Crucial Technology    | 3         | 2.22%   |
| Phison Electronics           | 2         | 1.48%   |
| Marvell Technology Group     | 2         | 1.48%   |
| Apple                        | 2         | 1.48%   |
| Union Memory (Shenzhen)      | 1         | 0.74%   |
| SK hynix                     | 1         | 0.74%   |
| Seagate Technology           | 1         | 0.74%   |
| ASMedia Technology           | 1         | 0.74%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 14        | 9.59%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 12        | 8.22%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 9         | 6.16%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 6         | 4.11%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 5         | 3.42%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 5         | 3.42%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 4         | 2.74%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 2.74%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4         | 2.74%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 2.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 4         | 2.74%   |
| AMD 400 Series Chipset SATA Controller                                           | 4         | 2.74%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 2.05%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 2.05%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 2.05%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 1.37%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 2         | 1.37%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 1.37%   |
| Phison E12 NVMe Controller                                                       | 2         | 1.37%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 2         | 1.37%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 1.37%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 1.37%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 1.37%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 1.37%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 2         | 1.37%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 1.37%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 0.68%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.68%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 0.68%   |
| Seagate FireCuda 520 SSD                                                         | 1         | 0.68%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 0.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.68%   |
| Samsung Electronics Non-Volatile memory controller                               | 1         | 0.68%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 1         | 0.68%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                       | 1         | 0.68%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                        | 1         | 0.68%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.68%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 1         | 0.68%   |
| Kingston Company KC2000 NVMe SSD                                                 | 1         | 0.68%   |
| Kingston Company A2000 NVMe SSD                                                  | 1         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 84        | 62.22%  |
| NVMe | 40        | 29.63%  |
| IDE  | 6         | 4.44%   |
| RAID | 5         | 3.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 89        | 81.65%  |
| AMD    | 20        | 18.35%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz           | 4         | 3.67%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 3         | 2.75%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 2         | 1.83%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 2         | 1.83%   |
| Intel Core i7-4702HQ CPU @ 2.20GHz          | 2         | 1.83%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 2         | 1.83%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 2         | 1.83%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 2         | 1.83%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2         | 1.83%   |
| AMD Ryzen 9 5900HX with Radeon Graphics     | 2         | 1.83%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2         | 1.83%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.92%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 0.92%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 0.92%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 1         | 0.92%   |
| Intel Pentium CPU P6000 @ 1.87GHz           | 1         | 0.92%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 1         | 0.92%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 1         | 0.92%   |
| Intel Pentium CPU 987 @ 1.50GHz             | 1         | 0.92%   |
| Intel Core m5-6Y54 CPU @ 1.10GHz            | 1         | 0.92%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz            | 1         | 0.92%   |
| Intel Core i9-9880H CPU @ 2.30GHz           | 1         | 0.92%   |
| Intel Core i7-9700KF CPU @ 3.60GHz          | 1         | 0.92%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 0.92%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 0.92%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.92%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1         | 0.92%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 0.92%   |
| Intel Core i7-6800K CPU @ 3.40GHz           | 1         | 0.92%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 0.92%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 0.92%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 0.92%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1         | 0.92%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 0.92%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1         | 0.92%   |
| Intel Core i7-4712MQ CPU @ 2.30GHz          | 1         | 0.92%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz          | 1         | 0.92%   |
| Intel Core i7-3940XM CPU @ 3.00GHz          | 1         | 0.92%   |
| Intel Core i7-3840QM CPU @ 2.80GHz          | 1         | 0.92%   |
| Intel Core i7-10700K CPU @ 3.80GHz          | 1         | 0.92%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 30        | 27.52%  |
| Intel Core i5           | 26        | 23.85%  |
| Intel Core i3           | 9         | 8.26%   |
| AMD Ryzen 5             | 6         | 5.5%    |
| Other                   | 4         | 3.67%   |
| Intel Pentium           | 4         | 3.67%   |
| Intel Celeron           | 4         | 3.67%   |
| AMD Ryzen 9             | 4         | 3.67%   |
| Intel Pentium Dual-Core | 3         | 2.75%   |
| AMD Ryzen 7             | 3         | 2.75%   |
| Intel Core 2 Quad       | 2         | 1.83%   |
| AMD Ryzen 7 PRO         | 2         | 1.83%   |
| Intel Pentium Silver    | 1         | 0.92%   |
| Intel Core m5           | 1         | 0.92%   |
| Intel Core m3           | 1         | 0.92%   |
| Intel Core i9           | 1         | 0.92%   |
| Intel Core 2 Duo        | 1         | 0.92%   |
| Intel Core 2            | 1         | 0.92%   |
| Intel Atom              | 1         | 0.92%   |
| AMD Ryzen 5 PRO         | 1         | 0.92%   |
| AMD Phenom II X4        | 1         | 0.92%   |
| AMD FX                  | 1         | 0.92%   |
| AMD E2                  | 1         | 0.92%   |
| AMD Athlon II X4        | 1         | 0.92%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 41        | 37.61%  |
| 2       | 40        | 36.7%   |
| 8       | 12        | 11.01%  |
| 6       | 11        | 10.09%  |
| 12      | 2         | 1.83%   |
| 1       | 2         | 1.83%   |
| Unknown | 1         | 0.92%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 109       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 82        | 75.23%  |
| 1       | 26        | 23.85%  |
| Unknown | 1         | 0.92%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 108       | 99.08%  |
| 32-bit         | 1         | 0.92%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 18.92%  |
| 0x306c3    | 12        | 10.81%  |
| 0x40651    | 5         | 4.5%    |
| 0x206a7    | 5         | 4.5%    |
| 0x906e9    | 4         | 3.6%    |
| 0x806ea    | 4         | 3.6%    |
| 0x406e3    | 4         | 3.6%    |
| 0x1067a    | 4         | 3.6%    |
| 0x806eb    | 3         | 2.7%    |
| 0x506e3    | 3         | 2.7%    |
| 0x306d4    | 3         | 2.7%    |
| 0x20655    | 3         | 2.7%    |
| 0xa0655    | 2         | 1.8%    |
| 0x906ed    | 2         | 1.8%    |
| 0x806ec    | 2         | 1.8%    |
| 0x706a1    | 2         | 1.8%    |
| 0x306a9    | 2         | 1.8%    |
| 0x10677    | 2         | 1.8%    |
| 0x0a50000c | 2         | 1.8%    |
| 0x08701021 | 2         | 1.8%    |
| 0x08701013 | 2         | 1.8%    |
| 0x08600106 | 2         | 1.8%    |
| 0x08600103 | 2         | 1.8%    |
| 0xa0671    | 1         | 0.9%    |
| 0x906ea    | 1         | 0.9%    |
| 0x906c0    | 1         | 0.9%    |
| 0x806e9    | 1         | 0.9%    |
| 0x806d1    | 1         | 0.9%    |
| 0x806c1    | 1         | 0.9%    |
| 0x6f6      | 1         | 0.9%    |
| 0x406f1    | 1         | 0.9%    |
| 0x20652    | 1         | 0.9%    |
| 0x106c2    | 1         | 0.9%    |
| 0x0a201009 | 1         | 0.9%    |
| 0x08600104 | 1         | 0.9%    |
| 0x08108102 | 1         | 0.9%    |
| 0x0810100b | 1         | 0.9%    |
| 0x0800820d | 1         | 0.9%    |
| 0x06006705 | 1         | 0.9%    |
| 0x010000db | 1         | 0.9%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 25        | 22.94%  |
| Haswell       | 19        | 17.43%  |
| Zen 2         | 10        | 9.17%   |
| Skylake       | 10        | 9.17%   |
| Penryn        | 6         | 5.5%    |
| SandyBridge   | 5         | 4.59%   |
| Westmere      | 4         | 3.67%   |
| Broadwell     | 4         | 3.67%   |
| Zen 3         | 3         | 2.75%   |
| IvyBridge     | 3         | 2.75%   |
| CometLake     | 3         | 2.75%   |
| Zen+          | 2         | 1.83%   |
| TigerLake     | 2         | 1.83%   |
| K10           | 2         | 1.83%   |
| Icelake       | 2         | 1.83%   |
| Goldmont plus | 2         | 1.83%   |
| Zen           | 1         | 0.92%   |
| Piledriver    | 1         | 0.92%   |
| Goldmont      | 1         | 0.92%   |
| Excavator     | 1         | 0.92%   |
| Core          | 1         | 0.92%   |
| Bonnell       | 1         | 0.92%   |
| Unknown       | 1         | 0.92%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 73        | 55.3%   |
| Nvidia | 39        | 29.55%  |
| AMD    | 20        | 15.15%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 8         | 5.97%   |
| Intel UHD Graphics 620                                                      | 6         | 4.48%   |
| AMD Renoir                                                                  | 6         | 4.48%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 5         | 3.73%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 5         | 3.73%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 5         | 3.73%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 4         | 2.99%   |
| Intel HD Graphics 530                                                       | 4         | 2.99%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4         | 2.99%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 3         | 2.24%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 3         | 2.24%   |
| Nvidia GP108M [GeForce MX250]                                               | 2         | 1.49%   |
| Nvidia GP108M [GeForce MX150]                                               | 2         | 1.49%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2         | 1.49%   |
| Nvidia GK107GLM [Quadro K1100M]                                             | 2         | 1.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 1.49%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 2         | 1.49%   |
| Intel Iris Plus Graphics 640                                                | 2         | 1.49%   |
| Intel HD Graphics 5500                                                      | 2         | 1.49%   |
| Intel HD Graphics 515                                                       | 2         | 1.49%   |
| AMD Cezanne                                                                 | 2         | 1.49%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 0.75%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                               | 1         | 0.75%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                       | 1         | 0.75%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1         | 0.75%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1         | 0.75%   |
| Nvidia GT218 [NVS 300]                                                      | 1         | 0.75%   |
| Nvidia GT218 [GeForce G210]                                                 | 1         | 0.75%   |
| Nvidia GT216M [GeForce GT 330M]                                             | 1         | 0.75%   |
| Nvidia GT215M [GeForce GTS 250M]                                            | 1         | 0.75%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1         | 0.75%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 0.75%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1         | 0.75%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1         | 0.75%   |
| Nvidia GM108M [GeForce 840M]                                                | 1         | 0.75%   |
| Nvidia GM107M [GeForce GTX 950M]                                            | 1         | 0.75%   |
| Nvidia GM107M [GeForce GTX 850M]                                            | 1         | 0.75%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1         | 0.75%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1         | 0.75%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1         | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 49        | 44.95%  |
| 1 x Nvidia     | 20        | 18.35%  |
| Intel + Nvidia | 20        | 18.35%  |
| 1 x AMD        | 15        | 13.76%  |
| Intel + AMD    | 3         | 2.75%   |
| 2 x AMD        | 2         | 1.83%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 84        | 76.36%  |
| Proprietary | 21        | 19.09%  |
| Unknown     | 5         | 4.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 69        | 63.3%   |
| 3.01-4.0   | 10        | 9.17%   |
| 0.01-0.5   | 10        | 9.17%   |
| 1.01-2.0   | 9         | 8.26%   |
| 0.51-1.0   | 8         | 7.34%   |
| 8.01-16.0  | 2         | 1.83%   |
| 5.01-6.0   | 1         | 0.92%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 19        | 15.57%  |
| Chimei Innolux          | 16        | 13.11%  |
| LG Display              | 14        | 11.48%  |
| AU Optronics            | 8         | 6.56%   |
| Hewlett-Packard         | 6         | 4.92%   |
| Goldstar                | 6         | 4.92%   |
| AOC                     | 6         | 4.92%   |
| Sharp                   | 5         | 4.1%    |
| Iiyama                  | 5         | 4.1%    |
| Dell                    | 5         | 4.1%    |
| Apple                   | 5         | 4.1%    |
| BOE                     | 4         | 3.28%   |
| Philips                 | 3         | 2.46%   |
| Medion                  | 3         | 2.46%   |
| Chi Mei Optoelectronics | 3         | 2.46%   |
| BenQ                    | 2         | 1.64%   |
| Videoseven              | 1         | 0.82%   |
| Sony                    | 1         | 0.82%   |
| PAR                     | 1         | 0.82%   |
| PANDA                   | 1         | 0.82%   |
| Panasonic               | 1         | 0.82%   |
| MSI                     | 1         | 0.82%   |
| Lenovo                  | 1         | 0.82%   |
| Fujitsu Siemens         | 1         | 0.82%   |
| Eizo                    | 1         | 0.82%   |
| Belinea                 | 1         | 0.82%   |
| Aosiman                 | 1         | 0.82%   |
| Ancor Communications    | 1         | 0.82%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 2         | 1.63%   |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch               | 2         | 1.63%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 2         | 1.63%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 2         | 1.63%   |
| AOC 2250W AOC2250 1920x1080 477x268mm 21.5-inch                       | 2         | 1.63%   |
| Videoseven L27ADS IGM2700 1920x1080 598x336mm 27.0-inch               | 1         | 0.81%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                 | 1         | 0.81%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch               | 1         | 0.81%   |
| Samsung Electronics T24B350 SAM093E 1920x1080 531x299mm 24.0-inch     | 1         | 0.81%   |
| Samsung Electronics SyncMaster SAM0612 1920x1080 604x342mm 27.3-inch  | 1         | 0.81%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch   | 1         | 0.81%   |
| Samsung Electronics SMT27A950 SAM080F 1920x1080 598x336mm 27.0-inch   | 1         | 0.81%   |
| Samsung Electronics SM2333T SAM0737 1920x1080 510x290mm 23.1-inch     | 1         | 0.81%   |
| Samsung Electronics S27D390 SAM0B67 1920x1080 598x336mm 27.0-inch     | 1         | 0.81%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.81%   |
| Samsung Electronics LCD Monitor U28E590 3840x2160                     | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC444E 1600x900 310x174mm 14.0-inch  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC5844 1920x1080 344x194mm 15.5-inch | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 410x230mm 18.5-inch | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 700x390mm 31.5-inch | 1         | 0.81%   |
| Samsung Electronics C27R50x SAM0F9D 1920x1080 598x336mm 27.0-inch     | 1         | 0.81%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1         | 0.81%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch     | 1         | 0.81%   |
| Philips PHL BDM3270 PHL08E7 2560x1440 708x398mm 32.0-inch             | 1         | 0.81%   |
| Philips PHL 275C5 PHLC0E4 1920x1080 598x336mm 27.0-inch               | 1         | 0.81%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch               | 1         | 0.81%   |
| PAR LED1920X1080 PAR9C63 1920x1080 710x400mm 32.1-inch                | 1         | 0.81%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 0.81%   |
| Panasonic VVX14P048M00 MEI96A2 3000x2000 285x190mm 13.5-inch          | 1         | 0.81%   |
| MSI MPG27CQ MSI3FA3 2560x1440 600x340mm 27.2-inch                     | 1         | 0.81%   |
| Medion Medion23.6 PC MEDB603 1920x1080 477x268mm 21.5-inch            | 1         | 0.81%   |
| Medion MD 20122 MED3601 1680x1050 474x296mm 22.0-inch                 | 1         | 0.81%   |
| Medion 42FPDEUDA1 MED222E 1920x1080                                   | 1         | 0.81%   |
| LG Display LP156WH2-TLE1 LGDCF01 1366x768 344x194mm 15.5-inch         | 1         | 0.81%   |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch          | 1         | 0.81%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 58        | 51.33%  |
| 1366x768 (WXGA)    | 15        | 13.27%  |
| 3840x2160 (4K)     | 11        | 9.73%   |
| 2560x1440 (QHD)    | 7         | 6.19%   |
| 1600x900 (HD+)     | 4         | 3.54%   |
| 1680x1050 (WSXGA+) | 3         | 2.65%   |
| 3200x1800 (QHD+)   | 2         | 1.77%   |
| 1920x1200 (WUXGA)  | 2         | 1.77%   |
| 1440x900 (WXGA+)   | 2         | 1.77%   |
| 1360x768           | 2         | 1.77%   |
| 1280x1024 (SXGA)   | 2         | 1.77%   |
| 3072x1920          | 1         | 0.88%   |
| 2880x1800          | 1         | 0.88%   |
| 2560x1600          | 1         | 0.88%   |
| 1280x800 (WXGA)    | 1         | 0.88%   |
| 1024x768 (XGA)     | 1         | 0.88%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 32        | 26.23%  |
| 27      | 15        | 12.3%   |
| 17      | 11        | 9.02%   |
| 14      | 11        | 9.02%   |
| 13      | 10        | 8.2%    |
| 23      | 8         | 6.56%   |
| 21      | 7         | 5.74%   |
| 24      | 6         | 4.92%   |
| Unknown | 4         | 3.28%   |
| 22      | 3         | 2.46%   |
| 72      | 2         | 1.64%   |
| 32      | 2         | 1.64%   |
| 18      | 2         | 1.64%   |
| 16      | 2         | 1.64%   |
| 59      | 1         | 0.82%   |
| 46      | 1         | 0.82%   |
| 33      | 1         | 0.82%   |
| 31      | 1         | 0.82%   |
| 25      | 1         | 0.82%   |
| 19      | 1         | 0.82%   |
| 11      | 1         | 0.82%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 48        | 40%     |
| 501-600     | 28        | 23.33%  |
| 401-500     | 12        | 10%     |
| 351-400     | 12        | 10%     |
| 201-300     | 7         | 5.83%   |
| Unknown     | 4         | 3.33%   |
| 701-800     | 3         | 2.5%    |
| 601-700     | 2         | 1.67%   |
| 1501-2000   | 2         | 1.67%   |
| 1001-1500   | 2         | 1.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 89        | 83.96%  |
| 16/10   | 12        | 11.32%  |
| 5/4     | 2         | 1.89%   |
| Unknown | 2         | 1.89%   |
| 4/3     | 1         | 0.94%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 32        | 26.23%  |
| 201-250        | 20        | 16.39%  |
| 81-90          | 16        | 13.11%  |
| 301-350        | 15        | 12.3%   |
| 121-130        | 8         | 6.56%   |
| 71-80          | 5         | 4.1%    |
| 351-500        | 4         | 3.28%   |
| Unknown        | 4         | 3.28%   |
| More than 1000 | 3         | 2.46%   |
| 251-300        | 3         | 2.46%   |
| 151-200        | 3         | 2.46%   |
| 141-150        | 3         | 2.46%   |
| 131-140        | 2         | 1.64%   |
| 51-60          | 1         | 0.82%   |
| 111-120        | 1         | 0.82%   |
| 501-1000       | 1         | 0.82%   |
| 91-100         | 1         | 0.82%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 36        | 30.25%  |
| 121-160       | 34        | 28.57%  |
| 101-120       | 28        | 23.53%  |
| 161-240       | 10        | 8.4%    |
| More than 240 | 5         | 4.2%    |
| Unknown       | 4         | 3.36%   |
| 1-50          | 2         | 1.68%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 86        | 77.48%  |
| 2     | 18        | 16.22%  |
| 0     | 5         | 4.5%    |
| 3     | 2         | 1.8%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 74        | 44.85%  |
| Realtek Semiconductor           | 45        | 27.27%  |
| Qualcomm Atheros                | 16        | 9.7%    |
| Broadcom                        | 13        | 7.88%   |
| Marvell Technology Group        | 4         | 2.42%   |
| Sierra Wireless                 | 2         | 1.21%   |
| DisplayLink                     | 2         | 1.21%   |
| TP-Link                         | 1         | 0.61%   |
| Ralink Technology               | 1         | 0.61%   |
| Qualcomm Atheros Communications | 1         | 0.61%   |
| MediaTek                        | 1         | 0.61%   |
| Lenovo                          | 1         | 0.61%   |
| JMicron Technology              | 1         | 0.61%   |
| Broadcom Limited                | 1         | 0.61%   |
| ASIX Electronics                | 1         | 0.61%   |
| Unknown                         | 1         | 0.61%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 32        | 16.24%  |
| Intel Wi-Fi 6 AX200                                                            | 11        | 5.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 2.54%   |
| Realtek RTL8125 2.5GbE Controller                                              | 5         | 2.54%   |
| Intel Wireless 8260                                                            | 5         | 2.54%   |
| Intel I211 Gigabit Network Connection                                          | 5         | 2.54%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 5         | 2.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 4         | 2.03%   |
| Intel Wireless 8265 / 8275                                                     | 4         | 2.03%   |
| Intel Wireless 7260                                                            | 4         | 2.03%   |
| Intel Wireless 3160                                                            | 3         | 1.52%   |
| Intel Ethernet Connection I219-V                                               | 3         | 1.52%   |
| Intel Ethernet Connection (2) I219-V                                           | 3         | 1.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 1.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 1.02%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 2         | 1.02%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2         | 1.02%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 2         | 1.02%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.02%   |
| Intel Wireless-AC 9260                                                         | 2         | 1.02%   |
| Intel Wireless 7265                                                            | 2         | 1.02%   |
| Intel Wireless 3165                                                            | 2         | 1.02%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 2         | 1.02%   |
| Intel Ethernet Connection I217-V                                               | 2         | 1.02%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 1.02%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 1.02%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 1.02%   |
| Intel Ethernet Connection (2) I218-V                                           | 2         | 1.02%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 2         | 1.02%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 2         | 1.02%   |
| DisplayLink Dell D3100 Docking Station                                         | 2         | 1.02%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                             | 2         | 1.02%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 2         | 1.02%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                    | 1         | 0.51%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A                            | 1         | 0.51%   |
| Sierra Wireless EM7305 Modem                                                   | 1         | 0.51%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.51%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                    | 1         | 0.51%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 0.51%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 56        | 59.57%  |
| Qualcomm Atheros                | 13        | 13.83%  |
| Broadcom                        | 10        | 10.64%  |
| Realtek Semiconductor           | 7         | 7.45%   |
| Sierra Wireless                 | 2         | 2.13%   |
| TP-Link                         | 1         | 1.06%   |
| Ralink Technology               | 1         | 1.06%   |
| Qualcomm Atheros Communications | 1         | 1.06%   |
| MediaTek                        | 1         | 1.06%   |
| Marvell Technology Group        | 1         | 1.06%   |
| Broadcom Limited                | 1         | 1.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 11        | 11.7%   |
| Intel Wireless 8260                                            | 5         | 5.32%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 5         | 5.32%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 4         | 4.26%   |
| Intel Wireless 8265 / 8275                                     | 4         | 4.26%   |
| Intel Wireless 7260                                            | 4         | 4.26%   |
| Intel Wireless 3160                                            | 3         | 3.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 2.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 2.13%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 2.13%   |
| Intel Wireless-AC 9260                                         | 2         | 2.13%   |
| Intel Wireless 7265                                            | 2         | 2.13%   |
| Intel Wireless 3165                                            | 2         | 2.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 2.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 2.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 2.13%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 2         | 2.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 2.13%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 1.06%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A            | 1         | 1.06%   |
| Sierra Wireless EM7305 Modem                                   | 1         | 1.06%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.06%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 1.06%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 1.06%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 1.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 1.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 1.06%   |
| Qualcomm Atheros AR9271 802.11n                                | 1         | 1.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 1.06%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 1.06%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1         | 1.06%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 1.06%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.06%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter            | 1         | 1.06%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 1         | 1.06%   |
| Intel WiMAX/WiFi Link 5150                                     | 1         | 1.06%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 1         | 1.06%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 1.06%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 1.06%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 1         | 1.06%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 43        | 43.43%  |
| Intel                    | 38        | 38.38%  |
| Qualcomm Atheros         | 5         | 5.05%   |
| Broadcom                 | 5         | 5.05%   |
| Marvell Technology Group | 3         | 3.03%   |
| DisplayLink              | 2         | 2.02%   |
| Lenovo                   | 1         | 1.01%   |
| JMicron Technology       | 1         | 1.01%   |
| ASIX Electronics         | 1         | 1.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 32        | 31.68%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 4.95%   |
| Realtek RTL8125 2.5GbE Controller                                              | 5         | 4.95%   |
| Intel I211 Gigabit Network Connection                                          | 5         | 4.95%   |
| Intel Ethernet Connection I219-V                                               | 3         | 2.97%   |
| Intel Ethernet Connection (2) I219-V                                           | 3         | 2.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 2.97%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2         | 1.98%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.98%   |
| Intel Ethernet Connection I217-V                                               | 2         | 1.98%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 1.98%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 1.98%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 1.98%   |
| Intel Ethernet Connection (2) I218-V                                           | 2         | 1.98%   |
| DisplayLink Dell D3100 Docking Station                                         | 2         | 1.98%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.99%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.99%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.99%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.99%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.99%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.99%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 0.99%   |
| Lenovo ThinkPad Lan                                                            | 1         | 0.99%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.99%   |
| Intel WiMAX Connection 2400m                                                   | 1         | 0.99%   |
| Intel Ethernet Controller I225-V                                               | 1         | 0.99%   |
| Intel Ethernet controller                                                      | 1         | 0.99%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.99%   |
| Intel Ethernet Connection (7) I219-V                                           | 1         | 0.99%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.99%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 0.99%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.99%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 0.99%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.99%   |
| Intel Ethernet Connection (11) I219-V                                          | 1         | 0.99%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 0.99%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 1         | 0.99%   |
| Intel 82566DC Gigabit Network Connection                                       | 1         | 0.99%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 1         | 0.99%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 1         | 0.99%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 92        | 50%     |
| WiFi     | 90        | 48.91%  |
| Modem    | 1         | 0.54%   |
| Unknown  | 1         | 0.54%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 64        | 55.65%  |
| Ethernet | 51        | 44.35%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 64        | 58.72%  |
| 1     | 40        | 36.7%   |
| 3     | 5         | 4.59%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 91        | 82.73%  |
| Yes  | 19        | 17.27%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 48        | 63.16%  |
| Foxconn / Hon Hai               | 5         | 6.58%   |
| Qualcomm Atheros Communications | 3         | 3.95%   |
| IMC Networks                    | 3         | 3.95%   |
| Cambridge Silicon Radio         | 3         | 3.95%   |
| Apple                           | 3         | 3.95%   |
| Realtek                         | 2         | 2.63%   |
| Hewlett-Packard                 | 2         | 2.63%   |
| Toshiba                         | 1         | 1.32%   |
| Realtek Semiconductor           | 1         | 1.32%   |
| Micro Star International        | 1         | 1.32%   |
| Marvell Semiconductor           | 1         | 1.32%   |
| Lite-On Technology              | 1         | 1.32%   |
| Broadcom                        | 1         | 1.32%   |
| ASUSTek Computer                | 1         | 1.32%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 19        | 25%     |
| Intel AX200 Bluetooth                                                               | 10        | 13.16%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 7         | 9.21%   |
| Intel AX201 Bluetooth                                                               | 5         | 6.58%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 3         | 3.95%   |
| Realtek Bluetooth Radio                                                             | 2         | 2.63%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 2.63%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 2.63%   |
| Intel AX210 Bluetooth                                                               | 2         | 2.63%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 2.63%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 2.63%   |
| Toshiba Bluetooth Device                                                            | 1         | 1.32%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.32%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 1         | 1.32%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 1.32%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.32%   |
| Micro Star International Motorola Bluetooth 2.1+EDR Device                          | 1         | 1.32%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 1         | 1.32%   |
| Lite-On Bluetooth Device                                                            | 1         | 1.32%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 1.32%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 1.32%   |
| IMC Networks Bluetooth Module                                                       | 1         | 1.32%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.32%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.32%   |
| Foxconn / Hon Hai BT                                                                | 1         | 1.32%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 1.32%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 1         | 1.32%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 1.32%   |
| Broadcom Bluetooth 3.0 Device                                                       | 1         | 1.32%   |
| ASUS BCM20702A0                                                                     | 1         | 1.32%   |
| Apple Bluetooth Host Controller                                                     | 1         | 1.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 89        | 62.24%  |
| AMD                            | 23        | 16.08%  |
| Nvidia                         | 21        | 14.69%  |
| Logitech                       | 2         | 1.4%    |
| www.hirestech.com 2010 REV 1.4 | 1         | 0.7%    |
| SteelSeries ApS                | 1         | 0.7%    |
| Sony                           | 1         | 0.7%    |
| Realtek Semiconductor          | 1         | 0.7%    |
| Lenovo                         | 1         | 0.7%    |
| C-Media Electronics            | 1         | 0.7%    |
| Bose                           | 1         | 0.7%    |
| Apple                          | 1         | 0.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 14        | 7.95%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 12        | 6.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 11        | 6.25%   |
| AMD Family 17h/19h HD Audio Controller                                     | 10        | 5.68%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 8         | 4.55%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 3.41%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 2.84%   |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 2.84%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 2.84%   |
| Intel 200 Series PCH HD Audio                                              | 5         | 2.84%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5         | 2.84%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 2.27%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 2.27%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 2.27%   |
| Nvidia High Definition Audio Controller                                    | 3         | 1.7%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 1.7%    |
| Intel Comet Lake PCH cAVS                                                  | 3         | 1.7%    |
| Intel Broadwell-U Audio Controller                                         | 3         | 1.7%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.7%    |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.14%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.14%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 1.14%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.14%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2         | 1.14%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 1.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.14%   |
| www.hirestech.com 2010 REV 1.4 Music Streamer Pro                          | 1         | 0.57%   |
| SteelSeries ApS SteelSeries Arctis 7                                       | 1         | 0.57%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 1         | 0.57%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.57%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.57%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.57%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.57%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.57%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.57%   |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 0.57%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.57%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.57%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 26        | 38.81%  |
| SK hynix            | 10        | 14.93%  |
| Micron Technology   | 5         | 7.46%   |
| Kingston            | 5         | 7.46%   |
| Corsair             | 5         | 7.46%   |
| Unknown             | 4         | 5.97%   |
| Crucial             | 4         | 5.97%   |
| G.Skill             | 3         | 4.48%   |
| A-DATA Technology   | 3         | 4.48%   |
| Timetec             | 1         | 1.49%   |
| Qimonda             | 1         | 1.49%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 3         | 4.23%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 2         | 2.82%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s       | 2         | 2.82%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 2         | 2.82%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s      | 2         | 2.82%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s     | 2         | 2.82%   |
| Unknown RAM Module 4GB SODIMM DDR3                          | 1         | 1.41%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                | 1         | 1.41%   |
| Unknown RAM Module 2GB SODIMM DDR2                          | 1         | 1.41%   |
| Unknown RAM Module 2048MB SODIMM DDR2                       | 1         | 1.41%   |
| Unknown RAM Module 1024MB SODIMM DDR2                       | 1         | 1.41%   |
| Timetec RAM SD3-1333 8GB SODIMM DDR3 1333MT/s               | 1         | 1.41%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s     | 1         | 1.41%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 1.41%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s      | 1         | 1.41%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s      | 1         | 1.41%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16384MB SODIMM DDR4 3200MT/s  | 1         | 1.41%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s     | 1         | 1.41%   |
| SK hynix RAM HMA81GS6MFR8N-UH 8GB SODIMM DDR4 2400MT/s      | 1         | 1.41%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s   | 1         | 1.41%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                 | 1         | 1.41%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR4 2933MT/s         | 1         | 1.41%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                 | 1         | 1.41%   |
| Samsung RAM Module 4GB SODIMM DDR3 1067MT/s                 | 1         | 1.41%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s             | 1         | 1.41%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s       | 1         | 1.41%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s       | 1         | 1.41%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 1         | 1.41%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 1         | 1.41%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s       | 1         | 1.41%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s      | 1         | 1.41%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s      | 1         | 1.41%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s       | 1         | 1.41%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 1         | 1.41%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s       | 1         | 1.41%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 1         | 1.41%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s       | 1         | 1.41%   |
| Samsung RAM M471A1G44AB0-CTD 8GB Row Of Chips DDR4 2667MT/s | 1         | 1.41%   |
| Samsung RAM M378A1K43CB2-CRC 8192MB DIMM DDR4 3500MT/s      | 1         | 1.41%   |
| Samsung RAM 99U5429-007.A00LF 2GB DIMM DDR2 800MT/s         | 1         | 1.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 34        | 53.97%  |
| DDR3   | 20        | 31.75%  |
| DDR2   | 4         | 6.35%   |
| LPDDR3 | 3         | 4.76%   |
| SDRAM  | 1         | 1.59%   |
| LPDDR4 | 1         | 1.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 42        | 67.74%  |
| DIMM         | 15        | 24.19%  |
| Row Of Chips | 5         | 8.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 32        | 47.76%  |
| 4096  | 13        | 19.4%   |
| 16384 | 12        | 17.91%  |
| 2048  | 7         | 10.45%  |
| 32768 | 2         | 2.99%   |
| 1024  | 1         | 1.49%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 15        | 23.08%  |
| 1600    | 12        | 18.46%  |
| 3200    | 8         | 12.31%  |
| 2400    | 7         | 10.77%  |
| 2133    | 5         | 7.69%   |
| 3600    | 3         | 4.62%   |
| Unknown | 3         | 4.62%   |
| 3400    | 2         | 3.08%   |
| 1333    | 2         | 3.08%   |
| 800     | 2         | 3.08%   |
| 3500    | 1         | 1.54%   |
| 2933    | 1         | 1.54%   |
| 2666    | 1         | 1.54%   |
| 1867    | 1         | 1.54%   |
| 1334    | 1         | 1.54%   |
| 1067    | 1         | 1.54%   |

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
| Chicony Electronics                    | 22        | 33.85%  |
| IMC Networks                           | 8         | 12.31%  |
| Microdia                               | 7         | 10.77%  |
| Logitech                               | 4         | 6.15%   |
| Ricoh                                  | 3         | 4.62%   |
| Realtek Semiconductor                  | 3         | 4.62%   |
| Alcor Micro                            | 3         | 4.62%   |
| Sunplus Innovation Technology          | 2         | 3.08%   |
| Samsung Electronics                    | 2         | 3.08%   |
| Quanta                                 | 2         | 3.08%   |
| Apple                                  | 2         | 3.08%   |
| Acer                                   | 2         | 3.08%   |
| Unknown                                | 1         | 1.54%   |
| Luxvisions Innotech Limited            | 1         | 1.54%   |
| Huawei Technologies                    | 1         | 1.54%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.54%   |
| ALi                                    | 1         | 1.54%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 4         | 6.15%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 6.15%   |
| IMC Networks Integrated Camera                      | 3         | 4.62%   |
| Chicony Integrated Camera                           | 3         | 4.62%   |
| Samsung Galaxy series, misc. (MTP mode)             | 2         | 3.08%   |
| Realtek Integrated_Webcam_HD                        | 2         | 3.08%   |
| Microdia Integrated Webcam                          | 2         | 3.08%   |
| Logitech B525 HD Webcam                             | 2         | 3.08%   |
| Chicony Integrated Camera (1280x720@30)             | 2         | 3.08%   |
| Chicony HP Wide Vision HD Camera                    | 2         | 3.08%   |
| Chicony HP HD Camera                                | 2         | 3.08%   |
| Chicony HD Webcam                                   | 2         | 3.08%   |
| Unknown 720p HD Camera                              | 1         | 1.54%   |
| Sunplus Laptop Integrated WebCam HD                 | 1         | 1.54%   |
| Sunplus HP HD Webcam [Fixed]                        | 1         | 1.54%   |
| Ricoh USB2.0 Camera                                 | 1         | 1.54%   |
| Ricoh Sony Visual Communication Camera              | 1         | 1.54%   |
| Ricoh Sony Vaio Integrated Webcam                   | 1         | 1.54%   |
| Realtek HP Truevision HD                            | 1         | 1.54%   |
| Quanta HP Webcam                                    | 1         | 1.54%   |
| Quanta HD User Facing                               | 1         | 1.54%   |
| Microdia Webcam                                     | 1         | 1.54%   |
| Luxvisions Innotech Limited HP HD Camera            | 1         | 1.54%   |
| Logitech Webcam C270                                | 1         | 1.54%   |
| Logitech HD Pro Webcam C920                         | 1         | 1.54%   |
| IMC Networks HD Camera                              | 1         | 1.54%   |
| Huawei HiCamera                                     | 1         | 1.54%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 1.54%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 1.54%   |
| Chicony USB 2.0 Camera                              | 1         | 1.54%   |
| Chicony TOSHIBA Web Camera - HD                     | 1         | 1.54%   |
| Chicony ThinkPad T490 Webcam                        | 1         | 1.54%   |
| Chicony Integrated HP HD Webcam                     | 1         | 1.54%   |
| Chicony HP Truevision HD                            | 1         | 1.54%   |
| Chicony HD WebCam (Asus N-series)                   | 1         | 1.54%   |
| Chicony FJ Camera                                   | 1         | 1.54%   |
| Chicony EasyCamera                                  | 1         | 1.54%   |
| Chicony Acer CrystalEye Webcam                      | 1         | 1.54%   |
| Cheng Uei Precision Industry (Foxlink) FJ 5M Camera | 1         | 1.54%   |
| Apple FaceTime HD Camera (Built-in)                 | 1         | 1.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 8         | 42.11%  |
| Validity Sensors           | 4         | 21.05%  |
| Shenzhen Goodix Technology | 3         | 15.79%  |
| Upek                       | 1         | 5.26%   |
| LighTuning Technology      | 1         | 5.26%   |
| Elan Microelectronics      | 1         | 5.26%   |
| AuthenTec                  | 1         | 5.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 4         | 21.05%  |
| Shenzhen Goodix Fingerprint Reader                         | 3         | 15.79%  |
| Unknown                                                    | 2         | 10.53%  |
| Validity Sensors VFS7552 Touch Fingerprint Sensor          | 1         | 5.26%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 1         | 5.26%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 1         | 5.26%   |
| Validity Sensors Synaptics WBDI                            | 1         | 5.26%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 1         | 5.26%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 5.26%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 1         | 5.26%   |
| LighTuning EgisTec_ES603                                   | 1         | 5.26%   |
| Elan ELAN:Fingerprint                                      | 1         | 5.26%   |
| AuthenTec Fingerprint Sensor                               | 1         | 5.26%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 5         | 55.56%  |
| Gemalto (was Gemplus) | 3         | 33.33%  |
| Broadcom              | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 55.56%  |
| Gemalto (was Gemplus) Prox SU USB PC Link Reader                             | 2         | 22.22%  |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 67        | 60.36%  |
| 1     | 29        | 26.13%  |
| 2     | 13        | 11.71%  |
| 3     | 2         | 1.8%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 19        | 32.2%   |
| Graphics card            | 12        | 20.34%  |
| Multimedia controller    | 6         | 10.17%  |
| Chipcard                 | 5         | 8.47%   |
| Network                  | 3         | 5.08%   |
| Net/wireless             | 3         | 5.08%   |
| Communication controller | 3         | 5.08%   |
| Card reader              | 3         | 5.08%   |
| Unassigned class         | 1         | 1.69%   |
| Sound                    | 1         | 1.69%   |
| Net/ethernet             | 1         | 1.69%   |
| Camera                   | 1         | 1.69%   |
| Bluetooth                | 1         | 1.69%   |

