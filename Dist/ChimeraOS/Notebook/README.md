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

Total: 47

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | G15 5510                    | [12bd3f99da](https://linux-hardware.org/?probe=12bd3f99da) | Oct 31, 2023 |
| Dell          | Precision 7520              | [ab5ec5ba37](https://linux-hardware.org/?probe=ab5ec5ba37) | Oct 22, 2023 |
| Acer          | Aspire VX5-591G             | [586d280ca5](https://linux-hardware.org/?probe=586d280ca5) | Oct 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [11820fb443](https://linux-hardware.org/?probe=11820fb443) | Oct 10, 2023 |
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
| ChimeraOS 43-1 | 12        | 30%     |
| ChimeraOS 39   | 8         | 20%     |
| ChimeraOS 42   | 7         | 17.5%   |
| ChimeraOS 41   | 5         | 12.5%   |
| ChimeraOS 44-1 | 2         | 5%      |
| ChimeraOS 44   | 2         | 5%      |
| ChimeraOS 38   | 2         | 5%      |
| ChimeraOS 43   | 1         | 2.5%    |
| ChimeraOS      | 1         | 2.5%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| ChimeraOS | 40        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 6.3.9-chimeraos-1       | 13        | 32.5%   |
| 6.1.11-arch1-1          | 8         | 20%     |
| 6.1.27-1-lts            | 7         | 17.5%   |
| 6.1.21-1-lts            | 5         | 12.5%   |
| 6.5.6-chos1-chimeraos-1 | 2         | 5%      |
| 6.5.3-chos1-chimeraos-1 | 2         | 5%      |
| 6.1.1-arch1-1           | 2         | 5%      |
| 6.4.9-0-generic         | 1         | 2.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.3.9   | 13        | 32.5%   |
| 6.1.11  | 8         | 20%     |
| 6.1.27  | 7         | 17.5%   |
| 6.1.21  | 5         | 12.5%   |
| 6.5.6   | 2         | 5%      |
| 6.5.3   | 2         | 5%      |
| 6.1.1   | 2         | 5%      |
| 6.4.9   | 1         | 2.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 22        | 55%     |
| 6.3     | 13        | 32.5%   |
| 6.5     | 4         | 10%     |
| 6.4     | 1         | 2.5%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 40        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| GNOME | 40        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 38        | 95%     |
| X11     | 2         | 5%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 40        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 31        | 77.5%   |
| pt_BR | 3         | 7.5%    |
| it_IT | 2         | 5%      |
| es_ES | 2         | 5%      |
| fr_FR | 1         | 2.5%    |
| C     | 1         | 2.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 40        | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 39        | 97.5%   |
| Ext4  | 1         | 2.5%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 40        | 100%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 40        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 40        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 7         | 17.5%   |
| Lenovo              | 6         | 15%     |
| Acer                | 6         | 15%     |
| Dell                | 4         | 10%     |
| MSI                 | 3         | 7.5%    |
| Hewlett-Packard     | 3         | 7.5%    |
| Razer               | 2         | 5%      |
| ONE-NETBOOK         | 2         | 5%      |
| Micro Electronics   | 1         | 2.5%    |
| GPD                 | 1         | 2.5%    |
| Google              | 1         | 2.5%    |
| Gigabyte Technology | 1         | 2.5%    |
| Anbernic            | 1         | 2.5%    |
| AMI                 | 1         | 2.5%    |
| Alienware           | 1         | 2.5%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| ONE-NETBOOK ONEXPLAYER 2 ARP23              | 2         | 5%      |
| Razer Blade Pro 17 (Early 2020) - RZ09-0329 | 1         | 2.5%    |
| Razer Blade 14 - RZ09-0370                  | 1         | 2.5%    |
| MSI MS-7C91                                 | 1         | 2.5%    |
| MSI GE75 Raider 10SF                        | 1         | 2.5%    |
| MSI CX62 6QD                                | 1         | 2.5%    |
| Micro MG-VCP17I-3070                        | 1         | 2.5%    |
| Lenovo Y50-70 20378                         | 1         | 2.5%    |
| Lenovo ThinkPad E15 20RD0011IX              | 1         | 2.5%    |
| Lenovo Legion Y540-15IRH 81SX               | 1         | 2.5%    |
| Lenovo IdeaPad 700-15ISK 80RU               | 1         | 2.5%    |
| Lenovo IdeaPad 320-15IKB 80YH               | 1         | 2.5%    |
| Lenovo IdeaPad 3 15ADA05 81W1               | 1         | 2.5%    |
| HP Victus by Laptop 16-d1xxx                | 1         | 2.5%    |
| HP EliteBook 850 G8 Notebook PC             | 1         | 2.5%    |
| HP 250 G4 Notebook PC                       | 1         | 2.5%    |
| GPD P2 MAX                                  | 1         | 2.5%    |
| Google Snappy                               | 1         | 2.5%    |
| Gigabyte Z97X-Gaming 5                      | 1         | 2.5%    |
| Dell Precision 7520                         | 1         | 2.5%    |
| Dell Latitude 3590                          | 1         | 2.5%    |
| Dell Inspiron 15 7000 Gaming                | 1         | 2.5%    |
| Dell G15 5510                               | 1         | 2.5%    |
| ASUS Zephyrus S GX502GV_GX502GV             | 1         | 2.5%    |
| ASUS VivoBook_ASUSLaptop X570DD_X570DD      | 1         | 2.5%    |
| ASUS TUF Gaming FX505DV_FX505DV             | 1         | 2.5%    |
| ASUS ROG Zephyrus G15 GA503QM_GA503QM       | 1         | 2.5%    |
| ASUS ROG CROSSHAIR VIII HERO                | 1         | 2.5%    |
| ASUS K45VM                                  | 1         | 2.5%    |
| ASUS ASUS TUF Gaming F15 FX506HCB_FX506HCB  | 1         | 2.5%    |
| Anbernic Win600                             | 1         | 2.5%    |
| Alienware 17 R2                             | 1         | 2.5%    |
| Acer Nitro AN515-57                         | 1         | 2.5%    |
| Acer Nitro AN515-51                         | 1         | 2.5%    |
| Acer Aspire VX5-591G                        | 1         | 2.5%    |
| Acer Aspire A715-42G                        | 1         | 2.5%    |
| Acer Aspire A515-51G                        | 1         | 2.5%    |
| Acer Aspire A315-58G                        | 1         | 2.5%    |
| Unknown                                     | 1         | 2.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Acer Aspire            | 4         | 10%     |
| Lenovo IdeaPad         | 3         | 7.5%    |
| Razer Blade            | 2         | 5%      |
| ONE-NETBOOK ONEXPLAYER | 2         | 5%      |
| ASUS ROG               | 2         | 5%      |
| Acer Nitro             | 2         | 5%      |
| MSI MS-7C91            | 1         | 2.5%    |
| MSI GE75               | 1         | 2.5%    |
| MSI CX62               | 1         | 2.5%    |
| Micro MG-VCP17I-3070   | 1         | 2.5%    |
| Lenovo Y50-70          | 1         | 2.5%    |
| Lenovo ThinkPad        | 1         | 2.5%    |
| Lenovo Legion          | 1         | 2.5%    |
| HP Victus              | 1         | 2.5%    |
| HP EliteBook           | 1         | 2.5%    |
| HP 250                 | 1         | 2.5%    |
| GPD P2                 | 1         | 2.5%    |
| Google Snappy          | 1         | 2.5%    |
| Gigabyte Z97X-Gaming   | 1         | 2.5%    |
| Dell Precision         | 1         | 2.5%    |
| Dell Latitude          | 1         | 2.5%    |
| Dell Inspiron          | 1         | 2.5%    |
| Dell G15               | 1         | 2.5%    |
| ASUS Zephyrus          | 1         | 2.5%    |
| ASUS VivoBook          | 1         | 2.5%    |
| ASUS TUF               | 1         | 2.5%    |
| ASUS K45VM             | 1         | 2.5%    |
| ASUS ASUS              | 1         | 2.5%    |
| Anbernic Win600        | 1         | 2.5%    |
| Alienware 17           | 1         | 2.5%    |
| Unknown                | 1         | 2.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 9         | 22.5%   |
| 2017 | 6         | 15%     |
| 2020 | 5         | 12.5%   |
| 2019 | 5         | 12.5%   |
| 2023 | 4         | 10%     |
| 2015 | 4         | 10%     |
| 2022 | 2         | 5%      |
| 2016 | 2         | 5%      |
| 2018 | 1         | 2.5%    |
| 2014 | 1         | 2.5%    |
| 2012 | 1         | 2.5%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 40        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 40        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 39        | 97.5%   |
| Yes  | 1         | 2.5%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 10        | 25%     |
| 32.01-64.0  | 9         | 22.5%   |
| 4.01-8.0    | 6         | 15%     |
| 8.01-16.0   | 6         | 15%     |
| 3.01-4.0    | 4         | 10%     |
| 24.01-32.0  | 3         | 7.5%    |
| 64.01-256.0 | 2         | 5%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 18        | 45%     |
| 3.01-4.0 | 8         | 20%     |
| 1.01-2.0 | 8         | 20%     |
| 4.01-8.0 | 6         | 15%     |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 20        | 50%     |
| 2      | 18        | 45%     |
| 6      | 1         | 2.5%    |
| 3      | 1         | 2.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 39        | 97.5%   |
| Yes       | 1         | 2.5%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 80%     |
| No        | 8         | 20%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 37        | 92.5%   |
| No        | 3         | 7.5%    |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 16        | 40%     |
| Brazil       | 5         | 12.5%   |
| Vietnam      | 2         | 5%      |
| UK           | 2         | 5%      |
| Spain        | 2         | 5%      |
| Saudi Arabia | 2         | 5%      |
| Italy        | 2         | 5%      |
| Switzerland  | 1         | 2.5%    |
| Romania      | 1         | 2.5%    |
| Poland       | 1         | 2.5%    |
| Netherlands  | 1         | 2.5%    |
| Hungary      | 1         | 2.5%    |
| Germany      | 1         | 2.5%    |
| France       | 1         | 2.5%    |
| Costa Rica   | 1         | 2.5%    |
| Belgium      | 1         | 2.5%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Wroclaw                  | 1         | 2.5%    |
| Vũng Tàu               | 1         | 2.5%    |
| Virginia Beach           | 1         | 2.5%    |
| Vila-seca                | 1         | 2.5%    |
| Tulcea                   | 1         | 2.5%    |
| St Louis                 | 1         | 2.5%    |
| Springfield              | 1         | 2.5%    |
| Santa Cruz das Palmeiras | 1         | 2.5%    |
| San José                | 1         | 2.5%    |
| Saltillo                 | 1         | 2.5%    |
| Ridley Park              | 1         | 2.5%    |
| Pittsburg                | 1         | 2.5%    |
| Pennsauken               | 1         | 2.5%    |
| Parma                    | 1         | 2.5%    |
| Newport News             | 1         | 2.5%    |
| Monticello               | 1         | 2.5%    |
| Milan                    | 1         | 2.5%    |
| Miami                    | 1         | 2.5%    |
| Manaus                   | 1         | 2.5%    |
| Legazpia                 | 1         | 2.5%    |
| Las Vegas                | 1         | 2.5%    |
| Jeddah                   | 1         | 2.5%    |
| Hot Springs              | 1         | 2.5%    |
| Highland Park            | 1         | 2.5%    |
| Gelsenkirchen            | 1         | 2.5%    |
| Foz do Iguaçu           | 1         | 2.5%    |
| Fortaleza                | 1         | 2.5%    |
| Fairbanks                | 1         | 2.5%    |
| Dammam                   | 1         | 2.5%    |
| Clichy-sous-Bois         | 1         | 2.5%    |
| Chattanooga              | 1         | 2.5%    |
| Charlotte                | 1         | 2.5%    |
| Budapest                 | 1         | 2.5%    |
| Brussels                 | 1         | 2.5%    |
| Binh Duong               | 1         | 2.5%    |
| Biel/Bienne              | 1         | 2.5%    |
| Belfast                  | 1         | 2.5%    |
| Barnet                   | 1         | 2.5%    |
| Araras                   | 1         | 2.5%    |
| Almere Stad              | 1         | 2.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 10        | 13     | 16.39%  |
| Samsung Electronics         | 7         | 7      | 11.48%  |
| Micron Technology           | 6         | 6      | 9.84%   |
| Kingston                    | 5         | 5      | 8.2%    |
| Unknown                     | 4         | 4      | 6.56%   |
| Seagate                     | 4         | 4      | 6.56%   |
| SanDisk                     | 4         | 4      | 6.56%   |
| Micron/Crucial Technology   | 3         | 4      | 4.92%   |
| Intel                       | 3         | 3      | 4.92%   |
| Toshiba                     | 2         | 2      | 3.28%   |
| SK hynix                    | 2         | 2      | 3.28%   |
| KIOXIA                      | 2         | 2      | 3.28%   |
| WDC PC S                    | 1         | 1      | 1.64%   |
| SSSTC                       | 1         | 1      | 1.64%   |
| Realtek Semiconductor       | 1         | 1      | 1.64%   |
| Phison Electronics          | 1         | 1      | 1.64%   |
| NT-1TB                      | 1         | 1      | 1.64%   |
| Kingston Technology Company | 1         | 1      | 1.64%   |
| JMicron Technology          | 1         | 1      | 1.64%   |
| Crucial                     | 1         | 1      | 1.64%   |
| Biwin Storage Technology    | 1         | 1      | 1.64%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 3         | 4.76%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB              | 3         | 4.76%   |
| Unknown MMC Card  64GB                             | 2         | 3.17%   |
| SK hynix HFM512GD3JX016N 512GB                     | 2         | 3.17%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 2         | 3.17%   |
| Micron 1100 SATA 256GB SSD                         | 2         | 3.17%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                   | 1         | 1.59%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 1         | 1.59%   |
| WDC WDBNCE0010PNC 1TB SSD                          | 1         | 1.59%   |
| WDC WD7500BPVT-80HXZT3 752GB                       | 1         | 1.59%   |
| WDC WD20SPZX-08UA7 2TB                             | 1         | 1.59%   |
| WDC WD201KFGX-68BKJN0 20TB                         | 1         | 1.59%   |
| WDC WD10SPZX-80Z10T2 1TB                           | 1         | 1.59%   |
| WDC WD10SPZX-24Z10 1TB                             | 1         | 1.59%   |
| WDC WD10SPCX-24HWST1 1TB                           | 1         | 1.59%   |
| WDC WD10JPVX-22JC3T0 1TB                           | 1         | 1.59%   |
| WDC WD10JPLX-00MBPT0 1TB                           | 1         | 1.59%   |
| WDC WD10EZEX-60M2NA0 1TB                           | 1         | 1.59%   |
| WDC PC S N530 SDBPNPZ 256GB                        | 1         | 1.59%   |
| Unknown NVMe SSD Drive 1024GB                      | 1         | 1.59%   |
| Unknown MMC Card  16GB                             | 1         | 1.59%   |
| Toshiba XG6 NVMe SSD Controller 256GB              | 1         | 1.59%   |
| Toshiba MQ01ABF050 500GB                           | 1         | 1.59%   |
| SSSTC CVB-8D128-HP 128GB                           | 1         | 1.59%   |
| Seagate ST9320423AS 320GB                          | 1         | 1.59%   |
| Seagate ST3500418AS 500GB                          | 1         | 1.59%   |
| Seagate ST1000LM048-2E7172 1TB                     | 1         | 1.59%   |
| Seagate ST1000LM035-1RK172 1TB                     | 1         | 1.59%   |
| Sandisk WD_BLACK SN770 2TB                         | 1         | 1.59%   |
| Sandisk WD Black SN850 1TB                         | 1         | 1.59%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB  | 1         | 1.59%   |
| SanDisk SDSSDX240GG25 240GB                        | 1         | 1.59%   |
| Samsung Portable SSD T5 1TB                        | 1         | 1.59%   |
| Samsung MZNLF128HCHP-000H1 128GB SSD               | 1         | 1.59%   |
| Realtek SSD 1TB                                    | 1         | 1.59%   |
| Phison E12 NVMe Controller 1TB                     | 1         | 1.59%   |
| NT-1TB 2242 1024GB                                 | 1         | 1.59%   |
| Micron MTFDHBA512QFD 512GB                         | 1         | 1.59%   |
| Micron 2200V_MTFDHBA512TCK 512GB                   | 1         | 1.59%   |
| Micron 1100_MTFDDAV512TBN 512GB SSD                | 1         | 1.59%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 9         | 9      | 64.29%  |
| Seagate | 4         | 4      | 28.57%  |
| Toshiba | 1         | 1      | 7.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Micron Technology   | 4         | 4      | 23.53%  |
| Kingston            | 4         | 4      | 23.53%  |
| WDC                 | 3         | 4      | 17.65%  |
| Samsung Electronics | 2         | 2      | 11.76%  |
| SSSTC               | 1         | 1      | 5.88%   |
| SanDisk             | 1         | 1      | 5.88%   |
| NT-1TB              | 1         | 1      | 5.88%   |
| Crucial             | 1         | 1      | 5.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 24        | 28     | 43.64%  |
| SSD     | 14        | 18     | 25.45%  |
| HDD     | 12        | 14     | 21.82%  |
| MMC     | 3         | 3      | 5.45%   |
| Unknown | 2         | 2      | 3.64%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 24        | 28     | 47.06%  |
| SATA | 21        | 31     | 41.18%  |
| SAS  | 3         | 3      | 5.88%   |
| MMC  | 3         | 3      | 5.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 12        | 12     | 46.15%  |
| 0.01-0.5   | 11        | 17     | 42.31%  |
| 1.01-2.0   | 2         | 2      | 7.69%   |
| 10.01-20.0 | 1         | 1      | 3.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 1001-2000      | 15        | 37.5%   |
| More than 3000 | 13        | 32.5%   |
| 251-500        | 6         | 15%     |
| 501-1000       | 4         | 10%     |
| 101-250        | 2         | 5%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 21-50          | 15        | 37.5%   |
| 101-250        | 7         | 17.5%   |
| 51-100         | 6         | 15%     |
| 251-500        | 5         | 12.5%   |
| 501-1000       | 5         | 12.5%   |
| More than 3000 | 1         | 2.5%    |
| 1-20           | 1         | 2.5%    |

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
| Detected | 40        | 65     | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 24        | 44.44%  |
| AMD                          | 6         | 11.11%  |
| Samsung Electronics          | 5         | 9.26%   |
| SanDisk                      | 3         | 5.56%   |
| Micron/Crucial Technology    | 3         | 5.56%   |
| SK hynix                     | 2         | 3.7%    |
| Micron Technology            | 2         | 3.7%    |
| KIOXIA                       | 2         | 3.7%    |
| Kingston Technology Company  | 2         | 3.7%    |
| Toshiba America Info Systems | 1         | 1.85%   |
| Realtek Semiconductor        | 1         | 1.85%   |
| Phison Electronics           | 1         | 1.85%   |
| INNOGRIT                     | 1         | 1.85%   |
| Biwin Storage Technology     | 1         | 1.85%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 7.02%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 4         | 7.02%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 5.26%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 3         | 5.26%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 5.26%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 5.26%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 2         | 3.51%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 3.51%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 2         | 3.51%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 2         | 3.51%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 3.51%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 3.51%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 3.51%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 1.75%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 1.75%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1         | 1.75%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 1         | 1.75%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                              | 1         | 1.75%   |
| Phison E12 NVMe Controller                                                     | 1         | 1.75%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 1         | 1.75%   |
| Micron 2200S NVMe SSD [Cassandra]                                              | 1         | 1.75%   |
| Kingston Company NV2 NVMe SSD E21T                                             | 1         | 1.75%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 1         | 1.75%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 1.75%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 1         | 1.75%   |
| Intel SSD 660P Series                                                          | 1         | 1.75%   |
| Intel SSD 600P Series                                                          | 1         | 1.75%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 1.75%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 1.75%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.75%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 1         | 1.75%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 1.75%   |
| INNOGRIT NVMe SSD Controller IG5236                                            | 1         | 1.75%   |
| Biwin Storage Non-Volatile memory controller                                   | 1         | 1.75%   |
| AMD RS690 PCI to PCI Bridge (PCI Express Port 2)                               | 1         | 1.75%   |
| AMD 500 Series Chipset SATA Controller                                         | 1         | 1.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 24        | 44.44%  |
| SATA | 22        | 40.74%  |
| RAID | 8         | 14.81%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 29        | 72.5%   |
| AMD    | 11        | 27.5%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 3         | 7.5%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 5%      |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 2         | 5%      |
| Intel 11th Gen Core i5-11400H @ 2.70GHz       | 2         | 5%      |
| AMD Ryzen 7 6800U with Radeon Graphics        | 2         | 5%      |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 5%      |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 1         | 2.5%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 2.5%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 2.5%    |
| Intel Core i7-4790K CPU @ 4.00GHz             | 1         | 2.5%    |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 2.5%    |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 2.5%    |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 2.5%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 2.5%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 2.5%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 2.5%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 2.5%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 2.5%    |
| Intel Core i5-4210H CPU @ 2.90GHz             | 1         | 2.5%    |
| Intel Core i5-10500H CPU @ 2.50GHz            | 1         | 2.5%    |
| Intel Celeron CPU N3350 @ 1.10GHz             | 1         | 2.5%    |
| Intel Atom x7-Z8700 CPU @ 1.60GHz             | 1         | 2.5%    |
| Intel 12th Gen Core i7-12700H                 | 1         | 2.5%    |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 1         | 2.5%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 1         | 2.5%    |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 2.5%    |
| AMD Ryzen 9 5900X 12-Core Processor           | 1         | 2.5%    |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 1         | 2.5%    |
| AMD Ryzen 9 5900HS with Radeon Graphics       | 1         | 2.5%    |
| AMD Ryzen 9 3900X 12-Core Processor           | 1         | 2.5%    |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 1         | 2.5%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 1         | 2.5%    |
| AMD Athlon Silver 3050e with Radeon Graphics  | 1         | 2.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Intel Core i7 | 10        | 25%     |
| Intel Core i5 | 10        | 25%     |
| Other         | 6         | 15%     |
| AMD Ryzen 9   | 4         | 10%     |
| AMD Ryzen 7   | 3         | 7.5%    |
| AMD Ryzen 5   | 3         | 7.5%    |
| Intel Core m3 | 1         | 2.5%    |
| Intel Celeron | 1         | 2.5%    |
| Intel Atom    | 1         | 2.5%    |
| AMD Athlon    | 1         | 2.5%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 17        | 42.5%   |
| 6      | 7         | 17.5%   |
| 2      | 7         | 17.5%   |
| 8      | 6         | 15%     |
| 12     | 2         | 5%      |
| 14     | 1         | 2.5%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 40        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 32        | 80%     |
| 1      | 8         | 20%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 40        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 40        | 100%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KabyLake   | 10        | 25%     |
| Unknown    | 7         | 17.5%   |
| Skylake    | 4         | 10%     |
| Zen+       | 3         | 7.5%    |
| Zen 3      | 3         | 7.5%    |
| Haswell    | 3         | 7.5%    |
| CometLake  | 3         | 7.5%    |
| TigerLake  | 2         | 5%      |
| Zen 2      | 1         | 2.5%    |
| Zen        | 1         | 2.5%    |
| Silvermont | 1         | 2.5%    |
| IvyBridge  | 1         | 2.5%    |
| Goldmont   | 1         | 2.5%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Nvidia | 26        | 40.63%  |
| Intel  | 26        | 40.63%  |
| AMD    | 12        | 18.75%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 6.25%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 4.69%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 3         | 4.69%   |
| Intel HD Graphics 630                                                                    | 3         | 4.69%   |
| Intel HD Graphics 530                                                                    | 3         | 4.69%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 3.13%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 2         | 3.13%   |
| Intel UHD Graphics 620                                                                   | 2         | 3.13%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 3.13%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 3.13%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 3.13%   |
| AMD Rembrandt [Radeon 680M]                                                              | 2         | 3.13%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 3.13%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.56%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 1.56%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 1.56%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 1.56%   |
| Nvidia TU106BM [GeForce RTX 2060 Mobile]                                                 | 1         | 1.56%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                                    | 1         | 1.56%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 1.56%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.56%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1         | 1.56%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 1         | 1.56%   |
| Nvidia GM204M [GeForce GTX 960 OEM / 970M]                                               | 1         | 1.56%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 1.56%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.56%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 1.56%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 1.56%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 1.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 1.56%   |
| Intel UHD Graphics 615                                                                   | 1         | 1.56%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 1.56%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 1         | 1.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 1.56%   |
| Intel HD Graphics 620                                                                    | 1         | 1.56%   |
| Intel HD Graphics 500                                                                    | 1         | 1.56%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.56%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.56%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 1         | 1.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 17        | 42.5%   |
| 1 x Intel      | 6         | 15%     |
| AMD + Nvidia   | 5         | 12.5%   |
| 1 x AMD        | 5         | 12.5%   |
| 1 x Nvidia     | 4         | 10%     |
| Intel + AMD    | 2         | 5%      |
| Other          | 1         | 2.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Proprietary | 21        | 52.5%   |
| Free        | 19        | 47.5%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 40        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Chimei Innolux      | 8         | 19.05%  |
| BOE                 | 8         | 19.05%  |
| AU Optronics        | 7         | 16.67%  |
| LG Display          | 6         | 14.29%  |
| Samsung Electronics | 2         | 4.76%   |
| Unknown (XXX)       | 1         | 2.38%   |
| TMX                 | 1         | 2.38%   |
| Sharp               | 1         | 2.38%   |
| RTK                 | 1         | 2.38%   |
| Philips             | 1         | 2.38%   |
| PANDA               | 1         | 2.38%   |
| Insignia            | 1         | 2.38%   |
| HJW                 | 1         | 2.38%   |
| Goldstar            | 1         | 2.38%   |
| GameMax             | 1         | 2.38%   |
| Fujitsu Siemens     | 1         | 2.38%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 2         | 4.76%   |
| BOE FLQ8423-24L0 BOE1003 1600x2560 113x181mm 8.4-inch                | 2         | 4.76%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 2         | 4.76%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch        | 1         | 2.38%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch              | 1         | 2.38%   |
| Sharp LQ173M1JW02 SHP14DB 1920x1080 382x215mm 17.3-inch              | 1         | 2.38%   |
| Samsung Electronics QBQ95 SAM7229 3840x2160 1872x1053mm 84.6-inch    | 1         | 2.38%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch | 1         | 2.38%   |
| RTK FHD HDR RTK2A3B 1920x1080 344x195mm 15.6-inch                    | 1         | 2.38%   |
| Philips LCD Monitor PHL4650 1280x768 530x398mm 26.1-inch             | 1         | 2.38%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 1         | 2.38%   |
| LG Display LCD Monitor LGD071E 1920x1080 344x194mm 15.5-inch         | 1         | 2.38%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch         | 1         | 2.38%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch         | 1         | 2.38%   |
| LG Display LCD Monitor LGD0459 1920x1080 382x215mm 17.3-inch         | 1         | 2.38%   |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch         | 1         | 2.38%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch          | 1         | 2.38%   |
| Insignia DX46L261A12 BBY0042 1920x1080 1020x570mm 46.0-inch          | 1         | 2.38%   |
| HJW MACROSILICON HJW9291 1680x1050 530x290mm 23.8-inch               | 1         | 2.38%   |
| Goldstar M237WDP GSM5779 1920x1080 598x336mm 27.0-inch               | 1         | 2.38%   |
| GameMax GMX32CEWQ GMX0315 2560x1440 697x392mm 31.5-inch              | 1         | 2.38%   |
| Fujitsu Siemens B22T-7 LED PG FUS082A 1920x1080 477x268mm 21.5-inch  | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN176E 1920x1080 381x214mm 17.2-inch     | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch     | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN1540 2560x1440 344x193mm 15.5-inch     | 1         | 2.38%   |
| BOE LCD Monitor BOE0AAD 1920x1080 355x200mm 16.0-inch                | 1         | 2.38%   |
| BOE LCD Monitor BOE0977 2560x1440 381x214mm 17.2-inch                | 1         | 2.38%   |
| BOE LCD Monitor BOE0816 1366x768 344x193mm 15.5-inch                 | 1         | 2.38%   |
| BOE LCD Monitor BOE06F1 1920x1080 344x194mm 15.5-inch                | 1         | 2.38%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                | 1         | 2.38%   |
| BOE LCD Monitor BOE065D 1920x1080 344x194mm 15.5-inch                | 1         | 2.38%   |
| AU Optronics LCD Monitor AUOED8F 1920x1080 344x193mm 15.5-inch       | 1         | 2.38%   |
| AU Optronics LCD Monitor AUOD0ED 1920x1080 344x193mm 15.5-inch       | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO82ED 1920x1080 344x193mm 15.5-inch       | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO135C 1366x768 256x144mm 11.6-inch        | 1         | 2.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 25        | 62.5%   |
| 1366x768 (WXGA) | 5         | 12.5%   |
| 2560x1440 (QHD) | 4         | 10%     |
| 3840x2160 (4K)  | 2         | 5%      |
| 1600x2560       | 2         | 5%      |
| 1280x960        | 1         | 2.5%    |
| 1280x768        | 1         | 2.5%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 23        | 54.76%  |
| 17     | 4         | 9.52%   |
| 14     | 2         | 4.76%   |
| 8      | 2         | 4.76%   |
| 84     | 1         | 2.38%   |
| 57     | 1         | 2.38%   |
| 54     | 1         | 2.38%   |
| 49     | 1         | 2.38%   |
| 34     | 1         | 2.38%   |
| 31     | 1         | 2.38%   |
| 27     | 1         | 2.38%   |
| 23     | 1         | 2.38%   |
| 21     | 1         | 2.38%   |
| 16     | 1         | 2.38%   |
| 11     | 1         | 2.38%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 25        | 59.52%  |
| 351-400     | 5         | 11.9%   |
| 701-800     | 2         | 4.76%   |
| 501-600     | 2         | 4.76%   |
| 101-200     | 2         | 4.76%   |
| 1001-1500   | 2         | 4.76%   |
| 601-700     | 1         | 2.38%   |
| 401-500     | 1         | 2.38%   |
| 201-300     | 1         | 2.38%   |
| 1501-2000   | 1         | 2.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 36        | 92.31%  |
| 0.62  | 2         | 5.13%   |
| 0.56  | 1         | 2.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 24        | 58.54%  |
| 121-130        | 4         | 9.76%   |
| More than 1000 | 3         | 7.32%   |
| 81-90          | 2         | 4.88%   |
| 1-40           | 2         | 4.88%   |
| 201-250        | 2         | 4.88%   |
| 51-60          | 1         | 2.44%   |
| 351-500        | 1         | 2.44%   |
| 301-350        | 1         | 2.44%   |
| 501-1000       | 1         | 2.44%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 24        | 60%     |
| 101-120       | 5         | 12.5%   |
| 1-50          | 3         | 7.5%    |
| 161-240       | 3         | 7.5%    |
| 51-100        | 3         | 7.5%    |
| More than 240 | 2         | 5%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 32        | 80%     |
| 2     | 6         | 15%     |
| 0     | 2         | 5%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 28        | 40.58%  |
| Intel                 | 24        | 34.78%  |
| Qualcomm Atheros      | 10        | 14.49%  |
| MediaTek              | 4         | 5.8%    |
| Broadcom Limited      | 1         | 1.45%   |
| Broadcom              | 1         | 1.45%   |
| ASIX Electronics      | 1         | 1.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 19        | 25.68%  |
| Realtek RTL8125 2.5GbE Controller                                    | 4         | 5.41%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 4         | 5.41%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 4         | 5.41%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 3         | 4.05%   |
| Intel Wireless 7265                                                  | 3         | 4.05%   |
| Intel Wireless 3165                                                  | 3         | 4.05%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 3         | 4.05%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 3         | 4.05%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 2         | 2.7%    |
| Realtek PCIe GbE Family Controller                                   | 2         | 2.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 2         | 2.7%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller            | 2         | 2.7%    |
| Intel Wireless 8265 / 8275                                           | 2         | 2.7%    |
| Intel Wi-Fi 6 AX201                                                  | 2         | 2.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                      | 2         | 2.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 1         | 1.35%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 1         | 1.35%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                     | 1         | 1.35%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                            | 1         | 1.35%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller            | 1         | 1.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 1         | 1.35%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 1         | 1.35%   |
| Intel I211 Gigabit Network Connection                                | 1         | 1.35%   |
| Intel Ethernet Connection (5) I219-LM                                | 1         | 1.35%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 1         | 1.35%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 1         | 1.35%   |
| Broadcom Limited BCM4352 802.11ac Dual Band Wireless Network Adapter | 1         | 1.35%   |
| Broadcom BCM4356 802.11ac Wireless Network Adapter                   | 1         | 1.35%   |
| ASIX AX88179 Gigabit Ethernet                                        | 1         | 1.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 24        | 58.54%  |
| Qualcomm Atheros      | 7         | 17.07%  |
| Realtek Semiconductor | 4         | 9.76%   |
| MediaTek              | 4         | 9.76%   |
| Broadcom Limited      | 1         | 2.44%   |
| Broadcom              | 1         | 2.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 4         | 9.76%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 4         | 9.76%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 3         | 7.32%   |
| Intel Wireless 7265                                                  | 3         | 7.32%   |
| Intel Wireless 3165                                                  | 3         | 7.32%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 3         | 7.32%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 3         | 7.32%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 2         | 4.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 2         | 4.88%   |
| Intel Wireless 8265 / 8275                                           | 2         | 4.88%   |
| Intel Wi-Fi 6 AX201                                                  | 2         | 4.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 2         | 4.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 1         | 2.44%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 1         | 2.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 1         | 2.44%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 1         | 2.44%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 1         | 2.44%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 1         | 2.44%   |
| Broadcom Limited BCM4352 802.11ac Dual Band Wireless Network Adapter | 1         | 2.44%   |
| Broadcom BCM4356 802.11ac Wireless Network Adapter                   | 1         | 2.44%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 26        | 78.79%  |
| Qualcomm Atheros      | 4         | 12.12%  |
| Intel                 | 2         | 6.06%   |
| ASIX Electronics      | 1         | 3.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19        | 57.58%  |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 12.12%  |
| Realtek PCIe GbE Family Controller                                | 2         | 6.06%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 6.06%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 3.03%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 3.03%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 3.03%   |
| Intel I211 Gigabit Network Connection                             | 1         | 3.03%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 3.03%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 3.03%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 40        | 55.56%  |
| Ethernet | 32        | 44.44%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 34        | 80.95%  |
| Ethernet | 8         | 19.05%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 29        | 72.5%   |
| 1     | 10        | 25%     |
| 3     | 1         | 2.5%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 25        | 62.5%   |
| Yes  | 15        | 37.5%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 23        | 62.16%  |
| Qualcomm Atheros Communications | 4         | 10.81%  |
| Lite-On Technology              | 3         | 8.11%   |
| IMC Networks                    | 3         | 8.11%   |
| Realtek Semiconductor           | 1         | 2.7%    |
| MediaTek                        | 1         | 2.7%    |
| Foxconn / Hon Hai               | 1         | 2.7%    |
| Cambridge Silicon Radio         | 1         | 2.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 8         | 21.62%  |
| Intel AX201 Bluetooth                               | 8         | 21.62%  |
| Intel AX210 Bluetooth                               | 4         | 10.81%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 8.11%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 5.41%   |
| IMC Networks Wireless_Device                        | 2         | 5.41%   |
| Realtek Bluetooth Radio                             | 1         | 2.7%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 2.7%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 2.7%    |
| MediaTek Wireless_Device                            | 1         | 2.7%    |
| Lite-On Wireless_Device                             | 1         | 2.7%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 2.7%    |
| Lite-On Bluetooth Device                            | 1         | 2.7%    |
| IMC Networks Bluetooth Radio                        | 1         | 2.7%    |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 1         | 2.7%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 27        | 42.86%  |
| Nvidia                 | 17        | 26.98%  |
| AMD                    | 12        | 19.05%  |
| Sony                   | 3         | 4.76%   |
| Realtek Semiconductor  | 1         | 1.59%   |
| Logitech               | 1         | 1.59%   |
| Kingston Technology    | 1         | 1.59%   |
| Generalplus Technology | 1         | 1.59%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                              | 9         | 12.16%  |
| Intel Sunrise Point-LP HD Audio                                     | 5         | 6.76%   |
| Nvidia TU106 High Definition Audio Controller                       | 3         | 4.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 3         | 4.05%   |
| Intel Tiger Lake-H HD Audio Controller                              | 3         | 4.05%   |
| Intel Comet Lake PCH cAVS                                           | 3         | 4.05%   |
| Intel CM238 HD Audio Controller                                     | 3         | 4.05%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 3         | 4.05%   |
| Sony DualSense wireless controller (PS5)                            | 2         | 2.7%    |
| Nvidia GP107GL High Definition Audio Controller                     | 2         | 2.7%    |
| Nvidia GA106 High Definition Audio Controller                       | 2         | 2.7%    |
| Nvidia GA104 High Definition Audio Controller                       | 2         | 2.7%    |
| Nvidia Audio device                                                 | 2         | 2.7%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 2         | 2.7%    |
| Intel Cannon Lake PCH cAVS                                          | 2         | 2.7%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 2         | 2.7%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 2         | 2.7%    |
| AMD Starship/Matisse HD Audio Controller                            | 2         | 2.7%    |
| AMD Renoir Radeon High Definition Audio Controller                  | 2         | 2.7%    |
| AMD Rembrandt Radeon High Definition Audio Controller               | 2         | 2.7%    |
| Sony DualShock 4 [CUH-ZCT2x]                                        | 1         | 1.35%   |
| Realtek Semiconductor USB Audio                                     | 1         | 1.35%   |
| Nvidia TU116 High Definition Audio Controller                       | 1         | 1.35%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller      | 1         | 1.35%   |
| Nvidia TU104 HD Audio Controller                                    | 1         | 1.35%   |
| Nvidia GP102 HDMI Audio Controller                                  | 1         | 1.35%   |
| Nvidia GM206 High Definition Audio Controller                       | 1         | 1.35%   |
| Nvidia GF108 High Definition Audio Controller                       | 1         | 1.35%   |
| Logitech Logitech G PRO X Gaming Headset                            | 1         | 1.35%   |
| Kingston Technology HyperX QuadCast                                 | 1         | 1.35%   |
| Intel Comet Lake PCH-LP cAVS                                        | 1         | 1.35%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster   | 1         | 1.35%   |
| Intel Alder Lake PCH-P High Definition Audio Controller             | 1         | 1.35%   |
| Intel 9 Series Chipset Family HD Audio Controller                   | 1         | 1.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 1         | 1.35%   |
| Generalplus Technology USB Audio Device                             | 1         | 1.35%   |
| AMD Navi 31 HDMI/DP Audio                                           | 1         | 1.35%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]          | 1         | 1.35%   |

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
| Chicony Electronics           | 10        | 37.04%  |
| Microdia                      | 4         | 14.81%  |
| IMC Networks                  | 4         | 14.81%  |
| Sunplus Innovation Technology | 2         | 7.41%   |
| Quanta                        | 2         | 7.41%   |
| Bison Electronics             | 2         | 7.41%   |
| Sonix Technology              | 1         | 3.7%    |
| Silicon Motion                | 1         | 3.7%    |
| Realtek Semiconductor         | 1         | 3.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                             | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| IMC Networks Integrated Camera    | 3         | 11.11%  |
| Chicony Integrated Camera         | 2         | 7.41%   |
| Chicony HD WebCam                 | 2         | 7.41%   |
| Chicony HD User Facing            | 2         | 7.41%   |
| Bison Lenovo EasyCamera           | 2         | 7.41%   |
| Sunplus Integrated_Webcam_HD      | 1         | 3.7%    |
| Sunplus HD WebCam                 | 1         | 3.7%    |
| Sonix USB2.0 HD UVC WebCam        | 1         | 3.7%    |
| Silicon Motion 300k Pixel Camera  | 1         | 3.7%    |
| Realtek Integrated Webcam         | 1         | 3.7%    |
| Quanta HP HD Camera               | 1         | 3.7%    |
| Quanta HD User Facing             | 1         | 3.7%    |
| Microdia USB 2.0 Camera           | 1         | 3.7%    |
| Microdia Integrated_Webcam_HD     | 1         | 3.7%    |
| Microdia Integrated_Webcam_FHD    | 1         | 3.7%    |
| Microdia HP Webcam                | 1         | 3.7%    |
| IMC Networks USB2.0 HD UVC WebCam | 1         | 3.7%    |
| Chicony USB2.0 0.3M UVC WebCam    | 1         | 3.7%    |
| Chicony HP Wide Vision HD Camera  | 1         | 3.7%    |
| Chicony HP Truevision HD          | 1         | 3.7%    |
| Chicony EasyCamera                | 1         | 3.7%    |

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
| 0     | 30        | 75%     |
| 1     | 9         | 22.5%   |
| 2     | 1         | 2.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 5         | 45.45%  |
| Multimedia controller | 2         | 18.18%  |
| Fingerprint reader    | 2         | 18.18%  |
| Net/wireless          | 1         | 9.09%   |
| Chipcard              | 1         | 9.09%   |

