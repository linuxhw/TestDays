ChimeraOS - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for ChimeraOS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/ChimeraOS/Desktop/README.md) and [notebooks](/Dist/ChimeraOS/Notebook/README.md).

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

Total: 74

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 1998                        | Desktop     | [91f6e54877](https://linux-hardware.org/?probe=91f6e54877) | Jun 30, 2023 |
| AMI           | Unknown                     | Notebook    | [88da6b0232](https://linux-hardware.org/?probe=88da6b0232) | Jun 25, 2023 |
| Acer          | Aspire A315-58G             | Notebook    | [ea2b8a58b1](https://linux-hardware.org/?probe=ea2b8a58b1) | Jun 22, 2023 |
| Gigabyte      | G1.Sniper A88X-CF           | Desktop     | [d4470db5d3](https://linux-hardware.org/?probe=d4470db5d3) | Jun 20, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [50efda9604](https://linux-hardware.org/?probe=50efda9604) | Jun 19, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [299db094f8](https://linux-hardware.org/?probe=299db094f8) | Jun 18, 2023 |
| Dell          | 07HXY6 A01                  | Desktop     | [ec3adcbe42](https://linux-hardware.org/?probe=ec3adcbe42) | Jun 16, 2023 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [4932ae40b6](https://linux-hardware.org/?probe=4932ae40b6) | Jun 13, 2023 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [c6401638dd](https://linux-hardware.org/?probe=c6401638dd) | Jun 11, 2023 |
| Google        | Snappy                      | Notebook    | [737988d62e](https://linux-hardware.org/?probe=737988d62e) | Jun 11, 2023 |
| Google        | Snappy                      | Notebook    | [f228dabe46](https://linux-hardware.org/?probe=f228dabe46) | Jun 11, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [798d8e8914](https://linux-hardware.org/?probe=798d8e8914) | Jun 11, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [5e060b53c2](https://linux-hardware.org/?probe=5e060b53c2) | Jun 10, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [0d548e314b](https://linux-hardware.org/?probe=0d548e314b) | Jun 10, 2023 |
| Dell          | Inspiron 14 7420 2-in-1     | Convertible | [d7b5162532](https://linux-hardware.org/?probe=d7b5162532) | Jun 09, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [d43ce99616](https://linux-hardware.org/?probe=d43ce99616) | Jun 07, 2023 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [8c6370ac0d](https://linux-hardware.org/?probe=8c6370ac0d) | May 23, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [4bbf7dc69e](https://linux-hardware.org/?probe=4bbf7dc69e) | May 21, 2023 |
| Microsoft     | Surface Book                | Tablet      | [7bb9611a98](https://linux-hardware.org/?probe=7bb9611a98) | May 21, 2023 |
| Micro Elec... | MG-VCP17I-3070              | Notebook    | [8ba5bb4bc7](https://linux-hardware.org/?probe=8ba5bb4bc7) | May 19, 2023 |
| Acer          | Aspire Z3-705               | All in one  | [95fcf79dd4](https://linux-hardware.org/?probe=95fcf79dd4) | May 18, 2023 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [41b69ae4db](https://linux-hardware.org/?probe=41b69ae4db) | May 12, 2023 |
| ASUSTek       | PRIME B760-PLUS D4          | Desktop     | [bb01d9e92b](https://linux-hardware.org/?probe=bb01d9e92b) | May 12, 2023 |
| ASUSTek       | ROG STRIX B460-I GAMING     | Desktop     | [3a9528f661](https://linux-hardware.org/?probe=3a9528f661) | May 10, 2023 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [bf3fee03d2](https://linux-hardware.org/?probe=bf3fee03d2) | May 09, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | Notebook    | [79bdb284fe](https://linux-hardware.org/?probe=79bdb284fe) | May 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [ad66608cf0](https://linux-hardware.org/?probe=ad66608cf0) | May 08, 2023 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [101ec0a833](https://linux-hardware.org/?probe=101ec0a833) | May 05, 2023 |
| AYANEO        | 2                           | Tablet      | [672b480b96](https://linux-hardware.org/?probe=672b480b96) | May 05, 2023 |
| ASUSTek       | PRIME B760-PLUS D4          | Desktop     | [4ec161ab9b](https://linux-hardware.org/?probe=4ec161ab9b) | May 04, 2023 |
| MSI           | CX62 6QD                    | Notebook    | [9c6b781beb](https://linux-hardware.org/?probe=9c6b781beb) | May 02, 2023 |
| AYANEO        | 2                           | Tablet      | [4db5d91519](https://linux-hardware.org/?probe=4db5d91519) | Apr 21, 2023 |
| Dell          | 0FDY5C A00                  | Desktop     | [a6865b8591](https://linux-hardware.org/?probe=a6865b8591) | Apr 16, 2023 |
| HP            | 250 G4 Notebook PC          | Notebook    | [08036de728](https://linux-hardware.org/?probe=08036de728) | Apr 15, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [a34f2e065b](https://linux-hardware.org/?probe=a34f2e065b) | Apr 14, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | Notebook    | [cacab44211](https://linux-hardware.org/?probe=cacab44211) | Apr 13, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | Notebook    | [2a4894bdc0](https://linux-hardware.org/?probe=2a4894bdc0) | Apr 13, 2023 |
| MSI           | MS-7C91                     | Notebook    | [663c6729cb](https://linux-hardware.org/?probe=663c6729cb) | Apr 12, 2023 |
| ASUSTek       | ROG STRIX B460-I GAMING     | Desktop     | [14db4e6f1d](https://linux-hardware.org/?probe=14db4e6f1d) | Apr 11, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [03db223af4](https://linux-hardware.org/?probe=03db223af4) | Apr 06, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [f8c2ffcd09](https://linux-hardware.org/?probe=f8c2ffcd09) | Apr 06, 2023 |
| Razer         | Blade Pro 17 (Early 2020... | Notebook    | [36d75e1d7f](https://linux-hardware.org/?probe=36d75e1d7f) | Mar 26, 2023 |
| Razer         | Blade Pro 17 (Early 2020... | Notebook    | [244b228a30](https://linux-hardware.org/?probe=244b228a30) | Mar 26, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [8a92687be7](https://linux-hardware.org/?probe=8a92687be7) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [f383688a79](https://linux-hardware.org/?probe=f383688a79) | Mar 23, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [ad4c43dd09](https://linux-hardware.org/?probe=ad4c43dd09) | Mar 21, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [de9712600d](https://linux-hardware.org/?probe=de9712600d) | Mar 20, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [1ee17b12bd](https://linux-hardware.org/?probe=1ee17b12bd) | Mar 19, 2023 |
| Gigabyte      | B460M DS3H AC V2-Y1         | Desktop     | [b21cd49226](https://linux-hardware.org/?probe=b21cd49226) | Mar 16, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [9f40b861a5](https://linux-hardware.org/?probe=9f40b861a5) | Mar 12, 2023 |
| Gigabyte      | B460M DS3H AC V2-Y1         | Desktop     | [7f8fc2ba96](https://linux-hardware.org/?probe=7f8fc2ba96) | Mar 10, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [b8ea458df5](https://linux-hardware.org/?probe=b8ea458df5) | Mar 08, 2023 |
| Dell          | 0XHGV1 A00                  | Desktop     | [8fa504e81f](https://linux-hardware.org/?probe=8fa504e81f) | Mar 07, 2023 |
| Intel         | DB75EN AAG39650-400         | Desktop     | [4a0feca3f5](https://linux-hardware.org/?probe=4a0feca3f5) | Mar 02, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [432235c684](https://linux-hardware.org/?probe=432235c684) | Feb 25, 2023 |
| Gigabyte      | H77M-D3H                    | Desktop     | [01eb743492](https://linux-hardware.org/?probe=01eb743492) | Feb 25, 2023 |
| Gigabyte      | H77M-D3H                    | Desktop     | [766790f373](https://linux-hardware.org/?probe=766790f373) | Feb 25, 2023 |
| ASUSTek       | B150I PRO GAMING/WIFI/AU... | Desktop     | [eb1e211b0f](https://linux-hardware.org/?probe=eb1e211b0f) | Feb 25, 2023 |
| MSI           | GE75 Raider 10SF            | Notebook    | [cc21335206](https://linux-hardware.org/?probe=cc21335206) | Feb 24, 2023 |
| HP            | 1998                        | Desktop     | [dbb952f3f6](https://linux-hardware.org/?probe=dbb952f3f6) | Feb 13, 2023 |
| HP            | 1998                        | Desktop     | [0171575a1d](https://linux-hardware.org/?probe=0171575a1d) | Feb 13, 2023 |
| ASUSTek       | K45VM                       | Notebook    | [06af577a0c](https://linux-hardware.org/?probe=06af577a0c) | Feb 04, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [69d2cb7e14](https://linux-hardware.org/?probe=69d2cb7e14) | Jan 11, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [f5ff2f8568](https://linux-hardware.org/?probe=f5ff2f8568) | Jan 06, 2023 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [3e4b14919e](https://linux-hardware.org/?probe=3e4b14919e) | Jan 05, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [02b3cbc8c6](https://linux-hardware.org/?probe=02b3cbc8c6) | Jan 04, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [13ae6c7e25](https://linux-hardware.org/?probe=13ae6c7e25) | Jan 01, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [49ca01435b](https://linux-hardware.org/?probe=49ca01435b) | Dec 27, 2022 |
| ONE-NETBOO... | ONE XPLAYER                 | Tablet      | [d721c7ae17](https://linux-hardware.org/?probe=d721c7ae17) | Dec 27, 2022 |
| Lenovo        | ThinkCentre M70e 0832B1U    | Desktop     | [d95663a632](https://linux-hardware.org/?probe=d95663a632) | Dec 07, 2022 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [2a7b6d570f](https://linux-hardware.org/?probe=2a7b6d570f) | Nov 26, 2022 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [58b3db6784](https://linux-hardware.org/?probe=58b3db6784) | Nov 23, 2022 |
| ONE-NETBOO... | ONE XPLAYER                 | Tablet      | [9bec9e1625](https://linux-hardware.org/?probe=9bec9e1625) | Oct 01, 2022 |
| ONE-NETBOO... | ONE XPLAYER                 | Tablet      | [501a588f11](https://linux-hardware.org/?probe=501a588f11) | Oct 01, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| ChimeraOS 42 | 17        | 30.91%  |
| ChimeraOS 39 | 15        | 27.27%  |
| ChimeraOS 41 | 11        | 20%     |
| ChimeraOS 38 | 6         | 10.91%  |
| ChimeraOS 37 | 4         | 7.27%   |
| ChimeraOS 43 | 1         | 1.82%   |
| ChimeraOS 35 | 1         | 1.82%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| ChimeraOS | 53        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version        | Computers | Percent |
|----------------|-----------|---------|
| 6.1.27-1-lts   | 17        | 30.36%  |
| 6.1.11-arch1-1 | 15        | 26.79%  |
| 6.1.21-1-lts   | 11        | 19.64%  |
| 6.1.1-arch1-1  | 6         | 10.71%  |
| 6.0.8-arch1-1  | 4         | 7.14%   |
| 6.3.3-arch1-1  | 1         | 1.79%   |
| 6.3.1-arch2-1  | 1         | 1.79%   |
| 5.19.6-arch1-1 | 1         | 1.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1.27  | 17        | 30.36%  |
| 6.1.11  | 15        | 26.79%  |
| 6.1.21  | 11        | 19.64%  |
| 6.1.1   | 6         | 10.71%  |
| 6.0.8   | 4         | 7.14%   |
| 6.3.3   | 1         | 1.79%   |
| 6.3.1   | 1         | 1.79%   |
| 5.19.6  | 1         | 1.79%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 48        | 88.89%  |
| 6.0     | 4         | 7.41%   |
| 6.3     | 1         | 1.85%   |
| 5.19    | 1         | 1.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 53        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GNOME   | 52        | 98.11%  |
| steamos | 1         | 1.89%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 47        | 88.68%  |
| X11     | 6         | 11.32%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 53        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 49        | 92.45%  |
| pt_BR | 1         | 1.89%   |
| it_IT | 1         | 1.89%   |
| es_ES | 1         | 1.89%   |
| de_DE | 1         | 1.89%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 53        | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 53        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 53        | 100%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 53        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 53        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Gigabyte Technology    | 9         | 16.98%  |
| ASUSTek Computer       | 9         | 16.98%  |
| Lenovo                 | 5         | 9.43%   |
| MSI                    | 4         | 7.55%   |
| Hewlett-Packard        | 4         | 7.55%   |
| Dell                   | 4         | 7.55%   |
| Acer                   | 4         | 7.55%   |
| Razer                  | 2         | 3.77%   |
| ONE-NETBOOK TECHNOLOGY | 2         | 3.77%   |
| ONE-NETBOOK            | 2         | 3.77%   |
| AYANEO                 | 2         | 3.77%   |
| Microsoft              | 1         | 1.89%   |
| Micro Electronics      | 1         | 1.89%   |
| MACHINIST              | 1         | 1.89%   |
| Intel                  | 1         | 1.89%   |
| Google                 | 1         | 1.89%   |
| AMI                    | 1         | 1.89%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| ONE-NETBOOK TECHNOLOGY ONE XPLAYER          | 2         | 3.77%   |
| ONE-NETBOOK ONEXPLAYER 2 ARP23              | 2         | 3.77%   |
| HP EliteDesk 800 G1 SFF                     | 2         | 3.77%   |
| AYANEO 2                                    | 2         | 3.77%   |
| Razer Blade Pro 17 (Early 2020) - RZ09-0329 | 1         | 1.89%   |
| Razer Blade 14 - RZ09-0370                  | 1         | 1.89%   |
| MSI MS-7D73                                 | 1         | 1.89%   |
| MSI MS-7C91                                 | 1         | 1.89%   |
| MSI GE75 Raider 10SF                        | 1         | 1.89%   |
| MSI CX62 6QD                                | 1         | 1.89%   |
| Microsoft Surface Book                      | 1         | 1.89%   |
| Micro MG-VCP17I-3070                        | 1         | 1.89%   |
| MACHINIST X99-RS9 V2.0                      | 1         | 1.89%   |
| Lenovo Y50-70 20378                         | 1         | 1.89%   |
| Lenovo ThinkCentre M70e 0832B1U             | 1         | 1.89%   |
| Lenovo Legion Y540-15IRH 81SX               | 1         | 1.89%   |
| Lenovo IdeaPad 700-15ISK 80RU               | 1         | 1.89%   |
| Lenovo IdeaPad 320-15IKB 80YH               | 1         | 1.89%   |
| Intel DB75EN AAG39650-400                   | 1         | 1.89%   |
| HP EliteBook 850 G8 Notebook PC             | 1         | 1.89%   |
| HP 250 G4 Notebook PC                       | 1         | 1.89%   |
| Google Snappy                               | 1         | 1.89%   |
| Gigabyte X570S AORUS ELITE AX               | 1         | 1.89%   |
| Gigabyte X570 AORUS ELITE WIFI              | 1         | 1.89%   |
| Gigabyte X470 AORUS GAMING 5 WIFI           | 1         | 1.89%   |
| Gigabyte H77M-D3H                           | 1         | 1.89%   |
| Gigabyte H510M H                            | 1         | 1.89%   |
| Gigabyte G1.Sniper A88X-CF                  | 1         | 1.89%   |
| Gigabyte B550I AORUS PRO AX                 | 1         | 1.89%   |
| Gigabyte B460M DS3H AC V2-Y1                | 1         | 1.89%   |
| Gigabyte B450 AORUS M                       | 1         | 1.89%   |
| Dell OptiPlex 7050                          | 1         | 1.89%   |
| Dell OptiPlex 7020                          | 1         | 1.89%   |
| Dell OptiPlex 5055 Ryzen APU                | 1         | 1.89%   |
| Dell Inspiron 14 7420 2-in-1                | 1         | 1.89%   |
| ASUS TUF Gaming FX505DV_FX505DV             | 1         | 1.89%   |
| ASUS ROG Zephyrus G15 GA503QM_GA503QM       | 1         | 1.89%   |
| ASUS ROG STRIX B650E-I GAMING WIFI          | 1         | 1.89%   |
| ASUS ROG STRIX B550-F GAMING                | 1         | 1.89%   |
| ASUS ROG STRIX B460-I GAMING                | 1         | 1.89%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| ASUS ROG                   | 4         | 7.55%   |
| Dell OptiPlex              | 3         | 5.66%   |
| Acer Aspire                | 3         | 5.66%   |
| Razer Blade                | 2         | 3.77%   |
| ONE-NETBOOK TECHNOLOGY ONE | 2         | 3.77%   |
| ONE-NETBOOK ONEXPLAYER     | 2         | 3.77%   |
| Lenovo IdeaPad             | 2         | 3.77%   |
| HP EliteDesk               | 2         | 3.77%   |
| AYANEO 2                   | 2         | 3.77%   |
| MSI MS-7D73                | 1         | 1.89%   |
| MSI MS-7C91                | 1         | 1.89%   |
| MSI GE75                   | 1         | 1.89%   |
| MSI CX62                   | 1         | 1.89%   |
| Microsoft Surface          | 1         | 1.89%   |
| Micro MG-VCP17I-3070       | 1         | 1.89%   |
| MACHINIST X99-RS9          | 1         | 1.89%   |
| Lenovo Y50-70              | 1         | 1.89%   |
| Lenovo ThinkCentre         | 1         | 1.89%   |
| Lenovo Legion              | 1         | 1.89%   |
| Intel DB75EN               | 1         | 1.89%   |
| HP EliteBook               | 1         | 1.89%   |
| HP 250                     | 1         | 1.89%   |
| Google Snappy              | 1         | 1.89%   |
| Gigabyte X570S             | 1         | 1.89%   |
| Gigabyte X570              | 1         | 1.89%   |
| Gigabyte X470              | 1         | 1.89%   |
| Gigabyte H77M-D3H          | 1         | 1.89%   |
| Gigabyte H510M             | 1         | 1.89%   |
| Gigabyte G1.Sniper         | 1         | 1.89%   |
| Gigabyte B550I             | 1         | 1.89%   |
| Gigabyte B460M             | 1         | 1.89%   |
| Gigabyte B450              | 1         | 1.89%   |
| Dell Inspiron              | 1         | 1.89%   |
| ASUS TUF                   | 1         | 1.89%   |
| ASUS PRIME                 | 1         | 1.89%   |
| ASUS P8H61-MX              | 1         | 1.89%   |
| ASUS K45VM                 | 1         | 1.89%   |
| ASUS B150I                 | 1         | 1.89%   |
| Acer Nitro                 | 1         | 1.89%   |
| Unknown                    | 1         | 1.89%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2022 | 9         | 16.98%  |
| 2021 | 8         | 15.09%  |
| 2020 | 7         | 13.21%  |
| 2019 | 4         | 7.55%   |
| 2017 | 4         | 7.55%   |
| 2016 | 4         | 7.55%   |
| 2012 | 4         | 7.55%   |
| 2023 | 3         | 5.66%   |
| 2015 | 3         | 5.66%   |
| 2013 | 3         | 5.66%   |
| 2018 | 2         | 3.77%   |
| 2014 | 1         | 1.89%   |
| 2010 | 1         | 1.89%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 24        | 45.28%  |
| Notebook    | 22        | 41.51%  |
| Tablet      | 5         | 9.43%   |
| Convertible | 1         | 1.89%   |
| All in one  | 1         | 1.89%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 53        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 52        | 98.11%  |
| Yes  | 1         | 1.89%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 15        | 28.3%   |
| 16.01-24.0  | 12        | 22.64%  |
| 8.01-16.0   | 9         | 16.98%  |
| 4.01-8.0    | 7         | 13.21%  |
| 3.01-4.0    | 4         | 7.55%   |
| 24.01-32.0  | 4         | 7.55%   |
| 64.01-256.0 | 2         | 3.77%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 25        | 45.45%  |
| 1.01-2.0   | 13        | 23.64%  |
| 3.01-4.0   | 11        | 20%     |
| 4.01-8.0   | 5         | 9.09%   |
| 16.01-24.0 | 1         | 1.82%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 25        | 45.45%  |
| 2      | 18        | 32.73%  |
| 3      | 8         | 14.55%  |
| 4      | 2         | 3.64%   |
| 8      | 1         | 1.82%   |
| 7      | 1         | 1.82%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 47        | 88.68%  |
| Yes       | 6         | 11.32%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 42        | 79.25%  |
| No        | 11        | 20.75%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 84.91%  |
| No        | 8         | 15.09%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 42        | 79.25%  |
| No        | 11        | 20.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 26        | 49.06%  |
| UK           | 3         | 5.66%   |
| Brazil       | 3         | 5.66%   |
| Russia       | 2         | 3.77%   |
| Italy        | 2         | 3.77%   |
| Germany      | 2         | 3.77%   |
| Canada       | 2         | 3.77%   |
| Australia    | 2         | 3.77%   |
| Spain        | 1         | 1.89%   |
| Saudi Arabia | 1         | 1.89%   |
| Romania      | 1         | 1.89%   |
| Poland       | 1         | 1.89%   |
| Norway       | 1         | 1.89%   |
| Netherlands  | 1         | 1.89%   |
| Macao        | 1         | 1.89%   |
| Hungary      | 1         | 1.89%   |
| Estonia      | 1         | 1.89%   |
| Costa Rica   | 1         | 1.89%   |
| Belgium      | 1         | 1.89%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Chattanooga              | 2         | 3.7%    |
| Yaroslavl                | 1         | 1.85%   |
| Wroclaw                  | 1         | 1.85%   |
| Watsonville              | 1         | 1.85%   |
| Virginia Beach           | 1         | 1.85%   |
| Tulcea                   | 1         | 1.85%   |
| Toronto                  | 1         | 1.85%   |
| Tallinn                  | 1         | 1.85%   |
| Sumaré                  | 1         | 1.85%   |
| Steyning                 | 1         | 1.85%   |
| St Louis                 | 1         | 1.85%   |
| Shelbyville              | 1         | 1.85%   |
| Seattle                  | 1         | 1.85%   |
| Santa Cruz das Palmeiras | 1         | 1.85%   |
| Sanford                  | 1         | 1.85%   |
| San José                | 1         | 1.85%   |
| Samara                   | 1         | 1.85%   |
| Saltillo                 | 1         | 1.85%   |
| Round Rock               | 1         | 1.85%   |
| Ridley Park              | 1         | 1.85%   |
| Racine                   | 1         | 1.85%   |
| Pittsburg                | 1         | 1.85%   |
| Phoenix                  | 1         | 1.85%   |
| Philadelphia             | 1         | 1.85%   |
| Pennsauken               | 1         | 1.85%   |
| Newport News             | 1         | 1.85%   |
| New York                 | 1         | 1.85%   |
| Monticello               | 1         | 1.85%   |
| Milan                    | 1         | 1.85%   |
| Melbourne                | 1         | 1.85%   |
| Macao                    | 1         | 1.85%   |
| Longueuil                | 1         | 1.85%   |
| Lewiston                 | 1         | 1.85%   |
| Jeddah                   | 1         | 1.85%   |
| Houston                  | 1         | 1.85%   |
| Hot Springs              | 1         | 1.85%   |
| Hixson                   | 1         | 1.85%   |
| Hamburg                  | 1         | 1.85%   |
| Gary                     | 1         | 1.85%   |
| Eidsberg                 | 1         | 1.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 14        | 22     | 15.05%  |
| WDC                          | 11        | 14     | 11.83%  |
| Seagate                      | 11        | 13     | 11.83%  |
| Kingston                     | 9         | 9      | 9.68%   |
| Sandisk                      | 7         | 11     | 7.53%   |
| Unknown                      | 6         | 6      | 6.45%   |
| Toshiba                      | 5         | 6      | 5.38%   |
| Phison Electronics           | 4         | 4      | 4.3%    |
| Micron Technology            | 4         | 6      | 4.3%    |
| Micron/Crucial Technology    | 3         | 3      | 3.23%   |
| Intel                        | 3         | 4      | 3.23%   |
| SK hynix                     | 2         | 2      | 2.15%   |
| Crucial                      | 2         | 4      | 2.15%   |
| Silicon Motion               | 1         | 1      | 1.08%   |
| Shenzhen Longsys Electronics | 1         | 1      | 1.08%   |
| Netac                        | 1         | 1      | 1.08%   |
| Kingston Technology Company  | 1         | 1      | 1.08%   |
| KingFast                     | 1         | 1      | 1.08%   |
| KingDian                     | 1         | 3      | 1.08%   |
| Hitachi                      | 1         | 1      | 1.08%   |
| Hewlett-Packard              | 1         | 1      | 1.08%   |
| Fanxiang                     | 1         | 1      | 1.08%   |
| Corsair                      | 1         | 1      | 1.08%   |
| Biwin Storage Technology     | 1         | 1      | 1.08%   |
| ADATA Technology             | 1         | 2      | 1.08%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB   | 5         | 5%      |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB    | 3         | 3%      |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                   | 3         | 3%      |
| Unknown MMC Card  64GB                                | 2         | 2%      |
| Samsung SSD 870 QVO 2TB                               | 2         | 2%      |
| Phison PS5013 E13 NVMe Controller 512GB               | 2         | 2%      |
| Kingston SA400S37120G 120GB SSD                       | 2         | 2%      |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 1         | 1%      |
| WDC WDBNCE5000PNC 500GB SSD                           | 1         | 1%      |
| WDC WD7500BPVT-80HXZT3 752GB                          | 1         | 1%      |
| WDC WD5000BEVT-22A0RT0 500GB                          | 1         | 1%      |
| WDC WD5000AVDS-63U7B1 500GB                           | 1         | 1%      |
| WDC WD40EZRX-00SPEB0 4TB                              | 1         | 1%      |
| WDC WD20SPZX-08UA7 2TB                                | 1         | 1%      |
| WDC WD20EARX-00PASB0 2TB                              | 1         | 1%      |
| WDC WD201KFGX-68BKJN0 20TB                            | 1         | 1%      |
| WDC WD1500HLFS-01G6U0 150GB                           | 1         | 1%      |
| WDC WD10SPCX-24HWST1 1TB                              | 1         | 1%      |
| WDC WD10JPLX-00MBPT0 1TB                              | 1         | 1%      |
| Unknown SD/MMC/MS PRO 250GB                           | 1         | 1%      |
| Unknown NVMe SSD Drive 1024GB                         | 1         | 1%      |
| Unknown MMC Card  512GB                               | 1         | 1%      |
| Unknown MMC Card  16GB                                | 1         | 1%      |
| Toshiba XG6 NVMe SSD Controller 2TB                   | 1         | 1%      |
| Toshiba NVMe Controller 256GB                         | 1         | 1%      |
| Toshiba MQ02ABD100H 1TB                               | 1         | 1%      |
| Toshiba MQ01ABF050 500GB                              | 1         | 1%      |
| Toshiba MK1234GSX 120GB                               | 1         | 1%      |
| SK hynix PC601 NVMe 256GB                             | 1         | 1%      |
| SK hynix HFM512GD3JX016N 512GB                        | 1         | 1%      |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 1         | 1%      |
| Shenzhen Longsys Lexar SSD NM710 2TB                  | 1         | 1%      |
| Seagate ST9500325AS 500GB                             | 1         | 1%      |
| Seagate ST9320423AS 320GB                             | 1         | 1%      |
| Seagate ST500LM000-1EJ162-SSHD 500GB                  | 1         | 1%      |
| Seagate ST4000LM024-2AN17V 4TB                        | 1         | 1%      |
| Seagate ST2000DM008-2FR102 2TB                        | 1         | 1%      |
| Seagate ST2000DM006-2DM164 2TB                        | 1         | 1%      |
| Seagate ST2000DL003-9VT166 2TB                        | 1         | 1%      |
| Seagate ST1000LM048-2E7172 1TB                        | 1         | 1%      |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 12     | 38.46%  |
| Seagate             | 10        | 12     | 38.46%  |
| Toshiba             | 3         | 4      | 11.54%  |
| Unknown             | 1         | 1      | 3.85%   |
| Samsung Electronics | 1         | 1      | 3.85%   |
| Hitachi             | 1         | 1      | 3.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 11     | 25%     |
| Kingston            | 6         | 6      | 21.43%  |
| SanDisk             | 4         | 6      | 14.29%  |
| Micron Technology   | 3         | 5      | 10.71%  |
| Crucial             | 2         | 4      | 7.14%   |
| WDC                 | 1         | 2      | 3.57%   |
| Netac               | 1         | 1      | 3.57%   |
| KingDian            | 1         | 3      | 3.57%   |
| Hewlett-Packard     | 1         | 1      | 3.57%   |
| Fanxiang            | 1         | 1      | 3.57%   |
| Corsair             | 1         | 1      | 3.57%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 32        | 41     | 40.51%  |
| SSD     | 21        | 41     | 26.58%  |
| HDD     | 20        | 31     | 25.32%  |
| MMC     | 4         | 4      | 5.06%   |
| Unknown | 2         | 2      | 2.53%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 33        | 69     | 45.21%  |
| NVMe | 32        | 41     | 43.84%  |
| SAS  | 4         | 5      | 5.48%   |
| MMC  | 4         | 4      | 5.48%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 20        | 42     | 45.45%  |
| 0.51-1.0   | 13        | 14     | 29.55%  |
| 1.01-2.0   | 6         | 8      | 13.64%  |
| 3.01-4.0   | 2         | 5      | 4.55%   |
| 2.01-3.0   | 1         | 1      | 2.27%   |
| 10.01-20.0 | 1         | 1      | 2.27%   |
| 4.01-10.0  | 1         | 1      | 2.27%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 20        | 37.04%  |
| 1001-2000      | 18        | 33.33%  |
| 251-500        | 7         | 12.96%  |
| 501-1000       | 5         | 9.26%   |
| 2001-3000      | 2         | 3.7%    |
| 101-250        | 2         | 3.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 19        | 34.55%  |
| 101-250        | 10        | 18.18%  |
| 51-100         | 8         | 14.55%  |
| 251-500        | 7         | 12.73%  |
| 501-1000       | 5         | 9.09%   |
| More than 3000 | 3         | 5.45%   |
| 2001-3000      | 2         | 3.64%   |
| 1001-2000      | 1         | 1.82%   |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 53        | 119    | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 32        | 41.03%  |
| AMD                          | 12        | 15.38%  |
| Samsung Electronics          | 8         | 10.26%  |
| SanDisk                      | 4         | 5.13%   |
| Phison Electronics           | 4         | 5.13%   |
| Kingston Technology Company  | 4         | 5.13%   |
| Micron/Crucial Technology    | 3         | 3.85%   |
| Toshiba America Info Systems | 2         | 2.56%   |
| SK hynix                     | 2         | 2.56%   |
| Biwin Storage Technology     | 2         | 2.56%   |
| Silicon Motion               | 1         | 1.28%   |
| Shenzhen Longsys Electronics | 1         | 1.28%   |
| Micron Technology            | 1         | 1.28%   |
| INNOGRIT                     | 1         | 1.28%   |
| ADATA Technology             | 1         | 1.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 9         | 10.34%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 5.75%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 4.6%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 4.6%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 4.6%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 3.45%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 3         | 3.45%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 3.45%   |
| AMD 500 Series Chipset SATA Controller                                         | 3         | 3.45%   |
| Phison PS5013 E13 NVMe Controller                                              | 2         | 2.3%    |
| Kingston Company NVMe Controller                                               | 2         | 2.3%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 2.3%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2         | 2.3%    |
| Biwin Storage Non-Volatile memory controller                                   | 2         | 2.3%    |
| AMD 400 Series Chipset SATA Controller                                         | 2         | 2.3%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 1.15%   |
| Toshiba America Info Systems NVMe Controller                                   | 1         | 1.15%   |
| SK hynix Non-Volatile memory controller                                        | 1         | 1.15%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 1         | 1.15%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1         | 1.15%   |
| Shenzhen Longsys Non-Volatile memory controller                                | 1         | 1.15%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 1.15%   |
| SanDisk WD Black SN770 NVMe SSD                                                | 1         | 1.15%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 1.15%   |
| SanDisk Non-Volatile memory controller                                         | 1         | 1.15%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.15%   |
| Phison PS5019-E19 PCIe4 NVMe Controller (DRAM-less)                            | 1         | 1.15%   |
| Phison E12 NVMe Controller                                                     | 1         | 1.15%   |
| Micron 2200S NVMe SSD                                                          | 1         | 1.15%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 1.15%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                             | 1         | 1.15%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.15%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 1         | 1.15%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 1.15%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 1         | 1.15%   |
| Intel SSD 665p Series                                                          | 1         | 1.15%   |
| Intel SSD 600P Series                                                          | 1         | 1.15%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.15%   |
| Intel Non-Volatile memory controller                                           | 1         | 1.15%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1         | 1.15%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 37        | 48.05%  |
| NVMe | 32        | 41.56%  |
| RAID | 6         | 7.79%   |
| IDE  | 2         | 2.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 33        | 62.26%  |
| AMD    | 20        | 37.74%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| AMD Ryzen 7 6800U with Radeon Graphics  | 4         | 7.41%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz      | 2         | 3.7%    |
| AMD Ryzen 9 5900X 12-Core Processor     | 2         | 3.7%    |
| AMD Ryzen 7 5800U with Radeon Graphics  | 2         | 3.7%    |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz     | 1         | 1.85%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 1         | 1.85%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 1.85%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 1         | 1.85%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 1         | 1.85%   |
| Intel Core i7-4770 CPU @ 3.40GHz        | 1         | 1.85%   |
| Intel Core i7-3610QM CPU @ 2.30GHz      | 1         | 1.85%   |
| Intel Core i7-10875H CPU @ 2.30GHz      | 1         | 1.85%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 1         | 1.85%   |
| Intel Core i5-7500 CPU @ 3.40GHz        | 1         | 1.85%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz      | 1         | 1.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 1         | 1.85%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 1         | 1.85%   |
| Intel Core i5-4570 CPU @ 3.20GHz        | 1         | 1.85%   |
| Intel Core i5-4210H CPU @ 2.90GHz       | 1         | 1.85%   |
| Intel Core i5-3570 CPU @ 3.40GHz        | 1         | 1.85%   |
| Intel Core i5-2500K CPU @ 3.30GHz       | 1         | 1.85%   |
| Intel Core i5-2500 CPU @ 3.30GHz        | 1         | 1.85%   |
| Intel Core i5-10400F CPU @ 2.90GHz      | 1         | 1.85%   |
| Intel Core i3-5005U CPU @ 2.00GHz       | 1         | 1.85%   |
| Intel Core i3-4160 CPU @ 3.60GHz        | 1         | 1.85%   |
| Intel Core i3-10100F CPU @ 3.60GHz      | 1         | 1.85%   |
| Intel Core i3-10100 CPU @ 3.60GHz       | 1         | 1.85%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz   | 1         | 1.85%   |
| Intel Celeron CPU N3350 @ 1.10GHz       | 1         | 1.85%   |
| Intel Atom x7-Z8700 CPU @ 1.60GHz       | 1         | 1.85%   |
| Intel 13th Gen Core i9-13900K           | 1         | 1.85%   |
| Intel 12th Gen Core i7-1255U            | 1         | 1.85%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz | 1         | 1.85%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 1         | 1.85%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 1         | 1.85%   |
| AMD Ryzen 9 7950X3D 16-Core Processor   | 1         | 1.85%   |
| AMD Ryzen 9 5950X 16-Core Processor     | 1         | 1.85%   |
| AMD Ryzen 9 5900HX with Radeon Graphics | 1         | 1.85%   |
| AMD Ryzen 9 5900HS with Radeon Graphics | 1         | 1.85%   |
| AMD Ryzen 7 7700X 8-Core Processor      | 1         | 1.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 12        | 22.22%  |
| AMD Ryzen 7       | 10        | 18.52%  |
| Intel Core i7     | 8         | 14.81%  |
| AMD Ryzen 9       | 6         | 11.11%  |
| Other             | 5         | 9.26%   |
| Intel Core i3     | 4         | 7.41%   |
| AMD Ryzen 5       | 3         | 5.56%   |
| Intel Xeon        | 1         | 1.85%   |
| Intel Core 2 Quad | 1         | 1.85%   |
| Intel Celeron     | 1         | 1.85%   |
| Intel Atom        | 1         | 1.85%   |
| AMD Ryzen 5 PRO   | 1         | 1.85%   |
| AMD A10           | 1         | 1.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 19        | 35.19%  |
| 8      | 13        | 24.07%  |
| 2      | 9         | 16.67%  |
| 6      | 7         | 12.96%  |
| 16     | 2         | 3.7%    |
| 12     | 2         | 3.7%    |
| 24     | 1         | 1.85%   |
| 10     | 1         | 1.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 53        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 41        | 77.36%  |
| 1      | 12        | 22.64%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 53        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 53        | 100%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Zen 3       | 10        | 18.87%  |
| Unknown     | 9         | 16.98%  |
| KabyLake    | 6         | 11.32%  |
| Haswell     | 5         | 9.43%   |
| CometLake   | 5         | 9.43%   |
| Skylake     | 4         | 7.55%   |
| Zen         | 2         | 3.77%   |
| TigerLake   | 2         | 3.77%   |
| SandyBridge | 2         | 3.77%   |
| IvyBridge   | 2         | 3.77%   |
| Zen+        | 1         | 1.89%   |
| Silvermont  | 1         | 1.89%   |
| Piledriver  | 1         | 1.89%   |
| Penryn      | 1         | 1.89%   |
| Goldmont    | 1         | 1.89%   |
| Broadwell   | 1         | 1.89%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| AMD    | 24        | 34.29%  |
| Nvidia | 23        | 32.86%  |
| Intel  | 23        | 32.86%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Rembrandt [Radeon 680M]                                                 | 4         | 5.63%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4         | 5.63%   |
| Intel HD Graphics 530                                                       | 3         | 4.23%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                             | 2         | 2.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 2.82%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 2         | 2.82%   |
| Intel HD Graphics 630                                                       | 2         | 2.82%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX]                                    | 2         | 2.82%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2         | 2.82%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2         | 2.82%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1         | 1.41%   |
| Nvidia TU117 [GeForce GTX 1630]                                             | 1         | 1.41%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 1         | 1.41%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1         | 1.41%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                     | 1         | 1.41%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 1         | 1.41%   |
| Nvidia TU106 [GeForce GTX 1650]                                             | 1         | 1.41%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                       | 1         | 1.41%   |
| Nvidia GP107M [GeForce MX350]                                               | 1         | 1.41%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 1         | 1.41%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1         | 1.41%   |
| Nvidia GM108M [GeForce MX130]                                               | 1         | 1.41%   |
| Nvidia GM108M [GeForce 940M]                                                | 1         | 1.41%   |
| Nvidia GM108M [GeForce 940MX]                                               | 1         | 1.41%   |
| Nvidia GM107M [GeForce GTX 960M]                                            | 1         | 1.41%   |
| Nvidia GM107M [GeForce GTX 950M]                                            | 1         | 1.41%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                           | 1         | 1.41%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 1         | 1.41%   |
| Nvidia GA106 [RTX A2000]                                                    | 1         | 1.41%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 1         | 1.41%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 1         | 1.41%   |
| Intel UHD Graphics 620                                                      | 1         | 1.41%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 1         | 1.41%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                   | 1         | 1.41%   |
| Intel HD Graphics 620                                                       | 1         | 1.41%   |
| Intel HD Graphics 5500                                                      | 1         | 1.41%   |
| Intel HD Graphics 500                                                       | 1         | 1.41%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1         | 1.41%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 1         | 1.41%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 1         | 1.41%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 20        | 37.04%  |
| 1 x Nvidia     | 10        | 18.52%  |
| Intel + Nvidia | 10        | 18.52%  |
| 1 x Intel      | 9         | 16.67%  |
| AMD + Nvidia   | 3         | 5.56%   |
| Other          | 1         | 1.85%   |
| Intel + AMD    | 1         | 1.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 31        | 58.49%  |
| Proprietary | 22        | 41.51%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 50        | 94.34%  |
| 3.01-4.0   | 2         | 3.77%   |
| 8.01-16.0  | 1         | 1.89%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 10        | 18.52%  |
| BOE                 | 7         | 12.96%  |
| Chimei Innolux      | 5         | 9.26%   |
| LG Display          | 4         | 7.41%   |
| BenQ                | 3         | 5.56%   |
| AU Optronics        | 3         | 5.56%   |
| Toshiba             | 2         | 3.7%    |
| Sony                | 2         | 3.7%    |
| Sharp               | 2         | 3.7%    |
| Goldstar            | 2         | 3.7%    |
| Vizio               | 1         | 1.85%   |
| TMX                 | 1         | 1.85%   |
| SANYO               | 1         | 1.85%   |
| Panasonic           | 1         | 1.85%   |
| Onkyo               | 1         | 1.85%   |
| MSI                 | 1         | 1.85%   |
| Insignia            | 1         | 1.85%   |
| Hewlett-Packard     | 1         | 1.85%   |
| Fujitsu Siemens     | 1         | 1.85%   |
| Dell                | 1         | 1.85%   |
| AYANEO              | 1         | 1.85%   |
| AYA                 | 1         | 1.85%   |
| ASUSTek Computer    | 1         | 1.85%   |
| Acer                | 1         | 1.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| BOE FLQ8423-24L0 BOE1003 1600x2560 113x181mm 8.4-inch                | 2         | 3.7%    |
| Vizio D40f-G9 VIZ1027 1920x1080 930x520mm 41.9-inch                  | 1         | 1.85%   |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                     | 1         | 1.85%   |
| Toshiba TV TSB002F 3840x2160 1095x616mm 49.5-inch                    | 1         | 1.85%   |
| TMX TL140BDXP02-0 TMX1400 2560x1440 310x174mm 14.0-inch              | 1         | 1.85%   |
| Sony TV SNYEE01 1920x1080                                            | 1         | 1.85%   |
| Sony TV SNY3002 1920x1080 1018x573mm 46.0-inch                       | 1         | 1.85%   |
| Sharp LQ173M1JW02 SHP14DB 1920x1080 382x215mm 17.3-inch              | 1         | 1.85%   |
| Sharp HDMI SHP0FE8 1920x1080 1152x648mm 52.0-inch                    | 1         | 1.85%   |
| SANYO TV SAN0206 1920x1080 886x498mm 40.0-inch                       | 1         | 1.85%   |
| Samsung Electronics SyncMaster SAM030F 1680x1050 474x296mm 22.0-inch | 1         | 1.85%   |
| Samsung Electronics S24R35xFZ SAM71A8 1920x1080 527x296mm 23.8-inch  | 1         | 1.85%   |
| Samsung Electronics S24C650 SAM09E8 1920x1080 521x293mm 23.5-inch    | 1         | 1.85%   |
| Samsung Electronics QBQ95 SAM7229 3840x2160 1872x1053mm 84.6-inch    | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SAM065D 1920x1080                    | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SAM020B 1920x540                     | 1         | 1.85%   |
| Samsung Electronics LC49G95T SAM7053 2560x1440 1193x336mm 48.8-inch  | 1         | 1.85%   |
| Samsung Electronics LC27T55 SAM701F 1920x1080 609x349mm 27.6-inch    | 1         | 1.85%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 1         | 1.85%   |
| Panasonic VVX14T092N00 MEI96A2 2256x1504 285x190mm 13.5-inch         | 1         | 1.85%   |
| Onkyo AV Receiver ONK1150 3840x2160 1872x1053mm 84.6-inch            | 1         | 1.85%   |
| MSI MAG301CR2 MSI3CB4 2560x1080 690x291mm 29.5-inch                  | 1         | 1.85%   |
| LG Display LCD Monitor LGD071E 1920x1080 344x194mm 15.5-inch         | 1         | 1.85%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch         | 1         | 1.85%   |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch         | 1         | 1.85%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch          | 1         | 1.85%   |
| Insignia NS32DD200NA14 BBY0032 1680x1050 700x390mm 31.5-inch         | 1         | 1.85%   |
| Hewlett-Packard M24fwa FHD HPN372F 1920x1080 527x296mm 23.8-inch     | 1         | 1.85%   |
| Goldstar TV GSMC0A0 3840x2160                                        | 1         | 1.85%   |
| Goldstar M237WDP GSM5779 1920x1080 598x336mm 27.0-inch               | 1         | 1.85%   |
| Fujitsu Siemens B22T-7 LED PG FUS082A 1920x1080 477x268mm 21.5-inch  | 1         | 1.85%   |
| Dell IN1910N DELA04C 1366x768 410x230mm 18.5-inch                    | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN176E 1920x1080 381x214mm 17.2-inch     | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch     | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN1540 2560x1440 344x193mm 15.5-inch     | 1         | 1.85%   |
| BOE LCD Monitor BOE9002 800x1280                                     | 1         | 1.85%   |
| BOE LCD Monitor BOE9001 1200x1920                                    | 1         | 1.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 24        | 47.06%  |
| 3840x2160 (4K)     | 5         | 9.8%    |
| 2560x1440 (QHD)    | 5         | 9.8%    |
| 1366x768 (WXGA)    | 5         | 9.8%    |
| 1200x1920          | 3         | 5.88%   |
| 1920x540           | 2         | 3.92%   |
| 1600x2560          | 2         | 3.92%   |
| 800x1280           | 1         | 1.96%   |
| 3840x1080          | 1         | 1.96%   |
| 2560x1080          | 1         | 1.96%   |
| 1920x1200 (WUXGA)  | 1         | 1.96%   |
| 1680x1050 (WSXGA+) | 1         | 1.96%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 11        | 20.37%  |
| Unknown | 6         | 11.11%  |
| 27      | 4         | 7.41%   |
| 17      | 4         | 7.41%   |
| 84      | 3         | 5.56%   |
| 72      | 3         | 5.56%   |
| 23      | 3         | 5.56%   |
| 14      | 3         | 5.56%   |
| 48      | 2         | 3.7%    |
| 24      | 2         | 3.7%    |
| 8       | 2         | 3.7%    |
| 74      | 1         | 1.85%   |
| 52      | 1         | 1.85%   |
| 49      | 1         | 1.85%   |
| 46      | 1         | 1.85%   |
| 40      | 1         | 1.85%   |
| 29      | 1         | 1.85%   |
| 26      | 1         | 1.85%   |
| 22      | 1         | 1.85%   |
| 21      | 1         | 1.85%   |
| 18      | 1         | 1.85%   |
| 11      | 1         | 1.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 14        | 26.42%  |
| 501-600     | 9         | 16.98%  |
| 1501-2000   | 6         | 11.32%  |
| Unknown     | 6         | 11.32%  |
| 1001-1500   | 5         | 9.43%   |
| 351-400     | 4         | 7.55%   |
| 401-500     | 3         | 5.66%   |
| 601-700     | 2         | 3.77%   |
| 101-200     | 2         | 3.77%   |
| 801-900     | 1         | 1.89%   |
| 201-300     | 1         | 1.89%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 38        | 73.08%  |
| 0.62  | 6         | 11.54%  |
| 16/10 | 4         | 7.69%   |
| 32/9  | 2         | 3.85%   |
| 21/9  | 1         | 1.92%   |
| 1.96  | 1         | 1.92%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 11        | 21.15%  |
| More than 1000 | 8         | 15.38%  |
| 301-350        | 6         | 11.54%  |
| 201-250        | 6         | 11.54%  |
| Unknown        | 6         | 11.54%  |
| 121-130        | 4         | 7.69%   |
| 501-1000       | 4         | 7.69%   |
| 81-90          | 3         | 5.77%   |
| 1-40           | 2         | 3.85%   |
| 51-60          | 1         | 1.92%   |
| 141-150        | 1         | 1.92%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 17        | 32.08%  |
| 121-160       | 12        | 22.64%  |
| 1-50          | 6         | 11.32%  |
| Unknown       | 6         | 11.32%  |
| 101-120       | 5         | 9.43%   |
| 161-240       | 4         | 7.55%   |
| More than 240 | 3         | 5.66%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 47        | 87.04%  |
| 2     | 6         | 11.11%  |
| 0     | 1         | 1.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 28        | 33.33%  |
| Intel                           | 27        | 32.14%  |
| Qualcomm Atheros                | 9         | 10.71%  |
| MediaTek                        | 8         | 9.52%   |
| Broadcom                        | 3         | 3.57%   |
| TP-Link                         | 2         | 2.38%   |
| Marvell Technology Group        | 2         | 2.38%   |
| Ralink Technology               | 1         | 1.19%   |
| Ralink                          | 1         | 1.19%   |
| Qualcomm Atheros Communications | 1         | 1.19%   |
| OnePlus Technology (Shenzhen)   | 1         | 1.19%   |
| Broadcom Limited                | 1         | 1.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                | Computers | Percent |
|--------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                    | 17        | 17.53%  |
| Realtek RTL8125 2.5GbE Controller                                                    | 7         | 7.22%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 6         | 6.19%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                              | 5         | 5.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                           | 3         | 3.09%   |
| Intel Wi-Fi 6 AX200                                                                  | 3         | 3.09%   |
| Intel Ethernet Connection I217-LM                                                    | 3         | 3.09%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                   | 2         | 2.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                             | 2         | 2.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                           | 2         | 2.06%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                        | 2         | 2.06%   |
| Intel Wireless 3165                                                                  | 2         | 2.06%   |
| Intel Wi-Fi 6 AX201                                                                  | 2         | 2.06%   |
| Intel I211 Gigabit Network Connection                                                | 2         | 2.06%   |
| Intel Ethernet Controller I225-V                                                     | 2         | 2.06%   |
| Intel Comet Lake PCH CNVi WiFi                                                       | 2         | 2.06%   |
| TP-Link Archer T4U ver.3                                                             | 1         | 1.03%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                               | 1         | 1.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                             | 1         | 1.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 1         | 1.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                      | 1         | 1.03%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                               | 1         | 1.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 1         | 1.03%   |
| Realtek RTL8187 Wireless Adapter                                                     | 1         | 1.03%   |
| Realtek PCIe GbE Family Controller                                                   | 1         | 1.03%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                    | 1         | 1.03%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                            | 1         | 1.03%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                            | 1         | 1.03%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                            | 1         | 1.03%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1         | 1.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 1         | 1.03%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                        | 1         | 1.03%   |
| OnePlus (Shenzhen) SM8150-MTP _SN:5A38C392                                           | 1         | 1.03%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                        | 1         | 1.03%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                                    | 1         | 1.03%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                              | 1         | 1.03%   |
| Intel Wireless-AC 9260                                                               | 1         | 1.03%   |
| Intel Wireless 7265                                                                  | 1         | 1.03%   |
| Intel Tiger Lake PCH CNVi WiFi                                                       | 1         | 1.03%   |
| Intel Ethernet Connection (5) I219-LM                                                | 1         | 1.03%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 21        | 42.86%  |
| MediaTek                        | 8         | 16.33%  |
| Qualcomm Atheros                | 6         | 12.24%  |
| Realtek Semiconductor           | 5         | 10.2%   |
| TP-Link                         | 2         | 4.08%   |
| Broadcom                        | 2         | 4.08%   |
| Ralink Technology               | 1         | 2.04%   |
| Ralink                          | 1         | 2.04%   |
| Qualcomm Atheros Communications | 1         | 2.04%   |
| Marvell Technology Group        | 1         | 2.04%   |
| Broadcom Limited                | 1         | 2.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Computers | Percent |
|--------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 6         | 11.32%  |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                              | 5         | 9.43%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                           | 3         | 5.66%   |
| Intel Wi-Fi 6 AX200                                                                  | 3         | 5.66%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                   | 2         | 3.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                           | 2         | 3.77%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                        | 2         | 3.77%   |
| Intel Wireless 3165                                                                  | 2         | 3.77%   |
| Intel Wi-Fi 6 AX201                                                                  | 2         | 3.77%   |
| Intel Comet Lake PCH CNVi WiFi                                                       | 2         | 3.77%   |
| TP-Link Archer T4U ver.3                                                             | 1         | 1.89%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                               | 1         | 1.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                             | 1         | 1.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 1         | 1.89%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                      | 1         | 1.89%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                               | 1         | 1.89%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 1         | 1.89%   |
| Realtek RTL8187 Wireless Adapter                                                     | 1         | 1.89%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                    | 1         | 1.89%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                            | 1         | 1.89%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1         | 1.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 1         | 1.89%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                        | 1         | 1.89%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                                    | 1         | 1.89%   |
| Intel Wireless-AC 9260                                                               | 1         | 1.89%   |
| Intel Wireless 7265                                                                  | 1         | 1.89%   |
| Intel Tiger Lake PCH CNVi WiFi                                                       | 1         | 1.89%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 1         | 1.89%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                      | 1         | 1.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 1         | 1.89%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                     | 1         | 1.89%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                           | 1         | 1.89%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                   | 1         | 1.89%   |
| Broadcom BCM4356 802.11ac Wireless Network Adapter                                   | 1         | 1.89%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 26        | 61.9%   |
| Intel                    | 11        | 26.19%  |
| Qualcomm Atheros         | 3         | 7.14%   |
| Marvell Technology Group | 1         | 2.38%   |
| Broadcom                 | 1         | 2.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17        | 39.53%  |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 16.28%  |
| Intel Ethernet Connection I217-LM                                 | 3         | 6.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 4.65%   |
| Intel I211 Gigabit Network Connection                             | 2         | 4.65%   |
| Intel Ethernet Controller I225-V                                  | 2         | 4.65%   |
| Realtek PCIe GbE Family Controller                                | 1         | 2.33%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 2.33%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 2.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 2.33%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 2.33%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 2.33%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 2.33%   |
| Intel Ethernet Connection (12) I219-V                             | 1         | 2.33%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 2.33%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1         | 2.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 44        | 51.16%  |
| Ethernet | 41        | 47.67%  |
| Unknown  | 1         | 1.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 38        | 67.86%  |
| Ethernet | 18        | 32.14%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 28        | 52.83%  |
| 1     | 23        | 43.4%   |
| 3     | 2         | 3.77%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 38        | 70.37%  |
| Yes  | 16        | 29.63%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 20        | 47.62%  |
| MediaTek                        | 6         | 14.29%  |
| Cambridge Silicon Radio         | 5         | 11.9%   |
| Lite-On Technology              | 3         | 7.14%   |
| IMC Networks                    | 3         | 7.14%   |
| Realtek Semiconductor           | 1         | 2.38%   |
| Qualcomm Atheros Communications | 1         | 2.38%   |
| Foxconn / Hon Hai               | 1         | 2.38%   |
| ASUSTek Computer                | 1         | 2.38%   |
| Apple                           | 1         | 2.38%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| MediaTek Wireless_Device                            | 6         | 13.95%  |
| Intel AX210 Bluetooth                               | 6         | 13.95%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5         | 11.63%  |
| Intel Bluetooth wireless interface                  | 4         | 9.3%    |
| Intel AX201 Bluetooth                               | 4         | 9.3%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 4.65%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 4.65%   |
| Intel AX200 Bluetooth                               | 2         | 4.65%   |
| IMC Networks Bluetooth Radio                        | 2         | 4.65%   |
| Realtek Bluetooth Radio                             | 1         | 2.33%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 2.33%   |
| Lite-On Bluetooth Device                            | 1         | 2.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 2.33%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.33%   |
| Intel Bluetooth Device                              | 1         | 2.33%   |
| IMC Networks Wireless_Device                        | 1         | 2.33%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 2.33%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1         | 2.33%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 32        | 36.78%  |
| AMD                      | 27        | 31.03%  |
| Nvidia                   | 17        | 19.54%  |
| Logitech                 | 2         | 2.3%    |
| SteelSeries ApS          | 1         | 1.15%   |
| Sony                     | 1         | 1.15%   |
| Razer USA                | 1         | 1.15%   |
| Micro Star International | 1         | 1.15%   |
| Kingston Technology      | 1         | 1.15%   |
| Hewlett-Packard          | 1         | 1.15%   |
| Focusrite-Novation       | 1         | 1.15%   |
| ASUSTek Computer         | 1         | 1.15%   |
| Astro Gaming             | 1         | 1.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                              | 13        | 11.82%  |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 5         | 4.55%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 5         | 4.55%   |
| AMD Rembrandt Radeon High Definition Audio Controller               | 5         | 4.55%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                             | 5         | 4.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 4         | 3.64%   |
| Intel Sunrise Point-LP HD Audio                                     | 4         | 3.64%   |
| AMD Starship/Matisse HD Audio Controller                            | 4         | 3.64%   |
| Nvidia TU106 High Definition Audio Controller                       | 3         | 2.73%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 3         | 2.73%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 3         | 2.73%   |
| Nvidia TU116 High Definition Audio Controller                       | 2         | 1.82%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller      | 2         | 1.82%   |
| Nvidia GA106 High Definition Audio Controller                       | 2         | 1.82%   |
| Nvidia GA104 High Definition Audio Controller                       | 2         | 1.82%   |
| Nvidia GA102 High Definition Audio Controller                       | 2         | 1.82%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 2         | 1.82%   |
| Intel Comet Lake PCH-V cAVS                                         | 2         | 1.82%   |
| Intel Comet Lake PCH cAVS                                           | 2         | 1.82%   |
| AMD Navi 31 [Radeon RX 7000 HDMI Audio]                             | 2         | 1.82%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]          | 2         | 1.82%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]        | 2         | 1.82%   |
| SteelSeries ApS SteelSeries Arctis 1 Wireless                       | 1         | 0.91%   |
| Sony DualSense wireless controller (PS5)                            | 1         | 0.91%   |
| Razer USA Razer Seiren Mini                                         | 1         | 0.91%   |
| Nvidia TU104 HD Audio Controller                                    | 1         | 0.91%   |
| Nvidia GP107GL High Definition Audio Controller                     | 1         | 0.91%   |
| Nvidia GP104 High Definition Audio Controller                       | 1         | 0.91%   |
| Nvidia GF108 High Definition Audio Controller                       | 1         | 0.91%   |
| Micro Star International USB Audio                                  | 1         | 0.91%   |
| Logitech Logitech USB Microphone                                    | 1         | 0.91%   |
| Logitech G432 Gaming Headset                                        | 1         | 0.91%   |
| Kingston Technology HyperX QuadCast                                 | 1         | 0.91%   |
| Intel Wildcat Point-LP High Definition Audio Controller             | 1         | 0.91%   |
| Intel Tiger Lake-H HD Audio Controller                              | 1         | 0.91%   |
| Intel Smart Sound Technology (SST) Audio Controller                 | 1         | 0.91%   |
| Intel NM10/ICH7 Family High Definition Audio Controller             | 1         | 0.91%   |
| Intel CM238 HD Audio Controller                                     | 1         | 0.91%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster   | 1         | 0.91%   |
| Intel Cannon Lake PCH cAVS                                          | 1         | 0.91%   |

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


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 6         | 30%     |
| Microdia                      | 4         | 20%     |
| IMC Networks                  | 3         | 15%     |
| Quanta                        | 2         | 10%     |
| Acer                          | 2         | 10%     |
| Sunplus Innovation Technology | 1         | 5%      |
| Logitech                      | 1         | 5%      |
| Apple                         | 1         | 5%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| IMC Networks Integrated Camera    | 2         | 10%     |
| Acer Lenovo EasyCamera            | 2         | 10%     |
| Sunplus HD WebCam                 | 1         | 5%      |
| Quanta HP HD Camera               | 1         | 5%      |
| Quanta HD User Facing             | 1         | 5%      |
| Microdia Webcam Vitade AF         | 1         | 5%      |
| Microdia USB Camera               | 1         | 5%      |
| Microdia Integrated_Webcam_FHD    | 1         | 5%      |
| Microdia HP Webcam                | 1         | 5%      |
| Logitech Webcam C200              | 1         | 5%      |
| IMC Networks USB2.0 HD UVC WebCam | 1         | 5%      |
| Chicony USB2.0 FHD Camera         | 1         | 5%      |
| Chicony USB2.0 0.3M UVC WebCam    | 1         | 5%      |
| Chicony Integrated IR Camera      | 1         | 5%      |
| Chicony Integrated Camera         | 1         | 5%      |
| Chicony HP Truevision HD          | 1         | 5%      |
| Chicony EasyCamera                | 1         | 5%      |
| Apple iPhone 5/5C/5S/6/SE/7/8/X   | 1         | 5%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor    | Computers | Percent |
|-----------|-----------|---------|
| Synaptics | 1         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 100%    |

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


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 44        | 83.02%  |
| 1     | 9         | 16.98%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Multimedia controller | 3         | 33.33%  |
| Graphics card         | 2         | 22.22%  |
| Storage/nvme          | 1         | 11.11%  |
| Network               | 1         | 11.11%  |
| Net/wireless          | 1         | 11.11%  |
| Fingerprint reader    | 1         | 11.11%  |

