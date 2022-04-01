Oracle Linux - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Oracle Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Oracle_Linux/Desktop/README.md) and [notebooks](/Dist/Oracle_Linux/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 70

| Vendor   | Model                       | Form-Factor | Probe                                                      | Date         |
|----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Lenovo   | Legion 5 15IMH05 82AU       | Notebook    | [2e24ad5259](https://linux-hardware.org/?probe=2e24ad5259) | Aug 19, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | Notebook    | [32ad696b97](https://linux-hardware.org/?probe=32ad696b97) | Aug 18, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | Notebook    | [2ccb1f7da2](https://linux-hardware.org/?probe=2ccb1f7da2) | Aug 16, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | Notebook    | [b2d5f563dc](https://linux-hardware.org/?probe=b2d5f563dc) | Aug 15, 2021 |
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
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | Notebook    | [20ac06d200](https://linux-hardware.org/?probe=20ac06d200) | Mar 06, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | Notebook    | [9f67379954](https://linux-hardware.org/?probe=9f67379954) | Mar 04, 2021 |
| Lenovo   | ThinkPad L490 20Q5CTO1WW    | Notebook    | [db0f24aee5](https://linux-hardware.org/?probe=db0f24aee5) | Mar 01, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | Notebook    | [f0c8352496](https://linux-hardware.org/?probe=f0c8352496) | Mar 01, 2021 |
| Dell     | Latitude 7410               | Notebook    | [5b725b01aa](https://linux-hardware.org/?probe=5b725b01aa) | Feb 26, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | Notebook    | [3145841279](https://linux-hardware.org/?probe=3145841279) | Feb 25, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | Notebook    | [835e8cad03](https://linux-hardware.org/?probe=835e8cad03) | Feb 25, 2021 |
| Dell     | Latitude 7410               | Notebook    | [430ac9fa0c](https://linux-hardware.org/?probe=430ac9fa0c) | Feb 24, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | Notebook    | [73aece12d7](https://linux-hardware.org/?probe=73aece12d7) | Feb 24, 2021 |
| Lenovo   | ThinkPad T490 20N3S77600    | Notebook    | [26e61c39f2](https://linux-hardware.org/?probe=26e61c39f2) | Feb 24, 2021 |
| Dell     | Latitude 7410               | Notebook    | [7aeb2cc674](https://linux-hardware.org/?probe=7aeb2cc674) | Feb 22, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | Notebook    | [58cdbf1ae1](https://linux-hardware.org/?probe=58cdbf1ae1) | Feb 18, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | Notebook    | [8af2c8d83c](https://linux-hardware.org/?probe=8af2c8d83c) | Feb 05, 2021 |
| ASUSTek  | G11CD                       | Desktop     | [13961e12a8](https://linux-hardware.org/?probe=13961e12a8) | Feb 01, 2021 |
| HP       | 158B                        | Desktop     | [5e6b9531d7](https://linux-hardware.org/?probe=5e6b9531d7) | Feb 01, 2021 |
| Dell     | Board                       | Desktop     | [bcd33a41f0](https://linux-hardware.org/?probe=bcd33a41f0) | Jan 25, 2021 |
| Gigabyte | X470 AORUS ULTRA GAMING-... | Desktop     | [71628a95b6](https://linux-hardware.org/?probe=71628a95b6) | Jan 13, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | Notebook    | [685b544c29](https://linux-hardware.org/?probe=685b544c29) | Jan 12, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | Notebook    | [68957c71fd](https://linux-hardware.org/?probe=68957c71fd) | Jan 07, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | Notebook    | [7d50d4e9d5](https://linux-hardware.org/?probe=7d50d4e9d5) | Jan 07, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | Notebook    | [7ea3c87bfe](https://linux-hardware.org/?probe=7ea3c87bfe) | Jan 06, 2021 |
| ASUSTek  | G11CD                       | Desktop     | [79f24a0a82](https://linux-hardware.org/?probe=79f24a0a82) | Dec 31, 2020 |
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
| Oracle Linux 8.3 | 12        | 28.57%  |
| Oracle Linux 8.5 | 9         | 21.43%  |
| Oracle Linux 8.4 | 7         | 16.67%  |
| Oracle Linux 8.1 | 3         | 7.14%   |
| Oracle Linux 7.7 | 3         | 7.14%   |
| Oracle Linux 8.2 | 2         | 4.76%   |
| Oracle Linux 7.8 | 2         | 4.76%   |
| Oracle Linux 7.6 | 2         | 4.76%   |
| Oracle Linux 7.9 | 1         | 2.38%   |
| Oracle Linux 7.4 | 1         | 2.38%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Oracle Linux | 36        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Computers | Percent |
|------------------------------------|-----------|---------|
| 5.4.17-2102.202.5.el8uek.x86_64    | 3         | 6.67%   |
| 5.4.17-2036.103.3.1.el8uek.x86_64  | 3         | 6.67%   |
| 4.18.0-348.12.2.el8_5.x86_64       | 3         | 6.67%   |
| 5.4.17-2136.304.4.3.el8uek.x86_64  | 2         | 4.44%   |
| 5.4.17-2102.205.7.3.el8uek.x86_64  | 2         | 4.44%   |
| 5.4.17-2102.204.4.2.el8uek.x86_64  | 2         | 4.44%   |
| 5.4.17-2102.200.13.el8uek.x86_64   | 2         | 4.44%   |
| 5.4.17-2036.102.0.2.el8uek.x86_64  | 2         | 4.44%   |
| 5.4.17-2036.101.2.el8uek.x86_64    | 2         | 4.44%   |
| 4.18.0-193.1.2.el8_2.x86_64        | 2         | 4.44%   |
| 4.18.0-147.3.1.el8_1.x86_64        | 2         | 4.44%   |
| 5.4.17-2136.305.5.2.el8uek.x86_64  | 1         | 2.22%   |
| 5.4.17-2136.301.1.4.el8uek.x86_64  | 1         | 2.22%   |
| 5.4.17-2102.201.3.el8uek.x86_64    | 1         | 2.22%   |
| 5.4.17-2036.104.4.el8uek.x86_64    | 1         | 2.22%   |
| 5.4.17-2036.100.6.1.el8uek.x86_64  | 1         | 2.22%   |
| 5.4.17-2011.0.7.el8uek.x86_64      | 1         | 2.22%   |
| 5.4.11-1.el7.elrepo.x86_64         | 1         | 2.22%   |
| 5.15.2-1.el8.elrepo.x86_64         | 1         | 2.22%   |
| 5.14.1-1.el8.elrepo.x86_64         | 1         | 2.22%   |
| 5.11.1-1.el8.elrepo.x86_64         | 1         | 2.22%   |
| 4.18.0-348.2.1.el8_5.x86_64        | 1         | 2.22%   |
| 4.18.0-240.15.1.el8_3.x86_64       | 1         | 2.22%   |
| 4.18.0-240.10.1.el8_3.x86_64       | 1         | 2.22%   |
| 4.14.35-2047.510.4.1.el7uek.x86_64 | 1         | 2.22%   |
| 4.14.35-1902.4.8.el7uek.x86_64     | 1         | 2.22%   |
| 4.14.35-1902.300.11.el7uek.x86_64  | 1         | 2.22%   |
| 4.14.35-1818.3.3.el7uek.x86_64     | 1         | 2.22%   |
| 3.10.0-957.21.2.el7.x86_64         | 1         | 2.22%   |
| 3.10.0-693.11.6.el7.x86_64         | 1         | 2.22%   |
| 3.10.0-1127.10.1.el7.x86_64        | 1         | 2.22%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.17  | 17        | 44.74%  |
| 4.18.0  | 10        | 26.32%  |
| 4.14.35 | 4         | 10.53%  |
| 3.10.0  | 3         | 7.89%   |
| 5.4.11  | 1         | 2.63%   |
| 5.15.2  | 1         | 2.63%   |
| 5.14.1  | 1         | 2.63%   |
| 5.11.1  | 1         | 2.63%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 18        | 47.37%  |
| 4.18    | 10        | 26.32%  |
| 4.14    | 4         | 10.53%  |
| 3.10    | 3         | 7.89%   |
| 5.15    | 1         | 2.63%   |
| 5.14    | 1         | 2.63%   |
| 5.11    | 1         | 2.63%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 36        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 25        | 65.79%  |
| Unknown       | 7         | 18.42%  |
| XFCE          | 2         | 5.26%   |
| MATE          | 2         | 5.26%   |
| KDE4          | 1         | 2.63%   |
| GNOME Classic | 1         | 2.63%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 17        | 44.74%  |
| Wayland | 17        | 44.74%  |
| Unknown | 4         | 10.53%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 23        | 62.16%  |
| GDM     | 13        | 35.14%  |
| TDM     | 1         | 2.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 18        | 48.65%  |
| en_GB      | 5         | 13.51%  |
| de_DE      | 4         | 10.81%  |
| Unknown    | 4         | 10.81%  |
| pt_BR      | 1         | 2.7%    |
| pl_PL      | 1         | 2.7%    |
| it_IT      | 1         | 2.7%    |
| en_US.UTF8 | 1         | 2.7%    |
| en_IN      | 1         | 2.7%    |
| en_AU      | 1         | 2.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 19        | 51.35%  |
| BIOS | 18        | 48.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Xfs     | 28        | 75.68%  |
| Ext4    | 7         | 18.92%  |
| Unknown | 2         | 5.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 23        | 62.16%  |
| GPT     | 9         | 24.32%  |
| MBR     | 5         | 13.51%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 33        | 91.67%  |
| Yes       | 3         | 8.33%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 35        | 97.22%  |
| Yes       | 1         | 2.78%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 14        | 38.89%  |
| Dell                | 7         | 19.44%  |
| Hewlett-Packard     | 4         | 11.11%  |
| ASUSTek Computer    | 4         | 11.11%  |
| Gigabyte Technology | 3         | 8.33%   |
| Standard            | 1         | 2.78%   |
| HPE                 | 1         | 2.78%   |
| Foxconn             | 1         | 2.78%   |
| Apple               | 1         | 2.78%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Lenovo ThinkPad T450 20BUS14900           | 2         | 5.56%   |
| ASUS X510UR                               | 2         | 5.56%   |
| Standard BW Series                        | 1         | 2.78%   |
| Lenovo ThinkPad X390 Yoga 20NQS2SF00      | 1         | 2.78%   |
| Lenovo ThinkPad X280 20KES4H34G           | 1         | 2.78%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QWS1R800 | 1         | 2.78%   |
| Lenovo ThinkPad T490 20N3S77600           | 1         | 2.78%   |
| Lenovo ThinkPad T480 20L6S56Y2X           | 1         | 2.78%   |
| Lenovo ThinkPad T480 20L5A07TAU           | 1         | 2.78%   |
| Lenovo ThinkPad L540 20AVCTO1WW           | 1         | 2.78%   |
| Lenovo ThinkPad L490 20Q5CTO1WW           | 1         | 2.78%   |
| Lenovo Legion 5 15IMH05 82AU              | 1         | 2.78%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS       | 1         | 2.78%   |
| Lenovo IdeaPad C340-14IWL 81RL            | 1         | 2.78%   |
| Lenovo IdeaPad 300-15ISK 80RS             | 1         | 2.78%   |
| HPE ProLiant BL460c Gen10                 | 1         | 2.78%   |
| HP ZBook 15                               | 1         | 2.78%   |
| HP Z820 Workstation                       | 1         | 2.78%   |
| HP ProBook 445 G6                         | 1         | 2.78%   |
| HP Notebook                               | 1         | 2.78%   |
| Gigabyte Z490 AORUS ELITE AC              | 1         | 2.78%   |
| Gigabyte X99-Designare EX-CF              | 1         | 2.78%   |
| Gigabyte X470 AORUS ULTRA GAMING          | 1         | 2.78%   |
| Foxconn p6-2400el                         | 1         | 2.78%   |
| Dell PowerEdge FC630                      | 1         | 2.78%   |
| Dell OptiPlex 980                         | 1         | 2.78%   |
| Dell OptiPlex 7060                        | 1         | 2.78%   |
| Dell Latitude E6420                       | 1         | 2.78%   |
| Dell Latitude 7420                        | 1         | 2.78%   |
| Dell Latitude 7410                        | 1         | 2.78%   |
| Dell Inspiron 3542                        | 1         | 2.78%   |
| ASUS UX305FA                              | 1         | 2.78%   |
| ASUS G11CD                                | 1         | 2.78%   |
| Apple Macmini7,1                          | 1         | 2.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 10        | 27.78%  |
| Lenovo IdeaPad         | 3         | 8.33%   |
| Dell Latitude          | 3         | 8.33%   |
| Dell OptiPlex          | 2         | 5.56%   |
| ASUS X510UR            | 2         | 5.56%   |
| Standard BW            | 1         | 2.78%   |
| Lenovo Legion          | 1         | 2.78%   |
| HPE ProLiant           | 1         | 2.78%   |
| HP ZBook               | 1         | 2.78%   |
| HP Z820                | 1         | 2.78%   |
| HP ProBook             | 1         | 2.78%   |
| HP Notebook            | 1         | 2.78%   |
| Gigabyte Z490          | 1         | 2.78%   |
| Gigabyte X99-Designare | 1         | 2.78%   |
| Gigabyte X470          | 1         | 2.78%   |
| Foxconn p6-2400el      | 1         | 2.78%   |
| Dell PowerEdge         | 1         | 2.78%   |
| Dell Inspiron          | 1         | 2.78%   |
| ASUS UX305FA           | 1         | 2.78%   |
| ASUS G11CD             | 1         | 2.78%   |
| Apple Macmini7         | 1         | 2.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 9         | 25%     |
| 2018 | 6         | 16.67%  |
| 2020 | 4         | 11.11%  |
| 2016 | 4         | 11.11%  |
| 2015 | 3         | 8.33%   |
| 2014 | 3         | 8.33%   |
| 2017 | 2         | 5.56%   |
| 2012 | 2         | 5.56%   |
| 2013 | 1         | 2.78%   |
| 2011 | 1         | 2.78%   |
| 2010 | 1         | 2.78%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 23        | 63.89%  |
| Desktop     | 9         | 25%     |
| Convertible | 2         | 5.56%   |
| Mini pc     | 1         | 2.78%   |
| Server      | 1         | 2.78%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 34        | 94.44%  |
| Enabled  | 2         | 5.56%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 36        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 10        | 27.03%  |
| 4.01-8.0        | 8         | 21.62%  |
| 32.01-64.0      | 8         | 21.62%  |
| 16.01-24.0      | 4         | 10.81%  |
| 3.01-4.0        | 3         | 8.11%   |
| 64.01-256.0     | 2         | 5.41%   |
| More than 256.0 | 1         | 2.7%    |
| 1.01-2.0        | 1         | 2.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 12        | 27.91%  |
| 2.01-3.0   | 11        | 25.58%  |
| 8.01-16.0  | 7         | 16.28%  |
| 3.01-4.0   | 5         | 11.63%  |
| 1.01-2.0   | 5         | 11.63%  |
| 16.01-24.0 | 1         | 2.33%   |
| 0.51-1.0   | 1         | 2.33%   |
| 0.01-0.5   | 1         | 2.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 29        | 80.56%  |
| 2      | 4         | 11.11%  |
| 3      | 2         | 5.56%   |
| 5      | 1         | 2.78%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 26        | 72.22%  |
| Yes       | 10        | 27.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 80.56%  |
| No        | 7         | 19.44%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 80.56%  |
| No        | 7         | 19.44%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 23        | 62.16%  |
| No        | 14        | 37.84%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 10        | 27.03%  |
| Germany     | 7         | 18.92%  |
| UK          | 4         | 10.81%  |
| Brazil      | 3         | 8.11%   |
| Romania     | 2         | 5.41%   |
| Netherlands | 2         | 5.41%   |
| Russia      | 1         | 2.7%    |
| Poland      | 1         | 2.7%    |
| Pakistan    | 1         | 2.7%    |
| Kazakhstan  | 1         | 2.7%    |
| Italy       | 1         | 2.7%    |
| India       | 1         | 2.7%    |
| Bulgaria    | 1         | 2.7%    |
| Australia   | 1         | 2.7%    |
| Argentina   | 1         | 2.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Seattle          | 2         | 5.13%   |
| Colorado Springs | 2         | 5.13%   |
| Bucharest        | 2         | 5.13%   |
| Berlin           | 2         | 5.13%   |
| Utrecht          | 1         | 2.56%   |
| Sofia            | 1         | 2.56%   |
| Siegen           | 1         | 2.56%   |
| Shrewsbury       | 1         | 2.56%   |
| Sao Paulo        | 1         | 2.56%   |
| Santo AndrÃ©   | 1         | 2.56%   |
| San Francisco    | 1         | 2.56%   |
| Rheinstetten     | 1         | 2.56%   |
| Reading          | 1         | 2.56%   |
| Port Saint Lucie | 1         | 2.56%   |
| Polch            | 1         | 2.56%   |
| Moscow           | 1         | 2.56%   |
| Milan            | 1         | 2.56%   |
| Maple Valley     | 1         | 2.56%   |
| London           | 1         | 2.56%   |
| Kreuztal         | 1         | 2.56%   |
| Karaganda        | 1         | 2.56%   |
| Karachi          | 1         | 2.56%   |
| Ituzaingo        | 1         | 2.56%   |
| Freudenberg      | 1         | 2.56%   |
| Eppelheim        | 1         | 2.56%   |
| Dietmannsried    | 1         | 2.56%   |
| Dallas           | 1         | 2.56%   |
| ChorzÃ³w       | 1         | 2.56%   |
| Chicago          | 1         | 2.56%   |
| Canberra         | 1         | 2.56%   |
| Campinas         | 1         | 2.56%   |
| Bracknell        | 1         | 2.56%   |
| Bengaluru        | 1         | 2.56%   |
| Asheville        | 1         | 2.56%   |
| Amsterdam        | 1         | 2.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 11        | 14     | 26.19%  |
| Seagate                 | 6         | 43     | 14.29%  |
| SanDisk                 | 6         | 7      | 14.29%  |
| WDC                     | 3         | 3      | 7.14%   |
| Unknown                 | 2         | 2      | 4.76%   |
| Union Memory (Shenzhen) | 1         | 2      | 2.38%   |
| Toshiba                 | 1         | 1      | 2.38%   |
| SK Hynix                | 1         | 1      | 2.38%   |
| Phison                  | 1         | 1      | 2.38%   |
| Micron Technology       | 1         | 4      | 2.38%   |
| Lite-On                 | 1         | 1      | 2.38%   |
| Lenovo                  | 1         | 1      | 2.38%   |
| Kingston                | 1         | 5      | 2.38%   |
| Intel                   | 1         | 1      | 2.38%   |
| HPE                     | 1         | 1      | 2.38%   |
| HGST                    | 1         | 1      | 2.38%   |
| Hewlett-Packard         | 1         | 1      | 2.38%   |
| Crucial                 | 1         | 1      | 2.38%   |
| Apple                   | 1         | 1      | 2.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seagate ST2000DM008-2FR102 2TB               | 2         | 4.44%   |
| SanDisk SSD PLUS 1000GB                      | 2         | 4.44%   |
| Samsung SSD PM830 2.5 7mm 256GB              | 2         | 4.44%   |
| WDC WDS500G2B0A-00SM50 500GB SSD             | 1         | 2.22%   |
| WDC WD10JPCX-24UE4T0 1TB                     | 1         | 2.22%   |
| WDC WD10EZEX-60M2NA0 1TB                     | 1         | 2.22%   |
| Unknown SD/MMC/MS PRO 32GB                   | 1         | 2.22%   |
| Unknown MMC Card  256GB                      | 1         | 2.22%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 2.22%   |
| Toshiba NVMe SSD Drive 512GB                 | 1         | 2.22%   |
| SK Hynix SKHynix_HFS256GD9TNG-L3A0B 256GB    | 1         | 2.22%   |
| Seagate ST8000VN004-2M2101 8TB               | 1         | 2.22%   |
| Seagate ST3500414CS 500GB                    | 1         | 2.22%   |
| Seagate ST2000NX0253 2TB                     | 1         | 2.22%   |
| Seagate ST1000NX0423 1TB                     | 1         | 2.22%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 2.22%   |
| SanDisk SDSSDH3512G 512GB                    | 1         | 2.22%   |
| SanDisk SD7SN3Q256G1002 256GB SSD            | 1         | 2.22%   |
| SanDisk SD6SB1M-256G-1006 256GB SSD          | 1         | 2.22%   |
| Sandisk NVMe SSD Drive 512GB                 | 1         | 2.22%   |
| Samsung SSD 960 EVO 250GB                    | 1         | 2.22%   |
| Samsung SSD 850 PRO 256GB                    | 1         | 2.22%   |
| Samsung PM9A1 NVMe 512GB                     | 1         | 2.22%   |
| Samsung NVMe SSD Drive 512GB                 | 1         | 2.22%   |
| Samsung MZVLW256HEHP-000L7 256GB             | 1         | 2.22%   |
| Samsung MZVLB1T0HBLR-000L7 1TB               | 1         | 2.22%   |
| Samsung MZ7LN512HMJP-000L7 512GB SSD         | 1         | 2.22%   |
| Samsung MZ7LN512HCHP-000L1 512GB SSD         | 1         | 2.22%   |
| Samsung MZ7LN256HCHP-000L7 256GB SSD         | 1         | 2.22%   |
| Samsung HD502IJ 500GB                        | 1         | 2.22%   |
| Phison NVMe SSD Drive 1TB                    | 1         | 2.22%   |
| Micron NVMe SSD Drive 256GB                  | 1         | 2.22%   |
| Micron 2200S NVMe 256GB                      | 1         | 2.22%   |
| Lite-On NVMe SSD Drive 512GB                 | 1         | 2.22%   |
| Lenovo LENSE30512GMSP34MEAT3TA 512GB         | 1         | 2.22%   |
| Kingston NVMe SSD Drive 1TB                  | 1         | 2.22%   |
| Intel SSDPEKKF256G8L 256GB                   | 1         | 2.22%   |
| HPE LOGICAL VOLUME 240GB SSD                 | 1         | 2.22%   |
| HGST HTS545050A7E380 500GB                   | 1         | 2.22%   |
| HP SSD S700 120GB                            | 1         | 2.22%   |
| Crucial CT500MX500SSD1 500GB                 | 1         | 2.22%   |
| Apple HDD HTS541010A9E662 1TB                | 1         | 2.22%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 43     | 50%     |
| WDC                 | 2         | 2      | 16.67%  |
| Unknown             | 1         | 1      | 8.33%   |
| Samsung Electronics | 1         | 1      | 8.33%   |
| HGST                | 1         | 1      | 8.33%   |
| Apple               | 1         | 1      | 8.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 6      | 40%     |
| SanDisk             | 5         | 5      | 33.33%  |
| WDC                 | 1         | 1      | 6.67%   |
| HPE                 | 1         | 1      | 6.67%   |
| Hewlett-Packard     | 1         | 1      | 6.67%   |
| Crucial             | 1         | 1      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 15        | 26     | 35.71%  |
| SSD  | 15        | 15     | 35.71%  |
| HDD  | 11        | 49     | 26.19%  |
| MMC  | 1         | 1      | 2.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 23        | 62     | 56.1%   |
| NVMe | 15        | 26     | 36.59%  |
| SAS  | 2         | 2      | 4.88%   |
| MMC  | 1         | 1      | 2.44%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 13        | 14     | 48.15%  |
| 0.51-1.0   | 10        | 11     | 37.04%  |
| 1.01-2.0   | 3         | 37     | 11.11%  |
| 4.01-10.0  | 1         | 2      | 3.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 8         | 21.62%  |
| 101-250        | 7         | 18.92%  |
| Unknown        | 7         | 18.92%  |
| 1-20           | 5         | 13.51%  |
| 501-1000       | 5         | 13.51%  |
| More than 3000 | 1         | 2.7%    |
| 21-50          | 1         | 2.7%    |
| 2001-3000      | 1         | 2.7%    |
| 1001-2000      | 1         | 2.7%    |
| 51-100         | 1         | 2.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 15        | 39.47%  |
| Unknown        | 7         | 18.42%  |
| 21-50          | 6         | 15.79%  |
| 101-250        | 4         | 10.53%  |
| 51-100         | 3         | 7.89%   |
| 251-500        | 2         | 5.26%   |
| More than 3000 | 1         | 2.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 50%     |
| Hewlett-Packard SSD S700 120GB     | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| Seagate         | 1         | 1      | 50%     |
| Hewlett-Packard | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1         | 1      | 50%     |
| HDD  | 1         | 1      | 50%     |

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
| Detected | 22        | 38     | 57.89%  |
| Works    | 14        | 51     | 36.84%  |
| Malfunc  | 2         | 2      | 5.26%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 23        | 52.27%  |
| Samsung Electronics          | 5         | 11.36%  |
| AMD                          | 4         | 9.09%   |
| Broadcom / LSI               | 2         | 4.55%   |
| Union Memory (Shenzhen)      | 1         | 2.27%   |
| Toshiba America Info Systems | 1         | 2.27%   |
| SK Hynix                     | 1         | 2.27%   |
| Sandisk                      | 1         | 2.27%   |
| Phison Electronics           | 1         | 2.27%   |
| Micron Technology            | 1         | 2.27%   |
| Lite-On Technology           | 1         | 2.27%   |
| Lenovo                       | 1         | 2.27%   |
| Kingston Technology Company  | 1         | 2.27%   |
| Adaptec                      | 1         | 2.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 4         | 8.16%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 6.12%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 3         | 6.12%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 4.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 4.08%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 2         | 4.08%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 2         | 4.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 4.08%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 4.08%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 2.04%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 2.04%   |
| SK Hynix Non-Volatile memory controller                                          | 1         | 2.04%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 2.04%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 2.04%   |
| Phison E12 NVMe Controller                                                       | 1         | 2.04%   |
| Micron Non-Volatile memory controller                                            | 1         | 2.04%   |
| Lite-On Non-Volatile memory controller                                           | 1         | 2.04%   |
| Lenovo Non-Volatile memory controller                                            | 1         | 2.04%   |
| Kingston Company A2000 NVMe SSD                                                  | 1         | 2.04%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1         | 2.04%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 2.04%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 2.04%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 2.04%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 2.04%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1         | 2.04%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                              | 1         | 2.04%   |
| Intel C600/X79 series chipset SATA RAID Controller                               | 1         | 2.04%   |
| Intel C600/X79 series chipset IDE-r Controller                                   | 1         | 2.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 2.04%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 1         | 2.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 1         | 2.04%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 1         | 2.04%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                              | 1         | 2.04%   |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                     | 1         | 2.04%   |
| AMD 400 Series Chipset SATA Controller                                           | 1         | 2.04%   |
| Adaptec Smart Storage PQI SAS                                                    | 1         | 2.04%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 23        | 51.11%  |
| NVMe | 15        | 33.33%  |
| RAID | 4         | 8.89%   |
| SAS  | 2         | 4.44%   |
| IDE  | 1         | 2.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 32        | 88.89%  |
| AMD    | 4         | 11.11%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-8665U CPU @ 1.90GHz               | 2         | 5.56%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 2         | 5.56%   |
| Intel Core i5-8350U CPU @ 1.70GHz               | 2         | 5.56%   |
| Intel Core i5-5300U CPU @ 2.30GHz               | 2         | 5.56%   |
| Intel Xeon Silver 4114 CPU @ 2.20GHz            | 1         | 2.78%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz             | 1         | 2.78%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz             | 1         | 2.78%   |
| Intel Processor 5Y10 CPU @ 0.80GHz              | 1         | 2.78%   |
| Intel Pentium CPU G2020 @ 2.90GHz               | 1         | 2.78%   |
| Intel Core i9-9880H CPU @ 2.30GHz               | 1         | 2.78%   |
| Intel Core i9-10900K CPU @ 3.70GHz              | 1         | 2.78%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 1         | 2.78%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 2.78%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 1         | 2.78%   |
| Intel Core i7-6800K CPU @ 3.40GHz               | 1         | 2.78%   |
| Intel Core i7-6700 CPU @ 3.40GHz                | 1         | 2.78%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 1         | 2.78%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz              | 1         | 2.78%   |
| Intel Core i7-2760QM CPU @ 2.40GHz              | 1         | 2.78%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 1         | 2.78%   |
| Intel Core i7-10610U CPU @ 1.80GHz              | 1         | 2.78%   |
| Intel Core i5-8365U CPU @ 1.60GHz               | 1         | 2.78%   |
| Intel Core i5-4278U CPU @ 2.60GHz               | 1         | 2.78%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 1         | 2.78%   |
| Intel Core i5-4210M CPU @ 2.60GHz               | 1         | 2.78%   |
| Intel Core i3 CPU 550 @ 3.20GHz                 | 1         | 2.78%   |
| Intel Celeron CPU N3010 @ 1.04GHz               | 1         | 2.78%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz         | 1         | 2.78%   |
| AMD Ryzen 7 PRO 2700U w/ Radeon Vega Mobile Gfx | 1         | 2.78%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 1         | 2.78%   |
| AMD A9-9420e RADEON R5, 5 COMPUTE CORES 2C+3G   | 1         | 2.78%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics     | 1         | 2.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i7     | 14        | 38.89%  |
| Intel Core i5     | 8         | 22.22%  |
| Other             | 3         | 8.33%   |
| Intel Xeon        | 2         | 5.56%   |
| Intel Core i9     | 2         | 5.56%   |
| Intel Xeon Silver | 1         | 2.78%   |
| Intel Pentium     | 1         | 2.78%   |
| Intel Core i3     | 1         | 2.78%   |
| Intel Celeron     | 1         | 2.78%   |
| AMD Ryzen 7 PRO   | 1         | 2.78%   |
| AMD Ryzen 7       | 1         | 2.78%   |
| AMD A8            | 1         | 2.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 13        | 36.11%  |
| 2      | 13        | 36.11%  |
| 6      | 3         | 8.33%   |
| 16     | 2         | 5.56%   |
| 8      | 2         | 5.56%   |
| 20     | 1         | 2.78%   |
| 10     | 1         | 2.78%   |
| 1      | 1         | 2.78%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 33        | 91.67%  |
| 2      | 3         | 8.33%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 31        | 86.11%  |
| 1      | 5         | 13.89%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 35        | 94.59%  |
| Unknown        | 2         | 5.41%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806ec    | 5         | 13.89%  |
| 0x806ea    | 3         | 8.33%   |
| 0x306d4    | 3         | 8.33%   |
| Unknown    | 3         | 8.33%   |
| 0x40651    | 2         | 5.56%   |
| 0x306c3    | 2         | 5.56%   |
| 0xa0655    | 1         | 2.78%   |
| 0xa0652    | 1         | 2.78%   |
| 0x906ed    | 1         | 2.78%   |
| 0x906ea    | 1         | 2.78%   |
| 0x806c1    | 1         | 2.78%   |
| 0x506e3    | 1         | 2.78%   |
| 0x50654    | 1         | 2.78%   |
| 0x406f1    | 1         | 2.78%   |
| 0x406e3    | 1         | 2.78%   |
| 0x406c4    | 1         | 2.78%   |
| 0x306e4    | 1         | 2.78%   |
| 0x306a9    | 1         | 2.78%   |
| 0x206a7    | 1         | 2.78%   |
| 0x20655    | 1         | 2.78%   |
| 0x0810100b | 1         | 2.78%   |
| 0x0800820d | 1         | 2.78%   |
| 0x07030105 | 1         | 2.78%   |
| 0x06006705 | 1         | 2.78%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 12        | 33.33%  |
| Broadwell   | 5         | 13.89%  |
| Haswell     | 4         | 11.11%  |
| Skylake     | 3         | 8.33%   |
| IvyBridge   | 2         | 5.56%   |
| CometLake   | 2         | 5.56%   |
| Zen+        | 1         | 2.78%   |
| Zen         | 1         | 2.78%   |
| Westmere    | 1         | 2.78%   |
| TigerLake   | 1         | 2.78%   |
| Silvermont  | 1         | 2.78%   |
| SandyBridge | 1         | 2.78%   |
| Puma        | 1         | 2.78%   |
| Excavator   | 1         | 2.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 25        | 58.14%  |
| Nvidia                     | 12        | 27.91%  |
| AMD                        | 4         | 9.3%    |
| Matrox Electronics Systems | 2         | 4.65%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 9.3%    |
| Intel UHD Graphics 620                                                                   | 3         | 6.98%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 4.65%   |
| Intel HD Graphics 620                                                                    | 2         | 4.65%   |
| Intel HD Graphics 5500                                                                   | 2         | 4.65%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 4.65%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 4.65%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 2.33%   |
| Nvidia TU117M                                                                            | 1         | 2.33%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1         | 2.33%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1         | 2.33%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 2.33%   |
| Nvidia GM204 [GeForce GTX 980]                                                           | 1         | 2.33%   |
| Nvidia GK208GLM [Quadro K610M]                                                           | 1         | 2.33%   |
| Nvidia GK110GL [Quadro K6000]                                                            | 1         | 2.33%   |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 2.33%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 2.33%   |
| Matrox Electronics Systems MGA G200eH3                                                   | 1         | 2.33%   |
| Matrox Electronics Systems G200eR2                                                       | 1         | 2.33%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 2.33%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 2.33%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 2.33%   |
| Intel HD Graphics 5300                                                                   | 1         | 2.33%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 2.33%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 2.33%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 2.33%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 2.33%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 2.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.33%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 2.33%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 2.33%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 2.33%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 2.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 18        | 50%     |
| 1 x Nvidia     | 7         | 19.44%  |
| Intel + Nvidia | 5         | 13.89%  |
| 1 x AMD        | 3         | 8.33%   |
| 1 x Matrox     | 2         | 5.56%   |
| Intel + AMD    | 1         | 2.78%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 32        | 88.89%  |
| Proprietary | 3         | 8.33%   |
| Unknown     | 1         | 2.78%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 56.76%  |
| 1.01-2.0   | 6         | 16.22%  |
| 3.01-4.0   | 5         | 13.51%  |
| 0.01-0.5   | 2         | 5.41%   |
| 5.01-6.0   | 1         | 2.7%    |
| 8.01-16.0  | 1         | 2.7%    |
| 0.51-1.0   | 1         | 2.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 8         | 17.02%  |
| LG Display           | 7         | 14.89%  |
| Chimei Innolux       | 5         | 10.64%  |
| Samsung Electronics  | 4         | 8.51%   |
| Lenovo               | 4         | 8.51%   |
| Dell                 | 4         | 8.51%   |
| BenQ                 | 3         | 6.38%   |
| Hewlett-Packard      | 2         | 4.26%   |
| BOE                  | 2         | 4.26%   |
| ViewSonic            | 1         | 2.13%   |
| Sony                 | 1         | 2.13%   |
| InfoVision           | 1         | 2.13%   |
| Goldstar             | 1         | 2.13%   |
| Element              | 1         | 2.13%   |
| Eizo                 | 1         | 2.13%   |
| ASUSTek Computer     | 1         | 2.13%   |
| Ancor Communications | 1         | 2.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 2         | 4.17%   |
| BenQ GL2760 BNQ78D5 1920x1080 598x336mm 27.0-inch                     | 2         | 4.17%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch         | 2         | 4.17%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x174mm 14.0-inch        | 2         | 4.17%   |
| ViewSonic VX2433wm VSC3822 1920x1080 520x290mm 23.4-inch              | 1         | 2.08%   |
| Sony TV SNY4502 1920x1080                                             | 1         | 2.08%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch   | 1         | 2.08%   |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch     | 1         | 2.08%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 340x190mm 15.3-inch | 1         | 2.08%   |
| Samsung Electronics LCD Monitor S24C650                               | 1         | 2.08%   |
| LG Display LCD Monitor LGD0609 1920x1080 309x174mm 14.0-inch          | 1         | 2.08%   |
| LG Display LCD Monitor LGD04BD 1366x768 344x194mm 15.5-inch           | 1         | 2.08%   |
| LG Display LCD Monitor LGD047C 1366x768 310x174mm 14.0-inch           | 1         | 2.08%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch           | 1         | 2.08%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch           | 1         | 2.08%   |
| Lenovo T24i-10 LEN61A6 1920x1080 530x300mm 24.0-inch                  | 1         | 2.08%   |
| Lenovo LEN T2424pA LEN60C8 1920x1080 527x296mm 23.8-inch              | 1         | 2.08%   |
| Lenovo LEN T2254pC LEN60CC 1680x1050 474x296mm 22.0-inch              | 1         | 2.08%   |
| Lenovo LEN P27u-10 LEN61B0 3840x2160 600x340mm 27.2-inch              | 1         | 2.08%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 1         | 2.08%   |
| Hewlett-Packard Z24i HWP309E 1920x1200 518x324mm 24.1-inch            | 1         | 2.08%   |
| Hewlett-Packard E273q HPN3474 2560x1440 597x336mm 27.0-inch           | 1         | 2.08%   |
| Goldstar E2240 GSM57A3 1920x1080 477x268mm 21.5-inch                  | 1         | 2.08%   |
| Element T430QVN02.1 ELE6586 3840x2160 708x398mm 32.0-inch             | 1         | 2.08%   |
| Eizo EV2460 ENC3129 1920x1080 528x297mm 23.9-inch                     | 1         | 2.08%   |
| Dell U2718Q DELA0E9 3840x2160 609x349mm 27.6-inch                     | 1         | 2.08%   |
| Dell P2722H DEL4240 1920x1080 598x336mm 27.0-inch                     | 1         | 2.08%   |
| Dell P2719H DEL4184 1920x1080 598x336mm 27.0-inch                     | 1         | 2.08%   |
| Dell LCD Monitor U2415 3840x1200                                      | 1         | 2.08%   |
| Dell IDRAC DEL0001 1280x1024                                          | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 340x190mm 15.3-inch      | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN14E8 1920x1080 309x173mm 13.9-inch      | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN1387 1920x1080 293x165mm 13.2-inch      | 1         | 2.08%   |
| BOE LCD Monitor BOE08E8 1920x1080 344x194mm 15.5-inch                 | 1         | 2.08%   |
| BOE LCD Monitor BOE074F 1920x1080 309x173mm 13.9-inch                 | 1         | 2.08%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO212D 1920x1080 293x165mm 13.2-inch        | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO106D 1920x1080 276x155mm 12.5-inch        | 1         | 2.08%   |
| ASUSTek Computer VP249 AUS24AF 1920x1080 527x296mm 23.8-inch          | 1         | 2.08%   |
| Ancor Communications VW246 ACI24F2 1920x1080 531x299mm 24.0-inch      | 1         | 2.08%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 21        | 55.26%  |
| 1366x768 (WXGA)    | 4         | 10.53%  |
| 3840x2160 (4K)     | 3         | 7.89%   |
| 1600x900 (HD+)     | 3         | 7.89%   |
| 3840x1200          | 1         | 2.63%   |
| 2560x1440 (QHD)    | 1         | 2.63%   |
| 1920x1200 (WUXGA)  | 1         | 2.63%   |
| 1680x1050 (WSXGA+) | 1         | 2.63%   |
| 1360x768           | 1         | 2.63%   |
| 1280x1024 (SXGA)   | 1         | 2.63%   |
| Unknown            | 1         | 2.63%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 9         | 20%     |
| 14      | 9         | 20%     |
| 27      | 6         | 13.33%  |
| 24      | 5         | 11.11%  |
| 13      | 5         | 11.11%  |
| 23      | 3         | 6.67%   |
| Unknown | 2         | 4.44%   |
| 72      | 1         | 2.22%   |
| 32      | 1         | 2.22%   |
| 22      | 1         | 2.22%   |
| 21      | 1         | 2.22%   |
| 18      | 1         | 2.22%   |
| 12      | 1         | 2.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 21        | 47.73%  |
| 501-600     | 12        | 27.27%  |
| 401-500     | 3         | 6.82%   |
| 201-300     | 3         | 6.82%   |
| Unknown     | 2         | 4.55%   |
| 701-800     | 1         | 2.27%   |
| 601-700     | 1         | 2.27%   |
| 1501-2000   | 1         | 2.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 30        | 88.24%  |
| 16/10   | 2         | 5.88%   |
| 5/4     | 1         | 2.94%   |
| Unknown | 1         | 2.94%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 12        | 27.27%  |
| 101-110        | 9         | 20.45%  |
| 201-250        | 8         | 18.18%  |
| 301-350        | 6         | 13.64%  |
| 71-80          | 2         | 4.55%   |
| Unknown        | 2         | 4.55%   |
| More than 1000 | 1         | 2.27%   |
| 61-70          | 1         | 2.27%   |
| 351-500        | 1         | 2.27%   |
| 251-300        | 1         | 2.27%   |
| 141-150        | 1         | 2.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 18        | 41.86%  |
| 51-100  | 12        | 27.91%  |
| 101-120 | 6         | 13.95%  |
| 161-240 | 4         | 9.3%    |
| Unknown | 2         | 4.65%   |
| 1-50    | 1         | 2.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 23        | 63.89%  |
| 2     | 8         | 22.22%  |
| 3     | 2         | 5.56%   |
| 0     | 2         | 5.56%   |
| 4     | 1         | 2.78%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 26        | 50.98%  |
| Realtek Semiconductor | 12        | 23.53%  |
| Broadcom              | 4         | 7.84%   |
| Qualcomm Atheros      | 3         | 5.88%   |
| Lenovo                | 2         | 3.92%   |
| Ralink Technology     | 1         | 1.96%   |
| NetGear               | 1         | 1.96%   |
| FIBOCOM               | 1         | 1.96%   |
| Broadcom Limited      | 1         | 1.96%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5         | 7.35%   |
| Intel Wireless 8265 / 8275                                        | 5         | 7.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 4.41%   |
| Intel Wireless 7265                                               | 3         | 4.41%   |
| Intel Ethernet Connection (6) I219-LM                             | 3         | 4.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 2.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 2.94%   |
| Intel Wireless 7260                                               | 2         | 2.94%   |
| Intel I211 Gigabit Network Connection                             | 2         | 2.94%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 2.94%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.94%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 2.94%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 2.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 2.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.94%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 1.47%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.47%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 1.47%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.47%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 1.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.47%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                   | 1         | 1.47%   |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 1.47%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 1.47%   |
| Intel Wireless-AC 9260                                            | 1         | 1.47%   |
| Intel Wireless 8260                                               | 1         | 1.47%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.47%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 1.47%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.47%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.47%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.47%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.47%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 1.47%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.47%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1         | 1.47%   |
| Intel 82599 10 Gigabit Dual Port Backplane Connection             | 1         | 1.47%   |
| Intel 82578DM Gigabit Network Connection                          | 1         | 1.47%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.47%   |
| FIBOCOM L830-EB                                                   | 1         | 1.47%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 1         | 1.47%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.47%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 1         | 1.47%   |
| Broadcom BCM57840 NetXtreme II 10/20-Gigabit Ethernet             | 1         | 1.47%   |
| Broadcom BCM43142 802.11b/g/n                                     | 1         | 1.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 21        | 65.63%  |
| Realtek Semiconductor | 3         | 9.38%   |
| Qualcomm Atheros      | 3         | 9.38%   |
| Ralink Technology     | 1         | 3.13%   |
| NetGear               | 1         | 3.13%   |
| FIBOCOM               | 1         | 3.13%   |
| Broadcom Limited      | 1         | 3.13%   |
| Broadcom              | 1         | 3.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                 | 5         | 15.63%  |
| Intel Wireless 7265                                        | 3         | 9.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 2         | 6.25%   |
| Intel Wireless 7260                                        | 2         | 6.25%   |
| Intel Comet Lake PCH CNVi WiFi                             | 2         | 6.25%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                   | 2         | 6.25%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1         | 3.13%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter   | 1         | 3.13%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 1         | 3.13%   |
| Ralink MT7601U Wireless Adapter                            | 1         | 3.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1         | 3.13%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]            | 1         | 3.13%   |
| Intel Wireless-AC 9260                                     | 1         | 3.13%   |
| Intel Wireless 8260                                        | 1         | 3.13%   |
| Intel Wi-Fi 6 AX201                                        | 1         | 3.13%   |
| Intel Wi-Fi 6 AX200                                        | 1         | 3.13%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth            | 1         | 3.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 1         | 3.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]               | 1         | 3.13%   |
| FIBOCOM L830-EB                                            | 1         | 3.13%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter | 1         | 3.13%   |
| Broadcom BCM43142 802.11b/g/n                              | 1         | 3.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 18        | 52.94%  |
| Realtek Semiconductor | 11        | 32.35%  |
| Broadcom              | 3         | 8.82%   |
| Lenovo                | 2         | 5.88%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5         | 13.89%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 8.33%   |
| Intel Ethernet Connection (6) I219-LM                             | 3         | 8.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 5.56%   |
| Intel I211 Gigabit Network Connection                             | 2         | 5.56%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 5.56%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 5.56%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 5.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 5.56%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 2.78%   |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 2.78%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 2.78%   |
| Intel Ethernet Connection I217-V                                  | 1         | 2.78%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.78%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 2.78%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 2.78%   |
| Intel 82599 10 Gigabit Dual Port Backplane Connection             | 1         | 2.78%   |
| Intel 82578DM Gigabit Network Connection                          | 1         | 2.78%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 2.78%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 1         | 2.78%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 2.78%   |
| Broadcom BCM57840 NetXtreme II 10/20-Gigabit Ethernet             | 1         | 2.78%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 29        | 50%     |
| Ethernet | 29        | 50%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 24        | 51.06%  |
| WiFi     | 23        | 48.94%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 22        | 61.11%  |
| 1     | 12        | 33.33%  |
| 4     | 1         | 2.78%   |
| 3     | 1         | 2.78%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 30        | 78.95%  |
| Yes  | 8         | 21.05%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 15        | 62.5%   |
| Qualcomm Atheros Communications | 3         | 12.5%   |
| Broadcom                        | 2         | 8.33%   |
| Realtek Semiconductor           | 1         | 4.17%   |
| IMC Networks                    | 1         | 4.17%   |
| ASUSTek Computer                | 1         | 4.17%   |
| Apple                           | 1         | 4.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 9         | 37.5%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 3         | 12.5%   |
| Qualcomm Atheros  Bluetooth Device             | 2         | 8.33%   |
| Intel AX201 Bluetooth                          | 2         | 8.33%   |
| Realtek Bluetooth Radio                        | 1         | 4.17%   |
| Qualcomm Atheros AR9462 Bluetooth              | 1         | 4.17%   |
| Intel Bluetooth Device                         | 1         | 4.17%   |
| IMC Networks Bluetooth Radio                   | 1         | 4.17%   |
| Broadcom BCM43142A0 Bluetooth 4.0              | 1         | 4.17%   |
| Broadcom BCM20702A0 Bluetooth 4.0              | 1         | 4.17%   |
| ASUS Broadcom BCM20702A0 Bluetooth             | 1         | 4.17%   |
| Apple Bluetooth Host Controller                | 1         | 4.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor    | Computers | Percent |
|-----------|-----------|---------|
| Intel     | 29        | 56.86%  |
| Nvidia    | 9         | 17.65%  |
| Lenovo    | 4         | 7.84%   |
| GN Netcom | 4         | 7.84%   |
| AMD       | 4         | 7.84%   |
| Unknown   | 1         | 1.96%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 6         | 10%     |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 6.67%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 5%      |
| Intel Broadwell-U Audio Controller                                                                | 3         | 5%      |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 3.33%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 2         | 3.33%   |
| Lenovo ThinkPad Dock USB Audio                                                                    | 2         | 3.33%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 3.33%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 3.33%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 3.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 3.33%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 3.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 3.33%   |
| Unknown Definitive Sym1                                                                           | 1         | 1.67%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 1.67%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.67%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 1.67%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 1.67%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 1.67%   |
| Nvidia GK110 High Definition Audio Controller                                                     | 1         | 1.67%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 1.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.67%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 1.67%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 1.67%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1         | 1.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 1.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.67%   |
| GN Netcom Jabra SPEAK 510                                                                         | 1         | 1.67%   |
| GN Netcom Jabra PRO 9470                                                                          | 1         | 1.67%   |
| GN Netcom Jabra Link 370                                                                          | 1         | 1.67%   |
| GN Netcom Jabra EVOLVE LINK                                                                       | 1         | 1.67%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.67%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.67%   |
| AMD High Definition Audio Controller                                                              | 1         | 1.67%   |
| AMD FCH Azalia Controller                                                                         | 1         | 1.67%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 1.67%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1         | 1.67%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 1.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 4         | 21.05%  |
| Micron Technology   | 4         | 21.05%  |
| SK Hynix            | 3         | 15.79%  |
| Kingston            | 2         | 10.53%  |
| Unknown             | 1         | 5.26%   |
| Smart               | 1         | 5.26%   |
| HPE                 | 1         | 5.26%   |
| Crucial             | 1         | 5.26%   |
| Corsair             | 1         | 5.26%   |
| Avant               | 1         | 5.26%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 2         | 10.53%  |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                  | 1         | 5.26%   |
| Smart RAM SMS4TDC3C0K0446SCG 4096MB SODIMM DDR4 2667MT/s     | 1         | 5.26%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s    | 1         | 5.26%   |
| SK Hynix RAM HMAA1GS6CMR8N-VK 8GB Row Of Chips DDR4 2667MT/s | 1         | 5.26%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s | 1         | 5.26%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 5.26%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s       | 1         | 5.26%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s  | 1         | 5.26%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s         | 1         | 5.26%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s        | 1         | 5.26%   |
| Micron RAM 18ASF2G72PDZ-2G3B1 16GB DIMM DDR4 2400MT/s        | 1         | 5.26%   |
| Kingston RAM KX830D-ELC 4096MB SODIMM DDR3 1333MT/s          | 1         | 5.26%   |
| Kingston RAM KTW149-ELF 1GB DIMM DDR3 1333MT/s               | 1         | 5.26%   |
| HPE RAM 840756-091 16GB DIMM DDR4 2666MT/s                   | 1         | 5.26%   |
| Crucial RAM BLE8G4D34AEEAK.K8FB 8192MB DIMM DDR4 3466MT/s    | 1         | 5.26%   |
| Corsair RAM CMSX32GX4M2A2666C18 16GB SODIMM DDR4 2667MT/s    | 1         | 5.26%   |
| Avant RAM H6451U66G1600G 4096MB SODIMM DDR3 1600MT/s         | 1         | 5.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 10        | 55.56%  |
| DDR3   | 7         | 38.89%  |
| LPDDR4 | 1         | 5.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 11        | 61.11%  |
| DIMM         | 4         | 22.22%  |
| Row Of Chips | 3         | 16.67%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 7         | 38.89%  |
| 4096  | 6         | 33.33%  |
| 16384 | 3         | 16.67%  |
| 32768 | 1         | 5.56%   |
| 1024  | 1         | 5.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 5         | 27.78%  |
| 1600  | 5         | 27.78%  |
| 2400  | 2         | 11.11%  |
| 1333  | 2         | 11.11%  |
| 4267  | 1         | 5.56%   |
| 3466  | 1         | 5.56%   |
| 2666  | 1         | 5.56%   |
| 1866  | 1         | 5.56%   |

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
| Chicony Electronics   | 8         | 33.33%  |
| IMC Networks          | 4         | 16.67%  |
| Suyin                 | 3         | 12.5%   |
| Logitech              | 3         | 12.5%   |
| Realtek Semiconductor | 2         | 8.33%   |
| Microdia              | 2         | 8.33%   |
| Lite-On Technology    | 1         | 4.17%   |
| Acer                  | 1         | 4.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Chicony Integrated Camera               | 6         | 24%     |
| Microdia Webcam Vitade AF               | 2         | 8%      |
| IMC Networks VGA UVC WebCam             | 2         | 8%      |
| IMC Networks Integrated Camera          | 2         | 8%      |
| Chicony Integrated Camera (1280x720@30) | 2         | 8%      |
| Suyin Integrated_Webcam_HD              | 1         | 4%      |
| Suyin HP Truevision HD                  | 1         | 4%      |
| Suyin Asus Integrated Webcam            | 1         | 4%      |
| Realtek Integrated_Webcam_HD            | 1         | 4%      |
| Realtek EasyCamera                      | 1         | 4%      |
| Logitech Webcam C920-C                  | 1         | 4%      |
| Logitech HD Webcam C615                 | 1         | 4%      |
| Logitech BRIO                           | 1         | 4%      |
| Lite-On HP HD Camera                    | 1         | 4%      |
| Chicony Integrated IR Camera            | 1         | 4%      |
| Acer SunplusIT Integrated Camera        | 1         | 4%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 6         | 60%     |
| Validity Sensors           | 3         | 30%     |
| Shenzhen Goodix Technology | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 30%     |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 20%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 20%     |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 10%     |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 10%     |
| Unknown                                                                    | 1         | 10%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 75%     |
| Alcor Micro | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 58200                                 | 2         | 50%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 25%     |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 16        | 43.24%  |
| 1     | 14        | 37.84%  |
| 2     | 5         | 13.51%  |
| 3     | 2         | 5.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 10        | 37.04%  |
| Unassigned class         | 3         | 11.11%  |
| Chipcard                 | 3         | 11.11%  |
| Net/wireless             | 2         | 7.41%   |
| Graphics card            | 2         | 7.41%   |
| Communication controller | 2         | 7.41%   |
| Card reader              | 2         | 7.41%   |
| Bluetooth                | 2         | 7.41%   |
| Storage                  | 1         | 3.7%    |

