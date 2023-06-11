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

Total: 62

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| ChimeraOS 39 | 15        | 33.33%  |
| ChimeraOS 41 | 11        | 24.44%  |
| ChimeraOS 42 | 7         | 15.56%  |
| ChimeraOS 38 | 6         | 13.33%  |
| ChimeraOS 37 | 4         | 8.89%   |
| ChimeraOS 43 | 1         | 2.22%   |
| ChimeraOS 35 | 1         | 2.22%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| ChimeraOS | 43        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version        | Computers | Percent |
|----------------|-----------|---------|
| 6.1.11-arch1-1 | 15        | 33.33%  |
| 6.1.21-1-lts   | 11        | 24.44%  |
| 6.1.27-1-lts   | 7         | 15.56%  |
| 6.1.1-arch1-1  | 6         | 13.33%  |
| 6.0.8-arch1-1  | 4         | 8.89%   |
| 6.3.1-arch2-1  | 1         | 2.22%   |
| 5.19.6-arch1-1 | 1         | 2.22%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1.11  | 15        | 33.33%  |
| 6.1.21  | 11        | 24.44%  |
| 6.1.27  | 7         | 15.56%  |
| 6.1.1   | 6         | 13.33%  |
| 6.0.8   | 4         | 8.89%   |
| 6.3.1   | 1         | 2.22%   |
| 5.19.6  | 1         | 2.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 38        | 86.36%  |
| 6.0     | 4         | 9.09%   |
| 6.3     | 1         | 2.27%   |
| 5.19    | 1         | 2.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 43        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GNOME   | 42        | 97.67%  |
| steamos | 1         | 2.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 37        | 86.05%  |
| X11     | 6         | 13.95%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 43        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 39        | 90.7%   |
| pt_BR | 1         | 2.33%   |
| it_IT | 1         | 2.33%   |
| es_ES | 1         | 2.33%   |
| de_DE | 1         | 2.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 43        | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 43        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 43        | 100%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 43        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 43        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| ASUSTek Computer       | 9         | 20.93%  |
| Gigabyte Technology    | 6         | 13.95%  |
| Lenovo                 | 5         | 11.63%  |
| MSI                    | 4         | 9.3%    |
| Hewlett-Packard        | 3         | 6.98%   |
| Acer                   | 3         | 6.98%   |
| ONE-NETBOOK TECHNOLOGY | 2         | 4.65%   |
| ONE-NETBOOK            | 2         | 4.65%   |
| Dell                   | 2         | 4.65%   |
| AYANEO                 | 2         | 4.65%   |
| Razer                  | 1         | 2.33%   |
| Microsoft              | 1         | 2.33%   |
| Micro Electronics      | 1         | 2.33%   |
| MACHINIST              | 1         | 2.33%   |
| Intel                  | 1         | 2.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| ONE-NETBOOK TECHNOLOGY ONE XPLAYER          | 2         | 4.65%   |
| ONE-NETBOOK ONEXPLAYER 2 ARP23              | 2         | 4.65%   |
| AYANEO 2                                    | 2         | 4.65%   |
| Razer Blade Pro 17 (Early 2020) - RZ09-0329 | 1         | 2.33%   |
| MSI MS-7D73                                 | 1         | 2.33%   |
| MSI MS-7C91                                 | 1         | 2.33%   |
| MSI GE75 Raider 10SF                        | 1         | 2.33%   |
| MSI CX62 6QD                                | 1         | 2.33%   |
| Microsoft Surface Book                      | 1         | 2.33%   |
| Micro MG-VCP17I-3070                        | 1         | 2.33%   |
| MACHINIST X99-RS9 V2.0                      | 1         | 2.33%   |
| Lenovo Y50-70 20378                         | 1         | 2.33%   |
| Lenovo ThinkCentre M70e 0832B1U             | 1         | 2.33%   |
| Lenovo Legion Y540-15IRH 81SX               | 1         | 2.33%   |
| Lenovo IdeaPad 700-15ISK 80RU               | 1         | 2.33%   |
| Lenovo IdeaPad 320-15IKB 80YH               | 1         | 2.33%   |
| Intel DB75EN AAG39650-400                   | 1         | 2.33%   |
| HP EliteDesk 800 G1 SFF                     | 1         | 2.33%   |
| HP EliteBook 850 G8 Notebook PC             | 1         | 2.33%   |
| HP 250 G4 Notebook PC                       | 1         | 2.33%   |
| Gigabyte X570S AORUS ELITE AX               | 1         | 2.33%   |
| Gigabyte X570 AORUS ELITE WIFI              | 1         | 2.33%   |
| Gigabyte X470 AORUS GAMING 5 WIFI           | 1         | 2.33%   |
| Gigabyte H77M-D3H                           | 1         | 2.33%   |
| Gigabyte H510M H                            | 1         | 2.33%   |
| Gigabyte B460M DS3H AC V2-Y1                | 1         | 2.33%   |
| Dell OptiPlex 7050                          | 1         | 2.33%   |
| Dell Inspiron 14 7420 2-in-1                | 1         | 2.33%   |
| ASUS TUF Gaming FX505DV_FX505DV             | 1         | 2.33%   |
| ASUS ROG Zephyrus G15 GA503QM_GA503QM       | 1         | 2.33%   |
| ASUS ROG STRIX B650E-I GAMING WIFI          | 1         | 2.33%   |
| ASUS ROG STRIX B550-F GAMING                | 1         | 2.33%   |
| ASUS ROG STRIX B460-I GAMING                | 1         | 2.33%   |
| ASUS PRIME B760-PLUS D4                     | 1         | 2.33%   |
| ASUS P8H61-MX R2.0                          | 1         | 2.33%   |
| ASUS K45VM                                  | 1         | 2.33%   |
| ASUS B150I PRO GAMING/WIFI/AURA             | 1         | 2.33%   |
| Acer Nitro AN515-51                         | 1         | 2.33%   |
| Acer Aspire Z3-705                          | 1         | 2.33%   |
| Acer Aspire A515-51G                        | 1         | 2.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| ASUS ROG                   | 4         | 9.3%    |
| ONE-NETBOOK TECHNOLOGY ONE | 2         | 4.65%   |
| ONE-NETBOOK ONEXPLAYER     | 2         | 4.65%   |
| Lenovo IdeaPad             | 2         | 4.65%   |
| AYANEO 2                   | 2         | 4.65%   |
| Acer Aspire                | 2         | 4.65%   |
| Razer Blade                | 1         | 2.33%   |
| MSI MS-7D73                | 1         | 2.33%   |
| MSI MS-7C91                | 1         | 2.33%   |
| MSI GE75                   | 1         | 2.33%   |
| MSI CX62                   | 1         | 2.33%   |
| Microsoft Surface          | 1         | 2.33%   |
| Micro MG-VCP17I-3070       | 1         | 2.33%   |
| MACHINIST X99-RS9          | 1         | 2.33%   |
| Lenovo Y50-70              | 1         | 2.33%   |
| Lenovo ThinkCentre         | 1         | 2.33%   |
| Lenovo Legion              | 1         | 2.33%   |
| Intel DB75EN               | 1         | 2.33%   |
| HP EliteDesk               | 1         | 2.33%   |
| HP EliteBook               | 1         | 2.33%   |
| HP 250                     | 1         | 2.33%   |
| Gigabyte X570S             | 1         | 2.33%   |
| Gigabyte X570              | 1         | 2.33%   |
| Gigabyte X470              | 1         | 2.33%   |
| Gigabyte H77M-D3H          | 1         | 2.33%   |
| Gigabyte H510M             | 1         | 2.33%   |
| Gigabyte B460M             | 1         | 2.33%   |
| Dell OptiPlex              | 1         | 2.33%   |
| Dell Inspiron              | 1         | 2.33%   |
| ASUS TUF                   | 1         | 2.33%   |
| ASUS PRIME                 | 1         | 2.33%   |
| ASUS P8H61-MX              | 1         | 2.33%   |
| ASUS K45VM                 | 1         | 2.33%   |
| ASUS B150I                 | 1         | 2.33%   |
| Acer Nitro                 | 1         | 2.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2022 | 9         | 20.93%  |
| 2021 | 6         | 13.95%  |
| 2020 | 6         | 13.95%  |
| 2017 | 4         | 9.3%    |
| 2012 | 4         | 9.3%    |
| 2019 | 3         | 6.98%   |
| 2016 | 3         | 6.98%   |
| 2015 | 3         | 6.98%   |
| 2023 | 2         | 4.65%   |
| 2018 | 1         | 2.33%   |
| 2013 | 1         | 2.33%   |
| 2010 | 1         | 2.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 18        | 41.86%  |
| Notebook    | 18        | 41.86%  |
| Tablet      | 5         | 11.63%  |
| Convertible | 1         | 2.33%   |
| All in one  | 1         | 2.33%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 43        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 43        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 13        | 30.23%  |
| 16.01-24.0  | 11        | 25.58%  |
| 8.01-16.0   | 7         | 16.28%  |
| 4.01-8.0    | 4         | 9.3%    |
| 24.01-32.0  | 4         | 9.3%    |
| 3.01-4.0    | 2         | 4.65%   |
| 64.01-256.0 | 2         | 4.65%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 19        | 42.22%  |
| 3.01-4.0   | 10        | 22.22%  |
| 1.01-2.0   | 10        | 22.22%  |
| 4.01-8.0   | 5         | 11.11%  |
| 16.01-24.0 | 1         | 2.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 2      | 17        | 38.64%  |
| 1      | 17        | 38.64%  |
| 3      | 7         | 15.91%  |
| 4      | 2         | 4.55%   |
| 7      | 1         | 2.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 39        | 90.7%   |
| Yes       | 4         | 9.3%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 35        | 81.4%   |
| No        | 8         | 18.6%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 88.37%  |
| No        | 5         | 11.63%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 79.07%  |
| No        | 9         | 20.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 20        | 46.51%  |
| UK           | 3         | 6.98%   |
| Brazil       | 3         | 6.98%   |
| Russia       | 2         | 4.65%   |
| Italy        | 2         | 4.65%   |
| Germany      | 2         | 4.65%   |
| Australia    | 2         | 4.65%   |
| Spain        | 1         | 2.33%   |
| Saudi Arabia | 1         | 2.33%   |
| Poland       | 1         | 2.33%   |
| Macao        | 1         | 2.33%   |
| Hungary      | 1         | 2.33%   |
| Estonia      | 1         | 2.33%   |
| Costa Rica   | 1         | 2.33%   |
| Canada       | 1         | 2.33%   |
| Belgium      | 1         | 2.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Yaroslavl                | 1         | 2.27%   |
| Wroclaw                  | 1         | 2.27%   |
| Watsonville              | 1         | 2.27%   |
| Virginia Beach           | 1         | 2.27%   |
| Tallinn                  | 1         | 2.27%   |
| Sumaré                  | 1         | 2.27%   |
| Steyning                 | 1         | 2.27%   |
| St Louis                 | 1         | 2.27%   |
| Seattle                  | 1         | 2.27%   |
| Santa Cruz das Palmeiras | 1         | 2.27%   |
| Sanford                  | 1         | 2.27%   |
| San José                | 1         | 2.27%   |
| Samara                   | 1         | 2.27%   |
| Saltillo                 | 1         | 2.27%   |
| Round Rock               | 1         | 2.27%   |
| Ridley Park              | 1         | 2.27%   |
| Racine                   | 1         | 2.27%   |
| Pittsburg                | 1         | 2.27%   |
| Philadelphia             | 1         | 2.27%   |
| Pennsauken               | 1         | 2.27%   |
| Newport News             | 1         | 2.27%   |
| New York                 | 1         | 2.27%   |
| Milan                    | 1         | 2.27%   |
| Melbourne                | 1         | 2.27%   |
| Macao                    | 1         | 2.27%   |
| Longueuil                | 1         | 2.27%   |
| Lewiston                 | 1         | 2.27%   |
| Jeddah                   | 1         | 2.27%   |
| Houston                  | 1         | 2.27%   |
| Hot Springs              | 1         | 2.27%   |
| Hixson                   | 1         | 2.27%   |
| Hamburg                  | 1         | 2.27%   |
| Carmignano               | 1         | 2.27%   |
| Budapest                 | 1         | 2.27%   |
| Brussels                 | 1         | 2.27%   |
| Brossard                 | 1         | 2.27%   |
| Bielefeld                | 1         | 2.27%   |
| Bellevue                 | 1         | 2.27%   |
| Belfast                  | 1         | 2.27%   |
| Beaverton                | 1         | 2.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 12        | 18     | 15%     |
| Seagate                      | 10        | 12     | 12.5%   |
| WDC                          | 9         | 11     | 11.25%  |
| Kingston                     | 8         | 8      | 10%     |
| Sandisk                      | 7         | 10     | 8.75%   |
| Toshiba                      | 5         | 5      | 6.25%   |
| Unknown                      | 4         | 4      | 5%      |
| Micron Technology            | 4         | 5      | 5%      |
| Phison Electronics           | 3         | 3      | 3.75%   |
| Intel                        | 3         | 4      | 3.75%   |
| Micron/Crucial Technology    | 2         | 2      | 2.5%    |
| Crucial                      | 2         | 3      | 2.5%    |
| Silicon Motion               | 1         | 1      | 1.25%   |
| Shenzhen Longsys Electronics | 1         | 1      | 1.25%   |
| Netac                        | 1         | 1      | 1.25%   |
| Kingston Technology Company  | 1         | 1      | 1.25%   |
| KingFast                     | 1         | 1      | 1.25%   |
| KingDian                     | 1         | 2      | 1.25%   |
| Hewlett-Packard              | 1         | 1      | 1.25%   |
| Fanxiang                     | 1         | 1      | 1.25%   |
| Corsair                      | 1         | 1      | 1.25%   |
| Biwin Storage Technology     | 1         | 1      | 1.25%   |
| ADATA Technology             | 1         | 2      | 1.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 4         | 4.6%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 3         | 3.45%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 2         | 2.3%    |
| Kingston SA400S37120G 120GB SSD                     | 2         | 2.3%    |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1         | 1.15%   |
| WDC WDBNCE5000PNC 500GB SSD                         | 1         | 1.15%   |
| WDC WD7500BPVT-80HXZT3 752GB                        | 1         | 1.15%   |
| WDC WD5000AVDS-63U7B1 500GB                         | 1         | 1.15%   |
| WDC WD40EZRX-00SPEB0 4TB                            | 1         | 1.15%   |
| WDC WD20SPZX-08UA7 2TB                              | 1         | 1.15%   |
| WDC WD20EARX-00PASB0 2TB                            | 1         | 1.15%   |
| WDC WD201KFGX-68BKJN0 20TB                          | 1         | 1.15%   |
| WDC WD10SPCX-24HWST1 1TB                            | 1         | 1.15%   |
| WDC WD10JPLX-00MBPT0 1TB                            | 1         | 1.15%   |
| Unknown SD/MMC/MS PRO 64GB                          | 1         | 1.15%   |
| Unknown NVMe SSD Drive 1024GB                       | 1         | 1.15%   |
| Unknown MMC Card  512GB                             | 1         | 1.15%   |
| Unknown MMC Card  16GB                              | 1         | 1.15%   |
| Toshiba XG6 NVMe SSD Controller 256GB               | 1         | 1.15%   |
| Toshiba NVMe Controller 256GB                       | 1         | 1.15%   |
| Toshiba MQ02ABD100H 1TB                             | 1         | 1.15%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 1.15%   |
| Toshiba MK1234GSX 120GB                             | 1         | 1.15%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 1TB | 1         | 1.15%   |
| Shenzhen Longsys Lexar SSD NM710 2TB                | 1         | 1.15%   |
| Seagate ST9500325AS 500GB                           | 1         | 1.15%   |
| Seagate ST9320423AS 320GB                           | 1         | 1.15%   |
| Seagate ST500LM000-1EJ162-SSHD 500GB                | 1         | 1.15%   |
| Seagate ST4000LM024-2AN17V 4TB                      | 1         | 1.15%   |
| Seagate ST2000DM006-2DM164 2TB                      | 1         | 1.15%   |
| Seagate ST2000DL003-9VT166 2TB                      | 1         | 1.15%   |
| Seagate ST1000LM048-2E7172 1TB                      | 1         | 1.15%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1.15%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1         | 1.15%   |
| Seagate Expansion Desk 4TB                          | 1         | 1.15%   |
| Seagate Basic 2TB                                   | 1         | 1.15%   |
| Sandisk WD_BLACK SN770 2TB                          | 1         | 1.15%   |
| Sandisk WD_BLACK SN750 SE NVMe 1TB                  | 1         | 1.15%   |
| Sandisk WD Black SN850 500GB                        | 1         | 1.15%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 256GB    | 1         | 1.15%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 11     | 40.91%  |
| WDC                 | 8         | 9      | 36.36%  |
| Toshiba             | 3         | 3      | 13.64%  |
| Unknown             | 1         | 1      | 4.55%   |
| Samsung Electronics | 1         | 1      | 4.55%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 9      | 23.08%  |
| Kingston            | 5         | 5      | 19.23%  |
| SanDisk             | 4         | 5      | 15.38%  |
| Micron Technology   | 3         | 4      | 11.54%  |
| Crucial             | 2         | 3      | 7.69%   |
| WDC                 | 1         | 2      | 3.85%   |
| Netac               | 1         | 1      | 3.85%   |
| KingDian            | 1         | 2      | 3.85%   |
| Hewlett-Packard     | 1         | 1      | 3.85%   |
| Fanxiang            | 1         | 1      | 3.85%   |
| Corsair             | 1         | 1      | 3.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 27        | 35     | 40.3%   |
| SSD     | 19        | 34     | 28.36%  |
| HDD     | 17        | 25     | 25.37%  |
| MMC     | 2         | 2      | 2.99%   |
| Unknown | 2         | 2      | 2.99%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 28        | 56     | 45.9%   |
| NVMe | 27        | 35     | 44.26%  |
| SAS  | 4         | 5      | 6.56%   |
| MMC  | 2         | 2      | 3.28%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 18        | 35     | 47.37%  |
| 0.51-1.0   | 12        | 12     | 31.58%  |
| 1.01-2.0   | 4         | 6      | 10.53%  |
| 3.01-4.0   | 3         | 5      | 7.89%   |
| 10.01-20.0 | 1         | 1      | 2.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 17        | 38.64%  |
| 1001-2000      | 15        | 34.09%  |
| 251-500        | 7         | 15.91%  |
| 501-1000       | 4         | 9.09%   |
| 2001-3000      | 1         | 2.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 15        | 33.33%  |
| 101-250        | 10        | 22.22%  |
| 51-100         | 6         | 13.33%  |
| 251-500        | 5         | 11.11%  |
| 501-1000       | 4         | 8.89%   |
| More than 3000 | 3         | 6.67%   |
| 2001-3000      | 1         | 2.22%   |
| 1001-2000      | 1         | 2.22%   |

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
| Detected | 43        | 98     | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 29        | 43.94%  |
| AMD                          | 8         | 12.12%  |
| Samsung Electronics          | 7         | 10.61%  |
| SanDisk                      | 4         | 6.06%   |
| Kingston Technology Company  | 4         | 6.06%   |
| Phison Electronics           | 3         | 4.55%   |
| Toshiba America Info Systems | 2         | 3.03%   |
| Micron/Crucial Technology    | 2         | 3.03%   |
| Biwin Storage Technology     | 2         | 3.03%   |
| Silicon Motion               | 1         | 1.52%   |
| Shenzhen Longsys Electronics | 1         | 1.52%   |
| Micron Technology            | 1         | 1.52%   |
| INNOGRIT                     | 1         | 1.52%   |
| ADATA Technology             | 1         | 1.52%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 6         | 8.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 5.56%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 5.56%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 4.17%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 4.17%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 4.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 4.17%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2         | 2.78%   |
| Kingston Company NVMe Controller                                               | 2         | 2.78%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 2.78%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2         | 2.78%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 2.78%   |
| Biwin Storage Non-Volatile memory controller                                   | 2         | 2.78%   |
| AMD 500 Series Chipset SATA Controller                                         | 2         | 2.78%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 1.39%   |
| Toshiba America Info Systems NVMe Controller                                   | 1         | 1.39%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1         | 1.39%   |
| Shenzhen Longsys Non-Volatile memory controller                                | 1         | 1.39%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 1.39%   |
| SanDisk WD Black SN770 NVMe SSD                                                | 1         | 1.39%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 1.39%   |
| SanDisk Non-Volatile memory controller                                         | 1         | 1.39%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.39%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 1.39%   |
| Phison Electronics Non-Volatile memory controller                              | 1         | 1.39%   |
| Phison E12 NVMe Controller                                                     | 1         | 1.39%   |
| Micron NVMe Storage Controller                                                 | 1         | 1.39%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 1.39%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                             | 1         | 1.39%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.39%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 1         | 1.39%   |
| Intel SSD 665p Series                                                          | 1         | 1.39%   |
| Intel SSD 600P Series                                                          | 1         | 1.39%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.39%   |
| Intel Non-Volatile memory controller                                           | 1         | 1.39%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1         | 1.39%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.39%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 1.39%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 1         | 1.39%   |
| Intel 700 Series Chipset Family SATA AHCI Controller                           | 1         | 1.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 31        | 48.44%  |
| NVMe | 27        | 42.19%  |
| RAID | 5         | 7.81%   |
| IDE  | 1         | 1.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 28        | 65.12%  |
| AMD    | 15        | 34.88%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 6800U with Radeon Graphics        | 4         | 9.09%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 2         | 4.55%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 2         | 4.55%   |
| AMD Ryzen 7 5800U with Radeon Graphics        | 2         | 4.55%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz           | 1         | 2.27%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 2.27%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 2.27%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 1         | 2.27%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 2.27%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 1         | 2.27%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 2.27%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 2.27%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 2.27%   |
| Intel Core i5-7500 CPU @ 3.40GHz              | 1         | 2.27%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 2.27%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 2.27%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 2.27%   |
| Intel Core i5-4210H CPU @ 2.90GHz             | 1         | 2.27%   |
| Intel Core i5-3570 CPU @ 3.40GHz              | 1         | 2.27%   |
| Intel Core i5-2500K CPU @ 3.30GHz             | 1         | 2.27%   |
| Intel Core i5-2500 CPU @ 3.30GHz              | 1         | 2.27%   |
| Intel Core i5-10400F CPU @ 2.90GHz            | 1         | 2.27%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 2.27%   |
| Intel Core i3-10100F CPU @ 3.60GHz            | 1         | 2.27%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 1         | 2.27%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz         | 1         | 2.27%   |
| Intel 13th Gen Core i9-13900K                 | 1         | 2.27%   |
| Intel 12th Gen Core i7-1255U                  | 1         | 2.27%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 1         | 2.27%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 1         | 2.27%   |
| AMD Ryzen 9 7950X3D 16-Core Processor         | 1         | 2.27%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 1         | 2.27%   |
| AMD Ryzen 9 5900HS with Radeon Graphics       | 1         | 2.27%   |
| AMD Ryzen 7 7700X 8-Core Processor            | 1         | 2.27%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 1         | 2.27%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 1         | 2.27%   |
| AMD Ryzen 7 1700X Eight-Core Processor        | 1         | 2.27%   |
| AMD Ryzen 5 7600X 6-Core Processor            | 1         | 2.27%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 11        | 25%     |
| AMD Ryzen 7       | 10        | 22.73%  |
| Intel Core i7     | 8         | 18.18%  |
| AMD Ryzen 9       | 5         | 11.36%  |
| Other             | 4         | 9.09%   |
| Intel Core i3     | 3         | 6.82%   |
| Intel Xeon        | 1         | 2.27%   |
| Intel Core 2 Quad | 1         | 2.27%   |
| AMD Ryzen 5       | 1         | 2.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 16        | 36.36%  |
| 8      | 12        | 27.27%  |
| 6      | 5         | 11.36%  |
| 2      | 5         | 11.36%  |
| 16     | 2         | 4.55%   |
| 12     | 2         | 4.55%   |
| 24     | 1         | 2.27%   |
| 10     | 1         | 2.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 43        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 34        | 79.07%  |
| 1      | 9         | 20.93%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 43        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 43        | 100%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 9         | 20.93%  |
| Zen 3       | 7         | 16.28%  |
| KabyLake    | 6         | 13.95%  |
| CometLake   | 5         | 11.63%  |
| Skylake     | 4         | 9.3%    |
| Haswell     | 3         | 6.98%   |
| SandyBridge | 2         | 4.65%   |
| IvyBridge   | 2         | 4.65%   |
| Zen+        | 1         | 2.33%   |
| Zen         | 1         | 2.33%   |
| TigerLake   | 1         | 2.33%   |
| Penryn      | 1         | 2.33%   |
| Broadwell   | 1         | 2.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Nvidia | 19        | 33.93%  |
| AMD    | 19        | 33.93%  |
| Intel  | 18        | 32.14%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Rembrandt [Radeon 680M]                                                 | 4         | 7.02%   |
| Intel HD Graphics 530                                                       | 3         | 5.26%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3         | 5.26%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 2         | 3.51%   |
| Intel HD Graphics 630                                                       | 2         | 3.51%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX]                                    | 2         | 3.51%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2         | 3.51%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2         | 3.51%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1         | 1.75%   |
| Nvidia TU117 [GeForce GTX 1630]                                             | 1         | 1.75%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 1         | 1.75%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1         | 1.75%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                     | 1         | 1.75%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 1         | 1.75%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                       | 1         | 1.75%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 1         | 1.75%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1         | 1.75%   |
| Nvidia GM108M [GeForce MX130]                                               | 1         | 1.75%   |
| Nvidia GM108M [GeForce 940M]                                                | 1         | 1.75%   |
| Nvidia GM108M [GeForce 940MX]                                               | 1         | 1.75%   |
| Nvidia GM107M [GeForce GTX 960M]                                            | 1         | 1.75%   |
| Nvidia GM107M [GeForce GTX 950M]                                            | 1         | 1.75%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                           | 1         | 1.75%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 1         | 1.75%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                             | 1         | 1.75%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 1         | 1.75%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 1         | 1.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1         | 1.75%   |
| Intel UHD Graphics 620                                                      | 1         | 1.75%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 1         | 1.75%   |
| Intel HD Graphics 620                                                       | 1         | 1.75%   |
| Intel HD Graphics 5500                                                      | 1         | 1.75%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1         | 1.75%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 1         | 1.75%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 1         | 1.75%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                 | 1         | 1.75%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 1         | 1.75%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 1         | 1.75%   |
| AMD Raphael                                                                 | 1         | 1.75%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1         | 1.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 17        | 38.64%  |
| Intel + Nvidia | 9         | 20.45%  |
| 1 x Nvidia     | 8         | 18.18%  |
| 1 x Intel      | 8         | 18.18%  |
| AMD + Nvidia   | 2         | 4.55%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 25        | 58.14%  |
| Proprietary | 18        | 41.86%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 40        | 93.02%  |
| 3.01-4.0   | 2         | 4.65%   |
| 8.01-16.0  | 1         | 2.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 18.6%   |
| BOE                 | 7         | 16.28%  |
| LG Display          | 4         | 9.3%    |
| Chimei Innolux      | 4         | 9.3%    |
| Sony                | 2         | 4.65%   |
| Sharp               | 2         | 4.65%   |
| Goldstar            | 2         | 4.65%   |
| BenQ                | 2         | 4.65%   |
| AU Optronics        | 2         | 4.65%   |
| Vizio               | 1         | 2.33%   |
| Toshiba             | 1         | 2.33%   |
| Panasonic           | 1         | 2.33%   |
| Onkyo               | 1         | 2.33%   |
| Insignia            | 1         | 2.33%   |
| Hewlett-Packard     | 1         | 2.33%   |
| AYANEO              | 1         | 2.33%   |
| AYA                 | 1         | 2.33%   |
| ASUSTek Computer    | 1         | 2.33%   |
| Acer                | 1         | 2.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| BOE FLQ8423-24L0 BOE1003 1600x2560 113x181mm 8.4-inch                | 2         | 4.65%   |
| Vizio D40f-G9 VIZ1027 1920x1080 477x268mm 21.5-inch                  | 1         | 2.33%   |
| Toshiba TV TSB002F 3840x2160 1095x616mm 49.5-inch                    | 1         | 2.33%   |
| Sony TV SNYEE01 1920x1080                                            | 1         | 2.33%   |
| Sony TV SNY3002 1920x1080 886x498mm 40.0-inch                        | 1         | 2.33%   |
| Sharp LQ173M1JW02 SHP14DB 1920x1080 382x215mm 17.3-inch              | 1         | 2.33%   |
| Sharp HDMI SHP0FE8 1920x1080 1152x648mm 52.0-inch                    | 1         | 2.33%   |
| Samsung Electronics SyncMaster SAM030F 1680x1050 474x296mm 22.0-inch | 1         | 2.33%   |
| Samsung Electronics S24R35xFZ SAM71A8 1920x1080 527x296mm 23.8-inch  | 1         | 2.33%   |
| Samsung Electronics S24C650 SAM09E8 1920x1080 521x293mm 23.5-inch    | 1         | 2.33%   |
| Samsung Electronics QBQ95 SAM7229 3840x2160 1872x1053mm 84.6-inch    | 1         | 2.33%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch | 1         | 2.33%   |
| Samsung Electronics LCD Monitor SAM065D 1920x1080                    | 1         | 2.33%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch  | 1         | 2.33%   |
| Samsung Electronics LC27T55 SAM701F 1920x1080 609x349mm 27.6-inch    | 1         | 2.33%   |
| Panasonic VVX14T092N00 MEI96A2 2256x1504 285x190mm 13.5-inch         | 1         | 2.33%   |
| Onkyo AV Receiver ONK1150 3840x2160 1872x1053mm 84.6-inch            | 1         | 2.33%   |
| LG Display LCD Monitor LGD071E 1920x1080 344x194mm 15.5-inch         | 1         | 2.33%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch         | 1         | 2.33%   |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch         | 1         | 2.33%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch          | 1         | 2.33%   |
| Insignia NS-32D20SNA14 BBY0032 1360x768 544x326mm 25.0-inch          | 1         | 2.33%   |
| Hewlett-Packard M24fwa FHD HPN372F 1920x1080 527x296mm 23.8-inch     | 1         | 2.33%   |
| Goldstar TV GSMC0A0 3840x2160                                        | 1         | 2.33%   |
| Goldstar M237WDP GSM5779 1920x1080 598x336mm 27.0-inch               | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN176E 1920x1080 381x214mm 17.2-inch     | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch     | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN1540 2560x1440 344x193mm 15.5-inch     | 1         | 2.33%   |
| BOE LCD Monitor BOE9002 800x1280                                     | 1         | 2.33%   |
| BOE LCD Monitor BOE9001 1200x1920                                    | 1         | 2.33%   |
| BOE LCD Monitor BOE0A2A 1920x1200 302x188mm 14.0-inch                | 1         | 2.33%   |
| BOE LCD Monitor BOE0977 2560x1440 381x214mm 17.2-inch                | 1         | 2.33%   |
| BOE LCD Monitor BOE065D 1920x1080 344x194mm 15.5-inch                | 1         | 2.33%   |
| BenQ XL2411Z BNQ7F31 1920x1080 530x300mm 24.0-inch                   | 1         | 2.33%   |
| BenQ LCD BNQ801B 2560x1440 527x296mm 23.8-inch                       | 1         | 2.33%   |
| AYANEO AYANEOWUXGA AYA0105 1200x1920                                 | 1         | 2.33%   |
| AYA AYANEOWUXGA AYA0105 1200x1920                                    | 1         | 2.33%   |
| AU Optronics LCD Monitor AUOD0ED 1920x1080 344x193mm 15.5-inch       | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 1         | 2.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 20        | 47.62%  |
| 3840x2160 (4K)     | 5         | 11.9%   |
| 2560x1440 (QHD)    | 4         | 9.52%   |
| 1366x768 (WXGA)    | 3         | 7.14%   |
| 1200x1920          | 3         | 7.14%   |
| 1600x2560          | 2         | 4.76%   |
| 800x1280           | 1         | 2.38%   |
| 3840x1080          | 1         | 2.38%   |
| 1920x540           | 1         | 2.38%   |
| 1920x1200 (WUXGA)  | 1         | 2.38%   |
| 1680x1050 (WSXGA+) | 1         | 2.38%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 10        | 23.26%  |
| Unknown | 5         | 11.63%  |
| 17      | 4         | 9.3%    |
| 84      | 3         | 6.98%   |
| 27      | 3         | 6.98%   |
| 23      | 3         | 6.98%   |
| 72      | 2         | 4.65%   |
| 48      | 2         | 4.65%   |
| 24      | 2         | 4.65%   |
| 14      | 2         | 4.65%   |
| 8       | 2         | 4.65%   |
| 52      | 1         | 2.33%   |
| 49      | 1         | 2.33%   |
| 40      | 1         | 2.33%   |
| 26      | 1         | 2.33%   |
| 22      | 1         | 2.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 12        | 27.91%  |
| 501-600     | 8         | 18.6%   |
| 1501-2000   | 5         | 11.63%  |
| Unknown     | 5         | 11.63%  |
| 351-400     | 4         | 9.3%    |
| 1001-1500   | 4         | 9.3%    |
| 101-200     | 2         | 4.65%   |
| 801-900     | 1         | 2.33%   |
| 601-700     | 1         | 2.33%   |
| 401-500     | 1         | 2.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 31        | 73.81%  |
| 0.62  | 6         | 14.29%  |
| 16/10 | 3         | 7.14%   |
| 32/9  | 1         | 2.38%   |
| 1.96  | 1         | 2.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 10        | 23.81%  |
| More than 1000 | 7         | 16.67%  |
| 201-250        | 5         | 11.9%   |
| Unknown        | 5         | 11.9%   |
| 301-350        | 4         | 9.52%   |
| 121-130        | 4         | 9.52%   |
| 501-1000       | 3         | 7.14%   |
| 81-90          | 2         | 4.76%   |
| 1-40           | 2         | 4.76%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 14        | 32.56%  |
| 121-160       | 10        | 23.26%  |
| Unknown       | 5         | 11.63%  |
| 1-50          | 4         | 9.3%    |
| 101-120       | 4         | 9.3%    |
| More than 240 | 3         | 6.98%   |
| 161-240       | 3         | 6.98%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 41        | 93.18%  |
| 2     | 3         | 6.82%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 23        | 33.33%  |
| Intel                           | 21        | 30.43%  |
| Qualcomm Atheros                | 9         | 13.04%  |
| MediaTek                        | 7         | 10.14%  |
| TP-Link                         | 2         | 2.9%    |
| Marvell Technology Group        | 2         | 2.9%    |
| Ralink                          | 1         | 1.45%   |
| Qualcomm Atheros Communications | 1         | 1.45%   |
| OnePlus Technology (Shenzhen)   | 1         | 1.45%   |
| Broadcom Limited                | 1         | 1.45%   |
| Broadcom                        | 1         | 1.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                | Computers | Percent |
|--------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                    | 14        | 17.28%  |
| Realtek RTL8125 2.5GbE Controller                                                    | 6         | 7.41%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 5         | 6.17%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                              | 4         | 4.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                           | 3         | 3.7%    |
| Intel Wi-Fi 6 AX200                                                                  | 3         | 3.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                             | 2         | 2.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                           | 2         | 2.47%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                        | 2         | 2.47%   |
| Intel I211 Gigabit Network Connection                                                | 2         | 2.47%   |
| Intel Ethernet Controller I225-V                                                     | 2         | 2.47%   |
| Intel Comet Lake PCH CNVi WiFi                                                       | 2         | 2.47%   |
| TP-Link Archer T4U ver.3                                                             | 1         | 1.23%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                               | 1         | 1.23%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                   | 1         | 1.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                             | 1         | 1.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 1         | 1.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                      | 1         | 1.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 1         | 1.23%   |
| Realtek RTL8187 Wireless Adapter                                                     | 1         | 1.23%   |
| Realtek PCIe GbE Family Controller                                                   | 1         | 1.23%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                            | 1         | 1.23%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                            | 1         | 1.23%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                            | 1         | 1.23%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1         | 1.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 1         | 1.23%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                        | 1         | 1.23%   |
| OnePlus (Shenzhen) SM8150-MTP _SN:5A38C392                                           | 1         | 1.23%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                        | 1         | 1.23%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                                    | 1         | 1.23%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                              | 1         | 1.23%   |
| Intel Wireless-AC 9260                                                               | 1         | 1.23%   |
| Intel Wireless 3165                                                                  | 1         | 1.23%   |
| Intel Wi-Fi 6 AX201                                                                  | 1         | 1.23%   |
| Intel Tiger Lake PCH CNVi WiFi                                                       | 1         | 1.23%   |
| Intel Ethernet Connection I217-LM                                                    | 1         | 1.23%   |
| Intel Ethernet Connection (5) I219-LM                                                | 1         | 1.23%   |
| Intel Ethernet Connection (2) I219-V                                                 | 1         | 1.23%   |
| Intel Ethernet Connection (12) I219-V                                                | 1         | 1.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 1         | 1.23%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 17        | 41.46%  |
| MediaTek                        | 7         | 17.07%  |
| Qualcomm Atheros                | 6         | 14.63%  |
| Realtek Semiconductor           | 4         | 9.76%   |
| TP-Link                         | 2         | 4.88%   |
| Ralink                          | 1         | 2.44%   |
| Qualcomm Atheros Communications | 1         | 2.44%   |
| Marvell Technology Group        | 1         | 2.44%   |
| Broadcom Limited                | 1         | 2.44%   |
| Broadcom                        | 1         | 2.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Computers | Percent |
|--------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 5         | 11.36%  |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                              | 4         | 9.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                           | 3         | 6.82%   |
| Intel Wi-Fi 6 AX200                                                                  | 3         | 6.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                           | 2         | 4.55%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                        | 2         | 4.55%   |
| Intel Comet Lake PCH CNVi WiFi                                                       | 2         | 4.55%   |
| TP-Link Archer T4U ver.3                                                             | 1         | 2.27%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                               | 1         | 2.27%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                   | 1         | 2.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                             | 1         | 2.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 1         | 2.27%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                      | 1         | 2.27%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 1         | 2.27%   |
| Realtek RTL8187 Wireless Adapter                                                     | 1         | 2.27%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                            | 1         | 2.27%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1         | 2.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 1         | 2.27%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                        | 1         | 2.27%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                                    | 1         | 2.27%   |
| Intel Wireless-AC 9260                                                               | 1         | 2.27%   |
| Intel Wireless 3165                                                                  | 1         | 2.27%   |
| Intel Wi-Fi 6 AX201                                                                  | 1         | 2.27%   |
| Intel Tiger Lake PCH CNVi WiFi                                                       | 1         | 2.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 1         | 2.27%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                      | 1         | 2.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 1         | 2.27%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                     | 1         | 2.27%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                           | 1         | 2.27%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                   | 1         | 2.27%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 22        | 62.86%  |
| Intel                    | 9         | 25.71%  |
| Qualcomm Atheros         | 3         | 8.57%   |
| Marvell Technology Group | 1         | 2.86%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14        | 38.89%  |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 16.67%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 5.56%   |
| Intel I211 Gigabit Network Connection                             | 2         | 5.56%   |
| Intel Ethernet Controller I225-V                                  | 2         | 5.56%   |
| Realtek PCIe GbE Family Controller                                | 1         | 2.78%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 2.78%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 2.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 2.78%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 2.78%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.78%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 2.78%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 2.78%   |
| Intel Ethernet Connection (12) I219-V                             | 1         | 2.78%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 2.78%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 37        | 51.39%  |
| Ethernet | 34        | 47.22%  |
| Unknown  | 1         | 1.39%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 32        | 68.09%  |
| Ethernet | 15        | 31.91%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 25        | 58.14%  |
| 1     | 16        | 37.21%  |
| 3     | 2         | 4.65%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 32        | 72.73%  |
| Yes  | 12        | 27.27%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 16        | 47.06%  |
| MediaTek                        | 5         | 14.71%  |
| Lite-On Technology              | 3         | 8.82%   |
| IMC Networks                    | 3         | 8.82%   |
| Cambridge Silicon Radio         | 2         | 5.88%   |
| Realtek Semiconductor           | 1         | 2.94%   |
| Qualcomm Atheros Communications | 1         | 2.94%   |
| Foxconn / Hon Hai               | 1         | 2.94%   |
| ASUSTek Computer                | 1         | 2.94%   |
| Apple                           | 1         | 2.94%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| MediaTek Wireless_Device                            | 5         | 14.29%  |
| Intel AX210 Bluetooth                               | 5         | 14.29%  |
| Intel AX201 Bluetooth                               | 4         | 11.43%  |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 5.71%   |
| Intel Bluetooth wireless interface                  | 2         | 5.71%   |
| Intel AX200 Bluetooth                               | 2         | 5.71%   |
| IMC Networks Bluetooth Radio                        | 2         | 5.71%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 5.71%   |
| Realtek Bluetooth Radio                             | 1         | 2.86%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 2.86%   |
| Lite-On Bluetooth Device                            | 1         | 2.86%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 2.86%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.86%   |
| Intel Bluetooth Device                              | 1         | 2.86%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 2.86%   |
| IMC Networks Wireless_Device                        | 1         | 2.86%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 1         | 2.86%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1         | 2.86%   |
| Apple Bluetooth Host Controller                     | 1         | 2.86%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 28        | 40%     |
| AMD                      | 21        | 30%     |
| Nvidia                   | 14        | 20%     |
| SteelSeries ApS          | 1         | 1.43%   |
| Sony                     | 1         | 1.43%   |
| Micro Star International | 1         | 1.43%   |
| Kingston Technology      | 1         | 1.43%   |
| Focusrite-Novation       | 1         | 1.43%   |
| ASUSTek Computer         | 1         | 1.43%   |
| Astro Gaming             | 1         | 1.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 9         | 10.47%  |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 5         | 5.81%   |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 4.65%   |
| AMD Starship/Matisse HD Audio Controller                                   | 4         | 4.65%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 4         | 4.65%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 3.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 3.49%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 3.49%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 3.49%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 2.33%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 2.33%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 2.33%   |
| Nvidia GA102 High Definition Audio Controller                              | 2         | 2.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 2.33%   |
| Intel Comet Lake PCH-V cAVS                                                | 2         | 2.33%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 2.33%   |
| AMD Navi 31 [Radeon RX 7000 HDMI Audio]                                    | 2         | 2.33%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2         | 2.33%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2         | 2.33%   |
| SteelSeries ApS SteelSeries Arctis 1 Wireless                              | 1         | 1.16%   |
| Sony DualSense wireless controller (PS5)                                   | 1         | 1.16%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 1.16%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.16%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 1.16%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.16%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 1.16%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 1.16%   |
| Micro Star International USB Audio                                         | 1         | 1.16%   |
| Kingston Technology HyperX Quadcast                                        | 1         | 1.16%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 1.16%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 1.16%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.16%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 1         | 1.16%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 1.16%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.16%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.16%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 1.16%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 1.16%   |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1           | 1         | 1.16%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 1.16%   |

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
| Chicony Electronics           | 5         | 33.33%  |
| Microdia                      | 2         | 13.33%  |
| IMC Networks                  | 2         | 13.33%  |
| Bison Electronics             | 2         | 13.33%  |
| Sunplus Innovation Technology | 1         | 6.67%   |
| Quanta                        | 1         | 6.67%   |
| Logitech                      | 1         | 6.67%   |
| Apple                         | 1         | 6.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Bison Lenovo EasyCamera           | 2         | 13.33%  |
| Sunplus HD WebCam                 | 1         | 6.67%   |
| Quanta HP HD Camera               | 1         | 6.67%   |
| Microdia Integrated_Webcam_FHD    | 1         | 6.67%   |
| Microdia HP Webcam                | 1         | 6.67%   |
| Logitech Webcam C200              | 1         | 6.67%   |
| IMC Networks USB2.0 HD UVC WebCam | 1         | 6.67%   |
| IMC Networks Integrated Camera    | 1         | 6.67%   |
| Chicony USB2.0 FHD Camera         | 1         | 6.67%   |
| Chicony USB2.0 0.3M UVC WebCam    | 1         | 6.67%   |
| Chicony Integrated IR Camera      | 1         | 6.67%   |
| Chicony Integrated Camera         | 1         | 6.67%   |
| Chicony EasyCamera                | 1         | 6.67%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X   | 1         | 6.67%   |

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
| 0     | 36        | 83.72%  |
| 1     | 7         | 16.28%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Multimedia controller | 3         | 42.86%  |
| Storage/nvme          | 1         | 14.29%  |
| Network               | 1         | 14.29%  |
| Graphics card         | 1         | 14.29%  |
| Fingerprint reader    | 1         | 14.29%  |

