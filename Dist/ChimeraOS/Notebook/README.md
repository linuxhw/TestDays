ChimeraOS - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for ChimeraOS.

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

Total: 38

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 15 7000 Gaming     | [6192c839f5](https://linux-hardware.org/?probe=6192c839f5) | Sep 06, 2023 |
| ASUSTek       | Zephyrus S GX502GV_GX502... | [3429c55014](https://linux-hardware.org/?probe=3429c55014) | Sep 06, 2023 |
| ASUSTek       | Zephyrus S GX502GV_GX502... | [72fb0f052e](https://linux-hardware.org/?probe=72fb0f052e) | Sep 06, 2023 |
| Dell          | Latitude 3590               | [9406fe5cf7](https://linux-hardware.org/?probe=9406fe5cf7) | Sep 02, 2023 |
| Acer          | Nitro AN515-57              | [ad8a62ee1d](https://linux-hardware.org/?probe=ad8a62ee1d) | Aug 14, 2023 |
| Anbernic      | Win600                      | [32213b8d3b](https://linux-hardware.org/?probe=32213b8d3b) | Aug 13, 2023 |
| GPD           | P2 MAX                      | [064bc78973](https://linux-hardware.org/?probe=064bc78973) | Aug 09, 2023 |
| HP            | Victus by Laptop 16-d1xx... | [74c80ca51b](https://linux-hardware.org/?probe=74c80ca51b) | Aug 06, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [d3e22fde36](https://linux-hardware.org/?probe=d3e22fde36) | Jul 25, 2023 |
| Lenovo        | ThinkPad E15 20RD0011IX     | [c7a1caa230](https://linux-hardware.org/?probe=c7a1caa230) | Jul 25, 2023 |
| Acer          | Aspire A715-42G             | [ac10700edb](https://linux-hardware.org/?probe=ac10700edb) | Jul 13, 2023 |
| AMI           | Unknown                     | [88da6b0232](https://linux-hardware.org/?probe=88da6b0232) | Jun 25, 2023 |
| Acer          | Aspire A315-58G             | [ea2b8a58b1](https://linux-hardware.org/?probe=ea2b8a58b1) | Jun 22, 2023 |
| Razer         | Blade 14 - RZ09-0370        | [4932ae40b6](https://linux-hardware.org/?probe=4932ae40b6) | Jun 13, 2023 |
| Google        | Snappy                      | [737988d62e](https://linux-hardware.org/?probe=737988d62e) | Jun 11, 2023 |
| Google        | Snappy                      | [f228dabe46](https://linux-hardware.org/?probe=f228dabe46) | Jun 11, 2023 |
| Lenovo        | Y50-70 20378                | [5e060b53c2](https://linux-hardware.org/?probe=5e060b53c2) | Jun 10, 2023 |
| Lenovo        | Y50-70 20378                | [0d548e314b](https://linux-hardware.org/?probe=0d548e314b) | Jun 10, 2023 |
| Acer          | Nitro AN515-51              | [4bbf7dc69e](https://linux-hardware.org/?probe=4bbf7dc69e) | May 21, 2023 |
| Micro Elec... | MG-VCP17I-3070              | [8ba5bb4bc7](https://linux-hardware.org/?probe=8ba5bb4bc7) | May 19, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | [79bdb284fe](https://linux-hardware.org/?probe=79bdb284fe) | May 09, 2023 |
| MSI           | CX62 6QD                    | [9c6b781beb](https://linux-hardware.org/?probe=9c6b781beb) | May 02, 2023 |
| HP            | 250 G4 Notebook PC          | [08036de728](https://linux-hardware.org/?probe=08036de728) | Apr 15, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [a34f2e065b](https://linux-hardware.org/?probe=a34f2e065b) | Apr 14, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | [cacab44211](https://linux-hardware.org/?probe=cacab44211) | Apr 13, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | [2a4894bdc0](https://linux-hardware.org/?probe=2a4894bdc0) | Apr 13, 2023 |
| MSI           | MS-7C91                     | [663c6729cb](https://linux-hardware.org/?probe=663c6729cb) | Apr 12, 2023 |
| Razer         | Blade Pro 17 (Early 2020... | [36d75e1d7f](https://linux-hardware.org/?probe=36d75e1d7f) | Mar 26, 2023 |
| Razer         | Blade Pro 17 (Early 2020... | [244b228a30](https://linux-hardware.org/?probe=244b228a30) | Mar 26, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [8a92687be7](https://linux-hardware.org/?probe=8a92687be7) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [f383688a79](https://linux-hardware.org/?probe=f383688a79) | Mar 23, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [de9712600d](https://linux-hardware.org/?probe=de9712600d) | Mar 20, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [1ee17b12bd](https://linux-hardware.org/?probe=1ee17b12bd) | Mar 19, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [b8ea458df5](https://linux-hardware.org/?probe=b8ea458df5) | Mar 08, 2023 |
| Acer          | Aspire A515-51G             | [432235c684](https://linux-hardware.org/?probe=432235c684) | Feb 25, 2023 |
| MSI           | GE75 Raider 10SF            | [cc21335206](https://linux-hardware.org/?probe=cc21335206) | Feb 24, 2023 |
| ASUSTek       | K45VM                       | [06af577a0c](https://linux-hardware.org/?probe=06af577a0c) | Feb 04, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [f5ff2f8568](https://linux-hardware.org/?probe=f5ff2f8568) | Jan 06, 2023 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| ChimeraOS 43-1 | 8         | 25%     |
| ChimeraOS 39   | 8         | 25%     |
| ChimeraOS 42   | 7         | 21.88%  |
| ChimeraOS 41   | 5         | 15.63%  |
| ChimeraOS 38   | 2         | 6.25%   |
| ChimeraOS 43   | 1         | 3.13%   |
| ChimeraOS      | 1         | 3.13%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| ChimeraOS | 32        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 6.3.9-chimeraos-1 | 9         | 28.13%  |
| 6.1.11-arch1-1    | 8         | 25%     |
| 6.1.27-1-lts      | 7         | 21.88%  |
| 6.1.21-1-lts      | 5         | 15.63%  |
| 6.1.1-arch1-1     | 2         | 6.25%   |
| 6.4.9-0-generic   | 1         | 3.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.3.9   | 9         | 28.13%  |
| 6.1.11  | 8         | 25%     |
| 6.1.27  | 7         | 21.88%  |
| 6.1.21  | 5         | 15.63%  |
| 6.1.1   | 2         | 6.25%   |
| 6.4.9   | 1         | 3.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 22        | 68.75%  |
| 6.3     | 9         | 28.13%  |
| 6.4     | 1         | 3.13%   |

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


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| GNOME | 32        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 30        | 93.75%  |
| X11     | 2         | 6.25%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 32        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 27        | 84.38%  |
| it_IT | 2         | 6.25%   |
| pt_BR | 1         | 3.13%   |
| es_ES | 1         | 3.13%   |
| C     | 1         | 3.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 32        | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 31        | 96.88%  |
| Ext4  | 1         | 3.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 32        | 100%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 32        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 32        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo            | 6         | 18.75%  |
| Acer              | 5         | 15.63%  |
| ASUSTek Computer  | 4         | 12.5%   |
| MSI               | 3         | 9.38%   |
| Hewlett-Packard   | 3         | 9.38%   |
| Razer             | 2         | 6.25%   |
| ONE-NETBOOK       | 2         | 6.25%   |
| Dell              | 2         | 6.25%   |
| Micro Electronics | 1         | 3.13%   |
| GPD               | 1         | 3.13%   |
| Google            | 1         | 3.13%   |
| Anbernic          | 1         | 3.13%   |
| AMI               | 1         | 3.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| ONE-NETBOOK ONEXPLAYER 2 ARP23              | 2         | 6.25%   |
| Razer Blade Pro 17 (Early 2020) - RZ09-0329 | 1         | 3.13%   |
| Razer Blade 14 - RZ09-0370                  | 1         | 3.13%   |
| MSI MS-7C91                                 | 1         | 3.13%   |
| MSI GE75 Raider 10SF                        | 1         | 3.13%   |
| MSI CX62 6QD                                | 1         | 3.13%   |
| Micro MG-VCP17I-3070                        | 1         | 3.13%   |
| Lenovo Y50-70 20378                         | 1         | 3.13%   |
| Lenovo ThinkPad E15 20RD0011IX              | 1         | 3.13%   |
| Lenovo Legion Y540-15IRH 81SX               | 1         | 3.13%   |
| Lenovo IdeaPad 700-15ISK 80RU               | 1         | 3.13%   |
| Lenovo IdeaPad 320-15IKB 80YH               | 1         | 3.13%   |
| Lenovo IdeaPad 3 15ADA05 81W1               | 1         | 3.13%   |
| HP Victus by Laptop 16-d1xxx                | 1         | 3.13%   |
| HP EliteBook 850 G8 Notebook PC             | 1         | 3.13%   |
| HP 250 G4 Notebook PC                       | 1         | 3.13%   |
| GPD P2 MAX                                  | 1         | 3.13%   |
| Google Snappy                               | 1         | 3.13%   |
| Dell Latitude 3590                          | 1         | 3.13%   |
| Dell Inspiron 15 7000 Gaming                | 1         | 3.13%   |
| ASUS Zephyrus S GX502GV_GX502GV             | 1         | 3.13%   |
| ASUS TUF Gaming FX505DV_FX505DV             | 1         | 3.13%   |
| ASUS ROG Zephyrus G15 GA503QM_GA503QM       | 1         | 3.13%   |
| ASUS K45VM                                  | 1         | 3.13%   |
| Anbernic Win600                             | 1         | 3.13%   |
| Acer Nitro AN515-57                         | 1         | 3.13%   |
| Acer Nitro AN515-51                         | 1         | 3.13%   |
| Acer Aspire A715-42G                        | 1         | 3.13%   |
| Acer Aspire A515-51G                        | 1         | 3.13%   |
| Acer Aspire A315-58G                        | 1         | 3.13%   |
| Unknown                                     | 1         | 3.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo IdeaPad         | 3         | 9.38%   |
| Acer Aspire            | 3         | 9.38%   |
| Razer Blade            | 2         | 6.25%   |
| ONE-NETBOOK ONEXPLAYER | 2         | 6.25%   |
| Acer Nitro             | 2         | 6.25%   |
| MSI MS-7C91            | 1         | 3.13%   |
| MSI GE75               | 1         | 3.13%   |
| MSI CX62               | 1         | 3.13%   |
| Micro MG-VCP17I-3070   | 1         | 3.13%   |
| Lenovo Y50-70          | 1         | 3.13%   |
| Lenovo ThinkPad        | 1         | 3.13%   |
| Lenovo Legion          | 1         | 3.13%   |
| HP Victus              | 1         | 3.13%   |
| HP EliteBook           | 1         | 3.13%   |
| HP 250                 | 1         | 3.13%   |
| GPD P2                 | 1         | 3.13%   |
| Google Snappy          | 1         | 3.13%   |
| Dell Latitude          | 1         | 3.13%   |
| Dell Inspiron          | 1         | 3.13%   |
| ASUS Zephyrus          | 1         | 3.13%   |
| ASUS TUF               | 1         | 3.13%   |
| ASUS ROG               | 1         | 3.13%   |
| ASUS K45VM             | 1         | 3.13%   |
| Anbernic Win600        | 1         | 3.13%   |
| Unknown                | 1         | 3.13%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 7         | 21.88%  |
| 2020 | 5         | 15.63%  |
| 2019 | 4         | 12.5%   |
| 2017 | 4         | 12.5%   |
| 2023 | 3         | 9.38%   |
| 2022 | 2         | 6.25%   |
| 2016 | 2         | 6.25%   |
| 2015 | 2         | 6.25%   |
| 2018 | 1         | 3.13%   |
| 2014 | 1         | 3.13%   |
| 2012 | 1         | 3.13%   |

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
| Disabled | 32        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 31        | 96.88%  |
| Yes  | 1         | 3.13%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 8         | 25%     |
| 4.01-8.0    | 5         | 15.63%  |
| 32.01-64.0  | 5         | 15.63%  |
| 8.01-16.0   | 5         | 15.63%  |
| 3.01-4.0    | 4         | 12.5%   |
| 24.01-32.0  | 3         | 9.38%   |
| 64.01-256.0 | 2         | 6.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 14        | 43.75%  |
| 1.01-2.0 | 8         | 25%     |
| 3.01-4.0 | 7         | 21.88%  |
| 4.01-8.0 | 3         | 9.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 17        | 53.13%  |
| 2      | 14        | 43.75%  |
| 3      | 1         | 3.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 31        | 96.88%  |
| Yes       | 1         | 3.13%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 75%     |
| No        | 8         | 25%     |

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
| Yes       | 31        | 96.88%  |
| No        | 1         | 3.13%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 13        | 40.63%  |
| Vietnam      | 2         | 6.25%   |
| UK           | 2         | 6.25%   |
| Saudi Arabia | 2         | 6.25%   |
| Italy        | 2         | 6.25%   |
| Brazil       | 2         | 6.25%   |
| Switzerland  | 1         | 3.13%   |
| Spain        | 1         | 3.13%   |
| Romania      | 1         | 3.13%   |
| Poland       | 1         | 3.13%   |
| Netherlands  | 1         | 3.13%   |
| Hungary      | 1         | 3.13%   |
| Germany      | 1         | 3.13%   |
| Costa Rica   | 1         | 3.13%   |
| Belgium      | 1         | 3.13%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Wroclaw                  | 1         | 3.13%   |
| Vũng Tàu               | 1         | 3.13%   |
| Virginia Beach           | 1         | 3.13%   |
| Tulcea                   | 1         | 3.13%   |
| St Louis                 | 1         | 3.13%   |
| Santa Cruz das Palmeiras | 1         | 3.13%   |
| San José                | 1         | 3.13%   |
| Saltillo                 | 1         | 3.13%   |
| Ridley Park              | 1         | 3.13%   |
| Pittsburg                | 1         | 3.13%   |
| Pennsauken               | 1         | 3.13%   |
| Parma                    | 1         | 3.13%   |
| Newport News             | 1         | 3.13%   |
| Monticello               | 1         | 3.13%   |
| Milan                    | 1         | 3.13%   |
| Legazpia                 | 1         | 3.13%   |
| Jeddah                   | 1         | 3.13%   |
| Hot Springs              | 1         | 3.13%   |
| Highland Park            | 1         | 3.13%   |
| Gelsenkirchen            | 1         | 3.13%   |
| Fairbanks                | 1         | 3.13%   |
| Dammam                   | 1         | 3.13%   |
| Chattanooga              | 1         | 3.13%   |
| Charlotte                | 1         | 3.13%   |
| Budapest                 | 1         | 3.13%   |
| Brussels                 | 1         | 3.13%   |
| Binh Duong               | 1         | 3.13%   |
| Biel/Bienne              | 1         | 3.13%   |
| Belfast                  | 1         | 3.13%   |
| Barnet                   | 1         | 3.13%   |
| Araras                   | 1         | 3.13%   |
| Almere Stad              | 1         | 3.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 7         | 7      | 14.58%  |
| Micron Technology         | 6         | 6      | 12.5%   |
| WDC                       | 5         | 5      | 10.42%  |
| Unknown                   | 4         | 4      | 8.33%   |
| Kingston                  | 4         | 4      | 8.33%   |
| Seagate                   | 3         | 3      | 6.25%   |
| Sandisk                   | 3         | 3      | 6.25%   |
| Intel                     | 3         | 3      | 6.25%   |
| Toshiba                   | 2         | 2      | 4.17%   |
| SK hynix                  | 2         | 2      | 4.17%   |
| Micron/Crucial Technology | 2         | 2      | 4.17%   |
| WDC PC S                  | 1         | 1      | 2.08%   |
| Phison Electronics        | 1         | 1      | 2.08%   |
| NT-1TB                    | 1         | 1      | 2.08%   |
| KIOXIA                    | 1         | 1      | 2.08%   |
| JMicron Technology        | 1         | 1      | 2.08%   |
| Crucial                   | 1         | 1      | 2.08%   |
| Biwin Storage Technology  | 1         | 1      | 2.08%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 3         | 6.25%   |
| Unknown MMC Card  64GB                                | 2         | 4.17%   |
| SK hynix HFM512GD3JX016N 512GB                        | 2         | 4.17%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 2         | 4.17%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                   | 2         | 4.17%   |
| Micron 1100 SATA 256GB SSD                            | 2         | 4.17%   |
| WDC WD7500BPVT-80HXZT3 752GB                          | 1         | 2.08%   |
| WDC WD20SPZX-08UA7 2TB                                | 1         | 2.08%   |
| WDC WD201KFGX-68BKJN0 20TB                            | 1         | 2.08%   |
| WDC WD10SPCX-24HWST1 1TB                              | 1         | 2.08%   |
| WDC WD10JPLX-00MBPT0 1TB                              | 1         | 2.08%   |
| WDC PC S N530 SDBPNPZ 256GB                           | 1         | 2.08%   |
| Unknown NVMe SSD Drive 1024GB                         | 1         | 2.08%   |
| Unknown MMC Card  16GB                                | 1         | 2.08%   |
| Toshiba XG6 NVMe SSD Controller 1024GB                | 1         | 2.08%   |
| Toshiba MQ01ABF050 500GB                              | 1         | 2.08%   |
| Seagate ST9320423AS 320GB                             | 1         | 2.08%   |
| Seagate ST1000LM048-2E7172 1TB                        | 1         | 2.08%   |
| Seagate ST1000LM035-1RK172 1TB                        | 1         | 2.08%   |
| Sandisk WD_BLACK SN770 2TB                            | 1         | 2.08%   |
| Sandisk WD Black SN850 256GB                          | 1         | 2.08%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB     | 1         | 2.08%   |
| Samsung Portable SSD T5 1TB                           | 1         | 2.08%   |
| Samsung MZNLF128HCHP-000H1 128GB SSD                  | 1         | 2.08%   |
| Phison E12 NVMe Controller 256GB                      | 1         | 2.08%   |
| NT-1TB 2242 1024GB                                    | 1         | 2.08%   |
| Micron MTFDHBA512QFD 512GB                            | 1         | 2.08%   |
| Micron 2200V_MTFDHBA512TCK 512GB                      | 1         | 2.08%   |
| Micron 1100_MTFDDAV512TBN 512GB SSD                   | 1         | 2.08%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD                   | 1         | 2.08%   |
| KIOXIA KBG40ZNT512G TOSHIBA MEMORY 512GB              | 1         | 2.08%   |
| Kingston SV300S37A120G 120GB SSD                      | 1         | 2.08%   |
| Kingston SV100S2128G 128GB SSD                        | 1         | 2.08%   |
| Kingston SA400S37480G 480GB SSD                       | 1         | 2.08%   |
| Kingston SA400S37120G 120GB SSD                       | 1         | 2.08%   |
| JMicron Tech 250GB                                    | 1         | 2.08%   |
| Intel SSDPEKNU512GZ 512GB                             | 1         | 2.08%   |
| Intel SSD 660P Series 512GB                           | 1         | 2.08%   |
| Intel SSD 600P Series 256GB                           | 1         | 2.08%   |
| Crucial CT240BX200SSD1 240GB                          | 1         | 2.08%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 5      | 55.56%  |
| Seagate | 3         | 3      | 33.33%  |
| Toshiba | 1         | 1      | 11.11%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Micron Technology   | 4         | 4      | 33.33%  |
| Kingston            | 4         | 4      | 33.33%  |
| Samsung Electronics | 2         | 2      | 16.67%  |
| NT-1TB              | 1         | 1      | 8.33%   |
| Crucial             | 1         | 1      | 8.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 20        | 22     | 46.51%  |
| SSD     | 10        | 12     | 23.26%  |
| HDD     | 8         | 9      | 18.6%   |
| MMC     | 3         | 3      | 6.98%   |
| Unknown | 2         | 2      | 4.65%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 20        | 22     | 48.78%  |
| SATA | 15        | 20     | 36.59%  |
| SAS  | 3         | 3      | 7.32%   |
| MMC  | 3         | 3      | 7.32%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 8         | 11     | 44.44%  |
| 0.51-1.0   | 7         | 7      | 38.89%  |
| 1.01-2.0   | 2         | 2      | 11.11%  |
| 10.01-20.0 | 1         | 1      | 5.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 1001-2000      | 13        | 40.63%  |
| More than 3000 | 9         | 28.13%  |
| 251-500        | 5         | 15.63%  |
| 501-1000       | 3         | 9.38%   |
| 101-250        | 2         | 6.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 21-50          | 13        | 40.63%  |
| 101-250        | 6         | 18.75%  |
| 51-100         | 5         | 15.63%  |
| 251-500        | 4         | 12.5%   |
| 501-1000       | 2         | 6.25%   |
| More than 3000 | 1         | 3.13%   |
| 1-20           | 1         | 3.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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
| Detected | 32        | 48     | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 20        | 46.51%  |
| Samsung Electronics          | 5         | 11.63%  |
| AMD                          | 4         | 9.3%    |
| SanDisk                      | 3         | 6.98%   |
| SK hynix                     | 2         | 4.65%   |
| Micron/Crucial Technology    | 2         | 4.65%   |
| Micron Technology            | 2         | 4.65%   |
| Toshiba America Info Systems | 1         | 2.33%   |
| Phison Electronics           | 1         | 2.33%   |
| KIOXIA                       | 1         | 2.33%   |
| INNOGRIT                     | 1         | 2.33%   |
| Biwin Storage Technology     | 1         | 2.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 6.52%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 6.52%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 6.52%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 6.52%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 3         | 6.52%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 2         | 4.35%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 4.35%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2         | 4.35%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 2         | 4.35%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 4.35%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 4.35%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 2.17%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 2.17%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1         | 2.17%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 2.17%   |
| Phison E12 NVMe Controller                                                     | 1         | 2.17%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 1         | 2.17%   |
| Micron 2200S NVMe SSD [Cassandra]                                              | 1         | 2.17%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 1         | 2.17%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 2.17%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 1         | 2.17%   |
| Intel SSD 660P Series                                                          | 1         | 2.17%   |
| Intel SSD 600P Series                                                          | 1         | 2.17%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 2.17%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 2.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 2.17%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 2.17%   |
| INNOGRIT NVMe SSD Controller IG5236                                            | 1         | 2.17%   |
| Biwin Storage Non-Volatile memory controller                                   | 1         | 2.17%   |
| AMD 500 Series Chipset SATA Controller                                         | 1         | 2.17%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 20        | 45.45%  |
| SATA | 18        | 40.91%  |
| RAID | 6         | 13.64%  |

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


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 6.25%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 2         | 6.25%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 2         | 6.25%   |
| AMD Ryzen 7 6800U with Radeon Graphics        | 2         | 6.25%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 1         | 3.13%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 3.13%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 3.13%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 3.13%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 3.13%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 3.13%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 3.13%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 3.13%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 3.13%   |
| Intel Core i5-4210H CPU @ 2.90GHz             | 1         | 3.13%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 1         | 3.13%   |
| Intel Atom x7-Z8700 CPU @ 1.60GHz             | 1         | 3.13%   |
| Intel 12th Gen Core i7-12700H                 | 1         | 3.13%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 1         | 3.13%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 1         | 3.13%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz       | 1         | 3.13%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 3.13%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 1         | 3.13%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 1         | 3.13%   |
| AMD Ryzen 9 5900HS with Radeon Graphics       | 1         | 3.13%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 1         | 3.13%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 1         | 3.13%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 3.13%   |
| AMD Athlon Silver 3050e with Radeon Graphics  | 1         | 3.13%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Intel Core i5 | 8         | 25%     |
| Intel Core i7 | 7         | 21.88%  |
| Other         | 5         | 15.63%  |
| AMD Ryzen 9   | 3         | 9.38%   |
| AMD Ryzen 7   | 3         | 9.38%   |
| AMD Ryzen 5   | 2         | 6.25%   |
| Intel Core m3 | 1         | 3.13%   |
| Intel Celeron | 1         | 3.13%   |
| Intel Atom    | 1         | 3.13%   |
| AMD Athlon    | 1         | 3.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 12        | 37.5%   |
| 2      | 7         | 21.88%  |
| 8      | 6         | 18.75%  |
| 6      | 5         | 15.63%  |
| 14     | 1         | 3.13%   |
| 12     | 1         | 3.13%   |

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
| 2      | 25        | 78.13%  |
| 1      | 7         | 21.88%  |

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


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 32        | 100%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KabyLake   | 9         | 28.13%  |
| Unknown    | 6         | 18.75%  |
| Zen 3      | 3         | 9.38%   |
| Skylake    | 3         | 9.38%   |
| Zen+       | 2         | 6.25%   |
| TigerLake  | 2         | 6.25%   |
| CometLake  | 2         | 6.25%   |
| Zen        | 1         | 3.13%   |
| Silvermont | 1         | 3.13%   |
| IvyBridge  | 1         | 3.13%   |
| Haswell    | 1         | 3.13%   |
| Goldmont   | 1         | 3.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 20        | 40.82%  |
| Nvidia | 19        | 38.78%  |
| AMD    | 10        | 20.41%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 6.12%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 2         | 4.08%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 4.08%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 2         | 4.08%   |
| Intel UHD Graphics 620                                                                   | 2         | 4.08%   |
| Intel HD Graphics 630                                                                    | 2         | 4.08%   |
| Intel HD Graphics 530                                                                    | 2         | 4.08%   |
| AMD Rembrandt [Radeon 680M]                                                              | 2         | 4.08%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 4.08%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 2.04%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 2.04%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 2.04%   |
| Nvidia TU106BM [GeForce RTX 2060 Mobile]                                                 | 1         | 2.04%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                                    | 1         | 2.04%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 2.04%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 2.04%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 2.04%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 2.04%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 2.04%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 2.04%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 2.04%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 2.04%   |
| Intel UHD Graphics 615                                                                   | 1         | 2.04%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 2.04%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 2.04%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 1         | 2.04%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 2.04%   |
| Intel HD Graphics 620                                                                    | 1         | 2.04%   |
| Intel HD Graphics 500                                                                    | 1         | 2.04%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 2.04%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 2.04%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 2.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.04%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 1         | 2.04%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 2.04%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 2.04%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX]                                                 | 1         | 2.04%   |
| AMD Lucienne                                                                             | 1         | 2.04%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 1         | 2.04%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 12        | 37.5%   |
| 1 x Intel      | 6         | 18.75%  |
| 1 x AMD        | 5         | 15.63%  |
| AMD + Nvidia   | 4         | 12.5%   |
| 1 x Nvidia     | 3         | 9.38%   |
| Other          | 1         | 3.13%   |
| Intel + AMD    | 1         | 3.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Proprietary | 18        | 56.25%  |
| Free        | 14        | 43.75%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 32        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Chimei Innolux      | 7         | 21.88%  |
| BOE                 | 6         | 18.75%  |
| LG Display          | 5         | 15.63%  |
| AU Optronics        | 5         | 15.63%  |
| Samsung Electronics | 2         | 6.25%   |
| TMX                 | 1         | 3.13%   |
| Sharp               | 1         | 3.13%   |
| RTK                 | 1         | 3.13%   |
| PANDA               | 1         | 3.13%   |
| Insignia            | 1         | 3.13%   |
| Goldstar            | 1         | 3.13%   |
| Fujitsu Siemens     | 1         | 3.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| BOE FLQ8423-24L0 BOE1003 1600x2560 113x181mm 8.4-inch                | 2         | 6.25%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch              | 1         | 3.13%   |
| Sharp LQ173M1JW02 SHP14DB 1920x1080 382x215mm 17.3-inch              | 1         | 3.13%   |
| Samsung Electronics QBQ95 SAM7229 3840x2160 1872x1053mm 84.6-inch    | 1         | 3.13%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch | 1         | 3.13%   |
| RTK FHD HDR RTK2A3B 1920x1080 344x195mm 15.6-inch                    | 1         | 3.13%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 1         | 3.13%   |
| LG Display LCD Monitor LGD071E 1920x1080 344x194mm 15.5-inch         | 1         | 3.13%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch         | 1         | 3.13%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch         | 1         | 3.13%   |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch         | 1         | 3.13%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch          | 1         | 3.13%   |
| Insignia NS-39L240A13 BBY0042 1920x1080 544x326mm 25.0-inch          | 1         | 3.13%   |
| Goldstar M237WDP GSM5779 1920x1080 598x336mm 27.0-inch               | 1         | 3.13%   |
| Fujitsu Siemens B22T-7 LED PG FUS082A 1920x1080 477x268mm 21.5-inch  | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN176E 1920x1080 381x214mm 17.2-inch     | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch     | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN1540 2560x1440 344x193mm 15.5-inch     | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 1         | 3.13%   |
| BOE LCD Monitor BOE0AAD 1920x1080 355x200mm 16.0-inch                | 1         | 3.13%   |
| BOE LCD Monitor BOE0977 2560x1440 381x214mm 17.2-inch                | 1         | 3.13%   |
| BOE LCD Monitor BOE0816 1366x768 344x193mm 15.5-inch                 | 1         | 3.13%   |
| BOE LCD Monitor BOE065D 1920x1080 344x194mm 15.5-inch                | 1         | 3.13%   |
| AU Optronics LCD Monitor AUOD0ED 1920x1080 344x193mm 15.5-inch       | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO82ED 1920x1080 344x194mm 15.5-inch       | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO135C 1366x768 256x144mm 11.6-inch        | 1         | 3.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 19        | 61.29%  |
| 1366x768 (WXGA) | 5         | 16.13%  |
| 2560x1440 (QHD) | 3         | 9.68%   |
| 3840x2160 (4K)  | 2         | 6.45%   |
| 1600x2560       | 2         | 6.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 18        | 56.25%  |
| 17     | 3         | 9.38%   |
| 14     | 2         | 6.25%   |
| 8      | 2         | 6.25%   |
| 84     | 1         | 3.13%   |
| 57     | 1         | 3.13%   |
| 49     | 1         | 3.13%   |
| 27     | 1         | 3.13%   |
| 21     | 1         | 3.13%   |
| 16     | 1         | 3.13%   |
| 11     | 1         | 3.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 20        | 62.5%   |
| 351-400     | 4         | 12.5%   |
| 101-200     | 2         | 6.25%   |
| 701-800     | 1         | 3.13%   |
| 501-600     | 1         | 3.13%   |
| 401-500     | 1         | 3.13%   |
| 201-300     | 1         | 3.13%   |
| 1501-2000   | 1         | 3.13%   |
| 1001-1500   | 1         | 3.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 28        | 90.32%  |
| 0.62  | 2         | 6.45%   |
| 0.56  | 1         | 3.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 19        | 61.29%  |
| 121-130        | 3         | 9.68%   |
| More than 1000 | 2         | 6.45%   |
| 81-90          | 2         | 6.45%   |
| 1-40           | 2         | 6.45%   |
| 51-60          | 1         | 3.23%   |
| 301-350        | 1         | 3.23%   |
| 201-250        | 1         | 3.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 18        | 58.06%  |
| 101-120       | 5         | 16.13%  |
| 161-240       | 3         | 9.68%   |
| More than 240 | 2         | 6.45%   |
| 51-100        | 2         | 6.45%   |
| 1-50          | 1         | 3.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 26        | 81.25%  |
| 2     | 4         | 12.5%   |
| 0     | 2         | 6.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 21        | 38.89%  |
| Intel                 | 18        | 33.33%  |
| Qualcomm Atheros      | 8         | 14.81%  |
| MediaTek              | 4         | 7.41%   |
| Broadcom Limited      | 1         | 1.85%   |
| Broadcom              | 1         | 1.85%   |
| ASIX Electronics      | 1         | 1.85%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 28.57%  |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 5.36%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 5.36%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 5.36%   |
| Intel Wireless 3165                                               | 3         | 5.36%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 5.36%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 3.57%   |
| Intel Wireless 7265                                               | 2         | 3.57%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 3.57%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 3.57%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 3.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 3.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 1.79%   |
| Realtek PCIe GbE Family Controller                                | 1         | 1.79%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.79%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.79%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 1.79%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1         | 1.79%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 1.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.79%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter        | 1         | 1.79%   |
| Broadcom BCM4356 802.11ac Wireless Network Adapter                | 1         | 1.79%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.79%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 18        | 56.25%  |
| Qualcomm Atheros      | 6         | 18.75%  |
| MediaTek              | 4         | 12.5%   |
| Realtek Semiconductor | 2         | 6.25%   |
| Broadcom Limited      | 1         | 3.13%   |
| Broadcom              | 1         | 3.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 3         | 9.38%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 3         | 9.38%   |
| Intel Wireless 3165                                           | 3         | 9.38%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 3         | 9.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 2         | 6.25%   |
| Intel Wireless 7265                                           | 2         | 6.25%   |
| Intel Wi-Fi 6 AX201                                           | 2         | 6.25%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 2         | 6.25%   |
| Intel Comet Lake PCH CNVi WiFi                                | 2         | 6.25%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 2         | 6.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 1         | 3.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 1         | 3.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 1         | 3.13%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 1         | 3.13%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 1         | 3.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 1         | 3.13%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter    | 1         | 3.13%   |
| Broadcom BCM4356 802.11ac Wireless Network Adapter            | 1         | 3.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 21        | 87.5%   |
| Qualcomm Atheros      | 2         | 8.33%   |
| ASIX Electronics      | 1         | 4.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 66.67%  |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 12.5%   |
| Realtek PCIe GbE Family Controller                                | 1         | 4.17%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 4.17%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 4.17%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 4.17%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 4.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 32        | 57.14%  |
| Ethernet | 24        | 42.86%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 28        | 82.35%  |
| Ethernet | 6         | 17.65%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 23        | 71.88%  |
| 1     | 9         | 28.13%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 23        | 71.88%  |
| Yes  | 9         | 28.13%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 18        | 58.06%  |
| Qualcomm Atheros Communications | 3         | 9.68%   |
| Lite-On Technology              | 3         | 9.68%   |
| IMC Networks                    | 3         | 9.68%   |
| Realtek Semiconductor           | 1         | 3.23%   |
| MediaTek                        | 1         | 3.23%   |
| Foxconn / Hon Hai               | 1         | 3.23%   |
| Cambridge Silicon Radio         | 1         | 3.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 6         | 19.35%  |
| Intel AX201 Bluetooth                               | 6         | 19.35%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 9.68%   |
| Intel AX210 Bluetooth                               | 3         | 9.68%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 6.45%   |
| IMC Networks Wireless_Device                        | 2         | 6.45%   |
| Realtek Bluetooth Radio                             | 1         | 3.23%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 3.23%   |
| MediaTek Wireless_Device                            | 1         | 3.23%   |
| Lite-On Wireless_Device                             | 1         | 3.23%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 3.23%   |
| Lite-On Bluetooth Device                            | 1         | 3.23%   |
| IMC Networks Bluetooth Radio                        | 1         | 3.23%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 3.23%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 22        | 46.81%  |
| Nvidia                 | 13        | 27.66%  |
| AMD                    | 9         | 19.15%  |
| Sony                   | 1         | 2.13%   |
| Realtek Semiconductor  | 1         | 2.13%   |
| Generalplus Technology | 1         | 2.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                              | 8         | 14.55%  |
| Intel Sunrise Point-LP HD Audio                                     | 5         | 9.09%   |
| Nvidia TU106 High Definition Audio Controller                       | 3         | 5.45%   |
| Nvidia GP107GL High Definition Audio Controller                     | 2         | 3.64%   |
| Nvidia GA106 High Definition Audio Controller                       | 2         | 3.64%   |
| Nvidia GA104 High Definition Audio Controller                       | 2         | 3.64%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 2         | 3.64%   |
| Intel Tiger Lake-H HD Audio Controller                              | 2         | 3.64%   |
| Intel Comet Lake PCH cAVS                                           | 2         | 3.64%   |
| Intel CM238 HD Audio Controller                                     | 2         | 3.64%   |
| Intel Cannon Lake PCH cAVS                                          | 2         | 3.64%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 2         | 3.64%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 2         | 3.64%   |
| AMD Rembrandt Radeon High Definition Audio Controller               | 2         | 3.64%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 2         | 3.64%   |
| Sony DualSense Wireless Controller                                  | 1         | 1.82%   |
| Realtek Semiconductor USB Audio                                     | 1         | 1.82%   |
| Nvidia TU116 High Definition Audio Controller                       | 1         | 1.82%   |
| Nvidia TU104 HD Audio Controller                                    | 1         | 1.82%   |
| Nvidia GF108 High Definition Audio Controller                       | 1         | 1.82%   |
| Nvidia Audio device                                                 | 1         | 1.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 1         | 1.82%   |
| Intel Comet Lake PCH-LP cAVS                                        | 1         | 1.82%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster   | 1         | 1.82%   |
| Intel Alder Lake PCH-P High Definition Audio Controller             | 1         | 1.82%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 1         | 1.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 1         | 1.82%   |
| Generalplus Technology USB Audio Device                             | 1         | 1.82%   |
| AMD Starship/Matisse HD Audio Controller                            | 1         | 1.82%   |
| AMD Navi 31 HDMI/DP Audio                                           | 1         | 1.82%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

Zero info for selected period =(

Memory Model
------------

Memory module models

Zero info for selected period =(

Memory Kind
-----------

Memory module kinds

Zero info for selected period =(

Memory Form Factor
------------------

Physical design of the memory module

Zero info for selected period =(

Memory Size
-----------

Memory module size

Zero info for selected period =(

Memory Speed
------------

Memory module speed

Zero info for selected period =(

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


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 9         | 40.91%  |
| IMC Networks                  | 4         | 18.18%  |
| Sunplus Innovation Technology | 2         | 9.09%   |
| Quanta                        | 2         | 9.09%   |
| Silicon Motion                | 1         | 4.55%   |
| Realtek Semiconductor         | 1         | 4.55%   |
| Microdia                      | 1         | 4.55%   |
| Bison Electronics             | 1         | 4.55%   |
| Acer                          | 1         | 4.55%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                             | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| IMC Networks Integrated Camera    | 3         | 13.64%  |
| Chicony Integrated Camera         | 2         | 9.09%   |
| Chicony HD User Facing            | 2         | 9.09%   |
| Sunplus Integrated_Webcam_HD      | 1         | 4.55%   |
| Sunplus HD WebCam                 | 1         | 4.55%   |
| Silicon Motion 300k Pixel Camera  | 1         | 4.55%   |
| Realtek Integrated Webcam         | 1         | 4.55%   |
| Quanta HP HD Camera               | 1         | 4.55%   |
| Quanta HD User Facing             | 1         | 4.55%   |
| Microdia HP Webcam                | 1         | 4.55%   |
| IMC Networks USB2.0 HD UVC WebCam | 1         | 4.55%   |
| Chicony USB2.0 0.3M UVC WebCam    | 1         | 4.55%   |
| Chicony Integrated IR Camera      | 1         | 4.55%   |
| Chicony HP Wide Vision HD Camera  | 1         | 4.55%   |
| Chicony HP Truevision HD          | 1         | 4.55%   |
| Chicony EasyCamera                | 1         | 4.55%   |
| Bison Lenovo EasyCamera           | 1         | 4.55%   |
| Acer Lenovo EasyCamera            | 1         | 4.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 1         | 50%     |
| Shenzhen Goodix Technology | 1         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 50%     |
| Shenzhen Goodix  FingerPrint Device                      | 1         | 50%     |

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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 26        | 81.25%  |
| 1     | 6         | 18.75%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Multimedia controller | 2         | 33.33%  |
| Fingerprint reader    | 2         | 33.33%  |
| Net/wireless          | 1         | 16.67%  |
| Graphics card         | 1         | 16.67%  |

