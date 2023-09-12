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

Total: 114

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 12        | 13.33%  |
| Ubuntu 22.04                 | 6         | 6.67%   |
| Ubuntu 18.04                 | 5         | 5.56%   |
| openSUSE Tumbleweed-XXXXXXXX | 4         | 4.44%   |
| Linux Mint 20.3              | 4         | 4.44%   |
| Ubuntu 21.04                 | 3         | 3.33%   |
| Pop!_OS 21.04                | 3         | 3.33%   |
| OpenMandriva 4.2             | 3         | 3.33%   |
| Xubuntu 20.04                | 2         | 2.22%   |
| Ubuntu 20.10                 | 2         | 2.22%   |
| Pop!_OS 22.04                | 2         | 2.22%   |
| OpenMandriva 4.90            | 2         | 2.22%   |
| OpenMandriva 23.03           | 2         | 2.22%   |
| Fedora 37                    | 2         | 2.22%   |
| Xubuntu 18.04                | 1         | 1.11%   |
| Ubuntu MATE 21.10            | 1         | 1.11%   |
| Ubuntu MATE 20.04            | 1         | 1.11%   |
| Ubuntu 18.10                 | 1         | 1.11%   |
| RHEL 8                       | 1         | 1.11%   |
| Pop!_OS 21.10                | 1         | 1.11%   |
| Pop!_OS 20.10                | 1         | 1.11%   |
| Pop!_OS 20.04                | 1         | 1.11%   |
| Parrot 5.3                   | 1         | 1.11%   |
| Parrot 5.1                   | 1         | 1.11%   |
| openSUSE Leap-15.1           | 1         | 1.11%   |
| OpenMandriva 4.3             | 1         | 1.11%   |
| Manjaro 21.2.6               | 1         | 1.11%   |
| Manjaro 19.0.2               | 1         | 1.11%   |
| Lubuntu 20.04                | 1         | 1.11%   |
| LMDE 4                       | 1         | 1.11%   |
| Linux Mint 21.2              | 1         | 1.11%   |
| Linux Mint 20.2              | 1         | 1.11%   |
| Linux Mint 19.2              | 1         | 1.11%   |
| Kubuntu 23.04                | 1         | 1.11%   |
| Kubuntu 22.04                | 1         | 1.11%   |
| Kubuntu 18.04                | 1         | 1.11%   |
| KDE neon 22.04               | 1         | 1.11%   |
| Kali 2022.4                  | 1         | 1.11%   |
| Garuda Linux Soaring         | 1         | 1.11%   |
| Fedora 36                    | 1         | 1.11%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 27        | 32.14%  |
| OpenMandriva | 8         | 9.52%   |
| Pop!_OS      | 7         | 8.33%   |
| Linux Mint   | 6         | 7.14%   |
| openSUSE     | 5         | 5.95%   |
| Fedora       | 4         | 4.76%   |
| Xubuntu      | 3         | 3.57%   |
| Kubuntu      | 3         | 3.57%   |
| Ubuntu MATE  | 2         | 2.38%   |
| Parrot       | 2         | 2.38%   |
| Manjaro      | 2         | 2.38%   |
| Endless      | 2         | 2.38%   |
| Debian       | 2         | 2.38%   |
| RHEL         | 1         | 1.19%   |
| Lubuntu      | 1         | 1.19%   |
| LMDE         | 1         | 1.19%   |
| KDE neon     | 1         | 1.19%   |
| Kali         | 1         | 1.19%   |
| Garuda Linux | 1         | 1.19%   |
| Elementary   | 1         | 1.19%   |
| Clear Linux  | 1         | 1.19%   |
| BlackPanther | 1         | 1.19%   |
| ArcoLinux    | 1         | 1.19%   |
| Arch         | 1         | 1.19%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.11.0-27-generic        | 3         | 3.26%   |
| 5.10.14-desktop-1omv4002 | 3         | 3.26%   |
| 6.2.6-desktop-1omv2390   | 2         | 2.17%   |
| 6.2.14-200.fc37.x86_64   | 2         | 2.17%   |
| 5.8.0-59-generic         | 2         | 2.17%   |
| 5.4.0-96-generic         | 2         | 2.17%   |
| 5.4.0-122-generic        | 2         | 2.17%   |
| 5.19.0-35-generic        | 2         | 2.17%   |
| 5.18.12-desktop-3omv4090 | 2         | 2.17%   |
| 5.11.0-34-generic        | 2         | 2.17%   |
| 5.11.0-17-generic        | 2         | 2.17%   |
| 5.0.0-23-generic         | 2         | 2.17%   |
| 6.4.3-1-default          | 1         | 1.09%   |
| 6.4.3-060403-generic     | 1         | 1.09%   |
| 6.2.0-26-generic         | 1         | 1.09%   |
| 6.1.8-060108-generic     | 1         | 1.09%   |
| 6.1.0-1parrot1-amd64     | 1         | 1.09%   |
| 6.0.6-76060006-generic   | 1         | 1.09%   |
| 6.0.0-kali3-amd64        | 1         | 1.09%   |
| 5.8.11-050811-generic    | 1         | 1.09%   |
| 5.8.0-63-generic         | 1         | 1.09%   |
| 5.8.0-55-generic         | 1         | 1.09%   |
| 5.8.0-43-generic         | 1         | 1.09%   |
| 5.8.0-31-generic         | 1         | 1.09%   |
| 5.8.0-20-generic         | 1         | 1.09%   |
| 5.8.0-14-generic         | 1         | 1.09%   |
| 5.7.6-201.fc32.x86_64    | 1         | 1.09%   |
| 5.7.1-1-default          | 1         | 1.09%   |
| 5.7.0-3-amd64            | 1         | 1.09%   |
| 5.7.0-050700-generic     | 1         | 1.09%   |
| 5.6.3-935.native         | 1         | 1.09%   |
| 5.5.8-1-MANJARO          | 1         | 1.09%   |
| 5.4.0-84-generic         | 1         | 1.09%   |
| 5.4.0-73-generic         | 1         | 1.09%   |
| 5.4.0-52-generic         | 1         | 1.09%   |
| 5.4.0-47-generic         | 1         | 1.09%   |
| 5.4.0-42-generic         | 1         | 1.09%   |
| 5.4.0-37-generic         | 1         | 1.09%   |
| 5.3.0-51-generic         | 1         | 1.09%   |
| 5.3.0-46-generic         | 1         | 1.09%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 12        | 13.33%  |
| 5.4.0   | 9         | 10%     |
| 5.8.0   | 8         | 8.89%   |
| 5.19.0  | 5         | 5.56%   |
| 5.15.0  | 5         | 5.56%   |
| 5.13.0  | 4         | 4.44%   |
| 5.3.0   | 3         | 3.33%   |
| 5.10.14 | 3         | 3.33%   |
| 4.15.0  | 3         | 3.33%   |
| 6.4.3   | 2         | 2.22%   |
| 6.2.6   | 2         | 2.22%   |
| 6.2.14  | 2         | 2.22%   |
| 5.7.0   | 2         | 2.22%   |
| 5.18.12 | 2         | 2.22%   |
| 5.0.0   | 2         | 2.22%   |
| 4.18.0  | 2         | 2.22%   |
| 6.2.0   | 1         | 1.11%   |
| 6.1.8   | 1         | 1.11%   |
| 6.1.0   | 1         | 1.11%   |
| 6.0.6   | 1         | 1.11%   |
| 6.0.0   | 1         | 1.11%   |
| 5.8.11  | 1         | 1.11%   |
| 5.7.6   | 1         | 1.11%   |
| 5.7.1   | 1         | 1.11%   |
| 5.6.3   | 1         | 1.11%   |
| 5.5.8   | 1         | 1.11%   |
| 5.18.5  | 1         | 1.11%   |
| 5.18.0  | 1         | 1.11%   |
| 5.16.7  | 1         | 1.11%   |
| 5.16.2  | 1         | 1.11%   |
| 5.16.11 | 1         | 1.11%   |
| 5.15.4  | 1         | 1.11%   |
| 5.15.32 | 1         | 1.11%   |
| 5.14.0  | 1         | 1.11%   |
| 5.12.13 | 1         | 1.11%   |
| 5.10.26 | 1         | 1.11%   |
| 5.10.0  | 1         | 1.11%   |
| 4.19.0  | 1         | 1.11%   |
| 4.18.16 | 1         | 1.11%   |
| 4.12.14 | 1         | 1.11%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 12        | 13.33%  |
| 5.8     | 9         | 10%     |
| 5.4     | 9         | 10%     |
| 5.15    | 7         | 7.78%   |
| 6.2     | 5         | 5.56%   |
| 5.19    | 5         | 5.56%   |
| 5.10    | 5         | 5.56%   |
| 5.7     | 4         | 4.44%   |
| 5.18    | 4         | 4.44%   |
| 5.13    | 4         | 4.44%   |
| 5.3     | 3         | 3.33%   |
| 5.16    | 3         | 3.33%   |
| 4.18    | 3         | 3.33%   |
| 4.15    | 3         | 3.33%   |
| 6.4     | 2         | 2.22%   |
| 6.1     | 2         | 2.22%   |
| 6.0     | 2         | 2.22%   |
| 5.0     | 2         | 2.22%   |
| 5.6     | 1         | 1.11%   |
| 5.5     | 1         | 1.11%   |
| 5.14    | 1         | 1.11%   |
| 5.12    | 1         | 1.11%   |
| 4.19    | 1         | 1.11%   |
| 4.12    | 1         | 1.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 80        | 98.77%  |
| i686   | 1         | 1.23%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 36        | 43.37%  |
| KDE5            | 15        | 18.07%  |
| X-Cinnamon      | 7         | 8.43%   |
| XFCE            | 6         | 7.23%   |
| Unknown         | 6         | 7.23%   |
| MATE            | 4         | 4.82%   |
| KDE             | 3         | 3.61%   |
| i3              | 2         | 2.41%   |
| Pantheon        | 1         | 1.2%    |
| LXQt            | 1         | 1.2%    |
| GNOME Flashback | 1         | 1.2%    |
| Cinnamon        | 1         | 1.2%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 66        | 78.57%  |
| Wayland | 14        | 16.67%  |
| Unknown | 4         | 4.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 38        | 44.19%  |
| GDM     | 14        | 16.28%  |
| LightDM | 13        | 15.12%  |
| SDDM    | 11        | 12.79%  |
| GDM3    | 7         | 8.14%   |
| TDM     | 3         | 3.49%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 38        | 44.71%  |
| en_GB   | 8         | 9.41%   |
| Unknown | 7         | 8.24%   |
| de_DE   | 6         | 7.06%   |
| de_LU   | 5         | 5.88%   |
| fr_LU   | 4         | 4.71%   |
| fr_FR   | 4         | 4.71%   |
| nl_NL   | 2         | 2.35%   |
| unm_US  | 1         | 1.18%   |
| pt_PT   | 1         | 1.18%   |
| pt_BR   | 1         | 1.18%   |
| POSIX   | 1         | 1.18%   |
| it_IT   | 1         | 1.18%   |
| hr_HR   | 1         | 1.18%   |
| fr_CH   | 1         | 1.18%   |
| es_ES   | 1         | 1.18%   |
| en_IE   | 1         | 1.18%   |
| en_AU   | 1         | 1.18%   |
| C       | 1         | 1.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 49        | 59.04%  |
| BIOS | 34        | 40.96%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 61        | 74.39%  |
| Btrfs   | 10        | 12.2%   |
| Overlay | 8         | 9.76%   |
| Xfs     | 2         | 2.44%   |
| Unknown | 1         | 1.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 38        | 46.34%  |
| Unknown | 37        | 45.12%  |
| MBR     | 7         | 8.54%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 75        | 91.46%  |
| Yes       | 7         | 8.54%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 60        | 74.07%  |
| Yes       | 21        | 25.93%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 14        | 17.28%  |
| Lenovo           | 12        | 14.81%  |
| Dell             | 11        | 13.58%  |
| ASUSTek Computer | 7         | 8.64%   |
| Sony             | 5         | 6.17%   |
| Acer             | 5         | 6.17%   |
| HUAWEI           | 4         | 4.94%   |
| Apple            | 4         | 4.94%   |
| Wortmann AG      | 3         | 3.7%    |
| win element      | 2         | 2.47%   |
| Medion           | 2         | 2.47%   |
| Fujitsu          | 2         | 2.47%   |
| Clevo            | 2         | 2.47%   |
| YJKC             | 1         | 1.23%   |
| TUXEDO           | 1         | 1.23%   |
| Toshiba          | 1         | 1.23%   |
| Timi             | 1         | 1.23%   |
| SLIMBOOK         | 1         | 1.23%   |
| Packard Bell     | 1         | 1.23%   |
| Notebook         | 1         | 1.23%   |
| MSI              | 1         | 1.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                             | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| win element MoreFine S500+                       | 2         | 2.47%   |
| Dell Precision M3800                             | 2         | 2.47%   |
| Dell Precision 7670                              | 2         | 2.47%   |
| YJKC vBook                                       | 1         | 1.23%   |
| Wortmann AG TERRA_MOBILE_1749                    | 1         | 1.23%   |
| Wortmann AG TERRA_MOBILE_1541H                   | 1         | 1.23%   |
| Wortmann AG MS-1727                              | 1         | 1.23%   |
| TUXEDO Pulse 14 Gen1                             | 1         | 1.23%   |
| Toshiba Satellite C55-A-1N0                      | 1         | 1.23%   |
| Timi RedmiBook 14 II                             | 1         | 1.23%   |
| Sony VPCP11S1R                                   | 1         | 1.23%   |
| Sony VPCEB2E1E                                   | 1         | 1.23%   |
| Sony VPCCA4E1E                                   | 1         | 1.23%   |
| Sony VGN-NS30E_S                                 | 1         | 1.23%   |
| Sony SVF1421E2EW                                 | 1         | 1.23%   |
| SLIMBOOK EXECUTIVE-14                            | 1         | 1.23%   |
| Packard Bell EasyNote TJ65                       | 1         | 1.23%   |
| Notebook NV4XMB,ME,MZ                            | 1         | 1.23%   |
| MSI GF72 8RD                                     | 1         | 1.23%   |
| Medion P6685 MD61138                             | 1         | 1.23%   |
| Medion E4254 MD62100                             | 1         | 1.23%   |
| Lenovo ThinkPad X1 Carbon 7th 20QDCTO1WW         | 1         | 1.23%   |
| Lenovo ThinkPad T590 20N4CTO1WW                  | 1         | 1.23%   |
| Lenovo ThinkPad T490 20N3S5DV0S                  | 1         | 1.23%   |
| Lenovo ThinkPad T480s 20L7001PFR                 | 1         | 1.23%   |
| Lenovo ThinkPad T470s W10DG 20JTS0R800           | 1         | 1.23%   |
| Lenovo ThinkPad T440p 20AWS24B00                 | 1         | 1.23%   |
| Lenovo ThinkPad P1 Gen 2 20QTCTO1WW              | 1         | 1.23%   |
| Lenovo ThinkPad L15 Gen 1 20U8S0AH00             | 1         | 1.23%   |
| Lenovo ThinkPad L15 Gen 1 20U7S05B00             | 1         | 1.23%   |
| Lenovo ThinkPad L14 Gen 2a 20X6S15A00            | 1         | 1.23%   |
| Lenovo IdeaPad 330-15ICH 81FK                    | 1         | 1.23%   |
| Lenovo G50-70 20351                              | 1         | 1.23%   |
| HUAWEI KLVL-WXXW                                 | 1         | 1.23%   |
| HUAWEI HVY-WXX9                                  | 1         | 1.23%   |
| HUAWEI HLYL-WXX9                                 | 1         | 1.23%   |
| HUAWEI CREM-WXX9                                 | 1         | 1.23%   |
| HP ZBook Fury 16 G9 Mobile Workstation PC        | 1         | 1.23%   |
| HP ZBook Fury 15.6 inch G8 Mobile Workstation PC | 1         | 1.23%   |
| HP Spectre Laptop 13-af0xx                       | 1         | 1.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 10        | 12.35%  |
| Dell Precision        | 7         | 8.64%   |
| HP EliteBook          | 4         | 4.94%   |
| Acer Aspire           | 4         | 4.94%   |
| ASUS VivoBook         | 3         | 3.7%    |
| Wortmann AG TERRA     | 2         | 2.47%   |
| win element MoreFine  | 2         | 2.47%   |
| HP ZBook              | 2         | 2.47%   |
| HP ProBook            | 2         | 2.47%   |
| HP ENVY               | 2         | 2.47%   |
| Dell XPS              | 2         | 2.47%   |
| YJKC vBook            | 1         | 1.23%   |
| Wortmann AG MS-1727   | 1         | 1.23%   |
| TUXEDO Pulse          | 1         | 1.23%   |
| Toshiba Satellite     | 1         | 1.23%   |
| Timi RedmiBook        | 1         | 1.23%   |
| Sony VPCP11S1R        | 1         | 1.23%   |
| Sony VPCEB2E1E        | 1         | 1.23%   |
| Sony VPCCA4E1E        | 1         | 1.23%   |
| Sony VGN-NS30E        | 1         | 1.23%   |
| Sony SVF1421E2EW      | 1         | 1.23%   |
| SLIMBOOK EXECUTIVE-14 | 1         | 1.23%   |
| Packard Bell EasyNote | 1         | 1.23%   |
| Notebook NV4XMB       | 1         | 1.23%   |
| MSI GF72              | 1         | 1.23%   |
| Medion P6685          | 1         | 1.23%   |
| Medion E4254          | 1         | 1.23%   |
| Lenovo IdeaPad        | 1         | 1.23%   |
| Lenovo G50-70         | 1         | 1.23%   |
| HUAWEI KLVL-WXXW      | 1         | 1.23%   |
| HUAWEI HVY-WXX9       | 1         | 1.23%   |
| HUAWEI HLYL-WXX9      | 1         | 1.23%   |
| HUAWEI CREM-WXX9      | 1         | 1.23%   |
| HP Spectre            | 1         | 1.23%   |
| HP Pavilion           | 1         | 1.23%   |
| HP OMEN               | 1         | 1.23%   |
| HP 255                | 1         | 1.23%   |
| Fujitsu STYLISTIC     | 1         | 1.23%   |
| Fujitsu LIFEBOOK      | 1         | 1.23%   |
| Dell Vostro           | 1         | 1.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 11        | 13.58%  |
| 2021 | 10        | 12.35%  |
| 2020 | 9         | 11.11%  |
| 2018 | 8         | 9.88%   |
| 2017 | 7         | 8.64%   |
| 2013 | 7         | 8.64%   |
| 2014 | 6         | 7.41%   |
| 2011 | 5         | 6.17%   |
| 2010 | 5         | 6.17%   |
| 2022 | 4         | 4.94%   |
| 2015 | 3         | 3.7%    |
| 2016 | 2         | 2.47%   |
| 2012 | 2         | 2.47%   |
| 2009 | 2         | 2.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 81        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 72        | 87.8%   |
| Enabled  | 10        | 12.2%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 81        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 20        | 24.1%   |
| 8.01-16.0   | 20        | 24.1%   |
| 4.01-8.0    | 15        | 18.07%  |
| 3.01-4.0    | 12        | 14.46%  |
| 32.01-64.0  | 8         | 9.64%   |
| 64.01-256.0 | 3         | 3.61%   |
| 2.01-3.0    | 2         | 2.41%   |
| 1.01-2.0    | 2         | 2.41%   |
| 24.01-32.0  | 1         | 1.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 27        | 31.76%  |
| 1.01-2.0   | 21        | 24.71%  |
| 4.01-8.0   | 14        | 16.47%  |
| 3.01-4.0   | 11        | 12.94%  |
| 8.01-16.0  | 7         | 8.24%   |
| 24.01-32.0 | 2         | 2.35%   |
| 16.01-24.0 | 1         | 1.18%   |
| 0.51-1.0   | 1         | 1.18%   |
| 0.01-0.5   | 1         | 1.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 60        | 74.07%  |
| 2      | 14        | 17.28%  |
| 3      | 6         | 7.41%   |
| 0      | 1         | 1.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 55        | 67.9%   |
| Yes       | 26        | 32.1%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 76.54%  |
| No        | 19        | 23.46%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 81        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 70        | 86.42%  |
| No        | 11        | 13.58%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| Luxembourg | 81        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Luxembourg        | 48        | 55.17%  |
| Strassen          | 8         | 9.2%    |
| Schifflange       | 3         | 3.45%   |
| Useldange         | 2         | 2.3%    |
| Steinfort         | 2         | 2.3%    |
| Schieren          | 2         | 2.3%    |
| Ehnen             | 2         | 2.3%    |
| Wiltz             | 1         | 1.15%   |
| Wecker            | 1         | 1.15%   |
| Vianden           | 1         | 1.15%   |
| Soleuvre          | 1         | 1.15%   |
| PerlГ©          | 1         | 1.15%   |
| Oberpallen        | 1         | 1.15%   |
| Niederanven       | 1         | 1.15%   |
| Leudelange        | 1         | 1.15%   |
| Hunsdorf          | 1         | 1.15%   |
| Ettelbruck        | 1         | 1.15%   |
| Esch-sur-Alzette  | 1         | 1.15%   |
| Echternach        | 1         | 1.15%   |
| Differdange       | 1         | 1.15%   |
| Diekirch          | 1         | 1.15%   |
| Clervaux          | 1         | 1.15%   |
| Bourscheid        | 1         | 1.15%   |
| Bettembourg       | 1         | 1.15%   |
| Bettange-sur-Mess | 1         | 1.15%   |
| Beckerich         | 1         | 1.15%   |
| Aspelt            | 1         | 1.15%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 25        | 31     | 23.81%  |
| Seagate                     | 12        | 12     | 11.43%  |
| WDC                         | 10        | 12     | 9.52%   |
| Toshiba                     | 10        | 11     | 9.52%   |
| SanDisk                     | 8         | 11     | 7.62%   |
| Kingston                    | 6         | 8      | 5.71%   |
| Crucial                     | 5         | 7      | 4.76%   |
| SK hynix                    | 4         | 4      | 3.81%   |
| Apple                       | 4         | 5      | 3.81%   |
| Intel                       | 3         | 4      | 2.86%   |
| Micron Technology           | 2         | 3      | 1.9%    |
| LITEONIT                    | 2         | 2      | 1.9%    |
| Union Memory (Shenzhen)     | 1         | 1      | 0.95%   |
| Phison Electronics          | 1         | 1      | 0.95%   |
| PHD 3.0                     | 1         | 1      | 0.95%   |
| LITEON                      | 1         | 1      | 0.95%   |
| Lenovo                      | 1         | 1      | 0.95%   |
| LaCie                       | 1         | 1      | 0.95%   |
| Kingston Technology Company | 1         | 2      | 0.95%   |
| KingDian                    | 1         | 1      | 0.95%   |
| Intenso                     | 1         | 2      | 0.95%   |
| HUAWEI                      | 1         | 1      | 0.95%   |
| Hitachi                     | 1         | 1      | 0.95%   |
| HGST                        | 1         | 1      | 0.95%   |
| FORESEE                     | 1         | 1      | 0.95%   |
| A-DATA Technology           | 1         | 1      | 0.95%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Seagate Expansion 2TB                             | 3         | 2.73%   |
| WDC WD10JPVX-22JC3T0 1TB                          | 2         | 1.82%   |
| Toshiba MQ01ABF050 500GB                          | 2         | 1.82%   |
| SanDisk SD8SN8U128G1122 128GB SSD                 | 2         | 1.82%   |
| SanDisk NVMe SSD Drive 1TB                        | 2         | 1.82%   |
| Samsung SSD 860 QVO 1TB                           | 2         | 1.82%   |
| Samsung MZVLW256HEHP-000L7 256GB                  | 2         | 1.82%   |
| LITEONIT LMT-256L9M-11 MSATA 256GB SSD            | 2         | 1.82%   |
| WDC WDS250G2B0B-00YS70 250GB SSD                  | 1         | 0.91%   |
| WDC WD3200LPCX-00VHAT0 320GB                      | 1         | 0.91%   |
| WDC WD10SPZX-17Z10T0 1TB                          | 1         | 0.91%   |
| WDC WD10SPCX-60HWST0 1TB                          | 1         | 0.91%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB              | 1         | 0.91%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB              | 1         | 0.91%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB                | 1         | 0.91%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB              | 1         | 0.91%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB      | 1         | 0.91%   |
| Toshiba NVMe SSD Drive 512GB                      | 1         | 0.91%   |
| Toshiba MQ02ABD100H 1TB                           | 1         | 0.91%   |
| Toshiba MK7575GSX 752GB                           | 1         | 0.91%   |
| Toshiba MK6459GSXP 640GB                          | 1         | 0.91%   |
| Toshiba MK2555GSX 250GB                           | 1         | 0.91%   |
| Toshiba KXG60PNV2T04 NVMe KIOXIA 2048GB           | 1         | 0.91%   |
| Toshiba KXG50ZNV512G 512GB                        | 1         | 0.91%   |
| Toshiba KXG50ZNV256G 256GB                        | 1         | 0.91%   |
| SK hynix PC801 NVMe 1TB                           | 1         | 0.91%   |
| SK hynix PC711 HFS512GDE9X073N 512GB              | 1         | 0.91%   |
| SK hynix HFS128G39TND-N210A 128GB SSD             | 1         | 0.91%   |
| SK hynix HCG8e  64GB                              | 1         | 0.91%   |
| Seagate ST950042 0ASG 500GB                       | 1         | 0.91%   |
| Seagate ST9320423AS 320GB                         | 1         | 0.91%   |
| Seagate ST750LM022 HN-M750MBB 752GB               | 1         | 0.91%   |
| Seagate ST2000LM015-2E8174 2TB                    | 1         | 0.91%   |
| Seagate ST1000LM049-2GH172 1TB                    | 1         | 0.91%   |
| Seagate ST1000LM048-2E7172 1TB                    | 1         | 0.91%   |
| Seagate ST1000LM035-1RK172 1TB                    | 1         | 0.91%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 1         | 0.91%   |
| Seagate ST1000LM014-1EJ164 1TB                    | 1         | 0.91%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB | 1         | 0.91%   |
| SanDisk SD9SN8W256G1102 256GB SSD                 | 1         | 0.91%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 12     | 42.86%  |
| Toshiba             | 6         | 7      | 21.43%  |
| WDC                 | 5         | 7      | 17.86%  |
| Samsung Electronics | 1         | 1      | 3.57%   |
| PHD 3.0             | 1         | 1      | 3.57%   |
| Hitachi             | 1         | 1      | 3.57%   |
| HGST                | 1         | 1      | 3.57%   |
| Apple               | 1         | 1      | 3.57%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 17     | 32.43%  |
| SanDisk             | 6         | 7      | 16.22%  |
| Crucial             | 4         | 6      | 10.81%  |
| Kingston            | 3         | 5      | 8.11%   |
| Micron Technology   | 2         | 3      | 5.41%   |
| LITEONIT            | 2         | 2      | 5.41%   |
| WDC                 | 1         | 1      | 2.7%    |
| SK hynix            | 1         | 1      | 2.7%    |
| LITEON              | 1         | 1      | 2.7%    |
| Lenovo              | 1         | 1      | 2.7%    |
| KingDian            | 1         | 1      | 2.7%    |
| Intenso             | 1         | 2      | 2.7%    |
| FORESEE             | 1         | 1      | 2.7%    |
| Apple               | 1         | 1      | 2.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 38        | 43     | 38%     |
| SSD     | 31        | 49     | 31%     |
| HDD     | 28        | 31     | 28%     |
| Unknown | 2         | 2      | 2%      |
| MMC     | 1         | 1      | 1%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 48        | 73     | 50.53%  |
| NVMe | 38        | 43     | 40%     |
| SAS  | 8         | 9      | 8.42%   |
| MMC  | 1         | 1      | 1.05%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 35        | 48     | 55.56%  |
| 0.51-1.0   | 22        | 26     | 34.92%  |
| 1.01-2.0   | 6         | 6      | 9.52%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 24        | 28.24%  |
| 101-250        | 16        | 18.82%  |
| 501-1000       | 14        | 16.47%  |
| 1001-2000      | 8         | 9.41%   |
| Unknown        | 6         | 7.06%   |
| More than 3000 | 4         | 4.71%   |
| 1-20           | 4         | 4.71%   |
| 51-100         | 4         | 4.71%   |
| 2001-3000      | 3         | 3.53%   |
| 21-50          | 2         | 2.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 26        | 30.23%  |
| 21-50     | 14        | 16.28%  |
| 101-250   | 12        | 13.95%  |
| 251-500   | 9         | 10.47%  |
| 51-100    | 8         | 9.3%    |
| 501-1000  | 7         | 8.14%   |
| Unknown   | 6         | 6.98%   |
| 2001-3000 | 3         | 3.49%   |
| 1001-2000 | 1         | 1.16%   |

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
| Works    | 42        | 55     | 48.28%  |
| Detected | 40        | 66     | 45.98%  |
| Malfunc  | 5         | 5      | 5.75%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 54        | 55.1%   |
| Samsung Electronics          | 12        | 12.24%  |
| SanDisk                      | 8         | 8.16%   |
| AMD                          | 7         | 7.14%   |
| Toshiba America Info Systems | 4         | 4.08%   |
| Kingston Technology Company  | 4         | 4.08%   |
| SK hynix                     | 2         | 2.04%   |
| Apple                        | 2         | 2.04%   |
| Union Memory (Shenzhen)      | 1         | 1.02%   |
| Phison Electronics           | 1         | 1.02%   |
| Micron/Crucial Technology    | 1         | 1.02%   |
| Marvell Technology Group     | 1         | 1.02%   |
| ADATA Technology             | 1         | 1.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 8         | 7.92%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 7         | 6.93%   |
| Intel Volume Management Device NVMe RAID Controller                            | 6         | 5.94%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 5         | 4.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 4.95%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 4.95%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 3.96%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 3.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 3.96%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 2.97%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 2.97%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 2.97%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 2.97%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 1.98%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 2         | 1.98%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 1.98%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 1.98%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 1.98%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.98%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 1.98%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.98%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 1.98%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 NVMe SSD 128GB                          | 1         | 0.99%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 1         | 0.99%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 1         | 0.99%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 0.99%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 0.99%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1         | 0.99%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 1         | 0.99%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 0.99%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 0.99%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 1         | 0.99%   |
| Kingston Company KC2000/KC2500 NVMe SSD                                        | 1         | 0.99%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                     | 1         | 0.99%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 0.99%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 1         | 0.99%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 1         | 0.99%   |
| Intel SSD 660P Series                                                          | 1         | 0.99%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 0.99%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 0.99%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 52        | 52%     |
| NVMe | 38        | 38%     |
| RAID | 9         | 9%      |
| IDE  | 1         | 1%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 68        | 83.95%  |
| AMD    | 13        | 16.05%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz           | 3         | 3.7%    |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 3.7%    |
| Intel Core i5-8265U CPU @ 1.60GHz           | 3         | 3.7%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 3         | 3.7%    |
| Intel Core i7-9750H CPU @ 2.60GHz           | 2         | 2.47%   |
| Intel Core i7-4702HQ CPU @ 2.20GHz          | 2         | 2.47%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 2         | 2.47%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 2         | 2.47%   |
| AMD Ryzen 9 5900HX with Radeon Graphics     | 2         | 2.47%   |
| AMD Ryzen 5 4600H with Radeon Graphics      | 2         | 2.47%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 1.23%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 1.23%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 1         | 1.23%   |
| Intel Pentium CPU P6000 @ 1.87GHz           | 1         | 1.23%   |
| Intel Pentium CPU 987 @ 1.50GHz             | 1         | 1.23%   |
| Intel Core m5-6Y54 CPU @ 1.10GHz            | 1         | 1.23%   |
| Intel Core i9-9880H CPU @ 2.30GHz           | 1         | 1.23%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 1.23%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 1.23%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 1.23%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 1.23%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 1.23%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 1.23%   |
| Intel Core i7-4712MQ CPU @ 2.30GHz          | 1         | 1.23%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz          | 1         | 1.23%   |
| Intel Core i7-3940XM CPU @ 3.00GHz          | 1         | 1.23%   |
| Intel Core i7-3840QM CPU @ 2.80GHz          | 1         | 1.23%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 1.23%   |
| Intel Core i5-8257U CPU @ 1.40GHz           | 1         | 1.23%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.23%   |
| Intel Core i5-7360U CPU @ 2.30GHz           | 1         | 1.23%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 1.23%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz          | 1         | 1.23%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1         | 1.23%   |
| Intel Core i5-4330M CPU @ 2.80GHz           | 1         | 1.23%   |
| Intel Core i5-4250U CPU @ 1.30GHz           | 1         | 1.23%   |
| Intel Core i5-4210M CPU @ 2.60GHz           | 1         | 1.23%   |
| Intel Core i5-4200M CPU @ 2.50GHz           | 1         | 1.23%   |
| Intel Core i5-3427U CPU @ 1.80GHz           | 1         | 1.23%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 1         | 1.23%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 21        | 25.93%  |
| Intel Core i5           | 20        | 24.69%  |
| Other                   | 11        | 13.58%  |
| Intel Core i3           | 5         | 6.17%   |
| AMD Ryzen 5             | 4         | 4.94%   |
| Intel Celeron           | 3         | 3.7%    |
| AMD Ryzen 7             | 3         | 3.7%    |
| Intel Pentium Dual-Core | 2         | 2.47%   |
| Intel Pentium           | 2         | 2.47%   |
| AMD Ryzen 9             | 2         | 2.47%   |
| AMD Ryzen 5 PRO         | 2         | 2.47%   |
| Intel Pentium Silver    | 1         | 1.23%   |
| Intel Core m5           | 1         | 1.23%   |
| Intel Core i9           | 1         | 1.23%   |
| Intel Atom              | 1         | 1.23%   |
| AMD Ryzen 7 PRO         | 1         | 1.23%   |
| AMD E2                  | 1         | 1.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 28        | 34.57%  |
| 2      | 28        | 34.57%  |
| 6      | 10        | 12.35%  |
| 8      | 9         | 11.11%  |
| 16     | 3         | 3.7%    |
| 1      | 2         | 2.47%   |
| 14     | 1         | 1.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 81        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 69        | 85.19%  |
| 1      | 12        | 14.81%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 80        | 98.77%  |
| 32-bit         | 1         | 1.23%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 23        | 26.74%  |
| 0x306c3    | 8         | 9.3%    |
| 0x206a7    | 5         | 5.81%   |
| 0x806ea    | 4         | 4.65%   |
| 0x806c1    | 4         | 4.65%   |
| 0x40651    | 4         | 4.65%   |
| 0x806eb    | 3         | 3.49%   |
| 0x406e3    | 3         | 3.49%   |
| 0x20655    | 3         | 3.49%   |
| 0x906ea    | 2         | 2.33%   |
| 0x806ec    | 2         | 2.33%   |
| 0x806d1    | 2         | 2.33%   |
| 0x706a1    | 2         | 2.33%   |
| 0x306d4    | 2         | 2.33%   |
| 0x306a9    | 2         | 2.33%   |
| 0x1067a    | 2         | 2.33%   |
| 0x0a50000c | 2         | 2.33%   |
| 0x08600106 | 2         | 2.33%   |
| 0x906ed    | 1         | 1.16%   |
| 0x906e9    | 1         | 1.16%   |
| 0x806e9    | 1         | 1.16%   |
| 0x20652    | 1         | 1.16%   |
| 0x106c2    | 1         | 1.16%   |
| 0x0a50000d | 1         | 1.16%   |
| 0x08608102 | 1         | 1.16%   |
| 0x08600104 | 1         | 1.16%   |
| 0x08600103 | 1         | 1.16%   |
| 0x08108102 | 1         | 1.16%   |
| 0x06006705 | 1         | 1.16%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 19        | 23.46%  |
| Haswell          | 12        | 14.81%  |
| Zen 2            | 6         | 7.41%   |
| TigerLake        | 5         | 6.17%   |
| Skylake          | 5         | 6.17%   |
| SandyBridge      | 5         | 6.17%   |
| Zen 3            | 4         | 4.94%   |
| Westmere         | 4         | 4.94%   |
| IvyBridge        | 3         | 3.7%    |
| Unknown          | 3         | 3.7%    |
| Penryn           | 2         | 2.47%   |
| Icelake          | 2         | 2.47%   |
| Goldmont plus    | 2         | 2.47%   |
| Broadwell        | 2         | 2.47%   |
| Alderlake Hybrid | 2         | 2.47%   |
| Zen+             | 1         | 1.23%   |
| Goldmont         | 1         | 1.23%   |
| Excavator        | 1         | 1.23%   |
| CometLake        | 1         | 1.23%   |
| Bonnell          | 1         | 1.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 63        | 57.8%   |
| Nvidia | 28        | 25.69%  |
| AMD    | 18        | 16.51%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 8         | 7.27%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 6         | 5.45%   |
| AMD Renoir                                                                | 6         | 5.45%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 5         | 4.55%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 5         | 4.55%   |
| Intel UHD Graphics 620                                                    | 4         | 3.64%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 4         | 3.64%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 4         | 3.64%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 4         | 3.64%   |
| Nvidia GA107GLM [RTX A1000 Laptop GPU]                                    | 3         | 2.73%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 3         | 2.73%   |
| Intel Alder Lake-HX GT1 [UHD Graphics 770]                                | 3         | 2.73%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 3         | 2.73%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 1.82%   |
| Nvidia GP108M [GeForce MX250]                                             | 2         | 1.82%   |
| Nvidia GP108M [GeForce MX150]                                             | 2         | 1.82%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 2         | 1.82%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 2         | 1.82%   |
| Nvidia GK107GLM [Quadro K1100M]                                           | 2         | 1.82%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 2         | 1.82%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                             | 1         | 0.91%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                     | 1         | 0.91%   |
| Nvidia GT215M [GeForce GTS 250M]                                          | 1         | 0.91%   |
| Nvidia GM108M [GeForce 840M]                                              | 1         | 0.91%   |
| Nvidia GM107M [GeForce GTX 950M]                                          | 1         | 0.91%   |
| Nvidia GM107M [GeForce GTX 850M]                                          | 1         | 0.91%   |
| Nvidia GK104M [GeForce GTX 680M]                                          | 1         | 0.91%   |
| Nvidia GF108M [GeForce GT 520M]                                           | 1         | 0.91%   |
| Nvidia GF108M [GeForce GT 415M]                                           | 1         | 0.91%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 1         | 0.91%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                        | 1         | 0.91%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 1         | 0.91%   |
| Nvidia G98M [GeForce G 105M]                                              | 1         | 0.91%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                       | 1         | 0.91%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 0.91%   |
| Intel Iris Plus Graphics 640                                              | 1         | 0.91%   |
| Intel HD Graphics 630                                                     | 1         | 0.91%   |
| Intel HD Graphics 5500                                                    | 1         | 0.91%   |
| Intel HD Graphics 530                                                     | 1         | 0.91%   |
| Intel HD Graphics 515                                                     | 1         | 0.91%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 35        | 43.21%  |
| Intel + Nvidia | 25        | 30.86%  |
| 1 x AMD        | 14        | 17.28%  |
| 1 x Nvidia     | 3         | 3.7%    |
| Intel + AMD    | 3         | 3.7%    |
| 2 x AMD        | 1         | 1.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 68        | 82.93%  |
| Proprietary | 12        | 14.63%  |
| Unknown     | 2         | 2.44%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 56        | 68.29%  |
| 3.01-4.0   | 8         | 9.76%   |
| 0.01-0.5   | 8         | 9.76%   |
| 1.01-2.0   | 6         | 7.32%   |
| 0.51-1.0   | 4         | 4.88%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 21        | 21.88%  |
| LG Display              | 15        | 15.63%  |
| Samsung Electronics     | 11        | 11.46%  |
| AU Optronics            | 10        | 10.42%  |
| Sharp                   | 6         | 6.25%   |
| BOE                     | 6         | 6.25%   |
| Hewlett-Packard         | 4         | 4.17%   |
| Apple                   | 4         | 4.17%   |
| AOC                     | 4         | 4.17%   |
| Chi Mei Optoelectronics | 3         | 3.13%   |
| Iiyama                  | 2         | 2.08%   |
| Videoseven              | 1         | 1.04%   |
| Sony                    | 1         | 1.04%   |
| Philips                 | 1         | 1.04%   |
| PANDA                   | 1         | 1.04%   |
| Medion                  | 1         | 1.04%   |
| Lenovo                  | 1         | 1.04%   |
| Goldstar                | 1         | 1.04%   |
| CSO                     | 1         | 1.04%   |
| BenQ                    | 1         | 1.04%   |
| Aosiman                 | 1         | 1.04%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP14BA 1920x1080 340x190mm 15.3-inch               | 2         | 2.04%   |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch               | 2         | 2.04%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 2         | 2.04%   |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 355x199mm 16.0-inch      | 2         | 2.04%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 2         | 2.04%   |
| AOC 2250W AOC2250 1920x1080 477x268mm 21.5-inch                       | 2         | 2.04%   |
| Videoseven L27ADS IGM2700 1920x1080 598x336mm 27.0-inch               | 1         | 1.02%   |
| Sony LCD Monitor SNY05FA 1366x768 340x190mm 15.3-inch                 | 1         | 1.02%   |
| Sharp LCD Monitor SHP1516 3840x2400 336x210mm 15.6-inch               | 1         | 1.02%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch               | 1         | 1.02%   |
| Samsung Electronics S27D390 SAM0B67 1920x1080 598x336mm 27.0-inch     | 1         | 1.02%   |
| Samsung Electronics Odyssey G8 SAM7231 3440x1440 809x354mm 34.8-inch  | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SEC444E 1600x900 310x174mm 14.0-inch  | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SDC5844 1920x1080 344x194mm 15.5-inch | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch  | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SAM0B60 1920x1080 887x500mm 40.1-inch | 1         | 1.02%   |
| Samsung Electronics C27R50x SAM0F9D 1920x1080 598x336mm 27.0-inch     | 1         | 1.02%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1         | 1.02%   |
| Philips PHL 346B1C PHL095C 3440x1440 797x334mm 34.0-inch              | 1         | 1.02%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 1.02%   |
| Medion 42FPDEUDA1 MED222E 1920x1080                                   | 1         | 1.02%   |
| LG Display LP156WH2-TLE1 LGDCF01 1366x768 344x194mm 15.5-inch         | 1         | 1.02%   |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch          | 1         | 1.02%   |
| LG Display LCD Monitor LGD05EE 2560x1440 309x174mm 14.0-inch          | 1         | 1.02%   |
| LG Display LCD Monitor LGD05CE 1920x1080 344x194mm 15.5-inch          | 1         | 1.02%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch          | 1         | 1.02%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 1.02%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 1         | 1.02%   |
| LG Display LCD Monitor LGD046B 1366x768 344x194mm 15.5-inch           | 1         | 1.02%   |
| LG Display LCD Monitor LGD040A 1920x1080 309x175mm 14.0-inch          | 1         | 1.02%   |
| LG Display LCD Monitor LGD03B8 1366x768 310x174mm 14.0-inch           | 1         | 1.02%   |
| LG Display LCD Monitor LGD03B3 1366x768 310x174mm 14.0-inch           | 1         | 1.02%   |
| LG Display LCD Monitor LGD038C 1366x768 256x144mm 11.6-inch           | 1         | 1.02%   |
| LG Display LCD Monitor LGD02EF 1366x768 310x174mm 14.0-inch           | 1         | 1.02%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch           | 1         | 1.02%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch           | 1         | 1.02%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 41        | 47.67%  |
| 1366x768 (WXGA)    | 15        | 17.44%  |
| 1600x900 (HD+)     | 4         | 4.65%   |
| 3840x2160 (4K)     | 3         | 3.49%   |
| 2880x1800          | 3         | 3.49%   |
| 1920x1200 (WUXGA)  | 3         | 3.49%   |
| 3440x1440          | 2         | 2.33%   |
| 3200x1800 (QHD+)   | 2         | 2.33%   |
| 2560x1440 (QHD)    | 2         | 2.33%   |
| 1440x900 (WXGA+)   | 2         | 2.33%   |
| 3840x2400          | 1         | 1.16%   |
| 3072x1920          | 1         | 1.16%   |
| 2560x1600          | 1         | 1.16%   |
| 2520x1680          | 1         | 1.16%   |
| 2160x1440          | 1         | 1.16%   |
| 1680x1050 (WSXGA+) | 1         | 1.16%   |
| 1360x768           | 1         | 1.16%   |
| 1280x800 (WXGA)    | 1         | 1.16%   |
| 1280x1024 (SXGA)   | 1         | 1.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 31        | 31.96%  |
| 14      | 14        | 14.43%  |
| 13      | 13        | 13.4%   |
| 17      | 10        | 10.31%  |
| 16      | 7         | 7.22%   |
| 27      | 4         | 4.12%   |
| 21      | 4         | 4.12%   |
| 40      | 2         | 2.06%   |
| 34      | 2         | 2.06%   |
| 24      | 2         | 2.06%   |
| 59      | 1         | 1.03%   |
| 33      | 1         | 1.03%   |
| 28      | 1         | 1.03%   |
| 23      | 1         | 1.03%   |
| 22      | 1         | 1.03%   |
| 18      | 1         | 1.03%   |
| 11      | 1         | 1.03%   |
| Unknown | 1         | 1.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 56        | 58.33%  |
| 351-400     | 11        | 11.46%  |
| 201-300     | 8         | 8.33%   |
| 501-600     | 7         | 7.29%   |
| 401-500     | 6         | 6.25%   |
| 801-900     | 3         | 3.13%   |
| 701-800     | 2         | 2.08%   |
| 601-700     | 1         | 1.04%   |
| 1001-1500   | 1         | 1.04%   |
| Unknown     | 1         | 1.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 63        | 75.9%   |
| 16/10 | 15        | 18.07%  |
| 3/2   | 2         | 2.41%   |
| 21/9  | 2         | 2.41%   |
| 5/4   | 1         | 1.2%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 31        | 31.96%  |
| 81-90          | 22        | 22.68%  |
| 201-250        | 7         | 7.22%   |
| 121-130        | 7         | 7.22%   |
| 111-120        | 6         | 6.19%   |
| 71-80          | 5         | 5.15%   |
| 351-500        | 4         | 4.12%   |
| 301-350        | 4         | 4.12%   |
| 141-150        | 2         | 2.06%   |
| 131-140        | 2         | 2.06%   |
| 501-1000       | 2         | 2.06%   |
| More than 1000 | 1         | 1.03%   |
| 51-60          | 1         | 1.03%   |
| 251-300        | 1         | 1.03%   |
| 91-100         | 1         | 1.03%   |
| Unknown        | 1         | 1.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 41        | 43.16%  |
| 101-120       | 25        | 26.32%  |
| 51-100        | 11        | 11.58%  |
| 161-240       | 10        | 10.53%  |
| More than 240 | 6         | 6.32%   |
| 1-50          | 1         | 1.05%   |
| Unknown       | 1         | 1.05%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 63        | 75.9%   |
| 2     | 16        | 19.28%  |
| 3     | 2         | 2.41%   |
| 0     | 2         | 2.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 56        | 43.08%  |
| Realtek Semiconductor           | 35        | 26.92%  |
| Qualcomm Atheros                | 13        | 10%     |
| Broadcom                        | 9         | 6.92%   |
| MediaTek                        | 3         | 2.31%   |
| Marvell Technology Group        | 3         | 2.31%   |
| Sierra Wireless                 | 2         | 1.54%   |
| DisplayLink                     | 2         | 1.54%   |
| Shenzhen Goodix Technology      | 1         | 0.77%   |
| Qualcomm Atheros Communications | 1         | 0.77%   |
| Lenovo                          | 1         | 0.77%   |
| JMicron Technology              | 1         | 0.77%   |
| Huawei Technologies             | 1         | 0.77%   |
| Broadcom Limited                | 1         | 0.77%   |
| ASIX Electronics                | 1         | 0.77%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 25        | 15.92%  |
| Intel Wi-Fi 6 AX200                                                            | 9         | 5.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 3.18%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 5         | 3.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 4         | 2.55%   |
| Intel Wireless 8260                                                            | 4         | 2.55%   |
| Intel Wireless 7260                                                            | 4         | 2.55%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 3         | 1.91%   |
| Intel Wireless 8265 / 8275                                                     | 3         | 1.91%   |
| Intel Wireless 3160                                                            | 3         | 1.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 3         | 1.91%   |
| Intel Alder Lake-S PCH CNVi WiFi                                               | 3         | 1.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 1.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 2         | 1.27%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 1.27%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 2         | 1.27%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                  | 2         | 1.27%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.27%   |
| Intel Wireless-AC 9260                                                         | 2         | 1.27%   |
| Intel Wireless 3165                                                            | 2         | 1.27%   |
| Intel Wi-Fi 6 AX201                                                            | 2         | 1.27%   |
| Intel Tiger Lake PCH CNVi WiFi                                                 | 2         | 1.27%   |
| Intel Ethernet Connection I219-V                                               | 2         | 1.27%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 1.27%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 1.27%   |
| Intel Ethernet Connection (17) I219-LM                                         | 2         | 1.27%   |
| DisplayLink Dell D3100 Docking Station                                         | 2         | 1.27%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 2         | 1.27%   |
| Sierra Wireless EM7455                                                         | 1         | 0.64%   |
| Sierra Wireless EM7305 Modem                                                   | 1         | 0.64%   |
| Shenzhen Goodix Unknow device                                                  | 1         | 0.64%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 1         | 0.64%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1         | 0.64%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 1         | 0.64%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.64%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 1         | 0.64%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.64%   |
| Qualcomm Atheros AR9271 802.11n                                                | 1         | 0.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 1         | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 54        | 63.53%  |
| Qualcomm Atheros                | 12        | 14.12%  |
| Realtek Semiconductor           | 6         | 7.06%   |
| Broadcom                        | 6         | 7.06%   |
| MediaTek                        | 3         | 3.53%   |
| Sierra Wireless                 | 2         | 2.35%   |
| Qualcomm Atheros Communications | 1         | 1.18%   |
| Broadcom Limited                | 1         | 1.18%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 9         | 10.47%  |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 5         | 5.81%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 4         | 4.65%   |
| Intel Wireless 8260                                            | 4         | 4.65%   |
| Intel Wireless 7260                                            | 4         | 4.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 3.49%   |
| Intel Wireless 8265 / 8275                                     | 3         | 3.49%   |
| Intel Wireless 3160                                            | 3         | 3.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 3.49%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 3         | 3.49%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 2.33%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 2.33%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 2.33%   |
| Intel Wireless-AC 9260                                         | 2         | 2.33%   |
| Intel Wireless 3165                                            | 2         | 2.33%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 2.33%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 2.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 2.33%   |
| Sierra Wireless EM7455                                         | 1         | 1.16%   |
| Sierra Wireless EM7305 Modem                                   | 1         | 1.16%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 1.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 1.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 1.16%   |
| Qualcomm Atheros AR9271 802.11n                                | 1         | 1.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 1.16%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 1.16%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 1.16%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.16%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter            | 1         | 1.16%   |
| Intel WiMAX/WiFi Link 5150                                     | 1         | 1.16%   |
| Intel WiMAX Connection 2400m                                   | 1         | 1.16%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 1.16%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 1         | 1.16%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 1.16%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 1.16%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 1.16%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 1         | 1.16%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 1.16%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 1.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 1         | 1.16%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 32        | 48.48%  |
| Intel                    | 19        | 28.79%  |
| Broadcom                 | 4         | 6.06%   |
| Qualcomm Atheros         | 3         | 4.55%   |
| Marvell Technology Group | 3         | 4.55%   |
| DisplayLink              | 2         | 3.03%   |
| Lenovo                   | 1         | 1.52%   |
| JMicron Technology       | 1         | 1.52%   |
| ASIX Electronics         | 1         | 1.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 25        | 36.76%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 7.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 4.41%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 2.94%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 2.94%   |
| Intel Ethernet Connection I219-V                                               | 2         | 2.94%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 2.94%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 2.94%   |
| Intel Ethernet Connection (17) I219-LM                                         | 2         | 2.94%   |
| DisplayLink Dell D3100 Docking Station                                         | 2         | 2.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1         | 1.47%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 1.47%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 1.47%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 1.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 1.47%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 1.47%   |
| Lenovo ThinkPad Lan                                                            | 1         | 1.47%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 1.47%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 1.47%   |
| Intel Ethernet Connection I217-V                                               | 1         | 1.47%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 1.47%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 1.47%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 1.47%   |
| Intel Ethernet Connection (17) I219-V                                          | 1         | 1.47%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 1.47%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 1.47%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 1         | 1.47%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 1.47%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 1         | 1.47%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 1         | 1.47%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 1.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 81        | 55.48%  |
| Ethernet | 62        | 42.47%  |
| Unknown  | 2         | 1.37%   |
| Modem    | 1         | 0.68%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 69        | 77.53%  |
| Ethernet | 20        | 22.47%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 56        | 69.14%  |
| 1     | 23        | 28.4%   |
| 3     | 2         | 2.47%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 63        | 76.83%  |
| Yes  | 19        | 23.17%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 47        | 67.14%  |
| Foxconn / Hon Hai               | 6         | 8.57%   |
| Realtek                         | 3         | 4.29%   |
| Qualcomm Atheros Communications | 3         | 4.29%   |
| Lite-On Technology              | 2         | 2.86%   |
| IMC Networks                    | 2         | 2.86%   |
| Hewlett-Packard                 | 2         | 2.86%   |
| Apple                           | 2         | 2.86%   |
| Toshiba                         | 1         | 1.43%   |
| Realtek Semiconductor           | 1         | 1.43%   |
| Micro Star International        | 1         | 1.43%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 15        | 21.43%  |
| Intel AX200 Bluetooth                                                               | 9         | 12.86%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 8         | 11.43%  |
| Intel AX201 Bluetooth                                                               | 6         | 8.57%   |
| Intel Bluetooth Device                                                              | 5         | 7.14%   |
| Realtek 802.11ac WLAN Adapter                                                       | 2         | 2.86%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 2         | 2.86%   |
| Lite-On Bluetooth Device                                                            | 2         | 2.86%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 2.86%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 2.86%   |
| Toshiba Bluetooth Device                                                            | 1         | 1.43%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.43%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.43%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.43%   |
| Micro Star International Motorola Bluetooth 2.1+EDR Device                          | 1         | 1.43%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 1.43%   |
| Intel AX210 Bluetooth                                                               | 1         | 1.43%   |
| IMC Networks Wireless_Device                                                        | 1         | 1.43%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.43%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 1         | 1.43%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.43%   |
| Foxconn / Hon Hai BT                                                                | 1         | 1.43%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 1.43%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 1         | 1.43%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 1.43%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 1.43%   |
| Apple Bluetooth Host Controller                                                     | 1         | 1.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel           | 68        | 68.69%  |
| AMD             | 15        | 15.15%  |
| Nvidia          | 10        | 10.1%   |
| Hewlett-Packard | 2         | 2.02%   |
| Logitech        | 1         | 1.01%   |
| Lenovo          | 1         | 1.01%   |
| Bose            | 1         | 1.01%   |
| Apple           | 1         | 1.01%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Renoir Radeon High Definition Audio Controller                         | 11        | 8.8%    |
| AMD Family 17h/19h HD Audio Controller                                     | 11        | 8.8%    |
| Intel Sunrise Point-LP HD Audio                                            | 9         | 7.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8         | 6.4%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8         | 6.4%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 4.8%    |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 4.8%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 4%      |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 3.2%    |
| Intel 8 Series HD Audio Controller                                         | 4         | 3.2%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 3.2%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 3.2%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 3.2%    |
| Nvidia Audio device                                                        | 3         | 2.4%    |
| Intel Alder Lake-S HD Audio Controller                                     | 3         | 2.4%    |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.6%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 1.6%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 1.6%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.6%    |
| Intel Broadwell-U Audio Controller                                         | 2         | 1.6%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 1.6%    |
| Hewlett-Packard USB Audio                                                  | 2         | 1.6%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.8%    |
| Nvidia High Definition Audio Controller                                    | 1         | 0.8%    |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.8%    |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 0.8%    |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 0.8%    |
| Logitech Headset H390                                                      | 1         | 0.8%    |
| Lenovo ThinkPad Dock USB Audio                                             | 1         | 0.8%    |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 1         | 0.8%    |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 0.8%    |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.8%    |
| Intel CM238 HD Audio Controller                                            | 1         | 0.8%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.8%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 0.8%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 0.8%    |
| Bose Revolve SoundLink                                                     | 1         | 0.8%    |
| Apple Audio Device                                                         | 1         | 0.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 0.8%    |
| AMD High Definition Audio Controller                                       | 1         | 0.8%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 25        | 45.45%  |
| SK hynix            | 12        | 21.82%  |
| Micron Technology   | 6         | 10.91%  |
| Unknown             | 3         | 5.45%   |
| Crucial             | 3         | 5.45%   |
| Kingston            | 2         | 3.64%   |
| A-DATA Technology   | 2         | 3.64%   |
| Wilk                | 1         | 1.82%   |
| Timetec             | 1         | 1.82%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 3         | 5%      |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                   | 2         | 3.33%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 3.33%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s          | 2         | 3.33%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 2         | 3.33%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s         | 2         | 3.33%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s          | 2         | 3.33%   |
| Wilk RAM GR3200S464L22S/16G 16GB SODIMM DDR4 3200MT/s          | 1         | 1.67%   |
| Unknown RAM Module 4GB SODIMM DDR3                             | 1         | 1.67%   |
| Unknown RAM Module 2GB SODIMM DDR2                             | 1         | 1.67%   |
| Unknown RAM Module 2048MB SODIMM DDR2                          | 1         | 1.67%   |
| Unknown RAM Module 1024MB SODIMM DDR2                          | 1         | 1.67%   |
| Timetec RAM SD3-1333 8GB SODIMM DDR3 1333MT/s                  | 1         | 1.67%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s        | 1         | 1.67%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 1.67%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s         | 1         | 1.67%   |
| SK hynix RAM HMCG88MEBSA092N 32GB SODIMM DDR5 4800MT/s         | 1         | 1.67%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 1         | 1.67%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s         | 1         | 1.67%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s        | 1         | 1.67%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s        | 1         | 1.67%   |
| SK hynix RAM HMA81GS6MFR8N-UH 8192MB SODIMM DDR4 2400MT/s      | 1         | 1.67%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s         | 1         | 1.67%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                    | 1         | 1.67%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.67%   |
| Samsung RAM Module 4GB SODIMM DDR3 1067MT/s                    | 1         | 1.67%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                | 1         | 1.67%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s          | 1         | 1.67%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s          | 1         | 1.67%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 1         | 1.67%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s          | 1         | 1.67%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s         | 1         | 1.67%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s         | 1         | 1.67%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 1         | 1.67%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s          | 1         | 1.67%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 1.67%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s          | 1         | 1.67%   |
| Samsung RAM M471A1G44AB0-CTD 8GB Row Of Chips DDR4 2667MT/s    | 1         | 1.67%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s        | 1         | 1.67%   |
| Micron RAM MT52L512M32D2PF-09 4GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 27        | 52.94%  |
| DDR3   | 16        | 31.37%  |
| LPDDR3 | 3         | 5.88%   |
| DDR5   | 3         | 5.88%   |
| DDR2   | 2         | 3.92%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 47        | 92.16%  |
| Row Of Chips | 4         | 7.84%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 24        | 42.11%  |
| 4096  | 13        | 22.81%  |
| 16384 | 11        | 19.3%   |
| 2048  | 5         | 8.77%   |
| 32768 | 3         | 5.26%   |
| 1024  | 1         | 1.75%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 15        | 27.78%  |
| 3200    | 12        | 22.22%  |
| 1600    | 10        | 18.52%  |
| 2400    | 4         | 7.41%   |
| 2133    | 4         | 7.41%   |
| 4800    | 3         | 5.56%   |
| Unknown | 3         | 5.56%   |
| 1334    | 1         | 1.85%   |
| 1333    | 1         | 1.85%   |
| 1067    | 1         | 1.85%   |

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
| Chicony Electronics                    | 22        | 29.73%  |
| Microdia                               | 11        | 14.86%  |
| IMC Networks                           | 9         | 12.16%  |
| Samsung Electronics                    | 4         | 5.41%   |
| Quanta                                 | 4         | 5.41%   |
| Ricoh                                  | 3         | 4.05%   |
| Realtek Semiconductor                  | 3         | 4.05%   |
| Luxvisions Innotech Limited            | 3         | 4.05%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.05%   |
| Bison Electronics                      | 3         | 4.05%   |
| Sunplus Innovation Technology          | 2         | 2.7%    |
| Alcor Micro                            | 2         | 2.7%    |
| ShineTech                              | 1         | 1.35%   |
| Logitech                               | 1         | 1.35%   |
| Apple                                  | 1         | 1.35%   |
| ALi                                    | 1         | 1.35%   |
| Acer                                   | 1         | 1.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                    | 5         | 6.76%   |
| IMC Networks USB2.0 HD UVC WebCam                | 5         | 6.76%   |
| Samsung Galaxy series, misc. (MTP mode)          | 4         | 5.41%   |
| IMC Networks Integrated Camera                   | 3         | 4.05%   |
| Chicony Integrated Camera                        | 3         | 4.05%   |
| Realtek Integrated_Webcam_HD                     | 2         | 2.7%    |
| Quanta HD User Facing                            | 2         | 2.7%    |
| Microdia Integrated_Webcam_FHD                   | 2         | 2.7%    |
| Microdia Integrated Webcam                       | 2         | 2.7%    |
| Luxvisions Innotech Limited HP HD Camera         | 2         | 2.7%    |
| Chicony Integrated IR Camera                     | 2         | 2.7%    |
| Chicony Integrated Camera (1280x720@30)          | 2         | 2.7%    |
| Chicony HP HD Camera                             | 2         | 2.7%    |
| Cheng Uei Precision Industry (Foxlink) HD Camera | 2         | 2.7%    |
| Sunplus HP HD Webcam [Fixed]                     | 1         | 1.35%   |
| Sunplus HD WebCam                                | 1         | 1.35%   |
| ShineTech HD Camera                              | 1         | 1.35%   |
| Ricoh USB2.0 Camera                              | 1         | 1.35%   |
| Ricoh Sony Visual Communication Camera           | 1         | 1.35%   |
| Ricoh Sony Vaio Integrated Webcam                | 1         | 1.35%   |
| Realtek HP Truevision HD                         | 1         | 1.35%   |
| Quanta HP Wide Vision HD Camera                  | 1         | 1.35%   |
| Quanta HP Webcam                                 | 1         | 1.35%   |
| Microdia Webcam Vitade AF                        | 1         | 1.35%   |
| Microdia Webcam                                  | 1         | 1.35%   |
| Luxvisions Innotech Limited HP 5MP Camera        | 1         | 1.35%   |
| Logitech HD Pro Webcam C920                      | 1         | 1.35%   |
| IMC Networks HD Camera                           | 1         | 1.35%   |
| Chicony USB2.0 VGA UVC WebCam                    | 1         | 1.35%   |
| Chicony USB2.0 HD UVC WebCam                     | 1         | 1.35%   |
| Chicony USB 2.0 Camera                           | 1         | 1.35%   |
| Chicony TOSHIBA Web Camera - HD                  | 1         | 1.35%   |
| Chicony ThinkPad T490 Webcam                     | 1         | 1.35%   |
| Chicony Integrated HP HD Webcam                  | 1         | 1.35%   |
| Chicony HP Wide Vision HD Camera                 | 1         | 1.35%   |
| Chicony HP Truevision HD                         | 1         | 1.35%   |
| Chicony HD WebCam (Asus N-series)                | 1         | 1.35%   |
| Chicony HD WebCam                                | 1         | 1.35%   |
| Chicony FJ Camera                                | 1         | 1.35%   |
| Chicony EasyCamera                               | 1         | 1.35%   |

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
| 0     | 41        | 48.81%  |
| 1     | 28        | 33.33%  |
| 2     | 13        | 15.48%  |
| 3     | 2         | 2.38%   |

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

