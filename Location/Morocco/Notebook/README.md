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

Total: 233

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T560 20FJS3YN00    | [636921b46c](https://linux-hardware.org/?probe=636921b46c) | Nov 24, 2022 |
| HP            | 15                          | [51711b792f](https://linux-hardware.org/?probe=51711b792f) | Nov 20, 2022 |
| HP            | EliteBook 8540w             | [4da059da1b](https://linux-hardware.org/?probe=4da059da1b) | Nov 14, 2022 |
| Lenovo        | B50-30 20382                | [c4e67c5f10](https://linux-hardware.org/?probe=c4e67c5f10) | Nov 13, 2022 |
| HP            | 250 G5 Notebook PC          | [d710968897](https://linux-hardware.org/?probe=d710968897) | Nov 11, 2022 |
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
| Ubuntu 20.04       | 33        | 19.53%  |
| Ubuntu 18.04       | 13        | 7.69%   |
| KDE neon 20.04     | 10        | 5.92%   |
| Debian 11          | 7         | 4.14%   |
| Ubuntu 22.04       | 6         | 3.55%   |
| OpenMandriva 4.3   | 6         | 3.55%   |
| OpenMandriva 4.2   | 6         | 3.55%   |
| Linux Mint 20.2    | 6         | 3.55%   |
| Zorin 16           | 4         | 2.37%   |
| Ubuntu 20.10       | 4         | 2.37%   |
| Ubuntu 19.10       | 4         | 2.37%   |
| Linux Mint 20.3    | 4         | 2.37%   |
| Arch               | 4         | 2.37%   |
| Ubuntu Unity 16.04 | 3         | 1.78%   |
| Pop!_OS 22.04      | 3         | 1.78%   |
| Manjaro            | 3         | 1.78%   |
| ArcoLinux Rolling  | 3         | 1.78%   |
| Xubuntu 20.04      | 2         | 1.18%   |
| Void Linux         | 2         | 1.18%   |
| Ubuntu 21.10       | 2         | 1.18%   |
| Ubuntu 21.04       | 2         | 1.18%   |
| Pop!_OS 21.10      | 2         | 1.18%   |
| Linux Mint 21      | 2         | 1.18%   |
| Linux Mint 19.3    | 2         | 1.18%   |
| Kali 2019.4        | 2         | 1.18%   |
| Fedora 36          | 2         | 1.18%   |
| Zorin 15           | 1         | 0.59%   |
| Xero Rolling       | 1         | 0.59%   |
| Ubuntu Unity 20.04 | 1         | 0.59%   |
| Ubuntu MATE 22.10  | 1         | 0.59%   |
| Ubuntu MATE 20.04  | 1         | 0.59%   |
| Ubuntu 19.04       | 1         | 0.59%   |
| Ubuntu 16.04       | 1         | 0.59%   |
| Ubuntu             | 1         | 0.59%   |
| RHEL 8             | 1         | 0.59%   |
| Pop!_OS 20.10      | 1         | 0.59%   |
| Parrot 5.0         | 1         | 0.59%   |
| openSUSE Leap-15.2 | 1         | 0.59%   |
| Nobara 36          | 1         | 0.59%   |
| Manjaro 21.3.7     | 1         | 0.59%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 61        | 37.65%  |
| Linux Mint   | 15        | 9.26%   |
| OpenMandriva | 12        | 7.41%   |
| KDE neon     | 10        | 6.17%   |
| Debian       | 8         | 4.94%   |
| Pop!_OS      | 6         | 3.7%    |
| Manjaro      | 6         | 3.7%    |
| Zorin        | 5         | 3.09%   |
| Kali         | 5         | 3.09%   |
| Ubuntu Unity | 4         | 2.47%   |
| Fedora       | 4         | 2.47%   |
| Arch         | 4         | 2.47%   |
| Endless      | 3         | 1.85%   |
| ArcoLinux    | 3         | 1.85%   |
| Xubuntu      | 2         | 1.23%   |
| Void Linux   | 2         | 1.23%   |
| Ubuntu MATE  | 2         | 1.23%   |
| Elementary   | 2         | 1.23%   |
| Xero         | 1         | 0.62%   |
| RHEL         | 1         | 0.62%   |
| Parrot       | 1         | 0.62%   |
| openSUSE     | 1         | 0.62%   |
| Nobara       | 1         | 0.62%   |
| EndeavourOS  | 1         | 0.62%   |
| CentOS       | 1         | 0.62%   |
| BunsenLabs   | 1         | 0.62%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003      | 6         | 3.3%    |
| 5.10.14-desktop-1omv4002     | 6         | 3.3%    |
| 5.13.0-40-generic            | 5         | 2.75%   |
| 5.8.0-43-generic             | 4         | 2.2%    |
| 5.4.0-58-generic             | 4         | 2.2%    |
| 5.4.0-48-generic             | 4         | 2.2%    |
| 5.4.0-42-generic             | 3         | 1.65%   |
| 5.3.0-40-generic             | 3         | 1.65%   |
| 5.17.5-76051705-generic      | 3         | 1.65%   |
| 5.11.0-37-generic            | 3         | 1.65%   |
| 5.8.0-48-generic             | 2         | 1.1%    |
| 5.8.0-38-generic             | 2         | 1.1%    |
| 5.8.0-33-generic             | 2         | 1.1%    |
| 5.4.0-96-generic             | 2         | 1.1%    |
| 5.4.0-88-generic             | 2         | 1.1%    |
| 5.4.0-65-generic             | 2         | 1.1%    |
| 5.4.0-37-generic             | 2         | 1.1%    |
| 5.4.0-33-generic             | 2         | 1.1%    |
| 5.4.0-29-generic             | 2         | 1.1%    |
| 5.3.0-kali2-686-pae          | 2         | 1.1%    |
| 5.3.0-51-generic             | 2         | 1.1%    |
| 5.3.0-28-generic             | 2         | 1.1%    |
| 5.18.19_1                    | 2         | 1.1%    |
| 5.15.0-53-generic            | 2         | 1.1%    |
| 5.15.0-50-generic            | 2         | 1.1%    |
| 5.15.0-46-generic            | 2         | 1.1%    |
| 5.14.14-arch1-1              | 2         | 1.1%    |
| 5.13.0-27-generic            | 2         | 1.1%    |
| 5.13.0-19-generic            | 2         | 1.1%    |
| 5.11.0-46-generic            | 2         | 1.1%    |
| 5.11.0-36-generic            | 2         | 1.1%    |
| 5.0.0-23-generic             | 2         | 1.1%    |
| 5.8.15-201.fc32.x86_64       | 1         | 0.55%   |
| 5.8.1-050801-generic         | 1         | 0.55%   |
| 5.8.0-rc6-3.g007dcf0-default | 1         | 0.55%   |
| 5.8.0-63-generic             | 1         | 0.55%   |
| 5.8.0-55-generic             | 1         | 0.55%   |
| 5.8.0-41-generic             | 1         | 0.55%   |
| 5.8.0-36-generic             | 1         | 0.55%   |
| 5.8.0-34-generic             | 1         | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 34        | 20.24%  |
| 5.8.0   | 14        | 8.33%   |
| 5.15.0  | 11        | 6.55%   |
| 5.11.0  | 11        | 6.55%   |
| 4.15.0  | 11        | 6.55%   |
| 5.3.0   | 10        | 5.95%   |
| 5.13.0  | 10        | 5.95%   |
| 5.10.0  | 8         | 4.76%   |
| 5.16.7  | 6         | 3.57%   |
| 5.10.14 | 6         | 3.57%   |
| 5.0.0   | 6         | 3.57%   |
| 5.17.5  | 3         | 1.79%   |
| 4.18.0  | 3         | 1.79%   |
| 5.19.0  | 2         | 1.19%   |
| 5.18.19 | 2         | 1.19%   |
| 5.16.0  | 2         | 1.19%   |
| 5.14.14 | 2         | 1.19%   |
| 4.19.0  | 2         | 1.19%   |
| 5.8.15  | 1         | 0.6%    |
| 5.8.1   | 1         | 0.6%    |
| 5.7.15  | 1         | 0.6%    |
| 5.19.9  | 1         | 0.6%    |
| 5.19.16 | 1         | 0.6%    |
| 5.19.14 | 1         | 0.6%    |
| 5.18.18 | 1         | 0.6%    |
| 5.18.12 | 1         | 0.6%    |
| 5.17.9  | 1         | 0.6%    |
| 5.17.15 | 1         | 0.6%    |
| 5.17.1  | 1         | 0.6%    |
| 5.16.2  | 1         | 0.6%    |
| 5.15.60 | 1         | 0.6%    |
| 5.15.4  | 1         | 0.6%    |
| 5.15.23 | 1         | 0.6%    |
| 5.15.21 | 1         | 0.6%    |
| 5.15.15 | 1         | 0.6%    |
| 5.15.12 | 1         | 0.6%    |
| 5.14.0  | 1         | 0.6%    |
| 5.13.19 | 1         | 0.6%    |
| 5.11.7  | 1         | 0.6%    |
| 5.11.14 | 1         | 0.6%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 34        | 20.24%  |
| 5.15    | 17        | 10.12%  |
| 5.8     | 16        | 9.52%   |
| 5.10    | 15        | 8.93%   |
| 5.11    | 13        | 7.74%   |
| 5.13    | 11        | 6.55%   |
| 4.15    | 11        | 6.55%   |
| 5.3     | 10        | 5.95%   |
| 5.16    | 9         | 5.36%   |
| 5.17    | 6         | 3.57%   |
| 5.0     | 6         | 3.57%   |
| 5.19    | 5         | 2.98%   |
| 5.18    | 4         | 2.38%   |
| 5.14    | 3         | 1.79%   |
| 4.18    | 3         | 1.79%   |
| 4.19    | 2         | 1.19%   |
| 5.7     | 1         | 0.6%    |
| 4.4     | 1         | 0.6%    |
| 4.13    | 1         | 0.6%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 152       | 95.6%   |
| i686   | 7         | 4.4%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 80        | 49.08%  |
| KDE5            | 27        | 16.56%  |
| Unknown         | 14        | 8.59%   |
| X-Cinnamon      | 11        | 6.75%   |
| XFCE            | 10        | 6.13%   |
| KDE             | 6         | 3.68%   |
| Unity           | 4         | 2.45%   |
| MATE            | 3         | 1.84%   |
| Pantheon        | 2         | 1.23%   |
| Cinnamon        | 2         | 1.23%   |
| xmonad          | 1         | 0.61%   |
| i3              | 1         | 0.61%   |
| GNOME Flashback | 1         | 0.61%   |
| Budgie          | 1         | 0.61%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 133       | 81.6%   |
| Wayland | 22        | 13.5%   |
| Unknown | 7         | 4.29%   |
| Tty     | 1         | 0.61%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 86        | 51.81%  |
| SDDM    | 25        | 15.06%  |
| GDM     | 25        | 15.06%  |
| LightDM | 16        | 9.64%   |
| GDM3    | 11        | 6.63%   |
| TDM     | 3         | 1.81%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 88        | 55%     |
| fr_FR   | 43        | 26.88%  |
| Unknown | 12        | 7.5%    |
| en_GB   | 7         | 4.38%   |
| de_DE   | 3         | 1.88%   |
| fr_MA   | 1         | 0.63%   |
| fr_BE   | 1         | 0.63%   |
| es_ES   | 1         | 0.63%   |
| en_AG   | 1         | 0.63%   |
| C       | 1         | 0.63%   |
| ar_MA   | 1         | 0.63%   |
| ar_EG   | 1         | 0.63%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 99        | 61.88%  |
| EFI  | 61        | 38.13%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 133       | 83.65%  |
| Overlay | 14        | 8.81%   |
| Btrfs   | 8         | 5.03%   |
| Xfs     | 2         | 1.26%   |
| Unknown | 2         | 1.26%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 87        | 54.38%  |
| GPT     | 47        | 29.38%  |
| MBR     | 26        | 16.25%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 141       | 88.68%  |
| Yes       | 18        | 11.32%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 105       | 65.63%  |
| Yes       | 55        | 34.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 55        | 34.59%  |
| Lenovo              | 28        | 17.61%  |
| Dell                | 24        | 15.09%  |
| ASUSTek Computer    | 12        | 7.55%   |
| Acer                | 7         | 4.4%    |
| Toshiba             | 6         | 3.77%   |
| Sony                | 3         | 1.89%   |
| Packard Bell        | 3         | 1.89%   |
| Apple               | 3         | 1.89%   |
| Timi                | 2         | 1.26%   |
| Samsung Electronics | 2         | 1.26%   |
| eMachines           | 2         | 1.26%   |
| Unknown             | 2         | 1.26%   |
| TUXEDO              | 1         | 0.63%   |
| TrekStor            | 1         | 0.63%   |
| Razer               | 1         | 0.63%   |
| Medion              | 1         | 0.63%   |
| Mediacom            | 1         | 0.63%   |
| GPD                 | 1         | 0.63%   |
| Google              | 1         | 0.63%   |
| Gigabyte Technology | 1         | 0.63%   |
| Clevo               | 1         | 0.63%   |
| Casper              | 1         | 0.63%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| HP Laptop 15-dw3xxx                        | 3         | 1.89%   |
| HP EliteBook 8440p                         | 3         | 1.89%   |
| HP EliteBook 840 G2                        | 3         | 1.89%   |
| Unknown                                    | 3         | 1.89%   |
| Timi TM1701                                | 2         | 1.26%   |
| Lenovo ThinkBook 15 G2 ITL 20VE            | 2         | 1.26%   |
| Lenovo IdeaPad L3 15IML05 81Y3             | 2         | 1.26%   |
| HP ZBook 15                                | 2         | 1.26%   |
| HP ProBook 650 G1                          | 2         | 1.26%   |
| HP ProBook 6470b                           | 2         | 1.26%   |
| HP Notebook                                | 2         | 1.26%   |
| HP EliteBook 8460p                         | 2         | 1.26%   |
| HP 250 G5 Notebook PC                      | 2         | 1.26%   |
| Dell Latitude E6520                        | 2         | 1.26%   |
| ASUS X540LA                                | 2         | 1.26%   |
| Acer Aspire ES1-523                        | 2         | 1.26%   |
| TUXEDO N13xWU                              | 1         | 0.63%   |
| TrekStor Surfbook W2                       | 1         | 0.63%   |
| Toshiba Satellite Pro C650                 | 1         | 0.63%   |
| Toshiba Satellite L750                     | 1         | 0.63%   |
| Toshiba Satellite L50-A-1EL                | 1         | 0.63%   |
| Toshiba Satellite L50-A-1DG                | 1         | 0.63%   |
| Toshiba Satellite C855-2CF                 | 1         | 0.63%   |
| Toshiba Satellite C660                     | 1         | 0.63%   |
| Sony VPCEH1L8E                             | 1         | 0.63%   |
| Sony VGN-FW11L                             | 1         | 0.63%   |
| Sony SVE14122CAW                           | 1         | 0.63%   |
| Samsung 355V4C/356V4C/3445VC/3545VC        | 1         | 0.63%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 0.63%   |
| Razer Blade Pro 17 (2019)                  | 1         | 0.63%   |
| Packard Bell EasyNote TS44HR               | 1         | 0.63%   |
| Packard Bell EasyNote TS11HR               | 1         | 0.63%   |
| Packard Bell EasyNote TK85                 | 1         | 0.63%   |
| Medion P7615                               | 1         | 0.63%   |
| Mediacom WinPad 11,6 FullHD- WPU11         | 1         | 0.63%   |
| Lenovo Z70-80 80FG                         | 1         | 0.63%   |
| Lenovo ThinkPad X280 20KF001KFR            | 1         | 0.63%   |
| Lenovo ThinkPad X250 20CLS4WV08            | 1         | 0.63%   |
| Lenovo ThinkPad X240 20AMA09VFR            | 1         | 0.63%   |
| Lenovo ThinkPad X220 4291V5K               | 1         | 0.63%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 18        | 11.32%  |
| Dell Latitude         | 18        | 11.32%  |
| HP EliteBook          | 16        | 10.06%  |
| HP ProBook            | 8         | 5.03%   |
| HP Laptop             | 8         | 5.03%   |
| HP Pavilion           | 7         | 4.4%    |
| Toshiba Satellite     | 6         | 3.77%   |
| Acer Aspire           | 5         | 3.14%   |
| Lenovo IdeaPad        | 4         | 2.52%   |
| HP 250                | 4         | 2.52%   |
| Packard Bell EasyNote | 3         | 1.89%   |
| HP ZBook              | 3         | 1.89%   |
| Unknown               | 3         | 1.89%   |
| Timi TM1701           | 2         | 1.26%   |
| Lenovo ThinkBook      | 2         | 1.26%   |
| HP Notebook           | 2         | 1.26%   |
| HP Compaq             | 2         | 1.26%   |
| Dell Precision        | 2         | 1.26%   |
| Dell Inspiron         | 2         | 1.26%   |
| ASUS X540LA           | 2         | 1.26%   |
| TUXEDO N13xWU         | 1         | 0.63%   |
| TrekStor Surfbook     | 1         | 0.63%   |
| Sony VPCEH1L8E        | 1         | 0.63%   |
| Sony VGN-FW11L        | 1         | 0.63%   |
| Sony SVE14122CAW      | 1         | 0.63%   |
| Samsung 355V4C        | 1         | 0.63%   |
| Samsung 300E4A        | 1         | 0.63%   |
| Razer Blade           | 1         | 0.63%   |
| Medion P7615          | 1         | 0.63%   |
| Mediacom WinPad       | 1         | 0.63%   |
| Lenovo Z70-80         | 1         | 0.63%   |
| Lenovo S21e-20        | 1         | 0.63%   |
| Lenovo G50-70         | 1         | 0.63%   |
| Lenovo B50-30         | 1         | 0.63%   |
| HP Presario           | 1         | 0.63%   |
| HP 650                | 1         | 0.63%   |
| HP 255                | 1         | 0.63%   |
| HP 15                 | 1         | 0.63%   |
| GPD MicroPC           | 1         | 0.63%   |
| Google Banon          | 1         | 0.63%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 18        | 11.32%  |
| 2011 | 18        | 11.32%  |
| 2016 | 16        | 10.06%  |
| 2010 | 15        | 9.43%   |
| 2018 | 14        | 8.81%   |
| 2015 | 14        | 8.81%   |
| 2020 | 10        | 6.29%   |
| 2012 | 10        | 6.29%   |
| 2017 | 9         | 5.66%   |
| 2014 | 9         | 5.66%   |
| 2019 | 8         | 5.03%   |
| 2021 | 6         | 3.77%   |
| 2009 | 5         | 3.14%   |
| 2008 | 3         | 1.89%   |
| 2007 | 2         | 1.26%   |
| 2006 | 1         | 0.63%   |
| 2005 | 1         | 0.63%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 159       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 153       | 94.44%  |
| Enabled  | 9         | 5.56%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 158       | 99.37%  |
| Yes  | 1         | 0.63%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 59        | 37.11%  |
| 3.01-4.0   | 46        | 28.93%  |
| 16.01-24.0 | 17        | 10.69%  |
| 8.01-16.0  | 16        | 10.06%  |
| 1.01-2.0   | 11        | 6.92%   |
| 32.01-64.0 | 3         | 1.89%   |
| 24.01-32.0 | 3         | 1.89%   |
| 2.01-3.0   | 2         | 1.26%   |
| 0.51-1.0   | 2         | 1.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 68        | 39.53%  |
| 2.01-3.0  | 57        | 33.14%  |
| 4.01-8.0  | 21        | 12.21%  |
| 3.01-4.0  | 18        | 10.47%  |
| 0.51-1.0  | 7         | 4.07%   |
| 8.01-16.0 | 1         | 0.58%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 134       | 83.23%  |
| 2      | 23        | 14.29%  |
| 3      | 4         | 2.48%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 80        | 50.31%  |
| No        | 79        | 49.69%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 143       | 89.94%  |
| No        | 16        | 10.06%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 157       | 98.13%  |
| No        | 3         | 1.88%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 114       | 70.81%  |
| No        | 47        | 29.19%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Morocco | 159       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Casablanca       | 40        | 23.95%  |
| Marrakesh        | 18        | 10.78%  |
| Rabat            | 17        | 10.18%  |
| Agadir           | 13        | 7.78%   |
| Fes              | 11        | 6.59%   |
| Salé            | 7         | 4.19%   |
| Oujda            | 7         | 4.19%   |
| Kenitra          | 7         | 4.19%   |
| Tangier          | 6         | 3.59%   |
| Khouribga        | 6         | 3.59%   |
| Nador            | 4         | 2.4%    |
| Meknes           | 4         | 2.4%    |
| Tiznit           | 3         | 1.8%    |
| Beni Mellal      | 3         | 1.8%    |
| Temara           | 2         | 1.2%    |
| Taza             | 2         | 1.2%    |
| Guelmim          | 2         | 1.2%    |
| Youssoufia       | 1         | 0.6%    |
| Tétouan         | 1         | 0.6%    |
| Targuist         | 1         | 0.6%    |
| Taourirt         | 1         | 0.6%    |
| Skhirate         | 1         | 0.6%    |
| Sidi Kacem       | 1         | 0.6%    |
| Safi             | 1         | 0.6%    |
| Mohammedia       | 1         | 0.6%    |
| Midelt           | 1         | 0.6%    |
| Ksar El Kebir    | 1         | 0.6%    |
| Karia Ba Mohamed | 1         | 0.6%    |
| Berkane          | 1         | 0.6%    |
| Al Aaroui        | 1         | 0.6%    |
| Agdz             | 1         | 0.6%    |
| Agdal            | 1         | 0.6%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 34        | 42     | 18.89%  |
| Toshiba             | 24        | 32     | 13.33%  |
| Samsung Electronics | 23        | 30     | 12.78%  |
| WDC                 | 21        | 27     | 11.67%  |
| Unknown             | 9         | 13     | 5%      |
| SanDisk             | 7         | 7      | 3.89%   |
| Hitachi             | 7         | 8      | 3.89%   |
| HGST                | 7         | 7      | 3.89%   |
| SK hynix            | 5         | 5      | 2.78%   |
| Kingston            | 5         | 6      | 2.78%   |
| Intel               | 5         | 6      | 2.78%   |
| Apple               | 4         | 4      | 2.22%   |
| KIOXIA              | 3         | 3      | 1.67%   |
| PNY                 | 2         | 3      | 1.11%   |
| LITEON              | 2         | 2      | 1.11%   |
| KingDian            | 2         | 5      | 1.11%   |
| Fujitsu             | 2         | 2      | 1.11%   |
| Crucial             | 2         | 2      | 1.11%   |
| China               | 2         | 3      | 1.11%   |
| TwinMOS             | 1         | 1      | 0.56%   |
| RCESSD              | 1         | 1      | 0.56%   |
| Phison              | 1         | 1      | 0.56%   |
| LITEONIT            | 1         | 1      | 0.56%   |
| KingSpec            | 1         | 1      | 0.56%   |
| KingFast            | 1         | 2      | 0.56%   |
| Indilinx            | 1         | 1      | 0.56%   |
| IBM/Hitachi         | 1         | 1      | 0.56%   |
| Hewlett-Packard     | 1         | 1      | 0.56%   |
| GOODRAM             | 1         | 1      | 0.56%   |
| BIWIN               | 1         | 1      | 0.56%   |
| Apacer              | 1         | 1      | 0.56%   |
| 2.5"                | 1         | 1      | 0.56%   |
| Unknown             | 1         | 1      | 0.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB         | 5         | 2.66%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 5         | 2.66%   |
| Seagate ST500LT012-1DG142 500GB        | 4         | 2.13%   |
| Samsung NVMe SSD Drive 512GB           | 4         | 2.13%   |
| Toshiba MQ01ACF050 500GB               | 3         | 1.6%    |
| Toshiba MQ01ABF050 500GB               | 3         | 1.6%    |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 3         | 1.6%    |
| HGST HTS545050A7E680 500GB             | 3         | 1.6%    |
| WDC WD5000LPCX-80VHAT1 500GB           | 2         | 1.06%   |
| WDC WD5000LPCX-60VHAT0 500GB           | 2         | 1.06%   |
| WDC WD1600BEVT-22ZCT0 160GB            | 2         | 1.06%   |
| Unknown MMC Card  32GB                 | 2         | 1.06%   |
| Unknown MMC Card  16GB                 | 2         | 1.06%   |
| Toshiba MQ04ABF100 1TB                 | 2         | 1.06%   |
| Toshiba MQ01ABD100 1TB                 | 2         | 1.06%   |
| Seagate ST9500325AS 500GB              | 2         | 1.06%   |
| Seagate ST500VT000-1DK142 500GB        | 2         | 1.06%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 2         | 1.06%   |
| Seagate ST500LM000-1EJ162 500GB        | 2         | 1.06%   |
| Samsung MZVLW256HEHP-000L7 256GB       | 2         | 1.06%   |
| Hitachi HTS723232A7A364 320GB          | 2         | 1.06%   |
| HGST HTS725050A7E630 500GB             | 2         | 1.06%   |
| WDC WDS256G1X0C-00ENX0 256GB           | 1         | 0.53%   |
| WDC WD5000LPCX-60VHAT1 500GB           | 1         | 0.53%   |
| WDC WD5000BPVT-22HXZT1 500GB           | 1         | 0.53%   |
| WDC WD3200BUCT-63TWBY0 320GB           | 1         | 0.53%   |
| WDC WD3200BPVT-22ZEST0 320GB           | 1         | 0.53%   |
| WDC WD3200BEVT-60ZCT1 320GB            | 1         | 0.53%   |
| WDC WD2500BPVT-22ZEST0 250GB           | 1         | 0.53%   |
| WDC WD2500BEVT-22A23T0 250GB           | 1         | 0.53%   |
| WDC WD2500BEKT-60V5T1 250GB            | 1         | 0.53%   |
| WDC WD2500BEKT-60A25T1 250GB           | 1         | 0.53%   |
| WDC WD10SPZX-60Z10T0 1TB               | 1         | 0.53%   |
| WDC WD10SPZX-08Z10 1TB                 | 1         | 0.53%   |
| WDC WD10JUCT-63CYNY0 1TB               | 1         | 0.53%   |
| WDC WD10JPVX-60JC3T0 1TB               | 1         | 0.53%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB   | 1         | 0.53%   |
| Unknown SD32G  32GB                    | 1         | 0.53%   |
| Unknown SB32G  32GB                    | 1         | 0.53%   |
| Unknown SB128  128GB                   | 1         | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 34        | 42     | 36.56%  |
| Toshiba             | 20        | 24     | 21.51%  |
| WDC                 | 19        | 25     | 20.43%  |
| Hitachi             | 7         | 8      | 7.53%   |
| HGST                | 7         | 7      | 7.53%   |
| Samsung Electronics | 2         | 2      | 2.15%   |
| Fujitsu             | 2         | 2      | 2.15%   |
| IBM/Hitachi         | 1         | 1      | 1.08%   |
| Apple               | 1         | 1      | 1.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 7         | 7      | 14.89%  |
| Samsung Electronics | 6         | 9      | 12.77%  |
| Kingston            | 4         | 5      | 8.51%   |
| SK hynix            | 3         | 3      | 6.38%   |
| PNY                 | 2         | 3      | 4.26%   |
| LITEON              | 2         | 2      | 4.26%   |
| KingDian            | 2         | 5      | 4.26%   |
| Intel               | 2         | 3      | 4.26%   |
| Crucial             | 2         | 2      | 4.26%   |
| China               | 2         | 3      | 4.26%   |
| Apple               | 2         | 2      | 4.26%   |
| TwinMOS             | 1         | 1      | 2.13%   |
| Toshiba             | 1         | 1      | 2.13%   |
| RCESSD              | 1         | 1      | 2.13%   |
| LITEONIT            | 1         | 1      | 2.13%   |
| KingSpec            | 1         | 1      | 2.13%   |
| KingFast            | 1         | 1      | 2.13%   |
| Indilinx            | 1         | 1      | 2.13%   |
| Hewlett-Packard     | 1         | 1      | 2.13%   |
| GOODRAM             | 1         | 1      | 2.13%   |
| BIWIN               | 1         | 1      | 2.13%   |
| Apacer              | 1         | 1      | 2.13%   |
| 2.5"                | 1         | 1      | 2.13%   |
| Unknown             | 1         | 1      | 2.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 92        | 112    | 51.98%  |
| SSD     | 46        | 57     | 25.99%  |
| NVMe    | 29        | 39     | 16.38%  |
| MMC     | 9         | 13     | 5.08%   |
| Unknown | 1         | 1      | 0.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 129       | 170    | 77.25%  |
| NVMe | 29        | 39     | 17.37%  |
| MMC  | 9         | 13     | 5.39%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 103       | 125    | 76.3%   |
| 0.51-1.0   | 31        | 43     | 22.96%  |
| 1.01-2.0   | 1         | 1      | 0.74%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 48        | 29.63%  |
| 251-500        | 44        | 27.16%  |
| 501-1000       | 17        | 10.49%  |
| 51-100         | 16        | 9.88%   |
| 21-50          | 15        | 9.26%   |
| 1-20           | 13        | 8.02%   |
| 1001-2000      | 5         | 3.09%   |
| Unknown        | 3         | 1.85%   |
| More than 3000 | 1         | 0.62%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 74        | 43.02%  |
| 21-50          | 40        | 23.26%  |
| 101-250        | 25        | 14.53%  |
| 51-100         | 21        | 12.21%  |
| 251-500        | 6         | 3.49%   |
| Unknown        | 3         | 1.74%   |
| 501-1000       | 2         | 1.16%   |
| More than 3000 | 1         | 0.58%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                        | 2         | 2      | 9.52%   |
| WDC WD5000BPVT-22HXZT1 500GB                     | 1         | 1      | 4.76%   |
| WDC WD2500BEKT-60A25T1 250GB                     | 1         | 1      | 4.76%   |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 4      | 4.76%   |
| Toshiba MQ01ACF050 500GB                         | 1         | 1      | 4.76%   |
| Toshiba MQ01ABD050 500GB                         | 1         | 1      | 4.76%   |
| Toshiba MQ01ABD032 320GB                         | 1         | 1      | 4.76%   |
| Toshiba MK2565GSXN 250GB                         | 1         | 1      | 4.76%   |
| Toshiba MK1237GSX 120GB                          | 1         | 1      | 4.76%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 4.76%   |
| Seagate ST500LM021-1KJ152 500GB                  | 1         | 1      | 4.76%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 4.76%   |
| Seagate ST500LM000-1EJ162 500GB                  | 1         | 1      | 4.76%   |
| SanDisk SD7UB3Q256G1001 256GB SSD                | 1         | 1      | 4.76%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 4.76%   |
| Hitachi HTS723232A7A364 320GB                    | 1         | 1      | 4.76%   |
| Hitachi HTS545050A7E380 500GB                    | 1         | 2      | 4.76%   |
| Hitachi HTS542525K9A300 250GB                    | 1         | 1      | 4.76%   |
| HGST HTS545050A7E680 500GB                       | 1         | 1      | 4.76%   |
| Fujitsu MHW2120BH 120GB                          | 1         | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 28.57%  |
| Toshiba             | 5         | 5      | 23.81%  |
| WDC                 | 3         | 6      | 14.29%  |
| Hitachi             | 3         | 4      | 14.29%  |
| SanDisk             | 1         | 1      | 4.76%   |
| Samsung Electronics | 1         | 1      | 4.76%   |
| HGST                | 1         | 1      | 4.76%   |
| Fujitsu             | 1         | 1      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 31.58%  |
| Toshiba | 5         | 5      | 26.32%  |
| WDC     | 3         | 6      | 15.79%  |
| Hitachi | 3         | 4      | 15.79%  |
| HGST    | 1         | 1      | 5.26%   |
| Fujitsu | 1         | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 23     | 90.48%  |
| SSD  | 2         | 2      | 9.52%   |

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
| Detected | 98        | 133    | 57.31%  |
| Works    | 50        | 61     | 29.24%  |
| Malfunc  | 21        | 25     | 12.28%  |
| Failed   | 2         | 3      | 1.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 131       | 77.06%  |
| Samsung Electronics              | 16        | 9.41%   |
| AMD                              | 9         | 5.29%   |
| Toshiba America Info Systems     | 3         | 1.76%   |
| KIOXIA                           | 3         | 1.76%   |
| SK hynix                         | 2         | 1.18%   |
| SanDisk                          | 2         | 1.18%   |
| Silicon Integrated Systems [SiS] | 1         | 0.59%   |
| Phison Electronics               | 1         | 0.59%   |
| Nvidia                           | 1         | 0.59%   |
| Kingston Technology Company      | 1         | 0.59%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 15        | 8.24%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 15        | 8.24%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 12        | 6.59%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 11        | 6.04%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 11        | 6.04%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 10        | 5.49%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 9         | 4.95%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 9         | 4.95%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 8         | 4.4%    |
| AMD FCH SATA Controller [AHCI mode]                                            | 7         | 3.85%   |
| Intel Volume Management Device NVMe RAID Controller                            | 6         | 3.3%    |
| Intel Tiger Lake-LP SATA Controller                                            | 6         | 3.3%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 2.75%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5         | 2.75%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 5         | 2.75%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 2.2%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 1.65%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 1.65%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 1.1%    |
| KIOXIA NVMe SSD Controller BG4                                                 | 2         | 1.1%    |
| Intel SSD 660P Series                                                          | 2         | 1.1%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 1.1%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 2         | 1.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 1.1%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.55%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.55%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 1         | 0.55%   |
| SK hynix Non-Volatile memory controller                                        | 1         | 0.55%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.55%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 1         | 0.55%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 1         | 0.55%   |
| SanDisk WD Black NVMe SSD                                                      | 1         | 0.55%   |
| SanDisk Non-Volatile memory controller                                         | 1         | 0.55%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 0.55%   |
| Phison E12 NVMe Controller                                                     | 1         | 0.55%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 0.55%   |
| KIOXIA NVMe SSD                                                                | 1         | 0.55%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 0.55%   |
| Intel SSD 600P Series                                                          | 1         | 0.55%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 122       | 68.54%  |
| NVMe | 29        | 16.29%  |
| RAID | 22        | 12.36%  |
| IDE  | 5         | 2.81%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 148       | 93.08%  |
| AMD    | 11        | 6.92%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz           | 6         | 3.77%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 6         | 3.77%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 5         | 3.14%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 5         | 3.14%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 4         | 2.52%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 4         | 2.52%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 4         | 2.52%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 4         | 2.52%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 3         | 1.89%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 3         | 1.89%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 3         | 1.89%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 3         | 1.89%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 3         | 1.89%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 3         | 1.89%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 3         | 1.89%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 3         | 1.89%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 1.26%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 2         | 1.26%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 2         | 1.26%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.26%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 1.26%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 2         | 1.26%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 1.26%   |
| Intel Core i5 CPU M 450 @ 2.40GHz           | 2         | 1.26%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 2         | 1.26%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 2         | 1.26%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 2         | 1.26%   |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz        | 2         | 1.26%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 2         | 1.26%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz           | 2         | 1.26%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2         | 1.26%   |
| AMD C-60 APU with Radeon HD Graphics        | 2         | 1.26%   |
| Intel Pentium M processor 1.73GHz           | 1         | 0.63%   |
| Intel Pentium Gold 7505 @ 2.00GHz           | 1         | 0.63%   |
| Intel Genuine CPU T2300 @ 1.66GHz           | 1         | 0.63%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.63%   |
| Intel Core i7-8850H CPU @ 2.60GHz           | 1         | 0.63%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.63%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.63%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz          | 1         | 0.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 61        | 38.36%  |
| Intel Core i7           | 28        | 17.61%  |
| Intel Core i3           | 24        | 15.09%  |
| Other                   | 8         | 5.03%   |
| Intel Core 2 Duo        | 8         | 5.03%   |
| Intel Celeron           | 8         | 5.03%   |
| Intel Atom              | 5         | 3.14%   |
| AMD E1                  | 3         | 1.89%   |
| Intel Pentium Dual-Core | 2         | 1.26%   |
| AMD Ryzen 5             | 2         | 1.26%   |
| AMD C-60                | 2         | 1.26%   |
| Intel Pentium M         | 1         | 0.63%   |
| Intel Pentium Gold      | 1         | 0.63%   |
| Intel Genuine           | 1         | 0.63%   |
| Intel Celeron M         | 1         | 0.63%   |
| AMD Ryzen 7 PRO         | 1         | 0.63%   |
| AMD A8                  | 1         | 0.63%   |
| AMD A6                  | 1         | 0.63%   |
| AMD A4                  | 1         | 0.63%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 105       | 66.04%  |
| 4      | 42        | 26.42%  |
| 1      | 5         | 3.14%   |
| 6      | 4         | 2.52%   |
| 8      | 3         | 1.89%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 159       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 124       | 77.99%  |
| 1      | 35        | 22.01%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 154       | 96.86%  |
| 32-bit         | 3         | 1.89%   |
| Unknown        | 2         | 1.26%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 14.81%  |
| 0x206a7    | 16        | 9.88%   |
| 0x306d4    | 11        | 6.79%   |
| 0x806ea    | 10        | 6.17%   |
| 0x306c3    | 9         | 5.56%   |
| 0x40651    | 8         | 4.94%   |
| 0x306a9    | 8         | 4.94%   |
| 0x20655    | 7         | 4.32%   |
| 0x806c1    | 6         | 3.7%    |
| 0x406e3    | 6         | 3.7%    |
| 0x1067a    | 6         | 3.7%    |
| 0x806ec    | 5         | 3.09%   |
| 0x806e9    | 5         | 3.09%   |
| 0x20652    | 5         | 3.09%   |
| 0x30678    | 4         | 2.47%   |
| 0x506e3    | 3         | 1.85%   |
| 0x906ea    | 2         | 1.23%   |
| 0x6fd      | 2         | 1.23%   |
| 0x406c4    | 2         | 1.23%   |
| 0x406c3    | 2         | 1.23%   |
| 0x10676    | 2         | 1.23%   |
| 0x07030105 | 2         | 1.23%   |
| 0x906e9    | 1         | 0.62%   |
| 0x806eb    | 1         | 0.62%   |
| 0x806d1    | 1         | 0.62%   |
| 0x706e5    | 1         | 0.62%   |
| 0x706a1    | 1         | 0.62%   |
| 0x6ec      | 1         | 0.62%   |
| 0x6e8      | 1         | 0.62%   |
| 0x6d8      | 1         | 0.62%   |
| 0x30673    | 1         | 0.62%   |
| 0x30661    | 1         | 0.62%   |
| 0x0a50000c | 1         | 0.62%   |
| 0x08108102 | 1         | 0.62%   |
| 0x0700010f | 1         | 0.62%   |
| 0x06006705 | 1         | 0.62%   |
| 0x05000119 | 1         | 0.62%   |
| 0x05000101 | 1         | 0.62%   |
| 0x03000027 | 1         | 0.62%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 27        | 16.98%  |
| Haswell       | 21        | 13.21%  |
| SandyBridge   | 18        | 11.32%  |
| Westmere      | 13        | 8.18%   |
| Skylake       | 12        | 7.55%   |
| Broadwell     | 11        | 6.92%   |
| Silvermont    | 9         | 5.66%   |
| Penryn        | 9         | 5.66%   |
| IvyBridge     | 9         | 5.66%   |
| TigerLake     | 7         | 4.4%    |
| P6            | 3         | 1.89%   |
| Bobcat        | 3         | 1.89%   |
| Puma          | 2         | 1.26%   |
| Icelake       | 2         | 1.26%   |
| Core          | 2         | 1.26%   |
| Bonnell       | 2         | 1.26%   |
| Unknown       | 2         | 1.26%   |
| Zen+          | 1         | 0.63%   |
| Zen 3         | 1         | 0.63%   |
| K10 Llano     | 1         | 0.63%   |
| Jaguar        | 1         | 0.63%   |
| Goldmont plus | 1         | 0.63%   |
| Excavator     | 1         | 0.63%   |
| CometLake     | 1         | 0.63%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 135       | 69.59%  |
| Nvidia | 37        | 19.07%  |
| AMD    | 22        | 11.34%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17        | 8.67%   |
| Intel UHD Graphics 620                                                                   | 11        | 5.61%   |
| Intel HD Graphics 5500                                                                   | 11        | 5.61%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 5.61%   |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 5.1%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 4.59%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 4.08%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 8         | 4.08%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 6         | 3.06%   |
| Intel HD Graphics 620                                                                    | 6         | 3.06%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 2.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 2.55%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 2.04%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 2.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 2.04%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 1.53%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 3         | 1.53%   |
| Intel HD Graphics 530                                                                    | 3         | 1.53%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.53%   |
| Nvidia TU117M [GeForce MX450]                                                            | 2         | 1.02%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 1.02%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 2         | 1.02%   |
| Nvidia GF119M [NVS 4200M]                                                                | 2         | 1.02%   |
| Nvidia GF119M [GeForce GT 520M]                                                          | 2         | 1.02%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.02%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 1.02%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.02%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 1.02%   |
| AMD Wrestler [Radeon HD 6290]                                                            | 2         | 1.02%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 1.02%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 2         | 1.02%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                                       | 1         | 0.51%   |
| Nvidia TU104M [GeForce RTX 2080 Mobile]                                                  | 1         | 0.51%   |
| Nvidia GT218M [GeForce G210M]                                                            | 1         | 0.51%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.51%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 0.51%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 0.51%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.51%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.51%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 1         | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 100       | 62.89%  |
| Intel + Nvidia | 30        | 18.87%  |
| 1 x AMD        | 17        | 10.69%  |
| 1 x Nvidia     | 7         | 4.4%    |
| Intel + AMD    | 5         | 3.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 136       | 83.44%  |
| Proprietary | 20        | 12.27%  |
| Unknown     | 7         | 4.29%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 118       | 72.39%  |
| 1.01-2.0   | 20        | 12.27%  |
| 0.01-0.5   | 15        | 9.2%    |
| 3.01-4.0   | 5         | 3.07%   |
| 0.51-1.0   | 4         | 2.45%   |
| 2.01-3.0   | 1         | 0.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 33        | 20.89%  |
| LG Display              | 32        | 20.25%  |
| Chimei Innolux          | 24        | 15.19%  |
| Samsung Electronics     | 21        | 13.29%  |
| BOE                     | 21        | 13.29%  |
| InfoVision              | 4         | 2.53%   |
| Hewlett-Packard         | 4         | 2.53%   |
| LG Philips              | 3         | 1.9%    |
| Lenovo                  | 3         | 1.9%    |
| Dell                    | 3         | 1.9%    |
| Chi Mei Optoelectronics | 3         | 1.9%    |
| Apple                   | 3         | 1.9%    |
| Sharp                   | 2         | 1.27%   |
| PANDA                   | 1         | 0.63%   |
| LGD                     | 1         | 0.63%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 3         | 1.9%    |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 3         | 1.9%    |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 1.9%    |
| Samsung Electronics LCD Monitor SEC3642 1366x768 344x194mm 15.5-inch  | 2         | 1.27%   |
| Samsung Electronics LCD Monitor SDC4D42 1366x768 309x174mm 14.0-inch  | 2         | 1.27%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 2         | 1.27%   |
| LG Display LCD Monitor LGD0504 1366x768 344x194mm 15.5-inch           | 2         | 1.27%   |
| LG Display LCD Monitor LGD03D9 1366x768 345x194mm 15.6-inch           | 2         | 1.27%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch            | 2         | 1.27%   |
| Dell 2208WFP DEL403B 1680x1050 473x296mm 22.0-inch                    | 2         | 1.27%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch       | 2         | 1.27%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 2         | 1.27%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.27%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch        | 2         | 1.27%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch         | 2         | 1.27%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 2         | 1.27%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 2         | 1.27%   |
| Sharp LCD Monitor SHP1516 3840x2400 336x210mm 15.6-inch               | 1         | 0.63%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 0.63%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch     | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC434E 1600x900 310x174mm 14.0-inch  | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC4143 1400x1050 286x214mm 14.1-inch | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC3959 1366x768 344x194mm 15.5-inch  | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC3846 1680x1050 331x207mm 15.4-inch | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 309x174mm 14.0-inch  | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch  | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC3051 1366x768 344x194mm 15.5-inch  | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SAM0FF0 3840x2160 950x540mm 43.0-inch | 1         | 0.63%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.63%   |
| LGD LCD Monitor 1920x1080                                             | 1         | 0.63%   |
| LG Philips LCD Monitor LPLE300 1280x800 331x207mm 15.4-inch           | 1         | 0.63%   |
| LG Philips LCD Monitor LPLBC00 1280x800 331x207mm 15.4-inch           | 1         | 0.63%   |
| LG Philips LCD Monitor LPL8D00 1280x800 304x190mm 14.1-inch           | 1         | 0.63%   |
| LG Display LCD Monitor LGDD801 1366x768 344x194mm 15.5-inch           | 1         | 0.63%   |
| LG Display LCD Monitor LGD059D 1920x1080 309x174mm 14.0-inch          | 1         | 0.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 77        | 50.33%  |
| 1920x1080 (FHD)    | 44        | 28.76%  |
| 1600x900 (HD+)     | 12        | 7.84%   |
| 1280x800 (WXGA)    | 6         | 3.92%   |
| 1680x1050 (WSXGA+) | 3         | 1.96%   |
| 1024x600           | 3         | 1.96%   |
| 3840x2160 (4K)     | 2         | 1.31%   |
| 3840x2400          | 1         | 0.65%   |
| 2880x1800          | 1         | 0.65%   |
| 2560x1600          | 1         | 0.65%   |
| 1920x1200 (WUXGA)  | 1         | 0.65%   |
| 1400x1050          | 1         | 0.65%   |
| 1024x768 (XGA)     | 1         | 0.65%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 93        | 58.86%  |
| 14      | 22        | 13.92%  |
| 13      | 13        | 8.23%   |
| 12      | 8         | 5.06%   |
| 17      | 5         | 3.16%   |
| 24      | 3         | 1.9%    |
| 18      | 3         | 1.9%    |
| 11      | 3         | 1.9%    |
| 23      | 2         | 1.27%   |
| 22      | 2         | 1.27%   |
| 10      | 2         | 1.27%   |
| 84      | 1         | 0.63%   |
| Unknown | 1         | 0.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 119       | 75.32%  |
| 201-300     | 19        | 12.03%  |
| 351-400     | 9         | 5.7%    |
| 501-600     | 5         | 3.16%   |
| 401-500     | 4         | 2.53%   |
| 1501-2000   | 1         | 0.63%   |
| Unknown     | 1         | 0.63%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 136       | 88.89%  |
| 16/10   | 14        | 9.15%   |
| 4/3     | 2         | 1.31%   |
| Unknown | 1         | 0.65%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 92        | 58.23%  |
| 81-90          | 30        | 18.99%  |
| 61-70          | 8         | 5.06%   |
| 201-250        | 5         | 3.16%   |
| 71-80          | 4         | 2.53%   |
| 121-130        | 4         | 2.53%   |
| 51-60          | 3         | 1.9%    |
| 141-150        | 3         | 1.9%    |
| 41-50          | 2         | 1.27%   |
| 251-300        | 2         | 1.27%   |
| More than 1000 | 1         | 0.63%   |
| 131-140        | 1         | 0.63%   |
| 111-120        | 1         | 0.63%   |
| 91-100         | 1         | 0.63%   |
| Unknown        | 1         | 0.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 70        | 44.59%  |
| 121-160       | 56        | 35.67%  |
| 51-100        | 21        | 13.38%  |
| 161-240       | 7         | 4.46%   |
| More than 240 | 2         | 1.27%   |
| Unknown       | 1         | 0.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 147       | 91.88%  |
| 2     | 9         | 5.63%   |
| 0     | 4         | 2.5%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 83        | 33.6%   |
| Realtek Semiconductor    | 74        | 29.96%  |
| Qualcomm Atheros         | 37        | 14.98%  |
| Broadcom                 | 28        | 11.34%  |
| Ralink Technology        | 5         | 2.02%   |
| Xiaomi                   | 3         | 1.21%   |
| Ralink                   | 3         | 1.21%   |
| Broadcom Limited         | 3         | 1.21%   |
| Lenovo                   | 2         | 0.81%   |
| TP-Link                  | 1         | 0.4%    |
| Sierra Wireless          | 1         | 0.4%    |
| Samsung Electronics      | 1         | 0.4%    |
| Qualcomm                 | 1         | 0.4%    |
| Nvidia                   | 1         | 0.4%    |
| Marvell Technology Group | 1         | 0.4%    |
| JMicron Technology       | 1         | 0.4%    |
| Dell                     | 1         | 0.4%    |
| Arduino SA               | 1         | 0.4%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 49        | 15.51%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 4.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 3.16%   |
| Intel Wireless 8265 / 8275                                        | 9         | 2.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 2.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 8         | 2.53%   |
| Intel Wireless 8260                                               | 8         | 2.53%   |
| Intel 82577LM Gigabit Network Connection                          | 8         | 2.53%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 2.22%   |
| Intel Wireless 7265                                               | 7         | 2.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 1.9%    |
| Intel Ethernet Connection I217-LM                                 | 6         | 1.9%    |
| Intel Centrino Advanced-N 6200                                    | 6         | 1.9%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 1.58%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 1.58%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 5         | 1.58%   |
| Intel Wireless 7260                                               | 5         | 1.58%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 1.58%   |
| Intel Centrino Advanced-N 6235                                    | 5         | 1.58%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 1.58%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 1.58%   |
| Ralink MT7601U Wireless Adapter                                   | 4         | 1.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 1.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.27%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 1.27%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.27%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 1.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 1.27%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 4         | 1.27%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.95%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.95%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.95%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 0.95%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.95%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.95%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.63%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 76        | 46.91%  |
| Qualcomm Atheros      | 32        | 19.75%  |
| Realtek Semiconductor | 21        | 12.96%  |
| Broadcom              | 20        | 12.35%  |
| Ralink Technology     | 5         | 3.09%   |
| Ralink                | 3         | 1.85%   |
| Broadcom Limited      | 3         | 1.85%   |
| TP-Link               | 1         | 0.62%   |
| Sierra Wireless       | 1         | 0.62%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 9         | 5.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 9         | 5.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 8         | 4.94%   |
| Intel Wireless 8260                                            | 8         | 4.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 7         | 4.32%   |
| Intel Wireless 7265                                            | 7         | 4.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 6         | 3.7%    |
| Intel Centrino Advanced-N 6200                                 | 6         | 3.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 3.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 5         | 3.09%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 5         | 3.09%   |
| Intel Wireless 7260                                            | 5         | 3.09%   |
| Intel Centrino Advanced-N 6235                                 | 5         | 3.09%   |
| Broadcom BCM43142 802.11b/g/n                                  | 5         | 3.09%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 3.09%   |
| Ralink MT7601U Wireless Adapter                                | 4         | 2.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 2.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 2.47%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 4         | 2.47%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 4         | 2.47%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 3         | 1.85%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 1.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 1.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.23%   |
| Intel Wireless 3165                                            | 2         | 1.23%   |
| Intel WiFi Link 5100                                           | 2         | 1.23%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 1.23%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 1.23%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 1.23%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 2         | 1.23%   |
| Broadcom BCM43225 802.11b/g/n                                  | 2         | 1.23%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 0.62%   |
| Sierra Wireless EM7455                                         | 1         | 0.62%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.62%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 0.62%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 0.62%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 0.62%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.62%   |
| Realtek 802.11ac NIC                                           | 1         | 0.62%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 68        | 45.03%  |
| Intel                    | 52        | 34.44%  |
| Qualcomm Atheros         | 11        | 7.28%   |
| Broadcom                 | 10        | 6.62%   |
| Xiaomi                   | 3         | 1.99%   |
| Lenovo                   | 2         | 1.32%   |
| Samsung Electronics      | 1         | 0.66%   |
| Qualcomm                 | 1         | 0.66%   |
| Nvidia                   | 1         | 0.66%   |
| Marvell Technology Group | 1         | 0.66%   |
| JMicron Technology       | 1         | 0.66%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 49        | 32.45%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 8.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 6.62%   |
| Intel 82577LM Gigabit Network Connection                          | 8         | 5.3%    |
| Intel Ethernet Connection I217-LM                                 | 6         | 3.97%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 3.31%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 2.65%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 2.65%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 2.65%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 1.99%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 1.99%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.99%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.32%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.32%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.32%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.32%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 2         | 1.32%   |
| Intel Ethernet Connection I217-V                                  | 2         | 1.32%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.32%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.32%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 1.32%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.66%   |
| Qualcomm Redmi Note 8                                             | 1         | 0.66%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.66%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.66%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.66%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.66%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 0.66%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.66%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.66%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.66%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.66%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.66%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.66%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                 | 1         | 0.66%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.66%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 0.66%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 1         | 0.66%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.66%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 157       | 51.82%  |
| Ethernet | 143       | 47.19%  |
| Modem    | 3         | 0.99%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 133       | 82.1%   |
| Ethernet | 29        | 17.9%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 139       | 86.88%  |
| 1     | 17        | 10.63%  |
| 0     | 3         | 1.88%   |
| 3     | 1         | 0.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 159       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 50        | 43.86%  |
| Realtek Semiconductor           | 16        | 14.04%  |
| Qualcomm Atheros Communications | 12        | 10.53%  |
| Broadcom                        | 8         | 7.02%   |
| Dell                            | 6         | 5.26%   |
| Lite-On Technology              | 5         | 4.39%   |
| Hewlett-Packard                 | 4         | 3.51%   |
| Ralink                          | 3         | 2.63%   |
| IMC Networks                    | 3         | 2.63%   |
| Apple                           | 2         | 1.75%   |
| Toshiba                         | 1         | 0.88%   |
| Foxconn International           | 1         | 0.88%   |
| Foxconn / Hon Hai               | 1         | 0.88%   |
| ASUSTek Computer                | 1         | 0.88%   |
| Alps Electric                   | 1         | 0.88%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 29        | 25.44%  |
| Realtek Bluetooth Radio                           | 10        | 8.77%   |
| Intel AX201 Bluetooth                             | 7         | 6.14%   |
| Qualcomm Atheros  Bluetooth Device                | 5         | 4.39%   |
| Intel Centrino Bluetooth Wireless Transceiver     | 5         | 4.39%   |
| Realtek  Bluetooth 4.2 Adapter                    | 4         | 3.51%   |
| Qualcomm Atheros AR3011 Bluetooth                 | 4         | 3.51%   |
| Dell DW375 Bluetooth Module                       | 4         | 3.51%   |
| Ralink RT3290 Bluetooth                           | 3         | 2.63%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 3         | 2.63%   |
| Intel Wireless-AC 3168 Bluetooth                  | 3         | 2.63%   |
| IMC Networks Bluetooth Device                     | 3         | 2.63%   |
| HP Broadcom 2070 Bluetooth Combo                  | 3         | 2.63%   |
| Realtek RTL8723B Bluetooth                        | 2         | 1.75%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 2         | 1.75%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device      | 2         | 1.75%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 2         | 1.75%   |
| Intel AX200 Bluetooth                             | 2         | 1.75%   |
| Broadcom HP Portable Bumble Bee                   | 2         | 1.75%   |
| Broadcom BCM43142A0 Bluetooth 4.0                 | 2         | 1.75%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]        | 2         | 1.75%   |
| Toshiba Bluetooth Device                          | 1         | 0.88%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 1         | 0.88%   |
| Intel Wireless-AC 9260 Bluetooth Adapter          | 1         | 0.88%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter  | 1         | 0.88%   |
| HP Bluetooth 1.2 Interface [Broadcom BCM2035]     | 1         | 0.88%   |
| Foxconn International BCM43142A0 Bluetooth module | 1         | 0.88%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller   | 1         | 0.88%   |
| Dell Wireless 360 Bluetooth                       | 1         | 0.88%   |
| Dell Wireless 350 Bluetooth                       | 1         | 0.88%   |
| Broadcom HP Portable SoftSailing                  | 1         | 0.88%   |
| Broadcom BCM43142 Bluetooth 4.0                   | 1         | 0.88%   |
| ASUS BT-270 Bluetooth Adapter                     | 1         | 0.88%   |
| Apple Built-in Bluetooth 2.0+EDR HCI              | 1         | 0.88%   |
| Apple Bluetooth Host Controller                   | 1         | 0.88%   |
| Alps Electric BCM2046 Bluetooth Device            | 1         | 0.88%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 144       | 77.84%  |
| Nvidia                           | 20        | 10.81%  |
| AMD                              | 16        | 8.65%   |
| Lenovo                           | 2         | 1.08%   |
| Silicon Integrated Systems [SiS] | 1         | 0.54%   |
| Logitech                         | 1         | 0.54%   |
| GN Netcom                        | 1         | 0.54%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 25        | 11.16%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 15        | 6.7%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 13        | 5.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 12        | 5.36%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 11        | 4.91%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 4.91%   |
| Intel Broadwell-U Audio Controller                                                                | 11        | 4.91%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 4.91%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 10        | 4.46%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 9         | 4.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 3.13%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 7         | 3.13%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 4         | 1.79%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 1.79%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.79%   |
| AMD FCH Azalia Controller                                                                         | 4         | 1.79%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.34%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 1.34%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.34%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.34%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.34%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 1.34%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.89%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.89%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 2         | 0.89%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.89%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 0.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.89%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.89%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.89%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 0.89%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.45%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.45%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.45%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.45%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.45%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.45%   |
| Nvidia Audio device                                                                               | 1         | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 28        | 28%     |
| SK hynix            | 25        | 25%     |
| Micron Technology   | 14        | 14%     |
| Kingston            | 13        | 13%     |
| Unknown             | 5         | 5%      |
| Elpida              | 3         | 3%      |
| Crucial             | 3         | 3%      |
| Ramaxel Technology  | 2         | 2%      |
| A-DATA Technology   | 2         | 2%      |
| Transcend           | 1         | 1%      |
| Toshiba             | 1         | 1%      |
| Sesame              | 1         | 1%      |
| Nanya Technology    | 1         | 1%      |
| ASint Technology    | 1         | 1%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 4         | 3.7%    |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s  | 4         | 3.7%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s    | 3         | 2.78%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 3         | 2.78%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 2         | 1.85%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 2         | 1.85%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s     | 2         | 1.85%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s     | 2         | 1.85%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s      | 2         | 1.85%   |
| Kingston RAM HP687515-H66-MCN 4096MB SODIMM DDR3 1600MT/s | 2         | 1.85%   |
| Kingston RAM HP16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s     | 2         | 1.85%   |
| Unknown RAM Module 4GB SODIMM DDR3                        | 1         | 0.93%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1066MT/s            | 1         | 0.93%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                 | 1         | 0.93%   |
| Unknown RAM Module 2048MB SODIMM DDR2                     | 1         | 0.93%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                  | 1         | 0.93%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s              | 1         | 0.93%   |
| Transcend RAM JM1333KSN-4G 4096MB SODIMM DDR3 1334MT/s    | 1         | 0.93%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s         | 1         | 0.93%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s           | 1         | 0.93%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s           | 1         | 0.93%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR 800MT/s   | 1         | 0.93%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 0.93%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 1         | 0.93%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 1         | 0.93%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 0.93%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1600MT/s    | 1         | 0.93%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s    | 1         | 0.93%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s    | 1         | 0.93%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s    | 1         | 0.93%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM 1334MT/s         | 1         | 0.93%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s    | 1         | 0.93%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1334MT/s    | 1         | 0.93%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s   | 1         | 0.93%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s    | 1         | 0.93%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 1         | 0.93%   |
| SK hynix RAM H9CCNNN8GTALAR-NUD 2GB LPDDR3 1600MT/s       | 1         | 0.93%   |
| Sesame RAM S939A2SGS-ITR 8192MB SODIMM DDR4 2667MT/s      | 1         | 0.93%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s               | 1         | 0.93%   |
| Samsung RAM M471B5773EB0-CK0 2GB SODIMM DDR3 1600MT/s     | 1         | 0.93%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 43        | 54.43%  |
| DDR4    | 24        | 30.38%  |
| DDR2    | 4         | 5.06%   |
| LPDDR4  | 3         | 3.8%    |
| LPDDR3  | 3         | 3.8%    |
| SDRAM   | 1         | 1.27%   |
| Unknown | 1         | 1.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 73        | 93.59%  |
| Row Of Chips | 3         | 3.85%   |
| DIMM         | 1         | 1.28%   |
| Unknown      | 1         | 1.28%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 39        | 46.43%  |
| 8192  | 28        | 33.33%  |
| 2048  | 11        | 13.1%   |
| 16384 | 5         | 5.95%   |
| 1024  | 1         | 1.19%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 30        | 34.88%  |
| 2667    | 14        | 16.28%  |
| 1334    | 11        | 12.79%  |
| 3200    | 7         | 8.14%   |
| 2133    | 4         | 4.65%   |
| 1333    | 4         | 4.65%   |
| 2400    | 3         | 3.49%   |
| 1066    | 2         | 2.33%   |
| 975     | 2         | 2.33%   |
| Unknown | 2         | 2.33%   |
| 4267    | 1         | 1.16%   |
| 4199    | 1         | 1.16%   |
| 3266    | 1         | 1.16%   |
| 1867    | 1         | 1.16%   |
| 1067    | 1         | 1.16%   |
| 800     | 1         | 1.16%   |
| 667     | 1         | 1.16%   |

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
| Chicony Electronics                    | 40        | 29.85%  |
| IMC Networks                           | 17        | 12.69%  |
| Cheng Uei Precision Industry (Foxlink) | 14        | 10.45%  |
| Realtek Semiconductor                  | 12        | 8.96%   |
| Suyin                                  | 8         | 5.97%   |
| Sunplus Innovation Technology          | 8         | 5.97%   |
| Lite-On Technology                     | 8         | 5.97%   |
| Microdia                               | 6         | 4.48%   |
| Ricoh                                  | 4         | 2.99%   |
| Quanta                                 | 4         | 2.99%   |
| Acer                                   | 3         | 2.24%   |
| Luxvisions Innotech Limited            | 2         | 1.49%   |
| Apple                                  | 2         | 1.49%   |
| Z-Star Microelectronics                | 1         | 0.75%   |
| Syntek                                 | 1         | 0.75%   |
| Sunplus Technology                     | 1         | 0.75%   |
| Silicon Motion                         | 1         | 0.75%   |
| ALi                                    | 1         | 0.75%   |
| Alcor Micro                            | 1         | 0.75%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 6         | 4.48%   |
| IMC Networks Integrated Camera                              | 5         | 3.73%   |
| Chicony HP Webcam [2 MP Macro]                              | 5         | 3.73%   |
| Chicony HP Webcam                                           | 4         | 2.99%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 4         | 2.99%   |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 3         | 2.24%   |
| Realtek USB Camera                                          | 3         | 2.24%   |
| Microdia Integrated Webcam                                  | 3         | 2.24%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 3         | 2.24%   |
| IMC Networks Lenovo EasyCamera                              | 3         | 2.24%   |
| Chicony HP HD Webcam                                        | 3         | 2.24%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 3         | 2.24%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 2         | 1.49%   |
| Sunplus HP Universal Camera                                 | 2         | 1.49%   |
| Ricoh Laptop_Integrated_Webcam_FHD                          | 2         | 1.49%   |
| Realtek Integrated_Webcam_HD                                | 2         | 1.49%   |
| Lite-On TOSHIBA Web Camera - HD                             | 2         | 1.49%   |
| Lite-On HP HD Webcam                                        | 2         | 1.49%   |
| Lite-On HP HD Camera                                        | 2         | 1.49%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 2         | 1.49%   |
| IMC Networks Integrated Webcam                              | 2         | 1.49%   |
| IMC Networks HP TrueVision HD Camera                        | 2         | 1.49%   |
| Chicony Lenovo Integrated Camera (0.3MP)                    | 2         | 1.49%   |
| Chicony Integrated Camera (1280x720@30)                     | 2         | 1.49%   |
| Chicony HP Wide Vision HD Camera                            | 2         | 1.49%   |
| Chicony HP HD Webcam [Fixed]                                | 2         | 1.49%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD     | 2         | 1.49%   |
| Z-Star Vimicro USB2.0 Camera                                | 1         | 0.75%   |
| Syntek Lenovo EasyCamera                                    | 1         | 0.75%   |
| Suyin WebCam                                                | 1         | 0.75%   |
| Suyin Sony Visual Communication Camera                      | 1         | 0.75%   |
| Suyin RGBIR Camera                                          | 1         | 0.75%   |
| Suyin Integrated_Webcam_HD                                  | 1         | 0.75%   |
| Suyin Integrated_Webcam_2M                                  | 1         | 0.75%   |
| Suyin HP Webcam-50                                          | 1         | 0.75%   |
| Sunplus 1.3M WebCam                                         | 1         | 0.75%   |
| Sunplus Integrated_Webcam_HD                                | 1         | 0.75%   |
| Sunplus HP Truevision HD                                    | 1         | 0.75%   |
| Sunplus Dell E5570 integrated webcam                        | 1         | 0.75%   |
| Silicon Motion WebCam SC-0311139N                           | 1         | 0.75%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 25        | 69.44%  |
| Synaptics                  | 5         | 13.89%  |
| Elan Microelectronics      | 4         | 11.11%  |
| Upek                       | 1         | 2.78%   |
| Shenzhen Goodix Technology | 1         | 2.78%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 10        | 27.78%  |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 11.11%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 11.11%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 8.33%   |
| Validity Sensors VFS491                                                    | 2         | 5.56%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 5.56%   |
| Elan ELAN:Fingerprint                                                      | 2         | 5.56%   |
| Elan ELAN:ARM-M4                                                           | 2         | 5.56%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2.78%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.78%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.78%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 2.78%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 2.78%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 2.78%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 2.78%   |

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
| 0     | 90        | 54.88%  |
| 1     | 57        | 34.76%  |
| 2     | 16        | 9.76%   |
| 3     | 1         | 0.61%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 36        | 39.56%  |
| Chipcard                 | 19        | 20.88%  |
| Graphics card            | 15        | 16.48%  |
| Storage                  | 5         | 5.49%   |
| Net/wireless             | 5         | 5.49%   |
| Bluetooth                | 3         | 3.3%    |
| Net/ethernet             | 2         | 2.2%    |
| Communication controller | 2         | 2.2%    |
| Unassigned class         | 1         | 1.1%    |
| Sound                    | 1         | 1.1%    |
| Modem                    | 1         | 1.1%    |
| Camera                   | 1         | 1.1%    |

