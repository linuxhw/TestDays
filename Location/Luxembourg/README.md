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

Total: 142

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 20        | 18.02%  |
| Ubuntu 18.04                 | 9         | 8.11%   |
| Ubuntu 21.04                 | 4         | 3.6%    |
| Linux Mint 20.3              | 4         | 3.6%    |
| Ubuntu 20.10                 | 3         | 2.7%    |
| Pop!_OS 21.04                | 3         | 2.7%    |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 2.7%    |
| OpenMandriva 4.2             | 3         | 2.7%    |
| Fedora 32                    | 3         | 2.7%    |
| Xubuntu 20.04                | 2         | 1.8%    |
| Ubuntu 18.10                 | 2         | 1.8%    |
| ROSA R9                      | 2         | 1.8%    |
| Pop!_OS 21.10                | 2         | 1.8%    |
| openSUSE Leap-15.2           | 2         | 1.8%    |
| OpenMandriva 4.90            | 2         | 1.8%    |
| LMDE 4                       | 2         | 1.8%    |
| Debian 10                    | 2         | 1.8%    |
| Xubuntu 18.04                | 1         | 0.9%    |
| Xubuntu 16.04                | 1         | 0.9%    |
| UbuntuDDE 20.04              | 1         | 0.9%    |
| Ubuntu MATE 21.10            | 1         | 0.9%    |
| Ubuntu MATE 20.04            | 1         | 0.9%    |
| Ubuntu 22.10                 | 1         | 0.9%    |
| Ubuntu 19.10                 | 1         | 0.9%    |
| RHEL 8                       | 1         | 0.9%    |
| Pop!_OS 20.10                | 1         | 0.9%    |
| Pop!_OS 20.04                | 1         | 0.9%    |
| openSUSE Leap-15.3           | 1         | 0.9%    |
| openSUSE Leap-15.1           | 1         | 0.9%    |
| OpenMandriva 4.3             | 1         | 0.9%    |
| Manjaro 21.2.6               | 1         | 0.9%    |
| Manjaro 21.1.0               | 1         | 0.9%    |
| Manjaro 19.0.2               | 1         | 0.9%    |
| Mageia 7                     | 1         | 0.9%    |
| Lubuntu 20.10                | 1         | 0.9%    |
| Lubuntu 20.04                | 1         | 0.9%    |
| Linux Mint 20.2              | 1         | 0.9%    |
| Linux Mint 20.1              | 1         | 0.9%    |
| Linux Mint 19.2              | 1         | 0.9%    |
| Kubuntu 20.04                | 1         | 0.9%    |
| Kubuntu 18.04                | 1         | 0.9%    |
| KDE neon 20.04               | 1         | 0.9%    |
| Kali 2021.3                  | 1         | 0.9%    |
| Garuda Linux Soaring         | 1         | 0.9%    |
| Fedora 36                    | 1         | 0.9%    |
| Fedora 34                    | 1         | 0.9%    |
| Fedora 33                    | 1         | 0.9%    |
| Endless 3.9.3                | 1         | 0.9%    |
| Endless 3.9.1                | 1         | 0.9%    |
| Endless 3.9.0                | 1         | 0.9%    |
| Endless 3.7.8                | 1         | 0.9%    |
| Elementary 6.1               | 1         | 0.9%    |
| Elementary 5.1.7             | 1         | 0.9%    |
| Debian 11                    | 1         | 0.9%    |
| Clear Linux 32820            | 1         | 0.9%    |
| CentOS 8                     | 1         | 0.9%    |
| BlackPanther 18.1            | 1         | 0.9%    |
| ArcoLinux Rolling            | 1         | 0.9%    |
| Arch Rolling                 | 1         | 0.9%    |
| Arch                         | 1         | 0.9%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 40        | 37.74%  |
| Pop!_OS      | 6         | 5.66%   |
| openSUSE     | 6         | 5.66%   |
| OpenMandriva | 6         | 5.66%   |
| Linux Mint   | 6         | 5.66%   |
| Fedora       | 6         | 5.66%   |
| Xubuntu      | 4         | 3.77%   |
| Manjaro      | 3         | 2.83%   |
| Debian       | 3         | 2.83%   |
| Ubuntu MATE  | 2         | 1.89%   |
| ROSA         | 2         | 1.89%   |
| Lubuntu      | 2         | 1.89%   |
| LMDE         | 2         | 1.89%   |
| Kubuntu      | 2         | 1.89%   |
| Endless      | 2         | 1.89%   |
| Elementary   | 2         | 1.89%   |
| Arch         | 2         | 1.89%   |
| UbuntuDDE    | 1         | 0.94%   |
| RHEL         | 1         | 0.94%   |
| Mageia       | 1         | 0.94%   |
| KDE neon     | 1         | 0.94%   |
| Kali         | 1         | 0.94%   |
| Garuda Linux | 1         | 0.94%   |
| Clear Linux  | 1         | 0.94%   |
| CentOS       | 1         | 0.94%   |
| BlackPanther | 1         | 0.94%   |
| ArcoLinux    | 1         | 0.94%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.8.0-43-generic                | 3         | 2.61%   |
| 5.11.0-27-generic               | 3         | 2.61%   |
| 5.10.14-desktop-1omv4002        | 3         | 2.61%   |
| 5.8.0-59-generic                | 2         | 1.74%   |
| 5.4.0-96-generic                | 2         | 1.74%   |
| 5.4.0-90-generic                | 2         | 1.74%   |
| 5.4.0-47-generic                | 2         | 1.74%   |
| 5.4.0-42-generic                | 2         | 1.74%   |
| 5.4.0-122-generic               | 2         | 1.74%   |
| 5.3.0-46-generic                | 2         | 1.74%   |
| 5.18.12-desktop-3omv4090        | 2         | 1.74%   |
| 5.16.11-76051611-generic        | 2         | 1.74%   |
| 5.11.0-34-generic               | 2         | 1.74%   |
| 5.11.0-17-generic               | 2         | 1.74%   |
| 5.0.0-23-generic                | 2         | 1.74%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 2         | 1.74%   |
| 4.19.0-17-amd64                 | 2         | 1.74%   |
| 5.9.13-zen1-1-zen               | 1         | 0.87%   |
| 5.9.10-200.fc33.x86_64          | 1         | 0.87%   |
| 5.8.11-050811-generic           | 1         | 0.87%   |
| 5.8.0-63-generic                | 1         | 0.87%   |
| 5.8.0-55-generic                | 1         | 0.87%   |
| 5.8.0-44-generic                | 1         | 0.87%   |
| 5.8.0-31-generic                | 1         | 0.87%   |
| 5.8.0-26-generic                | 1         | 0.87%   |
| 5.8.0-20-generic                | 1         | 0.87%   |
| 5.8.0-14-generic                | 1         | 0.87%   |
| 5.7.6-201.fc32.x86_64           | 1         | 0.87%   |
| 5.7.19-desktop-3.mga7           | 1         | 0.87%   |
| 5.7.14-200.fc32.x86_64          | 1         | 0.87%   |
| 5.7.1-1-default                 | 1         | 0.87%   |
| 5.7.0-3-amd64                   | 1         | 0.87%   |
| 5.7.0-050700-generic            | 1         | 0.87%   |
| 5.6.3-935.native                | 1         | 0.87%   |
| 5.5.8-1-MANJARO                 | 1         | 0.87%   |
| 5.4.0-91-generic                | 1         | 0.87%   |
| 5.4.0-84-generic                | 1         | 0.87%   |
| 5.4.0-73-generic                | 1         | 0.87%   |
| 5.4.0-72-generic                | 1         | 0.87%   |
| 5.4.0-58-generic                | 1         | 0.87%   |
| 5.4.0-56-generic                | 1         | 0.87%   |
| 5.4.0-52-generic                | 1         | 0.87%   |
| 5.4.0-40-generic                | 1         | 0.87%   |
| 5.4.0-37-generic                | 1         | 0.87%   |
| 5.4.0-21-generic                | 1         | 0.87%   |
| 5.3.18-lp152.66-default         | 1         | 0.87%   |
| 5.3.18-lp152.33-default         | 1         | 0.87%   |
| 5.3.18-59.19-preempt            | 1         | 0.87%   |
| 5.3.18-150300.59.49-preempt     | 1         | 0.87%   |
| 5.3.0-51-generic                | 1         | 0.87%   |
| 5.3.0-42-generic                | 1         | 0.87%   |
| 5.3.0-28-generic                | 1         | 0.87%   |
| 5.3.0-26-generic                | 1         | 0.87%   |
| 5.3.0-0.bpo.2-686-pae           | 1         | 0.87%   |
| 5.18.5-200.fc36.x86_64          | 1         | 0.87%   |
| 5.16.7-desktop-1omv4003         | 1         | 0.87%   |
| 5.16.2-arch1-1                  | 1         | 0.87%   |
| 5.15.4-zen1-1-zen               | 1         | 0.87%   |
| 5.15.32-1-MANJARO               | 1         | 0.87%   |
| 5.15.0-41-generic               | 1         | 0.87%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 19        | 17.59%  |
| 5.11.0  | 14        | 12.96%  |
| 5.8.0   | 10        | 9.26%   |
| 5.3.0   | 6         | 5.56%   |
| 4.18.0  | 6         | 5.56%   |
| 5.13.0  | 4         | 3.7%    |
| 5.15.0  | 3         | 2.78%   |
| 5.10.14 | 3         | 2.78%   |
| 5.0.0   | 3         | 2.78%   |
| 4.15.0  | 3         | 2.78%   |
| 5.7.0   | 2         | 1.85%   |
| 5.3.18  | 2         | 1.85%   |
| 5.18.12 | 2         | 1.85%   |
| 5.16.11 | 2         | 1.85%   |
| 5.10.0  | 2         | 1.85%   |
| 4.9.20  | 2         | 1.85%   |
| 4.19.0  | 2         | 1.85%   |
| 5.9.13  | 1         | 0.93%   |
| 5.9.10  | 1         | 0.93%   |
| 5.8.11  | 1         | 0.93%   |
| 5.7.6   | 1         | 0.93%   |
| 5.7.19  | 1         | 0.93%   |
| 5.7.14  | 1         | 0.93%   |
| 5.7.1   | 1         | 0.93%   |
| 5.6.3   | 1         | 0.93%   |
| 5.5.8   | 1         | 0.93%   |
| 5.18.5  | 1         | 0.93%   |
| 5.16.7  | 1         | 0.93%   |
| 5.16.2  | 1         | 0.93%   |
| 5.15.4  | 1         | 0.93%   |
| 5.15.32 | 1         | 0.93%   |
| 5.14.0  | 1         | 0.93%   |
| 5.13.4  | 1         | 0.93%   |
| 5.12.7  | 1         | 0.93%   |
| 5.12.13 | 1         | 0.93%   |
| 5.10.7  | 1         | 0.93%   |
| 5.10.26 | 1         | 0.93%   |
| 4.4.0   | 1         | 0.93%   |
| 4.18.16 | 1         | 0.93%   |
| 4.12.14 | 1         | 0.93%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 19        | 17.59%  |
| 5.11    | 14        | 12.96%  |
| 5.8     | 11        | 10.19%  |
| 5.3     | 8         | 7.41%   |
| 5.10    | 7         | 6.48%   |
| 4.18    | 7         | 6.48%   |
| 5.7     | 6         | 5.56%   |
| 5.15    | 5         | 4.63%   |
| 5.13    | 5         | 4.63%   |
| 5.16    | 4         | 3.7%    |
| 5.18    | 3         | 2.78%   |
| 5.0     | 3         | 2.78%   |
| 4.15    | 3         | 2.78%   |
| 5.9     | 2         | 1.85%   |
| 5.12    | 2         | 1.85%   |
| 4.9     | 2         | 1.85%   |
| 4.19    | 2         | 1.85%   |
| 5.6     | 1         | 0.93%   |
| 5.5     | 1         | 0.93%   |
| 5.14    | 1         | 0.93%   |
| 4.4     | 1         | 0.93%   |
| 4.12    | 1         | 0.93%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 102       | 98.08%  |
| i686   | 2         | 1.92%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 49        | 45.37%  |
| KDE5            | 15        | 13.89%  |
| Unknown         | 13        | 12.04%  |
| X-Cinnamon      | 8         | 7.41%   |
| XFCE            | 6         | 5.56%   |
| KDE             | 5         | 4.63%   |
| Pantheon        | 2         | 1.85%   |
| MATE            | 2         | 1.85%   |
| LXQt            | 2         | 1.85%   |
| i3              | 2         | 1.85%   |
| Cinnamon        | 2         | 1.85%   |
| GNOME Flashback | 1         | 0.93%   |
| Deepin          | 1         | 0.93%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 83        | 78.3%   |
| Wayland | 11        | 10.38%  |
| Unknown | 9         | 8.49%   |
| Tty     | 3         | 2.83%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 56        | 51.38%  |
| GDM     | 18        | 16.51%  |
| SDDM    | 15        | 13.76%  |
| LightDM | 13        | 11.93%  |
| TDM     | 4         | 3.67%   |
| GDM3    | 3         | 2.75%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 43        | 40.57%  |
| Unknown | 13        | 12.26%  |
| fr_FR   | 8         | 7.55%   |
| de_LU   | 7         | 6.6%    |
| en_GB   | 6         | 5.66%   |
| de_DE   | 6         | 5.66%   |
| C       | 5         | 4.72%   |
| fr_LU   | 4         | 3.77%   |
| es_ES   | 3         | 2.83%   |
| nl_NL   | 2         | 1.89%   |
| unm_US  | 1         | 0.94%   |
| pt_PT   | 1         | 0.94%   |
| pt_BR   | 1         | 0.94%   |
| POSIX   | 1         | 0.94%   |
| lb_LU   | 1         | 0.94%   |
| it_IT   | 1         | 0.94%   |
| hr_HR   | 1         | 0.94%   |
| en_IE   | 1         | 0.94%   |
| de_CH   | 1         | 0.94%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 54        | 51.43%  |
| BIOS | 51        | 48.57%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 77        | 74.04%  |
| Overlay | 9         | 8.65%   |
| Btrfs   | 8         | 7.69%   |
| Xfs     | 5         | 4.81%   |
| Unknown | 4         | 3.85%   |
| Zfs     | 1         | 0.96%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 57        | 54.81%  |
| GPT     | 41        | 39.42%  |
| MBR     | 6         | 5.77%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 94        | 89.52%  |
| Yes       | 11        | 10.48%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 74        | 70.48%  |
| Yes       | 31        | 29.52%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 18        | 17.31%  |
| Hewlett-Packard     | 14        | 13.46%  |
| Lenovo              | 12        | 11.54%  |
| Dell                | 8         | 7.69%   |
| Sony                | 5         | 4.81%   |
| Gigabyte Technology | 5         | 4.81%   |
| Apple               | 5         | 4.81%   |
| MSI                 | 4         | 3.85%   |
| Medion              | 4         | 3.85%   |
| Intel               | 4         | 3.85%   |
| Acer                | 4         | 3.85%   |
| Wortmann AG         | 3         | 2.88%   |
| ASRock              | 3         | 2.88%   |
| win element         | 2         | 1.92%   |
| Samsung Electronics | 2         | 1.92%   |
| Fujitsu             | 2         | 1.92%   |
| YJKC                | 1         | 0.96%   |
| TUXEDO              | 1         | 0.96%   |
| Toshiba             | 1         | 0.96%   |
| Timi                | 1         | 0.96%   |
| Packard Bell        | 1         | 0.96%   |
| Microsoft           | 1         | 0.96%   |
| HUAWEI              | 1         | 0.96%   |
| Foxconn             | 1         | 0.96%   |
| Clevo               | 1         | 0.96%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| ASUS All Series                          | 3         | 2.88%   |
| win element MoreFine S500+               | 2         | 1.92%   |
| Dell Precision M3800                     | 2         | 1.92%   |
| YJKC vBook                               | 1         | 0.96%   |
| Wortmann AG TERRA_MOBILE_1749            | 1         | 0.96%   |
| Wortmann AG TERRA_MOBILE_1541H           | 1         | 0.96%   |
| Wortmann AG MS-1727                      | 1         | 0.96%   |
| TUXEDO Pulse 14 Gen1                     | 1         | 0.96%   |
| Toshiba Satellite C55-A-1N0              | 1         | 0.96%   |
| Timi RedmiBook 14 II                     | 1         | 0.96%   |
| Sony VPCP11S1R                           | 1         | 0.96%   |
| Sony VPCEB2E1E                           | 1         | 0.96%   |
| Sony VPCCA4E1E                           | 1         | 0.96%   |
| Sony VGN-NS30E_S                         | 1         | 0.96%   |
| Sony SVF1421E2EW                         | 1         | 0.96%   |
| Samsung Galaxy TabPro S LTE              | 1         | 0.96%   |
| Samsung 950QDB                           | 1         | 0.96%   |
| Packard Bell EasyNote TJ65               | 1         | 0.96%   |
| MSI MS-7C80                              | 1         | 0.96%   |
| MSI MS-7C08                              | 1         | 0.96%   |
| MSI MS-7578                              | 1         | 0.96%   |
| MSI GF72 8RD                             | 1         | 0.96%   |
| Microsoft Surface Book 2                 | 1         | 0.96%   |
| Medion P961x                             | 1         | 0.96%   |
| Medion P6685 MD61138                     | 1         | 0.96%   |
| Medion MS-7848                           | 1         | 0.96%   |
| Medion E4254 MD62100                     | 1         | 0.96%   |
| Lenovo ThinkPad X1 Carbon 7th 20QDCTO1WW | 1         | 0.96%   |
| Lenovo ThinkPad T590 20N4CTO1WW          | 1         | 0.96%   |
| Lenovo ThinkPad T490 20N3S5DV0S          | 1         | 0.96%   |
| Lenovo ThinkPad T480s 20L7001PFR         | 1         | 0.96%   |
| Lenovo ThinkPad T470s W10DG 20JTS0R800   | 1         | 0.96%   |
| Lenovo ThinkPad T440p 20AWS24B00         | 1         | 0.96%   |
| Lenovo ThinkPad P1 Gen 2 20QTCTO1WW      | 1         | 0.96%   |
| Lenovo ThinkPad L15 Gen 1 20U8S0AH00     | 1         | 0.96%   |
| Lenovo ThinkPad L15 Gen 1 20U7S05B00     | 1         | 0.96%   |
| Lenovo ThinkCentre M910s 10MKS02N04      | 1         | 0.96%   |
| Lenovo IdeaPad 330-15ICH 81FK            | 1         | 0.96%   |
| Lenovo G50-70 20351                      | 1         | 0.96%   |
| Intel NUC7i5BNB J31144-303               | 1         | 0.96%   |
| Intel NUC5i3RYB H41000-505               | 1         | 0.96%   |
| Intel DG965SS AAD41678-308               | 1         | 0.96%   |
| Intel DG41WV AAE90316-104                | 1         | 0.96%   |
| HUAWEI HLYL-WXX9                         | 1         | 0.96%   |
| HP Spectre Laptop 13-af0xx               | 1         | 0.96%   |
| HP ProBook 6450b                         | 1         | 0.96%   |
| HP ProBook 450 G6                        | 1         | 0.96%   |
| HP Pavilion Gaming Notebook              | 1         | 0.96%   |
| HP ENVY x360 Convertible 15m-cn0xxx      | 1         | 0.96%   |
| HP ENVY Laptop 17-ce1xxx                 | 1         | 0.96%   |
| HP ENVY 15 x360 PC                       | 1         | 0.96%   |
| HP EliteDesk 800 G3 DM 35W               | 1         | 0.96%   |
| HP EliteBook 8560p                       | 1         | 0.96%   |
| HP EliteBook 850 G8 Notebook PC          | 1         | 0.96%   |
| HP EliteBook 8470p                       | 1         | 0.96%   |
| HP Compaq dc5800 Small Form Factor       | 1         | 0.96%   |
| HP Compaq 6000 Pro SFF PC                | 1         | 0.96%   |
| HP 255 G6 Notebook PC                    | 1         | 0.96%   |
| Gigabyte Z97X-Gaming 5                   | 1         | 0.96%   |
| Gigabyte Z270M-D3H                       | 1         | 0.96%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 9         | 8.65%   |
| Dell Precision        | 4         | 3.85%   |
| ASUS PRIME            | 4         | 3.85%   |
| HP ENVY               | 3         | 2.88%   |
| HP EliteBook          | 3         | 2.88%   |
| ASUS All              | 3         | 2.88%   |
| Acer Aspire           | 3         | 2.88%   |
| Wortmann AG TERRA     | 2         | 1.92%   |
| win element MoreFine  | 2         | 1.92%   |
| HP ProBook            | 2         | 1.92%   |
| HP Compaq             | 2         | 1.92%   |
| Dell XPS              | 2         | 1.92%   |
| ASUS VivoBook         | 2         | 1.92%   |
| ASUS TUF              | 2         | 1.92%   |
| ASUS ROG              | 2         | 1.92%   |
| YJKC vBook            | 1         | 0.96%   |
| Wortmann AG MS-1727   | 1         | 0.96%   |
| TUXEDO Pulse          | 1         | 0.96%   |
| Toshiba Satellite     | 1         | 0.96%   |
| Timi RedmiBook        | 1         | 0.96%   |
| Sony VPCP11S1R        | 1         | 0.96%   |
| Sony VPCEB2E1E        | 1         | 0.96%   |
| Sony VPCCA4E1E        | 1         | 0.96%   |
| Sony VGN-NS30E        | 1         | 0.96%   |
| Sony SVF1421E2EW      | 1         | 0.96%   |
| Samsung Galaxy        | 1         | 0.96%   |
| Samsung 950QDB        | 1         | 0.96%   |
| Packard Bell EasyNote | 1         | 0.96%   |
| MSI MS-7C80           | 1         | 0.96%   |
| MSI MS-7C08           | 1         | 0.96%   |
| MSI MS-7578           | 1         | 0.96%   |
| MSI GF72              | 1         | 0.96%   |
| Microsoft Surface     | 1         | 0.96%   |
| Medion P961x          | 1         | 0.96%   |
| Medion P6685          | 1         | 0.96%   |
| Medion MS-7848        | 1         | 0.96%   |
| Medion E4254          | 1         | 0.96%   |
| Lenovo ThinkCentre    | 1         | 0.96%   |
| Lenovo IdeaPad        | 1         | 0.96%   |
| Lenovo G50-70         | 1         | 0.96%   |
| Intel NUC7i5BNB       | 1         | 0.96%   |
| Intel NUC5i3RYB       | 1         | 0.96%   |
| Intel DG965SS         | 1         | 0.96%   |
| Intel DG41WV          | 1         | 0.96%   |
| HUAWEI HLYL-WXX9      | 1         | 0.96%   |
| HP Spectre            | 1         | 0.96%   |
| HP Pavilion           | 1         | 0.96%   |
| HP EliteDesk          | 1         | 0.96%   |
| HP 255                | 1         | 0.96%   |
| Gigabyte Z97X-Gaming  | 1         | 0.96%   |
| Gigabyte Z270M-D3H    | 1         | 0.96%   |
| Gigabyte X99-UD3-CF   | 1         | 0.96%   |
| Gigabyte X570         | 1         | 0.96%   |
| Gigabyte H81M-DS2     | 1         | 0.96%   |
| Fujitsu STYLISTIC     | 1         | 0.96%   |
| Fujitsu LIFEBOOK      | 1         | 0.96%   |
| Foxconn p6601fr-m     | 1         | 0.96%   |
| Dell Vostro           | 1         | 0.96%   |
| Dell Inspiron         | 1         | 0.96%   |
| Clevo P170EM          | 1         | 0.96%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2018 | 15        | 14.42%  |
| 2019 | 14        | 13.46%  |
| 2013 | 11        | 10.58%  |
| 2020 | 9         | 8.65%   |
| 2017 | 9         | 8.65%   |
| 2014 | 9         | 8.65%   |
| 2010 | 9         | 8.65%   |
| 2021 | 6         | 5.77%   |
| 2016 | 5         | 4.81%   |
| 2015 | 5         | 4.81%   |
| 2011 | 4         | 3.85%   |
| 2012 | 3         | 2.88%   |
| 2009 | 3         | 2.88%   |
| 2008 | 1         | 0.96%   |
| 2007 | 1         | 0.96%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 65        | 62.5%   |
| Desktop     | 31        | 29.81%  |
| Mini pc     | 3         | 2.88%   |
| Tablet      | 2         | 1.92%   |
| Convertible | 2         | 1.92%   |
| All in one  | 1         | 0.96%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 95        | 91.35%  |
| Enabled  | 9         | 8.65%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 104       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 30        | 28.85%  |
| 8.01-16.0   | 22        | 21.15%  |
| 4.01-8.0    | 20        | 19.23%  |
| 3.01-4.0    | 16        | 15.38%  |
| 32.01-64.0  | 9         | 8.65%   |
| 64.01-256.0 | 3         | 2.88%   |
| 1.01-2.0    | 2         | 1.92%   |
| 24.01-32.0  | 1         | 0.96%   |
| 2.01-3.0    | 1         | 0.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 32        | 29.63%  |
| 1.01-2.0   | 29        | 26.85%  |
| 4.01-8.0   | 20        | 18.52%  |
| 3.01-4.0   | 13        | 12.04%  |
| 8.01-16.0  | 9         | 8.33%   |
| 0.51-1.0   | 3         | 2.78%   |
| 24.01-32.0 | 1         | 0.93%   |
| 0.01-0.5   | 1         | 0.93%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 60        | 56.6%   |
| 2      | 26        | 24.53%  |
| 3      | 11        | 10.38%  |
| 4      | 4         | 3.77%   |
| 5      | 2         | 1.89%   |
| 0      | 2         | 1.89%   |
| 7      | 1         | 0.94%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 64        | 61.54%  |
| Yes       | 40        | 38.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 88        | 84.62%  |
| No        | 16        | 15.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 85        | 80.95%  |
| No        | 20        | 19.05%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 71        | 68.27%  |
| No        | 33        | 31.73%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country    | Computers | Percent |
|------------|-----------|---------|
| Luxembourg | 104       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Luxembourg        | 52        | 47.27%  |
| Strassen          | 9         | 8.18%   |
| Useldange         | 3         | 2.73%   |
| Schifflange       | 3         | 2.73%   |
| Schieren          | 3         | 2.73%   |
| Ehnen             | 3         | 2.73%   |
| Differdange       | 3         | 2.73%   |
| Wormeldange       | 2         | 1.82%   |
| Steinfort         | 2         | 1.82%   |
| Sanem             | 2         | 1.82%   |
| Esch-sur-Alzette  | 2         | 1.82%   |
| Bettange-sur-Mess | 2         | 1.82%   |
| Wiltz             | 1         | 0.91%   |
| Wecker            | 1         | 0.91%   |
| Vianden           | 1         | 0.91%   |
| Soleuvre          | 1         | 0.91%   |
| Roeser            | 1         | 0.91%   |
| Pontpierre        | 1         | 0.91%   |
| PerlГ©          | 1         | 0.91%   |
| Oberpallen        | 1         | 0.91%   |
| Niederanven       | 1         | 0.91%   |
| Leudelange        | 1         | 0.91%   |
| Kopstal           | 1         | 0.91%   |
| Junglinster       | 1         | 0.91%   |
| Itzig             | 1         | 0.91%   |
| Hunsdorf          | 1         | 0.91%   |
| Hosingen          | 1         | 0.91%   |
| Hesperange        | 1         | 0.91%   |
| Ettelbruck        | 1         | 0.91%   |
| Echternach        | 1         | 0.91%   |
| Diekirch          | 1         | 0.91%   |
| Bourscheid        | 1         | 0.91%   |
| Bettembourg       | 1         | 0.91%   |
| Belvaux           | 1         | 0.91%   |
| Beckerich         | 1         | 0.91%   |
| Aspelt            | 1         | 0.91%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 36        | 48     | 24.32%  |
| Seagate                   | 21        | 28     | 14.19%  |
| WDC                       | 18        | 28     | 12.16%  |
| Toshiba                   | 10        | 13     | 6.76%   |
| Crucial                   | 10        | 14     | 6.76%   |
| SanDisk                   | 8         | 11     | 5.41%   |
| Kingston                  | 7         | 10     | 4.73%   |
| Apple                     | 5         | 6      | 3.38%   |
| SK hynix                  | 3         | 3      | 2.03%   |
| Transcend                 | 2         | 2      | 1.35%   |
| LITEONIT                  | 2         | 2      | 1.35%   |
| LITEON                    | 2         | 2      | 1.35%   |
| Intenso                   | 2         | 3      | 1.35%   |
| Intel                     | 2         | 2      | 1.35%   |
| Hitachi                   | 2         | 3      | 1.35%   |
| HGST                      | 2         | 3      | 1.35%   |
| Union Memory (Shenzhen)   | 1         | 1      | 0.68%   |
| TCSUNBOW                  | 1         | 1      | 0.68%   |
| SABRENT                   | 1         | 1      | 0.68%   |
| Phison                    | 1         | 1      | 0.68%   |
| PHD 3.0                   | 1         | 1      | 0.68%   |
| OCZ                       | 1         | 1      | 0.68%   |
| Micron/Crucial Technology | 1         | 1      | 0.68%   |
| Micron Technology         | 1         | 2      | 0.68%   |
| Maxtor                    | 1         | 2      | 0.68%   |
| LaCie                     | 1         | 1      | 0.68%   |
| KingSpec                  | 1         | 1      | 0.68%   |
| KingDian                  | 1         | 1      | 0.68%   |
| Inateck                   | 1         | 1      | 0.68%   |
| Gigabyte Technology       | 1         | 1      | 0.68%   |
| FORESEE                   | 1         | 1      | 0.68%   |
| A-DATA Technology         | 1         | 1      | 0.68%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seagate Expansion 500GB                      | 3         | 1.8%    |
| Samsung SSD 840 EVO 250GB                    | 3         | 1.8%    |
| WDC WD10JPVX-22JC3T0 1TB                     | 2         | 1.2%    |
| Toshiba MQ01ABF050 500GB                     | 2         | 1.2%    |
| Seagate ST1000LM035-1RK172 1TB               | 2         | 1.2%    |
| SanDisk SD8SN8U128G1122 128GB SSD            | 2         | 1.2%    |
| SanDisk NVMe SSD Drive 1TB                   | 2         | 1.2%    |
| Samsung SSD 860 QVO 1TB                      | 2         | 1.2%    |
| Samsung SSD 860 EVO 250GB                    | 2         | 1.2%    |
| Samsung SSD 850 EVO 250GB                    | 2         | 1.2%    |
| Samsung SP2504C 250GB                        | 2         | 1.2%    |
| Samsung MZVLW256HEHP-000L7 256GB             | 2         | 1.2%    |
| LITEONIT LMT-256L9M-11 MSATA 256GB SSD       | 2         | 1.2%    |
| Kingston SA400S37240G 240GB SSD              | 2         | 1.2%    |
| Crucial CT240BX500SSD1 240GB                 | 2         | 1.2%    |
| Crucial CT1000P2SSD8 1TB                     | 2         | 1.2%    |
| WDC WDS500G3X0C-00SJG0 500GB                 | 1         | 0.6%    |
| WDC WDS250G2B0B-00YS70 250GB SSD             | 1         | 0.6%    |
| WDC WD5000AAVS-00ZTB0 500GB                  | 1         | 0.6%    |
| WDC WD5000AAKS-60Z1A0 500GB                  | 1         | 0.6%    |
| WDC WD40EZRZ-75GXCB0 4TB                     | 1         | 0.6%    |
| WDC WD4000FYYZ-01UL1B2 4TB                   | 1         | 0.6%    |
| WDC WD3200LPCX-00VHAT0 320GB                 | 1         | 0.6%    |
| WDC WD3001FFSX-68JNUN0 3TB                   | 1         | 0.6%    |
| WDC WD3000GLFS-01F8U0 304GB                  | 1         | 0.6%    |
| WDC WD20EFAX-68FB5N0 2TB                     | 1         | 0.6%    |
| WDC WD141KRYZ-01C66B0 14TB                   | 1         | 0.6%    |
| WDC WD10SPZX-17Z10T0 1TB                     | 1         | 0.6%    |
| WDC WD10SPCX-60HWST0 1TB                     | 1         | 0.6%    |
| WDC WD10EZRX-00A8LB0 1TB                     | 1         | 0.6%    |
| WDC WD10EZEX-60ZF5A0 1TB                     | 1         | 0.6%    |
| WDC WD10EZEX-08WN4A0 1TB                     | 1         | 0.6%    |
| WDC WD10EARS-00Y5B1 1TB                      | 1         | 0.6%    |
| WDC WD10EACS-00D6B1 1TB                      | 1         | 0.6%    |
| WDC WD1001FALS-00J7B0 1TB                    | 1         | 0.6%    |
| WDC PC SN730 SDBQNTY-512G-1001 512GB         | 1         | 0.6%    |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB           | 1         | 0.6%    |
| WDC PC SN730 SDBPNTY-512G-1027 512GB         | 1         | 0.6%    |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 0.6%    |
| Transcend TS512GSSD370 512GB                 | 1         | 0.6%    |
| Transcend TS256GMTS800 256GB SSD             | 1         | 0.6%    |
| Toshiba NVMe SSD Drive 512GB                 | 1         | 0.6%    |
| Toshiba MQ02ABD100H 1TB                      | 1         | 0.6%    |
| Toshiba MK7575GSX 752GB                      | 1         | 0.6%    |
| Toshiba MK6459GSXP 640GB                     | 1         | 0.6%    |
| Toshiba MK2555GSX 250GB                      | 1         | 0.6%    |
| Toshiba MG03ACA100 1TB                       | 1         | 0.6%    |
| Toshiba KXG60PNV2T04 NVMe KIOXIA 2048GB      | 1         | 0.6%    |
| Toshiba DT01ACA050 500GB                     | 1         | 0.6%    |
| TCSUNBOW X3 240GB SSD                        | 1         | 0.6%    |
| SK hynix PC401 HFS256GD9TNG-62A0A 256GB      | 1         | 0.6%    |
| SK hynix HFS128G39TND-N210A 128GB SSD        | 1         | 0.6%    |
| SK hynix HCG8e  64GB                         | 1         | 0.6%    |
| Seagate ST950042 0ASG 500GB                  | 1         | 0.6%    |
| Seagate ST9320423AS 320GB                    | 1         | 0.6%    |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 0.6%    |
| Seagate ST500DM002-1BD142 500GB              | 1         | 0.6%    |
| Seagate ST4000VN008-2DR166 4TB               | 1         | 0.6%    |
| Seagate ST4000DM004-2CV104 4TB               | 1         | 0.6%    |
| Seagate ST3750630AS 752GB                    | 1         | 0.6%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 26     | 37.25%  |
| WDC                 | 13        | 23     | 25.49%  |
| Toshiba             | 8         | 11     | 15.69%  |
| Samsung Electronics | 2         | 2      | 3.92%   |
| Hitachi             | 2         | 3      | 3.92%   |
| HGST                | 2         | 3      | 3.92%   |
| Apple               | 2         | 2      | 3.92%   |
| SABRENT             | 1         | 1      | 1.96%   |
| PHD 3.0             | 1         | 1      | 1.96%   |
| Intenso             | 1         | 1      | 1.96%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 24        | 32     | 38.71%  |
| Crucial             | 8         | 12     | 12.9%   |
| SanDisk             | 7         | 8      | 11.29%  |
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
| Inateck             | 1         | 1      | 1.61%   |
| FORESEE             | 1         | 1      | 1.61%   |
| Apple               | 1         | 1      | 1.61%   |
| A-DATA Technology   | 1         | 1      | 1.61%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 50        | 81     | 36.76%  |
| HDD     | 47        | 73     | 34.56%  |
| NVMe    | 36        | 39     | 26.47%  |
| Unknown | 2         | 2      | 1.47%   |
| MMC     | 1         | 1      | 0.74%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 76        | 145    | 62.3%   |
| NVMe | 36        | 39     | 29.51%  |
| SAS  | 9         | 11     | 7.38%   |
| MMC  | 1         | 1      | 0.82%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 61        | 95     | 57.55%  |
| 0.51-1.0   | 32        | 44     | 30.19%  |
| 1.01-2.0   | 5         | 6      | 4.72%   |
| 3.01-4.0   | 4         | 4      | 3.77%   |
| 2.01-3.0   | 3         | 4      | 2.83%   |
| 10.01-20.0 | 1         | 1      | 0.94%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 30        | 28.57%  |
| 251-500        | 21        | 20%     |
| 501-1000       | 15        | 14.29%  |
| Unknown        | 10        | 9.52%   |
| More than 3000 | 7         | 6.67%   |
| 1001-2000      | 7         | 6.67%   |
| 2001-3000      | 5         | 4.76%   |
| 1-20           | 5         | 4.76%   |
| 51-100         | 4         | 3.81%   |
| 21-50          | 1         | 0.95%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 37        | 34.58%  |
| 101-250        | 16        | 14.95%  |
| 21-50          | 14        | 13.08%  |
| 51-100         | 10        | 9.35%   |
| Unknown        | 10        | 9.35%   |
| 501-1000       | 8         | 7.48%   |
| 251-500        | 6         | 5.61%   |
| 2001-3000      | 3         | 2.8%    |
| 1001-2000      | 2         | 1.87%   |
| More than 3000 | 1         | 0.93%   |

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
| Detected | 57        | 113    | 52.78%  |
| Works    | 46        | 77     | 42.59%  |
| Malfunc  | 5         | 6      | 4.63%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 73        | 57.48%  |
| AMD                          | 15        | 11.81%  |
| Samsung Electronics          | 14        | 11.02%  |
| SanDisk                      | 7         | 5.51%   |
| Micron/Crucial Technology    | 3         | 2.36%   |
| Kingston Technology Company  | 3         | 2.36%   |
| Toshiba America Info Systems | 2         | 1.57%   |
| Phison Electronics           | 2         | 1.57%   |
| Marvell Technology Group     | 2         | 1.57%   |
| Apple                        | 2         | 1.57%   |
| Union Memory (Shenzhen)      | 1         | 0.79%   |
| SK hynix                     | 1         | 0.79%   |
| Seagate Technology           | 1         | 0.79%   |
| ASMedia Technology           | 1         | 0.79%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 13        | 9.49%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 12        | 8.76%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 5.11%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 3.65%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 3.65%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 5         | 3.65%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 4         | 2.92%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 2.92%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 2.92%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 2.92%   |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 2.92%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 2.19%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 2.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 3         | 2.19%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 2.19%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 1.46%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 1.46%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 1.46%   |
| Phison E12 NVMe Controller                                                     | 2         | 1.46%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2         | 1.46%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 1.46%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 1.46%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 1.46%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.46%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2         | 1.46%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 1.46%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 0.73%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 1         | 0.73%   |
| Seagate FireCuda 520 SSD                                                       | 1         | 0.73%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 0.73%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 0.73%   |
| Samsung Electronics Non-Volatile memory controller                             | 1         | 0.73%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1         | 0.73%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 1         | 0.73%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                      | 1         | 0.73%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 0.73%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 1         | 0.73%   |
| Kingston Company KC2000 NVMe SSD                                               | 1         | 0.73%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                     | 1         | 0.73%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 0.73%   |
| Intel SSD 660P Series                                                          | 1         | 0.73%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 0.73%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1         | 0.73%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 0.73%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 0.73%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 0.73%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 1         | 0.73%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                         | 1         | 0.73%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 1         | 0.73%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]            | 1         | 0.73%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                   | 1         | 0.73%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]  | 1         | 0.73%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]  | 1         | 0.73%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1         | 0.73%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 0.73%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 0.73%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1         | 0.73%   |
| Apple S3X NVMe Controller                                                      | 1         | 0.73%   |
| Apple ANS2 NVMe Controller                                                     | 1         | 0.73%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 1         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 79        | 62.2%   |
| NVMe | 37        | 29.13%  |
| IDE  | 6         | 4.72%   |
| RAID | 5         | 3.94%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 85        | 81.73%  |
| AMD    | 19        | 18.27%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz           | 4         | 3.85%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 3         | 2.88%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 2         | 1.92%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 2         | 1.92%   |
| Intel Core i7-4702HQ CPU @ 2.20GHz          | 2         | 1.92%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 2         | 1.92%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 2         | 1.92%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 2         | 1.92%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2         | 1.92%   |
| AMD Ryzen 9 5900HX with Radeon Graphics     | 2         | 1.92%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2         | 1.92%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.96%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 0.96%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 0.96%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 1         | 0.96%   |
| Intel Pentium CPU P6000 @ 1.87GHz           | 1         | 0.96%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 1         | 0.96%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 1         | 0.96%   |
| Intel Pentium CPU 987 @ 1.50GHz             | 1         | 0.96%   |
| Intel Core m5-6Y54 CPU @ 1.10GHz            | 1         | 0.96%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz            | 1         | 0.96%   |
| Intel Core i9-9880H CPU @ 2.30GHz           | 1         | 0.96%   |
| Intel Core i7-9700KF CPU @ 3.60GHz          | 1         | 0.96%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 0.96%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 0.96%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.96%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1         | 0.96%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 0.96%   |
| Intel Core i7-6800K CPU @ 3.40GHz           | 1         | 0.96%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 0.96%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 0.96%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 0.96%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1         | 0.96%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 0.96%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1         | 0.96%   |
| Intel Core i7-4712MQ CPU @ 2.30GHz          | 1         | 0.96%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz          | 1         | 0.96%   |
| Intel Core i7-3940XM CPU @ 3.00GHz          | 1         | 0.96%   |
| Intel Core i7-3840QM CPU @ 2.80GHz          | 1         | 0.96%   |
| Intel Core i7-10700K CPU @ 3.80GHz          | 1         | 0.96%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 1         | 0.96%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 0.96%   |
| Intel Core i5-8257U CPU @ 1.40GHz           | 1         | 0.96%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 0.96%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1         | 0.96%   |
| Intel Core i5-7360U CPU @ 2.30GHz           | 1         | 0.96%   |
| Intel Core i5-7260U CPU @ 2.20GHz           | 1         | 0.96%   |
| Intel Core i5-6600T CPU @ 2.70GHz           | 1         | 0.96%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 1         | 0.96%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1         | 0.96%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 0.96%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz          | 1         | 0.96%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1         | 0.96%   |
| Intel Core i5-4330M CPU @ 2.80GHz           | 1         | 0.96%   |
| Intel Core i5-4250U CPU @ 1.30GHz           | 1         | 0.96%   |
| Intel Core i5-4210M CPU @ 2.60GHz           | 1         | 0.96%   |
| Intel Core i5-4200M CPU @ 2.50GHz           | 1         | 0.96%   |
| Intel Core i5-3427U CPU @ 1.80GHz           | 1         | 0.96%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 1         | 0.96%   |
| Intel Core i5-2435M CPU @ 2.40GHz           | 1         | 0.96%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 30        | 28.85%  |
| Intel Core i5           | 25        | 24.04%  |
| Intel Core i3           | 7         | 6.73%   |
| AMD Ryzen 5             | 6         | 5.77%   |
| Other                   | 4         | 3.85%   |
| Intel Pentium           | 4         | 3.85%   |
| AMD Ryzen 9             | 4         | 3.85%   |
| Intel Pentium Dual-Core | 3         | 2.88%   |
| Intel Celeron           | 3         | 2.88%   |
| AMD Ryzen 7             | 3         | 2.88%   |
| Intel Core 2 Quad       | 2         | 1.92%   |
| Intel Pentium Silver    | 1         | 0.96%   |
| Intel Core m5           | 1         | 0.96%   |
| Intel Core m3           | 1         | 0.96%   |
| Intel Core i9           | 1         | 0.96%   |
| Intel Core 2 Duo        | 1         | 0.96%   |
| Intel Core 2            | 1         | 0.96%   |
| Intel Atom              | 1         | 0.96%   |
| AMD Ryzen 7 PRO         | 1         | 0.96%   |
| AMD Ryzen 5 PRO         | 1         | 0.96%   |
| AMD Phenom II X4        | 1         | 0.96%   |
| AMD FX                  | 1         | 0.96%   |
| AMD E2                  | 1         | 0.96%   |
| AMD Athlon II X4        | 1         | 0.96%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 40        | 38.46%  |
| 2       | 37        | 35.58%  |
| 8       | 11        | 10.58%  |
| 6       | 11        | 10.58%  |
| 12      | 2         | 1.92%   |
| 1       | 2         | 1.92%   |
| Unknown | 1         | 0.96%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 104       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 78        | 75%     |
| 1       | 25        | 24.04%  |
| Unknown | 1         | 0.96%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 103       | 99.04%  |
| 32-bit         | 1         | 0.96%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 20        | 18.87%  |
| 0x306c3    | 12        | 11.32%  |
| 0x40651    | 5         | 4.72%   |
| 0x906e9    | 4         | 3.77%   |
| 0x806ea    | 4         | 3.77%   |
| 0x206a7    | 4         | 3.77%   |
| 0x1067a    | 4         | 3.77%   |
| 0x806eb    | 3         | 2.83%   |
| 0x506e3    | 3         | 2.83%   |
| 0x406e3    | 3         | 2.83%   |
| 0x306d4    | 3         | 2.83%   |
| 0x20655    | 3         | 2.83%   |
| 0xa0655    | 2         | 1.89%   |
| 0x906ed    | 2         | 1.89%   |
| 0x806ec    | 2         | 1.89%   |
| 0x706a1    | 2         | 1.89%   |
| 0x306a9    | 2         | 1.89%   |
| 0x10677    | 2         | 1.89%   |
| 0x0a50000c | 2         | 1.89%   |
| 0x08701021 | 2         | 1.89%   |
| 0x08701013 | 2         | 1.89%   |
| 0x08600106 | 2         | 1.89%   |
| 0xa0671    | 1         | 0.94%   |
| 0x906ea    | 1         | 0.94%   |
| 0x806e9    | 1         | 0.94%   |
| 0x806d1    | 1         | 0.94%   |
| 0x806c1    | 1         | 0.94%   |
| 0x6f6      | 1         | 0.94%   |
| 0x406f1    | 1         | 0.94%   |
| 0x20652    | 1         | 0.94%   |
| 0x106c2    | 1         | 0.94%   |
| 0x0a201009 | 1         | 0.94%   |
| 0x08600104 | 1         | 0.94%   |
| 0x08600103 | 1         | 0.94%   |
| 0x08108102 | 1         | 0.94%   |
| 0x0810100b | 1         | 0.94%   |
| 0x0800820d | 1         | 0.94%   |
| 0x06006705 | 1         | 0.94%   |
| 0x010000db | 1         | 0.94%   |
| 0x010000c8 | 1         | 0.94%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 25        | 24.04%  |
| Haswell       | 19        | 18.27%  |
| Zen 2         | 9         | 8.65%   |
| Skylake       | 8         | 7.69%   |
| Penryn        | 6         | 5.77%   |
| Westmere      | 4         | 3.85%   |
| SandyBridge   | 4         | 3.85%   |
| Broadwell     | 4         | 3.85%   |
| Zen 3         | 3         | 2.88%   |
| IvyBridge     | 3         | 2.88%   |
| CometLake     | 3         | 2.88%   |
| Zen+          | 2         | 1.92%   |
| TigerLake     | 2         | 1.92%   |
| K10           | 2         | 1.92%   |
| Icelake       | 2         | 1.92%   |
| Goldmont plus | 2         | 1.92%   |
| Zen           | 1         | 0.96%   |
| Piledriver    | 1         | 0.96%   |
| Goldmont      | 1         | 0.96%   |
| Excavator     | 1         | 0.96%   |
| Core          | 1         | 0.96%   |
| Bonnell       | 1         | 0.96%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 69        | 54.76%  |
| Nvidia | 38        | 30.16%  |
| AMD    | 19        | 15.08%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 8         | 6.25%   |
| Intel UHD Graphics 620                                                      | 6         | 4.69%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 5         | 3.91%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 5         | 3.91%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 5         | 3.91%   |
| AMD Renoir                                                                  | 5         | 3.91%   |
| Intel HD Graphics 530                                                       | 4         | 3.13%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 3         | 2.34%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 3         | 2.34%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3         | 2.34%   |
| Nvidia GP108M [GeForce MX250]                                               | 2         | 1.56%   |
| Nvidia GP108M [GeForce MX150]                                               | 2         | 1.56%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2         | 1.56%   |
| Nvidia GK107GLM [Quadro K1100M]                                             | 2         | 1.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 1.56%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 2         | 1.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 2         | 1.56%   |
| Intel Iris Plus Graphics 640                                                | 2         | 1.56%   |
| Intel HD Graphics 5500                                                      | 2         | 1.56%   |
| Intel HD Graphics 515                                                       | 2         | 1.56%   |
| AMD Cezanne                                                                 | 2         | 1.56%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 0.78%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                               | 1         | 0.78%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                       | 1         | 0.78%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1         | 0.78%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1         | 0.78%   |
| Nvidia GT218 [NVS 300]                                                      | 1         | 0.78%   |
| Nvidia GT218 [GeForce G210]                                                 | 1         | 0.78%   |
| Nvidia GT216M [GeForce GT 330M]                                             | 1         | 0.78%   |
| Nvidia GT215M [GeForce GTS 250M]                                            | 1         | 0.78%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1         | 0.78%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 0.78%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1         | 0.78%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1         | 0.78%   |
| Nvidia GM108M [GeForce 840M]                                                | 1         | 0.78%   |
| Nvidia GM107M [GeForce GTX 950M]                                            | 1         | 0.78%   |
| Nvidia GM107M [GeForce GTX 850M]                                            | 1         | 0.78%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1         | 0.78%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1         | 0.78%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1         | 0.78%   |
| Nvidia GK104M [GeForce GTX 680M]                                            | 1         | 0.78%   |
| Nvidia GF119 [GeForce GT 705]                                               | 1         | 0.78%   |
| Nvidia GF108M [GeForce GT 415M]                                             | 1         | 0.78%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 1         | 0.78%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 1         | 0.78%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                          | 1         | 0.78%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 1         | 0.78%   |
| Nvidia G98M [GeForce G 105M]                                                | 1         | 0.78%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                         | 1         | 0.78%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 1         | 0.78%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 1         | 0.78%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 1         | 0.78%   |
| Intel HD Graphics 630                                                       | 1         | 0.78%   |
| Intel HD Graphics 500                                                       | 1         | 0.78%   |
| Intel HD Graphics                                                           | 1         | 0.78%   |
| Intel GeminiLake [UHD Graphics 605]                                         | 1         | 0.78%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1         | 0.78%   |
| Intel Core Processor Integrated Graphics Controller                         | 1         | 0.78%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 1         | 0.78%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1         | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 46        | 44.23%  |
| 1 x Nvidia     | 20        | 19.23%  |
| Intel + Nvidia | 19        | 18.27%  |
| 1 x AMD        | 14        | 13.46%  |
| Intel + AMD    | 3         | 2.88%   |
| 2 x AMD        | 2         | 1.92%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 79        | 75.24%  |
| Proprietary | 21        | 20%     |
| Unknown     | 5         | 4.76%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 66        | 63.46%  |
| 3.01-4.0   | 10        | 9.62%   |
| 1.01-2.0   | 9         | 8.65%   |
| 0.01-0.5   | 9         | 8.65%   |
| 0.51-1.0   | 7         | 6.73%   |
| 8.01-16.0  | 2         | 1.92%   |
| 5.01-6.0   | 1         | 0.96%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 19        | 16.1%   |
| Chimei Innolux          | 15        | 12.71%  |
| LG Display              | 13        | 11.02%  |
| AU Optronics            | 8         | 6.78%   |
| Hewlett-Packard         | 6         | 5.08%   |
| AOC                     | 6         | 5.08%   |
| Sharp                   | 5         | 4.24%   |
| Iiyama                  | 5         | 4.24%   |
| Goldstar                | 5         | 4.24%   |
| Dell                    | 5         | 4.24%   |
| Apple                   | 5         | 4.24%   |
| BOE                     | 4         | 3.39%   |
| Philips                 | 3         | 2.54%   |
| Medion                  | 3         | 2.54%   |
| Chi Mei Optoelectronics | 3         | 2.54%   |
| BenQ                    | 2         | 1.69%   |
| Videoseven              | 1         | 0.85%   |
| Sony                    | 1         | 0.85%   |
| PANDA                   | 1         | 0.85%   |
| Panasonic               | 1         | 0.85%   |
| MSI                     | 1         | 0.85%   |
| Lenovo                  | 1         | 0.85%   |
| Fujitsu Siemens         | 1         | 0.85%   |
| Eizo                    | 1         | 0.85%   |
| Belinea                 | 1         | 0.85%   |
| Aosiman                 | 1         | 0.85%   |
| Ancor Communications    | 1         | 0.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 2         | 1.68%   |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch               | 2         | 1.68%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 2         | 1.68%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 2         | 1.68%   |
| AOC 2250W AOC2250 1920x1080 477x268mm 21.5-inch                       | 2         | 1.68%   |
| Videoseven L27ADS IGM2700 1920x1080 598x336mm 27.0-inch               | 1         | 0.84%   |
| Sony LCD Monitor SNY05FA 1366x768 340x190mm 15.3-inch                 | 1         | 0.84%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch               | 1         | 0.84%   |
| Samsung Electronics T24B350 SAM093E 1920x1080 531x299mm 24.0-inch     | 1         | 0.84%   |
| Samsung Electronics SyncMaster SAM0612 1920x1080 604x342mm 27.3-inch  | 1         | 0.84%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch   | 1         | 0.84%   |
| Samsung Electronics SMT27A950 SAM080F 1920x1080 598x336mm 27.0-inch   | 1         | 0.84%   |
| Samsung Electronics SM2333T SAM0737 1920x1080 510x290mm 23.1-inch     | 1         | 0.84%   |
| Samsung Electronics S27D390 SAM0B67 1920x1080 598x336mm 27.0-inch     | 1         | 0.84%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.84%   |
| Samsung Electronics LCD Monitor U28E590 3840x2160                     | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SEC444E 1600x900 310x174mm 14.0-inch  | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SDC5844 1920x1080 344x194mm 15.5-inch | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SDC4141 3840x2160 344x194mm 15.5-inch | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 890x500mm 40.2-inch | 1         | 0.84%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch   | 1         | 0.84%   |
| Samsung Electronics C27R50x SAM0F9D 1920x1080 598x336mm 27.0-inch     | 1         | 0.84%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 1         | 0.84%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch     | 1         | 0.84%   |
| Philips PHL BDM3270 PHL08E7 2560x1440 708x398mm 32.0-inch             | 1         | 0.84%   |
| Philips PHL 275C5 PHLC0E4 1920x1080 598x336mm 27.0-inch               | 1         | 0.84%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch               | 1         | 0.84%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 0.84%   |
| Panasonic LCD Monitor MEI96A2 3840x2160 382x215mm 17.3-inch           | 1         | 0.84%   |
| MSI MPG27CQ MSI3FA3 2560x1440 600x340mm 27.2-inch                     | 1         | 0.84%   |
| Medion Medion23.6 PC MEDB603 1920x1080 477x268mm 21.5-inch            | 1         | 0.84%   |
| Medion MD 20122 MED3601 1680x1050 474x296mm 22.0-inch                 | 1         | 0.84%   |
| Medion 42FPDEUDA1 MED222E 1920x1080                                   | 1         | 0.84%   |
| LG Display LP156WH2-TLE1 LGDCF01 1366x768 344x194mm 15.5-inch         | 1         | 0.84%   |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch          | 1         | 0.84%   |
| LG Display LCD Monitor LGD05EE 2560x1440 309x174mm 14.0-inch          | 1         | 0.84%   |
| LG Display LCD Monitor LGD05CE 1920x1080 344x194mm 15.5-inch          | 1         | 0.84%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 0.84%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 1         | 0.84%   |
| LG Display LCD Monitor LGD046B 1366x768 344x194mm 15.5-inch           | 1         | 0.84%   |
| LG Display LCD Monitor LGD040A 1920x1080 309x175mm 14.0-inch          | 1         | 0.84%   |
| LG Display LCD Monitor LGD03B8 1366x768 310x174mm 14.0-inch           | 1         | 0.84%   |
| LG Display LCD Monitor LGD03B3 1366x768 310x174mm 14.0-inch           | 1         | 0.84%   |
| LG Display LCD Monitor LGD038C 1366x768 256x144mm 11.6-inch           | 1         | 0.84%   |
| LG Display LCD Monitor LGD02EF 1366x768 310x174mm 14.0-inch           | 1         | 0.84%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch           | 1         | 0.84%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 1         | 0.84%   |
| Iiyama X2485 IVM610F 1920x1080 520x320mm 24.0-inch                    | 1         | 0.84%   |
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                 | 1         | 0.84%   |
| Iiyama PL2773H IVM660A 1920x1080 598x336mm 27.0-inch                  | 1         | 0.84%   |
| Iiyama PL2492HN IVM6156 1920x1080 527x296mm 23.8-inch                 | 1         | 0.84%   |
| Iiyama PL2209HD IVM560B 1920x1080 478x269mm 21.6-inch                 | 1         | 0.84%   |
| Hewlett-Packard v220 HWP26FE 1680x1050 473x296mm 22.0-inch            | 1         | 0.84%   |
| Hewlett-Packard S2331 HWP2907 1920x1080 509x286mm 23.0-inch           | 1         | 0.84%   |
| Hewlett-Packard P244 HPN3620 1920x1080 527x297mm 23.8-inch            | 1         | 0.84%   |
| Hewlett-Packard L1950 HWP26E8 1280x1024 380x300mm 19.1-inch           | 1         | 0.84%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 56        | 51.38%  |
| 1366x768 (WXGA)    | 14        | 12.84%  |
| 3840x2160 (4K)     | 10        | 9.17%   |
| 2560x1440 (QHD)    | 7         | 6.42%   |
| 1600x900 (HD+)     | 4         | 3.67%   |
| 1680x1050 (WSXGA+) | 3         | 2.75%   |
| 3200x1800 (QHD+)   | 2         | 1.83%   |
| 1920x1200 (WUXGA)  | 2         | 1.83%   |
| 1440x900 (WXGA+)   | 2         | 1.83%   |
| 1360x768           | 2         | 1.83%   |
| 1280x1024 (SXGA)   | 2         | 1.83%   |
| 3072x1920          | 1         | 0.92%   |
| 2880x1800          | 1         | 0.92%   |
| 2560x1600          | 1         | 0.92%   |
| 1280x800 (WXGA)    | 1         | 0.92%   |
| 1024x768 (XGA)     | 1         | 0.92%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 30        | 25.42%  |
| 27      | 15        | 12.71%  |
| 17      | 11        | 9.32%   |
| 14      | 11        | 9.32%   |
| 13      | 10        | 8.47%   |
| 23      | 8         | 6.78%   |
| 21      | 7         | 5.93%   |
| 24      | 6         | 5.08%   |
| Unknown | 4         | 3.39%   |
| 22      | 3         | 2.54%   |
| 18      | 2         | 1.69%   |
| 16      | 2         | 1.69%   |
| 72      | 1         | 0.85%   |
| 59      | 1         | 0.85%   |
| 46      | 1         | 0.85%   |
| 33      | 1         | 0.85%   |
| 32      | 1         | 0.85%   |
| 31      | 1         | 0.85%   |
| 25      | 1         | 0.85%   |
| 19      | 1         | 0.85%   |
| 11      | 1         | 0.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 46        | 39.66%  |
| 501-600     | 28        | 24.14%  |
| 401-500     | 12        | 10.34%  |
| 351-400     | 12        | 10.34%  |
| 201-300     | 7         | 6.03%   |
| Unknown     | 4         | 3.45%   |
| 701-800     | 2         | 1.72%   |
| 601-700     | 2         | 1.72%   |
| 1001-1500   | 2         | 1.72%   |
| 1501-2000   | 1         | 0.86%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 85        | 83.33%  |
| 16/10   | 12        | 11.76%  |
| 5/4     | 2         | 1.96%   |
| Unknown | 2         | 1.96%   |
| 4/3     | 1         | 0.98%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 30        | 25.42%  |
| 201-250        | 20        | 16.95%  |
| 81-90          | 16        | 13.56%  |
| 301-350        | 15        | 12.71%  |
| 121-130        | 8         | 6.78%   |
| 71-80          | 5         | 4.24%   |
| Unknown        | 4         | 3.39%   |
| 351-500        | 3         | 2.54%   |
| 251-300        | 3         | 2.54%   |
| 151-200        | 3         | 2.54%   |
| 141-150        | 3         | 2.54%   |
| More than 1000 | 2         | 1.69%   |
| 131-140        | 2         | 1.69%   |
| 51-60          | 1         | 0.85%   |
| 111-120        | 1         | 0.85%   |
| 501-1000       | 1         | 0.85%   |
| 91-100         | 1         | 0.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 34        | 29.57%  |
| 121-160       | 33        | 28.7%   |
| 101-120       | 27        | 23.48%  |
| 161-240       | 10        | 8.7%    |
| More than 240 | 5         | 4.35%   |
| Unknown       | 4         | 3.48%   |
| 1-50          | 2         | 1.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 82        | 77.36%  |
| 2     | 18        | 16.98%  |
| 0     | 4         | 3.77%   |
| 3     | 2         | 1.89%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 70        | 44.59%  |
| Realtek Semiconductor           | 43        | 27.39%  |
| Qualcomm Atheros                | 16        | 10.19%  |
| Broadcom                        | 13        | 8.28%   |
| Marvell Technology Group        | 4         | 2.55%   |
| Sierra Wireless                 | 2         | 1.27%   |
| DisplayLink                     | 2         | 1.27%   |
| TP-Link                         | 1         | 0.64%   |
| Ralink Technology               | 1         | 0.64%   |
| Qualcomm Atheros Communications | 1         | 0.64%   |
| MediaTek                        | 1         | 0.64%   |
| Lenovo                          | 1         | 0.64%   |
| Broadcom Limited                | 1         | 0.64%   |
| ASIX Electronics                | 1         | 0.64%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 31        | 16.76%  |
| Intel Wi-Fi 6 AX200                                                            | 11        | 5.95%   |
| Realtek RTL8125 2.5GbE Controller                                              | 5         | 2.7%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 5         | 2.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 2.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 4         | 2.16%   |
| Intel Wireless 8265 / 8275                                                     | 4         | 2.16%   |
| Intel Wireless 7260                                                            | 4         | 2.16%   |
| Intel I211 Gigabit Network Connection                                          | 4         | 2.16%   |
| Intel Wireless 8260                                                            | 3         | 1.62%   |
| Intel Wireless 3160                                                            | 3         | 1.62%   |
| Intel Ethernet Connection (2) I219-V                                           | 3         | 1.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 1.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 1.08%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 2         | 1.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2         | 1.08%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 2         | 1.08%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.08%   |
| Intel Wireless-AC 9260                                                         | 2         | 1.08%   |
| Intel Wireless 7265                                                            | 2         | 1.08%   |
| Intel Wireless 3165                                                            | 2         | 1.08%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 2         | 1.08%   |
| Intel Ethernet Connection I217-V                                               | 2         | 1.08%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 1.08%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 1.08%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 1.08%   |
| Intel Ethernet Connection (2) I218-V                                           | 2         | 1.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 2         | 1.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 2         | 1.08%   |
| DisplayLink Dell D3100 Docking Station                                         | 2         | 1.08%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                             | 2         | 1.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 2         | 1.08%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                    | 1         | 0.54%   |
| Sierra Wireless EM7455                                                         | 1         | 0.54%   |
| Sierra Wireless EM7305 Modem                                                   | 1         | 0.54%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                    | 1         | 0.54%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 0.54%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.54%   |
| Ralink RT5370 Wireless Adapter                                                 | 1         | 0.54%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 1         | 0.54%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.54%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 1         | 0.54%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.54%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.54%   |
| Qualcomm Atheros AR9271 802.11n                                                | 1         | 0.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 1         | 0.54%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                               | 1         | 0.54%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                               | 1         | 0.54%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                 | 1         | 0.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 1         | 0.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.54%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                            | 1         | 0.54%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                              | 1         | 0.54%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 0.54%   |
| Lenovo ThinkPad Lan                                                            | 1         | 0.54%   |
| Intel WiMAX/WiFi Link 5150                                                     | 1         | 0.54%   |
| Intel WiMAX Connection 2400m                                                   | 1         | 0.54%   |
| Intel Wi-Fi 6 AX201                                                            | 1         | 0.54%   |
| Intel Tiger Lake PCH CNVi WiFi                                                 | 1         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 52        | 58.43%  |
| Qualcomm Atheros                | 13        | 14.61%  |
| Broadcom                        | 10        | 11.24%  |
| Realtek Semiconductor           | 6         | 6.74%   |
| Sierra Wireless                 | 2         | 2.25%   |
| TP-Link                         | 1         | 1.12%   |
| Ralink Technology               | 1         | 1.12%   |
| Qualcomm Atheros Communications | 1         | 1.12%   |
| MediaTek                        | 1         | 1.12%   |
| Marvell Technology Group        | 1         | 1.12%   |
| Broadcom Limited                | 1         | 1.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 11        | 12.36%  |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 5         | 5.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 4         | 4.49%   |
| Intel Wireless 8265 / 8275                                     | 4         | 4.49%   |
| Intel Wireless 7260                                            | 4         | 4.49%   |
| Intel Wireless 8260                                            | 3         | 3.37%   |
| Intel Wireless 3160                                            | 3         | 3.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 2.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 2.25%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 2.25%   |
| Intel Wireless-AC 9260                                         | 2         | 2.25%   |
| Intel Wireless 7265                                            | 2         | 2.25%   |
| Intel Wireless 3165                                            | 2         | 2.25%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 2.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 2.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 2.25%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 2         | 2.25%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 2.25%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 1.12%   |
| Sierra Wireless EM7455                                         | 1         | 1.12%   |
| Sierra Wireless EM7305 Modem                                   | 1         | 1.12%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 1.12%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 1.12%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 1.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 1.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 1.12%   |
| Qualcomm Atheros AR9271 802.11n                                | 1         | 1.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 1.12%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 1.12%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1         | 1.12%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 1.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.12%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter            | 1         | 1.12%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 1         | 1.12%   |
| Intel WiMAX/WiFi Link 5150                                     | 1         | 1.12%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 1.12%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 1.12%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 1         | 1.12%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 1.12%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 1.12%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 1.12%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 1.12%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 1         | 1.12%   |
| Intel Centrino Advanced-N 6200                                 | 1         | 1.12%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 1         | 1.12%   |
| Broadcom BCM4377b Wireless Network Adapter                     | 1         | 1.12%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 1         | 1.12%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 1         | 1.12%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter             | 1         | 1.12%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1         | 1.12%   |
| Broadcom BCM43142 802.11b/g/n                                  | 1         | 1.12%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 41        | 44.09%  |
| Intel                    | 35        | 37.63%  |
| Qualcomm Atheros         | 5         | 5.38%   |
| Broadcom                 | 5         | 5.38%   |
| Marvell Technology Group | 3         | 3.23%   |
| DisplayLink              | 2         | 2.15%   |
| Lenovo                   | 1         | 1.08%   |
| ASIX Electronics         | 1         | 1.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 31        | 32.63%  |
| Realtek RTL8125 2.5GbE Controller                                              | 5         | 5.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 4.21%   |
| Intel I211 Gigabit Network Connection                                          | 4         | 4.21%   |
| Intel Ethernet Connection (2) I219-V                                           | 3         | 3.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 3.16%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2         | 2.11%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 2.11%   |
| Intel Ethernet Connection I217-V                                               | 2         | 2.11%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 2.11%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 2.11%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 2.11%   |
| Intel Ethernet Connection (2) I218-V                                           | 2         | 2.11%   |
| DisplayLink Dell D3100 Docking Station                                         | 2         | 2.11%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 1.05%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 1.05%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 1.05%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 1.05%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 1.05%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 1.05%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 1.05%   |
| Lenovo ThinkPad Lan                                                            | 1         | 1.05%   |
| Intel WiMAX Connection 2400m                                                   | 1         | 1.05%   |
| Intel Ethernet Controller I225-V                                               | 1         | 1.05%   |
| Intel Ethernet controller                                                      | 1         | 1.05%   |
| Intel Ethernet Connection I219-V                                               | 1         | 1.05%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 1.05%   |
| Intel Ethernet Connection (7) I219-V                                           | 1         | 1.05%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 1.05%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 1.05%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 1.05%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 1.05%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 1.05%   |
| Intel Ethernet Connection (11) I219-V                                          | 1         | 1.05%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 1.05%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 1         | 1.05%   |
| Intel 82566DC Gigabit Network Connection                                       | 1         | 1.05%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 1         | 1.05%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 1         | 1.05%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 1.05%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 1         | 1.05%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 1         | 1.05%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 1.05%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 87        | 50.29%  |
| WiFi     | 85        | 49.13%  |
| Unknown  | 1         | 0.58%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 62        | 56.88%  |
| Ethernet | 47        | 43.12%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 59        | 56.73%  |
| 1     | 40        | 38.46%  |
| 3     | 5         | 4.81%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 88        | 83.81%  |
| Yes  | 17        | 16.19%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 45        | 62.5%   |
| Foxconn / Hon Hai               | 5         | 6.94%   |
| Qualcomm Atheros Communications | 3         | 4.17%   |
| Cambridge Silicon Radio         | 3         | 4.17%   |
| Apple                           | 3         | 4.17%   |
| Realtek                         | 2         | 2.78%   |
| IMC Networks                    | 2         | 2.78%   |
| Hewlett-Packard                 | 2         | 2.78%   |
| Toshiba                         | 1         | 1.39%   |
| Realtek Semiconductor           | 1         | 1.39%   |
| Micro Star International        | 1         | 1.39%   |
| Marvell Semiconductor           | 1         | 1.39%   |
| Lite-On Technology              | 1         | 1.39%   |
| Broadcom                        | 1         | 1.39%   |
| ASUSTek Computer                | 1         | 1.39%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 17        | 23.61%  |
| Intel AX200 Bluetooth                                                               | 10        | 13.89%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 7         | 9.72%   |
| Intel AX201 Bluetooth                                                               | 4         | 5.56%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 3         | 4.17%   |
| Realtek Bluetooth Radio                                                             | 2         | 2.78%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 2.78%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 2.78%   |
| Intel AX210 Bluetooth                                                               | 2         | 2.78%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 2.78%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 2.78%   |
| Toshiba Bluetooth Device                                                            | 1         | 1.39%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.39%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 1         | 1.39%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 1.39%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.39%   |
| Micro Star International Motorola Bluetooth 2.1+EDR Device                          | 1         | 1.39%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 1         | 1.39%   |
| Lite-On Bluetooth Device                                                            | 1         | 1.39%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 1.39%   |
| IMC Networks Bluetooth Module                                                       | 1         | 1.39%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.39%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.39%   |
| Foxconn / Hon Hai BT                                                                | 1         | 1.39%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 1.39%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 1         | 1.39%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 1.39%   |
| Broadcom Bluetooth 3.0 Device                                                       | 1         | 1.39%   |
| ASUS BCM20702A0                                                                     | 1         | 1.39%   |
| Apple Bluetooth Host Controller                                                     | 1         | 1.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 85        | 62.04%  |
| AMD                            | 22        | 16.06%  |
| Nvidia                         | 20        | 14.6%   |
| Logitech                       | 2         | 1.46%   |
| www.hirestech.com 2010 REV 1.4 | 1         | 0.73%   |
| SteelSeries ApS                | 1         | 0.73%   |
| Sony                           | 1         | 0.73%   |
| Realtek Semiconductor          | 1         | 0.73%   |
| Lenovo                         | 1         | 0.73%   |
| C-Media Electronics            | 1         | 0.73%   |
| Bose                           | 1         | 0.73%   |
| Apple                          | 1         | 0.73%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 12        | 7.1%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 12        | 7.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 11        | 6.51%   |
| AMD Family 17h/19h HD Audio Controller                                     | 9         | 5.33%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7         | 4.14%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 3.55%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 2.96%   |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 2.96%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 2.96%   |
| Intel 200 Series PCH HD Audio                                              | 5         | 2.96%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5         | 2.96%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 2.37%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 2.37%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 2.37%   |
| Nvidia High Definition Audio Controller                                    | 3         | 1.78%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 1.78%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 1.78%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 1.78%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 1.78%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.78%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.18%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 1.18%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.18%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2         | 1.18%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 1.18%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.18%   |
| www.hirestech.com 2010 REV 1.4 Music Streamer Pro                          | 1         | 0.59%   |
| SteelSeries ApS SteelSeries Arctis 7                                       | 1         | 0.59%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 1         | 0.59%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.59%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.59%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.59%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.59%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.59%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.59%   |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 0.59%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.59%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.59%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 0.59%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 0.59%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.59%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.59%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 0.59%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 0.59%   |
| Nvidia GA102 High Definition Audio Controller                              | 1         | 0.59%   |
| Logitech QuickCam Fusion                                                   | 1         | 0.59%   |
| Logitech Headset H390                                                      | 1         | 0.59%   |
| Lenovo ThinkPad Dock USB Audio                                             | 1         | 0.59%   |
| Intel USB PnP Sound Device                                                 | 1         | 0.59%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 1         | 0.59%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 0.59%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 0.59%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 0.59%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.59%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.59%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1         | 0.59%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1         | 0.59%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 0.59%   |
| C-Media Electronics Blue Snowball                                          | 1         | 0.59%   |
| Bose Revolve SoundLink                                                     | 1         | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 24        | 38.71%  |
| SK hynix            | 10        | 16.13%  |
| Micron Technology   | 5         | 8.06%   |
| Unknown             | 4         | 6.45%   |
| Kingston            | 4         | 6.45%   |
| Crucial             | 4         | 6.45%   |
| Corsair             | 4         | 6.45%   |
| G.Skill             | 3         | 4.84%   |
| A-DATA Technology   | 3         | 4.84%   |
| Qimonda             | 1         | 1.61%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 3         | 4.55%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s       | 2         | 3.03%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s          | 2         | 3.03%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 2         | 3.03%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s         | 2         | 3.03%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s        | 2         | 3.03%   |
| Unknown RAM Module 4GB SODIMM DDR3                             | 1         | 1.52%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                   | 1         | 1.52%   |
| Unknown RAM Module 2GB SODIMM DDR2                             | 1         | 1.52%   |
| Unknown RAM Module 2048MB SODIMM DDR2                          | 1         | 1.52%   |
| Unknown RAM Module 1024MB SODIMM DDR2                          | 1         | 1.52%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s        | 1         | 1.52%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 1.52%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s         | 1         | 1.52%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s         | 1         | 1.52%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16384MB SODIMM DDR4 3200MT/s     | 1         | 1.52%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16384MB SODIMM DDR4 2667MT/s     | 1         | 1.52%   |
| SK hynix RAM HMA81GS6MFR8N-UH 8192MB SODIMM DDR4 2400MT/s      | 1         | 1.52%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s         | 1         | 1.52%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.52%   |
| Samsung RAM Module 4GB SODIMM DDR3 1067MT/s                    | 1         | 1.52%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                | 1         | 1.52%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s          | 1         | 1.52%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s       | 1         | 1.52%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 1         | 1.52%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s          | 1         | 1.52%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s          | 1         | 1.52%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s         | 1         | 1.52%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s         | 1         | 1.52%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s          | 1         | 1.52%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 1         | 1.52%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s          | 1         | 1.52%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 1.52%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s          | 1         | 1.52%   |
| Samsung RAM M471A1G44AB0-CTD 8GB Row Of Chips DDR4 2667MT/s    | 1         | 1.52%   |
| Samsung RAM M378A1K43CB2-CRC 8192MB DIMM DDR4 3500MT/s         | 1         | 1.52%   |
| Samsung RAM 99U5429-007.A00LF 2GB DIMM DDR2 800MT/s            | 1         | 1.52%   |
| Qimonda RAM 64T256020EU2.5C2 2GB DIMM DDR2 800MT/s             | 1         | 1.52%   |
| Micron RAM MT52L512M32D2PF-09 4GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.52%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s  | 1         | 1.52%   |
| Micron RAM Module 8192MB SODIMM DDR4 2667MT/s                  | 1         | 1.52%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s           | 1         | 1.52%   |
| Micron RAM 4ATF51264HZ-2G3B2 4GB SODIMM DDR4 2400MT/s          | 1         | 1.52%   |
| Kingston RAM KHX4000C19D4/8GX 8GB DIMM DDR4 3600MT/s           | 1         | 1.52%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s            | 1         | 1.52%   |
| Kingston RAM 9905625-074.A00G 16384MB DIMM DDR4 2400MT/s       | 1         | 1.52%   |
| Kingston RAM 9905624-033.A00G 8GB SODIMM DDR4 2400MT/s         | 1         | 1.52%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s           | 1         | 1.52%   |
| G.Skill RAM F4-3200C16-16GIS 16GB DIMM DDR4 3600MT/s           | 1         | 1.52%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s            | 1         | 1.52%   |
| Crucial RAM CT8G4SFS824A.C8FDD1 8GB SODIMM DDR4 2400MT/s       | 1         | 1.52%   |
| Crucial RAM CT8G4DFS8266.C8FE 8GB DIMM DDR4 2667MT/s           | 1         | 1.52%   |
| Corsair RAM Module 2GB DIMM DDR2 800MT/s                       | 1         | 1.52%   |
| Corsair RAM CMW64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s         | 1         | 1.52%   |
| Corsair RAM CMW16GX4M2A2666C16 8GB DIMM DDR4 2666MT/s          | 1         | 1.52%   |
| Corsair RAM CMK16GX4M1B3000C15 16GB DIMM DDR4 3400MT/s         | 1         | 1.52%   |
| A-DATA RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.52%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3400MT/s                    | 1         | 1.52%   |
| A-DATA RAM AO1P24HC8T1-BPGS 8GB SODIMM DDR4 2400MT/s           | 1         | 1.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 31        | 53.45%  |
| DDR3   | 19        | 32.76%  |
| DDR2   | 4         | 6.9%    |
| LPDDR3 | 3         | 5.17%   |
| SDRAM  | 1         | 1.72%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 38        | 66.67%  |
| DIMM         | 15        | 26.32%  |
| Row Of Chips | 4         | 7.02%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 28        | 45.16%  |
| 4096  | 13        | 20.97%  |
| 16384 | 11        | 17.74%  |
| 2048  | 7         | 11.29%  |
| 32768 | 2         | 3.23%   |
| 1024  | 1         | 1.61%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 15        | 25%     |
| 1600    | 12        | 20%     |
| 3200    | 8         | 13.33%  |
| 2400    | 6         | 10%     |
| 3600    | 3         | 5%      |
| 2133    | 3         | 5%      |
| Unknown | 3         | 5%      |
| 3400    | 2         | 3.33%   |
| 800     | 2         | 3.33%   |
| 3500    | 1         | 1.67%   |
| 2666    | 1         | 1.67%   |
| 1867    | 1         | 1.67%   |
| 1334    | 1         | 1.67%   |
| 1333    | 1         | 1.67%   |
| 1067    | 1         | 1.67%   |

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
| Chicony Electronics                    | 21        | 33.33%  |
| IMC Networks                           | 8         | 12.7%   |
| Microdia                               | 7         | 11.11%  |
| Logitech                               | 4         | 6.35%   |
| Ricoh                                  | 3         | 4.76%   |
| Realtek Semiconductor                  | 3         | 4.76%   |
| Sunplus Innovation Technology          | 2         | 3.17%   |
| Samsung Electronics                    | 2         | 3.17%   |
| Quanta                                 | 2         | 3.17%   |
| Apple                                  | 2         | 3.17%   |
| Alcor Micro                            | 2         | 3.17%   |
| Acer                                   | 2         | 3.17%   |
| Unknown                                | 1         | 1.59%   |
| Luxvisions Innotech Limited            | 1         | 1.59%   |
| Huawei Technologies                    | 1         | 1.59%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.59%   |
| ALi                                    | 1         | 1.59%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 4         | 6.35%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 6.35%   |
| IMC Networks Integrated Camera                      | 3         | 4.76%   |
| Chicony Integrated Camera                           | 3         | 4.76%   |
| Samsung Galaxy series, misc. (MTP mode)             | 2         | 3.17%   |
| Realtek Integrated_Webcam_HD                        | 2         | 3.17%   |
| Microdia Integrated Webcam                          | 2         | 3.17%   |
| Logitech B525 HD Webcam                             | 2         | 3.17%   |
| Chicony Integrated Camera (1280x720@30)             | 2         | 3.17%   |
| Chicony HP Wide Vision HD Camera                    | 2         | 3.17%   |
| Chicony HD Webcam                                   | 2         | 3.17%   |
| Alcor Micro USB 2.0 Camera                          | 2         | 3.17%   |
| Unknown 720p HD Camera                              | 1         | 1.59%   |
| Sunplus Laptop Integrated WebCam HD                 | 1         | 1.59%   |
| Sunplus HP HD Webcam [Fixed]                        | 1         | 1.59%   |
| Ricoh USB2.0 Camera                                 | 1         | 1.59%   |
| Ricoh Sony Visual Communication Camera              | 1         | 1.59%   |
| Ricoh Sony Vaio Integrated Webcam                   | 1         | 1.59%   |
| Realtek HP Truevision HD                            | 1         | 1.59%   |
| Quanta HP Webcam                                    | 1         | 1.59%   |
| Quanta HD User Facing                               | 1         | 1.59%   |
| Microdia Webcam                                     | 1         | 1.59%   |
| Luxvisions Innotech Limited HP HD Camera            | 1         | 1.59%   |
| Logitech Webcam C270                                | 1         | 1.59%   |
| Logitech HD Pro Webcam C920                         | 1         | 1.59%   |
| IMC Networks HD Camera                              | 1         | 1.59%   |
| Huawei UVC Camera                                   | 1         | 1.59%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 1.59%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 1.59%   |
| Chicony USB 2.0 Camera                              | 1         | 1.59%   |
| Chicony TOSHIBA Web Camera - HD                     | 1         | 1.59%   |
| Chicony ThinkPad T490 Webcam                        | 1         | 1.59%   |
| Chicony Integrated HP HD Webcam                     | 1         | 1.59%   |
| Chicony HP Truevision HD                            | 1         | 1.59%   |
| Chicony HP HD Camera                                | 1         | 1.59%   |
| Chicony HD WebCam (Asus N-series)                   | 1         | 1.59%   |
| Chicony FJ Camera                                   | 1         | 1.59%   |
| Chicony EasyCamera                                  | 1         | 1.59%   |
| Chicony Acer CrystalEye Webcam                      | 1         | 1.59%   |
| Cheng Uei Precision Industry (Foxlink) FJ 5M Camera | 1         | 1.59%   |
| Apple FaceTime HD Camera (Built-in)                 | 1         | 1.59%   |
| Apple FaceTime HD Camera                            | 1         | 1.59%   |
| ALi Gateway Webcam                                  | 1         | 1.59%   |
| Acer Front Camera                                   | 1         | 1.59%   |
| Acer BisonCam, NB Pro                               | 1         | 1.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 8         | 44.44%  |
| Validity Sensors           | 3         | 16.67%  |
| Shenzhen Goodix Technology | 3         | 16.67%  |
| Upek                       | 1         | 5.56%   |
| LighTuning Technology      | 1         | 5.56%   |
| Elan Microelectronics      | 1         | 5.56%   |
| AuthenTec                  | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 4         | 22.22%  |
| Shenzhen Goodix Fingerprint Reader                         | 3         | 16.67%  |
| Unknown                                                    | 2         | 11.11%  |
| Validity Sensors VFS7552 Touch Fingerprint Sensor          | 1         | 5.56%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 1         | 5.56%   |
| Validity Sensors Synaptics WBDI                            | 1         | 5.56%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 1         | 5.56%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 5.56%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 1         | 5.56%   |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 1         | 5.56%   |
| Elan ELAN:Fingerprint                                      | 1         | 5.56%   |
| AuthenTec Fingerprint Sensor                               | 1         | 5.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 5         | 55.56%  |
| Gemalto (was Gemplus) | 3         | 33.33%  |
| Broadcom              | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 63        | 59.43%  |
| 1     | 28        | 26.42%  |
| 2     | 13        | 12.26%  |
| 3     | 2         | 1.89%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 18        | 31.03%  |
| Graphics card            | 12        | 20.69%  |
| Multimedia controller    | 6         | 10.34%  |
| Chipcard                 | 5         | 8.62%   |
| Network                  | 3         | 5.17%   |
| Net/wireless             | 3         | 5.17%   |
| Communication controller | 3         | 5.17%   |
| Card reader              | 3         | 5.17%   |
| Unassigned class         | 1         | 1.72%   |
| Sound                    | 1         | 1.72%   |
| Net/ethernet             | 1         | 1.72%   |
| Camera                   | 1         | 1.72%   |
| Bluetooth                | 1         | 1.72%   |

