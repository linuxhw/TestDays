Siduction - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Siduction.

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

Total: 44

| Vendor  | Model                       | Probe                                                      | Date         |
|---------|-----------------------------|------------------------------------------------------------|--------------|
| HP      | 250 G7 Notebook PC          | [428177914f](https://linux-hardware.org/?probe=428177914f) | Sep 17, 2023 |
| HP      | 250 G7 Notebook PC          | [f2b0e180d4](https://linux-hardware.org/?probe=f2b0e180d4) | Aug 27, 2023 |
| HP      | ZBook 15 G6                 | [eb23ebb0b8](https://linux-hardware.org/?probe=eb23ebb0b8) | Jun 10, 2023 |
| Apple   | MacBookPro9,2               | [baf92c8b36](https://linux-hardware.org/?probe=baf92c8b36) | Jun 08, 2023 |
| HP      | 250 G7 Notebook PC          | [2f0f83bda2](https://linux-hardware.org/?probe=2f0f83bda2) | May 25, 2023 |
| HP      | ProBook 640 G1              | [5dceebaf6c](https://linux-hardware.org/?probe=5dceebaf6c) | May 13, 2023 |
| Dell    | Vostro 15 3510              | [fc82fe9907](https://linux-hardware.org/?probe=fc82fe9907) | May 11, 2023 |
| Dell    | Latitude 5491               | [ef97e6890a](https://linux-hardware.org/?probe=ef97e6890a) | Apr 13, 2023 |
| ASUSTek | X751LAB                     | [03465bed03](https://linux-hardware.org/?probe=03465bed03) | Apr 06, 2023 |
| HP      | ProBook 640 G1              | [5aa6a42aa2](https://linux-hardware.org/?probe=5aa6a42aa2) | Mar 29, 2023 |
| Acer    | Swift SF314-51              | [5a73818024](https://linux-hardware.org/?probe=5a73818024) | Mar 27, 2023 |
| Lenovo  | ThinkPad X1 Carbon 5th 2... | [0c7e919608](https://linux-hardware.org/?probe=0c7e919608) | Mar 20, 2023 |
| Acer    | Aspire E5-551G              | [58703e3260](https://linux-hardware.org/?probe=58703e3260) | Mar 15, 2023 |
| Lenovo  | ThinkPad X1 Carbon 5th 2... | [5c39a363d8](https://linux-hardware.org/?probe=5c39a363d8) | Feb 28, 2023 |
| HP      | EliteBook 865 16 inch G9... | [49a4e66cd0](https://linux-hardware.org/?probe=49a4e66cd0) | Feb 05, 2023 |
| Acer    | Aspire V5-471               | [fe551b92a5](https://linux-hardware.org/?probe=fe551b92a5) | Oct 02, 2022 |
| Acer    | Aspire A515-55              | [bed4db4cf3](https://linux-hardware.org/?probe=bed4db4cf3) | Jul 16, 2022 |
| Acer    | Aspire E5-771G              | [a765f92826](https://linux-hardware.org/?probe=a765f92826) | Mar 28, 2022 |
| Lenovo  | ThinkPad T410 253725G       | [3e1c463980](https://linux-hardware.org/?probe=3e1c463980) | Jan 16, 2022 |
| Lenovo  | IdeaPad 3 15IIL05 81WE      | [7fa0610547](https://linux-hardware.org/?probe=7fa0610547) | Jan 02, 2022 |
| Lenovo  | ThinkPad E590 20NB001AIX    | [436614e885](https://linux-hardware.org/?probe=436614e885) | Sep 26, 2021 |
| Lenovo  | ThinkPad T410 253725G       | [65b842202c](https://linux-hardware.org/?probe=65b842202c) | Aug 06, 2021 |
| ASUSTek | ZenBook UX325JA_UX325JA     | [70ddebc8cc](https://linux-hardware.org/?probe=70ddebc8cc) | Jul 25, 2021 |
| ASUSTek | ZenBook UX325JA_UX325JA     | [455c830431](https://linux-hardware.org/?probe=455c830431) | Jul 25, 2021 |
| TUXEDO  | Book BA1510                 | [80b8c9719c](https://linux-hardware.org/?probe=80b8c9719c) | Jul 11, 2021 |
| HP      | ProBook 4520s               | [50b007f51d](https://linux-hardware.org/?probe=50b007f51d) | Jun 26, 2021 |
| HP      | ProBook 4520s               | [261b02ab53](https://linux-hardware.org/?probe=261b02ab53) | Jun 20, 2021 |
| HP      | Laptop 17-ca1xxx            | [99f175055d](https://linux-hardware.org/?probe=99f175055d) | May 05, 2021 |
| HP      | Laptop 17-ca1xxx            | [e21ac181a5](https://linux-hardware.org/?probe=e21ac181a5) | Apr 03, 2021 |
| HP      | Laptop 17-ca1xxx            | [a8a82ba1b9](https://linux-hardware.org/?probe=a8a82ba1b9) | Mar 01, 2021 |
| HP      | Laptop 17-ca1xxx            | [a3ea535d80](https://linux-hardware.org/?probe=a3ea535d80) | Feb 04, 2021 |
| HP      | Laptop 17-ca1xxx            | [d88b363f5e](https://linux-hardware.org/?probe=d88b363f5e) | Jan 19, 2021 |
| HP      | Laptop 17-ca1xxx            | [5e6eb88969](https://linux-hardware.org/?probe=5e6eb88969) | Jan 02, 2021 |
| HP      | Laptop 17-ca1xxx            | [09675fa9a5](https://linux-hardware.org/?probe=09675fa9a5) | Dec 09, 2020 |
| HP      | Laptop 17-ca1xxx            | [0779e6ce28](https://linux-hardware.org/?probe=0779e6ce28) | Nov 18, 2020 |
| HP      | Laptop 17-ca1xxx            | [386583ebea](https://linux-hardware.org/?probe=386583ebea) | Sep 02, 2020 |
| HP      | 250 G7 Notebook PC          | [52a48bdcb8](https://linux-hardware.org/?probe=52a48bdcb8) | Aug 02, 2020 |
| Lenovo  | ThinkPad E590 20NB001AIX    | [bc066bdf30](https://linux-hardware.org/?probe=bc066bdf30) | Feb 11, 2020 |
| HP      | Laptop 15-db0xxx            | [f6d4378d90](https://linux-hardware.org/?probe=f6d4378d90) | Jan 03, 2020 |
| Compal  | NBLBX                       | [865da8f6a9](https://linux-hardware.org/?probe=865da8f6a9) | Dec 05, 2019 |
| Lenovo  | ThinkPad Edge E540 20C60... | [552827c68a](https://linux-hardware.org/?probe=552827c68a) | Nov 20, 2019 |
| Lenovo  | ThinkPad Edge E540 20C60... | [d942b46e5b](https://linux-hardware.org/?probe=d942b46e5b) | Nov 20, 2019 |
| Lenovo  | ThinkPad Edge E540 20C60... | [17f6c8b364](https://linux-hardware.org/?probe=17f6c8b364) | Nov 20, 2019 |
| Acer    | Aspire 5750                 | [62afcd020e](https://linux-hardware.org/?probe=62afcd020e) | Feb 26, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Siduction 12       | 9         | 37.5%   |
| Siduction 11       | 7         | 29.17%  |
| Siduction Unstable | 4         | 16.67%  |
| Siduction 10       | 3         | 12.5%   |
| Siduction          | 1         | 4.17%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| Siduction | 21        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Notebooks | Percent |
|--------------------------------|-----------|---------|
| 6.2.8-1-siduction-amd64        | 2         | 5.71%   |
| 6.2.6-1-siduction-amd64        | 2         | 5.71%   |
| 6.5.3-1-siduction-amd64        | 1         | 2.86%   |
| 6.4.12-1-siduction-amd64       | 1         | 2.86%   |
| 6.3.7-1-siduction-amd64        | 1         | 2.86%   |
| 6.3.3-1-siduction-amd64        | 1         | 2.86%   |
| 6.2.15-1-siduction-amd64       | 1         | 2.86%   |
| 6.2.13-1-siduction-amd64       | 1         | 2.86%   |
| 6.2.11-1-siduction-amd64       | 1         | 2.86%   |
| 6.2.0-rc6-siduction-amd64      | 1         | 2.86%   |
| 6.1.1-4-siduction-amd64        | 1         | 2.86%   |
| 5.9.8-towo.3-siduction-amd64   | 1         | 2.86%   |
| 5.9.13-towo.1-siduction-amd64  | 1         | 2.86%   |
| 5.8.5-towo.1-siduction-amd64   | 1         | 2.86%   |
| 5.7.11-towo.2-siduction-amd64  | 1         | 2.86%   |
| 5.4.5-towo.2-siduction-amd64   | 1         | 2.86%   |
| 5.4.18-towo.1-siduction-amd64  | 1         | 2.86%   |
| 5.3.12-towo.2-siduction-amd64  | 1         | 2.86%   |
| 5.3.1-towo.2-siduction-amd64   | 1         | 2.86%   |
| 5.16.17-1-siduction-amd64      | 1         | 2.86%   |
| 5.15.15-1-siduction-amd64      | 1         | 2.86%   |
| 5.13.8-1-siduction-amd64       | 1         | 2.86%   |
| 5.13.6-1-siduction-amd64       | 1         | 2.86%   |
| 5.13.4-3-siduction-amd64       | 1         | 2.86%   |
| 5.13.1-1-siduction-amd64       | 1         | 2.86%   |
| 5.12.12-1-siduction-amd64      | 1         | 2.86%   |
| 5.11.18-1-siduction-amd64      | 1         | 2.86%   |
| 5.11.11-1-siduction-amd64      | 1         | 2.86%   |
| 5.10.4-towo.1-siduction-amd64  | 1         | 2.86%   |
| 5.10.19-towo.1-siduction-amd64 | 1         | 2.86%   |
| 5.10.17-towo.1-siduction-amd64 | 1         | 2.86%   |
| 5.10.12-towo.1-siduction-amd64 | 1         | 2.86%   |
| 4.20.11-towo.2-siduction-amd64 | 1         | 2.86%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2.8   | 2         | 5.71%   |
| 6.2.6   | 2         | 5.71%   |
| 6.5.3   | 1         | 2.86%   |
| 6.4.12  | 1         | 2.86%   |
| 6.3.7   | 1         | 2.86%   |
| 6.3.3   | 1         | 2.86%   |
| 6.2.15  | 1         | 2.86%   |
| 6.2.13  | 1         | 2.86%   |
| 6.2.11  | 1         | 2.86%   |
| 6.2.0   | 1         | 2.86%   |
| 6.1.1   | 1         | 2.86%   |
| 5.9.8   | 1         | 2.86%   |
| 5.9.13  | 1         | 2.86%   |
| 5.8.5   | 1         | 2.86%   |
| 5.7.11  | 1         | 2.86%   |
| 5.4.5   | 1         | 2.86%   |
| 5.4.18  | 1         | 2.86%   |
| 5.3.12  | 1         | 2.86%   |
| 5.3.1   | 1         | 2.86%   |
| 5.16.17 | 1         | 2.86%   |
| 5.15.15 | 1         | 2.86%   |
| 5.13.8  | 1         | 2.86%   |
| 5.13.6  | 1         | 2.86%   |
| 5.13.4  | 1         | 2.86%   |
| 5.13.1  | 1         | 2.86%   |
| 5.12.12 | 1         | 2.86%   |
| 5.11.18 | 1         | 2.86%   |
| 5.11.11 | 1         | 2.86%   |
| 5.10.4  | 1         | 2.86%   |
| 5.10.19 | 1         | 2.86%   |
| 5.10.17 | 1         | 2.86%   |
| 5.10.12 | 1         | 2.86%   |
| 4.20.11 | 1         | 2.86%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2     | 7         | 23.33%  |
| 5.13    | 4         | 13.33%  |
| 6.3     | 2         | 6.67%   |
| 5.4     | 2         | 6.67%   |
| 5.3     | 2         | 6.67%   |
| 5.10    | 2         | 6.67%   |
| 6.5     | 1         | 3.33%   |
| 6.4     | 1         | 3.33%   |
| 6.1     | 1         | 3.33%   |
| 5.9     | 1         | 3.33%   |
| 5.8     | 1         | 3.33%   |
| 5.7     | 1         | 3.33%   |
| 5.16    | 1         | 3.33%   |
| 5.15    | 1         | 3.33%   |
| 5.12    | 1         | 3.33%   |
| 5.11    | 1         | 3.33%   |
| 4.20    | 1         | 3.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 21        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KDE5            | 11        | 45.83%  |
| XFCE            | 4         | 16.67%  |
| Unknown         | 4         | 16.67%  |
| X-Cinnamon      | 2         | 8.33%   |
| LXQt            | 1         | 4.17%   |
| GNOME Flashback | 1         | 4.17%   |
| Cinnamon        | 1         | 4.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 19        | 90.48%  |
| Wayland | 1         | 4.76%   |
| Tty     | 1         | 4.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 13        | 59.09%  |
| Unknown | 7         | 31.82%  |
| TDM     | 1         | 4.55%   |
| GDM     | 1         | 4.55%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| de_DE   | 9         | 39.13%  |
| en_US   | 5         | 21.74%  |
| Unknown | 3         | 13.04%  |
| en_GB   | 2         | 8.7%    |
| fr_FR   | 1         | 4.35%   |
| en_CA   | 1         | 4.35%   |
| de_CH   | 1         | 4.35%   |
| C       | 1         | 4.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 13        | 59.09%  |
| BIOS | 9         | 40.91%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 18        | 85.71%  |
| Btrfs   | 2         | 9.52%   |
| Unknown | 1         | 4.76%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 12        | 54.55%  |
| Unknown | 7         | 31.82%  |
| MBR     | 3         | 13.64%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 18        | 85.71%  |
| Yes       | 3         | 14.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 17        | 80.95%  |
| Yes       | 4         | 19.05%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 7         | 33.33%  |
| Lenovo           | 5         | 23.81%  |
| Acer             | 4         | 19.05%  |
| Dell             | 2         | 9.52%   |
| TUXEDO           | 1         | 4.76%   |
| Compal           | 1         | 4.76%   |
| ASUSTek Computer | 1         | 4.76%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| TUXEDO Book BA1510                       | 1         | 4.76%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRCTO1WW | 1         | 4.76%   |
| Lenovo ThinkPad T410 253725G             | 1         | 4.76%   |
| Lenovo ThinkPad Edge E540 20C6003AGE     | 1         | 4.76%   |
| Lenovo ThinkPad E590 20NB001AIX          | 1         | 4.76%   |
| Lenovo IdeaPad 3 15IIL05 81WE            | 1         | 4.76%   |
| HP ZBook 15 G6                           | 1         | 4.76%   |
| HP ProBook 640 G1                        | 1         | 4.76%   |
| HP ProBook 4520s                         | 1         | 4.76%   |
| HP Laptop 17-ca1xxx                      | 1         | 4.76%   |
| HP Laptop 15-db0xxx                      | 1         | 4.76%   |
| HP EliteBook 865 16 inch G9 Notebook PC  | 1         | 4.76%   |
| HP 250 G7 Notebook PC                    | 1         | 4.76%   |
| Dell Vostro 15 3510                      | 1         | 4.76%   |
| Dell Latitude 5491                       | 1         | 4.76%   |
| Compal NBLBX                             | 1         | 4.76%   |
| ASUS ZenBook UX325JA_UX325JA             | 1         | 4.76%   |
| Acer Swift SF314-51                      | 1         | 4.76%   |
| Acer Aspire E5-771G                      | 1         | 4.76%   |
| Acer Aspire E5-551G                      | 1         | 4.76%   |
| Acer Aspire 5750                         | 1         | 4.76%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Lenovo ThinkPad | 4         | 19.05%  |
| Acer Aspire     | 3         | 14.29%  |
| HP ProBook      | 2         | 9.52%   |
| HP Laptop       | 2         | 9.52%   |
| TUXEDO Book     | 1         | 4.76%   |
| Lenovo IdeaPad  | 1         | 4.76%   |
| HP ZBook        | 1         | 4.76%   |
| HP EliteBook    | 1         | 4.76%   |
| HP 250          | 1         | 4.76%   |
| Dell Vostro     | 1         | 4.76%   |
| Dell Latitude   | 1         | 4.76%   |
| Compal NBLBX    | 1         | 4.76%   |
| ASUS ZenBook    | 1         | 4.76%   |
| Acer Swift      | 1         | 4.76%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 3         | 14.29%  |
| 2019 | 3         | 14.29%  |
| 2018 | 3         | 14.29%  |
| 2014 | 2         | 9.52%   |
| 2013 | 2         | 9.52%   |
| 2010 | 2         | 9.52%   |
| 2022 | 1         | 4.76%   |
| 2021 | 1         | 4.76%   |
| 2017 | 1         | 4.76%   |
| 2016 | 1         | 4.76%   |
| 2011 | 1         | 4.76%   |
| 2009 | 1         | 4.76%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 21        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 21        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 21        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 8         | 36.36%  |
| 8.01-16.0   | 5         | 22.73%  |
| 16.01-24.0  | 4         | 18.18%  |
| 32.01-64.0  | 2         | 9.09%   |
| 3.01-4.0    | 1         | 4.55%   |
| 64.01-256.0 | 1         | 4.55%   |
| Unknown     | 1         | 4.55%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 8         | 30.77%  |
| 3.01-4.0 | 6         | 23.08%  |
| 4.01-8.0 | 5         | 19.23%  |
| 1.01-2.0 | 4         | 15.38%  |
| 0.51-1.0 | 2         | 7.69%   |
| Unknown  | 1         | 3.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 14        | 66.67%  |
| 2      | 7         | 33.33%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 14        | 66.67%  |
| Yes       | 7         | 33.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 17        | 80.95%  |
| No        | 4         | 19.05%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 21        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 17        | 73.91%  |
| No        | 6         | 26.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Germany     | 9         | 40.91%  |
| Canada      | 3         | 13.64%  |
| USA         | 2         | 9.09%   |
| UK          | 2         | 9.09%   |
| Switzerland | 1         | 4.55%   |
| Sweden      | 1         | 4.55%   |
| Italy       | 1         | 4.55%   |
| Israel      | 1         | 4.55%   |
| France      | 1         | 4.55%   |
| Austria     | 1         | 4.55%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Munich               | 2         | 6.67%   |
| Zurich               | 1         | 3.33%   |
| Vienna               | 1         | 3.33%   |
| Turin                | 1         | 3.33%   |
| Toronto              | 1         | 3.33%   |
| Suisun               | 1         | 3.33%   |
| Stuttgart            | 1         | 3.33%   |
| Stockholm            | 1         | 3.33%   |
| Sidney               | 1         | 3.33%   |
| Schrobenhausen       | 1         | 3.33%   |
| San Francisco        | 1         | 3.33%   |
| Reading              | 1         | 3.33%   |
| Paris                | 1         | 3.33%   |
| Mittenwald           | 1         | 3.33%   |
| Milan                | 1         | 3.33%   |
| Mannheim             | 1         | 3.33%   |
| Malmo                | 1         | 3.33%   |
| Langewiesen          | 1         | 3.33%   |
| Landau               | 1         | 3.33%   |
| Jerusalem            | 1         | 3.33%   |
| Iserlohn             | 1         | 3.33%   |
| Hamburg              | 1         | 3.33%   |
| Guglingen            | 1         | 3.33%   |
| Friedrichsthal       | 1         | 3.33%   |
| Freiburg im Breisgau | 1         | 3.33%   |
| Edmonton             | 1         | 3.33%   |
| Düsseldorf          | 1         | 3.33%   |
| Blackwood            | 1         | 3.33%   |
| Berlin               | 1         | 3.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 10     | 31.03%  |
| Toshiba             | 5         | 14     | 17.24%  |
| WDC                 | 4         | 5      | 13.79%  |
| SK hynix            | 2         | 2      | 6.9%    |
| Seagate             | 2         | 2      | 6.9%    |
| Sandisk             | 2         | 4      | 6.9%    |
| Intel               | 2         | 4      | 6.9%    |
| SSSTC               | 1         | 1      | 3.45%   |
| Kingston            | 1         | 1      | 3.45%   |
| Crucial             | 1         | 2      | 3.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| WDC WD10JPVX-22JC3T0 1TB                | 2         | 6.67%   |
| Toshiba MQ04ABF100 1TB                  | 2         | 6.67%   |
| WDC WDS200T2B0B-00YS70 2TB SSD          | 1         | 3.33%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB    | 1         | 3.33%   |
| Toshiba THNSNK256GVN8 256GB SSD         | 1         | 3.33%   |
| Toshiba MQ01ACF032 320GB                | 1         | 3.33%   |
| Toshiba KBG30ZMT256G 256GB              | 1         | 3.33%   |
| SSSTC CL4-3D256-Q11 NVMe 256GB          | 1         | 3.33%   |
| SK hynix NVMe SSD Drive 512GB           | 1         | 3.33%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB | 1         | 3.33%   |
| Seagate ST9500420AS 500GB               | 1         | 3.33%   |
| Seagate ST1000LM014-1EJ164 1TB          | 1         | 3.33%   |
| Sandisk WD Blue SN570 1TB               | 1         | 3.33%   |
| SanDisk SSD U110 16GB                   | 1         | 3.33%   |
| Samsung SSD 990 PRO 2TB                 | 1         | 3.33%   |
| Samsung SSD 980 PRO 1TB                 | 1         | 3.33%   |
| Samsung SSD 870 QVO 1TB                 | 1         | 3.33%   |
| Samsung SSD 860 EVO M.2 1TB             | 1         | 3.33%   |
| Samsung SSD 850 EVO 500GB               | 1         | 3.33%   |
| Samsung SSD 850 EVO 250GB               | 1         | 3.33%   |
| Samsung SSD 840 Series 250GB            | 1         | 3.33%   |
| Samsung MZVLQ128HBHQ-00000 128GB        | 1         | 3.33%   |
| Samsung HM321HI 320GB                   | 1         | 3.33%   |
| Kingston SA2000M8500G 500GB             | 1         | 3.33%   |
| Intel SSDPEKNW010T9 1TB                 | 1         | 3.33%   |
| Intel HBRPEKNX0203AO 32GB               | 1         | 3.33%   |
| Intel HBRPEKNX0203A 1TB                 | 1         | 3.33%   |
| Crucial CT1000MX500SSD1 1TB             | 1         | 3.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 3         | 11     | 37.5%   |
| WDC                 | 2         | 3      | 25%     |
| Seagate             | 2         | 2      | 25%     |
| Samsung Electronics | 1         | 1      | 12.5%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 6      | 55.56%  |
| WDC                 | 1         | 1      | 11.11%  |
| Toshiba             | 1         | 1      | 11.11%  |
| SanDisk             | 1         | 1      | 11.11%  |
| Crucial             | 1         | 2      | 11.11%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 11        | 17     | 42.31%  |
| HDD  | 8         | 17     | 30.77%  |
| SSD  | 7         | 11     | 26.92%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 14        | 28     | 56%     |
| NVMe | 11        | 17     | 44%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 7         | 17     | 46.67%  |
| 0.01-0.5   | 7         | 10     | 46.67%  |
| 1.01-2.0   | 1         | 1      | 6.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 6         | 25%     |
| 101-250    | 4         | 16.67%  |
| 1001-2000  | 4         | 16.67%  |
| Unknown    | 4         | 16.67%  |
| 501-1000   | 3         | 12.5%   |
| 1-20       | 2         | 8.33%   |
| 21-50      | 1         | 4.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 11        | 40.74%  |
| Unknown   | 4         | 14.81%  |
| 101-250   | 3         | 11.11%  |
| 251-500   | 2         | 7.41%   |
| 21-50     | 2         | 7.41%   |
| 501-1000  | 2         | 7.41%   |
| 51-100    | 2         | 7.41%   |
| 1001-2000 | 1         | 3.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Notebooks | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| SK hynix BC501 HFM256GDJTNG-8310A 256GB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| SK hynix | 1         | 1      | 100%    |

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
| NVMe | 1         | 1      | 100%    |

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
| Works    | 17        | 34     | 70.83%  |
| Detected | 6         | 10     | 25%     |
| Malfunc  | 1         | 1      | 4.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 16        | 53.33%  |
| AMD                            | 4         | 13.33%  |
| Toshiba America Info Systems   | 2         | 6.67%   |
| SK hynix                       | 2         | 6.67%   |
| SanDisk                        | 2         | 6.67%   |
| Samsung Electronics            | 2         | 6.67%   |
| Solid State Storage Technology | 1         | 3.33%   |
| Kingston Technology Company    | 1         | 3.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 4         | 12.5%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 6.25%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 6.25%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 6.25%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 6.25%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 6.25%   |
| Solid State Storage CL4-8D512 NVMe SSD M.2 (DRAM-less)                         | 1         | 3.13%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 1         | 3.13%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 1         | 3.13%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 1         | 3.13%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 3.13%   |
| Kingston Company A2000 NVMe SSD                                                | 1         | 3.13%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 3.13%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 3.13%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 1         | 3.13%   |
| Intel SSD 665p Series [Neptune Harbor Refresh]                                 | 1         | 3.13%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]             | 1         | 3.13%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 3.13%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 3.13%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 3.13%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 1         | 3.13%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 3.13%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 1         | 3.13%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 16        | 53.33%  |
| NVMe | 11        | 36.67%  |
| RAID | 2         | 6.67%   |
| IDE  | 1         | 3.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 16        | 76.19%  |
| AMD    | 5         | 23.81%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 9.52%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 9.52%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 9.52%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 1         | 4.76%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 4.76%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 4.76%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1         | 4.76%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 4.76%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 4.76%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 4.76%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1         | 4.76%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 1         | 4.76%   |
| Intel Core i3-4000M CPU @ 2.40GHz             | 1         | 4.76%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 1         | 4.76%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 4.76%   |
| AMD Ryzen 9 PRO 6950HS with Radeon Graphics   | 1         | 4.76%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 1         | 4.76%   |
| AMD FX-7500 Radeon R7, 10 Compute Cores 4C+6G | 1         | 4.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Intel Core i5 | 7         | 33.33%  |
| Intel Core i7 | 6         | 28.57%  |
| AMD Ryzen 5   | 3         | 14.29%  |
| Intel Core i3 | 2         | 9.52%   |
| Other         | 1         | 4.76%   |
| AMD Ryzen 9   | 1         | 4.76%   |
| AMD FX        | 1         | 4.76%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 9         | 42.86%  |
| 2      | 9         | 42.86%  |
| 6      | 2         | 9.52%   |
| 8      | 1         | 4.76%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 21        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 21        | 100%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 20        | 95.24%  |
| Unknown        | 1         | 4.76%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 7         | 28%     |
| 0x806ec    | 2         | 8%      |
| 0x706e5    | 2         | 8%      |
| 0x20655    | 2         | 8%      |
| 0x08108102 | 2         | 8%      |
| 0x806eb    | 1         | 4%      |
| 0x806e9    | 1         | 4%      |
| 0x306d4    | 1         | 4%      |
| 0x306c3    | 1         | 4%      |
| 0x206a7    | 1         | 4%      |
| 0x20652    | 1         | 4%      |
| 0x0a404102 | 1         | 4%      |
| 0x08108109 | 1         | 4%      |
| 0x0810100b | 1         | 4%      |
| 0x06003106 | 1         | 4%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 5         | 23.81%  |
| Westmere    | 3         | 14.29%  |
| Zen+        | 2         | 9.52%   |
| IceLake     | 2         | 9.52%   |
| Haswell     | 2         | 9.52%   |
| Zen         | 1         | 4.76%   |
| TigerLake   | 1         | 4.76%   |
| Steamroller | 1         | 4.76%   |
| Skylake     | 1         | 4.76%   |
| SandyBridge | 1         | 4.76%   |
| Broadwell   | 1         | 4.76%   |
| Unknown     | 1         | 4.76%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 14        | 56%     |
| AMD    | 7         | 28%     |
| Nvidia | 4         | 16%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 2         | 7.69%   |
| Intel Iris Plus Graphics G7                                                 | 2         | 7.69%   |
| Intel Core Processor Integrated Graphics Controller                         | 2         | 7.69%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 2         | 7.69%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2         | 7.69%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                               | 1         | 3.85%   |
| Nvidia GM108M [GeForce MX130]                                               | 1         | 3.85%   |
| Nvidia GK208M [GeForce GT 740M]                                             | 1         | 3.85%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 1         | 3.85%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 1         | 3.85%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 1         | 3.85%   |
| Intel HD Graphics 620                                                       | 1         | 3.85%   |
| Intel HD Graphics 5500                                                      | 1         | 3.85%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 1         | 3.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1         | 3.85%   |
| AMD RV711/M93 [Mobility Radeon HD 4350/4550/530v/540v/545v / FirePro RG220] | 1         | 3.85%   |
| AMD Rembrandt [Radeon 680M]                                                 | 1         | 3.85%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1         | 3.85%   |
| AMD Opal XT [Radeon R7 M265/M365X/M465]                                     | 1         | 3.85%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                    | 1         | 3.85%   |
| AMD Kaveri [Radeon R6/R7 Graphics]                                          | 1         | 3.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 10        | 47.62%  |
| 1 x AMD        | 5         | 23.81%  |
| Intel + Nvidia | 3         | 14.29%  |
| 2 x AMD        | 1         | 4.76%   |
| 1 x Nvidia     | 1         | 4.76%   |
| Intel + AMD    | 1         | 4.76%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 19        | 90.48%  |
| Proprietary | 2         | 9.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 12        | 57.14%  |
| 1.01-2.0   | 3         | 14.29%  |
| 0.01-0.5   | 3         | 14.29%  |
| 0.51-1.0   | 2         | 9.52%   |
| 3.01-4.0   | 1         | 4.76%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Chimei Innolux  | 8         | 32%     |
| LG Display      | 5         | 20%     |
| AU Optronics    | 4         | 16%     |
| Lenovo          | 2         | 8%      |
| BOE             | 2         | 8%      |
| Hewlett-Packard | 1         | 4%      |
| Goldstar        | 1         | 4%      |
| Dell            | 1         | 4%      |
| AOC             | 1         | 4%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD06FF 1920x1080 344x194mm 15.5-inch     | 1         | 4%      |
| LG Display LCD Monitor LGD059D 1920x1080 309x174mm 14.0-inch     | 1         | 4%      |
| LG Display LCD Monitor LGD051D 1920x1080 309x174mm 14.0-inch     | 1         | 4%      |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch      | 1         | 4%      |
| LG Display LCD Monitor LGD03DE 1600x900 382x215mm 17.3-inch      | 1         | 4%      |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch         | 1         | 4%      |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch          | 1         | 4%      |
| Hewlett-Packard E243i HPN3463 1920x1200 518x324mm 24.1-inch      | 1         | 4%      |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch          | 1         | 4%      |
| Dell U2415 DELA0BC 1920x1200 518x324mm 24.1-inch                 | 1         | 4%      |
| Chimei Innolux LCD Monitor CMN175A 1920x1080 381x214mm 17.2-inch | 1         | 4%      |
| Chimei Innolux LCD Monitor CMN1610 1920x1200 344x215mm 16.0-inch | 1         | 4%      |
| Chimei Innolux LCD Monitor CMN15F6 1920x1080 344x193mm 15.5-inch | 1         | 4%      |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch | 1         | 4%      |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch  | 1         | 4%      |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch | 1         | 4%      |
| Chimei Innolux LCD Monitor CMN15C0 1920x1080 344x194mm 15.5-inch | 1         | 4%      |
| Chimei Innolux LCD Monitor CMN1388 1920x1080 293x165mm 13.2-inch | 1         | 4%      |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch            | 1         | 4%      |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch            | 1         | 4%      |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch   | 1         | 4%      |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch    | 1         | 4%      |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch    | 1         | 4%      |
| AU Optronics LCD Monitor AUO10ED 1920x1080 344x193mm 15.5-inch   | 1         | 4%      |
| AOC 2436 AOC2436 1920x1080 521x293mm 23.5-inch                   | 1         | 4%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 15        | 65.22%  |
| 1366x768 (WXGA)   | 4         | 17.39%  |
| 3840x2160 (4K)    | 1         | 4.35%   |
| 1920x1200 (WUXGA) | 1         | 4.35%   |
| 1600x900 (HD+)    | 1         | 4.35%   |
| 1440x900 (WXGA+)  | 1         | 4.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 12        | 48%     |
| 14     | 5         | 20%     |
| 17     | 2         | 8%      |
| 40     | 1         | 4%      |
| 27     | 1         | 4%      |
| 24     | 1         | 4%      |
| 23     | 1         | 4%      |
| 16     | 1         | 4%      |
| 13     | 1         | 4%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 18        | 72%     |
| 501-600     | 3         | 12%     |
| 351-400     | 2         | 8%      |
| 801-900     | 1         | 4%      |
| 201-300     | 1         | 4%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 19        | 86.36%  |
| 16/10 | 3         | 13.64%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 12        | 48%     |
| 81-90          | 5         | 20%     |
| 121-130        | 2         | 8%      |
| 71-80          | 1         | 4%      |
| 301-350        | 1         | 4%      |
| 251-300        | 1         | 4%      |
| 201-250        | 1         | 4%      |
| 111-120        | 1         | 4%      |
| 501-1000       | 1         | 4%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 15        | 60%     |
| 101-120 | 5         | 20%     |
| 51-100  | 3         | 12%     |
| 161-240 | 2         | 8%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 17        | 80.95%  |
| 2     | 4         | 19.05%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 13        | 39.39%  |
| Realtek Semiconductor | 12        | 36.36%  |
| Qualcomm Atheros      | 4         | 12.12%  |
| Broadcom              | 2         | 6.06%   |
| Qualcomm              | 1         | 3.03%   |
| NetGear               | 1         | 3.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 26.83%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 4.88%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 4.88%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 4.88%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 2.44%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 2.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.44%   |
| Realtek 802.11ac WLAN Adapter                                     | 1         | 2.44%   |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 1         | 2.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 2.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 2.44%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 2.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 2.44%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]       | 1         | 2.44%   |
| Intel Wireless-AC 9260                                            | 1         | 2.44%   |
| Intel Wireless 8265 / 8275                                        | 1         | 2.44%   |
| Intel Wireless 7260                                               | 1         | 2.44%   |
| Intel Wireless 3160                                               | 1         | 2.44%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 2.44%   |
| Intel Ethernet Connection I217-V                                  | 1         | 2.44%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 2.44%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.44%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 1         | 2.44%   |
| Intel Centrino Advanced-N 6200                                    | 1         | 2.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 2.44%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.44%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 2.44%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 1         | 2.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 12        | 54.55%  |
| Qualcomm Atheros      | 4         | 18.18%  |
| Realtek Semiconductor | 3         | 13.64%  |
| Qualcomm              | 1         | 4.55%   |
| NetGear               | 1         | 4.55%   |
| Broadcom              | 1         | 4.55%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 8.33%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 8.33%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 8.33%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 4.17%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 4.17%   |
| Realtek 802.11ac WLAN Adapter                                  | 1         | 4.17%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 1         | 4.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 4.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 4.17%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 4.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 4.17%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]    | 1         | 4.17%   |
| Intel Wireless-AC 9260                                         | 1         | 4.17%   |
| Intel Wireless 8265 / 8275                                     | 1         | 4.17%   |
| Intel Wireless 7260                                            | 1         | 4.17%   |
| Intel Wireless 3160                                            | 1         | 4.17%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 4.17%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 1         | 4.17%   |
| Intel Centrino Advanced-N 6200                                 | 1         | 4.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 4.17%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 1         | 4.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 12        | 70.59%  |
| Intel                 | 4         | 23.53%  |
| Broadcom              | 1         | 5.88%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 64.71%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 5.88%   |
| Intel Ethernet Connection I217-V                                  | 1         | 5.88%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 5.88%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 5.88%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 5.88%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 5.88%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 21        | 55.26%  |
| Ethernet | 17        | 44.74%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 19        | 90.48%  |
| Ethernet | 2         | 9.52%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 16        | 76.19%  |
| 1     | 5         | 23.81%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 17        | 77.27%  |
| Yes  | 5         | 22.73%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 9         | 47.37%  |
| Realtek Semiconductor           | 3         | 15.79%  |
| Lite-On Technology              | 2         | 10.53%  |
| Qualcomm Atheros Communications | 1         | 5.26%   |
| Foxconn / Hon Hai               | 1         | 5.26%   |
| Edimax Technology               | 1         | 5.26%   |
| Cambridge Silicon Radio         | 1         | 5.26%   |
| Broadcom                        | 1         | 5.26%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 15.79%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 15.79%  |
| Intel Bluetooth wireless interface                  | 2         | 10.53%  |
| Intel AX200 Bluetooth                               | 2         | 10.53%  |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 5.26%   |
| Lite-On Bluetooth Device                            | 1         | 5.26%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 5.26%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 5.26%   |
| Intel AX201 Bluetooth                               | 1         | 5.26%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 5.26%   |
| Edimax Bluetooth Adapter                            | 1         | 5.26%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 5.26%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 5.26%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel           | 16        | 61.54%  |
| AMD             | 7         | 26.92%  |
| Nvidia          | 1         | 3.85%   |
| Hewlett-Packard | 1         | 3.85%   |
| Astro Gaming    | 1         | 3.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 11.76%  |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 8.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 8.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 5.88%   |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 5.88%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 5.88%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 5.88%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 5.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 5.88%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 2.94%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 2.94%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 2.94%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 2.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 2.94%   |
| Hewlett-Packard USB Audio                                                  | 1         | 2.94%   |
| Astro Gaming Astro A50                                                     | 1         | 2.94%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1         | 2.94%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 1         | 2.94%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1         | 2.94%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 1         | 2.94%   |
| AMD FCH Azalia Controller                                                  | 1         | 2.94%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 36.36%  |
| Micron Technology   | 4         | 18.18%  |
| Crucial             | 4         | 18.18%  |
| Kingston            | 3         | 13.64%  |
| SK hynix            | 2         | 9.09%   |
| Nanya Technology    | 1         | 4.55%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 9.09%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 4.55%   |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 4.55%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 1         | 4.55%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 4.55%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 1         | 4.55%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s           | 1         | 4.55%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 4.55%   |
| Samsung RAM K4UBE3D4AA-MGCL 8GB Row Of Chips LPDDR4 4267MT/s     | 1         | 4.55%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 1         | 4.55%   |
| Micron RAM Module 16GB SODIMM DDR4 3200MT/s                      | 1         | 4.55%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 1         | 4.55%   |
| Micron RAM 4ATF25664HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 1         | 4.55%   |
| Micron RAM ...d 4096MB SODIMM DDR3 1067MT/s                      | 1         | 4.55%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s             | 1         | 4.55%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s           | 1         | 4.55%   |
| Kingston RAM 99U5663-007.A00G 16GB SODIMM DDR4 2667MT/s          | 1         | 4.55%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s           | 1         | 4.55%   |
| Crucial RAM CT4G3S1067M.C16FKD 4GB SODIMM DDR3 1066MT/s          | 1         | 4.55%   |
| Crucial RAM CT32G48C40S5.M16A1 32GB SODIMM DDR5 4800MT/s         | 1         | 4.55%   |
| Crucial RAM CT16G4SFD824A.C16FDD 16GB SODIMM DDR4 2400MT/s       | 1         | 4.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 9         | 50%     |
| DDR3   | 5         | 27.78%  |
| SDRAM  | 1         | 5.56%   |
| LPDDR4 | 1         | 5.56%   |
| LPDDR3 | 1         | 5.56%   |
| DDR5   | 1         | 5.56%   |

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
| 8192  | 6         | 31.58%  |
| 16384 | 3         | 15.79%  |
| 32768 | 1         | 5.26%   |
| 2048  | 1         | 5.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 5         | 25%     |
| 3200  | 3         | 15%     |
| 2400  | 3         | 15%     |
| 1600  | 2         | 10%     |
| 4800  | 1         | 5%      |
| 4267  | 1         | 5%      |
| 4199  | 1         | 5%      |
| 1867  | 1         | 5%      |
| 1334  | 1         | 5%      |
| 1067  | 1         | 5%      |
| 1066  | 1         | 5%      |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Notebooks | Percent |
|------------------------|-----------|---------|
| HP DeskJet 3630 series | 1         | 100%    |

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
| Chicony Electronics                    | 8         | 42.11%  |
| IMC Networks                           | 3         | 15.79%  |
| Suyin                                  | 1         | 5.26%   |
| Silicon Motion                         | 1         | 5.26%   |
| Realtek Semiconductor                  | 1         | 5.26%   |
| Quanta                                 | 1         | 5.26%   |
| Primax Electronics                     | 1         | 5.26%   |
| Microdia                               | 1         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 5.26%   |
| Bison Electronics                      | 1         | 5.26%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                              | 4         | 21.05%  |
| Suyin 1.3M Front                                               | 1         | 5.26%   |
| Silicon Motion USB 2.0 PC Cam                                  | 1         | 5.26%   |
| Realtek Integrated_Webcam_HD                                   | 1         | 5.26%   |
| Quanta HP Webcam                                               | 1         | 5.26%   |
| Primax Villem                                                  | 1         | 5.26%   |
| Microdia Integrated_Webcam_HD                                  | 1         | 5.26%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 1         | 5.26%   |
| IMC Networks SunplusIT Integrated Camera                       | 1         | 5.26%   |
| IMC Networks Integrated Camera                                 | 1         | 5.26%   |
| Chicony Integrated Camera                                      | 1         | 5.26%   |
| Chicony HP Webcam                                              | 1         | 5.26%   |
| Chicony HP HD Camera                                           | 1         | 5.26%   |
| Chicony HP 5MP Camera                                          | 1         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 5.26%   |
| Bison Integrated Camera                                        | 1         | 5.26%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 3         | 50%     |
| Synaptics             | 2         | 33.33%  |
| LighTuning Technology | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader              | 1         | 16.67%  |
| Validity Sensors VFS451 Fingerprint Reader               | 1         | 16.67%  |
| Validity Sensors Synaptics WBDI                          | 1         | 16.67%  |
| Synaptics Metallica MOH Touch Fingerprint Reader         | 1         | 16.67%  |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 16.67%  |
| LighTuning EgisTec Touch Fingerprint Sensor              | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Broadcom 5880 | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 13        | 61.9%   |
| 1     | 7         | 33.33%  |
| 2     | 1         | 4.76%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 6         | 66.67%  |
| Net/wireless       | 1         | 11.11%  |
| Graphics card      | 1         | 11.11%  |
| Chipcard           | 1         | 11.11%  |

