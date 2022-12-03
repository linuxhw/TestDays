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

Total: 45

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | B50-30 20382                | Notebook    | [3706f368de](https://linux-hardware.org/?probe=3706f368de) | Nov 24, 2022 |
| Gigabyte      | H81M-D2V                    | Desktop     | [6035f1ee45](https://linux-hardware.org/?probe=6035f1ee45) | Nov 11, 2022 |
| ASUSTek       | Q170M2                      | Desktop     | [c62954095d](https://linux-hardware.org/?probe=c62954095d) | Nov 11, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [832ebcb956](https://linux-hardware.org/?probe=832ebcb956) | Nov 03, 2022 |
| HP            | ProLiant DL360p Gen8        | Server      | [ef43d1f352](https://linux-hardware.org/?probe=ef43d1f352) | Nov 03, 2022 |
| Toshiba       | Satellite L50-C             | Notebook    | [b3e0ff9849](https://linux-hardware.org/?probe=b3e0ff9849) | Nov 01, 2022 |
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

![OS](./images/pie_chart/os_name.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| AlmaLinux 8.6 | 10        | 27.78%  |
| AlmaLinux 9.0 | 9         | 25%     |
| AlmaLinux 8.4 | 9         | 25%     |
| AlmaLinux 8.3 | 4         | 11.11%  |
| AlmaLinux 8.5 | 3         | 8.33%   |
| AlmaLinux 9.1 | 1         | 2.78%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| AlmaLinux | 36        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Computers | Percent |
|-------------------------------|-----------|---------|
| 5.14.0-70.22.1.el9_0.x86_64   | 3         | 8.33%   |
| 4.18.0-372.26.1.el8_6.x86_64  | 3         | 8.33%   |
| 4.18.0-240.15.1.el8_3.x86_64  | 3         | 8.33%   |
| 5.14.0-70.30.1.el9_0.x86_64   | 2         | 5.56%   |
| 5.14.0-70.13.1.el9_0.x86_64   | 2         | 5.56%   |
| 4.18.0-372.9.1.el8.x86_64     | 2         | 5.56%   |
| 4.18.0-348.12.2.el8_5.x86_64  | 2         | 5.56%   |
| 4.18.0-305.el8.x86_64         | 2         | 5.56%   |
| 4.18.0-305.7.1.el8_4.x86_64   | 2         | 5.56%   |
| 4.18.0-305.12.1.el8_4.x86_64  | 2         | 5.56%   |
| 5.4.175-1.el8.elrepo.x86_64   | 1         | 2.78%   |
| 5.15.45-v8.1.el8              | 1         | 2.78%   |
| 5.14.0-70.26.1.el9_0.x86_64   | 1         | 2.78%   |
| 5.14.0-70.17.1.el9_0.x86_64   | 1         | 2.78%   |
| 5.14.0-162.6.1.el9_1.x86_64   | 1         | 2.78%   |
| 5.10.60-v8.1.el8              | 1         | 2.78%   |
| 4.18.0-372.19.1.el8_6.x86_64  | 1         | 2.78%   |
| 4.18.0-372.16.1.el8_6.aarch64 | 1         | 2.78%   |
| 4.18.0-348.el8.x86_64         | 1         | 2.78%   |
| 4.18.0-348.2.1.el8_5.x86_64   | 1         | 2.78%   |
| 4.18.0-305.3.1.el8_4.x86_64   | 1         | 2.78%   |
| 4.18.0-305.10.2.el8_4.x86_64  | 1         | 2.78%   |
| 4.18.0-240.22.1.el8_3.x86_64  | 1         | 2.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18.0  | 23        | 63.89%  |
| 5.14.0  | 10        | 27.78%  |
| 5.4.175 | 1         | 2.78%   |
| 5.15.45 | 1         | 2.78%   |
| 5.10.60 | 1         | 2.78%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18    | 23        | 63.89%  |
| 5.14    | 10        | 27.78%  |
| 5.4     | 1         | 2.78%   |
| 5.15    | 1         | 2.78%   |
| 5.10    | 1         | 2.78%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 33        | 91.67%  |
| aarch64 | 3         | 8.33%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 22        | 61.11%  |
| Unknown       | 7         | 19.44%  |
| XFCE          | 2         | 5.56%   |
| MATE          | 2         | 5.56%   |
| KDE5          | 2         | 5.56%   |
| GNOME Classic | 1         | 2.78%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 16        | 44.44%  |
| Wayland | 16        | 44.44%  |
| Tty     | 2         | 5.56%   |
| Unknown | 2         | 5.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 21        | 58.33%  |
| GDM     | 11        | 30.56%  |
| SDDM    | 2         | 5.56%   |
| LightDM | 2         | 5.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 18        | 50%     |
| de_DE   | 6         | 16.67%  |
| fr_FR   | 2         | 5.56%   |
| en_GB   | 2         | 5.56%   |
| C       | 2         | 5.56%   |
| uk_UA   | 1         | 2.78%   |
| ru_RU   | 1         | 2.78%   |
| es_VE   | 1         | 2.78%   |
| es_ES   | 1         | 2.78%   |
| en_CA   | 1         | 2.78%   |
| Unknown | 1         | 2.78%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 23        | 63.89%  |
| BIOS | 13        | 36.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Xfs  | 27        | 75%     |
| Ext4 | 9         | 25%     |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 20        | 55.56%  |
| Unknown | 12        | 33.33%  |
| MBR     | 4         | 11.11%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 28        | 77.78%  |
| Yes       | 8         | 22.22%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 29        | 80.56%  |
| Yes       | 7         | 19.44%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 10        | 27.78%  |
| Hewlett-Packard         | 8         | 22.22%  |
| Gigabyte Technology     | 3         | 8.33%   |
| Dell                    | 3         | 8.33%   |
| ASUSTek Computer        | 3         | 8.33%   |
| Raspberry Pi Foundation | 2         | 5.56%   |
| Intel                   | 2         | 5.56%   |
| Acer                    | 2         | 5.56%   |
| Toshiba                 | 1         | 2.78%   |
| Google                  | 1         | 2.78%   |
| ASRock                  | 1         | 2.78%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| RPi Raspberry Pi                     | 2         | 5.56%   |
| Toshiba Satellite L50-C              | 1         | 2.78%   |
| Lenovo Yoga 2 13 20344               | 1         | 2.78%   |
| Lenovo ThinkStation P350 30E6S20S00  | 1         | 2.78%   |
| Lenovo ThinkPad T440s 20ARS32P00     | 1         | 2.78%   |
| Lenovo ThinkPad T14 Gen 1 20S1S39Q00 | 1         | 2.78%   |
| Lenovo Legion Y530-15ICH 81FV        | 1         | 2.78%   |
| Lenovo Legion 5 15IMH05H 81Y6        | 1         | 2.78%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS  | 1         | 2.78%   |
| Lenovo IdeaPad S145-15IWL 81MV       | 1         | 2.78%   |
| Lenovo IdeaPad 330-15ARR 81D2        | 1         | 2.78%   |
| Lenovo B50-30 20382                  | 1         | 2.78%   |
| Intel powered classmate PC           | 1         | 2.78%   |
| Intel NUC8i5BEH                      | 1         | 2.78%   |
| HP Z600 Workstation                  | 1         | 2.78%   |
| HP ProLiant DL360p Gen8              | 1         | 2.78%   |
| HP Laptop 17-cp0xxx                  | 1         | 2.78%   |
| HP Laptop 15-ef1xxx                  | 1         | 2.78%   |
| HP Falco                             | 1         | 2.78%   |
| HP ENVY dv6                          | 1         | 2.78%   |
| HP EliteBook 8570w                   | 1         | 2.78%   |
| HP EliteBook 8470p                   | 1         | 2.78%   |
| Google Kohaku                        | 1         | 2.78%   |
| Gigabyte Z590 AORUS PRO AX           | 1         | 2.78%   |
| Gigabyte MP32-AR1-00                 | 1         | 2.78%   |
| Gigabyte H81M-D2V                    | 1         | 2.78%   |
| Dell Precision 7920 Tower            | 1         | 2.78%   |
| Dell PowerEdge R6515                 | 1         | 2.78%   |
| Dell Inspiron 3185                   | 1         | 2.78%   |
| ASUS Q170M2                          | 1         | 2.78%   |
| ASUS M5A78L-M/USB3                   | 1         | 2.78%   |
| ASUS ASUS EXPERTBOOK B9450FA_B9450FA | 1         | 2.78%   |
| ASRock B460 Phantom Gaming 4         | 1         | 2.78%   |
| Acer TravelMate 5735Z                | 1         | 2.78%   |
| Acer TMP453-MG                       | 1         | 2.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Lenovo IdeaPad       | 3         | 8.33%   |
| RPi Raspberry        | 2         | 5.56%   |
| Lenovo ThinkPad      | 2         | 5.56%   |
| Lenovo Legion        | 2         | 5.56%   |
| HP Laptop            | 2         | 5.56%   |
| HP EliteBook         | 2         | 5.56%   |
| Toshiba Satellite    | 1         | 2.78%   |
| Lenovo Yoga          | 1         | 2.78%   |
| Lenovo ThinkStation  | 1         | 2.78%   |
| Lenovo B50-30        | 1         | 2.78%   |
| Intel powered        | 1         | 2.78%   |
| Intel NUC8i5BEH      | 1         | 2.78%   |
| HP Z600              | 1         | 2.78%   |
| HP ProLiant          | 1         | 2.78%   |
| HP Falco             | 1         | 2.78%   |
| HP ENVY              | 1         | 2.78%   |
| Google Kohaku        | 1         | 2.78%   |
| Gigabyte Z590        | 1         | 2.78%   |
| Gigabyte MP32-AR1-00 | 1         | 2.78%   |
| Gigabyte H81M-D2V    | 1         | 2.78%   |
| Dell Precision       | 1         | 2.78%   |
| Dell PowerEdge       | 1         | 2.78%   |
| Dell Inspiron        | 1         | 2.78%   |
| ASUS Q170M2          | 1         | 2.78%   |
| ASUS M5A78L-M        | 1         | 2.78%   |
| ASUS ASUS            | 1         | 2.78%   |
| ASRock B460          | 1         | 2.78%   |
| Acer TravelMate      | 1         | 2.78%   |
| Acer TMP453-MG       | 1         | 2.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 5         | 13.89%  |
| 2019    | 4         | 11.11%  |
| 2018    | 4         | 11.11%  |
| 2012    | 4         | 11.11%  |
| 2022    | 3         | 8.33%   |
| 2021    | 3         | 8.33%   |
| 2014    | 3         | 8.33%   |
| 2011    | 3         | 8.33%   |
| 2013    | 2         | 5.56%   |
| Unknown | 2         | 5.56%   |
| 2015    | 1         | 2.78%   |
| 2010    | 1         | 2.78%   |
| 2009    | 1         | 2.78%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 22        | 61.11%  |
| Desktop        | 7         | 19.44%  |
| Server         | 4         | 11.11%  |
| System on chip | 2         | 5.56%   |
| Mini pc        | 1         | 2.78%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 31        | 86.11%  |
| Enabled  | 5         | 13.89%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 34        | 94.44%  |
| Yes  | 2         | 5.56%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 10        | 27.78%  |
| 16.01-24.0      | 6         | 16.67%  |
| 8.01-16.0       | 6         | 16.67%  |
| 3.01-4.0        | 4         | 11.11%  |
| More than 256.0 | 3         | 8.33%   |
| 1.01-2.0        | 2         | 5.56%   |
| 0.51-1.0        | 2         | 5.56%   |
| 32.01-64.0      | 1         | 2.78%   |
| 24.01-32.0      | 1         | 2.78%   |
| 64.01-256.0     | 1         | 2.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 9         | 24.32%  |
| 1.01-2.0   | 9         | 24.32%  |
| 4.01-8.0   | 6         | 16.22%  |
| 3.01-4.0   | 4         | 10.81%  |
| 0.51-1.0   | 3         | 8.11%   |
| 8.01-16.0  | 2         | 5.41%   |
| 0.01-0.5   | 2         | 5.41%   |
| 24.01-32.0 | 1         | 2.7%    |
| 16.01-24.0 | 1         | 2.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 15        | 41.67%  |
| 2      | 13        | 36.11%  |
| 4      | 4         | 11.11%  |
| 11     | 1         | 2.78%   |
| 6      | 1         | 2.78%   |
| 3      | 1         | 2.78%   |
| 0      | 1         | 2.78%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 28        | 77.78%  |
| Yes       | 8         | 22.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 86.11%  |
| No        | 5         | 13.89%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 66.67%  |
| No        | 12        | 33.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 23        | 63.89%  |
| No        | 13        | 36.11%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 9         | 25%     |
| Germany      | 8         | 22.22%  |
| France       | 3         | 8.33%   |
| UK           | 2         | 5.56%   |
| Spain        | 2         | 5.56%   |
| Russia       | 2         | 5.56%   |
| Venezuela    | 1         | 2.78%   |
| Ukraine      | 1         | 2.78%   |
| Sweden       | 1         | 2.78%   |
| South Africa | 1         | 2.78%   |
| Pakistan     | 1         | 2.78%   |
| Netherlands  | 1         | 2.78%   |
| India        | 1         | 2.78%   |
| Finland      | 1         | 2.78%   |
| Canada       | 1         | 2.78%   |
| Bulgaria     | 1         | 2.78%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Hamburg       | 3         | 8.33%   |
| Queens        | 2         | 5.56%   |
| Zaporizhzhia  | 1         | 2.78%   |
| Uppsala       | 1         | 2.78%   |
| Tuusula       | 1         | 2.78%   |
| Stadtilm      | 1         | 2.78%   |
| Sofia         | 1         | 2.78%   |
| Shimanovsk    | 1         | 2.78%   |
| San Diego     | 1         | 2.78%   |
| Rothwell      | 1         | 2.78%   |
| Parla         | 1         | 2.78%   |
| Paris         | 1         | 2.78%   |
| Moscow        | 1         | 2.78%   |
| Mangalore     | 1         | 2.78%   |
| Los Angeles   | 1         | 2.78%   |
| Liverpool     | 1         | 2.78%   |
| Lille         | 1         | 2.78%   |
| Lawrence      | 1         | 2.78%   |
| Land O' Lakes | 1         | 2.78%   |
| Lahore        | 1         | 2.78%   |
| Kitimat       | 1         | 2.78%   |
| Kennewick     | 1         | 2.78%   |
| Johannesburg  | 1         | 2.78%   |
| Guglingen     | 1         | 2.78%   |
| Guanare       | 1         | 2.78%   |
| Groningen     | 1         | 2.78%   |
| Frankenthal   | 1         | 2.78%   |
| Essen         | 1         | 2.78%   |
| Castelginest  | 1         | 2.78%   |
| Bloomington   | 1         | 2.78%   |
| Berlin        | 1         | 2.78%   |
| Barcelona     | 1         | 2.78%   |
| Austin        | 1         | 2.78%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 7         | 13     | 13.21%  |
| WDC                         | 6         | 6      | 11.32%  |
| Samsung Electronics         | 6         | 9      | 11.32%  |
| Unknown                     | 3         | 3      | 5.66%   |
| Kingston                    | 3         | 3      | 5.66%   |
| Toshiba                     | 2         | 2      | 3.77%   |
| SK hynix                    | 2         | 2      | 3.77%   |
| LITEONIT                    | 2         | 2      | 3.77%   |
| Intel                       | 2         | 2      | 3.77%   |
| Dell                        | 2         | 3      | 3.77%   |
| Crucial                     | 2         | 4      | 3.77%   |
| Union Memory                | 1         | 1      | 1.89%   |
| Transcend                   | 1         | 1      | 1.89%   |
| SSSTC                       | 1         | 1      | 1.89%   |
| Plextor                     | 1         | 1      | 1.89%   |
| Netac                       | 1         | 1      | 1.89%   |
| Micron Technology           | 1         | 1      | 1.89%   |
| LITEON                      | 1         | 1      | 1.89%   |
| Kingston Technology Company | 1         | 1      | 1.89%   |
| Hitachi                     | 1         | 1      | 1.89%   |
| HGST                        | 1         | 1      | 1.89%   |
| Hewlett-Packard             | 1         | 8      | 1.89%   |
| EMTEC                       | 1         | 2      | 1.89%   |
| DELLBOSS                    | 1         | 1      | 1.89%   |
| China                       | 1         | 1      | 1.89%   |
| ASMT                        | 1         | 2      | 1.89%   |
| A-DATA Technology           | 1         | 1      | 1.89%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| WDC WD10SPZX-24Z10 1TB                      | 2         | 3.45%   |
| WDC WD5000LPCX-21VHAT0 500GB                | 1         | 1.72%   |
| WDC WD10SPZX-60Z10T1 1TB                    | 1         | 1.72%   |
| WDC WD10EZEX-08WN4A0 1TB                    | 1         | 1.72%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB        | 1         | 1.72%   |
| Unknown SD64G  64GB                         | 1         | 1.72%   |
| Unknown SD/MMC/MS PRO 8GB                   | 1         | 1.72%   |
| Unknown EC2QT  64GB                         | 1         | 1.72%   |
| Union Memory UMIS RPITJ512VME2OWD 512GB     | 1         | 1.72%   |
| Transcend TS256GMTE220S 256GB               | 1         | 1.72%   |
| Toshiba MK6475GSX 640GB                     | 1         | 1.72%   |
| Toshiba DT01ACA100 1TB                      | 1         | 1.72%   |
| SSSTC CL1-3D256 256GB                       | 1         | 1.72%   |
| SK hynix SH920 2.5 7MM 256GB SSD            | 1         | 1.72%   |
| SK hynix NVMe SSD Drive 256GB               | 1         | 1.72%   |
| Seagate ST4000NM000A 00MX141 00MX141LEN 4TB | 1         | 1.72%   |
| Seagate ST4000NC001-1FS168 4TB              | 1         | 1.72%   |
| Seagate ST4000DM000-1F2168 4TB              | 1         | 1.72%   |
| Seagate ST31000528AS 1TB                    | 1         | 1.72%   |
| Seagate ST250LM004 HN-M250MBB 250GB         | 1         | 1.72%   |
| Seagate ST2000NM012A-2MP130 2TB             | 1         | 1.72%   |
| Seagate ST2000LM015-2E8174 2TB              | 1         | 1.72%   |
| Seagate ST2000DM001-1ER164 2TB              | 1         | 1.72%   |
| Seagate ST1000NM0033-9ZM173 1TB             | 1         | 1.72%   |
| Seagate ST10000NM0478-2H7100 10TB           | 1         | 1.72%   |
| Samsung SSD PM810 FDE 2.5 256GB             | 1         | 1.72%   |
| Samsung SSD 970 EVO Plus 250GB              | 1         | 1.72%   |
| Samsung PSSD T7 Touch 1TB                   | 1         | 1.72%   |
| Samsung MZVLQ512HALU-00000 512GB            | 1         | 1.72%   |
| Samsung MZVLQ128HBHQ-000H1 128GB            | 1         | 1.72%   |
| Samsung MZVL22T0HBLB-00BL7 2TB              | 1         | 1.72%   |
| Samsung MZQL23T8HCLS-00A07 3.8TB            | 1         | 1.72%   |
| Plextor PX-128S3C 128GB SSD                 | 1         | 1.72%   |
| Netac SSD 512GB                             | 1         | 1.72%   |
| Micron MTFDDAK256MAM-1K12 256GB SSD         | 1         | 1.72%   |
| LITEONIT LSS-16L6G-HP 16GB SSD              | 1         | 1.72%   |
| LITEONIT LGT-128M6G 128GB SSD               | 1         | 1.72%   |
| LITEON CV1-8B256-HP 256GB SSD               | 1         | 1.72%   |
| Kingston Company A2000 NVMe SSD 500GB       | 1         | 1.72%   |
| Kingston SV300S37A240G 240GB SSD            | 1         | 1.72%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| Seagate         | 7         | 13     | 35%     |
| WDC             | 5         | 5      | 25%     |
| Toshiba         | 2         | 2      | 10%     |
| Unknown         | 1         | 1      | 5%      |
| Hitachi         | 1         | 1      | 5%      |
| HGST            | 1         | 1      | 5%      |
| Hewlett-Packard | 1         | 8      | 5%      |
| DELLBOSS        | 1         | 1      | 5%      |
| ASMT            | 1         | 2      | 5%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 3         | 3      | 16.67%  |
| Samsung Electronics | 2         | 2      | 11.11%  |
| LITEONIT            | 2         | 2      | 11.11%  |
| Intel               | 2         | 2      | 11.11%  |
| SK hynix            | 1         | 1      | 5.56%   |
| Plextor             | 1         | 1      | 5.56%   |
| Netac               | 1         | 1      | 5.56%   |
| Micron Technology   | 1         | 1      | 5.56%   |
| LITEON              | 1         | 1      | 5.56%   |
| Dell                | 1         | 2      | 5.56%   |
| Crucial             | 1         | 2      | 5.56%   |
| China               | 1         | 1      | 5.56%   |
| A-DATA Technology   | 1         | 1      | 5.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 19        | 34     | 36.54%  |
| SSD     | 17        | 20     | 32.69%  |
| NVMe    | 13        | 16     | 25%     |
| MMC     | 2         | 2      | 3.85%   |
| Unknown | 1         | 2      | 1.92%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 28        | 50     | 60.87%  |
| NVMe | 13        | 16     | 28.26%  |
| SAS  | 3         | 6      | 6.52%   |
| MMC  | 2         | 2      | 4.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 19        | 22     | 50%     |
| 0.51-1.0   | 10        | 11     | 26.32%  |
| 3.01-4.0   | 3         | 3      | 7.89%   |
| 1.01-2.0   | 3         | 7      | 7.89%   |
| 4.01-10.0  | 2         | 9      | 5.26%   |
| 10.01-20.0 | 1         | 2      | 2.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 12        | 33.33%  |
| More than 3000 | 5         | 13.89%  |
| 251-500        | 5         | 13.89%  |
| 501-1000       | 3         | 8.33%   |
| 51-100         | 3         | 8.33%   |
| 21-50          | 2         | 5.56%   |
| 1001-2000      | 2         | 5.56%   |
| 1-20           | 2         | 5.56%   |
| 2001-3000      | 1         | 2.78%   |
| Unknown        | 1         | 2.78%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 15        | 40.54%  |
| 21-50          | 8         | 21.62%  |
| 51-100         | 5         | 13.51%  |
| 251-500        | 3         | 8.11%   |
| More than 3000 | 2         | 5.41%   |
| 101-250        | 2         | 5.41%   |
| 501-1000       | 1         | 2.7%    |
| Unknown        | 1         | 2.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| SK hynix SH920 2.5 7MM 256GB SSD | 1         | 1      | 50%     |
| LITEONIT LSS-16L6G-HP 16GB SSD   | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


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

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 20        | 42     | 51.28%  |
| Detected | 17        | 30     | 43.59%  |
| Malfunc  | 2         | 2      | 5.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 25        | 53.19%  |
| AMD                            | 6         | 12.77%  |
| Samsung Electronics            | 5         | 10.64%  |
| Union Memory (Shenzhen)        | 2         | 4.26%   |
| Solid State Storage Technology | 1         | 2.13%   |
| SK hynix                       | 1         | 2.13%   |
| Silicon Motion                 | 1         | 2.13%   |
| SanDisk                        | 1         | 2.13%   |
| Micron/Crucial Technology      | 1         | 2.13%   |
| Marvell Technology Group       | 1         | 2.13%   |
| Kingston Technology Company    | 1         | 2.13%   |
| Hewlett-Packard                | 1         | 2.13%   |
| Broadcom / LSI                 | 1         | 2.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 5         | 10%     |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 6%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 6%      |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 2         | 4%      |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 4%      |
| Samsung NVMe SSD Controller 980                                                | 2         | 4%      |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 4%      |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 4%      |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 4%      |
| Solid State Storage Non-Volatile memory controller                             | 1         | 2%      |
| SK hynix BC511                                                                 | 1         | 2%      |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 2%      |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 2%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 2%      |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 1         | 2%      |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller          | 1         | 2%      |
| Kingston Company A2000 NVMe SSD                                                | 1         | 2%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 1         | 2%      |
| Intel SATA Controller [RAID mode]                                              | 1         | 2%      |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 2%      |
| Intel NVMe Datacenter SSD [3DNAND, Beta Rock Controller]                       | 1         | 2%      |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 2%      |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 2%      |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 2%      |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                  | 1         | 2%      |
| Intel C620 Series Chipset Family IDE Redirection                               | 1         | 2%      |
| Intel C600/X79 series chipset SATA RAID Controller                             | 1         | 2%      |
| Intel C600/X79 series chipset 4-Port SATA IDE Controller                       | 1         | 2%      |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 2%      |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 2%      |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 1         | 2%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 2%      |
| HP Smart Array Gen8 Controllers                                                | 1         | 2%      |
| Broadcom / LSI MegaRAID Tri-Mode SAS3408                                       | 1         | 2%      |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 1         | 2%      |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 1         | 2%      |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 27        | 56.25%  |
| NVMe | 14        | 29.17%  |
| RAID | 4         | 8.33%   |
| IDE  | 3         | 6.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 26        | 72.22%  |
| AMD    | 7         | 19.44%  |
| ARM    | 3         | 8.33%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 8.33%   |
| ARM Processor                                 | 3         | 8.33%   |
| Intel Xeon W-1350 @ 3.30GHz                   | 1         | 2.78%   |
| Intel Xeon Gold 5220R CPU @ 2.20GHz           | 1         | 2.78%   |
| Intel Xeon CPU X5550 @ 2.67GHz                | 1         | 2.78%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GHz            | 1         | 2.78%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 2.78%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 2.78%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1         | 2.78%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 2.78%   |
| Intel Core i7-3840QM CPU @ 2.80GHz            | 1         | 2.78%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 2.78%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 2.78%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 2.78%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 1         | 2.78%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 2.78%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 2.78%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 2.78%   |
| Intel Core i5-10400F CPU @ 2.90GHz            | 1         | 2.78%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 1         | 2.78%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 1         | 2.78%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 1         | 2.78%   |
| Intel Celeron 2955U @ 1.40GHz                 | 1         | 2.78%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 1         | 2.78%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz        | 1         | 2.78%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 1         | 2.78%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 1         | 2.78%   |
| AMD Ryzen 3 3250U with Radeon Graphics        | 1         | 2.78%   |
| AMD FX-8350 Eight-Core Processor              | 1         | 2.78%   |
| AMD EPYC 7402P 24-Core Processor              | 1         | 2.78%   |
| AMD A9-9420e RADEON R5, 5 COMPUTE CORES 2C+3G | 1         | 2.78%   |
| AMD A6-9220e RADEON R4, 5 COMPUTE CORES 2C+3G | 1         | 2.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 9         | 25%     |
| Other                   | 5         | 13.89%  |
| Intel Core i7           | 5         | 13.89%  |
| Intel Xeon              | 3         | 8.33%   |
| Intel Core i3           | 3         | 8.33%   |
| Intel Xeon Gold         | 1         | 2.78%   |
| Intel Pentium Dual-Core | 1         | 2.78%   |
| Intel Pentium           | 1         | 2.78%   |
| Intel Celeron           | 1         | 2.78%   |
| Intel Atom              | 1         | 2.78%   |
| AMD Ryzen 7             | 1         | 2.78%   |
| AMD Ryzen 5             | 1         | 2.78%   |
| AMD Ryzen 3             | 1         | 2.78%   |
| AMD FX                  | 1         | 2.78%   |
| AMD EPYC                | 1         | 2.78%   |
| AMD A6                  | 1         | 2.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 12        | 33.33%  |
| 2       | 12        | 33.33%  |
| 6       | 4         | 11.11%  |
| Unknown | 2         | 5.56%   |
| 80      | 1         | 2.78%   |
| 48      | 1         | 2.78%   |
| 24      | 1         | 2.78%   |
| 12      | 1         | 2.78%   |
| 8       | 1         | 2.78%   |
| 1       | 1         | 2.78%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 32        | 88.89%  |
| 2       | 2         | 5.56%   |
| Unknown | 2         | 5.56%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 28        | 77.78%  |
| 1       | 6         | 16.67%  |
| Unknown | 2         | 5.56%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 33        | 91.67%  |
| Unknown        | 3         | 8.33%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 6         | 16.67%  |
| 0x806ec    | 4         | 11.11%  |
| 0x306a9    | 4         | 11.11%  |
| 0x40651    | 3         | 8.33%   |
| 0xa0671    | 2         | 5.56%   |
| 0xa0655    | 1         | 2.78%   |
| 0xa0652    | 1         | 2.78%   |
| 0x906ea    | 1         | 2.78%   |
| 0x906e9    | 1         | 2.78%   |
| 0x50657    | 1         | 2.78%   |
| 0x406e3    | 1         | 2.78%   |
| 0x306c3    | 1         | 2.78%   |
| 0x30678    | 1         | 2.78%   |
| 0x106ca    | 1         | 2.78%   |
| 0x106a5    | 1         | 2.78%   |
| 0x1067a    | 1         | 2.78%   |
| 0x08608103 | 1         | 2.78%   |
| 0x08108109 | 1         | 2.78%   |
| 0x0810100b | 1         | 2.78%   |
| 0x06006705 | 1         | 2.78%   |
| 0x06006704 | 1         | 2.78%   |
| 0x06000852 | 1         | 2.78%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 7         | 19.44%  |
| IvyBridge   | 4         | 11.11%  |
| Haswell     | 4         | 11.11%  |
| Unknown     | 4         | 11.11%  |
| Skylake     | 2         | 5.56%   |
| Icelake     | 2         | 5.56%   |
| Excavator   | 2         | 5.56%   |
| CometLake   | 2         | 5.56%   |
| Zen+        | 1         | 2.78%   |
| Zen 2       | 1         | 2.78%   |
| Zen         | 1         | 2.78%   |
| Silvermont  | 1         | 2.78%   |
| SandyBridge | 1         | 2.78%   |
| Piledriver  | 1         | 2.78%   |
| Penryn      | 1         | 2.78%   |
| Nehalem     | 1         | 2.78%   |
| Bonnell     | 1         | 2.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 19        | 51.35%  |
| AMD                        | 8         | 21.62%  |
| Nvidia                     | 7         | 18.92%  |
| Matrox Electronics Systems | 2         | 5.41%   |
| ASPEED Technology          | 1         | 2.7%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                          | 3         | 8.11%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 3         | 8.11%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 2         | 5.41%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 2         | 5.41%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 1         | 2.7%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 2.7%    |
| Nvidia GP104 [GeForce GTX 1080]                                           | 1         | 2.7%    |
| Nvidia GM108M [GeForce 930M]                                              | 1         | 2.7%    |
| Nvidia GK107GLM [Quadro K1000M]                                           | 1         | 2.7%    |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                         | 1         | 2.7%    |
| Nvidia GA102GL [RTX A6000]                                                | 1         | 2.7%    |
| Matrox Electronics Systems MGA G200EH                                     | 1         | 2.7%    |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller  | 1         | 2.7%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 1         | 2.7%    |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 2.7%    |
| Intel RocketLake-S GT1 [UHD Graphics P750]                                | 1         | 2.7%    |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                 | 1         | 2.7%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 2.7%    |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 1         | 2.7%    |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                          | 1         | 2.7%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 1         | 2.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 1         | 2.7%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller   | 1         | 2.7%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller | 1         | 2.7%    |
| ASPEED Technology ASPEED Graphics Family                                  | 1         | 2.7%    |
| AMD RS780L [Radeon 3000]                                                  | 1         | 2.7%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 1         | 2.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1         | 2.7%    |
| AMD Lucienne                                                              | 1         | 2.7%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 1         | 2.7%    |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]       | 1         | 2.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 16        | 44.44%  |
| 1 x AMD        | 8         | 22.22%  |
| 1 x Nvidia     | 4         | 11.11%  |
| Intel + Nvidia | 3         | 8.33%   |
| Other          | 2         | 5.56%   |
| 1 x Matrox     | 2         | 5.56%   |
| 1 x ASPEED     | 1         | 2.78%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 27        | 75%     |
| Unknown     | 7         | 19.44%  |
| Proprietary | 2         | 5.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 66.67%  |
| 0.01-0.5   | 5         | 13.89%  |
| 1.01-2.0   | 4         | 11.11%  |
| 7.01-8.0   | 1         | 2.78%   |
| 32.01-64.0 | 1         | 2.78%   |
| 5.01-6.0   | 1         | 2.78%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 6         | 19.35%  |
| AU Optronics            | 6         | 19.35%  |
| Samsung Electronics     | 4         | 12.9%   |
| Dell                    | 2         | 6.45%   |
| BOE                     | 2         | 6.45%   |
| STD                     | 1         | 3.23%   |
| Sharp                   | 1         | 3.23%   |
| Seiki                   | 1         | 3.23%   |
| Philips                 | 1         | 3.23%   |
| PANDA                   | 1         | 3.23%   |
| Lenovo                  | 1         | 3.23%   |
| InfoVision              | 1         | 3.23%   |
| Goldstar                | 1         | 3.23%   |
| Chimei Innolux          | 1         | 3.23%   |
| Chi Mei Optoelectronics | 1         | 3.23%   |
| BenQ                    | 1         | 3.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| STD HDMI TV STD00C7 1920x1080 698x392mm 31.5-inch                        | 1         | 3.13%   |
| Sharp LC-32LB480U SHP3263 1920x1080 698x392mm 31.5-inch                  | 1         | 3.13%   |
| Seiki SC32HT04 SEK1366 1366x768 700x390mm 31.5-inch                      | 1         | 3.13%   |
| Samsung Electronics SyncMaster SAM021B 1400x1050 408x300mm 19.9-inch     | 1         | 3.13%   |
| Samsung Electronics S27H65x SAM0E1D 1920x1080 598x336mm 27.0-inch        | 1         | 3.13%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch     | 1         | 3.13%   |
| Samsung Electronics LCD Monitor SDC4142 3840x2160 294x165mm 13.3-inch    | 1         | 3.13%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch     | 1         | 3.13%   |
| Philips 19B PHL0879 1280x1024 376x301mm 19.0-inch                        | 1         | 3.13%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                  | 1         | 3.13%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch             | 1         | 3.13%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch              | 1         | 3.13%   |
| LG Display LCD Monitor LGD042D 1920x1080 294x165mm 13.3-inch             | 1         | 3.13%   |
| LG Display LCD Monitor LGD034A 1366x768 345x194mm 15.6-inch              | 1         | 3.13%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch              | 1         | 3.13%   |
| LG Display LCD Monitor LGD02A5 1366x768 345x194mm 15.6-inch              | 1         | 3.13%   |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                     | 1         | 3.13%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch             | 1         | 3.13%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch              | 1         | 3.13%   |
| Dell U2410 DELF015 1920x1200 518x324mm 24.1-inch                         | 1         | 3.13%   |
| Dell 1905FP DEL400C 1280x1024 376x301mm 19.0-inch                        | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 310x170mm 13.9-inch          | 1         | 3.13%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 1         | 3.13%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 1         | 3.13%   |
| BOE LCD Monitor BOE07A3 1920x1080 344x193mm 15.5-inch                    | 1         | 3.13%   |
| BenQ GL2450 BNQ78A5 1920x1080 531x298mm 24.0-inch                        | 1         | 3.13%   |
| AU Optronics LCD Monitor AUOF992 1920x1080 382x215mm 17.3-inch           | 1         | 3.13%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch           | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO623D 1920x1080 309x174mm 14.0-inch           | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO13ED 1920x1080 344x193mm 15.5-inch           | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch            | 1         | 3.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 16        | 50%     |
| 1366x768 (WXGA)   | 8         | 25%     |
| 3840x2160 (4K)    | 2         | 6.25%   |
| 1280x1024 (SXGA)  | 2         | 6.25%   |
| 2560x1440 (QHD)   | 1         | 3.13%   |
| 2560x1080         | 1         | 3.13%   |
| 1920x1200 (WUXGA) | 1         | 3.13%   |
| 1400x1050         | 1         | 3.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 11        | 34.38%  |
| 14     | 6         | 18.75%  |
| 31     | 3         | 9.38%   |
| 24     | 3         | 9.38%   |
| 19     | 2         | 6.25%   |
| 13     | 2         | 6.25%   |
| 34     | 1         | 3.13%   |
| 27     | 1         | 3.13%   |
| 20     | 1         | 3.13%   |
| 17     | 1         | 3.13%   |
| 11     | 1         | 3.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 17        | 53.13%  |
| 501-600     | 4         | 12.5%   |
| 601-700     | 3         | 9.38%   |
| 351-400     | 3         | 9.38%   |
| 201-300     | 3         | 9.38%   |
| 701-800     | 1         | 3.13%   |
| 401-500     | 1         | 3.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 24        | 82.76%  |
| 6/5   | 1         | 3.45%   |
| 5/4   | 1         | 3.45%   |
| 4/3   | 1         | 3.45%   |
| 21/9  | 1         | 3.45%   |
| 16/10 | 1         | 3.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 11        | 34.38%  |
| 81-90          | 6         | 18.75%  |
| 351-500        | 4         | 12.5%   |
| 151-200        | 3         | 9.38%   |
| 71-80          | 2         | 6.25%   |
| 201-250        | 2         | 6.25%   |
| 51-60          | 1         | 3.13%   |
| 301-350        | 1         | 3.13%   |
| 251-300        | 1         | 3.13%   |
| 121-130        | 1         | 3.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 12        | 38.71%  |
| 51-100        | 10        | 32.26%  |
| 101-120       | 5         | 16.13%  |
| More than 240 | 2         | 6.45%   |
| 1-50          | 1         | 3.23%   |
| 161-240       | 1         | 3.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 23        | 63.89%  |
| 0     | 8         | 22.22%  |
| 2     | 5         | 13.89%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 17        | 34%     |
| Realtek Semiconductor | 12        | 24%     |
| Qualcomm Atheros      | 6         | 12%     |
| Broadcom              | 4         | 8%      |
| Broadcom Limited      | 3         | 6%      |
| Standard Microsystems | 2         | 4%      |
| Mellanox Technologies | 2         | 4%      |
| TP-Link               | 1         | 2%      |
| Sierra Wireless       | 1         | 2%      |
| Samsung Electronics   | 1         | 2%      |
| MediaTek              | 1         | 2%      |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9         | 13.43%  |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 4.48%   |
| Standard Microsystems Ethernet controller                         | 2         | 2.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 2.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 2.99%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 2.99%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 2.99%   |
| Intel Wireless 7260                                               | 2         | 2.99%   |
| Intel I350 Gigabit Network Connection                             | 2         | 2.99%   |
| Intel I210 Gigabit Network Connection                             | 2         | 2.99%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 2.99%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.99%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.49%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 1.49%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.49%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.49%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 1.49%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 1.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.49%   |
| Mellanox MT28800 Family [ConnectX-5 Ex]                           | 1         | 1.49%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]             | 1         | 1.49%   |
| MediaTek TECNO F1                                                 | 1         | 1.49%   |
| Intel Wireless 8260                                               | 1         | 1.49%   |
| Intel Wireless 3165                                               | 1         | 1.49%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 1.49%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.49%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.49%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.49%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.49%   |
| Intel Ethernet Connection (3) I219-LM                             | 1         | 1.49%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.49%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 1.49%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.49%   |
| Intel Centrino Wireless-N 2230                                    | 1         | 1.49%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 1.49%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1         | 1.49%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 1.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 11        | 44%     |
| Qualcomm Atheros      | 6         | 24%     |
| Realtek Semiconductor | 5         | 20%     |
| Sierra Wireless       | 1         | 4%      |
| Broadcom Limited      | 1         | 4%      |
| Broadcom              | 1         | 4%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Comet Lake PCH-LP CNVi WiFi                          | 3         | 12%     |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 2         | 8%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 2         | 8%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 2         | 8%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 2         | 8%      |
| Intel Wireless 7260                                        | 2         | 8%      |
| Sierra Wireless EM7345 4G LTE                              | 1         | 4%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 4%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1         | 4%      |
| Realtek RTL8191SEvB Wireless LAN Controller                | 1         | 4%      |
| Intel Wireless 8260                                        | 1         | 4%      |
| Intel Wireless 3165                                        | 1         | 4%      |
| Intel Wi-Fi 6 AX200                                        | 1         | 4%      |
| Intel Comet Lake PCH CNVi WiFi                             | 1         | 4%      |
| Intel Centrino Wireless-N 2230                             | 1         | 4%      |
| Intel Centrino Ultimate-N 6300                             | 1         | 4%      |
| Broadcom Limited BCM43224 802.11a/b/g/n                    | 1         | 4%      |
| Broadcom BCM43225 802.11b/g/n                              | 1         | 4%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 12        | 33.33%  |
| Realtek Semiconductor | 11        | 30.56%  |
| Broadcom              | 3         | 8.33%   |
| Standard Microsystems | 2         | 5.56%   |
| Mellanox Technologies | 2         | 5.56%   |
| Broadcom Limited      | 2         | 5.56%   |
| TP-Link               | 1         | 2.78%   |
| Samsung Electronics   | 1         | 2.78%   |
| Qualcomm Atheros      | 1         | 2.78%   |
| MediaTek              | 1         | 2.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller     | 9         | 21.43%  |
| Standard Microsystems Ethernet controller                             | 2         | 4.76%   |
| Intel I350 Gigabit Network Connection                                 | 2         | 4.76%   |
| Intel I210 Gigabit Network Connection                                 | 2         | 4.76%   |
| Intel Ethernet Connection (10) I219-V                                 | 2         | 4.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                 | 2         | 4.76%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]       | 1         | 2.38%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)           | 1         | 2.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                              | 1         | 2.38%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                 | 1         | 2.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                 | 1         | 2.38%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                         | 1         | 2.38%   |
| Mellanox MT28800 Family [ConnectX-5 Ex]                               | 1         | 2.38%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                 | 1         | 2.38%   |
| MediaTek TECNO F1                                                     | 1         | 2.38%   |
| Intel Ethernet Controller I225-V                                      | 1         | 2.38%   |
| Intel Ethernet Connection I219-LM                                     | 1         | 2.38%   |
| Intel Ethernet Connection I218-LM                                     | 1         | 2.38%   |
| Intel Ethernet Connection (6) I219-V                                  | 1         | 2.38%   |
| Intel Ethernet Connection (3) I219-LM                                 | 1         | 2.38%   |
| Intel Ethernet Connection (2) I219-LM                                 | 1         | 2.38%   |
| Intel Ethernet Connection (14) I219-LM                                | 1         | 2.38%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                  | 1         | 2.38%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                     | 1         | 2.38%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                      | 1         | 2.38%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                      | 1         | 2.38%   |
| Broadcom Limited NetXtreme II BCM5709 Gigabit Ethernet                | 1         | 2.38%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe               | 1         | 2.38%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller | 1         | 2.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 31        | 56.36%  |
| WiFi     | 24        | 43.64%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 19        | 52.78%  |
| WiFi     | 17        | 47.22%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 19        | 52.78%  |
| 1     | 10        | 27.78%  |
| 5     | 2         | 5.56%   |
| 4     | 2         | 5.56%   |
| 0     | 2         | 5.56%   |
| 6     | 1         | 2.78%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 28        | 77.78%  |
| Yes  | 8         | 22.22%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 10        | 43.48%  |
| Qualcomm Atheros Communications | 5         | 21.74%  |
| Realtek Semiconductor           | 4         | 17.39%  |
| Foxconn / Hon Hai               | 1         | 4.35%   |
| Cambridge Silicon Radio         | 1         | 4.35%   |
| Broadcom                        | 1         | 4.35%   |
| ASUSTek Computer                | 1         | 4.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 4         | 17.39%  |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 17.39%  |
| Intel Bluetooth wireless interface                  | 4         | 17.39%  |
| Intel AX201 Bluetooth                               | 4         | 17.39%  |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 4.35%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 4.35%   |
| Intel AX200 Bluetooth                               | 1         | 4.35%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 4.35%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 4.35%   |
| Broadcom HP Portable SoftSailing                    | 1         | 4.35%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 4.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Intel                | 23        | 54.76%  |
| AMD                  | 8         | 19.05%  |
| Nvidia               | 6         | 14.29%  |
| C-Media Electronics  | 2         | 4.76%   |
| Giga-Byte Technology | 1         | 2.38%   |
| Conrad Electronic SE | 1         | 2.38%   |
| Apple                | 1         | 2.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 7.69%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 5.77%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 5.77%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 5.77%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 5.77%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 3.85%   |
| AMD High Definition Audio Controller                                       | 2         | 3.85%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 3.85%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 1.92%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.92%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 1.92%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 1.92%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.92%   |
| Nvidia GA102 High Definition Audio Controller                              | 1         | 1.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.92%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.92%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 1.92%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 1.92%   |
| Intel Lewisburg MROM 0                                                     | 1         | 1.92%   |
| Intel Comet Lake PCH-V cAVS                                                | 1         | 1.92%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.92%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.92%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 1.92%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1         | 1.92%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.92%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 1.92%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.92%   |
| Giga-Byte Technology USB Audio                                             | 1         | 1.92%   |
| Conrad Electronic SE MIDI Cable UA0037                                     | 1         | 1.92%   |
| C-Media Electronics USB Audio Device                                       | 1         | 1.92%   |
| C-Media Electronics CM106 Like Sound Device                                | 1         | 1.92%   |
| Apple USB-C to 3.5mm Headphone Jack Adapter                                | 1         | 1.92%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.92%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                     | 1         | 1.92%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 1.92%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1         | 1.92%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1         | 1.92%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 6         | 23.08%  |
| SK hynix            | 4         | 15.38%  |
| Micron Technology   | 4         | 15.38%  |
| Kingston            | 4         | 15.38%  |
| Crucial             | 3         | 11.54%  |
| Unknown             | 2         | 7.69%   |
| Timetec             | 1         | 3.85%   |
| Hewlett-Packard     | 1         | 3.85%   |
| Elpida              | 1         | 3.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 8GB DIMM 1600MT/s                                      | 1         | 3.45%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                               | 1         | 3.45%   |
| Timetec RAM SD3-1600 8192MB SODIMM DDR3                                   | 1         | 3.45%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 3.45%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s                    | 1         | 3.45%   |
| SK hynix RAM HMAA8GR7CJR4N-XN 64GB DIMM DDR4 3200MT/s                     | 1         | 3.45%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s              | 1         | 3.45%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4096MB Row Of Chips LPDDR3 2133MT/s       | 1         | 3.45%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                               | 1         | 3.45%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 2133MT/s                       | 1         | 3.45%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 1         | 3.45%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s                  | 1         | 3.45%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 1         | 3.45%   |
| Samsung RAM M393A4G43AB3-CWE 32GB DIMM DDR4 3200MT/s                      | 1         | 3.45%   |
| Micron RAM 9ASF2G72AZ-3G2B1 16GB DIMM DDR4 3200MT/s                       | 1         | 3.45%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s                     | 1         | 3.45%   |
| Micron RAM 4ATF51264HZ-2G6E3 4GB SODIMM DDR4 2667MT/s                     | 1         | 3.45%   |
| Micron RAM 36ASF8G72PZ-3G2E1 64GB DIMM DDR4 3200MT/s                      | 1         | 3.45%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s                      | 1         | 3.45%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s                   | 1         | 3.45%   |
| Kingston RAM KHX2666C15S4/8G 8GB SODIMM DDR4 2667MT/s                     | 1         | 3.45%   |
| Kingston RAM 787878787878787878787878787878787878 2GB SODIMM DDR2 667MT/s | 1         | 3.45%   |
| Kingston RAM 272727272727272727272727272727272727 2GB SODIMM DDR2 667MT/s | 1         | 3.45%   |
| HP RAM 712384-081 32GB DIMM DDR3 1866MT/s                                 | 1         | 3.45%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s                     | 1         | 3.45%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s                    | 1         | 3.45%   |
| Crucial RAM CT8G4SFS824A.C8FDD1 8GB SODIMM DDR4 2400MT/s                  | 1         | 3.45%   |
| Crucial RAM CT8G4DFRA32A.C4FE 8192MB DIMM DDR4 3200MT/s                   | 1         | 3.45%   |
| Crucial RAM CT102464BA160B.C16 8192MB DIMM DDR3 1600MT/s                  | 1         | 3.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 12        | 54.55%  |
| DDR3    | 6         | 27.27%  |
| LPDDR3  | 2         | 9.09%   |
| DDR2    | 1         | 4.55%   |
| Unknown | 1         | 4.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 10        | 45.45%  |
| DIMM         | 9         | 40.91%  |
| Row Of Chips | 3         | 13.64%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 9         | 39.13%  |
| 4096  | 7         | 30.43%  |
| 65536 | 2         | 8.7%    |
| 32768 | 2         | 8.7%    |
| 16384 | 2         | 8.7%    |
| 2048  | 1         | 4.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 8         | 32%     |
| 1600  | 6         | 24%     |
| 2667  | 3         | 12%     |
| 2133  | 2         | 8%      |
| 1866  | 2         | 8%      |
| 3600  | 1         | 4%      |
| 2400  | 1         | 4%      |
| 1333  | 1         | 4%      |
| 667   | 1         | 4%      |

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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 8         | 33.33%  |
| IMC Networks                           | 5         | 20.83%  |
| Acer                                   | 3         | 12.5%   |
| Suyin                                  | 2         | 8.33%   |
| Realtek Semiconductor                  | 1         | 4.17%   |
| Microdia                               | 1         | 4.17%   |
| Luxvisions Innotech Limited            | 1         | 4.17%   |
| Logitech                               | 1         | 4.17%   |
| Creative Technology                    | 1         | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 4.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                  | 4         | 16%     |
| Chicony Integrated HP HD Webcam                                 | 2         | 8%      |
| Chicony HP Truevision HD                                        | 2         | 8%      |
| Suyin HD WebCam                                                 | 1         | 4%      |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)     | 1         | 4%      |
| Realtek EasyCamera                                              | 1         | 4%      |
| Microdia Integrated_Webcam_HD                                   | 1         | 4%      |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 1         | 4%      |
| Logitech Webcam C120                                            | 1         | 4%      |
| IMC Networks USB2.0 HD IR UVC WebCam                            | 1         | 4%      |
| Creative Live! Cam Chat HD [VF0700]                             | 1         | 4%      |
| Chicony TOSHIBA Web Camera - HD                                 | 1         | 4%      |
| Chicony Lenovo EasyCamera                                       | 1         | 4%      |
| Chicony EasyCamera                                              | 1         | 4%      |
| Chicony 8M Camera                                               | 1         | 4%      |
| Chicony 720p HD Camera                                          | 1         | 4%      |
| Cheng Uei Precision Industry (Foxlink) HP True Vision HD Camera | 1         | 4%      |
| Acer USB Camera                                                 | 1         | 4%      |
| Acer Lenovo EasyCamera                                          | 1         | 4%      |
| Acer Integrated Camera                                          | 1         | 4%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 5         | 83.33%  |
| Elan Microelectronics | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Validity Sensors VFS491                      | 2         | 33.33%  |
| Validity Sensors VFS5011 Fingerprint Reader  | 1         | 16.67%  |
| Validity Sensors VFS 5011 fingerprint sensor | 1         | 16.67%  |
| Validity Sensors Fingerprint scanner         | 1         | 16.67%  |
| Elan ELAN:ARM-M4                             | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 21        | 58.33%  |
| 1     | 11        | 30.56%  |
| 2     | 2         | 5.56%   |
| 7     | 1         | 2.78%   |
| 5     | 1         | 2.78%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 6         | 26.09%  |
| Graphics card         | 5         | 21.74%  |
| Sound                 | 2         | 8.7%    |
| Net/wireless          | 2         | 8.7%    |
| Net/ethernet          | 2         | 8.7%    |
| Unassigned class      | 1         | 4.35%   |
| Storage/ide           | 1         | 4.35%   |
| Multimedia controller | 1         | 4.35%   |
| Chipcard              | 1         | 4.35%   |
| Camera                | 1         | 4.35%   |
| Bluetooth             | 1         | 4.35%   |

