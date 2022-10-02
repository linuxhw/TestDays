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

Total: 219

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Unknown       | 1.0                         | [f5b0e6a742](https://linux-hardware.org/?probe=f5b0e6a742) | Sep 24, 2022 |
| ASUSTek       | X555LD                      | [08793f9065](https://linux-hardware.org/?probe=08793f9065) | Sep 24, 2022 |
| HP            | EliteBook 840 G5            | [eb488dae73](https://linux-hardware.org/?probe=eb488dae73) | Sep 17, 2022 |
| HP            | EliteBook 840 G5            | [eb406c0e81](https://linux-hardware.org/?probe=eb406c0e81) | Sep 15, 2022 |
| HP            | EliteBook 840 G5            | [6b6e4efdfc](https://linux-hardware.org/?probe=6b6e4efdfc) | Sep 13, 2022 |
| HP            | EliteBook 840 G5            | [4083f9d2c9](https://linux-hardware.org/?probe=4083f9d2c9) | Sep 11, 2022 |
| HP            | EliteBook 840 G5            | [a870f2cf25](https://linux-hardware.org/?probe=a870f2cf25) | Sep 07, 2022 |
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
| Ubuntu 20.04       | 33        | 21.15%  |
| Ubuntu 18.04       | 12        | 7.69%   |
| KDE neon 20.04     | 10        | 6.41%   |
| OpenMandriva 4.2   | 6         | 3.85%   |
| Linux Mint 20.2    | 6         | 3.85%   |
| Debian 11          | 6         | 3.85%   |
| OpenMandriva 4.3   | 5         | 3.21%   |
| Zorin 16           | 4         | 2.56%   |
| Ubuntu 20.10       | 4         | 2.56%   |
| Ubuntu 19.10       | 4         | 2.56%   |
| Linux Mint 20.3    | 4         | 2.56%   |
| Arch               | 4         | 2.56%   |
| Ubuntu Unity 16.04 | 3         | 1.92%   |
| Pop!_OS 22.04      | 3         | 1.92%   |
| ArcoLinux Rolling  | 3         | 1.92%   |
| Void Linux         | 2         | 1.28%   |
| Ubuntu 22.04       | 2         | 1.28%   |
| Ubuntu 21.10       | 2         | 1.28%   |
| Ubuntu 21.04       | 2         | 1.28%   |
| Pop!_OS 21.10      | 2         | 1.28%   |
| Manjaro            | 2         | 1.28%   |
| Linux Mint 19.3    | 2         | 1.28%   |
| Kali 2019.4        | 2         | 1.28%   |
| Zorin 15           | 1         | 0.64%   |
| Xubuntu 20.04      | 1         | 0.64%   |
| Xero Rolling       | 1         | 0.64%   |
| Ubuntu Unity 20.04 | 1         | 0.64%   |
| Ubuntu MATE 20.04  | 1         | 0.64%   |
| Ubuntu 19.04       | 1         | 0.64%   |
| Ubuntu 16.04       | 1         | 0.64%   |
| Ubuntu             | 1         | 0.64%   |
| RHEL 8             | 1         | 0.64%   |
| Pop!_OS 20.10      | 1         | 0.64%   |
| Parrot 5.0         | 1         | 0.64%   |
| openSUSE Leap-15.2 | 1         | 0.64%   |
| Manjaro 21.3.7     | 1         | 0.64%   |
| Manjaro 21.1.6     | 1         | 0.64%   |
| Manjaro 20.1       | 1         | 0.64%   |
| Linux Mint 21      | 1         | 0.64%   |
| Linux Mint 20      | 1         | 0.64%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 56        | 37.33%  |
| Linux Mint   | 15        | 10%     |
| OpenMandriva | 11        | 7.33%   |
| KDE neon     | 10        | 6.67%   |
| Debian       | 7         | 4.67%   |
| Pop!_OS      | 6         | 4%      |
| Zorin        | 5         | 3.33%   |
| Manjaro      | 5         | 3.33%   |
| Kali         | 5         | 3.33%   |
| Ubuntu Unity | 4         | 2.67%   |
| Arch         | 4         | 2.67%   |
| Fedora       | 3         | 2%      |
| Endless      | 3         | 2%      |
| ArcoLinux    | 3         | 2%      |
| Void Linux   | 2         | 1.33%   |
| Elementary   | 2         | 1.33%   |
| Xubuntu      | 1         | 0.67%   |
| Xero         | 1         | 0.67%   |
| Ubuntu MATE  | 1         | 0.67%   |
| RHEL         | 1         | 0.67%   |
| Parrot       | 1         | 0.67%   |
| openSUSE     | 1         | 0.67%   |
| EndeavourOS  | 1         | 0.67%   |
| CentOS       | 1         | 0.67%   |
| BunsenLabs   | 1         | 0.67%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002     | 6         | 3.55%   |
| 5.16.7-desktop-1omv4003      | 5         | 2.96%   |
| 5.13.0-40-generic            | 5         | 2.96%   |
| 5.8.0-43-generic             | 4         | 2.37%   |
| 5.4.0-58-generic             | 4         | 2.37%   |
| 5.4.0-48-generic             | 4         | 2.37%   |
| 5.4.0-42-generic             | 3         | 1.78%   |
| 5.3.0-40-generic             | 3         | 1.78%   |
| 5.17.5-76051705-generic      | 3         | 1.78%   |
| 5.11.0-37-generic            | 3         | 1.78%   |
| 5.8.0-48-generic             | 2         | 1.18%   |
| 5.8.0-38-generic             | 2         | 1.18%   |
| 5.8.0-33-generic             | 2         | 1.18%   |
| 5.4.0-96-generic             | 2         | 1.18%   |
| 5.4.0-88-generic             | 2         | 1.18%   |
| 5.4.0-65-generic             | 2         | 1.18%   |
| 5.4.0-37-generic             | 2         | 1.18%   |
| 5.4.0-33-generic             | 2         | 1.18%   |
| 5.4.0-29-generic             | 2         | 1.18%   |
| 5.3.0-kali2-686-pae          | 2         | 1.18%   |
| 5.3.0-51-generic             | 2         | 1.18%   |
| 5.3.0-28-generic             | 2         | 1.18%   |
| 5.18.19_1                    | 2         | 1.18%   |
| 5.15.0-46-generic            | 2         | 1.18%   |
| 5.14.14-arch1-1              | 2         | 1.18%   |
| 5.13.0-27-generic            | 2         | 1.18%   |
| 5.13.0-19-generic            | 2         | 1.18%   |
| 5.11.0-46-generic            | 2         | 1.18%   |
| 5.11.0-36-generic            | 2         | 1.18%   |
| 5.0.0-23-generic             | 2         | 1.18%   |
| 5.8.15-201.fc32.x86_64       | 1         | 0.59%   |
| 5.8.1-050801-generic         | 1         | 0.59%   |
| 5.8.0-rc6-3.g007dcf0-default | 1         | 0.59%   |
| 5.8.0-63-generic             | 1         | 0.59%   |
| 5.8.0-55-generic             | 1         | 0.59%   |
| 5.8.0-41-generic             | 1         | 0.59%   |
| 5.8.0-36-generic             | 1         | 0.59%   |
| 5.8.0-34-generic             | 1         | 0.59%   |
| 5.8.0-14-generic             | 1         | 0.59%   |
| 5.7.15-1-MANJARO             | 1         | 0.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 34        | 21.94%  |
| 5.8.0   | 14        | 9.03%   |
| 5.11.0  | 11        | 7.1%    |
| 5.3.0   | 10        | 6.45%   |
| 5.13.0  | 10        | 6.45%   |
| 4.15.0  | 10        | 6.45%   |
| 5.10.0  | 7         | 4.52%   |
| 5.10.14 | 6         | 3.87%   |
| 5.0.0   | 6         | 3.87%   |
| 5.16.7  | 5         | 3.23%   |
| 5.15.0  | 5         | 3.23%   |
| 5.17.5  | 3         | 1.94%   |
| 4.18.0  | 3         | 1.94%   |
| 5.18.19 | 2         | 1.29%   |
| 5.16.0  | 2         | 1.29%   |
| 5.14.14 | 2         | 1.29%   |
| 4.19.0  | 2         | 1.29%   |
| 5.8.15  | 1         | 0.65%   |
| 5.8.1   | 1         | 0.65%   |
| 5.7.15  | 1         | 0.65%   |
| 5.19.9  | 1         | 0.65%   |
| 5.18.18 | 1         | 0.65%   |
| 5.18.12 | 1         | 0.65%   |
| 5.17.9  | 1         | 0.65%   |
| 5.17.15 | 1         | 0.65%   |
| 5.17.1  | 1         | 0.65%   |
| 5.16.2  | 1         | 0.65%   |
| 5.15.60 | 1         | 0.65%   |
| 5.15.4  | 1         | 0.65%   |
| 5.15.23 | 1         | 0.65%   |
| 5.15.21 | 1         | 0.65%   |
| 5.15.15 | 1         | 0.65%   |
| 5.15.12 | 1         | 0.65%   |
| 5.14.0  | 1         | 0.65%   |
| 5.13.19 | 1         | 0.65%   |
| 5.11.7  | 1         | 0.65%   |
| 5.11.14 | 1         | 0.65%   |
| 5.10.87 | 1         | 0.65%   |
| 4.4.0   | 1         | 0.65%   |
| 4.13.0  | 1         | 0.65%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 34        | 21.94%  |
| 5.8     | 16        | 10.32%  |
| 5.10    | 14        | 9.03%   |
| 5.11    | 13        | 8.39%   |
| 5.15    | 11        | 7.1%    |
| 5.13    | 11        | 7.1%    |
| 5.3     | 10        | 6.45%   |
| 4.15    | 10        | 6.45%   |
| 5.16    | 8         | 5.16%   |
| 5.17    | 6         | 3.87%   |
| 5.0     | 6         | 3.87%   |
| 5.18    | 4         | 2.58%   |
| 5.14    | 3         | 1.94%   |
| 4.18    | 3         | 1.94%   |
| 4.19    | 2         | 1.29%   |
| 5.7     | 1         | 0.65%   |
| 5.19    | 1         | 0.65%   |
| 4.4     | 1         | 0.65%   |
| 4.13    | 1         | 0.65%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 141       | 95.27%  |
| i686   | 7         | 4.73%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 73        | 48.34%  |
| KDE5            | 24        | 15.89%  |
| Unknown         | 14        | 9.27%   |
| X-Cinnamon      | 11        | 7.28%   |
| XFCE            | 9         | 5.96%   |
| KDE             | 6         | 3.97%   |
| Unity           | 4         | 2.65%   |
| Pantheon        | 2         | 1.32%   |
| MATE            | 2         | 1.32%   |
| Cinnamon        | 2         | 1.32%   |
| xmonad          | 1         | 0.66%   |
| i3              | 1         | 0.66%   |
| GNOME Flashback | 1         | 0.66%   |
| Budgie          | 1         | 0.66%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 127       | 84.11%  |
| Wayland | 16        | 10.6%   |
| Unknown | 7         | 4.64%   |
| Tty     | 1         | 0.66%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 84        | 54.55%  |
| SDDM    | 23        | 14.94%  |
| GDM     | 23        | 14.94%  |
| LightDM | 14        | 9.09%   |
| GDM3    | 7         | 4.55%   |
| TDM     | 3         | 1.95%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 80        | 53.69%  |
| fr_FR   | 40        | 26.85%  |
| Unknown | 12        | 8.05%   |
| en_GB   | 7         | 4.7%    |
| de_DE   | 3         | 2.01%   |
| fr_MA   | 1         | 0.67%   |
| fr_BE   | 1         | 0.67%   |
| es_ES   | 1         | 0.67%   |
| en_AG   | 1         | 0.67%   |
| C       | 1         | 0.67%   |
| ar_MA   | 1         | 0.67%   |
| ar_EG   | 1         | 0.67%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 92        | 61.74%  |
| EFI  | 57        | 38.26%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 124       | 83.78%  |
| Overlay | 13        | 8.78%   |
| Btrfs   | 7         | 4.73%   |
| Xfs     | 2         | 1.35%   |
| Unknown | 2         | 1.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 85        | 57.05%  |
| GPT     | 42        | 28.19%  |
| MBR     | 22        | 14.77%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 131       | 88.51%  |
| Yes       | 17        | 11.49%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 99        | 66.44%  |
| Yes       | 50        | 33.56%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 51        | 34.46%  |
| Lenovo              | 25        | 16.89%  |
| Dell                | 23        | 15.54%  |
| ASUSTek Computer    | 12        | 8.11%   |
| Acer                | 7         | 4.73%   |
| Toshiba             | 6         | 4.05%   |
| Sony                | 3         | 2.03%   |
| Packard Bell        | 3         | 2.03%   |
| Timi                | 2         | 1.35%   |
| Samsung Electronics | 2         | 1.35%   |
| Apple               | 2         | 1.35%   |
| Unknown             | 2         | 1.35%   |
| TUXEDO              | 1         | 0.68%   |
| TrekStor            | 1         | 0.68%   |
| Razer               | 1         | 0.68%   |
| Medion              | 1         | 0.68%   |
| Mediacom            | 1         | 0.68%   |
| GPD                 | 1         | 0.68%   |
| Google              | 1         | 0.68%   |
| Gigabyte Technology | 1         | 0.68%   |
| eMachines           | 1         | 0.68%   |
| Clevo               | 1         | 0.68%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| HP Laptop 15-dw3xxx                        | 3         | 2.03%   |
| HP EliteBook 8440p                         | 3         | 2.03%   |
| HP EliteBook 840 G2                        | 3         | 2.03%   |
| Unknown                                    | 3         | 2.03%   |
| Timi TM1701                                | 2         | 1.35%   |
| Lenovo IdeaPad L3 15IML05 81Y3             | 2         | 1.35%   |
| HP ZBook 15                                | 2         | 1.35%   |
| HP ProBook 6470b                           | 2         | 1.35%   |
| HP Notebook                                | 2         | 1.35%   |
| HP EliteBook 8460p                         | 2         | 1.35%   |
| Dell Latitude E6520                        | 2         | 1.35%   |
| ASUS X540LA                                | 2         | 1.35%   |
| Acer Aspire ES1-523                        | 2         | 1.35%   |
| TUXEDO N13xWU                              | 1         | 0.68%   |
| TrekStor Surfbook W2                       | 1         | 0.68%   |
| Toshiba Satellite Pro C650                 | 1         | 0.68%   |
| Toshiba Satellite L750                     | 1         | 0.68%   |
| Toshiba Satellite L50-A-1EL                | 1         | 0.68%   |
| Toshiba Satellite L50-A-1DG                | 1         | 0.68%   |
| Toshiba Satellite C855-2CF                 | 1         | 0.68%   |
| Toshiba Satellite C660                     | 1         | 0.68%   |
| Sony VPCEH1L8E                             | 1         | 0.68%   |
| Sony VGN-FW11L                             | 1         | 0.68%   |
| Sony SVE14122CAW                           | 1         | 0.68%   |
| Samsung 355V4C/356V4C/3445VC/3545VC        | 1         | 0.68%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 0.68%   |
| Razer Blade Pro 17 (2019)                  | 1         | 0.68%   |
| Packard Bell EasyNote TS44HR               | 1         | 0.68%   |
| Packard Bell EasyNote TS11HR               | 1         | 0.68%   |
| Packard Bell EasyNote TK85                 | 1         | 0.68%   |
| Medion P7615                               | 1         | 0.68%   |
| Mediacom WinPad 11,6 FullHD- WPU11         | 1         | 0.68%   |
| Lenovo Z70-80 80FG                         | 1         | 0.68%   |
| Lenovo ThinkPad X280 20KF001KFR            | 1         | 0.68%   |
| Lenovo ThinkPad X250 20CLS4WV08            | 1         | 0.68%   |
| Lenovo ThinkPad X240 20AMA09VFR            | 1         | 0.68%   |
| Lenovo ThinkPad X220 4291V5K               | 1         | 0.68%   |
| Lenovo ThinkPad X220 4291B66               | 1         | 0.68%   |
| Lenovo ThinkPad X13 Gen 2i 20WK00AJGE      | 1         | 0.68%   |
| Lenovo ThinkPad X1 Carbon 6th 20KH006JGE   | 1         | 0.68%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 17        | 11.49%  |
| Dell Latitude         | 17        | 11.49%  |
| HP EliteBook          | 14        | 9.46%   |
| HP Laptop             | 8         | 5.41%   |
| HP ProBook            | 7         | 4.73%   |
| HP Pavilion           | 7         | 4.73%   |
| Toshiba Satellite     | 6         | 4.05%   |
| Acer Aspire           | 5         | 3.38%   |
| Lenovo IdeaPad        | 4         | 2.7%    |
| Packard Bell EasyNote | 3         | 2.03%   |
| HP ZBook              | 3         | 2.03%   |
| HP 250                | 3         | 2.03%   |
| Unknown               | 3         | 2.03%   |
| Timi TM1701           | 2         | 1.35%   |
| HP Notebook           | 2         | 1.35%   |
| HP Compaq             | 2         | 1.35%   |
| Dell Precision        | 2         | 1.35%   |
| Dell Inspiron         | 2         | 1.35%   |
| ASUS X540LA           | 2         | 1.35%   |
| TUXEDO N13xWU         | 1         | 0.68%   |
| TrekStor Surfbook     | 1         | 0.68%   |
| Sony VPCEH1L8E        | 1         | 0.68%   |
| Sony VGN-FW11L        | 1         | 0.68%   |
| Sony SVE14122CAW      | 1         | 0.68%   |
| Samsung 355V4C        | 1         | 0.68%   |
| Samsung 300E4A        | 1         | 0.68%   |
| Razer Blade           | 1         | 0.68%   |
| Medion P7615          | 1         | 0.68%   |
| Mediacom WinPad       | 1         | 0.68%   |
| Lenovo Z70-80         | 1         | 0.68%   |
| Lenovo ThinkBook      | 1         | 0.68%   |
| Lenovo S21e-20        | 1         | 0.68%   |
| Lenovo G50-70         | 1         | 0.68%   |
| HP Presario           | 1         | 0.68%   |
| HP 650                | 1         | 0.68%   |
| HP 255                | 1         | 0.68%   |
| HP 15                 | 1         | 0.68%   |
| GPD MicroPC           | 1         | 0.68%   |
| Google Banon          | 1         | 0.68%   |
| Gigabyte AERO         | 1         | 0.68%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2011 | 18        | 12.16%  |
| 2013 | 17        | 11.49%  |
| 2018 | 14        | 9.46%   |
| 2016 | 13        | 8.78%   |
| 2015 | 13        | 8.78%   |
| 2010 | 12        | 8.11%   |
| 2012 | 10        | 6.76%   |
| 2017 | 9         | 6.08%   |
| 2020 | 8         | 5.41%   |
| 2019 | 8         | 5.41%   |
| 2014 | 8         | 5.41%   |
| 2021 | 6         | 4.05%   |
| 2009 | 5         | 3.38%   |
| 2008 | 3         | 2.03%   |
| 2007 | 2         | 1.35%   |
| 2006 | 1         | 0.68%   |
| 2005 | 1         | 0.68%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 148       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 142       | 94.67%  |
| Enabled  | 8         | 5.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 147       | 99.32%  |
| Yes  | 1         | 0.68%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 54        | 36.49%  |
| 3.01-4.0   | 42        | 28.38%  |
| 16.01-24.0 | 16        | 10.81%  |
| 8.01-16.0  | 16        | 10.81%  |
| 1.01-2.0   | 10        | 6.76%   |
| 32.01-64.0 | 3         | 2.03%   |
| 24.01-32.0 | 3         | 2.03%   |
| 2.01-3.0   | 2         | 1.35%   |
| 0.51-1.0   | 2         | 1.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 66        | 41.25%  |
| 2.01-3.0  | 52        | 32.5%   |
| 4.01-8.0  | 18        | 11.25%  |
| 3.01-4.0  | 16        | 10%     |
| 0.51-1.0  | 7         | 4.38%   |
| 8.01-16.0 | 1         | 0.63%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 124       | 83.22%  |
| 2      | 22        | 14.77%  |
| 3      | 3         | 2.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 50%     |
| No        | 74        | 50%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 132       | 89.19%  |
| No        | 16        | 10.81%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 146       | 97.99%  |
| No        | 3         | 2.01%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 105       | 70%     |
| No        | 45        | 30%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Morocco | 148       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Casablanca       | 35        | 22.44%  |
| Marrakesh        | 17        | 10.9%   |
| Rabat            | 16        | 10.26%  |
| Agadir           | 13        | 8.33%   |
| Fes              | 10        | 6.41%   |
| Oujda            | 7         | 4.49%   |
| Tangier          | 6         | 3.85%   |
| Salé            | 6         | 3.85%   |
| Khouribga        | 6         | 3.85%   |
| Kenitra          | 6         | 3.85%   |
| Nador            | 4         | 2.56%   |
| Meknes           | 4         | 2.56%   |
| Tiznit           | 3         | 1.92%   |
| Beni Mellal      | 3         | 1.92%   |
| Temara           | 2         | 1.28%   |
| Taza             | 2         | 1.28%   |
| Youssoufia       | 1         | 0.64%   |
| Tétouan         | 1         | 0.64%   |
| Targuist         | 1         | 0.64%   |
| Taourirt         | 1         | 0.64%   |
| Skhirate         | 1         | 0.64%   |
| Sidi Kacem       | 1         | 0.64%   |
| Safi             | 1         | 0.64%   |
| Mohammedia       | 1         | 0.64%   |
| Midelt           | 1         | 0.64%   |
| Ksar El Kebir    | 1         | 0.64%   |
| Karia Ba Mohamed | 1         | 0.64%   |
| Guelmim          | 1         | 0.64%   |
| Berkane          | 1         | 0.64%   |
| Al Aaroui        | 1         | 0.64%   |
| Agdz             | 1         | 0.64%   |
| Agdal            | 1         | 0.64%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 32        | 40     | 19.05%  |
| Toshiba             | 24        | 32     | 14.29%  |
| Samsung Electronics | 23        | 30     | 13.69%  |
| WDC                 | 19        | 23     | 11.31%  |
| Unknown             | 8         | 12     | 4.76%   |
| SanDisk             | 6         | 6      | 3.57%   |
| Hitachi             | 6         | 7      | 3.57%   |
| HGST                | 6         | 6      | 3.57%   |
| SK hynix            | 5         | 5      | 2.98%   |
| Kingston            | 5         | 6      | 2.98%   |
| Intel               | 4         | 5      | 2.38%   |
| Apple               | 3         | 3      | 1.79%   |
| PNY                 | 2         | 3      | 1.19%   |
| LITEON              | 2         | 2      | 1.19%   |
| KIOXIA              | 2         | 2      | 1.19%   |
| KingDian            | 2         | 3      | 1.19%   |
| Fujitsu             | 2         | 2      | 1.19%   |
| Crucial             | 2         | 2      | 1.19%   |
| China               | 2         | 3      | 1.19%   |
| TwinMOS             | 1         | 1      | 0.6%    |
| RCESSD              | 1         | 1      | 0.6%    |
| Phison              | 1         | 1      | 0.6%    |
| LITEONIT            | 1         | 1      | 0.6%    |
| KingSpec            | 1         | 1      | 0.6%    |
| KingFast            | 1         | 2      | 0.6%    |
| Indilinx            | 1         | 1      | 0.6%    |
| IBM/Hitachi         | 1         | 1      | 0.6%    |
| Hewlett-Packard     | 1         | 1      | 0.6%    |
| GOODRAM             | 1         | 1      | 0.6%    |
| BIWIN               | 1         | 1      | 0.6%    |
| Apacer              | 1         | 1      | 0.6%    |
| 2.5"                | 1         | 1      | 0.6%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB      | 5         | 2.84%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 5         | 2.84%   |
| Samsung NVMe SSD Drive 512GB        | 4         | 2.27%   |
| Toshiba MQ01ACF050 500GB            | 3         | 1.7%    |
| Toshiba MQ01ABF050 500GB            | 3         | 1.7%    |
| Seagate ST500LT012-1DG142 500GB     | 3         | 1.7%    |
| Samsung NVMe SSD Drive 256GB        | 3         | 1.7%    |
| WDC WD5000LPCX-80VHAT1 500GB        | 2         | 1.14%   |
| WDC WD5000LPCX-60VHAT0 500GB        | 2         | 1.14%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 2         | 1.14%   |
| Unknown MMC Card  32GB              | 2         | 1.14%   |
| Unknown MMC Card  16GB              | 2         | 1.14%   |
| Toshiba MQ04ABF100 1TB              | 2         | 1.14%   |
| Toshiba MQ01ABD100 1TB              | 2         | 1.14%   |
| Seagate ST9500325AS 500GB           | 2         | 1.14%   |
| Seagate ST500VT000-1DK142 500GB     | 2         | 1.14%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2         | 1.14%   |
| Seagate ST500LM000-1EJ162 500GB     | 2         | 1.14%   |
| Samsung MZVLW256HEHP-000L7 256GB    | 2         | 1.14%   |
| Hitachi HTS723232A7A364 320GB       | 2         | 1.14%   |
| HGST HTS725050A7E630 500GB          | 2         | 1.14%   |
| HGST HTS545050A7E680 500GB          | 2         | 1.14%   |
| WDC WDS256G1X0C-00ENX0 256GB        | 1         | 0.57%   |
| WDC WD5000LPCX-60VHAT1 500GB        | 1         | 0.57%   |
| WDC WD5000BPVT-22HXZT1 500GB        | 1         | 0.57%   |
| WDC WD3200BUCT-63TWBY0 320GB        | 1         | 0.57%   |
| WDC WD3200BPVT-22ZEST0 320GB        | 1         | 0.57%   |
| WDC WD3200BEVT-60ZCT1 320GB         | 1         | 0.57%   |
| WDC WD2500BPVT-22ZEST0 250GB        | 1         | 0.57%   |
| WDC WD2500BEVT-22A23T0 250GB        | 1         | 0.57%   |
| WDC WD2500BEKT-60V5T1 250GB         | 1         | 0.57%   |
| WDC WD10SPZX-60Z10T0 1TB            | 1         | 0.57%   |
| WDC WD10SPZX-08Z10 1TB              | 1         | 0.57%   |
| WDC WD10JUCT-63CYNY0 1TB            | 1         | 0.57%   |
| WDC WD10JPVX-60JC3T0 1TB            | 1         | 0.57%   |
| Unknown SB32G  32GB                 | 1         | 0.57%   |
| Unknown SB128  128GB                | 1         | 0.57%   |
| Unknown NCard  64GB                 | 1         | 0.57%   |
| Unknown NCard  32GB                 | 1         | 0.57%   |
| Unknown MMC Card  64GB              | 1         | 0.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 32        | 40     | 36.36%  |
| Toshiba             | 20        | 24     | 22.73%  |
| WDC                 | 18        | 22     | 20.45%  |
| Hitachi             | 6         | 7      | 6.82%   |
| HGST                | 6         | 6      | 6.82%   |
| Samsung Electronics | 2         | 2      | 2.27%   |
| Fujitsu             | 2         | 2      | 2.27%   |
| IBM/Hitachi         | 1         | 1      | 1.14%   |
| Apple               | 1         | 1      | 1.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 6         | 6      | 13.95%  |
| Samsung Electronics | 6         | 9      | 13.95%  |
| Kingston            | 4         | 5      | 9.3%    |
| SK hynix            | 3         | 3      | 6.98%   |
| PNY                 | 2         | 3      | 4.65%   |
| LITEON              | 2         | 2      | 4.65%   |
| KingDian            | 2         | 3      | 4.65%   |
| Crucial             | 2         | 2      | 4.65%   |
| China               | 2         | 3      | 4.65%   |
| TwinMOS             | 1         | 1      | 2.33%   |
| Toshiba             | 1         | 1      | 2.33%   |
| RCESSD              | 1         | 1      | 2.33%   |
| LITEONIT            | 1         | 1      | 2.33%   |
| KingSpec            | 1         | 1      | 2.33%   |
| KingFast            | 1         | 1      | 2.33%   |
| Intel               | 1         | 2      | 2.33%   |
| Indilinx            | 1         | 1      | 2.33%   |
| Hewlett-Packard     | 1         | 1      | 2.33%   |
| GOODRAM             | 1         | 1      | 2.33%   |
| BIWIN               | 1         | 1      | 2.33%   |
| Apple               | 1         | 1      | 2.33%   |
| Apacer              | 1         | 1      | 2.33%   |
| 2.5"                | 1         | 1      | 2.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 87        | 105    | 52.73%  |
| SSD     | 42        | 51     | 25.45%  |
| NVMe    | 27        | 37     | 16.36%  |
| MMC     | 8         | 12     | 4.85%   |
| Unknown | 1         | 1      | 0.61%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 120       | 157    | 77.42%  |
| NVMe | 27        | 37     | 17.42%  |
| MMC  | 8         | 12     | 5.16%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 96        | 116    | 76.19%  |
| 0.51-1.0   | 30        | 40     | 23.81%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 45        | 29.8%   |
| 251-500    | 43        | 28.48%  |
| 501-1000   | 17        | 11.26%  |
| 21-50      | 14        | 9.27%   |
| 51-100     | 13        | 8.61%   |
| 1-20       | 12        | 7.95%   |
| 1001-2000  | 4         | 2.65%   |
| Unknown    | 3         | 1.99%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 69        | 43.13%  |
| 21-50    | 39        | 24.38%  |
| 101-250  | 24        | 15%     |
| 51-100   | 17        | 10.63%  |
| 251-500  | 6         | 3.75%   |
| Unknown  | 3         | 1.88%   |
| 501-1000 | 2         | 1.25%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                        | 2         | 2      | 11.11%  |
| WDC WD5000BPVT-22HXZT1 500GB                     | 1         | 1      | 5.56%   |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 2      | 5.56%   |
| Toshiba MQ01ACF050 500GB                         | 1         | 1      | 5.56%   |
| Toshiba MQ01ABD050 500GB                         | 1         | 1      | 5.56%   |
| Toshiba MQ01ABD032 320GB                         | 1         | 1      | 5.56%   |
| Toshiba MK2565GSXN 250GB                         | 1         | 1      | 5.56%   |
| Toshiba MK1237GSX 120GB                          | 1         | 1      | 5.56%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 5.56%   |
| Seagate ST500LM021-1KJ152 500GB                  | 1         | 1      | 5.56%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 5.56%   |
| Seagate ST500LM000-1EJ162 500GB                  | 1         | 1      | 5.56%   |
| SanDisk SD7UB3Q256G1001 256GB SSD                | 1         | 1      | 5.56%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 5.56%   |
| Hitachi HTS723232A7A364 320GB                    | 1         | 1      | 5.56%   |
| Hitachi HTS545050A7E380 500GB                    | 1         | 2      | 5.56%   |
| Fujitsu MHW2120BH 120GB                          | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 33.33%  |
| Toshiba             | 5         | 5      | 27.78%  |
| WDC                 | 2         | 3      | 11.11%  |
| Hitachi             | 2         | 3      | 11.11%  |
| SanDisk             | 1         | 1      | 5.56%   |
| Samsung Electronics | 1         | 1      | 5.56%   |
| Fujitsu             | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 37.5%   |
| Toshiba | 5         | 5      | 31.25%  |
| WDC     | 2         | 3      | 12.5%   |
| Hitachi | 2         | 3      | 12.5%   |
| Fujitsu | 1         | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 18     | 88.89%  |
| SSD  | 2         | 2      | 11.11%  |

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
| Detected | 93        | 128    | 58.49%  |
| Works    | 46        | 55     | 28.93%  |
| Malfunc  | 18        | 20     | 11.32%  |
| Failed   | 2         | 3      | 1.26%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 120       | 76.43%  |
| Samsung Electronics              | 16        | 10.19%  |
| AMD                              | 9         | 5.73%   |
| Toshiba America Info Systems     | 3         | 1.91%   |
| SK hynix                         | 2         | 1.27%   |
| KIOXIA                           | 2         | 1.27%   |
| Silicon Integrated Systems [SiS] | 1         | 0.64%   |
| SanDisk                          | 1         | 0.64%   |
| Phison Electronics               | 1         | 0.64%   |
| Nvidia                           | 1         | 0.64%   |
| Kingston Technology Company      | 1         | 0.64%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 14        | 8.33%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 13        | 7.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 12        | 7.14%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 10        | 5.95%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 10        | 5.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 9         | 5.36%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 9         | 5.36%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 8         | 4.76%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 7         | 4.17%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 7         | 4.17%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 5         | 2.98%   |
| Intel Volume Management Device NVMe RAID Controller                              | 5         | 2.98%   |
| Intel Tiger Lake-LP SATA Controller                                              | 5         | 2.98%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 5         | 2.98%   |
| Intel Comet Lake SATA AHCI Controller                                            | 4         | 2.38%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 2.38%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 1.79%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 1.19%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 2         | 1.19%   |
| Intel SSD 660P Series                                                            | 2         | 1.19%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 1.19%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 1.19%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 1.19%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.19%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 0.6%    |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.6%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 1         | 0.6%    |
| SK hynix Non-Volatile memory controller                                          | 1         | 0.6%    |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.6%    |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.6%    |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.6%    |
| SanDisk WD Black NVMe SSD                                                        | 1         | 0.6%    |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 0.6%    |
| Phison E12 NVMe Controller                                                       | 1         | 0.6%    |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.6%    |
| Kingston Company Company Non-Volatile memory controller                          | 1         | 0.6%    |
| Intel SSD 600P Series                                                            | 1         | 0.6%    |
| Intel SATA Controller [RAID mode]                                                | 1         | 0.6%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 0.6%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 113       | 68.9%   |
| NVMe | 27        | 16.46%  |
| RAID | 19        | 11.59%  |
| IDE  | 5         | 3.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 137       | 92.57%  |
| AMD    | 11        | 7.43%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz           | 6         | 4.05%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 5         | 3.38%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 5         | 3.38%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 4         | 2.7%    |
| Intel Core i5-8250U CPU @ 1.60GHz           | 4         | 2.7%    |
| Intel Core i5-3230M CPU @ 2.60GHz           | 4         | 2.7%    |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 4         | 2.7%    |
| Intel Core i5-6200U CPU @ 2.30GHz           | 3         | 2.03%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 3         | 2.03%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 3         | 2.03%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 3         | 2.03%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 3         | 2.03%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 3         | 2.03%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 3         | 2.03%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 1.35%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 2         | 1.35%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.35%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 1.35%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 1.35%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 2         | 1.35%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 1.35%   |
| Intel Core i5 CPU M 450 @ 2.40GHz           | 2         | 1.35%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 2         | 1.35%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 2         | 1.35%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 2         | 1.35%   |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz        | 2         | 1.35%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 2         | 1.35%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 2         | 1.35%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz           | 2         | 1.35%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2         | 1.35%   |
| AMD C-60 APU with Radeon HD Graphics        | 2         | 1.35%   |
| Intel Pentium M processor 1.73GHz           | 1         | 0.68%   |
| Intel Pentium Gold 7505 @ 2.00GHz           | 1         | 0.68%   |
| Intel Genuine CPU T2300 @ 1.66GHz           | 1         | 0.68%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.68%   |
| Intel Core i7-8850H CPU @ 2.60GHz           | 1         | 0.68%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.68%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.68%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz          | 1         | 0.68%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 1         | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 56        | 37.84%  |
| Intel Core i7           | 27        | 18.24%  |
| Intel Core i3           | 23        | 15.54%  |
| Intel Core 2 Duo        | 8         | 5.41%   |
| Other                   | 6         | 4.05%   |
| Intel Celeron           | 6         | 4.05%   |
| Intel Atom              | 5         | 3.38%   |
| AMD E1                  | 3         | 2.03%   |
| Intel Pentium Dual-Core | 2         | 1.35%   |
| AMD Ryzen 5             | 2         | 1.35%   |
| AMD C-60                | 2         | 1.35%   |
| Intel Pentium M         | 1         | 0.68%   |
| Intel Pentium Gold      | 1         | 0.68%   |
| Intel Genuine           | 1         | 0.68%   |
| Intel Celeron M         | 1         | 0.68%   |
| AMD Ryzen 7 PRO         | 1         | 0.68%   |
| AMD A8                  | 1         | 0.68%   |
| AMD A6                  | 1         | 0.68%   |
| AMD A4                  | 1         | 0.68%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 97        | 65.54%  |
| 4      | 41        | 27.7%   |
| 1      | 4         | 2.7%    |
| 8      | 3         | 2.03%   |
| 6      | 3         | 2.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 148       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 115       | 77.7%   |
| 1      | 33        | 22.3%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 143       | 96.62%  |
| 32-bit         | 3         | 2.03%   |
| Unknown        | 2         | 1.35%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 20        | 13.25%  |
| 0x206a7    | 16        | 10.6%   |
| 0x806ea    | 10        | 6.62%   |
| 0x306d4    | 10        | 6.62%   |
| 0x306c3    | 9         | 5.96%   |
| 0x306a9    | 8         | 5.3%    |
| 0x40651    | 7         | 4.64%   |
| 0x406e3    | 6         | 3.97%   |
| 0x20655    | 6         | 3.97%   |
| 0x806ec    | 5         | 3.31%   |
| 0x806e9    | 5         | 3.31%   |
| 0x806c1    | 5         | 3.31%   |
| 0x20652    | 5         | 3.31%   |
| 0x1067a    | 5         | 3.31%   |
| 0x506e3    | 3         | 1.99%   |
| 0x30678    | 3         | 1.99%   |
| 0x906ea    | 2         | 1.32%   |
| 0x6fd      | 2         | 1.32%   |
| 0x406c4    | 2         | 1.32%   |
| 0x406c3    | 2         | 1.32%   |
| 0x10676    | 2         | 1.32%   |
| 0x07030105 | 2         | 1.32%   |
| 0x906e9    | 1         | 0.66%   |
| 0x806eb    | 1         | 0.66%   |
| 0x706e5    | 1         | 0.66%   |
| 0x706a1    | 1         | 0.66%   |
| 0x6ec      | 1         | 0.66%   |
| 0x6e8      | 1         | 0.66%   |
| 0x6d8      | 1         | 0.66%   |
| 0x30673    | 1         | 0.66%   |
| 0x30661    | 1         | 0.66%   |
| 0x0a50000c | 1         | 0.66%   |
| 0x08108102 | 1         | 0.66%   |
| 0x0700010f | 1         | 0.66%   |
| 0x06006705 | 1         | 0.66%   |
| 0x05000119 | 1         | 0.66%   |
| 0x05000101 | 1         | 0.66%   |
| 0x03000027 | 1         | 0.66%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 27        | 18.24%  |
| Haswell       | 19        | 12.84%  |
| SandyBridge   | 18        | 12.16%  |
| Westmere      | 11        | 7.43%   |
| Skylake       | 11        | 7.43%   |
| Broadwell     | 10        | 6.76%   |
| Silvermont    | 8         | 5.41%   |
| Penryn        | 8         | 5.41%   |
| IvyBridge     | 8         | 5.41%   |
| TigerLake     | 6         | 4.05%   |
| P6            | 3         | 2.03%   |
| Bobcat        | 3         | 2.03%   |
| Puma          | 2         | 1.35%   |
| Core          | 2         | 1.35%   |
| Bonnell       | 2         | 1.35%   |
| Unknown       | 2         | 1.35%   |
| Zen+          | 1         | 0.68%   |
| Zen 3         | 1         | 0.68%   |
| K10 Llano     | 1         | 0.68%   |
| Jaguar        | 1         | 0.68%   |
| IceLake       | 1         | 0.68%   |
| Goldmont plus | 1         | 0.68%   |
| Excavator     | 1         | 0.68%   |
| CometLake     | 1         | 0.68%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 125       | 69.06%  |
| Nvidia | 34        | 18.78%  |
| AMD    | 22        | 12.15%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17        | 9.29%   |
| Intel UHD Graphics 620                                                                   | 11        | 6.01%   |
| Intel HD Graphics 5500                                                                   | 10        | 5.46%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 5.46%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 4.92%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 4.37%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 3.83%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 3.83%   |
| Intel HD Graphics 620                                                                    | 6         | 3.28%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 2.73%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 2.19%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 2.19%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 2.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 2.19%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 2.19%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 3         | 1.64%   |
| Intel HD Graphics 530                                                                    | 3         | 1.64%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.64%   |
| Nvidia TU117M [GeForce MX450]                                                            | 2         | 1.09%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 1.09%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 1.09%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 2         | 1.09%   |
| Nvidia GF119M [NVS 4200M]                                                                | 2         | 1.09%   |
| Nvidia GF119M [GeForce GT 520M]                                                          | 2         | 1.09%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.09%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.09%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 1.09%   |
| AMD Wrestler [Radeon HD 6290]                                                            | 2         | 1.09%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 1.09%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 2         | 1.09%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                                       | 1         | 0.55%   |
| Nvidia TU104M [GeForce RTX 2080 Mobile]                                                  | 1         | 0.55%   |
| Nvidia GT218M [GeForce G210M]                                                            | 1         | 0.55%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.55%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 0.55%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.55%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.55%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 1         | 0.55%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.55%   |
| Nvidia GM107GLM [Quadro M2000M]                                                          | 1         | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 92        | 62.16%  |
| Intel + Nvidia | 28        | 18.92%  |
| 1 x AMD        | 17        | 11.49%  |
| 1 x Nvidia     | 6         | 4.05%   |
| Intel + AMD    | 5         | 3.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 128       | 84.21%  |
| Proprietary | 18        | 11.84%  |
| Unknown     | 6         | 3.95%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 108       | 71.52%  |
| 1.01-2.0   | 18        | 11.92%  |
| 0.01-0.5   | 15        | 9.93%   |
| 3.01-4.0   | 5         | 3.31%   |
| 0.51-1.0   | 4         | 2.65%   |
| 2.01-3.0   | 1         | 0.66%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 32        | 21.62%  |
| LG Display              | 28        | 18.92%  |
| Chimei Innolux          | 23        | 15.54%  |
| Samsung Electronics     | 20        | 13.51%  |
| BOE                     | 20        | 13.51%  |
| InfoVision              | 4         | 2.7%    |
| Hewlett-Packard         | 4         | 2.7%    |
| LG Philips              | 3         | 2.03%   |
| Lenovo                  | 3         | 2.03%   |
| Dell                    | 3         | 2.03%   |
| Chi Mei Optoelectronics | 3         | 2.03%   |
| Sharp                   | 2         | 1.35%   |
| Apple                   | 2         | 1.35%   |
| LGD                     | 1         | 0.68%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch         | 3         | 2.03%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                    | 3         | 2.03%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch    | 2         | 1.35%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 344x194mm 15.5-inch    | 2         | 1.35%   |
| Samsung Electronics LCD Monitor SDC4D42 1366x768 309x174mm 14.0-inch    | 2         | 1.35%   |
| LG Display LCD Monitor LGD03D9 1366x768 345x194mm 15.6-inch             | 2         | 1.35%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch              | 2         | 1.35%   |
| Dell 2208WFP DEL403B 1680x1050 473x296mm 22.0-inch                      | 2         | 1.35%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                   | 2         | 1.35%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch          | 2         | 1.35%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch          | 2         | 1.35%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch           | 2         | 1.35%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch           | 2         | 1.35%   |
| Sharp LCD Monitor SHP1516 3840x2400 336x210mm 15.6-inch                 | 1         | 0.68%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                 | 1         | 0.68%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch       | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 340x190mm 15.3-inch    | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC434E 1600x900 310x174mm 14.0-inch    | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC4143 1400x1050 286x214mm 14.1-inch   | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC3959 1366x768 344x194mm 15.5-inch    | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC3846 1680x1050 331x207mm 15.4-inch   | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 309x174mm 14.0-inch    | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch    | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch    | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC3051 1366x768 344x194mm 15.5-inch    | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x193mm 15.5-inch    | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch   | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch   | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SAM0FF0 3840x2160 1872x1053mm 84.6-inch | 1         | 0.68%   |
| LGD LCD Monitor 1920x1080                                               | 1         | 0.68%   |
| LG Philips LCD Monitor LPLE300 1280x800 331x207mm 15.4-inch             | 1         | 0.68%   |
| LG Philips LCD Monitor LPLBC00 1280x800 331x207mm 15.4-inch             | 1         | 0.68%   |
| LG Philips LCD Monitor LPL8D00 1280x800 304x190mm 14.1-inch             | 1         | 0.68%   |
| LG Display LCD Monitor LGDD801 1366x768 344x194mm 15.5-inch             | 1         | 0.68%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch            | 1         | 0.68%   |
| LG Display LCD Monitor LGD059D 1920x1080 309x174mm 14.0-inch            | 1         | 0.68%   |
| LG Display LCD Monitor LGD059A 1920x1080 344x194mm 15.5-inch            | 1         | 0.68%   |
| LG Display LCD Monitor LGD0532 1920x1080 344x194mm 15.5-inch            | 1         | 0.68%   |
| LG Display LCD Monitor LGD0504 1366x768 344x194mm 15.5-inch             | 1         | 0.68%   |
| LG Display LCD Monitor LGD04E1 1366x768 344x194mm 15.5-inch             | 1         | 0.68%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 72        | 50.35%  |
| 1920x1080 (FHD)    | 41        | 28.67%  |
| 1600x900 (HD+)     | 11        | 7.69%   |
| 1280x800 (WXGA)    | 6         | 4.2%    |
| 1680x1050 (WSXGA+) | 3         | 2.1%    |
| 1024x600           | 3         | 2.1%    |
| 3840x2160 (4K)     | 2         | 1.4%    |
| 3840x2400          | 1         | 0.7%    |
| 2880x1800          | 1         | 0.7%    |
| 1920x1200 (WUXGA)  | 1         | 0.7%    |
| 1400x1050          | 1         | 0.7%    |
| 1024x768 (XGA)     | 1         | 0.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 85        | 57.43%  |
| 14      | 21        | 14.19%  |
| 13      | 12        | 8.11%   |
| 12      | 8         | 5.41%   |
| 17      | 5         | 3.38%   |
| 24      | 3         | 2.03%   |
| 18      | 3         | 2.03%   |
| 11      | 3         | 2.03%   |
| 23      | 2         | 1.35%   |
| 22      | 2         | 1.35%   |
| 10      | 2         | 1.35%   |
| 84      | 1         | 0.68%   |
| Unknown | 1         | 0.68%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 111       | 75%     |
| 201-300     | 18        | 12.16%  |
| 351-400     | 8         | 5.41%   |
| 501-600     | 5         | 3.38%   |
| 401-500     | 4         | 2.7%    |
| 1501-2000   | 1         | 0.68%   |
| Unknown     | 1         | 0.68%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 127       | 88.81%  |
| 16/10   | 13        | 9.09%   |
| 4/3     | 2         | 1.4%    |
| Unknown | 1         | 0.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 84        | 56.76%  |
| 81-90          | 29        | 19.59%  |
| 61-70          | 8         | 5.41%   |
| 201-250        | 5         | 3.38%   |
| 121-130        | 4         | 2.7%    |
| 71-80          | 3         | 2.03%   |
| 51-60          | 3         | 2.03%   |
| 141-150        | 3         | 2.03%   |
| 41-50          | 2         | 1.35%   |
| 251-300        | 2         | 1.35%   |
| More than 1000 | 1         | 0.68%   |
| 131-140        | 1         | 0.68%   |
| 111-120        | 1         | 0.68%   |
| 91-100         | 1         | 0.68%   |
| Unknown        | 1         | 0.68%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 66        | 44.9%   |
| 121-160       | 52        | 35.37%  |
| 51-100        | 20        | 13.61%  |
| 161-240       | 6         | 4.08%   |
| More than 240 | 2         | 1.36%   |
| Unknown       | 1         | 0.68%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 137       | 91.95%  |
| 2     | 9         | 6.04%   |
| 0     | 3         | 2.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 75        | 32.75%  |
| Realtek Semiconductor    | 70        | 30.57%  |
| Qualcomm Atheros         | 36        | 15.72%  |
| Broadcom                 | 26        | 11.35%  |
| Ralink Technology        | 5         | 2.18%   |
| Ralink                   | 3         | 1.31%   |
| Broadcom Limited         | 3         | 1.31%   |
| Lenovo                   | 2         | 0.87%   |
| Xiaomi                   | 1         | 0.44%   |
| TP-Link                  | 1         | 0.44%   |
| Samsung Electronics      | 1         | 0.44%   |
| Qualcomm                 | 1         | 0.44%   |
| Nvidia                   | 1         | 0.44%   |
| Marvell Technology Group | 1         | 0.44%   |
| JMicron Technology       | 1         | 0.44%   |
| Dell                     | 1         | 0.44%   |
| Arduino SA               | 1         | 0.44%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 45        | 15.46%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 4.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 3.44%   |
| Intel Wireless 8265 / 8275                                        | 9         | 3.09%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 3.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 8         | 2.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 2.41%   |
| Intel Wireless 8260                                               | 7         | 2.41%   |
| Intel Wireless 7265                                               | 7         | 2.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 2.06%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 2.06%   |
| Intel 82577LM Gigabit Network Connection                          | 6         | 2.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 1.72%   |
| Intel Centrino Advanced-N 6235                                    | 5         | 1.72%   |
| Intel Centrino Advanced-N 6200                                    | 5         | 1.72%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 1.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 1.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 1.37%   |
| Ralink MT7601U Wireless Adapter                                   | 4         | 1.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 1.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.37%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 4         | 1.37%   |
| Intel Wireless 7260                                               | 4         | 1.37%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 1.37%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.37%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 1.37%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 1.37%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 1.03%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 1.03%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 1.03%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.03%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 1.03%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 3         | 1.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.69%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.69%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.69%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 2         | 0.69%   |
| Intel WiFi Link 5100                                              | 2         | 0.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 69        | 46%     |
| Qualcomm Atheros      | 31        | 20.67%  |
| Realtek Semiconductor | 20        | 13.33%  |
| Broadcom              | 18        | 12%     |
| Ralink Technology     | 5         | 3.33%   |
| Ralink                | 3         | 2%      |
| Broadcom Limited      | 3         | 2%      |
| TP-Link               | 1         | 0.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 9         | 6%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 9         | 6%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 5.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 4.67%   |
| Intel Wireless 8260                                                     | 7         | 4.67%   |
| Intel Wireless 7265                                                     | 7         | 4.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 4%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 3.33%   |
| Intel Centrino Advanced-N 6235                                          | 5         | 3.33%   |
| Intel Centrino Advanced-N 6200                                          | 5         | 3.33%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 3.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 3.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 2.67%   |
| Ralink MT7601U Wireless Adapter                                         | 4         | 2.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 2.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 2.67%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 4         | 2.67%   |
| Intel Wireless 7260                                                     | 4         | 2.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 2.67%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 2%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 2%      |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 2%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.33%   |
| Intel WiFi Link 5100                                                    | 2         | 1.33%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 1.33%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 1.33%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 2         | 1.33%   |
| Broadcom BCM43225 802.11b/g/n                                           | 2         | 1.33%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.67%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.67%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.67%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 1         | 0.67%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.67%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.67%   |
| Realtek 802.11ac NIC                                                    | 1         | 0.67%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.67%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.67%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.67%   |
| Intel Wireless 3165                                                     | 1         | 0.67%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 64        | 46.38%  |
| Intel                    | 47        | 34.06%  |
| Qualcomm Atheros         | 10        | 7.25%   |
| Broadcom                 | 9         | 6.52%   |
| Lenovo                   | 2         | 1.45%   |
| Xiaomi                   | 1         | 0.72%   |
| Samsung Electronics      | 1         | 0.72%   |
| Qualcomm                 | 1         | 0.72%   |
| Nvidia                   | 1         | 0.72%   |
| Marvell Technology Group | 1         | 0.72%   |
| JMicron Technology       | 1         | 0.72%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 45        | 32.61%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 9.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 7.25%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 4.35%   |
| Intel 82577LM Gigabit Network Connection                          | 6         | 4.35%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 2.9%    |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 2.9%    |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 2.9%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 2.17%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 2.17%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 2.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.45%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.45%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.45%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 2         | 1.45%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.45%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.45%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.45%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 1.45%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.72%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.72%   |
| Qualcomm Mobile Router                                            | 1         | 0.72%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.72%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.72%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.72%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.72%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 0.72%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.72%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.72%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.72%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.72%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.72%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.72%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                 | 1         | 0.72%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.72%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 0.72%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 1         | 0.72%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.72%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 146       | 51.96%  |
| Ethernet | 132       | 46.98%  |
| Modem    | 3         | 1.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 124       | 82.67%  |
| Ethernet | 26        | 17.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 128       | 85.91%  |
| 1     | 17        | 11.41%  |
| 0     | 3         | 2.01%   |
| 3     | 1         | 0.67%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 148       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 45        | 42.86%  |
| Realtek Semiconductor           | 15        | 14.29%  |
| Qualcomm Atheros Communications | 12        | 11.43%  |
| Broadcom                        | 7         | 6.67%   |
| Dell                            | 6         | 5.71%   |
| Lite-On Technology              | 5         | 4.76%   |
| Ralink                          | 3         | 2.86%   |
| IMC Networks                    | 3         | 2.86%   |
| Hewlett-Packard                 | 3         | 2.86%   |
| Toshiba                         | 1         | 0.95%   |
| Foxconn International           | 1         | 0.95%   |
| Foxconn / Hon Hai               | 1         | 0.95%   |
| ASUSTek Computer                | 1         | 0.95%   |
| Apple                           | 1         | 0.95%   |
| Alps Electric                   | 1         | 0.95%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 26        | 24.76%  |
| Realtek Bluetooth Radio                           | 10        | 9.52%   |
| Qualcomm Atheros  Bluetooth Device                | 5         | 4.76%   |
| Intel Centrino Bluetooth Wireless Transceiver     | 5         | 4.76%   |
| Intel AX201 Bluetooth                             | 5         | 4.76%   |
| Realtek  Bluetooth 4.2 Adapter                    | 4         | 3.81%   |
| Qualcomm Atheros AR3011 Bluetooth                 | 4         | 3.81%   |
| Dell DW375 Bluetooth Module                       | 4         | 3.81%   |
| Ralink RT3290 Bluetooth                           | 3         | 2.86%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 3         | 2.86%   |
| Intel Wireless-AC 3168 Bluetooth                  | 3         | 2.86%   |
| IMC Networks Bluetooth Device                     | 3         | 2.86%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 2         | 1.9%    |
| Lite-On Broadcom BCM43142A0 Bluetooth Device      | 2         | 1.9%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 2         | 1.9%    |
| Intel AX200 Bluetooth                             | 2         | 1.9%    |
| HP Broadcom 2070 Bluetooth Combo                  | 2         | 1.9%    |
| Broadcom BCM43142A0 Bluetooth 4.0                 | 2         | 1.9%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]        | 2         | 1.9%    |
| Toshiba Bluetooth Device                          | 1         | 0.95%   |
| Realtek RTL8723B Bluetooth                        | 1         | 0.95%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 1         | 0.95%   |
| Intel Wireless-AC 9260 Bluetooth Adapter          | 1         | 0.95%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter  | 1         | 0.95%   |
| HP Bluetooth 1.2 Interface [Broadcom BCM2035]     | 1         | 0.95%   |
| Foxconn International BCM43142A0 Bluetooth module | 1         | 0.95%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller   | 1         | 0.95%   |
| Dell Wireless 360 Bluetooth                       | 1         | 0.95%   |
| Dell Wireless 350 Bluetooth                       | 1         | 0.95%   |
| Broadcom HP Portable SoftSailing                  | 1         | 0.95%   |
| Broadcom HP Portable Bumble Bee                   | 1         | 0.95%   |
| Broadcom BCM43142 Bluetooth 4.0                   | 1         | 0.95%   |
| ASUS BT-270 Bluetooth Adapter                     | 1         | 0.95%   |
| Apple Built-in Bluetooth 2.0+EDR HCI              | 1         | 0.95%   |
| Alps Electric BCM2046 Bluetooth Device            | 1         | 0.95%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 133       | 77.33%  |
| Nvidia                           | 18        | 10.47%  |
| AMD                              | 16        | 9.3%    |
| Lenovo                           | 2         | 1.16%   |
| Silicon Integrated Systems [SiS] | 1         | 0.58%   |
| Logitech                         | 1         | 0.58%   |
| GN Netcom                        | 1         | 0.58%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 24        | 11.54%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 15        | 7.21%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 11        | 5.29%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 11        | 5.29%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 10        | 4.81%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 10        | 4.81%   |
| Intel Broadwell-U Audio Controller                                                                | 10        | 4.81%   |
| Intel 8 Series HD Audio Controller                                                                | 10        | 4.81%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9         | 4.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 8         | 3.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 2.88%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 2.88%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 4         | 1.92%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 1.92%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.92%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.92%   |
| AMD FCH Azalia Controller                                                                         | 4         | 1.92%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.44%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 1.44%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.44%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 1.44%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.44%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.44%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 1.44%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.96%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 2         | 0.96%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 0.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.96%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.96%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.96%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 0.96%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.48%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.48%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.48%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.48%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.48%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.48%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.48%   |
| Logitech Headset H390                                                                             | 1         | 0.48%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.48%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 26        | 28.57%  |
| SK hynix            | 24        | 26.37%  |
| Micron Technology   | 11        | 12.09%  |
| Kingston            | 11        | 12.09%  |
| Unknown             | 4         | 4.4%    |
| Elpida              | 3         | 3.3%    |
| Crucial             | 3         | 3.3%    |
| Ramaxel Technology  | 2         | 2.2%    |
| A-DATA Technology   | 2         | 2.2%    |
| Transcend           | 1         | 1.1%    |
| Toshiba             | 1         | 1.1%    |
| Sesame              | 1         | 1.1%    |
| Nanya Technology    | 1         | 1.1%    |
| ASint Technology    | 1         | 1.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 4         | 4.04%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 4         | 4.04%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 3         | 3.03%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 2         | 2.02%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s    | 2         | 2.02%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s     | 2         | 2.02%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s  | 2         | 2.02%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s      | 2         | 2.02%   |
| Kingston RAM HP16D3LS1KFG/4G 4096MB SODIMM DDR3 1600MT/s  | 2         | 2.02%   |
| Unknown RAM Module 4GB SODIMM DDR3                        | 1         | 1.01%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1066MT/s            | 1         | 1.01%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                 | 1         | 1.01%   |
| Unknown RAM Module 2048MB SODIMM DDR2                     | 1         | 1.01%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s              | 1         | 1.01%   |
| Transcend RAM JM1333KSN-4G 4096MB SODIMM DDR3 1334MT/s    | 1         | 1.01%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 1066MT/s      | 1         | 1.01%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s           | 1         | 1.01%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s           | 1         | 1.01%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s     | 1         | 1.01%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s | 1         | 1.01%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 1.01%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s | 1         | 1.01%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 1         | 1.01%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 1         | 1.01%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 1.01%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1600MT/s    | 1         | 1.01%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s    | 1         | 1.01%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s | 1         | 1.01%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s    | 1         | 1.01%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s    | 1         | 1.01%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s    | 1         | 1.01%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1334MT/s    | 1         | 1.01%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s   | 1         | 1.01%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s    | 1         | 1.01%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s | 1         | 1.01%   |
| SK hynix RAM H9CCNNN8GTALAR-NUD 2048MB LPDDR3 1600MT/s    | 1         | 1.01%   |
| Sesame RAM S939A2SGS-ITR 8192MB SODIMM DDR4 2667MT/s      | 1         | 1.01%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s               | 1         | 1.01%   |
| Samsung RAM M471B5773EB0-CK0 2048MB SODIMM DDR3 1600MT/s  | 1         | 1.01%   |
| Samsung RAM M471B5674QH0-YK0 2048MB SODIMM DDR3 1600MT/s  | 1         | 1.01%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 39        | 53.42%  |
| DDR4   | 23        | 31.51%  |
| DDR2   | 4         | 5.48%   |
| LPDDR4 | 3         | 4.11%   |
| LPDDR3 | 3         | 4.11%   |
| SDRAM  | 1         | 1.37%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 67        | 94.37%  |
| Row Of Chips | 2         | 2.82%   |
| DIMM         | 1         | 1.41%   |
| Unknown      | 1         | 1.41%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 36        | 46.15%  |
| 8192  | 27        | 34.62%  |
| 2048  | 9         | 11.54%  |
| 16384 | 5         | 6.41%   |
| 1024  | 1         | 1.28%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 27        | 34.18%  |
| 2667    | 14        | 17.72%  |
| 1334    | 9         | 11.39%  |
| 3200    | 6         | 7.59%   |
| 2133    | 4         | 5.06%   |
| 1333    | 4         | 5.06%   |
| 2400    | 3         | 3.8%    |
| 1066    | 2         | 2.53%   |
| 975     | 2         | 2.53%   |
| Unknown | 2         | 2.53%   |
| 4267    | 1         | 1.27%   |
| 4199    | 1         | 1.27%   |
| 3266    | 1         | 1.27%   |
| 1867    | 1         | 1.27%   |
| 1067    | 1         | 1.27%   |
| 667     | 1         | 1.27%   |

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
| Chicony Electronics                    | 38        | 30.65%  |
| IMC Networks                           | 15        | 12.1%   |
| Realtek Semiconductor                  | 12        | 9.68%   |
| Cheng Uei Precision Industry (Foxlink) | 12        | 9.68%   |
| Suyin                                  | 8         | 6.45%   |
| Sunplus Innovation Technology          | 8         | 6.45%   |
| Lite-On Technology                     | 7         | 5.65%   |
| Microdia                               | 6         | 4.84%   |
| Ricoh                                  | 4         | 3.23%   |
| Quanta                                 | 3         | 2.42%   |
| Acer                                   | 3         | 2.42%   |
| Luxvisions Innotech Limited            | 2         | 1.61%   |
| Syntek                                 | 1         | 0.81%   |
| Sunplus Technology                     | 1         | 0.81%   |
| Silicon Motion                         | 1         | 0.81%   |
| Apple                                  | 1         | 0.81%   |
| ALi                                    | 1         | 0.81%   |
| Alcor Micro                            | 1         | 0.81%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 6         | 4.84%   |
| IMC Networks Integrated Camera                              | 4         | 3.23%   |
| Chicony HP Webcam [2 MP Macro]                              | 4         | 3.23%   |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 3         | 2.42%   |
| Realtek USB Camera                                          | 3         | 2.42%   |
| Microdia Integrated Webcam                                  | 3         | 2.42%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 3         | 2.42%   |
| Chicony HP Webcam                                           | 3         | 2.42%   |
| Chicony HP HD Webcam                                        | 3         | 2.42%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 3         | 2.42%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 2         | 1.61%   |
| Sunplus HP Universal Camera                                 | 2         | 1.61%   |
| Ricoh Laptop_Integrated_Webcam_FHD                          | 2         | 1.61%   |
| Realtek Integrated_Webcam_HD                                | 2         | 1.61%   |
| Lite-On TOSHIBA Web Camera - HD                             | 2         | 1.61%   |
| Lite-On HP HD Webcam                                        | 2         | 1.61%   |
| Lite-On HP HD Camera                                        | 2         | 1.61%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 2         | 1.61%   |
| IMC Networks Lenovo EasyCamera                              | 2         | 1.61%   |
| IMC Networks Integrated Webcam                              | 2         | 1.61%   |
| IMC Networks HP TrueVision HD Camera                        | 2         | 1.61%   |
| Chicony Lenovo Integrated Camera (0.3MP)                    | 2         | 1.61%   |
| Chicony Integrated Camera (1280x720@30)                     | 2         | 1.61%   |
| Chicony HP Wide Vision HD Camera                            | 2         | 1.61%   |
| Chicony HP HD Webcam [Fixed]                                | 2         | 1.61%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD     | 2         | 1.61%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 2         | 1.61%   |
| Syntek Lenovo EasyCamera                                    | 1         | 0.81%   |
| Suyin WebCam                                                | 1         | 0.81%   |
| Suyin USB2.0 RGBIR Camera                                   | 1         | 0.81%   |
| Suyin Sony Visual Communication Camera                      | 1         | 0.81%   |
| Suyin Integrated_Webcam_HD                                  | 1         | 0.81%   |
| Suyin Integrated_Webcam_2M                                  | 1         | 0.81%   |
| Suyin HP Webcam-50                                          | 1         | 0.81%   |
| Sunplus 1.3M WebCam                                         | 1         | 0.81%   |
| Sunplus Integrated_Webcam_HD                                | 1         | 0.81%   |
| Sunplus HP Truevision HD                                    | 1         | 0.81%   |
| Sunplus Dell E5570 integrated webcam                        | 1         | 0.81%   |
| Silicon Motion WebCam SC-0311139N                           | 1         | 0.81%   |
| Ricoh Sony Vaio Integrated Webcam                           | 1         | 0.81%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 21        | 67.74%  |
| Synaptics             | 5         | 16.13%  |
| Elan Microelectronics | 4         | 12.9%   |
| Upek                  | 1         | 3.23%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 8         | 25.81%  |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 9.68%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 9.68%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 9.68%   |
| Validity Sensors VFS491                                                    | 2         | 6.45%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 6.45%   |
| Elan ELAN:Fingerprint                                                      | 2         | 6.45%   |
| Elan ELAN:ARM-M4                                                           | 2         | 6.45%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 3.23%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 3.23%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.23%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 3.23%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 3.23%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 3.23%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 11        | 61.11%  |
| Alcor Micro | 5         | 27.78%  |
| O2 Micro    | 2         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 27.78%  |
| Broadcom 5880                                                                | 3         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 11.11%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 5.56%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 5.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 86        | 56.21%  |
| 1     | 51        | 33.33%  |
| 2     | 15        | 9.8%    |
| 3     | 1         | 0.65%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 31        | 37.35%  |
| Chipcard                 | 18        | 21.69%  |
| Graphics card            | 14        | 16.87%  |
| Storage                  | 5         | 6.02%   |
| Net/wireless             | 5         | 6.02%   |
| Bluetooth                | 3         | 3.61%   |
| Communication controller | 2         | 2.41%   |
| Unassigned class         | 1         | 1.2%    |
| Sound                    | 1         | 1.2%    |
| Net/ethernet             | 1         | 1.2%    |
| Modem                    | 1         | 1.2%    |
| Camera                   | 1         | 1.2%    |

