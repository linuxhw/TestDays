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

Total: 43

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Alienware     | 17 R2                       | [6ad5704e29](https://linux-hardware.org/?probe=6ad5704e29) | Sep 21, 2023 |
| Alienware     | 17 R2                       | [76bf895d62](https://linux-hardware.org/?probe=76bf895d62) | Sep 21, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [4298a1ab82](https://linux-hardware.org/?probe=4298a1ab82) | Sep 16, 2023 |
| Gigabyte      | Z97X-Gaming 5               | [a3cdc2345d](https://linux-hardware.org/?probe=a3cdc2345d) | Sep 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [584a31e54e](https://linux-hardware.org/?probe=584a31e54e) | Sep 07, 2023 |
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
| ChimeraOS 43-1 | 12        | 33.33%  |
| ChimeraOS 39   | 8         | 22.22%  |
| ChimeraOS 42   | 7         | 19.44%  |
| ChimeraOS 41   | 5         | 13.89%  |
| ChimeraOS 38   | 2         | 5.56%   |
| ChimeraOS 43   | 1         | 2.78%   |
| ChimeraOS      | 1         | 2.78%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| ChimeraOS | 36        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 6.3.9-chimeraos-1 | 13        | 36.11%  |
| 6.1.11-arch1-1    | 8         | 22.22%  |
| 6.1.27-1-lts      | 7         | 19.44%  |
| 6.1.21-1-lts      | 5         | 13.89%  |
| 6.1.1-arch1-1     | 2         | 5.56%   |
| 6.4.9-0-generic   | 1         | 2.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.3.9   | 13        | 36.11%  |
| 6.1.11  | 8         | 22.22%  |
| 6.1.27  | 7         | 19.44%  |
| 6.1.21  | 5         | 13.89%  |
| 6.1.1   | 2         | 5.56%   |
| 6.4.9   | 1         | 2.78%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 22        | 61.11%  |
| 6.3     | 13        | 36.11%  |
| 6.4     | 1         | 2.78%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 36        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| GNOME | 36        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 34        | 94.44%  |
| X11     | 2         | 5.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 36        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 29        | 80.56%  |
| pt_BR | 2         | 5.56%   |
| it_IT | 2         | 5.56%   |
| es_ES | 2         | 5.56%   |
| C     | 1         | 2.78%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 36        | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 35        | 97.22%  |
| Ext4  | 1         | 2.78%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 36        | 100%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 36        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 36        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 6         | 16.67%  |
| ASUSTek Computer    | 6         | 16.67%  |
| Acer                | 5         | 13.89%  |
| MSI                 | 3         | 8.33%   |
| Hewlett-Packard     | 3         | 8.33%   |
| Razer               | 2         | 5.56%   |
| ONE-NETBOOK         | 2         | 5.56%   |
| Dell                | 2         | 5.56%   |
| Micro Electronics   | 1         | 2.78%   |
| GPD                 | 1         | 2.78%   |
| Google              | 1         | 2.78%   |
| Gigabyte Technology | 1         | 2.78%   |
| Anbernic            | 1         | 2.78%   |
| AMI                 | 1         | 2.78%   |
| Alienware           | 1         | 2.78%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| ONE-NETBOOK ONEXPLAYER 2 ARP23              | 2         | 5.56%   |
| Razer Blade Pro 17 (Early 2020) - RZ09-0329 | 1         | 2.78%   |
| Razer Blade 14 - RZ09-0370                  | 1         | 2.78%   |
| MSI MS-7C91                                 | 1         | 2.78%   |
| MSI GE75 Raider 10SF                        | 1         | 2.78%   |
| MSI CX62 6QD                                | 1         | 2.78%   |
| Micro MG-VCP17I-3070                        | 1         | 2.78%   |
| Lenovo Y50-70 20378                         | 1         | 2.78%   |
| Lenovo ThinkPad E15 20RD0011IX              | 1         | 2.78%   |
| Lenovo Legion Y540-15IRH 81SX               | 1         | 2.78%   |
| Lenovo IdeaPad 700-15ISK 80RU               | 1         | 2.78%   |
| Lenovo IdeaPad 320-15IKB 80YH               | 1         | 2.78%   |
| Lenovo IdeaPad 3 15ADA05 81W1               | 1         | 2.78%   |
| HP Victus by Laptop 16-d1xxx                | 1         | 2.78%   |
| HP EliteBook 850 G8 Notebook PC             | 1         | 2.78%   |
| HP 250 G4 Notebook PC                       | 1         | 2.78%   |
| GPD P2 MAX                                  | 1         | 2.78%   |
| Google Snappy                               | 1         | 2.78%   |
| Gigabyte Z97X-Gaming 5                      | 1         | 2.78%   |
| Dell Latitude 3590                          | 1         | 2.78%   |
| Dell Inspiron 15 7000 Gaming                | 1         | 2.78%   |
| ASUS Zephyrus S GX502GV_GX502GV             | 1         | 2.78%   |
| ASUS VivoBook_ASUSLaptop X570DD_X570DD      | 1         | 2.78%   |
| ASUS TUF Gaming FX505DV_FX505DV             | 1         | 2.78%   |
| ASUS ROG Zephyrus G15 GA503QM_GA503QM       | 1         | 2.78%   |
| ASUS ROG CROSSHAIR VIII HERO                | 1         | 2.78%   |
| ASUS K45VM                                  | 1         | 2.78%   |
| Anbernic Win600                             | 1         | 2.78%   |
| Alienware 17 R2                             | 1         | 2.78%   |
| Acer Nitro AN515-57                         | 1         | 2.78%   |
| Acer Nitro AN515-51                         | 1         | 2.78%   |
| Acer Aspire A715-42G                        | 1         | 2.78%   |
| Acer Aspire A515-51G                        | 1         | 2.78%   |
| Acer Aspire A315-58G                        | 1         | 2.78%   |
| Unknown                                     | 1         | 2.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo IdeaPad         | 3         | 8.33%   |
| Acer Aspire            | 3         | 8.33%   |
| Razer Blade            | 2         | 5.56%   |
| ONE-NETBOOK ONEXPLAYER | 2         | 5.56%   |
| ASUS ROG               | 2         | 5.56%   |
| Acer Nitro             | 2         | 5.56%   |
| MSI MS-7C91            | 1         | 2.78%   |
| MSI GE75               | 1         | 2.78%   |
| MSI CX62               | 1         | 2.78%   |
| Micro MG-VCP17I-3070   | 1         | 2.78%   |
| Lenovo Y50-70          | 1         | 2.78%   |
| Lenovo ThinkPad        | 1         | 2.78%   |
| Lenovo Legion          | 1         | 2.78%   |
| HP Victus              | 1         | 2.78%   |
| HP EliteBook           | 1         | 2.78%   |
| HP 250                 | 1         | 2.78%   |
| GPD P2                 | 1         | 2.78%   |
| Google Snappy          | 1         | 2.78%   |
| Gigabyte Z97X-Gaming   | 1         | 2.78%   |
| Dell Latitude          | 1         | 2.78%   |
| Dell Inspiron          | 1         | 2.78%   |
| ASUS Zephyrus          | 1         | 2.78%   |
| ASUS VivoBook          | 1         | 2.78%   |
| ASUS TUF               | 1         | 2.78%   |
| ASUS K45VM             | 1         | 2.78%   |
| Anbernic Win600        | 1         | 2.78%   |
| Alienware 17           | 1         | 2.78%   |
| Unknown                | 1         | 2.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 7         | 19.44%  |
| 2020 | 5         | 13.89%  |
| 2019 | 5         | 13.89%  |
| 2023 | 4         | 11.11%  |
| 2017 | 4         | 11.11%  |
| 2015 | 4         | 11.11%  |
| 2022 | 2         | 5.56%   |
| 2016 | 2         | 5.56%   |
| 2018 | 1         | 2.78%   |
| 2014 | 1         | 2.78%   |
| 2012 | 1         | 2.78%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 36        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 36        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 35        | 97.22%  |
| Yes  | 1         | 2.78%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 9         | 25%     |
| 32.01-64.0  | 7         | 19.44%  |
| 8.01-16.0   | 6         | 16.67%  |
| 4.01-8.0    | 5         | 13.89%  |
| 3.01-4.0    | 4         | 11.11%  |
| 24.01-32.0  | 3         | 8.33%   |
| 64.01-256.0 | 2         | 5.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 17        | 47.22%  |
| 1.01-2.0 | 8         | 22.22%  |
| 3.01-4.0 | 7         | 19.44%  |
| 4.01-8.0 | 4         | 11.11%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 19        | 52.78%  |
| 2      | 15        | 41.67%  |
| 6      | 1         | 2.78%   |
| 3      | 1         | 2.78%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 34        | 94.44%  |
| Yes       | 2         | 5.56%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 28        | 77.78%  |
| No        | 8         | 22.22%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 94.44%  |
| No        | 2         | 5.56%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 14        | 38.89%  |
| Brazil       | 4         | 11.11%  |
| Vietnam      | 2         | 5.56%   |
| UK           | 2         | 5.56%   |
| Spain        | 2         | 5.56%   |
| Saudi Arabia | 2         | 5.56%   |
| Italy        | 2         | 5.56%   |
| Switzerland  | 1         | 2.78%   |
| Romania      | 1         | 2.78%   |
| Poland       | 1         | 2.78%   |
| Netherlands  | 1         | 2.78%   |
| Hungary      | 1         | 2.78%   |
| Germany      | 1         | 2.78%   |
| Costa Rica   | 1         | 2.78%   |
| Belgium      | 1         | 2.78%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Wroclaw                  | 1         | 2.78%   |
| Vũng Tàu               | 1         | 2.78%   |
| Virginia Beach           | 1         | 2.78%   |
| Vila-seca                | 1         | 2.78%   |
| Tulcea                   | 1         | 2.78%   |
| St Louis                 | 1         | 2.78%   |
| Springfield              | 1         | 2.78%   |
| Santa Cruz das Palmeiras | 1         | 2.78%   |
| San José                | 1         | 2.78%   |
| Saltillo                 | 1         | 2.78%   |
| Ridley Park              | 1         | 2.78%   |
| Pittsburg                | 1         | 2.78%   |
| Pennsauken               | 1         | 2.78%   |
| Parma                    | 1         | 2.78%   |
| Newport News             | 1         | 2.78%   |
| Monticello               | 1         | 2.78%   |
| Milan                    | 1         | 2.78%   |
| Manaus                   | 1         | 2.78%   |
| Legazpia                 | 1         | 2.78%   |
| Jeddah                   | 1         | 2.78%   |
| Hot Springs              | 1         | 2.78%   |
| Highland Park            | 1         | 2.78%   |
| Gelsenkirchen            | 1         | 2.78%   |
| Fortaleza                | 1         | 2.78%   |
| Fairbanks                | 1         | 2.78%   |
| Dammam                   | 1         | 2.78%   |
| Chattanooga              | 1         | 2.78%   |
| Charlotte                | 1         | 2.78%   |
| Budapest                 | 1         | 2.78%   |
| Brussels                 | 1         | 2.78%   |
| Binh Duong               | 1         | 2.78%   |
| Biel/Bienne              | 1         | 2.78%   |
| Belfast                  | 1         | 2.78%   |
| Barnet                   | 1         | 2.78%   |
| Araras                   | 1         | 2.78%   |
| Almere Stad              | 1         | 2.78%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 9         | 11     | 16.07%  |
| Samsung Electronics         | 7         | 7      | 12.5%   |
| Micron Technology           | 6         | 6      | 10.71%  |
| Unknown                     | 4         | 4      | 7.14%   |
| Seagate                     | 4         | 4      | 7.14%   |
| SanDisk                     | 4         | 4      | 7.14%   |
| Kingston                    | 4         | 4      | 7.14%   |
| Intel                       | 3         | 3      | 5.36%   |
| Toshiba                     | 2         | 2      | 3.57%   |
| SK hynix                    | 2         | 2      | 3.57%   |
| Micron/Crucial Technology   | 2         | 2      | 3.57%   |
| WDC PC S                    | 1         | 1      | 1.79%   |
| Realtek Semiconductor       | 1         | 1      | 1.79%   |
| Phison Electronics          | 1         | 1      | 1.79%   |
| NT-1TB                      | 1         | 1      | 1.79%   |
| KIOXIA                      | 1         | 1      | 1.79%   |
| Kingston Technology Company | 1         | 1      | 1.79%   |
| JMicron Technology          | 1         | 1      | 1.79%   |
| Crucial                     | 1         | 1      | 1.79%   |
| Biwin Storage Technology    | 1         | 1      | 1.79%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 3         | 5.26%   |
| Unknown MMC Card  64GB                              | 2         | 3.51%   |
| SK hynix HFM512GD3JX016N 512GB                      | 2         | 3.51%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 2         | 3.51%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 2         | 3.51%   |
| Micron 1100 SATA 256GB SSD                          | 2         | 3.51%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 1.75%   |
| WDC WDBNCE0010PNC 1TB SSD                           | 1         | 1.75%   |
| WDC WD7500BPVT-80HXZT3 752GB                        | 1         | 1.75%   |
| WDC WD20SPZX-08UA7 2TB                              | 1         | 1.75%   |
| WDC WD201KFGX-68BKJN0 20TB                          | 1         | 1.75%   |
| WDC WD10SPZX-80Z10T2 1TB                            | 1         | 1.75%   |
| WDC WD10SPZX-24Z10 1TB                              | 1         | 1.75%   |
| WDC WD10SPCX-24HWST1 1TB                            | 1         | 1.75%   |
| WDC WD10JPLX-00MBPT0 1TB                            | 1         | 1.75%   |
| WDC WD10EZEX-60M2NA0 1TB                            | 1         | 1.75%   |
| WDC PC S N530 SDBPNPZ 256GB                         | 1         | 1.75%   |
| Unknown NVMe SSD Drive 1024GB                       | 1         | 1.75%   |
| Unknown MMC Card  16GB                              | 1         | 1.75%   |
| Toshiba XG6 NVMe SSD Controller 512GB               | 1         | 1.75%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 1.75%   |
| Seagate ST9320423AS 320GB                           | 1         | 1.75%   |
| Seagate ST3500418AS 500GB                           | 1         | 1.75%   |
| Seagate ST1000LM048-2E7172 1TB                      | 1         | 1.75%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1.75%   |
| Sandisk WD_BLACK SN770 2TB                          | 1         | 1.75%   |
| Sandisk WD Black SN850 1TB                          | 1         | 1.75%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB    | 1         | 1.75%   |
| SanDisk SDSSDX240GG25 240GB                         | 1         | 1.75%   |
| Samsung Portable SSD T5 1TB                         | 1         | 1.75%   |
| Samsung MZNLF128HCHP-000H1 128GB SSD                | 1         | 1.75%   |
| Realtek SSD 1TB                                     | 1         | 1.75%   |
| Phison E12 NVMe Controller 2TB                      | 1         | 1.75%   |
| NT-1TB 2242 1024GB                                  | 1         | 1.75%   |
| Micron MTFDHBA512QFD 512GB                          | 1         | 1.75%   |
| Micron 2200V_MTFDHBA512TCK 512GB                    | 1         | 1.75%   |
| Micron 1100_MTFDDAV512TBN 512GB SSD                 | 1         | 1.75%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD                 | 1         | 1.75%   |
| KIOXIA KBG40ZNT512G TOSHIBA MEMORY 512GB            | 1         | 1.75%   |
| Kingston Company A2000 NVMe SSD 1TB                 | 1         | 1.75%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 8         | 8      | 61.54%  |
| Seagate | 4         | 4      | 30.77%  |
| Toshiba | 1         | 1      | 7.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Micron Technology   | 4         | 4      | 26.67%  |
| Kingston            | 4         | 4      | 26.67%  |
| WDC                 | 2         | 3      | 13.33%  |
| Samsung Electronics | 2         | 2      | 13.33%  |
| SanDisk             | 1         | 1      | 6.67%   |
| NT-1TB              | 1         | 1      | 6.67%   |
| Crucial             | 1         | 1      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 22        | 24     | 44%     |
| SSD     | 12        | 16     | 24%     |
| HDD     | 11        | 13     | 22%     |
| MMC     | 3         | 3      | 6%      |
| Unknown | 2         | 2      | 4%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 22        | 24     | 46.81%  |
| SATA | 19        | 28     | 40.43%  |
| SAS  | 3         | 3      | 6.38%   |
| MMC  | 3         | 3      | 6.38%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 11        | 11     | 47.83%  |
| 0.01-0.5   | 9         | 15     | 39.13%  |
| 1.01-2.0   | 2         | 2      | 8.7%    |
| 10.01-20.0 | 1         | 1      | 4.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 1001-2000      | 13        | 36.11%  |
| More than 3000 | 12        | 33.33%  |
| 251-500        | 5         | 13.89%  |
| 501-1000       | 4         | 11.11%  |
| 101-250        | 2         | 5.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 21-50          | 14        | 38.89%  |
| 101-250        | 6         | 16.67%  |
| 51-100         | 6         | 16.67%  |
| 251-500        | 4         | 11.11%  |
| 501-1000       | 4         | 11.11%  |
| More than 3000 | 1         | 2.78%   |
| 1-20           | 1         | 2.78%   |

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
| Detected | 36        | 58     | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 22        | 44.9%   |
| AMD                          | 6         | 12.24%  |
| Samsung Electronics          | 5         | 10.2%   |
| SanDisk                      | 3         | 6.12%   |
| SK hynix                     | 2         | 4.08%   |
| Micron/Crucial Technology    | 2         | 4.08%   |
| Micron Technology            | 2         | 4.08%   |
| Toshiba America Info Systems | 1         | 2.04%   |
| Realtek Semiconductor        | 1         | 2.04%   |
| Phison Electronics           | 1         | 2.04%   |
| KIOXIA                       | 1         | 2.04%   |
| Kingston Technology Company  | 1         | 2.04%   |
| INNOGRIT                     | 1         | 2.04%   |
| Biwin Storage Technology     | 1         | 2.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 4         | 7.69%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 5.77%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 5.77%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 5.77%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 5.77%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 2         | 3.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 3.85%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2         | 3.85%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 2         | 3.85%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 3.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 3.85%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 3.85%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 1.92%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 1.92%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1         | 1.92%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 1.92%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                              | 1         | 1.92%   |
| Phison E12 NVMe Controller                                                     | 1         | 1.92%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 1         | 1.92%   |
| Micron 2200S NVMe SSD [Cassandra]                                              | 1         | 1.92%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 1         | 1.92%   |
| Kingston Company A2000 NVMe SSD                                                | 1         | 1.92%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 1.92%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 1         | 1.92%   |
| Intel SSD 660P Series                                                          | 1         | 1.92%   |
| Intel SSD 600P Series                                                          | 1         | 1.92%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 1.92%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.92%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 1         | 1.92%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 1.92%   |
| INNOGRIT NVMe SSD Controller IG5236                                            | 1         | 1.92%   |
| Biwin Storage Non-Volatile memory controller                                   | 1         | 1.92%   |
| AMD RS690 PCI to PCI Bridge (PCI Express Port 2)                               | 1         | 1.92%   |
| AMD 500 Series Chipset SATA Controller                                         | 1         | 1.92%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 22        | 44%     |
| SATA | 21        | 42%     |
| RAID | 7         | 14%     |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 25        | 69.44%  |
| AMD    | 11        | 30.56%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 5.56%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 2         | 5.56%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 2         | 5.56%   |
| AMD Ryzen 7 6800U with Radeon Graphics        | 2         | 5.56%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 5.56%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 1         | 2.78%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 2.78%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 1         | 2.78%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 2.78%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 2.78%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 2.78%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 2.78%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 2.78%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 2.78%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 2.78%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 2.78%   |
| Intel Core i5-4210H CPU @ 2.90GHz             | 1         | 2.78%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 1         | 2.78%   |
| Intel Atom x7-Z8700 CPU @ 1.60GHz             | 1         | 2.78%   |
| Intel 12th Gen Core i7-12700H                 | 1         | 2.78%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 1         | 2.78%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 1         | 2.78%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz       | 1         | 2.78%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 2.78%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 1         | 2.78%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 1         | 2.78%   |
| AMD Ryzen 9 5900HS with Radeon Graphics       | 1         | 2.78%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 1         | 2.78%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 1         | 2.78%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 1         | 2.78%   |
| AMD Athlon Silver 3050e with Radeon Graphics  | 1         | 2.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Intel Core i7 | 9         | 25%     |
| Intel Core i5 | 8         | 22.22%  |
| Other         | 5         | 13.89%  |
| AMD Ryzen 9   | 4         | 11.11%  |
| AMD Ryzen 7   | 3         | 8.33%   |
| AMD Ryzen 5   | 3         | 8.33%   |
| Intel Core m3 | 1         | 2.78%   |
| Intel Celeron | 1         | 2.78%   |
| Intel Atom    | 1         | 2.78%   |
| AMD Athlon    | 1         | 2.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 15        | 41.67%  |
| 2      | 7         | 19.44%  |
| 8      | 6         | 16.67%  |
| 6      | 5         | 13.89%  |
| 12     | 2         | 5.56%   |
| 14     | 1         | 2.78%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 36        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 29        | 80.56%  |
| 1      | 7         | 19.44%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 36        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 36        | 100%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KabyLake   | 9         | 25%     |
| Unknown    | 6         | 16.67%  |
| Zen+       | 3         | 8.33%   |
| Zen 3      | 3         | 8.33%   |
| Skylake    | 3         | 8.33%   |
| Haswell    | 3         | 8.33%   |
| TigerLake  | 2         | 5.56%   |
| CometLake  | 2         | 5.56%   |
| Zen 2      | 1         | 2.78%   |
| Zen        | 1         | 2.78%   |
| Silvermont | 1         | 2.78%   |
| IvyBridge  | 1         | 2.78%   |
| Goldmont   | 1         | 2.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Nvidia | 22        | 39.29%  |
| Intel  | 22        | 39.29%  |
| AMD    | 12        | 21.43%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 7.14%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 3.57%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 2         | 3.57%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 3.57%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 2         | 3.57%   |
| Intel UHD Graphics 620                                                                   | 2         | 3.57%   |
| Intel HD Graphics 630                                                                    | 2         | 3.57%   |
| Intel HD Graphics 530                                                                    | 2         | 3.57%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 3.57%   |
| AMD Rembrandt [Radeon 680M]                                                              | 2         | 3.57%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 3.57%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 1.79%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 1.79%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 1.79%   |
| Nvidia TU106BM [GeForce RTX 2060 Mobile]                                                 | 1         | 1.79%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                                    | 1         | 1.79%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 1.79%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.79%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1         | 1.79%   |
| Nvidia GM204M [GeForce GTX 960 OEM / 970M]                                               | 1         | 1.79%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 1.79%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.79%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 1.79%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 1.79%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 1.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 1.79%   |
| Intel UHD Graphics 615                                                                   | 1         | 1.79%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 1.79%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 1.79%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 1         | 1.79%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 1.79%   |
| Intel HD Graphics 620                                                                    | 1         | 1.79%   |
| Intel HD Graphics 500                                                                    | 1         | 1.79%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.79%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.79%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.79%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 1         | 1.79%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 1.79%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX]                                                 | 1         | 1.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 13        | 36.11%  |
| 1 x Intel      | 6         | 16.67%  |
| AMD + Nvidia   | 5         | 13.89%  |
| 1 x AMD        | 5         | 13.89%  |
| 1 x Nvidia     | 4         | 11.11%  |
| Intel + AMD    | 2         | 5.56%   |
| Other          | 1         | 2.78%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Proprietary | 21        | 58.33%  |
| Free        | 15        | 41.67%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 36        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Chimei Innolux      | 7         | 18.42%  |
| BOE                 | 7         | 18.42%  |
| LG Display          | 6         | 15.79%  |
| AU Optronics        | 5         | 13.16%  |
| Samsung Electronics | 2         | 5.26%   |
| Unknown (XXX)       | 1         | 2.63%   |
| TMX                 | 1         | 2.63%   |
| Sharp               | 1         | 2.63%   |
| RTK                 | 1         | 2.63%   |
| Philips             | 1         | 2.63%   |
| PANDA               | 1         | 2.63%   |
| Insignia            | 1         | 2.63%   |
| HJW                 | 1         | 2.63%   |
| Goldstar            | 1         | 2.63%   |
| GameMax             | 1         | 2.63%   |
| Fujitsu Siemens     | 1         | 2.63%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| BOE FLQ8423-24L0 BOE1003 1600x2560 113x181mm 8.4-inch                | 2         | 5.26%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch        | 1         | 2.63%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch              | 1         | 2.63%   |
| Sharp LQ173M1JW02 SHP14DB 1920x1080 382x215mm 17.3-inch              | 1         | 2.63%   |
| Samsung Electronics QBQ95 SAM7229 3840x2160 1872x1053mm 84.6-inch    | 1         | 2.63%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch | 1         | 2.63%   |
| RTK FHD HDR RTK2A3B 1920x1080 344x195mm 15.6-inch                    | 1         | 2.63%   |
| Philips LCD Monitor PHL4650 1280x768 530x398mm 26.1-inch             | 1         | 2.63%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 1         | 2.63%   |
| LG Display LCD Monitor LGD071E 1920x1080 344x194mm 15.5-inch         | 1         | 2.63%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch         | 1         | 2.63%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch         | 1         | 2.63%   |
| LG Display LCD Monitor LGD0459 1920x1080 382x215mm 17.3-inch         | 1         | 2.63%   |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch         | 1         | 2.63%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch          | 1         | 2.63%   |
| Insignia NS-22E400NA14 BBY0042 1920x1080 544x306mm 24.6-inch         | 1         | 2.63%   |
| HJW MACROSILICON HJW9291 1680x1050 530x290mm 23.8-inch               | 1         | 2.63%   |
| Goldstar M237WDP GSM5779 1920x1080 598x336mm 27.0-inch               | 1         | 2.63%   |
| GameMax GMX32CEWQ GMX0315 2560x1440 697x392mm 31.5-inch              | 1         | 2.63%   |
| Fujitsu Siemens B22T-7 LED PG FUS082A 1920x1080 477x268mm 21.5-inch  | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN176E 1920x1080 381x214mm 17.2-inch     | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch     | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN1540 2560x1440 344x193mm 15.5-inch     | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 1         | 2.63%   |
| BOE LCD Monitor BOE0AAD 1920x1080 355x200mm 16.0-inch                | 1         | 2.63%   |
| BOE LCD Monitor BOE0977 2560x1440 381x214mm 17.2-inch                | 1         | 2.63%   |
| BOE LCD Monitor BOE0816 1366x768 344x193mm 15.5-inch                 | 1         | 2.63%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                | 1         | 2.63%   |
| BOE LCD Monitor BOE065D 1920x1080 344x194mm 15.5-inch                | 1         | 2.63%   |
| AU Optronics LCD Monitor AUOD0ED 1920x1080 344x193mm 15.5-inch       | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO82ED 1920x1080 344x193mm 15.5-inch       | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO135C 1366x768 256x144mm 11.6-inch        | 1         | 2.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 21        | 58.33%  |
| 1366x768 (WXGA) | 5         | 13.89%  |
| 2560x1440 (QHD) | 4         | 11.11%  |
| 3840x2160 (4K)  | 2         | 5.56%   |
| 1600x2560       | 2         | 5.56%   |
| 1280x960        | 1         | 2.78%   |
| 1280x768        | 1         | 2.78%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 19        | 50%     |
| 17     | 4         | 10.53%  |
| 14     | 2         | 5.26%   |
| 8      | 2         | 5.26%   |
| 84     | 1         | 2.63%   |
| 57     | 1         | 2.63%   |
| 54     | 1         | 2.63%   |
| 49     | 1         | 2.63%   |
| 34     | 1         | 2.63%   |
| 31     | 1         | 2.63%   |
| 27     | 1         | 2.63%   |
| 23     | 1         | 2.63%   |
| 21     | 1         | 2.63%   |
| 16     | 1         | 2.63%   |
| 11     | 1         | 2.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 21        | 55.26%  |
| 351-400     | 5         | 13.16%  |
| 701-800     | 2         | 5.26%   |
| 501-600     | 2         | 5.26%   |
| 101-200     | 2         | 5.26%   |
| 1001-1500   | 2         | 5.26%   |
| 601-700     | 1         | 2.63%   |
| 401-500     | 1         | 2.63%   |
| 201-300     | 1         | 2.63%   |
| 1501-2000   | 1         | 2.63%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 32        | 91.43%  |
| 0.62  | 2         | 5.71%   |
| 0.56  | 1         | 2.86%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 20        | 54.05%  |
| 121-130        | 4         | 10.81%  |
| More than 1000 | 3         | 8.11%   |
| 81-90          | 2         | 5.41%   |
| 1-40           | 2         | 5.41%   |
| 201-250        | 2         | 5.41%   |
| 51-60          | 1         | 2.7%    |
| 351-500        | 1         | 2.7%    |
| 301-350        | 1         | 2.7%    |
| 501-1000       | 1         | 2.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 20        | 55.56%  |
| 101-120       | 5         | 13.89%  |
| 1-50          | 3         | 8.33%   |
| 161-240       | 3         | 8.33%   |
| 51-100        | 3         | 8.33%   |
| More than 240 | 2         | 5.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 28        | 77.78%  |
| 2     | 6         | 16.67%  |
| 0     | 2         | 5.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 25        | 40.32%  |
| Intel                 | 20        | 32.26%  |
| Qualcomm Atheros      | 10        | 16.13%  |
| MediaTek              | 4         | 6.45%   |
| Broadcom Limited      | 1         | 1.61%   |
| Broadcom              | 1         | 1.61%   |
| ASIX Electronics      | 1         | 1.61%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17        | 25.76%  |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 6.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 6.06%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 6.06%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 4.55%   |
| Intel Wireless 3165                                               | 3         | 4.55%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2         | 3.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 3.03%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 3.03%   |
| Intel Wireless 7265                                               | 2         | 3.03%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 3.03%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 3.03%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 3.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 3.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 1.52%   |
| Realtek PCIe GbE Family Controller                                | 1         | 1.52%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.52%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 1.52%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1         | 1.52%   |
| Intel Wireless 8265 / 8275                                        | 1         | 1.52%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.52%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 1.52%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.52%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter        | 1         | 1.52%   |
| Broadcom BCM4356 802.11ac Wireless Network Adapter                | 1         | 1.52%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 20        | 54.05%  |
| Qualcomm Atheros      | 7         | 18.92%  |
| Realtek Semiconductor | 4         | 10.81%  |
| MediaTek              | 4         | 10.81%  |
| Broadcom Limited      | 1         | 2.7%    |
| Broadcom              | 1         | 2.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 4         | 10.81%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 4         | 10.81%  |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 3         | 8.11%   |
| Intel Wireless 3165                                           | 3         | 8.11%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 2         | 5.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 2         | 5.41%   |
| Intel Wireless 7265                                           | 2         | 5.41%   |
| Intel Wi-Fi 6 AX201                                           | 2         | 5.41%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 2         | 5.41%   |
| Intel Comet Lake PCH CNVi WiFi                                | 2         | 5.41%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 2         | 5.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 1         | 2.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 1         | 2.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 1         | 2.7%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 1         | 2.7%    |
| Intel Wireless 8265 / 8275                                    | 1         | 2.7%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 1         | 2.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 1         | 2.7%    |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter    | 1         | 2.7%    |
| Broadcom BCM4356 802.11ac Wireless Network Adapter            | 1         | 2.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 23        | 79.31%  |
| Qualcomm Atheros      | 4         | 13.79%  |
| Intel                 | 1         | 3.45%   |
| ASIX Electronics      | 1         | 3.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17        | 58.62%  |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 13.79%  |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 6.9%    |
| Realtek PCIe GbE Family Controller                                | 1         | 3.45%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 3.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 3.45%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 3.45%   |
| Intel I211 Gigabit Network Connection                             | 1         | 3.45%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 3.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 36        | 56.25%  |
| Ethernet | 28        | 43.75%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 30        | 78.95%  |
| Ethernet | 8         | 21.05%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 25        | 69.44%  |
| 1     | 10        | 27.78%  |
| 3     | 1         | 2.78%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 25        | 69.44%  |
| Yes  | 11        | 30.56%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 20        | 58.82%  |
| Qualcomm Atheros Communications | 4         | 11.76%  |
| Lite-On Technology              | 3         | 8.82%   |
| IMC Networks                    | 3         | 8.82%   |
| Realtek Semiconductor           | 1         | 2.94%   |
| MediaTek                        | 1         | 2.94%   |
| Foxconn / Hon Hai               | 1         | 2.94%   |
| Cambridge Silicon Radio         | 1         | 2.94%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 7         | 20.59%  |
| Intel AX201 Bluetooth                               | 6         | 17.65%  |
| Intel AX210 Bluetooth                               | 4         | 11.76%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 8.82%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 5.88%   |
| IMC Networks Wireless_Device                        | 2         | 5.88%   |
| Realtek Bluetooth Radio                             | 1         | 2.94%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 2.94%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 2.94%   |
| MediaTek Wireless_Device                            | 1         | 2.94%   |
| Lite-On Wireless_Device                             | 1         | 2.94%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 2.94%   |
| Lite-On Bluetooth Device                            | 1         | 2.94%   |
| IMC Networks Bluetooth Radio                        | 1         | 2.94%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 1         | 2.94%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.94%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 24        | 42.86%  |
| Nvidia                 | 14        | 25%     |
| AMD                    | 12        | 21.43%  |
| Sony                   | 3         | 5.36%   |
| Realtek Semiconductor  | 1         | 1.79%   |
| Kingston Technology    | 1         | 1.79%   |
| Generalplus Technology | 1         | 1.79%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                              | 9         | 13.43%  |
| Intel Sunrise Point-LP HD Audio                                     | 5         | 7.46%   |
| Nvidia TU106 High Definition Audio Controller                       | 3         | 4.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 3         | 4.48%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 3         | 4.48%   |
| Sony DualSense wireless controller (PS5)                            | 2         | 2.99%   |
| Nvidia GP107GL High Definition Audio Controller                     | 2         | 2.99%   |
| Nvidia GA106 High Definition Audio Controller                       | 2         | 2.99%   |
| Nvidia GA104 High Definition Audio Controller                       | 2         | 2.99%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 2         | 2.99%   |
| Intel Tiger Lake-H HD Audio Controller                              | 2         | 2.99%   |
| Intel Comet Lake PCH cAVS                                           | 2         | 2.99%   |
| Intel CM238 HD Audio Controller                                     | 2         | 2.99%   |
| Intel Cannon Lake PCH cAVS                                          | 2         | 2.99%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 2         | 2.99%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 2         | 2.99%   |
| AMD Starship/Matisse HD Audio Controller                            | 2         | 2.99%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 2         | 2.99%   |
| AMD Rembrandt Radeon High Definition Audio Controller               | 2         | 2.99%   |
| Sony DualShock 4 [CUH-ZCT2x]                                        | 1         | 1.49%   |
| Realtek Semiconductor USB Audio                                     | 1         | 1.49%   |
| Nvidia TU116 High Definition Audio Controller                       | 1         | 1.49%   |
| Nvidia TU104 HD Audio Controller                                    | 1         | 1.49%   |
| Nvidia GP102 HDMI Audio Controller                                  | 1         | 1.49%   |
| Nvidia GF108 High Definition Audio Controller                       | 1         | 1.49%   |
| Nvidia Audio device                                                 | 1         | 1.49%   |
| Kingston Technology HyperX QuadCast                                 | 1         | 1.49%   |
| Intel Comet Lake PCH-LP cAVS                                        | 1         | 1.49%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster   | 1         | 1.49%   |
| Intel Alder Lake PCH-P High Definition Audio Controller             | 1         | 1.49%   |
| Intel 9 Series Chipset Family HD Audio Controller                   | 1         | 1.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 1         | 1.49%   |
| Generalplus Technology USB Audio Device                             | 1         | 1.49%   |
| AMD Navi 31 HDMI/DP Audio                                           | 1         | 1.49%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]          | 1         | 1.49%   |

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
| Chicony Electronics           | 9         | 37.5%   |
| IMC Networks                  | 4         | 16.67%  |
| Microdia                      | 3         | 12.5%   |
| Sunplus Innovation Technology | 2         | 8.33%   |
| Quanta                        | 2         | 8.33%   |
| Acer                          | 2         | 8.33%   |
| Silicon Motion                | 1         | 4.17%   |
| Realtek Semiconductor         | 1         | 4.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                             | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| IMC Networks Integrated Camera    | 3         | 12.5%   |
| Chicony Integrated Camera         | 2         | 8.33%   |
| Chicony HD User Facing            | 2         | 8.33%   |
| Acer Lenovo EasyCamera            | 2         | 8.33%   |
| Sunplus Integrated_Webcam_HD      | 1         | 4.17%   |
| Sunplus HD WebCam                 | 1         | 4.17%   |
| Silicon Motion 300k Pixel Camera  | 1         | 4.17%   |
| Realtek Integrated Webcam         | 1         | 4.17%   |
| Quanta HP HD Camera               | 1         | 4.17%   |
| Quanta HD User Facing             | 1         | 4.17%   |
| Microdia USB 2.0 Camera           | 1         | 4.17%   |
| Microdia Integrated_Webcam_FHD    | 1         | 4.17%   |
| Microdia HP Webcam                | 1         | 4.17%   |
| IMC Networks USB2.0 HD UVC WebCam | 1         | 4.17%   |
| Chicony USB2.0 0.3M UVC WebCam    | 1         | 4.17%   |
| Chicony Integrated IR Camera      | 1         | 4.17%   |
| Chicony HP Wide Vision HD Camera  | 1         | 4.17%   |
| Chicony HP Truevision HD          | 1         | 4.17%   |
| Chicony EasyCamera                | 1         | 4.17%   |

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
| 0     | 30        | 83.33%  |
| 1     | 6         | 16.67%  |

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

