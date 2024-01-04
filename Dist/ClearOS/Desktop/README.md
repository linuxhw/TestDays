ClearOS - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for ClearOS.

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

Total: 96

| Vendor   | Model                  | Probe                                                      | Date         |
|----------|------------------------|------------------------------------------------------------|--------------|
| MSI      | MS-7142                | [1cb67ac1ca](https://linux-hardware.org/?probe=1cb67ac1ca) | Mar 22, 2023 |
| ASRock   | AD525PV3               | [da83c87218](https://linux-hardware.org/?probe=da83c87218) | Dec 01, 2022 |
| Intel    | LADPNVMO AAE76523-300  | [db4e4c9c5b](https://linux-hardware.org/?probe=db4e4c9c5b) | Nov 22, 2022 |
| ASRock   | AD525PV3               | [4bba69ecd9](https://linux-hardware.org/?probe=4bba69ecd9) | Nov 18, 2022 |
| Intel    | LADPNVMO AAE76523-300  | [ea94d443c9](https://linux-hardware.org/?probe=ea94d443c9) | Nov 12, 2022 |
| Gigabyte | J1900M-D2P             | [7ea9f2df61](https://linux-hardware.org/?probe=7ea9f2df61) | Nov 06, 2022 |
| Gigabyte | Z77MX-D3H              | [be0b70efdb](https://linux-hardware.org/?probe=be0b70efdb) | Aug 15, 2022 |
| Gigabyte | Z77MX-D3H              | [360447806b](https://linux-hardware.org/?probe=360447806b) | Aug 04, 2022 |
| Gigabyte | GA-870A-UD3            | [950542a4a3](https://linux-hardware.org/?probe=950542a4a3) | Jul 16, 2022 |
| Gigabyte | J1900M-D2P             | [29602ec66f](https://linux-hardware.org/?probe=29602ec66f) | Jul 13, 2022 |
| Intel    | LADPNVMO AAE76523-300  | [07a37c99cb](https://linux-hardware.org/?probe=07a37c99cb) | Jul 11, 2022 |
| Gigabyte | J1900M-D2P             | [36fa61e21d](https://linux-hardware.org/?probe=36fa61e21d) | Jul 09, 2022 |
| Gigabyte | J1900M-D2P             | [d703a63932](https://linux-hardware.org/?probe=d703a63932) | Jun 26, 2022 |
| Gigabyte | J1900M-D2P             | [8ded20d82b](https://linux-hardware.org/?probe=8ded20d82b) | Jun 15, 2022 |
| Gigabyte | Z77MX-D3H              | [24c8a035ac](https://linux-hardware.org/?probe=24c8a035ac) | Jun 03, 2022 |
| Gigabyte | GA-870A-UD3            | [719fe6db76](https://linux-hardware.org/?probe=719fe6db76) | May 28, 2022 |
| Intel    | LADPNVMO AAE76523-300  | [9161d40357](https://linux-hardware.org/?probe=9161d40357) | May 14, 2022 |
| Gigabyte | Z77MX-D3H              | [42067d196a](https://linux-hardware.org/?probe=42067d196a) | May 02, 2022 |
| Gigabyte | J1900M-D2P             | [170db82573](https://linux-hardware.org/?probe=170db82573) | Apr 18, 2022 |
| ASRock   | AD525PV3               | [b5c71cfdef](https://linux-hardware.org/?probe=b5c71cfdef) | Apr 18, 2022 |
| Gigabyte | GA-870A-UD3            | [2bc3cb42bb](https://linux-hardware.org/?probe=2bc3cb42bb) | Apr 16, 2022 |
| Gigabyte | J1900M-D2P             | [794fbc68d8](https://linux-hardware.org/?probe=794fbc68d8) | Apr 14, 2022 |
| Intel    | LADPNVMO AAE76523-300  | [e6ca2fb62e](https://linux-hardware.org/?probe=e6ca2fb62e) | Feb 10, 2022 |
| ASRock   | AD525PV3               | [59739aa694](https://linux-hardware.org/?probe=59739aa694) | Jan 26, 2022 |
| ASRock   | AD525PV3               | [fc3b3de53f](https://linux-hardware.org/?probe=fc3b3de53f) | Jan 13, 2022 |
| ASUSTek  | A8R32-MVP Deluxe       | [0ddae870e9](https://linux-hardware.org/?probe=0ddae870e9) | Jan 13, 2022 |
| ASRock   | AD525PV3               | [51870f0b25](https://linux-hardware.org/?probe=51870f0b25) | Jan 01, 2022 |
| MSI      | MS-7142                | [4c0b236c8b](https://linux-hardware.org/?probe=4c0b236c8b) | Oct 06, 2021 |
| ASRock   | AD525PV3               | [04426b1a9d](https://linux-hardware.org/?probe=04426b1a9d) | Oct 02, 2021 |
| Gigabyte | J1900M-D2P             | [3e73db1984](https://linux-hardware.org/?probe=3e73db1984) | Sep 15, 2021 |
| Gigabyte | GA-870A-UD3            | [abc4e152fe](https://linux-hardware.org/?probe=abc4e152fe) | Sep 04, 2021 |
| Gigabyte | J1900M-D2P             | [836a8eb41d](https://linux-hardware.org/?probe=836a8eb41d) | Jul 11, 2021 |
| Gigabyte | J1900M-D2P             | [e0cb0f2571](https://linux-hardware.org/?probe=e0cb0f2571) | Jul 04, 2021 |
| ASRock   | AD2700-ITX             | [a1c7155352](https://linux-hardware.org/?probe=a1c7155352) | Jun 23, 2021 |
| MSI      | MS-7142                | [f1ffafce15](https://linux-hardware.org/?probe=f1ffafce15) | Feb 21, 2021 |
| ASRock   | K8Upgrade-VM800        | [0f084ce1b4](https://linux-hardware.org/?probe=0f084ce1b4) | Feb 11, 2021 |
| Gigabyte | D525TUD                | [d917ae12cd](https://linux-hardware.org/?probe=d917ae12cd) | Nov 08, 2020 |
| Gigabyte | Z77MX-D3H              | [85d94c05ce](https://linux-hardware.org/?probe=85d94c05ce) | Nov 08, 2020 |
| Gigabyte | D525TUD                | [cd08ac380a](https://linux-hardware.org/?probe=cd08ac380a) | Nov 08, 2020 |
| Gigabyte | Z77MX-D3H              | [d3a72a4472](https://linux-hardware.org/?probe=d3a72a4472) | Jul 08, 2020 |
| Gigabyte | GA-MA780G-UD3H         | [8112a45866](https://linux-hardware.org/?probe=8112a45866) | Jun 10, 2020 |
| Gigabyte | GA-870A-UD3            | [f4b0bf03de](https://linux-hardware.org/?probe=f4b0bf03de) | May 23, 2020 |
| Dell     | 07F37C A00             | [530cc43be2](https://linux-hardware.org/?probe=530cc43be2) | Apr 03, 2020 |
| Gigabyte | Z77MX-D3H              | [7e686b721e](https://linux-hardware.org/?probe=7e686b721e) | Mar 31, 2020 |
| Gigabyte | GA-MA780G-UD3H         | [16db1089e5](https://linux-hardware.org/?probe=16db1089e5) | Mar 15, 2020 |
| Gigabyte | GA-870A-UD3            | [c7bcbaa3a9](https://linux-hardware.org/?probe=c7bcbaa3a9) | Mar 15, 2020 |
| Gigabyte | GA-870A-UD3            | [60d8c5fbf4](https://linux-hardware.org/?probe=60d8c5fbf4) | Mar 11, 2020 |
| Intel    | LADPNVMO AAE76523-300  | [53be5db473](https://linux-hardware.org/?probe=53be5db473) | Feb 12, 2020 |
| Gigabyte | J1900M-D2P             | [4bc55155f5](https://linux-hardware.org/?probe=4bc55155f5) | Jan 11, 2020 |
| Gigabyte | D525TUD                | [3c58d48568](https://linux-hardware.org/?probe=3c58d48568) | Jan 10, 2020 |
| Gigabyte | J1900M-D2P             | [a8dc75f51b](https://linux-hardware.org/?probe=a8dc75f51b) | Jan 08, 2020 |
| Gigabyte | GA-MA780G-UD3H         | [52f139cc1c](https://linux-hardware.org/?probe=52f139cc1c) | Jan 08, 2020 |
| Gigabyte | J1900M-D2P             | [2ad366f4c0](https://linux-hardware.org/?probe=2ad366f4c0) | Dec 21, 2019 |
| Gigabyte | J1900M-D2P             | [e1685d9ba3](https://linux-hardware.org/?probe=e1685d9ba3) | Dec 06, 2019 |
| ASRock   | D1800B-ITX             | [13eafdefca](https://linux-hardware.org/?probe=13eafdefca) | Dec 06, 2019 |
| Gigabyte | D525TUD                | [2ece09c60b](https://linux-hardware.org/?probe=2ece09c60b) | Dec 06, 2019 |
| ASRock   | AD2700-ITX             | [fd83493705](https://linux-hardware.org/?probe=fd83493705) | Nov 26, 2019 |
| ASRock   | K8Upgrade-VM800        | [6fac734286](https://linux-hardware.org/?probe=6fac734286) | Nov 10, 2019 |
| ASRock   | AD2700-ITX             | [e568c873e2](https://linux-hardware.org/?probe=e568c873e2) | Nov 10, 2019 |
| Gigabyte | GA-990FXA-D3           | [ea03943650](https://linux-hardware.org/?probe=ea03943650) | Oct 24, 2019 |
| ASRock   | D1800B-ITX             | [1c2c965bff](https://linux-hardware.org/?probe=1c2c965bff) | Oct 16, 2019 |
| Gigabyte | J1900M-D2P             | [0a473fe232](https://linux-hardware.org/?probe=0a473fe232) | Oct 11, 2019 |
| Gigabyte | J1900M-D2P             | [23a87404be](https://linux-hardware.org/?probe=23a87404be) | Oct 11, 2019 |
| Gigabyte | J1900M-D2P             | [79d776a451](https://linux-hardware.org/?probe=79d776a451) | Oct 11, 2019 |
| ASRock   | D1800B-ITX             | [ea920a2bb8](https://linux-hardware.org/?probe=ea920a2bb8) | Sep 16, 2019 |
| Gigabyte | D525TUD                | [aac6218619](https://linux-hardware.org/?probe=aac6218619) | Aug 17, 2019 |
| Intel    | LADPNVMO AAE76523-300  | [f9331b7e6e](https://linux-hardware.org/?probe=f9331b7e6e) | Aug 11, 2019 |
| Gigabyte | Z77MX-D3H              | [d29d8e6525](https://linux-hardware.org/?probe=d29d8e6525) | Aug 11, 2019 |
| MSI      | MS-7142                | [5597a4ecbc](https://linux-hardware.org/?probe=5597a4ecbc) | Aug 09, 2019 |
| MSI      | MS-7142                | [62cb880370](https://linux-hardware.org/?probe=62cb880370) | Aug 09, 2019 |
| Gigabyte | GA-MA780G-UD3H         | [059b3e7104](https://linux-hardware.org/?probe=059b3e7104) | Aug 06, 2019 |
| ASRock   | K8Upgrade-VM800        | [4cf5bafe24](https://linux-hardware.org/?probe=4cf5bafe24) | Aug 05, 2019 |
| ASUSTek  | AT5NM10-I              | [47e870b0b9](https://linux-hardware.org/?probe=47e870b0b9) | Aug 05, 2019 |
| ASRock   | AD525PV3               | [27e239601b](https://linux-hardware.org/?probe=27e239601b) | Jul 14, 2019 |
| ASRock   | AD525PV3               | [a77743a828](https://linux-hardware.org/?probe=a77743a828) | Jul 06, 2019 |
| Gigabyte | Z77MX-D3H              | [0818f19e7a](https://linux-hardware.org/?probe=0818f19e7a) | May 10, 2019 |
| Intel    | D945GCLF2 AAE46416-103 | [1b11619ec9](https://linux-hardware.org/?probe=1b11619ec9) | Apr 19, 2019 |
| ASRock   | AD2700-ITX             | [9a4c5de0dd](https://linux-hardware.org/?probe=9a4c5de0dd) | Apr 17, 2019 |
| Gigabyte | Z77MX-D3H              | [84474e86fe](https://linux-hardware.org/?probe=84474e86fe) | Apr 14, 2019 |
| Gigabyte | D525TUD                | [e42fb17101](https://linux-hardware.org/?probe=e42fb17101) | Jan 24, 2019 |
| Gigabyte | GA-990FXA-D3           | [04595a2160](https://linux-hardware.org/?probe=04595a2160) | Dec 23, 2018 |
| Gigabyte | Z77MX-D3H              | [66d5165338](https://linux-hardware.org/?probe=66d5165338) | Dec 23, 2018 |
| Gigabyte | GA-990FXA-D3           | [6f5833f2e6](https://linux-hardware.org/?probe=6f5833f2e6) | Dec 20, 2018 |
| Gigabyte | GA-MA785G-UD3H         | [21cf5ac2d5](https://linux-hardware.org/?probe=21cf5ac2d5) | Dec 03, 2018 |
| Gigabyte | GA-MA785G-UD3H         | [f0831b789a](https://linux-hardware.org/?probe=f0831b789a) | Nov 20, 2018 |
| Gigabyte | 970A-DS3P              | [e84f35cfae](https://linux-hardware.org/?probe=e84f35cfae) | Nov 17, 2018 |
| ASRock   | K8Upgrade-VM800        | [f078674842](https://linux-hardware.org/?probe=f078674842) | Oct 29, 2018 |
| ASRock   | K8Upgrade-VM800        | [700f075a1a](https://linux-hardware.org/?probe=700f075a1a) | Oct 29, 2018 |
| Intel    | LADPNVMO AAE76523-300  | [8812da1475](https://linux-hardware.org/?probe=8812da1475) | Oct 29, 2018 |
| Intel    | D945GCLF2 AAE46416-103 | [ec75fd707d](https://linux-hardware.org/?probe=ec75fd707d) | Oct 29, 2018 |
| Intel    | LADPNVMO AAE76523-300  | [a1f047ea98](https://linux-hardware.org/?probe=a1f047ea98) | Oct 29, 2018 |
| ASUSTek  | AT5NM10-I              | [835a1b97e7](https://linux-hardware.org/?probe=835a1b97e7) | Oct 29, 2018 |
| ASRock   | AD2700-ITX             | [68112b4fbd](https://linux-hardware.org/?probe=68112b4fbd) | Oct 29, 2018 |
| ASRock   | D1800B-ITX             | [7c2537a197](https://linux-hardware.org/?probe=7c2537a197) | Oct 29, 2018 |
| Gigabyte | GA-MA780G-UD3H         | [a54a34840f](https://linux-hardware.org/?probe=a54a34840f) | Oct 29, 2018 |
| Gigabyte | Z77MX-D3H              | [775d3afac4](https://linux-hardware.org/?probe=775d3afac4) | Oct 29, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| ClearOS 7 | 24       | 100%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| ClearOS | 24       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 3.10.0-862.11.6.v7.x86_64   | 14       | 18.67%  |
| 3.10.0-957.21.3.v7.x86_64   | 7        | 9.33%   |
| 3.10.0-1160.71.1.el7.x86_64 | 7        | 9.33%   |
| 3.10.0-1160.62.1.el7.x86_64 | 6        | 8%      |
| 3.10.0-1062.9.1.el7.x86_64  | 5        | 6.67%   |
| 3.10.0-1160.66.1.el7.x86_64 | 4        | 5.33%   |
| 3.10.0-1062.1.2.el7.x86_64  | 4        | 5.33%   |
| 3.10.0-957.10.1.v7.x86_64   | 3        | 4%      |
| 3.10.0-1160.42.2.el7.x86_64 | 3        | 4%      |
| 3.10.0-1160.31.1.el7.x86_64 | 3        | 4%      |
| 3.10.0-1062.4.3.el7.x86_64  | 3        | 4%      |
| 3.10.0-1160.49.1.el7.x86_64 | 2        | 2.67%   |
| 3.10.0-1160.15.2.el7.x86_64 | 2        | 2.67%   |
| 3.10.0-1062.18.1.el7.x86_64 | 2        | 2.67%   |
| 3.10.0-1062.12.1.el7.x86_64 | 2        | 2.67%   |
| 3.10.0-693.17.1.v7.x86_64   | 1        | 1.33%   |
| 3.10.0-327.3.1.el7.x86_64   | 1        | 1.33%   |
| 3.10.0-1160.53.1.el7.x86_64 | 1        | 1.33%   |
| 3.10.0-1160.36.2.el7.x86_64 | 1        | 1.33%   |
| 3.10.0-1127.19.1.el7.x86_64 | 1        | 1.33%   |
| 3.10.0-1127.13.1.el7.x86_64 | 1        | 1.33%   |
| 3.10.0-1127.10.1.el7.x86_64 | 1        | 1.33%   |
| 3.10.0-1062.1.1.el7.x86_64  | 1        | 1.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 3.10.0  | 24       | 100%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 3.10    | 24       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 24       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 23       | 95.83%  |
| GNOME   | 1        | 4.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 24       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 23       | 95.83%  |
| GDM     | 1        | 4.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 19       | 57.58%  |
| en_AU   | 11       | 33.33%  |
| en_US   | 3        | 9.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 24       | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Xfs  | 24       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| MBR  | 24       | 96%     |
| GPT  | 1        | 4%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 85.19%  |
| Yes       | 4        | 14.81%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 24       | 92.31%  |
| Yes       | 2        | 7.69%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 13       | 54.17%  |
| ASRock              | 4        | 16.67%  |
| MSI                 | 2        | 8.33%   |
| Intel               | 2        | 8.33%   |
| ASUSTek Computer    | 2        | 8.33%   |
| Dell                | 1        | 4.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Gigabyte Z77MX-D3H           | 3        | 12.5%   |
| MSI MS-7142                  | 2        | 8.33%   |
| Gigabyte J1900M-D2P          | 2        | 8.33%   |
| Gigabyte GA-MA780G-UD3H      | 2        | 8.33%   |
| Gigabyte GA-990FXA-D3        | 2        | 8.33%   |
| Intel LADPNVMO AAE76523-300  | 1        | 4.17%   |
| Intel D945GCLF2 AAE46416-103 | 1        | 4.17%   |
| Gigabyte GA-MA785G-UD3H      | 1        | 4.17%   |
| Gigabyte GA-870A-UD3         | 1        | 4.17%   |
| Gigabyte D525TUD             | 1        | 4.17%   |
| Gigabyte 970A-DS3P           | 1        | 4.17%   |
| Dell Inspiron 3268           | 1        | 4.17%   |
| ASUS AT5NM10-I               | 1        | 4.17%   |
| ASUS A8R32-MVP Deluxe        | 1        | 4.17%   |
| ASRock K8Upgrade-VM800       | 1        | 4.17%   |
| ASRock D1800B-ITX            | 1        | 4.17%   |
| ASRock AD525PV3              | 1        | 4.17%   |
| ASRock AD2700-ITX            | 1        | 4.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Gigabyte Z77MX-D3H      | 3        | 12.5%   |
| MSI MS-7142             | 2        | 8.33%   |
| Gigabyte J1900M-D2P     | 2        | 8.33%   |
| Gigabyte GA-MA780G-UD3H | 2        | 8.33%   |
| Gigabyte GA-990FXA-D3   | 2        | 8.33%   |
| Intel LADPNVMO          | 1        | 4.17%   |
| Intel D945GCLF2         | 1        | 4.17%   |
| Gigabyte GA-MA785G-UD3H | 1        | 4.17%   |
| Gigabyte GA-870A-UD3    | 1        | 4.17%   |
| Gigabyte D525TUD        | 1        | 4.17%   |
| Gigabyte 970A-DS3P      | 1        | 4.17%   |
| Dell Inspiron           | 1        | 4.17%   |
| ASUS AT5NM10-I          | 1        | 4.17%   |
| ASUS A8R32-MVP          | 1        | 4.17%   |
| ASRock K8Upgrade-VM800  | 1        | 4.17%   |
| ASRock D1800B-ITX       | 1        | 4.17%   |
| ASRock AD525PV3         | 1        | 4.17%   |
| ASRock AD2700-ITX       | 1        | 4.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 4        | 16.67%  |
| 2014 | 3        | 12.5%   |
| 2011 | 3        | 12.5%   |
| 2010 | 3        | 12.5%   |
| 2009 | 3        | 12.5%   |
| 2005 | 3        | 12.5%   |
| 2008 | 2        | 8.33%   |
| 2017 | 1        | 4.17%   |
| 2013 | 1        | 4.17%   |
| 2006 | 1        | 4.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 24       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 24       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 24       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 8.01-16.0  | 8        | 29.63%  |
| 3.01-4.0   | 6        | 22.22%  |
| 1.01-2.0   | 6        | 22.22%  |
| 4.01-8.0   | 5        | 18.52%  |
| 16.01-24.0 | 2        | 7.41%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.51-1.0  | 14       | 31.82%  |
| 1.01-2.0  | 10       | 22.73%  |
| 2.01-3.0  | 9        | 20.45%  |
| 4.01-8.0  | 5        | 11.36%  |
| 3.01-4.0  | 3        | 6.82%   |
| 0.01-0.5  | 2        | 4.55%   |
| 8.01-16.0 | 1        | 2.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 18       | 64.29%  |
| 4      | 3        | 10.71%  |
| 3      | 2        | 7.14%   |
| 2      | 2        | 7.14%   |
| 8      | 1        | 3.57%   |
| 6      | 1        | 3.57%   |
| 0      | 1        | 3.57%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 84%     |
| Yes       | 4        | 16%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 24       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 22       | 91.67%  |
| Yes       | 2        | 8.33%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 82.14%  |
| Yes       | 5        | 17.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Australia | 23       | 95.83%  |
| USA       | 1        | 4.17%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City        | Desktops | Percent |
|-------------|----------|---------|
| Wahroonga   | 19       | 39.58%  |
| Sydney      | 11       | 22.92%  |
| Surry Hills | 10       | 20.83%  |
| Lane Cove   | 4        | 8.33%   |
| Launceston  | 3        | 6.25%   |
| Carson      | 1        | 2.08%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 14       | 76     | 41.18%  |
| WDC                 | 6        | 41     | 17.65%  |
| Maxtor              | 4        | 7      | 11.76%  |
| KingSpec            | 3        | 9      | 8.82%   |
| Seagate             | 2        | 33     | 5.88%   |
| LITEONIT            | 2        | 4      | 5.88%   |
| Vaseky              | 1        | 4      | 2.94%   |
| Intel               | 1        | 4      | 2.94%   |
| Hitachi             | 1        | 1      | 2.94%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Samsung SSD 850 PRO 128GB           | 5        | 10.42%  |
| Samsung SSD 850 EVO 250GB           | 5        | 10.42%  |
| Samsung SSD 830 Series 256GB        | 5        | 10.42%  |
| WDC WD10EFRX-68PJCN0 1TB            | 3        | 6.25%   |
| WDC WD10EFRX-68FYTN0 1TB            | 3        | 6.25%   |
| Seagate ST31000333AS 1TB            | 2        | 4.17%   |
| Seagate ST2000DL003-9VT166 2TB      | 2        | 4.17%   |
| Samsung SSD 840 PRO Series 128GB    | 2        | 4.17%   |
| Samsung SSD 840 EVO 250GB           | 2        | 4.17%   |
| Samsung HD103UJ 1TB                 | 2        | 4.17%   |
| Maxtor 6Y080L0 82GB                 | 2        | 4.17%   |
| Maxtor 6L200M0 200GB                | 2        | 4.17%   |
| LITEONIT LMT-128M6M mSATA 128GB SSD | 2        | 4.17%   |
| KingSpec MT-128 128GB SSD           | 2        | 4.17%   |
| WDC WD40EFRX-68N32N0 4TB            | 1        | 2.08%   |
| WDC WD2500BEVE-00A0HT0 250GB        | 1        | 2.08%   |
| WDC WD2000JB-16FUA0 200GB           | 1        | 2.08%   |
| WDC WD1200JB-00EVA0 120GB           | 1        | 2.08%   |
| Vaseky V850/64G 64GB SSD            | 1        | 2.08%   |
| Samsung HM250JI 250GB               | 1        | 2.08%   |
| KingSpec V-32 32GB SSD              | 1        | 2.08%   |
| Intel SSDSC2CT120A3 120GB           | 1        | 2.08%   |
| Hitachi HDS721010DLE630 1TB         | 1        | 2.08%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 41     | 37.5%   |
| Maxtor              | 4        | 7      | 25%     |
| Samsung Electronics | 3        | 19     | 18.75%  |
| Seagate             | 2        | 33     | 12.5%   |
| Hitachi             | 1        | 1      | 6.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 13       | 57     | 65%     |
| KingSpec            | 3        | 9      | 15%     |
| LITEONIT            | 2        | 4      | 10%     |
| Vaseky              | 1        | 4      | 5%      |
| Intel               | 1        | 4      | 5%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 18       | 78     | 58.06%  |
| HDD  | 13       | 101    | 41.94%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 23       | 179    | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 23       | 96     | 71.88%  |
| 0.51-1.0   | 6        | 64     | 18.75%  |
| 1.01-2.0   | 2        | 18     | 6.25%   |
| 3.01-4.0   | 1        | 1      | 3.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 51-100     | 19       | 63.33%  |
| 21-50      | 3        | 10%     |
| 101-250    | 3        | 10%     |
| 251-500    | 2        | 6.67%   |
| 2001-3000  | 1        | 3.33%   |
| 1001-2000  | 1        | 3.33%   |
| 501-1000   | 1        | 3.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 21       | 72.41%  |
| 21-50     | 3        | 10.34%  |
| 101-250   | 2        | 6.9%    |
| 2001-3000 | 1        | 3.45%   |
| 1001-2000 | 1        | 3.45%   |
| 51-100    | 1        | 3.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Maxtor 6Y080L0 82GB             | 2        | 4      | 25%     |
| Maxtor 6L200M0 200GB            | 2        | 3      | 25%     |
| Seagate ST31000333AS 1TB        | 1        | 3      | 12.5%   |
| Samsung Electronics HD103UJ 1TB | 1        | 12     | 12.5%   |
| Intel SSDSC2CT120A3 120GB       | 1        | 4      | 12.5%   |
| Hitachi HDS721010DLE630 1TB     | 1        | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Maxtor              | 4        | 7      | 50%     |
| Seagate             | 1        | 3      | 12.5%   |
| Samsung Electronics | 1        | 12     | 12.5%   |
| Intel               | 1        | 4      | 12.5%   |
| Hitachi             | 1        | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Maxtor              | 4        | 7      | 57.14%  |
| Seagate             | 1        | 3      | 14.29%  |
| Samsung Electronics | 1        | 12     | 14.29%  |
| Hitachi             | 1        | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 7        | 23     | 87.5%   |
| SSD  | 1        | 4      | 12.5%   |

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


| Status  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Works   | 19       | 152    | 70.37%  |
| Malfunc | 8        | 27     | 29.63%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Intel              | 13       | 46.43%  |
| AMD                | 7        | 25%     |
| VIA Technologies   | 3        | 10.71%  |
| JMicron Technology | 2        | 7.14%   |
| ULi Electronics    | 1        | 3.57%   |
| Silicon Image      | 1        | 3.57%   |
| 3ware              | 1        | 3.57%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 7        | 20%     |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                            | 5        | 14.29%  |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                   | 3        | 8.57%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                        | 3        | 8.57%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]  | 3        | 8.57%   |
| VIA VIA VT6420 SATA RAID Controller                                           | 2        | 5.71%   |
| JMicron JMB363 SATA/IDE Controller                                            | 2        | 5.71%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 2        | 5.71%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                          | 2        | 5.71%   |
| ULi ULi M5288 SATA                                                            | 1        | 2.86%   |
| ULi M5229 IDE                                                                 | 1        | 2.86%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                          | 1        | 2.86%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1        | 2.86%   |
| Intel 82801G (ICH7 Family) IDE Controller                                     | 1        | 2.86%   |
| 3ware 9650SE SATA-II RAID PCIe                                                | 1        | 2.86%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 20       | 58.82%  |
| IDE  | 10       | 29.41%  |
| RAID | 4        | 11.76%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 13       | 54.17%  |
| AMD    | 11       | 45.83%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| AMD FX-4100 Quad-Core Processor            | 4        | 16.67%  |
| Intel Core i7-3770 CPU @ 3.40GHz           | 3        | 12.5%   |
| AMD Sempron Processor 3000+                | 3        | 12.5%   |
| Intel Celeron CPU J1900 @ 1.99GHz          | 2        | 8.33%   |
| Intel Atom CPU D525 @ 1.80GHz              | 2        | 8.33%   |
| AMD Phenom II X2 570 Processor             | 2        | 8.33%   |
| Intel Genuine CPU @ 1.66GHz                | 1        | 4.17%   |
| Intel Core i3-7100 CPU @ 3.90GHz           | 1        | 4.17%   |
| Intel Celeron CPU J1800 @ 2.41GHz          | 1        | 4.17%   |
| Intel Atom CPU D510 @ 1.66GHz              | 1        | 4.17%   |
| Intel Atom CPU D2700 @ 2.13GHz             | 1        | 4.17%   |
| Intel Atom CPU 330 @ 1.60GHz               | 1        | 4.17%   |
| AMD Phenom II X4 955 Processor             | 1        | 4.17%   |
| AMD Athlon 64 X2 Dual Core Processor 4400+ | 1        | 4.17%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Desktops | Percent |
|------------------|----------|---------|
| Intel Atom       | 5        | 20.83%  |
| AMD FX           | 4        | 16.67%  |
| Intel Core i7    | 3        | 12.5%   |
| Intel Celeron    | 3        | 12.5%   |
| AMD Sempron      | 3        | 12.5%   |
| AMD Phenom II X2 | 2        | 8.33%   |
| Intel Genuine    | 1        | 4.17%   |
| Intel Core i3    | 1        | 4.17%   |
| AMD Phenom II X4 | 1        | 4.17%   |
| AMD Athlon 64 X2 | 1        | 4.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 15       | 62.5%   |
| 4      | 6        | 25%     |
| 1      | 3        | 12.5%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 24       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 14       | 58.33%  |
| 1      | 10       | 41.67%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 24       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 6        | 22.22%  |
| 0x106ca    | 4        | 14.81%  |
| 0x306a9    | 3        | 11.11%  |
| 0x30678    | 3        | 11.11%  |
| 0x0600063e | 3        | 11.11%  |
| 0x010000c8 | 3        | 11.11%  |
| 0x906e9    | 1        | 3.7%    |
| 0x30661    | 1        | 3.7%    |
| 0x106c2    | 1        | 3.7%    |
| 0x0600062e | 1        | 3.7%    |
| 0x06000609 | 1        | 3.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Bonnell    | 6        | 25%     |
| K8 Hammer  | 4        | 16.67%  |
| Bulldozer  | 4        | 16.67%  |
| Silvermont | 3        | 12.5%   |
| K10        | 3        | 12.5%   |
| IvyBridge  | 3        | 12.5%   |
| KabyLake   | 1        | 4.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 13       | 54.17%  |
| AMD              | 6        | 25%     |
| VIA Technologies | 3        | 12.5%   |
| Nvidia           | 2        | 8.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller | 4        | 14.29%  |
| VIA Technologies K8M800/K8N800/K8N800A [S3 UniChrome Pro]               | 3        | 10.71%  |
| Intel IvyBridge GT2 [HD Graphics 4000]                                  | 3        | 10.71%  |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display            | 3        | 10.71%  |
| AMD RV370 [Radeon X300]                                                 | 3        | 10.71%  |
| AMD RV370 [Radeon X300 SE]                                              | 3        | 10.71%  |
| Nvidia G72 [GeForce 7300 GS]                                            | 2        | 7.14%   |
| AMD RS780 [Radeon HD 3200]                                              | 2        | 7.14%   |
| Intel HD Graphics 630                                                   | 1        | 3.57%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller         | 1        | 3.57%   |
| Intel 82945G/GZ Integrated Graphics Controller                          | 1        | 3.57%   |
| AMD RV380 [Radeon X300/X550/X1050 Series] (Secondary)                   | 1        | 3.57%   |
| AMD RV370 [Radeon X600/X600 SE]                                         | 1        | 3.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 13       | 54.17%  |
| 2 x AMD    | 4        | 16.67%  |
| 1 x VIA    | 3        | 12.5%   |
| 1 x Nvidia | 2        | 8.33%   |
| 1 x AMD    | 2        | 8.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 18       | 64.29%  |
| Unknown | 10       | 35.71%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 15       | 53.57%  |
| 0.01-0.5   | 11       | 39.29%  |
| 1.01-2.0   | 2        | 7.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 16       | 35.56%  |
| ___                 | 9        | 20%     |
| Philips             | 5        | 11.11%  |
| ViewSonic           | 4        | 8.89%   |
| Unknown             | 4        | 8.89%   |
| BenQ                | 3        | 6.67%   |
| Lenovo              | 2        | 4.44%   |
| Hewlett-Packard     | 1        | 2.22%   |
| Dell                | 1        | 2.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM01D3 1440x900 408x225mm 18.3-inch     | 11       | 23.91%  |
| ___ LCD TV ___0101 1920x1080                                            | 9        | 19.57%  |
| Samsung Electronics LCD Monitor SAM2C35 1024x768 280x210mm 13.8-inch    | 5        | 10.87%  |
| Philips 190S PHL082F 1280x1024 338x270mm 17.0-inch                      | 5        | 10.87%  |
| ViewSonic VA2226w-11 VSC2051 1680x1050 495x291mm 22.6-inch              | 4        | 8.7%    |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                     | 4        | 8.7%    |
| BenQ FP91G+ BNQ76A5 1280x1024 376x301mm 19.0-inch                       | 3        | 6.52%   |
| Lenovo LEN L1711pC LEN13B7 1280x1024 338x270mm 17.0-inch                | 2        | 4.35%   |
| Samsung Electronics LCD Monitor SAM0F9F 3840x2160 1872x1053mm 84.6-inch | 1        | 2.17%   |
| Hewlett-Packard L1502 HWP2600 1024x768 304x228mm 15.0-inch              | 1        | 2.17%   |
| Dell P1917S DELD091 1280x1024 380x300mm 19.1-inch                       | 1        | 2.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 11       | 25%     |
| 1440x900 (WXGA+)   | 11       | 25%     |
| 1280x1024 (SXGA)   | 11       | 25%     |
| 1280x768           | 5        | 11.36%  |
| 1680x1050 (WSXGA+) | 4        | 9.09%   |
| 3840x2160 (4K)     | 1        | 2.27%   |
| 1024x768 (XGA)     | 1        | 2.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 19     | 18       | 40.91%  |
| 21     | 9        | 20.45%  |
| 13     | 5        | 11.36%  |
| 72     | 4        | 9.09%   |
| 22     | 4        | 9.09%   |
| 18     | 2        | 4.55%   |
| 84     | 1        | 2.27%   |
| 15     | 1        | 2.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 18       | 45%     |
| 351-400     | 11       | 27.5%   |
| 201-300     | 5        | 12.5%   |
| 1501-2000   | 5        | 12.5%   |
| 301-350     | 1        | 2.5%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 15       | 34.88%  |
| 16/10 | 11       | 25.58%  |
| 5/4   | 9        | 20.93%  |
| 4/3   | 6        | 13.95%  |
| 6/5   | 2        | 4.65%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 151-200        | 18       | 42.86%  |
| 201-250        | 13       | 30.95%  |
| More than 1000 | 5        | 11.9%   |
| 91-100         | 5        | 11.9%   |
| 111-120        | 1        | 2.38%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 23       | 63.89%  |
| 101-120 | 9        | 25%     |
| 1-50    | 4        | 11.11%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 18       | 52.94%  |
| 2     | 15       | 44.12%  |
| 0     | 1        | 2.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 20       | 35.71%  |
| Intel                    | 19       | 33.93%  |
| D-Link                   | 6        | 10.71%  |
| Qualcomm Atheros         | 5        | 8.93%   |
| VIA Technologies         | 3        | 5.36%   |
| Marvell Technology Group | 1        | 1.79%   |
| Broadcom                 | 1        | 1.79%   |
| ASIX Electronics         | 1        | 1.79%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17       | 26.15%  |
| Intel 82546EB Gigabit Ethernet Controller (Copper)                | 10       | 15.38%  |
| D-Link DUB-1312 Gigabit Ethernet Adapter                          | 6        | 9.23%   |
| Intel 82541PI Gigabit Ethernet Controller                         | 5        | 7.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4        | 6.15%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 3        | 4.62%   |
| Intel 82575EB Gigabit Network Connection                          | 3        | 4.62%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 4.62%   |
| Realtek RTL8150 Fast Ethernet Adapter                             | 2        | 3.08%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 3.08%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 2        | 3.08%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.54%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 1.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1        | 1.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1        | 1.54%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 1.54%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 1.54%   |
| Broadcom Network controller                                       | 1        | 1.54%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 1.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Qualcomm Atheros | 2        | 66.67%  |
| Broadcom         | 1        | 33.33%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1        | 33.33%  |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1        | 33.33%  |
| Broadcom Network controller                                    | 1        | 33.33%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 20       | 37.04%  |
| Intel                    | 19       | 35.19%  |
| D-Link                   | 6        | 11.11%  |
| Qualcomm Atheros         | 4        | 7.41%   |
| VIA Technologies         | 3        | 5.56%   |
| Marvell Technology Group | 1        | 1.85%   |
| ASIX Electronics         | 1        | 1.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17       | 27.42%  |
| Intel 82546EB Gigabit Ethernet Controller (Copper)                | 10       | 16.13%  |
| D-Link DUB-1312 Gigabit Ethernet Adapter                          | 6        | 9.68%   |
| Intel 82541PI Gigabit Ethernet Controller                         | 5        | 8.06%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4        | 6.45%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 3        | 4.84%   |
| Intel 82575EB Gigabit Network Connection                          | 3        | 4.84%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 4.84%   |
| Realtek RTL8150 Fast Ethernet Adapter                             | 2        | 3.23%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 3.23%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 2        | 3.23%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.61%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 1.61%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 1.61%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 1.61%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 1.61%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 24       | 92.31%  |
| WiFi     | 2        | 7.69%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 24       | 100%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 3     | 13       | 44.83%  |
| 2     | 5        | 17.24%  |
| 4     | 4        | 13.79%  |
| 1     | 4        | 13.79%  |
| 5     | 3        | 10.34%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 24       | 85.71%  |
| Yes  | 4        | 14.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 5        | 100%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5        | 100%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 8        | 66.67%  |
| AMD              | 2        | 16.67%  |
| VIA Technologies | 1        | 8.33%   |
| ULi Electronics  | 1        | 8.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3        | 23.08%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 23.08%  |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                     | 2        | 15.38%  |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 1        | 7.69%   |
| ULi Electronics HD Audio Controller                                        | 1        | 7.69%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1        | 7.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 7.69%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 7.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 13       | 50%     |
| Kingston            | 4        | 15.38%  |
| G.Skill             | 3        | 11.54%  |
| Crucial             | 2        | 7.69%   |
| Samsung Electronics | 1        | 3.85%   |
| pqi                 | 1        | 3.85%   |
| Nanya Technology    | 1        | 3.85%   |
| Corsair             | 1        | 3.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| G.Skill RAM F3-12800CL8-4GBXM 4GB DIMM DDR3 1600MT/s     | 3        | 9.68%   |
| Unknown RAM Module 8192MB DIMM                           | 2        | 6.45%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s             | 2        | 6.45%   |
| Unknown RAM Module 4096MB DIMM                           | 2        | 6.45%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s            | 2        | 6.45%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                   | 2        | 6.45%   |
| Kingston RAM 99U5471-011.A 2048MB DIMM DDR3 667MT/s      | 2        | 6.45%   |
| Kingston RAM 99U5471-002.A 2048MB DIMM DDR3 667MT/s      | 2        | 6.45%   |
| Crucial RAM CT51264BA160B.C16F 4GB DIMM DDR3 1600MT/s    | 2        | 6.45%   |
| Unknown RAM Module 4096MB SODIMM DDR2 800MT/s            | 1        | 3.23%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 1        | 3.23%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                   | 1        | 3.23%   |
| Unknown RAM Module 1024MB SODIMM DDR2 800MT/s            | 1        | 3.23%   |
| Unknown RAM Module 1024MB DIMM DDR 333MT/s               | 1        | 3.23%   |
| Samsung RAM M471B5273DH0-YK0 4GB DIMM DDR3 1600MT/s      | 1        | 3.23%   |
| pqi RAM Module 1024MB DIMM DDR2 800MT/s                  | 1        | 3.23%   |
| Nanya RAM Module 2048MB DIMM DDR2 800MT/s                | 1        | 3.23%   |
| Kingston RAM Module 2048MB DIMM DDR2 533MT/s             | 1        | 3.23%   |
| Kingston RAM 99U5471-020.A00LF 4096MB DIMM DDR3 1600MT/s | 1        | 3.23%   |
| Kingston RAM 99P5471-002.A 2048MB DIMM DDR3 667MT/s      | 1        | 3.23%   |
| Corsair RAM CMK16GX4M2A2400C16 8GB DIMM DDR4 2933MT/s    | 1        | 3.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 8        | 36.36%  |
| Unknown | 8        | 36.36%  |
| DDR2    | 4        | 18.18%  |
| DDR4    | 1        | 4.55%   |
| DDR     | 1        | 4.55%   |

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


| Size | Desktops | Percent |
|------|----------|---------|
| 4096 | 10       | 40%     |
| 2048 | 9        | 36%     |
| 8192 | 3        | 12%     |
| 1024 | 3        | 12%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 6        | 25%     |
| 667     | 4        | 16.67%  |
| Unknown | 4        | 16.67%  |
| 1333    | 3        | 12.5%   |
| 800     | 3        | 12.5%   |
| 2933    | 1        | 4.17%   |
| 533     | 1        | 4.17%   |
| 400     | 1        | 4.17%   |
| 333     | 1        | 4.17%   |

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

Zero info for selected period =(

Camera Model
------------

Camera device models

Zero info for selected period =(

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
| 0     | 14       | 46.67%  |
| 1     | 12       | 40%     |
| 2     | 3        | 10%     |
| 4     | 1        | 3.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 13       | 72.22%  |
| Network                  | 1        | 5.56%   |
| Net/wireless             | 1        | 5.56%   |
| Net/ethernet             | 1        | 5.56%   |
| Communication controller | 1        | 5.56%   |
| Card reader              | 1        | 5.56%   |

