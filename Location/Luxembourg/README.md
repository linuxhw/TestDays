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

Total: 153

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 20        | 16.67%  |
| Ubuntu 18.04                 | 10        | 8.33%   |
| Ubuntu 22.04                 | 4         | 3.33%   |
| Ubuntu 21.04                 | 4         | 3.33%   |
| Linux Mint 20.3              | 4         | 3.33%   |
| Ubuntu 20.10                 | 3         | 2.5%    |
| Pop!_OS 21.04                | 3         | 2.5%    |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 2.5%    |
| OpenMandriva 4.2             | 3         | 2.5%    |
| Fedora 32                    | 3         | 2.5%    |
| Xubuntu 20.04                | 2         | 1.67%   |
| Ubuntu 18.10                 | 2         | 1.67%   |
| ROSA R9                      | 2         | 1.67%   |
| Pop!_OS 22.04                | 2         | 1.67%   |
| Pop!_OS 21.10                | 2         | 1.67%   |
| openSUSE Leap-15.2           | 2         | 1.67%   |
| OpenMandriva 4.90            | 2         | 1.67%   |
| LMDE 4                       | 2         | 1.67%   |
| Debian 10                    | 2         | 1.67%   |
| Xubuntu 18.04                | 1         | 0.83%   |
| Xubuntu 16.04                | 1         | 0.83%   |
| UbuntuDDE 20.04              | 1         | 0.83%   |
| Ubuntu MATE 21.10            | 1         | 0.83%   |
| Ubuntu MATE 20.04            | 1         | 0.83%   |
| Ubuntu 22.10                 | 1         | 0.83%   |
| Ubuntu 19.10                 | 1         | 0.83%   |
| RHEL 8                       | 1         | 0.83%   |
| Pop!_OS 20.10                | 1         | 0.83%   |
| Pop!_OS 20.04                | 1         | 0.83%   |
| Parrot 5.1                   | 1         | 0.83%   |
| openSUSE Leap-15.3           | 1         | 0.83%   |
| openSUSE Leap-15.1           | 1         | 0.83%   |
| OpenMandriva 4.3             | 1         | 0.83%   |
| Manjaro 21.2.6               | 1         | 0.83%   |
| Manjaro 21.1.0               | 1         | 0.83%   |
| Manjaro 19.0.2               | 1         | 0.83%   |
| Mageia 7                     | 1         | 0.83%   |
| Lubuntu 20.10                | 1         | 0.83%   |
| Lubuntu 20.04                | 1         | 0.83%   |
| Linux Mint 20.2              | 1         | 0.83%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 44        | 38.6%   |
| Pop!_OS      | 8         | 7.02%   |
| openSUSE     | 6         | 5.26%   |
| OpenMandriva | 6         | 5.26%   |
| Linux Mint   | 6         | 5.26%   |
| Fedora       | 6         | 5.26%   |
| Xubuntu      | 4         | 3.51%   |
| Manjaro      | 3         | 2.63%   |
| Kubuntu      | 3         | 2.63%   |
| Debian       | 3         | 2.63%   |
| Ubuntu MATE  | 2         | 1.75%   |
| ROSA         | 2         | 1.75%   |
| Lubuntu      | 2         | 1.75%   |
| LMDE         | 2         | 1.75%   |
| Endless      | 2         | 1.75%   |
| Elementary   | 2         | 1.75%   |
| Arch         | 2         | 1.75%   |
| UbuntuDDE    | 1         | 0.88%   |
| RHEL         | 1         | 0.88%   |
| Parrot       | 1         | 0.88%   |
| Mageia       | 1         | 0.88%   |
| KDE neon     | 1         | 0.88%   |
| Kali         | 1         | 0.88%   |
| Garuda Linux | 1         | 0.88%   |
| Clear Linux  | 1         | 0.88%   |
| CentOS       | 1         | 0.88%   |
| BlackPanther | 1         | 0.88%   |
| ArcoLinux    | 1         | 0.88%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.8.0-43-generic                | 3         | 2.42%   |
| 5.11.0-27-generic               | 3         | 2.42%   |
| 5.10.14-desktop-1omv4002        | 3         | 2.42%   |
| 5.8.0-59-generic                | 2         | 1.61%   |
| 5.4.0-96-generic                | 2         | 1.61%   |
| 5.4.0-90-generic                | 2         | 1.61%   |
| 5.4.0-47-generic                | 2         | 1.61%   |
| 5.4.0-42-generic                | 2         | 1.61%   |
| 5.4.0-122-generic               | 2         | 1.61%   |
| 5.3.0-46-generic                | 2         | 1.61%   |
| 5.18.12-desktop-3omv4090        | 2         | 1.61%   |
| 5.16.11-76051611-generic        | 2         | 1.61%   |
| 5.15.0-52-generic               | 2         | 1.61%   |
| 5.11.0-34-generic               | 2         | 1.61%   |
| 5.11.0-17-generic               | 2         | 1.61%   |
| 5.0.0-23-generic                | 2         | 1.61%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 2         | 1.61%   |
| 4.19.0-17-amd64                 | 2         | 1.61%   |
| 6.0.6-76060006-generic          | 1         | 0.81%   |
| 5.9.13-zen1-1-zen               | 1         | 0.81%   |
| 5.9.10-200.fc33.x86_64          | 1         | 0.81%   |
| 5.8.11-050811-generic           | 1         | 0.81%   |
| 5.8.0-63-generic                | 1         | 0.81%   |
| 5.8.0-55-generic                | 1         | 0.81%   |
| 5.8.0-44-generic                | 1         | 0.81%   |
| 5.8.0-31-generic                | 1         | 0.81%   |
| 5.8.0-26-generic                | 1         | 0.81%   |
| 5.8.0-20-generic                | 1         | 0.81%   |
| 5.8.0-14-generic                | 1         | 0.81%   |
| 5.7.6-201.fc32.x86_64           | 1         | 0.81%   |
| 5.7.19-desktop-3.mga7           | 1         | 0.81%   |
| 5.7.14-200.fc32.x86_64          | 1         | 0.81%   |
| 5.7.1-1-default                 | 1         | 0.81%   |
| 5.7.0-3-amd64                   | 1         | 0.81%   |
| 5.7.0-050700-generic            | 1         | 0.81%   |
| 5.6.3-935.native                | 1         | 0.81%   |
| 5.5.8-1-MANJARO                 | 1         | 0.81%   |
| 5.4.0-91-generic                | 1         | 0.81%   |
| 5.4.0-84-generic                | 1         | 0.81%   |
| 5.4.0-73-generic                | 1         | 0.81%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 19        | 16.24%  |
| 5.11.0  | 14        | 11.97%  |
| 5.8.0   | 10        | 8.55%   |
| 5.15.0  | 8         | 6.84%   |
| 5.3.0   | 6         | 5.13%   |
| 4.18.0  | 6         | 5.13%   |
| 5.13.0  | 4         | 3.42%   |
| 4.15.0  | 4         | 3.42%   |
| 5.10.14 | 3         | 2.56%   |
| 5.0.0   | 3         | 2.56%   |
| 5.7.0   | 2         | 1.71%   |
| 5.3.18  | 2         | 1.71%   |
| 5.18.12 | 2         | 1.71%   |
| 5.16.11 | 2         | 1.71%   |
| 5.10.0  | 2         | 1.71%   |
| 4.9.20  | 2         | 1.71%   |
| 4.19.0  | 2         | 1.71%   |
| 6.0.6   | 1         | 0.85%   |
| 5.9.13  | 1         | 0.85%   |
| 5.9.10  | 1         | 0.85%   |
| 5.8.11  | 1         | 0.85%   |
| 5.7.6   | 1         | 0.85%   |
| 5.7.19  | 1         | 0.85%   |
| 5.7.14  | 1         | 0.85%   |
| 5.7.1   | 1         | 0.85%   |
| 5.6.3   | 1         | 0.85%   |
| 5.5.8   | 1         | 0.85%   |
| 5.19.0  | 1         | 0.85%   |
| 5.18.5  | 1         | 0.85%   |
| 5.18.0  | 1         | 0.85%   |
| 5.16.7  | 1         | 0.85%   |
| 5.16.2  | 1         | 0.85%   |
| 5.15.4  | 1         | 0.85%   |
| 5.15.32 | 1         | 0.85%   |
| 5.14.0  | 1         | 0.85%   |
| 5.13.4  | 1         | 0.85%   |
| 5.12.7  | 1         | 0.85%   |
| 5.12.13 | 1         | 0.85%   |
| 5.10.7  | 1         | 0.85%   |
| 5.10.26 | 1         | 0.85%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 19        | 16.24%  |
| 5.11    | 14        | 11.97%  |
| 5.8     | 11        | 9.4%    |
| 5.15    | 10        | 8.55%   |
| 5.3     | 8         | 6.84%   |
| 5.10    | 7         | 5.98%   |
| 4.18    | 7         | 5.98%   |
| 5.7     | 6         | 5.13%   |
| 5.13    | 5         | 4.27%   |
| 5.18    | 4         | 3.42%   |
| 5.16    | 4         | 3.42%   |
| 4.15    | 4         | 3.42%   |
| 5.0     | 3         | 2.56%   |
| 5.9     | 2         | 1.71%   |
| 5.12    | 2         | 1.71%   |
| 4.9     | 2         | 1.71%   |
| 4.19    | 2         | 1.71%   |
| 6.0     | 1         | 0.85%   |
| 5.6     | 1         | 0.85%   |
| 5.5     | 1         | 0.85%   |
| 5.19    | 1         | 0.85%   |
| 5.14    | 1         | 0.85%   |
| 4.4     | 1         | 0.85%   |
| 4.12    | 1         | 0.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 110       | 98.21%  |
| i686   | 2         | 1.79%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 54        | 46.55%  |
| KDE5            | 16        | 13.79%  |
| Unknown         | 14        | 12.07%  |
| X-Cinnamon      | 8         | 6.9%    |
| XFCE            | 6         | 5.17%   |
| KDE             | 5         | 4.31%   |
| MATE            | 3         | 2.59%   |
| Pantheon        | 2         | 1.72%   |
| LXQt            | 2         | 1.72%   |
| i3              | 2         | 1.72%   |
| Cinnamon        | 2         | 1.72%   |
| GNOME Flashback | 1         | 0.86%   |
| Deepin          | 1         | 0.86%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 88        | 76.52%  |
| Wayland | 14        | 12.17%  |
| Unknown | 9         | 7.83%   |
| Tty     | 4         | 3.48%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 59        | 50%     |
| GDM     | 18        | 15.25%  |
| SDDM    | 16        | 13.56%  |
| LightDM | 14        | 11.86%  |
| GDM3    | 7         | 5.93%   |
| TDM     | 4         | 3.39%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 46        | 40.35%  |
| Unknown | 13        | 11.4%   |
| fr_FR   | 10        | 8.77%   |
| de_LU   | 8         | 7.02%   |
| en_GB   | 7         | 6.14%   |
| de_DE   | 7         | 6.14%   |
| C       | 5         | 4.39%   |
| fr_LU   | 4         | 3.51%   |
| es_ES   | 3         | 2.63%   |
| nl_NL   | 2         | 1.75%   |
| unm_US  | 1         | 0.88%   |
| pt_PT   | 1         | 0.88%   |
| pt_BR   | 1         | 0.88%   |
| POSIX   | 1         | 0.88%   |
| lb_LU   | 1         | 0.88%   |
| it_IT   | 1         | 0.88%   |
| hr_HR   | 1         | 0.88%   |
| en_IE   | 1         | 0.88%   |
| de_CH   | 1         | 0.88%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 57        | 50.44%  |
| BIOS | 56        | 49.56%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 84        | 75%     |
| Overlay | 9         | 8.04%   |
| Btrfs   | 9         | 8.04%   |
| Xfs     | 5         | 4.46%   |
| Unknown | 4         | 3.57%   |
| Zfs     | 1         | 0.89%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 59        | 52.68%  |
| GPT     | 45        | 40.18%  |
| MBR     | 8         | 7.14%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 102       | 90.27%  |
| Yes       | 11        | 9.73%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 81        | 71.68%  |
| Yes       | 32        | 28.32%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 18        | 16.07%  |
| Hewlett-Packard     | 15        | 13.39%  |
| Lenovo              | 12        | 10.71%  |
| Dell                | 9         | 8.04%   |
| Intel               | 6         | 5.36%   |
| Sony                | 5         | 4.46%   |
| MSI                 | 5         | 4.46%   |
| Gigabyte Technology | 5         | 4.46%   |
| Apple               | 5         | 4.46%   |
| Medion              | 4         | 3.57%   |
| Acer                | 4         | 3.57%   |
| Wortmann AG         | 3         | 2.68%   |
| ASRock              | 3         | 2.68%   |
| win element         | 2         | 1.79%   |
| Samsung Electronics | 2         | 1.79%   |
| Fujitsu             | 2         | 1.79%   |
| Clevo               | 2         | 1.79%   |
| YJKC                | 1         | 0.89%   |
| TUXEDO              | 1         | 0.89%   |
| Toshiba             | 1         | 0.89%   |
| Timi                | 1         | 0.89%   |
| Packard Bell        | 1         | 0.89%   |
| Microsoft           | 1         | 0.89%   |
| LattePanda          | 1         | 0.89%   |
| JWIPC               | 1         | 0.89%   |
| HUAWEI              | 1         | 0.89%   |
| Foxconn             | 1         | 0.89%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| ASUS All Series                          | 3         | 2.68%   |
| win element MoreFine S500+               | 2         | 1.79%   |
| Dell Precision M3800                     | 2         | 1.79%   |
| YJKC vBook                               | 1         | 0.89%   |
| Wortmann AG TERRA_MOBILE_1749            | 1         | 0.89%   |
| Wortmann AG TERRA_MOBILE_1541H           | 1         | 0.89%   |
| Wortmann AG MS-1727                      | 1         | 0.89%   |
| TUXEDO Pulse 14 Gen1                     | 1         | 0.89%   |
| Toshiba Satellite C55-A-1N0              | 1         | 0.89%   |
| Timi RedmiBook 14 II                     | 1         | 0.89%   |
| Sony VPCP11S1R                           | 1         | 0.89%   |
| Sony VPCEB2E1E                           | 1         | 0.89%   |
| Sony VPCCA4E1E                           | 1         | 0.89%   |
| Sony VGN-NS30E_S                         | 1         | 0.89%   |
| Sony SVF1421E2EW                         | 1         | 0.89%   |
| Samsung Galaxy TabPro S LTE              | 1         | 0.89%   |
| Samsung 950QDB                           | 1         | 0.89%   |
| Packard Bell EasyNote TJ65               | 1         | 0.89%   |
| MSI MS-7C80                              | 1         | 0.89%   |
| MSI MS-7C08                              | 1         | 0.89%   |
| MSI MS-7816                              | 1         | 0.89%   |
| MSI MS-7578                              | 1         | 0.89%   |
| MSI GF72 8RD                             | 1         | 0.89%   |
| Microsoft Surface Book 2                 | 1         | 0.89%   |
| Medion P961x                             | 1         | 0.89%   |
| Medion P6685 MD61138                     | 1         | 0.89%   |
| Medion MS-7848                           | 1         | 0.89%   |
| Medion E4254 MD62100                     | 1         | 0.89%   |
| Lenovo ThinkPad X1 Carbon 7th 20QDCTO1WW | 1         | 0.89%   |
| Lenovo ThinkPad T590 20N4CTO1WW          | 1         | 0.89%   |
| Lenovo ThinkPad T490 20N3S5DV0S          | 1         | 0.89%   |
| Lenovo ThinkPad T480s 20L7001PFR         | 1         | 0.89%   |
| Lenovo ThinkPad T470s W10DG 20JTS0R800   | 1         | 0.89%   |
| Lenovo ThinkPad T440p 20AWS24B00         | 1         | 0.89%   |
| Lenovo ThinkPad P1 Gen 2 20QTCTO1WW      | 1         | 0.89%   |
| Lenovo ThinkPad L15 Gen 1 20U8S0AH00     | 1         | 0.89%   |
| Lenovo ThinkPad L15 Gen 1 20U7S05B00     | 1         | 0.89%   |
| Lenovo ThinkCentre M910s 10MKS02N04      | 1         | 0.89%   |
| Lenovo IdeaPad 330-15ICH 81FK            | 1         | 0.89%   |
| Lenovo G50-70 20351                      | 1         | 0.89%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 9         | 8.04%   |
| Dell Precision        | 5         | 4.46%   |
| HP EliteBook          | 4         | 3.57%   |
| ASUS PRIME            | 4         | 3.57%   |
| HP ENVY               | 3         | 2.68%   |
| ASUS All              | 3         | 2.68%   |
| Acer Aspire           | 3         | 2.68%   |
| Wortmann AG TERRA     | 2         | 1.79%   |
| win element MoreFine  | 2         | 1.79%   |
| HP ProBook            | 2         | 1.79%   |
| HP Compaq             | 2         | 1.79%   |
| Dell XPS              | 2         | 1.79%   |
| ASUS VivoBook         | 2         | 1.79%   |
| ASUS TUF              | 2         | 1.79%   |
| ASUS ROG              | 2         | 1.79%   |
| YJKC vBook            | 1         | 0.89%   |
| Wortmann AG MS-1727   | 1         | 0.89%   |
| TUXEDO Pulse          | 1         | 0.89%   |
| Toshiba Satellite     | 1         | 0.89%   |
| Timi RedmiBook        | 1         | 0.89%   |
| Sony VPCP11S1R        | 1         | 0.89%   |
| Sony VPCEB2E1E        | 1         | 0.89%   |
| Sony VPCCA4E1E        | 1         | 0.89%   |
| Sony VGN-NS30E        | 1         | 0.89%   |
| Sony SVF1421E2EW      | 1         | 0.89%   |
| Samsung Galaxy        | 1         | 0.89%   |
| Samsung 950QDB        | 1         | 0.89%   |
| Packard Bell EasyNote | 1         | 0.89%   |
| MSI MS-7C80           | 1         | 0.89%   |
| MSI MS-7C08           | 1         | 0.89%   |
| MSI MS-7816           | 1         | 0.89%   |
| MSI MS-7578           | 1         | 0.89%   |
| MSI GF72              | 1         | 0.89%   |
| Microsoft Surface     | 1         | 0.89%   |
| Medion P961x          | 1         | 0.89%   |
| Medion P6685          | 1         | 0.89%   |
| Medion MS-7848        | 1         | 0.89%   |
| Medion E4254          | 1         | 0.89%   |
| Lenovo ThinkCentre    | 1         | 0.89%   |
| Lenovo IdeaPad        | 1         | 0.89%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 14        | 12.5%   |
| 2018 | 14        | 12.5%   |
| 2013 | 12        | 10.71%  |
| 2017 | 11        | 9.82%   |
| 2020 | 10        | 8.93%   |
| 2014 | 9         | 8.04%   |
| 2010 | 9         | 8.04%   |
| 2021 | 6         | 5.36%   |
| 2016 | 6         | 5.36%   |
| 2015 | 5         | 4.46%   |
| 2011 | 5         | 4.46%   |
| 2012 | 3         | 2.68%   |
| 2009 | 3         | 2.68%   |
| 2022 | 2         | 1.79%   |
| 2007 | 2         | 1.79%   |
| 2008 | 1         | 0.89%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 68        | 60.71%  |
| Desktop     | 35        | 31.25%  |
| Mini pc     | 4         | 3.57%   |
| Tablet      | 2         | 1.79%   |
| Convertible | 2         | 1.79%   |
| All in one  | 1         | 0.89%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 103       | 91.96%  |
| Enabled  | 9         | 8.04%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 112       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 33        | 29.46%  |
| 8.01-16.0   | 24        | 21.43%  |
| 4.01-8.0    | 22        | 19.64%  |
| 3.01-4.0    | 16        | 14.29%  |
| 32.01-64.0  | 10        | 8.93%   |
| 64.01-256.0 | 3         | 2.68%   |
| 1.01-2.0    | 2         | 1.79%   |
| 24.01-32.0  | 1         | 0.89%   |
| 2.01-3.0    | 1         | 0.89%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 34        | 29.06%  |
| 1.01-2.0   | 34        | 29.06%  |
| 4.01-8.0   | 21        | 17.95%  |
| 3.01-4.0   | 13        | 11.11%  |
| 8.01-16.0  | 9         | 7.69%   |
| 0.51-1.0   | 3         | 2.56%   |
| 24.01-32.0 | 1         | 0.85%   |
| 16.01-24.0 | 1         | 0.85%   |
| 0.01-0.5   | 1         | 0.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 64        | 56.14%  |
| 2      | 29        | 25.44%  |
| 3      | 11        | 9.65%   |
| 4      | 5         | 4.39%   |
| 5      | 2         | 1.75%   |
| 0      | 2         | 1.75%   |
| 7      | 1         | 0.88%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 72        | 64.29%  |
| Yes       | 40        | 35.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 96        | 85.71%  |
| No        | 16        | 14.29%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 92        | 81.42%  |
| No        | 21        | 18.58%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 76        | 67.86%  |
| No        | 36        | 32.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country    | Computers | Percent |
|------------|-----------|---------|
| Luxembourg | 112       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Luxembourg        | 57        | 48.31%  |
| Strassen          | 9         | 7.63%   |
| Useldange         | 3         | 2.54%   |
| Schifflange       | 3         | 2.54%   |
| Schieren          | 3         | 2.54%   |
| Ehnen             | 3         | 2.54%   |
| Differdange       | 3         | 2.54%   |
| Wormeldange       | 2         | 1.69%   |
| Steinfort         | 2         | 1.69%   |
| Sanem             | 2         | 1.69%   |
| Esch-sur-Alzette  | 2         | 1.69%   |
| Bettange-sur-Mess | 2         | 1.69%   |
| Wiltz             | 1         | 0.85%   |
| Wecker            | 1         | 0.85%   |
| Wasserbillig      | 1         | 0.85%   |
| Vianden           | 1         | 0.85%   |
| Steinsel          | 1         | 0.85%   |
| Soleuvre          | 1         | 0.85%   |
| Roeser            | 1         | 0.85%   |
| Pontpierre        | 1         | 0.85%   |
| Pétange          | 1         | 0.85%   |
| PerlГ©          | 1         | 0.85%   |
| Oberpallen        | 1         | 0.85%   |
| Niederanven       | 1         | 0.85%   |
| Leudelange        | 1         | 0.85%   |
| Kopstal           | 1         | 0.85%   |
| Junglinster       | 1         | 0.85%   |
| Itzig             | 1         | 0.85%   |
| Hunsdorf          | 1         | 0.85%   |
| Hosingen          | 1         | 0.85%   |
| Hesperange        | 1         | 0.85%   |
| Ettelbruck        | 1         | 0.85%   |
| Echternach        | 1         | 0.85%   |
| Diekirch          | 1         | 0.85%   |
| Bourscheid        | 1         | 0.85%   |
| Bettembourg       | 1         | 0.85%   |
| Belvaux           | 1         | 0.85%   |
| Beckerich         | 1         | 0.85%   |
| Aspelt            | 1         | 0.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 38        | 52     | 23.75%  |
| Seagate                   | 23        | 31     | 14.38%  |
| WDC                       | 19        | 29     | 11.88%  |
| Toshiba                   | 11        | 14     | 6.88%   |
| SanDisk                   | 10        | 14     | 6.25%   |
| Crucial                   | 10        | 14     | 6.25%   |
| Kingston                  | 8         | 11     | 5%      |
| Apple                     | 5         | 6      | 3.13%   |
| SK hynix                  | 4         | 4      | 2.5%    |
| Hitachi                   | 3         | 4      | 1.88%   |
| Transcend                 | 2         | 2      | 1.25%   |
| LITEONIT                  | 2         | 2      | 1.25%   |
| LITEON                    | 2         | 2      | 1.25%   |
| Intenso                   | 2         | 3      | 1.25%   |
| Intel                     | 2         | 2      | 1.25%   |
| HGST                      | 2         | 3      | 1.25%   |
| Unknown                   | 1         | 2      | 0.63%   |
| Union Memory (Shenzhen)   | 1         | 1      | 0.63%   |
| TCSUNBOW                  | 1         | 1      | 0.63%   |
| SABRENT                   | 1         | 1      | 0.63%   |
| Phison                    | 1         | 1      | 0.63%   |
| PHD 3.0                   | 1         | 1      | 0.63%   |
| OCZ                       | 1         | 1      | 0.63%   |
| Micron/Crucial Technology | 1         | 1      | 0.63%   |
| Micron Technology         | 1         | 2      | 0.63%   |
| Maxtor                    | 1         | 2      | 0.63%   |
| LaCie                     | 1         | 1      | 0.63%   |
| KingSpec                  | 1         | 1      | 0.63%   |
| KingDian                  | 1         | 1      | 0.63%   |
| Inateck                   | 1         | 1      | 0.63%   |
| Gigabyte Technology       | 1         | 1      | 0.63%   |
| FORESEE                   | 1         | 1      | 0.63%   |
| A-DATA Technology         | 1         | 1      | 0.63%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Seagate Expansion 4TB                  | 4         | 2.19%   |
| Samsung SSD 840 EVO 250GB              | 3         | 1.64%   |
| WDC WD10JPVX-22JC3T0 1TB               | 2         | 1.09%   |
| Toshiba MQ01ABF050 500GB               | 2         | 1.09%   |
| Seagate ST1000LM035-1RK172 1TB         | 2         | 1.09%   |
| SanDisk SD8SN8U128G1122 128GB SSD      | 2         | 1.09%   |
| SanDisk NVMe SSD Drive 1TB             | 2         | 1.09%   |
| Samsung SSD 860 QVO 1TB                | 2         | 1.09%   |
| Samsung SSD 860 EVO 250GB              | 2         | 1.09%   |
| Samsung SSD 850 EVO 250GB              | 2         | 1.09%   |
| Samsung SP2504C 250GB                  | 2         | 1.09%   |
| Samsung MZVLW256HEHP-000L7 256GB       | 2         | 1.09%   |
| LITEONIT LMT-256L9M-11 MSATA 256GB SSD | 2         | 1.09%   |
| Kingston SA400S37240G 240GB SSD        | 2         | 1.09%   |
| Crucial CT240BX500SSD1 240GB           | 2         | 1.09%   |
| Crucial CT1000P2SSD8 1TB               | 2         | 1.09%   |
| WDC WDS500G3X0C-00SJG0 500GB           | 1         | 0.55%   |
| WDC WDS250G2B0B-00YS70 250GB SSD       | 1         | 0.55%   |
| WDC WD5000AAVS-00ZTB0 500GB            | 1         | 0.55%   |
| WDC WD5000AAKS-60Z1A0 500GB            | 1         | 0.55%   |
| WDC WD40EZRZ-75GXCB0 4TB               | 1         | 0.55%   |
| WDC WD4000FYYZ-01UL1B2 4TB             | 1         | 0.55%   |
| WDC WD3200LPCX-00VHAT0 320GB           | 1         | 0.55%   |
| WDC WD3001FFSX-68JNUN0 3TB             | 1         | 0.55%   |
| WDC WD3000GLFS-01F8U0 304GB            | 1         | 0.55%   |
| WDC WD20EFAX-68FB5N0 2TB               | 1         | 0.55%   |
| WDC WD141KRYZ-01C66B0 14TB             | 1         | 0.55%   |
| WDC WD10SPZX-17Z10T0 1TB               | 1         | 0.55%   |
| WDC WD10SPCX-60HWST0 1TB               | 1         | 0.55%   |
| WDC WD10EZRX-00A8LB0 1TB               | 1         | 0.55%   |
| WDC WD10EZEX-60ZF5A0 1TB               | 1         | 0.55%   |
| WDC WD10EZEX-08WN4A0 1TB               | 1         | 0.55%   |
| WDC WD10EARX-00N0YB0 1TB               | 1         | 0.55%   |
| WDC WD10EARS-00Y5B1 1TB                | 1         | 0.55%   |
| WDC WD10EACS-00D6B1 1TB                | 1         | 0.55%   |
| WDC WD1001FALS-00J7B0 1TB              | 1         | 0.55%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB   | 1         | 0.55%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB     | 1         | 0.55%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB   | 1         | 0.55%   |
| Unknown MMC Card  64GB                 | 1         | 0.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 29     | 37.5%   |
| WDC                 | 14        | 24     | 25%     |
| Toshiba             | 8         | 11     | 14.29%  |
| Samsung Electronics | 3         | 3      | 5.36%   |
| Hitachi             | 3         | 4      | 5.36%   |
| HGST                | 2         | 3      | 3.57%   |
| Apple               | 2         | 2      | 3.57%   |
| PHD 3.0             | 1         | 1      | 1.79%   |
| Intenso             | 1         | 1      | 1.79%   |
| Inateck             | 1         | 1      | 1.79%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 24        | 32     | 38.1%   |
| SanDisk             | 9         | 11     | 14.29%  |
| Crucial             | 8         | 12     | 12.7%   |
| Kingston            | 4         | 7      | 6.35%   |
| Transcend           | 2         | 2      | 3.17%   |
| LITEONIT            | 2         | 2      | 3.17%   |
| LITEON              | 2         | 2      | 3.17%   |
| WDC                 | 1         | 1      | 1.59%   |
| TCSUNBOW            | 1         | 1      | 1.59%   |
| SK hynix            | 1         | 1      | 1.59%   |
| OCZ                 | 1         | 1      | 1.59%   |
| Micron Technology   | 1         | 2      | 1.59%   |
| Maxtor              | 1         | 2      | 1.59%   |
| KingSpec            | 1         | 1      | 1.59%   |
| KingDian            | 1         | 1      | 1.59%   |
| Intenso             | 1         | 2      | 1.59%   |
| FORESEE             | 1         | 1      | 1.59%   |
| Apple               | 1         | 1      | 1.59%   |
| A-DATA Technology   | 1         | 1      | 1.59%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 52        | 83     | 35.62%  |
| HDD     | 50        | 79     | 34.25%  |
| NVMe    | 40        | 46     | 27.4%   |
| MMC     | 2         | 3      | 1.37%   |
| Unknown | 2         | 2      | 1.37%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 81        | 152    | 60.9%   |
| NVMe | 40        | 45     | 30.08%  |
| SAS  | 10        | 13     | 7.52%   |
| MMC  | 2         | 3      | 1.5%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 64        | 97     | 55.65%  |
| 0.51-1.0   | 35        | 47     | 30.43%  |
| 3.01-4.0   | 8         | 8      | 6.96%   |
| 1.01-2.0   | 4         | 5      | 3.48%   |
| 2.01-3.0   | 2         | 3      | 1.74%   |
| 10.01-20.0 | 1         | 1      | 0.87%   |
| 4.01-10.0  | 1         | 1      | 0.87%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 31        | 27.43%  |
| 251-500        | 23        | 20.35%  |
| 501-1000       | 16        | 14.16%  |
| Unknown        | 10        | 8.85%   |
| 1001-2000      | 9         | 7.96%   |
| More than 3000 | 8         | 7.08%   |
| 2001-3000      | 5         | 4.42%   |
| 1-20           | 5         | 4.42%   |
| 51-100         | 5         | 4.42%   |
| 21-50          | 1         | 0.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 40        | 34.78%  |
| 101-250        | 17        | 14.78%  |
| 21-50          | 16        | 13.91%  |
| 51-100         | 10        | 8.7%    |
| Unknown        | 10        | 8.7%    |
| 501-1000       | 8         | 6.96%   |
| 251-500        | 7         | 6.09%   |
| 2001-3000      | 3         | 2.61%   |
| More than 3000 | 2         | 1.74%   |
| 1001-2000      | 2         | 1.74%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABF050 500GB              | 2         | 2      | 40%     |
| Toshiba MK2555GSX 250GB               | 1         | 1      | 20%     |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 20%     |
| Crucial CT128MX100SSD1 128GB          | 1         | 2      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Toshiba  | 3         | 3      | 60%     |
| SK hynix | 1         | 1      | 20%     |
| Crucial  | 1         | 2      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 3         | 3      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 60        | 121    | 51.28%  |
| Works    | 52        | 86     | 44.44%  |
| Malfunc  | 5         | 6      | 4.27%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 80        | 57.14%  |
| AMD                          | 16        | 11.43%  |
| Samsung Electronics          | 15        | 10.71%  |
| SanDisk                      | 7         | 5%      |
| Kingston Technology Company  | 4         | 2.86%   |
| Toshiba America Info Systems | 3         | 2.14%   |
| Micron/Crucial Technology    | 3         | 2.14%   |
| Marvell Technology Group     | 3         | 2.14%   |
| SK hynix                     | 2         | 1.43%   |
| Phison Electronics           | 2         | 1.43%   |
| Apple                        | 2         | 1.43%   |
| Union Memory (Shenzhen)      | 1         | 0.71%   |
| Seagate Technology           | 1         | 0.71%   |
| ASMedia Technology           | 1         | 0.71%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 14        | 9.21%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 13        | 8.55%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 9         | 5.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 6         | 3.95%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 3.29%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 5         | 3.29%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 4         | 2.63%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 2.63%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 2.63%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 2.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 2.63%   |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 2.63%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.97%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 1.97%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 1.97%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 1.97%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 1.32%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 1.32%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 1.32%   |
| Phison E12 NVMe Controller                                                     | 2         | 1.32%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2         | 1.32%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                      | 2         | 1.32%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 1.32%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 1.32%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.32%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2         | 1.32%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 2         | 1.32%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 1.32%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 0.66%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.66%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 1         | 0.66%   |
| SK hynix Non-Volatile memory controller                                        | 1         | 0.66%   |
| Seagate FireCuda 520 SSD                                                       | 1         | 0.66%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 0.66%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 0.66%   |
| Samsung Electronics Non-Volatile memory controller                             | 1         | 0.66%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1         | 0.66%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 1         | 0.66%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 0.66%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 1         | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 85        | 61.15%  |
| NVMe | 41        | 29.5%   |
| IDE  | 7         | 5.04%   |
| RAID | 6         | 4.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 92        | 82.14%  |
| AMD    | 20        | 17.86%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz           | 4         | 3.57%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 3         | 2.68%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 2         | 1.79%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 2         | 1.79%   |
| Intel Core i7-4702HQ CPU @ 2.20GHz          | 2         | 1.79%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2         | 1.79%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 2         | 1.79%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 2         | 1.79%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 2         | 1.79%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2         | 1.79%   |
| AMD Ryzen 9 5900HX with Radeon Graphics     | 2         | 1.79%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2         | 1.79%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.89%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 0.89%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 0.89%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 1         | 0.89%   |
| Intel Pentium CPU P6000 @ 1.87GHz           | 1         | 0.89%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 1         | 0.89%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 1         | 0.89%   |
| Intel Pentium CPU 987 @ 1.50GHz             | 1         | 0.89%   |
| Intel Core m5-6Y54 CPU @ 1.10GHz            | 1         | 0.89%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz            | 1         | 0.89%   |
| Intel Core i9-9880H CPU @ 2.30GHz           | 1         | 0.89%   |
| Intel Core i7-9700KF CPU @ 3.60GHz          | 1         | 0.89%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 0.89%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 0.89%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.89%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1         | 0.89%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 0.89%   |
| Intel Core i7-6800K CPU @ 3.40GHz           | 1         | 0.89%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 0.89%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 0.89%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 0.89%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1         | 0.89%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 0.89%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1         | 0.89%   |
| Intel Core i7-4712MQ CPU @ 2.30GHz          | 1         | 0.89%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz          | 1         | 0.89%   |
| Intel Core i7-3940XM CPU @ 3.00GHz          | 1         | 0.89%   |
| Intel Core i7-3840QM CPU @ 2.80GHz          | 1         | 0.89%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 30        | 26.79%  |
| Intel Core i5           | 27        | 24.11%  |
| Intel Core i3           | 9         | 8.04%   |
| AMD Ryzen 5             | 6         | 5.36%   |
| Other                   | 5         | 4.46%   |
| Intel Pentium           | 4         | 3.57%   |
| Intel Celeron           | 4         | 3.57%   |
| AMD Ryzen 9             | 4         | 3.57%   |
| Intel Pentium Dual-Core | 3         | 2.68%   |
| Intel Core 2 Quad       | 3         | 2.68%   |
| AMD Ryzen 7             | 3         | 2.68%   |
| AMD Ryzen 7 PRO         | 2         | 1.79%   |
| Intel Pentium Silver    | 1         | 0.89%   |
| Intel Core m5           | 1         | 0.89%   |
| Intel Core m3           | 1         | 0.89%   |
| Intel Core i9           | 1         | 0.89%   |
| Intel Core 2 Duo        | 1         | 0.89%   |
| Intel Core 2            | 1         | 0.89%   |
| Intel Atom              | 1         | 0.89%   |
| AMD Ryzen 5 PRO         | 1         | 0.89%   |
| AMD Phenom II X4        | 1         | 0.89%   |
| AMD FX                  | 1         | 0.89%   |
| AMD E2                  | 1         | 0.89%   |
| AMD Athlon II X4        | 1         | 0.89%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 43        | 38.39%  |
| 2       | 40        | 35.71%  |
| 8       | 12        | 10.71%  |
| 6       | 11        | 9.82%   |
| 12      | 2         | 1.79%   |
| 1       | 2         | 1.79%   |
| 16      | 1         | 0.89%   |
| Unknown | 1         | 0.89%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 112       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 83        | 74.11%  |
| 1       | 28        | 25%     |
| Unknown | 1         | 0.89%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 111       | 99.11%  |
| 32-bit         | 1         | 0.89%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 19.3%   |
| 0x306c3    | 13        | 11.4%   |
| 0x40651    | 5         | 4.39%   |
| 0x206a7    | 5         | 4.39%   |
| 0x906e9    | 4         | 3.51%   |
| 0x806ea    | 4         | 3.51%   |
| 0x406e3    | 4         | 3.51%   |
| 0x1067a    | 4         | 3.51%   |
| 0x806eb    | 3         | 2.63%   |
| 0x506e3    | 3         | 2.63%   |
| 0x306d4    | 3         | 2.63%   |
| 0x20655    | 3         | 2.63%   |
| 0xa0655    | 2         | 1.75%   |
| 0x906ed    | 2         | 1.75%   |
| 0x806ec    | 2         | 1.75%   |
| 0x706a1    | 2         | 1.75%   |
| 0x306a9    | 2         | 1.75%   |
| 0x10677    | 2         | 1.75%   |
| 0x0a50000c | 2         | 1.75%   |
| 0x08701021 | 2         | 1.75%   |
| 0x08701013 | 2         | 1.75%   |
| 0x08600106 | 2         | 1.75%   |
| 0x08600103 | 2         | 1.75%   |
| 0xa0671    | 1         | 0.88%   |
| 0x906ea    | 1         | 0.88%   |
| 0x906c0    | 1         | 0.88%   |
| 0x806e9    | 1         | 0.88%   |
| 0x806d1    | 1         | 0.88%   |
| 0x806c1    | 1         | 0.88%   |
| 0x6fb      | 1         | 0.88%   |
| 0x6f6      | 1         | 0.88%   |
| 0x406f1    | 1         | 0.88%   |
| 0x20652    | 1         | 0.88%   |
| 0x106c2    | 1         | 0.88%   |
| 0x0a201009 | 1         | 0.88%   |
| 0x08600104 | 1         | 0.88%   |
| 0x08108102 | 1         | 0.88%   |
| 0x0810100b | 1         | 0.88%   |
| 0x0800820d | 1         | 0.88%   |
| 0x06006705 | 1         | 0.88%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 25        | 22.32%  |
| Haswell       | 20        | 17.86%  |
| Zen 2         | 10        | 8.93%   |
| Skylake       | 10        | 8.93%   |
| Penryn        | 6         | 5.36%   |
| SandyBridge   | 5         | 4.46%   |
| Westmere      | 4         | 3.57%   |
| Broadwell     | 4         | 3.57%   |
| Zen 3         | 3         | 2.68%   |
| IvyBridge     | 3         | 2.68%   |
| CometLake     | 3         | 2.68%   |
| Zen+          | 2         | 1.79%   |
| TigerLake     | 2         | 1.79%   |
| K10           | 2         | 1.79%   |
| Icelake       | 2         | 1.79%   |
| Goldmont plus | 2         | 1.79%   |
| Core          | 2         | 1.79%   |
| Unknown       | 2         | 1.79%   |
| Zen           | 1         | 0.89%   |
| Piledriver    | 1         | 0.89%   |
| Goldmont      | 1         | 0.89%   |
| Excavator     | 1         | 0.89%   |
| Bonnell       | 1         | 0.89%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 74        | 54.41%  |
| Nvidia | 40        | 29.41%  |
| AMD    | 22        | 16.18%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 8         | 5.8%    |
| Intel UHD Graphics 620                                                      | 6         | 4.35%   |
| AMD Renoir                                                                  | 6         | 4.35%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 5         | 3.62%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 5         | 3.62%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 5         | 3.62%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 4         | 2.9%    |
| Intel HD Graphics 530                                                       | 4         | 2.9%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4         | 2.9%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 3         | 2.17%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 3         | 2.17%   |
| Nvidia GP108M [GeForce MX250]                                               | 2         | 1.45%   |
| Nvidia GP108M [GeForce MX150]                                               | 2         | 1.45%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2         | 1.45%   |
| Nvidia GK107GLM [Quadro K1100M]                                             | 2         | 1.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 1.45%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 2         | 1.45%   |
| Intel Iris Plus Graphics 640                                                | 2         | 1.45%   |
| Intel HD Graphics 5500                                                      | 2         | 1.45%   |
| Intel HD Graphics 515                                                       | 2         | 1.45%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2         | 1.45%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 0.72%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                               | 1         | 0.72%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                       | 1         | 0.72%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1         | 0.72%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1         | 0.72%   |
| Nvidia GT218 [NVS 300]                                                      | 1         | 0.72%   |
| Nvidia GT218 [GeForce G210]                                                 | 1         | 0.72%   |
| Nvidia GT216M [GeForce GT 330M]                                             | 1         | 0.72%   |
| Nvidia GT215M [GeForce GTS 250M]                                            | 1         | 0.72%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1         | 0.72%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 0.72%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1         | 0.72%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1         | 0.72%   |
| Nvidia GM108M [GeForce 840M]                                                | 1         | 0.72%   |
| Nvidia GM107M [GeForce GTX 950M]                                            | 1         | 0.72%   |
| Nvidia GM107M [GeForce GTX 850M]                                            | 1         | 0.72%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1         | 0.72%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1         | 0.72%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 49        | 43.75%  |
| Intel + Nvidia | 21        | 18.75%  |
| 1 x Nvidia     | 20        | 17.86%  |
| 1 x AMD        | 17        | 15.18%  |
| Intel + AMD    | 3         | 2.68%   |
| 2 x AMD        | 2         | 1.79%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 86        | 76.11%  |
| Proprietary | 22        | 19.47%  |
| Unknown     | 5         | 4.42%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 70        | 62.5%   |
| 0.01-0.5   | 11        | 9.82%   |
| 3.01-4.0   | 10        | 8.93%   |
| 1.01-2.0   | 10        | 8.93%   |
| 0.51-1.0   | 8         | 7.14%   |
| 8.01-16.0  | 2         | 1.79%   |
| 5.01-6.0   | 1         | 0.89%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 19        | 15.08%  |
| Chimei Innolux          | 16        | 12.7%   |
| LG Display              | 14        | 11.11%  |
| AU Optronics            | 9         | 7.14%   |
| Hewlett-Packard         | 6         | 4.76%   |
| Goldstar                | 6         | 4.76%   |
| Dell                    | 6         | 4.76%   |
| AOC                     | 6         | 4.76%   |
| Sharp                   | 5         | 3.97%   |
| Iiyama                  | 5         | 3.97%   |
| Apple                   | 5         | 3.97%   |
| Philips                 | 4         | 3.17%   |
| BOE                     | 4         | 3.17%   |
| Medion                  | 3         | 2.38%   |
| Chi Mei Optoelectronics | 3         | 2.38%   |
| BenQ                    | 3         | 2.38%   |
| Videoseven              | 1         | 0.79%   |
| Sony                    | 1         | 0.79%   |
| PAR                     | 1         | 0.79%   |
| PANDA                   | 1         | 0.79%   |
| Panasonic               | 1         | 0.79%   |
| MSI                     | 1         | 0.79%   |
| Lenovo                  | 1         | 0.79%   |
| Fujitsu Siemens         | 1         | 0.79%   |
| Eizo                    | 1         | 0.79%   |
| Belinea                 | 1         | 0.79%   |
| Aosiman                 | 1         | 0.79%   |
| Ancor Communications    | 1         | 0.79%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 2         | 1.56%   |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch               | 2         | 1.56%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 2         | 1.56%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 2         | 1.56%   |
| AOC 2250W AOC2250 1920x1080 477x268mm 21.5-inch                       | 2         | 1.56%   |
| Videoseven L27ADS IGM2700 1920x1080 598x336mm 27.0-inch               | 1         | 0.78%   |
| Sony NvidiaDefault SNY05FA 1366x768 290x170mm 13.2-inch               | 1         | 0.78%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch               | 1         | 0.78%   |
| Samsung Electronics T24B350 SAM093E 1920x1080 531x299mm 24.0-inch     | 1         | 0.78%   |
| Samsung Electronics SyncMaster SAM0612 1920x1080 604x342mm 27.3-inch  | 1         | 0.78%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch   | 1         | 0.78%   |
| Samsung Electronics SMT27A950 SAM080F 1920x1080 598x336mm 27.0-inch   | 1         | 0.78%   |
| Samsung Electronics SM2333T SAM0737 1920x1080 510x290mm 23.1-inch     | 1         | 0.78%   |
| Samsung Electronics S27D390 SAM0B67 1920x1080 598x336mm 27.0-inch     | 1         | 0.78%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch     | 1         | 0.78%   |
| Samsung Electronics LCD Monitor U28E590 3840x2160                     | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC444E 1600x900 310x174mm 14.0-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SDC5844 1920x1080 344x194mm 15.5-inch | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SDC4141 3840x2160 344x194mm 15.5-inch | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 890x500mm 40.2-inch | 1         | 0.78%   |
| Samsung Electronics C27R50x SAM0F9D 1920x1080 600x340mm 27.2-inch     | 1         | 0.78%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1         | 0.78%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 0.78%   |
| Philips PHL BDM3270 PHL08E7 2560x1440 708x398mm 32.0-inch             | 1         | 0.78%   |
| Philips PHL 346B1C PHL095C 3440x1440 797x334mm 34.0-inch              | 1         | 0.78%   |
| Philips PHL 275C5 PHLC0E4 1920x1080 598x336mm 27.0-inch               | 1         | 0.78%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch               | 1         | 0.78%   |
| PAR LED1920X1080 PAR9C63 1920x1080 710x400mm 32.1-inch                | 1         | 0.78%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 0.78%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch           | 1         | 0.78%   |
| MSI MPG27CQ MSI3FA3 2560x1440 600x340mm 27.2-inch                     | 1         | 0.78%   |
| Medion Medion23.6 PC MEDB603 1920x1080 477x268mm 21.5-inch            | 1         | 0.78%   |
| Medion MD 20122 MED3601 1680x1050 474x296mm 22.0-inch                 | 1         | 0.78%   |
| Medion 42FPDEUDA1 MED222E 1920x1080                                   | 1         | 0.78%   |
| LG Display LP156WH2-TLE1 LGDCF01 1366x768 344x194mm 15.5-inch         | 1         | 0.78%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 60        | 51.28%  |
| 1366x768 (WXGA)    | 15        | 12.82%  |
| 3840x2160 (4K)     | 11        | 9.4%    |
| 2560x1440 (QHD)    | 7         | 5.98%   |
| 1600x900 (HD+)     | 4         | 3.42%   |
| 1920x1200 (WUXGA)  | 3         | 2.56%   |
| 1680x1050 (WSXGA+) | 3         | 2.56%   |
| 3200x1800 (QHD+)   | 2         | 1.71%   |
| 1440x900 (WXGA+)   | 2         | 1.71%   |
| 1360x768           | 2         | 1.71%   |
| 1280x1024 (SXGA)   | 2         | 1.71%   |
| 3440x1440          | 1         | 0.85%   |
| 3072x1920          | 1         | 0.85%   |
| 2880x1800          | 1         | 0.85%   |
| 2560x1600          | 1         | 0.85%   |
| 1280x800 (WXGA)    | 1         | 0.85%   |
| 1024x768 (XGA)     | 1         | 0.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 32        | 25.2%   |
| 27      | 15        | 11.81%  |
| 17      | 11        | 8.66%   |
| 14      | 11        | 8.66%   |
| 13      | 10        | 7.87%   |
| 24      | 8         | 6.3%    |
| 23      | 8         | 6.3%    |
| 21      | 8         | 6.3%    |
| Unknown | 4         | 3.15%   |
| 22      | 3         | 2.36%   |
| 16      | 3         | 2.36%   |
| 72      | 2         | 1.57%   |
| 32      | 2         | 1.57%   |
| 18      | 2         | 1.57%   |
| 59      | 1         | 0.79%   |
| 46      | 1         | 0.79%   |
| 34      | 1         | 0.79%   |
| 33      | 1         | 0.79%   |
| 31      | 1         | 0.79%   |
| 25      | 1         | 0.79%   |
| 19      | 1         | 0.79%   |
| 11      | 1         | 0.79%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 49        | 39.52%  |
| 501-600     | 29        | 23.39%  |
| 401-500     | 13        | 10.48%  |
| 351-400     | 12        | 9.68%   |
| 201-300     | 7         | 5.65%   |
| 701-800     | 4         | 3.23%   |
| Unknown     | 4         | 3.23%   |
| 601-700     | 2         | 1.61%   |
| 1501-2000   | 2         | 1.61%   |
| 1001-1500   | 2         | 1.61%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 91        | 82.73%  |
| 16/10   | 13        | 11.82%  |
| 5/4     | 2         | 1.82%   |
| Unknown | 2         | 1.82%   |
| 4/3     | 1         | 0.91%   |
| 21/9    | 1         | 0.91%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 32        | 25.4%   |
| 201-250        | 24        | 19.05%  |
| 81-90          | 16        | 12.7%   |
| 301-350        | 15        | 11.9%   |
| 121-130        | 8         | 6.35%   |
| 71-80          | 5         | 3.97%   |
| 351-500        | 5         | 3.97%   |
| Unknown        | 4         | 3.17%   |
| More than 1000 | 3         | 2.38%   |
| 251-300        | 3         | 2.38%   |
| 141-150        | 3         | 2.38%   |
| 131-140        | 2         | 1.59%   |
| 111-120        | 2         | 1.59%   |
| 51-60          | 1         | 0.79%   |
| 151-200        | 1         | 0.79%   |
| 501-1000       | 1         | 0.79%   |
| 91-100         | 1         | 0.79%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 37        | 30.08%  |
| 121-160       | 35        | 28.46%  |
| 101-120       | 30        | 24.39%  |
| 161-240       | 10        | 8.13%   |
| More than 240 | 5         | 4.07%   |
| Unknown       | 4         | 3.25%   |
| 1-50          | 2         | 1.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 88        | 77.19%  |
| 2     | 19        | 16.67%  |
| 0     | 5         | 4.39%   |
| 3     | 2         | 1.75%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 76        | 44.97%  |
| Realtek Semiconductor           | 47        | 27.81%  |
| Qualcomm Atheros                | 16        | 9.47%   |
| Broadcom                        | 13        | 7.69%   |
| Marvell Technology Group        | 4         | 2.37%   |
| Sierra Wireless                 | 2         | 1.18%   |
| DisplayLink                     | 2         | 1.18%   |
| TP-Link                         | 1         | 0.59%   |
| Ralink Technology               | 1         | 0.59%   |
| Qualcomm Atheros Communications | 1         | 0.59%   |
| MediaTek                        | 1         | 0.59%   |
| Lenovo                          | 1         | 0.59%   |
| JMicron Technology              | 1         | 0.59%   |
| Broadcom Limited                | 1         | 0.59%   |
| ASIX Electronics                | 1         | 0.59%   |
| Unknown                         | 1         | 0.59%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 33        | 16.26%  |
| Intel Wi-Fi 6 AX200                                                            | 11        | 5.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 6         | 2.96%   |
| Realtek RTL8125 2.5GbE Controller                                              | 5         | 2.46%   |
| Intel Wireless 8260                                                            | 5         | 2.46%   |
| Intel I211 Gigabit Network Connection                                          | 5         | 2.46%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 5         | 2.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 4         | 1.97%   |
| Intel Wireless 8265 / 8275                                                     | 4         | 1.97%   |
| Intel Wireless 7260                                                            | 4         | 1.97%   |
| Intel Wireless 3160                                                            | 3         | 1.48%   |
| Intel Ethernet Connection I219-V                                               | 3         | 1.48%   |
| Intel Ethernet Connection (2) I219-V                                           | 3         | 1.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 1.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 0.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 2         | 0.99%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2         | 0.99%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 2         | 0.99%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.99%   |
| Intel Wireless-AC 9260                                                         | 2         | 0.99%   |
| Intel Wireless 7265                                                            | 2         | 0.99%   |
| Intel Wireless 3165                                                            | 2         | 0.99%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 2         | 0.99%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.99%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 0.99%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 0.99%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.99%   |
| Intel Ethernet Connection (2) I218-V                                           | 2         | 0.99%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 2         | 0.99%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 2         | 0.99%   |
| DisplayLink Dell D3100 Docking Station                                         | 2         | 0.99%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                             | 2         | 0.99%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 2         | 0.99%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                    | 1         | 0.49%   |
| Sierra Wireless EM7455                                                         | 1         | 0.49%   |
| Sierra Wireless EM7305 Modem                                                   | 1         | 0.49%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.49%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                    | 1         | 0.49%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 0.49%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 57        | 59.38%  |
| Qualcomm Atheros                | 13        | 13.54%  |
| Broadcom                        | 10        | 10.42%  |
| Realtek Semiconductor           | 8         | 8.33%   |
| Sierra Wireless                 | 2         | 2.08%   |
| TP-Link                         | 1         | 1.04%   |
| Ralink Technology               | 1         | 1.04%   |
| Qualcomm Atheros Communications | 1         | 1.04%   |
| MediaTek                        | 1         | 1.04%   |
| Marvell Technology Group        | 1         | 1.04%   |
| Broadcom Limited                | 1         | 1.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 11        | 11.46%  |
| Intel Wireless 8260                                            | 5         | 5.21%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 5         | 5.21%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 4         | 4.17%   |
| Intel Wireless 8265 / 8275                                     | 4         | 4.17%   |
| Intel Wireless 7260                                            | 4         | 4.17%   |
| Intel Wireless 3160                                            | 3         | 3.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 2.08%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 2.08%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 2.08%   |
| Intel Wireless-AC 9260                                         | 2         | 2.08%   |
| Intel Wireless 7265                                            | 2         | 2.08%   |
| Intel Wireless 3165                                            | 2         | 2.08%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 2.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 2.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 2.08%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 2         | 2.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 2.08%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 1.04%   |
| Sierra Wireless EM7455                                         | 1         | 1.04%   |
| Sierra Wireless EM7305 Modem                                   | 1         | 1.04%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.04%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 1.04%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 1.04%   |
| Realtek 802.11ac NIC                                           | 1         | 1.04%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 1.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 1.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 1.04%   |
| Qualcomm Atheros AR9271 802.11n                                | 1         | 1.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 1.04%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 1.04%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1         | 1.04%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 1.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.04%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter            | 1         | 1.04%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 1         | 1.04%   |
| Intel WiMAX/WiFi Link 5150                                     | 1         | 1.04%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 1         | 1.04%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 1.04%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 1.04%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 45        | 43.69%  |
| Intel                    | 40        | 38.83%  |
| Qualcomm Atheros         | 5         | 4.85%   |
| Broadcom                 | 5         | 4.85%   |
| Marvell Technology Group | 3         | 2.91%   |
| DisplayLink              | 2         | 1.94%   |
| Lenovo                   | 1         | 0.97%   |
| JMicron Technology       | 1         | 0.97%   |
| ASIX Electronics         | 1         | 0.97%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 33        | 31.43%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 6         | 5.71%   |
| Realtek RTL8125 2.5GbE Controller                                              | 5         | 4.76%   |
| Intel I211 Gigabit Network Connection                                          | 5         | 4.76%   |
| Intel Ethernet Connection I219-V                                               | 3         | 2.86%   |
| Intel Ethernet Connection (2) I219-V                                           | 3         | 2.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 2.86%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2         | 1.9%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.9%    |
| Intel Ethernet Connection I217-V                                               | 2         | 1.9%    |
| Intel Ethernet Connection I217-LM                                              | 2         | 1.9%    |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 1.9%    |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 1.9%    |
| Intel Ethernet Connection (2) I218-V                                           | 2         | 1.9%    |
| DisplayLink Dell D3100 Docking Station                                         | 2         | 1.9%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.95%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.95%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.95%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.95%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.95%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.95%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 0.95%   |
| Lenovo ThinkPad Lan                                                            | 1         | 0.95%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.95%   |
| Intel WiMAX Connection 2400m                                                   | 1         | 0.95%   |
| Intel Ethernet Controller I225-V                                               | 1         | 0.95%   |
| Intel Ethernet controller                                                      | 1         | 0.95%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.95%   |
| Intel Ethernet Connection (7) I219-V                                           | 1         | 0.95%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.95%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 0.95%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.95%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 0.95%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.95%   |
| Intel Ethernet Connection (17) I219-LM                                         | 1         | 0.95%   |
| Intel Ethernet Connection (11) I219-V                                          | 1         | 0.95%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 0.95%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 1         | 0.95%   |
| Intel 82566DC-2 Gigabit Network Connection                                     | 1         | 0.95%   |
| Intel 82566DC Gigabit Network Connection                                       | 1         | 0.95%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 95        | 50.26%  |
| WiFi     | 92        | 48.68%  |
| Modem    | 1         | 0.53%   |
| Unknown  | 1         | 0.53%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 65        | 54.62%  |
| Ethernet | 54        | 45.38%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 65        | 58.04%  |
| 1     | 42        | 37.5%   |
| 3     | 5         | 4.46%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 93        | 82.3%   |
| Yes  | 20        | 17.7%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 49        | 63.64%  |
| Foxconn / Hon Hai               | 5         | 6.49%   |
| Qualcomm Atheros Communications | 3         | 3.9%    |
| IMC Networks                    | 3         | 3.9%    |
| Cambridge Silicon Radio         | 3         | 3.9%    |
| Apple                           | 3         | 3.9%    |
| Realtek                         | 2         | 2.6%    |
| Hewlett-Packard                 | 2         | 2.6%    |
| Toshiba                         | 1         | 1.3%    |
| Realtek Semiconductor           | 1         | 1.3%    |
| Micro Star International        | 1         | 1.3%    |
| Marvell Semiconductor           | 1         | 1.3%    |
| Lite-On Technology              | 1         | 1.3%    |
| Broadcom                        | 1         | 1.3%    |
| ASUSTek Computer                | 1         | 1.3%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 19        | 24.68%  |
| Intel AX200 Bluetooth                                                               | 10        | 12.99%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 7         | 9.09%   |
| Intel AX201 Bluetooth                                                               | 5         | 6.49%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 3         | 3.9%    |
| Realtek Bluetooth Radio                                                             | 2         | 2.6%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 2.6%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 2.6%    |
| Intel AX210 Bluetooth                                                               | 2         | 2.6%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 2.6%    |
| Apple Bluetooth USB Host Controller                                                 | 2         | 2.6%    |
| Toshiba Bluetooth Device                                                            | 1         | 1.3%    |
| Realtek Bluetooth Radio                                                             | 1         | 1.3%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 1         | 1.3%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 1.3%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.3%    |
| Micro Star International Motorola Bluetooth 2.1+EDR Device                          | 1         | 1.3%    |
| Marvell Bluetooth and Wireless LAN Composite                                        | 1         | 1.3%    |
| Lite-On Bluetooth Device                                                            | 1         | 1.3%    |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 1.3%    |
| Intel Bluetooth Device                                                              | 1         | 1.3%    |
| IMC Networks Bluetooth Radio                                                        | 1         | 1.3%    |
| IMC Networks Bluetooth Module                                                       | 1         | 1.3%    |
| IMC Networks Bluetooth Device                                                       | 1         | 1.3%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.3%    |
| Foxconn / Hon Hai BT                                                                | 1         | 1.3%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 1.3%    |
| Foxconn / Hon Hai BCM43142A0                                                        | 1         | 1.3%    |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 1.3%    |
| Broadcom Bluetooth 3.0 Device                                                       | 1         | 1.3%    |
| ASUS BCM20702A0                                                                     | 1         | 1.3%    |
| Apple Bluetooth Host Controller                                                     | 1         | 1.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 92        | 61.74%  |
| AMD                            | 24        | 16.11%  |
| Nvidia                         | 22        | 14.77%  |
| Logitech                       | 2         | 1.34%   |
| www.hirestech.com 2010 REV 1.4 | 1         | 0.67%   |
| SteelSeries ApS                | 1         | 0.67%   |
| Sony                           | 1         | 0.67%   |
| Realtek Semiconductor          | 1         | 0.67%   |
| Lenovo                         | 1         | 0.67%   |
| Hewlett-Packard                | 1         | 0.67%   |
| C-Media Electronics            | 1         | 0.67%   |
| Bose                           | 1         | 0.67%   |
| Apple                          | 1         | 0.67%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 14        | 7.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13        | 7.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 11        | 6.04%   |
| AMD Family 17h/19h HD Audio Controller                                     | 10        | 5.49%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 8         | 4.4%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 3.3%    |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 2.75%   |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 2.75%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 2.75%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 2.75%   |
| Intel 200 Series PCH HD Audio                                              | 5         | 2.75%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5         | 2.75%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 2.2%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 2.2%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 2.2%    |
| Nvidia High Definition Audio Controller                                    | 3         | 1.65%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 1.65%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 1.65%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 1.65%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.65%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.1%    |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.1%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 1.1%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.1%    |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2         | 1.1%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 1.1%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.1%    |
| www.hirestech.com 2010 REV 1.4 Music Streamer Pro                          | 1         | 0.55%   |
| SteelSeries ApS SteelSeries Arctis 7                                       | 1         | 0.55%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 1         | 0.55%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.55%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.55%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.55%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.55%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.55%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.55%   |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 0.55%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.55%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.55%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 26        | 37.14%  |
| SK hynix                     | 10        | 14.29%  |
| Micron Technology            | 5         | 7.14%   |
| Kingston                     | 5         | 7.14%   |
| Corsair                      | 5         | 7.14%   |
| Unknown                      | 4         | 5.71%   |
| Crucial                      | 4         | 5.71%   |
| G.Skill                      | 3         | 4.29%   |
| A-DATA Technology            | 3         | 4.29%   |
| Qimonda                      | 2         | 2.86%   |
| Unknown (0x7F7FB5FFFFFFFFFF) | 1         | 1.43%   |
| Timetec                      | 1         | 1.43%   |
| Dane-Elec                    | 1         | 1.43%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 3         | 4%      |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s         | 2         | 2.67%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s      | 2         | 2.67%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s         | 2         | 2.67%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s        | 2         | 2.67%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s       | 2         | 2.67%   |
| Unknown RAM Module 4GB SODIMM DDR3                            | 1         | 1.33%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                  | 1         | 1.33%   |
| Unknown RAM Module 2GB SODIMM DDR2                            | 1         | 1.33%   |
| Unknown RAM Module 2048MB SODIMM DDR2                         | 1         | 1.33%   |
| Unknown RAM Module 1024MB SODIMM DDR2                         | 1         | 1.33%   |
| Unknown (0x7F7FB5FFFFFFFFFF) RAM Module 1GB DIMM DDR2 667MT/s | 1         | 1.33%   |
| Timetec RAM SD3-1333 8192MB SODIMM DDR3 1333MT/s              | 1         | 1.33%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s       | 1         | 1.33%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 1.33%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s        | 1         | 1.33%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s        | 1         | 1.33%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s       | 1         | 1.33%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s       | 1         | 1.33%   |
| SK hynix RAM HMA81GS6MFR8N-UH 8GB SODIMM DDR4 2400MT/s        | 1         | 1.33%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s        | 1         | 1.33%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                   | 1         | 1.33%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR4 2933MT/s           | 1         | 1.33%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                   | 1         | 1.33%   |
| Samsung RAM Module 4GB SODIMM DDR3 1067MT/s                   | 1         | 1.33%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                  | 1         | 1.33%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s               | 1         | 1.33%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s         | 1         | 1.33%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s         | 1         | 1.33%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s         | 1         | 1.33%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s         | 1         | 1.33%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s         | 1         | 1.33%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s        | 1         | 1.33%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s        | 1         | 1.33%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s         | 1         | 1.33%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s         | 1         | 1.33%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s      | 1         | 1.33%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s         | 1         | 1.33%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s         | 1         | 1.33%   |
| Samsung RAM M471A1G44AB0-CTD 8GB Row Of Chips DDR4 2667MT/s   | 1         | 1.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 34        | 53.13%  |
| DDR3   | 20        | 31.25%  |
| DDR2   | 5         | 7.81%   |
| LPDDR3 | 3         | 4.69%   |
| SDRAM  | 1         | 1.56%   |
| LPDDR4 | 1         | 1.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 42        | 66.67%  |
| DIMM         | 16        | 25.4%   |
| Row Of Chips | 5         | 7.94%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 32        | 46.38%  |
| 4096  | 13        | 18.84%  |
| 16384 | 12        | 17.39%  |
| 2048  | 8         | 11.59%  |
| 32768 | 2         | 2.9%    |
| 1024  | 2         | 2.9%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 15        | 22.73%  |
| 1600    | 12        | 18.18%  |
| 3200    | 8         | 12.12%  |
| 2400    | 7         | 10.61%  |
| 2133    | 5         | 7.58%   |
| 3600    | 3         | 4.55%   |
| Unknown | 3         | 4.55%   |
| 3400    | 2         | 3.03%   |
| 1333    | 2         | 3.03%   |
| 800     | 2         | 3.03%   |
| 3500    | 1         | 1.52%   |
| 2933    | 1         | 1.52%   |
| 2666    | 1         | 1.52%   |
| 1867    | 1         | 1.52%   |
| 1334    | 1         | 1.52%   |
| 1067    | 1         | 1.52%   |
| 667     | 1         | 1.52%   |

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
| Chicony Electronics                    | 22        | 32.84%  |
| Microdia                               | 8         | 11.94%  |
| IMC Networks                           | 8         | 11.94%  |
| Logitech                               | 4         | 5.97%   |
| Samsung Electronics                    | 3         | 4.48%   |
| Ricoh                                  | 3         | 4.48%   |
| Realtek Semiconductor                  | 3         | 4.48%   |
| Alcor Micro                            | 3         | 4.48%   |
| Sunplus Innovation Technology          | 2         | 2.99%   |
| Quanta                                 | 2         | 2.99%   |
| Apple                                  | 2         | 2.99%   |
| Acer                                   | 2         | 2.99%   |
| Unknown                                | 1         | 1.49%   |
| Huawei Technologies                    | 1         | 1.49%   |
| DJJHFA1BIF5595                         | 1         | 1.49%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.49%   |
| ALi                                    | 1         | 1.49%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD           | 4         | 5.97%   |
| IMC Networks USB2.0 HD UVC WebCam       | 4         | 5.97%   |
| Samsung Galaxy A5 (MTP)                 | 3         | 4.48%   |
| IMC Networks Integrated Camera          | 3         | 4.48%   |
| Chicony Integrated Camera               | 3         | 4.48%   |
| Realtek Integrated_Webcam_HD            | 2         | 2.99%   |
| Microdia Integrated Webcam              | 2         | 2.99%   |
| Logitech B525 HD Webcam                 | 2         | 2.99%   |
| Chicony Integrated Camera (1280x720@30) | 2         | 2.99%   |
| Chicony HP Wide Vision HD Camera        | 2         | 2.99%   |
| Chicony HP HD Camera                    | 2         | 2.99%   |
| Chicony HD Webcam                       | 2         | 2.99%   |
| Alcor Micro USB 2.0 Camera              | 2         | 2.99%   |
| Unknown 720p HD Camera                  | 1         | 1.49%   |
| Sunplus Laptop Integrated WebCam HD     | 1         | 1.49%   |
| Sunplus HP HD Webcam [Fixed]            | 1         | 1.49%   |
| Ricoh USB2.0 Camera                     | 1         | 1.49%   |
| Ricoh Sony Visual Communication Camera  | 1         | 1.49%   |
| Ricoh Sony Vaio Integrated Webcam       | 1         | 1.49%   |
| Realtek HP Truevision HD                | 1         | 1.49%   |
| Quanta HP Webcam                        | 1         | 1.49%   |
| Quanta HD User Facing                   | 1         | 1.49%   |
| Microdia Webcam                         | 1         | 1.49%   |
| Microdia Integrated_Webcam_FHD          | 1         | 1.49%   |
| Logitech Webcam C270                    | 1         | 1.49%   |
| Logitech HD Pro Webcam C920             | 1         | 1.49%   |
| IMC Networks ov9734_azurewave_camera    | 1         | 1.49%   |
| Huawei UVC Camera                       | 1         | 1.49%   |
| DJJHFA1BIF5595 HP HD Camera             | 1         | 1.49%   |
| Chicony USB2.0 VGA UVC WebCam           | 1         | 1.49%   |
| Chicony USB2.0 HD UVC WebCam            | 1         | 1.49%   |
| Chicony USB 2.0 Camera                  | 1         | 1.49%   |
| Chicony TOSHIBA Web Camera - HD         | 1         | 1.49%   |
| Chicony ThinkPad T490 Webcam            | 1         | 1.49%   |
| Chicony Integrated HP HD Webcam         | 1         | 1.49%   |
| Chicony HP Truevision HD                | 1         | 1.49%   |
| Chicony HD WebCam (Asus N-series)       | 1         | 1.49%   |
| Chicony FJ Camera                       | 1         | 1.49%   |
| Chicony EasyCamera                      | 1         | 1.49%   |
| Chicony Acer CrystalEye Webcam          | 1         | 1.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


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

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


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
| LighTuning ES603 Swipe Fingerprint Sensor                  | 1         | 5.26%   |
| Elan ELAN:Fingerprint                                      | 1         | 5.26%   |
| AuthenTec Fingerprint Sensor                               | 1         | 5.26%   |

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
| 0     | 68        | 59.65%  |
| 1     | 31        | 27.19%  |
| 2     | 13        | 11.4%   |
| 3     | 2         | 1.75%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 19        | 31.15%  |
| Graphics card            | 12        | 19.67%  |
| Multimedia controller    | 6         | 9.84%   |
| Chipcard                 | 6         | 9.84%   |
| Net/wireless             | 4         | 6.56%   |
| Network                  | 3         | 4.92%   |
| Communication controller | 3         | 4.92%   |
| Card reader              | 3         | 4.92%   |
| Unassigned class         | 1         | 1.64%   |
| Sound                    | 1         | 1.64%   |
| Net/ethernet             | 1         | 1.64%   |
| Camera                   | 1         | 1.64%   |
| Bluetooth                | 1         | 1.64%   |

