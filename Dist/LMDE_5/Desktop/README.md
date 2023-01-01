LMDE 5 - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for LMDE 5.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 99

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Fujitsu   | D3003-S2 S26361-D3003-S2    | [cb55beafca](https://linux-hardware.org/?probe=cb55beafca) | Dec 30, 2022 |
| Fujitsu   | D3003-S2 S26361-D3003-S2    | [938db016a2](https://linux-hardware.org/?probe=938db016a2) | Dec 30, 2022 |
| ASUSTek   | Z170M-PLUS                  | [6b61c9a811](https://linux-hardware.org/?probe=6b61c9a811) | Dec 28, 2022 |
| Gigabyte  | GA-970A-D3                  | [82b0efdce8](https://linux-hardware.org/?probe=82b0efdce8) | Dec 25, 2022 |
| ASUSTek   | PRIME B350M-A               | [b03e4717c0](https://linux-hardware.org/?probe=b03e4717c0) | Dec 22, 2022 |
| Dell      | 0C27VV A01                  | [91c790d54e](https://linux-hardware.org/?probe=91c790d54e) | Dec 18, 2022 |
| MSI       | PRO B660M-A DDR4            | [770334f093](https://linux-hardware.org/?probe=770334f093) | Dec 16, 2022 |
| Dell      | 0T1D10 A01                  | [6988ab07fe](https://linux-hardware.org/?probe=6988ab07fe) | Dec 12, 2022 |
| Dell      | 0T1D10 A01                  | [6ec6d4563d](https://linux-hardware.org/?probe=6ec6d4563d) | Dec 12, 2022 |
| ASUSTek   | LEUCITE3                    | [b29a792d69](https://linux-hardware.org/?probe=b29a792d69) | Dec 12, 2022 |
| ASUSTek   | PRIME B450-PLUS             | [e810c5c2eb](https://linux-hardware.org/?probe=e810c5c2eb) | Dec 08, 2022 |
| ASUSTek   | P7P55D                      | [a1d27bfc48](https://linux-hardware.org/?probe=a1d27bfc48) | Dec 04, 2022 |
| SiYW      | V200 Series                 | [c80a75c310](https://linux-hardware.org/?probe=c80a75c310) | Dec 03, 2022 |
| HP        | 8299                        | [8f6b89bf07](https://linux-hardware.org/?probe=8f6b89bf07) | Nov 25, 2022 |
| Gigabyte  | GA-78LMT-USB3               | [1ad4dcb28a](https://linux-hardware.org/?probe=1ad4dcb28a) | Nov 22, 2022 |
| Gigabyte  | B450 I AORUS PRO WIFI-CF    | [f2a00a7bb3](https://linux-hardware.org/?probe=f2a00a7bb3) | Nov 21, 2022 |
| MSI       | MAG X570S TOMAHAWK MAX W... | [d93b2b9778](https://linux-hardware.org/?probe=d93b2b9778) | Nov 21, 2022 |
| MSI       | A320M-A PRO MAX             | [486c850cd6](https://linux-hardware.org/?probe=486c850cd6) | Nov 20, 2022 |
| Dell      | 0C27VV A01                  | [5e87654e7a](https://linux-hardware.org/?probe=5e87654e7a) | Nov 14, 2022 |
| ASUSTek   | M5A78L-M PLUS/USB3          | [95f38cc8d9](https://linux-hardware.org/?probe=95f38cc8d9) | Nov 12, 2022 |
| Dell      | 0C27VV A01                  | [9e5c4960c3](https://linux-hardware.org/?probe=9e5c4960c3) | Nov 10, 2022 |
| Dell      | 0C27VV A01                  | [a8c3b285d0](https://linux-hardware.org/?probe=a8c3b285d0) | Nov 10, 2022 |
| Dell      | 0N826N A03                  | [2126bcff1e](https://linux-hardware.org/?probe=2126bcff1e) | Nov 06, 2022 |
| MSI       | A320M-A PRO MAX             | [774861eae7](https://linux-hardware.org/?probe=774861eae7) | Oct 21, 2022 |
| HP        | 8299                        | [2b4c3924e4](https://linux-hardware.org/?probe=2b4c3924e4) | Oct 20, 2022 |
| HP        | 8299                        | [bf86078a8f](https://linux-hardware.org/?probe=bf86078a8f) | Oct 18, 2022 |
| Samsung   | DT1234567890 SEC_SW_REVI... | [19d09fb082](https://linux-hardware.org/?probe=19d09fb082) | Oct 17, 2022 |
| Samsung   | DT1234567890 SEC_SW_REVI... | [9f3307c5d0](https://linux-hardware.org/?probe=9f3307c5d0) | Oct 17, 2022 |
| Dell      | 0D735T A00                  | [20d0bc0836](https://linux-hardware.org/?probe=20d0bc0836) | Oct 12, 2022 |
| MSI       | B550-A PRO                  | [0526dffee9](https://linux-hardware.org/?probe=0526dffee9) | Oct 11, 2022 |
| AZW       | MINI S                      | [c5be5052a0](https://linux-hardware.org/?probe=c5be5052a0) | Oct 09, 2022 |
| ASUSTek   | Maximus VI HERO             | [2ee3173d51](https://linux-hardware.org/?probe=2ee3173d51) | Oct 08, 2022 |
| MSI       | B550-A PRO                  | [de85238b42](https://linux-hardware.org/?probe=de85238b42) | Oct 05, 2022 |
| ASRock    | A320M-HDV R4.0              | [b340ade9c9](https://linux-hardware.org/?probe=b340ade9c9) | Oct 05, 2022 |
| ASUSTek   | ROG CROSSHAIR VIII HERO     | [bc6ad9af3e](https://linux-hardware.org/?probe=bc6ad9af3e) | Oct 03, 2022 |
| Fujitsu   | D3062-A1 S26361-D3062-A1    | [3915f19817](https://linux-hardware.org/?probe=3915f19817) | Oct 03, 2022 |
| Acer      | Aspire XC-1660G V:1.1       | [f7f5368662](https://linux-hardware.org/?probe=f7f5368662) | Sep 28, 2022 |
| Acer      | Aspire XC-1660G V:1.1       | [fb983c65ac](https://linux-hardware.org/?probe=fb983c65ac) | Sep 28, 2022 |
| Dell      | 082WXT A01                  | [7b1ea76e92](https://linux-hardware.org/?probe=7b1ea76e92) | Sep 26, 2022 |
| Dell      | 082WXT A01                  | [7c4445ad04](https://linux-hardware.org/?probe=7c4445ad04) | Sep 26, 2022 |
| Gateway   | DX4870                      | [fd5b76e786](https://linux-hardware.org/?probe=fd5b76e786) | Sep 22, 2022 |
| Digiboard | NM70-TI                     | [84e21c8253](https://linux-hardware.org/?probe=84e21c8253) | Sep 21, 2022 |
| Dell      | 0XC837                      | [94ad27e346](https://linux-hardware.org/?probe=94ad27e346) | Sep 19, 2022 |
| MSI       | B360M MORTAR                | [cdcff8c15d](https://linux-hardware.org/?probe=cdcff8c15d) | Sep 18, 2022 |
| ASUSTek   | PRIME H610M-E D4            | [b8f2004ea5](https://linux-hardware.org/?probe=b8f2004ea5) | Sep 10, 2022 |
| Dell      | 0FJ030                      | [bf789b5c5f](https://linux-hardware.org/?probe=bf789b5c5f) | Sep 10, 2022 |
| MSI       | B450I GAMING PLUS AC        | [acbb191061](https://linux-hardware.org/?probe=acbb191061) | Sep 09, 2022 |
| Pegatron  | 2A9Eh                       | [2c7b59f70b](https://linux-hardware.org/?probe=2c7b59f70b) | Sep 08, 2022 |
| ASUSTek   | P8H77-V                     | [c92f578a36](https://linux-hardware.org/?probe=c92f578a36) | Sep 07, 2022 |
| ASUSTek   | ROG CROSSHAIR VIII HERO     | [9842cac1de](https://linux-hardware.org/?probe=9842cac1de) | Sep 04, 2022 |
| eMachines | EL1352G                     | [2547a277f7](https://linux-hardware.org/?probe=2547a277f7) | Sep 04, 2022 |
| ASUSTek   | P5K-E                       | [632cd1e47d](https://linux-hardware.org/?probe=632cd1e47d) | Sep 03, 2022 |
| Dell      | 042P49 A00                  | [31efc1e75f](https://linux-hardware.org/?probe=31efc1e75f) | Sep 01, 2022 |
| ASUSTek   | P5QPL-AM                    | [38e6481a65](https://linux-hardware.org/?probe=38e6481a65) | Aug 30, 2022 |
| Gigabyte  | B450M DS3H-CF               | [afde42fb41](https://linux-hardware.org/?probe=afde42fb41) | Aug 28, 2022 |
| Gigabyte  | B450M DS3H-CF               | [6c1db95864](https://linux-hardware.org/?probe=6c1db95864) | Aug 28, 2022 |
| MSI       | Z170A GAMING PRO            | [f86bc78c33](https://linux-hardware.org/?probe=f86bc78c33) | Aug 27, 2022 |
| MSI       | B85I                        | [454972a062](https://linux-hardware.org/?probe=454972a062) | Aug 19, 2022 |
| Gigabyte  | H97-Gaming 3                | [2d464fc182](https://linux-hardware.org/?probe=2d464fc182) | Aug 10, 2022 |
| Gigabyte  | B85M-DS3H-A                 | [527a0607d8](https://linux-hardware.org/?probe=527a0607d8) | Aug 08, 2022 |
| ASRock    | H61M-DGS                    | [683cd6273f](https://linux-hardware.org/?probe=683cd6273f) | Jul 30, 2022 |
| Gigabyte  | B450 AORUS M                | [fdaa3bac93](https://linux-hardware.org/?probe=fdaa3bac93) | Jul 20, 2022 |
| HP        | 8433 11                     | [85ecad964d](https://linux-hardware.org/?probe=85ecad964d) | Jul 17, 2022 |
| HP        | 8433 11                     | [7f6ec63dc8](https://linux-hardware.org/?probe=7f6ec63dc8) | Jul 17, 2022 |
| ASUSTek   | BM6820_BM6620_BP6320-8      | [8d8c845646](https://linux-hardware.org/?probe=8d8c845646) | Jul 17, 2022 |
| Gigabyte  | B450 AORUS M                | [12e48a7c0a](https://linux-hardware.org/?probe=12e48a7c0a) | Jul 06, 2022 |
| ASUSTek   | P8H77-M PRO                 | [efc2332724](https://linux-hardware.org/?probe=efc2332724) | Jul 02, 2022 |
| Dell      | 0XR1GT A00                  | [0d72ab6a71](https://linux-hardware.org/?probe=0d72ab6a71) | Jun 24, 2022 |
| Lenovo    | 3731 NOK                    | [efd1e69f79](https://linux-hardware.org/?probe=efd1e69f79) | Jun 09, 2022 |
| Lenovo    | 3731 NOK                    | [1da6b9f6c0](https://linux-hardware.org/?probe=1da6b9f6c0) | Jun 09, 2022 |
| Dell      | 0XR1GT A00                  | [8c3fd28612](https://linux-hardware.org/?probe=8c3fd28612) | Jun 08, 2022 |
| MSI       | MPG Z390 GAMING PRO CARB... | [6f8785bd56](https://linux-hardware.org/?probe=6f8785bd56) | May 30, 2022 |
| Lenovo    | MAHOBAY                     | [ba204646ba](https://linux-hardware.org/?probe=ba204646ba) | May 25, 2022 |
| Acer      | Seawolf                     | [dccbcb7ef3](https://linux-hardware.org/?probe=dccbcb7ef3) | May 25, 2022 |
| Intel     | DQ77MK AAG39642-400         | [f694bcfbc5](https://linux-hardware.org/?probe=f694bcfbc5) | May 21, 2022 |
| MSI       | X470 GAMING PLUS MAX        | [63950495b3](https://linux-hardware.org/?probe=63950495b3) | May 15, 2022 |
| MSI       | 970A-G43 PLUS               | [399deea7b9](https://linux-hardware.org/?probe=399deea7b9) | May 15, 2022 |
| Gigabyte  | Z68A-D3H-B3                 | [1441dfb79e](https://linux-hardware.org/?probe=1441dfb79e) | May 07, 2022 |
| HP        | 158B                        | [a613debdee](https://linux-hardware.org/?probe=a613debdee) | May 06, 2022 |
| HP        | 158B                        | [21f9c188f3](https://linux-hardware.org/?probe=21f9c188f3) | May 06, 2022 |
| HP        | 339A                        | [d58b95ebb1](https://linux-hardware.org/?probe=d58b95ebb1) | May 05, 2022 |
| Gigabyte  | H110M-S2H-CF                | [c45a37ce5d](https://linux-hardware.org/?probe=c45a37ce5d) | May 01, 2022 |
| ASUSTek   | PRIME H610M-A D4            | [e9376d24f0](https://linux-hardware.org/?probe=e9376d24f0) | Apr 29, 2022 |
| ASRock    | A320M-DGS                   | [b7df060840](https://linux-hardware.org/?probe=b7df060840) | Apr 19, 2022 |
| ASRock    | A320M-DGS                   | [70fe08376f](https://linux-hardware.org/?probe=70fe08376f) | Apr 19, 2022 |
| Dell      | 0CU568 A00                  | [b544c48421](https://linux-hardware.org/?probe=b544c48421) | Apr 19, 2022 |
| Dell      | 0CU568 A00                  | [84f7029c22](https://linux-hardware.org/?probe=84f7029c22) | Apr 19, 2022 |
| ASUSTek   | PRIME B350M-A               | [ed40a9ddc1](https://linux-hardware.org/?probe=ed40a9ddc1) | Apr 12, 2022 |
| ASUSTek   | PRIME B350M-A               | [9a137f0540](https://linux-hardware.org/?probe=9a137f0540) | Apr 12, 2022 |
| MSI       | Z170A GAMING M5             | [8f2e10cbf3](https://linux-hardware.org/?probe=8f2e10cbf3) | Apr 12, 2022 |
| Lenovo    | 312A SDK0J40697 WIN 3305... | [2a33f087e6](https://linux-hardware.org/?probe=2a33f087e6) | Apr 11, 2022 |
| Lenovo    | 312A SDK0J40697 WIN 3305... | [05b9ec80c6](https://linux-hardware.org/?probe=05b9ec80c6) | Apr 11, 2022 |
| Acer      | WG43M                       | [c7cb6ee141](https://linux-hardware.org/?probe=c7cb6ee141) | Apr 08, 2022 |
| ASUSTek   | P5G41T-M LX3                | [28371c08c2](https://linux-hardware.org/?probe=28371c08c2) | Apr 08, 2022 |
| MSI       | X470 GAMING PLUS MAX        | [9f1a76acb8](https://linux-hardware.org/?probe=9f1a76acb8) | Apr 06, 2022 |
| MSI       | X470 GAMING PLUS MAX        | [18a4ba3137](https://linux-hardware.org/?probe=18a4ba3137) | Apr 06, 2022 |
| ASUSTek   | P6T                         | [5ed6ed355f](https://linux-hardware.org/?probe=5ed6ed355f) | Apr 04, 2022 |
| ASUSTek   | PRIME H510M-D               | [1e0a28c8f3](https://linux-hardware.org/?probe=1e0a28c8f3) | Mar 28, 2022 |
| HP        | 0AE8h C                     | [d3980b5b59](https://linux-hardware.org/?probe=d3980b5b59) | Mar 14, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.0-12-amd64          | 15       | 20%     |
| 5.10.0-17-amd64          | 11       | 14.67%  |
| 5.10.0-14-amd64          | 10       | 13.33%  |
| 5.10.0-13-amd64          | 10       | 13.33%  |
| 5.10.0-18-amd64          | 9        | 12%     |
| 5.10.0-19-amd64          | 8        | 10.67%  |
| 5.10.0-20-amd64          | 4        | 5.33%   |
| 5.10.0-15-amd64          | 3        | 4%      |
| 5.10.0-16-amd64          | 2        | 2.67%   |
| 6.0.2-x64v2-rt11-xanmod1 | 1        | 1.33%   |
| 5.19.0-0.deb11.2-amd64   | 1        | 1.33%   |
| 5.10.0-13-686            | 1        | 1.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 69       | 97.18%  |
| 6.0.2   | 1        | 1.41%   |
| 5.19.0  | 1        | 1.41%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 69       | 97.18%  |
| 6.0     | 1        | 1.41%   |
| 5.19    | 1        | 1.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 70       | 98.59%  |
| i686   | 1        | 1.41%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| X-Cinnamon | 63       | 88.73%  |
| Cinnamon   | 5        | 7.04%   |
| XFCE       | 1        | 1.41%   |
| MATE       | 1        | 1.41%   |
| KDE5       | 1        | 1.41%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 71       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 49       | 69.01%  |
| LightDM | 20       | 28.17%  |
| SDDM    | 1        | 1.41%   |
| GDM     | 1        | 1.41%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 26       | 36.62%  |
| de_DE | 7        | 9.86%   |
| ru_RU | 6        | 8.45%   |
| pt_BR | 5        | 7.04%   |
| fr_FR | 4        | 5.63%   |
| it_IT | 3        | 4.23%   |
| en_CA | 3        | 4.23%   |
| sv_SE | 2        | 2.82%   |
| pl_PL | 2        | 2.82%   |
| es_ES | 2        | 2.82%   |
| en_GB | 2        | 2.82%   |
| sk_SK | 1        | 1.41%   |
| it_CH | 1        | 1.41%   |
| fr_CA | 1        | 1.41%   |
| es_NI | 1        | 1.41%   |
| en_ZA | 1        | 1.41%   |
| en_AU | 1        | 1.41%   |
| de_AT | 1        | 1.41%   |
| cs_CZ | 1        | 1.41%   |
| ar_EG | 1        | 1.41%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 42       | 59.15%  |
| EFI  | 29       | 40.85%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 65       | 91.55%  |
| Tmpfs   | 3        | 4.23%   |
| Btrfs   | 2        | 2.82%   |
| Overlay | 1        | 1.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 50       | 70.42%  |
| GPT     | 12       | 16.9%   |
| MBR     | 9        | 12.68%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 64       | 90.14%  |
| Yes       | 7        | 9.86%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 62       | 87.32%  |
| Yes       | 9        | 12.68%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 19       | 26.76%  |
| MSI                 | 10       | 14.08%  |
| Dell                | 10       | 14.08%  |
| Gigabyte Technology | 8        | 11.27%  |
| Hewlett-Packard     | 5        | 7.04%   |
| Lenovo              | 3        | 4.23%   |
| ASRock              | 3        | 4.23%   |
| Acer                | 3        | 4.23%   |
| Fujitsu             | 2        | 2.82%   |
| SiYW                | 1        | 1.41%   |
| Samsung Electronics | 1        | 1.41%   |
| Pegatron            | 1        | 1.41%   |
| Intel               | 1        | 1.41%   |
| Gateway             | 1        | 1.41%   |
| eMachines           | 1        | 1.41%   |
| Digiboard           | 1        | 1.41%   |
| AZW                 | 1        | 1.41%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS PRIME B350M-A                  | 2        | 2.82%   |
| SiYW V200 Series                    | 1        | 1.41%   |
| Samsung DeskTop System              | 1        | 1.41%   |
| Pegatron Pro 3015 Microtower PC     | 1        | 1.41%   |
| MSI MS-7D54                         | 1        | 1.41%   |
| MSI MS-7C52                         | 1        | 1.41%   |
| MSI MS-7B79                         | 1        | 1.41%   |
| MSI MS-7B23                         | 1        | 1.41%   |
| MSI MS-7B17                         | 1        | 1.41%   |
| MSI MS-7A40                         | 1        | 1.41%   |
| MSI MS-7984                         | 1        | 1.41%   |
| MSI MS-7977                         | 1        | 1.41%   |
| MSI MS-7974                         | 1        | 1.41%   |
| MSI MS-7851                         | 1        | 1.41%   |
| Lenovo V55t-15ARE 11KJ0036TX        | 1        | 1.41%   |
| Lenovo ThinkCentre M92p 3238E9U     | 1        | 1.41%   |
| Lenovo ThinkCentre M720s 10SUS9KW00 | 1        | 1.41%   |
| Intel DQ77MK AAG39642-400           | 1        | 1.41%   |
| HP Z820 Workstation                 | 1        | 1.41%   |
| HP Z600 Workstation                 | 1        | 1.41%   |
| HP Pavilion Desktop 590-p0xxx       | 1        | 1.41%   |
| HP EliteDesk 800 G3 SFF             | 1        | 1.41%   |
| HP Compaq Pro 6300 SFF              | 1        | 1.41%   |
| Gigabyte Z68A-D3H-B3                | 1        | 1.41%   |
| Gigabyte H110M-S2H                  | 1        | 1.41%   |
| Gigabyte GA-970A-D3                 | 1        | 1.41%   |
| Gigabyte GA-78LMT-USB3              | 1        | 1.41%   |
| Gigabyte B85M-DS3H-A                | 1        | 1.41%   |
| Gigabyte B450M DS3H                 | 1        | 1.41%   |
| Gigabyte B450 I AORUS PRO WIFI      | 1        | 1.41%   |
| Gigabyte B450 AORUS M               | 1        | 1.41%   |
| Gateway DX4870                      | 1        | 1.41%   |
| Fujitsu D3003-S2                    | 1        | 1.41%   |
| Fujitsu CELSIUS W410                | 1        | 1.41%   |
| eMachines EL1352G                   | 1        | 1.41%   |
| Digiboard NM70-TI                   | 1        | 1.41%   |
| Dell XPS A2010                      | 1        | 1.41%   |
| Dell Vostro 430                     | 1        | 1.41%   |
| Dell Vostro 3900                    | 1        | 1.41%   |
| Dell Precision WorkStation 670      | 1        | 1.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 6        | 8.45%   |
| Lenovo ThinkCentre     | 2        | 2.82%   |
| Gigabyte B450          | 2        | 2.82%   |
| Dell Vostro            | 2        | 2.82%   |
| Dell Precision         | 2        | 2.82%   |
| Dell OptiPlex          | 2        | 2.82%   |
| Dell Inspiron          | 2        | 2.82%   |
| Acer Aspire            | 2        | 2.82%   |
| SiYW V200              | 1        | 1.41%   |
| Samsung DeskTop        | 1        | 1.41%   |
| Pegatron Pro           | 1        | 1.41%   |
| MSI MS-7D54            | 1        | 1.41%   |
| MSI MS-7C52            | 1        | 1.41%   |
| MSI MS-7B79            | 1        | 1.41%   |
| MSI MS-7B23            | 1        | 1.41%   |
| MSI MS-7B17            | 1        | 1.41%   |
| MSI MS-7A40            | 1        | 1.41%   |
| MSI MS-7984            | 1        | 1.41%   |
| MSI MS-7977            | 1        | 1.41%   |
| MSI MS-7974            | 1        | 1.41%   |
| MSI MS-7851            | 1        | 1.41%   |
| Lenovo V55t-15ARE      | 1        | 1.41%   |
| Intel DQ77MK           | 1        | 1.41%   |
| HP Z820                | 1        | 1.41%   |
| HP Z600                | 1        | 1.41%   |
| HP Pavilion            | 1        | 1.41%   |
| HP EliteDesk           | 1        | 1.41%   |
| HP Compaq              | 1        | 1.41%   |
| Gigabyte Z68A-D3H-B3   | 1        | 1.41%   |
| Gigabyte H110M-S2H     | 1        | 1.41%   |
| Gigabyte GA-970A-D3    | 1        | 1.41%   |
| Gigabyte GA-78LMT-USB3 | 1        | 1.41%   |
| Gigabyte B85M-DS3H-A   | 1        | 1.41%   |
| Gigabyte B450M         | 1        | 1.41%   |
| Gateway DX4870         | 1        | 1.41%   |
| Fujitsu D3003-S2       | 1        | 1.41%   |
| Fujitsu CELSIUS        | 1        | 1.41%   |
| eMachines EL1352G      | 1        | 1.41%   |
| Digiboard NM70-TI      | 1        | 1.41%   |
| Dell XPS               | 1        | 1.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 12       | 16.9%   |
| 2012 | 11       | 15.49%  |
| 2015 | 6        | 8.45%   |
| 2009 | 6        | 8.45%   |
| 2017 | 5        | 7.04%   |
| 2021 | 4        | 5.63%   |
| 2011 | 4        | 5.63%   |
| 2010 | 4        | 5.63%   |
| 2022 | 3        | 4.23%   |
| 2019 | 3        | 4.23%   |
| 2013 | 3        | 4.23%   |
| 2006 | 3        | 4.23%   |
| 2016 | 2        | 2.82%   |
| 2007 | 2        | 2.82%   |
| 2020 | 1        | 1.41%   |
| 2014 | 1        | 1.41%   |
| 2008 | 1        | 1.41%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 71       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 71       | 98.61%  |
| Enabled  | 1        | 1.39%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 71       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 18       | 25%     |
| 16.01-24.0  | 17       | 23.61%  |
| 4.01-8.0    | 13       | 18.06%  |
| 32.01-64.0  | 10       | 13.89%  |
| 3.01-4.0    | 6        | 8.33%   |
| 24.01-32.0  | 3        | 4.17%   |
| 1.01-2.0    | 3        | 4.17%   |
| 64.01-256.0 | 1        | 1.39%   |
| 0.51-1.0    | 1        | 1.39%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 27       | 36.99%  |
| 2.01-3.0  | 21       | 28.77%  |
| 4.01-8.0  | 12       | 16.44%  |
| 3.01-4.0  | 8        | 10.96%  |
| 0.51-1.0  | 3        | 4.11%   |
| 8.01-16.0 | 2        | 2.74%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 31       | 43.66%  |
| 2      | 17       | 23.94%  |
| 3      | 13       | 18.31%  |
| 4      | 5        | 7.04%   |
| 5      | 3        | 4.23%   |
| 6      | 2        | 2.82%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 37       | 52.11%  |
| Yes       | 34       | 47.89%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 70       | 98.59%  |
| No        | 1        | 1.41%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 41       | 57.75%  |
| Yes       | 30       | 42.25%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 52       | 73.24%  |
| Yes       | 19       | 26.76%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 18       | 25.35%  |
| Russia       | 7        | 9.86%   |
| Germany      | 7        | 9.86%   |
| Brazil       | 6        | 8.45%   |
| Italy        | 5        | 7.04%   |
| France       | 5        | 7.04%   |
| Canada       | 4        | 5.63%   |
| Sweden       | 3        | 4.23%   |
| UK           | 2        | 2.82%   |
| Spain        | 2        | 2.82%   |
| Poland       | 2        | 2.82%   |
| Australia    | 2        | 2.82%   |
| Venezuela    | 1        | 1.41%   |
| Turkey       | 1        | 1.41%   |
| South Africa | 1        | 1.41%   |
| Slovakia     | 1        | 1.41%   |
| Nicaragua    | 1        | 1.41%   |
| Mexico       | 1        | 1.41%   |
| Latvia       | 1        | 1.41%   |
| Austria      | 1        | 1.41%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Melbourne                | 2        | 2.74%   |
| Frankfurt am Main        | 2        | 2.74%   |
| Washington               | 1        | 1.37%   |
| Volta Redonda            | 1        | 1.37%   |
| Vitória da Conquista    | 1        | 1.37%   |
| Vincennes                | 1        | 1.37%   |
| Vicente Guerrero         | 1        | 1.37%   |
| Ulyanovsk                | 1        | 1.37%   |
| Trieste                  | 1        | 1.37%   |
| Tolyatti                 | 1        | 1.37%   |
| Toledo                   | 1        | 1.37%   |
| Toccoa                   | 1        | 1.37%   |
| Tacoma                   | 1        | 1.37%   |
| Stockelsdorf             | 1        | 1.37%   |
| Stockbridge              | 1        | 1.37%   |
| Spruce Grove             | 1        | 1.37%   |
| Sollentuna               | 1        | 1.37%   |
| Schruns                  | 1        | 1.37%   |
| Sant Feliu de Llobregat  | 1        | 1.37%   |
| San Antonio de Los Altos | 1        | 1.37%   |
| San Antonio              | 1        | 1.37%   |
| Rome                     | 1        | 1.37%   |
| Riga                     | 1        | 1.37%   |
| Reynoldsburg             | 1        | 1.37%   |
| Rennes                   | 1        | 1.37%   |
| Queensbury               | 1        | 1.37%   |
| Prestatyn                | 1        | 1.37%   |
| Porto Uniao              | 1        | 1.37%   |
| Porto Alegre             | 1        | 1.37%   |
| Piaseczno                | 1        | 1.37%   |
| Pensacola                | 1        | 1.37%   |
| Oxford                   | 1        | 1.37%   |
| Orekhovo-Zuyevo          | 1        | 1.37%   |
| North Manchester         | 1        | 1.37%   |
| Nitra                    | 1        | 1.37%   |
| National City            | 1        | 1.37%   |
| Naples                   | 1        | 1.37%   |
| Moscow                   | 1        | 1.37%   |
| Montreal                 | 1        | 1.37%   |
| Milan                    | 1        | 1.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 25       | 37     | 20.83%  |
| Seagate             | 23       | 31     | 19.17%  |
| Samsung Electronics | 17       | 31     | 14.17%  |
| Kingston            | 10       | 11     | 8.33%   |
| Crucial             | 7        | 7      | 5.83%   |
| SanDisk             | 6        | 6      | 5%      |
| Toshiba             | 5        | 5      | 4.17%   |
| Hitachi             | 5        | 6      | 4.17%   |
| SK hynix            | 2        | 3      | 1.67%   |
| A-DATA Technology   | 2        | 2      | 1.67%   |
| XrayDisk            | 1        | 2      | 0.83%   |
| Transcend           | 1        | 2      | 0.83%   |
| SPCC                | 1        | 1      | 0.83%   |
| Phison Electronics  | 1        | 1      | 0.83%   |
| OCZ-VERTEX          | 1        | 1      | 0.83%   |
| Netac               | 1        | 1      | 0.83%   |
| Intenso             | 1        | 1      | 0.83%   |
| Intel               | 1        | 1      | 0.83%   |
| Hewlett-Packard     | 1        | 1      | 0.83%   |
| GOODRAM             | 1        | 1      | 0.83%   |
| Gigabyte Technology | 1        | 2      | 0.83%   |
| China               | 1        | 1      | 0.83%   |
| BR                  | 1        | 1      | 0.83%   |
| ASMedia             | 1        | 1      | 0.83%   |
| Apple               | 1        | 1      | 0.83%   |
| Apacer              | 1        | 1      | 0.83%   |
| 2.5''               | 1        | 1      | 0.83%   |
| Unknown             | 1        | 2      | 0.83%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB        | 5        | 3.6%    |
| Samsung SSD 850 EVO 500GB        | 3        | 2.16%   |
| Kingston SA400S37240G 240GB SSD  | 3        | 2.16%   |
| Crucial CT480BX500SSD1 480GB     | 3        | 2.16%   |
| WDC WD10EZEX-08WN4A0 1TB         | 2        | 1.44%   |
| Seagate ST3320418AS 320GB        | 2        | 1.44%   |
| Seagate ST3250318AS 250GB        | 2        | 1.44%   |
| Seagate ST2000DM008-2FR102 2TB   | 2        | 1.44%   |
| Seagate ST1000DM003-1CH162 1TB   | 2        | 1.44%   |
| Samsung NVMe SSD Drive 500GB     | 2        | 1.44%   |
| Samsung NVMe SSD Drive 250GB     | 2        | 1.44%   |
| Kingston SA400S37120G 120GB SSD  | 2        | 1.44%   |
| XrayDisk 480GB                   | 1        | 0.72%   |
| XrayDisk 1TB                     | 1        | 0.72%   |
| WDC WDS500G2B0B-00YS70 500GB SSD | 1        | 0.72%   |
| WDC WD60EZAZ-00ZGHB0 6TB         | 1        | 0.72%   |
| WDC WD5000LPSX-08A6W 500GB       | 1        | 0.72%   |
| WDC WD5000AZLX-08K2TA0 500GB     | 1        | 0.72%   |
| WDC WD5000AAKX-75U6AA0 500GB     | 1        | 0.72%   |
| WDC WD5000AAKX-22ERMA0 500GB     | 1        | 0.72%   |
| WDC WD5000AAJS-00TKA0 500GB      | 1        | 0.72%   |
| WDC WD40EZAZ-00SF3B0 4TB         | 1        | 0.72%   |
| WDC WD3200AAJS-22B4A0 320GB      | 1        | 0.72%   |
| WDC WD30EZRZ-00Z5HB0 3TB         | 1        | 0.72%   |
| WDC WD30EFRX-68EUZN0 3TB         | 1        | 0.72%   |
| WDC WD3003FZEX-00Z4SA0 3TB       | 1        | 0.72%   |
| WDC WD20SPZX-00UA7T0 2TB         | 1        | 0.72%   |
| WDC WD1600HLHX-60JJPV1 160GB     | 1        | 0.72%   |
| WDC WD1600AAJS-07PSA0 160GB      | 1        | 0.72%   |
| WDC WD10SPZX-21Z10T0 1TB         | 1        | 0.72%   |
| WDC WD10JPVX-75JC3T0 1TB         | 1        | 0.72%   |
| WDC WD10EZRX-00DC0B0 1TB         | 1        | 0.72%   |
| WDC WD10EZEX-75M2NA0 1TB         | 1        | 0.72%   |
| WDC WD10EZEX-22BN5A0 1TB         | 1        | 0.72%   |
| WDC WD10EFRX-68JCSN0 1TB         | 1        | 0.72%   |
| WDC WD10EFRX-68FYTN0 1TB         | 1        | 0.72%   |
| WDC WD10EAVS-00D7B0 1TB          | 1        | 0.72%   |
| WDC WD10EALX-009BA0 1TB          | 1        | 0.72%   |
| WDC WD10EACS-00D6B0 1TB          | 1        | 0.72%   |
| WDC WD1003FZEX-00MK2A0 1TB       | 1        | 0.72%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 24       | 36     | 39.34%  |
| Seagate             | 23       | 30     | 37.7%   |
| Hitachi             | 5        | 6      | 8.2%    |
| Toshiba             | 4        | 4      | 6.56%   |
| Samsung Electronics | 3        | 3      | 4.92%   |
| Intenso             | 1        | 1      | 1.64%   |
| ASMedia             | 1        | 1      | 1.64%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 11       | 17     | 22.92%  |
| Kingston            | 8        | 9      | 16.67%  |
| Crucial             | 7        | 7      | 14.58%  |
| SanDisk             | 5        | 5      | 10.42%  |
| A-DATA Technology   | 2        | 2      | 4.17%   |
| WDC                 | 1        | 1      | 2.08%   |
| Transcend           | 1        | 2      | 2.08%   |
| Toshiba             | 1        | 1      | 2.08%   |
| SPCC                | 1        | 1      | 2.08%   |
| SK hynix            | 1        | 1      | 2.08%   |
| OCZ-VERTEX          | 1        | 1      | 2.08%   |
| Netac               | 1        | 1      | 2.08%   |
| Hewlett-Packard     | 1        | 1      | 2.08%   |
| GOODRAM             | 1        | 1      | 2.08%   |
| Gigabyte Technology | 1        | 2      | 2.08%   |
| China               | 1        | 1      | 2.08%   |
| Apple               | 1        | 1      | 2.08%   |
| Apacer              | 1        | 1      | 2.08%   |
| 2.5''               | 1        | 1      | 2.08%   |
| Unknown             | 1        | 2      | 2.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 51       | 81     | 47.22%  |
| SSD     | 42       | 58     | 38.89%  |
| NVMe    | 12       | 18     | 11.11%  |
| Unknown | 3        | 4      | 2.78%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 69       | 135    | 80.23%  |
| NVMe | 12       | 18     | 13.95%  |
| SAS  | 5        | 8      | 5.81%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 53       | 81     | 57.61%  |
| 0.51-1.0   | 24       | 38     | 26.09%  |
| 1.01-2.0   | 8        | 10     | 8.7%    |
| 2.01-3.0   | 3        | 6      | 3.26%   |
| 4.01-10.0  | 3        | 3      | 3.26%   |
| 3.01-4.0   | 1        | 1      | 1.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 16       | 22.54%  |
| 101-250        | 14       | 19.72%  |
| 1001-2000      | 13       | 18.31%  |
| 501-1000       | 10       | 14.08%  |
| More than 3000 | 6        | 8.45%   |
| 2001-3000      | 4        | 5.63%   |
| 1-20           | 4        | 5.63%   |
| 51-100         | 3        | 4.23%   |
| 21-50          | 1        | 1.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 24       | 33.33%  |
| 21-50          | 11       | 15.28%  |
| 251-500        | 8        | 11.11%  |
| 501-1000       | 8        | 11.11%  |
| 51-100         | 7        | 9.72%   |
| 1001-2000      | 6        | 8.33%   |
| 101-250        | 5        | 6.94%   |
| More than 3000 | 2        | 2.78%   |
| 2001-3000      | 1        | 1.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB | 1        | 1      | 33.33%  |
| Seagate ST3250318AS 250GB       | 1        | 1      | 33.33%  |
| Seagate ST2000DX001-1CM164 2TB  | 1        | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 3        | 3      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 3        | 3      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 3        | 3      | 100%    |

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
| Detected | 53       | 112    | 68.83%  |
| Works    | 21       | 46     | 27.27%  |
| Malfunc  | 3        | 3      | 3.9%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 50       | 53.76%  |
| AMD                         | 20       | 21.51%  |
| Samsung Electronics         | 6        | 6.45%   |
| JMicron Technology          | 3        | 3.23%   |
| ASMedia Technology          | 3        | 3.23%   |
| Nvidia                      | 2        | 2.15%   |
| Kingston Technology Company | 2        | 2.15%   |
| Broadcom / LSI              | 2        | 2.15%   |
| SK hynix                    | 1        | 1.08%   |
| SanDisk                     | 1        | 1.08%   |
| Phison Electronics          | 1        | 1.08%   |
| Marvell Technology Group    | 1        | 1.08%   |
| LSI Logic / Symbios Logic   | 1        | 1.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 12       | 9.92%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6        | 4.96%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6        | 4.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5        | 4.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 4.13%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 3.31%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 3.31%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 4        | 3.31%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 3        | 2.48%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 2.48%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 2.48%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 2.48%   |
| AMD FCH SATA Controller D                                                               | 3        | 2.48%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 2.48%   |
| Kingston Company Company Non-Volatile memory controller                                 | 2        | 1.65%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2        | 1.65%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 1.65%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2        | 1.65%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 1.65%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 1.65%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2        | 1.65%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 1.65%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 1.65%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 1.65%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 1.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 1.65%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 1.65%   |
| SK hynix BC511                                                                          | 1        | 0.83%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 0.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.83%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.83%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 0.83%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                            | 1        | 0.83%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 0.83%   |
| Nvidia MCP61 IDE                                                                        | 1        | 0.83%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                                   | 1        | 0.83%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2008 [Falcon]                                    | 1        | 0.83%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1        | 0.83%   |
| Intel SSD 600P Series                                                                   | 1        | 0.83%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 0.83%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 61       | 62.24%  |
| IDE  | 18       | 18.37%  |
| NVMe | 12       | 12.24%  |
| RAID | 5        | 5.1%    |
| SAS  | 1        | 1.02%   |
| SCSI | 1        | 1.02%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 49       | 69.01%  |
| AMD    | 22       | 30.99%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 4        | 5.63%   |
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz         | 2        | 2.82%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2        | 2.82%   |
| Intel Pentium CPU G645 @ 2.90GHz            | 2        | 2.82%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 2        | 2.82%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 2.82%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 2.82%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 2        | 2.82%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2        | 2.82%   |
| AMD Ryzen 5 3350G with Radeon Vega Graphics | 2        | 2.82%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 2        | 2.82%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2        | 2.82%   |
| Intel Xeon CPU X5675 @ 3.07GHz              | 1        | 1.41%   |
| Intel Xeon CPU X5570 @ 2.93GHz              | 1        | 1.41%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz         | 1        | 1.41%   |
| Intel Xeon CPU 3.40GHz                      | 1        | 1.41%   |
| Intel Pentium Gold G7400                    | 1        | 1.41%   |
| Intel Pentium D CPU 3.40GHz                 | 1        | 1.41%   |
| Intel Pentium D CPU 2.80GHz                 | 1        | 1.41%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 1.41%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1        | 1.41%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 1.41%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 1.41%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1        | 1.41%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 1.41%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 1.41%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 1.41%   |
| Intel Core i5-3470S CPU @ 2.90GHz           | 1        | 1.41%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 1        | 1.41%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 1.41%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 1.41%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1        | 1.41%   |
| Intel Core i3-4340 CPU @ 3.60GHz            | 1        | 1.41%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1        | 1.41%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1        | 1.41%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz       | 1        | 1.41%   |
| Intel Core 2 Quad CPU Q6700 @ 2.66GHz       | 1        | 1.41%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 1        | 1.41%   |
| Intel Core 2 CPU 4300 @ 1.80GHz             | 1        | 1.41%   |
| Intel Celeron N5095 @ 2.00GHz               | 1        | 1.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 13       | 18.31%  |
| Intel Core i7           | 11       | 15.49%  |
| Intel Xeon              | 6        | 8.45%   |
| AMD Ryzen 5             | 6        | 8.45%   |
| AMD Ryzen 3             | 4        | 5.63%   |
| Intel Pentium           | 3        | 4.23%   |
| Intel Core 2 Quad       | 3        | 4.23%   |
| AMD Ryzen 7             | 3        | 4.23%   |
| Other                   | 2        | 2.82%   |
| Intel Pentium Dual-Core | 2        | 2.82%   |
| Intel Pentium D         | 2        | 2.82%   |
| Intel Core i3           | 2        | 2.82%   |
| Intel Celeron           | 2        | 2.82%   |
| AMD FX                  | 2        | 2.82%   |
| AMD Athlon II X2        | 2        | 2.82%   |
| Intel Pentium Gold      | 1        | 1.41%   |
| Intel Core 2 Duo        | 1        | 1.41%   |
| Intel Core 2            | 1        | 1.41%   |
| AMD Ryzen 9             | 1        | 1.41%   |
| AMD Phenom II X6        | 1        | 1.41%   |
| AMD Phenom II X4        | 1        | 1.41%   |
| AMD G                   | 1        | 1.41%   |
| AMD Athlon              | 1        | 1.41%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 36       | 50.7%   |
| 2      | 19       | 26.76%  |
| 6      | 7        | 9.86%   |
| 8      | 6        | 8.45%   |
| 16     | 3        | 4.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 67       | 94.37%  |
| 2      | 4        | 5.63%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 38       | 53.52%  |
| 2      | 33       | 46.48%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 71       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306a9    | 8        | 11.27%  |
| 0x206a7    | 6        | 8.45%   |
| 0x08108109 | 5        | 7.04%   |
| 0x506e3    | 4        | 5.63%   |
| 0x306c3    | 4        | 5.63%   |
| 0x1067a    | 4        | 5.63%   |
| Unknown    | 3        | 4.23%   |
| 0x906ed    | 2        | 2.82%   |
| 0x90675    | 2        | 2.82%   |
| 0x206d7    | 2        | 2.82%   |
| 0x106e5    | 2        | 2.82%   |
| 0x08701021 | 2        | 2.82%   |
| 0x08101016 | 2        | 2.82%   |
| 0x010000c8 | 2        | 2.82%   |
| 0xf65      | 1        | 1.41%   |
| 0xf47      | 1        | 1.41%   |
| 0xf43      | 1        | 1.41%   |
| 0xa0671    | 1        | 1.41%   |
| 0xa0653    | 1        | 1.41%   |
| 0x906ea    | 1        | 1.41%   |
| 0x906e9    | 1        | 1.41%   |
| 0x906c0    | 1        | 1.41%   |
| 0x806ea    | 1        | 1.41%   |
| 0x6fd      | 1        | 1.41%   |
| 0x6fb      | 1        | 1.41%   |
| 0x6f2      | 1        | 1.41%   |
| 0x206c2    | 1        | 1.41%   |
| 0x106a5    | 1        | 1.41%   |
| 0x0a50000b | 1        | 1.41%   |
| 0x0a20120a | 1        | 1.41%   |
| 0x0810100b | 1        | 1.41%   |
| 0x0800820d | 1        | 1.41%   |
| 0x08001137 | 1        | 1.41%   |
| 0x08001129 | 1        | 1.41%   |
| 0x06000852 | 1        | 1.41%   |
| 0x0600063d | 1        | 1.41%   |
| 0x05000119 | 1        | 1.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| IvyBridge   | 9        | 12.68%  |
| SandyBridge | 8        | 11.27%  |
| Zen+        | 6        | 8.45%   |
| Zen         | 5        | 7.04%   |
| KabyLake    | 5        | 7.04%   |
| Skylake     | 4        | 5.63%   |
| Penryn      | 4        | 5.63%   |
| K10         | 4        | 5.63%   |
| Haswell     | 4        | 5.63%   |
| NetBurst    | 3        | 4.23%   |
| Nehalem     | 3        | 4.23%   |
| Core        | 3        | 4.23%   |
| Unknown     | 3        | 4.23%   |
| Zen 3       | 2        | 2.82%   |
| Zen 2       | 2        | 2.82%   |
| Westmere    | 1        | 1.41%   |
| Tremont     | 1        | 1.41%   |
| Piledriver  | 1        | 1.41%   |
| CometLake   | 1        | 1.41%   |
| Bulldozer   | 1        | 1.41%   |
| Bobcat      | 1        | 1.41%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 42       | 53.85%  |
| Intel  | 18       | 23.08%  |
| AMD    | 18       | 23.08%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 5        | 6.33%   |
| Nvidia GT218 [GeForce 210]                                                  | 4        | 5.06%   |
| Nvidia GK208B [GeForce GT 730]                                              | 4        | 5.06%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 5.06%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4        | 5.06%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 3.8%    |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 3.8%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 3.8%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 3.8%    |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 2.53%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 1.27%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.27%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 1.27%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 1        | 1.27%   |
| Nvidia GP107GL [Quadro P620]                                                | 1        | 1.27%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 1.27%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.27%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.27%   |
| Nvidia GM107GL [Quadro K620]                                                | 1        | 1.27%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.27%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 1.27%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1        | 1.27%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 1.27%   |
| Nvidia GF119 [NVS 310]                                                      | 1        | 1.27%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 1.27%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                           | 1        | 1.27%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 1        | 1.27%   |
| Nvidia G92 [GeForce GTS 250]                                                | 1        | 1.27%   |
| Nvidia G92 [GeForce 8800 GT]                                                | 1        | 1.27%   |
| Nvidia G72 [GeForce 7500 LE]                                                | 1        | 1.27%   |
| Nvidia G72 [GeForce 7300 LE]                                                | 1        | 1.27%   |
| Nvidia C78 [GeForce 9100]                                                   | 1        | 1.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 1.27%   |
| Intel UHD Graphics 620                                                      | 1        | 1.27%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 1        | 1.27%   |
| Intel JasperLake [UHD Graphics]                                             | 1        | 1.27%   |
| Intel HD Graphics 630                                                       | 1        | 1.27%   |
| Intel HD Graphics 530                                                       | 1        | 1.27%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.27%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 1.27%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 39       | 53.42%  |
| 1 x Intel      | 15       | 20.55%  |
| 1 x AMD        | 13       | 17.81%  |
| AMD + Nvidia   | 3        | 4.11%   |
| 2 x AMD        | 1        | 1.37%   |
| Intel + Nvidia | 1        | 1.37%   |
| Intel + AMD    | 1        | 1.37%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 47       | 66.2%   |
| Proprietary | 17       | 23.94%  |
| Unknown     | 7        | 9.86%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 21       | 29.17%  |
| 1.01-2.0   | 20       | 27.78%  |
| 0.01-0.5   | 10       | 13.89%  |
| 3.01-4.0   | 9        | 12.5%   |
| 0.51-1.0   | 6        | 8.33%   |
| 7.01-8.0   | 2        | 2.78%   |
| 5.01-6.0   | 2        | 2.78%   |
| 2.01-3.0   | 1        | 1.39%   |
| 8.01-16.0  | 1        | 1.39%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 8        | 11.94%  |
| Acer                 | 7        | 10.45%  |
| Hewlett-Packard      | 6        | 8.96%   |
| Goldstar             | 6        | 8.96%   |
| Dell                 | 6        | 8.96%   |
| BenQ                 | 6        | 8.96%   |
| Philips              | 5        | 7.46%   |
| Unknown              | 3        | 4.48%   |
| AOC                  | 3        | 4.48%   |
| Ancor Communications | 3        | 4.48%   |
| Iiyama               | 2        | 2.99%   |
| ___                  | 1        | 1.49%   |
| ViewSonic            | 1        | 1.49%   |
| Sony                 | 1        | 1.49%   |
| SKY                  | 1        | 1.49%   |
| PLN                  | 1        | 1.49%   |
| Medion               | 1        | 1.49%   |
| Lenovo Group Limited | 1        | 1.49%   |
| Lenovo               | 1        | 1.49%   |
| Insignia             | 1        | 1.49%   |
| HannStar             | 1        | 1.49%   |
| ASUSTek Computer     | 1        | 1.49%   |
| Unknown              | 1        | 1.49%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch              | 2        | 2.78%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 2        | 2.78%   |
| ___ LCDTV16 ___0101 1920x1080                                        | 1        | 1.39%   |
| ViewSonic VG2230wm VSCA21E 1680x1050 474x296mm 22.0-inch             | 1        | 1.39%   |
| Unknown LCDTV14 0101 1360x768 1600x900mm 72.3-inch                   | 1        | 1.39%   |
| Unknown LCD Monitor SAMSUNG 1366x768                                 | 1        | 1.39%   |
| Unknown LCD Monitor SAMSUNG                                          | 1        | 1.39%   |
| Sony LCD Monitor TV 3840x1080                                        | 1        | 1.39%   |
| SKY TV-monitor SKY1402 3840x2160 708x398mm 32.0-inch                 | 1        | 1.39%   |
| SKY TV SKY1502 3840x2160 1150x650mm 52.0-inch                        | 1        | 1.39%   |
| Samsung Electronics SyncMaster SAM0259 1280x1024 376x301mm 19.0-inch | 1        | 1.39%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch   | 1        | 1.39%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch    | 1        | 1.39%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                 | 1        | 1.39%   |
| Samsung Electronics LCD Monitor SMBX2331 1920x1080                   | 1        | 1.39%   |
| Samsung Electronics LCD Monitor S27R65 3840x1080                     | 1        | 1.39%   |
| Samsung Electronics LCD Monitor S27R65                               | 1        | 1.39%   |
| Samsung Electronics LCD Monitor C27F390                              | 1        | 1.39%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch   | 1        | 1.39%   |
| PLN LCD Monitor PXL2790MW 1920x1080                                  | 1        | 1.39%   |
| Philips PHL BDM3270 PHL08E7 2560x1440 708x398mm 32.0-inch            | 1        | 1.39%   |
| Philips LCD Monitor PHL 242V8 1920x1080                              | 1        | 1.39%   |
| Philips 244E PHLC036 1920x1080 521x293mm 23.5-inch                   | 1        | 1.39%   |
| Medion MD20328 MED3942 1600x900 462x272mm 21.1-inch                  | 1        | 1.39%   |
| Lenovo Group Limited LCD Monitor LEN G32qc-10 4480x1440              | 1        | 1.39%   |
| Lenovo C24-20 LEN62A8 1920x1080 527x296mm 23.8-inch                  | 1        | 1.39%   |
| Insignia DX19LD150A11 BBY1943 1360x768 409x230mm 18.5-inch           | 1        | 1.39%   |
| Iiyama PLE2207WS IVM5609 1680x1050 474x296mm 22.0-inch               | 1        | 1.39%   |
| Iiyama PL2792H IVM664F 1920x1080 598x336mm 27.0-inch                 | 1        | 1.39%   |
| Hewlett-Packard w2216 HWP280B 1680x1050 465x291mm 21.6-inch          | 1        | 1.39%   |
| Hewlett-Packard W2072a HWP3000 1600x900 443x249mm 20.0-inch          | 1        | 1.39%   |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch         | 1        | 1.39%   |
| Hewlett-Packard E232 HWP327B 1920x1080 509x286mm 23.0-inch           | 1        | 1.39%   |
| Hewlett-Packard E232 HWP327A 1920x1080 509x286mm 23.0-inch           | 1        | 1.39%   |
| Hewlett-Packard E232 HWP3279 1920x1080 509x286mm 23.0-inch           | 1        | 1.39%   |
| Hewlett-Packard 27f HPN354B 1920x1080 598x336mm 27.0-inch            | 1        | 1.39%   |
| Hewlett-Packard 24y HPN3504 1920x1080 528x297mm 23.9-inch            | 1        | 1.39%   |
| HannStar HU151 HSD5555 1024x768 304x228mm 15.0-inch                  | 1        | 1.39%   |
| Goldstar ULTRAWIDE GSM7770 2560x1080 798x334mm 34.1-inch             | 1        | 1.39%   |
| Goldstar LG ULTRAGEAR GSM5B7F 2560x1440 600x340mm 27.2-inch          | 1        | 1.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 27       | 43.55%  |
| 1680x1050 (WSXGA+) | 7        | 11.29%  |
| 3840x2160 (4K)     | 3        | 4.84%   |
| 2560x1440 (QHD)    | 3        | 4.84%   |
| 1600x900 (HD+)     | 3        | 4.84%   |
| Unknown            | 3        | 4.84%   |
| 3840x1080          | 2        | 3.23%   |
| 2560x1080          | 2        | 3.23%   |
| 1440x900 (WXGA+)   | 2        | 3.23%   |
| 1366x768 (WXGA)    | 2        | 3.23%   |
| 1360x768           | 2        | 3.23%   |
| 1280x1024 (SXGA)   | 2        | 3.23%   |
| 4480x1440          | 1        | 1.61%   |
| 3440x1440          | 1        | 1.61%   |
| 1920x1200 (WUXGA)  | 1        | 1.61%   |
| 1024x768 (XGA)     | 1        | 1.61%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 14       | 21.54%  |
| 21      | 9        | 13.85%  |
| 27      | 7        | 10.77%  |
| 24      | 7        | 10.77%  |
| 23      | 5        | 7.69%   |
| 22      | 4        | 6.15%   |
| 20      | 3        | 4.62%   |
| 19      | 3        | 4.62%   |
| 34      | 2        | 3.08%   |
| 32      | 2        | 3.08%   |
| 18      | 2        | 3.08%   |
| 72      | 1        | 1.54%   |
| 52      | 1        | 1.54%   |
| 31      | 1        | 1.54%   |
| 28      | 1        | 1.54%   |
| 25      | 1        | 1.54%   |
| 17      | 1        | 1.54%   |
| 15      | 1        | 1.54%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 19       | 31.15%  |
| 401-500     | 16       | 26.23%  |
| Unknown     | 14       | 22.95%  |
| 701-800     | 4        | 6.56%   |
| 351-400     | 3        | 4.92%   |
| 601-700     | 2        | 3.28%   |
| 301-350     | 1        | 1.64%   |
| 1501-2000   | 1        | 1.64%   |
| 1001-1500   | 1        | 1.64%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 29       | 50.88%  |
| Unknown | 14       | 24.56%  |
| 16/10   | 8        | 14.04%  |
| 21/9    | 3        | 5.26%   |
| 5/4     | 2        | 3.51%   |
| 4/3     | 1        | 1.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 23       | 35.94%  |
| Unknown        | 14       | 21.88%  |
| 301-350        | 7        | 10.94%  |
| 151-200        | 6        | 9.38%   |
| 351-500        | 5        | 7.81%   |
| 251-300        | 3        | 4.69%   |
| More than 1000 | 2        | 3.13%   |
| 141-150        | 2        | 3.13%   |
| 131-140        | 1        | 1.56%   |
| 101-110        | 1        | 1.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 37       | 59.68%  |
| Unknown | 14       | 22.58%  |
| 101-120 | 9        | 14.52%  |
| 1-50    | 1        | 1.61%   |
| 121-160 | 1        | 1.61%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 51       | 71.83%  |
| 2     | 12       | 16.9%   |
| 0     | 6        | 8.45%   |
| 3     | 2        | 2.82%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 42       | 42%     |
| Intel                    | 32       | 32%     |
| Qualcomm Atheros         | 7        | 7%      |
| Ralink Technology        | 3        | 3%      |
| Broadcom                 | 3        | 3%      |
| Samsung Electronics      | 2        | 2%      |
| Nvidia                   | 2        | 2%      |
| Huawei Technologies      | 2        | 2%      |
| TP-Link                  | 1        | 1%      |
| Qualcomm                 | 1        | 1%      |
| NetGear                  | 1        | 1%      |
| Mercucys                 | 1        | 1%      |
| Marvell Technology Group | 1        | 1%      |
| HTC (High Tech Computer) | 1        | 1%      |
| Belkin Components        | 1        | 1%      |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 33       | 28.7%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 7        | 6.09%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 4        | 3.48%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 3        | 2.61%   |
| Intel Ethernet Connection (7) I219-V                                                          | 3        | 2.61%   |
| Samsung Galaxy series, misc. (tethering mode)                                                 | 2        | 1.74%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2        | 1.74%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 2        | 1.74%   |
| Intel Wireless-AC 9260                                                                        | 2        | 1.74%   |
| Intel Wireless 3165                                                                           | 2        | 1.74%   |
| Intel I211 Gigabit Network Connection                                                         | 2        | 1.74%   |
| Intel Ethernet Connection (2) I219-V                                                          | 2        | 1.74%   |
| Intel 82579V Gigabit Network Connection                                                       | 2        | 1.74%   |
| Intel 82574L Gigabit Network Connection                                                       | 2        | 1.74%   |
| Huawei STK-L21                                                                                | 2        | 1.74%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 1        | 0.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 0.87%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 0.87%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1        | 0.87%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1        | 0.87%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 0.87%   |
| Realtek RTL8187 Wireless Adapter                                                              | 1        | 0.87%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                               | 1        | 0.87%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 1        | 0.87%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 0.87%   |
| Realtek 802.11ac NIC                                                                          | 1        | 0.87%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                                     | 1        | 0.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1        | 0.87%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1        | 0.87%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                                      | 1        | 0.87%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                 | 1        | 0.87%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                                | 1        | 0.87%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg]                | 1        | 0.87%   |
| Qualcomm Android                                                                              | 1        | 0.87%   |
| Nvidia MCP77 Ethernet                                                                         | 1        | 0.87%   |
| Nvidia MCP61 Ethernet                                                                         | 1        | 0.87%   |
| NetGear A6150                                                                                 | 1        | 0.87%   |
| Mercucys MW300UM RTL8192EU wifi                                                               | 1        | 0.87%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                                       | 1        | 0.87%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 1        | 0.87%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 13       | 39.39%  |
| Intel                 | 9        | 27.27%  |
| Ralink Technology     | 3        | 9.09%   |
| Qualcomm Atheros      | 3        | 9.09%   |
| TP-Link               | 1        | 3.03%   |
| NetGear               | 1        | 3.03%   |
| Mercucys              | 1        | 3.03%   |
| Broadcom              | 1        | 3.03%   |
| Belkin Components     | 1        | 3.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 4        | 11.76%  |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 3        | 8.82%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2        | 5.88%   |
| Intel Wireless-AC 9260                                                                        | 2        | 5.88%   |
| Intel Wireless 3165                                                                           | 2        | 5.88%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 1        | 2.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 2.94%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 2.94%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1        | 2.94%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 1        | 2.94%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 2.94%   |
| Realtek RTL8187 Wireless Adapter                                                              | 1        | 2.94%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 2.94%   |
| Realtek 802.11ac NIC                                                                          | 1        | 2.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1        | 2.94%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1        | 2.94%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg]                | 1        | 2.94%   |
| NetGear A6150                                                                                 | 1        | 2.94%   |
| Mercucys MW300UM RTL8192EU wifi                                                               | 1        | 2.94%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 1        | 2.94%   |
| Intel Wi-Fi 6 AX200                                                                           | 1        | 2.94%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 1        | 2.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1        | 2.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1        | 2.94%   |
| Broadcom BCM4321 802.11a/b/g/n                                                                | 1        | 2.94%   |
| Belkin Components F9L1101v2 802.11abgn Wireless Adapter [Realtek RTL8192DU]                   | 1        | 2.94%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 37       | 47.44%  |
| Intel                    | 26       | 33.33%  |
| Qualcomm Atheros         | 4        | 5.13%   |
| Samsung Electronics      | 2        | 2.56%   |
| Nvidia                   | 2        | 2.56%   |
| Huawei Technologies      | 2        | 2.56%   |
| Broadcom                 | 2        | 2.56%   |
| Qualcomm                 | 1        | 1.28%   |
| Marvell Technology Group | 1        | 1.28%   |
| HTC (High Tech Computer) | 1        | 1.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 33       | 40.74%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 8.64%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 3.7%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 2.47%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 2.47%   |
| Intel I211 Gigabit Network Connection                             | 2        | 2.47%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 2.47%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 2.47%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 2.47%   |
| Huawei STK-L21                                                    | 2        | 2.47%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 1.23%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 1.23%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.23%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 1.23%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 1.23%   |
| Qualcomm Android                                                  | 1        | 1.23%   |
| Nvidia MCP77 Ethernet                                             | 1        | 1.23%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.23%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.23%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 1.23%   |
| Intel I210 Gigabit Fiber Network Connection                       | 1        | 1.23%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.23%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 1.23%   |
| Intel Ethernet Connection (17) I219-V                             | 1        | 1.23%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 1.23%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1        | 1.23%   |
| Intel 82567V-2 Gigabit Network Connection                         | 1        | 1.23%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 1.23%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 1.23%   |
| Intel 82545GM Gigabit Ethernet Controller                         | 1        | 1.23%   |
| HTC (High Tech Computer) Desire HD (modem mode)                   | 1        | 1.23%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.23%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 1.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 70       | 70%     |
| WiFi     | 30       | 30%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 58       | 79.45%  |
| WiFi     | 15       | 20.55%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 49       | 69.01%  |
| 2     | 21       | 29.58%  |
| 0     | 1        | 1.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 55       | 76.39%  |
| Yes  | 17       | 23.61%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 9        | 45%     |
| Cambridge Silicon Radio | 5        | 25%     |
| Realtek Semiconductor   | 2        | 10%     |
| Broadcom                | 2        | 10%     |
| Lite-On Technology      | 1        | 5%      |
| Dell                    | 1        | 5%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5        | 25%     |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 10%     |
| Intel Bluetooth wireless interface                  | 2        | 10%     |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 5%      |
| Realtek Bluetooth Radio                             | 1        | 5%      |
| Lite-On Bluetooth Device                            | 1        | 5%      |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 5%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 5%      |
| Intel AX210 Bluetooth                               | 1        | 5%      |
| Intel AX201 Bluetooth                               | 1        | 5%      |
| Intel AX200 Bluetooth                               | 1        | 5%      |
| Dell BT Mini-Receiver                               | 1        | 5%      |
| Broadcom BCM92045B3 ROM                             | 1        | 5%      |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 5%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 47       | 40.17%  |
| Nvidia                   | 38       | 32.48%  |
| AMD                      | 25       | 21.37%  |
| C-Media Electronics      | 3        | 2.56%   |
| Native Instruments       | 1        | 0.85%   |
| Micro Star International | 1        | 0.85%   |
| JMTek                    | 1        | 0.85%   |
| GN Netcom                | 1        | 0.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 9        | 6.77%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 8        | 6.02%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8        | 6.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8        | 6.02%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6        | 4.51%   |
| Nvidia High Definition Audio Controller                                    | 5        | 3.76%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5        | 3.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4        | 3.01%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4        | 3.01%   |
| Nvidia TU116 High Definition Audio Controller                              | 3        | 2.26%   |
| Nvidia GP108 High Definition Audio Controller                              | 3        | 2.26%   |
| Nvidia GM204 High Definition Audio Controller                              | 3        | 2.26%   |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 2.26%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 2.26%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3        | 2.26%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 2.26%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 2.26%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 2.26%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3        | 2.26%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 1.5%    |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 1.5%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 1.5%    |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2        | 1.5%    |
| Intel Alder Lake-S HD Audio Controller                                     | 2        | 1.5%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 1.5%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 1.5%    |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                  | 1        | 0.75%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 0.75%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 0.75%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 0.75%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 0.75%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 0.75%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 0.75%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 0.75%   |
| Nvidia GF116 High Definition Audio Controller                              | 1        | 0.75%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1        | 0.75%   |
| Nvidia GA102 High Definition Audio Controller                              | 1        | 0.75%   |
| Native Instruments Traktor Audio 2 MK2                                     | 1        | 0.75%   |
| Micro Star International USB Audio                                         | 1        | 0.75%   |
| JMTek USB PnP Audio Device                                                 | 1        | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 5        | 20.83%  |
| Unknown             | 4        | 16.67%  |
| Micron Technology   | 2        | 8.33%   |
| G.Skill             | 2        | 8.33%   |
| Corsair             | 2        | 8.33%   |
| Smart               | 1        | 4.17%   |
| SK hynix            | 1        | 4.17%   |
| Nanya Technology    | 1        | 4.17%   |
| Kingston            | 1        | 4.17%   |
| Elpida              | 1        | 4.17%   |
| Crucial             | 1        | 4.17%   |
| AVEXIR              | 1        | 4.17%   |
| A-DATA Technology   | 1        | 4.17%   |
| Unknown             | 1        | 4.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM 1333MT/s                  | 1        | 3.85%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                  | 1        | 3.85%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s              | 1        | 3.85%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                  | 1        | 3.85%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s              | 1        | 3.85%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s | 1        | 3.85%   |
| SK hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2666MT/s  | 1        | 3.85%   |
| Samsung RAM Module 8GB DIMM DDR4 2400MT/s             | 1        | 3.85%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s | 1        | 3.85%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s | 1        | 3.85%   |
| Samsung RAM M393B1G70QH0-CMA 8GB DIMM DDR3 1600MT/s   | 1        | 3.85%   |
| Samsung RAM M393B1G70BH0-YK0 8GB DIMM DDR3 1600MT/s   | 1        | 3.85%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s  | 1        | 3.85%   |
| Nanya RAM NT1GT64U8HB0BY-3C 1GB DIMM DDR2 667MT/s     | 1        | 3.85%   |
| Micron RAM 18JSF1G72PZ-1G9E1 8GB DIMM DDR3 1866MT/s   | 1        | 3.85%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s  | 1        | 3.85%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s   | 1        | 3.85%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s  | 1        | 3.85%   |
| G.Skill RAM F4-3000C16-16GVRB 16GB DIMM DDR4 3200MT/s | 1        | 3.85%   |
| Elpida RAM EBE21UE8AFFA-8G-F 2GB DIMM DDR2 800MT/s    | 1        | 3.85%   |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s | 1        | 3.85%   |
| Corsair RAM VS2GB1333D4 2GB DIMM DDR3 1600MT/s        | 1        | 3.85%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s | 1        | 3.85%   |
| AVEXIR RAM DDR4-3000 CL16 8GB 8GB DIMM DDR4 2133MT/s  | 1        | 3.85%   |
| A-DATA RAM DDR4 3200 16GB DIMM DDR4 3400MT/s          | 1        | 3.85%   |
| Unknown                                               | 1        | 3.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 9        | 40.91%  |
| DDR3    | 7        | 31.82%  |
| DDR2    | 3        | 13.64%  |
| Unknown | 2        | 9.09%   |
| SDRAM   | 1        | 4.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 20       | 90.91%  |
| SODIMM | 2        | 9.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 8        | 34.78%  |
| 4096  | 5        | 21.74%  |
| 16384 | 4        | 17.39%  |
| 2048  | 3        | 13.04%  |
| 1024  | 2        | 8.7%    |
| 32768 | 1        | 4.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 6        | 26.09%  |
| 3600  | 2        | 8.7%    |
| 3200  | 2        | 8.7%    |
| 1333  | 2        | 8.7%    |
| 667   | 2        | 8.7%    |
| 3400  | 1        | 4.35%   |
| 2667  | 1        | 4.35%   |
| 2666  | 1        | 4.35%   |
| 2400  | 1        | 4.35%   |
| 2133  | 1        | 4.35%   |
| 1866  | 1        | 4.35%   |
| 1334  | 1        | 4.35%   |
| 800   | 1        | 4.35%   |
| 533   | 1        | 4.35%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Konica Minolta     | 1        | 33.33%  |
| Hewlett-Packard    | 1        | 33.33%  |
| Brother Industries | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                 | Desktops | Percent |
|-----------------------|----------|---------|
| Konica Minolta 185    | 1        | 33.33%  |
| HP OfficeJet Pro 8730 | 1        | 33.33%  |
| Brother MFC-L2685DW   | 1        | 33.33%  |

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


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 5        | 33.33%  |
| Creative Technology           | 2        | 13.33%  |
| Z-Star Microelectronics       | 1        | 6.67%   |
| Sunplus Innovation Technology | 1        | 6.67%   |
| Pixart Imaging                | 1        | 6.67%   |
| OmniVision Technologies       | 1        | 6.67%   |
| MacroSilicon                  | 1        | 6.67%   |
| Huawei Technologies           | 1        | 6.67%   |
| ARC International             | 1        | 6.67%   |
| Alcor Micro                   | 1        | 6.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Z-Star Venus USB2.0 Camera                     | 1        | 6.67%   |
| Sunplus AAPDQT-0622-W                          | 1        | 6.67%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro           | 1        | 6.67%   |
| OmniVision Integrated Webcam for Dell XPS 2010 | 1        | 6.67%   |
| MacroSilicon USB Video                         | 1        | 6.67%   |
| Logitech Webcam C925e                          | 1        | 6.67%   |
| Logitech Webcam C270                           | 1        | 6.67%   |
| Logitech Webcam C210                           | 1        | 6.67%   |
| Logitech Webcam B500                           | 1        | 6.67%   |
| Logitech Logi Webcam C920e                     | 1        | 6.67%   |
| Huawei UVC Camera                              | 1        | 6.67%   |
| Creative VF0610 Live! Cam Socialize HD         | 1        | 6.67%   |
| Creative Live! Cam Sync HD [VF0770]            | 1        | 6.67%   |
| ARC International Camera                       | 1        | 6.67%   |
| Alcor Micro USB 2.0 PC Camera                  | 1        | 6.67%   |

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
| 0     | 53       | 73.61%  |
| 1     | 18       | 25%     |
| 2     | 1        | 1.39%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 10       | 47.62%  |
| Net/wireless             | 7        | 33.33%  |
| Unassigned class         | 1        | 4.76%   |
| Multimedia controller    | 1        | 4.76%   |
| Communication controller | 1        | 4.76%   |
| Camera                   | 1        | 4.76%   |

