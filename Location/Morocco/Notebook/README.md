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

Total: 295

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X260 20F5S2WX0R    | [cb338af601](https://linux-hardware.org/?probe=cb338af601) | Sep 04, 2023 |
| Acer          | Aspire 5742                 | [ff917b0920](https://linux-hardware.org/?probe=ff917b0920) | Sep 02, 2023 |
| Valve         | Jupiter                     | [6df7fe9dca](https://linux-hardware.org/?probe=6df7fe9dca) | Sep 02, 2023 |
| HP            | Bloog                       | [17077dd340](https://linux-hardware.org/?probe=17077dd340) | Aug 26, 2023 |
| Acer          | Nitro AN515-53              | [368352c126](https://linux-hardware.org/?probe=368352c126) | Jul 12, 2023 |
| Dell          | Latitude 5540               | [bdf022bb03](https://linux-hardware.org/?probe=bdf022bb03) | Jul 02, 2023 |
| Dell          | Latitude 5289               | [cb492423ed](https://linux-hardware.org/?probe=cb492423ed) | Jun 20, 2023 |
| Dell          | Latitude E7450              | [addda016c8](https://linux-hardware.org/?probe=addda016c8) | Jun 18, 2023 |
| ASUSTek       | X540LA                      | [55316783a4](https://linux-hardware.org/?probe=55316783a4) | Jun 16, 2023 |
| ASUSTek       | X540LA                      | [2c1b5651ed](https://linux-hardware.org/?probe=2c1b5651ed) | Jun 15, 2023 |
| ASUSTek       | UX32LN                      | [97ff235920](https://linux-hardware.org/?probe=97ff235920) | Jun 08, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [e92f94ecb3](https://linux-hardware.org/?probe=e92f94ecb3) | May 27, 2023 |
| HUAWEI        | CREM-WXX9                   | [73dfd22efc](https://linux-hardware.org/?probe=73dfd22efc) | May 21, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [7d4516eff2](https://linux-hardware.org/?probe=7d4516eff2) | May 20, 2023 |
| Dell          | Latitude E7450              | [14227e270f](https://linux-hardware.org/?probe=14227e270f) | May 19, 2023 |
| HP            | Pavilion g6                 | [21bf9f3d3f](https://linux-hardware.org/?probe=21bf9f3d3f) | May 12, 2023 |
| Dell          | Latitude 5510               | [2c279a470e](https://linux-hardware.org/?probe=2c279a470e) | May 10, 2023 |
| Lenovo        | ThinkPad T450 20BUS3E800    | [c419e60853](https://linux-hardware.org/?probe=c419e60853) | May 09, 2023 |
| Lenovo        | ThinkPad X201 3680HTG       | [9cb4890df2](https://linux-hardware.org/?probe=9cb4890df2) | May 06, 2023 |
| HP            | Pavilion g6                 | [3c4ec29c8a](https://linux-hardware.org/?probe=3c4ec29c8a) | May 05, 2023 |
| American M... | XA133PR110                  | [4c02a6f8da](https://linux-hardware.org/?probe=4c02a6f8da) | May 03, 2023 |
| HP            | EliteBook 830 G5            | [1979bde291](https://linux-hardware.org/?probe=1979bde291) | May 01, 2023 |
| HP            | 15                          | [17b9906d58](https://linux-hardware.org/?probe=17b9906d58) | May 01, 2023 |
| HP            | 15                          | [8fb1f3c8f8](https://linux-hardware.org/?probe=8fb1f3c8f8) | May 01, 2023 |
| Lenovo        | ThinkPad T430 2349BS7       | [8d832f0261](https://linux-hardware.org/?probe=8d832f0261) | Apr 26, 2023 |
| HP            | ProBook 5320m               | [7597710994](https://linux-hardware.org/?probe=7597710994) | Apr 24, 2023 |
| American M... | XA133PR110                  | [5c634b7029](https://linux-hardware.org/?probe=5c634b7029) | Apr 19, 2023 |
| American M... | XA133PR110                  | [08b47e43a7](https://linux-hardware.org/?probe=08b47e43a7) | Apr 17, 2023 |
| HP            | Laptop 15-dw2xxx            | [e9e05a1bb3](https://linux-hardware.org/?probe=e9e05a1bb3) | Apr 15, 2023 |
| HP            | Laptop 15-dw2xxx            | [0b4fdfd30e](https://linux-hardware.org/?probe=0b4fdfd30e) | Apr 15, 2023 |
| Lenovo        | ThinkPad X201 3680HTG       | [f7029b5f3b](https://linux-hardware.org/?probe=f7029b5f3b) | Apr 14, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [9fbd9476b2](https://linux-hardware.org/?probe=9fbd9476b2) | Mar 28, 2023 |
| Dell          | Latitude 5400               | [4e17f4827d](https://linux-hardware.org/?probe=4e17f4827d) | Mar 23, 2023 |
| Dell          | Latitude 5400               | [c85d243d8a](https://linux-hardware.org/?probe=c85d243d8a) | Mar 23, 2023 |
| Dell          | Vostro 3500                 | [2a85ee4871](https://linux-hardware.org/?probe=2a85ee4871) | Mar 15, 2023 |
| Dell          | Latitude E5450              | [2f16482775](https://linux-hardware.org/?probe=2f16482775) | Mar 04, 2023 |
| HP            | EliteBook 8440p             | [9ce5a599cd](https://linux-hardware.org/?probe=9ce5a599cd) | Mar 03, 2023 |
| Dell          | Latitude E6520              | [2774f2cb16](https://linux-hardware.org/?probe=2774f2cb16) | Mar 01, 2023 |
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
| Ubuntu 20.04       | 34        | 15.67%  |
| Ubuntu 22.04       | 15        | 6.91%   |
| Ubuntu 18.04       | 13        | 5.99%   |
| KDE neon 20.04     | 10        | 4.61%   |
| OpenMandriva 4.3   | 9         | 4.15%   |
| Debian 11          | 9         | 4.15%   |
| Pop!_OS 22.04      | 6         | 2.76%   |
| OpenMandriva 4.2   | 6         | 2.76%   |
| Linux Mint 20.2    | 6         | 2.76%   |
| Zorin 16           | 5         | 2.3%    |
| OpenMandriva 23.01 | 5         | 2.3%    |
| Ubuntu Unity 16.04 | 4         | 1.84%   |
| Ubuntu 20.10       | 4         | 1.84%   |
| Ubuntu 19.10       | 4         | 1.84%   |
| Linux Mint 20.3    | 4         | 1.84%   |
| ArcoLinux Rolling  | 4         | 1.84%   |
| Arch               | 4         | 1.84%   |
| Manjaro            | 3         | 1.38%   |
| Linux Mint 21.1    | 3         | 1.38%   |
| Fedora 38          | 3         | 1.38%   |
| Xubuntu 20.04      | 2         | 0.92%   |
| Xero Rolling       | 2         | 0.92%   |
| Void Linux         | 2         | 0.92%   |
| Ubuntu 21.10       | 2         | 0.92%   |
| Ubuntu 21.04       | 2         | 0.92%   |
| Pop!_OS 21.10      | 2         | 0.92%   |
| Linux Mint 21      | 2         | 0.92%   |
| Linux Mint 19.3    | 2         | 0.92%   |
| Kali 2019.4        | 2         | 0.92%   |
| Fedora 37          | 2         | 0.92%   |
| Fedora 36          | 2         | 0.92%   |
| Zorin 15           | 1         | 0.46%   |
| Ubuntu Unity 20.04 | 1         | 0.46%   |
| Ubuntu MATE 22.10  | 1         | 0.46%   |
| Ubuntu MATE 20.04  | 1         | 0.46%   |
| Ubuntu 19.04       | 1         | 0.46%   |
| Ubuntu 16.04       | 1         | 0.46%   |
| Ubuntu             | 1         | 0.46%   |
| SteamOS 3.4.10     | 1         | 0.46%   |
| SteamOS            | 1         | 0.46%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 71        | 34.63%  |
| OpenMandriva | 19        | 9.27%   |
| Linux Mint   | 17        | 8.29%   |
| KDE neon     | 11        | 5.37%   |
| Debian       | 11        | 5.37%   |
| Pop!_OS      | 10        | 4.88%   |
| Fedora       | 8         | 3.9%    |
| Kali         | 7         | 3.41%   |
| Zorin        | 6         | 2.93%   |
| Manjaro      | 6         | 2.93%   |
| Ubuntu Unity | 5         | 2.44%   |
| Arch         | 5         | 2.44%   |
| ArcoLinux    | 4         | 1.95%   |
| Endless      | 3         | 1.46%   |
| Xubuntu      | 2         | 0.98%   |
| Xero         | 2         | 0.98%   |
| Void Linux   | 2         | 0.98%   |
| Ubuntu MATE  | 2         | 0.98%   |
| SteamOS      | 2         | 0.98%   |
| openSUSE     | 2         | 0.98%   |
| EndeavourOS  | 2         | 0.98%   |
| Elementary   | 2         | 0.98%   |
| RHEL         | 1         | 0.49%   |
| Parrot       | 1         | 0.49%   |
| Nobara       | 1         | 0.49%   |
| CentOS       | 1         | 0.49%   |
| BunsenLabs   | 1         | 0.49%   |
| blendOS      | 1         | 0.49%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 9         | 3.91%   |
| 5.10.14-desktop-1omv4002 | 6         | 2.61%   |
| 6.1.1-desktop-1omv2290   | 5         | 2.17%   |
| 5.13.0-40-generic        | 5         | 2.17%   |
| 5.8.0-43-generic         | 4         | 1.74%   |
| 5.4.0-58-generic         | 4         | 1.74%   |
| 5.4.0-48-generic         | 4         | 1.74%   |
| 5.4.0-42-generic         | 3         | 1.3%    |
| 5.3.0-40-generic         | 3         | 1.3%    |
| 5.17.5-76051705-generic  | 3         | 1.3%    |
| 5.13.0-27-generic        | 3         | 1.3%    |
| 5.11.0-37-generic        | 3         | 1.3%    |
| 6.2.6-76060206-generic   | 2         | 0.87%   |
| 6.2.14-300.fc38.x86_64   | 2         | 0.87%   |
| 5.8.0-48-generic         | 2         | 0.87%   |
| 5.8.0-38-generic         | 2         | 0.87%   |
| 5.8.0-33-generic         | 2         | 0.87%   |
| 5.4.0-96-generic         | 2         | 0.87%   |
| 5.4.0-88-generic         | 2         | 0.87%   |
| 5.4.0-65-generic         | 2         | 0.87%   |
| 5.4.0-37-generic         | 2         | 0.87%   |
| 5.4.0-33-generic         | 2         | 0.87%   |
| 5.4.0-29-generic         | 2         | 0.87%   |
| 5.3.0-kali2-686-pae      | 2         | 0.87%   |
| 5.3.0-51-generic         | 2         | 0.87%   |
| 5.3.0-28-generic         | 2         | 0.87%   |
| 5.19.0-41-generic        | 2         | 0.87%   |
| 5.19.0-38-generic        | 2         | 0.87%   |
| 5.18.19_1                | 2         | 0.87%   |
| 5.15.0-58-generic        | 2         | 0.87%   |
| 5.15.0-53-generic        | 2         | 0.87%   |
| 5.15.0-50-generic        | 2         | 0.87%   |
| 5.15.0-46-generic        | 2         | 0.87%   |
| 5.14.14-arch1-1          | 2         | 0.87%   |
| 5.13.0-19-generic        | 2         | 0.87%   |
| 5.11.0-7612-generic      | 2         | 0.87%   |
| 5.11.0-46-generic        | 2         | 0.87%   |
| 5.11.0-36-generic        | 2         | 0.87%   |
| 5.10.0-21-amd64          | 2         | 0.87%   |
| 5.0.0-23-generic         | 2         | 0.87%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 34        | 15.81%  |
| 5.15.0  | 16        | 7.44%   |
| 5.8.0   | 14        | 6.51%   |
| 5.13.0  | 13        | 6.05%   |
| 5.11.0  | 12        | 5.58%   |
| 4.15.0  | 12        | 5.58%   |
| 5.3.0   | 10        | 4.65%   |
| 5.10.0  | 10        | 4.65%   |
| 5.16.7  | 9         | 4.19%   |
| 5.19.0  | 8         | 3.72%   |
| 5.10.14 | 6         | 2.79%   |
| 5.0.0   | 6         | 2.79%   |
| 6.1.1   | 5         | 2.33%   |
| 6.2.6   | 3         | 1.4%    |
| 5.17.5  | 3         | 1.4%    |
| 4.18.0  | 3         | 1.4%    |
| 6.2.14  | 2         | 0.93%   |
| 6.1.0   | 2         | 0.93%   |
| 5.18.19 | 2         | 0.93%   |
| 5.16.0  | 2         | 0.93%   |
| 5.14.14 | 2         | 0.93%   |
| 4.19.0  | 2         | 0.93%   |
| 6.4.9   | 1         | 0.47%   |
| 6.3.7   | 1         | 0.47%   |
| 6.3.6   | 1         | 0.47%   |
| 6.3.4   | 1         | 0.47%   |
| 6.3.2   | 1         | 0.47%   |
| 6.2.9   | 1         | 0.47%   |
| 6.2.10  | 1         | 0.47%   |
| 6.2.0   | 1         | 0.47%   |
| 6.1.7   | 1         | 0.47%   |
| 6.1.6   | 1         | 0.47%   |
| 6.0.14  | 1         | 0.47%   |
| 6.0.12  | 1         | 0.47%   |
| 6.0.0   | 1         | 0.47%   |
| 5.8.15  | 1         | 0.47%   |
| 5.8.1   | 1         | 0.47%   |
| 5.7.15  | 1         | 0.47%   |
| 5.19.9  | 1         | 0.47%   |
| 5.19.16 | 1         | 0.47%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 34        | 15.81%  |
| 5.15    | 22        | 10.23%  |
| 5.10    | 17        | 7.91%   |
| 5.8     | 16        | 7.44%   |
| 5.13    | 14        | 6.51%   |
| 5.11    | 14        | 6.51%   |
| 5.16    | 12        | 5.58%   |
| 4.15    | 12        | 5.58%   |
| 5.19    | 11        | 5.12%   |
| 5.3     | 10        | 4.65%   |
| 6.1     | 9         | 4.19%   |
| 6.2     | 8         | 3.72%   |
| 5.17    | 6         | 2.79%   |
| 5.0     | 6         | 2.79%   |
| 6.3     | 4         | 1.86%   |
| 5.18    | 4         | 1.86%   |
| 6.0     | 3         | 1.4%    |
| 5.14    | 3         | 1.4%    |
| 4.18    | 3         | 1.4%    |
| 4.19    | 2         | 0.93%   |
| 6.4     | 1         | 0.47%   |
| 5.7     | 1         | 0.47%   |
| 4.4     | 1         | 0.47%   |
| 4.14    | 1         | 0.47%   |
| 4.13    | 1         | 0.47%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 195       | 96.53%  |
| i686   | 7         | 3.47%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 104       | 50.24%  |
| KDE5            | 40        | 19.32%  |
| Unknown         | 14        | 6.76%   |
| X-Cinnamon      | 13        | 6.28%   |
| XFCE            | 12        | 5.8%    |
| KDE             | 7         | 3.38%   |
| Unity           | 5         | 2.42%   |
| MATE            | 3         | 1.45%   |
| Pantheon        | 2         | 0.97%   |
| Cinnamon        | 2         | 0.97%   |
| xmonad          | 1         | 0.48%   |
| sway            | 1         | 0.48%   |
| i3              | 1         | 0.48%   |
| GNOME Flashback | 1         | 0.48%   |
| Budgie          | 1         | 0.48%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 162       | 78.26%  |
| Wayland | 37        | 17.87%  |
| Unknown | 7         | 3.38%   |
| Tty     | 1         | 0.48%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 104       | 49.29%  |
| SDDM    | 35        | 16.59%  |
| GDM     | 30        | 14.22%  |
| GDM3    | 21        | 9.95%   |
| LightDM | 18        | 8.53%   |
| TDM     | 3         | 1.42%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 117       | 57.64%  |
| fr_FR   | 55        | 27.09%  |
| Unknown | 13        | 6.4%    |
| en_GB   | 8         | 3.94%   |
| de_DE   | 3         | 1.48%   |
| fr_MA   | 1         | 0.49%   |
| fr_BE   | 1         | 0.49%   |
| es_ES   | 1         | 0.49%   |
| en_AG   | 1         | 0.49%   |
| C       | 1         | 0.49%   |
| ar_MA   | 1         | 0.49%   |
| ar_EG   | 1         | 0.49%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 122       | 60.1%   |
| EFI  | 81        | 39.9%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 163       | 80.3%   |
| Overlay | 21        | 10.34%  |
| Btrfs   | 14        | 6.9%    |
| Xfs     | 2         | 0.99%   |
| Unknown | 2         | 0.99%   |
| Tmpfs   | 1         | 0.49%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 104       | 50.73%  |
| GPT     | 66        | 32.2%   |
| MBR     | 35        | 17.07%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 176       | 86.7%   |
| Yes       | 27        | 13.3%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 137       | 67.16%  |
| Yes       | 67        | 32.84%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 63        | 31.19%  |
| Dell                | 37        | 18.32%  |
| Lenovo              | 35        | 17.33%  |
| ASUSTek Computer    | 17        | 8.42%   |
| Acer                | 9         | 4.46%   |
| Toshiba             | 8         | 3.96%   |
| Sony                | 3         | 1.49%   |
| Packard Bell        | 3         | 1.49%   |
| Apple               | 3         | 1.49%   |
| Timi                | 2         | 0.99%   |
| Samsung Electronics | 2         | 0.99%   |
| HUAWEI              | 2         | 0.99%   |
| eMachines           | 2         | 0.99%   |
| Unknown             | 2         | 0.99%   |
| Valve               | 1         | 0.5%    |
| TUXEDO              | 1         | 0.5%    |
| TrekStor            | 1         | 0.5%    |
| SINTRONES           | 1         | 0.5%    |
| Razer               | 1         | 0.5%    |
| Medion              | 1         | 0.5%    |
| Mediacom            | 1         | 0.5%    |
| GPD                 | 1         | 0.5%    |
| Google              | 1         | 0.5%    |
| Gigabyte Technology | 1         | 0.5%    |
| Fujitsu Siemens     | 1         | 0.5%    |
| Clevo               | 1         | 0.5%    |
| Casper              | 1         | 0.5%    |
| American Megatrends | 1         | 0.5%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| HP EliteBook 8440p                         | 4         | 1.98%   |
| HP Pavilion g6                             | 3         | 1.49%   |
| HP Laptop 15-dw3xxx                        | 3         | 1.49%   |
| HP EliteBook 840 G2                        | 3         | 1.49%   |
| ASUS X540LA                                | 3         | 1.49%   |
| Unknown                                    | 3         | 1.49%   |
| Timi TM1701                                | 2         | 0.99%   |
| Lenovo ThinkBook 15 G2 ITL 20VE            | 2         | 0.99%   |
| Lenovo IdeaPad L3 15IML05 81Y3             | 2         | 0.99%   |
| HP ZBook 15                                | 2         | 0.99%   |
| HP ProBook 650 G1                          | 2         | 0.99%   |
| HP ProBook 6470b                           | 2         | 0.99%   |
| HP Notebook                                | 2         | 0.99%   |
| HP EliteBook 8460p                         | 2         | 0.99%   |
| HP 250 G5 Notebook PC                      | 2         | 0.99%   |
| Dell Latitude E7450                        | 2         | 0.99%   |
| Dell Latitude E6520                        | 2         | 0.99%   |
| Dell Latitude E6410                        | 2         | 0.99%   |
| Acer Aspire ES1-523                        | 2         | 0.99%   |
| Valve Jupiter                              | 1         | 0.5%    |
| TUXEDO N13xWU                              | 1         | 0.5%    |
| TrekStor Surfbook W2                       | 1         | 0.5%    |
| Toshiba Satellite Pro C650                 | 1         | 0.5%    |
| Toshiba Satellite L750                     | 1         | 0.5%    |
| Toshiba Satellite L50-B                    | 1         | 0.5%    |
| Toshiba Satellite L50-A-1EL                | 1         | 0.5%    |
| Toshiba Satellite L50-A-1DG                | 1         | 0.5%    |
| Toshiba Satellite C855-2CF                 | 1         | 0.5%    |
| Toshiba Satellite C855-1LG                 | 1         | 0.5%    |
| Toshiba Satellite C660                     | 1         | 0.5%    |
| Sony VPCEH1L8E                             | 1         | 0.5%    |
| Sony VGN-FW11L                             | 1         | 0.5%    |
| Sony SVE14122CAW                           | 1         | 0.5%    |
| SINTRONES AMB-5000G1                       | 1         | 0.5%    |
| Samsung 355V4C/356V4C/3445VC/3545VC        | 1         | 0.5%    |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 0.5%    |
| Razer Blade Pro 17 (2019)                  | 1         | 0.5%    |
| Packard Bell EasyNote TS44HR               | 1         | 0.5%    |
| Packard Bell EasyNote TS11HR               | 1         | 0.5%    |
| Packard Bell EasyNote TK85                 | 1         | 0.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Dell Latitude         | 30        | 14.85%  |
| Lenovo ThinkPad       | 21        | 10.4%   |
| HP EliteBook          | 18        | 8.91%   |
| HP Pavilion           | 10        | 4.95%   |
| HP ProBook            | 9         | 4.46%   |
| HP Laptop             | 9         | 4.46%   |
| Toshiba Satellite     | 8         | 3.96%   |
| Acer Aspire           | 6         | 2.97%   |
| Lenovo IdeaPad        | 5         | 2.48%   |
| HP 250                | 4         | 1.98%   |
| Packard Bell EasyNote | 3         | 1.49%   |
| Lenovo ThinkBook      | 3         | 1.49%   |
| HP ZBook              | 3         | 1.49%   |
| ASUS X540LA           | 3         | 1.49%   |
| Unknown               | 3         | 1.49%   |
| Timi TM1701           | 2         | 0.99%   |
| HP Notebook           | 2         | 0.99%   |
| HP Compaq             | 2         | 0.99%   |
| Dell Vostro           | 2         | 0.99%   |
| Dell Precision        | 2         | 0.99%   |
| Dell Inspiron         | 2         | 0.99%   |
| Valve Jupiter         | 1         | 0.5%    |
| TUXEDO N13xWU         | 1         | 0.5%    |
| TrekStor Surfbook     | 1         | 0.5%    |
| Sony VPCEH1L8E        | 1         | 0.5%    |
| Sony VGN-FW11L        | 1         | 0.5%    |
| Sony SVE14122CAW      | 1         | 0.5%    |
| SINTRONES AMB-5000G1  | 1         | 0.5%    |
| Samsung 355V4C        | 1         | 0.5%    |
| Samsung 300E4A        | 1         | 0.5%    |
| Razer Blade           | 1         | 0.5%    |
| Medion P7615          | 1         | 0.5%    |
| Mediacom WinPad       | 1         | 0.5%    |
| Lenovo Z70-80         | 1         | 0.5%    |
| Lenovo V310-15IKB     | 1         | 0.5%    |
| Lenovo S21e-20        | 1         | 0.5%    |
| Lenovo IdeaPadFlex    | 1         | 0.5%    |
| Lenovo G50-70         | 1         | 0.5%    |
| Lenovo B50-30         | 1         | 0.5%    |
| HUAWEI NBLB-WAX9N     | 1         | 0.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2010 | 21        | 10.4%   |
| 2013 | 20        | 9.9%    |
| 2011 | 20        | 9.9%    |
| 2014 | 18        | 8.91%   |
| 2016 | 17        | 8.42%   |
| 2018 | 16        | 7.92%   |
| 2015 | 15        | 7.43%   |
| 2020 | 14        | 6.93%   |
| 2017 | 12        | 5.94%   |
| 2012 | 11        | 5.45%   |
| 2021 | 10        | 4.95%   |
| 2019 | 10        | 4.95%   |
| 2009 | 5         | 2.48%   |
| 2008 | 4         | 1.98%   |
| 2007 | 3         | 1.49%   |
| 2022 | 2         | 0.99%   |
| 2006 | 2         | 0.99%   |
| 2023 | 1         | 0.5%    |
| 2005 | 1         | 0.5%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 202       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 192       | 93.66%  |
| Enabled  | 13        | 6.34%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 200       | 99.01%  |
| Yes  | 2         | 0.99%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 73        | 35.78%  |
| 3.01-4.0   | 55        | 26.96%  |
| 8.01-16.0  | 29        | 14.22%  |
| 16.01-24.0 | 22        | 10.78%  |
| 1.01-2.0   | 12        | 5.88%   |
| 32.01-64.0 | 4         | 1.96%   |
| 2.01-3.0   | 4         | 1.96%   |
| 24.01-32.0 | 3         | 1.47%   |
| 0.51-1.0   | 2         | 0.98%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 81        | 36.99%  |
| 2.01-3.0  | 67        | 30.59%  |
| 4.01-8.0  | 30        | 13.7%   |
| 3.01-4.0  | 29        | 13.24%  |
| 0.51-1.0  | 9         | 4.11%   |
| 8.01-16.0 | 3         | 1.37%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 171       | 83.82%  |
| 2      | 29        | 14.22%  |
| 3      | 4         | 1.96%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 107       | 52.97%  |
| Yes       | 95        | 47.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 179       | 88.61%  |
| No        | 23        | 11.39%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 200       | 98.52%  |
| No        | 3         | 1.48%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 147       | 71.71%  |
| No        | 58        | 28.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Morocco | 202       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Casablanca       | 47        | 21.76%  |
| Rabat            | 21        | 9.72%   |
| Marrakesh        | 21        | 9.72%   |
| Fes              | 15        | 6.94%   |
| Agadir           | 15        | 6.94%   |
| Tangier          | 11        | 5.09%   |
| Kenitra          | 11        | 5.09%   |
| Salé            | 10        | 4.63%   |
| Oujda            | 8         | 3.7%    |
| Meknes           | 7         | 3.24%   |
| Khouribga        | 7         | 3.24%   |
| Nador            | 5         | 2.31%   |
| Tiznit           | 3         | 1.39%   |
| El Jadida        | 3         | 1.39%   |
| Beni Mellal      | 3         | 1.39%   |
| Temara           | 2         | 0.93%   |
| Taza             | 2         | 0.93%   |
| Guelmim          | 2         | 0.93%   |
| Youssoufia       | 1         | 0.46%   |
| Tit Mellil       | 1         | 0.46%   |
| Tétouan         | 1         | 0.46%   |
| Targuist         | 1         | 0.46%   |
| Taourirt         | 1         | 0.46%   |
| Skhirate         | 1         | 0.46%   |
| Sidi Slimane     | 1         | 0.46%   |
| Sidi Kacem       | 1         | 0.46%   |
| Settat           | 1         | 0.46%   |
| Sefrou           | 1         | 0.46%   |
| Safi             | 1         | 0.46%   |
| Mohammedia       | 1         | 0.46%   |
| Midelt           | 1         | 0.46%   |
| Ksar El Kebir    | 1         | 0.46%   |
| Khemisset        | 1         | 0.46%   |
| Karia Ba Mohamed | 1         | 0.46%   |
| Inezgane         | 1         | 0.46%   |
| Errachidia       | 1         | 0.46%   |
| Berkane          | 1         | 0.46%   |
| Aousserd         | 1         | 0.46%   |
| Al Aaroui        | 1         | 0.46%   |
| Agdz             | 1         | 0.46%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 39        | 48     | 17.03%  |
| Toshiba                     | 31        | 39     | 13.54%  |
| Samsung Electronics         | 28        | 35     | 12.23%  |
| WDC                         | 27        | 35     | 11.79%  |
| Unknown                     | 13        | 19     | 5.68%   |
| SanDisk                     | 10        | 10     | 4.37%   |
| Hitachi                     | 9         | 10     | 3.93%   |
| HGST                        | 7         | 7      | 3.06%   |
| Kingston                    | 6         | 7      | 2.62%   |
| Intel                       | 6         | 7      | 2.62%   |
| SK hynix                    | 5         | 5      | 2.18%   |
| Apple                       | 5         | 5      | 2.18%   |
| KIOXIA                      | 4         | 4      | 1.75%   |
| PNY                         | 3         | 4      | 1.31%   |
| LITEON                      | 3         | 3      | 1.31%   |
| China                       | 3         | 4      | 1.31%   |
| Micron Technology           | 2         | 3      | 0.87%   |
| KingDian                    | 2         | 6      | 0.87%   |
| GOODRAM                     | 2         | 2      | 0.87%   |
| Fujitsu                     | 2         | 2      | 0.87%   |
| Crucial                     | 2         | 2      | 0.87%   |
| Unknown                     | 2         | 2      | 0.87%   |
| TwinMOS                     | 1         | 1      | 0.44%   |
| Transcend                   | 1         | 1      | 0.44%   |
| ShiJi                       | 1         | 2      | 0.44%   |
| RCESSD                      | 1         | 1      | 0.44%   |
| Phison                      | 1         | 1      | 0.44%   |
| O2 Micro                    | 1         | 1      | 0.44%   |
| LITEONIT                    | 1         | 1      | 0.44%   |
| Kingston Technology Company | 1         | 1      | 0.44%   |
| KingSpec                    | 1         | 1      | 0.44%   |
| KingFast                    | 1         | 2      | 0.44%   |
| Intenso                     | 1         | 2      | 0.44%   |
| Indilinx                    | 1         | 1      | 0.44%   |
| IBM/Hitachi                 | 1         | 1      | 0.44%   |
| Hewlett-Packard             | 1         | 1      | 0.44%   |
| BIWIN                       | 1         | 1      | 0.44%   |
| Apacer                      | 1         | 1      | 0.44%   |
| A-DATA Technology           | 1         | 1      | 0.44%   |
| 2.5"                        | 1         | 1      | 0.44%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB        | 5         | 2.1%    |
| Seagate ST1000LM035-1RK172 1TB         | 5         | 2.1%    |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 5         | 2.1%    |
| Toshiba MQ04ABF100 1TB                 | 4         | 1.68%   |
| Samsung NVMe SSD Drive 512GB           | 4         | 1.68%   |
| Toshiba MQ01ACF050 500GB               | 3         | 1.26%   |
| Toshiba MQ01ABF050 500GB               | 3         | 1.26%   |
| Toshiba MQ01ABD050 500GB               | 3         | 1.26%   |
| Seagate ST9500325AS 500GB              | 3         | 1.26%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB | 3         | 1.26%   |
| HGST HTS545050A7E680 500GB             | 3         | 1.26%   |
| WDC WD5000LPCX-80VHAT1 500GB           | 2         | 0.84%   |
| WDC WD5000LPCX-60VHAT0 500GB           | 2         | 0.84%   |
| WDC WD1600BEVT-22ZCT0 160GB            | 2         | 0.84%   |
| WDC WD10SPZX-60Z10T0 1TB               | 2         | 0.84%   |
| Unknown MMC Card  32GB                 | 2         | 0.84%   |
| Unknown MMC Card  16GB                 | 2         | 0.84%   |
| Toshiba MQ01ABD100 1TB                 | 2         | 0.84%   |
| Seagate ST500VT000-1DK142 500GB        | 2         | 0.84%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 2         | 0.84%   |
| Seagate ST500LM000-1EJ162 500GB        | 2         | 0.84%   |
| Samsung MZVLW256HEHP-000L7 256GB       | 2         | 0.84%   |
| Hitachi HTS723232A7A364 320GB          | 2         | 0.84%   |
| Hitachi HTS542525K9A300 250GB          | 2         | 0.84%   |
| HGST HTS725050A7E630 500GB             | 2         | 0.84%   |
| Unknown                                | 2         | 0.84%   |
| WDC WDS256G1X0C-00ENX0 256GB           | 1         | 0.42%   |
| WDC WD5000LPCX-60VHAT1 500GB           | 1         | 0.42%   |
| WDC WD5000BPVT-22HXZT1 500GB           | 1         | 0.42%   |
| WDC WD3200BUCT-63TWBY0 320GB           | 1         | 0.42%   |
| WDC WD3200BPVT-24JJ5T0 320GB           | 1         | 0.42%   |
| WDC WD3200BPVT-22ZEST0 320GB           | 1         | 0.42%   |
| WDC WD3200BEVT-60ZCT1 320GB            | 1         | 0.42%   |
| WDC WD2500BPVT-22ZEST0 250GB           | 1         | 0.42%   |
| WDC WD2500BEVT-22A23T0 208GB           | 1         | 0.42%   |
| WDC WD2500BEKT-60V5T1 250GB            | 1         | 0.42%   |
| WDC WD2500BEKT-60A25T1 250GB           | 1         | 0.42%   |
| WDC WD1600BEVS-60VAT0 160GB            | 1         | 0.42%   |
| WDC WD10SPZX-08Z10 1TB                 | 1         | 0.42%   |
| WDC WD10SPCX-24HWST0 1TB               | 1         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 39        | 48     | 34.82%  |
| Toshiba             | 26        | 30     | 23.21%  |
| WDC                 | 24        | 32     | 21.43%  |
| Hitachi             | 9         | 10     | 8.04%   |
| HGST                | 7         | 7      | 6.25%   |
| Samsung Electronics | 2         | 2      | 1.79%   |
| Fujitsu             | 2         | 2      | 1.79%   |
| Apple               | 2         | 2      | 1.79%   |
| IBM/Hitachi         | 1         | 1      | 0.89%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 8         | 8      | 13.56%  |
| Samsung Electronics | 8         | 11     | 13.56%  |
| Kingston            | 5         | 6      | 8.47%   |
| SK hynix            | 3         | 3      | 5.08%   |
| PNY                 | 3         | 4      | 5.08%   |
| LITEON              | 3         | 3      | 5.08%   |
| China               | 3         | 4      | 5.08%   |
| Micron Technology   | 2         | 3      | 3.39%   |
| KingDian            | 2         | 6      | 3.39%   |
| Intel               | 2         | 3      | 3.39%   |
| GOODRAM             | 2         | 2      | 3.39%   |
| Crucial             | 2         | 2      | 3.39%   |
| Apple               | 2         | 2      | 3.39%   |
| TwinMOS             | 1         | 1      | 1.69%   |
| Transcend           | 1         | 1      | 1.69%   |
| Toshiba             | 1         | 1      | 1.69%   |
| RCESSD              | 1         | 1      | 1.69%   |
| LITEONIT            | 1         | 1      | 1.69%   |
| KingSpec            | 1         | 1      | 1.69%   |
| KingFast            | 1         | 1      | 1.69%   |
| Indilinx            | 1         | 1      | 1.69%   |
| Hewlett-Packard     | 1         | 1      | 1.69%   |
| BIWIN               | 1         | 1      | 1.69%   |
| Apacer              | 1         | 1      | 1.69%   |
| A-DATA Technology   | 1         | 1      | 1.69%   |
| 2.5"                | 1         | 1      | 1.69%   |
| Unknown             | 1         | 1      | 1.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 111       | 134    | 49.78%  |
| SSD     | 57        | 71     | 25.56%  |
| NVMe    | 39        | 50     | 17.49%  |
| MMC     | 13        | 19     | 5.83%   |
| Unknown | 3         | 6      | 1.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 161       | 209    | 75.23%  |
| NVMe | 39        | 50     | 18.22%  |
| MMC  | 13        | 19     | 6.07%   |
| SAS  | 1         | 2      | 0.47%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 124       | 151    | 75.15%  |
| 0.51-1.0   | 40        | 53     | 24.24%  |
| 1.01-2.0   | 1         | 1      | 0.61%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 58        | 28.02%  |
| 251-500        | 57        | 27.54%  |
| 51-100         | 26        | 12.56%  |
| 501-1000       | 20        | 9.66%   |
| 1-20           | 19        | 9.18%   |
| 21-50          | 16        | 7.73%   |
| 1001-2000      | 6         | 2.9%    |
| Unknown        | 3         | 1.45%   |
| More than 3000 | 1         | 0.48%   |
| 2001-3000      | 1         | 0.48%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 93        | 42.47%  |
| 21-50          | 53        | 24.2%   |
| 101-250        | 30        | 13.7%   |
| 51-100         | 29        | 13.24%  |
| 251-500        | 7         | 3.2%    |
| Unknown        | 3         | 1.37%   |
| 501-1000       | 2         | 0.91%   |
| More than 3000 | 1         | 0.46%   |
| 1001-2000      | 1         | 0.46%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                        | 3         | 3      | 10.71%  |
| Toshiba MQ01ABD050 500GB                         | 2         | 2      | 7.14%   |
| Hitachi HTS542525K9A300 250GB                    | 2         | 2      | 7.14%   |
| WDC WD5000BPVT-22HXZT1 500GB                     | 1         | 1      | 3.57%   |
| WDC WD2500BEKT-60A25T1 250GB                     | 1         | 1      | 3.57%   |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 5      | 3.57%   |
| Toshiba MQ04ABF100 1TB                           | 1         | 1      | 3.57%   |
| Toshiba MQ01ACF050 500GB                         | 1         | 1      | 3.57%   |
| Toshiba MQ01ABD032 320GB                         | 1         | 1      | 3.57%   |
| Toshiba MK2565GSXN 250GB                         | 1         | 1      | 3.57%   |
| Toshiba MK1237GSX 120GB                          | 1         | 1      | 3.57%   |
| Seagate ST9320423AS 320GB                        | 1         | 1      | 3.57%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 3.57%   |
| Seagate ST500LM021-1KJ152 500GB                  | 1         | 1      | 3.57%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 3.57%   |
| Seagate ST500LM000-1EJ162 500GB                  | 1         | 1      | 3.57%   |
| SanDisk SD7UB3Q256G1001 256GB SSD                | 1         | 1      | 3.57%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 3.57%   |
| Micron Technology 1100 SATA 256GB SSD            | 1         | 1      | 3.57%   |
| Hitachi HTS723232A7A364 320GB                    | 1         | 1      | 3.57%   |
| Hitachi HTS545050A7E380 500GB                    | 1         | 2      | 3.57%   |
| HGST HTS545050A7E680 500GB                       | 1         | 1      | 3.57%   |
| Fujitsu MHW2120BH 120GB                          | 1         | 1      | 3.57%   |
| Apple HDD HTS541010A9E662 1TB                    | 1         | 1      | 3.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 28.57%  |
| Toshiba             | 7         | 7      | 25%     |
| Hitachi             | 4         | 5      | 14.29%  |
| WDC                 | 3         | 7      | 10.71%  |
| SanDisk             | 1         | 1      | 3.57%   |
| Samsung Electronics | 1         | 1      | 3.57%   |
| Micron Technology   | 1         | 1      | 3.57%   |
| HGST                | 1         | 1      | 3.57%   |
| Fujitsu             | 1         | 1      | 3.57%   |
| Apple               | 1         | 1      | 3.57%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 8      | 32%     |
| Toshiba | 7         | 7      | 28%     |
| Hitachi | 4         | 5      | 16%     |
| WDC     | 3         | 7      | 12%     |
| HGST    | 1         | 1      | 4%      |
| Fujitsu | 1         | 1      | 4%      |
| Apple   | 1         | 1      | 4%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 25        | 30     | 89.29%  |
| SSD  | 3         | 3      | 10.71%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                      | Notebooks | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| WDC WD2500BEVT-22A23T0 208GB               | 1         | 2      | 50%     |
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
| Detected | 124       | 168    | 57.41%  |
| Works    | 62        | 76     | 28.7%   |
| Malfunc  | 28        | 33     | 12.96%  |
| Failed   | 2         | 3      | 0.93%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 165       | 76.04%  |
| Samsung Electronics              | 19        | 8.76%   |
| AMD                              | 13        | 5.99%   |
| Toshiba America Info Systems     | 4         | 1.84%   |
| SanDisk                          | 4         | 1.84%   |
| KIOXIA                           | 4         | 1.84%   |
| SK hynix                         | 2         | 0.92%   |
| Kingston Technology Company      | 2         | 0.92%   |
| Silicon Integrated Systems [SiS] | 1         | 0.46%   |
| Phison Electronics               | 1         | 0.46%   |
| O2 Micro                         | 1         | 0.46%   |
| Nvidia                           | 1         | 0.46%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 22        | 9.44%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 19        | 8.15%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 15        | 6.44%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 14        | 6.01%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 13        | 5.58%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 12        | 5.15%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 10        | 4.29%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 10        | 4.29%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 9         | 3.86%   |
| Intel Volume Management Device NVMe RAID Controller                            | 8         | 3.43%   |
| Intel Tiger Lake-LP SATA Controller                                            | 8         | 3.43%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 8         | 3.43%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 7         | 3%      |
| Intel Comet Lake SATA AHCI Controller                                          | 6         | 2.58%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 6         | 2.58%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 2.15%   |
| Samsung NVMe SSD Controller 980                                                | 4         | 1.72%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 1.72%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 1.29%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 1.29%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 0.86%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 2         | 0.86%   |
| Intel SSD 660P Series                                                          | 2         | 0.86%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 2         | 0.86%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 2         | 0.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 0.86%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.43%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 1         | 0.43%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 1         | 0.43%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.43%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 1         | 0.43%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 1         | 0.43%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 0.43%   |
| SanDisk WD Black NVMe SSD                                                      | 1         | 0.43%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 1         | 0.43%   |
| SanDisk IX SN530 NVMe SSD (DRAM-less)                                          | 1         | 0.43%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 0.43%   |
| Phison E12 NVMe Controller                                                     | 1         | 0.43%   |
| O2 Micro FORESEE E2M2 NVMe SSD                                                 | 1         | 0.43%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 0.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 149       | 65.64%  |
| NVMe | 39        | 17.18%  |
| RAID | 31        | 13.66%  |
| IDE  | 8         | 3.52%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 185       | 91.58%  |
| AMD    | 17        | 8.42%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz           | 7         | 3.47%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 6         | 2.97%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 6         | 2.97%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 5         | 2.48%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 5         | 2.48%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 4         | 1.98%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 4         | 1.98%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 4         | 1.98%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 4         | 1.98%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 4         | 1.98%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 4         | 1.98%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 4         | 1.98%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 3         | 1.49%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 3         | 1.49%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 3         | 1.49%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 3         | 1.49%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 3         | 1.49%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 3         | 1.49%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 3         | 1.49%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 3         | 1.49%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 0.99%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 0.99%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 2         | 0.99%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 2         | 0.99%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 2         | 0.99%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 0.99%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 0.99%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 2         | 0.99%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 0.99%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 0.99%   |
| Intel Core i5 CPU M 460 @ 2.53GHz           | 2         | 0.99%   |
| Intel Core i5 CPU M 450 @ 2.40GHz           | 2         | 0.99%   |
| Intel Core i3-7100U CPU @ 2.40GHz           | 2         | 0.99%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 2         | 0.99%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 2         | 0.99%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 2         | 0.99%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 2         | 0.99%   |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz        | 2         | 0.99%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 2         | 0.99%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz           | 2         | 0.99%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 78        | 38.61%  |
| Intel Core i7           | 36        | 17.82%  |
| Intel Core i3           | 27        | 13.37%  |
| Other                   | 13        | 6.44%   |
| Intel Core 2 Duo        | 10        | 4.95%   |
| Intel Celeron           | 8         | 3.96%   |
| Intel Atom              | 5         | 2.48%   |
| AMD E1                  | 3         | 1.49%   |
| Intel Pentium Dual-Core | 2         | 0.99%   |
| AMD Ryzen 7             | 2         | 0.99%   |
| AMD Ryzen 5             | 2         | 0.99%   |
| AMD C-60                | 2         | 0.99%   |
| AMD A8                  | 2         | 0.99%   |
| AMD A6                  | 2         | 0.99%   |
| Intel Pentium Silver    | 1         | 0.5%    |
| Intel Pentium M         | 1         | 0.5%    |
| Intel Pentium Gold      | 1         | 0.5%    |
| Intel Pentium           | 1         | 0.5%    |
| Intel Genuine           | 1         | 0.5%    |
| Intel Core 2            | 1         | 0.5%    |
| Intel Celeron M         | 1         | 0.5%    |
| AMD Ryzen 9             | 1         | 0.5%    |
| AMD Ryzen 7 PRO         | 1         | 0.5%    |
| AMD A4                  | 1         | 0.5%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 131       | 64.85%  |
| 4      | 55        | 27.23%  |
| 8      | 5         | 2.48%   |
| 1      | 5         | 2.48%   |
| 6      | 4         | 1.98%   |
| 10     | 2         | 0.99%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 202       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 160       | 79.21%  |
| 1      | 42        | 20.79%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 197       | 97.52%  |
| 32-bit         | 3         | 1.49%   |
| Unknown        | 2         | 0.99%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 47        | 22.71%  |
| 0x206a7    | 17        | 8.21%   |
| 0x306d4    | 14        | 6.76%   |
| 0x40651    | 11        | 5.31%   |
| 0x806ea    | 10        | 4.83%   |
| 0x806ec    | 9         | 4.35%   |
| 0x306c3    | 9         | 4.35%   |
| 0x20655    | 9         | 4.35%   |
| 0x306a9    | 8         | 3.86%   |
| 0x806c1    | 7         | 3.38%   |
| 0x406e3    | 6         | 2.9%    |
| 0x1067a    | 6         | 2.9%    |
| 0x806e9    | 5         | 2.42%   |
| 0x20652    | 5         | 2.42%   |
| 0x6fd      | 4         | 1.93%   |
| 0x506e3    | 4         | 1.93%   |
| 0x30678    | 4         | 1.93%   |
| 0x0a50000c | 3         | 1.45%   |
| 0x906ea    | 2         | 0.97%   |
| 0x406c4    | 2         | 0.97%   |
| 0x406c3    | 2         | 0.97%   |
| 0x10676    | 2         | 0.97%   |
| 0x07030105 | 2         | 0.97%   |
| 0x0700010f | 2         | 0.97%   |
| 0xb06a3    | 1         | 0.48%   |
| 0x906e9    | 1         | 0.48%   |
| 0x806eb    | 1         | 0.48%   |
| 0x806d1    | 1         | 0.48%   |
| 0x706e5    | 1         | 0.48%   |
| 0x706a1    | 1         | 0.48%   |
| 0x6ec      | 1         | 0.48%   |
| 0x6e8      | 1         | 0.48%   |
| 0x6d8      | 1         | 0.48%   |
| 0x30673    | 1         | 0.48%   |
| 0x30661    | 1         | 0.48%   |
| 0x08108102 | 1         | 0.48%   |
| 0x06006705 | 1         | 0.48%   |
| 0x06001119 | 1         | 0.48%   |
| 0x05000119 | 1         | 0.48%   |
| 0x05000101 | 1         | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 35        | 17.33%  |
| Haswell          | 26        | 12.87%  |
| SandyBridge      | 19        | 9.41%   |
| Westmere         | 18        | 8.91%   |
| Broadwell        | 16        | 7.92%   |
| Skylake          | 15        | 7.43%   |
| IvyBridge        | 10        | 4.95%   |
| TigerLake        | 9         | 4.46%   |
| Silvermont       | 9         | 4.46%   |
| Penryn           | 9         | 4.46%   |
| Core             | 5         | 2.48%   |
| Zen 3            | 3         | 1.49%   |
| P6               | 3         | 1.49%   |
| IceLake          | 3         | 1.49%   |
| Bobcat           | 3         | 1.49%   |
| Unknown          | 3         | 1.49%   |
| Zen+             | 2         | 0.99%   |
| Puma             | 2         | 0.99%   |
| Jaguar           | 2         | 0.99%   |
| Goldmont plus    | 2         | 0.99%   |
| Bonnell          | 2         | 0.99%   |
| Alderlake Hybrid | 2         | 0.99%   |
| Piledriver       | 1         | 0.5%    |
| K10 Llano        | 1         | 0.5%    |
| Excavator        | 1         | 0.5%    |
| CometLake        | 1         | 0.5%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 171       | 68.13%  |
| Nvidia | 50        | 19.92%  |
| AMD    | 30        | 11.95%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 18        | 7.09%   |
| Intel HD Graphics 5500                                                                   | 16        | 6.3%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 16        | 6.3%    |
| Intel Core Processor Integrated Graphics Controller                                      | 15        | 5.91%   |
| Intel UHD Graphics 620                                                                   | 12        | 4.72%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 3.94%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 3.94%   |
| Intel HD Graphics 620                                                                    | 8         | 3.15%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 8         | 3.15%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 2.76%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 2.36%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 2.36%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 1.97%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 1.57%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.57%   |
| Intel HD Graphics 530                                                                    | 4         | 1.57%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 1.57%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.57%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 1.18%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 1.18%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 3         | 1.18%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 1.18%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 1.18%   |
| Nvidia TU117M [GeForce MX450]                                                            | 2         | 0.79%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.79%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.79%   |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 0.79%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 2         | 0.79%   |
| Nvidia GF119M [NVS 4200M]                                                                | 2         | 0.79%   |
| Nvidia GF119M [GeForce GT 520M]                                                          | 2         | 0.79%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 0.79%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.79%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 2         | 0.79%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.79%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.79%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.79%   |
| AMD Wrestler [Radeon HD 6290]                                                            | 2         | 0.79%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/5145/530v/540v/545v]                         | 2         | 0.79%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 0.79%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                                       | 1         | 0.39%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 123       | 60.59%  |
| Intel + Nvidia | 41        | 20.2%   |
| 1 x AMD        | 22        | 10.84%  |
| 1 x Nvidia     | 9         | 4.43%   |
| Intel + AMD    | 7         | 3.45%   |
| AMD + Nvidia   | 1         | 0.49%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 174       | 84.06%  |
| Proprietary | 24        | 11.59%  |
| Unknown     | 9         | 4.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 148       | 71.84%  |
| 1.01-2.0   | 25        | 12.14%  |
| 0.01-0.5   | 20        | 9.71%   |
| 3.01-4.0   | 7         | 3.4%    |
| 0.51-1.0   | 5         | 2.43%   |
| 2.01-3.0   | 1         | 0.49%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 40        | 19.7%   |
| AU Optronics            | 36        | 17.73%  |
| Chimei Innolux          | 34        | 16.75%  |
| Samsung Electronics     | 29        | 14.29%  |
| BOE                     | 27        | 13.3%   |
| InfoVision              | 6         | 2.96%   |
| Lenovo                  | 4         | 1.97%   |
| Hewlett-Packard         | 4         | 1.97%   |
| Dell                    | 4         | 1.97%   |
| Chi Mei Optoelectronics | 4         | 1.97%   |
| LG Philips              | 3         | 1.48%   |
| Apple                   | 3         | 1.48%   |
| Sharp                   | 2         | 0.99%   |
| Valve                   | 1         | 0.49%   |
| TMX                     | 1         | 0.49%   |
| PANDA                   | 1         | 0.49%   |
| MSI                     | 1         | 0.49%   |
| LGD                     | 1         | 0.49%   |
| IBM                     | 1         | 0.49%   |
| CNC                     | 1         | 0.49%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 4         | 1.96%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 309x174mm 14.0-inch     | 3         | 1.47%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 3         | 1.47%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 3         | 1.47%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 1.47%   |
| Samsung Electronics LCD Monitor SDC4D42 1366x768 309x174mm 14.0-inch     | 2         | 0.98%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 2         | 0.98%   |
| LG Display LCD Monitor LGD0504 1366x768 344x194mm 15.5-inch              | 2         | 0.98%   |
| LG Display LCD Monitor LGD03D9 1366x768 345x194mm 15.6-inch              | 2         | 0.98%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1080 518x324mm 24.1-inch               | 2         | 0.98%   |
| Dell 2208WFP DEL403B 1680x1050 473x296mm 22.0-inch                       | 2         | 0.98%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 2         | 0.98%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.98%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch          | 2         | 0.98%   |
| Chimei Innolux LCD Monitor CMN1343 1920x1080 282x165mm 12.9-inch         | 2         | 0.98%   |
| Chi Mei Optoelectronics LCD Monitor CMO1599 1366x768 344x193mm 15.5-inch | 2         | 0.98%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 2         | 0.98%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 0.98%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch           | 2         | 0.98%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch            | 2         | 0.98%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 2         | 0.98%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 1         | 0.49%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch                  | 1         | 0.49%   |
| Sharp LCD Monitor SHP1516 3840x2400 336x210mm 15.6-inch                  | 1         | 0.49%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 1         | 0.49%   |
| Samsung Electronics SyncMaster SAM0472 1440x900 367x229mm 17.0-inch      | 1         | 0.49%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch        | 1         | 0.49%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC434E 1600x900 310x174mm 14.0-inch     | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC4143 1400x1050 286x214mm 14.1-inch    | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC3959 1366x768 344x194mm 15.5-inch     | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC3846 1680x1050 331x207mm 15.4-inch    | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 309x174mm 14.0-inch     | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 303x190mm 14.1-inch     | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC3051 1366x768 344x194mm 15.5-inch     | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC304F 1680x945 409x230mm 18.5-inch     | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x193mm 15.5-inch     | 1         | 0.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 97        | 49.24%  |
| 1920x1080 (FHD)    | 57        | 28.93%  |
| 1600x900 (HD+)     | 14        | 7.11%   |
| 1280x800 (WXGA)    | 7         | 3.55%   |
| 1680x1050 (WSXGA+) | 3         | 1.52%   |
| 1024x600           | 3         | 1.52%   |
| 3840x2160 (4K)     | 2         | 1.02%   |
| 1440x900 (WXGA+)   | 2         | 1.02%   |
| 800x1280           | 1         | 0.51%   |
| 3840x2400          | 1         | 0.51%   |
| 2880x1800          | 1         | 0.51%   |
| 2560x1600          | 1         | 0.51%   |
| 2560x1440 (QHD)    | 1         | 0.51%   |
| 2520x1680          | 1         | 0.51%   |
| 1920x1200 (WUXGA)  | 1         | 0.51%   |
| 1680x945           | 1         | 0.51%   |
| 1400x1050          | 1         | 0.51%   |
| 1360x768           | 1         | 0.51%   |
| 1280x1024 (SXGA)   | 1         | 0.51%   |
| 1024x768 (XGA)     | 1         | 0.51%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 111       | 54.41%  |
| 14      | 27        | 13.24%  |
| 13      | 21        | 10.29%  |
| 12      | 12        | 5.88%   |
| 17      | 7         | 3.43%   |
| 23      | 4         | 1.96%   |
| 18      | 4         | 1.96%   |
| 24      | 3         | 1.47%   |
| 11      | 3         | 1.47%   |
| 22      | 2         | 0.98%   |
| 10      | 2         | 0.98%   |
| 84      | 1         | 0.49%   |
| 32      | 1         | 0.49%   |
| 31      | 1         | 0.49%   |
| 27      | 1         | 0.49%   |
| 19      | 1         | 0.49%   |
| 16      | 1         | 0.49%   |
| 7       | 1         | 0.49%   |
| Unknown | 1         | 0.49%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 147       | 72.06%  |
| 201-300     | 26        | 12.75%  |
| 351-400     | 13        | 6.37%   |
| 501-600     | 8         | 3.92%   |
| 401-500     | 5         | 2.45%   |
| 701-800     | 1         | 0.49%   |
| 601-700     | 1         | 0.49%   |
| 1501-2000   | 1         | 0.49%   |
| 1-100       | 1         | 0.49%   |
| Unknown     | 1         | 0.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 172       | 88.21%  |
| 16/10   | 16        | 8.21%   |
| 4/3     | 2         | 1.03%   |
| 3/2     | 2         | 1.03%   |
| 5/4     | 1         | 0.51%   |
| 0.67    | 1         | 0.51%   |
| Unknown | 1         | 0.51%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 110       | 53.92%  |
| 81-90          | 40        | 19.61%  |
| 61-70          | 12        | 5.88%   |
| 71-80          | 7         | 3.43%   |
| 201-250        | 7         | 3.43%   |
| 121-130        | 5         | 2.45%   |
| 141-150        | 4         | 1.96%   |
| 51-60          | 3         | 1.47%   |
| 351-500        | 2         | 0.98%   |
| 41-50          | 2         | 0.98%   |
| 251-300        | 2         | 0.98%   |
| 131-140        | 2         | 0.98%   |
| 111-120        | 2         | 0.98%   |
| More than 1000 | 1         | 0.49%   |
| 1-40           | 1         | 0.49%   |
| 301-350        | 1         | 0.49%   |
| 151-200        | 1         | 0.49%   |
| 91-100         | 1         | 0.49%   |
| Unknown        | 1         | 0.49%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 91        | 44.83%  |
| 121-160       | 66        | 32.51%  |
| 51-100        | 28        | 13.79%  |
| 161-240       | 14        | 6.9%    |
| More than 240 | 2         | 0.99%   |
| 1-50          | 1         | 0.49%   |
| Unknown       | 1         | 0.49%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 185       | 90.24%  |
| 2     | 15        | 7.32%   |
| 0     | 5         | 2.44%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 106       | 33.97%  |
| Realtek Semiconductor    | 94        | 30.13%  |
| Qualcomm Atheros         | 47        | 15.06%  |
| Broadcom                 | 32        | 10.26%  |
| Ralink Technology        | 7         | 2.24%   |
| Ralink                   | 5         | 1.6%    |
| Xiaomi                   | 3         | 0.96%   |
| Dell                     | 3         | 0.96%   |
| Broadcom Limited         | 3         | 0.96%   |
| Sierra Wireless          | 2         | 0.64%   |
| Lenovo                   | 2         | 0.64%   |
| TP-Link                  | 1         | 0.32%   |
| Samsung Electronics      | 1         | 0.32%   |
| Qualcomm                 | 1         | 0.32%   |
| Nvidia                   | 1         | 0.32%   |
| MediaTek                 | 1         | 0.32%   |
| Marvell Technology Group | 1         | 0.32%   |
| JMicron Technology       | 1         | 0.32%   |
| Arduino SA               | 1         | 0.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 58        | 14.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 20        | 5%      |
| Intel Wireless 7265                                               | 12        | 3%      |
| Intel Wireless 8265 / 8275                                        | 11        | 2.75%   |
| Intel 82577LM Gigabit Network Connection                          | 11        | 2.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 10        | 2.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 2.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 2.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 9         | 2.25%   |
| Intel Wireless 8260                                               | 9         | 2.25%   |
| Intel Ethernet Connection (3) I218-LM                             | 9         | 2.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 2.25%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 1.75%   |
| Intel Centrino Advanced-N 6200                                    | 7         | 1.75%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 6         | 1.5%    |
| Intel Ethernet Connection I217-LM                                 | 6         | 1.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 1.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 1.25%   |
| Ralink MT7601U Wireless Adapter                                   | 5         | 1.25%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 5         | 1.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 1.25%   |
| Intel Wireless 7260                                               | 5         | 1.25%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 1.25%   |
| Intel Centrino Advanced-N 6235                                    | 5         | 1.25%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 1.25%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 1.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1%      |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 1%      |
| Intel Wi-Fi 6 AX201                                               | 4         | 1%      |
| Intel Ethernet Connection I219-LM                                 | 4         | 1%      |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1%      |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 1%      |
| Broadcom BCM43228 802.11a/b/g/n                                   | 4         | 1%      |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.75%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.75%   |
| Intel WiFi Link 5100                                              | 3         | 0.75%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.75%   |
| Intel Centrino Ultimate-N 6300                                    | 3         | 0.75%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 98        | 46.67%  |
| Qualcomm Atheros      | 42        | 20%     |
| Realtek Semiconductor | 27        | 12.86%  |
| Broadcom              | 22        | 10.48%  |
| Ralink Technology     | 7         | 3.33%   |
| Ralink                | 5         | 2.38%   |
| Broadcom Limited      | 3         | 1.43%   |
| Sierra Wireless       | 2         | 0.95%   |
| Dell                  | 2         | 0.95%   |
| TP-Link               | 1         | 0.48%   |
| MediaTek              | 1         | 0.48%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                            | 12        | 5.71%   |
| Intel Wireless 8265 / 8275                                     | 11        | 5.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 10        | 4.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9         | 4.29%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 9         | 4.29%   |
| Intel Wireless 8260                                            | 9         | 4.29%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 9         | 4.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 7         | 3.33%   |
| Intel Centrino Advanced-N 6200                                 | 7         | 3.33%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 6         | 2.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 6         | 2.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 5         | 2.38%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 2.38%   |
| Ralink MT7601U Wireless Adapter                                | 5         | 2.38%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 5         | 2.38%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 5         | 2.38%   |
| Intel Wireless 7260                                            | 5         | 2.38%   |
| Intel Centrino Advanced-N 6235                                 | 5         | 2.38%   |
| Broadcom BCM43142 802.11b/g/n                                  | 5         | 2.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 2.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 1.9%    |
| Intel Wi-Fi 6 AX201                                            | 4         | 1.9%    |
| Broadcom BCM43228 802.11a/b/g/n                                | 4         | 1.9%    |
| Intel WiFi Link 5100                                           | 3         | 1.43%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 1.43%   |
| Intel Centrino Ultimate-N 6300                                 | 3         | 1.43%   |
| Sierra Wireless EM7455                                         | 2         | 0.95%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 0.95%   |
| Intel Wireless 3165                                            | 2         | 0.95%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 0.95%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 0.95%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 0.95%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 2         | 0.95%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 0.95%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 2         | 0.95%   |
| Broadcom BCM43225 802.11b/g/n                                  | 2         | 0.95%   |
| Broadcom BCM4311 802.11b/g WLAN                                | 2         | 0.95%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 0.48%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.48%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 0.48%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 84        | 45.16%  |
| Intel                    | 68        | 36.56%  |
| Broadcom                 | 13        | 6.99%   |
| Qualcomm Atheros         | 11        | 5.91%   |
| Xiaomi                   | 3         | 1.61%   |
| Lenovo                   | 2         | 1.08%   |
| Samsung Electronics      | 1         | 0.54%   |
| Qualcomm                 | 1         | 0.54%   |
| Nvidia                   | 1         | 0.54%   |
| Marvell Technology Group | 1         | 0.54%   |
| JMicron Technology       | 1         | 0.54%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 58        | 31.02%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 20        | 10.7%   |
| Intel 82577LM Gigabit Network Connection                          | 11        | 5.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 5.35%   |
| Intel Ethernet Connection (3) I218-LM                             | 9         | 4.81%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 3.21%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 2.67%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 2.14%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 2.14%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 2.14%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 2.14%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 1.6%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 1.6%    |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1.6%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 1.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.07%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.07%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.07%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.07%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 2         | 1.07%   |
| Intel Ethernet Connection I217-V                                  | 2         | 1.07%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 2         | 1.07%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.07%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.53%   |
| Qualcomm Redmi Note 8                                             | 1         | 0.53%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.53%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.53%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.53%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.53%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 0.53%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.53%   |
| Intel Ethernet Controller I219-LM                                 | 1         | 0.53%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.53%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.53%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.53%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 0.53%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.53%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 0.53%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.53%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.53%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 200       | 52.49%  |
| Ethernet | 178       | 46.72%  |
| Modem    | 3         | 0.79%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 170       | 83.33%  |
| Ethernet | 34        | 16.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 173       | 85.22%  |
| 1     | 25        | 12.32%  |
| 0     | 3         | 1.48%   |
| 7     | 1         | 0.49%   |
| 3     | 1         | 0.49%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 202       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 64        | 43.54%  |
| Realtek Semiconductor           | 19        | 12.93%  |
| Qualcomm Atheros Communications | 18        | 12.24%  |
| IMC Networks                    | 8         | 5.44%   |
| Broadcom                        | 8         | 5.44%   |
| Dell                            | 7         | 4.76%   |
| Ralink                          | 5         | 3.4%    |
| Lite-On Technology              | 5         | 3.4%    |
| Hewlett-Packard                 | 5         | 3.4%    |
| Apple                           | 2         | 1.36%   |
| Toshiba                         | 1         | 0.68%   |
| Foxconn International           | 1         | 0.68%   |
| Foxconn / Hon Hai               | 1         | 0.68%   |
| Cambridge Silicon Radio         | 1         | 0.68%   |
| ASUSTek Computer                | 1         | 0.68%   |
| Alps Electric                   | 1         | 0.68%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 36        | 24.49%  |
| Realtek Bluetooth Radio                             | 14        | 9.52%   |
| Intel AX201 Bluetooth                               | 10        | 6.8%    |
| Qualcomm Atheros  Bluetooth Device                  | 8         | 5.44%   |
| IMC Networks Bluetooth Device                       | 6         | 4.08%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 3.4%    |
| Ralink RT3290 Bluetooth                             | 5         | 3.4%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 3.4%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 3.4%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 2.72%   |
| Intel Bluetooth Device                              | 4         | 2.72%   |
| HP Broadcom 2070 Bluetooth Combo                    | 4         | 2.72%   |
| Dell DW375 Bluetooth Module                         | 4         | 2.72%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 2.04%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 2.04%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 1.36%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 1.36%   |
| Intel AX200 Bluetooth                               | 2         | 1.36%   |
| Dell Wireless 360 Bluetooth                         | 2         | 1.36%   |
| Broadcom HP Portable Bumble Bee                     | 2         | 1.36%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 1.36%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.36%   |
| Toshiba Bluetooth Device                            | 1         | 0.68%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.68%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.68%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.68%   |
| IMC Networks Wireless_Device                        | 1         | 0.68%   |
| IMC Networks Bluetooth Radio                        | 1         | 0.68%   |
| HP Bluetooth 1.2 Interface [Broadcom BCM2035]       | 1         | 0.68%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.68%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.68%   |
| Dell Wireless 350 Bluetooth                         | 1         | 0.68%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 0.68%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.68%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.68%   |
| ASUS BT-270 Bluetooth Adapter                       | 1         | 0.68%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 0.68%   |
| Apple Bluetooth Host Controller                     | 1         | 0.68%   |
| Alps Electric BCM2046 Bluetooth Device              | 1         | 0.68%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 181       | 76.69%  |
| Nvidia                           | 24        | 10.17%  |
| AMD                              | 22        | 9.32%   |
| Lenovo                           | 2         | 0.85%   |
| Silicon Integrated Systems [SiS] | 1         | 0.42%   |
| Nordic Semiconductor ASA         | 1         | 0.42%   |
| Logitech                         | 1         | 0.42%   |
| GN Netcom                        | 1         | 0.42%   |
| Generalplus Technology           | 1         | 0.42%   |
| Focusrite-Novation               | 1         | 0.42%   |
| ASUSTek Computer                 | 1         | 0.42%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 30        | 10.31%  |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 18        | 6.19%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 16        | 5.5%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 16        | 5.5%    |
| Intel Broadwell-U Audio Controller                                                                | 16        | 5.5%    |
| Intel 8 Series HD Audio Controller                                                                | 16        | 5.5%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 15        | 5.15%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 4.81%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 10        | 3.44%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 10        | 3.44%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 9         | 3.09%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 2.41%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 2.06%   |
| AMD FCH Azalia Controller                                                                         | 6         | 2.06%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 2.06%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.72%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 1.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.72%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 4         | 1.37%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 1.37%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 1.37%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.37%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.37%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 1.37%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 1.03%   |
| Nvidia Audio device                                                                               | 3         | 1.03%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.03%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.69%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.69%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 2         | 0.69%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.69%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.69%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.69%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.69%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.69%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 0.69%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.34%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.34%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.34%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 39        | 29.77%  |
| SK hynix            | 31        | 23.66%  |
| Micron Technology   | 19        | 14.5%   |
| Kingston            | 17        | 12.98%  |
| Unknown             | 5         | 3.82%   |
| Ramaxel Technology  | 4         | 3.05%   |
| A-DATA Technology   | 4         | 3.05%   |
| Elpida              | 3         | 2.29%   |
| Crucial             | 3         | 2.29%   |
| Nanya Technology    | 2         | 1.53%   |
| Transcend           | 1         | 0.76%   |
| Toshiba             | 1         | 0.76%   |
| Sesame              | 1         | 0.76%   |
| ASint Technology    | 1         | 0.76%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 4         | 2.82%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 4         | 2.82%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 3         | 2.11%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s       | 3         | 2.11%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 2         | 1.41%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s      | 2         | 1.41%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 2         | 1.41%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                 | 2         | 1.41%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s       | 2         | 1.41%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 2         | 1.41%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s       | 2         | 1.41%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 2         | 1.41%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 2         | 1.41%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s       | 2         | 1.41%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s        | 2         | 1.41%   |
| Kingston RAM HP687515-H66-MCN 4GB SODIMM DDR3 1600MT/s      | 2         | 1.41%   |
| Kingston RAM HP16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s       | 2         | 1.41%   |
| Unknown RAM Module 4GB SODIMM DDR3                          | 1         | 0.7%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1066MT/s              | 1         | 0.7%    |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                   | 1         | 0.7%    |
| Unknown RAM Module 2048MB SODIMM DDR2                       | 1         | 0.7%    |
| Unknown RAM Module 2048MB SODIMM 800MT/s                    | 1         | 0.7%    |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                | 1         | 0.7%    |
| Transcend RAM JM1333KSN-4G 4GB SODIMM DDR3 1334MT/s         | 1         | 0.7%    |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 1066MT/s        | 1         | 0.7%    |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s             | 1         | 0.7%    |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s             | 1         | 0.7%    |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s        | 1         | 0.7%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.7%    |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s      | 1         | 0.7%    |
| SK hynix RAM HMT41GS6DFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 1         | 0.7%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s   | 1         | 0.7%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 1         | 0.7%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.7%    |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1600MT/s      | 1         | 0.7%    |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s      | 1         | 0.7%    |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s   | 1         | 0.7%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s      | 1         | 0.7%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s      | 1         | 0.7%    |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s      | 1         | 0.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 53        | 51.46%  |
| DDR4    | 35        | 33.98%  |
| LPDDR4  | 4         | 3.88%   |
| DDR2    | 4         | 3.88%   |
| LPDDR3  | 3         | 2.91%   |
| Unknown | 2         | 1.94%   |
| SDRAM   | 1         | 0.97%   |
| DDR5    | 1         | 0.97%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 94        | 93.07%  |
| Row Of Chips | 4         | 3.96%   |
| Unknown      | 2         | 1.98%   |
| DIMM         | 1         | 0.99%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 46        | 39.66%  |
| 8192  | 44        | 37.93%  |
| 2048  | 15        | 12.93%  |
| 16384 | 8         | 6.9%    |
| 1024  | 3         | 2.59%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 37        | 32.74%  |
| 2667    | 18        | 15.93%  |
| 3200    | 14        | 12.39%  |
| 1334    | 13        | 11.5%   |
| 2400    | 6         | 5.31%   |
| 2133    | 5         | 4.42%   |
| 1333    | 4         | 3.54%   |
| 1066    | 3         | 2.65%   |
| 975     | 2         | 1.77%   |
| 800     | 2         | 1.77%   |
| Unknown | 2         | 1.77%   |
| 4800    | 1         | 0.88%   |
| 4267    | 1         | 0.88%   |
| 4199    | 1         | 0.88%   |
| 3266    | 1         | 0.88%   |
| 1867    | 1         | 0.88%   |
| 1067    | 1         | 0.88%   |
| 667     | 1         | 0.88%   |

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
| Chicony Electronics                    | 47        | 27.49%  |
| IMC Networks                           | 18        | 10.53%  |
| Realtek Semiconductor                  | 17        | 9.94%   |
| Cheng Uei Precision Industry (Foxlink) | 16        | 9.36%   |
| Sunplus Innovation Technology          | 11        | 6.43%   |
| Suyin                                  | 10        | 5.85%   |
| Microdia                               | 8         | 4.68%   |
| Lite-On Technology                     | 8         | 4.68%   |
| Quanta                                 | 7         | 4.09%   |
| Bison Electronics                      | 5         | 2.92%   |
| Ricoh                                  | 4         | 2.34%   |
| Syntek                                 | 3         | 1.75%   |
| Apple                                  | 3         | 1.75%   |
| Luxvisions Innotech Limited            | 2         | 1.17%   |
| ALi                                    | 2         | 1.17%   |
| Z-Star Microelectronics                | 1         | 0.58%   |
| Sunplus Technology                     | 1         | 0.58%   |
| Sonix Technology                       | 1         | 0.58%   |
| Silicon Motion                         | 1         | 0.58%   |
| ShineTech                              | 1         | 0.58%   |
| OPPO Electronics                       | 1         | 0.58%   |
| Logitech                               | 1         | 0.58%   |
| icSpring                               | 1         | 0.58%   |
| Alcor Micro                            | 1         | 0.58%   |
| Acer                                   | 1         | 0.58%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 7         | 4.09%   |
| Chicony HP Webcam [2 MP Macro]                              | 6         | 3.51%   |
| IMC Networks Integrated Camera                              | 5         | 2.92%   |
| Realtek Integrated_Webcam_HD                                | 4         | 2.34%   |
| Chicony HP Webcam                                           | 4         | 2.34%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 4         | 2.34%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 4         | 2.34%   |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 3         | 1.75%   |
| Sunplus Integrated_Webcam_HD                                | 3         | 1.75%   |
| Realtek USB Camera                                          | 3         | 1.75%   |
| Microdia Integrated Webcam                                  | 3         | 1.75%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 3         | 1.75%   |
| IMC Networks Lenovo EasyCamera                              | 3         | 1.75%   |
| Chicony HP HD Webcam                                        | 3         | 1.75%   |
| Syntek Lenovo EasyCamera                                    | 2         | 1.17%   |
| Suyin HP TrueVision HD Integrated Webcam                    | 2         | 1.17%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 2         | 1.17%   |
| Sunplus HP Universal Camera                                 | 2         | 1.17%   |
| Ricoh Laptop_Integrated_Webcam_FHD                          | 2         | 1.17%   |
| Quanta HP Wide Vision HD Camera                             | 2         | 1.17%   |
| Quanta HD Webcam                                            | 2         | 1.17%   |
| Lite-On TOSHIBA Web Camera - HD                             | 2         | 1.17%   |
| Lite-On HP HD Webcam                                        | 2         | 1.17%   |
| Lite-On HP HD Camera                                        | 2         | 1.17%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 2         | 1.17%   |
| IMC Networks Integrated Webcam                              | 2         | 1.17%   |
| IMC Networks HP TrueVision HD Camera                        | 2         | 1.17%   |
| Chicony USB2.0 HD UVC WebCam                                | 2         | 1.17%   |
| Chicony TOSHIBA Web Camera - HD                             | 2         | 1.17%   |
| Chicony Lenovo Integrated Camera (0.3MP)                    | 2         | 1.17%   |
| Chicony Integrated Camera (1280x720@30)                     | 2         | 1.17%   |
| Chicony HP Wide Vision HD Camera                            | 2         | 1.17%   |
| Chicony HP Truevision HD                                    | 2         | 1.17%   |
| Chicony HP HD Webcam [Fixed]                                | 2         | 1.17%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD     | 2         | 1.17%   |
| Bison Integrated Camera                                     | 2         | 1.17%   |
| Z-Star Vimicro USB2.0 Camera                                | 1         | 0.58%   |
| Syntek EasyCamera                                           | 1         | 0.58%   |
| Suyin WebCam                                                | 1         | 0.58%   |
| Suyin Sony Visual Communication Camera                      | 1         | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 27        | 65.85%  |
| Synaptics                  | 6         | 14.63%  |
| Elan Microelectronics      | 4         | 9.76%   |
| Shenzhen Goodix Technology | 2         | 4.88%   |
| Upek                       | 1         | 2.44%   |
| Focal-systems.Corp         | 1         | 2.44%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 10        | 24.39%  |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 12.2%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 9.76%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 7.32%   |
| Validity Sensors VFS491                                                    | 2         | 4.88%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 4.88%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 4.88%   |
| Elan ELAN:Fingerprint                                                      | 2         | 4.88%   |
| Elan ELAN:ARM-M4                                                           | 2         | 4.88%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2.44%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.44%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 2.44%   |
| Synaptics UWP WBDI Device                                                  | 1         | 2.44%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 2.44%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 2.44%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 2.44%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 2.44%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 2.44%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 20        | 66.67%  |
| Alcor Micro | 6         | 20%     |
| O2 Micro    | 4         | 13.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 6         | 20%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 13.33%  |
| Broadcom 5880                                                                | 4         | 13.33%  |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 6.67%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 6.67%   |
| Broadcom 58200                                                               | 2         | 6.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 115       | 55.29%  |
| 1     | 73        | 35.1%   |
| 2     | 16        | 7.69%   |
| 3     | 3         | 1.44%   |
| 5     | 1         | 0.48%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 41        | 34.75%  |
| Chipcard                 | 26        | 22.03%  |
| Graphics card            | 21        | 17.8%   |
| Net/wireless             | 7         | 5.93%   |
| Bluetooth                | 6         | 5.08%   |
| Storage                  | 5         | 4.24%   |
| Camera                   | 4         | 3.39%   |
| Sound                    | 2         | 1.69%   |
| Net/ethernet             | 2         | 1.69%   |
| Communication controller | 2         | 1.69%   |
| Unassigned class         | 1         | 0.85%   |
| Modem                    | 1         | 0.85%   |

