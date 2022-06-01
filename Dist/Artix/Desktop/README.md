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

Total: 66

| Vendor    | Model                   | Probe                                                      | Date         |
|-----------|-------------------------|------------------------------------------------------------|--------------|
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
| Artix Rolling  | 28       | 62.22%  |
| Artix          | 14       | 31.11%  |
| Artix 20210726 | 2        | 4.44%   |
| Artix 20220123 | 1        | 2.22%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| Artix | 43       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.10.8-artix1-1        | 3        | 5.88%   |
| 5.9.14-artix1-1        | 2        | 3.92%   |
| 5.8.8-artix1-1         | 2        | 3.92%   |
| 5.8.12-artix1-1        | 2        | 3.92%   |
| 5.7.6-artix1-1         | 2        | 3.92%   |
| 5.7.12-artix1-1        | 2        | 3.92%   |
| 5.15.12-artix1-1       | 2        | 3.92%   |
| 5.12.14-artix1-1       | 2        | 3.92%   |
| 5.12.12-artix1-1       | 2        | 3.92%   |
| 5.10.4-artix2-1        | 2        | 3.92%   |
| 5.9.8-zen1-1-zen       | 1        | 1.96%   |
| 5.9.14-zen1-1-zen      | 1        | 1.96%   |
| 5.9.12-artix1-1        | 1        | 1.96%   |
| 5.9.10-artix1-1        | 1        | 1.96%   |
| 5.8.5-xanmod1-1-xanmod | 1        | 1.96%   |
| 5.8.14-artix1-1        | 1        | 1.96%   |
| 5.7.2-artix1-1         | 1        | 1.96%   |
| 5.17.8-258-tkg-pds     | 1        | 1.96%   |
| 5.17.4-artix1-1        | 1        | 1.96%   |
| 5.16.3-artix1-1        | 1        | 1.96%   |
| 5.16.12-artix1-1       | 1        | 1.96%   |
| 5.16.10-artix1-1       | 1        | 1.96%   |
| 5.16.1-artix1-1        | 1        | 1.96%   |
| 5.15.3-zen1-1-zen      | 1        | 1.96%   |
| 5.15.2-zen1-1-zen      | 1        | 1.96%   |
| 5.15.13-zen1-1-zen     | 1        | 1.96%   |
| 5.14.3-198-tkg-bmq     | 1        | 1.96%   |
| 5.14.10-artix1-1       | 1        | 1.96%   |
| 5.13.8-188-tkg-pds     | 1        | 1.96%   |
| 5.13.4-artix1-1        | 1        | 1.96%   |
| 5.12.2-artix1-1        | 1        | 1.96%   |
| 5.11.16-artix1-1       | 1        | 1.96%   |
| 5.11.11-zen1-1-zen     | 1        | 1.96%   |
| 5.10.7                 | 1        | 1.96%   |
| 5.10.6-artix1-1        | 1        | 1.96%   |
| 5.10.16-artix1-1       | 1        | 1.96%   |
| 5.10.15-zen1-1-zen     | 1        | 1.96%   |
| 5.10.15-artix1-1       | 1        | 1.96%   |
| 5.10.11-zen2-1-zen     | 1        | 1.96%   |
| 4.19.0-1-MANJARO       | 1        | 1.96%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.9.14  | 3        | 5.88%   |
| 5.10.8  | 3        | 5.88%   |
| 5.8.8   | 2        | 3.92%   |
| 5.8.12  | 2        | 3.92%   |
| 5.7.6   | 2        | 3.92%   |
| 5.7.12  | 2        | 3.92%   |
| 5.15.12 | 2        | 3.92%   |
| 5.12.14 | 2        | 3.92%   |
| 5.12.12 | 2        | 3.92%   |
| 5.10.4  | 2        | 3.92%   |
| 5.10.15 | 2        | 3.92%   |
| 5.9.8   | 1        | 1.96%   |
| 5.9.12  | 1        | 1.96%   |
| 5.9.10  | 1        | 1.96%   |
| 5.8.5   | 1        | 1.96%   |
| 5.8.14  | 1        | 1.96%   |
| 5.7.2   | 1        | 1.96%   |
| 5.17.8  | 1        | 1.96%   |
| 5.17.4  | 1        | 1.96%   |
| 5.16.3  | 1        | 1.96%   |
| 5.16.12 | 1        | 1.96%   |
| 5.16.10 | 1        | 1.96%   |
| 5.16.1  | 1        | 1.96%   |
| 5.15.3  | 1        | 1.96%   |
| 5.15.2  | 1        | 1.96%   |
| 5.15.13 | 1        | 1.96%   |
| 5.14.3  | 1        | 1.96%   |
| 5.14.10 | 1        | 1.96%   |
| 5.13.8  | 1        | 1.96%   |
| 5.13.4  | 1        | 1.96%   |
| 5.12.2  | 1        | 1.96%   |
| 5.11.16 | 1        | 1.96%   |
| 5.11.11 | 1        | 1.96%   |
| 5.10.7  | 1        | 1.96%   |
| 5.10.6  | 1        | 1.96%   |
| 5.10.16 | 1        | 1.96%   |
| 5.10.11 | 1        | 1.96%   |
| 4.19.0  | 1        | 1.96%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 10       | 20.41%  |
| 5.9     | 6        | 12.24%  |
| 5.8     | 6        | 12.24%  |
| 5.15    | 5        | 10.2%   |
| 5.12    | 5        | 10.2%   |
| 5.7     | 4        | 8.16%   |
| 5.16    | 4        | 8.16%   |
| 5.17    | 2        | 4.08%   |
| 5.14    | 2        | 4.08%   |
| 5.13    | 2        | 4.08%   |
| 5.11    | 2        | 4.08%   |
| 4.19    | 1        | 2.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 43       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| KDE5       | 10       | 21.28%  |
| GNOME      | 8        | 17.02%  |
| XFCE       | 6        | 12.77%  |
| X-Cinnamon | 5        | 10.64%  |
| Unknown    | 5        | 10.64%  |
| MATE       | 3        | 6.38%   |
| Cinnamon   | 2        | 4.26%   |
| bspwm      | 2        | 4.26%   |
| sway       | 1        | 2.13%   |
| openbox    | 1        | 2.13%   |
| LXQt       | 1        | 2.13%   |
| LXDE       | 1        | 2.13%   |
| i3         | 1        | 2.13%   |
| dwm        | 1        | 2.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 31       | 68.89%  |
| Tty     | 9        | 20%     |
| Wayland | 3        | 6.67%   |
| Unknown | 2        | 4.44%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 18       | 39.13%  |
| SDDM    | 14       | 30.43%  |
| LightDM | 11       | 23.91%  |
| XDM     | 1        | 2.17%   |
| LXDM    | 1        | 2.17%   |
| GDM     | 1        | 2.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 16       | 37.21%  |
| fr_FR   | 5        | 11.63%  |
| Unknown | 4        | 9.3%    |
| C       | 3        | 6.98%   |
| ru_RU   | 2        | 4.65%   |
| pt_PT   | 2        | 4.65%   |
| de_DE   | 2        | 4.65%   |
| ja_JP   | 1        | 2.33%   |
| it_IT   | 1        | 2.33%   |
| es_MX   | 1        | 2.33%   |
| es_AR   | 1        | 2.33%   |
| en_IE   | 1        | 2.33%   |
| en_GB   | 1        | 2.33%   |
| en_AU   | 1        | 2.33%   |
| el_GR   | 1        | 2.33%   |
| bg_BG   | 1        | 2.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 30       | 68.18%  |
| BIOS | 14       | 31.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 29       | 67.44%  |
| Btrfs | 9        | 20.93%  |
| Xfs   | 2        | 4.65%   |
| F2fs  | 2        | 4.65%   |
| Jfs   | 1        | 2.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 34       | 75.56%  |
| Unknown | 8        | 17.78%  |
| MBR     | 3        | 6.67%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 31       | 70.45%  |
| Yes       | 13       | 29.55%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 31       | 70.45%  |
| Yes       | 13       | 29.55%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 14       | 32.56%  |
| Gigabyte Technology | 9        | 20.93%  |
| MSI                 | 8        | 18.6%   |
| ASRock              | 5        | 11.63%  |
| Hewlett-Packard     | 2        | 4.65%   |
| Dell                | 2        | 4.65%   |
| Intel               | 1        | 2.33%   |
| Biostar             | 1        | 2.33%   |
| Alienware           | 1        | 2.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| MSI MS-7C02                  | 2        | 4.65%   |
| MSI MS-7A38                  | 2        | 4.65%   |
| Gigabyte 970A-DS3P           | 2        | 4.65%   |
| MSI MS-7C56                  | 1        | 2.33%   |
| MSI MS-7C37                  | 1        | 2.33%   |
| MSI MS-7B79                  | 1        | 2.33%   |
| MSI MS-7A69                  | 1        | 2.33%   |
| Intel DX58SO2 AAG10925-205   | 1        | 2.33%   |
| HP Compaq 8200 Elite SFF PC  | 1        | 2.33%   |
| HP 280 G1 MT                 | 1        | 2.33%   |
| Gigabyte X570 AORUS ULTRA    | 1        | 2.33%   |
| Gigabyte X570 AORUS ELITE    | 1        | 2.33%   |
| Gigabyte X399 AORUS XTREME   | 1        | 2.33%   |
| Gigabyte P55-USB3            | 1        | 2.33%   |
| Gigabyte HA65M-D2H-B3        | 1        | 2.33%   |
| Gigabyte 990FXA-UD5          | 1        | 2.33%   |
| Gigabyte 990FXA-UD3 R5       | 1        | 2.33%   |
| Dell OptiPlex 5080           | 1        | 2.33%   |
| Dell Inspiron 530            | 1        | 2.33%   |
| Biostar G31D-M7              | 1        | 2.33%   |
| ASUS TUF Gaming X570-PLUS    | 1        | 2.33%   |
| ASUS TUF B450-PLUS GAMING    | 1        | 2.33%   |
| ASUS SABERTOOTH 990FX R2.0   | 1        | 2.33%   |
| ASUS ROG STRIX X570-F GAMING | 1        | 2.33%   |
| ASUS ROG STRIX B550-F GAMING | 1        | 2.33%   |
| ASUS ROG Maximus XI HERO     | 1        | 2.33%   |
| ASUS Pro WS X570-ACE         | 1        | 2.33%   |
| ASUS PRIME X370-PRO          | 1        | 2.33%   |
| ASUS PRIME B450M-A           | 1        | 2.33%   |
| ASUS PRIME B350M-A           | 1        | 2.33%   |
| ASUS P8H61-M LX3 R2.0        | 1        | 2.33%   |
| ASUS P8B75-M LX PLUS         | 1        | 2.33%   |
| ASUS G11CD                   | 1        | 2.33%   |
| ASUS All Series              | 1        | 2.33%   |
| ASRock X570 Phantom Gaming 4 | 1        | 2.33%   |
| ASRock H310CM-DVS            | 1        | 2.33%   |
| ASRock FM2A88X-ITX+          | 1        | 2.33%   |
| ASRock B450 Steel Legend     | 1        | 2.33%   |
| ASRock B150M Pro4S/D3        | 1        | 2.33%   |
| Alienware Aurora R8          | 1        | 2.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS ROG              | 3        | 6.98%   |
| ASUS PRIME            | 3        | 6.98%   |
| MSI MS-7C02           | 2        | 4.65%   |
| MSI MS-7A38           | 2        | 4.65%   |
| Gigabyte X570         | 2        | 4.65%   |
| Gigabyte 970A-DS3P    | 2        | 4.65%   |
| ASUS TUF              | 2        | 4.65%   |
| MSI MS-7C56           | 1        | 2.33%   |
| MSI MS-7C37           | 1        | 2.33%   |
| MSI MS-7B79           | 1        | 2.33%   |
| MSI MS-7A69           | 1        | 2.33%   |
| Intel DX58SO2         | 1        | 2.33%   |
| HP Compaq             | 1        | 2.33%   |
| HP 280                | 1        | 2.33%   |
| Gigabyte X399         | 1        | 2.33%   |
| Gigabyte P55-USB3     | 1        | 2.33%   |
| Gigabyte HA65M-D2H-B3 | 1        | 2.33%   |
| Gigabyte 990FXA-UD5   | 1        | 2.33%   |
| Gigabyte 990FXA-UD3   | 1        | 2.33%   |
| Dell OptiPlex         | 1        | 2.33%   |
| Dell Inspiron         | 1        | 2.33%   |
| Biostar G31D-M7       | 1        | 2.33%   |
| ASUS SABERTOOTH       | 1        | 2.33%   |
| ASUS Pro              | 1        | 2.33%   |
| ASUS P8H61-M          | 1        | 2.33%   |
| ASUS P8B75-M          | 1        | 2.33%   |
| ASUS G11CD            | 1        | 2.33%   |
| ASUS All              | 1        | 2.33%   |
| ASRock X570           | 1        | 2.33%   |
| ASRock H310CM-DVS     | 1        | 2.33%   |
| ASRock FM2A88X-ITX+   | 1        | 2.33%   |
| ASRock B450           | 1        | 2.33%   |
| ASRock B150M          | 1        | 2.33%   |
| Alienware Aurora      | 1        | 2.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 10       | 23.26%  |
| 2020 | 5        | 11.63%  |
| 2018 | 5        | 11.63%  |
| 2017 | 5        | 11.63%  |
| 2013 | 4        | 9.3%    |
| 2015 | 3        | 6.98%   |
| 2012 | 3        | 6.98%   |
| 2011 | 2        | 4.65%   |
| 2010 | 2        | 4.65%   |
| 2008 | 2        | 4.65%   |
| 2016 | 1        | 2.33%   |
| 2014 | 1        | 2.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 43       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 43       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 43       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 18       | 40.91%  |
| 8.01-16.0   | 11       | 25%     |
| 32.01-64.0  | 6        | 13.64%  |
| 3.01-4.0    | 4        | 9.09%   |
| 64.01-256.0 | 4        | 9.09%   |
| 1.01-2.0    | 1        | 2.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 13       | 27.66%  |
| 3.01-4.0   | 9        | 19.15%  |
| 2.01-3.0   | 9        | 19.15%  |
| 1.01-2.0   | 9        | 19.15%  |
| 0.51-1.0   | 3        | 6.38%   |
| 0.01-0.5   | 2        | 4.26%   |
| 16.01-24.0 | 1        | 2.13%   |
| 8.01-16.0  | 1        | 2.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 17       | 37.78%  |
| 3      | 12       | 26.67%  |
| 1      | 8        | 17.78%  |
| 4      | 4        | 8.89%   |
| 6      | 2        | 4.44%   |
| 8      | 1        | 2.22%   |
| 7      | 1        | 2.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 30       | 69.77%  |
| Yes       | 13       | 30.23%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 43       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 53.49%  |
| Yes       | 20       | 46.51%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 27       | 62.79%  |
| Yes       | 16       | 37.21%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Germany     | 8        | 18.18%  |
| France      | 7        | 15.91%  |
| USA         | 6        | 13.64%  |
| Russia      | 3        | 6.82%   |
| Greece      | 3        | 6.82%   |
| Switzerland | 2        | 4.55%   |
| Poland      | 2        | 4.55%   |
| Bulgaria    | 2        | 4.55%   |
| Ukraine     | 1        | 2.27%   |
| UK          | 1        | 2.27%   |
| Mexico      | 1        | 2.27%   |
| Japan       | 1        | 2.27%   |
| Italy       | 1        | 2.27%   |
| Iran        | 1        | 2.27%   |
| Hong Kong   | 1        | 2.27%   |
| Finland     | 1        | 2.27%   |
| Austria     | 1        | 2.27%   |
| Australia   | 1        | 2.27%   |
| Argentina   | 1        | 2.27%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Paris                  | 3        | 6.38%   |
| Frankfurt am Main      | 2        | 4.26%   |
| Bern                   | 2        | 4.26%   |
| Athens                 | 2        | 4.26%   |
| Wettringen             | 1        | 2.13%   |
| Vienna                 | 1        | 2.13%   |
| Upper Norwood          | 1        | 2.13%   |
| Ufa                    | 1        | 2.13%   |
| Thessaloniki           | 1        | 2.13%   |
| Tehran                 | 1        | 2.13%   |
| Sydney                 | 1        | 2.13%   |
| Stein                  | 1        | 2.13%   |
| Statesboro             | 1        | 2.13%   |
| Sofia                  | 1        | 2.13%   |
| Snohomish              | 1        | 2.13%   |
| Shavertown             | 1        | 2.13%   |
| San Miguel de Tucumán | 1        | 2.13%   |
| Riverview              | 1        | 2.13%   |
| Plovdiv                | 1        | 2.13%   |
| Moscow                 | 1        | 2.13%   |
| Maebashi               | 1        | 2.13%   |
| Lublin                 | 1        | 2.13%   |
| Kłodzko               | 1        | 2.13%   |
| Koga                   | 1        | 2.13%   |
| Kazan’               | 1        | 2.13%   |
| Helsinki               | 1        | 2.13%   |
| Gochsheim              | 1        | 2.13%   |
| Factoryville           | 1        | 2.13%   |
| Essen                  | 1        | 2.13%   |
| Dnipro                 | 1        | 2.13%   |
| Clarks Summit          | 1        | 2.13%   |
| Ciudad Victoria        | 1        | 2.13%   |
| Chatenois              | 1        | 2.13%   |
| Charlotte              | 1        | 2.13%   |
| Central                | 1        | 2.13%   |
| Castel Maggiore        | 1        | 2.13%   |
| Bourges                | 1        | 2.13%   |
| Bochum                 | 1        | 2.13%   |
| Besançon              | 1        | 2.13%   |
| Berlin                 | 1        | 2.13%   |
| Austin                 | 1        | 2.13%   |
| Argenteuil             | 1        | 2.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 19       | 36     | 19.39%  |
| Seagate             | 18       | 23     | 18.37%  |
| Samsung Electronics | 13       | 21     | 13.27%  |
| Kingston            | 8        | 8      | 8.16%   |
| Crucial             | 7        | 11     | 7.14%   |
| Toshiba             | 6        | 7      | 6.12%   |
| SanDisk             | 4        | 6      | 4.08%   |
| Intel               | 4        | 7      | 4.08%   |
| MAXTOR              | 2        | 2      | 2.04%   |
| JMicron             | 2        | 2      | 2.04%   |
| Hitachi             | 2        | 2      | 2.04%   |
| Corsair             | 2        | 2      | 2.04%   |
| Transcend           | 1        | 1      | 1.02%   |
| SPCC                | 1        | 1      | 1.02%   |
| SK Hynix            | 1        | 1      | 1.02%   |
| PNY                 | 1        | 1      | 1.02%   |
| Phison              | 1        | 1      | 1.02%   |
| Linux               | 1        | 1      | 1.02%   |
| HGST                | 1        | 2      | 1.02%   |
| Hewlett-Packard     | 1        | 1      | 1.02%   |
| GOODRAM             | 1        | 1      | 1.02%   |
| China               | 1        | 1      | 1.02%   |
| AMD                 | 1        | 1      | 1.02%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB             | 3        | 2.63%   |
| Seagate ST3500418AS 500GB          | 3        | 2.63%   |
| Seagate ST1000DM010-2EP102 1TB     | 3        | 2.63%   |
| Samsung SSD 860 EVO 250GB          | 3        | 2.63%   |
| WDC WD80EZAZ-11TDBA0 8TB           | 2        | 1.75%   |
| WDC WD10EZEX-08WN4A0 1TB           | 2        | 1.75%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2        | 1.75%   |
| Samsung SSD 970 EVO 1TB            | 2        | 1.75%   |
| Kingston SA400S37120G 120GB SSD    | 2        | 1.75%   |
| Crucial CT240BX500SSD1 240GB       | 2        | 1.75%   |
| WDC WDS500G2B0C-00PXH0 500GB       | 1        | 0.88%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 1        | 0.88%   |
| WDC WDS256G1X0C-00ENX0 256GB       | 1        | 0.88%   |
| WDC WDS100T2B0C-00PXH0 1TB         | 1        | 0.88%   |
| WDC WDS100T2B0A-00SM50 1TB SSD     | 1        | 0.88%   |
| WDC WDBNCE5000PNC 500GB SSD        | 1        | 0.88%   |
| WDC WD6001FZWX-00A2VA0 6TB         | 1        | 0.88%   |
| WDC WD5003ABYX-18WERA0 500GB       | 1        | 0.88%   |
| WDC WD5000LPVX-00V0TT0 500GB       | 1        | 0.88%   |
| WDC WD5000AAKX-60U6AA0 500GB       | 1        | 0.88%   |
| WDC WD40EZRZ-00WN9B0 4TB           | 1        | 0.88%   |
| WDC WD4003FZEX-00Z4SA0 4TB         | 1        | 0.88%   |
| WDC WD4003FFBX-68MU3N0 4TB         | 1        | 0.88%   |
| WDC WD30EZRX-00DC0B0 3TB           | 1        | 0.88%   |
| WDC WD30EFRX-68EUZN0 3TB           | 1        | 0.88%   |
| WDC WD2500HHTZ-04N21V0 250GB       | 1        | 0.88%   |
| WDC WD20EZRX-00D8PB0 2TB           | 1        | 0.88%   |
| WDC WD20EZBX-00AYRA0 2TB           | 1        | 0.88%   |
| WDC WD20EARS-00MVWB0 2TB           | 1        | 0.88%   |
| WDC WD2003FZEX-00SRLA0 2TB         | 1        | 0.88%   |
| WDC WD15EARS-22MVWB0 1TB           | 1        | 0.88%   |
| WDC WD10EZRZ-00HTKB0 1TB           | 1        | 0.88%   |
| WDC WD10EZEX-00BN5A0 1TB           | 1        | 0.88%   |
| WDC WD100EMAZ-00WJTA0 10TB         | 1        | 0.88%   |
| Transcend TS1TMTE220S 1TB          | 1        | 0.88%   |
| Toshiba MK7575GSX 752GB            | 1        | 0.88%   |
| Toshiba HDWD130 3TB                | 1        | 0.88%   |
| Toshiba HDWD110 1TB                | 1        | 0.88%   |
| SPCC Solid State Disk 240GB        | 1        | 0.88%   |
| SK Hynix PC601 NVMe 512GB          | 1        | 0.88%   |
| Seagate ST8000DM004-2CX188 8TB     | 1        | 0.88%   |
| Seagate ST500DM002-1SB10A 500GB    | 1        | 0.88%   |
| Seagate ST500DM002-1BD142 500GB    | 1        | 0.88%   |
| Seagate ST3600057SS 600GB          | 1        | 0.88%   |
| Seagate ST31000524AS 1TB           | 1        | 0.88%   |
| Seagate ST3000DM001-1CH166 3TB     | 1        | 0.88%   |
| Seagate ST2000LX001-1RG174 2TB     | 1        | 0.88%   |
| Seagate ST2000DX002-2DV164 2TB     | 1        | 0.88%   |
| Seagate ST2000DM006-2DM164 2TB     | 1        | 0.88%   |
| Seagate ST1000NM0011 1TB           | 1        | 0.88%   |
| Seagate ST1000DM003-1SB10C 1TB     | 1        | 0.88%   |
| Seagate ST1000DM003-1ER162 1TB     | 1        | 0.88%   |
| SanDisk SSD PLUS 1000GB            | 1        | 0.88%   |
| SanDisk SDSSDHII480G 480GB         | 1        | 0.88%   |
| Sandisk NVMe SSD Drive 500GB       | 1        | 0.88%   |
| Sandisk NVMe SSD Drive 256GB       | 1        | 0.88%   |
| Samsung SSD 970 PRO 1TB            | 1        | 0.88%   |
| Samsung SSD 970 EVO Plus 500GB     | 1        | 0.88%   |
| Samsung SSD 970 EVO 500GB          | 1        | 0.88%   |
| Samsung SSD 960 EVO 250GB          | 1        | 0.88%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 18       | 23     | 40%     |
| WDC     | 16       | 28     | 35.56%  |
| Toshiba | 6        | 7      | 13.33%  |
| MAXTOR  | 2        | 2      | 4.44%   |
| Hitachi | 2        | 2      | 4.44%   |
| HGST    | 1        | 2      | 2.22%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 8        | 11     | 22.86%  |
| Crucial             | 7        | 11     | 20%     |
| Kingston            | 6        | 6      | 17.14%  |
| WDC                 | 3        | 5      | 8.57%   |
| SanDisk             | 2        | 2      | 5.71%   |
| JMicron             | 2        | 2      | 5.71%   |
| Intel               | 2        | 3      | 5.71%   |
| SPCC                | 1        | 1      | 2.86%   |
| Linux               | 1        | 1      | 2.86%   |
| GOODRAM             | 1        | 1      | 2.86%   |
| China               | 1        | 1      | 2.86%   |
| AMD                 | 1        | 1      | 2.86%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 35       | 64     | 42.68%  |
| SSD  | 29       | 45     | 35.37%  |
| NVMe | 18       | 30     | 21.95%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 40       | 106    | 65.57%  |
| NVMe | 18       | 30     | 29.51%  |
| SAS  | 3        | 3      | 4.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 31       | 53     | 43.06%  |
| 0.51-1.0   | 23       | 31     | 31.94%  |
| 1.01-2.0   | 8        | 9      | 11.11%  |
| 2.01-3.0   | 4        | 4      | 5.56%   |
| 3.01-4.0   | 3        | 3      | 4.17%   |
| 4.01-10.0  | 3        | 9      | 4.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 9        | 20.45%  |
| 101-250        | 9        | 20.45%  |
| 1001-2000      | 9        | 20.45%  |
| 2001-3000      | 8        | 18.18%  |
| 501-1000       | 4        | 9.09%   |
| 251-500        | 3        | 6.82%   |
| 51-100         | 2        | 4.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 11       | 24.44%  |
| 251-500        | 6        | 13.33%  |
| 1001-2000      | 6        | 13.33%  |
| 1-20           | 6        | 13.33%  |
| More than 3000 | 5        | 11.11%  |
| 101-250        | 5        | 11.11%  |
| 21-50          | 2        | 4.44%   |
| 2001-3000      | 2        | 4.44%   |
| 51-100         | 2        | 4.44%   |

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
| MAXTOR 6Y080M0 81GB              | 1        | 1      | 9.09%   |
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
| MAXTOR          | 1        | 1      | 9.09%   |
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
| MAXTOR  | 1        | 1      | 16.67%  |

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
| Works    | 30       | 79     | 54.55%  |
| Detected | 15       | 48     | 27.27%  |
| Malfunc  | 10       | 12     | 18.18%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| AMD                         | 26       | 36.11%  |
| Intel                       | 18       | 25%     |
| Samsung Electronics         | 7        | 9.72%   |
| Sandisk                     | 4        | 5.56%   |
| Marvell Technology Group    | 4        | 5.56%   |
| Phison Electronics          | 3        | 4.17%   |
| ASMedia Technology          | 3        | 4.17%   |
| Silicon Motion              | 2        | 2.78%   |
| Kingston Technology Company | 2        | 2.78%   |
| SK Hynix                    | 1        | 1.39%   |
| JMicron Technology          | 1        | 1.39%   |
| Broadcom / LSI              | 1        | 1.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 18       | 20%     |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6        | 6.67%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6        | 6.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 5.56%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 3.33%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 3.33%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 3.33%   |
| Phison E12 NVMe Controller                                                              | 2        | 2.22%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 2        | 2.22%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 2.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2        | 2.22%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 2.22%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 2.22%   |
| SK Hynix Non-Volatile memory controller                                                 | 1        | 1.11%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 1.11%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 1.11%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 1        | 1.11%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 1        | 1.11%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 1.11%   |
| Sandisk WD Black NVMe SSD                                                               | 1        | 1.11%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 1.11%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 1.11%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                                   | 1        | 1.11%   |
| Marvell Group 88SE912x IDE Controller                                                   | 1        | 1.11%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                                    | 1        | 1.11%   |
| Kingston Company Company Non-Volatile memory controller                                 | 1        | 1.11%   |
| Kingston Company A2000 NVMe SSD                                                         | 1        | 1.11%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 1.11%   |
| Intel SSD 660P Series                                                                   | 1        | 1.11%   |
| Intel SSD 600P Series                                                                   | 1        | 1.11%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 1.11%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1        | 1.11%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 1.11%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 1.11%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1        | 1.11%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1        | 1.11%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 1.11%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 1.11%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                              | 1        | 1.11%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.11%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.11%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 1.11%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 1        | 1.11%   |
| AMD X399 Series Chipset SATA Controller                                                 | 1        | 1.11%   |
| AMD X370 Series Chipset SATA Controller                                                 | 1        | 1.11%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 1.11%   |
| AMD FCH IDE Controller                                                                  | 1        | 1.11%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 40       | 58.82%  |
| NVMe | 18       | 26.47%  |
| IDE  | 8        | 11.76%  |
| RAID | 1        | 1.47%   |
| SAS  | 1        | 1.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 26       | 60.47%  |
| Intel  | 17       | 39.53%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD Ryzen 9 3900X 12-Core Processor             | 3        | 6.98%   |
| AMD FX-8350 Eight-Core Processor                | 3        | 6.98%   |
| Intel Core i7-9700K CPU @ 3.60GHz               | 2        | 4.65%   |
| Intel Core i5-2500 CPU @ 3.30GHz                | 2        | 4.65%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 2        | 4.65%   |
| AMD Ryzen 5 3600 6-Core Processor               | 2        | 4.65%   |
| AMD Ryzen 5 2600X Six-Core Processor            | 2        | 4.65%   |
| Intel Core i7-9700F CPU @ 3.00GHz               | 1        | 2.33%   |
| Intel Core i7-4790K CPU @ 4.00GHz               | 1        | 2.33%   |
| Intel Core i7 CPU 970 @ 3.20GHz                 | 1        | 2.33%   |
| Intel Core i5-7600K CPU @ 3.80GHz               | 1        | 2.33%   |
| Intel Core i5-6600K CPU @ 3.50GHz               | 1        | 2.33%   |
| Intel Core i5-6400 CPU @ 2.70GHz                | 1        | 2.33%   |
| Intel Core i5-3330 CPU @ 3.00GHz                | 1        | 2.33%   |
| Intel Core i5-2310 CPU @ 2.90GHz                | 1        | 2.33%   |
| Intel Core i5-10500T CPU @ 2.30GHz              | 1        | 2.33%   |
| Intel Core i5 CPU 660 @ 3.33GHz                 | 1        | 2.33%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz            | 1        | 2.33%   |
| Intel Core 2 Duo CPU E4600 @ 2.40GHz            | 1        | 2.33%   |
| Intel Celeron CPU G1840 @ 2.80GHz               | 1        | 2.33%   |
| AMD Ryzen Threadripper 2990WX 32-Core Processor | 1        | 2.33%   |
| AMD Ryzen 9 3900XT 12-Core Processor            | 1        | 2.33%   |
| AMD Ryzen 7 5800X 8-Core Processor              | 1        | 2.33%   |
| AMD Ryzen 7 5700G with Radeon Graphics          | 1        | 2.33%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 1        | 2.33%   |
| AMD Ryzen 7 1700 Eight-Core Processor           | 1        | 2.33%   |
| AMD Ryzen 5 5600X 6-Core Processor              | 1        | 2.33%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 1        | 2.33%   |
| AMD Ryzen 5 1600 Six-Core Processor             | 1        | 2.33%   |
| AMD Ryzen 5 1500X Quad-Core Processor           | 1        | 2.33%   |
| AMD Ryzen 3 1200 Quad-Core Processor            | 1        | 2.33%   |
| AMD Phenom II X4 955 Processor                  | 1        | 2.33%   |
| AMD FX-6300 Six-Core Processor                  | 1        | 2.33%   |
| AMD A10-7870K Radeon R7, 12 Compute Cores 4C+8G | 1        | 2.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 9        | 20.93%  |
| AMD Ryzen 5            | 8        | 18.6%   |
| AMD Ryzen 7            | 6        | 13.95%  |
| Intel Core i7          | 5        | 11.63%  |
| AMD Ryzen 9            | 4        | 9.3%    |
| AMD FX                 | 4        | 9.3%    |
| Intel Core 2 Duo       | 2        | 4.65%   |
| Intel Celeron          | 1        | 2.33%   |
| AMD Ryzen Threadripper | 1        | 2.33%   |
| AMD Ryzen 3            | 1        | 2.33%   |
| AMD Phenom II X4       | 1        | 2.33%   |
| AMD A10                | 1        | 2.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 13       | 30.23%  |
| 8      | 9        | 20.93%  |
| 6      | 9        | 20.93%  |
| 2      | 5        | 11.63%  |
| 12     | 4        | 9.3%    |
| 3      | 2        | 4.65%   |
| 32     | 1        | 2.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 43       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 28       | 65.12%  |
| 1      | 15       | 34.88%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 43       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 9        | 20%     |
| 0x08701013 | 4        | 8.89%   |
| 0x08701021 | 3        | 6.67%   |
| 0x0800820d | 3        | 6.67%   |
| 0x06000822 | 3        | 6.67%   |
| 0x906ed    | 2        | 4.44%   |
| 0x506e3    | 2        | 4.44%   |
| 0x306c3    | 2        | 4.44%   |
| 0x206a7    | 2        | 4.44%   |
| 0xa0653    | 1        | 2.22%   |
| 0x906e9    | 1        | 2.22%   |
| 0x6fd      | 1        | 2.22%   |
| 0x306a9    | 1        | 2.22%   |
| 0x206c2    | 1        | 2.22%   |
| 0x20652    | 1        | 2.22%   |
| 0x1067a    | 1        | 2.22%   |
| 0x0a50000b | 1        | 2.22%   |
| 0x0a201016 | 1        | 2.22%   |
| 0x0a201009 | 1        | 2.22%   |
| 0x0800820b | 1        | 2.22%   |
| 0x08001138 | 1        | 2.22%   |
| 0x08001129 | 1        | 2.22%   |
| 0x06003106 | 1        | 2.22%   |
| 0x06000852 | 1        | 2.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen 2       | 8        | 18.6%   |
| Zen+        | 5        | 11.63%  |
| Zen 3       | 4        | 9.3%    |
| Piledriver  | 4        | 9.3%    |
| KabyLake    | 4        | 9.3%    |
| Zen         | 3        | 6.98%   |
| SandyBridge | 3        | 6.98%   |
| Westmere    | 2        | 4.65%   |
| Skylake     | 2        | 4.65%   |
| Haswell     | 2        | 4.65%   |
| Steamroller | 1        | 2.33%   |
| Penryn      | 1        | 2.33%   |
| K10         | 1        | 2.33%   |
| IvyBridge   | 1        | 2.33%   |
| Core        | 1        | 2.33%   |
| CometLake   | 1        | 2.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 24       | 51.06%  |
| Nvidia | 17       | 36.17%  |
| Intel  | 6        | 12.77%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7        | 14.29%  |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4        | 8.16%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 4.08%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 2        | 4.08%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 4.08%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 4.08%   |
| AMD Cezanne                                                                 | 2        | 4.08%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 2.04%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 2.04%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 2.04%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 2.04%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 2.04%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 2.04%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 2.04%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 2.04%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 2.04%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 2.04%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 2.04%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                           | 1        | 2.04%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 2.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 2.04%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 2.04%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 2.04%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 2.04%   |
| AMD Vega 20 [Radeon VII]                                                    | 1        | 2.04%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 1        | 2.04%   |
| AMD Redwood XT [Radeon HD 5670/5690/5730]                                   | 1        | 2.04%   |
| AMD Pitcairn XT [Radeon HD 7870 GHz Edition]                                | 1        | 2.04%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 1        | 2.04%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 1        | 2.04%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 1        | 2.04%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 1        | 2.04%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                          | 1        | 2.04%   |
| AMD Cayman PRO [Radeon HD 6950]                                             | 1        | 2.04%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1        | 2.04%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x AMD      | 20       | 45.45%  |
| 1 x Nvidia   | 15       | 34.09%  |
| 1 x Intel    | 5        | 11.36%  |
| 2 x AMD      | 2        | 4.55%   |
| AMD + Nvidia | 2        | 4.55%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 33       | 73.33%  |
| Proprietary | 12       | 26.67%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 13       | 27.66%  |
| 7.01-8.0   | 12       | 25.53%  |
| 3.01-4.0   | 7        | 14.89%  |
| 1.01-2.0   | 7        | 14.89%  |
| 8.01-16.0  | 3        | 6.38%   |
| 0.51-1.0   | 3        | 6.38%   |
| 5.01-6.0   | 1        | 2.13%   |
| 0.01-0.5   | 1        | 2.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 10       | 16.39%  |
| Philips              | 7        | 11.48%  |
| Acer                 | 7        | 11.48%  |
| AOC                  | 6        | 9.84%   |
| Goldstar             | 5        | 8.2%    |
| BenQ                 | 5        | 8.2%    |
| Dell                 | 4        | 6.56%   |
| ASUSTek Computer     | 3        | 4.92%   |
| Ancor Communications | 2        | 3.28%   |
| ViewSonic            | 1        | 1.64%   |
| Vestel Elektronik    | 1        | 1.64%   |
| Packard Bell         | 1        | 1.64%   |
| KTC                  | 1        | 1.64%   |
| Jean                 | 1        | 1.64%   |
| Iiyama               | 1        | 1.64%   |
| Idek Iiyama          | 1        | 1.64%   |
| HVR                  | 1        | 1.64%   |
| Hitachi              | 1        | 1.64%   |
| Envision Peripherals | 1        | 1.64%   |
| CTV                  | 1        | 1.64%   |
| Belinea              | 1        | 1.64%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Desktops | Percent |
|--------------------------------------------------------------------------|----------|---------|
| AOC F22 AOC2200 1920x1080 476x268mm 21.5-inch                            | 2        | 3.08%   |
| Ancor Communications ASUS PB277 ACI27B5 2560x1440 597x336mm 27.0-inch    | 2        | 3.08%   |
| ViewSonic LCD Monitor VX2452 Series 3840x1080                            | 1        | 1.54%   |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                            | 1        | 1.54%   |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch        | 1        | 1.54%   |
| Samsung Electronics T24B301 SAM098E 1920x1080 520x290mm 23.4-inch        | 1        | 1.54%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 1        | 1.54%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch        | 1        | 1.54%   |
| Samsung Electronics S24A31x SAM7114 1920x1080 527x296mm 23.8-inch        | 1        | 1.54%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch        | 1        | 1.54%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1420x800mm 64.2-inch   | 1        | 1.54%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 950x540mm 43.0-inch    | 1        | 1.54%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch        | 1        | 1.54%   |
| Samsung Electronics C27FG7x SAM0E41 1920x1080 598x337mm 27.0-inch        | 1        | 1.54%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch        | 1        | 1.54%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 1        | 1.54%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch                 | 1        | 1.54%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch                  | 1        | 1.54%   |
| Philips PHL 245E1 PHLC20B 2560x1440 527x296mm 23.8-inch                  | 1        | 1.54%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 1        | 1.54%   |
| Philips PHL 220V8 PHLC218 1920x1080 477x268mm 21.5-inch                  | 1        | 1.54%   |
| Philips 247ELH PHLC085 1920x1080 521x293mm 23.5-inch                     | 1        | 1.54%   |
| Philips 226VL PHLC081 1920x1080 480x268mm 21.6-inch                      | 1        | 1.54%   |
| Packard Bell Viseo203DX PKB0378 1600x900 432x240mm 19.5-inch             | 1        | 1.54%   |
| KTC 24'TV KTC2400 1360x768 708x398mm 32.0-inch                           | 1        | 1.54%   |
| Jean JT198x6-7 JEN17C6 1280x1024 376x301mm 19.0-inch                     | 1        | 1.54%   |
| Iiyama PL3461WQ IVM7615 3440x1440 800x335mm 34.1-inch                    | 1        | 1.54%   |
| Idek Iiyama LCD Monitor PL2488H                                          | 1        | 1.54%   |
| HVR HTC-VIVE HVRAA01 2160x1200                                           | 1        | 1.54%   |
| Hitachi HDMI HEC0030 1920x1080 580x330mm 26.3-inch                       | 1        | 1.54%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                  | 1        | 1.54%   |
| Goldstar MP59G GSM5B35 1920x1080 480x270mm 21.7-inch                     | 1        | 1.54%   |
| Goldstar HDR WFHD GSM7715 2560x1080 798x334mm 34.1-inch                  | 1        | 1.54%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                   | 1        | 1.54%   |
| Goldstar E2251 GSM586D 1920x1080 477x268mm 21.5-inch                     | 1        | 1.54%   |
| Envision Peripherals LED P2478MDHL ENV2478 1920x1080 531x299mm 24.0-inch | 1        | 1.54%   |
| Dell U2415 DELA0B8 1920x1200 518x324mm 24.1-inch                         | 1        | 1.54%   |
| Dell S2817Q DEL40EE 3840x2160 620x340mm 27.8-inch                        | 1        | 1.54%   |
| Dell P2211H DEL4061 1920x1080 477x268mm 21.5-inch                        | 1        | 1.54%   |
| Dell AW2518HF DELA103 1920x1080 544x303mm 24.5-inch                      | 1        | 1.54%   |
| CTV LCD Monitor CTV0030 1920x1080 930x520mm 41.9-inch                    | 1        | 1.54%   |
| BenQ LCD Monitor RL2455                                                  | 1        | 1.54%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                        | 1        | 1.54%   |
| BenQ FP71V+ BNQ76A2 1280x1024 376x301mm 19.0-inch                        | 1        | 1.54%   |
| BenQ FP202W BNQ76C3 1680x1050 376x301mm 19.0-inch                        | 1        | 1.54%   |
| BenQ EX2780Q BNQ7F76 2560x1440 597x336mm 27.0-inch                       | 1        | 1.54%   |
| Belinea Belinea101536 MAX05EA 1024x768 304x228mm 15.0-inch               | 1        | 1.54%   |
| ASUSTek Computer VP249 AUS24AF 1920x1080 527x296mm 23.8-inch             | 1        | 1.54%   |
| ASUSTek Computer VG289 AUS28BA 3840x2160 621x341mm 27.9-inch             | 1        | 1.54%   |
| ASUSTek Computer ROG PG27U AUS27A4 3840x2160 598x336mm 27.0-inch         | 1        | 1.54%   |
| AOC U3277WB AOC3277 3840x2160 698x393mm 31.5-inch                        | 1        | 1.54%   |
| AOC 2475W AOC2475 1920x1080 521x293mm 23.5-inch                          | 1        | 1.54%   |
| AOC 2370 AOC2370 1920x1080 509x286mm 23.0-inch                           | 1        | 1.54%   |
| AOC 2367M AOC2367 1920x1080 510x290mm 23.1-inch                          | 1        | 1.54%   |
| Ancor Communications LCD Monitor ASUS PB277 2560x1440                    | 1        | 1.54%   |
| Acer XB241H ACR050E 1920x1080 531x299mm 24.0-inch                        | 1        | 1.54%   |
| Acer S240HL ACR0289 1920x1080 531x299mm 24.0-inch                        | 1        | 1.54%   |
| Acer LCD Monitor P223W 3600x1080                                         | 1        | 1.54%   |
| Acer K242HQL ACR042E 1920x1080 521x293mm 23.5-inch                       | 1        | 1.54%   |
| Acer GN246HL ACR02FA 1920x1080 531x299mm 24.0-inch                       | 1        | 1.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 30       | 50.85%  |
| 3840x2160 (4K)     | 11       | 18.64%  |
| 2560x1440 (QHD)    | 5        | 8.47%   |
| 1280x1024 (SXGA)   | 2        | 3.39%   |
| Unknown            | 2        | 3.39%   |
| 3840x1080          | 1        | 1.69%   |
| 3600x1080          | 1        | 1.69%   |
| 3440x1440          | 1        | 1.69%   |
| 2560x1080          | 1        | 1.69%   |
| 2160x1200          | 1        | 1.69%   |
| 1920x1200 (WUXGA)  | 1        | 1.69%   |
| 1680x1050 (WSXGA+) | 1        | 1.69%   |
| 1600x900 (HD+)     | 1        | 1.69%   |
| 1024x768 (XGA)     | 1        | 1.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 11       | 18.97%  |
| 27      | 10       | 17.24%  |
| 24      | 10       | 17.24%  |
| 21      | 7        | 12.07%  |
| 84      | 4        | 6.9%    |
| Unknown | 4        | 6.9%    |
| 31      | 3        | 5.17%   |
| 34      | 2        | 3.45%   |
| 32      | 2        | 3.45%   |
| 19      | 2        | 3.45%   |
| 52      | 1        | 1.72%   |
| 20      | 1        | 1.72%   |
| 15      | 1        | 1.72%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 28       | 49.12%  |
| 401-500     | 8        | 14.04%  |
| 601-700     | 5        | 8.77%   |
| 701-800     | 4        | 7.02%   |
| 1501-2000   | 4        | 7.02%   |
| Unknown     | 4        | 7.02%   |
| 351-400     | 2        | 3.51%   |
| 301-350     | 1        | 1.75%   |
| 1001-1500   | 1        | 1.75%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 39       | 78%     |
| 16/10   | 3        | 6%      |
| Unknown | 3        | 6%      |
| 5/4     | 2        | 4%      |
| 21/9    | 2        | 4%      |
| 4/3     | 1        | 2%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 25       | 43.1%   |
| 301-350        | 10       | 17.24%  |
| 351-500        | 7        | 12.07%  |
| More than 1000 | 5        | 8.62%   |
| 151-200        | 4        | 6.9%    |
| Unknown        | 4        | 6.9%    |
| 251-300        | 2        | 3.45%   |
| 101-110        | 1        | 1.72%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 31       | 56.36%  |
| 101-120 | 12       | 21.82%  |
| 121-160 | 5        | 9.09%   |
| Unknown | 4        | 7.27%   |
| 161-240 | 2        | 3.64%   |
| 1-50    | 1        | 1.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 30       | 68.18%  |
| 2     | 10       | 22.73%  |
| 3     | 3        | 6.82%   |
| 4     | 1        | 2.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 28       | 48.28%  |
| Intel                                 | 17       | 29.31%  |
| Qualcomm Atheros                      | 2        | 3.45%   |
| D-Link System                         | 2        | 3.45%   |
| Xiaomi                                | 1        | 1.72%   |
| TP-Link                               | 1        | 1.72%   |
| Ralink Technology                     | 1        | 1.72%   |
| Qualcomm Atheros Communications       | 1        | 1.72%   |
| Microsoft                             | 1        | 1.72%   |
| Google                                | 1        | 1.72%   |
| DisplayLink                           | 1        | 1.72%   |
| Aquantia                              | 1        | 1.72%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 1.72%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                               | Desktops | Percent |
|-----------------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                                   | 25       | 33.33%  |
| Intel I211 Gigabit Network Connection                                                               | 6        | 8%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                               | 2        | 2.67%   |
| Intel Ethernet Connection (2) I219-V                                                                | 2        | 2.67%   |
| Intel 82574L Gigabit Network Connection                                                             | 2        | 2.67%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                                      | 1        | 1.33%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                         | 1        | 1.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                                     | 1        | 1.33%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                            | 1        | 1.33%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                            | 1        | 1.33%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                                     | 1        | 1.33%   |
| Realtek RTL8188EE Wireless Network Adapter                                                          | 1        | 1.33%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                             | 1        | 1.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                            | 1        | 1.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                               | 1        | 1.33%   |
| Realtek 802.11ac NIC                                                                                | 1        | 1.33%   |
| Ralink MT7601U Wireless Adapter                                                                     | 1        | 1.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                          | 1        | 1.33%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                                           | 1        | 1.33%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                                           | 1        | 1.33%   |
| Qualcomm Atheros AR9271 802.11n                                                                     | 1        | 1.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                                    | 1        | 1.33%   |
| Microsoft XBOX ACC                                                                                  | 1        | 1.33%   |
| Intel Wireless-AC 9260                                                                              | 1        | 1.33%   |
| Intel Wireless 8265 / 8275                                                                          | 1        | 1.33%   |
| Intel Wireless 7265                                                                                 | 1        | 1.33%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                              | 1        | 1.33%   |
| Intel Wi-Fi 6 AX200                                                                                 | 1        | 1.33%   |
| Intel I210 Gigabit Network Connection                                                               | 1        | 1.33%   |
| Intel Ethernet Controller I225-V                                                                    | 1        | 1.33%   |
| Intel Ethernet Connection (7) I219-V                                                                | 1        | 1.33%   |
| Intel Ethernet Connection (11) I219-LM                                                              | 1        | 1.33%   |
| Intel Comet Lake PCH CNVi WiFi                                                                      | 1        | 1.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                                                     | 1        | 1.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                               | 1        | 1.33%   |
| Intel 82567LF-2 Gigabit Network Connection                                                          | 1        | 1.33%   |
| Intel 82562V-2 10/100 Network Connection                                                            | 1        | 1.33%   |
| Google Nexus/Pixel Device (tether+ debug)                                                           | 1        | 1.33%   |
| DisplayLink Kensington Dock (Composite Device)                                                      | 1        | 1.33%   |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A2) [Atheros AR9170+AR9104]         | 1        | 1.33%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                                                     | 1        | 1.33%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]                                   | 1        | 1.33%   |
| 802.11g Adapter [Linksys WUSB54GC v3] WUSB100 v2 RangePlus Wireless Network Adapter [Ralink RT3070] | 1        | 1.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 7        | 33.33%  |
| Realtek Semiconductor                 | 6        | 28.57%  |
| Qualcomm Atheros                      | 2        | 9.52%   |
| TP-Link                               | 1        | 4.76%   |
| Ralink Technology                     | 1        | 4.76%   |
| Qualcomm Atheros Communications       | 1        | 4.76%   |
| Microsoft                             | 1        | 4.76%   |
| D-Link System                         | 1        | 4.76%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 4.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                               | Desktops | Percent |
|-----------------------------------------------------------------------------------------------------|----------|---------|
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                         | 1        | 4.55%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                                     | 1        | 4.55%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                            | 1        | 4.55%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                            | 1        | 4.55%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                                     | 1        | 4.55%   |
| Realtek RTL8188EE Wireless Network Adapter                                                          | 1        | 4.55%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                             | 1        | 4.55%   |
| Realtek 802.11ac NIC                                                                                | 1        | 4.55%   |
| Ralink MT7601U Wireless Adapter                                                                     | 1        | 4.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                          | 1        | 4.55%   |
| Qualcomm Atheros AR9271 802.11n                                                                     | 1        | 4.55%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                                    | 1        | 4.55%   |
| Microsoft XBOX ACC                                                                                  | 1        | 4.55%   |
| Intel Wireless-AC 9260                                                                              | 1        | 4.55%   |
| Intel Wireless 8265 / 8275                                                                          | 1        | 4.55%   |
| Intel Wireless 7265                                                                                 | 1        | 4.55%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                              | 1        | 4.55%   |
| Intel Wi-Fi 6 AX200                                                                                 | 1        | 4.55%   |
| Intel Comet Lake PCH CNVi WiFi                                                                      | 1        | 4.55%   |
| Intel Cannon Lake PCH CNVi WiFi                                                                     | 1        | 4.55%   |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A2) [Atheros AR9170+AR9104]         | 1        | 4.55%   |
| 802.11g Adapter [Linksys WUSB54GC v3] WUSB100 v2 RangePlus Wireless Network Adapter [Ralink RT3070] | 1        | 4.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 27       | 56.25%  |
| Intel                 | 15       | 31.25%  |
| Qualcomm Atheros      | 2        | 4.17%   |
| Xiaomi                | 1        | 2.08%   |
| DisplayLink           | 1        | 2.08%   |
| D-Link System         | 1        | 2.08%   |
| Aquantia              | 1        | 2.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25       | 48.08%  |
| Intel I211 Gigabit Network Connection                             | 6        | 11.54%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 3.85%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 3.85%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 3.85%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.92%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 1.92%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 1.92%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 1.92%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.92%   |
| Intel I210 Gigabit Network Connection                             | 1        | 1.92%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.92%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.92%   |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 1.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 1.92%   |
| Intel 82567LF-2 Gigabit Network Connection                        | 1        | 1.92%   |
| Intel 82562V-2 10/100 Network Connection                          | 1        | 1.92%   |
| DisplayLink Kensington Dock (Composite Device)                    | 1        | 1.92%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 1.92%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.92%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 43       | 66.15%  |
| WiFi     | 21       | 32.31%  |
| Modem    | 1        | 1.54%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 33       | 78.57%  |
| WiFi     | 9        | 21.43%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 24       | 55.81%  |
| 2     | 17       | 39.53%  |
| 4     | 2        | 4.65%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 39       | 90.7%   |
| Yes  | 4        | 9.3%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 7        | 43.75%  |
| IMC Networks                    | 3        | 18.75%  |
| Cambridge Silicon Radio         | 2        | 12.5%   |
| Qualcomm Atheros Communications | 1        | 6.25%   |
| HTC (High Tech Computer)        | 1        | 6.25%   |
| Broadcom                        | 1        | 6.25%   |
| ASUSTek Computer                | 1        | 6.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                                   | 2        | 12.5%   |
| IMC Networks Bluetooth Radio                                         | 2        | 12.5%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 2        | 12.5%   |
| Qualcomm Atheros  Bluetooth Device                                   | 1        | 6.25%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 1        | 6.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 1        | 6.25%   |
| Intel AX210 Bluetooth                                                | 1        | 6.25%   |
| Intel AX201 Bluetooth                                                | 1        | 6.25%   |
| Intel AX200 Bluetooth                                                | 1        | 6.25%   |
| IMC Networks Bluetooth Device                                        | 1        | 6.25%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 6.25%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 1        | 6.25%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 1        | 6.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD                                             | 31       | 36.47%  |
| Nvidia                                          | 17       | 20%     |
| Intel                                           | 16       | 18.82%  |
| C-Media Electronics                             | 4        | 4.71%   |
| Creative Labs                                   | 3        | 3.53%   |
| Logitech                                        | 2        | 2.35%   |
| Creative Technology                             | 2        | 2.35%   |
| TC Electronic                                   | 1        | 1.18%   |
| SteelSeries ApS                                 | 1        | 1.18%   |
| Realtek Semiconductor                           | 1        | 1.18%   |
| Razer USA                                       | 1        | 1.18%   |
| Native Instruments                              | 1        | 1.18%   |
| Licensed by Sony Computer Entertainment America | 1        | 1.18%   |
| Generalplus Technology                          | 1        | 1.18%   |
| Focusrite-Novation                              | 1        | 1.18%   |
| Corsair                                         | 1        | 1.18%   |
| AudioQuest                                      | 1        | 1.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 10       | 9.52%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 7        | 6.67%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 7        | 6.67%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5        | 4.76%   |
| AMD Navi 10 HDMI Audio                                                     | 5        | 4.76%   |
| Nvidia GP104 High Definition Audio Controller                              | 3        | 2.86%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3        | 2.86%   |
| Intel 200 Series PCH HD Audio                                              | 3        | 2.86%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3        | 2.86%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 1.9%    |
| Nvidia TU104 HD Audio Controller                                           | 2        | 1.9%    |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 1.9%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 1.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 1.9%    |
| Creative Labs CA0110 [Sound Blaster X-Fi Xtreme Audio]                     | 2        | 1.9%    |
| C-Media Electronics SADES Luna                                             | 2        | 1.9%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 2        | 1.9%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2        | 1.9%    |
| AMD Family 17h/19h HD Audio Controller                                     | 2        | 1.9%    |
| TC Electronic VoiceLive Play                                               | 1        | 0.95%   |
| SteelSeries ApS Arctis Pro Wireless                                        | 1        | 0.95%   |
| Realtek Semiconductor Speedlink Volity Microphone                          | 1        | 0.95%   |
| Razer USA RZ19-0229 Gaming Microphone                                      | 1        | 0.95%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 0.95%   |
| Nvidia High Definition Audio Controller                                    | 1        | 0.95%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 0.95%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 0.95%   |
| Nvidia GM200 High Definition Audio                                         | 1        | 0.95%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 0.95%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1        | 0.95%   |
| Nvidia Audio device                                                        | 1        | 0.95%   |
| Native Instruments Komplete Audio 6                                        | 1        | 0.95%   |
| Logitech G933 Wireless Headset Dongle                                      | 1        | 0.95%   |
| Logitech G432 Gaming Headset                                               | 1        | 0.95%   |
| Licensed by Sony Computer Entertainment America Rocksmith Guitar Adapter   | 1        | 0.95%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1        | 0.95%   |
| Intel Comet Lake PCH cAVS                                                  | 1        | 0.95%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 0.95%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 0.95%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1        | 0.95%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 0.95%   |
| Generalplus Technology Usb Audio Device                                    | 1        | 0.95%   |
| Focusrite-Novation Scarlett Solo (3rd Gen.)                                | 1        | 0.95%   |
| Creative Technology Sound Blaster Tactic(3D) Alpha                         | 1        | 0.95%   |
| Creative Technology Sound Blaster Premium HD [SBX]                         | 1        | 0.95%   |
| Creative Labs EMU20k2 [Sound Blaster X-Fi Titanium Series]                 | 1        | 0.95%   |
| Corsair HS45 Surround USB Sound Adapter                                    | 1        | 0.95%   |
| C-Media Electronics TONOR TC30 Audio Device                                | 1        | 0.95%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1        | 0.95%   |
| AudioQuest DragonFly                                                       | 1        | 0.95%   |
| AMD Vega 20 HDMI Audio [Radeon VII]                                        | 1        | 0.95%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 1        | 0.95%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1        | 0.95%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1        | 0.95%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 1        | 0.95%   |
| AMD Hawaii HDMI Audio [Radeon R9 290/290X / 390/390X]                      | 1        | 0.95%   |
| AMD FCH Azalia Controller                                                  | 1        | 0.95%   |
| AMD Cayman/Antilles HDMI Audio [Radeon HD 6930/6950/6970/6990]             | 1        | 0.95%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 11       | 25%     |
| G.Skill             | 9        | 20.45%  |
| Kingston            | 7        | 15.91%  |
| Crucial             | 4        | 9.09%   |
| Unknown             | 3        | 6.82%   |
| SK Hynix            | 3        | 6.82%   |
| Samsung Electronics | 2        | 4.55%   |
| Transcend           | 1        | 2.27%   |
| Patriot             | 1        | 2.27%   |
| Micron Technology   | 1        | 2.27%   |
| AMD                 | 1        | 2.27%   |
| A-DATA Technology   | 1        | 2.27%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3533MT/s  | 2        | 4.44%   |
| G.Skill RAM F3-10666CL9-4GBNT 4096MB DIMM DDR3 1400MT/s  | 2        | 4.44%   |
| Crucial RAM BLS16G4D30AESB.M16FE 16GB DIMM DDR4 3200MT/s | 2        | 4.44%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 2        | 4.44%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 1        | 2.22%   |
| Unknown RAM Module 2048MB DIMM SDRAM                     | 1        | 2.22%   |
| Unknown RAM Module 2048MB DIMM 1328MT/s                  | 1        | 2.22%   |
| Transcend RAM JM2666HLB-16G 16GB DIMM DDR4 2667MT/s      | 1        | 2.22%   |
| SK Hynix RAM HMA82GU7CJR8N-VK 16GB DIMM DDR4 2667MT/s    | 1        | 2.22%   |
| SK Hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s  | 1        | 2.22%   |
| SK Hynix RAM HMA41GU6AFR8N-TF 8GB DIMM DDR4 2465MT/s     | 1        | 2.22%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s      | 1        | 2.22%   |
| Samsung RAM M3 78T2863RZS-CF7 1GB DIMM DDR2 800MT/s      | 1        | 2.22%   |
| Patriot RAM PSD48G240082 8GB DIMM DDR4 2400MT/s          | 1        | 2.22%   |
| Micron RAM 16ATF2G64HZ-2G6J1 16GB SODIMM DDR4 2667MT/s   | 1        | 2.22%   |
| Kingston RAM XJ69DF-MIE 8GB DIMM DDR4 2933MT/s           | 1        | 2.22%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s      | 1        | 2.22%   |
| Kingston RAM 99U5584-014.A00LF 4096MB DIMM DDR3 1600MT/s | 1        | 2.22%   |
| Kingston RAM 99U5474-026.A00LF 4GB DIMM DDR3 1333MT/s    | 1        | 2.22%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 2.22%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 2.22%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s   | 1        | 2.22%   |
| G.Skill RAM F4-3200C16-8GSXWB 8GB DIMM DDR4 4133MT/s     | 1        | 2.22%   |
| G.Skill RAM F4-3200C16-8GIS 8192MB DIMM DDR4 3200MT/s    | 1        | 2.22%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s      | 1        | 2.22%   |
| G.Skill RAM F4-2400C15-4GRR 4096MB DIMM DDR4 2133MT/s    | 1        | 2.22%   |
| G.Skill RAM F3-2400C10-4GTX 4GB DIMM DDR3 2400MT/s       | 1        | 2.22%   |
| G.Skill RAM F3-1866C10-8G 8192MB DIMM DDR3 1600MT/s      | 1        | 2.22%   |
| Crucial RAM CT102464BD160B.C16 8GB DIMM DDR3 1600MT/s    | 1        | 2.22%   |
| Crucial RAM BL16G32C16U4BL.M16FE 16GB DIMM DDR4 3200MT/s | 1        | 2.22%   |
| Corsair RAM Module 4096MB DIMM DDR3 2481MT/s             | 1        | 2.22%   |
| Corsair RAM CMZ8GX3M2A160 4096MB DIMM DDR3 1333MT/s      | 1        | 2.22%   |
| Corsair RAM CMZ4GX3M1A160 4GB DIMM DDR3 1333MT/s         | 1        | 2.22%   |
| Corsair RAM CMY16GX3M2A1600C9 8192MB DIMM DDR3 2133MT/s  | 1        | 2.22%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3266MT/s    | 1        | 2.22%   |
| Corsair RAM CML8GX3M1A1600C10 8192MB DIMM DDR3 1600MT/s  | 1        | 2.22%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s    | 1        | 2.22%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s    | 1        | 2.22%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s    | 1        | 2.22%   |
| AMD RAM R534G1601U1S 4GB DIMM DDR3 1600MT/s              | 1        | 2.22%   |
| A-DATA RAM Module 32GB DIMM DDR4 3200MT/s                | 1        | 2.22%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 22       | 57.89%  |
| DDR3    | 12       | 31.58%  |
| Unknown | 2        | 5.26%   |
| SDRAM   | 1        | 2.63%   |
| DDR2    | 1        | 2.63%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 37       | 97.37%  |
| SODIMM | 1        | 2.63%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 16       | 40%     |
| 4096  | 13       | 32.5%   |
| 16384 | 7        | 17.5%   |
| 2048  | 2        | 5%      |
| 32768 | 1        | 2.5%    |
| 1024  | 1        | 2.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 7        | 16.28%  |
| 1600    | 7        | 16.28%  |
| 3600    | 4        | 9.3%    |
| 1333    | 4        | 9.3%    |
| 2667    | 3        | 6.98%   |
| 3533    | 2        | 4.65%   |
| 2933    | 2        | 4.65%   |
| 2400    | 2        | 4.65%   |
| 2133    | 2        | 4.65%   |
| 1400    | 2        | 4.65%   |
| 4133    | 1        | 2.33%   |
| 3466    | 1        | 2.33%   |
| 3266    | 1        | 2.33%   |
| 2481    | 1        | 2.33%   |
| 2465    | 1        | 2.33%   |
| 1328    | 1        | 2.33%   |
| 800     | 1        | 2.33%   |
| Unknown | 1        | 2.33%   |

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
| Logitech                      | 3        | 33.33%  |
| Sunplus Innovation Technology | 1        | 11.11%  |
| Microsoft                     | 1        | 11.11%  |
| KYE Systems (Mouse Systems)   | 1        | 11.11%  |
| GEMBIRD                       | 1        | 11.11%  |
| Creative Technology           | 1        | 11.11%  |
| ARC International             | 1        | 11.11%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Sunplus Aukey-PC-LM1E Camera                   | 1        | 11.11%  |
| Microsoft LifeCam Cinema                       | 1        | 11.11%  |
| Logitech Webcam C930e                          | 1        | 11.11%  |
| Logitech Webcam C310                           | 1        | 11.11%  |
| Logitech Webcam C270                           | 1        | 11.11%  |
| KYE Systems (Mouse Systems) Genius FaceCam 320 | 1        | 11.11%  |
| GEMBIRD USB2.0 PC CAMERA                       | 1        | 11.11%  |
| Creative Live! Cam Sync HD [VF0770]            | 1        | 11.11%  |
| ARC International Camera                       | 1        | 11.11%  |

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
| 0     | 39       | 90.7%   |
| 1     | 4        | 9.3%    |

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

