AlmaLinux - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for AlmaLinux.

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

Total: 45

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Dell      | Inspiron 5555               | [7c07dbad40](https://linux-hardware.org/?probe=7c07dbad40) | Jun 29, 2023 |
| Maibenben | MaiBook X series            | [5ca7ad5fb0](https://linux-hardware.org/?probe=5ca7ad5fb0) | Jun 07, 2023 |
| Dell      | Inspiron 5555               | [e14ab40d68](https://linux-hardware.org/?probe=e14ab40d68) | Jun 03, 2023 |
| MSI       | GL75 9SE                    | [7fd4d531c9](https://linux-hardware.org/?probe=7fd4d531c9) | May 18, 2023 |
| HP        | ZBook 17 G2                 | [fc2425ffde](https://linux-hardware.org/?probe=fc2425ffde) | Apr 08, 2023 |
| TUXEDO    | Aura 15 Gen1                | [1584039ca8](https://linux-hardware.org/?probe=1584039ca8) | Mar 24, 2023 |
| TUXEDO    | Aura 15 Gen1                | [a8e6ba1268](https://linux-hardware.org/?probe=a8e6ba1268) | Mar 24, 2023 |
| Lenovo    | ThinkPad P1 Gen 4i 20Y30... | [97af59e728](https://linux-hardware.org/?probe=97af59e728) | Mar 18, 2023 |
| Google    | Kefka                       | [8142fbc91a](https://linux-hardware.org/?probe=8142fbc91a) | Feb 24, 2023 |
| Dell      | Inspiron 3501               | [725c2a80f8](https://linux-hardware.org/?probe=725c2a80f8) | Jan 29, 2023 |
| Lenovo    | V14-ARE 82DQ                | [9fbcd4b714](https://linux-hardware.org/?probe=9fbcd4b714) | Jan 28, 2023 |
| HP        | Falco                       | [a52a8f8f4e](https://linux-hardware.org/?probe=a52a8f8f4e) | Jan 14, 2023 |
| Dell      | Latitude E6510              | [dab9cdc1be](https://linux-hardware.org/?probe=dab9cdc1be) | Jan 11, 2023 |
| HP        | Falco                       | [61ce7c6739](https://linux-hardware.org/?probe=61ce7c6739) | Dec 21, 2022 |
| HP        | EliteBook 850 G8 Noteboo... | [95d47d14cb](https://linux-hardware.org/?probe=95d47d14cb) | Dec 09, 2022 |
| Lenovo    | B50-30 20382                | [3706f368de](https://linux-hardware.org/?probe=3706f368de) | Nov 24, 2022 |
| Lenovo    | Legion Y530-15ICH 81FV      | [832ebcb956](https://linux-hardware.org/?probe=832ebcb956) | Nov 03, 2022 |
| Toshiba   | Satellite L50-C             | [b3e0ff9849](https://linux-hardware.org/?probe=b3e0ff9849) | Nov 01, 2022 |
| Acer      | TMP453-MG                   | [4d36d13ea9](https://linux-hardware.org/?probe=4d36d13ea9) | Oct 01, 2022 |
| Acer      | TravelMate 5735Z            | [b920fce554](https://linux-hardware.org/?probe=b920fce554) | Sep 17, 2022 |
| HP        | Falco                       | [5fa86b77d6](https://linux-hardware.org/?probe=5fa86b77d6) | Sep 17, 2022 |
| HP        | Laptop 15-ef1xxx            | [c01403937e](https://linux-hardware.org/?probe=c01403937e) | Sep 08, 2022 |
| HP        | ENVY dv6                    | [e7bc07047b](https://linux-hardware.org/?probe=e7bc07047b) | Aug 24, 2022 |
| HP        | Laptop 17-cp0xxx            | [82b34535ae](https://linux-hardware.org/?probe=82b34535ae) | Jul 06, 2022 |
| HP        | EliteBook 8470p             | [d6adb170de](https://linux-hardware.org/?probe=d6adb170de) | Jun 25, 2022 |
| Google    | Kohaku                      | [f43841c5e0](https://linux-hardware.org/?probe=f43841c5e0) | Jun 08, 2022 |
| Google    | Kohaku                      | [740a608274](https://linux-hardware.org/?probe=740a608274) | Jun 08, 2022 |
| Lenovo    | ThinkPad T440s 20ARS32P0... | [100b65a86d](https://linux-hardware.org/?probe=100b65a86d) | Jun 04, 2022 |
| Lenovo    | ThinkBook 13s-IWL 20R9      | [2fecc1fd76](https://linux-hardware.org/?probe=2fecc1fd76) | Apr 20, 2022 |
| Lenovo    | ThinkPad T14 Gen 1 20S1S... | [5ac68bc542](https://linux-hardware.org/?probe=5ac68bc542) | Mar 16, 2022 |
| Intel     | powered classmate PC        | [0585f5b715](https://linux-hardware.org/?probe=0585f5b715) | Dec 12, 2021 |
| Intel     | powered classmate PC        | [9416f348e4](https://linux-hardware.org/?probe=9416f348e4) | Dec 12, 2021 |
| Dell      | Inspiron 3185               | [53ac57fbea](https://linux-hardware.org/?probe=53ac57fbea) | Oct 26, 2021 |
| Dell      | Inspiron 3185               | [2c9cec7881](https://linux-hardware.org/?probe=2c9cec7881) | Oct 01, 2021 |
| Lenovo    | Yoga 2 13 20344             | [1a59499d3a](https://linux-hardware.org/?probe=1a59499d3a) | Sep 29, 2021 |
| Lenovo    | IdeaPad S145-15IWL 81MV     | [95a2b3a95d](https://linux-hardware.org/?probe=95a2b3a95d) | Aug 27, 2021 |
| HP        | EliteBook 8570w             | [37e72494a5](https://linux-hardware.org/?probe=37e72494a5) | Jul 29, 2021 |
| ASUSTek   | ASUS EXPERTBOOK B9450FA_... | [cdf0f4017c](https://linux-hardware.org/?probe=cdf0f4017c) | Jul 16, 2021 |
| Lenovo    | IdeaPad Slim 1-14AST-05 ... | [9044b57593](https://linux-hardware.org/?probe=9044b57593) | Jul 11, 2021 |
| Lenovo    | Legion 5 15IMH05H 81Y6      | [21a6135eda](https://linux-hardware.org/?probe=21a6135eda) | Jun 16, 2021 |
| Dell      | Inspiron 3185               | [84fa76eb2f](https://linux-hardware.org/?probe=84fa76eb2f) | Apr 20, 2021 |
| Dell      | Inspiron 3185               | [d49edb76fa](https://linux-hardware.org/?probe=d49edb76fa) | Apr 15, 2021 |
| Dell      | Inspiron 3185               | [15b8da5bc1](https://linux-hardware.org/?probe=15b8da5bc1) | Apr 14, 2021 |
| Lenovo    | IdeaPad Slim 1-14AST-05 ... | [f0791eb42d](https://linux-hardware.org/?probe=f0791eb42d) | Mar 30, 2021 |
| Lenovo    | IdeaPad 330-15ARR 81D2      | [8810309035](https://linux-hardware.org/?probe=8810309035) | Mar 24, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| AlmaLinux 9.1 | 8         | 24.24%  |
| AlmaLinux 9.0 | 6         | 18.18%  |
| AlmaLinux 8.6 | 5         | 15.15%  |
| AlmaLinux 8.4 | 5         | 15.15%  |
| AlmaLinux 8.3 | 3         | 9.09%   |
| AlmaLinux 9.2 | 2         | 6.06%   |
| AlmaLinux 8.5 | 2         | 6.06%   |
| AlmaLinux 8.8 | 1         | 3.03%   |
| AlmaLinux 8.7 | 1         | 3.03%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| AlmaLinux | 32        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 5.14.0-162.6.1.el9_1.x86_64  | 3         | 9.09%   |
| 5.14.0-70.22.1.el9_0.x86_64  | 2         | 6.06%   |
| 5.14.0-70.13.1.el9_0.x86_64  | 2         | 6.06%   |
| 5.14.0-284.11.1.el9_2.x86_64 | 2         | 6.06%   |
| 5.14.0-162.18.1.el9_1.x86_64 | 2         | 6.06%   |
| 5.14.0-162.12.1.el9_1.x86_64 | 2         | 6.06%   |
| 4.18.0-372.26.1.el8_6.x86_64 | 2         | 6.06%   |
| 4.18.0-305.7.1.el8_4.x86_64  | 2         | 6.06%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 2         | 6.06%   |
| 5.4.175-1.el8.elrepo.x86_64  | 1         | 3.03%   |
| 5.14.0-70.26.1.el9_0.x86_64  | 1         | 3.03%   |
| 5.14.0-70.17.1.el9_0.x86_64  | 1         | 3.03%   |
| 5.14.0-162.22.2.el9_1.x86_64 | 1         | 3.03%   |
| 4.18.0-477.13.1.el8_8.x86_64 | 1         | 3.03%   |
| 4.18.0-425.3.1.el8.x86_64    | 1         | 3.03%   |
| 4.18.0-372.9.1.el8.x86_64    | 1         | 3.03%   |
| 4.18.0-372.19.1.el8_6.x86_64 | 1         | 3.03%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 1         | 3.03%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 1         | 3.03%   |
| 4.18.0-305.el8.x86_64        | 1         | 3.03%   |
| 4.18.0-305.3.1.el8_4.x86_64  | 1         | 3.03%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 1         | 3.03%   |
| 4.18.0-240.22.1.el8_3.x86_64 | 1         | 3.03%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.0  | 16        | 50%     |
| 4.18.0  | 15        | 46.88%  |
| 5.4.175 | 1         | 3.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 16        | 50%     |
| 4.18    | 15        | 46.88%  |
| 5.4     | 1         | 3.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 32        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 23        | 71.88%  |
| MATE            | 3         | 9.38%   |
| KDE5            | 2         | 6.25%   |
| XFCE            | 1         | 3.13%   |
| GNOME Flashback | 1         | 3.13%   |
| GNOME Classic   | 1         | 3.13%   |
| Unknown         | 1         | 3.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 21        | 65.63%  |
| X11     | 10        | 31.25%  |
| Tty     | 1         | 3.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 15        | 46.88%  |
| GDM     | 12        | 37.5%   |
| LightDM | 3         | 9.38%   |
| SDDM    | 2         | 6.25%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 19        | 59.38%  |
| de_DE | 4         | 12.5%   |
| fr_FR | 3         | 9.38%   |
| ru_RU | 1         | 3.13%   |
| pl_PL | 1         | 3.13%   |
| es_VE | 1         | 3.13%   |
| es_ES | 1         | 3.13%   |
| en_CA | 1         | 3.13%   |
| C     | 1         | 3.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 23        | 71.88%  |
| BIOS | 9         | 28.13%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Xfs  | 25        | 78.13%  |
| Ext4 | 7         | 21.88%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 17        | 53.13%  |
| Unknown | 13        | 40.63%  |
| MBR     | 2         | 6.25%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 27        | 84.38%  |
| Yes       | 5         | 15.63%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 26        | 81.25%  |
| Yes       | 6         | 18.75%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 11        | 34.38%  |
| Hewlett-Packard  | 8         | 25%     |
| Dell             | 3         | 9.38%   |
| Google           | 2         | 6.25%   |
| Acer             | 2         | 6.25%   |
| TUXEDO           | 1         | 3.13%   |
| Toshiba          | 1         | 3.13%   |
| MSI              | 1         | 3.13%   |
| Maibenben        | 1         | 3.13%   |
| Intel            | 1         | 3.13%   |
| ASUSTek Computer | 1         | 3.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| TUXEDO Aura 15 Gen1                  | 1         | 3.13%   |
| Toshiba Satellite L50-C              | 1         | 3.13%   |
| MSI GL75 9SE                         | 1         | 3.13%   |
| Maibenben MaiBook X series           | 1         | 3.13%   |
| Lenovo Yoga 2 13 20344               | 1         | 3.13%   |
| Lenovo V14-ARE 82DQ                  | 1         | 3.13%   |
| Lenovo ThinkPad T440s 20ARS32P00     | 1         | 3.13%   |
| Lenovo ThinkPad T14 Gen 1 20S1S39Q00 | 1         | 3.13%   |
| Lenovo ThinkPad P1 Gen 4i 20Y3003XUS | 1         | 3.13%   |
| Lenovo Legion Y530-15ICH 81FV        | 1         | 3.13%   |
| Lenovo Legion 5 15IMH05H 81Y6        | 1         | 3.13%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS  | 1         | 3.13%   |
| Lenovo IdeaPad S145-15IWL 81MV       | 1         | 3.13%   |
| Lenovo IdeaPad 330-15ARR 81D2        | 1         | 3.13%   |
| Lenovo B50-30 20382                  | 1         | 3.13%   |
| Intel powered classmate PC           | 1         | 3.13%   |
| HP ZBook 17 G2                       | 1         | 3.13%   |
| HP Laptop 17-cp0xxx                  | 1         | 3.13%   |
| HP Laptop 15-ef1xxx                  | 1         | 3.13%   |
| HP Falco                             | 1         | 3.13%   |
| HP ENVY dv6                          | 1         | 3.13%   |
| HP EliteBook 8570w                   | 1         | 3.13%   |
| HP EliteBook 850 G8 Notebook PC      | 1         | 3.13%   |
| HP EliteBook 8470p                   | 1         | 3.13%   |
| Google Kohaku                        | 1         | 3.13%   |
| Google Kefka                         | 1         | 3.13%   |
| Dell Latitude E6510                  | 1         | 3.13%   |
| Dell Inspiron 5555                   | 1         | 3.13%   |
| Dell Inspiron 3185                   | 1         | 3.13%   |
| ASUS ASUS EXPERTBOOK B9450FA_B9450FA | 1         | 3.13%   |
| Acer TravelMate 5735Z                | 1         | 3.13%   |
| Acer TMP453-MG                       | 1         | 3.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 3         | 9.38%   |
| Lenovo IdeaPad    | 3         | 9.38%   |
| HP EliteBook      | 3         | 9.38%   |
| Lenovo Legion     | 2         | 6.25%   |
| HP Laptop         | 2         | 6.25%   |
| Dell Inspiron     | 2         | 6.25%   |
| TUXEDO Aura       | 1         | 3.13%   |
| Toshiba Satellite | 1         | 3.13%   |
| MSI GL75          | 1         | 3.13%   |
| Maibenben MaiBook | 1         | 3.13%   |
| Lenovo Yoga       | 1         | 3.13%   |
| Lenovo V14-ARE    | 1         | 3.13%   |
| Lenovo B50-30     | 1         | 3.13%   |
| Intel powered     | 1         | 3.13%   |
| HP ZBook          | 1         | 3.13%   |
| HP Falco          | 1         | 3.13%   |
| HP ENVY           | 1         | 3.13%   |
| Google Kohaku     | 1         | 3.13%   |
| Google Kefka      | 1         | 3.13%   |
| Dell Latitude     | 1         | 3.13%   |
| ASUS ASUS         | 1         | 3.13%   |
| Acer TravelMate   | 1         | 3.13%   |
| Acer TMP453-MG    | 1         | 3.13%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 6         | 18.75%  |
| 2019 | 4         | 12.5%   |
| 2014 | 4         | 12.5%   |
| 2022 | 3         | 9.38%   |
| 2018 | 3         | 9.38%   |
| 2012 | 3         | 9.38%   |
| 2021 | 2         | 6.25%   |
| 2015 | 2         | 6.25%   |
| 2011 | 2         | 6.25%   |
| 2010 | 2         | 6.25%   |
| 2013 | 1         | 3.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 32        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 26        | 81.25%  |
| Enabled  | 6         | 18.75%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 29        | 90.63%  |
| Yes  | 3         | 9.38%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 11        | 34.38%  |
| 8.01-16.0   | 9         | 28.13%  |
| 3.01-4.0    | 5         | 15.63%  |
| 16.01-24.0  | 4         | 12.5%   |
| 1.01-2.0    | 2         | 6.25%   |
| 64.01-256.0 | 1         | 3.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 10        | 29.41%  |
| 1.01-2.0  | 10        | 29.41%  |
| 3.01-4.0  | 6         | 17.65%  |
| 4.01-8.0  | 5         | 14.71%  |
| 0.51-1.0  | 2         | 5.88%   |
| 8.01-16.0 | 1         | 2.94%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 19        | 57.58%  |
| 2      | 11        | 33.33%  |
| 3      | 2         | 6.06%   |
| 0      | 1         | 3.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 24        | 75%     |
| Yes       | 8         | 25%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 68.75%  |
| No        | 10        | 31.25%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 90.63%  |
| No        | 3         | 9.38%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 9         | 28.13%  |
| Germany      | 5         | 15.63%  |
| France       | 4         | 12.5%   |
| Spain        | 2         | 6.25%   |
| Venezuela    | 1         | 3.13%   |
| Sweden       | 1         | 3.13%   |
| South Africa | 1         | 3.13%   |
| Russia       | 1         | 3.13%   |
| Puerto Rico  | 1         | 3.13%   |
| Poland       | 1         | 3.13%   |
| Pakistan     | 1         | 3.13%   |
| Netherlands  | 1         | 3.13%   |
| Mexico       | 1         | 3.13%   |
| India        | 1         | 3.13%   |
| Canada       | 1         | 3.13%   |
| Bulgaria     | 1         | 3.13%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Queens        | 2         | 6.25%   |
| Hamburg       | 2         | 6.25%   |
| Winterswijk   | 1         | 3.13%   |
| Wejherowo     | 1         | 3.13%   |
| Uppsala       | 1         | 3.13%   |
| Sofia         | 1         | 3.13%   |
| Saint-Brieuc  | 1         | 3.13%   |
| Regina        | 1         | 3.13%   |
| Redlands      | 1         | 3.13%   |
| Parla         | 1         | 3.13%   |
| Paris         | 1         | 3.13%   |
| Mangalore     | 1         | 3.13%   |
| Los Angeles   | 1         | 3.13%   |
| Lille         | 1         | 3.13%   |
| Land O' Lakes | 1         | 3.13%   |
| Lahore        | 1         | 3.13%   |
| Kennewick     | 1         | 3.13%   |
| Johannesburg  | 1         | 3.13%   |
| Irapuato      | 1         | 3.13%   |
| Guglingen     | 1         | 3.13%   |
| Guanare       | 1         | 3.13%   |
| Essen         | 1         | 3.13%   |
| Columbia      | 1         | 3.13%   |
| Castelginest  | 1         | 3.13%   |
| Beverly       | 1         | 3.13%   |
| Berlin        | 1         | 3.13%   |
| Beloyarskiy   | 1         | 3.13%   |
| Bayamón      | 1         | 3.13%   |
| Barcelona     | 1         | 3.13%   |
| Austin        | 1         | 3.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 7         | 7      | 15.91%  |
| Samsung Electronics         | 4         | 4      | 9.09%   |
| Kingston                    | 3         | 3      | 6.82%   |
| Intel                       | 3         | 3      | 6.82%   |
| Unknown                     | 2         | 3      | 4.55%   |
| SK hynix                    | 2         | 2      | 4.55%   |
| Sandisk                     | 2         | 2      | 4.55%   |
| Netac                       | 2         | 2      | 4.55%   |
| LITEONIT                    | 2         | 4      | 4.55%   |
| Union Memory                | 1         | 1      | 2.27%   |
| Transcend                   | 1         | 1      | 2.27%   |
| Toshiba                     | 1         | 1      | 2.27%   |
| SSSTC                       | 1         | 1      | 2.27%   |
| Seagate                     | 1         | 1      | 2.27%   |
| Plextor                     | 1         | 1      | 2.27%   |
| Micron Technology           | 1         | 1      | 2.27%   |
| KIOXIA                      | 1         | 1      | 2.27%   |
| Kingston Technology Company | 1         | 1      | 2.27%   |
| Hitachi                     | 1         | 1      | 2.27%   |
| HGST                        | 1         | 1      | 2.27%   |
| EMTEC                       | 1         | 2      | 2.27%   |
| Dell                        | 1         | 2      | 2.27%   |
| Crucial                     | 1         | 2      | 2.27%   |
| China                       | 1         | 1      | 2.27%   |
| ASMT                        | 1         | 2      | 2.27%   |
| A-DATA Technology           | 1         | 1      | 2.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| WDC WD10SPZX-24Z10 1TB                          | 2         | 4.44%   |
| WDC WD5000LPCX-21VHAT0 500GB                    | 1         | 2.22%   |
| WDC WD10SPZX-60Z10T1 1TB                        | 1         | 2.22%   |
| WDC WD10SPZX-60Z10T0 1TB                        | 1         | 2.22%   |
| WDC WD10JPVX-00JC3T0 1TB                        | 1         | 2.22%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB            | 1         | 2.22%   |
| Unknown SD/MMC/MS PRO 250GB                     | 1         | 2.22%   |
| Unknown MMC Card  16GB                          | 1         | 2.22%   |
| Union Memory UMIS RPITJ512VME2OWD 512GB         | 1         | 2.22%   |
| Transcend TS256GMTE220S 256GB                   | 1         | 2.22%   |
| Toshiba MK6475GSX 640GB                         | 1         | 2.22%   |
| SSSTC CL1-3D256 256GB                           | 1         | 2.22%   |
| SK hynix NVMe SSD Drive 256GB                   | 1         | 2.22%   |
| SK hynix BC511 NVMe 256GB                       | 1         | 2.22%   |
| Seagate ST250LM004 HN-M250MBB 250GB             | 1         | 2.22%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 500GB | 1         | 2.22%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD             | 1         | 2.22%   |
| Samsung SSD PM810 FDE 2.5 256GB                 | 1         | 2.22%   |
| Samsung MZVLQ512HALU-00000 512GB                | 1         | 2.22%   |
| Samsung MZVLQ128HBHQ-000H1 128GB                | 1         | 2.22%   |
| Samsung MZVL22T0HBLB-00BL7 2TB                  | 1         | 2.22%   |
| Plextor PX-128S3C 128GB SSD                     | 1         | 2.22%   |
| Netac SSD 128GB                                 | 1         | 2.22%   |
| Netac NVMe SSD Drive 2TB                        | 1         | 2.22%   |
| Micron MTFDDAK256MAM-1K12 256GB SSD             | 1         | 2.22%   |
| LITEONIT LSS-16L6G-HP 16GB SSD                  | 1         | 2.22%   |
| LITEONIT LGT-128M6G 128GB SSD                   | 1         | 2.22%   |
| KIOXIA KXG60ZNV512G 512GB                       | 1         | 2.22%   |
| Kingston Company A2000 NVMe SSD 250GB           | 1         | 2.22%   |
| Kingston SUV400S37120G 120GB SSD                | 1         | 2.22%   |
| Kingston SA400S37480G 480GB SSD                 | 1         | 2.22%   |
| Kingston SA400S37240G 240GB SSD                 | 1         | 2.22%   |
| Intel SSDSC2KF128G8L 128GB                      | 1         | 2.22%   |
| Intel SSDSC2BB800G4 800GB                       | 1         | 2.22%   |
| Intel SSDPEKNU512GZ 512GB                       | 1         | 2.22%   |
| Hitachi HTS545032B9A300 320GB                   | 1         | 2.22%   |
| HGST HTS541010A9E680 1TB                        | 1         | 2.22%   |
| EMTEC X200 256GB                                | 1         | 2.22%   |
| Dell WR202KD032G E70290F5 32GB                  | 1         | 2.22%   |
| Crucial CT240BX500SSD1 240GB                    | 1         | 2.22%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 6         | 6      | 50%     |
| Unknown | 1         | 2      | 8.33%   |
| Toshiba | 1         | 1      | 8.33%   |
| Seagate | 1         | 1      | 8.33%   |
| Hitachi | 1         | 1      | 8.33%   |
| HGST    | 1         | 1      | 8.33%   |
| ASMT    | 1         | 2      | 8.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 3         | 3      | 18.75%  |
| LITEONIT            | 2         | 4      | 12.5%   |
| Intel               | 2         | 2      | 12.5%   |
| SanDisk             | 1         | 1      | 6.25%   |
| Samsung Electronics | 1         | 1      | 6.25%   |
| Plextor             | 1         | 1      | 6.25%   |
| Netac               | 1         | 1      | 6.25%   |
| Micron Technology   | 1         | 1      | 6.25%   |
| Dell                | 1         | 2      | 6.25%   |
| Crucial             | 1         | 2      | 6.25%   |
| China               | 1         | 1      | 6.25%   |
| A-DATA Technology   | 1         | 1      | 6.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 15        | 20     | 35.71%  |
| NVMe    | 13        | 14     | 30.95%  |
| HDD     | 12        | 14     | 28.57%  |
| MMC     | 1         | 1      | 2.38%   |
| Unknown | 1         | 2      | 2.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 22        | 30     | 57.89%  |
| NVMe | 13        | 14     | 34.21%  |
| SAS  | 2         | 6      | 5.26%   |
| MMC  | 1         | 1      | 2.63%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 17        | 23     | 65.38%  |
| 0.51-1.0   | 9         | 11     | 34.62%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 12        | 36.36%  |
| 251-500    | 8         | 24.24%  |
| 1001-2000  | 3         | 9.09%   |
| 501-1000   | 3         | 9.09%   |
| 51-100     | 3         | 9.09%   |
| 21-50      | 2         | 6.06%   |
| 1-20       | 2         | 6.06%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 19        | 55.88%  |
| 21-50   | 9         | 26.47%  |
| 101-250 | 3         | 8.82%   |
| 51-100  | 2         | 5.88%   |
| 251-500 | 1         | 2.94%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| LITEONIT LSS-16L6G-HP 16GB SSD | 1         | 3      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| LITEONIT | 1         | 3      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1         | 3      | 100%    |

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
| Works    | 17        | 24     | 51.52%  |
| Detected | 15        | 24     | 45.45%  |
| Malfunc  | 1         | 3      | 3.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 20        | 50%     |
| AMD                            | 6         | 15%     |
| Samsung Electronics            | 3         | 7.5%    |
| Union Memory (Shenzhen)        | 2         | 5%      |
| SanDisk                        | 2         | 5%      |
| Toshiba America Info Systems   | 1         | 2.5%    |
| Solid State Storage Technology | 1         | 2.5%    |
| SK hynix                       | 1         | 2.5%    |
| Silicon Motion                 | 1         | 2.5%    |
| Netac Technology               | 1         | 2.5%    |
| Marvell Technology Group       | 1         | 2.5%    |
| Kingston Technology Company    | 1         | 2.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 6         | 15%     |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 7.5%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 7.5%    |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 2         | 5%      |
| Samsung NVMe SSD Controller 980                                                | 2         | 5%      |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 5%      |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 5%      |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 2.5%    |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 1         | 2.5%    |
| SK hynix BC511 NVMe SSD                                                        | 1         | 2.5%    |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 2.5%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 2.5%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 2.5%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 2.5%    |
| Netac Non-Volatile memory controller                                           | 1         | 2.5%    |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 1         | 2.5%    |
| Kingston Company A2000 NVMe SSD                                                | 1         | 2.5%    |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 2.5%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 1         | 2.5%    |
| Intel Non-Volatile memory controller                                           | 1         | 2.5%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 2.5%    |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 2.5%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 2.5%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 2.5%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 2.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 2.5%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 2.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 22        | 57.89%  |
| NVMe | 13        | 34.21%  |
| RAID | 3         | 7.89%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 23        | 71.88%  |
| AMD    | 9         | 28.13%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-10210U CPU @ 1.60GHz              | 3         | 9.38%   |
| Intel Xeon W-11855M CPU @ 3.20GHz               | 1         | 3.13%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz     | 1         | 3.13%   |
| Intel Pentium CPU N3540 @ 2.16GHz               | 1         | 3.13%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 1         | 3.13%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 1         | 3.13%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz              | 1         | 3.13%   |
| Intel Core i7-3840QM CPU @ 2.80GHz              | 1         | 3.13%   |
| Intel Core i7-3630QM CPU @ 2.40GHz              | 1         | 3.13%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 1         | 3.13%   |
| Intel Core i5-8300H CPU @ 2.30GHz               | 1         | 3.13%   |
| Intel Core i5-4300U CPU @ 1.90GHz               | 1         | 3.13%   |
| Intel Core i5-3360M CPU @ 2.80GHz               | 1         | 3.13%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 1         | 3.13%   |
| Intel Core i3-8145U CPU @ 2.10GHz               | 1         | 3.13%   |
| Intel Core i3-4010U CPU @ 1.70GHz               | 1         | 3.13%   |
| Intel Core i3 CPU M 370 @ 2.40GHz               | 1         | 3.13%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 1         | 3.13%   |
| Intel Celeron 2955U @ 1.40GHz                   | 1         | 3.13%   |
| Intel Atom CPU N455 @ 1.66GHz                   | 1         | 3.13%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz         | 1         | 3.13%   |
| AMD Ryzen 7 5800H with Radeon Graphics          | 1         | 3.13%   |
| AMD Ryzen 7 5700U with Radeon Graphics          | 1         | 3.13%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 1         | 3.13%   |
| AMD Ryzen 5 4500U with Radeon Graphics          | 1         | 3.13%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx   | 1         | 3.13%   |
| AMD Ryzen 3 3250U with Radeon Graphics          | 1         | 3.13%   |
| AMD A9-9420e RADEON R5, 5 COMPUTE CORES 2C+3G   | 1         | 3.13%   |
| AMD A6-9220e RADEON R4, 5 COMPUTE CORES 2C+3G   | 1         | 3.13%   |
| AMD A10-8700P Radeon R6, 10 Compute Cores 4C+6G | 1         | 3.13%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 7         | 21.88%  |
| Intel Core i7           | 6         | 18.75%  |
| Intel Core i3           | 3         | 9.38%   |
| AMD Ryzen 7             | 3         | 9.38%   |
| Other                   | 2         | 6.25%   |
| Intel Celeron           | 2         | 6.25%   |
| AMD Ryzen 5             | 2         | 6.25%   |
| Intel Xeon              | 1         | 3.13%   |
| Intel Pentium Dual-Core | 1         | 3.13%   |
| Intel Pentium           | 1         | 3.13%   |
| Intel Atom              | 1         | 3.13%   |
| AMD Ryzen 3             | 1         | 3.13%   |
| AMD A6                  | 1         | 3.13%   |
| AMD A10                 | 1         | 3.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 14        | 43.75%  |
| 4      | 10        | 31.25%  |
| 6      | 4         | 12.5%   |
| 8      | 3         | 9.38%   |
| 1      | 1         | 3.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 32        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 24        | 75%     |
| 1      | 8         | 25%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 32        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ec    | 4         | 12.5%   |
| 0x306a9    | 4         | 12.5%   |
| 0x40651    | 3         | 9.38%   |
| 0x08600106 | 2         | 6.25%   |
| 0xa0652    | 1         | 3.13%   |
| 0x906ed    | 1         | 3.13%   |
| 0x906ea    | 1         | 3.13%   |
| 0x806d1    | 1         | 3.13%   |
| 0x806c1    | 1         | 3.13%   |
| 0x406e3    | 1         | 3.13%   |
| 0x406c4    | 1         | 3.13%   |
| 0x306c3    | 1         | 3.13%   |
| 0x30678    | 1         | 3.13%   |
| 0x20655    | 1         | 3.13%   |
| 0x106ca    | 1         | 3.13%   |
| 0x1067a    | 1         | 3.13%   |
| 0x0a50000c | 1         | 3.13%   |
| 0x08608103 | 1         | 3.13%   |
| 0x08108109 | 1         | 3.13%   |
| 0x0810100b | 1         | 3.13%   |
| 0x06006705 | 1         | 3.13%   |
| 0x06006704 | 1         | 3.13%   |
| 0x06006110 | 1         | 3.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KabyLake   | 6         | 18.75%  |
| IvyBridge  | 4         | 12.5%   |
| Haswell    | 4         | 12.5%   |
| Excavator  | 3         | 9.38%   |
| Zen 2      | 2         | 6.25%   |
| Silvermont | 2         | 6.25%   |
| Zen+       | 1         | 3.13%   |
| Zen 3      | 1         | 3.13%   |
| Zen        | 1         | 3.13%   |
| Westmere   | 1         | 3.13%   |
| TigerLake  | 1         | 3.13%   |
| Skylake    | 1         | 3.13%   |
| Penryn     | 1         | 3.13%   |
| Icelake    | 1         | 3.13%   |
| CometLake  | 1         | 3.13%   |
| Bonnell    | 1         | 3.13%   |
| Unknown    | 1         | 3.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 21        | 53.85%  |
| Nvidia | 9         | 23.08%  |
| AMD    | 9         | 23.08%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 7.69%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 7.69%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 5.13%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 5.13%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 5.13%   |
| AMD Renoir                                                                               | 2         | 5.13%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 2.56%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 2.56%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 2.56%   |
| Nvidia GM108M [GeForce 930M]                                                             | 1         | 2.56%   |
| Nvidia GK107GLM [Quadro K1000M]                                                          | 1         | 2.56%   |
| Nvidia GK104GLM [Quadro K3100M]                                                          | 1         | 2.56%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 2.56%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                                       | 1         | 2.56%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 2.56%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 2.56%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 2.56%   |
| Intel Tiger Lake-H GT1 [UHD Graphics]                                                    | 1         | 2.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 2.56%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 2.56%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 2.56%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 2.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 2.56%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 2.56%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 2.56%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 2.56%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 2.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 2.56%   |
| AMD Lucienne                                                                             | 1         | 2.56%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 1         | 2.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 15        | 46.88%  |
| 1 x AMD        | 8         | 25%     |
| Intel + Nvidia | 6         | 18.75%  |
| 1 x Nvidia     | 2         | 6.25%   |
| AMD + Nvidia   | 1         | 3.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 29        | 90.63%  |
| Proprietary | 2         | 6.25%   |
| Unknown     | 1         | 3.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 17        | 53.13%  |
| 0.01-0.5   | 7         | 21.88%  |
| 5.01-6.0   | 3         | 9.38%   |
| 1.01-2.0   | 3         | 9.38%   |
| 3.01-4.0   | 2         | 6.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 8         | 23.53%  |
| LG Display              | 7         | 20.59%  |
| Samsung Electronics     | 4         | 11.76%  |
| BOE                     | 4         | 11.76%  |
| Chimei Innolux          | 3         | 8.82%   |
| PANDA                   | 2         | 5.88%   |
| InfoVision              | 2         | 5.88%   |
| Sharp                   | 1         | 2.94%   |
| Seiki                   | 1         | 2.94%   |
| Chi Mei Optoelectronics | 1         | 2.94%   |
| BenQ                    | 1         | 2.94%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO203D 1920x1080 309x173mm 13.9-inch           | 2         | 5.88%   |
| Sharp LC-32LB480U SHP3263 1920x1080 698x392mm 31.5-inch                  | 1         | 2.94%   |
| Seiki SC32HT04 SEK1366 1366x768 700x390mm 31.5-inch                      | 1         | 2.94%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 1         | 2.94%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch     | 1         | 2.94%   |
| Samsung Electronics LCD Monitor SDC4142 3840x2160 294x165mm 13.3-inch    | 1         | 2.94%   |
| Samsung Electronics LCD Monitor SDC4141 3840x2160 344x194mm 15.5-inch    | 1         | 2.94%   |
| PANDA LCD Monitor NCP0058 1920x1080 344x194mm 15.5-inch                  | 1         | 2.94%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                  | 1         | 2.94%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch             | 1         | 2.94%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch              | 1         | 2.94%   |
| LG Display LCD Monitor LGD042D 1920x1080 294x165mm 13.3-inch             | 1         | 2.94%   |
| LG Display LCD Monitor LGD03FB 1920x1080 382x215mm 17.3-inch             | 1         | 2.94%   |
| LG Display LCD Monitor LGD034A 1366x768 345x194mm 15.6-inch              | 1         | 2.94%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch              | 1         | 2.94%   |
| LG Display LCD Monitor LGD02A5 1366x768 345x194mm 15.6-inch              | 1         | 2.94%   |
| InfoVision LCD Monitor IVO3D41 1920x1080 344x194mm 15.5-inch             | 1         | 2.94%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch             | 1         | 2.94%   |
| Chimei Innolux LCD Monitor CMN1510 1920x1080 344x193mm 15.5-inch         | 1         | 2.94%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 309x174mm 14.0-inch          | 1         | 2.94%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 1         | 2.94%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 1         | 2.94%   |
| BOE LCD Monitor BOE09BA 2560x1600 345x215mm 16.0-inch                    | 1         | 2.94%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 1         | 2.94%   |
| BOE LCD Monitor BOE07A3 1920x1080 344x193mm 15.5-inch                    | 1         | 2.94%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                     | 1         | 2.94%   |
| BenQ GL2450 BNQ78A5 1920x1080 531x298mm 24.0-inch                        | 1         | 2.94%   |
| AU Optronics LCD Monitor AUOF992 1920x1080 382x215mm 17.3-inch           | 1         | 2.94%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch           | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO623D 1920x1080 309x174mm 14.0-inch           | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO479D 1920x1080 382x215mm 17.3-inch           | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO13ED 1920x1080 344x193mm 15.5-inch           | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch            | 1         | 2.94%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 20        | 58.82%  |
| 1366x768 (WXGA) | 10        | 29.41%  |
| 3840x2160 (4K)  | 2         | 5.88%   |
| 2560x1600       | 1         | 2.94%   |
| 1600x900 (HD+)  | 1         | 2.94%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 14        | 41.18%  |
| 14     | 7         | 20.59%  |
| 17     | 4         | 11.76%  |
| 13     | 3         | 8.82%   |
| 31     | 2         | 5.88%   |
| 11     | 2         | 5.88%   |
| 24     | 1         | 2.94%   |
| 16     | 1         | 2.94%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 23        | 67.65%  |
| 351-400     | 4         | 11.76%  |
| 201-300     | 4         | 11.76%  |
| 601-700     | 2         | 5.88%   |
| 501-600     | 1         | 2.94%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 30        | 96.77%  |
| 16/10 | 1         | 3.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 14        | 41.18%  |
| 81-90          | 8         | 23.53%  |
| 121-130        | 4         | 11.76%  |
| 71-80          | 2         | 5.88%   |
| 51-60          | 2         | 5.88%   |
| 351-500        | 2         | 5.88%   |
| 201-250        | 1         | 2.94%   |
| 111-120        | 1         | 2.94%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 18        | 52.94%  |
| 101-120       | 7         | 20.59%  |
| 51-100        | 4         | 11.76%  |
| More than 240 | 2         | 5.88%   |
| 161-240       | 2         | 5.88%   |
| 1-50          | 1         | 2.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 28        | 87.5%   |
| 2     | 3         | 9.38%   |
| 0     | 1         | 3.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 18        | 36.73%  |
| Realtek Semiconductor | 14        | 28.57%  |
| Qualcomm Atheros      | 8         | 16.33%  |
| Broadcom Limited      | 2         | 4.08%   |
| Broadcom              | 2         | 4.08%   |
| TP-Link               | 1         | 2.04%   |
| Sierra Wireless       | 1         | 2.04%   |
| Samsung Electronics   | 1         | 2.04%   |
| Ralink Technology     | 1         | 2.04%   |
| MediaTek              | 1         | 2.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8         | 13.56%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 5.08%   |
| Intel Wireless 7260                                               | 3         | 5.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 5.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 3.39%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 3.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 3.39%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 3.39%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 3.39%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 3.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.39%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.69%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 1.69%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.69%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 1.69%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1         | 1.69%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 1.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.69%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.69%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 1.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.69%   |
| MediaTek WP15                                                     | 1         | 1.69%   |
| Intel Wireless 7265                                               | 1         | 1.69%   |
| Intel Wireless 3165                                               | 1         | 1.69%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 1.69%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.69%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.69%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.69%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.69%   |
| Intel Centrino Wireless-N 2230                                    | 1         | 1.69%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 1.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 1.69%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.69%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 1.69%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                           | 1         | 1.69%   |
| Broadcom BCM43225 802.11b/g/n                                     | 1         | 1.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 1         | 1.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 16        | 45.71%  |
| Qualcomm Atheros      | 8         | 22.86%  |
| Realtek Semiconductor | 6         | 17.14%  |
| Broadcom              | 2         | 5.71%   |
| Sierra Wireless       | 1         | 2.86%   |
| Ralink Technology     | 1         | 2.86%   |
| Broadcom Limited      | 1         | 2.86%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 3         | 8.57%   |
| Intel Wireless 7260                                        | 3         | 8.57%   |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 3         | 8.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 2         | 5.71%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 2         | 5.71%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 2         | 5.71%   |
| Intel Wi-Fi 6 AX200                                        | 2         | 5.71%   |
| Sierra Wireless EM7345 4G LTE                              | 1         | 2.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 2.86%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1         | 2.86%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter        | 1         | 2.86%   |
| Realtek RTL8191SEvB Wireless LAN Controller                | 1         | 2.86%   |
| Ralink MT7601U Wireless Adapter                            | 1         | 2.86%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 2.86%   |
| Intel Wireless 7265                                        | 1         | 2.86%   |
| Intel Wireless 3165                                        | 1         | 2.86%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 1         | 2.86%   |
| Intel Wi-Fi 6 AX201                                        | 1         | 2.86%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1         | 2.86%   |
| Intel Centrino Wireless-N 2230                             | 1         | 2.86%   |
| Intel Centrino Ultimate-N 6300                             | 1         | 2.86%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 1         | 2.86%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                    | 1         | 2.86%   |
| Broadcom BCM43225 802.11b/g/n                              | 1         | 2.86%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter        | 1         | 2.86%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 12        | 52.17%  |
| Intel                 | 7         | 30.43%  |
| TP-Link               | 1         | 4.35%   |
| Qualcomm Atheros      | 1         | 4.35%   |
| MediaTek              | 1         | 4.35%   |
| Broadcom Limited      | 1         | 4.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8         | 34.78%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 8.7%    |
| Intel Ethernet Connection (10) I219-V                             | 2         | 8.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 8.7%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 4.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 4.35%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 4.35%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 4.35%   |
| MediaTek WP15                                                     | 1         | 4.35%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 4.35%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 4.35%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 4.35%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 4.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 32        | 58.18%  |
| Ethernet | 22        | 40%     |
| Modem    | 1         | 1.82%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 25        | 69.44%  |
| Ethernet | 11        | 30.56%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 20        | 62.5%   |
| 1     | 12        | 37.5%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 26        | 81.25%  |
| Yes  | 6         | 18.75%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 15        | 51.72%  |
| Qualcomm Atheros Communications | 7         | 24.14%  |
| Realtek Semiconductor           | 4         | 13.79%  |
| Foxconn / Hon Hai               | 1         | 3.45%   |
| Cambridge Silicon Radio         | 1         | 3.45%   |
| Broadcom                        | 1         | 3.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device                  | 5         | 17.24%  |
| Intel Bluetooth wireless interface                  | 5         | 17.24%  |
| Intel AX201 Bluetooth                               | 5         | 17.24%  |
| Realtek Bluetooth Radio                             | 3         | 10.34%  |
| Intel AX200 Bluetooth                               | 2         | 6.9%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 3.45%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 3.45%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 3.45%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 3.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 3.45%   |
| Intel AX210 Bluetooth                               | 1         | 3.45%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 3.45%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.45%   |
| Broadcom HP Portable SoftSailing                    | 1         | 3.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel                | 23        | 53.49%  |
| AMD                  | 9         | 20.93%  |
| Nvidia               | 8         | 18.6%   |
| C-Media Electronics  | 2         | 4.65%   |
| Conrad Electronic SE | 1         | 2.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 11.11%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 7.41%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 5.56%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 5.56%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 5.56%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 5.56%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 5.56%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 3.7%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 3.7%    |
| AMD High Definition Audio Controller                                                              | 2         | 3.7%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 1.85%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.85%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.85%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 1.85%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 1.85%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.85%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 1.85%   |
| Nvidia Audio device                                                                               | 1         | 1.85%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 1.85%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 1.85%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1         | 1.85%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 1.85%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.85%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 1.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 1.85%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.85%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 1.85%   |
| Conrad Electronic SE MIDI Cable UA0037                                                            | 1         | 1.85%   |
| C-Media Electronics USB Audio Device                                                              | 1         | 1.85%   |
| C-Media Electronics CM106 Like Sound Device                                                       | 1         | 1.85%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 33.33%  |
| SK hynix            | 4         | 16.67%  |
| Micron Technology   | 4         | 16.67%  |
| Kingston            | 3         | 12.5%   |
| Elpida              | 2         | 8.33%   |
| Unknown             | 1         | 4.17%   |
| Timetec             | 1         | 4.17%   |
| Crucial             | 1         | 4.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 2         | 7.41%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                               | 1         | 3.7%    |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                             | 1         | 3.7%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 3.7%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 3.7%    |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s                    | 1         | 3.7%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s              | 1         | 3.7%    |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s          | 1         | 3.7%    |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                               | 1         | 3.7%    |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 2133MT/s                       | 1         | 3.7%    |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                              | 1         | 3.7%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 1         | 3.7%    |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s                    | 1         | 3.7%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                     | 1         | 3.7%    |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s                     | 1         | 3.7%    |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s                     | 1         | 3.7%    |
| Micron RAM 4ATF51264HZ-2G6E3 4GB SODIMM DDR4 2667MT/s                     | 1         | 3.7%    |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                      | 1         | 3.7%    |
| Micron RAM 16KTF1G64HZ-1G6P1 8GB SODIMM DDR3 1600MT/s                     | 1         | 3.7%    |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s                      | 1         | 3.7%    |
| Kingston RAM KHX2666C15S4/8G 8GB SODIMM DDR4 2667MT/s                     | 1         | 3.7%    |
| Kingston RAM 787878787878787878787878787878787878 2GB SODIMM DDR2 667MT/s | 1         | 3.7%    |
| Kingston RAM 272727272727272727272727272727272727 2GB SODIMM DDR2 800MT/s | 1         | 3.7%    |
| Elpida RAM EBJ81UG8EFU0-GN-F 8GB SODIMM DDR3 1600MT/s                     | 1         | 3.7%    |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s                     | 1         | 3.7%    |
| Crucial RAM CT8G4SFS8266.C8FE 8GB SODIMM DDR4 2667MT/s                    | 1         | 3.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 9         | 50%     |
| DDR3   | 6         | 33.33%  |
| LPDDR3 | 2         | 11.11%  |
| DDR2   | 1         | 5.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 15        | 83.33%  |
| Row Of Chips | 3         | 16.67%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 8         | 42.11%  |
| 8192  | 7         | 36.84%  |
| 16384 | 2         | 10.53%  |
| 32768 | 1         | 5.26%   |
| 2048  | 1         | 5.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 6         | 28.57%  |
| 1600  | 6         | 28.57%  |
| 2667  | 3         | 14.29%  |
| 2133  | 2         | 9.52%   |
| 1866  | 1         | 4.76%   |
| 1333  | 1         | 4.76%   |
| 800   | 1         | 4.76%   |
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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 9         | 31.03%  |
| IMC Networks                           | 5         | 17.24%  |
| Suyin                                  | 2         | 6.9%    |
| Microdia                               | 2         | 6.9%    |
| Luxvisions Innotech Limited            | 2         | 6.9%    |
| Cheng Uei Precision Industry (Foxlink) | 2         | 6.9%    |
| Bison Electronics                      | 2         | 6.9%    |
| Acer                                   | 2         | 6.9%    |
| Syntek                                 | 1         | 3.45%   |
| SunplusIT                              | 1         | 3.45%   |
| Realtek Semiconductor                  | 1         | 3.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                           | 4         | 13.33%  |
| Chicony Integrated HP HD Webcam                                          | 2         | 6.67%   |
| Chicony HP Truevision HD                                                 | 2         | 6.67%   |
| Syntek Integrated Camera                                                 | 1         | 3.33%   |
| Suyin HD WebCam                                                          | 1         | 3.33%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)              | 1         | 3.33%   |
| SunplusIT HD Webcam                                                      | 1         | 3.33%   |
| Realtek EasyCamera                                                       | 1         | 3.33%   |
| Microdia Integrated_Webcam_HD                                            | 1         | 3.33%   |
| Microdia Integrated Webcam HD                                            | 1         | 3.33%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                      | 1         | 3.33%   |
| Luxvisions Innotech Limited HP HD Camera                                 | 1         | 3.33%   |
| IMC Networks USB2.0 HD IR UVC WebCam                                     | 1         | 3.33%   |
| Chicony TOSHIBA Web Camera - HD                                          | 1         | 3.33%   |
| Chicony Lenovo EasyCamera                                                | 1         | 3.33%   |
| Chicony Integrated RGB Camera                                            | 1         | 3.33%   |
| Chicony EasyCamera                                                       | 1         | 3.33%   |
| Chicony 8M Camera                                                        | 1         | 3.33%   |
| Chicony 720p HD Camera                                                   | 1         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) HP True Vision HD Camera          | 1         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 1         | 3.33%   |
| Bison Lenovo EasyCamera                                                  | 1         | 3.33%   |
| Bison Integrated Camera                                                  | 1         | 3.33%   |
| Acer USB Camera                                                          | 1         | 3.33%   |
| Acer HD Webcam                                                           | 1         | 3.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 6         | 75%     |
| Synaptics             | 1         | 12.5%   |
| Elan Microelectronics | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Validity Sensors VFS491                      | 2         | 25%     |
| Validity Sensors VFS5011 Fingerprint Reader  | 1         | 12.5%   |
| Validity Sensors VFS495 Fingerprint Reader   | 1         | 12.5%   |
| Validity Sensors VFS 5011 fingerprint sensor | 1         | 12.5%   |
| Validity Sensors Fingerprint scanner         | 1         | 12.5%   |
| Synaptics UWP WBDI Device                    | 1         | 12.5%   |
| Elan ELAN:ARM-M4                             | 1         | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 17        | 53.13%  |
| 1     | 10        | 31.25%  |
| 2     | 4         | 12.5%   |
| 7     | 1         | 3.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 8         | 34.78%  |
| Multimedia controller | 4         | 17.39%  |
| Net/wireless          | 3         | 13.04%  |
| Graphics card         | 3         | 13.04%  |
| Sound                 | 1         | 4.35%   |
| Firewire controller   | 1         | 4.35%   |
| Chipcard              | 1         | 4.35%   |
| Camera                | 1         | 4.35%   |
| Bluetooth             | 1         | 4.35%   |

