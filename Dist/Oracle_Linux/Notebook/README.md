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

Total: 66

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Dell      | Latitude 7430               | [299e6897d2](https://linux-hardware.org/?probe=299e6897d2) | Jun 05, 2023 |
| Lenovo    | ThinkPad T490 20N3S3XR00    | [0f80e19e5b](https://linux-hardware.org/?probe=0f80e19e5b) | May 23, 2023 |
| Lenovo    | ThinkPad W541 20EGS1PL00    | [751cc5dbc7](https://linux-hardware.org/?probe=751cc5dbc7) | May 22, 2023 |
| ASUSTek   | ZenBook UX425EA_UX425EA     | [9be6e0f395](https://linux-hardware.org/?probe=9be6e0f395) | Apr 18, 2023 |
| HP        | Laptop 17-cp0xxx            | [e87b8175b1](https://linux-hardware.org/?probe=e87b8175b1) | Jan 27, 2023 |
| HP        | Laptop 17-cp0xxx            | [70019cbdbf](https://linux-hardware.org/?probe=70019cbdbf) | Jan 25, 2023 |
| Google    | Lick                        | [d792b79719](https://linux-hardware.org/?probe=d792b79719) | Jan 12, 2023 |
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
| Oracle Linux 8.5 | 11        | 22.92%  |
| Oracle Linux 8.3 | 6         | 12.5%   |
| Oracle Linux 8.4 | 5         | 10.42%  |
| Oracle Linux 7.9 | 4         | 8.33%   |
| Oracle Linux 9.1 | 3         | 6.25%   |
| Oracle Linux 9.0 | 3         | 6.25%   |
| Oracle Linux 8.1 | 3         | 6.25%   |
| Oracle Linux 8.8 | 2         | 4.17%   |
| Oracle Linux 8.7 | 2         | 4.17%   |
| Oracle Linux 8.6 | 2         | 4.17%   |
| Oracle Linux 7.8 | 2         | 4.17%   |
| Oracle Linux 7.7 | 2         | 4.17%   |
| Oracle Linux 9.2 | 1         | 2.08%   |
| Oracle Linux 8.2 | 1         | 2.08%   |
| Oracle Linux 7.6 | 1         | 2.08%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Oracle Linux | 41        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Notebooks | Percent |
|------------------------------------|-----------|---------|
| 5.4.17-2036.103.3.1.el8uek.x86_64  | 3         | 5.66%   |
| 4.18.0-348.12.2.el8_5.x86_64       | 3         | 5.66%   |
| 5.4.17-2136.304.4.3.el8uek.x86_64  | 2         | 3.77%   |
| 5.4.17-2102.202.5.el8uek.x86_64    | 2         | 3.77%   |
| 5.15.0-2.52.3.el9uek.x86_64        | 2         | 3.77%   |
| 5.15.0-100.96.32.el8uek.x86_64     | 2         | 3.77%   |
| 4.18.0-147.3.1.el8_1.x86_64        | 2         | 3.77%   |
| 5.4.17-2136.312.3.4.el7uek.x86_64  | 1         | 1.89%   |
| 5.4.17-2136.310.7.el8uek.x86_64    | 1         | 1.89%   |
| 5.4.17-2136.309.4.el8uek.x86_64    | 1         | 1.89%   |
| 5.4.17-2136.308.9.el7uek.x86_64    | 1         | 1.89%   |
| 5.4.17-2136.306.1.3.el8uek.x86_64  | 1         | 1.89%   |
| 5.4.17-2136.305.5.4.el8uek.x86_64  | 1         | 1.89%   |
| 5.4.17-2136.305.5.3.el8uek.x86_64  | 1         | 1.89%   |
| 5.4.17-2136.305.5.2.el8uek.x86_64  | 1         | 1.89%   |
| 5.4.17-2136.301.1.4.el8uek.x86_64  | 1         | 1.89%   |
| 5.4.17-2136.300.7.el8uek.x86_64    | 1         | 1.89%   |
| 5.4.17-2102.205.7.3.el8uek.x86_64  | 1         | 1.89%   |
| 5.4.17-2102.204.4.4.el8uek.x86_64  | 1         | 1.89%   |
| 5.4.17-2102.204.4.2.el8uek.x86_64  | 1         | 1.89%   |
| 5.4.17-2102.201.3.el8uek.x86_64    | 1         | 1.89%   |
| 5.4.17-2102.200.13.el8uek.x86_64   | 1         | 1.89%   |
| 5.4.17-2036.104.4.el8uek.x86_64    | 1         | 1.89%   |
| 5.4.17-2011.0.7.el8uek.x86_64      | 1         | 1.89%   |
| 5.15.2-1.el8.elrepo.x86_64         | 1         | 1.89%   |
| 5.15.0-5.76.5.1.el9uek.x86_64      | 1         | 1.89%   |
| 5.15.0-101.103.2.1.el8uek.x86_64   | 1         | 1.89%   |
| 5.15.0-100.76.15.el9uek.x86_64     | 1         | 1.89%   |
| 5.15.0-0.30.20.1.el9uek.x86_64     | 1         | 1.89%   |
| 5.14.1-1.el8.elrepo.x86_64         | 1         | 1.89%   |
| 5.14.0-70.13.1.0.3.el9_0.x86_64    | 1         | 1.89%   |
| 5.14.0-284.11.1.el9_2.x86_64       | 1         | 1.89%   |
| 5.11.1-1.el8.elrepo.x86_64         | 1         | 1.89%   |
| 4.18.0-425.3.1.el8.x86_64          | 1         | 1.89%   |
| 4.18.0-240.15.1.el8_3.x86_64       | 1         | 1.89%   |
| 4.18.0-240.10.1.el8_3.x86_64       | 1         | 1.89%   |
| 4.18.0-193.1.2.el8_2.x86_64        | 1         | 1.89%   |
| 4.14.35-2047.510.4.1.el7uek.x86_64 | 1         | 1.89%   |
| 4.14.35-2025.401.4.el7uek.x86_64   | 1         | 1.89%   |
| 4.14.35-1902.4.8.el7uek.x86_64     | 1         | 1.89%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.17  | 15        | 34.88%  |
| 5.15.0  | 8         | 18.6%   |
| 4.18.0  | 8         | 18.6%   |
| 4.14.35 | 5         | 11.63%  |
| 5.14.0  | 2         | 4.65%   |
| 5.15.2  | 1         | 2.33%   |
| 5.14.1  | 1         | 2.33%   |
| 5.11.1  | 1         | 2.33%   |
| 4.1.12  | 1         | 2.33%   |
| 3.10.0  | 1         | 2.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 15        | 34.88%  |
| 5.15    | 9         | 20.93%  |
| 4.18    | 8         | 18.6%   |
| 4.14    | 5         | 11.63%  |
| 5.14    | 3         | 6.98%   |
| 5.11    | 1         | 2.33%   |
| 4.1     | 1         | 2.33%   |
| 3.10    | 1         | 2.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 41        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 33        | 73.33%  |
| Unknown       | 3         | 6.67%   |
| XFCE          | 2         | 4.44%   |
| MATE          | 2         | 4.44%   |
| KDE4          | 2         | 4.44%   |
| GNOME Classic | 2         | 4.44%   |
| KDE5          | 1         | 2.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 24        | 55.81%  |
| X11     | 17        | 39.53%  |
| Unknown | 2         | 4.65%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM     | 23        | 53.49%  |
| Unknown | 19        | 44.19%  |
| SDDM    | 1         | 2.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 28        | 66.67%  |
| en_GB   | 3         | 7.14%   |
| de_DE   | 3         | 7.14%   |
| en_AU   | 2         | 4.76%   |
| Unknown | 2         | 4.76%   |
| zh_HK   | 1         | 2.38%   |
| pt_BR   | 1         | 2.38%   |
| pl_PL   | 1         | 2.38%   |
| en_IN   | 1         | 2.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 25        | 59.52%  |
| BIOS | 17        | 40.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Xfs     | 37        | 86.05%  |
| Ext4    | 4         | 9.3%    |
| Unknown | 2         | 4.65%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 19        | 44.19%  |
| GPT     | 18        | 41.86%  |
| MBR     | 6         | 13.95%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 38        | 90.48%  |
| Yes       | 4         | 9.52%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 39        | 95.12%  |
| Yes       | 2         | 4.88%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 19        | 46.34%  |
| Dell             | 8         | 19.51%  |
| Hewlett-Packard  | 6         | 14.63%  |
| ASUSTek Computer | 4         | 9.76%   |
| Standard         | 1         | 2.44%   |
| Panasonic        | 1         | 2.44%   |
| Google           | 1         | 2.44%   |
| Dynabook         | 1         | 2.44%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Lenovo ThinkPad T450 20BUS14900           | 2         | 4.88%   |
| ASUS X510UR                               | 2         | 4.88%   |
| Standard BW Series                        | 1         | 2.44%   |
| Panasonic CF-53AAG54FM                    | 1         | 2.44%   |
| Lenovo ThinkPad X280 20KES4H34G           | 1         | 2.44%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QWS1R800 | 1         | 2.44%   |
| Lenovo ThinkPad W541 20EGS1PL00           | 1         | 2.44%   |
| Lenovo ThinkPad T490 20N3S77600           | 1         | 2.44%   |
| Lenovo ThinkPad T490 20N3S3XR00           | 1         | 2.44%   |
| Lenovo ThinkPad T480 20L6S56Y2X           | 1         | 2.44%   |
| Lenovo ThinkPad T480 20L5A07TAU           | 1         | 2.44%   |
| Lenovo ThinkPad T470 20HES21434           | 1         | 2.44%   |
| Lenovo ThinkPad T470 20HES0E71M           | 1         | 2.44%   |
| Lenovo ThinkPad T430s 2355C33             | 1         | 2.44%   |
| Lenovo ThinkPad P70 20ESS04S00            | 1         | 2.44%   |
| Lenovo ThinkPad P50s 20FL000MUS           | 1         | 2.44%   |
| Lenovo ThinkPad L540 20AVCTO1WW           | 1         | 2.44%   |
| Lenovo ThinkPad L490 20Q5CTO1WW           | 1         | 2.44%   |
| Lenovo Legion 5 15IMH05 82AU              | 1         | 2.44%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS       | 1         | 2.44%   |
| Lenovo IdeaPad 300-15ISK 80RS             | 1         | 2.44%   |
| HP ZBook 15                               | 1         | 2.44%   |
| HP ProBook 445 G6                         | 1         | 2.44%   |
| HP Notebook                               | 1         | 2.44%   |
| HP Laptop 17-cp0xxx                       | 1         | 2.44%   |
| HP EliteBook 840 G5                       | 1         | 2.44%   |
| HP Compaq 6730b                           | 1         | 2.44%   |
| Google Lick                               | 1         | 2.44%   |
| Dynabook PORTEGE X40-G                    | 1         | 2.44%   |
| Dell Precision M4800                      | 1         | 2.44%   |
| Dell Precision M4600                      | 1         | 2.44%   |
| Dell Latitude E6420                       | 1         | 2.44%   |
| Dell Latitude 7430                        | 1         | 2.44%   |
| Dell Latitude 7420                        | 1         | 2.44%   |
| Dell Latitude 7410                        | 1         | 2.44%   |
| Dell Inspiron 5502                        | 1         | 2.44%   |
| Dell Inspiron 3542                        | 1         | 2.44%   |
| ASUS ZenBook UX425EA_UX425EA              | 1         | 2.44%   |
| ASUS UX305FA                              | 1         | 2.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 16        | 39.02%  |
| Dell Latitude          | 4         | 9.76%   |
| Lenovo IdeaPad         | 2         | 4.88%   |
| Dell Precision         | 2         | 4.88%   |
| Dell Inspiron          | 2         | 4.88%   |
| ASUS X510UR            | 2         | 4.88%   |
| Standard BW            | 1         | 2.44%   |
| Panasonic CF-53AAG54FM | 1         | 2.44%   |
| Lenovo Legion          | 1         | 2.44%   |
| HP ZBook               | 1         | 2.44%   |
| HP ProBook             | 1         | 2.44%   |
| HP Notebook            | 1         | 2.44%   |
| HP Laptop              | 1         | 2.44%   |
| HP EliteBook           | 1         | 2.44%   |
| HP Compaq              | 1         | 2.44%   |
| Google Lick            | 1         | 2.44%   |
| Dynabook PORTEGE       | 1         | 2.44%   |
| ASUS ZenBook           | 1         | 2.44%   |
| ASUS UX305FA           | 1         | 2.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 6         | 14.63%  |
| 2020 | 5         | 12.2%   |
| 2014 | 5         | 12.2%   |
| 2018 | 4         | 9.76%   |
| 2017 | 4         | 9.76%   |
| 2016 | 4         | 9.76%   |
| 2011 | 3         | 7.32%   |
| 2022 | 2         | 4.88%   |
| 2021 | 2         | 4.88%   |
| 2015 | 2         | 4.88%   |
| 2013 | 2         | 4.88%   |
| 2012 | 1         | 2.44%   |
| 2008 | 1         | 2.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 41        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 34        | 80.95%  |
| Enabled  | 8         | 19.05%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 40        | 97.56%  |
| Yes  | 1         | 2.44%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 13        | 30.95%  |
| 8.01-16.0   | 13        | 30.95%  |
| 4.01-8.0    | 6         | 14.29%  |
| 3.01-4.0    | 5         | 11.9%   |
| 16.01-24.0  | 4         | 9.52%   |
| 64.01-256.0 | 1         | 2.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 17        | 35.42%  |
| 2.01-3.0   | 12        | 25%     |
| 3.01-4.0   | 8         | 16.67%  |
| 8.01-16.0  | 7         | 14.58%  |
| 1.01-2.0   | 2         | 4.17%   |
| 24.01-32.0 | 1         | 2.08%   |
| 0.51-1.0   | 1         | 2.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 35        | 83.33%  |
| 2      | 5         | 11.9%   |
| 4      | 1         | 2.38%   |
| 3      | 1         | 2.38%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 32        | 78.05%  |
| Yes       | 9         | 21.95%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 33        | 80.49%  |
| No        | 8         | 19.51%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 97.56%  |
| No        | 1         | 2.44%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 27        | 64.29%  |
| No        | 15        | 35.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 15        | 35.71%  |
| Germany     | 4         | 9.52%   |
| UK          | 3         | 7.14%   |
| Netherlands | 3         | 7.14%   |
| Brazil      | 3         | 7.14%   |
| Poland      | 2         | 4.76%   |
| Australia   | 2         | 4.76%   |
| Yemen       | 1         | 2.38%   |
| Turkey      | 1         | 2.38%   |
| Romania     | 1         | 2.38%   |
| Pakistan    | 1         | 2.38%   |
| India       | 1         | 2.38%   |
| Hungary     | 1         | 2.38%   |
| Hong Kong   | 1         | 2.38%   |
| Finland     | 1         | 2.38%   |
| Bulgaria    | 1         | 2.38%   |
| Argentina   | 1         | 2.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| San Diego          | 3         | 6.52%   |
| Siegen             | 2         | 4.35%   |
| Seattle            | 2         | 4.35%   |
| Amsterdam          | 2         | 4.35%   |
| Utrecht            | 1         | 2.17%   |
| Sydney             | 1         | 2.17%   |
| Sofia              | 1         | 2.17%   |
| Shrewsbury         | 1         | 2.17%   |
| Sao Paulo          | 1         | 2.17%   |
| Sao Caetano do Sul | 1         | 2.17%   |
| Sanaa              | 1         | 2.17%   |
| Rocklin            | 1         | 2.17%   |
| Redwood City       | 1         | 2.17%   |
| Port Saint Lucie   | 1         | 2.17%   |
| Pleven             | 1         | 2.17%   |
| Ngau Wu Tok        | 1         | 2.17%   |
| Nagercoil          | 1         | 2.17%   |
| Maple Valley       | 1         | 2.17%   |
| Lynnwood           | 1         | 2.17%   |
| Ludwigsburg        | 1         | 2.17%   |
| London             | 1         | 2.17%   |
| Las Vegas          | 1         | 2.17%   |
| Katowice           | 1         | 2.17%   |
| Karachi            | 1         | 2.17%   |
| Helsinki           | 1         | 2.17%   |
| Greven             | 1         | 2.17%   |
| Fremont            | 1         | 2.17%   |
| Ercsi              | 1         | 2.17%   |
| Elko               | 1         | 2.17%   |
| Drochtersen        | 1         | 2.17%   |
| Dallas             | 1         | 2.17%   |
| Colorado Springs   | 1         | 2.17%   |
| Chicago            | 1         | 2.17%   |
| Castelar           | 1         | 2.17%   |
| Canberra           | 1         | 2.17%   |
| Campinas           | 1         | 2.17%   |
| Bydgoszcz          | 1         | 2.17%   |
| Bucharest          | 1         | 2.17%   |
| Bracknell          | 1         | 2.17%   |
| Berlin             | 1         | 2.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 16        | 21     | 32.65%  |
| SanDisk                 | 7         | 8      | 14.29%  |
| Unknown                 | 4         | 6      | 8.16%   |
| WDC                     | 3         | 3      | 6.12%   |
| Seagate                 | 3         | 3      | 6.12%   |
| HGST                    | 3         | 6      | 6.12%   |
| Micron Technology       | 2         | 5      | 4.08%   |
| Union Memory (Shenzhen) | 1         | 2      | 2.04%   |
| Toshiba                 | 1         | 1      | 2.04%   |
| Phison Electronics      | 1         | 1      | 2.04%   |
| Lite-On                 | 1         | 1      | 2.04%   |
| Lenovo                  | 1         | 1      | 2.04%   |
| KIOXIA                  | 1         | 1      | 2.04%   |
| Kingston                | 1         | 7      | 2.04%   |
| JMicron Technology      | 1         | 1      | 2.04%   |
| Intel                   | 1         | 1      | 2.04%   |
| Fujitsu                 | 1         | 1      | 2.04%   |
| Crucial                 | 1         | 2      | 2.04%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| SanDisk SSD PLUS 1000GB                      | 2         | 4%      |
| Samsung MZVLB512HAJQ-000L7 512GB             | 2         | 4%      |
| Samsung MZ7LN512HMJP-000L7 512GB SSD         | 2         | 4%      |
| WDC WDS250G2B0A-00SM50 250GB SSD             | 1         | 2%      |
| WDC WD10SPZX-60Z10T1 1TB                     | 1         | 2%      |
| WDC WD10JPCX-24UE4T0 1TB                     | 1         | 2%      |
| Unknown SD/MMC/MS PRO 250GB                  | 1         | 2%      |
| Unknown MMC64G  64GB                         | 1         | 2%      |
| Unknown MMC Card  256GB                      | 1         | 2%      |
| Unknown MMC Card  1TB                        | 1         | 2%      |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 2%      |
| Toshiba THNSNJ512GCSU 512GB SSD              | 1         | 2%      |
| Seagate ST9750420AS 752GB                    | 1         | 2%      |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 2%      |
| Seagate BUP Slim BK 1TB                      | 1         | 2%      |
| SanDisk SDSSDH3512G 512GB                    | 1         | 2%      |
| SanDisk SD7SN3Q256G1002 256GB SSD            | 1         | 2%      |
| SanDisk SD6SB1M-256G-1006 256GB SSD          | 1         | 2%      |
| Sandisk PC SN740 NVMe WD 512GB               | 1         | 2%      |
| SanDisk NVMe SSD Drive 512GB                 | 1         | 2%      |
| Samsung SSD SM841N 2.5 7mm 512GB             | 1         | 2%      |
| Samsung SSD PM830 2.5 7mm 256GB              | 1         | 2%      |
| Samsung SSD 850 PRO 256GB                    | 1         | 2%      |
| Samsung PM9A1 NVMe 512GB                     | 1         | 2%      |
| Samsung NVMe SSD Drive 512GB                 | 1         | 2%      |
| Samsung NVMe SSD Drive 1TB                   | 1         | 2%      |
| Samsung MZVLW256HEHP-000L7 256GB             | 1         | 2%      |
| Samsung MZVLB1T0HBLR-000L7 1TB               | 1         | 2%      |
| Samsung MZVLB1T0HALR-000H1 1TB               | 1         | 2%      |
| Samsung MZNLN512HCJH-000L1 512GB SSD         | 1         | 2%      |
| Samsung MZ7LN512HCHP-000L1 512GB SSD         | 1         | 2%      |
| Samsung MZ7LN256HCHP-000L7 256GB SSD         | 1         | 2%      |
| Phison E16 PCIe4 NVMe Controller 1TB         | 1         | 2%      |
| Micron NVMe SSD Drive 256GB                  | 1         | 2%      |
| Micron 2300_MTFDHBA256TDV 256GB              | 1         | 2%      |
| Micron 2200S NVMe 256GB                      | 1         | 2%      |
| Lite-On NVMe SSD Drive 512GB                 | 1         | 2%      |
| Lenovo LENSE30512GMSP34MEAT3TA 512GB         | 1         | 2%      |
| KIOXIA KBG40ZNV128G 128GB                    | 1         | 2%      |
| Kingston NVMe SSD Drive 1TB                  | 1         | 2%      |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 3         | 3      | 27.27%  |
| HGST               | 3         | 6      | 27.27%  |
| WDC                | 2         | 2      | 18.18%  |
| Unknown            | 1         | 3      | 9.09%   |
| JMicron Technology | 1         | 1      | 9.09%   |
| Fujitsu            | 1         | 1      | 9.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 11     | 50%     |
| SanDisk             | 5         | 5      | 31.25%  |
| WDC                 | 1         | 1      | 6.25%   |
| Toshiba             | 1         | 1      | 6.25%   |
| Crucial             | 1         | 2      | 6.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 19        | 32     | 39.58%  |
| SSD  | 16        | 20     | 33.33%  |
| HDD  | 10        | 16     | 20.83%  |
| MMC  | 3         | 3      | 6.25%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 23        | 31     | 48.94%  |
| NVMe | 19        | 32     | 40.43%  |
| MMC  | 3         | 3      | 6.38%   |
| SAS  | 2         | 5      | 4.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 15        | 22     | 57.69%  |
| 0.01-0.5   | 11        | 14     | 42.31%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 10        | 23.81%  |
| 101-250    | 8         | 19.05%  |
| 1-20       | 7         | 16.67%  |
| 501-1000   | 6         | 14.29%  |
| Unknown    | 6         | 14.29%  |
| 51-100     | 3         | 7.14%   |
| 2001-3000  | 2         | 4.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 16        | 36.36%  |
| 21-50     | 7         | 15.91%  |
| 51-100    | 6         | 13.64%  |
| Unknown   | 6         | 13.64%  |
| 251-500   | 4         | 9.09%   |
| 101-250   | 2         | 4.55%   |
| 501-1000  | 2         | 4.55%   |
| 1001-2000 | 1         | 2.27%   |

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
| Detected | 23        | 41     | 51.11%  |
| Works    | 20        | 28     | 44.44%  |
| Malfunc  | 2         | 2      | 4.44%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 21        | 48.84%  |
| Samsung Electronics         | 8         | 18.6%   |
| AMD                         | 4         | 9.3%    |
| SanDisk                     | 2         | 4.65%   |
| Micron Technology           | 2         | 4.65%   |
| Union Memory (Shenzhen)     | 1         | 2.33%   |
| Phison Electronics          | 1         | 2.33%   |
| Lite-On Technology          | 1         | 2.33%   |
| Lenovo                      | 1         | 2.33%   |
| KIOXIA                      | 1         | 2.33%   |
| Kingston Technology Company | 1         | 2.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 6         | 13.64%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 4         | 9.09%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 4         | 9.09%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 6.82%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 3         | 6.82%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 6.82%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 2.27%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 2.27%   |
| Sandisk PC SN740 NVMe SSD                                                        | 1         | 2.27%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 2.27%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 2.27%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 2.27%   |
| Micron NVMe Storage Controller                                                   | 1         | 2.27%   |
| Micron 2200S NVMe SSD                                                            | 1         | 2.27%   |
| Lite-On Non-Volatile memory controller                                           | 1         | 2.27%   |
| Lenovo Non-Volatile memory controller                                            | 1         | 2.27%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 1         | 2.27%   |
| Kingston Company A2000 NVMe SSD                                                  | 1         | 2.27%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 2.27%   |
| Intel SSD 660P Series                                                            | 1         | 2.27%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 2.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 2.27%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1         | 2.27%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 2.27%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 1         | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 1         | 2.27%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 1         | 2.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 21        | 47.73%  |
| NVMe | 19        | 43.18%  |
| RAID | 4         | 9.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 37        | 90.24%  |
| AMD    | 4         | 9.76%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-8665U CPU @ 1.90GHz               | 2         | 4.88%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 2         | 4.88%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 2         | 4.88%   |
| Intel Core i7-10610U CPU @ 1.80GHz              | 2         | 4.88%   |
| Intel Core i5-8350U CPU @ 1.70GHz               | 2         | 4.88%   |
| Intel Core i5-7300U CPU @ 2.60GHz               | 2         | 4.88%   |
| Intel Core i5-5300U CPU @ 2.30GHz               | 2         | 4.88%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 2         | 4.88%   |
| Intel Processor 5Y10 CPU @ 0.80GHz              | 1         | 2.44%   |
| Intel Core i9-9880H CPU @ 2.30GHz               | 1         | 2.44%   |
| Intel Core i7-8650U CPU @ 1.90GHz               | 1         | 2.44%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 1         | 2.44%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz              | 1         | 2.44%   |
| Intel Core i7-4940MX CPU @ 3.10GHz              | 1         | 2.44%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz              | 1         | 2.44%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz              | 1         | 2.44%   |
| Intel Core i7-2860QM CPU @ 2.50GHz              | 1         | 2.44%   |
| Intel Core i7-2760QM CPU @ 2.40GHz              | 1         | 2.44%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 1         | 2.44%   |
| Intel Core i5-8365U CPU @ 1.60GHz               | 1         | 2.44%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 1         | 2.44%   |
| Intel Core i5-4210M CPU @ 2.60GHz               | 1         | 2.44%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 1         | 2.44%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 1         | 2.44%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz            | 1         | 2.44%   |
| Intel Celeron N4020 CPU @ 1.10GHz               | 1         | 2.44%   |
| Intel Celeron CPU N3010 @ 1.04GHz               | 1         | 2.44%   |
| Intel 12th Gen Core i7-1270P                    | 1         | 2.44%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz         | 1         | 2.44%   |
| AMD Ryzen 7 PRO 2700U w/ Radeon Vega Mobile Gfx | 1         | 2.44%   |
| AMD Ryzen 7 5700U with Radeon Graphics          | 1         | 2.44%   |
| AMD A9-9420e RADEON R5, 5 COMPUTE CORES 2C+3G   | 1         | 2.44%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics     | 1         | 2.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 17        | 41.46%  |
| Intel Core i5    | 11        | 26.83%  |
| Other            | 6         | 14.63%  |
| Intel Celeron    | 2         | 4.88%   |
| Intel Core i9    | 1         | 2.44%   |
| Intel Core 2 Duo | 1         | 2.44%   |
| AMD Ryzen 7 PRO  | 1         | 2.44%   |
| AMD Ryzen 7      | 1         | 2.44%   |
| AMD A8           | 1         | 2.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 19        | 46.34%  |
| 2      | 17        | 41.46%  |
| 8      | 2         | 4.88%   |
| 12     | 1         | 2.44%   |
| 6      | 1         | 2.44%   |
| 1      | 1         | 2.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 41        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 35        | 85.37%  |
| 1      | 6         | 14.63%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 40        | 95.24%  |
| Unknown        | 2         | 4.76%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ec    | 5         | 12.2%   |
| 0x806ea    | 4         | 9.76%   |
| 0x306c3    | 4         | 9.76%   |
| 0x806c1    | 3         | 7.32%   |
| 0x306d4    | 3         | 7.32%   |
| 0x206a7    | 3         | 7.32%   |
| 0x806e9    | 2         | 4.88%   |
| 0x406e3    | 2         | 4.88%   |
| Unknown    | 2         | 4.88%   |
| 0xa0652    | 1         | 2.44%   |
| 0x906ed    | 1         | 2.44%   |
| 0x906a3    | 1         | 2.44%   |
| 0x706a8    | 1         | 2.44%   |
| 0x506e3    | 1         | 2.44%   |
| 0x406c4    | 1         | 2.44%   |
| 0x40651    | 1         | 2.44%   |
| 0x306a9    | 1         | 2.44%   |
| 0x10676    | 1         | 2.44%   |
| 0x08608103 | 1         | 2.44%   |
| 0x0810100b | 1         | 2.44%   |
| 0x07030105 | 1         | 2.44%   |
| 0x06006705 | 1         | 2.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 14        | 34.15%  |
| Haswell          | 5         | 12.2%   |
| TigerLake        | 3         | 7.32%   |
| Skylake          | 3         | 7.32%   |
| SandyBridge      | 3         | 7.32%   |
| Broadwell        | 3         | 7.32%   |
| Zen              | 1         | 2.44%   |
| Silvermont       | 1         | 2.44%   |
| Puma             | 1         | 2.44%   |
| Penryn           | 1         | 2.44%   |
| IvyBridge        | 1         | 2.44%   |
| Goldmont plus    | 1         | 2.44%   |
| Excavator        | 1         | 2.44%   |
| CometLake        | 1         | 2.44%   |
| Alderlake Hybrid | 1         | 2.44%   |
| Unknown          | 1         | 2.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 33        | 62.26%  |
| Nvidia | 12        | 22.64%  |
| AMD    | 8         | 15.09%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 4         | 7.55%   |
| Intel HD Graphics 620                                                                    | 4         | 7.55%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 7.55%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 5.66%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 5.66%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 3.77%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 3.77%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 3.77%   |
| Intel HD Graphics 5500                                                                   | 2         | 3.77%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 3.77%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.89%   |
| Nvidia TU117M                                                                            | 1         | 1.89%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 1.89%   |
| Nvidia GM204GLM [Quadro M4000M]                                                          | 1         | 1.89%   |
| Nvidia GM108GLM [Quadro K620M / Quadro M500M]                                            | 1         | 1.89%   |
| Nvidia GK208GLM [Quadro K610M]                                                           | 1         | 1.89%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 1.89%   |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 1.89%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.89%   |
| Intel HD Graphics 5300                                                                   | 1         | 1.89%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1.89%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.89%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.89%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 1         | 1.89%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 1.89%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1         | 1.89%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 1         | 1.89%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                                          | 1         | 1.89%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 1.89%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 1.89%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 1.89%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 1.89%   |
| AMD Lucienne                                                                             | 1         | 1.89%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 1         | 1.89%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 20        | 47.62%  |
| Intel + Nvidia | 9         | 21.43%  |
| 1 x AMD        | 5         | 11.9%   |
| 1 x Nvidia     | 4         | 9.52%   |
| Intel + AMD    | 3         | 7.14%   |
| Other          | 1         | 2.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 37        | 86.05%  |
| Proprietary | 3         | 6.98%   |
| Unknown     | 3         | 6.98%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 50%     |
| 1.01-2.0   | 10        | 23.81%  |
| 3.01-4.0   | 5         | 11.9%   |
| 0.51-1.0   | 3         | 7.14%   |
| 0.01-0.5   | 3         | 7.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 12        | 20%     |
| LG Display           | 9         | 15%     |
| Chimei Innolux       | 7         | 11.67%  |
| Samsung Electronics  | 6         | 10%     |
| BOE                  | 5         | 8.33%   |
| Lenovo               | 4         | 6.67%   |
| Dell                 | 4         | 6.67%   |
| ViewSonic            | 3         | 5%      |
| InfoVision           | 3         | 5%      |
| BenQ                 | 2         | 3.33%   |
| Acer                 | 2         | 3.33%   |
| BOE Technology Group | 1         | 1.67%   |
| ASUSTek Computer     | 1         | 1.67%   |
| Ancor Communications | 1         | 1.67%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 2         | 3.17%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 2         | 3.17%   |
| Dell U2718Q DELA0E9 3840x2160 609x349mm 27.6-inch                     | 2         | 3.17%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 2         | 3.17%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 3.17%   |
| BenQ GL2760 BNQ78D5 1920x1080 598x336mm 27.0-inch                     | 2         | 3.17%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch         | 2         | 3.17%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 2         | 3.17%   |
| Acer SA230 ACR057E 1920x1080 509x286mm 23.0-inch                      | 2         | 3.17%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch         | 1         | 1.59%   |
| ViewSonic VX2433wm VSC3822 1920x1080 520x290mm 23.4-inch              | 1         | 1.59%   |
| ViewSonic VG2439 Series VSCD22B 1920x1080 521x293mm 23.5-inch         | 1         | 1.59%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 433x271mm 20.1-inch  | 1         | 1.59%   |
| Samsung Electronics SAMTRON STN0022 1280x1024 376x301mm 19.0-inch     | 1         | 1.59%   |
| Samsung Electronics S27H65x SAM0E1D 1920x1080 598x336mm 27.0-inch     | 1         | 1.59%   |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch     | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SDC3256 1920x1080 382x215mm 17.3-inch | 1         | 1.59%   |
| Samsung Electronics C32HG7x SAM0E14 2560x1440 697x392mm 31.5-inch     | 1         | 1.59%   |
| LG Display LCD Monitor LGD0628 1920x1080 309x174mm 14.0-inch          | 1         | 1.59%   |
| LG Display LCD Monitor LGD0609 1920x1080 309x174mm 14.0-inch          | 1         | 1.59%   |
| LG Display LCD Monitor LGD04BD 1366x768 344x194mm 15.5-inch           | 1         | 1.59%   |
| LG Display LCD Monitor LGD047C 1366x768 310x174mm 14.0-inch           | 1         | 1.59%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 1         | 1.59%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch           | 1         | 1.59%   |
| LG Display LCD Monitor LGD02D9 1920x1080 345x194mm 15.6-inch          | 1         | 1.59%   |
| Lenovo T24i-10 LEN61A6 1920x1080 527x296mm 23.8-inch                  | 1         | 1.59%   |
| Lenovo LEN T2424pA LEN60C8 1920x1080 527x296mm 23.8-inch              | 1         | 1.59%   |
| Lenovo LEN T2254pC LEN60CC 1680x1050 474x296mm 22.0-inch              | 1         | 1.59%   |
| Lenovo LEN P27u-10 LEN61B0 3840x2160 600x340mm 27.2-inch              | 1         | 1.59%   |
| InfoVision LCD Monitor IVO048E 1366x768 256x144mm 11.6-inch           | 1         | 1.59%   |
| Dell S3221QSA DELD105 3840x2160 697x392mm 31.5-inch                   | 1         | 1.59%   |
| Dell P2722H DEL4240 1920x1080 598x336mm 27.0-inch                     | 1         | 1.59%   |
| Dell P2719H DEL4184 1920x1080 598x336mm 27.0-inch                     | 1         | 1.59%   |
| Dell P2414H DELA09C 1920x1080 527x297mm 23.8-inch                     | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN14E8 1920x1080 309x173mm 13.9-inch      | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 1         | 1.59%   |
| BOE Technology Group LCD Monitor 1920x1080                            | 1         | 1.59%   |
| BOE LCD Monitor BOE0953 1920x1080 382x215mm 17.3-inch                 | 1         | 1.59%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 31        | 64.58%  |
| 1366x768 (WXGA)    | 5         | 10.42%  |
| 1600x900 (HD+)     | 4         | 8.33%   |
| 3840x2160 (4K)     | 3         | 6.25%   |
| 1680x1050 (WSXGA+) | 2         | 4.17%   |
| 2560x1440 (QHD)    | 1         | 2.08%   |
| 1280x800 (WXGA)    | 1         | 2.08%   |
| 1280x1024 (SXGA)   | 1         | 2.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 15        | 24.59%  |
| 14      | 12        | 19.67%  |
| 27      | 8         | 13.11%  |
| 13      | 7         | 11.48%  |
| 24      | 4         | 6.56%   |
| 23      | 3         | 4.92%   |
| 38      | 2         | 3.28%   |
| 31      | 2         | 3.28%   |
| 17      | 2         | 3.28%   |
| 22      | 1         | 1.64%   |
| 20      | 1         | 1.64%   |
| 19      | 1         | 1.64%   |
| 12      | 1         | 1.64%   |
| 11      | 1         | 1.64%   |
| Unknown | 1         | 1.64%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 33        | 55.93%  |
| 501-600     | 14        | 23.73%  |
| 201-300     | 3         | 5.08%   |
| 801-900     | 2         | 3.39%   |
| 601-700     | 2         | 3.39%   |
| 401-500     | 2         | 3.39%   |
| 351-400     | 2         | 3.39%   |
| Unknown     | 1         | 1.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 39        | 88.64%  |
| 16/10   | 3         | 6.82%   |
| 5/4     | 1         | 2.27%   |
| Unknown | 1         | 2.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 18        | 30%     |
| 101-110        | 15        | 25%     |
| 301-350        | 8         | 13.33%  |
| 201-250        | 7         | 11.67%  |
| 351-500        | 2         | 3.33%   |
| 151-200        | 2         | 3.33%   |
| 121-130        | 2         | 3.33%   |
| 501-1000       | 2         | 3.33%   |
| 71-80          | 1         | 1.67%   |
| 61-70          | 1         | 1.67%   |
| 51-60          | 1         | 1.67%   |
| Unknown        | 1         | 1.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 31        | 56.36%  |
| 51-100  | 14        | 25.45%  |
| 101-120 | 6         | 10.91%  |
| 161-240 | 3         | 5.45%   |
| Unknown | 1         | 1.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 23        | 54.76%  |
| 2     | 10        | 23.81%  |
| 3     | 5         | 11.9%   |
| 0     | 3         | 7.14%   |
| 4     | 1         | 2.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 34        | 57.63%  |
| Realtek Semiconductor | 13        | 22.03%  |
| Qualcomm Atheros      | 3         | 5.08%   |
| Lenovo                | 3         | 5.08%   |
| Ralink Technology     | 1         | 1.69%   |
| NetGear               | 1         | 1.69%   |
| Fibocom               | 1         | 1.69%   |
| Broadcom Limited      | 1         | 1.69%   |
| Broadcom              | 1         | 1.69%   |
| ASIX Electronics      | 1         | 1.69%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                        | 8         | 9.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 6.1%    |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 6.1%    |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4         | 4.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 4.88%   |
| Intel Wireless 7265                                               | 3         | 3.66%   |
| Intel Wireless 7260                                               | 3         | 3.66%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 3.66%   |
| Intel Ethernet Connection (6) I219-LM                             | 3         | 3.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 3.66%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 2.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 2.44%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 2         | 2.44%   |
| Intel Wireless 8260                                               | 2         | 2.44%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 2.44%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 2.44%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 2.44%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 2.44%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 1.22%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 1.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.22%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 1.22%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 1.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.22%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                   | 1         | 1.22%   |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 1.22%   |
| Intel Wireless-AC 9260                                            | 1         | 1.22%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 1.22%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 1.22%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 1         | 1.22%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 1         | 1.22%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.22%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.22%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.22%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.22%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.22%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.22%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 1.22%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 1         | 1.22%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                 | 1         | 1.22%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 33        | 75%     |
| Realtek Semiconductor | 4         | 9.09%   |
| Qualcomm Atheros      | 3         | 6.82%   |
| Ralink Technology     | 1         | 2.27%   |
| NetGear               | 1         | 2.27%   |
| Fibocom               | 1         | 2.27%   |
| Broadcom              | 1         | 2.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                 | 8         | 18.18%  |
| Intel Wireless 7265                                        | 3         | 6.82%   |
| Intel Wireless 7260                                        | 3         | 6.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]               | 3         | 6.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 2         | 4.55%   |
| Intel Wireless 8260                                        | 2         | 4.55%   |
| Intel Wi-Fi 6 AX201                                        | 2         | 4.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 2         | 4.55%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                   | 2         | 4.55%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 1         | 2.27%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1         | 2.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1         | 2.27%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 1         | 2.27%   |
| Ralink MT7601U Wireless Adapter                            | 1         | 2.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1         | 2.27%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]            | 1         | 2.27%   |
| Intel Wireless-AC 9260                                     | 1         | 2.27%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 1         | 2.27%   |
| Intel Wi-Fi 6 AX200                                        | 1         | 2.27%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection    | 1         | 2.27%   |
| Intel Gemini Lake PCH CNVi WiFi                            | 1         | 2.27%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1         | 2.27%   |
| Intel Centrino Ultimate-N 6300                             | 1         | 2.27%   |
| Intel Alder Lake-P PCH CNVi WiFi                           | 1         | 2.27%   |
| Fibocom L830-EB-00 LTE WWAN Modem                          | 1         | 2.27%   |
| Broadcom BCM43142 802.11b/g/n                              | 1         | 2.27%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 22        | 57.89%  |
| Realtek Semiconductor | 11        | 28.95%  |
| Lenovo                | 3         | 7.89%   |
| Broadcom Limited      | 1         | 2.63%   |
| ASIX Electronics      | 1         | 2.63%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 13.16%  |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 13.16%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4         | 10.53%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 10.53%  |
| Intel Ethernet Connection I217-LM                                 | 3         | 7.89%   |
| Intel Ethernet Connection (6) I219-LM                             | 3         | 7.89%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 5.26%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 2         | 5.26%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 5.26%   |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 2.63%   |
| Intel Ethernet Connection I219-V                                  | 1         | 2.63%   |
| Intel Ethernet Connection I217-V                                  | 1         | 2.63%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 2.63%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 2.63%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.63%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 1         | 2.63%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 2.63%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 40        | 54.79%  |
| Ethernet | 33        | 45.21%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 28        | 63.64%  |
| Ethernet | 16        | 36.36%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 28        | 68.29%  |
| 1     | 13        | 31.71%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 33        | 73.33%  |
| Yes  | 12        | 26.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 19        | 70.37%  |
| Qualcomm Atheros Communications | 3         | 11.11%  |
| Realtek Semiconductor           | 2         | 7.41%   |
| Broadcom                        | 2         | 7.41%   |
| Alps Electric                   | 1         | 3.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 10        | 37.04%  |
| Intel AX201 Bluetooth                          | 4         | 14.81%  |
| Qualcomm Atheros  Bluetooth Device             | 2         | 7.41%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 2         | 7.41%   |
| Realtek  Bluetooth 4.2 Adapter                 | 1         | 3.7%    |
| Realtek Bluetooth Radio                        | 1         | 3.7%    |
| Qualcomm Atheros AR9462 Bluetooth              | 1         | 3.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 1         | 3.7%    |
| Intel Bluetooth Device                         | 1         | 3.7%    |
| Intel AX210 Bluetooth                          | 1         | 3.7%    |
| Broadcom BCM43142A0 Bluetooth 4.0              | 1         | 3.7%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 1         | 3.7%    |
| Alps Electric UGTZ4 Bluetooth                  | 1         | 3.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 37        | 61.67%  |
| Nvidia              | 6         | 10%     |
| AMD                 | 6         | 10%     |
| Lenovo              | 4         | 6.67%   |
| GN Netcom           | 4         | 6.67%   |
| Unknown             | 1         | 1.67%   |
| TEAC                | 1         | 1.67%   |
| C-Media Electronics | 1         | 1.67%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 14.08%  |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 5.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 4.23%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 4.23%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 4.23%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 4.23%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 4.23%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 4.23%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 2.82%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 2         | 2.82%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 2.82%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 2.82%   |
| Unknown Definitive Sym1                                                                           | 1         | 1.41%   |
| TEAC US-2x2                                                                                       | 1         | 1.41%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 1.41%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 1.41%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 1.41%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 1.41%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                                          | 1         | 1.41%   |
| Lenovo ThinkPad Dock USB Audio                                                                    | 1         | 1.41%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1.41%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.41%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.41%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.41%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 1.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 1.41%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 1.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1         | 1.41%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.41%   |
| GN Netcom Jabra SPEAK 510                                                                         | 1         | 1.41%   |
| GN Netcom Jabra PRO 9460                                                                          | 1         | 1.41%   |
| GN Netcom Jabra Link 370                                                                          | 1         | 1.41%   |
| GN Netcom Jabra EVOLVE LINK                                                                       | 1         | 1.41%   |
| C-Media Electronics Blue Snowball                                                                 | 1         | 1.41%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 1.41%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.41%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.41%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 1.41%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 30.77%  |
| SK hynix            | 5         | 19.23%  |
| Micron Technology   | 5         | 19.23%  |
| Unknown             | 2         | 7.69%   |
| Kingston            | 2         | 7.69%   |
| Corsair             | 1         | 3.85%   |
| Avant               | 1         | 3.85%   |
| 4ea5                | 1         | 3.85%   |
| Unknown             | 1         | 3.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 3         | 11.11%  |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                  | 1         | 3.7%    |
| Unknown RAM Module 32GB SODIMM DDR4 2667MT/s                 | 1         | 3.7%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 3.7%    |
| SK hynix RAM HMAA1GS6CMR8N-VK 8GB Row Of Chips DDR4 2667MT/s | 1         | 3.7%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s | 1         | 3.7%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s    | 1         | 3.7%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 1         | 3.7%    |
| SK hynix RAM H9HCNNNBKUMLXR-NEE 2GB LPDDR4 2400MT/s          | 1         | 3.7%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 3.7%    |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s       | 1         | 3.7%    |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s       | 1         | 3.7%    |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s       | 1         | 3.7%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 1         | 3.7%    |
| Micron RAM Module 16384MB SODIMM DDR4 2400MT/s               | 1         | 3.7%    |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s  | 1         | 3.7%    |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s         | 1         | 3.7%    |
| Micron RAM 16JTF1G64HZ-1G4D1 8GB SODIMM DDR3 1333MT/s        | 1         | 3.7%    |
| Micron RAM 16ATF2G64HZ-2G1A1 16GB SODIMM DDR4 2133MT/s       | 1         | 3.7%    |
| Kingston RAM KX830D-ELC 4GB SODIMM DDR3 1333MT/s             | 1         | 3.7%    |
| Kingston RAM KN2M64-ETB 8GB SODIMM DDR3 1600MT/s             | 1         | 3.7%    |
| Corsair RAM CMSX32GX4M2A2666C18 16GB SODIMM DDR4 2667MT/s    | 1         | 3.7%    |
| Avant RAM H6451U66G1600G 4096MB SODIMM DDR3 1600MT/s         | 1         | 3.7%    |
| 4ea5 RAM H9HCNNNBKUMLXR-NEE 2GB LPDDR4 2400MT/s              | 1         | 3.7%    |
| Unknown                                                      | 1         | 3.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 12        | 50%     |
| DDR3   | 9         | 37.5%   |
| LPDDR4 | 2         | 8.33%   |
| LPDDR5 | 1         | 4.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 19        | 79.17%  |
| Row Of Chips | 4         | 16.67%  |
| Unknown      | 1         | 4.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 11        | 44%     |
| 4096  | 6         | 24%     |
| 16384 | 5         | 20%     |
| 32768 | 2         | 8%      |
| 2048  | 1         | 4%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 7         | 29.17%  |
| 1600  | 7         | 29.17%  |
| 2400  | 3         | 12.5%   |
| 1333  | 2         | 8.33%   |
| 6400  | 1         | 4.17%   |
| 4267  | 1         | 4.17%   |
| 3200  | 1         | 4.17%   |
| 2133  | 1         | 4.17%   |
| 1866  | 1         | 4.17%   |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 9         | 27.27%  |
| IMC Networks                           | 5         | 15.15%  |
| Realtek Semiconductor                  | 4         | 12.12%  |
| Logitech                               | 4         | 12.12%  |
| Suyin                                  | 3         | 9.09%   |
| Lite-On Technology                     | 3         | 9.09%   |
| Bison Electronics                      | 2         | 6.06%   |
| Microdia                               | 1         | 3.03%   |
| Luxvisions Innotech Limited            | 1         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 5         | 14.71%  |
| Realtek Integrated_Webcam_HD                                    | 2         | 5.88%   |
| Lite-On Integrated Camera                                       | 2         | 5.88%   |
| IMC Networks VGA UVC WebCam                                     | 2         | 5.88%   |
| IMC Networks Integrated Camera                                  | 2         | 5.88%   |
| Chicony Integrated Camera (1280x720@30)                         | 2         | 5.88%   |
| Bison SunplusIT Integrated Camera                               | 2         | 5.88%   |
| Suyin Integrated_Webcam_HD                                      | 1         | 2.94%   |
| Suyin HP Truevision HD                                          | 1         | 2.94%   |
| Suyin Asus Integrated Webcam                                    | 1         | 2.94%   |
| Realtek Integrated_Webcam_FHD                                   | 1         | 2.94%   |
| Realtek EasyCamera                                              | 1         | 2.94%   |
| Microdia Webcam Vitade AF                                       | 1         | 2.94%   |
| Luxvisions Innotech Limited EasyCamera 1M                       | 1         | 2.94%   |
| Logitech Webcam C925e                                           | 1         | 2.94%   |
| Logitech Webcam C920-C                                          | 1         | 2.94%   |
| Logitech HD Webcam C615                                         | 1         | 2.94%   |
| Logitech BRIO Ultra HD Webcam                                   | 1         | 2.94%   |
| Lite-On HP HD Camera                                            | 1         | 2.94%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 1         | 2.94%   |
| Chicony TOSHIBA Web Camera - HD                                 | 1         | 2.94%   |
| Chicony ThinkPad T490 Webcam                                    | 1         | 2.94%   |
| Chicony Integrated IR Camera                                    | 1         | 2.94%   |
| Cheng Uei Precision Industry (Foxlink) HP True Vision HD Camera | 1         | 2.94%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 8         | 50%     |
| Synaptics        | 7         | 43.75%  |
| Upek             | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 18.75%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 18.75%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 18.75%  |
| Validity Sensors Synaptics WBDI                                            | 2         | 12.5%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 12.5%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 6.25%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 6.25%   |
| Synaptics WBDI                                                             | 1         | 6.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 6         | 75%     |
| Alcor Micro | 2         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 3         | 37.5%   |
| Broadcom 58200                                 | 3         | 37.5%   |
| Alcor Micro AU9540 Smartcard Reader            | 2         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 21        | 48.84%  |
| 0     | 16        | 37.21%  |
| 2     | 5         | 11.63%  |
| 3     | 1         | 2.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 16        | 50%     |
| Chipcard           | 6         | 18.75%  |
| Graphics card      | 4         | 12.5%   |
| Storage            | 2         | 6.25%   |
| Net/wireless       | 2         | 6.25%   |
| Card reader        | 1         | 3.13%   |
| Bluetooth          | 1         | 3.13%   |

