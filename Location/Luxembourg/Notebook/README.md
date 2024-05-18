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

Total: 130

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Apple         | MacBookPro8,1               | [d8f7a5da03](https://linux-hardware.org/?probe=d8f7a5da03) | Apr 23, 2024 |
| Dell          | Latitude 5490               | [6083d1ad5b](https://linux-hardware.org/?probe=6083d1ad5b) | Apr 09, 2024 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [529873e41c](https://linux-hardware.org/?probe=529873e41c) | Mar 26, 2024 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | [0f6b378c5d](https://linux-hardware.org/?probe=0f6b378c5d) | Mar 22, 2024 |
| Unknown       | Unknown                     | [bad7799ac9](https://linux-hardware.org/?probe=bad7799ac9) | Feb 11, 2024 |
| ASUSTek       | K72JT                       | [51117cd448](https://linux-hardware.org/?probe=51117cd448) | Dec 29, 2023 |
| Dell          | Precision M3800             | [9e8d36821a](https://linux-hardware.org/?probe=9e8d36821a) | Dec 14, 2023 |
| HUAWEI        | HVY-WXX9                    | [6f35ce12bd](https://linux-hardware.org/?probe=6f35ce12bd) | Dec 07, 2023 |
| Dell          | Precision M3800             | [a01e02361f](https://linux-hardware.org/?probe=a01e02361f) | Nov 26, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [0b974daf24](https://linux-hardware.org/?probe=0b974daf24) | Nov 24, 2023 |
| Framework     | Laptop                      | [ad3c0b1f5c](https://linux-hardware.org/?probe=ad3c0b1f5c) | Nov 10, 2023 |
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
| Ubuntu 20.04                 | 13        | 12.5%   |
| Ubuntu 22.04                 | 9         | 8.65%   |
| Ubuntu 18.04                 | 5         | 4.81%   |
| openSUSE Tumbleweed-XXXXXXXX | 4         | 3.85%   |
| Linux Mint 20.3              | 4         | 3.85%   |
| Ubuntu 21.04                 | 3         | 2.88%   |
| Pop!_OS 21.04                | 3         | 2.88%   |
| OpenMandriva 4.90            | 3         | 2.88%   |
| OpenMandriva 4.2             | 3         | 2.88%   |
| Linux Mint 21.2              | 3         | 2.88%   |
| Xubuntu 20.04                | 2         | 1.92%   |
| Ubuntu 20.10                 | 2         | 1.92%   |
| Pop!_OS 22.04                | 2         | 1.92%   |
| OpenMandriva 23.03           | 2         | 1.92%   |
| Fedora 39                    | 2         | 1.92%   |
| Fedora 37                    | 2         | 1.92%   |
| Arch Rolling                 | 2         | 1.92%   |
| Xubuntu 18.04                | 1         | 0.96%   |
| Ubuntu MATE 21.10            | 1         | 0.96%   |
| Ubuntu MATE 20.04            | 1         | 0.96%   |
| Ubuntu 23.10                 | 1         | 0.96%   |
| Ubuntu 18.10                 | 1         | 0.96%   |
| RHEL 8                       | 1         | 0.96%   |
| Pop!_OS 21.10                | 1         | 0.96%   |
| Pop!_OS 20.10                | 1         | 0.96%   |
| Pop!_OS 20.04                | 1         | 0.96%   |
| Parrot 5.3                   | 1         | 0.96%   |
| Parrot 5.1                   | 1         | 0.96%   |
| openSUSE Leap-15.1           | 1         | 0.96%   |
| OpenMandriva 4.3             | 1         | 0.96%   |
| OpenMandriva 23.10           | 1         | 0.96%   |
| Manjaro 21.2.6               | 1         | 0.96%   |
| Manjaro 19.0.2               | 1         | 0.96%   |
| Lubuntu 20.04                | 1         | 0.96%   |
| LMDE 4                       | 1         | 0.96%   |
| Linux Mint 20.2              | 1         | 0.96%   |
| Linux Mint 19.2              | 1         | 0.96%   |
| Kubuntu 23.04                | 1         | 0.96%   |
| Kubuntu 22.04                | 1         | 0.96%   |
| Kubuntu 18.04                | 1         | 0.96%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 32        | 33.68%  |
| OpenMandriva | 9         | 9.47%   |
| Linux Mint   | 8         | 8.42%   |
| Pop!_OS      | 7         | 7.37%   |
| openSUSE     | 5         | 5.26%   |
| Fedora       | 5         | 5.26%   |
| Xubuntu      | 3         | 3.16%   |
| Kubuntu      | 3         | 3.16%   |
| Ubuntu MATE  | 2         | 2.11%   |
| Parrot       | 2         | 2.11%   |
| Manjaro      | 2         | 2.11%   |
| Endless      | 2         | 2.11%   |
| Debian       | 2         | 2.11%   |
| Arch         | 2         | 2.11%   |
| RHEL         | 1         | 1.05%   |
| Lubuntu      | 1         | 1.05%   |
| LMDE         | 1         | 1.05%   |
| KDE neon     | 1         | 1.05%   |
| Kali         | 1         | 1.05%   |
| Garuda Linux | 1         | 1.05%   |
| Elementary   | 1         | 1.05%   |
| Clear Linux  | 1         | 1.05%   |
| CachyOS      | 1         | 1.05%   |
| BlackPanther | 1         | 1.05%   |
| ArcoLinux    | 1         | 1.05%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.18.12-desktop-3omv4090 | 3         | 2.8%    |
| 5.11.0-27-generic        | 3         | 2.8%    |
| 5.10.14-desktop-1omv4002 | 3         | 2.8%    |
| 6.2.6-desktop-1omv2390   | 2         | 1.87%   |
| 6.2.14-200.fc37.x86_64   | 2         | 1.87%   |
| 5.8.0-59-generic         | 2         | 1.87%   |
| 5.4.0-96-generic         | 2         | 1.87%   |
| 5.4.0-122-generic        | 2         | 1.87%   |
| 5.19.0-35-generic        | 2         | 1.87%   |
| 5.11.0-34-generic        | 2         | 1.87%   |
| 5.11.0-17-generic        | 2         | 1.87%   |
| 5.0.0-23-generic         | 2         | 1.87%   |
| 6.7.9-200.fc39.x86_64    | 1         | 0.93%   |
| 6.6.6-200.fc39.x86_64    | 1         | 0.93%   |
| 6.6.2-arch1-1            | 1         | 0.93%   |
| 6.5.7-2-cachyos          | 1         | 0.93%   |
| 6.5.5-desktop-1omv2390   | 1         | 0.93%   |
| 6.5.12-200.fc38.x86_64   | 1         | 0.93%   |
| 6.5.0-28-generic         | 1         | 0.93%   |
| 6.5.0-27-generic         | 1         | 0.93%   |
| 6.5.0-26-generic         | 1         | 0.93%   |
| 6.5.0-10-generic         | 1         | 0.93%   |
| 6.4.3-1-default          | 1         | 0.93%   |
| 6.4.3-060403-generic     | 1         | 0.93%   |
| 6.2.0-37-generic         | 1         | 0.93%   |
| 6.2.0-26-generic         | 1         | 0.93%   |
| 6.1.8-060108-generic     | 1         | 0.93%   |
| 6.1.0-1parrot1-amd64     | 1         | 0.93%   |
| 6.0.6-76060006-generic   | 1         | 0.93%   |
| 6.0.0-kali3-amd64        | 1         | 0.93%   |
| 5.8.11-050811-generic    | 1         | 0.93%   |
| 5.8.0-63-generic         | 1         | 0.93%   |
| 5.8.0-55-generic         | 1         | 0.93%   |
| 5.8.0-43-generic         | 1         | 0.93%   |
| 5.8.0-31-generic         | 1         | 0.93%   |
| 5.8.0-20-generic         | 1         | 0.93%   |
| 5.8.0-14-generic         | 1         | 0.93%   |
| 5.7.6-201.fc32.x86_64    | 1         | 0.93%   |
| 5.7.1-1-default          | 1         | 0.93%   |
| 5.7.0-3-amd64            | 1         | 0.93%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 12        | 11.43%  |
| 5.4.0   | 9         | 8.57%   |
| 5.8.0   | 8         | 7.62%   |
| 5.15.0  | 8         | 7.62%   |
| 5.19.0  | 5         | 4.76%   |
| 6.5.0   | 4         | 3.81%   |
| 5.13.0  | 4         | 3.81%   |
| 5.3.0   | 3         | 2.86%   |
| 5.18.12 | 3         | 2.86%   |
| 5.10.14 | 3         | 2.86%   |
| 4.15.0  | 3         | 2.86%   |
| 6.4.3   | 2         | 1.9%    |
| 6.2.6   | 2         | 1.9%    |
| 6.2.14  | 2         | 1.9%    |
| 6.2.0   | 2         | 1.9%    |
| 5.7.0   | 2         | 1.9%    |
| 5.0.0   | 2         | 1.9%    |
| 4.18.0  | 2         | 1.9%    |
| 6.7.9   | 1         | 0.95%   |
| 6.6.6   | 1         | 0.95%   |
| 6.6.2   | 1         | 0.95%   |
| 6.5.7   | 1         | 0.95%   |
| 6.5.5   | 1         | 0.95%   |
| 6.5.12  | 1         | 0.95%   |
| 6.1.8   | 1         | 0.95%   |
| 6.1.0   | 1         | 0.95%   |
| 6.0.6   | 1         | 0.95%   |
| 6.0.0   | 1         | 0.95%   |
| 5.8.11  | 1         | 0.95%   |
| 5.7.6   | 1         | 0.95%   |
| 5.7.1   | 1         | 0.95%   |
| 5.6.3   | 1         | 0.95%   |
| 5.5.8   | 1         | 0.95%   |
| 5.18.5  | 1         | 0.95%   |
| 5.18.0  | 1         | 0.95%   |
| 5.16.7  | 1         | 0.95%   |
| 5.16.2  | 1         | 0.95%   |
| 5.16.11 | 1         | 0.95%   |
| 5.15.4  | 1         | 0.95%   |
| 5.15.32 | 1         | 0.95%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 12        | 11.43%  |
| 5.15    | 10        | 9.52%   |
| 5.8     | 9         | 8.57%   |
| 5.4     | 9         | 8.57%   |
| 6.5     | 7         | 6.67%   |
| 6.2     | 6         | 5.71%   |
| 5.19    | 5         | 4.76%   |
| 5.18    | 5         | 4.76%   |
| 5.10    | 5         | 4.76%   |
| 5.7     | 4         | 3.81%   |
| 5.13    | 4         | 3.81%   |
| 5.3     | 3         | 2.86%   |
| 5.16    | 3         | 2.86%   |
| 4.18    | 3         | 2.86%   |
| 4.15    | 3         | 2.86%   |
| 6.6     | 2         | 1.9%    |
| 6.4     | 2         | 1.9%    |
| 6.1     | 2         | 1.9%    |
| 6.0     | 2         | 1.9%    |
| 5.0     | 2         | 1.9%    |
| 6.7     | 1         | 0.95%   |
| 5.6     | 1         | 0.95%   |
| 5.5     | 1         | 0.95%   |
| 5.14    | 1         | 0.95%   |
| 5.12    | 1         | 0.95%   |
| 4.19    | 1         | 0.95%   |
| 4.12    | 1         | 0.95%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 91        | 98.91%  |
| i686   | 1         | 1.09%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 42        | 44.68%  |
| KDE5            | 17        | 18.09%  |
| X-Cinnamon      | 9         | 9.57%   |
| Unknown         | 7         | 7.45%   |
| XFCE            | 6         | 6.38%   |
| MATE            | 4         | 4.26%   |
| KDE             | 3         | 3.19%   |
| i3              | 2         | 2.13%   |
| Pantheon        | 1         | 1.06%   |
| LXQt            | 1         | 1.06%   |
| GNOME Flashback | 1         | 1.06%   |
| Cinnamon        | 1         | 1.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 70        | 72.16%  |
| Wayland | 22        | 22.68%  |
| Unknown | 5         | 5.15%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 40        | 41.24%  |
| GDM     | 17        | 17.53%  |
| SDDM    | 13        | 13.4%   |
| LightDM | 13        | 13.4%   |
| GDM3    | 11        | 11.34%  |
| TDM     | 3         | 3.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 45        | 46.88%  |
| en_GB   | 10        | 10.42%  |
| Unknown | 7         | 7.29%   |
| de_LU   | 6         | 6.25%   |
| de_DE   | 6         | 6.25%   |
| fr_LU   | 4         | 4.17%   |
| fr_FR   | 4         | 4.17%   |
| nl_NL   | 2         | 2.08%   |
| unm_US  | 1         | 1.04%   |
| pt_PT   | 1         | 1.04%   |
| pt_BR   | 1         | 1.04%   |
| POSIX   | 1         | 1.04%   |
| it_IT   | 1         | 1.04%   |
| hr_HR   | 1         | 1.04%   |
| fr_CH   | 1         | 1.04%   |
| fr_BE   | 1         | 1.04%   |
| es_ES   | 1         | 1.04%   |
| en_IE   | 1         | 1.04%   |
| en_AU   | 1         | 1.04%   |
| C       | 1         | 1.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 56        | 59.57%  |
| BIOS | 38        | 40.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 67        | 71.28%  |
| Btrfs   | 11        | 11.7%   |
| Overlay | 8         | 8.51%   |
| Tmpfs   | 4         | 4.26%   |
| Xfs     | 3         | 3.19%   |
| Unknown | 1         | 1.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 47        | 50%     |
| Unknown | 39        | 41.49%  |
| MBR     | 8         | 8.51%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 85        | 91.4%   |
| Yes       | 8         | 8.6%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 71        | 77.17%  |
| Yes       | 21        | 22.83%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 15        | 16.3%   |
| Hewlett-Packard  | 14        | 15.22%  |
| Dell             | 12        | 13.04%  |
| ASUSTek Computer | 8         | 8.7%    |
| Acer             | 6         | 6.52%   |
| Sony             | 5         | 5.43%   |
| Apple            | 5         | 5.43%   |
| HUAWEI           | 4         | 4.35%   |
| Wortmann AG      | 3         | 3.26%   |
| win element      | 2         | 2.17%   |
| MSI              | 2         | 2.17%   |
| Medion           | 2         | 2.17%   |
| Fujitsu          | 2         | 2.17%   |
| Clevo            | 2         | 2.17%   |
| YJKC             | 1         | 1.09%   |
| TUXEDO           | 1         | 1.09%   |
| Toshiba          | 1         | 1.09%   |
| Timi             | 1         | 1.09%   |
| SLIMBOOK         | 1         | 1.09%   |
| Panasonic        | 1         | 1.09%   |
| Packard Bell     | 1         | 1.09%   |
| Notebook         | 1         | 1.09%   |
| Framework        | 1         | 1.09%   |
| Unknown          | 1         | 1.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| win element MoreFine S500+               | 2         | 2.17%   |
| Dell Precision M3800                     | 2         | 2.17%   |
| Dell Precision 7670                      | 2         | 2.17%   |
| Apple MacBookPro8,1                      | 2         | 2.17%   |
| YJKC vBook                               | 1         | 1.09%   |
| Wortmann AG TERRA_MOBILE_1749            | 1         | 1.09%   |
| Wortmann AG TERRA_MOBILE_1541H           | 1         | 1.09%   |
| Wortmann AG MS-1727                      | 1         | 1.09%   |
| TUXEDO Pulse 14 Gen1                     | 1         | 1.09%   |
| Toshiba Satellite C55-A-1N0              | 1         | 1.09%   |
| Timi RedmiBook 14 II                     | 1         | 1.09%   |
| Sony VPCP11S1R                           | 1         | 1.09%   |
| Sony VPCEB2E1E                           | 1         | 1.09%   |
| Sony VPCCA4E1E                           | 1         | 1.09%   |
| Sony VGN-NS30E_S                         | 1         | 1.09%   |
| Sony SVF1421E2EW                         | 1         | 1.09%   |
| SLIMBOOK EXECUTIVE-14                    | 1         | 1.09%   |
| Panasonic CF-195DCUBML                   | 1         | 1.09%   |
| Packard Bell EasyNote TJ65               | 1         | 1.09%   |
| Notebook NV4XMB,ME,MZ                    | 1         | 1.09%   |
| MSI GF72 8RD                             | 1         | 1.09%   |
| MSI GE63 7RD                             | 1         | 1.09%   |
| Medion P6685 MD61138                     | 1         | 1.09%   |
| Medion E4254 MD62100                     | 1         | 1.09%   |
| Lenovo Yoga 3 Pro-1370 80HE              | 1         | 1.09%   |
| Lenovo ThinkPad X1 Carbon 7th 20QDCTO1WW | 1         | 1.09%   |
| Lenovo ThinkPad T590 20N4CTO1WW          | 1         | 1.09%   |
| Lenovo ThinkPad T490 20N3S5DV0S          | 1         | 1.09%   |
| Lenovo ThinkPad T480s 20L7001PFR         | 1         | 1.09%   |
| Lenovo ThinkPad T470s W10DG 20JTS0R800   | 1         | 1.09%   |
| Lenovo ThinkPad T440p 20AWS24B00         | 1         | 1.09%   |
| Lenovo ThinkPad P1 Gen 2 20QTCTO1WW      | 1         | 1.09%   |
| Lenovo ThinkPad L15 Gen 1 20U8S0AH00     | 1         | 1.09%   |
| Lenovo ThinkPad L15 Gen 1 20U7S05B00     | 1         | 1.09%   |
| Lenovo ThinkPad L14 Gen 2a 20X6S15A00    | 1         | 1.09%   |
| Lenovo Legion 5 15IAH7H 82RB             | 1         | 1.09%   |
| Lenovo IdeaPad Pro 5 16APH8 83AR         | 1         | 1.09%   |
| Lenovo IdeaPad 330-15ICH 81FK            | 1         | 1.09%   |
| Lenovo G50-70 20351                      | 1         | 1.09%   |
| HUAWEI KLVL-WXXW                         | 1         | 1.09%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 10        | 10.87%  |
| Dell Precision         | 7         | 7.61%   |
| HP EliteBook           | 4         | 4.35%   |
| Acer Aspire            | 4         | 4.35%   |
| ASUS VivoBook          | 3         | 3.26%   |
| Wortmann AG TERRA      | 2         | 2.17%   |
| win element MoreFine   | 2         | 2.17%   |
| Lenovo IdeaPad         | 2         | 2.17%   |
| HP ZBook               | 2         | 2.17%   |
| HP ProBook             | 2         | 2.17%   |
| HP ENVY                | 2         | 2.17%   |
| Dell XPS               | 2         | 2.17%   |
| Apple MacBookPro8      | 2         | 2.17%   |
| YJKC vBook             | 1         | 1.09%   |
| Wortmann AG MS-1727    | 1         | 1.09%   |
| TUXEDO Pulse           | 1         | 1.09%   |
| Toshiba Satellite      | 1         | 1.09%   |
| Timi RedmiBook         | 1         | 1.09%   |
| Sony VPCP11S1R         | 1         | 1.09%   |
| Sony VPCEB2E1E         | 1         | 1.09%   |
| Sony VPCCA4E1E         | 1         | 1.09%   |
| Sony VGN-NS30E         | 1         | 1.09%   |
| Sony SVF1421E2EW       | 1         | 1.09%   |
| SLIMBOOK EXECUTIVE-14  | 1         | 1.09%   |
| Panasonic CF-195DCUBML | 1         | 1.09%   |
| Packard Bell EasyNote  | 1         | 1.09%   |
| Notebook NV4XMB        | 1         | 1.09%   |
| MSI GF72               | 1         | 1.09%   |
| MSI GE63               | 1         | 1.09%   |
| Medion P6685           | 1         | 1.09%   |
| Medion E4254           | 1         | 1.09%   |
| Lenovo Yoga            | 1         | 1.09%   |
| Lenovo Legion          | 1         | 1.09%   |
| Lenovo G50-70          | 1         | 1.09%   |
| HUAWEI KLVL-WXXW       | 1         | 1.09%   |
| HUAWEI HVY-WXX9        | 1         | 1.09%   |
| HUAWEI HLYL-WXX9       | 1         | 1.09%   |
| HUAWEI CREM-WXX9       | 1         | 1.09%   |
| HP Spectre             | 1         | 1.09%   |
| HP Pavilion            | 1         | 1.09%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 11        | 11.96%  |
| 2019 | 11        | 11.96%  |
| 2018 | 10        | 10.87%  |
| 2020 | 8         | 8.7%    |
| 2014 | 8         | 8.7%    |
| 2017 | 7         | 7.61%   |
| 2013 | 7         | 7.61%   |
| 2011 | 7         | 7.61%   |
| 2022 | 6         | 6.52%   |
| 2010 | 5         | 5.43%   |
| 2015 | 3         | 3.26%   |
| 2012 | 3         | 3.26%   |
| 2023 | 2         | 2.17%   |
| 2016 | 2         | 2.17%   |
| 2009 | 2         | 2.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 92        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 81        | 87.1%   |
| Enabled  | 12        | 12.9%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 92        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 21        | 22.34%  |
| 8.01-16.0   | 20        | 21.28%  |
| 4.01-8.0    | 19        | 20.21%  |
| 3.01-4.0    | 13        | 13.83%  |
| 32.01-64.0  | 11        | 11.7%   |
| 24.01-32.0  | 3         | 3.19%   |
| 64.01-256.0 | 3         | 3.19%   |
| 2.01-3.0    | 2         | 2.13%   |
| 1.01-2.0    | 2         | 2.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 32        | 32.32%  |
| 1.01-2.0   | 22        | 22.22%  |
| 4.01-8.0   | 16        | 16.16%  |
| 3.01-4.0   | 13        | 13.13%  |
| 8.01-16.0  | 10        | 10.1%   |
| 24.01-32.0 | 2         | 2.02%   |
| 0.51-1.0   | 2         | 2.02%   |
| 16.01-24.0 | 1         | 1.01%   |
| 0.01-0.5   | 1         | 1.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 69        | 74.19%  |
| 2      | 16        | 17.2%   |
| 3      | 7         | 7.53%   |
| 0      | 1         | 1.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 64        | 69.57%  |
| Yes       | 28        | 30.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 70        | 76.09%  |
| No        | 22        | 23.91%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 92        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 80        | 86.96%  |
| No        | 12        | 13.04%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| Luxembourg | 92        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Luxembourg        | 58        | 59.18%  |
| Strassen          | 8         | 8.16%   |
| Schifflange       | 3         | 3.06%   |
| Useldange         | 2         | 2.04%   |
| Steinfort         | 2         | 2.04%   |
| Schieren          | 2         | 2.04%   |
| Ehnen             | 2         | 2.04%   |
| Wiltz             | 1         | 1.02%   |
| Wecker            | 1         | 1.02%   |
| Vianden           | 1         | 1.02%   |
| Tetange           | 1         | 1.02%   |
| Soleuvre          | 1         | 1.02%   |
| PerlГ©          | 1         | 1.02%   |
| Oberpallen        | 1         | 1.02%   |
| Niederanven       | 1         | 1.02%   |
| Leudelange        | 1         | 1.02%   |
| Hunsdorf          | 1         | 1.02%   |
| Ettelbruck        | 1         | 1.02%   |
| Esch-sur-Alzette  | 1         | 1.02%   |
| Echternach        | 1         | 1.02%   |
| Differdange       | 1         | 1.02%   |
| Diekirch          | 1         | 1.02%   |
| Clervaux          | 1         | 1.02%   |
| Bourscheid        | 1         | 1.02%   |
| Bettembourg       | 1         | 1.02%   |
| Bettange-sur-Mess | 1         | 1.02%   |
| Beckerich         | 1         | 1.02%   |
| Aspelt            | 1         | 1.02%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 29        | 41     | 24.37%  |
| WDC                         | 12        | 14     | 10.08%  |
| Toshiba                     | 12        | 13     | 10.08%  |
| Seagate                     | 12        | 12     | 10.08%  |
| SanDisk                     | 8         | 11     | 6.72%   |
| Kingston                    | 7         | 9      | 5.88%   |
| Crucial                     | 6         | 8      | 5.04%   |
| SK hynix                    | 5         | 5      | 4.2%    |
| Intel                       | 4         | 5      | 3.36%   |
| Apple                       | 4         | 5      | 3.36%   |
| Micron Technology           | 2         | 3      | 1.68%   |
| LITEONIT                    | 2         | 2      | 1.68%   |
| HGST                        | 2         | 2      | 1.68%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.84%   |
| Phison Electronics          | 1         | 1      | 0.84%   |
| PHD 3.0                     | 1         | 1      | 0.84%   |
| NT-128                      | 1         | 1      | 0.84%   |
| LITEON                      | 1         | 1      | 0.84%   |
| Lenovo                      | 1         | 3      | 0.84%   |
| LaCie                       | 1         | 1      | 0.84%   |
| Kingston Technology Company | 1         | 2      | 0.84%   |
| KingDian                    | 1         | 1      | 0.84%   |
| Intenso                     | 1         | 2      | 0.84%   |
| HUAWEI                      | 1         | 1      | 0.84%   |
| Hitachi                     | 1         | 1      | 0.84%   |
| FORESEE                     | 1         | 1      | 0.84%   |
| A-DATA Technology           | 1         | 1      | 0.84%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Seagate Expansion 2TB                        | 3         | 2.38%   |
| WDC WD10JPVX-22JC3T0 1TB                     | 2         | 1.59%   |
| Toshiba MQ01ABF050 500GB                     | 2         | 1.59%   |
| SanDisk SD8SN8U128G1122 128GB SSD            | 2         | 1.59%   |
| SanDisk NVMe SSD Drive 1TB                   | 2         | 1.59%   |
| Samsung SSD 860 QVO 1TB                      | 2         | 1.59%   |
| Samsung MZVLW256HEHP-000L7 256GB             | 2         | 1.59%   |
| LITEONIT LMT-256L9M-11 MSATA 256GB SSD       | 2         | 1.59%   |
| WDC WDS250G2B0B-00YS70 250GB SSD             | 1         | 0.79%   |
| WDC WDS200T1X0E-00AFY0 2TB                   | 1         | 0.79%   |
| WDC WDS100T2G0A-00JH30 1TB SSD               | 1         | 0.79%   |
| WDC WD3200LPCX-00VHAT0 320GB                 | 1         | 0.79%   |
| WDC WD10SPZX-17Z10T0 1TB                     | 1         | 0.79%   |
| WDC WD10SPCX-60HWST0 1TB                     | 1         | 0.79%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB         | 1         | 0.79%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB         | 1         | 0.79%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB           | 1         | 0.79%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB         | 1         | 0.79%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 0.79%   |
| Toshiba THNSNJ256G8NY 256GB SSD              | 1         | 0.79%   |
| Toshiba THNSNJ128GCST 128GB SSD              | 1         | 0.79%   |
| Toshiba NVMe SSD Drive 512GB                 | 1         | 0.79%   |
| Toshiba MQ02ABD100H 1TB                      | 1         | 0.79%   |
| Toshiba MK7575GSX 752GB                      | 1         | 0.79%   |
| Toshiba MK6459GSXP 640GB                     | 1         | 0.79%   |
| Toshiba MK2555GSX 250GB                      | 1         | 0.79%   |
| Toshiba KXG60PNV2T04 NVMe KIOXIA 2048GB      | 1         | 0.79%   |
| Toshiba KXG50ZNV512G 512GB                   | 1         | 0.79%   |
| Toshiba KXG50ZNV256G 256GB                   | 1         | 0.79%   |
| SK hynix SKHynix_HFS001TEJ4X112N 1TB         | 1         | 0.79%   |
| SK hynix PC801 NVMe 1TB                      | 1         | 0.79%   |
| SK hynix PC711 HFS512GDE9X073N 512GB         | 1         | 0.79%   |
| SK hynix HFS128G39TND-N210A 128GB SSD        | 1         | 0.79%   |
| SK hynix HCG8e  64GB                         | 1         | 0.79%   |
| Seagate ST950042 0ASG 500GB                  | 1         | 0.79%   |
| Seagate ST9320423AS 320GB                    | 1         | 0.79%   |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 0.79%   |
| Seagate ST2000LM015-2E8174 2TB               | 1         | 0.79%   |
| Seagate ST1000LM049-2GH172 1TB               | 1         | 0.79%   |
| Seagate ST1000LM048-2E7172 1TB               | 1         | 0.79%   |

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
| Samsung Electronics | 15        | 22     | 31.91%  |
| SanDisk             | 6         | 7      | 12.77%  |
| Crucial             | 5         | 7      | 10.64%  |
| Kingston            | 3         | 5      | 6.38%   |
| WDC                 | 2         | 2      | 4.26%   |
| Toshiba             | 2         | 2      | 4.26%   |
| Micron Technology   | 2         | 3      | 4.26%   |
| LITEONIT            | 2         | 2      | 4.26%   |
| SK hynix            | 1         | 1      | 2.13%   |
| PHD 3.0             | 1         | 1      | 2.13%   |
| NT-128              | 1         | 1      | 2.13%   |
| LITEON              | 1         | 1      | 2.13%   |
| Lenovo              | 1         | 3      | 2.13%   |
| KingDian            | 1         | 1      | 2.13%   |
| Intenso             | 1         | 2      | 2.13%   |
| Intel               | 1         | 1      | 2.13%   |
| FORESEE             | 1         | 1      | 2.13%   |
| Apple               | 1         | 1      | 2.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 43        | 51     | 37.72%  |
| SSD     | 40        | 63     | 35.09%  |
| HDD     | 28        | 31     | 24.56%  |
| Unknown | 2         | 2      | 1.75%   |
| MMC     | 1         | 1      | 0.88%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 56        | 86     | 51.38%  |
| NVMe | 43        | 51     | 39.45%  |
| SAS  | 9         | 10     | 8.26%   |
| MMC  | 1         | 1      | 0.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 42        | 55     | 57.53%  |
| 0.51-1.0   | 25        | 31     | 34.25%  |
| 1.01-2.0   | 6         | 8      | 8.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 26        | 26.53%  |
| 101-250        | 19        | 19.39%  |
| 501-1000       | 18        | 18.37%  |
| 1001-2000      | 9         | 9.18%   |
| Unknown        | 6         | 6.12%   |
| More than 3000 | 5         | 5.1%    |
| 1-20           | 5         | 5.1%    |
| 51-100         | 5         | 5.1%    |
| 2001-3000      | 3         | 3.06%   |
| 21-50          | 2         | 2.04%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 34        | 34.69%  |
| 21-50     | 14        | 14.29%  |
| 101-250   | 14        | 14.29%  |
| 251-500   | 9         | 9.18%   |
| 501-1000  | 8         | 8.16%   |
| 51-100    | 8         | 8.16%   |
| Unknown   | 6         | 6.12%   |
| 2001-3000 | 3         | 3.06%   |
| 1001-2000 | 2         | 2.04%   |

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
| Works    | 49        | 65     | 49%     |
| Detected | 46        | 78     | 46%     |
| Malfunc  | 5         | 5      | 5%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 63        | 56.25%  |
| Samsung Electronics          | 14        | 12.5%   |
| SanDisk                      | 9         | 8.04%   |
| AMD                          | 7         | 6.25%   |
| Kingston Technology Company  | 5         | 4.46%   |
| Toshiba America Info Systems | 4         | 3.57%   |
| SK hynix                     | 3         | 2.68%   |
| Apple                        | 2         | 1.79%   |
| Union Memory (Shenzhen)      | 1         | 0.89%   |
| Phison Electronics           | 1         | 0.89%   |
| Micron/Crucial Technology    | 1         | 0.89%   |
| Marvell Technology Group     | 1         | 0.89%   |
| ADATA Technology             | 1         | 0.89%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 8         | 6.96%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 7         | 6.09%   |
| Intel Volume Management Device NVMe RAID Controller                            | 6         | 5.22%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 5         | 4.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 4.35%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 4.35%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 5         | 4.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 4.35%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 3.48%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 3.48%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 4         | 3.48%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 3         | 2.61%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 2.61%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 2.61%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 3         | 2.61%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 2.61%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 2.61%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 2.61%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 2.61%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 1.74%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 2         | 1.74%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.74%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 1.74%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 x2 NVMe SSD 128GB, 256GB                | 1         | 0.87%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 1         | 0.87%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 1         | 0.87%   |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                              | 1         | 0.87%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 1         | 0.87%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1         | 0.87%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1         | 0.87%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 1         | 0.87%   |
| Kingston Company OM8SEP4 Design-In PCIe 4 NVMe SSD (TLC) (DRAM-less)           | 1         | 0.87%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 1         | 0.87%   |
| Kingston Company NV2 NVMe SSD SM2267XT (DRAM-less)                             | 1         | 0.87%   |
| Kingston Company KC2000/KC2500 NVMe SSD SM2262EN                               | 1         | 0.87%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                                 | 1         | 0.87%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 1         | 0.87%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                     | 1         | 0.87%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 0.87%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 1         | 0.87%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 59        | 51.75%  |
| NVMe | 43        | 37.72%  |
| RAID | 11        | 9.65%   |
| IDE  | 1         | 0.88%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 78        | 84.78%  |
| AMD    | 14        | 15.22%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 4         | 4.35%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 3         | 3.26%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 3.26%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 3         | 3.26%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 2         | 2.17%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 2         | 2.17%   |
| Intel Core i7-4702HQ CPU @ 2.20GHz          | 2         | 2.17%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 2.17%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 2         | 2.17%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 2         | 2.17%   |
| Intel 12th Gen Core i7-12700H               | 2         | 2.17%   |
| AMD Ryzen 9 5900HX with Radeon Graphics     | 2         | 2.17%   |
| AMD Ryzen 5 4600H with Radeon Graphics      | 2         | 2.17%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 1.09%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 1.09%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 1         | 1.09%   |
| Intel Pentium CPU P6000 @ 1.87GHz           | 1         | 1.09%   |
| Intel Pentium CPU 987 @ 1.50GHz             | 1         | 1.09%   |
| Intel Core m5-6Y54 CPU @ 1.10GHz            | 1         | 1.09%   |
| Intel Core M-5Y71 CPU @ 1.20GHz             | 1         | 1.09%   |
| Intel Core i9-9880H CPU @ 2.30GHz           | 1         | 1.09%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 1.09%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 1.09%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 1.09%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 1.09%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 1.09%   |
| Intel Core i7-4712MQ CPU @ 2.30GHz          | 1         | 1.09%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz          | 1         | 1.09%   |
| Intel Core i7-3940XM CPU @ 3.00GHz          | 1         | 1.09%   |
| Intel Core i7-3840QM CPU @ 2.80GHz          | 1         | 1.09%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 1.09%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 1.09%   |
| Intel Core i5-8257U CPU @ 1.40GHz           | 1         | 1.09%   |
| Intel Core i5-7360U CPU @ 2.30GHz           | 1         | 1.09%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 1.09%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz          | 1         | 1.09%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1         | 1.09%   |
| Intel Core i5-4330M CPU @ 2.80GHz           | 1         | 1.09%   |
| Intel Core i5-4250U CPU @ 1.30GHz           | 1         | 1.09%   |
| Intel Core i5-4210M CPU @ 2.60GHz           | 1         | 1.09%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 23        | 25%     |
| Intel Core i5           | 22        | 23.91%  |
| Other                   | 14        | 15.22%  |
| Intel Core i3           | 6         | 6.52%   |
| Intel Celeron           | 4         | 4.35%   |
| AMD Ryzen 7             | 4         | 4.35%   |
| AMD Ryzen 5             | 4         | 4.35%   |
| Intel Pentium Dual-Core | 2         | 2.17%   |
| Intel Pentium           | 2         | 2.17%   |
| AMD Ryzen 9             | 2         | 2.17%   |
| AMD Ryzen 5 PRO         | 2         | 2.17%   |
| Intel Pentium Silver    | 1         | 1.09%   |
| Intel Core m5           | 1         | 1.09%   |
| Intel Core M            | 1         | 1.09%   |
| Intel Core i9           | 1         | 1.09%   |
| Intel Atom              | 1         | 1.09%   |
| AMD Ryzen 7 PRO         | 1         | 1.09%   |
| AMD E2                  | 1         | 1.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 32        | 34.78%  |
| 2      | 32        | 34.78%  |
| 8      | 10        | 10.87%  |
| 6      | 10        | 10.87%  |
| 16     | 3         | 3.26%   |
| 14     | 2         | 2.17%   |
| 1      | 2         | 2.17%   |
| 10     | 1         | 1.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 92        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 79        | 85.87%  |
| 1      | 13        | 14.13%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 91        | 98.91%  |
| 32-bit         | 1         | 1.09%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 29        | 29.9%   |
| 0x306c3    | 8         | 8.25%   |
| 0x806c1    | 5         | 5.15%   |
| 0x206a7    | 5         | 5.15%   |
| 0x806ea    | 4         | 4.12%   |
| 0x40651    | 4         | 4.12%   |
| 0x20655    | 4         | 4.12%   |
| 0x806eb    | 3         | 3.09%   |
| 0x706a1    | 3         | 3.09%   |
| 0x406e3    | 3         | 3.09%   |
| 0x906ea    | 2         | 2.06%   |
| 0x906e9    | 2         | 2.06%   |
| 0x806ec    | 2         | 2.06%   |
| 0x806d1    | 2         | 2.06%   |
| 0x306d4    | 2         | 2.06%   |
| 0x306a9    | 2         | 2.06%   |
| 0x1067a    | 2         | 2.06%   |
| 0x0a50000c | 2         | 2.06%   |
| 0x08600106 | 2         | 2.06%   |
| 0x906ed    | 1         | 1.03%   |
| 0x806e9    | 1         | 1.03%   |
| 0x20652    | 1         | 1.03%   |
| 0x106c2    | 1         | 1.03%   |
| 0x0a704101 | 1         | 1.03%   |
| 0x0a50000d | 1         | 1.03%   |
| 0x08608102 | 1         | 1.03%   |
| 0x08600104 | 1         | 1.03%   |
| 0x08600103 | 1         | 1.03%   |
| 0x08108102 | 1         | 1.03%   |
| 0x06006705 | 1         | 1.03%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 21        | 22.83%  |
| Haswell          | 12        | 13.04%  |
| Zen 2            | 6         | 6.52%   |
| TigerLake        | 6         | 6.52%   |
| SandyBridge      | 6         | 6.52%   |
| Westmere         | 5         | 5.43%   |
| Skylake          | 5         | 5.43%   |
| Zen 3            | 4         | 4.35%   |
| IvyBridge        | 4         | 4.35%   |
| Alderlake Hybrid | 4         | 4.35%   |
| Unknown          | 4         | 4.35%   |
| Goldmont plus    | 3         | 3.26%   |
| Broadwell        | 3         | 3.26%   |
| Penryn           | 2         | 2.17%   |
| Icelake          | 2         | 2.17%   |
| Zen+             | 1         | 1.09%   |
| Goldmont         | 1         | 1.09%   |
| Excavator        | 1         | 1.09%   |
| CometLake        | 1         | 1.09%   |
| Bonnell          | 1         | 1.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 73        | 58.87%  |
| Nvidia | 31        | 25%     |
| AMD    | 20        | 16.13%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 8         | 6.4%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 6         | 4.8%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 6         | 4.8%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 6         | 4.8%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]             | 6         | 4.8%    |
| Intel UHD Graphics 620                                                    | 5         | 4%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 5         | 4%      |
| Intel Haswell-ULT Integrated Graphics Controller                          | 4         | 3.2%    |
| Intel 3rd Gen Core processor Graphics Controller                          | 4         | 3.2%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 4         | 3.2%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 3         | 2.4%    |
| Nvidia GA107GLM [RTX A1000 Laptop GPU]                                    | 3         | 2.4%    |
| Intel Skylake GT2 [HD Graphics 520]                                       | 3         | 2.4%    |
| Intel Alder Lake-HX GT1 [UHD Graphics 770]                                | 3         | 2.4%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 1.6%    |
| Nvidia GP108M [GeForce MX250]                                             | 2         | 1.6%    |
| Nvidia GP108M [GeForce MX150]                                             | 2         | 1.6%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 2         | 1.6%    |
| Nvidia GK107GLM [Quadro K1100M]                                           | 2         | 1.6%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 2         | 1.6%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 2         | 1.6%    |
| Intel HD Graphics 630                                                     | 2         | 1.6%    |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.6%    |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                 | 2         | 1.6%    |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                             | 1         | 0.8%    |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                     | 1         | 0.8%    |
| Nvidia GT215M [GeForce GTS 250M]                                          | 1         | 0.8%    |
| Nvidia GM108M [GeForce MX110]                                             | 1         | 0.8%    |
| Nvidia GM108M [GeForce 840M]                                              | 1         | 0.8%    |
| Nvidia GM107M [GeForce GTX 950M]                                          | 1         | 0.8%    |
| Nvidia GM107M [GeForce GTX 850M]                                          | 1         | 0.8%    |
| Nvidia GK104M [GeForce GTX 680M]                                          | 1         | 0.8%    |
| Nvidia GF108M [GeForce GT 520M]                                           | 1         | 0.8%    |
| Nvidia GF108M [GeForce GT 415M]                                           | 1         | 0.8%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 1         | 0.8%    |
| Nvidia GA107GLM [RTX A2000 Mobile]                                        | 1         | 0.8%    |
| Nvidia G98M [GeForce G 105M]                                              | 1         | 0.8%    |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                       | 1         | 0.8%    |
| Intel Raptor Lake-P [Iris Xe Graphics]                                    | 1         | 0.8%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 0.8%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 42        | 45.65%  |
| Intel + Nvidia | 27        | 29.35%  |
| 1 x AMD        | 16        | 17.39%  |
| 1 x Nvidia     | 3         | 3.26%   |
| Intel + AMD    | 3         | 3.26%   |
| 2 x AMD        | 1         | 1.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 78        | 83.87%  |
| Proprietary | 13        | 13.98%  |
| Unknown     | 2         | 2.15%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 64        | 68.82%  |
| 3.01-4.0   | 10        | 10.75%  |
| 0.01-0.5   | 8         | 8.6%    |
| 1.01-2.0   | 6         | 6.45%   |
| 0.51-1.0   | 5         | 5.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 22        | 20.75%  |
| LG Display              | 16        | 15.09%  |
| Samsung Electronics     | 13        | 12.26%  |
| AU Optronics            | 11        | 10.38%  |
| BOE                     | 9         | 8.49%   |
| Sharp                   | 6         | 5.66%   |
| Apple                   | 5         | 4.72%   |
| Hewlett-Packard         | 4         | 3.77%   |
| AOC                     | 4         | 3.77%   |
| Chi Mei Optoelectronics | 3         | 2.83%   |
| Iiyama                  | 2         | 1.89%   |
| CSO                     | 2         | 1.89%   |
| Videoseven              | 1         | 0.94%   |
| Sony                    | 1         | 0.94%   |
| Philips                 | 1         | 0.94%   |
| PANDA                   | 1         | 0.94%   |
| Medion                  | 1         | 0.94%   |
| Lenovo                  | 1         | 0.94%   |
| Goldstar                | 1         | 0.94%   |
| BenQ                    | 1         | 0.94%   |
| Aosiman                 | 1         | 0.94%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 2         | 1.85%   |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch               | 2         | 1.85%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 2         | 1.85%   |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 355x199mm 16.0-inch      | 2         | 1.85%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 2         | 1.85%   |
| AOC 2250W AOC2250 1920x1080 477x268mm 21.5-inch                       | 2         | 1.85%   |
| Videoseven L27ADS IGM2700 1920x1080 598x336mm 27.0-inch               | 1         | 0.93%   |
| Sony LCD Monitor SNY05FA 1366x768 340x190mm 15.3-inch                 | 1         | 0.93%   |
| Sharp LCD Monitor SHP1516 3840x2400 336x210mm 15.6-inch               | 1         | 0.93%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch               | 1         | 0.93%   |
| Samsung Electronics S27D390 SAM0B67 1920x1080 598x336mm 27.0-inch     | 1         | 0.93%   |
| Samsung Electronics Odyssey G8 SAM7231 3440x1440 809x354mm 34.8-inch  | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SEC444E 1600x900 310x174mm 14.0-inch  | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SDC5844 1920x1080 344x194mm 15.5-inch | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 293x165mm 13.2-inch | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SDC4181 2880x1800 302x189mm 14.0-inch | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch  | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SAM0B60 1920x1080 887x500mm 40.1-inch | 1         | 0.93%   |
| Samsung Electronics C27R50x SAM0F9D 1920x1080 598x336mm 27.0-inch     | 1         | 0.93%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1         | 0.93%   |
| Philips PHL 346B1C PHL095C 3440x1440 797x334mm 34.0-inch              | 1         | 0.93%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 0.93%   |
| Medion 42FPDEUDA1 MED222E 1920x1080                                   | 1         | 0.93%   |
| LG Display LP156WH2-TLE1 LGDCF01 1366x768 344x194mm 15.5-inch         | 1         | 0.93%   |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch          | 1         | 0.93%   |
| LG Display LCD Monitor LGD05EE 2560x1440 309x174mm 14.0-inch          | 1         | 0.93%   |
| LG Display LCD Monitor LGD05CE 1920x1080 344x194mm 15.5-inch          | 1         | 0.93%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch          | 1         | 0.93%   |
| LG Display LCD Monitor LGD0553 1920x1080 309x174mm 14.0-inch          | 1         | 0.93%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 0.93%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 1         | 0.93%   |
| LG Display LCD Monitor LGD046B 1366x768 344x194mm 15.5-inch           | 1         | 0.93%   |
| LG Display LCD Monitor LGD040A 1920x1080 309x175mm 14.0-inch          | 1         | 0.93%   |
| LG Display LCD Monitor LGD03B8 1366x768 310x174mm 14.0-inch           | 1         | 0.93%   |
| LG Display LCD Monitor LGD03B3 1366x768 310x174mm 14.0-inch           | 1         | 0.93%   |
| LG Display LCD Monitor LGD038C 1366x768 256x144mm 11.6-inch           | 1         | 0.93%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 44        | 45.83%  |
| 1366x768 (WXGA)    | 16        | 16.67%  |
| 2880x1800          | 4         | 4.17%   |
| 1600x900 (HD+)     | 4         | 4.17%   |
| 3840x2160 (4K)     | 3         | 3.13%   |
| 3200x1800 (QHD+)   | 3         | 3.13%   |
| 2560x1440 (QHD)    | 3         | 3.13%   |
| 1920x1200 (WUXGA)  | 3         | 3.13%   |
| 3440x1440          | 2         | 2.08%   |
| 2560x1600          | 2         | 2.08%   |
| 1440x900 (WXGA+)   | 2         | 2.08%   |
| 1280x800 (WXGA)    | 2         | 2.08%   |
| 3840x2400          | 1         | 1.04%   |
| 3072x1920          | 1         | 1.04%   |
| 2520x1680          | 1         | 1.04%   |
| 2256x1504          | 1         | 1.04%   |
| 2160x1440          | 1         | 1.04%   |
| 1680x1050 (WSXGA+) | 1         | 1.04%   |
| 1360x768           | 1         | 1.04%   |
| 1280x1024 (SXGA)   | 1         | 1.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 34        | 31.78%  |
| 14      | 17        | 15.89%  |
| 13      | 16        | 14.95%  |
| 17      | 10        | 9.35%   |
| 16      | 8         | 7.48%   |
| 27      | 4         | 3.74%   |
| 21      | 4         | 3.74%   |
| 34      | 2         | 1.87%   |
| 24      | 2         | 1.87%   |
| 59      | 1         | 0.93%   |
| 47      | 1         | 0.93%   |
| 40      | 1         | 0.93%   |
| 33      | 1         | 0.93%   |
| 28      | 1         | 0.93%   |
| 23      | 1         | 0.93%   |
| 22      | 1         | 0.93%   |
| 18      | 1         | 0.93%   |
| 11      | 1         | 0.93%   |
| Unknown | 1         | 0.93%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 63        | 59.43%  |
| 351-400     | 11        | 10.38%  |
| 201-300     | 11        | 10.38%  |
| 501-600     | 7         | 6.6%    |
| 401-500     | 6         | 5.66%   |
| 801-900     | 2         | 1.89%   |
| 701-800     | 2         | 1.89%   |
| 1001-1500   | 2         | 1.89%   |
| 601-700     | 1         | 0.94%   |
| Unknown     | 1         | 0.94%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 69        | 74.19%  |
| 16/10 | 18        | 19.35%  |
| 3/2   | 3         | 3.23%   |
| 21/9  | 2         | 2.15%   |
| 5/4   | 1         | 1.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 34        | 31.78%  |
| 81-90          | 27        | 25.23%  |
| 201-250        | 7         | 6.54%   |
| 121-130        | 7         | 6.54%   |
| 111-120        | 7         | 6.54%   |
| 71-80          | 6         | 5.61%   |
| 351-500        | 4         | 3.74%   |
| 301-350        | 4         | 3.74%   |
| 141-150        | 2         | 1.87%   |
| 131-140        | 2         | 1.87%   |
| 501-1000       | 2         | 1.87%   |
| More than 1000 | 1         | 0.93%   |
| 51-60          | 1         | 0.93%   |
| 251-300        | 1         | 0.93%   |
| 91-100         | 1         | 0.93%   |
| Unknown        | 1         | 0.93%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 44        | 41.9%   |
| 101-120       | 27        | 25.71%  |
| 161-240       | 13        | 12.38%  |
| 51-100        | 10        | 9.52%   |
| More than 240 | 8         | 7.62%   |
| 1-50          | 2         | 1.9%    |
| Unknown       | 1         | 0.95%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 73        | 77.66%  |
| 2     | 16        | 17.02%  |
| 0     | 3         | 3.19%   |
| 3     | 2         | 2.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 62        | 42.47%  |
| Realtek Semiconductor           | 38        | 26.03%  |
| Qualcomm Atheros                | 16        | 10.96%  |
| Broadcom                        | 10        | 6.85%   |
| MediaTek                        | 4         | 2.74%   |
| Sierra Wireless                 | 3         | 2.05%   |
| Marvell Technology Group        | 3         | 2.05%   |
| DisplayLink                     | 2         | 1.37%   |
| Broadcom Limited                | 2         | 1.37%   |
| Shenzhen Goodix Technology      | 1         | 0.68%   |
| Qualcomm Atheros Communications | 1         | 0.68%   |
| Lenovo                          | 1         | 0.68%   |
| JMicron Technology              | 1         | 0.68%   |
| Huawei Technologies             | 1         | 0.68%   |
| ASIX Electronics                | 1         | 0.68%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 26        | 14.61%  |
| Intel Wi-Fi 6 AX200                                                            | 9         | 5.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 6         | 3.37%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 5         | 2.81%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 4         | 2.25%   |
| Intel Wireless 8265 / 8275                                                     | 4         | 2.25%   |
| Intel Wireless 8260                                                            | 4         | 2.25%   |
| Intel Wireless 7260                                                            | 4         | 2.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4         | 2.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 3         | 1.69%   |
| Intel Wireless 3160                                                            | 3         | 1.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 3         | 1.69%   |
| Intel Alder Lake-S PCH CNVi WiFi                                               | 3         | 1.69%   |
| Sierra Wireless EM7305 Modem                                                   | 2         | 1.12%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 2         | 1.12%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 1.12%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2         | 1.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 2         | 1.12%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 2         | 1.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 2         | 1.12%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                  | 2         | 1.12%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.12%   |
| Intel Wireless 3165                                                            | 2         | 1.12%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                      | 2         | 1.12%   |
| Intel Wi-Fi 6 AX201                                                            | 2         | 1.12%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                        | 2         | 1.12%   |
| Intel Tiger Lake PCH CNVi WiFi                                                 | 2         | 1.12%   |
| Intel Ethernet Connection I219-V                                               | 2         | 1.12%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 1.12%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 1.12%   |
| Intel Ethernet Connection (17) I219-LM                                         | 2         | 1.12%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 2         | 1.12%   |
| Intel Centrino Advanced-N 6235                                                 | 2         | 1.12%   |
| Intel Alder Lake-P PCH CNVi WiFi                                               | 2         | 1.12%   |
| DisplayLink Dell D3100 Docking Station                                         | 2         | 1.12%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 1.12%   |
| Broadcom BCM4331 802.11a/b/g/n                                                 | 2         | 1.12%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 2         | 1.12%   |
| Sierra Wireless EM7455                                                         | 1         | 0.56%   |
| Shenzhen Goodix Unknow device                                                  | 1         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 60        | 61.22%  |
| Qualcomm Atheros                | 14        | 14.29%  |
| Realtek Semiconductor           | 7         | 7.14%   |
| Broadcom                        | 7         | 7.14%   |
| MediaTek                        | 4         | 4.08%   |
| Sierra Wireless                 | 3         | 3.06%   |
| Broadcom Limited                | 2         | 2.04%   |
| Qualcomm Atheros Communications | 1         | 1.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 9         | 9.18%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 5         | 5.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 4         | 4.08%   |
| Intel Wireless 8265 / 8275                                     | 4         | 4.08%   |
| Intel Wireless 8260                                            | 4         | 4.08%   |
| Intel Wireless 7260                                            | 4         | 4.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 3.06%   |
| Intel Wireless 3160                                            | 3         | 3.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 3.06%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 3         | 3.06%   |
| Sierra Wireless EM7305 Modem                                   | 2         | 2.04%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 2.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 2         | 2.04%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 2.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 2.04%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 2.04%   |
| Intel Wireless 3165                                            | 2         | 2.04%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 2         | 2.04%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 2.04%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 2         | 2.04%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 2.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 2.04%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 2.04%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 2.04%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 2         | 2.04%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 2.04%   |
| Sierra Wireless EM7455                                         | 1         | 1.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.02%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 1.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 1.02%   |
| Qualcomm Atheros AR9271 802.11n                                | 1         | 1.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 1.02%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 1.02%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 1.02%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 1         | 1.02%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter            | 1         | 1.02%   |
| Intel WiMAX/WiFi Link 5150                                     | 1         | 1.02%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 1         | 1.02%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 1         | 1.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 1.02%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 35        | 46.67%  |
| Intel                    | 22        | 29.33%  |
| Qualcomm Atheros         | 5         | 6.67%   |
| Broadcom                 | 5         | 6.67%   |
| Marvell Technology Group | 3         | 4%      |
| DisplayLink              | 2         | 2.67%   |
| Lenovo                   | 1         | 1.33%   |
| JMicron Technology       | 1         | 1.33%   |
| ASIX Electronics         | 1         | 1.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 26        | 33.77%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 6         | 7.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4         | 5.19%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 2.6%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2         | 2.6%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 2.6%    |
| Intel Ethernet Connection I219-V                                               | 2         | 2.6%    |
| Intel Ethernet Connection I217-LM                                              | 2         | 2.6%    |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 2.6%    |
| Intel Ethernet Connection (17) I219-LM                                         | 2         | 2.6%    |
| DisplayLink Dell D3100 Docking Station                                         | 2         | 2.6%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 2.6%    |
| Realtek Killer E2600 GbE Controller                                            | 1         | 1.3%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 1.3%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 1.3%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 1.3%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 1.3%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 1.3%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 1.3%    |
| Lenovo ThinkPad Lan                                                            | 1         | 1.3%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 1.3%    |
| Intel WiMAX Connection 2400m                                                   | 1         | 1.3%    |
| Intel Ethernet Connection I219-LM                                              | 1         | 1.3%    |
| Intel Ethernet Connection I217-V                                               | 1         | 1.3%    |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 1.3%    |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 1.3%    |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 1.3%    |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 1.3%    |
| Intel Ethernet Connection (17) I219-V                                          | 1         | 1.3%    |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 1.3%    |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 1.3%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 1         | 1.3%    |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 1         | 1.3%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 1         | 1.3%    |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 1.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 93        | 56.02%  |
| Ethernet | 70        | 42.17%  |
| Unknown  | 2         | 1.2%    |
| Modem    | 1         | 0.6%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 78        | 78%     |
| Ethernet | 22        | 22%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 62        | 67.39%  |
| 1     | 28        | 30.43%  |
| 3     | 2         | 2.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 68        | 73.12%  |
| Yes  | 25        | 26.88%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 53        | 65.43%  |
| Foxconn / Hon Hai               | 8         | 9.88%   |
| Qualcomm Atheros Communications | 4         | 4.94%   |
| Realtek                         | 3         | 3.7%    |
| Apple                           | 3         | 3.7%    |
| Realtek Semiconductor           | 2         | 2.47%   |
| Lite-On Technology              | 2         | 2.47%   |
| IMC Networks                    | 2         | 2.47%   |
| Hewlett-Packard                 | 2         | 2.47%   |
| Toshiba                         | 1         | 1.23%   |
| Micro Star International        | 1         | 1.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                                                               | 9         | 11.11%  |
| Intel Bluetooth wireless interface                                                  | 8         | 9.88%   |
| Intel Bluetooth Device                                                              | 8         | 9.88%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 8         | 9.88%   |
| Intel AX211 Bluetooth                                                               | 6         | 7.41%   |
| Intel AX201 Bluetooth                                                               | 6         | 7.41%   |
| Realtek Bluetooth Radio                                                             | 3         | 3.7%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 3.7%    |
| Realtek Bluetooth Radio                                                             | 2         | 2.47%   |
| Lite-On Bluetooth Device                                                            | 2         | 2.47%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 2.47%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 2.47%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 2.47%   |
| Intel AX210 Bluetooth                                                               | 2         | 2.47%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 2.47%   |
| Apple Bluetooth Host Controller                                                     | 2         | 2.47%   |
| Toshiba Bluetooth Device                                                            | 1         | 1.23%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.23%   |
| Micro Star International Motorola Bluetooth 2.1+EDR Device                          | 1         | 1.23%   |
| IMC Networks Wireless_Device                                                        | 1         | 1.23%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.23%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 1.23%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 1         | 1.23%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.23%   |
| Foxconn / Hon Hai BT                                                                | 1         | 1.23%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth                                     | 1         | 1.23%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 1.23%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 1         | 1.23%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 1.23%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 1.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 79        | 69.3%   |
| AMD                 | 17        | 14.91%  |
| Nvidia              | 11        | 9.65%   |
| Hewlett-Packard     | 2         | 1.75%   |
| Logitech            | 1         | 0.88%   |
| Lenovo              | 1         | 0.88%   |
| C-Media Electronics | 1         | 0.88%   |
| Bose                | 1         | 0.88%   |
| Apple               | 1         | 0.88%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 12        | 8.45%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 11        | 7.75%   |
| Intel Sunrise Point-LP HD Audio                                            | 10        | 7.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8         | 5.63%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8         | 5.63%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 7         | 4.93%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 4.23%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 4.23%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 3.52%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 3.52%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 3.52%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 2.82%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 2.82%   |
| Nvidia Audio device                                                        | 3         | 2.11%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 2.11%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 2.11%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 2.11%   |
| Intel Alder Lake-S HD Audio Controller                                     | 3         | 2.11%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.41%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 1.41%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 1.41%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.41%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 1.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 1.41%   |
| Hewlett-Packard USB Audio                                                  | 2         | 1.41%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2         | 1.41%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.7%    |
| Nvidia High Definition Audio Controller                                    | 1         | 0.7%    |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.7%    |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 0.7%    |
| Logitech Headset H390                                                      | 1         | 0.7%    |
| Lenovo ThinkPad Dock USB Audio                                             | 1         | 0.7%    |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 1         | 0.7%    |
| Intel Raptor Lake-P/U/H cAVS                                               | 1         | 0.7%    |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 0.7%    |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.7%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.7%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 0.7%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1         | 0.7%    |
| Bose Revolve SoundLink                                                     | 1         | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 26        | 41.94%  |
| SK hynix            | 14        | 22.58%  |
| Micron Technology   | 7         | 11.29%  |
| Unknown             | 4         | 6.45%   |
| Crucial             | 4         | 6.45%   |
| Kingston            | 2         | 3.23%   |
| A-DATA Technology   | 2         | 3.23%   |
| Wilk                | 1         | 1.61%   |
| Unknown (ABCD)      | 1         | 1.61%   |
| Timetec             | 1         | 1.61%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 4.48%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 2         | 2.99%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.99%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 2.99%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 2.99%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 2.99%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 2.99%   |
| Wilk RAM GR3200S464L22S/16G 16GB SODIMM DDR4 3200MT/s            | 1         | 1.49%   |
| Unknown RAM Module 4GB SODIMM LPDDR3 1600MT/s                    | 1         | 1.49%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 1.49%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 1.49%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 1         | 1.49%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 1.49%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 1.49%   |
| Timetec RAM SD3-1333 8GB SODIMM DDR3 1333MT/s                    | 1         | 1.49%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s          | 1         | 1.49%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.49%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 1.49%   |
| SK hynix RAM HMCG88MEBSA092N 32GB SODIMM DDR5 4800MT/s           | 1         | 1.49%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.49%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 1.49%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.49%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 1.49%   |
| SK hynix RAM HMA81GS6MFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 1.49%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 1         | 1.49%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 1         | 1.49%   |
| SK hynix RAM H58G66BK7BX067 8GB Row Of Chips LPDDR5 7500MT/s     | 1         | 1.49%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 1.49%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.49%   |
| Samsung RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 1.49%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                  | 1         | 1.49%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 1         | 1.49%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 1         | 1.49%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.49%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.49%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 1         | 1.49%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 1.49%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.49%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 1         | 1.49%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 1         | 1.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 29        | 50%     |
| DDR3   | 16        | 27.59%  |
| LPDDR3 | 4         | 6.9%    |
| DDR5   | 4         | 6.9%    |
| LPDDR5 | 2         | 3.45%   |
| DDR2   | 2         | 3.45%   |
| LPDDR4 | 1         | 1.72%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 51        | 87.93%  |
| Row Of Chips | 7         | 12.07%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 27        | 42.19%  |
| 4096  | 15        | 23.44%  |
| 16384 | 12        | 18.75%  |
| 2048  | 5         | 7.81%   |
| 32768 | 4         | 6.25%   |
| 1024  | 1         | 1.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 15        | 24.59%  |
| 3200    | 14        | 22.95%  |
| 1600    | 11        | 18.03%  |
| 2400    | 5         | 8.2%    |
| 4800    | 4         | 6.56%   |
| 2133    | 4         | 6.56%   |
| Unknown | 3         | 4.92%   |
| 7500    | 1         | 1.64%   |
| 6400    | 1         | 1.64%   |
| 1334    | 1         | 1.64%   |
| 1333    | 1         | 1.64%   |
| 1067    | 1         | 1.64%   |

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
| Chicony Electronics                    | 23        | 27.06%  |
| Microdia                               | 11        | 12.94%  |
| IMC Networks                           | 10        | 11.76%  |
| Bison Electronics                      | 5         | 5.88%   |
| Samsung Electronics                    | 4         | 4.71%   |
| Realtek Semiconductor                  | 4         | 4.71%   |
| Quanta                                 | 4         | 4.71%   |
| Ricoh                                  | 3         | 3.53%   |
| Luxvisions Innotech Limited            | 3         | 3.53%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.53%   |
| Apple                                  | 3         | 3.53%   |
| Syntek                                 | 2         | 2.35%   |
| Sunplus Innovation Technology          | 2         | 2.35%   |
| Alcor Micro                            | 2         | 2.35%   |
| Silicon Motion                         | 1         | 1.18%   |
| ShineTech                              | 1         | 1.18%   |
| Logitech                               | 1         | 1.18%   |
| ALi                                    | 1         | 1.18%   |
| Acer                                   | 1         | 1.18%   |
| Unknown                                | 1         | 1.18%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                    | 5         | 5.88%   |
| IMC Networks USB2.0 HD UVC WebCam                | 5         | 5.88%   |
| Samsung Galaxy series, misc. (MTP mode)          | 4         | 4.71%   |
| IMC Networks Integrated Camera                   | 3         | 3.53%   |
| Chicony Integrated Camera                        | 3         | 3.53%   |
| Realtek Integrated_Webcam_HD                     | 2         | 2.35%   |
| Quanta HD User Facing                            | 2         | 2.35%   |
| Microdia Integrated_Webcam_FHD                   | 2         | 2.35%   |
| Microdia Integrated Webcam                       | 2         | 2.35%   |
| Luxvisions Innotech Limited HP HD Camera         | 2         | 2.35%   |
| Chicony Integrated IR Camera                     | 2         | 2.35%   |
| Chicony Integrated Camera (1280x720@30)          | 2         | 2.35%   |
| Chicony HP HD Camera                             | 2         | 2.35%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera | 2         | 2.35%   |
| Apple FaceTime HD Camera                         | 2         | 2.35%   |
| Syntek USB2.0 Camera                             | 1         | 1.18%   |
| Syntek Integrated Camera                         | 1         | 1.18%   |
| Sunplus Laptop Integrated WebCam HD              | 1         | 1.18%   |
| Sunplus HP HD Webcam [Fixed]                     | 1         | 1.18%   |
| Silicon Motion Web Camera                        | 1         | 1.18%   |
| ShineTech HD Camera                              | 1         | 1.18%   |
| Ricoh USB2.0 Camera                              | 1         | 1.18%   |
| Ricoh Sony Visual Communication Camera           | 1         | 1.18%   |
| Ricoh Sony Vaio Integrated Webcam                | 1         | 1.18%   |
| Realtek Integrated Webcam_HD                     | 1         | 1.18%   |
| Realtek HP Truevision HD                         | 1         | 1.18%   |
| Quanta HP Wide Vision HD Camera                  | 1         | 1.18%   |
| Quanta HP Webcam                                 | 1         | 1.18%   |
| Microdia Webcam Vitade AF                        | 1         | 1.18%   |
| Microdia Webcam                                  | 1         | 1.18%   |
| Luxvisions Innotech Limited HP 5MP Camera        | 1         | 1.18%   |
| Logitech HD Pro Webcam C920                      | 1         | 1.18%   |
| IMC Networks Integrated Webcam                   | 1         | 1.18%   |
| IMC Networks HD Camera                           | 1         | 1.18%   |
| Chicony USB2.0 VGA UVC WebCam                    | 1         | 1.18%   |
| Chicony USB2.0 HD UVC WebCam                     | 1         | 1.18%   |
| Chicony TOSHIBA Web Camera - HD                  | 1         | 1.18%   |
| Chicony ThinkPad T490 Webcam                     | 1         | 1.18%   |
| Chicony Integrated HP HD Webcam                  | 1         | 1.18%   |
| Chicony HP Wide Vision HD Camera                 | 1         | 1.18%   |

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


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Broadcom                 | 4         | 33.33%  |
| Alcor Micro              | 4         | 33.33%  |
| Gemalto (was Gemplus)    | 3         | 25%     |
| Reiner SCT Kartensysteme | 1         | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 33.33%  |
| Gemalto (was Gemplus) Prox SU USB PC Link Reader                             | 2         | 16.67%  |
| Broadcom 58200                                                               | 2         | 16.67%  |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 8.33%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 8.33%   |
| Broadcom 5880                                                                | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 50        | 52.63%  |
| 1     | 30        | 31.58%  |
| 2     | 13        | 13.68%  |
| 3     | 2         | 2.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 22        | 36.67%  |
| Graphics card            | 12        | 20%     |
| Chipcard                 | 7         | 11.67%  |
| Net/wireless             | 4         | 6.67%   |
| Network                  | 3         | 5%      |
| Multimedia controller    | 3         | 5%      |
| Card reader              | 3         | 5%      |
| Communication controller | 2         | 3.33%   |
| Sound                    | 1         | 1.67%   |
| Net/ethernet             | 1         | 1.67%   |
| Camera                   | 1         | 1.67%   |
| Bluetooth                | 1         | 1.67%   |

