antiX - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for antiX.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/antiX/Desktop/README.md) and [notebooks](/Dist/antiX/Notebook/README.md).

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

Total: 42

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Apple         | MacBook7,1                  | Notebook    | [70413280df](https://linux-hardware.org/?probe=70413280df) | Mar 26, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [20e998c205](https://linux-hardware.org/?probe=20e998c205) | Mar 17, 2022 |
| Gigabyte      | F2A85XM-D3H                 | Desktop     | [cf20f6e233](https://linux-hardware.org/?probe=cf20f6e233) | Mar 09, 2022 |
| Gigabyte      | 945GCMX-S2                  | Desktop     | [54149177a7](https://linux-hardware.org/?probe=54149177a7) | Feb 12, 2022 |
| IBM           | ThinkPad T40 237342G        | Notebook    | [2c96b391e2](https://linux-hardware.org/?probe=2c96b391e2) | Jan 16, 2022 |
| IBM           | ThinkPad T40 237342G        | Notebook    | [5c4e8748ef](https://linux-hardware.org/?probe=5c4e8748ef) | Jan 16, 2022 |
| Toshiba       | Satellite 1905              | Notebook    | [e72b9043c8](https://linux-hardware.org/?probe=e72b9043c8) | Jan 14, 2022 |
| Unknown       | NF-CK804                    | Desktop     | [dc6287d017](https://linux-hardware.org/?probe=dc6287d017) | Jan 05, 2022 |
| Lenovo        | ThinkPad T440p 20AWS3RH0... | Notebook    | [b2a71d3bbe](https://linux-hardware.org/?probe=b2a71d3bbe) | Dec 30, 2021 |
| ASUSTek       | X71SL                       | Notebook    | [42e7b57eb8](https://linux-hardware.org/?probe=42e7b57eb8) | Dec 07, 2021 |
| ASUSTek       | A3L                         | Notebook    | [32489f1764](https://linux-hardware.org/?probe=32489f1764) | Dec 06, 2021 |
| ASUSTek       | A3L                         | Notebook    | [2b01c636c2](https://linux-hardware.org/?probe=2b01c636c2) | Dec 06, 2021 |
| ASUSTek       | X51RL                       | Notebook    | [0aeee18806](https://linux-hardware.org/?probe=0aeee18806) | Nov 19, 2021 |
| Acer          | AOA150                      | Notebook    | [24833c6a59](https://linux-hardware.org/?probe=24833c6a59) | Oct 26, 2021 |
| Dell          | Latitude E6400              | Notebook    | [6b7ef9cad5](https://linux-hardware.org/?probe=6b7ef9cad5) | Oct 21, 2021 |
| MSI           | GE62 7RE                    | Notebook    | [9d064bcc8d](https://linux-hardware.org/?probe=9d064bcc8d) | May 21, 2021 |
| MSI           | GE62 7RE                    | Notebook    | [d560e067d4](https://linux-hardware.org/?probe=d560e067d4) | May 21, 2021 |
| ASUSTek       | A8R-MVP                     | Desktop     | [43a7b44e3f](https://linux-hardware.org/?probe=43a7b44e3f) | Mar 27, 2021 |
| HP            | EliteBook 8770w             | Notebook    | [0af42b4958](https://linux-hardware.org/?probe=0af42b4958) | Mar 17, 2021 |
| Fujitsu       | FMVS54EB                    | Notebook    | [f01ca3644f](https://linux-hardware.org/?probe=f01ca3644f) | Mar 11, 2021 |
| Dell          | Latitude 5480               | Notebook    | [c9e0b19e8b](https://linux-hardware.org/?probe=c9e0b19e8b) | Mar 07, 2021 |
| Radiant Sy... | P845                        | Mini pc     | [4a3e3cd4ee](https://linux-hardware.org/?probe=4a3e3cd4ee) | Feb 23, 2021 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [a8985150bd](https://linux-hardware.org/?probe=a8985150bd) | Feb 08, 2021 |
| ASRock        | H81M-ITX                    | Desktop     | [7b2d6774c8](https://linux-hardware.org/?probe=7b2d6774c8) | Feb 05, 2021 |
| Radiant Sy... | P845                        | Mini pc     | [e751bd8090](https://linux-hardware.org/?probe=e751bd8090) | Jan 14, 2021 |
| Radiant Sy... | P845                        | Mini pc     | [cac53c0d21](https://linux-hardware.org/?probe=cac53c0d21) | Jan 14, 2021 |
| HP            | Mini 110-3700               | Notebook    | [33a6e65493](https://linux-hardware.org/?probe=33a6e65493) | Jan 06, 2021 |
| HP            | 8430 1000                   | All in one  | [db9e0da88a](https://linux-hardware.org/?probe=db9e0da88a) | Dec 06, 2020 |
| IBM           | ThinkPad T41 2374K50        | Notebook    | [c77530ec4e](https://linux-hardware.org/?probe=c77530ec4e) | Nov 19, 2020 |
| IBM           | ThinkPad T41 2374K50        | Notebook    | [9c27b878ae](https://linux-hardware.org/?probe=9c27b878ae) | Nov 17, 2020 |
| IBM           | ThinkPad T43 2668WEJ        | Notebook    | [c7508c3b5c](https://linux-hardware.org/?probe=c7508c3b5c) | Oct 02, 2020 |
| HP            | Pavilion dv2700             | Notebook    | [312d41f446](https://linux-hardware.org/?probe=312d41f446) | Aug 01, 2020 |
| HP            | 3641h                       | Desktop     | [f918637d53](https://linux-hardware.org/?probe=f918637d53) | Jul 29, 2020 |
| HP            | Mini 5101                   | Notebook    | [c0abbe79e6](https://linux-hardware.org/?probe=c0abbe79e6) | Apr 24, 2020 |
| HP            | Mini 5101                   | Notebook    | [8fd41129bc](https://linux-hardware.org/?probe=8fd41129bc) | Apr 24, 2020 |
| ASUSTek       | 900A                        | Notebook    | [9ab5761eb1](https://linux-hardware.org/?probe=9ab5761eb1) | Apr 05, 2020 |
| ASUSTek       | 900HA                       | Notebook    | [39b2bfbefc](https://linux-hardware.org/?probe=39b2bfbefc) | Mar 21, 2020 |
| Medion        | WIM2170                     | Notebook    | [a8c4771b62](https://linux-hardware.org/?probe=a8c4771b62) | Jan 13, 2020 |
| Medion        | WIM2170                     | Notebook    | [c879195021](https://linux-hardware.org/?probe=c879195021) | Jan 13, 2020 |
| Unknown       | Unknown                     | Desktop     | [7653370d96](https://linux-hardware.org/?probe=7653370d96) | Dec 16, 2019 |
| ASUSTek       | P5KPL/1600                  | Desktop     | [8ba4b22f71](https://linux-hardware.org/?probe=8ba4b22f71) | Oct 22, 2019 |
| Lenovo        | Board                       | Desktop     | [e68917ee9f](https://linux-hardware.org/?probe=e68917ee9f) | Nov 04, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| antiX 19.2     | 8         | 25%     |
| antiX 21       | 6         | 18.75%  |
| antiX 19.3     | 4         | 12.5%   |
| antiX 17.4.1   | 4         | 12.5%   |
| antiX 21-runit | 2         | 6.25%   |
| antiX 19.4     | 2         | 6.25%   |
| antiX 19.1     | 2         | 6.25%   |
| antiX 17.2.1   | 1         | 3.13%   |
| antiX 17.1     | 1         | 3.13%   |
| antiX 17       | 1         | 3.13%   |
| antiX 15       | 1         | 3.13%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| antiX | 32        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 4.9.160-antix.2-486-smp      | 4         | 12.5%   |
| 4.9.235-antix.1-amd64-smp    | 3         | 9.38%   |
| 4.9.212-antix.1-amd64-smp    | 3         | 9.38%   |
| 4.9.212-antix.1-486-smp      | 3         | 9.38%   |
| 4.9.0-279-antix.1-486-smp    | 3         | 9.38%   |
| 5.10.88-antix.1-amd64-smp    | 2         | 6.25%   |
| 5.10.57-antix.1-amd64-smp    | 2         | 6.25%   |
| 4.9.200-antix.1-486-smp      | 2         | 6.25%   |
| 4.9.0-279-antix.1-amd64-smp  | 2         | 6.25%   |
| 5.14.0-14.1-liquorix-amd64   | 1         | 3.13%   |
| 5.10.27-antix.1-amd64-smp    | 1         | 3.13%   |
| 4.9.87-antix.1-amd64-smp     | 1         | 3.13%   |
| 4.9.160-antix.1-amd64-smp    | 1         | 3.13%   |
| 4.9.0-264-antix.1-486-smp    | 1         | 3.13%   |
| 4.19.202-antix.1-686-smp-pae | 1         | 3.13%   |
| 4.19.100-antix.1-686-smp-pae | 1         | 3.13%   |
| 4.10.5-antix.1-486-smp       | 1         | 3.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.9.212  | 6         | 18.75%  |
| 4.9.0    | 6         | 18.75%  |
| 4.9.160  | 5         | 15.63%  |
| 4.9.235  | 3         | 9.38%   |
| 5.10.88  | 2         | 6.25%   |
| 5.10.57  | 2         | 6.25%   |
| 4.9.200  | 2         | 6.25%   |
| 5.14.0   | 1         | 3.13%   |
| 5.10.27  | 1         | 3.13%   |
| 4.9.87   | 1         | 3.13%   |
| 4.19.202 | 1         | 3.13%   |
| 4.19.100 | 1         | 3.13%   |
| 4.10.5   | 1         | 3.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.9     | 23        | 71.88%  |
| 5.10    | 5         | 15.63%  |
| 4.19    | 2         | 6.25%   |
| 5.14    | 1         | 3.13%   |
| 4.10    | 1         | 3.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 16        | 50%     |
| i686   | 16        | 50%     |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Unknown      | 20        | 62.5%   |
| icewm        | 8         | 25%     |
| XFCE         | 2         | 6.25%   |
| herbstluftwm | 1         | 3.13%   |
| GNOME        | 1         | 3.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 31        | 96.88%  |
| Tty  | 1         | 3.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SLiM    | 21        | 65.63%  |
| Unknown | 8         | 25%     |
| LightDM | 3         | 9.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 12        | 37.5%   |
| ru_RU   | 3         | 9.38%   |
| de_DE   | 3         | 9.38%   |
| Unknown | 3         | 9.38%   |
| sk_SK   | 2         | 6.25%   |
| en_AU   | 2         | 6.25%   |
| uk_UA   | 1         | 3.13%   |
| pt_BR   | 1         | 3.13%   |
| pl_PL   | 1         | 3.13%   |
| ja_JP   | 1         | 3.13%   |
| it_IT   | 1         | 3.13%   |
| es_MX   | 1         | 3.13%   |
| en_GB   | 1         | 3.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 27        | 84.38%  |
| EFI  | 5         | 15.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 26        | 81.25%  |
| Overlay  | 5         | 15.63%  |
| Reiserfs | 1         | 3.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 25        | 78.13%  |
| GPT     | 5         | 15.63%  |
| Unknown | 2         | 6.25%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 25        | 78.13%  |
| Yes       | 7         | 21.88%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 22        | 68.75%  |
| Yes       | 10        | 31.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 7         | 21.88%  |
| ASUSTek Computer    | 7         | 21.88%  |
| IBM                 | 3         | 9.38%   |
| Lenovo              | 2         | 6.25%   |
| Gigabyte Technology | 2         | 6.25%   |
| Dell                | 2         | 6.25%   |
| Unknown             | 2         | 6.25%   |
| Toshiba             | 1         | 3.13%   |
| Radiant Systems     | 1         | 3.13%   |
| MSI                 | 1         | 3.13%   |
| Medion              | 1         | 3.13%   |
| Fujitsu             | 1         | 3.13%   |
| Apple               | 1         | 3.13%   |
| Acer                | 1         | 3.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| Unknown                          | 2         | 6.25%   |
| Toshiba Satellite 1905           | 1         | 3.13%   |
| Radiant Systems P845             | 1         | 3.13%   |
| MSI GE62 7RE                     | 1         | 3.13%   |
| Medion WIM2170                   | 1         | 3.13%   |
| Lenovo ThinkPad T440p 20AWS3RH00 | 1         | 3.13%   |
| Lenovo ThinkCentre M91p 4480B9U  | 1         | 3.13%   |
| IBM ThinkPad T43 2668WEJ         | 1         | 3.13%   |
| IBM ThinkPad T41 2374K50         | 1         | 3.13%   |
| IBM ThinkPad T40 237342G         | 1         | 3.13%   |
| HP t5740                         | 1         | 3.13%   |
| HP Pavilion dv2700               | 1         | 3.13%   |
| HP Mini 5101                     | 1         | 3.13%   |
| HP Mini 110-3700                 | 1         | 3.13%   |
| HP EliteBook 8770w               | 1         | 3.13%   |
| HP EliteBook 2570p               | 1         | 3.13%   |
| HP All-in-One 24-f0xx            | 1         | 3.13%   |
| Gigabyte F2A85XM-D3H             | 1         | 3.13%   |
| Gigabyte 945GCMX-S2              | 1         | 3.13%   |
| Fujitsu FMVS54EB                 | 1         | 3.13%   |
| Dell Latitude E6400              | 1         | 3.13%   |
| Dell Latitude 5480               | 1         | 3.13%   |
| ASUS X71SL                       | 1         | 3.13%   |
| ASUS X51RL                       | 1         | 3.13%   |
| ASUS P5KPL/1600                  | 1         | 3.13%   |
| ASUS A8R-MVP                     | 1         | 3.13%   |
| ASUS A3L                         | 1         | 3.13%   |
| ASUS 900HA                       | 1         | 3.13%   |
| ASUS 900A                        | 1         | 3.13%   |
| Apple MacBook7,1                 | 1         | 3.13%   |
| Acer AOA150                      | 1         | 3.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| IBM ThinkPad         | 3         | 9.38%   |
| HP Mini              | 2         | 6.25%   |
| HP EliteBook         | 2         | 6.25%   |
| Dell Latitude        | 2         | 6.25%   |
| Unknown              | 2         | 6.25%   |
| Toshiba Satellite    | 1         | 3.13%   |
| Radiant Systems P845 | 1         | 3.13%   |
| MSI GE62             | 1         | 3.13%   |
| Medion WIM2170       | 1         | 3.13%   |
| Lenovo ThinkPad      | 1         | 3.13%   |
| Lenovo ThinkCentre   | 1         | 3.13%   |
| HP t5740             | 1         | 3.13%   |
| HP Pavilion          | 1         | 3.13%   |
| HP All-in-One        | 1         | 3.13%   |
| Gigabyte F2A85XM-D3H | 1         | 3.13%   |
| Gigabyte 945GCMX-S2  | 1         | 3.13%   |
| Fujitsu FMVS54EB     | 1         | 3.13%   |
| ASUS X71SL           | 1         | 3.13%   |
| ASUS X51RL           | 1         | 3.13%   |
| ASUS P5KPL           | 1         | 3.13%   |
| ASUS A8R-MVP         | 1         | 3.13%   |
| ASUS A3L             | 1         | 3.13%   |
| ASUS 900HA           | 1         | 3.13%   |
| ASUS 900A            | 1         | 3.13%   |
| Apple MacBook7       | 1         | 3.13%   |
| Acer AOA150          | 1         | 3.13%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2008    | 6         | 18.75%  |
| 2012    | 4         | 12.5%   |
| 2009    | 4         | 12.5%   |
| 2007    | 4         | 12.5%   |
| 2005    | 3         | 9.38%   |
| 2013    | 2         | 6.25%   |
| 2003    | 2         | 6.25%   |
| 2018    | 1         | 3.13%   |
| 2017    | 1         | 3.13%   |
| 2016    | 1         | 3.13%   |
| 2011    | 1         | 3.13%   |
| 2010    | 1         | 3.13%   |
| 2004    | 1         | 3.13%   |
| Unknown | 1         | 3.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 22        | 68.75%  |
| Desktop    | 8         | 25%     |
| Mini pc    | 1         | 3.13%   |
| All in one | 1         | 3.13%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 32        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 32        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 7         | 21.88%  |
| 1.01-2.0   | 6         | 18.75%  |
| 3.01-4.0   | 5         | 15.63%  |
| 2.01-3.0   | 4         | 12.5%   |
| 4.01-8.0   | 2         | 6.25%   |
| 32.01-64.0 | 2         | 6.25%   |
| 16.01-24.0 | 2         | 6.25%   |
| 8.01-16.0  | 2         | 6.25%   |
| 0.01-0.5   | 2         | 6.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 14        | 43.75%  |
| 0.51-1.0 | 9         | 28.13%  |
| 2.01-3.0 | 4         | 12.5%   |
| 1.01-2.0 | 4         | 12.5%   |
| 4.01-8.0 | 1         | 3.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 23        | 71.88%  |
| 2      | 5         | 15.63%  |
| 3      | 3         | 9.38%   |
| 0      | 1         | 3.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 18        | 56.25%  |
| No        | 14        | 43.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 96.88%  |
| No        | 1         | 3.13%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 23        | 71.88%  |
| No        | 9         | 28.13%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 23        | 71.88%  |
| Yes       | 9         | 28.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Computers | Percent |
|------------|-----------|---------|
| USA        | 7         | 21.88%  |
| Russia     | 5         | 15.63%  |
| Germany    | 5         | 15.63%  |
| Slovakia   | 2         | 6.25%   |
| Australia  | 2         | 6.25%   |
| Ukraine    | 1         | 3.13%   |
| Poland     | 1         | 3.13%   |
| Mexico     | 1         | 3.13%   |
| Kazakhstan | 1         | 3.13%   |
| Japan      | 1         | 3.13%   |
| Italy      | 1         | 3.13%   |
| Hungary    | 1         | 3.13%   |
| Greece     | 1         | 3.13%   |
| France     | 1         | 3.13%   |
| Denmark    | 1         | 3.13%   |
| Brazil     | 1         | 3.13%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| Sydney                    | 2         | 6.25%   |
| Moscow                    | 2         | 6.25%   |
| Bratislava                | 2         | 6.25%   |
| Zagnansk                  | 1         | 3.13%   |
| Yuzhno-Sakhalinsk         | 1         | 3.13%   |
| Wiesmoor                  | 1         | 3.13%   |
| Vogue                     | 1         | 3.13%   |
| Toms River                | 1         | 3.13%   |
| Springfield               | 1         | 3.13%   |
| Schloss Holte-Stukenbrock | 1         | 3.13%   |
| Salto                     | 1         | 3.13%   |
| Portland                  | 1         | 3.13%   |
| Osaka                     | 1         | 3.13%   |
| Norden                    | 1         | 3.13%   |
| Metzingen                 | 1         | 3.13%   |
| Mechanicsburg             | 1         | 3.13%   |
| Kazanâ€™             | 1         | 3.13%   |
| Karaganda                 | 1         | 3.13%   |
| Jonesboro                 | 1         | 3.13%   |
| Heraklion                 | 1         | 3.13%   |
| Frankfurt am Main         | 1         | 3.13%   |
| El Cerrito                | 1         | 3.13%   |
| Domodedovo                | 1         | 3.13%   |
| Dnipropetrovsk            | 1         | 3.13%   |
| Copenhagen                | 1         | 3.13%   |
| Celaya                    | 1         | 3.13%   |
| Budapest                  | 1         | 3.13%   |
| Boulder                   | 1         | 3.13%   |
| Albairate                 | 1         | 3.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 20.51%  |
| Hitachi             | 6         | 7      | 15.38%  |
| WDC                 | 5         | 5      | 12.82%  |
| Samsung Electronics | 5         | 6      | 12.82%  |
| Unknown             | 3         | 3      | 7.69%   |
| Toshiba             | 3         | 3      | 7.69%   |
| Kingston            | 2         | 2      | 5.13%   |
| Zheino              | 1         | 1      | 2.56%   |
| SanDisk             | 1         | 1      | 2.56%   |
| OCZ                 | 1         | 1      | 2.56%   |
| Intel               | 1         | 1      | 2.56%   |
| HGST                | 1         | 1      | 2.56%   |
| Hewlett-Packard     | 1         | 1      | 2.56%   |
| ASUS-PHISON         | 1         | 1      | 2.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Samsung SSD 750 EVO 120GB        | 2         | 5%      |
| Hitachi HTS723232A7A364 320GB    | 2         | 5%      |
| Zheino CHN mSATAM3 128 128GB SSD | 1         | 2.5%    |
| WDC WD5000LPLX-08ZNTT0 500GB     | 1         | 2.5%    |
| WDC WD3200BEVT-60ZCT1 320GB      | 1         | 2.5%    |
| WDC WD205BA 21GB                 | 1         | 2.5%    |
| WDC WD1600AAJS-00PSA0 160GB      | 1         | 2.5%    |
| WDC WD1200BEVE-00A0HT0 120GB     | 1         | 2.5%    |
| Unknown SR64G  64GB              | 1         | 2.5%    |
| Unknown SD/MMC/MS PRO 32GB       | 1         | 2.5%    |
| Unknown 2GB ATA Flash Disk       | 1         | 2.5%    |
| Toshiba THNSNJ256G8NY 256GB SSD  | 1         | 2.5%    |
| Toshiba MK2576GSX 250GB          | 1         | 2.5%    |
| Toshiba DT01ACA100 1TB           | 1         | 2.5%    |
| Seagate ST9160411AS 160GB        | 1         | 2.5%    |
| Seagate ST9160314AS 160GB        | 1         | 2.5%    |
| Seagate ST9160310AS 160GB        | 1         | 2.5%    |
| Seagate ST9160301AS 160GB        | 1         | 2.5%    |
| Seagate ST500LM021-1KJ152 500GB  | 1         | 2.5%    |
| Seagate ST500DM002-1BD142 500GB  | 1         | 2.5%    |
| Seagate ST3320620AS 320GB        | 1         | 2.5%    |
| Seagate ST3320413CS 320GB        | 1         | 2.5%    |
| SanDisk sandisk120 120GB SSD     | 1         | 2.5%    |
| Samsung SSD 850 EVO 120GB        | 1         | 2.5%    |
| Samsung HD250HJ 250GB            | 1         | 2.5%    |
| Samsung HD160JJ 160GB            | 1         | 2.5%    |
| Samsung HD080HJ 80GB             | 1         | 2.5%    |
| OCZ AGILITY3 120GB SSD           | 1         | 2.5%    |
| Kingston SUV500MS120G 120GB SSD  | 1         | 2.5%    |
| Kingston SUV400S37120G 120GB SSD | 1         | 2.5%    |
| Intel SSDSC2BW180A3H 180GB       | 1         | 2.5%    |
| Hitachi HTS725050A7E630 500GB    | 1         | 2.5%    |
| Hitachi HTS721060G9AT00 64GB     | 1         | 2.5%    |
| Hitachi HTS548040M9AT00 40GB     | 1         | 2.5%    |
| Hitachi HTS541612J9SA00 120GB    | 1         | 2.5%    |
| HGST HTS721010A9E630 1TB         | 1         | 2.5%    |
| HP SSD S750 512GB                | 1         | 2.5%    |
| ASUS-PHISON SSD 8GB              | 1         | 2.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 30.77%  |
| Hitachi             | 6         | 7      | 23.08%  |
| WDC                 | 5         | 5      | 19.23%  |
| Unknown             | 2         | 2      | 7.69%   |
| Toshiba             | 2         | 2      | 7.69%   |
| Samsung Electronics | 2         | 3      | 7.69%   |
| HGST                | 1         | 1      | 3.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 25%     |
| Kingston            | 2         | 2      | 16.67%  |
| Zheino              | 1         | 1      | 8.33%   |
| Toshiba             | 1         | 1      | 8.33%   |
| SanDisk             | 1         | 1      | 8.33%   |
| OCZ                 | 1         | 1      | 8.33%   |
| Intel               | 1         | 1      | 8.33%   |
| Hewlett-Packard     | 1         | 1      | 8.33%   |
| ASUS-PHISON         | 1         | 1      | 8.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 23        | 28     | 63.89%  |
| SSD  | 12        | 12     | 33.33%  |
| MMC  | 1         | 1      | 2.78%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 31        | 39     | 93.94%  |
| SAS  | 1         | 1      | 3.03%   |
| MMC  | 1         | 1      | 3.03%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 31        | 37     | 91.18%  |
| 0.51-1.0   | 3         | 3      | 8.82%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 12        | 37.5%   |
| 21-50      | 6         | 18.75%  |
| 1-20       | 6         | 18.75%  |
| 51-100     | 4         | 12.5%   |
| 501-1000   | 2         | 6.25%   |
| 251-500    | 1         | 3.13%   |
| Unknown    | 1         | 3.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 23        | 71.88%  |
| 21-50   | 4         | 12.5%   |
| 101-250 | 3         | 9.38%   |
| 51-100  | 1         | 3.13%   |
| Unknown | 1         | 3.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD3200BEVT-60ZCT1 320GB     | 1         | 1      | 7.69%   |
| WDC WD205BA 21GB                | 1         | 1      | 7.69%   |
| Seagate ST9160314AS 160GB       | 1         | 1      | 7.69%   |
| Seagate ST9160310AS 160GB       | 1         | 1      | 7.69%   |
| Seagate ST500DM002-1BD142 500GB | 1         | 1      | 7.69%   |
| Seagate ST3320620AS 320GB       | 1         | 1      | 7.69%   |
| Seagate ST3320413CS 320GB       | 1         | 1      | 7.69%   |
| SanDisk sandisk120 120GB SSD    | 1         | 1      | 7.69%   |
| Hitachi HTS725050A7E630 500GB   | 1         | 1      | 7.69%   |
| Hitachi HTS723232A7A364 320GB   | 1         | 1      | 7.69%   |
| Hitachi HTS721060G9AT00 64GB    | 1         | 1      | 7.69%   |
| Hitachi HTS548040M9AT00 40GB    | 1         | 1      | 7.69%   |
| Hitachi HTS541612J9SA00 120GB   | 1         | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 38.46%  |
| Hitachi | 5         | 5      | 38.46%  |
| WDC     | 2         | 2      | 15.38%  |
| SanDisk | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 41.67%  |
| Hitachi | 5         | 5      | 41.67%  |
| WDC     | 2         | 2      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 12     | 92.31%  |
| SSD  | 1         | 1      | 7.69%   |

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
| Works    | 17        | 22     | 48.57%  |
| Malfunc  | 13        | 13     | 37.14%  |
| Detected | 5         | 6      | 14.29%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 25        | 71.43%  |
| AMD                              | 3         | 8.57%   |
| Nvidia                           | 2         | 5.71%   |
| ULi Electronics                  | 1         | 2.86%   |
| Silicon Integrated Systems [SiS] | 1         | 2.86%   |
| Silicon Image                    | 1         | 2.86%   |
| JMicron Technology               | 1         | 2.86%   |
| ASMedia Technology               | 1         | 2.86%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 3         | 6.82%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3         | 6.82%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 3         | 6.82%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2         | 4.55%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 4.55%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 4.55%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 4.55%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 2         | 4.55%   |
| ULi ULi M5288 SATA                                                             | 1         | 2.27%   |
| ULi M5229 IDE                                                                  | 1         | 2.27%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 1         | 2.27%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 1         | 2.27%   |
| Silicon Image SiI 3531 [SATALink/SATARaid] Serial ATA Controller               | 1         | 2.27%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 1         | 2.27%   |
| Nvidia CK804 Serial ATA Controller                                             | 1         | 2.27%   |
| Nvidia CK804 IDE                                                               | 1         | 2.27%   |
| JMicron JMB360 AHCI Controller                                                 | 1         | 2.27%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 2.27%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 2.27%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 2.27%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]           | 1         | 2.27%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 1         | 2.27%   |
| Intel 82801FBM (ICH6M) SATA Controller                                         | 1         | 2.27%   |
| Intel 82801DB (ICH4) IDE Controller                                            | 1         | 2.27%   |
| Intel 82801BA IDE U100 Controller                                              | 1         | 2.27%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                  | 1         | 2.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 2.27%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1         | 2.27%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1         | 2.27%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 1         | 2.27%   |
| AMD SB600 IDE                                                                  | 1         | 2.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| IDE  | 20        | 51.28%  |
| SATA | 16        | 41.03%  |
| RAID | 3         | 7.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 28        | 87.5%   |
| AMD    | 4         | 12.5%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz                | 3         | 9.38%   |
| Intel Pentium M processor 1.60GHz            | 2         | 6.25%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz         | 2         | 6.25%   |
| Intel Atom CPU N280 @ 1.66GHz                | 2         | 6.25%   |
| Intel Xeon CPU L5410 @ 2.33GHz               | 1         | 3.13%   |
| Intel Pentium M processor 1600MHz            | 1         | 3.13%   |
| Intel Pentium M processor 1.86GHz            | 1         | 3.13%   |
| Intel Pentium II (Deschutes)                 | 1         | 3.13%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz       | 1         | 3.13%   |
| Intel Pentium 4 CPU 2.00GHz                  | 1         | 3.13%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz           | 1         | 3.13%   |
| Intel Core i7-7600U CPU @ 2.80GHz            | 1         | 3.13%   |
| Intel Core i7-3740QM CPU @ 2.70GHz           | 1         | 3.13%   |
| Intel Core i5-4300M CPU @ 2.60GHz            | 1         | 3.13%   |
| Intel Core i5-3320M CPU @ 2.60GHz            | 1         | 3.13%   |
| Intel Core i5-2400 CPU @ 3.10GHz             | 1         | 3.13%   |
| Intel Core i3-2330M CPU @ 2.20GHz            | 1         | 3.13%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz         | 1         | 3.13%   |
| Intel Core 2 Duo CPU T5750 @ 2.00GHz         | 1         | 3.13%   |
| Intel Core 2 Duo CPU T5450 @ 1.66GHz         | 1         | 3.13%   |
| Intel Celeron M processor 900MHz             | 1         | 3.13%   |
| Intel Celeron CPU 540 @ 1.86GHz              | 1         | 3.13%   |
| Intel Atom CPU N455 @ 1.66GHz                | 1         | 3.13%   |
| AMD Athlon 64 X2 Dual Core Processor 4600+   | 1         | 3.13%   |
| AMD Athlon 64 Processor 3200+                | 1         | 3.13%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G | 1         | 3.13%   |
| AMD A6-5400K APU with Radeon HD Graphics     | 1         | 3.13%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Atom         | 6         | 18.75%  |
| Intel Core 2 Duo   | 5         | 15.63%  |
| Intel Pentium M    | 4         | 12.5%   |
| Intel Core i7      | 3         | 9.38%   |
| Intel Core i5      | 3         | 9.38%   |
| Other              | 1         | 3.13%   |
| Intel Xeon         | 1         | 3.13%   |
| Intel Pentium Dual | 1         | 3.13%   |
| Intel Pentium 4    | 1         | 3.13%   |
| Intel Pentium      | 1         | 3.13%   |
| Intel Core i3      | 1         | 3.13%   |
| Intel Celeron M    | 1         | 3.13%   |
| Intel Celeron      | 1         | 3.13%   |
| AMD Athlon 64 X2   | 1         | 3.13%   |
| AMD Athlon 64      | 1         | 3.13%   |
| AMD A6             | 1         | 3.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 16        | 50%     |
| 2      | 12        | 37.5%   |
| 4      | 4         | 12.5%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 32        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 19        | 59.38%  |
| 2      | 13        | 40.63%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 20        | 62.5%   |
| 32-bit         | 12        | 37.5%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x106c2    | 5         | 15.63%  |
| 0x6fd      | 3         | 9.38%   |
| 0x1067a    | 3         | 9.38%   |
| 0x6d8      | 2         | 6.25%   |
| 0x6d6      | 2         | 6.25%   |
| 0x306a9    | 2         | 6.25%   |
| 0x206a7    | 2         | 6.25%   |
| Unknown    | 2         | 6.25%   |
| 0xf24      | 1         | 3.13%   |
| 0x906e9    | 1         | 3.13%   |
| 0x806e9    | 1         | 3.13%   |
| 0x695      | 1         | 3.13%   |
| 0x652      | 1         | 3.13%   |
| 0x306c3    | 1         | 3.13%   |
| 0x106ca    | 1         | 3.13%   |
| 0x10676    | 1         | 3.13%   |
| 0x10661    | 1         | 3.13%   |
| 0x06006705 | 1         | 3.13%   |
| 0x06001116 | 1         | 3.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Bonnell     | 6         | 18.75%  |
| P6          | 5         | 15.63%  |
| Penryn      | 4         | 12.5%   |
| Core        | 4         | 12.5%   |
| SandyBridge | 2         | 6.25%   |
| KabyLake    | 2         | 6.25%   |
| K8 Hammer   | 2         | 6.25%   |
| IvyBridge   | 2         | 6.25%   |
| Piledriver  | 1         | 3.13%   |
| NetBurst    | 1         | 3.13%   |
| Haswell     | 1         | 3.13%   |
| Excavator   | 1         | 3.13%   |
| Unknown     | 1         | 3.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 17        | 51.52%  |
| AMD    | 9         | 27.27%  |
| Nvidia | 7         | 21.21%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 4         | 9.76%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 4         | 9.76%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 2         | 4.88%   |
| Intel 82852/855GM Integrated Graphics Device                                  | 2         | 4.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 2         | 4.88%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 2         | 4.88%   |
| Nvidia MCP89 [GeForce 320M]                                                   | 1         | 2.44%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 2.44%   |
| Nvidia GK104GLM [Quadro K3000M]                                               | 1         | 2.44%   |
| Nvidia GF108 [GeForce GT 630]                                                 | 1         | 2.44%   |
| Nvidia G98M [GeForce 9300M GS]                                                | 1         | 2.44%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                           | 1         | 2.44%   |
| Nvidia G86M [GeForce 8400M GS]                                                | 1         | 2.44%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 2.44%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 2.44%   |
| Intel HD Graphics 630                                                         | 1         | 2.44%   |
| Intel HD Graphics 620                                                         | 1         | 2.44%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 1         | 2.44%   |
| Intel 82945G/GZ Integrated Graphics Controller                                | 1         | 2.44%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 1         | 2.44%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 1         | 2.44%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 1         | 2.44%   |
| AMD RV516 [Radeon X1300/X1550 Series] (Secondary)                             | 1         | 2.44%   |
| AMD RV516 [Radeon X1300/X1550 Series]                                         | 1         | 2.44%   |
| AMD RV515 [Radeon X1300/X1550]                                                | 1         | 2.44%   |
| AMD RV515 [Radeon X1300/X1550 Series] (Secondary)                             | 1         | 2.44%   |
| AMD RV370/M22 [Mobility Radeon X300]                                          | 1         | 2.44%   |
| AMD RV100/M6 [Rage/Radeon Mobility Series]                                    | 1         | 2.44%   |
| AMD RC410M [Mobility Radeon Xpress 200M]                                      | 1         | 2.44%   |
| AMD Rage 3 [3D Rage PRO AGP 2X]                                               | 1         | 2.44%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                  | 1         | 2.44%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 15        | 46.88%  |
| 1 x Nvidia     | 6         | 18.75%  |
| 1 x AMD        | 6         | 18.75%  |
| 2 x AMD        | 3         | 9.38%   |
| Other          | 1         | 3.13%   |
| Intel + Nvidia | 1         | 3.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 27        | 84.38%  |
| Unknown     | 3         | 9.38%   |
| Proprietary | 2         | 6.25%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 18        | 56.25%  |
| Unknown    | 8         | 25%     |
| 1.01-2.0   | 5         | 15.63%  |
| 3.01-4.0   | 1         | 3.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 5         | 20.83%  |
| Samsung Electronics | 4         | 16.67%  |
| LG Display          | 4         | 16.67%  |
| Acer                | 3         | 12.5%   |
| HannStar            | 2         | 8.33%   |
| Vizio               | 1         | 4.17%   |
| LG Philips          | 1         | 4.17%   |
| Hewlett-Packard     | 1         | 4.17%   |
| BOE                 | 1         | 4.17%   |
| Arnos Instruments   | 1         | 4.17%   |
| Apple               | 1         | 4.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch | 2         | 8.33%   |
| Vizio D39h-D0 VIZ1002 1366x768 853x479mm 38.5-inch                   | 1         | 4.17%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch | 1         | 4.17%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch | 1         | 4.17%   |
| LG Philips LCD Monitor LPLA101 1440x900 367x230mm 17.1-inch          | 1         | 4.17%   |
| LG Display LP101WH1-TLB5 LGD0248 1366x768 224x126mm 10.1-inch        | 1         | 4.17%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch         | 1         | 4.17%   |
| LG Display LCD Monitor LGD045E 1366x768 309x174mm 14.0-inch          | 1         | 4.17%   |
| LG Display LCD Monitor LGD02C7 1366x768 293x165mm 13.2-inch          | 1         | 4.17%   |
| Hewlett-Packard ALL-in-One HPN4018 1920x1080 527x297mm 23.8-inch     | 1         | 4.17%   |
| HannStar LCD Monitor HSD0325 1024x600 195x113mm 8.9-inch             | 1         | 4.17%   |
| HannStar HSD100IFW1 HSD03E9 1024x600 220x129mm 10.0-inch             | 1         | 4.17%   |
| BOE LCD Monitor BOE06E2 1920x1080 309x173mm 13.9-inch                | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch        | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO8074 1280x800 331x207mm 15.4-inch        | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO4047 1440x900 303x189mm 14.1-inch        | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch       | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO11C2 1024x600 195x113mm 8.9-inch         | 1         | 4.17%   |
| Arnos Instruments F-417 AIC7450 1280x1024 338x270mm 17.0-inch        | 1         | 4.17%   |
| Apple LCD Monitor APP9CBE 1280x800 286x179mm 13.3-inch               | 1         | 4.17%   |
| Acer VG220Q ACR06D8 1920x1080 476x268mm 21.5-inch                    | 1         | 4.17%   |
| Acer V243H ACR00A3 1920x1080 531x298mm 24.0-inch                     | 1         | 4.17%   |
| Acer S271HL ACR02CA 1920x1080 598x336mm 27.0-inch                    | 1         | 4.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 7         | 29.17%  |
| 1366x768 (WXGA)  | 5         | 20.83%  |
| 1280x800 (WXGA)  | 4         | 16.67%  |
| 1024x600         | 3         | 12.5%   |
| 1600x1200        | 2         | 8.33%   |
| 1440x900 (WXGA+) | 2         | 8.33%   |
| 1280x1024 (SXGA) | 1         | 4.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 13     | 4         | 16.67%  |
| 21     | 3         | 12.5%   |
| 17     | 3         | 12.5%   |
| 15     | 3         | 12.5%   |
| 14     | 3         | 12.5%   |
| 10     | 2         | 8.33%   |
| 8      | 2         | 8.33%   |
| 38     | 1         | 4.17%   |
| 27     | 1         | 4.17%   |
| 24     | 1         | 4.17%   |
| 23     | 1         | 4.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 8         | 33.33%  |
| 201-300     | 5         | 20.83%  |
| 501-600     | 3         | 12.5%   |
| 401-500     | 3         | 12.5%   |
| 351-400     | 2         | 8.33%   |
| 101-200     | 2         | 8.33%   |
| 801-900     | 1         | 4.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 15        | 62.5%   |
| 16/10 | 6         | 25%     |
| 4/3   | 2         | 8.33%   |
| 5/4   | 1         | 4.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 5         | 20.83%  |
| 201-250        | 5         | 20.83%  |
| 101-110        | 3         | 12.5%   |
| 71-80          | 2         | 8.33%   |
| 41-50          | 2         | 8.33%   |
| 1-40           | 2         | 8.33%   |
| 301-350        | 1         | 4.17%   |
| 141-150        | 1         | 4.17%   |
| 131-140        | 1         | 4.17%   |
| 121-130        | 1         | 4.17%   |
| 501-1000       | 1         | 4.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 8         | 34.78%  |
| 121-160 | 7         | 30.43%  |
| 101-120 | 7         | 30.43%  |
| 1-50    | 1         | 4.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 29        | 90.63%  |
| 0     | 3         | 9.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 13        | 25.49%  |
| Realtek Semiconductor            | 12        | 23.53%  |
| Qualcomm Atheros                 | 10        | 19.61%  |
| Broadcom                         | 5         | 9.8%    |
| Marvell Technology Group         | 3         | 5.88%   |
| Qualcomm Atheros Communications  | 2         | 3.92%   |
| Nvidia                           | 2         | 3.92%   |
| Silicon Integrated Systems [SiS] | 1         | 1.96%   |
| Ralink                           | 1         | 1.96%   |
| LSI                              | 1         | 1.96%   |
| Hewlett-Packard                  | 1         | 1.96%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 4         | 6.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3         | 4.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 3         | 4.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 3         | 4.69%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 2         | 3.13%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 2         | 3.13%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 2         | 3.13%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller             | 2         | 3.13%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                            | 2         | 3.13%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 3.13%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                 | 1         | 1.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.56%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 1.56%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 1.56%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 1.56%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1         | 1.56%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1         | 1.56%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 1.56%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 1.56%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 1.56%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 1.56%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.56%   |
| Nvidia MCP89 Ethernet                                                         | 1         | 1.56%   |
| Nvidia CK804 Ethernet Controller                                              | 1         | 1.56%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                       | 1         | 1.56%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                          | 1         | 1.56%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 1         | 1.56%   |
| LSI 56k WinModem                                                              | 1         | 1.56%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 1.56%   |
| Intel Wireless 7260                                                           | 1         | 1.56%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 1.56%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                               | 1         | 1.56%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 1         | 1.56%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 1.56%   |
| Intel Ethernet Connection (4) I219-LM                                         | 1         | 1.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 1.56%   |
| Intel Centrino Wireless-N 6150                                                | 1         | 1.56%   |
| Intel Centrino Wireless-N + WiMAX 6150                                        | 1         | 1.56%   |
| Intel Centrino Ultimate-N 6300                                                | 1         | 1.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1         | 1.56%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller              | 1         | 1.56%   |
| Intel 82801DB PRO/100 VE (LOM) Ethernet Controller                            | 1         | 1.56%   |
| Intel 82801BA/BAM/CA/CAM Ethernet Controller                                  | 1         | 1.56%   |
| Intel 82801BA/BAM AC'97 Modem Controller                                      | 1         | 1.56%   |
| Intel 82567LM Gigabit Network Connection                                      | 1         | 1.56%   |
| HP lt2523 Mobile Broadband Device                                             | 1         | 1.56%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express                      | 1         | 1.56%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                               | 1         | 1.56%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 1         | 1.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 9         | 36%     |
| Qualcomm Atheros                | 8         | 32%     |
| Broadcom                        | 3         | 12%     |
| Realtek Semiconductor           | 2         | 8%      |
| Qualcomm Atheros Communications | 2         | 8%      |
| Ralink                          | 1         | 4%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 4         | 15.38%  |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 7.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 3.85%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 3.85%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 3.85%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1         | 3.85%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 3.85%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 3.85%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                              | 1         | 3.85%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                         | 1         | 3.85%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 3.85%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 3.85%   |
| Intel Wireless 7260                                                           | 1         | 3.85%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 3.85%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                               | 1         | 3.85%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 1         | 3.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 3.85%   |
| Intel Centrino Wireless-N 6150                                                | 1         | 3.85%   |
| Intel Centrino Wireless-N + WiMAX 6150                                        | 1         | 3.85%   |
| Intel Centrino Ultimate-N 6300                                                | 1         | 3.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1         | 3.85%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 1         | 3.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 11        | 34.38%  |
| Intel                            | 10        | 31.25%  |
| Qualcomm Atheros                 | 3         | 9.38%   |
| Marvell Technology Group         | 3         | 9.38%   |
| Nvidia                           | 2         | 6.25%   |
| Broadcom                         | 2         | 6.25%   |
| Silicon Integrated Systems [SiS] | 1         | 3.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 9.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 9.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 9.38%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2         | 6.25%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2         | 6.25%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 6.25%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                | 2         | 6.25%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 3.13%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 3.13%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 3.13%   |
| Nvidia MCP89 Ethernet                                             | 1         | 3.13%   |
| Nvidia CK804 Ethernet Controller                                  | 1         | 3.13%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 3.13%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 3.13%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 3.13%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 3.13%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 3.13%   |
| Intel 82801DB PRO/100 VE (LOM) Ethernet Controller                | 1         | 3.13%   |
| Intel 82801BA/BAM/CA/CAM Ethernet Controller                      | 1         | 3.13%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 3.13%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 1         | 3.13%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 3.13%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 31        | 51.67%  |
| WiFi     | 23        | 38.33%  |
| Modem    | 6         | 10%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 19        | 61.29%  |
| Ethernet | 12        | 38.71%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 22        | 68.75%  |
| 1     | 10        | 31.25%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 29        | 90.63%  |
| Yes  | 3         | 9.38%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 3         | 33.33%  |
| Intel                 | 2         | 22.22%  |
| Realtek Semiconductor | 1         | 11.11%  |
| Ralink Technology     | 1         | 11.11%  |
| ASUSTek Computer      | 1         | 11.11%  |
| Apple                 | 1         | 11.11%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Broadcom HP Portable SoftSailing             | 2         | 22.22%  |
| Realtek  Bluetooth 4.2 Adapter               | 1         | 11.11%  |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter | 1         | 11.11%  |
| Intel Wireless-AC 3168 Bluetooth             | 1         | 11.11%  |
| Intel Bluetooth wireless interface           | 1         | 11.11%  |
| Broadcom BCM20702A0 Bluetooth 4.0            | 1         | 11.11%  |
| ASUS BT-253 Bluetooth Adapter                | 1         | 11.11%  |
| Apple Bluetooth Host Controller              | 1         | 11.11%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 22        | 62.86%  |
| Nvidia                           | 4         | 11.43%  |
| AMD                              | 3         | 8.57%   |
| Creative Labs                    | 2         | 5.71%   |
| ULi Electronics                  | 1         | 2.86%   |
| Silicon Integrated Systems [SiS] | 1         | 2.86%   |
| Ensoniq                          | 1         | 2.86%   |
| C-Media Electronics              | 1         | 2.86%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6         | 16.22%  |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 3         | 8.11%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 5.41%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 5.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 5.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 5.41%   |
| ULi Electronics HD Audio Controller                                        | 1         | 2.7%    |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1         | 2.7%    |
| Nvidia MCP89 High Definition Audio                                         | 1         | 2.7%    |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 2.7%    |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 2.7%    |
| Nvidia CK804 AC'97 Audio Controller                                        | 1         | 2.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 2.7%    |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 2.7%    |
| Intel CM238 HD Audio Controller                                            | 1         | 2.7%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 2.7%    |
| Intel 82801BA/BAM AC'97 Audio Controller                                   | 1         | 2.7%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 2.7%    |
| Ensoniq ES1371/ES1373 / Creative Labs CT2518                               | 1         | 2.7%    |
| Creative Labs EMU20k1 [Sound Blaster X-Fi Series]                          | 1         | 2.7%    |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 1         | 2.7%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1         | 2.7%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 2.7%    |
| AMD High Definition Audio Controller                                       | 1         | 2.7%    |
| AMD FCH Azalia Controller                                                  | 1         | 2.7%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 2.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 14        | 42.42%  |
| SK Hynix            | 5         | 15.15%  |
| Kingston            | 4         | 12.12%  |
| Samsung Electronics | 3         | 9.09%   |
| Micron Technology   | 2         | 6.06%   |
| Unknown (8A02)      | 1         | 3.03%   |
| Patriot             | 1         | 3.03%   |
| Crucial             | 1         | 3.03%   |
| Avant               | 1         | 3.03%   |
| Unknown             | 1         | 3.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 1024MB SODIMM DDR                           | 3         | 8.82%   |
| Unknown RAM Module 512MB SODIMM DDR                            | 2         | 5.88%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s                      | 1         | 2.94%   |
| Unknown RAM Module 512MB DIMM                                  | 1         | 2.94%   |
| Unknown RAM Module 2GB SODIMM SDRAM                            | 1         | 2.94%   |
| Unknown RAM Module 256MB DIMM SDRAM                            | 1         | 2.94%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                         | 1         | 2.94%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 2.94%   |
| Unknown RAM Module 1GB DIMM 667MT/s                            | 1         | 2.94%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                         | 1         | 2.94%   |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 1         | 2.94%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                    | 1         | 2.94%   |
| Unknown (8A02) RAM DDR4 16GB 2400MHz 16GB SODIMM DDR4 2400MT/s | 1         | 2.94%   |
| SK Hynix RAM Module 512MB SODIMM DDR2 533MT/s                  | 1         | 2.94%   |
| SK Hynix RAM Module 1GB SODIMM DDR3 1067MT/s                   | 1         | 2.94%   |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s           | 1         | 2.94%   |
| SK Hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 1         | 2.94%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 1         | 2.94%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s          | 1         | 2.94%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s       | 1         | 2.94%   |
| Samsung RAM M378B5673FH0 2GB DIMM DDR3 667MT/s                 | 1         | 2.94%   |
| Patriot RAM PSD34G1600L2S 4GB SODIMM DDR3 1600MT/s             | 1         | 2.94%   |
| Micron RAM Module 512MB SODIMM DDR2 533MT/s                    | 1         | 2.94%   |
| Micron RAM 8HTF12864HDY-800G1 1024MB SODIMM DDR2 800MT/s       | 1         | 2.94%   |
| Kingston RAM MSI24D4S7D8MB-16 16384MB SODIMM DDR4 2400MT/s     | 1         | 2.94%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s          | 1         | 2.94%   |
| Kingston RAM 99U5402-060.A 2GB DIMM DDR3 1333MT/s              | 1         | 2.94%   |
| Kingston RAM 9905428-095.D00LF 8GB SODIMM DDR3 1600MT/s        | 1         | 2.94%   |
| Crucial RAM CT102464BF160B.M16 8192MB SODIMM DDR3 1600MT/s     | 1         | 2.94%   |
| Avant RAM H641GU67F1600G 8GB SODIMM DDR3 1600MT/s              | 1         | 2.94%   |
| Unknown                                                        | 1         | 2.94%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 8         | 27.59%  |
| DDR     | 6         | 20.69%  |
| SDRAM   | 5         | 17.24%  |
| DDR2    | 5         | 17.24%  |
| DDR4    | 3         | 10.34%  |
| Unknown | 2         | 6.9%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 22        | 75.86%  |
| DIMM   | 7         | 24.14%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 1024  | 10        | 32.26%  |
| 2048  | 6         | 19.35%  |
| 512   | 5         | 16.13%  |
| 8192  | 4         | 12.9%   |
| 4096  | 4         | 12.9%   |
| 16384 | 1         | 3.23%   |
| 256   | 1         | 3.23%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| Unknown | 10        | 32.26%  |
| 1600    | 5         | 16.13%  |
| 667     | 4         | 12.9%   |
| 1333    | 2         | 6.45%   |
| 1067    | 2         | 6.45%   |
| 3266    | 1         | 3.23%   |
| 2667    | 1         | 3.23%   |
| 2400    | 1         | 3.23%   |
| 975     | 1         | 3.23%   |
| 800     | 1         | 3.23%   |
| 533     | 1         | 3.23%   |
| 400     | 1         | 3.23%   |
| 266     | 1         | 3.23%   |

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
| Chicony Electronics                    | 4         | 26.67%  |
| Pixart Imaging                         | 2         | 13.33%  |
| Microdia                               | 2         | 13.33%  |
| Suyin                                  | 1         | 6.67%   |
| Sunplus Innovation Technology          | 1         | 6.67%   |
| Lite-On Technology                     | 1         | 6.67%   |
| Importek                               | 1         | 6.67%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 6.67%   |
| Apple                                  | 1         | 6.67%   |
| Acer                                   | 1         | 6.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Pixart Imaging GE 1.3 MP MiniCam Pro                | 2         | 13.33%  |
| Suyin Lenovo EasyCamera                             | 1         | 6.67%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 6.67%   |
| Microdia Sonix USB 2.0 Camera                       | 1         | 6.67%   |
| Microdia Integrated Webcam                          | 1         | 6.67%   |
| Lite-On HP TrueVision HD Camera                     | 1         | 6.67%   |
| Importek FJ Camera                                  | 1         | 6.67%   |
| Chicony VGA 30fps UVC Webcam                        | 1         | 6.67%   |
| Chicony Integrated HP HD Webcam                     | 1         | 6.67%   |
| Chicony HP HD Webcam [Fixed]                        | 1         | 6.67%   |
| Chicony CNF8243 Webcam                              | 1         | 6.67%   |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC) | 1         | 6.67%   |
| Apple Built-in iSight                               | 1         | 6.67%   |
| Acer HP Webcam                                      | 1         | 6.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| AuthenTec        | 2         | 66.67%  |
| Validity Sensors | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Validity Sensors VFS491              | 1         | 33.33%  |
| AuthenTec AES2501 Fingerprint Sensor | 1         | 33.33%  |
| AuthenTec AES1600                    | 1         | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 2         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |
| Broadcom 5880                                  | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 25        | 78.13%  |
| 1     | 4         | 12.5%   |
| 2     | 3         | 9.38%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 4         | 40%     |
| Fingerprint reader       | 3         | 30%     |
| Modem                    | 1         | 10%     |
| Communication controller | 1         | 10%     |
| Chipcard                 | 1         | 10%     |

