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

Total: 90

| Vendor    | Model                   | Probe                                                      | Date         |
|-----------|-------------------------|------------------------------------------------------------|--------------|
| MSI       | B350M PRO-VDH           | [a15fa484d4](https://linux-hardware.org/?probe=a15fa484d4) | Apr 26, 2023 |
| ASUSTek   | ROG STRIX B350-F GAMING | [18111d76fc](https://linux-hardware.org/?probe=18111d76fc) | Apr 17, 2023 |
| Intel     | X99H                    | [b91cbf41c0](https://linux-hardware.org/?probe=b91cbf41c0) | Apr 06, 2023 |
| ASRock    | Z690 Taichi             | [fbad15ab18](https://linux-hardware.org/?probe=fbad15ab18) | Mar 24, 2023 |
| ASRock    | Z690 Taichi             | [76159d5fc4](https://linux-hardware.org/?probe=76159d5fc4) | Mar 22, 2023 |
| ASUSTek   | F2A55-M LE              | [47c7f6e38d](https://linux-hardware.org/?probe=47c7f6e38d) | Mar 03, 2023 |
| ASUSTek   | TUF Gaming B550M-PLUS   | [7ad97f8b6d](https://linux-hardware.org/?probe=7ad97f8b6d) | Feb 09, 2023 |
| ASUSTek   | ROG STRIX Z370-G GAMING | [84fb689a7e](https://linux-hardware.org/?probe=84fb689a7e) | Feb 06, 2023 |
| ASUSTek   | ROG STRIX Z370-G GAMING | [405641895c](https://linux-hardware.org/?probe=405641895c) | Jan 18, 2023 |
| Gigabyte  | B450 AORUS PRO WIFI-CF  | [b79de349a9](https://linux-hardware.org/?probe=b79de349a9) | Jan 01, 2023 |
| Gigabyte  | X570 AORUS ELITE WIFI   | [f17f99d4e6](https://linux-hardware.org/?probe=f17f99d4e6) | Nov 30, 2022 |
| Gigabyte  | B550M AORUS PRO         | [d72c486584](https://linux-hardware.org/?probe=d72c486584) | Oct 22, 2022 |
| Gigabyte  | B450 AORUS PRO WIFI-CF  | [6cbb7cbc35](https://linux-hardware.org/?probe=6cbb7cbc35) | Oct 17, 2022 |
| Gigabyte  | B450 AORUS PRO WIFI-CF  | [ca934ff06b](https://linux-hardware.org/?probe=ca934ff06b) | Oct 16, 2022 |
| MSI       | H410M PRO-VH            | [f632032d8c](https://linux-hardware.org/?probe=f632032d8c) | Aug 13, 2022 |
| Gigabyte  | Z77X-UD3H               | [db843c1cae](https://linux-hardware.org/?probe=db843c1cae) | Aug 07, 2022 |
| Gigabyte  | AB350M-DS3H V2-CF       | [00d543ee46](https://linux-hardware.org/?probe=00d543ee46) | Jul 07, 2022 |
| Gigabyte  | H61MA-D3V               | [f07968d013](https://linux-hardware.org/?probe=f07968d013) | Jul 07, 2022 |
| ASRock    | B460 Phantom Gaming 4   | [a4054a2ac8](https://linux-hardware.org/?probe=a4054a2ac8) | Jun 10, 2022 |
| ASUSTek   | M5A97 LE R2.0           | [009ea9b40a](https://linux-hardware.org/?probe=009ea9b40a) | Jun 09, 2022 |
| MSI       | MPG X570 GAMING PLUS    | [0e42effbfb](https://linux-hardware.org/?probe=0e42effbfb) | May 17, 2022 |
| Gigabyte  | X570 AORUS ULTRA        | [ea492e2997](https://linux-hardware.org/?probe=ea492e2997) | May 13, 2022 |
| Gigabyte  | HA65M-D2H-B3            | [313e83e0ef](https://linux-hardware.org/?probe=313e83e0ef) | Mar 10, 2022 |
| ASUSTek   | PRIME B350M-A           | [299a727e8a](https://linux-hardware.org/?probe=299a727e8a) | Mar 02, 2022 |
| MSI       | B550-A PRO              | [b16ba2b14a](https://linux-hardware.org/?probe=b16ba2b14a) | Jan 31, 2022 |
| ASRock    | B150M Pro4S/D3          | [b7a65f897c](https://linux-hardware.org/?probe=b7a65f897c) | Jan 29, 2022 |
| MSI       | B350M PRO-VDH           | [29b6159e9c](https://linux-hardware.org/?probe=29b6159e9c) | Jan 12, 2022 |
| ASUSTek   | ROG STRIX X570-F GAMING | [ca93455055](https://linux-hardware.org/?probe=ca93455055) | Jan 07, 2022 |
| ASUSTek   | Pro WS X570-ACE         | [1a7ef57da7](https://linux-hardware.org/?probe=1a7ef57da7) | Jan 07, 2022 |
| ASRock    | B450 Steel Legend       | [44ccc8eb49](https://linux-hardware.org/?probe=44ccc8eb49) | Nov 24, 2021 |
| MSI       | B450 TOMAHAWK MAX       | [9fca12db52](https://linux-hardware.org/?probe=9fca12db52) | Nov 22, 2021 |
| HP        | 1495                    | [e7c0f59f92](https://linux-hardware.org/?probe=e7c0f59f92) | Oct 15, 2021 |
| ASUSTek   | ROG Maximus XI HERO     | [e2c619e8dd](https://linux-hardware.org/?probe=e2c619e8dd) | Oct 12, 2021 |
| ASUSTek   | ROG Maximus XI HERO     | [1e612081c8](https://linux-hardware.org/?probe=1e612081c8) | Oct 02, 2021 |
| MSI       | X470 GAMING PLUS        | [d5871d0e2a](https://linux-hardware.org/?probe=d5871d0e2a) | Aug 25, 2021 |
| MSI       | MPG X570 GAMING PLUS    | [ec331e992a](https://linux-hardware.org/?probe=ec331e992a) | Aug 08, 2021 |
| ASUSTek   | PRIME B450M-A           | [558e1369e9](https://linux-hardware.org/?probe=558e1369e9) | Jul 25, 2021 |
| ASUSTek   | P8H61-M LX3 R2.0        | [156577ba27](https://linux-hardware.org/?probe=156577ba27) | Jul 18, 2021 |
| ASRock    | H310CM-DVS              | [f8e9ea8ffa](https://linux-hardware.org/?probe=f8e9ea8ffa) | Jun 26, 2021 |
| MSI       | Z270M MORTAR            | [5c54607559](https://linux-hardware.org/?probe=5c54607559) | Jun 22, 2021 |
| ASUSTek   | ROG STRIX Z370-G GAMING | [181bd83bdd](https://linux-hardware.org/?probe=181bd83bdd) | Jun 02, 2021 |
| ASRock    | FM2A88X-ITX+            | [2b91e357ca](https://linux-hardware.org/?probe=2b91e357ca) | May 16, 2021 |
| ASRock    | FM2A88X-ITX+            | [057546c50e](https://linux-hardware.org/?probe=057546c50e) | Apr 30, 2021 |
| ASUSTek   | SABERTOOTH 990FX R2.0   | [d1cf148ec4](https://linux-hardware.org/?probe=d1cf148ec4) | Apr 24, 2021 |
| ASUSTek   | ROG STRIX Z370-G GAMING | [132c1a0515](https://linux-hardware.org/?probe=132c1a0515) | Apr 08, 2021 |
| ASUSTek   | ROG STRIX B550-F GAMING | [5527015fb6](https://linux-hardware.org/?probe=5527015fb6) | Apr 08, 2021 |
| ASUSTek   | ROG STRIX Z370-G GAMING | [10132d3ee3](https://linux-hardware.org/?probe=10132d3ee3) | Apr 05, 2021 |
| ASUSTek   | ROG STRIX Z370-G GAMING | [62f6aa5c03](https://linux-hardware.org/?probe=62f6aa5c03) | Mar 27, 2021 |
| ASUSTek   | PRIME X370-PRO          | [91a16f1c67](https://linux-hardware.org/?probe=91a16f1c67) | Feb 21, 2021 |
| MSI       | X470 GAMING PLUS        | [f93e302542](https://linux-hardware.org/?probe=f93e302542) | Feb 15, 2021 |
| Alienware | 02XRCM A01              | [554d3ebf2f](https://linux-hardware.org/?probe=554d3ebf2f) | Feb 14, 2021 |
| Gigabyte  | 970A-DS3P               | [b4c4d7f99c](https://linux-hardware.org/?probe=b4c4d7f99c) | Feb 01, 2021 |
| Gigabyte  | 970A-DS3P               | [70eabb568f](https://linux-hardware.org/?probe=70eabb568f) | Jan 30, 2021 |
| MSI       | X470 GAMING PLUS        | [fb3e2ec12b](https://linux-hardware.org/?probe=fb3e2ec12b) | Jan 24, 2021 |
| ASUSTek   | TUF B450-PLUS GAMING    | [fda5fabbf5](https://linux-hardware.org/?probe=fda5fabbf5) | Jan 21, 2021 |
| Dell      | 0K216C                  | [524206eff9](https://linux-hardware.org/?probe=524206eff9) | Jan 20, 2021 |
| Dell      | 0D9JG3 A00              | [6c44448201](https://linux-hardware.org/?probe=6c44448201) | Jan 19, 2021 |
| ASUSTek   | P8B75-M LX PLUS         | [c53595bd26](https://linux-hardware.org/?probe=c53595bd26) | Jan 16, 2021 |
| ASRock    | X570 Phantom Gaming 4   | [335ee823bd](https://linux-hardware.org/?probe=335ee823bd) | Jan 16, 2021 |
| ASUSTek   | G11CD                   | [145a13d355](https://linux-hardware.org/?probe=145a13d355) | Jan 07, 2021 |
| ASUSTek   | G11CD                   | [dc70a6fae2](https://linux-hardware.org/?probe=dc70a6fae2) | Jan 07, 2021 |
| HP        | 2B34                    | [e48dc00e0a](https://linux-hardware.org/?probe=e48dc00e0a) | Jan 04, 2021 |
| Pegatron  | 2AC2A                   | [6dbd029143](https://linux-hardware.org/?probe=6dbd029143) | Jan 03, 2021 |
| Pegatron  | 2AC2A                   | [7dd04be8aa](https://linux-hardware.org/?probe=7dd04be8aa) | Jan 01, 2021 |
| ASUSTek   | TUF Gaming X570-PLUS    | [3f9f87f288](https://linux-hardware.org/?probe=3f9f87f288) | Dec 31, 2020 |
| ASUSTek   | TUF Gaming X570-PLUS    | [2acc15f485](https://linux-hardware.org/?probe=2acc15f485) | Dec 27, 2020 |
| Gigabyte  | X570 AORUS ELITE        | [64adbf132b](https://linux-hardware.org/?probe=64adbf132b) | Dec 08, 2020 |
| MSI       | Z87-G45 GAMING          | [cefff6c6c3](https://linux-hardware.org/?probe=cefff6c6c3) | Dec 05, 2020 |
| MSI       | Z87-G45 GAMING          | [cbcb59eb96](https://linux-hardware.org/?probe=cbcb59eb96) | Dec 03, 2020 |
| MSI       | B350M PRO-VDH           | [28b680c91d](https://linux-hardware.org/?probe=28b680c91d) | Nov 29, 2020 |
| Gigabyte  | 990FXA-UD3 R5           | [42a67a5d5e](https://linux-hardware.org/?probe=42a67a5d5e) | Nov 18, 2020 |
| Gigabyte  | 970A-DS3P               | [848672f794](https://linux-hardware.org/?probe=848672f794) | Oct 13, 2020 |
| Gigabyte  | X399 AORUS XTREME-CF    | [1193653309](https://linux-hardware.org/?probe=1193653309) | Oct 04, 2020 |
| Gigabyte  | P55-USB3                | [ceeced1246](https://linux-hardware.org/?probe=ceeced1246) | Oct 02, 2020 |
| ASUSTek   | H81M-C                  | [b062c35766](https://linux-hardware.org/?probe=b062c35766) | Sep 16, 2020 |
| ASUSTek   | G11CD                   | [962d52b690](https://linux-hardware.org/?probe=962d52b690) | Sep 14, 2020 |
| ASUSTek   | G11CD                   | [a663586db5](https://linux-hardware.org/?probe=a663586db5) | Sep 14, 2020 |
| ASUSTek   | TUF Gaming X570-PLUS    | [86215bb4fb](https://linux-hardware.org/?probe=86215bb4fb) | Aug 29, 2020 |
| MSI       | B450 TOMAHAWK MAX       | [e988296384](https://linux-hardware.org/?probe=e988296384) | Aug 19, 2020 |
| Gigabyte  | 990FXA-UD5              | [d86cfc12cc](https://linux-hardware.org/?probe=d86cfc12cc) | Aug 19, 2020 |
| Gigabyte  | 990FXA-UD5              | [937f502004](https://linux-hardware.org/?probe=937f502004) | Aug 18, 2020 |
| MSI       | Z87-G45 GAMING          | [5d992bbc09](https://linux-hardware.org/?probe=5d992bbc09) | Aug 11, 2020 |
| Gigabyte  | B450M DS3H-CF           | [ff7915ae78](https://linux-hardware.org/?probe=ff7915ae78) | Aug 07, 2020 |
| ASUSTek   | TUF Gaming X570-PLUS    | [a57e5d7e84](https://linux-hardware.org/?probe=a57e5d7e84) | Jul 08, 2020 |
| Intel     | DX58SO2 AAG10925-205    | [2e4066d769](https://linux-hardware.org/?probe=2e4066d769) | Jun 30, 2020 |
| ASUSTek   | TUF Gaming X570-PLUS    | [9623b5be2b](https://linux-hardware.org/?probe=9623b5be2b) | Jun 16, 2020 |
| ASUSTek   | TUF Gaming X570-PLUS    | [4125763b79](https://linux-hardware.org/?probe=4125763b79) | Jun 12, 2020 |
| ASUSTek   | TUF Gaming X570-PLUS    | [82af1cec2f](https://linux-hardware.org/?probe=82af1cec2f) | May 30, 2020 |
| ASUSTek   | TUF Gaming X570-PLUS    | [40adc1a5f5](https://linux-hardware.org/?probe=40adc1a5f5) | Apr 03, 2020 |
| Biostar   | G31D-M7                 | [9f6a5c0f39](https://linux-hardware.org/?probe=9f6a5c0f39) | Oct 25, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| Artix Rolling  | 38       | 62.3%   |
| Artix          | 16       | 26.23%  |
| Artix 20220123 | 2        | 3.28%   |
| Artix 20210726 | 2        | 3.28%   |
| Artix 20230320 | 1        | 1.64%   |
| Artix 20230215 | 1        | 1.64%   |
| Artix 20220713 | 1        | 1.64%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| Artix | 59       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                 | Desktops | Percent |
|-----------------------------------------|----------|---------|
| 5.10.8-artix1-1                         | 3        | 4.23%   |
| 6.2.6-artix1-1                          | 2        | 2.82%   |
| 6.1.8-artix1-1                          | 2        | 2.82%   |
| 5.9.14-artix1-1                         | 2        | 2.82%   |
| 5.8.8-artix1-1                          | 2        | 2.82%   |
| 5.8.12-artix1-1                         | 2        | 2.82%   |
| 5.7.6-artix1-1                          | 2        | 2.82%   |
| 5.7.12-artix1-1                         | 2        | 2.82%   |
| 5.18.16-artix1-1                        | 2        | 2.82%   |
| 5.15.12-artix1-1                        | 2        | 2.82%   |
| 5.12.14-artix1-1                        | 2        | 2.82%   |
| 5.12.12-artix1-1                        | 2        | 2.82%   |
| 5.11.16-artix1-1                        | 2        | 2.82%   |
| 5.10.4-artix2-1                         | 2        | 2.82%   |
| 6.2.11-artix1-1                         | 1        | 1.41%   |
| 6.1.4-artix1-1                          | 1        | 1.41%   |
| 6.1.12-artix1-1                         | 1        | 1.41%   |
| 6.1.1-x64v1-xanmod1-1                   | 1        | 1.41%   |
| 6.0.7-artix1-1                          | 1        | 1.41%   |
| 6.0.1-arch1-1                           | 1        | 1.41%   |
| 5.9.8-zen1-1-zen                        | 1        | 1.41%   |
| 5.9.14-zen1-1-zen                       | 1        | 1.41%   |
| 5.9.12-artix1-1                         | 1        | 1.41%   |
| 5.9.10-artix1-1                         | 1        | 1.41%   |
| 5.8.5-xanmod1-1-xanmod                  | 1        | 1.41%   |
| 5.8.14-artix1-1                         | 1        | 1.41%   |
| 5.7.2-artix1-1                          | 1        | 1.41%   |
| 5.4.197-1-lts54                         | 1        | 1.41%   |
| 5.18.9-zen1-1-zen                       | 1        | 1.41%   |
| 5.17.8-258-tkg-pds                      | 1        | 1.41%   |
| 5.17.4-artix1-1                         | 1        | 1.41%   |
| 5.17.12-lqx1-1-lqx                      | 1        | 1.41%   |
| 5.16.3-artix1-1                         | 1        | 1.41%   |
| 5.16.12-artix1-1                        | 1        | 1.41%   |
| 5.16.10-artix1-1                        | 1        | 1.41%   |
| 5.16.1-artix1-1                         | 1        | 1.41%   |
| 5.15.55-rt48-xanmod1-linux-xanmod-rt515 | 1        | 1.41%   |
| 5.15.51-xanmod1-tt-1                    | 1        | 1.41%   |
| 5.15.3-zen1-1-zen                       | 1        | 1.41%   |
| 5.15.2-zen1-1-zen                       | 1        | 1.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.9.14  | 3        | 4.23%   |
| 5.10.8  | 3        | 4.23%   |
| 6.2.6   | 2        | 2.82%   |
| 6.1.8   | 2        | 2.82%   |
| 5.8.8   | 2        | 2.82%   |
| 5.8.12  | 2        | 2.82%   |
| 5.7.6   | 2        | 2.82%   |
| 5.7.12  | 2        | 2.82%   |
| 5.18.16 | 2        | 2.82%   |
| 5.15.12 | 2        | 2.82%   |
| 5.12.14 | 2        | 2.82%   |
| 5.12.12 | 2        | 2.82%   |
| 5.11.16 | 2        | 2.82%   |
| 5.10.4  | 2        | 2.82%   |
| 5.10.15 | 2        | 2.82%   |
| 6.2.11  | 1        | 1.41%   |
| 6.1.4   | 1        | 1.41%   |
| 6.1.12  | 1        | 1.41%   |
| 6.1.1   | 1        | 1.41%   |
| 6.0.7   | 1        | 1.41%   |
| 6.0.1   | 1        | 1.41%   |
| 5.9.8   | 1        | 1.41%   |
| 5.9.12  | 1        | 1.41%   |
| 5.9.10  | 1        | 1.41%   |
| 5.8.5   | 1        | 1.41%   |
| 5.8.14  | 1        | 1.41%   |
| 5.7.2   | 1        | 1.41%   |
| 5.4.197 | 1        | 1.41%   |
| 5.18.9  | 1        | 1.41%   |
| 5.17.8  | 1        | 1.41%   |
| 5.17.4  | 1        | 1.41%   |
| 5.17.12 | 1        | 1.41%   |
| 5.16.3  | 1        | 1.41%   |
| 5.16.12 | 1        | 1.41%   |
| 5.16.10 | 1        | 1.41%   |
| 5.16.1  | 1        | 1.41%   |
| 5.15.55 | 1        | 1.41%   |
| 5.15.51 | 1        | 1.41%   |
| 5.15.3  | 1        | 1.41%   |
| 5.15.2  | 1        | 1.41%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 10       | 14.71%  |
| 5.15    | 7        | 10.29%  |
| 5.9     | 6        | 8.82%   |
| 5.8     | 6        | 8.82%   |
| 5.12    | 6        | 8.82%   |
| 6.1     | 4        | 5.88%   |
| 5.7     | 4        | 5.88%   |
| 5.16    | 4        | 5.88%   |
| 5.11    | 4        | 5.88%   |
| 6.2     | 3        | 4.41%   |
| 5.18    | 3        | 4.41%   |
| 5.17    | 3        | 4.41%   |
| 6.0     | 2        | 2.94%   |
| 5.14    | 2        | 2.94%   |
| 5.13    | 2        | 2.94%   |
| 5.4     | 1        | 1.47%   |
| 4.19    | 1        | 1.47%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 59       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| KDE5       | 17       | 26.56%  |
| GNOME      | 11       | 17.19%  |
| XFCE       | 8        | 12.5%   |
| X-Cinnamon | 6        | 9.38%   |
| MATE       | 5        | 7.81%   |
| Unknown    | 5        | 7.81%   |
| Cinnamon   | 3        | 4.69%   |
| i3         | 2        | 3.13%   |
| bspwm      | 2        | 3.13%   |
| sway       | 1        | 1.56%   |
| openbox    | 1        | 1.56%   |
| LXQt       | 1        | 1.56%   |
| LXDE       | 1        | 1.56%   |
| DWM        | 1        | 1.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 43       | 70.49%  |
| Tty     | 10       | 16.39%  |
| Wayland | 5        | 8.2%    |
| Unknown | 3        | 4.92%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 24       | 38.1%   |
| SDDM    | 19       | 30.16%  |
| LightDM | 15       | 23.81%  |
| GDM     | 2        | 3.17%   |
| XDM     | 1        | 1.59%   |
| SLiM    | 1        | 1.59%   |
| LXDM    | 1        | 1.59%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 21       | 35%     |
| ru_RU   | 7        | 11.67%  |
| fr_FR   | 5        | 8.33%   |
| Unknown | 5        | 8.33%   |
| C       | 4        | 6.67%   |
| de_DE   | 3        | 5%      |
| pt_PT   | 2        | 3.33%   |
| tr_TR   | 1        | 1.67%   |
| pt_BR   | 1        | 1.67%   |
| lt_LT   | 1        | 1.67%   |
| ja_JP   | 1        | 1.67%   |
| it_IT   | 1        | 1.67%   |
| es_MX   | 1        | 1.67%   |
| es_AR   | 1        | 1.67%   |
| en_IE   | 1        | 1.67%   |
| en_GB   | 1        | 1.67%   |
| en_AU   | 1        | 1.67%   |
| el_GR   | 1        | 1.67%   |
| de_AT   | 1        | 1.67%   |
| bg_BG   | 1        | 1.67%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 39       | 65%     |
| BIOS | 21       | 35%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 40       | 67.8%   |
| Btrfs | 13       | 22.03%  |
| Xfs   | 3        | 5.08%   |
| F2fs  | 2        | 3.39%   |
| Jfs   | 1        | 1.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 44       | 72.13%  |
| Unknown | 13       | 21.31%  |
| MBR     | 4        | 6.56%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 44       | 72.13%  |
| Yes       | 17       | 27.87%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 44       | 73.33%  |
| Yes       | 16       | 26.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 19       | 32.2%   |
| Gigabyte Technology | 15       | 25.42%  |
| MSI                 | 10       | 16.95%  |
| ASRock              | 7        | 11.86%  |
| Intel               | 2        | 3.39%   |
| Hewlett-Packard     | 2        | 3.39%   |
| Dell                | 2        | 3.39%   |
| Biostar             | 1        | 1.69%   |
| Alienware           | 1        | 1.69%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| MSI MS-7A38                    | 3        | 5.08%   |
| MSI MS-7C02                    | 2        | 3.39%   |
| Gigabyte 970A-DS3P             | 2        | 3.39%   |
| MSI MS-7C89                    | 1        | 1.69%   |
| MSI MS-7C56                    | 1        | 1.69%   |
| MSI MS-7C37                    | 1        | 1.69%   |
| MSI MS-7B79                    | 1        | 1.69%   |
| MSI MS-7A69                    | 1        | 1.69%   |
| Intel X99                      | 1        | 1.69%   |
| Intel DX58SO2 AAG10925-205     | 1        | 1.69%   |
| HP Compaq 8200 Elite SFF PC    | 1        | 1.69%   |
| HP 280 G1 MT                   | 1        | 1.69%   |
| Gigabyte Z77X-UD3H             | 1        | 1.69%   |
| Gigabyte X570 AORUS ULTRA      | 1        | 1.69%   |
| Gigabyte X570 AORUS ELITE WIFI | 1        | 1.69%   |
| Gigabyte X570 AORUS ELITE      | 1        | 1.69%   |
| Gigabyte X399 AORUS XTREME     | 1        | 1.69%   |
| Gigabyte P55-USB3              | 1        | 1.69%   |
| Gigabyte HA65M-D2H-B3          | 1        | 1.69%   |
| Gigabyte H61MA-D3V             | 1        | 1.69%   |
| Gigabyte B550M AORUS PRO       | 1        | 1.69%   |
| Gigabyte B450 AORUS PRO WIFI   | 1        | 1.69%   |
| Gigabyte AB350M-DS3H V2        | 1        | 1.69%   |
| Gigabyte 990FXA-UD5            | 1        | 1.69%   |
| Gigabyte 990FXA-UD3 R5         | 1        | 1.69%   |
| Dell OptiPlex 5080             | 1        | 1.69%   |
| Dell Inspiron 530              | 1        | 1.69%   |
| Biostar G31D-M7                | 1        | 1.69%   |
| ASUS TUF Gaming X570-PLUS      | 1        | 1.69%   |
| ASUS TUF Gaming B550M-PLUS     | 1        | 1.69%   |
| ASUS TUF B450-PLUS GAMING      | 1        | 1.69%   |
| ASUS SABERTOOTH 990FX R2.0     | 1        | 1.69%   |
| ASUS ROG STRIX Z370-G GAMING   | 1        | 1.69%   |
| ASUS ROG STRIX X570-F GAMING   | 1        | 1.69%   |
| ASUS ROG STRIX B550-F GAMING   | 1        | 1.69%   |
| ASUS ROG STRIX B350-F GAMING   | 1        | 1.69%   |
| ASUS ROG Maximus XI HERO       | 1        | 1.69%   |
| ASUS Pro WS X570-ACE           | 1        | 1.69%   |
| ASUS PRIME X370-PRO            | 1        | 1.69%   |
| ASUS PRIME B450M-A             | 1        | 1.69%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS ROG              | 5        | 8.47%   |
| MSI MS-7A38           | 3        | 5.08%   |
| Gigabyte X570         | 3        | 5.08%   |
| ASUS TUF              | 3        | 5.08%   |
| ASUS PRIME            | 3        | 5.08%   |
| MSI MS-7C02           | 2        | 3.39%   |
| Gigabyte 970A-DS3P    | 2        | 3.39%   |
| MSI MS-7C89           | 1        | 1.69%   |
| MSI MS-7C56           | 1        | 1.69%   |
| MSI MS-7C37           | 1        | 1.69%   |
| MSI MS-7B79           | 1        | 1.69%   |
| MSI MS-7A69           | 1        | 1.69%   |
| Intel X99             | 1        | 1.69%   |
| Intel DX58SO2         | 1        | 1.69%   |
| HP Compaq             | 1        | 1.69%   |
| HP 280                | 1        | 1.69%   |
| Gigabyte Z77X-UD3H    | 1        | 1.69%   |
| Gigabyte X399         | 1        | 1.69%   |
| Gigabyte P55-USB3     | 1        | 1.69%   |
| Gigabyte HA65M-D2H-B3 | 1        | 1.69%   |
| Gigabyte H61MA-D3V    | 1        | 1.69%   |
| Gigabyte B550M        | 1        | 1.69%   |
| Gigabyte B450         | 1        | 1.69%   |
| Gigabyte AB350M-DS3H  | 1        | 1.69%   |
| Gigabyte 990FXA-UD5   | 1        | 1.69%   |
| Gigabyte 990FXA-UD3   | 1        | 1.69%   |
| Dell OptiPlex         | 1        | 1.69%   |
| Dell Inspiron         | 1        | 1.69%   |
| Biostar G31D-M7       | 1        | 1.69%   |
| ASUS SABERTOOTH       | 1        | 1.69%   |
| ASUS Pro              | 1        | 1.69%   |
| ASUS P8H61-M          | 1        | 1.69%   |
| ASUS P8B75-M          | 1        | 1.69%   |
| ASUS M5A97            | 1        | 1.69%   |
| ASUS G11CD            | 1        | 1.69%   |
| ASUS F2A55-M          | 1        | 1.69%   |
| ASUS All              | 1        | 1.69%   |
| ASRock Z690           | 1        | 1.69%   |
| ASRock X570           | 1        | 1.69%   |
| ASRock H310CM-DVS     | 1        | 1.69%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 11       | 18.64%  |
| 2020 | 9        | 15.25%  |
| 2017 | 8        | 13.56%  |
| 2018 | 7        | 11.86%  |
| 2012 | 7        | 11.86%  |
| 2013 | 5        | 8.47%   |
| 2015 | 3        | 5.08%   |
| 2022 | 2        | 3.39%   |
| 2011 | 2        | 3.39%   |
| 2010 | 2        | 3.39%   |
| 2008 | 2        | 3.39%   |
| 2016 | 1        | 1.69%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 59       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 59       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 59       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 26       | 43.33%  |
| 8.01-16.0   | 14       | 23.33%  |
| 32.01-64.0  | 8        | 13.33%  |
| 64.01-256.0 | 6        | 10%     |
| 3.01-4.0    | 4        | 6.67%   |
| 4.01-8.0    | 1        | 1.67%   |
| 1.01-2.0    | 1        | 1.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 16       | 24.62%  |
| 3.01-4.0   | 14       | 21.54%  |
| 2.01-3.0   | 14       | 21.54%  |
| 1.01-2.0   | 12       | 18.46%  |
| 8.01-16.0  | 3        | 4.62%   |
| 0.51-1.0   | 3        | 4.62%   |
| 0.01-0.5   | 2        | 3.08%   |
| 16.01-24.0 | 1        | 1.54%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 25       | 40.32%  |
| 3      | 15       | 24.19%  |
| 1      | 11       | 17.74%  |
| 4      | 6        | 9.68%   |
| 6      | 3        | 4.84%   |
| 8      | 1        | 1.61%   |
| 7      | 1        | 1.61%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 45       | 76.27%  |
| Yes       | 14       | 23.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 59       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 30       | 50.85%  |
| Yes       | 29       | 49.15%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 33       | 55.93%  |
| Yes       | 26       | 44.07%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 10       | 16.67%  |
| Germany     | 9        | 15%     |
| Russia      | 7        | 11.67%  |
| France      | 7        | 11.67%  |
| Greece      | 3        | 5%      |
| Switzerland | 2        | 3.33%   |
| Poland      | 2        | 3.33%   |
| Finland     | 2        | 3.33%   |
| Canada      | 2        | 3.33%   |
| Bulgaria    | 2        | 3.33%   |
| Ukraine     | 1        | 1.67%   |
| UK          | 1        | 1.67%   |
| Turkey      | 1        | 1.67%   |
| Slovenia    | 1        | 1.67%   |
| Mexico      | 1        | 1.67%   |
| Lithuania   | 1        | 1.67%   |
| Japan       | 1        | 1.67%   |
| Italy       | 1        | 1.67%   |
| Iran        | 1        | 1.67%   |
| Hong Kong   | 1        | 1.67%   |
| Brazil      | 1        | 1.67%   |
| Austria     | 1        | 1.67%   |
| Australia   | 1        | 1.67%   |
| Argentina   | 1        | 1.67%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Paris                  | 3        | 4.76%   |
| Moscow                 | 2        | 3.17%   |
| Helsinki               | 2        | 3.17%   |
| Frankfurt am Main      | 2        | 3.17%   |
| Bern                   | 2        | 3.17%   |
| Athens                 | 2        | 3.17%   |
| Wettringen             | 1        | 1.59%   |
| Vladivostok            | 1        | 1.59%   |
| Vilnius                | 1        | 1.59%   |
| Vienna                 | 1        | 1.59%   |
| Vancouver              | 1        | 1.59%   |
| Upper Norwood          | 1        | 1.59%   |
| Ufa                    | 1        | 1.59%   |
| Toronto                | 1        | 1.59%   |
| Thessaloniki           | 1        | 1.59%   |
| Tehran                 | 1        | 1.59%   |
| Sydney                 | 1        | 1.59%   |
| Stein                  | 1        | 1.59%   |
| Stavropol              | 1        | 1.59%   |
| Statesboro             | 1        | 1.59%   |
| Sofia                  | 1        | 1.59%   |
| Snohomish              | 1        | 1.59%   |
| Shavertown             | 1        | 1.59%   |
| San Miguel de Tucumán | 1        | 1.59%   |
| Riverview              | 1        | 1.59%   |
| Rexburg                | 1        | 1.59%   |
| Plovdiv                | 1        | 1.59%   |
| Maua                   | 1        | 1.59%   |
| Maebashi               | 1        | 1.59%   |
| Lublin                 | 1        | 1.59%   |
| Ljubljana              | 1        | 1.59%   |
| Lafayette              | 1        | 1.59%   |
| Kłodzko               | 1        | 1.59%   |
| Koga                   | 1        | 1.59%   |
| Kazan’               | 1        | 1.59%   |
| Hurricane              | 1        | 1.59%   |
| Huntingtown            | 1        | 1.59%   |
| Gochsheim              | 1        | 1.59%   |
| Factoryville           | 1        | 1.59%   |
| Essen                  | 1        | 1.59%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 27       | 49     | 20.45%  |
| Seagate             | 21       | 28     | 15.91%  |
| Samsung Electronics | 18       | 29     | 13.64%  |
| Kingston            | 11       | 12     | 8.33%   |
| Crucial             | 9        | 15     | 6.82%   |
| Toshiba             | 7        | 8      | 5.3%    |
| SanDisk             | 6        | 9      | 4.55%   |
| Intel               | 4        | 7      | 3.03%   |
| Phison Electronics  | 2        | 2      | 1.52%   |
| Maxtor              | 2        | 2      | 1.52%   |
| JMicron Technology  | 2        | 2      | 1.52%   |
| Hitachi             | 2        | 2      | 1.52%   |
| Corsair             | 2        | 2      | 1.52%   |
| China               | 2        | 3      | 1.52%   |
| A-DATA Technology   | 2        | 2      | 1.52%   |
| TS512GMT            | 1        | 5      | 0.76%   |
| Transcend           | 1        | 1      | 0.76%   |
| SPCC Sol            | 1        | 1      | 0.76%   |
| SPCC                | 1        | 1      | 0.76%   |
| SK hynix            | 1        | 1      | 0.76%   |
| Silicon Motion      | 1        | 1      | 0.76%   |
| PNY                 | 1        | 1      | 0.76%   |
| Plextor             | 1        | 1      | 0.76%   |
| Phison              | 1        | 1      | 0.76%   |
| Netac               | 1        | 1      | 0.76%   |
| Linux               | 1        | 1      | 0.76%   |
| HGST                | 1        | 2      | 0.76%   |
| Hewlett-Packard     | 1        | 1      | 0.76%   |
| GOODRAM             | 1        | 1      | 0.76%   |
| AMD                 | 1        | 1      | 0.76%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| WDC WD10EZEX-08WN4A0 1TB                          | 3        | 1.96%   |
| Toshiba DT01ACA100 1TB                            | 3        | 1.96%   |
| Seagate ST3500418AS 500GB                         | 3        | 1.96%   |
| Seagate ST1000DM010-2EP102 1TB                    | 3        | 1.96%   |
| Samsung SSD 860 EVO 250GB                         | 3        | 1.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 3        | 1.96%   |
| WDC WD80EZAZ-11TDBA0 8TB                          | 2        | 1.31%   |
| WDC WD40EZRZ-00WN9B0 4TB                          | 2        | 1.31%   |
| WDC WD10EZEX-22MFCA0 1TB                          | 2        | 1.31%   |
| WDC WD100EMAZ-00WJTA0 10TB                        | 2        | 1.31%   |
| Seagate ST500DM002-1BD142 500GB                   | 2        | 1.31%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 2        | 1.31%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB             | 2        | 1.31%   |
| Samsung SSD 970 EVO 1TB                           | 2        | 1.31%   |
| Samsung SSD 840 EVO 250GB                         | 2        | 1.31%   |
| Phison PS5013 E13 NVMe Controller 500GB           | 2        | 1.31%   |
| Kingston SA400S37120G 120GB SSD                   | 2        | 1.31%   |
| Crucial CT250MX500SSD1 250GB                      | 2        | 1.31%   |
| Crucial CT240BX500SSD1 240GB                      | 2        | 1.31%   |
| Crucial CT1000MX500SSD1 1TB                       | 2        | 1.31%   |
| WDC WDS500G2B0C-00PXH0 500GB                      | 1        | 0.65%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 1        | 0.65%   |
| WDC WDS256G1X0C-00ENX0 256GB                      | 1        | 0.65%   |
| WDC WDS100T2B0C-00PXH0 1TB                        | 1        | 0.65%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                    | 1        | 0.65%   |
| WDC WDBNCE5000PNC 500GB SSD                       | 1        | 0.65%   |
| WDC WD80EFBX-68AZZN0 8TB                          | 1        | 0.65%   |
| WDC WD6001FZWX-00A2VA0 6TB                        | 1        | 0.65%   |
| WDC WD5003ABYX-18WERA0 500GB                      | 1        | 0.65%   |
| WDC WD5000LPVX-00V0TT0 500GB                      | 1        | 0.65%   |
| WDC WD5000AAKX-60U6AA0 500GB                      | 1        | 0.65%   |
| WDC WD4003FZEX-00Z4SA0 4TB                        | 1        | 0.65%   |
| WDC WD4003FFBX-68MU3N0 4TB                        | 1        | 0.65%   |
| WDC WD3200AAKX-00ERMA0 320GB                      | 1        | 0.65%   |
| WDC WD30EZRX-00DC0B0 3TB                          | 1        | 0.65%   |
| WDC WD30EFRX-68EUZN0 3TB                          | 1        | 0.65%   |
| WDC WD2500HHTZ-04N21V0 250GB                      | 1        | 0.65%   |
| WDC WD20EZRX-00D8PB0 2TB                          | 1        | 0.65%   |
| WDC WD20EZBX-00AYRA0 2TB                          | 1        | 0.65%   |
| WDC WD20EZAZ-00GGJB0 2TB                          | 1        | 0.65%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Desktops | Drives | Percent |
|--------------------|----------|--------|---------|
| WDC                | 24       | 41     | 40.68%  |
| Seagate            | 21       | 28     | 35.59%  |
| Toshiba            | 7        | 8      | 11.86%  |
| Maxtor             | 2        | 2      | 3.39%   |
| JMicron Technology | 2        | 2      | 3.39%   |
| Hitachi            | 2        | 2      | 3.39%   |
| HGST               | 1        | 2      | 1.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 10       | 14     | 21.74%  |
| Kingston            | 9        | 10     | 19.57%  |
| Crucial             | 9        | 15     | 19.57%  |
| WDC                 | 3        | 5      | 6.52%   |
| SanDisk             | 2        | 2      | 4.35%   |
| Intel               | 2        | 3      | 4.35%   |
| China               | 2        | 3      | 4.35%   |
| A-DATA Technology   | 2        | 2      | 4.35%   |
| SPCC Sol            | 1        | 1      | 2.17%   |
| SPCC                | 1        | 1      | 2.17%   |
| Plextor             | 1        | 1      | 2.17%   |
| Netac               | 1        | 1      | 2.17%   |
| Linux               | 1        | 1      | 2.17%   |
| GOODRAM             | 1        | 1      | 2.17%   |
| AMD                 | 1        | 1      | 2.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 47       | 85     | 40.52%  |
| SSD     | 41       | 61     | 35.34%  |
| NVMe    | 27       | 41     | 23.28%  |
| Unknown | 1        | 5      | 0.86%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 55       | 142    | 63.22%  |
| NVMe | 27       | 41     | 31.03%  |
| SAS  | 5        | 9      | 5.75%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 43       | 68     | 44.79%  |
| 0.51-1.0   | 30       | 47     | 31.25%  |
| 1.01-2.0   | 10       | 11     | 10.42%  |
| 4.01-10.0  | 5        | 12     | 5.21%   |
| 3.01-4.0   | 4        | 4      | 4.17%   |
| 2.01-3.0   | 4        | 4      | 4.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 12       | 19.67%  |
| 1001-2000      | 12       | 19.67%  |
| 2001-3000      | 11       | 18.03%  |
| 101-250        | 10       | 16.39%  |
| 501-1000       | 9        | 14.75%  |
| 251-500        | 5        | 8.2%    |
| 51-100         | 2        | 3.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 13       | 20.97%  |
| 251-500        | 10       | 16.13%  |
| 1001-2000      | 10       | 16.13%  |
| 1-20           | 8        | 12.9%   |
| More than 3000 | 7        | 11.29%  |
| 101-250        | 7        | 11.29%  |
| 51-100         | 3        | 4.84%   |
| 21-50          | 2        | 3.23%   |
| 2001-3000      | 2        | 3.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| WDC WD3200AAKX-00ERMA0 320GB     | 1        | 1      | 8.33%   |
| WDC WD30EZRX-00DC0B0 3TB         | 1        | 1      | 8.33%   |
| Toshiba MK7575GSX 752GB          | 1        | 1      | 8.33%   |
| Seagate ST8000DM004-2CX188 8TB   | 1        | 1      | 8.33%   |
| Seagate ST2000DX002-2DV164 2TB   | 1        | 1      | 8.33%   |
| Seagate ST2000DM006-2DM164 2TB   | 1        | 1      | 8.33%   |
| Maxtor 6Y080M0 82GB              | 1        | 1      | 8.33%   |
| Kingston SUV400S37240G 240GB SSD | 1        | 1      | 8.33%   |
| Kingston SA400S37120G 120GB SSD  | 1        | 1      | 8.33%   |
| Intel SSDSC2BW480A4 480GB        | 1        | 2      | 8.33%   |
| Intel SSDPEKKW128G7 128GB        | 1        | 1      | 8.33%   |
| Hewlett-Packard SSD EX900 250GB  | 1        | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor          | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| Seagate         | 3        | 3      | 25%     |
| WDC             | 2        | 2      | 16.67%  |
| Kingston        | 2        | 2      | 16.67%  |
| Intel           | 2        | 3      | 16.67%  |
| Toshiba         | 1        | 1      | 8.33%   |
| Maxtor          | 1        | 1      | 8.33%   |
| Hewlett-Packard | 1        | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 3        | 3      | 42.86%  |
| WDC     | 2        | 2      | 28.57%  |
| Toshiba | 1        | 1      | 14.29%  |
| Maxtor  | 1        | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 7        | 7      | 58.33%  |
| SSD  | 3        | 4      | 25%     |
| NVMe | 2        | 2      | 16.67%  |

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
| Works    | 37       | 104    | 50%     |
| Detected | 26       | 75     | 35.14%  |
| Malfunc  | 11       | 13     | 14.86%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| AMD                         | 35       | 35.71%  |
| Intel                       | 25       | 25.51%  |
| Samsung Electronics         | 11       | 11.22%  |
| SanDisk                     | 6        | 6.12%   |
| Phison Electronics          | 5        | 5.1%    |
| Marvell Technology Group    | 5        | 5.1%    |
| Silicon Motion              | 3        | 3.06%   |
| ASMedia Technology          | 3        | 3.06%   |
| Kingston Technology Company | 2        | 2.04%   |
| SK hynix                    | 1        | 1.02%   |
| JMicron Technology          | 1        | 1.02%   |
| Broadcom / LSI              | 1        | 1.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 24       | 19.83%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 9        | 7.44%   |
| AMD 400 Series Chipset SATA Controller                                         | 7        | 5.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 6        | 4.96%   |
| AMD 300 Series Chipset SATA Controller                                         | 6        | 4.96%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4        | 3.31%   |
| AMD 500 Series Chipset SATA Controller                                         | 4        | 3.31%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3        | 2.48%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 3        | 2.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3        | 2.48%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3        | 2.48%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 2        | 1.65%   |
| Phison PS5013 E13 NVMe Controller                                              | 2        | 1.65%   |
| Phison E12 NVMe Controller                                                     | 2        | 1.65%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2        | 1.65%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2        | 1.65%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2        | 1.65%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2        | 1.65%   |
| SK hynix Non-Volatile memory controller                                        | 1        | 0.83%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1        | 0.83%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1        | 0.83%   |
| SanDisk WD Black SN770 NVMe SSD                                                | 1        | 0.83%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1        | 0.83%   |
| SanDisk WD Black NVMe SSD                                                      | 1        | 0.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 0.83%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 0.83%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 0.83%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                          | 1        | 0.83%   |
| Marvell Group 88SE912x IDE Controller                                          | 1        | 0.83%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                           | 1        | 0.83%   |
| Kingston Company NVMe Controller                                               | 1        | 0.83%   |
| Kingston Company A2000 NVMe SSD                                                | 1        | 0.83%   |
| JMicron JMB363 SATA/IDE Controller                                             | 1        | 0.83%   |
| Intel SSD 660P Series                                                          | 1        | 0.83%   |
| Intel SSD 600P Series                                                          | 1        | 0.83%   |
| Intel SATA Controller [RAID mode]                                              | 1        | 0.83%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1        | 0.83%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1        | 0.83%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 0.83%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 1        | 0.83%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 56       | 60.22%  |
| NVMe | 27       | 29.03%  |
| IDE  | 8        | 8.6%    |
| RAID | 1        | 1.08%   |
| SAS  | 1        | 1.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 35       | 59.32%  |
| Intel  | 24       | 40.68%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD FX-8350 Eight-Core Processor                | 4        | 6.78%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 3        | 5.08%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 3        | 5.08%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 3        | 5.08%   |
| AMD Ryzen 5 2600X Six-Core Processor            | 3        | 5.08%   |
| Intel Core i7-9700K CPU @ 3.60GHz               | 2        | 3.39%   |
| Intel Core i5-2500 CPU @ 3.30GHz                | 2        | 3.39%   |
| Intel Core i5-10400F CPU @ 2.90GHz              | 2        | 3.39%   |
| AMD Ryzen 7 5700G with Radeon Graphics          | 2        | 3.39%   |
| AMD Ryzen 5 5600X 6-Core Processor              | 2        | 3.39%   |
| AMD Ryzen 5 3600 6-Core Processor               | 2        | 3.39%   |
| AMD Ryzen 5 1600 Six-Core Processor             | 2        | 3.39%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz             | 1        | 1.69%   |
| Intel Core i7-9700F CPU @ 3.00GHz               | 1        | 1.69%   |
| Intel Core i7-4790K CPU @ 4.00GHz               | 1        | 1.69%   |
| Intel Core i7 CPU 970 @ 3.20GHz                 | 1        | 1.69%   |
| Intel Core i5-9600K CPU @ 3.70GHz               | 1        | 1.69%   |
| Intel Core i5-7600K CPU @ 3.80GHz               | 1        | 1.69%   |
| Intel Core i5-6600K CPU @ 3.50GHz               | 1        | 1.69%   |
| Intel Core i5-6400 CPU @ 2.70GHz                | 1        | 1.69%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 1        | 1.69%   |
| Intel Core i5-3330 CPU @ 3.00GHz                | 1        | 1.69%   |
| Intel Core i5-2310 CPU @ 2.90GHz                | 1        | 1.69%   |
| Intel Core i5-10500T CPU @ 2.30GHz              | 1        | 1.69%   |
| Intel Core i5 CPU 660 @ 3.33GHz                 | 1        | 1.69%   |
| Intel Core i3-2120 CPU @ 3.30GHz                | 1        | 1.69%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz            | 1        | 1.69%   |
| Intel Core 2 Duo CPU E4600 @ 2.40GHz            | 1        | 1.69%   |
| Intel Celeron CPU G1840 @ 2.80GHz               | 1        | 1.69%   |
| Intel 12th Gen Core i5-12600K                   | 1        | 1.69%   |
| AMD Ryzen Threadripper 2990WX 32-Core Processor | 1        | 1.69%   |
| AMD Ryzen 9 3900XT 12-Core Processor            | 1        | 1.69%   |
| AMD Ryzen 7 5800X 8-Core Processor              | 1        | 1.69%   |
| AMD Ryzen 7 1700 Eight-Core Processor           | 1        | 1.69%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 1        | 1.69%   |
| AMD Ryzen 5 1500X Quad-Core Processor           | 1        | 1.69%   |
| AMD Ryzen 3 1200 Quad-Core Processor            | 1        | 1.69%   |
| AMD Phenom II X4 955 Processor                  | 1        | 1.69%   |
| AMD FX-6300 Six-Core Processor                  | 1        | 1.69%   |
| AMD A6-5400K APU with Radeon HD Graphics        | 1        | 1.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 13       | 22.03%  |
| AMD Ryzen 5            | 11       | 18.64%  |
| AMD Ryzen 7            | 10       | 16.95%  |
| Intel Core i7          | 5        | 8.47%   |
| AMD FX                 | 5        | 8.47%   |
| AMD Ryzen 9            | 4        | 6.78%   |
| Intel Core 2 Duo       | 2        | 3.39%   |
| Other                  | 1        | 1.69%   |
| Intel Xeon             | 1        | 1.69%   |
| Intel Core i3          | 1        | 1.69%   |
| Intel Celeron          | 1        | 1.69%   |
| AMD Ryzen Threadripper | 1        | 1.69%   |
| AMD Ryzen 3            | 1        | 1.69%   |
| AMD Phenom II X4       | 1        | 1.69%   |
| AMD A6                 | 1        | 1.69%   |
| AMD A10                | 1        | 1.69%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 16       | 27.12%  |
| 4      | 15       | 25.42%  |
| 8      | 13       | 22.03%  |
| 2      | 6        | 10.17%  |
| 12     | 4        | 6.78%   |
| 3      | 2        | 3.39%   |
| 32     | 1        | 1.69%   |
| 10     | 1        | 1.69%   |
| 1      | 1        | 1.69%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 59       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 42       | 71.19%  |
| 1      | 17       | 28.81%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 59       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 16       | 25.81%  |
| 0x0800820d | 6        | 9.68%   |
| 0x08701013 | 5        | 8.06%   |
| 0x906ed    | 3        | 4.84%   |
| 0x206a7    | 3        | 4.84%   |
| 0x08701021 | 3        | 4.84%   |
| 0x06000822 | 3        | 4.84%   |
| 0xa0655    | 2        | 3.23%   |
| 0x506e3    | 2        | 3.23%   |
| 0x306c3    | 2        | 3.23%   |
| 0x0a201016 | 2        | 3.23%   |
| 0x06000852 | 2        | 3.23%   |
| 0xa0653    | 1        | 1.61%   |
| 0x906e9    | 1        | 1.61%   |
| 0x6fd      | 1        | 1.61%   |
| 0x306a9    | 1        | 1.61%   |
| 0x206c2    | 1        | 1.61%   |
| 0x20652    | 1        | 1.61%   |
| 0x1067a    | 1        | 1.61%   |
| 0x0a50000b | 1        | 1.61%   |
| 0x0a201009 | 1        | 1.61%   |
| 0x0800820b | 1        | 1.61%   |
| 0x08001138 | 1        | 1.61%   |
| 0x08001129 | 1        | 1.61%   |
| 0x06003106 | 1        | 1.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen+             | 9        | 15.25%  |
| Zen 2            | 9        | 15.25%  |
| Zen 3            | 6        | 10.17%  |
| Piledriver       | 6        | 10.17%  |
| KabyLake         | 5        | 8.47%   |
| SandyBridge      | 4        | 6.78%   |
| Zen              | 3        | 5.08%   |
| Haswell          | 3        | 5.08%   |
| CometLake        | 3        | 5.08%   |
| Westmere         | 2        | 3.39%   |
| Skylake          | 2        | 3.39%   |
| IvyBridge        | 2        | 3.39%   |
| Steamroller      | 1        | 1.69%   |
| Penryn           | 1        | 1.69%   |
| K10              | 1        | 1.69%   |
| Core             | 1        | 1.69%   |
| Alderlake Hybrid | 1        | 1.69%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 35       | 55.56%  |
| Nvidia | 22       | 34.92%  |
| Intel  | 6        | 9.52%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 8        | 12.31%  |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 6        | 9.23%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 3        | 4.62%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 3.08%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 2        | 3.08%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 3.08%   |
| AMD Redwood XT [Radeon HD 5670/5690/5730]                                   | 2        | 3.08%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2        | 3.08%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 3.08%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 3.08%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 1.54%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 1.54%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 1.54%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 1.54%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 1.54%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                          | 1        | 1.54%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.54%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 1.54%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.54%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 1.54%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.54%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 1.54%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 1.54%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.54%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                           | 1        | 1.54%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.54%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 1.54%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 1        | 1.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 1.54%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.54%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 1.54%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.54%   |
| AMD Vega 20 [Radeon VII]                                                    | 1        | 1.54%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 1        | 1.54%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1        | 1.54%   |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                    | 1        | 1.54%   |
| AMD Pitcairn XT [Radeon HD 7870 GHz Edition]                                | 1        | 1.54%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 1        | 1.54%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 1        | 1.54%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 1        | 1.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x AMD      | 31       | 51.67%  |
| 1 x Nvidia   | 20       | 33.33%  |
| 1 x Intel    | 5        | 8.33%   |
| 2 x AMD      | 2        | 3.33%   |
| AMD + Nvidia | 2        | 3.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 45       | 73.77%  |
| Proprietary | 16       | 26.23%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 20       | 31.25%  |
| 7.01-8.0   | 14       | 21.88%  |
| 3.01-4.0   | 10       | 15.63%  |
| 1.01-2.0   | 7        | 10.94%  |
| 8.01-16.0  | 6        | 9.38%   |
| 0.51-1.0   | 5        | 7.81%   |
| 5.01-6.0   | 1        | 1.56%   |
| 0.01-0.5   | 1        | 1.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 12       | 15.19%  |
| Acer                 | 10       | 12.66%  |
| Philips              | 7        | 8.86%   |
| Goldstar             | 7        | 8.86%   |
| AOC                  | 7        | 8.86%   |
| Dell                 | 5        | 6.33%   |
| BenQ                 | 5        | 6.33%   |
| ASUSTek Computer     | 5        | 6.33%   |
| Ancor Communications | 2        | 2.53%   |
| ViewSonic            | 1        | 1.27%   |
| Vestel Elektronik    | 1        | 1.27%   |
| Sony                 | 1        | 1.27%   |
| Packard Bell         | 1        | 1.27%   |
| MSI                  | 1        | 1.27%   |
| LG Electronics       | 1        | 1.27%   |
| Lenovo Group Limited | 1        | 1.27%   |
| Lenovo               | 1        | 1.27%   |
| KTC                  | 1        | 1.27%   |
| Jean                 | 1        | 1.27%   |
| Iiyama               | 1        | 1.27%   |
| Idek Iiyama          | 1        | 1.27%   |
| HVR                  | 1        | 1.27%   |
| Hitachi              | 1        | 1.27%   |
| Hewlett-Packard      | 1        | 1.27%   |
| Envision Peripherals | 1        | 1.27%   |
| Eizo                 | 1        | 1.27%   |
| CTV                  | 1        | 1.27%   |
| Belinea              | 1        | 1.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| AOC e22t AOC2200 1920x1080 477x268mm 21.5-inch                          | 2        | 2.41%   |
| Ancor Communications ASUS PB277 ACI27B5 1920x1080 597x336mm 27.0-inch   | 2        | 2.41%   |
| ViewSonic LCD Monitor VX2452 Series 3840x1080                           | 1        | 1.2%    |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch  | 1        | 1.2%    |
| Sony TV SNY7001 1920x1080                                               | 1        | 1.2%    |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch       | 1        | 1.2%    |
| Samsung Electronics T24B301 SAM098E 1920x1080 521x293mm 23.5-inch       | 1        | 1.2%    |
| Samsung Electronics SyncMaster SAM047D 1360x768 410x230mm 18.5-inch     | 1        | 1.2%    |
| Samsung Electronics SMBX2450 SAM0721 1920x1080 531x299mm 24.0-inch      | 1        | 1.2%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1        | 1.2%    |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch       | 1        | 1.2%    |
| Samsung Electronics S24A31x SAM7114 1920x1080 527x296mm 23.8-inch       | 1        | 1.2%    |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 1        | 1.2%    |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 1        | 1.2%    |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 890x500mm 40.2-inch   | 1        | 1.2%    |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch       | 1        | 1.2%    |
| Samsung Electronics C27FG7x SAM0E41 1920x1080 598x337mm 27.0-inch       | 1        | 1.2%    |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch       | 1        | 1.2%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 1        | 1.2%    |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch                | 1        | 1.2%    |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch                 | 1        | 1.2%    |
| Philips PHL 245E1 PHLC20B 2560x1440 527x296mm 23.8-inch                 | 1        | 1.2%    |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 1        | 1.2%    |
| Philips PHL 220V8 PHLC218 1920x1080 477x268mm 21.5-inch                 | 1        | 1.2%    |
| Philips 247ELH PHLC085 1920x1080 521x293mm 23.5-inch                    | 1        | 1.2%    |
| Philips 226VL PHLC081 1920x1080 480x268mm 21.6-inch                     | 1        | 1.2%    |
| Packard Bell Viseo203DX PKB0378 1600x900 432x240mm 19.5-inch            | 1        | 1.2%    |
| MSI MAG341CQ MSI1462 3440x1440 797x333mm 34.0-inch                      | 1        | 1.2%    |
| LG Electronics LCD Monitor 34UC89G                                      | 1        | 1.2%    |
| Lenovo L197 Wide LEN1152 1440x900 410x257mm 19.1-inch                   | 1        | 1.2%    |
| Lenovo Group Limited LCD Monitor LEN LI2323swA 4480x1080                | 1        | 1.2%    |
| KTC W2402S KTC2400 1920x1080 527x296mm 23.8-inch                        | 1        | 1.2%    |
| Jean JT198x6-7 JEN17C6 1280x1024 376x301mm 19.0-inch                    | 1        | 1.2%    |
| Iiyama PL3461WQ IVM7615 3440x1440 800x335mm 34.1-inch                   | 1        | 1.2%    |
| Idek Iiyama LCD Monitor PL2488H                                         | 1        | 1.2%    |
| HVR HTC-VIVE HVRAA01 2160x1200                                          | 1        | 1.2%    |
| Hitachi HISENSE HEC0030 3840x2160 1872x1053mm 84.6-inch                 | 1        | 1.2%    |
| Hewlett-Packard LA1951 HWP285B 1280x960 380x300mm 19.1-inch             | 1        | 1.2%    |
| Goldstar W1642 GSM3E86 1360x768 344x194mm 15.5-inch                     | 1        | 1.2%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                | 1        | 1.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 36       | 47.37%  |
| 3840x2160 (4K)     | 13       | 17.11%  |
| 2560x1440 (QHD)    | 6        | 7.89%   |
| Unknown            | 3        | 3.95%   |
| 3440x1440          | 2        | 2.63%   |
| 2560x1080          | 2        | 2.63%   |
| 1360x768           | 2        | 2.63%   |
| 1280x1024 (SXGA)   | 2        | 2.63%   |
| 4480x1080          | 1        | 1.32%   |
| 3840x1080          | 1        | 1.32%   |
| 3600x1080          | 1        | 1.32%   |
| 2160x1200          | 1        | 1.32%   |
| 1920x1200 (WUXGA)  | 1        | 1.32%   |
| 1680x1050 (WSXGA+) | 1        | 1.32%   |
| 1600x900 (HD+)     | 1        | 1.32%   |
| 1440x900 (WXGA+)   | 1        | 1.32%   |
| 1280x960           | 1        | 1.32%   |
| 1024x768 (XGA)     | 1        | 1.32%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 14       | 18.67%  |
| 27      | 12       | 16%     |
| 24      | 12       | 16%     |
| 21      | 8        | 10.67%  |
| Unknown | 5        | 6.67%   |
| 84      | 4        | 5.33%   |
| 34      | 4        | 5.33%   |
| 31      | 4        | 5.33%   |
| 19      | 4        | 5.33%   |
| 32      | 2        | 2.67%   |
| 15      | 2        | 2.67%   |
| 72      | 1        | 1.33%   |
| 52      | 1        | 1.33%   |
| 20      | 1        | 1.33%   |
| 18      | 1        | 1.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 34       | 46.58%  |
| 401-500     | 11       | 15.07%  |
| 701-800     | 6        | 8.22%   |
| 601-700     | 6        | 8.22%   |
| 1501-2000   | 5        | 6.85%   |
| Unknown     | 5        | 6.85%   |
| 351-400     | 3        | 4.11%   |
| 301-350     | 2        | 2.74%   |
| 1001-1500   | 1        | 1.37%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 50       | 75.76%  |
| 21/9    | 4        | 6.06%   |
| 16/10   | 4        | 6.06%   |
| Unknown | 4        | 6.06%   |
| 5/4     | 3        | 4.55%   |
| 4/3     | 1        | 1.52%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 31       | 41.33%  |
| 301-350        | 12       | 16%     |
| 351-500        | 10       | 13.33%  |
| More than 1000 | 6        | 8%      |
| 151-200        | 6        | 8%      |
| Unknown        | 5        | 6.67%   |
| 251-300        | 2        | 2.67%   |
| 101-110        | 2        | 2.67%   |
| 141-150        | 1        | 1.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 38       | 55.07%  |
| 101-120 | 15       | 21.74%  |
| 121-160 | 6        | 8.7%    |
| Unknown | 5        | 7.25%   |
| 161-240 | 3        | 4.35%   |
| 1-50    | 2        | 2.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 43       | 70.49%  |
| 2     | 14       | 22.95%  |
| 3     | 3        | 4.92%   |
| 4     | 1        | 1.64%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 39       | 48.15%  |
| Intel                                 | 25       | 30.86%  |
| TP-Link                               | 3        | 3.7%    |
| Qualcomm Atheros                      | 3        | 3.7%    |
| D-Link System                         | 3        | 3.7%    |
| Xiaomi                                | 1        | 1.23%   |
| Ralink Technology                     | 1        | 1.23%   |
| Qualcomm Atheros Communications       | 1        | 1.23%   |
| Microsoft                             | 1        | 1.23%   |
| Google                                | 1        | 1.23%   |
| DisplayLink                           | 1        | 1.23%   |
| Aquantia                              | 1        | 1.23%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 1.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32       | 31.37%  |
| Intel I211 Gigabit Network Connection                             | 9        | 8.82%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 2.94%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 2        | 1.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2        | 1.96%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 2        | 1.96%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 1.96%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2        | 1.96%   |
| Intel Wi-Fi 6 AX200                                               | 2        | 1.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 1.96%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 1.96%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 1.96%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.98%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1        | 0.98%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.98%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1        | 0.98%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 0.98%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1        | 0.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.98%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 0.98%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 0.98%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1        | 0.98%   |
| Realtek 802.11ac NIC                                              | 1        | 0.98%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 0.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1        | 0.98%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.98%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.98%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1        | 0.98%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 0.98%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.98%   |
| Microsoft Xbox Wireless Adapter for Windows                       | 1        | 0.98%   |
| Intel Wireless-AC 9260                                            | 1        | 0.98%   |
| Intel Wireless 8265 / 8275                                        | 1        | 0.98%   |
| Intel Wireless 8260                                               | 1        | 0.98%   |
| Intel Wireless 7265                                               | 1        | 0.98%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.98%   |
| Intel Ethernet Controller I225-V                                  | 1        | 0.98%   |
| Intel Ethernet Connection I219-LM                                 | 1        | 0.98%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.98%   |
| Intel Ethernet Connection (17) I219-V                             | 1        | 0.98%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 12       | 40%     |
| Realtek Semiconductor                 | 8        | 26.67%  |
| TP-Link                               | 3        | 10%     |
| Qualcomm Atheros                      | 2        | 6.67%   |
| Ralink Technology                     | 1        | 3.33%   |
| Qualcomm Atheros Communications       | 1        | 3.33%   |
| Microsoft                             | 1        | 3.33%   |
| D-Link System                         | 1        | 3.33%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 3.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                               | Desktops | Percent |
|-----------------------------------------------------------------------------------------------------|----------|---------|
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                         | 2        | 6.45%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                                     | 2        | 6.45%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                            | 2        | 6.45%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                              | 2        | 6.45%   |
| Intel Wi-Fi 6 AX200                                                                                 | 2        | 6.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                                    | 2        | 6.45%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                                 | 1        | 3.23%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                            | 1        | 3.23%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                                     | 1        | 3.23%   |
| Realtek RTL8188EE Wireless Network Adapter                                                          | 1        | 3.23%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                             | 1        | 3.23%   |
| Realtek 802.11ac NIC                                                                                | 1        | 3.23%   |
| Ralink MT7601U Wireless Adapter                                                                     | 1        | 3.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                          | 1        | 3.23%   |
| Qualcomm Atheros AR9271 802.11n                                                                     | 1        | 3.23%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                                    | 1        | 3.23%   |
| Microsoft Xbox Wireless Adapter for Windows                                                         | 1        | 3.23%   |
| Intel Wireless-AC 9260                                                                              | 1        | 3.23%   |
| Intel Wireless 8265 / 8275                                                                          | 1        | 3.23%   |
| Intel Wireless 8260                                                                                 | 1        | 3.23%   |
| Intel Wireless 7265                                                                                 | 1        | 3.23%   |
| Intel Comet Lake PCH CNVi WiFi                                                                      | 1        | 3.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                                                     | 1        | 3.23%   |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A2) [Atheros AR9170+AR9104]         | 1        | 3.23%   |
| 802.11g Adapter [Linksys WUSB54GC v3] WUSB100 v2 RangePlus Wireless Network Adapter [Ralink RT3070] | 1        | 3.23%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 36       | 53.73%  |
| Intel                 | 22       | 32.84%  |
| Qualcomm Atheros      | 3        | 4.48%   |
| D-Link System         | 2        | 2.99%   |
| Xiaomi                | 1        | 1.49%   |
| Google                | 1        | 1.49%   |
| DisplayLink           | 1        | 1.49%   |
| Aquantia              | 1        | 1.49%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32       | 45.07%  |
| Intel I211 Gigabit Network Connection                             | 9        | 12.68%  |
| Intel Ethernet Connection (2) I219-V                              | 3        | 4.23%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 2.82%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 2.82%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 2.82%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.41%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 1.41%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1        | 1.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 1.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.41%   |
| Intel I210 Gigabit Network Connection                             | 1        | 1.41%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.41%   |
| Intel Ethernet Connection I219-LM                                 | 1        | 1.41%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.41%   |
| Intel Ethernet Connection (17) I219-V                             | 1        | 1.41%   |
| Intel Ethernet Connection (12) I219-V                             | 1        | 1.41%   |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 1.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 1.41%   |
| Intel 82567LF-2 Gigabit Network Connection                        | 1        | 1.41%   |
| Intel 82562V-2 10/100 Network Connection                          | 1        | 1.41%   |
| Google Nexus/Pixel Device (tether+ debug)                         | 1        | 1.41%   |
| DisplayLink Kensington Dock (Composite Device)                    | 1        | 1.41%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 59       | 66.29%  |
| WiFi     | 30       | 33.71%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 44       | 74.58%  |
| WiFi     | 15       | 25.42%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 32       | 54.24%  |
| 2     | 24       | 40.68%  |
| 4     | 2        | 3.39%   |
| 3     | 1        | 1.69%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 54       | 90%     |
| Yes  | 6        | 10%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 12       | 44.44%  |
| Cambridge Silicon Radio         | 6        | 22.22%  |
| IMC Networks                    | 3        | 11.11%  |
| ASUSTek Computer                | 2        | 7.41%   |
| Qualcomm Atheros Communications | 1        | 3.7%    |
| HTC (High Tech Computer)        | 1        | 3.7%    |
| Dynex                           | 1        | 3.7%    |
| Broadcom                        | 1        | 3.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 6        | 22.22%  |
| Intel Bluetooth wireless interface                                   | 3        | 11.11%  |
| Intel Wireless-AC 3168 Bluetooth                                     | 2        | 7.41%   |
| Intel AX210 Bluetooth                                                | 2        | 7.41%   |
| Intel AX200 Bluetooth                                                | 2        | 7.41%   |
| IMC Networks Bluetooth Radio                                         | 2        | 7.41%   |
| Qualcomm Atheros  Bluetooth Device                                   | 1        | 3.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 1        | 3.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 1        | 3.7%    |
| Intel AX201 Bluetooth                                                | 1        | 3.7%    |
| IMC Networks Bluetooth Device                                        | 1        | 3.7%    |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 3.7%    |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 1        | 3.7%    |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 1        | 3.7%    |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 1        | 3.7%    |
| ASUS Bluetooth Radio                                                 | 1        | 3.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD                                             | 46       | 38.33%  |
| Intel                                           | 23       | 19.17%  |
| Nvidia                                          | 22       | 18.33%  |
| C-Media Electronics                             | 9        | 7.5%    |
| Creative Labs                                   | 3        | 2.5%    |
| Logitech                                        | 2        | 1.67%   |
| Creative Technology                             | 2        | 1.67%   |
| TC Electronic                                   | 1        | 0.83%   |
| SteelSeries ApS                                 | 1        | 0.83%   |
| Shure                                           | 1        | 0.83%   |
| Realtek Semiconductor                           | 1        | 0.83%   |
| Razer USA                                       | 1        | 0.83%   |
| PreSonus Audio Electronics                      | 1        | 0.83%   |
| Native Instruments                              | 1        | 0.83%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.83%   |
| Generalplus Technology                          | 1        | 0.83%   |
| Focusrite-Novation                              | 1        | 0.83%   |
| EVGA                                            | 1        | 0.83%   |
| Corsair                                         | 1        | 0.83%   |
| AudioQuest                                      | 1        | 0.83%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 12       | 8.22%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 11       | 7.53%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 9        | 6.16%   |
| AMD Navi 10 HDMI Audio                                                     | 7        | 4.79%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6        | 4.11%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 5        | 3.42%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 5        | 3.42%   |
| Nvidia GP104 High Definition Audio Controller                              | 4        | 2.74%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 2.74%   |
| Intel 200 Series PCH HD Audio                                              | 4        | 2.74%   |
| C-Media Electronics USB Audio Device                                       | 3        | 2.05%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 3        | 2.05%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3        | 2.05%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3        | 2.05%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 1.37%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 1.37%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 1.37%   |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 1.37%   |
| Intel Comet Lake PCH-V cAVS                                                | 2        | 1.37%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 1.37%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2        | 1.37%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 1.37%   |
| Creative Labs CA0110 [Sound Blaster X-Fi Xtreme Audio]                     | 2        | 1.37%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 2        | 1.37%   |
| AMD FCH Azalia Controller                                                  | 2        | 1.37%   |
| TC Electronic VoiceLive Play                                               | 1        | 0.68%   |
| SteelSeries ApS Arctis Pro Wireless                                        | 1        | 0.68%   |
| Shure MV7                                                                  | 1        | 0.68%   |
| Realtek Semiconductor Realtek Audio USB                                    | 1        | 0.68%   |
| Razer USA RZ19-0229 Gaming Microphone                                      | 1        | 0.68%   |
| PreSonus Audio Electronics AudioBox Go                                     | 1        | 0.68%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 0.68%   |
| Nvidia TU102 High Definition Audio Controller                              | 1        | 0.68%   |
| Nvidia High Definition Audio Controller                                    | 1        | 0.68%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 0.68%   |
| Nvidia GM200 High Definition Audio                                         | 1        | 0.68%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 0.68%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1        | 0.68%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 0.68%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 13       | 22.81%  |
| G.Skill             | 12       | 21.05%  |
| Kingston            | 11       | 19.3%   |
| Unknown             | 4        | 7.02%   |
| Patriot             | 4        | 7.02%   |
| Crucial             | 4        | 7.02%   |
| SK hynix            | 3        | 5.26%   |
| Samsung Electronics | 2        | 3.51%   |
| Transcend           | 1        | 1.75%   |
| Micron Technology   | 1        | 1.75%   |
| AMD                 | 1        | 1.75%   |
| A-DATA Technology   | 1        | 1.75%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s     | 3        | 5%      |
| Kingston RAM 99U5474-026.A00LF 4GB DIMM DDR3 1333MT/s    | 2        | 3.33%   |
| G.Skill RAM F3-10666CL9-4GBNT 4GB DIMM DDR3 1600MT/s     | 2        | 3.33%   |
| Crucial RAM BLS16G4D30AESB.M16FE 16GB DIMM DDR4 3200MT/s | 2        | 3.33%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 2        | 3.33%   |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3200MT/s | 2        | 3.33%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 1        | 1.67%   |
| Unknown RAM Module 2048MB DIMM SDRAM                     | 1        | 1.67%   |
| Unknown RAM Module 2048MB DIMM 1328MT/s                  | 1        | 1.67%   |
| Unknown RAM 3600 C20 Series 32GB DIMM DDR4 3666MT/s      | 1        | 1.67%   |
| Transcend RAM JM2666HLB-16G 16GB DIMM DDR4 2667MT/s      | 1        | 1.67%   |
| SK hynix RAM HMA82GU7CJR8N-VK 16GB DIMM DDR4             | 1        | 1.67%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s  | 1        | 1.67%   |
| SK hynix RAM HMA41GU6AFR8N-TF 8GB DIMM DDR4 2465MT/s     | 1        | 1.67%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s      | 1        | 1.67%   |
| Samsung RAM M3 78T2863RZS-CF7 1GB DIMM DDR2 800MT/s      | 1        | 1.67%   |
| Patriot RAM PSD48G240082 8GB DIMM DDR4 2400MT/s          | 1        | 1.67%   |
| Patriot RAM PSD48G240081 8GB DIMM DDR4 2800MT/s          | 1        | 1.67%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s           | 1        | 1.67%   |
| Patriot RAM 3000 C16 Series 16GB DIMM DDR4 3200MT/s      | 1        | 1.67%   |
| Micron RAM 16ATF2G64HZ-2G6J1 16GB SODIMM DDR4 2667MT/s   | 1        | 1.67%   |
| Kingston RAM XJ69DF-MIE 8GB DIMM DDR4 2933MT/s           | 1        | 1.67%   |
| Kingston RAM MSI24D4U7S8MB-8 8GB DIMM DDR4 2400MT/s      | 1        | 1.67%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s      | 1        | 1.67%   |
| Kingston RAM 99U5595-003.A00LF 2GB DIMM DDR3             | 1        | 1.67%   |
| Kingston RAM 99U5584-014.A00LF 4096MB DIMM DDR3 1600MT/s | 1        | 1.67%   |
| Kingston RAM 99U5474-010.A00LF 2GB DIMM DDR3 1333MT/s    | 1        | 1.67%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 1.67%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 1.67%   |
| Kingston RAM 99P5474-033.A00LF 2GB DIMM DDR3 1600MT/s    | 1        | 1.67%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s   | 1        | 1.67%   |
| G.Skill RAM F4-3200C16-8GVRB 8GB DIMM DDR4 3200MT/s      | 1        | 1.67%   |
| G.Skill RAM F4-3200C16-8GSXWB 8GB DIMM DDR4 4133MT/s     | 1        | 1.67%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s       | 1        | 1.67%   |
| G.Skill RAM F4-3200C14-16GTZR 16GB DIMM DDR4 3533MT/s    | 1        | 1.67%   |
| G.Skill RAM F4-3000C16-8GVRB 8GB DIMM DDR4 3200MT/s      | 1        | 1.67%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s   | 1        | 1.67%   |
| G.Skill RAM F4-2400C15-4GRR 4GB DIMM DDR4 2133MT/s       | 1        | 1.67%   |
| G.Skill RAM F3-2400C10-4GTX 4GB DIMM DDR3 2400MT/s       | 1        | 1.67%   |
| G.Skill RAM F3-1866C10-8G 8GB DIMM DDR3 1600MT/s         | 1        | 1.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 30       | 61.22%  |
| DDR3    | 14       | 28.57%  |
| Unknown | 2        | 4.08%   |
| SDRAM   | 1        | 2.04%   |
| DDR5    | 1        | 2.04%   |
| DDR2    | 1        | 2.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 48       | 97.96%  |
| SODIMM | 1        | 2.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 23       | 43.4%   |
| 4096  | 13       | 24.53%  |
| 16384 | 9        | 16.98%  |
| 2048  | 4        | 7.55%   |
| 32768 | 3        | 5.66%   |
| 1024  | 1        | 1.89%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 10       | 18.87%  |
| 1600    | 8        | 15.09%  |
| 3600    | 6        | 11.32%  |
| 1333    | 5        | 9.43%   |
| 2667    | 3        | 5.66%   |
| 2400    | 3        | 5.66%   |
| 3666    | 2        | 3.77%   |
| 3466    | 2        | 3.77%   |
| 2933    | 2        | 3.77%   |
| 2133    | 2        | 3.77%   |
| 4800    | 1        | 1.89%   |
| 4133    | 1        | 1.89%   |
| 3733    | 1        | 1.89%   |
| 3533    | 1        | 1.89%   |
| 2800    | 1        | 1.89%   |
| 2481    | 1        | 1.89%   |
| 2465    | 1        | 1.89%   |
| 1328    | 1        | 1.89%   |
| 800     | 1        | 1.89%   |
| Unknown | 1        | 1.89%   |

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


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 6        | 40%     |
| Creative Technology           | 2        | 13.33%  |
| WaveRider Communications      | 1        | 6.67%   |
| Sunplus Innovation Technology | 1        | 6.67%   |
| Microsoft                     | 1        | 6.67%   |
| Microdia                      | 1        | 6.67%   |
| KYE Systems (Mouse Systems)   | 1        | 6.67%   |
| GEMBIRD                       | 1        | 6.67%   |
| ARC International             | 1        | 6.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Logitech Webcam C270                           | 2        | 13.33%  |
| WaveRider USB 2.0 Camera                       | 1        | 6.67%   |
| Sunplus Aukey-PC-LM1E Camera                   | 1        | 6.67%   |
| Microsoft LifeCam Cinema                       | 1        | 6.67%   |
| Microdia Webcam Vitade AF                      | 1        | 6.67%   |
| Logitech Webcam C930e                          | 1        | 6.67%   |
| Logitech Webcam C310                           | 1        | 6.67%   |
| Logitech HD Webcam C910                        | 1        | 6.67%   |
| Logitech BRIO Ultra HD Webcam                  | 1        | 6.67%   |
| KYE Systems (Mouse Systems) Genius FaceCam 320 | 1        | 6.67%   |
| GEMBIRD USB2.0 PC CAMERA                       | 1        | 6.67%   |
| Creative Live! Cam Sync HD [VF0770]            | 1        | 6.67%   |
| Creative Live! Cam Chat HD [VF0700]            | 1        | 6.67%   |
| ARC International Camera                       | 1        | 6.67%   |

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
| 0     | 53       | 89.83%  |
| 1     | 6        | 10.17%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Unassigned class         | 1        | 20%     |
| Net/wireless             | 1        | 20%     |
| Net/ethernet             | 1        | 20%     |
| Graphics card            | 1        | 20%     |
| Communication controller | 1        | 20%     |

