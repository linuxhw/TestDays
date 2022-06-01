Linux in Kenya - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------

A project to collect tested hardware configurations for Linux in Kenya.

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

Total: 37

| Vendor   | Model                    | Probe                                                      | Date         |
|----------|--------------------------|------------------------------------------------------------|--------------|
| Lenovo   | NOK                      | [e7a84a12e6](https://linux-hardware.org/?probe=e7a84a12e6) | May 16, 2022 |
| Dell     | 0773VG A02               | [ec8ec429fc](https://linux-hardware.org/?probe=ec8ec429fc) | Mar 07, 2022 |
| Dell     | 055H3G A01               | [7e00973942](https://linux-hardware.org/?probe=7e00973942) | Mar 06, 2022 |
| Dell     | 055H3G A01               | [05f63f2396](https://linux-hardware.org/?probe=05f63f2396) | Feb 04, 2022 |
| Gigabyte | H110M-A-CF               | [e6a3a69257](https://linux-hardware.org/?probe=e6a3a69257) | Jan 29, 2022 |
| HP       | 83E0                     | [4a54d6921c](https://linux-hardware.org/?probe=4a54d6921c) | Jan 13, 2022 |
| Gigabyte | B450 I AORUS PRO WIFI-CF | [ee1387e206](https://linux-hardware.org/?probe=ee1387e206) | Nov 26, 2021 |
| Dell     | 0R790T A00               | [b5a01103fd](https://linux-hardware.org/?probe=b5a01103fd) | Sep 14, 2021 |
| Dell     | 0R790T A00               | [a5290e7cb6](https://linux-hardware.org/?probe=a5290e7cb6) | Sep 14, 2021 |
| Acer     | Veriton X680G            | [3b8774337b](https://linux-hardware.org/?probe=3b8774337b) | Jul 23, 2021 |
| MSI      | B450 TOMAHAWK            | [8513c961a4](https://linux-hardware.org/?probe=8513c961a4) | Jun 21, 2021 |
| Dell     | 0HN7XN A01               | [2c35ee27d9](https://linux-hardware.org/?probe=2c35ee27d9) | May 20, 2021 |
| Dell     | 0773VG A02               | [a4d5cb7e11](https://linux-hardware.org/?probe=a4d5cb7e11) | Mar 10, 2021 |
| MSI      | B450 TOMAHAWK            | [f56f2da985](https://linux-hardware.org/?probe=f56f2da985) | Jan 28, 2021 |
| HP       | 3396                     | [12e6dc258e](https://linux-hardware.org/?probe=12e6dc258e) | Oct 31, 2020 |
| HP       | 3396                     | [876ee024dc](https://linux-hardware.org/?probe=876ee024dc) | Oct 31, 2020 |
| MSI      | B450 TOMAHAWK            | [6ea891ad6b](https://linux-hardware.org/?probe=6ea891ad6b) | Oct 13, 2020 |
| Dell     | 0773VG A02               | [8307343ab3](https://linux-hardware.org/?probe=8307343ab3) | Oct 09, 2020 |
| Dell     | 0773VG A02               | [2c6d570678](https://linux-hardware.org/?probe=2c6d570678) | Oct 09, 2020 |
| MSI      | B450 TOMAHAWK            | [dc38793462](https://linux-hardware.org/?probe=dc38793462) | Sep 08, 2020 |
| MSI      | 0A90                     | [4f8d53458d](https://linux-hardware.org/?probe=4f8d53458d) | Aug 11, 2020 |
| MSI      | 0A90                     | [04bdc6569a](https://linux-hardware.org/?probe=04bdc6569a) | Aug 09, 2020 |
| MSI      | 2AE0                     | [54a32fea6e](https://linux-hardware.org/?probe=54a32fea6e) | Aug 02, 2020 |
| Dell     | 0VNP2H A00               | [de21e4bff4](https://linux-hardware.org/?probe=de21e4bff4) | Jul 04, 2020 |
| HP       | 0AA8h                    | [e60c30f572](https://linux-hardware.org/?probe=e60c30f572) | Jun 25, 2020 |
| HP       | 0AA8h                    | [4017115305](https://linux-hardware.org/?probe=4017115305) | Jun 19, 2020 |
| HP       | 0AA8h                    | [752505c134](https://linux-hardware.org/?probe=752505c134) | Jun 17, 2020 |
| HP       | 3032h                    | [8aa1dd8ecd](https://linux-hardware.org/?probe=8aa1dd8ecd) | Jun 13, 2020 |
| Dell     | 0PU052                   | [5d99be49f0](https://linux-hardware.org/?probe=5d99be49f0) | May 31, 2020 |
| Dell     | 0PU052                   | [6b4292fc06](https://linux-hardware.org/?probe=6b4292fc06) | May 30, 2020 |
| Dell     | 0G214D A00               | [a8caa085de](https://linux-hardware.org/?probe=a8caa085de) | May 04, 2020 |
| Gigabyte | Z68XP-UD3                | [a26feb7507](https://linux-hardware.org/?probe=a26feb7507) | Apr 18, 2020 |
| HP       | 0B4Ch D                  | [2807f4c586](https://linux-hardware.org/?probe=2807f4c586) | Mar 12, 2020 |
| HP       | 09F0h                    | [bff6b4f556](https://linux-hardware.org/?probe=bff6b4f556) | Jan 21, 2020 |
| HP       | 09F0h                    | [ad09a9a9d4](https://linux-hardware.org/?probe=ad09a9a9d4) | Jan 21, 2020 |
| HP       | 0AA0h                    | [1787c13656](https://linux-hardware.org/?probe=1787c13656) | Jun 15, 2019 |
| ASUSTek  | M5A97 R2.0               | [304aa59840](https://linux-hardware.org/?probe=304aa59840) | Dec 14, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Ubuntu 20.04        | 8        | 28.57%  |
| ArcoLinux Rolling   | 3        | 10.71%  |
| Zorin 15            | 2        | 7.14%   |
| Ubuntu 18.04        | 2        | 7.14%   |
| Ubuntu Studio 21.10 | 1        | 3.57%   |
| Pop!_OS 20.10       | 1        | 3.57%   |
| Pop!_OS 20.04       | 1        | 3.57%   |
| OpenMandriva 4.2    | 1        | 3.57%   |
| Mageia 6            | 1        | 3.57%   |
| Lubuntu 20.10       | 1        | 3.57%   |
| Kali 2020.1         | 1        | 3.57%   |
| Fedora 34           | 1        | 3.57%   |
| Fedora 33           | 1        | 3.57%   |
| Fedora 32           | 1        | 3.57%   |
| Endless 3.8.3       | 1        | 3.57%   |
| Elementary 6        | 1        | 3.57%   |
| BlackPanther 18.1   | 1        | 3.57%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 10       | 38.46%  |
| ArcoLinux     | 3        | 11.54%  |
| Zorin         | 2        | 7.69%   |
| Fedora        | 2        | 7.69%   |
| Ubuntu Studio | 1        | 3.85%   |
| Pop!_OS       | 1        | 3.85%   |
| OpenMandriva  | 1        | 3.85%   |
| Mageia        | 1        | 3.85%   |
| Lubuntu       | 1        | 3.85%   |
| Kali          | 1        | 3.85%   |
| Endless       | 1        | 3.85%   |
| Elementary    | 1        | 3.85%   |
| BlackPanther  | 1        | 3.85%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.4.0-42-generic         | 2        | 6.9%    |
| 5.8.4-200.fc32.x86_64    | 1        | 3.45%   |
| 5.8.13-200.fc32.x86_64   | 1        | 3.45%   |
| 5.8.0-7642-generic       | 1        | 3.45%   |
| 5.8.0-63-generic         | 1        | 3.45%   |
| 5.8.0-53-generic         | 1        | 3.45%   |
| 5.8.0-43-generic         | 1        | 3.45%   |
| 5.4.0-7642-generic       | 1        | 3.45%   |
| 5.4.0-37-generic         | 1        | 3.45%   |
| 5.4.0-33-generic         | 1        | 3.45%   |
| 5.4.0-28-generic         | 1        | 3.45%   |
| 5.4.0-19-generic         | 1        | 3.45%   |
| 5.3.0-kali2-amd64        | 1        | 3.45%   |
| 5.3.0-62-generic         | 1        | 3.45%   |
| 5.3.0-28-generic         | 1        | 3.45%   |
| 5.16.2-zen1-1-zen        | 1        | 3.45%   |
| 5.15.26-1-lts            | 1        | 3.45%   |
| 5.15.10-arch1-1          | 1        | 3.45%   |
| 5.13.0-30-generic        | 1        | 3.45%   |
| 5.13.0-28-lowlatency     | 1        | 3.45%   |
| 5.12.11-300.fc34.x86_64  | 1        | 3.45%   |
| 5.11.0-40-generic        | 1        | 3.45%   |
| 5.10.14-desktop-1omv4002 | 1        | 3.45%   |
| 5.10.10-200.fc33.x86_64  | 1        | 3.45%   |
| 5.0.0-37-generic         | 1        | 3.45%   |
| 4.9.56-server-1.mga6     | 1        | 3.45%   |
| 4.18.16-desktop-1bP      | 1        | 3.45%   |
| 4.15.0-51-generic        | 1        | 3.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 7        | 24.14%  |
| 5.8.0   | 4        | 13.79%  |
| 5.3.0   | 3        | 10.34%  |
| 5.13.0  | 2        | 6.9%    |
| 5.8.4   | 1        | 3.45%   |
| 5.8.13  | 1        | 3.45%   |
| 5.16.2  | 1        | 3.45%   |
| 5.15.26 | 1        | 3.45%   |
| 5.15.10 | 1        | 3.45%   |
| 5.12.11 | 1        | 3.45%   |
| 5.11.0  | 1        | 3.45%   |
| 5.10.14 | 1        | 3.45%   |
| 5.10.10 | 1        | 3.45%   |
| 5.0.0   | 1        | 3.45%   |
| 4.9.56  | 1        | 3.45%   |
| 4.18.16 | 1        | 3.45%   |
| 4.15.0  | 1        | 3.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 7        | 25%     |
| 5.8     | 5        | 17.86%  |
| 5.3     | 3        | 10.71%  |
| 5.15    | 2        | 7.14%   |
| 5.13    | 2        | 7.14%   |
| 5.10    | 2        | 7.14%   |
| 5.16    | 1        | 3.57%   |
| 5.12    | 1        | 3.57%   |
| 5.11    | 1        | 3.57%   |
| 5.0     | 1        | 3.57%   |
| 4.9     | 1        | 3.57%   |
| 4.18    | 1        | 3.57%   |
| 4.15    | 1        | 3.57%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 25       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| GNOME    | 15       | 57.69%  |
| KDE5     | 4        | 15.38%  |
| Unknown  | 2        | 7.69%   |
| Pantheon | 1        | 3.85%   |
| LXQt     | 1        | 3.85%   |
| dwm      | 1        | 3.85%   |
| Cinnamon | 1        | 3.85%   |
| awesome  | 1        | 3.85%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 21       | 84%     |
| Wayland | 2        | 8%      |
| Tty     | 1        | 4%      |
| Unknown | 1        | 4%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 14       | 53.85%  |
| SDDM    | 6        | 23.08%  |
| LightDM | 3        | 11.54%  |
| GDM     | 2        | 7.69%   |
| GDM3    | 1        | 3.85%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 19       | 76%     |
| en_GB   | 3        | 12%     |
| Unknown | 3        | 12%     |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 18       | 72%     |
| EFI  | 7        | 28%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 19       | 73.08%  |
| Overlay | 4        | 15.38%  |
| Btrfs   | 2        | 7.69%   |
| Unknown | 1        | 3.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 16       | 64%     |
| GPT     | 5        | 20%     |
| MBR     | 4        | 16%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 76%     |
| Yes       | 6        | 24%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 56%     |
| Yes       | 11       | 44%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 8        | 32%     |
| Hewlett-Packard     | 7        | 28%     |
| MSI                 | 4        | 16%     |
| Gigabyte Technology | 3        | 12%     |
| Lenovo              | 1        | 4%      |
| ASUSTek Computer    | 1        | 4%      |
| Acer                | 1        | 4%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| MSI MS-7C02                            | 2        | 8%      |
| Dell OptiPlex 7010                     | 2        | 8%      |
| MSI 500-007A                           | 1        | 4%      |
| MSI 0A90                               | 1        | 4%      |
| Lenovo ThinkCentre E73 10AS00CVUM      | 1        | 4%      |
| HP Z400 Workstation                    | 1        | 4%      |
| HP xw4600 Workstation                  | 1        | 4%      |
| HP EliteDesk 800 G4 TWR                | 1        | 4%      |
| HP Compaq Elite 8300 CMT               | 1        | 4%      |
| HP Compaq dc7900 Convertible Minitower | 1        | 4%      |
| HP Compaq dc7800 Small Form Factor     | 1        | 4%      |
| HP Compaq dc7600 Convertible Minitower | 1        | 4%      |
| Gigabyte Z68XP-UD3                     | 1        | 4%      |
| Gigabyte H110M-A                       | 1        | 4%      |
| Gigabyte B450 I AORUS PRO WIFI         | 1        | 4%      |
| Dell OptiPlex 990                      | 1        | 4%      |
| Dell OptiPlex 760                      | 1        | 4%      |
| Dell OptiPlex 755                      | 1        | 4%      |
| Dell OptiPlex 7050                     | 1        | 4%      |
| Dell OptiPlex 5040                     | 1        | 4%      |
| Dell OptiPlex 380                      | 1        | 4%      |
| ASUS M5A97 R2.0                        | 1        | 4%      |
| Acer Veriton X680G                     | 1        | 4%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Dell OptiPlex      | 8        | 32%     |
| HP Compaq          | 4        | 16%     |
| MSI MS-7C02        | 2        | 8%      |
| MSI 500-007A       | 1        | 4%      |
| MSI 0A90           | 1        | 4%      |
| Lenovo ThinkCentre | 1        | 4%      |
| HP Z400            | 1        | 4%      |
| HP xw4600          | 1        | 4%      |
| HP EliteDesk       | 1        | 4%      |
| Gigabyte Z68XP-UD3 | 1        | 4%      |
| Gigabyte H110M-A   | 1        | 4%      |
| Gigabyte B450      | 1        | 4%      |
| ASUS M5A97         | 1        | 4%      |
| Acer Veriton       | 1        | 4%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 5        | 20%     |
| 2010 | 3        | 12%     |
| 2008 | 3        | 12%     |
| 2007 | 3        | 12%     |
| 2013 | 2        | 8%      |
| 2012 | 2        | 8%      |
| 2011 | 2        | 8%      |
| 2019 | 1        | 4%      |
| 2016 | 1        | 4%      |
| 2015 | 1        | 4%      |
| 2014 | 1        | 4%      |
| 2005 | 1        | 4%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 25       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 24       | 92.31%  |
| Enabled  | 2        | 7.69%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 25       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 3.01-4.0   | 5        | 19.23%  |
| 16.01-24.0 | 5        | 19.23%  |
| 8.01-16.0  | 5        | 19.23%  |
| 32.01-64.0 | 4        | 15.38%  |
| 1.01-2.0   | 4        | 15.38%  |
| 4.01-8.0   | 2        | 7.69%   |
| 2.01-3.0   | 1        | 3.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 10       | 37.04%  |
| 2.01-3.0  | 6        | 22.22%  |
| 0.51-1.0  | 4        | 14.81%  |
| 4.01-8.0  | 3        | 11.11%  |
| 3.01-4.0  | 2        | 7.41%   |
| 8.01-16.0 | 1        | 3.7%    |
| 0.01-0.5  | 1        | 3.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 13       | 52%     |
| 2      | 8        | 32%     |
| 6      | 1        | 4%      |
| 5      | 1        | 4%      |
| 4      | 1        | 4%      |
| 3      | 1        | 4%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 14       | 56%     |
| No        | 11       | 44%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 24       | 96%     |
| No        | 1        | 4%      |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 60%     |
| Yes       | 10       | 40%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 92%     |
| Yes       | 2        | 8%      |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Kenya   | 25       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City    | Desktops | Percent |
|---------|----------|---------|
| Nairobi | 24       | 92.31%  |
| Nakuru  | 1        | 3.85%   |
| Mombasa | 1        | 3.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 16       | 20     | 36.36%  |
| WDC                 | 7        | 9      | 15.91%  |
| Toshiba             | 3        | 3      | 6.82%   |
| SPCC                | 3        | 7      | 6.82%   |
| Team                | 2        | 2      | 4.55%   |
| Samsung Electronics | 2        | 4      | 4.55%   |
| Hitachi             | 2        | 2      | 4.55%   |
| HGST                | 2        | 3      | 4.55%   |
| Unknown             | 1        | 1      | 2.27%   |
| SanDisk             | 1        | 1      | 2.27%   |
| LITEON              | 1        | 1      | 2.27%   |
| Intel               | 1        | 1      | 2.27%   |
| HUAWEI              | 1        | 1      | 2.27%   |
| China               | 1        | 1      | 2.27%   |
| Unknown             | 1        | 1      | 2.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| WDC WD3200AAJS-56M0A0 320GB        | 2        | 4.08%   |
| Toshiba DT01ACA100 1TB             | 2        | 4.08%   |
| Team T253X2001T 1024GB SSD         | 2        | 4.08%   |
| SPCC Solid State Disk 256GB        | 2        | 4.08%   |
| SPCC M.2 PCIe SSD 512GB            | 2        | 4.08%   |
| Seagate ST500VT000-1BS142 500GB    | 2        | 4.08%   |
| Seagate ST3320418AS 320GB          | 2        | 4.08%   |
| Seagate ST2000DM008-2FR102 2TB     | 2        | 4.08%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2        | 4.08%   |
| Samsung SSD 840 EVO 250GB          | 2        | 4.08%   |
| WDC WD800GD-75FLC3 80GB            | 1        | 2.04%   |
| WDC WD5000AVDS-63U7B1 500GB        | 1        | 2.04%   |
| WDC WD5000AAKX-08U6AA0 500GB       | 1        | 2.04%   |
| WDC WD3200AAJS-56B4A0 320GB        | 1        | 2.04%   |
| WDC WD3200AAJS-00B4A0 320GB        | 1        | 2.04%   |
| WDC WD2500AAKX-08U6AA0 250GB       | 1        | 2.04%   |
| Unknown L200 Hard drive 2TB        | 1        | 2.04%   |
| Toshiba DT01ABA100V 1TB            | 1        | 2.04%   |
| Seagate ST_M13FQBL QNR 4GB         | 1        | 2.04%   |
| Seagate ST500DM002-1BD142 500GB    | 1        | 2.04%   |
| Seagate ST380817AS 80GB            | 1        | 2.04%   |
| Seagate ST3808110AS 80GB           | 1        | 2.04%   |
| Seagate ST380013AS 80GB            | 1        | 2.04%   |
| Seagate ST3250318AS 250GB          | 1        | 2.04%   |
| Seagate ST3250312AS 250GB          | 1        | 2.04%   |
| Seagate ST3160812AS Q 160GB        | 1        | 2.04%   |
| Seagate ST3000DM001-1CH166 3TB     | 1        | 2.04%   |
| Seagate ST2000DM001-1CH164 2TB     | 1        | 2.04%   |
| Seagate ST1000VM002-1CT162 1TB     | 1        | 2.04%   |
| SanDisk SDSSDA120G 120GB           | 1        | 2.04%   |
| LITEON IT LCS-128L9S-HP 128GB SSD  | 1        | 2.04%   |
| Intel SSDSC2BB160G4 160GB          | 1        | 2.04%   |
| HUAWEI SD Storage 8GB              | 1        | 2.04%   |
| Hitachi HDS721032CLA362 320GB      | 1        | 2.04%   |
| Hitachi HDS721025CLA382 250GB      | 1        | 2.04%   |
| HGST HUS724020ALE641 2TB           | 1        | 2.04%   |
| HGST HTS721010A9 1TB               | 1        | 2.04%   |
| China SATA3 120GB SSD              | 1        | 2.04%   |
| Unknown                            | 1        | 2.04%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 15       | 19     | 48.39%  |
| WDC     | 7        | 9      | 22.58%  |
| Toshiba | 3        | 3      | 9.68%   |
| Hitachi | 2        | 2      | 6.45%   |
| HGST    | 2        | 3      | 6.45%   |
| Unknown | 1        | 1      | 3.23%   |
| Unknown | 1        | 1      | 3.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Team                | 2        | 2      | 20%     |
| SPCC                | 2        | 3      | 20%     |
| Samsung Electronics | 2        | 4      | 20%     |
| SanDisk             | 1        | 1      | 10%     |
| LITEON              | 1        | 1      | 10%     |
| Intel               | 1        | 1      | 10%     |
| China               | 1        | 1      | 10%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 23       | 38     | 67.65%  |
| SSD     | 7        | 13     | 20.59%  |
| NVMe    | 2        | 4      | 5.88%   |
| Unknown | 2        | 2      | 5.88%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 25       | 52     | 89.29%  |
| NVMe | 2        | 4      | 7.14%   |
| SAS  | 1        | 1      | 3.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 21       | 34     | 63.64%  |
| 0.51-1.0   | 7        | 9      | 21.21%  |
| 1.01-2.0   | 4        | 7      | 12.12%  |
| 2.01-3.0   | 1        | 1      | 3.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 6        | 20.69%  |
| 1001-2000      | 6        | 20.69%  |
| 51-100         | 5        | 17.24%  |
| More than 3000 | 3        | 10.34%  |
| 251-500        | 3        | 10.34%  |
| 501-1000       | 2        | 6.9%    |
| 21-50          | 1        | 3.45%   |
| 2001-3000      | 1        | 3.45%   |
| 1-20           | 1        | 3.45%   |
| Unknown        | 1        | 3.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 12       | 41.38%  |
| 1001-2000 | 4        | 13.79%  |
| 21-50     | 3        | 10.34%  |
| 101-250   | 3        | 10.34%  |
| 251-500   | 2        | 6.9%    |
| 501-1000  | 2        | 6.9%    |
| 51-100    | 2        | 6.9%    |
| Unknown   | 1        | 3.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD3200AAJS-56M0A0 320GB        | 1        | 1      | 25%     |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 1      | 25%     |
| HGST HTS721010A9 1TB               | 1        | 2      | 25%     |
| Unknown                            | 1        | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 25%     |
| Seagate | 1        | 1      | 25%     |
| HGST    | 1        | 2      | 25%     |
| Unknown | 1        | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 25%     |
| Seagate | 1        | 1      | 25%     |
| HGST    | 1        | 2      | 25%     |
| Unknown | 1        | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 4        | 5      | 100%    |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 17       | 22     | 56.67%  |
| Works    | 9        | 30     | 30%     |
| Malfunc  | 4        | 5      | 13.33%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 20       | 66.67%  |
| AMD                       | 5        | 16.67%  |
| Silicon Motion            | 1        | 3.33%   |
| Realtek Semiconductor     | 1        | 3.33%   |
| Marvell Technology Group  | 1        | 3.33%   |
| LSI Logic / Symbios Logic | 1        | 3.33%   |
| Broadcom / LSI            | 1        | 3.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel SATA Controller [RAID mode]                                                       | 4        | 9.3%    |
| AMD FCH SATA Controller [AHCI mode]                                                     | 4        | 9.3%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 6.98%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3        | 6.98%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 6.98%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2        | 4.65%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 4.65%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2        | 4.65%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 4.65%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 2.33%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 1        | 2.33%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                                   | 1        | 2.33%   |
| LSI Logic / Symbios Logic SAS1064ET PCI-Express Fusion-MPT SAS                          | 1        | 2.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 2.33%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 2.33%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1        | 2.33%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1        | 2.33%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1        | 2.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1        | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 2.33%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 1        | 2.33%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 2.33%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 2.33%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 1        | 2.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1        | 2.33%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 2.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 16       | 47.06%  |
| IDE  | 10       | 29.41%  |
| RAID | 5        | 14.71%  |
| NVMe | 2        | 5.88%   |
| SCSI | 1        | 2.94%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 20       | 80%     |
| AMD    | 5        | 20%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-6500 CPU @ 3.20GHz            | 2        | 8%      |
| AMD Ryzen 5 1600 Six-Core Processor         | 2        | 8%      |
| Intel Xeon CPU W3680 @ 3.33GHz              | 1        | 4%      |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1        | 4%      |
| Intel Pentium 4 CPU 3.20GHz                 | 1        | 4%      |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 4%      |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 4%      |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 4%      |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 4%      |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 4%      |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 4%      |
| Intel Core i3-4160 CPU @ 3.60GHz            | 1        | 4%      |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1        | 4%      |
| Intel Core i3-2100 CPU @ 3.10GHz            | 1        | 4%      |
| Intel Core i3 CPU 550 @ 3.20GHz             | 1        | 4%      |
| Intel Core 2 Quad CPU @ 2.40GHz             | 1        | 4%      |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 1        | 4%      |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 1        | 4%      |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 1        | 4%      |
| Intel Core 2 CPU 6420 @ 2.13GHz             | 1        | 4%      |
| AMD Ryzen 7 2700 Eight-Core Processor       | 1        | 4%      |
| AMD FX-6300 Six-Core Processor              | 1        | 4%      |
| AMD A4-5300 APU with Radeon HD Graphics     | 1        | 4%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 4        | 16%     |
| Intel Core i3           | 4        | 16%     |
| Intel Core i7           | 3        | 12%     |
| Intel Core 2 Duo        | 3        | 12%     |
| Intel Pentium 4         | 2        | 8%      |
| AMD Ryzen 5             | 2        | 8%      |
| Intel Xeon              | 1        | 4%      |
| Intel Pentium Dual-Core | 1        | 4%      |
| Intel Core 2 Quad       | 1        | 4%      |
| Intel Core 2            | 1        | 4%      |
| AMD Ryzen 7             | 1        | 4%      |
| AMD FX                  | 1        | 4%      |
| AMD A4                  | 1        | 4%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 9        | 36%     |
| 4      | 7        | 28%     |
| 6      | 4        | 16%     |
| 1      | 3        | 12%     |
| 8      | 1        | 4%      |
| 3      | 1        | 4%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 25       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 14       | 56%     |
| 1      | 11       | 44%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 25       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x506e3    | 3        | 11.54%  |
| 0x306a9    | 3        | 11.54%  |
| 0x0800820d | 3        | 11.54%  |
| 0x206a7    | 2        | 7.69%   |
| 0x1067a    | 2        | 7.69%   |
| 0x10676    | 2        | 7.69%   |
| Unknown    | 2        | 7.69%   |
| 0xf65      | 1        | 3.85%   |
| 0xf43      | 1        | 3.85%   |
| 0x906ea    | 1        | 3.85%   |
| 0x6f7      | 1        | 3.85%   |
| 0x6f6      | 1        | 3.85%   |
| 0x206c2    | 1        | 3.85%   |
| 0x20655    | 1        | 3.85%   |
| 0x06001119 | 1        | 3.85%   |
| 0x0600084f | 1        | 3.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Penryn      | 4        | 16%     |
| Zen+        | 3        | 12%     |
| Skylake     | 3        | 12%     |
| IvyBridge   | 3        | 12%     |
| Westmere    | 2        | 8%      |
| SandyBridge | 2        | 8%      |
| Piledriver  | 2        | 8%      |
| NetBurst    | 2        | 8%      |
| Core        | 2        | 8%      |
| KabyLake    | 1        | 4%      |
| Haswell     | 1        | 4%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 13       | 44.83%  |
| Nvidia | 9        | 31.03%  |
| AMD    | 7        | 24.14%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 4        | 13.79%  |
| Nvidia GK208B [GeForce GT 710]                                            | 3        | 10.34%  |
| Nvidia GT218 [GeForce 210]                                                | 2        | 6.9%    |
| Intel HD Graphics 530                                                     | 2        | 6.9%    |
| Intel 4 Series Chipset Integrated Graphics Controller                     | 2        | 6.9%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2        | 6.9%    |
| Nvidia GK208B [GeForce GT 730]                                            | 1        | 3.45%   |
| Nvidia GK104 [GeForce GTX 760]                                            | 1        | 3.45%   |
| Nvidia GF119 [GeForce GT 610]                                             | 1        | 3.45%   |
| Nvidia G94GL [Quadro FX 1800]                                             | 1        | 3.45%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller          | 1        | 3.45%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                    | 1        | 3.45%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 1        | 3.45%   |
| Intel 82Q35 Express Integrated Graphics Controller                        | 1        | 3.45%   |
| Intel 82946GZ/GL Integrated Graphics Controller                           | 1        | 3.45%   |
| Intel 82945G/GZ Integrated Graphics Controller                            | 1        | 3.45%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller | 1        | 3.45%   |
| AMD Trinity 2 [Radeon HD 7480D]                                           | 1        | 3.45%   |
| AMD Pitcairn PRO [Radeon HD 7850 / R7 265 / R9 270 1024SP]                | 1        | 3.45%   |
| AMD Park [Mobility Radeon HD 5430]                                        | 1        | 3.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 10       | 38.46%  |
| 1 x Nvidia     | 8        | 30.77%  |
| 1 x AMD        | 7        | 26.92%  |
| Intel + Nvidia | 1        | 3.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 23       | 92%     |
| Proprietary | 2        | 8%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 12       | 48%     |
| 0.51-1.0   | 5        | 20%     |
| 3.01-4.0   | 3        | 12%     |
| 1.01-2.0   | 3        | 12%     |
| 7.01-8.0   | 2        | 8%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 7        | 25.93%  |
| Dell                | 7        | 25.93%  |
| Sony                | 3        | 11.11%  |
| Lenovo              | 3        | 11.11%  |
| Samsung Electronics | 2        | 7.41%   |
| VIE                 | 1        | 3.7%    |
| Unknown (XXX)       | 1        | 3.7%    |
| Unknown             | 1        | 3.7%    |
| Hitachi             | 1        | 3.7%    |
| BenQ                | 1        | 3.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics S22E450 SAM0C7A 1920x1080 477x268mm 21.5-inch     | 2        | 6.67%   |
| Lenovo T2224zD LEN60CB 1920x1080 476x267mm 21.5-inch                  | 2        | 6.67%   |
| VIE LED MONITOR VIE2302 1920x1080 473x296mm 22.0-inch                 | 1        | 3.33%   |
| Unknown LCD Monitor Hitachi Engineering Company Ltd HISENSE 3200x1080 | 1        | 3.33%   |
| Unknown (XXX) SMART TV XXX2851 3840x2160                              | 1        | 3.33%   |
| Sony TV SNYEF03 1600x900                                              | 1        | 3.33%   |
| Sony TV SNYDC02 1920x1080 930x523mm 42.0-inch                         | 1        | 3.33%   |
| Sony TV SNY0902 1360x768                                              | 1        | 3.33%   |
| Lenovo LEN LI1931ewA LEN65A1 1366x768 409x230mm 18.5-inch             | 1        | 3.33%   |
| Lenovo LEN E2054A LEN60DF 1440x900 420x260mm 19.4-inch                | 1        | 3.33%   |
| Hitachi HDMI HEC0030 1920x1080 580x330mm 26.3-inch                    | 1        | 3.33%   |
| Hewlett-Packard Z24i HWP309E 1920x1200 520x320mm 24.0-inch            | 1        | 3.33%   |
| Hewlett-Packard P222va HWP322C 1920x1080 477x268mm 21.5-inch          | 1        | 3.33%   |
| Hewlett-Packard LE2202x HWP2966 1920x1080 476x268mm 21.5-inch         | 1        | 3.33%   |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch          | 1        | 3.33%   |
| Hewlett-Packard LCD Monitor L1710                                     | 1        | 3.33%   |
| Hewlett-Packard LA2206 HWP2948 1920x1080 476x268mm 21.5-inch          | 1        | 3.33%   |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch           | 1        | 3.33%   |
| Hewlett-Packard E222 HWP3262 1920x1080 480x270mm 21.7-inch            | 1        | 3.33%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                      | 1        | 3.33%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 1        | 3.33%   |
| Dell P2314T DEL40A0 1920x1080 509x286mm 23.0-inch                     | 1        | 3.33%   |
| Dell E2011H DEL406B 1600x900 443x249mm 20.0-inch                      | 1        | 3.33%   |
| Dell E1910H DELD023 1366x768 410x230mm 18.5-inch                      | 1        | 3.33%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                     | 1        | 3.33%   |
| Dell 1908FP DEL4026 1280x1024 376x301mm 19.0-inch                     | 1        | 3.33%   |
| Dell 1908FP DEL4025 1280x1024 376x301mm 19.0-inch                     | 1        | 3.33%   |
| BenQ LCD BNQ8024 2560x1440 597x336mm 27.0-inch                        | 1        | 3.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 10       | 37.04%  |
| 1280x1024 (SXGA)  | 4        | 14.81%  |
| 3840x2160 (4K)    | 2        | 7.41%   |
| 1920x1200 (WUXGA) | 2        | 7.41%   |
| 1600x900 (HD+)    | 2        | 7.41%   |
| 1440x900 (WXGA+)  | 2        | 7.41%   |
| 1366x768 (WXGA)   | 2        | 7.41%   |
| 3200x1080         | 1        | 3.7%    |
| 2560x1440 (QHD)   | 1        | 3.7%    |
| Unknown           | 1        | 3.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 6        | 22.22%  |
| 19      | 4        | 14.81%  |
| 24      | 3        | 11.11%  |
| 72      | 2        | 7.41%   |
| 18      | 2        | 7.41%   |
| 17      | 2        | 7.41%   |
| 84      | 1        | 3.7%    |
| 54      | 1        | 3.7%    |
| 46      | 1        | 3.7%    |
| 27      | 1        | 3.7%    |
| 23      | 1        | 3.7%    |
| 22      | 1        | 3.7%    |
| 20      | 1        | 3.7%    |
| Unknown | 1        | 3.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 9        | 37.5%   |
| 501-600     | 5        | 20.83%  |
| 1501-2000   | 3        | 12.5%   |
| 351-400     | 2        | 8.33%   |
| 301-350     | 2        | 8.33%   |
| 1001-1500   | 2        | 8.33%   |
| Unknown     | 1        | 4.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 16       | 59.26%  |
| 16/10   | 6        | 22.22%  |
| 5/4     | 4        | 14.81%  |
| Unknown | 1        | 3.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 151-200        | 8        | 30.77%  |
| More than 1000 | 4        | 15.38%  |
| 201-250        | 4        | 15.38%  |
| 141-150        | 4        | 15.38%  |
| 251-300        | 3        | 11.54%  |
| 301-350        | 1        | 3.85%   |
| 501-1000       | 1        | 3.85%   |
| Unknown        | 1        | 3.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 12       | 52.17%  |
| 101-120 | 7        | 30.43%  |
| 1-50    | 3        | 13.04%  |
| Unknown | 1        | 4.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 16       | 64%     |
| 2     | 7        | 28%     |
| 0     | 2        | 8%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 15       | 42.86%  |
| Realtek Semiconductor | 9        | 25.71%  |
| MediaTek              | 3        | 8.57%   |
| Broadcom Limited      | 2        | 5.71%   |
| Broadcom              | 2        | 5.71%   |
| Ralink Technology     | 1        | 2.86%   |
| Qualcomm Atheros      | 1        | 2.86%   |
| OPPO Electronics      | 1        | 2.86%   |
| Huawei Technologies   | 1        | 2.86%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 7        | 17.07%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5        | 12.2%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 9.76%   |
| MediaTek Vodafone Smart N10                                       | 3        | 7.32%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 4.88%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 4.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 2.44%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1        | 2.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 2.44%   |
| OPPO realme X50 5G                                                | 1        | 2.44%   |
| Intel Wireless-AC 9260                                            | 1        | 2.44%   |
| Intel Wireless 8265 / 8275                                        | 1        | 2.44%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 2.44%   |
| Intel I211 Gigabit Network Connection                             | 1        | 2.44%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 2.44%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 2.44%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 2.44%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 2.44%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 2.44%   |
| Huawei Mass Storage                                               | 1        | 2.44%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 2.44%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 2.44%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1        | 2.44%   |
| Broadcom Limited NetXtreme BCM5752 Gigabit Ethernet PCI Express   | 1        | 2.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 7        | 70%     |
| Intel                 | 2        | 20%     |
| Ralink Technology     | 1        | 10%     |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter | 7        | 70%     |
| Ralink RT2870/RT3070 Wireless Adapter               | 1        | 10%     |
| Intel Wireless-AC 9260                              | 1        | 10%     |
| Intel Wireless 8265 / 8275                          | 1        | 10%     |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 15       | 51.72%  |
| Realtek Semiconductor | 5        | 17.24%  |
| MediaTek              | 3        | 10.34%  |
| Broadcom Limited      | 2        | 6.9%    |
| Broadcom              | 2        | 6.9%    |
| Qualcomm Atheros      | 1        | 3.45%   |
| OPPO Electronics      | 1        | 3.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5        | 16.67%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 13.33%  |
| MediaTek Vodafone Smart N10                                       | 3        | 10%     |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 6.67%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 6.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 3.33%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 3.33%   |
| OPPO realme X50 5G                                                | 1        | 3.33%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 3.33%   |
| Intel I211 Gigabit Network Connection                             | 1        | 3.33%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 3.33%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 3.33%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 3.33%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 3.33%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 3.33%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 3.33%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 3.33%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1        | 3.33%   |
| Broadcom Limited NetXtreme BCM5752 Gigabit Ethernet PCI Express   | 1        | 3.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 24       | 68.57%  |
| WiFi     | 10       | 28.57%  |
| Modem    | 1        | 2.86%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 17       | 70.83%  |
| WiFi     | 7        | 29.17%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 21       | 84%     |
| 2     | 2        | 8%      |
| 3     | 1        | 4%      |
| 0     | 1        | 4%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 25       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 2        | 100%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Intel Wireless-AC 9260 Bluetooth Adapter | 1        | 50%     |
| Intel Bluetooth wireless interface       | 1        | 50%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 19       | 48.72%  |
| Nvidia              | 8        | 20.51%  |
| AMD                 | 7        | 17.95%  |
| Lenovo              | 2        | 5.13%   |
| Texas Instruments   | 1        | 2.56%   |
| Medeli Electronics  | 1        | 2.56%   |
| C-Media Electronics | 1        | 2.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4        | 9.3%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4        | 9.3%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 6.98%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3        | 6.98%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 6.98%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 6.98%   |
| Nvidia High Definition Audio Controller                                    | 2        | 4.65%   |
| Lenovo T2224zD                                                             | 2        | 4.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 4.65%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 4.65%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 2.33%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 2.33%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 2.33%   |
| Medeli Electronics USB Audio Device                                        | 1        | 2.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 2.33%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 2.33%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 2.33%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1        | 2.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1        | 2.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 2.33%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 2.33%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 1        | 2.33%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1        | 2.33%   |
| AMD FCH Azalia Controller                                                  | 1        | 2.33%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1        | 2.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| SK Hynix            | 4        | 30.77%  |
| Micron Technology   | 2        | 15.38%  |
| G.Skill             | 2        | 15.38%  |
| Crucial             | 2        | 15.38%  |
| TwinMOS             | 1        | 7.69%   |
| Samsung Electronics | 1        | 7.69%   |
| Kingston            | 1        | 7.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s     | 2        | 13.33%  |
| TwinMOS RAM 9DECBNZB-TATP 4GB DIMM DDR3 1333MT/s         | 1        | 6.67%   |
| TwinMOS RAM 9DECBMZB-TATP 2048MB DIMM DDR3 1333MT/s      | 1        | 6.67%   |
| SK Hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s     | 1        | 6.67%   |
| SK Hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s     | 1        | 6.67%   |
| SK Hynix RAM HMT125U7BFR8C-H9 2048MB DIMM DDR3 1333MT/s  | 1        | 6.67%   |
| SK Hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2667MT/s     | 1        | 6.67%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s   | 1        | 6.67%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s      | 1        | 6.67%   |
| Micron RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s     | 1        | 6.67%   |
| Micron RAM 16KTF51264AZ-1G6M1 4096MB DIMM DDR3 1600MT/s  | 1        | 6.67%   |
| Kingston RAM KHX1600C10D3/8G 4096MB DIMM DDR3 1600MT/s   | 1        | 6.67%   |
| Crucial RAM CT51264BD160B.C16F 4096MB DIMM DDR3 1600MT/s | 1        | 6.67%   |
| Crucial RAM CB16GU2400.C16J 16GB DIMM DDR4 2400MT/s      | 1        | 6.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 5        | 45.45%  |
| DDR3  | 5        | 45.45%  |
| SDRAM | 1        | 9.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 9        | 90%     |
| SODIMM | 1        | 10%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 4        | 33.33%  |
| 16384 | 3        | 25%     |
| 4096  | 3        | 25%     |
| 2048  | 2        | 16.67%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 3        | 27.27%  |
| 3600  | 2        | 18.18%  |
| 2667  | 2        | 18.18%  |
| 1333  | 2        | 18.18%  |
| 2400  | 1        | 9.09%   |
| 1867  | 1        | 9.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                 | Desktops | Percent |
|-----------------------|----------|---------|
| HP LaserJet M101-M106 | 1        | 100%    |

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


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 2        | 50%     |
| MacroSilicon          | 1        | 25%     |
| Cubeternet            | 1        | 25%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek FULL HD 1080P Webcam    | 2        | 50%     |
| MacroSilicon USB Video          | 1        | 25%     |
| Cubeternet GL-UPC822 UVC WebCam | 1        | 25%     |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 24       | 96%     |
| 1     | 1        | 4%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 1        | 100%    |

