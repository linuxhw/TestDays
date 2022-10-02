AlmaLinux - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for AlmaLinux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/AlmaLinux/Desktop/README.md) and [notebooks](/Dist/AlmaLinux/Notebook/README.md).

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

Total: 39

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | TMP453-MG                   | Notebook    | [4d36d13ea9](https://linux-hardware.org/?probe=4d36d13ea9) | Oct 01, 2022 |
| Lenovo        | 1052 NOK                    | Desktop     | [28cd1416fe](https://linux-hardware.org/?probe=28cd1416fe) | Sep 22, 2022 |
| Acer          | TravelMate 5735Z            | Notebook    | [b920fce554](https://linux-hardware.org/?probe=b920fce554) | Sep 17, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [7e56cce9c8](https://linux-hardware.org/?probe=7e56cce9c8) | Sep 17, 2022 |
| HP            | Falco                       | Notebook    | [5fa86b77d6](https://linux-hardware.org/?probe=5fa86b77d6) | Sep 17, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [c01403937e](https://linux-hardware.org/?probe=c01403937e) | Sep 08, 2022 |
| HP            | ENVY dv6                    | Notebook    | [e7bc07047b](https://linux-hardware.org/?probe=e7bc07047b) | Aug 24, 2022 |
| Gigabyte      | MP32-AR1-00 01010101        | Server      | [e93d3eae0d](https://linux-hardware.org/?probe=e93d3eae0d) | Jul 20, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [82b34535ae](https://linux-hardware.org/?probe=82b34535ae) | Jul 06, 2022 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [0dc125da55](https://linux-hardware.org/?probe=0dc125da55) | Jul 05, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [d6adb170de](https://linux-hardware.org/?probe=d6adb170de) | Jun 25, 2022 |
| Google        | Kohaku                      | Notebook    | [f43841c5e0](https://linux-hardware.org/?probe=f43841c5e0) | Jun 08, 2022 |
| Google        | Kohaku                      | Notebook    | [740a608274](https://linux-hardware.org/?probe=740a608274) | Jun 08, 2022 |
| Lenovo        | ThinkPad T440s 20ARS32P0... | Notebook    | [100b65a86d](https://linux-hardware.org/?probe=100b65a86d) | Jun 04, 2022 |
| Dell          | 060K5C A06                  | Server      | [c8be539d80](https://linux-hardware.org/?probe=c8be539d80) | May 14, 2022 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [2fecc1fd76](https://linux-hardware.org/?probe=2fecc1fd76) | Apr 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [5ac68bc542](https://linux-hardware.org/?probe=5ac68bc542) | Mar 16, 2022 |
| Gigabyte      | Z590 AORUS PRO AX           | Desktop     | [a517886d4d](https://linux-hardware.org/?probe=a517886d4d) | Feb 10, 2022 |
| Dell          | 0R4CNN A02                  | Server      | [c701d3a15f](https://linux-hardware.org/?probe=c701d3a15f) | Feb 07, 2022 |
| Intel         | powered classmate PC        | Notebook    | [0585f5b715](https://linux-hardware.org/?probe=0585f5b715) | Dec 12, 2021 |
| Intel         | powered classmate PC        | Notebook    | [9416f348e4](https://linux-hardware.org/?probe=9416f348e4) | Dec 12, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [c28c41bdd4](https://linux-hardware.org/?probe=c28c41bdd4) | Nov 05, 2021 |
| Dell          | Inspiron 3185               | Notebook    | [53ac57fbea](https://linux-hardware.org/?probe=53ac57fbea) | Oct 26, 2021 |
| Dell          | Inspiron 3185               | Notebook    | [2c9cec7881](https://linux-hardware.org/?probe=2c9cec7881) | Oct 01, 2021 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [1a59499d3a](https://linux-hardware.org/?probe=1a59499d3a) | Sep 29, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [95a2b3a95d](https://linux-hardware.org/?probe=95a2b3a95d) | Aug 27, 2021 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [972f935578](https://linux-hardware.org/?probe=972f935578) | Aug 23, 2021 |
| HP            | EliteBook 8570w             | Notebook    | [37e72494a5](https://linux-hardware.org/?probe=37e72494a5) | Jul 29, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | Notebook    | [cdf0f4017c](https://linux-hardware.org/?probe=cdf0f4017c) | Jul 16, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [9044b57593](https://linux-hardware.org/?probe=9044b57593) | Jul 11, 2021 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [21a6135eda](https://linux-hardware.org/?probe=21a6135eda) | Jun 16, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [e5a30a171e](https://linux-hardware.org/?probe=e5a30a171e) | Jun 08, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [043878564d](https://linux-hardware.org/?probe=043878564d) | Jun 08, 2021 |
| Dell          | Inspiron 3185               | Notebook    | [84fa76eb2f](https://linux-hardware.org/?probe=84fa76eb2f) | Apr 20, 2021 |
| Dell          | Inspiron 3185               | Notebook    | [d49edb76fa](https://linux-hardware.org/?probe=d49edb76fa) | Apr 15, 2021 |
| Dell          | Inspiron 3185               | Notebook    | [15b8da5bc1](https://linux-hardware.org/?probe=15b8da5bc1) | Apr 14, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [f0791eb42d](https://linux-hardware.org/?probe=f0791eb42d) | Mar 30, 2021 |
| HP            | 0AE8h C                     | Desktop     | [b7fd559b13](https://linux-hardware.org/?probe=b7fd559b13) | Mar 24, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [8810309035](https://linux-hardware.org/?probe=8810309035) | Mar 24, 2021 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| AlmaLinux 8.6 | 9         | 30%     |
| AlmaLinux 8.4 | 9         | 30%     |
| AlmaLinux 9.0 | 5         | 16.67%  |
| AlmaLinux 8.3 | 4         | 13.33%  |
| AlmaLinux 8.5 | 3         | 10%     |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| AlmaLinux | 30        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                       | Computers | Percent |
|-------------------------------|-----------|---------|
| 5.14.0-70.22.1.el9_0.x86_64   | 3         | 10%     |
| 4.18.0-240.15.1.el8_3.x86_64  | 3         | 10%     |
| 4.18.0-372.9.1.el8.x86_64     | 2         | 6.67%   |
| 4.18.0-372.26.1.el8_6.x86_64  | 2         | 6.67%   |
| 4.18.0-348.12.2.el8_5.x86_64  | 2         | 6.67%   |
| 4.18.0-305.el8.x86_64         | 2         | 6.67%   |
| 4.18.0-305.7.1.el8_4.x86_64   | 2         | 6.67%   |
| 4.18.0-305.12.1.el8_4.x86_64  | 2         | 6.67%   |
| 5.4.175-1.el8.elrepo.x86_64   | 1         | 3.33%   |
| 5.15.45-v8.1.el8              | 1         | 3.33%   |
| 5.14.0-70.17.1.el9_0.x86_64   | 1         | 3.33%   |
| 5.14.0-70.13.1.el9_0.x86_64   | 1         | 3.33%   |
| 5.10.60-v8.1.el8              | 1         | 3.33%   |
| 4.18.0-372.19.1.el8_6.x86_64  | 1         | 3.33%   |
| 4.18.0-372.16.1.el8_6.aarch64 | 1         | 3.33%   |
| 4.18.0-348.el8.x86_64         | 1         | 3.33%   |
| 4.18.0-348.2.1.el8_5.x86_64   | 1         | 3.33%   |
| 4.18.0-305.3.1.el8_4.x86_64   | 1         | 3.33%   |
| 4.18.0-305.10.2.el8_4.x86_64  | 1         | 3.33%   |
| 4.18.0-240.22.1.el8_3.x86_64  | 1         | 3.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18.0  | 22        | 73.33%  |
| 5.14.0  | 5         | 16.67%  |
| 5.4.175 | 1         | 3.33%   |
| 5.15.45 | 1         | 3.33%   |
| 5.10.60 | 1         | 3.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18    | 22        | 73.33%  |
| 5.14    | 5         | 16.67%  |
| 5.4     | 1         | 3.33%   |
| 5.15    | 1         | 3.33%   |
| 5.10    | 1         | 3.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 27        | 90%     |
| aarch64 | 3         | 10%     |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GNOME   | 21        | 70%     |
| Unknown | 5         | 16.67%  |
| MATE    | 2         | 6.67%   |
| XFCE    | 1         | 3.33%   |
| KDE5    | 1         | 3.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 15        | 50%     |
| X11     | 12        | 40%     |
| Unknown | 2         | 6.67%   |
| Tty     | 1         | 3.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 17        | 56.67%  |
| GDM     | 11        | 36.67%  |
| LightDM | 2         | 6.67%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 16        | 53.33%  |
| de_DE   | 5         | 16.67%  |
| fr_FR   | 2         | 6.67%   |
| uk_UA   | 1         | 3.33%   |
| ru_RU   | 1         | 3.33%   |
| es_VE   | 1         | 3.33%   |
| en_GB   | 1         | 3.33%   |
| en_CA   | 1         | 3.33%   |
| C       | 1         | 3.33%   |
| Unknown | 1         | 3.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 18        | 60%     |
| BIOS | 12        | 40%     |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Xfs  | 23        | 76.67%  |
| Ext4 | 7         | 23.33%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 16        | 53.33%  |
| Unknown | 10        | 33.33%  |
| MBR     | 4         | 13.33%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 24        | 80%     |
| Yes       | 6         | 20%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 24        | 80%     |
| Yes       | 6         | 20%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 8         | 26.67%  |
| Hewlett-Packard         | 7         | 23.33%  |
| Dell                    | 3         | 10%     |
| Raspberry Pi Foundation | 2         | 6.67%   |
| Intel                   | 2         | 6.67%   |
| Gigabyte Technology     | 2         | 6.67%   |
| ASUSTek Computer        | 2         | 6.67%   |
| Acer                    | 2         | 6.67%   |
| Google                  | 1         | 3.33%   |
| ASRock                  | 1         | 3.33%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| RPi Raspberry Pi                     | 2         | 6.67%   |
| Lenovo Yoga 2 13 20344               | 1         | 3.33%   |
| Lenovo ThinkStation P350 30E6S20S00  | 1         | 3.33%   |
| Lenovo ThinkPad T440s 20ARS32P00     | 1         | 3.33%   |
| Lenovo ThinkPad T14 Gen 1 20S1S39Q00 | 1         | 3.33%   |
| Lenovo Legion 5 15IMH05H 81Y6        | 1         | 3.33%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS  | 1         | 3.33%   |
| Lenovo IdeaPad S145-15IWL 81MV       | 1         | 3.33%   |
| Lenovo IdeaPad 330-15ARR 81D2        | 1         | 3.33%   |
| Intel powered classmate PC           | 1         | 3.33%   |
| Intel NUC8i5BEH                      | 1         | 3.33%   |
| HP Z600 Workstation                  | 1         | 3.33%   |
| HP Laptop 17-cp0xxx                  | 1         | 3.33%   |
| HP Laptop 15-ef1xxx                  | 1         | 3.33%   |
| HP Falco                             | 1         | 3.33%   |
| HP ENVY dv6                          | 1         | 3.33%   |
| HP EliteBook 8570w                   | 1         | 3.33%   |
| HP EliteBook 8470p                   | 1         | 3.33%   |
| Google Kohaku                        | 1         | 3.33%   |
| Gigabyte Z590 AORUS PRO AX           | 1         | 3.33%   |
| Gigabyte MP32-AR1-00                 | 1         | 3.33%   |
| Dell Precision 7920 Tower            | 1         | 3.33%   |
| Dell PowerEdge R6515                 | 1         | 3.33%   |
| Dell Inspiron 3185                   | 1         | 3.33%   |
| ASUS M5A78L-M/USB3                   | 1         | 3.33%   |
| ASUS ASUS EXPERTBOOK B9450FA_B9450FA | 1         | 3.33%   |
| ASRock B460 Phantom Gaming 4         | 1         | 3.33%   |
| Acer TravelMate 5735Z                | 1         | 3.33%   |
| Acer TMP453-MG                       | 1         | 3.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Lenovo IdeaPad       | 3         | 10%     |
| RPi Raspberry        | 2         | 6.67%   |
| Lenovo ThinkPad      | 2         | 6.67%   |
| HP Laptop            | 2         | 6.67%   |
| HP EliteBook         | 2         | 6.67%   |
| Lenovo Yoga          | 1         | 3.33%   |
| Lenovo ThinkStation  | 1         | 3.33%   |
| Lenovo Legion        | 1         | 3.33%   |
| Intel powered        | 1         | 3.33%   |
| Intel NUC8i5BEH      | 1         | 3.33%   |
| HP Z600              | 1         | 3.33%   |
| HP Falco             | 1         | 3.33%   |
| HP ENVY              | 1         | 3.33%   |
| Google Kohaku        | 1         | 3.33%   |
| Gigabyte Z590        | 1         | 3.33%   |
| Gigabyte MP32-AR1-00 | 1         | 3.33%   |
| Dell Precision       | 1         | 3.33%   |
| Dell PowerEdge       | 1         | 3.33%   |
| Dell Inspiron        | 1         | 3.33%   |
| ASUS M5A78L-M        | 1         | 3.33%   |
| ASUS ASUS            | 1         | 3.33%   |
| ASRock B460          | 1         | 3.33%   |
| Acer TravelMate      | 1         | 3.33%   |
| Acer TMP453-MG       | 1         | 3.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 5         | 16.67%  |
| 2019    | 4         | 13.33%  |
| 2022    | 3         | 10%     |
| 2021    | 3         | 10%     |
| 2012    | 3         | 10%     |
| 2011    | 3         | 10%     |
| 2018    | 2         | 6.67%   |
| 2014    | 2         | 6.67%   |
| Unknown | 2         | 6.67%   |
| 2013    | 1         | 3.33%   |
| 2010    | 1         | 3.33%   |
| 2009    | 1         | 3.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 19        | 63.33%  |
| Desktop        | 5         | 16.67%  |
| Server         | 3         | 10%     |
| System on chip | 2         | 6.67%   |
| Mini pc        | 1         | 3.33%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 26        | 86.67%  |
| Enabled  | 4         | 13.33%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 28        | 93.33%  |
| Yes  | 2         | 6.67%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 10        | 33.33%  |
| 16.01-24.0      | 4         | 13.33%  |
| 8.01-16.0       | 4         | 13.33%  |
| 3.01-4.0        | 3         | 10%     |
| More than 256.0 | 2         | 6.67%   |
| 1.01-2.0        | 2         | 6.67%   |
| 0.51-1.0        | 2         | 6.67%   |
| 32.01-64.0      | 1         | 3.33%   |
| 24.01-32.0      | 1         | 3.33%   |
| 64.01-256.0     | 1         | 3.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 7         | 22.58%  |
| 1.01-2.0   | 7         | 22.58%  |
| 4.01-8.0   | 6         | 19.35%  |
| 3.01-4.0   | 4         | 12.9%   |
| 0.51-1.0   | 2         | 6.45%   |
| 0.01-0.5   | 2         | 6.45%   |
| 24.01-32.0 | 1         | 3.23%   |
| 16.01-24.0 | 1         | 3.23%   |
| 8.01-16.0  | 1         | 3.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 13        | 43.33%  |
| 2      | 11        | 36.67%  |
| 4      | 3         | 10%     |
| 6      | 1         | 3.33%   |
| 3      | 1         | 3.33%   |
| 0      | 1         | 3.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 25        | 83.33%  |
| Yes       | 5         | 16.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 83.33%  |
| No        | 5         | 16.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 21        | 70%     |
| No        | 9         | 30%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 66.67%  |
| No        | 10        | 33.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 8         | 26.67%  |
| Germany      | 7         | 23.33%  |
| France       | 3         | 10%     |
| Russia       | 2         | 6.67%   |
| Venezuela    | 1         | 3.33%   |
| Ukraine      | 1         | 3.33%   |
| UK           | 1         | 3.33%   |
| Sweden       | 1         | 3.33%   |
| Spain        | 1         | 3.33%   |
| South Africa | 1         | 3.33%   |
| Pakistan     | 1         | 3.33%   |
| India        | 1         | 3.33%   |
| Finland      | 1         | 3.33%   |
| Canada       | 1         | 3.33%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Hamburg       | 3         | 10%     |
| Queens        | 2         | 6.67%   |
| Zaporizhzhia  | 1         | 3.33%   |
| Uppsala       | 1         | 3.33%   |
| Tuusula       | 1         | 3.33%   |
| Shimanovsk    | 1         | 3.33%   |
| San Diego     | 1         | 3.33%   |
| Paris         | 1         | 3.33%   |
| Moscow        | 1         | 3.33%   |
| Mangalore     | 1         | 3.33%   |
| Liverpool     | 1         | 3.33%   |
| Lille         | 1         | 3.33%   |
| Lawrence      | 1         | 3.33%   |
| Land O' Lakes | 1         | 3.33%   |
| Lahore        | 1         | 3.33%   |
| Kitimat       | 1         | 3.33%   |
| Kennewick     | 1         | 3.33%   |
| Johannesburg  | 1         | 3.33%   |
| Guglingen     | 1         | 3.33%   |
| Guanare       | 1         | 3.33%   |
| Frankenthal   | 1         | 3.33%   |
| Essen         | 1         | 3.33%   |
| Castelginest  | 1         | 3.33%   |
| Bloomington   | 1         | 3.33%   |
| Berlin        | 1         | 3.33%   |
| Barcelona     | 1         | 3.33%   |
| Austin        | 1         | 3.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 6      | 13.95%  |
| Seagate             | 6         | 12     | 13.95%  |
| Samsung Electronics | 6         | 9      | 13.95%  |
| Unknown             | 3         | 3      | 6.98%   |
| SK hynix            | 2         | 2      | 4.65%   |
| LITEONIT            | 2         | 2      | 4.65%   |
| Kingston            | 2         | 2      | 4.65%   |
| Intel               | 2         | 2      | 4.65%   |
| Dell                | 2         | 3      | 4.65%   |
| Union Memory        | 1         | 1      | 2.33%   |
| Toshiba             | 1         | 1      | 2.33%   |
| SSSTC               | 1         | 1      | 2.33%   |
| Netac               | 1         | 1      | 2.33%   |
| Micron Technology   | 1         | 1      | 2.33%   |
| Hitachi             | 1         | 1      | 2.33%   |
| EMTEC               | 1         | 2      | 2.33%   |
| DELLBOSS            | 1         | 1      | 2.33%   |
| Crucial             | 1         | 2      | 2.33%   |
| China               | 1         | 1      | 2.33%   |
| ASMT                | 1         | 2      | 2.33%   |
| A-DATA Technology   | 1         | 1      | 2.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| WDC WD10SPZX-24Z10 1TB                      | 2         | 4.26%   |
| WDC WD5000LPCX-21VHAT0 500GB                | 1         | 2.13%   |
| WDC WD10SPZX-60Z10T1 1TB                    | 1         | 2.13%   |
| WDC WD10EZEX-08WN4A0 1TB                    | 1         | 2.13%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB        | 1         | 2.13%   |
| Unknown SD64G  64GB                         | 1         | 2.13%   |
| Unknown SD/MMC/MS PRO 2GB                   | 1         | 2.13%   |
| Unknown EC2QT  64GB                         | 1         | 2.13%   |
| Union Memory UMIS RPITJ512VME2OWD 512GB     | 1         | 2.13%   |
| Toshiba MK6475GSX 640GB                     | 1         | 2.13%   |
| SSSTC CL1-3D256 256GB                       | 1         | 2.13%   |
| SK hynix SH920 2.5 7MM 256GB SSD            | 1         | 2.13%   |
| SK hynix NVMe SSD Drive 256GB               | 1         | 2.13%   |
| Seagate ST4000NM000A 00MX141 00MX141LEN 4TB | 1         | 2.13%   |
| Seagate ST4000NC001-1FS168 4TB              | 1         | 2.13%   |
| Seagate ST4000DM000-1F2168 4TB              | 1         | 2.13%   |
| Seagate ST250LM004 HN-M250MBB 250GB         | 1         | 2.13%   |
| Seagate ST2000NM012A-2MP130 2TB             | 1         | 2.13%   |
| Seagate ST2000LM015-2E8174 2TB              | 1         | 2.13%   |
| Seagate ST2000DM001-1ER164 2TB              | 1         | 2.13%   |
| Seagate ST1000NM0033-9ZM173 1TB             | 1         | 2.13%   |
| Seagate ST10000NM0478-2H7100 10TB           | 1         | 2.13%   |
| Samsung SSD PM810 FDE 2.5 256GB             | 1         | 2.13%   |
| Samsung SSD 970 EVO Plus 250GB              | 1         | 2.13%   |
| Samsung PSSD T7 Touch 1TB                   | 1         | 2.13%   |
| Samsung MZVLQ512HALU-00000 512GB            | 1         | 2.13%   |
| Samsung MZVLQ128HBHQ-000H1 128GB            | 1         | 2.13%   |
| Samsung MZVL22T0HBLB-00BL7 2TB              | 1         | 2.13%   |
| Samsung MZQL23T8HCLS-00A07 3.8TB            | 1         | 2.13%   |
| Netac SSD 512GB                             | 1         | 2.13%   |
| Micron MTFDDAK256MAM-1K12 256GB SSD         | 1         | 2.13%   |
| LITEONIT LSS-16L6G-HP 16GB SSD              | 1         | 2.13%   |
| LITEONIT LGT-128M6G 128GB SSD               | 1         | 2.13%   |
| Kingston SV300S37A240G 240GB SSD            | 1         | 2.13%   |
| Kingston SA400S37240G 240GB SSD             | 1         | 2.13%   |
| Intel SSDSC2KF128G8L 128GB                  | 1         | 2.13%   |
| Intel SSDSC2KB019T8R 1.9TB                  | 1         | 2.13%   |
| Hitachi HTS545032B9A300 320GB               | 1         | 2.13%   |
| EMTEC X200 256GB                            | 1         | 2.13%   |
| DELLBOSS VD 240GB                           | 1         | 2.13%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 6         | 12     | 37.5%   |
| WDC      | 5         | 5      | 31.25%  |
| Unknown  | 1         | 1      | 6.25%   |
| Toshiba  | 1         | 1      | 6.25%   |
| Hitachi  | 1         | 1      | 6.25%   |
| DELLBOSS | 1         | 1      | 6.25%   |
| ASMT     | 1         | 2      | 6.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 14.29%  |
| LITEONIT            | 2         | 2      | 14.29%  |
| Kingston            | 2         | 2      | 14.29%  |
| Intel               | 2         | 2      | 14.29%  |
| SK hynix            | 1         | 1      | 7.14%   |
| Netac               | 1         | 1      | 7.14%   |
| Micron Technology   | 1         | 1      | 7.14%   |
| Dell                | 1         | 2      | 7.14%   |
| China               | 1         | 1      | 7.14%   |
| A-DATA Technology   | 1         | 1      | 7.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 16        | 23     | 37.21%  |
| SSD     | 13        | 15     | 30.23%  |
| NVMe    | 11        | 14     | 25.58%  |
| MMC     | 2         | 2      | 4.65%   |
| Unknown | 1         | 2      | 2.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 22        | 34     | 57.89%  |
| NVMe | 11        | 14     | 28.95%  |
| SAS  | 3         | 6      | 7.89%   |
| MMC  | 2         | 2      | 5.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 15        | 17     | 48.39%  |
| 0.51-1.0   | 8         | 8      | 25.81%  |
| 3.01-4.0   | 3         | 3      | 9.68%   |
| 1.01-2.0   | 3         | 7      | 9.68%   |
| 4.01-10.0  | 2         | 3      | 6.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 9         | 30%     |
| 251-500        | 5         | 16.67%  |
| More than 3000 | 4         | 13.33%  |
| 501-1000       | 3         | 10%     |
| 21-50          | 2         | 6.67%   |
| 1001-2000      | 2         | 6.67%   |
| 1-20           | 2         | 6.67%   |
| 2001-3000      | 1         | 3.33%   |
| 51-100         | 1         | 3.33%   |
| Unknown        | 1         | 3.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 12        | 38.71%  |
| 21-50          | 6         | 19.35%  |
| 51-100         | 5         | 16.13%  |
| 251-500        | 3         | 9.68%   |
| 101-250        | 2         | 6.45%   |
| More than 3000 | 1         | 3.23%   |
| 501-1000       | 1         | 3.23%   |
| Unknown        | 1         | 3.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| SK hynix SH920 2.5 7MM 256GB SSD | 1         | 1      | 50%     |
| LITEONIT LSS-16L6G-HP 16GB SSD   | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| SK hynix | 1         | 1      | 50%     |
| LITEONIT | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 2         | 2      | 100%    |

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
| Works    | 16        | 29     | 48.48%  |
| Detected | 15        | 25     | 45.45%  |
| Malfunc  | 2         | 2      | 6.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 19        | 50%     |
| AMD                            | 6         | 15.79%  |
| Samsung Electronics            | 5         | 13.16%  |
| Union Memory (Shenzhen)        | 2         | 5.26%   |
| Solid State Storage Technology | 1         | 2.63%   |
| SK hynix                       | 1         | 2.63%   |
| SanDisk                        | 1         | 2.63%   |
| Micron/Crucial Technology      | 1         | 2.63%   |
| Marvell Technology Group       | 1         | 2.63%   |
| Broadcom / LSI                 | 1         | 2.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                   | 5         | 12.2%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                          | 3         | 7.32%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]      | 3         | 7.32%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                | 2         | 4.88%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                        | 2         | 4.88%   |
| Samsung NVMe SSD Controller 980                                       | 2         | 4.88%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                     | 2         | 4.88%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                  | 2         | 4.88%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                  | 2         | 4.88%   |
| Solid State Storage Non-Volatile memory controller                    | 1         | 2.44%   |
| SK hynix BC511                                                        | 1         | 2.44%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                            | 1         | 2.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                         | 1         | 2.44%   |
| Micron/Crucial Non-Volatile memory controller                         | 1         | 2.44%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller | 1         | 2.44%   |
| Intel SATA Controller [RAID mode]                                     | 1         | 2.44%   |
| Intel NVMe Datacenter SSD [3DNAND, Beta Rock Controller]              | 1         | 2.44%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                    | 1         | 2.44%   |
| Intel Comet Lake SATA AHCI Controller                                 | 1         | 2.44%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]         | 1         | 2.44%   |
| Intel C620 Series Chipset Family IDE Redirection                      | 1         | 2.44%   |
| Intel C600/X79 series chipset SATA RAID Controller                    | 1         | 2.44%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode] | 1         | 2.44%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                        | 1         | 2.44%   |
| Broadcom / LSI MegaRAID Tri-Mode SAS3408                              | 1         | 2.44%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                      | 1         | 2.44%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                  | 1         | 2.44%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 22        | 56.41%  |
| NVMe | 12        | 30.77%  |
| RAID | 3         | 7.69%   |
| IDE  | 2         | 5.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 20        | 66.67%  |
| AMD    | 7         | 23.33%  |
| ARM    | 3         | 10%     |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 10%     |
| ARM Processor                                 | 3         | 10%     |
| Intel Xeon W-1350 @ 3.30GHz                   | 1         | 3.33%   |
| Intel Xeon Gold 5220R CPU @ 2.20GHz           | 1         | 3.33%   |
| Intel Xeon CPU X5550 @ 2.67GHz                | 1         | 3.33%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 3.33%   |
| Intel Core i7-3840QM CPU @ 2.80GHz            | 1         | 3.33%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 3.33%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 3.33%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 1         | 3.33%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 3.33%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 3.33%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 3.33%   |
| Intel Core i5-10400F CPU @ 2.90GHz            | 1         | 3.33%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 1         | 3.33%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 1         | 3.33%   |
| Intel Celeron 2955U @ 1.40GHz                 | 1         | 3.33%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 1         | 3.33%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz        | 1         | 3.33%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 1         | 3.33%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 1         | 3.33%   |
| AMD Ryzen 3 3250U with Radeon Graphics        | 1         | 3.33%   |
| AMD FX-8350 Eight-Core Processor              | 1         | 3.33%   |
| AMD EPYC 7402P 24-Core Processor              | 1         | 3.33%   |
| AMD A9-9420e RADEON R5, 5 COMPUTE CORES 2C+3G | 1         | 3.33%   |
| AMD A6-9220e RADEON R4, 5 COMPUTE CORES 2C+3G | 1         | 3.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 8         | 26.67%  |
| Other                   | 5         | 16.67%  |
| Intel Core i7           | 3         | 10%     |
| Intel Xeon              | 2         | 6.67%   |
| Intel Core i3           | 2         | 6.67%   |
| Intel Xeon Gold         | 1         | 3.33%   |
| Intel Pentium Dual-Core | 1         | 3.33%   |
| Intel Celeron           | 1         | 3.33%   |
| Intel Atom              | 1         | 3.33%   |
| AMD Ryzen 7             | 1         | 3.33%   |
| AMD Ryzen 5             | 1         | 3.33%   |
| AMD Ryzen 3             | 1         | 3.33%   |
| AMD FX                  | 1         | 3.33%   |
| AMD EPYC                | 1         | 3.33%   |
| AMD A6                  | 1         | 3.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 10        | 33.33%  |
| 4       | 9         | 30%     |
| 6       | 4         | 13.33%  |
| Unknown | 2         | 6.67%   |
| 80      | 1         | 3.33%   |
| 48      | 1         | 3.33%   |
| 24      | 1         | 3.33%   |
| 8       | 1         | 3.33%   |
| 1       | 1         | 3.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 27        | 90%     |
| Unknown | 2         | 6.67%   |
| 2       | 1         | 3.33%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 23        | 76.67%  |
| 1       | 5         | 16.67%  |
| Unknown | 2         | 6.67%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 27        | 90%     |
| Unknown        | 3         | 10%     |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 5         | 16.67%  |
| 0x806ec    | 4         | 13.33%  |
| 0x306a9    | 4         | 13.33%  |
| 0x40651    | 3         | 10%     |
| 0xa0671    | 2         | 6.67%   |
| 0xa0655    | 1         | 3.33%   |
| 0xa0652    | 1         | 3.33%   |
| 0x50657    | 1         | 3.33%   |
| 0x106ca    | 1         | 3.33%   |
| 0x106a5    | 1         | 3.33%   |
| 0x1067a    | 1         | 3.33%   |
| 0x08608103 | 1         | 3.33%   |
| 0x08108109 | 1         | 3.33%   |
| 0x0810100b | 1         | 3.33%   |
| 0x06006705 | 1         | 3.33%   |
| 0x06006704 | 1         | 3.33%   |
| 0x06000852 | 1         | 3.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KabyLake   | 5         | 16.67%  |
| IvyBridge  | 4         | 13.33%  |
| Unknown    | 4         | 13.33%  |
| Haswell    | 3         | 10%     |
| Icelake    | 2         | 6.67%   |
| Excavator  | 2         | 6.67%   |
| CometLake  | 2         | 6.67%   |
| Zen+       | 1         | 3.33%   |
| Zen 2      | 1         | 3.33%   |
| Zen        | 1         | 3.33%   |
| Skylake    | 1         | 3.33%   |
| Piledriver | 1         | 3.33%   |
| Penryn     | 1         | 3.33%   |
| Nehalem    | 1         | 3.33%   |
| Bonnell    | 1         | 3.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 15        | 51.72%  |
| AMD                        | 8         | 27.59%  |
| Nvidia                     | 4         | 13.79%  |
| Matrox Electronics Systems | 1         | 3.45%   |
| ASPEED Technology          | 1         | 3.45%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                         | 3         | 10.34%  |
| Intel CometLake-U GT2 [UHD Graphics]                                     | 3         | 10.34%  |
| Intel 3rd Gen Core processor Graphics Controller                         | 2         | 6.9%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                 | 2         | 6.9%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                               | 1         | 3.45%   |
| Nvidia GK107GLM [Quadro K1000M]                                          | 1         | 3.45%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                        | 1         | 3.45%   |
| Nvidia GA102GL [RTX A6000]                                               | 1         | 3.45%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller | 1         | 3.45%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                               | 1         | 3.45%   |
| Intel RocketLake-S GT1 [UHD Graphics P750]                               | 1         | 3.45%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                | 1         | 3.45%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller             | 1         | 3.45%   |
| Intel CometLake-H GT2 [UHD Graphics]                                     | 1         | 3.45%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                         | 1         | 3.45%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller  | 1         | 3.45%   |
| ASPEED Technology ASPEED Graphics Family                                 | 1         | 3.45%   |
| AMD RS780L [Radeon 3000]                                                 | 1         | 3.45%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]         | 1         | 3.45%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]     | 1         | 3.45%   |
| AMD Lucienne                                                             | 1         | 3.45%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                  | 1         | 3.45%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]      | 1         | 3.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 14        | 46.67%  |
| 1 x AMD        | 8         | 26.67%  |
| 1 x Nvidia     | 3         | 10%     |
| Other          | 2         | 6.67%   |
| 1 x Matrox     | 1         | 3.33%   |
| Intel + Nvidia | 1         | 3.33%   |
| 1 x ASPEED     | 1         | 3.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 24        | 80%     |
| Unknown     | 4         | 13.33%  |
| Proprietary | 2         | 6.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 19        | 63.33%  |
| 0.01-0.5   | 5         | 16.67%  |
| 1.01-2.0   | 3         | 10%     |
| 7.01-8.0   | 1         | 3.33%   |
| 32.01-64.0 | 1         | 3.33%   |
| 5.01-6.0   | 1         | 3.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 6         | 20.69%  |
| LG Display              | 5         | 17.24%  |
| Samsung Electronics     | 3         | 10.34%  |
| Dell                    | 2         | 6.9%    |
| BOE                     | 2         | 6.9%    |
| STD                     | 1         | 3.45%   |
| Sharp                   | 1         | 3.45%   |
| Seiki                   | 1         | 3.45%   |
| Philips                 | 1         | 3.45%   |
| PANDA                   | 1         | 3.45%   |
| Lenovo                  | 1         | 3.45%   |
| InfoVision              | 1         | 3.45%   |
| Goldstar                | 1         | 3.45%   |
| Chimei Innolux          | 1         | 3.45%   |
| Chi Mei Optoelectronics | 1         | 3.45%   |
| BenQ                    | 1         | 3.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| STD HDMI TV STD00C7 1920x1080 698x392mm 31.5-inch                        | 1         | 3.33%   |
| Sharp LC-32LB480U SHP3263 1920x1080 698x392mm 31.5-inch                  | 1         | 3.33%   |
| Seiki SC32HT04 SEK1366 1366x768 700x390mm 31.5-inch                      | 1         | 3.33%   |
| Samsung Electronics SyncMaster SAM021B 1400x1050 408x300mm 19.9-inch     | 1         | 3.33%   |
| Samsung Electronics S27H65x SAM0E1D 1920x1080 598x336mm 27.0-inch        | 1         | 3.33%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch     | 1         | 3.33%   |
| Samsung Electronics LCD Monitor SDC4142 3840x2160 294x165mm 13.3-inch    | 1         | 3.33%   |
| Philips 19B PHL0879 1280x1024 376x301mm 19.0-inch                        | 1         | 3.33%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                  | 1         | 3.33%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch             | 1         | 3.33%   |
| LG Display LCD Monitor LGD042D 1920x1080 290x170mm 13.2-inch             | 1         | 3.33%   |
| LG Display LCD Monitor LGD034A 1366x768 345x194mm 15.6-inch              | 1         | 3.33%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch              | 1         | 3.33%   |
| LG Display LCD Monitor LGD02A5 1366x768 345x194mm 15.6-inch              | 1         | 3.33%   |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                     | 1         | 3.33%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch             | 1         | 3.33%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 1         | 3.33%   |
| Dell U2410 DELF015 1920x1200 518x324mm 24.1-inch                         | 1         | 3.33%   |
| Dell 1905FP DEL400C 1280x1024 376x301mm 19.0-inch                        | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 309x174mm 14.0-inch          | 1         | 3.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 1         | 3.33%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 1         | 3.33%   |
| BOE LCD Monitor BOE07A3 1920x1080 344x193mm 15.5-inch                    | 1         | 3.33%   |
| BenQ GL2450 BNQ78A5 1920x1080 531x298mm 24.0-inch                        | 1         | 3.33%   |
| AU Optronics LCD Monitor AUOF992 1920x1080 382x215mm 17.3-inch           | 1         | 3.33%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch           | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO623D 1920x1080 309x174mm 14.0-inch           | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO13ED 1920x1080 344x193mm 15.5-inch           | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch            | 1         | 3.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 16        | 53.33%  |
| 1366x768 (WXGA)   | 7         | 23.33%  |
| 1280x1024 (SXGA)  | 2         | 6.67%   |
| 3840x2160 (4K)    | 1         | 3.33%   |
| 2560x1440 (QHD)   | 1         | 3.33%   |
| 2560x1080         | 1         | 3.33%   |
| 1920x1200 (WUXGA) | 1         | 3.33%   |
| 1400x1050         | 1         | 3.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 9         | 30%     |
| 14     | 6         | 20%     |
| 31     | 3         | 10%     |
| 24     | 3         | 10%     |
| 19     | 2         | 6.67%   |
| 13     | 2         | 6.67%   |
| 34     | 1         | 3.33%   |
| 27     | 1         | 3.33%   |
| 20     | 1         | 3.33%   |
| 17     | 1         | 3.33%   |
| 11     | 1         | 3.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 15        | 50%     |
| 501-600     | 4         | 13.33%  |
| 601-700     | 3         | 10%     |
| 351-400     | 3         | 10%     |
| 201-300     | 3         | 10%     |
| 701-800     | 1         | 3.33%   |
| 401-500     | 1         | 3.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 22        | 81.48%  |
| 6/5   | 1         | 3.7%    |
| 5/4   | 1         | 3.7%    |
| 4/3   | 1         | 3.7%    |
| 21/9  | 1         | 3.7%    |
| 16/10 | 1         | 3.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 9         | 30%     |
| 81-90          | 6         | 20%     |
| 351-500        | 4         | 13.33%  |
| 151-200        | 3         | 10%     |
| 71-80          | 2         | 6.67%   |
| 201-250        | 2         | 6.67%   |
| 51-60          | 1         | 3.33%   |
| 301-350        | 1         | 3.33%   |
| 251-300        | 1         | 3.33%   |
| 121-130        | 1         | 3.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 12        | 41.38%  |
| 51-100        | 10        | 34.48%  |
| 101-120       | 4         | 13.79%  |
| More than 240 | 1         | 3.45%   |
| 1-50          | 1         | 3.45%   |
| 161-240       | 1         | 3.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 21        | 70%     |
| 2     | 5         | 16.67%  |
| 0     | 4         | 13.33%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 15        | 38.46%  |
| Realtek Semiconductor | 7         | 17.95%  |
| Qualcomm Atheros      | 5         | 12.82%  |
| Broadcom              | 3         | 7.69%   |
| Standard Microsystems | 2         | 5.13%   |
| Broadcom Limited      | 2         | 5.13%   |
| TP-Link               | 1         | 2.56%   |
| Sierra Wireless       | 1         | 2.56%   |
| Samsung Electronics   | 1         | 2.56%   |
| Mellanox Technologies | 1         | 2.56%   |
| MediaTek              | 1         | 2.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller     | 4         | 7.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                     | 3         | 5.45%   |
| Standard Microsystems Ethernet controller                             | 2         | 3.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter              | 2         | 3.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter            | 2         | 3.64%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                      | 2         | 3.64%   |
| Intel Wireless 7260                                                   | 2         | 3.64%   |
| Intel I350 Gigabit Network Connection                                 | 2         | 3.64%   |
| Intel I210 Gigabit Network Connection                                 | 2         | 3.64%   |
| Intel Ethernet Connection (10) I219-V                                 | 2         | 3.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                 | 2         | 3.64%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]       | 1         | 1.82%   |
| Sierra Wireless EM7345 4G LTE                                         | 1         | 1.82%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)           | 1         | 1.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter              | 1         | 1.82%   |
| Realtek RTL8191SEvB Wireless LAN Controller                           | 1         | 1.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                              | 1         | 1.82%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                 | 1         | 1.82%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                 | 1         | 1.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter            | 1         | 1.82%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                         | 1         | 1.82%   |
| Mellanox MT28800 Family [ConnectX-5 Ex]                               | 1         | 1.82%   |
| MediaTek TECNO POVA 2                                                 | 1         | 1.82%   |
| Intel Wireless 8260                                                   | 1         | 1.82%   |
| Intel Wi-Fi 6 AX200                                                   | 1         | 1.82%   |
| Intel Ethernet Controller I225-V                                      | 1         | 1.82%   |
| Intel Ethernet Connection I219-LM                                     | 1         | 1.82%   |
| Intel Ethernet Connection I218-LM                                     | 1         | 1.82%   |
| Intel Ethernet Connection (6) I219-V                                  | 1         | 1.82%   |
| Intel Ethernet Connection (3) I219-LM                                 | 1         | 1.82%   |
| Intel Ethernet Connection (14) I219-LM                                | 1         | 1.82%   |
| Intel Comet Lake PCH CNVi WiFi                                        | 1         | 1.82%   |
| Intel Centrino Wireless-N 2230                                        | 1         | 1.82%   |
| Intel Centrino Ultimate-N 6300                                        | 1         | 1.82%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                  | 1         | 1.82%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                     | 1         | 1.82%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                      | 1         | 1.82%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe               | 1         | 1.82%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                               | 1         | 1.82%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller | 1         | 1.82%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 10        | 45.45%  |
| Qualcomm Atheros      | 5         | 22.73%  |
| Realtek Semiconductor | 4         | 18.18%  |
| Sierra Wireless       | 1         | 4.55%   |
| Broadcom Limited      | 1         | 4.55%   |
| Broadcom              | 1         | 4.55%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Comet Lake PCH-LP CNVi WiFi                          | 3         | 13.64%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 2         | 9.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 2         | 9.09%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 2         | 9.09%   |
| Intel Wireless 7260                                        | 2         | 9.09%   |
| Sierra Wireless EM7345 4G LTE                              | 1         | 4.55%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 4.55%   |
| Realtek RTL8191SEvB Wireless LAN Controller                | 1         | 4.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1         | 4.55%   |
| Intel Wireless 8260                                        | 1         | 4.55%   |
| Intel Wi-Fi 6 AX200                                        | 1         | 4.55%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1         | 4.55%   |
| Intel Centrino Wireless-N 2230                             | 1         | 4.55%   |
| Intel Centrino Ultimate-N 6300                             | 1         | 4.55%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                    | 1         | 4.55%   |
| Broadcom BCM43225 802.11b/g/n                              | 1         | 4.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 11        | 40.74%  |
| Realtek Semiconductor | 6         | 22.22%  |
| Standard Microsystems | 2         | 7.41%   |
| Broadcom              | 2         | 7.41%   |
| TP-Link               | 1         | 3.7%    |
| Samsung Electronics   | 1         | 3.7%    |
| Qualcomm Atheros      | 1         | 3.7%    |
| Mellanox Technologies | 1         | 3.7%    |
| MediaTek              | 1         | 3.7%    |
| Broadcom Limited      | 1         | 3.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller     | 4         | 12.12%  |
| Standard Microsystems Ethernet controller                             | 2         | 6.06%   |
| Intel I350 Gigabit Network Connection                                 | 2         | 6.06%   |
| Intel I210 Gigabit Network Connection                                 | 2         | 6.06%   |
| Intel Ethernet Connection (10) I219-V                                 | 2         | 6.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                 | 2         | 6.06%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]       | 1         | 3.03%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)           | 1         | 3.03%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                              | 1         | 3.03%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                 | 1         | 3.03%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                 | 1         | 3.03%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                         | 1         | 3.03%   |
| Mellanox MT28800 Family [ConnectX-5 Ex]                               | 1         | 3.03%   |
| MediaTek TECNO POVA 2                                                 | 1         | 3.03%   |
| Intel Ethernet Controller I225-V                                      | 1         | 3.03%   |
| Intel Ethernet Connection I219-LM                                     | 1         | 3.03%   |
| Intel Ethernet Connection I218-LM                                     | 1         | 3.03%   |
| Intel Ethernet Connection (6) I219-V                                  | 1         | 3.03%   |
| Intel Ethernet Connection (3) I219-LM                                 | 1         | 3.03%   |
| Intel Ethernet Connection (14) I219-LM                                | 1         | 3.03%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                  | 1         | 3.03%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                     | 1         | 3.03%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                      | 1         | 3.03%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe               | 1         | 3.03%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller | 1         | 3.03%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 25        | 54.35%  |
| WiFi     | 21        | 45.65%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 15        | 50%     |
| Ethernet | 15        | 50%     |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 15        | 50%     |
| 1     | 10        | 33.33%  |
| 4     | 2         | 6.67%   |
| 0     | 2         | 6.67%   |
| 6     | 1         | 3.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 24        | 80%     |
| Yes  | 6         | 20%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 9         | 45%     |
| Qualcomm Atheros Communications | 4         | 20%     |
| Realtek Semiconductor           | 3         | 15%     |
| Foxconn / Hon Hai               | 1         | 5%      |
| Cambridge Silicon Radio         | 1         | 5%      |
| Broadcom                        | 1         | 5%      |
| ASUSTek Computer                | 1         | 5%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device                  | 4         | 20%     |
| Intel AX201 Bluetooth                               | 4         | 20%     |
| Realtek Bluetooth Radio                             | 3         | 15%     |
| Intel Bluetooth wireless interface                  | 3         | 15%     |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 5%      |
| Intel AX200 Bluetooth                               | 1         | 5%      |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 5%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 5%      |
| Broadcom HP Portable SoftSailing                    | 1         | 5%      |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 5%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Intel                | 18        | 52.94%  |
| AMD                  | 8         | 23.53%  |
| Nvidia               | 4         | 11.76%  |
| C-Media Electronics  | 2         | 5.88%   |
| Giga-Byte Technology | 1         | 2.94%   |
| Conrad Electronic SE | 1         | 2.94%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 4         | 9.3%    |
| Intel Haswell-ULT HD Audio Controller                               | 3         | 6.98%   |
| Intel Comet Lake PCH-LP cAVS                                        | 3         | 6.98%   |
| Intel 8 Series HD Audio Controller                                  | 3         | 6.98%   |
| AMD Family 17h/19h HD Audio Controller                              | 3         | 6.98%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 2         | 4.65%   |
| AMD High Definition Audio Controller                                | 2         | 4.65%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                    | 2         | 4.65%   |
| Nvidia TU116 High Definition Audio Controller                       | 1         | 2.33%   |
| Nvidia GK107 HDMI Audio Controller                                  | 1         | 2.33%   |
| Nvidia GF108 High Definition Audio Controller                       | 1         | 2.33%   |
| Nvidia GA102 High Definition Audio Controller                       | 1         | 2.33%   |
| Intel Tiger Lake-H HD Audio Controller                              | 1         | 2.33%   |
| Intel NM10/ICH7 Family High Definition Audio Controller             | 1         | 2.33%   |
| Intel Lewisburg MROM 0                                              | 1         | 2.33%   |
| Intel Comet Lake PCH-V cAVS                                         | 1         | 2.33%   |
| Intel Comet Lake PCH cAVS                                           | 1         | 2.33%   |
| Intel Cannon Point-LP High Definition Audio Controller              | 1         | 2.33%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                    | 1         | 2.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                      | 1         | 2.33%   |
| Giga-Byte Technology USB Audio                                      | 1         | 2.33%   |
| Conrad Electronic SE MIDI Cable UA0037                              | 1         | 2.33%   |
| C-Media Electronics USB Audio Device                                | 1         | 2.33%   |
| C-Media Electronics CM106 Like Sound Device                         | 1         | 2.33%   |
| AMD SBx00 Azalia (Intel HDA)                                        | 1         | 2.33%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]              | 1         | 2.33%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 1         | 2.33%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]          | 1         | 2.33%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]        | 1         | 2.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 4         | 20%     |
| Samsung Electronics | 4         | 20%     |
| Micron Technology   | 4         | 20%     |
| Kingston            | 3         | 15%     |
| Unknown             | 2         | 10%     |
| Crucial             | 2         | 10%     |
| Elpida              | 1         | 5%      |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 8GB DIMM 1600MT/s                                      | 1         | 4.35%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                               | 1         | 4.35%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 4.35%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s                 | 1         | 4.35%   |
| SK hynix RAM HMAA8GR7CJR4N-XN 64GB DIMM DDR4 3200MT/s                     | 1         | 4.35%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s              | 1         | 4.35%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s          | 1         | 4.35%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                               | 1         | 4.35%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 2133MT/s                       | 1         | 4.35%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s                  | 1         | 4.35%   |
| Samsung RAM M393A4G43AB3-CWE 32GB DIMM DDR4 3200MT/s                      | 1         | 4.35%   |
| Micron RAM 9ASF2G72AZ-3G2B1 16GB DIMM DDR4 3200MT/s                       | 1         | 4.35%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s                     | 1         | 4.35%   |
| Micron RAM 4ATF51264HZ-2G6E3 4GB SODIMM DDR4 2667MT/s                     | 1         | 4.35%   |
| Micron RAM 36ASF8G72PZ-3G2E1 64GB DIMM DDR4 3200MT/s                      | 1         | 4.35%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s                      | 1         | 4.35%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s                      | 1         | 4.35%   |
| Kingston RAM 787878787878787878787878787878787878 2GB SODIMM DDR2 667MT/s | 1         | 4.35%   |
| Kingston RAM 272727272727272727272727272727272727 2GB SODIMM DDR2 667MT/s | 1         | 4.35%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s                     | 1         | 4.35%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s                    | 1         | 4.35%   |
| Crucial RAM CT8G4SFS824A.C8FDD1 8GB SODIMM DDR4 2400MT/s                  | 1         | 4.35%   |
| Crucial RAM CT8G4DFRA32A.C4FE 8192MB DIMM DDR4 3200MT/s                   | 1         | 4.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 11        | 61.11%  |
| DDR3    | 3         | 16.67%  |
| LPDDR3  | 2         | 11.11%  |
| DDR2    | 1         | 5.56%   |
| Unknown | 1         | 5.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 8         | 44.44%  |
| DIMM         | 7         | 38.89%  |
| Row Of Chips | 3         | 16.67%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 7         | 36.84%  |
| 8192  | 6         | 31.58%  |
| 65536 | 2         | 10.53%  |
| 16384 | 2         | 10.53%  |
| 32768 | 1         | 5.26%   |
| 2048  | 1         | 5.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 8         | 38.1%   |
| 1600  | 4         | 19.05%  |
| 2667  | 2         | 9.52%   |
| 2133  | 2         | 9.52%   |
| 3600  | 1         | 4.76%   |
| 2400  | 1         | 4.76%   |
| 1866  | 1         | 4.76%   |
| 1333  | 1         | 4.76%   |
| 667   | 1         | 4.76%   |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 7         | 33.33%  |
| IMC Networks                           | 4         | 19.05%  |
| Suyin                                  | 2         | 9.52%   |
| Acer                                   | 2         | 9.52%   |
| Realtek Semiconductor                  | 1         | 4.76%   |
| Microdia                               | 1         | 4.76%   |
| Luxvisions Innotech Limited            | 1         | 4.76%   |
| Logitech                               | 1         | 4.76%   |
| Creative Technology                    | 1         | 4.76%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 4.76%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                  | 3         | 13.64%  |
| Chicony Integrated HP HD Webcam                                 | 2         | 9.09%   |
| Chicony HP Truevision HD                                        | 2         | 9.09%   |
| Suyin HD WebCam                                                 | 1         | 4.55%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)     | 1         | 4.55%   |
| Realtek EasyCamera                                              | 1         | 4.55%   |
| Microdia Integrated_Webcam_HD                                   | 1         | 4.55%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 1         | 4.55%   |
| Logitech Webcam C120                                            | 1         | 4.55%   |
| IMC Networks USB2.0 HD IR UVC WebCam                            | 1         | 4.55%   |
| Creative Live! Cam Chat HD [VF0700]                             | 1         | 4.55%   |
| Chicony Lenovo EasyCamera                                       | 1         | 4.55%   |
| Chicony EasyCamera                                              | 1         | 4.55%   |
| Chicony 8M Camera                                               | 1         | 4.55%   |
| Chicony 720p HD Camera                                          | 1         | 4.55%   |
| Cheng Uei Precision Industry (Foxlink) HP True Vision HD Camera | 1         | 4.55%   |
| Acer USB Camera                                                 | 1         | 4.55%   |
| Acer Integrated Camera                                          | 1         | 4.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 4         | 80%     |
| Elan Microelectronics | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Validity Sensors VFS491                      | 2         | 40%     |
| Validity Sensors VFS 5011 fingerprint sensor | 1         | 20%     |
| Validity Sensors Fingerprint scanner         | 1         | 20%     |
| Elan ELAN:ARM-M4                             | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 20        | 66.67%  |
| 1     | 8         | 26.67%  |
| 2     | 2         | 6.67%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 5         | 41.67%  |
| Graphics card         | 2         | 16.67%  |
| Unassigned class      | 1         | 8.33%   |
| Storage/ide           | 1         | 8.33%   |
| Net/wireless          | 1         | 8.33%   |
| Multimedia controller | 1         | 8.33%   |
| Chipcard              | 1         | 8.33%   |

