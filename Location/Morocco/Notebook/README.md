Linux in Morocco - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Morocco.

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

Total: 228

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [451acdb910](https://linux-hardware.org/?probe=451acdb910) | Oct 31, 2022 |
| HP            | 15                          | [c356a2b0cd](https://linux-hardware.org/?probe=c356a2b0cd) | Oct 30, 2022 |
| HP            | 15                          | [34e1ac4cbe](https://linux-hardware.org/?probe=34e1ac4cbe) | Oct 30, 2022 |
| HP            | EliteBook Folio 1040 G1     | [81df2d786a](https://linux-hardware.org/?probe=81df2d786a) | Oct 15, 2022 |
| Dell          | Latitude E4310              | [318726cca9](https://linux-hardware.org/?probe=318726cca9) | Oct 14, 2022 |
| Casper        | EXCALIBUR G770              | [7961a3ca3e](https://linux-hardware.org/?probe=7961a3ca3e) | Oct 14, 2022 |
| eMachines     | eME528                      | [502802d50d](https://linux-hardware.org/?probe=502802d50d) | Oct 13, 2022 |
| Apple         | MacBookPro10,2              | [379590d053](https://linux-hardware.org/?probe=379590d053) | Oct 09, 2022 |
| HP            | ProBook 650 G1              | [e31d2052e5](https://linux-hardware.org/?probe=e31d2052e5) | Oct 06, 2022 |
| HP            | ProBook 650 G1              | [1bcfb0642f](https://linux-hardware.org/?probe=1bcfb0642f) | Oct 06, 2022 |
| Unknown       | 1.0                         | [f5b0e6a742](https://linux-hardware.org/?probe=f5b0e6a742) | Sep 24, 2022 |
| ASUSTek       | X555LD                      | [08793f9065](https://linux-hardware.org/?probe=08793f9065) | Sep 24, 2022 |
| HP            | EliteBook 840 G5            | [eb488dae73](https://linux-hardware.org/?probe=eb488dae73) | Sep 17, 2022 |
| HP            | EliteBook 840 G5            | [eb406c0e81](https://linux-hardware.org/?probe=eb406c0e81) | Sep 15, 2022 |
| HP            | EliteBook 840 G5            | [6b6e4efdfc](https://linux-hardware.org/?probe=6b6e4efdfc) | Sep 13, 2022 |
| HP            | EliteBook 840 G5            | [4083f9d2c9](https://linux-hardware.org/?probe=4083f9d2c9) | Sep 11, 2022 |
| HP            | EliteBook 840 G5            | [bd15d55792](https://linux-hardware.org/?probe=bd15d55792) | Sep 07, 2022 |
| Dell          | Latitude 5490               | [a3f76e546f](https://linux-hardware.org/?probe=a3f76e546f) | Sep 01, 2022 |
| ASUSTek       | K72Jk                       | [d456f7083c](https://linux-hardware.org/?probe=d456f7083c) | Aug 26, 2022 |
| HP            | Compaq 15                   | [c2bdac6148](https://linux-hardware.org/?probe=c2bdac6148) | Aug 21, 2022 |
| HP            | ProBook 450 G7              | [c636c0401e](https://linux-hardware.org/?probe=c636c0401e) | Aug 18, 2022 |
| Dell          | Latitude E5500              | [5d04270674](https://linux-hardware.org/?probe=5d04270674) | Aug 08, 2022 |
| Acer          | Aspire ES1-523              | [d14f053671](https://linux-hardware.org/?probe=d14f053671) | Aug 01, 2022 |
| Lenovo        | S21e-20 80M4                | [bec71c2353](https://linux-hardware.org/?probe=bec71c2353) | Jul 27, 2022 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | [02dd3c2357](https://linux-hardware.org/?probe=02dd3c2357) | Jul 21, 2022 |
| Dell          | Latitude D620               | [70be0d553e](https://linux-hardware.org/?probe=70be0d553e) | Jul 08, 2022 |
| HP            | Laptop 15-dw3xxx            | [44b541373b](https://linux-hardware.org/?probe=44b541373b) | Jul 08, 2022 |
| Dell          | Latitude E6420              | [ede3298bf4](https://linux-hardware.org/?probe=ede3298bf4) | Jul 02, 2022 |
| HP            | ZBook 15 G3                 | [8c6f371222](https://linux-hardware.org/?probe=8c6f371222) | Jun 19, 2022 |
| HP            | Laptop 15-ra0xx             | [947ca74beb](https://linux-hardware.org/?probe=947ca74beb) | Jun 16, 2022 |
| HP            | Laptop 15-ra0xx             | [70ed4ebad8](https://linux-hardware.org/?probe=70ed4ebad8) | Jun 16, 2022 |
| Lenovo        | ThinkPad T430 2349BS7       | [2369e183ec](https://linux-hardware.org/?probe=2369e183ec) | May 30, 2022 |
| eMachines     | eM350                       | [2573854a09](https://linux-hardware.org/?probe=2573854a09) | May 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [ae7670331c](https://linux-hardware.org/?probe=ae7670331c) | May 22, 2022 |
| Gigabyte      | AERO 15 KC                  | [5ebc19bd4c](https://linux-hardware.org/?probe=5ebc19bd4c) | May 18, 2022 |
| HP            | Laptop 17-cn0xxx            | [39bb2b41e5](https://linux-hardware.org/?probe=39bb2b41e5) | May 18, 2022 |
| HP            | Laptop 15s-eq2xxx           | [427af3e3a0](https://linux-hardware.org/?probe=427af3e3a0) | May 09, 2022 |
| HP            | Laptop 15-dw3xxx            | [7d4d1cb642](https://linux-hardware.org/?probe=7d4d1cb642) | May 06, 2022 |
| Dell          | Latitude E5440              | [556fccb6d3](https://linux-hardware.org/?probe=556fccb6d3) | May 06, 2022 |
| Packard Be... | EasyNote TS44HR             | [2eff4001dc](https://linux-hardware.org/?probe=2eff4001dc) | May 06, 2022 |
| HP            | Laptop 15-dw3xxx            | [889f1cba36](https://linux-hardware.org/?probe=889f1cba36) | Apr 30, 2022 |
| Toshiba       | Satellite C660              | [f4403056c8](https://linux-hardware.org/?probe=f4403056c8) | Apr 30, 2022 |
| HP            | Pavilion g6                 | [b79730a7af](https://linux-hardware.org/?probe=b79730a7af) | Apr 27, 2022 |
| Lenovo        | ThinkPad T460 20FN002SUS    | [0fad5f6cd2](https://linux-hardware.org/?probe=0fad5f6cd2) | Apr 21, 2022 |
| HP            | Presario C500 (GF852EA#A... | [b14e9c5694](https://linux-hardware.org/?probe=b14e9c5694) | Apr 08, 2022 |
| TrekStor      | Surfbook W2                 | [52eb1e4ce9](https://linux-hardware.org/?probe=52eb1e4ce9) | Apr 06, 2022 |
| HP            | Notebook                    | [313ca81d16](https://linux-hardware.org/?probe=313ca81d16) | Mar 27, 2022 |
| HP            | 250 G5 Notebook PC          | [24664b0486](https://linux-hardware.org/?probe=24664b0486) | Mar 25, 2022 |
| HP            | 250 G5 Notebook PC          | [1cb13706a4](https://linux-hardware.org/?probe=1cb13706a4) | Mar 25, 2022 |
| Dell          | Vostro 1015                 | [5eac01f806](https://linux-hardware.org/?probe=5eac01f806) | Mar 25, 2022 |
| Dell          | Vostro 1015                 | [ce0fa4ee36](https://linux-hardware.org/?probe=ce0fa4ee36) | Mar 25, 2022 |
| Dell          | Latitude E5440              | [6b871a160e](https://linux-hardware.org/?probe=6b871a160e) | Mar 22, 2022 |
| Dell          | Latitude E5440              | [bd5621d6e2](https://linux-hardware.org/?probe=bd5621d6e2) | Mar 21, 2022 |
| HP            | ProBook 440 G5              | [39d48e6d79](https://linux-hardware.org/?probe=39d48e6d79) | Feb 28, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [fc6097a447](https://linux-hardware.org/?probe=fc6097a447) | Feb 23, 2022 |
| Dell          | Inspiron 5558               | [6888384b59](https://linux-hardware.org/?probe=6888384b59) | Feb 21, 2022 |
| ASUSTek       | X751LD                      | [074c993361](https://linux-hardware.org/?probe=074c993361) | Feb 19, 2022 |
| Dell          | Latitude E6520              | [f921803f50](https://linux-hardware.org/?probe=f921803f50) | Feb 16, 2022 |
| HP            | EliteBook 8440p             | [ae8afcd09f](https://linux-hardware.org/?probe=ae8afcd09f) | Feb 13, 2022 |
| HP            | ProBook 440 G5              | [4769ae7351](https://linux-hardware.org/?probe=4769ae7351) | Feb 12, 2022 |
| Dell          | Precision M4800             | [8f91ff2d57](https://linux-hardware.org/?probe=8f91ff2d57) | Jan 29, 2022 |
| Dell          | Latitude E6520              | [ee96960cec](https://linux-hardware.org/?probe=ee96960cec) | Jan 25, 2022 |
| ASUSTek       | X540LA                      | [a24d99bf3b](https://linux-hardware.org/?probe=a24d99bf3b) | Jan 24, 2022 |
| Clevo         | W24/250CU                   | [64c6f06849](https://linux-hardware.org/?probe=64c6f06849) | Jan 22, 2022 |
| Google        | Banon                       | [3e792337e2](https://linux-hardware.org/?probe=3e792337e2) | Jan 21, 2022 |
| Google        | Banon                       | [c4cfb244b1](https://linux-hardware.org/?probe=c4cfb244b1) | Jan 21, 2022 |
| HP            | Pavilion g6                 | [099231b0b3](https://linux-hardware.org/?probe=099231b0b3) | Jan 19, 2022 |
| HP            | EliteBook 840 G1            | [8e4f80059d](https://linux-hardware.org/?probe=8e4f80059d) | Jan 14, 2022 |
| Lenovo        | ThinkPad P50 20EQS6J100     | [f366de3acf](https://linux-hardware.org/?probe=f366de3acf) | Jan 03, 2022 |
| Dell          | Precision 5560              | [04cb5954e9](https://linux-hardware.org/?probe=04cb5954e9) | Dec 31, 2021 |
| Timi          | TM1701                      | [ce3374e321](https://linux-hardware.org/?probe=ce3374e321) | Dec 23, 2021 |
| Acer          | Aspire One 522              | [7f495fc85b](https://linux-hardware.org/?probe=7f495fc85b) | Dec 21, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [331d419175](https://linux-hardware.org/?probe=331d419175) | Dec 06, 2021 |
| HP            | EliteBook 8460p             | [97aec623b3](https://linux-hardware.org/?probe=97aec623b3) | Dec 04, 2021 |
| ASUSTek       | K72Jr                       | [518ee0b884](https://linux-hardware.org/?probe=518ee0b884) | Nov 30, 2021 |
| ASUSTek       | K72Jr                       | [405b87f8bf](https://linux-hardware.org/?probe=405b87f8bf) | Nov 29, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3DD1... | [816aaebc79](https://linux-hardware.org/?probe=816aaebc79) | Nov 27, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3DD1... | [162c76040f](https://linux-hardware.org/?probe=162c76040f) | Nov 27, 2021 |
| Lenovo        | ThinkPad X13 Gen 2i 20WK... | [7b9f86430d](https://linux-hardware.org/?probe=7b9f86430d) | Nov 25, 2021 |
| Lenovo        | ThinkPad X13 Gen 2i 20WK... | [c5aa70cf8a](https://linux-hardware.org/?probe=c5aa70cf8a) | Nov 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [73b27d5257](https://linux-hardware.org/?probe=73b27d5257) | Nov 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [915ddf82b5](https://linux-hardware.org/?probe=915ddf82b5) | Nov 23, 2021 |
| HP            | EliteBook 8530w             | [e3a38e431e](https://linux-hardware.org/?probe=e3a38e431e) | Nov 23, 2021 |
| HP            | ZBook 15                    | [6aca3076ac](https://linux-hardware.org/?probe=6aca3076ac) | Nov 22, 2021 |
| HP            | 15                          | [e82411639f](https://linux-hardware.org/?probe=e82411639f) | Nov 20, 2021 |
| Toshiba       | Satellite L50-A-1EL         | [40fff0be70](https://linux-hardware.org/?probe=40fff0be70) | Nov 19, 2021 |
| Apple         | MacBookPro13,3              | [e80b600640](https://linux-hardware.org/?probe=e80b600640) | Nov 12, 2021 |
| HP            | Laptop 15-dw3xxx            | [966b61331a](https://linux-hardware.org/?probe=966b61331a) | Nov 05, 2021 |
| HP            | Laptop 15-dw3xxx            | [e1c9be9f1d](https://linux-hardware.org/?probe=e1c9be9f1d) | Nov 05, 2021 |
| HP            | Pavilion Power Laptop 15... | [c1f75f6249](https://linux-hardware.org/?probe=c1f75f6249) | Oct 27, 2021 |
| ASUSTek       | X540LA                      | [c947e5b1ea](https://linux-hardware.org/?probe=c947e5b1ea) | Oct 26, 2021 |
| HP            | Laptop 15-da0xxx            | [2de5c74bc0](https://linux-hardware.org/?probe=2de5c74bc0) | Oct 23, 2021 |
| HP            | 250 I3-5005U 15.6           | [94c7602d80](https://linux-hardware.org/?probe=94c7602d80) | Oct 20, 2021 |
| Sony          | VPCEH1L8E                   | [11ef4d4baf](https://linux-hardware.org/?probe=11ef4d4baf) | Oct 19, 2021 |
| Sony          | SVE14122CAW                 | [7e20d79b1d](https://linux-hardware.org/?probe=7e20d79b1d) | Oct 16, 2021 |
| Razer         | Blade Pro 17 (2019)         | [c0fc32d290](https://linux-hardware.org/?probe=c0fc32d290) | Oct 09, 2021 |
| Dell          | Latitude E5570              | [bfc3702626](https://linux-hardware.org/?probe=bfc3702626) | Oct 04, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | [c5f4555ed5](https://linux-hardware.org/?probe=c5f4555ed5) | Sep 29, 2021 |
| Dell          | Latitude E5570              | [b4f22d5062](https://linux-hardware.org/?probe=b4f22d5062) | Sep 27, 2021 |
| Dell          | Latitude E5570              | [42c88d1bb8](https://linux-hardware.org/?probe=42c88d1bb8) | Sep 27, 2021 |
| HP            | EliteBook 8530w             | [37a7444281](https://linux-hardware.org/?probe=37a7444281) | Sep 25, 2021 |
| HP            | EliteBook 8530w             | [326645a221](https://linux-hardware.org/?probe=326645a221) | Sep 25, 2021 |
| Dell          | XPS 13 9350                 | [b01438543e](https://linux-hardware.org/?probe=b01438543e) | Sep 20, 2021 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [554c02e687](https://linux-hardware.org/?probe=554c02e687) | Sep 14, 2021 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [e2202296c9](https://linux-hardware.org/?probe=e2202296c9) | Sep 13, 2021 |
| HP            | Pavilion Power Laptop 15... | [d63a5c07e1](https://linux-hardware.org/?probe=d63a5c07e1) | Aug 28, 2021 |
| HP            | Pavilion Power Laptop 15... | [78316d40ea](https://linux-hardware.org/?probe=78316d40ea) | Aug 28, 2021 |
| Lenovo        | ThinkPad X250 20CLS4WV08    | [2c09cdd5bd](https://linux-hardware.org/?probe=2c09cdd5bd) | Aug 12, 2021 |
| HP            | 15                          | [80ce139934](https://linux-hardware.org/?probe=80ce139934) | Aug 06, 2021 |
| HP            | 15                          | [24c674140c](https://linux-hardware.org/?probe=24c674140c) | Aug 05, 2021 |
| HP            | Laptop 15-dw3xxx            | [ea05f5d624](https://linux-hardware.org/?probe=ea05f5d624) | Jul 21, 2021 |
| Unknown       | 1.0                         | [d049c76d58](https://linux-hardware.org/?probe=d049c76d58) | Jul 08, 2021 |
| Unknown       | 1.0                         | [deb4346da8](https://linux-hardware.org/?probe=deb4346da8) | Jul 08, 2021 |
| Unknown       | 1.0                         | [967654bdb6](https://linux-hardware.org/?probe=967654bdb6) | Jul 04, 2021 |
| Unknown       | 1.0                         | [36977bacbe](https://linux-hardware.org/?probe=36977bacbe) | Jul 03, 2021 |
| HP            | Pavilion Power Laptop 15... | [19666df61f](https://linux-hardware.org/?probe=19666df61f) | Jun 26, 2021 |
| HP            | Pavilion Power Laptop 15... | [df836c85c5](https://linux-hardware.org/?probe=df836c85c5) | Jun 26, 2021 |
| HP            | EliteBook 840 G3            | [dd3d9ede87](https://linux-hardware.org/?probe=dd3d9ede87) | Jun 20, 2021 |
| Unknown       | Unknown                     | [80c0612f78](https://linux-hardware.org/?probe=80c0612f78) | Jun 04, 2021 |
| Unknown       | Unknown                     | [9bac89aecf](https://linux-hardware.org/?probe=9bac89aecf) | Jun 04, 2021 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | [3890d7877d](https://linux-hardware.org/?probe=3890d7877d) | May 06, 2021 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | [44810c2cc1](https://linux-hardware.org/?probe=44810c2cc1) | May 06, 2021 |
| Lenovo        | ThinkPad X220 4291V5K       | [c0b9d7bd52](https://linux-hardware.org/?probe=c0b9d7bd52) | Apr 26, 2021 |
| Lenovo        | ThinkPad X220 4291V5K       | [4ec1325f12](https://linux-hardware.org/?probe=4ec1325f12) | Apr 26, 2021 |
| HP            | EliteBook 8460p             | [cf8b627aa4](https://linux-hardware.org/?probe=cf8b627aa4) | Apr 11, 2021 |
| HP            | EliteBook 8460p             | [bd04b1367f](https://linux-hardware.org/?probe=bd04b1367f) | Apr 11, 2021 |
| HP            | EliteBook 840 G2            | [522eb62b1a](https://linux-hardware.org/?probe=522eb62b1a) | Apr 03, 2021 |
| HP            | EliteBook 840 G2            | [e9df8836cf](https://linux-hardware.org/?probe=e9df8836cf) | Apr 03, 2021 |
| HP            | EliteBook 2540p             | [46c15e3b14](https://linux-hardware.org/?probe=46c15e3b14) | Apr 01, 2021 |
| HP            | EliteBook 840 G2            | [e1023ad432](https://linux-hardware.org/?probe=e1023ad432) | Mar 31, 2021 |
| HP            | EliteBook 840 G2            | [5c9803ca79](https://linux-hardware.org/?probe=5c9803ca79) | Mar 31, 2021 |
| HP            | Pavilion Laptop 15-ck0xx    | [f973f0f31c](https://linux-hardware.org/?probe=f973f0f31c) | Mar 23, 2021 |
| Dell          | Latitude 5580               | [9fd0e8f6b5](https://linux-hardware.org/?probe=9fd0e8f6b5) | Mar 22, 2021 |
| Lenovo        | ThinkPad X220 4291B66       | [411fb65be7](https://linux-hardware.org/?probe=411fb65be7) | Mar 21, 2021 |
| HP            | Notebook                    | [fbc522f5e7](https://linux-hardware.org/?probe=fbc522f5e7) | Feb 24, 2021 |
| HP            | Pavilion Sleekbook 15       | [aeb3111a93](https://linux-hardware.org/?probe=aeb3111a93) | Feb 20, 2021 |
| HP            | EliteBook 840 G2            | [1ffab0446e](https://linux-hardware.org/?probe=1ffab0446e) | Feb 17, 2021 |
| Lenovo        | ThinkPad T460 20FN002SUS    | [2ba0a379e8](https://linux-hardware.org/?probe=2ba0a379e8) | Feb 16, 2021 |
| Dell          | Latitude 3480               | [533356cb56](https://linux-hardware.org/?probe=533356cb56) | Feb 15, 2021 |
| HP            | Pavilion dv7                | [17dcac4931](https://linux-hardware.org/?probe=17dcac4931) | Feb 10, 2021 |
| GPD           | MicroPC                     | [ed2233e6ce](https://linux-hardware.org/?probe=ed2233e6ce) | Feb 08, 2021 |
| Acer          | AO722                       | [24cb20b715](https://linux-hardware.org/?probe=24cb20b715) | Feb 04, 2021 |
| HP            | EliteBook 840 G2            | [8da09ed292](https://linux-hardware.org/?probe=8da09ed292) | Feb 04, 2021 |
| Lenovo        | ThinkPad E590 20NB002AMB    | [e45b210ee6](https://linux-hardware.org/?probe=e45b210ee6) | Feb 01, 2021 |
| Lenovo        | ThinkPad T460 20FN002SUS    | [6c9654a854](https://linux-hardware.org/?probe=6c9654a854) | Jan 25, 2021 |
| Apple         | MacBook5,2                  | [512f5b5bdc](https://linux-hardware.org/?probe=512f5b5bdc) | Jan 18, 2021 |
| HP            | Pavilion dv7                | [bc33dda5d6](https://linux-hardware.org/?probe=bc33dda5d6) | Jan 09, 2021 |
| HP            | 650                         | [65c5445c17](https://linux-hardware.org/?probe=65c5445c17) | Jan 08, 2021 |
| Sony          | VGN-FW11L                   | [e99fe042af](https://linux-hardware.org/?probe=e99fe042af) | Jan 06, 2021 |
| HP            | 255 G7 Notebook PC          | [493c807f09](https://linux-hardware.org/?probe=493c807f09) | Jan 06, 2021 |
| Lenovo        | ThinkPad E570 20H50078IX    | [9162d07863](https://linux-hardware.org/?probe=9162d07863) | Dec 31, 2020 |
| Lenovo        | ThinkPad E570 20H50078IX    | [f1f07aecd0](https://linux-hardware.org/?probe=f1f07aecd0) | Dec 31, 2020 |
| Dell          | Latitude E6440              | [cec6c1fd51](https://linux-hardware.org/?probe=cec6c1fd51) | Dec 25, 2020 |
| HP            | 650                         | [ff87d07205](https://linux-hardware.org/?probe=ff87d07205) | Dec 21, 2020 |
| Packard Be... | EasyNote TS11HR             | [9c31cf187f](https://linux-hardware.org/?probe=9c31cf187f) | Dec 17, 2020 |
| Timi          | TM1701                      | [bc63393a91](https://linux-hardware.org/?probe=bc63393a91) | Dec 13, 2020 |
| Lenovo        | ThinkPad T480s 20L8S3P30... | [1a37278a5b](https://linux-hardware.org/?probe=1a37278a5b) | Dec 13, 2020 |
| HP            | EliteBook 8560w             | [d546d8c598](https://linux-hardware.org/?probe=d546d8c598) | Nov 25, 2020 |
| HP            | EliteBook 8560w             | [9bb315e3ac](https://linux-hardware.org/?probe=9bb315e3ac) | Nov 25, 2020 |
| Dell          | Latitude E6440              | [6739c087eb](https://linux-hardware.org/?probe=6739c087eb) | Nov 20, 2020 |
| TUXEDO        | N13xWU                      | [b72558f93c](https://linux-hardware.org/?probe=b72558f93c) | Nov 19, 2020 |
| TUXEDO        | N13xWU                      | [e6a667e32c](https://linux-hardware.org/?probe=e6a667e32c) | Nov 08, 2020 |
| TUXEDO        | N13xWU                      | [b4cd820410](https://linux-hardware.org/?probe=b4cd820410) | Nov 08, 2020 |
| Lenovo        | ThinkPad X280 20KF001KFR    | [bb66d36c3e](https://linux-hardware.org/?probe=bb66d36c3e) | Oct 23, 2020 |
| ASUSTek       | X555LAB                     | [d4755cc80a](https://linux-hardware.org/?probe=d4755cc80a) | Oct 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [ef4b4ee1be](https://linux-hardware.org/?probe=ef4b4ee1be) | Oct 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [c1d3bd539a](https://linux-hardware.org/?probe=c1d3bd539a) | Oct 09, 2020 |
| HP            | ProBook 450 G0              | [a12e9900c0](https://linux-hardware.org/?probe=a12e9900c0) | Oct 07, 2020 |
| HP            | ProBook 450 G0              | [822c9a0ece](https://linux-hardware.org/?probe=822c9a0ece) | Oct 07, 2020 |
| HP            | Compaq nc6220 (PL814AV)     | [7f042faa64](https://linux-hardware.org/?probe=7f042faa64) | Oct 04, 2020 |
| HP            | EliteBook 8440p             | [a5438c06dc](https://linux-hardware.org/?probe=a5438c06dc) | Oct 02, 2020 |
| HP            | ProBook 6470b               | [0c6e7c5d06](https://linux-hardware.org/?probe=0c6e7c5d06) | Sep 30, 2020 |
| HP            | ProBook 6470b               | [3ab44ecc2c](https://linux-hardware.org/?probe=3ab44ecc2c) | Sep 20, 2020 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | [e36d2e46a2](https://linux-hardware.org/?probe=e36d2e46a2) | Sep 16, 2020 |
| Lenovo        | ThinkPad X280 20KF001KFR    | [09ba7a078c](https://linux-hardware.org/?probe=09ba7a078c) | Sep 06, 2020 |
| Toshiba       | Satellite L750              | [1c9467e7ff](https://linux-hardware.org/?probe=1c9467e7ff) | Aug 31, 2020 |
| Dell          | Latitude E5270              | [b9e93e40f1](https://linux-hardware.org/?probe=b9e93e40f1) | Aug 26, 2020 |
| Toshiba       | Satellite C855-2CF          | [00048c3fd7](https://linux-hardware.org/?probe=00048c3fd7) | Aug 26, 2020 |
| HP            | ProBook 650 G1              | [134ae0f98f](https://linux-hardware.org/?probe=134ae0f98f) | Aug 24, 2020 |
| Lenovo        | ThinkPad X280 20KF001KFR    | [47a6af7e14](https://linux-hardware.org/?probe=47a6af7e14) | Aug 23, 2020 |
| HP            | Laptop 15-da0xxx            | [b51e82eb8b](https://linux-hardware.org/?probe=b51e82eb8b) | Aug 08, 2020 |
| HP            | ProBook 440 G7              | [b2d1e5272e](https://linux-hardware.org/?probe=b2d1e5272e) | Aug 07, 2020 |
| Lenovo        | Z70-80 80FG                 | [8f0c5d78da](https://linux-hardware.org/?probe=8f0c5d78da) | Jul 29, 2020 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [c4b91061bd](https://linux-hardware.org/?probe=c4b91061bd) | Jun 24, 2020 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [1d9441c4cb](https://linux-hardware.org/?probe=1d9441c4cb) | Jun 24, 2020 |
| HP            | EliteBook 840 G2            | [8f31cacb03](https://linux-hardware.org/?probe=8f31cacb03) | Jun 15, 2020 |
| Dell          | Latitude E6410              | [63006c892d](https://linux-hardware.org/?probe=63006c892d) | Jun 12, 2020 |
| Dell          | Latitude E6540              | [0820a41e4a](https://linux-hardware.org/?probe=0820a41e4a) | Jun 03, 2020 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [d4a0f7593f](https://linux-hardware.org/?probe=d4a0f7593f) | May 30, 2020 |
| Packard Be... | EasyNote TK85               | [1ef7f1dccf](https://linux-hardware.org/?probe=1ef7f1dccf) | May 24, 2020 |
| HP            | Unknown                     | [83216ab6f8](https://linux-hardware.org/?probe=83216ab6f8) | May 23, 2020 |
| Dell          | Latitude E5270              | [79c2208ee5](https://linux-hardware.org/?probe=79c2208ee5) | May 16, 2020 |
| HP            | Laptop 15-da0xxx            | [4d933966bb](https://linux-hardware.org/?probe=4d933966bb) | May 16, 2020 |
| HP            | ZBook 15                    | [7fdf5ffeb8](https://linux-hardware.org/?probe=7fdf5ffeb8) | May 10, 2020 |
| Lenovo        | G50-70 20351                | [fea9f24d5a](https://linux-hardware.org/?probe=fea9f24d5a) | Apr 27, 2020 |
| Lenovo        | G50-70 20351                | [f6609c3613](https://linux-hardware.org/?probe=f6609c3613) | Apr 27, 2020 |
| ASUSTek       | UX31A                       | [2ce7c49619](https://linux-hardware.org/?probe=2ce7c49619) | Apr 16, 2020 |
| ASUSTek       | X542UAR                     | [1597291755](https://linux-hardware.org/?probe=1597291755) | Apr 03, 2020 |
| HP            | 250 G3                      | [e92714c5e6](https://linux-hardware.org/?probe=e92714c5e6) | Mar 18, 2020 |
| Dell          | Latitude E6510              | [bc7b29779f](https://linux-hardware.org/?probe=bc7b29779f) | Mar 08, 2020 |
| Packard Be... | EasyNote TK85               | [bf3776568a](https://linux-hardware.org/?probe=bf3776568a) | Feb 23, 2020 |
| HP            | EliteBook 8440p             | [2bc65b9511](https://linux-hardware.org/?probe=2bc65b9511) | Feb 22, 2020 |
| HP            | EliteBook 8440p             | [4ef298fd63](https://linux-hardware.org/?probe=4ef298fd63) | Feb 22, 2020 |
| HP            | Pavilion Laptop 15-cs2xx... | [98c2d41201](https://linux-hardware.org/?probe=98c2d41201) | Feb 21, 2020 |
| HP            | Pavilion Laptop 15-cs2xx... | [6b512c0e61](https://linux-hardware.org/?probe=6b512c0e61) | Feb 21, 2020 |
| Dell          | Latitude E5520              | [2994cbb1d2](https://linux-hardware.org/?probe=2994cbb1d2) | Feb 21, 2020 |
| Dell          | Inspiron 3521               | [35973fcba8](https://linux-hardware.org/?probe=35973fcba8) | Jan 01, 2020 |
| Medion        | P7615                       | [1402e4bf25](https://linux-hardware.org/?probe=1402e4bf25) | Dec 29, 2019 |
| Toshiba       | Satellite Pro C650          | [984a530b85](https://linux-hardware.org/?probe=984a530b85) | Dec 19, 2019 |
| Medion        | P7615                       | [56fdcbb995](https://linux-hardware.org/?probe=56fdcbb995) | Nov 25, 2019 |
| Medion        | P7615                       | [150034113d](https://linux-hardware.org/?probe=150034113d) | Nov 25, 2019 |
| Acer          | Aspire 7736                 | [64727a44db](https://linux-hardware.org/?probe=64727a44db) | Nov 24, 2019 |
| Acer          | Aspire 7736                 | [3415167cef](https://linux-hardware.org/?probe=3415167cef) | Nov 23, 2019 |
| Acer          | Aspire ES1-523              | [74c8472d6f](https://linux-hardware.org/?probe=74c8472d6f) | Nov 12, 2019 |
| ASUSTek       | X200MA                      | [860c71f889](https://linux-hardware.org/?probe=860c71f889) | Nov 10, 2019 |
| Acer          | Calpella                    | [6ff918b898](https://linux-hardware.org/?probe=6ff918b898) | Oct 29, 2019 |
| Dell          | Latitude 3590               | [8e1927b00a](https://linux-hardware.org/?probe=8e1927b00a) | Sep 22, 2019 |
| Lenovo        | ThinkPad T440 20B7S2MF01    | [4dc662ddb5](https://linux-hardware.org/?probe=4dc662ddb5) | Sep 04, 2019 |
| HP            | Laptop 15-bs0xx             | [73e92501d3](https://linux-hardware.org/?probe=73e92501d3) | Aug 29, 2019 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [d9903b4749](https://linux-hardware.org/?probe=d9903b4749) | May 14, 2019 |
| Toshiba       | Satellite L50-A-1DG         | [b0e44b3093](https://linux-hardware.org/?probe=b0e44b3093) | Apr 13, 2019 |
| Toshiba       | Satellite L50-A-1DG         | [1103235a87](https://linux-hardware.org/?probe=1103235a87) | Apr 13, 2019 |
| Acer          | Aspire E5-575               | [e7e29b676f](https://linux-hardware.org/?probe=e7e29b676f) | Mar 16, 2019 |
| Acer          | Aspire E5-575               | [4d2d0aa109](https://linux-hardware.org/?probe=4d2d0aa109) | Feb 20, 2019 |
| ASUSTek       | F5VL                        | [8c665a5eb1](https://linux-hardware.org/?probe=8c665a5eb1) | Feb 07, 2019 |
| ASUSTek       | F5VL                        | [d54a4a5d26](https://linux-hardware.org/?probe=d54a4a5d26) | Dec 12, 2018 |
| Lenovo        | ThinkPad X240 20AMA09VFR    | [8e1e3b46c5](https://linux-hardware.org/?probe=8e1e3b46c5) | Nov 26, 2018 |
| Lenovo        | ThinkPad X240 20AMA09VFR    | [b14f27a474](https://linux-hardware.org/?probe=b14f27a474) | Nov 26, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 33        | 20.12%  |
| Ubuntu 18.04       | 12        | 7.32%   |
| KDE neon 20.04     | 10        | 6.1%    |
| Debian 11          | 7         | 4.27%   |
| OpenMandriva 4.2   | 6         | 3.66%   |
| Linux Mint 20.2    | 6         | 3.66%   |
| Ubuntu 22.04       | 5         | 3.05%   |
| OpenMandriva 4.3   | 5         | 3.05%   |
| Zorin 16           | 4         | 2.44%   |
| Ubuntu 20.10       | 4         | 2.44%   |
| Ubuntu 19.10       | 4         | 2.44%   |
| Linux Mint 20.3    | 4         | 2.44%   |
| Arch               | 4         | 2.44%   |
| Ubuntu Unity 16.04 | 3         | 1.83%   |
| Pop!_OS 22.04      | 3         | 1.83%   |
| Manjaro            | 3         | 1.83%   |
| ArcoLinux Rolling  | 3         | 1.83%   |
| Xubuntu 20.04      | 2         | 1.22%   |
| Void Linux         | 2         | 1.22%   |
| Ubuntu 21.10       | 2         | 1.22%   |
| Ubuntu 21.04       | 2         | 1.22%   |
| Pop!_OS 21.10      | 2         | 1.22%   |
| Linux Mint 19.3    | 2         | 1.22%   |
| Kali 2019.4        | 2         | 1.22%   |
| Fedora 36          | 2         | 1.22%   |
| Zorin 15           | 1         | 0.61%   |
| Xero Rolling       | 1         | 0.61%   |
| Ubuntu Unity 20.04 | 1         | 0.61%   |
| Ubuntu MATE 20.04  | 1         | 0.61%   |
| Ubuntu 19.04       | 1         | 0.61%   |
| Ubuntu 16.04       | 1         | 0.61%   |
| Ubuntu             | 1         | 0.61%   |
| RHEL 8             | 1         | 0.61%   |
| Pop!_OS 20.10      | 1         | 0.61%   |
| Parrot 5.0         | 1         | 0.61%   |
| openSUSE Leap-15.2 | 1         | 0.61%   |
| Nobara 36          | 1         | 0.61%   |
| Manjaro 21.3.7     | 1         | 0.61%   |
| Manjaro 21.1.6     | 1         | 0.61%   |
| Manjaro 20.1       | 1         | 0.61%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 59        | 37.34%  |
| Linux Mint   | 15        | 9.49%   |
| OpenMandriva | 11        | 6.96%   |
| KDE neon     | 10        | 6.33%   |
| Debian       | 8         | 5.06%   |
| Pop!_OS      | 6         | 3.8%    |
| Manjaro      | 6         | 3.8%    |
| Zorin        | 5         | 3.16%   |
| Kali         | 5         | 3.16%   |
| Ubuntu Unity | 4         | 2.53%   |
| Fedora       | 4         | 2.53%   |
| Arch         | 4         | 2.53%   |
| Endless      | 3         | 1.9%    |
| ArcoLinux    | 3         | 1.9%    |
| Xubuntu      | 2         | 1.27%   |
| Void Linux   | 2         | 1.27%   |
| Elementary   | 2         | 1.27%   |
| Xero         | 1         | 0.63%   |
| Ubuntu MATE  | 1         | 0.63%   |
| RHEL         | 1         | 0.63%   |
| Parrot       | 1         | 0.63%   |
| openSUSE     | 1         | 0.63%   |
| Nobara       | 1         | 0.63%   |
| EndeavourOS  | 1         | 0.63%   |
| CentOS       | 1         | 0.63%   |
| BunsenLabs   | 1         | 0.63%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002     | 6         | 3.39%   |
| 5.16.7-desktop-1omv4003      | 5         | 2.82%   |
| 5.13.0-40-generic            | 5         | 2.82%   |
| 5.8.0-43-generic             | 4         | 2.26%   |
| 5.4.0-58-generic             | 4         | 2.26%   |
| 5.4.0-48-generic             | 4         | 2.26%   |
| 5.4.0-42-generic             | 3         | 1.69%   |
| 5.3.0-40-generic             | 3         | 1.69%   |
| 5.17.5-76051705-generic      | 3         | 1.69%   |
| 5.11.0-37-generic            | 3         | 1.69%   |
| 5.8.0-48-generic             | 2         | 1.13%   |
| 5.8.0-38-generic             | 2         | 1.13%   |
| 5.8.0-33-generic             | 2         | 1.13%   |
| 5.4.0-96-generic             | 2         | 1.13%   |
| 5.4.0-88-generic             | 2         | 1.13%   |
| 5.4.0-65-generic             | 2         | 1.13%   |
| 5.4.0-37-generic             | 2         | 1.13%   |
| 5.4.0-33-generic             | 2         | 1.13%   |
| 5.4.0-29-generic             | 2         | 1.13%   |
| 5.3.0-kali2-686-pae          | 2         | 1.13%   |
| 5.3.0-51-generic             | 2         | 1.13%   |
| 5.3.0-28-generic             | 2         | 1.13%   |
| 5.18.19_1                    | 2         | 1.13%   |
| 5.15.0-50-generic            | 2         | 1.13%   |
| 5.15.0-46-generic            | 2         | 1.13%   |
| 5.14.14-arch1-1              | 2         | 1.13%   |
| 5.13.0-27-generic            | 2         | 1.13%   |
| 5.13.0-19-generic            | 2         | 1.13%   |
| 5.11.0-46-generic            | 2         | 1.13%   |
| 5.11.0-36-generic            | 2         | 1.13%   |
| 5.0.0-23-generic             | 2         | 1.13%   |
| 5.8.15-201.fc32.x86_64       | 1         | 0.56%   |
| 5.8.1-050801-generic         | 1         | 0.56%   |
| 5.8.0-rc6-3.g007dcf0-default | 1         | 0.56%   |
| 5.8.0-63-generic             | 1         | 0.56%   |
| 5.8.0-55-generic             | 1         | 0.56%   |
| 5.8.0-41-generic             | 1         | 0.56%   |
| 5.8.0-36-generic             | 1         | 0.56%   |
| 5.8.0-34-generic             | 1         | 0.56%   |
| 5.8.0-14-generic             | 1         | 0.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 34        | 20.86%  |
| 5.8.0   | 14        | 8.59%   |
| 5.11.0  | 11        | 6.75%   |
| 5.3.0   | 10        | 6.13%   |
| 5.13.0  | 10        | 6.13%   |
| 4.15.0  | 10        | 6.13%   |
| 5.15.0  | 9         | 5.52%   |
| 5.10.0  | 8         | 4.91%   |
| 5.10.14 | 6         | 3.68%   |
| 5.0.0   | 6         | 3.68%   |
| 5.16.7  | 5         | 3.07%   |
| 5.17.5  | 3         | 1.84%   |
| 4.18.0  | 3         | 1.84%   |
| 5.18.19 | 2         | 1.23%   |
| 5.16.0  | 2         | 1.23%   |
| 5.14.14 | 2         | 1.23%   |
| 4.19.0  | 2         | 1.23%   |
| 5.8.15  | 1         | 0.61%   |
| 5.8.1   | 1         | 0.61%   |
| 5.7.15  | 1         | 0.61%   |
| 5.19.9  | 1         | 0.61%   |
| 5.19.16 | 1         | 0.61%   |
| 5.19.14 | 1         | 0.61%   |
| 5.19.0  | 1         | 0.61%   |
| 5.18.18 | 1         | 0.61%   |
| 5.18.12 | 1         | 0.61%   |
| 5.17.9  | 1         | 0.61%   |
| 5.17.15 | 1         | 0.61%   |
| 5.17.1  | 1         | 0.61%   |
| 5.16.2  | 1         | 0.61%   |
| 5.15.60 | 1         | 0.61%   |
| 5.15.4  | 1         | 0.61%   |
| 5.15.23 | 1         | 0.61%   |
| 5.15.21 | 1         | 0.61%   |
| 5.15.15 | 1         | 0.61%   |
| 5.15.12 | 1         | 0.61%   |
| 5.14.0  | 1         | 0.61%   |
| 5.13.19 | 1         | 0.61%   |
| 5.11.7  | 1         | 0.61%   |
| 5.11.14 | 1         | 0.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 34        | 20.86%  |
| 5.8     | 16        | 9.82%   |
| 5.15    | 15        | 9.2%    |
| 5.10    | 15        | 9.2%    |
| 5.11    | 13        | 7.98%   |
| 5.13    | 11        | 6.75%   |
| 5.3     | 10        | 6.13%   |
| 4.15    | 10        | 6.13%   |
| 5.16    | 8         | 4.91%   |
| 5.17    | 6         | 3.68%   |
| 5.0     | 6         | 3.68%   |
| 5.19    | 4         | 2.45%   |
| 5.18    | 4         | 2.45%   |
| 5.14    | 3         | 1.84%   |
| 4.18    | 3         | 1.84%   |
| 4.19    | 2         | 1.23%   |
| 5.7     | 1         | 0.61%   |
| 4.4     | 1         | 0.61%   |
| 4.13    | 1         | 0.61%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 148       | 95.48%  |
| i686   | 7         | 4.52%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 78        | 49.06%  |
| KDE5            | 26        | 16.35%  |
| Unknown         | 14        | 8.81%   |
| X-Cinnamon      | 11        | 6.92%   |
| XFCE            | 10        | 6.29%   |
| KDE             | 6         | 3.77%   |
| Unity           | 4         | 2.52%   |
| Pantheon        | 2         | 1.26%   |
| MATE            | 2         | 1.26%   |
| Cinnamon        | 2         | 1.26%   |
| xmonad          | 1         | 0.63%   |
| i3              | 1         | 0.63%   |
| GNOME Flashback | 1         | 0.63%   |
| Budgie          | 1         | 0.63%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 129       | 81.13%  |
| Wayland | 22        | 13.84%  |
| Unknown | 7         | 4.4%    |
| Tty     | 1         | 0.63%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 86        | 53.09%  |
| GDM     | 25        | 15.43%  |
| SDDM    | 24        | 14.81%  |
| LightDM | 15        | 9.26%   |
| GDM3    | 9         | 5.56%   |
| TDM     | 3         | 1.85%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 85        | 54.49%  |
| fr_FR   | 42        | 26.92%  |
| Unknown | 12        | 7.69%   |
| en_GB   | 7         | 4.49%   |
| de_DE   | 3         | 1.92%   |
| fr_MA   | 1         | 0.64%   |
| fr_BE   | 1         | 0.64%   |
| es_ES   | 1         | 0.64%   |
| en_AG   | 1         | 0.64%   |
| C       | 1         | 0.64%   |
| ar_MA   | 1         | 0.64%   |
| ar_EG   | 1         | 0.64%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 96        | 61.54%  |
| EFI  | 60        | 38.46%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 130       | 83.87%  |
| Overlay | 13        | 8.39%   |
| Btrfs   | 8         | 5.16%   |
| Xfs     | 2         | 1.29%   |
| Unknown | 2         | 1.29%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 87        | 55.77%  |
| GPT     | 45        | 28.85%  |
| MBR     | 24        | 15.38%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 138       | 89.03%  |
| Yes       | 17        | 10.97%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 104       | 66.67%  |
| Yes       | 52        | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 53        | 34.19%  |
| Lenovo              | 26        | 16.77%  |
| Dell                | 24        | 15.48%  |
| ASUSTek Computer    | 12        | 7.74%   |
| Acer                | 7         | 4.52%   |
| Toshiba             | 6         | 3.87%   |
| Sony                | 3         | 1.94%   |
| Packard Bell        | 3         | 1.94%   |
| Apple               | 3         | 1.94%   |
| Timi                | 2         | 1.29%   |
| Samsung Electronics | 2         | 1.29%   |
| eMachines           | 2         | 1.29%   |
| Unknown             | 2         | 1.29%   |
| TUXEDO              | 1         | 0.65%   |
| TrekStor            | 1         | 0.65%   |
| Razer               | 1         | 0.65%   |
| Medion              | 1         | 0.65%   |
| Mediacom            | 1         | 0.65%   |
| GPD                 | 1         | 0.65%   |
| Google              | 1         | 0.65%   |
| Gigabyte Technology | 1         | 0.65%   |
| Clevo               | 1         | 0.65%   |
| Casper              | 1         | 0.65%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| HP Laptop 15-dw3xxx                        | 3         | 1.94%   |
| HP EliteBook 8440p                         | 3         | 1.94%   |
| HP EliteBook 840 G2                        | 3         | 1.94%   |
| Unknown                                    | 3         | 1.94%   |
| Timi TM1701                                | 2         | 1.29%   |
| Lenovo ThinkBook 15 G2 ITL 20VE            | 2         | 1.29%   |
| Lenovo IdeaPad L3 15IML05 81Y3             | 2         | 1.29%   |
| HP ZBook 15                                | 2         | 1.29%   |
| HP ProBook 650 G1                          | 2         | 1.29%   |
| HP ProBook 6470b                           | 2         | 1.29%   |
| HP Notebook                                | 2         | 1.29%   |
| HP EliteBook 8460p                         | 2         | 1.29%   |
| Dell Latitude E6520                        | 2         | 1.29%   |
| ASUS X540LA                                | 2         | 1.29%   |
| Acer Aspire ES1-523                        | 2         | 1.29%   |
| TUXEDO N13xWU                              | 1         | 0.65%   |
| TrekStor Surfbook W2                       | 1         | 0.65%   |
| Toshiba Satellite Pro C650                 | 1         | 0.65%   |
| Toshiba Satellite L750                     | 1         | 0.65%   |
| Toshiba Satellite L50-A-1EL                | 1         | 0.65%   |
| Toshiba Satellite L50-A-1DG                | 1         | 0.65%   |
| Toshiba Satellite C855-2CF                 | 1         | 0.65%   |
| Toshiba Satellite C660                     | 1         | 0.65%   |
| Sony VPCEH1L8E                             | 1         | 0.65%   |
| Sony VGN-FW11L                             | 1         | 0.65%   |
| Sony SVE14122CAW                           | 1         | 0.65%   |
| Samsung 355V4C/356V4C/3445VC/3545VC        | 1         | 0.65%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 0.65%   |
| Razer Blade Pro 17 (2019)                  | 1         | 0.65%   |
| Packard Bell EasyNote TS44HR               | 1         | 0.65%   |
| Packard Bell EasyNote TS11HR               | 1         | 0.65%   |
| Packard Bell EasyNote TK85                 | 1         | 0.65%   |
| Medion P7615                               | 1         | 0.65%   |
| Mediacom WinPad 11,6 FullHD- WPU11         | 1         | 0.65%   |
| Lenovo Z70-80 80FG                         | 1         | 0.65%   |
| Lenovo ThinkPad X280 20KF001KFR            | 1         | 0.65%   |
| Lenovo ThinkPad X250 20CLS4WV08            | 1         | 0.65%   |
| Lenovo ThinkPad X240 20AMA09VFR            | 1         | 0.65%   |
| Lenovo ThinkPad X220 4291V5K               | 1         | 0.65%   |
| Lenovo ThinkPad X220 4291B66               | 1         | 0.65%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Dell Latitude         | 18        | 11.61%  |
| Lenovo ThinkPad       | 17        | 10.97%  |
| HP EliteBook          | 15        | 9.68%   |
| HP ProBook            | 8         | 5.16%   |
| HP Laptop             | 8         | 5.16%   |
| HP Pavilion           | 7         | 4.52%   |
| Toshiba Satellite     | 6         | 3.87%   |
| Acer Aspire           | 5         | 3.23%   |
| Lenovo IdeaPad        | 4         | 2.58%   |
| Packard Bell EasyNote | 3         | 1.94%   |
| HP ZBook              | 3         | 1.94%   |
| HP 250                | 3         | 1.94%   |
| Unknown               | 3         | 1.94%   |
| Timi TM1701           | 2         | 1.29%   |
| Lenovo ThinkBook      | 2         | 1.29%   |
| HP Notebook           | 2         | 1.29%   |
| HP Compaq             | 2         | 1.29%   |
| Dell Precision        | 2         | 1.29%   |
| Dell Inspiron         | 2         | 1.29%   |
| ASUS X540LA           | 2         | 1.29%   |
| TUXEDO N13xWU         | 1         | 0.65%   |
| TrekStor Surfbook     | 1         | 0.65%   |
| Sony VPCEH1L8E        | 1         | 0.65%   |
| Sony VGN-FW11L        | 1         | 0.65%   |
| Sony SVE14122CAW      | 1         | 0.65%   |
| Samsung 355V4C        | 1         | 0.65%   |
| Samsung 300E4A        | 1         | 0.65%   |
| Razer Blade           | 1         | 0.65%   |
| Medion P7615          | 1         | 0.65%   |
| Mediacom WinPad       | 1         | 0.65%   |
| Lenovo Z70-80         | 1         | 0.65%   |
| Lenovo S21e-20        | 1         | 0.65%   |
| Lenovo G50-70         | 1         | 0.65%   |
| HP Presario           | 1         | 0.65%   |
| HP 650                | 1         | 0.65%   |
| HP 255                | 1         | 0.65%   |
| HP 15                 | 1         | 0.65%   |
| GPD MicroPC           | 1         | 0.65%   |
| Google Banon          | 1         | 0.65%   |
| Gigabyte AERO         | 1         | 0.65%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 18        | 11.61%  |
| 2011 | 18        | 11.61%  |
| 2018 | 14        | 9.03%   |
| 2016 | 14        | 9.03%   |
| 2015 | 14        | 9.03%   |
| 2010 | 14        | 9.03%   |
| 2020 | 10        | 6.45%   |
| 2012 | 10        | 6.45%   |
| 2017 | 9         | 5.81%   |
| 2019 | 8         | 5.16%   |
| 2014 | 8         | 5.16%   |
| 2021 | 6         | 3.87%   |
| 2009 | 5         | 3.23%   |
| 2008 | 3         | 1.94%   |
| 2007 | 2         | 1.29%   |
| 2006 | 1         | 0.65%   |
| 2005 | 1         | 0.65%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 155       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 149       | 94.3%   |
| Enabled  | 9         | 5.7%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 154       | 99.35%  |
| Yes  | 1         | 0.65%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 57        | 36.77%  |
| 3.01-4.0   | 44        | 28.39%  |
| 16.01-24.0 | 17        | 10.97%  |
| 8.01-16.0  | 16        | 10.32%  |
| 1.01-2.0   | 11        | 7.1%    |
| 32.01-64.0 | 3         | 1.94%   |
| 24.01-32.0 | 3         | 1.94%   |
| 2.01-3.0   | 2         | 1.29%   |
| 0.51-1.0   | 2         | 1.29%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 67        | 40.12%  |
| 2.01-3.0  | 56        | 33.53%  |
| 4.01-8.0  | 20        | 11.98%  |
| 3.01-4.0  | 16        | 9.58%   |
| 0.51-1.0  | 7         | 4.19%   |
| 8.01-16.0 | 1         | 0.6%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 130       | 83.33%  |
| 2      | 23        | 14.74%  |
| 3      | 3         | 1.92%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 79        | 50.97%  |
| Yes       | 76        | 49.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 139       | 89.68%  |
| No        | 16        | 10.32%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 153       | 98.08%  |
| No        | 3         | 1.92%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 110       | 70.06%  |
| No        | 47        | 29.94%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Morocco | 155       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Casablanca       | 39        | 23.93%  |
| Marrakesh        | 18        | 11.04%  |
| Rabat            | 17        | 10.43%  |
| Agadir           | 13        | 7.98%   |
| Fes              | 10        | 6.13%   |
| Oujda            | 7         | 4.29%   |
| Kenitra          | 7         | 4.29%   |
| Tangier          | 6         | 3.68%   |
| Salé            | 6         | 3.68%   |
| Khouribga        | 6         | 3.68%   |
| Nador            | 4         | 2.45%   |
| Meknes           | 4         | 2.45%   |
| Tiznit           | 3         | 1.84%   |
| Beni Mellal      | 3         | 1.84%   |
| Temara           | 2         | 1.23%   |
| Taza             | 2         | 1.23%   |
| Youssoufia       | 1         | 0.61%   |
| Tétouan         | 1         | 0.61%   |
| Targuist         | 1         | 0.61%   |
| Taourirt         | 1         | 0.61%   |
| Skhirate         | 1         | 0.61%   |
| Sidi Kacem       | 1         | 0.61%   |
| Safi             | 1         | 0.61%   |
| Mohammedia       | 1         | 0.61%   |
| Midelt           | 1         | 0.61%   |
| Ksar El Kebir    | 1         | 0.61%   |
| Karia Ba Mohamed | 1         | 0.61%   |
| Guelmim          | 1         | 0.61%   |
| Berkane          | 1         | 0.61%   |
| Al Aaroui        | 1         | 0.61%   |
| Agdz             | 1         | 0.61%   |
| Agdal            | 1         | 0.61%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 33        | 41     | 18.86%  |
| Toshiba             | 24        | 32     | 13.71%  |
| Samsung Electronics | 23        | 30     | 13.14%  |
| WDC                 | 20        | 25     | 11.43%  |
| Unknown             | 8         | 12     | 4.57%   |
| SanDisk             | 7         | 7      | 4%      |
| Hitachi             | 7         | 8      | 4%      |
| HGST                | 6         | 6      | 3.43%   |
| SK hynix            | 5         | 5      | 2.86%   |
| Kingston            | 5         | 6      | 2.86%   |
| Intel               | 4         | 5      | 2.29%   |
| Apple               | 4         | 4      | 2.29%   |
| KIOXIA              | 3         | 3      | 1.71%   |
| PNY                 | 2         | 3      | 1.14%   |
| LITEON              | 2         | 2      | 1.14%   |
| KingDian            | 2         | 4      | 1.14%   |
| Fujitsu             | 2         | 2      | 1.14%   |
| Crucial             | 2         | 2      | 1.14%   |
| China               | 2         | 3      | 1.14%   |
| TwinMOS             | 1         | 1      | 0.57%   |
| RCESSD              | 1         | 1      | 0.57%   |
| Phison              | 1         | 1      | 0.57%   |
| LITEONIT            | 1         | 1      | 0.57%   |
| KingSpec            | 1         | 1      | 0.57%   |
| KingFast            | 1         | 2      | 0.57%   |
| Indilinx            | 1         | 1      | 0.57%   |
| IBM/Hitachi         | 1         | 1      | 0.57%   |
| Hewlett-Packard     | 1         | 1      | 0.57%   |
| GOODRAM             | 1         | 1      | 0.57%   |
| BIWIN               | 1         | 1      | 0.57%   |
| Apacer              | 1         | 1      | 0.57%   |
| 2.5"                | 1         | 1      | 0.57%   |
| Unknown             | 1         | 1      | 0.57%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB         | 5         | 2.73%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 5         | 2.73%   |
| Samsung NVMe SSD Drive 512GB           | 4         | 2.19%   |
| Toshiba MQ01ACF050 500GB               | 3         | 1.64%   |
| Toshiba MQ01ABF050 500GB               | 3         | 1.64%   |
| Seagate ST500LT012-1DG142 500GB        | 3         | 1.64%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 3         | 1.64%   |
| WDC WD5000LPCX-80VHAT1 500GB           | 2         | 1.09%   |
| WDC WD5000LPCX-60VHAT0 500GB           | 2         | 1.09%   |
| WDC WD1600BEVT-22ZCT0 160GB            | 2         | 1.09%   |
| Unknown MMC Card  32GB                 | 2         | 1.09%   |
| Unknown MMC Card  16GB                 | 2         | 1.09%   |
| Toshiba MQ04ABF100 1TB                 | 2         | 1.09%   |
| Toshiba MQ01ABD100 1TB                 | 2         | 1.09%   |
| Seagate ST9500325AS 500GB              | 2         | 1.09%   |
| Seagate ST500VT000-1DK142 500GB        | 2         | 1.09%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 2         | 1.09%   |
| Seagate ST500LM000-1EJ162 500GB        | 2         | 1.09%   |
| Samsung MZVLW256HEHP-000L7 256GB       | 2         | 1.09%   |
| Hitachi HTS723232A7A364 320GB          | 2         | 1.09%   |
| HGST HTS725050A7E630 500GB             | 2         | 1.09%   |
| HGST HTS545050A7E680 500GB             | 2         | 1.09%   |
| WDC WDS256G1X0C-00ENX0 256GB           | 1         | 0.55%   |
| WDC WD5000LPCX-60VHAT1 500GB           | 1         | 0.55%   |
| WDC WD5000BPVT-22HXZT1 500GB           | 1         | 0.55%   |
| WDC WD3200BUCT-63TWBY0 320GB           | 1         | 0.55%   |
| WDC WD3200BPVT-22ZEST0 320GB           | 1         | 0.55%   |
| WDC WD3200BEVT-60ZCT1 320GB            | 1         | 0.55%   |
| WDC WD2500BPVT-22ZEST0 250GB           | 1         | 0.55%   |
| WDC WD2500BEVT-22A23T0 250GB           | 1         | 0.55%   |
| WDC WD2500BEKT-60V5T1 250GB            | 1         | 0.55%   |
| WDC WD10SPZX-60Z10T0 1TB               | 1         | 0.55%   |
| WDC WD10SPZX-08Z10 1TB                 | 1         | 0.55%   |
| WDC WD10JUCT-63CYNY0 1TB               | 1         | 0.55%   |
| WDC WD10JPVX-60JC3T0 1TB               | 1         | 0.55%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB   | 1         | 0.55%   |
| Unknown SB32G  32GB                    | 1         | 0.55%   |
| Unknown SB128  128GB                   | 1         | 0.55%   |
| Unknown NCard  64GB                    | 1         | 0.55%   |
| Unknown NCard  32GB                    | 1         | 0.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 33        | 41     | 36.67%  |
| Toshiba             | 20        | 24     | 22.22%  |
| WDC                 | 18        | 23     | 20%     |
| Hitachi             | 7         | 8      | 7.78%   |
| HGST                | 6         | 6      | 6.67%   |
| Samsung Electronics | 2         | 2      | 2.22%   |
| Fujitsu             | 2         | 2      | 2.22%   |
| IBM/Hitachi         | 1         | 1      | 1.11%   |
| Apple               | 1         | 1      | 1.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 7         | 7      | 15.22%  |
| Samsung Electronics | 6         | 9      | 13.04%  |
| Kingston            | 4         | 5      | 8.7%    |
| SK hynix            | 3         | 3      | 6.52%   |
| PNY                 | 2         | 3      | 4.35%   |
| LITEON              | 2         | 2      | 4.35%   |
| KingDian            | 2         | 4      | 4.35%   |
| Crucial             | 2         | 2      | 4.35%   |
| China               | 2         | 3      | 4.35%   |
| Apple               | 2         | 2      | 4.35%   |
| TwinMOS             | 1         | 1      | 2.17%   |
| Toshiba             | 1         | 1      | 2.17%   |
| RCESSD              | 1         | 1      | 2.17%   |
| LITEONIT            | 1         | 1      | 2.17%   |
| KingSpec            | 1         | 1      | 2.17%   |
| KingFast            | 1         | 1      | 2.17%   |
| Intel               | 1         | 2      | 2.17%   |
| Indilinx            | 1         | 1      | 2.17%   |
| Hewlett-Packard     | 1         | 1      | 2.17%   |
| GOODRAM             | 1         | 1      | 2.17%   |
| BIWIN               | 1         | 1      | 2.17%   |
| Apacer              | 1         | 1      | 2.17%   |
| 2.5"                | 1         | 1      | 2.17%   |
| Unknown             | 1         | 1      | 2.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 89        | 108    | 51.74%  |
| SSD     | 45        | 55     | 26.16%  |
| NVMe    | 29        | 39     | 16.86%  |
| MMC     | 8         | 12     | 4.65%   |
| Unknown | 1         | 1      | 0.58%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 125       | 164    | 77.16%  |
| NVMe | 29        | 39     | 17.9%   |
| MMC  | 8         | 12     | 4.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 99        | 120    | 75.57%  |
| 0.51-1.0   | 31        | 42     | 23.66%  |
| 1.01-2.0   | 1         | 1      | 0.76%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 47        | 29.75%  |
| 251-500    | 44        | 27.85%  |
| 501-1000   | 17        | 10.76%  |
| 21-50      | 15        | 9.49%   |
| 51-100     | 15        | 9.49%   |
| 1-20       | 12        | 7.59%   |
| 1001-2000  | 5         | 3.16%   |
| Unknown    | 3         | 1.9%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 72        | 42.86%  |
| 21-50    | 40        | 23.81%  |
| 101-250  | 25        | 14.88%  |
| 51-100   | 20        | 11.9%   |
| 251-500  | 6         | 3.57%   |
| Unknown  | 3         | 1.79%   |
| 501-1000 | 2         | 1.19%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                        | 2         | 2      | 10.53%  |
| WDC WD5000BPVT-22HXZT1 500GB                     | 1         | 1      | 5.26%   |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 3      | 5.26%   |
| Toshiba MQ01ACF050 500GB                         | 1         | 1      | 5.26%   |
| Toshiba MQ01ABD050 500GB                         | 1         | 1      | 5.26%   |
| Toshiba MQ01ABD032 320GB                         | 1         | 1      | 5.26%   |
| Toshiba MK2565GSXN 250GB                         | 1         | 1      | 5.26%   |
| Toshiba MK1237GSX 120GB                          | 1         | 1      | 5.26%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 5.26%   |
| Seagate ST500LM021-1KJ152 500GB                  | 1         | 1      | 5.26%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 5.26%   |
| Seagate ST500LM000-1EJ162 500GB                  | 1         | 1      | 5.26%   |
| SanDisk SD7UB3Q256G1001 256GB SSD                | 1         | 1      | 5.26%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 5.26%   |
| Hitachi HTS723232A7A364 320GB                    | 1         | 1      | 5.26%   |
| Hitachi HTS545050A7E380 500GB                    | 1         | 2      | 5.26%   |
| Hitachi HTS542525K9A300 250GB                    | 1         | 1      | 5.26%   |
| Fujitsu MHW2120BH 120GB                          | 1         | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 31.58%  |
| Toshiba             | 5         | 5      | 26.32%  |
| Hitachi             | 3         | 4      | 15.79%  |
| WDC                 | 2         | 4      | 10.53%  |
| SanDisk             | 1         | 1      | 5.26%   |
| Samsung Electronics | 1         | 1      | 5.26%   |
| Fujitsu             | 1         | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 35.29%  |
| Toshiba | 5         | 5      | 29.41%  |
| Hitachi | 3         | 4      | 17.65%  |
| WDC     | 2         | 4      | 11.76%  |
| Fujitsu | 1         | 1      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 17        | 20     | 89.47%  |
| SSD  | 2         | 2      | 10.53%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                      | Notebooks | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| WDC WD2500BEVT-22A23T0 250GB               | 1         | 2      | 50%     |
| Samsung Electronics MZVLB1T0HALR-00000 1TB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 2      | 50%     |
| Samsung Electronics | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 96        | 131    | 57.83%  |
| Works    | 49        | 59     | 29.52%  |
| Malfunc  | 19        | 22     | 11.45%  |
| Failed   | 2         | 3      | 1.2%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 127       | 76.51%  |
| Samsung Electronics              | 16        | 9.64%   |
| AMD                              | 9         | 5.42%   |
| Toshiba America Info Systems     | 3         | 1.81%   |
| KIOXIA                           | 3         | 1.81%   |
| SK hynix                         | 2         | 1.2%    |
| SanDisk                          | 2         | 1.2%    |
| Silicon Integrated Systems [SiS] | 1         | 0.6%    |
| Phison Electronics               | 1         | 0.6%    |
| Nvidia                           | 1         | 0.6%    |
| Kingston Technology Company      | 1         | 0.6%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 15        | 8.43%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 14        | 7.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 12        | 6.74%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 11        | 6.18%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 10        | 5.62%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 10        | 5.62%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 9         | 5.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 9         | 5.06%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 8         | 4.49%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 7         | 3.93%   |
| Intel Volume Management Device NVMe RAID Controller                              | 6         | 3.37%   |
| Intel Tiger Lake-LP SATA Controller                                              | 6         | 3.37%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 5         | 2.81%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 5         | 2.81%   |
| Intel Comet Lake SATA AHCI Controller                                            | 4         | 2.25%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 2.25%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 1.69%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 1.12%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 2         | 1.12%   |
| Intel SSD 660P Series                                                            | 2         | 1.12%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 1.12%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 1.12%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 1.12%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.12%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 0.56%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.56%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 1         | 0.56%   |
| SK hynix Non-Volatile memory controller                                          | 1         | 0.56%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.56%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.56%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.56%   |
| SanDisk WD Black NVMe SSD                                                        | 1         | 0.56%   |
| SanDisk Non-Volatile memory controller                                           | 1         | 0.56%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 0.56%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.56%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.56%   |
| KIOXIA NVMe SSD                                                                  | 1         | 0.56%   |
| Kingston Company Company Non-Volatile memory controller                          | 1         | 0.56%   |
| Intel SSD 600P Series                                                            | 1         | 0.56%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 118       | 67.82%  |
| NVMe | 29        | 16.67%  |
| RAID | 22        | 12.64%  |
| IDE  | 5         | 2.87%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 144       | 92.9%   |
| AMD    | 11        | 7.1%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz           | 6         | 3.87%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 5         | 3.23%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 5         | 3.23%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 4         | 2.58%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 4         | 2.58%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 4         | 2.58%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 4         | 2.58%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 4         | 2.58%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 3         | 1.94%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 3         | 1.94%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 3         | 1.94%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 3         | 1.94%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 3         | 1.94%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 3         | 1.94%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 1.29%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 2         | 1.29%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 2         | 1.29%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.29%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 1.29%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 1.29%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 2         | 1.29%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 1.29%   |
| Intel Core i5 CPU M 450 @ 2.40GHz           | 2         | 1.29%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 2         | 1.29%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 2         | 1.29%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 2         | 1.29%   |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz        | 2         | 1.29%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 2         | 1.29%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 2         | 1.29%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz           | 2         | 1.29%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2         | 1.29%   |
| AMD C-60 APU with Radeon HD Graphics        | 2         | 1.29%   |
| Intel Pentium M processor 1.73GHz           | 1         | 0.65%   |
| Intel Pentium Gold 7505 @ 2.00GHz           | 1         | 0.65%   |
| Intel Genuine CPU T2300 @ 1.66GHz           | 1         | 0.65%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.65%   |
| Intel Core i7-8850H CPU @ 2.60GHz           | 1         | 0.65%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.65%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.65%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz          | 1         | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 59        | 38.06%  |
| Intel Core i7           | 28        | 18.06%  |
| Intel Core i3           | 23        | 14.84%  |
| Other                   | 8         | 5.16%   |
| Intel Core 2 Duo        | 8         | 5.16%   |
| Intel Celeron           | 7         | 4.52%   |
| Intel Atom              | 5         | 3.23%   |
| AMD E1                  | 3         | 1.94%   |
| Intel Pentium Dual-Core | 2         | 1.29%   |
| AMD Ryzen 5             | 2         | 1.29%   |
| AMD C-60                | 2         | 1.29%   |
| Intel Pentium M         | 1         | 0.65%   |
| Intel Pentium Gold      | 1         | 0.65%   |
| Intel Genuine           | 1         | 0.65%   |
| Intel Celeron M         | 1         | 0.65%   |
| AMD Ryzen 7 PRO         | 1         | 0.65%   |
| AMD A8                  | 1         | 0.65%   |
| AMD A6                  | 1         | 0.65%   |
| AMD A4                  | 1         | 0.65%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 101       | 65.16%  |
| 4      | 42        | 27.1%   |
| 1      | 5         | 3.23%   |
| 6      | 4         | 2.58%   |
| 8      | 3         | 1.94%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 155       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 121       | 78.06%  |
| 1      | 34        | 21.94%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 150       | 96.77%  |
| 32-bit         | 3         | 1.94%   |
| Unknown        | 2         | 1.29%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 13.92%  |
| 0x206a7    | 16        | 10.13%  |
| 0x806ea    | 10        | 6.33%   |
| 0x306d4    | 10        | 6.33%   |
| 0x306c3    | 9         | 5.7%    |
| 0x40651    | 8         | 5.06%   |
| 0x306a9    | 8         | 5.06%   |
| 0x20655    | 7         | 4.43%   |
| 0x806c1    | 6         | 3.8%    |
| 0x406e3    | 6         | 3.8%    |
| 0x1067a    | 6         | 3.8%    |
| 0x806ec    | 5         | 3.16%   |
| 0x806e9    | 5         | 3.16%   |
| 0x20652    | 5         | 3.16%   |
| 0x506e3    | 3         | 1.9%    |
| 0x30678    | 3         | 1.9%    |
| 0x906ea    | 2         | 1.27%   |
| 0x6fd      | 2         | 1.27%   |
| 0x406c4    | 2         | 1.27%   |
| 0x406c3    | 2         | 1.27%   |
| 0x10676    | 2         | 1.27%   |
| 0x07030105 | 2         | 1.27%   |
| 0x906e9    | 1         | 0.63%   |
| 0x806eb    | 1         | 0.63%   |
| 0x806d1    | 1         | 0.63%   |
| 0x706e5    | 1         | 0.63%   |
| 0x706a1    | 1         | 0.63%   |
| 0x6ec      | 1         | 0.63%   |
| 0x6e8      | 1         | 0.63%   |
| 0x6d8      | 1         | 0.63%   |
| 0x30673    | 1         | 0.63%   |
| 0x30661    | 1         | 0.63%   |
| 0x0a50000c | 1         | 0.63%   |
| 0x08108102 | 1         | 0.63%   |
| 0x0700010f | 1         | 0.63%   |
| 0x06006705 | 1         | 0.63%   |
| 0x05000119 | 1         | 0.63%   |
| 0x05000101 | 1         | 0.63%   |
| 0x03000027 | 1         | 0.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 27        | 17.42%  |
| Haswell       | 21        | 13.55%  |
| SandyBridge   | 18        | 11.61%  |
| Westmere      | 12        | 7.74%   |
| Skylake       | 11        | 7.1%    |
| Broadwell     | 10        | 6.45%   |
| Penryn        | 9         | 5.81%   |
| IvyBridge     | 9         | 5.81%   |
| Silvermont    | 8         | 5.16%   |
| TigerLake     | 7         | 4.52%   |
| P6            | 3         | 1.94%   |
| Bobcat        | 3         | 1.94%   |
| Puma          | 2         | 1.29%   |
| Icelake       | 2         | 1.29%   |
| Core          | 2         | 1.29%   |
| Bonnell       | 2         | 1.29%   |
| Unknown       | 2         | 1.29%   |
| Zen+          | 1         | 0.65%   |
| Zen 3         | 1         | 0.65%   |
| K10 Llano     | 1         | 0.65%   |
| Jaguar        | 1         | 0.65%   |
| Goldmont plus | 1         | 0.65%   |
| Excavator     | 1         | 0.65%   |
| CometLake     | 1         | 0.65%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 132       | 69.84%  |
| Nvidia | 35        | 18.52%  |
| AMD    | 22        | 11.64%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17        | 8.9%    |
| Intel UHD Graphics 620                                                                   | 11        | 5.76%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 5.76%   |
| Intel HD Graphics 5500                                                                   | 10        | 5.24%   |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 5.24%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 4.71%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 8         | 4.19%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 3.66%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 6         | 3.14%   |
| Intel HD Graphics 620                                                                    | 6         | 3.14%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 2.62%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 2.09%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 2.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 2.09%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 2.09%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 3         | 1.57%   |
| Intel HD Graphics 530                                                                    | 3         | 1.57%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.57%   |
| Nvidia TU117M [GeForce MX450]                                                            | 2         | 1.05%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 1.05%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 1.05%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 2         | 1.05%   |
| Nvidia GF119M [NVS 4200M]                                                                | 2         | 1.05%   |
| Nvidia GF119M [GeForce GT 520M]                                                          | 2         | 1.05%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.05%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 1.05%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.05%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 1.05%   |
| AMD Wrestler [Radeon HD 6290]                                                            | 2         | 1.05%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 1.05%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 2         | 1.05%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                                       | 1         | 0.52%   |
| Nvidia TU104M [GeForce RTX 2080 Mobile]                                                  | 1         | 0.52%   |
| Nvidia GT218M [GeForce G210M]                                                            | 1         | 0.52%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.52%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 0.52%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.52%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.52%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 1         | 0.52%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 98        | 63.23%  |
| Intel + Nvidia | 29        | 18.71%  |
| 1 x AMD        | 17        | 10.97%  |
| 1 x Nvidia     | 6         | 3.87%   |
| Intel + AMD    | 5         | 3.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 134       | 84.28%  |
| Proprietary | 19        | 11.95%  |
| Unknown     | 6         | 3.77%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 115       | 72.33%  |
| 1.01-2.0   | 19        | 11.95%  |
| 0.01-0.5   | 15        | 9.43%   |
| 3.01-4.0   | 5         | 3.14%   |
| 0.51-1.0   | 4         | 2.52%   |
| 2.01-3.0   | 1         | 0.63%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 33        | 21.29%  |
| LG Display              | 30        | 19.35%  |
| Chimei Innolux          | 23        | 14.84%  |
| Samsung Electronics     | 21        | 13.55%  |
| BOE                     | 21        | 13.55%  |
| InfoVision              | 4         | 2.58%   |
| Hewlett-Packard         | 4         | 2.58%   |
| LG Philips              | 3         | 1.94%   |
| Lenovo                  | 3         | 1.94%   |
| Dell                    | 3         | 1.94%   |
| Chi Mei Optoelectronics | 3         | 1.94%   |
| Apple                   | 3         | 1.94%   |
| Sharp                   | 2         | 1.29%   |
| PANDA                   | 1         | 0.65%   |
| LGD                     | 1         | 0.65%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch    | 3         | 1.94%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch         | 3         | 1.94%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                    | 3         | 1.94%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 344x194mm 15.5-inch    | 2         | 1.29%   |
| Samsung Electronics LCD Monitor SDC4D42 1366x768 309x174mm 14.0-inch    | 2         | 1.29%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch            | 2         | 1.29%   |
| LG Display LCD Monitor LGD03D9 1366x768 345x194mm 15.6-inch             | 2         | 1.29%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch              | 2         | 1.29%   |
| Dell 2208WFP DEL403B 1680x1050 473x296mm 22.0-inch                      | 2         | 1.29%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                   | 2         | 1.29%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch          | 2         | 1.29%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch          | 2         | 1.29%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch           | 2         | 1.29%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch           | 2         | 1.29%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch           | 2         | 1.29%   |
| Sharp LCD Monitor SHP1516 3840x2400 336x210mm 15.6-inch                 | 1         | 0.65%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                 | 1         | 0.65%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch       | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch    | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC434E 1600x900 310x174mm 14.0-inch    | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC4143 1400x1050 286x214mm 14.1-inch   | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC3959 1366x768 344x194mm 15.5-inch    | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC3846 1680x1050 331x207mm 15.4-inch   | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 309x174mm 14.0-inch    | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch    | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch    | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC3051 1366x768 344x194mm 15.5-inch    | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch    | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch   | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch   | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SAM0FF0 3840x2160 1872x1053mm 84.6-inch | 1         | 0.65%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                 | 1         | 0.65%   |
| LGD LCD Monitor 1920x1080                                               | 1         | 0.65%   |
| LG Philips LCD Monitor LPLE300 1280x800 331x207mm 15.4-inch             | 1         | 0.65%   |
| LG Philips LCD Monitor LPLBC00 1280x800 331x207mm 15.4-inch             | 1         | 0.65%   |
| LG Philips LCD Monitor LPL8D00 1280x800 304x190mm 14.1-inch             | 1         | 0.65%   |
| LG Display LCD Monitor LGDD801 1366x768 344x194mm 15.5-inch             | 1         | 0.65%   |
| LG Display LCD Monitor LGD059D 1920x1080 309x174mm 14.0-inch            | 1         | 0.65%   |
| LG Display LCD Monitor LGD059A 1920x1080 344x194mm 15.5-inch            | 1         | 0.65%   |
| LG Display LCD Monitor LGD0532 1920x1080 344x194mm 15.5-inch            | 1         | 0.65%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 75        | 50%     |
| 1920x1080 (FHD)    | 43        | 28.67%  |
| 1600x900 (HD+)     | 12        | 8%      |
| 1280x800 (WXGA)    | 6         | 4%      |
| 1680x1050 (WSXGA+) | 3         | 2%      |
| 1024x600           | 3         | 2%      |
| 3840x2160 (4K)     | 2         | 1.33%   |
| 3840x2400          | 1         | 0.67%   |
| 2880x1800          | 1         | 0.67%   |
| 2560x1600          | 1         | 0.67%   |
| 1920x1200 (WUXGA)  | 1         | 0.67%   |
| 1400x1050          | 1         | 0.67%   |
| 1024x768 (XGA)     | 1         | 0.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 90        | 58.06%  |
| 14      | 22        | 14.19%  |
| 13      | 13        | 8.39%   |
| 12      | 8         | 5.16%   |
| 17      | 5         | 3.23%   |
| 24      | 3         | 1.94%   |
| 18      | 3         | 1.94%   |
| 11      | 3         | 1.94%   |
| 23      | 2         | 1.29%   |
| 22      | 2         | 1.29%   |
| 10      | 2         | 1.29%   |
| 84      | 1         | 0.65%   |
| Unknown | 1         | 0.65%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 116       | 74.84%  |
| 201-300     | 19        | 12.26%  |
| 351-400     | 9         | 5.81%   |
| 501-600     | 5         | 3.23%   |
| 401-500     | 4         | 2.58%   |
| 1501-2000   | 1         | 0.65%   |
| Unknown     | 1         | 0.65%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 133       | 88.67%  |
| 16/10   | 14        | 9.33%   |
| 4/3     | 2         | 1.33%   |
| Unknown | 1         | 0.67%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 89        | 57.42%  |
| 81-90          | 30        | 19.35%  |
| 61-70          | 8         | 5.16%   |
| 201-250        | 5         | 3.23%   |
| 71-80          | 4         | 2.58%   |
| 121-130        | 4         | 2.58%   |
| 51-60          | 3         | 1.94%   |
| 141-150        | 3         | 1.94%   |
| 41-50          | 2         | 1.29%   |
| 251-300        | 2         | 1.29%   |
| More than 1000 | 1         | 0.65%   |
| 131-140        | 1         | 0.65%   |
| 111-120        | 1         | 0.65%   |
| 91-100         | 1         | 0.65%   |
| Unknown        | 1         | 0.65%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 68        | 44.16%  |
| 121-160       | 55        | 35.71%  |
| 51-100        | 21        | 13.64%  |
| 161-240       | 7         | 4.55%   |
| More than 240 | 2         | 1.3%    |
| Unknown       | 1         | 0.65%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 144       | 92.31%  |
| 2     | 9         | 5.77%   |
| 0     | 3         | 1.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 80        | 33.2%   |
| Realtek Semiconductor    | 72        | 29.88%  |
| Qualcomm Atheros         | 37        | 15.35%  |
| Broadcom                 | 28        | 11.62%  |
| Ralink Technology        | 5         | 2.07%   |
| Xiaomi                   | 3         | 1.24%   |
| Ralink                   | 3         | 1.24%   |
| Broadcom Limited         | 3         | 1.24%   |
| Lenovo                   | 2         | 0.83%   |
| TP-Link                  | 1         | 0.41%   |
| Samsung Electronics      | 1         | 0.41%   |
| Qualcomm                 | 1         | 0.41%   |
| Nvidia                   | 1         | 0.41%   |
| Marvell Technology Group | 1         | 0.41%   |
| JMicron Technology       | 1         | 0.41%   |
| Dell                     | 1         | 0.41%   |
| Arduino SA               | 1         | 0.41%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 47        | 15.31%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 4.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 3.26%   |
| Intel Wireless 8265 / 8275                                        | 9         | 2.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 2.93%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 8         | 2.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 2.28%   |
| Intel Wireless 8260                                               | 7         | 2.28%   |
| Intel Wireless 7265                                               | 7         | 2.28%   |
| Intel 82577LM Gigabit Network Connection                          | 7         | 2.28%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 1.95%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 1.95%   |
| Intel Centrino Advanced-N 6200                                    | 6         | 1.95%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 1.63%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 5         | 1.63%   |
| Intel Wireless 7260                                               | 5         | 1.63%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 1.63%   |
| Intel Centrino Advanced-N 6235                                    | 5         | 1.63%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 1.63%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 1.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 1.3%    |
| Ralink MT7601U Wireless Adapter                                   | 4         | 1.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 1.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.3%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 1.3%    |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.3%    |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 1.3%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 1.3%    |
| Broadcom BCM43228 802.11a/b/g/n                                   | 4         | 1.3%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.98%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.98%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.98%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 0.98%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.65%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.65%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.65%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.65%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 73        | 46.5%   |
| Qualcomm Atheros      | 32        | 20.38%  |
| Realtek Semiconductor | 20        | 12.74%  |
| Broadcom              | 20        | 12.74%  |
| Ralink Technology     | 5         | 3.18%   |
| Ralink                | 3         | 1.91%   |
| Broadcom Limited      | 3         | 1.91%   |
| TP-Link               | 1         | 0.64%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 9         | 5.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 9         | 5.73%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 5.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 4.46%   |
| Intel Wireless 8260                                                     | 7         | 4.46%   |
| Intel Wireless 7265                                                     | 7         | 4.46%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 3.82%   |
| Intel Centrino Advanced-N 6200                                          | 6         | 3.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 3.18%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 5         | 3.18%   |
| Intel Wireless 7260                                                     | 5         | 3.18%   |
| Intel Centrino Advanced-N 6235                                          | 5         | 3.18%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 3.18%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 3.18%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 2.55%   |
| Ralink MT7601U Wireless Adapter                                         | 4         | 2.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 2.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 2.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 2.55%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 4         | 2.55%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.91%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 1.91%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.27%   |
| Intel WiFi Link 5100                                                    | 2         | 1.27%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 1.27%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 1.27%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 2         | 1.27%   |
| Broadcom BCM43225 802.11b/g/n                                           | 2         | 1.27%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.64%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.64%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.64%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 1         | 0.64%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.64%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.64%   |
| Realtek 802.11ac NIC                                                    | 1         | 0.64%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.64%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.64%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.64%   |
| Intel Wireless 3165                                                     | 1         | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 66        | 44.9%   |
| Intel                    | 50        | 34.01%  |
| Qualcomm Atheros         | 11        | 7.48%   |
| Broadcom                 | 10        | 6.8%    |
| Xiaomi                   | 3         | 2.04%   |
| Lenovo                   | 2         | 1.36%   |
| Samsung Electronics      | 1         | 0.68%   |
| Qualcomm                 | 1         | 0.68%   |
| Nvidia                   | 1         | 0.68%   |
| Marvell Technology Group | 1         | 0.68%   |
| JMicron Technology       | 1         | 0.68%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 47        | 31.97%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 8.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 6.8%    |
| Intel 82577LM Gigabit Network Connection                          | 7         | 4.76%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 4.08%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 3.4%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 2.72%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 2.72%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 2.72%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 2.04%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 2.04%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 2.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.36%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.36%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.36%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.36%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 2         | 1.36%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.36%   |
| Intel Ethernet Connection I217-V                                  | 2         | 1.36%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.36%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.36%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 1.36%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.68%   |
| Qualcomm Mobile Router                                            | 1         | 0.68%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.68%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.68%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.68%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.68%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 0.68%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.68%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.68%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.68%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.68%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.68%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.68%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                 | 1         | 0.68%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.68%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 0.68%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 1         | 0.68%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.68%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 153       | 51.86%  |
| Ethernet | 139       | 47.12%  |
| Modem    | 3         | 1.02%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 129       | 81.65%  |
| Ethernet | 29        | 18.35%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 135       | 86.54%  |
| 1     | 17        | 10.9%   |
| 0     | 3         | 1.92%   |
| 3     | 1         | 0.64%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 155       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 48        | 43.64%  |
| Realtek Semiconductor           | 15        | 13.64%  |
| Qualcomm Atheros Communications | 12        | 10.91%  |
| Broadcom                        | 8         | 7.27%   |
| Dell                            | 6         | 5.45%   |
| Lite-On Technology              | 5         | 4.55%   |
| Ralink                          | 3         | 2.73%   |
| IMC Networks                    | 3         | 2.73%   |
| Hewlett-Packard                 | 3         | 2.73%   |
| Apple                           | 2         | 1.82%   |
| Toshiba                         | 1         | 0.91%   |
| Foxconn International           | 1         | 0.91%   |
| Foxconn / Hon Hai               | 1         | 0.91%   |
| ASUSTek Computer                | 1         | 0.91%   |
| Alps Electric                   | 1         | 0.91%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 27        | 24.55%  |
| Realtek Bluetooth Radio                           | 10        | 9.09%   |
| Intel AX201 Bluetooth                             | 7         | 6.36%   |
| Qualcomm Atheros  Bluetooth Device                | 5         | 4.55%   |
| Intel Centrino Bluetooth Wireless Transceiver     | 5         | 4.55%   |
| Realtek  Bluetooth 4.2 Adapter                    | 4         | 3.64%   |
| Qualcomm Atheros AR3011 Bluetooth                 | 4         | 3.64%   |
| Dell DW375 Bluetooth Module                       | 4         | 3.64%   |
| Ralink RT3290 Bluetooth                           | 3         | 2.73%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 3         | 2.73%   |
| Intel Wireless-AC 3168 Bluetooth                  | 3         | 2.73%   |
| IMC Networks Bluetooth Device                     | 3         | 2.73%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 2         | 1.82%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device      | 2         | 1.82%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 2         | 1.82%   |
| Intel AX200 Bluetooth                             | 2         | 1.82%   |
| HP Broadcom 2070 Bluetooth Combo                  | 2         | 1.82%   |
| Broadcom HP Portable Bumble Bee                   | 2         | 1.82%   |
| Broadcom BCM43142A0 Bluetooth 4.0                 | 2         | 1.82%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]        | 2         | 1.82%   |
| Toshiba Bluetooth Device                          | 1         | 0.91%   |
| Realtek RTL8723B Bluetooth                        | 1         | 0.91%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 1         | 0.91%   |
| Intel Wireless-AC 9260 Bluetooth Adapter          | 1         | 0.91%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter  | 1         | 0.91%   |
| HP Bluetooth 1.2 Interface [Broadcom BCM2035]     | 1         | 0.91%   |
| Foxconn International BCM43142A0 Bluetooth module | 1         | 0.91%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller   | 1         | 0.91%   |
| Dell Wireless 360 Bluetooth                       | 1         | 0.91%   |
| Dell Wireless 350 Bluetooth                       | 1         | 0.91%   |
| Broadcom HP Portable SoftSailing                  | 1         | 0.91%   |
| Broadcom BCM43142 Bluetooth 4.0                   | 1         | 0.91%   |
| ASUS BT-270 Bluetooth Adapter                     | 1         | 0.91%   |
| Apple Built-in Bluetooth 2.0+EDR HCI              | 1         | 0.91%   |
| Apple Bluetooth Host Controller                   | 1         | 0.91%   |
| Alps Electric BCM2046 Bluetooth Device            | 1         | 0.91%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 140       | 77.78%  |
| Nvidia                           | 19        | 10.56%  |
| AMD                              | 16        | 8.89%   |
| Lenovo                           | 2         | 1.11%   |
| Silicon Integrated Systems [SiS] | 1         | 0.56%   |
| Logitech                         | 1         | 0.56%   |
| GN Netcom                        | 1         | 0.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 24        | 11.01%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 15        | 6.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 12        | 5.5%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 12        | 5.5%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 5.05%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 5.05%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 10        | 4.59%   |
| Intel Broadwell-U Audio Controller                                                                | 10        | 4.59%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 10        | 4.59%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 9         | 4.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 3.21%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 7         | 3.21%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 4         | 1.83%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 1.83%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.83%   |
| AMD FCH Azalia Controller                                                                         | 4         | 1.83%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.38%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 1.38%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.38%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 1.38%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.38%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.38%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 1.38%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.92%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 2         | 0.92%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.92%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 0.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.92%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.92%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.92%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 0.92%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.46%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.46%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.46%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.46%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.46%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.46%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.46%   |
| Nvidia Audio device                                                                               | 1         | 0.46%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 28        | 28.87%  |
| SK hynix            | 25        | 25.77%  |
| Micron Technology   | 13        | 13.4%   |
| Kingston            | 11        | 11.34%  |
| Unknown             | 5         | 5.15%   |
| Elpida              | 3         | 3.09%   |
| Crucial             | 3         | 3.09%   |
| Ramaxel Technology  | 2         | 2.06%   |
| A-DATA Technology   | 2         | 2.06%   |
| Transcend           | 1         | 1.03%   |
| Toshiba             | 1         | 1.03%   |
| Sesame              | 1         | 1.03%   |
| Nanya Technology    | 1         | 1.03%   |
| ASint Technology    | 1         | 1.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 4         | 3.81%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 4         | 3.81%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s    | 3         | 2.86%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 3         | 2.86%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 2         | 1.9%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s     | 2         | 1.9%    |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s     | 2         | 1.9%    |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s      | 2         | 1.9%    |
| Kingston RAM HP16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s     | 2         | 1.9%    |
| Unknown RAM Module 4GB SODIMM DDR3                        | 1         | 0.95%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1066MT/s            | 1         | 0.95%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                 | 1         | 0.95%   |
| Unknown RAM Module 2048MB SODIMM DDR2                     | 1         | 0.95%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                  | 1         | 0.95%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s              | 1         | 0.95%   |
| Transcend RAM JM1333KSN-4G 4096MB SODIMM DDR3 1334MT/s    | 1         | 0.95%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s         | 1         | 0.95%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s           | 1         | 0.95%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s           | 1         | 0.95%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s     | 1         | 0.95%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 0.95%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 0.95%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s | 1         | 0.95%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 1         | 0.95%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 1         | 0.95%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 0.95%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1600MT/s    | 1         | 0.95%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s    | 1         | 0.95%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s    | 1         | 0.95%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s    | 1         | 0.95%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s    | 1         | 0.95%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s    | 1         | 0.95%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1334MT/s    | 1         | 0.95%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s   | 1         | 0.95%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8192MB SODIMM DDR4 3200MT/s | 1         | 0.95%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 1         | 0.95%   |
| SK hynix RAM H9CCNNN8GTALAR-NUD 2GB LPDDR3 1600MT/s       | 1         | 0.95%   |
| Sesame RAM S939A2SGS-ITR 8192MB SODIMM DDR4 2667MT/s      | 1         | 0.95%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s               | 1         | 0.95%   |
| Samsung RAM M471B5773EB0-CK0 2048MB SODIMM DDR3 1600MT/s  | 1         | 0.95%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 41        | 53.25%  |
| DDR4    | 24        | 31.17%  |
| DDR2    | 4         | 5.19%   |
| LPDDR4  | 3         | 3.9%    |
| LPDDR3  | 3         | 3.9%    |
| SDRAM   | 1         | 1.3%    |
| Unknown | 1         | 1.3%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 71        | 93.42%  |
| Row Of Chips | 3         | 3.95%   |
| DIMM         | 1         | 1.32%   |
| Unknown      | 1         | 1.32%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 37        | 45.12%  |
| 8192  | 28        | 34.15%  |
| 2048  | 11        | 13.41%  |
| 16384 | 5         | 6.1%    |
| 1024  | 1         | 1.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 28        | 33.73%  |
| 2667    | 14        | 16.87%  |
| 1334    | 10        | 12.05%  |
| 3200    | 7         | 8.43%   |
| 2133    | 4         | 4.82%   |
| 1333    | 4         | 4.82%   |
| 2400    | 3         | 3.61%   |
| 1066    | 2         | 2.41%   |
| 975     | 2         | 2.41%   |
| Unknown | 2         | 2.41%   |
| 4267    | 1         | 1.2%    |
| 4199    | 1         | 1.2%    |
| 3266    | 1         | 1.2%    |
| 1867    | 1         | 1.2%    |
| 1067    | 1         | 1.2%    |
| 800     | 1         | 1.2%    |
| 667     | 1         | 1.2%    |

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

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 38        | 29.23%  |
| IMC Networks                           | 16        | 12.31%  |
| Cheng Uei Precision Industry (Foxlink) | 14        | 10.77%  |
| Realtek Semiconductor                  | 12        | 9.23%   |
| Suyin                                  | 8         | 6.15%   |
| Sunplus Innovation Technology          | 8         | 6.15%   |
| Lite-On Technology                     | 7         | 5.38%   |
| Microdia                               | 6         | 4.62%   |
| Ricoh                                  | 4         | 3.08%   |
| Quanta                                 | 4         | 3.08%   |
| Acer                                   | 3         | 2.31%   |
| Luxvisions Innotech Limited            | 2         | 1.54%   |
| Apple                                  | 2         | 1.54%   |
| Z-Star Microelectronics                | 1         | 0.77%   |
| Syntek                                 | 1         | 0.77%   |
| Sunplus Technology                     | 1         | 0.77%   |
| Silicon Motion                         | 1         | 0.77%   |
| ALi                                    | 1         | 0.77%   |
| Alcor Micro                            | 1         | 0.77%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 6         | 4.62%   |
| IMC Networks Integrated Camera                              | 5         | 3.85%   |
| Chicony HP Webcam [2 MP Macro]                              | 4         | 3.08%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 4         | 3.08%   |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 3         | 2.31%   |
| Microdia Integrated Webcam                                  | 3         | 2.31%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 3         | 2.31%   |
| Chicony HP Webcam                                           | 3         | 2.31%   |
| Chicony HP HD Webcam                                        | 3         | 2.31%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 3         | 2.31%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 2         | 1.54%   |
| Sunplus HP Universal Camera                                 | 2         | 1.54%   |
| Ricoh Laptop_Integrated_Webcam_FHD                          | 2         | 1.54%   |
| Realtek USB Camera                                          | 2         | 1.54%   |
| Realtek Integrated_Webcam_HD                                | 2         | 1.54%   |
| Lite-On TOSHIBA Web Camera - HD                             | 2         | 1.54%   |
| Lite-On HP HD Webcam                                        | 2         | 1.54%   |
| Lite-On HP HD Camera                                        | 2         | 1.54%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 2         | 1.54%   |
| IMC Networks Lenovo EasyCamera                              | 2         | 1.54%   |
| IMC Networks Integrated Webcam                              | 2         | 1.54%   |
| IMC Networks HP TrueVision HD Camera                        | 2         | 1.54%   |
| Chicony Lenovo Integrated Camera (0.3MP)                    | 2         | 1.54%   |
| Chicony Integrated Camera (1280x720@30)                     | 2         | 1.54%   |
| Chicony HP Wide Vision HD Camera                            | 2         | 1.54%   |
| Chicony HP HD Webcam [Fixed]                                | 2         | 1.54%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD     | 2         | 1.54%   |
| Z-Star Vimicro USB Camera (Mercury)                         | 1         | 0.77%   |
| Syntek Lenovo EasyCamera                                    | 1         | 0.77%   |
| Suyin WebCam                                                | 1         | 0.77%   |
| Suyin Sony Visual Communication Camera                      | 1         | 0.77%   |
| Suyin RGBIR Camera                                          | 1         | 0.77%   |
| Suyin Integrated_Webcam_HD                                  | 1         | 0.77%   |
| Suyin Integrated_Webcam_2M                                  | 1         | 0.77%   |
| Suyin HP Webcam-50                                          | 1         | 0.77%   |
| Sunplus 1.3M WebCam                                         | 1         | 0.77%   |
| Sunplus Integrated_Webcam_HD                                | 1         | 0.77%   |
| Sunplus HP Truevision HD                                    | 1         | 0.77%   |
| Sunplus Dell E5570 integrated webcam                        | 1         | 0.77%   |
| Silicon Motion WebCam SC-0311139N                           | 1         | 0.77%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 23        | 67.65%  |
| Synaptics                  | 5         | 14.71%  |
| Elan Microelectronics      | 4         | 11.76%  |
| Upek                       | 1         | 2.94%   |
| Shenzhen Goodix Technology | 1         | 2.94%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 10        | 29.41%  |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 8.82%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 8.82%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 8.82%   |
| Validity Sensors VFS491                                                    | 2         | 5.88%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 5.88%   |
| Elan ELAN:Fingerprint                                                      | 2         | 5.88%   |
| Elan ELAN:ARM-M4                                                           | 2         | 5.88%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2.94%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.94%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.94%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 2.94%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 2.94%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 2.94%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 2.94%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 12        | 63.16%  |
| Alcor Micro | 5         | 26.32%  |
| O2 Micro    | 2         | 10.53%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 36.84%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 26.32%  |
| Broadcom 5880                                                                | 3         | 15.79%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 10.53%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 5.26%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 5.26%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 88        | 55%     |
| 1     | 56        | 35%     |
| 2     | 15        | 9.38%   |
| 3     | 1         | 0.63%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 34        | 38.64%  |
| Chipcard                 | 19        | 21.59%  |
| Graphics card            | 14        | 15.91%  |
| Storage                  | 5         | 5.68%   |
| Net/wireless             | 5         | 5.68%   |
| Bluetooth                | 3         | 3.41%   |
| Net/ethernet             | 2         | 2.27%   |
| Communication controller | 2         | 2.27%   |
| Unassigned class         | 1         | 1.14%   |
| Sound                    | 1         | 1.14%   |
| Modem                    | 1         | 1.14%   |
| Camera                   | 1         | 1.14%   |

