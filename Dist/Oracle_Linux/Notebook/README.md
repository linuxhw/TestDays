Oracle Linux - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for Oracle Linux.

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

Total: 59

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Panasonic | CF-53AAG54FM                | [cf7f652846](https://linux-hardware.org/?probe=cf7f652846) | Dec 21, 2022 |
| Lenovo    | ThinkPad T470 20HES0E71M    | [85fc801717](https://linux-hardware.org/?probe=85fc801717) | Dec 05, 2022 |
| Lenovo    | ThinkPad P70 20ESS04S00     | [01b85c4c2a](https://linux-hardware.org/?probe=01b85c4c2a) | Nov 10, 2022 |
| Lenovo    | ThinkPad T470 20HES21434    | [39ff1846e3](https://linux-hardware.org/?probe=39ff1846e3) | Oct 23, 2022 |
| Dynabook  | PORTEGE X40-G               | [fc68a9cdbf](https://linux-hardware.org/?probe=fc68a9cdbf) | Oct 03, 2022 |
| HP        | EliteBook 840 G5            | [2709daf415](https://linux-hardware.org/?probe=2709daf415) | Sep 13, 2022 |
| Lenovo    | Legion 5 15IMH05 82AU       | [bd4737dfcf](https://linux-hardware.org/?probe=bd4737dfcf) | Aug 18, 2022 |
| Dell      | Inspiron 5502               | [28dcf01e88](https://linux-hardware.org/?probe=28dcf01e88) | Aug 03, 2022 |
| Lenovo    | Legion 5 15IMH05 82AU       | [3dddb3aac3](https://linux-hardware.org/?probe=3dddb3aac3) | Jul 20, 2022 |
| Lenovo    | ThinkPad P70 20ESS04S00     | [fc29967bed](https://linux-hardware.org/?probe=fc29967bed) | Jun 17, 2022 |
| HP        | Compaq 6730b                | [dd94c9145b](https://linux-hardware.org/?probe=dd94c9145b) | Jun 11, 2022 |
| Lenovo    | ThinkPad T410 2518A37       | [04e81b8b3f](https://linux-hardware.org/?probe=04e81b8b3f) | Jun 04, 2022 |
| Lenovo    | ThinkPad T430s 2355C33      | [33de2bbd12](https://linux-hardware.org/?probe=33de2bbd12) | May 31, 2022 |
| Lenovo    | ThinkPad T430s 2355C33      | [4eab57bebf](https://linux-hardware.org/?probe=4eab57bebf) | May 30, 2022 |
| Dell      | Precision M4600             | [0ac2adfe5a](https://linux-hardware.org/?probe=0ac2adfe5a) | Apr 21, 2022 |
| Dell      | Precision M4800             | [fb13b19803](https://linux-hardware.org/?probe=fb13b19803) | Apr 21, 2022 |
| Lenovo    | ThinkPad P50s 20FL000MUS    | [99fbb4446c](https://linux-hardware.org/?probe=99fbb4446c) | Apr 16, 2022 |
| Lenovo    | ThinkPad X1 Extreme 2nd ... | [b708e920f3](https://linux-hardware.org/?probe=b708e920f3) | Mar 21, 2022 |
| Lenovo    | ThinkPad T450 20BUS14900    | [bd60aae97a](https://linux-hardware.org/?probe=bd60aae97a) | Mar 11, 2022 |
| Lenovo    | ThinkPad T480 20L5A07TAU    | [755854f7d4](https://linux-hardware.org/?probe=755854f7d4) | Mar 11, 2022 |
| Lenovo    | ThinkPad X280 20KES4H34G    | [2b8a4f4664](https://linux-hardware.org/?probe=2b8a4f4664) | Mar 10, 2022 |
| Dell      | Latitude 7420               | [af5f1055fe](https://linux-hardware.org/?probe=af5f1055fe) | Mar 10, 2022 |
| HP        | ProBook 445 G6              | [88d8b32328](https://linux-hardware.org/?probe=88d8b32328) | Jan 26, 2022 |
| Lenovo    | ThinkPad T450 20BUS14900    | [44c8e11f02](https://linux-hardware.org/?probe=44c8e11f02) | Dec 22, 2021 |
| Lenovo    | IdeaPad 300-15ISK 80RS      | [1c9ca21f4e](https://linux-hardware.org/?probe=1c9ca21f4e) | Dec 10, 2021 |
| Dell      | Latitude 7410               | [3efa87284e](https://linux-hardware.org/?probe=3efa87284e) | Nov 18, 2021 |
| Dell      | Latitude E6420              | [b809392380](https://linux-hardware.org/?probe=b809392380) | Oct 08, 2021 |
| Dell      | Latitude 7410               | [8f1a1a4798](https://linux-hardware.org/?probe=8f1a1a4798) | Sep 06, 2021 |
| Dell      | Latitude 7410               | [b03a0e0152](https://linux-hardware.org/?probe=b03a0e0152) | Sep 06, 2021 |
| Lenovo    | Legion 5 15IMH05 82AU       | [7b393c5790](https://linux-hardware.org/?probe=7b393c5790) | Aug 21, 2021 |
| Lenovo    | Legion 5 15IMH05 82AU       | [394c99adc8](https://linux-hardware.org/?probe=394c99adc8) | Aug 19, 2021 |
| Dell      | Inspiron 3542               | [0909599e9c](https://linux-hardware.org/?probe=0909599e9c) | Aug 11, 2021 |
| Lenovo    | Legion 5 15IMH05 82AU       | [ba7afba1a6](https://linux-hardware.org/?probe=ba7afba1a6) | Jul 08, 2021 |
| Lenovo    | ThinkPad L490 20Q5CTO1WW    | [0225c17d79](https://linux-hardware.org/?probe=0225c17d79) | Jul 02, 2021 |
| Lenovo    | Legion 5 15IMH05 82AU       | [505b82b2de](https://linux-hardware.org/?probe=505b82b2de) | Jun 06, 2021 |
| Lenovo    | Legion 5 15IMH05 82AU       | [75b2ef5126](https://linux-hardware.org/?probe=75b2ef5126) | May 13, 2021 |
| Lenovo    | Legion 5 15IMH05 82AU       | [734a4fbc56](https://linux-hardware.org/?probe=734a4fbc56) | May 09, 2021 |
| ASUSTek   | UX305FA                     | [0bf50fba2d](https://linux-hardware.org/?probe=0bf50fba2d) | Mar 15, 2021 |
| Lenovo    | IdeaPad Slim 1-14AST-05 ... | [ff355a9bb1](https://linux-hardware.org/?probe=ff355a9bb1) | Mar 11, 2021 |
| Lenovo    | IdeaPad Slim 1-14AST-05 ... | [9f67379954](https://linux-hardware.org/?probe=9f67379954) | Mar 04, 2021 |
| Lenovo    | ThinkPad L490 20Q5CTO1WW    | [db0f24aee5](https://linux-hardware.org/?probe=db0f24aee5) | Mar 01, 2021 |
| Dell      | Latitude 7410               | [5b725b01aa](https://linux-hardware.org/?probe=5b725b01aa) | Feb 26, 2021 |
| Lenovo    | Legion 5 15IMH05 82AU       | [835e8cad03](https://linux-hardware.org/?probe=835e8cad03) | Feb 25, 2021 |
| Dell      | Latitude 7410               | [430ac9fa0c](https://linux-hardware.org/?probe=430ac9fa0c) | Feb 24, 2021 |
| Lenovo    | ThinkPad T490 20N3S77600    | [26e61c39f2](https://linux-hardware.org/?probe=26e61c39f2) | Feb 24, 2021 |
| Dell      | Latitude 7410               | [7aeb2cc674](https://linux-hardware.org/?probe=7aeb2cc674) | Feb 22, 2021 |
| Lenovo    | IdeaPad Slim 1-14AST-05 ... | [8af2c8d83c](https://linux-hardware.org/?probe=8af2c8d83c) | Feb 05, 2021 |
| Lenovo    | IdeaPad Slim 1-14AST-05 ... | [7ea3c87bfe](https://linux-hardware.org/?probe=7ea3c87bfe) | Jan 06, 2021 |
| Standard  | BW Series                   | [1f6cf82ba8](https://linux-hardware.org/?probe=1f6cf82ba8) | Jun 13, 2020 |
| HP        | Notebook                    | [e3c242a846](https://linux-hardware.org/?probe=e3c242a846) | May 24, 2020 |
| Lenovo    | ThinkPad L490 20Q5CTO1WW    | [d8b2c132c1](https://linux-hardware.org/?probe=d8b2c132c1) | Apr 09, 2020 |
| HP        | ZBook 15                    | [4723616d8c](https://linux-hardware.org/?probe=4723616d8c) | Apr 09, 2020 |
| Lenovo    | ThinkPad L490 20Q5CTO1WW    | [1acbabb197](https://linux-hardware.org/?probe=1acbabb197) | Apr 06, 2020 |
| Lenovo    | ThinkPad T480 20L6S56Y2X    | [5343997520](https://linux-hardware.org/?probe=5343997520) | Feb 23, 2020 |
| ASUSTek   | X510UR                      | [914b9fbe64](https://linux-hardware.org/?probe=914b9fbe64) | Feb 04, 2020 |
| ASUSTek   | X510UR                      | [014d5ef0c8](https://linux-hardware.org/?probe=014d5ef0c8) | Jan 28, 2020 |
| ASUSTek   | X510UR                      | [9d05b420d4](https://linux-hardware.org/?probe=9d05b420d4) | Jan 28, 2020 |
| Lenovo    | ThinkPad L540 20AVCTO1WW    | [8c1dba9d6e](https://linux-hardware.org/?probe=8c1dba9d6e) | Sep 10, 2019 |
| Lenovo    | ThinkPad T480 20L6S56Y2X    | [f012a475eb](https://linux-hardware.org/?probe=f012a475eb) | Apr 11, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Oracle Linux 8.5 | 11        | 26.19%  |
| Oracle Linux 8.3 | 6         | 14.29%  |
| Oracle Linux 8.4 | 5         | 11.9%   |
| Oracle Linux 7.9 | 4         | 9.52%   |
| Oracle Linux 9.0 | 3         | 7.14%   |
| Oracle Linux 8.1 | 3         | 7.14%   |
| Oracle Linux 8.6 | 2         | 4.76%   |
| Oracle Linux 7.8 | 2         | 4.76%   |
| Oracle Linux 7.7 | 2         | 4.76%   |
| Oracle Linux 9.1 | 1         | 2.38%   |
| Oracle Linux 8.7 | 1         | 2.38%   |
| Oracle Linux 8.2 | 1         | 2.38%   |
| Oracle Linux 7.6 | 1         | 2.38%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Oracle Linux | 35        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Notebooks | Percent |
|------------------------------------|-----------|---------|
| 5.4.17-2036.103.3.1.el8uek.x86_64  | 3         | 6.38%   |
| 4.18.0-348.12.2.el8_5.x86_64       | 3         | 6.38%   |
| 5.4.17-2136.304.4.3.el8uek.x86_64  | 2         | 4.26%   |
| 5.4.17-2102.202.5.el8uek.x86_64    | 2         | 4.26%   |
| 5.15.0-2.52.3.el9uek.x86_64        | 2         | 4.26%   |
| 4.18.0-147.3.1.el8_1.x86_64        | 2         | 4.26%   |
| 5.4.17-2136.312.3.4.el7uek.x86_64  | 1         | 2.13%   |
| 5.4.17-2136.310.7.el8uek.x86_64    | 1         | 2.13%   |
| 5.4.17-2136.309.4.el8uek.x86_64    | 1         | 2.13%   |
| 5.4.17-2136.308.9.el7uek.x86_64    | 1         | 2.13%   |
| 5.4.17-2136.306.1.3.el8uek.x86_64  | 1         | 2.13%   |
| 5.4.17-2136.305.5.4.el8uek.x86_64  | 1         | 2.13%   |
| 5.4.17-2136.305.5.3.el8uek.x86_64  | 1         | 2.13%   |
| 5.4.17-2136.305.5.2.el8uek.x86_64  | 1         | 2.13%   |
| 5.4.17-2136.301.1.4.el8uek.x86_64  | 1         | 2.13%   |
| 5.4.17-2136.300.7.el8uek.x86_64    | 1         | 2.13%   |
| 5.4.17-2102.205.7.3.el8uek.x86_64  | 1         | 2.13%   |
| 5.4.17-2102.204.4.4.el8uek.x86_64  | 1         | 2.13%   |
| 5.4.17-2102.204.4.2.el8uek.x86_64  | 1         | 2.13%   |
| 5.4.17-2102.201.3.el8uek.x86_64    | 1         | 2.13%   |
| 5.4.17-2102.200.13.el8uek.x86_64   | 1         | 2.13%   |
| 5.4.17-2036.104.4.el8uek.x86_64    | 1         | 2.13%   |
| 5.4.17-2011.0.7.el8uek.x86_64      | 1         | 2.13%   |
| 5.15.2-1.el8.elrepo.x86_64         | 1         | 2.13%   |
| 5.15.0-100.76.15.el9uek.x86_64     | 1         | 2.13%   |
| 5.15.0-0.30.20.1.el9uek.x86_64     | 1         | 2.13%   |
| 5.14.1-1.el8.elrepo.x86_64         | 1         | 2.13%   |
| 5.11.1-1.el8.elrepo.x86_64         | 1         | 2.13%   |
| 4.18.0-425.3.1.el8.x86_64          | 1         | 2.13%   |
| 4.18.0-240.15.1.el8_3.x86_64       | 1         | 2.13%   |
| 4.18.0-240.10.1.el8_3.x86_64       | 1         | 2.13%   |
| 4.18.0-193.1.2.el8_2.x86_64        | 1         | 2.13%   |
| 4.14.35-2047.510.4.1.el7uek.x86_64 | 1         | 2.13%   |
| 4.14.35-2025.401.4.el7uek.x86_64   | 1         | 2.13%   |
| 4.14.35-1902.4.8.el7uek.x86_64     | 1         | 2.13%   |
| 4.14.35-1902.300.11.el7uek.x86_64  | 1         | 2.13%   |
| 4.14.35-1818.3.3.el7uek.x86_64     | 1         | 2.13%   |
| 4.1.12-124.63.2.1.el7uek.x86_64    | 1         | 2.13%   |
| 3.10.0-1127.10.1.el7.x86_64        | 1         | 2.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.17  | 15        | 40.54%  |
| 4.18.0  | 8         | 21.62%  |
| 4.14.35 | 5         | 13.51%  |
| 5.15.0  | 4         | 10.81%  |
| 5.15.2  | 1         | 2.7%    |
| 5.14.1  | 1         | 2.7%    |
| 5.11.1  | 1         | 2.7%    |
| 4.1.12  | 1         | 2.7%    |
| 3.10.0  | 1         | 2.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 15        | 40.54%  |
| 4.18    | 8         | 21.62%  |
| 5.15    | 5         | 13.51%  |
| 4.14    | 5         | 13.51%  |
| 5.14    | 1         | 2.7%    |
| 5.11    | 1         | 2.7%    |
| 4.1     | 1         | 2.7%    |
| 3.10    | 1         | 2.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 35        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 28        | 71.79%  |
| Unknown       | 3         | 7.69%   |
| XFCE          | 2         | 5.13%   |
| MATE          | 2         | 5.13%   |
| KDE4          | 2         | 5.13%   |
| KDE5          | 1         | 2.56%   |
| GNOME Classic | 1         | 2.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 19        | 51.35%  |
| X11     | 16        | 43.24%  |
| Unknown | 2         | 5.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM     | 18        | 48.65%  |
| Unknown | 18        | 48.65%  |
| SDDM    | 1         | 2.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 23        | 63.89%  |
| en_GB   | 3         | 8.33%   |
| de_DE   | 3         | 8.33%   |
| en_AU   | 2         | 5.56%   |
| Unknown | 2         | 5.56%   |
| zh_HK   | 1         | 2.78%   |
| pt_BR   | 1         | 2.78%   |
| pl_PL   | 1         | 2.78%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 19        | 52.78%  |
| BIOS | 17        | 47.22%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Xfs     | 31        | 83.78%  |
| Ext4    | 4         | 10.81%  |
| Unknown | 2         | 5.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 18        | 48.65%  |
| GPT     | 13        | 35.14%  |
| MBR     | 6         | 16.22%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 32        | 88.89%  |
| Yes       | 4         | 11.11%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 34        | 97.14%  |
| Yes       | 1         | 2.86%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 17        | 48.57%  |
| Dell             | 7         | 20%     |
| Hewlett-Packard  | 5         | 14.29%  |
| ASUSTek Computer | 3         | 8.57%   |
| Standard         | 1         | 2.86%   |
| Panasonic        | 1         | 2.86%   |
| Dynabook         | 1         | 2.86%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Lenovo ThinkPad T450 20BUS14900           | 2         | 5.71%   |
| ASUS X510UR                               | 2         | 5.71%   |
| Standard BW Series                        | 1         | 2.86%   |
| Panasonic CF-53AAG54FM                    | 1         | 2.86%   |
| Lenovo ThinkPad X280 20KES4H34G           | 1         | 2.86%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QWS1R800 | 1         | 2.86%   |
| Lenovo ThinkPad T490 20N3S77600           | 1         | 2.86%   |
| Lenovo ThinkPad T480 20L6S56Y2X           | 1         | 2.86%   |
| Lenovo ThinkPad T480 20L5A07TAU           | 1         | 2.86%   |
| Lenovo ThinkPad T470 20HES21434           | 1         | 2.86%   |
| Lenovo ThinkPad T470 20HES0E71M           | 1         | 2.86%   |
| Lenovo ThinkPad T430s 2355C33             | 1         | 2.86%   |
| Lenovo ThinkPad P70 20ESS04S00            | 1         | 2.86%   |
| Lenovo ThinkPad P50s 20FL000MUS           | 1         | 2.86%   |
| Lenovo ThinkPad L540 20AVCTO1WW           | 1         | 2.86%   |
| Lenovo ThinkPad L490 20Q5CTO1WW           | 1         | 2.86%   |
| Lenovo Legion 5 15IMH05 82AU              | 1         | 2.86%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS       | 1         | 2.86%   |
| Lenovo IdeaPad 300-15ISK 80RS             | 1         | 2.86%   |
| HP ZBook 15                               | 1         | 2.86%   |
| HP ProBook 445 G6                         | 1         | 2.86%   |
| HP Notebook                               | 1         | 2.86%   |
| HP EliteBook 840 G5                       | 1         | 2.86%   |
| HP Compaq 6730b                           | 1         | 2.86%   |
| Dynabook PORTEGE X40-G                    | 1         | 2.86%   |
| Dell Precision M4800                      | 1         | 2.86%   |
| Dell Precision M4600                      | 1         | 2.86%   |
| Dell Latitude E6420                       | 1         | 2.86%   |
| Dell Latitude 7420                        | 1         | 2.86%   |
| Dell Latitude 7410                        | 1         | 2.86%   |
| Dell Inspiron 5502                        | 1         | 2.86%   |
| Dell Inspiron 3542                        | 1         | 2.86%   |
| ASUS UX305FA                              | 1         | 2.86%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 14        | 40%     |
| Dell Latitude          | 3         | 8.57%   |
| Lenovo IdeaPad         | 2         | 5.71%   |
| Dell Precision         | 2         | 5.71%   |
| Dell Inspiron          | 2         | 5.71%   |
| ASUS X510UR            | 2         | 5.71%   |
| Standard BW            | 1         | 2.86%   |
| Panasonic CF-53AAG54FM | 1         | 2.86%   |
| Lenovo Legion          | 1         | 2.86%   |
| HP ZBook               | 1         | 2.86%   |
| HP ProBook             | 1         | 2.86%   |
| HP Notebook            | 1         | 2.86%   |
| HP EliteBook           | 1         | 2.86%   |
| HP Compaq              | 1         | 2.86%   |
| Dynabook PORTEGE       | 1         | 2.86%   |
| ASUS UX305FA           | 1         | 2.86%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 5         | 14.29%  |
| 2020 | 4         | 11.43%  |
| 2018 | 4         | 11.43%  |
| 2017 | 4         | 11.43%  |
| 2016 | 4         | 11.43%  |
| 2015 | 3         | 8.57%   |
| 2014 | 3         | 8.57%   |
| 2011 | 3         | 8.57%   |
| 2013 | 2         | 5.71%   |
| 2021 | 1         | 2.86%   |
| 2012 | 1         | 2.86%   |
| 2008 | 1         | 2.86%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 35        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 30        | 83.33%  |
| Enabled  | 6         | 16.67%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 35        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 11        | 30.56%  |
| 32.01-64.0  | 10        | 27.78%  |
| 4.01-8.0    | 6         | 16.67%  |
| 3.01-4.0    | 4         | 11.11%  |
| 16.01-24.0  | 4         | 11.11%  |
| 64.01-256.0 | 1         | 2.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 14        | 33.33%  |
| 2.01-3.0   | 11        | 26.19%  |
| 8.01-16.0  | 7         | 16.67%  |
| 3.01-4.0   | 6         | 14.29%  |
| 1.01-2.0   | 2         | 4.76%   |
| 24.01-32.0 | 1         | 2.38%   |
| 0.51-1.0   | 1         | 2.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 31        | 86.11%  |
| 2      | 3         | 8.33%   |
| 4      | 1         | 2.78%   |
| 3      | 1         | 2.78%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 26        | 74.29%  |
| Yes       | 9         | 25.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 82.86%  |
| No        | 6         | 17.14%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 97.14%  |
| No        | 1         | 2.86%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 23        | 63.89%  |
| No        | 13        | 36.11%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 12        | 33.33%  |
| Germany     | 4         | 11.11%  |
| UK          | 3         | 8.33%   |
| Brazil      | 3         | 8.33%   |
| Poland      | 2         | 5.56%   |
| Netherlands | 2         | 5.56%   |
| Australia   | 2         | 5.56%   |
| Yemen       | 1         | 2.78%   |
| Romania     | 1         | 2.78%   |
| Pakistan    | 1         | 2.78%   |
| Hungary     | 1         | 2.78%   |
| Hong Kong   | 1         | 2.78%   |
| Finland     | 1         | 2.78%   |
| Bulgaria    | 1         | 2.78%   |
| Argentina   | 1         | 2.78%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| San Diego          | 3         | 7.5%    |
| Siegen             | 2         | 5%      |
| Seattle            | 2         | 5%      |
| Utrecht            | 1         | 2.5%    |
| Sydney             | 1         | 2.5%    |
| Sofia              | 1         | 2.5%    |
| Shrewsbury         | 1         | 2.5%    |
| Sao Paulo          | 1         | 2.5%    |
| Sao Caetano do Sul | 1         | 2.5%    |
| Sanaa              | 1         | 2.5%    |
| Rocklin            | 1         | 2.5%    |
| Port Saint Lucie   | 1         | 2.5%    |
| Pleven             | 1         | 2.5%    |
| Ngau Wu Tok        | 1         | 2.5%    |
| Maple Valley       | 1         | 2.5%    |
| Ludwigsburg        | 1         | 2.5%    |
| London             | 1         | 2.5%    |
| Las Vegas          | 1         | 2.5%    |
| Katowice           | 1         | 2.5%    |
| Karachi            | 1         | 2.5%    |
| Helsinki           | 1         | 2.5%    |
| Greven             | 1         | 2.5%    |
| Fremont            | 1         | 2.5%    |
| Ercsi              | 1         | 2.5%    |
| Drochtersen        | 1         | 2.5%    |
| Dallas             | 1         | 2.5%    |
| Colorado Springs   | 1         | 2.5%    |
| Chicago            | 1         | 2.5%    |
| Castelar           | 1         | 2.5%    |
| Canberra           | 1         | 2.5%    |
| Campinas           | 1         | 2.5%    |
| Bydgoszcz          | 1         | 2.5%    |
| Bucharest          | 1         | 2.5%    |
| Bracknell          | 1         | 2.5%    |
| Berlin             | 1         | 2.5%    |
| Amsterdam          | 1         | 2.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 16        | 21     | 39.02%  |
| SanDisk                 | 6         | 7      | 14.63%  |
| Seagate                 | 3         | 3      | 7.32%   |
| HGST                    | 3         | 6      | 7.32%   |
| WDC                     | 2         | 2      | 4.88%   |
| Unknown                 | 2         | 4      | 4.88%   |
| Micron Technology       | 2         | 5      | 4.88%   |
| Union Memory (Shenzhen) | 1         | 2      | 2.44%   |
| Lite-On                 | 1         | 1      | 2.44%   |
| Lenovo                  | 1         | 1      | 2.44%   |
| Kingston                | 1         | 7      | 2.44%   |
| JMicron Technology      | 1         | 1      | 2.44%   |
| Fujitsu                 | 1         | 1      | 2.44%   |
| Crucial                 | 1         | 2      | 2.44%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| SanDisk SSD PLUS 1000GB                      | 2         | 4.76%   |
| Samsung MZVLB512HAJQ-000L7 512GB             | 2         | 4.76%   |
| Samsung MZ7LN512HMJP-000L7 512GB SSD         | 2         | 4.76%   |
| WDC WDS250G2B0A-00SM50 250GB SSD             | 1         | 2.38%   |
| WDC WD10JPCX-24UE4T0 1TB                     | 1         | 2.38%   |
| Unknown SD/MMC/MS PRO 64GB                   | 1         | 2.38%   |
| Unknown MMC Card  256GB                      | 1         | 2.38%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 2.38%   |
| Seagate ST9750420AS 752GB                    | 1         | 2.38%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 2.38%   |
| Seagate BUP Slim BK 1TB                      | 1         | 2.38%   |
| SanDisk SDSSDH3512G 512GB                    | 1         | 2.38%   |
| SanDisk SD7SN3Q256G1002 256GB SSD            | 1         | 2.38%   |
| SanDisk SD6SB1M-256G-1006 256GB SSD          | 1         | 2.38%   |
| SanDisk NVMe SSD Drive 512GB                 | 1         | 2.38%   |
| Samsung SSD SM841N 2.5 7mm 512GB             | 1         | 2.38%   |
| Samsung SSD PM830 2.5 7mm 256GB              | 1         | 2.38%   |
| Samsung SSD 850 PRO 256GB                    | 1         | 2.38%   |
| Samsung PM9A1 NVMe 512GB                     | 1         | 2.38%   |
| Samsung NVMe SSD Drive 512GB                 | 1         | 2.38%   |
| Samsung NVMe SSD Drive 1TB                   | 1         | 2.38%   |
| Samsung MZVLW256HEHP-000L7 256GB             | 1         | 2.38%   |
| Samsung MZVLB1T0HBLR-000L7 1TB               | 1         | 2.38%   |
| Samsung MZVLB1T0HALR-000H1 1TB               | 1         | 2.38%   |
| Samsung MZNLN512HCJH-000L1 512GB SSD         | 1         | 2.38%   |
| Samsung MZ7LN512HCHP-000L1 512GB SSD         | 1         | 2.38%   |
| Samsung MZ7LN256HCHP-000L7 256GB SSD         | 1         | 2.38%   |
| Micron NVMe SSD Drive 256GB                  | 1         | 2.38%   |
| Micron 2300_MTFDHBA256TDV 256GB              | 1         | 2.38%   |
| Micron 2200S NVMe 256GB                      | 1         | 2.38%   |
| Lite-On NVMe SSD Drive 512GB                 | 1         | 2.38%   |
| Lenovo LENSE30512GMSP34MEAT3TA 512GB         | 1         | 2.38%   |
| Kingston NVMe SSD Drive 1TB                  | 1         | 2.38%   |
| JMicron Disk 500GB                           | 1         | 2.38%   |
| HGST HTS545050A7E380 500GB                   | 1         | 2.38%   |
| HGST HTS541010A9E680 1TB                     | 1         | 2.38%   |
| HGST HTS541010A7E630 1TB                     | 1         | 2.38%   |
| Fujitsu MHZ2160BH G2 160GB                   | 1         | 2.38%   |
| Crucial CT500MX500SSD1 500GB                 | 1         | 2.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 3         | 3      | 30%     |
| HGST               | 3         | 6      | 30%     |
| WDC                | 1         | 1      | 10%     |
| Unknown            | 1         | 3      | 10%     |
| JMicron Technology | 1         | 1      | 10%     |
| Fujitsu            | 1         | 1      | 10%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 11     | 53.33%  |
| SanDisk             | 5         | 5      | 33.33%  |
| WDC                 | 1         | 1      | 6.67%   |
| Crucial             | 1         | 2      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 15        | 28     | 37.5%   |
| SSD  | 15        | 19     | 37.5%   |
| HDD  | 9         | 15     | 22.5%   |
| MMC  | 1         | 1      | 2.5%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 21        | 29     | 53.85%  |
| NVMe | 15        | 28     | 38.46%  |
| SAS  | 2         | 5      | 5.13%   |
| MMC  | 1         | 1      | 2.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 13        | 20     | 54.17%  |
| 0.01-0.5   | 11        | 14     | 45.83%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 8         | 22.22%  |
| 101-250    | 6         | 16.67%  |
| 1-20       | 6         | 16.67%  |
| 501-1000   | 6         | 16.67%  |
| Unknown    | 6         | 16.67%  |
| 2001-3000  | 2         | 5.56%   |
| 51-100     | 2         | 5.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 11        | 28.95%  |
| 21-50     | 7         | 18.42%  |
| Unknown   | 6         | 15.79%  |
| 51-100    | 5         | 13.16%  |
| 251-500   | 4         | 10.53%  |
| 101-250   | 2         | 5.26%   |
| 501-1000  | 2         | 5.26%   |
| 1001-2000 | 1         | 2.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST9750420AS 752GB          | 1         | 1      | 50%     |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 2      | 100%    |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 20        | 38     | 52.63%  |
| Works    | 16        | 23     | 42.11%  |
| Malfunc  | 2         | 2      | 5.26%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 19        | 51.35%  |
| Samsung Electronics         | 8         | 21.62%  |
| AMD                         | 3         | 8.11%   |
| Micron Technology           | 2         | 5.41%   |
| Union Memory (Shenzhen)     | 1         | 2.7%    |
| SanDisk                     | 1         | 2.7%    |
| Lite-On Technology          | 1         | 2.7%    |
| Lenovo                      | 1         | 2.7%    |
| Kingston Technology Company | 1         | 2.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 6         | 16.22%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 4         | 10.81%  |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 8.11%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 3         | 8.11%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 3         | 8.11%   |
| Micron Non-Volatile memory controller                                            | 2         | 5.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 5.41%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 2.7%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 2.7%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 2.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 2.7%    |
| Lite-On Non-Volatile memory controller                                           | 1         | 2.7%    |
| Lenovo Non-Volatile memory controller                                            | 1         | 2.7%    |
| Kingston Company A2000 NVMe SSD                                                  | 1         | 2.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 2.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 2.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1         | 2.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 2.7%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 1         | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 1         | 2.7%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 1         | 2.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 19        | 51.35%  |
| NVMe | 15        | 40.54%  |
| RAID | 3         | 8.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 32        | 91.43%  |
| AMD    | 3         | 8.57%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-7500U CPU @ 2.70GHz               | 2         | 5.71%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 2         | 5.71%   |
| Intel Core i7-10610U CPU @ 1.80GHz              | 2         | 5.71%   |
| Intel Core i5-8350U CPU @ 1.70GHz               | 2         | 5.71%   |
| Intel Core i5-7300U CPU @ 2.60GHz               | 2         | 5.71%   |
| Intel Core i5-5300U CPU @ 2.30GHz               | 2         | 5.71%   |
| Intel Processor 5Y10 CPU @ 0.80GHz              | 1         | 2.86%   |
| Intel Core i9-9880H CPU @ 2.30GHz               | 1         | 2.86%   |
| Intel Core i7-8665U CPU @ 1.90GHz               | 1         | 2.86%   |
| Intel Core i7-8650U CPU @ 1.90GHz               | 1         | 2.86%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 1         | 2.86%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz              | 1         | 2.86%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz              | 1         | 2.86%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz              | 1         | 2.86%   |
| Intel Core i7-2860QM CPU @ 2.50GHz              | 1         | 2.86%   |
| Intel Core i7-2760QM CPU @ 2.40GHz              | 1         | 2.86%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 1         | 2.86%   |
| Intel Core i5-8365U CPU @ 1.60GHz               | 1         | 2.86%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 1         | 2.86%   |
| Intel Core i5-4210M CPU @ 2.60GHz               | 1         | 2.86%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 1         | 2.86%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 1         | 2.86%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz            | 1         | 2.86%   |
| Intel Celeron CPU N3010 @ 1.04GHz               | 1         | 2.86%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz         | 1         | 2.86%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 1         | 2.86%   |
| AMD Ryzen 7 PRO 2700U w/ Radeon Vega Mobile Gfx | 1         | 2.86%   |
| AMD A9-9420e RADEON R5, 5 COMPUTE CORES 2C+3G   | 1         | 2.86%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics     | 1         | 2.86%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 15        | 42.86%  |
| Intel Core i5    | 11        | 31.43%  |
| Other            | 4         | 11.43%  |
| Intel Core i9    | 1         | 2.86%   |
| Intel Core 2 Duo | 1         | 2.86%   |
| Intel Celeron    | 1         | 2.86%   |
| AMD Ryzen 7 PRO  | 1         | 2.86%   |
| AMD A8           | 1         | 2.86%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 16        | 45.71%  |
| 2      | 16        | 45.71%  |
| 8      | 1         | 2.86%   |
| 6      | 1         | 2.86%   |
| 1      | 1         | 2.86%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 35        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 31        | 88.57%  |
| 1      | 4         | 11.43%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 34        | 94.44%  |
| Unknown        | 2         | 5.56%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ec    | 4         | 11.43%  |
| 0x806ea    | 4         | 11.43%  |
| 0x306d4    | 3         | 8.57%   |
| 0x306c3    | 3         | 8.57%   |
| 0x206a7    | 3         | 8.57%   |
| 0x806e9    | 2         | 5.71%   |
| 0x806c1    | 2         | 5.71%   |
| 0x406e3    | 2         | 5.71%   |
| Unknown    | 2         | 5.71%   |
| 0xa0652    | 1         | 2.86%   |
| 0x906ed    | 1         | 2.86%   |
| 0x506e3    | 1         | 2.86%   |
| 0x406c4    | 1         | 2.86%   |
| 0x40651    | 1         | 2.86%   |
| 0x306a9    | 1         | 2.86%   |
| 0x10676    | 1         | 2.86%   |
| 0x0810100b | 1         | 2.86%   |
| 0x07030105 | 1         | 2.86%   |
| 0x06006705 | 1         | 2.86%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 13        | 37.14%  |
| Haswell     | 4         | 11.43%  |
| Skylake     | 3         | 8.57%   |
| SandyBridge | 3         | 8.57%   |
| Broadwell   | 3         | 8.57%   |
| TigerLake   | 2         | 5.71%   |
| Zen         | 1         | 2.86%   |
| Silvermont  | 1         | 2.86%   |
| Puma        | 1         | 2.86%   |
| Penryn      | 1         | 2.86%   |
| IvyBridge   | 1         | 2.86%   |
| Excavator   | 1         | 2.86%   |
| CometLake   | 1         | 2.86%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 28        | 60.87%  |
| Nvidia | 11        | 23.91%  |
| AMD    | 7         | 15.22%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 4         | 8.7%    |
| Intel HD Graphics 620                                                                    | 4         | 8.7%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 6.52%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 4.35%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 4.35%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 4.35%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 4.35%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 4.35%   |
| Intel HD Graphics 5500                                                                   | 2         | 4.35%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 4.35%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 2.17%   |
| Nvidia TU117M                                                                            | 1         | 2.17%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 2.17%   |
| Nvidia GM204GLM [Quadro M4000M]                                                          | 1         | 2.17%   |
| Nvidia GM108GLM [Quadro K620M / Quadro M500M]                                            | 1         | 2.17%   |
| Nvidia GK208GLM [Quadro K610M]                                                           | 1         | 2.17%   |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 2.17%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 2.17%   |
| Intel HD Graphics 5300                                                                   | 1         | 2.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 2.17%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 2.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.17%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 2.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1         | 2.17%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 1         | 2.17%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                                          | 1         | 2.17%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 2.17%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 2.17%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 2.17%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 2.17%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 1         | 2.17%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 17        | 47.22%  |
| Intel + Nvidia | 8         | 22.22%  |
| 1 x Nvidia     | 4         | 11.11%  |
| 1 x AMD        | 4         | 11.11%  |
| Intel + AMD    | 3         | 8.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 32        | 86.49%  |
| Proprietary | 3         | 8.11%   |
| Unknown     | 2         | 5.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 17        | 47.22%  |
| 1.01-2.0   | 9         | 25%     |
| 3.01-4.0   | 5         | 13.89%  |
| 0.51-1.0   | 3         | 8.33%   |
| 0.01-0.5   | 2         | 5.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 12        | 23.08%  |
| LG Display           | 9         | 17.31%  |
| Samsung Electronics  | 4         | 7.69%   |
| Lenovo               | 4         | 7.69%   |
| Dell                 | 4         | 7.69%   |
| Chimei Innolux       | 4         | 7.69%   |
| BOE                  | 4         | 7.69%   |
| ViewSonic            | 3         | 5.77%   |
| InfoVision           | 2         | 3.85%   |
| BenQ                 | 2         | 3.85%   |
| BOE Technology Group | 1         | 1.92%   |
| ASUSTek Computer     | 1         | 1.92%   |
| Ancor Communications | 1         | 1.92%   |
| Acer                 | 1         | 1.92%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 2         | 3.64%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 2         | 3.64%   |
| Dell U2718Q DELA0E9 3840x2160 854x481mm 38.6-inch                     | 2         | 3.64%   |
| BenQ GL2760 BNQ78D5 1920x1080 598x336mm 27.0-inch                     | 2         | 3.64%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch         | 2         | 3.64%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 2         | 3.64%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch         | 1         | 1.82%   |
| ViewSonic VX2433wm VSC3822 1920x1080 520x290mm 23.4-inch              | 1         | 1.82%   |
| ViewSonic VG2439 Series VSCD22B 1920x1080 521x293mm 23.5-inch         | 1         | 1.82%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 433x271mm 20.1-inch  | 1         | 1.82%   |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch     | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SDC3256 1920x1080 382x215mm 17.3-inch | 1         | 1.82%   |
| Samsung Electronics C32HG7x SAM0E14 2560x1440 697x392mm 31.5-inch     | 1         | 1.82%   |
| LG Display LCD Monitor LGD0628 1920x1080 309x174mm 14.0-inch          | 1         | 1.82%   |
| LG Display LCD Monitor LGD0609 1920x1080 309x174mm 14.0-inch          | 1         | 1.82%   |
| LG Display LCD Monitor LGD04BD 1366x768 344x194mm 15.5-inch           | 1         | 1.82%   |
| LG Display LCD Monitor LGD047C 1366x768 310x174mm 14.0-inch           | 1         | 1.82%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 1         | 1.82%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch           | 1         | 1.82%   |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch          | 1         | 1.82%   |
| Lenovo T24i-10 LEN61A6 1920x1080 527x296mm 23.8-inch                  | 1         | 1.82%   |
| Lenovo LEN T2424pA LEN60C8 1920x1080 527x296mm 23.8-inch              | 1         | 1.82%   |
| Lenovo LEN T2254pC LEN60CC 1680x1050 474x296mm 22.0-inch              | 1         | 1.82%   |
| Lenovo LEN P27u-10 LEN61B0 3840x2160 597x336mm 27.0-inch              | 1         | 1.82%   |
| Dell S3221QS DELD105 3840x2160 697x392mm 31.5-inch                    | 1         | 1.82%   |
| Dell P2719H DEL4184 1920x1080 600x340mm 27.2-inch                     | 1         | 1.82%   |
| Dell P2414H DELA09C 1920x1080 530x300mm 24.0-inch                     | 1         | 1.82%   |
| Dell E2009W DEL4240 1680x1050 433x271mm 20.1-inch                     | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN14E8 1920x1080 309x173mm 13.9-inch      | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 1         | 1.82%   |
| BOE Technology Group LCD Monitor 1920x1080                            | 1         | 1.82%   |
| BOE LCD Monitor BOE08E8 1920x1080 344x194mm 15.5-inch                 | 1         | 1.82%   |
| BOE LCD Monitor BOE0819 1920x1080 344x194mm 15.5-inch                 | 1         | 1.82%   |
| BOE LCD Monitor BOE074F 1920x1080 309x173mm 13.9-inch                 | 1         | 1.82%   |
| BOE LCD Monitor BOE0630 1920x1080 344x194mm 15.5-inch                 | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO8074 1280x800 331x207mm 15.4-inch         | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 1         | 1.82%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 27        | 64.29%  |
| 1600x900 (HD+)     | 4         | 9.52%   |
| 1366x768 (WXGA)    | 4         | 9.52%   |
| 3840x2160 (4K)     | 3         | 7.14%   |
| 1680x1050 (WSXGA+) | 2         | 4.76%   |
| 2560x1440 (QHD)    | 1         | 2.38%   |
| 1280x800 (WXGA)    | 1         | 2.38%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 14        | 26.42%  |
| 14      | 12        | 22.64%  |
| 27      | 6         | 11.32%  |
| 13      | 5         | 9.43%   |
| 24      | 4         | 7.55%   |
| 23      | 3         | 5.66%   |
| 38      | 2         | 3.77%   |
| 31      | 2         | 3.77%   |
| 22      | 1         | 1.89%   |
| 20      | 1         | 1.89%   |
| 17      | 1         | 1.89%   |
| 12      | 1         | 1.89%   |
| Unknown | 1         | 1.89%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 30        | 57.69%  |
| 501-600     | 12        | 23.08%  |
| 801-900     | 2         | 3.85%   |
| 601-700     | 2         | 3.85%   |
| 401-500     | 2         | 3.85%   |
| 201-300     | 2         | 3.85%   |
| 351-400     | 1         | 1.92%   |
| Unknown     | 1         | 1.92%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 34        | 89.47%  |
| 16/10   | 3         | 7.89%   |
| Unknown | 1         | 2.63%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 16        | 30.77%  |
| 101-110        | 14        | 26.92%  |
| 201-250        | 7         | 13.46%  |
| 301-350        | 6         | 11.54%  |
| 351-500        | 2         | 3.85%   |
| 501-1000       | 2         | 3.85%   |
| 71-80          | 1         | 1.92%   |
| 61-70          | 1         | 1.92%   |
| 151-200        | 1         | 1.92%   |
| 121-130        | 1         | 1.92%   |
| Unknown        | 1         | 1.92%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 26        | 55.32%  |
| 51-100  | 11        | 23.4%   |
| 101-120 | 6         | 12.77%  |
| 161-240 | 3         | 6.38%   |
| Unknown | 1         | 2.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 21        | 58.33%  |
| 2     | 7         | 19.44%  |
| 3     | 5         | 13.89%  |
| 0     | 2         | 5.56%   |
| 4     | 1         | 2.78%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 29        | 56.86%  |
| Realtek Semiconductor | 11        | 21.57%  |
| Qualcomm Atheros      | 3         | 5.88%   |
| Lenovo                | 3         | 5.88%   |
| Ralink Technology     | 1         | 1.96%   |
| NetGear               | 1         | 1.96%   |
| Fibocom               | 1         | 1.96%   |
| Broadcom Limited      | 1         | 1.96%   |
| Broadcom              | 1         | 1.96%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                        | 8         | 11.11%  |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 6.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 5.56%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4         | 5.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 5.56%   |
| Intel Wireless 7265                                               | 3         | 4.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 4.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 2.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 2.78%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 2         | 2.78%   |
| Intel Wireless 8260                                               | 2         | 2.78%   |
| Intel Wireless 7260                                               | 2         | 2.78%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 2.78%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 2.78%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 2.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 2.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 1.39%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 1.39%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 1.39%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 1.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.39%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                   | 1         | 1.39%   |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 1.39%   |
| Intel Wireless-AC 9260                                            | 1         | 1.39%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 1.39%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.39%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 1.39%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 1         | 1.39%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.39%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.39%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.39%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.39%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.39%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.39%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 1.39%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 1.39%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                 | 1         | 1.39%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 1         | 1.39%   |
| Broadcom BCM43142 802.11b/g/n                                     | 1         | 1.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 28        | 73.68%  |
| Realtek Semiconductor | 3         | 7.89%   |
| Qualcomm Atheros      | 3         | 7.89%   |
| Ralink Technology     | 1         | 2.63%   |
| NetGear               | 1         | 2.63%   |
| Fibocom               | 1         | 2.63%   |
| Broadcom              | 1         | 2.63%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                 | 8         | 21.05%  |
| Intel Wireless 7265                                        | 3         | 7.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]               | 3         | 7.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 2         | 5.26%   |
| Intel Wireless 8260                                        | 2         | 5.26%   |
| Intel Wireless 7260                                        | 2         | 5.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 2         | 5.26%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 1         | 2.63%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1         | 2.63%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 1         | 2.63%   |
| Ralink MT7601U Wireless Adapter                            | 1         | 2.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1         | 2.63%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]            | 1         | 2.63%   |
| Intel Wireless-AC 9260                                     | 1         | 2.63%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 1         | 2.63%   |
| Intel Wi-Fi 6 AX201                                        | 1         | 2.63%   |
| Intel Wi-Fi 6 AX200                                        | 1         | 2.63%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection    | 1         | 2.63%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1         | 2.63%   |
| Intel Centrino Ultimate-N 6300                             | 1         | 2.63%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                   | 1         | 2.63%   |
| Fibocom L830-EB-00 LTE WWAN Modem                          | 1         | 2.63%   |
| Broadcom BCM43142 802.11b/g/n                              | 1         | 2.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 20        | 58.82%  |
| Realtek Semiconductor | 10        | 29.41%  |
| Lenovo                | 3         | 8.82%   |
| Broadcom Limited      | 1         | 2.94%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Intel Ethernet Connection (4) I219-LM                             | 5         | 14.71%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 11.76%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4         | 11.76%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 11.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 5.88%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 2         | 5.88%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 5.88%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 5.88%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 5.88%   |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 2.94%   |
| Intel Ethernet Connection I219-V                                  | 1         | 2.94%   |
| Intel Ethernet Connection I217-V                                  | 1         | 2.94%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 2.94%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 2.94%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.94%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 1         | 2.94%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 34        | 53.97%  |
| Ethernet | 29        | 46.03%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 26        | 66.67%  |
| Ethernet | 13        | 33.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 26        | 74.29%  |
| 1     | 9         | 25.71%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 27        | 69.23%  |
| Yes  | 12        | 30.77%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 16        | 69.57%  |
| Qualcomm Atheros Communications | 3         | 13.04%  |
| Broadcom                        | 2         | 8.7%    |
| Realtek Semiconductor           | 1         | 4.35%   |
| Alps Electric                   | 1         | 4.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 10        | 43.48%  |
| Intel AX201 Bluetooth                          | 3         | 13.04%  |
| Qualcomm Atheros  Bluetooth Device             | 2         | 8.7%    |
| Realtek  Bluetooth 4.2 Adapter                 | 1         | 4.35%   |
| Qualcomm Atheros AR9462 Bluetooth              | 1         | 4.35%   |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 1         | 4.35%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1         | 4.35%   |
| Intel AX210 Bluetooth                          | 1         | 4.35%   |
| Broadcom BCM43142A0 Bluetooth 4.0              | 1         | 4.35%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 1         | 4.35%   |
| Alps Electric UGTZ4 Bluetooth                  | 1         | 4.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 32        | 60.38%  |
| Nvidia              | 5         | 9.43%   |
| AMD                 | 5         | 9.43%   |
| Lenovo              | 4         | 7.55%   |
| GN Netcom           | 4         | 7.55%   |
| Unknown             | 1         | 1.89%   |
| TEAC                | 1         | 1.89%   |
| C-Media Electronics | 1         | 1.89%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 16.13%  |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 4.84%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 4.84%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 4.84%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 4.84%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 3.23%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 2         | 3.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 3.23%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 3.23%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 3.23%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 3.23%   |
| Unknown Definitive Sym1                                                                           | 1         | 1.61%   |
| TEAC US-2x2                                                                                       | 1         | 1.61%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 1.61%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 1.61%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 1.61%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                                          | 1         | 1.61%   |
| Lenovo ThinkPad Dock USB Audio                                                                    | 1         | 1.61%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1.61%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.61%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.61%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 1.61%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 1.61%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1         | 1.61%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.61%   |
| GN Netcom Jabra SPEAK 510                                                                         | 1         | 1.61%   |
| GN Netcom Jabra PRO 9470                                                                          | 1         | 1.61%   |
| GN Netcom Jabra Link 370                                                                          | 1         | 1.61%   |
| GN Netcom Jabra EVOLVE LINK                                                                       | 1         | 1.61%   |
| C-Media Electronics Blue Snowball                                                                 | 1         | 1.61%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 1.61%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.61%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 1.61%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.61%   |
| AMD High Definition Audio Controller                                                              | 1         | 1.61%   |
| AMD FCH Azalia Controller                                                                         | 1         | 1.61%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 1.61%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 1.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 6         | 31.58%  |
| SK hynix            | 4         | 21.05%  |
| Micron Technology   | 4         | 21.05%  |
| Kingston            | 2         | 10.53%  |
| Unknown             | 1         | 5.26%   |
| Corsair             | 1         | 5.26%   |
| Avant               | 1         | 5.26%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s           | 2         | 10%     |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                     | 1         | 5%      |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 5%      |
| SK hynix RAM HMAA1GS6CMR8N-VK 8192MB Row Of Chips DDR4 2667MT/s | 1         | 5%      |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s    | 1         | 5%      |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s          | 1         | 5%      |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s          | 1         | 5%      |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 5%      |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s          | 1         | 5%      |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s          | 1         | 5%      |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s          | 1         | 5%      |
| Micron RAM Module 16384MB SODIMM DDR4 2400MT/s                  | 1         | 5%      |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s     | 1         | 5%      |
| Micron RAM 16JTF1G64HZ-1G4D1 8GB SODIMM DDR3 1333MT/s           | 1         | 5%      |
| Micron RAM 16ATF2G64HZ-2G1A1 16384MB SODIMM DDR4 2133MT/s       | 1         | 5%      |
| Kingston RAM KX830D-ELC 4GB SODIMM DDR3 1333MT/s                | 1         | 5%      |
| Kingston RAM KN2M64-ETB 8GB SODIMM DDR3 1600MT/s                | 1         | 5%      |
| Corsair RAM CMSX32GX4M2A2666C18 16GB SODIMM DDR4 2667MT/s       | 1         | 5%      |
| Avant RAM H6451U66G1600G 4096MB SODIMM DDR3 1600MT/s            | 1         | 5%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 10        | 52.63%  |
| DDR3   | 8         | 42.11%  |
| LPDDR4 | 1         | 5.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 16        | 84.21%  |
| Row Of Chips | 3         | 15.79%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 8         | 42.11%  |
| 16384 | 5         | 26.32%  |
| 4096  | 5         | 26.32%  |
| 32768 | 1         | 5.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 6         | 31.58%  |
| 1600  | 6         | 31.58%  |
| 2400  | 2         | 10.53%  |
| 1333  | 2         | 10.53%  |
| 4267  | 1         | 5.26%   |
| 2133  | 1         | 5.26%   |
| 1866  | 1         | 5.26%   |

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

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 120 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Chicony Electronics   | 9         | 32.14%  |
| Logitech              | 4         | 14.29%  |
| IMC Networks          | 4         | 14.29%  |
| Suyin                 | 3         | 10.71%  |
| Realtek Semiconductor | 3         | 10.71%  |
| Lite-On Technology    | 3         | 10.71%  |
| Microdia              | 1         | 3.57%   |
| Acer                  | 1         | 3.57%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Chicony Integrated Camera               | 5         | 17.24%  |
| Realtek Integrated_Webcam_HD            | 2         | 6.9%    |
| Lite-On Integrated Camera               | 2         | 6.9%    |
| IMC Networks VGA UVC WebCam             | 2         | 6.9%    |
| IMC Networks Integrated Camera          | 2         | 6.9%    |
| Chicony Integrated Camera (1280x720@30) | 2         | 6.9%    |
| Suyin Integrated_Webcam_HD              | 1         | 3.45%   |
| Suyin HP Truevision HD                  | 1         | 3.45%   |
| Suyin Asus Integrated Webcam            | 1         | 3.45%   |
| Realtek EasyCamera                      | 1         | 3.45%   |
| Microdia Webcam Vitade AF               | 1         | 3.45%   |
| Logitech Webcam C925e                   | 1         | 3.45%   |
| Logitech Webcam C920-C                  | 1         | 3.45%   |
| Logitech HD Webcam C615                 | 1         | 3.45%   |
| Logitech BRIO Ultra HD Webcam           | 1         | 3.45%   |
| Lite-On HP HD Camera                    | 1         | 3.45%   |
| Chicony TOSHIBA Web Camera - HD         | 1         | 3.45%   |
| Chicony ThinkPad T490 Webcam            | 1         | 3.45%   |
| Chicony Integrated IR Camera            | 1         | 3.45%   |
| Acer SunplusIT Integrated Camera        | 1         | 3.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 8         | 53.33%  |
| Synaptics        | 6         | 40%     |
| Upek             | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 20%     |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 20%     |
| Validity Sensors Synaptics WBDI                                            | 2         | 13.33%  |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 13.33%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 13.33%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 6.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 6.67%   |
| Unknown                                                                    | 1         | 6.67%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 83.33%  |
| Alcor Micro | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 3         | 50%     |
| Broadcom 58200                                 | 2         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 19        | 51.35%  |
| 0     | 13        | 35.14%  |
| 2     | 3         | 8.11%   |
| 3     | 2         | 5.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 15        | 51.72%  |
| Chipcard           | 5         | 17.24%  |
| Graphics card      | 3         | 10.34%  |
| Storage            | 2         | 6.9%    |
| Net/wireless       | 2         | 6.9%    |
| Card reader        | 1         | 3.45%   |
| Bluetooth          | 1         | 3.45%   |

