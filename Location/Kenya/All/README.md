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

Total: 344

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 840 G1            | Notebook    | [c8b979d035](https://linux-hardware.org/?probe=c8b979d035) | Apr 30, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [95b5e79487](https://linux-hardware.org/?probe=95b5e79487) | Apr 30, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS1... | Convertible | [7f30bca791](https://linux-hardware.org/?probe=7f30bca791) | Apr 28, 2023 |
| Dell          | Latitude E6410              | Notebook    | [52ada88fb1](https://linux-hardware.org/?probe=52ada88fb1) | Apr 20, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [37eee19e22](https://linux-hardware.org/?probe=37eee19e22) | Apr 15, 2023 |
| Unknown       | Q-790                       | Desktop     | [5f41d7d182](https://linux-hardware.org/?probe=5f41d7d182) | Apr 04, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [c90d525ee8](https://linux-hardware.org/?probe=c90d525ee8) | Mar 31, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [d5ba09feb1](https://linux-hardware.org/?probe=d5ba09feb1) | Mar 27, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [d1ba8cb8e9](https://linux-hardware.org/?probe=d1ba8cb8e9) | Mar 24, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [049eafecc8](https://linux-hardware.org/?probe=049eafecc8) | Mar 20, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [599f8de7ba](https://linux-hardware.org/?probe=599f8de7ba) | Mar 11, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [8e12f88524](https://linux-hardware.org/?probe=8e12f88524) | Mar 11, 2023 |
| ASUSTek       | UX32LA                      | Notebook    | [3432e951dd](https://linux-hardware.org/?probe=3432e951dd) | Mar 06, 2023 |
| Lenovo        | E51-80 80QB                 | Notebook    | [824ece168f](https://linux-hardware.org/?probe=824ece168f) | Mar 03, 2023 |
| Lenovo        | E51-80 80QB                 | Notebook    | [73794bde33](https://linux-hardware.org/?probe=73794bde33) | Mar 03, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [f492107b66](https://linux-hardware.org/?probe=f492107b66) | Feb 19, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [c9f0a04fcf](https://linux-hardware.org/?probe=c9f0a04fcf) | Feb 10, 2023 |
| HP            | 3047h                       | Desktop     | [bdb6af834f](https://linux-hardware.org/?probe=bdb6af834f) | Feb 08, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [311514a737](https://linux-hardware.org/?probe=311514a737) | Feb 07, 2023 |
| Toshiba       | Satellite C850D-B615        | Notebook    | [66a7f0123f](https://linux-hardware.org/?probe=66a7f0123f) | Feb 07, 2023 |
| Dell          | 0C8810                      | Desktop     | [1df9a88e4a](https://linux-hardware.org/?probe=1df9a88e4a) | Feb 06, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [caedc4c130](https://linux-hardware.org/?probe=caedc4c130) | Jan 29, 2023 |
| HP            | 630                         | Notebook    | [837878455e](https://linux-hardware.org/?probe=837878455e) | Jan 28, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [5ad0221a16](https://linux-hardware.org/?probe=5ad0221a16) | Jan 22, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [d0fe42d2fd](https://linux-hardware.org/?probe=d0fe42d2fd) | Jan 22, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [940d192ea9](https://linux-hardware.org/?probe=940d192ea9) | Jan 20, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [3bc61d7363](https://linux-hardware.org/?probe=3bc61d7363) | Jan 15, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [cae0a5557a](https://linux-hardware.org/?probe=cae0a5557a) | Jan 12, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [00780c7a70](https://linux-hardware.org/?probe=00780c7a70) | Jan 11, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [54eaec4178](https://linux-hardware.org/?probe=54eaec4178) | Jan 10, 2023 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [29654c0c64](https://linux-hardware.org/?probe=29654c0c64) | Jan 06, 2023 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [56e25a5805](https://linux-hardware.org/?probe=56e25a5805) | Dec 28, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [199df541f2](https://linux-hardware.org/?probe=199df541f2) | Dec 21, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [856515e522](https://linux-hardware.org/?probe=856515e522) | Dec 19, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [3e518355b6](https://linux-hardware.org/?probe=3e518355b6) | Dec 17, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [eccd29cfac](https://linux-hardware.org/?probe=eccd29cfac) | Dec 17, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [0de958194e](https://linux-hardware.org/?probe=0de958194e) | Dec 15, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [84c7e04946](https://linux-hardware.org/?probe=84c7e04946) | Dec 08, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [580fb6172f](https://linux-hardware.org/?probe=580fb6172f) | Dec 07, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [645418a0dd](https://linux-hardware.org/?probe=645418a0dd) | Nov 30, 2022 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | Notebook    | [2a4bb490d0](https://linux-hardware.org/?probe=2a4bb490d0) | Nov 29, 2022 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | Notebook    | [a05b99b00e](https://linux-hardware.org/?probe=a05b99b00e) | Nov 29, 2022 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [21cd2084c5](https://linux-hardware.org/?probe=21cd2084c5) | Nov 16, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [b152ccfb56](https://linux-hardware.org/?probe=b152ccfb56) | Nov 14, 2022 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [c42e078d94](https://linux-hardware.org/?probe=c42e078d94) | Nov 04, 2022 |
| HP            | ProBook 650 G2              | Notebook    | [713f71652e](https://linux-hardware.org/?probe=713f71652e) | Nov 04, 2022 |
| Lenovo        | ThinkPad T430s 23539KU      | Notebook    | [34d3046ea4](https://linux-hardware.org/?probe=34d3046ea4) | Nov 03, 2022 |
| Lenovo        | ThinkPad T430s 23539KU      | Notebook    | [ff4e869df2](https://linux-hardware.org/?probe=ff4e869df2) | Nov 03, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [c3049c59a8](https://linux-hardware.org/?probe=c3049c59a8) | Oct 30, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [daae18ab91](https://linux-hardware.org/?probe=daae18ab91) | Oct 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [2ceb11d7b3](https://linux-hardware.org/?probe=2ceb11d7b3) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [5c3d640129](https://linux-hardware.org/?probe=5c3d640129) | Oct 29, 2022 |
| Dell          | Latitude 3350               | Notebook    | [e545da88bf](https://linux-hardware.org/?probe=e545da88bf) | Oct 28, 2022 |
| Lenovo        | Legion S7 15IMH5 82BC       | Notebook    | [7654e5f9c4](https://linux-hardware.org/?probe=7654e5f9c4) | Oct 26, 2022 |
| HP            | ProBook 650 G2              | Notebook    | [7848c6d520](https://linux-hardware.org/?probe=7848c6d520) | Oct 26, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [6a9b93fdeb](https://linux-hardware.org/?probe=6a9b93fdeb) | Oct 16, 2022 |
| HP            | ProBook 650 G2              | Notebook    | [43ce2df718](https://linux-hardware.org/?probe=43ce2df718) | Oct 12, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [dc3347c309](https://linux-hardware.org/?probe=dc3347c309) | Oct 10, 2022 |
| Gigabyte      | TRX40 AORUS PRO WIFI        | Desktop     | [85f2638273](https://linux-hardware.org/?probe=85f2638273) | Oct 05, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [77f9a2e79a](https://linux-hardware.org/?probe=77f9a2e79a) | Oct 04, 2022 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [921b395e9c](https://linux-hardware.org/?probe=921b395e9c) | Oct 02, 2022 |
| HP            | 15                          | Notebook    | [28e8e01768](https://linux-hardware.org/?probe=28e8e01768) | Sep 28, 2022 |
| HP            | EliteBook Folio 9480m       | Notebook    | [e2232c49ca](https://linux-hardware.org/?probe=e2232c49ca) | Sep 25, 2022 |
| Toshiba       | TECRA A50-A                 | Notebook    | [6ef2538a5a](https://linux-hardware.org/?probe=6ef2538a5a) | Sep 23, 2022 |
| Dell          | Latitude 3350               | Notebook    | [62c380dcd0](https://linux-hardware.org/?probe=62c380dcd0) | Sep 22, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [20d37d51bd](https://linux-hardware.org/?probe=20d37d51bd) | Sep 21, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [cabebaa0e6](https://linux-hardware.org/?probe=cabebaa0e6) | Sep 21, 2022 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | Notebook    | [6c1c4c8712](https://linux-hardware.org/?probe=6c1c4c8712) | Sep 10, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [1796a51c0c](https://linux-hardware.org/?probe=1796a51c0c) | Sep 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [f7189849b4](https://linux-hardware.org/?probe=f7189849b4) | Sep 01, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [6d7ce1962d](https://linux-hardware.org/?probe=6d7ce1962d) | Aug 24, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [f85ff90a58](https://linux-hardware.org/?probe=f85ff90a58) | Aug 22, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [3842f0e711](https://linux-hardware.org/?probe=3842f0e711) | Aug 22, 2022 |
| ASUSTek       | X540NA                      | Notebook    | [1fa4b8b58a](https://linux-hardware.org/?probe=1fa4b8b58a) | Aug 21, 2022 |
| ASUSTek       | X540NA                      | Notebook    | [e9bcb08163](https://linux-hardware.org/?probe=e9bcb08163) | Aug 21, 2022 |
| HP            | ENVY 15                     | Notebook    | [5d984dedf6](https://linux-hardware.org/?probe=5d984dedf6) | Aug 20, 2022 |
| HP            | 097Ch                       | Desktop     | [ac391817bc](https://linux-hardware.org/?probe=ac391817bc) | Aug 19, 2022 |
| ASUSTek       | X540NA                      | Notebook    | [c37ee0a700](https://linux-hardware.org/?probe=c37ee0a700) | Aug 08, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [b947e19278](https://linux-hardware.org/?probe=b947e19278) | Aug 02, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [2abfab93cb](https://linux-hardware.org/?probe=2abfab93cb) | Aug 02, 2022 |
| HP            | 1493                        | Desktop     | [2925e7a321](https://linux-hardware.org/?probe=2925e7a321) | Aug 01, 2022 |
| HP            | Unknown                     | Notebook    | [1e1768ebfa](https://linux-hardware.org/?probe=1e1768ebfa) | Jul 24, 2022 |
| HP            | Unknown                     | Notebook    | [aa2aa159c9](https://linux-hardware.org/?probe=aa2aa159c9) | Jul 14, 2022 |
| HP            | 15                          | Notebook    | [91c97ad34a](https://linux-hardware.org/?probe=91c97ad34a) | Jun 24, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [2969400046](https://linux-hardware.org/?probe=2969400046) | Jun 20, 2022 |
| HP            | 3397                        | Desktop     | [0679103825](https://linux-hardware.org/?probe=0679103825) | Jun 13, 2022 |
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

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 46        | 17.97%  |
| Ubuntu 22.04                 | 22        | 8.59%   |
| Ubuntu 18.04                 | 19        | 7.42%   |
| Linux Mint 20.3              | 7         | 2.73%   |
| Fedora 36                    | 7         | 2.73%   |
| Zorin 16                     | 6         | 2.34%   |
| Zorin 15                     | 6         | 2.34%   |
| Manjaro                      | 6         | 2.34%   |
| Pop!_OS 20.04                | 5         | 1.95%   |
| OpenMandriva 4.2             | 5         | 1.95%   |
| Arch                         | 5         | 1.95%   |
| Ubuntu 20.10                 | 4         | 1.56%   |
| Ubuntu 19.04                 | 4         | 1.56%   |
| Linux Mint 21                | 4         | 1.56%   |
| Fedora 37                    | 4         | 1.56%   |
| Ubuntu 21.10                 | 3         | 1.17%   |
| Ubuntu 21.04                 | 3         | 1.17%   |
| Q4OS 3                       | 3         | 1.17%   |
| Fedora 35                    | 3         | 1.17%   |
| Fedora 33                    | 3         | 1.17%   |
| Fedora 32                    | 3         | 1.17%   |
| Debian 11                    | 3         | 1.17%   |
| ArcoLinux Rolling            | 3         | 1.17%   |
| Ubuntu 19.10                 | 2         | 0.78%   |
| Pop!_OS 20.10                | 2         | 0.78%   |
| Parrot 5.1                   | 2         | 0.78%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 0.78%   |
| OpenMandriva 4.3             | 2         | 0.78%   |
| Linux Mint 20.2              | 2         | 0.78%   |
| Linux Mint 19                | 2         | 0.78%   |
| Kali 2022.3                  | 2         | 0.78%   |
| Kali 2020.1                  | 2         | 0.78%   |
| Endless 3.9.4                | 2         | 0.78%   |
| Endless 3.9.2                | 2         | 0.78%   |
| Endless 3.9.1                | 2         | 0.78%   |
| Elementary 6.1               | 2         | 0.78%   |
| Elementary 6                 | 2         | 0.78%   |
| Elementary 5.1.7             | 2         | 0.78%   |
| BlackPanther 18.1            | 2         | 0.78%   |
| Android                      | 2         | 0.78%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 99        | 41.42%  |
| Fedora        | 20        | 8.37%   |
| Linux Mint    | 15        | 6.28%   |
| Zorin         | 12        | 5.02%   |
| Endless       | 10        | 4.18%   |
| OpenMandriva  | 9         | 3.77%   |
| Pop!_OS       | 8         | 3.35%   |
| Manjaro       | 7         | 2.93%   |
| Arch          | 7         | 2.93%   |
| Parrot        | 6         | 2.51%   |
| Kali          | 6         | 2.51%   |
| Elementary    | 5         | 2.09%   |
| Debian        | 4         | 1.67%   |
| Q4OS          | 3         | 1.26%   |
| ArcoLinux     | 3         | 1.26%   |
| Ubuntu MATE   | 2         | 0.84%   |
| ROSA          | 2         | 0.84%   |
| openSUSE      | 2         | 0.84%   |
| Lubuntu       | 2         | 0.84%   |
| KDE neon      | 2         | 0.84%   |
| BlackPanther  | 2         | 0.84%   |
| Android       | 2         | 0.84%   |
| Xubuntu       | 1         | 0.42%   |
| Ubuntu Studio | 1         | 0.42%   |
| Ubuntu Budgie | 1         | 0.42%   |
| RHEL          | 1         | 0.42%   |
| Nobara        | 1         | 0.42%   |
| Mageia        | 1         | 0.42%   |
| LMDE          | 1         | 0.42%   |
| Garuda Linux  | 1         | 0.42%   |
| Deepin        | 1         | 0.42%   |
| CentOS        | 1         | 0.42%   |
| antiX         | 1         | 0.42%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.8.0-14-generic         | 6         | 2.17%   |
| 5.4.0-42-generic         | 5         | 1.81%   |
| 5.15.0-58-generic        | 5         | 1.81%   |
| 5.15.0-52-generic        | 5         | 1.81%   |
| 5.15.0-41-generic        | 5         | 1.81%   |
| 5.10.14-desktop-1omv4002 | 5         | 1.81%   |
| 5.4.0-52-generic         | 4         | 1.45%   |
| 5.11.0-38-generic        | 4         | 1.45%   |
| 5.8.0-43-generic         | 3         | 1.09%   |
| 5.4.0-58-generic         | 3         | 1.09%   |
| 5.4.0-45-generic         | 3         | 1.09%   |
| 5.4.0-37-generic         | 3         | 1.09%   |
| 5.3.0-28-generic         | 3         | 1.09%   |
| 5.19.0-38-generic        | 3         | 1.09%   |
| 5.19.0-35-generic        | 3         | 1.09%   |
| 5.15.0-53-generic        | 3         | 1.09%   |
| 4.19.0-17-amd64          | 3         | 1.09%   |
| 5.9.13-200.fc33.x86_64   | 2         | 0.72%   |
| 5.8.4-200.fc32.x86_64    | 2         | 0.72%   |
| 5.8.0-63-generic         | 2         | 0.72%   |
| 5.8.0-59-generic         | 2         | 0.72%   |
| 5.8.0-55-generic         | 2         | 0.72%   |
| 5.8.0-50-generic         | 2         | 0.72%   |
| 5.4.0-67-generic         | 2         | 0.72%   |
| 5.4.0-65-generic         | 2         | 0.72%   |
| 5.4.0-54-generic         | 2         | 0.72%   |
| 5.4.0-48-generic         | 2         | 0.72%   |
| 5.4.0-47-generic         | 2         | 0.72%   |
| 5.4.0-33-generic         | 2         | 0.72%   |
| 5.4.0-19-generic         | 2         | 0.72%   |
| 5.4.0-137-generic        | 2         | 0.72%   |
| 5.3.0-62-generic         | 2         | 0.72%   |
| 5.19.9-200.fc36.x86_64   | 2         | 0.72%   |
| 5.18.13-200.fc36.x86_64  | 2         | 0.72%   |
| 5.18.0-14parrot1-amd64   | 2         | 0.72%   |
| 5.16.7-desktop-1omv4003  | 2         | 0.72%   |
| 5.15.0-46-generic        | 2         | 0.72%   |
| 5.13.19-2-MANJARO        | 2         | 0.72%   |
| 5.13.0-28-generic        | 2         | 0.72%   |
| 5.13.0-27-generic        | 2         | 0.72%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 50        | 19.23%  |
| 5.15.0  | 25        | 9.62%   |
| 5.8.0   | 24        | 9.23%   |
| 5.11.0  | 16        | 6.15%   |
| 5.13.0  | 12        | 4.62%   |
| 4.15.0  | 12        | 4.62%   |
| 5.3.0   | 10        | 3.85%   |
| 5.0.0   | 9         | 3.46%   |
| 5.19.0  | 7         | 2.69%   |
| 5.10.14 | 5         | 1.92%   |
| 5.10.0  | 5         | 1.92%   |
| 5.18.0  | 4         | 1.54%   |
| 4.19.0  | 4         | 1.54%   |
| 4.18.0  | 4         | 1.54%   |
| 5.19.9  | 3         | 1.15%   |
| 5.16.7  | 3         | 1.15%   |
| 6.1.0   | 2         | 0.77%   |
| 5.9.13  | 2         | 0.77%   |
| 5.8.4   | 2         | 0.77%   |
| 5.18.13 | 2         | 0.77%   |
| 5.17.5  | 2         | 0.77%   |
| 5.13.19 | 2         | 0.77%   |
| 4.18.16 | 2         | 0.77%   |
| 6.2.9   | 1         | 0.38%   |
| 6.1.15  | 1         | 0.38%   |
| 6.1.1   | 1         | 0.38%   |
| 6.0.15  | 1         | 0.38%   |
| 6.0.12  | 1         | 0.38%   |
| 5.9.14  | 1         | 0.38%   |
| 5.8.13  | 1         | 0.38%   |
| 5.8.12  | 1         | 0.38%   |
| 5.7.17  | 1         | 0.38%   |
| 5.6.7   | 1         | 0.38%   |
| 5.6.5   | 1         | 0.38%   |
| 5.6.11  | 1         | 0.38%   |
| 5.5.0   | 1         | 0.38%   |
| 5.2.5   | 1         | 0.38%   |
| 5.2.0   | 1         | 0.38%   |
| 5.19.5  | 1         | 0.38%   |
| 5.19.2  | 1         | 0.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 50        | 19.46%  |
| 5.15    | 30        | 11.67%  |
| 5.8     | 27        | 10.51%  |
| 5.11    | 17        | 6.61%   |
| 5.19    | 16        | 6.23%   |
| 5.13    | 14        | 5.45%   |
| 5.10    | 14        | 5.45%   |
| 4.15    | 12        | 4.67%   |
| 5.3     | 10        | 3.89%   |
| 5.0     | 10        | 3.89%   |
| 5.16    | 7         | 2.72%   |
| 5.18    | 6         | 2.33%   |
| 4.18    | 6         | 2.33%   |
| 4.19    | 5         | 1.95%   |
| 6.1     | 4         | 1.56%   |
| 5.9     | 3         | 1.17%   |
| 5.6     | 3         | 1.17%   |
| 5.17    | 3         | 1.17%   |
| 5.14    | 3         | 1.17%   |
| 4.9     | 3         | 1.17%   |
| 6.0     | 2         | 0.78%   |
| 5.2     | 2         | 0.78%   |
| 5.12    | 2         | 0.78%   |
| 6.2     | 1         | 0.39%   |
| 5.7     | 1         | 0.39%   |
| 5.5     | 1         | 0.39%   |
| 5.1     | 1         | 0.39%   |
| 4.4     | 1         | 0.39%   |
| 4.16    | 1         | 0.39%   |
| 4.13    | 1         | 0.39%   |
| 3.10    | 1         | 0.39%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 230       | 97.87%  |
| i686    | 3         | 1.28%   |
| armv8l  | 1         | 0.43%   |
| aarch64 | 1         | 0.43%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 143       | 59.34%  |
| KDE5            | 25        | 10.37%  |
| Unknown         | 25        | 10.37%  |
| X-Cinnamon      | 15        | 6.22%   |
| XFCE            | 7         | 2.9%    |
| MATE            | 7         | 2.9%    |
| Pantheon        | 5         | 2.07%   |
| KDE             | 4         | 1.66%   |
| LXQt            | 2         | 0.83%   |
| KDE4            | 2         | 0.83%   |
| Cinnamon        | 2         | 0.83%   |
| GNOME Flashback | 1         | 0.41%   |
| DWM             | 1         | 0.41%   |
| Deepin          | 1         | 0.41%   |
| awesome         | 1         | 0.41%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 168       | 69.71%  |
| Wayland | 57        | 23.65%  |
| Unknown | 14        | 5.81%   |
| Tty     | 2         | 0.83%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 123       | 51.04%  |
| GDM3    | 33        | 13.69%  |
| GDM     | 32        | 13.28%  |
| SDDM    | 28        | 11.62%  |
| LightDM | 18        | 7.47%   |
| TDM     | 5         | 2.07%   |
| KDM     | 2         | 0.83%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 182       | 76.15%  |
| Unknown | 29        | 12.13%  |
| en_GB   | 25        | 10.46%  |
| C       | 2         | 0.84%   |
| en_AG   | 1         | 0.42%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 134       | 55.83%  |
| EFI  | 106       | 44.17%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 188       | 79.66%  |
| Btrfs   | 23        | 9.75%   |
| Overlay | 16        | 6.78%   |
| Unknown | 5         | 2.12%   |
| Tmpfs   | 2         | 0.85%   |
| Zfs     | 1         | 0.42%   |
| Xfs     | 1         | 0.42%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 133       | 55.65%  |
| GPT     | 75        | 31.38%  |
| MBR     | 31        | 12.97%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 203       | 86.02%  |
| Yes       | 33        | 13.98%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 164       | 69.49%  |
| Yes       | 72        | 30.51%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 98        | 41.7%   |
| Lenovo                      | 39        | 16.6%   |
| Dell                        | 35        | 14.89%  |
| ASUSTek Computer            | 11        | 4.68%   |
| Toshiba                     | 8         | 3.4%    |
| Acer                        | 5         | 2.13%   |
| MSI                         | 4         | 1.7%    |
| Gigabyte Technology         | 4         | 1.7%    |
| Unknown                     | 4         | 1.7%    |
| Samsung Electronics         | 3         | 1.28%   |
| Chuwi                       | 2         | 0.85%   |
| Apple                       | 2         | 0.85%   |
| TECNO                       | 1         | 0.43%   |
| Sony                        | 1         | 0.43%   |
| SLIMBOOK                    | 1         | 0.43%   |
| Panasonic                   | 1         | 0.43%   |
| Notebook                    | 1         | 0.43%   |
| IP3 Tech                    | 1         | 0.43%   |
| Intel                       | 1         | 0.43%   |
| Insyde                      | 1         | 0.43%   |
| IBM                         | 1         | 0.43%   |
| I-Life Digital Technologies | 1         | 0.43%   |
| HUAWEI                      | 1         | 0.43%   |
| Getac                       | 1         | 0.43%   |
| Foxconn                     | 1         | 0.43%   |
| EVOC                        | 1         | 0.43%   |
| EUROCOM                     | 1         | 0.43%   |
| Endless                     | 1         | 0.43%   |
| Eluktronics                 | 1         | 0.43%   |
| Clevo                       | 1         | 0.43%   |
| ASRock                      | 1         | 0.43%   |
| AMI                         | 1         | 0.43%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Unknown                                 | 6         | 2.55%   |
| HP EliteBook 840 G1                     | 5         | 2.13%   |
| HP EliteBook 840 G3                     | 4         | 1.7%    |
| Dell XPS 13 9310                        | 4         | 1.7%    |
| HP EliteBook Folio 9480m                | 3         | 1.28%   |
| HP EliteBook Folio 9470m                | 3         | 1.28%   |
| HP EliteBook 8460p                      | 3         | 1.28%   |
| Toshiba Satellite C660                  | 2         | 0.85%   |
| MSI MS-7C02                             | 2         | 0.85%   |
| Lenovo IdeaPad S340-14IIL 81VV          | 2         | 0.85%   |
| HP Spectre x360 Convertible             | 2         | 0.85%   |
| HP ProBook 640 G1                       | 2         | 0.85%   |
| HP ProBook 440 G5                       | 2         | 0.85%   |
| HP Pavilion Laptop 15-cs3xxx            | 2         | 0.85%   |
| HP ENVY 15                              | 2         | 0.85%   |
| HP EliteBook 8440p                      | 2         | 0.85%   |
| HP EliteBook 840 G2                     | 2         | 0.85%   |
| HP EliteBook 2570p                      | 2         | 0.85%   |
| HP Compaq Mini 110c-1100                | 2         | 0.85%   |
| HP 630                                  | 2         | 0.85%   |
| HP 15 Notebook PC                       | 2         | 0.85%   |
| HP 15                                   | 2         | 0.85%   |
| Dell OptiPlex 7010                      | 2         | 0.85%   |
| Dell Latitude E6410                     | 2         | 0.85%   |
| Dell Inspiron 5767                      | 2         | 0.85%   |
| ASUS X540NA                             | 2         | 0.85%   |
| Toshiba TECRA A50-A                     | 1         | 0.43%   |
| Toshiba Satellite L50-B                 | 1         | 0.43%   |
| Toshiba Satellite C850D-B615            | 1         | 0.43%   |
| Toshiba R84SAU2                         | 1         | 0.43%   |
| Toshiba dynabook Satellite B554/M       | 1         | 0.43%   |
| Toshiba dynabook R731/E                 | 1         | 0.43%   |
| TECNO WinPad 2                          | 1         | 0.43%   |
| Sony VGN-NS295J                         | 1         | 0.43%   |
| SLIMBOOK PROX14-AMD                     | 1         | 0.43%   |
| Samsung RC410/RC510/RC710               | 1         | 0.43%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV | 1         | 0.43%   |
| Samsung 300E4C/300E5C/300E7C            | 1         | 0.43%   |
| Panasonic CF-SX2JDQZF5                  | 1         | 0.43%   |
| Notebook P65xHP                         | 1         | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| HP EliteBook           | 32        | 13.62%  |
| Lenovo ThinkPad        | 19        | 8.09%   |
| HP ProBook             | 13        | 5.53%   |
| Dell OptiPlex          | 11        | 4.68%   |
| Lenovo IdeaPad         | 10        | 4.26%   |
| HP Compaq              | 10        | 4.26%   |
| HP Pavilion            | 9         | 3.83%   |
| Dell Latitude          | 9         | 3.83%   |
| Dell Inspiron          | 9         | 3.83%   |
| HP ENVY                | 7         | 2.98%   |
| Unknown                | 6         | 2.55%   |
| HP Laptop              | 5         | 2.13%   |
| Dell XPS               | 5         | 2.13%   |
| Toshiba Satellite      | 4         | 1.7%    |
| HP Spectre             | 4         | 1.7%    |
| HP 15                  | 4         | 1.7%    |
| Acer Aspire            | 4         | 1.7%    |
| Toshiba dynabook       | 2         | 0.85%   |
| MSI MS-7C02            | 2         | 0.85%   |
| Lenovo Legion          | 2         | 0.85%   |
| HP ZBook               | 2         | 0.85%   |
| HP 630                 | 2         | 0.85%   |
| ASUS X540NA            | 2         | 0.85%   |
| Toshiba TECRA          | 1         | 0.43%   |
| Toshiba R84SAU2        | 1         | 0.43%   |
| TECNO WinPad           | 1         | 0.43%   |
| Sony VGN-NS295J        | 1         | 0.43%   |
| SLIMBOOK PROX14-AMD    | 1         | 0.43%   |
| Samsung RC410          | 1         | 0.43%   |
| Samsung 300E5EV        | 1         | 0.43%   |
| Samsung 300E4C         | 1         | 0.43%   |
| Panasonic CF-SX2JDQZF5 | 1         | 0.43%   |
| Notebook P65xHP        | 1         | 0.43%   |
| MSI 500-007A           | 1         | 0.43%   |
| MSI 0A90               | 1         | 0.43%   |
| Lenovo Z50-75          | 1         | 0.43%   |
| Lenovo V330-14IKB      | 1         | 0.43%   |
| Lenovo V310-15ISK      | 1         | 0.43%   |
| Lenovo V14-IGL         | 1         | 0.43%   |
| Lenovo V130-14IKB      | 1         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 24        | 10.21%  |
| 2013    | 24        | 10.21%  |
| 2016    | 21        | 8.94%   |
| 2019    | 20        | 8.51%   |
| 2012    | 19        | 8.09%   |
| 2015    | 18        | 7.66%   |
| 2011    | 17        | 7.23%   |
| 2017    | 16        | 6.81%   |
| 2014    | 16        | 6.81%   |
| 2020    | 15        | 6.38%   |
| 2010    | 13        | 5.53%   |
| 2021    | 8         | 3.4%    |
| 2008    | 6         | 2.55%   |
| 2007    | 5         | 2.13%   |
| 2009    | 3         | 1.28%   |
| Unknown | 3         | 1.28%   |
| 2022    | 2         | 0.85%   |
| 2006    | 2         | 0.85%   |
| 2005    | 2         | 0.85%   |
| 2004    | 1         | 0.43%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 178       | 75.74%  |
| Desktop     | 38        | 16.17%  |
| Convertible | 13        | 5.53%   |
| Phone       | 2         | 0.85%   |
| Mini pc     | 2         | 0.85%   |
| All in one  | 1         | 0.43%   |
| Server      | 1         | 0.43%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 220       | 92.44%  |
| Enabled  | 18        | 7.56%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 235       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 63        | 26.36%  |
| 4.01-8.0        | 61        | 25.52%  |
| 8.01-16.0       | 38        | 15.9%   |
| 16.01-24.0      | 32        | 13.39%  |
| 1.01-2.0        | 21        | 8.79%   |
| 32.01-64.0      | 11        | 4.6%    |
| 64.01-256.0     | 5         | 2.09%   |
| 24.01-32.0      | 3         | 1.26%   |
| 2.01-3.0        | 2         | 0.84%   |
| 0.51-1.0        | 2         | 0.84%   |
| More than 256.0 | 1         | 0.42%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 72        | 27.48%  |
| 1.01-2.0    | 72        | 27.48%  |
| 4.01-8.0    | 44        | 16.79%  |
| 3.01-4.0    | 43        | 16.41%  |
| 0.51-1.0    | 20        | 7.63%   |
| 8.01-16.0   | 7         | 2.67%   |
| 0.01-0.5    | 2         | 0.76%   |
| 64.01-256.0 | 1         | 0.38%   |
| Unknown     | 1         | 0.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 186       | 77.5%   |
| 2      | 39        | 16.25%  |
| 4      | 5         | 2.08%   |
| 3      | 4         | 1.67%   |
| 0      | 2         | 0.83%   |
| 10     | 1         | 0.42%   |
| 8      | 1         | 0.42%   |
| 6      | 1         | 0.42%   |
| 5      | 1         | 0.42%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 147       | 62.55%  |
| Yes       | 88        | 37.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 194       | 82.55%  |
| No        | 41        | 17.45%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 205       | 86.86%  |
| No        | 31        | 13.14%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 157       | 66.24%  |
| No        | 80        | 33.76%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Kenya   | 235       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City     | Computers | Percent |
|----------|-----------|---------|
| Nairobi  | 221       | 91.32%  |
| Mombasa  | 4         | 1.65%   |
| Nakuru   | 3         | 1.24%   |
| Nyeri    | 2         | 0.83%   |
| Kiambu   | 2         | 0.83%   |
| Eldoret  | 2         | 0.83%   |
| Wote     | 1         | 0.41%   |
| Rongai   | 1         | 0.41%   |
| Narok    | 1         | 0.41%   |
| Nanyuki  | 1         | 0.41%   |
| Murang'a | 1         | 0.41%   |
| Maralal  | 1         | 0.41%   |
| Machakos | 1         | 0.41%   |
| Kisii    | 1         | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 75        | 96     | 26.13%  |
| WDC                 | 38        | 46     | 13.24%  |
| Toshiba             | 33        | 38     | 11.5%   |
| Samsung Electronics | 31        | 46     | 10.8%   |
| Unknown             | 16        | 23     | 5.57%   |
| HGST                | 16        | 27     | 5.57%   |
| SanDisk             | 13        | 14     | 4.53%   |
| Hitachi             | 12        | 14     | 4.18%   |
| Intel               | 6         | 8      | 2.09%   |
| Crucial             | 6         | 8      | 2.09%   |
| SPCC                | 5         | 9      | 1.74%   |
| Micron Technology   | 5         | 6      | 1.74%   |
| SK hynix            | 4         | 5      | 1.39%   |
| MARSHAL             | 4         | 4      | 1.39%   |
| Kingston            | 3         | 5      | 1.05%   |
| Team                | 2         | 2      | 0.7%    |
| Maxtor              | 2         | 2      | 0.7%    |
| HUAWEI              | 2         | 2      | 0.7%    |
| China               | 2         | 2      | 0.7%    |
| Unknown             | 2         | 2      | 0.7%    |
| TCSUNBOW            | 1         | 1      | 0.35%   |
| Plextor             | 1         | 1      | 0.35%   |
| Netac               | 1         | 1      | 0.35%   |
| LITEON              | 1         | 1      | 0.35%   |
| Lexar               | 1         | 1      | 0.35%   |
| Golden              | 1         | 1      | 0.35%   |
| Eluktro             | 1         | 1      | 0.35%   |
| CARLSTEIN           | 1         | 4      | 0.35%   |
| Apple               | 1         | 1      | 0.35%   |
| A-DATA Technology   | 1         | 1      | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 970GB   | 11        | 3.64%   |
| Toshiba MQ04ABF100 1TB             | 6         | 1.99%   |
| Seagate ST500LT012-9WS142 500GB    | 6         | 1.99%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 6         | 1.99%   |
| Toshiba MQ01ABF050 500GB           | 5         | 1.66%   |
| Samsung NVMe SSD Drive 512GB       | 5         | 1.66%   |
| HGST HTS725050A7E630 500GB         | 5         | 1.66%   |
| Unknown MMC Card  64GB             | 4         | 1.32%   |
| Toshiba MQ01ABD100 1TB             | 4         | 1.32%   |
| Seagate ST9500325AS 500GB          | 4         | 1.32%   |
| Seagate ST500LT012-1DG142 500GB    | 4         | 1.32%   |
| Seagate ST500LM021-1KJ152 500GB    | 4         | 1.32%   |
| Samsung SSD 960 EVO 1TB            | 4         | 1.32%   |
| WDC WD3200AAJS-56M0A0 320GB        | 3         | 0.99%   |
| WDC PC SN730 NVMe 512GB            | 3         | 0.99%   |
| Unknown MMC Card  32GB             | 3         | 0.99%   |
| SPCC M.2 PCIe SSD 512GB            | 3         | 0.99%   |
| Seagate ST500DM002-1BD142 500GB    | 3         | 0.99%   |
| Crucial CT2050MX300SSD1 2TB        | 3         | 0.99%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 2         | 0.66%   |
| WDC WD5000LPCX-60VHAT0 500GB       | 2         | 0.66%   |
| WDC WD5000LPCX-24VHAT0 500GB       | 2         | 0.66%   |
| WDC WD2500BEKT-75PVMT0 250GB       | 2         | 0.66%   |
| WDC WD10SPZX-60Z10T0 1TB           | 2         | 0.66%   |
| Unknown NCard  32GB                | 2         | 0.66%   |
| Unknown MMC Card                   | 2         | 0.66%   |
| Toshiba DT01ACA100 1TB             | 2         | 0.66%   |
| Team T253X2001T 1024GB SSD         | 2         | 0.66%   |
| SPCC Solid State Disk 256GB        | 2         | 0.66%   |
| Seagate ST500VT000-1DK142 500GB    | 2         | 0.66%   |
| Seagate ST500VT000-1BS142 500GB    | 2         | 0.66%   |
| Seagate ST500LM030-1RK17D 500GB    | 2         | 0.66%   |
| Seagate ST3320418AS 320GB          | 2         | 0.66%   |
| Seagate ST3250318AS 250GB          | 2         | 0.66%   |
| Seagate ST250LT003-9YG14C 250GB    | 2         | 0.66%   |
| Seagate ST2000LM003 HN-M201RAD 2TB | 2         | 0.66%   |
| Seagate ST2000DM008-2FR102 2TB     | 2         | 0.66%   |
| Samsung SSD 840 EVO 250GB          | 2         | 0.66%   |
| Samsung NVMe SSD Drive 256GB       | 2         | 0.66%   |
| MARSHAL MAL2500SA-T54L 500GB       | 2         | 0.66%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 74        | 95     | 43.27%  |
| WDC                 | 31        | 39     | 18.13%  |
| Toshiba             | 28        | 33     | 16.37%  |
| HGST                | 16        | 27     | 9.36%   |
| Hitachi             | 12        | 14     | 7.02%   |
| MARSHAL             | 4         | 4      | 2.34%   |
| Samsung Electronics | 2         | 2      | 1.17%   |
| Maxtor              | 2         | 2      | 1.17%   |
| Unknown             | 1         | 1      | 0.58%   |
| Unknown             | 1         | 1      | 0.58%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 10        | 10     | 19.23%  |
| Samsung Electronics | 9         | 15     | 17.31%  |
| Crucial             | 6         | 8      | 11.54%  |
| Micron Technology   | 3         | 4      | 5.77%   |
| WDC                 | 2         | 2      | 3.85%   |
| Toshiba             | 2         | 2      | 3.85%   |
| Team                | 2         | 2      | 3.85%   |
| SPCC                | 2         | 3      | 3.85%   |
| Kingston            | 2         | 4      | 3.85%   |
| Intel               | 2         | 2      | 3.85%   |
| China               | 2         | 2      | 3.85%   |
| TCSUNBOW            | 1         | 1      | 1.92%   |
| SK hynix            | 1         | 1      | 1.92%   |
| Plextor             | 1         | 1      | 1.92%   |
| Netac               | 1         | 1      | 1.92%   |
| LITEON              | 1         | 1      | 1.92%   |
| Lexar               | 1         | 1      | 1.92%   |
| Golden              | 1         | 1      | 1.92%   |
| Eluktro             | 1         | 1      | 1.92%   |
| A-DATA Technology   | 1         | 1      | 1.92%   |
| Unknown             | 1         | 1      | 1.92%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 153       | 218    | 56.88%  |
| NVMe    | 49        | 63     | 18.22%  |
| SSD     | 49        | 64     | 18.22%  |
| MMC     | 14        | 20     | 5.2%    |
| Unknown | 4         | 7      | 1.49%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 187       | 285    | 73.62%  |
| NVMe | 49        | 63     | 19.29%  |
| MMC  | 14        | 20     | 5.51%   |
| SAS  | 4         | 4      | 1.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 134       | 185    | 66.01%  |
| 0.51-1.0   | 55        | 69     | 27.09%  |
| 1.01-2.0   | 9         | 19     | 4.43%   |
| 3.01-4.0   | 2         | 5      | 0.99%   |
| 4.01-10.0  | 2         | 3      | 0.99%   |
| 2.01-3.0   | 1         | 1      | 0.49%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 68        | 27.42%  |
| 101-250        | 54        | 21.77%  |
| 501-1000       | 39        | 15.73%  |
| 51-100         | 24        | 9.68%   |
| 1001-2000      | 17        | 6.85%   |
| Unknown        | 12        | 4.84%   |
| 1-20           | 10        | 4.03%   |
| More than 3000 | 8         | 3.23%   |
| 21-50          | 8         | 3.23%   |
| 2001-3000      | 8         | 3.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 68        | 26.88%  |
| 21-50          | 43        | 17%     |
| 101-250        | 42        | 16.6%   |
| 51-100         | 37        | 14.62%  |
| 251-500        | 25        | 9.88%   |
| Unknown        | 12        | 4.74%   |
| 501-1000       | 11        | 4.35%   |
| 1001-2000      | 10        | 3.95%   |
| More than 3000 | 4         | 1.58%   |
| 2001-3000      | 1         | 0.4%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB       | 3         | 3      | 9.09%   |
| WDC WD2500BEKT-75PVMT0 250GB          | 2         | 2      | 6.06%   |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 6.06%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 1      | 3.03%   |
| WDC WD3200AAJS-56M0A0 320GB           | 1         | 1      | 3.03%   |
| WDC WD10SPZX-60Z10T0 1TB              | 1         | 1      | 3.03%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 3.03%   |
| Toshiba MQ01ABD050V 500GB             | 1         | 1      | 3.03%   |
| Toshiba MK3263GSX 320GB               | 1         | 1      | 3.03%   |
| Toshiba MK3252GSX 320GB               | 1         | 1      | 3.03%   |
| Toshiba MK2555GSX 250GB               | 1         | 1      | 3.03%   |
| SK hynix HFS128G32TND-N210A 128GB SSD | 1         | 1      | 3.03%   |
| Seagate ST9500325AS 500GB             | 1         | 1      | 3.03%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 3.03%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1      | 3.03%   |
| Seagate ST500DM002-1BD142 500GB       | 1         | 1      | 3.03%   |
| Seagate ST1000LM049-2GH172 1TB        | 1         | 1      | 3.03%   |
| Seagate ST1000LM035-1RK172 970GB      | 1         | 1      | 3.03%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 1      | 3.03%   |
| MARSHAL MAL2750SA-T54 752GB           | 1         | 1      | 3.03%   |
| Hitachi HTS545032B9A300 320GB         | 1         | 1      | 3.03%   |
| Hitachi HTS542525K9SA00 250GB         | 1         | 1      | 3.03%   |
| HGST HTS725050A7E630 500GB            | 1         | 1      | 3.03%   |
| HGST HTS721010A9 1TB                  | 1         | 2      | 3.03%   |
| HGST HTS545050A7E380 500GB            | 1         | 1      | 3.03%   |
| HGST HTS541515A9E630 1TB              | 1         | 2      | 3.03%   |
| HGST HTS541010A9E680 1TB              | 1         | 2      | 3.03%   |
| Crucial CT2050MX300SSD1 2TB           | 1         | 2      | 3.03%   |
| Unknown                               | 1         | 1      | 3.03%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 10        | 10     | 31.25%  |
| Toshiba  | 7         | 7      | 21.88%  |
| WDC      | 5         | 5      | 15.63%  |
| HGST     | 4         | 8      | 12.5%   |
| Hitachi  | 2         | 2      | 6.25%   |
| SK hynix | 1         | 1      | 3.13%   |
| MARSHAL  | 1         | 1      | 3.13%   |
| Crucial  | 1         | 2      | 3.13%   |
| Unknown  | 1         | 1      | 3.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 10        | 10     | 33.33%  |
| Toshiba | 7         | 7      | 23.33%  |
| WDC     | 5         | 5      | 16.67%  |
| HGST    | 4         | 8      | 13.33%  |
| Hitachi | 2         | 2      | 6.67%   |
| MARSHAL | 1         | 1      | 3.33%   |
| Unknown | 1         | 1      | 3.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 29        | 34     | 93.55%  |
| SSD  | 2         | 3      | 6.45%   |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 149       | 220    | 61.32%  |
| Works    | 64        | 115    | 26.34%  |
| Malfunc  | 30        | 37     | 12.35%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 197       | 74.9%   |
| Samsung Electronics          | 22        | 8.37%   |
| AMD                          | 15        | 5.7%    |
| SanDisk                      | 8         | 3.04%   |
| Toshiba America Info Systems | 3         | 1.14%   |
| SK hynix                     | 3         | 1.14%   |
| Silicon Motion               | 3         | 1.14%   |
| Micron Technology            | 2         | 0.76%   |
| LSI Logic / Symbios Logic    | 2         | 0.76%   |
| Shenzhen Longsys Electronics | 1         | 0.38%   |
| Realtek Semiconductor        | 1         | 0.38%   |
| Marvell Technology Group     | 1         | 0.38%   |
| Kingston Technology Company  | 1         | 0.38%   |
| JMicron Technology           | 1         | 0.38%   |
| Broadcom / LSI               | 1         | 0.38%   |
| ASMedia Technology           | 1         | 0.38%   |
| Apple                        | 1         | 0.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 30        | 10.34%  |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 19        | 6.55%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 15        | 5.17%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 15        | 5.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 13        | 4.48%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 13        | 4.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 12        | 4.14%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 11        | 3.79%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 8         | 2.76%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 7         | 2.41%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 5         | 1.72%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 5         | 1.72%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4         | 1.38%   |
| Samsung NVMe SSD Controller 980                                                         | 4         | 1.38%   |
| Intel SATA Controller [RAID mode]                                                       | 4         | 1.38%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4         | 1.38%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4         | 1.38%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 4         | 1.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 4         | 1.38%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4         | 1.38%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4         | 1.38%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3         | 1.03%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 3         | 1.03%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 3         | 1.03%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3         | 1.03%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 1.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 3         | 1.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 3         | 1.03%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 3         | 1.03%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3         | 1.03%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 2         | 0.69%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 2         | 0.69%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2         | 0.69%   |
| Micron NVMe Storage Controller                                                          | 2         | 0.69%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2         | 0.69%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 2         | 0.69%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 2         | 0.69%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 0.69%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2         | 0.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 170       | 62.5%   |
| NVMe | 49        | 18.01%  |
| RAID | 29        | 10.66%  |
| IDE  | 23        | 8.46%   |
| SCSI | 1         | 0.37%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 213       | 90.64%  |
| AMD    | 20        | 8.51%   |
| ARM    | 2         | 0.85%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz           | 6         | 2.55%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 6         | 2.55%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 5         | 2.13%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 5         | 2.13%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 5         | 2.13%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 5         | 2.13%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 4         | 1.7%    |
| Intel Core i7-6600U CPU @ 2.60GHz           | 4         | 1.7%    |
| Intel Core i5-5200U CPU @ 2.20GHz           | 4         | 1.7%    |
| Intel Core i5-2540M CPU @ 2.60GHz           | 4         | 1.7%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 4         | 1.7%    |
| Intel Core i7-8750H CPU @ 2.20GHz           | 3         | 1.28%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 3         | 1.28%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 3         | 1.28%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 3         | 1.28%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 3         | 1.28%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 3         | 1.28%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 3         | 1.28%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 3         | 1.28%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 3         | 1.28%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 0.85%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 0.85%   |
| Intel Pentium 4 CPU 2.80GHz                 | 2         | 0.85%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 2         | 0.85%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 2         | 0.85%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 2         | 0.85%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 0.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 0.85%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2         | 0.85%   |
| Intel Core i5-4310U CPU @ 2.00GHz           | 2         | 0.85%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 2         | 0.85%   |
| Intel Core i5-3437U CPU @ 1.90GHz           | 2         | 0.85%   |
| Intel Core i5-3427U CPU @ 1.80GHz           | 2         | 0.85%   |
| Intel Core i5-3360M CPU @ 2.80GHz           | 2         | 0.85%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 0.85%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 2         | 0.85%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 0.85%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 0.85%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2         | 0.85%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 2         | 0.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 67        | 28.51%  |
| Intel Core i7           | 55        | 23.4%   |
| Intel Core i3           | 21        | 8.94%   |
| Intel Celeron           | 19        | 8.09%   |
| Other                   | 11        | 4.68%   |
| Intel Atom              | 8         | 3.4%    |
| Intel Core 2 Duo        | 7         | 2.98%   |
| AMD Ryzen 7             | 6         | 2.55%   |
| Intel Pentium           | 5         | 2.13%   |
| AMD Ryzen 5             | 5         | 2.13%   |
| Intel Xeon              | 4         | 1.7%    |
| Intel Pentium 4         | 4         | 1.7%    |
| Intel Pentium Dual-Core | 3         | 1.28%   |
| Intel Core i9           | 3         | 1.28%   |
| Intel Core 2            | 3         | 1.28%   |
| Intel Core 2 Quad       | 2         | 0.85%   |
| AMD FX                  | 2         | 0.85%   |
| AMD A10                 | 2         | 0.85%   |
| Intel Pentium Dual      | 1         | 0.43%   |
| Intel Core m3           | 1         | 0.43%   |
| ARM AArch64             | 1         | 0.43%   |
| AMD Ryzen Threadripper  | 1         | 0.43%   |
| AMD Ryzen 9             | 1         | 0.43%   |
| AMD Phenom II X3        | 1         | 0.43%   |
| AMD E2                  | 1         | 0.43%   |
| AMD A4                  | 1         | 0.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 130       | 55.32%  |
| 4       | 70        | 29.79%  |
| 6       | 11        | 4.68%   |
| 8       | 9         | 3.83%   |
| 1       | 7         | 2.98%   |
| 3       | 3         | 1.28%   |
| 32      | 1         | 0.43%   |
| 20      | 1         | 0.43%   |
| 12      | 1         | 0.43%   |
| 10      | 1         | 0.43%   |
| Unknown | 1         | 0.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 233       | 99.15%  |
| 2      | 2         | 0.85%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 173       | 73.62%  |
| 1       | 61        | 25.96%  |
| Unknown | 1         | 0.43%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 233       | 99.15%  |
| 32-bit         | 2         | 0.85%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 59        | 23.98%  |
| 0x306a9    | 21        | 8.54%   |
| 0x206a7    | 16        | 6.5%    |
| 0x40651    | 14        | 5.69%   |
| 0x406e3    | 10        | 4.07%   |
| 0x306c3    | 10        | 4.07%   |
| 0x806ea    | 8         | 3.25%   |
| 0x806c1    | 8         | 3.25%   |
| 0x806ec    | 7         | 2.85%   |
| 0x906ea    | 6         | 2.44%   |
| 0x306d4    | 6         | 2.44%   |
| 0x30678    | 6         | 2.44%   |
| 0x1067a    | 6         | 2.44%   |
| 0x20655    | 5         | 2.03%   |
| 0x506e3    | 4         | 1.63%   |
| 0x806e9    | 3         | 1.22%   |
| 0x706e5    | 3         | 1.22%   |
| 0x406c4    | 3         | 1.22%   |
| 0x0800820d | 3         | 1.22%   |
| 0x906e9    | 2         | 0.81%   |
| 0x806eb    | 2         | 0.81%   |
| 0x706a8    | 2         | 0.81%   |
| 0x706a1    | 2         | 0.81%   |
| 0x6fd      | 2         | 0.81%   |
| 0x6f6      | 2         | 0.81%   |
| 0x406c3    | 2         | 0.81%   |
| 0x106c2    | 2         | 0.81%   |
| 0x10676    | 2         | 0.81%   |
| 0x08608103 | 2         | 0.81%   |
| 0xf65      | 1         | 0.41%   |
| 0xf49      | 1         | 0.41%   |
| 0xf43      | 1         | 0.41%   |
| 0xa0652    | 1         | 0.41%   |
| 0x906ec    | 1         | 0.41%   |
| 0x906a4    | 1         | 0.41%   |
| 0x90661    | 1         | 0.41%   |
| 0x806c2    | 1         | 0.41%   |
| 0x6fa      | 1         | 0.41%   |
| 0x6f7      | 1         | 0.41%   |
| 0x6f2      | 1         | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 41        | 17.45%  |
| Haswell          | 33        | 14.04%  |
| IvyBridge        | 22        | 9.36%   |
| Skylake          | 21        | 8.94%   |
| SandyBridge      | 18        | 7.66%   |
| Silvermont       | 15        | 6.38%   |
| Westmere         | 9         | 3.83%   |
| TigerLake        | 9         | 3.83%   |
| Penryn           | 8         | 3.4%    |
| Core             | 8         | 3.4%    |
| Broadwell        | 7         | 2.98%   |
| IceLake          | 6         | 2.55%   |
| Zen+             | 5         | 2.13%   |
| Zen 2            | 4         | 1.7%    |
| NetBurst         | 4         | 1.7%    |
| Goldmont plus    | 4         | 1.7%    |
| Unknown          | 4         | 1.7%    |
| Goldmont         | 3         | 1.28%   |
| Zen 3            | 2         | 0.85%   |
| Piledriver       | 2         | 0.85%   |
| Excavator        | 2         | 0.85%   |
| Bonnell          | 2         | 0.85%   |
| Tremont          | 1         | 0.43%   |
| Steamroller      | 1         | 0.43%   |
| K10              | 1         | 0.43%   |
| CometLake        | 1         | 0.43%   |
| Bobcat           | 1         | 0.43%   |
| Alderlake Hybrid | 1         | 0.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 190       | 72.52%  |
| Nvidia                     | 36        | 13.74%  |
| AMD                        | 35        | 13.36%  |
| Matrox Electronics Systems | 1         | 0.38%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 19        | 7.12%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 17        | 6.37%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 16        | 5.99%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 15        | 5.62%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 11        | 4.12%   |
| Intel UHD Graphics 620                                                                   | 10        | 3.75%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 10        | 3.75%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 3.37%   |
| Intel HD Graphics 620                                                                    | 8         | 3%      |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 3%      |
| Intel HD Graphics 5500                                                                   | 7         | 2.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 2.62%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 7         | 2.62%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 1.87%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 1.5%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.5%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 1.5%    |
| Nvidia GP108M [GeForce MX250]                                                            | 3         | 1.12%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 1.12%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 1.12%   |
| Intel HD Graphics 530                                                                    | 3         | 1.12%   |
| Intel HD Graphics 500                                                                    | 3         | 1.12%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3         | 1.12%   |
| AMD Renoir                                                                               | 3         | 1.12%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.75%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 2         | 0.75%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 0.75%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 0.75%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.75%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.75%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 0.75%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 0.75%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2         | 0.75%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 0.75%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 0.75%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 0.75%   |
| AMD Park [Mobility Radeon HD 5430]                                                       | 2         | 0.75%   |
| AMD Lucienne                                                                             | 2         | 0.75%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 1         | 0.37%   |
| Nvidia TU104BM [GeForce RTX 2080 Mobile]                                                 | 1         | 0.37%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 163       | 68.78%  |
| 1 x AMD        | 25        | 10.55%  |
| 1 x Nvidia     | 20        | 8.44%   |
| Intel + Nvidia | 16        | 6.75%   |
| Intel + AMD    | 9         | 3.8%    |
| Other          | 2         | 0.84%   |
| 2 x AMD        | 1         | 0.42%   |
| 1 x Matrox     | 1         | 0.42%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 220       | 92.83%  |
| Proprietary | 13        | 5.49%   |
| Unknown     | 4         | 1.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 181       | 75.73%  |
| 1.01-2.0   | 17        | 7.11%   |
| 0.01-0.5   | 17        | 7.11%   |
| 3.01-4.0   | 9         | 3.77%   |
| 7.01-8.0   | 7         | 2.93%   |
| 0.51-1.0   | 7         | 2.93%   |
| 8.01-16.0  | 1         | 0.42%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 48        | 19.83%  |
| Chimei Innolux          | 34        | 14.05%  |
| LG Display              | 30        | 12.4%   |
| BOE                     | 28        | 11.57%  |
| Hewlett-Packard         | 22        | 9.09%   |
| Samsung Electronics     | 20        | 8.26%   |
| Dell                    | 12        | 4.96%   |
| Sharp                   | 6         | 2.48%   |
| InfoVision              | 6         | 2.48%   |
| Sony                    | 5         | 2.07%   |
| Lenovo                  | 5         | 2.07%   |
| Chi Mei Optoelectronics | 3         | 1.24%   |
| Apple                   | 3         | 1.24%   |
| Unknown (XXX)           | 2         | 0.83%   |
| LG Philips              | 2         | 0.83%   |
| KDC                     | 2         | 0.83%   |
| HannStar                | 2         | 0.83%   |
| VIE                     | 1         | 0.41%   |
| Unknown                 | 1         | 0.41%   |
| S2-Tek                  | 1         | 0.41%   |
| Planar                  | 1         | 0.41%   |
| NEC Computers           | 1         | 0.41%   |
| Hitachi                 | 1         | 0.41%   |
| Eizo                    | 1         | 0.41%   |
| CVT                     | 1         | 0.41%   |
| CSO                     | 1         | 0.41%   |
| BenQ                    | 1         | 0.41%   |
| Acer                    | 1         | 0.41%   |
| Unknown                 | 1         | 0.41%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 4         | 1.63%   |
| Chimei Innolux LCD Monitor CMN14A3 1600x900 309x174mm 14.0-inch          | 4         | 1.63%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                  | 3         | 1.22%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 1.22%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 3         | 1.22%   |
| AU Optronics LCD Monitor AUO223E 1600x900 309x174mm 14.0-inch            | 3         | 1.22%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 3         | 1.22%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 3         | 1.22%   |
| Sony TV SNY6F02 1360x768                                                 | 2         | 0.82%   |
| Samsung Electronics S22E450 SAM0C7A 1920x1080 477x268mm 21.5-inch        | 2         | 0.82%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 0.82%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 2         | 0.82%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch              | 2         | 0.82%   |
| Lenovo T2224zD LEN60CB 1920x1080 476x267mm 21.5-inch                     | 2         | 0.82%   |
| Hewlett-Packard E222 HWP3262 1920x1080 476x268mm 21.5-inch               | 2         | 0.82%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 2         | 0.82%   |
| Dell E1910H DELD023 1366x768 410x230mm 18.5-inch                         | 2         | 0.82%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 2         | 0.82%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch         | 2         | 0.82%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x173mm 13.9-inch          | 2         | 0.82%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 0.82%   |
| BOE LCD Monitor BOE0780 1920x1080 344x194mm 15.5-inch                    | 2         | 0.82%   |
| BOE LCD Monitor BOE0695 1920x1080 380x210mm 17.1-inch                    | 2         | 0.82%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch            | 2         | 0.82%   |
| VIE LED MONITOR VIE2302 1920x1080 473x296mm 22.0-inch                    | 1         | 0.41%   |
| Unknown LCD Monitor Hitachi Engineering Company Ltd HISENSE 3200x1080    | 1         | 0.41%   |
| Unknown (XXX) LEDTV XXX0001 1366x768 575x323mm 26.0-inch                 | 1         | 0.41%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch           | 1         | 0.41%   |
| Sony TV SNYEF03 1600x900                                                 | 1         | 0.41%   |
| Sony TV SNYDC02 1920x1080 930x523mm 42.0-inch                            | 1         | 0.41%   |
| Sony TV SNY0902 1360x768                                                 | 1         | 0.41%   |
| Sharp LQ133T1JW02 SHP13FF 2560x1440 294x165mm 13.3-inch                  | 1         | 0.41%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                  | 1         | 0.41%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                  | 1         | 0.41%   |
| Samsung Electronics SyncMaster SAM022B 1280x1024 338x270mm 17.0-inch     | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 303x190mm 14.1-inch     | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC4542 1280x800 303x190mm 14.1-inch     | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 309x174mm 14.0-inch     | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch     | 1         | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 91        | 38.72%  |
| 1920x1080 (FHD)    | 74        | 31.49%  |
| 1600x900 (HD+)     | 17        | 7.23%   |
| 1280x1024 (SXGA)   | 9         | 3.83%   |
| 3840x2160 (4K)     | 8         | 3.4%    |
| 1920x1200 (WUXGA)  | 5         | 2.13%   |
| 1440x900 (WXGA+)   | 5         | 2.13%   |
| 1280x800 (WXGA)    | 4         | 1.7%    |
| 2560x1440 (QHD)    | 3         | 1.28%   |
| 1360x768           | 3         | 1.28%   |
| 1680x1050 (WSXGA+) | 2         | 0.85%   |
| 1024x768 (XGA)     | 2         | 0.85%   |
| 1024x600           | 2         | 0.85%   |
| Unknown            | 2         | 0.85%   |
| 3840x2400          | 1         | 0.43%   |
| 3440x1440          | 1         | 0.43%   |
| 3200x1800 (QHD+)   | 1         | 0.43%   |
| 3200x1080          | 1         | 0.43%   |
| 3072x1920          | 1         | 0.43%   |
| 2560x1080          | 1         | 0.43%   |
| 2160x1440          | 1         | 0.43%   |
| 1920x1280          | 1         | 0.43%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 73        | 30.42%  |
| 13      | 47        | 19.58%  |
| 14      | 40        | 16.67%  |
| 17      | 8         | 3.33%   |
| 21      | 7         | 2.92%   |
| 19      | 7         | 2.92%   |
| 24      | 6         | 2.5%    |
| 18      | 6         | 2.5%    |
| 12      | 6         | 2.5%    |
| 11      | 6         | 2.5%    |
| 23      | 5         | 2.08%   |
| 72      | 4         | 1.67%   |
| 20      | 3         | 1.25%   |
| 10      | 3         | 1.25%   |
| Unknown | 3         | 1.25%   |
| 84      | 2         | 0.83%   |
| 46      | 2         | 0.83%   |
| 34      | 2         | 0.83%   |
| 27      | 2         | 0.83%   |
| 26      | 2         | 0.83%   |
| 22      | 2         | 0.83%   |
| 54      | 1         | 0.42%   |
| 42      | 1         | 0.42%   |
| 31      | 1         | 0.42%   |
| 16      | 1         | 0.42%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 142       | 59.92%  |
| 201-300     | 35        | 14.77%  |
| 401-500     | 16        | 6.75%   |
| 501-600     | 15        | 6.33%   |
| 351-400     | 13        | 5.49%   |
| 1501-2000   | 6         | 2.53%   |
| Unknown     | 3         | 1.27%   |
| 1001-1500   | 2         | 0.84%   |
| 901-1000    | 2         | 0.84%   |
| 801-900     | 1         | 0.42%   |
| 701-800     | 1         | 0.42%   |
| 601-700     | 1         | 0.42%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 189       | 82.17%  |
| 16/10   | 24        | 10.43%  |
| 5/4     | 9         | 3.91%   |
| Unknown | 3         | 1.3%    |
| 3/2     | 2         | 0.87%   |
| 21/9    | 2         | 0.87%   |
| 4/3     | 1         | 0.43%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 73        | 30.54%  |
| 81-90          | 68        | 28.45%  |
| 71-80          | 19        | 7.95%   |
| 151-200        | 14        | 5.86%   |
| 201-250        | 12        | 5.02%   |
| 141-150        | 9         | 3.77%   |
| More than 1000 | 7         | 2.93%   |
| 61-70          | 6         | 2.51%   |
| 51-60          | 6         | 2.51%   |
| 251-300        | 5         | 2.09%   |
| 351-500        | 3         | 1.26%   |
| 41-50          | 3         | 1.26%   |
| 301-350        | 3         | 1.26%   |
| 121-130        | 3         | 1.26%   |
| 501-1000       | 3         | 1.26%   |
| Unknown        | 3         | 1.26%   |
| 131-140        | 1         | 0.42%   |
| 111-120        | 1         | 0.42%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 82        | 34.89%  |
| 121-160       | 74        | 31.49%  |
| 51-100        | 47        | 20%     |
| 161-240       | 16        | 6.81%   |
| 1-50          | 7         | 2.98%   |
| More than 240 | 6         | 2.55%   |
| Unknown       | 3         | 1.28%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 199       | 82.92%  |
| 2     | 31        | 12.92%  |
| 0     | 9         | 3.75%   |
| 3     | 1         | 0.42%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 140       | 39.66%  |
| Realtek Semiconductor             | 96        | 27.2%   |
| Qualcomm Atheros                  | 44        | 12.46%  |
| Broadcom                          | 22        | 6.23%   |
| MediaTek                          | 8         | 2.27%   |
| Hewlett-Packard                   | 6         | 1.7%    |
| Samsung Electronics               | 4         | 1.13%   |
| Huawei Technologies               | 4         | 1.13%   |
| Broadcom Limited                  | 4         | 1.13%   |
| Sierra Wireless                   | 3         | 0.85%   |
| Ralink Technology                 | 3         | 0.85%   |
| Ralink                            | 3         | 0.85%   |
| OPPO Electronics                  | 3         | 0.85%   |
| Marvell Technology Group          | 3         | 0.85%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.57%   |
| Xiaomi                            | 2         | 0.57%   |
| T & A Mobile Phones               | 2         | 0.57%   |
| Spreadtrum Communications         | 1         | 0.28%   |
| Qualcomm                          | 1         | 0.28%   |
| IBM                               | 1         | 0.28%   |
| Ericsson Business Mobile Networks | 1         | 0.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 54        | 12.22%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 21        | 4.75%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 19        | 4.3%    |
| Intel Wireless 7260                                               | 19        | 4.3%    |
| Intel Ethernet Connection I218-LM                                 | 15        | 3.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 13        | 2.94%   |
| Intel Wireless 7265                                               | 11        | 2.49%   |
| Intel Wireless 8265 / 8275                                        | 9         | 2.04%   |
| Intel Ethernet Connection I219-LM                                 | 9         | 2.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 2.04%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 8         | 1.81%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 8         | 1.81%   |
| Intel Wireless 8260                                               | 8         | 1.81%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 8         | 1.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 1.58%   |
| MediaTek PRESIDENT_GOLD_10                                        | 7         | 1.58%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 1.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 1.36%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 1.36%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 5         | 1.13%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 0.9%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 0.9%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 0.9%    |
| Intel Ethernet Connection I217-V                                  | 4         | 0.9%    |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 0.9%    |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 0.9%    |
| Intel 82577LM Gigabit Network Connection                          | 4         | 0.9%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 0.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 0.68%   |
| OPPO KALAMA-MTP_CID:0437_SN:AEEEF597                              | 3         | 0.68%   |
| Intel I211 Gigabit Network Connection                             | 3         | 0.68%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.68%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.68%   |
| Intel Centrino Advanced-N 6200                                    | 3         | 0.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 0.68%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 0.68%   |
| HP lt4112 Gobi 4G Module Network Device                           | 3         | 0.68%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 3         | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 111       | 51.87%  |
| Qualcomm Atheros      | 38        | 17.76%  |
| Realtek Semiconductor | 37        | 17.29%  |
| Broadcom              | 16        | 7.48%   |
| Hewlett-Packard       | 4         | 1.87%   |
| Ralink Technology     | 3         | 1.4%    |
| Ralink                | 3         | 1.4%    |
| Sierra Wireless       | 2         | 0.93%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                            | 19        | 8.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 13        | 6.07%   |
| Intel Wireless 7265                                            | 11        | 5.14%   |
| Intel Wireless 8265 / 8275                                     | 9         | 4.21%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 9         | 4.21%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 8         | 3.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 8         | 3.74%   |
| Intel Wireless 8260                                            | 8         | 3.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 8         | 3.74%   |
| Intel Wi-Fi 6 AX201                                            | 7         | 3.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 2.8%    |
| Intel Wi-Fi 6 AX200                                            | 6         | 2.8%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 5         | 2.34%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 4         | 1.87%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 1.87%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 4         | 1.87%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 1.4%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 1.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3         | 1.4%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 1.4%    |
| Intel Centrino Advanced-N 6200                                 | 3         | 1.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 1.4%    |
| HP lt4112 Gobi 4G Module Network Device                        | 3         | 1.4%    |
| Broadcom BCM43228 802.11a/b/g/n                                | 3         | 1.4%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 1.4%    |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 3         | 1.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.93%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 2         | 0.93%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 0.93%   |
| Ralink MT7601U Wireless Adapter                                | 2         | 0.93%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 0.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 0.93%   |
| Intel Wireless-AC 9260                                         | 2         | 0.93%   |
| Intel Wireless 3165                                            | 2         | 0.93%   |
| Intel Wireless 3160                                            | 2         | 0.93%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 0.93%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 0.93%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 0.93%   |
| Sierra Wireless EM7455                                         | 1         | 0.47%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 90        | 40.72%  |
| Realtek Semiconductor      | 80        | 36.2%   |
| Qualcomm Atheros           | 9         | 4.07%   |
| MediaTek                   | 8         | 3.62%   |
| Broadcom                   | 7         | 3.17%   |
| Broadcom Limited           | 4         | 1.81%   |
| Samsung Electronics        | 3         | 1.36%   |
| OPPO Electronics           | 3         | 1.36%   |
| Marvell Technology Group   | 3         | 1.36%   |
| ZTE WCDMA Technologies MSM | 2         | 0.9%    |
| Xiaomi                     | 2         | 0.9%    |
| T & A Mobile Phones        | 2         | 0.9%    |
| Huawei Technologies        | 2         | 0.9%    |
| Hewlett-Packard            | 2         | 0.9%    |
| Spreadtrum Communications  | 1         | 0.45%   |
| Sierra Wireless            | 1         | 0.45%   |
| Qualcomm                   | 1         | 0.45%   |
| IBM                        | 1         | 0.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 54        | 24.11%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 21        | 9.38%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 19        | 8.48%   |
| Intel Ethernet Connection I218-LM                                 | 15        | 6.7%    |
| Intel Ethernet Connection I219-LM                                 | 9         | 4.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 3.13%   |
| MediaTek PRESIDENT_GOLD_10                                        | 7         | 3.13%   |
| Intel Ethernet Connection I217-V                                  | 4         | 1.79%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.79%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 1.79%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 1.79%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 1.34%   |
| OPPO KALAMA-MTP_CID:0437_SN:AEEEF597                              | 3         | 1.34%   |
| Intel I211 Gigabit Network Connection                             | 3         | 1.34%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.34%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 1.34%   |
| ZTE WCDMA MSM DEMO Mobile Boardband                               | 2         | 0.89%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.89%   |
| T & A Mobile Phones A509DL                                        | 2         | 0.89%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.89%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.89%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.89%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.89%   |
| MediaTek BL8800Pro                                                | 2         | 0.89%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.89%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.89%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.89%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.89%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2         | 0.89%   |
| Huawei E353/E3131                                                 | 2         | 0.89%   |
| HP lt4120 Snapdragon X5 LTE                                       | 2         | 0.89%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 2         | 0.89%   |
| Spreadtrum Nokia G21                                              | 1         | 0.45%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.45%   |
| Qualcomm SM7250-PICASSO _SN:6897A937                              | 1         | 0.45%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.45%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.45%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.45%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.45%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 205       | 50.87%  |
| Ethernet | 194       | 48.14%  |
| Modem    | 4         | 0.99%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 170       | 71.73%  |
| Ethernet | 67        | 28.27%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 146       | 61.86%  |
| 1     | 75        | 31.78%  |
| 0     | 10        | 4.24%   |
| 3     | 3         | 1.27%   |
| 6     | 1         | 0.42%   |
| 4     | 1         | 0.42%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 230       | 97.87%  |
| Yes  | 5         | 2.13%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 90        | 57.32%  |
| Qualcomm Atheros Communications | 22        | 14.01%  |
| Realtek Semiconductor           | 14        | 8.92%   |
| Broadcom                        | 9         | 5.73%   |
| IMC Networks                    | 4         | 2.55%   |
| Hewlett-Packard                 | 4         | 2.55%   |
| Lite-On Technology              | 3         | 1.91%   |
| Toshiba                         | 2         | 1.27%   |
| Ralink                          | 2         | 1.27%   |
| Cambridge Silicon Radio         | 2         | 1.27%   |
| Realtek                         | 1         | 0.64%   |
| Foxconn / Hon Hai               | 1         | 0.64%   |
| Dell                            | 1         | 0.64%   |
| Apple                           | 1         | 0.64%   |
| Alps Electric                   | 1         | 0.64%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 48        | 30.57%  |
| Qualcomm Atheros  Bluetooth Device                  | 14        | 8.92%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 14        | 8.92%   |
| Intel AX201 Bluetooth                               | 11        | 7.01%   |
| Realtek Bluetooth Radio                             | 8         | 5.1%    |
| Intel AX200 Bluetooth                               | 6         | 3.82%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 2.55%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 2.55%   |
| Broadcom HP Portable SoftSailing                    | 4         | 2.55%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.91%   |
| IMC Networks Bluetooth Device                       | 3         | 1.91%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.91%   |
| Ralink RT3290 Bluetooth                             | 2         | 1.27%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 1.27%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 1.27%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.27%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 1.27%   |
| Broadcom HP Portable Bumble Bee                     | 2         | 1.27%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.27%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.64%   |
| Toshiba Atheros AR3012 Bluetooth                    | 1         | 0.64%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.64%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.64%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 0.64%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.64%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.64%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.64%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.64%   |
| Lite-On Bluetooth Device                            | 1         | 0.64%   |
| Lite-On Atheros Bluetooth                           | 1         | 0.64%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.64%   |
| Intel Bluetooth Device                              | 1         | 0.64%   |
| Intel AX210 Bluetooth                               | 1         | 0.64%   |
| IMC Networks Bluetooth                              | 1         | 0.64%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.64%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.64%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.64%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 0.64%   |
| Apple Bluetooth HCI                                 | 1         | 0.64%   |
| Alps Electric UGNZG                                 | 1         | 0.64%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 204       | 76.12%  |
| AMD                         | 27        | 10.07%  |
| Nvidia                      | 21        | 7.84%   |
| Texas Instruments           | 3         | 1.12%   |
| Generalplus Technology      | 3         | 1.12%   |
| Lenovo                      | 2         | 0.75%   |
| Turtle Beach                | 1         | 0.37%   |
| Realtek Semiconductor       | 1         | 0.37%   |
| Medeli Electronics          | 1         | 0.37%   |
| GN Netcom                   | 1         | 0.37%   |
| Giga-Byte Technology        | 1         | 0.37%   |
| FiiO Electronics Technology | 1         | 0.37%   |
| C-Media Electronics         | 1         | 0.37%   |
| Apple                       | 1         | 0.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 36        | 11.25%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 21        | 6.56%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 19        | 5.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 19        | 5.94%   |
| Intel 8 Series HD Audio Controller                                                                | 18        | 5.63%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 13        | 4.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12        | 3.75%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 11        | 3.44%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 9         | 2.81%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 8         | 2.5%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 2.19%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 2.19%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 2.19%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 2.19%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 6         | 1.88%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 1.88%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 1.88%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 1.88%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 1.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 1.56%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 1.25%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.25%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 1.25%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.25%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 4         | 1.25%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.94%   |
| Generalplus Technology USB Audio Device                                                           | 3         | 0.94%   |
| AMD FCH Azalia Controller                                                                         | 3         | 0.94%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 0.94%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 2         | 0.63%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.63%   |
| Lenovo T2224zD                                                                                    | 2         | 0.63%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 0.63%   |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 0.63%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 0.63%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 0.63%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 0.63%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.63%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 41        | 28.08%  |
| SK hynix            | 38        | 26.03%  |
| Micron Technology   | 16        | 10.96%  |
| Kingston            | 13        | 8.9%    |
| Unknown             | 9         | 6.16%   |
| Crucial             | 8         | 5.48%   |
| Ramaxel Technology  | 5         | 3.42%   |
| Elpida              | 3         | 2.05%   |
| A-DATA Technology   | 3         | 2.05%   |
| G.Skill             | 2         | 1.37%   |
| TwinMOS             | 1         | 0.68%   |
| Team                | 1         | 0.68%   |
| Qimonda             | 1         | 0.68%   |
| Patriot             | 1         | 0.68%   |
| Nanya Technology    | 1         | 0.68%   |
| Avant               | 1         | 0.68%   |
| Apacer              | 1         | 0.68%   |
| Unknown             | 1         | 0.68%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 5         | 3.33%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 4         | 2.67%   |
| Unknown RAM Module 1GB Row Of Chips LPDDR4 4267MT/s         | 3         | 2%      |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 3         | 2%      |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 3         | 2%      |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s | 3         | 2%      |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 3         | 2%      |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s              | 2         | 1.33%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 2         | 1.33%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s      | 2         | 1.33%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 2         | 1.33%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s       | 2         | 1.33%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 2         | 1.33%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s       | 2         | 1.33%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s       | 2         | 1.33%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s     | 2         | 1.33%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s        | 2         | 1.33%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                   | 1         | 0.67%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                  | 1         | 0.67%   |
| Unknown RAM Module 2GB SODIMM DDR 800MT/s                   | 1         | 0.67%   |
| Unknown RAM Module 2048MB SODIMM DDR2                       | 1         | 0.67%   |
| TwinMOS RAM 9DECBNZB-TATP 4GB DIMM DDR3 1333MT/s            | 1         | 0.67%   |
| TwinMOS RAM 9DECBMZB-TATP 2048MB DIMM DDR3 1333MT/s         | 1         | 0.67%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s          | 1         | 0.67%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                | 1         | 0.67%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s        | 1         | 0.67%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2667MT/s                | 1         | 0.67%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s             | 1         | 0.67%   |
| SK hynix RAM Module 1GB Row Of Chips LPDDR4 4267MT/s        | 1         | 0.67%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s       | 1         | 0.67%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s        | 1         | 0.67%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.67%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.67%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s      | 1         | 0.67%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s        | 1         | 0.67%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s      | 1         | 0.67%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.67%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 0.67%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s      | 1         | 0.67%   |
| SK hynix RAM HMT325S6EFR8C-PB 2GB SODIMM DDR3 1600MT/s      | 1         | 0.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR3   | 51        | 44.35%  |
| DDR4   | 47        | 40.87%  |
| LPDDR4 | 5         | 4.35%   |
| DDR2   | 5         | 4.35%   |
| LPDDR3 | 4         | 3.48%   |
| SDRAM  | 2         | 1.74%   |
| DDR    | 1         | 0.87%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 88        | 73.95%  |
| Row Of Chips | 16        | 13.45%  |
| DIMM         | 13        | 10.92%  |
| Chip         | 2         | 1.68%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 49        | 37.98%  |
| 8192  | 35        | 27.13%  |
| 2048  | 19        | 14.73%  |
| 16384 | 16        | 12.4%   |
| 1024  | 6         | 4.65%   |
| 32768 | 4         | 3.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 39        | 30.71%  |
| 2667    | 26        | 20.47%  |
| 3200    | 13        | 10.24%  |
| 1333    | 10        | 7.87%   |
| 2400    | 6         | 4.72%   |
| 1334    | 6         | 4.72%   |
| 4267    | 5         | 3.94%   |
| 2133    | 5         | 3.94%   |
| 1867    | 3         | 2.36%   |
| 667     | 3         | 2.36%   |
| 3600    | 2         | 1.57%   |
| 3266    | 2         | 1.57%   |
| 800     | 2         | 1.57%   |
| 8400    | 1         | 0.79%   |
| 4199    | 1         | 0.79%   |
| 3800    | 1         | 0.79%   |
| 2666    | 1         | 0.79%   |
| Unknown | 1         | 0.79%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 53        | 28.8%   |
| Cheng Uei Precision Industry (Foxlink) | 23        | 12.5%   |
| Realtek Semiconductor                  | 12        | 6.52%   |
| Sunplus Innovation Technology          | 11        | 5.98%   |
| Syntek                                 | 10        | 5.43%   |
| Lite-On Technology                     | 10        | 5.43%   |
| Microdia                               | 9         | 4.89%   |
| IMC Networks                           | 8         | 4.35%   |
| Acer                                   | 8         | 4.35%   |
| Bison Electronics                      | 6         | 3.26%   |
| Silicon Motion                         | 3         | 1.63%   |
| Samsung Electronics                    | 3         | 1.63%   |
| Quanta                                 | 3         | 1.63%   |
| Logitech                               | 3         | 1.63%   |
| Suyin                                  | 2         | 1.09%   |
| Ricoh                                  | 2         | 1.09%   |
| Luxvisions Innotech Limited            | 2         | 1.09%   |
| Importek                               | 2         | 1.09%   |
| Apple                                  | 2         | 1.09%   |
| Alcor Micro                            | 2         | 1.09%   |
| Z-Star Microelectronics                | 1         | 0.54%   |
| Xiaomi                                 | 1         | 0.54%   |
| Unknown                                | 1         | 0.54%   |
| Primax Electronics                     | 1         | 0.54%   |
| MacroSilicon                           | 1         | 0.54%   |
| LG Electronics                         | 1         | 0.54%   |
| icSpring                               | 1         | 0.54%   |
| DigiTech                               | 1         | 0.54%   |
| Cubeternet                             | 1         | 0.54%   |
| ALi                                    | 1         | 0.54%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 10        | 5.41%   |
| Chicony HP HD Webcam                                                       | 7         | 3.78%   |
| Syntek Integrated Camera                                                   | 6         | 3.24%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 6         | 3.24%   |
| Realtek Integrated_Webcam_HD                                               | 5         | 2.7%    |
| Lite-On HP HD Camera                                                       | 5         | 2.7%    |
| Chicony USB 2.0 Camera                                                     | 5         | 2.7%    |
| Microdia Integrated_Webcam_HD                                              | 4         | 2.16%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 4         | 2.16%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 4         | 2.16%   |
| Sunplus HP HD Webcam [Fixed]                                               | 3         | 1.62%   |
| Lite-On HP HD Webcam                                                       | 3         | 1.62%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 3         | 1.62%   |
| Chicony HP Wide Vision HD Camera                                           | 3         | 1.62%   |
| Chicony HP HD Webcam [Fixed]                                               | 3         | 1.62%   |
| Chicony HP HD Camera                                                       | 3         | 1.62%   |
| Chicony HD Webcam                                                          | 3         | 1.62%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed]                | 3         | 1.62%   |
| Bison Integrated Camera                                                    | 3         | 1.62%   |
| Syntek Lenovo EasyCamera                                                   | 2         | 1.08%   |
| Syntek EasyCamera                                                          | 2         | 1.08%   |
| Sunplus Integrated_Webcam_HD                                               | 2         | 1.08%   |
| Sunplus HP Truevision Full HD                                              | 2         | 1.08%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 2         | 1.08%   |
| Realtek Integrated Webcam                                                  | 2         | 1.08%   |
| Realtek FULL HD 1080P Webcam                                               | 2         | 1.08%   |
| Logitech Webcam C270                                                       | 2         | 1.08%   |
| Importek HP Webcam-50                                                      | 2         | 1.08%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 2         | 1.08%   |
| Chicony TOSHIBA Web Camera - HD                                            | 2         | 1.08%   |
| Chicony Integrated HP HD Webcam                                            | 2         | 1.08%   |
| Chicony HP Webcam [2 MP Macro]                                             | 2         | 1.08%   |
| Chicony HP Truevision HD                                                   | 2         | 1.08%   |
| Acer ThinkPad P50 Integrated Camera                                        | 2         | 1.08%   |
| Acer Integrated Camera                                                     | 2         | 1.08%   |
| Z-Star Vimicro USB Camera (Altair)                                         | 1         | 0.54%   |
| Xiaomi Mi 9 Lite                                                           | 1         | 0.54%   |
| Unknown USB Camera                                                         | 1         | 0.54%   |
| Suyin HP Webcam                                                            | 1         | 0.54%   |
| Suyin Asus Integrated Webcam                                               | 1         | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 42        | 67.74%  |
| Synaptics                  | 12        | 19.35%  |
| Shenzhen Goodix Technology | 5         | 8.06%   |
| LighTuning Technology      | 1         | 1.61%   |
| Elan Microelectronics      | 1         | 1.61%   |
| AuthenTec                  | 1         | 1.61%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 15        | 24.19%  |
| Validity Sensors VFS491                                                    | 7         | 11.29%  |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 6.45%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 6.45%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 6.45%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 4.84%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 4.84%   |
| Synaptics WBDI Device                                                      | 3         | 4.84%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 3.23%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 3.23%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 3.23%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 3.23%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 3.23%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.61%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.61%   |
| Synaptics UWP WBDI                                                         | 1         | 1.61%   |
| Synaptics  WBDI                                                            | 1         | 1.61%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 1.61%   |
| Shenzhen Goodix  Fingerprint Device                                        | 1         | 1.61%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.61%   |
| Elan ELAN:ARM-M4                                                           | 1         | 1.61%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 1.61%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 50%     |
| Upek        | 2         | 20%     |
| Alcor Micro | 2         | 20%     |
| O2 Micro    | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 30%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 20%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 20%     |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 10%     |
| Broadcom 5880                                                                | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 149       | 62.87%  |
| 1     | 72        | 30.38%  |
| 2     | 15        | 6.33%   |
| 3     | 1         | 0.42%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 62        | 60.19%  |
| Graphics card            | 10        | 9.71%   |
| Chipcard                 | 9         | 8.74%   |
| Net/wireless             | 5         | 4.85%   |
| Camera                   | 4         | 3.88%   |
| Multimedia controller    | 3         | 2.91%   |
| Storage                  | 2         | 1.94%   |
| Net/ethernet             | 2         | 1.94%   |
| Communication controller | 2         | 1.94%   |
| Bluetooth                | 2         | 1.94%   |
| Unassigned class         | 1         | 0.97%   |
| Sound                    | 1         | 0.97%   |

