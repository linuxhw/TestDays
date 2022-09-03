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

Total: 53

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo   | Legion 5 15IMH05 82AU       | [bd4737dfcf](https://linux-hardware.org/?probe=bd4737dfcf) | Aug 18, 2022 |
| Dell     | Inspiron 5502               | [28dcf01e88](https://linux-hardware.org/?probe=28dcf01e88) | Aug 03, 2022 |
| Lenovo   | Legion 5 15IMH05 82AU       | [3dddb3aac3](https://linux-hardware.org/?probe=3dddb3aac3) | Jul 20, 2022 |
| Lenovo   | ThinkPad P70 20ESS04S00     | [fc29967bed](https://linux-hardware.org/?probe=fc29967bed) | Jun 17, 2022 |
| HP       | Compaq 6730b                | [dd94c9145b](https://linux-hardware.org/?probe=dd94c9145b) | Jun 11, 2022 |
| Lenovo   | ThinkPad T410 2518A37       | [04e81b8b3f](https://linux-hardware.org/?probe=04e81b8b3f) | Jun 04, 2022 |
| Lenovo   | ThinkPad T430s 2355C33      | [33de2bbd12](https://linux-hardware.org/?probe=33de2bbd12) | May 31, 2022 |
| Lenovo   | ThinkPad T430s 2355C33      | [4eab57bebf](https://linux-hardware.org/?probe=4eab57bebf) | May 30, 2022 |
| Dell     | Precision M4600             | [0ac2adfe5a](https://linux-hardware.org/?probe=0ac2adfe5a) | Apr 21, 2022 |
| Dell     | Precision M4800             | [fb13b19803](https://linux-hardware.org/?probe=fb13b19803) | Apr 21, 2022 |
| Lenovo   | ThinkPad P50s 20FL000MUS    | [99fbb4446c](https://linux-hardware.org/?probe=99fbb4446c) | Apr 16, 2022 |
| Lenovo   | ThinkPad X1 Extreme 2nd ... | [b708e920f3](https://linux-hardware.org/?probe=b708e920f3) | Mar 21, 2022 |
| Lenovo   | ThinkPad T450 20BUS14900    | [bd60aae97a](https://linux-hardware.org/?probe=bd60aae97a) | Mar 11, 2022 |
| Lenovo   | ThinkPad T480 20L5A07TAU    | [755854f7d4](https://linux-hardware.org/?probe=755854f7d4) | Mar 11, 2022 |
| Lenovo   | ThinkPad X280 20KES4H34G    | [2b8a4f4664](https://linux-hardware.org/?probe=2b8a4f4664) | Mar 10, 2022 |
| Dell     | Latitude 7420               | [af5f1055fe](https://linux-hardware.org/?probe=af5f1055fe) | Mar 10, 2022 |
| HP       | ProBook 445 G6              | [88d8b32328](https://linux-hardware.org/?probe=88d8b32328) | Jan 26, 2022 |
| Lenovo   | ThinkPad T450 20BUS14900    | [44c8e11f02](https://linux-hardware.org/?probe=44c8e11f02) | Dec 22, 2021 |
| Lenovo   | IdeaPad 300-15ISK 80RS      | [1c9ca21f4e](https://linux-hardware.org/?probe=1c9ca21f4e) | Dec 10, 2021 |
| Dell     | Latitude 7410               | [3efa87284e](https://linux-hardware.org/?probe=3efa87284e) | Nov 18, 2021 |
| Dell     | Latitude E6420              | [b809392380](https://linux-hardware.org/?probe=b809392380) | Oct 08, 2021 |
| Dell     | Latitude 7410               | [8f1a1a4798](https://linux-hardware.org/?probe=8f1a1a4798) | Sep 06, 2021 |
| Dell     | Latitude 7410               | [b03a0e0152](https://linux-hardware.org/?probe=b03a0e0152) | Sep 06, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | [7b393c5790](https://linux-hardware.org/?probe=7b393c5790) | Aug 21, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | [394c99adc8](https://linux-hardware.org/?probe=394c99adc8) | Aug 19, 2021 |
| Dell     | Inspiron 3542               | [0909599e9c](https://linux-hardware.org/?probe=0909599e9c) | Aug 11, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | [ba7afba1a6](https://linux-hardware.org/?probe=ba7afba1a6) | Jul 08, 2021 |
| Lenovo   | ThinkPad L490 20Q5CTO1WW    | [0225c17d79](https://linux-hardware.org/?probe=0225c17d79) | Jul 02, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | [505b82b2de](https://linux-hardware.org/?probe=505b82b2de) | Jun 06, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | [75b2ef5126](https://linux-hardware.org/?probe=75b2ef5126) | May 13, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | [734a4fbc56](https://linux-hardware.org/?probe=734a4fbc56) | May 09, 2021 |
| ASUSTek  | UX305FA                     | [0bf50fba2d](https://linux-hardware.org/?probe=0bf50fba2d) | Mar 15, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | [ff355a9bb1](https://linux-hardware.org/?probe=ff355a9bb1) | Mar 11, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | [9f67379954](https://linux-hardware.org/?probe=9f67379954) | Mar 04, 2021 |
| Lenovo   | ThinkPad L490 20Q5CTO1WW    | [db0f24aee5](https://linux-hardware.org/?probe=db0f24aee5) | Mar 01, 2021 |
| Dell     | Latitude 7410               | [5b725b01aa](https://linux-hardware.org/?probe=5b725b01aa) | Feb 26, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | [835e8cad03](https://linux-hardware.org/?probe=835e8cad03) | Feb 25, 2021 |
| Dell     | Latitude 7410               | [430ac9fa0c](https://linux-hardware.org/?probe=430ac9fa0c) | Feb 24, 2021 |
| Lenovo   | ThinkPad T490 20N3S77600    | [26e61c39f2](https://linux-hardware.org/?probe=26e61c39f2) | Feb 24, 2021 |
| Dell     | Latitude 7410               | [7aeb2cc674](https://linux-hardware.org/?probe=7aeb2cc674) | Feb 22, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | [8af2c8d83c](https://linux-hardware.org/?probe=8af2c8d83c) | Feb 05, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | [7ea3c87bfe](https://linux-hardware.org/?probe=7ea3c87bfe) | Jan 06, 2021 |
| Standard | BW Series                   | [1f6cf82ba8](https://linux-hardware.org/?probe=1f6cf82ba8) | Jun 13, 2020 |
| HP       | Notebook                    | [e3c242a846](https://linux-hardware.org/?probe=e3c242a846) | May 24, 2020 |
| Lenovo   | ThinkPad L490 20Q5CTO1WW    | [d8b2c132c1](https://linux-hardware.org/?probe=d8b2c132c1) | Apr 09, 2020 |
| HP       | ZBook 15                    | [4723616d8c](https://linux-hardware.org/?probe=4723616d8c) | Apr 09, 2020 |
| Lenovo   | ThinkPad L490 20Q5CTO1WW    | [1acbabb197](https://linux-hardware.org/?probe=1acbabb197) | Apr 06, 2020 |
| Lenovo   | ThinkPad T480 20L6S56Y2X    | [5343997520](https://linux-hardware.org/?probe=5343997520) | Feb 23, 2020 |
| ASUSTek  | X510UR                      | [914b9fbe64](https://linux-hardware.org/?probe=914b9fbe64) | Feb 04, 2020 |
| ASUSTek  | X510UR                      | [014d5ef0c8](https://linux-hardware.org/?probe=014d5ef0c8) | Jan 28, 2020 |
| ASUSTek  | X510UR                      | [9d05b420d4](https://linux-hardware.org/?probe=9d05b420d4) | Jan 28, 2020 |
| Lenovo   | ThinkPad L540 20AVCTO1WW    | [8c1dba9d6e](https://linux-hardware.org/?probe=8c1dba9d6e) | Sep 10, 2019 |
| Lenovo   | ThinkPad T480 20L6S56Y2X    | [f012a475eb](https://linux-hardware.org/?probe=f012a475eb) | Apr 11, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Oracle Linux 8.5 | 11        | 29.73%  |
| Oracle Linux 8.3 | 6         | 16.22%  |
| Oracle Linux 8.4 | 5         | 13.51%  |
| Oracle Linux 8.1 | 3         | 8.11%   |
| Oracle Linux 7.9 | 3         | 8.11%   |
| Oracle Linux 8.6 | 2         | 5.41%   |
| Oracle Linux 7.8 | 2         | 5.41%   |
| Oracle Linux 7.7 | 2         | 5.41%   |
| Oracle Linux 9.0 | 1         | 2.7%    |
| Oracle Linux 8.2 | 1         | 2.7%    |
| Oracle Linux 7.6 | 1         | 2.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Oracle Linux | 30        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Notebooks | Percent |
|------------------------------------|-----------|---------|
| 5.4.17-2036.103.3.1.el8uek.x86_64  | 3         | 7.32%   |
| 4.18.0-348.12.2.el8_5.x86_64       | 3         | 7.32%   |
| 5.4.17-2136.304.4.3.el8uek.x86_64  | 2         | 4.88%   |
| 5.4.17-2102.202.5.el8uek.x86_64    | 2         | 4.88%   |
| 4.18.0-147.3.1.el8_1.x86_64        | 2         | 4.88%   |
| 5.4.17-2136.310.7.el8uek.x86_64    | 1         | 2.44%   |
| 5.4.17-2136.309.4.el8uek.x86_64    | 1         | 2.44%   |
| 5.4.17-2136.308.9.el7uek.x86_64    | 1         | 2.44%   |
| 5.4.17-2136.306.1.3.el8uek.x86_64  | 1         | 2.44%   |
| 5.4.17-2136.305.5.4.el8uek.x86_64  | 1         | 2.44%   |
| 5.4.17-2136.305.5.3.el8uek.x86_64  | 1         | 2.44%   |
| 5.4.17-2136.305.5.2.el8uek.x86_64  | 1         | 2.44%   |
| 5.4.17-2136.301.1.4.el8uek.x86_64  | 1         | 2.44%   |
| 5.4.17-2136.300.7.el8uek.x86_64    | 1         | 2.44%   |
| 5.4.17-2102.205.7.3.el8uek.x86_64  | 1         | 2.44%   |
| 5.4.17-2102.204.4.4.el8uek.x86_64  | 1         | 2.44%   |
| 5.4.17-2102.204.4.2.el8uek.x86_64  | 1         | 2.44%   |
| 5.4.17-2102.201.3.el8uek.x86_64    | 1         | 2.44%   |
| 5.4.17-2102.200.13.el8uek.x86_64   | 1         | 2.44%   |
| 5.4.17-2036.104.4.el8uek.x86_64    | 1         | 2.44%   |
| 5.4.17-2011.0.7.el8uek.x86_64      | 1         | 2.44%   |
| 5.15.2-1.el8.elrepo.x86_64         | 1         | 2.44%   |
| 5.15.0-0.30.20.1.el9uek.x86_64     | 1         | 2.44%   |
| 5.14.1-1.el8.elrepo.x86_64         | 1         | 2.44%   |
| 5.11.1-1.el8.elrepo.x86_64         | 1         | 2.44%   |
| 4.18.0-240.15.1.el8_3.x86_64       | 1         | 2.44%   |
| 4.18.0-240.10.1.el8_3.x86_64       | 1         | 2.44%   |
| 4.18.0-193.1.2.el8_2.x86_64        | 1         | 2.44%   |
| 4.14.35-2047.510.4.1.el7uek.x86_64 | 1         | 2.44%   |
| 4.14.35-1902.4.8.el7uek.x86_64     | 1         | 2.44%   |
| 4.14.35-1902.300.11.el7uek.x86_64  | 1         | 2.44%   |
| 4.14.35-1818.3.3.el7uek.x86_64     | 1         | 2.44%   |
| 4.1.12-124.63.2.1.el7uek.x86_64    | 1         | 2.44%   |
| 3.10.0-1127.10.1.el7.x86_64        | 1         | 2.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.17  | 15        | 46.88%  |
| 4.18.0  | 7         | 21.88%  |
| 4.14.35 | 4         | 12.5%   |
| 5.15.2  | 1         | 3.13%   |
| 5.15.0  | 1         | 3.13%   |
| 5.14.1  | 1         | 3.13%   |
| 5.11.1  | 1         | 3.13%   |
| 4.1.12  | 1         | 3.13%   |
| 3.10.0  | 1         | 3.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 15        | 46.88%  |
| 4.18    | 7         | 21.88%  |
| 4.14    | 4         | 12.5%   |
| 5.15    | 2         | 6.25%   |
| 5.14    | 1         | 3.13%   |
| 5.11    | 1         | 3.13%   |
| 4.1     | 1         | 3.13%   |
| 3.10    | 1         | 3.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 30        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 22        | 66.67%  |
| Unknown       | 3         | 9.09%   |
| XFCE          | 2         | 6.06%   |
| MATE          | 2         | 6.06%   |
| KDE4          | 2         | 6.06%   |
| KDE5          | 1         | 3.03%   |
| GNOME Classic | 1         | 3.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 15        | 46.88%  |
| Wayland | 15        | 46.88%  |
| Unknown | 2         | 6.25%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 17        | 53.13%  |
| GDM     | 14        | 43.75%  |
| SDDM    | 1         | 3.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 18        | 58.06%  |
| en_GB   | 3         | 9.68%   |
| de_DE   | 3         | 9.68%   |
| en_AU   | 2         | 6.45%   |
| Unknown | 2         | 6.45%   |
| zh_HK   | 1         | 3.23%   |
| pt_BR   | 1         | 3.23%   |
| pl_PL   | 1         | 3.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 16        | 51.61%  |
| EFI  | 15        | 48.39%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Xfs     | 26        | 81.25%  |
| Ext4    | 4         | 12.5%   |
| Unknown | 2         | 6.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 17        | 53.13%  |
| GPT     | 9         | 28.13%  |
| MBR     | 6         | 18.75%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 27        | 87.1%   |
| Yes       | 4         | 12.9%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 29        | 96.67%  |
| Yes       | 1         | 3.33%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 15        | 50%     |
| Dell             | 7         | 23.33%  |
| Hewlett-Packard  | 4         | 13.33%  |
| ASUSTek Computer | 3         | 10%     |
| Standard         | 1         | 3.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Lenovo ThinkPad T450 20BUS14900           | 2         | 6.67%   |
| ASUS X510UR                               | 2         | 6.67%   |
| Standard BW Series                        | 1         | 3.33%   |
| Lenovo ThinkPad X280 20KES4H34G           | 1         | 3.33%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QWS1R800 | 1         | 3.33%   |
| Lenovo ThinkPad T490 20N3S77600           | 1         | 3.33%   |
| Lenovo ThinkPad T480 20L6S56Y2X           | 1         | 3.33%   |
| Lenovo ThinkPad T480 20L5A07TAU           | 1         | 3.33%   |
| Lenovo ThinkPad T430s 2355C33             | 1         | 3.33%   |
| Lenovo ThinkPad P70 20ESS04S00            | 1         | 3.33%   |
| Lenovo ThinkPad P50s 20FL000MUS           | 1         | 3.33%   |
| Lenovo ThinkPad L540 20AVCTO1WW           | 1         | 3.33%   |
| Lenovo ThinkPad L490 20Q5CTO1WW           | 1         | 3.33%   |
| Lenovo Legion 5 15IMH05 82AU              | 1         | 3.33%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS       | 1         | 3.33%   |
| Lenovo IdeaPad 300-15ISK 80RS             | 1         | 3.33%   |
| HP ZBook 15                               | 1         | 3.33%   |
| HP ProBook 445 G6                         | 1         | 3.33%   |
| HP Notebook                               | 1         | 3.33%   |
| HP Compaq 6730b                           | 1         | 3.33%   |
| Dell Precision M4800                      | 1         | 3.33%   |
| Dell Precision M4600                      | 1         | 3.33%   |
| Dell Latitude E6420                       | 1         | 3.33%   |
| Dell Latitude 7420                        | 1         | 3.33%   |
| Dell Latitude 7410                        | 1         | 3.33%   |
| Dell Inspiron 5502                        | 1         | 3.33%   |
| Dell Inspiron 3542                        | 1         | 3.33%   |
| ASUS UX305FA                              | 1         | 3.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Lenovo ThinkPad | 12        | 40%     |
| Dell Latitude   | 3         | 10%     |
| Lenovo IdeaPad  | 2         | 6.67%   |
| Dell Precision  | 2         | 6.67%   |
| Dell Inspiron   | 2         | 6.67%   |
| ASUS X510UR     | 2         | 6.67%   |
| Standard BW     | 1         | 3.33%   |
| Lenovo Legion   | 1         | 3.33%   |
| HP ZBook        | 1         | 3.33%   |
| HP ProBook      | 1         | 3.33%   |
| HP Notebook     | 1         | 3.33%   |
| HP Compaq       | 1         | 3.33%   |
| ASUS UX305FA    | 1         | 3.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 5         | 16.67%  |
| 2020 | 4         | 13.33%  |
| 2016 | 4         | 13.33%  |
| 2018 | 3         | 10%     |
| 2015 | 3         | 10%     |
| 2014 | 3         | 10%     |
| 2017 | 2         | 6.67%   |
| 2013 | 2         | 6.67%   |
| 2011 | 2         | 6.67%   |
| 2012 | 1         | 3.33%   |
| 2008 | 1         | 3.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 30        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 27        | 87.1%   |
| Enabled  | 4         | 12.9%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 30        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 9         | 29.03%  |
| 8.01-16.0   | 8         | 25.81%  |
| 4.01-8.0    | 5         | 16.13%  |
| 3.01-4.0    | 4         | 12.9%   |
| 16.01-24.0  | 4         | 12.9%   |
| 64.01-256.0 | 1         | 3.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 11        | 30.56%  |
| 2.01-3.0   | 10        | 27.78%  |
| 8.01-16.0  | 7         | 19.44%  |
| 3.01-4.0   | 4         | 11.11%  |
| 1.01-2.0   | 2         | 5.56%   |
| 24.01-32.0 | 1         | 2.78%   |
| 0.51-1.0   | 1         | 2.78%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 26        | 83.87%  |
| 2      | 3         | 9.68%   |
| 4      | 1         | 3.23%   |
| 3      | 1         | 3.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 22        | 73.33%  |
| Yes       | 8         | 26.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 83.33%  |
| No        | 5         | 16.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 96.67%  |
| No        | 1         | 3.33%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 18        | 58.06%  |
| No        | 13        | 41.94%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 11        | 35.48%  |
| Germany     | 4         | 12.9%   |
| UK          | 3         | 9.68%   |
| Brazil      | 3         | 9.68%   |
| Netherlands | 2         | 6.45%   |
| Australia   | 2         | 6.45%   |
| Romania     | 1         | 3.23%   |
| Poland      | 1         | 3.23%   |
| Pakistan    | 1         | 3.23%   |
| Hong Kong   | 1         | 3.23%   |
| Bulgaria    | 1         | 3.23%   |
| Argentina   | 1         | 3.23%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| San Diego          | 3         | 8.82%   |
| Siegen             | 2         | 5.88%   |
| Seattle            | 2         | 5.88%   |
| Utrecht            | 1         | 2.94%   |
| Sydney             | 1         | 2.94%   |
| Sofia              | 1         | 2.94%   |
| Shrewsbury         | 1         | 2.94%   |
| Sao Paulo          | 1         | 2.94%   |
| Sao Caetano do Sul | 1         | 2.94%   |
| Rocklin            | 1         | 2.94%   |
| Port Saint Lucie   | 1         | 2.94%   |
| Pleven             | 1         | 2.94%   |
| Ngau Wu Tok        | 1         | 2.94%   |
| Maple Valley       | 1         | 2.94%   |
| Ludwigsburg        | 1         | 2.94%   |
| London             | 1         | 2.94%   |
| Katowice           | 1         | 2.94%   |
| Karachi            | 1         | 2.94%   |
| Greven             | 1         | 2.94%   |
| Drochtersen        | 1         | 2.94%   |
| Dallas             | 1         | 2.94%   |
| Colorado Springs   | 1         | 2.94%   |
| Chicago            | 1         | 2.94%   |
| Castelar           | 1         | 2.94%   |
| Canberra           | 1         | 2.94%   |
| Campinas           | 1         | 2.94%   |
| Bucharest          | 1         | 2.94%   |
| Bracknell          | 1         | 2.94%   |
| Berlin             | 1         | 2.94%   |
| Amsterdam          | 1         | 2.94%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 13        | 16     | 36.11%  |
| SanDisk                 | 6         | 7      | 16.67%  |
| Seagate                 | 3         | 3      | 8.33%   |
| WDC                     | 2         | 2      | 5.56%   |
| Unknown                 | 2         | 4      | 5.56%   |
| HGST                    | 2         | 3      | 5.56%   |
| Union Memory (Shenzhen) | 1         | 2      | 2.78%   |
| Micron Technology       | 1         | 4      | 2.78%   |
| Lite-On                 | 1         | 1      | 2.78%   |
| Lenovo                  | 1         | 1      | 2.78%   |
| Kingston                | 1         | 7      | 2.78%   |
| JMicron Technology      | 1         | 1      | 2.78%   |
| Fujitsu                 | 1         | 1      | 2.78%   |
| Crucial                 | 1         | 2      | 2.78%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| SanDisk SSD PLUS 1000GB                      | 2         | 5.41%   |
| Samsung MZ7LN512HMJP-000L7 512GB SSD         | 2         | 5.41%   |
| WDC WDS250G2B0A-00SM50 250GB SSD             | 1         | 2.7%    |
| WDC WD10JPCX-24UE4T0 1TB                     | 1         | 2.7%    |
| Unknown SD/MMC/MS PRO 128GB                  | 1         | 2.7%    |
| Unknown MMC Card  256GB                      | 1         | 2.7%    |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 2.7%    |
| Seagate ST9750420AS 752GB                    | 1         | 2.7%    |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 2.7%    |
| Seagate BUP Slim BK 1TB                      | 1         | 2.7%    |
| SanDisk SDSSDH3512G 512GB                    | 1         | 2.7%    |
| SanDisk SD7SN3Q256G1002 256GB SSD            | 1         | 2.7%    |
| SanDisk SD6SB1M-256G-1006 256GB SSD          | 1         | 2.7%    |
| SanDisk NVMe SSD Drive 512GB                 | 1         | 2.7%    |
| Samsung SSD SM841N 2.5 7mm 512GB             | 1         | 2.7%    |
| Samsung SSD PM830 2.5 7mm 256GB              | 1         | 2.7%    |
| Samsung SSD 850 PRO 256GB                    | 1         | 2.7%    |
| Samsung PM9A1 NVMe 512GB                     | 1         | 2.7%    |
| Samsung NVMe SSD Drive 512GB                 | 1         | 2.7%    |
| Samsung NVMe SSD Drive 1TB                   | 1         | 2.7%    |
| Samsung MZVLW256HEHP-000L7 256GB             | 1         | 2.7%    |
| Samsung MZVLB1T0HBLR-000L7 1TB               | 1         | 2.7%    |
| Samsung MZNLN512HCJH-000L1 512GB SSD         | 1         | 2.7%    |
| Samsung MZ7LN512HCHP-000L1 512GB SSD         | 1         | 2.7%    |
| Samsung MZ7LN256HCHP-000L7 256GB SSD         | 1         | 2.7%    |
| Micron NVMe SSD Drive 256GB                  | 1         | 2.7%    |
| Micron 2200S NVMe 256GB                      | 1         | 2.7%    |
| Lite-On NVMe SSD Drive 512GB                 | 1         | 2.7%    |
| Lenovo LENSE30512GMSP34MEAT3TA 512GB         | 1         | 2.7%    |
| Kingston NVMe SSD Drive 1TB                  | 1         | 2.7%    |
| JMicron Disk 250GB                           | 1         | 2.7%    |
| HGST HTS545050A7E380 500GB                   | 1         | 2.7%    |
| HGST HTS541010A7E630 1TB                     | 1         | 2.7%    |
| Fujitsu MHZ2160BH G2 160GB                   | 1         | 2.7%    |
| Crucial CT500MX500SSD1 500GB                 | 1         | 2.7%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 3         | 3      | 33.33%  |
| HGST               | 2         | 3      | 22.22%  |
| WDC                | 1         | 1      | 11.11%  |
| Unknown            | 1         | 3      | 11.11%  |
| JMicron Technology | 1         | 1      | 11.11%  |
| Fujitsu            | 1         | 1      | 11.11%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 9      | 53.33%  |
| SanDisk             | 5         | 5      | 33.33%  |
| WDC                 | 1         | 1      | 6.67%   |
| Crucial             | 1         | 2      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 15        | 17     | 42.86%  |
| NVMe | 11        | 24     | 31.43%  |
| HDD  | 8         | 12     | 22.86%  |
| MMC  | 1         | 1      | 2.86%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 20        | 24     | 58.82%  |
| NVMe | 11        | 24     | 32.35%  |
| SAS  | 2         | 5      | 5.88%   |
| MMC  | 1         | 1      | 2.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 12        | 15     | 52.17%  |
| 0.01-0.5   | 11        | 14     | 47.83%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 7         | 22.58%  |
| Unknown    | 6         | 19.35%  |
| 101-250    | 5         | 16.13%  |
| 1-20       | 5         | 16.13%  |
| 501-1000   | 4         | 12.9%   |
| 2001-3000  | 2         | 6.45%   |
| 51-100     | 2         | 6.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 10        | 30.3%   |
| 21-50     | 6         | 18.18%  |
| Unknown   | 6         | 18.18%  |
| 51-100    | 4         | 12.12%  |
| 251-500   | 3         | 9.09%   |
| 101-250   | 2         | 6.06%   |
| 1001-2000 | 1         | 3.03%   |
| 501-1000  | 1         | 3.03%   |

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
| Detected | 19        | 37     | 57.58%  |
| Works    | 12        | 15     | 36.36%  |
| Malfunc  | 2         | 2      | 6.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 18        | 56.25%  |
| Samsung Electronics         | 5         | 15.63%  |
| AMD                         | 3         | 9.38%   |
| Union Memory (Shenzhen)     | 1         | 3.13%   |
| SanDisk                     | 1         | 3.13%   |
| Micron Technology           | 1         | 3.13%   |
| Lite-On Technology          | 1         | 3.13%   |
| Lenovo                      | 1         | 3.13%   |
| Kingston Technology Company | 1         | 3.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 4         | 12.5%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 9.38%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 9.38%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 3         | 9.38%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 3         | 9.38%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 6.25%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 3.13%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 3.13%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 3.13%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 3.13%   |
| Micron Non-Volatile memory controller                                            | 1         | 3.13%   |
| Lite-On Non-Volatile memory controller                                           | 1         | 3.13%   |
| Lenovo Non-Volatile memory controller                                            | 1         | 3.13%   |
| Kingston Company A2000 NVMe SSD                                                  | 1         | 3.13%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 3.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 3.13%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1         | 3.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 3.13%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 1         | 3.13%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 1         | 3.13%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 18        | 56.25%  |
| NVMe | 11        | 34.38%  |
| RAID | 3         | 9.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 27        | 90%     |
| AMD    | 3         | 10%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-7500U CPU @ 2.70GHz               | 2         | 6.67%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 2         | 6.67%   |
| Intel Core i5-8350U CPU @ 1.70GHz               | 2         | 6.67%   |
| Intel Core i5-5300U CPU @ 2.30GHz               | 2         | 6.67%   |
| Intel Processor 5Y10 CPU @ 0.80GHz              | 1         | 3.33%   |
| Intel Core i9-9880H CPU @ 2.30GHz               | 1         | 3.33%   |
| Intel Core i7-8665U CPU @ 1.90GHz               | 1         | 3.33%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 1         | 3.33%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz              | 1         | 3.33%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz              | 1         | 3.33%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz              | 1         | 3.33%   |
| Intel Core i7-2860QM CPU @ 2.50GHz              | 1         | 3.33%   |
| Intel Core i7-2760QM CPU @ 2.40GHz              | 1         | 3.33%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 1         | 3.33%   |
| Intel Core i7-10610U CPU @ 1.80GHz              | 1         | 3.33%   |
| Intel Core i5-8365U CPU @ 1.60GHz               | 1         | 3.33%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 1         | 3.33%   |
| Intel Core i5-4210M CPU @ 2.60GHz               | 1         | 3.33%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 1         | 3.33%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz            | 1         | 3.33%   |
| Intel Celeron CPU N3010 @ 1.04GHz               | 1         | 3.33%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz         | 1         | 3.33%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 1         | 3.33%   |
| AMD Ryzen 7 PRO 2700U w/ Radeon Vega Mobile Gfx | 1         | 3.33%   |
| AMD A9-9420e RADEON R5, 5 COMPUTE CORES 2C+3G   | 1         | 3.33%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics     | 1         | 3.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 13        | 43.33%  |
| Intel Core i5    | 8         | 26.67%  |
| Other            | 4         | 13.33%  |
| Intel Core i9    | 1         | 3.33%   |
| Intel Core 2 Duo | 1         | 3.33%   |
| Intel Celeron    | 1         | 3.33%   |
| AMD Ryzen 7 PRO  | 1         | 3.33%   |
| AMD A8           | 1         | 3.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 14        | 46.67%  |
| 2      | 13        | 43.33%  |
| 8      | 1         | 3.33%   |
| 6      | 1         | 3.33%   |
| 1      | 1         | 3.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 30        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 26        | 86.67%  |
| 1      | 4         | 13.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 29        | 93.55%  |
| Unknown        | 2         | 6.45%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ec    | 3         | 10%     |
| 0x806ea    | 3         | 10%     |
| 0x306d4    | 3         | 10%     |
| 0x306c3    | 3         | 10%     |
| 0x806c1    | 2         | 6.67%   |
| 0x406e3    | 2         | 6.67%   |
| 0x206a7    | 2         | 6.67%   |
| Unknown    | 2         | 6.67%   |
| 0xa0652    | 1         | 3.33%   |
| 0x906ed    | 1         | 3.33%   |
| 0x506e3    | 1         | 3.33%   |
| 0x406c4    | 1         | 3.33%   |
| 0x40651    | 1         | 3.33%   |
| 0x306a9    | 1         | 3.33%   |
| 0x10676    | 1         | 3.33%   |
| 0x0810100b | 1         | 3.33%   |
| 0x07030105 | 1         | 3.33%   |
| 0x06006705 | 1         | 3.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 9         | 30%     |
| Haswell     | 4         | 13.33%  |
| Skylake     | 3         | 10%     |
| Broadwell   | 3         | 10%     |
| TigerLake   | 2         | 6.67%   |
| SandyBridge | 2         | 6.67%   |
| Zen         | 1         | 3.33%   |
| Silvermont  | 1         | 3.33%   |
| Puma        | 1         | 3.33%   |
| Penryn      | 1         | 3.33%   |
| IvyBridge   | 1         | 3.33%   |
| Excavator   | 1         | 3.33%   |
| CometLake   | 1         | 3.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 23        | 57.5%   |
| Nvidia | 11        | 27.5%   |
| AMD    | 6         | 15%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 3         | 7.5%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 7.5%    |
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 5%      |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 5%      |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 5%      |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 5%      |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 5%      |
| Intel HD Graphics 620                                                                    | 2         | 5%      |
| Intel HD Graphics 5500                                                                   | 2         | 5%      |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 2.5%    |
| Nvidia TU117M                                                                            | 1         | 2.5%    |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 2.5%    |
| Nvidia GM204GLM [Quadro M4000M]                                                          | 1         | 2.5%    |
| Nvidia GM108GLM [Quadro K620M / Quadro M500M]                                            | 1         | 2.5%    |
| Nvidia GK208GLM [Quadro K610M]                                                           | 1         | 2.5%    |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 2.5%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 2.5%    |
| Intel HD Graphics 5300                                                                   | 1         | 2.5%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 2.5%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 2.5%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 2.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.5%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 2.5%    |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 1         | 2.5%    |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                                          | 1         | 2.5%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 2.5%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 2.5%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 2.5%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 2.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 13        | 41.94%  |
| Intel + Nvidia | 8         | 25.81%  |
| 1 x Nvidia     | 4         | 12.9%   |
| 1 x AMD        | 4         | 12.9%   |
| Intel + AMD    | 2         | 6.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 27        | 84.38%  |
| Proprietary | 3         | 9.38%   |
| Unknown     | 2         | 6.25%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 13        | 41.94%  |
| 1.01-2.0   | 9         | 29.03%  |
| 3.01-4.0   | 4         | 12.9%   |
| 0.51-1.0   | 3         | 9.68%   |
| 0.01-0.5   | 2         | 6.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 11        | 24.44%  |
| LG Display           | 8         | 17.78%  |
| Lenovo               | 4         | 8.89%   |
| Dell                 | 4         | 8.89%   |
| BOE                  | 4         | 8.89%   |
| Samsung Electronics  | 3         | 6.67%   |
| Chimei Innolux       | 3         | 6.67%   |
| BenQ                 | 2         | 4.44%   |
| ViewSonic            | 1         | 2.22%   |
| InfoVision           | 1         | 2.22%   |
| BOE Technology Group | 1         | 2.22%   |
| ASUSTek Computer     | 1         | 2.22%   |
| Ancor Communications | 1         | 2.22%   |
| Acer                 | 1         | 2.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 2         | 4.17%   |
| Dell U2718Q DELA0E9 3840x2160 609x349mm 27.6-inch                     | 2         | 4.17%   |
| BenQ GL2760 BNQ78D5 1920x1080 598x336mm 27.0-inch                     | 2         | 4.17%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch         | 2         | 4.17%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 2         | 4.17%   |
| ViewSonic VX2433wm VSC3822 1920x1080 520x290mm 23.4-inch              | 1         | 2.08%   |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch     | 1         | 2.08%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 1         | 2.08%   |
| Samsung Electronics LCD Monitor SDC3256 1920x1080 382x215mm 17.3-inch | 1         | 2.08%   |
| Samsung Electronics C32HG7x SAM0E14 2560x1440 697x392mm 31.5-inch     | 1         | 2.08%   |
| LG Display LCD Monitor LGD0609 1920x1080 309x174mm 14.0-inch          | 1         | 2.08%   |
| LG Display LCD Monitor LGD04BD 1366x768 344x194mm 15.5-inch           | 1         | 2.08%   |
| LG Display LCD Monitor LGD047C 1366x768 310x174mm 14.0-inch           | 1         | 2.08%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 1         | 2.08%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch           | 1         | 2.08%   |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch          | 1         | 2.08%   |
| Lenovo T24i-10 LEN61A6 1920x1080 527x296mm 23.8-inch                  | 1         | 2.08%   |
| Lenovo LEN T2424pA LEN60C8 1920x1080 527x296mm 23.8-inch              | 1         | 2.08%   |
| Lenovo LEN T2254pC LEN60CC 1680x1050 474x296mm 22.0-inch              | 1         | 2.08%   |
| Lenovo LEN P27u-10 LEN61B0 3840x2160 600x340mm 27.2-inch              | 1         | 2.08%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 1         | 2.08%   |
| Dell S3221QS DELD105 3840x2160 697x392mm 31.5-inch                    | 1         | 2.08%   |
| Dell P2719H DEL4184 1920x1080 598x336mm 27.0-inch                     | 1         | 2.08%   |
| Dell P2414H DELA09C 1920x1080 527x297mm 23.8-inch                     | 1         | 2.08%   |
| Dell E2009W DEL4240 1680x1050 433x271mm 20.1-inch                     | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN14E8 1920x1080 309x173mm 13.9-inch      | 1         | 2.08%   |
| BOE Technology Group LCD Monitor 1920x1080                            | 1         | 2.08%   |
| BOE LCD Monitor BOE08E8 1920x1080 344x194mm 15.5-inch                 | 1         | 2.08%   |
| BOE LCD Monitor BOE0819 1920x1080 344x194mm 15.5-inch                 | 1         | 2.08%   |
| BOE LCD Monitor BOE074F 1920x1080 309x173mm 13.9-inch                 | 1         | 2.08%   |
| BOE LCD Monitor BOE0630 1920x1080 344x194mm 15.5-inch                 | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO8074 1280x800 331x207mm 15.4-inch         | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch         | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO212D 1920x1080 293x165mm 13.2-inch        | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO106D 1920x1080 276x155mm 12.5-inch        | 1         | 2.08%   |
| ASUSTek Computer VP249 AUS24AF 1920x1080 527x296mm 23.8-inch          | 1         | 2.08%   |
| Ancor Communications VW246 ACI24F2 1920x1080 531x299mm 24.0-inch      | 1         | 2.08%   |
| Acer SA230 ACR057E 1920x1080 509x286mm 23.0-inch                      | 1         | 2.08%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 22        | 61.11%  |
| 1600x900 (HD+)     | 4         | 11.11%  |
| 1366x768 (WXGA)    | 4         | 11.11%  |
| 3840x2160 (4K)     | 3         | 8.33%   |
| 2560x1440 (QHD)    | 1         | 2.78%   |
| 1680x1050 (WSXGA+) | 1         | 2.78%   |
| 1280x800 (WXGA)    | 1         | 2.78%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 14        | 30.43%  |
| 14      | 10        | 21.74%  |
| 27      | 7         | 15.22%  |
| 24      | 4         | 8.7%    |
| 13      | 3         | 6.52%   |
| 31      | 2         | 4.35%   |
| 23      | 2         | 4.35%   |
| 22      | 1         | 2.17%   |
| 17      | 1         | 2.17%   |
| 12      | 1         | 2.17%   |
| Unknown | 1         | 2.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 26        | 59.09%  |
| 501-600     | 10        | 22.73%  |
| 601-700     | 3         | 6.82%   |
| 201-300     | 2         | 4.55%   |
| 401-500     | 1         | 2.27%   |
| 351-400     | 1         | 2.27%   |
| Unknown     | 1         | 2.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 29        | 90.63%  |
| 16/10   | 2         | 6.25%   |
| Unknown | 1         | 3.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 14        | 31.11%  |
| 81-90          | 12        | 26.67%  |
| 301-350        | 7         | 15.56%  |
| 201-250        | 6         | 13.33%  |
| 351-500        | 2         | 4.44%   |
| 71-80          | 1         | 2.22%   |
| 61-70          | 1         | 2.22%   |
| 121-130        | 1         | 2.22%   |
| Unknown        | 1         | 2.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 22        | 53.66%  |
| 51-100  | 11        | 26.83%  |
| 101-120 | 4         | 9.76%   |
| 161-240 | 3         | 7.32%   |
| Unknown | 1         | 2.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 17        | 54.84%  |
| 2     | 7         | 22.58%  |
| 3     | 4         | 12.9%   |
| 0     | 2         | 6.45%   |
| 4     | 1         | 3.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 24        | 54.55%  |
| Realtek Semiconductor | 10        | 22.73%  |
| Qualcomm Atheros      | 3         | 6.82%   |
| Lenovo                | 2         | 4.55%   |
| Ralink Technology     | 1         | 2.27%   |
| NetGear               | 1         | 2.27%   |
| Fibocom               | 1         | 2.27%   |
| Broadcom Limited      | 1         | 2.27%   |
| Broadcom              | 1         | 2.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                        | 5         | 8.2%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 6.56%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4         | 6.56%   |
| Intel Wireless 7265                                               | 3         | 4.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 4.92%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 3.28%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 3.28%   |
| Intel Wireless 8260                                               | 2         | 3.28%   |
| Intel Wireless 7260                                               | 2         | 3.28%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 3.28%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 3.28%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 3.28%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 3.28%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 3.28%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 1.64%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 1.64%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 1.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.64%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                   | 1         | 1.64%   |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 1.64%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 1.64%   |
| Intel Wireless-AC 9260                                            | 1         | 1.64%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 1.64%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.64%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 1.64%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 1         | 1.64%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.64%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.64%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.64%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.64%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.64%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.64%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.64%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 1.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 1.64%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                 | 1         | 1.64%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 1         | 1.64%   |
| Broadcom BCM43142 802.11b/g/n                                     | 1         | 1.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 23        | 71.88%  |
| Qualcomm Atheros      | 3         | 9.38%   |
| Realtek Semiconductor | 2         | 6.25%   |
| Ralink Technology     | 1         | 3.13%   |
| NetGear               | 1         | 3.13%   |
| Fibocom               | 1         | 3.13%   |
| Broadcom              | 1         | 3.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                 | 5         | 15.63%  |
| Intel Wireless 7265                                        | 3         | 9.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 2         | 6.25%   |
| Intel Wireless 8260                                        | 2         | 6.25%   |
| Intel Wireless 7260                                        | 2         | 6.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]               | 2         | 6.25%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1         | 3.13%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 1         | 3.13%   |
| Ralink MT7601U Wireless Adapter                            | 1         | 3.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1         | 3.13%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]            | 1         | 3.13%   |
| Intel Wireless-AC 9260                                     | 1         | 3.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 1         | 3.13%   |
| Intel Wi-Fi 6 AX201                                        | 1         | 3.13%   |
| Intel Wi-Fi 6 AX200                                        | 1         | 3.13%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection    | 1         | 3.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 1         | 3.13%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1         | 3.13%   |
| Intel Centrino Ultimate-N 6300                             | 1         | 3.13%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                   | 1         | 3.13%   |
| Fibocom L830-EB-00 LTE WWAN Modem                          | 1         | 3.13%   |
| Broadcom BCM43142 802.11b/g/n                              | 1         | 3.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 16        | 55.17%  |
| Realtek Semiconductor | 10        | 34.48%  |
| Lenovo                | 2         | 6.9%    |
| Broadcom Limited      | 1         | 3.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 13.79%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4         | 13.79%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 10.34%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 6.9%    |
| Intel Ethernet Connection I217-LM                                 | 2         | 6.9%    |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 6.9%    |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 6.9%    |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 6.9%    |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 3.45%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 3.45%   |
| Intel Ethernet Connection I219-V                                  | 1         | 3.45%   |
| Intel Ethernet Connection I217-V                                  | 1         | 3.45%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 3.45%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 3.45%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 3.45%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 1         | 3.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 29        | 53.7%   |
| Ethernet | 25        | 46.3%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 21        | 65.63%  |
| Ethernet | 11        | 34.38%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 22        | 73.33%  |
| 1     | 8         | 26.67%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 21        | 63.64%  |
| Yes  | 12        | 36.36%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 12        | 66.67%  |
| Qualcomm Atheros Communications | 3         | 16.67%  |
| Broadcom                        | 2         | 11.11%  |
| Realtek Semiconductor           | 1         | 5.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 7         | 38.89%  |
| Qualcomm Atheros  Bluetooth Device             | 2         | 11.11%  |
| Intel AX201 Bluetooth                          | 2         | 11.11%  |
| Realtek  Bluetooth 4.2 Adapter                 | 1         | 5.56%   |
| Qualcomm Atheros AR9462 Bluetooth              | 1         | 5.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 1         | 5.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1         | 5.56%   |
| Intel AX210 Bluetooth                          | 1         | 5.56%   |
| Broadcom BCM43142A0 Bluetooth 4.0              | 1         | 5.56%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 1         | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor    | Notebooks | Percent |
|-----------|-----------|---------|
| Intel     | 27        | 60%     |
| Nvidia    | 5         | 11.11%  |
| AMD       | 5         | 11.11%  |
| GN Netcom | 4         | 8.89%   |
| Lenovo    | 3         | 6.67%   |
| Unknown   | 1         | 2.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 7         | 12.96%  |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 5.56%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 5.56%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 5.56%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 3.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 3.7%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 3.7%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 3.7%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 3.7%    |
| Unknown Definitive Sym1                                                                           | 1         | 1.85%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 1.85%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 1.85%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 1.85%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 1         | 1.85%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                                          | 1         | 1.85%   |
| Lenovo ThinkPad Dock USB Audio                                                                    | 1         | 1.85%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1.85%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 1.85%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.85%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 1.85%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 1.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1         | 1.85%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.85%   |
| GN Netcom Jabra SPEAK 510                                                                         | 1         | 1.85%   |
| GN Netcom Jabra PRO 9470                                                                          | 1         | 1.85%   |
| GN Netcom Jabra Link 370                                                                          | 1         | 1.85%   |
| GN Netcom Jabra EVOLVE LINK                                                                       | 1         | 1.85%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 1.85%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.85%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 1.85%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.85%   |
| AMD High Definition Audio Controller                                                              | 1         | 1.85%   |
| AMD FCH Azalia Controller                                                                         | 1         | 1.85%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 1.85%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 1.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 4         | 26.67%  |
| SK hynix            | 3         | 20%     |
| Micron Technology   | 3         | 20%     |
| Kingston            | 2         | 13.33%  |
| Unknown             | 1         | 6.67%   |
| Corsair             | 1         | 6.67%   |
| Avant               | 1         | 6.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 2         | 13.33%  |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                  | 1         | 6.67%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 6.67%   |
| SK hynix RAM HMAA1GS6CMR8N-VK 8GB Row Of Chips DDR4 2667MT/s | 1         | 6.67%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s | 1         | 6.67%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s     | 1         | 6.67%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s       | 1         | 6.67%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s  | 1         | 6.67%   |
| Micron RAM 16JTF1G64HZ-1G4D1 8GB SODIMM DDR3 1333MT/s        | 1         | 6.67%   |
| Micron RAM 16ATF2G64HZ-2G1A1 16384MB SODIMM DDR4 2133MT/s    | 1         | 6.67%   |
| Kingston RAM KX830D-ELC 4GB SODIMM DDR3 1333MT/s             | 1         | 6.67%   |
| Kingston RAM KN2M64-ETB 8GB SODIMM DDR3 1600MT/s             | 1         | 6.67%   |
| Corsair RAM CMSX32GX4M2A2666C18 16GB SODIMM DDR4 2667MT/s    | 1         | 6.67%   |
| Avant RAM H6451U66G1600G 4096MB SODIMM DDR3 1600MT/s         | 1         | 6.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 8         | 53.33%  |
| DDR4   | 6         | 40%     |
| LPDDR4 | 1         | 6.67%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 12        | 80%     |
| Row Of Chips | 3         | 20%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 7         | 46.67%  |
| 4096  | 5         | 33.33%  |
| 16384 | 2         | 13.33%  |
| 32768 | 1         | 6.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 6         | 40%     |
| 2667  | 3         | 20%     |
| 1333  | 2         | 13.33%  |
| 4267  | 1         | 6.67%   |
| 2400  | 1         | 6.67%   |
| 2133  | 1         | 6.67%   |
| 1866  | 1         | 6.67%   |

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
| Chicony Electronics   | 7         | 29.17%  |
| Suyin                 | 3         | 12.5%   |
| Realtek Semiconductor | 3         | 12.5%   |
| Logitech              | 3         | 12.5%   |
| Lite-On Technology    | 3         | 12.5%   |
| IMC Networks          | 3         | 12.5%   |
| Microdia              | 1         | 4.17%   |
| Acer                  | 1         | 4.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Chicony Integrated Camera               | 4         | 16%     |
| Realtek Integrated_Webcam_HD            | 2         | 8%      |
| Lite-On Integrated Camera               | 2         | 8%      |
| IMC Networks VGA UVC WebCam             | 2         | 8%      |
| Chicony Integrated Camera (1280x720@30) | 2         | 8%      |
| Suyin Integrated_Webcam_HD              | 1         | 4%      |
| Suyin HP Truevision HD                  | 1         | 4%      |
| Suyin Asus Integrated Webcam            | 1         | 4%      |
| Realtek EasyCamera                      | 1         | 4%      |
| Microdia Webcam Vitade AF               | 1         | 4%      |
| Logitech Webcam C920-C                  | 1         | 4%      |
| Logitech HD Webcam C615                 | 1         | 4%      |
| Logitech BRIO Ultra HD Webcam           | 1         | 4%      |
| Lite-On HP HD Camera                    | 1         | 4%      |
| IMC Networks Integrated Camera          | 1         | 4%      |
| Chicony ThinkPad T490 Webcam            | 1         | 4%      |
| Chicony Integrated IR Camera            | 1         | 4%      |
| Acer SunplusIT Integrated Camera        | 1         | 4%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Synaptics        | 6         | 54.55%  |
| Validity Sensors | 5         | 45.45%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 27.27%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 27.27%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 18.18%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 9.09%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 9.09%   |
| Unknown                                                                    | 1         | 9.09%   |

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
| 1     | 16        | 50%     |
| 0     | 12        | 37.5%   |
| 2     | 3         | 9.38%   |
| 3     | 1         | 3.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 11        | 47.83%  |
| Chipcard           | 5         | 21.74%  |
| Storage            | 2         | 8.7%    |
| Graphics card      | 2         | 8.7%    |
| Net/wireless       | 1         | 4.35%   |
| Card reader        | 1         | 4.35%   |
| Bluetooth          | 1         | 4.35%   |

