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

Total: 57

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
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
| Lenovo   | Legion 5 15IMH05 82AU       | [2e24ad5259](https://linux-hardware.org/?probe=2e24ad5259) | Aug 19, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | [32ad696b97](https://linux-hardware.org/?probe=32ad696b97) | Aug 18, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | [2ccb1f7da2](https://linux-hardware.org/?probe=2ccb1f7da2) | Aug 16, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | [b2d5f563dc](https://linux-hardware.org/?probe=b2d5f563dc) | Aug 15, 2021 |
| Dell     | Inspiron 3542               | [0909599e9c](https://linux-hardware.org/?probe=0909599e9c) | Aug 11, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | [ba7afba1a6](https://linux-hardware.org/?probe=ba7afba1a6) | Jul 08, 2021 |
| Lenovo   | ThinkPad L490 20Q5CTO1WW    | [0225c17d79](https://linux-hardware.org/?probe=0225c17d79) | Jul 02, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | [505b82b2de](https://linux-hardware.org/?probe=505b82b2de) | Jun 06, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | [75b2ef5126](https://linux-hardware.org/?probe=75b2ef5126) | May 13, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | [734a4fbc56](https://linux-hardware.org/?probe=734a4fbc56) | May 09, 2021 |
| ASUSTek  | UX305FA                     | [0bf50fba2d](https://linux-hardware.org/?probe=0bf50fba2d) | Mar 15, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | [ff355a9bb1](https://linux-hardware.org/?probe=ff355a9bb1) | Mar 11, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | [20ac06d200](https://linux-hardware.org/?probe=20ac06d200) | Mar 06, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | [9f67379954](https://linux-hardware.org/?probe=9f67379954) | Mar 04, 2021 |
| Lenovo   | ThinkPad L490 20Q5CTO1WW    | [db0f24aee5](https://linux-hardware.org/?probe=db0f24aee5) | Mar 01, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | [f0c8352496](https://linux-hardware.org/?probe=f0c8352496) | Mar 01, 2021 |
| Dell     | Latitude 7410               | [5b725b01aa](https://linux-hardware.org/?probe=5b725b01aa) | Feb 26, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | [3145841279](https://linux-hardware.org/?probe=3145841279) | Feb 25, 2021 |
| Lenovo   | Legion 5 15IMH05 82AU       | [835e8cad03](https://linux-hardware.org/?probe=835e8cad03) | Feb 25, 2021 |
| Dell     | Latitude 7410               | [430ac9fa0c](https://linux-hardware.org/?probe=430ac9fa0c) | Feb 24, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | [73aece12d7](https://linux-hardware.org/?probe=73aece12d7) | Feb 24, 2021 |
| Lenovo   | ThinkPad T490 20N3S77600    | [26e61c39f2](https://linux-hardware.org/?probe=26e61c39f2) | Feb 24, 2021 |
| Dell     | Latitude 7410               | [7aeb2cc674](https://linux-hardware.org/?probe=7aeb2cc674) | Feb 22, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | [58cdbf1ae1](https://linux-hardware.org/?probe=58cdbf1ae1) | Feb 18, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | [8af2c8d83c](https://linux-hardware.org/?probe=8af2c8d83c) | Feb 05, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | [685b544c29](https://linux-hardware.org/?probe=685b544c29) | Jan 12, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | [68957c71fd](https://linux-hardware.org/?probe=68957c71fd) | Jan 07, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | [7d50d4e9d5](https://linux-hardware.org/?probe=7d50d4e9d5) | Jan 07, 2021 |
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
| Oracle Linux 8.5 | 11        | 34.38%  |
| Oracle Linux 8.3 | 6         | 18.75%  |
| Oracle Linux 8.4 | 5         | 15.63%  |
| Oracle Linux 8.1 | 3         | 9.38%   |
| Oracle Linux 7.8 | 2         | 6.25%   |
| Oracle Linux 7.7 | 2         | 6.25%   |
| Oracle Linux 8.2 | 1         | 3.13%   |
| Oracle Linux 7.9 | 1         | 3.13%   |
| Oracle Linux 7.6 | 1         | 3.13%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Oracle Linux | 26        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Notebooks | Percent |
|------------------------------------|-----------|---------|
| 5.4.17-2036.103.3.1.el8uek.x86_64  | 3         | 8.82%   |
| 4.18.0-348.12.2.el8_5.x86_64       | 3         | 8.82%   |
| 5.4.17-2136.304.4.3.el8uek.x86_64  | 2         | 5.88%   |
| 5.4.17-2102.204.4.2.el8uek.x86_64  | 2         | 5.88%   |
| 5.4.17-2102.202.5.el8uek.x86_64    | 2         | 5.88%   |
| 4.18.0-147.3.1.el8_1.x86_64        | 2         | 5.88%   |
| 5.4.17-2136.306.1.3.el8uek.x86_64  | 1         | 2.94%   |
| 5.4.17-2136.305.5.4.el8uek.x86_64  | 1         | 2.94%   |
| 5.4.17-2136.305.5.3.el8uek.x86_64  | 1         | 2.94%   |
| 5.4.17-2136.305.5.2.el8uek.x86_64  | 1         | 2.94%   |
| 5.4.17-2136.301.1.4.el8uek.x86_64  | 1         | 2.94%   |
| 5.4.17-2102.205.7.3.el8uek.x86_64  | 1         | 2.94%   |
| 5.4.17-2102.201.3.el8uek.x86_64    | 1         | 2.94%   |
| 5.4.17-2102.200.13.el8uek.x86_64   | 1         | 2.94%   |
| 5.4.17-2036.104.4.el8uek.x86_64    | 1         | 2.94%   |
| 5.4.17-2011.0.7.el8uek.x86_64      | 1         | 2.94%   |
| 5.15.2-1.el8.elrepo.x86_64         | 1         | 2.94%   |
| 5.14.1-1.el8.elrepo.x86_64         | 1         | 2.94%   |
| 5.11.1-1.el8.elrepo.x86_64         | 1         | 2.94%   |
| 4.18.0-240.10.1.el8_3.x86_64       | 1         | 2.94%   |
| 4.18.0-193.1.2.el8_2.x86_64        | 1         | 2.94%   |
| 4.14.35-2047.510.4.1.el7uek.x86_64 | 1         | 2.94%   |
| 4.14.35-1902.4.8.el7uek.x86_64     | 1         | 2.94%   |
| 4.14.35-1902.300.11.el7uek.x86_64  | 1         | 2.94%   |
| 4.14.35-1818.3.3.el7uek.x86_64     | 1         | 2.94%   |
| 3.10.0-1127.10.1.el7.x86_64        | 1         | 2.94%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.17  | 13        | 46.43%  |
| 4.18.0  | 7         | 25%     |
| 4.14.35 | 4         | 14.29%  |
| 5.15.2  | 1         | 3.57%   |
| 5.14.1  | 1         | 3.57%   |
| 5.11.1  | 1         | 3.57%   |
| 3.10.0  | 1         | 3.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 13        | 46.43%  |
| 4.18    | 7         | 25%     |
| 4.14    | 4         | 14.29%  |
| 5.15    | 1         | 3.57%   |
| 5.14    | 1         | 3.57%   |
| 5.11    | 1         | 3.57%   |
| 3.10    | 1         | 3.57%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 26        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GNOME   | 20        | 71.43%  |
| Unknown | 3         | 10.71%  |
| XFCE    | 2         | 7.14%   |
| MATE    | 2         | 7.14%   |
| KDE4    | 1         | 3.57%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 14        | 50%     |
| Wayland | 13        | 46.43%  |
| Unknown | 1         | 3.57%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 14        | 51.85%  |
| GDM     | 13        | 48.15%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 16        | 59.26%  |
| en_GB   | 3         | 11.11%  |
| de_DE   | 3         | 11.11%  |
| Unknown | 2         | 7.41%   |
| pt_BR   | 1         | 3.7%    |
| pl_PL   | 1         | 3.7%    |
| en_AU   | 1         | 3.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 14        | 51.85%  |
| EFI  | 13        | 48.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Xfs     | 21        | 77.78%  |
| Ext4    | 4         | 14.81%  |
| Unknown | 2         | 7.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 16        | 59.26%  |
| GPT     | 7         | 25.93%  |
| MBR     | 4         | 14.81%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 24        | 92.31%  |
| Yes       | 2         | 7.69%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 25        | 96.15%  |
| Yes       | 1         | 3.85%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 13        | 50%     |
| Dell             | 6         | 23.08%  |
| Hewlett-Packard  | 3         | 11.54%  |
| ASUSTek Computer | 3         | 11.54%  |
| Standard         | 1         | 3.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Lenovo ThinkPad T450 20BUS14900           | 2         | 7.69%   |
| ASUS X510UR                               | 2         | 7.69%   |
| Standard BW Series                        | 1         | 3.85%   |
| Lenovo ThinkPad X280 20KES4H34G           | 1         | 3.85%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QWS1R800 | 1         | 3.85%   |
| Lenovo ThinkPad T490 20N3S77600           | 1         | 3.85%   |
| Lenovo ThinkPad T480 20L6S56Y2X           | 1         | 3.85%   |
| Lenovo ThinkPad T480 20L5A07TAU           | 1         | 3.85%   |
| Lenovo ThinkPad P50s 20FL000MUS           | 1         | 3.85%   |
| Lenovo ThinkPad L540 20AVCTO1WW           | 1         | 3.85%   |
| Lenovo ThinkPad L490 20Q5CTO1WW           | 1         | 3.85%   |
| Lenovo Legion 5 15IMH05 82AU              | 1         | 3.85%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS       | 1         | 3.85%   |
| Lenovo IdeaPad 300-15ISK 80RS             | 1         | 3.85%   |
| HP ZBook 15                               | 1         | 3.85%   |
| HP ProBook 445 G6                         | 1         | 3.85%   |
| HP Notebook                               | 1         | 3.85%   |
| Dell Precision M4800                      | 1         | 3.85%   |
| Dell Precision M4600                      | 1         | 3.85%   |
| Dell Latitude E6420                       | 1         | 3.85%   |
| Dell Latitude 7420                        | 1         | 3.85%   |
| Dell Latitude 7410                        | 1         | 3.85%   |
| Dell Inspiron 3542                        | 1         | 3.85%   |
| ASUS UX305FA                              | 1         | 3.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Lenovo ThinkPad | 10        | 38.46%  |
| Dell Latitude   | 3         | 11.54%  |
| Lenovo IdeaPad  | 2         | 7.69%   |
| Dell Precision  | 2         | 7.69%   |
| ASUS X510UR     | 2         | 7.69%   |
| Standard BW     | 1         | 3.85%   |
| Lenovo Legion   | 1         | 3.85%   |
| HP ZBook        | 1         | 3.85%   |
| HP ProBook      | 1         | 3.85%   |
| HP Notebook     | 1         | 3.85%   |
| Dell Inspiron   | 1         | 3.85%   |
| ASUS UX305FA    | 1         | 3.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 5         | 19.23%  |
| 2016 | 4         | 15.38%  |
| 2020 | 3         | 11.54%  |
| 2018 | 3         | 11.54%  |
| 2014 | 3         | 11.54%  |
| 2017 | 2         | 7.69%   |
| 2015 | 2         | 7.69%   |
| 2013 | 2         | 7.69%   |
| 2011 | 2         | 7.69%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 26        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 24        | 92.31%  |
| Enabled  | 2         | 7.69%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 26        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 32.01-64.0 | 8         | 29.63%  |
| 8.01-16.0  | 8         | 29.63%  |
| 4.01-8.0   | 5         | 18.52%  |
| 3.01-4.0   | 3         | 11.11%  |
| 16.01-24.0 | 3         | 11.11%  |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 9         | 28.13%  |
| 2.01-3.0   | 8         | 25%     |
| 8.01-16.0  | 7         | 21.88%  |
| 3.01-4.0   | 3         | 9.38%   |
| 1.01-2.0   | 3         | 9.38%   |
| 24.01-32.0 | 1         | 3.13%   |
| 0.51-1.0   | 1         | 3.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 24        | 92.31%  |
| 2      | 2         | 7.69%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 19        | 73.08%  |
| Yes       | 7         | 26.92%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 21        | 80.77%  |
| No        | 5         | 19.23%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 96.15%  |
| No        | 1         | 3.85%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 16        | 59.26%  |
| No        | 11        | 40.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 10        | 37.04%  |
| Germany     | 4         | 14.81%  |
| UK          | 3         | 11.11%  |
| Netherlands | 2         | 7.41%   |
| Brazil      | 2         | 7.41%   |
| Romania     | 1         | 3.7%    |
| Poland      | 1         | 3.7%    |
| Pakistan    | 1         | 3.7%    |
| Bulgaria    | 1         | 3.7%    |
| Australia   | 1         | 3.7%    |
| Argentina   | 1         | 3.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Seattle          | 2         | 6.9%    |
| San Diego        | 2         | 6.9%    |
| Utrecht          | 1         | 3.45%   |
| Sofia            | 1         | 3.45%   |
| Siegen           | 1         | 3.45%   |
| Shrewsbury       | 1         | 3.45%   |
| Santo AndrÃ©   | 1         | 3.45%   |
| Rocklin          | 1         | 3.45%   |
| Port Saint Lucie | 1         | 3.45%   |
| Polch            | 1         | 3.45%   |
| Maple Valley     | 1         | 3.45%   |
| London           | 1         | 3.45%   |
| Kreuztal         | 1         | 3.45%   |
| Karachi          | 1         | 3.45%   |
| Ituzaingo        | 1         | 3.45%   |
| Freudenberg      | 1         | 3.45%   |
| Eppelheim        | 1         | 3.45%   |
| Dallas           | 1         | 3.45%   |
| Colorado Springs | 1         | 3.45%   |
| ChorzÃ³w       | 1         | 3.45%   |
| Chicago          | 1         | 3.45%   |
| Canberra         | 1         | 3.45%   |
| Campinas         | 1         | 3.45%   |
| Bucharest        | 1         | 3.45%   |
| Bracknell        | 1         | 3.45%   |
| Berlin           | 1         | 3.45%   |
| Amsterdam        | 1         | 3.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 11        | 13     | 39.29%  |
| SanDisk                 | 6         | 7      | 21.43%  |
| Unknown                 | 2         | 2      | 7.14%   |
| Seagate                 | 2         | 2      | 7.14%   |
| WDC                     | 1         | 1      | 3.57%   |
| Union Memory (Shenzhen) | 1         | 2      | 3.57%   |
| Micron Technology       | 1         | 4      | 3.57%   |
| Lite-On                 | 1         | 1      | 3.57%   |
| Lenovo                  | 1         | 1      | 3.57%   |
| Kingston                | 1         | 5      | 3.57%   |
| HGST                    | 1         | 1      | 3.57%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| SanDisk SSD PLUS 1000GB                      | 2         | 6.9%    |
| Samsung MZ7LN512HMJP-000L7 512GB SSD         | 2         | 6.9%    |
| WDC WD10JPCX-24UE4T0 1TB                     | 1         | 3.45%   |
| Unknown SD/MMC/MS PRO 16GB                   | 1         | 3.45%   |
| Unknown MMC Card  256GB                      | 1         | 3.45%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 3.45%   |
| Seagate ST9750420AS 752GB                    | 1         | 3.45%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 3.45%   |
| SanDisk SDSSDH3512G 512GB                    | 1         | 3.45%   |
| SanDisk SD7SN3Q256G1002 256GB SSD            | 1         | 3.45%   |
| SanDisk SD6SB1M-256G-1006 256GB SSD          | 1         | 3.45%   |
| Sandisk NVMe SSD Drive 512GB                 | 1         | 3.45%   |
| Samsung SSD SM841N 2.5 7mm 512GB             | 1         | 3.45%   |
| Samsung SSD PM830 2.5 7mm 256GB              | 1         | 3.45%   |
| Samsung SSD 850 PRO 256GB                    | 1         | 3.45%   |
| Samsung PM9A1 NVMe 512GB                     | 1         | 3.45%   |
| Samsung NVMe SSD Drive 512GB                 | 1         | 3.45%   |
| Samsung MZVLW256HEHP-000L7 256GB             | 1         | 3.45%   |
| Samsung MZVLB1T0HBLR-000L7 1TB               | 1         | 3.45%   |
| Samsung MZ7LN512HCHP-000L1 512GB SSD         | 1         | 3.45%   |
| Samsung MZ7LN256HCHP-000L7 256GB SSD         | 1         | 3.45%   |
| Micron NVMe SSD Drive 256GB                  | 1         | 3.45%   |
| Micron 2200S NVMe 256GB                      | 1         | 3.45%   |
| Lite-On NVMe SSD Drive 512GB                 | 1         | 3.45%   |
| Lenovo LENSE30512GMSP34MEAT3TA 512GB         | 1         | 3.45%   |
| Kingston NVMe SSD Drive 1TB                  | 1         | 3.45%   |
| HGST HTS545050A7E380 500GB                   | 1         | 3.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 40%     |
| WDC     | 1         | 1      | 20%     |
| Unknown | 1         | 1      | 20%     |
| HGST    | 1         | 1      | 20%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 7      | 58.33%  |
| SanDisk             | 5         | 5      | 41.67%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 12        | 12     | 42.86%  |
| NVMe | 10        | 21     | 35.71%  |
| HDD  | 5         | 5      | 17.86%  |
| MMC  | 1         | 1      | 3.57%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 16        | 16     | 57.14%  |
| NVMe | 10        | 21     | 35.71%  |
| SAS  | 1         | 1      | 3.57%   |
| MMC  | 1         | 1      | 3.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 10        | 10     | 58.82%  |
| 0.01-0.5   | 7         | 7      | 41.18%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 6         | 22.22%  |
| Unknown    | 6         | 22.22%  |
| 101-250    | 5         | 18.52%  |
| 1-20       | 5         | 18.52%  |
| 501-1000   | 4         | 14.81%  |
| 51-100     | 1         | 3.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 11        | 39.29%  |
| Unknown | 6         | 21.43%  |
| 21-50   | 4         | 14.29%  |
| 251-500 | 3         | 10.71%  |
| 101-250 | 2         | 7.14%   |
| 51-100  | 2         | 7.14%   |

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
| Detected | 16        | 27     | 57.14%  |
| Works    | 10        | 10     | 35.71%  |
| Malfunc  | 2         | 2      | 7.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 15        | 53.57%  |
| Samsung Electronics         | 4         | 14.29%  |
| AMD                         | 3         | 10.71%  |
| Union Memory (Shenzhen)     | 1         | 3.57%   |
| Sandisk                     | 1         | 3.57%   |
| Micron Technology           | 1         | 3.57%   |
| Lite-On Technology          | 1         | 3.57%   |
| Lenovo                      | 1         | 3.57%   |
| Kingston Technology Company | 1         | 3.57%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 4         | 14.29%  |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 10.71%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 3         | 10.71%  |
| AMD FCH SATA Controller [AHCI mode]                                              | 3         | 10.71%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 7.14%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 7.14%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 3.57%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 3.57%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 3.57%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 3.57%   |
| Micron Non-Volatile memory controller                                            | 1         | 3.57%   |
| Lite-On Non-Volatile memory controller                                           | 1         | 3.57%   |
| Lenovo Non-Volatile memory controller                                            | 1         | 3.57%   |
| Kingston Company A2000 NVMe SSD                                                  | 1         | 3.57%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 3.57%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 3.57%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 1         | 3.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 15        | 53.57%  |
| NVMe | 10        | 35.71%  |
| RAID | 3         | 10.71%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 23        | 88.46%  |
| AMD    | 3         | 11.54%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-7500U CPU @ 2.70GHz               | 2         | 7.69%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 2         | 7.69%   |
| Intel Core i5-8350U CPU @ 1.70GHz               | 2         | 7.69%   |
| Intel Core i5-5300U CPU @ 2.30GHz               | 2         | 7.69%   |
| Intel Processor 5Y10 CPU @ 0.80GHz              | 1         | 3.85%   |
| Intel Core i9-9880H CPU @ 2.30GHz               | 1         | 3.85%   |
| Intel Core i7-8665U CPU @ 1.90GHz               | 1         | 3.85%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 1         | 3.85%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz              | 1         | 3.85%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz              | 1         | 3.85%   |
| Intel Core i7-2860QM CPU @ 2.50GHz              | 1         | 3.85%   |
| Intel Core i7-2760QM CPU @ 2.40GHz              | 1         | 3.85%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 1         | 3.85%   |
| Intel Core i7-10610U CPU @ 1.80GHz              | 1         | 3.85%   |
| Intel Core i5-8365U CPU @ 1.60GHz               | 1         | 3.85%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 1         | 3.85%   |
| Intel Core i5-4210M CPU @ 2.60GHz               | 1         | 3.85%   |
| Intel Celeron CPU N3010 @ 1.04GHz               | 1         | 3.85%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz         | 1         | 3.85%   |
| AMD Ryzen 7 PRO 2700U w/ Radeon Vega Mobile Gfx | 1         | 3.85%   |
| AMD A9-9420e RADEON R5, 5 COMPUTE CORES 2C+3G   | 1         | 3.85%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics     | 1         | 3.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i7   | 12        | 46.15%  |
| Intel Core i5   | 7         | 26.92%  |
| Other           | 3         | 11.54%  |
| Intel Core i9   | 1         | 3.85%   |
| Intel Celeron   | 1         | 3.85%   |
| AMD Ryzen 7 PRO | 1         | 3.85%   |
| AMD A8          | 1         | 3.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 12        | 46.15%  |
| 2      | 11        | 42.31%  |
| 8      | 1         | 3.85%   |
| 6      | 1         | 3.85%   |
| 1      | 1         | 3.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 26        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 23        | 88.46%  |
| 1      | 3         | 11.54%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 25        | 92.59%  |
| Unknown        | 2         | 7.41%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ec    | 3         | 11.54%  |
| 0x806ea    | 3         | 11.54%  |
| 0x306d4    | 3         | 11.54%  |
| 0x306c3    | 3         | 11.54%  |
| 0x406e3    | 2         | 7.69%   |
| 0x206a7    | 2         | 7.69%   |
| Unknown    | 2         | 7.69%   |
| 0xa0652    | 1         | 3.85%   |
| 0x906ed    | 1         | 3.85%   |
| 0x806c1    | 1         | 3.85%   |
| 0x406c4    | 1         | 3.85%   |
| 0x40651    | 1         | 3.85%   |
| 0x0810100b | 1         | 3.85%   |
| 0x07030105 | 1         | 3.85%   |
| 0x06006705 | 1         | 3.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 9         | 34.62%  |
| Haswell     | 4         | 15.38%  |
| Broadwell   | 3         | 11.54%  |
| Skylake     | 2         | 7.69%   |
| SandyBridge | 2         | 7.69%   |
| Zen         | 1         | 3.85%   |
| TigerLake   | 1         | 3.85%   |
| Silvermont  | 1         | 3.85%   |
| Puma        | 1         | 3.85%   |
| Excavator   | 1         | 3.85%   |
| CometLake   | 1         | 3.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 20        | 58.82%  |
| Nvidia | 8         | 23.53%  |
| AMD    | 6         | 17.65%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 3         | 8.82%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 8.82%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 5.88%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 5.88%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 5.88%   |
| Intel HD Graphics 620                                                                    | 2         | 5.88%   |
| Intel HD Graphics 5500                                                                   | 2         | 5.88%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 2.94%   |
| Nvidia TU117M                                                                            | 1         | 2.94%   |
| Nvidia GM108GLM [Quadro K620M / Quadro M500M]                                            | 1         | 2.94%   |
| Nvidia GK208GLM [Quadro K610M]                                                           | 1         | 2.94%   |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 2.94%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 2.94%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 2.94%   |
| Intel HD Graphics 5300                                                                   | 1         | 2.94%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 2.94%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 2.94%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 2.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.94%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 1         | 2.94%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                                          | 1         | 2.94%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 2.94%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 2.94%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 2.94%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 2.94%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 12        | 46.15%  |
| Intel + Nvidia | 6         | 23.08%  |
| 1 x AMD        | 4         | 15.38%  |
| 1 x Nvidia     | 2         | 7.69%   |
| Intel + AMD    | 2         | 7.69%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 23        | 88.46%  |
| Proprietary | 2         | 7.69%   |
| Unknown     | 1         | 3.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 13        | 48.15%  |
| 1.01-2.0   | 7         | 25.93%  |
| 3.01-4.0   | 3         | 11.11%  |
| 0.51-1.0   | 2         | 7.41%   |
| 0.01-0.5   | 2         | 7.41%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 9         | 24.32%  |
| LG Display           | 8         | 21.62%  |
| Lenovo               | 4         | 10.81%  |
| Chimei Innolux       | 3         | 8.11%   |
| BOE                  | 3         | 8.11%   |
| Samsung Electronics  | 2         | 5.41%   |
| Dell                 | 2         | 5.41%   |
| BenQ                 | 2         | 5.41%   |
| ViewSonic            | 1         | 2.7%    |
| InfoVision           | 1         | 2.7%    |
| ASUSTek Computer     | 1         | 2.7%    |
| Ancor Communications | 1         | 2.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 2         | 5.26%   |
| BenQ GL2760 BNQ78D5 1920x1080 598x336mm 27.0-inch                     | 2         | 5.26%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch         | 2         | 5.26%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x174mm 14.0-inch        | 2         | 5.26%   |
| ViewSonic VX2433wm VSC3822 1920x1080 520x290mm 23.4-inch              | 1         | 2.63%   |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch     | 1         | 2.63%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 1         | 2.63%   |
| LG Display LCD Monitor LGD0609 1920x1080 309x174mm 14.0-inch          | 1         | 2.63%   |
| LG Display LCD Monitor LGD04BD 1366x768 344x194mm 15.5-inch           | 1         | 2.63%   |
| LG Display LCD Monitor LGD047C 1366x768 310x174mm 14.0-inch           | 1         | 2.63%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 1         | 2.63%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch           | 1         | 2.63%   |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch          | 1         | 2.63%   |
| Lenovo T24i-10 LEN61A6 1920x1080 527x296mm 23.8-inch                  | 1         | 2.63%   |
| Lenovo LEN T2424pA LEN60C8 1920x1080 527x296mm 23.8-inch              | 1         | 2.63%   |
| Lenovo LEN T2254pC LEN60CC 1680x1050 474x296mm 22.0-inch              | 1         | 2.63%   |
| Lenovo LEN P27u-10 LEN61B0 3840x2160 597x336mm 27.0-inch              | 1         | 2.63%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 1         | 2.63%   |
| Dell U2718Q DELA0E9 3840x2160 609x349mm 27.6-inch                     | 1         | 2.63%   |
| Dell P2719H DEL4184 1920x1080 598x336mm 27.0-inch                     | 1         | 2.63%   |
| Dell E2009W DEL4240 1680x1050 433x271mm 20.1-inch                     | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN14E8 1920x1080 310x170mm 13.9-inch      | 1         | 2.63%   |
| BOE LCD Monitor BOE08E8 1920x1080 344x194mm 15.5-inch                 | 1         | 2.63%   |
| BOE LCD Monitor BOE074F 1920x1080 309x173mm 13.9-inch                 | 1         | 2.63%   |
| BOE LCD Monitor BOE0630 1920x1080 344x194mm 15.5-inch                 | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO212D 1920x1080 293x165mm 13.2-inch        | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO106D 1920x1080 276x155mm 12.5-inch        | 1         | 2.63%   |
| ASUSTek Computer VP249 AUS24AF 1920x1080 530x300mm 24.0-inch          | 1         | 2.63%   |
| Ancor Communications VW246 ACI24F2 1920x1080 531x299mm 24.0-inch      | 1         | 2.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 19        | 65.52%  |
| 1366x768 (WXGA)    | 4         | 13.79%  |
| 1600x900 (HD+)     | 3         | 10.34%  |
| 3840x2160 (4K)     | 2         | 6.9%    |
| 1680x1050 (WSXGA+) | 1         | 3.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 12        | 33.33%  |
| 14     | 9         | 25%     |
| 27     | 5         | 13.89%  |
| 24     | 3         | 8.33%   |
| 13     | 3         | 8.33%   |
| 23     | 2         | 5.56%   |
| 22     | 1         | 2.78%   |
| 12     | 1         | 2.78%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 23        | 65.71%  |
| 501-600     | 8         | 22.86%  |
| 201-300     | 2         | 5.71%   |
| 601-700     | 1         | 2.86%   |
| 401-500     | 1         | 2.86%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 25        | 96.15%  |
| 16/10 | 1         | 3.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 12        | 34.29%  |
| 81-90          | 11        | 31.43%  |
| 301-350        | 5         | 14.29%  |
| 201-250        | 5         | 14.29%  |
| 71-80          | 1         | 2.86%   |
| 61-70          | 1         | 2.86%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 19        | 55.88%  |
| 51-100  | 8         | 23.53%  |
| 101-120 | 4         | 11.76%  |
| 161-240 | 3         | 8.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 16        | 61.54%  |
| 2     | 6         | 23.08%  |
| 3     | 2         | 7.69%   |
| 4     | 1         | 3.85%   |
| 0     | 1         | 3.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 20        | 52.63%  |
| Realtek Semiconductor | 9         | 23.68%  |
| Qualcomm Atheros      | 3         | 7.89%   |
| Lenovo                | 2         | 5.26%   |
| Ralink Technology     | 1         | 2.63%   |
| NetGear               | 1         | 2.63%   |
| Fibocom               | 1         | 2.63%   |
| Broadcom              | 1         | 2.63%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                        | 5         | 9.43%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4         | 7.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 5.66%   |
| Intel Wireless 7265                                               | 3         | 5.66%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 3.77%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 3.77%   |
| Intel Wireless 7260                                               | 2         | 3.77%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 3.77%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 3.77%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 3.77%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 3.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.77%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 1.89%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 1.89%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 1.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.89%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                   | 1         | 1.89%   |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 1.89%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 1.89%   |
| Intel Wireless-AC 9260                                            | 1         | 1.89%   |
| Intel Wireless 8260                                               | 1         | 1.89%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.89%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 1.89%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.89%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.89%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.89%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.89%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.89%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 1.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1         | 1.89%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 1.89%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                 | 1         | 1.89%   |
| Broadcom BCM43142 802.11b/g/n                                     | 1         | 1.89%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 19        | 67.86%  |
| Qualcomm Atheros      | 3         | 10.71%  |
| Realtek Semiconductor | 2         | 7.14%   |
| Ralink Technology     | 1         | 3.57%   |
| NetGear               | 1         | 3.57%   |
| Fibocom               | 1         | 3.57%   |
| Broadcom              | 1         | 3.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                 | 5         | 17.86%  |
| Intel Wireless 7265                                        | 3         | 10.71%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 2         | 7.14%   |
| Intel Wireless 7260                                        | 2         | 7.14%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1         | 3.57%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 1         | 3.57%   |
| Ralink MT7601U Wireless Adapter                            | 1         | 3.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1         | 3.57%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]            | 1         | 3.57%   |
| Intel Wireless-AC 9260                                     | 1         | 3.57%   |
| Intel Wireless 8260                                        | 1         | 3.57%   |
| Intel Wi-Fi 6 AX201                                        | 1         | 3.57%   |
| Intel Wi-Fi 6 AX200                                        | 1         | 3.57%   |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 1         | 3.57%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1         | 3.57%   |
| Intel Centrino Ultimate-N 6300                             | 1         | 3.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]               | 1         | 3.57%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                   | 1         | 3.57%   |
| Fibocom L830-EB-00 LTE WWAN Modem                          | 1         | 3.57%   |
| Broadcom BCM43142 802.11b/g/n                              | 1         | 3.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 14        | 56%     |
| Realtek Semiconductor | 9         | 36%     |
| Lenovo                | 2         | 8%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4         | 16%     |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 12%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 8%      |
| Intel Ethernet Connection I217-LM                                 | 2         | 8%      |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 8%      |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 8%      |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 8%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 8%      |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 4%      |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 4%      |
| Intel Ethernet Connection I219-V                                  | 1         | 4%      |
| Intel Ethernet Connection I217-V                                  | 1         | 4%      |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 4%      |
| Intel Ethernet Connection (4) I219-V                              | 1         | 4%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 25        | 54.35%  |
| Ethernet | 21        | 45.65%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 21        | 58.33%  |
| Ethernet | 15        | 41.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 19        | 73.08%  |
| 1     | 7         | 26.92%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 19        | 67.86%  |
| Yes  | 9         | 32.14%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 68.75%  |
| Qualcomm Atheros Communications | 3         | 18.75%  |
| Realtek Semiconductor           | 1         | 6.25%   |
| Broadcom                        | 1         | 6.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 7         | 43.75%  |
| Qualcomm Atheros  Bluetooth Device             | 2         | 12.5%   |
| Intel Bluetooth Device                         | 2         | 12.5%   |
| Realtek  Bluetooth 4.2 Adapter                 | 1         | 6.25%   |
| Qualcomm Atheros AR9462 Bluetooth              | 1         | 6.25%   |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 1         | 6.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1         | 6.25%   |
| Broadcom BCM43142A0 Bluetooth 4.0              | 1         | 6.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor    | Notebooks | Percent |
|-----------|-----------|---------|
| Intel     | 23        | 57.5%   |
| AMD       | 5         | 12.5%   |
| Nvidia    | 4         | 10%     |
| GN Netcom | 4         | 10%     |
| Lenovo    | 3         | 7.5%    |
| Unknown   | 1         | 2.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 7         | 14.29%  |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 6.12%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 6.12%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 6.12%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 4.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 4.08%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 4.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 4.08%   |
| Unknown Definitive Sym1                                                                           | 1         | 2.04%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 2.04%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 2.04%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 1         | 2.04%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                                          | 1         | 2.04%   |
| Lenovo ThinkPad Dock USB Audio                                                                    | 1         | 2.04%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 2.04%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 2.04%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 2.04%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 2.04%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 2.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.04%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 2.04%   |
| GN Netcom Jabra SPEAK 510                                                                         | 1         | 2.04%   |
| GN Netcom Jabra PRO 9470                                                                          | 1         | 2.04%   |
| GN Netcom Jabra Link 370                                                                          | 1         | 2.04%   |
| GN Netcom Jabra EVOLVE LINK                                                                       | 1         | 2.04%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 2.04%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 2.04%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 2.04%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 2.04%   |
| AMD High Definition Audio Controller                                                              | 1         | 2.04%   |
| AMD FCH Azalia Controller                                                                         | 1         | 2.04%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 2.04%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 2.04%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 4         | 28.57%  |
| SK Hynix            | 3         | 21.43%  |
| Micron Technology   | 2         | 14.29%  |
| Kingston            | 2         | 14.29%  |
| Unknown             | 1         | 7.14%   |
| Corsair             | 1         | 7.14%   |
| Avant               | 1         | 7.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 2         | 14.29%  |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                    | 1         | 7.14%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s      | 1         | 7.14%   |
| SK Hynix RAM HMAA1GS6CMR8N-VK 8GB Row Of Chips DDR4 2667MT/s   | 1         | 7.14%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s   | 1         | 7.14%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s       | 1         | 7.14%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s         | 1         | 7.14%   |
| Micron RAM 53E2G32D4NQ-046 4096MB Row Of Chips LPDDR4 4267MT/s | 1         | 7.14%   |
| Micron RAM 16JTF1G64HZ-1G4D1 8GB SODIMM DDR3 1333MT/s          | 1         | 7.14%   |
| Kingston RAM KX830D-ELC 4096MB SODIMM DDR3 1333MT/s            | 1         | 7.14%   |
| Kingston RAM KN2M64-ETB 8GB SODIMM DDR3 1600MT/s               | 1         | 7.14%   |
| Corsair RAM CMSX32GX4M2A2666C18 16GB SODIMM DDR4 2667MT/s      | 1         | 7.14%   |
| Avant RAM H6451U66G1600G 4096MB SODIMM DDR3 1600MT/s           | 1         | 7.14%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 8         | 57.14%  |
| DDR4   | 5         | 35.71%  |
| LPDDR4 | 1         | 7.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 11        | 78.57%  |
| Row Of Chips | 3         | 21.43%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 7         | 50%     |
| 4096  | 5         | 35.71%  |
| 32768 | 1         | 7.14%   |
| 16384 | 1         | 7.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 6         | 42.86%  |
| 2667  | 3         | 21.43%  |
| 1333  | 2         | 14.29%  |
| 4267  | 1         | 7.14%   |
| 2400  | 1         | 7.14%   |
| 1866  | 1         | 7.14%   |

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
| Chicony Electronics   | 7         | 31.82%  |
| Suyin                 | 3         | 13.64%  |
| Logitech              | 3         | 13.64%  |
| IMC Networks          | 3         | 13.64%  |
| Realtek Semiconductor | 2         | 9.09%   |
| Lite-On Technology    | 2         | 9.09%   |
| Microdia              | 1         | 4.55%   |
| Acer                  | 1         | 4.55%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Chicony Integrated Camera               | 4         | 17.39%  |
| IMC Networks VGA UVC WebCam             | 2         | 8.7%    |
| Chicony Integrated Camera (1280x720@30) | 2         | 8.7%    |
| Suyin Integrated_Webcam_HD              | 1         | 4.35%   |
| Suyin HP Truevision HD                  | 1         | 4.35%   |
| Suyin Asus Integrated Webcam            | 1         | 4.35%   |
| Realtek Integrated_Webcam_HD            | 1         | 4.35%   |
| Realtek EasyCamera                      | 1         | 4.35%   |
| Microdia Webcam Vitade AF               | 1         | 4.35%   |
| Logitech Webcam C920-C                  | 1         | 4.35%   |
| Logitech HD Webcam C615                 | 1         | 4.35%   |
| Logitech BRIO Ultra HD Webcam           | 1         | 4.35%   |
| Lite-On Integrated Camera               | 1         | 4.35%   |
| Lite-On HP HD Camera                    | 1         | 4.35%   |
| IMC Networks Integrated Camera          | 1         | 4.35%   |
| Chicony ThinkPad T490 Webcam            | 1         | 4.35%   |
| Chicony Integrated IR Camera            | 1         | 4.35%   |
| Acer SunplusIT Integrated Camera        | 1         | 4.35%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Synaptics        | 6         | 60%     |
| Validity Sensors | 4         | 40%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 30%     |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 30%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 20%     |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 10%     |
| Unknown                                                                    | 1         | 10%     |

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
| 1     | 13        | 48.15%  |
| 0     | 10        | 37.04%  |
| 2     | 3         | 11.11%  |
| 3     | 1         | 3.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 10        | 47.62%  |
| Chipcard           | 5         | 23.81%  |
| Storage            | 2         | 9.52%   |
| Graphics card      | 2         | 9.52%   |
| Net/wireless       | 1         | 4.76%   |
| Card reader        | 1         | 4.76%   |

