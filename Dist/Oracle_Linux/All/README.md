Oracle Linux - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Oracle Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Oracle_Linux/Desktop/README.md) and [notebooks](/Dist/Oracle_Linux/Notebook/README.md).

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

Total: 67

| Vendor   | Model                       | Form-Factor | Probe                                                      | Date         |
|----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI      | Z77A-G43                    | Desktop     | [909e3e3c2e](https://linux-hardware.org/?probe=909e3e3c2e) | Jun 29, 2022 |
| ASUSTek  | P8H67                       | Desktop     | [b194dad4cf](https://linux-hardware.org/?probe=b194dad4cf) | Jun 25, 2022 |
| Lenovo   | ThinkPad P70 20ESS04S00     | Notebook    | [fc29967bed](https://linux-hardware.org/?probe=fc29967bed) | Jun 17, 2022 |
| HP       | Compaq 6730b                | Notebook    | [dd94c9145b](https://linux-hardware.org/?probe=dd94c9145b) | Jun 11, 2022 |
| Lenovo   | ThinkPad T410 2518A37       | Notebook    | [04e81b8b3f](https://linux-hardware.org/?probe=04e81b8b3f) | Jun 04, 2022 |
| Lenovo   | ThinkPad T430s 2355C33      | Notebook    | [33de2bbd12](https://linux-hardware.org/?probe=33de2bbd12) | May 31, 2022 |
| Lenovo   | ThinkPad T430s 2355C33      | Notebook    | [4eab57bebf](https://linux-hardware.org/?probe=4eab57bebf) | May 30, 2022 |
| Dell     | Precision M4600             | Notebook    | [0ac2adfe5a](https://linux-hardware.org/?probe=0ac2adfe5a) | Apr 21, 2022 |
| Dell     | Precision M4800             | Notebook    | [fb13b19803](https://linux-hardware.org/?probe=fb13b19803) | Apr 21, 2022 |
| Lenovo   | ThinkPad P50s 20FL000MUS    | Notebook    | [99fbb4446c](https://linux-hardware.org/?probe=99fbb4446c) | Apr 16, 2022 |
| Dell     | 0C522T A03                  | Desktop     | [3dc84dc8ff](https://linux-hardware.org/?probe=3dc84dc8ff) | Mar 24, 2022 |
| Lenovo   | ThinkPad X1 Extreme 2nd ... | Notebook    | [b708e920f3](https://linux-hardware.org/?probe=b708e920f3) | Mar 21, 2022 |
| Lenovo   | ThinkPad T450 20BUS14900    | Notebook    | [bd60aae97a](https://linux-hardware.org/?probe=bd60aae97a) | Mar 11, 2022 |
| Lenovo   | ThinkPad T480 20L5A07TAU    | Notebook    | [755854f7d4](https://linux-hardware.org/?probe=755854f7d4) | Mar 11, 2022 |
| Lenovo   | ThinkPad X280 20KES4H34G    | Notebook    | [2b8a4f4664](https://linux-hardware.org/?probe=2b8a4f4664) | Mar 10, 2022 |
| Dell     | Latitude 7420               | Notebook    | [af5f1055fe](https://linux-hardware.org/?probe=af5f1055fe) | Mar 10, 2022 |
| HP       | ProBook 445 G6              | Notebook    | [88d8b32328](https://linux-hardware.org/?probe=88d8b32328) | Jan 26, 2022 |
| Lenovo   | ThinkPad X390 Yoga 20NQS... | Convertible | [8219e32fef](https://linux-hardware.org/?probe=8219e32fef) | Dec 22, 2021 |
| Lenovo   | ThinkPad T450 20BUS14900    | Notebook    | [44c8e11f02](https://linux-hardware.org/?probe=44c8e11f02) | Dec 22, 2021 |
| Lenovo   | IdeaPad 300-15ISK 80RS      | Notebook    | [1c9ca21f4e](https://linux-hardware.org/?probe=1c9ca21f4e) | Dec 10, 2021 |
| Dell     | Latitude 7410               | Notebook    | [3efa87284e](https://linux-hardware.org/?probe=3efa87284e) | Nov 18, 2021 |
| Dell     | Latitude E6420              | Notebook    | [b809392380](https://linux-hardware.org/?probe=b809392380) | Oct 08, 2021 |
| Lenovo   | IdeaPad C340-14IWL 81RL     | Convertible | [cf3c570b7a](https://linux-hardware.org/?probe=cf3c570b7a) | Sep 27, 2021 |
| Dell     | Latitude 7410               | Notebook    | [8f1a1a4798](https://linux-hardware.org/?probe=8f1a1a4798) | Sep 06, 2021 |
| Dell     | Latitude 7410               | Notebook    | [b03a0e0152](https://linux-hardware.org/?probe=b03a0e0152) | Sep 06, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | Notebook    | [7b393c5790](https://linux-hardware.org/?probe=7b393c5790) | Aug 21, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | Notebook    | [394c99adc8](https://linux-hardware.org/?probe=394c99adc8) | Aug 19, 2021 |
| Dell     | Inspiron 3542               | Notebook    | [0909599e9c](https://linux-hardware.org/?probe=0909599e9c) | Aug 11, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | Notebook    | [ba7afba1a6](https://linux-hardware.org/?probe=ba7afba1a6) | Jul 08, 2021 |
| Lenovo   | ThinkPad L490 20Q5CTO1WW    | Notebook    | [0225c17d79](https://linux-hardware.org/?probe=0225c17d79) | Jul 02, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | Notebook    | [505b82b2de](https://linux-hardware.org/?probe=505b82b2de) | Jun 06, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | Notebook    | [75b2ef5126](https://linux-hardware.org/?probe=75b2ef5126) | May 13, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | Notebook    | [734a4fbc56](https://linux-hardware.org/?probe=734a4fbc56) | May 09, 2021 |
| Gigabyte | Z490 AORUS ELITE AC         | Desktop     | [978ae6f2cb](https://linux-hardware.org/?probe=978ae6f2cb) | May 02, 2021 |
| ASUSTek  | UX305FA                     | Notebook    | [0bf50fba2d](https://linux-hardware.org/?probe=0bf50fba2d) | Mar 15, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | Notebook    | [ff355a9bb1](https://linux-hardware.org/?probe=ff355a9bb1) | Mar 11, 2021 |
| Gigabyte | X99-Designare EX-CF         | Desktop     | [5195396549](https://linux-hardware.org/?probe=5195396549) | Mar 06, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | Notebook    | [9f67379954](https://linux-hardware.org/?probe=9f67379954) | Mar 04, 2021 |
| Lenovo   | ThinkPad L490 20Q5CTO1WW    | Notebook    | [db0f24aee5](https://linux-hardware.org/?probe=db0f24aee5) | Mar 01, 2021 |
| Dell     | Latitude 7410               | Notebook    | [5b725b01aa](https://linux-hardware.org/?probe=5b725b01aa) | Feb 26, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | Notebook    | [835e8cad03](https://linux-hardware.org/?probe=835e8cad03) | Feb 25, 2021 |
| Dell     | Latitude 7410               | Notebook    | [430ac9fa0c](https://linux-hardware.org/?probe=430ac9fa0c) | Feb 24, 2021 |
| Lenovo   | ThinkPad T490 20N3S77600    | Notebook    | [26e61c39f2](https://linux-hardware.org/?probe=26e61c39f2) | Feb 24, 2021 |
| Dell     | Latitude 7410               | Notebook    | [7aeb2cc674](https://linux-hardware.org/?probe=7aeb2cc674) | Feb 22, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | Notebook    | [8af2c8d83c](https://linux-hardware.org/?probe=8af2c8d83c) | Feb 05, 2021 |
| ASUSTek  | G11CD                       | Desktop     | [13961e12a8](https://linux-hardware.org/?probe=13961e12a8) | Feb 01, 2021 |
| HP       | 158B                        | Desktop     | [5e6b9531d7](https://linux-hardware.org/?probe=5e6b9531d7) | Feb 01, 2021 |
| Dell     | PowerEdge FC630             | Desktop     | [bcd33a41f0](https://linux-hardware.org/?probe=bcd33a41f0) | Jan 25, 2021 |
| Gigabyte | X470 AORUS ULTRA GAMING-... | Desktop     | [71628a95b6](https://linux-hardware.org/?probe=71628a95b6) | Jan 13, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | Notebook    | [7ea3c87bfe](https://linux-hardware.org/?probe=7ea3c87bfe) | Jan 06, 2021 |
| Foxconn  | 2ADA                        | Desktop     | [809e03aea5](https://linux-hardware.org/?probe=809e03aea5) | Dec 24, 2020 |
| ASUSTek  | G11CD                       | Desktop     | [d9d0f8fdf2](https://linux-hardware.org/?probe=d9d0f8fdf2) | Dec 20, 2020 |
| Standard | BW Series                   | Notebook    | [1f6cf82ba8](https://linux-hardware.org/?probe=1f6cf82ba8) | Jun 13, 2020 |
| Apple    | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [109e02e0f2](https://linux-hardware.org/?probe=109e02e0f2) | Jun 07, 2020 |
| Apple    | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [2d385b9cb0](https://linux-hardware.org/?probe=2d385b9cb0) | Jun 07, 2020 |
| HP       | Notebook                    | Notebook    | [e3c242a846](https://linux-hardware.org/?probe=e3c242a846) | May 24, 2020 |
| Lenovo   | ThinkPad L490 20Q5CTO1WW    | Notebook    | [d8b2c132c1](https://linux-hardware.org/?probe=d8b2c132c1) | Apr 09, 2020 |
| HP       | ZBook 15                    | Notebook    | [4723616d8c](https://linux-hardware.org/?probe=4723616d8c) | Apr 09, 2020 |
| Lenovo   | ThinkPad L490 20Q5CTO1WW    | Notebook    | [1acbabb197](https://linux-hardware.org/?probe=1acbabb197) | Apr 06, 2020 |
| Lenovo   | ThinkPad T480 20L6S56Y2X    | Notebook    | [5343997520](https://linux-hardware.org/?probe=5343997520) | Feb 23, 2020 |
| Dell     | 0C96W1 A01                  | Desktop     | [b5c14107bb](https://linux-hardware.org/?probe=b5c14107bb) | Feb 12, 2020 |
| ASUSTek  | X510UR                      | Notebook    | [914b9fbe64](https://linux-hardware.org/?probe=914b9fbe64) | Feb 04, 2020 |
| ASUSTek  | X510UR                      | Notebook    | [014d5ef0c8](https://linux-hardware.org/?probe=014d5ef0c8) | Jan 28, 2020 |
| ASUSTek  | X510UR                      | Notebook    | [9d05b420d4](https://linux-hardware.org/?probe=9d05b420d4) | Jan 28, 2020 |
| Lenovo   | ThinkPad L540 20AVCTO1WW    | Notebook    | [8c1dba9d6e](https://linux-hardware.org/?probe=8c1dba9d6e) | Sep 10, 2019 |
| HPE      | ProLiant BL460c Gen10       | Server      | [9e91d0ed19](https://linux-hardware.org/?probe=9e91d0ed19) | Jun 14, 2019 |
| Lenovo   | ThinkPad T480 20L6S56Y2X    | Notebook    | [f012a475eb](https://linux-hardware.org/?probe=f012a475eb) | Apr 11, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Oracle Linux 8.5 | 12        | 24%     |
| Oracle Linux 8.3 | 12        | 24%     |
| Oracle Linux 8.4 | 7         | 14%     |
| Oracle Linux 8.6 | 3         | 6%      |
| Oracle Linux 8.1 | 3         | 6%      |
| Oracle Linux 7.9 | 3         | 6%      |
| Oracle Linux 7.7 | 3         | 6%      |
| Oracle Linux 8.2 | 2         | 4%      |
| Oracle Linux 7.8 | 2         | 4%      |
| Oracle Linux 7.6 | 2         | 4%      |
| Oracle Linux 7.4 | 1         | 2%      |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Oracle Linux | 44        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Computers | Percent |
|------------------------------------|-----------|---------|
| 5.4.17-2102.202.5.el8uek.x86_64    | 3         | 5.56%   |
| 5.4.17-2036.103.3.1.el8uek.x86_64  | 3         | 5.56%   |
| 4.18.0-348.12.2.el8_5.x86_64       | 3         | 5.56%   |
| 5.4.17-2136.304.4.3.el8uek.x86_64  | 2         | 3.7%    |
| 5.4.17-2102.205.7.3.el8uek.x86_64  | 2         | 3.7%    |
| 5.4.17-2102.200.13.el8uek.x86_64   | 2         | 3.7%    |
| 5.4.17-2036.102.0.2.el8uek.x86_64  | 2         | 3.7%    |
| 5.4.17-2036.101.2.el8uek.x86_64    | 2         | 3.7%    |
| 4.18.0-240.15.1.el8_3.x86_64       | 2         | 3.7%    |
| 4.18.0-193.1.2.el8_2.x86_64        | 2         | 3.7%    |
| 4.18.0-147.3.1.el8_1.x86_64        | 2         | 3.7%    |
| 5.4.17-2136.308.9.el8uek.x86_64    | 1         | 1.85%   |
| 5.4.17-2136.308.9.el7uek.x86_64    | 1         | 1.85%   |
| 5.4.17-2136.307.3.1.el8uek.x86_64  | 1         | 1.85%   |
| 5.4.17-2136.306.1.3.el8uek.x86_64  | 1         | 1.85%   |
| 5.4.17-2136.305.5.4.el8uek.x86_64  | 1         | 1.85%   |
| 5.4.17-2136.305.5.3.el8uek.x86_64  | 1         | 1.85%   |
| 5.4.17-2136.305.5.2.el8uek.x86_64  | 1         | 1.85%   |
| 5.4.17-2136.301.1.4.el8uek.x86_64  | 1         | 1.85%   |
| 5.4.17-2136.300.7.el8uek.x86_64    | 1         | 1.85%   |
| 5.4.17-2102.204.4.4.el8uek.x86_64  | 1         | 1.85%   |
| 5.4.17-2102.204.4.2.el8uek.x86_64  | 1         | 1.85%   |
| 5.4.17-2102.201.3.el8uek.x86_64    | 1         | 1.85%   |
| 5.4.17-2036.104.4.el8uek.x86_64    | 1         | 1.85%   |
| 5.4.17-2036.100.6.1.el8uek.x86_64  | 1         | 1.85%   |
| 5.4.17-2011.0.7.el8uek.x86_64      | 1         | 1.85%   |
| 5.4.11-1.el7.elrepo.x86_64         | 1         | 1.85%   |
| 5.15.2-1.el8.elrepo.x86_64         | 1         | 1.85%   |
| 5.14.1-1.el8.elrepo.x86_64         | 1         | 1.85%   |
| 5.11.1-1.el8.elrepo.x86_64         | 1         | 1.85%   |
| 4.18.0-348.2.1.el8_5.x86_64        | 1         | 1.85%   |
| 4.18.0-240.10.1.el8_3.x86_64       | 1         | 1.85%   |
| 4.14.35-2047.510.4.1.el7uek.x86_64 | 1         | 1.85%   |
| 4.14.35-1902.4.8.el7uek.x86_64     | 1         | 1.85%   |
| 4.14.35-1902.300.11.el7uek.x86_64  | 1         | 1.85%   |
| 4.14.35-1818.3.3.el7uek.x86_64     | 1         | 1.85%   |
| 4.1.12-124.63.2.1.el7uek.x86_64    | 1         | 1.85%   |
| 3.10.0-957.21.2.el7.x86_64         | 1         | 1.85%   |
| 3.10.0-693.11.6.el7.x86_64         | 1         | 1.85%   |
| 3.10.0-1127.10.1.el7.x86_64        | 1         | 1.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.17  | 24        | 52.17%  |
| 4.18.0  | 10        | 21.74%  |
| 4.14.35 | 4         | 8.7%    |
| 3.10.0  | 3         | 6.52%   |
| 5.4.11  | 1         | 2.17%   |
| 5.15.2  | 1         | 2.17%   |
| 5.14.1  | 1         | 2.17%   |
| 5.11.1  | 1         | 2.17%   |
| 4.1.12  | 1         | 2.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 25        | 54.35%  |
| 4.18    | 10        | 21.74%  |
| 4.14    | 4         | 8.7%    |
| 3.10    | 3         | 6.52%   |
| 5.15    | 1         | 2.17%   |
| 5.14    | 1         | 2.17%   |
| 5.11    | 1         | 2.17%   |
| 4.1     | 1         | 2.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 44        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 31        | 65.96%  |
| Unknown       | 7         | 14.89%  |
| XFCE          | 2         | 4.26%   |
| MATE          | 2         | 4.26%   |
| KDE4          | 2         | 4.26%   |
| GNOME Classic | 2         | 4.26%   |
| KDE5          | 1         | 2.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 23        | 50%     |
| X11     | 18        | 39.13%  |
| Unknown | 5         | 10.87%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 27        | 58.7%   |
| GDM     | 17        | 36.96%  |
| TDM     | 1         | 2.17%   |
| SDDM    | 1         | 2.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 23        | 51.11%  |
| en_GB      | 5         | 11.11%  |
| de_DE      | 4         | 8.89%   |
| Unknown    | 4         | 8.89%   |
| en_AU      | 2         | 4.44%   |
| zh_HK      | 1         | 2.22%   |
| ru_RU      | 1         | 2.22%   |
| pt_BR      | 1         | 2.22%   |
| pl_PL      | 1         | 2.22%   |
| it_IT      | 1         | 2.22%   |
| en_US.UTF8 | 1         | 2.22%   |
| en_IN      | 1         | 2.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 24        | 53.33%  |
| EFI  | 21        | 46.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Xfs     | 37        | 80.43%  |
| Ext4    | 7         | 15.22%  |
| Unknown | 2         | 4.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 24        | 52.17%  |
| GPT     | 12        | 26.09%  |
| MBR     | 10        | 21.74%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 40        | 88.89%  |
| Yes       | 5         | 11.11%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 43        | 97.73%  |
| Yes       | 1         | 2.27%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 17        | 38.64%  |
| Dell                | 9         | 20.45%  |
| Hewlett-Packard     | 5         | 11.36%  |
| ASUSTek Computer    | 5         | 11.36%  |
| Gigabyte Technology | 3         | 6.82%   |
| Standard            | 1         | 2.27%   |
| MSI                 | 1         | 2.27%   |
| HPE                 | 1         | 2.27%   |
| Foxconn             | 1         | 2.27%   |
| Apple               | 1         | 2.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Lenovo ThinkPad T450 20BUS14900           | 2         | 4.55%   |
| ASUS X510UR                               | 2         | 4.55%   |
| Standard BW Series                        | 1         | 2.27%   |
| MSI MS-7758                               | 1         | 2.27%   |
| Lenovo ThinkPad X390 Yoga 20NQS2SF00      | 1         | 2.27%   |
| Lenovo ThinkPad X280 20KES4H34G           | 1         | 2.27%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QWS1R800 | 1         | 2.27%   |
| Lenovo ThinkPad T490 20N3S77600           | 1         | 2.27%   |
| Lenovo ThinkPad T480 20L6S56Y2X           | 1         | 2.27%   |
| Lenovo ThinkPad T480 20L5A07TAU           | 1         | 2.27%   |
| Lenovo ThinkPad T430s 2355C33             | 1         | 2.27%   |
| Lenovo ThinkPad P70 20ESS04S00            | 1         | 2.27%   |
| Lenovo ThinkPad P50s 20FL000MUS           | 1         | 2.27%   |
| Lenovo ThinkPad L540 20AVCTO1WW           | 1         | 2.27%   |
| Lenovo ThinkPad L490 20Q5CTO1WW           | 1         | 2.27%   |
| Lenovo Legion 5 15IMH05 82AU              | 1         | 2.27%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS       | 1         | 2.27%   |
| Lenovo IdeaPad C340-14IWL 81RL            | 1         | 2.27%   |
| Lenovo IdeaPad 300-15ISK 80RS             | 1         | 2.27%   |
| HPE ProLiant BL460c Gen10                 | 1         | 2.27%   |
| HP ZBook 15                               | 1         | 2.27%   |
| HP Z820 Workstation                       | 1         | 2.27%   |
| HP ProBook 445 G6                         | 1         | 2.27%   |
| HP Notebook                               | 1         | 2.27%   |
| HP Compaq 6730b                           | 1         | 2.27%   |
| Gigabyte Z490 AORUS ELITE AC              | 1         | 2.27%   |
| Gigabyte X99-Designare EX-CF              | 1         | 2.27%   |
| Gigabyte X470 AORUS ULTRA GAMING          | 1         | 2.27%   |
| Foxconn p6-2400el                         | 1         | 2.27%   |
| Dell Precision M4800                      | 1         | 2.27%   |
| Dell Precision M4600                      | 1         | 2.27%   |
| Dell PowerEdge FC630                      | 1         | 2.27%   |
| Dell OptiPlex 980                         | 1         | 2.27%   |
| Dell OptiPlex 7060                        | 1         | 2.27%   |
| Dell Latitude E6420                       | 1         | 2.27%   |
| Dell Latitude 7420                        | 1         | 2.27%   |
| Dell Latitude 7410                        | 1         | 2.27%   |
| Dell Inspiron 3542                        | 1         | 2.27%   |
| ASUS UX305FA                              | 1         | 2.27%   |
| ASUS P8H67                                | 1         | 2.27%   |
| ASUS G11CD                                | 1         | 2.27%   |
| Apple Macmini7,1                          | 1         | 2.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 13        | 29.55%  |
| Lenovo IdeaPad         | 3         | 6.82%   |
| Dell Latitude          | 3         | 6.82%   |
| Dell Precision         | 2         | 4.55%   |
| Dell OptiPlex          | 2         | 4.55%   |
| ASUS X510UR            | 2         | 4.55%   |
| Standard BW            | 1         | 2.27%   |
| MSI MS-7758            | 1         | 2.27%   |
| Lenovo Legion          | 1         | 2.27%   |
| HPE ProLiant           | 1         | 2.27%   |
| HP ZBook               | 1         | 2.27%   |
| HP Z820                | 1         | 2.27%   |
| HP ProBook             | 1         | 2.27%   |
| HP Notebook            | 1         | 2.27%   |
| HP Compaq              | 1         | 2.27%   |
| Gigabyte Z490          | 1         | 2.27%   |
| Gigabyte X99-Designare | 1         | 2.27%   |
| Gigabyte X470          | 1         | 2.27%   |
| Foxconn p6-2400el      | 1         | 2.27%   |
| Dell PowerEdge         | 1         | 2.27%   |
| Dell Inspiron          | 1         | 2.27%   |
| ASUS UX305FA           | 1         | 2.27%   |
| ASUS P8H67             | 1         | 2.27%   |
| ASUS G11CD             | 1         | 2.27%   |
| Apple Macmini7         | 1         | 2.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 8         | 18.18%  |
| 2018 | 6         | 13.64%  |
| 2016 | 6         | 13.64%  |
| 2020 | 4         | 9.09%   |
| 2015 | 4         | 9.09%   |
| 2012 | 4         | 9.09%   |
| 2014 | 3         | 6.82%   |
| 2017 | 2         | 4.55%   |
| 2013 | 2         | 4.55%   |
| 2011 | 2         | 4.55%   |
| 2010 | 2         | 4.55%   |
| 2008 | 1         | 2.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 29        | 65.91%  |
| Desktop     | 11        | 25%     |
| Convertible | 2         | 4.55%   |
| Mini pc     | 1         | 2.27%   |
| Server      | 1         | 2.27%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 42        | 93.33%  |
| Enabled  | 3         | 6.67%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 44        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 11        | 24.44%  |
| 32.01-64.0      | 10        | 22.22%  |
| 4.01-8.0        | 9         | 20%     |
| 16.01-24.0      | 5         | 11.11%  |
| 3.01-4.0        | 4         | 8.89%   |
| 64.01-256.0     | 3         | 6.67%   |
| More than 256.0 | 1         | 2.22%   |
| 24.01-32.0      | 1         | 2.22%   |
| 1.01-2.0        | 1         | 2.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 16        | 32%     |
| 4.01-8.0   | 12        | 24%     |
| 8.01-16.0  | 8         | 16%     |
| 3.01-4.0   | 6         | 12%     |
| 1.01-2.0   | 4         | 8%      |
| 24.01-32.0 | 1         | 2%      |
| 16.01-24.0 | 1         | 2%      |
| 0.51-1.0   | 1         | 2%      |
| 0.01-0.5   | 1         | 2%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 35        | 77.78%  |
| 2      | 5         | 11.11%  |
| 4      | 2         | 4.44%   |
| 3      | 2         | 4.44%   |
| 5      | 1         | 2.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 31        | 70.45%  |
| Yes       | 13        | 29.55%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 37        | 84.09%  |
| No        | 7         | 15.91%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 35        | 79.55%  |
| No        | 9         | 20.45%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 53.33%  |
| No        | 21        | 46.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 14        | 31.11%  |
| Germany     | 7         | 15.56%  |
| UK          | 4         | 8.89%   |
| Brazil      | 3         | 6.67%   |
| Australia   | 3         | 6.67%   |
| Russia      | 2         | 4.44%   |
| Romania     | 2         | 4.44%   |
| Netherlands | 2         | 4.44%   |
| Poland      | 1         | 2.22%   |
| Pakistan    | 1         | 2.22%   |
| Kazakhstan  | 1         | 2.22%   |
| Italy       | 1         | 2.22%   |
| India       | 1         | 2.22%   |
| Hong Kong   | 1         | 2.22%   |
| Bulgaria    | 1         | 2.22%   |
| Argentina   | 1         | 2.22%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| San Diego          | 3         | 6.12%   |
| Siegen             | 2         | 4.08%   |
| Seattle            | 2         | 4.08%   |
| Colorado Springs   | 2         | 4.08%   |
| Bucharest          | 2         | 4.08%   |
| Berlin             | 2         | 4.08%   |
| Weaverville        | 1         | 2.04%   |
| Veliky Novgorod    | 1         | 2.04%   |
| Utrecht            | 1         | 2.04%   |
| Sydney             | 1         | 2.04%   |
| Sofia              | 1         | 2.04%   |
| Shrewsbury         | 1         | 2.04%   |
| Sao Paulo          | 1         | 2.04%   |
| Sao Caetano do Sul | 1         | 2.04%   |
| San Francisco      | 1         | 2.04%   |
| Rocklin            | 1         | 2.04%   |
| Reading            | 1         | 2.04%   |
| Port Saint Lucie   | 1         | 2.04%   |
| Pleven             | 1         | 2.04%   |
| Ngau Wu Tok        | 1         | 2.04%   |
| Neunkirchen        | 1         | 2.04%   |
| Moscow             | 1         | 2.04%   |
| Maple Valley       | 1         | 2.04%   |
| Ludwigsburg        | 1         | 2.04%   |
| London             | 1         | 2.04%   |
| Langgons           | 1         | 2.04%   |
| Katowice           | 1         | 2.04%   |
| Karaganda          | 1         | 2.04%   |
| Karachi            | 1         | 2.04%   |
| Greven             | 1         | 2.04%   |
| Drochtersen        | 1         | 2.04%   |
| Dallas             | 1         | 2.04%   |
| Chicago            | 1         | 2.04%   |
| Castelar           | 1         | 2.04%   |
| Canberra           | 1         | 2.04%   |
| Campinas           | 1         | 2.04%   |
| Bracknell          | 1         | 2.04%   |
| Bengaluru          | 1         | 2.04%   |
| Asheville          | 1         | 2.04%   |
| Amsterdam          | 1         | 2.04%   |
| Albairate          | 1         | 2.04%   |
| Adelaide           | 1         | 2.04%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 14        | 18     | 26.42%  |
| Seagate                 | 8         | 46     | 15.09%  |
| SanDisk                 | 6         | 7      | 11.32%  |
| WDC                     | 4         | 4      | 7.55%   |
| Unknown                 | 2         | 4      | 3.77%   |
| Toshiba                 | 2         | 2      | 3.77%   |
| Kingston                | 2         | 7      | 3.77%   |
| HGST                    | 2         | 3      | 3.77%   |
| Crucial                 | 2         | 3      | 3.77%   |
| Union Memory (Shenzhen) | 1         | 2      | 1.89%   |
| SK hynix                | 1         | 1      | 1.89%   |
| Phison                  | 1         | 1      | 1.89%   |
| Micron Technology       | 1         | 4      | 1.89%   |
| Lite-On                 | 1         | 1      | 1.89%   |
| Lenovo                  | 1         | 1      | 1.89%   |
| Intel                   | 1         | 1      | 1.89%   |
| HPE                     | 1         | 1      | 1.89%   |
| Hewlett-Packard         | 1         | 1      | 1.89%   |
| Fujitsu                 | 1         | 1      | 1.89%   |
| Apple                   | 1         | 1      | 1.89%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seagate ST2000DM008-2FR102 2TB               | 2         | 3.45%   |
| SanDisk SSD PLUS 1000GB                      | 2         | 3.45%   |
| Samsung SSD PM830 2.5 7mm 256GB              | 2         | 3.45%   |
| Samsung MZ7LN512HMJP-000L7 512GB SSD         | 2         | 3.45%   |
| Crucial CT500MX500SSD1 500GB                 | 2         | 3.45%   |
| WDC WDS500G2B0A-00SM50 500GB SSD             | 1         | 1.72%   |
| WDC WDS250G2B0A-00SM50 250GB SSD             | 1         | 1.72%   |
| WDC WD10JPCX-24UE4T0 1TB                     | 1         | 1.72%   |
| WDC WD10EZEX-60M2NA0 1TB                     | 1         | 1.72%   |
| Unknown SD/MMC/MS PRO 128GB                  | 1         | 1.72%   |
| Unknown MMC Card  256GB                      | 1         | 1.72%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 1.72%   |
| Toshiba NVMe SSD Drive 512GB                 | 1         | 1.72%   |
| Toshiba MG04ACA200E 2TB                      | 1         | 1.72%   |
| SK hynix SKHynix_HFS256GD9TNG-L3A0B 256GB    | 1         | 1.72%   |
| Seagate ST9750420AS 752GB                    | 1         | 1.72%   |
| Seagate ST8000VN004-2M2101 8TB               | 1         | 1.72%   |
| Seagate ST3750528AS 752GB                    | 1         | 1.72%   |
| Seagate ST3500414CS 500GB                    | 1         | 1.72%   |
| Seagate ST2000NX0253 2TB                     | 1         | 1.72%   |
| Seagate ST1000NX0423 1TB                     | 1         | 1.72%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1.72%   |
| Seagate ST1000LM010-9YH146 1TB               | 1         | 1.72%   |
| SanDisk SDSSDH3512G 512GB                    | 1         | 1.72%   |
| SanDisk SD7SN3Q256G1002 256GB SSD            | 1         | 1.72%   |
| SanDisk SD6SB1M-256G-1006 256GB SSD          | 1         | 1.72%   |
| SanDisk NVMe SSD Drive 512GB                 | 1         | 1.72%   |
| Samsung SSD SM841N 2.5 7mm 512GB             | 1         | 1.72%   |
| Samsung SSD 960 EVO 250GB                    | 1         | 1.72%   |
| Samsung SSD 850 PRO 256GB                    | 1         | 1.72%   |
| Samsung PM9A1 NVMe 512GB                     | 1         | 1.72%   |
| Samsung NVMe SSD Drive 512GB                 | 1         | 1.72%   |
| Samsung MZVLW256HEHP-000L7 256GB             | 1         | 1.72%   |
| Samsung MZVLB1T0HBLR-000L7 1TB               | 1         | 1.72%   |
| Samsung MZNLN512HCJH-000L1 512GB SSD         | 1         | 1.72%   |
| Samsung MZ7LN512HCHP-000L1 512GB SSD         | 1         | 1.72%   |
| Samsung MZ7LN256HCHP-000L7 256GB SSD         | 1         | 1.72%   |
| Samsung HD502IJ 500GB                        | 1         | 1.72%   |
| Phison NVMe SSD Drive 1TB                    | 1         | 1.72%   |
| Micron NVMe SSD Drive 256GB                  | 1         | 1.72%   |
| Micron 2200S NVMe 256GB                      | 1         | 1.72%   |
| Lite-On NVMe SSD Drive 512GB                 | 1         | 1.72%   |
| Lenovo LENSE30512GMSP34MEAT3TA 512GB         | 1         | 1.72%   |
| Kingston SUV400S37240G 240GB SSD             | 1         | 1.72%   |
| Kingston SA400S37240G 240GB SSD              | 1         | 1.72%   |
| Kingston NVMe SSD Drive 1TB                  | 1         | 1.72%   |
| Intel SSDPEKKF256G8L 256GB                   | 1         | 1.72%   |
| HPE LOGICAL VOLUME 304GB                     | 1         | 1.72%   |
| HGST HTS545050A7E380 500GB                   | 1         | 1.72%   |
| HGST HTS541010A7E630 1TB                     | 1         | 1.72%   |
| HP SSD S700 120GB                            | 1         | 1.72%   |
| Fujitsu MHZ2160BH G2 160GB                   | 1         | 1.72%   |
| Apple HDD HTS541010A9E662 1TB                | 1         | 1.72%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 46     | 44.44%  |
| WDC                 | 2         | 2      | 11.11%  |
| HGST                | 2         | 3      | 11.11%  |
| Unknown             | 1         | 3      | 5.56%   |
| Toshiba             | 1         | 1      | 5.56%   |
| Samsung Electronics | 1         | 1      | 5.56%   |
| HPE                 | 1         | 1      | 5.56%   |
| Fujitsu             | 1         | 1      | 5.56%   |
| Apple               | 1         | 1      | 5.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 10     | 45%     |
| SanDisk             | 5         | 5      | 25%     |
| WDC                 | 2         | 2      | 10%     |
| Crucial             | 2         | 3      | 10%     |
| Kingston            | 1         | 2      | 5%      |
| Hewlett-Packard     | 1         | 1      | 5%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 20        | 23     | 37.74%  |
| HDD  | 17        | 59     | 32.08%  |
| NVMe | 15        | 26     | 28.3%   |
| MMC  | 1         | 1      | 1.89%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 32        | 78     | 64%     |
| NVMe | 15        | 26     | 30%     |
| SAS  | 2         | 4      | 4%      |
| MMC  | 1         | 1      | 2%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 17        | 22     | 45.95%  |
| 0.51-1.0   | 15        | 20     | 40.54%  |
| 1.01-2.0   | 4         | 38     | 10.81%  |
| 4.01-10.0  | 1         | 2      | 2.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 11        | 24.44%  |
| 101-250        | 8         | 17.78%  |
| Unknown        | 7         | 15.56%  |
| 501-1000       | 6         | 13.33%  |
| 1-20           | 5         | 11.11%  |
| 2001-3000      | 2         | 4.44%   |
| 1001-2000      | 2         | 4.44%   |
| 51-100         | 2         | 4.44%   |
| More than 3000 | 1         | 2.22%   |
| 21-50          | 1         | 2.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 14        | 30.43%  |
| 21-50          | 10        | 21.74%  |
| Unknown        | 7         | 15.22%  |
| 101-250        | 5         | 10.87%  |
| 51-100         | 5         | 10.87%  |
| 251-500        | 3         | 6.52%   |
| More than 3000 | 1         | 2.17%   |
| 501-1000       | 1         | 2.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST9750420AS 752GB          | 1         | 1      | 33.33%  |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 33.33%  |
| Hewlett-Packard SSD S700 120GB     | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| Seagate         | 2         | 2      | 66.67%  |
| Hewlett-Packard | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 2      | 66.67%  |
| SSD  | 1         | 1      | 33.33%  |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 26        | 48     | 55.32%  |
| Works    | 18        | 58     | 38.3%   |
| Malfunc  | 3         | 3      | 6.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 31        | 58.49%  |
| Samsung Electronics          | 5         | 9.43%   |
| AMD                          | 4         | 7.55%   |
| Broadcom / LSI               | 2         | 3.77%   |
| VIA Technologies             | 1         | 1.89%   |
| Union Memory (Shenzhen)      | 1         | 1.89%   |
| Toshiba America Info Systems | 1         | 1.89%   |
| SK hynix                     | 1         | 1.89%   |
| SanDisk                      | 1         | 1.89%   |
| Phison Electronics           | 1         | 1.89%   |
| Micron Technology            | 1         | 1.89%   |
| Lite-On Technology           | 1         | 1.89%   |
| Lenovo                       | 1         | 1.89%   |
| Kingston Technology Company  | 1         | 1.89%   |
| Adaptec                      | 1         | 1.89%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 4         | 6.78%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 4         | 6.78%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 3         | 5.08%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 5.08%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 3.39%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 3.39%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2         | 3.39%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2         | 3.39%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2         | 3.39%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2         | 3.39%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 3.39%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1         | 1.69%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                  | 1         | 1.69%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 1         | 1.69%   |
| SK hynix Non-Volatile memory controller                                                 | 1         | 1.69%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1         | 1.69%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1         | 1.69%   |
| Phison E12 NVMe Controller                                                              | 1         | 1.69%   |
| Micron Non-Volatile memory controller                                                   | 1         | 1.69%   |
| Lite-On Non-Volatile memory controller                                                  | 1         | 1.69%   |
| Lenovo Non-Volatile memory controller                                                   | 1         | 1.69%   |
| Kingston Company A2000 NVMe SSD                                                         | 1         | 1.69%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                 | 1         | 1.69%   |
| Intel SATA Controller [RAID mode]                                                       | 1         | 1.69%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1         | 1.69%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1         | 1.69%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1         | 1.69%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1         | 1.69%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1         | 1.69%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1         | 1.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 1         | 1.69%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 1         | 1.69%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1         | 1.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1         | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1         | 1.69%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1         | 1.69%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 1         | 1.69%   |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                            | 1         | 1.69%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1         | 1.69%   |
| Adaptec Smart Storage PQI SAS                                                           | 1         | 1.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 28        | 52.83%  |
| NVMe | 15        | 28.3%   |
| RAID | 6         | 11.32%  |
| SAS  | 2         | 3.77%   |
| IDE  | 2         | 3.77%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 40        | 90.91%  |
| AMD    | 4         | 9.09%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-8665U CPU @ 1.90GHz               | 2         | 4.55%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 2         | 4.55%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 2         | 4.55%   |
| Intel Core i5-8350U CPU @ 1.70GHz               | 2         | 4.55%   |
| Intel Core i5-5300U CPU @ 2.30GHz               | 2         | 4.55%   |
| Intel Xeon Silver 4114 CPU @ 2.20GHz            | 1         | 2.27%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz             | 1         | 2.27%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz             | 1         | 2.27%   |
| Intel Processor 5Y10 CPU @ 0.80GHz              | 1         | 2.27%   |
| Intel Pentium CPU G2020 @ 2.90GHz               | 1         | 2.27%   |
| Intel Core i9-9880H CPU @ 2.30GHz               | 1         | 2.27%   |
| Intel Core i9-10900K CPU @ 3.70GHz              | 1         | 2.27%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 1         | 2.27%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 2.27%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 1         | 2.27%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz              | 1         | 2.27%   |
| Intel Core i7-6800K CPU @ 3.40GHz               | 1         | 2.27%   |
| Intel Core i7-6700 CPU @ 3.40GHz                | 1         | 2.27%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz              | 1         | 2.27%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz              | 1         | 2.27%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 1         | 2.27%   |
| Intel Core i7-2860QM CPU @ 2.50GHz              | 1         | 2.27%   |
| Intel Core i7-2760QM CPU @ 2.40GHz              | 1         | 2.27%   |
| Intel Core i7-2600 CPU @ 3.40GHz                | 1         | 2.27%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 1         | 2.27%   |
| Intel Core i7-10610U CPU @ 1.80GHz              | 1         | 2.27%   |
| Intel Core i5-8365U CPU @ 1.60GHz               | 1         | 2.27%   |
| Intel Core i5-4278U CPU @ 2.60GHz               | 1         | 2.27%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 1         | 2.27%   |
| Intel Core i5-4210M CPU @ 2.60GHz               | 1         | 2.27%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 1         | 2.27%   |
| Intel Core i3 CPU 550 @ 3.20GHz                 | 1         | 2.27%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz            | 1         | 2.27%   |
| Intel Celeron CPU N3010 @ 1.04GHz               | 1         | 2.27%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz         | 1         | 2.27%   |
| AMD Ryzen 7 PRO 2700U w/ Radeon Vega Mobile Gfx | 1         | 2.27%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 1         | 2.27%   |
| AMD A9-9420e RADEON R5, 5 COMPUTE CORES 2C+3G   | 1         | 2.27%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics     | 1         | 2.27%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i7     | 20        | 45.45%  |
| Intel Core i5     | 9         | 20.45%  |
| Other             | 3         | 6.82%   |
| Intel Xeon        | 2         | 4.55%   |
| Intel Core i9     | 2         | 4.55%   |
| Intel Xeon Silver | 1         | 2.27%   |
| Intel Pentium     | 1         | 2.27%   |
| Intel Core i3     | 1         | 2.27%   |
| Intel Core 2 Duo  | 1         | 2.27%   |
| Intel Celeron     | 1         | 2.27%   |
| AMD Ryzen 7 PRO   | 1         | 2.27%   |
| AMD Ryzen 7       | 1         | 2.27%   |
| AMD A8            | 1         | 2.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 18        | 40.91%  |
| 2      | 16        | 36.36%  |
| 6      | 3         | 6.82%   |
| 16     | 2         | 4.55%   |
| 8      | 2         | 4.55%   |
| 20     | 1         | 2.27%   |
| 10     | 1         | 2.27%   |
| 1      | 1         | 2.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 41        | 93.18%  |
| 2      | 3         | 6.82%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 38        | 86.36%  |
| 1      | 6         | 13.64%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 43        | 95.56%  |
| Unknown        | 2         | 4.44%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806ec    | 5         | 11.36%  |
| 0x806ea    | 3         | 6.82%   |
| 0x306d4    | 3         | 6.82%   |
| 0x306c3    | 3         | 6.82%   |
| 0x306a9    | 3         | 6.82%   |
| 0x206a7    | 3         | 6.82%   |
| Unknown    | 3         | 6.82%   |
| 0x506e3    | 2         | 4.55%   |
| 0x406e3    | 2         | 4.55%   |
| 0x40651    | 2         | 4.55%   |
| 0xa0655    | 1         | 2.27%   |
| 0xa0652    | 1         | 2.27%   |
| 0x906ed    | 1         | 2.27%   |
| 0x906ea    | 1         | 2.27%   |
| 0x806c1    | 1         | 2.27%   |
| 0x50654    | 1         | 2.27%   |
| 0x406f1    | 1         | 2.27%   |
| 0x406c4    | 1         | 2.27%   |
| 0x306e4    | 1         | 2.27%   |
| 0x20655    | 1         | 2.27%   |
| 0x10676    | 1         | 2.27%   |
| 0x0810100b | 1         | 2.27%   |
| 0x0800820d | 1         | 2.27%   |
| 0x07030105 | 1         | 2.27%   |
| 0x06006705 | 1         | 2.27%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 12        | 27.27%  |
| Skylake     | 5         | 11.36%  |
| Haswell     | 5         | 11.36%  |
| Broadwell   | 5         | 11.36%  |
| IvyBridge   | 4         | 9.09%   |
| SandyBridge | 3         | 6.82%   |
| CometLake   | 2         | 4.55%   |
| Zen+        | 1         | 2.27%   |
| Zen         | 1         | 2.27%   |
| Westmere    | 1         | 2.27%   |
| TigerLake   | 1         | 2.27%   |
| Silvermont  | 1         | 2.27%   |
| Puma        | 1         | 2.27%   |
| Penryn      | 1         | 2.27%   |
| Excavator   | 1         | 2.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 29        | 53.7%   |
| Nvidia                     | 16        | 29.63%  |
| AMD                        | 7         | 12.96%  |
| Matrox Electronics Systems | 2         | 3.7%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 7.41%   |
| Intel UHD Graphics 620                                                                   | 3         | 5.56%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 5.56%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 3.7%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 3.7%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 3.7%    |
| Intel HD Graphics 620                                                                    | 2         | 3.7%    |
| Intel HD Graphics 5500                                                                   | 2         | 3.7%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 3.7%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.85%   |
| Nvidia TU117M                                                                            | 1         | 1.85%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1         | 1.85%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1         | 1.85%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 1.85%   |
| Nvidia GM204GLM [Quadro M4000M]                                                          | 1         | 1.85%   |
| Nvidia GM204 [GeForce GTX 980]                                                           | 1         | 1.85%   |
| Nvidia GM108GLM [Quadro K620M / Quadro M500M]                                            | 1         | 1.85%   |
| Nvidia GK208GLM [Quadro K610M]                                                           | 1         | 1.85%   |
| Nvidia GK110GL [Quadro K6000]                                                            | 1         | 1.85%   |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 1.85%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                                      | 1         | 1.85%   |
| Matrox Electronics Systems MGA G200eH3                                                   | 1         | 1.85%   |
| Matrox Electronics Systems G200eR2                                                       | 1         | 1.85%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 1.85%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 1.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.85%   |
| Intel HD Graphics 5300                                                                   | 1         | 1.85%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.85%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.85%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 1.85%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.85%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 1.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.85%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 1.85%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 1         | 1.85%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                                          | 1         | 1.85%   |
| AMD Turks [Radeon HD 7600 Series]                                                        | 1         | 1.85%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 1.85%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 1.85%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 1.85%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 1.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 19        | 43.18%  |
| 1 x Nvidia     | 9         | 20.45%  |
| Intel + Nvidia | 7         | 15.91%  |
| 1 x AMD        | 5         | 11.36%  |
| 1 x Matrox     | 2         | 4.55%   |
| Intel + AMD    | 2         | 4.55%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 39        | 88.64%  |
| Proprietary | 3         | 6.82%   |
| Unknown     | 2         | 4.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 48.89%  |
| 1.01-2.0   | 9         | 20%     |
| 3.01-4.0   | 7         | 15.56%  |
| 0.51-1.0   | 3         | 6.67%   |
| 0.01-0.5   | 2         | 4.44%   |
| 5.01-6.0   | 1         | 2.22%   |
| 8.01-16.0  | 1         | 2.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 11        | 19.3%   |
| LG Display           | 8         | 14.04%  |
| Samsung Electronics  | 6         | 10.53%  |
| Dell                 | 5         | 8.77%   |
| Chimei Innolux       | 5         | 8.77%   |
| Lenovo               | 4         | 7.02%   |
| BOE                  | 3         | 5.26%   |
| BenQ                 | 3         | 5.26%   |
| Hewlett-Packard      | 2         | 3.51%   |
| ViewSonic            | 1         | 1.75%   |
| Sony                 | 1         | 1.75%   |
| SAC                  | 1         | 1.75%   |
| InfoVision           | 1         | 1.75%   |
| Goldstar             | 1         | 1.75%   |
| Element              | 1         | 1.75%   |
| Eizo                 | 1         | 1.75%   |
| ASUSTek Computer     | 1         | 1.75%   |
| Ancor Communications | 1         | 1.75%   |
| Acer                 | 1         | 1.75%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 2         | 3.33%   |
| BenQ GL2760 BNQ78D5 1920x1080 598x336mm 27.0-inch                     | 2         | 3.33%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch         | 2         | 3.33%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 2         | 3.33%   |
| ViewSonic VX2433wm VSC3822 1920x1080 520x290mm 23.4-inch              | 1         | 1.67%   |
| Sony TV SNY4502 1920x1080                                             | 1         | 1.67%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch   | 1         | 1.67%   |
| Samsung Electronics S27D391 SAM0B89 1920x1080 600x340mm 27.2-inch     | 1         | 1.67%   |
| Samsung Electronics S27D391 SAM0B88 1920x1080 598x336mm 27.0-inch     | 1         | 1.67%   |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch     | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SDC3256 1920x1080 382x215mm 17.3-inch | 1         | 1.67%   |
| Samsung Electronics LCD Monitor S24C650                               | 1         | 1.67%   |
| Samsung Electronics C32HG7x SAM0E14 2560x1440 697x392mm 31.5-inch     | 1         | 1.67%   |
| SAC LED MONITOR SAC952D 1920x1080 480x270mm 21.7-inch                 | 1         | 1.67%   |
| LG Display LCD Monitor LGD0609 1920x1080 309x174mm 14.0-inch          | 1         | 1.67%   |
| LG Display LCD Monitor LGD04BD 1366x768 344x194mm 15.5-inch           | 1         | 1.67%   |
| LG Display LCD Monitor LGD047C 1366x768 310x174mm 14.0-inch           | 1         | 1.67%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 1         | 1.67%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch           | 1         | 1.67%   |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch          | 1         | 1.67%   |
| Lenovo T24i-10 LEN61A6 1920x1080 527x296mm 23.8-inch                  | 1         | 1.67%   |
| Lenovo LEN T2424pA LEN60C8 1920x1080 527x296mm 23.8-inch              | 1         | 1.67%   |
| Lenovo LEN T2254pC LEN60CC 1680x1050 474x296mm 22.0-inch              | 1         | 1.67%   |
| Lenovo LEN P27u-10 LEN61B0 3840x2160 600x340mm 27.2-inch              | 1         | 1.67%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 1         | 1.67%   |
| Hewlett-Packard Z24i HWP309E 1920x1200 518x324mm 24.1-inch            | 1         | 1.67%   |
| Hewlett-Packard E273q HPN3474 2560x1440 597x336mm 27.0-inch           | 1         | 1.67%   |
| Goldstar E2240 GSM57A3 1920x1080 477x268mm 21.5-inch                  | 1         | 1.67%   |
| Element T430QVN02.1 ELE6586 3840x2160 708x398mm 32.0-inch             | 1         | 1.67%   |
| Eizo EV2460 ENC3129 1920x1080 528x297mm 23.9-inch                     | 1         | 1.67%   |
| Dell U2718Q DELA0E9 3840x2160 609x349mm 27.6-inch                     | 1         | 1.67%   |
| Dell P2719H DEL4184 1920x1080 598x336mm 27.0-inch                     | 1         | 1.67%   |
| Dell P2414H DELA09C 1920x1080 527x297mm 23.8-inch                     | 1         | 1.67%   |
| Dell LCD Monitor U2415 3840x1200                                      | 1         | 1.67%   |
| Dell IDRAC DEL0001 1280x1024                                          | 1         | 1.67%   |
| Dell E2009W DEL4240 1680x1050 433x271mm 20.1-inch                     | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 340x190mm 15.3-inch      | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN14E8 1920x1080 310x170mm 13.9-inch      | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN1387 1920x1080 293x165mm 13.2-inch      | 1         | 1.67%   |
| BOE LCD Monitor BOE08E8 1920x1080 344x194mm 15.5-inch                 | 1         | 1.67%   |
| BOE LCD Monitor BOE074F 1920x1080 309x173mm 13.9-inch                 | 1         | 1.67%   |
| BOE LCD Monitor BOE0630 1920x1080 344x194mm 15.5-inch                 | 1         | 1.67%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO8074 1280x800 331x207mm 15.4-inch         | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch         | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO212D 1920x1080 293x165mm 13.2-inch        | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 1         | 1.67%   |
| AU Optronics LCD Monitor AUO106D 1920x1080 276x155mm 12.5-inch        | 1         | 1.67%   |
| ASUSTek Computer VP249 AUS24AF 1920x1080 527x296mm 23.8-inch          | 1         | 1.67%   |
| Ancor Communications VW246 ACI24F2 1920x1080 531x299mm 24.0-inch      | 1         | 1.67%   |
| Acer SA230 ACR057E 1920x1080 509x286mm 23.0-inch                      | 1         | 1.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 28        | 58.33%  |
| 1600x900 (HD+)     | 4         | 8.33%   |
| 1366x768 (WXGA)    | 4         | 8.33%   |
| 3840x2160 (4K)     | 3         | 6.25%   |
| 2560x1440 (QHD)    | 2         | 4.17%   |
| 3840x1200          | 1         | 2.08%   |
| 1920x1200 (WUXGA)  | 1         | 2.08%   |
| 1680x1050 (WSXGA+) | 1         | 2.08%   |
| 1360x768           | 1         | 2.08%   |
| 1280x800 (WXGA)    | 1         | 2.08%   |
| 1280x1024 (SXGA)   | 1         | 2.08%   |
| Unknown            | 1         | 2.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 13        | 23.21%  |
| 14      | 10        | 17.86%  |
| 27      | 8         | 14.29%  |
| 24      | 6         | 10.71%  |
| 13      | 5         | 8.93%   |
| 23      | 3         | 5.36%   |
| 21      | 2         | 3.57%   |
| Unknown | 2         | 3.57%   |
| 72      | 1         | 1.79%   |
| 32      | 1         | 1.79%   |
| 31      | 1         | 1.79%   |
| 22      | 1         | 1.79%   |
| 18      | 1         | 1.79%   |
| 17      | 1         | 1.79%   |
| 12      | 1         | 1.79%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 26        | 47.27%  |
| 501-600     | 15        | 27.27%  |
| 401-500     | 4         | 7.27%   |
| 201-300     | 3         | 5.45%   |
| 601-700     | 2         | 3.64%   |
| Unknown     | 2         | 3.64%   |
| 701-800     | 1         | 1.82%   |
| 351-400     | 1         | 1.82%   |
| 1501-2000   | 1         | 1.82%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 38        | 88.37%  |
| 16/10   | 3         | 6.98%   |
| 5/4     | 1         | 2.33%   |
| Unknown | 1         | 2.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 13        | 23.64%  |
| 101-110        | 13        | 23.64%  |
| 201-250        | 10        | 18.18%  |
| 301-350        | 8         | 14.55%  |
| 71-80          | 2         | 3.64%   |
| 351-500        | 2         | 3.64%   |
| Unknown        | 2         | 3.64%   |
| More than 1000 | 1         | 1.82%   |
| 61-70          | 1         | 1.82%   |
| 251-300        | 1         | 1.82%   |
| 141-150        | 1         | 1.82%   |
| 121-130        | 1         | 1.82%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 23        | 44.23%  |
| 51-100  | 15        | 28.85%  |
| 101-120 | 7         | 13.46%  |
| 161-240 | 4         | 7.69%   |
| Unknown | 2         | 3.85%   |
| 1-50    | 1         | 1.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 28        | 63.64%  |
| 2     | 10        | 22.73%  |
| 3     | 3         | 6.82%   |
| 0     | 2         | 4.55%   |
| 4     | 1         | 2.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 32        | 52.46%  |
| Realtek Semiconductor | 14        | 22.95%  |
| Qualcomm Atheros      | 4         | 6.56%   |
| Broadcom              | 4         | 6.56%   |
| Lenovo                | 2         | 3.28%   |
| Broadcom Limited      | 2         | 3.28%   |
| Ralink Technology     | 1         | 1.64%   |
| NetGear               | 1         | 1.64%   |
| Fibocom               | 1         | 1.64%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 8.54%   |
| Intel Wireless 8265 / 8275                                        | 5         | 6.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 4.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 3.66%   |
| Intel Wireless 8260                                               | 3         | 3.66%   |
| Intel Wireless 7265                                               | 3         | 3.66%   |
| Intel Ethernet Connection (6) I219-LM                             | 3         | 3.66%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 2.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 2.44%   |
| Intel Wireless 7260                                               | 2         | 2.44%   |
| Intel I211 Gigabit Network Connection                             | 2         | 2.44%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 2.44%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 2.44%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.44%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 2.44%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 2.44%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 2.44%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 2.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 1.22%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.22%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 1.22%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.22%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 1.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.22%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 1.22%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                   | 1         | 1.22%   |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 1.22%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 1.22%   |
| Intel Wireless-AC 9260                                            | 1         | 1.22%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.22%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 1.22%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 1         | 1.22%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.22%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.22%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.22%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.22%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.22%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 1.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.22%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 1.22%   |
| Intel 82599 10 Gigabit Dual Port Backplane Connection             | 1         | 1.22%   |
| Intel 82578DM Gigabit Network Connection                          | 1         | 1.22%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.22%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                 | 1         | 1.22%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 1         | 1.22%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.22%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 1         | 1.22%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 1         | 1.22%   |
| Broadcom BCM57840 NetXtreme II 10/20-Gigabit Ethernet             | 1         | 1.22%   |
| Broadcom BCM43142 802.11b/g/n                                     | 1         | 1.22%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 26        | 68.42%  |
| Qualcomm Atheros      | 4         | 10.53%  |
| Realtek Semiconductor | 3         | 7.89%   |
| Ralink Technology     | 1         | 2.63%   |
| NetGear               | 1         | 2.63%   |
| Fibocom               | 1         | 2.63%   |
| Broadcom Limited      | 1         | 2.63%   |
| Broadcom              | 1         | 2.63%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 5         | 13.16%  |
| Intel Wireless 8260                                            | 3         | 7.89%   |
| Intel Wireless 7265                                            | 3         | 7.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 2         | 5.26%   |
| Intel Wireless 7260                                            | 2         | 5.26%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 5.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 5.26%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 5.26%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 2.63%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.63%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 2.63%   |
| Ralink MT7601U Wireless Adapter                                | 1         | 2.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 2.63%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 2.63%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                | 1         | 2.63%   |
| Intel Wireless-AC 9260                                         | 1         | 2.63%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 2.63%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 2.63%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 2.63%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 2.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 2.63%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 2.63%   |
| Fibocom L830-EB-00 LTE WWAN Modem                              | 1         | 2.63%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 1         | 2.63%   |
| Broadcom BCM43142 802.11b/g/n                                  | 1         | 2.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 23        | 54.76%  |
| Realtek Semiconductor | 13        | 30.95%  |
| Broadcom              | 3         | 7.14%   |
| Lenovo                | 2         | 4.76%   |
| Broadcom Limited      | 1         | 2.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 15.91%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 9.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 6.82%   |
| Intel Ethernet Connection (6) I219-LM                             | 3         | 6.82%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 4.55%   |
| Intel I211 Gigabit Network Connection                             | 2         | 4.55%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 4.55%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 4.55%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 4.55%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 4.55%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 2.27%   |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 2.27%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 2.27%   |
| Intel Ethernet Connection I219-V                                  | 1         | 2.27%   |
| Intel Ethernet Connection I217-V                                  | 1         | 2.27%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 2.27%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.27%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 2.27%   |
| Intel 82599 10 Gigabit Dual Port Backplane Connection             | 1         | 2.27%   |
| Intel 82578DM Gigabit Network Connection                          | 1         | 2.27%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 2.27%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 1         | 2.27%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 2.27%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 1         | 2.27%   |
| Broadcom BCM57840 NetXtreme II 10/20-Gigabit Ethernet             | 1         | 2.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 37        | 51.39%  |
| WiFi     | 35        | 48.61%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 23        | 50%     |
| Ethernet | 23        | 50%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 28        | 63.64%  |
| 1     | 14        | 31.82%  |
| 4     | 1         | 2.27%   |
| 3     | 1         | 2.27%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 35        | 74.47%  |
| Yes  | 12        | 25.53%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 15        | 60%     |
| Qualcomm Atheros Communications | 3         | 12%     |
| Broadcom                        | 3         | 12%     |
| Realtek Semiconductor           | 1         | 4%      |
| IMC Networks                    | 1         | 4%      |
| ASUSTek Computer                | 1         | 4%      |
| Apple                           | 1         | 4%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 9         | 36%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 3         | 12%     |
| Qualcomm Atheros  Bluetooth Device             | 2         | 8%      |
| Intel Bluetooth Device                         | 2         | 8%      |
| Realtek  Bluetooth 4.2 Adapter                 | 1         | 4%      |
| Qualcomm Atheros AR9462 Bluetooth              | 1         | 4%      |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 1         | 4%      |
| IMC Networks Bluetooth Radio                   | 1         | 4%      |
| Broadcom BCM43142A0 Bluetooth 4.0              | 1         | 4%      |
| Broadcom BCM20702A0 Bluetooth 4.0              | 1         | 4%      |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 1         | 4%      |
| ASUS Broadcom BCM20702A0 Bluetooth             | 1         | 4%      |
| Apple Bluetooth Host Controller                | 1         | 4%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor    | Computers | Percent |
|-----------|-----------|---------|
| Intel     | 37        | 58.73%  |
| Nvidia    | 10        | 15.87%  |
| AMD       | 7         | 11.11%  |
| Lenovo    | 4         | 6.35%   |
| GN Netcom | 4         | 6.35%   |
| Unknown   | 1         | 1.59%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 7         | 9.59%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 5.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 5.48%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 4.11%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 4.11%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 4.11%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 2.74%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 2.74%   |
| Lenovo ThinkPad Dock USB Audio                                                                    | 2         | 2.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 2.74%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 2.74%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 2.74%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 2.74%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 2.74%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 2.74%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 2.74%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 2.74%   |
| Unknown Definitive Sym1                                                                           | 1         | 1.37%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 1.37%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.37%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 1.37%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 1.37%   |
| Nvidia GK110 High Definition Audio Controller                                                     | 1         | 1.37%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 1.37%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 1         | 1.37%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                                          | 1         | 1.37%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 1.37%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 1.37%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1         | 1.37%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.37%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 1.37%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 1.37%   |
| GN Netcom Jabra SPEAK 510                                                                         | 1         | 1.37%   |
| GN Netcom Jabra PRO 9470                                                                          | 1         | 1.37%   |
| GN Netcom Jabra Link 370                                                                          | 1         | 1.37%   |
| GN Netcom Jabra EVOLVE LINK                                                                       | 1         | 1.37%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.37%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 1.37%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.37%   |
| AMD High Definition Audio Controller                                                              | 1         | 1.37%   |
| AMD FCH Azalia Controller                                                                         | 1         | 1.37%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 1.37%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1         | 1.37%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 1.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Micron Technology   | 6         | 26.09%  |
| Samsung Electronics | 4         | 17.39%  |
| Kingston            | 4         | 17.39%  |
| SK hynix            | 3         | 13.04%  |
| Unknown             | 1         | 4.35%   |
| Smart               | 1         | 4.35%   |
| HPE                 | 1         | 4.35%   |
| Crucial             | 1         | 4.35%   |
| Corsair             | 1         | 4.35%   |
| Avant               | 1         | 4.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s           | 2         | 8.33%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                     | 1         | 4.17%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s           | 1         | 4.17%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 4.17%   |
| SK hynix RAM HMAA1GS6CMR8N-VK 8192MB Row Of Chips DDR4 2667MT/s | 1         | 4.17%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s    | 1         | 4.17%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 4.17%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s          | 1         | 4.17%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s     | 1         | 4.17%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s            | 1         | 4.17%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s           | 1         | 4.17%   |
| Micron RAM 18ASF2G72PDZ-2G3B1 16GB DIMM DDR4 2400MT/s           | 1         | 4.17%   |
| Micron RAM 16JTF1G64HZ-1G4D1 8GB SODIMM DDR3 1333MT/s           | 1         | 4.17%   |
| Micron RAM 16ATF2G64HZ-2G1A1 16384MB SODIMM DDR4 2133MT/s       | 1         | 4.17%   |
| Kingston RAM KX830D-ELC 4096MB SODIMM DDR3 1333MT/s             | 1         | 4.17%   |
| Kingston RAM KTW149-ELF 1GB DIMM DDR3 1333MT/s                  | 1         | 4.17%   |
| Kingston RAM KN2M64-ETB 8GB SODIMM DDR3 1600MT/s                | 1         | 4.17%   |
| Kingston RAM 9905471-006.A00LF 4GB DIMM DDR3 1333MT/s           | 1         | 4.17%   |
| Kingston RAM 9905403-892.A00LF 8GB DIMM DDR3 1333MT/s           | 1         | 4.17%   |
| HPE RAM 840756-091 16GB DIMM DDR4 2666MT/s                      | 1         | 4.17%   |
| Crucial RAM BLE8G4D34AEEAK.K8FB 8192MB DIMM DDR4 3466MT/s       | 1         | 4.17%   |
| Corsair RAM CMSX32GX4M2A2666C18 16GB SODIMM DDR4 2667MT/s       | 1         | 4.17%   |
| Avant RAM H6451U66G1600G 4096MB SODIMM DDR3 1600MT/s            | 1         | 4.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 11        | 50%     |
| DDR3   | 10        | 45.45%  |
| LPDDR4 | 1         | 4.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 14        | 63.64%  |
| DIMM         | 5         | 22.73%  |
| Row Of Chips | 3         | 13.64%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 10        | 43.48%  |
| 4096  | 7         | 30.43%  |
| 16384 | 4         | 17.39%  |
| 32768 | 1         | 4.35%   |
| 1024  | 1         | 4.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 6         | 27.27%  |
| 2667  | 5         | 22.73%  |
| 1333  | 4         | 18.18%  |
| 2400  | 2         | 9.09%   |
| 4267  | 1         | 4.55%   |
| 3466  | 1         | 4.55%   |
| 2666  | 1         | 4.55%   |
| 2133  | 1         | 4.55%   |
| 1866  | 1         | 4.55%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Samsung ML-1660 Series | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 120 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Chicony Electronics   | 8         | 30.77%  |
| IMC Networks          | 4         | 15.38%  |
| Suyin                 | 3         | 11.54%  |
| Logitech              | 3         | 11.54%  |
| Lite-On Technology    | 3         | 11.54%  |
| Realtek Semiconductor | 2         | 7.69%   |
| Microdia              | 2         | 7.69%   |
| Acer                  | 1         | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Chicony Integrated Camera               | 5         | 18.52%  |
| Microdia Webcam Vitade AF               | 2         | 7.41%   |
| Lite-On Integrated Camera               | 2         | 7.41%   |
| IMC Networks VGA UVC WebCam             | 2         | 7.41%   |
| IMC Networks Integrated Camera          | 2         | 7.41%   |
| Chicony Integrated Camera (1280x720@30) | 2         | 7.41%   |
| Suyin Integrated_Webcam_HD              | 1         | 3.7%    |
| Suyin HP Truevision HD                  | 1         | 3.7%    |
| Suyin Asus Integrated Webcam            | 1         | 3.7%    |
| Realtek Integrated_Webcam_HD            | 1         | 3.7%    |
| Realtek EasyCamera                      | 1         | 3.7%    |
| Logitech Webcam C920-C                  | 1         | 3.7%    |
| Logitech HD Webcam C615                 | 1         | 3.7%    |
| Logitech BRIO Ultra HD Webcam           | 1         | 3.7%    |
| Lite-On HP HD Camera                    | 1         | 3.7%    |
| Chicony ThinkPad T490 Webcam            | 1         | 3.7%    |
| Chicony Integrated IR Camera            | 1         | 3.7%    |
| Acer SunplusIT Integrated Camera        | 1         | 3.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 6         | 50%     |
| Validity Sensors           | 5         | 41.67%  |
| Shenzhen Goodix Technology | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 25%     |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 25%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 16.67%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 8.33%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 8.33%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 8.33%   |
| Unknown                                                                    | 1         | 8.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 83.33%  |
| Alcor Micro | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
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


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 19        | 42.22%  |
| 0     | 18        | 40%     |
| 2     | 6         | 13.33%  |
| 3     | 2         | 4.44%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 12        | 35.29%  |
| Chipcard                 | 5         | 14.71%  |
| Unassigned class         | 3         | 8.82%   |
| Graphics card            | 3         | 8.82%   |
| Bluetooth                | 3         | 8.82%   |
| Storage                  | 2         | 5.88%   |
| Net/wireless             | 2         | 5.88%   |
| Communication controller | 2         | 5.88%   |
| Card reader              | 2         | 5.88%   |

