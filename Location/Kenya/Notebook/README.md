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

Total: 203

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Unknown                     | [1e1768ebfa](https://linux-hardware.org/?probe=1e1768ebfa) | Jul 24, 2022 |
| HP            | Unknown                     | [aa2aa159c9](https://linux-hardware.org/?probe=aa2aa159c9) | Jul 14, 2022 |
| HP            | 15                          | [91c97ad34a](https://linux-hardware.org/?probe=91c97ad34a) | Jun 24, 2022 |
| HP            | ProBook 440 G5              | [2969400046](https://linux-hardware.org/?probe=2969400046) | Jun 20, 2022 |
| HP            | EliteBook 840 G3            | [92acbd4c3f](https://linux-hardware.org/?probe=92acbd4c3f) | May 31, 2022 |
| HP            | ZHAN 66 Pro A 14 G3         | [9d27d641ca](https://linux-hardware.org/?probe=9d27d641ca) | May 25, 2022 |
| HP            | ZHAN 66 Pro A 14 G3         | [db3577b92d](https://linux-hardware.org/?probe=db3577b92d) | May 25, 2022 |
| Notebook      | P65xHP                      | [b1205b8ca1](https://linux-hardware.org/?probe=b1205b8ca1) | May 10, 2022 |
| HP            | EliteBook 840 G3            | [9d0ee854e4](https://linux-hardware.org/?probe=9d0ee854e4) | May 10, 2022 |
| Lenovo        | Z50-75 80EC                 | [691a4c0ca5](https://linux-hardware.org/?probe=691a4c0ca5) | May 08, 2022 |
| Acer          | Aspire 5920G                | [b2ffc81ed6](https://linux-hardware.org/?probe=b2ffc81ed6) | May 07, 2022 |
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
| Lenovo        | ThinkPad T440p 20AWS5D20... | [6cf30d2192](https://linux-hardware.org/?probe=6cf30d2192) | Apr 26, 2020 |
| HP            | ProBook 6470b               | [a6132519cf](https://linux-hardware.org/?probe=a6132519cf) | Apr 21, 2020 |
| HP            | ProBook 6470b               | [255652dcf4](https://linux-hardware.org/?probe=255652dcf4) | Apr 21, 2020 |
| Lenovo        | V110-15ISK 80TL             | [2dec0ef690](https://linux-hardware.org/?probe=2dec0ef690) | Apr 18, 2020 |
| HP            | 15 Notebook PC              | [120e9af4f0](https://linux-hardware.org/?probe=120e9af4f0) | Apr 11, 2020 |
| HP            | EliteBook Folio 1040 G1     | [04ee092498](https://linux-hardware.org/?probe=04ee092498) | Apr 08, 2020 |
| HP            | Pavilion Laptop 13-an0xx... | [ecef1f0fcb](https://linux-hardware.org/?probe=ecef1f0fcb) | Apr 07, 2020 |
| ASUSTek       | X540SAA                     | [f5e7614710](https://linux-hardware.org/?probe=f5e7614710) | Mar 14, 2020 |
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
| HP            | OMEN by Laptop              | [c4f5abc453](https://linux-hardware.org/?probe=c4f5abc453) | Jul 12, 2019 |
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
| Sony          | VGN-NS295J                  | [9d2ccc3bc1](https://linux-hardware.org/?probe=9d2ccc3bc1) | Dec 20, 2017 |
| Sony          | VGN-NS295J                  | [08cfe3b021](https://linux-hardware.org/?probe=08cfe3b021) | Dec 20, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 33        | 22.15%  |
| Ubuntu 18.04                 | 15        | 10.07%  |
| Zorin 16                     | 6         | 4.03%   |
| Manjaro                      | 5         | 3.36%   |
| Zorin 15                     | 4         | 2.68%   |
| Ubuntu 20.10                 | 4         | 2.68%   |
| Ubuntu 19.04                 | 4         | 2.68%   |
| Pop!_OS 20.04                | 4         | 2.68%   |
| OpenMandriva 4.2             | 4         | 2.68%   |
| Ubuntu 21.04                 | 3         | 2.01%   |
| Q4OS 3                       | 3         | 2.01%   |
| Arch                         | 3         | 2.01%   |
| Ubuntu 21.10                 | 2         | 1.34%   |
| Ubuntu 19.10                 | 2         | 1.34%   |
| Linux Mint 20.3              | 2         | 1.34%   |
| Linux Mint 20.2              | 2         | 1.34%   |
| Linux Mint 19                | 2         | 1.34%   |
| Fedora 35                    | 2         | 1.34%   |
| Fedora 32                    | 2         | 1.34%   |
| Endless 3.9.4                | 2         | 1.34%   |
| Endless 3.9.2                | 2         | 1.34%   |
| Endless 3.9.1                | 2         | 1.34%   |
| Debian 11                    | 2         | 1.34%   |
| Xubuntu 20.04                | 1         | 0.67%   |
| Ubuntu MATE 21.04            | 1         | 0.67%   |
| Ubuntu MATE 20.04            | 1         | 0.67%   |
| Ubuntu Budgie 20.04          | 1         | 0.67%   |
| Ubuntu 22.04                 | 1         | 0.67%   |
| Ubuntu 16.04                 | 1         | 0.67%   |
| ROSA R11                     | 1         | 0.67%   |
| ROSA R10                     | 1         | 0.67%   |
| Pop!_OS 21.04                | 1         | 0.67%   |
| Pop!_OS 20.10                | 1         | 0.67%   |
| Parrot 5.0                   | 1         | 0.67%   |
| Parrot 4.9                   | 1         | 0.67%   |
| Parrot 4.8                   | 1         | 0.67%   |
| Parrot 4.7                   | 1         | 0.67%   |
| Parrot 4.11                  | 1         | 0.67%   |
| openSUSE Tumbleweed-XXXXXXXX | 1         | 0.67%   |
| OpenMandriva 4.3             | 1         | 0.67%   |
| Manjaro 20.1                 | 1         | 0.67%   |
| LMDE 5                       | 1         | 0.67%   |
| KDE neon 20.04               | 1         | 0.67%   |
| Kali 2021.3                  | 1         | 0.67%   |
| Kali 2020.1                  | 1         | 0.67%   |
| Garuda Linux Soaring         | 1         | 0.67%   |
| Fedora 36                    | 1         | 0.67%   |
| Fedora 33                    | 1         | 0.67%   |
| Fedora 31                    | 1         | 0.67%   |
| Fedora 29                    | 1         | 0.67%   |
| Endless 3.9.5                | 1         | 0.67%   |
| Endless 3.9.3                | 1         | 0.67%   |
| Endless 3.8.7                | 1         | 0.67%   |
| Endless 3.7.8                | 1         | 0.67%   |
| Endless 3.7.7                | 1         | 0.67%   |
| Elementary 6.1               | 1         | 0.67%   |
| Elementary 5.1.7             | 1         | 0.67%   |
| Debian 10                    | 1         | 0.67%   |
| BlackPanther 18.1            | 1         | 0.67%   |
| Arch V19.04.4                | 1         | 0.67%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 60        | 42.86%  |
| Zorin         | 10        | 7.14%   |
| Fedora        | 8         | 5.71%   |
| Endless       | 8         | 5.71%   |
| Pop!_OS       | 6         | 4.29%   |
| Manjaro       | 6         | 4.29%   |
| Linux Mint    | 6         | 4.29%   |
| OpenMandriva  | 5         | 3.57%   |
| Arch          | 5         | 3.57%   |
| Parrot        | 4         | 2.86%   |
| Q4OS          | 3         | 2.14%   |
| Debian        | 3         | 2.14%   |
| Ubuntu MATE   | 2         | 1.43%   |
| ROSA          | 2         | 1.43%   |
| Kali          | 2         | 1.43%   |
| Elementary    | 2         | 1.43%   |
| Xubuntu       | 1         | 0.71%   |
| Ubuntu Budgie | 1         | 0.71%   |
| openSUSE      | 1         | 0.71%   |
| LMDE          | 1         | 0.71%   |
| KDE neon      | 1         | 0.71%   |
| Garuda Linux  | 1         | 0.71%   |
| BlackPanther  | 1         | 0.71%   |
| antiX         | 1         | 0.71%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.8.0-14-generic         | 6         | 3.7%    |
| 5.11.0-38-generic        | 4         | 2.47%   |
| 5.10.14-desktop-1omv4002 | 4         | 2.47%   |
| 5.4.0-58-generic         | 3         | 1.85%   |
| 5.4.0-52-generic         | 3         | 1.85%   |
| 5.4.0-45-generic         | 3         | 1.85%   |
| 5.4.0-42-generic         | 3         | 1.85%   |
| 4.19.0-17-amd64          | 3         | 1.85%   |
| 5.8.0-59-generic         | 2         | 1.23%   |
| 5.8.0-43-generic         | 2         | 1.23%   |
| 5.4.0-67-generic         | 2         | 1.23%   |
| 5.4.0-65-generic         | 2         | 1.23%   |
| 5.4.0-54-generic         | 2         | 1.23%   |
| 5.4.0-48-generic         | 2         | 1.23%   |
| 5.4.0-47-generic         | 2         | 1.23%   |
| 5.4.0-37-generic         | 2         | 1.23%   |
| 5.3.0-28-generic         | 2         | 1.23%   |
| 5.15.0-41-generic        | 2         | 1.23%   |
| 5.13.19-2-MANJARO        | 2         | 1.23%   |
| 5.13.0-27-generic        | 2         | 1.23%   |
| 5.11.0-37-generic        | 2         | 1.23%   |
| 5.11.0-34-generic        | 2         | 1.23%   |
| 5.9.14-arch1-1           | 1         | 0.62%   |
| 5.9.13-200.fc33.x86_64   | 1         | 0.62%   |
| 5.8.4-200.fc32.x86_64    | 1         | 0.62%   |
| 5.8.12-arch1-1           | 1         | 0.62%   |
| 5.8.0-63-generic         | 1         | 0.62%   |
| 5.8.0-55-generic         | 1         | 0.62%   |
| 5.8.0-51-generic         | 1         | 0.62%   |
| 5.8.0-50-generic         | 1         | 0.62%   |
| 5.8.0-48-generic         | 1         | 0.62%   |
| 5.8.0-44-generic         | 1         | 0.62%   |
| 5.8.0-41-generic         | 1         | 0.62%   |
| 5.8.0-29-generic         | 1         | 0.62%   |
| 5.8.0-26-generic         | 1         | 0.62%   |
| 5.8.0-25-generic         | 1         | 0.62%   |
| 5.7.17-2-MANJARO         | 1         | 0.62%   |
| 5.6.7-200.fc31.x86_64    | 1         | 0.62%   |
| 5.6.5-050605-generic     | 1         | 0.62%   |
| 5.6.11-300.fc32.x86_64   | 1         | 0.62%   |
| 5.5.0-1parrot1-amd64     | 1         | 0.62%   |
| 5.4.0-77-generic         | 1         | 0.62%   |
| 5.4.0-7634-generic       | 1         | 0.62%   |
| 5.4.0-7629-generic       | 1         | 0.62%   |
| 5.4.0-7626-generic       | 1         | 0.62%   |
| 5.4.0-7625-generic       | 1         | 0.62%   |
| 5.4.0-74-generic         | 1         | 0.62%   |
| 5.4.0-70-generic         | 1         | 0.62%   |
| 5.4.0-62-generic         | 1         | 0.62%   |
| 5.4.0-4parrot1-amd64     | 1         | 0.62%   |
| 5.4.0-39-generic         | 1         | 0.62%   |
| 5.4.0-38-generic         | 1         | 0.62%   |
| 5.4.0-33-generic         | 1         | 0.62%   |
| 5.4.0-29-generic         | 1         | 0.62%   |
| 5.4.0-26-generic         | 1         | 0.62%   |
| 5.4.0-121-generic        | 1         | 0.62%   |
| 5.3.0-kali1-amd64        | 1         | 0.62%   |
| 5.3.0-62-generic         | 1         | 0.62%   |
| 5.3.0-59-generic         | 1         | 0.62%   |
| 5.3.0-46-generic         | 1         | 0.62%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 35        | 22.88%  |
| 5.8.0   | 18        | 11.76%  |
| 5.11.0  | 13        | 8.5%    |
| 4.15.0  | 11        | 7.19%   |
| 5.3.0   | 7         | 4.58%   |
| 5.13.0  | 7         | 4.58%   |
| 5.0.0   | 7         | 4.58%   |
| 5.10.14 | 4         | 2.61%   |
| 5.10.0  | 4         | 2.61%   |
| 4.19.0  | 4         | 2.61%   |
| 5.15.0  | 3         | 1.96%   |
| 5.17.5  | 2         | 1.31%   |
| 5.16.7  | 2         | 1.31%   |
| 5.13.19 | 2         | 1.31%   |
| 4.18.0  | 2         | 1.31%   |
| 5.9.14  | 1         | 0.65%   |
| 5.9.13  | 1         | 0.65%   |
| 5.8.4   | 1         | 0.65%   |
| 5.8.12  | 1         | 0.65%   |
| 5.7.17  | 1         | 0.65%   |
| 5.6.7   | 1         | 0.65%   |
| 5.6.5   | 1         | 0.65%   |
| 5.6.11  | 1         | 0.65%   |
| 5.5.0   | 1         | 0.65%   |
| 5.2.5   | 1         | 0.65%   |
| 5.2.0   | 1         | 0.65%   |
| 5.17.6  | 1         | 0.65%   |
| 5.17.4  | 1         | 0.65%   |
| 5.16.16 | 1         | 0.65%   |
| 5.16.14 | 1         | 0.65%   |
| 5.16.0  | 1         | 0.65%   |
| 5.15.13 | 1         | 0.65%   |
| 5.14.6  | 1         | 0.65%   |
| 5.14.10 | 1         | 0.65%   |
| 5.14.0  | 1         | 0.65%   |
| 5.11.6  | 1         | 0.65%   |
| 5.10.70 | 1         | 0.65%   |
| 5.10.42 | 1         | 0.65%   |
| 5.10.16 | 1         | 0.65%   |
| 5.1.6   | 1         | 0.65%   |
| 5.0.10  | 1         | 0.65%   |
| 4.9.60  | 1         | 0.65%   |
| 4.9.0   | 1         | 0.65%   |
| 4.19.1  | 1         | 0.65%   |
| 4.18.16 | 1         | 0.65%   |
| 4.16.13 | 1         | 0.65%   |
| 4.13.0  | 1         | 0.65%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 35        | 23.18%  |
| 5.8     | 20        | 13.25%  |
| 5.11    | 14        | 9.27%   |
| 5.10    | 11        | 7.28%   |
| 4.15    | 11        | 7.28%   |
| 5.13    | 9         | 5.96%   |
| 5.0     | 8         | 5.3%    |
| 5.3     | 7         | 4.64%   |
| 4.19    | 5         | 3.31%   |
| 5.16    | 4         | 2.65%   |
| 5.15    | 4         | 2.65%   |
| 5.6     | 3         | 1.99%   |
| 5.17    | 3         | 1.99%   |
| 5.14    | 3         | 1.99%   |
| 4.18    | 3         | 1.99%   |
| 5.9     | 2         | 1.32%   |
| 5.2     | 2         | 1.32%   |
| 4.9     | 2         | 1.32%   |
| 5.7     | 1         | 0.66%   |
| 5.5     | 1         | 0.66%   |
| 5.1     | 1         | 0.66%   |
| 4.16    | 1         | 0.66%   |
| 4.13    | 1         | 0.66%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 135       | 97.83%  |
| i686   | 3         | 2.17%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 85        | 59.86%  |
| Unknown    | 19        | 13.38%  |
| KDE5       | 13        | 9.15%   |
| X-Cinnamon | 6         | 4.23%   |
| XFCE       | 5         | 3.52%   |
| MATE       | 5         | 3.52%   |
| KDE        | 4         | 2.82%   |
| Pantheon   | 2         | 1.41%   |
| KDE4       | 2         | 1.41%   |
| Cinnamon   | 1         | 0.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 110       | 78.57%  |
| Wayland | 21        | 15%     |
| Unknown | 9         | 6.43%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 86        | 60.56%  |
| GDM     | 25        | 17.61%  |
| SDDM    | 13        | 9.15%   |
| GDM3    | 7         | 4.93%   |
| TDM     | 5         | 3.52%   |
| LightDM | 4         | 2.82%   |
| KDM     | 2         | 1.41%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 98        | 70%     |
| Unknown | 23        | 16.43%  |
| en_GB   | 17        | 12.14%  |
| C       | 2         | 1.43%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 80        | 56.74%  |
| EFI  | 61        | 43.26%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 119       | 86.23%  |
| Overlay | 9         | 6.52%   |
| Btrfs   | 8         | 5.8%    |
| Unknown | 2         | 1.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 87        | 62.14%  |
| GPT     | 36        | 25.71%  |
| MBR     | 17        | 12.14%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 122       | 87.77%  |
| Yes       | 17        | 12.23%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 96        | 69.57%  |
| Yes       | 42        | 30.43%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 58        | 42.03%  |
| Lenovo                      | 25        | 18.12%  |
| Dell                        | 16        | 11.59%  |
| ASUSTek Computer            | 7         | 5.07%   |
| Toshiba                     | 6         | 4.35%   |
| Acer                        | 4         | 2.9%    |
| Samsung Electronics         | 3         | 2.17%   |
| Chuwi                       | 2         | 1.45%   |
| Apple                       | 2         | 1.45%   |
| TECNO                       | 1         | 0.72%   |
| Sony                        | 1         | 0.72%   |
| SLIMBOOK                    | 1         | 0.72%   |
| Panasonic                   | 1         | 0.72%   |
| Notebook                    | 1         | 0.72%   |
| Insyde                      | 1         | 0.72%   |
| I-Life Digital Technologies | 1         | 0.72%   |
| HUAWEI                      | 1         | 0.72%   |
| Getac                       | 1         | 0.72%   |
| EVOC                        | 1         | 0.72%   |
| EUROCOM                     | 1         | 0.72%   |
| Endless                     | 1         | 0.72%   |
| Eluktronics                 | 1         | 0.72%   |
| Clevo                       | 1         | 0.72%   |
| Unknown                     | 1         | 0.72%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| HP EliteBook Folio 9480m                | 3         | 2.17%   |
| HP EliteBook Folio 9470m                | 3         | 2.17%   |
| HP EliteBook 840 G3                     | 3         | 2.17%   |
| HP EliteBook 840 G1                     | 3         | 2.17%   |
| Dell XPS 13 9310                        | 3         | 2.17%   |
| Unknown                                 | 3         | 2.17%   |
| Toshiba Satellite C660                  | 2         | 1.45%   |
| HP ProBook 640 G1                       | 2         | 1.45%   |
| HP ProBook 440 G5                       | 2         | 1.45%   |
| HP Pavilion Laptop 15-cs3xxx            | 2         | 1.45%   |
| HP EliteBook 840 G2                     | 2         | 1.45%   |
| HP Compaq Mini 110c-1100                | 2         | 1.45%   |
| HP 15 Notebook PC                       | 2         | 1.45%   |
| Dell Inspiron 5767                      | 2         | 1.45%   |
| Toshiba Satellite L50-B                 | 1         | 0.72%   |
| Toshiba R84SAU2                         | 1         | 0.72%   |
| Toshiba dynabook Satellite B554/M       | 1         | 0.72%   |
| Toshiba dynabook R731/E                 | 1         | 0.72%   |
| TECNO WinPad 2                          | 1         | 0.72%   |
| Sony VGN-NS295J                         | 1         | 0.72%   |
| SLIMBOOK PROX14-AMD                     | 1         | 0.72%   |
| Samsung RC410/RC510/RC710               | 1         | 0.72%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV | 1         | 0.72%   |
| Samsung 300E4C/300E5C/300E7C            | 1         | 0.72%   |
| Panasonic CF-SX2JDQZF5                  | 1         | 0.72%   |
| Notebook P65xHP                         | 1         | 0.72%   |
| Lenovo Z50-75 80EC                      | 1         | 0.72%   |
| Lenovo V330-14IKB 81B0                  | 1         | 0.72%   |
| Lenovo V310-15ISK 80SY                  | 1         | 0.72%   |
| Lenovo V14-IGL 82C2                     | 1         | 0.72%   |
| Lenovo V130-14IKB 81HQ                  | 1         | 0.72%   |
| Lenovo V110-15ISK 80TL                  | 1         | 0.72%   |
| Lenovo ThinkPad X250 20CLA21MJP         | 1         | 0.72%   |
| Lenovo ThinkPad X240 20AMS4J900         | 1         | 0.72%   |
| Lenovo ThinkPad X240 20AL00CQAU         | 1         | 0.72%   |
| Lenovo ThinkPad X131e 33672T5           | 1         | 0.72%   |
| Lenovo ThinkPad X1 Carbon 3460AE4       | 1         | 0.72%   |
| Lenovo ThinkPad T490s 20NYS8J900        | 1         | 0.72%   |
| Lenovo ThinkPad T470s W10DG 20JTS16607  | 1         | 0.72%   |
| Lenovo ThinkPad T470s 20HGS6PF09        | 1         | 0.72%   |
| Lenovo ThinkPad T460s 20FAS3QC00        | 1         | 0.72%   |
| Lenovo ThinkPad T460 20FMS1DH01         | 1         | 0.72%   |
| Lenovo ThinkPad T440p 20AWS5D200        | 1         | 0.72%   |
| Lenovo ThinkPad P52s 20LB0021US         | 1         | 0.72%   |
| Lenovo ThinkPad L480 20LTS1RE0Y         | 1         | 0.72%   |
| Lenovo ThinkPad E520 1143ADU            | 1         | 0.72%   |
| Lenovo IdeaPad 330S-14IKB 81F4          | 1         | 0.72%   |
| Lenovo IdeaPad 330-15IKB 81DE           | 1         | 0.72%   |
| Lenovo IdeaPad 320S-14IKB 80X4          | 1         | 0.72%   |
| Lenovo IdeaPad 3 15IIL05 81WE           | 1         | 0.72%   |
| Lenovo IdeaPad 100S-11IBY 80R2          | 1         | 0.72%   |
| Insyde i101c                            | 1         | 0.72%   |
| I-Life Digital ZED AIR PRO              | 1         | 0.72%   |
| HUAWEI NBLK-WAX9X                       | 1         | 0.72%   |
| HP ZHAN 66 Pro A 14 G3                  | 1         | 0.72%   |
| HP ZBook 15 G2                          | 1         | 0.72%   |
| HP ProBook 6560b                        | 1         | 0.72%   |
| HP ProBook 6470b                        | 1         | 0.72%   |
| HP ProBook 4540s                        | 1         | 0.72%   |
| HP ProBook 450 G1                       | 1         | 0.72%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| HP EliteBook           | 22        | 15.94%  |
| Lenovo ThinkPad        | 14        | 10.14%  |
| HP ProBook             | 11        | 7.97%   |
| Dell Latitude          | 7         | 5.07%   |
| HP Pavilion            | 6         | 4.35%   |
| Dell Inspiron          | 6         | 4.35%   |
| Lenovo IdeaPad         | 5         | 3.62%   |
| Acer Aspire            | 4         | 2.9%    |
| Toshiba Satellite      | 3         | 2.17%   |
| HP Laptop              | 3         | 2.17%   |
| HP ENVY                | 3         | 2.17%   |
| HP 15                  | 3         | 2.17%   |
| Dell XPS               | 3         | 2.17%   |
| Unknown                | 3         | 2.17%   |
| Toshiba dynabook       | 2         | 1.45%   |
| HP Compaq              | 2         | 1.45%   |
| Toshiba R84SAU2        | 1         | 0.72%   |
| TECNO WinPad           | 1         | 0.72%   |
| Sony VGN-NS295J        | 1         | 0.72%   |
| SLIMBOOK PROX14-AMD    | 1         | 0.72%   |
| Samsung RC410          | 1         | 0.72%   |
| Samsung 300E5EV        | 1         | 0.72%   |
| Samsung 300E4C         | 1         | 0.72%   |
| Panasonic CF-SX2JDQZF5 | 1         | 0.72%   |
| Notebook P65xHP        | 1         | 0.72%   |
| Lenovo Z50-75          | 1         | 0.72%   |
| Lenovo V330-14IKB      | 1         | 0.72%   |
| Lenovo V310-15ISK      | 1         | 0.72%   |
| Lenovo V14-IGL         | 1         | 0.72%   |
| Lenovo V130-14IKB      | 1         | 0.72%   |
| Lenovo V110-15ISK      | 1         | 0.72%   |
| Insyde i101c           | 1         | 0.72%   |
| I-Life Digital ZED     | 1         | 0.72%   |
| HUAWEI NBLK-WAX9X      | 1         | 0.72%   |
| HP ZHAN                | 1         | 0.72%   |
| HP ZBook               | 1         | 0.72%   |
| HP Presario            | 1         | 0.72%   |
| HP OMEN                | 1         | 0.72%   |
| HP Notebook            | 1         | 0.72%   |
| HP 630                 | 1         | 0.72%   |
| Getac V110             | 1         | 0.72%   |
| EVOC P7xxTM1-(G)       | 1         | 0.72%   |
| EUROCOM Q6             | 1         | 0.72%   |
| Endless EF20EA         | 1         | 0.72%   |
| Eluktronics MAG-15u    | 1         | 0.72%   |
| Clevo P7xxDM2-(G)      | 1         | 0.72%   |
| Chuwi HeroBook         | 1         | 0.72%   |
| Chuwi GemiBook         | 1         | 0.72%   |
| ASUS Zephyrus          | 1         | 0.72%   |
| ASUS X551MA            | 1         | 0.72%   |
| ASUS X540SAA           | 1         | 0.72%   |
| ASUS X540NA            | 1         | 0.72%   |
| ASUS X202EV            | 1         | 0.72%   |
| ASUS VivoBook          | 1         | 0.72%   |
| ASUS UX305CA           | 1         | 0.72%   |
| Apple MacBookPro3      | 1         | 0.72%   |
| Apple MacBookPro16     | 1         | 0.72%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 17        | 12.32%  |
| 2018 | 15        | 10.87%  |
| 2016 | 15        | 10.87%  |
| 2015 | 13        | 9.42%   |
| 2019 | 12        | 8.7%    |
| 2014 | 11        | 7.97%   |
| 2012 | 11        | 7.97%   |
| 2017 | 10        | 7.25%   |
| 2011 | 10        | 7.25%   |
| 2020 | 9         | 6.52%   |
| 2010 | 7         | 5.07%   |
| 2009 | 2         | 1.45%   |
| 2007 | 2         | 1.45%   |
| 2006 | 2         | 1.45%   |
| 2021 | 1         | 0.72%   |
| 2008 | 1         | 0.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 138       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 128       | 91.43%  |
| Enabled  | 12        | 8.57%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 138       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 46        | 33.09%  |
| 4.01-8.0    | 38        | 27.34%  |
| 8.01-16.0   | 19        | 13.67%  |
| 16.01-24.0  | 14        | 10.07%  |
| 1.01-2.0    | 12        | 8.63%   |
| 32.01-64.0  | 4         | 2.88%   |
| 64.01-256.0 | 3         | 2.16%   |
| 24.01-32.0  | 1         | 0.72%   |
| 2.01-3.0    | 1         | 0.72%   |
| 0.51-1.0    | 1         | 0.72%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 49        | 31.41%  |
| 2.01-3.0  | 44        | 28.21%  |
| 3.01-4.0  | 25        | 16.03%  |
| 4.01-8.0  | 23        | 14.74%  |
| 0.51-1.0  | 13        | 8.33%   |
| 8.01-16.0 | 2         | 1.28%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 121       | 85.21%  |
| 2      | 17        | 11.97%  |
| 10     | 1         | 0.7%    |
| 8      | 1         | 0.7%    |
| 4      | 1         | 0.7%    |
| 3      | 1         | 0.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 82        | 59.42%  |
| Yes       | 56        | 40.58%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 121       | 87.68%  |
| No        | 17        | 12.32%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 132       | 95.65%  |
| No        | 6         | 4.35%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 104       | 74.29%  |
| No        | 36        | 25.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Kenya   | 138       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City     | Notebooks | Percent |
|----------|-----------|---------|
| Nairobi  | 127       | 89.44%  |
| Mombasa  | 3         | 2.11%   |
| Nakuru   | 2         | 1.41%   |
| Kiambu   | 2         | 1.41%   |
| Eldoret  | 2         | 1.41%   |
| Wote     | 1         | 0.7%    |
| Nyeri    | 1         | 0.7%    |
| Narok    | 1         | 0.7%    |
| Maralal  | 1         | 0.7%    |
| Machakos | 1         | 0.7%    |
| Kisii    | 1         | 0.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 42        | 56     | 26.92%  |
| Toshiba             | 22        | 27     | 14.1%   |
| WDC                 | 18        | 24     | 11.54%  |
| Samsung Electronics | 15        | 24     | 9.62%   |
| Unknown             | 11        | 15     | 7.05%   |
| HGST                | 9         | 16     | 5.77%   |
| Hitachi             | 8         | 9      | 5.13%   |
| SanDisk             | 6         | 6      | 3.85%   |
| Crucial             | 6         | 8      | 3.85%   |
| Micron Technology   | 4         | 4      | 2.56%   |
| MARSHAL             | 3         | 3      | 1.92%   |
| Kingston            | 2         | 4      | 1.28%   |
| SK hynix            | 1         | 1      | 0.64%   |
| Plextor             | 1         | 1      | 0.64%   |
| Netac               | 1         | 1      | 0.64%   |
| Intel               | 1         | 1      | 0.64%   |
| HUAWEI              | 1         | 1      | 0.64%   |
| Golden              | 1         | 1      | 0.64%   |
| Eluktro             | 1         | 1      | 0.64%   |
| CARLSTEIN           | 1         | 2      | 0.64%   |
| Apple               | 1         | 1      | 0.64%   |
| A-DATA Technology   | 1         | 1      | 0.64%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 8         | 4.91%   |
| Seagate ST500LT012-9WS142 500GB      | 5         | 3.07%   |
| HGST HTS725050A7E630 500GB           | 5         | 3.07%   |
| Toshiba MQ04ABF100 1TB               | 4         | 2.45%   |
| Samsung SSD 960 EVO 1TB              | 4         | 2.45%   |
| WDC PC SN730 NVMe 512GB              | 3         | 1.84%   |
| Unknown MMC Card  64GB               | 3         | 1.84%   |
| Unknown MMC Card  32GB               | 3         | 1.84%   |
| Toshiba MQ01ABF050 500GB             | 3         | 1.84%   |
| Toshiba MQ01ABD100 1TB               | 3         | 1.84%   |
| Seagate ST9500325AS 500GB            | 3         | 1.84%   |
| Seagate ST500LT012-1DG142 500GB      | 3         | 1.84%   |
| Seagate ST500LM021-1KJ152 500GB      | 3         | 1.84%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 3         | 1.84%   |
| Crucial CT2050MX300SSD1 2TB          | 3         | 1.84%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 2         | 1.23%   |
| WDC WD2500BEKT-75PVMT0 250GB         | 2         | 1.23%   |
| Unknown NCard  32GB                  | 2         | 1.23%   |
| Seagate ST500VT000-1DK142 500GB      | 2         | 1.23%   |
| Seagate ST250LT003-9YG14C 250GB      | 2         | 1.23%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 2         | 1.23%   |
| Samsung NVMe SSD Drive 512GB         | 2         | 1.23%   |
| Samsung NVMe SSD Drive 256GB         | 2         | 1.23%   |
| Hitachi HTS545032B9A300 320GB        | 2         | 1.23%   |
| HGST HTS541010A9E680 1TB             | 2         | 1.23%   |
| WDC WDS100T1B0A-00H9H0 1TB SSD       | 1         | 0.61%   |
| WDC WD5000LPVX-75V0TT0 500GB         | 1         | 0.61%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.61%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 0.61%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 1         | 0.61%   |
| WDC WD5000LPCX-22VHAT1 500GB         | 1         | 0.61%   |
| WDC WD5000BPVT-60HXZT3 500GB         | 1         | 0.61%   |
| WDC WD3200BUCT-63TWBY0 320GB         | 1         | 0.61%   |
| WDC WD10SPZX-60Z10T0 1TB             | 1         | 0.61%   |
| WDC WD10JPVX-60JC3T0 1TB             | 1         | 0.61%   |
| WDC WD10JPCX-24UE4T0 1TB             | 1         | 0.61%   |
| Unknown MMC Card  4GB                | 1         | 0.61%   |
| Unknown MMC Card  2GB                | 1         | 0.61%   |
| Unknown EB2MW  32GB                  | 1         | 0.61%   |
| Unknown ASTC  32GB                   | 1         | 0.61%   |
| Unknown 68CHP  16GB                  | 1         | 0.61%   |
| Toshiba THNSNJ256G8NY 256GB SSD      | 1         | 0.61%   |
| Toshiba NVMe SSD Drive 240GB         | 1         | 0.61%   |
| Toshiba MQ01ACF050 500GB             | 1         | 0.61%   |
| Toshiba MQ01ACF032 320GB             | 1         | 0.61%   |
| Toshiba MQ01ABF032 320GB             | 1         | 0.61%   |
| Toshiba MQ01ABD050V 500GB            | 1         | 0.61%   |
| Toshiba MK5076GSX 500GB              | 1         | 0.61%   |
| Toshiba MK3263GSX 320GB              | 1         | 0.61%   |
| Toshiba MK3252GSX 320GB              | 1         | 0.61%   |
| Toshiba MK1234GSX 120GB              | 1         | 0.61%   |
| Toshiba KXG6AZNV512G 512GB           | 1         | 0.61%   |
| Toshiba KXG60ZNV512G 512GB           | 1         | 0.61%   |
| SK hynix NVMe SSD Drive 256GB        | 1         | 0.61%   |
| Seagate ST9750420AS 752GB            | 1         | 0.61%   |
| Seagate ST9160314AS 160GB            | 1         | 0.61%   |
| Seagate ST750LM000-1EJ16G-SSHD 752GB | 1         | 0.61%   |
| Seagate ST500LX025-1U717D 500GB      | 1         | 0.61%   |
| Seagate ST500LM030-1RK17D 500GB      | 1         | 0.61%   |
| Seagate ST500LM000-1EJ162 500GB      | 1         | 0.61%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 42        | 56     | 44.68%  |
| Toshiba | 18        | 23     | 19.15%  |
| WDC     | 14        | 20     | 14.89%  |
| HGST    | 9         | 16     | 9.57%   |
| Hitachi | 8         | 9      | 8.51%   |
| MARSHAL | 3         | 3      | 3.19%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 6         | 6      | 21.43%  |
| Crucial             | 6         | 8      | 21.43%  |
| Samsung Electronics | 5         | 8      | 17.86%  |
| Micron Technology   | 2         | 2      | 7.14%   |
| Kingston            | 2         | 4      | 7.14%   |
| WDC                 | 1         | 1      | 3.57%   |
| Toshiba             | 1         | 1      | 3.57%   |
| Plextor             | 1         | 1      | 3.57%   |
| Netac               | 1         | 1      | 3.57%   |
| Golden              | 1         | 1      | 3.57%   |
| Eluktro             | 1         | 1      | 3.57%   |
| A-DATA Technology   | 1         | 1      | 3.57%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 91        | 127    | 58.71%  |
| SSD     | 28        | 35     | 18.06%  |
| NVMe    | 23        | 27     | 14.84%  |
| MMC     | 11        | 15     | 7.1%    |
| Unknown | 2         | 3      | 1.29%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 113       | 162    | 75.33%  |
| NVMe | 23        | 27     | 15.33%  |
| MMC  | 11        | 15     | 7.33%   |
| SAS  | 3         | 3      | 2%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 79        | 103    | 67.52%  |
| 0.51-1.0   | 33        | 44     | 28.21%  |
| 1.01-2.0   | 4         | 11     | 3.42%   |
| 3.01-4.0   | 1         | 4      | 0.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 43        | 30.07%  |
| 101-250        | 29        | 20.28%  |
| 501-1000       | 19        | 13.29%  |
| 51-100         | 16        | 11.19%  |
| 1-20           | 8         | 5.59%   |
| 21-50          | 7         | 4.9%    |
| 1001-2000      | 7         | 4.9%    |
| Unknown        | 6         | 4.2%    |
| 2001-3000      | 5         | 3.5%    |
| More than 3000 | 3         | 2.1%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 42        | 28.19%  |
| 21-50          | 27        | 18.12%  |
| 101-250        | 26        | 17.45%  |
| 51-100         | 18        | 12.08%  |
| 251-500        | 16        | 10.74%  |
| 501-1000       | 6         | 4.03%   |
| Unknown        | 6         | 4.03%   |
| 1001-2000      | 4         | 2.68%   |
| More than 3000 | 3         | 2.01%   |
| 2001-3000      | 1         | 0.67%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD2500BEKT-75PVMT0 250GB    | 2         | 2      | 10.53%  |
| Seagate ST500LT012-1DG142 500GB | 2         | 2      | 10.53%  |
| WDC WD10SPZX-60Z10T0 1TB        | 1         | 1      | 5.26%   |
| Toshiba MQ01ABF050 500GB        | 1         | 1      | 5.26%   |
| Toshiba MQ01ABD100 1TB          | 1         | 1      | 5.26%   |
| Toshiba MQ01ABD050V 500GB       | 1         | 1      | 5.26%   |
| Toshiba MK3263GSX 320GB         | 1         | 1      | 5.26%   |
| Toshiba MK3252GSX 320GB         | 1         | 1      | 5.26%   |
| Seagate ST9500325AS 500GB       | 1         | 1      | 5.26%   |
| Seagate ST1000LM035-1RK172 1TB  | 1         | 1      | 5.26%   |
| MARSHAL MAL2750SA-T54 752GB     | 1         | 1      | 5.26%   |
| Hitachi HTS545032B9A300 320GB   | 1         | 1      | 5.26%   |
| Hitachi HTS542525K9SA00 250GB   | 1         | 1      | 5.26%   |
| HGST HTS725050A7E630 500GB      | 1         | 1      | 5.26%   |
| HGST HTS541515A9E630 1TB        | 1         | 2      | 5.26%   |
| HGST HTS541010A9E680 1TB        | 1         | 2      | 5.26%   |
| Crucial CT2050MX300SSD1 2TB     | 1         | 2      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 5         | 5      | 27.78%  |
| Seagate | 4         | 4      | 22.22%  |
| WDC     | 3         | 3      | 16.67%  |
| Hitachi | 2         | 2      | 11.11%  |
| HGST    | 2         | 5      | 11.11%  |
| MARSHAL | 1         | 1      | 5.56%   |
| Crucial | 1         | 2      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 5         | 5      | 29.41%  |
| Seagate | 4         | 4      | 23.53%  |
| WDC     | 3         | 3      | 17.65%  |
| Hitachi | 2         | 2      | 11.76%  |
| HGST    | 2         | 5      | 11.76%  |
| MARSHAL | 1         | 1      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 17        | 20     | 94.44%  |
| SSD  | 1         | 2      | 5.56%   |

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
| Detected | 89        | 128    | 64.03%  |
| Works    | 33        | 57     | 23.74%  |
| Malfunc  | 17        | 22     | 12.23%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 120       | 81.08%  |
| Samsung Electronics          | 12        | 8.11%   |
| AMD                          | 5         | 3.38%   |
| Toshiba America Info Systems | 3         | 2.03%   |
| SanDisk                      | 3         | 2.03%   |
| Micron Technology            | 2         | 1.35%   |
| SK hynix                     | 1         | 0.68%   |
| ASMedia Technology           | 1         | 0.68%   |
| Apple                        | 1         | 0.68%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 21        | 13.64%  |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 14        | 9.09%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 11        | 7.14%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 10        | 6.49%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 9         | 5.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 9         | 5.84%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 6         | 3.9%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 6         | 3.9%    |
| AMD FCH SATA Controller [AHCI mode]                                                    | 5         | 3.25%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 4         | 2.6%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 4         | 2.6%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 4         | 2.6%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 4         | 2.6%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 3         | 1.95%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 3         | 1.95%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 1.95%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 3         | 1.95%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 2         | 1.3%    |
| Samsung NVMe SSD Controller 980                                                        | 2         | 1.3%    |
| Micron Non-Volatile memory controller                                                  | 2         | 1.3%    |
| Intel Volume Management Device NVMe RAID Controller                                    | 2         | 1.3%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 2         | 1.3%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 2         | 1.3%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 2         | 1.3%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 1.3%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 2         | 1.3%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 1         | 0.65%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 1         | 0.65%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 1         | 0.65%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 0.65%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 1         | 0.65%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 1         | 0.65%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 0.65%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 0.65%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 1         | 0.65%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 1         | 0.65%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 0.65%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 0.65%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 1         | 0.65%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 1         | 0.65%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                       | 1         | 0.65%   |
| ASMedia 106x SATA/RAID Controller                                                      | 1         | 0.65%   |
| Apple ANS2 NVMe Controller                                                             | 1         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 108       | 72%     |
| NVMe | 23        | 15.33%  |
| RAID | 12        | 8%      |
| IDE  | 7         | 4.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 132       | 95.65%  |
| AMD    | 6         | 4.35%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz           | 5         | 3.62%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 5         | 3.62%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 4         | 2.9%    |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 2.17%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 3         | 2.17%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 3         | 2.17%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 3         | 2.17%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 3         | 2.17%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 3         | 2.17%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 3         | 2.17%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 3         | 2.17%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 3         | 2.17%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 1.45%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 1.45%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 2         | 1.45%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.45%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 2         | 1.45%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.45%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 2         | 1.45%   |
| Intel Core i5-3437U CPU @ 1.90GHz           | 2         | 1.45%   |
| Intel Core i5-3427U CPU @ 1.80GHz           | 2         | 1.45%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 1.45%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 2         | 1.45%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 1.45%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 1.45%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 2         | 1.45%   |
| Intel Core i3-4100M CPU @ 2.50GHz           | 2         | 1.45%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 2         | 1.45%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 2         | 1.45%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 2         | 1.45%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 2         | 1.45%   |
| Intel Celeron CPU 1007U @ 1.50GHz           | 2         | 1.45%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 2         | 1.45%   |
| Intel Atom CPU N270 @ 1.60GHz               | 2         | 1.45%   |
| Intel Pentium CPU N3510 @ 1.99GHz           | 1         | 0.72%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 0.72%   |
| Intel Pentium CPU 2117U @ 1.80GHz           | 1         | 0.72%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz            | 1         | 0.72%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1         | 0.72%   |
| Intel Core i9-9880H CPU @ 2.30GHz           | 1         | 0.72%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 0.72%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 0.72%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1         | 0.72%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 0.72%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.72%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 0.72%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 0.72%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 0.72%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 0.72%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz          | 1         | 0.72%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 0.72%   |
| Intel Core i7-4600M CPU @ 2.90GHz           | 1         | 0.72%   |
| Intel Core i7-2620M CPU @ 2.70GHz           | 1         | 0.72%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 1         | 0.72%   |
| Intel Core i5-8350U CPU @ 1.70GHz           | 1         | 0.72%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1         | 0.72%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 1         | 0.72%   |
| Intel Core i5-4310U CPU @ 2.00GHz           | 1         | 0.72%   |
| Intel Core i5-3317U CPU @ 1.70GHz           | 1         | 0.72%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 0.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 42        | 30.43%  |
| Intel Core i7           | 36        | 26.09%  |
| Intel Celeron           | 15        | 10.87%  |
| Intel Core i3           | 13        | 9.42%   |
| Intel Atom              | 8         | 5.8%    |
| Intel Pentium           | 5         | 3.62%   |
| Other                   | 3         | 2.17%   |
| Intel Core 2 Duo        | 3         | 2.17%   |
| Intel Pentium Dual-Core | 2         | 1.45%   |
| Intel Core i9           | 2         | 1.45%   |
| Intel Core 2            | 2         | 1.45%   |
| AMD Ryzen 7             | 2         | 1.45%   |
| AMD A10                 | 2         | 1.45%   |
| Intel Core m3           | 1         | 0.72%   |
| AMD Ryzen 5             | 1         | 0.72%   |
| AMD FX                  | 1         | 0.72%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 90        | 65.22%  |
| 4       | 39        | 28.26%  |
| 8       | 4         | 2.9%    |
| 6       | 2         | 1.45%   |
| 1       | 2         | 1.45%   |
| Unknown | 1         | 0.72%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 138       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 104       | 75.36%  |
| 1       | 33        | 23.91%  |
| Unknown | 1         | 0.72%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 136       | 98.55%  |
| 32-bit         | 2         | 1.45%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 29        | 20.42%  |
| 0x306a9    | 12        | 8.45%   |
| 0x206a7    | 12        | 8.45%   |
| 0x40651    | 11        | 7.75%   |
| 0x306c3    | 9         | 6.34%   |
| 0x806ea    | 6         | 4.23%   |
| 0x306d4    | 6         | 4.23%   |
| 0x406e3    | 5         | 3.52%   |
| 0x30678    | 5         | 3.52%   |
| 0x806ec    | 4         | 2.82%   |
| 0x806e9    | 3         | 2.11%   |
| 0x806c1    | 3         | 2.11%   |
| 0x406c4    | 3         | 2.11%   |
| 0x20655    | 3         | 2.11%   |
| 0x1067a    | 3         | 2.11%   |
| 0x906ea    | 2         | 1.41%   |
| 0x906e9    | 2         | 1.41%   |
| 0x806eb    | 2         | 1.41%   |
| 0x706e5    | 2         | 1.41%   |
| 0x706a8    | 2         | 1.41%   |
| 0x706a1    | 2         | 1.41%   |
| 0x406c3    | 2         | 1.41%   |
| 0x106c2    | 2         | 1.41%   |
| 0x906ec    | 1         | 0.7%    |
| 0x6fd      | 1         | 0.7%    |
| 0x6fa      | 1         | 0.7%    |
| 0x6f6      | 1         | 0.7%    |
| 0x6f2      | 1         | 0.7%    |
| 0x506e3    | 1         | 0.7%    |
| 0x506c9    | 1         | 0.7%    |
| 0x30673    | 1         | 0.7%    |
| 0x08600106 | 1         | 0.7%    |
| 0x08600103 | 1         | 0.7%    |
| 0x08108109 | 1         | 0.7%    |
| 0x0600611a | 1         | 0.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 30        | 21.74%  |
| Haswell       | 23        | 16.67%  |
| Silvermont    | 14        | 10.14%  |
| IvyBridge     | 13        | 9.42%   |
| SandyBridge   | 12        | 8.7%    |
| Skylake       | 10        | 7.25%   |
| Broadwell     | 6         | 4.35%   |
| Westmere      | 4         | 2.9%    |
| Goldmont plus | 4         | 2.9%    |
| Core          | 4         | 2.9%    |
| TigerLake     | 3         | 2.17%   |
| Penryn        | 3         | 2.17%   |
| IceLake       | 3         | 2.17%   |
| Zen 2         | 2         | 1.45%   |
| Excavator     | 2         | 1.45%   |
| Bonnell       | 2         | 1.45%   |
| Zen+          | 1         | 0.72%   |
| Steamroller   | 1         | 0.72%   |
| Goldmont      | 1         | 0.72%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 121       | 78.57%  |
| AMD    | 17        | 11.04%  |
| Nvidia | 16        | 10.39%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 14        | 8.86%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 13        | 8.23%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 6.33%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 5.7%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 8         | 5.06%   |
| Intel UHD Graphics 620                                                                   | 7         | 4.43%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 4.43%   |
| Intel HD Graphics 620                                                                    | 7         | 4.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 4.43%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 4.43%   |
| Intel HD Graphics 5500                                                                   | 6         | 3.8%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 3.8%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 2.53%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 2.53%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.9%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 1.9%    |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 1.27%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 2         | 1.27%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 1.27%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.27%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 1.27%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 1.27%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 1.27%   |
| AMD Renoir                                                                               | 2         | 1.27%   |
| Nvidia TU104BM [GeForce RTX 2080 Mobile]                                                 | 1         | 0.63%   |
| Nvidia GT218M [GeForce 315M]                                                             | 1         | 0.63%   |
| Nvidia GP108GLM [Quadro P500 Mobile]                                                     | 1         | 0.63%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.63%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                                  | 1         | 0.63%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.63%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 0.63%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.63%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.63%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 1         | 0.63%   |
| Nvidia G84M [GeForce 8600M GT]                                                           | 1         | 0.63%   |
| Nvidia G72M [GeForce Go 7400]                                                            | 1         | 0.63%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 0.63%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 1         | 0.63%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 0.63%   |
| Intel HD Graphics 630                                                                    | 1         | 0.63%   |
| Intel HD Graphics 530                                                                    | 1         | 0.63%   |
| Intel HD Graphics 520                                                                    | 1         | 0.63%   |
| Intel HD Graphics 515                                                                    | 1         | 0.63%   |
| Intel HD Graphics 500                                                                    | 1         | 0.63%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 0.63%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 1         | 0.63%   |
| AMD RV620/M82 [Mobility Radeon HD 3410/3430]                                             | 1         | 0.63%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 0.63%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 1         | 0.63%   |
| AMD Kaveri [Radeon R6/R7 Graphics]                                                       | 1         | 0.63%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 1         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 105       | 76.09%  |
| Intel + Nvidia | 10        | 7.25%   |
| 1 x AMD        | 10        | 7.25%   |
| 1 x Nvidia     | 6         | 4.35%   |
| Intel + AMD    | 6         | 4.35%   |
| 2 x AMD        | 1         | 0.72%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 132       | 94.29%  |
| Proprietary | 7         | 5%      |
| Unknown     | 1         | 0.71%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 112       | 79.43%  |
| 1.01-2.0   | 9         | 6.38%   |
| 0.01-0.5   | 9         | 6.38%   |
| 3.01-4.0   | 5         | 3.55%   |
| 7.01-8.0   | 4         | 2.84%   |
| 0.51-1.0   | 2         | 1.42%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 33        | 23.08%  |
| Chimei Innolux          | 27        | 18.88%  |
| BOE                     | 23        | 16.08%  |
| LG Display              | 21        | 14.69%  |
| Samsung Electronics     | 10        | 6.99%   |
| Hewlett-Packard         | 6         | 4.2%    |
| Sharp                   | 3         | 2.1%    |
| Chi Mei Optoelectronics | 3         | 2.1%    |
| Apple                   | 3         | 2.1%    |
| LG Philips              | 2         | 1.4%    |
| Lenovo                  | 2         | 1.4%    |
| KDC                     | 2         | 1.4%    |
| InfoVision              | 2         | 1.4%    |
| HannStar                | 2         | 1.4%    |
| Unknown (XXX)           | 1         | 0.7%    |
| Eizo                    | 1         | 0.7%    |
| CVT                     | 1         | 0.7%    |
| Acer                    | 1         | 0.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                  | 3         | 2.1%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 2.1%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 3         | 2.1%    |
| Chimei Innolux LCD Monitor CMN14A3 1600x900 309x174mm 14.0-inch          | 3         | 2.1%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 1.4%    |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 2         | 1.4%    |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch         | 2         | 1.4%    |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x173mm 13.9-inch          | 2         | 1.4%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x194mm 15.5-inch | 2         | 1.4%    |
| BOE LCD Monitor BOE0780 1920x1080 344x194mm 15.5-inch                    | 2         | 1.4%    |
| BOE LCD Monitor BOE0695 1920x1080 380x210mm 17.1-inch                    | 2         | 1.4%    |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 1.4%    |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch            | 2         | 1.4%    |
| AU Optronics LCD Monitor AUO223E 1600x900 309x174mm 14.0-inch            | 2         | 1.4%    |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 2         | 1.4%    |
| Unknown (XXX) LEDTV XXX0001 1366x768 575x323mm 26.0-inch                 | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch     | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch     | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC3642 1366x768 309x174mm 14.0-inch     | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC3051 1366x768 344x194mm 15.5-inch     | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SDC4942 1366x768 309x174mm 14.0-inch     | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SAM7017 3840x2160 950x540mm 43.0-inch    | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch     | 1         | 0.7%    |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch              | 1         | 0.7%    |
| LG Philips LCD Monitor LPL0132 1280x800 304x190mm 14.1-inch              | 1         | 0.7%    |
| LG Display LCD Monitor LGD0619 1920x1080 309x174mm 14.0-inch             | 1         | 0.7%    |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch             | 1         | 0.7%    |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch             | 1         | 0.7%    |
| LG Display LCD Monitor LGD0532 1920x1080 344x194mm 15.5-inch             | 1         | 0.7%    |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch              | 1         | 0.7%    |
| LG Display LCD Monitor LGD04FD 1366x768 344x194mm 15.5-inch              | 1         | 0.7%    |
| LG Display LCD Monitor LGD0493 1366x768 344x194mm 15.5-inch              | 1         | 0.7%    |
| LG Display LCD Monitor LGD048B 1366x768 309x174mm 14.0-inch              | 1         | 0.7%    |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 1         | 0.7%    |
| LG Display LCD Monitor LGD045E 1366x768 309x174mm 14.0-inch              | 1         | 0.7%    |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch              | 1         | 0.7%    |
| LG Display LCD Monitor LGD03CD 1366x768 277x156mm 12.5-inch              | 1         | 0.7%    |
| LG Display LCD Monitor LGD03B8 1366x768 310x174mm 14.0-inch              | 1         | 0.7%    |
| LG Display LCD Monitor LGD03AD 1366x768 309x174mm 14.0-inch              | 1         | 0.7%    |
| LG Display LCD Monitor LGD0386 1366x768 309x174mm 14.0-inch              | 1         | 0.7%    |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch              | 1         | 0.7%    |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch              | 1         | 0.7%    |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch              | 1         | 0.7%    |
| Lenovo LEN S24e-10 LEN61CA 1920x1080 527x296mm 23.8-inch                 | 1         | 0.7%    |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 1         | 0.7%    |
| KDC LCD Monitor KDC05F1 1366x768 344x193mm 15.5-inch                     | 1         | 0.7%    |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                     | 1         | 0.7%    |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch             | 1         | 0.7%    |
| InfoVision LCD Monitor IVO04E3 1366x768 277x156mm 12.5-inch              | 1         | 0.7%    |
| Hewlett-Packard Z23i HWP3090 1920x1080 509x286mm 23.0-inch               | 1         | 0.7%    |
| Hewlett-Packard W2072a HWP3000 1600x900 443x249mm 20.0-inch              | 1         | 0.7%    |
| Hewlett-Packard V197 HWP3348 1366x768 410x230mm 18.5-inch                | 1         | 0.7%    |
| Hewlett-Packard LCD Monitor E232                                         | 1         | 0.7%    |
| Hewlett-Packard 27f HPN354A 1920x1080 598x336mm 27.0-inch                | 1         | 0.7%    |
| Hewlett-Packard 2311x HWP293A 1920x1080 510x287mm 23.0-inch              | 1         | 0.7%    |
| Eizo L557 ENC1690 1280x1024 337x270mm 17.0-inch                          | 1         | 0.7%    |
| CVT CVTE TV CVT0003 1920x1080 1000x610mm 46.1-inch                       | 1         | 0.7%    |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch         | 1         | 0.7%    |
| Chimei Innolux LCD Monitor CMN15FF 1366x768 344x193mm 15.5-inch          | 1         | 0.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 72        | 52.17%  |
| 1920x1080 (FHD)   | 39        | 28.26%  |
| 1600x900 (HD+)    | 11        | 7.97%   |
| 1920x1200 (WUXGA) | 3         | 2.17%   |
| 1280x800 (WXGA)   | 3         | 2.17%   |
| 1024x600          | 2         | 1.45%   |
| 3840x2160 (4K)    | 1         | 0.72%   |
| 3072x1920         | 1         | 0.72%   |
| 2560x1080         | 1         | 0.72%   |
| 2160x1440         | 1         | 0.72%   |
| 1440x900 (WXGA+)  | 1         | 0.72%   |
| 1360x768          | 1         | 0.72%   |
| 1280x1024 (SXGA)  | 1         | 0.72%   |
| Unknown           | 1         | 0.72%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 50        | 35.21%  |
| 13      | 32        | 22.54%  |
| 14      | 28        | 19.72%  |
| 11      | 6         | 4.23%   |
| 12      | 5         | 3.52%   |
| 17      | 4         | 2.82%   |
| 23      | 3         | 2.11%   |
| 10      | 3         | 2.11%   |
| 18      | 2         | 1.41%   |
| 84      | 1         | 0.7%    |
| 46      | 1         | 0.7%    |
| 34      | 1         | 0.7%    |
| 31      | 1         | 0.7%    |
| 27      | 1         | 0.7%    |
| 26      | 1         | 0.7%    |
| 20      | 1         | 0.7%    |
| 16      | 1         | 0.7%    |
| Unknown | 1         | 0.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 101       | 71.13%  |
| 201-300     | 23        | 16.2%   |
| 351-400     | 6         | 4.23%   |
| 501-600     | 5         | 3.52%   |
| 401-500     | 2         | 1.41%   |
| 801-900     | 1         | 0.7%    |
| 601-700     | 1         | 0.7%    |
| 1501-2000   | 1         | 0.7%    |
| 901-1000    | 1         | 0.7%    |
| Unknown     | 1         | 0.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 120       | 88.89%  |
| 16/10   | 11        | 8.15%   |
| 5/4     | 1         | 0.74%   |
| 3/2     | 1         | 0.74%   |
| 21/9    | 1         | 0.74%   |
| Unknown | 1         | 0.74%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 51        | 35.92%  |
| 101-110        | 50        | 35.21%  |
| 71-80          | 9         | 6.34%   |
| 51-60          | 6         | 4.23%   |
| 61-70          | 5         | 3.52%   |
| 41-50          | 3         | 2.11%   |
| 201-250        | 3         | 2.11%   |
| 141-150        | 3         | 2.11%   |
| 121-130        | 3         | 2.11%   |
| 351-500        | 2         | 1.41%   |
| More than 1000 | 1         | 0.7%    |
| 301-350        | 1         | 0.7%    |
| 251-300        | 1         | 0.7%    |
| 151-200        | 1         | 0.7%    |
| 111-120        | 1         | 0.7%    |
| 501-1000       | 1         | 0.7%    |
| Unknown        | 1         | 0.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 59        | 41.55%  |
| 121-160 | 53        | 37.32%  |
| 51-100  | 18        | 12.68%  |
| 161-240 | 9         | 6.34%   |
| 1-50    | 2         | 1.41%   |
| Unknown | 1         | 0.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 122       | 86.52%  |
| 2     | 15        | 10.64%  |
| 0     | 3         | 2.13%   |
| 3     | 1         | 0.71%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 82        | 37.61%  |
| Realtek Semiconductor             | 61        | 27.98%  |
| Qualcomm Atheros                  | 34        | 15.6%   |
| Broadcom                          | 14        | 6.42%   |
| Hewlett-Packard                   | 5         | 2.29%   |
| Sierra Wireless                   | 3         | 1.38%   |
| MediaTek                          | 3         | 1.38%   |
| Huawei Technologies               | 3         | 1.38%   |
| T & A Mobile Phones               | 2         | 0.92%   |
| Ralink Technology                 | 2         | 0.92%   |
| Ralink                            | 2         | 0.92%   |
| Marvell Technology Group          | 2         | 0.92%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.46%   |
| Spreadtrum Communications         | 1         | 0.46%   |
| Samsung Electronics               | 1         | 0.46%   |
| OPPO Electronics                  | 1         | 0.46%   |
| Ericsson Business Mobile Networks | 1         | 0.46%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 36        | 13.09%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 16        | 5.82%   |
| Intel Wireless 7260                                               | 16        | 5.82%   |
| Intel Ethernet Connection I218-LM                                 | 12        | 4.36%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 4%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 9         | 3.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 2.55%   |
| Intel Wireless 8260                                               | 6         | 2.18%   |
| Intel Wireless 7265                                               | 6         | 2.18%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 2.18%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 2.18%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 6         | 2.18%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 1.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.82%   |
| Intel Wireless 8265 / 8275                                        | 5         | 1.82%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 1.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 1.09%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.09%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 1.09%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 1.09%   |
| Intel Ethernet Connection I217-V                                  | 3         | 1.09%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.09%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 1.09%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 1.09%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 3         | 1.09%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 1.09%   |
| T & A Mobile Phones TCL 30                                        | 2         | 0.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.73%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.73%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.73%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.73%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.73%   |
| Ralink MT7601U Wireless Adapter                                   | 2         | 0.73%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.73%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.73%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.73%   |
| MediaTek moto e(6) plus                                           | 2         | 0.73%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.73%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 0.73%   |
| Intel Centrino Advanced-N 6235                                    | 2         | 0.73%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.73%   |
| Huawei E353/E3131                                                 | 2         | 0.73%   |
| HP lt4120 Snapdragon X5 LTE                                       | 2         | 0.73%   |
| HP lt4112 Gobi 4G Module Network Device                           | 2         | 0.73%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 2         | 0.73%   |
| ZTE WCDMA MSM ZTE MSM                                             | 1         | 0.36%   |
| Spreadtrum Unisoc Phone                                           | 1         | 0.36%   |
| Sierra Wireless EM7455                                            | 1         | 0.36%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.36%   |
| Sierra Wireless EM7305 Modem                                      | 1         | 0.36%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.36%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.36%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 0.36%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1         | 0.36%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.36%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 0.36%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1         | 0.36%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.36%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 73        | 52.14%  |
| Qualcomm Atheros      | 29        | 20.71%  |
| Realtek Semiconductor | 16        | 11.43%  |
| Broadcom              | 12        | 8.57%   |
| Sierra Wireless       | 3         | 2.14%   |
| Hewlett-Packard       | 3         | 2.14%   |
| Ralink Technology     | 2         | 1.43%   |
| Ralink                | 2         | 1.43%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                                     | 16        | 11.43%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 6.43%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 5%      |
| Intel Wireless 8260                                                     | 6         | 4.29%   |
| Intel Wireless 7265                                                     | 6         | 4.29%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 4.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 4.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 3.57%   |
| Intel Wireless 8265 / 8275                                              | 5         | 3.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 2.14%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 2.14%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 2.14%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 2.14%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 2.14%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 2.14%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 2.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.43%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.43%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.43%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 1.43%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.43%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 1.43%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 1.43%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.43%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 1.43%   |
| HP lt4112 Gobi 4G Module Network Device                                 | 2         | 1.43%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 2         | 1.43%   |
| Sierra Wireless EM7455                                                  | 1         | 0.71%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.71%   |
| Sierra Wireless EM7305 Modem                                            | 1         | 0.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.71%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.71%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.71%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 0.71%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.71%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.71%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                  | 1         | 0.71%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.71%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.71%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 1         | 0.71%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.71%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.71%   |
| Intel Wireless 3165                                                     | 1         | 0.71%   |
| Intel Wireless 3160                                                     | 1         | 0.71%   |
| Intel WiFi Link 5100                                                    | 1         | 0.71%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 0.71%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.71%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 0.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 0.71%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 0.71%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                           | 1         | 0.71%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 0.71%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1         | 0.71%   |
| HP lt4111 LTE/EV-DO/HSPA+ Gobi 4G Module                                | 1         | 0.71%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                      | 1         | 0.71%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 1         | 0.71%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 1         | 0.71%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 1         | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 56        | 42.42%  |
| Intel                      | 50        | 37.88%  |
| Qualcomm Atheros           | 8         | 6.06%   |
| MediaTek                   | 3         | 2.27%   |
| Broadcom                   | 3         | 2.27%   |
| T & A Mobile Phones        | 2         | 1.52%   |
| Marvell Technology Group   | 2         | 1.52%   |
| Huawei Technologies        | 2         | 1.52%   |
| Hewlett-Packard            | 2         | 1.52%   |
| ZTE WCDMA Technologies MSM | 1         | 0.76%   |
| Spreadtrum Communications  | 1         | 0.76%   |
| Samsung Electronics        | 1         | 0.76%   |
| OPPO Electronics           | 1         | 0.76%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 36        | 27.07%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 16        | 12.03%  |
| Intel Ethernet Connection I218-LM                                 | 12        | 9.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 8.27%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 4.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 3.76%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 3.01%   |
| Intel Ethernet Connection I217-V                                  | 3         | 2.26%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 2.26%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 2.26%   |
| T & A Mobile Phones TCL 30                                        | 2         | 1.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.5%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 1.5%    |
| MediaTek moto e(6) plus                                           | 2         | 1.5%    |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.5%    |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.5%    |
| Huawei E353/E3131                                                 | 2         | 1.5%    |
| HP lt4120 Snapdragon X5 LTE                                       | 2         | 1.5%    |
| ZTE WCDMA MSM ZTE MSM                                             | 1         | 0.75%   |
| Spreadtrum Unisoc Phone                                           | 1         | 0.75%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.75%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.75%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.75%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.75%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.75%   |
| OPPO SDM720G-IDP _SN:B922E265                                     | 1         | 0.75%   |
| MediaTek RMX3085                                                  | 1         | 0.75%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.75%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.75%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.75%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.75%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.75%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.75%   |
| Broadcom NetXtreme BCM5753M Gigabit Ethernet PCI Express          | 1         | 0.75%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 0.75%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.75%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 132       | 51.76%  |
| Ethernet | 121       | 47.45%  |
| Modem    | 2         | 0.78%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 114       | 80.85%  |
| Ethernet | 27        | 19.15%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 111       | 80.43%  |
| 1     | 19        | 13.77%  |
| 0     | 7         | 5.07%   |
| 3     | 1         | 0.72%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 135       | 97.83%  |
| Yes  | 3         | 2.17%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 59        | 56.73%  |
| Qualcomm Atheros Communications | 17        | 16.35%  |
| Realtek Semiconductor           | 6         | 5.77%   |
| Broadcom                        | 6         | 5.77%   |
| Lite-On Technology              | 3         | 2.88%   |
| IMC Networks                    | 3         | 2.88%   |
| Hewlett-Packard                 | 3         | 2.88%   |
| Toshiba                         | 1         | 0.96%   |
| Realtek                         | 1         | 0.96%   |
| Ralink                          | 1         | 0.96%   |
| Foxconn / Hon Hai               | 1         | 0.96%   |
| Dell                            | 1         | 0.96%   |
| Apple                           | 1         | 0.96%   |
| Alps Electric                   | 1         | 0.96%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 34        | 32.69%  |
| Qualcomm Atheros  Bluetooth Device             | 10        | 9.62%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 9         | 8.65%   |
| Intel AX201 Bluetooth                          | 5         | 4.81%   |
| Intel Centrino Bluetooth Wireless Transceiver  | 4         | 3.85%   |
| Realtek  Bluetooth 4.2 Adapter                 | 3         | 2.88%   |
| Realtek Bluetooth Radio                        | 3         | 2.88%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0          | 3         | 2.88%   |
| Intel AX200 Bluetooth                          | 3         | 2.88%   |
| Qualcomm Atheros AR3011 Bluetooth              | 2         | 1.92%   |
| Intel Bluetooth Device                         | 2         | 1.92%   |
| IMC Networks Bluetooth Device                  | 2         | 1.92%   |
| HP Broadcom 2070 Bluetooth Combo               | 2         | 1.92%   |
| Broadcom HP Portable SoftSailing               | 2         | 1.92%   |
| Broadcom HP Portable Bumble Bee                | 2         | 1.92%   |
| Toshiba Atheros AR3012 Bluetooth               | 1         | 0.96%   |
| Realtek Bluetooth Radio                        | 1         | 0.96%   |
| Ralink RT3290 Bluetooth                        | 1         | 0.96%   |
| Qualcomm Atheros AR9462 Bluetooth              | 1         | 0.96%   |
| Qualcomm Atheros AR3012 Bluetooth              | 1         | 0.96%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth     | 1         | 0.96%   |
| Lite-On Bluetooth Device                       | 1         | 0.96%   |
| Lite-On Atheros Bluetooth                      | 1         | 0.96%   |
| Intel Wireless-AC 3168 Bluetooth               | 1         | 0.96%   |
| Intel AX210 Bluetooth                          | 1         | 0.96%   |
| IMC Networks Bluetooth                         | 1         | 0.96%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]  | 1         | 0.96%   |
| Foxconn / Hon Hai Bluetooth Device             | 1         | 0.96%   |
| Dell DW375 Bluetooth Module                    | 1         | 0.96%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 1         | 0.96%   |
| Broadcom BCM2070 Bluetooth Device              | 1         | 0.96%   |
| Apple Bluetooth HCI                            | 1         | 0.96%   |
| Alps Electric UGNZG                            | 1         | 0.96%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 125       | 85.03%  |
| AMD                         | 10        | 6.8%    |
| Nvidia                      | 6         | 4.08%   |
| Turtle Beach                | 1         | 0.68%   |
| Texas Instruments           | 1         | 0.68%   |
| Realtek Semiconductor       | 1         | 0.68%   |
| GN Netcom                   | 1         | 0.68%   |
| FiiO Electronics Technology | 1         | 0.68%   |
| Apple                       | 1         | 0.68%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 24        | 13.26%  |
| Intel Haswell-ULT HD Audio Controller                                                             | 14        | 7.73%   |
| Intel 8 Series HD Audio Controller                                                                | 14        | 7.73%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 13        | 7.18%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 12        | 6.63%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 9         | 4.97%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9         | 4.97%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8         | 4.42%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 3.31%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 3.31%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 2.21%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 2.21%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 2.21%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 2.21%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 2.21%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.66%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.66%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 1.66%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 1.66%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 1.1%    |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.1%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.1%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.1%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.1%    |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.1%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.1%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2         | 1.1%    |
| Turtle Beach PX11 Headset                                                                         | 1         | 0.55%   |
| Texas Instruments PCM2912A Audio Codec                                                            | 1         | 0.55%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.55%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.55%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.55%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.55%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.55%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.55%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.55%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 0.55%   |
| GN Netcom Jabra SPEAK 510                                                                         | 1         | 0.55%   |
| FiiO Electronics Technology FiiO USB DAC-E10                                                      | 1         | 0.55%   |
| Apple Audio Device                                                                                | 1         | 0.55%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 1         | 0.55%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 0.55%   |
| AMD Navi 10 HDMI Audio                                                                            | 1         | 0.55%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 1         | 0.55%   |
| AMD FCH Azalia Controller                                                                         | 1         | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 27        | 33.75%  |
| SK hynix            | 15        | 18.75%  |
| Unknown             | 9         | 11.25%  |
| Micron Technology   | 8         | 10%     |
| Kingston            | 8         | 10%     |
| Ramaxel Technology  | 3         | 3.75%   |
| Crucial             | 3         | 3.75%   |
| A-DATA Technology   | 2         | 2.5%    |
| Qimonda             | 1         | 1.25%   |
| Patriot             | 1         | 1.25%   |
| Nanya Technology    | 1         | 1.25%   |
| Elpida              | 1         | 1.25%   |
| Avant               | 1         | 1.25%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 4         | 4.94%   |
| Unknown RAM Module 1GB Row Of Chips LPDDR4 4267MT/s            | 3         | 3.7%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 3         | 3.7%    |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                 | 2         | 2.47%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 2         | 2.47%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 2         | 2.47%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 2         | 2.47%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 2         | 2.47%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 2         | 2.47%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s          | 2         | 2.47%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s        | 2         | 2.47%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                      | 1         | 1.23%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1         | 1.23%   |
| Unknown RAM Module 2GB SODIMM DDR 800MT/s                      | 1         | 1.23%   |
| Unknown RAM Module 2048MB SODIMM DDR2                          | 1         | 1.23%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s          | 1         | 1.23%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 1.23%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s      | 1         | 1.23%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s         | 1         | 1.23%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8192MB SODIMM DDR3 1600MT/s      | 1         | 1.23%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 1.23%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1334MT/s      | 1         | 1.23%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 1         | 1.23%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s         | 1         | 1.23%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s   | 1         | 1.23%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s         | 1         | 1.23%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2400MT/s                 | 1         | 1.23%   |
| Samsung RAM Module 4GB Row Of Chips DDR4 2400MT/s              | 1         | 1.23%   |
| Samsung RAM Module 4096MB SODIMM DDR4 3200MT/s                 | 1         | 1.23%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s          | 1         | 1.23%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s          | 1         | 1.23%   |
| Samsung RAM M471B5674BH0-YH9 2GB Chip DDR3 1333MT/s            | 1         | 1.23%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s          | 1         | 1.23%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 1         | 1.23%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s          | 1         | 1.23%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s       | 1         | 1.23%   |
| Samsung RAM M471A5244CB0-CTD 4096MB Row Of Chips DDR4 2667MT/s | 1         | 1.23%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s          | 1         | 1.23%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s         | 1         | 1.23%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s       | 1         | 1.23%   |
| Samsung RAM M4 70T2864DZ3-CE6 1GB SODIMM DDR 667MT/s           | 1         | 1.23%   |
| Ramaxel RAM RMT3170KE68F9F1600 4GB SODIMM DDR3 1600MT/s        | 1         | 1.23%   |
| Ramaxel RAM RMT3170EF68F9W1600 4GB SODIMM DDR3 1600MT/s        | 1         | 1.23%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s        | 1         | 1.23%   |
| Qimonda RAM 64T128021HDL3SB 1GB SODIMM DDR 667MT/s             | 1         | 1.23%   |
| Patriot RAM 2400 C15 Series 8GB SODIMM DDR4 2667MT/s           | 1         | 1.23%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s           | 1         | 1.23%   |
| Micron RAM Module 8192MB SODIMM DDR4 2667MT/s                  | 1         | 1.23%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s           | 1         | 1.23%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s           | 1         | 1.23%   |
| Micron RAM 4KTF25664HZ-1G6E2 2GB SODIMM DDR3 1600MT/s          | 1         | 1.23%   |
| Micron RAM 4KTF25664HZ-1G4E1 2048MB SODIMM DDR3 1333MT/s       | 1         | 1.23%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s         | 1         | 1.23%   |
| Kingston RAM Module 1024MB SODIMM DDR2 667MT/s                 | 1         | 1.23%   |
| Kingston RAM KN2M64-ETB 8GB SODIMM DDR3 1600MT/s               | 1         | 1.23%   |
| Kingston RAM ACR16D3LS1KFG/8G 8GB SODIMM DDR3 1600MT/s         | 1         | 1.23%   |
| Kingston RAM 9905744-066.A00G 32GB SODIMM DDR4 3200MT/s        | 1         | 1.23%   |
| Kingston RAM 9905700-011.A00G 8GB SODIMM DDR4 2400MT/s         | 1         | 1.23%   |
| Kingston RAM 9905474-011.A00LF 4096MB SODIMM DDR3 1600MT/s     | 1         | 1.23%   |
| Elpida RAM Module 4096MB SODIMM LPDDR3 1867MT/s                | 1         | 1.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 34        | 50%     |
| DDR4   | 23        | 33.82%  |
| DDR2   | 5         | 7.35%   |
| LPDDR4 | 3         | 4.41%   |
| SDRAM  | 1         | 1.47%   |
| LPDDR3 | 1         | 1.47%   |
| DDR    | 1         | 1.47%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 60        | 88.24%  |
| Row Of Chips | 6         | 8.82%   |
| Chip         | 2         | 2.94%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 27        | 37.5%   |
| 8192  | 18        | 25%     |
| 2048  | 14        | 19.44%  |
| 16384 | 6         | 8.33%   |
| 1024  | 5         | 6.94%   |
| 32768 | 2         | 2.78%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 25        | 34.72%  |
| 2667    | 14        | 19.44%  |
| 1333    | 6         | 8.33%   |
| 1334    | 5         | 6.94%   |
| 2400    | 4         | 5.56%   |
| 4267    | 3         | 4.17%   |
| 2133    | 3         | 4.17%   |
| 667     | 3         | 4.17%   |
| 3200    | 2         | 2.78%   |
| 800     | 2         | 2.78%   |
| 8400    | 1         | 1.39%   |
| 4199    | 1         | 1.39%   |
| 3266    | 1         | 1.39%   |
| 1867    | 1         | 1.39%   |
| Unknown | 1         | 1.39%   |

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
| Chicony Electronics                    | 34        | 27.2%   |
| Cheng Uei Precision Industry (Foxlink) | 16        | 12.8%   |
| Acer                                   | 13        | 10.4%   |
| Sunplus Innovation Technology          | 7         | 5.6%    |
| Realtek Semiconductor                  | 7         | 5.6%    |
| Microdia                               | 7         | 5.6%    |
| Syntek                                 | 6         | 4.8%    |
| Lite-On Technology                     | 6         | 4.8%    |
| IMC Networks                           | 5         | 4%      |
| Silicon Motion                         | 3         | 2.4%    |
| Quanta                                 | 3         | 2.4%    |
| Suyin                                  | 2         | 1.6%    |
| Samsung Electronics                    | 2         | 1.6%    |
| Ricoh                                  | 2         | 1.6%    |
| Logitech                               | 2         | 1.6%    |
| Importek                               | 2         | 1.6%    |
| Apple                                  | 2         | 1.6%    |
| Unknown                                | 1         | 0.8%    |
| LG Electronics                         | 1         | 0.8%    |
| icSpring                               | 1         | 0.8%    |
| DigiTech                               | 1         | 0.8%    |
| ALi                                    | 1         | 0.8%    |
| Alcor Micro                            | 1         | 0.8%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony HP HD Webcam                                                       | 6         | 4.76%   |
| Chicony USB 2.0 Camera                                                     | 5         | 3.97%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 5         | 3.97%   |
| Realtek Integrated_Webcam_HD                                               | 4         | 3.17%   |
| Chicony Integrated Camera                                                  | 4         | 3.17%   |
| Acer Integrated Camera                                                     | 4         | 3.17%   |
| Syntek Integrated Camera                                                   | 3         | 2.38%   |
| Microdia Integrated_Webcam_HD                                              | 3         | 2.38%   |
| Lite-On HP HD Webcam                                                       | 3         | 2.38%   |
| Lite-On HP HD Camera                                                       | 3         | 2.38%   |
| Chicony HD Webcam                                                          | 3         | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 3         | 2.38%   |
| Syntek EasyCamera                                                          | 2         | 1.59%   |
| Sunplus Integrated_Webcam_HD                                               | 2         | 1.59%   |
| Sunplus HP HD Webcam [Fixed]                                               | 2         | 1.59%   |
| Realtek Integrated Webcam                                                  | 2         | 1.59%   |
| Importek HP Webcam-50                                                      | 2         | 1.59%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 2         | 1.59%   |
| Chicony Integrated HP HD Webcam                                            | 2         | 1.59%   |
| Chicony HP HD Webcam [Fixed]                                               | 2         | 1.59%   |
| Chicony HP HD Camera                                                       | 2         | 1.59%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed]                | 2         | 1.59%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 2         | 1.59%   |
| Acer ThinkPad P50 Integrated Camera                                        | 2         | 1.59%   |
| Unknown USB Camera                                                         | 1         | 0.79%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 0.79%   |
| Suyin HP Webcam                                                            | 1         | 0.79%   |
| Suyin Asus Integrated Webcam                                               | 1         | 0.79%   |
| Sunplus HP Wide Vision HD                                                  | 1         | 0.79%   |
| Sunplus HP TrueVision HD Camera                                            | 1         | 0.79%   |
| Sunplus HP Truevision HD                                                   | 1         | 0.79%   |
| Silicon Motion WebCam SC-13HDL11939N                                       | 1         | 0.79%   |
| Silicon Motion WebCam SC-10HDD12636N                                       | 1         | 0.79%   |
| Silicon Motion 300k Pixel Camera                                           | 1         | 0.79%   |
| Samsung Galaxy A5 (MTP)                                                    | 1         | 0.79%   |
| Samsung Galaxy (debugging mode)                                            | 1         | 0.79%   |
| Ricoh Sony Vaio Integrated Webcam                                          | 1         | 0.79%   |
| Ricoh Laptop_Integrated_Webcam_FHD                                         | 1         | 0.79%   |
| Realtek HP Webcam                                                          | 1         | 0.79%   |
| Quanta VGA WebCam                                                          | 1         | 0.79%   |
| Quanta HP Wide Vision HD Camera                                            | 1         | 0.79%   |
| Quanta HP HD Camera                                                        | 1         | 0.79%   |
| Microdia Sonix USB 2.0 Camera                                              | 1         | 0.79%   |
| Microdia Laptop_Integrated_Webcam_7645BB9590586C77DC683CD9114697FF.3M      | 1         | 0.79%   |
| Microdia HP Integrated Webcam                                              | 1         | 0.79%   |
| Microdia Amcrest AWC2198 USB Webcam                                        | 1         | 0.79%   |
| Logitech Webcam C270                                                       | 1         | 0.79%   |
| Logitech BRIO Ultra HD Webcam                                              | 1         | 0.79%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode)                      | 1         | 0.79%   |
| IMC Networks USB2.0 UVC HD Webcam                                          | 1         | 0.79%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 0.79%   |
| IMC Networks ov9734_azurewave_camera                                       | 1         | 0.79%   |
| icSpring camera                                                            | 1         | 0.79%   |
| DigiTech WebCam SCB-1110M                                                  | 1         | 0.79%   |
| Chicony USB 5M WebCam                                                      | 1         | 0.79%   |
| Chicony TOSHIBA Web Camera - MP                                            | 1         | 0.79%   |
| Chicony TOSHIBA Web Camera - HD                                            | 1         | 0.79%   |
| Chicony Lenovo EasyCamera                                                  | 1         | 0.79%   |
| Chicony Integrated Camera (1280x720@30)                                    | 1         | 0.79%   |
| Chicony HP Wide Vision HD Camera                                           | 1         | 0.79%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 29        | 67.44%  |
| Synaptics                  | 8         | 18.6%   |
| Shenzhen Goodix Technology | 4         | 9.3%    |
| LighTuning Technology      | 1         | 2.33%   |
| AuthenTec                  | 1         | 2.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 13        | 30.23%  |
| Validity Sensors VFS491                                                    | 6         | 13.95%  |
| Synaptics WBDI Device                                                      | 3         | 6.98%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 6.98%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 4.65%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 4.65%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 4.65%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 4.65%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2.33%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 2.33%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 2.33%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 2.33%   |
| Synaptics  WBDI                                                            | 1         | 2.33%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 2.33%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 2.33%   |
| Shenzhen Goodix  Fingerprint Device                                        | 1         | 2.33%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 2.33%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 2.33%   |

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
| 0     | 83        | 59.29%  |
| 1     | 45        | 32.14%  |
| 2     | 11        | 7.86%   |
| 3     | 1         | 0.71%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 43        | 63.24%  |
| Chipcard                 | 7         | 10.29%  |
| Graphics card            | 5         | 7.35%   |
| Net/wireless             | 3         | 4.41%   |
| Camera                   | 3         | 4.41%   |
| Storage                  | 2         | 2.94%   |
| Communication controller | 2         | 2.94%   |
| Sound                    | 1         | 1.47%   |
| Net/ethernet             | 1         | 1.47%   |
| Bluetooth                | 1         | 1.47%   |

