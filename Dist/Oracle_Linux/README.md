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

| Vendor   | Model                       | Form-Factor | Probe                                                      | Date         |
|----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                            | Computers | Percent |
|------------------------------------|-----------|---------|
| 5.4.17-2036.103.3.1.el8uek.x86_64  | 3         | 7.69%   |
| 5.4.17-2102.205.7.3.el8uek.x86_64  | 2         | 5.13%   |
| 5.4.17-2102.204.4.2.el8uek.x86_64  | 2         | 5.13%   |
| 5.4.17-2102.202.5.el8uek.x86_64    | 2         | 5.13%   |
| 5.4.17-2102.200.13.el8uek.x86_64   | 2         | 5.13%   |
| 5.4.17-2036.102.0.2.el8uek.x86_64  | 2         | 5.13%   |
| 5.4.17-2036.101.2.el8uek.x86_64    | 2         | 5.13%   |
| 4.18.0-193.1.2.el8_2.x86_64        | 2         | 5.13%   |
| 4.18.0-147.3.1.el8_1.x86_64        | 2         | 5.13%   |
| 5.4.17-2136.301.1.4.el8uek.x86_64  | 1         | 2.56%   |
| 5.4.17-2102.201.3.el8uek.x86_64    | 1         | 2.56%   |
| 5.4.17-2036.104.4.el8uek.x86_64    | 1         | 2.56%   |
| 5.4.17-2036.100.6.1.el8uek.x86_64  | 1         | 2.56%   |
| 5.4.17-2011.0.7.el8uek.x86_64      | 1         | 2.56%   |
| 5.4.11-1.el7.elrepo.x86_64         | 1         | 2.56%   |
| 5.15.2-1.el8.elrepo.x86_64         | 1         | 2.56%   |
| 5.14.1-1.el8.elrepo.x86_64         | 1         | 2.56%   |
| 5.11.1-1.el8.elrepo.x86_64         | 1         | 2.56%   |
| 4.18.0-348.2.1.el8_5.x86_64        | 1         | 2.56%   |
| 4.18.0-348.12.2.el8_5.x86_64       | 1         | 2.56%   |
| 4.18.0-240.15.1.el8_3.x86_64       | 1         | 2.56%   |
| 4.18.0-240.10.1.el8_3.x86_64       | 1         | 2.56%   |
| 4.14.35-2047.510.4.1.el7uek.x86_64 | 1         | 2.56%   |
| 4.14.35-1902.4.8.el7uek.x86_64     | 1         | 2.56%   |
| 4.14.35-1902.300.11.el7uek.x86_64  | 1         | 2.56%   |
| 4.14.35-1818.3.3.el7uek.x86_64     | 1         | 2.56%   |
| 3.10.0-957.21.2.el7.x86_64         | 1         | 2.56%   |
| 3.10.0-693.11.6.el7.x86_64         | 1         | 2.56%   |
| 3.10.0-1127.10.1.el7.x86_64        | 1         | 2.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.17  | 13        | 40.63%  |
| 4.18.0  | 8         | 25%     |
| 4.14.35 | 4         | 12.5%   |
| 3.10.0  | 3         | 9.38%   |
| 5.4.11  | 1         | 3.13%   |
| 5.15.2  | 1         | 3.13%   |
| 5.14.1  | 1         | 3.13%   |
| 5.11.1  | 1         | 3.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 14        | 43.75%  |
| 4.18    | 8         | 25%     |
| 4.14    | 4         | 12.5%   |
| 3.10    | 3         | 9.38%   |
| 5.15    | 1         | 3.13%   |
| 5.14    | 1         | 3.13%   |
| 5.11    | 1         | 3.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 30        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 21        | 65.63%  |
| Unknown       | 5         | 15.63%  |
| XFCE          | 2         | 6.25%   |
| MATE          | 2         | 6.25%   |
| KDE4          | 1         | 3.13%   |
| GNOME Classic | 1         | 3.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 15        | 46.88%  |
| Wayland | 14        | 43.75%  |
| Unknown | 3         | 9.38%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 22        | 70.97%  |
| GDM     | 9         | 29.03%  |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 16        | 51.61%  |
| de_DE   | 4         | 12.9%   |
| Unknown | 4         | 12.9%   |
| en_GB   | 3         | 9.68%   |
| pt_BR   | 1         | 3.23%   |
| pl_PL   | 1         | 3.23%   |
| it_IT   | 1         | 3.23%   |
| en_IN   | 1         | 3.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 16        | 51.61%  |
| EFI  | 15        | 48.39%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Xfs     | 23        | 74.19%  |
| Ext4    | 6         | 19.35%  |
| Unknown | 2         | 6.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 23        | 74.19%  |
| GPT     | 5         | 16.13%  |
| MBR     | 3         | 9.68%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 27        | 90%     |
| Yes       | 3         | 10%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 30        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 10        | 33.33%  |
| Dell                | 5         | 16.67%  |
| Hewlett-Packard     | 4         | 13.33%  |
| ASUSTek Computer    | 4         | 13.33%  |
| Gigabyte Technology | 3         | 10%     |
| Standard            | 1         | 3.33%   |
| HPE                 | 1         | 3.33%   |
| Foxconn             | 1         | 3.33%   |
| Apple               | 1         | 3.33%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUS X510UR                          | 2         | 6.67%   |
| Standard BW Series                   | 1         | 3.33%   |
| Lenovo ThinkPad X390 Yoga 20NQS2SF00 | 1         | 3.33%   |
| Lenovo ThinkPad T490 20N3S77600      | 1         | 3.33%   |
| Lenovo ThinkPad T480 20L6S56Y2X      | 1         | 3.33%   |
| Lenovo ThinkPad T450 20BUS14900      | 1         | 3.33%   |
| Lenovo ThinkPad L540 20AVCTO1WW      | 1         | 3.33%   |
| Lenovo ThinkPad L490 20Q5CTO1WW      | 1         | 3.33%   |
| Lenovo Legion 5 15IMH05 82AU         | 1         | 3.33%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS  | 1         | 3.33%   |
| Lenovo IdeaPad C340-14IWL 81RL       | 1         | 3.33%   |
| Lenovo IdeaPad 300-15ISK 80RS        | 1         | 3.33%   |
| HPE ProLiant BL460c Gen10            | 1         | 3.33%   |
| HP ZBook 15                          | 1         | 3.33%   |
| HP Z820 Workstation                  | 1         | 3.33%   |
| HP ProBook 445 G6                    | 1         | 3.33%   |
| HP Notebook                          | 1         | 3.33%   |
| Gigabyte Z490 AORUS ELITE AC         | 1         | 3.33%   |
| Gigabyte X99-Designare EX-CF         | 1         | 3.33%   |
| Gigabyte X470 AORUS ULTRA GAMING     | 1         | 3.33%   |
| Foxconn p6-2400el                    | 1         | 3.33%   |
| Dell PowerEdge FC630                 | 1         | 3.33%   |
| Dell OptiPlex 7060                   | 1         | 3.33%   |
| Dell Latitude E6420                  | 1         | 3.33%   |
| Dell Latitude 7410                   | 1         | 3.33%   |
| Dell Inspiron 3542                   | 1         | 3.33%   |
| ASUS UX305FA                         | 1         | 3.33%   |
| ASUS G11CD                           | 1         | 3.33%   |
| Apple Macmini7,1                     | 1         | 3.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 6         | 20%     |
| Lenovo IdeaPad         | 3         | 10%     |
| Dell Latitude          | 2         | 6.67%   |
| ASUS X510UR            | 2         | 6.67%   |
| Standard BW            | 1         | 3.33%   |
| Lenovo Legion          | 1         | 3.33%   |
| HPE ProLiant           | 1         | 3.33%   |
| HP ZBook               | 1         | 3.33%   |
| HP Z820                | 1         | 3.33%   |
| HP ProBook             | 1         | 3.33%   |
| HP Notebook            | 1         | 3.33%   |
| Gigabyte Z490          | 1         | 3.33%   |
| Gigabyte X99-Designare | 1         | 3.33%   |
| Gigabyte X470          | 1         | 3.33%   |
| Foxconn p6-2400el      | 1         | 3.33%   |
| Dell PowerEdge         | 1         | 3.33%   |
| Dell OptiPlex          | 1         | 3.33%   |
| Dell Inspiron          | 1         | 3.33%   |
| ASUS UX305FA           | 1         | 3.33%   |
| ASUS G11CD             | 1         | 3.33%   |
| Apple Macmini7         | 1         | 3.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 8         | 26.67%  |
| 2018 | 4         | 13.33%  |
| 2016 | 4         | 13.33%  |
| 2020 | 3         | 10%     |
| 2014 | 3         | 10%     |
| 2017 | 2         | 6.67%   |
| 2015 | 2         | 6.67%   |
| 2012 | 2         | 6.67%   |
| 2013 | 1         | 3.33%   |
| 2011 | 1         | 3.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 18        | 60%     |
| Desktop     | 8         | 26.67%  |
| Convertible | 2         | 6.67%   |
| Mini pc     | 1         | 3.33%   |
| Server      | 1         | 3.33%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 28        | 93.33%  |
| Enabled  | 2         | 6.67%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 30        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 8         | 25.81%  |
| 8.01-16.0       | 8         | 25.81%  |
| 32.01-64.0      | 5         | 16.13%  |
| 16.01-24.0      | 4         | 12.9%   |
| 3.01-4.0        | 3         | 9.68%   |
| 64.01-256.0     | 2         | 6.45%   |
| More than 256.0 | 1         | 3.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 11        | 29.73%  |
| 4.01-8.0   | 10        | 27.03%  |
| 3.01-4.0   | 5         | 13.51%  |
| 1.01-2.0   | 5         | 13.51%  |
| 8.01-16.0  | 4         | 10.81%  |
| 16.01-24.0 | 1         | 2.7%    |
| 0.51-1.0   | 1         | 2.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 24        | 80%     |
| 2      | 3         | 10%     |
| 3      | 2         | 6.67%   |
| 5      | 1         | 3.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 21        | 70%     |
| Yes       | 9         | 30%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 23        | 76.67%  |
| No        | 7         | 23.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 80%     |
| No        | 6         | 20%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 64.52%  |
| No        | 11        | 35.48%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 8         | 25.81%  |
| Germany     | 7         | 22.58%  |
| Brazil      | 3         | 9.68%   |
| UK          | 2         | 6.45%   |
| Netherlands | 2         | 6.45%   |
| Russia      | 1         | 3.23%   |
| Romania     | 1         | 3.23%   |
| Poland      | 1         | 3.23%   |
| Pakistan    | 1         | 3.23%   |
| Kazakhstan  | 1         | 3.23%   |
| Italy       | 1         | 3.23%   |
| India       | 1         | 3.23%   |
| Bulgaria    | 1         | 3.23%   |
| Argentina   | 1         | 3.23%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Colorado Springs | 2         | 6.06%   |
| Berlin           | 2         | 6.06%   |
| Utrecht          | 1         | 3.03%   |
| SГЈo Paulo     | 1         | 3.03%   |
| Sofia            | 1         | 3.03%   |
| Siegen           | 1         | 3.03%   |
| SÃ£o Paulo     | 1         | 3.03%   |
| Santo AndrÃ©   | 1         | 3.03%   |
| San Francisco    | 1         | 3.03%   |
| Rheinstetten     | 1         | 3.03%   |
| Reading          | 1         | 3.03%   |
| Port Saint Lucie | 1         | 3.03%   |
| Polch            | 1         | 3.03%   |
| Moscow           | 1         | 3.03%   |
| Milan            | 1         | 3.03%   |
| Maple Valley     | 1         | 3.03%   |
| Kreuztal         | 1         | 3.03%   |
| Karaganda        | 1         | 3.03%   |
| Karachi          | 1         | 3.03%   |
| Ituzaingo        | 1         | 3.03%   |
| Freudenberg      | 1         | 3.03%   |
| Eppelheim        | 1         | 3.03%   |
| Dietmannsried    | 1         | 3.03%   |
| Dallas           | 1         | 3.03%   |
| ChorzÃ³w       | 1         | 3.03%   |
| Chicago          | 1         | 3.03%   |
| Bucharest        | 1         | 3.03%   |
| Bracknell        | 1         | 3.03%   |
| Bengaluru        | 1         | 3.03%   |
| Asheville        | 1         | 3.03%   |
| Amsterdam        | 1         | 3.03%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 7         | 10     | 20%     |
| Seagate                 | 6         | 43     | 17.14%  |
| SanDisk                 | 6         | 7      | 17.14%  |
| WDC                     | 3         | 3      | 8.57%   |
| Unknown                 | 1         | 1      | 2.86%   |
| Union Memory (Shenzhen) | 1         | 2      | 2.86%   |
| Toshiba                 | 1         | 1      | 2.86%   |
| SK Hynix                | 1         | 1      | 2.86%   |
| Phison                  | 1         | 1      | 2.86%   |
| Micron Technology       | 1         | 4      | 2.86%   |
| Lite-On                 | 1         | 1      | 2.86%   |
| Kingston                | 1         | 5      | 2.86%   |
| Intel                   | 1         | 1      | 2.86%   |
| HPE                     | 1         | 1      | 2.86%   |
| HGST                    | 1         | 1      | 2.86%   |
| Crucial                 | 1         | 1      | 2.86%   |
| Apple                   | 1         | 1      | 2.86%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seagate ST2000DM008-2FR102 2TB               | 2         | 5.26%   |
| SanDisk SSD PLUS 1000GB                      | 2         | 5.26%   |
| Samsung SSD PM830 2.5 7mm 256GB              | 2         | 5.26%   |
| WDC WDS500G2B0A-00SM50 500GB SSD             | 1         | 2.63%   |
| WDC WD10JPCX-24UE4T0 1TB                     | 1         | 2.63%   |
| WDC WD10EZEX-60M2NA0 1TB                     | 1         | 2.63%   |
| Unknown SD/MMC/MS PRO 64GB                   | 1         | 2.63%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 2.63%   |
| Toshiba NVMe SSD Drive 512GB                 | 1         | 2.63%   |
| SK Hynix SKHynix_HFS256GD9TNG-L3A0B 256GB    | 1         | 2.63%   |
| Seagate ST8000VN004-2M2101 8TB               | 1         | 2.63%   |
| Seagate ST3500414CS 500GB                    | 1         | 2.63%   |
| Seagate ST2000NX0253 2TB                     | 1         | 2.63%   |
| Seagate ST1000NX0423 1TB                     | 1         | 2.63%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 2.63%   |
| SanDisk SDSSDH3512G 512GB                    | 1         | 2.63%   |
| SanDisk SD7SN3Q256G1002 256GB SSD            | 1         | 2.63%   |
| SanDisk SD6SB1M-256G-1006 256GB SSD          | 1         | 2.63%   |
| Sandisk NVMe SSD Drive 512GB                 | 1         | 2.63%   |
| Samsung SSD 960 EVO 250GB                    | 1         | 2.63%   |
| Samsung SSD 850 PRO 256GB                    | 1         | 2.63%   |
| Samsung NVMe SSD Drive 512GB                 | 1         | 2.63%   |
| Samsung MZ7LN512HMJP-000L7 512GB SSD         | 1         | 2.63%   |
| Samsung MZ7LN256HCHP-000L7 256GB SSD         | 1         | 2.63%   |
| Samsung HD502IJ 500GB                        | 1         | 2.63%   |
| Phison NVMe SSD Drive 1TB                    | 1         | 2.63%   |
| Micron NVMe SSD Drive 256GB                  | 1         | 2.63%   |
| Micron 2200S NVMe 256GB                      | 1         | 2.63%   |
| Lite-On NVMe SSD Drive 512GB                 | 1         | 2.63%   |
| Kingston NVMe SSD Drive 1TB                  | 1         | 2.63%   |
| Intel SSDPEKKF256G8L 256GB                   | 1         | 2.63%   |
| HPE LOGICAL VOLUME 91TB                      | 1         | 2.63%   |
| HGST HTS545050A7E380 500GB                   | 1         | 2.63%   |
| Crucial CT500MX500SSD1 500GB                 | 1         | 2.63%   |
| Apple HDD HTS541010A9E662 1TB                | 1         | 2.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


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

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 5         | 5      | 38.46%  |
| Samsung Electronics | 5         | 5      | 38.46%  |
| WDC                 | 1         | 1      | 7.69%   |
| HPE                 | 1         | 1      | 7.69%   |
| Crucial             | 1         | 1      | 7.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 13        | 13     | 37.14%  |
| NVMe | 11        | 22     | 31.43%  |
| HDD  | 11        | 49     | 31.43%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 21        | 60     | 61.76%  |
| NVMe | 11        | 22     | 32.35%  |
| SAS  | 2         | 2      | 5.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB  | Computers | Drives | Percent |
|-------------|-----------|--------|---------|
| 0.01-0.5    | 11        | 12     | 44%     |
| 0.51-1.0    | 9         | 10     | 36%     |
| 1.01-2.0    | 3         | 37     | 12%     |
| 50.01-100.0 | 1         | 1      | 4%      |
| 4.01-10.0   | 1         | 2      | 4%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 8         | 25.81%  |
| 101-250        | 7         | 22.58%  |
| Unknown        | 7         | 22.58%  |
| 501-1000       | 4         | 12.9%   |
| More than 3000 | 1         | 3.23%   |
| 2001-3000      | 1         | 3.23%   |
| 1001-2000      | 1         | 3.23%   |
| 1-20           | 1         | 3.23%   |
| 51-100         | 1         | 3.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 10        | 31.25%  |
| Unknown        | 7         | 21.88%  |
| 21-50          | 6         | 18.75%  |
| 101-250        | 4         | 12.5%   |
| 51-100         | 3         | 9.38%   |
| More than 3000 | 1         | 3.13%   |
| 251-500        | 1         | 3.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1         | 1      | 100%    |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 21        | 37     | 67.74%  |
| Works    | 9         | 46     | 29.03%  |
| Malfunc  | 1         | 1      | 3.23%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 21        | 55.26%  |
| AMD                          | 4         | 10.53%  |
| Samsung Electronics          | 2         | 5.26%   |
| Broadcom / LSI               | 2         | 5.26%   |
| Union Memory (Shenzhen)      | 1         | 2.63%   |
| Toshiba America Info Systems | 1         | 2.63%   |
| SK Hynix                     | 1         | 2.63%   |
| Sandisk                      | 1         | 2.63%   |
| Phison Electronics           | 1         | 2.63%   |
| Micron Technology            | 1         | 2.63%   |
| Lite-On Technology           | 1         | 2.63%   |
| Kingston Technology Company  | 1         | 2.63%   |
| Adaptec                      | 1         | 2.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 4         | 9.3%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 3         | 6.98%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 4.65%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 2         | 4.65%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 2         | 4.65%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 4.65%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 4.65%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 2.33%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 2.33%   |
| SK Hynix Non-Volatile memory controller                                          | 1         | 2.33%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 2.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 2.33%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 2.33%   |
| Phison E12 NVMe Controller                                                       | 1         | 2.33%   |
| Micron Non-Volatile memory controller                                            | 1         | 2.33%   |
| Lite-On Non-Volatile memory controller                                           | 1         | 2.33%   |
| Kingston Company A2000 NVMe SSD                                                  | 1         | 2.33%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1         | 2.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 2.33%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 2.33%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 2.33%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1         | 2.33%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                              | 1         | 2.33%   |
| Intel C600/X79 series chipset SATA RAID Controller                               | 1         | 2.33%   |
| Intel C600/X79 series chipset IDE-r Controller                                   | 1         | 2.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 2.33%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 1         | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 1         | 2.33%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 1         | 2.33%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                              | 1         | 2.33%   |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                     | 1         | 2.33%   |
| AMD 400 Series Chipset SATA Controller                                           | 1         | 2.33%   |
| Adaptec Smart Storage PQI SAS                                                    | 1         | 2.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 22        | 56.41%  |
| NVMe | 11        | 28.21%  |
| RAID | 3         | 7.69%   |
| SAS  | 2         | 5.13%   |
| IDE  | 1         | 2.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 26        | 86.67%  |
| AMD    | 4         | 13.33%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-8665U CPU @ 1.90GHz               | 2         | 6.67%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 2         | 6.67%   |
| Intel Xeon Silver 4114 CPU @ 2.20GHz            | 1         | 3.33%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz             | 1         | 3.33%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz             | 1         | 3.33%   |
| Intel Processor 5Y10 CPU @ 0.80GHz              | 1         | 3.33%   |
| Intel Pentium CPU G2020 @ 2.90GHz               | 1         | 3.33%   |
| Intel Core i9-10900K CPU @ 3.70GHz              | 1         | 3.33%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 1         | 3.33%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 3.33%   |
| Intel Core i7-6800K CPU @ 3.40GHz               | 1         | 3.33%   |
| Intel Core i7-6700 CPU @ 3.40GHz                | 1         | 3.33%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 1         | 3.33%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz              | 1         | 3.33%   |
| Intel Core i7-2760QM CPU @ 2.40GHz              | 1         | 3.33%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 1         | 3.33%   |
| Intel Core i7-10610U CPU @ 1.80GHz              | 1         | 3.33%   |
| Intel Core i5-8365U CPU @ 1.60GHz               | 1         | 3.33%   |
| Intel Core i5-8350U CPU @ 1.70GHz               | 1         | 3.33%   |
| Intel Core i5-5300U CPU @ 2.30GHz               | 1         | 3.33%   |
| Intel Core i5-4278U CPU @ 2.60GHz               | 1         | 3.33%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 1         | 3.33%   |
| Intel Core i5-4210M CPU @ 2.60GHz               | 1         | 3.33%   |
| Intel Celeron CPU N3010 @ 1.04GHz               | 1         | 3.33%   |
| AMD Ryzen 7 PRO 2700U w/ Radeon Vega Mobile Gfx | 1         | 3.33%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 1         | 3.33%   |
| AMD A9-9420e RADEON R5, 5 COMPUTE CORES 2C+3G   | 1         | 3.33%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics     | 1         | 3.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i7     | 13        | 43.33%  |
| Intel Core i5     | 6         | 20%     |
| Other             | 2         | 6.67%   |
| Intel Xeon        | 2         | 6.67%   |
| Intel Xeon Silver | 1         | 3.33%   |
| Intel Pentium     | 1         | 3.33%   |
| Intel Core i9     | 1         | 3.33%   |
| Intel Celeron     | 1         | 3.33%   |
| AMD Ryzen 7 PRO   | 1         | 3.33%   |
| AMD Ryzen 7       | 1         | 3.33%   |
| AMD A8            | 1         | 3.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 11        | 36.67%  |
| 4      | 10        | 33.33%  |
| 6      | 3         | 10%     |
| 16     | 2         | 6.67%   |
| 20     | 1         | 3.33%   |
| 10     | 1         | 3.33%   |
| 8      | 1         | 3.33%   |
| 1      | 1         | 3.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 27        | 90%     |
| 2      | 3         | 10%     |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 25        | 83.33%  |
| 1      | 5         | 16.67%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 29        | 93.55%  |
| Unknown        | 2         | 6.45%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806ec    | 5         | 16.67%  |
| Unknown    | 3         | 10%     |
| 0x40651    | 2         | 6.67%   |
| 0x306d4    | 2         | 6.67%   |
| 0x306c3    | 2         | 6.67%   |
| 0xa0655    | 1         | 3.33%   |
| 0xa0652    | 1         | 3.33%   |
| 0x906ea    | 1         | 3.33%   |
| 0x806ea    | 1         | 3.33%   |
| 0x506e3    | 1         | 3.33%   |
| 0x50654    | 1         | 3.33%   |
| 0x406f1    | 1         | 3.33%   |
| 0x406e3    | 1         | 3.33%   |
| 0x406c4    | 1         | 3.33%   |
| 0x306e4    | 1         | 3.33%   |
| 0x306a9    | 1         | 3.33%   |
| 0x206a7    | 1         | 3.33%   |
| 0x0810100b | 1         | 3.33%   |
| 0x0800820d | 1         | 3.33%   |
| 0x07030105 | 1         | 3.33%   |
| 0x06006705 | 1         | 3.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 9         | 30%     |
| Haswell     | 4         | 13.33%  |
| Broadwell   | 4         | 13.33%  |
| Skylake     | 3         | 10%     |
| IvyBridge   | 2         | 6.67%   |
| CometLake   | 2         | 6.67%   |
| Zen+        | 1         | 3.33%   |
| Zen         | 1         | 3.33%   |
| Silvermont  | 1         | 3.33%   |
| SandyBridge | 1         | 3.33%   |
| Puma        | 1         | 3.33%   |
| Excavator   | 1         | 3.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 20        | 54.05%  |
| Nvidia                     | 11        | 29.73%  |
| AMD                        | 4         | 10.81%  |
| Matrox Electronics Systems | 2         | 5.41%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 10.81%  |
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 5.41%   |
| Intel HD Graphics 620                                                                    | 2         | 5.41%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 5.41%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 5.41%   |
| Nvidia TU117M                                                                            | 1         | 2.7%    |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1         | 2.7%    |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1         | 2.7%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 2.7%    |
| Nvidia GM204 [GeForce GTX 980]                                                           | 1         | 2.7%    |
| Nvidia GK208GLM [Quadro K610M]                                                           | 1         | 2.7%    |
| Nvidia GK110GL [Quadro K6000]                                                            | 1         | 2.7%    |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 2.7%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 2.7%    |
| Matrox Electronics Systems MGA G200eH3                                                   | 1         | 2.7%    |
| Matrox Electronics Systems G200eR2                                                       | 1         | 2.7%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 2.7%    |
| Intel UHD Graphics 620                                                                   | 1         | 2.7%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 2.7%    |
| Intel HD Graphics 5500                                                                   | 1         | 2.7%    |
| Intel HD Graphics 5300                                                                   | 1         | 2.7%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 2.7%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 2.7%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 2.7%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 2.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.7%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 2.7%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 2.7%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 2.7%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 2.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 13        | 43.33%  |
| 1 x Nvidia     | 6         | 20%     |
| Intel + Nvidia | 5         | 16.67%  |
| 1 x AMD        | 3         | 10%     |
| 1 x Matrox     | 2         | 6.67%   |
| Intel + AMD    | 1         | 3.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 27        | 90%     |
| Proprietary | 2         | 6.67%   |
| Unknown     | 1         | 3.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 15        | 48.39%  |
| 1.01-2.0   | 6         | 19.35%  |
| 3.01-4.0   | 5         | 16.13%  |
| 0.01-0.5   | 2         | 6.45%   |
| 5.01-6.0   | 1         | 3.23%   |
| 8.01-16.0  | 1         | 3.23%   |
| 0.51-1.0   | 1         | 3.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| LG Display          | 7         | 20.59%  |
| AU Optronics        | 5         | 14.71%  |
| Chimei Innolux      | 4         | 11.76%  |
| BenQ                | 3         | 8.82%   |
| Samsung Electronics | 2         | 5.88%   |
| Hewlett-Packard     | 2         | 5.88%   |
| Dell                | 2         | 5.88%   |
| ViewSonic           | 1         | 2.94%   |
| Sony                | 1         | 2.94%   |
| Lenovo              | 1         | 2.94%   |
| InfoVision          | 1         | 2.94%   |
| Goldstar            | 1         | 2.94%   |
| Element             | 1         | 2.94%   |
| Eizo                | 1         | 2.94%   |
| BOE                 | 1         | 2.94%   |
| ASUSTek Computer    | 1         | 2.94%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 2         | 5.88%   |
| BenQ GL2760 BNQ78D5 1920x1080 598x336mm 27.0-inch                     | 2         | 5.88%   |
| ViewSonic VX2433wm VSC3822 1920x1080 520x290mm 23.4-inch              | 1         | 2.94%   |
| Sony TV SNY4502 1920x1080 1600x900mm 72.3-inch                        | 1         | 2.94%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 1         | 2.94%   |
| Samsung Electronics LCD Monitor S24C650                               | 1         | 2.94%   |
| LG Display LCD Monitor LGD0609 1920x1080 309x174mm 14.0-inch          | 1         | 2.94%   |
| LG Display LCD Monitor LGD04BD 1366x768 344x194mm 15.5-inch           | 1         | 2.94%   |
| LG Display LCD Monitor LGD047C 1366x768 310x174mm 14.0-inch           | 1         | 2.94%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 1         | 2.94%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch           | 1         | 2.94%   |
| Lenovo T24i-10 LEN61A6 1920x1080 530x300mm 24.0-inch                  | 1         | 2.94%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 1         | 2.94%   |
| Hewlett-Packard Z24i HWP309E 1920x1200 518x324mm 24.1-inch            | 1         | 2.94%   |
| Hewlett-Packard E273q HPN3474 2560x1440 597x336mm 27.0-inch           | 1         | 2.94%   |
| Goldstar E2240 GSM57A3 1920x1080 477x268mm 21.5-inch                  | 1         | 2.94%   |
| Element T430QVN02.1 ELE6586 3840x2160 708x398mm 32.0-inch             | 1         | 2.94%   |
| Eizo EV2460 ENC3129 1920x1080 528x297mm 23.9-inch                     | 1         | 2.94%   |
| Dell LCD Monitor U2415 3840x1200                                      | 1         | 2.94%   |
| Dell IDRAC DEL0001 1280x1024                                          | 1         | 2.94%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 1         | 2.94%   |
| Chimei Innolux LCD Monitor CMN14E8 1920x1080 309x173mm 13.9-inch      | 1         | 2.94%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 1         | 2.94%   |
| Chimei Innolux LCD Monitor CMN1387 1920x1080 293x165mm 13.2-inch      | 1         | 2.94%   |
| BOE LCD Monitor BOE08E8 1920x1080 344x194mm 15.5-inch                 | 1         | 2.94%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch         | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO212D 1920x1080 293x165mm 13.2-inch        | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 1         | 2.94%   |
| ASUSTek Computer VP249 AUS24AF 1920x1080 527x296mm 23.8-inch          | 1         | 2.94%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 16        | 57.14%  |
| 1366x768 (WXGA)   | 4         | 14.29%  |
| 1600x900 (HD+)    | 2         | 7.14%   |
| 3840x2160 (4K)    | 1         | 3.57%   |
| 3840x1200         | 1         | 3.57%   |
| 2560x1440 (QHD)   | 1         | 3.57%   |
| 1920x1200 (WUXGA) | 1         | 3.57%   |
| 1280x1024 (SXGA)  | 1         | 3.57%   |
| Unknown           | 1         | 3.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 8         | 24.24%  |
| 14      | 7         | 21.21%  |
| 24      | 4         | 12.12%  |
| 13      | 4         | 12.12%  |
| 27      | 3         | 9.09%   |
| 23      | 2         | 6.06%   |
| Unknown | 2         | 6.06%   |
| 72      | 1         | 3.03%   |
| 32      | 1         | 3.03%   |
| 21      | 1         | 3.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 17        | 53.13%  |
| 501-600     | 8         | 25%     |
| 201-300     | 2         | 6.25%   |
| Unknown     | 2         | 6.25%   |
| 701-800     | 1         | 3.13%   |
| 401-500     | 1         | 3.13%   |
| 1501-2000   | 1         | 3.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 24        | 88.89%  |
| 5/4     | 1         | 3.7%    |
| 16/10   | 1         | 3.7%    |
| Unknown | 1         | 3.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 9         | 28.13%  |
| 101-110        | 8         | 25%     |
| 201-250        | 5         | 15.63%  |
| 301-350        | 3         | 9.38%   |
| 71-80          | 2         | 6.25%   |
| Unknown        | 2         | 6.25%   |
| More than 1000 | 1         | 3.13%   |
| 351-500        | 1         | 3.13%   |
| 251-300        | 1         | 3.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 14        | 43.75%  |
| 51-100  | 7         | 21.88%  |
| 101-120 | 6         | 18.75%  |
| 161-240 | 2         | 6.25%   |
| Unknown | 2         | 6.25%   |
| 1-50    | 1         | 3.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 22        | 73.33%  |
| 2     | 5         | 16.67%  |
| 0     | 2         | 6.67%   |
| 3     | 1         | 3.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 20        | 47.62%  |
| Realtek Semiconductor | 9         | 21.43%  |
| Broadcom              | 4         | 9.52%   |
| Qualcomm Atheros      | 3         | 7.14%   |
| Lenovo                | 2         | 4.76%   |
| Ralink Technology     | 1         | 2.38%   |
| NetGear               | 1         | 2.38%   |
| Fibocom               | 1         | 2.38%   |
| Broadcom Limited      | 1         | 2.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5         | 9.09%   |
| Intel Wireless 8265 / 8275                                        | 3         | 5.45%   |
| Intel Ethernet Connection (6) I219-LM                             | 3         | 5.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 3.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 3.64%   |
| Intel Wireless 7265                                               | 2         | 3.64%   |
| Intel Wireless 7260                                               | 2         | 3.64%   |
| Intel I211 Gigabit Network Connection                             | 2         | 3.64%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 3.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 3.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.64%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 1.82%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.82%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 1.82%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.82%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 1.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.82%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                   | 1         | 1.82%   |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 1.82%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 1.82%   |
| Intel Wireless-AC 9260                                            | 1         | 1.82%   |
| Intel Wireless 8260                                               | 1         | 1.82%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.82%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.82%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.82%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.82%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.82%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.82%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 1.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1         | 1.82%   |
| Intel 82599 10 Gigabit Dual Port Backplane Connection             | 1         | 1.82%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.82%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                 | 1         | 1.82%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 1         | 1.82%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.82%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 1         | 1.82%   |
| Broadcom BCM57840 NetXtreme II 10/20-Gigabit Ethernet             | 1         | 1.82%   |
| Broadcom BCM43142 802.11b/g/n                                     | 1         | 1.82%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 16        | 59.26%  |
| Realtek Semiconductor | 3         | 11.11%  |
| Qualcomm Atheros      | 3         | 11.11%  |
| Ralink Technology     | 1         | 3.7%    |
| NetGear               | 1         | 3.7%    |
| Fibocom               | 1         | 3.7%    |
| Broadcom Limited      | 1         | 3.7%    |
| Broadcom              | 1         | 3.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                 | 3         | 11.11%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 2         | 7.41%   |
| Intel Wireless 7265                                        | 2         | 7.41%   |
| Intel Wireless 7260                                        | 2         | 7.41%   |
| Intel Comet Lake PCH CNVi WiFi                             | 2         | 7.41%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                   | 2         | 7.41%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1         | 3.7%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter   | 1         | 3.7%    |
| Realtek RTL8188EE Wireless Network Adapter                 | 1         | 3.7%    |
| Ralink MT7601U Wireless Adapter                            | 1         | 3.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1         | 3.7%    |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]            | 1         | 3.7%    |
| Intel Wireless-AC 9260                                     | 1         | 3.7%    |
| Intel Wireless 8260                                        | 1         | 3.7%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth            | 1         | 3.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 1         | 3.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]               | 1         | 3.7%    |
| Fibocom L830-EB-00 LTE WWAN Modem                          | 1         | 3.7%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter | 1         | 3.7%    |
| Broadcom BCM43142 802.11b/g/n                              | 1         | 3.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 13        | 50%     |
| Realtek Semiconductor | 8         | 30.77%  |
| Broadcom              | 3         | 11.54%  |
| Lenovo                | 2         | 7.69%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5         | 17.86%  |
| Intel Ethernet Connection (6) I219-LM                             | 3         | 10.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 7.14%   |
| Intel I211 Gigabit Network Connection                             | 2         | 7.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 7.14%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 3.57%   |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 3.57%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 3.57%   |
| Intel Ethernet Connection I217-V                                  | 1         | 3.57%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 3.57%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 3.57%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 3.57%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 3.57%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 3.57%   |
| Intel 82599 10 Gigabit Dual Port Backplane Connection             | 1         | 3.57%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 3.57%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 1         | 3.57%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 3.57%   |
| Broadcom BCM57840 NetXtreme II 10/20-Gigabit Ethernet             | 1         | 3.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 24        | 51.06%  |
| Ethernet | 23        | 48.94%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 20        | 50%     |
| Ethernet | 20        | 50%     |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 18        | 60%     |
| 1     | 10        | 33.33%  |
| 4     | 1         | 3.33%   |
| 3     | 1         | 3.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 27        | 84.38%  |
| Yes  | 5         | 15.63%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 12        | 57.14%  |
| Qualcomm Atheros Communications | 3         | 14.29%  |
| Broadcom                        | 2         | 9.52%   |
| Realtek Semiconductor           | 1         | 4.76%   |
| IMC Networks                    | 1         | 4.76%   |
| ASUSTek Computer                | 1         | 4.76%   |
| Apple                           | 1         | 4.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Bluetooth Device                   | 5         | 23.81%  |
| Intel Bluetooth wireless interface       | 4         | 19.05%  |
| Qualcomm Atheros  Bluetooth Device       | 2         | 9.52%   |
| Intel AX201 Bluetooth                    | 2         | 9.52%   |
| Realtek  Bluetooth 4.2 Adapter           | 1         | 4.76%   |
| Qualcomm Atheros AR9462 Bluetooth        | 1         | 4.76%   |
| Intel Wireless-AC 9260 Bluetooth Adapter | 1         | 4.76%   |
| IMC Networks Bluetooth Radio             | 1         | 4.76%   |
| Broadcom BCM43142A0 Bluetooth 4.0        | 1         | 4.76%   |
| Broadcom BCM20702A0 Bluetooth 4.0        | 1         | 4.76%   |
| ASUS Broadcom BCM20702A0 Bluetooth       | 1         | 4.76%   |
| Apple Bluetooth Host Controller          | 1         | 4.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor    | Computers | Percent |
|-----------|-----------|---------|
| Intel     | 23        | 56.1%   |
| Nvidia    | 8         | 19.51%  |
| Lenovo    | 4         | 9.76%   |
| AMD       | 4         | 9.76%   |
| Unknown   | 1         | 2.44%   |
| GN Netcom | 1         | 2.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 4         | 8.16%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 8.16%   |
| Lenovo ThinkPad Dock USB Audio                                                                    | 2         | 4.08%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 4.08%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 4.08%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 4.08%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 4.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 4.08%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 4.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 4.08%   |
| Unknown Definitive Sym1                                                                           | 1         | 2.04%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 2.04%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 2.04%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 2.04%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 2.04%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 2.04%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 2.04%   |
| Nvidia GK110 High Definition Audio Controller                                                     | 1         | 2.04%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 2.04%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 1         | 2.04%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                                          | 1         | 2.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 2.04%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 2.04%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 2.04%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1         | 2.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.04%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 2.04%   |
| GN Netcom Jabra Link 370                                                                          | 1         | 2.04%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 2.04%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 2.04%   |
| AMD High Definition Audio Controller                                                              | 1         | 2.04%   |
| AMD FCH Azalia Controller                                                                         | 1         | 2.04%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 2.04%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1         | 2.04%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 2.04%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 3         | 23.08%  |
| Micron Technology   | 3         | 23.08%  |
| SK Hynix            | 2         | 15.38%  |
| Smart               | 1         | 7.69%   |
| Kingston            | 1         | 7.69%   |
| HPE                 | 1         | 7.69%   |
| Crucial             | 1         | 7.69%   |
| Avant               | 1         | 7.69%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 2         | 15.38%  |
| Smart RAM SMS4TDC3C0K0446SCG 4096MB SODIMM DDR4 2667MT/s     | 1         | 7.69%   |
| SK Hynix RAM HMAA1GS6CMR8N-VK 8GB Row Of Chips DDR4 2667MT/s | 1         | 7.69%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s | 1         | 7.69%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 7.69%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s         | 1         | 7.69%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s        | 1         | 7.69%   |
| Micron RAM 18ASF2G72PDZ-2G3B1 16GB DIMM DDR4 2400MT/s        | 1         | 7.69%   |
| Kingston RAM KX830D-ELC 4096MB SODIMM DDR3 1333MT/s          | 1         | 7.69%   |
| HPE RAM 840756-091 16GB DIMM DDR4 2666MT/s                   | 1         | 7.69%   |
| Crucial RAM BLE8G4D34AEEAK.K8FB 8192MB DIMM DDR4 3466MT/s    | 1         | 7.69%   |
| Avant RAM H6451U66G1600G 4096MB SODIMM DDR3 1600MT/s         | 1         | 7.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| DDR4 | 7         | 58.33%  |
| DDR3 | 5         | 41.67%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 7         | 58.33%  |
| DIMM         | 3         | 25%     |
| Row Of Chips | 2         | 16.67%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 5         | 41.67%  |
| 4096  | 5         | 41.67%  |
| 16384 | 2         | 16.67%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 4         | 33.33%  |
| 2667  | 3         | 25%     |
| 3466  | 1         | 8.33%   |
| 2666  | 1         | 8.33%   |
| 2400  | 1         | 8.33%   |
| 1866  | 1         | 8.33%   |
| 1333  | 1         | 8.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Samsung ML-1660 Series | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 120 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Chicony Electronics   | 6         | 33.33%  |
| Suyin                 | 3         | 16.67%  |
| IMC Networks          | 3         | 16.67%  |
| Realtek Semiconductor | 2         | 11.11%  |
| Microdia              | 2         | 11.11%  |
| Logitech              | 1         | 5.56%   |
| Lite-On Technology    | 1         | 5.56%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Chicony Integrated Camera               | 5         | 27.78%  |
| Microdia Webcam Vitade AF               | 2         | 11.11%  |
| IMC Networks USB2.0 VGA UVC WebCam      | 2         | 11.11%  |
| Suyin Integrated_Webcam_HD              | 1         | 5.56%   |
| Suyin HP Truevision HD                  | 1         | 5.56%   |
| Suyin Asus Integrated Webcam            | 1         | 5.56%   |
| Realtek Integrated_Webcam_HD            | 1         | 5.56%   |
| Realtek EasyCamera                      | 1         | 5.56%   |
| Logitech Webcam C920-C                  | 1         | 5.56%   |
| Lite-On HP HD Camera                    | 1         | 5.56%   |
| IMC Networks Integrated Camera          | 1         | 5.56%   |
| Chicony Integrated Camera (1280x720@30) | 1         | 5.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 3         | 50%     |
| Validity Sensors           | 2         | 33.33%  |
| Shenzhen Goodix Technology | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 16.67%  |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 16.67%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 16.67%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 16.67%  |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 16.67%  |
| Unknown                                                                    | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 66.67%  |
| Alcor Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 33.33%  |
| Broadcom 58200                                 | 1         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 15        | 48.39%  |
| 1     | 9         | 29.03%  |
| 2     | 5         | 16.13%  |
| 3     | 2         | 6.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 6         | 27.27%  |
| Unassigned class         | 3         | 13.64%  |
| Net/wireless             | 2         | 9.09%   |
| Graphics card            | 2         | 9.09%   |
| Communication controller | 2         | 9.09%   |
| Chipcard                 | 2         | 9.09%   |
| Card reader              | 2         | 9.09%   |
| Bluetooth                | 2         | 9.09%   |
| Storage                  | 1         | 4.55%   |

