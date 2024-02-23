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

Total: 115

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock    | B450 Pro4                   | [457ba2586a](https://linux-hardware.org/?probe=457ba2586a) | Jan 03, 2024 |
| HP        | 2B29                        | [93ef9f39bd](https://linux-hardware.org/?probe=93ef9f39bd) | Dec 24, 2023 |
| MSI       | 970 GAMING                  | [498753636e](https://linux-hardware.org/?probe=498753636e) | Dec 22, 2023 |
| ASRock    | X300M-STX                   | [9109738b7f](https://linux-hardware.org/?probe=9109738b7f) | Dec 22, 2023 |
| ASRock    | X300M-STX                   | [4017c676bf](https://linux-hardware.org/?probe=4017c676bf) | Dec 22, 2023 |
| ASRock    | B450 Gaming K4              | [96ff1ae1f7](https://linux-hardware.org/?probe=96ff1ae1f7) | Nov 28, 2023 |
| Intel     | X99H                        | [056d58d460](https://linux-hardware.org/?probe=056d58d460) | Nov 19, 2023 |
| Intel     | X99H                        | [409013cb66](https://linux-hardware.org/?probe=409013cb66) | Nov 19, 2023 |
| Gigabyte  | H61M-S2PV                   | [4174372199](https://linux-hardware.org/?probe=4174372199) | Nov 11, 2023 |
| Gigabyte  | H61M-S2PV                   | [749f236b5d](https://linux-hardware.org/?probe=749f236b5d) | Nov 09, 2023 |
| ASRock    | B450 Gaming K4              | [94dac5876f](https://linux-hardware.org/?probe=94dac5876f) | Nov 07, 2023 |
| ASRock    | B450 Gaming K4              | [77879ace29](https://linux-hardware.org/?probe=77879ace29) | Nov 07, 2023 |
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
| Artix Rolling  | 50       | 62.5%   |
| Artix          | 21       | 26.25%  |
| Artix 20220123 | 2        | 2.5%    |
| Artix 20210726 | 2        | 2.5%    |
| Artix 20230501 | 1        | 1.25%   |
| Artix 20230320 | 1        | 1.25%   |
| Artix 20230306 | 1        | 1.25%   |
| Artix 20230215 | 1        | 1.25%   |
| Artix 20220713 | 1        | 1.25%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| Artix | 77       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 6.5.7-artix1-1         | 3        | 3.3%    |
| 5.10.8-artix1-1        | 3        | 3.3%    |
| 6.6.7-artix1-1         | 2        | 2.2%    |
| 6.6.4-artix1-1         | 2        | 2.2%    |
| 6.2.6-artix1-1         | 2        | 2.2%    |
| 6.2.13-artix1-1        | 2        | 2.2%    |
| 6.1.8-artix1-1         | 2        | 2.2%    |
| 5.9.14-artix1-1        | 2        | 2.2%    |
| 5.8.8-artix1-1         | 2        | 2.2%    |
| 5.8.12-artix1-1        | 2        | 2.2%    |
| 5.7.6-artix1-1         | 2        | 2.2%    |
| 5.7.12-artix1-1        | 2        | 2.2%    |
| 5.18.16-artix1-1       | 2        | 2.2%    |
| 5.15.12-artix1-1       | 2        | 2.2%    |
| 5.12.14-artix1-1       | 2        | 2.2%    |
| 5.12.12-artix1-1       | 2        | 2.2%    |
| 5.11.16-artix1-1       | 2        | 2.2%    |
| 5.10.4-artix2-1        | 2        | 2.2%    |
| 6.6.1-artix1-1         | 1        | 1.1%    |
| 6.5.5-artix1-1         | 1        | 1.1%    |
| 6.5.2-zen1-1-zen       | 1        | 1.1%    |
| 6.4.4-artix1-1         | 1        | 1.1%    |
| 6.4.3-artix1-2         | 1        | 1.1%    |
| 6.4.15-lqx1-2-lqx      | 1        | 1.1%    |
| 6.4.10-artix1-1        | 1        | 1.1%    |
| 6.3.7-zen1-1-zen       | 1        | 1.1%    |
| 6.3.6-artix1-1         | 1        | 1.1%    |
| 6.3.2-zen1-1-zen       | 1        | 1.1%    |
| 6.2.11-artix1-1        | 1        | 1.1%    |
| 6.1.4-artix1-1         | 1        | 1.1%    |
| 6.1.32-1-lts           | 1        | 1.1%    |
| 6.1.12-artix1-1        | 1        | 1.1%    |
| 6.1.1-x64v1-xanmod1-1  | 1        | 1.1%    |
| 6.0.7-artix1-1         | 1        | 1.1%    |
| 6.0.1-arch1-1          | 1        | 1.1%    |
| 5.9.8-zen1-1-zen       | 1        | 1.1%    |
| 5.9.14-zen1-1-zen      | 1        | 1.1%    |
| 5.9.12-artix1-1        | 1        | 1.1%    |
| 5.9.10-artix1-1        | 1        | 1.1%    |
| 5.8.5-xanmod1-1-xanmod | 1        | 1.1%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.5.7   | 3        | 3.3%    |
| 5.9.14  | 3        | 3.3%    |
| 5.10.8  | 3        | 3.3%    |
| 6.6.7   | 2        | 2.2%    |
| 6.6.4   | 2        | 2.2%    |
| 6.2.6   | 2        | 2.2%    |
| 6.2.13  | 2        | 2.2%    |
| 6.1.8   | 2        | 2.2%    |
| 5.8.8   | 2        | 2.2%    |
| 5.8.12  | 2        | 2.2%    |
| 5.7.6   | 2        | 2.2%    |
| 5.7.12  | 2        | 2.2%    |
| 5.18.16 | 2        | 2.2%    |
| 5.15.12 | 2        | 2.2%    |
| 5.12.14 | 2        | 2.2%    |
| 5.12.12 | 2        | 2.2%    |
| 5.11.16 | 2        | 2.2%    |
| 5.10.4  | 2        | 2.2%    |
| 5.10.15 | 2        | 2.2%    |
| 6.6.1   | 1        | 1.1%    |
| 6.5.5   | 1        | 1.1%    |
| 6.5.2   | 1        | 1.1%    |
| 6.4.4   | 1        | 1.1%    |
| 6.4.3   | 1        | 1.1%    |
| 6.4.15  | 1        | 1.1%    |
| 6.4.10  | 1        | 1.1%    |
| 6.3.7   | 1        | 1.1%    |
| 6.3.6   | 1        | 1.1%    |
| 6.3.2   | 1        | 1.1%    |
| 6.2.11  | 1        | 1.1%    |
| 6.1.4   | 1        | 1.1%    |
| 6.1.32  | 1        | 1.1%    |
| 6.1.12  | 1        | 1.1%    |
| 6.1.1   | 1        | 1.1%    |
| 6.0.7   | 1        | 1.1%    |
| 6.0.1   | 1        | 1.1%    |
| 5.9.8   | 1        | 1.1%    |
| 5.9.12  | 1        | 1.1%    |
| 5.9.10  | 1        | 1.1%    |
| 5.8.5   | 1        | 1.1%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 10       | 11.49%  |
| 5.15    | 7        | 8.05%   |
| 5.9     | 6        | 6.9%    |
| 5.8     | 6        | 6.9%    |
| 5.12    | 6        | 6.9%    |
| 6.6     | 5        | 5.75%   |
| 6.5     | 5        | 5.75%   |
| 6.2     | 5        | 5.75%   |
| 6.1     | 5        | 5.75%   |
| 5.7     | 4        | 4.6%    |
| 5.16    | 4        | 4.6%    |
| 5.11    | 4        | 4.6%    |
| 6.4     | 3        | 3.45%   |
| 6.3     | 3        | 3.45%   |
| 5.18    | 3        | 3.45%   |
| 5.17    | 3        | 3.45%   |
| 6.0     | 2        | 2.3%    |
| 5.14    | 2        | 2.3%    |
| 5.13    | 2        | 2.3%    |
| 5.4     | 1        | 1.15%   |
| 4.19    | 1        | 1.15%   |

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


| Name       | Desktops | Percent |
|------------|----------|---------|
| KDE5       | 26       | 31.71%  |
| GNOME      | 12       | 14.63%  |
| XFCE       | 10       | 12.2%   |
| Unknown    | 7        | 8.54%   |
| X-Cinnamon | 6        | 7.32%   |
| MATE       | 6        | 7.32%   |
| i3         | 3        | 3.66%   |
| Cinnamon   | 3        | 3.66%   |
| bspwm      | 3        | 3.66%   |
| LXQt       | 2        | 2.44%   |
| sway       | 1        | 1.22%   |
| openbox    | 1        | 1.22%   |
| LXDE       | 1        | 1.22%   |
| DWM        | 1        | 1.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 60       | 75.95%  |
| Tty     | 11       | 13.92%  |
| Wayland | 5        | 6.33%   |
| Unknown | 3        | 3.8%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 33       | 40.74%  |
| SDDM    | 24       | 29.63%  |
| LightDM | 19       | 23.46%  |
| GDM     | 2        | 2.47%   |
| XDM     | 1        | 1.23%   |
| SLiM    | 1        | 1.23%   |
| LXDM    | 1        | 1.23%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 31       | 39.74%  |
| ru_RU   | 9        | 11.54%  |
| Unknown | 7        | 8.97%   |
| fr_FR   | 5        | 6.41%   |
| C       | 5        | 6.41%   |
| de_DE   | 3        | 3.85%   |
| pt_PT   | 2        | 2.56%   |
| pt_BR   | 2        | 2.56%   |
| en_GB   | 2        | 2.56%   |
| tr_TR   | 1        | 1.28%   |
| lt_LT   | 1        | 1.28%   |
| ja_JP   | 1        | 1.28%   |
| it_IT   | 1        | 1.28%   |
| es_MX   | 1        | 1.28%   |
| es_AR   | 1        | 1.28%   |
| en_IE   | 1        | 1.28%   |
| en_AU   | 1        | 1.28%   |
| el_GR   | 1        | 1.28%   |
| de_CH   | 1        | 1.28%   |
| de_AT   | 1        | 1.28%   |
| bg_BG   | 1        | 1.28%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 53       | 67.95%  |
| BIOS | 25       | 32.05%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 52       | 67.53%  |
| Btrfs | 17       | 22.08%  |
| Xfs   | 4        | 5.19%   |
| F2fs  | 2        | 2.6%    |
| Tmpfs | 1        | 1.3%    |
| Jfs   | 1        | 1.3%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 58       | 73.42%  |
| Unknown | 17       | 21.52%  |
| MBR     | 4        | 5.06%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 57       | 72.15%  |
| Yes       | 22       | 27.85%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 57       | 73.08%  |
| Yes       | 21       | 26.92%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 20       | 25.97%  |
| MSI                 | 17       | 22.08%  |
| Gigabyte Technology | 17       | 22.08%  |
| ASRock              | 10       | 12.99%  |
| Intel               | 3        | 3.9%    |
| Hewlett-Packard     | 3        | 3.9%    |
| Dell                | 3        | 3.9%    |
| Biostar             | 2        | 2.6%    |
| MACHINIST           | 1        | 1.3%    |
| Alienware           | 1        | 1.3%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| MSI MS-7A38                    | 3        | 3.9%    |
| MSI MS-7C37                    | 2        | 2.6%    |
| MSI MS-7C02                    | 2        | 2.6%    |
| Intel X99                      | 2        | 2.6%    |
| Gigabyte 970A-DS3P             | 2        | 2.6%    |
| MSI MS-7E07                    | 1        | 1.3%    |
| MSI MS-7C89                    | 1        | 1.3%    |
| MSI MS-7C56                    | 1        | 1.3%    |
| MSI MS-7B79                    | 1        | 1.3%    |
| MSI MS-7B09                    | 1        | 1.3%    |
| MSI MS-7A69                    | 1        | 1.3%    |
| MSI MS-7A15                    | 1        | 1.3%    |
| MSI MS-7982                    | 1        | 1.3%    |
| MSI MS-7850                    | 1        | 1.3%    |
| MSI MS-7693                    | 1        | 1.3%    |
| MACHINIST X99-MR9D PLUS V1.0   | 1        | 1.3%    |
| Intel DX58SO2 AAG10925-205     | 1        | 1.3%    |
| HP Compaq 8200 Elite SFF PC    | 1        | 1.3%    |
| HP 550-a114                    | 1        | 1.3%    |
| HP 280 G1 MT                   | 1        | 1.3%    |
| Gigabyte Z77X-UD3H             | 1        | 1.3%    |
| Gigabyte X570 AORUS ULTRA      | 1        | 1.3%    |
| Gigabyte X570 AORUS ELITE WIFI | 1        | 1.3%    |
| Gigabyte X570 AORUS ELITE      | 1        | 1.3%    |
| Gigabyte X399 AORUS XTREME     | 1        | 1.3%    |
| Gigabyte P55-USB3              | 1        | 1.3%    |
| Gigabyte HA65M-D2H-B3          | 1        | 1.3%    |
| Gigabyte H61MA-D3V             | 1        | 1.3%    |
| Gigabyte H61M-S2PV             | 1        | 1.3%    |
| Gigabyte H410M H               | 1        | 1.3%    |
| Gigabyte B550M AORUS PRO       | 1        | 1.3%    |
| Gigabyte B450 AORUS PRO WIFI   | 1        | 1.3%    |
| Gigabyte AB350M-DS3H V2        | 1        | 1.3%    |
| Gigabyte 990FXA-UD5            | 1        | 1.3%    |
| Gigabyte 990FXA-UD3 R5         | 1        | 1.3%    |
| Dell OptiPlex 7060             | 1        | 1.3%    |
| Dell OptiPlex 5080             | 1        | 1.3%    |
| Dell Inspiron 530              | 1        | 1.3%    |
| Biostar G31D-M7                | 1        | 1.3%    |
| Biostar A320MH                 | 1        | 1.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS ROG              | 5        | 6.49%   |
| MSI MS-7A38           | 3        | 3.9%    |
| Gigabyte X570         | 3        | 3.9%    |
| ASUS TUF              | 3        | 3.9%    |
| ASUS PRIME            | 3        | 3.9%    |
| ASRock B450           | 3        | 3.9%    |
| MSI MS-7C37           | 2        | 2.6%    |
| MSI MS-7C02           | 2        | 2.6%    |
| Intel X99             | 2        | 2.6%    |
| Gigabyte 970A-DS3P    | 2        | 2.6%    |
| Dell OptiPlex         | 2        | 2.6%    |
| MSI MS-7E07           | 1        | 1.3%    |
| MSI MS-7C89           | 1        | 1.3%    |
| MSI MS-7C56           | 1        | 1.3%    |
| MSI MS-7B79           | 1        | 1.3%    |
| MSI MS-7B09           | 1        | 1.3%    |
| MSI MS-7A69           | 1        | 1.3%    |
| MSI MS-7A15           | 1        | 1.3%    |
| MSI MS-7982           | 1        | 1.3%    |
| MSI MS-7850           | 1        | 1.3%    |
| MSI MS-7693           | 1        | 1.3%    |
| MACHINIST X99-MR9D    | 1        | 1.3%    |
| Intel DX58SO2         | 1        | 1.3%    |
| HP Compaq             | 1        | 1.3%    |
| HP 550-a114           | 1        | 1.3%    |
| HP 280                | 1        | 1.3%    |
| Gigabyte Z77X-UD3H    | 1        | 1.3%    |
| Gigabyte X399         | 1        | 1.3%    |
| Gigabyte P55-USB3     | 1        | 1.3%    |
| Gigabyte HA65M-D2H-B3 | 1        | 1.3%    |
| Gigabyte H61MA-D3V    | 1        | 1.3%    |
| Gigabyte H61M-S2PV    | 1        | 1.3%    |
| Gigabyte H410M        | 1        | 1.3%    |
| Gigabyte B550M        | 1        | 1.3%    |
| Gigabyte B450         | 1        | 1.3%    |
| Gigabyte AB350M-DS3H  | 1        | 1.3%    |
| Gigabyte 990FXA-UD5   | 1        | 1.3%    |
| Gigabyte 990FXA-UD3   | 1        | 1.3%    |
| Dell Inspiron         | 1        | 1.3%    |
| Biostar G31D-M7       | 1        | 1.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 12       | 15.58%  |
| 2020 | 11       | 14.29%  |
| 2018 | 10       | 12.99%  |
| 2017 | 9        | 11.69%  |
| 2012 | 8        | 10.39%  |
| 2022 | 5        | 6.49%   |
| 2013 | 5        | 6.49%   |
| 2015 | 4        | 5.19%   |
| 2016 | 3        | 3.9%    |
| 2014 | 3        | 3.9%    |
| 2011 | 2        | 2.6%    |
| 2010 | 2        | 2.6%    |
| 2008 | 2        | 2.6%    |
| 2021 | 1        | 1.3%    |

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
| Disabled | 77       | 100%    |

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
| 16.01-24.0  | 32       | 41.03%  |
| 8.01-16.0   | 21       | 26.92%  |
| 32.01-64.0  | 11       | 14.1%   |
| 64.01-256.0 | 7        | 8.97%   |
| 3.01-4.0    | 4        | 5.13%   |
| 4.01-8.0    | 1        | 1.28%   |
| 24.01-32.0  | 1        | 1.28%   |
| 1.01-2.0    | 1        | 1.28%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 22       | 25.88%  |
| 2.01-3.0   | 18       | 21.18%  |
| 3.01-4.0   | 16       | 18.82%  |
| 1.01-2.0   | 16       | 18.82%  |
| 8.01-16.0  | 6        | 7.06%   |
| 0.51-1.0   | 3        | 3.53%   |
| 16.01-24.0 | 2        | 2.35%   |
| 0.01-0.5   | 2        | 2.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 32       | 40%     |
| 3      | 21       | 26.25%  |
| 1      | 14       | 17.5%   |
| 4      | 6        | 7.5%    |
| 6      | 4        | 5%      |
| 8      | 2        | 2.5%    |
| 7      | 1        | 1.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 61       | 79.22%  |
| Yes       | 16       | 20.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 75       | 97.4%   |
| No        | 2        | 2.6%    |

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
| No        | 44       | 57.14%  |
| Yes       | 33       | 42.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 13       | 16.67%  |
| Russia      | 11       | 14.1%   |
| Germany     | 10       | 12.82%  |
| France      | 7        | 8.97%   |
| Brazil      | 4        | 5.13%   |
| Switzerland | 3        | 3.85%   |
| Poland      | 3        | 3.85%   |
| Greece      | 3        | 3.85%   |
| UK          | 2        | 2.56%   |
| Turkey      | 2        | 2.56%   |
| Finland     | 2        | 2.56%   |
| Canada      | 2        | 2.56%   |
| Bulgaria    | 2        | 2.56%   |
| Ukraine     | 1        | 1.28%   |
| Slovenia    | 1        | 1.28%   |
| Netherlands | 1        | 1.28%   |
| Mexico      | 1        | 1.28%   |
| Lithuania   | 1        | 1.28%   |
| Japan       | 1        | 1.28%   |
| Italy       | 1        | 1.28%   |
| Iran        | 1        | 1.28%   |
| India       | 1        | 1.28%   |
| Hong Kong   | 1        | 1.28%   |
| Guatemala   | 1        | 1.28%   |
| Austria     | 1        | 1.28%   |
| Australia   | 1        | 1.28%   |
| Argentina   | 1        | 1.28%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Paris                  | 3        | 3.7%    |
| St Petersburg          | 2        | 2.47%   |
| Moscow                 | 2        | 2.47%   |
| Helsinki               | 2        | 2.47%   |
| Frankfurt am Main      | 2        | 2.47%   |
| Charlotte              | 2        | 2.47%   |
| Bern                   | 2        | 2.47%   |
| Athens                 | 2        | 2.47%   |
| Wettringen             | 1        | 1.23%   |
| Vladivostok            | 1        | 1.23%   |
| Vilnius                | 1        | 1.23%   |
| Vienna                 | 1        | 1.23%   |
| Vancouver              | 1        | 1.23%   |
| Upper Norwood          | 1        | 1.23%   |
| Ufa                    | 1        | 1.23%   |
| Toronto                | 1        | 1.23%   |
| Thessaloniki           | 1        | 1.23%   |
| Tehran                 | 1        | 1.23%   |
| Sydney                 | 1        | 1.23%   |
| Surat                  | 1        | 1.23%   |
| Stein                  | 1        | 1.23%   |
| Stavropol              | 1        | 1.23%   |
| Statesboro             | 1        | 1.23%   |
| Sofia                  | 1        | 1.23%   |
| Snohomish              | 1        | 1.23%   |
| Shishkin Les           | 1        | 1.23%   |
| Shavertown             | 1        | 1.23%   |
| Saratov                | 1        | 1.23%   |
| Sao Paulo              | 1        | 1.23%   |
| San Miguel de Tucumán | 1        | 1.23%   |
| Rotherham              | 1        | 1.23%   |
| Rosmalen               | 1        | 1.23%   |
| Riverview              | 1        | 1.23%   |
| Rexburg                | 1        | 1.23%   |
| Plovdiv                | 1        | 1.23%   |
| Munich                 | 1        | 1.23%   |
| Maua                   | 1        | 1.23%   |
| Maebashi               | 1        | 1.23%   |
| Maceió                | 1        | 1.23%   |
| Lublin                 | 1        | 1.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 32       | 57     | 18.39%  |
| Seagate                     | 25       | 34     | 14.37%  |
| Samsung Electronics         | 25       | 36     | 14.37%  |
| Kingston                    | 14       | 15     | 8.05%   |
| Crucial                     | 12       | 18     | 6.9%    |
| Toshiba                     | 11       | 12     | 6.32%   |
| SanDisk                     | 7        | 10     | 4.02%   |
| Intel                       | 4        | 7      | 2.3%    |
| Phison Electronics          | 3        | 6      | 1.72%   |
| Hitachi                     | 3        | 3      | 1.72%   |
| A-DATA Technology           | 3        | 3      | 1.72%   |
| SK hynix                    | 2        | 2      | 1.15%   |
| Maxtor                      | 2        | 2      | 1.15%   |
| JMicron Technology          | 2        | 2      | 1.15%   |
| HGST                        | 2        | 3      | 1.15%   |
| Corsair                     | 2        | 2      | 1.15%   |
| China                       | 2        | 3      | 1.15%   |
| AMD                         | 2        | 2      | 1.15%   |
| XUM                         | 1        | 1      | 0.57%   |
| USB3.0                      | 1        | 1      | 0.57%   |
| Unknown                     | 1        | 1      | 0.57%   |
| TS512GMT                    | 1        | 5      | 0.57%   |
| Transcend                   | 1        | 1      | 0.57%   |
| SPCC Sol                    | 1        | 1      | 0.57%   |
| SPCC                        | 1        | 1      | 0.57%   |
| Silicon Motion              | 1        | 1      | 0.57%   |
| PNY                         | 1        | 1      | 0.57%   |
| Plextor                     | 1        | 1      | 0.57%   |
| Phison                      | 1        | 1      | 0.57%   |
| Netac                       | 1        | 1      | 0.57%   |
| MAXIO Technology (Hangzhou) | 1        | 3      | 0.57%   |
| Linux                       | 1        | 1      | 0.57%   |
| KingSpec                    | 1        | 1      | 0.57%   |
| Hewlett-Packard             | 1        | 1      | 0.57%   |
| GOODRAM                     | 1        | 1      | 0.57%   |
| Biostar                     | 1        | 1      | 0.57%   |
| Apacer                      | 1        | 1      | 0.57%   |
| ADATA Technology            | 1        | 1      | 0.57%   |
| Unknown                     | 1        | 3      | 0.57%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 6        | 3.02%   |
| Toshiba DT01ACA100 1TB                            | 5        | 2.51%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 3        | 1.51%   |
| Seagate ST3500418AS 500GB                         | 3        | 1.51%   |
| Seagate ST1000DM010-2EP102 1TB                    | 3        | 1.51%   |
| Samsung SSD 860 EVO 250GB                         | 3        | 1.51%   |
| Crucial CT240BX500SSD1 240GB                      | 3        | 1.51%   |
| Crucial CT1000MX500SSD1 1TB                       | 3        | 1.51%   |
| WDC WD80EZAZ-11TDBA0 8TB                          | 2        | 1.01%   |
| WDC WD40EZRZ-00WN9B0 4TB                          | 2        | 1.01%   |
| WDC WD20EZBX-00AYRA0 2TB                          | 2        | 1.01%   |
| WDC WD10EZEX-22MFCA0 1TB                          | 2        | 1.01%   |
| WDC WD100EMAZ-00WJTA0 10TB                        | 2        | 1.01%   |
| Toshiba DT01ACA050 500GB                          | 2        | 1.01%   |
| Seagate ST500DM002-1BD142 500GB                   | 2        | 1.01%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 2        | 1.01%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB              | 2        | 1.01%   |
| Samsung SSD 970 EVO 1TB                           | 2        | 1.01%   |
| Samsung SSD 840 EVO 250GB                         | 2        | 1.01%   |
| Phison PS5013 E13 NVMe Controller 256GB           | 2        | 1.01%   |
| Kingston SV300S37A240G 240GB SSD                  | 2        | 1.01%   |
| Kingston SA400S37480G 480GB SSD                   | 2        | 1.01%   |
| Kingston SA400S37120G 120GB SSD                   | 2        | 1.01%   |
| Crucial CT250MX500SSD1 250GB                      | 2        | 1.01%   |
| AMD R5SL240G 240GB SSD                            | 2        | 1.01%   |
| A-DATA SU650 240GB SSD                            | 2        | 1.01%   |
| XUM HX256GSSDSATA3 256GB                          | 1        | 0.5%    |
| WDC WDS500G2B0C-00PXH0 500GB                      | 1        | 0.5%    |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 1        | 0.5%    |
| WDC WDS256G1X0C-00ENX0 256GB                      | 1        | 0.5%    |
| WDC WDS100T2B0C-00PXH0 1TB                        | 1        | 0.5%    |
| WDC WDS100T2B0A-00SM50 1TB SSD                    | 1        | 0.5%    |
| WDC WDBNCE5000PNC 500GB SSD                       | 1        | 0.5%    |
| WDC WD80EFBX-68AZZN0 8TB                          | 1        | 0.5%    |
| WDC WD6001FZWX-00A2VA0 6TB                        | 1        | 0.5%    |
| WDC WD5003ABYX-18WERA0 500GB                      | 1        | 0.5%    |
| WDC WD5000LPVX-00V0TT0 500GB                      | 1        | 0.5%    |
| WDC WD5000LPLX-75ZNTT0 500GB                      | 1        | 0.5%    |
| WDC WD5000AVCS-632DY1 500GB                       | 1        | 0.5%    |
| WDC WD5000AAKX-60U6AA0 500GB                      | 1        | 0.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 29       | 49     | 38.16%  |
| Seagate             | 25       | 34     | 32.89%  |
| Toshiba             | 11       | 12     | 14.47%  |
| Hitachi             | 3        | 3      | 3.95%   |
| Maxtor              | 2        | 2      | 2.63%   |
| JMicron Technology  | 2        | 2      | 2.63%   |
| HGST                | 2        | 3      | 2.63%   |
| Unknown             | 1        | 1      | 1.32%   |
| Samsung Electronics | 1        | 1      | 1.32%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 13       | 17     | 20.31%  |
| Kingston            | 12       | 13     | 18.75%  |
| Crucial             | 12       | 18     | 18.75%  |
| WDC                 | 3        | 5      | 4.69%   |
| SanDisk             | 3        | 3      | 4.69%   |
| A-DATA Technology   | 3        | 3      | 4.69%   |
| Intel               | 2        | 3      | 3.13%   |
| China               | 2        | 3      | 3.13%   |
| AMD                 | 2        | 2      | 3.13%   |
| XUM                 | 1        | 1      | 1.56%   |
| USB3.0              | 1        | 1      | 1.56%   |
| SPCC Sol            | 1        | 1      | 1.56%   |
| SPCC                | 1        | 1      | 1.56%   |
| SK hynix            | 1        | 1      | 1.56%   |
| Plextor             | 1        | 1      | 1.56%   |
| Netac               | 1        | 1      | 1.56%   |
| Linux               | 1        | 1      | 1.56%   |
| KingSpec            | 1        | 1      | 1.56%   |
| GOODRAM             | 1        | 1      | 1.56%   |
| Biostar             | 1        | 1      | 1.56%   |
| Apacer              | 1        | 1      | 1.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 59       | 107    | 40.14%  |
| SSD     | 53       | 79     | 36.05%  |
| NVMe    | 33       | 52     | 22.45%  |
| Unknown | 2        | 8      | 1.36%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 72       | 179    | 63.16%  |
| NVMe | 33       | 52     | 28.95%  |
| SAS  | 9        | 15     | 7.89%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 57       | 90     | 45.97%  |
| 0.51-1.0   | 36       | 55     | 29.03%  |
| 1.01-2.0   | 15       | 16     | 12.1%   |
| 4.01-10.0  | 7        | 14     | 5.65%   |
| 3.01-4.0   | 5        | 7      | 4.03%   |
| 2.01-3.0   | 4        | 4      | 3.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 17       | 21.52%  |
| More than 3000 | 14       | 17.72%  |
| 2001-3000      | 13       | 16.46%  |
| 101-250        | 12       | 15.19%  |
| 501-1000       | 11       | 13.92%  |
| 251-500        | 9        | 11.39%  |
| 51-100         | 2        | 2.53%   |
| Unknown        | 1        | 1.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 15       | 18.75%  |
| 251-500        | 12       | 15%     |
| 1001-2000      | 11       | 13.75%  |
| 101-250        | 10       | 12.5%   |
| 1-20           | 9        | 11.25%  |
| More than 3000 | 8        | 10%     |
| 21-50          | 5        | 6.25%   |
| 51-100         | 5        | 6.25%   |
| 2001-3000      | 4        | 5%      |
| Unknown        | 1        | 1.25%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD5000AVCS-632DY1 500GB       | 1        | 1      | 5.88%   |
| WDC WD3200AAKX-00ERMA0 320GB      | 1        | 1      | 5.88%   |
| WDC WD30EZRX-00DC0B0 3TB          | 1        | 1      | 5.88%   |
| Toshiba MK7575GSX 752GB           | 1        | 1      | 5.88%   |
| Toshiba DT01ACA100 1TB            | 1        | 1      | 5.88%   |
| Seagate ST8000DM004-2CX188 8TB    | 1        | 1      | 5.88%   |
| Seagate ST6000VN0033-2EE110 6TB   | 1        | 1      | 5.88%   |
| Seagate ST2000DX002-2DV164 2TB    | 1        | 1      | 5.88%   |
| Seagate ST2000DM006-2DM164 2TB    | 1        | 1      | 5.88%   |
| Maxtor 6Y080M0 82GB               | 1        | 1      | 5.88%   |
| Kingston SUV400S37240G 240GB SSD  | 1        | 1      | 5.88%   |
| Kingston SA400S37120G 120GB SSD   | 1        | 1      | 5.88%   |
| Intel SSDSC2BW480A4 480GB         | 1        | 2      | 5.88%   |
| Intel SSDPEKKW128G7 128GB         | 1        | 1      | 5.88%   |
| HGST HTS541010A9E680 1TB          | 1        | 1      | 5.88%   |
| Hewlett-Packard SSD EX900 250GB   | 1        | 1      | 5.88%   |
| A-DATA Technology SU650 240GB SSD | 1        | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| Seagate           | 4        | 4      | 23.53%  |
| WDC               | 3        | 3      | 17.65%  |
| Toshiba           | 2        | 2      | 11.76%  |
| Kingston          | 2        | 2      | 11.76%  |
| Intel             | 2        | 3      | 11.76%  |
| Maxtor            | 1        | 1      | 5.88%   |
| HGST              | 1        | 1      | 5.88%   |
| Hewlett-Packard   | 1        | 1      | 5.88%   |
| A-DATA Technology | 1        | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 4      | 36.36%  |
| WDC     | 3        | 3      | 27.27%  |
| Toshiba | 2        | 2      | 18.18%  |
| Maxtor  | 1        | 1      | 9.09%   |
| HGST    | 1        | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 10       | 11     | 62.5%   |
| SSD  | 4        | 5      | 25%     |
| NVMe | 2        | 2      | 12.5%   |

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
| Works    | 46       | 126    | 47.42%  |
| Detected | 35       | 101    | 36.08%  |
| Malfunc  | 15       | 18     | 15.46%  |
| Fixed    | 1        | 1      | 1.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| AMD                         | 43       | 34.68%  |
| Intel                       | 34       | 27.42%  |
| Samsung Electronics         | 14       | 11.29%  |
| SanDisk                     | 6        | 4.84%   |
| Phison Electronics          | 6        | 4.84%   |
| ASMedia Technology          | 6        | 4.84%   |
| Marvell Technology Group    | 5        | 4.03%   |
| Silicon Motion              | 3        | 2.42%   |
| Kingston Technology Company | 2        | 1.61%   |
| SK hynix                    | 1        | 0.81%   |
| MAXIO Technology (Hangzhou) | 1        | 0.81%   |
| JMicron Technology          | 1        | 0.81%   |
| Broadcom / LSI              | 1        | 0.81%   |
| ADATA Technology            | 1        | 0.81%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 30       | 19.74%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 12       | 7.89%   |
| AMD 400 Series Chipset SATA Controller                                         | 9        | 5.92%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 6        | 3.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 6        | 3.95%   |
| AMD 300 Series Chipset SATA Controller                                         | 6        | 3.95%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4        | 2.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4        | 2.63%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4        | 2.63%   |
| AMD 500 Series Chipset SATA Controller                                         | 4        | 2.63%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 3        | 1.97%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 3        | 1.97%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3        | 1.97%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3        | 1.97%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 2        | 1.32%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 2        | 1.32%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2        | 1.32%   |
| Phison E12 NVMe Controller                                                     | 2        | 1.32%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2        | 1.32%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2        | 1.32%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2        | 1.32%   |
| AMD X399 Series Chipset SATA Controller                                        | 2        | 1.32%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2        | 1.32%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 1        | 0.66%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1        | 0.66%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 1        | 0.66%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1        | 0.66%   |
| SanDisk WD Black NVMe SSD                                                      | 1        | 0.66%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 1        | 0.66%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 0.66%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 1        | 0.66%   |
| Phison E18 PCIe4 NVMe Controller                                               | 1        | 0.66%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 1        | 0.66%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                          | 1        | 0.66%   |
| Marvell Group 88SE912x IDE Controller                                          | 1        | 0.66%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                           | 1        | 0.66%   |
| Kingston Company NV1 NVMe SSD SM2263XT (DRAM-less)                             | 1        | 0.66%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 1        | 0.66%   |
| JMicron JMB363 SATA/IDE Controller                                             | 1        | 0.66%   |
| Intel SSD 660P Series                                                          | 1        | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 73       | 62.39%  |
| NVMe | 33       | 28.21%  |
| IDE  | 9        | 7.69%   |
| RAID | 1        | 0.85%   |
| SAS  | 1        | 0.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 44       | 57.14%  |
| Intel  | 33       | 42.86%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD FX-8350 Eight-Core Processor                | 5        | 6.49%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 4        | 5.19%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 3        | 3.9%    |
| AMD Ryzen 7 5700G with Radeon Graphics          | 3        | 3.9%    |
| AMD Ryzen 7 2700X Eight-Core Processor          | 3        | 3.9%    |
| AMD Ryzen 5 2600X Six-Core Processor            | 3        | 3.9%    |
| Intel Core i7-9700K CPU @ 3.60GHz               | 2        | 2.6%    |
| Intel Core i5-6600K CPU @ 3.50GHz               | 2        | 2.6%    |
| Intel Core i5-3330 CPU @ 3.00GHz                | 2        | 2.6%    |
| Intel Core i5-2500 CPU @ 3.30GHz                | 2        | 2.6%    |
| Intel Core i5-10400F CPU @ 2.90GHz              | 2        | 2.6%    |
| AMD Ryzen 5 5600X 6-Core Processor              | 2        | 2.6%    |
| AMD Ryzen 5 3600 6-Core Processor               | 2        | 2.6%    |
| AMD Ryzen 5 1600 Six-Core Processor             | 2        | 2.6%    |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz             | 1        | 1.3%    |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz             | 1        | 1.3%    |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz             | 1        | 1.3%    |
| Intel Pentium CPU G4560 @ 3.50GHz               | 1        | 1.3%    |
| Intel Core i7-9700F CPU @ 3.00GHz               | 1        | 1.3%    |
| Intel Core i7-4790K CPU @ 4.00GHz               | 1        | 1.3%    |
| Intel Core i7 CPU 970 @ 3.20GHz                 | 1        | 1.3%    |
| Intel Core i5-9600K CPU @ 3.70GHz               | 1        | 1.3%    |
| Intel Core i5-8500 CPU @ 3.00GHz                | 1        | 1.3%    |
| Intel Core i5-7600K CPU @ 3.80GHz               | 1        | 1.3%    |
| Intel Core i5-6400 CPU @ 2.70GHz                | 1        | 1.3%    |
| Intel Core i5-4670K CPU @ 3.40GHz               | 1        | 1.3%    |
| Intel Core i5-3470 CPU @ 3.20GHz                | 1        | 1.3%    |
| Intel Core i5-2310 CPU @ 2.90GHz                | 1        | 1.3%    |
| Intel Core i5-10500T CPU @ 2.30GHz              | 1        | 1.3%    |
| Intel Core i5 CPU 660 @ 3.33GHz                 | 1        | 1.3%    |
| Intel Core i3-2120 CPU @ 3.30GHz                | 1        | 1.3%    |
| Intel Core i3-10100 CPU @ 3.60GHz               | 1        | 1.3%    |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz            | 1        | 1.3%    |
| Intel Core 2 Duo CPU E4600 @ 2.40GHz            | 1        | 1.3%    |
| Intel Celeron CPU G1840 @ 2.80GHz               | 1        | 1.3%    |
| Intel 12th Gen Core i9-12900K                   | 1        | 1.3%    |
| Intel 12th Gen Core i5-12600K                   | 1        | 1.3%    |
| AMD Ryzen Threadripper 2990WX 32-Core Processor | 1        | 1.3%    |
| AMD Ryzen Threadripper 1900X 8-Core Processor   | 1        | 1.3%    |
| AMD Ryzen 9 3900XT 12-Core Processor            | 1        | 1.3%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 17       | 22.08%  |
| AMD Ryzen 7            | 13       | 16.88%  |
| AMD Ryzen 5            | 12       | 15.58%  |
| AMD FX                 | 6        | 7.79%   |
| Intel Core i7          | 5        | 6.49%   |
| AMD Ryzen 9            | 4        | 5.19%   |
| Intel Xeon             | 3        | 3.9%    |
| Other                  | 2        | 2.6%    |
| Intel Core i3          | 2        | 2.6%    |
| Intel Core 2 Duo       | 2        | 2.6%    |
| AMD Ryzen Threadripper | 2        | 2.6%    |
| AMD A10                | 2        | 2.6%    |
| Intel Pentium          | 1        | 1.3%    |
| Intel Celeron          | 1        | 1.3%    |
| AMD Ryzen 3            | 1        | 1.3%    |
| AMD Phenom II X4       | 1        | 1.3%    |
| AMD Athlon             | 1        | 1.3%    |
| AMD A8                 | 1        | 1.3%    |
| AMD A6                 | 1        | 1.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 21       | 27.27%  |
| 6      | 18       | 23.38%  |
| 8      | 17       | 22.08%  |
| 2      | 9        | 11.69%  |
| 12     | 4        | 5.19%   |
| 10     | 2        | 2.6%    |
| 3      | 2        | 2.6%    |
| 32     | 1        | 1.3%    |
| 16     | 1        | 1.3%    |
| 14     | 1        | 1.3%    |
| 1      | 1        | 1.3%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 77       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 55       | 71.43%  |
| 1      | 22       | 28.57%  |

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
| Unknown    | 28       | 35%     |
| 0x0800820d | 6        | 7.5%    |
| 0x08701021 | 5        | 6.25%   |
| 0x08701013 | 5        | 6.25%   |
| 0x906ed    | 3        | 3.75%   |
| 0x206a7    | 3        | 3.75%   |
| 0x06000822 | 3        | 3.75%   |
| 0xa0655    | 2        | 2.5%    |
| 0x506e3    | 2        | 2.5%    |
| 0x306c3    | 2        | 2.5%    |
| 0x0a201016 | 2        | 2.5%    |
| 0x06003106 | 2        | 2.5%    |
| 0x06000852 | 2        | 2.5%    |
| 0xa0653    | 1        | 1.25%   |
| 0x906e9    | 1        | 1.25%   |
| 0x6fd      | 1        | 1.25%   |
| 0x306a9    | 1        | 1.25%   |
| 0x206c2    | 1        | 1.25%   |
| 0x20652    | 1        | 1.25%   |
| 0x1067a    | 1        | 1.25%   |
| 0x0a50000b | 1        | 1.25%   |
| 0x0a201009 | 1        | 1.25%   |
| 0x08108109 | 1        | 1.25%   |
| 0x0800820b | 1        | 1.25%   |
| 0x08001138 | 1        | 1.25%   |
| 0x08001137 | 1        | 1.25%   |
| 0x08001129 | 1        | 1.25%   |
| 0x07030105 | 1        | 1.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 12       | 15.58%  |
| Zen+             | 10       | 12.99%  |
| Zen 3            | 7        | 9.09%   |
| Piledriver       | 7        | 9.09%   |
| KabyLake         | 7        | 9.09%   |
| Haswell          | 5        | 6.49%   |
| Zen              | 4        | 5.19%   |
| SandyBridge      | 4        | 5.19%   |
| CometLake        | 4        | 5.19%   |
| Skylake          | 3        | 3.9%    |
| IvyBridge        | 3        | 3.9%    |
| Westmere         | 2        | 2.6%    |
| Steamroller      | 2        | 2.6%    |
| Alderlake Hybrid | 2        | 2.6%    |
| Puma             | 1        | 1.3%    |
| Penryn           | 1        | 1.3%    |
| K10              | 1        | 1.3%    |
| Core             | 1        | 1.3%    |
| Broadwell        | 1        | 1.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 44       | 53.66%  |
| Nvidia | 29       | 35.37%  |
| Intel  | 9        | 10.98%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 9        | 10.59%  |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 7        | 8.24%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3        | 3.53%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 3        | 3.53%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 2        | 2.35%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 2.35%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 2.35%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 2.35%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 2        | 2.35%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 2.35%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 2.35%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 2        | 2.35%   |
| AMD Redwood XT [Radeon HD 5670/5690/5730]                                   | 2        | 2.35%   |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                    | 2        | 2.35%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2        | 2.35%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 2.35%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 2        | 2.35%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.18%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 1.18%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 1.18%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 1.18%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                          | 1        | 1.18%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.18%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.18%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 1.18%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.18%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.18%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 1.18%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 1.18%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.18%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                           | 1        | 1.18%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.18%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 1.18%   |
| Nvidia GA104 [GeForce RTX 3060]                                             | 1        | 1.18%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 1        | 1.18%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 1        | 1.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 1.18%   |
| Intel HD Graphics 610                                                       | 1        | 1.18%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.18%   |
| Intel AlderLake-S GT1                                                       | 1        | 1.18%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 39       | 50%     |
| 1 x Nvidia     | 26       | 33.33%  |
| 1 x Intel      | 7        | 8.97%   |
| 2 x AMD        | 3        | 3.85%   |
| AMD + Nvidia   | 2        | 2.56%   |
| Intel + Nvidia | 1        | 1.28%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 57       | 72.15%  |
| Proprietary | 22       | 27.85%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 28       | 34.15%  |
| 7.01-8.0   | 17       | 20.73%  |
| 3.01-4.0   | 11       | 13.41%  |
| 1.01-2.0   | 9        | 10.98%  |
| 8.01-16.0  | 7        | 8.54%   |
| 0.51-1.0   | 6        | 7.32%   |
| 5.01-6.0   | 2        | 2.44%   |
| 0.01-0.5   | 2        | 2.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 14       | 14%     |
| Goldstar             | 11       | 11%     |
| Acer                 | 11       | 11%     |
| Philips              | 9        | 9%      |
| ASUSTek Computer     | 8        | 8%      |
| AOC                  | 8        | 8%      |
| Dell                 | 6        | 6%      |
| BenQ                 | 5        | 5%      |
| Ancor Communications | 4        | 4%      |
| MSI                  | 2        | 2%      |
| ViewSonic            | 1        | 1%      |
| Vestel Elektronik    | 1        | 1%      |
| Unknown              | 1        | 1%      |
| Sony                 | 1        | 1%      |
| Packard Bell         | 1        | 1%      |
| LG Electronics       | 1        | 1%      |
| Lenovo Group Limited | 1        | 1%      |
| Lenovo               | 1        | 1%      |
| KTC                  | 1        | 1%      |
| Jean                 | 1        | 1%      |
| Iiyama               | 1        | 1%      |
| Idek Iiyama          | 1        | 1%      |
| HVR                  | 1        | 1%      |
| Hitachi              | 1        | 1%      |
| Hewlett-Packard      | 1        | 1%      |
| GAOMON               | 1        | 1%      |
| Envision Peripherals | 1        | 1%      |
| Eizo                 | 1        | 1%      |
| CTV                  | 1        | 1%      |
| Belinea              | 1        | 1%      |
| Beko                 | 1        | 1%      |
| Unknown              | 1        | 1%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| MSI MAG341CQ MSI1462 3440x1440 797x333mm 34.0-inch                      | 2        | 1.92%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                | 2        | 1.92%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 2        | 1.92%   |
| ASUSTek Computer VG24V AUS2420 1920x1080 521x293mm 23.5-inch            | 2        | 1.92%   |
| AOC F22 AOC2200 1920x1080 476x268mm 21.5-inch                           | 2        | 1.92%   |
| Ancor Communications ASUS PB277 ACI27B5 1920x1080 597x336mm 27.0-inch   | 2        | 1.92%   |
| ViewSonic LCD Monitor VX2452 Series 3840x1080                           | 1        | 0.96%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch    | 1        | 0.96%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch               | 1        | 0.96%   |
| Sony TV SNY7001 1920x1080                                               | 1        | 0.96%   |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch       | 1        | 0.96%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch       | 1        | 0.96%   |
| Samsung Electronics T24B301 SAM098E 1920x1080 521x293mm 23.5-inch       | 1        | 0.96%   |
| Samsung Electronics SyncMaster SAM047D 1360x768 410x230mm 18.5-inch     | 1        | 0.96%   |
| Samsung Electronics SMBX2450 SAM0721 1920x1080 531x299mm 24.0-inch      | 1        | 0.96%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1        | 0.96%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch       | 1        | 0.96%   |
| Samsung Electronics S24A31x SAM7114 1920x1080 527x296mm 23.8-inch       | 1        | 0.96%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 1        | 0.96%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 950x540mm 43.0-inch   | 1        | 0.96%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1872x1053mm 84.6-inch | 1        | 0.96%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch      | 1        | 0.96%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch       | 1        | 0.96%   |
| Samsung Electronics C27FG7x SAM0E41 1920x1080 598x337mm 27.0-inch       | 1        | 0.96%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch       | 1        | 0.96%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 1        | 0.96%   |
| Philips PHL 346E2C PHLC247 3440x1440 797x334mm 34.0-inch                | 1        | 0.96%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch                | 1        | 0.96%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch                 | 1        | 0.96%   |
| Philips PHL 245E1 PHLC20B 2560x1440 527x296mm 23.8-inch                 | 1        | 0.96%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 1        | 0.96%   |
| Philips PHL 223V5LH PHLC114 1920x1080 477x268mm 21.5-inch               | 1        | 0.96%   |
| Philips PHL 220V8 PHLC218 1920x1080 477x268mm 21.5-inch                 | 1        | 0.96%   |
| Philips 247ELH PHLC085 1920x1080 521x293mm 23.5-inch                    | 1        | 0.96%   |
| Philips 226VL PHLC081 1920x1080 480x268mm 21.6-inch                     | 1        | 0.96%   |
| Packard Bell Viseo203DX PKB0378 1600x900 432x240mm 19.5-inch            | 1        | 0.96%   |
| LG Electronics LCD Monitor 34UC89G                                      | 1        | 0.96%   |
| Lenovo L197 Wide LEN1152 1440x900 410x257mm 19.1-inch                   | 1        | 0.96%   |
| Lenovo Group Limited LCD Monitor LEN LI2323swA 4480x1080                | 1        | 0.96%   |
| KTC 24'TV KTC2400 1920x1080 516x323mm 24.0-inch                         | 1        | 0.96%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 43       | 44.33%  |
| 3840x2160 (4K)     | 17       | 17.53%  |
| 2560x1440 (QHD)    | 7        | 7.22%   |
| 1280x1024 (SXGA)   | 5        | 5.15%   |
| 3440x1440          | 4        | 4.12%   |
| 2560x1080          | 3        | 3.09%   |
| Unknown            | 3        | 3.09%   |
| 3840x1080          | 2        | 2.06%   |
| 1920x1200 (WUXGA)  | 2        | 2.06%   |
| 1360x768           | 2        | 2.06%   |
| 4480x1080          | 1        | 1.03%   |
| 3600x1080          | 1        | 1.03%   |
| 2288x1287          | 1        | 1.03%   |
| 2160x1200          | 1        | 1.03%   |
| 1680x1050 (WSXGA+) | 1        | 1.03%   |
| 1600x900 (HD+)     | 1        | 1.03%   |
| 1440x900 (WXGA+)   | 1        | 1.03%   |
| 1280x960           | 1        | 1.03%   |
| 1024x768 (XGA)     | 1        | 1.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 15       | 15.63%  |
| 23      | 15       | 15.63%  |
| 27      | 13       | 13.54%  |
| 21      | 11       | 11.46%  |
| 34      | 7        | 7.29%   |
| Unknown | 6        | 6.25%   |
| 31      | 5        | 5.21%   |
| 19      | 5        | 5.21%   |
| 84      | 4        | 4.17%   |
| 72      | 2        | 2.08%   |
| 32      | 2        | 2.08%   |
| 17      | 2        | 2.08%   |
| 15      | 2        | 2.08%   |
| 142     | 1        | 1.04%   |
| 52      | 1        | 1.04%   |
| 48      | 1        | 1.04%   |
| 25      | 1        | 1.04%   |
| 20      | 1        | 1.04%   |
| 18      | 1        | 1.04%   |
| 11      | 1        | 1.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 38       | 40.86%  |
| 401-500        | 14       | 15.05%  |
| 701-800        | 9        | 9.68%   |
| 601-700        | 8        | 8.6%    |
| 1501-2000      | 6        | 6.45%   |
| Unknown        | 6        | 6.45%   |
| 351-400        | 4        | 4.3%    |
| 301-350        | 4        | 4.3%    |
| 1001-1500      | 2        | 2.15%   |
| More than 2000 | 1        | 1.08%   |
| 201-300        | 1        | 1.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 61       | 70.11%  |
| 21/9    | 7        | 8.05%   |
| 5/4     | 6        | 6.9%    |
| 16/10   | 5        | 5.75%   |
| Unknown | 5        | 5.75%   |
| 4/3     | 1        | 1.15%   |
| 32/9    | 1        | 1.15%   |
| 1.00    | 1        | 1.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 38       | 40%     |
| 351-500        | 14       | 14.74%  |
| 301-350        | 13       | 13.68%  |
| More than 1000 | 8        | 8.42%   |
| 151-200        | 6        | 6.32%   |
| Unknown        | 6        | 6.32%   |
| 251-300        | 3        | 3.16%   |
| 141-150        | 3        | 3.16%   |
| 101-110        | 2        | 2.11%   |
| 51-60          | 1        | 1.05%   |
| 501-1000       | 1        | 1.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 47       | 52.81%  |
| 101-120 | 21       | 23.6%   |
| 121-160 | 8        | 8.99%   |
| Unknown | 6        | 6.74%   |
| 1-50    | 4        | 4.49%   |
| 161-240 | 3        | 3.37%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 56       | 70.89%  |
| 2     | 19       | 24.05%  |
| 3     | 3        | 3.8%    |
| 4     | 1        | 1.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 52       | 49.52%  |
| Intel                                 | 30       | 28.57%  |
| TP-Link                               | 4        | 3.81%   |
| Qualcomm Atheros                      | 4        | 3.81%   |
| Ralink Technology                     | 3        | 2.86%   |
| D-Link System                         | 3        | 2.86%   |
| Xiaomi                                | 1        | 0.95%   |
| Qualcomm Atheros Communications       | 1        | 0.95%   |
| Microsoft                             | 1        | 0.95%   |
| Google                                | 1        | 0.95%   |
| DisplayLink                           | 1        | 0.95%   |
| Broadcom                              | 1        | 0.95%   |
| ASIX Electronics                      | 1        | 0.95%   |
| Aquantia                              | 1        | 0.95%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.95%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 44       | 33.85%  |
| Intel I211 Gigabit Network Connection                                  | 10       | 7.69%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 4        | 3.08%   |
| Intel Ethernet Connection (2) I219-V                                   | 3        | 2.31%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 3        | 2.31%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 2        | 1.54%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                    | 2        | 1.54%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 2        | 1.54%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 2        | 1.54%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter               | 2        | 1.54%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2        | 1.54%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2        | 1.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2        | 1.54%   |
| Intel Wi-Fi 6 AX200                                                    | 2        | 1.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2        | 1.54%   |
| Intel 82574L Gigabit Network Connection                                | 2        | 1.54%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                        | 2        | 1.54%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1        | 0.77%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 1        | 0.77%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 1        | 0.77%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 1        | 0.77%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1        | 0.77%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 1        | 0.77%   |
| Realtek 802.11ac NIC                                                   | 1        | 0.77%   |
| Ralink RT5572 Wireless Adapter                                         | 1        | 0.77%   |
| Ralink RT5370 Wireless Adapter                                         | 1        | 0.77%   |
| Ralink MT7601U Wireless Adapter                                        | 1        | 0.77%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 1        | 0.77%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1        | 0.77%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1        | 0.77%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1        | 0.77%   |
| Qualcomm Atheros AR9271 802.11n                                        | 1        | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 1        | 0.77%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1        | 0.77%   |
| Microsoft Xbox Wireless Adapter for Windows                            | 1        | 0.77%   |
| Intel Wireless 8265 / 8275                                             | 1        | 0.77%   |
| Intel Wireless 8260                                                    | 1        | 0.77%   |
| Intel Wireless 7265                                                    | 1        | 0.77%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 1        | 0.77%   |
| Intel I210 Gigabit Network Connection                                  | 1        | 0.77%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 16       | 41.03%  |
| Realtek Semiconductor                 | 9        | 23.08%  |
| TP-Link                               | 4        | 10.26%  |
| Ralink Technology                     | 3        | 7.69%   |
| Qualcomm Atheros                      | 2        | 5.13%   |
| Qualcomm Atheros Communications       | 1        | 2.56%   |
| Microsoft                             | 1        | 2.56%   |
| D-Link System                         | 1        | 2.56%   |
| Broadcom                              | 1        | 2.56%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 2.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                               | Desktops | Percent |
|-----------------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                                           | 4        | 10%     |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                                    | 3        | 7.5%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                         | 2        | 5%      |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                                 | 2        | 5%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                                     | 2        | 5%      |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                            | 2        | 5%      |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                            | 2        | 5%      |
| Intel Wi-Fi 6 AX200                                                                                 | 2        | 5%      |
| Intel Cannon Lake PCH CNVi WiFi                                                                     | 2        | 5%      |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                                     | 1        | 2.5%    |
| Realtek RTL8188EE Wireless Network Adapter                                                          | 1        | 2.5%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                             | 1        | 2.5%    |
| Realtek 802.11ac NIC                                                                                | 1        | 2.5%    |
| Ralink RT5572 Wireless Adapter                                                                      | 1        | 2.5%    |
| Ralink RT5370 Wireless Adapter                                                                      | 1        | 2.5%    |
| Ralink MT7601U Wireless Adapter                                                                     | 1        | 2.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                          | 1        | 2.5%    |
| Qualcomm Atheros AR9271 802.11n                                                                     | 1        | 2.5%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                                    | 1        | 2.5%    |
| Microsoft Xbox Wireless Adapter for Windows                                                         | 1        | 2.5%    |
| Intel Wireless 8265 / 8275                                                                          | 1        | 2.5%    |
| Intel Wireless 8260                                                                                 | 1        | 2.5%    |
| Intel Wireless 7265                                                                                 | 1        | 2.5%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                                             | 1        | 2.5%    |
| Intel Comet Lake PCH CNVi WiFi                                                                      | 1        | 2.5%    |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A2) [Atheros AR9170+AR9104]         | 1        | 2.5%    |
| Broadcom BCM43142 802.11b/g/n                                                                       | 1        | 2.5%    |
| 802.11g Adapter [Linksys WUSB54GC v3] WUSB100 v2 RangePlus Wireless Network Adapter [Ralink RT3070] | 1        | 2.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 49       | 58.33%  |
| Intel                 | 24       | 28.57%  |
| Qualcomm Atheros      | 4        | 4.76%   |
| D-Link System         | 2        | 2.38%   |
| Xiaomi                | 1        | 1.19%   |
| Google                | 1        | 1.19%   |
| DisplayLink           | 1        | 1.19%   |
| ASIX Electronics      | 1        | 1.19%   |
| Aquantia              | 1        | 1.19%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 44       | 48.89%  |
| Intel I211 Gigabit Network Connection                                          | 10       | 11.11%  |
| Intel Ethernet Connection (2) I219-V                                           | 3        | 3.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2        | 2.22%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2        | 2.22%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2        | 2.22%   |
| Intel 82574L Gigabit Network Connection                                        | 2        | 2.22%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                                | 2        | 2.22%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1        | 1.11%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1        | 1.11%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1        | 1.11%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1        | 1.11%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1        | 1.11%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1        | 1.11%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1        | 1.11%   |
| Intel I210 Gigabit Network Connection                                          | 1        | 1.11%   |
| Intel Ethernet Controller I225-V                                               | 1        | 1.11%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                  | 1        | 1.11%   |
| Intel Ethernet Connection I219-LM                                              | 1        | 1.11%   |
| Intel Ethernet Connection (7) I219-V                                           | 1        | 1.11%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1        | 1.11%   |
| Intel Ethernet Connection (17) I219-V                                          | 1        | 1.11%   |
| Intel Ethernet Connection (12) I219-V                                          | 1        | 1.11%   |
| Intel Ethernet Connection (11) I219-LM                                         | 1        | 1.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 1        | 1.11%   |
| Intel 82567LF-2 Gigabit Network Connection                                     | 1        | 1.11%   |
| Intel 82562V-2 10/100 Network Connection                                       | 1        | 1.11%   |
| Google Nexus/Pixel Device (tether+ debug)                                      | 1        | 1.11%   |
| DisplayLink Kensington Dock (Composite Device)                                 | 1        | 1.11%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1        | 1.11%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 1        | 1.11%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 75       | 65.79%  |
| WiFi     | 39       | 34.21%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 55       | 72.37%  |
| WiFi     | 21       | 27.63%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 43       | 55.84%  |
| 2     | 28       | 36.36%  |
| 3     | 3        | 3.9%    |
| 4     | 2        | 2.6%    |
| 0     | 1        | 1.3%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 65       | 83.33%  |
| Yes  | 13       | 16.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 16       | 45.71%  |
| Cambridge Silicon Radio         | 7        | 20%     |
| IMC Networks                    | 4        | 11.43%  |
| ASUSTek Computer                | 3        | 8.57%   |
| Broadcom                        | 2        | 5.71%   |
| Qualcomm Atheros Communications | 1        | 2.86%   |
| HTC (High Tech Computer)        | 1        | 2.86%   |
| Dynex                           | 1        | 2.86%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 7        | 20%     |
| Intel AX210 Bluetooth                                                | 4        | 11.43%  |
| Intel Wireless-AC 3168 Bluetooth                                     | 3        | 8.57%   |
| Intel Bluetooth wireless interface                                   | 3        | 8.57%   |
| IMC Networks Bluetooth Radio                                         | 3        | 8.57%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 2        | 5.71%   |
| Intel AX200 Bluetooth                                                | 2        | 5.71%   |
| Qualcomm Atheros  Bluetooth Device                                   | 1        | 2.86%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 1        | 2.86%   |
| Intel AX201 Bluetooth                                                | 1        | 2.86%   |
| IMC Networks Bluetooth Device                                        | 1        | 2.86%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 2.86%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 1        | 2.86%   |
| Broadcom BCM43142A0 Bluetooth Device                                 | 1        | 2.86%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 1        | 2.86%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 1        | 2.86%   |
| ASUS Bluetooth Radio                                                 | 1        | 2.86%   |
| ASUS ASUS USB-BT500                                                  | 1        | 2.86%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD                                             | 57       | 37.5%   |
| Intel                                           | 32       | 21.05%  |
| Nvidia                                          | 28       | 18.42%  |
| C-Media Electronics                             | 10       | 6.58%   |
| Creative Labs                                   | 5        | 3.29%   |
| Logitech                                        | 3        | 1.97%   |
| Creative Technology                             | 2        | 1.32%   |
| TC Electronic                                   | 1        | 0.66%   |
| SteelSeries ApS                                 | 1        | 0.66%   |
| Shure                                           | 1        | 0.66%   |
| Realtek Semiconductor                           | 1        | 0.66%   |
| Razer USA                                       | 1        | 0.66%   |
| PreSonus Audio Electronics                      | 1        | 0.66%   |
| Native Instruments                              | 1        | 0.66%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.66%   |
| JMTek                                           | 1        | 0.66%   |
| Generalplus Technology                          | 1        | 0.66%   |
| Focusrite-Novation                              | 1        | 0.66%   |
| EVGA                                            | 1        | 0.66%   |
| Corsair                                         | 1        | 0.66%   |
| Blue Microphones                                | 1        | 0.66%   |
| AudioQuest                                      | 1        | 0.66%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 14       | 7.57%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 12       | 6.49%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 11       | 5.95%   |
| AMD Navi 10 HDMI Audio                                                     | 8        | 4.32%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7        | 3.78%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5        | 2.7%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 5        | 2.7%    |
| AMD Family 17h/19h HD Audio Controller                                     | 5        | 2.7%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 5        | 2.7%    |
| Nvidia GP104 High Definition Audio Controller                              | 4        | 2.16%   |
| Intel 200 Series PCH HD Audio                                              | 4        | 2.16%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4        | 2.16%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4        | 2.16%   |
| AMD FCH Azalia Controller                                                  | 4        | 2.16%   |
| Nvidia TU116 High Definition Audio Controller                              | 3        | 1.62%   |
| Nvidia TU104 HD Audio Controller                                           | 3        | 1.62%   |
| Intel Comet Lake PCH-V cAVS                                                | 3        | 1.62%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3        | 1.62%   |
| C-Media Electronics USB Audio Device                                       | 3        | 1.62%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 3        | 1.62%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 1.08%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 1.08%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 1.08%   |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 1.08%   |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 1.08%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 1.08%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2        | 1.08%   |
| Creative Labs CA0110 [Sound Blaster X-Fi Xtreme Audio]                     | 2        | 1.08%   |
| C-Media Electronics Blue Snowball                                          | 2        | 1.08%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 2        | 1.08%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 2        | 1.08%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 1.08%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 2        | 1.08%   |
| TC Electronic VoiceLive Play                                               | 1        | 0.54%   |
| SteelSeries ApS Arctis Pro Wireless                                        | 1        | 0.54%   |
| Shure MV7                                                                  | 1        | 0.54%   |
| Realtek Semiconductor Maono AU-PM401                                       | 1        | 0.54%   |
| Razer USA RZ19-0229 Gaming Microphone                                      | 1        | 0.54%   |
| PreSonus Audio Electronics AudioBox Go                                     | 1        | 0.54%   |
| Nvidia TU102 High Definition Audio Controller                              | 1        | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 15       | 20.83%  |
| Kingston            | 14       | 19.44%  |
| G.Skill             | 12       | 16.67%  |
| Unknown             | 6        | 8.33%   |
| SK hynix            | 5        | 6.94%   |
| Crucial             | 5        | 6.94%   |
| Samsung Electronics | 4        | 5.56%   |
| Patriot             | 4        | 5.56%   |
| A-DATA Technology   | 3        | 4.17%   |
| Transcend           | 1        | 1.39%   |
| Micron Technology   | 1        | 1.39%   |
| Golden Empire       | 1        | 1.39%   |
| AMD                 | 1        | 1.39%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s        | 3        | 3.95%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s       | 3        | 3.95%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                   | 2        | 2.63%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s         | 2        | 2.63%   |
| Kingston RAM 99U5474-026.A00LF 4GB DIMM DDR3 1333MT/s       | 2        | 2.63%   |
| G.Skill RAM F3-10666CL9-4GBNT 4GB DIMM DDR3 1600MT/s        | 2        | 2.63%   |
| Crucial RAM BLS16G4D30AESB.M16FE 16GB DIMM DDR4 3200MT/s    | 2        | 2.63%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s       | 2        | 2.63%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                        | 1        | 1.32%   |
| Unknown RAM Module 2048MB DIMM SDRAM                        | 1        | 1.32%   |
| Unknown RAM Module 2048MB DIMM 1328MT/s                     | 1        | 1.32%   |
| Unknown RAM 3600 C20 Series 32GB DIMM DDR4 3666MT/s         | 1        | 1.32%   |
| Transcend RAM JM2666HLB-16G 16GB DIMM DDR4 2667MT/s         | 1        | 1.32%   |
| SK hynix RAM HMA82GU7CJR8N-VK 16GB DIMM DDR4 2667MT/s       | 1        | 1.32%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s     | 1        | 1.32%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 1        | 1.32%   |
| SK hynix RAM HMA41GU6AFR8N-TF 8GB DIMM DDR4 2465MT/s        | 1        | 1.32%   |
| SK hynix RAM HMA41GR7MFR4N-TF 8GB DIMM DDR4 2667MT/s        | 1        | 1.32%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s         | 1        | 1.32%   |
| Samsung RAM M378B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s         | 1        | 1.32%   |
| Samsung RAM M323R2GA3BB0-CQKOL 16GB DIMM DDR5 4802MT/s      | 1        | 1.32%   |
| Samsung RAM M3 78T2863RZS-CF7 1GB DIMM DDR2 800MT/s         | 1        | 1.32%   |
| Patriot RAM PSD48G240082 8GB DIMM DDR4 2400MT/s             | 1        | 1.32%   |
| Patriot RAM PSD48G240081 8GB DIMM DDR4 2800MT/s             | 1        | 1.32%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s              | 1        | 1.32%   |
| Patriot RAM 3000 C16 Series 8GB DIMM DDR4 3200MT/s          | 1        | 1.32%   |
| Micron RAM 16ATF2G64HZ-2G6J1 16GB SODIMM DDR4 2667MT/s      | 1        | 1.32%   |
| Kingston RAM XJ69DF-MIE 8GB DIMM DDR4 2933MT/s              | 1        | 1.32%   |
| Kingston RAM MSI24D4U7S8MB-8 8GB DIMM DDR4 2400MT/s         | 1        | 1.32%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s           | 1        | 1.32%   |
| Kingston RAM KF3200C20S4/16G 16GB SODIMM DDR4 3200MT/s      | 1        | 1.32%   |
| Kingston RAM KF2666C16D4/8G 8GB DIMM DDR4 2667MT/s          | 1        | 1.32%   |
| Kingston RAM 99U5595-003.A00LF 2GB DIMM DDR3 1600MT/s       | 1        | 1.32%   |
| Kingston RAM 99U5584-014.A00LF 4GB DIMM DDR3 1600MT/s       | 1        | 1.32%   |
| Kingston RAM 99U5474-010.A00LF 2GB DIMM DDR3 1333MT/s       | 1        | 1.32%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s       | 1        | 1.32%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s       | 1        | 1.32%   |
| Kingston RAM 99P5474-033.A00LF 2GB DIMM DDR3 1600MT/s       | 1        | 1.32%   |
| Golden Empire RAM CL16-18-18 D4-3000 8GB DIMM DDR4 3000MT/s | 1        | 1.32%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s      | 1        | 1.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 40       | 63.49%  |
| DDR3    | 17       | 26.98%  |
| DDR5    | 2        | 3.17%   |
| Unknown | 2        | 3.17%   |
| SDRAM   | 1        | 1.59%   |
| DDR2    | 1        | 1.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 60       | 95.24%  |
| SODIMM | 3        | 4.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 30       | 44.78%  |
| 4096  | 15       | 22.39%  |
| 16384 | 12       | 17.91%  |
| 32768 | 5        | 7.46%   |
| 2048  | 4        | 5.97%   |
| 1024  | 1        | 1.49%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 11       | 16.18%  |
| 1600    | 11       | 16.18%  |
| 3600    | 7        | 10.29%  |
| 2667    | 6        | 8.82%   |
| 1333    | 5        | 7.35%   |
| 3733    | 4        | 5.88%   |
| 2933    | 3        | 4.41%   |
| 2400    | 3        | 4.41%   |
| 3666    | 2        | 2.94%   |
| 3533    | 2        | 2.94%   |
| 3000    | 2        | 2.94%   |
| 2133    | 2        | 2.94%   |
| 6000    | 1        | 1.47%   |
| 4802    | 1        | 1.47%   |
| 4133    | 1        | 1.47%   |
| 3400    | 1        | 1.47%   |
| 2800    | 1        | 1.47%   |
| 2481    | 1        | 1.47%   |
| 2465    | 1        | 1.47%   |
| 1328    | 1        | 1.47%   |
| 800     | 1        | 1.47%   |
| Unknown | 1        | 1.47%   |

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
| Ricoh SP 211SU                | 1        | 25%     |
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
| Logitech                      | 6        | 33.33%  |
| Microdia                      | 2        | 11.11%  |
| Creative Technology           | 2        | 11.11%  |
| WaveRider Communications      | 1        | 5.56%   |
| Sunplus Innovation Technology | 1        | 5.56%   |
| Microsoft                     | 1        | 5.56%   |
| KYE Systems (Mouse Systems)   | 1        | 5.56%   |
| Google                        | 1        | 5.56%   |
| GEMBIRD                       | 1        | 5.56%   |
| Cubeternet                    | 1        | 5.56%   |
| ARC International             | 1        | 5.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Logitech Webcam C270                           | 2        | 11.11%  |
| WaveRider USB 2.0 Camera                       | 1        | 5.56%   |
| Sunplus USB Camera                             | 1        | 5.56%   |
| Microsoft LifeCam Cinema                       | 1        | 5.56%   |
| Microdia Webcam Vitade AF                      | 1        | 5.56%   |
| Microdia USB 2.0 Camera                        | 1        | 5.56%   |
| Logitech Webcam C930e                          | 1        | 5.56%   |
| Logitech Webcam C310                           | 1        | 5.56%   |
| Logitech HD Webcam C910                        | 1        | 5.56%   |
| Logitech BRIO Ultra HD Webcam                  | 1        | 5.56%   |
| KYE Systems (Mouse Systems) Genius FaceCam 320 | 1        | 5.56%   |
| Google Nexus/Pixel Device (MTP + debug)        | 1        | 5.56%   |
| GEMBIRD USB2.0 PC CAMERA                       | 1        | 5.56%   |
| Cubeternet GL-UPC822 UVC WebCam                | 1        | 5.56%   |
| Creative Live! Cam Sync HD [VF0770]            | 1        | 5.56%   |
| Creative Live! Cam Chat HD [VF0700]            | 1        | 5.56%   |
| ARC International Camera                       | 1        | 5.56%   |

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
| 0     | 68       | 88.31%  |
| 1     | 7        | 9.09%   |
| 3     | 1        | 1.3%    |
| 2     | 1        | 1.3%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Unassigned class         | 2        | 22.22%  |
| Net/wireless             | 2        | 22.22%  |
| Communication controller | 2        | 22.22%  |
| Sound                    | 1        | 11.11%  |
| Net/ethernet             | 1        | 11.11%  |
| Graphics card            | 1        | 11.11%  |

