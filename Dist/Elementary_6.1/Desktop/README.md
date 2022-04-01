Elementary 6.1 - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------

A project to collect tested hardware configurations for Elementary 6.1.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 107

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo   | ThinkCentre M58 6258D3G     | [b67f1750b8](https://linux-hardware.org/?probe=b67f1750b8) | Mar 31, 2022 |
| Lenovo   | ThinkCentre M58 6258D3G     | [1cd22c83f1](https://linux-hardware.org/?probe=1cd22c83f1) | Mar 31, 2022 |
| MSI      | H97 GAMING 3                | [97f38615e3](https://linux-hardware.org/?probe=97f38615e3) | Mar 31, 2022 |
| MSI      | MEG X570 ACE                | [55572b8a7e](https://linux-hardware.org/?probe=55572b8a7e) | Mar 31, 2022 |
| ASUSTek  | Rampage IV GENE             | [c067a4d0e7](https://linux-hardware.org/?probe=c067a4d0e7) | Mar 29, 2022 |
| Dell     | 0C522T A00                  | [33ae998152](https://linux-hardware.org/?probe=33ae998152) | Mar 26, 2022 |
| Dell     | 0C522T A00                  | [90242bb090](https://linux-hardware.org/?probe=90242bb090) | Mar 26, 2022 |
| MSI      | MPG B550 GAMING EDGE WIF... | [7577679057](https://linux-hardware.org/?probe=7577679057) | Mar 25, 2022 |
| Gigabyte | A320M-S2H-CF                | [a237859a86](https://linux-hardware.org/?probe=a237859a86) | Mar 24, 2022 |
| Intel    | X79Turbo V1.x               | [18b126a753](https://linux-hardware.org/?probe=18b126a753) | Mar 24, 2022 |
| AMI      | Cherry Trail CR             | [bbea34ce64](https://linux-hardware.org/?probe=bbea34ce64) | Mar 22, 2022 |
| AMI      | Cherry Trail CR             | [bc5a34ef7e](https://linux-hardware.org/?probe=bc5a34ef7e) | Mar 20, 2022 |
| ASUSTek  | Rampage IV GENE             | [7f5053b061](https://linux-hardware.org/?probe=7f5053b061) | Mar 16, 2022 |
| ASUSTek  | Rampage IV GENE             | [7ff55a3ca6](https://linux-hardware.org/?probe=7ff55a3ca6) | Mar 16, 2022 |
| ASUSTek  | P8H61-M LX3 R2.0            | [eda8848760](https://linux-hardware.org/?probe=eda8848760) | Mar 15, 2022 |
| AOpen    | D1009 A1A4                  | [a7375d4581](https://linux-hardware.org/?probe=a7375d4581) | Mar 13, 2022 |
| MSI      | B85I                        | [d134c8451b](https://linux-hardware.org/?probe=d134c8451b) | Mar 12, 2022 |
| ASRock   | B450M Pro4                  | [12459fc7ea](https://linux-hardware.org/?probe=12459fc7ea) | Mar 11, 2022 |
| Gigabyte | B150N Phoenix-WIFI-CF       | [a64818ccea](https://linux-hardware.org/?probe=a64818ccea) | Mar 10, 2022 |
| Biostar  | N68S3B                      | [aa1e6a4c82](https://linux-hardware.org/?probe=aa1e6a4c82) | Mar 10, 2022 |
| ASUSTek  | M11AD                       | [8bb5baaa5a](https://linux-hardware.org/?probe=8bb5baaa5a) | Mar 09, 2022 |
| Biostar  | H61MLV2                     | [d5c330bad8](https://linux-hardware.org/?probe=d5c330bad8) | Mar 08, 2022 |
| HP       | 2ADC                        | [ed0714a64a](https://linux-hardware.org/?probe=ed0714a64a) | Mar 07, 2022 |
| MSI      | B85I                        | [39926596b7](https://linux-hardware.org/?probe=39926596b7) | Mar 07, 2022 |
| Dell     | 0PU052                      | [766b0e4665](https://linux-hardware.org/?probe=766b0e4665) | Mar 06, 2022 |
| Dell     | 0PU052                      | [a8e19bd112](https://linux-hardware.org/?probe=a8e19bd112) | Mar 06, 2022 |
| HP       | 1589                        | [88876808e9](https://linux-hardware.org/?probe=88876808e9) | Mar 05, 2022 |
| HP       | 802E                        | [14c73a40e0](https://linux-hardware.org/?probe=14c73a40e0) | Mar 05, 2022 |
| ASRock   | FM2A58M-DG3+                | [0b7875b1b5](https://linux-hardware.org/?probe=0b7875b1b5) | Mar 05, 2022 |
| HP       | 805D                        | [2a09665009](https://linux-hardware.org/?probe=2a09665009) | Mar 02, 2022 |
| ASUSTek  | M4N72-E                     | [c3fe570b4d](https://linux-hardware.org/?probe=c3fe570b4d) | Feb 28, 2022 |
| ASUSTek  | H81-PLUS                    | [e8956dc4ec](https://linux-hardware.org/?probe=e8956dc4ec) | Feb 27, 2022 |
| Gigabyte | X470 AORUS ULTRA GAMING-... | [a6d5cc0368](https://linux-hardware.org/?probe=a6d5cc0368) | Feb 26, 2022 |
| Gigabyte | Z390 UD                     | [7ea66813f3](https://linux-hardware.org/?probe=7ea66813f3) | Feb 23, 2022 |
| ASUSTek  | PRIME B450M-GAMING/BR       | [73b31ddab0](https://linux-hardware.org/?probe=73b31ddab0) | Feb 20, 2022 |
| MSI      | B85I                        | [24674e9e3a](https://linux-hardware.org/?probe=24674e9e3a) | Feb 20, 2022 |
| Intel    | DH61BE AAG14062-210         | [00566bb73f](https://linux-hardware.org/?probe=00566bb73f) | Feb 19, 2022 |
| MSI      | B85I                        | [633f6bf495](https://linux-hardware.org/?probe=633f6bf495) | Feb 19, 2022 |
| ASUSTek  | M11AD                       | [035887c4ab](https://linux-hardware.org/?probe=035887c4ab) | Feb 18, 2022 |
| ASUSTek  | P5B                         | [fa4c095fd7](https://linux-hardware.org/?probe=fa4c095fd7) | Feb 17, 2022 |
| Intel    | H61                         | [a70c59ad0e](https://linux-hardware.org/?probe=a70c59ad0e) | Feb 17, 2022 |
| ASUSTek  | PRIME Z590-A                | [6beda6e2da](https://linux-hardware.org/?probe=6beda6e2da) | Feb 16, 2022 |
| Biostar  | A68MD PRO                   | [da42cc4da7](https://linux-hardware.org/?probe=da42cc4da7) | Feb 16, 2022 |
| MSI      | B85I                        | [28c1f1b8ae](https://linux-hardware.org/?probe=28c1f1b8ae) | Feb 13, 2022 |
| ASUSTek  | PRIME Z590-A                | [825734953d](https://linux-hardware.org/?probe=825734953d) | Feb 13, 2022 |
| MSI      | B85I                        | [898dced271](https://linux-hardware.org/?probe=898dced271) | Feb 13, 2022 |
| Gigabyte | F2A68HM-H                   | [a2a41e039c](https://linux-hardware.org/?probe=a2a41e039c) | Feb 13, 2022 |
| Gigabyte | F2A68HM-H                   | [2f3941c9cb](https://linux-hardware.org/?probe=2f3941c9cb) | Feb 12, 2022 |
| ASUSTek  | PRIME A320M-K               | [5f4de1e2b0](https://linux-hardware.org/?probe=5f4de1e2b0) | Feb 12, 2022 |
| ASUSTek  | PRIME B360M-K               | [698e174402](https://linux-hardware.org/?probe=698e174402) | Feb 09, 2022 |
| ASUSTek  | H110M-C                     | [82f3d6edf9](https://linux-hardware.org/?probe=82f3d6edf9) | Feb 09, 2022 |
| MSI      | B450I GAMING PLUS AC        | [a2af859752](https://linux-hardware.org/?probe=a2af859752) | Feb 09, 2022 |
| ECS      | H55H-M                      | [856a42d74b](https://linux-hardware.org/?probe=856a42d74b) | Feb 07, 2022 |
| ASUSTek  | ROG STRIX B360-H GAMING     | [92d9fdcc97](https://linux-hardware.org/?probe=92d9fdcc97) | Feb 07, 2022 |
| Lenovo   | NO DPK                      | [4bb7cedbd8](https://linux-hardware.org/?probe=4bb7cedbd8) | Feb 06, 2022 |
| HP       | 802E                        | [31e2fe159c](https://linux-hardware.org/?probe=31e2fe159c) | Feb 05, 2022 |
| ASUSTek  | H110M-C                     | [6ba127c715](https://linux-hardware.org/?probe=6ba127c715) | Feb 04, 2022 |
| ASUSTek  | P5B                         | [9b661f64dd](https://linux-hardware.org/?probe=9b661f64dd) | Feb 04, 2022 |
| Foxconn  | NETBOX nT-435/535 Ver       | [c7d50db62b](https://linux-hardware.org/?probe=c7d50db62b) | Feb 03, 2022 |
| Foxconn  | NETBOX nT-435/535 Ver       | [2ee2be7ccf](https://linux-hardware.org/?probe=2ee2be7ccf) | Feb 03, 2022 |
| HP       | ProLiant ML110 G7           | [2e1dcafe6c](https://linux-hardware.org/?probe=2e1dcafe6c) | Feb 03, 2022 |
| ASUSTek  | H110M-C                     | [4d2233f824](https://linux-hardware.org/?probe=4d2233f824) | Feb 03, 2022 |
| HP       | 339A                        | [cf9dca84ff](https://linux-hardware.org/?probe=cf9dca84ff) | Feb 02, 2022 |
| Unknown  | Unknown                     | [629972c689](https://linux-hardware.org/?probe=629972c689) | Feb 01, 2022 |
| HP       | 805D                        | [19295e5827](https://linux-hardware.org/?probe=19295e5827) | Feb 01, 2022 |
| ASUSTek  | H110I-PLUS                  | [ebeaf681e3](https://linux-hardware.org/?probe=ebeaf681e3) | Feb 01, 2022 |
| Gigabyte | B75M-D3H                    | [18717f0712](https://linux-hardware.org/?probe=18717f0712) | Feb 01, 2022 |
| MSI      | Z270 KRAIT GAMING           | [17ccbf9c76](https://linux-hardware.org/?probe=17ccbf9c76) | Jan 28, 2022 |
| Gigabyte | H61M-DS2                    | [e800b95c58](https://linux-hardware.org/?probe=e800b95c58) | Jan 26, 2022 |
| ASRock   | H61M-HVS                    | [8fdf1980ee](https://linux-hardware.org/?probe=8fdf1980ee) | Jan 25, 2022 |
| ASRock   | H61M-HVS                    | [5d19dff1e4](https://linux-hardware.org/?probe=5d19dff1e4) | Jan 25, 2022 |
| Acer     | ConceptD CM100-51A V:1.1    | [663bbd709d](https://linux-hardware.org/?probe=663bbd709d) | Jan 24, 2022 |
| FIRICH   | J1900                       | [937e24af64](https://linux-hardware.org/?probe=937e24af64) | Jan 22, 2022 |
| ASUSTek  | ROG STRIX B360-H GAMING     | [d1505fe489](https://linux-hardware.org/?probe=d1505fe489) | Jan 21, 2022 |
| ASUSTek  | ROG STRIX X570-E GAMING     | [75d67cd8a4](https://linux-hardware.org/?probe=75d67cd8a4) | Jan 20, 2022 |
| ASUSTek  | TUF GAMING B550M-PLUS       | [7a14d864d4](https://linux-hardware.org/?probe=7a14d864d4) | Jan 20, 2022 |
| ASUSTek  | TUF B365M-PLUS GAMING       | [ec51f5ca3e](https://linux-hardware.org/?probe=ec51f5ca3e) | Jan 19, 2022 |
| MSI      | B450 TOMAHAWK MAX II        | [488d339e77](https://linux-hardware.org/?probe=488d339e77) | Jan 19, 2022 |
| MSI      | B450M-A PRO MAX             | [e7225dad8e](https://linux-hardware.org/?probe=e7225dad8e) | Jan 17, 2022 |
| ASUSTek  | H61M-CS                     | [8855875fbd](https://linux-hardware.org/?probe=8855875fbd) | Jan 14, 2022 |
| Unknown  | T3 MRD                      | [33392a90ce](https://linux-hardware.org/?probe=33392a90ce) | Jan 13, 2022 |
| MSI      | X470 GAMING PLUS MAX        | [00a00c3cac](https://linux-hardware.org/?probe=00a00c3cac) | Jan 13, 2022 |
| ASUSTek  | M5A78L-M LX3                | [39f3687349](https://linux-hardware.org/?probe=39f3687349) | Jan 12, 2022 |
| Foxconn  | 2AB1                        | [07faf9a309](https://linux-hardware.org/?probe=07faf9a309) | Jan 12, 2022 |
| Foxconn  | 2AB1                        | [de61623232](https://linux-hardware.org/?probe=de61623232) | Jan 11, 2022 |
| ASUSTek  | H110M-C                     | [be4291793d](https://linux-hardware.org/?probe=be4291793d) | Jan 10, 2022 |
| Gigabyte | X570 AORUS ELITE            | [7ce29e0c54](https://linux-hardware.org/?probe=7ce29e0c54) | Jan 09, 2022 |
| HP       | 8597                        | [09ed815dd0](https://linux-hardware.org/?probe=09ed815dd0) | Jan 08, 2022 |
| Gigabyte | GA-970A-D3                  | [b1c9832ce6](https://linux-hardware.org/?probe=b1c9832ce6) | Jan 07, 2022 |
| ASRock   | Z370 Pro4                   | [51cba69624](https://linux-hardware.org/?probe=51cba69624) | Jan 06, 2022 |
| ASRock   | B450M-HDV R4.0              | [20dfc25b62](https://linux-hardware.org/?probe=20dfc25b62) | Jan 05, 2022 |
| Gigabyte | B85M-DS3H-A                 | [cd6abb9f49](https://linux-hardware.org/?probe=cd6abb9f49) | Jan 03, 2022 |
| MSI      | 2A9C                        | [8d08f7f383](https://linux-hardware.org/?probe=8d08f7f383) | Dec 31, 2021 |
| HP       | 3397                        | [323dc8992b](https://linux-hardware.org/?probe=323dc8992b) | Dec 31, 2021 |
| ASUSTek  | X79-DELUXE                  | [00b9dd3788](https://linux-hardware.org/?probe=00b9dd3788) | Dec 30, 2021 |
| HP       | 1589                        | [d123a8de64](https://linux-hardware.org/?probe=d123a8de64) | Dec 30, 2021 |
| Foxconn  | 2AB1                        | [bcd6fc46cc](https://linux-hardware.org/?probe=bcd6fc46cc) | Dec 30, 2021 |
| ASUSTek  | TUF GAMING B550M-PLUS       | [5f67c759fe](https://linux-hardware.org/?probe=5f67c759fe) | Dec 28, 2021 |
| Gigabyte | Z390 UD                     | [2399fa64ba](https://linux-hardware.org/?probe=2399fa64ba) | Dec 26, 2021 |
| Apple    | Mac-F42C88C8 Proto1         | [783618fe4b](https://linux-hardware.org/?probe=783618fe4b) | Dec 23, 2021 |
| ASUSTek  | H97-PLUS                    | [cba91c2ad2](https://linux-hardware.org/?probe=cba91c2ad2) | Dec 22, 2021 |
| MSI      | B450-A PRO MAX              | [f14eef1ae6](https://linux-hardware.org/?probe=f14eef1ae6) | Dec 20, 2021 |
| Gigabyte | H310M S2P                   | [a931eb10f0](https://linux-hardware.org/?probe=a931eb10f0) | Dec 19, 2021 |
| Foxconn  | 2AB1                        | [d9077a5d94](https://linux-hardware.org/?probe=d9077a5d94) | Dec 18, 2021 |
| Foxconn  | 2AB1                        | [b789981cc4](https://linux-hardware.org/?probe=b789981cc4) | Dec 17, 2021 |
| Gigabyte | Z590 AORUS ELITE AX         | [c068e358e8](https://linux-hardware.org/?probe=c068e358e8) | Dec 16, 2021 |
| ASUSTek  | M5A78L-M LX3                | [720cc7a45f](https://linux-hardware.org/?probe=720cc7a45f) | Dec 15, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 5.11.0-43-generic    | 21       | 24.71%  |
| 5.13.0-28-generic    | 16       | 18.82%  |
| 5.13.0-30-generic    | 9        | 10.59%  |
| 5.13.0-27-generic    | 8        | 9.41%   |
| 5.13.0-35-generic    | 7        | 8.24%   |
| 5.11.0-41-generic    | 5        | 5.88%   |
| 5.13.0-37-generic    | 4        | 4.71%   |
| 5.11.0-44-generic    | 4        | 4.71%   |
| 5.13.0-39-generic    | 2        | 2.35%   |
| 5.13.0-25-generic    | 2        | 2.35%   |
| 5.11.0-46-generic    | 2        | 2.35%   |
| 5.13.0-28-lowlatency | 1        | 1.18%   |
| 5.13.0-22-generic    | 1        | 1.18%   |
| 5.11.0-43-lowlatency | 1        | 1.18%   |
| 5.11.0-40-generic    | 1        | 1.18%   |
| 5.11.0-37-generic    | 1        | 1.18%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13.0  | 46       | 58.23%  |
| 5.11.0  | 33       | 41.77%  |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13    | 46       | 58.23%  |
| 5.11    | 33       | 41.77%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 77       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Pantheon | 77       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 77       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 65       | 84.42%  |
| LightDM | 12       | 15.58%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 30       | 38.96%  |
| de_DE | 11       | 14.29%  |
| es_ES | 7        | 9.09%   |
| fr_FR | 6        | 7.79%   |
| en_GB | 5        | 6.49%   |
| ru_RU | 4        | 5.19%   |
| it_IT | 3        | 3.9%    |
| tr_TR | 2        | 2.6%    |
| pl_PL | 2        | 2.6%    |
| sr_RS | 1        | 1.3%    |
| pt_PT | 1        | 1.3%    |
| pt_BR | 1        | 1.3%    |
| ja_JP | 1        | 1.3%    |
| fr_CA | 1        | 1.3%    |
| en_CA | 1        | 1.3%    |
| en_AU | 1        | 1.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 40       | 51.95%  |
| BIOS | 37       | 48.05%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 74       | 96.1%   |
| Btrfs | 2        | 2.6%    |
| Xfs   | 1        | 1.3%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 67       | 87.01%  |
| GPT     | 8        | 10.39%  |
| MBR     | 2        | 2.6%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 74       | 96.1%   |
| Yes       | 3        | 3.9%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 74       | 96.1%   |
| Yes       | 3        | 3.9%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 20       | 25.97%  |
| Gigabyte Technology | 13       | 16.88%  |
| MSI                 | 11       | 14.29%  |
| Hewlett-Packard     | 8        | 10.39%  |
| ASRock              | 5        | 6.49%   |
| Intel               | 3        | 3.9%    |
| Biostar             | 3        | 3.9%    |
| Lenovo              | 2        | 2.6%    |
| Foxconn             | 2        | 2.6%    |
| Dell                | 2        | 2.6%    |
| Unknown             | 2        | 2.6%    |
| FIRICH              | 1        | 1.3%    |
| ECS                 | 1        | 1.3%    |
| Apple               | 1        | 1.3%    |
| AOpen               | 1        | 1.3%    |
| AMI                 | 1        | 1.3%    |
| Acer                | 1        | 1.3%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| Gigabyte Z390 UD                 | 2        | 2.6%    |
| ASUS TUF GAMING B550M-PLUS       | 2        | 2.6%    |
| ASUS All Series                  | 2        | 2.6%    |
| Unknown                          | 2        | 2.6%    |
| MSI PPPPP-CCC#MMMMMMMM           | 1        | 1.3%    |
| MSI MS-7C91                      | 1        | 1.3%    |
| MSI MS-7C52                      | 1        | 1.3%    |
| MSI MS-7C35                      | 1        | 1.3%    |
| MSI MS-7C02                      | 1        | 1.3%    |
| MSI MS-7B86                      | 1        | 1.3%    |
| MSI MS-7B79                      | 1        | 1.3%    |
| MSI MS-7A59                      | 1        | 1.3%    |
| MSI MS-7A40                      | 1        | 1.3%    |
| MSI MS-7918                      | 1        | 1.3%    |
| MSI MS-7851                      | 1        | 1.3%    |
| Lenovo ThinkCentre M72e 3664AD7  | 1        | 1.3%    |
| Lenovo ThinkCentre M58 6258D3G   | 1        | 1.3%    |
| Intel X79                        | 1        | 1.3%    |
| Intel H61                        | 1        | 1.3%    |
| Intel DH61BE AAG14062-210        | 1        | 1.3%    |
| HP Z420 Workstation              | 1        | 1.3%    |
| HP Z240 SFF Workstation          | 1        | 1.3%    |
| HP ProLiant ML110 G7             | 1        | 1.3%    |
| HP ProDesk 600 G5 SFF            | 1        | 1.3%    |
| HP ProDesk 600 G2 SFF            | 1        | 1.3%    |
| HP Compaq Pro 6300 MT            | 1        | 1.3%    |
| HP Compaq Elite 8300 SFF         | 1        | 1.3%    |
| HP 520-1175a                     | 1        | 1.3%    |
| Gigabyte Z590 AORUS ELITE AX     | 1        | 1.3%    |
| Gigabyte X570 AORUS ELITE        | 1        | 1.3%    |
| Gigabyte X470 AORUS ULTRA GAMING | 1        | 1.3%    |
| Gigabyte H61M-DS2                | 1        | 1.3%    |
| Gigabyte H310M S2P 2.0           | 1        | 1.3%    |
| Gigabyte GA-970A-D3              | 1        | 1.3%    |
| Gigabyte F2A68HM-H               | 1        | 1.3%    |
| Gigabyte B85M-DS3H-A             | 1        | 1.3%    |
| Gigabyte B75M-D3H                | 1        | 1.3%    |
| Gigabyte B150N Phoenix-WIFI      | 1        | 1.3%    |
| Gigabyte A320M-S2H               | 1        | 1.3%    |
| Foxconn p6616f                   | 1        | 1.3%    |
| Foxconn nT435/nT535              | 1        | 1.3%    |
| FIRICH J1900                     | 1        | 1.3%    |
| ECS H55H-M                       | 1        | 1.3%    |
| Dell OptiPlex 980                | 1        | 1.3%    |
| Dell OptiPlex 755                | 1        | 1.3%    |
| Biostar N68S3B                   | 1        | 1.3%    |
| Biostar H61MLV2                  | 1        | 1.3%    |
| Biostar A68MD PRO                | 1        | 1.3%    |
| ASUS X79-DELUXE                  | 1        | 1.3%    |
| ASUS TUF B365M-PLUS GAMING       | 1        | 1.3%    |
| ASUS ROG STRIX X570-E GAMING     | 1        | 1.3%    |
| ASUS ROG STRIX B360-H GAMING     | 1        | 1.3%    |
| ASUS Rampage IV GENE             | 1        | 1.3%    |
| ASUS PRIME Z590-A                | 1        | 1.3%    |
| ASUS PRIME B450M-GAMING/BR       | 1        | 1.3%    |
| ASUS PRIME B360M-K               | 1        | 1.3%    |
| ASUS P8H61-M LX3 R2.0            | 1        | 1.3%    |
| ASUS P5B                         | 1        | 1.3%    |
| ASUS M5A78L-M LX3                | 1        | 1.3%    |
| ASUS M4N72-E                     | 1        | 1.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS TUF               | 3        | 3.9%    |
| ASUS PRIME             | 3        | 3.9%    |
| Lenovo ThinkCentre     | 2        | 2.6%    |
| HP ProDesk             | 2        | 2.6%    |
| HP Compaq              | 2        | 2.6%    |
| Gigabyte Z390          | 2        | 2.6%    |
| Dell OptiPlex          | 2        | 2.6%    |
| ASUS ROG               | 2        | 2.6%    |
| ASUS All               | 2        | 2.6%    |
| Unknown                | 2        | 2.6%    |
| MSI PPPPP-CCC#MMMMMMMM | 1        | 1.3%    |
| MSI MS-7C91            | 1        | 1.3%    |
| MSI MS-7C52            | 1        | 1.3%    |
| MSI MS-7C35            | 1        | 1.3%    |
| MSI MS-7C02            | 1        | 1.3%    |
| MSI MS-7B86            | 1        | 1.3%    |
| MSI MS-7B79            | 1        | 1.3%    |
| MSI MS-7A59            | 1        | 1.3%    |
| MSI MS-7A40            | 1        | 1.3%    |
| MSI MS-7918            | 1        | 1.3%    |
| MSI MS-7851            | 1        | 1.3%    |
| Intel X79              | 1        | 1.3%    |
| Intel H61              | 1        | 1.3%    |
| Intel DH61BE           | 1        | 1.3%    |
| HP Z420                | 1        | 1.3%    |
| HP Z240                | 1        | 1.3%    |
| HP ProLiant            | 1        | 1.3%    |
| HP 520-1175a           | 1        | 1.3%    |
| Gigabyte Z590          | 1        | 1.3%    |
| Gigabyte X570          | 1        | 1.3%    |
| Gigabyte X470          | 1        | 1.3%    |
| Gigabyte H61M-DS2      | 1        | 1.3%    |
| Gigabyte H310M         | 1        | 1.3%    |
| Gigabyte GA-970A-D3    | 1        | 1.3%    |
| Gigabyte F2A68HM-H     | 1        | 1.3%    |
| Gigabyte B85M-DS3H-A   | 1        | 1.3%    |
| Gigabyte B75M-D3H      | 1        | 1.3%    |
| Gigabyte B150N         | 1        | 1.3%    |
| Gigabyte A320M-S2H     | 1        | 1.3%    |
| Foxconn p6616f         | 1        | 1.3%    |
| Foxconn nT435          | 1        | 1.3%    |
| FIRICH J1900           | 1        | 1.3%    |
| ECS H55H-M             | 1        | 1.3%    |
| Biostar N68S3B         | 1        | 1.3%    |
| Biostar H61MLV2        | 1        | 1.3%    |
| Biostar A68MD          | 1        | 1.3%    |
| ASUS X79-DELUXE        | 1        | 1.3%    |
| ASUS Rampage           | 1        | 1.3%    |
| ASUS P8H61-M           | 1        | 1.3%    |
| ASUS P5B               | 1        | 1.3%    |
| ASUS M5A78L-M          | 1        | 1.3%    |
| ASUS M4N72-E           | 1        | 1.3%    |
| ASUS M11AD             | 1        | 1.3%    |
| ASUS H61M-CS           | 1        | 1.3%    |
| ASUS H110M-C           | 1        | 1.3%    |
| ASUS H110I-PLUS        | 1        | 1.3%    |
| ASRock Z370            | 1        | 1.3%    |
| ASRock H61M-HVS        | 1        | 1.3%    |
| ASRock FM2A58M-DG3+    | 1        | 1.3%    |
| ASRock B450M-HDV       | 1        | 1.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 10       | 12.99%  |
| 2012 | 10       | 12.99%  |
| 2019 | 8        | 10.39%  |
| 2020 | 7        | 9.09%   |
| 2015 | 6        | 7.79%   |
| 2014 | 6        | 7.79%   |
| 2011 | 6        | 7.79%   |
| 2010 | 5        | 6.49%   |
| 2021 | 4        | 5.19%   |
| 2017 | 4        | 5.19%   |
| 2013 | 4        | 5.19%   |
| 2016 | 3        | 3.9%    |
| 2009 | 1        | 1.3%    |
| 2008 | 1        | 1.3%    |
| 2007 | 1        | 1.3%    |
| 2006 | 1        | 1.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 77       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 76       | 98.7%   |
| Enabled  | 1        | 1.3%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 77       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 17       | 21.79%  |
| 16.01-24.0  | 17       | 21.79%  |
| 8.01-16.0   | 15       | 19.23%  |
| 4.01-8.0    | 13       | 16.67%  |
| 3.01-4.0    | 9        | 11.54%  |
| 24.01-32.0  | 2        | 2.56%   |
| 64.01-256.0 | 2        | 2.56%   |
| 1.01-2.0    | 2        | 2.56%   |
| 2.01-3.0    | 1        | 1.28%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 35       | 41.18%  |
| 2.01-3.0  | 23       | 27.06%  |
| 4.01-8.0  | 13       | 15.29%  |
| 3.01-4.0  | 11       | 12.94%  |
| 8.01-16.0 | 3        | 3.53%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 27       | 34.18%  |
| 1      | 27       | 34.18%  |
| 3      | 11       | 13.92%  |
| 4      | 8        | 10.13%  |
| 7      | 2        | 2.53%   |
| 6      | 2        | 2.53%   |
| 5      | 2        | 2.53%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 47       | 60.26%  |
| Yes       | 31       | 39.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 77       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 39       | 50.65%  |
| Yes       | 38       | 49.35%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 50       | 64.94%  |
| Yes       | 27       | 35.06%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Germany      | 11       | 14.29%  |
| USA          | 8        | 10.39%  |
| UK           | 5        | 6.49%   |
| Spain        | 5        | 6.49%   |
| France       | 5        | 6.49%   |
| Russia       | 4        | 5.19%   |
| Italy        | 3        | 3.9%    |
| Indonesia    | 3        | 3.9%    |
| Australia    | 3        | 3.9%    |
| Turkey       | 2        | 2.6%    |
| Poland       | 2        | 2.6%    |
| Iran         | 2        | 2.6%    |
| India        | 2        | 2.6%    |
| Canada       | 2        | 2.6%    |
| Brazil       | 2        | 2.6%    |
| Argentina    | 2        | 2.6%    |
| Thailand     | 1        | 1.3%    |
| Switzerland  | 1        | 1.3%    |
| Sweden       | 1        | 1.3%    |
| Sri Lanka    | 1        | 1.3%    |
| South Africa | 1        | 1.3%    |
| Serbia       | 1        | 1.3%    |
| Norway       | 1        | 1.3%    |
| New Zealand  | 1        | 1.3%    |
| Netherlands  | 1        | 1.3%    |
| Mexico       | 1        | 1.3%    |
| Lithuania    | 1        | 1.3%    |
| Japan        | 1        | 1.3%    |
| Hong Kong    | 1        | 1.3%    |
| Egypt        | 1        | 1.3%    |
| Czechia      | 1        | 1.3%    |
| Austria      | 1        | 1.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Warsaw                  | 2        | 2.41%   |
| Hamburg                 | 2        | 2.41%   |
| Brisbane                | 2        | 2.41%   |
| Znojmo                  | 1        | 1.2%    |
| Woolloongabba           | 1        | 1.2%    |
| Wolgast                 | 1        | 1.2%    |
| Wattala                 | 1        | 1.2%    |
| Vilanova i la GeltrÃº | 1        | 1.2%    |
| Vienna                  | 1        | 1.2%    |
| Uppsala                 | 1        | 1.2%    |
| Tournus                 | 1        | 1.2%    |
| Thrissur                | 1        | 1.2%    |
| Tehran                  | 1        | 1.2%    |
| Tangerang               | 1        | 1.2%    |
| Sydney                  | 1        | 1.2%    |
| Suresnes                | 1        | 1.2%    |
| Spello                  | 1        | 1.2%    |
| Southampton             | 1        | 1.2%    |
| Sornay                  | 1        | 1.2%    |
| Sentmenat               | 1        | 1.2%    |
| Sao Paulo               | 1        | 1.2%    |
| Saguenay                | 1        | 1.2%    |
| Russell                 | 1        | 1.2%    |
| Rueso                   | 1        | 1.2%    |
| Rotterdam               | 1        | 1.2%    |
| Pune                    | 1        | 1.2%    |
| Plano                   | 1        | 1.2%    |
| Paris                   | 1        | 1.2%    |
| Oldham                  | 1        | 1.2%    |
| Oldenburg               | 1        | 1.2%    |
| Novi Sad                | 1        | 1.2%    |
| Neubrandenburg          | 1        | 1.2%    |
| Muralto                 | 1        | 1.2%    |
| Moscow                  | 1        | 1.2%    |
| Monmouth                | 1        | 1.2%    |
| Milan                   | 1        | 1.2%    |
| McKinney                | 1        | 1.2%    |
| MÃ¡laga               | 1        | 1.2%    |
| Madrid                  | 1        | 1.2%    |
| MaÅ¾eikiai            | 1        | 1.2%    |
| Lyngdal                 | 1        | 1.2%    |
| London                  | 1        | 1.2%    |
| Lauterbach              | 1        | 1.2%    |
| Lasino                  | 1        | 1.2%    |
| Larnage                 | 1        | 1.2%    |
| La Plata                | 1        | 1.2%    |
| Krasnodar               | 1        | 1.2%    |
| Kobe                    | 1        | 1.2%    |
| Kingston                | 1        | 1.2%    |
| Khimki                  | 1        | 1.2%    |
| Kazan’                | 1        | 1.2%    |
| Johannesburg            | 1        | 1.2%    |
| Jakarta                 | 1        | 1.2%    |
| Istanbul                | 1        | 1.2%    |
| Hennef                  | 1        | 1.2%    |
| Garin                   | 1        | 1.2%    |
| Fairmont                | 1        | 1.2%    |
| Edmonton                | 1        | 1.2%    |
| Ecatepec                | 1        | 1.2%    |
| Dresden                 | 1        | 1.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 23       | 35     | 15.97%  |
| Seagate                   | 21       | 27     | 14.58%  |
| Samsung Electronics       | 19       | 29     | 13.19%  |
| Kingston                  | 16       | 17     | 11.11%  |
| Toshiba                   | 8        | 9      | 5.56%   |
| Crucial                   | 7        | 7      | 4.86%   |
| Unknown                   | 5        | 12     | 3.47%   |
| SanDisk                   | 5        | 7      | 3.47%   |
| Intel                     | 4        | 4      | 2.78%   |
| Hitachi                   | 4        | 4      | 2.78%   |
| A-DATA Technology         | 4        | 4      | 2.78%   |
| PNY                       | 3        | 5      | 2.08%   |
| Phison                    | 3        | 3      | 2.08%   |
| ASMT                      | 3        | 3      | 2.08%   |
| Micron Technology         | 2        | 2      | 1.39%   |
| XPG                       | 1        | 1      | 0.69%   |
| Transcend                 | 1        | 1      | 0.69%   |
| Team                      | 1        | 1      | 0.69%   |
| Realtek Semiconductor     | 1        | 1      | 0.69%   |
| PLEXTOR                   | 1        | 1      | 0.69%   |
| OCZ                       | 1        | 1      | 0.69%   |
| Netac                     | 1        | 1      | 0.69%   |
| MidasForce                | 1        | 1      | 0.69%   |
| Micron/Crucial Technology | 1        | 2      | 0.69%   |
| MAXTOR                    | 1        | 1      | 0.69%   |
| Leven                     | 1        | 1      | 0.69%   |
| JMicron                   | 1        | 1      | 0.69%   |
| Intenso                   | 1        | 1      | 0.69%   |
| Hewlett-Packard           | 1        | 1      | 0.69%   |
| GOODRAM                   | 1        | 1      | 0.69%   |
| Gigabyte Technology       | 1        | 1      | 0.69%   |
| Corsair                   | 1        | 1      | 0.69%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Samsung NVMe SSD Drive 500GB       | 4        | 2.48%   |
| Kingston SA400S37120G 120GB SSD    | 4        | 2.48%   |
| Toshiba DT01ACA050 500GB           | 3        | 1.86%   |
| Kingston SA400S37240G 240GB SSD    | 3        | 1.86%   |
| Crucial CT240BX500SSD1 240GB       | 3        | 1.86%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 2        | 1.24%   |
| WDC WD40EFRX-68N32N0 4TB           | 2        | 1.24%   |
| Unknown SD/MMC 16GB                | 2        | 1.24%   |
| Unknown M.S./M.S.Pro/HG 16GB       | 2        | 1.24%   |
| Toshiba HDWD110 1TB                | 2        | 1.24%   |
| Seagate ST3500418AS 500GB          | 2        | 1.24%   |
| Seagate ST2000DX002-2DV164 2TB     | 2        | 1.24%   |
| Seagate ST1000DM003-1ER162 1TB     | 2        | 1.24%   |
| Samsung SSD 850 EVO 250GB          | 2        | 1.24%   |
| Samsung HD322HJ 320GB              | 2        | 1.24%   |
| PNY CS900 480GB SSD                | 2        | 1.24%   |
| Phison NVMe SSD Drive 1TB          | 2        | 1.24%   |
| Kingston NVMe SSD Drive 1TB        | 2        | 1.24%   |
| Crucial CT1000MX500SSD1 1TB        | 2        | 1.24%   |
| XPG NVMe SSD Drive 512GB           | 1        | 0.62%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 1        | 0.62%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD   | 1        | 0.62%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 1        | 0.62%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 1        | 0.62%   |
| WDC WD6401AALS-00L3B2 640GB        | 1        | 0.62%   |
| WDC WD5000AVDS-63U7B1 500GB        | 1        | 0.62%   |
| WDC WD5000AAKX-001CA0 500GB        | 1        | 0.62%   |
| WDC WD5000AAKS-00UU3A0 500GB       | 1        | 0.62%   |
| WDC WD5000AAKS-00A7B2 500GB        | 1        | 0.62%   |
| WDC WD40EZAZ-00SF3B0 4TB           | 1        | 0.62%   |
| WDC WD3200AAJS-00L7A0 320GB        | 1        | 0.62%   |
| WDC WD30PURX-64P6ZY0 3TB           | 1        | 0.62%   |
| WDC WD3003FZEX-00Z4SA0 3TB         | 1        | 0.62%   |
| WDC WD20EFRX-68EUZN0 2TB           | 1        | 0.62%   |
| WDC WD20EARX-00PASB0 2TB           | 1        | 0.62%   |
| WDC WD1600JS-55NCB1 160GB          | 1        | 0.62%   |
| WDC WD15EARX-00PASB0 1TB           | 1        | 0.62%   |
| WDC WD10EZEX-22MFCA0 1TB           | 1        | 0.62%   |
| WDC WD10EZEX-08WN4A0 1TB           | 1        | 0.62%   |
| WDC WD10EZEX-08M2NA0 1TB           | 1        | 0.62%   |
| WDC WD10EZEX-00UD2A0 1TB           | 1        | 0.62%   |
| WDC WD10EZEX-00BN5A0 1TB           | 1        | 0.62%   |
| WDC WD10EADS-00L5B1 1TB            | 1        | 0.62%   |
| WDC SSC-D0064SC-2100 64GB          | 1        | 0.62%   |
| WDC PC SN730 SDBQNTY-1T00-1014 1TB | 1        | 0.62%   |
| Unknown SD/MMC/MS PRO 32GB         | 1        | 0.62%   |
| Unknown SD/MMC/M.S.PRO 32GB        | 1        | 0.62%   |
| Unknown MMC Card  32GB             | 1        | 0.62%   |
| Unknown 128G32  128GB              | 1        | 0.62%   |
| Transcend TS512GSSD370S 512GB      | 1        | 0.62%   |
| Toshiba TR150 480GB SSD            | 1        | 0.62%   |
| Toshiba HDWE160 6TB                | 1        | 0.62%   |
| Toshiba HDWE140 4TB                | 1        | 0.62%   |
| Toshiba HDWD120 2TB                | 1        | 0.62%   |
| Team T253X1120G 120GB SSD          | 1        | 0.62%   |
| Seagate ST9500325AS 500GB          | 1        | 0.62%   |
| Seagate ST93205620AS 320GB         | 1        | 0.62%   |
| Seagate ST4000DX001-1CE168 4TB     | 1        | 0.62%   |
| Seagate ST3750528AS 752GB          | 1        | 0.62%   |
| Seagate ST3500312CS 500GB          | 1        | 0.62%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 20       | 26     | 35.09%  |
| WDC                 | 19       | 25     | 33.33%  |
| Toshiba             | 7        | 8      | 12.28%  |
| Hitachi             | 4        | 4      | 7.02%   |
| Samsung Electronics | 3        | 4      | 5.26%   |
| ASMT                | 2        | 2      | 3.51%   |
| Unknown             | 1        | 1      | 1.75%   |
| Hewlett-Packard     | 1        | 1      | 1.75%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 13       | 17     | 20.97%  |
| Kingston            | 12       | 13     | 19.35%  |
| Crucial             | 7        | 7      | 11.29%  |
| SanDisk             | 5        | 6      | 8.06%   |
| WDC                 | 4        | 8      | 6.45%   |
| PNY                 | 3        | 5      | 4.84%   |
| A-DATA Technology   | 3        | 3      | 4.84%   |
| Intel               | 2        | 2      | 3.23%   |
| Transcend           | 1        | 1      | 1.61%   |
| Toshiba             | 1        | 1      | 1.61%   |
| Team                | 1        | 1      | 1.61%   |
| PLEXTOR             | 1        | 1      | 1.61%   |
| OCZ                 | 1        | 1      | 1.61%   |
| MidasForce          | 1        | 1      | 1.61%   |
| Micron Technology   | 1        | 1      | 1.61%   |
| MAXTOR              | 1        | 1      | 1.61%   |
| Leven               | 1        | 1      | 1.61%   |
| Intenso             | 1        | 1      | 1.61%   |
| GOODRAM             | 1        | 1      | 1.61%   |
| Gigabyte Technology | 1        | 1      | 1.61%   |
| Corsair             | 1        | 1      | 1.61%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 55       | 74     | 42.31%  |
| HDD     | 47       | 71     | 36.15%  |
| NVMe    | 20       | 26     | 15.38%  |
| Unknown | 6        | 13     | 4.62%   |
| MMC     | 2        | 2      | 1.54%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 71       | 141    | 69.61%  |
| NVMe | 20       | 26     | 19.61%  |
| SAS  | 9        | 17     | 8.82%   |
| MMC  | 2        | 2      | 1.96%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 55       | 90     | 58.51%  |
| 0.51-1.0   | 20       | 33     | 21.28%  |
| 1.01-2.0   | 8        | 9      | 8.51%   |
| 3.01-4.0   | 7        | 8      | 7.45%   |
| 2.01-3.0   | 2        | 3      | 2.13%   |
| 4.01-10.0  | 2        | 2      | 2.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 24       | 30.38%  |
| 251-500        | 20       | 25.32%  |
| 501-1000       | 12       | 15.19%  |
| 1001-2000      | 8        | 10.13%  |
| More than 3000 | 6        | 7.59%   |
| 51-100         | 5        | 6.33%   |
| 21-50          | 3        | 3.8%    |
| 2001-3000      | 1        | 1.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 32       | 38.1%   |
| 21-50          | 13       | 15.48%  |
| 101-250        | 13       | 15.48%  |
| 251-500        | 8        | 9.52%   |
| 51-100         | 7        | 8.33%   |
| 501-1000       | 6        | 7.14%   |
| 1001-2000      | 3        | 3.57%   |
| More than 3000 | 1        | 1.19%   |
| 2001-3000      | 1        | 1.19%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate ST3500312CS 500GB | 1        | 1      | 50%     |
| SanDisk SSD PLUS 240GB    | 1        | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 50%     |
| SanDisk | 1        | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 1        | 1      | 50%     |
| HDD  | 1        | 1      | 50%     |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 69       | 165    | 87.34%  |
| Works    | 8        | 19     | 10.13%  |
| Malfunc  | 2        | 2      | 2.53%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 52       | 50%     |
| AMD                         | 22       | 21.15%  |
| Samsung Electronics         | 7        | 6.73%   |
| Kingston Technology Company | 4        | 3.85%   |
| Phison Electronics          | 3        | 2.88%   |
| ASMedia Technology          | 3        | 2.88%   |
| Sandisk                     | 2        | 1.92%   |
| Realtek Semiconductor       | 2        | 1.92%   |
| Nvidia                      | 2        | 1.92%   |
| Marvell Technology Group    | 2        | 1.92%   |
| Seagate Technology          | 1        | 0.96%   |
| Micron/Crucial Technology   | 1        | 0.96%   |
| Micron Technology           | 1        | 0.96%   |
| JMicron Technology          | 1        | 0.96%   |
| ADATA Technology            | 1        | 0.96%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 11       | 8.66%   |
| AMD 400 Series Chipset SATA Controller                                                  | 9        | 7.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 5.51%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 4.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5        | 3.94%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5        | 3.94%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 4        | 3.15%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 3.15%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 3.15%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4        | 3.15%   |
| Kingston Company A2000 NVMe SSD                                                         | 3        | 2.36%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3        | 2.36%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 2.36%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3        | 2.36%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 1.57%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 1.57%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 1.57%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 1.57%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 1.57%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 1.57%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 1.57%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 2        | 1.57%   |
| Seagate FireCuda 530 SSD                                                                | 1        | 0.79%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 0.79%   |
| Sandisk Non-Volatile memory controller                                                  | 1        | 0.79%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.79%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.79%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 1        | 0.79%   |
| Realtek Realtek Non-Volatile memory controller                                          | 1        | 0.79%   |
| Phison E12 NVMe Controller                                                              | 1        | 0.79%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 1        | 0.79%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                            | 1        | 0.79%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 0.79%   |
| Nvidia MCP61 IDE                                                                        | 1        | 0.79%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 0.79%   |
| Micron Non-Volatile memory controller                                                   | 1        | 0.79%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 1        | 0.79%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 1        | 0.79%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                                      | 1        | 0.79%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 0.79%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                 | 1        | 0.79%   |
| Intel SSD 660P Series                                                                   | 1        | 0.79%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 0.79%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1        | 0.79%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 0.79%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 0.79%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1        | 0.79%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1        | 0.79%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1        | 0.79%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 1        | 0.79%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1        | 0.79%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1        | 0.79%   |
| Intel 82801HB (ICH8) 4 port SATA Controller [AHCI mode]                                 | 1        | 0.79%   |
| Intel 631xESB/632xESB SATA AHCI Controller                                              | 1        | 0.79%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 1        | 0.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 1        | 0.79%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 1        | 0.79%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 1        | 0.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 0.79%   |
| AMD FCH SATA Controller D                                                               | 1        | 0.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 67       | 63.21%  |
| NVMe | 20       | 18.87%  |
| IDE  | 16       | 15.09%  |
| RAID | 2        | 1.89%   |
| SAS  | 1        | 0.94%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 53       | 68.83%  |
| AMD    | 24       | 31.17%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor          | 4        | 5.19%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 3.9%    |
| Intel Core i7-9700 CPU @ 3.00GHz            | 2        | 2.6%    |
| Intel Core i5-8400 CPU @ 2.80GHz            | 2        | 2.6%    |
| Intel Core i3 CPU 530 @ 2.93GHz             | 2        | 2.6%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 2        | 2.6%    |
| Intel 11th Gen Core i7-11700K @ 3.60GHz     | 2        | 2.6%    |
| AMD Ryzen 9 3900X 12-Core Processor         | 2        | 2.6%    |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 2.6%    |
| Intel Xeon CPU E5462 @ 2.80GHz              | 1        | 1.3%    |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1        | 1.3%    |
| Intel Xeon CPU E5-2665 0 @ 2.40GHz          | 1        | 1.3%    |
| Intel Xeon CPU E5-1660 0 @ 3.30GHz          | 1        | 1.3%    |
| Intel Xeon CPU E31270 @ 3.40GHz             | 1        | 1.3%    |
| Intel Xeon CPU E31240 @ 3.30GHz             | 1        | 1.3%    |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz         | 1        | 1.3%    |
| Intel Pentium CPU G630 @ 2.70GHz            | 1        | 1.3%    |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 1.3%    |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 1.3%    |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 1.3%    |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 1.3%    |
| Intel Core i7-4930K CPU @ 3.40GHz           | 1        | 1.3%    |
| Intel Core i7-4790S CPU @ 3.20GHz           | 1        | 1.3%    |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 1.3%    |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 1.3%    |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 1.3%    |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 1.3%    |
| Intel Core i5-9400F CPU @ 2.90GHz           | 1        | 1.3%    |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 1.3%    |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1        | 1.3%    |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 1.3%    |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1        | 1.3%    |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1        | 1.3%    |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 1.3%    |
| Intel Core i3-9100F CPU @ 3.60GHz           | 1        | 1.3%    |
| Intel Core i3-8100 CPU @ 3.60GHz            | 1        | 1.3%    |
| Intel Core i3-6100 CPU @ 3.70GHz            | 1        | 1.3%    |
| Intel Core i3-4160 CPU @ 3.60GHz            | 1        | 1.3%    |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1        | 1.3%    |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1        | 1.3%    |
| Intel Core i3 CPU 550 @ 3.20GHz             | 1        | 1.3%    |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz       | 1        | 1.3%    |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1        | 1.3%    |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 1        | 1.3%    |
| Intel Celeron J4125 CPU @ 2.00GHz           | 1        | 1.3%    |
| Intel Celeron CPU J1900 @ 1.99GHz           | 1        | 1.3%    |
| Intel Celeron CPU G530 @ 2.40GHz            | 1        | 1.3%    |
| Intel Celeron CPU G440 @ 1.60GHz            | 1        | 1.3%    |
| Intel Atom CPU D525 @ 1.80GHz               | 1        | 1.3%    |
| AMD Ryzen 7 5800X 8-Core Processor          | 1        | 1.3%    |
| AMD Ryzen 7 3800X 8-Core Processor          | 1        | 1.3%    |
| AMD Ryzen 5 3600 6-Core Processor           | 1        | 1.3%    |
| AMD Ryzen 5 2600X Six-Core Processor        | 1        | 1.3%    |
| AMD Ryzen 5 1600 Six-Core Processor         | 1        | 1.3%    |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 1        | 1.3%    |
| AMD Phenom II X4 B55 Processor              | 1        | 1.3%    |
| AMD Phenom II X4 955 Processor              | 1        | 1.3%    |
| AMD Phenom II X4 820 Processor              | 1        | 1.3%    |
| AMD FX-4100 Quad-Core Processor             | 1        | 1.3%    |
| AMD Athlon X4 750K Quad Core Processor      | 1        | 1.3%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core i5     | 13       | 16.88%  |
| Intel Core i7     | 11       | 14.29%  |
| Intel Core i3     | 9        | 11.69%  |
| Intel Xeon        | 7        | 9.09%   |
| AMD Ryzen 7       | 6        | 7.79%   |
| AMD Ryzen 5       | 5        | 6.49%   |
| Intel Celeron     | 4        | 5.19%   |
| Intel Atom        | 3        | 3.9%    |
| AMD Phenom II X4  | 3        | 3.9%    |
| Other             | 2        | 2.6%    |
| Intel Core 2 Duo  | 2        | 2.6%    |
| AMD Ryzen 9       | 2        | 2.6%    |
| AMD Athlon        | 2        | 2.6%    |
| Intel Pentium     | 1        | 1.3%    |
| Intel Core 2 Quad | 1        | 1.3%    |
| AMD Ryzen 3       | 1        | 1.3%    |
| AMD FX            | 1        | 1.3%    |
| AMD Athlon X4     | 1        | 1.3%    |
| AMD Athlon II X2  | 1        | 1.3%    |
| AMD A8            | 1        | 1.3%    |
| AMD A10           | 1        | 1.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 29       | 37.66%  |
| 2      | 20       | 25.97%  |
| 8      | 14       | 18.18%  |
| 6      | 11       | 14.29%  |
| 12     | 2        | 2.6%    |
| 1      | 1        | 1.3%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 76       | 98.7%   |
| 2      | 1        | 1.3%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 44       | 57.14%  |
| 1      | 33       | 42.86%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 77       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x206a7    | 9        | 11.69%  |
| 0x306c3    | 6        | 7.79%   |
| 0x08701021 | 6        | 7.79%   |
| 0x306a9    | 5        | 6.49%   |
| 0x506e3    | 4        | 5.19%   |
| 0x906ea    | 3        | 3.9%    |
| 0x206d7    | 3        | 3.9%    |
| Unknown    | 3        | 3.9%    |
| 0xa0671    | 2        | 2.6%    |
| 0x906ed    | 2        | 2.6%    |
| 0x906eb    | 2        | 2.6%    |
| 0x906e9    | 2        | 2.6%    |
| 0x406c4    | 2        | 2.6%    |
| 0x20652    | 2        | 2.6%    |
| 0x1067a    | 2        | 2.6%    |
| 0x08108109 | 2        | 2.6%    |
| 0x0800820d | 2        | 2.6%    |
| 0x06003106 | 2        | 2.6%    |
| 0x010000c8 | 2        | 2.6%    |
| 0x906ec    | 1        | 1.3%    |
| 0x706a8    | 1        | 1.3%    |
| 0x6fb      | 1        | 1.3%    |
| 0x306e4    | 1        | 1.3%    |
| 0x30678    | 1        | 1.3%    |
| 0x20655    | 1        | 1.3%    |
| 0x106ca    | 1        | 1.3%    |
| 0x10676    | 1        | 1.3%    |
| 0x0a201009 | 1        | 1.3%    |
| 0x08701013 | 1        | 1.3%    |
| 0x08101016 | 1        | 1.3%    |
| 0x08001138 | 1        | 1.3%    |
| 0x06001119 | 1        | 1.3%    |
| 0x0600063e | 1        | 1.3%    |
| 0x010000db | 1        | 1.3%    |
| 0x010000c7 | 1        | 1.3%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| SandyBridge   | 12       | 15.58%  |
| KabyLake      | 11       | 14.29%  |
| Zen 2         | 8        | 10.39%  |
| IvyBridge     | 6        | 7.79%   |
| Haswell       | 6        | 7.79%   |
| Zen+          | 5        | 6.49%   |
| Skylake       | 4        | 5.19%   |
| K10           | 4        | 5.19%   |
| Westmere      | 3        | 3.9%    |
| Silvermont    | 3        | 3.9%    |
| Penryn        | 3        | 3.9%    |
| Zen           | 2        | 2.6%    |
| Steamroller   | 2        | 2.6%    |
| Icelake       | 2        | 2.6%    |
| Zen 3         | 1        | 1.3%    |
| Piledriver    | 1        | 1.3%    |
| Goldmont plus | 1        | 1.3%    |
| Core          | 1        | 1.3%    |
| Bulldozer     | 1        | 1.3%    |
| Bonnell       | 1        | 1.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 29       | 36.25%  |
| Nvidia | 28       | 35%     |
| Intel  | 23       | 28.75%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6        | 7.23%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 3        | 3.61%   |
| Intel HD Graphics 530                                                                    | 3        | 3.61%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3        | 3.61%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3        | 3.61%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 3        | 3.61%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 3        | 3.61%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 2        | 2.41%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2        | 2.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 2.41%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 2        | 2.41%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 2        | 2.41%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1        | 1.2%    |
| Nvidia TU104 [GeForce RTX 2080]                                                          | 1        | 1.2%    |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1        | 1.2%    |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 1        | 1.2%    |
| Nvidia TU104 [GeForce RTX 2060]                                                          | 1        | 1.2%    |
| Nvidia GP107GL [Quadro P1000]                                                            | 1        | 1.2%    |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1        | 1.2%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1        | 1.2%    |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 1.2%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 1.2%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 1        | 1.2%    |
| Nvidia GK104 [GeForce GTX 670]                                                           | 1        | 1.2%    |
| Nvidia GF119 [GeForce GT 625 OEM]                                                        | 1        | 1.2%    |
| Nvidia GF110 [GeForce GTX 580]                                                           | 1        | 1.2%    |
| Nvidia GF108 [GeForce GT 730]                                                            | 1        | 1.2%    |
| Nvidia GF108 [GeForce GT 630]                                                            | 1        | 1.2%    |
| Nvidia GF108 [GeForce GT 430]                                                            | 1        | 1.2%    |
| Nvidia GF100 [GeForce GTX 470]                                                           | 1        | 1.2%    |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                                        | 1        | 1.2%    |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                                           | 1        | 1.2%    |
| Nvidia G96C [GeForce 9500 GT]                                                            | 1        | 1.2%    |
| Nvidia G96C [GeForce 9400 GT]                                                            | 1        | 1.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1        | 1.2%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 1.2%    |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 1        | 1.2%    |
| Intel HD Graphics 630                                                                    | 1        | 1.2%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1        | 1.2%    |
| Intel Core Processor Integrated Graphics Controller                                      | 1        | 1.2%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1        | 1.2%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1        | 1.2%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1        | 1.2%    |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                                        | 1        | 1.2%    |
| AMD RV730 PRO [Radeon HD 4650]                                                           | 1        | 1.2%    |
| AMD RV630 XT [Radeon HD 2600 XT]                                                         | 1        | 1.2%    |
| AMD RV610 [Radeon HD 2400 PRO/XT]                                                        | 1        | 1.2%    |
| AMD RS880 [Radeon HD 4200]                                                               | 1        | 1.2%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1        | 1.2%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1        | 1.2%    |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 1        | 1.2%    |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 1        | 1.2%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 1        | 1.2%    |
| AMD Hawaii PRO [Radeon R9 290/390]                                                       | 1        | 1.2%    |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                              | 1        | 1.2%    |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                                         | 1        | 1.2%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1        | 1.2%    |
| AMD Cape Verde PRX [Radeon R9 255 OEM]                                                   | 1        | 1.2%    |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                                       | 1        | 1.2%    |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 1        | 1.2%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x Nvidia  | 28       | 35.9%   |
| 1 x AMD     | 26       | 33.33%  |
| 1 x Intel   | 21       | 26.92%  |
| 2 x AMD     | 2        | 2.56%   |
| Intel + AMD | 1        | 1.28%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 61       | 78.21%  |
| Proprietary | 17       | 21.79%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 22       | 27.85%  |
| 3.01-4.0   | 14       | 17.72%  |
| 1.01-2.0   | 14       | 17.72%  |
| 0.51-1.0   | 10       | 12.66%  |
| 7.01-8.0   | 7        | 8.86%   |
| 5.01-6.0   | 4        | 5.06%   |
| 0.01-0.5   | 4        | 5.06%   |
| 2.01-3.0   | 2        | 2.53%   |
| 8.01-16.0  | 2        | 2.53%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 12       | 13.64%  |
| Acer                 | 11       | 12.5%   |
| Hewlett-Packard      | 10       | 11.36%  |
| Goldstar             | 8        | 9.09%   |
| Philips              | 7        | 7.95%   |
| Dell                 | 6        | 6.82%   |
| BenQ                 | 5        | 5.68%   |
| AOC                  | 3        | 3.41%   |
| Ancor Communications | 3        | 3.41%   |
| Lenovo               | 2        | 2.27%   |
| AUS                  | 2        | 2.27%   |
| ___                  | 1        | 1.14%   |
| Vizio                | 1        | 1.14%   |
| ViewSonic            | 1        | 1.14%   |
| Vestel               | 1        | 1.14%   |
| Unknown              | 1        | 1.14%   |
| SPC                  | 1        | 1.14%   |
| MSI                  | 1        | 1.14%   |
| Mi                   | 1        | 1.14%   |
| LG Electronics       | 1        | 1.14%   |
| IOD                  | 1        | 1.14%   |
| Iiyama               | 1        | 1.14%   |
| HPN                  | 1        | 1.14%   |
| Fujitsu Siemens      | 1        | 1.14%   |
| Element              | 1        | 1.14%   |
| Eizo                 | 1        | 1.14%   |
| CHR                  | 1        | 1.14%   |
| CHD                  | 1        | 1.14%   |
| BOE                  | 1        | 1.14%   |
| Unknown              | 1        | 1.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch              | 2        | 2.13%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                      | 2        | 2.13%   |
| Goldstar 22EN33 GSM597C 1920x1080 480x270mm 21.7-inch                          | 2        | 2.13%   |
| BenQ EL2870U BNQ7949 3840x2160 621x341mm 27.9-inch                             | 2        | 2.13%   |
| ___ LCD TV ___9000 1360x768                                                    | 1        | 1.06%   |
| Vizio M322i-B1 VIZ1005 1920x1080 698x392mm 31.5-inch                           | 1        | 1.06%   |
| ViewSonic LCD Monitor VX2260WM 3840x1080                                       | 1        | 1.06%   |
| ViewSonic LCD Monitor VX2260WM                                                 | 1        | 1.06%   |
| Vestel LCD Monitor 49FHD_LCD_TV 1920x1080                                      | 1        | 1.06%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                             | 1        | 1.06%   |
| SPC LCD Monitor SPC1900 1440x900 368x207mm 16.6-inch                           | 1        | 1.06%   |
| Samsung Electronics T24D391 SAM0B72 1920x1080 521x293mm 23.5-inch              | 1        | 1.06%   |
| Samsung Electronics SA300/SA350 SAM078C 1600x900 443x249mm 20.0-inch           | 1        | 1.06%   |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch           | 1        | 1.06%   |
| Samsung Electronics S22C450 SAM09C7 1680x1050 473x291mm 21.9-inch              | 1        | 1.06%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 477x268mm 21.5-inch              | 1        | 1.06%   |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch           | 1        | 1.06%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1060x626mm 48.5-inch         | 1        | 1.06%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 700x390mm 31.5-inch           | 1        | 1.06%   |
| Samsung Electronics LCD Monitor SAM0530 1360x768                               | 1        | 1.06%   |
| Samsung Electronics LCD Monitor S22D300                                        | 1        | 1.06%   |
| Samsung Electronics LC32G5xT SAM7088 2560x1440 700x400mm 31.7-inch             | 1        | 1.06%   |
| Philips PHL BDM4350 PHL08FA 3840x2160 953x543mm 43.2-inch                      | 1        | 1.06%   |
| Philips PHL 345E2 PHLC237 3440x1440 800x335mm 34.1-inch                        | 1        | 1.06%   |
| Philips PHL 275E1 PHLC20C 2560x1440 597x336mm 27.0-inch                        | 1        | 1.06%   |
| Philips PHL 203V5 PHLC0CE 1600x900 434x236mm 19.4-inch                         | 1        | 1.06%   |
| Philips LCD Monitor PHL 276E8V 7680x2160                                       | 1        | 1.06%   |
| Philips LCD Monitor PHL 276E8V 3840x2160                                       | 1        | 1.06%   |
| Philips LCD Monitor PHL 276E8V                                                 | 1        | 1.06%   |
| Philips LCD Monitor 19B 1280x1024                                              | 1        | 1.06%   |
| Philips 190CW PHLC023 1440x900 408x255mm 18.9-inch                             | 1        | 1.06%   |
| MSI MAG341CQ MSI1462 3440x1440 800x330mm 34.1-inch                             | 1        | 1.06%   |
| Mi Monitor XMI2701 2560x1440 597x335mm 27.0-inch                               | 1        | 1.06%   |
| LG Electronics LCD Monitor 2D FHD LG TV 3840x1080                              | 1        | 1.06%   |
| Lenovo LT2252p Wide LEN0A0C 1680x1050 474x296mm 22.0-inch                      | 1        | 1.06%   |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                           | 1        | 1.06%   |
| IOD LCD-AD221F-T IOD1687 1920x1080 477x268mm 21.5-inch                         | 1        | 1.06%   |
| Iiyama PLB2403WS IVM5601 1920x1200 519x324mm 24.1-inch                         | 1        | 1.06%   |
| HPN LCD Monitor HP 27fw 1920x1080                                              | 1        | 1.06%   |
| Hewlett-Packard w2207 HWP26A9 1680x1050 473x296mm 22.0-inch                    | 1        | 1.06%   |
| Hewlett-Packard VH27 HPN3525 1920x1080 598x336mm 27.0-inch                     | 1        | 1.06%   |
| Hewlett-Packard V194 HWP3346 1366x768 410x230mm 18.5-inch                      | 1        | 1.06%   |
| Hewlett-Packard TouchSmart HP_touchsmart HWP4211 1920x1080 509x286mm 23.0-inch | 1        | 1.06%   |
| Hewlett-Packard OMEN by HP 32 HPN3378 2560x1440 708x399mm 32.0-inch            | 1        | 1.06%   |
| Hewlett-Packard LCD Monitor w17e 1440x900                                      | 1        | 1.06%   |
| Hewlett-Packard LA2205 HWP2848 1680x1050 473x296mm 22.0-inch                   | 1        | 1.06%   |
| Hewlett-Packard 27q HPN3564 2560x1440 597x336mm 27.0-inch                      | 1        | 1.06%   |
| Hewlett-Packard 24er HWP3320 1920x1080 527x296mm 23.8-inch                     | 1        | 1.06%   |
| Hewlett-Packard 2010 HWP2889 1600x900 443x250mm 20.0-inch                      | 1        | 1.06%   |
| Goldstar QHD GSM772A 2560x1440 697x392mm 31.5-inch                             | 1        | 1.06%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                         | 1        | 1.06%   |
| Goldstar 2D HD TV GSM59CA 1920x1080 521x293mm 23.5-inch                        | 1        | 1.06%   |
| Goldstar 2D HD TV GSM59C8 1366x768 509x286mm 23.0-inch                         | 1        | 1.06%   |
| Fujitsu Siemens L22W-6SA FUS0747 1680x1050 474x296mm 22.0-inch                 | 1        | 1.06%   |
| Element ELFW4017BF ELE3553 1920x1080 708x398mm 32.0-inch                       | 1        | 1.06%   |
| Eizo EV2455 ENC2533 1920x1200 519x324mm 24.1-inch                              | 1        | 1.06%   |
| Dell U2414H DELA0B2 1920x1080 527x296mm 23.8-inch                              | 1        | 1.06%   |
| Dell SE2416H DELD082 1920x1080 527x296mm 23.8-inch                             | 1        | 1.06%   |
| Dell SE2216H DELF071 1920x1080 476x268mm 21.5-inch                             | 1        | 1.06%   |
| Dell S2721DGF DEL41D9 2560x1440 597x336mm 27.0-inch                            | 1        | 1.06%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 33       | 37.08%  |
| 2560x1440 (QHD)    | 11       | 12.36%  |
| 3840x2160 (4K)     | 9        | 10.11%  |
| 1680x1050 (WSXGA+) | 8        | 8.99%   |
| 1366x768 (WXGA)    | 7        | 7.87%   |
| 1440x900 (WXGA+)   | 4        | 4.49%   |
| 1600x900 (HD+)     | 3        | 3.37%   |
| 1360x768           | 3        | 3.37%   |
| Unknown            | 3        | 3.37%   |
| 3840x1080          | 2        | 2.25%   |
| 3440x1440          | 2        | 2.25%   |
| 1920x1200 (WUXGA)  | 2        | 2.25%   |
| 7680x2160          | 1        | 1.12%   |
| 1280x1024 (SXGA)   | 1        | 1.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 15       | 17.65%  |
| 21      | 11       | 12.94%  |
| 24      | 10       | 11.76%  |
| 27      | 9        | 10.59%  |
| 23      | 8        | 9.41%   |
| 22      | 8        | 9.41%   |
| 31      | 4        | 4.71%   |
| 32      | 3        | 3.53%   |
| 18      | 3        | 3.53%   |
| 34      | 2        | 2.35%   |
| 20      | 2        | 2.35%   |
| 19      | 2        | 2.35%   |
| 15      | 2        | 2.35%   |
| 72      | 1        | 1.18%   |
| 55      | 1        | 1.18%   |
| 48      | 1        | 1.18%   |
| 43      | 1        | 1.18%   |
| 26      | 1        | 1.18%   |
| 16      | 1        | 1.18%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 25       | 30.12%  |
| 501-600     | 24       | 28.92%  |
| Unknown     | 15       | 18.07%  |
| 601-700     | 7        | 8.43%   |
| 701-800     | 5        | 6.02%   |
| 301-350     | 2        | 2.41%   |
| 1001-1500   | 2        | 2.41%   |
| 351-400     | 1        | 1.2%    |
| 1501-2000   | 1        | 1.2%    |
| 901-1000    | 1        | 1.2%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 49       | 62.82%  |
| 16/10   | 14       | 17.95%  |
| Unknown | 13       | 16.67%  |
| 21/9    | 2        | 2.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 28       | 33.73%  |
| Unknown        | 15       | 18.07%  |
| 351-500        | 9        | 10.84%  |
| 301-350        | 9        | 10.84%  |
| 151-200        | 7        | 8.43%   |
| 251-300        | 6        | 7.23%   |
| More than 1000 | 3        | 3.61%   |
| 141-150        | 2        | 2.41%   |
| 111-120        | 1        | 1.2%    |
| 101-110        | 1        | 1.2%    |
| 501-1000       | 1        | 1.2%    |
| 91-100         | 1        | 1.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 39       | 47.56%  |
| 101-120 | 20       | 24.39%  |
| Unknown | 15       | 18.29%  |
| 1-50    | 4        | 4.88%   |
| 121-160 | 4        | 4.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 63       | 80.77%  |
| 2     | 13       | 16.67%  |
| 3     | 2        | 2.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 54       | 46.96%  |
| Intel                    | 33       | 28.7%   |
| Qualcomm Atheros         | 4        | 3.48%   |
| Broadcom                 | 4        | 3.48%   |
| Samsung Electronics      | 3        | 2.61%   |
| Ralink Technology        | 3        | 2.61%   |
| TP-Link                  | 2        | 1.74%   |
| Xiaomi                   | 1        | 0.87%   |
| Ralink                   | 1        | 0.87%   |
| Nvidia                   | 1        | 0.87%   |
| Motorola PCS             | 1        | 0.87%   |
| Microsoft                | 1        | 0.87%   |
| Marvell Technology Group | 1        | 0.87%   |
| Linksys                  | 1        | 0.87%   |
| LG Electronics           | 1        | 0.87%   |
| Huawei Technologies      | 1        | 0.87%   |
| D-Link System            | 1        | 0.87%   |
| Broadcom Limited         | 1        | 0.87%   |
| AVM                      | 1        | 0.87%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 38       | 29.46%  |
| Realtek RTL8125 2.5GbE Controller                                 | 6        | 4.65%   |
| Intel Wi-Fi 6 AX200                                               | 6        | 4.65%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 3.1%    |
| Realtek 802.11ac NIC                                              | 4        | 3.1%    |
| Intel I211 Gigabit Network Connection                             | 4        | 3.1%    |
| Intel Ethernet Connection (2) I219-V                              | 4        | 3.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 3.1%    |
| Ralink MT7601U Wireless Adapter                                   | 3        | 2.33%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 2.33%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 1.55%   |
| Intel Ethernet Controller I225-V                                  | 2        | 1.55%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 1.55%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 2        | 1.55%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.78%   |
| TP-Link Archer T4U ver.3                                          | 1        | 0.78%   |
| TP-Link 802.11ac NIC                                              | 1        | 0.78%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 0.78%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.78%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.78%   |
| Realtek RTL8191SEvA Wireless LAN Controller                       | 1        | 0.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 0.78%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter           | 1        | 0.78%   |
| Realtek RTL8187 Wireless Adapter                                  | 1        | 0.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.78%   |
| Realtek 802.11n WLAN Adapter                                      | 1        | 0.78%   |
| Realtek 802.11n                                                   | 1        | 0.78%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1        | 0.78%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.78%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.78%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.78%   |
| Nvidia MCP61 Ethernet                                             | 1        | 0.78%   |
| Motorola PCS moto g(7) optimo maxx(XT1955DL)                      | 1        | 0.78%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1        | 0.78%   |
| Marvell Group 88w8335 [Libertas] 802.11b/g Wireless               | 1        | 0.78%   |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                         | 1        | 0.78%   |
| LG AN-WF100 802.11abgn Wireless Adapter [Broadcom BCM4323]        | 1        | 0.78%   |
| Intel Wireless-AC 9260                                            | 1        | 0.78%   |
| Intel Wireless 8260                                               | 1        | 0.78%   |
| Intel Wireless 3165                                               | 1        | 0.78%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1        | 0.78%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.78%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 0.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1        | 0.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1        | 0.78%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 0.78%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 0.78%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 0.78%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.78%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 1        | 0.78%   |
| Huawei SNE-LX3                                                    | 1        | 0.78%   |
| D-Link System DWA-110 Wireless G Adapter(rev.A1) [Ralink RT2571W] | 1        | 0.78%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                            | 1        | 0.78%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1        | 0.78%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 1        | 0.78%   |
| AVM Fritz!WLAN N v2 [Atheros AR9271]                              | 1        | 0.78%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 13       | 30.95%  |
| Realtek Semiconductor    | 12       | 28.57%  |
| Broadcom                 | 4        | 9.52%   |
| Ralink Technology        | 3        | 7.14%   |
| TP-Link                  | 2        | 4.76%   |
| Ralink                   | 1        | 2.38%   |
| Microsoft                | 1        | 2.38%   |
| Marvell Technology Group | 1        | 2.38%   |
| Linksys                  | 1        | 2.38%   |
| LG Electronics           | 1        | 2.38%   |
| D-Link System            | 1        | 2.38%   |
| Broadcom Limited         | 1        | 2.38%   |
| AVM                      | 1        | 2.38%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                               | 6        | 13.95%  |
| Realtek 802.11ac NIC                                              | 4        | 9.3%    |
| Ralink MT7601U Wireless Adapter                                   | 3        | 6.98%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 2        | 4.65%   |
| TP-Link Archer T4U ver.3                                          | 1        | 2.33%   |
| TP-Link 802.11ac NIC                                              | 1        | 2.33%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 2.33%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1        | 2.33%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1        | 2.33%   |
| Realtek RTL8191SEvA Wireless LAN Controller                       | 1        | 2.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 2.33%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter           | 1        | 2.33%   |
| Realtek RTL8187 Wireless Adapter                                  | 1        | 2.33%   |
| Realtek 802.11n WLAN Adapter                                      | 1        | 2.33%   |
| Realtek 802.11n                                                   | 1        | 2.33%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1        | 2.33%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1        | 2.33%   |
| Marvell Group 88w8335 [Libertas] 802.11b/g Wireless               | 1        | 2.33%   |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                         | 1        | 2.33%   |
| LG AN-WF100 802.11abgn Wireless Adapter [Broadcom BCM4323]        | 1        | 2.33%   |
| Intel Wireless-AC 9260                                            | 1        | 2.33%   |
| Intel Wireless 8260                                               | 1        | 2.33%   |
| Intel Wireless 3165                                               | 1        | 2.33%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1        | 2.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 2.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1        | 2.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1        | 2.33%   |
| D-Link System DWA-110 Wireless G Adapter(rev.A1) [Ralink RT2571W] | 1        | 2.33%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                            | 1        | 2.33%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1        | 2.33%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 1        | 2.33%   |
| AVM Fritz!WLAN N v2 [Atheros AR9271]                              | 1        | 2.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 49       | 56.98%  |
| Intel                 | 26       | 30.23%  |
| Qualcomm Atheros      | 4        | 4.65%   |
| Samsung Electronics   | 3        | 3.49%   |
| Xiaomi                | 1        | 1.16%   |
| Nvidia                | 1        | 1.16%   |
| Motorola PCS          | 1        | 1.16%   |
| Huawei Technologies   | 1        | 1.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 38       | 44.19%  |
| Realtek RTL8125 2.5GbE Controller                                 | 6        | 6.98%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 4.65%   |
| Intel I211 Gigabit Network Connection                             | 4        | 4.65%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 4.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 4.65%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 3.49%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 2.33%   |
| Intel Ethernet Controller I225-V                                  | 2        | 2.33%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 2.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.16%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 1.16%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 1.16%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 1.16%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 1.16%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 1.16%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 1.16%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.16%   |
| Motorola PCS moto g(7) optimo maxx(XT1955DL)                      | 1        | 1.16%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.16%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.16%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 1.16%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.16%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 1.16%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 1.16%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 1        | 1.16%   |
| Huawei SNE-LX3                                                    | 1        | 1.16%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 77       | 66.38%  |
| WiFi     | 39       | 33.62%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 73       | 72.28%  |
| WiFi     | 28       | 27.72%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 50       | 64.94%  |
| 2     | 22       | 28.57%  |
| 3     | 4        | 5.19%   |
| 0     | 1        | 1.3%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 58       | 73.42%  |
| Yes  | 21       | 26.58%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 11       | 40.74%  |
| Cambridge Silicon Radio | 8        | 29.63%  |
| Realtek Semiconductor   | 2        | 7.41%   |
| Apple                   | 2        | 7.41%   |
| Qcom                    | 1        | 3.7%    |
| IMC Networks            | 1        | 3.7%    |
| Broadcom                | 1        | 3.7%    |
| ASUSTek Computer        | 1        | 3.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8        | 29.63%  |
| Intel AX200 Bluetooth                               | 5        | 18.52%  |
| Realtek Bluetooth Radio                             | 2        | 7.41%   |
| Intel Bluetooth wireless interface                  | 2        | 7.41%   |
| Qcom Bluetooth USB                                  | 1        | 3.7%    |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 3.7%    |
| Intel Bluetooth Device                              | 1        | 3.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 3.7%    |
| Intel AX201 Bluetooth                               | 1        | 3.7%    |
| IMC Networks BCM20702A0                             | 1        | 3.7%    |
| Broadcom HP Portable Bumble Bee                     | 1        | 3.7%    |
| ASUS BCM20702A0                                     | 1        | 3.7%    |
| Apple Bluetooth USB Host Controller                 | 1        | 3.7%    |
| Apple Bluetooth HCI                                 | 1        | 3.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 48       | 37.8%   |
| AMD                    | 35       | 27.56%  |
| Nvidia                 | 28       | 22.05%  |
| C-Media Electronics    | 5        | 3.94%   |
| Creative Labs          | 4        | 3.15%   |
| Logitech               | 2        | 1.57%   |
| Razer USA              | 1        | 0.79%   |
| GN Netcom              | 1        | 0.79%   |
| Generalplus Technology | 1        | 0.79%   |
| Focusrite-Novation     | 1        | 0.79%   |
| Corsair                | 1        | 0.79%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 11       | 7.69%   |
| AMD Starship/Matisse HD Audio Controller                                          | 7        | 4.9%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 7        | 4.9%    |
| Intel Cannon Lake PCH cAVS                                                        | 6        | 4.2%    |
| Nvidia GP106 High Definition Audio Controller                                     | 5        | 3.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 5        | 3.5%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 5        | 3.5%    |
| Nvidia TU104 HD Audio Controller                                                  | 4        | 2.8%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 4        | 2.8%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 4        | 2.8%    |
| Nvidia GF108 High Definition Audio Controller                                     | 3        | 2.1%    |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 3        | 2.1%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 3        | 2.1%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 3        | 2.1%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 3        | 2.1%    |
| Intel 200 Series PCH HD Audio                                                     | 3        | 2.1%    |
| AMD SBx00 Azalia (Intel HDA)                                                      | 3        | 2.1%    |
| AMD FCH Azalia Controller                                                         | 3        | 2.1%    |
| AMD Family 17h/19h HD Audio Controller                                            | 3        | 2.1%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 3        | 2.1%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3        | 2.1%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 2        | 1.4%    |
| Nvidia GP107GL High Definition Audio Controller                                   | 2        | 1.4%    |
| Intel Tiger Lake-H HD Audio Controller                                            | 2        | 1.4%    |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 2        | 1.4%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 2        | 1.4%    |
| AMD Kaveri HDMI/DP Audio Controller                                               | 2        | 1.4%    |
| Razer USA RC30-026902, Gaming Headset [Nari Essential, Wireless, Receiver]        | 1        | 0.7%    |
| Nvidia TU116 High Definition Audio Controller                                     | 1        | 0.7%    |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 1        | 0.7%    |
| Nvidia MCP61 High Definition Audio                                                | 1        | 0.7%    |
| Nvidia GP102 HDMI Audio Controller                                                | 1        | 0.7%    |
| Nvidia GM204 High Definition Audio Controller                                     | 1        | 0.7%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 1        | 0.7%    |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 1        | 0.7%    |
| Nvidia GK104 HDMI Audio Controller                                                | 1        | 0.7%    |
| Nvidia GF119 HDMI Audio Controller                                                | 1        | 0.7%    |
| Nvidia GF110 High Definition Audio Controller                                     | 1        | 0.7%    |
| Nvidia GF100 High Definition Audio Controller                                     | 1        | 0.7%    |
| Nvidia GA104 High Definition Audio Controller                                     | 1        | 0.7%    |
| Nvidia GA102 High Definition Audio Controller                                     | 1        | 0.7%    |
| Logitech Headset H340                                                             | 1        | 0.7%    |
| Logitech G733 Gaming Headset                                                      | 1        | 0.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 1        | 0.7%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 1        | 0.7%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 1        | 0.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 1        | 0.7%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 1        | 0.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 1        | 0.7%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 1        | 0.7%    |
| Intel 631xESB/632xESB High Definition Audio Controller                            | 1        | 0.7%    |
| GN Netcom Jabra SPEAK 510 USB                                                     | 1        | 0.7%    |
| Generalplus Technology USB Audio Device                                           | 1        | 0.7%    |
| Focusrite-Novation Focusrite Scarlett 2i2 2nd Gen                                 | 1        | 0.7%    |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                     | 1        | 0.7%    |
| Creative Labs EMU20k2 [Sound Blaster X-Fi Titanium Series]                        | 1        | 0.7%    |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                | 1        | 0.7%    |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                        | 1        | 0.7%    |
| Corsair VOID PRO Wireless Gaming Headset                                          | 1        | 0.7%    |
| C-Media Electronics KLIM Mantis Audio 7.1                                         | 1        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 4        | 26.67%  |
| SK Hynix            | 3        | 20%     |
| Kingston            | 2        | 13.33%  |
| Corsair             | 2        | 13.33%  |
| Unknown             | 1        | 6.67%   |
| Ramaxel Technology  | 1        | 6.67%   |
| PNY                 | 1        | 6.67%   |
| Patriot             | 1        | 6.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unknown RAM Module 8192MB DIMM DDR3 1066MT/s              | 1        | 6.67%   |
| SK Hynix RAM HMT42GR7BMR4C 16384MB DIMM DDR3 1066MT/s     | 1        | 6.67%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s   | 1        | 6.67%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 1        | 6.67%   |
| Samsung RAM Module 8192MB DIMM DDR4 2666MT/s              | 1        | 6.67%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 1        | 6.67%   |
| Samsung RAM M393B2K70DM0 16384MB DIMM DDR3 1066MT/s       | 1        | 6.67%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s       | 1        | 6.67%   |
| Ramaxel RAM RMUA5090KB78HAF2133 8192MB DIMM DDR4 2133MT/s | 1        | 6.67%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8192MB DIMM DDR4 3200MT/s    | 1        | 6.67%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s        | 1        | 6.67%   |
| Kingston RAM 9905625-030.A00G 8192MB DIMM DDR4 2133MT/s   | 1        | 6.67%   |
| Kingston RAM 9905471-015.A00LF 4096MB DIMM DDR3 1333MT/s  | 1        | 6.67%   |
| Corsair RAM CMX8GX3M1A1600C11 8192MB DIMM DDR3 1600MT/s   | 1        | 6.67%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s      | 1        | 6.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR3 | 6        | 54.55%  |
| DDR4 | 5        | 45.45%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 10       | 90.91%  |
| SODIMM | 1        | 9.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 6        | 54.55%  |
| 4096  | 3        | 27.27%  |
| 32768 | 1        | 9.09%   |
| 16384 | 1        | 9.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 2        | 16.67%  |
| 1600  | 2        | 16.67%  |
| 1066  | 2        | 16.67%  |
| 2800  | 1        | 8.33%   |
| 2666  | 1        | 8.33%   |
| 2200  | 1        | 8.33%   |
| 2133  | 1        | 8.33%   |
| 1800  | 1        | 8.33%   |
| 1333  | 1        | 8.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Dymo-CoStar | 1        | 50%     |
| Canon       | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| Dymo-CoStar LabelWriter 450 | 1        | 50%     |
| Canon PIXMA MG3600 Series   | 1        | 50%     |

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


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Logitech            | 3        | 30%     |
| Microsoft           | 2        | 20%     |
| Apple               | 2        | 20%     |
| Microdia            | 1        | 10%     |
| Chicony Electronics | 1        | 10%     |
| ANYKA               | 1        | 10%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Apple iPhone 5/5C/5S/6/SE             | 2        | 20%     |
| Microsoft LifeCam VX-800              | 1        | 10%     |
| Microsoft LifeCam HD-3000             | 1        | 10%     |
| Microdia USB 2.0 Camera               | 1        | 10%     |
| Logitech QuickCam Communicate Deluxe  | 1        | 10%     |
| Logitech Logi 4K Stream Edition       | 1        | 10%     |
| Logitech B525 HD Webcam               | 1        | 10%     |
| Chicony HP High Definition 1MP Webcam | 1        | 10%     |
| ANYKA V380 FHD Camera                 | 1        | 10%     |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Chicony Electronics | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Chicony Electronics HP Skylab USB Smartcard Keyboard | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 69       | 88.46%  |
| 1     | 7        | 8.97%   |
| 4     | 1        | 1.28%   |
| 2     | 1        | 1.28%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Net/wireless          | 8        | 66.67%  |
| Storage/ide           | 1        | 8.33%   |
| Sound                 | 1        | 8.33%   |
| Multimedia controller | 1        | 8.33%   |
| Bluetooth             | 1        | 8.33%   |

