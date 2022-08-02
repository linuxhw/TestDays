Linux in Kenya - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Linux in Kenya.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Kenya/Desktop/README.md) and [notebooks](/Location/Kenya/Notebook/README.md).

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

Total: 265

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 1493                        | Desktop     | [2925e7a321](https://linux-hardware.org/?probe=2925e7a321) | Aug 01, 2022 |
| HP            | Unknown                     | Notebook    | [1e1768ebfa](https://linux-hardware.org/?probe=1e1768ebfa) | Jul 24, 2022 |
| HP            | Unknown                     | Notebook    | [aa2aa159c9](https://linux-hardware.org/?probe=aa2aa159c9) | Jul 14, 2022 |
| HP            | 15                          | Notebook    | [91c97ad34a](https://linux-hardware.org/?probe=91c97ad34a) | Jun 24, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [2969400046](https://linux-hardware.org/?probe=2969400046) | Jun 20, 2022 |
| HP            | 3397                        | Desktop     | [0679103825](https://linux-hardware.org/?probe=0679103825) | Jun 13, 2022 |
| HP            | 3397                        | Desktop     | [579dd31cda](https://linux-hardware.org/?probe=579dd31cda) | Jun 09, 2022 |
| HP            | 3397                        | Desktop     | [e86ba79fcf](https://linux-hardware.org/?probe=e86ba79fcf) | Jun 09, 2022 |
| Dell          | 0HHV7N A00                  | Desktop     | [1f7a666022](https://linux-hardware.org/?probe=1f7a666022) | Jun 02, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [92acbd4c3f](https://linux-hardware.org/?probe=92acbd4c3f) | May 31, 2022 |
| HP            | ZHAN 66 Pro A 14 G3         | Notebook    | [9d27d641ca](https://linux-hardware.org/?probe=9d27d641ca) | May 25, 2022 |
| HP            | ZHAN 66 Pro A 14 G3         | Notebook    | [db3577b92d](https://linux-hardware.org/?probe=db3577b92d) | May 25, 2022 |
| Lenovo        | NOK                         | Desktop     | [e7a84a12e6](https://linux-hardware.org/?probe=e7a84a12e6) | May 16, 2022 |
| Notebook      | P65xHP                      | Notebook    | [b1205b8ca1](https://linux-hardware.org/?probe=b1205b8ca1) | May 10, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [9d0ee854e4](https://linux-hardware.org/?probe=9d0ee854e4) | May 10, 2022 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [691a4c0ca5](https://linux-hardware.org/?probe=691a4c0ca5) | May 08, 2022 |
| Acer          | Aspire 5920G                | Notebook    | [b2ffc81ed6](https://linux-hardware.org/?probe=b2ffc81ed6) | May 07, 2022 |
| HP            | ProBook 440 G6              | Notebook    | [94684071ed](https://linux-hardware.org/?probe=94684071ed) | May 05, 2022 |
| Dell          | Latitude 3340               | Notebook    | [b724073bff](https://linux-hardware.org/?probe=b724073bff) | May 05, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [53bceed0aa](https://linux-hardware.org/?probe=53bceed0aa) | Apr 29, 2022 |
| Dell          | Latitude 3340               | Notebook    | [e6aa31da26](https://linux-hardware.org/?probe=e6aa31da26) | Apr 23, 2022 |
| Lenovo        | ThinkPad X131e 33672T5      | Notebook    | [64e00f7a40](https://linux-hardware.org/?probe=64e00f7a40) | Apr 12, 2022 |
| HP            | EliteBook x360 1030 G8 N... | Convertible | [ef1693c88f](https://linux-hardware.org/?probe=ef1693c88f) | Apr 07, 2022 |
| HP            | EliteBook Folio 9480m       | Notebook    | [a83be65e4f](https://linux-hardware.org/?probe=a83be65e4f) | Apr 02, 2022 |
| HP            | EliteBook Folio 9480m       | Notebook    | [5bb1b6ca04](https://linux-hardware.org/?probe=5bb1b6ca04) | Apr 02, 2022 |
| Lenovo        | ThinkPad X131e 33672T5      | Notebook    | [277143e66b](https://linux-hardware.org/?probe=277143e66b) | Mar 26, 2022 |
| HP            | 83EB                        | All in one  | [26fea5e4f7](https://linux-hardware.org/?probe=26fea5e4f7) | Mar 19, 2022 |
| Dell          | 0773VG A02                  | Desktop     | [ec8ec429fc](https://linux-hardware.org/?probe=ec8ec429fc) | Mar 07, 2022 |
| Dell          | 055H3G A01                  | Desktop     | [7e00973942](https://linux-hardware.org/?probe=7e00973942) | Mar 06, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [c66cc8aa4e](https://linux-hardware.org/?probe=c66cc8aa4e) | Feb 17, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [a2e640db60](https://linux-hardware.org/?probe=a2e640db60) | Feb 08, 2022 |
| Dell          | 055H3G A01                  | Desktop     | [05f63f2396](https://linux-hardware.org/?probe=05f63f2396) | Feb 04, 2022 |
| Lenovo        | ThinkPad T490s 20NYS8J90... | Notebook    | [c1aee9b559](https://linux-hardware.org/?probe=c1aee9b559) | Feb 03, 2022 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [71b93f7b57](https://linux-hardware.org/?probe=71b93f7b57) | Feb 03, 2022 |
| Gigabyte      | H110M-A-CF                  | Desktop     | [e6a3a69257](https://linux-hardware.org/?probe=e6a3a69257) | Jan 29, 2022 |
| HP            | ProBook 4540s               | Notebook    | [16794fee23](https://linux-hardware.org/?probe=16794fee23) | Jan 20, 2022 |
| Lenovo        | V14-IGL 82C2                | Notebook    | [c90b300aea](https://linux-hardware.org/?probe=c90b300aea) | Jan 16, 2022 |
| HP            | Presario CQ56               | Notebook    | [8d03d80424](https://linux-hardware.org/?probe=8d03d80424) | Jan 14, 2022 |
| HP            | 83E0                        | Desktop     | [4a54d6921c](https://linux-hardware.org/?probe=4a54d6921c) | Jan 13, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [fac2fc3940](https://linux-hardware.org/?probe=fac2fc3940) | Jan 13, 2022 |
| Lenovo        | ThinkPad X240 20AL00CQAU    | Notebook    | [9f36bf55ba](https://linux-hardware.org/?probe=9f36bf55ba) | Jan 11, 2022 |
| HP            | Presario CQ56               | Notebook    | [a0bc0364a8](https://linux-hardware.org/?probe=a0bc0364a8) | Jan 08, 2022 |
| Lenovo        | ThinkPad X250 20CLA21MJP    | Notebook    | [850c0ae1da](https://linux-hardware.org/?probe=850c0ae1da) | Jan 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | Notebook    | [c08374a615](https://linux-hardware.org/?probe=c08374a615) | Dec 30, 2021 |
| Dell          | Inspiron 3543               | Notebook    | [30756486fd](https://linux-hardware.org/?probe=30756486fd) | Dec 26, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [01b4efe7c0](https://linux-hardware.org/?probe=01b4efe7c0) | Dec 17, 2021 |
| HP            | ENVY Pro 4-b000 Ultraboo... | Notebook    | [1bac69aa61](https://linux-hardware.org/?probe=1bac69aa61) | Dec 17, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [dff30c5ec8](https://linux-hardware.org/?probe=dff30c5ec8) | Dec 15, 2021 |
| HP            | ENVY Pro 4-b000 Ultraboo... | Notebook    | [20259384ac](https://linux-hardware.org/?probe=20259384ac) | Dec 14, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [b159811d48](https://linux-hardware.org/?probe=b159811d48) | Dec 12, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [2197770fd0](https://linux-hardware.org/?probe=2197770fd0) | Dec 12, 2021 |
| Chuwi         | HeroBook Air                | Notebook    | [dd5567d4dc](https://linux-hardware.org/?probe=dd5567d4dc) | Dec 08, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [64521297e2](https://linux-hardware.org/?probe=64521297e2) | Dec 07, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [b6a5bb8982](https://linux-hardware.org/?probe=b6a5bb8982) | Dec 06, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [ee1387e206](https://linux-hardware.org/?probe=ee1387e206) | Nov 26, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [2b0946038d](https://linux-hardware.org/?probe=2b0946038d) | Nov 18, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [e1597401db](https://linux-hardware.org/?probe=e1597401db) | Nov 16, 2021 |
| SLIMBOOK      | PROX14-AMD                  | Notebook    | [820951b4af](https://linux-hardware.org/?probe=820951b4af) | Nov 16, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [022146ab90](https://linux-hardware.org/?probe=022146ab90) | Nov 14, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [e3997c3bcb](https://linux-hardware.org/?probe=e3997c3bcb) | Nov 12, 2021 |
| Dell          | Inspiron 7506 2n1           | Convertible | [c5620beab2](https://linux-hardware.org/?probe=c5620beab2) | Nov 07, 2021 |
| Dell          | Inspiron 7506 2n1           | Convertible | [94ac3dba1a](https://linux-hardware.org/?probe=94ac3dba1a) | Nov 07, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [516eabe645](https://linux-hardware.org/?probe=516eabe645) | Nov 02, 2021 |
| Chuwi         | GemiBook                    | Notebook    | [f40d5fd5a7](https://linux-hardware.org/?probe=f40d5fd5a7) | Oct 27, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [170dd8b241](https://linux-hardware.org/?probe=170dd8b241) | Oct 22, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [044c6efa0d](https://linux-hardware.org/?probe=044c6efa0d) | Oct 08, 2021 |
| HP            | Laptop 15-ra0xx             | Notebook    | [5e542184d8](https://linux-hardware.org/?probe=5e542184d8) | Oct 02, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [5a23abfa74](https://linux-hardware.org/?probe=5a23abfa74) | Sep 29, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [0646fc1739](https://linux-hardware.org/?probe=0646fc1739) | Sep 27, 2021 |
| Acer          | Aspire V3-572P              | Notebook    | [3eecfd13ad](https://linux-hardware.org/?probe=3eecfd13ad) | Sep 25, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [2e1581c3b3](https://linux-hardware.org/?probe=2e1581c3b3) | Sep 24, 2021 |
| Apple         | MacBookPro16,1              | Notebook    | [ab55e1ade6](https://linux-hardware.org/?probe=ab55e1ade6) | Sep 22, 2021 |
| Acer          | Aspire 5749Z                | Notebook    | [40bf0d5bb0](https://linux-hardware.org/?probe=40bf0d5bb0) | Sep 17, 2021 |
| Dell          | 0R790T A00                  | Desktop     | [b5a01103fd](https://linux-hardware.org/?probe=b5a01103fd) | Sep 14, 2021 |
| Dell          | 0R790T A00                  | Desktop     | [a5290e7cb6](https://linux-hardware.org/?probe=a5290e7cb6) | Sep 14, 2021 |
| Eluktronic... | MAG-15u                     | Notebook    | [f931222022](https://linux-hardware.org/?probe=f931222022) | Sep 13, 2021 |
| Insyde        | i101c                       | Notebook    | [de0a5f2925](https://linux-hardware.org/?probe=de0a5f2925) | Aug 31, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [27b0daea73](https://linux-hardware.org/?probe=27b0daea73) | Aug 25, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [e5f9d8b06f](https://linux-hardware.org/?probe=e5f9d8b06f) | Aug 20, 2021 |
| HP            | EliteBook Folio 9480m       | Notebook    | [b89fc8114f](https://linux-hardware.org/?probe=b89fc8114f) | Aug 09, 2021 |
| Lenovo        | ThinkPad T460s 20FAS3QC0... | Notebook    | [c642d92231](https://linux-hardware.org/?probe=c642d92231) | Jul 31, 2021 |
| Lenovo        | ThinkPad T460s 20FAS3QC0... | Notebook    | [c374609a3e](https://linux-hardware.org/?probe=c374609a3e) | Jul 29, 2021 |
| Lenovo        | ThinkPad T460s 20FAS3QC0... | Notebook    | [c9de881b72](https://linux-hardware.org/?probe=c9de881b72) | Jul 25, 2021 |
| Lenovo        | ThinkPad T460s 20FAS3QC0... | Notebook    | [10e46eeaf3](https://linux-hardware.org/?probe=10e46eeaf3) | Jul 25, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [88afb2e5a1](https://linux-hardware.org/?probe=88afb2e5a1) | Jul 23, 2021 |
| Acer          | Veriton X680G               | Desktop     | [3b8774337b](https://linux-hardware.org/?probe=3b8774337b) | Jul 23, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [d80d4d487b](https://linux-hardware.org/?probe=d80d4d487b) | Jul 22, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [b3a36bf681](https://linux-hardware.org/?probe=b3a36bf681) | Jul 21, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [0f54d945d0](https://linux-hardware.org/?probe=0f54d945d0) | Jul 21, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [daa99f3a24](https://linux-hardware.org/?probe=daa99f3a24) | Jul 15, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [6c9393a9d6](https://linux-hardware.org/?probe=6c9393a9d6) | Jul 08, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [e60c71a5e1](https://linux-hardware.org/?probe=e60c71a5e1) | Jun 25, 2021 |
| IBM           | Node 1, Processor Card      | Server      | [be2298910b](https://linux-hardware.org/?probe=be2298910b) | Jun 24, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [8513c961a4](https://linux-hardware.org/?probe=8513c961a4) | Jun 21, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | Notebook    | [9d9ecee1b9](https://linux-hardware.org/?probe=9d9ecee1b9) | Jun 20, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [e9d94e06f1](https://linux-hardware.org/?probe=e9d94e06f1) | Jun 18, 2021 |
| Unknown       | Unknown                     | Phone       | [7948d69684](https://linux-hardware.org/?probe=7948d69684) | Jun 05, 2021 |
| Lenovo        | V130-14IKB 81HQ             | Notebook    | [549f1c8bd1](https://linux-hardware.org/?probe=549f1c8bd1) | May 25, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [304747e4c6](https://linux-hardware.org/?probe=304747e4c6) | May 23, 2021 |
| IP3 Tech      | AB1                         | Mini pc     | [b2cc37b9ac](https://linux-hardware.org/?probe=b2cc37b9ac) | May 21, 2021 |
| Dell          | 0HN7XN A01                  | Desktop     | [2c35ee27d9](https://linux-hardware.org/?probe=2c35ee27d9) | May 20, 2021 |
| Dell          | Inspiron 3543               | Notebook    | [11b99bedb6](https://linux-hardware.org/?probe=11b99bedb6) | May 13, 2021 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [a71cb329b2](https://linux-hardware.org/?probe=a71cb329b2) | May 12, 2021 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [dc61da2d5e](https://linux-hardware.org/?probe=dc61da2d5e) | May 09, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [e177523d81](https://linux-hardware.org/?probe=e177523d81) | May 03, 2021 |
| Dell          | Inspiron 3543               | Notebook    | [e8771a4577](https://linux-hardware.org/?probe=e8771a4577) | May 01, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [ee57ec30cd](https://linux-hardware.org/?probe=ee57ec30cd) | Apr 28, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [95c380139d](https://linux-hardware.org/?probe=95c380139d) | Apr 28, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [b35c15fb6b](https://linux-hardware.org/?probe=b35c15fb6b) | Apr 25, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [108510a130](https://linux-hardware.org/?probe=108510a130) | Apr 08, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [561287f5a8](https://linux-hardware.org/?probe=561287f5a8) | Apr 06, 2021 |
| HP            | 15 Notebook PC              | Notebook    | [ecac5c48dc](https://linux-hardware.org/?probe=ecac5c48dc) | Apr 02, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [95f53c1b72](https://linux-hardware.org/?probe=95f53c1b72) | Mar 19, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [585322e740](https://linux-hardware.org/?probe=585322e740) | Mar 19, 2021 |
| Toshiba       | Satellite L50-B             | Notebook    | [b345b644ae](https://linux-hardware.org/?probe=b345b644ae) | Mar 18, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [89e652d12d](https://linux-hardware.org/?probe=89e652d12d) | Mar 18, 2021 |
| Dell          | 0773VG A02                  | Desktop     | [a4d5cb7e11](https://linux-hardware.org/?probe=a4d5cb7e11) | Mar 10, 2021 |
| Toshiba       | dynabook Satellite B554/... | Notebook    | [31915e8c0b](https://linux-hardware.org/?probe=31915e8c0b) | Mar 10, 2021 |
| Toshiba       | dynabook Satellite B554/... | Notebook    | [e166e551cd](https://linux-hardware.org/?probe=e166e551cd) | Mar 09, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [10c98c982d](https://linux-hardware.org/?probe=10c98c982d) | Mar 07, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [09037a0a1b](https://linux-hardware.org/?probe=09037a0a1b) | Mar 06, 2021 |
| HP            | ENVY 15                     | Notebook    | [5c1bfc1459](https://linux-hardware.org/?probe=5c1bfc1459) | Mar 05, 2021 |
| HP            | ProBook 430 G6              | Notebook    | [5ed6cc994b](https://linux-hardware.org/?probe=5ed6cc994b) | Mar 05, 2021 |
| Dell          | Inspiron N5030              | Notebook    | [47077a37f2](https://linux-hardware.org/?probe=47077a37f2) | Feb 25, 2021 |
| Toshiba       | Satellite L50-B             | Notebook    | [c4ab183609](https://linux-hardware.org/?probe=c4ab183609) | Feb 24, 2021 |
| Toshiba       | Satellite L50-B             | Notebook    | [55c54121f8](https://linux-hardware.org/?probe=55c54121f8) | Feb 24, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [3311619921](https://linux-hardware.org/?probe=3311619921) | Feb 18, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [b573c1e746](https://linux-hardware.org/?probe=b573c1e746) | Feb 17, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [eda69993ed](https://linux-hardware.org/?probe=eda69993ed) | Feb 17, 2021 |
| HP            | Laptop 15-da1xxx            | Notebook    | [66c8150e0d](https://linux-hardware.org/?probe=66c8150e0d) | Feb 14, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [96be56a30d](https://linux-hardware.org/?probe=96be56a30d) | Feb 13, 2021 |
| TECNO         | WinPad 2                    | Notebook    | [336989b30d](https://linux-hardware.org/?probe=336989b30d) | Feb 10, 2021 |
| TECNO         | WinPad 2                    | Notebook    | [439563e244](https://linux-hardware.org/?probe=439563e244) | Feb 09, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [38d7cb1271](https://linux-hardware.org/?probe=38d7cb1271) | Feb 06, 2021 |
| Dell          | Inspiron 3580               | Notebook    | [417752f660](https://linux-hardware.org/?probe=417752f660) | Jan 30, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [f56f2da985](https://linux-hardware.org/?probe=f56f2da985) | Jan 28, 2021 |
| Lenovo        | ThinkPad P52s 20LB0021US    | Notebook    | [4e50af07df](https://linux-hardware.org/?probe=4e50af07df) | Jan 28, 2021 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [671c83ebf7](https://linux-hardware.org/?probe=671c83ebf7) | Jan 27, 2021 |
| HP            | ProBook 6560b               | Notebook    | [4771c30f72](https://linux-hardware.org/?probe=4771c30f72) | Jan 18, 2021 |
| HP            | Compaq Mini 110c-1100       | Notebook    | [e2f7ccd4ad](https://linux-hardware.org/?probe=e2f7ccd4ad) | Jan 14, 2021 |
| ASUSTek       | X540NA                      | Notebook    | [9b2af2d13c](https://linux-hardware.org/?probe=9b2af2d13c) | Jan 13, 2021 |
| HP            | ProBook 6560b               | Notebook    | [d6d7748e86](https://linux-hardware.org/?probe=d6d7748e86) | Dec 30, 2020 |
| HP            | EliteBook Folio 9470m       | Notebook    | [013db2cd8e](https://linux-hardware.org/?probe=013db2cd8e) | Dec 25, 2020 |
| Endless       | EF20EA                      | Notebook    | [c216bffe9d](https://linux-hardware.org/?probe=c216bffe9d) | Dec 20, 2020 |
| Endless       | EF20EA                      | Notebook    | [e2409b47e2](https://linux-hardware.org/?probe=e2409b47e2) | Dec 20, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [c3c7909b48](https://linux-hardware.org/?probe=c3c7909b48) | Dec 20, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [c764c0655e](https://linux-hardware.org/?probe=c764c0655e) | Dec 16, 2020 |
| Lenovo        | ThinkPad T470s 20HGS6PF0... | Notebook    | [2f91f2576d](https://linux-hardware.org/?probe=2f91f2576d) | Dec 14, 2020 |
| I-Life Dig... | ZED AIR PRO                 | Notebook    | [98d5a20a00](https://linux-hardware.org/?probe=98d5a20a00) | Dec 12, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [885a64d9d3](https://linux-hardware.org/?probe=885a64d9d3) | Dec 12, 2020 |
| ASUSTek       | X202EV                      | Notebook    | [b3b2381999](https://linux-hardware.org/?probe=b3b2381999) | Nov 25, 2020 |
| HP            | Compaq Mini 110c-1100       | Notebook    | [36bc2c3cdf](https://linux-hardware.org/?probe=36bc2c3cdf) | Nov 18, 2020 |
| Lenovo        | ThinkPad X240 20AMS4J900    | Notebook    | [8a54e51f5a](https://linux-hardware.org/?probe=8a54e51f5a) | Nov 17, 2020 |
| HP            | Laptop 15-da1xxx            | Notebook    | [7c1f9ebdef](https://linux-hardware.org/?probe=7c1f9ebdef) | Nov 12, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [ccefa81140](https://linux-hardware.org/?probe=ccefa81140) | Nov 12, 2020 |
| HP            | ZBook 15 G2                 | Notebook    | [5c863855cc](https://linux-hardware.org/?probe=5c863855cc) | Nov 11, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [372e62dd5a](https://linux-hardware.org/?probe=372e62dd5a) | Nov 11, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [6b0122d8c2](https://linux-hardware.org/?probe=6b0122d8c2) | Nov 06, 2020 |
| HP            | 3396                        | Desktop     | [12e6dc258e](https://linux-hardware.org/?probe=12e6dc258e) | Oct 31, 2020 |
| HP            | 3396                        | Desktop     | [876ee024dc](https://linux-hardware.org/?probe=876ee024dc) | Oct 31, 2020 |
| HP            | Spectre x360 Convertible    | Convertible | [b4e75e63fb](https://linux-hardware.org/?probe=b4e75e63fb) | Oct 30, 2020 |
| Dell          | Latitude E6420              | Notebook    | [e1f1909639](https://linux-hardware.org/?probe=e1f1909639) | Oct 25, 2020 |
| Dell          | Latitude E6420              | Notebook    | [e1bbf1beb6](https://linux-hardware.org/?probe=e1bbf1beb6) | Oct 25, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [a2eb617037](https://linux-hardware.org/?probe=a2eb617037) | Oct 16, 2020 |
| MSI           | B450 TOMAHAWK               | Desktop     | [6ea891ad6b](https://linux-hardware.org/?probe=6ea891ad6b) | Oct 13, 2020 |
| Dell          | 0773VG A02                  | Desktop     | [8307343ab3](https://linux-hardware.org/?probe=8307343ab3) | Oct 09, 2020 |
| Dell          | 0773VG A02                  | Desktop     | [2c6d570678](https://linux-hardware.org/?probe=2c6d570678) | Oct 09, 2020 |
| Unknown       | Unknown                     | Phone       | [6f31ab4962](https://linux-hardware.org/?probe=6f31ab4962) | Oct 03, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [5b0c257b43](https://linux-hardware.org/?probe=5b0c257b43) | Oct 02, 2020 |
| Dell          | Latitude D820               | Notebook    | [ae1fa80f73](https://linux-hardware.org/?probe=ae1fa80f73) | Oct 02, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [47a129fdd0](https://linux-hardware.org/?probe=47a129fdd0) | Sep 28, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [ebcb037006](https://linux-hardware.org/?probe=ebcb037006) | Sep 28, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [8232648226](https://linux-hardware.org/?probe=8232648226) | Sep 20, 2020 |
| Samsung       | RC410/RC510/RC710           | Notebook    | [37985e0340](https://linux-hardware.org/?probe=37985e0340) | Sep 19, 2020 |
| HP            | ProBook 440 G5              | Notebook    | [92ee6a03be](https://linux-hardware.org/?probe=92ee6a03be) | Sep 14, 2020 |
| ASUSTek       | UX305CA                     | Notebook    | [f51d9347e3](https://linux-hardware.org/?probe=f51d9347e3) | Sep 10, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [6e6f79b651](https://linux-hardware.org/?probe=6e6f79b651) | Sep 10, 2020 |
| MSI           | B450 TOMAHAWK               | Desktop     | [dc38793462](https://linux-hardware.org/?probe=dc38793462) | Sep 08, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [4d64af6a38](https://linux-hardware.org/?probe=4d64af6a38) | Sep 07, 2020 |
| ASUSTek       | X551MA                      | Notebook    | [6e93ef18ce](https://linux-hardware.org/?probe=6e93ef18ce) | Sep 03, 2020 |
| HP            | EliteBook Folio 9480m       | Notebook    | [19a0f0bfdc](https://linux-hardware.org/?probe=19a0f0bfdc) | Sep 03, 2020 |
| HP            | ProBook 440 G5              | Notebook    | [9c70b1dad4](https://linux-hardware.org/?probe=9c70b1dad4) | Sep 02, 2020 |
| MSI           | 0A90                        | Desktop     | [4f8d53458d](https://linux-hardware.org/?probe=4f8d53458d) | Aug 11, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [31f100c680](https://linux-hardware.org/?probe=31f100c680) | Aug 10, 2020 |
| MSI           | 0A90                        | Desktop     | [04bdc6569a](https://linux-hardware.org/?probe=04bdc6569a) | Aug 09, 2020 |
| MSI           | 2AE0                        | Desktop     | [54a32fea6e](https://linux-hardware.org/?probe=54a32fea6e) | Aug 02, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [2a88596017](https://linux-hardware.org/?probe=2a88596017) | Jul 30, 2020 |
| HP            | Pavilion Laptop 15t-cs20... | Notebook    | [f778796026](https://linux-hardware.org/?probe=f778796026) | Jul 16, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [551521f7c9](https://linux-hardware.org/?probe=551521f7c9) | Jul 11, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [a1265cca74](https://linux-hardware.org/?probe=a1265cca74) | Jul 11, 2020 |
| Dell          | 0VNP2H A00                  | Desktop     | [de21e4bff4](https://linux-hardware.org/?probe=de21e4bff4) | Jul 04, 2020 |
| Lenovo        | ThinkPad E520 1143ADU       | Notebook    | [412f31bc06](https://linux-hardware.org/?probe=412f31bc06) | Jul 01, 2020 |
| Lenovo        | ThinkPad L480 20LTS1RE0Y    | Notebook    | [76ef35dd77](https://linux-hardware.org/?probe=76ef35dd77) | Jun 26, 2020 |
| HP            | 0AA8h                       | Desktop     | [e60c30f572](https://linux-hardware.org/?probe=e60c30f572) | Jun 25, 2020 |
| HP            | EliteBook Folio 9470m       | Notebook    | [4f747e9c8a](https://linux-hardware.org/?probe=4f747e9c8a) | Jun 25, 2020 |
| HP            | ProBook 440 G2              | Notebook    | [21efc22417](https://linux-hardware.org/?probe=21efc22417) | Jun 21, 2020 |
| Dell          | Latitude 3150               | Notebook    | [0299c15a34](https://linux-hardware.org/?probe=0299c15a34) | Jun 20, 2020 |
| HP            | Pavilion x2 Detachable      | Notebook    | [6277131dfd](https://linux-hardware.org/?probe=6277131dfd) | Jun 20, 2020 |
| HP            | 0AA8h                       | Desktop     | [4017115305](https://linux-hardware.org/?probe=4017115305) | Jun 19, 2020 |
| HP            | 0AA8h                       | Desktop     | [752505c134](https://linux-hardware.org/?probe=752505c134) | Jun 17, 2020 |
| Lenovo        | ThinkPad T460 20FMS1DH01    | Notebook    | [f16d9a4077](https://linux-hardware.org/?probe=f16d9a4077) | Jun 17, 2020 |
| ASUSTek       | X540NA                      | Notebook    | [530934acb0](https://linux-hardware.org/?probe=530934acb0) | Jun 17, 2020 |
| HP            | Pavilion x2 Detachable      | Notebook    | [0e66f9df2c](https://linux-hardware.org/?probe=0e66f9df2c) | Jun 16, 2020 |
| HP            | ZBook Studio x360 G5        | Convertible | [620453a9dc](https://linux-hardware.org/?probe=620453a9dc) | Jun 16, 2020 |
| Lenovo        | ThinkPad T460 20FMS1DH01    | Notebook    | [483d2473b0](https://linux-hardware.org/?probe=483d2473b0) | Jun 15, 2020 |
| Getac         | V110                        | Notebook    | [4e3a330cb5](https://linux-hardware.org/?probe=4e3a330cb5) | Jun 13, 2020 |
| HP            | 3032h                       | Desktop     | [8aa1dd8ecd](https://linux-hardware.org/?probe=8aa1dd8ecd) | Jun 13, 2020 |
| Toshiba       | R84SAU2                     | Notebook    | [d59976ae7f](https://linux-hardware.org/?probe=d59976ae7f) | Jun 10, 2020 |
| Acer          | Aspire A315-33              | Notebook    | [c0eeb5a67b](https://linux-hardware.org/?probe=c0eeb5a67b) | Jun 03, 2020 |
| Lenovo        | ThinkPad E520 1143ADU       | Notebook    | [e903b1af8a](https://linux-hardware.org/?probe=e903b1af8a) | May 31, 2020 |
| Dell          | 0PU052                      | Desktop     | [5d99be49f0](https://linux-hardware.org/?probe=5d99be49f0) | May 31, 2020 |
| Lenovo        | ThinkPad E520 1143ADU       | Notebook    | [75e6d735a0](https://linux-hardware.org/?probe=75e6d735a0) | May 31, 2020 |
| Dell          | 0PU052                      | Desktop     | [6b4292fc06](https://linux-hardware.org/?probe=6b4292fc06) | May 30, 2020 |
| Dell          | Inspiron 5767               | Notebook    | [bdab68c78a](https://linux-hardware.org/?probe=bdab68c78a) | May 25, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [8240cd4643](https://linux-hardware.org/?probe=8240cd4643) | May 17, 2020 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [227b4dc4ec](https://linux-hardware.org/?probe=227b4dc4ec) | May 15, 2020 |
| Apple         | MacBookPro3,1               | Notebook    | [5ca063ed58](https://linux-hardware.org/?probe=5ca063ed58) | May 11, 2020 |
| Dell          | Latitude E6410              | Notebook    | [7a885b703e](https://linux-hardware.org/?probe=7a885b703e) | May 10, 2020 |
| HP            | ZBook Studio x360 G5        | Convertible | [0420235572](https://linux-hardware.org/?probe=0420235572) | May 08, 2020 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [d64b4a56e0](https://linux-hardware.org/?probe=d64b4a56e0) | May 08, 2020 |
| Dell          | 0G214D A00                  | Desktop     | [a8caa085de](https://linux-hardware.org/?probe=a8caa085de) | May 04, 2020 |
| Lenovo        | ThinkPad T440p 20AWS5D20... | Notebook    | [85b487e27d](https://linux-hardware.org/?probe=85b487e27d) | May 02, 2020 |
| Dell          | Inspiron 5767               | Notebook    | [32e3129638](https://linux-hardware.org/?probe=32e3129638) | May 02, 2020 |
| Dell          | Latitude 7490               | Notebook    | [cc8b2bc724](https://linux-hardware.org/?probe=cc8b2bc724) | Apr 30, 2020 |
| Lenovo        | ThinkPad T440p 20AWS5D20... | Notebook    | [6cf30d2192](https://linux-hardware.org/?probe=6cf30d2192) | Apr 26, 2020 |
| HP            | ProBook 6470b               | Notebook    | [a6132519cf](https://linux-hardware.org/?probe=a6132519cf) | Apr 21, 2020 |
| HP            | ProBook 6470b               | Notebook    | [255652dcf4](https://linux-hardware.org/?probe=255652dcf4) | Apr 21, 2020 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [2dec0ef690](https://linux-hardware.org/?probe=2dec0ef690) | Apr 18, 2020 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [a26feb7507](https://linux-hardware.org/?probe=a26feb7507) | Apr 18, 2020 |
| HP            | 15 Notebook PC              | Notebook    | [120e9af4f0](https://linux-hardware.org/?probe=120e9af4f0) | Apr 11, 2020 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [04ee092498](https://linux-hardware.org/?probe=04ee092498) | Apr 08, 2020 |
| HP            | Pavilion Laptop 13-an0xx... | Notebook    | [ecef1f0fcb](https://linux-hardware.org/?probe=ecef1f0fcb) | Apr 07, 2020 |
| ASUSTek       | X540SAA                     | Notebook    | [f5e7614710](https://linux-hardware.org/?probe=f5e7614710) | Mar 14, 2020 |
| HP            | 0B4Ch D                     | Desktop     | [2807f4c586](https://linux-hardware.org/?probe=2807f4c586) | Mar 12, 2020 |
| HP            | Pavilion x2 Detachable      | Notebook    | [b634560d95](https://linux-hardware.org/?probe=b634560d95) | Mar 01, 2020 |
| HP            | 09F0h                       | Desktop     | [bff6b4f556](https://linux-hardware.org/?probe=bff6b4f556) | Jan 21, 2020 |
| HP            | 09F0h                       | Desktop     | [ad09a9a9d4](https://linux-hardware.org/?probe=ad09a9a9d4) | Jan 21, 2020 |
| HP            | ENVY TS 15                  | Notebook    | [eb1591f00c](https://linux-hardware.org/?probe=eb1591f00c) | Dec 23, 2019 |
| HP            | Spectre x360 Convertible    | Convertible | [6f8fd31c2c](https://linux-hardware.org/?probe=6f8fd31c2c) | Dec 19, 2019 |
| HP            | Spectre x360 Convertible    | Convertible | [a18a54d051](https://linux-hardware.org/?probe=a18a54d051) | Oct 30, 2019 |
| Dell          | Latitude E6220              | Notebook    | [37cf274f19](https://linux-hardware.org/?probe=37cf274f19) | Oct 30, 2019 |
| HP            | EliteBook 820 G2            | Notebook    | [05b4f35642](https://linux-hardware.org/?probe=05b4f35642) | Oct 11, 2019 |
| HP            | 630                         | Notebook    | [687ccfe3b1](https://linux-hardware.org/?probe=687ccfe3b1) | Sep 28, 2019 |
| EVOC          | P7xxTM1-(G)                 | Notebook    | [f0f19467e3](https://linux-hardware.org/?probe=f0f19467e3) | Sep 04, 2019 |
| EVOC          | P7xxTM1-(G)                 | Notebook    | [2ec595f039](https://linux-hardware.org/?probe=2ec595f039) | Sep 03, 2019 |
| HP            | ENVY TS 15                  | Notebook    | [054a6961ec](https://linux-hardware.org/?probe=054a6961ec) | Aug 18, 2019 |
| Panasonic     | CF-SX2JDQZF5                | Notebook    | [6986c9f2d2](https://linux-hardware.org/?probe=6986c9f2d2) | Aug 17, 2019 |
| EVOC          | P7xxTM1-(G)                 | Notebook    | [f9f9fbd6bd](https://linux-hardware.org/?probe=f9f9fbd6bd) | Aug 06, 2019 |
| HP            | EliteBook 8440p             | Notebook    | [e2c04796a0](https://linux-hardware.org/?probe=e2c04796a0) | Jul 25, 2019 |
| HP            | OMEN by Laptop              | Notebook    | [c4f5abc453](https://linux-hardware.org/?probe=c4f5abc453) | Jul 12, 2019 |
| HP            | EliteBook 840 G1            | Notebook    | [70e21ebad0](https://linux-hardware.org/?probe=70e21ebad0) | Jun 30, 2019 |
| HP            | EliteBook 840 G1            | Notebook    | [25b5bf978a](https://linux-hardware.org/?probe=25b5bf978a) | Jun 29, 2019 |
| HP            | 0AA0h                       | Desktop     | [1787c13656](https://linux-hardware.org/?probe=1787c13656) | Jun 15, 2019 |
| HP            | ProBook 450 G1              | Notebook    | [8f23861866](https://linux-hardware.org/?probe=8f23861866) | Jun 04, 2019 |
| Unknown       | Unknown                     | Notebook    | [57dd20a793](https://linux-hardware.org/?probe=57dd20a793) | Jun 03, 2019 |
| Dell          | Inspiron 5570               | Notebook    | [86722cf4ab](https://linux-hardware.org/?probe=86722cf4ab) | May 05, 2019 |
| HP            | Notebook                    | Notebook    | [ca99cb8e00](https://linux-hardware.org/?probe=ca99cb8e00) | Apr 10, 2019 |
| ASUSTek       | Zephyrus M GM501GS          | Notebook    | [2f1b160149](https://linux-hardware.org/?probe=2f1b160149) | Nov 19, 2018 |
| Clevo         | P7xxDM2-(G)                 | Notebook    | [9cfa1aef75](https://linux-hardware.org/?probe=9cfa1aef75) | Jun 20, 2018 |
| EUROCOM       | Q6                          | Notebook    | [001ab8c139](https://linux-hardware.org/?probe=001ab8c139) | Jun 02, 2018 |
| EUROCOM       | Q6                          | Notebook    | [15b4e0daf2](https://linux-hardware.org/?probe=15b4e0daf2) | Jun 02, 2018 |
| Clevo         | P7xxDM2-(G)                 | Notebook    | [9fcaed033f](https://linux-hardware.org/?probe=9fcaed033f) | Mar 09, 2018 |
| Sony          | VGN-NS295J                  | Notebook    | [9d2ccc3bc1](https://linux-hardware.org/?probe=9d2ccc3bc1) | Dec 20, 2017 |
| Sony          | VGN-NS295J                  | Notebook    | [08cfe3b021](https://linux-hardware.org/?probe=08cfe3b021) | Dec 20, 2017 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [304aa59840](https://linux-hardware.org/?probe=304aa59840) | Dec 14, 2017 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 46        | 23.59%  |
| Ubuntu 18.04                 | 18        | 9.23%   |
| Zorin 16                     | 6         | 3.08%   |
| Zorin 15                     | 6         | 3.08%   |
| Pop!_OS 20.04                | 5         | 2.56%   |
| OpenMandriva 4.2             | 5         | 2.56%   |
| Manjaro                      | 5         | 2.56%   |
| Ubuntu 20.10                 | 4         | 2.05%   |
| Ubuntu 19.04                 | 4         | 2.05%   |
| Arch                         | 4         | 2.05%   |
| Ubuntu 21.10                 | 3         | 1.54%   |
| Ubuntu 21.04                 | 3         | 1.54%   |
| Q4OS 3                       | 3         | 1.54%   |
| Fedora 35                    | 3         | 1.54%   |
| Fedora 33                    | 3         | 1.54%   |
| Fedora 32                    | 3         | 1.54%   |
| ArcoLinux Rolling            | 3         | 1.54%   |
| Ubuntu 19.10                 | 2         | 1.03%   |
| Pop!_OS 20.10                | 2         | 1.03%   |
| OpenMandriva 4.3             | 2         | 1.03%   |
| Linux Mint 20.3              | 2         | 1.03%   |
| Linux Mint 20.2              | 2         | 1.03%   |
| Linux Mint 19                | 2         | 1.03%   |
| Kali 2020.1                  | 2         | 1.03%   |
| Endless 3.9.4                | 2         | 1.03%   |
| Endless 3.9.2                | 2         | 1.03%   |
| Endless 3.9.1                | 2         | 1.03%   |
| Elementary 6                 | 2         | 1.03%   |
| Elementary 5.1.7             | 2         | 1.03%   |
| Debian 11                    | 2         | 1.03%   |
| BlackPanther 18.1            | 2         | 1.03%   |
| Android                      | 2         | 1.03%   |
| Xubuntu 20.04                | 1         | 0.51%   |
| Ubuntu Studio 21.10          | 1         | 0.51%   |
| Ubuntu MATE 21.04            | 1         | 0.51%   |
| Ubuntu MATE 20.04            | 1         | 0.51%   |
| Ubuntu Budgie 20.04          | 1         | 0.51%   |
| Ubuntu 22.04                 | 1         | 0.51%   |
| Ubuntu 16.04                 | 1         | 0.51%   |
| ROSA R11                     | 1         | 0.51%   |
| ROSA R10                     | 1         | 0.51%   |
| Pop!_OS 21.04                | 1         | 0.51%   |
| Parrot 5.0                   | 1         | 0.51%   |
| Parrot 4.9                   | 1         | 0.51%   |
| Parrot 4.8                   | 1         | 0.51%   |
| Parrot 4.7                   | 1         | 0.51%   |
| Parrot 4.11                  | 1         | 0.51%   |
| openSUSE Tumbleweed-XXXXXXXX | 1         | 0.51%   |
| Manjaro 20.1                 | 1         | 0.51%   |
| Mageia 6                     | 1         | 0.51%   |
| Lubuntu 20.10                | 1         | 0.51%   |
| LMDE 5                       | 1         | 0.51%   |
| Linux Mint 21                | 1         | 0.51%   |
| KDE neon 20.04               | 1         | 0.51%   |
| Kali 2021.3                  | 1         | 0.51%   |
| Garuda Linux Soaring         | 1         | 0.51%   |
| Fedora 36                    | 1         | 0.51%   |
| Fedora 34                    | 1         | 0.51%   |
| Fedora 31                    | 1         | 0.51%   |
| Fedora 29                    | 1         | 0.51%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 77        | 42.08%  |
| Zorin         | 12        | 6.56%   |
| Fedora        | 12        | 6.56%   |
| Endless       | 10        | 5.46%   |
| Pop!_OS       | 7         | 3.83%   |
| OpenMandriva  | 7         | 3.83%   |
| Linux Mint    | 7         | 3.83%   |
| Manjaro       | 6         | 3.28%   |
| Arch          | 6         | 3.28%   |
| Parrot        | 4         | 2.19%   |
| Elementary    | 4         | 2.19%   |
| Q4OS          | 3         | 1.64%   |
| Kali          | 3         | 1.64%   |
| Debian        | 3         | 1.64%   |
| ArcoLinux     | 3         | 1.64%   |
| Ubuntu MATE   | 2         | 1.09%   |
| ROSA          | 2         | 1.09%   |
| BlackPanther  | 2         | 1.09%   |
| Android       | 2         | 1.09%   |
| Xubuntu       | 1         | 0.55%   |
| Ubuntu Studio | 1         | 0.55%   |
| Ubuntu Budgie | 1         | 0.55%   |
| openSUSE      | 1         | 0.55%   |
| Mageia        | 1         | 0.55%   |
| Lubuntu       | 1         | 0.55%   |
| LMDE          | 1         | 0.55%   |
| KDE neon      | 1         | 0.55%   |
| Garuda Linux  | 1         | 0.55%   |
| CentOS        | 1         | 0.55%   |
| antiX         | 1         | 0.55%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.8.0-14-generic         | 6         | 2.83%   |
| 5.4.0-42-generic         | 5         | 2.36%   |
| 5.10.14-desktop-1omv4002 | 5         | 2.36%   |
| 5.4.0-52-generic         | 4         | 1.89%   |
| 5.11.0-38-generic        | 4         | 1.89%   |
| 5.8.0-43-generic         | 3         | 1.42%   |
| 5.4.0-58-generic         | 3         | 1.42%   |
| 5.4.0-45-generic         | 3         | 1.42%   |
| 5.4.0-37-generic         | 3         | 1.42%   |
| 5.3.0-28-generic         | 3         | 1.42%   |
| 5.15.0-41-generic        | 3         | 1.42%   |
| 4.19.0-17-amd64          | 3         | 1.42%   |
| 5.9.13-200.fc33.x86_64   | 2         | 0.94%   |
| 5.8.4-200.fc32.x86_64    | 2         | 0.94%   |
| 5.8.0-63-generic         | 2         | 0.94%   |
| 5.8.0-59-generic         | 2         | 0.94%   |
| 5.8.0-55-generic         | 2         | 0.94%   |
| 5.8.0-50-generic         | 2         | 0.94%   |
| 5.4.0-67-generic         | 2         | 0.94%   |
| 5.4.0-65-generic         | 2         | 0.94%   |
| 5.4.0-54-generic         | 2         | 0.94%   |
| 5.4.0-48-generic         | 2         | 0.94%   |
| 5.4.0-47-generic         | 2         | 0.94%   |
| 5.4.0-33-generic         | 2         | 0.94%   |
| 5.4.0-19-generic         | 2         | 0.94%   |
| 5.3.0-62-generic         | 2         | 0.94%   |
| 5.16.7-desktop-1omv4003  | 2         | 0.94%   |
| 5.13.19-2-MANJARO        | 2         | 0.94%   |
| 5.13.0-28-generic        | 2         | 0.94%   |
| 5.13.0-27-generic        | 2         | 0.94%   |
| 5.11.0-37-generic        | 2         | 0.94%   |
| 5.11.0-34-generic        | 2         | 0.94%   |
| 5.0.0-37-generic         | 2         | 0.94%   |
| 5.0.0-32-generic         | 2         | 0.94%   |
| 4.18.16-desktop-1bP      | 2         | 0.94%   |
| 5.9.14-arch1-1           | 1         | 0.47%   |
| 5.8.13-200.fc32.x86_64   | 1         | 0.47%   |
| 5.8.12-arch1-1           | 1         | 0.47%   |
| 5.8.0-7642-generic       | 1         | 0.47%   |
| 5.8.0-53-generic         | 1         | 0.47%   |
| 5.8.0-51-generic         | 1         | 0.47%   |
| 5.8.0-48-generic         | 1         | 0.47%   |
| 5.8.0-44-generic         | 1         | 0.47%   |
| 5.8.0-41-generic         | 1         | 0.47%   |
| 5.8.0-29-generic         | 1         | 0.47%   |
| 5.8.0-26-generic         | 1         | 0.47%   |
| 5.8.0-25-generic         | 1         | 0.47%   |
| 5.8.0-050800-generic     | 1         | 0.47%   |
| 5.7.17-2-MANJARO         | 1         | 0.47%   |
| 5.6.7-200.fc31.x86_64    | 1         | 0.47%   |
| 5.6.5-050605-generic     | 1         | 0.47%   |
| 5.6.11-300.fc32.x86_64   | 1         | 0.47%   |
| 5.5.0-1parrot1-amd64     | 1         | 0.47%   |
| 5.4.0-77-generic         | 1         | 0.47%   |
| 5.4.0-7642-generic       | 1         | 0.47%   |
| 5.4.0-7634-generic       | 1         | 0.47%   |
| 5.4.0-7629-generic       | 1         | 0.47%   |
| 5.4.0-7626-generic       | 1         | 0.47%   |
| 5.4.0-7625-generic       | 1         | 0.47%   |
| 5.4.0-74-generic         | 1         | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 45        | 22.61%  |
| 5.8.0   | 24        | 12.06%  |
| 5.11.0  | 14        | 7.04%   |
| 5.13.0  | 12        | 6.03%   |
| 4.15.0  | 12        | 6.03%   |
| 5.3.0   | 10        | 5.03%   |
| 5.0.0   | 9         | 4.52%   |
| 5.10.14 | 5         | 2.51%   |
| 5.15.0  | 4         | 2.01%   |
| 5.10.0  | 4         | 2.01%   |
| 4.19.0  | 4         | 2.01%   |
| 5.16.7  | 3         | 1.51%   |
| 4.18.0  | 3         | 1.51%   |
| 5.9.13  | 2         | 1.01%   |
| 5.8.4   | 2         | 1.01%   |
| 5.17.5  | 2         | 1.01%   |
| 5.13.19 | 2         | 1.01%   |
| 4.18.16 | 2         | 1.01%   |
| 5.9.14  | 1         | 0.5%    |
| 5.8.13  | 1         | 0.5%    |
| 5.8.12  | 1         | 0.5%    |
| 5.7.17  | 1         | 0.5%    |
| 5.6.7   | 1         | 0.5%    |
| 5.6.5   | 1         | 0.5%    |
| 5.6.11  | 1         | 0.5%    |
| 5.5.0   | 1         | 0.5%    |
| 5.2.5   | 1         | 0.5%    |
| 5.2.0   | 1         | 0.5%    |
| 5.17.6  | 1         | 0.5%    |
| 5.17.4  | 1         | 0.5%    |
| 5.16.2  | 1         | 0.5%    |
| 5.16.18 | 1         | 0.5%    |
| 5.16.16 | 1         | 0.5%    |
| 5.16.14 | 1         | 0.5%    |
| 5.16.0  | 1         | 0.5%    |
| 5.15.26 | 1         | 0.5%    |
| 5.15.13 | 1         | 0.5%    |
| 5.15.10 | 1         | 0.5%    |
| 5.14.6  | 1         | 0.5%    |
| 5.14.10 | 1         | 0.5%    |
| 5.14.0  | 1         | 0.5%    |
| 5.12.4  | 1         | 0.5%    |
| 5.12.11 | 1         | 0.5%    |
| 5.11.6  | 1         | 0.5%    |
| 5.10.70 | 1         | 0.5%    |
| 5.10.42 | 1         | 0.5%    |
| 5.10.16 | 1         | 0.5%    |
| 5.10.10 | 1         | 0.5%    |
| 5.1.6   | 1         | 0.5%    |
| 5.0.10  | 1         | 0.5%    |
| 4.9.60  | 1         | 0.5%    |
| 4.9.56  | 1         | 0.5%    |
| 4.9.0   | 1         | 0.5%    |
| 4.4.111 | 1         | 0.5%    |
| 4.19.1  | 1         | 0.5%    |
| 4.16.13 | 1         | 0.5%    |
| 4.13.0  | 1         | 0.5%    |
| 3.10.65 | 1         | 0.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 45        | 22.96%  |
| 5.8     | 27        | 13.78%  |
| 5.11    | 15        | 7.65%   |
| 5.13    | 14        | 7.14%   |
| 5.10    | 13        | 6.63%   |
| 4.15    | 12        | 6.12%   |
| 5.3     | 10        | 5.1%    |
| 5.0     | 10        | 5.1%    |
| 5.16    | 7         | 3.57%   |
| 5.15    | 7         | 3.57%   |
| 4.19    | 5         | 2.55%   |
| 4.18    | 5         | 2.55%   |
| 5.9     | 3         | 1.53%   |
| 5.6     | 3         | 1.53%   |
| 5.17    | 3         | 1.53%   |
| 5.14    | 3         | 1.53%   |
| 4.9     | 3         | 1.53%   |
| 5.2     | 2         | 1.02%   |
| 5.12    | 2         | 1.02%   |
| 5.7     | 1         | 0.51%   |
| 5.5     | 1         | 0.51%   |
| 5.1     | 1         | 0.51%   |
| 4.4     | 1         | 0.51%   |
| 4.16    | 1         | 0.51%   |
| 4.13    | 1         | 0.51%   |
| 3.10    | 1         | 0.51%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 175       | 97.22%  |
| i686    | 3         | 1.67%   |
| armv8l  | 1         | 0.56%   |
| aarch64 | 1         | 0.56%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 111       | 59.68%  |
| Unknown    | 24        | 12.9%   |
| KDE5       | 19        | 10.22%  |
| X-Cinnamon | 7         | 3.76%   |
| XFCE       | 5         | 2.69%   |
| MATE       | 5         | 2.69%   |
| Pantheon   | 4         | 2.15%   |
| KDE        | 4         | 2.15%   |
| KDE4       | 2         | 1.08%   |
| Cinnamon   | 2         | 1.08%   |
| LXQt       | 1         | 0.54%   |
| DWM        | 1         | 0.54%   |
| awesome    | 1         | 0.54%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 141       | 77.05%  |
| Wayland | 28        | 15.3%   |
| Unknown | 13        | 7.1%    |
| Tty     | 1         | 0.55%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 110       | 59.46%  |
| GDM     | 28        | 15.14%  |
| SDDM    | 21        | 11.35%  |
| GDM3    | 11        | 5.95%   |
| LightDM | 8         | 4.32%   |
| TDM     | 5         | 2.7%    |
| KDM     | 2         | 1.08%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 131       | 71.58%  |
| Unknown | 29        | 15.85%  |
| en_GB   | 21        | 11.48%  |
| C       | 2         | 1.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 108       | 58.38%  |
| EFI  | 77        | 41.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 149       | 82.32%  |
| Overlay | 14        | 7.73%   |
| Btrfs   | 13        | 7.18%   |
| Unknown | 5         | 2.76%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 116       | 63.74%  |
| GPT     | 43        | 23.63%  |
| MBR     | 23        | 12.64%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 158       | 87.29%  |
| Yes       | 23        | 12.71%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 124       | 68.89%  |
| Yes       | 56        | 31.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 75        | 41.67%  |
| Lenovo                      | 26        | 14.44%  |
| Dell                        | 26        | 14.44%  |
| ASUSTek Computer            | 8         | 4.44%   |
| Toshiba                     | 6         | 3.33%   |
| Acer                        | 5         | 2.78%   |
| MSI                         | 4         | 2.22%   |
| Samsung Electronics         | 3         | 1.67%   |
| Gigabyte Technology         | 3         | 1.67%   |
| Unknown                     | 3         | 1.67%   |
| Chuwi                       | 2         | 1.11%   |
| Apple                       | 2         | 1.11%   |
| TECNO                       | 1         | 0.56%   |
| Sony                        | 1         | 0.56%   |
| SLIMBOOK                    | 1         | 0.56%   |
| Panasonic                   | 1         | 0.56%   |
| Notebook                    | 1         | 0.56%   |
| IP3 Tech                    | 1         | 0.56%   |
| Insyde                      | 1         | 0.56%   |
| IBM                         | 1         | 0.56%   |
| I-Life Digital Technologies | 1         | 0.56%   |
| HUAWEI                      | 1         | 0.56%   |
| Getac                       | 1         | 0.56%   |
| EVOC                        | 1         | 0.56%   |
| EUROCOM                     | 1         | 0.56%   |
| Endless                     | 1         | 0.56%   |
| Eluktronics                 | 1         | 0.56%   |
| Clevo                       | 1         | 0.56%   |
| AMI                         | 1         | 0.56%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Unknown                                 | 5         | 2.78%   |
| HP EliteBook Folio 9480m                | 3         | 1.67%   |
| HP EliteBook Folio 9470m                | 3         | 1.67%   |
| HP EliteBook 840 G3                     | 3         | 1.67%   |
| HP EliteBook 840 G1                     | 3         | 1.67%   |
| Dell XPS 13 9310                        | 3         | 1.67%   |
| Toshiba Satellite C660                  | 2         | 1.11%   |
| MSI MS-7C02                             | 2         | 1.11%   |
| HP Spectre x360 Convertible             | 2         | 1.11%   |
| HP ProBook 640 G1                       | 2         | 1.11%   |
| HP ProBook 440 G5                       | 2         | 1.11%   |
| HP Pavilion Laptop 15-cs3xxx            | 2         | 1.11%   |
| HP EliteBook 840 G2                     | 2         | 1.11%   |
| HP Compaq Mini 110c-1100                | 2         | 1.11%   |
| HP 15 Notebook PC                       | 2         | 1.11%   |
| Dell OptiPlex 7010                      | 2         | 1.11%   |
| Dell Inspiron 5767                      | 2         | 1.11%   |
| Toshiba Satellite L50-B                 | 1         | 0.56%   |
| Toshiba R84SAU2                         | 1         | 0.56%   |
| Toshiba dynabook Satellite B554/M       | 1         | 0.56%   |
| Toshiba dynabook R731/E                 | 1         | 0.56%   |
| TECNO WinPad 2                          | 1         | 0.56%   |
| Sony VGN-NS295J                         | 1         | 0.56%   |
| SLIMBOOK PROX14-AMD                     | 1         | 0.56%   |
| Samsung RC410/RC510/RC710               | 1         | 0.56%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV | 1         | 0.56%   |
| Samsung 300E4C/300E5C/300E7C            | 1         | 0.56%   |
| Panasonic CF-SX2JDQZF5                  | 1         | 0.56%   |
| Notebook P65xHP                         | 1         | 0.56%   |
| MSI 500-007A                            | 1         | 0.56%   |
| MSI 0A90                                | 1         | 0.56%   |
| Lenovo Z50-75 80EC                      | 1         | 0.56%   |
| Lenovo V330-14IKB 81B0                  | 1         | 0.56%   |
| Lenovo V310-15ISK 80SY                  | 1         | 0.56%   |
| Lenovo V14-IGL 82C2                     | 1         | 0.56%   |
| Lenovo V130-14IKB 81HQ                  | 1         | 0.56%   |
| Lenovo V110-15ISK 80TL                  | 1         | 0.56%   |
| Lenovo ThinkPad X250 20CLA21MJP         | 1         | 0.56%   |
| Lenovo ThinkPad X240 20AMS4J900         | 1         | 0.56%   |
| Lenovo ThinkPad X240 20AL00CQAU         | 1         | 0.56%   |
| Lenovo ThinkPad X131e 33672T5           | 1         | 0.56%   |
| Lenovo ThinkPad X1 Carbon 3460AE4       | 1         | 0.56%   |
| Lenovo ThinkPad T490s 20NYS8J900        | 1         | 0.56%   |
| Lenovo ThinkPad T470s W10DG 20JTS16607  | 1         | 0.56%   |
| Lenovo ThinkPad T470s 20HGS6PF09        | 1         | 0.56%   |
| Lenovo ThinkPad T460s 20FAS3QC00        | 1         | 0.56%   |
| Lenovo ThinkPad T460 20FMS1DH01         | 1         | 0.56%   |
| Lenovo ThinkPad T440p 20AWS5D200        | 1         | 0.56%   |
| Lenovo ThinkPad P52s 20LB0021US         | 1         | 0.56%   |
| Lenovo ThinkPad L480 20LTS1RE0Y         | 1         | 0.56%   |
| Lenovo ThinkPad E520 1143ADU            | 1         | 0.56%   |
| Lenovo ThinkCentre E73 10AS00CVUM       | 1         | 0.56%   |
| Lenovo IdeaPad 330S-14IKB 81F4          | 1         | 0.56%   |
| Lenovo IdeaPad 330-15IKB 81DE           | 1         | 0.56%   |
| Lenovo IdeaPad 320S-14IKB 80X4          | 1         | 0.56%   |
| Lenovo IdeaPad 3 15IIL05 81WE           | 1         | 0.56%   |
| Lenovo IdeaPad 100S-11IBY 80R2          | 1         | 0.56%   |
| IP3 Tech AP34                           | 1         | 0.56%   |
| Insyde i101c                            | 1         | 0.56%   |
| IBM System x3850 X5 -[7143B1A]          | 1         | 0.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| HP EliteBook           | 23        | 12.78%  |
| Lenovo ThinkPad        | 14        | 7.78%   |
| HP ProBook             | 11        | 6.11%   |
| HP Compaq              | 8         | 4.44%   |
| Dell OptiPlex          | 8         | 4.44%   |
| Dell Latitude          | 7         | 3.89%   |
| Dell Inspiron          | 7         | 3.89%   |
| HP Pavilion            | 6         | 3.33%   |
| Lenovo IdeaPad         | 5         | 2.78%   |
| HP ENVY                | 5         | 2.78%   |
| Unknown                | 5         | 2.78%   |
| Acer Aspire            | 4         | 2.22%   |
| Toshiba Satellite      | 3         | 1.67%   |
| HP Spectre             | 3         | 1.67%   |
| HP Laptop              | 3         | 1.67%   |
| HP 15                  | 3         | 1.67%   |
| Dell XPS               | 3         | 1.67%   |
| Toshiba dynabook       | 2         | 1.11%   |
| MSI MS-7C02            | 2         | 1.11%   |
| HP ZBook               | 2         | 1.11%   |
| Toshiba R84SAU2        | 1         | 0.56%   |
| TECNO WinPad           | 1         | 0.56%   |
| Sony VGN-NS295J        | 1         | 0.56%   |
| SLIMBOOK PROX14-AMD    | 1         | 0.56%   |
| Samsung RC410          | 1         | 0.56%   |
| Samsung 300E5EV        | 1         | 0.56%   |
| Samsung 300E4C         | 1         | 0.56%   |
| Panasonic CF-SX2JDQZF5 | 1         | 0.56%   |
| Notebook P65xHP        | 1         | 0.56%   |
| MSI 500-007A           | 1         | 0.56%   |
| MSI 0A90               | 1         | 0.56%   |
| Lenovo Z50-75          | 1         | 0.56%   |
| Lenovo V330-14IKB      | 1         | 0.56%   |
| Lenovo V310-15ISK      | 1         | 0.56%   |
| Lenovo V14-IGL         | 1         | 0.56%   |
| Lenovo V130-14IKB      | 1         | 0.56%   |
| Lenovo V110-15ISK      | 1         | 0.56%   |
| Lenovo ThinkCentre     | 1         | 0.56%   |
| IP3 Tech AP34          | 1         | 0.56%   |
| Insyde i101c           | 1         | 0.56%   |
| IBM System             | 1         | 0.56%   |
| I-Life Digital ZED     | 1         | 0.56%   |
| HUAWEI NBLK-WAX9X      | 1         | 0.56%   |
| HP ZHAN                | 1         | 0.56%   |
| HP Z400                | 1         | 0.56%   |
| HP xw4600              | 1         | 0.56%   |
| HP ProOne              | 1         | 0.56%   |
| HP Presario            | 1         | 0.56%   |
| HP OMEN                | 1         | 0.56%   |
| HP Notebook            | 1         | 0.56%   |
| HP EliteDesk           | 1         | 0.56%   |
| HP 630                 | 1         | 0.56%   |
| Gigabyte Z68XP-UD3     | 1         | 0.56%   |
| Gigabyte H110M-A       | 1         | 0.56%   |
| Gigabyte B450          | 1         | 0.56%   |
| Getac V110             | 1         | 0.56%   |
| EVOC P7xxTM1-(G)       | 1         | 0.56%   |
| EUROCOM Q6             | 1         | 0.56%   |
| Endless EF20EA         | 1         | 0.56%   |
| Eluktronics MAG-15u    | 1         | 0.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 21        | 11.67%  |
| 2013    | 20        | 11.11%  |
| 2016    | 17        | 9.44%   |
| 2015    | 17        | 9.44%   |
| 2019    | 14        | 7.78%   |
| 2012    | 14        | 7.78%   |
| 2011    | 13        | 7.22%   |
| 2020    | 12        | 6.67%   |
| 2017    | 12        | 6.67%   |
| 2014    | 12        | 6.67%   |
| 2010    | 10        | 5.56%   |
| 2007    | 5         | 2.78%   |
| 2008    | 4         | 2.22%   |
| 2021    | 2         | 1.11%   |
| 2009    | 2         | 1.11%   |
| 2006    | 2         | 1.11%   |
| Unknown | 2         | 1.11%   |
| 2005    | 1         | 0.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 138       | 76.67%  |
| Desktop     | 28        | 15.56%  |
| Convertible | 8         | 4.44%   |
| Phone       | 2         | 1.11%   |
| Mini pc     | 2         | 1.11%   |
| All in one  | 1         | 0.56%   |
| Server      | 1         | 0.56%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 169       | 92.35%  |
| Enabled  | 14        | 7.65%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 180       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 55        | 30.05%  |
| 4.01-8.0    | 41        | 22.4%   |
| 8.01-16.0   | 29        | 15.85%  |
| 16.01-24.0  | 23        | 12.57%  |
| 1.01-2.0    | 17        | 9.29%   |
| 32.01-64.0  | 8         | 4.37%   |
| 64.01-256.0 | 4         | 2.19%   |
| 24.01-32.0  | 2         | 1.09%   |
| 2.01-3.0    | 2         | 1.09%   |
| 0.51-1.0    | 2         | 1.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 63        | 31.03%  |
| 2.01-3.0    | 53        | 26.11%  |
| 3.01-4.0    | 32        | 15.76%  |
| 4.01-8.0    | 31        | 15.27%  |
| 0.51-1.0    | 17        | 8.37%   |
| 8.01-16.0   | 4         | 1.97%   |
| 64.01-256.0 | 1         | 0.49%   |
| 0.01-0.5    | 1         | 0.49%   |
| Unknown     | 1         | 0.49%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 145       | 78.8%   |
| 2      | 30        | 16.3%   |
| 4      | 3         | 1.63%   |
| 3      | 2         | 1.09%   |
| 10     | 1         | 0.54%   |
| 8      | 1         | 0.54%   |
| 6      | 1         | 0.54%   |
| 5      | 1         | 0.54%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 108       | 60%     |
| Yes       | 72        | 40%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 154       | 85.56%  |
| No        | 26        | 14.44%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 155       | 86.11%  |
| No        | 25        | 13.89%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 118       | 64.84%  |
| No        | 64        | 35.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Kenya   | 180       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City     | Computers | Percent |
|----------|-----------|---------|
| Nairobi  | 168       | 90.81%  |
| Mombasa  | 4         | 2.16%   |
| Nakuru   | 3         | 1.62%   |
| Kiambu   | 2         | 1.08%   |
| Eldoret  | 2         | 1.08%   |
| Wote     | 1         | 0.54%   |
| Nyeri    | 1         | 0.54%   |
| Narok    | 1         | 0.54%   |
| Maralal  | 1         | 0.54%   |
| Machakos | 1         | 0.54%   |
| Kisii    | 1         | 0.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 61        | 79     | 27.73%  |
| Toshiba             | 29        | 34     | 13.18%  |
| WDC                 | 26        | 34     | 11.82%  |
| Samsung Electronics | 22        | 35     | 10%     |
| Unknown             | 16        | 23     | 7.27%   |
| HGST                | 11        | 19     | 5%      |
| Hitachi             | 10        | 11     | 4.55%   |
| SanDisk             | 9         | 10     | 4.09%   |
| Crucial             | 6         | 8      | 2.73%   |
| Micron Technology   | 4         | 4      | 1.82%   |
| SPCC                | 3         | 7      | 1.36%   |
| MARSHAL             | 3         | 3      | 1.36%   |
| Team                | 2         | 2      | 0.91%   |
| SK hynix            | 2         | 3      | 0.91%   |
| Kingston            | 2         | 4      | 0.91%   |
| Intel               | 2         | 2      | 0.91%   |
| HUAWEI              | 2         | 2      | 0.91%   |
| Plextor             | 1         | 1      | 0.45%   |
| Netac               | 1         | 1      | 0.45%   |
| LITEON              | 1         | 1      | 0.45%   |
| Golden              | 1         | 1      | 0.45%   |
| Eluktro             | 1         | 1      | 0.45%   |
| China               | 1         | 1      | 0.45%   |
| CARLSTEIN           | 1         | 2      | 0.45%   |
| Apple               | 1         | 1      | 0.45%   |
| A-DATA Technology   | 1         | 1      | 0.45%   |
| Unknown             | 1         | 1      | 0.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB     | 8         | 3.43%   |
| Toshiba MQ04ABF100 1TB             | 5         | 2.15%   |
| Seagate ST500LT012-9WS142 500GB    | 5         | 2.15%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 5         | 2.15%   |
| Samsung NVMe SSD Drive 512GB       | 5         | 2.15%   |
| HGST HTS725050A7E630 500GB         | 5         | 2.15%   |
| Unknown MMC Card  64GB             | 4         | 1.72%   |
| Toshiba MQ01ABF050 500GB           | 4         | 1.72%   |
| Samsung SSD 960 EVO 1TB            | 4         | 1.72%   |
| WDC PC SN730 NVMe 512GB            | 3         | 1.29%   |
| Unknown MMC Card  32GB             | 3         | 1.29%   |
| Toshiba MQ01ABD100 1TB             | 3         | 1.29%   |
| Seagate ST9500325AS 500GB          | 3         | 1.29%   |
| Seagate ST500LT012-1DG142 500GB    | 3         | 1.29%   |
| Seagate ST500LM021-1KJ152 500GB    | 3         | 1.29%   |
| Seagate ST500DM002-1BD142 500GB    | 3         | 1.29%   |
| Crucial CT2050MX300SSD1 2TB        | 3         | 1.29%   |
| WDC WD5000LPCX-24VHAT0 500GB       | 2         | 0.86%   |
| WDC WD3200AAJS-56M0A0 320GB        | 2         | 0.86%   |
| WDC WD2500BEKT-75PVMT0 250GB       | 2         | 0.86%   |
| Unknown NCard  32GB                | 2         | 0.86%   |
| Unknown MMC Card                   | 2         | 0.86%   |
| Toshiba DT01ACA100 1TB             | 2         | 0.86%   |
| Team T253X2001T 1024GB SSD         | 2         | 0.86%   |
| SPCC Solid State Disk 256GB        | 2         | 0.86%   |
| SPCC M.2 PCIe SSD 512GB            | 2         | 0.86%   |
| Seagate ST500VT000-1DK142 500GB    | 2         | 0.86%   |
| Seagate ST500VT000-1BS142 500GB    | 2         | 0.86%   |
| Seagate ST3320418AS 320GB          | 2         | 0.86%   |
| Seagate ST250LT003-9YG14C 250GB    | 2         | 0.86%   |
| Seagate ST2000LM003 HN-M201RAD 2TB | 2         | 0.86%   |
| Seagate ST2000DM008-2FR102 2TB     | 2         | 0.86%   |
| Samsung SSD 840 EVO 250GB          | 2         | 0.86%   |
| Samsung NVMe SSD Drive 256GB       | 2         | 0.86%   |
| HUAWEI SD Storage 8GB              | 2         | 0.86%   |
| Hitachi HTS545032B9A300 320GB      | 2         | 0.86%   |
| HGST HTS721010A9 1TB               | 2         | 0.86%   |
| HGST HTS541010A9E680 1TB           | 2         | 0.86%   |
| WDC WDS100T1B0A-00H9H0 1TB SSD     | 1         | 0.43%   |
| WDC WD800GD-75FLC3 80GB            | 1         | 0.43%   |
| WDC WD5000LPVX-75V0TT0 500GB       | 1         | 0.43%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 1         | 0.43%   |
| WDC WD5000LPCX-60VHAT0 500GB       | 1         | 0.43%   |
| WDC WD5000LPCX-24C6HT0 500GB       | 1         | 0.43%   |
| WDC WD5000LPCX-22VHAT1 500GB       | 1         | 0.43%   |
| WDC WD5000BPVT-60HXZT3 500GB       | 1         | 0.43%   |
| WDC WD5000AVVS-63M8B0 500GB        | 1         | 0.43%   |
| WDC WD5000AVDS-63U7B1 500GB        | 1         | 0.43%   |
| WDC WD5000AAKX-08U6AA0 500GB       | 1         | 0.43%   |
| WDC WD3200BUCT-63TWBY0 320GB       | 1         | 0.43%   |
| WDC WD3200AAJS-56B4A0 320GB        | 1         | 0.43%   |
| WDC WD3200AAJS-00B4A0 320GB        | 1         | 0.43%   |
| WDC WD2500AAKX-08U6AA0 250GB       | 1         | 0.43%   |
| WDC WD10SPZX-60Z10T0 1TB           | 1         | 0.43%   |
| WDC WD10JPVX-60JC3T0 1TB           | 1         | 0.43%   |
| WDC WD10JPCX-24UE4T0 1TB           | 1         | 0.43%   |
| Unknown NVMe SSD Drive 1TB         | 1         | 0.43%   |
| Unknown MMC Card  4GB              | 1         | 0.43%   |
| Unknown MMC Card  2GB              | 1         | 0.43%   |
| Unknown L200 Hard drive 2TB        | 1         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 60        | 78     | 45.45%  |
| Toshiba | 24        | 29     | 18.18%  |
| WDC     | 22        | 30     | 16.67%  |
| HGST    | 11        | 19     | 8.33%   |
| Hitachi | 10        | 11     | 7.58%   |
| MARSHAL | 3         | 3      | 2.27%   |
| Unknown | 1         | 1      | 0.76%   |
| Unknown | 1         | 1      | 0.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 8         | 8      | 19.51%  |
| Samsung Electronics | 8         | 14     | 19.51%  |
| Crucial             | 6         | 8      | 14.63%  |
| Toshiba             | 2         | 2      | 4.88%   |
| Team                | 2         | 2      | 4.88%   |
| SPCC                | 2         | 3      | 4.88%   |
| Micron Technology   | 2         | 2      | 4.88%   |
| Kingston            | 2         | 4      | 4.88%   |
| WDC                 | 1         | 1      | 2.44%   |
| Plextor             | 1         | 1      | 2.44%   |
| Netac               | 1         | 1      | 2.44%   |
| LITEON              | 1         | 1      | 2.44%   |
| Intel               | 1         | 1      | 2.44%   |
| Golden              | 1         | 1      | 2.44%   |
| Eluktro             | 1         | 1      | 2.44%   |
| China               | 1         | 1      | 2.44%   |
| A-DATA Technology   | 1         | 1      | 2.44%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 119       | 172    | 57.49%  |
| SSD     | 38        | 52     | 18.36%  |
| NVMe    | 32        | 42     | 15.46%  |
| MMC     | 14        | 20     | 6.76%   |
| Unknown | 4         | 5      | 1.93%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 145       | 225    | 74.36%  |
| NVMe | 32        | 42     | 16.41%  |
| MMC  | 14        | 20     | 7.18%   |
| SAS  | 4         | 4      | 2.05%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 104       | 143    | 65.82%  |
| 0.51-1.0   | 43        | 57     | 27.22%  |
| 1.01-2.0   | 9         | 19     | 5.7%    |
| 3.01-4.0   | 1         | 4      | 0.63%   |
| 2.01-3.0   | 1         | 1      | 0.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 53        | 27.75%  |
| 101-250        | 37        | 19.37%  |
| 501-1000       | 26        | 13.61%  |
| 51-100         | 21        | 10.99%  |
| 1001-2000      | 14        | 7.33%   |
| Unknown        | 10        | 5.24%   |
| 1-20           | 9         | 4.71%   |
| 21-50          | 8         | 4.19%   |
| More than 3000 | 7         | 3.66%   |
| 2001-3000      | 6         | 3.14%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 54        | 27.55%  |
| 21-50          | 33        | 16.84%  |
| 101-250        | 33        | 16.84%  |
| 51-100         | 23        | 11.73%  |
| 251-500        | 20        | 10.2%   |
| Unknown        | 10        | 5.1%    |
| 1001-2000      | 9         | 4.59%   |
| 501-1000       | 9         | 4.59%   |
| More than 3000 | 4         | 2.04%   |
| 2001-3000      | 1         | 0.51%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD2500BEKT-75PVMT0 250GB       | 2         | 2      | 8%      |
| Seagate ST500LT012-1DG142 500GB    | 2         | 2      | 8%      |
| WDC WD3200AAJS-56M0A0 320GB        | 1         | 1      | 4%      |
| WDC WD10SPZX-60Z10T0 1TB           | 1         | 1      | 4%      |
| Toshiba MQ01ABF050 500GB           | 1         | 1      | 4%      |
| Toshiba MQ01ABD100 1TB             | 1         | 1      | 4%      |
| Toshiba MQ01ABD050V 500GB          | 1         | 1      | 4%      |
| Toshiba MK3263GSX 320GB            | 1         | 1      | 4%      |
| Toshiba MK3252GSX 320GB            | 1         | 1      | 4%      |
| Toshiba MK2555GSX 250GB            | 1         | 1      | 4%      |
| Seagate ST9500325AS 500GB          | 1         | 1      | 4%      |
| Seagate ST500DM002-1BD142 500GB    | 1         | 1      | 4%      |
| Seagate ST1000LM035-1RK172 1TB     | 1         | 1      | 4%      |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 4%      |
| MARSHAL MAL2750SA-T54 752GB        | 1         | 1      | 4%      |
| Hitachi HTS545032B9A300 320GB      | 1         | 1      | 4%      |
| Hitachi HTS542525K9SA00 250GB      | 1         | 1      | 4%      |
| HGST HTS725050A7E630 500GB         | 1         | 1      | 4%      |
| HGST HTS721010A9 1TB               | 1         | 2      | 4%      |
| HGST HTS541515A9E630 1TB           | 1         | 2      | 4%      |
| HGST HTS541010A9E680 1TB           | 1         | 2      | 4%      |
| Crucial CT2050MX300SSD1 2TB        | 1         | 2      | 4%      |
| Unknown                            | 1         | 1      | 4%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 6         | 6      | 25%     |
| Seagate | 6         | 6      | 25%     |
| WDC     | 4         | 4      | 16.67%  |
| HGST    | 3         | 7      | 12.5%   |
| Hitachi | 2         | 2      | 8.33%   |
| MARSHAL | 1         | 1      | 4.17%   |
| Crucial | 1         | 2      | 4.17%   |
| Unknown | 1         | 1      | 4.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 6         | 6      | 26.09%  |
| Seagate | 6         | 6      | 26.09%  |
| WDC     | 4         | 4      | 17.39%  |
| HGST    | 3         | 7      | 13.04%  |
| Hitachi | 2         | 2      | 8.7%    |
| MARSHAL | 1         | 1      | 4.35%   |
| Unknown | 1         | 1      | 4.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 22        | 27     | 95.65%  |
| SSD  | 1         | 2      | 4.35%   |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 119       | 171    | 63.64%  |
| Works    | 46        | 91     | 24.6%   |
| Malfunc  | 22        | 29     | 11.76%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 152       | 76.77%  |
| Samsung Electronics          | 16        | 8.08%   |
| AMD                          | 10        | 5.05%   |
| SanDisk                      | 4         | 2.02%   |
| Toshiba America Info Systems | 3         | 1.52%   |
| SK hynix                     | 2         | 1.01%   |
| Micron Technology            | 2         | 1.01%   |
| LSI Logic / Symbios Logic    | 2         | 1.01%   |
| Silicon Motion               | 1         | 0.51%   |
| Shenzhen Longsys Electronics | 1         | 0.51%   |
| Realtek Semiconductor        | 1         | 0.51%   |
| Marvell Technology Group     | 1         | 0.51%   |
| Broadcom / LSI               | 1         | 0.51%   |
| ASMedia Technology           | 1         | 0.51%   |
| Apple                        | 1         | 0.51%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 23        | 10.6%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 14        | 6.45%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 11        | 5.07%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 10        | 4.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 10        | 4.61%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 9         | 4.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 9         | 4.15%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 9         | 4.15%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 6         | 2.76%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 5         | 2.3%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 4         | 1.84%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 4         | 1.84%   |
| Intel SATA Controller [RAID mode]                                                      | 4         | 1.84%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 4         | 1.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 4         | 1.84%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]           | 4         | 1.84%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 3         | 1.38%   |
| Samsung NVMe SSD Controller 980                                                        | 3         | 1.38%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 3         | 1.38%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 3         | 1.38%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 3         | 1.38%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                   | 3         | 1.38%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 1.38%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 3         | 1.38%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 3         | 1.38%   |
| AMD 400 Series Chipset SATA Controller                                                 | 3         | 1.38%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 2         | 0.92%   |
| Micron Non-Volatile memory controller                                                  | 2         | 0.92%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 2         | 0.92%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 2         | 0.92%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 2         | 0.92%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                             | 2         | 0.92%   |
| Intel 82Q35 Express PT IDER Controller                                                 | 2         | 0.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 2         | 0.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 0.92%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 2         | 0.92%   |
| Intel 4 Series Chipset PT IDER Controller                                              | 2         | 0.92%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                       | 2         | 0.92%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 1         | 0.46%   |
| SK hynix BC511                                                                         | 1         | 0.46%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 1         | 0.46%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 1         | 0.46%   |
| Shenzhen Longsys SM2263EN/SM2263XT-based OEM SSD                                       | 1         | 0.46%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 1         | 0.46%   |
| Realtek RTS5763DL NVMe SSD Controller                                                  | 1         | 0.46%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                                  | 1         | 0.46%   |
| LSI Logic / Symbios Logic SAS1064ET PCI-Express Fusion-MPT SAS                         | 1         | 0.46%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2008 [Falcon]                                   | 1         | 0.46%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 1         | 0.46%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 1         | 0.46%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                       | 1         | 0.46%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                             | 1         | 0.46%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                   | 1         | 0.46%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                    | 1         | 0.46%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                           | 1         | 0.46%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 0.46%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 1         | 0.46%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 1         | 0.46%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 0.46%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 0.46%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 133       | 65.2%   |
| NVMe | 32        | 15.69%  |
| RAID | 20        | 9.8%    |
| IDE  | 18        | 8.82%   |
| SCSI | 1         | 0.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 165       | 91.67%  |
| AMD    | 13        | 7.22%   |
| ARM    | 2         | 1.11%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz           | 5         | 2.78%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 5         | 2.78%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 4         | 2.22%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 4         | 2.22%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 3         | 1.67%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 3         | 1.67%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 3         | 1.67%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 3         | 1.67%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 3         | 1.67%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 3         | 1.67%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 3         | 1.67%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 3         | 1.67%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 3         | 1.67%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 1.11%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 1.11%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 2         | 1.11%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.11%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2         | 1.11%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 2         | 1.11%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.11%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 2         | 1.11%   |
| Intel Core i5-3437U CPU @ 1.90GHz           | 2         | 1.11%   |
| Intel Core i5-3427U CPU @ 1.80GHz           | 2         | 1.11%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 1.11%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 2         | 1.11%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 1.11%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 1.11%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 2         | 1.11%   |
| Intel Core i3-4100M CPU @ 2.50GHz           | 2         | 1.11%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 2         | 1.11%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 2         | 1.11%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 2         | 1.11%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 2         | 1.11%   |
| Intel Celeron CPU 1007U @ 1.50GHz           | 2         | 1.11%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 2         | 1.11%   |
| Intel Atom CPU N270 @ 1.60GHz               | 2         | 1.11%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2         | 1.11%   |
| AMD Ryzen 7 4700U with Radeon Graphics      | 2         | 1.11%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2         | 1.11%   |
| Intel Xeon E-2186M CPU @ 2.90GHz            | 1         | 0.56%   |
| Intel Xeon CPU W3680 @ 3.33GHz              | 1         | 0.56%   |
| Intel Xeon CPU E7- 4870 @ 2.40GHz           | 1         | 0.56%   |
| Intel Xeon CPU E5-1630 v3 @ 3.70GHz         | 1         | 0.56%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1         | 0.56%   |
| Intel Pentium CPU N3510 @ 1.99GHz           | 1         | 0.56%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 0.56%   |
| Intel Pentium CPU 2117U @ 1.80GHz           | 1         | 0.56%   |
| Intel Pentium 4 CPU 3.20GHz                 | 1         | 0.56%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1         | 0.56%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz            | 1         | 0.56%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1         | 0.56%   |
| Intel Core i9-9880H CPU @ 2.30GHz           | 1         | 0.56%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 0.56%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 0.56%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 0.56%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1         | 0.56%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 0.56%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.56%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 0.56%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 48        | 26.67%  |
| Intel Core i7           | 42        | 23.33%  |
| Intel Core i3           | 17        | 9.44%   |
| Intel Celeron           | 17        | 9.44%   |
| Intel Atom              | 8         | 4.44%   |
| Intel Core 2 Duo        | 7         | 3.89%   |
| Other                   | 6         | 3.33%   |
| Intel Pentium           | 5         | 2.78%   |
| AMD Ryzen 7             | 5         | 2.78%   |
| Intel Xeon              | 4         | 2.22%   |
| Intel Pentium Dual-Core | 3         | 1.67%   |
| Intel Core 2            | 3         | 1.67%   |
| AMD Ryzen 5             | 3         | 1.67%   |
| Intel Pentium 4         | 2         | 1.11%   |
| Intel Core i9           | 2         | 1.11%   |
| AMD FX                  | 2         | 1.11%   |
| AMD A10                 | 2         | 1.11%   |
| Intel Core m3           | 1         | 0.56%   |
| Intel Core 2 Quad       | 1         | 0.56%   |
| ARM AArch64             | 1         | 0.56%   |
| AMD A4                  | 1         | 0.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 103       | 57.22%  |
| 4       | 53        | 29.44%  |
| 6       | 8         | 4.44%   |
| 8       | 7         | 3.89%   |
| 1       | 5         | 2.78%   |
| 3       | 2         | 1.11%   |
| 20      | 1         | 0.56%   |
| Unknown | 1         | 0.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 178       | 98.89%  |
| 2      | 2         | 1.11%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 127       | 70.56%  |
| 1       | 52        | 28.89%  |
| Unknown | 1         | 0.56%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 178       | 98.89%  |
| 32-bit         | 2         | 1.11%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 38        | 20.11%  |
| 0x306a9    | 16        | 8.47%   |
| 0x206a7    | 14        | 7.41%   |
| 0x40651    | 11        | 5.82%   |
| 0x306c3    | 9         | 4.76%   |
| 0x806ea    | 7         | 3.7%    |
| 0x406e3    | 7         | 3.7%    |
| 0x306d4    | 6         | 3.17%   |
| 0x30678    | 6         | 3.17%   |
| 0x1067a    | 6         | 3.17%   |
| 0x906ea    | 5         | 2.65%   |
| 0x806c1    | 5         | 2.65%   |
| 0x806ec    | 4         | 2.12%   |
| 0x506e3    | 4         | 2.12%   |
| 0x20655    | 4         | 2.12%   |
| 0x806e9    | 3         | 1.59%   |
| 0x406c4    | 3         | 1.59%   |
| 0x0800820d | 3         | 1.59%   |
| 0x906e9    | 2         | 1.06%   |
| 0x806eb    | 2         | 1.06%   |
| 0x706e5    | 2         | 1.06%   |
| 0x706a8    | 2         | 1.06%   |
| 0x706a1    | 2         | 1.06%   |
| 0x6f6      | 2         | 1.06%   |
| 0x406c3    | 2         | 1.06%   |
| 0x106c2    | 2         | 1.06%   |
| 0x10676    | 2         | 1.06%   |
| 0xf65      | 1         | 0.53%   |
| 0xf43      | 1         | 0.53%   |
| 0x906ec    | 1         | 0.53%   |
| 0x6fd      | 1         | 0.53%   |
| 0x6fa      | 1         | 0.53%   |
| 0x6f7      | 1         | 0.53%   |
| 0x6f2      | 1         | 0.53%   |
| 0x506c9    | 1         | 0.53%   |
| 0x306f2    | 1         | 0.53%   |
| 0x30673    | 1         | 0.53%   |
| 0x206f2    | 1         | 0.53%   |
| 0x206c2    | 1         | 0.53%   |
| 0x08600106 | 1         | 0.53%   |
| 0x08600104 | 1         | 0.53%   |
| 0x08600103 | 1         | 0.53%   |
| 0x08108109 | 1         | 0.53%   |
| 0x08108102 | 1         | 0.53%   |
| 0x0600611a | 1         | 0.53%   |
| 0x06001119 | 1         | 0.53%   |
| 0x0600084f | 1         | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 34        | 18.89%  |
| Haswell       | 25        | 13.89%  |
| IvyBridge     | 17        | 9.44%   |
| Skylake       | 15        | 8.33%   |
| Silvermont    | 15        | 8.33%   |
| SandyBridge   | 14        | 7.78%   |
| Penryn        | 8         | 4.44%   |
| Westmere      | 7         | 3.89%   |
| Core          | 6         | 3.33%   |
| Broadwell     | 6         | 3.33%   |
| Zen+          | 5         | 2.78%   |
| TigerLake     | 5         | 2.78%   |
| Goldmont plus | 4         | 2.22%   |
| Zen 2         | 3         | 1.67%   |
| IceLake       | 3         | 1.67%   |
| Piledriver    | 2         | 1.11%   |
| NetBurst      | 2         | 1.11%   |
| Goldmont      | 2         | 1.11%   |
| Excavator     | 2         | 1.11%   |
| Bonnell       | 2         | 1.11%   |
| Unknown       | 2         | 1.11%   |
| Steamroller   | 1         | 0.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 145       | 72.86%  |
| Nvidia                     | 27        | 13.57%  |
| AMD                        | 26        | 13.07%  |
| Matrox Electronics Systems | 1         | 0.5%    |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 14        | 6.9%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 13        | 6.4%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12        | 5.91%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 4.43%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 4.43%   |
| Intel UHD Graphics 620                                                                   | 8         | 3.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 3.94%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 8         | 3.94%   |
| Intel HD Graphics 620                                                                    | 7         | 3.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 3.45%   |
| Intel HD Graphics 5500                                                                   | 6         | 2.96%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 2.96%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 2.46%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.97%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.97%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 1.97%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 1.48%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 1.48%   |
| Intel HD Graphics 530                                                                    | 3         | 1.48%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3         | 1.48%   |
| AMD Renoir                                                                               | 3         | 1.48%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.99%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 0.99%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 2         | 0.99%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 0.99%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 0.99%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.99%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.99%   |
| Intel HD Graphics 500                                                                    | 2         | 0.99%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 0.99%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 0.99%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 0.99%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 0.99%   |
| Nvidia TU104BM [GeForce RTX 2080 Mobile]                                                 | 1         | 0.49%   |
| Nvidia GT218M [GeForce 315M]                                                             | 1         | 0.49%   |
| Nvidia GT218 [NVS 300]                                                                   | 1         | 0.49%   |
| Nvidia GP108GLM [Quadro P500 Mobile]                                                     | 1         | 0.49%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 1         | 0.49%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.49%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                                  | 1         | 0.49%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.49%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 0.49%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.49%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.49%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1         | 0.49%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 1         | 0.49%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 1         | 0.49%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 1         | 0.49%   |
| Nvidia G94GL [Quadro FX 1800]                                                            | 1         | 0.49%   |
| Nvidia G84M [GeForce 8600M GT]                                                           | 1         | 0.49%   |
| Nvidia G72M [GeForce Go 7400]                                                            | 1         | 0.49%   |
| Matrox Electronics Systems MGA G200EV                                                    | 1         | 0.49%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 0.49%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 1         | 0.49%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1         | 0.49%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 0.49%   |
| Intel HD Graphics 630                                                                    | 1         | 0.49%   |
| Intel HD Graphics 520                                                                    | 1         | 0.49%   |
| Intel HD Graphics 515                                                                    | 1         | 0.49%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 126       | 69.23%  |
| 1 x AMD        | 19        | 10.44%  |
| 1 x Nvidia     | 16        | 8.79%   |
| Intel + Nvidia | 11        | 6.04%   |
| Intel + AMD    | 6         | 3.3%    |
| Other          | 2         | 1.1%    |
| 2 x AMD        | 1         | 0.55%   |
| 1 x Matrox     | 1         | 0.55%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 170       | 93.41%  |
| Proprietary | 9         | 4.95%   |
| Unknown     | 3         | 1.65%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 138       | 75%     |
| 1.01-2.0   | 13        | 7.07%   |
| 0.01-0.5   | 11        | 5.98%   |
| 3.01-4.0   | 9         | 4.89%   |
| 0.51-1.0   | 7         | 3.8%    |
| 7.01-8.0   | 6         | 3.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 35        | 19.23%  |
| Chimei Innolux          | 27        | 14.84%  |
| BOE                     | 24        | 13.19%  |
| LG Display              | 22        | 12.09%  |
| Hewlett-Packard         | 17        | 9.34%   |
| Samsung Electronics     | 12        | 6.59%   |
| Dell                    | 8         | 4.4%    |
| Lenovo                  | 5         | 2.75%   |
| Sharp                   | 4         | 2.2%    |
| InfoVision              | 4         | 2.2%    |
| Sony                    | 3         | 1.65%   |
| Chi Mei Optoelectronics | 3         | 1.65%   |
| Apple                   | 3         | 1.65%   |
| Unknown (XXX)           | 2         | 1.1%    |
| LG Philips              | 2         | 1.1%    |
| KDC                     | 2         | 1.1%    |
| HannStar                | 2         | 1.1%    |
| VIE                     | 1         | 0.55%   |
| Unknown                 | 1         | 0.55%   |
| Hitachi                 | 1         | 0.55%   |
| Eizo                    | 1         | 0.55%   |
| CVT                     | 1         | 0.55%   |
| BenQ                    | 1         | 0.55%   |
| Acer                    | 1         | 0.55%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                  | 3         | 1.62%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 1.62%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 3         | 1.62%   |
| Chimei Innolux LCD Monitor CMN14A3 1600x900 309x174mm 14.0-inch          | 3         | 1.62%   |
| Samsung Electronics S22E450 SAM0C7A 1920x1080 477x268mm 21.5-inch        | 2         | 1.08%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 1.08%   |
| Lenovo T2224zD LEN60CB 1920x1080 476x267mm 21.5-inch                     | 2         | 1.08%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 2         | 1.08%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch         | 2         | 1.08%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x173mm 13.9-inch          | 2         | 1.08%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x194mm 15.5-inch | 2         | 1.08%   |
| BOE LCD Monitor BOE0780 1920x1080 344x194mm 15.5-inch                    | 2         | 1.08%   |
| BOE LCD Monitor BOE0695 1920x1080 380x210mm 17.1-inch                    | 2         | 1.08%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 1.08%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch            | 2         | 1.08%   |
| AU Optronics LCD Monitor AUO223E 1600x900 309x174mm 14.0-inch            | 2         | 1.08%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 2         | 1.08%   |
| VIE LED MONITOR VIE2302 1920x1080 473x296mm 22.0-inch                    | 1         | 0.54%   |
| Unknown LCD Monitor Hitachi Engineering Company Ltd HISENSE 3200x1080    | 1         | 0.54%   |
| Unknown (XXX) LEDTV XXX0001 1366x768 575x323mm 26.0-inch                 | 1         | 0.54%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch           | 1         | 0.54%   |
| Sony TV SNYEF03 1600x900                                                 | 1         | 0.54%   |
| Sony TV SNYDC02 1920x1080 930x523mm 42.0-inch                            | 1         | 0.54%   |
| Sony TV SNY0902 1360x768                                                 | 1         | 0.54%   |
| Sharp LQ133T1JW02 SHP13FF 2560x1440 294x165mm 13.3-inch                  | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch     | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch     | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 309x174mm 14.0-inch     | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC3051 1366x768 344x194mm 15.5-inch     | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SDC4942 1366x768 309x174mm 14.0-inch     | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SAM7017 3840x2160 950x540mm 43.0-inch    | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch     | 1         | 0.54%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch              | 1         | 0.54%   |
| LG Philips LCD Monitor LPL0132 1280x800 304x190mm 14.1-inch              | 1         | 0.54%   |
| LG Display LCD Monitor LGD0619 1920x1080 309x174mm 14.0-inch             | 1         | 0.54%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch             | 1         | 0.54%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch             | 1         | 0.54%   |
| LG Display LCD Monitor LGD0588 3840x2160 293x165mm 13.2-inch             | 1         | 0.54%   |
| LG Display LCD Monitor LGD0532 1920x1080 344x194mm 15.5-inch             | 1         | 0.54%   |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch              | 1         | 0.54%   |
| LG Display LCD Monitor LGD04FD 1366x768 344x194mm 15.5-inch              | 1         | 0.54%   |
| LG Display LCD Monitor LGD0493 1366x768 344x194mm 15.5-inch              | 1         | 0.54%   |
| LG Display LCD Monitor LGD048B 1366x768 309x174mm 14.0-inch              | 1         | 0.54%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 1         | 0.54%   |
| LG Display LCD Monitor LGD045E 1366x768 309x174mm 14.0-inch              | 1         | 0.54%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch              | 1         | 0.54%   |
| LG Display LCD Monitor LGD03CD 1366x768 277x156mm 12.5-inch              | 1         | 0.54%   |
| LG Display LCD Monitor LGD03B8 1366x768 310x174mm 14.0-inch              | 1         | 0.54%   |
| LG Display LCD Monitor LGD03AD 1366x768 309x174mm 14.0-inch              | 1         | 0.54%   |
| LG Display LCD Monitor LGD0386 1366x768 309x174mm 14.0-inch              | 1         | 0.54%   |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch              | 1         | 0.54%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch              | 1         | 0.54%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch              | 1         | 0.54%   |
| Lenovo LEN S24e-10 LEN61CA 1920x1080 527x296mm 23.8-inch                 | 1         | 0.54%   |
| Lenovo LEN LI1931ewA LEN65A1 1366x768 409x230mm 18.5-inch                | 1         | 0.54%   |
| Lenovo LEN E2054A LEN60DF 1440x900 420x260mm 19.4-inch                   | 1         | 0.54%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 1         | 0.54%   |
| KDC LCD Monitor KDC05F1 1366x768 344x193mm 15.5-inch                     | 1         | 0.54%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                     | 1         | 0.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 74        | 41.81%  |
| 1920x1080 (FHD)    | 55        | 31.07%  |
| 1600x900 (HD+)     | 13        | 7.34%   |
| 1280x1024 (SXGA)   | 6         | 3.39%   |
| 1920x1200 (WUXGA)  | 5         | 2.82%   |
| 3840x2160 (4K)     | 4         | 2.26%   |
| 1440x900 (WXGA+)   | 3         | 1.69%   |
| 1280x800 (WXGA)    | 3         | 1.69%   |
| 2560x1440 (QHD)    | 2         | 1.13%   |
| 1024x600           | 2         | 1.13%   |
| Unknown            | 2         | 1.13%   |
| 3440x1440          | 1         | 0.56%   |
| 3200x1080          | 1         | 0.56%   |
| 3072x1920          | 1         | 0.56%   |
| 2560x1080          | 1         | 0.56%   |
| 2160x1440          | 1         | 0.56%   |
| 1680x1050 (WSXGA+) | 1         | 0.56%   |
| 1360x768           | 1         | 0.56%   |
| 1024x768 (XGA)     | 1         | 0.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 54        | 29.83%  |
| 13      | 36        | 19.89%  |
| 14      | 28        | 15.47%  |
| 21      | 6         | 3.31%   |
| 17      | 6         | 3.31%   |
| 11      | 6         | 3.31%   |
| 19      | 5         | 2.76%   |
| 12      | 5         | 2.76%   |
| 24      | 4         | 2.21%   |
| 23      | 4         | 2.21%   |
| 18      | 4         | 2.21%   |
| 10      | 3         | 1.66%   |
| 84      | 2         | 1.1%    |
| 72      | 2         | 1.1%    |
| 46      | 2         | 1.1%    |
| 34      | 2         | 1.1%    |
| 27      | 2         | 1.1%    |
| 22      | 2         | 1.1%    |
| 20      | 2         | 1.1%    |
| Unknown | 2         | 1.1%    |
| 54      | 1         | 0.55%   |
| 31      | 1         | 0.55%   |
| 26      | 1         | 0.55%   |
| 16      | 1         | 0.55%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 107       | 60.11%  |
| 201-300     | 27        | 15.17%  |
| 401-500     | 12        | 6.74%   |
| 501-600     | 11        | 6.18%   |
| 351-400     | 9         | 5.06%   |
| 1501-2000   | 4         | 2.25%   |
| 1001-1500   | 2         | 1.12%   |
| Unknown     | 2         | 1.12%   |
| 801-900     | 1         | 0.56%   |
| 701-800     | 1         | 0.56%   |
| 601-700     | 1         | 0.56%   |
| 901-1000    | 1         | 0.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 143       | 82.18%  |
| 16/10   | 19        | 10.92%  |
| 5/4     | 6         | 3.45%   |
| 21/9    | 2         | 1.15%   |
| Unknown | 2         | 1.15%   |
| 4/3     | 1         | 0.57%   |
| 3/2     | 1         | 0.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 54        | 30%     |
| 81-90          | 51        | 28.33%  |
| 71-80          | 13        | 7.22%   |
| 151-200        | 10        | 5.56%   |
| 201-250        | 8         | 4.44%   |
| 141-150        | 7         | 3.89%   |
| 51-60          | 6         | 3.33%   |
| More than 1000 | 5         | 2.78%   |
| 61-70          | 5         | 2.78%   |
| 251-300        | 5         | 2.78%   |
| 351-500        | 3         | 1.67%   |
| 41-50          | 3         | 1.67%   |
| 121-130        | 3         | 1.67%   |
| 301-350        | 2         | 1.11%   |
| 501-1000       | 2         | 1.11%   |
| Unknown        | 2         | 1.11%   |
| 111-120        | 1         | 0.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 67        | 37.85%  |
| 121-160       | 56        | 31.64%  |
| 51-100        | 34        | 19.21%  |
| 161-240       | 12        | 6.78%   |
| 1-50          | 5         | 2.82%   |
| Unknown       | 2         | 1.13%   |
| More than 240 | 1         | 0.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 152       | 83.06%  |
| 2     | 23        | 12.57%  |
| 0     | 7         | 3.83%   |
| 3     | 1         | 0.55%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 110       | 40%     |
| Realtek Semiconductor             | 74        | 26.91%  |
| Qualcomm Atheros                  | 35        | 12.73%  |
| Broadcom                          | 18        | 6.55%   |
| MediaTek                          | 7         | 2.55%   |
| Hewlett-Packard                   | 5         | 1.82%   |
| Huawei Technologies               | 4         | 1.45%   |
| Sierra Wireless                   | 3         | 1.09%   |
| Ralink Technology                 | 3         | 1.09%   |
| T & A Mobile Phones               | 2         | 0.73%   |
| Ralink                            | 2         | 0.73%   |
| OPPO Electronics                  | 2         | 0.73%   |
| Marvell Technology Group          | 2         | 0.73%   |
| Broadcom Limited                  | 2         | 0.73%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.36%   |
| Spreadtrum Communications         | 1         | 0.36%   |
| Samsung Electronics               | 1         | 0.36%   |
| Qualcomm                          | 1         | 0.36%   |
| IBM                               | 1         | 0.36%   |
| Ericsson Business Mobile Networks | 1         | 0.36%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 43        | 12.57%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 16        | 4.68%   |
| Intel Wireless 7260                                               | 16        | 4.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16        | 4.68%   |
| Intel Ethernet Connection I218-LM                                 | 12        | 3.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 9         | 2.63%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 8         | 2.34%   |
| Intel Wireless 7265                                               | 8         | 2.34%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 2.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 2.05%   |
| Intel Wireless 8265 / 8275                                        | 7         | 2.05%   |
| MediaTek moto e(6) plus                                           | 6         | 1.75%   |
| Intel Wireless 8260                                               | 6         | 1.75%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 1.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 1.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 6         | 1.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.46%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 1.46%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 1.17%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 1.17%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 0.88%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.88%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.88%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.88%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 0.88%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 0.88%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 3         | 0.88%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 0.88%   |
| T & A Mobile Phones TCL 30                                        | 2         | 0.58%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.58%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 2         | 0.58%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.58%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.58%   |
| Ralink MT7601U Wireless Adapter                                   | 2         | 0.58%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.58%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.58%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.58%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.58%   |
| OPPO SDM720G-IDP _SN:B922E265                                     | 2         | 0.58%   |
| MediaTek RMX3085                                                  | 2         | 0.58%   |
| Intel Wireless-AC 9260                                            | 2         | 0.58%   |
| Intel Wireless 3165                                               | 2         | 0.58%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.58%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 0.58%   |
| Intel Centrino Advanced-N 6235                                    | 2         | 0.58%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.58%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.58%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2         | 0.58%   |
| Huawei E353/E3131                                                 | 2         | 0.58%   |
| HP lt4120 Snapdragon X5 LTE                                       | 2         | 0.58%   |
| HP lt4112 Gobi 4G Module Network Device                           | 2         | 0.58%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 2         | 0.58%   |
| ZTE WCDMA MSM ZTE MSM                                             | 1         | 0.29%   |
| Spreadtrum Unisoc Phone                                           | 1         | 0.29%   |
| Sierra Wireless EM7455                                            | 1         | 0.29%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.29%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 84        | 51.53%  |
| Qualcomm Atheros      | 29        | 17.79%  |
| Realtek Semiconductor | 26        | 15.95%  |
| Broadcom              | 13        | 7.98%   |
| Sierra Wireless       | 3         | 1.84%   |
| Ralink Technology     | 3         | 1.84%   |
| Hewlett-Packard       | 3         | 1.84%   |
| Ralink                | 2         | 1.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                                     | 16        | 9.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 5.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 8         | 4.91%   |
| Intel Wireless 7265                                                     | 8         | 4.91%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 4.29%   |
| Intel Wireless 8265 / 8275                                              | 7         | 4.29%   |
| Intel Wireless 8260                                                     | 6         | 3.68%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 3.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 3.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 3.07%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 3.07%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 2.45%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 1.84%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 1.84%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.84%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 1.84%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.84%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 1.84%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.84%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.23%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 2         | 1.23%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 1.23%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.23%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 1.23%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 1.23%   |
| Intel Wireless-AC 9260                                                  | 2         | 1.23%   |
| Intel Wireless 3165                                                     | 2         | 1.23%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.23%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 1.23%   |
| HP lt4112 Gobi 4G Module Network Device                                 | 2         | 1.23%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 2         | 1.23%   |
| Sierra Wireless EM7455                                                  | 1         | 0.61%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.61%   |
| Sierra Wireless EM7305 Modem                                            | 1         | 0.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.61%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.61%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.61%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.61%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.61%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                  | 1         | 0.61%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.61%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 1         | 0.61%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.61%   |
| Intel Wireless 3160                                                     | 1         | 0.61%   |
| Intel WiFi Link 5100                                                    | 1         | 0.61%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 0.61%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.61%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 0.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 0.61%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 0.61%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                           | 1         | 0.61%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 0.61%   |
| HP lt4111 LTE/EV-DO/HSPA+ Gobi 4G Module                                | 1         | 0.61%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                      | 1         | 0.61%   |
| Broadcom BCM4361 802.11ac Dual-Band Wireless Network Controller         | 1         | 0.61%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 1         | 0.61%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 1         | 0.61%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 1         | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 70        | 40.46%  |
| Realtek Semiconductor      | 64        | 36.99%  |
| Qualcomm Atheros           | 9         | 5.2%    |
| MediaTek                   | 7         | 4.05%   |
| Broadcom                   | 6         | 3.47%   |
| T & A Mobile Phones        | 2         | 1.16%   |
| OPPO Electronics           | 2         | 1.16%   |
| Marvell Technology Group   | 2         | 1.16%   |
| Huawei Technologies        | 2         | 1.16%   |
| Hewlett-Packard            | 2         | 1.16%   |
| Broadcom Limited           | 2         | 1.16%   |
| ZTE WCDMA Technologies MSM | 1         | 0.58%   |
| Spreadtrum Communications  | 1         | 0.58%   |
| Samsung Electronics        | 1         | 0.58%   |
| Qualcomm                   | 1         | 0.58%   |
| IBM                        | 1         | 0.58%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 43        | 24.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 16        | 9.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16        | 9.09%   |
| Intel Ethernet Connection I218-LM                                 | 12        | 6.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 3.98%   |
| MediaTek moto e(6) plus                                           | 6         | 3.41%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 3.41%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 2.27%   |
| Intel Ethernet Connection I217-V                                  | 3         | 1.7%    |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.7%    |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.7%    |
| Intel 82579V Gigabit Network Connection                           | 3         | 1.7%    |
| T & A Mobile Phones TCL 30                                        | 2         | 1.14%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 1.14%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.14%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 1.14%   |
| OPPO SDM720G-IDP _SN:B922E265                                     | 2         | 1.14%   |
| MediaTek RMX3085                                                  | 2         | 1.14%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 1.14%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.14%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 1.14%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2         | 1.14%   |
| Huawei E353/E3131                                                 | 2         | 1.14%   |
| HP lt4120 Snapdragon X5 LTE                                       | 2         | 1.14%   |
| ZTE WCDMA MSM ZTE MSM                                             | 1         | 0.57%   |
| Spreadtrum Unisoc Phone                                           | 1         | 0.57%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.57%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.57%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.57%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.57%   |
| Qualcomm Android                                                  | 1         | 0.57%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.57%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.57%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1         | 0.57%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.57%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.57%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.57%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.57%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.57%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.57%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 0.57%   |
| Intel 82580 Gigabit Network Connection                            | 1         | 0.57%   |
| Intel 82578DM Gigabit Network Connection                          | 1         | 0.57%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 0.57%   |
| Intel 82567V-4 Gigabit Network Connection                         | 1         | 0.57%   |
| IBM RNDIS/CDC ETHER                                               | 1         | 0.57%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 1         | 0.57%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 0.57%   |
| Broadcom NetXtreme BCM5753M Gigabit Ethernet PCI Express          | 1         | 0.57%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 0.57%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.57%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.57%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1         | 0.57%   |
| Broadcom Limited NetXtreme BCM5752 Gigabit Ethernet PCI Express   | 1         | 0.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 155       | 49.68%  |
| Ethernet | 154       | 49.36%  |
| Modem    | 3         | 0.96%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 129       | 72.47%  |
| Ethernet | 49        | 27.53%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 116       | 64.44%  |
| 1     | 52        | 28.89%  |
| 0     | 9         | 5%      |
| 3     | 2         | 1.11%   |
| 6     | 1         | 0.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 177       | 98.33%  |
| Yes  | 3         | 1.67%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 70        | 59.32%  |
| Qualcomm Atheros Communications | 17        | 14.41%  |
| Realtek Semiconductor           | 8         | 6.78%   |
| Broadcom                        | 6         | 5.08%   |
| Lite-On Technology              | 3         | 2.54%   |
| IMC Networks                    | 3         | 2.54%   |
| Hewlett-Packard                 | 3         | 2.54%   |
| Toshiba                         | 1         | 0.85%   |
| Realtek                         | 1         | 0.85%   |
| Ralink                          | 1         | 0.85%   |
| Foxconn / Hon Hai               | 1         | 0.85%   |
| Dell                            | 1         | 0.85%   |
| Cambridge Silicon Radio         | 1         | 0.85%   |
| Apple                           | 1         | 0.85%   |
| Alps Electric                   | 1         | 0.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 39        | 33.05%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 11        | 9.32%   |
| Qualcomm Atheros  Bluetooth Device                  | 10        | 8.47%   |
| Intel AX201 Bluetooth                               | 7         | 5.93%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 3.39%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 3.39%   |
| Intel AX200 Bluetooth                               | 4         | 3.39%   |
| Realtek Bluetooth Radio                             | 3         | 2.54%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 2.54%   |
| Intel Bluetooth Device                              | 3         | 2.54%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 1.69%   |
| IMC Networks Bluetooth Device                       | 2         | 1.69%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 1.69%   |
| Broadcom HP Portable SoftSailing                    | 2         | 1.69%   |
| Broadcom HP Portable Bumble Bee                     | 2         | 1.69%   |
| Toshiba Atheros AR3012 Bluetooth                    | 1         | 0.85%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.85%   |
| Realtek Bluetooth Radio                             | 1         | 0.85%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.85%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.85%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.85%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.85%   |
| Lite-On Bluetooth Device                            | 1         | 0.85%   |
| Lite-On Atheros Bluetooth                           | 1         | 0.85%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.85%   |
| Intel AX210 Bluetooth                               | 1         | 0.85%   |
| IMC Networks Bluetooth                              | 1         | 0.85%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.85%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.85%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.85%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 0.85%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 0.85%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 0.85%   |
| Apple Bluetooth HCI                                 | 1         | 0.85%   |
| Alps Electric UGNZG                                 | 1         | 0.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 156       | 77.61%  |
| AMD                         | 19        | 9.45%   |
| Nvidia                      | 15        | 7.46%   |
| Texas Instruments           | 2         | 1%      |
| Lenovo                      | 2         | 1%      |
| Turtle Beach                | 1         | 0.5%    |
| Realtek Semiconductor       | 1         | 0.5%    |
| Medeli Electronics          | 1         | 0.5%    |
| GN Netcom                   | 1         | 0.5%    |
| FiiO Electronics Technology | 1         | 0.5%    |
| C-Media Electronics         | 1         | 0.5%    |
| Apple                       | 1         | 0.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 27        | 11.2%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 17        | 7.05%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 14        | 5.81%   |
| Intel 8 Series HD Audio Controller                                                                | 14        | 5.81%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 14        | 5.81%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 10        | 4.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9         | 3.73%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 9         | 3.73%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 2.9%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 2.49%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 2.49%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 2.49%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 2.07%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 2.07%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 2.07%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 2.07%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 2.07%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 2.07%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.66%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.66%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.66%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 4         | 1.66%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 1.24%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.24%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 1.24%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 1.24%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.83%   |
| Lenovo T2224zD                                                                                    | 2         | 0.83%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.83%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 0.83%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 0.83%   |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 0.83%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 0.83%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 0.83%   |
| AMD FCH Azalia Controller                                                                         | 2         | 0.83%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.83%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2         | 0.83%   |
| Turtle Beach PX11 Headset                                                                         | 1         | 0.41%   |
| Texas Instruments PCM2912A Audio Codec                                                            | 1         | 0.41%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.41%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.41%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.41%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.41%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.41%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.41%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.41%   |
| Medeli Electronics USB Audio Device                                                               | 1         | 0.41%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.41%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 1         | 0.41%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 0.41%   |
| GN Netcom Jabra SPEAK 510                                                                         | 1         | 0.41%   |
| FiiO Electronics Technology FiiO USB DAC-E10                                                      | 1         | 0.41%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 1         | 0.41%   |
| Apple Audio Device                                                                                | 1         | 0.41%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 1         | 0.41%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 0.41%   |
| AMD Navi 10 HDMI Audio                                                                            | 1         | 0.41%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 1         | 0.41%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 0.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 29        | 29%     |
| SK hynix            | 23        | 23%     |
| Micron Technology   | 10        | 10%     |
| Kingston            | 10        | 10%     |
| Unknown             | 9         | 9%      |
| Crucial             | 5         | 5%      |
| Ramaxel Technology  | 3         | 3%      |
| G.Skill             | 2         | 2%      |
| Elpida              | 2         | 2%      |
| A-DATA Technology   | 2         | 2%      |
| TwinMOS             | 1         | 1%      |
| Qimonda             | 1         | 1%      |
| Patriot             | 1         | 1%      |
| Nanya Technology    | 1         | 1%      |
| Avant               | 1         | 1%      |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 4         | 3.88%   |
| Unknown RAM Module 1GB Row Of Chips LPDDR4 4267MT/s                 | 3         | 2.91%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 2.91%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                      | 2         | 1.94%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 1.94%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 1.94%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 2         | 1.94%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 1.94%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 1.94%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s               | 2         | 1.94%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s             | 2         | 1.94%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s                | 2         | 1.94%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                           | 1         | 0.97%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 1         | 0.97%   |
| Unknown RAM Module 2GB SODIMM DDR 800MT/s                           | 1         | 0.97%   |
| Unknown RAM Module 2048MB SODIMM DDR2                               | 1         | 0.97%   |
| TwinMOS RAM 9DECBNZB-TATP 4GB DIMM DDR3 1333MT/s                    | 1         | 0.97%   |
| TwinMOS RAM 9DECBMZB-TATP 2048MB DIMM DDR3 1333MT/s                 | 1         | 0.97%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2667MT/s                        | 1         | 0.97%   |
| SK hynix RAM Module 1GB Row Of Chips LPDDR4 4267MT/s                | 1         | 0.97%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s               | 1         | 0.97%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s                | 1         | 0.97%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.97%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.97%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 0.97%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s                | 1         | 0.97%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8192MB SODIMM DDR3 1600MT/s           | 1         | 0.97%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.97%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1334MT/s           | 1         | 0.97%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 1         | 0.97%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s              | 1         | 0.97%   |
| SK hynix RAM HMT125U7BFR8C-H9 2GB DIMM DDR3 1333MT/s                | 1         | 0.97%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s                | 1         | 0.97%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s        | 1         | 0.97%   |
| SK hynix RAM HMA81GU6CJR8N-VK 8192MB DIMM DDR4 2667MT/s             | 1         | 0.97%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 1         | 0.97%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s              | 1         | 0.97%   |
| SK hynix RAM H9CCNNNCPTMLBR-NUD 4096MB Row Of Chips LPDDR3 1867MT/s | 1         | 0.97%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2400MT/s                      | 1         | 0.97%   |
| Samsung RAM Module 4GB Row Of Chips DDR4 2400MT/s                   | 1         | 0.97%   |
| Samsung RAM Module 4096MB SODIMM DDR4 3200MT/s                      | 1         | 0.97%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 1         | 0.97%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s               | 1         | 0.97%   |
| Samsung RAM M471B5674BH0-YH9 2GB Chip DDR3 1333MT/s                 | 1         | 0.97%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 1         | 0.97%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.97%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.97%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 1         | 0.97%   |
| Samsung RAM M471A5244CB0-CTD 4096MB Row Of Chips DDR4 2667MT/s      | 1         | 0.97%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 1         | 0.97%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s              | 1         | 0.97%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 0.97%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s            | 1         | 0.97%   |
| Samsung RAM M4 70T2864DZ3-CE6 1GB SODIMM DDR 667MT/s                | 1         | 0.97%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s                 | 1         | 0.97%   |
| Ramaxel RAM RMT3170KE68F9F1600 4GB SODIMM DDR3 1600MT/s             | 1         | 0.97%   |
| Ramaxel RAM RMT3170EF68F9W1600 4GB SODIMM DDR3 1600MT/s             | 1         | 0.97%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s             | 1         | 0.97%   |
| Qimonda RAM 64T128021HDL3SB 1GB SODIMM DDR 667MT/s                  | 1         | 0.97%   |
| Patriot RAM 2400 C15 Series 8GB SODIMM DDR4 2667MT/s                | 1         | 0.97%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR3   | 40        | 47.06%  |
| DDR4   | 30        | 35.29%  |
| DDR2   | 5         | 5.88%   |
| LPDDR4 | 4         | 4.71%   |
| LPDDR3 | 3         | 3.53%   |
| SDRAM  | 2         | 2.35%   |
| DDR    | 1         | 1.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 63        | 75%     |
| DIMM         | 10        | 11.9%   |
| Row Of Chips | 9         | 10.71%  |
| Chip         | 2         | 2.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 33        | 36.67%  |
| 8192  | 23        | 25.56%  |
| 2048  | 17        | 18.89%  |
| 16384 | 9         | 10%     |
| 1024  | 6         | 6.67%   |
| 32768 | 2         | 2.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 29        | 32.58%  |
| 2667    | 17        | 19.1%   |
| 1333    | 9         | 10.11%  |
| 2400    | 5         | 5.62%   |
| 1334    | 5         | 5.62%   |
| 4267    | 4         | 4.49%   |
| 3200    | 3         | 3.37%   |
| 2133    | 3         | 3.37%   |
| 1867    | 3         | 3.37%   |
| 667     | 3         | 3.37%   |
| 3600    | 2         | 2.25%   |
| 800     | 2         | 2.25%   |
| 8400    | 1         | 1.12%   |
| 4199    | 1         | 1.12%   |
| 3266    | 1         | 1.12%   |
| Unknown | 1         | 1.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                 | Computers | Percent |
|-----------------------|-----------|---------|
| HP LaserJet M101-M106 | 1         | 100%    |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 38        | 27.14%  |
| Cheng Uei Precision Industry (Foxlink) | 16        | 11.43%  |
| Acer                                   | 13        | 9.29%   |
| Realtek Semiconductor                  | 10        | 7.14%   |
| Sunplus Innovation Technology          | 9         | 6.43%   |
| Lite-On Technology                     | 8         | 5.71%   |
| Microdia                               | 7         | 5%      |
| Syntek                                 | 6         | 4.29%   |
| IMC Networks                           | 5         | 3.57%   |
| Silicon Motion                         | 3         | 2.14%   |
| Quanta                                 | 3         | 2.14%   |
| Suyin                                  | 2         | 1.43%   |
| Samsung Electronics                    | 2         | 1.43%   |
| Ricoh                                  | 2         | 1.43%   |
| Logitech                               | 2         | 1.43%   |
| Importek                               | 2         | 1.43%   |
| Apple                                  | 2         | 1.43%   |
| Z-Star Microelectronics                | 1         | 0.71%   |
| Xiaomi                                 | 1         | 0.71%   |
| Unknown                                | 1         | 0.71%   |
| MacroSilicon                           | 1         | 0.71%   |
| LG Electronics                         | 1         | 0.71%   |
| icSpring                               | 1         | 0.71%   |
| DigiTech                               | 1         | 0.71%   |
| Cubeternet                             | 1         | 0.71%   |
| ALi                                    | 1         | 0.71%   |
| Alcor Micro                            | 1         | 0.71%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony HP HD Webcam                                                       | 6         | 4.26%   |
| Realtek Integrated_Webcam_HD                                               | 5         | 3.55%   |
| Chicony USB 2.0 Camera                                                     | 5         | 3.55%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 5         | 3.55%   |
| Lite-On HP HD Camera                                                       | 4         | 2.84%   |
| Chicony Integrated Camera                                                  | 4         | 2.84%   |
| Acer Integrated Camera                                                     | 4         | 2.84%   |
| Syntek Integrated Camera                                                   | 3         | 2.13%   |
| Microdia Integrated_Webcam_HD                                              | 3         | 2.13%   |
| Lite-On HP HD Webcam                                                       | 3         | 2.13%   |
| Chicony HP HD Camera                                                       | 3         | 2.13%   |
| Chicony HD Webcam                                                          | 3         | 2.13%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 3         | 2.13%   |
| Syntek EasyCamera                                                          | 2         | 1.42%   |
| Sunplus Integrated_Webcam_HD                                               | 2         | 1.42%   |
| Sunplus HP Truevision Full HD                                              | 2         | 1.42%   |
| Sunplus HP HD Webcam [Fixed]                                               | 2         | 1.42%   |
| Realtek Integrated Webcam                                                  | 2         | 1.42%   |
| Realtek FULL HD 1080P Webcam                                               | 2         | 1.42%   |
| Importek HP Webcam-50                                                      | 2         | 1.42%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 2         | 1.42%   |
| Chicony Integrated HP HD Webcam                                            | 2         | 1.42%   |
| Chicony HP Wide Vision HD Camera                                           | 2         | 1.42%   |
| Chicony HP HD Webcam [Fixed]                                               | 2         | 1.42%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed]                | 2         | 1.42%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 2         | 1.42%   |
| Acer ThinkPad P50 Integrated Camera                                        | 2         | 1.42%   |
| Z-Star Vimicro USB Camera (Altair)                                         | 1         | 0.71%   |
| Xiaomi Redmi Note 10 Pro                                                   | 1         | 0.71%   |
| Unknown USB Camera                                                         | 1         | 0.71%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 0.71%   |
| Suyin HP Webcam                                                            | 1         | 0.71%   |
| Suyin Asus Integrated Webcam                                               | 1         | 0.71%   |
| Sunplus HP Wide Vision HD                                                  | 1         | 0.71%   |
| Sunplus HP TrueVision HD Camera                                            | 1         | 0.71%   |
| Sunplus HP Truevision HD                                                   | 1         | 0.71%   |
| Silicon Motion WebCam SC-13HDL11939N                                       | 1         | 0.71%   |
| Silicon Motion WebCam SC-10HDD12636N                                       | 1         | 0.71%   |
| Silicon Motion 300k Pixel Camera                                           | 1         | 0.71%   |
| Samsung Galaxy A5 (MTP)                                                    | 1         | 0.71%   |
| Samsung Galaxy (debugging mode)                                            | 1         | 0.71%   |
| Ricoh Sony Vaio Integrated Webcam                                          | 1         | 0.71%   |
| Ricoh Laptop_Integrated_Webcam_FHD                                         | 1         | 0.71%   |
| Realtek HP Webcam                                                          | 1         | 0.71%   |
| Quanta VGA WebCam                                                          | 1         | 0.71%   |
| Quanta HP Wide Vision HD Camera                                            | 1         | 0.71%   |
| Quanta HP HD Camera                                                        | 1         | 0.71%   |
| Microdia Sonix USB 2.0 Camera                                              | 1         | 0.71%   |
| Microdia Laptop_Integrated_Webcam_7645BB9590586C77DC683CD9114697FF.3M      | 1         | 0.71%   |
| Microdia HP Integrated Webcam                                              | 1         | 0.71%   |
| Microdia Amcrest AWC2198 USB Webcam                                        | 1         | 0.71%   |
| MacroSilicon USB3.0 HD VIDEO                                               | 1         | 0.71%   |
| Logitech Webcam C270                                                       | 1         | 0.71%   |
| Logitech BRIO Ultra HD Webcam                                              | 1         | 0.71%   |
| Lite-On HP Wide Vision HD Camera                                           | 1         | 0.71%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode)                      | 1         | 0.71%   |
| IMC Networks USB2.0 UVC HD Webcam                                          | 1         | 0.71%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 0.71%   |
| IMC Networks ov9734_azurewave_camera                                       | 1         | 0.71%   |
| icSpring camera                                                            | 1         | 0.71%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 30        | 66.67%  |
| Synaptics                  | 9         | 20%     |
| Shenzhen Goodix Technology | 4         | 8.89%   |
| LighTuning Technology      | 1         | 2.22%   |
| AuthenTec                  | 1         | 2.22%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 13        | 28.89%  |
| Validity Sensors VFS491                                                    | 6         | 13.33%  |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 6.67%   |
| Synaptics WBDI Device                                                      | 3         | 6.67%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 6.67%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 4.44%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 4.44%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 4.44%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2.22%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 2.22%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 2.22%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 2.22%   |
| Synaptics  WBDI                                                            | 1         | 2.22%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 2.22%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 2.22%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 2.22%   |
| Shenzhen Goodix  Fingerprint Device                                        | 1         | 2.22%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 2.22%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 2.22%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 50%     |
| Alcor Micro | 2         | 25%     |
| Upek        | 1         | 12.5%   |
| O2 Micro    | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 119       | 65.38%  |
| 1     | 51        | 28.02%  |
| 2     | 11        | 6.04%   |
| 3     | 1         | 0.55%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 45        | 60.81%  |
| Chipcard                 | 7         | 9.46%   |
| Graphics card            | 6         | 8.11%   |
| Net/wireless             | 3         | 4.05%   |
| Camera                   | 3         | 4.05%   |
| Storage                  | 2         | 2.7%    |
| Multimedia controller    | 2         | 2.7%    |
| Communication controller | 2         | 2.7%    |
| Unassigned class         | 1         | 1.35%   |
| Sound                    | 1         | 1.35%   |
| Net/ethernet             | 1         | 1.35%   |
| Bluetooth                | 1         | 1.35%   |

