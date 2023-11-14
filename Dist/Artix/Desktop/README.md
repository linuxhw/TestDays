Artix - Tested Hardware & Statistics (Desktops)
-----------------------------------------------

A project to collect tested hardware configurations for Artix.

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

Total: 103

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| MACHINIST | X99-MR9D PLUS V1.0          | [aaeff9a386](https://linux-hardware.org/?probe=aaeff9a386) | Oct 20, 2023 |
| Biostar   | A320MH                      | [d797fd8fa3](https://linux-hardware.org/?probe=d797fd8fa3) | Oct 15, 2023 |
| MSI       | Z97 PC Mate                 | [6e2fa2dc88](https://linux-hardware.org/?probe=6e2fa2dc88) | Oct 07, 2023 |
| MSI       | MPG X570 GAMING EDGE WIF... | [20ba60e073](https://linux-hardware.org/?probe=20ba60e073) | Sep 21, 2023 |
| MSI       | H170M PRO-DH                | [0eb433075b](https://linux-hardware.org/?probe=0eb433075b) | Aug 12, 2023 |
| MACHINIST | X99-MR9D PLUS V1.0          | [29f8d73c0e](https://linux-hardware.org/?probe=29f8d73c0e) | Aug 05, 2023 |
| MACHINIST | X99-MR9D PLUS V1.0          | [d1ef825b01](https://linux-hardware.org/?probe=d1ef825b01) | Jul 24, 2023 |
| MSI       | X399 GAMING PRO CARBON A... | [b9bef208f1](https://linux-hardware.org/?probe=b9bef208f1) | Jun 26, 2023 |
| ASUSTek   | K30BF_M32BF_A_F_K31BF_6     | [7a56496149](https://linux-hardware.org/?probe=7a56496149) | Jun 16, 2023 |
| Dell      | 0DWPVW A00                  | [94a28f2fec](https://linux-hardware.org/?probe=94a28f2fec) | Jun 16, 2023 |
| MSI       | PRO Z790-A WIFI             | [1c7cc37995](https://linux-hardware.org/?probe=1c7cc37995) | Jun 03, 2023 |
| MSI       | H110M PRO-VH PLUS           | [14985fd04f](https://linux-hardware.org/?probe=14985fd04f) | May 18, 2023 |
| Gigabyte  | H410M H                     | [f115dd1851](https://linux-hardware.org/?probe=f115dd1851) | May 03, 2023 |
| MSI       | B350M PRO-VDH               | [a15fa484d4](https://linux-hardware.org/?probe=a15fa484d4) | Apr 26, 2023 |
| ASUSTek   | ROG STRIX B350-F GAMING     | [18111d76fc](https://linux-hardware.org/?probe=18111d76fc) | Apr 17, 2023 |
| Intel     | X99H                        | [b91cbf41c0](https://linux-hardware.org/?probe=b91cbf41c0) | Apr 06, 2023 |
| ASRock    | Z690 Taichi                 | [fbad15ab18](https://linux-hardware.org/?probe=fbad15ab18) | Mar 24, 2023 |
| ASRock    | Z690 Taichi                 | [76159d5fc4](https://linux-hardware.org/?probe=76159d5fc4) | Mar 22, 2023 |
| ASUSTek   | F2A55-M LE                  | [47c7f6e38d](https://linux-hardware.org/?probe=47c7f6e38d) | Mar 03, 2023 |
| ASUSTek   | TUF Gaming B550M-PLUS       | [7ad97f8b6d](https://linux-hardware.org/?probe=7ad97f8b6d) | Feb 09, 2023 |
| ASUSTek   | ROG STRIX Z370-G GAMING     | [84fb689a7e](https://linux-hardware.org/?probe=84fb689a7e) | Feb 06, 2023 |
| ASUSTek   | ROG STRIX Z370-G GAMING     | [405641895c](https://linux-hardware.org/?probe=405641895c) | Jan 18, 2023 |
| Gigabyte  | B450 AORUS PRO WIFI-CF      | [b79de349a9](https://linux-hardware.org/?probe=b79de349a9) | Jan 01, 2023 |
| Gigabyte  | X570 AORUS ELITE WIFI       | [f17f99d4e6](https://linux-hardware.org/?probe=f17f99d4e6) | Nov 30, 2022 |
| Gigabyte  | B550M AORUS PRO             | [d72c486584](https://linux-hardware.org/?probe=d72c486584) | Oct 22, 2022 |
| Gigabyte  | B450 AORUS PRO WIFI-CF      | [6cbb7cbc35](https://linux-hardware.org/?probe=6cbb7cbc35) | Oct 17, 2022 |
| Gigabyte  | B450 AORUS PRO WIFI-CF      | [ca934ff06b](https://linux-hardware.org/?probe=ca934ff06b) | Oct 16, 2022 |
| MSI       | H410M PRO-VH                | [f632032d8c](https://linux-hardware.org/?probe=f632032d8c) | Aug 13, 2022 |
| Gigabyte  | Z77X-UD3H                   | [db843c1cae](https://linux-hardware.org/?probe=db843c1cae) | Aug 07, 2022 |
| Gigabyte  | AB350M-DS3H V2-CF           | [00d543ee46](https://linux-hardware.org/?probe=00d543ee46) | Jul 07, 2022 |
| Gigabyte  | H61MA-D3V                   | [f07968d013](https://linux-hardware.org/?probe=f07968d013) | Jul 07, 2022 |
| ASRock    | B460 Phantom Gaming 4       | [a4054a2ac8](https://linux-hardware.org/?probe=a4054a2ac8) | Jun 10, 2022 |
| ASUSTek   | M5A97 LE R2.0               | [009ea9b40a](https://linux-hardware.org/?probe=009ea9b40a) | Jun 09, 2022 |
| MSI       | MPG X570 GAMING PLUS        | [0e42effbfb](https://linux-hardware.org/?probe=0e42effbfb) | May 17, 2022 |
| Gigabyte  | X570 AORUS ULTRA            | [ea492e2997](https://linux-hardware.org/?probe=ea492e2997) | May 13, 2022 |
| Gigabyte  | HA65M-D2H-B3                | [313e83e0ef](https://linux-hardware.org/?probe=313e83e0ef) | Mar 10, 2022 |
| ASUSTek   | PRIME B350M-A               | [299a727e8a](https://linux-hardware.org/?probe=299a727e8a) | Mar 02, 2022 |
| MSI       | B550-A PRO                  | [b16ba2b14a](https://linux-hardware.org/?probe=b16ba2b14a) | Jan 31, 2022 |
| ASRock    | B150M Pro4S/D3              | [b7a65f897c](https://linux-hardware.org/?probe=b7a65f897c) | Jan 29, 2022 |
| MSI       | B350M PRO-VDH               | [29b6159e9c](https://linux-hardware.org/?probe=29b6159e9c) | Jan 12, 2022 |
| ASUSTek   | ROG STRIX X570-F GAMING     | [ca93455055](https://linux-hardware.org/?probe=ca93455055) | Jan 07, 2022 |
| ASUSTek   | Pro WS X570-ACE             | [1a7ef57da7](https://linux-hardware.org/?probe=1a7ef57da7) | Jan 07, 2022 |
| ASRock    | B450 Steel Legend           | [44ccc8eb49](https://linux-hardware.org/?probe=44ccc8eb49) | Nov 24, 2021 |
| MSI       | B450 TOMAHAWK MAX           | [9fca12db52](https://linux-hardware.org/?probe=9fca12db52) | Nov 22, 2021 |
| HP        | 1495                        | [e7c0f59f92](https://linux-hardware.org/?probe=e7c0f59f92) | Oct 15, 2021 |
| ASUSTek   | ROG Maximus XI HERO         | [e2c619e8dd](https://linux-hardware.org/?probe=e2c619e8dd) | Oct 12, 2021 |
| ASUSTek   | ROG Maximus XI HERO         | [1e612081c8](https://linux-hardware.org/?probe=1e612081c8) | Oct 02, 2021 |
| MSI       | X470 GAMING PLUS            | [d5871d0e2a](https://linux-hardware.org/?probe=d5871d0e2a) | Aug 25, 2021 |
| MSI       | MPG X570 GAMING PLUS        | [ec331e992a](https://linux-hardware.org/?probe=ec331e992a) | Aug 08, 2021 |
| ASUSTek   | PRIME B450M-A               | [558e1369e9](https://linux-hardware.org/?probe=558e1369e9) | Jul 25, 2021 |
| ASUSTek   | P8H61-M LX3 R2.0            | [156577ba27](https://linux-hardware.org/?probe=156577ba27) | Jul 18, 2021 |
| ASRock    | H310CM-DVS                  | [f8e9ea8ffa](https://linux-hardware.org/?probe=f8e9ea8ffa) | Jun 26, 2021 |
| MSI       | Z270M MORTAR                | [5c54607559](https://linux-hardware.org/?probe=5c54607559) | Jun 22, 2021 |
| ASUSTek   | ROG STRIX Z370-G GAMING     | [181bd83bdd](https://linux-hardware.org/?probe=181bd83bdd) | Jun 02, 2021 |
| ASRock    | FM2A88X-ITX+                | [2b91e357ca](https://linux-hardware.org/?probe=2b91e357ca) | May 16, 2021 |
| ASRock    | FM2A88X-ITX+                | [057546c50e](https://linux-hardware.org/?probe=057546c50e) | Apr 30, 2021 |
| ASUSTek   | SABERTOOTH 990FX R2.0       | [d1cf148ec4](https://linux-hardware.org/?probe=d1cf148ec4) | Apr 24, 2021 |
| ASUSTek   | ROG STRIX Z370-G GAMING     | [132c1a0515](https://linux-hardware.org/?probe=132c1a0515) | Apr 08, 2021 |
| ASUSTek   | ROG STRIX B550-F GAMING     | [5527015fb6](https://linux-hardware.org/?probe=5527015fb6) | Apr 08, 2021 |
| ASUSTek   | ROG STRIX Z370-G GAMING     | [10132d3ee3](https://linux-hardware.org/?probe=10132d3ee3) | Apr 05, 2021 |
| ASUSTek   | ROG STRIX Z370-G GAMING     | [62f6aa5c03](https://linux-hardware.org/?probe=62f6aa5c03) | Mar 27, 2021 |
| ASUSTek   | PRIME X370-PRO              | [91a16f1c67](https://linux-hardware.org/?probe=91a16f1c67) | Feb 21, 2021 |
| MSI       | X470 GAMING PLUS            | [f93e302542](https://linux-hardware.org/?probe=f93e302542) | Feb 15, 2021 |
| Alienware | 02XRCM A01                  | [554d3ebf2f](https://linux-hardware.org/?probe=554d3ebf2f) | Feb 14, 2021 |
| Gigabyte  | 970A-DS3P                   | [b4c4d7f99c](https://linux-hardware.org/?probe=b4c4d7f99c) | Feb 01, 2021 |
| Gigabyte  | 970A-DS3P                   | [70eabb568f](https://linux-hardware.org/?probe=70eabb568f) | Jan 30, 2021 |
| MSI       | X470 GAMING PLUS            | [fb3e2ec12b](https://linux-hardware.org/?probe=fb3e2ec12b) | Jan 24, 2021 |
| ASUSTek   | TUF B450-PLUS GAMING        | [fda5fabbf5](https://linux-hardware.org/?probe=fda5fabbf5) | Jan 21, 2021 |
| Dell      | 0K216C                      | [524206eff9](https://linux-hardware.org/?probe=524206eff9) | Jan 20, 2021 |
| Dell      | 0D9JG3 A00                  | [6c44448201](https://linux-hardware.org/?probe=6c44448201) | Jan 19, 2021 |
| ASUSTek   | P8B75-M LX PLUS             | [c53595bd26](https://linux-hardware.org/?probe=c53595bd26) | Jan 16, 2021 |
| ASRock    | X570 Phantom Gaming 4       | [335ee823bd](https://linux-hardware.org/?probe=335ee823bd) | Jan 16, 2021 |
| ASUSTek   | G11CD                       | [145a13d355](https://linux-hardware.org/?probe=145a13d355) | Jan 07, 2021 |
| ASUSTek   | G11CD                       | [dc70a6fae2](https://linux-hardware.org/?probe=dc70a6fae2) | Jan 07, 2021 |
| HP        | 2B34                        | [e48dc00e0a](https://linux-hardware.org/?probe=e48dc00e0a) | Jan 04, 2021 |
| Pegatron  | 2AC2A                       | [6dbd029143](https://linux-hardware.org/?probe=6dbd029143) | Jan 03, 2021 |
| Pegatron  | 2AC2A                       | [7dd04be8aa](https://linux-hardware.org/?probe=7dd04be8aa) | Jan 01, 2021 |
| ASUSTek   | TUF Gaming X570-PLUS        | [3f9f87f288](https://linux-hardware.org/?probe=3f9f87f288) | Dec 31, 2020 |
| ASUSTek   | TUF Gaming X570-PLUS        | [2acc15f485](https://linux-hardware.org/?probe=2acc15f485) | Dec 27, 2020 |
| Gigabyte  | X570 AORUS ELITE            | [64adbf132b](https://linux-hardware.org/?probe=64adbf132b) | Dec 08, 2020 |
| MSI       | Z87-G45 GAMING              | [cefff6c6c3](https://linux-hardware.org/?probe=cefff6c6c3) | Dec 05, 2020 |
| MSI       | Z87-G45 GAMING              | [cbcb59eb96](https://linux-hardware.org/?probe=cbcb59eb96) | Dec 03, 2020 |
| MSI       | B350M PRO-VDH               | [28b680c91d](https://linux-hardware.org/?probe=28b680c91d) | Nov 29, 2020 |
| Gigabyte  | 990FXA-UD3 R5               | [42a67a5d5e](https://linux-hardware.org/?probe=42a67a5d5e) | Nov 18, 2020 |
| Gigabyte  | 970A-DS3P                   | [848672f794](https://linux-hardware.org/?probe=848672f794) | Oct 13, 2020 |
| Gigabyte  | X399 AORUS XTREME-CF        | [1193653309](https://linux-hardware.org/?probe=1193653309) | Oct 04, 2020 |
| Gigabyte  | P55-USB3                    | [ceeced1246](https://linux-hardware.org/?probe=ceeced1246) | Oct 02, 2020 |
| ASUSTek   | H81M-C                      | [b062c35766](https://linux-hardware.org/?probe=b062c35766) | Sep 16, 2020 |
| ASUSTek   | G11CD                       | [962d52b690](https://linux-hardware.org/?probe=962d52b690) | Sep 14, 2020 |
| ASUSTek   | G11CD                       | [a663586db5](https://linux-hardware.org/?probe=a663586db5) | Sep 14, 2020 |
| ASUSTek   | TUF Gaming X570-PLUS        | [86215bb4fb](https://linux-hardware.org/?probe=86215bb4fb) | Aug 29, 2020 |
| MSI       | B450 TOMAHAWK MAX           | [e988296384](https://linux-hardware.org/?probe=e988296384) | Aug 19, 2020 |
| Gigabyte  | 990FXA-UD5                  | [d86cfc12cc](https://linux-hardware.org/?probe=d86cfc12cc) | Aug 19, 2020 |
| Gigabyte  | 990FXA-UD5                  | [937f502004](https://linux-hardware.org/?probe=937f502004) | Aug 18, 2020 |
| MSI       | Z87-G45 GAMING              | [5d992bbc09](https://linux-hardware.org/?probe=5d992bbc09) | Aug 11, 2020 |
| Gigabyte  | B450M DS3H-CF               | [ff7915ae78](https://linux-hardware.org/?probe=ff7915ae78) | Aug 07, 2020 |
| ASUSTek   | TUF Gaming X570-PLUS        | [a57e5d7e84](https://linux-hardware.org/?probe=a57e5d7e84) | Jul 08, 2020 |
| Intel     | DX58SO2 AAG10925-205        | [2e4066d769](https://linux-hardware.org/?probe=2e4066d769) | Jun 30, 2020 |
| ASUSTek   | TUF Gaming X570-PLUS        | [9623b5be2b](https://linux-hardware.org/?probe=9623b5be2b) | Jun 16, 2020 |
| ASUSTek   | TUF Gaming X570-PLUS        | [4125763b79](https://linux-hardware.org/?probe=4125763b79) | Jun 12, 2020 |
| ASUSTek   | TUF Gaming X570-PLUS        | [82af1cec2f](https://linux-hardware.org/?probe=82af1cec2f) | May 30, 2020 |
| ASUSTek   | TUF Gaming X570-PLUS        | [40adc1a5f5](https://linux-hardware.org/?probe=40adc1a5f5) | Apr 03, 2020 |
| Biostar   | G31D-M7                     | [9f6a5c0f39](https://linux-hardware.org/?probe=9f6a5c0f39) | Oct 25, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| Artix Rolling  | 46       | 63.01%  |
| Artix          | 18       | 24.66%  |
| Artix 20220123 | 2        | 2.74%   |
| Artix 20210726 | 2        | 2.74%   |
| Artix 20230501 | 1        | 1.37%   |
| Artix 20230320 | 1        | 1.37%   |
| Artix 20230306 | 1        | 1.37%   |
| Artix 20230215 | 1        | 1.37%   |
| Artix 20220713 | 1        | 1.37%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| Artix | 70       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.10.8-artix1-1        | 3        | 3.57%   |
| 6.2.6-artix1-1         | 2        | 2.38%   |
| 6.2.13-artix1-1        | 2        | 2.38%   |
| 6.1.8-artix1-1         | 2        | 2.38%   |
| 5.9.14-artix1-1        | 2        | 2.38%   |
| 5.8.8-artix1-1         | 2        | 2.38%   |
| 5.8.12-artix1-1        | 2        | 2.38%   |
| 5.7.6-artix1-1         | 2        | 2.38%   |
| 5.7.12-artix1-1        | 2        | 2.38%   |
| 5.18.16-artix1-1       | 2        | 2.38%   |
| 5.15.12-artix1-1       | 2        | 2.38%   |
| 5.12.14-artix1-1       | 2        | 2.38%   |
| 5.12.12-artix1-1       | 2        | 2.38%   |
| 5.11.16-artix1-1       | 2        | 2.38%   |
| 5.10.4-artix2-1        | 2        | 2.38%   |
| 6.5.7-artix1-1         | 1        | 1.19%   |
| 6.5.5-artix1-1         | 1        | 1.19%   |
| 6.5.2-zen1-1-zen       | 1        | 1.19%   |
| 6.4.4-artix1-1         | 1        | 1.19%   |
| 6.4.3-artix1-2         | 1        | 1.19%   |
| 6.4.15-lqx1-2-lqx      | 1        | 1.19%   |
| 6.4.10-artix1-1        | 1        | 1.19%   |
| 6.3.7-zen1-1-zen       | 1        | 1.19%   |
| 6.3.6-artix1-1         | 1        | 1.19%   |
| 6.3.2-zen1-1-zen       | 1        | 1.19%   |
| 6.2.11-artix1-1        | 1        | 1.19%   |
| 6.1.4-artix1-1         | 1        | 1.19%   |
| 6.1.32-1-lts           | 1        | 1.19%   |
| 6.1.12-artix1-1        | 1        | 1.19%   |
| 6.1.1-x64v1-xanmod1-1  | 1        | 1.19%   |
| 6.0.7-artix1-1         | 1        | 1.19%   |
| 6.0.1-arch1-1          | 1        | 1.19%   |
| 5.9.8-zen1-1-zen       | 1        | 1.19%   |
| 5.9.14-zen1-1-zen      | 1        | 1.19%   |
| 5.9.12-artix1-1        | 1        | 1.19%   |
| 5.9.10-artix1-1        | 1        | 1.19%   |
| 5.8.5-xanmod1-1-xanmod | 1        | 1.19%   |
| 5.8.14-artix1-1        | 1        | 1.19%   |
| 5.7.2-artix1-1         | 1        | 1.19%   |
| 5.4.197-1-lts54        | 1        | 1.19%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.9.14  | 3        | 3.57%   |
| 5.10.8  | 3        | 3.57%   |
| 6.2.6   | 2        | 2.38%   |
| 6.2.13  | 2        | 2.38%   |
| 6.1.8   | 2        | 2.38%   |
| 5.8.8   | 2        | 2.38%   |
| 5.8.12  | 2        | 2.38%   |
| 5.7.6   | 2        | 2.38%   |
| 5.7.12  | 2        | 2.38%   |
| 5.18.16 | 2        | 2.38%   |
| 5.15.12 | 2        | 2.38%   |
| 5.12.14 | 2        | 2.38%   |
| 5.12.12 | 2        | 2.38%   |
| 5.11.16 | 2        | 2.38%   |
| 5.10.4  | 2        | 2.38%   |
| 5.10.15 | 2        | 2.38%   |
| 6.5.7   | 1        | 1.19%   |
| 6.5.5   | 1        | 1.19%   |
| 6.5.2   | 1        | 1.19%   |
| 6.4.4   | 1        | 1.19%   |
| 6.4.3   | 1        | 1.19%   |
| 6.4.15  | 1        | 1.19%   |
| 6.4.10  | 1        | 1.19%   |
| 6.3.7   | 1        | 1.19%   |
| 6.3.6   | 1        | 1.19%   |
| 6.3.2   | 1        | 1.19%   |
| 6.2.11  | 1        | 1.19%   |
| 6.1.4   | 1        | 1.19%   |
| 6.1.32  | 1        | 1.19%   |
| 6.1.12  | 1        | 1.19%   |
| 6.1.1   | 1        | 1.19%   |
| 6.0.7   | 1        | 1.19%   |
| 6.0.1   | 1        | 1.19%   |
| 5.9.8   | 1        | 1.19%   |
| 5.9.12  | 1        | 1.19%   |
| 5.9.10  | 1        | 1.19%   |
| 5.8.5   | 1        | 1.19%   |
| 5.8.14  | 1        | 1.19%   |
| 5.7.2   | 1        | 1.19%   |
| 5.4.197 | 1        | 1.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 10       | 12.5%   |
| 5.15    | 7        | 8.75%   |
| 5.9     | 6        | 7.5%    |
| 5.8     | 6        | 7.5%    |
| 5.12    | 6        | 7.5%    |
| 6.2     | 5        | 6.25%   |
| 6.1     | 5        | 6.25%   |
| 5.7     | 4        | 5%      |
| 5.16    | 4        | 5%      |
| 5.11    | 4        | 5%      |
| 6.5     | 3        | 3.75%   |
| 6.4     | 3        | 3.75%   |
| 6.3     | 3        | 3.75%   |
| 5.18    | 3        | 3.75%   |
| 5.17    | 3        | 3.75%   |
| 6.0     | 2        | 2.5%    |
| 5.14    | 2        | 2.5%    |
| 5.13    | 2        | 2.5%    |
| 5.4     | 1        | 1.25%   |
| 4.19    | 1        | 1.25%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 70       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| KDE5       | 22       | 29.33%  |
| GNOME      | 11       | 14.67%  |
| XFCE       | 8        | 10.67%  |
| Unknown    | 7        | 9.33%   |
| X-Cinnamon | 6        | 8%      |
| MATE       | 6        | 8%      |
| i3         | 3        | 4%      |
| Cinnamon   | 3        | 4%      |
| bspwm      | 3        | 4%      |
| LXQt       | 2        | 2.67%   |
| sway       | 1        | 1.33%   |
| openbox    | 1        | 1.33%   |
| LXDE       | 1        | 1.33%   |
| DWM        | 1        | 1.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 53       | 73.61%  |
| Tty     | 11       | 15.28%  |
| Wayland | 5        | 6.94%   |
| Unknown | 3        | 4.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 28       | 37.84%  |
| SDDM    | 23       | 31.08%  |
| LightDM | 18       | 24.32%  |
| GDM     | 2        | 2.7%    |
| XDM     | 1        | 1.35%   |
| SLiM    | 1        | 1.35%   |
| LXDM    | 1        | 1.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 27       | 38.03%  |
| ru_RU   | 8        | 11.27%  |
| Unknown | 6        | 8.45%   |
| fr_FR   | 5        | 7.04%   |
| C       | 5        | 7.04%   |
| de_DE   | 3        | 4.23%   |
| pt_PT   | 2        | 2.82%   |
| pt_BR   | 2        | 2.82%   |
| en_GB   | 2        | 2.82%   |
| tr_TR   | 1        | 1.41%   |
| lt_LT   | 1        | 1.41%   |
| ja_JP   | 1        | 1.41%   |
| it_IT   | 1        | 1.41%   |
| es_MX   | 1        | 1.41%   |
| es_AR   | 1        | 1.41%   |
| en_IE   | 1        | 1.41%   |
| en_AU   | 1        | 1.41%   |
| el_GR   | 1        | 1.41%   |
| de_AT   | 1        | 1.41%   |
| bg_BG   | 1        | 1.41%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 49       | 69.01%  |
| BIOS | 22       | 30.99%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 46       | 65.71%  |
| Btrfs | 16       | 22.86%  |
| Xfs   | 4        | 5.71%   |
| F2fs  | 2        | 2.86%   |
| Tmpfs | 1        | 1.43%   |
| Jfs   | 1        | 1.43%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 54       | 75%     |
| Unknown | 14       | 19.44%  |
| MBR     | 4        | 5.56%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 51       | 70.83%  |
| Yes       | 21       | 29.17%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 51       | 71.83%  |
| Yes       | 20       | 28.17%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 20       | 28.57%  |
| MSI                 | 16       | 22.86%  |
| Gigabyte Technology | 16       | 22.86%  |
| ASRock              | 7        | 10%     |
| Dell                | 3        | 4.29%   |
| Intel               | 2        | 2.86%   |
| Hewlett-Packard     | 2        | 2.86%   |
| Biostar             | 2        | 2.86%   |
| MACHINIST           | 1        | 1.43%   |
| Alienware           | 1        | 1.43%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| MSI MS-7A38                    | 3        | 4.29%   |
| MSI MS-7C37                    | 2        | 2.86%   |
| MSI MS-7C02                    | 2        | 2.86%   |
| Gigabyte 970A-DS3P             | 2        | 2.86%   |
| MSI MS-7E07                    | 1        | 1.43%   |
| MSI MS-7C89                    | 1        | 1.43%   |
| MSI MS-7C56                    | 1        | 1.43%   |
| MSI MS-7B79                    | 1        | 1.43%   |
| MSI MS-7B09                    | 1        | 1.43%   |
| MSI MS-7A69                    | 1        | 1.43%   |
| MSI MS-7A15                    | 1        | 1.43%   |
| MSI MS-7982                    | 1        | 1.43%   |
| MSI MS-7850                    | 1        | 1.43%   |
| MACHINIST X99-MR9D PLUS V1.0   | 1        | 1.43%   |
| Intel X99                      | 1        | 1.43%   |
| Intel DX58SO2 AAG10925-205     | 1        | 1.43%   |
| HP Compaq 8200 Elite SFF PC    | 1        | 1.43%   |
| HP 280 G1 MT                   | 1        | 1.43%   |
| Gigabyte Z77X-UD3H             | 1        | 1.43%   |
| Gigabyte X570 AORUS ULTRA      | 1        | 1.43%   |
| Gigabyte X570 AORUS ELITE WIFI | 1        | 1.43%   |
| Gigabyte X570 AORUS ELITE      | 1        | 1.43%   |
| Gigabyte X399 AORUS XTREME     | 1        | 1.43%   |
| Gigabyte P55-USB3              | 1        | 1.43%   |
| Gigabyte HA65M-D2H-B3          | 1        | 1.43%   |
| Gigabyte H61MA-D3V             | 1        | 1.43%   |
| Gigabyte H410M H               | 1        | 1.43%   |
| Gigabyte B550M AORUS PRO       | 1        | 1.43%   |
| Gigabyte B450 AORUS PRO WIFI   | 1        | 1.43%   |
| Gigabyte AB350M-DS3H V2        | 1        | 1.43%   |
| Gigabyte 990FXA-UD5            | 1        | 1.43%   |
| Gigabyte 990FXA-UD3 R5         | 1        | 1.43%   |
| Dell OptiPlex 7060             | 1        | 1.43%   |
| Dell OptiPlex 5080             | 1        | 1.43%   |
| Dell Inspiron 530              | 1        | 1.43%   |
| Biostar G31D-M7                | 1        | 1.43%   |
| Biostar A320MH                 | 1        | 1.43%   |
| ASUS TUF Gaming X570-PLUS      | 1        | 1.43%   |
| ASUS TUF Gaming B550M-PLUS     | 1        | 1.43%   |
| ASUS TUF B450-PLUS GAMING      | 1        | 1.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS ROG              | 5        | 7.14%   |
| MSI MS-7A38           | 3        | 4.29%   |
| Gigabyte X570         | 3        | 4.29%   |
| ASUS TUF              | 3        | 4.29%   |
| ASUS PRIME            | 3        | 4.29%   |
| MSI MS-7C37           | 2        | 2.86%   |
| MSI MS-7C02           | 2        | 2.86%   |
| Gigabyte 970A-DS3P    | 2        | 2.86%   |
| Dell OptiPlex         | 2        | 2.86%   |
| MSI MS-7E07           | 1        | 1.43%   |
| MSI MS-7C89           | 1        | 1.43%   |
| MSI MS-7C56           | 1        | 1.43%   |
| MSI MS-7B79           | 1        | 1.43%   |
| MSI MS-7B09           | 1        | 1.43%   |
| MSI MS-7A69           | 1        | 1.43%   |
| MSI MS-7A15           | 1        | 1.43%   |
| MSI MS-7982           | 1        | 1.43%   |
| MSI MS-7850           | 1        | 1.43%   |
| MACHINIST X99-MR9D    | 1        | 1.43%   |
| Intel X99             | 1        | 1.43%   |
| Intel DX58SO2         | 1        | 1.43%   |
| HP Compaq             | 1        | 1.43%   |
| HP 280                | 1        | 1.43%   |
| Gigabyte Z77X-UD3H    | 1        | 1.43%   |
| Gigabyte X399         | 1        | 1.43%   |
| Gigabyte P55-USB3     | 1        | 1.43%   |
| Gigabyte HA65M-D2H-B3 | 1        | 1.43%   |
| Gigabyte H61MA-D3V    | 1        | 1.43%   |
| Gigabyte H410M        | 1        | 1.43%   |
| Gigabyte B550M        | 1        | 1.43%   |
| Gigabyte B450         | 1        | 1.43%   |
| Gigabyte AB350M-DS3H  | 1        | 1.43%   |
| Gigabyte 990FXA-UD5   | 1        | 1.43%   |
| Gigabyte 990FXA-UD3   | 1        | 1.43%   |
| Dell Inspiron         | 1        | 1.43%   |
| Biostar G31D-M7       | 1        | 1.43%   |
| Biostar A320MH        | 1        | 1.43%   |
| ASUS SABERTOOTH       | 1        | 1.43%   |
| ASUS Pro              | 1        | 1.43%   |
| ASUS P8H61-M          | 1        | 1.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 12       | 17.14%  |
| 2020 | 10       | 14.29%  |
| 2017 | 9        | 12.86%  |
| 2018 | 8        | 11.43%  |
| 2012 | 7        | 10%     |
| 2013 | 5        | 7.14%   |
| 2022 | 4        | 5.71%   |
| 2016 | 3        | 4.29%   |
| 2015 | 3        | 4.29%   |
| 2014 | 2        | 2.86%   |
| 2011 | 2        | 2.86%   |
| 2010 | 2        | 2.86%   |
| 2008 | 2        | 2.86%   |
| 2021 | 1        | 1.43%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 70       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 70       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 70       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 29       | 40.85%  |
| 8.01-16.0   | 18       | 25.35%  |
| 32.01-64.0  | 11       | 15.49%  |
| 64.01-256.0 | 7        | 9.86%   |
| 3.01-4.0    | 4        | 5.63%   |
| 4.01-8.0    | 1        | 1.41%   |
| 1.01-2.0    | 1        | 1.41%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 20       | 25.64%  |
| 2.01-3.0   | 17       | 21.79%  |
| 3.01-4.0   | 16       | 20.51%  |
| 1.01-2.0   | 15       | 19.23%  |
| 8.01-16.0  | 3        | 3.85%   |
| 0.51-1.0   | 3        | 3.85%   |
| 16.01-24.0 | 2        | 2.56%   |
| 0.01-0.5   | 2        | 2.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 29       | 39.73%  |
| 3      | 19       | 26.03%  |
| 1      | 12       | 16.44%  |
| 4      | 6        | 8.22%   |
| 6      | 4        | 5.48%   |
| 8      | 2        | 2.74%   |
| 7      | 1        | 1.37%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 56       | 80%     |
| Yes       | 14       | 20%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 68       | 97.14%  |
| No        | 2        | 2.86%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 36       | 51.43%  |
| Yes       | 34       | 48.57%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 39       | 55.71%  |
| Yes       | 31       | 44.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 12       | 16.9%   |
| Germany     | 10       | 14.08%  |
| Russia      | 8        | 11.27%  |
| France      | 7        | 9.86%   |
| Brazil      | 4        | 5.63%   |
| Greece      | 3        | 4.23%   |
| UK          | 2        | 2.82%   |
| Switzerland | 2        | 2.82%   |
| Poland      | 2        | 2.82%   |
| Finland     | 2        | 2.82%   |
| Canada      | 2        | 2.82%   |
| Bulgaria    | 2        | 2.82%   |
| Ukraine     | 1        | 1.41%   |
| Turkey      | 1        | 1.41%   |
| Slovenia    | 1        | 1.41%   |
| Netherlands | 1        | 1.41%   |
| Mexico      | 1        | 1.41%   |
| Lithuania   | 1        | 1.41%   |
| Japan       | 1        | 1.41%   |
| Italy       | 1        | 1.41%   |
| Iran        | 1        | 1.41%   |
| India       | 1        | 1.41%   |
| Hong Kong   | 1        | 1.41%   |
| Guatemala   | 1        | 1.41%   |
| Austria     | 1        | 1.41%   |
| Australia   | 1        | 1.41%   |
| Argentina   | 1        | 1.41%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Paris                  | 3        | 4.05%   |
| Moscow                 | 2        | 2.7%    |
| Helsinki               | 2        | 2.7%    |
| Frankfurt am Main      | 2        | 2.7%    |
| Charlotte              | 2        | 2.7%    |
| Bern                   | 2        | 2.7%    |
| Athens                 | 2        | 2.7%    |
| Wettringen             | 1        | 1.35%   |
| Vladivostok            | 1        | 1.35%   |
| Vilnius                | 1        | 1.35%   |
| Vienna                 | 1        | 1.35%   |
| Vancouver              | 1        | 1.35%   |
| Upper Norwood          | 1        | 1.35%   |
| Ufa                    | 1        | 1.35%   |
| Toronto                | 1        | 1.35%   |
| Thessaloniki           | 1        | 1.35%   |
| Tehran                 | 1        | 1.35%   |
| Sydney                 | 1        | 1.35%   |
| Surat                  | 1        | 1.35%   |
| Stein                  | 1        | 1.35%   |
| Stavropol              | 1        | 1.35%   |
| Statesboro             | 1        | 1.35%   |
| Sofia                  | 1        | 1.35%   |
| Snohomish              | 1        | 1.35%   |
| Shavertown             | 1        | 1.35%   |
| Saratov                | 1        | 1.35%   |
| Sao Paulo              | 1        | 1.35%   |
| San Miguel de Tucumán | 1        | 1.35%   |
| Rotherham              | 1        | 1.35%   |
| Rosmalen               | 1        | 1.35%   |
| Riverview              | 1        | 1.35%   |
| Rexburg                | 1        | 1.35%   |
| Plovdiv                | 1        | 1.35%   |
| Munich                 | 1        | 1.35%   |
| Maua                   | 1        | 1.35%   |
| Maebashi               | 1        | 1.35%   |
| Maceió                | 1        | 1.35%   |
| Lublin                 | 1        | 1.35%   |
| Ljubljana              | 1        | 1.35%   |
| Lafayette              | 1        | 1.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 31       | 56     | 19.38%  |
| Seagate                     | 23       | 31     | 14.38%  |
| Samsung Electronics         | 23       | 34     | 14.38%  |
| Kingston                    | 14       | 15     | 8.75%   |
| Crucial                     | 11       | 17     | 6.88%   |
| Toshiba                     | 9        | 10     | 5.63%   |
| SanDisk                     | 6        | 9      | 3.75%   |
| Intel                       | 4        | 7      | 2.5%    |
| Phison Electronics          | 3        | 6      | 1.88%   |
| Hitachi                     | 3        | 3      | 1.88%   |
| A-DATA Technology           | 3        | 3      | 1.88%   |
| SK hynix                    | 2        | 2      | 1.25%   |
| Maxtor                      | 2        | 2      | 1.25%   |
| JMicron Technology          | 2        | 2      | 1.25%   |
| Corsair                     | 2        | 2      | 1.25%   |
| China                       | 2        | 3      | 1.25%   |
| XUM                         | 1        | 1      | 0.63%   |
| USB3.0                      | 1        | 1      | 0.63%   |
| TS512GMT                    | 1        | 5      | 0.63%   |
| Transcend                   | 1        | 1      | 0.63%   |
| SPCC Sol                    | 1        | 1      | 0.63%   |
| SPCC                        | 1        | 1      | 0.63%   |
| Silicon Motion              | 1        | 1      | 0.63%   |
| PNY                         | 1        | 1      | 0.63%   |
| Plextor                     | 1        | 1      | 0.63%   |
| Phison                      | 1        | 1      | 0.63%   |
| Netac                       | 1        | 1      | 0.63%   |
| MAXIO Technology (Hangzhou) | 1        | 3      | 0.63%   |
| Linux                       | 1        | 1      | 0.63%   |
| KingSpec                    | 1        | 1      | 0.63%   |
| HGST                        | 1        | 2      | 0.63%   |
| Hewlett-Packard             | 1        | 1      | 0.63%   |
| GOODRAM                     | 1        | 1      | 0.63%   |
| Biostar                     | 1        | 1      | 0.63%   |
| AMD                         | 1        | 1      | 0.63%   |
| Unknown                     | 1        | 3      | 0.63%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB                            | 5        | 2.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 4        | 2.17%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 3        | 1.63%   |
| Seagate ST3500418AS 500GB                         | 3        | 1.63%   |
| Seagate ST1000DM010-2EP102 1TB                    | 3        | 1.63%   |
| Samsung SSD 860 EVO 250GB                         | 3        | 1.63%   |
| Crucial CT240BX500SSD1 240GB                      | 3        | 1.63%   |
| WDC WD80EZAZ-11TDBA0 8TB                          | 2        | 1.09%   |
| WDC WD40EZRZ-00WN9B0 4TB                          | 2        | 1.09%   |
| WDC WD10EZEX-22MFCA0 1TB                          | 2        | 1.09%   |
| WDC WD100EMAZ-00WJTA0 10TB                        | 2        | 1.09%   |
| Seagate ST500DM002-1BD142 500GB                   | 2        | 1.09%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 2        | 1.09%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                | 2        | 1.09%   |
| Samsung SSD 970 EVO 1TB                           | 2        | 1.09%   |
| Samsung SSD 840 EVO 250GB                         | 2        | 1.09%   |
| Phison PS5013 E13 NVMe Controller 256GB           | 2        | 1.09%   |
| Kingston SV300S37A240G 240GB SSD                  | 2        | 1.09%   |
| Kingston SA400S37480G 480GB SSD                   | 2        | 1.09%   |
| Kingston SA400S37120G 120GB SSD                   | 2        | 1.09%   |
| Crucial CT250MX500SSD1 250GB                      | 2        | 1.09%   |
| Crucial CT1000MX500SSD1 1TB                       | 2        | 1.09%   |
| A-DATA SU650 240GB SSD                            | 2        | 1.09%   |
| XUM HX256GSSDSATA3 256GB                          | 1        | 0.54%   |
| WDC WDS500G2B0C-00PXH0 500GB                      | 1        | 0.54%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 1        | 0.54%   |
| WDC WDS256G1X0C-00ENX0 256GB                      | 1        | 0.54%   |
| WDC WDS100T2B0C-00PXH0 1TB                        | 1        | 0.54%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                    | 1        | 0.54%   |
| WDC WDBNCE5000PNC 500GB SSD                       | 1        | 0.54%   |
| WDC WD80EFBX-68AZZN0 8TB                          | 1        | 0.54%   |
| WDC WD6001FZWX-00A2VA0 6TB                        | 1        | 0.54%   |
| WDC WD5003ABYX-18WERA0 500GB                      | 1        | 0.54%   |
| WDC WD5000LPVX-00V0TT0 500GB                      | 1        | 0.54%   |
| WDC WD5000LPLX-75ZNTT0 500GB                      | 1        | 0.54%   |
| WDC WD5000AVCS-632DY1 500GB                       | 1        | 0.54%   |
| WDC WD5000AAKX-60U6AA0 500GB                      | 1        | 0.54%   |
| WDC WD4003FZEX-00Z4SA0 4TB                        | 1        | 0.54%   |
| WDC WD4003FFBX-68MU3N0 4TB                        | 1        | 0.54%   |
| WDC WD4002FFWX-68TZ4N0 4TB                        | 1        | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 28       | 48     | 40.58%  |
| Seagate             | 23       | 31     | 33.33%  |
| Toshiba             | 9        | 10     | 13.04%  |
| Hitachi             | 3        | 3      | 4.35%   |
| Maxtor              | 2        | 2      | 2.9%    |
| USB3.0              | 1        | 1      | 1.45%   |
| Samsung Electronics | 1        | 1      | 1.45%   |
| JMicron Technology  | 1        | 1      | 1.45%   |
| HGST                | 1        | 2      | 1.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 13       | 17     | 22.03%  |
| Kingston            | 12       | 13     | 20.34%  |
| Crucial             | 11       | 17     | 18.64%  |
| WDC                 | 3        | 5      | 5.08%   |
| A-DATA Technology   | 3        | 3      | 5.08%   |
| SanDisk             | 2        | 2      | 3.39%   |
| Intel               | 2        | 3      | 3.39%   |
| China               | 2        | 3      | 3.39%   |
| XUM                 | 1        | 1      | 1.69%   |
| SPCC Sol            | 1        | 1      | 1.69%   |
| SPCC                | 1        | 1      | 1.69%   |
| SK hynix            | 1        | 1      | 1.69%   |
| Plextor             | 1        | 1      | 1.69%   |
| Netac               | 1        | 1      | 1.69%   |
| Linux               | 1        | 1      | 1.69%   |
| KingSpec            | 1        | 1      | 1.69%   |
| GOODRAM             | 1        | 1      | 1.69%   |
| Biostar             | 1        | 1      | 1.69%   |
| AMD                 | 1        | 1      | 1.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 54       | 99     | 39.71%  |
| SSD     | 49       | 74     | 36.03%  |
| NVMe    | 31       | 50     | 22.79%  |
| Unknown | 2        | 8      | 1.47%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 66       | 168    | 63.46%  |
| NVMe | 30       | 49     | 28.85%  |
| SAS  | 8        | 14     | 7.69%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 52       | 82     | 45.61%  |
| 0.51-1.0   | 33       | 52     | 28.95%  |
| 1.01-2.0   | 13       | 14     | 11.4%   |
| 4.01-10.0  | 6        | 13     | 5.26%   |
| 3.01-4.0   | 5        | 7      | 4.39%   |
| 2.01-3.0   | 5        | 5      | 4.39%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 15       | 20.83%  |
| More than 3000 | 14       | 19.44%  |
| 2001-3000      | 12       | 16.67%  |
| 101-250        | 11       | 15.28%  |
| 501-1000       | 10       | 13.89%  |
| 251-500        | 7        | 9.72%   |
| 51-100         | 2        | 2.78%   |
| Unknown        | 1        | 1.39%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 13       | 17.81%  |
| 251-500        | 11       | 15.07%  |
| 1001-2000      | 11       | 15.07%  |
| 101-250        | 10       | 13.7%   |
| 1-20           | 9        | 12.33%  |
| More than 3000 | 8        | 10.96%  |
| 21-50          | 4        | 5.48%   |
| 2001-3000      | 3        | 4.11%   |
| 51-100         | 3        | 4.11%   |
| Unknown        | 1        | 1.37%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD5000AVCS-632DY1 500GB       | 1        | 1      | 6.25%   |
| WDC WD3200AAKX-00ERMA0 320GB      | 1        | 1      | 6.25%   |
| WDC WD30EZRX-00DC0B0 3TB          | 1        | 1      | 6.25%   |
| Toshiba MK7575GSX 752GB           | 1        | 1      | 6.25%   |
| Toshiba DT01ACA100 1TB            | 1        | 1      | 6.25%   |
| Seagate ST8000DM004-2CX188 8TB    | 1        | 1      | 6.25%   |
| Seagate ST6000VN0033-2EE110 6TB   | 1        | 1      | 6.25%   |
| Seagate ST2000DX002-2DV164 2TB    | 1        | 1      | 6.25%   |
| Seagate ST2000DM006-2DM164 2TB    | 1        | 1      | 6.25%   |
| Maxtor 6Y080M0 80GB               | 1        | 1      | 6.25%   |
| Kingston SUV400S37240G 240GB SSD  | 1        | 1      | 6.25%   |
| Kingston SA400S37120G 120GB SSD   | 1        | 1      | 6.25%   |
| Intel SSDSC2BW480A4 480GB         | 1        | 2      | 6.25%   |
| Intel SSDPEKKW128G7 128GB         | 1        | 1      | 6.25%   |
| Hewlett-Packard SSD EX900 250GB   | 1        | 1      | 6.25%   |
| A-DATA Technology SU650 240GB SSD | 1        | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| Seagate           | 4        | 4      | 25%     |
| WDC               | 3        | 3      | 18.75%  |
| Toshiba           | 2        | 2      | 12.5%   |
| Kingston          | 2        | 2      | 12.5%   |
| Intel             | 2        | 3      | 12.5%   |
| Maxtor            | 1        | 1      | 6.25%   |
| Hewlett-Packard   | 1        | 1      | 6.25%   |
| A-DATA Technology | 1        | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 4      | 40%     |
| WDC     | 3        | 3      | 30%     |
| Toshiba | 2        | 2      | 20%     |
| Maxtor  | 1        | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 9        | 10     | 60%     |
| SSD  | 4        | 5      | 26.67%  |
| NVMe | 2        | 2      | 13.33%  |

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
| Works    | 43       | 121    | 48.86%  |
| Detected | 30       | 92     | 34.09%  |
| Malfunc  | 14       | 17     | 15.91%  |
| Fixed    | 1        | 1      | 1.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| AMD                         | 39       | 34.51%  |
| Intel                       | 32       | 28.32%  |
| Samsung Electronics         | 12       | 10.62%  |
| SanDisk                     | 6        | 5.31%   |
| Phison Electronics          | 6        | 5.31%   |
| Marvell Technology Group    | 5        | 4.42%   |
| ASMedia Technology          | 4        | 3.54%   |
| Silicon Motion              | 3        | 2.65%   |
| Kingston Technology Company | 2        | 1.77%   |
| SK hynix                    | 1        | 0.88%   |
| MAXIO Technology (Hangzhou) | 1        | 0.88%   |
| JMicron Technology          | 1        | 0.88%   |
| Broadcom / LSI              | 1        | 0.88%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 28       | 20.14%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 10       | 7.19%   |
| AMD 400 Series Chipset SATA Controller                                         | 7        | 5.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 6        | 4.32%   |
| AMD 300 Series Chipset SATA Controller                                         | 6        | 4.32%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4        | 2.88%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4        | 2.88%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 4        | 2.88%   |
| AMD 500 Series Chipset SATA Controller                                         | 4        | 2.88%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 3        | 2.16%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 3        | 2.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3        | 2.16%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3        | 2.16%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 2        | 1.44%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 2        | 1.44%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2        | 1.44%   |
| Phison E12 NVMe Controller                                                     | 2        | 1.44%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2        | 1.44%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2        | 1.44%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2        | 1.44%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2        | 1.44%   |
| AMD X399 Series Chipset SATA Controller                                        | 2        | 1.44%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 1        | 0.72%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1        | 0.72%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 1        | 0.72%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1        | 0.72%   |
| SanDisk WD Black NVMe SSD                                                      | 1        | 0.72%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 1        | 0.72%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 0.72%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 1        | 0.72%   |
| Phison E18 PCIe4 NVMe Controller                                               | 1        | 0.72%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 1        | 0.72%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                          | 1        | 0.72%   |
| Marvell Group 88SE912x IDE Controller                                          | 1        | 0.72%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                           | 1        | 0.72%   |
| Kingston Company NV1 NVMe SSD SM2263XT                                         | 1        | 0.72%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 1        | 0.72%   |
| JMicron JMB363 SATA/IDE Controller                                             | 1        | 0.72%   |
| Intel SSD 660P Series                                                          | 1        | 0.72%   |
| Intel SSD 600P Series                                                          | 1        | 0.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 67       | 62.62%  |
| NVMe | 30       | 28.04%  |
| IDE  | 8        | 7.48%   |
| RAID | 1        | 0.93%   |
| SAS  | 1        | 0.93%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 39       | 55.71%  |
| Intel  | 31       | 44.29%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD FX-8350 Eight-Core Processor                | 4        | 5.71%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 3        | 4.29%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 3        | 4.29%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 3        | 4.29%   |
| AMD Ryzen 5 2600X Six-Core Processor            | 3        | 4.29%   |
| Intel Core i7-9700K CPU @ 3.60GHz               | 2        | 2.86%   |
| Intel Core i5-6600K CPU @ 3.50GHz               | 2        | 2.86%   |
| Intel Core i5-2500 CPU @ 3.30GHz                | 2        | 2.86%   |
| Intel Core i5-10400F CPU @ 2.90GHz              | 2        | 2.86%   |
| AMD Ryzen 7 5700G with Radeon Graphics          | 2        | 2.86%   |
| AMD Ryzen 5 5600X 6-Core Processor              | 2        | 2.86%   |
| AMD Ryzen 5 3600 6-Core Processor               | 2        | 2.86%   |
| AMD Ryzen 5 1600 Six-Core Processor             | 2        | 2.86%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz             | 1        | 1.43%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz             | 1        | 1.43%   |
| Intel Pentium CPU G4560 @ 3.50GHz               | 1        | 1.43%   |
| Intel Core i7-9700F CPU @ 3.00GHz               | 1        | 1.43%   |
| Intel Core i7-4790K CPU @ 4.00GHz               | 1        | 1.43%   |
| Intel Core i7 CPU 970 @ 3.20GHz                 | 1        | 1.43%   |
| Intel Core i5-9600K CPU @ 3.70GHz               | 1        | 1.43%   |
| Intel Core i5-8500 CPU @ 3.00GHz                | 1        | 1.43%   |
| Intel Core i5-7600K CPU @ 3.80GHz               | 1        | 1.43%   |
| Intel Core i5-6400 CPU @ 2.70GHz                | 1        | 1.43%   |
| Intel Core i5-4670K CPU @ 3.40GHz               | 1        | 1.43%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 1        | 1.43%   |
| Intel Core i5-3330 CPU @ 3.00GHz                | 1        | 1.43%   |
| Intel Core i5-2310 CPU @ 2.90GHz                | 1        | 1.43%   |
| Intel Core i5-10500T CPU @ 2.30GHz              | 1        | 1.43%   |
| Intel Core i5 CPU 660 @ 3.33GHz                 | 1        | 1.43%   |
| Intel Core i3-2120 CPU @ 3.30GHz                | 1        | 1.43%   |
| Intel Core i3-10100 CPU @ 3.60GHz               | 1        | 1.43%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz            | 1        | 1.43%   |
| Intel Core 2 Duo CPU E4600 @ 2.40GHz            | 1        | 1.43%   |
| Intel Celeron CPU G1840 @ 2.80GHz               | 1        | 1.43%   |
| Intel 12th Gen Core i9-12900K                   | 1        | 1.43%   |
| Intel 12th Gen Core i5-12600K                   | 1        | 1.43%   |
| AMD Ryzen Threadripper 2990WX 32-Core Processor | 1        | 1.43%   |
| AMD Ryzen Threadripper 1900X 8-Core Processor   | 1        | 1.43%   |
| AMD Ryzen 9 3900XT 12-Core Processor            | 1        | 1.43%   |
| AMD Ryzen 7 5800X 8-Core Processor              | 1        | 1.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 16       | 22.86%  |
| AMD Ryzen 7            | 11       | 15.71%  |
| AMD Ryzen 5            | 11       | 15.71%  |
| Intel Core i7          | 5        | 7.14%   |
| AMD FX                 | 5        | 7.14%   |
| AMD Ryzen 9            | 4        | 5.71%   |
| Other                  | 2        | 2.86%   |
| Intel Xeon             | 2        | 2.86%   |
| Intel Core i3          | 2        | 2.86%   |
| Intel Core 2 Duo       | 2        | 2.86%   |
| AMD Ryzen Threadripper | 2        | 2.86%   |
| AMD A10                | 2        | 2.86%   |
| Intel Pentium          | 1        | 1.43%   |
| Intel Celeron          | 1        | 1.43%   |
| AMD Ryzen 3            | 1        | 1.43%   |
| AMD Phenom II X4       | 1        | 1.43%   |
| AMD Athlon             | 1        | 1.43%   |
| AMD A6                 | 1        | 1.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 18       | 25.71%  |
| 6      | 17       | 24.29%  |
| 8      | 15       | 21.43%  |
| 2      | 9        | 12.86%  |
| 12     | 4        | 5.71%   |
| 3      | 2        | 2.86%   |
| 32     | 1        | 1.43%   |
| 16     | 1        | 1.43%   |
| 14     | 1        | 1.43%   |
| 10     | 1        | 1.43%   |
| 1      | 1        | 1.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 70       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 50       | 71.43%  |
| 1      | 20       | 28.57%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 70       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 23       | 31.51%  |
| 0x0800820d | 6        | 8.22%   |
| 0x08701013 | 5        | 6.85%   |
| 0x08701021 | 4        | 5.48%   |
| 0x906ed    | 3        | 4.11%   |
| 0x206a7    | 3        | 4.11%   |
| 0x06000822 | 3        | 4.11%   |
| 0xa0655    | 2        | 2.74%   |
| 0x506e3    | 2        | 2.74%   |
| 0x306c3    | 2        | 2.74%   |
| 0x0a201016 | 2        | 2.74%   |
| 0x06003106 | 2        | 2.74%   |
| 0x06000852 | 2        | 2.74%   |
| 0xa0653    | 1        | 1.37%   |
| 0x906e9    | 1        | 1.37%   |
| 0x6fd      | 1        | 1.37%   |
| 0x306a9    | 1        | 1.37%   |
| 0x206c2    | 1        | 1.37%   |
| 0x20652    | 1        | 1.37%   |
| 0x1067a    | 1        | 1.37%   |
| 0x0a50000b | 1        | 1.37%   |
| 0x0a201009 | 1        | 1.37%   |
| 0x08108109 | 1        | 1.37%   |
| 0x0800820b | 1        | 1.37%   |
| 0x08001138 | 1        | 1.37%   |
| 0x08001137 | 1        | 1.37%   |
| 0x08001129 | 1        | 1.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen+             | 10       | 14.29%  |
| Zen 2            | 10       | 14.29%  |
| KabyLake         | 7        | 10%     |
| Zen 3            | 6        | 8.57%   |
| Piledriver       | 6        | 8.57%   |
| Zen              | 4        | 5.71%   |
| SandyBridge      | 4        | 5.71%   |
| Haswell          | 4        | 5.71%   |
| CometLake        | 4        | 5.71%   |
| Skylake          | 3        | 4.29%   |
| Westmere         | 2        | 2.86%   |
| Steamroller      | 2        | 2.86%   |
| IvyBridge        | 2        | 2.86%   |
| Alderlake Hybrid | 2        | 2.86%   |
| Penryn           | 1        | 1.43%   |
| K10              | 1        | 1.43%   |
| Core             | 1        | 1.43%   |
| Broadwell        | 1        | 1.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 40       | 53.33%  |
| Nvidia | 26       | 34.67%  |
| Intel  | 9        | 12%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 9        | 11.54%  |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 6        | 7.69%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 3        | 3.85%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 2        | 2.56%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 2.56%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 2.56%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 2.56%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 2        | 2.56%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 2.56%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 2.56%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 2        | 2.56%   |
| AMD Redwood XT [Radeon HD 5670/5690/5730]                                   | 2        | 2.56%   |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                    | 2        | 2.56%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2        | 2.56%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 2.56%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 2        | 2.56%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 2.56%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 1.28%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 1.28%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 1.28%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                          | 1        | 1.28%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.28%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.28%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 1.28%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.28%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.28%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 1.28%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 1.28%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.28%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                           | 1        | 1.28%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.28%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 1.28%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 1        | 1.28%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 1.28%   |
| Intel HD Graphics 610                                                       | 1        | 1.28%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.28%   |
| Intel AlderLake-S GT1                                                       | 1        | 1.28%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.28%   |
| AMD Vega 20 [Radeon VII]                                                    | 1        | 1.28%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1        | 1.28%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 35       | 49.3%   |
| 1 x Nvidia     | 23       | 32.39%  |
| 1 x Intel      | 7        | 9.86%   |
| 2 x AMD        | 3        | 4.23%   |
| AMD + Nvidia   | 2        | 2.82%   |
| Intel + Nvidia | 1        | 1.41%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 52       | 72.22%  |
| Proprietary | 20       | 27.78%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 25       | 33.33%  |
| 7.01-8.0   | 16       | 21.33%  |
| 3.01-4.0   | 11       | 14.67%  |
| 1.01-2.0   | 9        | 12%     |
| 8.01-16.0  | 6        | 8%      |
| 0.51-1.0   | 6        | 8%      |
| 5.01-6.0   | 1        | 1.33%   |
| 0.01-0.5   | 1        | 1.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 14       | 15.22%  |
| Acer                 | 11       | 11.96%  |
| Goldstar             | 10       | 10.87%  |
| Philips              | 8        | 8.7%    |
| AOC                  | 8        | 8.7%    |
| Dell                 | 6        | 6.52%   |
| BenQ                 | 5        | 5.43%   |
| ASUSTek Computer     | 5        | 5.43%   |
| Ancor Communications | 3        | 3.26%   |
| MSI                  | 2        | 2.17%   |
| ViewSonic            | 1        | 1.09%   |
| Vestel Elektronik    | 1        | 1.09%   |
| Unknown              | 1        | 1.09%   |
| Sony                 | 1        | 1.09%   |
| Packard Bell         | 1        | 1.09%   |
| LG Electronics       | 1        | 1.09%   |
| Lenovo Group Limited | 1        | 1.09%   |
| Lenovo               | 1        | 1.09%   |
| KTC                  | 1        | 1.09%   |
| Jean                 | 1        | 1.09%   |
| Iiyama               | 1        | 1.09%   |
| Idek Iiyama          | 1        | 1.09%   |
| HVR                  | 1        | 1.09%   |
| Hitachi              | 1        | 1.09%   |
| Hewlett-Packard      | 1        | 1.09%   |
| GAOMON               | 1        | 1.09%   |
| Envision Peripherals | 1        | 1.09%   |
| Eizo                 | 1        | 1.09%   |
| CTV                  | 1        | 1.09%   |
| Belinea              | 1        | 1.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| MSI MAG341CQ MSI1462 3440x1440 797x333mm 34.0-inch                      | 2        | 2.08%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch             | 2        | 2.08%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 2        | 2.08%   |
| AOC 2200W AOC2200 1920x1080 476x268mm 21.5-inch                         | 2        | 2.08%   |
| Ancor Communications ASUS PB277 ACI27B5 1920x1080 597x336mm 27.0-inch   | 2        | 2.08%   |
| ViewSonic LCD Monitor VX2452 Series 3840x1080                           | 1        | 1.04%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                        | 1        | 1.04%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch               | 1        | 1.04%   |
| Sony TV SNY7001 1920x1080                                               | 1        | 1.04%   |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch       | 1        | 1.04%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch       | 1        | 1.04%   |
| Samsung Electronics T24B301 SAM098E 1920x1080 521x293mm 23.5-inch       | 1        | 1.04%   |
| Samsung Electronics SMBX2450 SAM0721 1920x1080 531x299mm 24.0-inch      | 1        | 1.04%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1        | 1.04%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 530x300mm 24.0-inch       | 1        | 1.04%   |
| Samsung Electronics S24A31x SAM7114 1920x1080 527x296mm 23.8-inch       | 1        | 1.04%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 1        | 1.04%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 1        | 1.04%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1110x620mm 50.1-inch  | 1        | 1.04%   |
| Samsung Electronics LCD Monitor SAM047D 2288x1287 410x230mm 18.5-inch   | 1        | 1.04%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch      | 1        | 1.04%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch       | 1        | 1.04%   |
| Samsung Electronics C27FG7x SAM0E41 1920x1080 598x337mm 27.0-inch       | 1        | 1.04%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch       | 1        | 1.04%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 1        | 1.04%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch                | 1        | 1.04%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch                 | 1        | 1.04%   |
| Philips PHL 245E1 PHLC20B 1920x1080 527x296mm 23.8-inch                 | 1        | 1.04%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 1        | 1.04%   |
| Philips PHL 223V5LH PHLC114 1920x1080 477x268mm 21.5-inch               | 1        | 1.04%   |
| Philips PHL 220V8 PHLC218 1920x1080 477x268mm 21.5-inch                 | 1        | 1.04%   |
| Philips 247ELH PHLC085 1920x1080 521x293mm 23.5-inch                    | 1        | 1.04%   |
| Philips 226VL PHLC081 1920x1080 480x268mm 21.6-inch                     | 1        | 1.04%   |
| Packard Bell Viseo203DX PKB0378 1600x900 432x240mm 19.5-inch            | 1        | 1.04%   |
| LG Electronics LCD Monitor 34UC89G                                      | 1        | 1.04%   |
| Lenovo L197 Wide LEN1152 1440x900 410x257mm 19.1-inch                   | 1        | 1.04%   |
| Lenovo Group Limited LCD Monitor LEN LI2323swA 4480x1080                | 1        | 1.04%   |
| KTC W2402S KTC2400 1920x1080 527x296mm 23.8-inch                        | 1        | 1.04%   |
| Jean JT198x6-7 JEN17C6 1280x1024 376x301mm 19.0-inch                    | 1        | 1.04%   |
| Iiyama PL3461WQ IVM7615 3440x1440 800x330mm 34.1-inch                   | 1        | 1.04%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 39       | 43.82%  |
| 3840x2160 (4K)     | 16       | 17.98%  |
| 2560x1440 (QHD)    | 7        | 7.87%   |
| 1280x1024 (SXGA)   | 4        | 4.49%   |
| 3440x1440          | 3        | 3.37%   |
| 2560x1080          | 3        | 3.37%   |
| Unknown            | 3        | 3.37%   |
| 3840x1080          | 2        | 2.25%   |
| 1360x768           | 2        | 2.25%   |
| 4480x1080          | 1        | 1.12%   |
| 3600x1080          | 1        | 1.12%   |
| 2288x1287          | 1        | 1.12%   |
| 2160x1200          | 1        | 1.12%   |
| 1920x1200 (WUXGA)  | 1        | 1.12%   |
| 1680x1050 (WSXGA+) | 1        | 1.12%   |
| 1600x900 (HD+)     | 1        | 1.12%   |
| 1440x900 (WXGA+)   | 1        | 1.12%   |
| 1280x960           | 1        | 1.12%   |
| 1024x768 (XGA)     | 1        | 1.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 15       | 17.05%  |
| 27      | 14       | 15.91%  |
| 24      | 12       | 13.64%  |
| 21      | 11       | 12.5%   |
| 34      | 6        | 6.82%   |
| Unknown | 5        | 5.68%   |
| 84      | 4        | 4.55%   |
| 31      | 4        | 4.55%   |
| 19      | 4        | 4.55%   |
| 32      | 2        | 2.27%   |
| 17      | 2        | 2.27%   |
| 15      | 2        | 2.27%   |
| 142     | 1        | 1.14%   |
| 72      | 1        | 1.14%   |
| 52      | 1        | 1.14%   |
| 48      | 1        | 1.14%   |
| 20      | 1        | 1.14%   |
| 18      | 1        | 1.14%   |
| 11      | 1        | 1.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 36       | 41.86%  |
| 401-500        | 14       | 16.28%  |
| 701-800        | 8        | 9.3%    |
| 601-700        | 7        | 8.14%   |
| 1501-2000      | 5        | 5.81%   |
| Unknown        | 5        | 5.81%   |
| 301-350        | 4        | 4.65%   |
| 351-400        | 3        | 3.49%   |
| 1001-1500      | 2        | 2.33%   |
| More than 2000 | 1        | 1.16%   |
| 201-300        | 1        | 1.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 57       | 72.15%  |
| 21/9    | 6        | 7.59%   |
| 5/4     | 5        | 6.33%   |
| 16/10   | 4        | 5.06%   |
| Unknown | 4        | 5.06%   |
| 4/3     | 1        | 1.27%   |
| 32/9    | 1        | 1.27%   |
| 1.00    | 1        | 1.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 35       | 39.77%  |
| 301-350        | 14       | 15.91%  |
| 351-500        | 12       | 13.64%  |
| More than 1000 | 7        | 7.95%   |
| 151-200        | 6        | 6.82%   |
| Unknown        | 5        | 5.68%   |
| 141-150        | 3        | 3.41%   |
| 251-300        | 2        | 2.27%   |
| 101-110        | 2        | 2.27%   |
| 51-60          | 1        | 1.14%   |
| 501-1000       | 1        | 1.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 43       | 52.44%  |
| 101-120 | 20       | 24.39%  |
| 121-160 | 7        | 8.54%   |
| Unknown | 5        | 6.1%    |
| 161-240 | 4        | 4.88%   |
| 1-50    | 3        | 3.66%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 50       | 69.44%  |
| 2     | 18       | 25%     |
| 3     | 3        | 4.17%   |
| 4     | 1        | 1.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 46       | 49.46%  |
| Intel                                 | 29       | 31.18%  |
| TP-Link                               | 3        | 3.23%   |
| Qualcomm Atheros                      | 3        | 3.23%   |
| D-Link System                         | 3        | 3.23%   |
| Ralink Technology                     | 2        | 2.15%   |
| Xiaomi                                | 1        | 1.08%   |
| Qualcomm Atheros Communications       | 1        | 1.08%   |
| Microsoft                             | 1        | 1.08%   |
| Google                                | 1        | 1.08%   |
| DisplayLink                           | 1        | 1.08%   |
| Aquantia                              | 1        | 1.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 1.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 39       | 33.05%  |
| Intel I211 Gigabit Network Connection                             | 10       | 8.47%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3        | 2.54%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 2.54%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 2.54%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 2        | 1.69%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2        | 1.69%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2        | 1.69%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 2        | 1.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 1.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 1.69%   |
| Intel Wi-Fi 6 AX200                                               | 2        | 1.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2        | 1.69%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 1.69%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 1.69%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.85%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1        | 0.85%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1        | 0.85%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 0.85%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1        | 0.85%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 0.85%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 0.85%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1        | 0.85%   |
| Realtek 802.11ac NIC                                              | 1        | 0.85%   |
| Ralink RT5370 Wireless Adapter                                    | 1        | 0.85%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 0.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1        | 0.85%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.85%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.85%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1        | 0.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 0.85%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.85%   |
| Microsoft Xbox Wireless Adapter for Windows                       | 1        | 0.85%   |
| Intel Wireless-AC 9260                                            | 1        | 0.85%   |
| Intel Wireless 8265 / 8275                                        | 1        | 0.85%   |
| Intel Wireless 8260                                               | 1        | 0.85%   |
| Intel Wireless 7265                                               | 1        | 0.85%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.85%   |
| Intel Ethernet Controller I225-V                                  | 1        | 0.85%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1        | 0.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 15       | 42.86%  |
| Realtek Semiconductor                 | 9        | 25.71%  |
| TP-Link                               | 3        | 8.57%   |
| Ralink Technology                     | 2        | 5.71%   |
| Qualcomm Atheros                      | 2        | 5.71%   |
| Qualcomm Atheros Communications       | 1        | 2.86%   |
| Microsoft                             | 1        | 2.86%   |
| D-Link System                         | 1        | 2.86%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 2.86%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                               | Desktops | Percent |
|-----------------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                              | 3        | 8.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                                    | 3        | 8.33%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                         | 2        | 5.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                                     | 2        | 5.56%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                            | 2        | 5.56%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                            | 2        | 5.56%   |
| Intel Wi-Fi 6 AX200                                                                                 | 2        | 5.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                                                     | 2        | 5.56%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                                 | 1        | 2.78%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                                     | 1        | 2.78%   |
| Realtek RTL8188EE Wireless Network Adapter                                                          | 1        | 2.78%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                             | 1        | 2.78%   |
| Realtek 802.11ac NIC                                                                                | 1        | 2.78%   |
| Ralink RT5370 Wireless Adapter                                                                      | 1        | 2.78%   |
| Ralink MT7601U Wireless Adapter                                                                     | 1        | 2.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                          | 1        | 2.78%   |
| Qualcomm Atheros AR9271 802.11n                                                                     | 1        | 2.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                                    | 1        | 2.78%   |
| Microsoft Xbox Wireless Adapter for Windows                                                         | 1        | 2.78%   |
| Intel Wireless-AC 9260                                                                              | 1        | 2.78%   |
| Intel Wireless 8265 / 8275                                                                          | 1        | 2.78%   |
| Intel Wireless 8260                                                                                 | 1        | 2.78%   |
| Intel Wireless 7265                                                                                 | 1        | 2.78%   |
| Intel Comet Lake PCH CNVi WiFi                                                                      | 1        | 2.78%   |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A2) [Atheros AR9170+AR9104]         | 1        | 2.78%   |
| 802.11g Adapter [Linksys WUSB54GC v3] WUSB100 v2 RangePlus Wireless Network Adapter [Ralink RT3070] | 1        | 2.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 43       | 56.58%  |
| Intel                 | 24       | 31.58%  |
| Qualcomm Atheros      | 3        | 3.95%   |
| D-Link System         | 2        | 2.63%   |
| Xiaomi                | 1        | 1.32%   |
| Google                | 1        | 1.32%   |
| DisplayLink           | 1        | 1.32%   |
| Aquantia              | 1        | 1.32%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 39       | 47.56%  |
| Intel I211 Gigabit Network Connection                             | 10       | 12.2%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 3.66%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 2.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 2.44%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 2.44%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 2.44%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.22%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.22%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 1.22%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1        | 1.22%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 1.22%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.22%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.22%   |
| Intel I210 Gigabit Network Connection                             | 1        | 1.22%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.22%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1        | 1.22%   |
| Intel Ethernet Connection I219-LM                                 | 1        | 1.22%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.22%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.22%   |
| Intel Ethernet Connection (17) I219-V                             | 1        | 1.22%   |
| Intel Ethernet Connection (12) I219-V                             | 1        | 1.22%   |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 1.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 1.22%   |
| Intel 82567LF-2 Gigabit Network Connection                        | 1        | 1.22%   |
| Intel 82562V-2 10/100 Network Connection                          | 1        | 1.22%   |
| Google Nexus/Pixel Device (tether+ debug)                         | 1        | 1.22%   |
| DisplayLink Kensington Dock (Composite Device)                    | 1        | 1.22%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 68       | 66.02%  |
| WiFi     | 35       | 33.98%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 51       | 73.91%  |
| WiFi     | 18       | 26.09%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 38       | 54.29%  |
| 2     | 26       | 37.14%  |
| 3     | 3        | 4.29%   |
| 4     | 2        | 2.86%   |
| 0     | 1        | 1.43%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 59       | 83.1%   |
| Yes  | 12       | 16.9%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 15       | 45.45%  |
| Cambridge Silicon Radio         | 7        | 21.21%  |
| IMC Networks                    | 4        | 12.12%  |
| ASUSTek Computer                | 3        | 9.09%   |
| Qualcomm Atheros Communications | 1        | 3.03%   |
| HTC (High Tech Computer)        | 1        | 3.03%   |
| Dynex                           | 1        | 3.03%   |
| Broadcom                        | 1        | 3.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 7        | 21.21%  |
| Intel Wireless-AC 3168 Bluetooth                                     | 3        | 9.09%   |
| Intel Bluetooth wireless interface                                   | 3        | 9.09%   |
| Intel AX210 Bluetooth                                                | 3        | 9.09%   |
| IMC Networks Bluetooth Radio                                         | 3        | 9.09%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 2        | 6.06%   |
| Intel AX200 Bluetooth                                                | 2        | 6.06%   |
| Qualcomm Atheros  Bluetooth Device                                   | 1        | 3.03%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 1        | 3.03%   |
| Intel AX201 Bluetooth                                                | 1        | 3.03%   |
| IMC Networks Bluetooth Device                                        | 1        | 3.03%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 3.03%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 1        | 3.03%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 1        | 3.03%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 1        | 3.03%   |
| ASUS Bluetooth Radio                                                 | 1        | 3.03%   |
| ASUS ASUS USB-BT500                                                  | 1        | 3.03%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD                                             | 51       | 36.17%  |
| Intel                                           | 30       | 21.28%  |
| Nvidia                                          | 26       | 18.44%  |
| C-Media Electronics                             | 9        | 6.38%   |
| Creative Labs                                   | 5        | 3.55%   |
| Logitech                                        | 3        | 2.13%   |
| Creative Technology                             | 2        | 1.42%   |
| TC Electronic                                   | 1        | 0.71%   |
| SteelSeries ApS                                 | 1        | 0.71%   |
| Shure                                           | 1        | 0.71%   |
| Realtek Semiconductor                           | 1        | 0.71%   |
| Razer USA                                       | 1        | 0.71%   |
| PreSonus Audio Electronics                      | 1        | 0.71%   |
| Native Instruments                              | 1        | 0.71%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.71%   |
| JMTek                                           | 1        | 0.71%   |
| Generalplus Technology                          | 1        | 0.71%   |
| Focusrite-Novation                              | 1        | 0.71%   |
| EVGA                                            | 1        | 0.71%   |
| Corsair                                         | 1        | 0.71%   |
| Blue Microphones                                | 1        | 0.71%   |
| AudioQuest                                      | 1        | 0.71%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 12       | 7.02%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 12       | 7.02%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 11       | 6.43%   |
| AMD Navi 10 HDMI Audio                                                     | 7        | 4.09%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6        | 3.51%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 5        | 2.92%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 5        | 2.92%   |
| Nvidia GP104 High Definition Audio Controller                              | 4        | 2.34%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 2.34%   |
| Intel 200 Series PCH HD Audio                                              | 4        | 2.34%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4        | 2.34%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4        | 2.34%   |
| Nvidia TU104 HD Audio Controller                                           | 3        | 1.75%   |
| Intel Comet Lake PCH-V cAVS                                                | 3        | 1.75%   |
| C-Media Electronics USB Audio Device                                       | 3        | 1.75%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 3        | 1.75%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3        | 1.75%   |
| AMD FCH Azalia Controller                                                  | 3        | 1.75%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 1.17%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 1.17%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 1.17%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 1.17%   |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 1.17%   |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 1.17%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 1.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 1.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2        | 1.17%   |
| Creative Labs CA0110 [Sound Blaster X-Fi Xtreme Audio]                     | 2        | 1.17%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 2        | 1.17%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 2        | 1.17%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 2        | 1.17%   |
| TC Electronic VoiceLive Play                                               | 1        | 0.58%   |
| SteelSeries ApS Arctis Pro Wireless                                        | 1        | 0.58%   |
| Shure MV7                                                                  | 1        | 0.58%   |
| Realtek Semiconductor Realtek Audio USB                                    | 1        | 0.58%   |
| Razer USA RZ19-0229 Gaming Microphone                                      | 1        | 0.58%   |
| PreSonus Audio Electronics AudioBox Go                                     | 1        | 0.58%   |
| Nvidia TU102 High Definition Audio Controller                              | 1        | 0.58%   |
| Nvidia High Definition Audio Controller                                    | 1        | 0.58%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 14       | 20.9%   |
| Kingston            | 13       | 19.4%   |
| G.Skill             | 12       | 17.91%  |
| Unknown             | 5        | 7.46%   |
| Crucial             | 5        | 7.46%   |
| SK hynix            | 4        | 5.97%   |
| Patriot             | 4        | 5.97%   |
| Samsung Electronics | 3        | 4.48%   |
| A-DATA Technology   | 3        | 4.48%   |
| Transcend           | 1        | 1.49%   |
| Micron Technology   | 1        | 1.49%   |
| Golden Empire       | 1        | 1.49%   |
| AMD                 | 1        | 1.49%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s        | 3        | 4.23%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s         | 2        | 2.82%   |
| Kingston RAM 99U5474-026.A00LF 4GB DIMM DDR3 1333MT/s       | 2        | 2.82%   |
| G.Skill RAM F3-10666CL9-4GBNT 4GB DIMM DDR3 1600MT/s        | 2        | 2.82%   |
| Crucial RAM BLS16G4D30AESB.M16FE 16GB DIMM DDR4 3200MT/s    | 2        | 2.82%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s       | 2        | 2.82%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s       | 2        | 2.82%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                   | 1        | 1.41%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                        | 1        | 1.41%   |
| Unknown RAM Module 2048MB DIMM SDRAM                        | 1        | 1.41%   |
| Unknown RAM Module 2048MB DIMM 1328MT/s                     | 1        | 1.41%   |
| Unknown RAM 3600 C20 Series 32GB DIMM DDR4 3666MT/s         | 1        | 1.41%   |
| Transcend RAM JM2666HLB-16G 16GB DIMM DDR4 2667MT/s         | 1        | 1.41%   |
| SK hynix RAM HMA82GU7CJR8N-VK 16GB DIMM DDR4 2667MT/s       | 1        | 1.41%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s     | 1        | 1.41%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 1        | 1.41%   |
| SK hynix RAM HMA41GU6AFR8N-TF 8GB DIMM DDR4 2465MT/s        | 1        | 1.41%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s         | 1        | 1.41%   |
| Samsung RAM M323R2GA3BB0-CQKOL 16GB DIMM DDR5 4802MT/s      | 1        | 1.41%   |
| Samsung RAM M3 78T2863RZS-CF7 1024MB DIMM DDR2 800MT/s      | 1        | 1.41%   |
| Patriot RAM PSD48G240082 8GB DIMM DDR4 2400MT/s             | 1        | 1.41%   |
| Patriot RAM PSD48G240081 8GB DIMM DDR4 2800MT/s             | 1        | 1.41%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s              | 1        | 1.41%   |
| Patriot RAM 3000 C16 Series 16GB DIMM DDR4 3200MT/s         | 1        | 1.41%   |
| Micron RAM 16ATF2G64HZ-2G6J1 16GB SODIMM DDR4 2667MT/s      | 1        | 1.41%   |
| Kingston RAM XJ69DF-MIE 8GB DIMM DDR4 2933MT/s              | 1        | 1.41%   |
| Kingston RAM MSI24D4U7S8MB-8 8GB DIMM DDR4 2400MT/s         | 1        | 1.41%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s           | 1        | 1.41%   |
| Kingston RAM KF2666C16D4/8G 8GB DIMM DDR4 2667MT/s          | 1        | 1.41%   |
| Kingston RAM 99U5595-003.A00LF 2GB DIMM DDR3 1600MT/s       | 1        | 1.41%   |
| Kingston RAM 99U5584-014.A00LF 4GB DIMM DDR3 1600MT/s       | 1        | 1.41%   |
| Kingston RAM 99U5474-010.A00LF 2GB DIMM DDR3 1333MT/s       | 1        | 1.41%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s       | 1        | 1.41%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s       | 1        | 1.41%   |
| Kingston RAM 99P5474-033.A00LF 2GB DIMM DDR3 1600MT/s       | 1        | 1.41%   |
| Golden Empire RAM CL16-18-18 D4-3000 8GB DIMM DDR4 3000MT/s | 1        | 1.41%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s      | 1        | 1.41%   |
| G.Skill RAM F4-3200C16-8GVRB 8GB DIMM DDR4 3200MT/s         | 1        | 1.41%   |
| G.Skill RAM F4-3200C16-8GSXWB 8GB DIMM DDR4 4133MT/s        | 1        | 1.41%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s          | 1        | 1.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 37       | 62.71%  |
| DDR3    | 16       | 27.12%  |
| DDR5    | 2        | 3.39%   |
| Unknown | 2        | 3.39%   |
| SDRAM   | 1        | 1.69%   |
| DDR2    | 1        | 1.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 57       | 96.61%  |
| SODIMM | 2        | 3.39%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 27       | 42.86%  |
| 4096  | 15       | 23.81%  |
| 16384 | 12       | 19.05%  |
| 32768 | 4        | 6.35%   |
| 2048  | 4        | 6.35%   |
| 1024  | 1        | 1.59%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 10       | 15.63%  |
| 1600    | 10       | 15.63%  |
| 3600    | 6        | 9.38%   |
| 2667    | 5        | 7.81%   |
| 1333    | 5        | 7.81%   |
| 3733    | 4        | 6.25%   |
| 2933    | 3        | 4.69%   |
| 2400    | 3        | 4.69%   |
| 3666    | 2        | 3.13%   |
| 3533    | 2        | 3.13%   |
| 3000    | 2        | 3.13%   |
| 2133    | 2        | 3.13%   |
| 6000    | 1        | 1.56%   |
| 4802    | 1        | 1.56%   |
| 4133    | 1        | 1.56%   |
| 3400    | 1        | 1.56%   |
| 2800    | 1        | 1.56%   |
| 2481    | 1        | 1.56%   |
| 2465    | 1        | 1.56%   |
| 1328    | 1        | 1.56%   |
| 800     | 1        | 1.56%   |
| Unknown | 1        | 1.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 1        | 25%     |
| Ricoh               | 1        | 25%     |
| Hewlett-Packard     | 1        | 25%     |
| Brother Industries  | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Samsung SCX-3400 Series       | 1        | 25%     |
| Ricoh SP 210SU                | 1        | 25%     |
| HP Officejet Pro L7400        | 1        | 25%     |
| Brother HL-2030 Laser Printer | 1        | 25%     |

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


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Canon CanoScan LIDE 25 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 6        | 35.29%  |
| Microdia                      | 2        | 11.76%  |
| Creative Technology           | 2        | 11.76%  |
| WaveRider Communications      | 1        | 5.88%   |
| Sunplus Innovation Technology | 1        | 5.88%   |
| Microsoft                     | 1        | 5.88%   |
| KYE Systems (Mouse Systems)   | 1        | 5.88%   |
| GEMBIRD                       | 1        | 5.88%   |
| Cubeternet                    | 1        | 5.88%   |
| ARC International             | 1        | 5.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Logitech Webcam C270                           | 2        | 11.76%  |
| WaveRider USB 2.0 Camera                       | 1        | 5.88%   |
| Sunplus Aukey-PC-LM1E Camera                   | 1        | 5.88%   |
| Microsoft LifeCam Cinema                       | 1        | 5.88%   |
| Microdia Webcam Vitade AF                      | 1        | 5.88%   |
| Microdia USB 2.0 Camera                        | 1        | 5.88%   |
| Logitech Webcam C930e                          | 1        | 5.88%   |
| Logitech Webcam C310                           | 1        | 5.88%   |
| Logitech HD Webcam C910                        | 1        | 5.88%   |
| Logitech BRIO Ultra HD Webcam                  | 1        | 5.88%   |
| KYE Systems (Mouse Systems) Genius FaceCam 320 | 1        | 5.88%   |
| GEMBIRD USB2.0 PC CAMERA                       | 1        | 5.88%   |
| Cubeternet GL-UPC822 UVC WebCam                | 1        | 5.88%   |
| Creative Live! Cam Sync HD [VF0770]            | 1        | 5.88%   |
| Creative Live! Cam Chat HD [VF0700]            | 1        | 5.88%   |
| ARC International Camera                       | 1        | 5.88%   |

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
| 0     | 63       | 90%     |
| 1     | 6        | 8.57%   |
| 3     | 1        | 1.43%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Unassigned class         | 2        | 28.57%  |
| Communication controller | 2        | 28.57%  |
| Net/wireless             | 1        | 14.29%  |
| Net/ethernet             | 1        | 14.29%  |
| Graphics card            | 1        | 14.29%  |

