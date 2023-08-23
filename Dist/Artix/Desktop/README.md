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

Total: 98

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
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
| Artix Rolling  | 42       | 61.76%  |
| Artix          | 17       | 25%     |
| Artix 20220123 | 2        | 2.94%   |
| Artix 20210726 | 2        | 2.94%   |
| Artix 20230501 | 1        | 1.47%   |
| Artix 20230320 | 1        | 1.47%   |
| Artix 20230306 | 1        | 1.47%   |
| Artix 20230215 | 1        | 1.47%   |
| Artix 20220713 | 1        | 1.47%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| Artix | 66       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.10.8-artix1-1        | 3        | 3.8%    |
| 6.2.6-artix1-1         | 2        | 2.53%   |
| 6.2.13-artix1-1        | 2        | 2.53%   |
| 6.1.8-artix1-1         | 2        | 2.53%   |
| 5.9.14-artix1-1        | 2        | 2.53%   |
| 5.8.8-artix1-1         | 2        | 2.53%   |
| 5.8.12-artix1-1        | 2        | 2.53%   |
| 5.7.6-artix1-1         | 2        | 2.53%   |
| 5.7.12-artix1-1        | 2        | 2.53%   |
| 5.18.16-artix1-1       | 2        | 2.53%   |
| 5.15.12-artix1-1       | 2        | 2.53%   |
| 5.12.14-artix1-1       | 2        | 2.53%   |
| 5.12.12-artix1-1       | 2        | 2.53%   |
| 5.11.16-artix1-1       | 2        | 2.53%   |
| 5.10.4-artix2-1        | 2        | 2.53%   |
| 6.4.4-artix1-1         | 1        | 1.27%   |
| 6.4.3-artix1-2         | 1        | 1.27%   |
| 6.3.7-zen1-1-zen       | 1        | 1.27%   |
| 6.3.6-artix1-1         | 1        | 1.27%   |
| 6.3.2-zen1-1-zen       | 1        | 1.27%   |
| 6.2.11-artix1-1        | 1        | 1.27%   |
| 6.1.4-artix1-1         | 1        | 1.27%   |
| 6.1.32-1-lts           | 1        | 1.27%   |
| 6.1.12-artix1-1        | 1        | 1.27%   |
| 6.1.1-x64v1-xanmod1-1  | 1        | 1.27%   |
| 6.0.7-artix1-1         | 1        | 1.27%   |
| 6.0.1-arch1-1          | 1        | 1.27%   |
| 5.9.8-zen1-1-zen       | 1        | 1.27%   |
| 5.9.14-zen1-1-zen      | 1        | 1.27%   |
| 5.9.12-artix1-1        | 1        | 1.27%   |
| 5.9.10-artix1-1        | 1        | 1.27%   |
| 5.8.5-xanmod1-1-xanmod | 1        | 1.27%   |
| 5.8.14-artix1-1        | 1        | 1.27%   |
| 5.7.2-artix1-1         | 1        | 1.27%   |
| 5.4.197-1-lts54        | 1        | 1.27%   |
| 5.18.9-zen1-1-zen      | 1        | 1.27%   |
| 5.17.8-258-tkg-pds     | 1        | 1.27%   |
| 5.17.4-artix1-1        | 1        | 1.27%   |
| 5.17.12-lqx1-1-lqx     | 1        | 1.27%   |
| 5.16.3-artix1-1        | 1        | 1.27%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.9.14  | 3        | 3.8%    |
| 5.10.8  | 3        | 3.8%    |
| 6.2.6   | 2        | 2.53%   |
| 6.2.13  | 2        | 2.53%   |
| 6.1.8   | 2        | 2.53%   |
| 5.8.8   | 2        | 2.53%   |
| 5.8.12  | 2        | 2.53%   |
| 5.7.6   | 2        | 2.53%   |
| 5.7.12  | 2        | 2.53%   |
| 5.18.16 | 2        | 2.53%   |
| 5.15.12 | 2        | 2.53%   |
| 5.12.14 | 2        | 2.53%   |
| 5.12.12 | 2        | 2.53%   |
| 5.11.16 | 2        | 2.53%   |
| 5.10.4  | 2        | 2.53%   |
| 5.10.15 | 2        | 2.53%   |
| 6.4.4   | 1        | 1.27%   |
| 6.4.3   | 1        | 1.27%   |
| 6.3.7   | 1        | 1.27%   |
| 6.3.6   | 1        | 1.27%   |
| 6.3.2   | 1        | 1.27%   |
| 6.2.11  | 1        | 1.27%   |
| 6.1.4   | 1        | 1.27%   |
| 6.1.32  | 1        | 1.27%   |
| 6.1.12  | 1        | 1.27%   |
| 6.1.1   | 1        | 1.27%   |
| 6.0.7   | 1        | 1.27%   |
| 6.0.1   | 1        | 1.27%   |
| 5.9.8   | 1        | 1.27%   |
| 5.9.12  | 1        | 1.27%   |
| 5.9.10  | 1        | 1.27%   |
| 5.8.5   | 1        | 1.27%   |
| 5.8.14  | 1        | 1.27%   |
| 5.7.2   | 1        | 1.27%   |
| 5.4.197 | 1        | 1.27%   |
| 5.18.9  | 1        | 1.27%   |
| 5.17.8  | 1        | 1.27%   |
| 5.17.4  | 1        | 1.27%   |
| 5.17.12 | 1        | 1.27%   |
| 5.16.3  | 1        | 1.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 10       | 13.33%  |
| 5.15    | 7        | 9.33%   |
| 5.9     | 6        | 8%      |
| 5.8     | 6        | 8%      |
| 5.12    | 6        | 8%      |
| 6.2     | 5        | 6.67%   |
| 6.1     | 5        | 6.67%   |
| 5.7     | 4        | 5.33%   |
| 5.16    | 4        | 5.33%   |
| 5.11    | 4        | 5.33%   |
| 6.3     | 3        | 4%      |
| 5.18    | 3        | 4%      |
| 5.17    | 3        | 4%      |
| 6.0     | 2        | 2.67%   |
| 5.14    | 2        | 2.67%   |
| 5.13    | 2        | 2.67%   |
| 6.4     | 1        | 1.33%   |
| 5.4     | 1        | 1.33%   |
| 4.19    | 1        | 1.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 66       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| KDE5       | 21       | 29.58%  |
| GNOME      | 11       | 15.49%  |
| XFCE       | 8        | 11.27%  |
| X-Cinnamon | 6        | 8.45%   |
| MATE       | 6        | 8.45%   |
| Unknown    | 6        | 8.45%   |
| Cinnamon   | 3        | 4.23%   |
| bspwm      | 3        | 4.23%   |
| i3         | 2        | 2.82%   |
| sway       | 1        | 1.41%   |
| openbox    | 1        | 1.41%   |
| LXQt       | 1        | 1.41%   |
| LXDE       | 1        | 1.41%   |
| DWM        | 1        | 1.41%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 50       | 73.53%  |
| Tty     | 10       | 14.71%  |
| Wayland | 5        | 7.35%   |
| Unknown | 3        | 4.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 27       | 38.57%  |
| SDDM    | 21       | 30%     |
| LightDM | 17       | 24.29%  |
| GDM     | 2        | 2.86%   |
| XDM     | 1        | 1.43%   |
| SLiM    | 1        | 1.43%   |
| LXDM    | 1        | 1.43%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 25       | 37.31%  |
| ru_RU   | 8        | 11.94%  |
| fr_FR   | 5        | 7.46%   |
| C       | 5        | 7.46%   |
| Unknown | 5        | 7.46%   |
| de_DE   | 3        | 4.48%   |
| pt_PT   | 2        | 2.99%   |
| pt_BR   | 2        | 2.99%   |
| tr_TR   | 1        | 1.49%   |
| lt_LT   | 1        | 1.49%   |
| ja_JP   | 1        | 1.49%   |
| it_IT   | 1        | 1.49%   |
| es_MX   | 1        | 1.49%   |
| es_AR   | 1        | 1.49%   |
| en_IE   | 1        | 1.49%   |
| en_GB   | 1        | 1.49%   |
| en_AU   | 1        | 1.49%   |
| el_GR   | 1        | 1.49%   |
| de_AT   | 1        | 1.49%   |
| bg_BG   | 1        | 1.49%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 45       | 67.16%  |
| BIOS | 22       | 32.84%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 43       | 65.15%  |
| Btrfs | 15       | 22.73%  |
| Xfs   | 4        | 6.06%   |
| F2fs  | 2        | 3.03%   |
| Tmpfs | 1        | 1.52%   |
| Jfs   | 1        | 1.52%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 50       | 73.53%  |
| Unknown | 14       | 20.59%  |
| MBR     | 4        | 5.88%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 48       | 70.59%  |
| Yes       | 20       | 29.41%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 48       | 71.64%  |
| Yes       | 19       | 28.36%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 20       | 30.3%   |
| Gigabyte Technology | 16       | 24.24%  |
| MSI                 | 13       | 19.7%   |
| ASRock              | 7        | 10.61%  |
| Dell                | 3        | 4.55%   |
| Intel               | 2        | 3.03%   |
| Hewlett-Packard     | 2        | 3.03%   |
| MACHINIST           | 1        | 1.52%   |
| Biostar             | 1        | 1.52%   |
| Alienware           | 1        | 1.52%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| MSI MS-7A38                    | 3        | 4.55%   |
| MSI MS-7C02                    | 2        | 3.03%   |
| Gigabyte 970A-DS3P             | 2        | 3.03%   |
| MSI MS-7E07                    | 1        | 1.52%   |
| MSI MS-7C89                    | 1        | 1.52%   |
| MSI MS-7C56                    | 1        | 1.52%   |
| MSI MS-7C37                    | 1        | 1.52%   |
| MSI MS-7B79                    | 1        | 1.52%   |
| MSI MS-7B09                    | 1        | 1.52%   |
| MSI MS-7A69                    | 1        | 1.52%   |
| MSI MS-7A15                    | 1        | 1.52%   |
| MACHINIST X99-MR9D PLUS V1.0   | 1        | 1.52%   |
| Intel X99                      | 1        | 1.52%   |
| Intel DX58SO2 AAG10925-205     | 1        | 1.52%   |
| HP Compaq 8200 Elite SFF PC    | 1        | 1.52%   |
| HP 280 G1 MT                   | 1        | 1.52%   |
| Gigabyte Z77X-UD3H             | 1        | 1.52%   |
| Gigabyte X570 AORUS ULTRA      | 1        | 1.52%   |
| Gigabyte X570 AORUS ELITE WIFI | 1        | 1.52%   |
| Gigabyte X570 AORUS ELITE      | 1        | 1.52%   |
| Gigabyte X399 AORUS XTREME     | 1        | 1.52%   |
| Gigabyte P55-USB3              | 1        | 1.52%   |
| Gigabyte HA65M-D2H-B3          | 1        | 1.52%   |
| Gigabyte H61MA-D3V             | 1        | 1.52%   |
| Gigabyte H410M H               | 1        | 1.52%   |
| Gigabyte B550M AORUS PRO       | 1        | 1.52%   |
| Gigabyte B450 AORUS PRO WIFI   | 1        | 1.52%   |
| Gigabyte AB350M-DS3H V2        | 1        | 1.52%   |
| Gigabyte 990FXA-UD5            | 1        | 1.52%   |
| Gigabyte 990FXA-UD3 R5         | 1        | 1.52%   |
| Dell OptiPlex 7060             | 1        | 1.52%   |
| Dell OptiPlex 5080             | 1        | 1.52%   |
| Dell Inspiron 530              | 1        | 1.52%   |
| Biostar G31D-M7                | 1        | 1.52%   |
| ASUS TUF Gaming X570-PLUS      | 1        | 1.52%   |
| ASUS TUF Gaming B550M-PLUS     | 1        | 1.52%   |
| ASUS TUF B450-PLUS GAMING      | 1        | 1.52%   |
| ASUS SABERTOOTH 990FX R2.0     | 1        | 1.52%   |
| ASUS ROG STRIX Z370-G GAMING   | 1        | 1.52%   |
| ASUS ROG STRIX X570-F GAMING   | 1        | 1.52%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS ROG              | 5        | 7.58%   |
| MSI MS-7A38           | 3        | 4.55%   |
| Gigabyte X570         | 3        | 4.55%   |
| ASUS TUF              | 3        | 4.55%   |
| ASUS PRIME            | 3        | 4.55%   |
| MSI MS-7C02           | 2        | 3.03%   |
| Gigabyte 970A-DS3P    | 2        | 3.03%   |
| Dell OptiPlex         | 2        | 3.03%   |
| MSI MS-7E07           | 1        | 1.52%   |
| MSI MS-7C89           | 1        | 1.52%   |
| MSI MS-7C56           | 1        | 1.52%   |
| MSI MS-7C37           | 1        | 1.52%   |
| MSI MS-7B79           | 1        | 1.52%   |
| MSI MS-7B09           | 1        | 1.52%   |
| MSI MS-7A69           | 1        | 1.52%   |
| MSI MS-7A15           | 1        | 1.52%   |
| MACHINIST X99-MR9D    | 1        | 1.52%   |
| Intel X99             | 1        | 1.52%   |
| Intel DX58SO2         | 1        | 1.52%   |
| HP Compaq             | 1        | 1.52%   |
| HP 280                | 1        | 1.52%   |
| Gigabyte Z77X-UD3H    | 1        | 1.52%   |
| Gigabyte X399         | 1        | 1.52%   |
| Gigabyte P55-USB3     | 1        | 1.52%   |
| Gigabyte HA65M-D2H-B3 | 1        | 1.52%   |
| Gigabyte H61MA-D3V    | 1        | 1.52%   |
| Gigabyte H410M        | 1        | 1.52%   |
| Gigabyte B550M        | 1        | 1.52%   |
| Gigabyte B450         | 1        | 1.52%   |
| Gigabyte AB350M-DS3H  | 1        | 1.52%   |
| Gigabyte 990FXA-UD5   | 1        | 1.52%   |
| Gigabyte 990FXA-UD3   | 1        | 1.52%   |
| Dell Inspiron         | 1        | 1.52%   |
| Biostar G31D-M7       | 1        | 1.52%   |
| ASUS SABERTOOTH       | 1        | 1.52%   |
| ASUS Pro              | 1        | 1.52%   |
| ASUS P8H61-M          | 1        | 1.52%   |
| ASUS P8B75-M          | 1        | 1.52%   |
| ASUS M5A97            | 1        | 1.52%   |
| ASUS K30BF            | 1        | 1.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 11       | 16.67%  |
| 2020 | 10       | 15.15%  |
| 2017 | 9        | 13.64%  |
| 2018 | 7        | 10.61%  |
| 2012 | 7        | 10.61%  |
| 2013 | 5        | 7.58%   |
| 2022 | 4        | 6.06%   |
| 2015 | 4        | 6.06%   |
| 2016 | 2        | 3.03%   |
| 2011 | 2        | 3.03%   |
| 2010 | 2        | 3.03%   |
| 2008 | 2        | 3.03%   |
| 2021 | 1        | 1.52%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 66       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 66       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 66       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 27       | 40.3%   |
| 8.01-16.0   | 17       | 25.37%  |
| 32.01-64.0  | 10       | 14.93%  |
| 64.01-256.0 | 7        | 10.45%  |
| 3.01-4.0    | 4        | 5.97%   |
| 4.01-8.0    | 1        | 1.49%   |
| 1.01-2.0    | 1        | 1.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 18       | 24.66%  |
| 3.01-4.0   | 16       | 21.92%  |
| 2.01-3.0   | 15       | 20.55%  |
| 1.01-2.0   | 14       | 19.18%  |
| 8.01-16.0  | 3        | 4.11%   |
| 0.51-1.0   | 3        | 4.11%   |
| 16.01-24.0 | 2        | 2.74%   |
| 0.01-0.5   | 2        | 2.74%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 27       | 39.13%  |
| 3      | 17       | 24.64%  |
| 1      | 12       | 17.39%  |
| 4      | 6        | 8.7%    |
| 6      | 4        | 5.8%    |
| 8      | 2        | 2.9%    |
| 7      | 1        | 1.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 52       | 78.79%  |
| Yes       | 14       | 21.21%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 65       | 98.48%  |
| No        | 1        | 1.52%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 33       | 50%     |
| No        | 33       | 50%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 36       | 54.55%  |
| Yes       | 30       | 45.45%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 11       | 16.42%  |
| Germany     | 10       | 14.93%  |
| Russia      | 8        | 11.94%  |
| France      | 7        | 10.45%  |
| Greece      | 3        | 4.48%   |
| Brazil      | 3        | 4.48%   |
| Switzerland | 2        | 2.99%   |
| Poland      | 2        | 2.99%   |
| Finland     | 2        | 2.99%   |
| Canada      | 2        | 2.99%   |
| Bulgaria    | 2        | 2.99%   |
| Ukraine     | 1        | 1.49%   |
| UK          | 1        | 1.49%   |
| Turkey      | 1        | 1.49%   |
| Slovenia    | 1        | 1.49%   |
| Mexico      | 1        | 1.49%   |
| Lithuania   | 1        | 1.49%   |
| Japan       | 1        | 1.49%   |
| Italy       | 1        | 1.49%   |
| Iran        | 1        | 1.49%   |
| India       | 1        | 1.49%   |
| Hong Kong   | 1        | 1.49%   |
| Guatemala   | 1        | 1.49%   |
| Austria     | 1        | 1.49%   |
| Australia   | 1        | 1.49%   |
| Argentina   | 1        | 1.49%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Paris                  | 3        | 4.29%   |
| Moscow                 | 2        | 2.86%   |
| Helsinki               | 2        | 2.86%   |
| Frankfurt am Main      | 2        | 2.86%   |
| Bern                   | 2        | 2.86%   |
| Athens                 | 2        | 2.86%   |
| Wettringen             | 1        | 1.43%   |
| Vladivostok            | 1        | 1.43%   |
| Vilnius                | 1        | 1.43%   |
| Vienna                 | 1        | 1.43%   |
| Vancouver              | 1        | 1.43%   |
| Upper Norwood          | 1        | 1.43%   |
| Ufa                    | 1        | 1.43%   |
| Toronto                | 1        | 1.43%   |
| Thessaloniki           | 1        | 1.43%   |
| Tehran                 | 1        | 1.43%   |
| Sydney                 | 1        | 1.43%   |
| Surat                  | 1        | 1.43%   |
| Stein                  | 1        | 1.43%   |
| Stavropol              | 1        | 1.43%   |
| Statesboro             | 1        | 1.43%   |
| Sofia                  | 1        | 1.43%   |
| Snohomish              | 1        | 1.43%   |
| Shavertown             | 1        | 1.43%   |
| Saratov                | 1        | 1.43%   |
| Sao Paulo              | 1        | 1.43%   |
| San Miguel de Tucumán | 1        | 1.43%   |
| Riverview              | 1        | 1.43%   |
| Rexburg                | 1        | 1.43%   |
| Plovdiv                | 1        | 1.43%   |
| Munich                 | 1        | 1.43%   |
| Maua                   | 1        | 1.43%   |
| Maebashi               | 1        | 1.43%   |
| Maceió                | 1        | 1.43%   |
| Lublin                 | 1        | 1.43%   |
| Ljubljana              | 1        | 1.43%   |
| Lafayette              | 1        | 1.43%   |
| Kłodzko               | 1        | 1.43%   |
| Koga                   | 1        | 1.43%   |
| Kazan’               | 1        | 1.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 31       | 56     | 20.67%  |
| Seagate                     | 22       | 30     | 14.67%  |
| Samsung Electronics         | 20       | 31     | 13.33%  |
| Kingston                    | 13       | 14     | 8.67%   |
| Crucial                     | 10       | 16     | 6.67%   |
| Toshiba                     | 9        | 10     | 6%      |
| SanDisk                     | 6        | 9      | 4%      |
| Intel                       | 4        | 7      | 2.67%   |
| Phison Electronics          | 3        | 6      | 2%      |
| Hitachi                     | 3        | 3      | 2%      |
| A-DATA Technology           | 3        | 3      | 2%      |
| Maxtor                      | 2        | 2      | 1.33%   |
| JMicron Technology          | 2        | 2      | 1.33%   |
| Corsair                     | 2        | 2      | 1.33%   |
| China                       | 2        | 3      | 1.33%   |
| USB3.0                      | 1        | 1      | 0.67%   |
| TS512GMT                    | 1        | 5      | 0.67%   |
| Transcend                   | 1        | 1      | 0.67%   |
| SPCC Sol                    | 1        | 1      | 0.67%   |
| SPCC                        | 1        | 1      | 0.67%   |
| SK hynix                    | 1        | 1      | 0.67%   |
| Silicon Motion              | 1        | 1      | 0.67%   |
| PNY                         | 1        | 1      | 0.67%   |
| Plextor                     | 1        | 1      | 0.67%   |
| Phison                      | 1        | 1      | 0.67%   |
| Netac                       | 1        | 1      | 0.67%   |
| MAXIO Technology (Hangzhou) | 1        | 2      | 0.67%   |
| Linux                       | 1        | 1      | 0.67%   |
| HGST                        | 1        | 2      | 0.67%   |
| Hewlett-Packard             | 1        | 1      | 0.67%   |
| GOODRAM                     | 1        | 1      | 0.67%   |
| AMD                         | 1        | 1      | 0.67%   |
| Unknown                     | 1        | 2      | 0.67%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB                              | 5        | 2.87%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 4        | 2.3%    |
| WDC WD10EZEX-08WN4A0 1TB                            | 3        | 1.72%   |
| Seagate ST3500418AS 500GB                           | 3        | 1.72%   |
| Seagate ST1000DM010-2EP102 1TB                      | 3        | 1.72%   |
| Samsung SSD 860 EVO 250GB                           | 3        | 1.72%   |
| Crucial CT240BX500SSD1 240GB                        | 3        | 1.72%   |
| WDC WD80EZAZ-11TDBA0 8TB                            | 2        | 1.15%   |
| WDC WD40EZRZ-00WN9B0 4TB                            | 2        | 1.15%   |
| WDC WD10EZEX-22MFCA0 1TB                            | 2        | 1.15%   |
| WDC WD100EMAZ-00WJTA0 10TB                          | 2        | 1.15%   |
| Seagate ST500DM002-1BD142 500GB                     | 2        | 1.15%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2        | 1.15%   |
| Sandisk WD Blue SN550 NVMe SSD 250GB                | 2        | 1.15%   |
| Samsung SSD 970 EVO 1TB                             | 2        | 1.15%   |
| Samsung SSD 840 EVO 250GB                           | 2        | 1.15%   |
| Phison PS5013 E13 NVMe Controller 256GB             | 2        | 1.15%   |
| Kingston SA400S37480G 480GB SSD                     | 2        | 1.15%   |
| Kingston SA400S37120G 120GB SSD                     | 2        | 1.15%   |
| Crucial CT250MX500SSD1 250GB                        | 2        | 1.15%   |
| Crucial CT1000MX500SSD1 1TB                         | 2        | 1.15%   |
| A-DATA SU650 240GB SSD                              | 2        | 1.15%   |
| WDC WDS500G2B0C-00PXH0 500GB                        | 1        | 0.57%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1        | 0.57%   |
| WDC WDS256G1X0C-00ENX0 256GB                        | 1        | 0.57%   |
| WDC WDS100T2B0C-00PXH0 1TB                          | 1        | 0.57%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 1        | 0.57%   |
| WDC WDBNCE5000PNC 500GB SSD                         | 1        | 0.57%   |
| WDC WD80EFBX-68AZZN0 8TB                            | 1        | 0.57%   |
| WDC WD6001FZWX-00A2VA0 6TB                          | 1        | 0.57%   |
| WDC WD5003ABYX-18WERA0 500GB                        | 1        | 0.57%   |
| WDC WD5000LPVX-00V0TT0 500GB                        | 1        | 0.57%   |
| WDC WD5000LPLX-75ZNTT0 500GB                        | 1        | 0.57%   |
| WDC WD5000AVCS-632DY1 500GB                         | 1        | 0.57%   |
| WDC WD5000AAKX-60U6AA0 500GB                        | 1        | 0.57%   |
| WDC WD4003FZEX-00Z4SA0 4TB                          | 1        | 0.57%   |
| WDC WD4003FFBX-68MU3N0 4TB                          | 1        | 0.57%   |
| WDC WD4002FFWX-68TZ4N0 4TB                          | 1        | 0.57%   |
| WDC WD3200AAKX-00ERMA0 320GB                        | 1        | 0.57%   |
| WDC WD30EZRX-00DC0B0 3TB                            | 1        | 0.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Desktops | Drives | Percent |
|--------------------|----------|--------|---------|
| WDC                | 28       | 48     | 41.18%  |
| Seagate            | 22       | 30     | 32.35%  |
| Toshiba            | 9        | 10     | 13.24%  |
| Hitachi            | 3        | 3      | 4.41%   |
| Maxtor             | 2        | 2      | 2.94%   |
| JMicron Technology | 2        | 2      | 2.94%   |
| USB3.0             | 1        | 1      | 1.47%   |
| HGST               | 1        | 2      | 1.47%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 11       | 15     | 21.57%  |
| Kingston            | 11       | 12     | 21.57%  |
| Crucial             | 10       | 16     | 19.61%  |
| WDC                 | 3        | 5      | 5.88%   |
| A-DATA Technology   | 3        | 3      | 5.88%   |
| SanDisk             | 2        | 2      | 3.92%   |
| Intel               | 2        | 3      | 3.92%   |
| China               | 2        | 3      | 3.92%   |
| SPCC Sol            | 1        | 1      | 1.96%   |
| SPCC                | 1        | 1      | 1.96%   |
| Plextor             | 1        | 1      | 1.96%   |
| Netac               | 1        | 1      | 1.96%   |
| Linux               | 1        | 1      | 1.96%   |
| GOODRAM             | 1        | 1      | 1.96%   |
| AMD                 | 1        | 1      | 1.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 52       | 98     | 40.31%  |
| SSD     | 45       | 66     | 34.88%  |
| NVMe    | 30       | 48     | 23.26%  |
| Unknown | 2        | 7      | 1.55%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 62       | 158    | 62.63%  |
| NVMe | 30       | 48     | 30.3%   |
| SAS  | 7        | 13     | 7.07%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 48       | 76     | 45.28%  |
| 0.51-1.0   | 32       | 52     | 30.19%  |
| 1.01-2.0   | 11       | 12     | 10.38%  |
| 4.01-10.0  | 6        | 13     | 5.66%   |
| 3.01-4.0   | 5        | 7      | 4.72%   |
| 2.01-3.0   | 4        | 4      | 3.77%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 14       | 20.59%  |
| More than 3000 | 13       | 19.12%  |
| 2001-3000      | 12       | 17.65%  |
| 101-250        | 10       | 14.71%  |
| 501-1000       | 9        | 13.24%  |
| 251-500        | 7        | 10.29%  |
| 51-100         | 2        | 2.94%   |
| Unknown        | 1        | 1.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 13       | 18.84%  |
| 251-500        | 11       | 15.94%  |
| 1001-2000      | 11       | 15.94%  |
| 1-20           | 9        | 13.04%  |
| More than 3000 | 8        | 11.59%  |
| 101-250        | 8        | 11.59%  |
| 21-50          | 3        | 4.35%   |
| 51-100         | 3        | 4.35%   |
| 2001-3000      | 2        | 2.9%    |
| Unknown        | 1        | 1.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD5000AVCS-632DY1 500GB       | 1        | 1      | 6.67%   |
| WDC WD3200AAKX-00ERMA0 320GB      | 1        | 1      | 6.67%   |
| WDC WD30EZRX-00DC0B0 3TB          | 1        | 1      | 6.67%   |
| Toshiba MK7575GSX 752GB           | 1        | 1      | 6.67%   |
| Toshiba DT01ACA100 1TB            | 1        | 1      | 6.67%   |
| Seagate ST8000DM004-2CX188 8TB    | 1        | 1      | 6.67%   |
| Seagate ST2000DX002-2DV164 2TB    | 1        | 1      | 6.67%   |
| Seagate ST2000DM006-2DM164 2TB    | 1        | 1      | 6.67%   |
| Maxtor 6Y080M0 80GB               | 1        | 1      | 6.67%   |
| Kingston SUV400S37240G 240GB SSD  | 1        | 1      | 6.67%   |
| Kingston SA400S37120G 120GB SSD   | 1        | 1      | 6.67%   |
| Intel SSDSC2BW480A4 480GB         | 1        | 2      | 6.67%   |
| Intel SSDPEKKW128G7 128GB         | 1        | 1      | 6.67%   |
| Hewlett-Packard SSD EX900 250GB   | 1        | 1      | 6.67%   |
| A-DATA Technology SU650 240GB SSD | 1        | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| WDC               | 3        | 3      | 20%     |
| Seagate           | 3        | 3      | 20%     |
| Toshiba           | 2        | 2      | 13.33%  |
| Kingston          | 2        | 2      | 13.33%  |
| Intel             | 2        | 3      | 13.33%  |
| Maxtor            | 1        | 1      | 6.67%   |
| Hewlett-Packard   | 1        | 1      | 6.67%   |
| A-DATA Technology | 1        | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 3        | 3      | 33.33%  |
| Seagate | 3        | 3      | 33.33%  |
| Toshiba | 2        | 2      | 22.22%  |
| Maxtor  | 1        | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 8        | 9      | 57.14%  |
| SSD  | 4        | 5      | 28.57%  |
| NVMe | 2        | 2      | 14.29%  |

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
| Works    | 41       | 117    | 49.4%   |
| Detected | 28       | 85     | 33.73%  |
| Malfunc  | 13       | 16     | 15.66%  |
| Fixed    | 1        | 1      | 1.2%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| AMD                         | 37       | 34.26%  |
| Intel                       | 30       | 27.78%  |
| Samsung Electronics         | 12       | 11.11%  |
| SanDisk                     | 6        | 5.56%   |
| Phison Electronics          | 6        | 5.56%   |
| Marvell Technology Group    | 5        | 4.63%   |
| Silicon Motion              | 3        | 2.78%   |
| ASMedia Technology          | 3        | 2.78%   |
| Kingston Technology Company | 2        | 1.85%   |
| SK hynix                    | 1        | 0.93%   |
| MAXIO Technology (Hangzhou) | 1        | 0.93%   |
| JMicron Technology          | 1        | 0.93%   |
| Broadcom / LSI              | 1        | 0.93%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 26       | 19.55%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 10       | 7.52%   |
| AMD 400 Series Chipset SATA Controller                                         | 7        | 5.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 6        | 4.51%   |
| AMD 300 Series Chipset SATA Controller                                         | 6        | 4.51%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4        | 3.01%   |
| AMD 500 Series Chipset SATA Controller                                         | 4        | 3.01%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3        | 2.26%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 3        | 2.26%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3        | 2.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3        | 2.26%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3        | 2.26%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3        | 2.26%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 2        | 1.5%    |
| Phison PS5013 E13 NVMe Controller                                              | 2        | 1.5%    |
| Phison E16 PCIe4 NVMe Controller                                               | 2        | 1.5%    |
| Phison E12 NVMe Controller                                                     | 2        | 1.5%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2        | 1.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2        | 1.5%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2        | 1.5%    |
| AMD X399 Series Chipset SATA Controller                                        | 2        | 1.5%    |
| SK hynix PC601 NVMe Solid State Drive                                          | 1        | 0.75%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1        | 0.75%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1        | 0.75%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1        | 0.75%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1        | 0.75%   |
| SanDisk WD Black NVMe SSD                                                      | 1        | 0.75%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 0.75%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 0.75%   |
| Phison E18 PCIe4 NVMe Controller                                               | 1        | 0.75%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 1        | 0.75%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                          | 1        | 0.75%   |
| Marvell Group 88SE912x IDE Controller                                          | 1        | 0.75%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                           | 1        | 0.75%   |
| Kingston Company NVMe Controller                                               | 1        | 0.75%   |
| Kingston Company A2000 NVMe SSD                                                | 1        | 0.75%   |
| JMicron JMB363 SATA/IDE Controller                                             | 1        | 0.75%   |
| Intel SSD 660P Series                                                          | 1        | 0.75%   |
| Intel SSD 600P Series                                                          | 1        | 0.75%   |
| Intel SATA Controller [RAID mode]                                              | 1        | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 63       | 61.17%  |
| NVMe | 30       | 29.13%  |
| IDE  | 8        | 7.77%   |
| RAID | 1        | 0.97%   |
| SAS  | 1        | 0.97%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 37       | 56.06%  |
| Intel  | 29       | 43.94%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD FX-8350 Eight-Core Processor                | 4        | 6.06%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 3        | 4.55%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 3        | 4.55%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 3        | 4.55%   |
| AMD Ryzen 5 2600X Six-Core Processor            | 3        | 4.55%   |
| Intel Core i7-9700K CPU @ 3.60GHz               | 2        | 3.03%   |
| Intel Core i5-2500 CPU @ 3.30GHz                | 2        | 3.03%   |
| Intel Core i5-10400F CPU @ 2.90GHz              | 2        | 3.03%   |
| AMD Ryzen 7 5700G with Radeon Graphics          | 2        | 3.03%   |
| AMD Ryzen 5 5600X 6-Core Processor              | 2        | 3.03%   |
| AMD Ryzen 5 3600 6-Core Processor               | 2        | 3.03%   |
| AMD Ryzen 5 1600 Six-Core Processor             | 2        | 3.03%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz             | 1        | 1.52%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz             | 1        | 1.52%   |
| Intel Pentium CPU G4560 @ 3.50GHz               | 1        | 1.52%   |
| Intel Core i7-9700F CPU @ 3.00GHz               | 1        | 1.52%   |
| Intel Core i7-4790K CPU @ 4.00GHz               | 1        | 1.52%   |
| Intel Core i7 CPU 970 @ 3.20GHz                 | 1        | 1.52%   |
| Intel Core i5-9600K CPU @ 3.70GHz               | 1        | 1.52%   |
| Intel Core i5-8500 CPU @ 3.00GHz                | 1        | 1.52%   |
| Intel Core i5-7600K CPU @ 3.80GHz               | 1        | 1.52%   |
| Intel Core i5-6600K CPU @ 3.50GHz               | 1        | 1.52%   |
| Intel Core i5-6400 CPU @ 2.70GHz                | 1        | 1.52%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 1        | 1.52%   |
| Intel Core i5-3330 CPU @ 3.00GHz                | 1        | 1.52%   |
| Intel Core i5-2310 CPU @ 2.90GHz                | 1        | 1.52%   |
| Intel Core i5-10500T CPU @ 2.30GHz              | 1        | 1.52%   |
| Intel Core i5 CPU 660 @ 3.33GHz                 | 1        | 1.52%   |
| Intel Core i3-2120 CPU @ 3.30GHz                | 1        | 1.52%   |
| Intel Core i3-10100 CPU @ 3.60GHz               | 1        | 1.52%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz            | 1        | 1.52%   |
| Intel Core 2 Duo CPU E4600 @ 2.40GHz            | 1        | 1.52%   |
| Intel Celeron CPU G1840 @ 2.80GHz               | 1        | 1.52%   |
| Intel 12th Gen Core i9-12900K                   | 1        | 1.52%   |
| Intel 12th Gen Core i5-12600K                   | 1        | 1.52%   |
| AMD Ryzen Threadripper 2990WX 32-Core Processor | 1        | 1.52%   |
| AMD Ryzen Threadripper 1900X 8-Core Processor   | 1        | 1.52%   |
| AMD Ryzen 9 3900XT 12-Core Processor            | 1        | 1.52%   |
| AMD Ryzen 7 5800X 8-Core Processor              | 1        | 1.52%   |
| AMD Ryzen 7 1700 Eight-Core Processor           | 1        | 1.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 14       | 21.21%  |
| AMD Ryzen 5            | 11       | 16.67%  |
| AMD Ryzen 7            | 10       | 15.15%  |
| Intel Core i7          | 5        | 7.58%   |
| AMD FX                 | 5        | 7.58%   |
| AMD Ryzen 9            | 4        | 6.06%   |
| Other                  | 2        | 3.03%   |
| Intel Xeon             | 2        | 3.03%   |
| Intel Core i3          | 2        | 3.03%   |
| Intel Core 2 Duo       | 2        | 3.03%   |
| AMD Ryzen Threadripper | 2        | 3.03%   |
| AMD A10                | 2        | 3.03%   |
| Intel Pentium          | 1        | 1.52%   |
| Intel Celeron          | 1        | 1.52%   |
| AMD Ryzen 3            | 1        | 1.52%   |
| AMD Phenom II X4       | 1        | 1.52%   |
| AMD A6                 | 1        | 1.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 17       | 25.76%  |
| 4      | 16       | 24.24%  |
| 8      | 14       | 21.21%  |
| 2      | 8        | 12.12%  |
| 12     | 4        | 6.06%   |
| 3      | 2        | 3.03%   |
| 32     | 1        | 1.52%   |
| 16     | 1        | 1.52%   |
| 14     | 1        | 1.52%   |
| 10     | 1        | 1.52%   |
| 1      | 1        | 1.52%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 66       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 48       | 72.73%  |
| 1      | 18       | 27.27%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 66       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 21       | 30.43%  |
| 0x0800820d | 6        | 8.7%    |
| 0x08701013 | 5        | 7.25%   |
| 0x906ed    | 3        | 4.35%   |
| 0x206a7    | 3        | 4.35%   |
| 0x08701021 | 3        | 4.35%   |
| 0x06000822 | 3        | 4.35%   |
| 0xa0655    | 2        | 2.9%    |
| 0x506e3    | 2        | 2.9%    |
| 0x306c3    | 2        | 2.9%    |
| 0x0a201016 | 2        | 2.9%    |
| 0x06003106 | 2        | 2.9%    |
| 0x06000852 | 2        | 2.9%    |
| 0xa0653    | 1        | 1.45%   |
| 0x906e9    | 1        | 1.45%   |
| 0x6fd      | 1        | 1.45%   |
| 0x306a9    | 1        | 1.45%   |
| 0x206c2    | 1        | 1.45%   |
| 0x20652    | 1        | 1.45%   |
| 0x1067a    | 1        | 1.45%   |
| 0x0a50000b | 1        | 1.45%   |
| 0x0a201009 | 1        | 1.45%   |
| 0x0800820b | 1        | 1.45%   |
| 0x08001138 | 1        | 1.45%   |
| 0x08001137 | 1        | 1.45%   |
| 0x08001129 | 1        | 1.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen+             | 9        | 13.64%  |
| Zen 2            | 9        | 13.64%  |
| KabyLake         | 7        | 10.61%  |
| Zen 3            | 6        | 9.09%   |
| Piledriver       | 6        | 9.09%   |
| Zen              | 4        | 6.06%   |
| SandyBridge      | 4        | 6.06%   |
| CometLake        | 4        | 6.06%   |
| Haswell          | 3        | 4.55%   |
| Westmere         | 2        | 3.03%   |
| Steamroller      | 2        | 3.03%   |
| Skylake          | 2        | 3.03%   |
| IvyBridge        | 2        | 3.03%   |
| Alderlake Hybrid | 2        | 3.03%   |
| Penryn           | 1        | 1.52%   |
| K10              | 1        | 1.52%   |
| Core             | 1        | 1.52%   |
| Broadwell        | 1        | 1.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 38       | 53.52%  |
| Nvidia | 24       | 33.8%   |
| Intel  | 9        | 12.68%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 9        | 12.16%  |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 6        | 8.11%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 3        | 4.05%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 2        | 2.7%    |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 2.7%    |
| Nvidia GM206 [GeForce GTX 950]                                              | 2        | 2.7%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 2.7%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 2.7%    |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 2        | 2.7%    |
| AMD Redwood XT [Radeon HD 5670/5690/5730]                                   | 2        | 2.7%    |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                    | 2        | 2.7%    |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2        | 2.7%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 2.7%    |
| AMD Kaveri [Radeon R7 Graphics]                                             | 2        | 2.7%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 2.7%    |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 1.35%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 1.35%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 1.35%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 1.35%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                          | 1        | 1.35%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.35%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.35%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 1.35%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.35%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 1.35%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.35%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 1.35%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 1.35%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.35%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                           | 1        | 1.35%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.35%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 1.35%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 1        | 1.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 1.35%   |
| Intel HD Graphics 610                                                       | 1        | 1.35%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.35%   |
| Intel AlderLake-S GT1                                                       | 1        | 1.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.35%   |
| AMD Vega 20 [Radeon VII]                                                    | 1        | 1.35%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1        | 1.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 33       | 49.25%  |
| 1 x Nvidia     | 21       | 31.34%  |
| 1 x Intel      | 7        | 10.45%  |
| 2 x AMD        | 3        | 4.48%   |
| AMD + Nvidia   | 2        | 2.99%   |
| Intel + Nvidia | 1        | 1.49%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 50       | 73.53%  |
| Proprietary | 18       | 26.47%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 24       | 33.8%   |
| 7.01-8.0   | 15       | 21.13%  |
| 3.01-4.0   | 10       | 14.08%  |
| 1.01-2.0   | 8        | 11.27%  |
| 8.01-16.0  | 6        | 8.45%   |
| 0.51-1.0   | 6        | 8.45%   |
| 5.01-6.0   | 1        | 1.41%   |
| 0.01-0.5   | 1        | 1.41%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 14       | 16.28%  |
| Acer                 | 10       | 11.63%  |
| Goldstar             | 9        | 10.47%  |
| Philips              | 8        | 9.3%    |
| AOC                  | 7        | 8.14%   |
| Dell                 | 6        | 6.98%   |
| BenQ                 | 5        | 5.81%   |
| ASUSTek Computer     | 5        | 5.81%   |
| Ancor Communications | 3        | 3.49%   |
| ViewSonic            | 1        | 1.16%   |
| Vestel Elektronik    | 1        | 1.16%   |
| Sony                 | 1        | 1.16%   |
| Packard Bell         | 1        | 1.16%   |
| MSI                  | 1        | 1.16%   |
| LG Electronics       | 1        | 1.16%   |
| Lenovo Group Limited | 1        | 1.16%   |
| Lenovo               | 1        | 1.16%   |
| KTC                  | 1        | 1.16%   |
| Jean                 | 1        | 1.16%   |
| Iiyama               | 1        | 1.16%   |
| Idek Iiyama          | 1        | 1.16%   |
| HVR                  | 1        | 1.16%   |
| Hitachi              | 1        | 1.16%   |
| Hewlett-Packard      | 1        | 1.16%   |
| Envision Peripherals | 1        | 1.16%   |
| Eizo                 | 1        | 1.16%   |
| CTV                  | 1        | 1.16%   |
| Belinea              | 1        | 1.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 2        | 2.22%   |
| AOC F22 AOC2200 1920x1080 476x268mm 21.5-inch                           | 2        | 2.22%   |
| Ancor Communications ASUS PB277 ACI27B5 2560x1440 597x336mm 27.0-inch   | 2        | 2.22%   |
| ViewSonic LCD Monitor VX2452 Series 3840x1080                           | 1        | 1.11%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                        | 1        | 1.11%   |
| Sony TV SNY7001 1920x1080                                               | 1        | 1.11%   |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch       | 1        | 1.11%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch       | 1        | 1.11%   |
| Samsung Electronics T24B301 SAM098E 1920x1080 521x293mm 23.5-inch       | 1        | 1.11%   |
| Samsung Electronics SMBX2450 SAM0721 1920x1080 531x299mm 24.0-inch      | 1        | 1.11%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1        | 1.11%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch       | 1        | 1.11%   |
| Samsung Electronics S24A31x SAM7114 1920x1080 527x296mm 23.8-inch       | 1        | 1.11%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 1        | 1.11%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 950x540mm 43.0-inch   | 1        | 1.11%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1872x1053mm 84.6-inch | 1        | 1.11%   |
| Samsung Electronics LCD Monitor SAM047D 2288x1287 410x230mm 18.5-inch   | 1        | 1.11%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch      | 1        | 1.11%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 700x390mm 31.5-inch       | 1        | 1.11%   |
| Samsung Electronics C27FG7x SAM0E41 1920x1080 598x337mm 27.0-inch       | 1        | 1.11%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch       | 1        | 1.11%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 1        | 1.11%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch                | 1        | 1.11%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch                 | 1        | 1.11%   |
| Philips PHL 245E1 PHLC20B 2560x1440 527x296mm 23.8-inch                 | 1        | 1.11%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 1        | 1.11%   |
| Philips PHL 223V5LH PHLC114 1920x1080 477x268mm 21.5-inch               | 1        | 1.11%   |
| Philips PHL 220V8 PHLC218 1920x1080 477x268mm 21.5-inch                 | 1        | 1.11%   |
| Philips 247ELH PHLC085 1920x1080 521x293mm 23.5-inch                    | 1        | 1.11%   |
| Philips 226VL PHLC081 1920x1080 480x268mm 21.6-inch                     | 1        | 1.11%   |
| Packard Bell Viseo203DX PKB0378 1600x900 432x240mm 19.5-inch            | 1        | 1.11%   |
| MSI Optix G241VC MSI1462 1920x1080 521x294mm 23.6-inch                  | 1        | 1.11%   |
| LG Electronics LCD Monitor 34UC89G                                      | 1        | 1.11%   |
| Lenovo L197 Wide LEN1152 1440x900 410x257mm 19.1-inch                   | 1        | 1.11%   |
| Lenovo Group Limited LCD Monitor LEN LI2323swA 4480x1080                | 1        | 1.11%   |
| KTC W2402S KTC2400 1920x1080 527x296mm 23.8-inch                        | 1        | 1.11%   |
| Jean JT198x6-7 JEN17C6 1280x1024 376x301mm 19.0-inch                    | 1        | 1.11%   |
| Iiyama PL3461WQ IVM7615 3440x1440 800x335mm 34.1-inch                   | 1        | 1.11%   |
| Idek Iiyama LCD Monitor PL2488H                                         | 1        | 1.11%   |
| HVR HTC-VIVE HVRAA01 2160x1200                                          | 1        | 1.11%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 37       | 44.58%  |
| 3840x2160 (4K)     | 16       | 19.28%  |
| 2560x1440 (QHD)    | 7        | 8.43%   |
| 1280x1024 (SXGA)   | 3        | 3.61%   |
| Unknown            | 3        | 3.61%   |
| 3840x1080          | 2        | 2.41%   |
| 3440x1440          | 2        | 2.41%   |
| 2560x1080          | 2        | 2.41%   |
| 1360x768           | 2        | 2.41%   |
| 4480x1080          | 1        | 1.2%    |
| 3600x1080          | 1        | 1.2%    |
| 2160x1200          | 1        | 1.2%    |
| 1920x1200 (WUXGA)  | 1        | 1.2%    |
| 1680x1050 (WSXGA+) | 1        | 1.2%    |
| 1600x900 (HD+)     | 1        | 1.2%    |
| 1440x900 (WXGA+)   | 1        | 1.2%    |
| 1280x960           | 1        | 1.2%    |
| 1024x768 (XGA)     | 1        | 1.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 14       | 17.07%  |
| 23      | 14       | 17.07%  |
| 24      | 12       | 14.63%  |
| 21      | 11       | 13.41%  |
| Unknown | 5        | 6.1%    |
| 84      | 4        | 4.88%   |
| 34      | 4        | 4.88%   |
| 31      | 4        | 4.88%   |
| 19      | 4        | 4.88%   |
| 32      | 2        | 2.44%   |
| 15      | 2        | 2.44%   |
| 72      | 1        | 1.22%   |
| 52      | 1        | 1.22%   |
| 48      | 1        | 1.22%   |
| 20      | 1        | 1.22%   |
| 18      | 1        | 1.22%   |
| 17      | 1        | 1.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 35       | 43.75%  |
| 401-500     | 14       | 17.5%   |
| 601-700     | 7        | 8.75%   |
| 701-800     | 6        | 7.5%    |
| 1501-2000   | 5        | 6.25%   |
| Unknown     | 5        | 6.25%   |
| 351-400     | 3        | 3.75%   |
| 301-350     | 3        | 3.75%   |
| 1001-1500   | 2        | 2.5%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 55       | 75.34%  |
| 5/4     | 4        | 5.48%   |
| 21/9    | 4        | 5.48%   |
| 16/10   | 4        | 5.48%   |
| Unknown | 4        | 5.48%   |
| 4/3     | 1        | 1.37%   |
| 32/9    | 1        | 1.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 34       | 41.46%  |
| 301-350        | 14       | 17.07%  |
| 351-500        | 10       | 12.2%   |
| More than 1000 | 6        | 7.32%   |
| 151-200        | 6        | 7.32%   |
| Unknown        | 5        | 6.1%    |
| 251-300        | 2        | 2.44%   |
| 141-150        | 2        | 2.44%   |
| 101-110        | 2        | 2.44%   |
| 501-1000       | 1        | 1.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 40       | 52.63%  |
| 101-120 | 19       | 25%     |
| 121-160 | 7        | 9.21%   |
| Unknown | 5        | 6.58%   |
| 161-240 | 3        | 3.95%   |
| 1-50    | 2        | 2.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 48       | 70.59%  |
| 2     | 16       | 23.53%  |
| 3     | 3        | 4.41%   |
| 4     | 1        | 1.47%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 43       | 48.31%  |
| Intel                                 | 28       | 31.46%  |
| TP-Link                               | 3        | 3.37%   |
| Qualcomm Atheros                      | 3        | 3.37%   |
| D-Link System                         | 3        | 3.37%   |
| Ralink Technology                     | 2        | 2.25%   |
| Xiaomi                                | 1        | 1.12%   |
| Qualcomm Atheros Communications       | 1        | 1.12%   |
| Microsoft                             | 1        | 1.12%   |
| Google                                | 1        | 1.12%   |
| DisplayLink                           | 1        | 1.12%   |
| Aquantia                              | 1        | 1.12%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 1.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 36       | 31.58%  |
| Intel I211 Gigabit Network Connection                             | 10       | 8.77%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3        | 2.63%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 2.63%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 2        | 1.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2        | 1.75%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2        | 1.75%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 2        | 1.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 1.75%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 1.75%   |
| Intel Wi-Fi 6 AX200                                               | 2        | 1.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 1.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2        | 1.75%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 1.75%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 1.75%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.88%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1        | 0.88%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1        | 0.88%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 0.88%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1        | 0.88%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 0.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 0.88%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1        | 0.88%   |
| Realtek 802.11ac NIC                                              | 1        | 0.88%   |
| Ralink RT5370 Wireless Adapter                                    | 1        | 0.88%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 0.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1        | 0.88%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.88%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.88%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1        | 0.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 0.88%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.88%   |
| Microsoft Xbox Wireless Adapter for Windows                       | 1        | 0.88%   |
| Intel Wireless-AC 9260                                            | 1        | 0.88%   |
| Intel Wireless 8265 / 8275                                        | 1        | 0.88%   |
| Intel Wireless 8260                                               | 1        | 0.88%   |
| Intel Wireless 7265                                               | 1        | 0.88%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.88%   |
| Intel Ethernet Controller I225-V                                  | 1        | 0.88%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1        | 0.88%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 14       | 41.18%  |
| Realtek Semiconductor                 | 9        | 26.47%  |
| TP-Link                               | 3        | 8.82%   |
| Ralink Technology                     | 2        | 5.88%   |
| Qualcomm Atheros                      | 2        | 5.88%   |
| Qualcomm Atheros Communications       | 1        | 2.94%   |
| Microsoft                             | 1        | 2.94%   |
| D-Link System                         | 1        | 2.94%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 2.94%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                               | Desktops | Percent |
|-----------------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                              | 3        | 8.57%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                         | 2        | 5.71%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                                     | 2        | 5.71%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                            | 2        | 5.71%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                            | 2        | 5.71%   |
| Intel Wi-Fi 6 AX200                                                                                 | 2        | 5.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                                    | 2        | 5.71%   |
| Intel Cannon Lake PCH CNVi WiFi                                                                     | 2        | 5.71%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                                 | 1        | 2.86%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                                     | 1        | 2.86%   |
| Realtek RTL8188EE Wireless Network Adapter                                                          | 1        | 2.86%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                             | 1        | 2.86%   |
| Realtek 802.11ac NIC                                                                                | 1        | 2.86%   |
| Ralink RT5370 Wireless Adapter                                                                      | 1        | 2.86%   |
| Ralink MT7601U Wireless Adapter                                                                     | 1        | 2.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                          | 1        | 2.86%   |
| Qualcomm Atheros AR9271 802.11n                                                                     | 1        | 2.86%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                                    | 1        | 2.86%   |
| Microsoft Xbox Wireless Adapter for Windows                                                         | 1        | 2.86%   |
| Intel Wireless-AC 9260                                                                              | 1        | 2.86%   |
| Intel Wireless 8265 / 8275                                                                          | 1        | 2.86%   |
| Intel Wireless 8260                                                                                 | 1        | 2.86%   |
| Intel Wireless 7265                                                                                 | 1        | 2.86%   |
| Intel Comet Lake PCH CNVi WiFi                                                                      | 1        | 2.86%   |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A2) [Atheros AR9170+AR9104]         | 1        | 2.86%   |
| 802.11g Adapter [Linksys WUSB54GC v3] WUSB100 v2 RangePlus Wireless Network Adapter [Ralink RT3070] | 1        | 2.86%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 40       | 54.79%  |
| Intel                 | 24       | 32.88%  |
| Qualcomm Atheros      | 3        | 4.11%   |
| D-Link System         | 2        | 2.74%   |
| Xiaomi                | 1        | 1.37%   |
| Google                | 1        | 1.37%   |
| DisplayLink           | 1        | 1.37%   |
| Aquantia              | 1        | 1.37%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 36       | 45.57%  |
| Intel I211 Gigabit Network Connection                             | 10       | 12.66%  |
| Intel Ethernet Connection (2) I219-V                              | 3        | 3.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 2.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 2.53%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 2.53%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 2.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.27%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.27%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 1.27%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1        | 1.27%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 1.27%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.27%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.27%   |
| Intel I210 Gigabit Network Connection                             | 1        | 1.27%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.27%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1        | 1.27%   |
| Intel Ethernet Connection I219-LM                                 | 1        | 1.27%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.27%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.27%   |
| Intel Ethernet Connection (17) I219-V                             | 1        | 1.27%   |
| Intel Ethernet Connection (12) I219-V                             | 1        | 1.27%   |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 1.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 1.27%   |
| Intel 82567LF-2 Gigabit Network Connection                        | 1        | 1.27%   |
| Intel 82562V-2 10/100 Network Connection                          | 1        | 1.27%   |
| Google Nexus/Pixel Device (tether+ debug)                         | 1        | 1.27%   |
| DisplayLink Kensington Dock (Composite Device)                    | 1        | 1.27%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 65       | 65.66%  |
| WiFi     | 34       | 34.34%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 48       | 73.85%  |
| WiFi     | 17       | 26.15%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 34       | 51.52%  |
| 2     | 26       | 39.39%  |
| 3     | 3        | 4.55%   |
| 4     | 2        | 3.03%   |
| 0     | 1        | 1.52%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 58       | 86.57%  |
| Yes  | 9        | 13.43%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 14       | 45.16%  |
| Cambridge Silicon Radio         | 7        | 22.58%  |
| IMC Networks                    | 4        | 12.9%   |
| ASUSTek Computer                | 2        | 6.45%   |
| Qualcomm Atheros Communications | 1        | 3.23%   |
| HTC (High Tech Computer)        | 1        | 3.23%   |
| Dynex                           | 1        | 3.23%   |
| Broadcom                        | 1        | 3.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 7        | 22.58%  |
| Intel Bluetooth wireless interface                                   | 3        | 9.68%   |
| Intel AX210 Bluetooth                                                | 3        | 9.68%   |
| IMC Networks Bluetooth Radio                                         | 3        | 9.68%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 2        | 6.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 2        | 6.45%   |
| Intel AX200 Bluetooth                                                | 2        | 6.45%   |
| Qualcomm Atheros  Bluetooth Device                                   | 1        | 3.23%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 1        | 3.23%   |
| Intel AX201 Bluetooth                                                | 1        | 3.23%   |
| IMC Networks Bluetooth Device                                        | 1        | 3.23%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 3.23%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 1        | 3.23%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 1        | 3.23%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 1        | 3.23%   |
| ASUS Bluetooth Radio                                                 | 1        | 3.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD                                             | 49       | 37.12%  |
| Intel                                           | 28       | 21.21%  |
| Nvidia                                          | 24       | 18.18%  |
| C-Media Electronics                             | 9        | 6.82%   |
| Creative Labs                                   | 4        | 3.03%   |
| Logitech                                        | 2        | 1.52%   |
| Creative Technology                             | 2        | 1.52%   |
| TC Electronic                                   | 1        | 0.76%   |
| SteelSeries ApS                                 | 1        | 0.76%   |
| Shure                                           | 1        | 0.76%   |
| Realtek Semiconductor                           | 1        | 0.76%   |
| Razer USA                                       | 1        | 0.76%   |
| PreSonus Audio Electronics                      | 1        | 0.76%   |
| Native Instruments                              | 1        | 0.76%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.76%   |
| JMTek                                           | 1        | 0.76%   |
| Generalplus Technology                          | 1        | 0.76%   |
| Focusrite-Novation                              | 1        | 0.76%   |
| EVGA                                            | 1        | 0.76%   |
| Corsair                                         | 1        | 0.76%   |
| AudioQuest                                      | 1        | 0.76%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 12       | 7.45%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 12       | 7.45%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 11       | 6.83%   |
| AMD Navi 10 HDMI Audio                                                     | 7        | 4.35%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6        | 3.73%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 5        | 3.11%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 5        | 3.11%   |
| Nvidia GP104 High Definition Audio Controller                              | 4        | 2.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 2.48%   |
| Intel 200 Series PCH HD Audio                                              | 4        | 2.48%   |
| Intel Comet Lake PCH-V cAVS                                                | 3        | 1.86%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 1.86%   |
| C-Media Electronics USB Audio Device                                       | 3        | 1.86%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 3        | 1.86%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3        | 1.86%   |
| AMD FCH Azalia Controller                                                  | 3        | 1.86%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3        | 1.86%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 1.24%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 1.24%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 1.24%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 1.24%   |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 1.24%   |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 1.24%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 1.24%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2        | 1.24%   |
| Creative Labs CA0110 [Sound Blaster X-Fi Xtreme Audio]                     | 2        | 1.24%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 2        | 1.24%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 2        | 1.24%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 2        | 1.24%   |
| TC Electronic VoiceLive Play                                               | 1        | 0.62%   |
| SteelSeries ApS Arctis Pro Wireless                                        | 1        | 0.62%   |
| Shure MV7                                                                  | 1        | 0.62%   |
| Realtek Semiconductor Realtek Audio USB                                    | 1        | 0.62%   |
| Razer USA RZ19-0229 Gaming Microphone                                      | 1        | 0.62%   |
| PreSonus Audio Electronics AudioBox Go                                     | 1        | 0.62%   |
| Nvidia TU102 High Definition Audio Controller                              | 1        | 0.62%   |
| Nvidia High Definition Audio Controller                                    | 1        | 0.62%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.62%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 0.62%   |
| Nvidia GM200 High Definition Audio                                         | 1        | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 14       | 22.22%  |
| Kingston            | 12       | 19.05%  |
| G.Skill             | 12       | 19.05%  |
| Unknown             | 5        | 7.94%   |
| SK hynix            | 4        | 6.35%   |
| Patriot             | 4        | 6.35%   |
| Crucial             | 4        | 6.35%   |
| Samsung Electronics | 3        | 4.76%   |
| A-DATA Technology   | 2        | 3.17%   |
| Transcend           | 1        | 1.59%   |
| Micron Technology   | 1        | 1.59%   |
| AMD                 | 1        | 1.59%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s     | 3        | 4.48%   |
| Kingston RAM 99U5474-026.A00LF 4GB DIMM DDR3 1333MT/s    | 2        | 2.99%   |
| G.Skill RAM F3-10666CL9-4GBNT 4GB DIMM DDR3 1600MT/s     | 2        | 2.99%   |
| Crucial RAM BLS16G4D30AESB.M16FE 16GB DIMM DDR4 3200MT/s | 2        | 2.99%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 2        | 2.99%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s    | 2        | 2.99%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                | 1        | 1.49%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 1        | 1.49%   |
| Unknown RAM Module 2048MB DIMM SDRAM                     | 1        | 1.49%   |
| Unknown RAM Module 2048MB DIMM 1328MT/s                  | 1        | 1.49%   |
| Unknown RAM 3600 C20 Series 32GB DIMM DDR4 3666MT/s      | 1        | 1.49%   |
| Transcend RAM JM2666HLB-16G 16GB DIMM DDR4 2667MT/s      | 1        | 1.49%   |
| SK hynix RAM HMA82GU7CJR8N-VK 16GB DIMM DDR4 2667MT/s    | 1        | 1.49%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s  | 1        | 1.49%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s   | 1        | 1.49%   |
| SK hynix RAM HMA41GU6AFR8N-TF 8GB DIMM DDR4 2465MT/s     | 1        | 1.49%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s      | 1        | 1.49%   |
| Samsung RAM M323R2GA3BB0-CQKOL 16GB DIMM DDR5 4802MT/s   | 1        | 1.49%   |
| Samsung RAM M3 78T2863RZS-CF7 1GB DIMM DDR2 800MT/s      | 1        | 1.49%   |
| Patriot RAM PSD48G240082 8GB DIMM DDR4 2400MT/s          | 1        | 1.49%   |
| Patriot RAM PSD48G240081 8GB DIMM DDR4 2800MT/s          | 1        | 1.49%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s           | 1        | 1.49%   |
| Patriot RAM 3000 C16 Series 16GB DIMM DDR4 3200MT/s      | 1        | 1.49%   |
| Micron RAM 16ATF2G64HZ-2G6J1 16GB SODIMM DDR4 2667MT/s   | 1        | 1.49%   |
| Kingston RAM XJ69DF-MIE 8GB DIMM DDR4 2933MT/s           | 1        | 1.49%   |
| Kingston RAM MSI24D4U7S8MB-8 8GB DIMM DDR4 2400MT/s      | 1        | 1.49%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s        | 1        | 1.49%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s      | 1        | 1.49%   |
| Kingston RAM KF2666C16D4/8G 8GB DIMM DDR4 2667MT/s       | 1        | 1.49%   |
| Kingston RAM 99U5595-003.A00LF 2GB DIMM DDR3             | 1        | 1.49%   |
| Kingston RAM 99U5584-014.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 1.49%   |
| Kingston RAM 99U5474-010.A00LF 2GB DIMM DDR3 1333MT/s    | 1        | 1.49%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 1.49%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 1.49%   |
| Kingston RAM 99P5474-033.A00LF 2GB DIMM DDR3 1600MT/s    | 1        | 1.49%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s   | 1        | 1.49%   |
| G.Skill RAM F4-3200C16-8GVRB 8GB DIMM DDR4 3200MT/s      | 1        | 1.49%   |
| G.Skill RAM F4-3200C16-8GSXWB 8GB DIMM DDR4 4133MT/s     | 1        | 1.49%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s       | 1        | 1.49%   |
| G.Skill RAM F4-3200C14-16GTZR 16GB DIMM DDR4 3600MT/s    | 1        | 1.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 34       | 61.82%  |
| DDR3    | 15       | 27.27%  |
| DDR5    | 2        | 3.64%   |
| Unknown | 2        | 3.64%   |
| SDRAM   | 1        | 1.82%   |
| DDR2    | 1        | 1.82%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 53       | 96.36%  |
| SODIMM | 2        | 3.64%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 27       | 45.76%  |
| 4096  | 13       | 22.03%  |
| 16384 | 11       | 18.64%  |
| 2048  | 4        | 6.78%   |
| 32768 | 3        | 5.08%   |
| 1024  | 1        | 1.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 10       | 16.67%  |
| 1600    | 9        | 15%     |
| 3600    | 8        | 13.33%  |
| 2667    | 5        | 8.33%   |
| 1333    | 5        | 8.33%   |
| 2400    | 3        | 5%      |
| 3666    | 2        | 3.33%   |
| 3533    | 2        | 3.33%   |
| 2933    | 2        | 3.33%   |
| 2133    | 2        | 3.33%   |
| 4802    | 1        | 1.67%   |
| 4800    | 1        | 1.67%   |
| 4133    | 1        | 1.67%   |
| 3733    | 1        | 1.67%   |
| 3400    | 1        | 1.67%   |
| 3000    | 1        | 1.67%   |
| 2800    | 1        | 1.67%   |
| 2481    | 1        | 1.67%   |
| 2465    | 1        | 1.67%   |
| 1328    | 1        | 1.67%   |
| 800     | 1        | 1.67%   |
| Unknown | 1        | 1.67%   |

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
| Logitech                      | 6        | 37.5%   |
| Microdia                      | 2        | 12.5%   |
| Creative Technology           | 2        | 12.5%   |
| WaveRider Communications      | 1        | 6.25%   |
| Sunplus Innovation Technology | 1        | 6.25%   |
| Microsoft                     | 1        | 6.25%   |
| KYE Systems (Mouse Systems)   | 1        | 6.25%   |
| GEMBIRD                       | 1        | 6.25%   |
| ARC International             | 1        | 6.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Logitech Webcam C270                           | 2        | 12.5%   |
| WaveRider USB 2.0 Camera                       | 1        | 6.25%   |
| Sunplus Aukey-PC-LM1E Camera                   | 1        | 6.25%   |
| Microsoft LifeCam Cinema                       | 1        | 6.25%   |
| Microdia Webcam Vitade AF                      | 1        | 6.25%   |
| Microdia USB 2.0 Camera                        | 1        | 6.25%   |
| Logitech Webcam C930e                          | 1        | 6.25%   |
| Logitech Webcam C310                           | 1        | 6.25%   |
| Logitech HD Webcam C910                        | 1        | 6.25%   |
| Logitech BRIO Ultra HD Webcam                  | 1        | 6.25%   |
| KYE Systems (Mouse Systems) Genius FaceCam 320 | 1        | 6.25%   |
| GEMBIRD USB2.0 PC CAMERA                       | 1        | 6.25%   |
| Creative Live! Cam Sync HD [VF0770]            | 1        | 6.25%   |
| Creative Live! Cam Chat HD [VF0700]            | 1        | 6.25%   |
| ARC International Camera                       | 1        | 6.25%   |

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
| 0     | 59       | 89.39%  |
| 1     | 6        | 9.09%   |
| 3     | 1        | 1.52%   |

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

