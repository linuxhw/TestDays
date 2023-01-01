Linux in Sweden - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Sweden.

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

Total: 1307

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire V3-571G              | [273f6722e0](https://linux-hardware.org/?probe=273f6722e0) | Dec 31, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [270ba62d9d](https://linux-hardware.org/?probe=270ba62d9d) | Dec 31, 2022 |
| Lenovo        | Z70-80 80FG                 | [16419f6991](https://linux-hardware.org/?probe=16419f6991) | Dec 30, 2022 |
| Lenovo        | Z70-80 80FG                 | [4386242be1](https://linux-hardware.org/?probe=4386242be1) | Dec 30, 2022 |
| Valve         | Jupiter                     | [15c60654b3](https://linux-hardware.org/?probe=15c60654b3) | Dec 30, 2022 |
| Apple         | MacBookPro11,3              | [87d0f67d84](https://linux-hardware.org/?probe=87d0f67d84) | Dec 30, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [2ef0101186](https://linux-hardware.org/?probe=2ef0101186) | Dec 25, 2022 |
| Dell          | Latitude 3380               | [e4847d5b1f](https://linux-hardware.org/?probe=e4847d5b1f) | Dec 24, 2022 |
| HP            | EliteBook 840 G5            | [92f12e3ec7](https://linux-hardware.org/?probe=92f12e3ec7) | Dec 24, 2022 |
| MSI           | Katana GF66 11UE            | [b993283081](https://linux-hardware.org/?probe=b993283081) | Dec 22, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [92515d8a95](https://linux-hardware.org/?probe=92515d8a95) | Dec 21, 2022 |
| Schenker      | XMG APEX 15 MAX (E22)       | [6b46538fea](https://linux-hardware.org/?probe=6b46538fea) | Dec 21, 2022 |
| Dell          | Latitude 3380               | [808c693271](https://linux-hardware.org/?probe=808c693271) | Dec 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [4fbc0ddbd5](https://linux-hardware.org/?probe=4fbc0ddbd5) | Dec 20, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [ffa7e28596](https://linux-hardware.org/?probe=ffa7e28596) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [143d2059a6](https://linux-hardware.org/?probe=143d2059a6) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [888e6092a6](https://linux-hardware.org/?probe=888e6092a6) | Dec 15, 2022 |
| HP            | EliteBook 830 G6            | [5248ee7dbe](https://linux-hardware.org/?probe=5248ee7dbe) | Dec 15, 2022 |
| HP            | EliteBook 830 G7 Noteboo... | [3403282c8c](https://linux-hardware.org/?probe=3403282c8c) | Dec 15, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [bec79890c8](https://linux-hardware.org/?probe=bec79890c8) | Dec 15, 2022 |
| Dell          | Latitude E7240              | [c47fc4fadf](https://linux-hardware.org/?probe=c47fc4fadf) | Dec 14, 2022 |
| Insyde        | G0975                       | [1f4823542d](https://linux-hardware.org/?probe=1f4823542d) | Dec 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [4a3ac966fc](https://linux-hardware.org/?probe=4a3ac966fc) | Dec 13, 2022 |
| Dell          | Latitude 5430               | [b439d1e1a4](https://linux-hardware.org/?probe=b439d1e1a4) | Dec 12, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [4b0492b053](https://linux-hardware.org/?probe=4b0492b053) | Dec 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [ca7d835a38](https://linux-hardware.org/?probe=ca7d835a38) | Dec 11, 2022 |
| Google        | Orco                        | [40acd3207e](https://linux-hardware.org/?probe=40acd3207e) | Dec 10, 2022 |
| Google        | Orco                        | [9c369b40b3](https://linux-hardware.org/?probe=9c369b40b3) | Dec 10, 2022 |
| Lenovo        | ThinkPad T490s 20NX001KM... | [49f30d3eee](https://linux-hardware.org/?probe=49f30d3eee) | Dec 06, 2022 |
| ASUSTek       | VivoBook S13 X330UA         | [d01d1e9652](https://linux-hardware.org/?probe=d01d1e9652) | Dec 06, 2022 |
| Dell          | XPS 13 9370                 | [b500d948bf](https://linux-hardware.org/?probe=b500d948bf) | Dec 05, 2022 |
| HP            | EliteBook 840 G2            | [ff90421b87](https://linux-hardware.org/?probe=ff90421b87) | Dec 05, 2022 |
| HP            | EliteBook 840 G1            | [3bc6ea9cfa](https://linux-hardware.org/?probe=3bc6ea9cfa) | Dec 05, 2022 |
| HP            | EliteBook 840 G1            | [aaed16d626](https://linux-hardware.org/?probe=aaed16d626) | Dec 05, 2022 |
| HP            | EliteBook 840 G2            | [cd63efdbd4](https://linux-hardware.org/?probe=cd63efdbd4) | Dec 05, 2022 |
| Sony          | VPCEB1M1E                   | [7ea8161a05](https://linux-hardware.org/?probe=7ea8161a05) | Dec 01, 2022 |
| HP            | Laptop 15-dw1xxx            | [d8d5459ad6](https://linux-hardware.org/?probe=d8d5459ad6) | Dec 01, 2022 |
| Lenovo        | ThinkPad T470p 20J60018M... | [994d8e4b1d](https://linux-hardware.org/?probe=994d8e4b1d) | Dec 01, 2022 |
| HP            | Laptop 15-dw1xxx            | [1dddd99280](https://linux-hardware.org/?probe=1dddd99280) | Dec 01, 2022 |
| Lenovo        | ThinkPad L560 20F10034MX    | [34842eb8d9](https://linux-hardware.org/?probe=34842eb8d9) | Dec 01, 2022 |
| Lenovo        | ThinkPad X270 20HNS03B00    | [bd40de3011](https://linux-hardware.org/?probe=bd40de3011) | Nov 30, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [258c074e40](https://linux-hardware.org/?probe=258c074e40) | Nov 30, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [29ec19d38e](https://linux-hardware.org/?probe=29ec19d38e) | Nov 30, 2022 |
| Lenovo        | ThinkPad T470p 20J60018M... | [c5f7049b04](https://linux-hardware.org/?probe=c5f7049b04) | Nov 28, 2022 |
| Lenovo        | ThinkPad E580 20KS001QMX    | [97fda88c7b](https://linux-hardware.org/?probe=97fda88c7b) | Nov 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [ce5a80936d](https://linux-hardware.org/?probe=ce5a80936d) | Nov 24, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [9758f3268e](https://linux-hardware.org/?probe=9758f3268e) | Nov 23, 2022 |
| ASUSTek       | Strix GL504GW_GL504GW       | [f06e160e11](https://linux-hardware.org/?probe=f06e160e11) | Nov 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [7121172cc6](https://linux-hardware.org/?probe=7121172cc6) | Nov 22, 2022 |
| Dell          | XPS 9320                    | [52b55ea024](https://linux-hardware.org/?probe=52b55ea024) | Nov 21, 2022 |
| Dell          | XPS 9320                    | [7ea2296eaf](https://linux-hardware.org/?probe=7ea2296eaf) | Nov 21, 2022 |
| Apple         | MacBookPro10,1              | [71cb60b441](https://linux-hardware.org/?probe=71cb60b441) | Nov 21, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [3534f07f4a](https://linux-hardware.org/?probe=3534f07f4a) | Nov 18, 2022 |
| ASUSTek       | N550JK                      | [86a2f7caea](https://linux-hardware.org/?probe=86a2f7caea) | Nov 18, 2022 |
| Dell          | Latitude 5310               | [8c9625dc17](https://linux-hardware.org/?probe=8c9625dc17) | Nov 17, 2022 |
| Dell          | Latitude 5310               | [958c48cd54](https://linux-hardware.org/?probe=958c48cd54) | Nov 17, 2022 |
| HP            | ZBook 15u G6                | [e6600fae5a](https://linux-hardware.org/?probe=e6600fae5a) | Nov 16, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [64fb474239](https://linux-hardware.org/?probe=64fb474239) | Nov 14, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [fa18a7779e](https://linux-hardware.org/?probe=fa18a7779e) | Nov 13, 2022 |
| Apple         | MacBook5,1                  | [aea8b4a908](https://linux-hardware.org/?probe=aea8b4a908) | Nov 12, 2022 |
| Apple         | MacBook5,1                  | [4aa0411587](https://linux-hardware.org/?probe=4aa0411587) | Nov 12, 2022 |
| Dell          | XPS 13 9370                 | [2865464ccd](https://linux-hardware.org/?probe=2865464ccd) | Nov 11, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [48f127b453](https://linux-hardware.org/?probe=48f127b453) | Nov 11, 2022 |
| ASUSTek       | U36SD                       | [d6b92cbdaa](https://linux-hardware.org/?probe=d6b92cbdaa) | Nov 07, 2022 |
| Acer          | Aspire A515-52              | [ed07b564ec](https://linux-hardware.org/?probe=ed07b564ec) | Nov 07, 2022 |
| HP            | EliteBook 830 G5            | [92c837ff5a](https://linux-hardware.org/?probe=92c837ff5a) | Nov 06, 2022 |
| HP            | EliteBook 830 G5            | [298819594a](https://linux-hardware.org/?probe=298819594a) | Nov 06, 2022 |
| Packard Be... | EasyNote TS11HR             | [8a62c61d38](https://linux-hardware.org/?probe=8a62c61d38) | Nov 06, 2022 |
| HP            | ZBook 15u G6                | [58025a9d04](https://linux-hardware.org/?probe=58025a9d04) | Nov 05, 2022 |
| HP            | ZBook 15u G6                | [bd1a9c6659](https://linux-hardware.org/?probe=bd1a9c6659) | Nov 05, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [7590df932b](https://linux-hardware.org/?probe=7590df932b) | Nov 05, 2022 |
| Apple         | MacBookPro16,2              | [ad1ae18c98](https://linux-hardware.org/?probe=ad1ae18c98) | Nov 04, 2022 |
| Apple         | MacBookPro10,1              | [b2af134ab3](https://linux-hardware.org/?probe=b2af134ab3) | Nov 04, 2022 |
| HP            | ProBook 640 G1              | [9d1ba43c71](https://linux-hardware.org/?probe=9d1ba43c71) | Nov 04, 2022 |
| HP            | ProBook 640 G1              | [dac055fa29](https://linux-hardware.org/?probe=dac055fa29) | Nov 04, 2022 |
| HUAWEI        | KLVL-WXX9                   | [de163caae3](https://linux-hardware.org/?probe=de163caae3) | Nov 04, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [442942f712](https://linux-hardware.org/?probe=442942f712) | Nov 04, 2022 |
| HP            | EliteBook 830 G7 Noteboo... | [063675c104](https://linux-hardware.org/?probe=063675c104) | Oct 29, 2022 |
| HP            | ZBook Fury 15.6 inch G8 ... | [f95081e76e](https://linux-hardware.org/?probe=f95081e76e) | Oct 27, 2022 |
| HP            | EliteBook 830 G7 Noteboo... | [0fcfd33f95](https://linux-hardware.org/?probe=0fcfd33f95) | Oct 27, 2022 |
| Samsung       | 305V4A/305V5A/3415VA        | [d8f70347cf](https://linux-hardware.org/?probe=d8f70347cf) | Oct 24, 2022 |
| Valve         | Jupiter                     | [302efb993a](https://linux-hardware.org/?probe=302efb993a) | Oct 22, 2022 |
| Lenovo        | ThinkPad P52 20M90017MX     | [8f3fdb4d9c](https://linux-hardware.org/?probe=8f3fdb4d9c) | Oct 22, 2022 |
| Valve         | Jupiter                     | [024fdc987b](https://linux-hardware.org/?probe=024fdc987b) | Oct 21, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [5e59c8933b](https://linux-hardware.org/?probe=5e59c8933b) | Oct 20, 2022 |
| Valve         | Jupiter                     | [6249475f24](https://linux-hardware.org/?probe=6249475f24) | Oct 20, 2022 |
| Lenovo        | IdeaPad S340-15APITouch ... | [aa65a51ac6](https://linux-hardware.org/?probe=aa65a51ac6) | Oct 18, 2022 |
| Apple         | MacBookAir6,1               | [2438851671](https://linux-hardware.org/?probe=2438851671) | Oct 16, 2022 |
| Acer          | Aspire V3-571               | [8457aa21e7](https://linux-hardware.org/?probe=8457aa21e7) | Oct 16, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [689281cab0](https://linux-hardware.org/?probe=689281cab0) | Oct 15, 2022 |
| Dell          | XPS 13 9360                 | [6def734895](https://linux-hardware.org/?probe=6def734895) | Oct 14, 2022 |
| Acer          | Aspire 8950G                | [8888f23e03](https://linux-hardware.org/?probe=8888f23e03) | Oct 14, 2022 |
| Lenovo        | ThinkPad E595 20NF001HMX    | [1ae4e8967a](https://linux-hardware.org/?probe=1ae4e8967a) | Oct 14, 2022 |
| Gigabyte      | P65Q                        | [8e83936c53](https://linux-hardware.org/?probe=8e83936c53) | Oct 12, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [10ea852e71](https://linux-hardware.org/?probe=10ea852e71) | Oct 12, 2022 |
| Dell          | XPS 15 9560                 | [ef1a363500](https://linux-hardware.org/?probe=ef1a363500) | Oct 11, 2022 |
| Apple         | MacBookPro9,2               | [7b6f3fcf28](https://linux-hardware.org/?probe=7b6f3fcf28) | Oct 10, 2022 |
| HP            | Pavilion dv7                | [4564037395](https://linux-hardware.org/?probe=4564037395) | Oct 07, 2022 |
| Dell          | XPS 13 7390                 | [c52e60caae](https://linux-hardware.org/?probe=c52e60caae) | Oct 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [28d49251c7](https://linux-hardware.org/?probe=28d49251c7) | Oct 04, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [3ec3f59233](https://linux-hardware.org/?probe=3ec3f59233) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [5ed7136249](https://linux-hardware.org/?probe=5ed7136249) | Oct 03, 2022 |
| ASUSTek       | UX303UB                     | [d67f04fc6e](https://linux-hardware.org/?probe=d67f04fc6e) | Oct 02, 2022 |
| Dell          | Latitude E6320              | [69290cc372](https://linux-hardware.org/?probe=69290cc372) | Oct 02, 2022 |
| ASUSTek       | UX303UB                     | [e09f793c1a](https://linux-hardware.org/?probe=e09f793c1a) | Oct 01, 2022 |
| HP            | EliteBook 840 G3            | [24a248630f](https://linux-hardware.org/?probe=24a248630f) | Sep 30, 2022 |
| Dell          | XPS 13 9310                 | [6f9bc0cdba](https://linux-hardware.org/?probe=6f9bc0cdba) | Sep 26, 2022 |
| Dell          | XPS 13 9310                 | [d65cd8309b](https://linux-hardware.org/?probe=d65cd8309b) | Sep 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [8f29c3dc10](https://linux-hardware.org/?probe=8f29c3dc10) | Sep 24, 2022 |
| TUXEDO        | Unknown                     | [52ddc219ae](https://linux-hardware.org/?probe=52ddc219ae) | Sep 23, 2022 |
| Valve         | Jupiter                     | [c81b14b950](https://linux-hardware.org/?probe=c81b14b950) | Sep 23, 2022 |
| Lenovo        | Yoga 13sACN 2021 82CY       | [d374a74e0d](https://linux-hardware.org/?probe=d374a74e0d) | Sep 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [5e7597fb17](https://linux-hardware.org/?probe=5e7597fb17) | Sep 22, 2022 |
| HP            | Pavilion g7                 | [a5f3f12174](https://linux-hardware.org/?probe=a5f3f12174) | Sep 20, 2022 |
| ASUSTek       | GL553VE                     | [4d93da1983](https://linux-hardware.org/?probe=4d93da1983) | Sep 20, 2022 |
| Dell          | Latitude E6320              | [4995ae034f](https://linux-hardware.org/?probe=4995ae034f) | Sep 19, 2022 |
| Dell          | Latitude E6320              | [4bf59d7938](https://linux-hardware.org/?probe=4bf59d7938) | Sep 19, 2022 |
| ASUSTek       | GL553VE                     | [27b8d384a2](https://linux-hardware.org/?probe=27b8d384a2) | Sep 19, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [38d90248df](https://linux-hardware.org/?probe=38d90248df) | Sep 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [4c33a54701](https://linux-hardware.org/?probe=4c33a54701) | Sep 16, 2022 |
| Dell          | Latitude 7300               | [9802315270](https://linux-hardware.org/?probe=9802315270) | Sep 14, 2022 |
| Dell          | Latitude 7300               | [5d82c4da95](https://linux-hardware.org/?probe=5d82c4da95) | Sep 14, 2022 |
| Lenovo        | ThinkBook 13x ITG 20WJ      | [2e6e759434](https://linux-hardware.org/?probe=2e6e759434) | Sep 13, 2022 |
| HP            | ProBook 440 G7              | [082bf17ff0](https://linux-hardware.org/?probe=082bf17ff0) | Sep 08, 2022 |
| HP            | Compaq Presario CQ60        | [f6981692e0](https://linux-hardware.org/?probe=f6981692e0) | Sep 08, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [492849d42d](https://linux-hardware.org/?probe=492849d42d) | Sep 07, 2022 |
| Dell          | Precision 5530              | [d588e96ddc](https://linux-hardware.org/?probe=d588e96ddc) | Sep 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [308047a7cb](https://linux-hardware.org/?probe=308047a7cb) | Sep 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [b1edd48233](https://linux-hardware.org/?probe=b1edd48233) | Sep 05, 2022 |
| Acer          | Aspire V3-571G              | [3f17eeffec](https://linux-hardware.org/?probe=3f17eeffec) | Sep 03, 2022 |
| Dell          | Latitude 7300               | [30994e1857](https://linux-hardware.org/?probe=30994e1857) | Sep 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [dea9852124](https://linux-hardware.org/?probe=dea9852124) | Sep 02, 2022 |
| Purism        | Librem 14                   | [54d6cbb49d](https://linux-hardware.org/?probe=54d6cbb49d) | Sep 01, 2022 |
| HP            | Pavilion 15                 | [19c7cae23c](https://linux-hardware.org/?probe=19c7cae23c) | Aug 31, 2022 |
| Acer          | Predator PT516-51s          | [5739f0b1a0](https://linux-hardware.org/?probe=5739f0b1a0) | Aug 28, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [70b2e9f836](https://linux-hardware.org/?probe=70b2e9f836) | Aug 27, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | [264a4fd9a7](https://linux-hardware.org/?probe=264a4fd9a7) | Aug 26, 2022 |
| Apple         | MacBookPro14,1              | [ce2bb0938b](https://linux-hardware.org/?probe=ce2bb0938b) | Aug 26, 2022 |
| Apple         | MacBookPro14,1              | [61b05137a7](https://linux-hardware.org/?probe=61b05137a7) | Aug 26, 2022 |
| ASUSTek       | T100HAN                     | [9438c7bb11](https://linux-hardware.org/?probe=9438c7bb11) | Aug 23, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [6fcc3e058d](https://linux-hardware.org/?probe=6fcc3e058d) | Aug 22, 2022 |
| Samsung       | 935XDB                      | [a8d4f5e6a0](https://linux-hardware.org/?probe=a8d4f5e6a0) | Aug 20, 2022 |
| MSI           | GF63 Thin 10UC              | [b04f79d93a](https://linux-hardware.org/?probe=b04f79d93a) | Aug 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [87fcf5d702](https://linux-hardware.org/?probe=87fcf5d702) | Aug 19, 2022 |
| Lenovo        | ThinkPad X201 3626FAG       | [0271f9018f](https://linux-hardware.org/?probe=0271f9018f) | Aug 19, 2022 |
| HP            | Pavilion g6                 | [ddc9a7396e](https://linux-hardware.org/?probe=ddc9a7396e) | Aug 16, 2022 |
| HP            | Pavilion g6                 | [ef1cbed5a4](https://linux-hardware.org/?probe=ef1cbed5a4) | Aug 16, 2022 |
| Acer          | Aspire ES1-512              | [cb59c4a321](https://linux-hardware.org/?probe=cb59c4a321) | Aug 15, 2022 |
| Acer          | Aspire ES1-512              | [496f0834ae](https://linux-hardware.org/?probe=496f0834ae) | Aug 15, 2022 |
| Packard Be... | EasyNote TS11HR             | [837159c07a](https://linux-hardware.org/?probe=837159c07a) | Aug 14, 2022 |
| MSI           | Prestige 15 A10SC           | [58d3be66c0](https://linux-hardware.org/?probe=58d3be66c0) | Aug 14, 2022 |
| Apple         | MacBookPro11,3              | [1091d27582](https://linux-hardware.org/?probe=1091d27582) | Aug 11, 2022 |
| Lenovo        | ThinkPad X201 3626FAG       | [34938e0949](https://linux-hardware.org/?probe=34938e0949) | Aug 11, 2022 |
| Valve         | Jupiter                     | [813863fbbf](https://linux-hardware.org/?probe=813863fbbf) | Aug 09, 2022 |
| Apple         | MacBookPro11,3              | [c530c6e2cb](https://linux-hardware.org/?probe=c530c6e2cb) | Aug 08, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [119cdc7bf8](https://linux-hardware.org/?probe=119cdc7bf8) | Aug 07, 2022 |
| Lenovo        | Yoga SLIM 7-14ARE05 82A2    | [091235281e](https://linux-hardware.org/?probe=091235281e) | Aug 06, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [ec98a546e1](https://linux-hardware.org/?probe=ec98a546e1) | Aug 06, 2022 |
| Lenovo        | Yoga SLIM 7-14ARE05 82A2    | [431684d65c](https://linux-hardware.org/?probe=431684d65c) | Aug 05, 2022 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [a2733a0f87](https://linux-hardware.org/?probe=a2733a0f87) | Aug 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [cdc1f14772](https://linux-hardware.org/?probe=cdc1f14772) | Aug 04, 2022 |
| Samsung       | 700G7C                      | [cd554f5d17](https://linux-hardware.org/?probe=cd554f5d17) | Aug 03, 2022 |
| Dell          | Precision 14 5470           | [089d1a151f](https://linux-hardware.org/?probe=089d1a151f) | Aug 03, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [de9a854095](https://linux-hardware.org/?probe=de9a854095) | Jul 31, 2022 |
| Dell          | Inspiron 5558               | [06b58ca667](https://linux-hardware.org/?probe=06b58ca667) | Jul 31, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [ae030e58fb](https://linux-hardware.org/?probe=ae030e58fb) | Jul 31, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [249d407b66](https://linux-hardware.org/?probe=249d407b66) | Jul 30, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [4fa56bac04](https://linux-hardware.org/?probe=4fa56bac04) | Jul 29, 2022 |
| HP            | ZBook 15 G2                 | [34f32c0d0d](https://linux-hardware.org/?probe=34f32c0d0d) | Jul 27, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | [b3df887fe1](https://linux-hardware.org/?probe=b3df887fe1) | Jul 27, 2022 |
| ASUSTek       | ZenBook UX325UA             | [587ea51239](https://linux-hardware.org/?probe=587ea51239) | Jul 26, 2022 |
| Dell          | Precision 7560              | [2fdcece648](https://linux-hardware.org/?probe=2fdcece648) | Jul 25, 2022 |
| Dell          | Precision 7560              | [02fb353f1e](https://linux-hardware.org/?probe=02fb353f1e) | Jul 25, 2022 |
| MSI           | Raider GE76 12UGS           | [65c50de21a](https://linux-hardware.org/?probe=65c50de21a) | Jul 22, 2022 |
| MSI           | Raider GE76 12UGS           | [6dba304ba4](https://linux-hardware.org/?probe=6dba304ba4) | Jul 22, 2022 |
| ASUSTek       | K52Dr                       | [efd71c663d](https://linux-hardware.org/?probe=efd71c663d) | Jul 22, 2022 |
| Acer          | Predator PT516-51s          | [8337c958e2](https://linux-hardware.org/?probe=8337c958e2) | Jul 22, 2022 |
| Toshiba       | BLB                         | [997a7c93d7](https://linux-hardware.org/?probe=997a7c93d7) | Jul 21, 2022 |
| Dell          | Latitude E5450              | [c8243bf1a8](https://linux-hardware.org/?probe=c8243bf1a8) | Jul 20, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [2a10c24690](https://linux-hardware.org/?probe=2a10c24690) | Jul 20, 2022 |
| Dell          | Precision 7760              | [742cb747ef](https://linux-hardware.org/?probe=742cb747ef) | Jul 20, 2022 |
| ASUSTek       | K52Dr                       | [31471e3583](https://linux-hardware.org/?probe=31471e3583) | Jul 19, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [ac6aba12f5](https://linux-hardware.org/?probe=ac6aba12f5) | Jul 19, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [7f4f42a3f7](https://linux-hardware.org/?probe=7f4f42a3f7) | Jul 19, 2022 |
| Dell          | Precision 3561              | [7dfa6ede1e](https://linux-hardware.org/?probe=7dfa6ede1e) | Jul 18, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [fb9a47e37f](https://linux-hardware.org/?probe=fb9a47e37f) | Jul 17, 2022 |
| Star Labs     | StarBook                    | [fdae1cd2c3](https://linux-hardware.org/?probe=fdae1cd2c3) | Jul 12, 2022 |
| HP            | EliteBook 830 G5            | [235fc9b289](https://linux-hardware.org/?probe=235fc9b289) | Jul 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [a42efbead1](https://linux-hardware.org/?probe=a42efbead1) | Jul 11, 2022 |
| HP            | EliteBook 830 G5            | [8d8610ee4f](https://linux-hardware.org/?probe=8d8610ee4f) | Jul 11, 2022 |
| HP            | EliteBook 830 G5            | [4dba0dc5ab](https://linux-hardware.org/?probe=4dba0dc5ab) | Jul 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [0e13eaa824](https://linux-hardware.org/?probe=0e13eaa824) | Jul 10, 2022 |
| Dell          | Precision 5570              | [e4409961fd](https://linux-hardware.org/?probe=e4409961fd) | Jul 08, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [5cff36844a](https://linux-hardware.org/?probe=5cff36844a) | Jul 07, 2022 |
| Valve         | Jupiter                     | [458276506d](https://linux-hardware.org/?probe=458276506d) | Jul 06, 2022 |
| Acer          | Predator PT516-51s          | [9309da8b72](https://linux-hardware.org/?probe=9309da8b72) | Jul 05, 2022 |
| Acer          | Aspire 3100                 | [498f4edafb](https://linux-hardware.org/?probe=498f4edafb) | Jul 05, 2022 |
| Acer          | Aspire 3100                 | [1264fab131](https://linux-hardware.org/?probe=1264fab131) | Jul 05, 2022 |
| Dell          | Precision M4700             | [fad2fe7297](https://linux-hardware.org/?probe=fad2fe7297) | Jul 04, 2022 |
| Dell          | XPS 15 9520                 | [0cb6549f23](https://linux-hardware.org/?probe=0cb6549f23) | Jun 30, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [27343a622f](https://linux-hardware.org/?probe=27343a622f) | Jun 25, 2022 |
| HP            | Pavilion dv7                | [5dd67bc68a](https://linux-hardware.org/?probe=5dd67bc68a) | Jun 25, 2022 |
| ASUSTek       | N61Vn                       | [72d62f755d](https://linux-hardware.org/?probe=72d62f755d) | Jun 24, 2022 |
| HP            | ZBook 15 G2                 | [cfa8a05299](https://linux-hardware.org/?probe=cfa8a05299) | Jun 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [5188bfb9d3](https://linux-hardware.org/?probe=5188bfb9d3) | Jun 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [27623895a1](https://linux-hardware.org/?probe=27623895a1) | Jun 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [f76be8391b](https://linux-hardware.org/?probe=f76be8391b) | Jun 18, 2022 |
| Apple         | MacBookAir6,2               | [f75b5004f9](https://linux-hardware.org/?probe=f75b5004f9) | Jun 17, 2022 |
| HP            | EliteBook 830 G7 Noteboo... | [8153e1c68e](https://linux-hardware.org/?probe=8153e1c68e) | Jun 13, 2022 |
| HP            | EliteBook 830 G6            | [12fb5f93c9](https://linux-hardware.org/?probe=12fb5f93c9) | Jun 13, 2022 |
| Dell          | Precision 7520              | [002f7ce017](https://linux-hardware.org/?probe=002f7ce017) | Jun 12, 2022 |
| HP            | Pavilion g6                 | [63dcba0c57](https://linux-hardware.org/?probe=63dcba0c57) | Jun 10, 2022 |
| Dell          | Vostro 2520                 | [884806d49f](https://linux-hardware.org/?probe=884806d49f) | Jun 09, 2022 |
| Acer          | Aspire 5749Z                | [d7020510e2](https://linux-hardware.org/?probe=d7020510e2) | Jun 08, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [685df41f04](https://linux-hardware.org/?probe=685df41f04) | Jun 07, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7762... | [9ccaec00d8](https://linux-hardware.org/?probe=9ccaec00d8) | Jun 06, 2022 |
| Dell          | Latitude D630               | [fb28805860](https://linux-hardware.org/?probe=fb28805860) | Jun 05, 2022 |
| Apple         | MacBookPro8,1               | [d191629954](https://linux-hardware.org/?probe=d191629954) | Jun 04, 2022 |
| Apple         | MacBookPro8,1               | [816c29b1df](https://linux-hardware.org/?probe=816c29b1df) | Jun 04, 2022 |
| HP            | ProBook 6450b               | [52467822a6](https://linux-hardware.org/?probe=52467822a6) | Jun 03, 2022 |
| HP            | ProBook 6450b               | [26bce40d20](https://linux-hardware.org/?probe=26bce40d20) | Jun 01, 2022 |
| Dell          | Latitude E7240              | [e3c9cca7e1](https://linux-hardware.org/?probe=e3c9cca7e1) | Jun 01, 2022 |
| Acer          | Swift SF314-42              | [f4906f3799](https://linux-hardware.org/?probe=f4906f3799) | Jun 01, 2022 |
| Toshiba       | Satellite L50D-B            | [860be26e14](https://linux-hardware.org/?probe=860be26e14) | May 29, 2022 |
| Lenovo        | ThinkPad W500 4061W8H       | [db9160e089](https://linux-hardware.org/?probe=db9160e089) | May 29, 2022 |
| HP            | ProBook 650 G1              | [b32a949b01](https://linux-hardware.org/?probe=b32a949b01) | May 28, 2022 |
| ASUSTek       | U31Jg                       | [b761173e5e](https://linux-hardware.org/?probe=b761173e5e) | May 26, 2022 |
| Fujitsu       | CELSIUS H730                | [6f0b24d450](https://linux-hardware.org/?probe=6f0b24d450) | May 26, 2022 |
| HP            | EliteBook 850 G6            | [25e4d08ac2](https://linux-hardware.org/?probe=25e4d08ac2) | May 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [2d28231751](https://linux-hardware.org/?probe=2d28231751) | May 25, 2022 |
| Apple         | MacBook6,1                  | [683ff3ab1a](https://linux-hardware.org/?probe=683ff3ab1a) | May 24, 2022 |
| Apple         | MacBookAir7,2               | [b620a51628](https://linux-hardware.org/?probe=b620a51628) | May 22, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [32b5f99569](https://linux-hardware.org/?probe=32b5f99569) | May 22, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [cc0b92bd45](https://linux-hardware.org/?probe=cc0b92bd45) | May 21, 2022 |
| HP            | 635                         | [2421582549](https://linux-hardware.org/?probe=2421582549) | May 21, 2022 |
| Apple         | MacBook6,1                  | [97e7c3fd74](https://linux-hardware.org/?probe=97e7c3fd74) | May 19, 2022 |
| HP            | EliteBook 8460p             | [a1cbc8b911](https://linux-hardware.org/?probe=a1cbc8b911) | May 19, 2022 |
| HP            | EliteBook Folio 1040 G3     | [13bc0ce7c5](https://linux-hardware.org/?probe=13bc0ce7c5) | May 19, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | [736bd1ab68](https://linux-hardware.org/?probe=736bd1ab68) | May 18, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | [6c41f73e8a](https://linux-hardware.org/?probe=6c41f73e8a) | May 18, 2022 |
| HP            | 635                         | [3168b50a90](https://linux-hardware.org/?probe=3168b50a90) | May 18, 2022 |
| Apple         | MacBookPro16,2              | [ceb6a7e5a3](https://linux-hardware.org/?probe=ceb6a7e5a3) | May 16, 2022 |
| Apple         | MacBookPro16,2              | [5c4ebc223f](https://linux-hardware.org/?probe=5c4ebc223f) | May 16, 2022 |
| MSI           | GS73VR 7RG                  | [3815425b08](https://linux-hardware.org/?probe=3815425b08) | May 15, 2022 |
| Notebook      | NS50_70MU                   | [cff8de13ce](https://linux-hardware.org/?probe=cff8de13ce) | May 12, 2022 |
| Notebook      | NS50_70MU                   | [ebf71be1f5](https://linux-hardware.org/?probe=ebf71be1f5) | May 12, 2022 |
| MSI           | GF63 Thin 9SCSR             | [a80ef1636d](https://linux-hardware.org/?probe=a80ef1636d) | May 12, 2022 |
| ASUSTek       | A6U                         | [4a8ad00e5e](https://linux-hardware.org/?probe=4a8ad00e5e) | May 12, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [38bc924977](https://linux-hardware.org/?probe=38bc924977) | May 12, 2022 |
| Lenovo        | ThinkPad X270 20HMS27Q00    | [615d6650a0](https://linux-hardware.org/?probe=615d6650a0) | May 08, 2022 |
| Lenovo        | ThinkPad X240 20AMS6FF00    | [3e3da41a35](https://linux-hardware.org/?probe=3e3da41a35) | May 08, 2022 |
| ASUSTek       | E200HA                      | [ba413ad853](https://linux-hardware.org/?probe=ba413ad853) | May 08, 2022 |
| Samsung       | 750XDA                      | [466689475e](https://linux-hardware.org/?probe=466689475e) | May 07, 2022 |
| ASUSTek       | E200HA                      | [6fc7c6f086](https://linux-hardware.org/?probe=6fc7c6f086) | May 07, 2022 |
| Dell          | Precision M4700             | [81cc8ba45c](https://linux-hardware.org/?probe=81cc8ba45c) | May 06, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U2S... | [64eb136705](https://linux-hardware.org/?probe=64eb136705) | May 03, 2022 |
| Acer          | Aspire A315-41              | [1bd7f7cd93](https://linux-hardware.org/?probe=1bd7f7cd93) | May 02, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [f6cc5e2ad5](https://linux-hardware.org/?probe=f6cc5e2ad5) | May 01, 2022 |
| HP            | Pavilion Notebook           | [995ea9538b](https://linux-hardware.org/?probe=995ea9538b) | Apr 30, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [5d02fb20c7](https://linux-hardware.org/?probe=5d02fb20c7) | Apr 29, 2022 |
| Lenovo        | ThinkPad X131e 33683YG      | [58076aa8e9](https://linux-hardware.org/?probe=58076aa8e9) | Apr 28, 2022 |
| Dell          | XPS 13 7390                 | [37b195945a](https://linux-hardware.org/?probe=37b195945a) | Apr 28, 2022 |
| Dell          | Latitude 7420               | [8e3bcab404](https://linux-hardware.org/?probe=8e3bcab404) | Apr 28, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [3b4a331875](https://linux-hardware.org/?probe=3b4a331875) | Apr 26, 2022 |
| Lenovo        | ThinkPad T61 64665WG        | [ac1bec6053](https://linux-hardware.org/?probe=ac1bec6053) | Apr 26, 2022 |
| Lenovo        | ThinkPad T450s 20BWS3FX0... | [00d3556f08](https://linux-hardware.org/?probe=00d3556f08) | Apr 23, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [7988499108](https://linux-hardware.org/?probe=7988499108) | Apr 23, 2022 |
| HP            | EliteBook Folio 9470m       | [cd369fb3e3](https://linux-hardware.org/?probe=cd369fb3e3) | Apr 23, 2022 |
| Lenovo        | ThinkPad T470s 20HF004MM... | [69a5e98a04](https://linux-hardware.org/?probe=69a5e98a04) | Apr 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [3e1029ed36](https://linux-hardware.org/?probe=3e1029ed36) | Apr 22, 2022 |
| Lenovo        | IdeaPad 500S-13ISK 80Q2     | [4548a301f8](https://linux-hardware.org/?probe=4548a301f8) | Apr 22, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [3b76e2f5ab](https://linux-hardware.org/?probe=3b76e2f5ab) | Apr 21, 2022 |
| ASUSTek       | UX31E                       | [ca406cf975](https://linux-hardware.org/?probe=ca406cf975) | Apr 21, 2022 |
| ASUSTek       | UX31E                       | [32d9d8c8df](https://linux-hardware.org/?probe=32d9d8c8df) | Apr 21, 2022 |
| ASUSTek       | G551JW                      | [b0d7f099f5](https://linux-hardware.org/?probe=b0d7f099f5) | Apr 18, 2022 |
| Lenovo        | ThinkPad X131e 33683YG      | [7855e19861](https://linux-hardware.org/?probe=7855e19861) | Apr 17, 2022 |
| Acer          | Aspire V3-571               | [5bd64f9988](https://linux-hardware.org/?probe=5bd64f9988) | Apr 17, 2022 |
| Toshiba       | BLB                         | [903779c2b2](https://linux-hardware.org/?probe=903779c2b2) | Apr 16, 2022 |
| Toshiba       | BLB                         | [1dffc347dd](https://linux-hardware.org/?probe=1dffc347dd) | Apr 16, 2022 |
| HP            | ProBook 430 G1              | [c42de00504](https://linux-hardware.org/?probe=c42de00504) | Apr 15, 2022 |
| Lenovo        | ThinkPad X280 20KE001MMX    | [fb0da9def7](https://linux-hardware.org/?probe=fb0da9def7) | Apr 15, 2022 |
| Dell          | Latitude E7450              | [9af0006104](https://linux-hardware.org/?probe=9af0006104) | Apr 15, 2022 |
| Apple         | MacBookPro11,3              | [b2fdf48a7f](https://linux-hardware.org/?probe=b2fdf48a7f) | Apr 14, 2022 |
| Apple         | MacBookPro11,3              | [ca14d0eb57](https://linux-hardware.org/?probe=ca14d0eb57) | Apr 13, 2022 |
| TUXEDO        | Pulse 14 Gen1               | [68e6736cd2](https://linux-hardware.org/?probe=68e6736cd2) | Apr 13, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [502a8c9d32](https://linux-hardware.org/?probe=502a8c9d32) | Apr 13, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | [d9f1aff70a](https://linux-hardware.org/?probe=d9f1aff70a) | Apr 13, 2022 |
| Packard Be... | EasyNote ENTG71BM           | [44520b705b](https://linux-hardware.org/?probe=44520b705b) | Apr 11, 2022 |
| ASUSTek       | N56DY                       | [8fdcef45a9](https://linux-hardware.org/?probe=8fdcef45a9) | Apr 10, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [ce0316a106](https://linux-hardware.org/?probe=ce0316a106) | Apr 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [ff93a4d2f5](https://linux-hardware.org/?probe=ff93a4d2f5) | Apr 08, 2022 |
| Apple         | MacBookPro11,3              | [16fa67b6c1](https://linux-hardware.org/?probe=16fa67b6c1) | Apr 07, 2022 |
| Apple         | MacBookPro11,3              | [fca3b357c3](https://linux-hardware.org/?probe=fca3b357c3) | Apr 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [f4c5281aa9](https://linux-hardware.org/?probe=f4c5281aa9) | Apr 07, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | [1c62a4c421](https://linux-hardware.org/?probe=1c62a4c421) | Apr 07, 2022 |
| HP            | EliteBook 8760w             | [e3a9cdfd95](https://linux-hardware.org/?probe=e3a9cdfd95) | Apr 05, 2022 |
| ASUSTek       | UX32VD                      | [31836fcaa9](https://linux-hardware.org/?probe=31836fcaa9) | Apr 05, 2022 |
| Gigabyte      | P65Q                        | [c0e5b4550a](https://linux-hardware.org/?probe=c0e5b4550a) | Apr 01, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [0b247aa185](https://linux-hardware.org/?probe=0b247aa185) | Mar 30, 2022 |
| Dell          | Precision 5540              | [26060f12a6](https://linux-hardware.org/?probe=26060f12a6) | Mar 27, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [e5b0f5c259](https://linux-hardware.org/?probe=e5b0f5c259) | Mar 27, 2022 |
| Apple         | MacBookPro11,3              | [4e534bb83a](https://linux-hardware.org/?probe=4e534bb83a) | Mar 26, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [801fa902d0](https://linux-hardware.org/?probe=801fa902d0) | Mar 24, 2022 |
| HP            | ProBook 430 G1              | [9f295312dc](https://linux-hardware.org/?probe=9f295312dc) | Mar 21, 2022 |
| Dell          | Latitude 7300               | [751dc53e2b](https://linux-hardware.org/?probe=751dc53e2b) | Mar 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [c0faa2a27b](https://linux-hardware.org/?probe=c0faa2a27b) | Mar 19, 2022 |
| HP            | EliteBook 850 G5            | [6d8c8748e2](https://linux-hardware.org/?probe=6d8c8748e2) | Mar 17, 2022 |
| Dell          | Inspiron MP061              | [2b46add19f](https://linux-hardware.org/?probe=2b46add19f) | Mar 16, 2022 |
| Fujitsu       | LIFEBOOK E546               | [247dd3e47c](https://linux-hardware.org/?probe=247dd3e47c) | Mar 13, 2022 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | [3dc49dc5f3](https://linux-hardware.org/?probe=3dc49dc5f3) | Mar 13, 2022 |
| Toshiba       | Satellite C50D-A-14E        | [256e08de3d](https://linux-hardware.org/?probe=256e08de3d) | Mar 13, 2022 |
| Lenovo        | Flex 2-15 20405             | [3e4ac3a045](https://linux-hardware.org/?probe=3e4ac3a045) | Mar 07, 2022 |
| HP            | ENVY 15                     | [a4f5eedd3c](https://linux-hardware.org/?probe=a4f5eedd3c) | Mar 06, 2022 |
| ASUSTek       | E205SA                      | [4c896c9379](https://linux-hardware.org/?probe=4c896c9379) | Mar 05, 2022 |
| Lenovo        | ThinkPad E580 20KS001QMX    | [af4563cb12](https://linux-hardware.org/?probe=af4563cb12) | Mar 04, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [88a973e27f](https://linux-hardware.org/?probe=88a973e27f) | Mar 02, 2022 |
| Google        | Rammus                      | [a326a69db9](https://linux-hardware.org/?probe=a326a69db9) | Mar 02, 2022 |
| Google        | Rammus                      | [b395780983](https://linux-hardware.org/?probe=b395780983) | Mar 02, 2022 |
| HP            | ProBook 640 G2              | [75cdf384b5](https://linux-hardware.org/?probe=75cdf384b5) | Feb 27, 2022 |
| Acer          | Aspire V3-571               | [ff2de5c1da](https://linux-hardware.org/?probe=ff2de5c1da) | Feb 27, 2022 |
| Sony          | VPCEB36FG                   | [d46f784fbb](https://linux-hardware.org/?probe=d46f784fbb) | Feb 26, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [cfd0806662](https://linux-hardware.org/?probe=cfd0806662) | Feb 25, 2022 |
| Acer          | Swift SF314-43              | [1434453fc0](https://linux-hardware.org/?probe=1434453fc0) | Feb 24, 2022 |
| Acer          | Swift SF514-52T             | [3bfa40a4c8](https://linux-hardware.org/?probe=3bfa40a4c8) | Feb 24, 2022 |
| HP            | EliteBook 835 G8 Noteboo... | [4a18cd9a94](https://linux-hardware.org/?probe=4a18cd9a94) | Feb 22, 2022 |
| ASUSTek       | G75VW                       | [d31201b74c](https://linux-hardware.org/?probe=d31201b74c) | Feb 22, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [672f08c769](https://linux-hardware.org/?probe=672f08c769) | Feb 22, 2022 |
| Dell          | Precision 3510              | [3956ab645b](https://linux-hardware.org/?probe=3956ab645b) | Feb 21, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [d2119e4516](https://linux-hardware.org/?probe=d2119e4516) | Feb 21, 2022 |
| Unknown       | Unknown                     | [129c8a24d9](https://linux-hardware.org/?probe=129c8a24d9) | Feb 20, 2022 |
| ZEPTO         | ZNOTE                       | [5ff5c2b966](https://linux-hardware.org/?probe=5ff5c2b966) | Feb 20, 2022 |
| Lenovo        | Yoga 2 Pro 20266            | [dda75e3ba9](https://linux-hardware.org/?probe=dda75e3ba9) | Feb 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7b9e4b097d](https://linux-hardware.org/?probe=7b9e4b097d) | Feb 18, 2022 |
| HP            | Pavilion Gaming Notebook    | [b0cf9aa220](https://linux-hardware.org/?probe=b0cf9aa220) | Feb 18, 2022 |
| HP            | Pavilion dv6                | [012e2b5d56](https://linux-hardware.org/?probe=012e2b5d56) | Feb 15, 2022 |
| Dell          | Latitude 5480               | [62ab6cb2c3](https://linux-hardware.org/?probe=62ab6cb2c3) | Feb 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [a8c5477e60](https://linux-hardware.org/?probe=a8c5477e60) | Feb 13, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | [8ce0419468](https://linux-hardware.org/?probe=8ce0419468) | Feb 13, 2022 |
| Dell          | Latitude E6430              | [4b91478aaa](https://linux-hardware.org/?probe=4b91478aaa) | Feb 11, 2022 |
| Dell          | Latitude D620               | [dfbcd57dc6](https://linux-hardware.org/?probe=dfbcd57dc6) | Feb 10, 2022 |
| HP            | ENVY 15                     | [91c40a9559](https://linux-hardware.org/?probe=91c40a9559) | Feb 08, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [95b53bcaf7](https://linux-hardware.org/?probe=95b53bcaf7) | Feb 08, 2022 |
| Acer          | Aspire ES1-111              | [8f36d1baac](https://linux-hardware.org/?probe=8f36d1baac) | Feb 08, 2022 |
| Acer          | Aspire ES1-111              | [accf5c8a43](https://linux-hardware.org/?probe=accf5c8a43) | Feb 08, 2022 |
| Lenovo        | E31-70 80KX                 | [d4fe754aa4](https://linux-hardware.org/?probe=d4fe754aa4) | Feb 07, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [2427f8c1da](https://linux-hardware.org/?probe=2427f8c1da) | Feb 07, 2022 |
| Acer          | Swift SF314-43              | [386053c3ce](https://linux-hardware.org/?probe=386053c3ce) | Feb 07, 2022 |
| MSI           | GT680R/GX680R/GT683R/GT6... | [15419beff9](https://linux-hardware.org/?probe=15419beff9) | Feb 02, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | [f111410eeb](https://linux-hardware.org/?probe=f111410eeb) | Feb 02, 2022 |
| HP            | EliteBook 830 G6            | [108d91c953](https://linux-hardware.org/?probe=108d91c953) | Feb 02, 2022 |
| HP            | EliteBook 830 G6            | [d866cabd88](https://linux-hardware.org/?probe=d866cabd88) | Feb 02, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [340ecf86ab](https://linux-hardware.org/?probe=340ecf86ab) | Feb 01, 2022 |
| ASUSTek       | GR8                         | [1d8f5be27c](https://linux-hardware.org/?probe=1d8f5be27c) | Jan 30, 2022 |
| Apple         | MacBook3,1                  | [a59b4aa98d](https://linux-hardware.org/?probe=a59b4aa98d) | Jan 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [b584b0b69a](https://linux-hardware.org/?probe=b584b0b69a) | Jan 29, 2022 |
| Lenovo        | ThinkPad T540p 20BE0086M... | [707a381138](https://linux-hardware.org/?probe=707a381138) | Jan 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [6b771832b8](https://linux-hardware.org/?probe=6b771832b8) | Jan 27, 2022 |
| Lenovo        | ThinkPad T420 4236VJ7       | [1d8bb5fbe6](https://linux-hardware.org/?probe=1d8bb5fbe6) | Jan 27, 2022 |
| Lenovo        | ThinkPad T420 4236VJ7       | [87aa03d881](https://linux-hardware.org/?probe=87aa03d881) | Jan 27, 2022 |
| Lenovo        | ThinkPad T410s 292494G      | [cd8aef64e1](https://linux-hardware.org/?probe=cd8aef64e1) | Jan 24, 2022 |
| Apple         | MacBookPro12,1              | [c5c764ccd7](https://linux-hardware.org/?probe=c5c764ccd7) | Jan 24, 2022 |
| Dell          | Latitude E7440              | [74aa958191](https://linux-hardware.org/?probe=74aa958191) | Jan 23, 2022 |
| Notebook      | N13xWU                      | [0d615c6812](https://linux-hardware.org/?probe=0d615c6812) | Jan 22, 2022 |
| Acer          | Swift SF315-41              | [95afa35615](https://linux-hardware.org/?probe=95afa35615) | Jan 22, 2022 |
| Dell          | Inspiron 5721               | [5310b893aa](https://linux-hardware.org/?probe=5310b893aa) | Jan 19, 2022 |
| Dell          | Latitude 7480               | [526c09a456](https://linux-hardware.org/?probe=526c09a456) | Jan 17, 2022 |
| Acer          | Aspire ES1-111              | [2dfe5563ef](https://linux-hardware.org/?probe=2dfe5563ef) | Jan 17, 2022 |
| HP            | EliteBook 850 G3            | [35b6de7b5d](https://linux-hardware.org/?probe=35b6de7b5d) | Jan 16, 2022 |
| Dell          | Precision 3561              | [f5417a1852](https://linux-hardware.org/?probe=f5417a1852) | Jan 16, 2022 |
| Lenovo        | ThinkPad Edge E531 68852... | [2e8135c20d](https://linux-hardware.org/?probe=2e8135c20d) | Jan 15, 2022 |
| Lenovo        | ThinkPad T410s 292494G      | [df5d687786](https://linux-hardware.org/?probe=df5d687786) | Jan 14, 2022 |
| Lenovo        | ThinkPad X240 20AMS6170H    | [03fc719875](https://linux-hardware.org/?probe=03fc719875) | Jan 14, 2022 |
| Dell          | Latitude 5290               | [f1c632a454](https://linux-hardware.org/?probe=f1c632a454) | Jan 12, 2022 |
| Apple         | MacBook3,1                  | [c670d007f3](https://linux-hardware.org/?probe=c670d007f3) | Jan 11, 2022 |
| ASUSTek       | UX310UQ                     | [a9b40e5f8c](https://linux-hardware.org/?probe=a9b40e5f8c) | Jan 10, 2022 |
| Sony          | VPCEB3S1E                   | [6f78e2d423](https://linux-hardware.org/?probe=6f78e2d423) | Jan 07, 2022 |
| Lenovo        | B50-30 80ES                 | [42db32249d](https://linux-hardware.org/?probe=42db32249d) | Jan 07, 2022 |
| Razer         | Book 13 - RZ09-0357         | [148a68191d](https://linux-hardware.org/?probe=148a68191d) | Jan 06, 2022 |
| HP            | EliteBook 1040 G2           | [ca6f52fbeb](https://linux-hardware.org/?probe=ca6f52fbeb) | Jan 06, 2022 |
| Samsung       | 935XDB                      | [1bb7122515](https://linux-hardware.org/?probe=1bb7122515) | Jan 06, 2022 |
| Lenovo        | ThinkPad X240 20AMA2F8MS    | [7b5c7a047a](https://linux-hardware.org/?probe=7b5c7a047a) | Jan 06, 2022 |
| Lenovo        | B50-30 80ES                 | [649be03cf4](https://linux-hardware.org/?probe=649be03cf4) | Jan 06, 2022 |
| Packard Be... | EasyNote TE69BM             | [526fc1b476](https://linux-hardware.org/?probe=526fc1b476) | Jan 05, 2022 |
| HP            | ProBook 640 G1              | [a7f4591b40](https://linux-hardware.org/?probe=a7f4591b40) | Jan 05, 2022 |
| Dell          | XPS 13 9350                 | [492d47c1fa](https://linux-hardware.org/?probe=492d47c1fa) | Jan 04, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [367ef74be3](https://linux-hardware.org/?probe=367ef74be3) | Jan 01, 2022 |
| Apple         | MacBookPro11,3              | [4a20cd5429](https://linux-hardware.org/?probe=4a20cd5429) | Jan 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [fbc9c7ad1a](https://linux-hardware.org/?probe=fbc9c7ad1a) | Jan 01, 2022 |
| Samsung       | 905S3G/906S3G/915S3G        | [7a756782d8](https://linux-hardware.org/?probe=7a756782d8) | Dec 31, 2021 |
| ZEPTO         | ZNOTE                       | [f81a927e9b](https://linux-hardware.org/?probe=f81a927e9b) | Dec 31, 2021 |
| Dell          | Precision 5540              | [ba4fef27b9](https://linux-hardware.org/?probe=ba4fef27b9) | Dec 30, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [51d4addbb3](https://linux-hardware.org/?probe=51d4addbb3) | Dec 29, 2021 |
| Lenovo        | ThinkPad T490s 20NX000DM... | [e1ba67fc0f](https://linux-hardware.org/?probe=e1ba67fc0f) | Dec 28, 2021 |
| eMachines     | E525                        | [fd80580005](https://linux-hardware.org/?probe=fd80580005) | Dec 28, 2021 |
| Lenovo        | V14-ADA 82C6                | [3ac88f1f0b](https://linux-hardware.org/?probe=3ac88f1f0b) | Dec 28, 2021 |
| Acer          | AOHAPPY                     | [3a8a8f6b8e](https://linux-hardware.org/?probe=3a8a8f6b8e) | Dec 27, 2021 |
| Acer          | Swift SF314-511             | [3a201fd936](https://linux-hardware.org/?probe=3a201fd936) | Dec 27, 2021 |
| Apple         | MacBook3,1                  | [705810cc40](https://linux-hardware.org/?probe=705810cc40) | Dec 25, 2021 |
| eMachines     | E525                        | [fcc3b2a5e3](https://linux-hardware.org/?probe=fcc3b2a5e3) | Dec 25, 2021 |
| eMachines     | E525                        | [e5853e5629](https://linux-hardware.org/?probe=e5853e5629) | Dec 25, 2021 |
| Samsung       | 950XDB/951XDB/950XDY        | [edad019098](https://linux-hardware.org/?probe=edad019098) | Dec 23, 2021 |
| HP            | EliteBook Folio 9470m       | [9dd62bbf73](https://linux-hardware.org/?probe=9dd62bbf73) | Dec 23, 2021 |
| Toshiba       | Satellite L50D-B            | [b5a9d0b1dc](https://linux-hardware.org/?probe=b5a9d0b1dc) | Dec 21, 2021 |
| Apple         | MacBookAir6,1               | [b2e3490378](https://linux-hardware.org/?probe=b2e3490378) | Dec 21, 2021 |
| Packard Be... | EasyNote TE69HW             | [c6876b9023](https://linux-hardware.org/?probe=c6876b9023) | Dec 20, 2021 |
| HP            | ZBook Fury 15 G7 Mobile ... | [3fea1de018](https://linux-hardware.org/?probe=3fea1de018) | Dec 20, 2021 |
| eMachines     | E525                        | [bcb03ff38c](https://linux-hardware.org/?probe=bcb03ff38c) | Dec 20, 2021 |
| MSI           | Katana GF66 11UE            | [36aea8dc19](https://linux-hardware.org/?probe=36aea8dc19) | Dec 18, 2021 |
| Dell          | Precision 5540              | [14a6857b99](https://linux-hardware.org/?probe=14a6857b99) | Dec 18, 2021 |
| MSI           | Katana GF66 11UE            | [56be528067](https://linux-hardware.org/?probe=56be528067) | Dec 18, 2021 |
| Dell          | XPS 15 9500                 | [98e451612c](https://linux-hardware.org/?probe=98e451612c) | Dec 17, 2021 |
| ASUSTek       | ZenBook UX425EA_BX425EA     | [38d349f99c](https://linux-hardware.org/?probe=38d349f99c) | Dec 15, 2021 |
| Dell          | Latitude E6400              | [2936dcb6ab](https://linux-hardware.org/?probe=2936dcb6ab) | Dec 14, 2021 |
| Acer          | Nitro AN515-45              | [d4bed6e3e7](https://linux-hardware.org/?probe=d4bed6e3e7) | Dec 14, 2021 |
| Dell          | Latitude E7450              | [f5f9fd93f9](https://linux-hardware.org/?probe=f5f9fd93f9) | Dec 09, 2021 |
| Lenovo        | ThinkPad X260 20F5S0V400    | [77c3ba8640](https://linux-hardware.org/?probe=77c3ba8640) | Dec 09, 2021 |
| Dell          | Precision 5560              | [2af841d052](https://linux-hardware.org/?probe=2af841d052) | Dec 07, 2021 |
| Dell          | Precision 5560              | [aeba66f4d6](https://linux-hardware.org/?probe=aeba66f4d6) | Dec 07, 2021 |
| HP            | Pavilion dv6                | [479a9e57d5](https://linux-hardware.org/?probe=479a9e57d5) | Dec 07, 2021 |
| HP            | Pavilion dv6                | [98ad56ddcc](https://linux-hardware.org/?probe=98ad56ddcc) | Dec 07, 2021 |
| Lenovo        | B50-70 80EU                 | [80d04f078e](https://linux-hardware.org/?probe=80d04f078e) | Dec 07, 2021 |
| HP            | Compaq CQ58                 | [a859413f86](https://linux-hardware.org/?probe=a859413f86) | Dec 05, 2021 |
| Apple         | MacBookPro14,3              | [b08702eb1e](https://linux-hardware.org/?probe=b08702eb1e) | Dec 05, 2021 |
| HUAWEI        | VLT-WX0                     | [3e01a8673d](https://linux-hardware.org/?probe=3e01a8673d) | Dec 04, 2021 |
| Lenovo        | ThinkPad T410s 292494G      | [f43363fde0](https://linux-hardware.org/?probe=f43363fde0) | Dec 03, 2021 |
| Dell          | XPS 13 9310                 | [fa0051b73b](https://linux-hardware.org/?probe=fa0051b73b) | Dec 02, 2021 |
| Apple         | MacBookPro14,3              | [a7366c8449](https://linux-hardware.org/?probe=a7366c8449) | Dec 02, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [68fffd46cf](https://linux-hardware.org/?probe=68fffd46cf) | Dec 01, 2021 |
| HP            | OMEN Laptop 15-en1xxx       | [fa59cc1ea9](https://linux-hardware.org/?probe=fa59cc1ea9) | Dec 01, 2021 |
| Fujitsu       | LIFEBOOK AH531/GFO          | [5f2264a472](https://linux-hardware.org/?probe=5f2264a472) | Nov 30, 2021 |
| Fujitsu       | LIFEBOOK AH531/GFO          | [af8104b01a](https://linux-hardware.org/?probe=af8104b01a) | Nov 30, 2021 |
| HP            | OMEN Laptop 15-en1xxx       | [66f2018614](https://linux-hardware.org/?probe=66f2018614) | Nov 30, 2021 |
| Toshiba       | Satellite C50-A-19U         | [89f2320bc9](https://linux-hardware.org/?probe=89f2320bc9) | Nov 30, 2021 |
| Acer          | Predator PT315-51           | [b37881e828](https://linux-hardware.org/?probe=b37881e828) | Nov 29, 2021 |
| HP            | EliteBook 8460p             | [56f6b7ec0a](https://linux-hardware.org/?probe=56f6b7ec0a) | Nov 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [a74aec830e](https://linux-hardware.org/?probe=a74aec830e) | Nov 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [af530bb7c7](https://linux-hardware.org/?probe=af530bb7c7) | Nov 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [6056117cca](https://linux-hardware.org/?probe=6056117cca) | Nov 26, 2021 |
| HUAWEI        | KLVL-WXX9                   | [19f2a1dd2f](https://linux-hardware.org/?probe=19f2a1dd2f) | Nov 26, 2021 |
| HUAWEI        | KLVL-WXX9                   | [90f2d59148](https://linux-hardware.org/?probe=90f2d59148) | Nov 26, 2021 |
| Lenovo        | Legion Y540-15IRH 81SX      | [7ac3b720be](https://linux-hardware.org/?probe=7ac3b720be) | Nov 25, 2021 |
| HUAWEI        | KLVL-WXX9                   | [3352efa5cd](https://linux-hardware.org/?probe=3352efa5cd) | Nov 25, 2021 |
| Apple         | MacBookPro10,1              | [27d5b7dc47](https://linux-hardware.org/?probe=27d5b7dc47) | Nov 24, 2021 |
| HP            | Pavilion Notebook           | [ee309c7776](https://linux-hardware.org/?probe=ee309c7776) | Nov 23, 2021 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [0f39f8f706](https://linux-hardware.org/?probe=0f39f8f706) | Nov 22, 2021 |
| Dell          | XPS 13 9370                 | [9f8a07614e](https://linux-hardware.org/?probe=9f8a07614e) | Nov 21, 2021 |
| ASUSTek       | K53U                        | [12136b1cbd](https://linux-hardware.org/?probe=12136b1cbd) | Nov 20, 2021 |
| Lenovo        | ThinkPad T440s 20AR003RM... | [2c0279ade5](https://linux-hardware.org/?probe=2c0279ade5) | Nov 20, 2021 |
| ASUSTek       | K53U                        | [5a5b8c420f](https://linux-hardware.org/?probe=5a5b8c420f) | Nov 20, 2021 |
| Dell          | Latitude E5570              | [48ea4215ad](https://linux-hardware.org/?probe=48ea4215ad) | Nov 18, 2021 |
| Google        | Edgar                       | [0c4bb072e0](https://linux-hardware.org/?probe=0c4bb072e0) | Nov 16, 2021 |
| HP            | ProBook 6450b               | [943ef75a8b](https://linux-hardware.org/?probe=943ef75a8b) | Nov 16, 2021 |
| Dell          | XPS 13 9370                 | [343fdf2e23](https://linux-hardware.org/?probe=343fdf2e23) | Nov 16, 2021 |
| Lenovo        | B50-10 80QR                 | [cb474c37e6](https://linux-hardware.org/?probe=cb474c37e6) | Nov 15, 2021 |
| Lenovo        | ThinkPad 25 20K70000MX      | [86d3ea8b6a](https://linux-hardware.org/?probe=86d3ea8b6a) | Nov 15, 2021 |
| Google        | Edgar                       | [9cb0616971](https://linux-hardware.org/?probe=9cb0616971) | Nov 15, 2021 |
| HP            | Pavilion g7                 | [dbdeebfe86](https://linux-hardware.org/?probe=dbdeebfe86) | Nov 14, 2021 |
| Lenovo        | ThinkPad X260 20F5S0E000    | [2321968d02](https://linux-hardware.org/?probe=2321968d02) | Nov 09, 2021 |
| ASUSTek       | N550JK                      | [23fd9d7d0d](https://linux-hardware.org/?probe=23fd9d7d0d) | Nov 06, 2021 |
| HP            | EliteBook 2570p             | [dc62969834](https://linux-hardware.org/?probe=dc62969834) | Nov 05, 2021 |
| Sony          | VPCCA2S1E                   | [2ce8a8295b](https://linux-hardware.org/?probe=2ce8a8295b) | Nov 05, 2021 |
| HP            | ProBook 640 G1              | [acb5ceea62](https://linux-hardware.org/?probe=acb5ceea62) | Nov 05, 2021 |
| Google        | Grunt                       | [e6c7c07304](https://linux-hardware.org/?probe=e6c7c07304) | Nov 04, 2021 |
| HP            | ZBook 15 G6                 | [36b8c3bedd](https://linux-hardware.org/?probe=36b8c3bedd) | Nov 03, 2021 |
| Lenovo        | ThinkPad T480 20L50009MX    | [349faf5242](https://linux-hardware.org/?probe=349faf5242) | Nov 03, 2021 |
| On by NetO... | LT1.1 BRZ                   | [a520593d47](https://linux-hardware.org/?probe=a520593d47) | Nov 02, 2021 |
| On by NetO... | LT1.1 BRZ                   | [f9312f99c7](https://linux-hardware.org/?probe=f9312f99c7) | Nov 02, 2021 |
| Unknown       | Unknown                     | [ae9e2708e9](https://linux-hardware.org/?probe=ae9e2708e9) | Nov 02, 2021 |
| HP            | Laptop 15-bw0xx             | [1869db225e](https://linux-hardware.org/?probe=1869db225e) | Nov 02, 2021 |
| HP            | ZBook 14 G2                 | [ffb40f821b](https://linux-hardware.org/?probe=ffb40f821b) | Oct 30, 2021 |
| Sony          | VGN-CS31S_W                 | [13451dd6c5](https://linux-hardware.org/?probe=13451dd6c5) | Oct 30, 2021 |
| HP            | ProBook 430 G1              | [15d9329bd3](https://linux-hardware.org/?probe=15d9329bd3) | Oct 28, 2021 |
| ASUSTek       | T100HAN                     | [c518746ece](https://linux-hardware.org/?probe=c518746ece) | Oct 25, 2021 |
| ASUSTek       | T100HAN                     | [5f27dd2f45](https://linux-hardware.org/?probe=5f27dd2f45) | Oct 25, 2021 |
| Acer          | Nitro AN515-45              | [f6ddc3a2da](https://linux-hardware.org/?probe=f6ddc3a2da) | Oct 24, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [e9991e486b](https://linux-hardware.org/?probe=e9991e486b) | Oct 23, 2021 |
| Unknown       | Unknown                     | [470c0932ae](https://linux-hardware.org/?probe=470c0932ae) | Oct 23, 2021 |
| Acer          | Aspire V3-772G              | [10e7ffc71d](https://linux-hardware.org/?probe=10e7ffc71d) | Oct 19, 2021 |
| Lenovo        | ThinkPad T490 20N2005VMX    | [2e44d637e3](https://linux-hardware.org/?probe=2e44d637e3) | Oct 16, 2021 |
| Dell          | Latitude E5250              | [793091ac6a](https://linux-hardware.org/?probe=793091ac6a) | Oct 14, 2021 |
| Google        | Treeya                      | [82b0964b6d](https://linux-hardware.org/?probe=82b0964b6d) | Oct 14, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [c3cdfe0336](https://linux-hardware.org/?probe=c3cdfe0336) | Oct 14, 2021 |
| HP            | EliteBook 830 G6            | [66a9b21300](https://linux-hardware.org/?probe=66a9b21300) | Oct 14, 2021 |
| Google        | Treeya                      | [6c10b9bcb3](https://linux-hardware.org/?probe=6c10b9bcb3) | Oct 14, 2021 |
| ASUSTek       | TP201SA                     | [504956d2e9](https://linux-hardware.org/?probe=504956d2e9) | Oct 13, 2021 |
| eMachines     | G730                        | [6450ba7397](https://linux-hardware.org/?probe=6450ba7397) | Oct 12, 2021 |
| eMachines     | G730                        | [b24afe5dc2](https://linux-hardware.org/?probe=b24afe5dc2) | Oct 12, 2021 |
| Apple         | MacBookAir6,1               | [66f91918dc](https://linux-hardware.org/?probe=66f91918dc) | Oct 12, 2021 |
| Apple         | MacBookAir6,1               | [87403edfc9](https://linux-hardware.org/?probe=87403edfc9) | Oct 11, 2021 |
| Apple         | MacBookAir7,2               | [31ae42bc51](https://linux-hardware.org/?probe=31ae42bc51) | Oct 09, 2021 |
| Apple         | MacBookAir7,2               | [5b47e8efcb](https://linux-hardware.org/?probe=5b47e8efcb) | Oct 09, 2021 |
| ASUSTek       | X550LB                      | [d96d114426](https://linux-hardware.org/?probe=d96d114426) | Oct 06, 2021 |
| HP            | EliteBook 830 G6            | [28ecb03df2](https://linux-hardware.org/?probe=28ecb03df2) | Oct 05, 2021 |
| Dell          | Latitude 5290               | [e3afd1ef97](https://linux-hardware.org/?probe=e3afd1ef97) | Oct 04, 2021 |
| HP            | ProBook 430 G1              | [01109c5fde](https://linux-hardware.org/?probe=01109c5fde) | Oct 04, 2021 |
| Dell          | Precision M6800             | [b85ad62146](https://linux-hardware.org/?probe=b85ad62146) | Oct 03, 2021 |
| Dell          | Precision M6800             | [61a932607b](https://linux-hardware.org/?probe=61a932607b) | Oct 03, 2021 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [46db33820d](https://linux-hardware.org/?probe=46db33820d) | Oct 03, 2021 |
| Lenovo        | G50-80 80E5                 | [133b546e7f](https://linux-hardware.org/?probe=133b546e7f) | Oct 03, 2021 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [9c3c1f9a85](https://linux-hardware.org/?probe=9c3c1f9a85) | Oct 01, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [6876f0e86d](https://linux-hardware.org/?probe=6876f0e86d) | Sep 29, 2021 |
| Lenovo        | IdeaPad 710S Plus-13IKB ... | [4a91c75662](https://linux-hardware.org/?probe=4a91c75662) | Sep 28, 2021 |
| HP            | EliteBook 830 G6            | [72c41f4a85](https://linux-hardware.org/?probe=72c41f4a85) | Sep 27, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [560598d6fb](https://linux-hardware.org/?probe=560598d6fb) | Sep 26, 2021 |
| HP            | Laptop 15s-eq2xxx           | [2460060920](https://linux-hardware.org/?probe=2460060920) | Sep 25, 2021 |
| HP            | Laptop 15s-eq2xxx           | [639131ddd5](https://linux-hardware.org/?probe=639131ddd5) | Sep 25, 2021 |
| ASUSTek       | GL553VE                     | [c55708bb3f](https://linux-hardware.org/?probe=c55708bb3f) | Sep 23, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [df7ff85482](https://linux-hardware.org/?probe=df7ff85482) | Sep 23, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [36c78f1667](https://linux-hardware.org/?probe=36c78f1667) | Sep 23, 2021 |
| HP            | Presario CQ62               | [dc91fe3b30](https://linux-hardware.org/?probe=dc91fe3b30) | Sep 22, 2021 |
| Apple         | MacBookAir7,2               | [83f3d6df86](https://linux-hardware.org/?probe=83f3d6df86) | Sep 21, 2021 |
| Apple         | MacBookPro8,1               | [5b337fdb0a](https://linux-hardware.org/?probe=5b337fdb0a) | Sep 20, 2021 |
| Dell          | Inspiron 14 5410 2-in-1     | [439f4b690a](https://linux-hardware.org/?probe=439f4b690a) | Sep 20, 2021 |
| Dell          | Inspiron 14 5410 2-in-1     | [a9edf67742](https://linux-hardware.org/?probe=a9edf67742) | Sep 20, 2021 |
| Apple         | MacBookPro8,1               | [7c806aa7c5](https://linux-hardware.org/?probe=7c806aa7c5) | Sep 19, 2021 |
| Dell          | Latitude E7450              | [f5963dc359](https://linux-hardware.org/?probe=f5963dc359) | Sep 18, 2021 |
| Dell          | Precision 7720              | [80f3d1e3b0](https://linux-hardware.org/?probe=80f3d1e3b0) | Sep 17, 2021 |
| Dell          | Latitude 5290               | [baae3812d5](https://linux-hardware.org/?probe=baae3812d5) | Sep 14, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [dc1b85b8c9](https://linux-hardware.org/?probe=dc1b85b8c9) | Sep 14, 2021 |
| Lenovo        | G50-80 80E5                 | [ef850713da](https://linux-hardware.org/?probe=ef850713da) | Sep 14, 2021 |
| HP            | EliteBook 820 G1            | [9631d6f9e1](https://linux-hardware.org/?probe=9631d6f9e1) | Sep 14, 2021 |
| Acer          | Swift SF314-511             | [4286a4710c](https://linux-hardware.org/?probe=4286a4710c) | Sep 11, 2021 |
| Acer          | Swift SF114-33              | [31bc470f08](https://linux-hardware.org/?probe=31bc470f08) | Sep 11, 2021 |
| Toshiba       | Satellite L50D-B            | [6eb7be93e9](https://linux-hardware.org/?probe=6eb7be93e9) | Sep 10, 2021 |
| HP            | ProBook 6460b               | [b0f0eaf216](https://linux-hardware.org/?probe=b0f0eaf216) | Sep 09, 2021 |
| HP            | ZBook 17 G3                 | [7e85c2791f](https://linux-hardware.org/?probe=7e85c2791f) | Sep 07, 2021 |
| HP            | ProBook 4540s               | [41d764faaf](https://linux-hardware.org/?probe=41d764faaf) | Sep 06, 2021 |
| PC Special... | N150CU                      | [2fd6f4b53c](https://linux-hardware.org/?probe=2fd6f4b53c) | Sep 05, 2021 |
| HP            | ProBook 6450b               | [960930d457](https://linux-hardware.org/?probe=960930d457) | Sep 04, 2021 |
| HP            | ProBook 6450b               | [98041e0acd](https://linux-hardware.org/?probe=98041e0acd) | Sep 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [d40a00437d](https://linux-hardware.org/?probe=d40a00437d) | Aug 30, 2021 |
| Lenovo        | B51-80 80LM                 | [a81c83bd1c](https://linux-hardware.org/?probe=a81c83bd1c) | Aug 30, 2021 |
| Acer          | Aspire E5-573G              | [78ad2b6854](https://linux-hardware.org/?probe=78ad2b6854) | Aug 27, 2021 |
| Lenovo        | ThinkPad T420s 4174FM9      | [12fd92046e](https://linux-hardware.org/?probe=12fd92046e) | Aug 27, 2021 |
| ASUSTek       | X510UAR                     | [cd238d180b](https://linux-hardware.org/?probe=cd238d180b) | Aug 23, 2021 |
| Toshiba       | Satellite L50D-B            | [1e514cb947](https://linux-hardware.org/?probe=1e514cb947) | Aug 23, 2021 |
| Dell          | Inspiron 7520               | [a8e8ae384a](https://linux-hardware.org/?probe=a8e8ae384a) | Aug 20, 2021 |
| Dell          | XPS 15 9500                 | [6d76e9c22e](https://linux-hardware.org/?probe=6d76e9c22e) | Aug 18, 2021 |
| PC Special... | Standard                    | [b7baa43d24](https://linux-hardware.org/?probe=b7baa43d24) | Aug 18, 2021 |
| MSI           | GP63 Leopard 8RE            | [40a8ec3a95](https://linux-hardware.org/?probe=40a8ec3a95) | Aug 16, 2021 |
| Razer         | Blade                       | [b6bad1f725](https://linux-hardware.org/?probe=b6bad1f725) | Aug 15, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [77c51b6b7b](https://linux-hardware.org/?probe=77c51b6b7b) | Aug 15, 2021 |
| HP            | Pavilion 17                 | [b628f70687](https://linux-hardware.org/?probe=b628f70687) | Aug 15, 2021 |
| Lenovo        | ThinkPad T480s 20L8S3DK1... | [695ac6427d](https://linux-hardware.org/?probe=695ac6427d) | Aug 15, 2021 |
| HP            | Compaq nc6320 (EV073AV)     | [bf6050f750](https://linux-hardware.org/?probe=bf6050f750) | Aug 14, 2021 |
| Lenovo        | ThinkPad X250 20CM001RMS    | [d0dfc1011e](https://linux-hardware.org/?probe=d0dfc1011e) | Aug 12, 2021 |
| Lenovo        | Z50-70 20354                | [1eba114602](https://linux-hardware.org/?probe=1eba114602) | Aug 11, 2021 |
| Lenovo        | Z50-70 20354                | [a31c1f0fda](https://linux-hardware.org/?probe=a31c1f0fda) | Aug 11, 2021 |
| Dell          | Inspiron ME051              | [5ca4e6101b](https://linux-hardware.org/?probe=5ca4e6101b) | Aug 10, 2021 |
| Lenovo        | Z50-70 20354                | [c1209f4d40](https://linux-hardware.org/?probe=c1209f4d40) | Aug 09, 2021 |
| Dell          | Precision M4500             | [d7b650fecf](https://linux-hardware.org/?probe=d7b650fecf) | Aug 09, 2021 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [64784dd9c7](https://linux-hardware.org/?probe=64784dd9c7) | Aug 09, 2021 |
| Dell          | XPS 15 7590                 | [1778263a70](https://linux-hardware.org/?probe=1778263a70) | Aug 08, 2021 |
| Lenovo        | Z50-70 20354                | [9e08265168](https://linux-hardware.org/?probe=9e08265168) | Aug 08, 2021 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [18d1628875](https://linux-hardware.org/?probe=18d1628875) | Aug 07, 2021 |
| HP            | Pavilion 15                 | [73f50567a1](https://linux-hardware.org/?probe=73f50567a1) | Aug 07, 2021 |
| Dell          | Latitude E6400              | [dea83da57d](https://linux-hardware.org/?probe=dea83da57d) | Aug 04, 2021 |
| Packard Be... | EasyNote TS11SB             | [aa9468a3de](https://linux-hardware.org/?probe=aa9468a3de) | Aug 03, 2021 |
| Packard Be... | EasyNote TS11SB             | [57fbaedb1e](https://linux-hardware.org/?probe=57fbaedb1e) | Aug 03, 2021 |
| HP            | Elite x2 1012 G1            | [7c2abb5f03](https://linux-hardware.org/?probe=7c2abb5f03) | Aug 02, 2021 |
| HP            | Pavilion 15                 | [08bd4b9549](https://linux-hardware.org/?probe=08bd4b9549) | Aug 02, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [5cacc2c659](https://linux-hardware.org/?probe=5cacc2c659) | Jul 29, 2021 |
| Toshiba       | Satellite L750              | [822adc34c6](https://linux-hardware.org/?probe=822adc34c6) | Jul 28, 2021 |
| HP            | ProBook 6460b               | [ad2986d747](https://linux-hardware.org/?probe=ad2986d747) | Jul 26, 2021 |
| HP            | Pavilion dv6500             | [896e1bc2a0](https://linux-hardware.org/?probe=896e1bc2a0) | Jul 25, 2021 |
| HP            | Pavilion dv6500             | [1325b6d6c2](https://linux-hardware.org/?probe=1325b6d6c2) | Jul 25, 2021 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | [ed51414a9d](https://linux-hardware.org/?probe=ed51414a9d) | Jul 22, 2021 |
| Lenovo        | ThinkPad T460 20FNS0KT00    | [64c8fe4e52](https://linux-hardware.org/?probe=64c8fe4e52) | Jul 20, 2021 |
| Dell          | Vostro 3500                 | [2e8c9fa212](https://linux-hardware.org/?probe=2e8c9fa212) | Jul 18, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | [cdf0f4017c](https://linux-hardware.org/?probe=cdf0f4017c) | Jul 16, 2021 |
| Intel Clie... | LAPBC710                    | [49a2ccdeee](https://linux-hardware.org/?probe=49a2ccdeee) | Jul 12, 2021 |
| HP            | Pavilion 15                 | [b4eeb3105e](https://linux-hardware.org/?probe=b4eeb3105e) | Jul 12, 2021 |
| HP            | Pavilion dv6                | [bb0f20f7a9](https://linux-hardware.org/?probe=bb0f20f7a9) | Jul 10, 2021 |
| Lenovo        | ThinkPad X220 4286CTO       | [8845d0216e](https://linux-hardware.org/?probe=8845d0216e) | Jul 09, 2021 |
| HP            | Elite x2 1012 G1            | [4d5cea91ad](https://linux-hardware.org/?probe=4d5cea91ad) | Jul 07, 2021 |
| HP            | EliteBook 8470p             | [505684a737](https://linux-hardware.org/?probe=505684a737) | Jul 07, 2021 |
| Apple         | MacBookPro11,5              | [43d77edd56](https://linux-hardware.org/?probe=43d77edd56) | Jul 01, 2021 |
| Lenovo        | ThinkPad T460s 20FAS2L60... | [c0ba9a0437](https://linux-hardware.org/?probe=c0ba9a0437) | Jun 30, 2021 |
| Apple         | MacBookPro11,5              | [103c0edcbd](https://linux-hardware.org/?probe=103c0edcbd) | Jun 30, 2021 |
| Lenovo        | ThinkPad T460 20FMS06105    | [242cf25827](https://linux-hardware.org/?probe=242cf25827) | Jun 29, 2021 |
| Lenovo        | ThinkPad X201 3626FAG       | [259908557b](https://linux-hardware.org/?probe=259908557b) | Jun 28, 2021 |
| Toshiba       | Satellite L855              | [45df91892a](https://linux-hardware.org/?probe=45df91892a) | Jun 27, 2021 |
| Toshiba       | Satellite L855              | [5fc995dac3](https://linux-hardware.org/?probe=5fc995dac3) | Jun 27, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [392be37a79](https://linux-hardware.org/?probe=392be37a79) | Jun 25, 2021 |
| Lenovo        | Legion 5 17IMH05H 81Y8      | [6995133402](https://linux-hardware.org/?probe=6995133402) | Jun 24, 2021 |
| Lenovo        | B50-30 80ES                 | [b9d0b5be2d](https://linux-hardware.org/?probe=b9d0b5be2d) | Jun 23, 2021 |
| ASUSTek       | ROG Strix G731GW_G731GW     | [85a0c7c512](https://linux-hardware.org/?probe=85a0c7c512) | Jun 23, 2021 |
| Lenovo        | B50-30 80ES                 | [e2b40afe3c](https://linux-hardware.org/?probe=e2b40afe3c) | Jun 23, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [e4ba771332](https://linux-hardware.org/?probe=e4ba771332) | Jun 22, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [495c04a536](https://linux-hardware.org/?probe=495c04a536) | Jun 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c1abf6c844](https://linux-hardware.org/?probe=c1abf6c844) | Jun 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [aa95a9d75f](https://linux-hardware.org/?probe=aa95a9d75f) | Jun 20, 2021 |
| Lenovo        | IdeaPadFlex 15 20309        | [7a60f78b32](https://linux-hardware.org/?probe=7a60f78b32) | Jun 17, 2021 |
| HP            | ZBook 17 G2                 | [3342d4d378](https://linux-hardware.org/?probe=3342d4d378) | Jun 17, 2021 |
| HP            | EliteBook 725 G3            | [f57f7d1e53](https://linux-hardware.org/?probe=f57f7d1e53) | Jun 16, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [0e1e07507e](https://linux-hardware.org/?probe=0e1e07507e) | Jun 15, 2021 |
| Dell          | Latitude 3350               | [7fe0552d03](https://linux-hardware.org/?probe=7fe0552d03) | Jun 14, 2021 |
| Dell          | XPS 17 9700                 | [293537d794](https://linux-hardware.org/?probe=293537d794) | Jun 11, 2021 |
| HP            | ZBook 17 G2                 | [05a2ecf3ec](https://linux-hardware.org/?probe=05a2ecf3ec) | Jun 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [48bda0fbd3](https://linux-hardware.org/?probe=48bda0fbd3) | Jun 09, 2021 |
| Lenovo        | ThinkPad X201 4492W36       | [f309552e6e](https://linux-hardware.org/?probe=f309552e6e) | Jun 07, 2021 |
| Sony          | VPCCA2S1E                   | [6b20cf032f](https://linux-hardware.org/?probe=6b20cf032f) | Jun 05, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [117372a8ff](https://linux-hardware.org/?probe=117372a8ff) | Jun 05, 2021 |
| Lenovo        | Yoga 700-14ISK 80QD         | [6946ffb375](https://linux-hardware.org/?probe=6946ffb375) | Jun 03, 2021 |
| Dell          | Latitude 9520               | [10a4c770cf](https://linux-hardware.org/?probe=10a4c770cf) | Jun 02, 2021 |
| Lenovo        | Yoga 700-14ISK 80QD         | [d8507e3c64](https://linux-hardware.org/?probe=d8507e3c64) | Jun 01, 2021 |
| Apple         | MacBookPro12,1              | [f7f5736b13](https://linux-hardware.org/?probe=f7f5736b13) | Jun 01, 2021 |
| HP            | EliteBook Revolve 810       | [24758ed5b3](https://linux-hardware.org/?probe=24758ed5b3) | May 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [cad013a6a5](https://linux-hardware.org/?probe=cad013a6a5) | May 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [af407b12e2](https://linux-hardware.org/?probe=af407b12e2) | May 29, 2021 |
| HP            | EliteBook Folio 9470m       | [8c36612ff4](https://linux-hardware.org/?probe=8c36612ff4) | May 26, 2021 |
| HP            | ZBook 17 G2                 | [5e10971a64](https://linux-hardware.org/?probe=5e10971a64) | May 25, 2021 |
| Apple         | MacBookPro6,1               | [a0012821b7](https://linux-hardware.org/?probe=a0012821b7) | May 25, 2021 |
| Dell          | Latitude D520               | [7a817a0426](https://linux-hardware.org/?probe=7a817a0426) | May 25, 2021 |
| HP            | EliteBook Revolve 810 G3    | [e0068ae9b7](https://linux-hardware.org/?probe=e0068ae9b7) | May 23, 2021 |
| PC Special... | N150CU                      | [eebe654729](https://linux-hardware.org/?probe=eebe654729) | May 22, 2021 |
| PC Special... | N150CU                      | [99d75e799f](https://linux-hardware.org/?probe=99d75e799f) | May 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [d5ea76578b](https://linux-hardware.org/?probe=d5ea76578b) | May 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [0ccd96a39e](https://linux-hardware.org/?probe=0ccd96a39e) | May 21, 2021 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [828f345230](https://linux-hardware.org/?probe=828f345230) | May 19, 2021 |
| Dell          | Precision 5540              | [91e4aff19e](https://linux-hardware.org/?probe=91e4aff19e) | May 17, 2021 |
| Dell          | Latitude 3350               | [f4e6b7cf7f](https://linux-hardware.org/?probe=f4e6b7cf7f) | May 15, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [ae6af1c7e1](https://linux-hardware.org/?probe=ae6af1c7e1) | May 14, 2021 |
| HP            | EliteBook 850 G3            | [cb589a4d2c](https://linux-hardware.org/?probe=cb589a4d2c) | May 14, 2021 |
| HP            | EliteBook 850 G3            | [00a23f1149](https://linux-hardware.org/?probe=00a23f1149) | May 14, 2021 |
| Dell          | Latitude 3350               | [bb64b2df5c](https://linux-hardware.org/?probe=bb64b2df5c) | May 13, 2021 |
| Lenovo        | Legion 7 15IMH05 81YT       | [461ae5a890](https://linux-hardware.org/?probe=461ae5a890) | May 08, 2021 |
| HP            | EliteBook 850 G3            | [85a71e335a](https://linux-hardware.org/?probe=85a71e335a) | May 06, 2021 |
| Dell          | XPS 13 9310                 | [5103d9a329](https://linux-hardware.org/?probe=5103d9a329) | May 06, 2021 |
| Dell          | XPS 13 9310                 | [951fb73d61](https://linux-hardware.org/?probe=951fb73d61) | May 06, 2021 |
| Apple         | MacBookPro14,1              | [f1b3020464](https://linux-hardware.org/?probe=f1b3020464) | May 03, 2021 |
| ASUSTek       | X502CA                      | [6763e02e82](https://linux-hardware.org/?probe=6763e02e82) | Apr 30, 2021 |
| Dell          | XPS 17 9700                 | [02dae8d8ba](https://linux-hardware.org/?probe=02dae8d8ba) | Apr 24, 2021 |
| Lenovo        | ThinkPad T560 20FHCTO1WW    | [0d0db8039c](https://linux-hardware.org/?probe=0d0db8039c) | Apr 24, 2021 |
| HP            | Compaq 6730s                | [31fa38668e](https://linux-hardware.org/?probe=31fa38668e) | Apr 23, 2021 |
| HP            | Compaq 6730s                | [ad60afcbe6](https://linux-hardware.org/?probe=ad60afcbe6) | Apr 23, 2021 |
| HP            | ProBook 430 G2              | [03a0b4cf9d](https://linux-hardware.org/?probe=03a0b4cf9d) | Apr 22, 2021 |
| HP            | ProBook 430 G2              | [9f9065affa](https://linux-hardware.org/?probe=9f9065affa) | Apr 22, 2021 |
| HP            | Pavilion dv8000 (EW858EA... | [b64833b0b1](https://linux-hardware.org/?probe=b64833b0b1) | Apr 21, 2021 |
| HP            | Pavilion dv8000 (EW858EA... | [e378a38500](https://linux-hardware.org/?probe=e378a38500) | Apr 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [9f3189e59c](https://linux-hardware.org/?probe=9f3189e59c) | Apr 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [644309ff4c](https://linux-hardware.org/?probe=644309ff4c) | Apr 20, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [2e1606428e](https://linux-hardware.org/?probe=2e1606428e) | Apr 19, 2021 |
| Dell          | XPS 13 9343                 | [fd2c114081](https://linux-hardware.org/?probe=fd2c114081) | Apr 19, 2021 |
| Dell          | XPS 13 9343                 | [2d99520074](https://linux-hardware.org/?probe=2d99520074) | Apr 19, 2021 |
| Dell          | XPS 17 9700                 | [84387a75f7](https://linux-hardware.org/?probe=84387a75f7) | Apr 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [5d66639b00](https://linux-hardware.org/?probe=5d66639b00) | Apr 17, 2021 |
| Toshiba       | Satellite A300              | [37b42247f5](https://linux-hardware.org/?probe=37b42247f5) | Apr 17, 2021 |
| Toshiba       | Satellite A300              | [d0c0ba115d](https://linux-hardware.org/?probe=d0c0ba115d) | Apr 17, 2021 |
| Dell          | Latitude D520               | [4e8b58ab28](https://linux-hardware.org/?probe=4e8b58ab28) | Apr 16, 2021 |
| ASUSTek       | N53SN                       | [97b4a56f7d](https://linux-hardware.org/?probe=97b4a56f7d) | Apr 16, 2021 |
| Dell          | Precision 3551              | [4e9b5b097e](https://linux-hardware.org/?probe=4e9b5b097e) | Apr 15, 2021 |
| Dell          | Precision 5540              | [a171f512e1](https://linux-hardware.org/?probe=a171f512e1) | Apr 14, 2021 |
| ASUSTek       | G751JY                      | [914c959acf](https://linux-hardware.org/?probe=914c959acf) | Apr 13, 2021 |
| Acer          | Aspire 5560                 | [bc4d7942f2](https://linux-hardware.org/?probe=bc4d7942f2) | Apr 13, 2021 |
| Acer          | Aspire 5560                 | [c01ef90ff1](https://linux-hardware.org/?probe=c01ef90ff1) | Apr 13, 2021 |
| Lenovo        | ThinkPad X390 20Q00056MX    | [377be16b54](https://linux-hardware.org/?probe=377be16b54) | Apr 13, 2021 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [8ed94ed92f](https://linux-hardware.org/?probe=8ed94ed92f) | Apr 12, 2021 |
| Lenovo        | ThinkPad X270 20HMS27Q00    | [6a307c820d](https://linux-hardware.org/?probe=6a307c820d) | Apr 12, 2021 |
| Dell          | XPS 15 9560                 | [6dd46ebb68](https://linux-hardware.org/?probe=6dd46ebb68) | Apr 11, 2021 |
| Dell          | Latitude 3350               | [347c1e4246](https://linux-hardware.org/?probe=347c1e4246) | Apr 11, 2021 |
| Lenovo        | ThinkPad W541 20EF000UMN    | [f366b44668](https://linux-hardware.org/?probe=f366b44668) | Apr 11, 2021 |
| Dell          | Precision 7740              | [e00242182c](https://linux-hardware.org/?probe=e00242182c) | Apr 10, 2021 |
| Dell          | Precision 7740              | [5b18086d86](https://linux-hardware.org/?probe=5b18086d86) | Apr 10, 2021 |
| ASUSTek       | 1008HA                      | [efa68e1607](https://linux-hardware.org/?probe=efa68e1607) | Apr 09, 2021 |
| Apple         | MacBookPro9,2               | [8fe0fefb60](https://linux-hardware.org/?probe=8fe0fefb60) | Apr 09, 2021 |
| HP            | EliteBook 2740p             | [6604ebcf44](https://linux-hardware.org/?probe=6604ebcf44) | Apr 09, 2021 |
| HP            | Compaq 6730b (NN204ET#AK... | [3d9460ecd7](https://linux-hardware.org/?probe=3d9460ecd7) | Apr 08, 2021 |
| Lenovo        | B575e 36852EG               | [494789235b](https://linux-hardware.org/?probe=494789235b) | Apr 08, 2021 |
| Acer          | Aspire VN7-793G             | [881e9bb0dd](https://linux-hardware.org/?probe=881e9bb0dd) | Apr 06, 2021 |
| Acer          | Aspire VN7-793G             | [cd805ae4e6](https://linux-hardware.org/?probe=cd805ae4e6) | Apr 06, 2021 |
| Lenovo        | ThinkPad T440s 20AR003RM... | [9c7afa6f8c](https://linux-hardware.org/?probe=9c7afa6f8c) | Apr 06, 2021 |
| ASUSTek       | 1008HA                      | [8819e810d5](https://linux-hardware.org/?probe=8819e810d5) | Apr 05, 2021 |
| HP            | EliteBook 840 G3            | [9bb8d87d34](https://linux-hardware.org/?probe=9bb8d87d34) | Apr 05, 2021 |
| HP            | EliteBook 840 G3            | [1e04362858](https://linux-hardware.org/?probe=1e04362858) | Apr 05, 2021 |
| HP            | EliteBook 840 G3            | [4c92681db0](https://linux-hardware.org/?probe=4c92681db0) | Apr 05, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [6a799a77de](https://linux-hardware.org/?probe=6a799a77de) | Apr 05, 2021 |
| Dell          | Latitude E6430              | [cef48a7c98](https://linux-hardware.org/?probe=cef48a7c98) | Apr 05, 2021 |
| Lenovo        | ThinkPad 11e 3rd Gen 20G... | [d8320bacb4](https://linux-hardware.org/?probe=d8320bacb4) | Apr 05, 2021 |
| Dell          | Latitude E6430              | [8e76a74a21](https://linux-hardware.org/?probe=8e76a74a21) | Apr 04, 2021 |
| ASUSTek       | 1008HA                      | [1045f8543a](https://linux-hardware.org/?probe=1045f8543a) | Apr 04, 2021 |
| Lenovo        | ThinkPad E580 20KS001QMX    | [28b80e551f](https://linux-hardware.org/?probe=28b80e551f) | Apr 04, 2021 |
| HP            | Laptop 17-ca1xxx            | [e21ac181a5](https://linux-hardware.org/?probe=e21ac181a5) | Apr 03, 2021 |
| Dell          | Precision 7540              | [9ad15db73f](https://linux-hardware.org/?probe=9ad15db73f) | Apr 02, 2021 |
| Apple         | MacBookPro8,1               | [6632391038](https://linux-hardware.org/?probe=6632391038) | Apr 02, 2021 |
| Dell          | XPS 15 9560                 | [dd4081dc68](https://linux-hardware.org/?probe=dd4081dc68) | Apr 02, 2021 |
| ASUSTek       | U32U                        | [2842f61fc9](https://linux-hardware.org/?probe=2842f61fc9) | Apr 02, 2021 |
| PC Special... | N150CU                      | [f0729cc9bf](https://linux-hardware.org/?probe=f0729cc9bf) | Apr 01, 2021 |
| PC Special... | N150CU                      | [39136d47f7](https://linux-hardware.org/?probe=39136d47f7) | Apr 01, 2021 |
| Dell          | Latitude 3350               | [9e3b1f256c](https://linux-hardware.org/?probe=9e3b1f256c) | Apr 01, 2021 |
| Lenovo        | ThinkPad X240 20AMS1WW0X    | [1f98cf2913](https://linux-hardware.org/?probe=1f98cf2913) | Mar 31, 2021 |
| Lenovo        | ThinkPad T440s 20AR003RM... | [286287736b](https://linux-hardware.org/?probe=286287736b) | Mar 31, 2021 |
| Gigabyte      | AERO 15-SA                  | [26957c118d](https://linux-hardware.org/?probe=26957c118d) | Mar 30, 2021 |
| Dell          | Latitude E6430              | [5989458f51](https://linux-hardware.org/?probe=5989458f51) | Mar 29, 2021 |
| HP            | ProBook 4540s               | [6999b29045](https://linux-hardware.org/?probe=6999b29045) | Mar 29, 2021 |
| HP            | ProBook 440 G5              | [6c5ee38371](https://linux-hardware.org/?probe=6c5ee38371) | Mar 27, 2021 |
| Acer          | Aspire E5-575G              | [d96f9a5cd5](https://linux-hardware.org/?probe=d96f9a5cd5) | Mar 27, 2021 |
| Lenovo        | ThinkPad T430s 2356DH2      | [86d756fb89](https://linux-hardware.org/?probe=86d756fb89) | Mar 27, 2021 |
| HP            | ProBook 440 G5              | [46ffef3efa](https://linux-hardware.org/?probe=46ffef3efa) | Mar 27, 2021 |
| Dell          | XPS 15 7590                 | [6727afc25e](https://linux-hardware.org/?probe=6727afc25e) | Mar 25, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | [57162c4f3e](https://linux-hardware.org/?probe=57162c4f3e) | Mar 24, 2021 |
| Lenovo        | ThinkPad T420 4180AZ5       | [4b39173927](https://linux-hardware.org/?probe=4b39173927) | Mar 23, 2021 |
| HP            | ProBook 4540s               | [3eebedc4c6](https://linux-hardware.org/?probe=3eebedc4c6) | Mar 23, 2021 |
| HP            | ProBook 4540s               | [96a4aad39a](https://linux-hardware.org/?probe=96a4aad39a) | Mar 23, 2021 |
| HP            | Laptop 15-da1xxx            | [3a2dc8930d](https://linux-hardware.org/?probe=3a2dc8930d) | Mar 22, 2021 |
| Dell          | Precision 7540              | [b5273482f4](https://linux-hardware.org/?probe=b5273482f4) | Mar 21, 2021 |
| Dell          | Vostro 15-3568              | [2c8acbf86c](https://linux-hardware.org/?probe=2c8acbf86c) | Mar 21, 2021 |
| ASUSTek       | X555LD                      | [90646a2169](https://linux-hardware.org/?probe=90646a2169) | Mar 20, 2021 |
| Acer          | Aspire 5742G                | [da8880b543](https://linux-hardware.org/?probe=da8880b543) | Mar 19, 2021 |
| Acer          | Aspire 5742G                | [047a34bb2c](https://linux-hardware.org/?probe=047a34bb2c) | Mar 19, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [f991500c35](https://linux-hardware.org/?probe=f991500c35) | Mar 18, 2021 |
| Dell          | Latitude E4310              | [edbe42639c](https://linux-hardware.org/?probe=edbe42639c) | Mar 17, 2021 |
| HP            | EliteBook Folio 9470m       | [30efdef045](https://linux-hardware.org/?probe=30efdef045) | Mar 15, 2021 |
| HP            | EliteBook 2570p             | [3bf2664982](https://linux-hardware.org/?probe=3bf2664982) | Mar 14, 2021 |
| ASUSTek       | X580VD                      | [968d9a1d18](https://linux-hardware.org/?probe=968d9a1d18) | Mar 14, 2021 |
| ASUSTek       | X580VD                      | [e10f767f8d](https://linux-hardware.org/?probe=e10f767f8d) | Mar 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [44775f7ea2](https://linux-hardware.org/?probe=44775f7ea2) | Mar 12, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80XK      | [5d7090421a](https://linux-hardware.org/?probe=5d7090421a) | Mar 12, 2021 |
| MSI           | GX60 1AC                    | [774db4f685](https://linux-hardware.org/?probe=774db4f685) | Mar 12, 2021 |
| HP            | EliteBook 840 G2            | [e90e4463c7](https://linux-hardware.org/?probe=e90e4463c7) | Mar 11, 2021 |
| HP            | Compaq 8710w                | [2b1ffee1d7](https://linux-hardware.org/?probe=2b1ffee1d7) | Mar 11, 2021 |
| Acer          | AOD255E                     | [cacd668025](https://linux-hardware.org/?probe=cacd668025) | Mar 10, 2021 |
| PC Special... | N150CU                      | [50a23abcf2](https://linux-hardware.org/?probe=50a23abcf2) | Mar 09, 2021 |
| Dell          | Precision 5540              | [e3aca0cdf9](https://linux-hardware.org/?probe=e3aca0cdf9) | Mar 09, 2021 |
| Dell          | Latitude E7250              | [76aeabfc6d](https://linux-hardware.org/?probe=76aeabfc6d) | Mar 07, 2021 |
| Dell          | XPS 13 9310                 | [5754ce9311](https://linux-hardware.org/?probe=5754ce9311) | Mar 02, 2021 |
| HP            | Laptop 17-ca1xxx            | [a8a82ba1b9](https://linux-hardware.org/?probe=a8a82ba1b9) | Mar 01, 2021 |
| Fujitsu       | LIFEBOOK U745               | [2acf51105b](https://linux-hardware.org/?probe=2acf51105b) | Feb 28, 2021 |
| Intel         | SLIMBOOK                    | [36bbd7056a](https://linux-hardware.org/?probe=36bbd7056a) | Feb 28, 2021 |
| Dell          | Latitude E7450              | [dfb4275179](https://linux-hardware.org/?probe=dfb4275179) | Feb 28, 2021 |
| HP            | EliteBook Folio 9470m       | [b9cfaac7a6](https://linux-hardware.org/?probe=b9cfaac7a6) | Feb 27, 2021 |
| ASUSTek       | X202EV                      | [1c1369ff15](https://linux-hardware.org/?probe=1c1369ff15) | Feb 25, 2021 |
| HP            | EliteBook 830 G5            | [65135f4810](https://linux-hardware.org/?probe=65135f4810) | Feb 24, 2021 |
| HP            | EliteBook 820 G2            | [50dcf0521d](https://linux-hardware.org/?probe=50dcf0521d) | Feb 24, 2021 |
| Lenovo        | ThinkPad L590 20Q8S75F01    | [ae827c1e6b](https://linux-hardware.org/?probe=ae827c1e6b) | Feb 24, 2021 |
| Dell          | Precision M4800             | [744b7bc3a5](https://linux-hardware.org/?probe=744b7bc3a5) | Feb 23, 2021 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [a05ca7a665](https://linux-hardware.org/?probe=a05ca7a665) | Feb 23, 2021 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [2009ef0f7f](https://linux-hardware.org/?probe=2009ef0f7f) | Feb 23, 2021 |
| HP            | EliteBook 2570p             | [f3e1294a65](https://linux-hardware.org/?probe=f3e1294a65) | Feb 23, 2021 |
| Dell          | Latitude E6540              | [550d35b65b](https://linux-hardware.org/?probe=550d35b65b) | Feb 20, 2021 |
| HP            | ProBook 4330s               | [01954b26a9](https://linux-hardware.org/?probe=01954b26a9) | Feb 20, 2021 |
| ASUSTek       | UX430UQ                     | [3dce65d104](https://linux-hardware.org/?probe=3dce65d104) | Feb 19, 2021 |
| ASUSTek       | UX430UQ                     | [11cebb071c](https://linux-hardware.org/?probe=11cebb071c) | Feb 19, 2021 |
| Sony          | VPCF23C5E                   | [fdfa46f36e](https://linux-hardware.org/?probe=fdfa46f36e) | Feb 19, 2021 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [fe2c72978e](https://linux-hardware.org/?probe=fe2c72978e) | Feb 19, 2021 |
| Lenovo        | ThinkPad L590 20Q8S75F01    | [39d098054a](https://linux-hardware.org/?probe=39d098054a) | Feb 18, 2021 |
| Dell          | Vostro 3500                 | [bd2b4fae3a](https://linux-hardware.org/?probe=bd2b4fae3a) | Feb 18, 2021 |
| Dell          | Latitude 5480               | [41472dbe02](https://linux-hardware.org/?probe=41472dbe02) | Feb 18, 2021 |
| HP            | Compaq 6510b (GB867ET#AK... | [c9c18dfdeb](https://linux-hardware.org/?probe=c9c18dfdeb) | Feb 16, 2021 |
| Acer          | Aspire 5750G                | [84855d9ab6](https://linux-hardware.org/?probe=84855d9ab6) | Feb 14, 2021 |
| BOX           | W54_W94_W955TU,-T,-C        | [45730a0879](https://linux-hardware.org/?probe=45730a0879) | Feb 14, 2021 |
| HP            | Pavilion Notebook           | [065510eb37](https://linux-hardware.org/?probe=065510eb37) | Feb 13, 2021 |
| Lenovo        | ThinkPad Edge E530c 3366... | [e34430353c](https://linux-hardware.org/?probe=e34430353c) | Feb 13, 2021 |
| ASUSTek       | K70IO                       | [4912792c07](https://linux-hardware.org/?probe=4912792c07) | Feb 13, 2021 |
| PC Special... | N150CU                      | [9400902b39](https://linux-hardware.org/?probe=9400902b39) | Feb 13, 2021 |
| HP            | ProBook 640 G1              | [3b37587b81](https://linux-hardware.org/?probe=3b37587b81) | Feb 12, 2021 |
| HP            | ZBook 15                    | [dc1d23b1c6](https://linux-hardware.org/?probe=dc1d23b1c6) | Feb 12, 2021 |
| Acer          | Aspire 5750G                | [4d8c753a43](https://linux-hardware.org/?probe=4d8c753a43) | Feb 09, 2021 |
| HP            | ENVY Notebook               | [c951e2abbd](https://linux-hardware.org/?probe=c951e2abbd) | Feb 07, 2021 |
| Notebook      | N2x0WU                      | [e660e0f0da](https://linux-hardware.org/?probe=e660e0f0da) | Feb 05, 2021 |
| ASUSTek       | G75VW                       | [9fc5da433d](https://linux-hardware.org/?probe=9fc5da433d) | Feb 05, 2021 |
| ASUSTek       | ZenBook 13 UX331UAL         | [918139e56e](https://linux-hardware.org/?probe=918139e56e) | Feb 05, 2021 |
| Lenovo        | ThinkPad E520 11438NG       | [3dcd713cd1](https://linux-hardware.org/?probe=3dcd713cd1) | Feb 05, 2021 |
| Dell          | XPS 13 9310                 | [948271ba61](https://linux-hardware.org/?probe=948271ba61) | Feb 05, 2021 |
| ASUSTek       | UX430UAR                    | [65e796cdaf](https://linux-hardware.org/?probe=65e796cdaf) | Feb 04, 2021 |
| HP            | EliteBook 8440p             | [024180fc49](https://linux-hardware.org/?probe=024180fc49) | Feb 03, 2021 |
| System76      | Galago UltraPro             | [ba1c44690a](https://linux-hardware.org/?probe=ba1c44690a) | Feb 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [e746534229](https://linux-hardware.org/?probe=e746534229) | Feb 01, 2021 |
| HP            | EliteBook 8440p             | [32ea31202d](https://linux-hardware.org/?probe=32ea31202d) | Feb 01, 2021 |
| Dell          | Precision 5550              | [61de611018](https://linux-hardware.org/?probe=61de611018) | Jan 29, 2021 |
| Dell          | Precision 7720              | [c99e4945f6](https://linux-hardware.org/?probe=c99e4945f6) | Jan 29, 2021 |
| Lenovo        | ThinkPad P1 20MDS0LX00      | [19aa307625](https://linux-hardware.org/?probe=19aa307625) | Jan 29, 2021 |
| Notebook      | N350TW                      | [8f873c01cb](https://linux-hardware.org/?probe=8f873c01cb) | Jan 28, 2021 |
| Apple         | MacBookAir7,2               | [cf6599a35b](https://linux-hardware.org/?probe=cf6599a35b) | Jan 27, 2021 |
| ASUSTek       | X550LB                      | [427d6af239](https://linux-hardware.org/?probe=427d6af239) | Jan 25, 2021 |
| ASUSTek       | X550LB                      | [a6a84e8eb2](https://linux-hardware.org/?probe=a6a84e8eb2) | Jan 24, 2021 |
| HP            | EliteBook 8570p             | [a2536bd6fe](https://linux-hardware.org/?probe=a2536bd6fe) | Jan 23, 2021 |
| ASUSTek       | TP300LA                     | [890339ddee](https://linux-hardware.org/?probe=890339ddee) | Jan 22, 2021 |
| Toshiba       | Satellite Pro C50-A-1EK     | [b2b20ad037](https://linux-hardware.org/?probe=b2b20ad037) | Jan 21, 2021 |
| Toshiba       | Satellite Pro C50-A-1EK     | [8718991f34](https://linux-hardware.org/?probe=8718991f34) | Jan 21, 2021 |
| Toshiba       | Satellite Pro C50-A-1EK     | [67a92e99d9](https://linux-hardware.org/?probe=67a92e99d9) | Jan 21, 2021 |
| ASUSTek       | ROG Strix G731GT_G731GT     | [fa99318483](https://linux-hardware.org/?probe=fa99318483) | Jan 21, 2021 |
| Acer          | Aspire V5-561G              | [41a988bc1c](https://linux-hardware.org/?probe=41a988bc1c) | Jan 17, 2021 |
| HP            | EliteBook 2560p             | [92cd0842ee](https://linux-hardware.org/?probe=92cd0842ee) | Jan 15, 2021 |
| Dell          | Vostro 3500                 | [efa4546342](https://linux-hardware.org/?probe=efa4546342) | Jan 14, 2021 |
| ASUSTek       | N53SN                       | [a0fd8f8b91](https://linux-hardware.org/?probe=a0fd8f8b91) | Jan 13, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | [929b0edb33](https://linux-hardware.org/?probe=929b0edb33) | Jan 11, 2021 |
| HP            | EliteBook 2570p             | [731a3aef2a](https://linux-hardware.org/?probe=731a3aef2a) | Jan 10, 2021 |
| Lenovo        | ThinkPad T460 20FN004CMX    | [0f6a89ef2c](https://linux-hardware.org/?probe=0f6a89ef2c) | Jan 10, 2021 |
| Alienware     | 13 R3                       | [d3e331e671](https://linux-hardware.org/?probe=d3e331e671) | Jan 10, 2021 |
| ASUSTek       | TP300LA                     | [67fa6528dc](https://linux-hardware.org/?probe=67fa6528dc) | Jan 09, 2021 |
| HP            | EliteBook 2570p             | [68910248cd](https://linux-hardware.org/?probe=68910248cd) | Jan 09, 2021 |
| Lenovo        | ThinkPad T440s 20AR003RM... | [afdde38feb](https://linux-hardware.org/?probe=afdde38feb) | Jan 08, 2021 |
| Acer          | Aspire V3-571G              | [ae420c0bca](https://linux-hardware.org/?probe=ae420c0bca) | Jan 08, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [55f711c5eb](https://linux-hardware.org/?probe=55f711c5eb) | Jan 08, 2021 |
| Acer          | Aspire 5750G                | [a448a76b2e](https://linux-hardware.org/?probe=a448a76b2e) | Jan 06, 2021 |
| Dell          | Vostro 3559                 | [aa443d9d50](https://linux-hardware.org/?probe=aa443d9d50) | Jan 05, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [ea65a42d36](https://linux-hardware.org/?probe=ea65a42d36) | Jan 05, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [bb226d61ff](https://linux-hardware.org/?probe=bb226d61ff) | Jan 05, 2021 |
| Dell          | Precision M6300             | [5b6ca806fb](https://linux-hardware.org/?probe=5b6ca806fb) | Jan 04, 2021 |
| Notebook      | N350TW                      | [5d6a245e70](https://linux-hardware.org/?probe=5d6a245e70) | Jan 03, 2021 |
| Star Labs     | Lite                        | [02fa9d26a2](https://linux-hardware.org/?probe=02fa9d26a2) | Jan 03, 2021 |
| Dell          | Latitude E4300              | [272cc1ce98](https://linux-hardware.org/?probe=272cc1ce98) | Jan 01, 2021 |
| Star Labs     | Lite                        | [64ec49adf7](https://linux-hardware.org/?probe=64ec49adf7) | Jan 01, 2021 |
| Star Labs     | Lite                        | [8a83fcbe27](https://linux-hardware.org/?probe=8a83fcbe27) | Jan 01, 2021 |
| ASUSTek       | X541UA                      | [7c018503fa](https://linux-hardware.org/?probe=7c018503fa) | Jan 01, 2021 |
| ASUSTek       | X541UA                      | [88a33cb3b7](https://linux-hardware.org/?probe=88a33cb3b7) | Jan 01, 2021 |
| Dell          | Latitude D410               | [26b1a84efa](https://linux-hardware.org/?probe=26b1a84efa) | Dec 31, 2020 |
| Dell          | Latitude D410               | [ef6b6f5048](https://linux-hardware.org/?probe=ef6b6f5048) | Dec 31, 2020 |
| HP            | Compaq nc6400 (RH478EA#A... | [d7fd1a7a8d](https://linux-hardware.org/?probe=d7fd1a7a8d) | Dec 31, 2020 |
| Dell          | Latitude D410               | [6d20834f6e](https://linux-hardware.org/?probe=6d20834f6e) | Dec 30, 2020 |
| Dell          | Latitude D410               | [341284656b](https://linux-hardware.org/?probe=341284656b) | Dec 29, 2020 |
| Apple         | MacBookPro12,1              | [e60ff2c9ad](https://linux-hardware.org/?probe=e60ff2c9ad) | Dec 28, 2020 |
| HP            | Compaq 6510b (GB867ET#AK... | [65279b81c8](https://linux-hardware.org/?probe=65279b81c8) | Dec 28, 2020 |
| HP            | 255 G2                      | [c0f14d1c9f](https://linux-hardware.org/?probe=c0f14d1c9f) | Dec 28, 2020 |
| HP            | ProBook 4330s               | [d6c9d261b3](https://linux-hardware.org/?probe=d6c9d261b3) | Dec 28, 2020 |
| EUROCOM       | Tornado F5                  | [f38086ba01](https://linux-hardware.org/?probe=f38086ba01) | Dec 27, 2020 |
| Packard Be... | EasyNote TK85               | [5fd111e9bf](https://linux-hardware.org/?probe=5fd111e9bf) | Dec 27, 2020 |
| Packard Be... | EasyNote TK85               | [cc2c8a071d](https://linux-hardware.org/?probe=cc2c8a071d) | Dec 26, 2020 |
| ASUSTek       | N56DY                       | [4ff3c1bbac](https://linux-hardware.org/?probe=4ff3c1bbac) | Dec 25, 2020 |
| ASUSTek       | N56DY                       | [5f0b1bccdd](https://linux-hardware.org/?probe=5f0b1bccdd) | Dec 25, 2020 |
| EUROCOM       | Tornado F5                  | [31028ce28e](https://linux-hardware.org/?probe=31028ce28e) | Dec 25, 2020 |
| Samsung       | RC420/RC520/RC720           | [2621a1f2f7](https://linux-hardware.org/?probe=2621a1f2f7) | Dec 24, 2020 |
| PC Special... | N150CU                      | [91fa48cbba](https://linux-hardware.org/?probe=91fa48cbba) | Dec 23, 2020 |
| HP            | ProBook 4330s               | [c49ab6d1cd](https://linux-hardware.org/?probe=c49ab6d1cd) | Dec 23, 2020 |
| HP            | ProBook 4330s               | [3faa3f96b5](https://linux-hardware.org/?probe=3faa3f96b5) | Dec 23, 2020 |
| HP            | ENVY Spectre XT Ultraboo... | [fb90fb35ab](https://linux-hardware.org/?probe=fb90fb35ab) | Dec 21, 2020 |
| HP            | EliteBook Revolve 810       | [b6b29c8237](https://linux-hardware.org/?probe=b6b29c8237) | Dec 17, 2020 |
| ASUSTek       | UX430UAR                    | [27e6c318cf](https://linux-hardware.org/?probe=27e6c318cf) | Dec 17, 2020 |
| Dell          | Latitude E6430              | [f579dcf588](https://linux-hardware.org/?probe=f579dcf588) | Dec 16, 2020 |
| MSI           | GE70 2OC\2OE                | [60dea2620f](https://linux-hardware.org/?probe=60dea2620f) | Dec 15, 2020 |
| Lenovo        | ThinkPad T440s 20AR003RM... | [435ab3dc8c](https://linux-hardware.org/?probe=435ab3dc8c) | Dec 15, 2020 |
| Acer          | Aspire V3-571               | [7d0c6ab7b1](https://linux-hardware.org/?probe=7d0c6ab7b1) | Dec 14, 2020 |
| ASUSTek       | UL50VT                      | [693b14d7bc](https://linux-hardware.org/?probe=693b14d7bc) | Dec 14, 2020 |
| Sony          | VGN-FZ31M                   | [a66ff4c9f1](https://linux-hardware.org/?probe=a66ff4c9f1) | Dec 13, 2020 |
| Lenovo        | V14-IWL 81YB                | [5b1407d6e4](https://linux-hardware.org/?probe=5b1407d6e4) | Dec 11, 2020 |
| Dell          | XPS 17 9700                 | [c86faa6047](https://linux-hardware.org/?probe=c86faa6047) | Dec 11, 2020 |
| Lenovo        | ThinkPad X61s 76693JG       | [037685f512](https://linux-hardware.org/?probe=037685f512) | Dec 10, 2020 |
| Lenovo        | ThinkPad P51 20HH002WMX     | [8eec8ac7f3](https://linux-hardware.org/?probe=8eec8ac7f3) | Dec 09, 2020 |
| Sony          | SVF1521A6EW                 | [b895f1d731](https://linux-hardware.org/?probe=b895f1d731) | Dec 08, 2020 |
| HP            | ProBook 6450b               | [e0290fc13f](https://linux-hardware.org/?probe=e0290fc13f) | Dec 07, 2020 |
| HP            | Pavilion dv9700             | [c2e755bbd2](https://linux-hardware.org/?probe=c2e755bbd2) | Dec 06, 2020 |
| HP            | Pavilion dv7                | [aebd3290e0](https://linux-hardware.org/?probe=aebd3290e0) | Dec 05, 2020 |
| Lenovo        | Y50-70 20378                | [e5069e0526](https://linux-hardware.org/?probe=e5069e0526) | Dec 02, 2020 |
| Dell          | Precision 5540              | [e580d3c815](https://linux-hardware.org/?probe=e580d3c815) | Dec 01, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [c176e7e603](https://linux-hardware.org/?probe=c176e7e603) | Nov 29, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [e4e600f1ed](https://linux-hardware.org/?probe=e4e600f1ed) | Nov 29, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [8b7bafb647](https://linux-hardware.org/?probe=8b7bafb647) | Nov 28, 2020 |
| Packard Be... | EasyNote TE69HW             | [877c539b22](https://linux-hardware.org/?probe=877c539b22) | Nov 27, 2020 |
| Dell          | Latitude E7440              | [7b84406eb7](https://linux-hardware.org/?probe=7b84406eb7) | Nov 25, 2020 |
| Dell          | XPS 15 7590                 | [bfe0a182c7](https://linux-hardware.org/?probe=bfe0a182c7) | Nov 25, 2020 |
| Toshiba       | Satellite L40               | [162b3dae3c](https://linux-hardware.org/?probe=162b3dae3c) | Nov 24, 2020 |
| Toshiba       | Satellite L40               | [65c7d13202](https://linux-hardware.org/?probe=65c7d13202) | Nov 24, 2020 |
| Lenovo        | ThinkPad P1 20MDS0LX00      | [13677ed02e](https://linux-hardware.org/?probe=13677ed02e) | Nov 21, 2020 |
| Lenovo        | ThinkPad P1 20MDS0LX00      | [e77da357d5](https://linux-hardware.org/?probe=e77da357d5) | Nov 19, 2020 |
| Dell          | XPS 15 9500                 | [a550f45f26](https://linux-hardware.org/?probe=a550f45f26) | Nov 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [b1b685d6f2](https://linux-hardware.org/?probe=b1b685d6f2) | Nov 18, 2020 |
| Dell          | XPS 13 9310                 | [1e89c57bd3](https://linux-hardware.org/?probe=1e89c57bd3) | Nov 16, 2020 |
| HP            | ProBook 6570b               | [9d02d072b5](https://linux-hardware.org/?probe=9d02d072b5) | Nov 16, 2020 |
| Lenovo        | ThinkPad X220 4286CTO       | [1279053cad](https://linux-hardware.org/?probe=1279053cad) | Nov 15, 2020 |
| HP            | EliteBook 840 G6            | [6a99d1db55](https://linux-hardware.org/?probe=6a99d1db55) | Nov 15, 2020 |
| Dell          | Latitude E6320              | [61bd7b89c9](https://linux-hardware.org/?probe=61bd7b89c9) | Nov 14, 2020 |
| HP            | EliteBook Revolve 810       | [29b4740f0e](https://linux-hardware.org/?probe=29b4740f0e) | Nov 14, 2020 |
| HP            | EliteBook Revolve 810       | [fc46156f6d](https://linux-hardware.org/?probe=fc46156f6d) | Nov 14, 2020 |
| MSI           | GL62 6QD                    | [aae5c5e2a6](https://linux-hardware.org/?probe=aae5c5e2a6) | Nov 13, 2020 |
| Dell          | XPS 13 9310                 | [80343cf550](https://linux-hardware.org/?probe=80343cf550) | Nov 11, 2020 |
| Dell          | Latitude E6320              | [0b28ed3b69](https://linux-hardware.org/?probe=0b28ed3b69) | Nov 11, 2020 |
| Acer          | Aspire E5-521               | [65830eafc6](https://linux-hardware.org/?probe=65830eafc6) | Nov 10, 2020 |
| MSI           | GL73 8RC                    | [44f82bfc01](https://linux-hardware.org/?probe=44f82bfc01) | Nov 09, 2020 |
| Lenovo        | G560 0679                   | [b3a54d7dd5](https://linux-hardware.org/?probe=b3a54d7dd5) | Nov 09, 2020 |
| Lenovo        | V110-14IAP 80TF             | [62946a2f8c](https://linux-hardware.org/?probe=62946a2f8c) | Nov 09, 2020 |
| Dell          | Latitude E6320              | [0157c2fcb3](https://linux-hardware.org/?probe=0157c2fcb3) | Nov 08, 2020 |
| Lenovo        | ThinkPad L440 20ASS34900    | [0320af5232](https://linux-hardware.org/?probe=0320af5232) | Nov 08, 2020 |
| Lenovo        | ThinkPad T440s 20AR003RM... | [fbb029244c](https://linux-hardware.org/?probe=fbb029244c) | Nov 07, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [91f7303817](https://linux-hardware.org/?probe=91f7303817) | Nov 06, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [543c444fdf](https://linux-hardware.org/?probe=543c444fdf) | Nov 05, 2020 |
| Dell          | Latitude 3350               | [a8f5719a0a](https://linux-hardware.org/?probe=a8f5719a0a) | Nov 05, 2020 |
| Acer          | Aspire VN7-593G             | [3892565ed3](https://linux-hardware.org/?probe=3892565ed3) | Nov 04, 2020 |
| Dell          | Latitude 3350               | [65f4e655fc](https://linux-hardware.org/?probe=65f4e655fc) | Nov 03, 2020 |
| MSI           | GP60 2PE                    | [826e175164](https://linux-hardware.org/?probe=826e175164) | Nov 01, 2020 |
| MSI           | GP60 2PE                    | [ea487475af](https://linux-hardware.org/?probe=ea487475af) | Oct 31, 2020 |
| MSI           | GL62 6QD                    | [6768f07648](https://linux-hardware.org/?probe=6768f07648) | Oct 28, 2020 |
| Dell          | Latitude E7470              | [890fea6488](https://linux-hardware.org/?probe=890fea6488) | Oct 27, 2020 |
| Fujitsu Si... | AMILO Notebook Pa 3553      | [68f95ea08d](https://linux-hardware.org/?probe=68f95ea08d) | Oct 25, 2020 |
| Fujitsu Si... | AMILO Notebook Pa 3553      | [2487ba73b1](https://linux-hardware.org/?probe=2487ba73b1) | Oct 25, 2020 |
| Lenovo        | ThinkPad A485 20MU000DMX    | [3d919ab14e](https://linux-hardware.org/?probe=3d919ab14e) | Oct 23, 2020 |
| Acer          | Nitro AN515-52              | [fd1a6f5055](https://linux-hardware.org/?probe=fd1a6f5055) | Oct 22, 2020 |
| HP            | ZBook 15                    | [83e4ff7f1b](https://linux-hardware.org/?probe=83e4ff7f1b) | Oct 20, 2020 |
| HP            | ZBook 15                    | [1de0f37e99](https://linux-hardware.org/?probe=1de0f37e99) | Oct 20, 2020 |
| HP            | ProBook 450 G3              | [a1767ad1a4](https://linux-hardware.org/?probe=a1767ad1a4) | Oct 17, 2020 |
| HP            | ProBook 450 G3              | [e4faef5664](https://linux-hardware.org/?probe=e4faef5664) | Oct 17, 2020 |
| Lenovo        | ThinkPad A485 20MU000DMX    | [2e95605d0b](https://linux-hardware.org/?probe=2e95605d0b) | Oct 16, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [6bccbe114e](https://linux-hardware.org/?probe=6bccbe114e) | Oct 15, 2020 |
| Dell          | Latitude 3350               | [4cd708305e](https://linux-hardware.org/?probe=4cd708305e) | Oct 15, 2020 |
| Apple         | MacBookPro9,2               | [b2ee43c521](https://linux-hardware.org/?probe=b2ee43c521) | Oct 15, 2020 |
| Dell          | Vostro 5471                 | [22d3ea53f1](https://linux-hardware.org/?probe=22d3ea53f1) | Oct 12, 2020 |
| Dell          | XPS 13 9360                 | [fd0d0c7def](https://linux-hardware.org/?probe=fd0d0c7def) | Oct 12, 2020 |
| HP            | EliteBook 840 G2            | [9cb88c457c](https://linux-hardware.org/?probe=9cb88c457c) | Oct 10, 2020 |
| Dell          | Latitude 7490               | [13b67348d0](https://linux-hardware.org/?probe=13b67348d0) | Oct 09, 2020 |
| Dell          | XPS 13 9360                 | [a748505992](https://linux-hardware.org/?probe=a748505992) | Oct 05, 2020 |
| Dell          | Latitude 3350               | [40f1d36776](https://linux-hardware.org/?probe=40f1d36776) | Oct 05, 2020 |
| Lenovo        | ThinkPad L440 20ASS2JL00    | [f94c3aa8fd](https://linux-hardware.org/?probe=f94c3aa8fd) | Oct 05, 2020 |
| HP            | ZBook 15 G2                 | [10ee29e867](https://linux-hardware.org/?probe=10ee29e867) | Oct 04, 2020 |
| PC Special... | N150CU                      | [d6855993c3](https://linux-hardware.org/?probe=d6855993c3) | Oct 01, 2020 |
| Lenovo        | V130-15IKB 81HN             | [09abf1a088](https://linux-hardware.org/?probe=09abf1a088) | Sep 30, 2020 |
| Lenovo        | ThinkPad L460 20FU002UMX    | [c87dcf0aa1](https://linux-hardware.org/?probe=c87dcf0aa1) | Sep 29, 2020 |
| ASUSTek       | X751BP                      | [f361030dac](https://linux-hardware.org/?probe=f361030dac) | Sep 29, 2020 |
| ASUSTek       | X751BP                      | [0ff716d746](https://linux-hardware.org/?probe=0ff716d746) | Sep 29, 2020 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [add52d1094](https://linux-hardware.org/?probe=add52d1094) | Sep 29, 2020 |
| Lenovo        | ThinkPad P52 20M9001FRT     | [51c9d65b89](https://linux-hardware.org/?probe=51c9d65b89) | Sep 29, 2020 |
| Lenovo        | ThinkPad E495 20NE001TMX    | [fe24c7efc7](https://linux-hardware.org/?probe=fe24c7efc7) | Sep 28, 2020 |
| ASUSTek       | X556UB                      | [15790fbe92](https://linux-hardware.org/?probe=15790fbe92) | Sep 28, 2020 |
| Dell          | XPS 15 9570                 | [40fd0fa205](https://linux-hardware.org/?probe=40fd0fa205) | Sep 28, 2020 |
| Acer          | Aspire V3-571               | [0aa3ce7368](https://linux-hardware.org/?probe=0aa3ce7368) | Sep 27, 2020 |
| Lenovo        | ThinkPad T490s 20NX000EM... | [cc52f7719c](https://linux-hardware.org/?probe=cc52f7719c) | Sep 26, 2020 |
| Lenovo        | ThinkPad T490s 20NX000EM... | [48212a4f99](https://linux-hardware.org/?probe=48212a4f99) | Sep 26, 2020 |
| ASUSTek       | UL30VT                      | [0c2c2af0ce](https://linux-hardware.org/?probe=0c2c2af0ce) | Sep 26, 2020 |
| Lenovo        | ThinkPad X230 23252EG       | [31e0cd8ca1](https://linux-hardware.org/?probe=31e0cd8ca1) | Sep 24, 2020 |
| HP            | ZBook Studio G5             | [65ffa6972f](https://linux-hardware.org/?probe=65ffa6972f) | Sep 23, 2020 |
| Dell          | Inspiron 5520               | [d0303f5b83](https://linux-hardware.org/?probe=d0303f5b83) | Sep 23, 2020 |
| HP            | Compaq 6710b (KE121ET#AK... | [7adc66498b](https://linux-hardware.org/?probe=7adc66498b) | Sep 22, 2020 |
| Dell          | Latitude 3350               | [7ac791fc18](https://linux-hardware.org/?probe=7ac791fc18) | Sep 20, 2020 |
| ASUSTek       | UL30VT                      | [48f8840b61](https://linux-hardware.org/?probe=48f8840b61) | Sep 19, 2020 |
| Lenovo        | ThinkPad L430 24681R3       | [a96ad52bc9](https://linux-hardware.org/?probe=a96ad52bc9) | Sep 16, 2020 |
| Lenovo        | ThinkPad T440s 20AR003RM... | [1726e5904b](https://linux-hardware.org/?probe=1726e5904b) | Sep 13, 2020 |
| HP            | ProBook 470 G1              | [8369e41ac6](https://linux-hardware.org/?probe=8369e41ac6) | Sep 09, 2020 |
| Toshiba       | Satellite C670D-11P         | [951c1d520e](https://linux-hardware.org/?probe=951c1d520e) | Sep 06, 2020 |
| Toshiba       | Satellite C670D-11P         | [232e086547](https://linux-hardware.org/?probe=232e086547) | Sep 06, 2020 |
| ASUSTek       | G751JY                      | [773aaa38ba](https://linux-hardware.org/?probe=773aaa38ba) | Sep 03, 2020 |
| ASUSTek       | TUF Gaming FA506IV_FX506... | [6265987b7d](https://linux-hardware.org/?probe=6265987b7d) | Sep 02, 2020 |
| Dell          | Precision 5530              | [59be93b9f3](https://linux-hardware.org/?probe=59be93b9f3) | Sep 02, 2020 |
| Dell          | XPS 15 9500                 | [8dae51e89a](https://linux-hardware.org/?probe=8dae51e89a) | Sep 02, 2020 |
| Lenovo        | Z50-70 20354                | [04a50d1273](https://linux-hardware.org/?probe=04a50d1273) | Sep 01, 2020 |
| Dell          | XPS 13 9360                 | [9c688c8ec3](https://linux-hardware.org/?probe=9c688c8ec3) | Sep 01, 2020 |
| Dell          | XPS 13 9360                 | [c43e8e5452](https://linux-hardware.org/?probe=c43e8e5452) | Sep 01, 2020 |
| Dell          | XPS 15 9500                 | [867b9c76b4](https://linux-hardware.org/?probe=867b9c76b4) | Aug 31, 2020 |
| HP            | ProBook 4540s               | [615e7d9dfa](https://linux-hardware.org/?probe=615e7d9dfa) | Aug 29, 2020 |
| Google        | Reks                        | [9642234bc1](https://linux-hardware.org/?probe=9642234bc1) | Aug 27, 2020 |
| Sony          | VPCCW1S1E                   | [a21990e7e3](https://linux-hardware.org/?probe=a21990e7e3) | Aug 26, 2020 |
| Sony          | SVF13N2J4RS                 | [3ce53aa5ba](https://linux-hardware.org/?probe=3ce53aa5ba) | Aug 26, 2020 |
| HP            | EliteBook Folio 1040 G2     | [b0c7b9a8df](https://linux-hardware.org/?probe=b0c7b9a8df) | Aug 24, 2020 |
| Dell          | XPS 15 9570                 | [b2636a7543](https://linux-hardware.org/?probe=b2636a7543) | Aug 24, 2020 |
| HP            | Laptop 14s-dq1xxx           | [e7450d32f7](https://linux-hardware.org/?probe=e7450d32f7) | Aug 24, 2020 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | [7c299b5384](https://linux-hardware.org/?probe=7c299b5384) | Aug 23, 2020 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | [19586f3d92](https://linux-hardware.org/?probe=19586f3d92) | Aug 23, 2020 |
| HP            | ProBook 4540s               | [d802ce490d](https://linux-hardware.org/?probe=d802ce490d) | Aug 23, 2020 |
| Dell          | Latitude E6410              | [fd9e17ee51](https://linux-hardware.org/?probe=fd9e17ee51) | Aug 22, 2020 |
| Dell          | Latitude 5480               | [a3d3c7d13d](https://linux-hardware.org/?probe=a3d3c7d13d) | Aug 19, 2020 |
| HP            | EliteBook 840 G6            | [8f768222bd](https://linux-hardware.org/?probe=8f768222bd) | Aug 19, 2020 |
| Lenovo        | ThinkPad W530 24478K0       | [74fda860f1](https://linux-hardware.org/?probe=74fda860f1) | Aug 17, 2020 |
| Acer          | Aspire V3-772G              | [43cad6ef61](https://linux-hardware.org/?probe=43cad6ef61) | Aug 16, 2020 |
| MSI           | PS63 Modern 8SC             | [6a5ce95a82](https://linux-hardware.org/?probe=6a5ce95a82) | Aug 16, 2020 |
| Dell          | Latitude E6230              | [413296aea0](https://linux-hardware.org/?probe=413296aea0) | Aug 15, 2020 |
| Sony          | SVE1713C5E                  | [d5548d16b9](https://linux-hardware.org/?probe=d5548d16b9) | Aug 11, 2020 |
| YJKC          | vBOOK Plus RVP7             | [9d61e799e9](https://linux-hardware.org/?probe=9d61e799e9) | Aug 11, 2020 |
| Packard Be... | EasyNote TE69KB             | [5a431ae254](https://linux-hardware.org/?probe=5a431ae254) | Aug 08, 2020 |
| Lenovo        | ThinkPad X230 23252EG       | [df9004d133](https://linux-hardware.org/?probe=df9004d133) | Aug 07, 2020 |
| HP            | ProBook 4540s               | [ba871fc63f](https://linux-hardware.org/?probe=ba871fc63f) | Aug 06, 2020 |
| Dell          | Vostro 15-3568              | [a8ae8e7d68](https://linux-hardware.org/?probe=a8ae8e7d68) | Aug 05, 2020 |
| HP            | EliteBook 820 G3            | [9cc6147a4b](https://linux-hardware.org/?probe=9cc6147a4b) | Aug 03, 2020 |
| HP            | Notebook                    | [daf982706c](https://linux-hardware.org/?probe=daf982706c) | Aug 02, 2020 |
| HP            | Notebook                    | [1b3e005f48](https://linux-hardware.org/?probe=1b3e005f48) | Aug 02, 2020 |
| Sony          | VPCCA2S1E                   | [23d271e5f9](https://linux-hardware.org/?probe=23d271e5f9) | Aug 01, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [866268f4a1](https://linux-hardware.org/?probe=866268f4a1) | Jul 30, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [7495dfc0db](https://linux-hardware.org/?probe=7495dfc0db) | Jul 28, 2020 |
| Dell          | XPS 15 9560                 | [897c79afd9](https://linux-hardware.org/?probe=897c79afd9) | Jul 28, 2020 |
| HP            | ProBook 440 G4              | [2c9f3809f5](https://linux-hardware.org/?probe=2c9f3809f5) | Jul 25, 2020 |
| Dell          | Latitude 7390               | [66315a7d03](https://linux-hardware.org/?probe=66315a7d03) | Jul 24, 2020 |
| Dell          | Latitude 7400               | [1d53623b83](https://linux-hardware.org/?probe=1d53623b83) | Jul 23, 2020 |
| Lenovo        | G50-80 80E5                 | [4c71d19b3c](https://linux-hardware.org/?probe=4c71d19b3c) | Jul 23, 2020 |
| Toshiba       | Satellite Pro A300          | [f6f47ddd48](https://linux-hardware.org/?probe=f6f47ddd48) | Jul 22, 2020 |
| Dell          | Vostro 15-3568              | [52281c5c2d](https://linux-hardware.org/?probe=52281c5c2d) | Jul 22, 2020 |
| Lenovo        | ThinkPad T420 4236H45       | [61fd4ce395](https://linux-hardware.org/?probe=61fd4ce395) | Jul 20, 2020 |
| ASUSTek       | N550JK                      | [46cb4a6a21](https://linux-hardware.org/?probe=46cb4a6a21) | Jul 19, 2020 |
| Notebook      | N13xWU                      | [b454f8be8b](https://linux-hardware.org/?probe=b454f8be8b) | Jul 19, 2020 |
| Lenovo        | ThinkPad Edge 13IAL# 019... | [f1e0ca231d](https://linux-hardware.org/?probe=f1e0ca231d) | Jul 17, 2020 |
| Packard Be... | DOTS E2                     | [7c39181469](https://linux-hardware.org/?probe=7c39181469) | Jul 16, 2020 |
| Packard Be... | DOTS E2                     | [6ccd387cca](https://linux-hardware.org/?probe=6ccd387cca) | Jul 16, 2020 |
| Toshiba       | Satellite Pro A300          | [161d2f4301](https://linux-hardware.org/?probe=161d2f4301) | Jul 13, 2020 |
| Sony          | VPCYA1V9E                   | [a18b5b10da](https://linux-hardware.org/?probe=a18b5b10da) | Jul 13, 2020 |
| ASUSTek       | G551JM                      | [49c799973a](https://linux-hardware.org/?probe=49c799973a) | Jul 11, 2020 |
| HP            | ProBook 430 G1              | [695797d759](https://linux-hardware.org/?probe=695797d759) | Jul 11, 2020 |
| Lenovo        | IdeaPad S145-14API 81UV     | [04341d8ec3](https://linux-hardware.org/?probe=04341d8ec3) | Jul 11, 2020 |
| GOCLEVER      | INSIGNIA 1010 Business      | [16e0fc6692](https://linux-hardware.org/?probe=16e0fc6692) | Jul 10, 2020 |
| ASUSTek       | N550JV                      | [ef73738889](https://linux-hardware.org/?probe=ef73738889) | Jul 10, 2020 |
| ASUSTek       | N550JV                      | [037229866f](https://linux-hardware.org/?probe=037229866f) | Jul 10, 2020 |
| Notebook      | N2x0WU                      | [3d377a9ec3](https://linux-hardware.org/?probe=3d377a9ec3) | Jul 09, 2020 |
| PC Special... | N150CU                      | [98055ea3a5](https://linux-hardware.org/?probe=98055ea3a5) | Jul 06, 2020 |
| PC Special... | N150CU                      | [940e89b2ae](https://linux-hardware.org/?probe=940e89b2ae) | Jul 05, 2020 |
| PC Special... | N150CU                      | [6f7e0f4a22](https://linux-hardware.org/?probe=6f7e0f4a22) | Jul 04, 2020 |
| Lenovo        | ThinkPad P52 20M9001FRT     | [6deb3ed800](https://linux-hardware.org/?probe=6deb3ed800) | Jul 04, 2020 |
| PC Special... | N150CU                      | [e000363c3f](https://linux-hardware.org/?probe=e000363c3f) | Jul 03, 2020 |
| Lenovo        | ThinkPad P52 20M9001FRT     | [7ad372e11f](https://linux-hardware.org/?probe=7ad372e11f) | Jul 03, 2020 |
| ASUSTek       | K53SD                       | [0d83d52317](https://linux-hardware.org/?probe=0d83d52317) | Jul 01, 2020 |
| Dell          | Latitude 7490               | [4a6f72df25](https://linux-hardware.org/?probe=4a6f72df25) | Jun 30, 2020 |
| Lenovo        | ThinkPad P52 20M9001FRT     | [6ec07a9cad](https://linux-hardware.org/?probe=6ec07a9cad) | Jun 29, 2020 |
| HP            | EliteBook 840 G2            | [ba88603322](https://linux-hardware.org/?probe=ba88603322) | Jun 24, 2020 |
| Dell          | Latitude E6430              | [cc1fa32507](https://linux-hardware.org/?probe=cc1fa32507) | Jun 24, 2020 |
| ASUSTek       | UX430UQ                     | [9c5906b7df](https://linux-hardware.org/?probe=9c5906b7df) | Jun 23, 2020 |
| Sony          | VPCCA2S1E                   | [a26823176d](https://linux-hardware.org/?probe=a26823176d) | Jun 22, 2020 |
| PC Special... | N150CU                      | [82eaf1bef8](https://linux-hardware.org/?probe=82eaf1bef8) | Jun 21, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Sweden/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 138       | 14.79%  |
| Ubuntu 18.04                 | 74        | 7.93%   |
| Ubuntu 22.04                 | 44        | 4.72%   |
| Debian 11                    | 26        | 2.79%   |
| Pop!_OS 21.04                | 22        | 2.36%   |
| OpenMandriva 4.2             | 21        | 2.25%   |
| Arch                         | 21        | 2.25%   |
| Ubuntu 19.04                 | 19        | 2.04%   |
| OpenMandriva 4.3             | 19        | 2.04%   |
| Fedora 35                    | 18        | 1.93%   |
| Manjaro                      | 17        | 1.82%   |
| Zorin 16                     | 16        | 1.71%   |
| Ubuntu 21.10                 | 16        | 1.71%   |
| Pop!_OS 20.10                | 16        | 1.71%   |
| Pop!_OS 20.04                | 16        | 1.71%   |
| Zorin 15                     | 15        | 1.61%   |
| KDE neon 20.04               | 15        | 1.61%   |
| Arch Rolling                 | 15        | 1.61%   |
| Pop!_OS 22.04                | 14        | 1.5%    |
| Linux Mint 20.2              | 14        | 1.5%    |
| Ubuntu 19.10                 | 13        | 1.39%   |
| Linux Mint 20.3              | 12        | 1.29%   |
| Linux Mint 20.1              | 12        | 1.29%   |
| Fedora 34                    | 12        | 1.29%   |
| Ubuntu 21.04                 | 11        | 1.18%   |
| openSUSE Tumbleweed-XXXXXXXX | 11        | 1.18%   |
| Ubuntu 20.10                 | 10        | 1.07%   |
| Fedora 36                    | 10        | 1.07%   |
| Pop!_OS 21.10                | 9         | 0.96%   |
| Fedora 33                    | 9         | 0.96%   |
| ArcoLinux Rolling            | 9         | 0.96%   |
| Linux Mint 20                | 8         | 0.86%   |
| Linux Mint 19.3              | 8         | 0.86%   |
| Xubuntu 20.04                | 7         | 0.75%   |
| Ubuntu 18.10                 | 7         | 0.75%   |
| Fedora 32                    | 7         | 0.75%   |
| Gentoo 2.6                   | 6         | 0.64%   |
| Fedora 31                    | 6         | 0.64%   |
| Debian Testing               | 6         | 0.64%   |
| Linux Mint 21                | 5         | 0.54%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 320       | 35.83%  |
| Pop!_OS       | 74        | 8.29%   |
| Fedora        | 70        | 7.84%   |
| Linux Mint    | 67        | 7.5%    |
| OpenMandriva  | 45        | 5.04%   |
| Debian        | 37        | 4.14%   |
| Manjaro       | 35        | 3.92%   |
| Arch          | 35        | 3.92%   |
| Zorin         | 31        | 3.47%   |
| KDE neon      | 21        | 2.35%   |
| Xubuntu       | 17        | 1.9%    |
| ArcoLinux     | 12        | 1.34%   |
| openSUSE      | 11        | 1.23%   |
| Gentoo        | 11        | 1.23%   |
| Kubuntu       | 9         | 1.01%   |
| Endless       | 8         | 0.9%    |
| ROSA          | 7         | 0.78%   |
| Kali          | 7         | 0.78%   |
| EndeavourOS   | 6         | 0.67%   |
| CentOS        | 6         | 0.67%   |
| Ubuntu MATE   | 5         | 0.56%   |
| Elementary    | 5         | 0.56%   |
| SteamOS       | 4         | 0.45%   |
| Peppermint    | 4         | 0.45%   |
| Parrot        | 4         | 0.45%   |
| BlackPanther  | 4         | 0.45%   |
| Ubuntu Unity  | 3         | 0.34%   |
| Ubuntu Budgie | 3         | 0.34%   |
| Lubuntu       | 3         | 0.34%   |
| Slackware     | 2         | 0.22%   |
| LMDE          | 2         | 0.22%   |
| Garuda Linux  | 2         | 0.22%   |
| Clear Linux   | 2         | 0.22%   |
| Chrome OS     | 2         | 0.22%   |
| BunsenLabs    | 2         | 0.22%   |
| Xero          | 1         | 0.11%   |
| Solus         | 1         | 0.11%   |
| Siduction     | 1         | 0.11%   |
| Rocky Linux   | 1         | 0.11%   |
| Reborn OS     | 1         | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 21        | 2.07%   |
| 5.4.0-42-generic         | 18        | 1.78%   |
| 5.16.7-desktop-1omv4003  | 18        | 1.78%   |
| 5.15.0-56-generic        | 18        | 1.78%   |
| 5.4.0-58-generic         | 12        | 1.18%   |
| 5.4.0-48-generic         | 12        | 1.18%   |
| 5.15.0-52-generic        | 12        | 1.18%   |
| 5.3.0-40-generic         | 10        | 0.99%   |
| 5.13.0-30-generic        | 10        | 0.99%   |
| 5.4.0-52-generic         | 9         | 0.89%   |
| 5.4.0-40-generic         | 9         | 0.89%   |
| 5.11.0-37-generic        | 9         | 0.89%   |
| 5.8.0-48-generic         | 8         | 0.79%   |
| 5.15.0-48-generic        | 8         | 0.79%   |
| 5.13.0-7614-generic      | 8         | 0.79%   |
| 5.4.0-70-generic         | 7         | 0.69%   |
| 5.4.0-65-generic         | 7         | 0.69%   |
| 5.13.0-39-generic        | 7         | 0.69%   |
| 5.10.0-8-amd64           | 7         | 0.69%   |
| 4.15.0-47-generic        | 7         | 0.69%   |
| 5.8.0-7630-generic       | 6         | 0.59%   |
| 5.4.0-7634-generic       | 6         | 0.59%   |
| 5.4.0-66-generic         | 6         | 0.59%   |
| 5.4.0-54-generic         | 6         | 0.59%   |
| 5.4.0-33-generic         | 6         | 0.59%   |
| 5.3.0-51-generic         | 6         | 0.59%   |
| 5.3.0-28-generic         | 6         | 0.59%   |
| 5.15.0-50-generic        | 6         | 0.59%   |
| 5.11.0-41-generic        | 6         | 0.59%   |
| 5.4.0-56-generic         | 5         | 0.49%   |
| 5.4.0-37-generic         | 5         | 0.49%   |
| 5.4.0-29-generic         | 5         | 0.49%   |
| 5.15.0-46-generic        | 5         | 0.49%   |
| 5.11.0-7620-generic      | 5         | 0.49%   |
| 5.11.0-7614-generic      | 5         | 0.49%   |
| 5.11.0-40-generic        | 5         | 0.49%   |
| 5.11.0-38-generic        | 5         | 0.49%   |
| 5.11.0-27-generic        | 5         | 0.49%   |
| 5.0.0-25-generic         | 5         | 0.49%   |
| 5.8.0-7642-generic       | 4         | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 173       | 18.17%  |
| 5.15.0  | 71        | 7.46%   |
| 5.11.0  | 66        | 6.93%   |
| 5.13.0  | 60        | 6.3%    |
| 5.8.0   | 50        | 5.25%   |
| 5.3.0   | 46        | 4.83%   |
| 4.15.0  | 45        | 4.73%   |
| 5.10.0  | 35        | 3.68%   |
| 5.0.0   | 34        | 3.57%   |
| 4.18.0  | 23        | 2.42%   |
| 5.10.14 | 21        | 2.21%   |
| 5.16.7  | 19        | 2%      |
| 5.14.0  | 7         | 0.74%   |
| 5.17.5  | 6         | 0.63%   |
| 5.16.0  | 6         | 0.63%   |
| 5.7.0   | 5         | 0.53%   |
| 5.18.0  | 5         | 0.53%   |
| 6.0.8   | 4         | 0.42%   |
| 5.19.0  | 4         | 0.42%   |
| 5.17.1  | 4         | 0.42%   |
| 5.16.2  | 4         | 0.42%   |
| 5.16.15 | 4         | 0.42%   |
| 5.15.5  | 4         | 0.42%   |
| 5.15.15 | 4         | 0.42%   |
| 4.18.16 | 4         | 0.42%   |
| 6.0.6   | 3         | 0.32%   |
| 5.9.14  | 3         | 0.32%   |
| 5.5.8   | 3         | 0.32%   |
| 5.18.14 | 3         | 0.32%   |
| 5.18.10 | 3         | 0.32%   |
| 5.16.18 | 3         | 0.32%   |
| 5.15.8  | 3         | 0.32%   |
| 5.15.7  | 3         | 0.32%   |
| 5.15.11 | 3         | 0.32%   |
| 5.14.11 | 3         | 0.32%   |
| 5.12.4  | 3         | 0.32%   |
| 5.11.11 | 3         | 0.32%   |
| 4.19.0  | 3         | 0.32%   |
| 6.1.0   | 2         | 0.21%   |
| 5.9.8   | 2         | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 179       | 19.08%  |
| 5.15    | 102       | 10.87%  |
| 5.11    | 78        | 8.32%   |
| 5.10    | 72        | 7.68%   |
| 5.13    | 70        | 7.46%   |
| 5.8     | 62        | 6.61%   |
| 5.3     | 52        | 5.54%   |
| 5.16    | 45        | 4.8%    |
| 4.15    | 45        | 4.8%    |
| 5.0     | 36        | 3.84%   |
| 4.18    | 29        | 3.09%   |
| 5.18    | 20        | 2.13%   |
| 5.17    | 18        | 1.92%   |
| 5.14    | 17        | 1.81%   |
| 6.0     | 14        | 1.49%   |
| 5.9     | 14        | 1.49%   |
| 5.12    | 14        | 1.49%   |
| 5.7     | 11        | 1.17%   |
| 5.6     | 11        | 1.17%   |
| 5.19    | 11        | 1.17%   |
| 4.19    | 8         | 0.85%   |
| 5.5     | 7         | 0.75%   |
| 5.2     | 6         | 0.64%   |
| 4.9     | 5         | 0.53%   |
| 5.1     | 4         | 0.43%   |
| 6.1     | 3         | 0.32%   |
| 4.1     | 2         | 0.21%   |
| 4.20    | 1         | 0.11%   |
| 4.14    | 1         | 0.11%   |
| 3.10    | 1         | 0.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 840       | 98.36%  |
| i686   | 14        | 1.64%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 443       | 49.5%   |
| Unknown         | 126       | 14.08%  |
| KDE5            | 104       | 11.62%  |
| XFCE            | 61        | 6.82%   |
| X-Cinnamon      | 53        | 5.92%   |
| KDE             | 29        | 3.24%   |
| MATE            | 21        | 2.35%   |
| Cinnamon        | 9         | 1.01%   |
| i3              | 8         | 0.89%   |
| LXQt            | 6         | 0.67%   |
| Pantheon        | 5         | 0.56%   |
| LXDE            | 5         | 0.56%   |
| Unity           | 3         | 0.34%   |
| sway            | 3         | 0.34%   |
| KDE4            | 3         | 0.34%   |
| Budgie          | 3         | 0.34%   |
| qtile           | 2         | 0.22%   |
| DWM             | 2         | 0.22%   |
| Deepin          | 2         | 0.22%   |
| awesome         | 2         | 0.22%   |
| Trinity         | 1         | 0.11%   |
| spectrwm        | 1         | 0.11%   |
| LeftWM          | 1         | 0.11%   |
| GNOME Flashback | 1         | 0.11%   |
| bspwm           | 1         | 0.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 657       | 74.57%  |
| Wayland | 138       | 15.66%  |
| Unknown | 72        | 8.17%   |
| Tty     | 14        | 1.59%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 490       | 54.99%  |
| GDM     | 119       | 13.36%  |
| SDDM    | 100       | 11.22%  |
| GDM3    | 84        | 9.43%   |
| LightDM | 63        | 7.07%   |
| TDM     | 28        | 3.14%   |
| XDM     | 3         | 0.34%   |
| KDM     | 3         | 0.34%   |
| Ly      | 1         | 0.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| en_US      | 430       | 48.81%  |
| sv_SE      | 228       | 25.88%  |
| Unknown    | 119       | 13.51%  |
| en_GB      | 47        | 5.33%   |
| C          | 9         | 1.02%   |
| de_DE      | 8         | 0.91%   |
| ru_RU      | 7         | 0.79%   |
| pl_PL      | 5         | 0.57%   |
| en_SE      | 5         | 0.57%   |
| fr_FR      | 3         | 0.34%   |
| lt_LT      | 2         | 0.23%   |
| en_DK      | 2         | 0.23%   |
| en_CA      | 2         | 0.23%   |
| uk_UA      | 1         | 0.11%   |
| sv_SE.UTF8 | 1         | 0.11%   |
| sv_FI      | 1         | 0.11%   |
| POSIX      | 1         | 0.11%   |
| nn_NO      | 1         | 0.11%   |
| nb_NO      | 1         | 0.11%   |
| hu_HU      | 1         | 0.11%   |
| fi_FI      | 1         | 0.11%   |
| es_ES      | 1         | 0.11%   |
| en_IE      | 1         | 0.11%   |
| en_AU      | 1         | 0.11%   |
| en_AG      | 1         | 0.11%   |
| C.UTF8     | 1         | 0.11%   |
| bg_BG      | 1         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 456       | 51.94%  |
| BIOS | 422       | 48.06%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 678       | 77.4%   |
| Btrfs   | 79        | 9.02%   |
| Overlay | 56        | 6.39%   |
| Unknown | 31        | 3.54%   |
| Xfs     | 12        | 1.37%   |
| Zfs     | 11        | 1.26%   |
| Ext2    | 6         | 0.68%   |
| F2fs    | 2         | 0.23%   |
| XXXXXXX | 1         | 0.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 509       | 58.3%   |
| GPT     | 293       | 33.56%  |
| MBR     | 71        | 8.13%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 786       | 90.76%  |
| Yes       | 80        | 9.24%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 696       | 80.65%  |
| Yes       | 167       | 19.35%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo               | 198       | 23.19%  |
| Hewlett-Packard      | 181       | 21.19%  |
| Dell                 | 137       | 16.04%  |
| ASUSTek Computer     | 112       | 13.11%  |
| Acer                 | 58        | 6.79%   |
| Apple                | 35        | 4.1%    |
| MSI                  | 18        | 2.11%   |
| Sony                 | 15        | 1.76%   |
| Toshiba              | 14        | 1.64%   |
| Samsung Electronics  | 9         | 1.05%   |
| Packard Bell         | 9         | 1.05%   |
| Notebook             | 7         | 0.82%   |
| Google               | 7         | 0.82%   |
| Fujitsu              | 6         | 0.7%    |
| Unknown              | 5         | 0.59%   |
| Valve                | 4         | 0.47%   |
| HUAWEI               | 4         | 0.47%   |
| TUXEDO               | 3         | 0.35%   |
| Fujitsu Siemens      | 3         | 0.35%   |
| Star Labs            | 2         | 0.23%   |
| Razer                | 2         | 0.23%   |
| PC Specialist        | 2         | 0.23%   |
| eMachines            | 2         | 0.23%   |
| Alienware            | 2         | 0.23%   |
| ZEPTO                | 1         | 0.12%   |
| YJKC                 | 1         | 0.12%   |
| Timi                 | 1         | 0.12%   |
| System76             | 1         | 0.12%   |
| SLIMBOOK             | 1         | 0.12%   |
| Schenker             | 1         | 0.12%   |
| Purism               | 1         | 0.12%   |
| On by NetOnNet       | 1         | 0.12%   |
| LG Electronics       | 1         | 0.12%   |
| Intel Client Systems | 1         | 0.12%   |
| Intel                | 1         | 0.12%   |
| Insyde               | 1         | 0.12%   |
| GOCLEVER             | 1         | 0.12%   |
| Gigabyte Technology  | 1         | 0.12%   |
| GIADA                | 1         | 0.12%   |
| EUROCOM              | 1         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 7         | 0.82%   |
| Dell Precision 5540                        | 6         | 0.7%    |
| HP Pavilion dv7                            | 5         | 0.59%   |
| HP Pavilion 15                             | 5         | 0.59%   |
| HP EliteBook Folio 9470m                   | 5         | 0.59%   |
| HP EliteBook 840 G2                        | 5         | 0.59%   |
| Dell XPS 13 9310                           | 5         | 0.59%   |
| Apple MacBookPro11,3                       | 5         | 0.59%   |
| Acer Aspire V3-571                         | 5         | 0.59%   |
| Valve Jupiter                              | 4         | 0.47%   |
| HP EliteBook 830 G6                        | 4         | 0.47%   |
| Dell XPS 15 9570                           | 4         | 0.47%   |
| Dell XPS 15 9500                           | 4         | 0.47%   |
| Dell XPS 13 9370                           | 4         | 0.47%   |
| Apple MacBookAir7,2                        | 4         | 0.47%   |
| Lenovo Z50-70 20354                        | 3         | 0.35%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW005NMX | 3         | 0.35%   |
| HUAWEI KLVL-WXX9                           | 3         | 0.35%   |
| HP ZBook 15 G2                             | 3         | 0.35%   |
| HP ProBook 640 G1                          | 3         | 0.35%   |
| HP ProBook 430 G1                          | 3         | 0.35%   |
| HP Pavilion Notebook                       | 3         | 0.35%   |
| HP Pavilion dv6                            | 3         | 0.35%   |
| HP Pavilion 17                             | 3         | 0.35%   |
| HP Laptop 15-db0xxx                        | 3         | 0.35%   |
| HP ENVY 15                                 | 3         | 0.35%   |
| HP EliteBook 8440p                         | 3         | 0.35%   |
| HP EliteBook 840 G6                        | 3         | 0.35%   |
| HP EliteBook 840 G3                        | 3         | 0.35%   |
| HP EliteBook 840 G1                        | 3         | 0.35%   |
| Dell XPS 15 9560                           | 3         | 0.35%   |
| Dell XPS 15 7590                           | 3         | 0.35%   |
| Dell Precision M4700                       | 3         | 0.35%   |
| Dell Latitude E7440                        | 3         | 0.35%   |
| Dell Latitude E7240                        | 3         | 0.35%   |
| Dell Latitude E6430                        | 3         | 0.35%   |
| Dell Latitude 5480                         | 3         | 0.35%   |
| ASUS VivoBook_ASUSLaptop X512DAP_X512DA    | 3         | 0.35%   |
| Apple MacBookPro9,2                        | 3         | 0.35%   |
| Apple MacBookPro8,1                        | 3         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 126       | 14.75%  |
| HP EliteBook          | 67        | 7.85%   |
| Dell Latitude         | 52        | 6.09%   |
| Acer Aspire           | 40        | 4.68%   |
| Dell XPS              | 36        | 4.22%   |
| Dell Precision        | 35        | 4.1%    |
| HP Pavilion           | 31        | 3.63%   |
| Lenovo IdeaPad        | 28        | 3.28%   |
| HP ProBook            | 27        | 3.16%   |
| ASUS VivoBook         | 16        | 1.87%   |
| HP ZBook              | 15        | 1.76%   |
| Toshiba Satellite     | 12        | 1.41%   |
| HP Laptop             | 12        | 1.41%   |
| HP Compaq             | 12        | 1.41%   |
| ASUS ROG              | 10        | 1.17%   |
| ASUS ZenBook          | 9         | 1.05%   |
| Packard Bell EasyNote | 8         | 0.94%   |
| Lenovo Legion         | 8         | 0.94%   |
| Dell Inspiron         | 8         | 0.94%   |
| Lenovo Yoga           | 7         | 0.82%   |
| Acer Swift            | 7         | 0.82%   |
| Unknown               | 7         | 0.82%   |
| HP ENVY               | 6         | 0.7%    |
| Dell Vostro           | 6         | 0.7%    |
| Apple MacBookPro11    | 6         | 0.7%    |
| Fujitsu LIFEBOOK      | 5         | 0.59%   |
| Valve Jupiter         | 4         | 0.47%   |
| ASUS TUF              | 4         | 0.47%   |
| Apple MacBookAir7     | 4         | 0.47%   |
| Acer Predator         | 4         | 0.47%   |
| Acer Nitro            | 4         | 0.47%   |
| MSI GF63              | 3         | 0.35%   |
| Lenovo Z50-70         | 3         | 0.35%   |
| HUAWEI KLVL-WXX9      | 3         | 0.35%   |
| ASUS ASUS             | 3         | 0.35%   |
| Apple MacBookPro9     | 3         | 0.35%   |
| Apple MacBookPro8     | 3         | 0.35%   |
| Apple MacBookPro14    | 3         | 0.35%   |
| Apple MacBookPro10    | 3         | 0.35%   |
| Apple MacBookAir6     | 3         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 84        | 9.84%   |
| 2013 | 78        | 9.13%   |
| 2018 | 76        | 8.9%    |
| 2021 | 74        | 8.67%   |
| 2011 | 62        | 7.26%   |
| 2020 | 60        | 7.03%   |
| 2015 | 59        | 6.91%   |
| 2017 | 58        | 6.79%   |
| 2012 | 58        | 6.79%   |
| 2014 | 57        | 6.67%   |
| 2016 | 51        | 5.97%   |
| 2010 | 48        | 5.62%   |
| 2008 | 25        | 2.93%   |
| 2007 | 19        | 2.22%   |
| 2009 | 17        | 1.99%   |
| 2022 | 16        | 1.87%   |
| 2006 | 7         | 0.82%   |
| 2005 | 5         | 0.59%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 854       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 745       | 86.43%  |
| Enabled  | 117       | 13.57%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 845       | 98.95%  |
| Yes  | 9         | 1.05%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 240       | 27.84%  |
| 16.01-24.0  | 170       | 19.72%  |
| 3.01-4.0    | 153       | 17.75%  |
| 8.01-16.0   | 149       | 17.29%  |
| 32.01-64.0  | 94        | 10.9%   |
| 1.01-2.0    | 29        | 3.36%   |
| 24.01-32.0  | 9         | 1.04%   |
| 2.01-3.0    | 7         | 0.81%   |
| 64.01-256.0 | 6         | 0.7%    |
| 0.51-1.0    | 5         | 0.58%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 332       | 35.32%  |
| 2.01-3.0   | 239       | 25.43%  |
| 4.01-8.0   | 148       | 15.74%  |
| 3.01-4.0   | 126       | 13.4%   |
| 0.51-1.0   | 46        | 4.89%   |
| 8.01-16.0  | 31        | 3.3%    |
| 0.01-0.5   | 11        | 1.17%   |
| 16.01-24.0 | 7         | 0.74%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 692       | 79.63%  |
| 2      | 154       | 17.72%  |
| 3      | 15        | 1.73%   |
| 4      | 4         | 0.46%   |
| 0      | 4         | 0.46%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 597       | 69.58%  |
| Yes       | 261       | 30.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 696       | 81.12%  |
| No        | 162       | 18.88%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 845       | 98.95%  |
| No        | 9         | 1.05%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 700       | 81.11%  |
| No        | 163       | 18.89%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Sweden  | 854       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Stockholm         | 167       | 18.03%  |
| Gothenburg        | 90        | 9.72%   |
| Malmo             | 39        | 4.21%   |
| Uppsala           | 26        | 2.81%   |
| Linköping        | 17        | 1.84%   |
| Lund              | 15        | 1.62%   |
| Bromma            | 13        | 1.4%    |
| Örebro           | 11        | 1.19%   |
| Norrköping       | 11        | 1.19%   |
| Huddinge          | 11        | 1.19%   |
| Vaestra Froelunda | 10        | 1.08%   |
| Solna             | 10        | 1.08%   |
| Bandhagen         | 10        | 1.08%   |
| Vaxjo             | 9         | 0.97%   |
| Sollentuna        | 9         | 0.97%   |
| Haegersten        | 9         | 0.97%   |
| Västerås        | 8         | 0.86%   |
| Södertälje      | 8         | 0.86%   |
| Kista             | 8         | 0.86%   |
| Karlskrona        | 8         | 0.86%   |
| Umeå             | 7         | 0.76%   |
| Staffanstorp      | 7         | 0.76%   |
| Mjoelby           | 7         | 0.76%   |
| Landskrona        | 7         | 0.76%   |
| Karlstad          | 7         | 0.76%   |
| Helsingborg       | 7         | 0.76%   |
| Taby              | 6         | 0.65%   |
| Norsborg          | 6         | 0.65%   |
| Moelndal          | 6         | 0.65%   |
| Katrineholm       | 6         | 0.65%   |
| Handen            | 6         | 0.65%   |
| Halmstad          | 6         | 0.65%   |
| Alvsjo            | 6         | 0.65%   |
| Upplands Vasby    | 5         | 0.54%   |
| Sundbyberg        | 5         | 0.54%   |
| Spanga            | 5         | 0.54%   |
| Jönköping       | 5         | 0.54%   |
| Akersberga        | 5         | 0.54%   |
| Vendelso          | 4         | 0.43%   |
| Vaennaes          | 4         | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 209       | 273    | 20.51%  |
| WDC                            | 101       | 127    | 9.91%   |
| Toshiba                        | 80        | 101    | 7.85%   |
| Seagate                        | 76        | 88     | 7.46%   |
| SanDisk                        | 66        | 86     | 6.48%   |
| Kingston                       | 66        | 86     | 6.48%   |
| Intel                          | 66        | 73     | 6.48%   |
| Unknown                        | 52        | 67     | 5.1%    |
| SK hynix                       | 51        | 55     | 5%      |
| Micron Technology              | 37        | 43     | 3.63%   |
| Hitachi                        | 31        | 36     | 3.04%   |
| HGST                           | 25        | 30     | 2.45%   |
| Apple                          | 21        | 27     | 2.06%   |
| Crucial                        | 18        | 25     | 1.77%   |
| LITEON                         | 15        | 19     | 1.47%   |
| OCZ                            | 9         | 9      | 0.88%   |
| KIOXIA                         | 9         | 9      | 0.88%   |
| LITEONIT                       | 6         | 10     | 0.59%   |
| A-DATA Technology              | 6         | 6      | 0.59%   |
| Intenso                        | 5         | 5      | 0.49%   |
| Phison                         | 4         | 4      | 0.39%   |
| Kingston Technology Company    | 4         | 4      | 0.39%   |
| Union Memory                   | 3         | 3      | 0.29%   |
| Transcend                      | 3         | 3      | 0.29%   |
| Silicon Motion                 | 3         | 14     | 0.29%   |
| Phison Electronics             | 3         | 3      | 0.29%   |
| Lenovo                         | 3         | 3      | 0.29%   |
| Fujitsu                        | 3         | 4      | 0.29%   |
| China                          | 3         | 3      | 0.29%   |
| Unknown                        | 3         | 3      | 0.29%   |
| Solid State Storage Technology | 2         | 2      | 0.2%    |
| ROG                            | 2         | 2      | 0.2%    |
| PNY                            | 2         | 2      | 0.2%    |
| M4-CT128                       | 2         | 2      | 0.2%    |
| Lite-On                        | 2         | 2      | 0.2%    |
| JMicron Technology             | 2         | 2      | 0.2%    |
| Hewlett-Packard                | 2         | 2      | 0.2%    |
| GOODRAM                        | 2         | 2      | 0.2%    |
| Corsair                        | 2         | 2      | 0.2%    |
| ASMT                           | 2         | 2      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Toshiba NVMe SSD Drive 512GB                        | 12        | 1.14%   |
| SK hynix NVMe SSD Drive 512GB                       | 11        | 1.05%   |
| Samsung NVMe SSD Drive 512GB                        | 11        | 1.05%   |
| SanDisk NVMe SSD Drive 512GB                        | 10        | 0.95%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 9         | 0.86%   |
| Samsung NVMe SSD Drive 1024GB                       | 9         | 0.86%   |
| Unknown MMC Card  16GB                              | 8         | 0.76%   |
| HGST HTS721010A9E630 1TB                            | 8         | 0.76%   |
| Unknown MMC Card  64GB                              | 7         | 0.67%   |
| Unknown MMC Card  32GB                              | 7         | 0.67%   |
| Seagate ST9500325AS 500GB                           | 7         | 0.67%   |
| Samsung SSD 850 EVO 500GB                           | 7         | 0.67%   |
| Samsung SSD 850 EVO 250GB                           | 7         | 0.67%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD                 | 7         | 0.67%   |
| Kingston SA400S37480G 480GB SSD                     | 7         | 0.67%   |
| Kingston SA400S37120G 120GB SSD                     | 7         | 0.67%   |
| Intel NVMe SSD Drive 256GB                          | 7         | 0.67%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 6         | 0.57%   |
| Toshiba NVMe SSD Drive 256GB                        | 6         | 0.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 6         | 0.57%   |
| Samsung SSD 970 EVO Plus 1TB                        | 6         | 0.57%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 6         | 0.57%   |
| Kingston SUV400S37120G 120GB SSD                    | 6         | 0.57%   |
| SanDisk NVMe SSD Drive 256GB                        | 5         | 0.48%   |
| Micron NVMe SSD Drive 512GB                         | 5         | 0.48%   |
| Kingston SA400S37240G 240GB SSD                     | 5         | 0.48%   |
| Intel SSDPEKNW010T8 1TB                             | 5         | 0.48%   |
| HGST HTS545050A7E680 500GB                          | 5         | 0.48%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 4         | 0.38%   |
| Toshiba MQ04ABF100 1TB                              | 4         | 0.38%   |
| Toshiba MQ01ACF032 320GB                            | 4         | 0.38%   |
| Toshiba MQ01ABD100 1TB                              | 4         | 0.38%   |
| SK hynix PC711 NVMe 512GB                           | 4         | 0.38%   |
| Seagate ST9320423AS 320GB                           | 4         | 0.38%   |
| Seagate ST320LT007-9ZV142 320GB                     | 4         | 0.38%   |
| Seagate ST1000LM035-1RK172 1TB                      | 4         | 0.38%   |
| SanDisk NVMe SSD Drive 1TB                          | 4         | 0.38%   |
| SanDisk NVMe SSD Drive 1024GB                       | 4         | 0.38%   |
| Samsung SSD 840 EVO 250GB                           | 4         | 0.38%   |
| Samsung NVMe SSD Drive 500GB                        | 4         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 74        | 85     | 31.62%  |
| WDC                 | 57        | 73     | 24.36%  |
| Toshiba             | 35        | 42     | 14.96%  |
| Hitachi             | 31        | 36     | 13.25%  |
| HGST                | 25        | 30     | 10.68%  |
| Samsung Electronics | 4         | 4      | 1.71%   |
| Fujitsu             | 3         | 4      | 1.28%   |
| Unknown             | 2         | 2      | 0.85%   |
| Apple               | 2         | 2      | 0.85%   |
| ASMT                | 1         | 1      | 0.43%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 108       | 146    | 26.87%  |
| Kingston            | 52        | 69     | 12.94%  |
| SanDisk             | 41        | 51     | 10.2%   |
| Intel               | 40        | 43     | 9.95%   |
| Micron Technology   | 22        | 26     | 5.47%   |
| WDC                 | 17        | 22     | 4.23%   |
| Crucial             | 17        | 24     | 4.23%   |
| Apple               | 16        | 21     | 3.98%   |
| SK hynix            | 14        | 16     | 3.48%   |
| LITEON              | 14        | 18     | 3.48%   |
| Toshiba             | 11        | 18     | 2.74%   |
| OCZ                 | 9         | 9      | 2.24%   |
| LITEONIT            | 6         | 10     | 1.49%   |
| Intenso             | 4         | 4      | 1%      |
| Transcend           | 3         | 3      | 0.75%   |
| China               | 3         | 3      | 0.75%   |
| A-DATA Technology   | 3         | 3      | 0.75%   |
| PNY                 | 2         | 2      | 0.5%    |
| M4-CT128            | 2         | 2      | 0.5%    |
| Corsair             | 2         | 2      | 0.5%    |
| Unknown             | 1         | 1      | 0.25%   |
| TO Exter            | 1         | 1      | 0.25%   |
| Star                | 1         | 1      | 0.25%   |
| SSSTC               | 1         | 1      | 0.25%   |
| Seagate             | 1         | 1      | 0.25%   |
| Radeon              | 1         | 1      | 0.25%   |
| OCZ-VERTEX3         | 1         | 1      | 0.25%   |
| MyDigitalSSD        | 1         | 1      | 0.25%   |
| Maxtor              | 1         | 1      | 0.25%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.25%   |
| KingSpec            | 1         | 1      | 0.25%   |
| KingFast            | 1         | 1      | 0.25%   |
| JMicron Technology  | 1         | 1      | 0.25%   |
| GOODRAM             | 1         | 1      | 0.25%   |
| ASMT                | 1         | 1      | 0.25%   |
| Unknown             | 1         | 1      | 0.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 371       | 508    | 38.53%  |
| NVMe    | 305       | 399    | 31.67%  |
| HDD     | 228       | 279    | 23.68%  |
| MMC     | 50        | 64     | 5.19%   |
| Unknown | 9         | 8      | 0.93%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 550       | 770    | 59.08%  |
| NVMe | 304       | 396    | 32.65%  |
| MMC  | 50        | 64     | 5.37%   |
| SAS  | 27        | 28     | 2.9%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 461       | 625    | 77.74%  |
| 0.51-1.0   | 122       | 150    | 20.57%  |
| 1.01-2.0   | 7         | 8      | 1.18%   |
| 3.01-4.0   | 2         | 3      | 0.34%   |
| 4.01-10.0  | 1         | 1      | 0.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 297       | 33%     |
| 251-500        | 234       | 26%     |
| 501-1000       | 116       | 12.89%  |
| 1-20           | 73        | 8.11%   |
| 1001-2000      | 48        | 5.33%   |
| 51-100         | 48        | 5.33%   |
| Unknown        | 36        | 4%      |
| 21-50          | 31        | 3.44%   |
| More than 3000 | 9         | 1%      |
| 2001-3000      | 8         | 0.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 405       | 43.55%  |
| 21-50          | 149       | 16.02%  |
| 101-250        | 136       | 14.62%  |
| 51-100         | 100       | 10.75%  |
| 251-500        | 58        | 6.24%   |
| Unknown        | 36        | 3.87%   |
| 501-1000       | 30        | 3.23%   |
| 1001-2000      | 13        | 1.4%    |
| More than 3000 | 1         | 0.11%   |
| 2001-3000      | 1         | 0.11%   |
| 0              | 1         | 0.11%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                           | 4         | 4      | 10.26%  |
| Seagate ST9250410AS 250GB                           | 2         | 3      | 5.13%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD      | 2         | 3      | 5.13%   |
| HGST HTS541010A9E680 1TB                            | 2         | 2      | 5.13%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 1         | 1      | 2.56%   |
| Union Memory UMIS RPJTJ128MED1MWX 128GB             | 1         | 1      | 2.56%   |
| Transcend TS240GMTS420S 240GB SSD                   | 1         | 1      | 2.56%   |
| Toshiba MK1633GSG 160GB                             | 1         | 1      | 2.56%   |
| Toshiba MK1237GSX 120GB                             | 1         | 1      | 2.56%   |
| SK hynix SH920 mSATA 128GB SSD                      | 1         | 1      | 2.56%   |
| Seagate ST96812A 64GB                               | 1         | 1      | 2.56%   |
| Seagate ST9500420AS 500GB                           | 1         | 1      | 2.56%   |
| Seagate ST9250315AS 250GB                           | 1         | 1      | 2.56%   |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 1      | 2.56%   |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 1      | 2.56%   |
| Seagate ST1000LM049-2GH172 1TB                      | 1         | 1      | 2.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 2.56%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD                 | 1         | 1      | 2.56%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 1         | 1      | 2.56%   |
| Samsung Electronics MZ7PA128HMCD-010L1 128GB SSD    | 1         | 1      | 2.56%   |
| OCZ AGILITY3 120GB SSD                              | 1         | 1      | 2.56%   |
| Micron Technology MTFDDAK512TBN-1AR1ZABHA 512GB SSD | 1         | 1      | 2.56%   |
| LITEONIT LMT-256M6M-HP 256GB SSD                    | 1         | 1      | 2.56%   |
| Intel SSDSCKJF180A5H RSED 180GB                     | 1         | 1      | 2.56%   |
| Intel SSDSC2BW480A4 480GB                           | 1         | 1      | 2.56%   |
| Intel SSDSC2BW240A4 240GB                           | 1         | 2      | 2.56%   |
| Intel SSDSA2BW160G3H 160GB                          | 1         | 1      | 2.56%   |
| Hitachi HTS543216L9A300 160GB                       | 1         | 1      | 2.56%   |
| Hitachi HTS542525K9SA00 250GB                       | 1         | 1      | 2.56%   |
| Hitachi HTS541616J9AT00 160GB                       | 1         | 1      | 2.56%   |
| HGST HTS725050A7E630 500GB                          | 1         | 1      | 2.56%   |
| HGST HTS545050A7E680 500GB                          | 1         | 1      | 2.56%   |
| Corsair Force 3 SSD 240GB                           | 1         | 1      | 2.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 14     | 33.33%  |
| Intel               | 4         | 5      | 10.26%  |
| HGST                | 4         | 4      | 10.26%  |
| Micron Technology   | 3         | 4      | 7.69%   |
| Hitachi             | 3         | 3      | 7.69%   |
| Toshiba             | 2         | 2      | 5.13%   |
| Samsung Electronics | 2         | 2      | 5.13%   |
| WDC                 | 1         | 1      | 2.56%   |
| Union Memory        | 1         | 1      | 2.56%   |
| Transcend           | 1         | 1      | 2.56%   |
| SK hynix            | 1         | 1      | 2.56%   |
| SanDisk             | 1         | 1      | 2.56%   |
| OCZ                 | 1         | 1      | 2.56%   |
| LITEONIT            | 1         | 1      | 2.56%   |
| Corsair             | 1         | 1      | 2.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 13        | 14     | 56.52%  |
| HGST    | 4         | 4      | 17.39%  |
| Hitachi | 3         | 3      | 13.04%  |
| Toshiba | 2         | 2      | 8.7%    |
| WDC     | 1         | 1      | 4.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 23        | 24     | 58.97%  |
| SSD  | 15        | 17     | 38.46%  |
| NVMe | 1         | 1      | 2.56%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                                           | Notebooks | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 256GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 561       | 827    | 62.2%   |
| Works    | 302       | 388    | 33.48%  |
| Malfunc  | 38        | 42     | 4.21%   |
| Failed   | 1         | 1      | 0.11%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 570       | 58.34%  |
| Samsung Electronics              | 113       | 11.57%  |
| AMD                              | 87        | 8.9%    |
| SanDisk                          | 49        | 5.02%   |
| Toshiba America Info Systems     | 37        | 3.79%   |
| SK hynix                         | 36        | 3.68%   |
| Kingston Technology Company      | 16        | 1.64%   |
| Micron Technology                | 15        | 1.54%   |
| Phison Electronics               | 8         | 0.82%   |
| KIOXIA                           | 7         | 0.72%   |
| Nvidia                           | 6         | 0.61%   |
| Union Memory (Shenzhen)          | 4         | 0.41%   |
| Silicon Motion                   | 4         | 0.41%   |
| Lite-On Technology               | 4         | 0.41%   |
| Apple                            | 4         | 0.41%   |
| Solid State Storage Technology   | 3         | 0.31%   |
| Silicon Integrated Systems [SiS] | 3         | 0.31%   |
| Marvell Technology Group         | 3         | 0.31%   |
| Lenovo                           | 3         | 0.31%   |
| ADATA Technology                 | 3         | 0.31%   |
| Realtek Semiconductor            | 1         | 0.1%    |
| Micron/Crucial Technology        | 1         | 0.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 72        | 6.94%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 71        | 6.84%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 60        | 5.78%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 59        | 5.68%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 52        | 5.01%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 46        | 4.43%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 44        | 4.24%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 35        | 3.37%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 33        | 3.18%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 28        | 2.7%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 22        | 2.12%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 20        | 1.93%   |
| Samsung NVMe SSD Controller 980                                                | 19        | 1.83%   |
| Intel Volume Management Device NVMe RAID Controller                            | 18        | 1.73%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 18        | 1.73%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 16        | 1.54%   |
| Micron Non-Volatile memory controller                                          | 15        | 1.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 15        | 1.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 14        | 1.35%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 13        | 1.25%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 12        | 1.16%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 12        | 1.16%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 12        | 1.16%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 11        | 1.06%   |
| SK hynix Non-Volatile memory controller                                        | 11        | 1.06%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 10        | 0.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 10        | 0.96%   |
| Intel SSD 660P Series                                                          | 9         | 0.87%   |
| Intel SSD 600P Series                                                          | 9         | 0.87%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 8         | 0.77%   |
| SanDisk Non-Volatile memory controller                                         | 8         | 0.77%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 8         | 0.77%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 8         | 0.77%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 7         | 0.67%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 7         | 0.67%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 7         | 0.67%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 7         | 0.67%   |
| Samsung Electronics SATA controller                                            | 7         | 0.67%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 7         | 0.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 7         | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 559       | 55.68%  |
| NVMe | 307       | 30.58%  |
| RAID | 73        | 7.27%   |
| IDE  | 65        | 6.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 717       | 83.96%  |
| AMD    | 137       | 16.04%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz       | 20        | 2.34%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 19        | 2.22%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 15        | 1.76%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 14        | 1.64%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 12        | 1.41%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 12        | 1.41%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 11        | 1.29%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 10        | 1.17%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 10        | 1.17%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 10        | 1.17%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 9         | 1.05%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 9         | 1.05%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 8         | 0.94%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 8         | 0.94%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 8         | 0.94%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 8         | 0.94%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 8         | 0.94%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 8         | 0.94%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 7         | 0.82%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz      | 7         | 0.82%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 7         | 0.82%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 7         | 0.82%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 7         | 0.82%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 7         | 0.82%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 7         | 0.82%   |
| Intel Core i7-8850H CPU @ 2.60GHz       | 6         | 0.7%    |
| Intel Core i7-4510U CPU @ 2.00GHz       | 6         | 0.7%    |
| Intel Core i7-3610QM CPU @ 2.30GHz      | 6         | 0.7%    |
| Intel Core i5-8365U CPU @ 1.60GHz       | 6         | 0.7%    |
| Intel Core i5-6300U CPU @ 2.40GHz       | 6         | 0.7%    |
| Intel Core i5-3320M CPU @ 2.60GHz       | 6         | 0.7%    |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 6         | 0.7%    |
| AMD Ryzen 7 5700U with Radeon Graphics  | 6         | 0.7%    |
| AMD Ryzen 7 4800H with Radeon Graphics  | 6         | 0.7%    |
| Intel Core i7-9850H CPU @ 2.60GHz       | 5         | 0.59%   |
| Intel Core i7-8665U CPU @ 1.90GHz       | 5         | 0.59%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 5         | 0.59%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 5         | 0.59%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz      | 5         | 0.59%   |
| Intel Core i7-3740QM CPU @ 2.70GHz      | 5         | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 264       | 30.91%  |
| Intel Core i5                  | 221       | 25.88%  |
| Other                          | 58        | 6.79%   |
| Intel Core i3                  | 47        | 5.5%    |
| Intel Core 2 Duo               | 38        | 4.45%   |
| Intel Celeron                  | 31        | 3.63%   |
| AMD Ryzen 7                    | 30        | 3.51%   |
| AMD Ryzen 5                    | 24        | 2.81%   |
| Intel Pentium                  | 13        | 1.52%   |
| Intel Atom                     | 13        | 1.52%   |
| Intel Genuine                  | 9         | 1.05%   |
| AMD Ryzen 3                    | 9         | 1.05%   |
| AMD A6                         | 8         | 0.94%   |
| AMD Ryzen 9                    | 7         | 0.82%   |
| AMD A8                         | 7         | 0.82%   |
| Intel Core i9                  | 6         | 0.7%    |
| Intel Core 2                   | 6         | 0.7%    |
| AMD E1                         | 6         | 0.7%    |
| AMD A4                         | 6         | 0.7%    |
| Intel Xeon                     | 5         | 0.59%   |
| AMD E                          | 5         | 0.59%   |
| AMD A10                        | 5         | 0.59%   |
| AMD Ryzen 7 PRO                | 4         | 0.47%   |
| Intel Pentium Dual             | 3         | 0.35%   |
| AMD Ryzen 5 PRO                | 3         | 0.35%   |
| Intel Pentium Silver           | 2         | 0.23%   |
| Intel Pentium M                | 2         | 0.23%   |
| Intel Core m3                  | 2         | 0.23%   |
| Intel Celeron Dual-Core        | 2         | 0.23%   |
| AMD Turion 64 X2 Mobile        | 2         | 0.23%   |
| Intel Pentium Dual-Core        | 1         | 0.12%   |
| Intel Core m5                  | 1         | 0.12%   |
| Intel Celeron M                | 1         | 0.12%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.12%   |
| AMD Turion II Dual-Core        | 1         | 0.12%   |
| AMD Turion 64 Mobile           | 1         | 0.12%   |
| AMD Sempron                    | 1         | 0.12%   |
| AMD Quad-Core                  | 1         | 0.12%   |
| AMD PRO A10                    | 1         | 0.12%   |
| AMD Phenom II                  | 1         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 431       | 50.47%  |
| 4      | 291       | 34.07%  |
| 6      | 64        | 7.49%   |
| 8      | 49        | 5.74%   |
| 1      | 12        | 1.41%   |
| 14     | 3         | 0.35%   |
| 12     | 3         | 0.35%   |
| 10     | 1         | 0.12%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 854       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 675       | 78.95%  |
| 1      | 180       | 21.05%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 834       | 97.32%  |
| Unknown        | 16        | 1.87%   |
| 32-bit         | 7         | 0.82%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 198       | 22.37%  |
| 0x306a9    | 50        | 5.65%   |
| 0x40651    | 44        | 4.97%   |
| 0x206a7    | 44        | 4.97%   |
| 0x306c3    | 37        | 4.18%   |
| 0x406e3    | 33        | 3.73%   |
| 0x306d4    | 33        | 3.73%   |
| 0x806ec    | 32        | 3.62%   |
| 0x806e9    | 29        | 3.28%   |
| 0x806ea    | 28        | 3.16%   |
| 0x806c1    | 27        | 3.05%   |
| 0x20655    | 23        | 2.6%    |
| 0x1067a    | 23        | 2.6%    |
| 0x906ea    | 22        | 2.49%   |
| 0x906e9    | 21        | 2.37%   |
| 0xa0652    | 10        | 1.13%   |
| 0x806eb    | 10        | 1.13%   |
| 0x6fd      | 10        | 1.13%   |
| 0x0a50000c | 10        | 1.13%   |
| 0x0700010f | 9         | 1.02%   |
| 0x406c4    | 8         | 0.9%    |
| 0x30678    | 8         | 0.9%    |
| 0x08108109 | 8         | 0.9%    |
| 0x0810100b | 8         | 0.9%    |
| 0x806d1    | 7         | 0.79%   |
| 0x506e3    | 7         | 0.79%   |
| 0x20652    | 7         | 0.79%   |
| 0x08608103 | 7         | 0.79%   |
| 0x08600106 | 7         | 0.79%   |
| 0x08108102 | 7         | 0.79%   |
| 0x05000119 | 7         | 0.79%   |
| 0x906ed    | 6         | 0.68%   |
| 0x906a3    | 6         | 0.68%   |
| 0x6fb      | 6         | 0.68%   |
| 0x6f6      | 6         | 0.68%   |
| 0x10676    | 6         | 0.68%   |
| 0x40661    | 5         | 0.56%   |
| 0x06001119 | 5         | 0.56%   |
| 0x03000027 | 5         | 0.56%   |
| 0x706e5    | 4         | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 194       | 22.72%  |
| Haswell          | 99        | 11.59%  |
| IvyBridge        | 63        | 7.38%   |
| SandyBridge      | 59        | 6.91%   |
| Skylake          | 50        | 5.85%   |
| Broadwell        | 38        | 4.45%   |
| Westmere         | 34        | 3.98%   |
| TigerLake        | 34        | 3.98%   |
| Penryn           | 31        | 3.63%   |
| Silvermont       | 29        | 3.4%    |
| Core             | 29        | 3.4%    |
| Unknown          | 24        | 2.81%   |
| Zen 3            | 21        | 2.46%   |
| Zen+             | 18        | 2.11%   |
| Zen 2            | 16        | 1.87%   |
| CometLake        | 16        | 1.87%   |
| Excavator        | 11        | 1.29%   |
| Zen              | 10        | 1.17%   |
| Icelake          | 10        | 1.17%   |
| Jaguar           | 9         | 1.05%   |
| Piledriver       | 6         | 0.7%    |
| K10 Llano        | 6         | 0.7%    |
| Goldmont plus    | 6         | 0.7%    |
| Bobcat           | 6         | 0.7%    |
| Puma             | 5         | 0.59%   |
| K8 Hammer        | 5         | 0.59%   |
| Bonnell          | 5         | 0.59%   |
| Alderlake Hybrid | 5         | 0.59%   |
| P6               | 4         | 0.47%   |
| K10              | 4         | 0.47%   |
| Nehalem          | 3         | 0.35%   |
| K8 & K10 hybrid  | 2         | 0.23%   |
| Goldmont         | 2         | 0.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 637       | 59.15%  |
| Nvidia                           | 260       | 24.14%  |
| AMD                              | 177       | 16.43%  |
| Silicon Integrated Systems [SiS] | 3         | 0.28%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 54        | 4.84%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 53        | 4.75%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 52        | 4.66%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 40        | 3.58%   |
| Intel UHD Graphics 620                                                                   | 38        | 3.41%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 38        | 3.41%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 35        | 3.14%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 33        | 2.96%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 31        | 2.78%   |
| Intel HD Graphics 5500                                                                   | 30        | 2.69%   |
| Intel HD Graphics 620                                                                    | 29        | 2.6%    |
| Intel HD Graphics 630                                                                    | 23        | 2.06%   |
| Intel Core Processor Integrated Graphics Controller                                      | 23        | 2.06%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 19        | 1.7%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 19        | 1.7%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 16        | 1.43%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 16        | 1.43%   |
| AMD Renoir                                                                               | 16        | 1.43%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 15        | 1.34%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 14        | 1.25%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 14        | 1.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 13        | 1.16%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 12        | 1.08%   |
| AMD Lucienne                                                                             | 11        | 0.99%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 10        | 0.9%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 9         | 0.81%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 9         | 0.81%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 9         | 0.81%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 8         | 0.72%   |
| Nvidia GM108M [GeForce 840M]                                                             | 8         | 0.72%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 7         | 0.63%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 7         | 0.63%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 7         | 0.63%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 7         | 0.63%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 7         | 0.63%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 6         | 0.54%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 6         | 0.54%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 6         | 0.54%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 6         | 0.54%   |
| Intel HD Graphics 530                                                                    | 6         | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 435       | 50.76%  |
| Intel + Nvidia | 178       | 20.77%  |
| 1 x AMD        | 117       | 13.65%  |
| 1 x Nvidia     | 63        | 7.35%   |
| Intel + AMD    | 25        | 2.92%   |
| AMD + Nvidia   | 19        | 2.22%   |
| 2 x AMD        | 17        | 1.98%   |
| 1 x SiS        | 3         | 0.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 704       | 81.39%  |
| Proprietary | 144       | 16.65%  |
| Unknown     | 17        | 1.97%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 553       | 63.27%  |
| 1.01-2.0   | 101       | 11.56%  |
| 0.01-0.5   | 99        | 11.33%  |
| 0.51-1.0   | 49        | 5.61%   |
| 3.01-4.0   | 47        | 5.38%   |
| 5.01-6.0   | 13        | 1.49%   |
| 7.01-8.0   | 8         | 0.92%   |
| 2.01-3.0   | 4         | 0.46%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 229       | 22.7%   |
| LG Display              | 130       | 12.88%  |
| Chimei Innolux          | 121       | 11.99%  |
| Samsung Electronics     | 105       | 10.41%  |
| BOE                     | 68        | 6.74%   |
| Sharp                   | 49        | 4.86%   |
| Dell                    | 35        | 3.47%   |
| Apple                   | 35        | 3.47%   |
| Lenovo                  | 24        | 2.38%   |
| Chi Mei Optoelectronics | 20        | 1.98%   |
| Philips                 | 19        | 1.88%   |
| InfoVision              | 17        | 1.68%   |
| LG Philips              | 16        | 1.59%   |
| Hewlett-Packard         | 13        | 1.29%   |
| BenQ                    | 11        | 1.09%   |
| ASUSTek Computer        | 10        | 0.99%   |
| AOC                     | 10        | 0.99%   |
| Goldstar                | 8         | 0.79%   |
| CSO                     | 8         | 0.79%   |
| Ancor Communications    | 8         | 0.79%   |
| Acer                    | 8         | 0.79%   |
| PANDA                   | 6         | 0.59%   |
| Sony                    | 5         | 0.5%    |
| Panasonic               | 5         | 0.5%    |
| BOE Technology Group    | 5         | 0.5%    |
| Quanta Display          | 4         | 0.4%    |
| LGD                     | 4         | 0.4%    |
| Vestel Elektronik       | 3         | 0.3%    |
| Toshiba                 | 3         | 0.3%    |
| Eizo                    | 3         | 0.3%    |
| Analogix                | 3         | 0.3%    |
| Unknown                 | 2         | 0.2%    |
| Nvidia                  | 2         | 0.2%    |
| CPT                     | 2         | 0.2%    |
| VOXICON                 | 1         | 0.1%    |
| ViewSonic               | 1         | 0.1%    |
| SMP                     | 1         | 0.1%    |
| RTK                     | 1         | 0.1%    |
| Positivo                | 1         | 0.1%    |
| Olevia                  | 1         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 11        | 1.08%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 8         | 0.78%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 7         | 0.68%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 7         | 0.68%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 7         | 0.68%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 7         | 0.68%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 7         | 0.68%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 6         | 0.59%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 6         | 0.59%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 6         | 0.59%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 5         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 5         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 5         | 0.49%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 4         | 0.39%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 4         | 0.39%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch           | 4         | 0.39%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 4         | 0.39%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 4         | 0.39%   |
| InfoVision LCD Monitor IVO857F 1920x1080 294x165mm 13.3-inch          | 4         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 4         | 0.39%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch      | 4         | 0.39%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 4         | 0.39%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch      | 4         | 0.39%   |
| AU Optronics LCD Monitor AUOD291 1920x1200 301x188mm 14.0-inch        | 4         | 0.39%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch        | 4         | 0.39%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 4         | 0.39%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch  | 3         | 0.29%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 3         | 0.29%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 3         | 0.29%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 3         | 0.29%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 3         | 0.29%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch | 3         | 0.29%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 3         | 0.29%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 3         | 0.29%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch           | 3         | 0.29%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch          | 3         | 0.29%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch               | 3         | 0.29%   |
| Hewlett-Packard E273q HPN3474 2560x1440 597x336mm 27.0-inch           | 3         | 0.29%   |
| Hewlett-Packard E243i HPN3462 1920x1200 520x320mm 24.0-inch           | 3         | 0.29%   |
| Dell U3011 DEL4065 2560x1600 641x401mm 29.8-inch                      | 3         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 421       | 43.67%  |
| 1366x768 (WXGA)    | 211       | 21.89%  |
| 3840x2160 (4K)     | 57        | 5.91%   |
| 2560x1440 (QHD)    | 43        | 4.46%   |
| 1280x800 (WXGA)    | 37        | 3.84%   |
| 1600x900 (HD+)     | 35        | 3.63%   |
| 1920x1200 (WUXGA)  | 29        | 3.01%   |
| 1440x900 (WXGA+)   | 17        | 1.76%   |
| 2880x1800          | 15        | 1.56%   |
| 2560x1600          | 14        | 1.45%   |
| 3840x2400          | 13        | 1.35%   |
| 1680x1050 (WSXGA+) | 12        | 1.24%   |
| 3440x1440          | 11        | 1.14%   |
| 1280x1024 (SXGA)   | 6         | 0.62%   |
| 1024x768 (XGA)     | 6         | 0.62%   |
| 3200x1800 (QHD+)   | 5         | 0.52%   |
| 1024x600           | 5         | 0.52%   |
| 800x1280           | 4         | 0.41%   |
| Unknown            | 4         | 0.41%   |
| 3840x1080          | 3         | 0.31%   |
| 2160x1440          | 3         | 0.31%   |
| 1920x540           | 3         | 0.31%   |
| 1360x768           | 3         | 0.31%   |
| 2288x1287          | 2         | 0.21%   |
| 3840x1600          | 1         | 0.1%    |
| 2880x1920          | 1         | 0.1%    |
| 2560x1080          | 1         | 0.1%    |
| 1920x1280          | 1         | 0.1%    |
| 1400x1050          | 1         | 0.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 334       | 33.07%  |
| 13      | 183       | 18.12%  |
| 14      | 126       | 12.48%  |
| 17      | 65        | 6.44%   |
| 27      | 46        | 4.55%   |
| 12      | 46        | 4.55%   |
| 24      | 42        | 4.16%   |
| Unknown | 26        | 2.57%   |
| 23      | 23        | 2.28%   |
| 11      | 23        | 2.28%   |
| 31      | 12        | 1.19%   |
| 34      | 9         | 0.89%   |
| 21      | 7         | 0.69%   |
| 18      | 6         | 0.59%   |
| 84      | 5         | 0.5%    |
| 32      | 5         | 0.5%    |
| 22      | 5         | 0.5%    |
| 19      | 5         | 0.5%    |
| 16      | 5         | 0.5%    |
| 10      | 5         | 0.5%    |
| 54      | 3         | 0.3%    |
| 29      | 3         | 0.3%    |
| 65      | 2         | 0.2%    |
| 48      | 2         | 0.2%    |
| 47      | 2         | 0.2%    |
| 42      | 2         | 0.2%    |
| 37      | 2         | 0.2%    |
| 35      | 2         | 0.2%    |
| 33      | 2         | 0.2%    |
| 26      | 2         | 0.2%    |
| 142     | 1         | 0.1%    |
| 75      | 1         | 0.1%    |
| 74      | 1         | 0.1%    |
| 72      | 1         | 0.1%    |
| 60      | 1         | 0.1%    |
| 40      | 1         | 0.1%    |
| 39      | 1         | 0.1%    |
| 25      | 1         | 0.1%    |
| 20      | 1         | 0.1%    |
| 9       | 1         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 537       | 53.65%  |
| 201-300        | 176       | 17.58%  |
| 501-600        | 103       | 10.29%  |
| 351-400        | 75        | 7.49%   |
| Unknown        | 26        | 2.6%    |
| 601-700        | 20        | 2%      |
| 401-500        | 20        | 2%      |
| 701-800        | 16        | 1.6%    |
| 1001-1500      | 10        | 1%      |
| 1501-2000      | 8         | 0.8%    |
| 801-900        | 5         | 0.5%    |
| 901-1000       | 3         | 0.3%    |
| More than 2000 | 1         | 0.1%    |
| 101-200        | 1         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 694       | 77.89%  |
| 16/10   | 135       | 15.15%  |
| Unknown | 20        | 2.24%   |
| 21/9    | 13        | 1.46%   |
| 4/3     | 8         | 0.9%    |
| 3/2     | 8         | 0.9%    |
| 5/4     | 6         | 0.67%   |
| 0.62    | 4         | 0.45%   |
| 32/9    | 2         | 0.22%   |
| 1.00    | 1         | 0.11%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 332       | 32.97%  |
| 81-90          | 223       | 22.14%  |
| 71-80          | 85        | 8.44%   |
| 121-130        | 56        | 5.56%   |
| 201-250        | 55        | 5.46%   |
| 301-350        | 48        | 4.77%   |
| 61-70          | 44        | 4.37%   |
| 351-500        | 31        | 3.08%   |
| Unknown        | 26        | 2.58%   |
| 51-60          | 23        | 2.28%   |
| 251-300        | 22        | 2.18%   |
| More than 1000 | 16        | 1.59%   |
| 131-140        | 9         | 0.89%   |
| 501-1000       | 9         | 0.89%   |
| 151-200        | 7         | 0.7%    |
| 41-50          | 6         | 0.6%    |
| 141-150        | 6         | 0.6%    |
| 111-120        | 5         | 0.5%    |
| 91-100         | 4         | 0.4%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 413       | 41.84%  |
| 101-120       | 232       | 23.51%  |
| 51-100        | 145       | 14.69%  |
| 161-240       | 101       | 10.23%  |
| More than 240 | 54        | 5.47%   |
| Unknown       | 26        | 2.63%   |
| 1-50          | 16        | 1.62%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 679       | 77.69%  |
| 2     | 159       | 18.19%  |
| 3     | 19        | 2.17%   |
| 0     | 17        | 1.95%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 520       | 39.45%  |
| Realtek Semiconductor                  | 338       | 25.64%  |
| Qualcomm Atheros                       | 170       | 12.9%   |
| Broadcom                               | 95        | 7.21%   |
| Broadcom Limited                       | 31        | 2.35%   |
| MediaTek                               | 16        | 1.21%   |
| Hewlett-Packard                        | 15        | 1.14%   |
| Ralink                                 | 12        | 0.91%   |
| Dell                                   | 12        | 0.91%   |
| Marvell Technology Group               | 11        | 0.83%   |
| ASIX Electronics                       | 10        | 0.76%   |
| Sierra Wireless                        | 8         | 0.61%   |
| Lenovo                                 | 7         | 0.53%   |
| Huawei Technologies                    | 6         | 0.46%   |
| Ericsson Business Mobile Networks      | 6         | 0.46%   |
| Nvidia                                 | 5         | 0.38%   |
| DisplayLink                            | 5         | 0.38%   |
| ASUSTek Computer                       | 5         | 0.38%   |
| NetGear                                | 4         | 0.3%    |
| Fibocom                                | 4         | 0.3%    |
| TP-Link                                | 3         | 0.23%   |
| Silicon Integrated Systems [SiS]       | 3         | 0.23%   |
| Qualcomm                               | 3         | 0.23%   |
| D-Link                                 | 3         | 0.23%   |
| Texas Instruments                      | 2         | 0.15%   |
| Samsung Electronics                    | 2         | 0.15%   |
| Ralink Technology                      | 2         | 0.15%   |
| Microsoft                              | 2         | 0.15%   |
| Wacom                                  | 1         | 0.08%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.08%   |
| SEGGER                                 | 1         | 0.08%   |
| Qualcomm Atheros Communications        | 1         | 0.08%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.08%   |
| Novatek Microelectronics               | 1         | 0.08%   |
| Linksys                                | 1         | 0.08%   |
| JMicron Technology                     | 1         | 0.08%   |
| IMC Networks                           | 1         | 0.08%   |
| ICS Advent                             | 1         | 0.08%   |
| Gemtek                                 | 1         | 0.08%   |
| Edimax Technology                      | 1         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 212       | 12.77%  |
| Intel Wireless 8265 / 8275                                        | 60        | 3.61%   |
| Intel Wireless 7260                                               | 54        | 3.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 46        | 2.77%   |
| Intel Wi-Fi 6 AX200                                               | 44        | 2.65%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 40        | 2.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 38        | 2.29%   |
| Intel Wireless 7265                                               | 36        | 2.17%   |
| Intel Wireless 8260                                               | 33        | 1.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 28        | 1.69%   |
| Intel Wi-Fi 6 AX201                                               | 28        | 1.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 25        | 1.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 25        | 1.51%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 24        | 1.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 20        | 1.2%    |
| Intel Ethernet Connection I218-LM                                 | 20        | 1.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 20        | 1.2%    |
| Intel Ethernet Connection (3) I218-LM                             | 19        | 1.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 18        | 1.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 18        | 1.08%   |
| Intel Ethernet Connection (4) I219-V                              | 17        | 1.02%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 17        | 1.02%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 16        | 0.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 15        | 0.9%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 15        | 0.9%    |
| Intel Wireless-AC 9260                                            | 14        | 0.84%   |
| Intel Ethernet Connection I219-LM                                 | 14        | 0.84%   |
| Intel Ethernet Connection (4) I219-LM                             | 14        | 0.84%   |
| Intel Centrino Advanced-N 6200                                    | 14        | 0.84%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 14        | 0.84%   |
| Intel Wireless 3160                                               | 13        | 0.78%   |
| Intel Ethernet Connection I217-LM                                 | 13        | 0.78%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 13        | 0.78%   |
| Intel 82577LM Gigabit Network Connection                          | 13        | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 12        | 0.72%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 12        | 0.72%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 12        | 0.72%   |
| Intel Ethernet Connection I219-V                                  | 11        | 0.66%   |
| Intel Centrino Advanced-N 6235                                    | 11        | 0.66%   |
| Intel Ethernet Connection (6) I219-V                              | 10        | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 500       | 55.74%  |
| Qualcomm Atheros                | 143       | 15.94%  |
| Realtek Semiconductor           | 92        | 10.26%  |
| Broadcom                        | 69        | 7.69%   |
| Broadcom Limited                | 18        | 2.01%   |
| MediaTek                        | 16        | 1.78%   |
| Ralink                          | 12        | 1.34%   |
| Sierra Wireless                 | 8         | 0.89%   |
| Dell                            | 6         | 0.67%   |
| ASUSTek Computer                | 5         | 0.56%   |
| NetGear                         | 4         | 0.45%   |
| Hewlett-Packard                 | 4         | 0.45%   |
| Fibocom                         | 4         | 0.45%   |
| Ralink Technology               | 2         | 0.22%   |
| Qualcomm                        | 2         | 0.22%   |
| D-Link                          | 2         | 0.22%   |
| Wacom                           | 1         | 0.11%   |
| TP-Link                         | 1         | 0.11%   |
| Qualcomm Atheros Communications | 1         | 0.11%   |
| Microsoft                       | 1         | 0.11%   |
| Linksys                         | 1         | 0.11%   |
| IMC Networks                    | 1         | 0.11%   |
| Edimax Technology               | 1         | 0.11%   |
| D-Link System                   | 1         | 0.11%   |
| Chu Yuen Enterprise             | 1         | 0.11%   |
| Belkin Components               | 1         | 0.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 60        | 6.67%   |
| Intel Wireless 7260                                            | 54        | 6%      |
| Intel Wi-Fi 6 AX200                                            | 44        | 4.89%   |
| Intel Wireless 7265                                            | 36        | 4%      |
| Intel Wireless 8260                                            | 33        | 3.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 28        | 3.11%   |
| Intel Wi-Fi 6 AX201                                            | 28        | 3.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 25        | 2.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 25        | 2.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 24        | 2.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 20        | 2.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 20        | 2.22%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 18        | 2%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 18        | 2%      |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 17        | 1.89%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 16        | 1.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 15        | 1.67%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 15        | 1.67%   |
| Intel Wireless-AC 9260                                         | 14        | 1.56%   |
| Intel Centrino Advanced-N 6200                                 | 14        | 1.56%   |
| Intel Wireless 3160                                            | 13        | 1.44%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 13        | 1.44%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 12        | 1.33%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 12        | 1.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 12        | 1.33%   |
| Intel Centrino Advanced-N 6235                                 | 11        | 1.22%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 10        | 1.11%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 9         | 1%      |
| Intel Centrino Wireless-N 2230                                 | 8         | 0.89%   |
| Intel Centrino Ultimate-N 6300                                 | 8         | 0.89%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 7         | 0.78%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 7         | 0.78%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 7         | 0.78%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 7         | 0.78%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 7         | 0.78%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 7         | 0.78%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 7         | 0.78%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 7         | 0.78%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 6         | 0.67%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 6         | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 306       | 42.32%  |
| Intel                            | 245       | 33.89%  |
| Qualcomm Atheros                 | 55        | 7.61%   |
| Broadcom                         | 42        | 5.81%   |
| Broadcom Limited                 | 14        | 1.94%   |
| Marvell Technology Group         | 11        | 1.52%   |
| ASIX Electronics                 | 10        | 1.38%   |
| Lenovo                           | 7         | 0.97%   |
| Nvidia                           | 5         | 0.69%   |
| Huawei Technologies              | 5         | 0.69%   |
| Hewlett-Packard                  | 5         | 0.69%   |
| DisplayLink                      | 5         | 0.69%   |
| TP-Link                          | 2         | 0.28%   |
| Silicon Integrated Systems [SiS] | 2         | 0.28%   |
| Samsung Electronics              | 2         | 0.28%   |
| Qualcomm                         | 1         | 0.14%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.14%   |
| Microsoft                        | 1         | 0.14%   |
| JMicron Technology               | 1         | 0.14%   |
| ICS Advent                       | 1         | 0.14%   |
| Gemtek                           | 1         | 0.14%   |
| D-Link                           | 1         | 0.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 212       | 29.08%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 46        | 6.31%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 40        | 5.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 38        | 5.21%   |
| Intel Ethernet Connection I218-LM                                 | 20        | 2.74%   |
| Intel Ethernet Connection (3) I218-LM                             | 19        | 2.61%   |
| Intel Ethernet Connection (4) I219-V                              | 17        | 2.33%   |
| Intel Ethernet Connection I219-LM                                 | 14        | 1.92%   |
| Intel Ethernet Connection (4) I219-LM                             | 14        | 1.92%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 14        | 1.92%   |
| Intel Ethernet Connection I217-LM                                 | 13        | 1.78%   |
| Intel 82577LM Gigabit Network Connection                          | 13        | 1.78%   |
| Intel Ethernet Connection I219-V                                  | 11        | 1.51%   |
| Intel Ethernet Connection (6) I219-V                              | 10        | 1.37%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 9         | 1.23%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 9         | 1.23%   |
| Intel Ethernet Connection (6) I219-LM                             | 8         | 1.1%    |
| ASIX AX88179 Gigabit Ethernet                                     | 8         | 1.1%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 7         | 0.96%   |
| Intel Ethernet Connection I217-V                                  | 7         | 0.96%   |
| Intel 82566MM Gigabit Network Connection                          | 7         | 0.96%   |
| Intel 82567LM Gigabit Network Connection                          | 6         | 0.82%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 6         | 0.82%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5         | 0.69%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 5         | 0.69%   |
| Intel Ethernet Connection (7) I219-V                              | 5         | 0.69%   |
| Intel Ethernet Connection (7) I219-LM                             | 5         | 0.69%   |
| Intel Ethernet Connection (5) I219-LM                             | 5         | 0.69%   |
| Intel Ethernet Connection (14) I219-LM                            | 5         | 0.69%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 0.69%   |
| Huawei STK-L21                                                    | 5         | 0.69%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 5         | 0.69%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 5         | 0.69%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 4         | 0.55%   |
| HP lt4120 Snapdragon X5 LTE                                       | 4         | 0.55%   |
| DisplayLink Dell Universal Dock D6000                             | 4         | 0.55%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 4         | 0.55%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.41%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 0.41%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 845       | 53.86%  |
| Ethernet | 693       | 44.17%  |
| Modem    | 28        | 1.78%   |
| Unknown  | 3         | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 696       | 76.4%   |
| Ethernet | 214       | 23.49%  |
| Unknown  | 1         | 0.11%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 618       | 72.37%  |
| 1     | 222       | 26%     |
| 3     | 8         | 0.94%   |
| 0     | 6         | 0.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 829       | 96.51%  |
| Yes  | 30        | 3.49%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 375       | 53.34%  |
| Qualcomm Atheros Communications | 54        | 7.68%   |
| Realtek Semiconductor           | 44        | 6.26%   |
| Broadcom                        | 39        | 5.55%   |
| IMC Networks                    | 37        | 5.26%   |
| Foxconn / Hon Hai               | 29        | 4.13%   |
| Apple                           | 29        | 4.13%   |
| Lite-On Technology              | 25        | 3.56%   |
| Hewlett-Packard                 | 16        | 2.28%   |
| Dell                            | 15        | 2.13%   |
| ASUSTek Computer                | 10        | 1.42%   |
| Ralink                          | 7         | 1%      |
| Cambridge Silicon Radio         | 6         | 0.85%   |
| Toshiba                         | 4         | 0.57%   |
| Realtek                         | 3         | 0.43%   |
| Ralink Technology               | 2         | 0.28%   |
| MediaTek                        | 2         | 0.28%   |
| Chicony Electronics             | 2         | 0.28%   |
| USI                             | 1         | 0.14%   |
| Fujitsu                         | 1         | 0.14%   |
| Creative Technology             | 1         | 0.14%   |
| Alps Electric                   | 1         | 0.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 183       | 25.92%  |
| Intel AX201 Bluetooth                               | 59        | 8.36%   |
| Intel AX200 Bluetooth                               | 44        | 6.23%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 36        | 5.1%    |
| Realtek Bluetooth Radio                             | 32        | 4.53%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 18        | 2.55%   |
| Apple Bluetooth Host Controller                     | 18        | 2.55%   |
| IMC Networks Bluetooth Radio                        | 17        | 2.41%   |
| Foxconn / Hon Hai Bluetooth Device                  | 16        | 2.27%   |
| Qualcomm Atheros  Bluetooth Device                  | 14        | 1.98%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 14        | 1.98%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 12        | 1.7%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 11        | 1.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 11        | 1.56%   |
| Broadcom BCM2045B (BDC-2.1)                         | 11        | 1.56%   |
| Apple Bluetooth USB Host Controller                 | 10        | 1.42%   |
| Realtek  Bluetooth 4.2 Adapter                      | 8         | 1.13%   |
| Lite-On Bluetooth Device                            | 8         | 1.13%   |
| IMC Networks Bluetooth Device                       | 8         | 1.13%   |
| HP Broadcom 2070 Bluetooth Combo                    | 8         | 1.13%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 8         | 1.13%   |
| Ralink RT3290 Bluetooth                             | 7         | 0.99%   |
| Intel AX210 Bluetooth                               | 7         | 0.99%   |
| Lite-On Atheros AR3012 Bluetooth                    | 6         | 0.85%   |
| Intel Bluetooth Device                              | 6         | 0.85%   |
| Foxconn / Hon Hai Wireless_Device                   | 6         | 0.85%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 0.85%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 0.85%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 5         | 0.71%   |
| Intel Wireless-AC 3168 Bluetooth                    | 5         | 0.71%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 5         | 0.71%   |
| Dell DW375 Bluetooth Module                         | 5         | 0.71%   |
| IMC Networks Wireless_Device                        | 4         | 0.57%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 4         | 0.57%   |
| Dell BCM20702A0 Bluetooth Module                    | 4         | 0.57%   |
| Broadcom HP Portable SoftSailing                    | 4         | 0.57%   |
| Broadcom HP Portable Bumble Bee                     | 4         | 0.57%   |
| Broadcom BCM20702A0                                 | 4         | 0.57%   |
| ASUS BT-253 Bluetooth Adapter                       | 4         | 0.57%   |
| Realtek RTL8723B Bluetooth                          | 3         | 0.42%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 701       | 65.27%  |
| AMD                              | 155       | 14.43%  |
| Nvidia                           | 134       | 12.48%  |
| Realtek Semiconductor            | 11        | 1.02%   |
| C-Media Electronics              | 10        | 0.93%   |
| Logitech                         | 7         | 0.65%   |
| Plantronics                      | 5         | 0.47%   |
| Lenovo                           | 5         | 0.47%   |
| Kingston Technology              | 5         | 0.47%   |
| Silicon Integrated Systems [SiS] | 3         | 0.28%   |
| SAVITECH                         | 3         | 0.28%   |
| RODE Microphones                 | 3         | 0.28%   |
| Apple                            | 3         | 0.28%   |
| SteelSeries ApS                  | 2         | 0.19%   |
| Hewlett-Packard                  | 2         | 0.19%   |
| GN Netcom                        | 2         | 0.19%   |
| DSEA A/S                         | 2         | 0.19%   |
| Creative Technology              | 2         | 0.19%   |
| XMOS                             | 1         | 0.09%   |
| Texas Instruments                | 1         | 0.09%   |
| SlrTek                           | 1         | 0.09%   |
| Samson Technologies              | 1         | 0.09%   |
| QinHeng Electronics              | 1         | 0.09%   |
| PreSonus Audio Electronics       | 1         | 0.09%   |
| No brand                         | 1         | 0.09%   |
| Line6                            | 1         | 0.09%   |
| LG Electronics                   | 1         | 0.09%   |
| JMTek                            | 1         | 0.09%   |
| JBL                              | 1         | 0.09%   |
| GYROCOM C&C                      | 1         | 0.09%   |
| Generalplus Technology           | 1         | 0.09%   |
| Focusrite-Novation               | 1         | 0.09%   |
| Elite Silicon                    | 1         | 0.09%   |
| Digidesign                       | 1         | 0.09%   |
| Conexant Systems                 | 1         | 0.09%   |
| ASUSTek Computer                 | 1         | 0.09%   |
| Asahi Kasei Microsystems         | 1         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 112       | 8.56%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 73        | 5.58%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 68        | 5.2%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 53        | 4.05%   |
| Intel 8 Series HD Audio Controller                                                                | 53        | 4.05%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 53        | 4.05%   |
| Intel Cannon Lake PCH cAVS                                                                        | 45        | 3.44%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 45        | 3.44%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 41        | 3.13%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 38        | 2.91%   |
| Intel Broadwell-U Audio Controller                                                                | 38        | 2.91%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 37        | 2.83%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 35        | 2.68%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 34        | 2.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 29        | 2.22%   |
| AMD FCH Azalia Controller                                                                         | 28        | 2.14%   |
| Intel CM238 HD Audio Controller                                                                   | 26        | 1.99%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 26        | 1.99%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 25        | 1.91%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 21        | 1.61%   |
| AMD Kabini HDMI/DP Audio                                                                          | 19        | 1.45%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 18        | 1.38%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 15        | 1.15%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 14        | 1.07%   |
| Intel Comet Lake PCH cAVS                                                                         | 14        | 1.07%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 14        | 1.07%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 13        | 0.99%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 13        | 0.99%   |
| Nvidia High Definition Audio Controller                                                           | 12        | 0.92%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 12        | 0.92%   |
| Realtek Semiconductor USB Audio                                                                   | 11        | 0.84%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 11        | 0.84%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 10        | 0.76%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 9         | 0.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9         | 0.69%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 9         | 0.69%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 7         | 0.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 0.54%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 7         | 0.54%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 6         | 0.46%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 159       | 31.8%   |
| SK hynix            | 123       | 24.6%   |
| Micron Technology   | 70        | 14%     |
| Kingston            | 41        | 8.2%    |
| Unknown             | 33        | 6.6%    |
| Corsair             | 18        | 3.6%    |
| Crucial             | 12        | 2.4%    |
| Ramaxel Technology  | 9         | 1.8%    |
| Elpida              | 8         | 1.6%    |
| A-DATA Technology   | 7         | 1.4%    |
| Nanya Technology    | 4         | 0.8%    |
| Unknown             | 4         | 0.8%    |
| Team                | 2         | 0.4%    |
| Unknown (ABCD)      | 1         | 0.2%    |
| Qimonda             | 1         | 0.2%    |
| Patriot             | 1         | 0.2%    |
| Netlist             | 1         | 0.2%    |
| GSkill              | 1         | 0.2%    |
| GOODRAM             | 1         | 0.2%    |
| G.Skill             | 1         | 0.2%    |
| Avant               | 1         | 0.2%    |
| ASint Technology    | 1         | 0.2%    |
| Apacer              | 1         | 0.2%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 11        | 2.06%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 1.68%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 1.5%    |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 7         | 1.31%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 1.31%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 6         | 1.12%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 6         | 1.12%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 1.12%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 1.12%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 6         | 1.12%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.93%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 0.93%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 5         | 0.93%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 5         | 0.93%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.75%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 4         | 0.75%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 4         | 0.75%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 4         | 0.75%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                  | 4         | 0.75%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 4         | 0.75%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 4         | 0.75%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 4         | 0.75%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 4         | 0.75%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.75%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s      | 4         | 0.75%   |
| Unknown                                                          | 4         | 0.75%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 3         | 0.56%   |
| Unknown RAM Module 2048MB SODIMM DDR3                            | 3         | 0.56%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.56%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 3         | 0.56%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 3         | 0.56%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1334MT/s           | 3         | 0.56%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 3         | 0.56%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 3         | 0.56%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 3         | 0.56%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 3         | 0.56%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.56%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 3         | 0.56%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.56%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 186       | 41.8%   |
| DDR3    | 162       | 36.4%   |
| LPDDR4  | 35        | 7.87%   |
| LPDDR3  | 25        | 5.62%   |
| DDR2    | 19        | 4.27%   |
| SDRAM   | 8         | 1.8%    |
| DDR5    | 3         | 0.67%   |
| DRAM    | 2         | 0.45%   |
| DDR     | 2         | 0.45%   |
| Unknown | 2         | 0.45%   |
| LPDDR5  | 1         | 0.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 383       | 85.11%  |
| Row Of Chips | 56        | 12.44%  |
| Chip         | 8         | 1.78%   |
| Unknown      | 2         | 0.44%   |
| DIMM         | 1         | 0.22%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 178       | 37.32%  |
| 4096  | 123       | 25.79%  |
| 16384 | 90        | 18.87%  |
| 2048  | 67        | 14.05%  |
| 32768 | 9         | 1.89%   |
| 1024  | 8         | 1.68%   |
| 512   | 2         | 0.42%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 117       | 24.68%  |
| 2667    | 86        | 18.14%  |
| 3200    | 64        | 13.5%   |
| 2133    | 34        | 7.17%   |
| 2400    | 31        | 6.54%   |
| 1334    | 24        | 5.06%   |
| 4267    | 21        | 4.43%   |
| 1333    | 16        | 3.38%   |
| 667     | 13        | 2.74%   |
| Unknown | 12        | 2.53%   |
| 4266    | 9         | 1.9%    |
| 1867    | 9         | 1.9%    |
| 3266    | 6         | 1.27%   |
| 1067    | 5         | 1.05%   |
| 4199    | 4         | 0.84%   |
| 800     | 4         | 0.84%   |
| 8400    | 3         | 0.63%   |
| 4800    | 3         | 0.63%   |
| 6400    | 2         | 0.42%   |
| 2048    | 2         | 0.42%   |
| 1066    | 2         | 0.42%   |
| 975     | 2         | 0.42%   |
| 3733    | 1         | 0.21%   |
| 1639    | 1         | 0.21%   |
| 888     | 1         | 0.21%   |
| 533     | 1         | 0.21%   |
| 266     | 1         | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 42.86%  |
| Samsung Electronics | 2         | 28.57%  |
| Oki Data            | 1         | 14.29%  |
| Brother Industries  | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                        | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung SCX-3200 Series      | 1         | 14.29%  |
| Samsung M2070 Series         | 1         | 14.29%  |
| Oki Data USB Device          | 1         | 14.29%  |
| HP LaserJet P2035            | 1         | 14.29%  |
| HP ENVY 4520 series          | 1         | 14.29%  |
| HP DeskJet 5650c             | 1         | 14.29%  |
| Brother QL-500 label printer | 1         | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| HP ScanJet 2200c | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 198       | 26.83%  |
| Microdia                               | 81        | 10.98%  |
| IMC Networks                           | 70        | 9.49%   |
| Acer                                   | 65        | 8.81%   |
| Realtek Semiconductor                  | 56        | 7.59%   |
| Sunplus Innovation Technology          | 38        | 5.15%   |
| Cheng Uei Precision Industry (Foxlink) | 35        | 4.74%   |
| Lite-On Technology                     | 32        | 4.34%   |
| Quanta                                 | 24        | 3.25%   |
| Apple                                  | 24        | 3.25%   |
| Suyin                                  | 22        | 2.98%   |
| Syntek                                 | 16        | 2.17%   |
| Ricoh                                  | 10        | 1.36%   |
| Logitech                               | 10        | 1.36%   |
| Lenovo                                 | 8         | 1.08%   |
| ALi                                    | 6         | 0.81%   |
| Alcor Micro                            | 6         | 0.81%   |
| Silicon Motion                         | 4         | 0.54%   |
| Luxvisions Innotech Limited            | 4         | 0.54%   |
| DJJHFA1BIF5595                         | 4         | 0.54%   |
| Unknown                                | 3         | 0.41%   |
| Samsung Electronics                    | 3         | 0.41%   |
| Primax Electronics                     | 3         | 0.41%   |
| Sunplus Technology                     | 2         | 0.27%   |
| Importek                               | 2         | 0.27%   |
| DigiTech                               | 2         | 0.27%   |
| Creative Technology                    | 2         | 0.27%   |
| Z-Star Microelectronics                | 1         | 0.14%   |
| SunplusIT                              | 1         | 0.14%   |
| Sonix Technology                       | 1         | 0.14%   |
| Polycom                                | 1         | 0.14%   |
| LG Electronics                         | 1         | 0.14%   |
| Intel                                  | 1         | 0.14%   |
| Generalplus Technology                 | 1         | 0.14%   |
| Etron Technology                       | 1         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                            | 45        | 6.04%   |
| Chicony Integrated Camera                                                | 43        | 5.77%   |
| IMC Networks USB2.0 HD UVC WebCam                                        | 24        | 3.22%   |
| Realtek Integrated_Webcam_HD                                             | 21        | 2.82%   |
| IMC Networks Integrated Camera                                           | 21        | 2.82%   |
| Chicony HD WebCam                                                        | 19        | 2.55%   |
| Acer Integrated Camera                                                   | 18        | 2.42%   |
| Chicony HP HD Camera                                                     | 13        | 1.74%   |
| Acer Lenovo EasyCamera                                                   | 13        | 1.74%   |
| Sunplus HD WebCam                                                        | 11        | 1.48%   |
| Lite-On HP HD Camera                                                     | 11        | 1.48%   |
| Syntek Integrated Camera                                                 | 9         | 1.21%   |
| Sunplus Integrated_Webcam_HD                                             | 9         | 1.21%   |
| Lite-On Integrated Camera                                                | 9         | 1.21%   |
| Lite-On HP HD Webcam                                                     | 9         | 1.21%   |
| Chicony HP HD Webcam                                                     | 9         | 1.21%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                      | 9         | 1.21%   |
| Apple iPhone5/5C/5S/6                                                    | 9         | 1.21%   |
| Acer SunplusIT Integrated Camera                                         | 9         | 1.21%   |
| Quanta HP HD Camera                                                      | 8         | 1.07%   |
| Syntek Lenovo EasyCamera                                                 | 7         | 0.94%   |
| Chicony HP Truevision HD                                                 | 7         | 0.94%   |
| Chicony HP HD Webcam [Fixed]                                             | 7         | 0.94%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 7         | 0.94%   |
| Realtek USB Camera                                                       | 6         | 0.81%   |
| IMC Networks USB2.0 VGA UVC WebCam                                       | 6         | 0.81%   |
| Chicony USB2.0 HD UVC WebCam                                             | 6         | 0.81%   |
| Chicony USB2.0 Camera                                                    | 6         | 0.81%   |
| Chicony HD User Facing                                                   | 6         | 0.81%   |
| Apple FaceTime HD Camera                                                 | 6         | 0.81%   |
| Acer EasyCamera                                                          | 6         | 0.81%   |
| Realtek USB2.0 VGA UVC WebCam                                            | 5         | 0.67%   |
| Realtek USB2.0 HD UVC WebCam                                             | 5         | 0.67%   |
| Quanta HD Webcam                                                         | 5         | 0.67%   |
| IMC Networks USB2.0 UVC HD Webcam                                        | 5         | 0.67%   |
| ALi Gateway Webcam                                                       | 5         | 0.67%   |
| Suyin HP Truevision HD                                                   | 4         | 0.54%   |
| Sunplus Laptop Integrated Webcam HD                                      | 4         | 0.54%   |
| Sunplus HP HD Webcam [Fixed]                                             | 4         | 0.54%   |
| Realtek Integrated Webcam_HD                                             | 4         | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 99        | 47.37%  |
| Synaptics                  | 51        | 24.4%   |
| Shenzhen Goodix Technology | 18        | 8.61%   |
| AuthenTec                  | 11        | 5.26%   |
| Upek                       | 10        | 4.78%   |
| Elan Microelectronics      | 10        | 4.78%   |
| STMicroelectronics         | 6         | 2.87%   |
| LighTuning Technology      | 4         | 1.91%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 35        | 16.75%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 14        | 6.7%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 14        | 6.7%    |
| Shenzhen Goodix FingerPrint                                                | 12        | 5.74%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 9         | 4.31%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 9         | 4.31%   |
| Unknown                                                                    | 9         | 4.31%   |
| Validity Sensors VFS491                                                    | 8         | 3.83%   |
| Validity Sensors Synaptics WBDI                                            | 8         | 3.83%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 8         | 3.83%   |
| Elan ELAN:Fingerprint                                                      | 8         | 3.83%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 7         | 3.35%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 2.87%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 2.87%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 2.39%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 2.39%   |
| Shenzhen Goodix  Fingerprint Device                                        | 5         | 2.39%   |
| AuthenTec AES2810                                                          | 5         | 2.39%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 2.39%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 1.44%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 1.44%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 1.44%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 1.44%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 0.96%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.96%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 0.96%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 0.96%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.48%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.48%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.48%   |
| Synaptics WBDI Device                                                      | 1         | 0.48%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.48%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 0.48%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.48%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.48%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 1         | 0.48%   |
| Elan ELAN:ARM-M4                                                           | 1         | 0.48%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.48%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 51        | 44.74%  |
| Alcor Micro | 46        | 40.35%  |
| O2 Micro    | 8         | 7.02%   |
| Upek        | 4         | 3.51%   |
| Lenovo      | 4         | 3.51%   |
| Yubico.com  | 1         | 0.88%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 46        | 40.35%  |
| Broadcom BCM5880 Secure Applications Processor                               | 17        | 14.91%  |
| Broadcom 58200                                                               | 13        | 11.4%   |
| Broadcom 5880                                                                | 11        | 9.65%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 7.89%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 7         | 6.14%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 3.51%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 3.51%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.88%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.88%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.88%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 466       | 53.01%  |
| 1     | 316       | 35.95%  |
| 2     | 86        | 9.78%   |
| 3     | 8         | 0.91%   |
| 4     | 2         | 0.23%   |
| 7     | 1         | 0.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 209       | 40.9%   |
| Chipcard                 | 103       | 20.16%  |
| Graphics card            | 65        | 12.72%  |
| Net/wireless             | 37        | 7.24%   |
| Multimedia controller    | 30        | 5.87%   |
| Camera                   | 17        | 3.33%   |
| Bluetooth                | 15        | 2.94%   |
| Communication controller | 13        | 2.54%   |
| Sound                    | 5         | 0.98%   |
| Net/ethernet             | 4         | 0.78%   |
| Card reader              | 4         | 0.78%   |
| Storage                  | 2         | 0.39%   |
| Modem                    | 2         | 0.39%   |
| Flash memory             | 2         | 0.39%   |
| Storage/nvme             | 1         | 0.2%    |
| Storage/ide              | 1         | 0.2%    |
| Storage/ata              | 1         | 0.2%    |

