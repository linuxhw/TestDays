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

Total: 240

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 2570p             | [199df541f2](https://linux-hardware.org/?probe=199df541f2) | Dec 21, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [856515e522](https://linux-hardware.org/?probe=856515e522) | Dec 19, 2022 |
| HP            | EliteBook 840 G3            | [3e518355b6](https://linux-hardware.org/?probe=3e518355b6) | Dec 17, 2022 |
| HP            | EliteBook 840 G3            | [eccd29cfac](https://linux-hardware.org/?probe=eccd29cfac) | Dec 17, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [645418a0dd](https://linux-hardware.org/?probe=645418a0dd) | Nov 30, 2022 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | [2a4bb490d0](https://linux-hardware.org/?probe=2a4bb490d0) | Nov 29, 2022 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | [a05b99b00e](https://linux-hardware.org/?probe=a05b99b00e) | Nov 29, 2022 |
| HP            | Pavilion Laptop 15-eh2xx... | [21cd2084c5](https://linux-hardware.org/?probe=21cd2084c5) | Nov 16, 2022 |
| HP            | Laptop 15-bs0xx             | [b152ccfb56](https://linux-hardware.org/?probe=b152ccfb56) | Nov 14, 2022 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [c42e078d94](https://linux-hardware.org/?probe=c42e078d94) | Nov 04, 2022 |
| HP            | ProBook 650 G2              | [713f71652e](https://linux-hardware.org/?probe=713f71652e) | Nov 04, 2022 |
| Lenovo        | ThinkPad T430s 23539KU      | [34d3046ea4](https://linux-hardware.org/?probe=34d3046ea4) | Nov 03, 2022 |
| Lenovo        | ThinkPad T430s 23539KU      | [ff4e869df2](https://linux-hardware.org/?probe=ff4e869df2) | Nov 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [2ceb11d7b3](https://linux-hardware.org/?probe=2ceb11d7b3) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [5c3d640129](https://linux-hardware.org/?probe=5c3d640129) | Oct 29, 2022 |
| Dell          | Latitude 3350               | [e545da88bf](https://linux-hardware.org/?probe=e545da88bf) | Oct 28, 2022 |
| Lenovo        | Legion S7 15IMH5 82BC       | [7654e5f9c4](https://linux-hardware.org/?probe=7654e5f9c4) | Oct 26, 2022 |
| HP            | ProBook 650 G2              | [7848c6d520](https://linux-hardware.org/?probe=7848c6d520) | Oct 26, 2022 |
| HP            | ProBook 450 G7              | [6a9b93fdeb](https://linux-hardware.org/?probe=6a9b93fdeb) | Oct 16, 2022 |
| HP            | ProBook 650 G2              | [43ce2df718](https://linux-hardware.org/?probe=43ce2df718) | Oct 12, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [dc3347c309](https://linux-hardware.org/?probe=dc3347c309) | Oct 10, 2022 |
| Dell          | Inspiron 1525               | [77f9a2e79a](https://linux-hardware.org/?probe=77f9a2e79a) | Oct 04, 2022 |
| HP            | 15                          | [28e8e01768](https://linux-hardware.org/?probe=28e8e01768) | Sep 28, 2022 |
| HP            | EliteBook Folio 9480m       | [e2232c49ca](https://linux-hardware.org/?probe=e2232c49ca) | Sep 25, 2022 |
| Toshiba       | TECRA A50-A                 | [6ef2538a5a](https://linux-hardware.org/?probe=6ef2538a5a) | Sep 23, 2022 |
| Dell          | Latitude 3350               | [62c380dcd0](https://linux-hardware.org/?probe=62c380dcd0) | Sep 22, 2022 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | [6c1c4c8712](https://linux-hardware.org/?probe=6c1c4c8712) | Sep 10, 2022 |
| HP            | EliteBook 840 G1            | [1796a51c0c](https://linux-hardware.org/?probe=1796a51c0c) | Sep 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [f7189849b4](https://linux-hardware.org/?probe=f7189849b4) | Sep 01, 2022 |
| HP            | EliteBook 8440p             | [f85ff90a58](https://linux-hardware.org/?probe=f85ff90a58) | Aug 22, 2022 |
| HP            | EliteBook 8440p             | [3842f0e711](https://linux-hardware.org/?probe=3842f0e711) | Aug 22, 2022 |
| ASUSTek       | X540NA                      | [1fa4b8b58a](https://linux-hardware.org/?probe=1fa4b8b58a) | Aug 21, 2022 |
| ASUSTek       | X540NA                      | [e9bcb08163](https://linux-hardware.org/?probe=e9bcb08163) | Aug 21, 2022 |
| HP            | ENVY 15                     | [5d984dedf6](https://linux-hardware.org/?probe=5d984dedf6) | Aug 20, 2022 |
| ASUSTek       | X540NA                      | [c37ee0a700](https://linux-hardware.org/?probe=c37ee0a700) | Aug 08, 2022 |
| Dell          | Inspiron 3521               | [b947e19278](https://linux-hardware.org/?probe=b947e19278) | Aug 02, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [2abfab93cb](https://linux-hardware.org/?probe=2abfab93cb) | Aug 02, 2022 |
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


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 33        | 18.75%  |
| Ubuntu 18.04        | 15        | 8.52%   |
| Ubuntu 22.04        | 11        | 6.25%   |
| Zorin 16            | 6         | 3.41%   |
| Fedora 36           | 6         | 3.41%   |
| Manjaro             | 5         | 2.84%   |
| Zorin 15            | 4         | 2.27%   |
| Ubuntu 20.10        | 4         | 2.27%   |
| Ubuntu 19.04        | 4         | 2.27%   |
| Pop!_OS 20.04       | 4         | 2.27%   |
| OpenMandriva 4.2    | 4         | 2.27%   |
| Linux Mint 20.3     | 4         | 2.27%   |
| Arch                | 4         | 2.27%   |
| Ubuntu 21.04        | 3         | 1.7%    |
| Q4OS 3              | 3         | 1.7%    |
| Ubuntu 21.10        | 2         | 1.14%   |
| Ubuntu 19.10        | 2         | 1.14%   |
| Parrot 5.1          | 2         | 1.14%   |
| Linux Mint 20.2     | 2         | 1.14%   |
| Linux Mint 19       | 2         | 1.14%   |
| Fedora 35           | 2         | 1.14%   |
| Fedora 32           | 2         | 1.14%   |
| Endless 3.9.4       | 2         | 1.14%   |
| Endless 3.9.2       | 2         | 1.14%   |
| Endless 3.9.1       | 2         | 1.14%   |
| Debian 11           | 2         | 1.14%   |
| Xubuntu 20.04       | 1         | 0.57%   |
| Ubuntu MATE 21.04   | 1         | 0.57%   |
| Ubuntu MATE 20.04   | 1         | 0.57%   |
| Ubuntu Budgie 20.04 | 1         | 0.57%   |
| Ubuntu 16.04        | 1         | 0.57%   |
| ROSA R11            | 1         | 0.57%   |
| ROSA R10            | 1         | 0.57%   |
| RHEL 8              | 1         | 0.57%   |
| Pop!_OS 22.04       | 1         | 0.57%   |
| Pop!_OS 21.04       | 1         | 0.57%   |
| Pop!_OS 20.10       | 1         | 0.57%   |
| Parrot 5.0          | 1         | 0.57%   |
| Parrot 4.9          | 1         | 0.57%   |
| Parrot 4.8          | 1         | 0.57%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 69        | 42.07%  |
| Fedora        | 12        | 7.32%   |
| Zorin         | 10        | 6.1%    |
| Linux Mint    | 9         | 5.49%   |
| Endless       | 8         | 4.88%   |
| Pop!_OS       | 7         | 4.27%   |
| Parrot        | 6         | 3.66%   |
| Manjaro       | 6         | 3.66%   |
| Arch          | 6         | 3.66%   |
| OpenMandriva  | 5         | 3.05%   |
| Q4OS          | 3         | 1.83%   |
| Kali          | 3         | 1.83%   |
| Debian        | 3         | 1.83%   |
| Ubuntu MATE   | 2         | 1.22%   |
| ROSA          | 2         | 1.22%   |
| Elementary    | 2         | 1.22%   |
| Xubuntu       | 1         | 0.61%   |
| Ubuntu Budgie | 1         | 0.61%   |
| RHEL          | 1         | 0.61%   |
| openSUSE      | 1         | 0.61%   |
| Nobara        | 1         | 0.61%   |
| Lubuntu       | 1         | 0.61%   |
| LMDE          | 1         | 0.61%   |
| KDE neon      | 1         | 0.61%   |
| Garuda Linux  | 1         | 0.61%   |
| BlackPanther  | 1         | 0.61%   |
| antiX         | 1         | 0.61%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.8.0-14-generic         | 6         | 3.16%   |
| 5.15.0-52-generic        | 4         | 2.11%   |
| 5.11.0-38-generic        | 4         | 2.11%   |
| 5.10.14-desktop-1omv4002 | 4         | 2.11%   |
| 5.4.0-58-generic         | 3         | 1.58%   |
| 5.4.0-52-generic         | 3         | 1.58%   |
| 5.4.0-45-generic         | 3         | 1.58%   |
| 5.4.0-42-generic         | 3         | 1.58%   |
| 5.15.0-53-generic        | 3         | 1.58%   |
| 5.15.0-41-generic        | 3         | 1.58%   |
| 4.19.0-17-amd64          | 3         | 1.58%   |
| 5.8.0-59-generic         | 2         | 1.05%   |
| 5.8.0-43-generic         | 2         | 1.05%   |
| 5.4.0-67-generic         | 2         | 1.05%   |
| 5.4.0-65-generic         | 2         | 1.05%   |
| 5.4.0-54-generic         | 2         | 1.05%   |
| 5.4.0-48-generic         | 2         | 1.05%   |
| 5.4.0-47-generic         | 2         | 1.05%   |
| 5.4.0-37-generic         | 2         | 1.05%   |
| 5.3.0-28-generic         | 2         | 1.05%   |
| 5.18.13-200.fc36.x86_64  | 2         | 1.05%   |
| 5.18.0-14parrot1-amd64   | 2         | 1.05%   |
| 5.15.0-46-generic        | 2         | 1.05%   |
| 5.13.19-2-MANJARO        | 2         | 1.05%   |
| 5.13.0-27-generic        | 2         | 1.05%   |
| 5.11.0-37-generic        | 2         | 1.05%   |
| 5.11.0-34-generic        | 2         | 1.05%   |
| 6.0.12-300.fc37.x86_64   | 1         | 0.53%   |
| 5.9.14-arch1-1           | 1         | 0.53%   |
| 5.9.13-200.fc33.x86_64   | 1         | 0.53%   |
| 5.8.4-200.fc32.x86_64    | 1         | 0.53%   |
| 5.8.12-arch1-1           | 1         | 0.53%   |
| 5.8.0-63-generic         | 1         | 0.53%   |
| 5.8.0-55-generic         | 1         | 0.53%   |
| 5.8.0-51-generic         | 1         | 0.53%   |
| 5.8.0-50-generic         | 1         | 0.53%   |
| 5.8.0-48-generic         | 1         | 0.53%   |
| 5.8.0-44-generic         | 1         | 0.53%   |
| 5.8.0-41-generic         | 1         | 0.53%   |
| 5.8.0-29-generic         | 1         | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 36        | 20%     |
| 5.8.0   | 18        | 10%     |
| 5.15.0  | 16        | 8.89%   |
| 5.11.0  | 13        | 7.22%   |
| 4.15.0  | 11        | 6.11%   |
| 5.3.0   | 7         | 3.89%   |
| 5.13.0  | 7         | 3.89%   |
| 5.0.0   | 7         | 3.89%   |
| 5.10.14 | 4         | 2.22%   |
| 5.10.0  | 4         | 2.22%   |
| 4.19.0  | 4         | 2.22%   |
| 5.18.0  | 3         | 1.67%   |
| 4.18.0  | 3         | 1.67%   |
| 5.19.9  | 2         | 1.11%   |
| 5.18.13 | 2         | 1.11%   |
| 5.17.5  | 2         | 1.11%   |
| 5.16.7  | 2         | 1.11%   |
| 5.13.19 | 2         | 1.11%   |
| 6.0.12  | 1         | 0.56%   |
| 5.9.14  | 1         | 0.56%   |
| 5.9.13  | 1         | 0.56%   |
| 5.8.4   | 1         | 0.56%   |
| 5.8.12  | 1         | 0.56%   |
| 5.7.17  | 1         | 0.56%   |
| 5.6.7   | 1         | 0.56%   |
| 5.6.5   | 1         | 0.56%   |
| 5.6.11  | 1         | 0.56%   |
| 5.5.0   | 1         | 0.56%   |
| 5.2.5   | 1         | 0.56%   |
| 5.2.0   | 1         | 0.56%   |
| 5.19.2  | 1         | 0.56%   |
| 5.19.15 | 1         | 0.56%   |
| 5.19.13 | 1         | 0.56%   |
| 5.19.0  | 1         | 0.56%   |
| 5.17.6  | 1         | 0.56%   |
| 5.17.4  | 1         | 0.56%   |
| 5.16.16 | 1         | 0.56%   |
| 5.16.14 | 1         | 0.56%   |
| 5.16.0  | 1         | 0.56%   |
| 5.15.13 | 1         | 0.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 36        | 20.22%  |
| 5.8     | 20        | 11.24%  |
| 5.15    | 17        | 9.55%   |
| 5.11    | 14        | 7.87%   |
| 5.10    | 11        | 6.18%   |
| 4.15    | 11        | 6.18%   |
| 5.13    | 9         | 5.06%   |
| 5.0     | 8         | 4.49%   |
| 5.3     | 7         | 3.93%   |
| 5.19    | 6         | 3.37%   |
| 5.18    | 5         | 2.81%   |
| 4.19    | 5         | 2.81%   |
| 5.16    | 4         | 2.25%   |
| 4.18    | 4         | 2.25%   |
| 5.6     | 3         | 1.69%   |
| 5.17    | 3         | 1.69%   |
| 5.14    | 3         | 1.69%   |
| 5.9     | 2         | 1.12%   |
| 5.2     | 2         | 1.12%   |
| 4.9     | 2         | 1.12%   |
| 6.0     | 1         | 0.56%   |
| 5.7     | 1         | 0.56%   |
| 5.5     | 1         | 0.56%   |
| 5.1     | 1         | 0.56%   |
| 4.16    | 1         | 0.56%   |
| 4.13    | 1         | 0.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 159       | 98.15%  |
| i686   | 3         | 1.85%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 101       | 60.84%  |
| Unknown    | 19        | 11.45%  |
| KDE5       | 15        | 9.04%   |
| X-Cinnamon | 10        | 6.02%   |
| MATE       | 6         | 3.61%   |
| XFCE       | 5         | 3.01%   |
| KDE        | 4         | 2.41%   |
| Pantheon   | 2         | 1.2%    |
| KDE4       | 2         | 1.2%    |
| LXQt       | 1         | 0.6%    |
| Cinnamon   | 1         | 0.6%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 121       | 72.89%  |
| Wayland | 35        | 21.08%  |
| Unknown | 10        | 6.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 92        | 55.42%  |
| GDM     | 28        | 16.87%  |
| SDDM    | 17        | 10.24%  |
| GDM3    | 16        | 9.64%   |
| LightDM | 6         | 3.61%   |
| TDM     | 5         | 3.01%   |
| KDM     | 2         | 1.2%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 119       | 72.56%  |
| Unknown | 23        | 14.02%  |
| en_GB   | 19        | 11.59%  |
| C       | 2         | 1.22%   |
| en_AG   | 1         | 0.61%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 92        | 55.76%  |
| EFI  | 73        | 44.24%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 135       | 83.33%  |
| Btrfs   | 14        | 8.64%   |
| Overlay | 9         | 5.56%   |
| Unknown | 2         | 1.23%   |
| Zfs     | 1         | 0.62%   |
| Xfs     | 1         | 0.62%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 97        | 58.79%  |
| GPT     | 47        | 28.48%  |
| MBR     | 21        | 12.73%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 144       | 88.34%  |
| Yes       | 19        | 11.66%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 114       | 70.37%  |
| Yes       | 48        | 29.63%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 68        | 41.98%  |
| Lenovo                      | 34        | 20.99%  |
| Dell                        | 19        | 11.73%  |
| ASUSTek Computer            | 8         | 4.94%   |
| Toshiba                     | 7         | 4.32%   |
| Acer                        | 4         | 2.47%   |
| Samsung Electronics         | 3         | 1.85%   |
| Chuwi                       | 2         | 1.23%   |
| Apple                       | 2         | 1.23%   |
| TECNO                       | 1         | 0.62%   |
| Sony                        | 1         | 0.62%   |
| SLIMBOOK                    | 1         | 0.62%   |
| Panasonic                   | 1         | 0.62%   |
| Notebook                    | 1         | 0.62%   |
| Insyde                      | 1         | 0.62%   |
| I-Life Digital Technologies | 1         | 0.62%   |
| HUAWEI                      | 1         | 0.62%   |
| Getac                       | 1         | 0.62%   |
| EVOC                        | 1         | 0.62%   |
| EUROCOM                     | 1         | 0.62%   |
| Endless                     | 1         | 0.62%   |
| Eluktronics                 | 1         | 0.62%   |
| Clevo                       | 1         | 0.62%   |
| Unknown                     | 1         | 0.62%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| HP EliteBook 840 G3                     | 4         | 2.47%   |
| HP EliteBook 840 G1                     | 4         | 2.47%   |
| HP EliteBook Folio 9480m                | 3         | 1.85%   |
| HP EliteBook Folio 9470m                | 3         | 1.85%   |
| Dell XPS 13 9310                        | 3         | 1.85%   |
| Unknown                                 | 3         | 1.85%   |
| Toshiba Satellite C660                  | 2         | 1.23%   |
| Lenovo IdeaPad S340-14IIL 81VV          | 2         | 1.23%   |
| HP ProBook 640 G1                       | 2         | 1.23%   |
| HP ProBook 440 G5                       | 2         | 1.23%   |
| HP Pavilion Laptop 15-cs3xxx            | 2         | 1.23%   |
| HP ENVY 15                              | 2         | 1.23%   |
| HP EliteBook 8440p                      | 2         | 1.23%   |
| HP EliteBook 840 G2                     | 2         | 1.23%   |
| HP Compaq Mini 110c-1100                | 2         | 1.23%   |
| HP 15 Notebook PC                       | 2         | 1.23%   |
| HP 15                                   | 2         | 1.23%   |
| Dell Inspiron 5767                      | 2         | 1.23%   |
| ASUS X540NA                             | 2         | 1.23%   |
| Toshiba TECRA A50-A                     | 1         | 0.62%   |
| Toshiba Satellite L50-B                 | 1         | 0.62%   |
| Toshiba R84SAU2                         | 1         | 0.62%   |
| Toshiba dynabook Satellite B554/M       | 1         | 0.62%   |
| Toshiba dynabook R731/E                 | 1         | 0.62%   |
| TECNO WinPad 2                          | 1         | 0.62%   |
| Sony VGN-NS295J                         | 1         | 0.62%   |
| SLIMBOOK PROX14-AMD                     | 1         | 0.62%   |
| Samsung RC410/RC510/RC710               | 1         | 0.62%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV | 1         | 0.62%   |
| Samsung 300E4C/300E5C/300E7C            | 1         | 0.62%   |
| Panasonic CF-SX2JDQZF5                  | 1         | 0.62%   |
| Notebook P65xHP                         | 1         | 0.62%   |
| Lenovo Z50-75 80EC                      | 1         | 0.62%   |
| Lenovo V330-14IKB 81B0                  | 1         | 0.62%   |
| Lenovo V310-15ISK 80SY                  | 1         | 0.62%   |
| Lenovo V14-IGL 82C2                     | 1         | 0.62%   |
| Lenovo V130-14IKB 81HQ                  | 1         | 0.62%   |
| Lenovo V110-15ISK 80TL                  | 1         | 0.62%   |
| Lenovo ThinkPad X250 20CLA21MJP         | 1         | 0.62%   |
| Lenovo ThinkPad X240 20AMS4J900         | 1         | 0.62%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| HP EliteBook           | 26        | 16.05%  |
| Lenovo ThinkPad        | 18        | 11.11%  |
| HP ProBook             | 13        | 8.02%   |
| Lenovo IdeaPad         | 9         | 5.56%   |
| Dell Latitude          | 8         | 4.94%   |
| Dell Inspiron          | 8         | 4.94%   |
| HP Pavilion            | 7         | 4.32%   |
| HP Laptop              | 4         | 2.47%   |
| HP ENVY                | 4         | 2.47%   |
| HP 15                  | 4         | 2.47%   |
| Acer Aspire            | 4         | 2.47%   |
| Toshiba Satellite      | 3         | 1.85%   |
| Dell XPS               | 3         | 1.85%   |
| Unknown                | 3         | 1.85%   |
| Toshiba dynabook       | 2         | 1.23%   |
| HP Compaq              | 2         | 1.23%   |
| ASUS X540NA            | 2         | 1.23%   |
| Toshiba TECRA          | 1         | 0.62%   |
| Toshiba R84SAU2        | 1         | 0.62%   |
| TECNO WinPad           | 1         | 0.62%   |
| Sony VGN-NS295J        | 1         | 0.62%   |
| SLIMBOOK PROX14-AMD    | 1         | 0.62%   |
| Samsung RC410          | 1         | 0.62%   |
| Samsung 300E5EV        | 1         | 0.62%   |
| Samsung 300E4C         | 1         | 0.62%   |
| Panasonic CF-SX2JDQZF5 | 1         | 0.62%   |
| Notebook P65xHP        | 1         | 0.62%   |
| Lenovo Z50-75          | 1         | 0.62%   |
| Lenovo V330-14IKB      | 1         | 0.62%   |
| Lenovo V310-15ISK      | 1         | 0.62%   |
| Lenovo V14-IGL         | 1         | 0.62%   |
| Lenovo V130-14IKB      | 1         | 0.62%   |
| Lenovo V110-15ISK      | 1         | 0.62%   |
| Lenovo Legion          | 1         | 0.62%   |
| Insyde i101c           | 1         | 0.62%   |
| I-Life Digital ZED     | 1         | 0.62%   |
| HUAWEI NBLK-WAX9X      | 1         | 0.62%   |
| HP ZHAN                | 1         | 0.62%   |
| HP ZBook               | 1         | 0.62%   |
| HP Presario            | 1         | 0.62%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2013    | 19        | 11.73%  |
| 2016    | 18        | 11.11%  |
| 2019    | 16        | 9.88%   |
| 2018    | 15        | 9.26%   |
| 2012    | 14        | 8.64%   |
| 2017    | 13        | 8.02%   |
| 2015    | 13        | 8.02%   |
| 2014    | 13        | 8.02%   |
| 2020    | 10        | 6.17%   |
| 2011    | 10        | 6.17%   |
| 2010    | 9         | 5.56%   |
| 2021    | 3         | 1.85%   |
| 2009    | 2         | 1.23%   |
| 2008    | 2         | 1.23%   |
| 2007    | 2         | 1.23%   |
| 2006    | 2         | 1.23%   |
| Unknown | 1         | 0.62%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 162       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 151       | 92.07%  |
| Enabled  | 13        | 7.93%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 162       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 49        | 30.06%  |
| 4.01-8.0    | 48        | 29.45%  |
| 8.01-16.0   | 24        | 14.72%  |
| 16.01-24.0  | 18        | 11.04%  |
| 1.01-2.0    | 13        | 7.98%   |
| 32.01-64.0  | 5         | 3.07%   |
| 64.01-256.0 | 3         | 1.84%   |
| 24.01-32.0  | 1         | 0.61%   |
| 2.01-3.0    | 1         | 0.61%   |
| 0.51-1.0    | 1         | 0.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 52        | 28.57%  |
| 2.01-3.0  | 51        | 28.02%  |
| 3.01-4.0  | 31        | 17.03%  |
| 4.01-8.0  | 30        | 16.48%  |
| 0.51-1.0  | 15        | 8.24%   |
| 8.01-16.0 | 3         | 1.65%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 142       | 85.54%  |
| 2      | 20        | 12.05%  |
| 10     | 1         | 0.6%    |
| 8      | 1         | 0.6%    |
| 4      | 1         | 0.6%    |
| 3      | 1         | 0.6%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 101       | 62.35%  |
| Yes       | 61        | 37.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 138       | 85.19%  |
| No        | 24        | 14.81%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 156       | 96.3%   |
| No        | 6         | 3.7%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 126       | 76.83%  |
| No        | 38        | 23.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Kenya   | 162       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City     | Notebooks | Percent |
|----------|-----------|---------|
| Nairobi  | 150       | 89.29%  |
| Mombasa  | 3         | 1.79%   |
| Nakuru   | 2         | 1.19%   |
| Kiambu   | 2         | 1.19%   |
| Eldoret  | 2         | 1.19%   |
| Wote     | 1         | 0.6%    |
| Rongai   | 1         | 0.6%    |
| Nyeri    | 1         | 0.6%    |
| Narok    | 1         | 0.6%    |
| Nanyuki  | 1         | 0.6%    |
| Murang'a | 1         | 0.6%    |
| Maralal  | 1         | 0.6%    |
| Machakos | 1         | 0.6%    |
| Kisii    | 1         | 0.6%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 46        | 61     | 25.14%  |
| Toshiba             | 25        | 30     | 13.66%  |
| WDC                 | 23        | 29     | 12.57%  |
| Samsung Electronics | 18        | 27     | 9.84%   |
| HGST                | 12        | 21     | 6.56%   |
| Unknown             | 11        | 15     | 6.01%   |
| Hitachi             | 8         | 9      | 4.37%   |
| SanDisk             | 7         | 7      | 3.83%   |
| Crucial             | 6         | 8      | 3.28%   |
| Micron Technology   | 5         | 6      | 2.73%   |
| MARSHAL             | 4         | 4      | 2.19%   |
| SPCC                | 2         | 2      | 1.09%   |
| SK hynix            | 2         | 2      | 1.09%   |
| Kingston            | 2         | 4      | 1.09%   |
| TCSUNBOW            | 1         | 1      | 0.55%   |
| Plextor             | 1         | 1      | 0.55%   |
| Netac               | 1         | 1      | 0.55%   |
| Lexar               | 1         | 1      | 0.55%   |
| Intel               | 1         | 1      | 0.55%   |
| HUAWEI              | 1         | 1      | 0.55%   |
| Golden              | 1         | 1      | 0.55%   |
| Eluktro             | 1         | 1      | 0.55%   |
| China               | 1         | 1      | 0.55%   |
| CARLSTEIN           | 1         | 3      | 0.55%   |
| Apple               | 1         | 1      | 0.55%   |
| A-DATA Technology   | 1         | 1      | 0.55%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB         | 9         | 4.74%   |
| Seagate ST500LT012-9WS142 500GB        | 6         | 3.16%   |
| Toshiba MQ04ABF100 1TB                 | 5         | 2.63%   |
| HGST HTS725050A7E630 500GB             | 5         | 2.63%   |
| Toshiba MQ01ABD100 1TB                 | 4         | 2.11%   |
| Seagate ST500LT012-1DG142 500GB        | 4         | 2.11%   |
| Samsung SSD 960 EVO 1TB                | 4         | 2.11%   |
| WDC PC SN730 NVMe 512GB                | 3         | 1.58%   |
| Unknown MMC Card  64GB                 | 3         | 1.58%   |
| Unknown MMC Card  32GB                 | 3         | 1.58%   |
| Toshiba MQ01ABF050 500GB               | 3         | 1.58%   |
| Seagate ST9500325AS 500GB              | 3         | 1.58%   |
| Seagate ST500LM021-1KJ152 500GB        | 3         | 1.58%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 3         | 1.58%   |
| Crucial CT2050MX300SSD1 2TB            | 3         | 1.58%   |
| WDC WD5000LPCX-60VHAT0 500GB           | 2         | 1.05%   |
| WDC WD5000LPCX-24VHAT0 500GB           | 2         | 1.05%   |
| WDC WD2500BEKT-75PVMT0 250GB           | 2         | 1.05%   |
| WDC WD10SPZX-60Z10T0 1TB               | 2         | 1.05%   |
| Unknown NCard  32GB                    | 2         | 1.05%   |
| Seagate ST500VT000-1DK142 500GB        | 2         | 1.05%   |
| Seagate ST500LM030-1RK17D 500GB        | 2         | 1.05%   |
| Seagate ST250LT003-9YG14C 250GB        | 2         | 1.05%   |
| Seagate ST2000LM003 HN-M201RAD 2TB     | 2         | 1.05%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 2         | 1.05%   |
| Samsung NVMe SSD Drive 512GB           | 2         | 1.05%   |
| MARSHAL MAL2500SA-T54L 500GB           | 2         | 1.05%   |
| Hitachi HTS545032B9A300 320GB          | 2         | 1.05%   |
| HGST HTS541010A9E680 1TB               | 2         | 1.05%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 1         | 0.53%   |
| WDC WDS100T1B0A-00H9H0 1TB SSD         | 1         | 0.53%   |
| WDC WD5000LPVX-75V0TT0 500GB           | 1         | 0.53%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 1         | 0.53%   |
| WDC WD5000LPCX-24C6HT0 500GB           | 1         | 0.53%   |
| WDC WD5000LPCX-22VHAT1 500GB           | 1         | 0.53%   |
| WDC WD5000BPVT-60HXZT3 500GB           | 1         | 0.53%   |
| WDC WD3200BUCT-63TWBY0 320GB           | 1         | 0.53%   |
| WDC WD10SPZX-08Z10 1TB                 | 1         | 0.53%   |
| WDC WD10JPVX-60JC3T0 1TB               | 1         | 0.53%   |
| WDC WD10JPCX-24UE4T0 1TB               | 1         | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 46        | 61     | 42.59%  |
| Toshiba | 21        | 26     | 19.44%  |
| WDC     | 17        | 23     | 15.74%  |
| HGST    | 12        | 21     | 11.11%  |
| Hitachi | 8         | 9      | 7.41%   |
| MARSHAL | 4         | 4      | 3.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 7         | 7      | 19.44%  |
| Samsung Electronics | 6         | 9      | 16.67%  |
| Crucial             | 6         | 8      | 16.67%  |
| Micron Technology   | 3         | 4      | 8.33%   |
| WDC                 | 2         | 2      | 5.56%   |
| Kingston            | 2         | 4      | 5.56%   |
| Toshiba             | 1         | 1      | 2.78%   |
| TCSUNBOW            | 1         | 1      | 2.78%   |
| SK hynix            | 1         | 1      | 2.78%   |
| Plextor             | 1         | 1      | 2.78%   |
| Netac               | 1         | 1      | 2.78%   |
| Lexar               | 1         | 1      | 2.78%   |
| Golden              | 1         | 1      | 2.78%   |
| Eluktro             | 1         | 1      | 2.78%   |
| China               | 1         | 1      | 2.78%   |
| A-DATA Technology   | 1         | 1      | 2.78%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 105       | 144    | 57.69%  |
| SSD     | 36        | 44     | 19.78%  |
| NVMe    | 28        | 32     | 15.38%  |
| MMC     | 11        | 15     | 6.04%   |
| Unknown | 2         | 4      | 1.1%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 133       | 189    | 76%     |
| NVMe | 28        | 32     | 16%     |
| MMC  | 11        | 15     | 6.29%   |
| SAS  | 3         | 3      | 1.71%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 93        | 123    | 67.88%  |
| 0.51-1.0   | 39        | 50     | 28.47%  |
| 1.01-2.0   | 4         | 11     | 2.92%   |
| 3.01-4.0   | 1         | 4      | 0.73%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 50        | 29.94%  |
| 101-250        | 35        | 20.96%  |
| 501-1000       | 27        | 16.17%  |
| 51-100         | 17        | 10.18%  |
| 1-20           | 8         | 4.79%   |
| 21-50          | 7         | 4.19%   |
| 1001-2000      | 7         | 4.19%   |
| Unknown        | 7         | 4.19%   |
| 2001-3000      | 6         | 3.59%   |
| More than 3000 | 3         | 1.8%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 46        | 26.44%  |
| 21-50          | 32        | 18.39%  |
| 101-250        | 31        | 17.82%  |
| 51-100         | 24        | 13.79%  |
| 251-500        | 18        | 10.34%  |
| 501-1000       | 8         | 4.6%    |
| Unknown        | 7         | 4.02%   |
| 1001-2000      | 4         | 2.3%    |
| More than 3000 | 3         | 1.72%   |
| 2001-3000      | 1         | 0.57%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB       | 3         | 3      | 12.5%   |
| WDC WD2500BEKT-75PVMT0 250GB          | 2         | 2      | 8.33%   |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 8.33%   |
| WDC WD10SPZX-60Z10T0 1TB              | 1         | 1      | 4.17%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 4.17%   |
| Toshiba MQ01ABD050V 500GB             | 1         | 1      | 4.17%   |
| Toshiba MK3263GSX 320GB               | 1         | 1      | 4.17%   |
| Toshiba MK3252GSX 320GB               | 1         | 1      | 4.17%   |
| SK hynix HFS128G32TND-N210A 128GB SSD | 1         | 1      | 4.17%   |
| Seagate ST9500325AS 500GB             | 1         | 1      | 4.17%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 4.17%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 4.17%   |
| MARSHAL MAL2750SA-T54 752GB           | 1         | 1      | 4.17%   |
| Hitachi HTS545032B9A300 320GB         | 1         | 1      | 4.17%   |
| Hitachi HTS542525K9SA00 250GB         | 1         | 1      | 4.17%   |
| HGST HTS725050A7E630 500GB            | 1         | 1      | 4.17%   |
| HGST HTS545050A7E380 500GB            | 1         | 1      | 4.17%   |
| HGST HTS541515A9E630 1TB              | 1         | 2      | 4.17%   |
| HGST HTS541010A9E680 1TB              | 1         | 2      | 4.17%   |
| Crucial CT2050MX300SSD1 2TB           | 1         | 2      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Toshiba  | 6         | 6      | 26.09%  |
| Seagate  | 6         | 6      | 26.09%  |
| WDC      | 3         | 3      | 13.04%  |
| HGST     | 3         | 6      | 13.04%  |
| Hitachi  | 2         | 2      | 8.7%    |
| SK hynix | 1         | 1      | 4.35%   |
| MARSHAL  | 1         | 1      | 4.35%   |
| Crucial  | 1         | 2      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 6         | 6      | 28.57%  |
| Seagate | 6         | 6      | 28.57%  |
| WDC     | 3         | 3      | 14.29%  |
| HGST    | 3         | 6      | 14.29%  |
| Hitachi | 2         | 2      | 9.52%   |
| MARSHAL | 1         | 1      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 21        | 24     | 91.3%   |
| SSD  | 2         | 3      | 8.7%    |

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
| Detected | 102       | 147    | 62.2%   |
| Works    | 40        | 65     | 24.39%  |
| Malfunc  | 22        | 27     | 13.41%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 140       | 80.46%  |
| Samsung Electronics          | 14        | 8.05%   |
| AMD                          | 6         | 3.45%   |
| SanDisk                      | 4         | 2.3%    |
| Toshiba America Info Systems | 3         | 1.72%   |
| Silicon Motion               | 2         | 1.15%   |
| Micron Technology            | 2         | 1.15%   |
| SK hynix                     | 1         | 0.57%   |
| ASMedia Technology           | 1         | 0.57%   |
| Apple                        | 1         | 0.57%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 25        | 13.81%  |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 17        | 9.39%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 14        | 7.73%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 12        | 6.63%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 11        | 6.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 9         | 4.97%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 8         | 4.42%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 7         | 3.87%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 6         | 3.31%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 4         | 2.21%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 4         | 2.21%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 4         | 2.21%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 4         | 2.21%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 3         | 1.66%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 3         | 1.66%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 1.66%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 3         | 1.66%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 3         | 1.66%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 3         | 1.66%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 2         | 1.1%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 2         | 1.1%    |
| Samsung NVMe SSD Controller 980                                                        | 2         | 1.1%    |
| Micron Non-Volatile memory controller                                                  | 2         | 1.1%    |
| Intel Volume Management Device NVMe RAID Controller                                    | 2         | 1.1%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 2         | 1.1%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 2         | 1.1%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 2         | 1.1%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 2         | 1.1%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 2         | 1.1%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 1         | 0.55%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 1         | 0.55%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 1         | 0.55%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 1         | 0.55%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 0.55%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 1         | 0.55%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 0.55%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 0.55%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 1         | 0.55%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 1         | 0.55%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 127       | 71.75%  |
| NVMe | 28        | 15.82%  |
| RAID | 14        | 7.91%   |
| IDE  | 8         | 4.52%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 154       | 95.06%  |
| AMD    | 8         | 4.94%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-4600U CPU @ 2.10GHz           | 6         | 3.7%    |
| Intel Core i7-8565U CPU @ 1.80GHz           | 5         | 3.09%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 5         | 3.09%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 4         | 2.47%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 4         | 2.47%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 4         | 2.47%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 4         | 2.47%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 1.85%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 3         | 1.85%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 3         | 1.85%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 3         | 1.85%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 3         | 1.85%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 3         | 1.85%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 1.23%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 1.23%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 2         | 1.23%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 2         | 1.23%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 2         | 1.23%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.23%   |
| Intel Core i5-4310U CPU @ 2.00GHz           | 2         | 1.23%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 2         | 1.23%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.23%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 2         | 1.23%   |
| Intel Core i5-3437U CPU @ 1.90GHz           | 2         | 1.23%   |
| Intel Core i5-3427U CPU @ 1.80GHz           | 2         | 1.23%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 1.23%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 2         | 1.23%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 2         | 1.23%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 1.23%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 1.23%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 2         | 1.23%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 2         | 1.23%   |
| Intel Core i3-4100M CPU @ 2.50GHz           | 2         | 1.23%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 2         | 1.23%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 2         | 1.23%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 2         | 1.23%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 2         | 1.23%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 2         | 1.23%   |
| Intel Celeron CPU 1007U @ 1.50GHz           | 2         | 1.23%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 2         | 1.23%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 52        | 32.1%   |
| Intel Core i7           | 43        | 26.54%  |
| Intel Celeron           | 16        | 9.88%   |
| Intel Core i3           | 15        | 9.26%   |
| Intel Atom              | 8         | 4.94%   |
| Intel Pentium           | 5         | 3.09%   |
| Other                   | 3         | 1.85%   |
| Intel Core i9           | 3         | 1.85%   |
| Intel Core 2 Duo        | 3         | 1.85%   |
| AMD Ryzen 5             | 3         | 1.85%   |
| Intel Pentium Dual-Core | 2         | 1.23%   |
| Intel Core 2            | 2         | 1.23%   |
| AMD Ryzen 7             | 2         | 1.23%   |
| AMD A10                 | 2         | 1.23%   |
| Intel Pentium Dual      | 1         | 0.62%   |
| Intel Core m3           | 1         | 0.62%   |
| AMD FX                  | 1         | 0.62%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 105       | 64.81%  |
| 4       | 45        | 27.78%  |
| 8       | 5         | 3.09%   |
| 6       | 4         | 2.47%   |
| 1       | 2         | 1.23%   |
| Unknown | 1         | 0.62%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 162       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 126       | 77.78%  |
| 1       | 35        | 21.6%   |
| Unknown | 1         | 0.62%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 160       | 98.77%  |
| 32-bit         | 2         | 1.23%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 39        | 23.35%  |
| 0x306a9    | 15        | 8.98%   |
| 0x40651    | 12        | 7.19%   |
| 0x206a7    | 12        | 7.19%   |
| 0x306c3    | 9         | 5.39%   |
| 0x406e3    | 8         | 4.79%   |
| 0x806ec    | 6         | 3.59%   |
| 0x806ea    | 6         | 3.59%   |
| 0x306d4    | 6         | 3.59%   |
| 0x30678    | 5         | 2.99%   |
| 0x20655    | 4         | 2.4%    |
| 0x806e9    | 3         | 1.8%    |
| 0x806c1    | 3         | 1.8%    |
| 0x706e5    | 3         | 1.8%    |
| 0x406c4    | 3         | 1.8%    |
| 0x1067a    | 3         | 1.8%    |
| 0x906ea    | 2         | 1.2%    |
| 0x906e9    | 2         | 1.2%    |
| 0x806eb    | 2         | 1.2%    |
| 0x706a8    | 2         | 1.2%    |
| 0x706a1    | 2         | 1.2%    |
| 0x6fd      | 2         | 1.2%    |
| 0x406c3    | 2         | 1.2%    |
| 0x106c2    | 2         | 1.2%    |
| 0xa0652    | 1         | 0.6%    |
| 0x906ec    | 1         | 0.6%    |
| 0x6fa      | 1         | 0.6%    |
| 0x6f6      | 1         | 0.6%    |
| 0x6f2      | 1         | 0.6%    |
| 0x506e3    | 1         | 0.6%    |
| 0x506c9    | 1         | 0.6%    |
| 0x30673    | 1         | 0.6%    |
| 0x0a50000d | 1         | 0.6%    |
| 0x08608103 | 1         | 0.6%    |
| 0x08600106 | 1         | 0.6%    |
| 0x08600103 | 1         | 0.6%    |
| 0x08108109 | 1         | 0.6%    |
| 0x0600611a | 1         | 0.6%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 32        | 19.75%  |
| Haswell       | 28        | 17.28%  |
| IvyBridge     | 16        | 9.88%   |
| Skylake       | 14        | 8.64%   |
| Silvermont    | 14        | 8.64%   |
| SandyBridge   | 12        | 7.41%   |
| Broadwell     | 7         | 4.32%   |
| IceLake       | 6         | 3.7%    |
| Westmere      | 5         | 3.09%   |
| Core          | 5         | 3.09%   |
| Goldmont plus | 4         | 2.47%   |
| TigerLake     | 3         | 1.85%   |
| Penryn        | 3         | 1.85%   |
| Zen 2         | 2         | 1.23%   |
| Goldmont      | 2         | 1.23%   |
| Excavator     | 2         | 1.23%   |
| Bonnell       | 2         | 1.23%   |
| Zen+          | 1         | 0.62%   |
| Zen 3         | 1         | 0.62%   |
| Steamroller   | 1         | 0.62%   |
| CometLake     | 1         | 0.62%   |
| Unknown       | 1         | 0.62%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 142       | 77.6%   |
| Nvidia | 21        | 11.48%  |
| AMD    | 20        | 10.93%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 17        | 9.04%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 16        | 8.51%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 11        | 5.85%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 10        | 5.32%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 10        | 5.32%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 5.32%   |
| Intel UHD Graphics 620                                                                   | 7         | 3.72%   |
| Intel HD Graphics 620                                                                    | 7         | 3.72%   |
| Intel HD Graphics 5500                                                                   | 7         | 3.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 3.72%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 3.72%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 3.19%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 2.13%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 2.13%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 2.13%   |
| Nvidia GP108M [GeForce MX250]                                                            | 3         | 1.6%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.6%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 1.6%    |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 2         | 1.06%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 1.06%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.06%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 1.06%   |
| Intel HD Graphics 500                                                                    | 2         | 1.06%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 1.06%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 1.06%   |
| AMD Renoir                                                                               | 2         | 1.06%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 1         | 0.53%   |
| Nvidia TU104BM [GeForce RTX 2080 Mobile]                                                 | 1         | 0.53%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.53%   |
| Nvidia GT218M [GeForce 315M]                                                             | 1         | 0.53%   |
| Nvidia GP108GLM [Quadro P500 Mobile]                                                     | 1         | 0.53%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.53%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                                  | 1         | 0.53%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.53%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 0.53%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.53%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.53%   |
| Nvidia GK107M [GeForce GT 750M]                                                          | 1         | 0.53%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 1         | 0.53%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 121       | 74.69%  |
| Intel + Nvidia | 14        | 8.64%   |
| 1 x AMD        | 12        | 7.41%   |
| 1 x Nvidia     | 7         | 4.32%   |
| Intel + AMD    | 7         | 4.32%   |
| 2 x AMD        | 1         | 0.62%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 155       | 94.51%  |
| Proprietary | 8         | 4.88%   |
| Unknown     | 1         | 0.61%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 131       | 79.39%  |
| 1.01-2.0   | 12        | 7.27%   |
| 0.01-0.5   | 11        | 6.67%   |
| 3.01-4.0   | 5         | 3.03%   |
| 7.01-8.0   | 4         | 2.42%   |
| 0.51-1.0   | 2         | 1.21%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 42        | 24.85%  |
| Chimei Innolux          | 31        | 18.34%  |
| BOE                     | 25        | 14.79%  |
| LG Display              | 24        | 14.2%   |
| Samsung Electronics     | 14        | 8.28%   |
| Hewlett-Packard         | 7         | 4.14%   |
| Sharp                   | 3         | 1.78%   |
| Chi Mei Optoelectronics | 3         | 1.78%   |
| Apple                   | 3         | 1.78%   |
| LG Philips              | 2         | 1.18%   |
| Lenovo                  | 2         | 1.18%   |
| KDC                     | 2         | 1.18%   |
| InfoVision              | 2         | 1.18%   |
| HannStar                | 2         | 1.18%   |
| Unknown (XXX)           | 1         | 0.59%   |
| Planar                  | 1         | 0.59%   |
| Eizo                    | 1         | 0.59%   |
| Dell                    | 1         | 0.59%   |
| CVT                     | 1         | 0.59%   |
| CSO                     | 1         | 0.59%   |
| Acer                    | 1         | 0.59%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 4         | 2.37%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                  | 3         | 1.78%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 1.78%   |
| Chimei Innolux LCD Monitor CMN14A3 1600x900 309x174mm 14.0-inch          | 3         | 1.78%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 3         | 1.78%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 3         | 1.78%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 3         | 1.78%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 1.18%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 2         | 1.18%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch              | 2         | 1.18%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 2         | 1.18%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 2         | 1.18%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch         | 2         | 1.18%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x173mm 13.9-inch          | 2         | 1.18%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 1.18%   |
| BOE LCD Monitor BOE0780 1920x1080 344x194mm 15.5-inch                    | 2         | 1.18%   |
| BOE LCD Monitor BOE0695 1920x1080 380x210mm 17.1-inch                    | 2         | 1.18%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch            | 2         | 1.18%   |
| AU Optronics LCD Monitor AUO223E 1600x900 309x174mm 14.0-inch            | 2         | 1.18%   |
| Unknown (XXX) LEDTV XXX0001 1366x768 575x323mm 26.0-inch                 | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch     | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 344x194mm 15.5-inch     | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch     | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch     | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SEC3051 1600x900 390x230mm 17.8-inch     | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch     | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SDC4942 1366x768 309x174mm 14.0-inch     | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SAM7017 3840x2160 1872x1053mm 84.6-inch  | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch     | 1         | 0.59%   |
| Planar PNR PL1910MW PNR1910 1440x900 410x257mm 19.1-inch                 | 1         | 0.59%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch              | 1         | 0.59%   |
| LG Philips LCD Monitor LPL0132 1280x800 304x190mm 14.1-inch              | 1         | 0.59%   |
| LG Display LCD Monitor LGD0619 1920x1080 309x174mm 14.0-inch             | 1         | 0.59%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch             | 1         | 0.59%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch             | 1         | 0.59%   |
| LG Display LCD Monitor LGD0532 1920x1080 344x194mm 15.5-inch             | 1         | 0.59%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 1         | 0.59%   |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch              | 1         | 0.59%   |
| LG Display LCD Monitor LGD04FD 1366x768 344x194mm 15.5-inch              | 1         | 0.59%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 81        | 49.39%  |
| 1920x1080 (FHD)    | 48        | 29.27%  |
| 1600x900 (HD+)     | 13        | 7.93%   |
| 1280x800 (WXGA)    | 4         | 2.44%   |
| 3840x2160 (4K)     | 3         | 1.83%   |
| 1920x1200 (WUXGA)  | 3         | 1.83%   |
| 1440x900 (WXGA+)   | 2         | 1.22%   |
| 1024x600           | 2         | 1.22%   |
| 3072x1920          | 1         | 0.61%   |
| 2560x1440 (QHD)    | 1         | 0.61%   |
| 2560x1080          | 1         | 0.61%   |
| 2160x1440          | 1         | 0.61%   |
| 1680x1050 (WSXGA+) | 1         | 0.61%   |
| 1360x768           | 1         | 0.61%   |
| 1280x1024 (SXGA)   | 1         | 0.61%   |
| Unknown            | 1         | 0.61%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 61        | 36.31%  |
| 14      | 37        | 22.02%  |
| 13      | 35        | 20.83%  |
| 11      | 6         | 3.57%   |
| 12      | 5         | 2.98%   |
| 17      | 4         | 2.38%   |
| 10      | 3         | 1.79%   |
| 23      | 2         | 1.19%   |
| 20      | 2         | 1.19%   |
| 18      | 2         | 1.19%   |
| 84      | 1         | 0.6%    |
| 46      | 1         | 0.6%    |
| 34      | 1         | 0.6%    |
| 31      | 1         | 0.6%    |
| 27      | 1         | 0.6%    |
| 26      | 1         | 0.6%    |
| 24      | 1         | 0.6%    |
| 21      | 1         | 0.6%    |
| 19      | 1         | 0.6%    |
| 16      | 1         | 0.6%    |
| Unknown | 1         | 0.6%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 121       | 72.02%  |
| 201-300     | 25        | 14.88%  |
| 351-400     | 7         | 4.17%   |
| 501-600     | 5         | 2.98%   |
| 401-500     | 5         | 2.98%   |
| 801-900     | 1         | 0.6%    |
| 601-700     | 1         | 0.6%    |
| 1501-2000   | 1         | 0.6%    |
| 901-1000    | 1         | 0.6%    |
| Unknown     | 1         | 0.6%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 142       | 88.75%  |
| 16/10   | 14        | 8.75%   |
| 5/4     | 1         | 0.63%   |
| 3/2     | 1         | 0.63%   |
| 21/9    | 1         | 0.63%   |
| Unknown | 1         | 0.63%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 61        | 36.31%  |
| 101-110        | 61        | 36.31%  |
| 71-80          | 11        | 6.55%   |
| 51-60          | 6         | 3.57%   |
| 61-70          | 5         | 2.98%   |
| 201-250        | 4         | 2.38%   |
| 41-50          | 3         | 1.79%   |
| 151-200        | 3         | 1.79%   |
| 141-150        | 3         | 1.79%   |
| 121-130        | 3         | 1.79%   |
| 351-500        | 2         | 1.19%   |
| More than 1000 | 1         | 0.6%    |
| 301-350        | 1         | 0.6%    |
| 251-300        | 1         | 0.6%    |
| 111-120        | 1         | 0.6%    |
| 501-1000       | 1         | 0.6%    |
| Unknown        | 1         | 0.6%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 68        | 40.48%  |
| 121-160       | 62        | 36.9%   |
| 51-100        | 23        | 13.69%  |
| 161-240       | 10        | 5.95%   |
| More than 240 | 2         | 1.19%   |
| 1-50          | 2         | 1.19%   |
| Unknown       | 1         | 0.6%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 142       | 86.06%  |
| 2     | 18        | 10.91%  |
| 0     | 4         | 2.42%   |
| 3     | 1         | 0.61%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 97        | 38.8%   |
| Realtek Semiconductor             | 68        | 27.2%   |
| Qualcomm Atheros                  | 40        | 16%     |
| Broadcom                          | 15        | 6%      |
| Hewlett-Packard                   | 5         | 2%      |
| Sierra Wireless                   | 3         | 1.2%    |
| Ralink                            | 3         | 1.2%    |
| MediaTek                          | 3         | 1.2%    |
| Marvell Technology Group          | 3         | 1.2%    |
| Huawei Technologies               | 3         | 1.2%    |
| ZTE WCDMA Technologies MSM        | 2         | 0.8%    |
| T & A Mobile Phones               | 2         | 0.8%    |
| Ralink Technology                 | 2         | 0.8%    |
| Spreadtrum Communications         | 1         | 0.4%    |
| Samsung Electronics               | 1         | 0.4%    |
| OPPO Electronics                  | 1         | 0.4%    |
| Ericsson Business Mobile Networks | 1         | 0.4%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 40        | 12.62%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 5.68%   |
| Intel Wireless 7260                                               | 18        | 5.68%   |
| Intel Ethernet Connection I218-LM                                 | 14        | 4.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13        | 4.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 12        | 3.79%   |
| Intel Ethernet Connection I219-LM                                 | 9         | 2.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 8         | 2.52%   |
| Intel Wireless 8260                                               | 8         | 2.52%   |
| Intel Wireless 7265                                               | 8         | 2.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 7         | 2.21%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 7         | 2.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 1.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 1.58%   |
| Intel Wireless 8265 / 8275                                        | 5         | 1.58%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 1.26%   |
| Intel Ethernet Connection I217-V                                  | 4         | 1.26%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 1.26%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 0.95%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 0.95%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 0.95%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.95%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.95%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 0.95%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.95%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 3         | 0.95%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 0.95%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 3         | 0.95%   |
| ZTE WCDMA MSM ZTE WCDMA MSM                                       | 2         | 0.63%   |
| T & A Mobile Phones ALCATEL ONETOUCH PIXI 3 (4)                   | 2         | 0.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.63%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.63%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.63%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.63%   |
| Ralink MT7601U Wireless Adapter                                   | 2         | 0.63%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.63%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.63%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 87        | 53.05%  |
| Qualcomm Atheros      | 35        | 21.34%  |
| Realtek Semiconductor | 18        | 10.98%  |
| Broadcom              | 13        | 7.93%   |
| Sierra Wireless       | 3         | 1.83%   |
| Ralink                | 3         | 1.83%   |
| Hewlett-Packard       | 3         | 1.83%   |
| Ralink Technology     | 2         | 1.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                            | 18        | 10.98%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 12        | 7.32%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 8         | 4.88%   |
| Intel Wireless 8260                                            | 8         | 4.88%   |
| Intel Wireless 7265                                            | 8         | 4.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 7         | 4.27%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 7         | 4.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 3.66%   |
| Intel Wireless 8265 / 8275                                     | 5         | 3.05%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 4         | 2.44%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 1.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3         | 1.83%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 1.83%   |
| Intel Wi-Fi 6 AX200                                            | 3         | 1.83%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 1.83%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 3         | 1.83%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 1.83%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 3         | 1.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.22%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 1.22%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 1.22%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 1.22%   |
| Ralink MT7601U Wireless Adapter                                | 2         | 1.22%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 1.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 1.22%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.22%   |
| Intel Wireless 3160                                            | 2         | 1.22%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.22%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 1.22%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 1.22%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.22%   |
| HP lt4112 Gobi 4G Module Network Device                        | 2         | 1.22%   |
| Sierra Wireless EM7455                                         | 1         | 0.61%   |
| Sierra Wireless EM7345 4G LTE                                  | 1         | 0.61%   |
| Sierra Wireless EM7305 Modem                                   | 1         | 0.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.61%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.61%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 0.61%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1         | 0.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 62        | 41.33%  |
| Intel                      | 60        | 40%     |
| Qualcomm Atheros           | 8         | 5.33%   |
| MediaTek                   | 3         | 2%      |
| Marvell Technology Group   | 3         | 2%      |
| Broadcom                   | 3         | 2%      |
| ZTE WCDMA Technologies MSM | 2         | 1.33%   |
| T & A Mobile Phones        | 2         | 1.33%   |
| Huawei Technologies        | 2         | 1.33%   |
| Hewlett-Packard            | 2         | 1.33%   |
| Spreadtrum Communications  | 1         | 0.67%   |
| Samsung Electronics        | 1         | 0.67%   |
| OPPO Electronics           | 1         | 0.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 40        | 26.49%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 11.92%  |
| Intel Ethernet Connection I218-LM                                 | 14        | 9.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13        | 8.61%   |
| Intel Ethernet Connection I219-LM                                 | 9         | 5.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 3.31%   |
| Intel Ethernet Connection I217-V                                  | 4         | 2.65%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 2.65%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.99%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 1.99%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.99%   |
| ZTE WCDMA MSM ZTE WCDMA MSM                                       | 2         | 1.32%   |
| T & A Mobile Phones ALCATEL ONETOUCH PIXI 3 (4)                   | 2         | 1.32%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.32%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 1.32%   |
| MediaTek Infinix NOTE 11                                          | 2         | 1.32%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.32%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 1.32%   |
| Huawei E353/E3131                                                 | 2         | 1.32%   |
| HP lt4120 Snapdragon X5 LTE                                       | 2         | 1.32%   |
| Spreadtrum Nokia G21                                              | 1         | 0.66%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.66%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.66%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.66%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.66%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.66%   |
| OPPO RMX3263                                                      | 1         | 0.66%   |
| MediaTek TECNO CAMON 18P                                          | 1         | 0.66%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.66%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.66%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.66%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.66%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.66%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.66%   |
| Broadcom NetXtreme BCM5753M Gigabit Ethernet PCI Express          | 1         | 0.66%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 0.66%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.66%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 156       | 52.7%   |
| Ethernet | 138       | 46.62%  |
| Modem    | 2         | 0.68%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 138       | 81.18%  |
| Ethernet | 32        | 18.82%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 127       | 78.4%   |
| 1     | 26        | 16.05%  |
| 0     | 7         | 4.32%   |
| 3     | 2         | 1.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 159       | 98.15%  |
| Yes  | 3         | 1.85%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 70        | 55.56%  |
| Qualcomm Atheros Communications | 21        | 16.67%  |
| Realtek Semiconductor           | 8         | 6.35%   |
| Broadcom                        | 8         | 6.35%   |
| IMC Networks                    | 4         | 3.17%   |
| Hewlett-Packard                 | 4         | 3.17%   |
| Lite-On Technology              | 3         | 2.38%   |
| Ralink                          | 2         | 1.59%   |
| Toshiba                         | 1         | 0.79%   |
| Realtek                         | 1         | 0.79%   |
| Foxconn / Hon Hai               | 1         | 0.79%   |
| Dell                            | 1         | 0.79%   |
| Apple                           | 1         | 0.79%   |
| Alps Electric                   | 1         | 0.79%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface               | 40        | 31.75%  |
| Qualcomm Atheros  Bluetooth Device               | 11        | 8.73%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 11        | 8.73%   |
| Intel AX201 Bluetooth                            | 7         | 5.56%   |
| Realtek Bluetooth Radio                          | 5         | 3.97%   |
| Intel Centrino Bluetooth Wireless Transceiver    | 4         | 3.17%   |
| Realtek  Bluetooth 4.2 Adapter                   | 3         | 2.38%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0            | 3         | 2.38%   |
| Intel AX200 Bluetooth                            | 3         | 2.38%   |
| IMC Networks Bluetooth Device                    | 3         | 2.38%   |
| HP Broadcom 2070 Bluetooth Combo                 | 3         | 2.38%   |
| Broadcom HP Portable SoftSailing                 | 3         | 2.38%   |
| Ralink RT3290 Bluetooth                          | 2         | 1.59%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0           | 2         | 1.59%   |
| Qualcomm Atheros AR3011 Bluetooth                | 2         | 1.59%   |
| Intel Wireless-AC 3168 Bluetooth                 | 2         | 1.59%   |
| Broadcom HP Portable Bumble Bee                  | 2         | 1.59%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]       | 2         | 1.59%   |
| Toshiba Atheros AR3012 Bluetooth                 | 1         | 0.79%   |
| Realtek Bluetooth Radio                          | 1         | 0.79%   |
| Qualcomm Atheros Bluetooth USB Host Controller   | 1         | 0.79%   |
| Qualcomm Atheros AR9462 Bluetooth                | 1         | 0.79%   |
| Qualcomm Atheros AR3012 Bluetooth                | 1         | 0.79%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth       | 1         | 0.79%   |
| Lite-On Bluetooth Device                         | 1         | 0.79%   |
| Lite-On Atheros Bluetooth                        | 1         | 0.79%   |
| Intel Wireless-AC 9260 Bluetooth Adapter         | 1         | 0.79%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 1         | 0.79%   |
| Intel AX210 Bluetooth                            | 1         | 0.79%   |
| IMC Networks Bluetooth                           | 1         | 0.79%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]    | 1         | 0.79%   |
| Foxconn / Hon Hai Bluetooth Device               | 1         | 0.79%   |
| Dell DW375 Bluetooth Module                      | 1         | 0.79%   |
| Broadcom BCM2070 Bluetooth Device                | 1         | 0.79%   |
| Apple Bluetooth HCI                              | 1         | 0.79%   |
| Alps Electric UGNZG                              | 1         | 0.79%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 147       | 84.97%  |
| AMD                         | 12        | 6.94%   |
| Nvidia                      | 8         | 4.62%   |
| Turtle Beach                | 1         | 0.58%   |
| Texas Instruments           | 1         | 0.58%   |
| Realtek Semiconductor       | 1         | 0.58%   |
| GN Netcom                   | 1         | 0.58%   |
| FiiO Electronics Technology | 1         | 0.58%   |
| Apple                       | 1         | 0.58%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 28        | 13.02%  |
| Intel Haswell-ULT HD Audio Controller                                                             | 17        | 7.91%   |
| Intel 8 Series HD Audio Controller                                                                | 17        | 7.91%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 16        | 7.44%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 12        | 5.58%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 11        | 5.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10        | 4.65%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 10        | 4.65%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 3.26%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 3.26%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 6         | 2.79%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 2.33%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 2.33%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 1.86%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.86%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.86%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.4%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 1.4%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.4%    |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.93%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.93%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 0.93%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 0.93%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 0.93%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.93%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2         | 0.93%   |
| Turtle Beach PX11 Headset                                                                         | 1         | 0.47%   |
| Texas Instruments PCM2912A Audio Codec                                                            | 1         | 0.47%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.47%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.47%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.47%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.47%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.47%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.47%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.47%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.47%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.47%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 35        | 34.65%  |
| SK hynix            | 23        | 22.77%  |
| Micron Technology   | 11        | 10.89%  |
| Unknown             | 9         | 8.91%   |
| Kingston            | 8         | 7.92%   |
| Ramaxel Technology  | 3         | 2.97%   |
| Crucial             | 3         | 2.97%   |
| Elpida              | 2         | 1.98%   |
| A-DATA Technology   | 2         | 1.98%   |
| Qimonda             | 1         | 0.99%   |
| Patriot             | 1         | 0.99%   |
| Nanya Technology    | 1         | 0.99%   |
| Avant               | 1         | 0.99%   |
| Unknown             | 1         | 0.99%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 4         | 3.88%   |
| Unknown RAM Module 1GB Row Of Chips LPDDR4 4267MT/s          | 3         | 2.91%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 3         | 2.91%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 3         | 2.91%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s  | 3         | 2.91%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s               | 2         | 1.94%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 1.94%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 1.94%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 2         | 1.94%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s     | 2         | 1.94%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 2         | 1.94%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 2         | 1.94%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 1.94%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s        | 2         | 1.94%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s      | 2         | 1.94%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                    | 1         | 0.97%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 1         | 0.97%   |
| Unknown RAM Module 2GB SODIMM DDR 800MT/s                    | 1         | 0.97%   |
| Unknown RAM Module 2048MB SODIMM DDR2                        | 1         | 0.97%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 1         | 0.97%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s         | 1         | 0.97%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 800MT/s     | 1         | 0.97%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.97%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s       | 1         | 0.97%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 0.97%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 1         | 0.97%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.97%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 1         | 0.97%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s       | 1         | 0.97%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s | 1         | 0.97%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s | 1         | 0.97%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8192MB SODIMM DDR4 3200MT/s    | 1         | 0.97%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s       | 1         | 0.97%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 1         | 0.97%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2400MT/s               | 1         | 0.97%   |
| Samsung RAM Module 4GB SODIMM DDR4 3200MT/s                  | 1         | 0.97%   |
| Samsung RAM Module 4GB Row Of Chips DDR4 2400MT/s            | 1         | 0.97%   |
| Samsung RAM Module 4096MB SODIMM DDR4 3200MT/s               | 1         | 0.97%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s        | 1         | 0.97%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s        | 1         | 0.97%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 38        | 46.91%  |
| DDR4   | 31        | 38.27%  |
| DDR2   | 5         | 6.17%   |
| LPDDR4 | 3         | 3.7%    |
| LPDDR3 | 2         | 2.47%   |
| SDRAM  | 1         | 1.23%   |
| DDR    | 1         | 1.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 72        | 84.71%  |
| Row Of Chips | 11        | 12.94%  |
| Chip         | 2         | 2.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 36        | 40.45%  |
| 8192  | 24        | 26.97%  |
| 2048  | 13        | 14.61%  |
| 16384 | 9         | 10.11%  |
| 1024  | 5         | 5.62%   |
| 32768 | 2         | 2.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 28        | 31.11%  |
| 2667    | 18        | 20%     |
| 3200    | 8         | 8.89%   |
| 1333    | 7         | 7.78%   |
| 2400    | 5         | 5.56%   |
| 2133    | 5         | 5.56%   |
| 1334    | 5         | 5.56%   |
| 4267    | 3         | 3.33%   |
| 667     | 3         | 3.33%   |
| 3266    | 2         | 2.22%   |
| 800     | 2         | 2.22%   |
| 8400    | 1         | 1.11%   |
| 4199    | 1         | 1.11%   |
| 1867    | 1         | 1.11%   |
| Unknown | 1         | 1.11%   |

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
| Chicony Electronics                    | 46        | 30.87%  |
| Cheng Uei Precision Industry (Foxlink) | 20        | 13.42%  |
| Acer                                   | 14        | 9.4%    |
| Syntek                                 | 8         | 5.37%   |
| Sunplus Innovation Technology          | 8         | 5.37%   |
| Realtek Semiconductor                  | 8         | 5.37%   |
| Microdia                               | 7         | 4.7%    |
| Lite-On Technology                     | 6         | 4.03%   |
| IMC Networks                           | 6         | 4.03%   |
| Silicon Motion                         | 3         | 2.01%   |
| Samsung Electronics                    | 3         | 2.01%   |
| Quanta                                 | 3         | 2.01%   |
| Suyin                                  | 2         | 1.34%   |
| Ricoh                                  | 2         | 1.34%   |
| Logitech                               | 2         | 1.34%   |
| Importek                               | 2         | 1.34%   |
| Apple                                  | 2         | 1.34%   |
| USB Camera                             | 1         | 0.67%   |
| Unknown                                | 1         | 0.67%   |
| Luxvisions Innotech Limited            | 1         | 0.67%   |
| LG Electronics                         | 1         | 0.67%   |
| DigiTech                               | 1         | 0.67%   |
| ALi                                    | 1         | 0.67%   |
| Alcor Micro                            | 1         | 0.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 10        | 6.67%   |
| Chicony HP HD Webcam                                                       | 7         | 4.67%   |
| Syntek Integrated Camera                                                   | 5         | 3.33%   |
| Chicony USB 2.0 Camera                                                     | 5         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 5         | 3.33%   |
| Acer Integrated Camera                                                     | 5         | 3.33%   |
| Realtek Integrated_Webcam_HD                                               | 4         | 2.67%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 4         | 2.67%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 4         | 2.67%   |
| Microdia Integrated_Webcam_HD                                              | 3         | 2%      |
| Lite-On HP HD Webcam                                                       | 3         | 2%      |
| Lite-On HP HD Camera                                                       | 3         | 2%      |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 3         | 2%      |
| Chicony HP HD Webcam [Fixed]                                               | 3         | 2%      |
| Chicony HD Webcam                                                          | 3         | 2%      |
| Syntek EasyCamera                                                          | 2         | 1.33%   |
| Sunplus Integrated_Webcam_HD                                               | 2         | 1.33%   |
| Sunplus HP HD Webcam [Fixed]                                               | 2         | 1.33%   |
| Samsung Galaxy A5 (MTP)                                                    | 2         | 1.33%   |
| Realtek Integrated Webcam                                                  | 2         | 1.33%   |
| Importek HP Webcam-50                                                      | 2         | 1.33%   |
| Chicony Integrated HP HD Webcam                                            | 2         | 1.33%   |
| Chicony HP Webcam [2 MP Macro]                                             | 2         | 1.33%   |
| Chicony HP Truevision HD                                                   | 2         | 1.33%   |
| Chicony HP HD Camera                                                       | 2         | 1.33%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed]                | 2         | 1.33%   |
| Acer ThinkPad P50 Integrated Camera                                        | 2         | 1.33%   |
| USB Camera USB Camera                                                      | 1         | 0.67%   |
| Unknown USB Camera                                                         | 1         | 0.67%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 0.67%   |
| Suyin HP Webcam                                                            | 1         | 0.67%   |
| Suyin Asus Integrated Webcam                                               | 1         | 0.67%   |
| Sunplus Laptop Integrated Webcam HD                                        | 1         | 0.67%   |
| Sunplus HP Wide Vision HD                                                  | 1         | 0.67%   |
| Sunplus HP TrueVision HD Camera                                            | 1         | 0.67%   |
| Sunplus HP Truevision HD                                                   | 1         | 0.67%   |
| Silicon Motion WebCam SC-13HDL11939N                                       | 1         | 0.67%   |
| Silicon Motion WebCam SC-10HDD12636N                                       | 1         | 0.67%   |
| Silicon Motion 300k Pixel Camera                                           | 1         | 0.67%   |
| Samsung Galaxy (debugging mode)                                            | 1         | 0.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 36        | 67.92%  |
| Synaptics                  | 10        | 18.87%  |
| Shenzhen Goodix Technology | 4         | 7.55%   |
| LighTuning Technology      | 1         | 1.89%   |
| Elan Microelectronics      | 1         | 1.89%   |
| AuthenTec                  | 1         | 1.89%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 15        | 28.3%   |
| Validity Sensors VFS491                                                    | 7         | 13.21%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 5.66%   |
| Synaptics WBDI Device                                                      | 3         | 5.66%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 5.66%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 3.77%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 3.77%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 3.77%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 3.77%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 3.77%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 3.77%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 3.77%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.89%   |
| Synaptics  WBDI                                                            | 1         | 1.89%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 1.89%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.89%   |
| Shenzhen Goodix  Fingerprint Device                                        | 1         | 1.89%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.89%   |
| Elan ELAN:ARM-M4                                                           | 1         | 1.89%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 1.89%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 44.44%  |
| Upek        | 2         | 22.22%  |
| Alcor Micro | 2         | 22.22%  |
| O2 Micro    | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 22.22%  |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 22.22%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 22.22%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 11.11%  |
| Broadcom 5880                                                                | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 95        | 57.93%  |
| 1     | 53        | 32.32%  |
| 2     | 15        | 9.15%   |
| 3     | 1         | 0.61%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 53        | 63.1%   |
| Graphics card            | 8         | 9.52%   |
| Chipcard                 | 8         | 9.52%   |
| Net/wireless             | 3         | 3.57%   |
| Camera                   | 3         | 3.57%   |
| Storage                  | 2         | 2.38%   |
| Net/ethernet             | 2         | 2.38%   |
| Communication controller | 2         | 2.38%   |
| Bluetooth                | 2         | 2.38%   |
| Sound                    | 1         | 1.19%   |

