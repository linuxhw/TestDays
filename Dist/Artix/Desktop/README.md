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

Total: 77

| Vendor    | Model                   | Probe                                                      | Date         |
|-----------|-------------------------|------------------------------------------------------------|--------------|
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
| ASRock    | FM2A88X-ITX+            | [2b91e357ca](https://linux-hardware.org/?probe=2b91e357ca) | May 16, 2021 |
| ASRock    | FM2A88X-ITX+            | [057546c50e](https://linux-hardware.org/?probe=057546c50e) | Apr 30, 2021 |
| ASUSTek   | SABERTOOTH 990FX R2.0   | [d1cf148ec4](https://linux-hardware.org/?probe=d1cf148ec4) | Apr 24, 2021 |
| ASUSTek   | ROG STRIX B550-F GAMING | [5527015fb6](https://linux-hardware.org/?probe=5527015fb6) | Apr 08, 2021 |
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
| Artix Rolling  | 34       | 62.96%  |
| Artix          | 15       | 27.78%  |
| Artix 20220123 | 2        | 3.7%    |
| Artix 20210726 | 2        | 3.7%    |
| Artix 20220713 | 1        | 1.85%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| Artix | 52       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                 | Desktops | Percent |
|-----------------------------------------|----------|---------|
| 5.10.8-artix1-1                         | 3        | 4.92%   |
| 5.9.14-artix1-1                         | 2        | 3.28%   |
| 5.8.8-artix1-1                          | 2        | 3.28%   |
| 5.8.12-artix1-1                         | 2        | 3.28%   |
| 5.7.6-artix1-1                          | 2        | 3.28%   |
| 5.7.12-artix1-1                         | 2        | 3.28%   |
| 5.18.16-artix1-1                        | 2        | 3.28%   |
| 5.15.12-artix1-1                        | 2        | 3.28%   |
| 5.12.14-artix1-1                        | 2        | 3.28%   |
| 5.12.12-artix1-1                        | 2        | 3.28%   |
| 5.10.4-artix2-1                         | 2        | 3.28%   |
| 6.1.1-x64v1-xanmod1-1                   | 1        | 1.64%   |
| 6.0.7-artix1-1                          | 1        | 1.64%   |
| 6.0.1-arch1-1                           | 1        | 1.64%   |
| 5.9.8-zen1-1-zen                        | 1        | 1.64%   |
| 5.9.14-zen1-1-zen                       | 1        | 1.64%   |
| 5.9.12-artix1-1                         | 1        | 1.64%   |
| 5.9.10-artix1-1                         | 1        | 1.64%   |
| 5.8.5-xanmod1-1-xanmod                  | 1        | 1.64%   |
| 5.8.14-artix1-1                         | 1        | 1.64%   |
| 5.7.2-artix1-1                          | 1        | 1.64%   |
| 5.4.197-1-lts54                         | 1        | 1.64%   |
| 5.18.9-zen1-1-zen                       | 1        | 1.64%   |
| 5.17.8-258-tkg-pds                      | 1        | 1.64%   |
| 5.17.4-artix1-1                         | 1        | 1.64%   |
| 5.17.12-lqx1-1-lqx                      | 1        | 1.64%   |
| 5.16.3-artix1-1                         | 1        | 1.64%   |
| 5.16.12-artix1-1                        | 1        | 1.64%   |
| 5.16.10-artix1-1                        | 1        | 1.64%   |
| 5.16.1-artix1-1                         | 1        | 1.64%   |
| 5.15.55-rt48-xanmod1-linux-xanmod-rt515 | 1        | 1.64%   |
| 5.15.51-xanmod1-tt-1                    | 1        | 1.64%   |
| 5.15.3-zen1-1-zen                       | 1        | 1.64%   |
| 5.15.2-zen1-1-zen                       | 1        | 1.64%   |
| 5.15.13-zen1-1-zen                      | 1        | 1.64%   |
| 5.14.3-198-tkg-bmq                      | 1        | 1.64%   |
| 5.14.10-artix1-1                        | 1        | 1.64%   |
| 5.13.8-188-tkg-pds                      | 1        | 1.64%   |
| 5.13.4-artix1-1                         | 1        | 1.64%   |
| 5.12.2-artix1-1                         | 1        | 1.64%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.9.14  | 3        | 4.92%   |
| 5.10.8  | 3        | 4.92%   |
| 5.8.8   | 2        | 3.28%   |
| 5.8.12  | 2        | 3.28%   |
| 5.7.6   | 2        | 3.28%   |
| 5.7.12  | 2        | 3.28%   |
| 5.18.16 | 2        | 3.28%   |
| 5.15.12 | 2        | 3.28%   |
| 5.12.14 | 2        | 3.28%   |
| 5.12.12 | 2        | 3.28%   |
| 5.10.4  | 2        | 3.28%   |
| 5.10.15 | 2        | 3.28%   |
| 6.1.1   | 1        | 1.64%   |
| 6.0.7   | 1        | 1.64%   |
| 6.0.1   | 1        | 1.64%   |
| 5.9.8   | 1        | 1.64%   |
| 5.9.12  | 1        | 1.64%   |
| 5.9.10  | 1        | 1.64%   |
| 5.8.5   | 1        | 1.64%   |
| 5.8.14  | 1        | 1.64%   |
| 5.7.2   | 1        | 1.64%   |
| 5.4.197 | 1        | 1.64%   |
| 5.18.9  | 1        | 1.64%   |
| 5.17.8  | 1        | 1.64%   |
| 5.17.4  | 1        | 1.64%   |
| 5.17.12 | 1        | 1.64%   |
| 5.16.3  | 1        | 1.64%   |
| 5.16.12 | 1        | 1.64%   |
| 5.16.10 | 1        | 1.64%   |
| 5.16.1  | 1        | 1.64%   |
| 5.15.55 | 1        | 1.64%   |
| 5.15.51 | 1        | 1.64%   |
| 5.15.3  | 1        | 1.64%   |
| 5.15.2  | 1        | 1.64%   |
| 5.15.13 | 1        | 1.64%   |
| 5.14.3  | 1        | 1.64%   |
| 5.14.10 | 1        | 1.64%   |
| 5.13.8  | 1        | 1.64%   |
| 5.13.4  | 1        | 1.64%   |
| 5.12.2  | 1        | 1.64%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 10       | 16.95%  |
| 5.15    | 7        | 11.86%  |
| 5.9     | 6        | 10.17%  |
| 5.8     | 6        | 10.17%  |
| 5.12    | 5        | 8.47%   |
| 5.7     | 4        | 6.78%   |
| 5.16    | 4        | 6.78%   |
| 5.18    | 3        | 5.08%   |
| 5.17    | 3        | 5.08%   |
| 6.0     | 2        | 3.39%   |
| 5.14    | 2        | 3.39%   |
| 5.13    | 2        | 3.39%   |
| 5.11    | 2        | 3.39%   |
| 6.1     | 1        | 1.69%   |
| 5.4     | 1        | 1.69%   |
| 4.19    | 1        | 1.69%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 52       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| KDE5       | 14       | 25%     |
| GNOME      | 9        | 16.07%  |
| XFCE       | 7        | 12.5%   |
| X-Cinnamon | 6        | 10.71%  |
| Unknown    | 5        | 8.93%   |
| MATE       | 4        | 7.14%   |
| i3         | 2        | 3.57%   |
| Cinnamon   | 2        | 3.57%   |
| bspwm      | 2        | 3.57%   |
| sway       | 1        | 1.79%   |
| openbox    | 1        | 1.79%   |
| LXQt       | 1        | 1.79%   |
| LXDE       | 1        | 1.79%   |
| DWM        | 1        | 1.79%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 38       | 70.37%  |
| Tty     | 10       | 18.52%  |
| Wayland | 4        | 7.41%   |
| Unknown | 2        | 3.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 21       | 38.18%  |
| SDDM    | 17       | 30.91%  |
| LightDM | 13       | 23.64%  |
| XDM     | 1        | 1.82%   |
| SLiM    | 1        | 1.82%   |
| LXDM    | 1        | 1.82%   |
| GDM     | 1        | 1.82%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 18       | 34.62%  |
| ru_RU   | 6        | 11.54%  |
| fr_FR   | 5        | 9.62%   |
| C       | 4        | 7.69%   |
| Unknown | 4        | 7.69%   |
| pt_PT   | 2        | 3.85%   |
| de_DE   | 2        | 3.85%   |
| tr_TR   | 1        | 1.92%   |
| lt_LT   | 1        | 1.92%   |
| ja_JP   | 1        | 1.92%   |
| it_IT   | 1        | 1.92%   |
| es_MX   | 1        | 1.92%   |
| es_AR   | 1        | 1.92%   |
| en_IE   | 1        | 1.92%   |
| en_GB   | 1        | 1.92%   |
| en_AU   | 1        | 1.92%   |
| el_GR   | 1        | 1.92%   |
| bg_BG   | 1        | 1.92%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 35       | 66.04%  |
| BIOS | 18       | 33.96%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 34       | 65.38%  |
| Btrfs | 13       | 25%     |
| Xfs   | 2        | 3.85%   |
| F2fs  | 2        | 3.85%   |
| Jfs   | 1        | 1.92%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 40       | 74.07%  |
| Unknown | 10       | 18.52%  |
| MBR     | 4        | 7.41%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 38       | 70.37%  |
| Yes       | 16       | 29.63%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 38       | 71.7%   |
| Yes       | 15       | 28.3%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 15       | 28.85%  |
| ASUSTek Computer    | 15       | 28.85%  |
| MSI                 | 9        | 17.31%  |
| ASRock              | 6        | 11.54%  |
| Hewlett-Packard     | 2        | 3.85%   |
| Dell                | 2        | 3.85%   |
| Intel               | 1        | 1.92%   |
| Biostar             | 1        | 1.92%   |
| Alienware           | 1        | 1.92%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| MSI MS-7C02                    | 2        | 3.85%   |
| MSI MS-7A38                    | 2        | 3.85%   |
| Gigabyte 970A-DS3P             | 2        | 3.85%   |
| MSI MS-7C89                    | 1        | 1.92%   |
| MSI MS-7C56                    | 1        | 1.92%   |
| MSI MS-7C37                    | 1        | 1.92%   |
| MSI MS-7B79                    | 1        | 1.92%   |
| MSI MS-7A69                    | 1        | 1.92%   |
| Intel DX58SO2 AAG10925-205     | 1        | 1.92%   |
| HP Compaq 8200 Elite SFF PC    | 1        | 1.92%   |
| HP 280 G1 MT                   | 1        | 1.92%   |
| Gigabyte Z77X-UD3H             | 1        | 1.92%   |
| Gigabyte X570 AORUS ULTRA      | 1        | 1.92%   |
| Gigabyte X570 AORUS ELITE WIFI | 1        | 1.92%   |
| Gigabyte X570 AORUS ELITE      | 1        | 1.92%   |
| Gigabyte X399 AORUS XTREME     | 1        | 1.92%   |
| Gigabyte P55-USB3              | 1        | 1.92%   |
| Gigabyte HA65M-D2H-B3          | 1        | 1.92%   |
| Gigabyte H61MA-D3V             | 1        | 1.92%   |
| Gigabyte B550M AORUS PRO       | 1        | 1.92%   |
| Gigabyte B450 AORUS PRO WIFI   | 1        | 1.92%   |
| Gigabyte AB350M-DS3H V2        | 1        | 1.92%   |
| Gigabyte 990FXA-UD5            | 1        | 1.92%   |
| Gigabyte 990FXA-UD3 R5         | 1        | 1.92%   |
| Dell OptiPlex 5080             | 1        | 1.92%   |
| Dell Inspiron 530              | 1        | 1.92%   |
| Biostar G31D-M7                | 1        | 1.92%   |
| ASUS TUF Gaming X570-PLUS      | 1        | 1.92%   |
| ASUS TUF B450-PLUS GAMING      | 1        | 1.92%   |
| ASUS SABERTOOTH 990FX R2.0     | 1        | 1.92%   |
| ASUS ROG STRIX X570-F GAMING   | 1        | 1.92%   |
| ASUS ROG STRIX B550-F GAMING   | 1        | 1.92%   |
| ASUS ROG Maximus XI HERO       | 1        | 1.92%   |
| ASUS Pro WS X570-ACE           | 1        | 1.92%   |
| ASUS PRIME X370-PRO            | 1        | 1.92%   |
| ASUS PRIME B450M-A             | 1        | 1.92%   |
| ASUS PRIME B350M-A             | 1        | 1.92%   |
| ASUS P8H61-M LX3 R2.0          | 1        | 1.92%   |
| ASUS P8B75-M LX PLUS           | 1        | 1.92%   |
| ASUS M5A97 LE R2.0             | 1        | 1.92%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Gigabyte X570         | 3        | 5.77%   |
| ASUS ROG              | 3        | 5.77%   |
| ASUS PRIME            | 3        | 5.77%   |
| MSI MS-7C02           | 2        | 3.85%   |
| MSI MS-7A38           | 2        | 3.85%   |
| Gigabyte 970A-DS3P    | 2        | 3.85%   |
| ASUS TUF              | 2        | 3.85%   |
| MSI MS-7C89           | 1        | 1.92%   |
| MSI MS-7C56           | 1        | 1.92%   |
| MSI MS-7C37           | 1        | 1.92%   |
| MSI MS-7B79           | 1        | 1.92%   |
| MSI MS-7A69           | 1        | 1.92%   |
| Intel DX58SO2         | 1        | 1.92%   |
| HP Compaq             | 1        | 1.92%   |
| HP 280                | 1        | 1.92%   |
| Gigabyte Z77X-UD3H    | 1        | 1.92%   |
| Gigabyte X399         | 1        | 1.92%   |
| Gigabyte P55-USB3     | 1        | 1.92%   |
| Gigabyte HA65M-D2H-B3 | 1        | 1.92%   |
| Gigabyte H61MA-D3V    | 1        | 1.92%   |
| Gigabyte B550M        | 1        | 1.92%   |
| Gigabyte B450         | 1        | 1.92%   |
| Gigabyte AB350M-DS3H  | 1        | 1.92%   |
| Gigabyte 990FXA-UD5   | 1        | 1.92%   |
| Gigabyte 990FXA-UD3   | 1        | 1.92%   |
| Dell OptiPlex         | 1        | 1.92%   |
| Dell Inspiron         | 1        | 1.92%   |
| Biostar G31D-M7       | 1        | 1.92%   |
| ASUS SABERTOOTH       | 1        | 1.92%   |
| ASUS Pro              | 1        | 1.92%   |
| ASUS P8H61-M          | 1        | 1.92%   |
| ASUS P8B75-M          | 1        | 1.92%   |
| ASUS M5A97            | 1        | 1.92%   |
| ASUS G11CD            | 1        | 1.92%   |
| ASUS All              | 1        | 1.92%   |
| ASRock X570           | 1        | 1.92%   |
| ASRock H310CM-DVS     | 1        | 1.92%   |
| ASRock FM2A88X-ITX+   | 1        | 1.92%   |
| ASRock B460           | 1        | 1.92%   |
| ASRock B450           | 1        | 1.92%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 11       | 21.15%  |
| 2020 | 8        | 15.38%  |
| 2018 | 7        | 13.46%  |
| 2012 | 6        | 11.54%  |
| 2017 | 5        | 9.62%   |
| 2013 | 5        | 9.62%   |
| 2015 | 3        | 5.77%   |
| 2011 | 2        | 3.85%   |
| 2010 | 2        | 3.85%   |
| 2008 | 2        | 3.85%   |
| 2016 | 1        | 1.92%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 52       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 52       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 52       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 22       | 41.51%  |
| 8.01-16.0   | 13       | 24.53%  |
| 32.01-64.0  | 8        | 15.09%  |
| 3.01-4.0    | 4        | 7.55%   |
| 64.01-256.0 | 4        | 7.55%   |
| 4.01-8.0    | 1        | 1.89%   |
| 1.01-2.0    | 1        | 1.89%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 15       | 26.79%  |
| 2.01-3.0   | 12       | 21.43%  |
| 3.01-4.0   | 10       | 17.86%  |
| 1.01-2.0   | 10       | 17.86%  |
| 8.01-16.0  | 3        | 5.36%   |
| 0.51-1.0   | 3        | 5.36%   |
| 0.01-0.5   | 2        | 3.57%   |
| 16.01-24.0 | 1        | 1.79%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 23       | 42.59%  |
| 3      | 12       | 22.22%  |
| 1      | 9        | 16.67%  |
| 4      | 6        | 11.11%  |
| 6      | 2        | 3.7%    |
| 8      | 1        | 1.85%   |
| 7      | 1        | 1.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 39       | 75%     |
| Yes       | 13       | 25%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 52       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 27       | 51.92%  |
| Yes       | 25       | 48.08%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 31       | 59.62%  |
| Yes       | 21       | 40.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 8        | 15.09%  |
| Germany     | 8        | 15.09%  |
| France      | 7        | 13.21%  |
| Russia      | 6        | 11.32%  |
| Greece      | 3        | 5.66%   |
| Switzerland | 2        | 3.77%   |
| Poland      | 2        | 3.77%   |
| Finland     | 2        | 3.77%   |
| Bulgaria    | 2        | 3.77%   |
| Ukraine     | 1        | 1.89%   |
| UK          | 1        | 1.89%   |
| Turkey      | 1        | 1.89%   |
| Mexico      | 1        | 1.89%   |
| Lithuania   | 1        | 1.89%   |
| Japan       | 1        | 1.89%   |
| Italy       | 1        | 1.89%   |
| Iran        | 1        | 1.89%   |
| Hong Kong   | 1        | 1.89%   |
| Canada      | 1        | 1.89%   |
| Austria     | 1        | 1.89%   |
| Australia   | 1        | 1.89%   |
| Argentina   | 1        | 1.89%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Paris                  | 3        | 5.36%   |
| Moscow                 | 2        | 3.57%   |
| Helsinki               | 2        | 3.57%   |
| Frankfurt am Main      | 2        | 3.57%   |
| Bern                   | 2        | 3.57%   |
| Athens                 | 2        | 3.57%   |
| Wettringen             | 1        | 1.79%   |
| Vladivostok            | 1        | 1.79%   |
| Vilnius                | 1        | 1.79%   |
| Vienna                 | 1        | 1.79%   |
| Upper Norwood          | 1        | 1.79%   |
| Ufa                    | 1        | 1.79%   |
| Toronto                | 1        | 1.79%   |
| Thessaloniki           | 1        | 1.79%   |
| Tehran                 | 1        | 1.79%   |
| Sydney                 | 1        | 1.79%   |
| Stein                  | 1        | 1.79%   |
| Stavropol              | 1        | 1.79%   |
| Statesboro             | 1        | 1.79%   |
| Sofia                  | 1        | 1.79%   |
| Snohomish              | 1        | 1.79%   |
| Shavertown             | 1        | 1.79%   |
| San Miguel de Tucumán | 1        | 1.79%   |
| Riverview              | 1        | 1.79%   |
| Rexburg                | 1        | 1.79%   |
| Plovdiv                | 1        | 1.79%   |
| Maebashi               | 1        | 1.79%   |
| Lublin                 | 1        | 1.79%   |
| Kłodzko               | 1        | 1.79%   |
| Koga                   | 1        | 1.79%   |
| Kazan’               | 1        | 1.79%   |
| Hurricane              | 1        | 1.79%   |
| Gochsheim              | 1        | 1.79%   |
| Factoryville           | 1        | 1.79%   |
| Essen                  | 1        | 1.79%   |
| Dnipro                 | 1        | 1.79%   |
| Clarks Summit          | 1        | 1.79%   |
| Ciudad Victoria        | 1        | 1.79%   |
| Chatenois              | 1        | 1.79%   |
| Charlotte              | 1        | 1.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 24       | 45     | 20.51%  |
| Seagate             | 20       | 25     | 17.09%  |
| Samsung Electronics | 15       | 24     | 12.82%  |
| Kingston            | 11       | 12     | 9.4%    |
| Toshiba             | 7        | 8      | 5.98%   |
| Crucial             | 7        | 11     | 5.98%   |
| SanDisk             | 5        | 7      | 4.27%   |
| Intel               | 4        | 7      | 3.42%   |
| Maxtor              | 2        | 2      | 1.71%   |
| JMicron Technology  | 2        | 2      | 1.71%   |
| Hitachi             | 2        | 2      | 1.71%   |
| Corsair             | 2        | 2      | 1.71%   |
| A-DATA Technology   | 2        | 2      | 1.71%   |
| Transcend           | 1        | 1      | 0.85%   |
| SPCC                | 1        | 1      | 0.85%   |
| SK hynix            | 1        | 1      | 0.85%   |
| PNY                 | 1        | 1      | 0.85%   |
| Plextor             | 1        | 1      | 0.85%   |
| Phison Electronics  | 1        | 1      | 0.85%   |
| Phison              | 1        | 1      | 0.85%   |
| Netac               | 1        | 1      | 0.85%   |
| Linux               | 1        | 1      | 0.85%   |
| HGST                | 1        | 2      | 0.85%   |
| Hewlett-Packard     | 1        | 1      | 0.85%   |
| GOODRAM             | 1        | 1      | 0.85%   |
| China               | 1        | 1      | 0.85%   |
| AMD                 | 1        | 1      | 0.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| WDC WD10EZEX-08WN4A0 1TB                            | 3        | 2.22%   |
| Toshiba DT01ACA100 1TB                              | 3        | 2.22%   |
| Seagate ST3500418AS 500GB                           | 3        | 2.22%   |
| Seagate ST1000DM010-2EP102 1TB                      | 3        | 2.22%   |
| Samsung SSD 860 EVO 250GB                           | 3        | 2.22%   |
| WDC WD80EZAZ-11TDBA0 8TB                            | 2        | 1.48%   |
| WDC WD40EZRZ-00WN9B0 4TB                            | 2        | 1.48%   |
| WDC WD10EZEX-22MFCA0 1TB                            | 2        | 1.48%   |
| WDC WD100EMAZ-00WJTA0 10TB                          | 2        | 1.48%   |
| Seagate ST500DM002-1BD142 500GB                     | 2        | 1.48%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2        | 1.48%   |
| Samsung SSD 970 EVO 1TB                             | 2        | 1.48%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 2        | 1.48%   |
| Kingston SA400S37120G 120GB SSD                     | 2        | 1.48%   |
| Crucial CT240BX500SSD1 240GB                        | 2        | 1.48%   |
| WDC WDS500G2B0C-00PXH0 500GB                        | 1        | 0.74%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1        | 0.74%   |
| WDC WDS256G1X0C-00ENX0 256GB                        | 1        | 0.74%   |
| WDC WDS100T2B0C-00PXH0 1TB                          | 1        | 0.74%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 1        | 0.74%   |
| WDC WDBNCE5000PNC 500GB SSD                         | 1        | 0.74%   |
| WDC WD6001FZWX-00A2VA0 6TB                          | 1        | 0.74%   |
| WDC WD5003ABYX-18WERA0 500GB                        | 1        | 0.74%   |
| WDC WD5000LPVX-00V0TT0 500GB                        | 1        | 0.74%   |
| WDC WD5000AAKX-60U6AA0 500GB                        | 1        | 0.74%   |
| WDC WD4003FZEX-00Z4SA0 4TB                          | 1        | 0.74%   |
| WDC WD4003FFBX-68MU3N0 4TB                          | 1        | 0.74%   |
| WDC WD3200AAKX-00ERMA0 320GB                        | 1        | 0.74%   |
| WDC WD30EZRX-00DC0B0 3TB                            | 1        | 0.74%   |
| WDC WD30EFRX-68EUZN0 3TB                            | 1        | 0.74%   |
| WDC WD2500HHTZ-04N21V0 250GB                        | 1        | 0.74%   |
| WDC WD20EZRX-00D8PB0 2TB                            | 1        | 0.74%   |
| WDC WD20EZBX-00AYRA0 2TB                            | 1        | 0.74%   |
| WDC WD20EARS-00MVWB0 2TB                            | 1        | 0.74%   |
| WDC WD2003FZEX-00SRLA0 2TB                          | 1        | 0.74%   |
| WDC WD15EARS-22MVWB0 1TB                            | 1        | 0.74%   |
| WDC WD10EZRZ-00HTKB0 1TB                            | 1        | 0.74%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 1        | 0.74%   |
| WDC WD1003FZEX-00K3CA0 1TB                          | 1        | 0.74%   |
| Transcend TS1TMTE220S 1TB                           | 1        | 0.74%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Desktops | Drives | Percent |
|--------------------|----------|--------|---------|
| WDC                | 21       | 37     | 38.89%  |
| Seagate            | 20       | 25     | 37.04%  |
| Toshiba            | 7        | 8      | 12.96%  |
| Maxtor             | 2        | 2      | 3.7%    |
| Hitachi            | 2        | 2      | 3.7%    |
| JMicron Technology | 1        | 1      | 1.85%   |
| HGST               | 1        | 2      | 1.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 9        | 10     | 21.95%  |
| Samsung Electronics | 8        | 11     | 19.51%  |
| Crucial             | 7        | 11     | 17.07%  |
| WDC                 | 3        | 5      | 7.32%   |
| SanDisk             | 2        | 2      | 4.88%   |
| Intel               | 2        | 3      | 4.88%   |
| A-DATA Technology   | 2        | 2      | 4.88%   |
| SPCC                | 1        | 1      | 2.44%   |
| Plextor             | 1        | 1      | 2.44%   |
| Netac               | 1        | 1      | 2.44%   |
| Linux               | 1        | 1      | 2.44%   |
| JMicron Technology  | 1        | 1      | 2.44%   |
| GOODRAM             | 1        | 1      | 2.44%   |
| China               | 1        | 1      | 2.44%   |
| AMD                 | 1        | 1      | 2.44%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 43       | 77     | 43%     |
| SSD  | 35       | 52     | 35%     |
| NVMe | 22       | 35     | 22%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 49       | 126    | 66.22%  |
| NVMe | 22       | 35     | 29.73%  |
| SAS  | 3        | 3      | 4.05%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 39       | 63     | 44.83%  |
| 0.51-1.0   | 27       | 38     | 31.03%  |
| 1.01-2.0   | 9        | 10     | 10.34%  |
| 3.01-4.0   | 4        | 4      | 4.6%    |
| 2.01-3.0   | 4        | 4      | 4.6%    |
| 4.01-10.0  | 4        | 10     | 4.6%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 11       | 20.37%  |
| 2001-3000      | 10       | 18.52%  |
| 1001-2000      | 10       | 18.52%  |
| 101-250        | 9        | 16.67%  |
| 501-1000       | 8        | 14.81%  |
| 251-500        | 4        | 7.41%   |
| 51-100         | 2        | 3.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 13       | 23.64%  |
| 251-500        | 9        | 16.36%  |
| More than 3000 | 7        | 12.73%  |
| 1001-2000      | 7        | 12.73%  |
| 1-20           | 7        | 12.73%  |
| 101-250        | 6        | 10.91%  |
| 21-50          | 2        | 3.64%   |
| 2001-3000      | 2        | 3.64%   |
| 51-100         | 2        | 3.64%   |

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
| Maxtor 6Y080M0 81GB              | 1        | 1      | 8.33%   |
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
| Works    | 34       | 91     | 52.31%  |
| Detected | 20       | 60     | 30.77%  |
| Malfunc  | 11       | 13     | 16.92%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| AMD                         | 31       | 36.05%  |
| Intel                       | 22       | 25.58%  |
| Samsung Electronics         | 9        | 10.47%  |
| SanDisk                     | 5        | 5.81%   |
| Marvell Technology Group    | 5        | 5.81%   |
| Phison Electronics          | 4        | 4.65%   |
| ASMedia Technology          | 3        | 3.49%   |
| Silicon Motion              | 2        | 2.33%   |
| Kingston Technology Company | 2        | 2.33%   |
| SK hynix                    | 1        | 1.16%   |
| JMicron Technology          | 1        | 1.16%   |
| Broadcom / LSI              | 1        | 1.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 21       | 19.81%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 8        | 7.55%   |
| AMD 400 Series Chipset SATA Controller                                         | 7        | 6.6%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 6        | 5.66%   |
| AMD 300 Series Chipset SATA Controller                                         | 4        | 3.77%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 3        | 2.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3        | 2.83%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3        | 2.83%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3        | 2.83%   |
| AMD 500 Series Chipset SATA Controller                                         | 3        | 2.83%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2        | 1.89%   |
| Phison E12 NVMe Controller                                                     | 2        | 1.89%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2        | 1.89%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2        | 1.89%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2        | 1.89%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2        | 1.89%   |
| SK hynix Non-Volatile memory controller                                        | 1        | 0.94%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1        | 0.94%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1        | 0.94%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1        | 0.94%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1        | 0.94%   |
| SanDisk WD Black NVMe SSD                                                      | 1        | 0.94%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 0.94%   |
| Phison PS5013 E13 NVMe Controller                                              | 1        | 0.94%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 0.94%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                          | 1        | 0.94%   |
| Marvell Group 88SE912x IDE Controller                                          | 1        | 0.94%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                           | 1        | 0.94%   |
| Kingston Company Company Non-Volatile memory controller                        | 1        | 0.94%   |
| Kingston Company A2000 NVMe SSD                                                | 1        | 0.94%   |
| JMicron JMB363 SATA/IDE Controller                                             | 1        | 0.94%   |
| Intel SSD 660P Series                                                          | 1        | 0.94%   |
| Intel SSD 600P Series                                                          | 1        | 0.94%   |
| Intel SATA Controller [RAID mode]                                              | 1        | 0.94%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1        | 0.94%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1        | 0.94%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 0.94%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]            | 1        | 0.94%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 1        | 0.94%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1        | 0.94%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 49       | 60.49%  |
| NVMe | 22       | 27.16%  |
| IDE  | 8        | 9.88%   |
| RAID | 1        | 1.23%   |
| SAS  | 1        | 1.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 31       | 59.62%  |
| Intel  | 21       | 40.38%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD FX-8350 Eight-Core Processor                | 4        | 7.69%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 3        | 5.77%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 3        | 5.77%   |
| AMD Ryzen 5 2600X Six-Core Processor            | 3        | 5.77%   |
| Intel Core i7-9700K CPU @ 3.60GHz               | 2        | 3.85%   |
| Intel Core i5-2500 CPU @ 3.30GHz                | 2        | 3.85%   |
| Intel Core i5-10400F CPU @ 2.90GHz              | 2        | 3.85%   |
| AMD Ryzen 7 5700G with Radeon Graphics          | 2        | 3.85%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 2        | 3.85%   |
| AMD Ryzen 5 3600 6-Core Processor               | 2        | 3.85%   |
| Intel Core i7-9700F CPU @ 3.00GHz               | 1        | 1.92%   |
| Intel Core i7-4790K CPU @ 4.00GHz               | 1        | 1.92%   |
| Intel Core i7 CPU 970 @ 3.20GHz                 | 1        | 1.92%   |
| Intel Core i5-7600K CPU @ 3.80GHz               | 1        | 1.92%   |
| Intel Core i5-6600K CPU @ 3.50GHz               | 1        | 1.92%   |
| Intel Core i5-6400 CPU @ 2.70GHz                | 1        | 1.92%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 1        | 1.92%   |
| Intel Core i5-3330 CPU @ 3.00GHz                | 1        | 1.92%   |
| Intel Core i5-2310 CPU @ 2.90GHz                | 1        | 1.92%   |
| Intel Core i5-10500T CPU @ 2.30GHz              | 1        | 1.92%   |
| Intel Core i5 CPU 660 @ 3.33GHz                 | 1        | 1.92%   |
| Intel Core i3-2120 CPU @ 3.30GHz                | 1        | 1.92%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz            | 1        | 1.92%   |
| Intel Core 2 Duo CPU E4600 @ 2.40GHz            | 1        | 1.92%   |
| Intel Celeron CPU G1840 @ 2.80GHz               | 1        | 1.92%   |
| AMD Ryzen Threadripper 2990WX 32-Core Processor | 1        | 1.92%   |
| AMD Ryzen 9 3900XT 12-Core Processor            | 1        | 1.92%   |
| AMD Ryzen 7 5800X 8-Core Processor              | 1        | 1.92%   |
| AMD Ryzen 7 1700 Eight-Core Processor           | 1        | 1.92%   |
| AMD Ryzen 5 5600X 6-Core Processor              | 1        | 1.92%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 1        | 1.92%   |
| AMD Ryzen 5 1600 Six-Core Processor             | 1        | 1.92%   |
| AMD Ryzen 5 1500X Quad-Core Processor           | 1        | 1.92%   |
| AMD Ryzen 3 1200 Quad-Core Processor            | 1        | 1.92%   |
| AMD Phenom II X4 955 Processor                  | 1        | 1.92%   |
| AMD FX-6300 Six-Core Processor                  | 1        | 1.92%   |
| AMD A10-7870K Radeon R7, 12 Compute Cores 4C+8G | 1        | 1.92%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 12       | 23.08%  |
| AMD Ryzen 7            | 9        | 17.31%  |
| AMD Ryzen 5            | 9        | 17.31%  |
| Intel Core i7          | 5        | 9.62%   |
| AMD FX                 | 5        | 9.62%   |
| AMD Ryzen 9            | 4        | 7.69%   |
| Intel Core 2 Duo       | 2        | 3.85%   |
| Intel Core i3          | 1        | 1.92%   |
| Intel Celeron          | 1        | 1.92%   |
| AMD Ryzen Threadripper | 1        | 1.92%   |
| AMD Ryzen 3            | 1        | 1.92%   |
| AMD Phenom II X4       | 1        | 1.92%   |
| AMD A10                | 1        | 1.92%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 15       | 28.85%  |
| 8      | 12       | 23.08%  |
| 6      | 12       | 23.08%  |
| 2      | 6        | 11.54%  |
| 12     | 4        | 7.69%   |
| 3      | 2        | 3.85%   |
| 32     | 1        | 1.92%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 52       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 36       | 69.23%  |
| 1      | 16       | 30.77%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 52       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 11       | 20.37%  |
| 0x08701013 | 5        | 9.26%   |
| 0x0800820d | 5        | 9.26%   |
| 0x206a7    | 3        | 5.56%   |
| 0x08701021 | 3        | 5.56%   |
| 0x06000822 | 3        | 5.56%   |
| 0xa0655    | 2        | 3.7%    |
| 0x906ed    | 2        | 3.7%    |
| 0x506e3    | 2        | 3.7%    |
| 0x306c3    | 2        | 3.7%    |
| 0x06000852 | 2        | 3.7%    |
| 0xa0653    | 1        | 1.85%   |
| 0x906e9    | 1        | 1.85%   |
| 0x6fd      | 1        | 1.85%   |
| 0x306a9    | 1        | 1.85%   |
| 0x206c2    | 1        | 1.85%   |
| 0x20652    | 1        | 1.85%   |
| 0x1067a    | 1        | 1.85%   |
| 0x0a50000b | 1        | 1.85%   |
| 0x0a201016 | 1        | 1.85%   |
| 0x0a201009 | 1        | 1.85%   |
| 0x0800820b | 1        | 1.85%   |
| 0x08001138 | 1        | 1.85%   |
| 0x08001129 | 1        | 1.85%   |
| 0x06003106 | 1        | 1.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen 2       | 9        | 17.31%  |
| Zen+        | 7        | 13.46%  |
| Zen 3       | 5        | 9.62%   |
| Piledriver  | 5        | 9.62%   |
| SandyBridge | 4        | 7.69%   |
| KabyLake    | 4        | 7.69%   |
| Zen         | 3        | 5.77%   |
| CometLake   | 3        | 5.77%   |
| Westmere    | 2        | 3.85%   |
| Skylake     | 2        | 3.85%   |
| IvyBridge   | 2        | 3.85%   |
| Haswell     | 2        | 3.85%   |
| Steamroller | 1        | 1.92%   |
| Penryn      | 1        | 1.92%   |
| K10         | 1        | 1.92%   |
| Core        | 1        | 1.92%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 29       | 51.79%  |
| Nvidia | 21       | 37.5%   |
| Intel  | 6        | 10.71%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 8        | 13.79%  |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 6        | 10.34%  |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 3.45%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 2        | 3.45%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 3.45%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 3.45%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 3.45%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 1.72%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 1.72%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 1.72%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 1.72%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 1.72%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.72%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 1.72%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.72%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 1.72%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.72%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 1.72%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 1.72%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.72%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                           | 1        | 1.72%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.72%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 1.72%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 1        | 1.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 1.72%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.72%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 1.72%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.72%   |
| AMD Vega 20 [Radeon VII]                                                    | 1        | 1.72%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 1        | 1.72%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1        | 1.72%   |
| AMD Redwood XT [Radeon HD 5670/5690/5730]                                   | 1        | 1.72%   |
| AMD Pitcairn XT [Radeon HD 7870 GHz Edition]                                | 1        | 1.72%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 1        | 1.72%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 1        | 1.72%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 1        | 1.72%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 1        | 1.72%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 1        | 1.72%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                          | 1        | 1.72%   |
| AMD Cayman PRO [Radeon HD 6950]                                             | 1        | 1.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x AMD      | 25       | 47.17%  |
| 1 x Nvidia   | 19       | 35.85%  |
| 1 x Intel    | 5        | 9.43%   |
| 2 x AMD      | 2        | 3.77%   |
| AMD + Nvidia | 2        | 3.77%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 39       | 72.22%  |
| Proprietary | 15       | 27.78%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 16       | 28.57%  |
| 7.01-8.0   | 14       | 25%     |
| 3.01-4.0   | 9        | 16.07%  |
| 1.01-2.0   | 7        | 12.5%   |
| 0.51-1.0   | 5        | 8.93%   |
| 8.01-16.0  | 3        | 5.36%   |
| 5.01-6.0   | 1        | 1.79%   |
| 0.01-0.5   | 1        | 1.79%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 11       | 15.49%  |
| Acer                 | 9        | 12.68%  |
| Philips              | 7        | 9.86%   |
| Goldstar             | 7        | 9.86%   |
| AOC                  | 7        | 9.86%   |
| BenQ                 | 5        | 7.04%   |
| Dell                 | 4        | 5.63%   |
| ASUSTek Computer     | 4        | 5.63%   |
| Ancor Communications | 2        | 2.82%   |
| ViewSonic            | 1        | 1.41%   |
| Vestel Elektronik    | 1        | 1.41%   |
| Sony                 | 1        | 1.41%   |
| Packard Bell         | 1        | 1.41%   |
| MSI                  | 1        | 1.41%   |
| KTC                  | 1        | 1.41%   |
| Jean                 | 1        | 1.41%   |
| Iiyama               | 1        | 1.41%   |
| Idek Iiyama          | 1        | 1.41%   |
| HVR                  | 1        | 1.41%   |
| Hitachi              | 1        | 1.41%   |
| Hewlett-Packard      | 1        | 1.41%   |
| Envision Peripherals | 1        | 1.41%   |
| CTV                  | 1        | 1.41%   |
| Belinea              | 1        | 1.41%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| AOC F22 AOC2200 1920x1080 476x268mm 21.5-inch                           | 2        | 2.67%   |
| Ancor Communications ASUS PB277 ACI27B5 2560x1440 597x336mm 27.0-inch   | 2        | 2.67%   |
| ViewSonic LCD Monitor VX2452 Series 3840x1080                           | 1        | 1.33%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch    | 1        | 1.33%   |
| Sony TV SNY7001 1920x1080                                               | 1        | 1.33%   |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch       | 1        | 1.33%   |
| Samsung Electronics T24B301 SAM098E 1920x1080 521x293mm 23.5-inch       | 1        | 1.33%   |
| Samsung Electronics SyncMaster SAM047D 1360x768 410x230mm 18.5-inch     | 1        | 1.33%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch       | 1        | 1.33%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch       | 1        | 1.33%   |
| Samsung Electronics S24A31x SAM7114 1920x1080 527x296mm 23.8-inch       | 1        | 1.33%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 1        | 1.33%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 1        | 1.33%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1872x1053mm 84.6-inch | 1        | 1.33%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch       | 1        | 1.33%   |
| Samsung Electronics C27FG7x SAM0E41 1920x1080 598x337mm 27.0-inch       | 1        | 1.33%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch       | 1        | 1.33%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 1        | 1.33%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch                | 1        | 1.33%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch                 | 1        | 1.33%   |
| Philips PHL 245E1 PHLC20B 2560x1440 527x296mm 23.8-inch                 | 1        | 1.33%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 1        | 1.33%   |
| Philips PHL 220V8 PHLC218 1920x1080 477x268mm 21.5-inch                 | 1        | 1.33%   |
| Philips 247ELH PHLC085 1920x1080 521x293mm 23.5-inch                    | 1        | 1.33%   |
| Philips 226VL PHLC081 1920x1080 480x268mm 21.6-inch                     | 1        | 1.33%   |
| Packard Bell Viseo203DX PKB0378 1600x900 432x240mm 19.5-inch            | 1        | 1.33%   |
| MSI Optix G241VC MSI1462 1920x1080 521x294mm 23.6-inch                  | 1        | 1.33%   |
| KTC 24'TV KTC2400 1600x900 516x323mm 24.0-inch                          | 1        | 1.33%   |
| Jean JT198x6-7 JEN17C6 1280x1024 376x301mm 19.0-inch                    | 1        | 1.33%   |
| Iiyama PL3461WQ IVM7615 3440x1440 800x335mm 34.1-inch                   | 1        | 1.33%   |
| Idek Iiyama LCD Monitor PL2488H                                         | 1        | 1.33%   |
| HVR HTC-VIVE HVRAA01 2160x1200                                          | 1        | 1.33%   |
| Hitachi HISENSE HEC0030 1920x1080 580x330mm 26.3-inch                   | 1        | 1.33%   |
| Hewlett-Packard LA1951 HWP285B 1280x1024 380x300mm 19.1-inch            | 1        | 1.33%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                | 1        | 1.33%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                 | 1        | 1.33%   |
| Goldstar MP59G GSM5B35 1920x1080 480x270mm 21.7-inch                    | 1        | 1.33%   |
| Goldstar LG ULTRAGEAR GSM5B7F 2560x1440 600x340mm 27.2-inch             | 1        | 1.33%   |
| Goldstar HDR WFHD GSM7715 2560x1080 798x334mm 34.1-inch                 | 1        | 1.33%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                  | 1        | 1.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 34       | 49.28%  |
| 3840x2160 (4K)     | 11       | 15.94%  |
| 2560x1440 (QHD)    | 7        | 10.14%  |
| 3440x1440          | 2        | 2.9%    |
| 2560x1080          | 2        | 2.9%    |
| 1280x1024 (SXGA)   | 2        | 2.9%    |
| Unknown            | 2        | 2.9%    |
| 3840x1080          | 1        | 1.45%   |
| 3600x1080          | 1        | 1.45%   |
| 2160x1200          | 1        | 1.45%   |
| 1920x1200 (WUXGA)  | 1        | 1.45%   |
| 1680x1050 (WSXGA+) | 1        | 1.45%   |
| 1600x900 (HD+)     | 1        | 1.45%   |
| 1360x768           | 1        | 1.45%   |
| 1280x960           | 1        | 1.45%   |
| 1024x768 (XGA)     | 1        | 1.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 12       | 17.65%  |
| 23      | 12       | 17.65%  |
| 24      | 11       | 16.18%  |
| 21      | 8        | 11.76%  |
| 84      | 4        | 5.88%   |
| 34      | 4        | 5.88%   |
| Unknown | 4        | 5.88%   |
| 31      | 3        | 4.41%   |
| 19      | 3        | 4.41%   |
| 32      | 2        | 2.94%   |
| 72      | 1        | 1.47%   |
| 52      | 1        | 1.47%   |
| 20      | 1        | 1.47%   |
| 18      | 1        | 1.47%   |
| 15      | 1        | 1.47%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 32       | 47.76%  |
| 401-500     | 10       | 14.93%  |
| 701-800     | 6        | 8.96%   |
| 601-700     | 5        | 7.46%   |
| 1501-2000   | 5        | 7.46%   |
| Unknown     | 4        | 5.97%   |
| 351-400     | 3        | 4.48%   |
| 301-350     | 1        | 1.49%   |
| 1001-1500   | 1        | 1.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 46       | 76.67%  |
| 21/9    | 4        | 6.67%   |
| 5/4     | 3        | 5%      |
| 16/10   | 3        | 5%      |
| Unknown | 3        | 5%      |
| 4/3     | 1        | 1.67%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 28       | 41.18%  |
| 301-350        | 12       | 17.65%  |
| 351-500        | 9        | 13.24%  |
| More than 1000 | 6        | 8.82%   |
| 151-200        | 5        | 7.35%   |
| Unknown        | 4        | 5.88%   |
| 251-300        | 2        | 2.94%   |
| 141-150        | 1        | 1.47%   |
| 101-110        | 1        | 1.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 36       | 56.25%  |
| 101-120 | 15       | 23.44%  |
| 121-160 | 5        | 7.81%   |
| Unknown | 4        | 6.25%   |
| 1-50    | 2        | 3.13%   |
| 161-240 | 2        | 3.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 38       | 71.7%   |
| 2     | 11       | 20.75%  |
| 3     | 3        | 5.66%   |
| 4     | 1        | 1.89%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 32       | 45.71%  |
| Intel                                 | 21       | 30%     |
| TP-Link                               | 3        | 4.29%   |
| Qualcomm Atheros                      | 3        | 4.29%   |
| D-Link System                         | 3        | 4.29%   |
| Xiaomi                                | 1        | 1.43%   |
| Ralink Technology                     | 1        | 1.43%   |
| Qualcomm Atheros Communications       | 1        | 1.43%   |
| Microsoft                             | 1        | 1.43%   |
| Google                                | 1        | 1.43%   |
| DisplayLink                           | 1        | 1.43%   |
| Aquantia                              | 1        | 1.43%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 1.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 29       | 32.22%  |
| Intel I211 Gigabit Network Connection                             | 8        | 8.89%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 2        | 2.22%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 2.22%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 2.22%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 2.22%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 2.22%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 2.22%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.11%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1        | 1.11%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1        | 1.11%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1        | 1.11%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1        | 1.11%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1        | 1.11%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 1.11%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1        | 1.11%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.11%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 1.11%   |
| Realtek 802.11ac+Bluetooth 5.0 Adapter                            | 1        | 1.11%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 1.11%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1        | 1.11%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 1.11%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.11%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1        | 1.11%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 1.11%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.11%   |
| Microsoft XBOX ACC                                                | 1        | 1.11%   |
| Intel Wireless-AC 9260                                            | 1        | 1.11%   |
| Intel Wireless 8265 / 8275                                        | 1        | 1.11%   |
| Intel Wireless 8260                                               | 1        | 1.11%   |
| Intel Wireless 7265                                               | 1        | 1.11%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1        | 1.11%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 1.11%   |
| Intel I210 Gigabit Network Connection                             | 1        | 1.11%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.11%   |
| Intel Ethernet Connection I219-LM                                 | 1        | 1.11%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.11%   |
| Intel Ethernet Connection (12) I219-V                             | 1        | 1.11%   |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 1.11%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1        | 1.11%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 10       | 38.46%  |
| Realtek Semiconductor                 | 6        | 23.08%  |
| TP-Link                               | 3        | 11.54%  |
| Qualcomm Atheros                      | 2        | 7.69%   |
| Ralink Technology                     | 1        | 3.85%   |
| Qualcomm Atheros Communications       | 1        | 3.85%   |
| Microsoft                             | 1        | 3.85%   |
| D-Link System                         | 1        | 3.85%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 3.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                               | Desktops | Percent |
|-----------------------------------------------------------------------------------------------------|----------|---------|
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                         | 2        | 7.41%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                                    | 2        | 7.41%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                                 | 1        | 3.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                                     | 1        | 3.7%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                            | 1        | 3.7%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                            | 1        | 3.7%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                                     | 1        | 3.7%    |
| Realtek RTL8188EE Wireless Network Adapter                                                          | 1        | 3.7%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                             | 1        | 3.7%    |
| Realtek 802.11ac+Bluetooth 5.0 Adapter                                                              | 1        | 3.7%    |
| Ralink MT7601U Wireless Adapter                                                                     | 1        | 3.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                          | 1        | 3.7%    |
| Qualcomm Atheros AR9271 802.11n                                                                     | 1        | 3.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                                    | 1        | 3.7%    |
| Microsoft XBOX ACC                                                                                  | 1        | 3.7%    |
| Intel Wireless-AC 9260                                                                              | 1        | 3.7%    |
| Intel Wireless 8265 / 8275                                                                          | 1        | 3.7%    |
| Intel Wireless 8260                                                                                 | 1        | 3.7%    |
| Intel Wireless 7265                                                                                 | 1        | 3.7%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                              | 1        | 3.7%    |
| Intel Wi-Fi 6 AX200                                                                                 | 1        | 3.7%    |
| Intel Comet Lake PCH CNVi WiFi                                                                      | 1        | 3.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                                                     | 1        | 3.7%    |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A2) [Atheros AR9170+AR9104]         | 1        | 3.7%    |
| 802.11g Adapter [Linksys WUSB54GC v3] WUSB100 v2 RangePlus Wireless Network Adapter [Ralink RT3070] | 1        | 3.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 31       | 52.54%  |
| Intel                 | 19       | 32.2%   |
| Qualcomm Atheros      | 3        | 5.08%   |
| D-Link System         | 2        | 3.39%   |
| Xiaomi                | 1        | 1.69%   |
| Google                | 1        | 1.69%   |
| DisplayLink           | 1        | 1.69%   |
| Aquantia              | 1        | 1.69%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 29       | 46.03%  |
| Intel I211 Gigabit Network Connection                             | 8        | 12.7%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 3.17%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 3.17%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 3.17%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 3.17%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.59%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 1.59%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 1.59%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.59%   |
| Intel I210 Gigabit Network Connection                             | 1        | 1.59%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.59%   |
| Intel Ethernet Connection I219-LM                                 | 1        | 1.59%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.59%   |
| Intel Ethernet Connection (12) I219-V                             | 1        | 1.59%   |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 1.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 1.59%   |
| Intel 82567LF-2 Gigabit Network Connection                        | 1        | 1.59%   |
| Intel 82562V-2 10/100 Network Connection                          | 1        | 1.59%   |
| Google Nexus/Pixel Device (tether+ debug)                         | 1        | 1.59%   |
| DisplayLink Kensington Dock (Composite Device)                    | 1        | 1.59%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.59%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 52       | 66.67%  |
| WiFi     | 26       | 33.33%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 39       | 76.47%  |
| WiFi     | 12       | 23.53%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 29       | 55.77%  |
| 2     | 21       | 40.38%  |
| 4     | 2        | 3.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 48       | 92.31%  |
| Yes  | 4        | 7.69%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 10       | 47.62%  |
| Cambridge Silicon Radio         | 4        | 19.05%  |
| IMC Networks                    | 3        | 14.29%  |
| Qualcomm Atheros Communications | 1        | 4.76%   |
| HTC (High Tech Computer)        | 1        | 4.76%   |
| Broadcom                        | 1        | 4.76%   |
| ASUSTek Computer                | 1        | 4.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 4        | 19.05%  |
| Intel Bluetooth wireless interface                                   | 3        | 14.29%  |
| Intel Wireless-AC 3168 Bluetooth                                     | 2        | 9.52%   |
| IMC Networks Bluetooth Radio                                         | 2        | 9.52%   |
| Qualcomm Atheros  Bluetooth Device                                   | 1        | 4.76%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 1        | 4.76%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 1        | 4.76%   |
| Intel AX210 Bluetooth                                                | 1        | 4.76%   |
| Intel AX201 Bluetooth                                                | 1        | 4.76%   |
| Intel AX200 Bluetooth                                                | 1        | 4.76%   |
| IMC Networks Bluetooth Device                                        | 1        | 4.76%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 4.76%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 1        | 4.76%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 1        | 4.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD                                             | 39       | 36.79%  |
| Nvidia                                          | 21       | 19.81%  |
| Intel                                           | 20       | 18.87%  |
| C-Media Electronics                             | 6        | 5.66%   |
| Creative Labs                                   | 3        | 2.83%   |
| Logitech                                        | 2        | 1.89%   |
| Creative Technology                             | 2        | 1.89%   |
| TC Electronic                                   | 1        | 0.94%   |
| SteelSeries ApS                                 | 1        | 0.94%   |
| Shure                                           | 1        | 0.94%   |
| Realtek Semiconductor                           | 1        | 0.94%   |
| Razer USA                                       | 1        | 0.94%   |
| PreSonus Audio Electronics                      | 1        | 0.94%   |
| Native Instruments                              | 1        | 0.94%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.94%   |
| Generalplus Technology                          | 1        | 0.94%   |
| Focusrite-Novation                              | 1        | 0.94%   |
| EVGA                                            | 1        | 0.94%   |
| Corsair                                         | 1        | 0.94%   |
| AudioQuest                                      | 1        | 0.94%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 11       | 8.53%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 9        | 6.98%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 8        | 6.2%    |
| AMD Navi 10 HDMI Audio                                                     | 7        | 5.43%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6        | 4.65%   |
| Nvidia GP104 High Definition Audio Controller                              | 4        | 3.1%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 3.1%    |
| Intel 200 Series PCH HD Audio                                              | 3        | 2.33%   |
| C-Media Electronics USB Audio Device                                       | 3        | 2.33%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3        | 2.33%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3        | 2.33%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3        | 2.33%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3        | 2.33%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 1.55%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 1.55%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 1.55%   |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 1.55%   |
| Intel Comet Lake PCH-V cAVS                                                | 2        | 1.55%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 1.55%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2        | 1.55%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 1.55%   |
| Creative Labs CA0110 [Sound Blaster X-Fi Xtreme Audio]                     | 2        | 1.55%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2        | 1.55%   |
| TC Electronic VoiceLive Play                                               | 1        | 0.78%   |
| SteelSeries ApS Arctis Pro Wireless                                        | 1        | 0.78%   |
| Shure MV7                                                                  | 1        | 0.78%   |
| Realtek Semiconductor Maono AU-PM401                                       | 1        | 0.78%   |
| Razer USA RZ19-0229 Gaming Microphone                                      | 1        | 0.78%   |
| PreSonus Audio Electronics AudioBox Go                                     | 1        | 0.78%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 0.78%   |
| Nvidia High Definition Audio Controller                                    | 1        | 0.78%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 0.78%   |
| Nvidia GM200 High Definition Audio                                         | 1        | 0.78%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 0.78%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1        | 0.78%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 0.78%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 0.78%   |
| Nvidia GA102 High Definition Audio Controller                              | 1        | 0.78%   |
| Native Instruments Komplete Audio 6                                        | 1        | 0.78%   |
| Logitech G933 Wireless Headset Dongle                                      | 1        | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 12       | 22.64%  |
| Kingston            | 11       | 20.75%  |
| G.Skill             | 11       | 20.75%  |
| Crucial             | 4        | 7.55%   |
| Unknown             | 3        | 5.66%   |
| SK hynix            | 3        | 5.66%   |
| Patriot             | 3        | 5.66%   |
| Samsung Electronics | 2        | 3.77%   |
| Transcend           | 1        | 1.89%   |
| Micron Technology   | 1        | 1.89%   |
| AMD                 | 1        | 1.89%   |
| A-DATA Technology   | 1        | 1.89%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s     | 3        | 5.36%   |
| Kingston RAM 99U5474-026.A00LF 4GB DIMM DDR3 1333MT/s    | 2        | 3.57%   |
| G.Skill RAM F3-10666CL9-4GBNT 4GB DIMM DDR3 1600MT/s     | 2        | 3.57%   |
| Crucial RAM BLS16G4D30AESB.M16FE 16GB DIMM DDR4 3200MT/s | 2        | 3.57%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 2        | 3.57%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s    | 2        | 3.57%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 1        | 1.79%   |
| Unknown RAM Module 2048MB DIMM SDRAM                     | 1        | 1.79%   |
| Unknown RAM Module 2048MB DIMM 1328MT/s                  | 1        | 1.79%   |
| Transcend RAM JM2666HLB-16G 16GB DIMM DDR4 2667MT/s      | 1        | 1.79%   |
| SK hynix RAM HMA82GU7CJR8N-VK 16384MB DIMM DDR4 2667MT/s | 1        | 1.79%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s  | 1        | 1.79%   |
| SK hynix RAM HMA41GU6AFR8N-TF 8GB DIMM DDR4 2465MT/s     | 1        | 1.79%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s      | 1        | 1.79%   |
| Samsung RAM M3 78T2863RZS-CF7 1GB DIMM DDR2 800MT/s      | 1        | 1.79%   |
| Patriot RAM PSD48G240082 8GB DIMM DDR4 2400MT/s          | 1        | 1.79%   |
| Patriot RAM PSD48G240081 8GB DIMM DDR4 2800MT/s          | 1        | 1.79%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s           | 1        | 1.79%   |
| Micron RAM 16ATF2G64HZ-2G6J1 16GB SODIMM DDR4 2667MT/s   | 1        | 1.79%   |
| Kingston RAM XJ69DF-MIE 8GB DIMM DDR4 2933MT/s           | 1        | 1.79%   |
| Kingston RAM MSI24D4U7S8MB-8 8GB DIMM DDR4 2400MT/s      | 1        | 1.79%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s      | 1        | 1.79%   |
| Kingston RAM 99U5595-003.A00LF 2GB DIMM DDR3             | 1        | 1.79%   |
| Kingston RAM 99U5584-014.A00LF 4096MB DIMM DDR3 1600MT/s | 1        | 1.79%   |
| Kingston RAM 99U5474-010.A00LF 2GB DIMM DDR3 1333MT/s    | 1        | 1.79%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 1.79%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 1.79%   |
| Kingston RAM 99P5474-033.A00LF 2GB DIMM DDR3 1600MT/s    | 1        | 1.79%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s   | 1        | 1.79%   |
| G.Skill RAM F4-3200C16-8GSXWB 8GB DIMM DDR4 4133MT/s     | 1        | 1.79%   |
| G.Skill RAM F4-3200C16-8GIS 8192MB DIMM DDR4 3200MT/s    | 1        | 1.79%   |
| G.Skill RAM F4-3200C14-16GTZR 16GB DIMM DDR4 3533MT/s    | 1        | 1.79%   |
| G.Skill RAM F4-3000C16-8GVRB 8GB DIMM DDR4 3200MT/s      | 1        | 1.79%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s      | 1        | 1.79%   |
| G.Skill RAM F4-2400C15-4GRR 4096MB DIMM DDR4 2133MT/s    | 1        | 1.79%   |
| G.Skill RAM F3-2400C10-4GTX 4GB DIMM DDR3 2400MT/s       | 1        | 1.79%   |
| G.Skill RAM F3-1866C10-8G 8192MB DIMM DDR3 1600MT/s      | 1        | 1.79%   |
| Crucial RAM CT102464BD160B.C16 8GB DIMM DDR3 1600MT/s    | 1        | 1.79%   |
| Crucial RAM BL16G32C16U4BL.M16FE 16GB DIMM DDR4 3200MT/s | 1        | 1.79%   |
| Corsair RAM Module 4096MB DIMM DDR3 2481MT/s             | 1        | 1.79%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 27       | 60%     |
| DDR3    | 14       | 31.11%  |
| Unknown | 2        | 4.44%   |
| SDRAM   | 1        | 2.22%   |
| DDR2    | 1        | 2.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 44       | 97.78%  |
| SODIMM | 1        | 2.22%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 22       | 44.9%   |
| 4096  | 13       | 26.53%  |
| 16384 | 8        | 16.33%  |
| 2048  | 4        | 8.16%   |
| 32768 | 1        | 2.04%   |
| 1024  | 1        | 2.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 8        | 16.33%  |
| 1600    | 8        | 16.33%  |
| 3600    | 7        | 14.29%  |
| 1333    | 5        | 10.2%   |
| 2667    | 3        | 6.12%   |
| 2400    | 3        | 6.12%   |
| 3466    | 2        | 4.08%   |
| 2933    | 2        | 4.08%   |
| 2133    | 2        | 4.08%   |
| 4133    | 1        | 2.04%   |
| 3733    | 1        | 2.04%   |
| 3533    | 1        | 2.04%   |
| 2800    | 1        | 2.04%   |
| 2481    | 1        | 2.04%   |
| 2465    | 1        | 2.04%   |
| 1328    | 1        | 2.04%   |
| 800     | 1        | 2.04%   |
| Unknown | 1        | 2.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Ricoh              | 1        | 33.33%  |
| Hewlett-Packard    | 1        | 33.33%  |
| Brother Industries | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Ricoh SP 212SUw               | 1        | 33.33%  |
| HP Officejet Pro L7400        | 1        | 33.33%  |
| Brother HL-2030 Laser Printer | 1        | 33.33%  |

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
| Logitech                      | 4        | 30.77%  |
| Creative Technology           | 2        | 15.38%  |
| WaveRider Communications      | 1        | 7.69%   |
| Sunplus Innovation Technology | 1        | 7.69%   |
| Microsoft                     | 1        | 7.69%   |
| Microdia                      | 1        | 7.69%   |
| KYE Systems (Mouse Systems)   | 1        | 7.69%   |
| GEMBIRD                       | 1        | 7.69%   |
| ARC International             | 1        | 7.69%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Logitech Webcam C270                           | 2        | 15.38%  |
| WaveRider USB 2.0 Camera                       | 1        | 7.69%   |
| Sunplus Aukey-PC-LM1E Camera                   | 1        | 7.69%   |
| Microsoft LifeCam Cinema                       | 1        | 7.69%   |
| Microdia Webcam Vitade AF                      | 1        | 7.69%   |
| Logitech Webcam C930e                          | 1        | 7.69%   |
| Logitech Webcam C310                           | 1        | 7.69%   |
| KYE Systems (Mouse Systems) Genius FaceCam 320 | 1        | 7.69%   |
| GEMBIRD USB2.0 PC CAMERA                       | 1        | 7.69%   |
| Creative Live! Cam Sync HD [VF0770]            | 1        | 7.69%   |
| Creative Live! Cam Chat HD [VF0700]            | 1        | 7.69%   |
| ARC International Camera                       | 1        | 7.69%   |

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
| 0     | 47       | 90.38%  |
| 1     | 5        | 9.62%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Unassigned class         | 1        | 25%     |
| Net/wireless             | 1        | 25%     |
| Graphics card            | 1        | 25%     |
| Communication controller | 1        | 25%     |

