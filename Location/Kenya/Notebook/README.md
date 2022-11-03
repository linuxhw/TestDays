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

Total: 227

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04        | 33        | 19.76%  |
| Ubuntu 18.04        | 15        | 8.98%   |
| Ubuntu 22.04        | 7         | 4.19%   |
| Zorin 16            | 6         | 3.59%   |
| Fedora 36           | 6         | 3.59%   |
| Manjaro             | 5         | 2.99%   |
| Zorin 15            | 4         | 2.4%    |
| Ubuntu 20.10        | 4         | 2.4%    |
| Ubuntu 19.04        | 4         | 2.4%    |
| Pop!_OS 20.04       | 4         | 2.4%    |
| OpenMandriva 4.2    | 4         | 2.4%    |
| Arch                | 4         | 2.4%    |
| Ubuntu 21.04        | 3         | 1.8%    |
| Q4OS 3              | 3         | 1.8%    |
| Linux Mint 20.3     | 3         | 1.8%    |
| Ubuntu 21.10        | 2         | 1.2%    |
| Ubuntu 19.10        | 2         | 1.2%    |
| Linux Mint 20.2     | 2         | 1.2%    |
| Linux Mint 19       | 2         | 1.2%    |
| Fedora 35           | 2         | 1.2%    |
| Fedora 32           | 2         | 1.2%    |
| Endless 3.9.4       | 2         | 1.2%    |
| Endless 3.9.2       | 2         | 1.2%    |
| Endless 3.9.1       | 2         | 1.2%    |
| Debian 11           | 2         | 1.2%    |
| Xubuntu 20.04       | 1         | 0.6%    |
| Ubuntu MATE 21.04   | 1         | 0.6%    |
| Ubuntu MATE 20.04   | 1         | 0.6%    |
| Ubuntu Budgie 20.04 | 1         | 0.6%    |
| Ubuntu 16.04        | 1         | 0.6%    |
| ROSA R11            | 1         | 0.6%    |
| ROSA R10            | 1         | 0.6%    |
| Pop!_OS 22.04       | 1         | 0.6%    |
| Pop!_OS 21.04       | 1         | 0.6%    |
| Pop!_OS 20.10       | 1         | 0.6%    |
| Parrot 5.1          | 1         | 0.6%    |
| Parrot 5.0          | 1         | 0.6%    |
| Parrot 4.9          | 1         | 0.6%    |
| Parrot 4.8          | 1         | 0.6%    |
| Parrot 4.7          | 1         | 0.6%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 66        | 42.04%  |
| Fedora        | 12        | 7.64%   |
| Zorin         | 10        | 6.37%   |
| Endless       | 8         | 5.1%    |
| Pop!_OS       | 7         | 4.46%   |
| Linux Mint    | 7         | 4.46%   |
| Manjaro       | 6         | 3.82%   |
| Arch          | 6         | 3.82%   |
| Parrot        | 5         | 3.18%   |
| OpenMandriva  | 5         | 3.18%   |
| Q4OS          | 3         | 1.91%   |
| Kali          | 3         | 1.91%   |
| Debian        | 3         | 1.91%   |
| Ubuntu MATE   | 2         | 1.27%   |
| ROSA          | 2         | 1.27%   |
| Elementary    | 2         | 1.27%   |
| Xubuntu       | 1         | 0.64%   |
| Ubuntu Budgie | 1         | 0.64%   |
| openSUSE      | 1         | 0.64%   |
| Nobara        | 1         | 0.64%   |
| Lubuntu       | 1         | 0.64%   |
| LMDE          | 1         | 0.64%   |
| KDE neon      | 1         | 0.64%   |
| Garuda Linux  | 1         | 0.64%   |
| BlackPanther  | 1         | 0.64%   |
| antiX         | 1         | 0.64%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.8.0-14-generic         | 6         | 3.33%   |
| 5.11.0-38-generic        | 4         | 2.22%   |
| 5.10.14-desktop-1omv4002 | 4         | 2.22%   |
| 5.4.0-58-generic         | 3         | 1.67%   |
| 5.4.0-52-generic         | 3         | 1.67%   |
| 5.4.0-45-generic         | 3         | 1.67%   |
| 5.4.0-42-generic         | 3         | 1.67%   |
| 5.15.0-41-generic        | 3         | 1.67%   |
| 4.19.0-17-amd64          | 3         | 1.67%   |
| 5.8.0-59-generic         | 2         | 1.11%   |
| 5.8.0-43-generic         | 2         | 1.11%   |
| 5.4.0-67-generic         | 2         | 1.11%   |
| 5.4.0-65-generic         | 2         | 1.11%   |
| 5.4.0-54-generic         | 2         | 1.11%   |
| 5.4.0-48-generic         | 2         | 1.11%   |
| 5.4.0-47-generic         | 2         | 1.11%   |
| 5.4.0-37-generic         | 2         | 1.11%   |
| 5.3.0-28-generic         | 2         | 1.11%   |
| 5.18.13-200.fc36.x86_64  | 2         | 1.11%   |
| 5.15.0-52-generic        | 2         | 1.11%   |
| 5.15.0-46-generic        | 2         | 1.11%   |
| 5.13.19-2-MANJARO        | 2         | 1.11%   |
| 5.13.0-27-generic        | 2         | 1.11%   |
| 5.11.0-37-generic        | 2         | 1.11%   |
| 5.11.0-34-generic        | 2         | 1.11%   |
| 5.9.14-arch1-1           | 1         | 0.56%   |
| 5.9.13-200.fc33.x86_64   | 1         | 0.56%   |
| 5.8.4-200.fc32.x86_64    | 1         | 0.56%   |
| 5.8.12-arch1-1           | 1         | 0.56%   |
| 5.8.0-63-generic         | 1         | 0.56%   |
| 5.8.0-55-generic         | 1         | 0.56%   |
| 5.8.0-51-generic         | 1         | 0.56%   |
| 5.8.0-50-generic         | 1         | 0.56%   |
| 5.8.0-48-generic         | 1         | 0.56%   |
| 5.8.0-44-generic         | 1         | 0.56%   |
| 5.8.0-41-generic         | 1         | 0.56%   |
| 5.8.0-29-generic         | 1         | 0.56%   |
| 5.8.0-26-generic         | 1         | 0.56%   |
| 5.8.0-25-generic         | 1         | 0.56%   |
| 5.7.17-2-MANJARO         | 1         | 0.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 35        | 20.47%  |
| 5.8.0   | 18        | 10.53%  |
| 5.11.0  | 13        | 7.6%    |
| 5.15.0  | 11        | 6.43%   |
| 4.15.0  | 11        | 6.43%   |
| 5.3.0   | 7         | 4.09%   |
| 5.13.0  | 7         | 4.09%   |
| 5.0.0   | 7         | 4.09%   |
| 5.10.14 | 4         | 2.34%   |
| 5.10.0  | 4         | 2.34%   |
| 4.19.0  | 4         | 2.34%   |
| 5.19.9  | 2         | 1.17%   |
| 5.18.13 | 2         | 1.17%   |
| 5.18.0  | 2         | 1.17%   |
| 5.17.5  | 2         | 1.17%   |
| 5.16.7  | 2         | 1.17%   |
| 5.13.19 | 2         | 1.17%   |
| 4.18.0  | 2         | 1.17%   |
| 5.9.14  | 1         | 0.58%   |
| 5.9.13  | 1         | 0.58%   |
| 5.8.4   | 1         | 0.58%   |
| 5.8.12  | 1         | 0.58%   |
| 5.7.17  | 1         | 0.58%   |
| 5.6.7   | 1         | 0.58%   |
| 5.6.5   | 1         | 0.58%   |
| 5.6.11  | 1         | 0.58%   |
| 5.5.0   | 1         | 0.58%   |
| 5.2.5   | 1         | 0.58%   |
| 5.2.0   | 1         | 0.58%   |
| 5.19.2  | 1         | 0.58%   |
| 5.19.15 | 1         | 0.58%   |
| 5.19.13 | 1         | 0.58%   |
| 5.19.0  | 1         | 0.58%   |
| 5.17.6  | 1         | 0.58%   |
| 5.17.4  | 1         | 0.58%   |
| 5.16.16 | 1         | 0.58%   |
| 5.16.14 | 1         | 0.58%   |
| 5.16.0  | 1         | 0.58%   |
| 5.15.13 | 1         | 0.58%   |
| 5.14.6  | 1         | 0.58%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 35        | 20.71%  |
| 5.8     | 20        | 11.83%  |
| 5.11    | 14        | 8.28%   |
| 5.15    | 12        | 7.1%    |
| 5.10    | 11        | 6.51%   |
| 4.15    | 11        | 6.51%   |
| 5.13    | 9         | 5.33%   |
| 5.0     | 8         | 4.73%   |
| 5.3     | 7         | 4.14%   |
| 5.19    | 6         | 3.55%   |
| 4.19    | 5         | 2.96%   |
| 5.18    | 4         | 2.37%   |
| 5.16    | 4         | 2.37%   |
| 5.6     | 3         | 1.78%   |
| 5.17    | 3         | 1.78%   |
| 5.14    | 3         | 1.78%   |
| 4.18    | 3         | 1.78%   |
| 5.9     | 2         | 1.18%   |
| 5.2     | 2         | 1.18%   |
| 4.9     | 2         | 1.18%   |
| 5.7     | 1         | 0.59%   |
| 5.5     | 1         | 0.59%   |
| 5.1     | 1         | 0.59%   |
| 4.16    | 1         | 0.59%   |
| 4.13    | 1         | 0.59%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 152       | 98.06%  |
| i686   | 3         | 1.94%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 97        | 61.01%  |
| Unknown    | 19        | 11.95%  |
| KDE5       | 14        | 8.81%   |
| X-Cinnamon | 8         | 5.03%   |
| MATE       | 6         | 3.77%   |
| XFCE       | 5         | 3.14%   |
| KDE        | 4         | 2.52%   |
| Pantheon   | 2         | 1.26%   |
| KDE4       | 2         | 1.26%   |
| LXQt       | 1         | 0.63%   |
| Cinnamon   | 1         | 0.63%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 117       | 74.05%  |
| Wayland | 31        | 19.62%  |
| Unknown | 10        | 6.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 92        | 57.86%  |
| GDM     | 27        | 16.98%  |
| SDDM    | 16        | 10.06%  |
| GDM3    | 13        | 8.18%   |
| TDM     | 5         | 3.14%   |
| LightDM | 4         | 2.52%   |
| KDM     | 2         | 1.26%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 112       | 71.34%  |
| Unknown | 23        | 14.65%  |
| en_GB   | 19        | 12.1%   |
| C       | 2         | 1.27%   |
| en_AG   | 1         | 0.64%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 90        | 56.96%  |
| EFI  | 68        | 43.04%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 130       | 83.87%  |
| Btrfs   | 13        | 8.39%   |
| Overlay | 9         | 5.81%   |
| Unknown | 2         | 1.29%   |
| Zfs     | 1         | 0.65%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 97        | 61.78%  |
| GPT     | 41        | 26.11%  |
| MBR     | 19        | 12.1%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 138       | 88.46%  |
| Yes       | 18        | 11.54%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 110       | 70.97%  |
| Yes       | 45        | 29.03%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 64        | 41.29%  |
| Lenovo                      | 31        | 20%     |
| Dell                        | 19        | 12.26%  |
| ASUSTek Computer            | 8         | 5.16%   |
| Toshiba                     | 7         | 4.52%   |
| Acer                        | 4         | 2.58%   |
| Samsung Electronics         | 3         | 1.94%   |
| Chuwi                       | 2         | 1.29%   |
| Apple                       | 2         | 1.29%   |
| TECNO                       | 1         | 0.65%   |
| Sony                        | 1         | 0.65%   |
| SLIMBOOK                    | 1         | 0.65%   |
| Panasonic                   | 1         | 0.65%   |
| Notebook                    | 1         | 0.65%   |
| Insyde                      | 1         | 0.65%   |
| I-Life Digital Technologies | 1         | 0.65%   |
| HUAWEI                      | 1         | 0.65%   |
| Getac                       | 1         | 0.65%   |
| EVOC                        | 1         | 0.65%   |
| EUROCOM                     | 1         | 0.65%   |
| Endless                     | 1         | 0.65%   |
| Eluktronics                 | 1         | 0.65%   |
| Clevo                       | 1         | 0.65%   |
| Unknown                     | 1         | 0.65%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| HP EliteBook 840 G1                     | 4         | 2.58%   |
| HP EliteBook Folio 9480m                | 3         | 1.94%   |
| HP EliteBook Folio 9470m                | 3         | 1.94%   |
| HP EliteBook 840 G3                     | 3         | 1.94%   |
| Dell XPS 13 9310                        | 3         | 1.94%   |
| Unknown                                 | 3         | 1.94%   |
| Toshiba Satellite C660                  | 2         | 1.29%   |
| HP ProBook 640 G1                       | 2         | 1.29%   |
| HP ProBook 440 G5                       | 2         | 1.29%   |
| HP Pavilion Laptop 15-cs3xxx            | 2         | 1.29%   |
| HP ENVY 15                              | 2         | 1.29%   |
| HP EliteBook 8440p                      | 2         | 1.29%   |
| HP EliteBook 840 G2                     | 2         | 1.29%   |
| HP Compaq Mini 110c-1100                | 2         | 1.29%   |
| HP 15 Notebook PC                       | 2         | 1.29%   |
| HP 15                                   | 2         | 1.29%   |
| Dell Inspiron 5767                      | 2         | 1.29%   |
| ASUS X540NA                             | 2         | 1.29%   |
| Toshiba TECRA A50-A                     | 1         | 0.65%   |
| Toshiba Satellite L50-B                 | 1         | 0.65%   |
| Toshiba R84SAU2                         | 1         | 0.65%   |
| Toshiba dynabook Satellite B554/M       | 1         | 0.65%   |
| Toshiba dynabook R731/E                 | 1         | 0.65%   |
| TECNO WinPad 2                          | 1         | 0.65%   |
| Sony VGN-NS295J                         | 1         | 0.65%   |
| SLIMBOOK PROX14-AMD                     | 1         | 0.65%   |
| Samsung RC410/RC510/RC710               | 1         | 0.65%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV | 1         | 0.65%   |
| Samsung 300E4C/300E5C/300E7C            | 1         | 0.65%   |
| Panasonic CF-SX2JDQZF5                  | 1         | 0.65%   |
| Notebook P65xHP                         | 1         | 0.65%   |
| Lenovo Z50-75 80EC                      | 1         | 0.65%   |
| Lenovo V330-14IKB 81B0                  | 1         | 0.65%   |
| Lenovo V310-15ISK 80SY                  | 1         | 0.65%   |
| Lenovo V14-IGL 82C2                     | 1         | 0.65%   |
| Lenovo V130-14IKB 81HQ                  | 1         | 0.65%   |
| Lenovo V110-15ISK 80TL                  | 1         | 0.65%   |
| Lenovo ThinkPad X250 20CLA21MJP         | 1         | 0.65%   |
| Lenovo ThinkPad X240 20AMS4J900         | 1         | 0.65%   |
| Lenovo ThinkPad X240 20AL00CQAU         | 1         | 0.65%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| HP EliteBook           | 24        | 15.48%  |
| Lenovo ThinkPad        | 17        | 10.97%  |
| HP ProBook             | 13        | 8.39%   |
| Dell Latitude          | 8         | 5.16%   |
| Dell Inspiron          | 8         | 5.16%   |
| Lenovo IdeaPad         | 7         | 4.52%   |
| HP Pavilion            | 6         | 3.87%   |
| HP ENVY                | 4         | 2.58%   |
| HP 15                  | 4         | 2.58%   |
| Acer Aspire            | 4         | 2.58%   |
| Toshiba Satellite      | 3         | 1.94%   |
| HP Laptop              | 3         | 1.94%   |
| Dell XPS               | 3         | 1.94%   |
| Unknown                | 3         | 1.94%   |
| Toshiba dynabook       | 2         | 1.29%   |
| HP Compaq              | 2         | 1.29%   |
| ASUS X540NA            | 2         | 1.29%   |
| Toshiba TECRA          | 1         | 0.65%   |
| Toshiba R84SAU2        | 1         | 0.65%   |
| TECNO WinPad           | 1         | 0.65%   |
| Sony VGN-NS295J        | 1         | 0.65%   |
| SLIMBOOK PROX14-AMD    | 1         | 0.65%   |
| Samsung RC410          | 1         | 0.65%   |
| Samsung 300E5EV        | 1         | 0.65%   |
| Samsung 300E4C         | 1         | 0.65%   |
| Panasonic CF-SX2JDQZF5 | 1         | 0.65%   |
| Notebook P65xHP        | 1         | 0.65%   |
| Lenovo Z50-75          | 1         | 0.65%   |
| Lenovo V330-14IKB      | 1         | 0.65%   |
| Lenovo V310-15ISK      | 1         | 0.65%   |
| Lenovo V14-IGL         | 1         | 0.65%   |
| Lenovo V130-14IKB      | 1         | 0.65%   |
| Lenovo V110-15ISK      | 1         | 0.65%   |
| Lenovo Legion          | 1         | 0.65%   |
| Insyde i101c           | 1         | 0.65%   |
| I-Life Digital ZED     | 1         | 0.65%   |
| HUAWEI NBLK-WAX9X      | 1         | 0.65%   |
| HP ZHAN                | 1         | 0.65%   |
| HP ZBook               | 1         | 0.65%   |
| HP Presario            | 1         | 0.65%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2013    | 19        | 12.26%  |
| 2016    | 17        | 10.97%  |
| 2019    | 15        | 9.68%   |
| 2018    | 15        | 9.68%   |
| 2015    | 13        | 8.39%   |
| 2014    | 13        | 8.39%   |
| 2017    | 12        | 7.74%   |
| 2012    | 12        | 7.74%   |
| 2011    | 10        | 6.45%   |
| 2020    | 9         | 5.81%   |
| 2010    | 9         | 5.81%   |
| 2021    | 2         | 1.29%   |
| 2009    | 2         | 1.29%   |
| 2008    | 2         | 1.29%   |
| 2007    | 2         | 1.29%   |
| 2006    | 2         | 1.29%   |
| Unknown | 1         | 0.65%   |

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
| Disabled | 144       | 91.72%  |
| Enabled  | 13        | 8.28%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 155       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 49        | 31.41%  |
| 4.01-8.0    | 45        | 28.85%  |
| 8.01-16.0   | 22        | 14.1%   |
| 16.01-24.0  | 16        | 10.26%  |
| 1.01-2.0    | 13        | 8.33%   |
| 32.01-64.0  | 5         | 3.21%   |
| 64.01-256.0 | 3         | 1.92%   |
| 24.01-32.0  | 1         | 0.64%   |
| 2.01-3.0    | 1         | 0.64%   |
| 0.51-1.0    | 1         | 0.64%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 51        | 29.48%  |
| 2.01-3.0  | 48        | 27.75%  |
| 3.01-4.0  | 29        | 16.76%  |
| 4.01-8.0  | 27        | 15.61%  |
| 0.51-1.0  | 15        | 8.67%   |
| 8.01-16.0 | 3         | 1.73%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 137       | 86.16%  |
| 2      | 18        | 11.32%  |
| 10     | 1         | 0.63%   |
| 8      | 1         | 0.63%   |
| 4      | 1         | 0.63%   |
| 3      | 1         | 0.63%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 95        | 61.29%  |
| Yes       | 60        | 38.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 134       | 86.45%  |
| No        | 21        | 13.55%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 149       | 96.13%  |
| No        | 6         | 3.87%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 119       | 75.8%   |
| No        | 38        | 24.2%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Kenya   | 155       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City     | Notebooks | Percent |
|----------|-----------|---------|
| Nairobi  | 144       | 90%     |
| Mombasa  | 3         | 1.88%   |
| Nakuru   | 2         | 1.25%   |
| Kiambu   | 2         | 1.25%   |
| Eldoret  | 2         | 1.25%   |
| Wote     | 1         | 0.63%   |
| Nyeri    | 1         | 0.63%   |
| Narok    | 1         | 0.63%   |
| Nanyuki  | 1         | 0.63%   |
| Maralal  | 1         | 0.63%   |
| Machakos | 1         | 0.63%   |
| Kisii    | 1         | 0.63%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 44        | 59     | 25.29%  |
| Toshiba             | 24        | 29     | 13.79%  |
| WDC                 | 21        | 27     | 12.07%  |
| Samsung Electronics | 17        | 26     | 9.77%   |
| HGST                | 12        | 20     | 6.9%    |
| Unknown             | 11        | 15     | 6.32%   |
| Hitachi             | 8         | 9      | 4.6%    |
| SanDisk             | 7         | 7      | 4.02%   |
| Crucial             | 6         | 8      | 3.45%   |
| Micron Technology   | 5         | 5      | 2.87%   |
| MARSHAL             | 3         | 3      | 1.72%   |
| SPCC                | 2         | 2      | 1.15%   |
| Kingston            | 2         | 4      | 1.15%   |
| TCSUNBOW            | 1         | 1      | 0.57%   |
| SK hynix            | 1         | 1      | 0.57%   |
| Plextor             | 1         | 1      | 0.57%   |
| Netac               | 1         | 1      | 0.57%   |
| Lexar               | 1         | 1      | 0.57%   |
| Intel               | 1         | 1      | 0.57%   |
| HUAWEI              | 1         | 1      | 0.57%   |
| Golden              | 1         | 1      | 0.57%   |
| Eluktro             | 1         | 1      | 0.57%   |
| CARLSTEIN           | 1         | 2      | 0.57%   |
| Apple               | 1         | 1      | 0.57%   |
| A-DATA Technology   | 1         | 1      | 0.57%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB         | 8         | 4.42%   |
| Seagate ST500LT012-9WS142 500GB        | 6         | 3.31%   |
| Toshiba MQ04ABF100 1TB                 | 5         | 2.76%   |
| HGST HTS725050A7E630 500GB             | 5         | 2.76%   |
| Samsung SSD 960 EVO 1TB                | 4         | 2.21%   |
| WDC PC SN730 NVMe 512GB                | 3         | 1.66%   |
| Unknown MMC Card  64GB                 | 3         | 1.66%   |
| Unknown MMC Card  32GB                 | 3         | 1.66%   |
| Toshiba MQ01ABF050 500GB               | 3         | 1.66%   |
| Toshiba MQ01ABD100 1TB                 | 3         | 1.66%   |
| Seagate ST9500325AS 500GB              | 3         | 1.66%   |
| Seagate ST500LT012-1DG142 500GB        | 3         | 1.66%   |
| Seagate ST500LM021-1KJ152 500GB        | 3         | 1.66%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 3         | 1.66%   |
| Crucial CT2050MX300SSD1 2TB            | 3         | 1.66%   |
| WDC WD5000LPCX-60VHAT0 500GB           | 2         | 1.1%    |
| WDC WD5000LPCX-24VHAT0 500GB           | 2         | 1.1%    |
| WDC WD2500BEKT-75PVMT0 250GB           | 2         | 1.1%    |
| WDC WD10SPZX-60Z10T0 1TB               | 2         | 1.1%    |
| Unknown NCard  32GB                    | 2         | 1.1%    |
| Seagate ST500VT000-1DK142 500GB        | 2         | 1.1%    |
| Seagate ST500LM030-1RK17D 500GB        | 2         | 1.1%    |
| Seagate ST250LT003-9YG14C 250GB        | 2         | 1.1%    |
| Seagate ST2000LM003 HN-M201RAD 2TB     | 2         | 1.1%    |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 2         | 1.1%    |
| Samsung NVMe SSD Drive 512GB           | 2         | 1.1%    |
| Hitachi HTS545032B9A300 320GB          | 2         | 1.1%    |
| HGST HTS541010A9E680 1TB               | 2         | 1.1%    |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 1         | 0.55%   |
| WDC WDS100T1B0A-00H9H0 1TB SSD         | 1         | 0.55%   |
| WDC WD5000LPVX-75V0TT0 500GB           | 1         | 0.55%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 1         | 0.55%   |
| WDC WD5000LPCX-24C6HT0 500GB           | 1         | 0.55%   |
| WDC WD5000LPCX-22VHAT1 500GB           | 1         | 0.55%   |
| WDC WD5000BPVT-60HXZT3 500GB           | 1         | 0.55%   |
| WDC WD3200BUCT-63TWBY0 320GB           | 1         | 0.55%   |
| WDC WD10JPVX-60JC3T0 1TB               | 1         | 0.55%   |
| WDC WD10JPCX-24UE4T0 1TB               | 1         | 0.55%   |
| Unknown MMC Card  4GB                  | 1         | 0.55%   |
| Unknown MMC Card  2GB                  | 1         | 0.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 44        | 59     | 42.72%  |
| Toshiba | 20        | 25     | 19.42%  |
| WDC     | 16        | 22     | 15.53%  |
| HGST    | 12        | 20     | 11.65%  |
| Hitachi | 8         | 9      | 7.77%   |
| MARSHAL | 3         | 3      | 2.91%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 7         | 7      | 21.21%  |
| Crucial             | 6         | 8      | 18.18%  |
| Samsung Electronics | 5         | 8      | 15.15%  |
| Micron Technology   | 3         | 3      | 9.09%   |
| WDC                 | 2         | 2      | 6.06%   |
| Kingston            | 2         | 4      | 6.06%   |
| Toshiba             | 1         | 1      | 3.03%   |
| TCSUNBOW            | 1         | 1      | 3.03%   |
| Plextor             | 1         | 1      | 3.03%   |
| Netac               | 1         | 1      | 3.03%   |
| Lexar               | 1         | 1      | 3.03%   |
| Golden              | 1         | 1      | 3.03%   |
| Eluktro             | 1         | 1      | 3.03%   |
| A-DATA Technology   | 1         | 1      | 3.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 100       | 138    | 57.8%   |
| SSD     | 33        | 40     | 19.08%  |
| NVMe    | 27        | 31     | 15.61%  |
| MMC     | 11        | 15     | 6.36%   |
| Unknown | 2         | 3      | 1.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 127       | 178    | 75.6%   |
| NVMe | 27        | 31     | 16.07%  |
| MMC  | 11        | 15     | 6.55%   |
| SAS  | 3         | 3      | 1.79%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 90        | 116    | 68.7%   |
| 0.51-1.0   | 36        | 47     | 27.48%  |
| 1.01-2.0   | 4         | 11     | 3.05%   |
| 3.01-4.0   | 1         | 4      | 0.76%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 49        | 30.63%  |
| 101-250        | 32        | 20%     |
| 501-1000       | 24        | 15%     |
| 51-100         | 17        | 10.63%  |
| 1-20           | 8         | 5%      |
| 21-50          | 7         | 4.38%   |
| 1001-2000      | 7         | 4.38%   |
| Unknown        | 7         | 4.38%   |
| 2001-3000      | 6         | 3.75%   |
| More than 3000 | 3         | 1.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 45        | 26.95%  |
| 21-50          | 31        | 18.56%  |
| 101-250        | 30        | 17.96%  |
| 51-100         | 22        | 13.17%  |
| 251-500        | 17        | 10.18%  |
| 501-1000       | 7         | 4.19%   |
| Unknown        | 7         | 4.19%   |
| 1001-2000      | 4         | 2.4%    |
| More than 3000 | 3         | 1.8%    |
| 2001-3000      | 1         | 0.6%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD2500BEKT-75PVMT0 250GB    | 2         | 2      | 9.52%   |
| Seagate ST500LT012-1DG142 500GB | 2         | 2      | 9.52%   |
| WDC WD10SPZX-60Z10T0 1TB        | 1         | 1      | 4.76%   |
| Toshiba MQ01ABF050 500GB        | 1         | 1      | 4.76%   |
| Toshiba MQ01ABD100 1TB          | 1         | 1      | 4.76%   |
| Toshiba MQ01ABD050V 500GB       | 1         | 1      | 4.76%   |
| Toshiba MK3263GSX 320GB         | 1         | 1      | 4.76%   |
| Toshiba MK3252GSX 320GB         | 1         | 1      | 4.76%   |
| Seagate ST9500325AS 500GB       | 1         | 1      | 4.76%   |
| Seagate ST500LT012-9WS142 500GB | 1         | 1      | 4.76%   |
| Seagate ST1000LM035-1RK172 1TB  | 1         | 1      | 4.76%   |
| MARSHAL MAL2750SA-T54 752GB     | 1         | 1      | 4.76%   |
| Hitachi HTS545032B9A300 320GB   | 1         | 1      | 4.76%   |
| Hitachi HTS542525K9SA00 250GB   | 1         | 1      | 4.76%   |
| HGST HTS725050A7E630 500GB      | 1         | 1      | 4.76%   |
| HGST HTS545050A7E380 500GB      | 1         | 1      | 4.76%   |
| HGST HTS541515A9E630 1TB        | 1         | 2      | 4.76%   |
| HGST HTS541010A9E680 1TB        | 1         | 2      | 4.76%   |
| Crucial CT2050MX300SSD1 2TB     | 1         | 2      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 5         | 5      | 25%     |
| Seagate | 5         | 5      | 25%     |
| WDC     | 3         | 3      | 15%     |
| HGST    | 3         | 6      | 15%     |
| Hitachi | 2         | 2      | 10%     |
| MARSHAL | 1         | 1      | 5%      |
| Crucial | 1         | 2      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 5         | 5      | 26.32%  |
| Seagate | 5         | 5      | 26.32%  |
| WDC     | 3         | 3      | 15.79%  |
| HGST    | 3         | 6      | 15.79%  |
| Hitachi | 2         | 2      | 10.53%  |
| MARSHAL | 1         | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 22     | 95%     |
| SSD  | 1         | 2      | 5%      |

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
| Detected | 100       | 141    | 64.1%   |
| Works    | 37        | 62     | 23.72%  |
| Malfunc  | 19        | 24     | 12.18%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 134       | 80.24%  |
| Samsung Electronics          | 14        | 8.38%   |
| AMD                          | 6         | 3.59%   |
| Toshiba America Info Systems | 3         | 1.8%    |
| SanDisk                      | 3         | 1.8%    |
| Silicon Motion               | 2         | 1.2%    |
| Micron Technology            | 2         | 1.2%    |
| SK hynix                     | 1         | 0.6%    |
| ASMedia Technology           | 1         | 0.6%    |
| Apple                        | 1         | 0.6%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 23        | 13.22%  |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 17        | 9.77%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 12        | 6.9%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 11        | 6.32%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 11        | 6.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 9         | 5.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 8         | 4.6%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 7         | 4.02%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 6         | 3.45%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 4         | 2.3%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 4         | 2.3%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 4         | 2.3%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 4         | 2.3%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 3         | 1.72%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 3         | 1.72%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 1.72%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 3         | 1.72%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 3         | 1.72%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 3         | 1.72%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 2         | 1.15%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 2         | 1.15%   |
| Samsung NVMe SSD Controller 980                                                        | 2         | 1.15%   |
| Micron Non-Volatile memory controller                                                  | 2         | 1.15%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 2         | 1.15%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 2         | 1.15%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 2         | 1.15%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 2         | 1.15%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 2         | 1.15%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 1         | 0.57%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 1         | 0.57%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 1         | 0.57%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 0.57%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 1         | 0.57%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 1         | 0.57%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 0.57%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 0.57%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 1         | 0.57%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 1         | 0.57%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 0.57%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 122       | 71.76%  |
| NVMe | 27        | 15.88%  |
| RAID | 13        | 7.65%   |
| IDE  | 8         | 4.71%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 148       | 95.48%  |
| AMD    | 7         | 4.52%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-4600U CPU @ 2.10GHz           | 6         | 3.87%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 5         | 3.23%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 5         | 3.23%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 4         | 2.58%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 4         | 2.58%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 1.94%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 3         | 1.94%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 3         | 1.94%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 3         | 1.94%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 3         | 1.94%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 3         | 1.94%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 3         | 1.94%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 3         | 1.94%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 1.29%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 1.29%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 2         | 1.29%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 2         | 1.29%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.29%   |
| Intel Core i5-4310U CPU @ 2.00GHz           | 2         | 1.29%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 2         | 1.29%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.29%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 2         | 1.29%   |
| Intel Core i5-3437U CPU @ 1.90GHz           | 2         | 1.29%   |
| Intel Core i5-3427U CPU @ 1.80GHz           | 2         | 1.29%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 1.29%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 2         | 1.29%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 1.29%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 1.29%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 2         | 1.29%   |
| Intel Core i3-4100M CPU @ 2.50GHz           | 2         | 1.29%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 2         | 1.29%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 2         | 1.29%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 2         | 1.29%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 2         | 1.29%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 2         | 1.29%   |
| Intel Celeron CPU 1007U @ 1.50GHz           | 2         | 1.29%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 2         | 1.29%   |
| Intel Atom CPU N270 @ 1.60GHz               | 2         | 1.29%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz      | 1         | 0.65%   |
| Intel Pentium CPU N3510 @ 1.99GHz           | 1         | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 49        | 31.61%  |
| Intel Core i7           | 41        | 26.45%  |
| Intel Celeron           | 16        | 10.32%  |
| Intel Core i3           | 14        | 9.03%   |
| Intel Atom              | 8         | 5.16%   |
| Intel Pentium           | 5         | 3.23%   |
| Other                   | 3         | 1.94%   |
| Intel Core i9           | 3         | 1.94%   |
| Intel Core 2 Duo        | 3         | 1.94%   |
| Intel Pentium Dual-Core | 2         | 1.29%   |
| Intel Core 2            | 2         | 1.29%   |
| AMD Ryzen 7             | 2         | 1.29%   |
| AMD Ryzen 5             | 2         | 1.29%   |
| AMD A10                 | 2         | 1.29%   |
| Intel Pentium Dual      | 1         | 0.65%   |
| Intel Core m3           | 1         | 0.65%   |
| AMD FX                  | 1         | 0.65%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 101       | 65.16%  |
| 4       | 43        | 27.74%  |
| 8       | 5         | 3.23%   |
| 6       | 3         | 1.94%   |
| 1       | 2         | 1.29%   |
| Unknown | 1         | 0.65%   |

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


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 119       | 76.77%  |
| 1       | 35        | 22.58%  |
| Unknown | 1         | 0.65%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 153       | 98.71%  |
| 32-bit         | 2         | 1.29%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 36        | 22.64%  |
| 0x306a9    | 13        | 8.18%   |
| 0x40651    | 12        | 7.55%   |
| 0x206a7    | 12        | 7.55%   |
| 0x306c3    | 9         | 5.66%   |
| 0x806ec    | 6         | 3.77%   |
| 0x806ea    | 6         | 3.77%   |
| 0x406e3    | 6         | 3.77%   |
| 0x306d4    | 6         | 3.77%   |
| 0x30678    | 5         | 3.14%   |
| 0x20655    | 4         | 2.52%   |
| 0x806e9    | 3         | 1.89%   |
| 0x806c1    | 3         | 1.89%   |
| 0x706e5    | 3         | 1.89%   |
| 0x406c4    | 3         | 1.89%   |
| 0x1067a    | 3         | 1.89%   |
| 0x906ea    | 2         | 1.26%   |
| 0x906e9    | 2         | 1.26%   |
| 0x806eb    | 2         | 1.26%   |
| 0x706a8    | 2         | 1.26%   |
| 0x706a1    | 2         | 1.26%   |
| 0x6fd      | 2         | 1.26%   |
| 0x406c3    | 2         | 1.26%   |
| 0x106c2    | 2         | 1.26%   |
| 0xa0652    | 1         | 0.63%   |
| 0x906ec    | 1         | 0.63%   |
| 0x6fa      | 1         | 0.63%   |
| 0x6f6      | 1         | 0.63%   |
| 0x6f2      | 1         | 0.63%   |
| 0x506e3    | 1         | 0.63%   |
| 0x506c9    | 1         | 0.63%   |
| 0x30673    | 1         | 0.63%   |
| 0x08608103 | 1         | 0.63%   |
| 0x08600106 | 1         | 0.63%   |
| 0x08600103 | 1         | 0.63%   |
| 0x08108109 | 1         | 0.63%   |
| 0x0600611a | 1         | 0.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 32        | 20.65%  |
| Haswell       | 28        | 18.06%  |
| Silvermont    | 14        | 9.03%   |
| IvyBridge     | 14        | 9.03%   |
| Skylake       | 12        | 7.74%   |
| SandyBridge   | 12        | 7.74%   |
| Broadwell     | 7         | 4.52%   |
| Westmere      | 5         | 3.23%   |
| Core          | 5         | 3.23%   |
| IceLake       | 4         | 2.58%   |
| Goldmont plus | 4         | 2.58%   |
| TigerLake     | 3         | 1.94%   |
| Penryn        | 3         | 1.94%   |
| Zen 2         | 2         | 1.29%   |
| Goldmont      | 2         | 1.29%   |
| Excavator     | 2         | 1.29%   |
| Bonnell       | 2         | 1.29%   |
| Zen+          | 1         | 0.65%   |
| Steamroller   | 1         | 0.65%   |
| CometLake     | 1         | 0.65%   |
| Unknown       | 1         | 0.65%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 136       | 77.71%  |
| Nvidia | 20        | 11.43%  |
| AMD    | 19        | 10.86%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 17        | 9.44%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 14        | 7.78%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 10        | 5.56%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 10        | 5.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 5.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 5%      |
| Intel UHD Graphics 620                                                                   | 7         | 3.89%   |
| Intel HD Graphics 620                                                                    | 7         | 3.89%   |
| Intel HD Graphics 5500                                                                   | 7         | 3.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 3.89%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 3.89%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 3.33%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 2.22%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 2.22%   |
| Nvidia GP108M [GeForce MX250]                                                            | 3         | 1.67%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.67%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 1.67%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 1.67%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 2         | 1.11%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 1.11%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.11%   |
| Intel HD Graphics 500                                                                    | 2         | 1.11%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 1.11%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 1.11%   |
| AMD Renoir                                                                               | 2         | 1.11%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 1         | 0.56%   |
| Nvidia TU104BM [GeForce RTX 2080 Mobile]                                                 | 1         | 0.56%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.56%   |
| Nvidia GT218M [GeForce 315M]                                                             | 1         | 0.56%   |
| Nvidia GP108GLM [Quadro P500 Mobile]                                                     | 1         | 0.56%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.56%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                                  | 1         | 0.56%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.56%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 0.56%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.56%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.56%   |
| Nvidia GK107M [GeForce GT 750M]                                                          | 1         | 0.56%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 1         | 0.56%   |
| Nvidia G84M [GeForce 8600M GT]                                                           | 1         | 0.56%   |
| Nvidia G72M [GeForce Go 7400]                                                            | 1         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 116       | 74.84%  |
| Intel + Nvidia | 13        | 8.39%   |
| 1 x AMD        | 11        | 7.1%    |
| 1 x Nvidia     | 7         | 4.52%   |
| Intel + AMD    | 7         | 4.52%   |
| 2 x AMD        | 1         | 0.65%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 148       | 94.27%  |
| Proprietary | 8         | 5.1%    |
| Unknown     | 1         | 0.64%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 125       | 79.11%  |
| 1.01-2.0   | 12        | 7.59%   |
| 0.01-0.5   | 10        | 6.33%   |
| 3.01-4.0   | 5         | 3.16%   |
| 7.01-8.0   | 4         | 2.53%   |
| 0.51-1.0   | 2         | 1.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 39        | 24.07%  |
| Chimei Innolux          | 30        | 18.52%  |
| LG Display              | 24        | 14.81%  |
| BOE                     | 24        | 14.81%  |
| Samsung Electronics     | 12        | 7.41%   |
| Hewlett-Packard         | 7         | 4.32%   |
| Sharp                   | 3         | 1.85%   |
| Chi Mei Optoelectronics | 3         | 1.85%   |
| Apple                   | 3         | 1.85%   |
| LG Philips              | 2         | 1.23%   |
| Lenovo                  | 2         | 1.23%   |
| KDC                     | 2         | 1.23%   |
| InfoVision              | 2         | 1.23%   |
| HannStar                | 2         | 1.23%   |
| Unknown (XXX)           | 1         | 0.62%   |
| Planar                  | 1         | 0.62%   |
| Eizo                    | 1         | 0.62%   |
| Dell                    | 1         | 0.62%   |
| CVT                     | 1         | 0.62%   |
| CSO                     | 1         | 0.62%   |
| Acer                    | 1         | 0.62%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 4         | 2.47%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                  | 3         | 1.85%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 1.85%   |
| Chimei Innolux LCD Monitor CMN14A3 1600x900 309x174mm 14.0-inch          | 3         | 1.85%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 3         | 1.85%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 1.23%   |
| LG Display LCD Monitor LGD045E 1366x768 309x174mm 14.0-inch              | 2         | 1.23%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 2         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 2         | 1.23%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch         | 2         | 1.23%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x173mm 13.9-inch          | 2         | 1.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 1.23%   |
| BOE LCD Monitor BOE0780 1920x1080 344x194mm 15.5-inch                    | 2         | 1.23%   |
| BOE LCD Monitor BOE0695 1920x1080 380x210mm 17.1-inch                    | 2         | 1.23%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch            | 2         | 1.23%   |
| AU Optronics LCD Monitor AUO223E 1600x900 309x174mm 14.0-inch            | 2         | 1.23%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 2         | 1.23%   |
| Unknown (XXX) LEDTV XXX0001 1366x768 575x323mm 26.0-inch                 | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch     | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 344x194mm 15.5-inch     | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch     | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC3051 1366x768 344x194mm 15.5-inch     | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch     | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SDC4942 1366x768 309x174mm 14.0-inch     | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SAM7017 3840x2160 950x540mm 43.0-inch    | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SAM0C3C 1360x768 609x347mm 27.6-inch     | 1         | 0.62%   |
| Planar PNR PL1910MW PNR1910 1440x900 410x257mm 19.1-inch                 | 1         | 0.62%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch              | 1         | 0.62%   |
| LG Philips LCD Monitor LPL0132 1280x800 304x190mm 14.1-inch              | 1         | 0.62%   |
| LG Display LCD Monitor LGD0619 1920x1080 309x174mm 14.0-inch             | 1         | 0.62%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch             | 1         | 0.62%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch             | 1         | 0.62%   |
| LG Display LCD Monitor LGD0532 1920x1080 344x194mm 15.5-inch             | 1         | 0.62%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 1         | 0.62%   |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch              | 1         | 0.62%   |
| LG Display LCD Monitor LGD04FD 1366x768 344x194mm 15.5-inch              | 1         | 0.62%   |
| LG Display LCD Monitor LGD0493 1366x768 344x194mm 15.5-inch              | 1         | 0.62%   |
| LG Display LCD Monitor LGD048B 1366x768 309x174mm 14.0-inch              | 1         | 0.62%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 79        | 50.32%  |
| 1920x1080 (FHD)    | 44        | 28.03%  |
| 1600x900 (HD+)     | 12        | 7.64%   |
| 1280x800 (WXGA)    | 4         | 2.55%   |
| 3840x2160 (4K)     | 3         | 1.91%   |
| 1920x1200 (WUXGA)  | 3         | 1.91%   |
| 1440x900 (WXGA+)   | 2         | 1.27%   |
| 1024x600           | 2         | 1.27%   |
| 3072x1920          | 1         | 0.64%   |
| 2560x1440 (QHD)    | 1         | 0.64%   |
| 2560x1080          | 1         | 0.64%   |
| 2160x1440          | 1         | 0.64%   |
| 1680x1050 (WSXGA+) | 1         | 0.64%   |
| 1360x768           | 1         | 0.64%   |
| 1280x1024 (SXGA)   | 1         | 0.64%   |
| Unknown            | 1         | 0.64%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 58        | 36.02%  |
| 14      | 35        | 21.74%  |
| 13      | 33        | 20.5%   |
| 11      | 6         | 3.73%   |
| 12      | 5         | 3.11%   |
| 17      | 4         | 2.48%   |
| 23      | 3         | 1.86%   |
| 10      | 3         | 1.86%   |
| 20      | 2         | 1.24%   |
| 18      | 2         | 1.24%   |
| 84      | 1         | 0.62%   |
| 46      | 1         | 0.62%   |
| 34      | 1         | 0.62%   |
| 31      | 1         | 0.62%   |
| 27      | 1         | 0.62%   |
| 26      | 1         | 0.62%   |
| 21      | 1         | 0.62%   |
| 19      | 1         | 0.62%   |
| 16      | 1         | 0.62%   |
| Unknown | 1         | 0.62%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 116       | 72.05%  |
| 201-300     | 24        | 14.91%  |
| 351-400     | 6         | 3.73%   |
| 501-600     | 5         | 3.11%   |
| 401-500     | 5         | 3.11%   |
| 801-900     | 1         | 0.62%   |
| 601-700     | 1         | 0.62%   |
| 1501-2000   | 1         | 0.62%   |
| 901-1000    | 1         | 0.62%   |
| Unknown     | 1         | 0.62%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 135       | 88.24%  |
| 16/10   | 14        | 9.15%   |
| 5/4     | 1         | 0.65%   |
| 3/2     | 1         | 0.65%   |
| 21/9    | 1         | 0.65%   |
| Unknown | 1         | 0.65%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 58        | 36.02%  |
| 101-110        | 58        | 36.02%  |
| 71-80          | 10        | 6.21%   |
| 51-60          | 6         | 3.73%   |
| 61-70          | 5         | 3.11%   |
| 201-250        | 4         | 2.48%   |
| 41-50          | 3         | 1.86%   |
| 151-200        | 3         | 1.86%   |
| 141-150        | 3         | 1.86%   |
| 121-130        | 3         | 1.86%   |
| 351-500        | 2         | 1.24%   |
| More than 1000 | 1         | 0.62%   |
| 301-350        | 1         | 0.62%   |
| 251-300        | 1         | 0.62%   |
| 111-120        | 1         | 0.62%   |
| 501-1000       | 1         | 0.62%   |
| Unknown        | 1         | 0.62%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 66        | 40.99%  |
| 121-160       | 58        | 36.02%  |
| 51-100        | 22        | 13.66%  |
| 161-240       | 10        | 6.21%   |
| More than 240 | 2         | 1.24%   |
| 1-50          | 2         | 1.24%   |
| Unknown       | 1         | 0.62%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 135       | 85.44%  |
| 2     | 18        | 11.39%  |
| 0     | 4         | 2.53%   |
| 3     | 1         | 0.63%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 92        | 38.17%  |
| Realtek Semiconductor             | 66        | 27.39%  |
| Qualcomm Atheros                  | 38        | 15.77%  |
| Broadcom                          | 15        | 6.22%   |
| Hewlett-Packard                   | 5         | 2.07%   |
| Sierra Wireless                   | 3         | 1.24%   |
| Ralink                            | 3         | 1.24%   |
| MediaTek                          | 3         | 1.24%   |
| Marvell Technology Group          | 3         | 1.24%   |
| Huawei Technologies               | 3         | 1.24%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.83%   |
| T & A Mobile Phones               | 2         | 0.83%   |
| Ralink Technology                 | 2         | 0.83%   |
| Spreadtrum Communications         | 1         | 0.41%   |
| Samsung Electronics               | 1         | 0.41%   |
| OPPO Electronics                  | 1         | 0.41%   |
| Ericsson Business Mobile Networks | 1         | 0.41%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 39        | 12.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 5.88%   |
| Intel Wireless 7260                                               | 18        | 5.88%   |
| Intel Ethernet Connection I218-LM                                 | 14        | 4.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 11        | 3.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 3.59%   |
| Intel Wireless 7265                                               | 8         | 2.61%   |
| Intel Ethernet Connection I219-LM                                 | 8         | 2.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 2.29%   |
| Intel Wireless 8260                                               | 7         | 2.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 7         | 2.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 1.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 1.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 1.63%   |
| Intel Wireless 8265 / 8275                                        | 5         | 1.63%   |
| Intel Ethernet Connection I217-V                                  | 4         | 1.31%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 1.31%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 0.98%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 0.98%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 0.98%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.98%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.98%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.98%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 0.98%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.98%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 3         | 0.98%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 0.98%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 3         | 0.98%   |
| ZTE WCDMA MSM ZTE MSM                                             | 2         | 0.65%   |
| T & A Mobile Phones ALCATEL ONETOUCH PIXI 3 (4)                   | 2         | 0.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.65%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.65%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.65%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.65%   |
| Ralink MT7601U Wireless Adapter                                   | 2         | 0.65%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.65%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.65%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.65%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 83        | 52.87%  |
| Qualcomm Atheros      | 33        | 21.02%  |
| Realtek Semiconductor | 17        | 10.83%  |
| Broadcom              | 13        | 8.28%   |
| Sierra Wireless       | 3         | 1.91%   |
| Ralink                | 3         | 1.91%   |
| Hewlett-Packard       | 3         | 1.91%   |
| Ralink Technology     | 2         | 1.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                            | 18        | 11.46%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 11        | 7.01%   |
| Intel Wireless 7265                                            | 8         | 5.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 7         | 4.46%   |
| Intel Wireless 8260                                            | 7         | 4.46%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 7         | 4.46%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 3.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 3.82%   |
| Intel Wireless 8265 / 8275                                     | 5         | 3.18%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 1.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3         | 1.91%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 1.91%   |
| Intel Wi-Fi 6 AX200                                            | 3         | 1.91%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 3         | 1.91%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 1.91%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 3         | 1.91%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 1.91%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 3         | 1.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.27%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 1.27%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 1.27%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 1.27%   |
| Ralink MT7601U Wireless Adapter                                | 2         | 1.27%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 1.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 1.27%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.27%   |
| Intel Wireless 3160                                            | 2         | 1.27%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 1.27%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 1.27%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.27%   |
| HP lt4112 Gobi 4G Module Network Device                        | 2         | 1.27%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A            | 1         | 0.64%   |
| Sierra Wireless EM7345 4G LTE                                  | 1         | 0.64%   |
| Sierra Wireless EM7305 Modem                                   | 1         | 0.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.64%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.64%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 0.64%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1         | 0.64%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.64%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 61        | 41.78%  |
| Intel                      | 57        | 39.04%  |
| Qualcomm Atheros           | 8         | 5.48%   |
| MediaTek                   | 3         | 2.05%   |
| Marvell Technology Group   | 3         | 2.05%   |
| Broadcom                   | 3         | 2.05%   |
| ZTE WCDMA Technologies MSM | 2         | 1.37%   |
| T & A Mobile Phones        | 2         | 1.37%   |
| Huawei Technologies        | 2         | 1.37%   |
| Hewlett-Packard            | 2         | 1.37%   |
| Spreadtrum Communications  | 1         | 0.68%   |
| Samsung Electronics        | 1         | 0.68%   |
| OPPO Electronics           | 1         | 0.68%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 39        | 26.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 12.24%  |
| Intel Ethernet Connection I218-LM                                 | 14        | 9.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 7.48%   |
| Intel Ethernet Connection I219-LM                                 | 8         | 5.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 3.4%    |
| Intel Ethernet Connection I217-V                                  | 4         | 2.72%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 2.72%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 2.04%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 2.04%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 2.04%   |
| ZTE WCDMA MSM ZTE MSM                                             | 2         | 1.36%   |
| T & A Mobile Phones ALCATEL ONETOUCH PIXI 3 (4)                   | 2         | 1.36%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.36%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 1.36%   |
| MediaTek TECNO Pouvoir 3 Air                                      | 2         | 1.36%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.36%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 1.36%   |
| Huawei E353/E3131                                                 | 2         | 1.36%   |
| HP HP lt4120 Snapdragon X5 LTE                                    | 2         | 1.36%   |
| Spreadtrum Spreadtrum Phone                                       | 1         | 0.68%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.68%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.68%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.68%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.68%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.68%   |
| OPPO RMX2180                                                      | 1         | 0.68%   |
| MediaTek moto e(7) power                                          | 1         | 0.68%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.68%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.68%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.68%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.68%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.68%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.68%   |
| Broadcom NetXtreme BCM5753M Gigabit Ethernet PCI Express          | 1         | 0.68%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 0.68%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.68%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 149       | 52.28%  |
| Ethernet | 134       | 47.02%  |
| Modem    | 2         | 0.7%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 131       | 81.37%  |
| Ethernet | 30        | 18.63%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 124       | 80%     |
| 1     | 23        | 14.84%  |
| 0     | 7         | 4.52%   |
| 3     | 1         | 0.65%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 152       | 98.06%  |
| Yes  | 3         | 1.94%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 67        | 56.3%   |
| Qualcomm Atheros Communications | 20        | 16.81%  |
| Realtek Semiconductor           | 7         | 5.88%   |
| Broadcom                        | 6         | 5.04%   |
| IMC Networks                    | 4         | 3.36%   |
| Hewlett-Packard                 | 4         | 3.36%   |
| Lite-On Technology              | 3         | 2.52%   |
| Ralink                          | 2         | 1.68%   |
| Toshiba                         | 1         | 0.84%   |
| Realtek                         | 1         | 0.84%   |
| Foxconn / Hon Hai               | 1         | 0.84%   |
| Dell                            | 1         | 0.84%   |
| Apple                           | 1         | 0.84%   |
| Alps Electric                   | 1         | 0.84%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface               | 39        | 32.77%  |
| Qualcomm Atheros  Bluetooth Device               | 10        | 8.4%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 10        | 8.4%    |
| Intel AX201 Bluetooth                            | 7         | 5.88%   |
| Realtek Bluetooth Radio                          | 4         | 3.36%   |
| Intel Centrino Bluetooth Wireless Transceiver    | 4         | 3.36%   |
| Realtek  Bluetooth 4.2 Adapter                   | 3         | 2.52%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0            | 3         | 2.52%   |
| Intel AX200 Bluetooth                            | 3         | 2.52%   |
| IMC Networks Bluetooth Device                    | 3         | 2.52%   |
| HP Broadcom 2070 Bluetooth Combo                 | 3         | 2.52%   |
| Ralink RT3290 Bluetooth                          | 2         | 1.68%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0           | 2         | 1.68%   |
| Qualcomm Atheros AR3011 Bluetooth                | 2         | 1.68%   |
| Broadcom HP Portable SoftSailing                 | 2         | 1.68%   |
| Broadcom HP Portable Bumble Bee                  | 2         | 1.68%   |
| Toshiba Atheros AR3012 Bluetooth                 | 1         | 0.84%   |
| Realtek Bluetooth Radio                          | 1         | 0.84%   |
| Qualcomm Atheros Bluetooth USB Host Controller   | 1         | 0.84%   |
| Qualcomm Atheros AR9462 Bluetooth                | 1         | 0.84%   |
| Qualcomm Atheros AR3012 Bluetooth                | 1         | 0.84%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth       | 1         | 0.84%   |
| Lite-On Bluetooth Device                         | 1         | 0.84%   |
| Lite-On Atheros Bluetooth                        | 1         | 0.84%   |
| Intel Wireless-AC 9260 Bluetooth Adapter         | 1         | 0.84%   |
| Intel Wireless-AC 3168 Bluetooth                 | 1         | 0.84%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 1         | 0.84%   |
| Intel AX210 Bluetooth                            | 1         | 0.84%   |
| IMC Networks Bluetooth                           | 1         | 0.84%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]    | 1         | 0.84%   |
| Foxconn / Hon Hai Bluetooth Device               | 1         | 0.84%   |
| Dell DW375 Bluetooth Module                      | 1         | 0.84%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]       | 1         | 0.84%   |
| Broadcom BCM2070 Bluetooth Device                | 1         | 0.84%   |
| Apple Bluetooth HCI                              | 1         | 0.84%   |
| Alps Electric UGNZG                              | 1         | 0.84%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 141       | 84.94%  |
| AMD                         | 11        | 6.63%   |
| Nvidia                      | 8         | 4.82%   |
| Turtle Beach                | 1         | 0.6%    |
| Texas Instruments           | 1         | 0.6%    |
| Realtek Semiconductor       | 1         | 0.6%    |
| GN Netcom                   | 1         | 0.6%    |
| FiiO Electronics Technology | 1         | 0.6%    |
| Apple                       | 1         | 0.6%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 26        | 12.56%  |
| Intel Haswell-ULT HD Audio Controller                                                             | 17        | 8.21%   |
| Intel 8 Series HD Audio Controller                                                                | 17        | 8.21%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 6.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 12        | 5.8%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 11        | 5.31%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10        | 4.83%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 10        | 4.83%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 3.38%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 3.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 2.42%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 1.93%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.93%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.93%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 4         | 1.93%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.45%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 1.45%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.45%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 1.45%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.97%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.97%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 0.97%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 0.97%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 0.97%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.97%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2         | 0.97%   |
| Turtle Beach PX11 Headset                                                                         | 1         | 0.48%   |
| Texas Instruments PCM2912A Audio Codec                                                            | 1         | 0.48%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.48%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.48%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.48%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.48%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.48%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.48%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.48%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.48%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.48%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.48%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 31        | 34.07%  |
| SK hynix            | 19        | 20.88%  |
| Micron Technology   | 10        | 10.99%  |
| Unknown             | 9         | 9.89%   |
| Kingston            | 8         | 8.79%   |
| Ramaxel Technology  | 3         | 3.3%    |
| Crucial             | 3         | 3.3%    |
| A-DATA Technology   | 2         | 2.2%    |
| Qimonda             | 1         | 1.1%    |
| Patriot             | 1         | 1.1%    |
| Nanya Technology    | 1         | 1.1%    |
| Elpida              | 1         | 1.1%    |
| Avant               | 1         | 1.1%    |
| Unknown             | 1         | 1.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 4         | 4.3%    |
| Unknown RAM Module 1GB Row Of Chips LPDDR4 4267MT/s          | 3         | 3.23%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 3         | 3.23%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s               | 2         | 2.15%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 2.15%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 2.15%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 2         | 2.15%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 2         | 2.15%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 2         | 2.15%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 2         | 2.15%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s  | 2         | 2.15%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 2.15%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s        | 2         | 2.15%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s      | 2         | 2.15%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                    | 1         | 1.08%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 1         | 1.08%   |
| Unknown RAM Module 2GB SODIMM DDR 800MT/s                    | 1         | 1.08%   |
| Unknown RAM Module 2048MB SODIMM DDR2                        | 1         | 1.08%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s         | 1         | 1.08%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 800MT/s     | 1         | 1.08%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.08%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 1         | 1.08%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 1         | 1.08%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s       | 1         | 1.08%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 1.08%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.08%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 1         | 1.08%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s       | 1         | 1.08%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s | 1         | 1.08%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s | 1         | 1.08%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s       | 1         | 1.08%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2400MT/s               | 1         | 1.08%   |
| Samsung RAM Module 4GB SODIMM DDR4 3200MT/s                  | 1         | 1.08%   |
| Samsung RAM Module 4GB Row Of Chips DDR4 2400MT/s            | 1         | 1.08%   |
| Samsung RAM Module 4096MB SODIMM DDR4 3200MT/s               | 1         | 1.08%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s        | 1         | 1.08%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s        | 1         | 1.08%   |
| Samsung RAM M471B5674BH0-YH9 2GB Chip DDR3 1333MT/s          | 1         | 1.08%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 1.08%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.08%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 36        | 48%     |
| DDR4   | 27        | 36%     |
| DDR2   | 5         | 6.67%   |
| LPDDR4 | 3         | 4%      |
| LPDDR3 | 2         | 2.67%   |
| SDRAM  | 1         | 1.33%   |
| DDR    | 1         | 1.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 66        | 84.62%  |
| Row Of Chips | 10        | 12.82%  |
| Chip         | 2         | 2.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 33        | 40.24%  |
| 8192  | 21        | 25.61%  |
| 2048  | 13        | 15.85%  |
| 16384 | 8         | 9.76%   |
| 1024  | 5         | 6.1%    |
| 32768 | 2         | 2.44%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 26        | 31.71%  |
| 2667    | 16        | 19.51%  |
| 1333    | 7         | 8.54%   |
| 3200    | 6         | 7.32%   |
| 1334    | 5         | 6.1%    |
| 2400    | 4         | 4.88%   |
| 2133    | 4         | 4.88%   |
| 4267    | 3         | 3.66%   |
| 667     | 3         | 3.66%   |
| 3266    | 2         | 2.44%   |
| 800     | 2         | 2.44%   |
| 8400    | 1         | 1.22%   |
| 4199    | 1         | 1.22%   |
| 1867    | 1         | 1.22%   |
| Unknown | 1         | 1.22%   |

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
| Chicony Electronics                    | 43        | 30.5%   |
| Cheng Uei Precision Industry (Foxlink) | 18        | 12.77%  |
| Acer                                   | 13        | 9.22%   |
| Syntek                                 | 8         | 5.67%   |
| Sunplus Innovation Technology          | 8         | 5.67%   |
| Realtek Semiconductor                  | 8         | 5.67%   |
| Microdia                               | 7         | 4.96%   |
| Lite-On Technology                     | 6         | 4.26%   |
| IMC Networks                           | 6         | 4.26%   |
| Silicon Motion                         | 3         | 2.13%   |
| Quanta                                 | 3         | 2.13%   |
| Suyin                                  | 2         | 1.42%   |
| Samsung Electronics                    | 2         | 1.42%   |
| Ricoh                                  | 2         | 1.42%   |
| Logitech                               | 2         | 1.42%   |
| Importek                               | 2         | 1.42%   |
| Apple                                  | 2         | 1.42%   |
| Unknown                                | 1         | 0.71%   |
| LG Electronics                         | 1         | 0.71%   |
| icSpring                               | 1         | 0.71%   |
| DigiTech                               | 1         | 0.71%   |
| ALi                                    | 1         | 0.71%   |
| Alcor Micro                            | 1         | 0.71%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 8         | 5.63%   |
| Chicony HP HD Webcam                                                       | 7         | 4.93%   |
| Syntek Integrated Camera                                                   | 5         | 3.52%   |
| Chicony USB 2.0 Camera                                                     | 5         | 3.52%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 5         | 3.52%   |
| Realtek Integrated_Webcam_HD                                               | 4         | 2.82%   |
| Acer Integrated Camera                                                     | 4         | 2.82%   |
| Microdia Integrated_Webcam_HD                                              | 3         | 2.11%   |
| Lite-On HP HD Webcam                                                       | 3         | 2.11%   |
| Lite-On HP HD Camera                                                       | 3         | 2.11%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 3         | 2.11%   |
| Chicony HD Webcam                                                          | 3         | 2.11%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 3         | 2.11%   |
| Syntek EasyCamera                                                          | 2         | 1.41%   |
| Sunplus Integrated_Webcam_HD                                               | 2         | 1.41%   |
| Sunplus HP HD Webcam [Fixed]                                               | 2         | 1.41%   |
| Realtek Integrated Webcam                                                  | 2         | 1.41%   |
| Importek HP Webcam-50                                                      | 2         | 1.41%   |
| Chicony Integrated HP HD Webcam                                            | 2         | 1.41%   |
| Chicony HP Webcam [2 MP Macro]                                             | 2         | 1.41%   |
| Chicony HP Truevision HD                                                   | 2         | 1.41%   |
| Chicony HP HD Webcam [Fixed]                                               | 2         | 1.41%   |
| Chicony HP HD Camera                                                       | 2         | 1.41%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 2         | 1.41%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera            | 2         | 1.41%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed]                | 2         | 1.41%   |
| Acer ThinkPad P50 Integrated Camera                                        | 2         | 1.41%   |
| Unknown USB Camera                                                         | 1         | 0.7%    |
| Syntek Lenovo EasyCamera                                                   | 1         | 0.7%    |
| Suyin HP Webcam                                                            | 1         | 0.7%    |
| Suyin Asus Integrated Webcam                                               | 1         | 0.7%    |
| Sunplus Laptop Integrated Webcam HD                                        | 1         | 0.7%    |
| Sunplus HP Wide Vision HD                                                  | 1         | 0.7%    |
| Sunplus HP TrueVision HD Camera                                            | 1         | 0.7%    |
| Sunplus HP Truevision HD                                                   | 1         | 0.7%    |
| Silicon Motion WebCam SC-13HDL11939N                                       | 1         | 0.7%    |
| Silicon Motion WebCam SC-10HDD12636N                                       | 1         | 0.7%    |
| Silicon Motion 300k Pixel Camera                                           | 1         | 0.7%    |
| Samsung Galaxy series, misc. (MTP mode)                                    | 1         | 0.7%    |
| Samsung Galaxy (debugging mode)                                            | 1         | 0.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 34        | 68%     |
| Synaptics                  | 10        | 20%     |
| Shenzhen Goodix Technology | 4         | 8%      |
| LighTuning Technology      | 1         | 2%      |
| AuthenTec                  | 1         | 2%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 14        | 28%     |
| Validity Sensors VFS491                                                    | 6         | 12%     |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 6%      |
| Synaptics WBDI Device                                                      | 3         | 6%      |
| Shenzhen Goodix FingerPrint                                                | 3         | 6%      |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 4%      |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 4%      |
| Validity Sensors Synaptics WBDI                                            | 2         | 4%      |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 4%      |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 4%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 4%      |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 4%      |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2%      |
| Synaptics  WBDI                                                            | 1         | 2%      |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 2%      |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 2%      |
| Shenzhen Goodix  Fingerprint Device                                        | 1         | 2%      |
| LighTuning EgisTec_ES603                                                   | 1         | 2%      |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 2%      |

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
| 0     | 92        | 58.6%   |
| 1     | 50        | 31.85%  |
| 2     | 14        | 8.92%   |
| 3     | 1         | 0.64%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 50        | 63.29%  |
| Graphics card            | 7         | 8.86%   |
| Chipcard                 | 7         | 8.86%   |
| Net/wireless             | 3         | 3.8%    |
| Camera                   | 3         | 3.8%    |
| Storage                  | 2         | 2.53%   |
| Net/ethernet             | 2         | 2.53%   |
| Communication controller | 2         | 2.53%   |
| Bluetooth                | 2         | 2.53%   |
| Sound                    | 1         | 1.27%   |

