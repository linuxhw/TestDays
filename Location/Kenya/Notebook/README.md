Linux in Kenya - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Kenya.

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

Total: 202

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | ProBook 440 G6              | [94684071ed](https://linux-hardware.org/?probe=94684071ed) | May 05, 2022 |
| Dell          | Latitude 3340               | [b724073bff](https://linux-hardware.org/?probe=b724073bff) | May 05, 2022 |
| HP            | EliteBook 840 G1            | [53bceed0aa](https://linux-hardware.org/?probe=53bceed0aa) | Apr 29, 2022 |
| Dell          | Latitude 3340               | [e6aa31da26](https://linux-hardware.org/?probe=e6aa31da26) | Apr 23, 2022 |
| Lenovo        | ThinkPad X131e 33672T5      | [64e00f7a40](https://linux-hardware.org/?probe=64e00f7a40) | Apr 12, 2022 |
| HP            | EliteBook Folio 9480m       | [a83be65e4f](https://linux-hardware.org/?probe=a83be65e4f) | Apr 02, 2022 |
| HP            | EliteBook Folio 9480m       | [5bb1b6ca04](https://linux-hardware.org/?probe=5bb1b6ca04) | Apr 02, 2022 |
| Lenovo        | ThinkPad X131e 33672T5      | [277143e66b](https://linux-hardware.org/?probe=277143e66b) | Mar 26, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | [a2e640db60](https://linux-hardware.org/?probe=a2e640db60) | Feb 08, 2022 |
| Lenovo        | ThinkPad T490s 20NYS8J90... | [c1aee9b559](https://linux-hardware.org/?probe=c1aee9b559) | Feb 03, 2022 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [71b93f7b57](https://linux-hardware.org/?probe=71b93f7b57) | Feb 03, 2022 |
| HP            | ProBook 4540s               | [16794fee23](https://linux-hardware.org/?probe=16794fee23) | Jan 20, 2022 |
| Lenovo        | V14-IGL 82C2                | [c90b300aea](https://linux-hardware.org/?probe=c90b300aea) | Jan 16, 2022 |
| HP            | Presario CQ56               | [8d03d80424](https://linux-hardware.org/?probe=8d03d80424) | Jan 14, 2022 |
| HP            | EliteBook 840 G2            | [fac2fc3940](https://linux-hardware.org/?probe=fac2fc3940) | Jan 13, 2022 |
| Lenovo        | ThinkPad X240 20AL00CQAU    | [9f36bf55ba](https://linux-hardware.org/?probe=9f36bf55ba) | Jan 11, 2022 |
| HP            | Presario CQ56               | [a0bc0364a8](https://linux-hardware.org/?probe=a0bc0364a8) | Jan 08, 2022 |
| Lenovo        | ThinkPad X250 20CLA21MJP    | [850c0ae1da](https://linux-hardware.org/?probe=850c0ae1da) | Jan 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | [c08374a615](https://linux-hardware.org/?probe=c08374a615) | Dec 30, 2021 |
| Dell          | Inspiron 3543               | [30756486fd](https://linux-hardware.org/?probe=30756486fd) | Dec 26, 2021 |
| Dell          | XPS 13 9310                 | [01b4efe7c0](https://linux-hardware.org/?probe=01b4efe7c0) | Dec 17, 2021 |
| HP            | ENVY Pro 4-b000 Ultraboo... | [1bac69aa61](https://linux-hardware.org/?probe=1bac69aa61) | Dec 17, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [dff30c5ec8](https://linux-hardware.org/?probe=dff30c5ec8) | Dec 15, 2021 |
| HP            | ENVY Pro 4-b000 Ultraboo... | [20259384ac](https://linux-hardware.org/?probe=20259384ac) | Dec 14, 2021 |
| Toshiba       | Satellite C660              | [b159811d48](https://linux-hardware.org/?probe=b159811d48) | Dec 12, 2021 |
| Toshiba       | Satellite C660              | [2197770fd0](https://linux-hardware.org/?probe=2197770fd0) | Dec 12, 2021 |
| Chuwi         | HeroBook Air                | [dd5567d4dc](https://linux-hardware.org/?probe=dd5567d4dc) | Dec 08, 2021 |
| Toshiba       | Satellite C660              | [64521297e2](https://linux-hardware.org/?probe=64521297e2) | Dec 07, 2021 |
| Toshiba       | Satellite C660              | [b6a5bb8982](https://linux-hardware.org/?probe=b6a5bb8982) | Dec 06, 2021 |
| Dell          | XPS 13 9310                 | [2b0946038d](https://linux-hardware.org/?probe=2b0946038d) | Nov 18, 2021 |
| Dell          | XPS 13 9310                 | [e1597401db](https://linux-hardware.org/?probe=e1597401db) | Nov 16, 2021 |
| SLIMBOOK      | PROX14-AMD                  | [820951b4af](https://linux-hardware.org/?probe=820951b4af) | Nov 16, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [022146ab90](https://linux-hardware.org/?probe=022146ab90) | Nov 14, 2021 |
| HP            | EliteBook 2560p             | [e3997c3bcb](https://linux-hardware.org/?probe=e3997c3bcb) | Nov 12, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [516eabe645](https://linux-hardware.org/?probe=516eabe645) | Nov 02, 2021 |
| Chuwi         | GemiBook                    | [f40d5fd5a7](https://linux-hardware.org/?probe=f40d5fd5a7) | Oct 27, 2021 |
| HP            | ProBook 640 G1              | [170dd8b241](https://linux-hardware.org/?probe=170dd8b241) | Oct 22, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [044c6efa0d](https://linux-hardware.org/?probe=044c6efa0d) | Oct 08, 2021 |
| HP            | Laptop 15-ra0xx             | [5e542184d8](https://linux-hardware.org/?probe=5e542184d8) | Oct 02, 2021 |
| HP            | EliteBook 820 G1            | [5a23abfa74](https://linux-hardware.org/?probe=5a23abfa74) | Sep 29, 2021 |
| HP            | EliteBook 820 G1            | [0646fc1739](https://linux-hardware.org/?probe=0646fc1739) | Sep 27, 2021 |
| Acer          | Aspire V3-572P              | [3eecfd13ad](https://linux-hardware.org/?probe=3eecfd13ad) | Sep 25, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [2e1581c3b3](https://linux-hardware.org/?probe=2e1581c3b3) | Sep 24, 2021 |
| Apple         | MacBookPro16,1              | [ab55e1ade6](https://linux-hardware.org/?probe=ab55e1ade6) | Sep 22, 2021 |
| Acer          | Aspire 5749Z                | [40bf0d5bb0](https://linux-hardware.org/?probe=40bf0d5bb0) | Sep 17, 2021 |
| Eluktronic... | MAG-15u                     | [f931222022](https://linux-hardware.org/?probe=f931222022) | Sep 13, 2021 |
| Insyde        | i101c                       | [de0a5f2925](https://linux-hardware.org/?probe=de0a5f2925) | Aug 31, 2021 |
| HP            | Pavilion Power Laptop 15... | [e8370d3b93](https://linux-hardware.org/?probe=e8370d3b93) | Aug 30, 2021 |
| HP            | Pavilion Power Laptop 15... | [a663972867](https://linux-hardware.org/?probe=a663972867) | Aug 26, 2021 |
| HP            | Pavilion Power Laptop 15... | [d29deaa58e](https://linux-hardware.org/?probe=d29deaa58e) | Aug 26, 2021 |
| Toshiba       | Satellite C660              | [27b0daea73](https://linux-hardware.org/?probe=27b0daea73) | Aug 25, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | [e5f9d8b06f](https://linux-hardware.org/?probe=e5f9d8b06f) | Aug 20, 2021 |
| HP            | EliteBook Folio 9480m       | [b89fc8114f](https://linux-hardware.org/?probe=b89fc8114f) | Aug 09, 2021 |
| Lenovo        | ThinkPad T460s 20FAS3QC0... | [c642d92231](https://linux-hardware.org/?probe=c642d92231) | Jul 31, 2021 |
| Lenovo        | ThinkPad T460s 20FAS3QC0... | [c374609a3e](https://linux-hardware.org/?probe=c374609a3e) | Jul 29, 2021 |
| Lenovo        | ThinkPad T460s 20FAS3QC0... | [c9de881b72](https://linux-hardware.org/?probe=c9de881b72) | Jul 25, 2021 |
| Lenovo        | ThinkPad T460s 20FAS3QC0... | [10e46eeaf3](https://linux-hardware.org/?probe=10e46eeaf3) | Jul 25, 2021 |
| HP            | EliteBook 840 G3            | [88afb2e5a1](https://linux-hardware.org/?probe=88afb2e5a1) | Jul 23, 2021 |
| Toshiba       | Satellite C660              | [d80d4d487b](https://linux-hardware.org/?probe=d80d4d487b) | Jul 22, 2021 |
| HP            | ProBook 640 G1              | [b3a36bf681](https://linux-hardware.org/?probe=b3a36bf681) | Jul 21, 2021 |
| HP            | Pavilion Notebook           | [0f54d945d0](https://linux-hardware.org/?probe=0f54d945d0) | Jul 21, 2021 |
| HP            | Pavilion Notebook           | [9dd1c380c1](https://linux-hardware.org/?probe=9dd1c380c1) | Jul 15, 2021 |
| HP            | Pavilion Notebook           | [daa99f3a24](https://linux-hardware.org/?probe=daa99f3a24) | Jul 15, 2021 |
| HP            | ProBook 640 G1              | [6c9393a9d6](https://linux-hardware.org/?probe=6c9393a9d6) | Jul 08, 2021 |
| HP            | EliteBook 840 G1            | [e60c71a5e1](https://linux-hardware.org/?probe=e60c71a5e1) | Jun 25, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | [9d9ecee1b9](https://linux-hardware.org/?probe=9d9ecee1b9) | Jun 20, 2021 |
| HP            | Laptop 15-bw0xx             | [e9d94e06f1](https://linux-hardware.org/?probe=e9d94e06f1) | Jun 18, 2021 |
| Lenovo        | V130-14IKB 81HQ             | [549f1c8bd1](https://linux-hardware.org/?probe=549f1c8bd1) | May 25, 2021 |
| HP            | EliteBook 840 G2            | [304747e4c6](https://linux-hardware.org/?probe=304747e4c6) | May 23, 2021 |
| Dell          | Inspiron 3543               | [11b99bedb6](https://linux-hardware.org/?probe=11b99bedb6) | May 13, 2021 |
| Lenovo        | V330-14IKB 81B0             | [a71cb329b2](https://linux-hardware.org/?probe=a71cb329b2) | May 12, 2021 |
| Lenovo        | V330-14IKB 81B0             | [dc61da2d5e](https://linux-hardware.org/?probe=dc61da2d5e) | May 09, 2021 |
| Dell          | Inspiron 3543               | [e8771a4577](https://linux-hardware.org/?probe=e8771a4577) | May 01, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [ee57ec30cd](https://linux-hardware.org/?probe=ee57ec30cd) | Apr 28, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [95c380139d](https://linux-hardware.org/?probe=95c380139d) | Apr 28, 2021 |
| Toshiba       | dynabook R731/E             | [108510a130](https://linux-hardware.org/?probe=108510a130) | Apr 08, 2021 |
| HP            | EliteBook Folio 9470m       | [561287f5a8](https://linux-hardware.org/?probe=561287f5a8) | Apr 06, 2021 |
| HP            | 15 Notebook PC              | [ecac5c48dc](https://linux-hardware.org/?probe=ecac5c48dc) | Apr 02, 2021 |
| HP            | EliteBook 840 G6            | [95f53c1b72](https://linux-hardware.org/?probe=95f53c1b72) | Mar 19, 2021 |
| HP            | EliteBook 840 G6            | [585322e740](https://linux-hardware.org/?probe=585322e740) | Mar 19, 2021 |
| Toshiba       | Satellite L50-B             | [b345b644ae](https://linux-hardware.org/?probe=b345b644ae) | Mar 18, 2021 |
| HP            | ProBook 640 G1              | [89e652d12d](https://linux-hardware.org/?probe=89e652d12d) | Mar 18, 2021 |
| Toshiba       | dynabook Satellite B554/... | [31915e8c0b](https://linux-hardware.org/?probe=31915e8c0b) | Mar 10, 2021 |
| Toshiba       | dynabook Satellite B554/... | [e166e551cd](https://linux-hardware.org/?probe=e166e551cd) | Mar 09, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [10c98c982d](https://linux-hardware.org/?probe=10c98c982d) | Mar 07, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [09037a0a1b](https://linux-hardware.org/?probe=09037a0a1b) | Mar 06, 2021 |
| HP            | ENVY 15                     | [5c1bfc1459](https://linux-hardware.org/?probe=5c1bfc1459) | Mar 05, 2021 |
| HP            | ProBook 430 G6              | [5ed6cc994b](https://linux-hardware.org/?probe=5ed6cc994b) | Mar 05, 2021 |
| Dell          | Inspiron N5030              | [47077a37f2](https://linux-hardware.org/?probe=47077a37f2) | Feb 25, 2021 |
| Toshiba       | Satellite L50-B             | [c4ab183609](https://linux-hardware.org/?probe=c4ab183609) | Feb 24, 2021 |
| Toshiba       | Satellite L50-B             | [55c54121f8](https://linux-hardware.org/?probe=55c54121f8) | Feb 24, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [3311619921](https://linux-hardware.org/?probe=3311619921) | Feb 18, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [b573c1e746](https://linux-hardware.org/?probe=b573c1e746) | Feb 17, 2021 |
| HP            | EliteBook 8470p             | [eda69993ed](https://linux-hardware.org/?probe=eda69993ed) | Feb 17, 2021 |
| HP            | Laptop 15-da1xxx            | [66c8150e0d](https://linux-hardware.org/?probe=66c8150e0d) | Feb 14, 2021 |
| HP            | EliteBook 8470p             | [96be56a30d](https://linux-hardware.org/?probe=96be56a30d) | Feb 13, 2021 |
| TECNO         | WinPad 2                    | [336989b30d](https://linux-hardware.org/?probe=336989b30d) | Feb 10, 2021 |
| TECNO         | WinPad 2                    | [439563e244](https://linux-hardware.org/?probe=439563e244) | Feb 09, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [38d7cb1271](https://linux-hardware.org/?probe=38d7cb1271) | Feb 06, 2021 |
| Dell          | Inspiron 3580               | [417752f660](https://linux-hardware.org/?probe=417752f660) | Jan 30, 2021 |
| Lenovo        | ThinkPad P52s 20LB0021US    | [4e50af07df](https://linux-hardware.org/?probe=4e50af07df) | Jan 28, 2021 |
| Lenovo        | V310-15ISK 80SY             | [671c83ebf7](https://linux-hardware.org/?probe=671c83ebf7) | Jan 27, 2021 |
| HP            | ProBook 6560b               | [4771c30f72](https://linux-hardware.org/?probe=4771c30f72) | Jan 18, 2021 |
| HP            | Compaq Mini 110c-1100       | [e2f7ccd4ad](https://linux-hardware.org/?probe=e2f7ccd4ad) | Jan 14, 2021 |
| ASUSTek       | X540NA                      | [9b2af2d13c](https://linux-hardware.org/?probe=9b2af2d13c) | Jan 13, 2021 |
| HP            | ProBook 6560b               | [0b69385e25](https://linux-hardware.org/?probe=0b69385e25) | Jan 04, 2021 |
| HP            | ProBook 6560b               | [d6d7748e86](https://linux-hardware.org/?probe=d6d7748e86) | Dec 30, 2020 |
| HP            | EliteBook Folio 9470m       | [013db2cd8e](https://linux-hardware.org/?probe=013db2cd8e) | Dec 25, 2020 |
| Endless       | EF20EA                      | [c216bffe9d](https://linux-hardware.org/?probe=c216bffe9d) | Dec 20, 2020 |
| Endless       | EF20EA                      | [e2409b47e2](https://linux-hardware.org/?probe=e2409b47e2) | Dec 20, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [c3c7909b48](https://linux-hardware.org/?probe=c3c7909b48) | Dec 20, 2020 |
| Lenovo        | ThinkPad T470s 20HGS6PF0... | [2f91f2576d](https://linux-hardware.org/?probe=2f91f2576d) | Dec 14, 2020 |
| I-Life Dig... | ZED AIR PRO                 | [98d5a20a00](https://linux-hardware.org/?probe=98d5a20a00) | Dec 12, 2020 |
| Dell          | Inspiron 3543               | [885a64d9d3](https://linux-hardware.org/?probe=885a64d9d3) | Dec 12, 2020 |
| ASUSTek       | X202EV                      | [b3b2381999](https://linux-hardware.org/?probe=b3b2381999) | Nov 25, 2020 |
| HP            | Compaq Mini 110c-1100       | [36bc2c3cdf](https://linux-hardware.org/?probe=36bc2c3cdf) | Nov 18, 2020 |
| Lenovo        | ThinkPad X240 20AMS4J900    | [8a54e51f5a](https://linux-hardware.org/?probe=8a54e51f5a) | Nov 17, 2020 |
| HP            | Laptop 15-da1xxx            | [7c1f9ebdef](https://linux-hardware.org/?probe=7c1f9ebdef) | Nov 12, 2020 |
| HP            | EliteBook 8460p             | [ccefa81140](https://linux-hardware.org/?probe=ccefa81140) | Nov 12, 2020 |
| HP            | ZBook 15 G2                 | [5c863855cc](https://linux-hardware.org/?probe=5c863855cc) | Nov 11, 2020 |
| Dell          | Inspiron 3543               | [372e62dd5a](https://linux-hardware.org/?probe=372e62dd5a) | Nov 11, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [6b0122d8c2](https://linux-hardware.org/?probe=6b0122d8c2) | Nov 06, 2020 |
| Dell          | Latitude E6420              | [e1f1909639](https://linux-hardware.org/?probe=e1f1909639) | Oct 25, 2020 |
| Dell          | Latitude E6420              | [e1bbf1beb6](https://linux-hardware.org/?probe=e1bbf1beb6) | Oct 25, 2020 |
| HP            | EliteBook 8460p             | [a2eb617037](https://linux-hardware.org/?probe=a2eb617037) | Oct 16, 2020 |
| Dell          | Inspiron 3543               | [5b0c257b43](https://linux-hardware.org/?probe=5b0c257b43) | Oct 02, 2020 |
| Dell          | Latitude D820               | [ae1fa80f73](https://linux-hardware.org/?probe=ae1fa80f73) | Oct 02, 2020 |
| Dell          | Inspiron 3543               | [47a129fdd0](https://linux-hardware.org/?probe=47a129fdd0) | Sep 28, 2020 |
| Dell          | Inspiron 3543               | [ebcb037006](https://linux-hardware.org/?probe=ebcb037006) | Sep 28, 2020 |
| HP            | EliteBook 8460p             | [8232648226](https://linux-hardware.org/?probe=8232648226) | Sep 20, 2020 |
| Samsung       | RC410/RC510/RC710           | [37985e0340](https://linux-hardware.org/?probe=37985e0340) | Sep 19, 2020 |
| HP            | ProBook 440 G5              | [92ee6a03be](https://linux-hardware.org/?probe=92ee6a03be) | Sep 14, 2020 |
| ASUSTek       | UX305CA                     | [f51d9347e3](https://linux-hardware.org/?probe=f51d9347e3) | Sep 10, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | [6e6f79b651](https://linux-hardware.org/?probe=6e6f79b651) | Sep 10, 2020 |
| HP            | EliteBook 840 G2            | [4d64af6a38](https://linux-hardware.org/?probe=4d64af6a38) | Sep 07, 2020 |
| ASUSTek       | X551MA                      | [6e93ef18ce](https://linux-hardware.org/?probe=6e93ef18ce) | Sep 03, 2020 |
| HP            | EliteBook Folio 9480m       | [19a0f0bfdc](https://linux-hardware.org/?probe=19a0f0bfdc) | Sep 03, 2020 |
| HP            | ProBook 440 G5              | [9c70b1dad4](https://linux-hardware.org/?probe=9c70b1dad4) | Sep 02, 2020 |
| HP            | EliteBook 840 G2            | [31f100c680](https://linux-hardware.org/?probe=31f100c680) | Aug 10, 2020 |
| HP            | EliteBook 840 G2            | [c8bad363d2](https://linux-hardware.org/?probe=c8bad363d2) | Aug 10, 2020 |
| HP            | EliteBook 840 G2            | [2a88596017](https://linux-hardware.org/?probe=2a88596017) | Jul 30, 2020 |
| HP            | Pavilion Laptop 15t-cs20... | [f778796026](https://linux-hardware.org/?probe=f778796026) | Jul 16, 2020 |
| Lenovo        | ThinkPad E520 1143ADU       | [412f31bc06](https://linux-hardware.org/?probe=412f31bc06) | Jul 01, 2020 |
| Lenovo        | ThinkPad L480 20LTS1RE0Y    | [76ef35dd77](https://linux-hardware.org/?probe=76ef35dd77) | Jun 26, 2020 |
| HP            | EliteBook Folio 9470m       | [4f747e9c8a](https://linux-hardware.org/?probe=4f747e9c8a) | Jun 25, 2020 |
| HP            | ProBook 440 G2              | [21efc22417](https://linux-hardware.org/?probe=21efc22417) | Jun 21, 2020 |
| Dell          | Latitude 3150               | [0299c15a34](https://linux-hardware.org/?probe=0299c15a34) | Jun 20, 2020 |
| HP            | Pavilion x2 Detachable      | [6277131dfd](https://linux-hardware.org/?probe=6277131dfd) | Jun 20, 2020 |
| Lenovo        | ThinkPad T460 20FMS1DH01    | [f16d9a4077](https://linux-hardware.org/?probe=f16d9a4077) | Jun 17, 2020 |
| ASUSTek       | X540NA                      | [530934acb0](https://linux-hardware.org/?probe=530934acb0) | Jun 17, 2020 |
| HP            | Pavilion x2 Detachable      | [0e66f9df2c](https://linux-hardware.org/?probe=0e66f9df2c) | Jun 16, 2020 |
| Lenovo        | ThinkPad T460 20FMS1DH01    | [483d2473b0](https://linux-hardware.org/?probe=483d2473b0) | Jun 15, 2020 |
| Getac         | V110                        | [4e3a330cb5](https://linux-hardware.org/?probe=4e3a330cb5) | Jun 13, 2020 |
| Toshiba       | R84SAU2                     | [d59976ae7f](https://linux-hardware.org/?probe=d59976ae7f) | Jun 10, 2020 |
| Acer          | Aspire A315-33              | [c0eeb5a67b](https://linux-hardware.org/?probe=c0eeb5a67b) | Jun 03, 2020 |
| Lenovo        | ThinkPad E520 1143ADU       | [e903b1af8a](https://linux-hardware.org/?probe=e903b1af8a) | May 31, 2020 |
| Lenovo        | ThinkPad E520 1143ADU       | [75e6d735a0](https://linux-hardware.org/?probe=75e6d735a0) | May 31, 2020 |
| Dell          | Inspiron 5767               | [bdab68c78a](https://linux-hardware.org/?probe=bdab68c78a) | May 25, 2020 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [227b4dc4ec](https://linux-hardware.org/?probe=227b4dc4ec) | May 15, 2020 |
| Apple         | MacBookPro3,1               | [5ca063ed58](https://linux-hardware.org/?probe=5ca063ed58) | May 11, 2020 |
| Dell          | Latitude E6410              | [7a885b703e](https://linux-hardware.org/?probe=7a885b703e) | May 10, 2020 |
| Lenovo        | V110-15ISK 80TL             | [d64b4a56e0](https://linux-hardware.org/?probe=d64b4a56e0) | May 08, 2020 |
| Lenovo        | ThinkPad T440p 20AWS5D20... | [85b487e27d](https://linux-hardware.org/?probe=85b487e27d) | May 02, 2020 |
| Dell          | Inspiron 5767               | [32e3129638](https://linux-hardware.org/?probe=32e3129638) | May 02, 2020 |
| Dell          | Latitude 7490               | [cc8b2bc724](https://linux-hardware.org/?probe=cc8b2bc724) | Apr 30, 2020 |
| Lenovo        | ThinkPad T440p 20AWS5D20... | [e05b9764c6](https://linux-hardware.org/?probe=e05b9764c6) | Apr 26, 2020 |
| Lenovo        | ThinkPad T440p 20AWS5D20... | [6cf30d2192](https://linux-hardware.org/?probe=6cf30d2192) | Apr 26, 2020 |
| HP            | ProBook 6470b               | [a6132519cf](https://linux-hardware.org/?probe=a6132519cf) | Apr 21, 2020 |
| HP            | ProBook 6470b               | [255652dcf4](https://linux-hardware.org/?probe=255652dcf4) | Apr 21, 2020 |
| Lenovo        | V110-15ISK 80TL             | [2dec0ef690](https://linux-hardware.org/?probe=2dec0ef690) | Apr 18, 2020 |
| HP            | 15 Notebook PC              | [120e9af4f0](https://linux-hardware.org/?probe=120e9af4f0) | Apr 11, 2020 |
| HP            | EliteBook Folio 1040 G1     | [04ee092498](https://linux-hardware.org/?probe=04ee092498) | Apr 08, 2020 |
| HP            | Pavilion Laptop 13-an0xx... | [ecef1f0fcb](https://linux-hardware.org/?probe=ecef1f0fcb) | Apr 07, 2020 |
| HP            | Pavilion x2 Detachable      | [c64e5a3bb2](https://linux-hardware.org/?probe=c64e5a3bb2) | Apr 04, 2020 |
| ASUSTek       | X540SAA                     | [f5e7614710](https://linux-hardware.org/?probe=f5e7614710) | Mar 14, 2020 |
| HP            | Pavilion x2 Detachable      | [71875266d4](https://linux-hardware.org/?probe=71875266d4) | Mar 01, 2020 |
| HP            | Pavilion x2 Detachable      | [24e019c5a5](https://linux-hardware.org/?probe=24e019c5a5) | Mar 01, 2020 |
| HP            | Pavilion x2 Detachable      | [b634560d95](https://linux-hardware.org/?probe=b634560d95) | Mar 01, 2020 |
| HP            | ENVY TS 15                  | [eb1591f00c](https://linux-hardware.org/?probe=eb1591f00c) | Dec 23, 2019 |
| Dell          | Latitude E6220              | [37cf274f19](https://linux-hardware.org/?probe=37cf274f19) | Oct 30, 2019 |
| HP            | EliteBook 820 G2            | [05b4f35642](https://linux-hardware.org/?probe=05b4f35642) | Oct 11, 2019 |
| HP            | 630                         | [687ccfe3b1](https://linux-hardware.org/?probe=687ccfe3b1) | Sep 28, 2019 |
| EVOC          | P7xxTM1-(G)                 | [f0f19467e3](https://linux-hardware.org/?probe=f0f19467e3) | Sep 04, 2019 |
| EVOC          | P7xxTM1-(G)                 | [2ec595f039](https://linux-hardware.org/?probe=2ec595f039) | Sep 03, 2019 |
| HP            | ENVY TS 15                  | [054a6961ec](https://linux-hardware.org/?probe=054a6961ec) | Aug 18, 2019 |
| Panasonic     | CF-SX2JDQZF5                | [6986c9f2d2](https://linux-hardware.org/?probe=6986c9f2d2) | Aug 17, 2019 |
| EVOC          | P7xxTM1-(G)                 | [f9f9fbd6bd](https://linux-hardware.org/?probe=f9f9fbd6bd) | Aug 06, 2019 |
| HP            | EliteBook 8440p             | [e2c04796a0](https://linux-hardware.org/?probe=e2c04796a0) | Jul 25, 2019 |
| HP            | OMEN by HP Laptop           | [c4f5abc453](https://linux-hardware.org/?probe=c4f5abc453) | Jul 12, 2019 |
| HP            | EliteBook 840 G1            | [70e21ebad0](https://linux-hardware.org/?probe=70e21ebad0) | Jun 30, 2019 |
| HP            | EliteBook 840 G1            | [25b5bf978a](https://linux-hardware.org/?probe=25b5bf978a) | Jun 29, 2019 |
| HP            | ProBook 450 G1              | [8f23861866](https://linux-hardware.org/?probe=8f23861866) | Jun 04, 2019 |
| Unknown       | Unknown                     | [57dd20a793](https://linux-hardware.org/?probe=57dd20a793) | Jun 03, 2019 |
| Dell          | Inspiron 5570               | [86722cf4ab](https://linux-hardware.org/?probe=86722cf4ab) | May 05, 2019 |
| HP            | Notebook                    | [ca99cb8e00](https://linux-hardware.org/?probe=ca99cb8e00) | Apr 10, 2019 |
| ASUSTek       | Zephyrus M GM501GS          | [2f1b160149](https://linux-hardware.org/?probe=2f1b160149) | Nov 19, 2018 |
| Clevo         | P7xxDM2-(G)                 | [9cfa1aef75](https://linux-hardware.org/?probe=9cfa1aef75) | Jun 20, 2018 |
| EUROCOM       | Q6                          | [001ab8c139](https://linux-hardware.org/?probe=001ab8c139) | Jun 02, 2018 |
| EUROCOM       | Q6                          | [15b4e0daf2](https://linux-hardware.org/?probe=15b4e0daf2) | Jun 02, 2018 |
| Clevo         | P7xxDM2-(G)                 | [9fcaed033f](https://linux-hardware.org/?probe=9fcaed033f) | Mar 09, 2018 |
| Sony          | VGN-NS295J                  | [08cfe3b021](https://linux-hardware.org/?probe=08cfe3b021) | Dec 20, 2017 |
| Sony          | VGN-NS295J                  | [9d2ccc3bc1](https://linux-hardware.org/?probe=9d2ccc3bc1) | Dec 20, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 33        | 23.4%   |
| Ubuntu 18.04                 | 15        | 10.64%  |
| Manjaro                      | 5         | 3.55%   |
| Zorin 15                     | 4         | 2.84%   |
| Ubuntu 20.10                 | 4         | 2.84%   |
| Ubuntu 19.04                 | 4         | 2.84%   |
| Pop!_OS 20.04                | 4         | 2.84%   |
| OpenMandriva 4.2             | 4         | 2.84%   |
| Zorin 16                     | 3         | 2.13%   |
| Ubuntu 21.04                 | 3         | 2.13%   |
| Q4OS 3                       | 3         | 2.13%   |
| Arch                         | 3         | 2.13%   |
| Ubuntu 21.10                 | 2         | 1.42%   |
| Ubuntu 19.10                 | 2         | 1.42%   |
| Linux Mint 20.2              | 2         | 1.42%   |
| Linux Mint 19                | 2         | 1.42%   |
| Fedora 35                    | 2         | 1.42%   |
| Fedora 32                    | 2         | 1.42%   |
| Endless 3.9.4                | 2         | 1.42%   |
| Endless 3.9.2                | 2         | 1.42%   |
| Endless 3.9.1                | 2         | 1.42%   |
| Xubuntu 20.04                | 1         | 0.71%   |
| Ubuntu MATE 21.04            | 1         | 0.71%   |
| Ubuntu MATE 20.04            | 1         | 0.71%   |
| Ubuntu Budgie 20.04          | 1         | 0.71%   |
| Ubuntu 16.04                 | 1         | 0.71%   |
| ROSA R11                     | 1         | 0.71%   |
| ROSA R10                     | 1         | 0.71%   |
| Pop!_OS 21.04                | 1         | 0.71%   |
| Pop!_OS 20.10                | 1         | 0.71%   |
| Parrot 4.9                   | 1         | 0.71%   |
| Parrot 4.8                   | 1         | 0.71%   |
| Parrot 4.7                   | 1         | 0.71%   |
| Parrot 4.11                  | 1         | 0.71%   |
| openSUSE Tumbleweed-20210316 | 1         | 0.71%   |
| openSUSE Tumbleweed-20210221 | 1         | 0.71%   |
| OpenMandriva 4.3             | 1         | 0.71%   |
| Manjaro 20.1                 | 1         | 0.71%   |
| LMDE 5                       | 1         | 0.71%   |
| Linux Mint 20.3              | 1         | 0.71%   |
| KDE neon 20.04               | 1         | 0.71%   |
| Kali 2021.3                  | 1         | 0.71%   |
| Kali 2020.1                  | 1         | 0.71%   |
| Garuda Linux Soaring         | 1         | 0.71%   |
| Fedora 34                    | 1         | 0.71%   |
| Fedora 33                    | 1         | 0.71%   |
| Fedora 31                    | 1         | 0.71%   |
| Fedora 29                    | 1         | 0.71%   |
| Endless 3.9.5                | 1         | 0.71%   |
| Endless 3.9.3                | 1         | 0.71%   |
| Endless 3.8.7                | 1         | 0.71%   |
| Endless 3.7.8                | 1         | 0.71%   |
| Endless 3.7.7                | 1         | 0.71%   |
| Elementary 6.1               | 1         | 0.71%   |
| Elementary 5.1.7             | 1         | 0.71%   |
| Debian 11                    | 1         | 0.71%   |
| Debian 10                    | 1         | 0.71%   |
| BlackPanther 18.1            | 1         | 0.71%   |
| Arch V19.04.4                | 1         | 0.71%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 59        | 45.04%  |
| Fedora        | 8         | 6.11%   |
| Endless       | 8         | 6.11%   |
| Zorin         | 7         | 5.34%   |
| Pop!_OS       | 6         | 4.58%   |
| Manjaro       | 6         | 4.58%   |
| OpenMandriva  | 5         | 3.82%   |
| Linux Mint    | 5         | 3.82%   |
| Arch          | 4         | 3.05%   |
| Q4OS          | 3         | 2.29%   |
| Parrot        | 3         | 2.29%   |
| Ubuntu MATE   | 2         | 1.53%   |
| ROSA          | 2         | 1.53%   |
| Kali          | 2         | 1.53%   |
| Elementary    | 2         | 1.53%   |
| Debian        | 2         | 1.53%   |
| Xubuntu       | 1         | 0.76%   |
| Ubuntu Budgie | 1         | 0.76%   |
| openSUSE      | 1         | 0.76%   |
| LMDE          | 1         | 0.76%   |
| KDE neon      | 1         | 0.76%   |
| Garuda Linux  | 1         | 0.76%   |
| BlackPanther  | 1         | 0.76%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.8.0-14-generic         | 6         | 3.92%   |
| 5.11.0-38-generic        | 4         | 2.61%   |
| 5.10.14-desktop-1omv4002 | 4         | 2.61%   |
| 5.4.0-58-generic         | 3         | 1.96%   |
| 5.4.0-52-generic         | 3         | 1.96%   |
| 5.4.0-45-generic         | 3         | 1.96%   |
| 5.4.0-42-generic         | 3         | 1.96%   |
| 4.19.0-17-amd64          | 3         | 1.96%   |
| 5.8.0-59-generic         | 2         | 1.31%   |
| 5.8.0-43-generic         | 2         | 1.31%   |
| 5.4.0-67-generic         | 2         | 1.31%   |
| 5.4.0-65-generic         | 2         | 1.31%   |
| 5.4.0-54-generic         | 2         | 1.31%   |
| 5.4.0-48-generic         | 2         | 1.31%   |
| 5.4.0-47-generic         | 2         | 1.31%   |
| 5.4.0-37-generic         | 2         | 1.31%   |
| 5.3.0-28-generic         | 2         | 1.31%   |
| 5.13.19-2-MANJARO        | 2         | 1.31%   |
| 5.13.0-27-generic        | 2         | 1.31%   |
| 5.11.0-37-generic        | 2         | 1.31%   |
| 5.11.0-34-generic        | 2         | 1.31%   |
| 5.9.14-arch1-1           | 1         | 0.65%   |
| 5.9.13-200.fc33.x86_64   | 1         | 0.65%   |
| 5.8.4-200.fc32.x86_64    | 1         | 0.65%   |
| 5.8.12-arch1-1           | 1         | 0.65%   |
| 5.8.0-63-generic         | 1         | 0.65%   |
| 5.8.0-55-generic         | 1         | 0.65%   |
| 5.8.0-51-generic         | 1         | 0.65%   |
| 5.8.0-50-generic         | 1         | 0.65%   |
| 5.8.0-48-generic         | 1         | 0.65%   |
| 5.8.0-44-generic         | 1         | 0.65%   |
| 5.8.0-41-generic         | 1         | 0.65%   |
| 5.8.0-29-generic         | 1         | 0.65%   |
| 5.8.0-26-generic         | 1         | 0.65%   |
| 5.8.0-25-generic         | 1         | 0.65%   |
| 5.7.17-2-MANJARO         | 1         | 0.65%   |
| 5.6.7-200.fc31.x86_64    | 1         | 0.65%   |
| 5.6.5-050605-generic     | 1         | 0.65%   |
| 5.6.11-300.fc32.x86_64   | 1         | 0.65%   |
| 5.5.0-1parrot1-amd64     | 1         | 0.65%   |
| 5.4.0-77-generic         | 1         | 0.65%   |
| 5.4.0-7634-generic       | 1         | 0.65%   |
| 5.4.0-7629-generic       | 1         | 0.65%   |
| 5.4.0-7626-generic       | 1         | 0.65%   |
| 5.4.0-7625-generic       | 1         | 0.65%   |
| 5.4.0-74-generic         | 1         | 0.65%   |
| 5.4.0-70-generic         | 1         | 0.65%   |
| 5.4.0-4parrot1-amd64     | 1         | 0.65%   |
| 5.4.0-39-generic         | 1         | 0.65%   |
| 5.4.0-38-generic         | 1         | 0.65%   |
| 5.4.0-33-generic         | 1         | 0.65%   |
| 5.4.0-29-generic         | 1         | 0.65%   |
| 5.4.0-26-generic         | 1         | 0.65%   |
| 5.3.0-kali1-amd64        | 1         | 0.65%   |
| 5.3.0-62-generic         | 1         | 0.65%   |
| 5.3.0-59-generic         | 1         | 0.65%   |
| 5.3.0-46-generic         | 1         | 0.65%   |
| 5.3.0-45-generic         | 1         | 0.65%   |
| 5.3.0-40-generic         | 1         | 0.65%   |
| 5.3.0-24-generic         | 1         | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 34        | 23.61%  |
| 5.8.0   | 18        | 12.5%   |
| 5.11.0  | 13        | 9.03%   |
| 4.15.0  | 11        | 7.64%   |
| 5.3.0   | 7         | 4.86%   |
| 5.0.0   | 7         | 4.86%   |
| 5.13.0  | 6         | 4.17%   |
| 5.10.14 | 4         | 2.78%   |
| 4.19.0  | 4         | 2.78%   |
| 5.10.0  | 3         | 2.08%   |
| 5.16.7  | 2         | 1.39%   |
| 5.13.19 | 2         | 1.39%   |
| 4.18.0  | 2         | 1.39%   |
| 5.9.14  | 1         | 0.69%   |
| 5.9.13  | 1         | 0.69%   |
| 5.8.4   | 1         | 0.69%   |
| 5.8.12  | 1         | 0.69%   |
| 5.7.17  | 1         | 0.69%   |
| 5.6.7   | 1         | 0.69%   |
| 5.6.5   | 1         | 0.69%   |
| 5.6.11  | 1         | 0.69%   |
| 5.5.0   | 1         | 0.69%   |
| 5.2.5   | 1         | 0.69%   |
| 5.2.0   | 1         | 0.69%   |
| 5.17.5  | 1         | 0.69%   |
| 5.17.4  | 1         | 0.69%   |
| 5.16.16 | 1         | 0.69%   |
| 5.16.14 | 1         | 0.69%   |
| 5.15.13 | 1         | 0.69%   |
| 5.14.6  | 1         | 0.69%   |
| 5.14.10 | 1         | 0.69%   |
| 5.14.0  | 1         | 0.69%   |
| 5.13.12 | 1         | 0.69%   |
| 5.11.6  | 1         | 0.69%   |
| 5.10.70 | 1         | 0.69%   |
| 5.10.42 | 1         | 0.69%   |
| 5.10.16 | 1         | 0.69%   |
| 5.1.6   | 1         | 0.69%   |
| 5.0.10  | 1         | 0.69%   |
| 4.9.60  | 1         | 0.69%   |
| 4.19.1  | 1         | 0.69%   |
| 4.18.16 | 1         | 0.69%   |
| 4.16.13 | 1         | 0.69%   |
| 4.13.0  | 1         | 0.69%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 34        | 23.94%  |
| 5.8     | 20        | 14.08%  |
| 5.11    | 14        | 9.86%   |
| 4.15    | 11        | 7.75%   |
| 5.10    | 10        | 7.04%   |
| 5.13    | 9         | 6.34%   |
| 5.0     | 8         | 5.63%   |
| 5.3     | 7         | 4.93%   |
| 4.19    | 5         | 3.52%   |
| 5.6     | 3         | 2.11%   |
| 5.16    | 3         | 2.11%   |
| 5.14    | 3         | 2.11%   |
| 4.18    | 3         | 2.11%   |
| 5.9     | 2         | 1.41%   |
| 5.2     | 2         | 1.41%   |
| 5.7     | 1         | 0.7%    |
| 5.5     | 1         | 0.7%    |
| 5.17    | 1         | 0.7%    |
| 5.15    | 1         | 0.7%    |
| 5.1     | 1         | 0.7%    |
| 4.9     | 1         | 0.7%    |
| 4.16    | 1         | 0.7%    |
| 4.13    | 1         | 0.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 126       | 97.67%  |
| i686   | 3         | 2.33%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 80        | 60.15%  |
| Unknown    | 19        | 14.29%  |
| KDE5       | 12        | 9.02%   |
| X-Cinnamon | 5         | 3.76%   |
| XFCE       | 4         | 3.01%   |
| MATE       | 4         | 3.01%   |
| KDE        | 4         | 3.01%   |
| Pantheon   | 2         | 1.5%    |
| KDE4       | 2         | 1.5%    |
| Cinnamon   | 1         | 0.75%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 104       | 79.39%  |
| Wayland | 18        | 13.74%  |
| Unknown | 9         | 6.87%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 82        | 61.65%  |
| GDM     | 23        | 17.29%  |
| SDDM    | 12        | 9.02%   |
| GDM3    | 6         | 4.51%   |
| TDM     | 5         | 3.76%   |
| LightDM | 3         | 2.26%   |
| KDM     | 2         | 1.5%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 90        | 68.7%   |
| Unknown | 23        | 17.56%  |
| en_GB   | 16        | 12.21%  |
| C       | 2         | 1.53%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 74        | 56.06%  |
| EFI  | 58        | 43.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 111       | 86.05%  |
| Overlay | 9         | 6.98%   |
| Btrfs   | 7         | 5.43%   |
| Unknown | 2         | 1.55%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 83        | 63.36%  |
| GPT     | 33        | 25.19%  |
| MBR     | 15        | 11.45%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 114       | 88.37%  |
| Yes       | 15        | 11.63%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 90        | 69.77%  |
| Yes       | 39        | 30.23%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 52        | 40.31%  |
| Lenovo                      | 24        | 18.6%   |
| Dell                        | 16        | 12.4%   |
| ASUSTek Computer            | 7         | 5.43%   |
| Toshiba                     | 6         | 4.65%   |
| Samsung Electronics         | 3         | 2.33%   |
| Acer                        | 3         | 2.33%   |
| Chuwi                       | 2         | 1.55%   |
| Apple                       | 2         | 1.55%   |
| TECNO                       | 1         | 0.78%   |
| Sony                        | 1         | 0.78%   |
| SLIMBOOK                    | 1         | 0.78%   |
| Panasonic                   | 1         | 0.78%   |
| Insyde                      | 1         | 0.78%   |
| I-Life Digital Technologies | 1         | 0.78%   |
| HUAWEI                      | 1         | 0.78%   |
| Getac                       | 1         | 0.78%   |
| EVOC                        | 1         | 0.78%   |
| EUROCOM                     | 1         | 0.78%   |
| Endless                     | 1         | 0.78%   |
| Eluktronics                 | 1         | 0.78%   |
| Clevo                       | 1         | 0.78%   |
| Unknown                     | 1         | 0.78%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| HP EliteBook Folio 9480m                | 3         | 2.33%   |
| HP EliteBook Folio 9470m                | 3         | 2.33%   |
| HP EliteBook 840 G1                     | 3         | 2.33%   |
| Dell XPS 13 9310                        | 3         | 2.33%   |
| Toshiba Satellite C660                  | 2         | 1.55%   |
| HP ProBook 640 G1                       | 2         | 1.55%   |
| HP Pavilion Laptop 15-cs3xxx            | 2         | 1.55%   |
| HP EliteBook 840 G2                     | 2         | 1.55%   |
| HP Compaq Mini 110c-1100                | 2         | 1.55%   |
| HP 15 Notebook PC                       | 2         | 1.55%   |
| Dell Inspiron 5767                      | 2         | 1.55%   |
| Toshiba Satellite L50-B                 | 1         | 0.78%   |
| Toshiba R84SAU2                         | 1         | 0.78%   |
| Toshiba dynabook Satellite B554/M       | 1         | 0.78%   |
| Toshiba dynabook R731/E                 | 1         | 0.78%   |
| TECNO WinPad 2                          | 1         | 0.78%   |
| Sony VGN-NS295J                         | 1         | 0.78%   |
| SLIMBOOK PROX14-AMD                     | 1         | 0.78%   |
| Samsung RC410/RC510/RC710               | 1         | 0.78%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV | 1         | 0.78%   |
| Samsung 300E4C/300E5C/300E7C            | 1         | 0.78%   |
| Panasonic CF-SX2JDQZF5                  | 1         | 0.78%   |
| Lenovo V330-14IKB 81B0                  | 1         | 0.78%   |
| Lenovo V310-15ISK 80SY                  | 1         | 0.78%   |
| Lenovo V14-IGL 82C2                     | 1         | 0.78%   |
| Lenovo V130-14IKB 81HQ                  | 1         | 0.78%   |
| Lenovo V110-15ISK 80TL                  | 1         | 0.78%   |
| Lenovo ThinkPad X250 20CLA21MJP         | 1         | 0.78%   |
| Lenovo ThinkPad X240 20AMS4J900         | 1         | 0.78%   |
| Lenovo ThinkPad X240 20AL00CQAU         | 1         | 0.78%   |
| Lenovo ThinkPad X131e 33672T5           | 1         | 0.78%   |
| Lenovo ThinkPad X1 Carbon 3460AE4       | 1         | 0.78%   |
| Lenovo ThinkPad T490s 20NYS8J900        | 1         | 0.78%   |
| Lenovo ThinkPad T470s W10DG 20JTS16607  | 1         | 0.78%   |
| Lenovo ThinkPad T470s 20HGS6PF09        | 1         | 0.78%   |
| Lenovo ThinkPad T460s 20FAS3QC00        | 1         | 0.78%   |
| Lenovo ThinkPad T460 20FMS1DH01         | 1         | 0.78%   |
| Lenovo ThinkPad T440p 20AWS5D200        | 1         | 0.78%   |
| Lenovo ThinkPad P52s 20LB0021US         | 1         | 0.78%   |
| Lenovo ThinkPad L480 20LTS1RE0Y         | 1         | 0.78%   |
| Lenovo ThinkPad E520 1143ADU            | 1         | 0.78%   |
| Lenovo IdeaPad 330S-14IKB 81F4          | 1         | 0.78%   |
| Lenovo IdeaPad 330-15IKB 81DE           | 1         | 0.78%   |
| Lenovo IdeaPad 320S-14IKB 80X4          | 1         | 0.78%   |
| Lenovo IdeaPad 3 15IIL05 81WE           | 1         | 0.78%   |
| Lenovo IdeaPad 100S-11IBY 80R2          | 1         | 0.78%   |
| Insyde i101c                            | 1         | 0.78%   |
| I-Life Digital ZED AIR PRO              | 1         | 0.78%   |
| HUAWEI NBLK-WAX9X                       | 1         | 0.78%   |
| HP ZBook 15 G2                          | 1         | 0.78%   |
| HP ProBook 6560b                        | 1         | 0.78%   |
| HP ProBook 6470b                        | 1         | 0.78%   |
| HP ProBook 4540s                        | 1         | 0.78%   |
| HP ProBook 450 G1                       | 1         | 0.78%   |
| HP ProBook 440 G6                       | 1         | 0.78%   |
| HP ProBook 440 G5                       | 1         | 0.78%   |
| HP ProBook 440 G2                       | 1         | 0.78%   |
| HP ProBook 430 G6                       | 1         | 0.78%   |
| HP Presario CQ56                        | 1         | 0.78%   |
| HP Pavilion x2 Detachable               | 1         | 0.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| HP EliteBook           | 20        | 15.5%   |
| Lenovo ThinkPad        | 14        | 10.85%  |
| HP ProBook             | 10        | 7.75%   |
| HP Pavilion            | 7         | 5.43%   |
| Dell Latitude          | 7         | 5.43%   |
| Dell Inspiron          | 6         | 4.65%   |
| Lenovo IdeaPad         | 5         | 3.88%   |
| Toshiba Satellite      | 3         | 2.33%   |
| HP Laptop              | 3         | 2.33%   |
| HP ENVY                | 3         | 2.33%   |
| Dell XPS               | 3         | 2.33%   |
| Acer Aspire            | 3         | 2.33%   |
| Toshiba dynabook       | 2         | 1.55%   |
| HP Compaq              | 2         | 1.55%   |
| HP 15                  | 2         | 1.55%   |
| Toshiba R84SAU2        | 1         | 0.78%   |
| TECNO WinPad           | 1         | 0.78%   |
| Sony VGN-NS295J        | 1         | 0.78%   |
| SLIMBOOK PROX14-AMD    | 1         | 0.78%   |
| Samsung RC410          | 1         | 0.78%   |
| Samsung 300E5EV        | 1         | 0.78%   |
| Samsung 300E4C         | 1         | 0.78%   |
| Panasonic CF-SX2JDQZF5 | 1         | 0.78%   |
| Lenovo V330-14IKB      | 1         | 0.78%   |
| Lenovo V310-15ISK      | 1         | 0.78%   |
| Lenovo V14-IGL         | 1         | 0.78%   |
| Lenovo V130-14IKB      | 1         | 0.78%   |
| Lenovo V110-15ISK      | 1         | 0.78%   |
| Insyde i101c           | 1         | 0.78%   |
| I-Life Digital ZED     | 1         | 0.78%   |
| HUAWEI NBLK-WAX9X      | 1         | 0.78%   |
| HP ZBook               | 1         | 0.78%   |
| HP Presario            | 1         | 0.78%   |
| HP OMEN                | 1         | 0.78%   |
| HP Notebook            | 1         | 0.78%   |
| HP 630                 | 1         | 0.78%   |
| Getac V110             | 1         | 0.78%   |
| EVOC P7xxTM1-(G)       | 1         | 0.78%   |
| EUROCOM Q6             | 1         | 0.78%   |
| Endless EF20EA         | 1         | 0.78%   |
| Eluktronics MAG-15u    | 1         | 0.78%   |
| Clevo P7xxDM2-(G)      | 1         | 0.78%   |
| Chuwi HeroBook         | 1         | 0.78%   |
| Chuwi GemiBook         | 1         | 0.78%   |
| ASUS Zephyrus          | 1         | 0.78%   |
| ASUS X551MA            | 1         | 0.78%   |
| ASUS X540SAA           | 1         | 0.78%   |
| ASUS X540NA            | 1         | 0.78%   |
| ASUS X202EV            | 1         | 0.78%   |
| ASUS VivoBook          | 1         | 0.78%   |
| ASUS UX305CA           | 1         | 0.78%   |
| Apple MacBookPro3      | 1         | 0.78%   |
| Apple MacBookPro16     | 1         | 0.78%   |
| Unknown                | 1         | 0.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 15        | 11.63%  |
| 2013 | 14        | 10.85%  |
| 2015 | 13        | 10.08%  |
| 2019 | 12        | 9.3%    |
| 2016 | 12        | 9.3%    |
| 2014 | 11        | 8.53%   |
| 2012 | 11        | 8.53%   |
| 2017 | 10        | 7.75%   |
| 2011 | 10        | 7.75%   |
| 2020 | 8         | 6.2%    |
| 2010 | 7         | 5.43%   |
| 2009 | 2         | 1.55%   |
| 2007 | 2         | 1.55%   |
| 2021 | 1         | 0.78%   |
| 2008 | 1         | 0.78%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 129       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 119       | 90.84%  |
| Enabled  | 12        | 9.16%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 129       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 43        | 33.08%  |
| 4.01-8.0    | 35        | 26.92%  |
| 8.01-16.0   | 17        | 13.08%  |
| 16.01-24.0  | 14        | 10.77%  |
| 1.01-2.0    | 11        | 8.46%   |
| 32.01-64.0  | 4         | 3.08%   |
| 64.01-256.0 | 3         | 2.31%   |
| 24.01-32.0  | 1         | 0.77%   |
| 2.01-3.0    | 1         | 0.77%   |
| 0.51-1.0    | 1         | 0.77%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 46        | 31.08%  |
| 2.01-3.0  | 42        | 28.38%  |
| 3.01-4.0  | 25        | 16.89%  |
| 4.01-8.0  | 20        | 13.51%  |
| 0.51-1.0  | 12        | 8.11%   |
| 8.01-16.0 | 3         | 2.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 113       | 84.96%  |
| 2      | 16        | 12.03%  |
| 10     | 1         | 0.75%   |
| 8      | 1         | 0.75%   |
| 4      | 1         | 0.75%   |
| 3      | 1         | 0.75%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 78        | 60.47%  |
| Yes       | 51        | 39.53%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 112       | 86.82%  |
| No        | 17        | 13.18%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 123       | 95.35%  |
| No        | 6         | 4.65%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 97        | 74.05%  |
| No        | 34        | 25.95%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Kenya   | 129       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City     | Notebooks | Percent |
|----------|-----------|---------|
| Nairobi  | 120       | 89.55%  |
| Mombasa  | 4         | 2.99%   |
| Nyeri    | 3         | 2.24%   |
| Nakuru   | 2         | 1.49%   |
| Kiambu   | 2         | 1.49%   |
| Mlolongo | 1         | 0.75%   |
| Maralal  | 1         | 0.75%   |
| Kisii    | 1         | 0.75%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 40        | 54     | 27.21%  |
| Toshiba             | 19        | 24     | 12.93%  |
| WDC                 | 18        | 24     | 12.24%  |
| Samsung Electronics | 14        | 23     | 9.52%   |
| Unknown             | 11        | 17     | 7.48%   |
| HGST                | 10        | 17     | 6.8%    |
| Hitachi             | 6         | 7      | 4.08%   |
| Crucial             | 6         | 8      | 4.08%   |
| SanDisk             | 5         | 5      | 3.4%    |
| Micron Technology   | 4         | 4      | 2.72%   |
| MARSHAL             | 3         | 3      | 2.04%   |
| Kingston            | 2         | 4      | 1.36%   |
| SK Hynix            | 1         | 1      | 0.68%   |
| PLEXTOR             | 1         | 1      | 0.68%   |
| Netac               | 1         | 1      | 0.68%   |
| Intel               | 1         | 1      | 0.68%   |
| HUAWEI              | 1         | 1      | 0.68%   |
| Golden              | 1         | 1      | 0.68%   |
| CARLSTEIN           | 1         | 2      | 0.68%   |
| Apple               | 1         | 1      | 0.68%   |
| A-DATA Technology   | 1         | 1      | 0.68%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 8         | 5.19%   |
| Seagate ST500LT012-9WS142 500GB      | 5         | 3.25%   |
| HGST HTS725050A7E630 500GB           | 5         | 3.25%   |
| Samsung SSD 960 EVO 1TB              | 4         | 2.6%    |
| WDC PC SN730 NVMe 512GB              | 3         | 1.95%   |
| Unknown MMC Card  64GB               | 3         | 1.95%   |
| Unknown MMC Card  32GB               | 3         | 1.95%   |
| Toshiba MQ04ABF100 1TB               | 3         | 1.95%   |
| Seagate ST9500325AS 500GB            | 3         | 1.95%   |
| Seagate ST500LT012-1DG142 500GB      | 3         | 1.95%   |
| Seagate ST500LM021-1KJ152 500GB      | 3         | 1.95%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 3         | 1.95%   |
| Crucial CT2050MX300SSD1 2TB          | 3         | 1.95%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 2         | 1.3%    |
| WDC WD2500BEKT-75PVMT0 250GB         | 2         | 1.3%    |
| Unknown NCard  32GB                  | 2         | 1.3%    |
| Toshiba MQ01ABF050 500GB             | 2         | 1.3%    |
| Toshiba MQ01ABD100 1TB               | 2         | 1.3%    |
| Seagate ST500VT000-1DK142 500GB      | 2         | 1.3%    |
| Seagate ST250LT003-9YG14C 250GB      | 2         | 1.3%    |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 2         | 1.3%    |
| Samsung NVMe SSD Drive 512GB         | 2         | 1.3%    |
| HGST HTS541010A9E680 1TB             | 2         | 1.3%    |
| WDC WDS100T1B0A-00H9H0 1TB SSD       | 1         | 0.65%   |
| WDC WD5000LPVX-75V0TT0 500GB         | 1         | 0.65%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.65%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 0.65%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 1         | 0.65%   |
| WDC WD5000LPCX-22VHAT1 500GB         | 1         | 0.65%   |
| WDC WD5000BPVT-60HXZT3 500GB         | 1         | 0.65%   |
| WDC WD3200BUCT-63TWBY0 320GB         | 1         | 0.65%   |
| WDC WD10SPZX-60Z10T0 1TB             | 1         | 0.65%   |
| WDC WD10JPVX-60JC3T0 1TB             | 1         | 0.65%   |
| WDC WD10JPCX-24UE4T0 1TB             | 1         | 0.65%   |
| Unknown MMC Card  4GB                | 1         | 0.65%   |
| Unknown MMC Card  2GB                | 1         | 0.65%   |
| Unknown EB2MW  32GB                  | 1         | 0.65%   |
| Unknown ASTC  32GB                   | 1         | 0.65%   |
| Unknown 68CHP  16GB                  | 1         | 0.65%   |
| Toshiba THNSNJ256G8NY 256GB SSD      | 1         | 0.65%   |
| Toshiba NVMe SSD Drive 240GB         | 1         | 0.65%   |
| Toshiba MQ01ACF050 500GB             | 1         | 0.65%   |
| Toshiba MQ01ACF032 320GB             | 1         | 0.65%   |
| Toshiba MQ01ABF032 320GB             | 1         | 0.65%   |
| Toshiba MQ01ABD050V 500GB            | 1         | 0.65%   |
| Toshiba MK5076GSX 500GB              | 1         | 0.65%   |
| Toshiba MK3263GSX 320GB              | 1         | 0.65%   |
| Toshiba MK3252GSX 320GB              | 1         | 0.65%   |
| Toshiba MK1234GSX 120GB              | 1         | 0.65%   |
| Toshiba KXG6AZNV512G 512GB           | 1         | 0.65%   |
| Toshiba KXG60ZNV512G 512GB           | 1         | 0.65%   |
| SK Hynix NVMe SSD Drive 256GB        | 1         | 0.65%   |
| Seagate ST9750420AS 752GB            | 1         | 0.65%   |
| Seagate ST9160314AS 160GB            | 1         | 0.65%   |
| Seagate ST750LM000-1EJ16G-SSHD 752GB | 1         | 0.65%   |
| Seagate ST500LM030-1RK17D 500GB      | 1         | 0.65%   |
| Seagate ST500LM000-1EJ162 500GB      | 1         | 0.65%   |
| Seagate ST320VT000-1BS14C 320GB      | 1         | 0.65%   |
| Seagate ST2000LM003 HN-M 2TB         | 1         | 0.65%   |
| Seagate ST1000VT001-1RE172 1TB       | 1         | 0.65%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 40        | 54     | 45.45%  |
| Toshiba | 15        | 20     | 17.05%  |
| WDC     | 14        | 20     | 15.91%  |
| HGST    | 10        | 17     | 11.36%  |
| Hitachi | 6         | 7      | 6.82%   |
| MARSHAL | 3         | 3      | 3.41%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 6         | 8      | 24%     |
| SanDisk             | 5         | 5      | 20%     |
| Samsung Electronics | 4         | 7      | 16%     |
| Micron Technology   | 2         | 2      | 8%      |
| Kingston            | 2         | 4      | 8%      |
| WDC                 | 1         | 1      | 4%      |
| Toshiba             | 1         | 1      | 4%      |
| PLEXTOR             | 1         | 1      | 4%      |
| Netac               | 1         | 1      | 4%      |
| Golden              | 1         | 1      | 4%      |
| A-DATA Technology   | 1         | 1      | 4%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 85        | 121    | 58.62%  |
| SSD     | 25        | 32     | 17.24%  |
| NVMe    | 22        | 27     | 15.17%  |
| MMC     | 11        | 17     | 7.59%   |
| Unknown | 2         | 3      | 1.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 106       | 154    | 75.18%  |
| NVMe | 22        | 27     | 15.6%   |
| MMC  | 11        | 17     | 7.8%    |
| SAS  | 2         | 2      | 1.42%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 72        | 96     | 66.67%  |
| 0.51-1.0   | 31        | 42     | 28.7%   |
| 1.01-2.0   | 4         | 11     | 3.7%    |
| 3.01-4.0   | 1         | 4      | 0.93%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 42        | 31.34%  |
| 101-250        | 27        | 20.15%  |
| 501-1000       | 19        | 14.18%  |
| 51-100         | 11        | 8.21%   |
| 1-20           | 8         | 5.97%   |
| 21-50          | 7         | 5.22%   |
| Unknown        | 7         | 5.22%   |
| 2001-3000      | 5         | 3.73%   |
| 1001-2000      | 5         | 3.73%   |
| More than 3000 | 3         | 2.24%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 38        | 27.14%  |
| 21-50          | 26        | 18.57%  |
| 101-250        | 26        | 18.57%  |
| 251-500        | 16        | 11.43%  |
| 51-100         | 15        | 10.71%  |
| Unknown        | 7         | 5%      |
| 1001-2000      | 4         | 2.86%   |
| 501-1000       | 4         | 2.86%   |
| More than 3000 | 3         | 2.14%   |
| 2001-3000      | 1         | 0.71%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD2500BEKT-75PVMT0 250GB    | 2         | 2      | 11.76%  |
| Seagate ST500LT012-1DG142 500GB | 2         | 2      | 11.76%  |
| WDC WD10SPZX-60Z10T0 1TB        | 1         | 1      | 5.88%   |
| Toshiba MQ01ABD100 1TB          | 1         | 1      | 5.88%   |
| Toshiba MQ01ABD050V 500GB       | 1         | 1      | 5.88%   |
| Toshiba MK3263GSX 320GB         | 1         | 1      | 5.88%   |
| Toshiba MK3252GSX 320GB         | 1         | 1      | 5.88%   |
| Seagate ST9500325AS 500GB       | 1         | 1      | 5.88%   |
| Seagate ST1000LM035-1RK172 1TB  | 1         | 1      | 5.88%   |
| MARSHAL MAL2750SA-T54 752GB     | 1         | 1      | 5.88%   |
| Hitachi HTS545032B9A300 320GB   | 1         | 1      | 5.88%   |
| HGST HTS725050A7E630 500GB      | 1         | 1      | 5.88%   |
| HGST HTS541515A9E630 1TB        | 1         | 2      | 5.88%   |
| HGST HTS541010A9E680 1TB        | 1         | 2      | 5.88%   |
| Crucial CT2050MX300SSD1 2TB     | 1         | 2      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 4         | 4      | 25%     |
| Seagate | 4         | 4      | 25%     |
| WDC     | 3         | 3      | 18.75%  |
| HGST    | 2         | 5      | 12.5%   |
| MARSHAL | 1         | 1      | 6.25%   |
| Hitachi | 1         | 1      | 6.25%   |
| Crucial | 1         | 2      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 4         | 4      | 26.67%  |
| Seagate | 4         | 4      | 26.67%  |
| WDC     | 3         | 3      | 20%     |
| HGST    | 2         | 5      | 13.33%  |
| MARSHAL | 1         | 1      | 6.67%   |
| Hitachi | 1         | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 18     | 93.75%  |
| SSD  | 1         | 2      | 6.25%   |

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
| Detected | 85        | 126    | 64.89%  |
| Works    | 31        | 54     | 23.66%  |
| Malfunc  | 15        | 20     | 11.45%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 113       | 81.88%  |
| Samsung Electronics          | 11        | 7.97%   |
| Toshiba America Info Systems | 3         | 2.17%   |
| Sandisk                      | 3         | 2.17%   |
| AMD                          | 3         | 2.17%   |
| Micron Technology            | 2         | 1.45%   |
| SK Hynix                     | 1         | 0.72%   |
| ASMedia Technology           | 1         | 0.72%   |
| Apple                        | 1         | 0.72%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 18        | 12.77%  |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 14        | 9.93%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 11        | 7.8%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 10        | 7.09%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 9         | 6.38%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 9         | 6.38%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 4.26%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 5         | 3.55%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 4         | 2.84%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 2.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 2.84%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 3         | 2.13%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 3         | 2.13%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 2.13%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 2.13%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 3         | 2.13%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 1.42%   |
| Micron Non-Volatile memory controller                                            | 2         | 1.42%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 1.42%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 1.42%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.42%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 1.42%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 1.42%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 1         | 0.71%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 1         | 0.71%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.71%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.71%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1         | 0.71%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.71%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 0.71%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 0.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 0.71%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 0.71%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 1         | 0.71%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 1         | 0.71%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 1         | 0.71%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 1         | 0.71%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 1         | 0.71%   |
| ASMedia 106x SATA/RAID Controller                                                | 1         | 0.71%   |
| Apple ANS2 NVMe Controller                                                       | 1         | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 100       | 72.46%  |
| NVMe | 22        | 15.94%  |
| RAID | 12        | 8.7%    |
| IDE  | 4         | 2.9%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 125       | 96.9%   |
| AMD    | 4         | 3.1%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz           | 5         | 3.88%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 5         | 3.88%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 4         | 3.1%    |
| Intel Core i5-8265U CPU @ 1.60GHz           | 3         | 2.33%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 3         | 2.33%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 3         | 2.33%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 3         | 2.33%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 3         | 2.33%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 3         | 2.33%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 1.55%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 1.55%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 2         | 1.55%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 1.55%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 2         | 1.55%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.55%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 1.55%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 2         | 1.55%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.55%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 2         | 1.55%   |
| Intel Core i5-3437U CPU @ 1.90GHz           | 2         | 1.55%   |
| Intel Core i5-3427U CPU @ 1.80GHz           | 2         | 1.55%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 1.55%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 1.55%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 1.55%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 2         | 1.55%   |
| Intel Core i3-4100M CPU @ 2.50GHz           | 2         | 1.55%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 2         | 1.55%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 2         | 1.55%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 2         | 1.55%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 2         | 1.55%   |
| Intel Celeron CPU 1007U @ 1.50GHz           | 2         | 1.55%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 2         | 1.55%   |
| Intel Atom CPU N270 @ 1.60GHz               | 2         | 1.55%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 0.78%   |
| Intel Pentium CPU 2117U @ 1.80GHz           | 1         | 0.78%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz            | 1         | 0.78%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1         | 0.78%   |
| Intel Core i9-9880H CPU @ 2.30GHz           | 1         | 0.78%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 0.78%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 0.78%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1         | 0.78%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 0.78%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.78%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 0.78%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 0.78%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 0.78%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 0.78%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz          | 1         | 0.78%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 0.78%   |
| Intel Core i7-4600M CPU @ 2.90GHz           | 1         | 0.78%   |
| Intel Core i7-2620M CPU @ 2.70GHz           | 1         | 0.78%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 1         | 0.78%   |
| Intel Core i5-8350U CPU @ 1.70GHz           | 1         | 0.78%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1         | 0.78%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 1         | 0.78%   |
| Intel Core i5-4310U CPU @ 2.00GHz           | 1         | 0.78%   |
| Intel Core i5-3317U CPU @ 1.70GHz           | 1         | 0.78%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 0.78%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 1         | 0.78%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 1         | 0.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 40        | 31.01%  |
| Intel Core i7           | 34        | 26.36%  |
| Intel Celeron           | 15        | 11.63%  |
| Intel Core i3           | 13        | 10.08%  |
| Intel Atom              | 8         | 6.2%    |
| Intel Pentium           | 4         | 3.1%    |
| Other                   | 3         | 2.33%   |
| Intel Pentium Dual-Core | 2         | 1.55%   |
| Intel Core i9           | 2         | 1.55%   |
| Intel Core 2 Duo        | 2         | 1.55%   |
| AMD A10                 | 2         | 1.55%   |
| Intel Core m3           | 1         | 0.78%   |
| Intel Core 2            | 1         | 0.78%   |
| AMD Ryzen 7             | 1         | 0.78%   |
| AMD Ryzen 5             | 1         | 0.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 84        | 65.12%  |
| 4       | 37        | 28.68%  |
| 8       | 3         | 2.33%   |
| 6       | 2         | 1.55%   |
| 1       | 2         | 1.55%   |
| Unknown | 1         | 0.78%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 129       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 99        | 76.74%  |
| 1       | 29        | 22.48%  |
| Unknown | 1         | 0.78%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 127       | 98.45%  |
| 32-bit         | 2         | 1.55%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 18.8%   |
| 0x306a9    | 12        | 9.02%   |
| 0x40651    | 11        | 8.27%   |
| 0x206a7    | 11        | 8.27%   |
| 0x306c3    | 9         | 6.77%   |
| 0x806ea    | 6         | 4.51%   |
| 0x306d4    | 6         | 4.51%   |
| 0x406e3    | 5         | 3.76%   |
| 0x30678    | 5         | 3.76%   |
| 0x806ec    | 4         | 3.01%   |
| 0x806e9    | 3         | 2.26%   |
| 0x806c1    | 3         | 2.26%   |
| 0x406c4    | 3         | 2.26%   |
| 0x20655    | 3         | 2.26%   |
| 0x1067a    | 3         | 2.26%   |
| 0x906ea    | 2         | 1.5%    |
| 0x906e9    | 2         | 1.5%    |
| 0x806eb    | 2         | 1.5%    |
| 0x706e5    | 2         | 1.5%    |
| 0x706a8    | 2         | 1.5%    |
| 0x706a1    | 2         | 1.5%    |
| 0x406c3    | 2         | 1.5%    |
| 0x106c2    | 2         | 1.5%    |
| 0x906ec    | 1         | 0.75%   |
| 0x6fa      | 1         | 0.75%   |
| 0x6f6      | 1         | 0.75%   |
| 0x506e3    | 1         | 0.75%   |
| 0x506c9    | 1         | 0.75%   |
| 0x08600103 | 1         | 0.75%   |
| 0x08108109 | 1         | 0.75%   |
| 0x0600611a | 1         | 0.75%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 29        | 22.48%  |
| Haswell       | 23        | 17.83%  |
| Silvermont    | 13        | 10.08%  |
| IvyBridge     | 13        | 10.08%  |
| SandyBridge   | 11        | 8.53%   |
| Skylake       | 8         | 6.2%    |
| Broadwell     | 6         | 4.65%   |
| Westmere      | 4         | 3.1%    |
| Goldmont plus | 4         | 3.1%    |
| TigerLake     | 3         | 2.33%   |
| Penryn        | 3         | 2.33%   |
| IceLake       | 3         | 2.33%   |
| Excavator     | 2         | 1.55%   |
| Core          | 2         | 1.55%   |
| Bonnell       | 2         | 1.55%   |
| Zen+          | 1         | 0.78%   |
| Zen 2         | 1         | 0.78%   |
| Goldmont      | 1         | 0.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 116       | 80.56%  |
| Nvidia | 15        | 10.42%  |
| AMD    | 13        | 9.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 14        | 9.52%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 13        | 8.84%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 6.8%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 6.12%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 8         | 5.44%   |
| Intel HD Graphics 620                                                                    | 7         | 4.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 4.76%   |
| Intel UHD Graphics 620                                                                   | 6         | 4.08%   |
| Intel HD Graphics 5500                                                                   | 6         | 4.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 4.08%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 4.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 3.4%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 2.72%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 2.72%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 2.04%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 1.36%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 2         | 1.36%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 1.36%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.36%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.36%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 1.36%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 1.36%   |
| Nvidia TU104BM [GeForce RTX 2080 Mobile]                                                 | 1         | 0.68%   |
| Nvidia GT218M [GeForce 315M]                                                             | 1         | 0.68%   |
| Nvidia GP108GLM [Quadro P500 Mobile]                                                     | 1         | 0.68%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.68%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                                  | 1         | 0.68%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.68%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.68%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.68%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 1         | 0.68%   |
| Nvidia G84M [GeForce 8600M GT]                                                           | 1         | 0.68%   |
| Nvidia G72M [GeForce Go 7400]                                                            | 1         | 0.68%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 1         | 0.68%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 0.68%   |
| Intel HD Graphics 630                                                                    | 1         | 0.68%   |
| Intel HD Graphics 530                                                                    | 1         | 0.68%   |
| Intel HD Graphics 520                                                                    | 1         | 0.68%   |
| Intel HD Graphics 515                                                                    | 1         | 0.68%   |
| Intel HD Graphics 500                                                                    | 1         | 0.68%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 0.68%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 0.68%   |
| AMD RV620/M82 [Mobility Radeon HD 3410/3430]                                             | 1         | 0.68%   |
| AMD Renoir                                                                               | 1         | 0.68%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 0.68%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 1         | 0.68%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 1         | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 101       | 78.29%  |
| Intel + Nvidia | 9         | 6.98%   |
| 1 x Nvidia     | 6         | 4.65%   |
| Intel + AMD    | 6         | 4.65%   |
| 1 x AMD        | 6         | 4.65%   |
| 2 x AMD        | 1         | 0.78%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 123       | 93.89%  |
| Proprietary | 7         | 5.34%   |
| Unknown     | 1         | 0.76%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 105       | 79.55%  |
| 1.01-2.0   | 9         | 6.82%   |
| 0.01-0.5   | 7         | 5.3%    |
| 3.01-4.0   | 6         | 4.55%   |
| 7.01-8.0   | 4         | 3.03%   |
| 0.51-1.0   | 1         | 0.76%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 30        | 22.56%  |
| Chimei Innolux          | 26        | 19.55%  |
| BOE                     | 22        | 16.54%  |
| LG Display              | 19        | 14.29%  |
| Samsung Electronics     | 9         | 6.77%   |
| Hewlett-Packard         | 6         | 4.51%   |
| Sharp                   | 3         | 2.26%   |
| Chi Mei Optoelectronics | 3         | 2.26%   |
| Apple                   | 3         | 2.26%   |
| Lenovo                  | 2         | 1.5%    |
| KDC                     | 2         | 1.5%    |
| InfoVision              | 2         | 1.5%    |
| HannStar                | 2         | 1.5%    |
| LG Philips              | 1         | 0.75%   |
| Eizo                    | 1         | 0.75%   |
| CVT                     | 1         | 0.75%   |
| Acer                    | 1         | 0.75%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                  | 3         | 2.26%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 2.26%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 3         | 2.26%   |
| Chimei Innolux LCD Monitor CMN14A3 1600x900 309x174mm 14.0-inch          | 3         | 2.26%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 2         | 1.5%    |
| HannStar HSD100IFW1 HSD03E9 1024x600 220x129mm 10.0-inch                 | 2         | 1.5%    |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch         | 2         | 1.5%    |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x173mm 13.9-inch          | 2         | 1.5%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 1.5%    |
| BOE LCD Monitor BOE0780 1920x1080 344x194mm 15.5-inch                    | 2         | 1.5%    |
| BOE LCD Monitor BOE0695 1920x1080 380x210mm 17.1-inch                    | 2         | 1.5%    |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 1.5%    |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch            | 2         | 1.5%    |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch     | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 309x174mm 14.0-inch     | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC3051 1366x768 344x194mm 15.5-inch     | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SDC4942 1366x768 309x174mm 14.0-inch     | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SAM7017 3840x2160 950x540mm 43.0-inch    | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch     | 1         | 0.75%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch              | 1         | 0.75%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch             | 1         | 0.75%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch             | 1         | 0.75%   |
| LG Display LCD Monitor LGD0532 1920x1080 344x194mm 15.5-inch             | 1         | 0.75%   |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch              | 1         | 0.75%   |
| LG Display LCD Monitor LGD04FD 1366x768 344x194mm 15.5-inch              | 1         | 0.75%   |
| LG Display LCD Monitor LGD0493 1366x768 344x194mm 15.5-inch              | 1         | 0.75%   |
| LG Display LCD Monitor LGD048B 1366x768 309x174mm 14.0-inch              | 1         | 0.75%   |
| LG Display LCD Monitor LGD045E 1366x768 309x174mm 14.0-inch              | 1         | 0.75%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch              | 1         | 0.75%   |
| LG Display LCD Monitor LGD03CD 1366x768 277x156mm 12.5-inch              | 1         | 0.75%   |
| LG Display LCD Monitor LGD03B8 1366x768 310x174mm 14.0-inch              | 1         | 0.75%   |
| LG Display LCD Monitor LGD03AD 1366x768 309x174mm 14.0-inch              | 1         | 0.75%   |
| LG Display LCD Monitor LGD0386 1366x768 309x174mm 14.0-inch              | 1         | 0.75%   |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch              | 1         | 0.75%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch              | 1         | 0.75%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch              | 1         | 0.75%   |
| Lenovo LEN S24e-10 LEN61CA 1920x1080 527x296mm 23.8-inch                 | 1         | 0.75%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 1         | 0.75%   |
| KDC LCD Monitor KDC05F1 1366x768 256x144mm 11.6-inch                     | 1         | 0.75%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                     | 1         | 0.75%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch             | 1         | 0.75%   |
| InfoVision LCD Monitor IVO04E3 1366x768 277x156mm 12.5-inch              | 1         | 0.75%   |
| Hewlett-Packard Z23i HWP3090 1920x1080 509x286mm 23.0-inch               | 1         | 0.75%   |
| Hewlett-Packard W2072a HWP3000 1600x900 443x249mm 20.0-inch              | 1         | 0.75%   |
| Hewlett-Packard V197 HWP3348 1366x768 410x230mm 18.5-inch                | 1         | 0.75%   |
| Hewlett-Packard LCD Monitor E232                                         | 1         | 0.75%   |
| Hewlett-Packard 27fw HPN354A 1920x1080 598x336mm 27.0-inch               | 1         | 0.75%   |
| Hewlett-Packard 2311 HWP293A 1920x1080 509x286mm 23.0-inch               | 1         | 0.75%   |
| Eizo L557 ENC1690 1280x1024 337x270mm 17.0-inch                          | 1         | 0.75%   |
| CVT CVTE TV CVT0003 1920x1080 1000x610mm 46.1-inch                       | 1         | 0.75%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch         | 1         | 0.75%   |
| Chimei Innolux LCD Monitor CMN15FF 1366x768 344x193mm 15.5-inch          | 1         | 0.75%   |
| Chimei Innolux LCD Monitor CMN15D3 1920x1080 344x193mm 15.5-inch         | 1         | 0.75%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch          | 1         | 0.75%   |
| Chimei Innolux LCD Monitor CMN15BB 1920x1080 344x194mm 15.5-inch         | 1         | 0.75%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 1         | 0.75%   |
| Chimei Innolux LCD Monitor CMN14E3 1366x768 309x173mm 13.9-inch          | 1         | 0.75%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 1         | 0.75%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 1         | 0.75%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 66        | 51.56%  |
| 1920x1080 (FHD)   | 37        | 28.91%  |
| 1600x900 (HD+)    | 10        | 7.81%   |
| 1920x1200 (WUXGA) | 3         | 2.34%   |
| 1280x800 (WXGA)   | 2         | 1.56%   |
| 1024x600          | 2         | 1.56%   |
| 3840x2160 (4K)    | 1         | 0.78%   |
| 3072x1920         | 1         | 0.78%   |
| 2560x1080         | 1         | 0.78%   |
| 2160x1440         | 1         | 0.78%   |
| 1440x900 (WXGA+)  | 1         | 0.78%   |
| 1360x768          | 1         | 0.78%   |
| 1280x1024 (SXGA)  | 1         | 0.78%   |
| Unknown           | 1         | 0.78%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 48        | 36.36%  |
| 13      | 29        | 21.97%  |
| 14      | 24        | 18.18%  |
| 11      | 6         | 4.55%   |
| 12      | 5         | 3.79%   |
| 17      | 4         | 3.03%   |
| 23      | 3         | 2.27%   |
| 10      | 3         | 2.27%   |
| 18      | 2         | 1.52%   |
| 84      | 1         | 0.76%   |
| 46      | 1         | 0.76%   |
| 34      | 1         | 0.76%   |
| 31      | 1         | 0.76%   |
| 27      | 1         | 0.76%   |
| 20      | 1         | 0.76%   |
| 16      | 1         | 0.76%   |
| Unknown | 1         | 0.76%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 92        | 69.7%   |
| 201-300     | 23        | 17.42%  |
| 351-400     | 6         | 4.55%   |
| 501-600     | 4         | 3.03%   |
| 401-500     | 2         | 1.52%   |
| 801-900     | 1         | 0.76%   |
| 601-700     | 1         | 0.76%   |
| 1501-2000   | 1         | 0.76%   |
| 901-1000    | 1         | 0.76%   |
| Unknown     | 1         | 0.76%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 113       | 89.68%  |
| 16/10   | 9         | 7.14%   |
| 5/4     | 1         | 0.79%   |
| 3/2     | 1         | 0.79%   |
| 21/9    | 1         | 0.79%   |
| Unknown | 1         | 0.79%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 48        | 36.36%  |
| 81-90          | 44        | 33.33%  |
| 71-80          | 9         | 6.82%   |
| 51-60          | 6         | 4.55%   |
| 61-70          | 5         | 3.79%   |
| 41-50          | 3         | 2.27%   |
| 201-250        | 3         | 2.27%   |
| 141-150        | 3         | 2.27%   |
| 121-130        | 3         | 2.27%   |
| 351-500        | 2         | 1.52%   |
| More than 1000 | 1         | 0.76%   |
| 301-350        | 1         | 0.76%   |
| 151-200        | 1         | 0.76%   |
| 111-120        | 1         | 0.76%   |
| 501-1000       | 1         | 0.76%   |
| Unknown        | 1         | 0.76%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 54        | 40.91%  |
| 121-160 | 50        | 37.88%  |
| 51-100  | 16        | 12.12%  |
| 161-240 | 9         | 6.82%   |
| 1-50    | 2         | 1.52%   |
| Unknown | 1         | 0.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 114       | 86.36%  |
| 2     | 14        | 10.61%  |
| 0     | 3         | 2.27%   |
| 3     | 1         | 0.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 76        | 37.44%  |
| Realtek Semiconductor             | 57        | 28.08%  |
| Qualcomm Atheros                  | 33        | 16.26%  |
| Broadcom                          | 12        | 5.91%   |
| Hewlett-Packard                   | 5         | 2.46%   |
| Sierra Wireless                   | 3         | 1.48%   |
| MediaTek                          | 3         | 1.48%   |
| Huawei Technologies               | 3         | 1.48%   |
| T & A Mobile Phones               | 2         | 0.99%   |
| Ralink Technology                 | 2         | 0.99%   |
| Marvell Technology Group          | 2         | 0.99%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.49%   |
| Spreadtrum Communications         | 1         | 0.49%   |
| Ralink                            | 1         | 0.49%   |
| OPPO Electronics                  | 1         | 0.49%   |
| Ericsson Business Mobile Networks | 1         | 0.49%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 33        | 12.89%  |
| Intel Wireless 7260                                               | 16        | 6.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 5.86%   |
| Intel Ethernet Connection I218-LM                                 | 12        | 4.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 3.91%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 9         | 3.52%   |
| Intel Wireless 7265                                               | 7         | 2.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 2.34%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 6         | 2.34%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 1.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 1.95%   |
| Intel Wireless 8265 / 8275                                        | 4         | 1.56%   |
| Intel Wireless 8260                                               | 4         | 1.56%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 1.56%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 1.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 1.17%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.17%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 1.17%   |
| Intel Ethernet Connection I217-V                                  | 3         | 1.17%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.17%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 1.17%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 1.17%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 3         | 1.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 1.17%   |
| T & A Mobile Phones Alcatel 3X                                    | 2         | 0.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.78%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.78%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.78%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.78%   |
| Ralink MT7601U Wireless Adapter                                   | 2         | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.78%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.78%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.78%   |
| MediaTek NOA N2                                                   | 2         | 0.78%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 0.78%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.78%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 0.78%   |
| Intel Centrino Advanced-N 6235                                    | 2         | 0.78%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.78%   |
| Huawei E353/E3131                                                 | 2         | 0.78%   |
| HP lt4120 Snapdragon X5 LTE                                       | 2         | 0.78%   |
| HP lt4112 Gobi 4G Module Network Device                           | 2         | 0.78%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 2         | 0.78%   |
| ZTE WCDMA MSM ZTE MSM                                             | 1         | 0.39%   |
| Spreadtrum Unisoc Phone                                           | 1         | 0.39%   |
| Sierra Wireless EM7455                                            | 1         | 0.39%   |
| Sierra Wireless EM7355                                            | 1         | 0.39%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.39%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.39%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 0.39%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1         | 0.39%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.39%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 0.39%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.39%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.39%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.39%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 67        | 51.54%  |
| Qualcomm Atheros      | 28        | 21.54%  |
| Realtek Semiconductor | 16        | 12.31%  |
| Broadcom              | 11        | 8.46%   |
| Hewlett-Packard       | 3         | 2.31%   |
| Sierra Wireless       | 2         | 1.54%   |
| Ralink Technology     | 2         | 1.54%   |
| Ralink                | 1         | 0.77%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                                     | 16        | 12.31%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 6.92%   |
| Intel Wireless 7265                                                     | 7         | 5.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 4.62%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 4.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 3.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 3.85%   |
| Intel Wireless 8265 / 8275                                              | 4         | 3.08%   |
| Intel Wireless 8260                                                     | 4         | 3.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 2.31%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 2.31%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 2.31%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 2.31%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 2.31%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 2.31%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.54%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.54%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 1.54%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.54%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 1.54%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 1.54%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 1.54%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.54%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 1.54%   |
| HP lt4112 Gobi 4G Module Network Device                                 | 2         | 1.54%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 2         | 1.54%   |
| Sierra Wireless EM7455                                                  | 1         | 0.77%   |
| Sierra Wireless EM7355                                                  | 1         | 0.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.77%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.77%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.77%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 0.77%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.77%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.77%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.77%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 1         | 0.77%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.77%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.77%   |
| Intel Wireless 3165                                                     | 1         | 0.77%   |
| Intel Wireless 3160                                                     | 1         | 0.77%   |
| Intel WiFi Link 5100                                                    | 1         | 0.77%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 0.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 0.77%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 0.77%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                           | 1         | 0.77%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 0.77%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1         | 0.77%   |
| HP lt4111 LTE/EV-DO/HSPA+ Gobi 4G Module                                | 1         | 0.77%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                      | 1         | 0.77%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 1         | 0.77%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 1         | 0.77%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 52        | 42.28%  |
| Intel                      | 47        | 38.21%  |
| Qualcomm Atheros           | 8         | 6.5%    |
| MediaTek                   | 3         | 2.44%   |
| T & A Mobile Phones        | 2         | 1.63%   |
| Marvell Technology Group   | 2         | 1.63%   |
| Huawei Technologies        | 2         | 1.63%   |
| Hewlett-Packard            | 2         | 1.63%   |
| ZTE WCDMA Technologies MSM | 1         | 0.81%   |
| Spreadtrum Communications  | 1         | 0.81%   |
| Sierra Wireless            | 1         | 0.81%   |
| OPPO Electronics           | 1         | 0.81%   |
| Broadcom                   | 1         | 0.81%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 33        | 26.61%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 12.1%   |
| Intel Ethernet Connection I218-LM                                 | 12        | 9.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 8.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 4.03%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 3.23%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 3.23%   |
| Intel Ethernet Connection I217-V                                  | 3         | 2.42%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 2.42%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 2.42%   |
| T & A Mobile Phones Alcatel 3X                                    | 2         | 1.61%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.61%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 1.61%   |
| MediaTek NOA N2                                                   | 2         | 1.61%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.61%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.61%   |
| Huawei E353/E3131                                                 | 2         | 1.61%   |
| HP lt4120 Snapdragon X5 LTE                                       | 2         | 1.61%   |
| ZTE WCDMA MSM ZTE MSM                                             | 1         | 0.81%   |
| Spreadtrum Unisoc Phone                                           | 1         | 0.81%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.81%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.81%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.81%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.81%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.81%   |
| OPPO SDM665-IDP _SN:18689828                                      | 1         | 0.81%   |
| MediaTek WP7                                                      | 1         | 0.81%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.81%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.81%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.81%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.81%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.81%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.81%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 0.81%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 123       | 51.9%   |
| Ethernet | 112       | 47.26%  |
| Modem    | 2         | 0.84%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 112       | 68.71%  |
| Ethernet | 51        | 31.29%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 102       | 79.07%  |
| 1     | 19        | 14.73%  |
| 0     | 7         | 5.43%   |
| 3     | 1         | 0.78%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 126       | 97.67%  |
| Yes  | 3         | 2.33%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 55        | 56.7%   |
| Qualcomm Atheros Communications | 16        | 16.49%  |
| Realtek Semiconductor           | 6         | 6.19%   |
| Broadcom                        | 6         | 6.19%   |
| Lite-On Technology              | 3         | 3.09%   |
| IMC Networks                    | 3         | 3.09%   |
| Toshiba                         | 1         | 1.03%   |
| Realtek                         | 1         | 1.03%   |
| Ralink                          | 1         | 1.03%   |
| Hewlett-Packard                 | 1         | 1.03%   |
| Foxconn / Hon Hai               | 1         | 1.03%   |
| Dell                            | 1         | 1.03%   |
| Apple                           | 1         | 1.03%   |
| Alps Electric                   | 1         | 1.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 32        | 32.99%  |
| Qualcomm Atheros  Bluetooth Device             | 9         | 9.28%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 9         | 9.28%   |
| Intel AX201 Bluetooth                          | 5         | 5.15%   |
| Intel Centrino Bluetooth Wireless Transceiver  | 4         | 4.12%   |
| Realtek Bluetooth Radio                        | 3         | 3.09%   |
| Realtek  Bluetooth 4.2 Adapter                 | 2         | 2.06%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0          | 2         | 2.06%   |
| Qualcomm Atheros AR3011 Bluetooth              | 2         | 2.06%   |
| Intel AX200 Bluetooth                          | 2         | 2.06%   |
| IMC Networks Bluetooth Device                  | 2         | 2.06%   |
| Broadcom HP Portable SoftSailing               | 2         | 2.06%   |
| Broadcom HP Portable Bumble Bee                | 2         | 2.06%   |
| Toshiba Atheros AR3012 Bluetooth               | 1         | 1.03%   |
| Realtek 802.11n WLAN Adapter                   | 1         | 1.03%   |
| Realtek Bluetooth Radio                        | 1         | 1.03%   |
| Ralink RT3290 Bluetooth                        | 1         | 1.03%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0         | 1         | 1.03%   |
| Qualcomm Atheros AR9462 Bluetooth              | 1         | 1.03%   |
| Qualcomm Atheros AR3012 Bluetooth              | 1         | 1.03%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth     | 1         | 1.03%   |
| Lite-On Bluetooth Device                       | 1         | 1.03%   |
| Lite-On Atheros Bluetooth                      | 1         | 1.03%   |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 1         | 1.03%   |
| Intel Wireless-AC 3168 Bluetooth               | 1         | 1.03%   |
| Intel Bluetooth Device                         | 1         | 1.03%   |
| IMC Networks Bluetooth                         | 1         | 1.03%   |
| HP Broadcom 2070 Bluetooth Combo               | 1         | 1.03%   |
| Foxconn / Hon Hai Bluetooth Device             | 1         | 1.03%   |
| Dell DW375 Bluetooth Module                    | 1         | 1.03%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 1         | 1.03%   |
| Broadcom BCM2070 Bluetooth Device              | 1         | 1.03%   |
| Apple Bluetooth HCI                            | 1         | 1.03%   |
| Alps Electric UGNZG                            | 1         | 1.03%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 118       | 86.76%  |
| Nvidia                      | 6         | 4.41%   |
| AMD                         | 6         | 4.41%   |
| Turtle Beach                | 1         | 0.74%   |
| Texas Instruments           | 1         | 0.74%   |
| Realtek Semiconductor       | 1         | 0.74%   |
| GN Netcom                   | 1         | 0.74%   |
| FiiO Electronics Technology | 1         | 0.74%   |
| Apple                       | 1         | 0.74%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 21        | 12.5%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 14        | 8.33%   |
| Intel 8 Series HD Audio Controller                                                                | 14        | 8.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 13        | 7.74%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 6.55%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 9         | 5.36%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9         | 5.36%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8         | 4.76%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 3.57%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 3.57%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 2.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 2.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 2.38%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.79%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1.79%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 1.79%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 1.79%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 1.19%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.19%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.19%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.19%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 1.19%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.19%   |
| Turtle Beach PX11 Headset                                                                         | 1         | 0.6%    |
| Texas Instruments PCM2912A Audio Codec                                                            | 1         | 0.6%    |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.6%    |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.6%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.6%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.6%    |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.6%    |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.6%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.6%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.6%    |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 0.6%    |
| GN Netcom Jabra SPEAK 510                                                                         | 1         | 0.6%    |
| FiiO Electronics Technology K3                                                                    | 1         | 0.6%    |
| Apple Audio Device                                                                                | 1         | 0.6%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 0.6%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 0.6%    |
| AMD Navi 10 HDMI Audio                                                                            | 1         | 0.6%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 25        | 33.78%  |
| SK Hynix            | 15        | 20.27%  |
| Unknown             | 8         | 10.81%  |
| Micron Technology   | 8         | 10.81%  |
| Kingston            | 7         | 9.46%   |
| Ramaxel Technology  | 3         | 4.05%   |
| Crucial             | 3         | 4.05%   |
| A-DATA Technology   | 2         | 2.7%    |
| Nanya Technology    | 1         | 1.35%   |
| Elpida              | 1         | 1.35%   |
| Avant               | 1         | 1.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s         | 4         | 5.33%   |
| Unknown RAM Module 1GB Row Of Chips LPDDR4 4267MT/s           | 3         | 4%      |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                | 2         | 2.67%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 2         | 2.67%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s     | 2         | 2.67%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s         | 2         | 2.67%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s      | 2         | 2.67%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s         | 2         | 2.67%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s         | 2         | 2.67%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s         | 2         | 2.67%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s       | 2         | 2.67%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                     | 1         | 1.33%   |
| Unknown RAM Module 2GB SODIMM DDR 800MT/s                     | 1         | 1.33%   |
| Unknown RAM Module 2048MB SODIMM DDR2                         | 1         | 1.33%   |
| SK Hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 800MT/s      | 1         | 1.33%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 1.33%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s     | 1         | 1.33%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s        | 1         | 1.33%   |
| SK Hynix RAM HMT41GS6MFR8C-PB 8192MB SODIMM DDR3 1600MT/s     | 1         | 1.33%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 1.33%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s        | 1         | 1.33%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1333MT/s     | 1         | 1.33%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s     | 1         | 1.33%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s  | 1         | 1.33%   |
| SK Hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s        | 1         | 1.33%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2400MT/s                | 1         | 1.33%   |
| Samsung RAM Module 4GB Row Of Chips DDR4 2400MT/s             | 1         | 1.33%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s         | 1         | 1.33%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s         | 1         | 1.33%   |
| Samsung RAM M471B5674BH0-YH9 2GB Chip DDR3 1333MT/s           | 1         | 1.33%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s      | 1         | 1.33%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s         | 1         | 1.33%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s         | 1         | 1.33%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s         | 1         | 1.33%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s   | 1         | 1.33%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s      | 1         | 1.33%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s        | 1         | 1.33%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s         | 1         | 1.33%   |
| Samsung RAM M4 70T2864DZ3-CE6 1GB SODIMM DDR 667MT/s          | 1         | 1.33%   |
| Ramaxel RAM RMT3170KE68F9F1600 4GB SODIMM DDR3 1600MT/s       | 1         | 1.33%   |
| Ramaxel RAM RMT3170EF68F9W1600 4GB SODIMM DDR3 1600MT/s       | 1         | 1.33%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s       | 1         | 1.33%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s          | 1         | 1.33%   |
| Micron RAM Module 8192MB SODIMM DDR4 2667MT/s                 | 1         | 1.33%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s       | 1         | 1.33%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s          | 1         | 1.33%   |
| Micron RAM 4KTF25664HZ-1G6E2 2GB SODIMM DDR3 1600MT/s         | 1         | 1.33%   |
| Micron RAM 4KTF25664HZ-1G4E1 2048MB SODIMM DDR3 1333MT/s      | 1         | 1.33%   |
| Micron RAM 16KTF51264HZ-1G6M1 4096MB SODIMM DDR3 1600MT/s     | 1         | 1.33%   |
| Kingston RAM KN2M64-ETB 8GB SODIMM DDR3 1600MT/s              | 1         | 1.33%   |
| Kingston RAM HP26D4S9S8MHF-8 8GB SODIMM DDR4 2667MT/s         | 1         | 1.33%   |
| Kingston RAM ACR16D3LS1KFG/8G 8GB SODIMM DDR3 1600MT/s        | 1         | 1.33%   |
| Kingston RAM 9905744-066.A00G 32GB SODIMM DDR4 3200MT/s       | 1         | 1.33%   |
| Kingston RAM 9905474-011.A00LF 4096MB SODIMM DDR3 1600MT/s    | 1         | 1.33%   |
| Elpida RAM Module 4096MB SODIMM LPDDR3 1867MT/s               | 1         | 1.33%   |
| Crucial RAM CT8G4SFS8266.C8FE 8GB SODIMM DDR4 2667MT/s        | 1         | 1.33%   |
| Crucial RAM CT16G4SFD8213.C16FAD 16384MB SODIMM DDR4 2133MT/s | 1         | 1.33%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s       | 1         | 1.33%   |
| Avant RAM J642GU42J9266NF 16GB SODIMM DDR4 2667MT/s           | 1         | 1.33%   |
| A-DATA RAM Module 16384MB SODIMM DDR4 2667MT/s                | 1         | 1.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 33        | 51.56%  |
| DDR4   | 22        | 34.38%  |
| LPDDR4 | 3         | 4.69%   |
| DDR2   | 3         | 4.69%   |
| SDRAM  | 1         | 1.56%   |
| LPDDR3 | 1         | 1.56%   |
| DDR    | 1         | 1.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 56        | 87.5%   |
| Row Of Chips | 6         | 9.38%   |
| Chip         | 2         | 3.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 25        | 37.31%  |
| 8192  | 18        | 26.87%  |
| 2048  | 13        | 19.4%   |
| 16384 | 6         | 8.96%   |
| 1024  | 4         | 5.97%   |
| 32768 | 1         | 1.49%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 24        | 35.82%  |
| 2667    | 15        | 22.39%  |
| 1333    | 6         | 8.96%   |
| 1334    | 5         | 7.46%   |
| 4267    | 3         | 4.48%   |
| 2400    | 3         | 4.48%   |
| 2133    | 3         | 4.48%   |
| 800     | 2         | 2.99%   |
| 4199    | 1         | 1.49%   |
| 3266    | 1         | 1.49%   |
| 3200    | 1         | 1.49%   |
| 1867    | 1         | 1.49%   |
| 667     | 1         | 1.49%   |
| Unknown | 1         | 1.49%   |

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
| Chicony Electronics                    | 32        | 27.35%  |
| Cheng Uei Precision Industry (Foxlink) | 13        | 11.11%  |
| Acer                                   | 13        | 11.11%  |
| Realtek Semiconductor                  | 8         | 6.84%   |
| Sunplus Innovation Technology          | 7         | 5.98%   |
| Microdia                               | 6         | 5.13%   |
| Syntek                                 | 5         | 4.27%   |
| IMC Networks                           | 5         | 4.27%   |
| Lite-On Technology                     | 4         | 3.42%   |
| Silicon Motion                         | 3         | 2.56%   |
| Quanta                                 | 3         | 2.56%   |
| Suyin                                  | 2         | 1.71%   |
| Samsung Electronics                    | 2         | 1.71%   |
| Ricoh                                  | 2         | 1.71%   |
| Logitech                               | 2         | 1.71%   |
| Importek                               | 2         | 1.71%   |
| Apple                                  | 2         | 1.71%   |
| USB Camera                             | 1         | 0.85%   |
| Unknown                                | 1         | 0.85%   |
| LG Electronics                         | 1         | 0.85%   |
| DigiTech                               | 1         | 0.85%   |
| ALi                                    | 1         | 0.85%   |
| Alcor Micro                            | 1         | 0.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony HP HD Webcam                                                       | 6         | 5.08%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 5         | 4.24%   |
| Realtek Integrated_Webcam_HD                                               | 4         | 3.39%   |
| Chicony USB 2.0 Camera                                                     | 4         | 3.39%   |
| Chicony Integrated Camera                                                  | 4         | 3.39%   |
| Acer Integrated Camera                                                     | 4         | 3.39%   |
| Syntek Integrated Camera                                                   | 3         | 2.54%   |
| Microdia Integrated_Webcam_HD                                              | 3         | 2.54%   |
| Lite-On HP HD Webcam                                                       | 3         | 2.54%   |
| Chicony HD Webcam                                                          | 3         | 2.54%   |
| Syntek EasyCamera                                                          | 2         | 1.69%   |
| Sunplus Integrated_Webcam_HD                                               | 2         | 1.69%   |
| Sunplus HP HD Webcam [Fixed]                                               | 2         | 1.69%   |
| Realtek Integrated Webcam                                                  | 2         | 1.69%   |
| Importek HP Webcam-50                                                      | 2         | 1.69%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 2         | 1.69%   |
| Chicony HP HD Webcam [Fixed]                                               | 2         | 1.69%   |
| Chicony HP HD Camera                                                       | 2         | 1.69%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 2         | 1.69%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed]                | 2         | 1.69%   |
| Acer ThinkPad P50 Integrated Camera                                        | 2         | 1.69%   |
| USB Camera USB Camera                                                      | 1         | 0.85%   |
| Unknown USB Camera                                                         | 1         | 0.85%   |
| Suyin HP Webcam                                                            | 1         | 0.85%   |
| Suyin Asus Integrated Webcam                                               | 1         | 0.85%   |
| Sunplus HP Wide Vision HD                                                  | 1         | 0.85%   |
| Sunplus HP TrueVision HD Camera                                            | 1         | 0.85%   |
| Sunplus HP Truevision HD                                                   | 1         | 0.85%   |
| Silicon Motion WebCam SC-13HDL11939N                                       | 1         | 0.85%   |
| Silicon Motion WebCam SC-10HDD12636N                                       | 1         | 0.85%   |
| Silicon Motion 300k Pixel Camera                                           | 1         | 0.85%   |
| Samsung Galaxy A5 (MTP)                                                    | 1         | 0.85%   |
| Samsung Galaxy (debugging mode)                                            | 1         | 0.85%   |
| Ricoh Sony Vaio Integrated Webcam                                          | 1         | 0.85%   |
| Ricoh Laptop_Integrated_Webcam_FHD                                         | 1         | 0.85%   |
| Realtek HP Wide Vision HD Camera                                           | 1         | 0.85%   |
| Realtek HP Webcam                                                          | 1         | 0.85%   |
| Quanta VGA WebCam                                                          | 1         | 0.85%   |
| Quanta HP Wide Vision HD Camera                                            | 1         | 0.85%   |
| Quanta HP HD Camera                                                        | 1         | 0.85%   |
| Microdia Webcam Vitade AF                                                  | 1         | 0.85%   |
| Microdia Laptop_Integrated_Webcam_0.3M                                     | 1         | 0.85%   |
| Microdia HP Integrated Webcam                                              | 1         | 0.85%   |
| Logitech Webcam C270                                                       | 1         | 0.85%   |
| Logitech BRIO Ultra HD Webcam                                              | 1         | 0.85%   |
| Lite-On HP HD Camera                                                       | 1         | 0.85%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode)                      | 1         | 0.85%   |
| IMC Networks USB2.0 UVC HD Webcam                                          | 1         | 0.85%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 0.85%   |
| IMC Networks ov9734_azurewave_camera                                       | 1         | 0.85%   |
| DigiTech WebCam SCB-1110M                                                  | 1         | 0.85%   |
| Chicony USB 5M WebCam                                                      | 1         | 0.85%   |
| Chicony TOSHIBA Web Camera - MP                                            | 1         | 0.85%   |
| Chicony TOSHIBA Web Camera - HD                                            | 1         | 0.85%   |
| Chicony Lenovo EasyCamera                                                  | 1         | 0.85%   |
| Chicony Integrated HP HD Webcam                                            | 1         | 0.85%   |
| Chicony Integrated Camera (1280x720@30)                                    | 1         | 0.85%   |
| Chicony HP Wide Vision HD Camera                                           | 1         | 0.85%   |
| Chicony HP Wide Vision HD                                                  | 1         | 0.85%   |
| Chicony HP Webcam [2 MP Macro]                                             | 1         | 0.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 27        | 69.23%  |
| Synaptics                  | 8         | 20.51%  |
| Shenzhen Goodix Technology | 4         | 10.26%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 11        | 28.21%  |
| Validity Sensors VFS491                                                    | 6         | 15.38%  |
| Synaptics WBDI Device                                                      | 3         | 7.69%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 7.69%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 5.13%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 5.13%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 5.13%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 5.13%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2.56%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 2.56%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 2.56%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 2.56%   |
| Synaptics  WBDI                                                            | 1         | 2.56%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 2.56%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 2.56%   |
| Shenzhen Goodix  Fingerprint Device                                        | 1         | 2.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 50%     |
| Alcor Micro | 2         | 25%     |
| Upek        | 1         | 12.5%   |
| O2 Micro    | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 25%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 25%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 12.5%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 12.5%   |
| Broadcom 5880                                                                | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 78        | 59.54%  |
| 1     | 43        | 32.82%  |
| 2     | 10        | 7.63%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 39        | 63.93%  |
| Chipcard                 | 7         | 11.48%  |
| Graphics card            | 4         | 6.56%   |
| Net/wireless             | 3         | 4.92%   |
| Storage                  | 2         | 3.28%   |
| Camera                   | 2         | 3.28%   |
| Sound                    | 1         | 1.64%   |
| Net/ethernet             | 1         | 1.64%   |
| Communication controller | 1         | 1.64%   |
| Bluetooth                | 1         | 1.64%   |

