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

Total: 257

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | X751LK                      | [f312f303e0](https://linux-hardware.org/?probe=f312f303e0) | Feb 26, 2023 |
| HP            | Pavilion g6                 | [39b27e9850](https://linux-hardware.org/?probe=39b27e9850) | Feb 19, 2023 |
| Dell          | Latitude E7450              | [16f40c9f6a](https://linux-hardware.org/?probe=16f40c9f6a) | Feb 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [b82ad16853](https://linux-hardware.org/?probe=b82ad16853) | Feb 08, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [76dd43711a](https://linux-hardware.org/?probe=76dd43711a) | Feb 08, 2023 |
| Toshiba       | Satellite C855-1LG          | [26ce54002a](https://linux-hardware.org/?probe=26ce54002a) | Feb 05, 2023 |
| Dell          | Latitude 3500               | [79cdb991bf](https://linux-hardware.org/?probe=79cdb991bf) | Feb 03, 2023 |
| Lenovo        | V310-15IKB 80T3             | [a39fb673c7](https://linux-hardware.org/?probe=a39fb673c7) | Feb 03, 2023 |
| Dell          | Latitude D630               | [aa435d7701](https://linux-hardware.org/?probe=aa435d7701) | Feb 03, 2023 |
| Dell          | Latitude D630               | [b191402036](https://linux-hardware.org/?probe=b191402036) | Feb 03, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [b33f2d5606](https://linux-hardware.org/?probe=b33f2d5606) | Jan 28, 2023 |
| Dell          | Latitude E6410              | [854634fb32](https://linux-hardware.org/?probe=854634fb32) | Jan 24, 2023 |
| Dell          | Latitude E6410              | [a5edbef8d2](https://linux-hardware.org/?probe=a5edbef8d2) | Jan 24, 2023 |
| Fujitsu Si... | AMILO Xi 3650               | [1f238129d8](https://linux-hardware.org/?probe=1f238129d8) | Jan 12, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | [c5379f6dc1](https://linux-hardware.org/?probe=c5379f6dc1) | Jan 12, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | [2c092397ea](https://linux-hardware.org/?probe=2c092397ea) | Jan 05, 2023 |
| Dell          | Latitude 5510               | [68e4810231](https://linux-hardware.org/?probe=68e4810231) | Dec 24, 2022 |
| SINTRONES     | AMB-5000G1                  | [3f9a3badb0](https://linux-hardware.org/?probe=3f9a3badb0) | Dec 17, 2022 |
| SINTRONES     | AMB-5000G1                  | [b1738a6528](https://linux-hardware.org/?probe=b1738a6528) | Dec 17, 2022 |
| Dell          | Latitude D820               | [29df917188](https://linux-hardware.org/?probe=29df917188) | Dec 16, 2022 |
| Dell          | Latitude D820               | [27f19eafce](https://linux-hardware.org/?probe=27f19eafce) | Dec 16, 2022 |
| Dell          | Latitude E7250              | [3e40466ae4](https://linux-hardware.org/?probe=3e40466ae4) | Dec 13, 2022 |
| HP            | Pavilion 15                 | [5d88eed564](https://linux-hardware.org/?probe=5d88eed564) | Dec 13, 2022 |
| Toshiba       | Satellite L50-B             | [5bbe558b2f](https://linux-hardware.org/?probe=5bbe558b2f) | Dec 05, 2022 |
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
| Ubuntu 20.04       | 34        | 18.18%  |
| Ubuntu 18.04       | 13        | 6.95%   |
| KDE neon 20.04     | 10        | 5.35%   |
| Ubuntu 22.04       | 9         | 4.81%   |
| OpenMandriva 4.3   | 8         | 4.28%   |
| Debian 11          | 8         | 4.28%   |
| OpenMandriva 4.2   | 6         | 3.21%   |
| Linux Mint 20.2    | 6         | 3.21%   |
| Zorin 16           | 5         | 2.67%   |
| Ubuntu Unity 16.04 | 4         | 2.14%   |
| Ubuntu 20.10       | 4         | 2.14%   |
| Ubuntu 19.10       | 4         | 2.14%   |
| OpenMandriva 23.01 | 4         | 2.14%   |
| Linux Mint 20.3    | 4         | 2.14%   |
| Arch               | 4         | 2.14%   |
| Pop!_OS 22.04      | 3         | 1.6%    |
| Manjaro            | 3         | 1.6%    |
| ArcoLinux Rolling  | 3         | 1.6%    |
| Xubuntu 20.04      | 2         | 1.07%   |
| Void Linux         | 2         | 1.07%   |
| Ubuntu 21.10       | 2         | 1.07%   |
| Ubuntu 21.04       | 2         | 1.07%   |
| Pop!_OS 21.10      | 2         | 1.07%   |
| Linux Mint 21.1    | 2         | 1.07%   |
| Linux Mint 21      | 2         | 1.07%   |
| Linux Mint 19.3    | 2         | 1.07%   |
| Kali 2019.4        | 2         | 1.07%   |
| Fedora 37          | 2         | 1.07%   |
| Fedora 36          | 2         | 1.07%   |
| Zorin 15           | 1         | 0.53%   |
| Xero Rolling       | 1         | 0.53%   |
| Ubuntu Unity 20.04 | 1         | 0.53%   |
| Ubuntu MATE 22.10  | 1         | 0.53%   |
| Ubuntu MATE 20.04  | 1         | 0.53%   |
| Ubuntu 19.04       | 1         | 0.53%   |
| Ubuntu 16.04       | 1         | 0.53%   |
| Ubuntu             | 1         | 0.53%   |
| RHEL 8             | 1         | 0.53%   |
| Pop!_OS 20.10      | 1         | 0.53%   |
| Parrot 5.0         | 1         | 0.53%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 65        | 36.11%  |
| OpenMandriva | 18        | 10%     |
| Linux Mint   | 17        | 9.44%   |
| KDE neon     | 10        | 5.56%   |
| Debian       | 9         | 5%      |
| Zorin        | 6         | 3.33%   |
| Pop!_OS      | 6         | 3.33%   |
| Manjaro      | 6         | 3.33%   |
| Kali         | 6         | 3.33%   |
| Fedora       | 6         | 3.33%   |
| Ubuntu Unity | 5         | 2.78%   |
| Arch         | 4         | 2.22%   |
| Endless      | 3         | 1.67%   |
| ArcoLinux    | 3         | 1.67%   |
| Xubuntu      | 2         | 1.11%   |
| Void Linux   | 2         | 1.11%   |
| Ubuntu MATE  | 2         | 1.11%   |
| Elementary   | 2         | 1.11%   |
| Xero         | 1         | 0.56%   |
| RHEL         | 1         | 0.56%   |
| Parrot       | 1         | 0.56%   |
| openSUSE     | 1         | 0.56%   |
| Nobara       | 1         | 0.56%   |
| EndeavourOS  | 1         | 0.56%   |
| CentOS       | 1         | 0.56%   |
| BunsenLabs   | 1         | 0.56%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 8         | 4%      |
| 5.10.14-desktop-1omv4002 | 6         | 3%      |
| 5.13.0-40-generic        | 5         | 2.5%    |
| 6.1.1-desktop-1omv2290   | 4         | 2%      |
| 5.8.0-43-generic         | 4         | 2%      |
| 5.4.0-58-generic         | 4         | 2%      |
| 5.4.0-48-generic         | 4         | 2%      |
| 5.4.0-42-generic         | 3         | 1.5%    |
| 5.3.0-40-generic         | 3         | 1.5%    |
| 5.17.5-76051705-generic  | 3         | 1.5%    |
| 5.13.0-27-generic        | 3         | 1.5%    |
| 5.11.0-37-generic        | 3         | 1.5%    |
| 5.8.0-48-generic         | 2         | 1%      |
| 5.8.0-38-generic         | 2         | 1%      |
| 5.8.0-33-generic         | 2         | 1%      |
| 5.4.0-96-generic         | 2         | 1%      |
| 5.4.0-88-generic         | 2         | 1%      |
| 5.4.0-65-generic         | 2         | 1%      |
| 5.4.0-37-generic         | 2         | 1%      |
| 5.4.0-33-generic         | 2         | 1%      |
| 5.4.0-29-generic         | 2         | 1%      |
| 5.3.0-kali2-686-pae      | 2         | 1%      |
| 5.3.0-51-generic         | 2         | 1%      |
| 5.3.0-28-generic         | 2         | 1%      |
| 5.18.19_1                | 2         | 1%      |
| 5.15.0-58-generic        | 2         | 1%      |
| 5.15.0-53-generic        | 2         | 1%      |
| 5.15.0-50-generic        | 2         | 1%      |
| 5.15.0-46-generic        | 2         | 1%      |
| 5.14.14-arch1-1          | 2         | 1%      |
| 5.13.0-19-generic        | 2         | 1%      |
| 5.11.0-46-generic        | 2         | 1%      |
| 5.11.0-36-generic        | 2         | 1%      |
| 5.0.0-23-generic         | 2         | 1%      |
| 4.15.0-112-generic       | 2         | 1%      |
| 6.1.7-200.fc37.x86_64    | 1         | 0.5%    |
| 6.1.6-060106-generic     | 1         | 0.5%    |
| 6.0.14-300.fc37.x86_64   | 1         | 0.5%    |
| 6.0.0-kali6-amd64        | 1         | 0.5%    |
| 5.8.15-201.fc32.x86_64   | 1         | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 34        | 18.28%  |
| 5.15.0  | 16        | 8.6%    |
| 5.8.0   | 14        | 7.53%   |
| 4.15.0  | 12        | 6.45%   |
| 5.13.0  | 11        | 5.91%   |
| 5.11.0  | 11        | 5.91%   |
| 5.3.0   | 10        | 5.38%   |
| 5.10.0  | 9         | 4.84%   |
| 5.16.7  | 8         | 4.3%    |
| 5.10.14 | 6         | 3.23%   |
| 5.0.0   | 6         | 3.23%   |
| 6.1.1   | 4         | 2.15%   |
| 5.17.5  | 3         | 1.61%   |
| 4.18.0  | 3         | 1.61%   |
| 5.19.0  | 2         | 1.08%   |
| 5.18.19 | 2         | 1.08%   |
| 5.16.0  | 2         | 1.08%   |
| 5.14.14 | 2         | 1.08%   |
| 4.19.0  | 2         | 1.08%   |
| 6.1.7   | 1         | 0.54%   |
| 6.1.6   | 1         | 0.54%   |
| 6.0.14  | 1         | 0.54%   |
| 6.0.0   | 1         | 0.54%   |
| 5.8.15  | 1         | 0.54%   |
| 5.8.1   | 1         | 0.54%   |
| 5.7.15  | 1         | 0.54%   |
| 5.19.9  | 1         | 0.54%   |
| 5.19.16 | 1         | 0.54%   |
| 5.19.14 | 1         | 0.54%   |
| 5.18.18 | 1         | 0.54%   |
| 5.18.12 | 1         | 0.54%   |
| 5.17.9  | 1         | 0.54%   |
| 5.17.15 | 1         | 0.54%   |
| 5.17.1  | 1         | 0.54%   |
| 5.16.2  | 1         | 0.54%   |
| 5.15.60 | 1         | 0.54%   |
| 5.15.4  | 1         | 0.54%   |
| 5.15.23 | 1         | 0.54%   |
| 5.15.21 | 1         | 0.54%   |
| 5.15.15 | 1         | 0.54%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 34        | 18.28%  |
| 5.15    | 22        | 11.83%  |
| 5.8     | 16        | 8.6%    |
| 5.10    | 16        | 8.6%    |
| 5.11    | 13        | 6.99%   |
| 5.13    | 12        | 6.45%   |
| 4.15    | 12        | 6.45%   |
| 5.16    | 11        | 5.91%   |
| 5.3     | 10        | 5.38%   |
| 6.1     | 6         | 3.23%   |
| 5.17    | 6         | 3.23%   |
| 5.0     | 6         | 3.23%   |
| 5.19    | 5         | 2.69%   |
| 5.18    | 4         | 2.15%   |
| 5.14    | 3         | 1.61%   |
| 4.18    | 3         | 1.61%   |
| 6.0     | 2         | 1.08%   |
| 4.19    | 2         | 1.08%   |
| 5.7     | 1         | 0.54%   |
| 4.4     | 1         | 0.54%   |
| 4.13    | 1         | 0.54%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 170       | 96.05%  |
| i686   | 7         | 3.95%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 89        | 49.17%  |
| KDE5            | 33        | 18.23%  |
| Unknown         | 14        | 7.73%   |
| X-Cinnamon      | 13        | 7.18%   |
| XFCE            | 10        | 5.52%   |
| KDE             | 6         | 3.31%   |
| Unity           | 5         | 2.76%   |
| MATE            | 3         | 1.66%   |
| Pantheon        | 2         | 1.1%    |
| Cinnamon        | 2         | 1.1%    |
| xmonad          | 1         | 0.55%   |
| i3              | 1         | 0.55%   |
| GNOME Flashback | 1         | 0.55%   |
| Budgie          | 1         | 0.55%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 146       | 80.66%  |
| Wayland | 27        | 14.92%  |
| Unknown | 7         | 3.87%   |
| Tty     | 1         | 0.55%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 91        | 49.46%  |
| SDDM    | 31        | 16.85%  |
| GDM     | 27        | 14.67%  |
| LightDM | 17        | 9.24%   |
| GDM3    | 15        | 8.15%   |
| TDM     | 3         | 1.63%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 99        | 55.62%  |
| fr_FR   | 50        | 28.09%  |
| Unknown | 12        | 6.74%   |
| en_GB   | 7         | 3.93%   |
| de_DE   | 3         | 1.69%   |
| fr_MA   | 1         | 0.56%   |
| fr_BE   | 1         | 0.56%   |
| es_ES   | 1         | 0.56%   |
| en_AG   | 1         | 0.56%   |
| C       | 1         | 0.56%   |
| ar_MA   | 1         | 0.56%   |
| ar_EG   | 1         | 0.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 107       | 60.11%  |
| EFI  | 71        | 39.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 144       | 81.36%  |
| Overlay | 20        | 11.3%   |
| Btrfs   | 9         | 5.08%   |
| Xfs     | 2         | 1.13%   |
| Unknown | 2         | 1.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 92        | 51.69%  |
| GPT     | 53        | 29.78%  |
| MBR     | 33        | 18.54%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 153       | 86.44%  |
| Yes       | 24        | 13.56%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 115       | 64.61%  |
| Yes       | 63        | 35.39%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 57        | 32.2%   |
| Lenovo              | 31        | 17.51%  |
| Dell                | 31        | 17.51%  |
| ASUSTek Computer    | 14        | 7.91%   |
| Toshiba             | 8         | 4.52%   |
| Acer                | 7         | 3.95%   |
| Sony                | 3         | 1.69%   |
| Packard Bell        | 3         | 1.69%   |
| Apple               | 3         | 1.69%   |
| Timi                | 2         | 1.13%   |
| Samsung Electronics | 2         | 1.13%   |
| eMachines           | 2         | 1.13%   |
| Unknown             | 2         | 1.13%   |
| TUXEDO              | 1         | 0.56%   |
| TrekStor            | 1         | 0.56%   |
| SINTRONES           | 1         | 0.56%   |
| Razer               | 1         | 0.56%   |
| Medion              | 1         | 0.56%   |
| Mediacom            | 1         | 0.56%   |
| GPD                 | 1         | 0.56%   |
| Google              | 1         | 0.56%   |
| Gigabyte Technology | 1         | 0.56%   |
| Fujitsu Siemens     | 1         | 0.56%   |
| Clevo               | 1         | 0.56%   |
| Casper              | 1         | 0.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| HP Laptop 15-dw3xxx                        | 3         | 1.69%   |
| HP EliteBook 8440p                         | 3         | 1.69%   |
| HP EliteBook 840 G2                        | 3         | 1.69%   |
| Unknown                                    | 3         | 1.69%   |
| Timi TM1701                                | 2         | 1.13%   |
| Lenovo ThinkBook 15 G2 ITL 20VE            | 2         | 1.13%   |
| Lenovo IdeaPad L3 15IML05 81Y3             | 2         | 1.13%   |
| HP ZBook 15                                | 2         | 1.13%   |
| HP ProBook 650 G1                          | 2         | 1.13%   |
| HP ProBook 6470b                           | 2         | 1.13%   |
| HP Pavilion g6                             | 2         | 1.13%   |
| HP Notebook                                | 2         | 1.13%   |
| HP EliteBook 8460p                         | 2         | 1.13%   |
| HP 250 G5 Notebook PC                      | 2         | 1.13%   |
| Dell Latitude E6520                        | 2         | 1.13%   |
| Dell Latitude E6410                        | 2         | 1.13%   |
| ASUS X540LA                                | 2         | 1.13%   |
| Acer Aspire ES1-523                        | 2         | 1.13%   |
| TUXEDO N13xWU                              | 1         | 0.56%   |
| TrekStor Surfbook W2                       | 1         | 0.56%   |
| Toshiba Satellite Pro C650                 | 1         | 0.56%   |
| Toshiba Satellite L750                     | 1         | 0.56%   |
| Toshiba Satellite L50-B                    | 1         | 0.56%   |
| Toshiba Satellite L50-A-1EL                | 1         | 0.56%   |
| Toshiba Satellite L50-A-1DG                | 1         | 0.56%   |
| Toshiba Satellite C855-2CF                 | 1         | 0.56%   |
| Toshiba Satellite C855-1LG                 | 1         | 0.56%   |
| Toshiba Satellite C660                     | 1         | 0.56%   |
| Sony VPCEH1L8E                             | 1         | 0.56%   |
| Sony VGN-FW11L                             | 1         | 0.56%   |
| Sony SVE14122CAW                           | 1         | 0.56%   |
| SINTRONES AMB-5000G1                       | 1         | 0.56%   |
| Samsung 355V4C/356V4C/3445VC/3545VC        | 1         | 0.56%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 0.56%   |
| Razer Blade Pro 17 (2019)                  | 1         | 0.56%   |
| Packard Bell EasyNote TS44HR               | 1         | 0.56%   |
| Packard Bell EasyNote TS11HR               | 1         | 0.56%   |
| Packard Bell EasyNote TK85                 | 1         | 0.56%   |
| Medion P7615                               | 1         | 0.56%   |
| Mediacom WinPad 11,6 FullHD- WPU11         | 1         | 0.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Dell Latitude         | 25        | 14.12%  |
| Lenovo ThinkPad       | 18        | 10.17%  |
| HP EliteBook          | 16        | 9.04%   |
| HP Pavilion           | 9         | 5.08%   |
| Toshiba Satellite     | 8         | 4.52%   |
| HP ProBook            | 8         | 4.52%   |
| HP Laptop             | 8         | 4.52%   |
| Acer Aspire           | 5         | 2.82%   |
| Lenovo IdeaPad        | 4         | 2.26%   |
| HP 250                | 4         | 2.26%   |
| Packard Bell EasyNote | 3         | 1.69%   |
| Lenovo ThinkBook      | 3         | 1.69%   |
| HP ZBook              | 3         | 1.69%   |
| Unknown               | 3         | 1.69%   |
| Timi TM1701           | 2         | 1.13%   |
| HP Notebook           | 2         | 1.13%   |
| HP Compaq             | 2         | 1.13%   |
| Dell Precision        | 2         | 1.13%   |
| Dell Inspiron         | 2         | 1.13%   |
| ASUS X540LA           | 2         | 1.13%   |
| TUXEDO N13xWU         | 1         | 0.56%   |
| TrekStor Surfbook     | 1         | 0.56%   |
| Sony VPCEH1L8E        | 1         | 0.56%   |
| Sony VGN-FW11L        | 1         | 0.56%   |
| Sony SVE14122CAW      | 1         | 0.56%   |
| SINTRONES AMB-5000G1  | 1         | 0.56%   |
| Samsung 355V4C        | 1         | 0.56%   |
| Samsung 300E4A        | 1         | 0.56%   |
| Razer Blade           | 1         | 0.56%   |
| Medion P7615          | 1         | 0.56%   |
| Mediacom WinPad       | 1         | 0.56%   |
| Lenovo Z70-80         | 1         | 0.56%   |
| Lenovo V310-15IKB     | 1         | 0.56%   |
| Lenovo S21e-20        | 1         | 0.56%   |
| Lenovo IdeaPadFlex    | 1         | 0.56%   |
| Lenovo G50-70         | 1         | 0.56%   |
| Lenovo B50-30         | 1         | 0.56%   |
| HP Presario           | 1         | 0.56%   |
| HP 650                | 1         | 0.56%   |
| HP 255                | 1         | 0.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 20        | 11.3%   |
| 2011 | 19        | 10.73%  |
| 2016 | 16        | 9.04%   |
| 2010 | 16        | 9.04%   |
| 2018 | 15        | 8.47%   |
| 2015 | 14        | 7.91%   |
| 2014 | 13        | 7.34%   |
| 2020 | 12        | 6.78%   |
| 2012 | 11        | 6.21%   |
| 2017 | 10        | 5.65%   |
| 2019 | 9         | 5.08%   |
| 2021 | 7         | 3.95%   |
| 2009 | 5         | 2.82%   |
| 2008 | 4         | 2.26%   |
| 2007 | 3         | 1.69%   |
| 2006 | 2         | 1.13%   |
| 2005 | 1         | 0.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 177       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 169       | 93.89%  |
| Enabled  | 11        | 6.11%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 176       | 99.44%  |
| Yes  | 1         | 0.56%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 64        | 36.16%  |
| 3.01-4.0   | 50        | 28.25%  |
| 8.01-16.0  | 21        | 11.86%  |
| 16.01-24.0 | 19        | 10.73%  |
| 1.01-2.0   | 12        | 6.78%   |
| 32.01-64.0 | 3         | 1.69%   |
| 24.01-32.0 | 3         | 1.69%   |
| 2.01-3.0   | 3         | 1.69%   |
| 0.51-1.0   | 2         | 1.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 78        | 41.05%  |
| 2.01-3.0  | 60        | 31.58%  |
| 4.01-8.0  | 23        | 12.11%  |
| 3.01-4.0  | 20        | 10.53%  |
| 0.51-1.0  | 8         | 4.21%   |
| 8.01-16.0 | 1         | 0.53%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 151       | 84.36%  |
| 2      | 24        | 13.41%  |
| 3      | 4         | 2.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 89        | 50.28%  |
| No        | 88        | 49.72%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 161       | 90.96%  |
| No        | 16        | 9.04%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 175       | 98.31%  |
| No        | 3         | 1.69%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 128       | 71.51%  |
| No        | 51        | 28.49%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Morocco | 177       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Casablanca       | 44        | 23.78%  |
| Rabat            | 19        | 10.27%  |
| Marrakesh        | 19        | 10.27%  |
| Agadir           | 15        | 8.11%   |
| Kenitra          | 11        | 5.95%   |
| Fes              | 11        | 5.95%   |
| Salé            | 8         | 4.32%   |
| Oujda            | 7         | 3.78%   |
| Khouribga        | 7         | 3.78%   |
| Tangier          | 6         | 3.24%   |
| Meknes           | 5         | 2.7%    |
| Nador            | 4         | 2.16%   |
| Tiznit           | 3         | 1.62%   |
| Beni Mellal      | 3         | 1.62%   |
| Temara           | 2         | 1.08%   |
| Taza             | 2         | 1.08%   |
| Guelmim          | 2         | 1.08%   |
| El Jadida        | 2         | 1.08%   |
| Youssoufia       | 1         | 0.54%   |
| Tétouan         | 1         | 0.54%   |
| Targuist         | 1         | 0.54%   |
| Taourirt         | 1         | 0.54%   |
| Skhirate         | 1         | 0.54%   |
| Sidi Kacem       | 1         | 0.54%   |
| Safi             | 1         | 0.54%   |
| Mohammedia       | 1         | 0.54%   |
| Midelt           | 1         | 0.54%   |
| Ksar El Kebir    | 1         | 0.54%   |
| Karia Ba Mohamed | 1         | 0.54%   |
| Berkane          | 1         | 0.54%   |
| Al Aaroui        | 1         | 0.54%   |
| Agdz             | 1         | 0.54%   |
| Agdal            | 1         | 0.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 36        | 44     | 18.18%  |
| Toshiba             | 28        | 36     | 14.14%  |
| Samsung Electronics | 26        | 33     | 13.13%  |
| WDC                 | 24        | 30     | 12.12%  |
| Unknown             | 10        | 14     | 5.05%   |
| Hitachi             | 8         | 9      | 4.04%   |
| SanDisk             | 7         | 7      | 3.54%   |
| HGST                | 7         | 7      | 3.54%   |
| SK hynix            | 5         | 5      | 2.53%   |
| Kingston            | 5         | 6      | 2.53%   |
| Intel               | 5         | 6      | 2.53%   |
| Apple               | 5         | 5      | 2.53%   |
| KIOXIA              | 3         | 3      | 1.52%   |
| PNY                 | 2         | 3      | 1.01%   |
| LITEON              | 2         | 2      | 1.01%   |
| KingDian            | 2         | 5      | 1.01%   |
| GOODRAM             | 2         | 2      | 1.01%   |
| Fujitsu             | 2         | 2      | 1.01%   |
| Crucial             | 2         | 2      | 1.01%   |
| China               | 2         | 3      | 1.01%   |
| TwinMOS             | 1         | 1      | 0.51%   |
| RCESSD              | 1         | 1      | 0.51%   |
| Phison              | 1         | 1      | 0.51%   |
| Micron Technology   | 1         | 1      | 0.51%   |
| LITEONIT            | 1         | 1      | 0.51%   |
| KingSpec            | 1         | 1      | 0.51%   |
| KingFast            | 1         | 2      | 0.51%   |
| Indilinx            | 1         | 1      | 0.51%   |
| IBM/Hitachi         | 1         | 1      | 0.51%   |
| Hewlett-Packard     | 1         | 1      | 0.51%   |
| BIWIN               | 1         | 1      | 0.51%   |
| Apacer              | 1         | 1      | 0.51%   |
| A-DATA Technology   | 1         | 1      | 0.51%   |
| 2.5"                | 1         | 1      | 0.51%   |
| Unknown             | 1         | 1      | 0.51%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB        | 5         | 2.43%   |
| Seagate ST1000LM035-1RK172 1TB         | 5         | 2.43%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 5         | 2.43%   |
| Samsung NVMe SSD Drive 512GB           | 4         | 1.94%   |
| Toshiba MQ04ABF100 1TB                 | 3         | 1.46%   |
| Toshiba MQ01ACF050 500GB               | 3         | 1.46%   |
| Toshiba MQ01ABF050 500GB               | 3         | 1.46%   |
| Toshiba MQ01ABD050 500GB               | 3         | 1.46%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 3         | 1.46%   |
| HGST HTS545050A7E680 500GB             | 3         | 1.46%   |
| WDC WD5000LPCX-80VHAT1 500GB           | 2         | 0.97%   |
| WDC WD5000LPCX-60VHAT0 500GB           | 2         | 0.97%   |
| WDC WD1600BEVT-22ZCT0 160GB            | 2         | 0.97%   |
| Unknown MMC Card  32GB                 | 2         | 0.97%   |
| Unknown MMC Card  16GB                 | 2         | 0.97%   |
| Toshiba MQ01ABD100 1TB                 | 2         | 0.97%   |
| Seagate ST9500325AS 500GB              | 2         | 0.97%   |
| Seagate ST500VT000-1DK142 500GB        | 2         | 0.97%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 2         | 0.97%   |
| Seagate ST500LM000-1EJ162 500GB        | 2         | 0.97%   |
| Samsung MZVLW256HEHP-000L7 256GB       | 2         | 0.97%   |
| Hitachi HTS723232A7A364 320GB          | 2         | 0.97%   |
| Hitachi HTS542525K9A300 250GB          | 2         | 0.97%   |
| HGST HTS725050A7E630 500GB             | 2         | 0.97%   |
| WDC WDS256G1X0C-00ENX0 256GB           | 1         | 0.49%   |
| WDC WD5000LPCX-60VHAT1 500GB           | 1         | 0.49%   |
| WDC WD5000BPVT-22HXZT1 500GB           | 1         | 0.49%   |
| WDC WD3200BUCT-63TWBY0 320GB           | 1         | 0.49%   |
| WDC WD3200BPVT-22ZEST0 320GB           | 1         | 0.49%   |
| WDC WD3200BEVT-60ZCT1 320GB            | 1         | 0.49%   |
| WDC WD2500BPVT-22ZEST0 250GB           | 1         | 0.49%   |
| WDC WD2500BEVT-22A23T0 250GB           | 1         | 0.49%   |
| WDC WD2500BEKT-60V5T1 250GB            | 1         | 0.49%   |
| WDC WD2500BEKT-60A25T1 250GB           | 1         | 0.49%   |
| WDC WD1600BEVS-60VAT0 160GB            | 1         | 0.49%   |
| WDC WD10SPZX-60Z10T0 1TB               | 1         | 0.49%   |
| WDC WD10SPZX-08Z10 1TB                 | 1         | 0.49%   |
| WDC WD10SPCX-24HWST0 1TB               | 1         | 0.49%   |
| WDC WD10JUCT-63CYNY0 1TB               | 1         | 0.49%   |
| WDC WD10JPVX-60JC3T0 1TB               | 1         | 0.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 36        | 44     | 34.95%  |
| Toshiba             | 24        | 28     | 23.3%   |
| WDC                 | 21        | 27     | 20.39%  |
| Hitachi             | 8         | 9      | 7.77%   |
| HGST                | 7         | 7      | 6.8%    |
| Samsung Electronics | 2         | 2      | 1.94%   |
| Fujitsu             | 2         | 2      | 1.94%   |
| Apple               | 2         | 2      | 1.94%   |
| IBM/Hitachi         | 1         | 1      | 0.97%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 7         | 7      | 13.73%  |
| Samsung Electronics | 7         | 10     | 13.73%  |
| Kingston            | 4         | 5      | 7.84%   |
| SK hynix            | 3         | 3      | 5.88%   |
| PNY                 | 2         | 3      | 3.92%   |
| LITEON              | 2         | 2      | 3.92%   |
| KingDian            | 2         | 5      | 3.92%   |
| Intel               | 2         | 3      | 3.92%   |
| GOODRAM             | 2         | 2      | 3.92%   |
| Crucial             | 2         | 2      | 3.92%   |
| China               | 2         | 3      | 3.92%   |
| Apple               | 2         | 2      | 3.92%   |
| TwinMOS             | 1         | 1      | 1.96%   |
| Toshiba             | 1         | 1      | 1.96%   |
| RCESSD              | 1         | 1      | 1.96%   |
| Micron Technology   | 1         | 1      | 1.96%   |
| LITEONIT            | 1         | 1      | 1.96%   |
| KingSpec            | 1         | 1      | 1.96%   |
| KingFast            | 1         | 1      | 1.96%   |
| Indilinx            | 1         | 1      | 1.96%   |
| Hewlett-Packard     | 1         | 1      | 1.96%   |
| BIWIN               | 1         | 1      | 1.96%   |
| Apacer              | 1         | 1      | 1.96%   |
| A-DATA Technology   | 1         | 1      | 1.96%   |
| 2.5"                | 1         | 1      | 1.96%   |
| Unknown             | 1         | 1      | 1.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 102       | 122    | 52.31%  |
| SSD     | 50        | 61     | 25.64%  |
| NVMe    | 32        | 42     | 16.41%  |
| MMC     | 10        | 14     | 5.13%   |
| Unknown | 1         | 1      | 0.51%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 143       | 184    | 77.3%   |
| NVMe | 32        | 42     | 17.3%   |
| MMC  | 10        | 14     | 5.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 113       | 135    | 75.84%  |
| 0.51-1.0   | 35        | 47     | 23.49%  |
| 1.01-2.0   | 1         | 1      | 0.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 52        | 28.89%  |
| 251-500        | 50        | 27.78%  |
| 51-100         | 19        | 10.56%  |
| 1-20           | 18        | 10%     |
| 501-1000       | 17        | 9.44%   |
| 21-50          | 15        | 8.33%   |
| 1001-2000      | 5         | 2.78%   |
| Unknown        | 3         | 1.67%   |
| More than 3000 | 1         | 0.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 86        | 45.26%  |
| 21-50          | 44        | 23.16%  |
| 101-250        | 25        | 13.16%  |
| 51-100         | 23        | 12.11%  |
| 251-500        | 6         | 3.16%   |
| Unknown        | 3         | 1.58%   |
| 501-1000       | 2         | 1.05%   |
| More than 3000 | 1         | 0.53%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD050 500GB                         | 2         | 2      | 8.33%   |
| Seagate ST9500325AS 500GB                        | 2         | 2      | 8.33%   |
| Hitachi HTS542525K9A300 250GB                    | 2         | 2      | 8.33%   |
| WDC WD5000BPVT-22HXZT1 500GB                     | 1         | 1      | 4.17%   |
| WDC WD2500BEKT-60A25T1 250GB                     | 1         | 1      | 4.17%   |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 4      | 4.17%   |
| Toshiba MQ01ACF050 500GB                         | 1         | 1      | 4.17%   |
| Toshiba MQ01ABD032 320GB                         | 1         | 1      | 4.17%   |
| Toshiba MK2565GSXN 250GB                         | 1         | 1      | 4.17%   |
| Toshiba MK1237GSX 120GB                          | 1         | 1      | 4.17%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 4.17%   |
| Seagate ST500LM021-1KJ152 500GB                  | 1         | 1      | 4.17%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 4.17%   |
| Seagate ST500LM000-1EJ162 500GB                  | 1         | 1      | 4.17%   |
| SanDisk SD7UB3Q256G1001 256GB SSD                | 1         | 1      | 4.17%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 4.17%   |
| Hitachi HTS723232A7A364 320GB                    | 1         | 1      | 4.17%   |
| Hitachi HTS545050A7E380 500GB                    | 1         | 2      | 4.17%   |
| HGST HTS545050A7E680 500GB                       | 1         | 1      | 4.17%   |
| Fujitsu MHW2120BH 120GB                          | 1         | 1      | 4.17%   |
| Apple HDD HTS541010A9E662 1TB                    | 1         | 1      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 6         | 6      | 25%     |
| Seagate             | 6         | 6      | 25%     |
| Hitachi             | 4         | 5      | 16.67%  |
| WDC                 | 3         | 6      | 12.5%   |
| SanDisk             | 1         | 1      | 4.17%   |
| Samsung Electronics | 1         | 1      | 4.17%   |
| HGST                | 1         | 1      | 4.17%   |
| Fujitsu             | 1         | 1      | 4.17%   |
| Apple               | 1         | 1      | 4.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 6         | 6      | 27.27%  |
| Seagate | 6         | 6      | 27.27%  |
| Hitachi | 4         | 5      | 18.18%  |
| WDC     | 3         | 6      | 13.64%  |
| HGST    | 1         | 1      | 4.55%   |
| Fujitsu | 1         | 1      | 4.55%   |
| Apple   | 1         | 1      | 4.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 22        | 26     | 91.67%  |
| SSD  | 2         | 2      | 8.33%   |

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
| Detected | 108       | 143    | 57.14%  |
| Works    | 55        | 66     | 29.1%   |
| Malfunc  | 24        | 28     | 12.7%   |
| Failed   | 2         | 3      | 1.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 146       | 76.84%  |
| Samsung Electronics              | 18        | 9.47%   |
| AMD                              | 11        | 5.79%   |
| Toshiba America Info Systems     | 3         | 1.58%   |
| SanDisk                          | 3         | 1.58%   |
| KIOXIA                           | 3         | 1.58%   |
| SK hynix                         | 2         | 1.05%   |
| Silicon Integrated Systems [SiS] | 1         | 0.53%   |
| Phison Electronics               | 1         | 0.53%   |
| Nvidia                           | 1         | 0.53%   |
| Kingston Technology Company      | 1         | 0.53%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 20        | 9.8%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 16        | 7.84%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 13        | 6.37%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 12        | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 12        | 5.88%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 11        | 5.39%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 9         | 4.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 9         | 4.41%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 8         | 3.92%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 8         | 3.92%   |
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 3.43%   |
| Intel Tiger Lake-LP SATA Controller                                            | 7         | 3.43%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 2.45%   |
| Intel Comet Lake SATA AHCI Controller                                          | 5         | 2.45%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5         | 2.45%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 5         | 2.45%   |
| Samsung NVMe SSD Controller 980                                                | 4         | 1.96%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 1.47%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 1.47%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 1.47%   |
| SanDisk Non-Volatile memory controller                                         | 2         | 0.98%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 2         | 0.98%   |
| Intel SSD 660P Series                                                          | 2         | 0.98%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 2         | 0.98%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 2         | 0.98%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 0.98%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.49%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.49%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 1         | 0.49%   |
| SK hynix Non-Volatile memory controller                                        | 1         | 0.49%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.49%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 1         | 0.49%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 1         | 0.49%   |
| SanDisk WD Black NVMe SSD                                                      | 1         | 0.49%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 0.49%   |
| Phison E12 NVMe Controller                                                     | 1         | 0.49%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 0.49%   |
| KIOXIA NVMe SSD                                                                | 1         | 0.49%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 0.49%   |
| Intel SSD 600P Series                                                          | 1         | 0.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 132       | 66.33%  |
| NVMe | 32        | 16.08%  |
| RAID | 28        | 14.07%  |
| IDE  | 7         | 3.52%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 163       | 92.09%  |
| AMD    | 14        | 7.91%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz           | 6         | 3.39%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 6         | 3.39%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 5         | 2.82%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 5         | 2.82%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 4         | 2.26%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 4         | 2.26%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 4         | 2.26%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 4         | 2.26%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 3         | 1.69%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 3         | 1.69%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 3         | 1.69%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 3         | 1.69%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 3         | 1.69%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 3         | 1.69%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 3         | 1.69%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 3         | 1.69%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 3         | 1.69%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 1.13%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 1.13%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 2         | 1.13%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 2         | 1.13%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 2         | 1.13%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.13%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 1.13%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 2         | 1.13%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.13%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 2         | 1.13%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 1.13%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 2         | 1.13%   |
| Intel Core i5 CPU M 450 @ 2.40GHz           | 2         | 1.13%   |
| Intel Core i3-7100U CPU @ 2.40GHz           | 2         | 1.13%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 2         | 1.13%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 2         | 1.13%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 2         | 1.13%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 2         | 1.13%   |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz        | 2         | 1.13%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 2         | 1.13%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz           | 2         | 1.13%   |
| AMD C-60 APU with Radeon HD Graphics        | 2         | 1.13%   |
| Intel Pentium M processor 1.73GHz           | 1         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 65        | 36.72%  |
| Intel Core i7           | 33        | 18.64%  |
| Intel Core i3           | 25        | 14.12%  |
| Intel Core 2 Duo        | 10        | 5.65%   |
| Other                   | 9         | 5.08%   |
| Intel Celeron           | 8         | 4.52%   |
| Intel Atom              | 5         | 2.82%   |
| AMD E1                  | 3         | 1.69%   |
| Intel Pentium Dual-Core | 2         | 1.13%   |
| AMD Ryzen 5             | 2         | 1.13%   |
| AMD C-60                | 2         | 1.13%   |
| AMD A8                  | 2         | 1.13%   |
| AMD A6                  | 2         | 1.13%   |
| Intel Pentium M         | 1         | 0.56%   |
| Intel Pentium Gold      | 1         | 0.56%   |
| Intel Pentium           | 1         | 0.56%   |
| Intel Genuine           | 1         | 0.56%   |
| Intel Core 2            | 1         | 0.56%   |
| Intel Celeron M         | 1         | 0.56%   |
| AMD Ryzen 9             | 1         | 0.56%   |
| AMD Ryzen 7 PRO         | 1         | 0.56%   |
| AMD A4                  | 1         | 0.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 117       | 66.1%   |
| 4      | 47        | 26.55%  |
| 1      | 5         | 2.82%   |
| 8      | 4         | 2.26%   |
| 6      | 4         | 2.26%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 177       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 137       | 77.4%   |
| 1      | 40        | 22.6%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 172       | 97.18%  |
| 32-bit         | 3         | 1.69%   |
| Unknown        | 2         | 1.13%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 27        | 15%     |
| 0x206a7    | 17        | 9.44%   |
| 0x306d4    | 13        | 7.22%   |
| 0x40651    | 11        | 6.11%   |
| 0x806ea    | 10        | 5.56%   |
| 0x306c3    | 9         | 5%      |
| 0x306a9    | 8         | 4.44%   |
| 0x20655    | 8         | 4.44%   |
| 0x806ec    | 7         | 3.89%   |
| 0x806c1    | 6         | 3.33%   |
| 0x406e3    | 6         | 3.33%   |
| 0x1067a    | 6         | 3.33%   |
| 0x806e9    | 5         | 2.78%   |
| 0x20652    | 5         | 2.78%   |
| 0x6fd      | 4         | 2.22%   |
| 0x506e3    | 4         | 2.22%   |
| 0x30678    | 4         | 2.22%   |
| 0x906ea    | 2         | 1.11%   |
| 0x406c4    | 2         | 1.11%   |
| 0x406c3    | 2         | 1.11%   |
| 0x10676    | 2         | 1.11%   |
| 0x0a50000c | 2         | 1.11%   |
| 0x07030105 | 2         | 1.11%   |
| 0x0700010f | 2         | 1.11%   |
| 0x906e9    | 1         | 0.56%   |
| 0x806eb    | 1         | 0.56%   |
| 0x806d1    | 1         | 0.56%   |
| 0x706e5    | 1         | 0.56%   |
| 0x706a1    | 1         | 0.56%   |
| 0x6ec      | 1         | 0.56%   |
| 0x6e8      | 1         | 0.56%   |
| 0x6d8      | 1         | 0.56%   |
| 0x30673    | 1         | 0.56%   |
| 0x30661    | 1         | 0.56%   |
| 0x08108102 | 1         | 0.56%   |
| 0x06006705 | 1         | 0.56%   |
| 0x06001119 | 1         | 0.56%   |
| 0x05000119 | 1         | 0.56%   |
| 0x05000101 | 1         | 0.56%   |
| 0x03000027 | 1         | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 30        | 16.95%  |
| Haswell       | 24        | 13.56%  |
| SandyBridge   | 19        | 10.73%  |
| Westmere      | 14        | 7.91%   |
| Skylake       | 13        | 7.34%   |
| Broadwell     | 13        | 7.34%   |
| Silvermont    | 9         | 5.08%   |
| Penryn        | 9         | 5.08%   |
| IvyBridge     | 9         | 5.08%   |
| TigerLake     | 8         | 4.52%   |
| Core          | 5         | 2.82%   |
| P6            | 3         | 1.69%   |
| Bobcat        | 3         | 1.69%   |
| Zen 3         | 2         | 1.13%   |
| Puma          | 2         | 1.13%   |
| Jaguar        | 2         | 1.13%   |
| Icelake       | 2         | 1.13%   |
| Bonnell       | 2         | 1.13%   |
| Unknown       | 2         | 1.13%   |
| Zen+          | 1         | 0.56%   |
| Piledriver    | 1         | 0.56%   |
| K10 Llano     | 1         | 0.56%   |
| Goldmont plus | 1         | 0.56%   |
| Excavator     | 1         | 0.56%   |
| CometLake     | 1         | 0.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 149       | 67.73%  |
| Nvidia | 44        | 20%     |
| AMD    | 27        | 12.27%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 18        | 8.07%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 14        | 6.28%   |
| Intel HD Graphics 5500                                                                   | 13        | 5.83%   |
| Intel UHD Graphics 620                                                                   | 11        | 4.93%   |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 4.93%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 4.04%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 3.59%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 8         | 3.59%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 3.14%   |
| Intel HD Graphics 620                                                                    | 7         | 3.14%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 2.69%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 2.24%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 2.24%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 1.79%   |
| Intel HD Graphics 530                                                                    | 4         | 1.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.79%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 1.35%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 3         | 1.35%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.35%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.35%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 1.35%   |
| Nvidia TU117M [GeForce MX450]                                                            | 2         | 0.9%    |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.9%    |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 0.9%    |
| Nvidia GK208M [GeForce GT 740M]                                                          | 2         | 0.9%    |
| Nvidia GF119M [NVS 4200M]                                                                | 2         | 0.9%    |
| Nvidia GF119M [GeForce GT 520M]                                                          | 2         | 0.9%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.9%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.9%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.9%    |
| AMD Wrestler [Radeon HD 6290]                                                            | 2         | 0.9%    |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/5145/530v/540v/545v]                         | 2         | 0.9%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 0.9%    |
| Nvidia TU117GLM [T1200 Laptop GPU]                                                       | 1         | 0.45%   |
| Nvidia TU104M [GeForce RTX 2080 Mobile]                                                  | 1         | 0.45%   |
| Nvidia GT218M [GeForce G210M]                                                            | 1         | 0.45%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.45%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 0.45%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 0.45%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 107       | 60.45%  |
| Intel + Nvidia | 35        | 19.77%  |
| 1 x AMD        | 19        | 10.73%  |
| 1 x Nvidia     | 8         | 4.52%   |
| Intel + AMD    | 7         | 3.95%   |
| AMD + Nvidia   | 1         | 0.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 150       | 82.87%  |
| Proprietary | 22        | 12.15%  |
| Unknown     | 9         | 4.97%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 126       | 69.61%  |
| 1.01-2.0   | 24        | 13.26%  |
| 0.01-0.5   | 19        | 10.5%   |
| 3.01-4.0   | 6         | 3.31%   |
| 0.51-1.0   | 5         | 2.76%   |
| 2.01-3.0   | 1         | 0.55%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 37        | 21.02%  |
| LG Display              | 35        | 19.89%  |
| Samsung Electronics     | 26        | 14.77%  |
| Chimei Innolux          | 26        | 14.77%  |
| BOE                     | 22        | 12.5%   |
| InfoVision              | 4         | 2.27%   |
| Hewlett-Packard         | 4         | 2.27%   |
| Dell                    | 4         | 2.27%   |
| LG Philips              | 3         | 1.7%    |
| Lenovo                  | 3         | 1.7%    |
| Chi Mei Optoelectronics | 3         | 1.7%    |
| Apple                   | 3         | 1.7%    |
| Sharp                   | 2         | 1.14%   |
| TMX                     | 1         | 0.57%   |
| PANDA                   | 1         | 0.57%   |
| MSI                     | 1         | 0.57%   |
| LGD                     | 1         | 0.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch  | 4         | 2.26%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 3         | 1.69%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 1.69%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 309x174mm 14.0-inch  | 2         | 1.13%   |
| Samsung Electronics LCD Monitor SDC4D42 1366x768 309x174mm 14.0-inch  | 2         | 1.13%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 2         | 1.13%   |
| LG Display LCD Monitor LGD0504 1366x768 344x194mm 15.5-inch           | 2         | 1.13%   |
| LG Display LCD Monitor LGD03D9 1366x768 345x194mm 15.6-inch           | 2         | 1.13%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1080 518x324mm 24.1-inch            | 2         | 1.13%   |
| Dell 2208WFP DEL403B 1680x1050 473x296mm 22.0-inch                    | 2         | 1.13%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 1.13%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x194mm 15.5-inch       | 2         | 1.13%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 2         | 1.13%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.13%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 2         | 1.13%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch        | 2         | 1.13%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch         | 2         | 1.13%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 2         | 1.13%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 2         | 1.13%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch               | 1         | 0.56%   |
| Sharp LCD Monitor SHP1516 3840x2400 336x210mm 15.6-inch               | 1         | 0.56%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 0.56%   |
| Samsung Electronics SyncMaster SAM0472 1440x900 367x229mm 17.0-inch   | 1         | 0.56%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch     | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC434E 1600x900 310x174mm 14.0-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC4143 1400x1050 286x214mm 14.1-inch | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3959 1366x768 344x194mm 15.5-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3846 1680x1050 331x207mm 15.4-inch | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 344x194mm 15.5-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 303x190mm 14.1-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3051 1600x900 390x230mm 17.8-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC304F 1680x945 409x230mm 18.5-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4146 1366x768 344x194mm 15.5-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SAM0FF0 3840x2160 950x540mm 43.0-inch | 1         | 0.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 86        | 50%     |
| 1920x1080 (FHD)    | 48        | 27.91%  |
| 1600x900 (HD+)     | 13        | 7.56%   |
| 1280x800 (WXGA)    | 6         | 3.49%   |
| 1680x1050 (WSXGA+) | 3         | 1.74%   |
| 1024x600           | 3         | 1.74%   |
| 3840x2160 (4K)     | 2         | 1.16%   |
| 1440x900 (WXGA+)   | 2         | 1.16%   |
| 3840x2400          | 1         | 0.58%   |
| 2880x1800          | 1         | 0.58%   |
| 2560x1600          | 1         | 0.58%   |
| 2560x1440 (QHD)    | 1         | 0.58%   |
| 1920x1200 (WUXGA)  | 1         | 0.58%   |
| 1680x945           | 1         | 0.58%   |
| 1400x1050          | 1         | 0.58%   |
| 1360x768           | 1         | 0.58%   |
| 1024x768 (XGA)     | 1         | 0.58%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 101       | 57.06%  |
| 14      | 24        | 13.56%  |
| 13      | 15        | 8.47%   |
| 12      | 9         | 5.08%   |
| 17      | 7         | 3.95%   |
| 18      | 4         | 2.26%   |
| 24      | 3         | 1.69%   |
| 23      | 3         | 1.69%   |
| 11      | 3         | 1.69%   |
| 22      | 2         | 1.13%   |
| 10      | 2         | 1.13%   |
| 84      | 1         | 0.56%   |
| 31      | 1         | 0.56%   |
| 27      | 1         | 0.56%   |
| Unknown | 1         | 0.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 130       | 73.45%  |
| 201-300     | 20        | 11.3%   |
| 351-400     | 12        | 6.78%   |
| 501-600     | 7         | 3.95%   |
| 401-500     | 5         | 2.82%   |
| 601-700     | 1         | 0.56%   |
| 1501-2000   | 1         | 0.56%   |
| Unknown     | 1         | 0.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 151       | 88.82%  |
| 16/10   | 16        | 9.41%   |
| 4/3     | 2         | 1.18%   |
| Unknown | 1         | 0.59%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 100       | 56.5%   |
| 81-90          | 34        | 19.21%  |
| 61-70          | 9         | 5.08%   |
| 201-250        | 6         | 3.39%   |
| 121-130        | 5         | 2.82%   |
| 71-80          | 4         | 2.26%   |
| 141-150        | 4         | 2.26%   |
| 51-60          | 3         | 1.69%   |
| 41-50          | 2         | 1.13%   |
| 251-300        | 2         | 1.13%   |
| 131-140        | 2         | 1.13%   |
| More than 1000 | 1         | 0.56%   |
| 351-500        | 1         | 0.56%   |
| 301-350        | 1         | 0.56%   |
| 111-120        | 1         | 0.56%   |
| 91-100         | 1         | 0.56%   |
| Unknown        | 1         | 0.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 81        | 46.02%  |
| 121-160       | 57        | 32.39%  |
| 51-100        | 25        | 14.2%   |
| 161-240       | 9         | 5.11%   |
| More than 240 | 2         | 1.14%   |
| 1-50          | 1         | 0.57%   |
| Unknown       | 1         | 0.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 161       | 90.45%  |
| 2     | 12        | 6.74%   |
| 0     | 5         | 2.81%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 92        | 33.21%  |
| Realtek Semiconductor    | 83        | 29.96%  |
| Qualcomm Atheros         | 42        | 15.16%  |
| Broadcom                 | 30        | 10.83%  |
| Ralink Technology        | 6         | 2.17%   |
| Ralink                   | 5         | 1.81%   |
| Xiaomi                   | 3         | 1.08%   |
| Broadcom Limited         | 3         | 1.08%   |
| Lenovo                   | 2         | 0.72%   |
| Dell                     | 2         | 0.72%   |
| TP-Link                  | 1         | 0.36%   |
| Sierra Wireless          | 1         | 0.36%   |
| Samsung Electronics      | 1         | 0.36%   |
| Qualcomm                 | 1         | 0.36%   |
| Nvidia                   | 1         | 0.36%   |
| MediaTek                 | 1         | 0.36%   |
| Marvell Technology Group | 1         | 0.36%   |
| JMicron Technology       | 1         | 0.36%   |
| Arduino SA               | 1         | 0.36%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 53        | 14.97%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 5.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 2.82%   |
| Intel Wireless 8265 / 8275                                        | 9         | 2.54%   |
| Intel Wireless 7265                                               | 9         | 2.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 2.54%   |
| Intel 82577LM Gigabit Network Connection                          | 9         | 2.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 8         | 2.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 2.26%   |
| Intel Wireless 8260                                               | 8         | 2.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 1.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 1.98%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 1.69%   |
| Intel Ethernet Connection (3) I218-LM                             | 6         | 1.69%   |
| Intel Centrino Advanced-N 6200                                    | 6         | 1.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 1.41%   |
| Ralink MT7601U Wireless Adapter                                   | 5         | 1.41%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 5         | 1.41%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 1.41%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 5         | 1.41%   |
| Intel Wireless 7260                                               | 5         | 1.41%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 1.41%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 1.41%   |
| Intel Centrino Advanced-N 6235                                    | 5         | 1.41%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 1.41%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 1.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.13%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 1.13%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 1.13%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.13%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 1.13%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 4         | 1.13%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.85%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.85%   |
| Intel WiFi Link 5100                                              | 3         | 0.85%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.85%   |
| Intel Centrino Ultimate-N 6300                                    | 3         | 0.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.56%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 84        | 46.15%  |
| Qualcomm Atheros      | 37        | 20.33%  |
| Realtek Semiconductor | 22        | 12.09%  |
| Broadcom              | 21        | 11.54%  |
| Ralink Technology     | 6         | 3.3%    |
| Ralink                | 5         | 2.75%   |
| Broadcom Limited      | 3         | 1.65%   |
| TP-Link               | 1         | 0.55%   |
| Sierra Wireless       | 1         | 0.55%   |
| MediaTek              | 1         | 0.55%   |
| Dell                  | 1         | 0.55%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 9         | 4.95%   |
| Intel Wireless 7265                                            | 9         | 4.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 9         | 4.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 8         | 4.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 8         | 4.4%    |
| Intel Wireless 8260                                            | 8         | 4.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 7         | 3.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 7         | 3.85%   |
| Intel Centrino Advanced-N 6200                                 | 6         | 3.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 2.75%   |
| Ralink MT7601U Wireless Adapter                                | 5         | 2.75%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 5         | 2.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 5         | 2.75%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 5         | 2.75%   |
| Intel Wireless 7260                                            | 5         | 2.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 2.75%   |
| Intel Centrino Advanced-N 6235                                 | 5         | 2.75%   |
| Broadcom BCM43142 802.11b/g/n                                  | 5         | 2.75%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 2.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 2.2%    |
| Intel Wi-Fi 6 AX201                                            | 4         | 2.2%    |
| Broadcom BCM43228 802.11a/b/g/n                                | 4         | 2.2%    |
| Intel WiFi Link 5100                                           | 3         | 1.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 1.65%   |
| Intel Centrino Ultimate-N 6300                                 | 3         | 1.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.1%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 1.1%    |
| Intel Wireless 3165                                            | 2         | 1.1%    |
| Intel Wi-Fi 6 AX200                                            | 2         | 1.1%    |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 1.1%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 1.1%    |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 2         | 1.1%    |
| Broadcom BCM43225 802.11b/g/n                                  | 2         | 1.1%    |
| Broadcom BCM4311 802.11b/g WLAN                                | 2         | 1.1%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 0.55%   |
| Sierra Wireless EM7455                                         | 1         | 0.55%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.55%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 0.55%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 0.55%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 0.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 77        | 45.83%  |
| Intel                    | 58        | 34.52%  |
| Broadcom                 | 12        | 7.14%   |
| Qualcomm Atheros         | 11        | 6.55%   |
| Xiaomi                   | 3         | 1.79%   |
| Lenovo                   | 2         | 1.19%   |
| Samsung Electronics      | 1         | 0.6%    |
| Qualcomm                 | 1         | 0.6%    |
| Nvidia                   | 1         | 0.6%    |
| Marvell Technology Group | 1         | 0.6%    |
| JMicron Technology       | 1         | 0.6%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 53        | 31.36%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 10.65%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 5.92%   |
| Intel 82577LM Gigabit Network Connection                          | 9         | 5.33%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 3.55%   |
| Intel Ethernet Connection (3) I218-LM                             | 6         | 3.55%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 2.96%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 2.37%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 2.37%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 2.37%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 1.78%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 1.78%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.18%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.18%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.18%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.18%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 2         | 1.18%   |
| Intel Ethernet Connection I217-V                                  | 2         | 1.18%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.18%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 2         | 1.18%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.18%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 1.18%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.59%   |
| Qualcomm Redmi 9T                                                 | 1         | 0.59%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.59%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.59%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.59%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.59%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 0.59%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.59%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.59%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.59%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.59%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 0.59%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.59%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.59%   |
| Intel 82567LF Gigabit Network Connection                          | 1         | 0.59%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.59%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                 | 1         | 0.59%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 175       | 51.78%  |
| Ethernet | 160       | 47.34%  |
| Modem    | 3         | 0.89%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 147       | 82.58%  |
| Ethernet | 31        | 17.42%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 155       | 87.08%  |
| 1     | 18        | 10.11%  |
| 0     | 3         | 1.69%   |
| 7     | 1         | 0.56%   |
| 3     | 1         | 0.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 177       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 54        | 42.19%  |
| Realtek Semiconductor           | 16        | 12.5%   |
| Qualcomm Atheros Communications | 16        | 12.5%   |
| Broadcom                        | 8         | 6.25%   |
| Dell                            | 7         | 5.47%   |
| Ralink                          | 5         | 3.91%   |
| Lite-On Technology              | 5         | 3.91%   |
| IMC Networks                    | 5         | 3.91%   |
| Hewlett-Packard                 | 4         | 3.13%   |
| Apple                           | 2         | 1.56%   |
| Toshiba                         | 1         | 0.78%   |
| Foxconn International           | 1         | 0.78%   |
| Foxconn / Hon Hai               | 1         | 0.78%   |
| Cambridge Silicon Radio         | 1         | 0.78%   |
| ASUSTek Computer                | 1         | 0.78%   |
| Alps Electric                   | 1         | 0.78%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 31        | 24.22%  |
| Realtek Bluetooth Radio                             | 10        | 7.81%   |
| Intel AX201 Bluetooth                               | 9         | 7.03%   |
| Qualcomm Atheros  Bluetooth Device                  | 7         | 5.47%   |
| Ralink RT3290 Bluetooth                             | 5         | 3.91%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 3.91%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 3.13%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 3.13%   |
| IMC Networks Bluetooth Device                       | 4         | 3.13%   |
| Dell DW375 Bluetooth Module                         | 4         | 3.13%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 2.34%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 2.34%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 2.34%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 2.34%   |
| Realtek RTL8723B Bluetooth                          | 2         | 1.56%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 1.56%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 1.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 1.56%   |
| Intel AX200 Bluetooth                               | 2         | 1.56%   |
| Dell Wireless 360 Bluetooth                         | 2         | 1.56%   |
| Broadcom HP Portable Bumble Bee                     | 2         | 1.56%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 1.56%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.56%   |
| Toshiba Bluetooth Device                            | 1         | 0.78%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.78%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.78%   |
| IMC Networks Wireless_Device                        | 1         | 0.78%   |
| HP Bluetooth 1.2 Interface [Broadcom BCM2035]       | 1         | 0.78%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.78%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.78%   |
| Dell Wireless 350 Bluetooth                         | 1         | 0.78%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 0.78%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.78%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.78%   |
| ASUS BT-270 Bluetooth Adapter                       | 1         | 0.78%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 0.78%   |
| Apple Bluetooth Host Controller                     | 1         | 0.78%   |
| Alps Electric BCM2046 Bluetooth Device              | 1         | 0.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 159       | 77.56%  |
| Nvidia                           | 22        | 10.73%  |
| AMD                              | 19        | 9.27%   |
| Lenovo                           | 2         | 0.98%   |
| Silicon Integrated Systems [SiS] | 1         | 0.49%   |
| Logitech                         | 1         | 0.49%   |
| GN Netcom                        | 1         | 0.49%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 26        | 10.32%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 15        | 5.95%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 14        | 5.56%   |
| Intel 8 Series HD Audio Controller                                                                | 14        | 5.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 14        | 5.56%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 13        | 5.16%   |
| Intel Broadwell-U Audio Controller                                                                | 13        | 5.16%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 13        | 5.16%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 10        | 3.97%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 10        | 3.97%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 8         | 3.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 2.78%   |
| AMD FCH Azalia Controller                                                                         | 6         | 2.38%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 1.98%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 1.98%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.98%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 1.59%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 4         | 1.59%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.59%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 1.59%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 4         | 1.59%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 1.19%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.19%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.19%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.19%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 1.19%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.79%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.79%   |
| Nvidia Audio device                                                                               | 2         | 0.79%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 2         | 0.79%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.79%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.79%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.79%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.4%    |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.4%    |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.4%    |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.4%    |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.4%    |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.4%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 34        | 29.31%  |
| SK hynix            | 28        | 24.14%  |
| Micron Technology   | 16        | 13.79%  |
| Kingston            | 16        | 13.79%  |
| Unknown             | 5         | 4.31%   |
| A-DATA Technology   | 4         | 3.45%   |
| Elpida              | 3         | 2.59%   |
| Crucial             | 3         | 2.59%   |
| Ramaxel Technology  | 2         | 1.72%   |
| Transcend           | 1         | 0.86%   |
| Toshiba             | 1         | 0.86%   |
| Sesame              | 1         | 0.86%   |
| Nanya Technology    | 1         | 0.86%   |
| ASint Technology    | 1         | 0.86%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s   | 4         | 3.17%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s    | 4         | 3.17%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s   | 3         | 2.38%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s    | 3         | 2.38%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 2         | 1.59%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s   | 2         | 1.59%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s    | 2         | 1.59%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s    | 2         | 1.59%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s | 2         | 1.59%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s    | 2         | 1.59%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s    | 2         | 1.59%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s     | 2         | 1.59%   |
| Kingston RAM HP687515-H66-MCN 4GB SODIMM DDR3 1600MT/s   | 2         | 1.59%   |
| Kingston RAM HP16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s    | 2         | 1.59%   |
| Unknown RAM Module 4GB SODIMM DDR3                       | 1         | 0.79%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1066MT/s           | 1         | 0.79%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                | 1         | 0.79%   |
| Unknown RAM Module 2048MB SODIMM DDR2                    | 1         | 0.79%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                 | 1         | 0.79%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s             | 1         | 0.79%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM DDR3 1334MT/s      | 1         | 0.79%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s        | 1         | 0.79%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s          | 1         | 0.79%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s          | 1         | 0.79%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s    | 1         | 0.79%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 1         | 0.79%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s   | 1         | 0.79%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s   | 1         | 0.79%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s   | 1         | 0.79%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 1         | 0.79%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1600MT/s   | 1         | 0.79%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s   | 1         | 0.79%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s   | 1         | 0.79%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s   | 1         | 0.79%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s   | 1         | 0.79%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s   | 1         | 0.79%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1334MT/s   | 1         | 0.79%   |
| SK hynix RAM HMT125S6AFP8C-G7 2GB SODIMM 1066MT/s        | 1         | 0.79%   |
| SK hynix RAM HMT112S6AFP6C-G7 1GB SODIMM 800MT/s         | 1         | 0.79%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s  | 1         | 0.79%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 50        | 55.56%  |
| DDR4    | 27        | 30%     |
| DDR2    | 4         | 4.44%   |
| LPDDR4  | 3         | 3.33%   |
| LPDDR3  | 3         | 3.33%   |
| Unknown | 2         | 2.22%   |
| SDRAM   | 1         | 1.11%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 83        | 94.32%  |
| Row Of Chips | 3         | 3.41%   |
| DIMM         | 1         | 1.14%   |
| Unknown      | 1         | 1.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 45        | 45%     |
| 8192  | 33        | 33%     |
| 2048  | 14        | 14%     |
| 16384 | 6         | 6%      |
| 1024  | 2         | 2%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 36        | 36%     |
| 2667    | 16        | 16%     |
| 1334    | 11        | 11%     |
| 3200    | 10        | 10%     |
| 2400    | 4         | 4%      |
| 2133    | 4         | 4%      |
| 1333    | 4         | 4%      |
| 1066    | 3         | 3%      |
| 975     | 2         | 2%      |
| 800     | 2         | 2%      |
| Unknown | 2         | 2%      |
| 4267    | 1         | 1%      |
| 4199    | 1         | 1%      |
| 3266    | 1         | 1%      |
| 1867    | 1         | 1%      |
| 1067    | 1         | 1%      |
| 667     | 1         | 1%      |

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
| Chicony Electronics                    | 43        | 29.05%  |
| IMC Networks                           | 17        | 11.49%  |
| Realtek Semiconductor                  | 14        | 9.46%   |
| Cheng Uei Precision Industry (Foxlink) | 14        | 9.46%   |
| Sunplus Innovation Technology          | 10        | 6.76%   |
| Suyin                                  | 9         | 6.08%   |
| Lite-On Technology                     | 8         | 5.41%   |
| Microdia                               | 7         | 4.73%   |
| Ricoh                                  | 4         | 2.7%    |
| Quanta                                 | 4         | 2.7%    |
| Acer                                   | 4         | 2.7%    |
| Syntek                                 | 3         | 2.03%   |
| Apple                                  | 3         | 2.03%   |
| Z-Star Microelectronics                | 1         | 0.68%   |
| Sunplus Technology                     | 1         | 0.68%   |
| Silicon Motion                         | 1         | 0.68%   |
| Luxvisions Innotech Limited            | 1         | 0.68%   |
| Logitech                               | 1         | 0.68%   |
| DLEQNA19IFK6G2                         | 1         | 0.68%   |
| ALi                                    | 1         | 0.68%   |
| Alcor Micro                            | 1         | 0.68%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 6         | 4.05%   |
| IMC Networks Integrated Camera                              | 5         | 3.38%   |
| Chicony HP Webcam [2 MP Macro]                              | 5         | 3.38%   |
| Chicony HP Webcam                                           | 4         | 2.7%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 4         | 2.7%    |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 3         | 2.03%   |
| Realtek USB Camera                                          | 3         | 2.03%   |
| Realtek Integrated_Webcam_HD                                | 3         | 2.03%   |
| Microdia Integrated Webcam                                  | 3         | 2.03%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 3         | 2.03%   |
| IMC Networks Lenovo EasyCamera                              | 3         | 2.03%   |
| Chicony HP HD Webcam                                        | 3         | 2.03%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 3         | 2.03%   |
| Syntek Lenovo EasyCamera                                    | 2         | 1.35%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 2         | 1.35%   |
| Sunplus Integrated_Webcam_HD                                | 2         | 1.35%   |
| Sunplus HP Universal Camera                                 | 2         | 1.35%   |
| Ricoh Laptop_Integrated_Webcam_FHD                          | 2         | 1.35%   |
| Lite-On TOSHIBA Web Camera - HD                             | 2         | 1.35%   |
| Lite-On HP HD Webcam                                        | 2         | 1.35%   |
| Lite-On HP HD Camera                                        | 2         | 1.35%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 2         | 1.35%   |
| IMC Networks Integrated Webcam                              | 2         | 1.35%   |
| IMC Networks HP TrueVision HD Camera                        | 2         | 1.35%   |
| Chicony TOSHIBA Web Camera - HD                             | 2         | 1.35%   |
| Chicony Lenovo Integrated Camera (0.3MP)                    | 2         | 1.35%   |
| Chicony Integrated Camera (1280x720@30)                     | 2         | 1.35%   |
| Chicony HP Wide Vision HD Camera                            | 2         | 1.35%   |
| Chicony HP Truevision HD                                    | 2         | 1.35%   |
| Chicony HP HD Webcam [Fixed]                                | 2         | 1.35%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD     | 2         | 1.35%   |
| Acer Integrated Camera                                      | 2         | 1.35%   |
| Z-Star Vimicro USB2.0 Camera                                | 1         | 0.68%   |
| Syntek EasyCamera                                           | 1         | 0.68%   |
| Suyin WebCam                                                | 1         | 0.68%   |
| Suyin Sony Visual Communication Camera                      | 1         | 0.68%   |
| Suyin RGBIR Camera                                          | 1         | 0.68%   |
| Suyin Integrated_Webcam_HD                                  | 1         | 0.68%   |
| Suyin Integrated_Webcam_2M                                  | 1         | 0.68%   |
| Suyin HP Webcam-50                                          | 1         | 0.68%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 25        | 65.79%  |
| Synaptics                  | 6         | 15.79%  |
| Elan Microelectronics      | 4         | 10.53%  |
| Shenzhen Goodix Technology | 2         | 5.26%   |
| Upek                       | 1         | 2.63%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 10        | 26.32%  |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 10.53%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 10.53%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 7.89%   |
| Validity Sensors VFS491                                                    | 2         | 5.26%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 5.26%   |
| Elan ELAN:Fingerprint                                                      | 2         | 5.26%   |
| Elan ELAN:ARM-M4                                                           | 2         | 5.26%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2.63%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.63%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.63%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 2.63%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 2.63%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 2.63%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 2.63%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 2.63%   |
| Unknown                                                                    | 1         | 2.63%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 16        | 64%     |
| Alcor Micro | 5         | 20%     |
| O2 Micro    | 4         | 16%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 40%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 20%     |
| Broadcom 5880                                                                | 3         | 12%     |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 8%      |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 8%      |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 8%      |
| Broadcom 58200                                                               | 1         | 4%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 99        | 54.4%   |
| 1     | 64        | 35.16%  |
| 2     | 15        | 8.24%   |
| 3     | 3         | 1.65%   |
| 5     | 1         | 0.55%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 38        | 35.51%  |
| Chipcard                 | 23        | 21.5%   |
| Graphics card            | 18        | 16.82%  |
| Net/wireless             | 7         | 6.54%   |
| Bluetooth                | 6         | 5.61%   |
| Storage                  | 5         | 4.67%   |
| Sound                    | 2         | 1.87%   |
| Net/ethernet             | 2         | 1.87%   |
| Communication controller | 2         | 1.87%   |
| Camera                   | 2         | 1.87%   |
| Unassigned class         | 1         | 0.93%   |
| Modem                    | 1         | 0.93%   |

