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

Total: 68

| Vendor    | Model                   | Probe                                                      | Date         |
|-----------|-------------------------|------------------------------------------------------------|--------------|
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
| Artix Rolling  | 30       | 63.83%  |
| Artix          | 14       | 29.79%  |
| Artix 20210726 | 2        | 4.26%   |
| Artix 20220123 | 1        | 2.13%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| Artix | 45       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.10.8-artix1-1        | 3        | 5.66%   |
| 5.9.14-artix1-1        | 2        | 3.77%   |
| 5.8.8-artix1-1         | 2        | 3.77%   |
| 5.8.12-artix1-1        | 2        | 3.77%   |
| 5.7.6-artix1-1         | 2        | 3.77%   |
| 5.7.12-artix1-1        | 2        | 3.77%   |
| 5.15.12-artix1-1       | 2        | 3.77%   |
| 5.12.14-artix1-1       | 2        | 3.77%   |
| 5.12.12-artix1-1       | 2        | 3.77%   |
| 5.10.4-artix2-1        | 2        | 3.77%   |
| 5.9.8-zen1-1-zen       | 1        | 1.89%   |
| 5.9.14-zen1-1-zen      | 1        | 1.89%   |
| 5.9.12-artix1-1        | 1        | 1.89%   |
| 5.9.10-artix1-1        | 1        | 1.89%   |
| 5.8.5-xanmod1-1-xanmod | 1        | 1.89%   |
| 5.8.14-artix1-1        | 1        | 1.89%   |
| 5.7.2-artix1-1         | 1        | 1.89%   |
| 5.4.197-1-lts54        | 1        | 1.89%   |
| 5.17.8-258-tkg-pds     | 1        | 1.89%   |
| 5.17.4-artix1-1        | 1        | 1.89%   |
| 5.17.12-lqx1-1-lqx     | 1        | 1.89%   |
| 5.16.3-artix1-1        | 1        | 1.89%   |
| 5.16.12-artix1-1       | 1        | 1.89%   |
| 5.16.10-artix1-1       | 1        | 1.89%   |
| 5.16.1-artix1-1        | 1        | 1.89%   |
| 5.15.3-zen1-1-zen      | 1        | 1.89%   |
| 5.15.2-zen1-1-zen      | 1        | 1.89%   |
| 5.15.13-zen1-1-zen     | 1        | 1.89%   |
| 5.14.3-198-tkg-bmq     | 1        | 1.89%   |
| 5.14.10-artix1-1       | 1        | 1.89%   |
| 5.13.8-188-tkg-pds     | 1        | 1.89%   |
| 5.13.4-artix1-1        | 1        | 1.89%   |
| 5.12.2-artix1-1        | 1        | 1.89%   |
| 5.11.16-artix1-1       | 1        | 1.89%   |
| 5.11.11-zen1-1-zen     | 1        | 1.89%   |
| 5.10.7                 | 1        | 1.89%   |
| 5.10.6-artix1-1        | 1        | 1.89%   |
| 5.10.16-artix1-1       | 1        | 1.89%   |
| 5.10.15-zen1-1-zen     | 1        | 1.89%   |
| 5.10.15-artix1-1       | 1        | 1.89%   |
| 5.10.11-zen2-1-zen     | 1        | 1.89%   |
| 4.19.0-1-MANJARO       | 1        | 1.89%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.9.14  | 3        | 5.66%   |
| 5.10.8  | 3        | 5.66%   |
| 5.8.8   | 2        | 3.77%   |
| 5.8.12  | 2        | 3.77%   |
| 5.7.6   | 2        | 3.77%   |
| 5.7.12  | 2        | 3.77%   |
| 5.15.12 | 2        | 3.77%   |
| 5.12.14 | 2        | 3.77%   |
| 5.12.12 | 2        | 3.77%   |
| 5.10.4  | 2        | 3.77%   |
| 5.10.15 | 2        | 3.77%   |
| 5.9.8   | 1        | 1.89%   |
| 5.9.12  | 1        | 1.89%   |
| 5.9.10  | 1        | 1.89%   |
| 5.8.5   | 1        | 1.89%   |
| 5.8.14  | 1        | 1.89%   |
| 5.7.2   | 1        | 1.89%   |
| 5.4.197 | 1        | 1.89%   |
| 5.17.8  | 1        | 1.89%   |
| 5.17.4  | 1        | 1.89%   |
| 5.17.12 | 1        | 1.89%   |
| 5.16.3  | 1        | 1.89%   |
| 5.16.12 | 1        | 1.89%   |
| 5.16.10 | 1        | 1.89%   |
| 5.16.1  | 1        | 1.89%   |
| 5.15.3  | 1        | 1.89%   |
| 5.15.2  | 1        | 1.89%   |
| 5.15.13 | 1        | 1.89%   |
| 5.14.3  | 1        | 1.89%   |
| 5.14.10 | 1        | 1.89%   |
| 5.13.8  | 1        | 1.89%   |
| 5.13.4  | 1        | 1.89%   |
| 5.12.2  | 1        | 1.89%   |
| 5.11.16 | 1        | 1.89%   |
| 5.11.11 | 1        | 1.89%   |
| 5.10.7  | 1        | 1.89%   |
| 5.10.6  | 1        | 1.89%   |
| 5.10.16 | 1        | 1.89%   |
| 5.10.11 | 1        | 1.89%   |
| 4.19.0  | 1        | 1.89%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 10       | 19.61%  |
| 5.9     | 6        | 11.76%  |
| 5.8     | 6        | 11.76%  |
| 5.15    | 5        | 9.8%    |
| 5.12    | 5        | 9.8%    |
| 5.7     | 4        | 7.84%   |
| 5.16    | 4        | 7.84%   |
| 5.17    | 3        | 5.88%   |
| 5.14    | 2        | 3.92%   |
| 5.13    | 2        | 3.92%   |
| 5.11    | 2        | 3.92%   |
| 5.4     | 1        | 1.96%   |
| 4.19    | 1        | 1.96%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 45       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| KDE5       | 11       | 22.45%  |
| GNOME      | 8        | 16.33%  |
| XFCE       | 6        | 12.24%  |
| X-Cinnamon | 6        | 12.24%  |
| Unknown    | 5        | 10.2%   |
| MATE       | 3        | 6.12%   |
| Cinnamon   | 2        | 4.08%   |
| bspwm      | 2        | 4.08%   |
| sway       | 1        | 2.04%   |
| openbox    | 1        | 2.04%   |
| LXQt       | 1        | 2.04%   |
| LXDE       | 1        | 2.04%   |
| i3         | 1        | 2.04%   |
| DWM        | 1        | 2.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 33       | 70.21%  |
| Tty     | 9        | 19.15%  |
| Wayland | 3        | 6.38%   |
| Unknown | 2        | 4.26%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 18       | 37.5%   |
| SDDM    | 15       | 31.25%  |
| LightDM | 12       | 25%     |
| XDM     | 1        | 2.08%   |
| LXDM    | 1        | 2.08%   |
| GDM     | 1        | 2.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 16       | 35.56%  |
| fr_FR   | 5        | 11.11%  |
| ru_RU   | 4        | 8.89%   |
| Unknown | 4        | 8.89%   |
| C       | 3        | 6.67%   |
| pt_PT   | 2        | 4.44%   |
| de_DE   | 2        | 4.44%   |
| ja_JP   | 1        | 2.22%   |
| it_IT   | 1        | 2.22%   |
| es_MX   | 1        | 2.22%   |
| es_AR   | 1        | 2.22%   |
| en_IE   | 1        | 2.22%   |
| en_GB   | 1        | 2.22%   |
| en_AU   | 1        | 2.22%   |
| el_GR   | 1        | 2.22%   |
| bg_BG   | 1        | 2.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 31       | 67.39%  |
| BIOS | 15       | 32.61%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 30       | 66.67%  |
| Btrfs | 10       | 22.22%  |
| Xfs   | 2        | 4.44%   |
| F2fs  | 2        | 4.44%   |
| Jfs   | 1        | 2.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 35       | 74.47%  |
| Unknown | 8        | 17.02%  |
| MBR     | 4        | 8.51%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 33       | 71.74%  |
| Yes       | 13       | 28.26%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 33       | 71.74%  |
| Yes       | 13       | 28.26%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 15       | 33.33%  |
| Gigabyte Technology | 9        | 20%     |
| MSI                 | 8        | 17.78%  |
| ASRock              | 6        | 13.33%  |
| Hewlett-Packard     | 2        | 4.44%   |
| Dell                | 2        | 4.44%   |
| Intel               | 1        | 2.22%   |
| Biostar             | 1        | 2.22%   |
| Alienware           | 1        | 2.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| MSI MS-7C02                  | 2        | 4.44%   |
| MSI MS-7A38                  | 2        | 4.44%   |
| Gigabyte 970A-DS3P           | 2        | 4.44%   |
| MSI MS-7C56                  | 1        | 2.22%   |
| MSI MS-7C37                  | 1        | 2.22%   |
| MSI MS-7B79                  | 1        | 2.22%   |
| MSI MS-7A69                  | 1        | 2.22%   |
| Intel DX58SO2 AAG10925-205   | 1        | 2.22%   |
| HP Compaq 8200 Elite SFF PC  | 1        | 2.22%   |
| HP 280 G1 MT                 | 1        | 2.22%   |
| Gigabyte X570 AORUS ULTRA    | 1        | 2.22%   |
| Gigabyte X570 AORUS ELITE    | 1        | 2.22%   |
| Gigabyte X399 AORUS XTREME   | 1        | 2.22%   |
| Gigabyte P55-USB3            | 1        | 2.22%   |
| Gigabyte HA65M-D2H-B3        | 1        | 2.22%   |
| Gigabyte 990FXA-UD5          | 1        | 2.22%   |
| Gigabyte 990FXA-UD3 R5       | 1        | 2.22%   |
| Dell OptiPlex 5080           | 1        | 2.22%   |
| Dell Inspiron 530            | 1        | 2.22%   |
| Biostar G31D-M7              | 1        | 2.22%   |
| ASUS TUF Gaming X570-PLUS    | 1        | 2.22%   |
| ASUS TUF B450-PLUS GAMING    | 1        | 2.22%   |
| ASUS SABERTOOTH 990FX R2.0   | 1        | 2.22%   |
| ASUS ROG STRIX X570-F GAMING | 1        | 2.22%   |
| ASUS ROG STRIX B550-F GAMING | 1        | 2.22%   |
| ASUS ROG Maximus XI HERO     | 1        | 2.22%   |
| ASUS Pro WS X570-ACE         | 1        | 2.22%   |
| ASUS PRIME X370-PRO          | 1        | 2.22%   |
| ASUS PRIME B450M-A           | 1        | 2.22%   |
| ASUS PRIME B350M-A           | 1        | 2.22%   |
| ASUS P8H61-M LX3 R2.0        | 1        | 2.22%   |
| ASUS P8B75-M LX PLUS         | 1        | 2.22%   |
| ASUS M5A97 LE R2.0           | 1        | 2.22%   |
| ASUS G11CD                   | 1        | 2.22%   |
| ASUS All Series              | 1        | 2.22%   |
| ASRock X570 Phantom Gaming 4 | 1        | 2.22%   |
| ASRock H310CM-DVS            | 1        | 2.22%   |
| ASRock FM2A88X-ITX+          | 1        | 2.22%   |
| ASRock B460 Phantom Gaming 4 | 1        | 2.22%   |
| ASRock B450 Steel Legend     | 1        | 2.22%   |
| ASRock B150M Pro4S/D3        | 1        | 2.22%   |
| Alienware Aurora R8          | 1        | 2.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS ROG              | 3        | 6.67%   |
| ASUS PRIME            | 3        | 6.67%   |
| MSI MS-7C02           | 2        | 4.44%   |
| MSI MS-7A38           | 2        | 4.44%   |
| Gigabyte X570         | 2        | 4.44%   |
| Gigabyte 970A-DS3P    | 2        | 4.44%   |
| ASUS TUF              | 2        | 4.44%   |
| MSI MS-7C56           | 1        | 2.22%   |
| MSI MS-7C37           | 1        | 2.22%   |
| MSI MS-7B79           | 1        | 2.22%   |
| MSI MS-7A69           | 1        | 2.22%   |
| Intel DX58SO2         | 1        | 2.22%   |
| HP Compaq             | 1        | 2.22%   |
| HP 280                | 1        | 2.22%   |
| Gigabyte X399         | 1        | 2.22%   |
| Gigabyte P55-USB3     | 1        | 2.22%   |
| Gigabyte HA65M-D2H-B3 | 1        | 2.22%   |
| Gigabyte 990FXA-UD5   | 1        | 2.22%   |
| Gigabyte 990FXA-UD3   | 1        | 2.22%   |
| Dell OptiPlex         | 1        | 2.22%   |
| Dell Inspiron         | 1        | 2.22%   |
| Biostar G31D-M7       | 1        | 2.22%   |
| ASUS SABERTOOTH       | 1        | 2.22%   |
| ASUS Pro              | 1        | 2.22%   |
| ASUS P8H61-M          | 1        | 2.22%   |
| ASUS P8B75-M          | 1        | 2.22%   |
| ASUS M5A97            | 1        | 2.22%   |
| ASUS G11CD            | 1        | 2.22%   |
| ASUS All              | 1        | 2.22%   |
| ASRock X570           | 1        | 2.22%   |
| ASRock H310CM-DVS     | 1        | 2.22%   |
| ASRock FM2A88X-ITX+   | 1        | 2.22%   |
| ASRock B460           | 1        | 2.22%   |
| ASRock B450           | 1        | 2.22%   |
| ASRock B150M          | 1        | 2.22%   |
| Alienware Aurora      | 1        | 2.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 10       | 22.22%  |
| 2020 | 6        | 13.33%  |
| 2018 | 5        | 11.11%  |
| 2017 | 5        | 11.11%  |
| 2013 | 4        | 8.89%   |
| 2012 | 4        | 8.89%   |
| 2015 | 3        | 6.67%   |
| 2011 | 2        | 4.44%   |
| 2010 | 2        | 4.44%   |
| 2008 | 2        | 4.44%   |
| 2016 | 1        | 2.22%   |
| 2014 | 1        | 2.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 45       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 45       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 45       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 19       | 41.3%   |
| 8.01-16.0   | 12       | 26.09%  |
| 32.01-64.0  | 6        | 13.04%  |
| 3.01-4.0    | 4        | 8.7%    |
| 64.01-256.0 | 4        | 8.7%    |
| 1.01-2.0    | 1        | 2.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 14       | 28.57%  |
| 2.01-3.0   | 10       | 20.41%  |
| 3.01-4.0   | 9        | 18.37%  |
| 1.01-2.0   | 9        | 18.37%  |
| 0.51-1.0   | 3        | 6.12%   |
| 0.01-0.5   | 2        | 4.08%   |
| 16.01-24.0 | 1        | 2.04%   |
| 8.01-16.0  | 1        | 2.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 19       | 40.43%  |
| 3      | 12       | 25.53%  |
| 1      | 8        | 17.02%  |
| 4      | 4        | 8.51%   |
| 6      | 2        | 4.26%   |
| 8      | 1        | 2.13%   |
| 7      | 1        | 2.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 31       | 68.89%  |
| Yes       | 14       | 31.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 45       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 24       | 53.33%  |
| Yes       | 21       | 46.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 28       | 62.22%  |
| Yes       | 17       | 37.78%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Germany     | 8        | 17.39%  |
| France      | 7        | 15.22%  |
| USA         | 6        | 13.04%  |
| Russia      | 5        | 10.87%  |
| Greece      | 3        | 6.52%   |
| Switzerland | 2        | 4.35%   |
| Poland      | 2        | 4.35%   |
| Bulgaria    | 2        | 4.35%   |
| Ukraine     | 1        | 2.17%   |
| UK          | 1        | 2.17%   |
| Mexico      | 1        | 2.17%   |
| Japan       | 1        | 2.17%   |
| Italy       | 1        | 2.17%   |
| Iran        | 1        | 2.17%   |
| Hong Kong   | 1        | 2.17%   |
| Finland     | 1        | 2.17%   |
| Austria     | 1        | 2.17%   |
| Australia   | 1        | 2.17%   |
| Argentina   | 1        | 2.17%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Paris                  | 3        | 6.12%   |
| Moscow                 | 2        | 4.08%   |
| Frankfurt am Main      | 2        | 4.08%   |
| Bern                   | 2        | 4.08%   |
| Athens                 | 2        | 4.08%   |
| Wettringen             | 1        | 2.04%   |
| Vienna                 | 1        | 2.04%   |
| Upper Norwood          | 1        | 2.04%   |
| Ufa                    | 1        | 2.04%   |
| Thessaloniki           | 1        | 2.04%   |
| Tehran                 | 1        | 2.04%   |
| Sydney                 | 1        | 2.04%   |
| Stein                  | 1        | 2.04%   |
| Stavropol              | 1        | 2.04%   |
| Statesboro             | 1        | 2.04%   |
| Sofia                  | 1        | 2.04%   |
| Snohomish              | 1        | 2.04%   |
| Shavertown             | 1        | 2.04%   |
| San Miguel de Tucumán | 1        | 2.04%   |
| Riverview              | 1        | 2.04%   |
| Plovdiv                | 1        | 2.04%   |
| Maebashi               | 1        | 2.04%   |
| Lublin                 | 1        | 2.04%   |
| Kłodzko               | 1        | 2.04%   |
| Koga                   | 1        | 2.04%   |
| Kazan’               | 1        | 2.04%   |
| Helsinki               | 1        | 2.04%   |
| Gochsheim              | 1        | 2.04%   |
| Factoryville           | 1        | 2.04%   |
| Essen                  | 1        | 2.04%   |
| Dnipro                 | 1        | 2.04%   |
| Clarks Summit          | 1        | 2.04%   |
| Ciudad Victoria        | 1        | 2.04%   |
| Chatenois              | 1        | 2.04%   |
| Charlotte              | 1        | 2.04%   |
| Central                | 1        | 2.04%   |
| Castel Maggiore        | 1        | 2.04%   |
| Bourges                | 1        | 2.04%   |
| Bochum                 | 1        | 2.04%   |
| Besançon              | 1        | 2.04%   |
| Berlin                 | 1        | 2.04%   |
| Austin                 | 1        | 2.04%   |
| Argenteuil             | 1        | 2.04%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 19       | 36     | 18.63%  |
| Seagate             | 18       | 23     | 17.65%  |
| Samsung Electronics | 13       | 21     | 12.75%  |
| Kingston            | 9        | 9      | 8.82%   |
| Toshiba             | 7        | 8      | 6.86%   |
| Crucial             | 7        | 11     | 6.86%   |
| SanDisk             | 4        | 6      | 3.92%   |
| Intel               | 4        | 7      | 3.92%   |
| Maxtor              | 2        | 2      | 1.96%   |
| JMicron Technology  | 2        | 2      | 1.96%   |
| Hitachi             | 2        | 2      | 1.96%   |
| Corsair             | 2        | 2      | 1.96%   |
| Transcend           | 1        | 1      | 0.98%   |
| SPCC                | 1        | 1      | 0.98%   |
| SK hynix            | 1        | 1      | 0.98%   |
| PNY                 | 1        | 1      | 0.98%   |
| Phison              | 1        | 1      | 0.98%   |
| Netac               | 1        | 1      | 0.98%   |
| Linux               | 1        | 1      | 0.98%   |
| HGST                | 1        | 2      | 0.98%   |
| Hewlett-Packard     | 1        | 1      | 0.98%   |
| Goodram             | 1        | 1      | 0.98%   |
| China               | 1        | 1      | 0.98%   |
| AMD                 | 1        | 1      | 0.98%   |
| A-DATA Technology   | 1        | 1      | 0.98%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB             | 3        | 2.54%   |
| Seagate ST3500418AS 500GB          | 3        | 2.54%   |
| Seagate ST1000DM010-2EP102 1TB     | 3        | 2.54%   |
| Samsung SSD 860 EVO 250GB          | 3        | 2.54%   |
| WDC WD80EZAZ-11TDBA0 8TB           | 2        | 1.69%   |
| WDC WD10EZEX-08WN4A0 1TB           | 2        | 1.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2        | 1.69%   |
| Samsung SSD 970 EVO 1TB            | 2        | 1.69%   |
| Kingston SA400S37120G 120GB SSD    | 2        | 1.69%   |
| Crucial CT240BX500SSD1 240GB       | 2        | 1.69%   |
| WDC WDS500G2B0C-00PXH0 500GB       | 1        | 0.85%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 1        | 0.85%   |
| WDC WDS256G1X0C-00ENX0 256GB       | 1        | 0.85%   |
| WDC WDS100T2B0C-00PXH0 1TB         | 1        | 0.85%   |
| WDC WDS100T2B0A-00SM50 1TB SSD     | 1        | 0.85%   |
| WDC WDBNCE5000PNC 500GB SSD        | 1        | 0.85%   |
| WDC WD6001FZWX-00A2VA0 6TB         | 1        | 0.85%   |
| WDC WD5003ABYX-18WERA0 500GB       | 1        | 0.85%   |
| WDC WD5000LPVX-00V0TT0 500GB       | 1        | 0.85%   |
| WDC WD5000AAKX-60U6AA0 500GB       | 1        | 0.85%   |
| WDC WD40EZRZ-00WN9B0 4TB           | 1        | 0.85%   |
| WDC WD4003FZEX-00Z4SA0 4TB         | 1        | 0.85%   |
| WDC WD4003FFBX-68MU3N0 4TB         | 1        | 0.85%   |
| WDC WD30EZRX-00DC0B0 3TB           | 1        | 0.85%   |
| WDC WD30EFRX-68EUZN0 3TB           | 1        | 0.85%   |
| WDC WD2500HHTZ-04N21V0 250GB       | 1        | 0.85%   |
| WDC WD20EZRX-00D8PB0 2TB           | 1        | 0.85%   |
| WDC WD20EZBX-00AYRA0 2TB           | 1        | 0.85%   |
| WDC WD20EARS-00MVWB0 2TB           | 1        | 0.85%   |
| WDC WD2003FZEX-00SRLA0 2TB         | 1        | 0.85%   |
| WDC WD15EARS-22MVWB0 1TB           | 1        | 0.85%   |
| WDC WD10EZRZ-00HTKB0 1TB           | 1        | 0.85%   |
| WDC WD10EZEX-00BN5A0 1TB           | 1        | 0.85%   |
| WDC WD100EMAZ-00WJTA0 10TB         | 1        | 0.85%   |
| Transcend TS1TMTE220S 1TB          | 1        | 0.85%   |
| Toshiba MK7575GSX 752GB            | 1        | 0.85%   |
| Toshiba HDWD130 3TB                | 1        | 0.85%   |
| Toshiba HDWD110 1TB                | 1        | 0.85%   |
| Toshiba DT01ACA050 500GB           | 1        | 0.85%   |
| SPCC Solid State Disk 240GB        | 1        | 0.85%   |
| SK hynix PC601 NVMe 512GB          | 1        | 0.85%   |
| Seagate ST8000DM004-2CX188 8TB     | 1        | 0.85%   |
| Seagate ST500DM002-1SB10A 500GB    | 1        | 0.85%   |
| Seagate ST500DM002-1BD142 500GB    | 1        | 0.85%   |
| Seagate ST3600057SS 600GB          | 1        | 0.85%   |
| Seagate ST31000524AS 1TB           | 1        | 0.85%   |
| Seagate ST3000DM001-1CH166 3TB     | 1        | 0.85%   |
| Seagate ST2000LX001-1RG174 2TB     | 1        | 0.85%   |
| Seagate ST2000DX002-2DV164 2TB     | 1        | 0.85%   |
| Seagate ST2000DM006-2DM164 2TB     | 1        | 0.85%   |
| Seagate ST1000NM0011 1TB           | 1        | 0.85%   |
| Seagate ST1000DM003-1SB10C 1TB     | 1        | 0.85%   |
| Seagate ST1000DM003-1ER162 1TB     | 1        | 0.85%   |
| SanDisk SSD PLUS 1000GB            | 1        | 0.85%   |
| SanDisk SDSSDHII480G 480GB         | 1        | 0.85%   |
| SanDisk NVMe SSD Drive 500GB       | 1        | 0.85%   |
| SanDisk NVMe SSD Drive 256GB       | 1        | 0.85%   |
| Samsung SSD 970 PRO 1TB            | 1        | 0.85%   |
| Samsung SSD 970 EVO Plus 500GB     | 1        | 0.85%   |
| Samsung SSD 970 EVO 500GB          | 1        | 0.85%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Desktops | Drives | Percent |
|--------------------|----------|--------|---------|
| Seagate            | 18       | 23     | 38.3%   |
| WDC                | 16       | 28     | 34.04%  |
| Toshiba            | 7        | 8      | 14.89%  |
| Maxtor             | 2        | 2      | 4.26%   |
| Hitachi            | 2        | 2      | 4.26%   |
| JMicron Technology | 1        | 1      | 2.13%   |
| HGST               | 1        | 2      | 2.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 8        | 11     | 21.62%  |
| Kingston            | 7        | 7      | 18.92%  |
| Crucial             | 7        | 11     | 18.92%  |
| WDC                 | 3        | 5      | 8.11%   |
| SanDisk             | 2        | 2      | 5.41%   |
| Intel               | 2        | 3      | 5.41%   |
| SPCC                | 1        | 1      | 2.7%    |
| Netac               | 1        | 1      | 2.7%    |
| Linux               | 1        | 1      | 2.7%    |
| JMicron Technology  | 1        | 1      | 2.7%    |
| Goodram             | 1        | 1      | 2.7%    |
| China               | 1        | 1      | 2.7%    |
| AMD                 | 1        | 1      | 2.7%    |
| A-DATA Technology   | 1        | 1      | 2.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 36       | 66     | 42.35%  |
| SSD  | 31       | 47     | 36.47%  |
| NVMe | 18       | 30     | 21.18%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 42       | 110    | 66.67%  |
| NVMe | 18       | 30     | 28.57%  |
| SAS  | 3        | 3      | 4.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 32       | 54     | 42.67%  |
| 0.51-1.0   | 24       | 33     | 32%     |
| 1.01-2.0   | 9        | 10     | 12%     |
| 2.01-3.0   | 4        | 4      | 5.33%   |
| 3.01-4.0   | 3        | 3      | 4%      |
| 4.01-10.0  | 3        | 9      | 4%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 9        | 19.57%  |
| 101-250        | 9        | 19.57%  |
| 1001-2000      | 9        | 19.57%  |
| 2001-3000      | 8        | 17.39%  |
| 501-1000       | 5        | 10.87%  |
| 251-500        | 4        | 8.7%    |
| 51-100         | 2        | 4.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 11       | 23.4%   |
| 251-500        | 7        | 14.89%  |
| 1-20           | 7        | 14.89%  |
| 1001-2000      | 6        | 12.77%  |
| More than 3000 | 5        | 10.64%  |
| 101-250        | 5        | 10.64%  |
| 21-50          | 2        | 4.26%   |
| 2001-3000      | 2        | 4.26%   |
| 51-100         | 2        | 4.26%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| WDC WD30EZRX-00DC0B0 3TB         | 1        | 1      | 9.09%   |
| Toshiba MK7575GSX 752GB          | 1        | 1      | 9.09%   |
| Seagate ST8000DM004-2CX188 8TB   | 1        | 1      | 9.09%   |
| Seagate ST2000DX002-2DV164 2TB   | 1        | 1      | 9.09%   |
| Seagate ST2000DM006-2DM164 2TB   | 1        | 1      | 9.09%   |
| Maxtor 6Y080M0 81GB              | 1        | 1      | 9.09%   |
| Kingston SUV400S37240G 240GB SSD | 1        | 1      | 9.09%   |
| Kingston SA400S37120G 120GB SSD  | 1        | 1      | 9.09%   |
| Intel SSDSC2BW480A4 480GB        | 1        | 2      | 9.09%   |
| Intel SSDPEKKW128G7 128GB        | 1        | 1      | 9.09%   |
| Hewlett-Packard SSD EX900 250GB  | 1        | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor          | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| Seagate         | 3        | 3      | 27.27%  |
| Kingston        | 2        | 2      | 18.18%  |
| Intel           | 2        | 3      | 18.18%  |
| WDC             | 1        | 1      | 9.09%   |
| Toshiba         | 1        | 1      | 9.09%   |
| Maxtor          | 1        | 1      | 9.09%   |
| Hewlett-Packard | 1        | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 3        | 3      | 50%     |
| WDC     | 1        | 1      | 16.67%  |
| Toshiba | 1        | 1      | 16.67%  |
| Maxtor  | 1        | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 6        | 6      | 54.55%  |
| SSD  | 3        | 4      | 27.27%  |
| NVMe | 2        | 2      | 18.18%  |

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
| Works    | 32       | 83     | 56.14%  |
| Detected | 15       | 48     | 26.32%  |
| Malfunc  | 10       | 12     | 17.54%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| AMD                         | 27       | 36.49%  |
| Intel                       | 19       | 25.68%  |
| Samsung Electronics         | 7        | 9.46%   |
| SanDisk                     | 4        | 5.41%   |
| Marvell Technology Group    | 4        | 5.41%   |
| Phison Electronics          | 3        | 4.05%   |
| ASMedia Technology          | 3        | 4.05%   |
| Silicon Motion              | 2        | 2.7%    |
| Kingston Technology Company | 2        | 2.7%    |
| SK hynix                    | 1        | 1.35%   |
| JMicron Technology          | 1        | 1.35%   |
| Broadcom / LSI              | 1        | 1.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 18       | 19.57%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6        | 6.52%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 6        | 6.52%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6        | 6.52%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 3.26%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 3.26%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 3.26%   |
| Phison E12 NVMe Controller                                                              | 2        | 2.17%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 2        | 2.17%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 2.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2        | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 2.17%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 2.17%   |
| SK hynix Non-Volatile memory controller                                                 | 1        | 1.09%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 1.09%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 1.09%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 1.09%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 1        | 1.09%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 1.09%   |
| SanDisk WD Black NVMe SSD                                                               | 1        | 1.09%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 1.09%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 1.09%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                                   | 1        | 1.09%   |
| Marvell Group 88SE912x IDE Controller                                                   | 1        | 1.09%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                                    | 1        | 1.09%   |
| Kingston Company Company Non-Volatile memory controller                                 | 1        | 1.09%   |
| Kingston Company A2000 NVMe SSD                                                         | 1        | 1.09%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 1.09%   |
| Intel SSD 660P Series                                                                   | 1        | 1.09%   |
| Intel SSD 600P Series                                                                   | 1        | 1.09%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 1.09%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1        | 1.09%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 1.09%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 1.09%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1        | 1.09%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1        | 1.09%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 1.09%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                              | 1        | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.09%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 1.09%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 1.09%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 1        | 1.09%   |
| AMD X399 Series Chipset SATA Controller                                                 | 1        | 1.09%   |
| AMD X370 Series Chipset SATA Controller                                                 | 1        | 1.09%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 1.09%   |
| AMD FCH IDE Controller                                                                  | 1        | 1.09%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 42       | 60%     |
| NVMe | 18       | 25.71%  |
| IDE  | 8        | 11.43%  |
| RAID | 1        | 1.43%   |
| SAS  | 1        | 1.43%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 27       | 60%     |
| Intel  | 18       | 40%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD FX-8350 Eight-Core Processor                | 4        | 8.89%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 3        | 6.67%   |
| Intel Core i7-9700K CPU @ 3.60GHz               | 2        | 4.44%   |
| Intel Core i5-2500 CPU @ 3.30GHz                | 2        | 4.44%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 2        | 4.44%   |
| AMD Ryzen 5 3600 6-Core Processor               | 2        | 4.44%   |
| AMD Ryzen 5 2600X Six-Core Processor            | 2        | 4.44%   |
| Intel Core i7-9700F CPU @ 3.00GHz               | 1        | 2.22%   |
| Intel Core i7-4790K CPU @ 4.00GHz               | 1        | 2.22%   |
| Intel Core i7 CPU 970 @ 3.20GHz                 | 1        | 2.22%   |
| Intel Core i5-7600K CPU @ 3.80GHz               | 1        | 2.22%   |
| Intel Core i5-6600K CPU @ 3.50GHz               | 1        | 2.22%   |
| Intel Core i5-6400 CPU @ 2.70GHz                | 1        | 2.22%   |
| Intel Core i5-3330 CPU @ 3.00GHz                | 1        | 2.22%   |
| Intel Core i5-2310 CPU @ 2.90GHz                | 1        | 2.22%   |
| Intel Core i5-10500T CPU @ 2.30GHz              | 1        | 2.22%   |
| Intel Core i5-10400F CPU @ 2.90GHz              | 1        | 2.22%   |
| Intel Core i5 CPU 660 @ 3.33GHz                 | 1        | 2.22%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz            | 1        | 2.22%   |
| Intel Core 2 Duo CPU E4600 @ 2.40GHz            | 1        | 2.22%   |
| Intel Celeron CPU G1840 @ 2.80GHz               | 1        | 2.22%   |
| AMD Ryzen Threadripper 2990WX 32-Core Processor | 1        | 2.22%   |
| AMD Ryzen 9 3900XT 12-Core Processor            | 1        | 2.22%   |
| AMD Ryzen 7 5800X 8-Core Processor              | 1        | 2.22%   |
| AMD Ryzen 7 5700G with Radeon Graphics          | 1        | 2.22%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 1        | 2.22%   |
| AMD Ryzen 7 1700 Eight-Core Processor           | 1        | 2.22%   |
| AMD Ryzen 5 5600X 6-Core Processor              | 1        | 2.22%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 1        | 2.22%   |
| AMD Ryzen 5 1600 Six-Core Processor             | 1        | 2.22%   |
| AMD Ryzen 5 1500X Quad-Core Processor           | 1        | 2.22%   |
| AMD Ryzen 3 1200 Quad-Core Processor            | 1        | 2.22%   |
| AMD Phenom II X4 955 Processor                  | 1        | 2.22%   |
| AMD FX-6300 Six-Core Processor                  | 1        | 2.22%   |
| AMD A10-7870K Radeon R7, 12 Compute Cores 4C+8G | 1        | 2.22%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 10       | 22.22%  |
| AMD Ryzen 5            | 8        | 17.78%  |
| AMD Ryzen 7            | 6        | 13.33%  |
| Intel Core i7          | 5        | 11.11%  |
| AMD FX                 | 5        | 11.11%  |
| AMD Ryzen 9            | 4        | 8.89%   |
| Intel Core 2 Duo       | 2        | 4.44%   |
| Intel Celeron          | 1        | 2.22%   |
| AMD Ryzen Threadripper | 1        | 2.22%   |
| AMD Ryzen 3            | 1        | 2.22%   |
| AMD Phenom II X4       | 1        | 2.22%   |
| AMD A10                | 1        | 2.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 14       | 31.11%  |
| 6      | 10       | 22.22%  |
| 8      | 9        | 20%     |
| 2      | 5        | 11.11%  |
| 12     | 4        | 8.89%   |
| 3      | 2        | 4.44%   |
| 32     | 1        | 2.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 45       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 30       | 66.67%  |
| 1      | 15       | 33.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 45       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 9        | 19.15%  |
| 0x08701013 | 4        | 8.51%   |
| 0x08701021 | 3        | 6.38%   |
| 0x0800820d | 3        | 6.38%   |
| 0x06000822 | 3        | 6.38%   |
| 0x906ed    | 2        | 4.26%   |
| 0x506e3    | 2        | 4.26%   |
| 0x306c3    | 2        | 4.26%   |
| 0x206a7    | 2        | 4.26%   |
| 0x06000852 | 2        | 4.26%   |
| 0xa0655    | 1        | 2.13%   |
| 0xa0653    | 1        | 2.13%   |
| 0x906e9    | 1        | 2.13%   |
| 0x6fd      | 1        | 2.13%   |
| 0x306a9    | 1        | 2.13%   |
| 0x206c2    | 1        | 2.13%   |
| 0x20652    | 1        | 2.13%   |
| 0x1067a    | 1        | 2.13%   |
| 0x0a50000b | 1        | 2.13%   |
| 0x0a201016 | 1        | 2.13%   |
| 0x0a201009 | 1        | 2.13%   |
| 0x0800820b | 1        | 2.13%   |
| 0x08001138 | 1        | 2.13%   |
| 0x08001129 | 1        | 2.13%   |
| 0x06003106 | 1        | 2.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen 2       | 8        | 17.78%  |
| Zen+        | 5        | 11.11%  |
| Piledriver  | 5        | 11.11%  |
| Zen 3       | 4        | 8.89%   |
| KabyLake    | 4        | 8.89%   |
| Zen         | 3        | 6.67%   |
| SandyBridge | 3        | 6.67%   |
| Westmere    | 2        | 4.44%   |
| Skylake     | 2        | 4.44%   |
| Haswell     | 2        | 4.44%   |
| CometLake   | 2        | 4.44%   |
| Steamroller | 1        | 2.22%   |
| Penryn      | 1        | 2.22%   |
| K10         | 1        | 2.22%   |
| IvyBridge   | 1        | 2.22%   |
| Core        | 1        | 2.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 25       | 51.02%  |
| Nvidia | 18       | 36.73%  |
| Intel  | 6        | 12.24%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 8        | 15.69%  |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4        | 7.84%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 3.92%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 2        | 3.92%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 3.92%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 3.92%   |
| AMD Cezanne                                                                 | 2        | 3.92%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 1.96%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 1.96%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 1.96%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 1.96%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 1.96%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.96%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.96%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 1.96%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 1.96%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 1.96%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.96%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                           | 1        | 1.96%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.96%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 1.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 1.96%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.96%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 1.96%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.96%   |
| AMD Vega 20 [Radeon VII]                                                    | 1        | 1.96%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 1        | 1.96%   |
| AMD Redwood XT [Radeon HD 5670/5690/5730]                                   | 1        | 1.96%   |
| AMD Pitcairn XT [Radeon HD 7870 GHz Edition]                                | 1        | 1.96%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 1        | 1.96%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 1        | 1.96%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 1        | 1.96%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 1        | 1.96%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                          | 1        | 1.96%   |
| AMD Cayman PRO [Radeon HD 6950]                                             | 1        | 1.96%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1        | 1.96%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x AMD      | 21       | 45.65%  |
| 1 x Nvidia   | 16       | 34.78%  |
| 1 x Intel    | 5        | 10.87%  |
| 2 x AMD      | 2        | 4.35%   |
| AMD + Nvidia | 2        | 4.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 34       | 72.34%  |
| Proprietary | 13       | 27.66%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 7.01-8.0   | 13       | 26.53%  |
| Unknown    | 13       | 26.53%  |
| 3.01-4.0   | 7        | 14.29%  |
| 1.01-2.0   | 7        | 14.29%  |
| 0.51-1.0   | 4        | 8.16%   |
| 8.01-16.0  | 3        | 6.12%   |
| 5.01-6.0   | 1        | 2.04%   |
| 0.01-0.5   | 1        | 2.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 10       | 15.63%  |
| Acer                 | 8        | 12.5%   |
| Philips              | 7        | 10.94%  |
| Goldstar             | 6        | 9.38%   |
| AOC                  | 6        | 9.38%   |
| BenQ                 | 5        | 7.81%   |
| Dell                 | 4        | 6.25%   |
| ASUSTek Computer     | 3        | 4.69%   |
| Ancor Communications | 2        | 3.13%   |
| ViewSonic            | 1        | 1.56%   |
| Vestel Elektronik    | 1        | 1.56%   |
| Packard Bell         | 1        | 1.56%   |
| KTC                  | 1        | 1.56%   |
| Jean                 | 1        | 1.56%   |
| Iiyama               | 1        | 1.56%   |
| Idek Iiyama          | 1        | 1.56%   |
| HVR                  | 1        | 1.56%   |
| Hitachi              | 1        | 1.56%   |
| Hewlett-Packard      | 1        | 1.56%   |
| Envision Peripherals | 1        | 1.56%   |
| CTV                  | 1        | 1.56%   |
| Belinea              | 1        | 1.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Desktops | Percent |
|--------------------------------------------------------------------------|----------|---------|
| AOC F22 AOC2200 1920x1080 476x268mm 21.5-inch                            | 2        | 2.94%   |
| Ancor Communications ASUS PB277 ACI27B5 2560x1440 597x336mm 27.0-inch    | 2        | 2.94%   |
| ViewSonic LCD Monitor VX2452 Series 3840x1080                            | 1        | 1.47%   |
| Vestel Elektronik 28W_LCD_TV VES3700 1920x540                            | 1        | 1.47%   |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch        | 1        | 1.47%   |
| Samsung Electronics T24B301 SAM098E 1920x1080 520x290mm 23.4-inch        | 1        | 1.47%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 1        | 1.47%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch        | 1        | 1.47%   |
| Samsung Electronics S24A31x SAM7114 1920x1080 527x296mm 23.8-inch        | 1        | 1.47%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch        | 1        | 1.47%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch  | 1        | 1.47%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1872x1053mm 84.6-inch  | 1        | 1.47%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch        | 1        | 1.47%   |
| Samsung Electronics C27FG7x SAM0E41 1920x1080 598x337mm 27.0-inch        | 1        | 1.47%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch        | 1        | 1.47%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 1        | 1.47%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch                 | 1        | 1.47%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch                  | 1        | 1.47%   |
| Philips PHL 245E1 PHLC20B 2560x1440 527x296mm 23.8-inch                  | 1        | 1.47%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 1        | 1.47%   |
| Philips PHL 220V8 PHLC218 1920x1080 477x268mm 21.5-inch                  | 1        | 1.47%   |
| Philips 247ELH PHLC085 1920x1080 521x293mm 23.5-inch                     | 1        | 1.47%   |
| Philips 226VL PHLC081 1920x1080 480x268mm 21.6-inch                      | 1        | 1.47%   |
| Packard Bell Viseo203DX PKB0378 1600x900 432x240mm 19.5-inch             | 1        | 1.47%   |
| KTC 24'TV KTC2400 1360x768 708x398mm 32.0-inch                           | 1        | 1.47%   |
| Jean JT198x6-7 JEN17C6 1280x1024 376x301mm 19.0-inch                     | 1        | 1.47%   |
| Iiyama PL3461WQ IVM7615 3440x1440 800x335mm 34.1-inch                    | 1        | 1.47%   |
| Idek Iiyama LCD Monitor PL2488H                                          | 1        | 1.47%   |
| HVR HTC-VIVE HVRAA01 2160x1200                                           | 1        | 1.47%   |
| Hitachi HDMI HEC0030 1920x1080 580x330mm 26.3-inch                       | 1        | 1.47%   |
| Hewlett-Packard LA1951 HWP285B 1280x1024 380x300mm 19.1-inch             | 1        | 1.47%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 1        | 1.47%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                  | 1        | 1.47%   |
| Goldstar MP59G GSM5B35 1920x1080 480x270mm 21.7-inch                     | 1        | 1.47%   |
| Goldstar HDR WFHD GSM7715 2560x1080 798x334mm 34.1-inch                  | 1        | 1.47%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                   | 1        | 1.47%   |
| Goldstar E2251 GSM586D 1920x1080 477x268mm 21.5-inch                     | 1        | 1.47%   |
| Envision Peripherals LED P2478MDHL ENV2478 1920x1080 531x299mm 24.0-inch | 1        | 1.47%   |
| Dell U2415 DELA0B8 1920x1200 520x320mm 24.0-inch                         | 1        | 1.47%   |
| Dell S2817Q DEL40EE 3840x2160 620x340mm 27.8-inch                        | 1        | 1.47%   |
| Dell P2211H DEL4061 1920x1080 477x268mm 21.5-inch                        | 1        | 1.47%   |
| Dell AW2518HF DELA103 1920x1080 544x303mm 24.5-inch                      | 1        | 1.47%   |
| CTV LCD Monitor CTV0030 1920x1080 930x520mm 41.9-inch                    | 1        | 1.47%   |
| BenQ LCD Monitor RL2455                                                  | 1        | 1.47%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                        | 1        | 1.47%   |
| BenQ FP71V+ BNQ76A2 1280x1024 376x301mm 19.0-inch                        | 1        | 1.47%   |
| BenQ FP202W BNQ76C3 1680x1050 376x301mm 19.0-inch                        | 1        | 1.47%   |
| BenQ EX2780Q BNQ7F76 2560x1440 597x336mm 27.0-inch                       | 1        | 1.47%   |
| Belinea Belinea101536 MAX05EA 1024x768 304x228mm 15.0-inch               | 1        | 1.47%   |
| ASUSTek Computer VP249 AUS24AF 1920x1080 527x296mm 23.8-inch             | 1        | 1.47%   |
| ASUSTek Computer VG289 AUS28BA 3840x2160 621x341mm 27.9-inch             | 1        | 1.47%   |
| ASUSTek Computer ROG PG27U AUS27A4 3840x2160 598x336mm 27.0-inch         | 1        | 1.47%   |
| AOC U3277WB AOC3277 3840x2160 698x393mm 31.5-inch                        | 1        | 1.47%   |
| AOC 2475W AOC2475 1920x1080 521x293mm 23.5-inch                          | 1        | 1.47%   |
| AOC 2370 AOC2370 1920x1080 509x286mm 23.0-inch                           | 1        | 1.47%   |
| AOC 2367M AOC2367 1920x1080 510x290mm 23.1-inch                          | 1        | 1.47%   |
| Ancor Communications LCD Monitor ASUS PB277 2560x1440                    | 1        | 1.47%   |
| Acer XB241H ACR050E 1920x1080 531x299mm 24.0-inch                        | 1        | 1.47%   |
| Acer V243H ACR00A3 1920x1080 530x290mm 23.8-inch                         | 1        | 1.47%   |
| Acer S240HL ACR0289 1920x1080 531x299mm 24.0-inch                        | 1        | 1.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 31       | 50%     |
| 3840x2160 (4K)     | 11       | 17.74%  |
| 2560x1440 (QHD)    | 5        | 8.06%   |
| 2560x1080          | 2        | 3.23%   |
| 1280x1024 (SXGA)   | 2        | 3.23%   |
| Unknown            | 2        | 3.23%   |
| 3840x1080          | 1        | 1.61%   |
| 3600x1080          | 1        | 1.61%   |
| 3440x1440          | 1        | 1.61%   |
| 2160x1200          | 1        | 1.61%   |
| 1920x1200 (WUXGA)  | 1        | 1.61%   |
| 1680x1050 (WSXGA+) | 1        | 1.61%   |
| 1600x900 (HD+)     | 1        | 1.61%   |
| 1280x960           | 1        | 1.61%   |
| 1024x768 (XGA)     | 1        | 1.61%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 11       | 18.03%  |
| 23      | 11       | 18.03%  |
| 27      | 10       | 16.39%  |
| 21      | 7        | 11.48%  |
| 84      | 4        | 6.56%   |
| Unknown | 4        | 6.56%   |
| 34      | 3        | 4.92%   |
| 31      | 3        | 4.92%   |
| 19      | 3        | 4.92%   |
| 32      | 2        | 3.28%   |
| 52      | 1        | 1.64%   |
| 20      | 1        | 1.64%   |
| 15      | 1        | 1.64%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 29       | 48.33%  |
| 401-500     | 8        | 13.33%  |
| 701-800     | 5        | 8.33%   |
| 601-700     | 5        | 8.33%   |
| 1501-2000   | 4        | 6.67%   |
| Unknown     | 4        | 6.67%   |
| 351-400     | 3        | 5%      |
| 301-350     | 1        | 1.67%   |
| 1001-1500   | 1        | 1.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 40       | 75.47%  |
| 5/4     | 3        | 5.66%   |
| 21/9    | 3        | 5.66%   |
| 16/10   | 3        | 5.66%   |
| Unknown | 3        | 5.66%   |
| 4/3     | 1        | 1.89%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 26       | 42.62%  |
| 301-350        | 10       | 16.39%  |
| 351-500        | 8        | 13.11%  |
| More than 1000 | 5        | 8.2%    |
| 151-200        | 5        | 8.2%    |
| Unknown        | 4        | 6.56%   |
| 251-300        | 2        | 3.28%   |
| 101-110        | 1        | 1.64%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 33       | 57.89%  |
| 101-120 | 12       | 21.05%  |
| 121-160 | 5        | 8.77%   |
| Unknown | 4        | 7.02%   |
| 161-240 | 2        | 3.51%   |
| 1-50    | 1        | 1.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 31       | 67.39%  |
| 2     | 11       | 23.91%  |
| 3     | 3        | 6.52%   |
| 4     | 1        | 2.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 29       | 47.54%  |
| Intel                                 | 18       | 29.51%  |
| D-Link System                         | 3        | 4.92%   |
| Qualcomm Atheros                      | 2        | 3.28%   |
| Xiaomi                                | 1        | 1.64%   |
| TP-Link                               | 1        | 1.64%   |
| Ralink Technology                     | 1        | 1.64%   |
| Qualcomm Atheros Communications       | 1        | 1.64%   |
| Microsoft                             | 1        | 1.64%   |
| Google                                | 1        | 1.64%   |
| DisplayLink                           | 1        | 1.64%   |
| Aquantia                              | 1        | 1.64%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 1.64%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                               | Desktops | Percent |
|-----------------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                                   | 26       | 32.91%  |
| Intel I211 Gigabit Network Connection                                                               | 6        | 7.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                               | 2        | 2.53%   |
| Intel Ethernet Connection (2) I219-V                                                                | 2        | 2.53%   |
| Intel 82574L Gigabit Network Connection                                                             | 2        | 2.53%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                                                     | 2        | 2.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                                      | 1        | 1.27%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                         | 1        | 1.27%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                                     | 1        | 1.27%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                            | 1        | 1.27%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                            | 1        | 1.27%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                                     | 1        | 1.27%   |
| Realtek RTL8188EE Wireless Network Adapter                                                          | 1        | 1.27%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                             | 1        | 1.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                            | 1        | 1.27%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                               | 1        | 1.27%   |
| Realtek 802.11ac NIC                                                                                | 1        | 1.27%   |
| Ralink MT7601U Wireless Adapter                                                                     | 1        | 1.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                          | 1        | 1.27%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                                           | 1        | 1.27%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                                           | 1        | 1.27%   |
| Qualcomm Atheros AR9271 802.11n                                                                     | 1        | 1.27%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                                    | 1        | 1.27%   |
| Microsoft XBOX ACC                                                                                  | 1        | 1.27%   |
| Intel Wireless-AC 9260                                                                              | 1        | 1.27%   |
| Intel Wireless 8265 / 8275                                                                          | 1        | 1.27%   |
| Intel Wireless 8260                                                                                 | 1        | 1.27%   |
| Intel Wireless 7265                                                                                 | 1        | 1.27%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                              | 1        | 1.27%   |
| Intel Wi-Fi 6 AX200                                                                                 | 1        | 1.27%   |
| Intel I210 Gigabit Network Connection                                                               | 1        | 1.27%   |
| Intel Ethernet Controller I225-V                                                                    | 1        | 1.27%   |
| Intel Ethernet Connection I219-LM                                                                   | 1        | 1.27%   |
| Intel Ethernet Connection (7) I219-V                                                                | 1        | 1.27%   |
| Intel Ethernet Connection (11) I219-LM                                                              | 1        | 1.27%   |
| Intel Comet Lake PCH CNVi WiFi                                                                      | 1        | 1.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                                                     | 1        | 1.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                               | 1        | 1.27%   |
| Intel 82567LF-2 Gigabit Network Connection                                                          | 1        | 1.27%   |
| Intel 82562V-2 10/100 Network Connection                                                            | 1        | 1.27%   |
| Google Nexus/Pixel Device (tether+ debug)                                                           | 1        | 1.27%   |
| DisplayLink Kensington Dock (Composite Device)                                                      | 1        | 1.27%   |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A2) [Atheros AR9170+AR9104]         | 1        | 1.27%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]                                   | 1        | 1.27%   |
| 802.11g Adapter [Linksys WUSB54GC v3] WUSB100 v2 RangePlus Wireless Network Adapter [Ralink RT3070] | 1        | 1.27%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 8        | 36.36%  |
| Realtek Semiconductor                 | 6        | 27.27%  |
| Qualcomm Atheros                      | 2        | 9.09%   |
| TP-Link                               | 1        | 4.55%   |
| Ralink Technology                     | 1        | 4.55%   |
| Qualcomm Atheros Communications       | 1        | 4.55%   |
| Microsoft                             | 1        | 4.55%   |
| D-Link System                         | 1        | 4.55%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 4.55%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                               | Desktops | Percent |
|-----------------------------------------------------------------------------------------------------|----------|---------|
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                         | 1        | 4.35%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                                     | 1        | 4.35%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                            | 1        | 4.35%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                            | 1        | 4.35%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                                     | 1        | 4.35%   |
| Realtek RTL8188EE Wireless Network Adapter                                                          | 1        | 4.35%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                             | 1        | 4.35%   |
| Realtek 802.11ac NIC                                                                                | 1        | 4.35%   |
| Ralink MT7601U Wireless Adapter                                                                     | 1        | 4.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                          | 1        | 4.35%   |
| Qualcomm Atheros AR9271 802.11n                                                                     | 1        | 4.35%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                                    | 1        | 4.35%   |
| Microsoft XBOX ACC                                                                                  | 1        | 4.35%   |
| Intel Wireless-AC 9260                                                                              | 1        | 4.35%   |
| Intel Wireless 8265 / 8275                                                                          | 1        | 4.35%   |
| Intel Wireless 8260                                                                                 | 1        | 4.35%   |
| Intel Wireless 7265                                                                                 | 1        | 4.35%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                              | 1        | 4.35%   |
| Intel Wi-Fi 6 AX200                                                                                 | 1        | 4.35%   |
| Intel Comet Lake PCH CNVi WiFi                                                                      | 1        | 4.35%   |
| Intel Cannon Lake PCH CNVi WiFi                                                                     | 1        | 4.35%   |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A2) [Atheros AR9170+AR9104]         | 1        | 4.35%   |
| 802.11g Adapter [Linksys WUSB54GC v3] WUSB100 v2 RangePlus Wireless Network Adapter [Ralink RT3070] | 1        | 4.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 28       | 54.9%   |
| Intel                 | 16       | 31.37%  |
| Qualcomm Atheros      | 2        | 3.92%   |
| D-Link System         | 2        | 3.92%   |
| Xiaomi                | 1        | 1.96%   |
| DisplayLink           | 1        | 1.96%   |
| Aquantia              | 1        | 1.96%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 26       | 47.27%  |
| Intel I211 Gigabit Network Connection                             | 6        | 10.91%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 3.64%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 3.64%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 3.64%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 3.64%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.82%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 1.82%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 1.82%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.82%   |
| Intel I210 Gigabit Network Connection                             | 1        | 1.82%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.82%   |
| Intel Ethernet Connection I219-LM                                 | 1        | 1.82%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.82%   |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 1.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 1.82%   |
| Intel 82567LF-2 Gigabit Network Connection                        | 1        | 1.82%   |
| Intel 82562V-2 10/100 Network Connection                          | 1        | 1.82%   |
| DisplayLink Kensington Dock (Composite Device)                    | 1        | 1.82%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.82%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 45       | 66.18%  |
| WiFi     | 22       | 32.35%  |
| Modem    | 1        | 1.47%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 34       | 77.27%  |
| WiFi     | 10       | 22.73%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 24       | 53.33%  |
| 2     | 19       | 42.22%  |
| 4     | 2        | 4.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 41       | 91.11%  |
| Yes  | 4        | 8.89%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 8        | 47.06%  |
| IMC Networks                    | 3        | 17.65%  |
| Cambridge Silicon Radio         | 2        | 11.76%  |
| Qualcomm Atheros Communications | 1        | 5.88%   |
| HTC (High Tech Computer)        | 1        | 5.88%   |
| Broadcom                        | 1        | 5.88%   |
| ASUSTek Computer                | 1        | 5.88%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                                   | 3        | 17.65%  |
| IMC Networks Bluetooth Radio                                         | 2        | 11.76%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 2        | 11.76%  |
| Qualcomm Atheros  Bluetooth Device                                   | 1        | 5.88%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 1        | 5.88%   |
| Intel Bluetooth Device                                               | 1        | 5.88%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 1        | 5.88%   |
| Intel AX210 Bluetooth                                                | 1        | 5.88%   |
| Intel AX200 Bluetooth                                                | 1        | 5.88%   |
| IMC Networks Bluetooth Device                                        | 1        | 5.88%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 5.88%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 1        | 5.88%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 1        | 5.88%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD                                             | 33       | 36.67%  |
| Nvidia                                          | 18       | 20%     |
| Intel                                           | 17       | 18.89%  |
| C-Media Electronics                             | 5        | 5.56%   |
| Creative Labs                                   | 3        | 3.33%   |
| Logitech                                        | 2        | 2.22%   |
| Creative Technology                             | 2        | 2.22%   |
| TC Electronic                                   | 1        | 1.11%   |
| SteelSeries ApS                                 | 1        | 1.11%   |
| Realtek Semiconductor                           | 1        | 1.11%   |
| Razer USA                                       | 1        | 1.11%   |
| Native Instruments                              | 1        | 1.11%   |
| Licensed by Sony Computer Entertainment America | 1        | 1.11%   |
| Generalplus Technology                          | 1        | 1.11%   |
| Focusrite-Novation                              | 1        | 1.11%   |
| Corsair                                         | 1        | 1.11%   |
| AudioQuest                                      | 1        | 1.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 10       | 9.09%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 8        | 7.27%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 7        | 6.36%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6        | 5.45%   |
| AMD Navi 10 HDMI Audio                                                     | 5        | 4.55%   |
| Nvidia GP104 High Definition Audio Controller                              | 3        | 2.73%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3        | 2.73%   |
| Intel 200 Series PCH HD Audio                                              | 3        | 2.73%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3        | 2.73%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 1.82%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 1.82%   |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 1.82%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 1.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 1.82%   |
| Creative Labs CA0110 [Sound Blaster X-Fi Xtreme Audio]                     | 2        | 1.82%   |
| C-Media Electronics USB Audio Device                                       | 2        | 1.82%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2        | 1.82%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2        | 1.82%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2        | 1.82%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2        | 1.82%   |
| TC Electronic VoiceLive Play                                               | 1        | 0.91%   |
| SteelSeries ApS Arctis Pro Wireless                                        | 1        | 0.91%   |
| Realtek Semiconductor Realtek Audio USB                                    | 1        | 0.91%   |
| Razer USA RZ19-0229 Gaming Microphone                                      | 1        | 0.91%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 0.91%   |
| Nvidia High Definition Audio Controller                                    | 1        | 0.91%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 0.91%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 0.91%   |
| Nvidia GM200 High Definition Audio                                         | 1        | 0.91%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 0.91%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1        | 0.91%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 0.91%   |
| Nvidia Audio device                                                        | 1        | 0.91%   |
| Native Instruments Komplete Audio 6                                        | 1        | 0.91%   |
| Logitech G933 Wireless Headset Dongle                                      | 1        | 0.91%   |
| Logitech G432 Gaming Headset                                               | 1        | 0.91%   |
| Licensed by Sony Computer Entertainment America Rocksmith Guitar Adapter   | 1        | 0.91%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1        | 0.91%   |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 0.91%   |
| Intel Comet Lake PCH cAVS                                                  | 1        | 0.91%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 0.91%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 0.91%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1        | 0.91%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 0.91%   |
| Generalplus Technology IMYB 7.1 Channel                                    | 1        | 0.91%   |
| Focusrite-Novation Scarlett Solo (3rd Gen.)                                | 1        | 0.91%   |
| Creative Technology Sound Blaster Tactic(3D) Alpha                         | 1        | 0.91%   |
| Creative Technology Sound Blaster Premium HD [SBX]                         | 1        | 0.91%   |
| Creative Labs EMU20k2 [Sound Blaster X-Fi Titanium Series]                 | 1        | 0.91%   |
| Corsair HS45 Surround USB Sound Adapter                                    | 1        | 0.91%   |
| C-Media Electronics SKP PODCAST-300U                                       | 1        | 0.91%   |
| AudioQuest DragonFly                                                       | 1        | 0.91%   |
| AMD Vega 20 HDMI Audio [Radeon VII]                                        | 1        | 0.91%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 1        | 0.91%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1        | 0.91%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1        | 0.91%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 1        | 0.91%   |
| AMD Hawaii HDMI Audio [Radeon R9 290/290X / 390/390X]                      | 1        | 0.91%   |
| AMD FCH Azalia Controller                                                  | 1        | 0.91%   |
| AMD Cayman/Antilles HDMI Audio [Radeon HD 6930/6950/6970/6990]             | 1        | 0.91%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 11       | 23.4%   |
| Kingston            | 9        | 19.15%  |
| G.Skill             | 9        | 19.15%  |
| Crucial             | 4        | 8.51%   |
| Unknown             | 3        | 6.38%   |
| SK hynix            | 3        | 6.38%   |
| Samsung Electronics | 2        | 4.26%   |
| Patriot             | 2        | 4.26%   |
| Transcend           | 1        | 2.13%   |
| Micron Technology   | 1        | 2.13%   |
| AMD                 | 1        | 2.13%   |
| A-DATA Technology   | 1        | 2.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3533MT/s  | 3        | 6.12%   |
| G.Skill RAM F3-10666CL9-4GBNT 4096MB DIMM DDR3 1400MT/s  | 2        | 4.08%   |
| Crucial RAM BLS16G4D30AESB.M16FE 16GB DIMM DDR4 3200MT/s | 2        | 4.08%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 2        | 4.08%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 1        | 2.04%   |
| Unknown RAM Module 2048MB DIMM SDRAM                     | 1        | 2.04%   |
| Unknown RAM Module 2048MB DIMM 1328MT/s                  | 1        | 2.04%   |
| Transcend RAM JM2666HLB-16G 16GB DIMM DDR4 2667MT/s      | 1        | 2.04%   |
| SK hynix RAM HMA82GU7CJR8N-VK 16GB DIMM DDR4 2667MT/s    | 1        | 2.04%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s  | 1        | 2.04%   |
| SK hynix RAM HMA41GU6AFR8N-TF 8192MB DIMM DDR4 2465MT/s  | 1        | 2.04%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s      | 1        | 2.04%   |
| Samsung RAM M3 78T2863RZS-CF7 1GB DIMM DDR2 800MT/s      | 1        | 2.04%   |
| Patriot RAM PSD48G240082 8GB DIMM DDR4 2400MT/s          | 1        | 2.04%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s           | 1        | 2.04%   |
| Micron RAM 16ATF2G64HZ-2G6J1 16GB SODIMM DDR4 2667MT/s   | 1        | 2.04%   |
| Kingston RAM XJ69DF-MIE 8GB DIMM DDR4 2933MT/s           | 1        | 2.04%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s      | 1        | 2.04%   |
| Kingston RAM 99U5595-003.A00LF 2GB DIMM DDR3 1600MT/s    | 1        | 2.04%   |
| Kingston RAM 99U5584-014.A00LF 4096MB DIMM DDR3 1600MT/s | 1        | 2.04%   |
| Kingston RAM 99U5474-026.A00LF 4GB DIMM DDR3 1333MT/s    | 1        | 2.04%   |
| Kingston RAM 99U5471-020.A00LF 4096MB DIMM DDR3 1600MT/s | 1        | 2.04%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 2.04%   |
| Kingston RAM 99P5474-033.A00LF 2GB DIMM DDR3 1600MT/s    | 1        | 2.04%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s   | 1        | 2.04%   |
| G.Skill RAM F4-3200C16-8GSXWB 8GB DIMM DDR4 4133MT/s     | 1        | 2.04%   |
| G.Skill RAM F4-3200C16-8GIS 8192MB DIMM DDR4 3200MT/s    | 1        | 2.04%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s      | 1        | 2.04%   |
| G.Skill RAM F4-2400C15-4GRR 4096MB DIMM DDR4 2133MT/s    | 1        | 2.04%   |
| G.Skill RAM F3-2400C10-4GTX 4GB DIMM DDR3 2400MT/s       | 1        | 2.04%   |
| G.Skill RAM F3-1866C10-8G 8192MB DIMM DDR3 1600MT/s      | 1        | 2.04%   |
| Crucial RAM CT102464BD160B.C16 8GB DIMM DDR3 1600MT/s    | 1        | 2.04%   |
| Crucial RAM BL16G32C16U4BL.M16FE 16GB DIMM DDR4 3200MT/s | 1        | 2.04%   |
| Corsair RAM Module 4096MB DIMM DDR3 2481MT/s             | 1        | 2.04%   |
| Corsair RAM CMZ8GX3M2A160 4096MB DIMM DDR3 1333MT/s      | 1        | 2.04%   |
| Corsair RAM CMZ4GX3M1A160 4GB DIMM DDR3 1333MT/s         | 1        | 2.04%   |
| Corsair RAM CMY16GX3M2A1600C9 8192MB DIMM DDR3 2133MT/s  | 1        | 2.04%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3266MT/s    | 1        | 2.04%   |
| Corsair RAM CML8GX3M1A1600C10 8192MB DIMM DDR3 1600MT/s  | 1        | 2.04%   |
| Corsair RAM CMK16GX4M2D3600C18 8192MB DIMM DDR4 3600MT/s | 1        | 2.04%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s    | 1        | 2.04%   |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3000MT/s | 1        | 2.04%   |
| AMD RAM R534G1601U1S 4GB DIMM DDR3 1600MT/s              | 1        | 2.04%   |
| A-DATA RAM Module 32GB DIMM DDR4 3200MT/s                | 1        | 2.04%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 23       | 57.5%   |
| DDR3    | 13       | 32.5%   |
| Unknown | 2        | 5%      |
| SDRAM   | 1        | 2.5%    |
| DDR2    | 1        | 2.5%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 39       | 97.5%   |
| SODIMM | 1        | 2.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 18       | 41.86%  |
| 4096  | 13       | 30.23%  |
| 16384 | 7        | 16.28%  |
| 2048  | 3        | 6.98%   |
| 32768 | 1        | 2.33%   |
| 1024  | 1        | 2.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 8        | 17.78%  |
| 3200    | 7        | 15.56%  |
| 3600    | 4        | 8.89%   |
| 1333    | 4        | 8.89%   |
| 3533    | 3        | 6.67%   |
| 2667    | 3        | 6.67%   |
| 2933    | 2        | 4.44%   |
| 2400    | 2        | 4.44%   |
| 2133    | 2        | 4.44%   |
| 1400    | 2        | 4.44%   |
| 4133    | 1        | 2.22%   |
| 3466    | 1        | 2.22%   |
| 3266    | 1        | 2.22%   |
| 2481    | 1        | 2.22%   |
| 2465    | 1        | 2.22%   |
| 1328    | 1        | 2.22%   |
| 800     | 1        | 2.22%   |
| Unknown | 1        | 2.22%   |

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
| Logitech                      | 3        | 30%     |
| Creative Technology           | 2        | 20%     |
| Sunplus Innovation Technology | 1        | 10%     |
| Microsoft                     | 1        | 10%     |
| KYE Systems (Mouse Systems)   | 1        | 10%     |
| GEMBIRD                       | 1        | 10%     |
| ARC International             | 1        | 10%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Sunplus Aukey-PC-LM1E Camera                   | 1        | 10%     |
| Microsoft LifeCam Cinema                       | 1        | 10%     |
| Logitech Webcam C930e                          | 1        | 10%     |
| Logitech Webcam C310                           | 1        | 10%     |
| Logitech Webcam C270                           | 1        | 10%     |
| KYE Systems (Mouse Systems) Genius FaceCam 320 | 1        | 10%     |
| GEMBIRD USB2.0 PC CAMERA                       | 1        | 10%     |
| Creative Live! Cam Sync HD [VF0770]            | 1        | 10%     |
| Creative Live! Cam Chat HD [VF0700]            | 1        | 10%     |
| ARC International Camera                       | 1        | 10%     |

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
| 0     | 40       | 88.89%  |
| 1     | 5        | 11.11%  |

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

