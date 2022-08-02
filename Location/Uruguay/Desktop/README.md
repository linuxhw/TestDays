Linux in Uruguay - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Uruguay.

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

Total: 97

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| MACHINIST  | X79 (INTEL Xeon E5/Corei... | [e83fe522d7](https://linux-hardware.org/?probe=e83fe522d7) | Jul 31, 2022 |
| Gigabyte   | Z170X-Gaming 3              | [a3c2fdccfc](https://linux-hardware.org/?probe=a3c2fdccfc) | Jul 27, 2022 |
| ASRock     | FM2A58M-VG3+ R2.0           | [04affeedf7](https://linux-hardware.org/?probe=04affeedf7) | Jul 18, 2022 |
| HP         | 1632                        | [d2582aff1d](https://linux-hardware.org/?probe=d2582aff1d) | Jul 12, 2022 |
| Gigabyte   | H410M H V3                  | [0d26f198ff](https://linux-hardware.org/?probe=0d26f198ff) | Jul 06, 2022 |
| MSI        | MPG X570 GAMING PLUS        | [5fa355f7ec](https://linux-hardware.org/?probe=5fa355f7ec) | Jun 26, 2022 |
| Gigabyte   | B450 GAMING X               | [34e884bb50](https://linux-hardware.org/?probe=34e884bb50) | Jun 08, 2022 |
| Gigabyte   | Z390 AORUS ELITE-CF         | [95ac26b654](https://linux-hardware.org/?probe=95ac26b654) | May 19, 2022 |
| Foxconn    | G31MX Series                | [911987151a](https://linux-hardware.org/?probe=911987151a) | Mar 23, 2022 |
| Foxconn    | G31MX Series                | [7d9cc6ac07](https://linux-hardware.org/?probe=7d9cc6ac07) | Mar 22, 2022 |
| Gigabyte   | Z370 AORUS Gaming 7         | [9699b8889c](https://linux-hardware.org/?probe=9699b8889c) | Feb 27, 2022 |
| ASUSTek    | TUF Gaming B460M-PLUS       | [37231251ed](https://linux-hardware.org/?probe=37231251ed) | Feb 21, 2022 |
| ASRock     | FM2A55M-HD+                 | [52ca8c0d7c](https://linux-hardware.org/?probe=52ca8c0d7c) | Feb 13, 2022 |
| HP         | 3047h                       | [ee6260c5f4](https://linux-hardware.org/?probe=ee6260c5f4) | Feb 10, 2022 |
| Gigabyte   | GA-970A-D3                  | [0fe418c7b1](https://linux-hardware.org/?probe=0fe418c7b1) | Jan 07, 2022 |
| HP         | 0AA8h                       | [9abf55a71f](https://linux-hardware.org/?probe=9abf55a71f) | Jan 05, 2022 |
| HP         | 0AA8h                       | [44c9ba4231](https://linux-hardware.org/?probe=44c9ba4231) | Jan 03, 2022 |
| Biostar    | Z490A-SILVER                | [b5e7622be0](https://linux-hardware.org/?probe=b5e7622be0) | Jan 02, 2022 |
| Dell       | 06D7TR A00                  | [90f509fc24](https://linux-hardware.org/?probe=90f509fc24) | Dec 09, 2021 |
| Gigabyte   | H81M-DS2                    | [44b341f68d](https://linux-hardware.org/?probe=44b341f68d) | Nov 10, 2021 |
| ASRock     | N68-S                       | [eac798f714](https://linux-hardware.org/?probe=eac798f714) | Nov 01, 2021 |
| Gigabyte   | X570 GAMING X               | [174875a3d4](https://linux-hardware.org/?probe=174875a3d4) | Oct 25, 2021 |
| MSI        | X570-A PRO                  | [357ea9ab5d](https://linux-hardware.org/?probe=357ea9ab5d) | Oct 22, 2021 |
| ASRock     | B450M Steel Legend          | [fea193c839](https://linux-hardware.org/?probe=fea193c839) | Sep 10, 2021 |
| Gigabyte   | Z390 AORUS ELITE-CF         | [dbeb8785e6](https://linux-hardware.org/?probe=dbeb8785e6) | Sep 01, 2021 |
| ASRock     | FM2A55M-VG3+                | [c2e1837665](https://linux-hardware.org/?probe=c2e1837665) | Aug 24, 2021 |
| ASUSTek    | M5A99X EVO R2.0             | [b6c401b55e](https://linux-hardware.org/?probe=b6c401b55e) | Jul 15, 2021 |
| ASUSTek    | TUF Gaming B550-PLUS        | [38ee95b416](https://linux-hardware.org/?probe=38ee95b416) | Jun 02, 2021 |
| ASUSTek    | PRIME B450M-A II            | [ab4b1b7a15](https://linux-hardware.org/?probe=ab4b1b7a15) | May 31, 2021 |
| ASRock     | FM2A55M-VG3+                | [d9065ac8d1](https://linux-hardware.org/?probe=d9065ac8d1) | May 30, 2021 |
| ASRock     | A320M-HDV R3.0              | [0ed78505e8](https://linux-hardware.org/?probe=0ed78505e8) | May 19, 2021 |
| ASRock     | FM2A55M-VG3+                | [41e6c088d2](https://linux-hardware.org/?probe=41e6c088d2) | May 16, 2021 |
| ASRock     | FM2A55M-VG3+                | [ada1c4a259](https://linux-hardware.org/?probe=ada1c4a259) | May 12, 2021 |
| ASRock     | N68-VS3 FX                  | [bcee870f79](https://linux-hardware.org/?probe=bcee870f79) | Apr 24, 2021 |
| ASRock     | N68-VS3 FX                  | [b92a431094](https://linux-hardware.org/?probe=b92a431094) | Apr 24, 2021 |
| ASUSTek    | M5A78L-M/USB3               | [7d28bb0ba2](https://linux-hardware.org/?probe=7d28bb0ba2) | Apr 23, 2021 |
| Gigabyte   | Z390 AORUS ELITE-CF         | [5042e6d421](https://linux-hardware.org/?probe=5042e6d421) | Apr 20, 2021 |
| ASUSTek    | P8H77-V                     | [9b0d9c1623](https://linux-hardware.org/?probe=9b0d9c1623) | Apr 05, 2021 |
| Supermicro | P4DMS                       | [34867ad122](https://linux-hardware.org/?probe=34867ad122) | Mar 22, 2021 |
| Supermicro | P4DMS                       | [9de21bc6ec](https://linux-hardware.org/?probe=9de21bc6ec) | Mar 14, 2021 |
| Lenovo     | MAHOBAY NOK                 | [901fd74eaa](https://linux-hardware.org/?probe=901fd74eaa) | Feb 20, 2021 |
| ASUSTek    | PRIME B450M-A II            | [7f1fc20897](https://linux-hardware.org/?probe=7f1fc20897) | Feb 19, 2021 |
| ASUSTek    | PRIME B450M-A II            | [9527a6802e](https://linux-hardware.org/?probe=9527a6802e) | Feb 19, 2021 |
| Gigabyte   | H81M-DS2                    | [9473725930](https://linux-hardware.org/?probe=9473725930) | Feb 15, 2021 |
| Dell       | 0C522T A03                  | [0b52890aaf](https://linux-hardware.org/?probe=0b52890aaf) | Jan 29, 2021 |
| Dell       | 0C522T A03                  | [3a777180a1](https://linux-hardware.org/?probe=3a777180a1) | Jan 29, 2021 |
| Intel      | H61M-DS2                    | [930418d2da](https://linux-hardware.org/?probe=930418d2da) | Jan 23, 2021 |
| Gigabyte   | H81M-DS2                    | [4b7df9598e](https://linux-hardware.org/?probe=4b7df9598e) | Jan 20, 2021 |
| Intel      | H61M-DS2                    | [53bde98202](https://linux-hardware.org/?probe=53bde98202) | Jan 09, 2021 |
| MSI        | A55M-P33                    | [43267cc6f4](https://linux-hardware.org/?probe=43267cc6f4) | Dec 16, 2020 |
| ASRock     | H310CM-HDV                  | [729161e56a](https://linux-hardware.org/?probe=729161e56a) | Dec 08, 2020 |
| ASRock     | H310CM-HDV                  | [37f7b460d4](https://linux-hardware.org/?probe=37f7b460d4) | Dec 08, 2020 |
| ASRock     | A320M-HDV                   | [912852805f](https://linux-hardware.org/?probe=912852805f) | Oct 22, 2020 |
| Dell       | 0C27VV A00                  | [fd9547e219](https://linux-hardware.org/?probe=fd9547e219) | Oct 01, 2020 |
| Gigabyte   | H310M A-CF                  | [ff30e910c4](https://linux-hardware.org/?probe=ff30e910c4) | Aug 12, 2020 |
| Intel      | DP35DP AAD81073-208         | [0009968f3b](https://linux-hardware.org/?probe=0009968f3b) | Aug 05, 2020 |
| Gigabyte   | GA-78LMT-S2                 | [71c07410ee](https://linux-hardware.org/?probe=71c07410ee) | Jul 25, 2020 |
| ASUSTek    | PRIME B450-PLUS             | [d4c35c226e](https://linux-hardware.org/?probe=d4c35c226e) | Jul 01, 2020 |
| ASUSTek    | PRIME B450-PLUS             | [178da315d2](https://linux-hardware.org/?probe=178da315d2) | Jul 01, 2020 |
| Fujitsu    | D3064-A1 S26361-D3064-A1    | [6a4b069ed8](https://linux-hardware.org/?probe=6a4b069ed8) | Jun 30, 2020 |
| MSI        | H81M-E33                    | [9f2577531a](https://linux-hardware.org/?probe=9f2577531a) | Jun 10, 2020 |
| MSI        | B85-G43 GAMING              | [0a5437ade3](https://linux-hardware.org/?probe=0a5437ade3) | May 22, 2020 |
| ASUSTek    | P8H67-M LX                  | [0ba192cc01](https://linux-hardware.org/?probe=0ba192cc01) | May 22, 2020 |
| ASUSTek    | Rampage IV EXTREME          | [627fed813d](https://linux-hardware.org/?probe=627fed813d) | May 18, 2020 |
| Gigabyte   | H61M-S1                     | [493ce118d1](https://linux-hardware.org/?probe=493ce118d1) | May 16, 2020 |
| ASUSTek    | K8V-X SE                    | [154224ff78](https://linux-hardware.org/?probe=154224ff78) | May 16, 2020 |
| ASUSTek    | K8V-X SE                    | [173008c9ff](https://linux-hardware.org/?probe=173008c9ff) | May 16, 2020 |
| Gigabyte   | H61M-S1                     | [98a86c1397](https://linux-hardware.org/?probe=98a86c1397) | May 15, 2020 |
| ASUSTek    | Rampage IV EXTREME          | [1beb748dc0](https://linux-hardware.org/?probe=1beb748dc0) | May 12, 2020 |
| HP         | 090Ch                       | [c471684991](https://linux-hardware.org/?probe=c471684991) | May 04, 2020 |
| HP         | 090Ch                       | [6f88fbc1ad](https://linux-hardware.org/?probe=6f88fbc1ad) | May 04, 2020 |
| MSI        | B85-G43 GAMING              | [1532d55ba0](https://linux-hardware.org/?probe=1532d55ba0) | May 01, 2020 |
| MSI        | B85-G43 GAMING              | [c931341a8c](https://linux-hardware.org/?probe=c931341a8c) | May 01, 2020 |
| ASRock     | G41M-VS3                    | [e52c07ce77](https://linux-hardware.org/?probe=e52c07ce77) | May 01, 2020 |
| Gateway    | DX4375                      | [1470b063f3](https://linux-hardware.org/?probe=1470b063f3) | Apr 28, 2020 |
| ECS        | H310H5-M2                   | [b1aaebf57b](https://linux-hardware.org/?probe=b1aaebf57b) | Apr 19, 2020 |
| ASRock     | ALiveNF6P-VSTA              | [3036b319ab](https://linux-hardware.org/?probe=3036b319ab) | Apr 16, 2020 |
| ASRock     | ALiveNF6P-VSTA              | [ebd210c2af](https://linux-hardware.org/?probe=ebd210c2af) | Apr 16, 2020 |
| MSI        | G31M2                       | [7534350893](https://linux-hardware.org/?probe=7534350893) | Mar 28, 2020 |
| HP         | 1497                        | [973b170ac6](https://linux-hardware.org/?probe=973b170ac6) | Mar 23, 2020 |
| HP         | 1497                        | [26d8104c5e](https://linux-hardware.org/?probe=26d8104c5e) | Mar 02, 2020 |
| MSI        | A68HM-E33 V2                | [743f3ff81c](https://linux-hardware.org/?probe=743f3ff81c) | Dec 22, 2019 |
| MSI        | A68HM-E33 V2                | [1d3a9ef0d2](https://linux-hardware.org/?probe=1d3a9ef0d2) | Dec 22, 2019 |
| MSI        | A68HM-E33 V2                | [806c1e6d78](https://linux-hardware.org/?probe=806c1e6d78) | Dec 22, 2019 |
| Gigabyte   | Z390 AORUS ELITE-CF         | [c28821415f](https://linux-hardware.org/?probe=c28821415f) | Nov 15, 2019 |
| Gigabyte   | H81M-DS2                    | [273463747b](https://linux-hardware.org/?probe=273463747b) | Oct 29, 2019 |
| Gigabyte   | H81M-DS2                    | [dfda14135d](https://linux-hardware.org/?probe=dfda14135d) | Oct 28, 2019 |
| Gigabyte   | H81M-DS2                    | [3418011c79](https://linux-hardware.org/?probe=3418011c79) | Oct 27, 2019 |
| Gigabyte   | H81M-DS2                    | [cb622d3902](https://linux-hardware.org/?probe=cb622d3902) | Oct 27, 2019 |
| ASUSTek    | M5A87                       | [cead36d312](https://linux-hardware.org/?probe=cead36d312) | May 18, 2019 |
| ASUSTek    | M5A87                       | [6dfdec0635](https://linux-hardware.org/?probe=6dfdec0635) | May 18, 2019 |
| HP         | 1998                        | [0ae1b2ac01](https://linux-hardware.org/?probe=0ae1b2ac01) | May 13, 2019 |
| Gigabyte   | AX370-Gaming 5              | [547801f07c](https://linux-hardware.org/?probe=547801f07c) | Apr 15, 2019 |
| Gigabyte   | AX370-Gaming 5              | [859c76fdf7](https://linux-hardware.org/?probe=859c76fdf7) | Mar 17, 2019 |
| ASRock     | ALiveNF6P-VSTA              | [4684e2d239](https://linux-hardware.org/?probe=4684e2d239) | Dec 04, 2018 |
| ASRock     | ALiveNF6P-VSTA              | [a26c805e14](https://linux-hardware.org/?probe=a26c805e14) | Dec 04, 2018 |
| MSI        | G41M-P26                    | [59c7d54670](https://linux-hardware.org/?probe=59c7d54670) | Nov 10, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Ubuntu 20.04      | 11       | 16.67%  |
| Ubuntu 18.04      | 6        | 9.09%   |
| OpenMandriva 4.3  | 6        | 9.09%   |
| Xubuntu 20.04     | 3        | 4.55%   |
| Linux Mint 19.3   | 3        | 4.55%   |
| Ubuntu 18.10      | 2        | 3.03%   |
| ROSA R11.1        | 2        | 3.03%   |
| Pop!_OS 20.04     | 2        | 3.03%   |
| Linux Mint 20     | 2        | 3.03%   |
| BlackPanther 18.1 | 2        | 3.03%   |
| Arch              | 2        | 3.03%   |
| Zorin 15          | 1        | 1.52%   |
| Xubuntu 21.04     | 1        | 1.52%   |
| Xubuntu 18.04     | 1        | 1.52%   |
| Ubuntu 21.10      | 1        | 1.52%   |
| Ubuntu 19.04      | 1        | 1.52%   |
| Pop!_OS 22.04     | 1        | 1.52%   |
| Pop!_OS 21.10     | 1        | 1.52%   |
| OpenMandriva 4.50 | 1        | 1.52%   |
| OpenMandriva 4.2  | 1        | 1.52%   |
| Lubuntu 18.04     | 1        | 1.52%   |
| Lubuntu 16.10     | 1        | 1.52%   |
| LMDE 4            | 1        | 1.52%   |
| LinuxFX 11.1      | 1        | 1.52%   |
| Linux Mint 20.2   | 1        | 1.52%   |
| Linux Mint 19.1   | 1        | 1.52%   |
| KDE neon 20.04    | 1        | 1.52%   |
| KDE neon 18.04    | 1        | 1.52%   |
| Fedora 36         | 1        | 1.52%   |
| Fedora 35         | 1        | 1.52%   |
| Fedora 34         | 1        | 1.52%   |
| Fedora 33         | 1        | 1.52%   |
| Endless 3.8.6     | 1        | 1.52%   |
| Debian Testing    | 1        | 1.52%   |
| ArcoLinux Rolling | 1        | 1.52%   |
| Arch Rolling      | 1        | 1.52%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 20       | 30.77%  |
| OpenMandriva | 8        | 12.31%  |
| Linux Mint   | 7        | 10.77%  |
| Xubuntu      | 5        | 7.69%   |
| Pop!_OS      | 4        | 6.15%   |
| Fedora       | 4        | 6.15%   |
| Arch         | 3        | 4.62%   |
| ROSA         | 2        | 3.08%   |
| Lubuntu      | 2        | 3.08%   |
| KDE neon     | 2        | 3.08%   |
| BlackPanther | 2        | 3.08%   |
| Zorin        | 1        | 1.54%   |
| LMDE         | 1        | 1.54%   |
| LinuxFX      | 1        | 1.54%   |
| Endless      | 1        | 1.54%   |
| Debian       | 1        | 1.54%   |
| ArcoLinux    | 1        | 1.54%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Desktops | Percent |
|--------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003        | 6        | 8.45%   |
| 5.4.0-42-generic               | 4        | 5.63%   |
| 5.3.0-46-generic               | 3        | 4.23%   |
| 5.4.83-generic-2rosa-x86_64    | 2        | 2.82%   |
| 5.4.0-65-generic               | 2        | 2.82%   |
| 5.11.0-38-generic              | 2        | 2.82%   |
| 5.0.0-32-generic               | 2        | 2.82%   |
| 4.18.16-desktop-1bP            | 2        | 2.82%   |
| 5.6.0-2-amd64                  | 1        | 1.41%   |
| 5.4.0-92-lowlatency            | 1        | 1.41%   |
| 5.4.0-91-generic               | 1        | 1.41%   |
| 5.4.0-72-generic               | 1        | 1.41%   |
| 5.4.0-62-generic               | 1        | 1.41%   |
| 5.4.0-56-generic               | 1        | 1.41%   |
| 5.4.0-52-generic               | 1        | 1.41%   |
| 5.4.0-39-generic               | 1        | 1.41%   |
| 5.4.0-33-generic               | 1        | 1.41%   |
| 5.4.0-29-generic               | 1        | 1.41%   |
| 5.4.0-26-generic               | 1        | 1.41%   |
| 5.4.0-0.bpo.4-amd64            | 1        | 1.41%   |
| 5.3.0-51-generic               | 1        | 1.41%   |
| 5.3.0-40-generic               | 1        | 1.41%   |
| 5.18.12-arch1-1                | 1        | 1.41%   |
| 5.18.10-76051810-generic       | 1        | 1.41%   |
| 5.17.5-300.fc36.x86_64         | 1        | 1.41%   |
| 5.17.12-200.fc35.x86_64        | 1        | 1.41%   |
| 5.15.23-76051523-generic       | 1        | 1.41%   |
| 5.13.12-200.fc34.x86_64        | 1        | 1.41%   |
| 5.13.0-44-generic              | 1        | 1.41%   |
| 5.13.0-35-generic              | 1        | 1.41%   |
| 5.13.0-22-generic              | 1        | 1.41%   |
| 5.12.8-arch1-1                 | 1        | 1.41%   |
| 5.12.4-desktop-1omv4050        | 1        | 1.41%   |
| 5.12.3-arch1-1                 | 1        | 1.41%   |
| 5.12.15-arch1-1                | 1        | 1.41%   |
| 5.11.18-300.fc34.x86_64        | 1        | 1.41%   |
| 5.11.15-200.fc33.x86_64        | 1        | 1.41%   |
| 5.11.0-7633-generic            | 1        | 1.41%   |
| 5.11.0-7612-generic            | 1        | 1.41%   |
| 5.11.0-43-lowlatency           | 1        | 1.41%   |
| 5.11.0-40-generic              | 1        | 1.41%   |
| 5.10.16-arch1-1                | 1        | 1.41%   |
| 5.10.14-desktop-1omv4002       | 1        | 1.41%   |
| 5.0.0-37-generic               | 1        | 1.41%   |
| 4.8.0-27-generic               | 1        | 1.41%   |
| 4.18.0-20-generic              | 1        | 1.41%   |
| 4.18.0-17-generic              | 1        | 1.41%   |
| 4.18.0-16-generic              | 1        | 1.41%   |
| 4.18.0-11-generic              | 1        | 1.41%   |
| 4.15.0-desktop-45.1rosa-x86_64 | 1        | 1.41%   |
| 4.15.0-99-generic              | 1        | 1.41%   |
| 4.15.0-66-generic              | 1        | 1.41%   |
| 4.15.0-48-generic              | 1        | 1.41%   |
| 4.15.0-42-generic              | 1        | 1.41%   |
| 4.15.0-29-generic              | 1        | 1.41%   |
| 4.15.0-136-generic             | 1        | 1.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 16       | 23.19%  |
| 4.15.0  | 7        | 10.14%  |
| 5.16.7  | 6        | 8.7%    |
| 5.11.0  | 6        | 8.7%    |
| 5.3.0   | 5        | 7.25%   |
| 5.13.0  | 3        | 4.35%   |
| 5.0.0   | 3        | 4.35%   |
| 4.18.0  | 3        | 4.35%   |
| 5.4.83  | 2        | 2.9%    |
| 4.18.16 | 2        | 2.9%    |
| 5.6.0   | 1        | 1.45%   |
| 5.18.12 | 1        | 1.45%   |
| 5.18.10 | 1        | 1.45%   |
| 5.17.5  | 1        | 1.45%   |
| 5.17.12 | 1        | 1.45%   |
| 5.15.23 | 1        | 1.45%   |
| 5.13.12 | 1        | 1.45%   |
| 5.12.8  | 1        | 1.45%   |
| 5.12.4  | 1        | 1.45%   |
| 5.12.3  | 1        | 1.45%   |
| 5.12.15 | 1        | 1.45%   |
| 5.11.18 | 1        | 1.45%   |
| 5.11.15 | 1        | 1.45%   |
| 5.10.16 | 1        | 1.45%   |
| 5.10.14 | 1        | 1.45%   |
| 4.8.0   | 1        | 1.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 18       | 26.09%  |
| 5.11    | 8        | 11.59%  |
| 4.15    | 7        | 10.14%  |
| 5.16    | 6        | 8.7%    |
| 5.3     | 5        | 7.25%   |
| 4.18    | 5        | 7.25%   |
| 5.13    | 4        | 5.8%    |
| 5.12    | 4        | 5.8%    |
| 5.0     | 3        | 4.35%   |
| 5.18    | 2        | 2.9%    |
| 5.17    | 2        | 2.9%    |
| 5.10    | 2        | 2.9%    |
| 5.6     | 1        | 1.45%   |
| 5.15    | 1        | 1.45%   |
| 4.8     | 1        | 1.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 60       | 95.24%  |
| i686   | 3        | 4.76%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 22       | 33.33%  |
| KDE5       | 16       | 24.24%  |
| Unknown    | 7        | 10.61%  |
| X-Cinnamon | 6        | 9.09%   |
| XFCE       | 5        | 7.58%   |
| LXDE       | 3        | 4.55%   |
| MATE       | 2        | 3.03%   |
| KDE4       | 2        | 3.03%   |
| KDE        | 2        | 3.03%   |
| Cinnamon   | 1        | 1.52%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 58       | 89.23%  |
| Unknown | 4        | 6.15%   |
| Wayland | 3        | 4.62%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 35       | 54.69%  |
| SDDM    | 13       | 20.31%  |
| LightDM | 7        | 10.94%  |
| GDM     | 5        | 7.81%   |
| KDM     | 2        | 3.13%   |
| TDM     | 1        | 1.56%   |
| GDM3    | 1        | 1.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| es_UY   | 30       | 45.45%  |
| en_US   | 14       | 21.21%  |
| es_ES   | 9        | 13.64%  |
| Unknown | 8        | 12.12%  |
| es_AR   | 4        | 6.06%   |
| C       | 1        | 1.52%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 41       | 64.06%  |
| EFI  | 23       | 35.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 51       | 79.69%  |
| Overlay | 10       | 15.63%  |
| Xfs     | 1        | 1.56%   |
| Btrfs   | 1        | 1.56%   |
| Unknown | 1        | 1.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 38       | 59.38%  |
| GPT     | 18       | 28.13%  |
| MBR     | 8        | 12.5%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 46       | 73.02%  |
| Yes       | 17       | 26.98%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 34       | 53.13%  |
| No        | 30       | 46.88%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 13       | 20.63%  |
| ASRock              | 12       | 19.05%  |
| ASUSTek Computer    | 11       | 17.46%  |
| MSI                 | 8        | 12.7%   |
| Hewlett-Packard     | 6        | 9.52%   |
| Dell                | 3        | 4.76%   |
| Intel               | 2        | 3.17%   |
| Supermicro          | 1        | 1.59%   |
| MACHINIST           | 1        | 1.59%   |
| Lenovo              | 1        | 1.59%   |
| Gateway             | 1        | 1.59%   |
| Fujitsu             | 1        | 1.59%   |
| Foxconn             | 1        | 1.59%   |
| ECS                 | 1        | 1.59%   |
| Biostar             | 1        | 1.59%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                             | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| MSI MS-7C37                                                      | 2        | 3.17%   |
| Gigabyte Z390 AORUS ELITE                                        | 2        | 3.17%   |
| ASRock ALiveNF6P-VSTA                                            | 2        | 3.17%   |
| Supermicro P4DMS                                                 | 1        | 1.59%   |
| MSI MS-7817                                                      | 1        | 1.59%   |
| MSI MS-7816                                                      | 1        | 1.59%   |
| MSI MS-7786                                                      | 1        | 1.59%   |
| MSI MS-7721                                                      | 1        | 1.59%   |
| MSI MS-7592                                                      | 1        | 1.59%   |
| MSI MS-7383                                                      | 1        | 1.59%   |
| MACHINIST X79 (INTEL Xeon E5/Corei7 DMI2 - C600/C200 Cipset V309 | 1        | 1.59%   |
| Lenovo ThinkCentre M92p 3238BK7                                  | 1        | 1.59%   |
| Intel H61M-DS2                                                   | 1        | 1.59%   |
| Intel DP35DP AAD81073-208                                        | 1        | 1.59%   |
| HP rp5800                                                        | 1        | 1.59%   |
| HP EliteDesk 800 G1 SFF                                          | 1        | 1.59%   |
| HP dc5000 SFF(DX854AV)                                           | 1        | 1.59%   |
| HP Compaq dc7800p Small Form Factor                              | 1        | 1.59%   |
| HP Compaq 6200 Pro SFF PC                                        | 1        | 1.59%   |
| HP Compaq 6005 Pro MT PC                                         | 1        | 1.59%   |
| Gigabyte Z370 AORUS Gaming 7                                     | 1        | 1.59%   |
| Gigabyte Z170X-Gaming 3                                          | 1        | 1.59%   |
| Gigabyte X570 GAMING X                                           | 1        | 1.59%   |
| Gigabyte H81M-DS2                                                | 1        | 1.59%   |
| Gigabyte H61M-S1                                                 | 1        | 1.59%   |
| Gigabyte H410M H V3                                              | 1        | 1.59%   |
| Gigabyte H310M A                                                 | 1        | 1.59%   |
| Gigabyte GA-970A-D3                                              | 1        | 1.59%   |
| Gigabyte GA-78LMT-S2                                             | 1        | 1.59%   |
| Gigabyte B450 GAMING X                                           | 1        | 1.59%   |
| Gigabyte AX370-Gaming 5                                          | 1        | 1.59%   |
| Gateway DX4375                                                   | 1        | 1.59%   |
| Fujitsu ESPRIMO C700                                             | 1        | 1.59%   |
| Foxconn G31MX Series                                             | 1        | 1.59%   |
| ECS H310H5-M2                                                    | 1        | 1.59%   |
| Dell OptiPlex 990                                                | 1        | 1.59%   |
| Dell OptiPlex 980                                                | 1        | 1.59%   |
| Dell OptiPlex 780                                                | 1        | 1.59%   |
| Biostar Z490A-SILVER                                             | 1        | 1.59%   |
| ASUS TUF Gaming B550-PLUS                                        | 1        | 1.59%   |
| ASUS TUF Gaming B460M-PLUS                                       | 1        | 1.59%   |
| ASUS Rampage IV EXTREME                                          | 1        | 1.59%   |
| ASUS PRIME B450M-A II                                            | 1        | 1.59%   |
| ASUS PRIME B450-PLUS                                             | 1        | 1.59%   |
| ASUS P8H77-V                                                     | 1        | 1.59%   |
| ASUS P8H67-M LX                                                  | 1        | 1.59%   |
| ASUS M5A99X EVO R2.0                                             | 1        | 1.59%   |
| ASUS M5A87                                                       | 1        | 1.59%   |
| ASUS M5A78L-M/USB3                                               | 1        | 1.59%   |
| ASUS K8V-X SE                                                    | 1        | 1.59%   |
| ASRock N68-VS3 FX                                                | 1        | 1.59%   |
| ASRock N68-S                                                     | 1        | 1.59%   |
| ASRock H310CM-HDV                                                | 1        | 1.59%   |
| ASRock G41M-VS3                                                  | 1        | 1.59%   |
| ASRock FM2A58M-VG3+ R2.0                                         | 1        | 1.59%   |
| ASRock FM2A55M-VG3+                                              | 1        | 1.59%   |
| ASRock FM2A55M-HD+                                               | 1        | 1.59%   |
| ASRock B450M Steel Legend                                        | 1        | 1.59%   |
| ASRock A320M-HDV R3.0                                            | 1        | 1.59%   |
| ASRock A320M-HDV                                                 | 1        | 1.59%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| HP Compaq             | 3        | 4.76%   |
| Dell OptiPlex         | 3        | 4.76%   |
| MSI MS-7C37           | 2        | 3.17%   |
| Gigabyte Z390         | 2        | 3.17%   |
| ASUS TUF              | 2        | 3.17%   |
| ASUS PRIME            | 2        | 3.17%   |
| ASRock ALiveNF6P-VSTA | 2        | 3.17%   |
| ASRock A320M-HDV      | 2        | 3.17%   |
| Supermicro P4DMS      | 1        | 1.59%   |
| MSI MS-7817           | 1        | 1.59%   |
| MSI MS-7816           | 1        | 1.59%   |
| MSI MS-7786           | 1        | 1.59%   |
| MSI MS-7721           | 1        | 1.59%   |
| MSI MS-7592           | 1        | 1.59%   |
| MSI MS-7383           | 1        | 1.59%   |
| MACHINIST X79         | 1        | 1.59%   |
| Lenovo ThinkCentre    | 1        | 1.59%   |
| Intel H61M-DS2        | 1        | 1.59%   |
| Intel DP35DP          | 1        | 1.59%   |
| HP rp5800             | 1        | 1.59%   |
| HP EliteDesk          | 1        | 1.59%   |
| HP dc5000             | 1        | 1.59%   |
| Gigabyte Z370         | 1        | 1.59%   |
| Gigabyte Z170X-Gaming | 1        | 1.59%   |
| Gigabyte X570         | 1        | 1.59%   |
| Gigabyte H81M-DS2     | 1        | 1.59%   |
| Gigabyte H61M-S1      | 1        | 1.59%   |
| Gigabyte H410M        | 1        | 1.59%   |
| Gigabyte H310M        | 1        | 1.59%   |
| Gigabyte GA-970A-D3   | 1        | 1.59%   |
| Gigabyte GA-78LMT-S2  | 1        | 1.59%   |
| Gigabyte B450         | 1        | 1.59%   |
| Gigabyte AX370-Gaming | 1        | 1.59%   |
| Gateway DX4375        | 1        | 1.59%   |
| Fujitsu ESPRIMO       | 1        | 1.59%   |
| Foxconn G31MX         | 1        | 1.59%   |
| ECS H310H5-M2         | 1        | 1.59%   |
| Biostar Z490A-SILVER  | 1        | 1.59%   |
| ASUS Rampage          | 1        | 1.59%   |
| ASUS P8H77-V          | 1        | 1.59%   |
| ASUS P8H67-M          | 1        | 1.59%   |
| ASUS M5A99X           | 1        | 1.59%   |
| ASUS M5A87            | 1        | 1.59%   |
| ASUS M5A78L-M         | 1        | 1.59%   |
| ASUS K8V-X            | 1        | 1.59%   |
| ASRock N68-VS3        | 1        | 1.59%   |
| ASRock N68-S          | 1        | 1.59%   |
| ASRock H310CM-HDV     | 1        | 1.59%   |
| ASRock G41M-VS3       | 1        | 1.59%   |
| ASRock FM2A58M-VG3+   | 1        | 1.59%   |
| ASRock FM2A55M-VG3+   | 1        | 1.59%   |
| ASRock FM2A55M-HD+    | 1        | 1.59%   |
| ASRock B450M          | 1        | 1.59%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 11       | 17.46%  |
| 2019 | 8        | 12.7%   |
| 2013 | 7        | 11.11%  |
| 2012 | 5        | 7.94%   |
| 2018 | 4        | 6.35%   |
| 2009 | 4        | 6.35%   |
| 2007 | 4        | 6.35%   |
| 2020 | 3        | 4.76%   |
| 2017 | 3        | 4.76%   |
| 2021 | 2        | 3.17%   |
| 2015 | 2        | 3.17%   |
| 2014 | 2        | 3.17%   |
| 2010 | 2        | 3.17%   |
| 2022 | 1        | 1.59%   |
| 2016 | 1        | 1.59%   |
| 2008 | 1        | 1.59%   |
| 2005 | 1        | 1.59%   |
| 2004 | 1        | 1.59%   |
| 2003 | 1        | 1.59%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 63       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 63       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 63       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 14       | 21.21%  |
| 16.01-24.0  | 13       | 19.7%   |
| 3.01-4.0    | 12       | 18.18%  |
| 4.01-8.0    | 10       | 15.15%  |
| 32.01-64.0  | 5        | 7.58%   |
| 1.01-2.0    | 4        | 6.06%   |
| 24.01-32.0  | 3        | 4.55%   |
| 64.01-256.0 | 3        | 4.55%   |
| 0.51-1.0    | 1        | 1.52%   |
| 0.01-0.5    | 1        | 1.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 24       | 35.82%  |
| 2.01-3.0  | 14       | 20.9%   |
| 3.01-4.0  | 11       | 16.42%  |
| 0.51-1.0  | 6        | 8.96%   |
| 4.01-8.0  | 5        | 7.46%   |
| 8.01-16.0 | 4        | 5.97%   |
| 0.01-0.5  | 3        | 4.48%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 27       | 40.91%  |
| 2      | 19       | 28.79%  |
| 3      | 10       | 15.15%  |
| 4      | 8        | 12.12%  |
| 5      | 2        | 3.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 33       | 52.38%  |
| No        | 30       | 47.62%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 62       | 98.41%  |
| No        | 1        | 1.59%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 39       | 60%     |
| Yes       | 26       | 40%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 52       | 82.54%  |
| Yes       | 11       | 17.46%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Uruguay | 63       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Montevideo       | 50       | 75.76%  |
| Maldonado        | 3        | 4.55%   |
| San Jose de Mayo | 2        | 3.03%   |
| Las Piedras      | 2        | 3.03%   |
| Florida          | 2        | 3.03%   |
| Nuevo Paris      | 1        | 1.52%   |
| Melo             | 1        | 1.52%   |
| Malvin Norte     | 1        | 1.52%   |
| La Paz           | 1        | 1.52%   |
| Durazno          | 1        | 1.52%   |
| Ciudad del Plata | 1        | 1.52%   |
| Centro           | 1        | 1.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 35       | 46     | 30.43%  |
| Seagate                   | 18       | 25     | 15.65%  |
| Samsung Electronics       | 18       | 19     | 15.65%  |
| Kingston                  | 16       | 18     | 13.91%  |
| Toshiba                   | 10       | 14     | 8.7%    |
| Hitachi                   | 3        | 6      | 2.61%   |
| Crucial                   | 3        | 4      | 2.61%   |
| Micron/Crucial Technology | 2        | 3      | 1.74%   |
| Hewlett-Packard           | 2        | 2      | 1.74%   |
| Silicon Motion            | 1        | 1      | 0.87%   |
| Phison                    | 1        | 1      | 0.87%   |
| Micron Technology         | 1        | 1      | 0.87%   |
| Maxtor                    | 1        | 2      | 0.87%   |
| IBM-ESXS                  | 1        | 1      | 0.87%   |
| HGST                      | 1        | 1      | 0.87%   |
| Gigabyte Technology       | 1        | 1      | 0.87%   |
| ExcelStor                 | 1        | 1      | 0.87%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB               | 5        | 3.94%   |
| Samsung HD161HJ 160GB                | 5        | 3.94%   |
| WDC WD5000AAKX-00ERMA0 500GB         | 3        | 2.36%   |
| WDC WD10EZEX-08WN4A0 1TB             | 3        | 2.36%   |
| Toshiba DT01ACA300 3TB               | 3        | 2.36%   |
| Seagate ST1000DM010-2EP102 1TB       | 3        | 2.36%   |
| Kingston SA400S37240G 240GB SSD      | 3        | 2.36%   |
| Kingston SA400S37120G 120GB SSD      | 3        | 2.36%   |
| WDC WD10EFRX-68FYTN0 1TB             | 2        | 1.57%   |
| Seagate ST500DM002-1BD142 500GB      | 2        | 1.57%   |
| Seagate ST3250312AS 250GB            | 2        | 1.57%   |
| Samsung HD103SJ 1TB                  | 2        | 1.57%   |
| Kingston SV300S37A120G 120GB SSD     | 2        | 1.57%   |
| Kingston SNVS1000G 1TB               | 2        | 1.57%   |
| Kingston SA400S37480G 480GB SSD      | 2        | 1.57%   |
| Kingston SA2000M81000G 1TB           | 2        | 1.57%   |
| WDC WDS512G1X0C-00ENX0 512GB         | 1        | 0.79%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1        | 0.79%   |
| WDC WDS250G2B0B-00YS70 250GB SSD     | 1        | 0.79%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1        | 0.79%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1        | 0.79%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1        | 0.79%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 1        | 0.79%   |
| WDC WD800JD-60LSA5 80GB              | 1        | 0.79%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1        | 0.79%   |
| WDC WD5000LPVT-24G33T1 500GB         | 1        | 0.79%   |
| WDC WD5000BEKT-60KA9T0 500GB         | 1        | 0.79%   |
| WDC WD5000AZLX-00ZR6A0 500GB         | 1        | 0.79%   |
| WDC WD5000AVVS-63ZWB0 500GB          | 1        | 0.79%   |
| WDC WD5000AAKS-00A7B2 500GB          | 1        | 0.79%   |
| WDC WD5000AAJS-00A8B0 500GB          | 1        | 0.79%   |
| WDC WD40EZRZ-00GXCB0 4TB             | 1        | 0.79%   |
| WDC WD400BB-00DEA0 40GB              | 1        | 0.79%   |
| WDC WD2500JS-58NCB1 250GB            | 1        | 0.79%   |
| WDC WD2500AAKX-603CA0 250GB          | 1        | 0.79%   |
| WDC WD2500AAKX-07U6AA0 250GB         | 1        | 0.79%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 1        | 0.79%   |
| WDC WD1600AAJS-65M0A0 160GB          | 1        | 0.79%   |
| WDC WD1600AABS-00PRA0 160GB          | 1        | 0.79%   |
| WDC WD10EZEX-75ZF5A0 1TB             | 1        | 0.79%   |
| WDC WD10EZEX-60WN4A1 1TB             | 1        | 0.79%   |
| WDC WD10EZEX-60M2NA0 1TB             | 1        | 0.79%   |
| WDC WD10EZEX-22RKKA0 1TB             | 1        | 0.79%   |
| WDC WD10EZEX-21WN4A0 1TB             | 1        | 0.79%   |
| WDC WD10EZEX-07WN4A0 1TB             | 1        | 0.79%   |
| WDC WD10EZEX-00KUWA0 1TB             | 1        | 0.79%   |
| WDC WD10EZEX-00BN5A0 1TB             | 1        | 0.79%   |
| WDC WD10EZEX-00BBHA0 1TB             | 1        | 0.79%   |
| WDC WD10EARS-22Y5B1 1TB              | 1        | 0.79%   |
| Toshiba MQ01ABD100 1TB               | 1        | 0.79%   |
| Toshiba MQ01ABD075 752GB             | 1        | 0.79%   |
| Toshiba MK3265GSXV 320GB             | 1        | 0.79%   |
| Silicon Motion NVMe SSD Drive 1024GB | 1        | 0.79%   |
| Seagate ST9160314AS 160GB            | 1        | 0.79%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 1        | 0.79%   |
| Seagate ST500DM005 HD502HJ 500GB     | 1        | 0.79%   |
| Seagate ST380013AS 40Y8751LEN 80GB   | 1        | 0.79%   |
| Seagate ST3750640NS 752GB            | 1        | 0.79%   |
| Seagate ST340014A 40GB               | 1        | 0.79%   |
| Seagate ST3250310CS 250GB            | 1        | 0.79%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 30       | 39     | 38.46%  |
| Seagate             | 18       | 25     | 23.08%  |
| Samsung Electronics | 14       | 14     | 17.95%  |
| Toshiba             | 10       | 14     | 12.82%  |
| Hitachi             | 3        | 6      | 3.85%   |
| Maxtor              | 1        | 2      | 1.28%   |
| HGST                | 1        | 1      | 1.28%   |
| ExcelStor           | 1        | 1      | 1.28%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 12       | 13     | 50%     |
| WDC                 | 5        | 5      | 20.83%  |
| Samsung Electronics | 2        | 3      | 8.33%   |
| Crucial             | 2        | 2      | 8.33%   |
| Micron Technology   | 1        | 1      | 4.17%   |
| Hewlett-Packard     | 1        | 1      | 4.17%   |
| Gigabyte Technology | 1        | 1      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 54       | 102    | 59.34%  |
| SSD     | 24       | 26     | 26.37%  |
| NVMe    | 12       | 17     | 13.19%  |
| Unknown | 1        | 1      | 1.1%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 60       | 127    | 81.08%  |
| NVMe | 12       | 17     | 16.22%  |
| SAS  | 2        | 2      | 2.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 49       | 72     | 59.76%  |
| 0.51-1.0   | 27       | 50     | 32.93%  |
| 2.01-3.0   | 4        | 4      | 4.88%   |
| 3.01-4.0   | 1        | 1      | 1.22%   |
| 1.01-2.0   | 1        | 1      | 1.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 17       | 26.15%  |
| 251-500    | 11       | 16.92%  |
| 501-1000   | 11       | 16.92%  |
| 1001-2000  | 8        | 12.31%  |
| 1-20       | 7        | 10.77%  |
| 21-50      | 4        | 6.15%   |
| Unknown    | 3        | 4.62%   |
| 2001-3000  | 2        | 3.08%   |
| 51-100     | 2        | 3.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 24       | 37.5%   |
| 21-50     | 10       | 15.63%  |
| 101-250   | 7        | 10.94%  |
| 501-1000  | 7        | 10.94%  |
| 251-500   | 5        | 7.81%   |
| 51-100    | 5        | 7.81%   |
| Unknown   | 3        | 4.69%   |
| 1001-2000 | 2        | 3.13%   |
| 2001-3000 | 1        | 1.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| WDC WD5000BEKT-60KA9T0 500GB     | 1        | 1      | 8.33%   |
| WDC WD5000AAJS-00A8B0 500GB      | 1        | 1      | 8.33%   |
| WDC WD10EARS-22Y5B1 1TB          | 1        | 1      | 8.33%   |
| Toshiba MQ01ABD075 752GB         | 1        | 1      | 8.33%   |
| Toshiba DT01ACA100 1TB           | 1        | 1      | 8.33%   |
| Seagate ST500DM005 HD502HJ 500GB | 1        | 1      | 8.33%   |
| Seagate ST500DM002-1BD142 500GB  | 1        | 1      | 8.33%   |
| Seagate ST3750640NS 752GB        | 1        | 6      | 8.33%   |
| Seagate ST3250310CS 250GB        | 1        | 1      | 8.33%   |
| Seagate ST3200827AS 200GB        | 1        | 1      | 8.33%   |
| Seagate ST250DM000-1BD141 250GB  | 1        | 1      | 8.33%   |
| Seagate ST1000DM010-2EP102 1TB   | 1        | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 6        | 12     | 54.55%  |
| WDC     | 3        | 3      | 27.27%  |
| Toshiba | 2        | 2      | 18.18%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 6        | 12     | 54.55%  |
| WDC     | 3        | 3      | 27.27%  |
| Toshiba | 2        | 2      | 18.18%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 11       | 17     | 100%    |

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
| Detected | 40       | 84     | 54.05%  |
| Works    | 23       | 45     | 31.08%  |
| Malfunc  | 11       | 17     | 14.86%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 35       | 42.17%  |
| AMD                         | 23       | 27.71%  |
| Nvidia                      | 4        | 4.82%   |
| Kingston Technology Company | 4        | 4.82%   |
| ASMedia Technology          | 4        | 4.82%   |
| Micron/Crucial Technology   | 3        | 3.61%   |
| Silicon Motion              | 2        | 2.41%   |
| SanDisk                     | 2        | 2.41%   |
| Samsung Electronics         | 2        | 2.41%   |
| VIA Technologies            | 1        | 1.2%    |
| Phison Electronics          | 1        | 1.2%    |
| Marvell Technology Group    | 1        | 1.2%    |
| Adaptec                     | 1        | 1.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 14       | 12.28%  |
| Nvidia MCP61 SATA Controller                                                            | 4        | 3.51%   |
| Nvidia MCP61 IDE                                                                        | 4        | 3.51%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4        | 3.51%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4        | 3.51%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 3.51%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 4        | 3.51%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4        | 3.51%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 3.51%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 3.51%   |
| AMD FCH IDE Controller                                                                  | 4        | 3.51%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4        | 3.51%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 2.63%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 2.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3        | 2.63%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 2        | 1.75%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 2        | 1.75%   |
| Kingston Company Company Non-Volatile memory controller                                 | 2        | 1.75%   |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 1.75%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 1.75%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 1.75%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 1.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 1.75%   |
| AMD FCH SATA Controller D                                                               | 2        | 1.75%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1        | 0.88%   |
| VIA VIA VT6420 SATA RAID Controller                                                     | 1        | 0.88%   |
| SanDisk WD Black NVMe SSD                                                               | 1        | 0.88%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 0.88%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.88%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 0.88%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1        | 0.88%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 1        | 0.88%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                                      | 1        | 0.88%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 0.88%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 0.88%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 0.88%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 1        | 0.88%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1        | 0.88%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1        | 0.88%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1        | 0.88%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1        | 0.88%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                            | 1        | 0.88%   |
| Intel 82801CA Ultra ATA Storage Controller                                              | 1        | 0.88%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1        | 0.88%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1        | 0.88%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 1        | 0.88%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 0.88%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 1        | 0.88%   |
| AMD X370 Series Chipset SATA Controller                                                 | 1        | 0.88%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1        | 0.88%   |
| AMD 500 Series Chipset SATA Controller                                                  | 1        | 0.88%   |
| Adaptec AIC-7899P U160/m                                                                | 1        | 0.88%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 46       | 52.27%  |
| IDE  | 26       | 29.55%  |
| NVMe | 12       | 13.64%  |
| RAID | 3        | 3.41%   |
| SCSI | 1        | 1.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 35       | 55.56%  |
| AMD    | 28       | 44.44%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD Ryzen 5 1600 Six-Core Processor             | 3        | 4.76%   |
| Intel Core i7-4790 CPU @ 3.60GHz                | 2        | 3.17%   |
| Intel Core i5-8400 CPU @ 2.80GHz                | 2        | 3.17%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz            | 2        | 3.17%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 2        | 3.17%   |
| Intel Xeon CPU E5-2420 0 @ 1.90GHz              | 1        | 1.59%   |
| Intel Xeon CPU 2.40GHz                          | 1        | 1.59%   |
| Intel Pentium 4 CPU 2.80GHz                     | 1        | 1.59%   |
| Intel Core i9-9900KF CPU @ 3.60GHz              | 1        | 1.59%   |
| Intel Core i7-8700K CPU @ 3.70GHz               | 1        | 1.59%   |
| Intel Core i7-4930K CPU @ 3.40GHz               | 1        | 1.59%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 1        | 1.59%   |
| Intel Core i7-2600K CPU @ 3.40GHz               | 1        | 1.59%   |
| Intel Core i7-2600 CPU @ 3.40GHz                | 1        | 1.59%   |
| Intel Core i7-10700F CPU @ 2.90GHz              | 1        | 1.59%   |
| Intel Core i5-9400F CPU @ 2.90GHz               | 1        | 1.59%   |
| Intel Core i5-6400 CPU @ 2.70GHz                | 1        | 1.59%   |
| Intel Core i5-4570 CPU @ 3.20GHz                | 1        | 1.59%   |
| Intel Core i5-3470T CPU @ 2.90GHz               | 1        | 1.59%   |
| Intel Core i5-2500S CPU @ 2.70GHz               | 1        | 1.59%   |
| Intel Core i5-2400S CPU @ 2.50GHz               | 1        | 1.59%   |
| Intel Core i5-10400F CPU @ 2.90GHz              | 1        | 1.59%   |
| Intel Core i5-10400 CPU @ 2.90GHz               | 1        | 1.59%   |
| Intel Core i5 CPU 650 @ 3.20GHz                 | 1        | 1.59%   |
| Intel Core i3-9100 CPU @ 3.60GHz                | 1        | 1.59%   |
| Intel Core i3-4160 CPU @ 3.60GHz                | 1        | 1.59%   |
| Intel Core i3-2120 CPU @ 3.30GHz                | 1        | 1.59%   |
| Intel Core i3-2100 CPU @ 3.10GHz                | 1        | 1.59%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz           | 1        | 1.59%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz           | 1        | 1.59%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz           | 1        | 1.59%   |
| Intel Core 2 Duo CPU E8300 @ 2.83GHz            | 1        | 1.59%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz            | 1        | 1.59%   |
| Intel Celeron CPU G550 @ 2.60GHz                | 1        | 1.59%   |
| AMD Ryzen 7 5700G with Radeon Graphics          | 1        | 1.59%   |
| AMD Ryzen 7 1700 Eight-Core Processor           | 1        | 1.59%   |
| AMD Ryzen 5 3600 6-Core Processor               | 1        | 1.59%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics     | 1        | 1.59%   |
| AMD Ryzen 3 3100 4-Core Processor               | 1        | 1.59%   |
| AMD Phenom II X6 1100T Processor                | 1        | 1.59%   |
| AMD Phenom II X6 1055T Processor                | 1        | 1.59%   |
| AMD Phenom 9550 Quad-Core Processor             | 1        | 1.59%   |
| AMD FX-8320E Eight-Core Processor               | 1        | 1.59%   |
| AMD FX-8300 Eight-Core Processor                | 1        | 1.59%   |
| AMD FX-4300 Quad-Core Processor                 | 1        | 1.59%   |
| AMD Athlon II X2 B28 Processor                  | 1        | 1.59%   |
| AMD Athlon II X2 250 Processor                  | 1        | 1.59%   |
| AMD Athlon II X2 245 Processor                  | 1        | 1.59%   |
| AMD Athlon 64 X2 Dual Core Processor 4600+      | 1        | 1.59%   |
| AMD Athlon 64 Processor 3000+                   | 1        | 1.59%   |
| AMD Athlon 3000G with Radeon Vega Graphics      | 1        | 1.59%   |
| AMD A8-7600 Radeon R7, 10 Compute Cores 4C+6G   | 1        | 1.59%   |
| AMD A6-6400K APU with Radeon HD Graphics        | 1        | 1.59%   |
| AMD A6-5200 APU with Radeon HD Graphics         | 1        | 1.59%   |
| AMD A4-4000 APU with Radeon HD Graphics         | 1        | 1.59%   |
| AMD A4-3300 APU with Radeon HD Graphics         | 1        | 1.59%   |
| AMD A10-7860K Radeon R7, 12 Compute Cores 4C+8G | 1        | 1.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core i5     | 11       | 17.46%  |
| Intel Core i7     | 8        | 12.7%   |
| AMD Ryzen 5       | 5        | 7.94%   |
| Intel Core i3     | 4        | 6.35%   |
| Intel Core 2 Duo  | 4        | 6.35%   |
| AMD Ryzen 7       | 4        | 6.35%   |
| Intel Core 2 Quad | 3        | 4.76%   |
| AMD FX            | 3        | 4.76%   |
| AMD Athlon II X2  | 3        | 4.76%   |
| Intel Xeon        | 2        | 3.17%   |
| AMD Phenom II X6  | 2        | 3.17%   |
| AMD A6            | 2        | 3.17%   |
| AMD A4            | 2        | 3.17%   |
| Intel Pentium 4   | 1        | 1.59%   |
| Intel Core i9     | 1        | 1.59%   |
| Intel Celeron     | 1        | 1.59%   |
| AMD Ryzen 3       | 1        | 1.59%   |
| AMD Phenom        | 1        | 1.59%   |
| AMD Athlon 64 X2  | 1        | 1.59%   |
| AMD Athlon 64     | 1        | 1.59%   |
| AMD Athlon        | 1        | 1.59%   |
| AMD A8            | 1        | 1.59%   |
| AMD A10           | 1        | 1.59%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 20       | 31.75%  |
| 4      | 19       | 30.16%  |
| 6      | 14       | 22.22%  |
| 8      | 6        | 9.52%   |
| 1      | 4        | 6.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 62       | 98.41%  |
| 2      | 1        | 1.59%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 36       | 57.14%  |
| 1      | 27       | 42.86%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 60       | 95.24%  |
| 32-bit         | 2        | 3.17%   |
| Unknown        | 1        | 1.59%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 12       | 19.05%  |
| 0x206a7    | 5        | 7.94%   |
| 0x906ea    | 4        | 6.35%   |
| 0x306c3    | 4        | 6.35%   |
| 0x1067a    | 4        | 6.35%   |
| 0x08701021 | 4        | 6.35%   |
| 0x06000852 | 3        | 4.76%   |
| 0xa0655    | 2        | 3.17%   |
| 0x08001138 | 2        | 3.17%   |
| 0x06001119 | 2        | 3.17%   |
| 0x010000dc | 2        | 3.17%   |
| 0xf33      | 1        | 1.59%   |
| 0xf27      | 1        | 1.59%   |
| 0x906ec    | 1        | 1.59%   |
| 0x906eb    | 1        | 1.59%   |
| 0x306a9    | 1        | 1.59%   |
| 0x206d7    | 1        | 1.59%   |
| 0x20655    | 1        | 1.59%   |
| 0x10677    | 1        | 1.59%   |
| 0x10676    | 1        | 1.59%   |
| 0x08108109 | 1        | 1.59%   |
| 0x08108102 | 1        | 1.59%   |
| 0x0800820d | 1        | 1.59%   |
| 0x08001137 | 1        | 1.59%   |
| 0x06003106 | 1        | 1.59%   |
| 0x03000027 | 1        | 1.59%   |
| 0x010000c8 | 1        | 1.59%   |
| 0x010000b6 | 1        | 1.59%   |
| 0x01000083 | 1        | 1.59%   |
| 0x00000000 | 1        | 1.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| SandyBridge | 8        | 12.7%   |
| Penryn      | 6        | 9.52%   |
| KabyLake    | 6        | 9.52%   |
| K10         | 6        | 9.52%   |
| Piledriver  | 5        | 7.94%   |
| Zen 2       | 4        | 6.35%   |
| Haswell     | 4        | 6.35%   |
| Zen+        | 3        | 4.76%   |
| Zen         | 3        | 4.76%   |
| IvyBridge   | 3        | 4.76%   |
| CometLake   | 3        | 4.76%   |
| Steamroller | 2        | 3.17%   |
| NetBurst    | 2        | 3.17%   |
| K8 Hammer   | 2        | 3.17%   |
| Zen 3       | 1        | 1.59%   |
| Westmere    | 1        | 1.59%   |
| Skylake     | 1        | 1.59%   |
| K10 Llano   | 1        | 1.59%   |
| Jaguar      | 1        | 1.59%   |
| Core        | 1        | 1.59%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 31       | 46.97%  |
| AMD    | 21       | 31.82%  |
| Intel  | 14       | 21.21%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 3        | 4.41%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 4.41%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 2        | 2.94%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 2.94%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 2.94%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 2.94%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 2        | 2.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 2.94%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 2.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 2.94%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 2        | 2.94%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 2.94%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 1.47%   |
| Nvidia NV34 [GeForce FX 5200]                                               | 1        | 1.47%   |
| Nvidia GT216 [GeForce 210]                                                  | 1        | 1.47%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.47%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 1.47%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.47%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 1.47%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 1.47%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 1.47%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 1.47%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.47%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.47%   |
| Nvidia GK107GL [Quadro K600]                                                | 1        | 1.47%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 1.47%   |
| Nvidia GF108 [GeForce GT 430]                                               | 1        | 1.47%   |
| Nvidia GF100 [GeForce GTX 470]                                              | 1        | 1.47%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 1.47%   |
| Nvidia G96C [GeForce 9400 GT]                                               | 1        | 1.47%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 1.47%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 1.47%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.47%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 1        | 1.47%   |
| Intel 82865G Integrated Graphics Controller                                 | 1        | 1.47%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.47%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 1.47%   |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 1        | 1.47%   |
| AMD RV100 [Radeon 7000 / Radeon VE]                                         | 1        | 1.47%   |
| AMD RS880 [Radeon HD 4200]                                                  | 1        | 1.47%   |
| AMD RS780L [Radeon 3000]                                                    | 1        | 1.47%   |
| AMD Richland [Radeon HD 8470D]                                              | 1        | 1.47%   |
| AMD Rage 3 [Rage XL PCI]                                                    | 1        | 1.47%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]           | 1        | 1.47%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 1        | 1.47%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 1        | 1.47%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 1        | 1.47%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 1.47%   |
| AMD Kabini [Radeon HD 8400 / R3 Series]                                     | 1        | 1.47%   |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                 | 1        | 1.47%   |
| AMD Cezanne                                                                 | 1        | 1.47%   |
| AMD Bonaire XTX [Radeon R7 260X/360]                                        | 1        | 1.47%   |
| AMD Barts XT [Radeon HD 6870]                                               | 1        | 1.47%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1        | 1.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 29       | 46.03%  |
| 1 x AMD        | 18       | 28.57%  |
| 1 x Intel      | 12       | 19.05%  |
| 2 x AMD        | 2        | 3.17%   |
| Intel + Nvidia | 1        | 1.59%   |
| AMD + Nvidia   | 1        | 1.59%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 49       | 76.56%  |
| Proprietary | 10       | 15.63%  |
| Unknown     | 5        | 7.81%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 23       | 35.38%  |
| 1.01-2.0   | 13       | 20%     |
| 0.51-1.0   | 10       | 15.38%  |
| 0.01-0.5   | 8        | 12.31%  |
| 3.01-4.0   | 6        | 9.23%   |
| 7.01-8.0   | 2        | 3.08%   |
| 5.01-6.0   | 2        | 3.08%   |
| 8.01-16.0  | 1        | 1.54%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| AOC                     | 12       | 18.75%  |
| ViewSonic               | 9        | 14.06%  |
| Samsung Electronics     | 8        | 12.5%   |
| Goldstar                | 6        | 9.38%   |
| KTC                     | 4        | 6.25%   |
| Acer                    | 4        | 6.25%   |
| Lenovo                  | 3        | 4.69%   |
| Hewlett-Packard         | 3        | 4.69%   |
| Unknown                 | 2        | 3.13%   |
| Dell                    | 2        | 3.13%   |
| Sony                    | 1        | 1.56%   |
| RIS                     | 1        | 1.56%   |
| Panasonic               | 1        | 1.56%   |
| Lenovo Group Limited    | 1        | 1.56%   |
| KOA                     | 1        | 1.56%   |
| Hitachi                 | 1        | 1.56%   |
| Envision                | 1        | 1.56%   |
| CVT                     | 1        | 1.56%   |
| Chi Mei Optoelectronics | 1        | 1.56%   |
| BenQ                    | 1        | 1.56%   |
| Ancor Communications    | 1        | 1.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Desktops | Percent |
|--------------------------------------------------------------------------|----------|---------|
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch            | 2        | 2.99%   |
| Lenovo LEN C32q-20 LEN65F8 2560x1440 698x393mm 31.5-inch                 | 2        | 2.99%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                          | 2        | 2.99%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                           | 2        | 2.99%   |
| AOC 1950w AOC1950 1366x768 410x230mm 18.5-inch                           | 2        | 2.99%   |
| AOC 1621w AOC1621 1366x768 344x194mm 15.5-inch                           | 2        | 2.99%   |
| ViewSonic XG2405 VSC0D39 1920x1080 530x300mm 24.0-inch                   | 1        | 1.49%   |
| ViewSonic VX2478 Series VSCE032 2560x1440 526x296mm 23.8-inch            | 1        | 1.49%   |
| ViewSonic VX2452 Series VSCDE2E 1920x1080 521x293mm 23.5-inch            | 1        | 1.49%   |
| ViewSonic VX1935wm VSC2A1E 1440x900 408x255mm 18.9-inch                  | 1        | 1.49%   |
| ViewSonic VA702b VSC231C 1280x1024 338x270mm 17.0-inch                   | 1        | 1.49%   |
| ViewSonic VA2415-FHD VSC533C 1920x1080 527x296mm 23.8-inch               | 1        | 1.49%   |
| ViewSonic VA1903a VSC8A31 1366x768 410x230mm 18.5-inch                   | 1        | 1.49%   |
| ViewSonic LCD Monitor VX2240w 3600x1080                                  | 1        | 1.49%   |
| ViewSonic LCD Monitor VA2261                                             | 1        | 1.49%   |
| Unknown MS306 0030 1920x1080 708x398mm 32.0-inch                         | 1        | 1.49%   |
| Unknown LCD Monitor RTK 2944x1080                                        | 1        | 1.49%   |
| Sony LCD Monitor TV                                                      | 1        | 1.49%   |
| Samsung Electronics SyncMaster SAM0546 1920x1080 510x287mm 23.0-inch     | 1        | 1.49%   |
| Samsung Electronics SyncMaster SAM0286 1280x720 372x209mm 16.8-inch      | 1        | 1.49%   |
| Samsung Electronics SM2333TN SAM06FC 1920x1080 477x268mm 21.5-inch       | 1        | 1.49%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch     | 1        | 1.49%   |
| Samsung Electronics S22F350 SAM0D1B 1920x1080 477x268mm 21.5-inch        | 1        | 1.49%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch         | 1        | 1.49%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1872x1053mm 84.6-inch  | 1        | 1.49%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 1        | 1.49%   |
| RIS D185W1-8E RIS0709 1366x768 410x230mm 18.5-inch                       | 1        | 1.49%   |
| Panasonic LCD Monitor TV                                                 | 1        | 1.49%   |
| Lenovo LEN T2254pC LEN60CC 1680x1050 474x296mm 22.0-inch                 | 1        | 1.49%   |
| Lenovo Group Limited LCD Monitor LEN T2254pC 1680x1050                   | 1        | 1.49%   |
| KTC W9023S5 KTC1852 1360x768 410x230mm 18.5-inch                         | 1        | 1.49%   |
| KTC W5006L KTC1542 1280x768 331x207mm 15.4-inch                          | 1        | 1.49%   |
| KTC 42L21-ISDB KTC4202 1920x1080 983x576mm 44.9-inch                     | 1        | 1.49%   |
| KTC 42 TV KTC4200 1920x1080 983x576mm 44.9-inch                          | 1        | 1.49%   |
| KOA LCD Monitor KONKA LCDTV 1920x1080                                    | 1        | 1.49%   |
| Hitachi HISENSE HEC0030 3840x2160 1210x680mm 54.6-inch                   | 1        | 1.49%   |
| Hewlett-Packard VH22 HWP3352 1920x1080 477x268mm 21.5-inch               | 1        | 1.49%   |
| Hewlett-Packard LA1905 HWP2844 1440x900 408x255mm 18.9-inch              | 1        | 1.49%   |
| Hewlett-Packard L1755 HWP264A 1280x1024 376x301mm 19.0-inch              | 1        | 1.49%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 1        | 1.49%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 1        | 1.49%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                    | 1        | 1.49%   |
| Goldstar HD GSM5ACD 1366x768 410x230mm 18.5-inch                         | 1        | 1.49%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 1        | 1.49%   |
| Goldstar E2042 GSM4ED7 1600x900 443x249mm 20.0-inch                      | 1        | 1.49%   |
| Envision EPI3243 EPI3243 1360x768 708x398mm 32.0-inch                    | 1        | 1.49%   |
| Dell U2414H DELA0A4 1920x1080 530x300mm 24.0-inch                        | 1        | 1.49%   |
| Dell E196FP DELA015 1280x1024 376x301mm 19.0-inch                        | 1        | 1.49%   |
| CVT LCD CVT001A 1920x1080 330x210mm 15.4-inch                            | 1        | 1.49%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 1        | 1.49%   |
| BenQ T52W BNQ771F 1280x720 332x187mm 15.0-inch                           | 1        | 1.49%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                          | 1        | 1.49%   |
| AOC 2461W AOC2461 1920x1080 521x293mm 23.5-inch                          | 1        | 1.49%   |
| AOC 2243W AOC2243 1920x1080 477x268mm 21.5-inch                          | 1        | 1.49%   |
| AOC 2036 AOC2036 1600x900 443x249mm 20.0-inch                            | 1        | 1.49%   |
| AOC 2036 AOC2036 1600x900 440x250mm 19.9-inch                            | 1        | 1.49%   |
| Ancor Communications ASUS PB238 ACI23A2 1920x1080 509x286mm 23.0-inch    | 1        | 1.49%   |
| Acer V226HQL ACR032D 1920x1080 477x268mm 21.5-inch                       | 1        | 1.49%   |
| Acer V206HQLB ACR051A 1366x768 434x236mm 19.4-inch                       | 1        | 1.49%   |
| Acer V206HQL ACR0334 1600x900 432x240mm 19.5-inch                        | 1        | 1.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 18       | 30%     |
| 1366x768 (WXGA)    | 11       | 18.33%  |
| 1600x900 (HD+)     | 5        | 8.33%   |
| 3840x2160 (4K)     | 4        | 6.67%   |
| 1280x1024 (SXGA)   | 4        | 6.67%   |
| 2560x1440 (QHD)    | 3        | 5%      |
| Unknown            | 3        | 5%      |
| 1680x1050 (WSXGA+) | 2        | 3.33%   |
| 1440x900 (WXGA+)   | 2        | 3.33%   |
| 1360x768           | 2        | 3.33%   |
| 1280x720 (HD)      | 2        | 3.33%   |
| 3600x1080          | 1        | 1.67%   |
| 2944x1080          | 1        | 1.67%   |
| 2560x1080          | 1        | 1.67%   |
| 1280x768           | 1        | 1.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 10       | 16.13%  |
| 18      | 9        | 14.52%  |
| 21      | 8        | 12.9%   |
| 19      | 6        | 9.68%   |
| 15      | 6        | 9.68%   |
| Unknown | 5        | 8.06%   |
| 20      | 3        | 4.84%   |
| 84      | 2        | 3.23%   |
| 44      | 2        | 3.23%   |
| 32      | 2        | 3.23%   |
| 31      | 2        | 3.23%   |
| 24      | 2        | 3.23%   |
| 34      | 1        | 1.61%   |
| 27      | 1        | 1.61%   |
| 22      | 1        | 1.61%   |
| 17      | 1        | 1.61%   |
| 16      | 1        | 1.61%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 24       | 40%     |
| 501-600     | 11       | 18.33%  |
| 301-350     | 7        | 11.67%  |
| Unknown     | 5        | 8.33%   |
| 351-400     | 4        | 6.67%   |
| 701-800     | 3        | 5%      |
| 601-700     | 2        | 3.33%   |
| 1501-2000   | 2        | 3.33%   |
| 901-1000    | 2        | 3.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 40       | 72.73%  |
| 16/10   | 5        | 9.09%   |
| Unknown | 5        | 9.09%   |
| 5/4     | 4        | 7.27%   |
| 21/9    | 1        | 1.82%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 15       | 25.86%  |
| 151-200        | 15       | 25.86%  |
| 141-150        | 7        | 12.07%  |
| 101-110        | 5        | 8.62%   |
| Unknown        | 5        | 8.62%   |
| 351-500        | 4        | 6.9%    |
| More than 1000 | 2        | 3.45%   |
| 501-1000       | 2        | 3.45%   |
| 301-350        | 1        | 1.72%   |
| 121-130        | 1        | 1.72%   |
| 91-100         | 1        | 1.72%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 36       | 64.29%  |
| 101-120 | 9        | 16.07%  |
| Unknown | 5        | 8.93%   |
| 1-50    | 3        | 5.36%   |
| 121-160 | 2        | 3.57%   |
| 161-240 | 1        | 1.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 43       | 67.19%  |
| 2     | 13       | 20.31%  |
| 0     | 7        | 10.94%  |
| 4     | 1        | 1.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 35       | 39.33%  |
| Intel                 | 21       | 23.6%   |
| Qualcomm Atheros      | 10       | 11.24%  |
| Ralink Technology     | 5        | 5.62%   |
| Nvidia                | 4        | 4.49%   |
| TP-Link               | 3        | 3.37%   |
| Xiaomi                | 2        | 2.25%   |
| Broadcom              | 2        | 2.25%   |
| VIA Technologies      | 1        | 1.12%   |
| Samsung Electronics   | 1        | 1.12%   |
| Ralink                | 1        | 1.12%   |
| Qualcomm              | 1        | 1.12%   |
| Mercucys              | 1        | 1.12%   |
| Huawei Technologies   | 1        | 1.12%   |
| Broadcom Limited      | 1        | 1.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30       | 30%     |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4        | 4%      |
| Nvidia MCP61 Ethernet                                             | 4        | 4%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 4%      |
| Intel Ethernet Connection (7) I219-V                              | 3        | 3%      |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 2%      |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2        | 2%      |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 2        | 2%      |
| Ralink MT7601U Wireless Adapter                                   | 2        | 2%      |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2        | 2%      |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 2%      |
| Intel Wi-Fi 6 AX200                                               | 2        | 2%      |
| Intel 82579V Gigabit Network Connection                           | 2        | 2%      |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 2        | 2%      |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 1%      |
| VIA AC'97 Modem Controller                                        | 1        | 1%      |
| TP-Link 802.11ac NIC                                              | 1        | 1%      |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 1%      |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1        | 1%      |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1        | 1%      |
| Realtek RTL8188SU 802.11n WLAN Adapter                            | 1        | 1%      |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 1%      |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 1        | 1%      |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 1%      |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1        | 1%      |
| Ralink RT2070 Wireless Adapter                                    | 1        | 1%      |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                 | 1        | 1%      |
| Ralink RT2561/RT61 802.11g PCI                                    | 1        | 1%      |
| Qualcomm BENGAL-QRD _SN:C5464635                                  | 1        | 1%      |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1        | 1%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1        | 1%      |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1        | 1%      |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1%      |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 1%      |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1        | 1%      |
| Mercucys 802.11n NIC                                              | 1        | 1%      |
| Intel I211 Gigabit Network Connection                             | 1        | 1%      |
| Intel Ethernet Connection I217-LM                                 | 1        | 1%      |
| Intel Ethernet Connection (2) I219-V                              | 1        | 1%      |
| Intel Ethernet Connection (12) I219-V                             | 1        | 1%      |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1%      |
| Intel 82578DM Gigabit Network Connection                          | 1        | 1%      |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 1%      |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 1%      |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 1%      |
| Intel 82544GC Gigabit Ethernet Controller (LOM)                   | 1        | 1%      |
| Huawei E353/E3131                                                 | 1        | 1%      |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1%      |
| Broadcom Limited NetXtreme BCM5782 Gigabit Ethernet               | 1        | 1%      |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 1        | 1%      |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 11       | 40.74%  |
| Ralink Technology     | 5        | 18.52%  |
| TP-Link               | 3        | 11.11%  |
| Qualcomm Atheros      | 3        | 11.11%  |
| Intel                 | 2        | 7.41%   |
| Ralink                | 1        | 3.7%    |
| Mercucys              | 1        | 3.7%    |
| Broadcom              | 1        | 3.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 4        | 14.81%  |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2        | 7.41%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 2        | 7.41%   |
| Ralink MT7601U Wireless Adapter                                | 2        | 7.41%   |
| Intel Wi-Fi 6 AX200                                            | 2        | 7.41%   |
| TP-Link 802.11ac NIC                                           | 1        | 3.7%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 1        | 3.7%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1        | 3.7%    |
| Realtek RTL8188SU 802.11n WLAN Adapter                         | 1        | 3.7%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1        | 3.7%    |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter       | 1        | 3.7%    |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1        | 3.7%    |
| Ralink RT2070 Wireless Adapter                                 | 1        | 3.7%    |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter              | 1        | 3.7%    |
| Ralink RT2561/RT61 802.11g PCI                                 | 1        | 3.7%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 3.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1        | 3.7%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 1        | 3.7%    |
| Mercucys 802.11n NIC                                           | 1        | 3.7%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 1        | 3.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 32       | 45.07%  |
| Intel                 | 20       | 28.17%  |
| Qualcomm Atheros      | 7        | 9.86%   |
| Nvidia                | 4        | 5.63%   |
| Xiaomi                | 2        | 2.82%   |
| VIA Technologies      | 1        | 1.41%   |
| Samsung Electronics   | 1        | 1.41%   |
| Qualcomm              | 1        | 1.41%   |
| Huawei Technologies   | 1        | 1.41%   |
| Broadcom Limited      | 1        | 1.41%   |
| Broadcom              | 1        | 1.41%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30       | 41.67%  |
| Nvidia MCP61 Ethernet                                             | 4        | 5.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 5.56%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 4.17%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 2.78%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2        | 2.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 2.78%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 2.78%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 2        | 2.78%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 1.39%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 1.39%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.39%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 1.39%   |
| Qualcomm BENGAL-QRD _SN:C5464635                                  | 1        | 1.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.39%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 1.39%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1        | 1.39%   |
| Intel I211 Gigabit Network Connection                             | 1        | 1.39%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.39%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 1.39%   |
| Intel Ethernet Connection (12) I219-V                             | 1        | 1.39%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.39%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 1.39%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 1.39%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 1.39%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 1.39%   |
| Intel 82544GC Gigabit Ethernet Controller (LOM)                   | 1        | 1.39%   |
| Huawei E353/E3131                                                 | 1        | 1.39%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.39%   |
| Broadcom Limited NetXtreme BCM5782 Gigabit Ethernet               | 1        | 1.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 62       | 69.66%  |
| WiFi     | 26       | 29.21%  |
| Modem    | 1        | 1.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 44       | 68.75%  |
| WiFi     | 20       | 31.25%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 50       | 79.37%  |
| 2     | 11       | 17.46%  |
| 3     | 1        | 1.59%   |
| 0     | 1        | 1.59%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 53       | 81.54%  |
| Yes  | 12       | 18.46%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 7        | 63.64%  |
| Intel                           | 2        | 18.18%  |
| Realtek Semiconductor           | 1        | 9.09%   |
| Qualcomm Atheros Communications | 1        | 9.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7        | 63.64%  |
| Intel AX200 Bluetooth                               | 2        | 18.18%  |
| Realtek Bluetooth Radio                             | 1        | 9.09%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 9.09%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 34       | 33.33%  |
| Nvidia                 | 28       | 27.45%  |
| AMD                    | 25       | 24.51%  |
| Logitech               | 3        | 2.94%   |
| VIA Technologies       | 2        | 1.96%   |
| Samson Technologies    | 2        | 1.96%   |
| Creative Labs          | 2        | 1.96%   |
| Texas Instruments      | 1        | 0.98%   |
| Rockwell International | 1        | 0.98%   |
| Focusrite-Novation     | 1        | 0.98%   |
| Elgato Systems         | 1        | 0.98%   |
| Creative Technology    | 1        | 0.98%   |
| C-Media Electronics    | 1        | 0.98%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller  | 7        | 5.79%   |
| AMD SBx00 Azalia (Intel HDA)                                                | 6        | 4.96%   |
| AMD FCH Azalia Controller                                                   | 6        | 4.96%   |
| Nvidia High Definition Audio Controller                                     | 5        | 4.13%   |
| Nvidia MCP61 High Definition Audio                                          | 4        | 3.31%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                     | 4        | 3.31%   |
| Intel Cannon Lake PCH cAVS                                                  | 4        | 3.31%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller         | 4        | 3.31%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                         | 4        | 3.31%   |
| Nvidia TU116 High Definition Audio Controller                               | 3        | 2.48%   |
| Nvidia GK208 HDMI/DP Audio Controller                                       | 3        | 2.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller            | 3        | 2.48%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller         | 3        | 2.48%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]     | 3        | 2.48%   |
| AMD Family 17h/19h HD Audio Controller                                      | 3        | 2.48%   |
| Nvidia GP107GL High Definition Audio Controller                             | 2        | 1.65%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]               | 2        | 1.65%   |
| Nvidia GA106 High Definition Audio Controller                               | 2        | 1.65%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                              | 2        | 1.65%   |
| Intel 200 Series PCH HD Audio                                               | 2        | 1.65%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]               | 2        | 1.65%   |
| AMD Starship/Matisse HD Audio Controller                                    | 2        | 1.65%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                         | 2        | 1.65%   |
| AMD Navi 10 HDMI Audio                                                      | 2        | 1.65%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                  | 2        | 1.65%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                | 2        | 1.65%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                   | 1        | 0.83%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller | 1        | 0.83%   |
| Texas Instruments PCM2902 Audio Codec                                       | 1        | 0.83%   |
| Samson Technologies Meteor condenser microphone                             | 1        | 0.83%   |
| Samson Technologies C03U multi-pattern microphone                           | 1        | 0.83%   |
| Rockwell International Riptide Bus / Firmware Downloader [PCI Audio]        | 1        | 0.83%   |
| Nvidia GT216 HDMI Audio Controller                                          | 1        | 0.83%   |
| Nvidia GP108 High Definition Audio Controller                               | 1        | 0.83%   |
| Nvidia GP106 High Definition Audio Controller                               | 1        | 0.83%   |
| Nvidia GM206 High Definition Audio Controller                               | 1        | 0.83%   |
| Nvidia GM204 High Definition Audio Controller                               | 1        | 0.83%   |
| Nvidia GK107 HDMI Audio Controller                                          | 1        | 0.83%   |
| Nvidia GF119 HDMI Audio Controller                                          | 1        | 0.83%   |
| Nvidia GF108 High Definition Audio Controller                               | 1        | 0.83%   |
| Nvidia GF100 High Definition Audio Controller                               | 1        | 0.83%   |
| Logitech USB Headset                                                        | 1        | 0.83%   |
| Logitech Headset H390                                                       | 1        | 0.83%   |
| Logitech G935 Gaming Headset                                                | 1        | 0.83%   |
| Intel Comet Lake PCH-V cAVS                                                 | 1        | 0.83%   |
| Intel Comet Lake PCH cAVS                                                   | 1        | 0.83%   |
| Intel C600/X79 series chipset High Definition Audio Controller              | 1        | 0.83%   |
| Intel Audio device                                                          | 1        | 0.83%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                         | 1        | 0.83%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                        | 1        | 0.83%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                    | 1        | 0.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller             | 1        | 0.83%   |
| Focusrite-Novation Scarlett Solo USB                                        | 1        | 0.83%   |
| Elgato Systems Elgato Wave:3                                                | 1        | 0.83%   |
| Creative Technology Sound Blaster Premium HD [SBX]                          | 1        | 0.83%   |
| C-Media Electronics CM108 Audio Controller                                  | 1        | 0.83%   |
| AMD Trinity HDMI Audio Controller                                           | 1        | 0.83%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                          | 1        | 0.83%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                      | 1        | 0.83%   |
| AMD Renoir Radeon High Definition Audio Controller                          | 1        | 0.83%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 11       | 26.19%  |
| Unknown             | 8        | 19.05%  |
| Crucial             | 5        | 11.9%   |
| SK hynix            | 3        | 7.14%   |
| Samsung Electronics | 3        | 7.14%   |
| Team                | 2        | 4.76%   |
| Micron Technology   | 2        | 4.76%   |
| A-DATA Technology   | 2        | 4.76%   |
| Smart               | 1        | 2.38%   |
| Patriot             | 1        | 2.38%   |
| Infineon            | 1        | 2.38%   |
| Hikvision           | 1        | 2.38%   |
| Corsair             | 1        | 2.38%   |
| Avant               | 1        | 2.38%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s   | 3        | 6.52%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                | 1        | 2.17%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                     | 1        | 2.17%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                     | 1        | 2.17%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s             | 1        | 2.17%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 1        | 2.17%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s             | 1        | 2.17%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                  | 1        | 2.17%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                 | 1        | 2.17%   |
| Unknown RAM 3200 C18 Series 16384MB DIMM DDR4 2400MT/s   | 1        | 2.17%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s       | 1        | 2.17%   |
| Team RAM Elite-1333 4GB DIMM DDR3 1333MT/s               | 1        | 2.17%   |
| Smart RAM SM5643285D8N6CHIBH 256MB DIMM DDR 266MT/s      | 1        | 2.17%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s               | 1        | 2.17%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 1        | 2.17%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s     | 1        | 2.17%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s    | 1        | 2.17%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s      | 1        | 2.17%   |
| Samsung RAM M378A1K43CB2-CRC 8192MB DIMM DDR4 3500MT/s   | 1        | 2.17%   |
| Patriot RAM PSD416G26662 16GB DIMM DDR4 2667MT/s         | 1        | 2.17%   |
| Micron RAM 8KTF25664AZ-1G4M1 2048MB DIMM DDR3 1333MT/s   | 1        | 2.17%   |
| Micron RAM 8JTF25664AZ-1G4M1 2048MB DIMM DDR3 1333MT/s   | 1        | 2.17%   |
| Kingston RAM Module 4GB DIMM DDR3 1333MT/s               | 1        | 2.17%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s        | 1        | 2.17%   |
| Kingston RAM KHX2133C14/16G 16GB DIMM DDR4 2176MT/s      | 1        | 2.17%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s      | 1        | 2.17%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s      | 1        | 2.17%   |
| Kingston RAM KHX1600C10D3/8G 4096MB DIMM DDR3 1600MT/s   | 1        | 2.17%   |
| Kingston RAM 99U5702-095.A00G 8GB DIMM DDR4 2667MT/s     | 1        | 2.17%   |
| Kingston RAM 99U5474-012.A00LF 4096MB DIMM DDR3 1333MT/s | 1        | 2.17%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s    | 1        | 2.17%   |
| Kingston RAM 99U5471-025.A00LF 4GB DIMM DDR3 1333MT/s    | 1        | 2.17%   |
| Infineon RAM 64D32300GU6C 256MB DIMM DDR 333MT/s         | 1        | 2.17%   |
| Hikvision RAM HKED4161DAA1D0MA1 16GB DIMM DDR4 2667MT/s  | 1        | 2.17%   |
| Hikvision RAM HKED4081CBA1D0MA1 8GB DIMM DDR4 2666MT/s   | 1        | 2.17%   |
| Crucial RAM CT25664BA1339.M8FD 2GB DIMM DDR3 1333MT/s    | 1        | 2.17%   |
| Crucial RAM CT16G4DFD824A.M16FD 16GB DIMM DDR4 2400MT/s  | 1        | 2.17%   |
| Crucial RAM CT16G4DFD824A.C16FDD 16GB DIMM DDR4 2400MT/s | 1        | 2.17%   |
| Crucial RAM CT102464BD160B.M16 8GB DIMM DDR3 1600MT/s    | 1        | 2.17%   |
| Crucial RAM BL16G30C15U4B.M16FE1 16GB DIMM DDR4 3000MT/s | 1        | 2.17%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s      | 1        | 2.17%   |
| Avant RAM F641GU67G1600G 8192MB DIMM DDR3 1600MT/s       | 1        | 2.17%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3400MT/s              | 1        | 2.17%   |
| A-DATA RAM DDR4 3000 2OZ 16GB DIMM DDR4 3000MT/s         | 1        | 2.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 14       | 42.42%  |
| DDR4    | 13       | 39.39%  |
| Unknown | 3        | 9.09%   |
| SDRAM   | 1        | 3.03%   |
| DDR2    | 1        | 3.03%   |
| DDR     | 1        | 3.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 31       | 96.88%  |
| SODIMM | 1        | 3.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 11       | 26.83%  |
| 16384 | 10       | 24.39%  |
| 4096  | 8        | 19.51%  |
| 2048  | 8        | 19.51%  |
| 32768 | 2        | 4.88%   |
| 1024  | 1        | 2.44%   |
| 256   | 1        | 2.44%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1333  | 9        | 22.5%   |
| 1600  | 7        | 17.5%   |
| 2667  | 4        | 10%     |
| 3600  | 3        | 7.5%    |
| 2400  | 3        | 7.5%    |
| 3000  | 2        | 5%      |
| 2133  | 2        | 5%      |
| 3733  | 1        | 2.5%    |
| 3500  | 1        | 2.5%    |
| 3400  | 1        | 2.5%    |
| 2933  | 1        | 2.5%    |
| 2666  | 1        | 2.5%    |
| 2176  | 1        | 2.5%    |
| 1867  | 1        | 2.5%    |
| 533   | 1        | 2.5%    |
| 333   | 1        | 2.5%    |
| 266   | 1        | 2.5%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Xerox              | 1        | 50%     |
| Brother Industries | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Xerox Phaser 3040 | 1        | 33.33%  |
| Brother DCP-T500W | 1        | 33.33%  |
| Brother DCP-T420W | 1        | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 110 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Logitech            | 7        | 46.67%  |
| Apple               | 2        | 13.33%  |
| Unknown             | 1        | 6.67%   |
| Sony                | 1        | 6.67%   |
| Samsung Electronics | 1        | 6.67%   |
| GEMBIRD             | 1        | 6.67%   |
| Aveo Technology     | 1        | 6.67%   |
| A4Tech              | 1        | 6.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Logitech Webcam C270            | 2        | 13.33%  |
| Apple iPhone 5/5C/5S/6/SE       | 2        | 13.33%  |
| Unknown HD camera               | 1        | 6.67%   |
| Sony CEVCECM                    | 1        | 6.67%   |
| Samsung Galaxy A5 (MTP)         | 1        | 6.67%   |
| Logitech Webcam C930e           | 1        | 6.67%   |
| Logitech Webcam C925e           | 1        | 6.67%   |
| Logitech Webcam C110            | 1        | 6.67%   |
| Logitech C922 Pro Stream Webcam | 1        | 6.67%   |
| Logitech C505e HD Webcam        | 1        | 6.67%   |
| GEMBIRD USB2.0 PC CAMERA        | 1        | 6.67%   |
| Aveo USB2.0 Camera              | 1        | 6.67%   |
| A4Tech REDRAGON Live Camera     | 1        | 6.67%   |

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

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 54       | 83.08%  |
| 1     | 9        | 13.85%  |
| 3     | 1        | 1.54%   |
| 2     | 1        | 1.54%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 7        | 53.85%  |
| Net/wireless             | 3        | 23.08%  |
| Unassigned class         | 1        | 7.69%   |
| Sound                    | 1        | 7.69%   |
| Communication controller | 1        | 7.69%   |

