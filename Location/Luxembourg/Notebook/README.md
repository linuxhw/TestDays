Linux in Luxembourg - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Luxembourg.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 119

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Panasonic     | CF-195DCUBML                | [e9e34a8b3b](https://linux-hardware.org/?probe=e9e34a8b3b) | Oct 29, 2023 |
| SLIMBOOK      | EXECUTIVE-14                | [39250155c4](https://linux-hardware.org/?probe=39250155c4) | Oct 26, 2023 |
| Acer          | Swift SFG14-71              | [612557336e](https://linux-hardware.org/?probe=612557336e) | Oct 14, 2023 |
| Samsung       | 550XBE/350XBE               | [3185dde146](https://linux-hardware.org/?probe=3185dde146) | Oct 04, 2023 |
| MSI           | GE63 7RD                    | [b0aac4eb91](https://linux-hardware.org/?probe=b0aac4eb91) | Sep 13, 2023 |
| Dell          | Precision 7670              | [09797bd60c](https://linux-hardware.org/?probe=09797bd60c) | Aug 04, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [2b50e2b375](https://linux-hardware.org/?probe=2b50e2b375) | Jul 29, 2023 |
| HUAWEI        | KLVL-WXXW                   | [f0dcdf797e](https://linux-hardware.org/?probe=f0dcdf797e) | Jul 23, 2023 |
| HUAWEI        | KLVL-WXXW                   | [49fc9fb8ce](https://linux-hardware.org/?probe=49fc9fb8ce) | Jul 23, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [a210e832a8](https://linux-hardware.org/?probe=a210e832a8) | Jun 16, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [eb6365c303](https://linux-hardware.org/?probe=eb6365c303) | Jun 16, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X6... | [e3e61eef7a](https://linux-hardware.org/?probe=e3e61eef7a) | Jun 15, 2023 |
| Dell          | Precision M3800             | [f5f8f44c9e](https://linux-hardware.org/?probe=f5f8f44c9e) | May 10, 2023 |
| Notebook      | NV4XMB,ME,MZ                | [f3b5a181df](https://linux-hardware.org/?probe=f3b5a181df) | May 02, 2023 |
| HUAWEI        | CREM-WXX9                   | [d3ef8c638e](https://linux-hardware.org/?probe=d3ef8c638e) | Apr 30, 2023 |
| SLIMBOOK      | EXECUTIVE-14                | [e66056ac2d](https://linux-hardware.org/?probe=e66056ac2d) | Apr 09, 2023 |
| Dell          | Precision 5570              | [a3d5f928ee](https://linux-hardware.org/?probe=a3d5f928ee) | Mar 31, 2023 |
| Acer          | Aspire A514-54              | [94da64753b](https://linux-hardware.org/?probe=94da64753b) | Mar 30, 2023 |
| ASUSTek       | N751JK                      | [813b5026ad](https://linux-hardware.org/?probe=813b5026ad) | Mar 18, 2023 |
| HUAWEI        | HVY-WXX9                    | [b5ef4ae548](https://linux-hardware.org/?probe=b5ef4ae548) | Mar 14, 2023 |
| HUAWEI        | HVY-WXX9                    | [e79cdeaf10](https://linux-hardware.org/?probe=e79cdeaf10) | Mar 13, 2023 |
| Packard Be... | EasyNote TJ65               | [18f0877a2e](https://linux-hardware.org/?probe=18f0877a2e) | Mar 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [ac5cf996d9](https://linux-hardware.org/?probe=ac5cf996d9) | Mar 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [bc56140257](https://linux-hardware.org/?probe=bc56140257) | Jan 25, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [71c2b809fb](https://linux-hardware.org/?probe=71c2b809fb) | Jan 09, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [5b645cbd36](https://linux-hardware.org/?probe=5b645cbd36) | Dec 22, 2022 |
| Dell          | Precision 7670              | [93f14c8b55](https://linux-hardware.org/?probe=93f14c8b55) | Nov 21, 2022 |
| Dell          | Latitude 5520               | [91cab639f0](https://linux-hardware.org/?probe=91cab639f0) | Nov 17, 2022 |
| Clevo         | W25xHPx                     | [04196b2306](https://linux-hardware.org/?probe=04196b2306) | Oct 13, 2022 |
| HP            | EliteBook 850 G3            | [2eee433657](https://linux-hardware.org/?probe=2eee433657) | Sep 17, 2022 |
| ASUSTek       | N751JK                      | [ca6cba3420](https://linux-hardware.org/?probe=ca6cba3420) | Jul 28, 2022 |
| Wortmann      | MS-1727                     | [4697b4b4e5](https://linux-hardware.org/?probe=4697b4b4e5) | Jul 27, 2022 |
| HP            | EliteBook 8560p             | [584fe927af](https://linux-hardware.org/?probe=584fe927af) | Jul 19, 2022 |
| Apple         | MacBookAir6,2               | [cc9185a171](https://linux-hardware.org/?probe=cc9185a171) | Jul 17, 2022 |
| ASUSTek       | TUF Gaming FX505DY_TUF50... | [df304b4da1](https://linux-hardware.org/?probe=df304b4da1) | Jun 17, 2022 |
| win elemen... | MoreFine S500+              | [eafff91c80](https://linux-hardware.org/?probe=eafff91c80) | Jun 03, 2022 |
| TUXEDO        | Pulse 14 Gen1               | [ca9c5a57a8](https://linux-hardware.org/?probe=ca9c5a57a8) | May 06, 2022 |
| Acer          | Nitro AN515-55              | [731e3d2588](https://linux-hardware.org/?probe=731e3d2588) | Apr 03, 2022 |
| Acer          | Nitro AN515-55              | [ad42ffd24d](https://linux-hardware.org/?probe=ad42ffd24d) | Apr 03, 2022 |
| Sony          | VPCCA4E1E                   | [95fc0956c8](https://linux-hardware.org/?probe=95fc0956c8) | Mar 27, 2022 |
| ASUSTek       | UX430UNR                    | [86dc3583ca](https://linux-hardware.org/?probe=86dc3583ca) | Mar 09, 2022 |
| ASUSTek       | UX430UNR                    | [4c45b3ea17](https://linux-hardware.org/?probe=4c45b3ea17) | Mar 06, 2022 |
| ASUSTek       | UX430UNR                    | [a76e22e410](https://linux-hardware.org/?probe=a76e22e410) | Mar 06, 2022 |
| HP            | 255 G6 Notebook PC          | [30c3320bb3](https://linux-hardware.org/?probe=30c3320bb3) | Feb 12, 2022 |
| HP            | 255 G6 Notebook PC          | [d4f9b2d0e3](https://linux-hardware.org/?probe=d4f9b2d0e3) | Feb 12, 2022 |
| Sony          | VPCEB2E1E                   | [e3df114520](https://linux-hardware.org/?probe=e3df114520) | Feb 11, 2022 |
| HP            | ProBook 450 G6              | [d8a9a9c7d3](https://linux-hardware.org/?probe=d8a9a9c7d3) | Jan 31, 2022 |
| Lenovo        | ThinkPad T490 20N3S5DV0S    | [e619ec0303](https://linux-hardware.org/?probe=e619ec0303) | Jan 31, 2022 |
| Medion        | P6685 MD61138               | [57dfdfb610](https://linux-hardware.org/?probe=57dfdfb610) | Jan 27, 2022 |
| win elemen... | MoreFine S500+              | [d7767ce266](https://linux-hardware.org/?probe=d7767ce266) | Jan 23, 2022 |
| win elemen... | MoreFine S500+              | [d63a6d7de6](https://linux-hardware.org/?probe=d63a6d7de6) | Jan 23, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [6892ab87e1](https://linux-hardware.org/?probe=6892ab87e1) | Jan 13, 2022 |
| Packard Be... | EasyNote TJ65               | [252c250082](https://linux-hardware.org/?probe=252c250082) | Jan 06, 2022 |
| Fujitsu       | LIFEBOOK E746               | [55ac013e1e](https://linux-hardware.org/?probe=55ac013e1e) | Jan 06, 2022 |
| Fujitsu       | LIFEBOOK E746               | [2f7baecdec](https://linux-hardware.org/?probe=2f7baecdec) | Jan 02, 2022 |
| Fujitsu       | LIFEBOOK E746               | [54248086d3](https://linux-hardware.org/?probe=54248086d3) | Dec 25, 2021 |
| Fujitsu       | LIFEBOOK E746               | [1b53993ffc](https://linux-hardware.org/?probe=1b53993ffc) | Dec 25, 2021 |
| Dell          | XPS 15 7590                 | [63f386f998](https://linux-hardware.org/?probe=63f386f998) | Nov 23, 2021 |
| Sony          | VGN-NS30E_S                 | [a36535818d](https://linux-hardware.org/?probe=a36535818d) | Nov 20, 2021 |
| YJKC          | vBook                       | [42ccc640d7](https://linux-hardware.org/?probe=42ccc640d7) | Nov 03, 2021 |
| MSI           | GF72 8RD                    | [4ac8472977](https://linux-hardware.org/?probe=4ac8472977) | Oct 23, 2021 |
| Wortmann      | TERRA_MOBILE_1749           | [8917a2fc6b](https://linux-hardware.org/?probe=8917a2fc6b) | Oct 15, 2021 |
| Dell          | Precision M2800             | [b046a9dfe3](https://linux-hardware.org/?probe=b046a9dfe3) | Oct 08, 2021 |
| ASUSTek       | UX360CA                     | [52039745c7](https://linux-hardware.org/?probe=52039745c7) | Sep 15, 2021 |
| ASUSTek       | UX360CA                     | [413bad53c5](https://linux-hardware.org/?probe=413bad53c5) | Sep 14, 2021 |
| HP            | ProBook 450 G6              | [03689a5674](https://linux-hardware.org/?probe=03689a5674) | Sep 10, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U7S... | [da01ae06a6](https://linux-hardware.org/?probe=da01ae06a6) | Sep 09, 2021 |
| Dell          | Precision M3800             | [5dba4d3bce](https://linux-hardware.org/?probe=5dba4d3bce) | Sep 07, 2021 |
| Dell          | Inspiron 16 7610            | [29c29dc50b](https://linux-hardware.org/?probe=29c29dc50b) | Sep 06, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [d819b1cc24](https://linux-hardware.org/?probe=d819b1cc24) | Sep 04, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [b5388437b9](https://linux-hardware.org/?probe=b5388437b9) | Sep 04, 2021 |
| HP            | Pavilion Gaming Notebook    | [3b8bef3c61](https://linux-hardware.org/?probe=3b8bef3c61) | Aug 23, 2021 |
| HP            | Pavilion Gaming Notebook    | [c2a3d9da9e](https://linux-hardware.org/?probe=c2a3d9da9e) | Aug 12, 2021 |
| HP            | ProBook 6450b               | [e607e5a89e](https://linux-hardware.org/?probe=e607e5a89e) | Jul 31, 2021 |
| Acer          | Aspire V5-561G              | [caf0285b12](https://linux-hardware.org/?probe=caf0285b12) | Jul 17, 2021 |
| HP            | ProBook 450 G6              | [f13877e5d4](https://linux-hardware.org/?probe=f13877e5d4) | Jul 08, 2021 |
| Sony          | VPCP11S1R                   | [185fd7ceef](https://linux-hardware.org/?probe=185fd7ceef) | Jul 05, 2021 |
| HP            | EliteBook 850 G8 Noteboo... | [c031043704](https://linux-hardware.org/?probe=c031043704) | Jul 01, 2021 |
| HP            | EliteBook 850 G8 Noteboo... | [28c858a3ad](https://linux-hardware.org/?probe=28c858a3ad) | Jul 01, 2021 |
| Lenovo        | ThinkPad T480s 20L7001PF... | [b54604a23d](https://linux-hardware.org/?probe=b54604a23d) | Jun 10, 2021 |
| HUAWEI        | HLYL-WXX9                   | [22e9ce0306](https://linux-hardware.org/?probe=22e9ce0306) | Jun 10, 2021 |
| HUAWEI        | HLYL-WXX9                   | [4bc5bdf702](https://linux-hardware.org/?probe=4bc5bdf702) | Jun 10, 2021 |
| Fujitsu       | STYLISTIC Q702              | [6af6b1aa99](https://linux-hardware.org/?probe=6af6b1aa99) | May 17, 2021 |
| Wortmann      | TERRA_MOBILE_1749           | [47e02d3203](https://linux-hardware.org/?probe=47e02d3203) | May 14, 2021 |
| Fujitsu       | STYLISTIC Q702              | [ceb707caf8](https://linux-hardware.org/?probe=ceb707caf8) | May 14, 2021 |
| HP            | Pavilion Gaming Notebook    | [f514df9912](https://linux-hardware.org/?probe=f514df9912) | May 02, 2021 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [359bf83027](https://linux-hardware.org/?probe=359bf83027) | Apr 05, 2021 |
| Toshiba       | Satellite C55-A-1N0         | [7fe4a33a38](https://linux-hardware.org/?probe=7fe4a33a38) | Mar 27, 2021 |
| Apple         | MacBookPro8,1               | [467f82a695](https://linux-hardware.org/?probe=467f82a695) | Feb 22, 2021 |
| Apple         | MacBookPro14,1              | [34e4083988](https://linux-hardware.org/?probe=34e4083988) | Feb 20, 2021 |
| Dell          | Vostro 3558                 | [176249071b](https://linux-hardware.org/?probe=176249071b) | Feb 13, 2021 |
| HP            | ENVY 15 x360 PC             | [1760641bd6](https://linux-hardware.org/?probe=1760641bd6) | Feb 13, 2021 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [cdc7e7e576](https://linux-hardware.org/?probe=cdc7e7e576) | Dec 25, 2020 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [dfebaa1e1e](https://linux-hardware.org/?probe=dfebaa1e1e) | Dec 06, 2020 |
| Acer          | Aspire 4741                 | [e65bbc0990](https://linux-hardware.org/?probe=e65bbc0990) | Nov 28, 2020 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [a6b200eda6](https://linux-hardware.org/?probe=a6b200eda6) | Nov 13, 2020 |
| Dell          | Precision 5540              | [5b3140e7e8](https://linux-hardware.org/?probe=5b3140e7e8) | Oct 29, 2020 |
| Dell          | XPS 15 9560                 | [c2660b6ca0](https://linux-hardware.org/?probe=c2660b6ca0) | Oct 07, 2020 |
| Apple         | MacBookPro15,4              | [2352614158](https://linux-hardware.org/?probe=2352614158) | Sep 25, 2020 |
| Lenovo        | ThinkPad T440p 20AWS24B0... | [8178cca0f9](https://linux-hardware.org/?probe=8178cca0f9) | Sep 16, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [a06e93e3e9](https://linux-hardware.org/?probe=a06e93e3e9) | Sep 04, 2020 |
| Timi          | RedmiBook 14 II             | [6cd091184f](https://linux-hardware.org/?probe=6cd091184f) | Aug 21, 2020 |
| Packard Be... | EasyNote TJ65               | [cce3b0b23c](https://linux-hardware.org/?probe=cce3b0b23c) | Aug 07, 2020 |
| HP            | EliteBook 8470p             | [2de50effb2](https://linux-hardware.org/?probe=2de50effb2) | Jul 26, 2020 |
| HP            | EliteBook 8470p             | [c85723b6bf](https://linux-hardware.org/?probe=c85723b6bf) | Jul 23, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QTCT... | [0037393fbf](https://linux-hardware.org/?probe=0037393fbf) | Jul 02, 2020 |
| Clevo         | P170EM                      | [41248f6ae8](https://linux-hardware.org/?probe=41248f6ae8) | Jun 13, 2020 |
| Clevo         | P170EM                      | [6f7578fede](https://linux-hardware.org/?probe=6f7578fede) | Jun 13, 2020 |
| Lenovo        | G50-70 20351                | [fac974e5a6](https://linux-hardware.org/?probe=fac974e5a6) | May 03, 2020 |
| HP            | ENVY Laptop 17-ce1xxx       | [cf98b2c860](https://linux-hardware.org/?probe=cf98b2c860) | Apr 13, 2020 |
| Wortmann      | TERRA_MOBILE_1541H          | [46b44d2d1f](https://linux-hardware.org/?probe=46b44d2d1f) | Apr 12, 2020 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | [91c4d3ed7c](https://linux-hardware.org/?probe=91c4d3ed7c) | Apr 10, 2020 |
| Acer          | Aspire E5-771G              | [c8a1411a14](https://linux-hardware.org/?probe=c8a1411a14) | Mar 28, 2020 |
| Dell          | Precision M3800             | [33ee2bd8db](https://linux-hardware.org/?probe=33ee2bd8db) | Mar 22, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [945a4d4691](https://linux-hardware.org/?probe=945a4d4691) | Mar 21, 2020 |
| HP            | Spectre Laptop 13-af0xx     | [8ee92af301](https://linux-hardware.org/?probe=8ee92af301) | Oct 12, 2019 |
| MSI           | GF72 8RD                    | [b0a808dbdb](https://linux-hardware.org/?probe=b0a808dbdb) | Aug 09, 2019 |
| Sony          | SVF1421E2EW                 | [6fd2106f13](https://linux-hardware.org/?probe=6fd2106f13) | Mar 02, 2019 |
| Medion        | E4254 MD62100               | [660722192a](https://linux-hardware.org/?probe=660722192a) | Jan 25, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 12        | 12.63%  |
| Ubuntu 22.04                 | 6         | 6.32%   |
| Ubuntu 18.04                 | 5         | 5.26%   |
| openSUSE Tumbleweed-XXXXXXXX | 4         | 4.21%   |
| Linux Mint 20.3              | 4         | 4.21%   |
| Ubuntu 21.04                 | 3         | 3.16%   |
| Pop!_OS 21.04                | 3         | 3.16%   |
| OpenMandriva 4.2             | 3         | 3.16%   |
| Xubuntu 20.04                | 2         | 2.11%   |
| Ubuntu 20.10                 | 2         | 2.11%   |
| Pop!_OS 22.04                | 2         | 2.11%   |
| Parrot 5.3                   | 2         | 2.11%   |
| OpenMandriva 4.90            | 2         | 2.11%   |
| OpenMandriva 23.03           | 2         | 2.11%   |
| Linux Mint 21.2              | 2         | 2.11%   |
| Fedora 37                    | 2         | 2.11%   |
| Xubuntu 18.04                | 1         | 1.05%   |
| Ubuntu MATE 21.10            | 1         | 1.05%   |
| Ubuntu MATE 20.04            | 1         | 1.05%   |
| Ubuntu 23.10                 | 1         | 1.05%   |
| Ubuntu 18.10                 | 1         | 1.05%   |
| RHEL 8                       | 1         | 1.05%   |
| Pop!_OS 21.10                | 1         | 1.05%   |
| Pop!_OS 20.10                | 1         | 1.05%   |
| Pop!_OS 20.04                | 1         | 1.05%   |
| Parrot 5.1                   | 1         | 1.05%   |
| openSUSE Leap-15.1           | 1         | 1.05%   |
| OpenMandriva 4.3             | 1         | 1.05%   |
| OpenMandriva 23.10           | 1         | 1.05%   |
| Manjaro 21.2.6               | 1         | 1.05%   |
| Manjaro 19.0.2               | 1         | 1.05%   |
| Lubuntu 20.04                | 1         | 1.05%   |
| LMDE 4                       | 1         | 1.05%   |
| Linux Mint 20.2              | 1         | 1.05%   |
| Linux Mint 19.2              | 1         | 1.05%   |
| Kubuntu 23.04                | 1         | 1.05%   |
| Kubuntu 22.04                | 1         | 1.05%   |
| Kubuntu 18.04                | 1         | 1.05%   |
| KDE neon 22.04               | 1         | 1.05%   |
| Kali 2022.4                  | 1         | 1.05%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 28        | 31.82%  |
| OpenMandriva | 8         | 9.09%   |
| Pop!_OS      | 7         | 7.95%   |
| Linux Mint   | 7         | 7.95%   |
| openSUSE     | 5         | 5.68%   |
| Fedora       | 4         | 4.55%   |
| Xubuntu      | 3         | 3.41%   |
| Parrot       | 3         | 3.41%   |
| Kubuntu      | 3         | 3.41%   |
| Ubuntu MATE  | 2         | 2.27%   |
| Manjaro      | 2         | 2.27%   |
| Endless      | 2         | 2.27%   |
| Debian       | 2         | 2.27%   |
| RHEL         | 1         | 1.14%   |
| Lubuntu      | 1         | 1.14%   |
| LMDE         | 1         | 1.14%   |
| KDE neon     | 1         | 1.14%   |
| Kali         | 1         | 1.14%   |
| Garuda Linux | 1         | 1.14%   |
| Elementary   | 1         | 1.14%   |
| Clear Linux  | 1         | 1.14%   |
| CachyOS      | 1         | 1.14%   |
| BlackPanther | 1         | 1.14%   |
| ArcoLinux    | 1         | 1.14%   |
| Arch         | 1         | 1.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.11.0-27-generic        | 3         | 3.09%   |
| 5.10.14-desktop-1omv4002 | 3         | 3.09%   |
| 6.2.6-desktop-1omv2390   | 2         | 2.06%   |
| 6.2.14-200.fc37.x86_64   | 2         | 2.06%   |
| 6.1.0-1parrot1-amd64     | 2         | 2.06%   |
| 5.8.0-59-generic         | 2         | 2.06%   |
| 5.4.0-96-generic         | 2         | 2.06%   |
| 5.4.0-122-generic        | 2         | 2.06%   |
| 5.19.0-35-generic        | 2         | 2.06%   |
| 5.18.12-desktop-3omv4090 | 2         | 2.06%   |
| 5.11.0-34-generic        | 2         | 2.06%   |
| 5.11.0-17-generic        | 2         | 2.06%   |
| 5.0.0-23-generic         | 2         | 2.06%   |
| 6.5.7-2-cachyos          | 1         | 1.03%   |
| 6.5.5-desktop-1omv2390   | 1         | 1.03%   |
| 6.5.0-10-generic         | 1         | 1.03%   |
| 6.4.3-1-default          | 1         | 1.03%   |
| 6.4.3-060403-generic     | 1         | 1.03%   |
| 6.2.0-26-generic         | 1         | 1.03%   |
| 6.1.8-060108-generic     | 1         | 1.03%   |
| 6.0.6-76060006-generic   | 1         | 1.03%   |
| 6.0.0-kali3-amd64        | 1         | 1.03%   |
| 5.8.11-050811-generic    | 1         | 1.03%   |
| 5.8.0-63-generic         | 1         | 1.03%   |
| 5.8.0-55-generic         | 1         | 1.03%   |
| 5.8.0-43-generic         | 1         | 1.03%   |
| 5.8.0-31-generic         | 1         | 1.03%   |
| 5.8.0-20-generic         | 1         | 1.03%   |
| 5.8.0-14-generic         | 1         | 1.03%   |
| 5.7.6-201.fc32.x86_64    | 1         | 1.03%   |
| 5.7.1-1-default          | 1         | 1.03%   |
| 5.7.0-3-amd64            | 1         | 1.03%   |
| 5.7.0-050700-generic     | 1         | 1.03%   |
| 5.6.3-935.native         | 1         | 1.03%   |
| 5.5.8-1-MANJARO          | 1         | 1.03%   |
| 5.4.0-84-generic         | 1         | 1.03%   |
| 5.4.0-73-generic         | 1         | 1.03%   |
| 5.4.0-52-generic         | 1         | 1.03%   |
| 5.4.0-47-generic         | 1         | 1.03%   |
| 5.4.0-42-generic         | 1         | 1.03%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 12        | 12.63%  |
| 5.4.0   | 9         | 9.47%   |
| 5.8.0   | 8         | 8.42%   |
| 5.15.0  | 6         | 6.32%   |
| 5.19.0  | 5         | 5.26%   |
| 5.13.0  | 4         | 4.21%   |
| 5.3.0   | 3         | 3.16%   |
| 5.10.14 | 3         | 3.16%   |
| 4.15.0  | 3         | 3.16%   |
| 6.4.3   | 2         | 2.11%   |
| 6.2.6   | 2         | 2.11%   |
| 6.2.14  | 2         | 2.11%   |
| 6.1.0   | 2         | 2.11%   |
| 5.7.0   | 2         | 2.11%   |
| 5.18.12 | 2         | 2.11%   |
| 5.0.0   | 2         | 2.11%   |
| 4.18.0  | 2         | 2.11%   |
| 6.5.7   | 1         | 1.05%   |
| 6.5.5   | 1         | 1.05%   |
| 6.5.0   | 1         | 1.05%   |
| 6.2.0   | 1         | 1.05%   |
| 6.1.8   | 1         | 1.05%   |
| 6.0.6   | 1         | 1.05%   |
| 6.0.0   | 1         | 1.05%   |
| 5.8.11  | 1         | 1.05%   |
| 5.7.6   | 1         | 1.05%   |
| 5.7.1   | 1         | 1.05%   |
| 5.6.3   | 1         | 1.05%   |
| 5.5.8   | 1         | 1.05%   |
| 5.18.5  | 1         | 1.05%   |
| 5.18.0  | 1         | 1.05%   |
| 5.16.7  | 1         | 1.05%   |
| 5.16.2  | 1         | 1.05%   |
| 5.16.11 | 1         | 1.05%   |
| 5.15.4  | 1         | 1.05%   |
| 5.15.32 | 1         | 1.05%   |
| 5.14.0  | 1         | 1.05%   |
| 5.12.13 | 1         | 1.05%   |
| 5.10.26 | 1         | 1.05%   |
| 5.10.0  | 1         | 1.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 12        | 12.63%  |
| 5.8     | 9         | 9.47%   |
| 5.4     | 9         | 9.47%   |
| 5.15    | 8         | 8.42%   |
| 6.2     | 5         | 5.26%   |
| 5.19    | 5         | 5.26%   |
| 5.10    | 5         | 5.26%   |
| 5.7     | 4         | 4.21%   |
| 5.18    | 4         | 4.21%   |
| 5.13    | 4         | 4.21%   |
| 6.5     | 3         | 3.16%   |
| 6.1     | 3         | 3.16%   |
| 5.3     | 3         | 3.16%   |
| 5.16    | 3         | 3.16%   |
| 4.18    | 3         | 3.16%   |
| 4.15    | 3         | 3.16%   |
| 6.4     | 2         | 2.11%   |
| 6.0     | 2         | 2.11%   |
| 5.0     | 2         | 2.11%   |
| 5.6     | 1         | 1.05%   |
| 5.5     | 1         | 1.05%   |
| 5.14    | 1         | 1.05%   |
| 5.12    | 1         | 1.05%   |
| 4.19    | 1         | 1.05%   |
| 4.12    | 1         | 1.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 84        | 98.82%  |
| i686   | 1         | 1.18%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 38        | 43.68%  |
| KDE5            | 15        | 17.24%  |
| X-Cinnamon      | 8         | 9.2%    |
| XFCE            | 6         | 6.9%    |
| Unknown         | 6         | 6.9%    |
| MATE            | 5         | 5.75%   |
| KDE             | 3         | 3.45%   |
| i3              | 2         | 2.3%    |
| Pantheon        | 1         | 1.15%   |
| LXQt            | 1         | 1.15%   |
| GNOME Flashback | 1         | 1.15%   |
| Cinnamon        | 1         | 1.15%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 68        | 76.4%   |
| Wayland | 17        | 19.1%   |
| Unknown | 4         | 4.49%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 40        | 44.44%  |
| GDM     | 15        | 16.67%  |
| LightDM | 13        | 14.44%  |
| SDDM    | 11        | 12.22%  |
| GDM3    | 8         | 8.89%   |
| TDM     | 3         | 3.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 41        | 46.07%  |
| en_GB   | 8         | 8.99%   |
| Unknown | 7         | 7.87%   |
| de_DE   | 6         | 6.74%   |
| de_LU   | 5         | 5.62%   |
| fr_LU   | 4         | 4.49%   |
| fr_FR   | 4         | 4.49%   |
| pt_BR   | 2         | 2.25%   |
| nl_NL   | 2         | 2.25%   |
| unm_US  | 1         | 1.12%   |
| pt_PT   | 1         | 1.12%   |
| POSIX   | 1         | 1.12%   |
| it_IT   | 1         | 1.12%   |
| hr_HR   | 1         | 1.12%   |
| fr_CH   | 1         | 1.12%   |
| es_ES   | 1         | 1.12%   |
| en_IE   | 1         | 1.12%   |
| en_AU   | 1         | 1.12%   |
| C       | 1         | 1.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 51        | 58.62%  |
| BIOS | 36        | 41.38%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 62        | 72.09%  |
| Btrfs   | 11        | 12.79%  |
| Overlay | 8         | 9.3%    |
| Xfs     | 3         | 3.49%   |
| Tmpfs   | 1         | 1.16%   |
| Unknown | 1         | 1.16%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 40        | 46.51%  |
| Unknown | 39        | 45.35%  |
| MBR     | 7         | 8.14%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 79        | 91.86%  |
| Yes       | 7         | 8.14%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 64        | 75.29%  |
| Yes       | 21        | 24.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 14        | 16.47%  |
| Lenovo              | 12        | 14.12%  |
| Dell                | 11        | 12.94%  |
| ASUSTek Computer    | 7         | 8.24%   |
| Acer                | 6         | 7.06%   |
| Sony                | 5         | 5.88%   |
| HUAWEI              | 4         | 4.71%   |
| Apple               | 4         | 4.71%   |
| Wortmann AG         | 3         | 3.53%   |
| win element         | 2         | 2.35%   |
| MSI                 | 2         | 2.35%   |
| Medion              | 2         | 2.35%   |
| Fujitsu             | 2         | 2.35%   |
| Clevo               | 2         | 2.35%   |
| YJKC                | 1         | 1.18%   |
| TUXEDO              | 1         | 1.18%   |
| Toshiba             | 1         | 1.18%   |
| Timi                | 1         | 1.18%   |
| SLIMBOOK            | 1         | 1.18%   |
| Samsung Electronics | 1         | 1.18%   |
| Panasonic           | 1         | 1.18%   |
| Packard Bell        | 1         | 1.18%   |
| Notebook            | 1         | 1.18%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| win element MoreFine S500+               | 2         | 2.35%   |
| Dell Precision M3800                     | 2         | 2.35%   |
| Dell Precision 7670                      | 2         | 2.35%   |
| YJKC vBook                               | 1         | 1.18%   |
| Wortmann AG TERRA_MOBILE_1749            | 1         | 1.18%   |
| Wortmann AG TERRA_MOBILE_1541H           | 1         | 1.18%   |
| Wortmann AG MS-1727                      | 1         | 1.18%   |
| TUXEDO Pulse 14 Gen1                     | 1         | 1.18%   |
| Toshiba Satellite C55-A-1N0              | 1         | 1.18%   |
| Timi RedmiBook 14 II                     | 1         | 1.18%   |
| Sony VPCP11S1R                           | 1         | 1.18%   |
| Sony VPCEB2E1E                           | 1         | 1.18%   |
| Sony VPCCA4E1E                           | 1         | 1.18%   |
| Sony VGN-NS30E_S                         | 1         | 1.18%   |
| Sony SVF1421E2EW                         | 1         | 1.18%   |
| SLIMBOOK EXECUTIVE-14                    | 1         | 1.18%   |
| Samsung 550XBE/350XBE                    | 1         | 1.18%   |
| Panasonic CF-195DCUBML                   | 1         | 1.18%   |
| Packard Bell EasyNote TJ65               | 1         | 1.18%   |
| Notebook NV4XMB,ME,MZ                    | 1         | 1.18%   |
| MSI GF72 8RD                             | 1         | 1.18%   |
| MSI GE63 7RD                             | 1         | 1.18%   |
| Medion P6685 MD61138                     | 1         | 1.18%   |
| Medion E4254 MD62100                     | 1         | 1.18%   |
| Lenovo ThinkPad X1 Carbon 7th 20QDCTO1WW | 1         | 1.18%   |
| Lenovo ThinkPad T590 20N4CTO1WW          | 1         | 1.18%   |
| Lenovo ThinkPad T490 20N3S5DV0S          | 1         | 1.18%   |
| Lenovo ThinkPad T480s 20L7001PFR         | 1         | 1.18%   |
| Lenovo ThinkPad T470s W10DG 20JTS0R800   | 1         | 1.18%   |
| Lenovo ThinkPad T440p 20AWS24B00         | 1         | 1.18%   |
| Lenovo ThinkPad P1 Gen 2 20QTCTO1WW      | 1         | 1.18%   |
| Lenovo ThinkPad L15 Gen 1 20U8S0AH00     | 1         | 1.18%   |
| Lenovo ThinkPad L15 Gen 1 20U7S05B00     | 1         | 1.18%   |
| Lenovo ThinkPad L14 Gen 2a 20X6S15A00    | 1         | 1.18%   |
| Lenovo IdeaPad 330-15ICH 81FK            | 1         | 1.18%   |
| Lenovo G50-70 20351                      | 1         | 1.18%   |
| HUAWEI KLVL-WXXW                         | 1         | 1.18%   |
| HUAWEI HVY-WXX9                          | 1         | 1.18%   |
| HUAWEI HLYL-WXX9                         | 1         | 1.18%   |
| HUAWEI CREM-WXX9                         | 1         | 1.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 10        | 11.76%  |
| Dell Precision         | 7         | 8.24%   |
| HP EliteBook           | 4         | 4.71%   |
| Acer Aspire            | 4         | 4.71%   |
| ASUS VivoBook          | 3         | 3.53%   |
| Wortmann AG TERRA      | 2         | 2.35%   |
| win element MoreFine   | 2         | 2.35%   |
| HP ZBook               | 2         | 2.35%   |
| HP ProBook             | 2         | 2.35%   |
| HP ENVY                | 2         | 2.35%   |
| Dell XPS               | 2         | 2.35%   |
| YJKC vBook             | 1         | 1.18%   |
| Wortmann AG MS-1727    | 1         | 1.18%   |
| TUXEDO Pulse           | 1         | 1.18%   |
| Toshiba Satellite      | 1         | 1.18%   |
| Timi RedmiBook         | 1         | 1.18%   |
| Sony VPCP11S1R         | 1         | 1.18%   |
| Sony VPCEB2E1E         | 1         | 1.18%   |
| Sony VPCCA4E1E         | 1         | 1.18%   |
| Sony VGN-NS30E         | 1         | 1.18%   |
| Sony SVF1421E2EW       | 1         | 1.18%   |
| SLIMBOOK EXECUTIVE-14  | 1         | 1.18%   |
| Samsung 550XBE         | 1         | 1.18%   |
| Panasonic CF-195DCUBML | 1         | 1.18%   |
| Packard Bell EasyNote  | 1         | 1.18%   |
| Notebook NV4XMB        | 1         | 1.18%   |
| MSI GF72               | 1         | 1.18%   |
| MSI GE63               | 1         | 1.18%   |
| Medion P6685           | 1         | 1.18%   |
| Medion E4254           | 1         | 1.18%   |
| Lenovo IdeaPad         | 1         | 1.18%   |
| Lenovo G50-70          | 1         | 1.18%   |
| HUAWEI KLVL-WXXW       | 1         | 1.18%   |
| HUAWEI HVY-WXX9        | 1         | 1.18%   |
| HUAWEI HLYL-WXX9       | 1         | 1.18%   |
| HUAWEI CREM-WXX9       | 1         | 1.18%   |
| HP Spectre             | 1         | 1.18%   |
| HP Pavilion            | 1         | 1.18%   |
| HP OMEN                | 1         | 1.18%   |
| HP 255                 | 1         | 1.18%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 12        | 14.12%  |
| 2021 | 10        | 11.76%  |
| 2020 | 9         | 10.59%  |
| 2018 | 9         | 10.59%  |
| 2017 | 7         | 8.24%   |
| 2014 | 7         | 8.24%   |
| 2013 | 7         | 8.24%   |
| 2011 | 5         | 5.88%   |
| 2010 | 5         | 5.88%   |
| 2022 | 4         | 4.71%   |
| 2015 | 3         | 3.53%   |
| 2016 | 2         | 2.35%   |
| 2012 | 2         | 2.35%   |
| 2009 | 2         | 2.35%   |
| 2023 | 1         | 1.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 85        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 75        | 87.21%  |
| Enabled  | 11        | 12.79%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 85        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 21        | 24.14%  |
| 8.01-16.0   | 20        | 22.99%  |
| 4.01-8.0    | 17        | 19.54%  |
| 3.01-4.0    | 12        | 13.79%  |
| 32.01-64.0  | 9         | 10.34%  |
| 64.01-256.0 | 3         | 3.45%   |
| 2.01-3.0    | 2         | 2.3%    |
| 1.01-2.0    | 2         | 2.3%    |
| 24.01-32.0  | 1         | 1.15%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 30        | 33.71%  |
| 1.01-2.0   | 21        | 23.6%   |
| 4.01-8.0   | 14        | 15.73%  |
| 3.01-4.0   | 12        | 13.48%  |
| 8.01-16.0  | 7         | 7.87%   |
| 24.01-32.0 | 2         | 2.25%   |
| 16.01-24.0 | 1         | 1.12%   |
| 0.51-1.0   | 1         | 1.12%   |
| 0.01-0.5   | 1         | 1.12%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 63        | 73.26%  |
| 2      | 15        | 17.44%  |
| 3      | 7         | 8.14%   |
| 0      | 1         | 1.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 59        | 69.41%  |
| Yes       | 26        | 30.59%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 65        | 76.47%  |
| No        | 20        | 23.53%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 85        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 87.06%  |
| No        | 11        | 12.94%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| Luxembourg | 85        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Luxembourg        | 52        | 57.14%  |
| Strassen          | 8         | 8.79%   |
| Schifflange       | 3         | 3.3%    |
| Useldange         | 2         | 2.2%    |
| Steinfort         | 2         | 2.2%    |
| Schieren          | 2         | 2.2%    |
| Ehnen             | 2         | 2.2%    |
| Wiltz             | 1         | 1.1%    |
| Wecker            | 1         | 1.1%    |
| Vianden           | 1         | 1.1%    |
| Soleuvre          | 1         | 1.1%    |
| PerlГ©          | 1         | 1.1%    |
| Oberpallen        | 1         | 1.1%    |
| Niederanven       | 1         | 1.1%    |
| Leudelange        | 1         | 1.1%    |
| Hunsdorf          | 1         | 1.1%    |
| Ettelbruck        | 1         | 1.1%    |
| Esch-sur-Alzette  | 1         | 1.1%    |
| Echternach        | 1         | 1.1%    |
| Differdange       | 1         | 1.1%    |
| Diekirch          | 1         | 1.1%    |
| Clervaux          | 1         | 1.1%    |
| Bourscheid        | 1         | 1.1%    |
| Bettembourg       | 1         | 1.1%    |
| Bettange-sur-Mess | 1         | 1.1%    |
| Beckerich         | 1         | 1.1%    |
| Aspelt            | 1         | 1.1%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 26        | 34     | 23.42%  |
| Toshiba                     | 12        | 13     | 10.81%  |
| Seagate                     | 12        | 12     | 10.81%  |
| WDC                         | 10        | 12     | 9.01%   |
| SanDisk                     | 8         | 11     | 7.21%   |
| Kingston                    | 7         | 9      | 6.31%   |
| Crucial                     | 6         | 8      | 5.41%   |
| SK hynix                    | 4         | 4      | 3.6%    |
| Apple                       | 4         | 5      | 3.6%    |
| Intel                       | 3         | 4      | 2.7%    |
| Micron Technology           | 2         | 3      | 1.8%    |
| LITEONIT                    | 2         | 2      | 1.8%    |
| HGST                        | 2         | 2      | 1.8%    |
| Union Memory (Shenzhen)     | 1         | 1      | 0.9%    |
| Phison Electronics          | 1         | 1      | 0.9%    |
| PHD 3.0                     | 1         | 1      | 0.9%    |
| LITEON                      | 1         | 1      | 0.9%    |
| Lenovo                      | 1         | 1      | 0.9%    |
| LaCie                       | 1         | 1      | 0.9%    |
| Kingston Technology Company | 1         | 2      | 0.9%    |
| KingDian                    | 1         | 1      | 0.9%    |
| Intenso                     | 1         | 2      | 0.9%    |
| HUAWEI                      | 1         | 1      | 0.9%    |
| Hitachi                     | 1         | 1      | 0.9%    |
| FORESEE                     | 1         | 1      | 0.9%    |
| A-DATA Technology           | 1         | 1      | 0.9%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Seagate Expansion 1TB                        | 3         | 2.54%   |
| WDC WD10JPVX-22JC3T0 1TB                     | 2         | 1.69%   |
| Toshiba MQ01ABF050 500GB                     | 2         | 1.69%   |
| SanDisk SD8SN8U128G1122 128GB SSD            | 2         | 1.69%   |
| SanDisk NVMe SSD Drive 1TB                   | 2         | 1.69%   |
| Samsung SSD 860 QVO 1TB                      | 2         | 1.69%   |
| Samsung MZVLW256HEHP-000L7 256GB             | 2         | 1.69%   |
| LITEONIT LMT-256L9M-11 MSATA 256GB SSD       | 2         | 1.69%   |
| WDC WDS250G2B0B-00YS70 250GB SSD             | 1         | 0.85%   |
| WDC WD3200LPCX-00VHAT0 320GB                 | 1         | 0.85%   |
| WDC WD10SPZX-17Z10T0 1TB                     | 1         | 0.85%   |
| WDC WD10SPCX-60HWST0 1TB                     | 1         | 0.85%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB         | 1         | 0.85%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB         | 1         | 0.85%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB           | 1         | 0.85%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB         | 1         | 0.85%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 0.85%   |
| Toshiba THNSNJ256G8NY 256GB SSD              | 1         | 0.85%   |
| Toshiba THNSNJ128GCST 128GB SSD              | 1         | 0.85%   |
| Toshiba NVMe SSD Drive 512GB                 | 1         | 0.85%   |
| Toshiba MQ02ABD100H 1TB                      | 1         | 0.85%   |
| Toshiba MK7575GSX 752GB                      | 1         | 0.85%   |
| Toshiba MK6459GSXP 640GB                     | 1         | 0.85%   |
| Toshiba MK2555GSX 250GB                      | 1         | 0.85%   |
| Toshiba KXG60PNV2T04 NVMe KIOXIA 2048GB      | 1         | 0.85%   |
| Toshiba KXG50ZNV512G 512GB                   | 1         | 0.85%   |
| Toshiba KXG50ZNV256G 256GB                   | 1         | 0.85%   |
| SK hynix PC801 NVMe 1TB                      | 1         | 0.85%   |
| SK hynix PC711 HFS512GDE9X073N 512GB         | 1         | 0.85%   |
| SK hynix HFS128G39TND-N210A 128GB SSD        | 1         | 0.85%   |
| SK hynix HCG8e  64GB                         | 1         | 0.85%   |
| Seagate ST950042 0ASG 500GB                  | 1         | 0.85%   |
| Seagate ST9320423AS 320GB                    | 1         | 0.85%   |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 0.85%   |
| Seagate ST2000LM015-2E8174 2TB               | 1         | 0.85%   |
| Seagate ST1000LM049-2GH172 1TB               | 1         | 0.85%   |
| Seagate ST1000LM048-2E7172 1TB               | 1         | 0.85%   |
| Seagate ST1000LM035-1RK172 1TB               | 1         | 0.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 0.85%   |
| Seagate ST1000LM014-1EJ164 1TB               | 1         | 0.85%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 12     | 42.86%  |
| Toshiba             | 6         | 7      | 21.43%  |
| WDC                 | 5         | 7      | 17.86%  |
| HGST                | 2         | 2      | 7.14%   |
| Samsung Electronics | 1         | 1      | 3.57%   |
| Hitachi             | 1         | 1      | 3.57%   |
| Apple               | 1         | 1      | 3.57%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 17     | 29.27%  |
| SanDisk             | 6         | 7      | 14.63%  |
| Crucial             | 5         | 7      | 12.2%   |
| Kingston            | 3         | 5      | 7.32%   |
| Toshiba             | 2         | 2      | 4.88%   |
| Micron Technology   | 2         | 3      | 4.88%   |
| LITEONIT            | 2         | 2      | 4.88%   |
| WDC                 | 1         | 1      | 2.44%   |
| SK hynix            | 1         | 1      | 2.44%   |
| PHD 3.0             | 1         | 1      | 2.44%   |
| LITEON              | 1         | 1      | 2.44%   |
| Lenovo              | 1         | 1      | 2.44%   |
| KingDian            | 1         | 1      | 2.44%   |
| Intenso             | 1         | 2      | 2.44%   |
| FORESEE             | 1         | 1      | 2.44%   |
| Apple               | 1         | 1      | 2.44%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 40        | 47     | 38.1%   |
| SSD     | 34        | 53     | 32.38%  |
| HDD     | 28        | 31     | 26.67%  |
| Unknown | 2         | 2      | 1.9%    |
| MMC     | 1         | 1      | 0.95%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 51        | 77     | 50.5%   |
| NVMe | 40        | 46     | 39.6%   |
| SAS  | 9         | 10     | 8.91%   |
| MMC  | 1         | 1      | 0.99%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 38        | 51     | 58.46%  |
| 0.51-1.0   | 24        | 30     | 36.92%  |
| 1.01-2.0   | 3         | 3      | 4.62%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 26        | 28.89%  |
| 101-250        | 18        | 20%     |
| 501-1000       | 15        | 16.67%  |
| 1001-2000      | 8         | 8.89%   |
| Unknown        | 6         | 6.67%   |
| More than 3000 | 4         | 4.44%   |
| 1-20           | 4         | 4.44%   |
| 51-100         | 4         | 4.44%   |
| 2001-3000      | 3         | 3.33%   |
| 21-50          | 2         | 2.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 29        | 32.22%  |
| 21-50     | 14        | 15.56%  |
| 101-250   | 12        | 13.33%  |
| 251-500   | 9         | 10%     |
| 51-100    | 9         | 10%     |
| 501-1000  | 7         | 7.78%   |
| Unknown   | 6         | 6.67%   |
| 2001-3000 | 3         | 3.33%   |
| 1001-2000 | 1         | 1.11%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABF050 500GB              | 2         | 2      | 40%     |
| Toshiba MK2555GSX 250GB               | 1         | 1      | 20%     |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 20%     |
| Seagate ST1000LM049-2GH172 1TB        | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Toshiba  | 3         | 3      | 60%     |
| SK hynix | 1         | 1      | 20%     |
| Seagate  | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 3         | 3      | 75%     |
| Seagate | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 4      | 80%     |
| SSD  | 1         | 1      | 20%     |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 43        | 71     | 47.25%  |
| Works    | 43        | 58     | 47.25%  |
| Malfunc  | 5         | 5      | 5.49%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 58        | 55.77%  |
| Samsung Electronics          | 13        | 12.5%   |
| SanDisk                      | 8         | 7.69%   |
| AMD                          | 7         | 6.73%   |
| Kingston Technology Company  | 5         | 4.81%   |
| Toshiba America Info Systems | 4         | 3.85%   |
| SK hynix                     | 2         | 1.92%   |
| Apple                        | 2         | 1.92%   |
| Union Memory (Shenzhen)      | 1         | 0.96%   |
| Phison Electronics           | 1         | 0.96%   |
| Micron/Crucial Technology    | 1         | 0.96%   |
| Marvell Technology Group     | 1         | 0.96%   |
| ADATA Technology             | 1         | 0.96%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 8         | 7.48%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 7         | 6.54%   |
| Intel Volume Management Device NVMe RAID Controller                            | 6         | 5.61%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 5         | 4.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 4.67%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 4.67%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 5         | 4.67%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 3.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 3.74%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 2.8%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 3         | 2.8%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 2.8%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 2.8%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 2.8%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 2.8%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 1.87%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 2         | 1.87%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 1.87%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 1.87%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.87%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.87%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.87%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 1.87%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 x2 NVMe SSD 128GB, 256GB                | 1         | 0.93%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 1         | 0.93%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 1         | 0.93%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 1         | 0.93%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1         | 0.93%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1         | 0.93%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 1         | 0.93%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 1         | 0.93%   |
| Kingston Company NV2 NVMe SSD SM2267XT                                         | 1         | 0.93%   |
| Kingston Company KC2000/KC2500 NVMe SSD SM2262EN                               | 1         | 0.93%   |
| Kingston Company Design-In PCIe 4 NVMe SSD (TLC)                               | 1         | 0.93%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                                 | 1         | 0.93%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 1         | 0.93%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                     | 1         | 0.93%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 0.93%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 1         | 0.93%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 1         | 0.93%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 55        | 51.89%  |
| NVMe | 40        | 37.74%  |
| RAID | 10        | 9.43%   |
| IDE  | 1         | 0.94%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 72        | 84.71%  |
| AMD    | 13        | 15.29%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-8265U CPU @ 1.60GHz           | 4         | 4.71%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 3         | 3.53%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 3.53%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 3         | 3.53%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 2         | 2.35%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 2         | 2.35%   |
| Intel Core i7-4702HQ CPU @ 2.20GHz          | 2         | 2.35%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 2         | 2.35%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 2         | 2.35%   |
| AMD Ryzen 9 5900HX with Radeon Graphics     | 2         | 2.35%   |
| AMD Ryzen 5 4600H with Radeon Graphics      | 2         | 2.35%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 1.18%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 1.18%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 1         | 1.18%   |
| Intel Pentium CPU P6000 @ 1.87GHz           | 1         | 1.18%   |
| Intel Pentium CPU 987 @ 1.50GHz             | 1         | 1.18%   |
| Intel Core m5-6Y54 CPU @ 1.10GHz            | 1         | 1.18%   |
| Intel Core i9-9880H CPU @ 2.30GHz           | 1         | 1.18%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 1.18%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 1.18%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 1.18%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 1.18%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 1.18%   |
| Intel Core i7-4712MQ CPU @ 2.30GHz          | 1         | 1.18%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz          | 1         | 1.18%   |
| Intel Core i7-3940XM CPU @ 3.00GHz          | 1         | 1.18%   |
| Intel Core i7-3840QM CPU @ 2.80GHz          | 1         | 1.18%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 1.18%   |
| Intel Core i5-8257U CPU @ 1.40GHz           | 1         | 1.18%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.18%   |
| Intel Core i5-7360U CPU @ 2.30GHz           | 1         | 1.18%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 1.18%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz          | 1         | 1.18%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1         | 1.18%   |
| Intel Core i5-4330M CPU @ 2.80GHz           | 1         | 1.18%   |
| Intel Core i5-4250U CPU @ 1.30GHz           | 1         | 1.18%   |
| Intel Core i5-4210M CPU @ 2.60GHz           | 1         | 1.18%   |
| Intel Core i5-4200M CPU @ 2.50GHz           | 1         | 1.18%   |
| Intel Core i5-3427U CPU @ 1.80GHz           | 1         | 1.18%   |
| Intel Core i5-3340M CPU @ 2.70GHz           | 1         | 1.18%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 22        | 25.88%  |
| Intel Core i5           | 22        | 25.88%  |
| Other                   | 12        | 14.12%  |
| Intel Core i3           | 5         | 5.88%   |
| AMD Ryzen 5             | 4         | 4.71%   |
| Intel Celeron           | 3         | 3.53%   |
| AMD Ryzen 7             | 3         | 3.53%   |
| Intel Pentium Dual-Core | 2         | 2.35%   |
| Intel Pentium           | 2         | 2.35%   |
| AMD Ryzen 9             | 2         | 2.35%   |
| AMD Ryzen 5 PRO         | 2         | 2.35%   |
| Intel Pentium Silver    | 1         | 1.18%   |
| Intel Core m5           | 1         | 1.18%   |
| Intel Core i9           | 1         | 1.18%   |
| Intel Atom              | 1         | 1.18%   |
| AMD Ryzen 7 PRO         | 1         | 1.18%   |
| AMD E2                  | 1         | 1.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 30        | 35.29%  |
| 2      | 29        | 34.12%  |
| 6      | 10        | 11.76%  |
| 8      | 9         | 10.59%  |
| 16     | 3         | 3.53%   |
| 1      | 2         | 2.35%   |
| 14     | 1         | 1.18%   |
| 10     | 1         | 1.18%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 85        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 73        | 85.88%  |
| 1      | 12        | 14.12%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 84        | 98.82%  |
| 32-bit         | 1         | 1.18%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 26        | 28.89%  |
| 0x306c3    | 8         | 8.89%   |
| 0x206a7    | 5         | 5.56%   |
| 0x806ea    | 4         | 4.44%   |
| 0x806c1    | 4         | 4.44%   |
| 0x40651    | 4         | 4.44%   |
| 0x806eb    | 3         | 3.33%   |
| 0x406e3    | 3         | 3.33%   |
| 0x20655    | 3         | 3.33%   |
| 0x906ea    | 2         | 2.22%   |
| 0x906e9    | 2         | 2.22%   |
| 0x806ec    | 2         | 2.22%   |
| 0x806d1    | 2         | 2.22%   |
| 0x706a1    | 2         | 2.22%   |
| 0x306d4    | 2         | 2.22%   |
| 0x306a9    | 2         | 2.22%   |
| 0x1067a    | 2         | 2.22%   |
| 0x0a50000c | 2         | 2.22%   |
| 0x08600106 | 2         | 2.22%   |
| 0x906ed    | 1         | 1.11%   |
| 0x806e9    | 1         | 1.11%   |
| 0x20652    | 1         | 1.11%   |
| 0x106c2    | 1         | 1.11%   |
| 0x0a50000d | 1         | 1.11%   |
| 0x08608102 | 1         | 1.11%   |
| 0x08600104 | 1         | 1.11%   |
| 0x08600103 | 1         | 1.11%   |
| 0x08108102 | 1         | 1.11%   |
| 0x06006705 | 1         | 1.11%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 21        | 24.71%  |
| Haswell          | 12        | 14.12%  |
| Zen 2            | 6         | 7.06%   |
| TigerLake        | 5         | 5.88%   |
| Skylake          | 5         | 5.88%   |
| SandyBridge      | 5         | 5.88%   |
| Zen 3            | 4         | 4.71%   |
| Westmere         | 4         | 4.71%   |
| IvyBridge        | 4         | 4.71%   |
| Alderlake Hybrid | 3         | 3.53%   |
| Unknown          | 3         | 3.53%   |
| Penryn           | 2         | 2.35%   |
| Icelake          | 2         | 2.35%   |
| Goldmont plus    | 2         | 2.35%   |
| Broadwell        | 2         | 2.35%   |
| Zen+             | 1         | 1.18%   |
| Goldmont         | 1         | 1.18%   |
| Excavator        | 1         | 1.18%   |
| CometLake        | 1         | 1.18%   |
| Bonnell          | 1         | 1.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 67        | 58.26%  |
| Nvidia | 30        | 26.09%  |
| AMD    | 18        | 15.65%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 8         | 6.9%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 6         | 5.17%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 6         | 5.17%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]             | 6         | 5.17%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 5         | 4.31%   |
| Intel UHD Graphics 620                                                    | 4         | 3.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 4         | 3.45%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 4         | 3.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 4         | 3.45%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 4         | 3.45%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 3         | 2.59%   |
| Nvidia GA107GLM [RTX A1000 Laptop GPU]                                    | 3         | 2.59%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 3         | 2.59%   |
| Intel Alder Lake-HX GT1 [UHD Graphics 770]                                | 3         | 2.59%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 1.72%   |
| Nvidia GP108M [GeForce MX250]                                             | 2         | 1.72%   |
| Nvidia GP108M [GeForce MX150]                                             | 2         | 1.72%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 2         | 1.72%   |
| Nvidia GK107GLM [Quadro K1100M]                                           | 2         | 1.72%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 2         | 1.72%   |
| Intel HD Graphics 630                                                     | 2         | 1.72%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                             | 1         | 0.86%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                     | 1         | 0.86%   |
| Nvidia GT215M [GeForce GTS 250M]                                          | 1         | 0.86%   |
| Nvidia GM108M [GeForce MX110]                                             | 1         | 0.86%   |
| Nvidia GM108M [GeForce 840M]                                              | 1         | 0.86%   |
| Nvidia GM107M [GeForce GTX 950M]                                          | 1         | 0.86%   |
| Nvidia GM107M [GeForce GTX 850M]                                          | 1         | 0.86%   |
| Nvidia GK104M [GeForce GTX 680M]                                          | 1         | 0.86%   |
| Nvidia GF108M [GeForce GT 520M]                                           | 1         | 0.86%   |
| Nvidia GF108M [GeForce GT 415M]                                           | 1         | 0.86%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 1         | 0.86%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                        | 1         | 0.86%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 1         | 0.86%   |
| Nvidia G98M [GeForce G 105M]                                              | 1         | 0.86%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                       | 1         | 0.86%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                    | 1         | 0.86%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 0.86%   |
| Intel Iris Plus Graphics 640                                              | 1         | 0.86%   |
| Intel HD Graphics 5500                                                    | 1         | 0.86%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 37        | 43.53%  |
| Intel + Nvidia | 27        | 31.76%  |
| 1 x AMD        | 14        | 16.47%  |
| 1 x Nvidia     | 3         | 3.53%   |
| Intel + AMD    | 3         | 3.53%   |
| 2 x AMD        | 1         | 1.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 71        | 82.56%  |
| Proprietary | 13        | 15.12%  |
| Unknown     | 2         | 2.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 59        | 68.6%   |
| 3.01-4.0   | 9         | 10.47%  |
| 0.01-0.5   | 8         | 9.3%    |
| 1.01-2.0   | 6         | 6.98%   |
| 0.51-1.0   | 4         | 4.65%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 22        | 22.22%  |
| LG Display              | 15        | 15.15%  |
| Samsung Electronics     | 12        | 12.12%  |
| AU Optronics            | 11        | 11.11%  |
| Sharp                   | 6         | 6.06%   |
| BOE                     | 6         | 6.06%   |
| Hewlett-Packard         | 4         | 4.04%   |
| Apple                   | 4         | 4.04%   |
| AOC                     | 4         | 4.04%   |
| Chi Mei Optoelectronics | 3         | 3.03%   |
| Iiyama                  | 2         | 2.02%   |
| Videoseven              | 1         | 1.01%   |
| Sony                    | 1         | 1.01%   |
| Philips                 | 1         | 1.01%   |
| PANDA                   | 1         | 1.01%   |
| Medion                  | 1         | 1.01%   |
| Lenovo                  | 1         | 1.01%   |
| Goldstar                | 1         | 1.01%   |
| CSO                     | 1         | 1.01%   |
| BenQ                    | 1         | 1.01%   |
| Aosiman                 | 1         | 1.01%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP14BA 1920x1080 340x190mm 15.3-inch               | 2         | 1.98%   |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch               | 2         | 1.98%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 381x214mm 17.2-inch      | 2         | 1.98%   |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 355x199mm 16.0-inch      | 2         | 1.98%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 2         | 1.98%   |
| AOC 2250W AOC2250 1920x1080 477x268mm 21.5-inch                       | 2         | 1.98%   |
| Videoseven L27ADS IGM2700 1920x1080 598x336mm 27.0-inch               | 1         | 0.99%   |
| Sony Nvidia Defaul t Flat Panel SNY05FA 1366x768 309x174mm 14.0-inch  | 1         | 0.99%   |
| Sharp LCD Monitor SHP1516 3840x2400 336x210mm 15.6-inch               | 1         | 0.99%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch               | 1         | 0.99%   |
| Samsung Electronics S27D390 SAM0B67 1920x1080 598x336mm 27.0-inch     | 1         | 0.99%   |
| Samsung Electronics Odyssey G8 SAM7231 3440x1440 809x354mm 34.8-inch  | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SEC444E 1600x900 310x174mm 14.0-inch  | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SDC5844 1920x1080 344x194mm 15.5-inch | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SDC4181 2880x1800 302x189mm 14.0-inch | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch  | 1         | 0.99%   |
| Samsung Electronics LCD Monitor SAM0B60 1920x1080 887x500mm 40.1-inch | 1         | 0.99%   |
| Samsung Electronics C27R50x SAM0F9D 1920x1080 598x336mm 27.0-inch     | 1         | 0.99%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1         | 0.99%   |
| Philips PHL 346B1C PHL095C 3440x1440 797x334mm 34.0-inch              | 1         | 0.99%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 0.99%   |
| Medion 42FPDEUDA1 MED222E 1920x1080                                   | 1         | 0.99%   |
| LG Display LP156WH2-TLE1 LGDCF01 1366x768 344x194mm 15.5-inch         | 1         | 0.99%   |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch          | 1         | 0.99%   |
| LG Display LCD Monitor LGD05EE 2560x1440 309x174mm 14.0-inch          | 1         | 0.99%   |
| LG Display LCD Monitor LGD05CE 1920x1080 344x194mm 15.5-inch          | 1         | 0.99%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch          | 1         | 0.99%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 0.99%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 1         | 0.99%   |
| LG Display LCD Monitor LGD046B 1366x768 344x194mm 15.5-inch           | 1         | 0.99%   |
| LG Display LCD Monitor LGD040A 1920x1080 309x175mm 14.0-inch          | 1         | 0.99%   |
| LG Display LCD Monitor LGD03B8 1366x768 310x174mm 14.0-inch           | 1         | 0.99%   |
| LG Display LCD Monitor LGD03B3 1366x768 310x174mm 14.0-inch           | 1         | 0.99%   |
| LG Display LCD Monitor LGD038C 1366x768 256x144mm 11.6-inch           | 1         | 0.99%   |
| LG Display LCD Monitor LGD02EF 1366x768 310x174mm 14.0-inch           | 1         | 0.99%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch           | 1         | 0.99%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 42        | 47.19%  |
| 1366x768 (WXGA)    | 16        | 17.98%  |
| 2880x1800          | 4         | 4.49%   |
| 1600x900 (HD+)     | 4         | 4.49%   |
| 3840x2160 (4K)     | 3         | 3.37%   |
| 1920x1200 (WUXGA)  | 3         | 3.37%   |
| 3440x1440          | 2         | 2.25%   |
| 3200x1800 (QHD+)   | 2         | 2.25%   |
| 2560x1440 (QHD)    | 2         | 2.25%   |
| 1440x900 (WXGA+)   | 2         | 2.25%   |
| 3840x2400          | 1         | 1.12%   |
| 3072x1920          | 1         | 1.12%   |
| 2560x1600          | 1         | 1.12%   |
| 2520x1680          | 1         | 1.12%   |
| 2160x1440          | 1         | 1.12%   |
| 1680x1050 (WSXGA+) | 1         | 1.12%   |
| 1360x768           | 1         | 1.12%   |
| 1280x800 (WXGA)    | 1         | 1.12%   |
| 1280x1024 (SXGA)   | 1         | 1.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 33        | 33%     |
| 14      | 15        | 15%     |
| 13      | 13        | 13%     |
| 17      | 10        | 10%     |
| 16      | 7         | 7%      |
| 27      | 4         | 4%      |
| 21      | 4         | 4%      |
| 40      | 2         | 2%      |
| 34      | 2         | 2%      |
| 24      | 2         | 2%      |
| 59      | 1         | 1%      |
| 33      | 1         | 1%      |
| 28      | 1         | 1%      |
| 23      | 1         | 1%      |
| 22      | 1         | 1%      |
| 18      | 1         | 1%      |
| 11      | 1         | 1%      |
| Unknown | 1         | 1%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 59        | 59.6%   |
| 351-400     | 11        | 11.11%  |
| 201-300     | 8         | 8.08%   |
| 501-600     | 7         | 7.07%   |
| 401-500     | 6         | 6.06%   |
| 801-900     | 3         | 3.03%   |
| 701-800     | 2         | 2.02%   |
| 601-700     | 1         | 1.01%   |
| 1001-1500   | 1         | 1.01%   |
| Unknown     | 1         | 1.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 65        | 75.58%  |
| 16/10 | 16        | 18.6%   |
| 3/2   | 2         | 2.33%   |
| 21/9  | 2         | 2.33%   |
| 5/4   | 1         | 1.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 33        | 33%     |
| 81-90          | 23        | 23%     |
| 201-250        | 7         | 7%      |
| 121-130        | 7         | 7%      |
| 111-120        | 6         | 6%      |
| 71-80          | 5         | 5%      |
| 351-500        | 4         | 4%      |
| 301-350        | 4         | 4%      |
| 141-150        | 2         | 2%      |
| 131-140        | 2         | 2%      |
| 501-1000       | 2         | 2%      |
| More than 1000 | 1         | 1%      |
| 51-60          | 1         | 1%      |
| 251-300        | 1         | 1%      |
| 91-100         | 1         | 1%      |
| Unknown        | 1         | 1%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 42        | 42.86%  |
| 101-120       | 26        | 26.53%  |
| 51-100        | 11        | 11.22%  |
| 161-240       | 10        | 10.2%   |
| More than 240 | 7         | 7.14%   |
| 1-50          | 1         | 1.02%   |
| Unknown       | 1         | 1.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 66        | 75.86%  |
| 2     | 16        | 18.39%  |
| 0     | 3         | 3.45%   |
| 3     | 2         | 2.3%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 59        | 43.07%  |
| Realtek Semiconductor           | 36        | 26.28%  |
| Qualcomm Atheros                | 15        | 10.95%  |
| Broadcom                        | 9         | 6.57%   |
| Sierra Wireless                 | 3         | 2.19%   |
| MediaTek                        | 3         | 2.19%   |
| Marvell Technology Group        | 3         | 2.19%   |
| DisplayLink                     | 2         | 1.46%   |
| Shenzhen Goodix Technology      | 1         | 0.73%   |
| Qualcomm Atheros Communications | 1         | 0.73%   |
| Lenovo                          | 1         | 0.73%   |
| JMicron Technology              | 1         | 0.73%   |
| Huawei Technologies             | 1         | 0.73%   |
| Broadcom Limited                | 1         | 0.73%   |
| ASIX Electronics                | 1         | 0.73%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 25        | 15.15%  |
| Intel Wi-Fi 6 AX200                                                            | 9         | 5.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 3.03%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 5         | 3.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 4         | 2.42%   |
| Intel Wireless 8260                                                            | 4         | 2.42%   |
| Intel Wireless 7260                                                            | 4         | 2.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4         | 2.42%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 3         | 1.82%   |
| Intel Wireless 8265 / 8275                                                     | 3         | 1.82%   |
| Intel Wireless 3160                                                            | 3         | 1.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 3         | 1.82%   |
| Intel Alder Lake-S PCH CNVi WiFi                                               | 3         | 1.82%   |
| Sierra Wireless EM7305 Modem                                                   | 2         | 1.21%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 2         | 1.21%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 1.21%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2         | 1.21%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 2         | 1.21%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 2         | 1.21%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                  | 2         | 1.21%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.21%   |
| Intel Wireless-AC 9260                                                         | 2         | 1.21%   |
| Intel Wireless 3165                                                            | 2         | 1.21%   |
| Intel Wi-Fi 6 AX201                                                            | 2         | 1.21%   |
| Intel Tiger Lake PCH CNVi WiFi                                                 | 2         | 1.21%   |
| Intel Ethernet Connection I219-V                                               | 2         | 1.21%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 1.21%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 1.21%   |
| Intel Ethernet Connection (17) I219-LM                                         | 2         | 1.21%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 2         | 1.21%   |
| Intel Centrino Advanced-N 6235                                                 | 2         | 1.21%   |
| DisplayLink Dell D3100 Docking Station                                         | 2         | 1.21%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 2         | 1.21%   |
| Sierra Wireless EM7455                                                         | 1         | 0.61%   |
| Shenzhen Goodix Unknow device                                                  | 1         | 0.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 1         | 0.61%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.61%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 1         | 0.61%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 57        | 63.33%  |
| Qualcomm Atheros                | 13        | 14.44%  |
| Realtek Semiconductor           | 6         | 6.67%   |
| Broadcom                        | 6         | 6.67%   |
| Sierra Wireless                 | 3         | 3.33%   |
| MediaTek                        | 3         | 3.33%   |
| Qualcomm Atheros Communications | 1         | 1.11%   |
| Broadcom Limited                | 1         | 1.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 9         | 10%     |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 5         | 5.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 4         | 4.44%   |
| Intel Wireless 8260                                            | 4         | 4.44%   |
| Intel Wireless 7260                                            | 4         | 4.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 3.33%   |
| Intel Wireless 8265 / 8275                                     | 3         | 3.33%   |
| Intel Wireless 3160                                            | 3         | 3.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 3.33%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 3         | 3.33%   |
| Sierra Wireless EM7305 Modem                                   | 2         | 2.22%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 2.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 2         | 2.22%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 2.22%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 2.22%   |
| Intel Wireless-AC 9260                                         | 2         | 2.22%   |
| Intel Wireless 3165                                            | 2         | 2.22%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 2.22%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 2.22%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 2.22%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 2.22%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 2.22%   |
| Sierra Wireless EM7455                                         | 1         | 1.11%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 1.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 1.11%   |
| Qualcomm Atheros AR9271 802.11n                                | 1         | 1.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 1.11%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 1.11%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 1.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.11%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter            | 1         | 1.11%   |
| Intel WiMAX/WiFi Link 5150                                     | 1         | 1.11%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 1.11%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 1         | 1.11%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 1         | 1.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 1.11%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 1.11%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 1         | 1.11%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 1.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 1         | 1.11%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 33        | 47.14%  |
| Intel                    | 21        | 30%     |
| Qualcomm Atheros         | 4         | 5.71%   |
| Broadcom                 | 4         | 5.71%   |
| Marvell Technology Group | 3         | 4.29%   |
| DisplayLink              | 2         | 2.86%   |
| Lenovo                   | 1         | 1.43%   |
| JMicron Technology       | 1         | 1.43%   |
| ASIX Electronics         | 1         | 1.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 25        | 34.72%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 6.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4         | 5.56%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 2.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2         | 2.78%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 2.78%   |
| Intel Ethernet Connection I219-V                                               | 2         | 2.78%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 2.78%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 2.78%   |
| Intel Ethernet Connection (17) I219-LM                                         | 2         | 2.78%   |
| DisplayLink Dell D3100 Docking Station                                         | 2         | 2.78%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 1.39%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 1.39%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 1.39%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 1.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 1.39%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 1.39%   |
| Lenovo ThinkPad Lan                                                            | 1         | 1.39%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 1.39%   |
| Intel WiMAX Connection 2400m                                                   | 1         | 1.39%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 1.39%   |
| Intel Ethernet Connection I217-V                                               | 1         | 1.39%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 1.39%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 1.39%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 1.39%   |
| Intel Ethernet Connection (17) I219-V                                          | 1         | 1.39%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 1.39%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 1.39%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 1         | 1.39%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 1.39%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 1         | 1.39%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 1         | 1.39%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 1.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 85        | 55.56%  |
| Ethernet | 65        | 42.48%  |
| Unknown  | 2         | 1.31%   |
| Modem    | 1         | 0.65%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 73        | 78.49%  |
| Ethernet | 20        | 21.51%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 59        | 69.41%  |
| 1     | 24        | 28.24%  |
| 3     | 2         | 2.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 64        | 74.42%  |
| Yes  | 22        | 25.58%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 50        | 67.57%  |
| Foxconn / Hon Hai               | 6         | 8.11%   |
| Qualcomm Atheros Communications | 4         | 5.41%   |
| Realtek                         | 3         | 4.05%   |
| Lite-On Technology              | 2         | 2.7%    |
| IMC Networks                    | 2         | 2.7%    |
| Hewlett-Packard                 | 2         | 2.7%    |
| Apple                           | 2         | 2.7%    |
| Toshiba                         | 1         | 1.35%   |
| Realtek Semiconductor           | 1         | 1.35%   |
| Micro Star International        | 1         | 1.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 15        | 20.27%  |
| Intel AX200 Bluetooth                                                               | 9         | 12.16%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 8         | 10.81%  |
| Intel AX201 Bluetooth                                                               | 6         | 8.11%   |
| Intel Bluetooth Device                                                              | 5         | 6.76%   |
| Realtek Bluetooth Radio                                                             | 3         | 4.05%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 4.05%   |
| Lite-On Bluetooth Device                                                            | 2         | 2.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 2.7%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 2.7%    |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 2.7%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 2.7%    |
| Toshiba Bluetooth Device                                                            | 1         | 1.35%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.35%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.35%   |
| Micro Star International Motorola Bluetooth 2.1+EDR Device                          | 1         | 1.35%   |
| Intel AX210 Bluetooth                                                               | 1         | 1.35%   |
| IMC Networks Wireless_Device                                                        | 1         | 1.35%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.35%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 1.35%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.35%   |
| Foxconn / Hon Hai BT                                                                | 1         | 1.35%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 1.35%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 1         | 1.35%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 1.35%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 1.35%   |
| Apple Bluetooth Host Controller                                                     | 1         | 1.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel           | 72        | 69.9%   |
| AMD             | 15        | 14.56%  |
| Nvidia          | 10        | 9.71%   |
| Hewlett-Packard | 2         | 1.94%   |
| Logitech        | 1         | 0.97%   |
| Lenovo          | 1         | 0.97%   |
| Bose            | 1         | 0.97%   |
| Apple           | 1         | 0.97%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Renoir Radeon High Definition Audio Controller                         | 11        | 8.53%   |
| AMD Family 17h/19h HD Audio Controller                                     | 11        | 8.53%   |
| Intel Sunrise Point-LP HD Audio                                            | 9         | 6.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8         | 6.2%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8         | 6.2%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 7         | 5.43%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 4.65%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 3.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 3.88%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 3.1%    |
| Intel 8 Series HD Audio Controller                                         | 4         | 3.1%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 3.1%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 3.1%    |
| Nvidia Audio device                                                        | 3         | 2.33%   |
| Intel Alder Lake-S HD Audio Controller                                     | 3         | 2.33%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.55%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 1.55%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 1.55%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.55%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.55%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 1.55%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 1.55%   |
| Hewlett-Packard USB Audio                                                  | 2         | 1.55%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.78%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.78%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.78%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 0.78%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 0.78%   |
| Logitech Headset H390                                                      | 1         | 0.78%   |
| Lenovo ThinkPad Dock USB Audio                                             | 1         | 0.78%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 1         | 0.78%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 1         | 0.78%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 0.78%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.78%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.78%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 0.78%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 0.78%   |
| Bose Revolve SoundLink                                                     | 1         | 0.78%   |
| Apple Audio Device                                                         | 1         | 0.78%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 25        | 44.64%  |
| SK hynix            | 13        | 23.21%  |
| Micron Technology   | 6         | 10.71%  |
| Unknown             | 3         | 5.36%   |
| Crucial             | 3         | 5.36%   |
| Kingston            | 2         | 3.57%   |
| A-DATA Technology   | 2         | 3.57%   |
| Wilk                | 1         | 1.79%   |
| Timetec             | 1         | 1.79%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 4.92%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 2         | 3.28%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 3.28%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 3.28%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 3.28%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 3.28%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 3.28%   |
| Wilk RAM GR3200S464L22S/16G 16GB SODIMM DDR4 3200MT/s            | 1         | 1.64%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 1.64%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 1.64%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 1         | 1.64%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 1.64%   |
| Timetec RAM SD3-1333 8GB SODIMM DDR3 1333MT/s                    | 1         | 1.64%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s          | 1         | 1.64%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.64%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 1.64%   |
| SK hynix RAM HMCG88MEBSA092N 32GB SODIMM DDR5 4800MT/s           | 1         | 1.64%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.64%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 1.64%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.64%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 1.64%   |
| SK hynix RAM HMA81GS6MFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 1.64%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 1         | 1.64%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB Row Of Chips LPDDR5 6400MT/s | 1         | 1.64%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 1.64%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.64%   |
| Samsung RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 1.64%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                  | 1         | 1.64%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 1         | 1.64%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 1         | 1.64%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.64%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.64%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 1         | 1.64%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 1.64%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.64%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.64%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.64%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.64%   |
| Samsung RAM M471A1G44AB0-CTD 8GB Row Of Chips DDR4 2667MT/s      | 1         | 1.64%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 1         | 1.64%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 27        | 51.92%  |
| DDR3   | 16        | 30.77%  |
| LPDDR3 | 3         | 5.77%   |
| DDR5   | 3         | 5.77%   |
| DDR2   | 2         | 3.85%   |
| LPDDR5 | 1         | 1.92%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 47        | 90.38%  |
| Row Of Chips | 5         | 9.62%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 24        | 41.38%  |
| 4096  | 14        | 24.14%  |
| 16384 | 11        | 18.97%  |
| 2048  | 5         | 8.62%   |
| 32768 | 3         | 5.17%   |
| 1024  | 1         | 1.72%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 15        | 27.27%  |
| 3200    | 12        | 21.82%  |
| 1600    | 10        | 18.18%  |
| 2400    | 4         | 7.27%   |
| 2133    | 4         | 7.27%   |
| 4800    | 3         | 5.45%   |
| Unknown | 3         | 5.45%   |
| 6400    | 1         | 1.82%   |
| 1334    | 1         | 1.82%   |
| 1333    | 1         | 1.82%   |
| 1067    | 1         | 1.82%   |

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

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 23        | 29.49%  |
| Microdia                               | 11        | 14.1%   |
| IMC Networks                           | 9         | 11.54%  |
| Bison Electronics                      | 5         | 6.41%   |
| Samsung Electronics                    | 4         | 5.13%   |
| Quanta                                 | 4         | 5.13%   |
| Ricoh                                  | 3         | 3.85%   |
| Realtek Semiconductor                  | 3         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.85%   |
| Sunplus Innovation Technology          | 2         | 2.56%   |
| Luxvisions Innotech Limited            | 2         | 2.56%   |
| Alcor Micro                            | 2         | 2.56%   |
| Syntek                                 | 1         | 1.28%   |
| Silicon Motion                         | 1         | 1.28%   |
| ShineTech                              | 1         | 1.28%   |
| Logitech                               | 1         | 1.28%   |
| DLTDC0A9II090N                         | 1         | 1.28%   |
| Apple                                  | 1         | 1.28%   |
| ALi                                    | 1         | 1.28%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                    | 5         | 6.41%   |
| IMC Networks USB2.0 HD UVC WebCam                | 5         | 6.41%   |
| Samsung Galaxy series, misc. (MTP mode)          | 4         | 5.13%   |
| IMC Networks Integrated Camera                   | 3         | 3.85%   |
| Chicony Integrated Camera                        | 3         | 3.85%   |
| Chicony HD Webcam                                | 3         | 3.85%   |
| Realtek Integrated_Webcam_HD                     | 2         | 2.56%   |
| Quanta HD User Facing                            | 2         | 2.56%   |
| Microdia Integrated_Webcam_FHD                   | 2         | 2.56%   |
| Microdia Integrated Webcam                       | 2         | 2.56%   |
| Luxvisions Innotech Limited HP HD Camera         | 2         | 2.56%   |
| Chicony Integrated Camera (1280x720@30)          | 2         | 2.56%   |
| Chicony HP HD Camera                             | 2         | 2.56%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera | 2         | 2.56%   |
| Alcor Micro USB 2.0 Camera                       | 2         | 2.56%   |
| Syntek USB2.0 Camera                             | 1         | 1.28%   |
| Sunplus HP HD Webcam [Fixed]                     | 1         | 1.28%   |
| Sunplus HD WebCam                                | 1         | 1.28%   |
| Silicon Motion Web Camera                        | 1         | 1.28%   |
| ShineTech HD Camera                              | 1         | 1.28%   |
| Ricoh USB2.0 Camera                              | 1         | 1.28%   |
| Ricoh Sony Visual Communication Camera           | 1         | 1.28%   |
| Ricoh Sony Vaio Integrated Webcam                | 1         | 1.28%   |
| Realtek HP Truevision HD                         | 1         | 1.28%   |
| Quanta HP Wide Vision HD Camera                  | 1         | 1.28%   |
| Quanta HP Webcam                                 | 1         | 1.28%   |
| Microdia Webcam Vitade AF                        | 1         | 1.28%   |
| Microdia Webcam                                  | 1         | 1.28%   |
| Logitech HD Pro Webcam C920                      | 1         | 1.28%   |
| IMC Networks ov9734_azurewave_camera             | 1         | 1.28%   |
| DLTDC0A9II090N HP 5MP Camera                     | 1         | 1.28%   |
| Chicony USB2.0 VGA UVC WebCam                    | 1         | 1.28%   |
| Chicony USB2.0 HD UVC WebCam                     | 1         | 1.28%   |
| Chicony USB 2.0 Camera                           | 1         | 1.28%   |
| Chicony TOSHIBA Web Camera - HD                  | 1         | 1.28%   |
| Chicony ThinkPad T490 Webcam                     | 1         | 1.28%   |
| Chicony Integrated HP HD Webcam                  | 1         | 1.28%   |
| Chicony HP Wide Vision HD Camera                 | 1         | 1.28%   |
| Chicony HP Truevision HD                         | 1         | 1.28%   |
| Chicony HD WebCam (Asus N-series)                | 1         | 1.28%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 9         | 40.91%  |
| Shenzhen Goodix Technology | 5         | 22.73%  |
| Validity Sensors           | 4         | 18.18%  |
| Upek                       | 1         | 4.55%   |
| LighTuning Technology      | 1         | 4.55%   |
| Elan Microelectronics      | 1         | 4.55%   |
| AuthenTec                  | 1         | 4.55%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 4         | 18.18%  |
| Shenzhen Goodix Fingerprint Reader                       | 3         | 13.64%  |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 9.09%   |
| Shenzhen Goodix  Fingerprint Device                      | 2         | 9.09%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor        | 1         | 4.55%   |
| Validity Sensors VFS495 Fingerprint Reader               | 1         | 4.55%   |
| Validity Sensors VFS451 Fingerprint Reader               | 1         | 4.55%   |
| Validity Sensors Synaptics WBDI                          | 1         | 4.55%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 1         | 4.55%   |
| Synaptics UWP WBDI                                       | 1         | 4.55%   |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 1         | 4.55%   |
| Synaptics Fingerprint reader [HP G6]                     | 1         | 4.55%   |
| LighTuning ES603 Swipe Fingerprint Sensor                | 1         | 4.55%   |
| Elan ELAN:Fingerprint                                    | 1         | 4.55%   |
| AuthenTec Fingerprint Sensor                             | 1         | 4.55%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 4         | 40%     |
| Gemalto (was Gemplus) | 3         | 30%     |
| Broadcom              | 3         | 30%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 40%     |
| Gemalto (was Gemplus) Prox SU USB PC Link Reader                             | 2         | 20%     |
| Broadcom 58200                                                               | 2         | 20%     |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 45        | 51.14%  |
| 1     | 28        | 31.82%  |
| 2     | 13        | 14.77%  |
| 3     | 2         | 2.27%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 22        | 37.93%  |
| Graphics card            | 12        | 20.69%  |
| Chipcard                 | 6         | 10.34%  |
| Network                  | 3         | 5.17%   |
| Net/wireless             | 3         | 5.17%   |
| Multimedia controller    | 3         | 5.17%   |
| Card reader              | 3         | 5.17%   |
| Communication controller | 2         | 3.45%   |
| Sound                    | 1         | 1.72%   |
| Net/ethernet             | 1         | 1.72%   |
| Camera                   | 1         | 1.72%   |
| Bluetooth                | 1         | 1.72%   |

