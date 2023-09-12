Archcraft - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Archcraft.

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

Total: 51

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Vostro 3401                 | [792ea03809](https://linux-hardware.org/?probe=792ea03809) | Aug 19, 2023 |
| Packard Be... | EasyNote TK85               | [da059008eb](https://linux-hardware.org/?probe=da059008eb) | Aug 14, 2023 |
| AXDIA Inte... | WINPAD V10                  | [4dc8c20191](https://linux-hardware.org/?probe=4dc8c20191) | Aug 13, 2023 |
| HUAWEI        | HLYL-WXX9                   | [41831db130](https://linux-hardware.org/?probe=41831db130) | Aug 13, 2023 |
| HP            | Laptop 15-dy2xxx            | [bbe4e49261](https://linux-hardware.org/?probe=bbe4e49261) | Aug 01, 2023 |
| AXDIA Inte... | WINPAD V10                  | [0e7e712860](https://linux-hardware.org/?probe=0e7e712860) | Jul 24, 2023 |
| Dell          | Latitude E5420              | [be15c1e3d1](https://linux-hardware.org/?probe=be15c1e3d1) | Jul 20, 2023 |
| Infinix       | INBook X1 Pro               | [a03717af50](https://linux-hardware.org/?probe=a03717af50) | Jun 26, 2023 |
| HP            | Notebook                    | [1ce7986145](https://linux-hardware.org/?probe=1ce7986145) | Jun 11, 2023 |
| HUAWEI        | NBD-WXX9                    | [61c1703e67](https://linux-hardware.org/?probe=61c1703e67) | Jun 10, 2023 |
| HUAWEI        | NBD-WXX9                    | [321ad38786](https://linux-hardware.org/?probe=321ad38786) | Jun 10, 2023 |
| HUAWEI        | BOHB-WAX9                   | [08eb3979f4](https://linux-hardware.org/?probe=08eb3979f4) | May 19, 2023 |
| Dell          | Latitude 5490               | [2ce70b7a2c](https://linux-hardware.org/?probe=2ce70b7a2c) | May 04, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [eeef579322](https://linux-hardware.org/?probe=eeef579322) | Apr 28, 2023 |
| MSI           | Alpha 15 B5EEK              | [c7f5eaf3f1](https://linux-hardware.org/?probe=c7f5eaf3f1) | Mar 28, 2023 |
| eMachines     | eME730                      | [0e1683ee34](https://linux-hardware.org/?probe=0e1683ee34) | Mar 08, 2023 |
| eMachines     | eME730                      | [db15f88805](https://linux-hardware.org/?probe=db15f88805) | Mar 08, 2023 |
| MSI           | Katana GF66 11UE            | [aead8d4d18](https://linux-hardware.org/?probe=aead8d4d18) | Jan 26, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | [6f3b4fc131](https://linux-hardware.org/?probe=6f3b4fc131) | Jan 16, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | [b33bedc4c2](https://linux-hardware.org/?probe=b33bedc4c2) | Jan 15, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | [806da9b386](https://linux-hardware.org/?probe=806da9b386) | Jan 12, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | [29e6fcfd32](https://linux-hardware.org/?probe=29e6fcfd32) | Jan 12, 2023 |
| Dell          | Inspiron 7559               | [52cf8ddc0f](https://linux-hardware.org/?probe=52cf8ddc0f) | Dec 22, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | [d2c04dd7cd](https://linux-hardware.org/?probe=d2c04dd7cd) | Dec 01, 2022 |
| Chuwi         | GemiBook Pro                | [315d8b6ff7](https://linux-hardware.org/?probe=315d8b6ff7) | Nov 08, 2022 |
| MSI           | GF63 Thin 10SC              | [2b22722ce8](https://linux-hardware.org/?probe=2b22722ce8) | Oct 27, 2022 |
| Dell          | Latitude E6420              | [3ea84baba3](https://linux-hardware.org/?probe=3ea84baba3) | Sep 09, 2022 |
| Dell          | Latitude E6420              | [78fd24b713](https://linux-hardware.org/?probe=78fd24b713) | Sep 09, 2022 |
| Apple         | MacBook4,1                  | [500d050ad6](https://linux-hardware.org/?probe=500d050ad6) | Sep 06, 2022 |
| Apple         | MacBook4,1                  | [01b8531ddf](https://linux-hardware.org/?probe=01b8531ddf) | Sep 04, 2022 |
| Apple         | MacBook4,1                  | [9e4c1bc292](https://linux-hardware.org/?probe=9e4c1bc292) | Sep 04, 2022 |
| HP            | Notebook                    | [b0b97c0ea3](https://linux-hardware.org/?probe=b0b97c0ea3) | Aug 30, 2022 |
| HP            | Laptop 15-dw0xxx            | [8bb62c2062](https://linux-hardware.org/?probe=8bb62c2062) | Aug 24, 2022 |
| ASUSTek       | X441SA                      | [cb26c73037](https://linux-hardware.org/?probe=cb26c73037) | Aug 16, 2022 |
| Acer          | Swift SF113-31              | [1c4298ff33](https://linux-hardware.org/?probe=1c4298ff33) | Aug 08, 2022 |
| Acer          | Swift SF113-31              | [0f1ad8ccf7](https://linux-hardware.org/?probe=0f1ad8ccf7) | Aug 08, 2022 |
| Dell          | Latitude E7250              | [2dd83a16c7](https://linux-hardware.org/?probe=2dd83a16c7) | Aug 01, 2022 |
| Acer          | Aspire E5-573               | [01f3150f60](https://linux-hardware.org/?probe=01f3150f60) | Jul 01, 2022 |
| Positivo      | CHT14B                      | [95566d3625](https://linux-hardware.org/?probe=95566d3625) | Jun 05, 2022 |
| Framework     | Laptop                      | [f8790adbf2](https://linux-hardware.org/?probe=f8790adbf2) | May 25, 2022 |
| Standard      | Unknown                     | [74971ae227](https://linux-hardware.org/?probe=74971ae227) | May 04, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [c8c2ede566](https://linux-hardware.org/?probe=c8c2ede566) | Feb 11, 2022 |
| Dell          | Inspiron 3542               | [f3f3b08d89](https://linux-hardware.org/?probe=f3f3b08d89) | Feb 09, 2022 |
| Dell          | Inspiron 3542               | [e975782c15](https://linux-hardware.org/?probe=e975782c15) | Jan 31, 2022 |
| Lenovo        | ThinkPad T430 2351AK9       | [19f50b09d5](https://linux-hardware.org/?probe=19f50b09d5) | Jan 21, 2022 |
| Apple         | MacBookAir4,1               | [ecc4515014](https://linux-hardware.org/?probe=ecc4515014) | Nov 01, 2021 |
| Google        | Kindred                     | [c2631a9488](https://linux-hardware.org/?probe=c2631a9488) | Jul 29, 2021 |
| HP            | Laptop 15q-bu1xx            | [af9f2a95ec](https://linux-hardware.org/?probe=af9f2a95ec) | Jun 28, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | [5e0e7e2b80](https://linux-hardware.org/?probe=5e0e7e2b80) | Jun 25, 2021 |
| HP            | Pavilion g4                 | [6a3471480a](https://linux-hardware.org/?probe=6a3471480a) | May 29, 2021 |
| MSI           | GL65 Leopard 10SFK          | [a9e5bb7556](https://linux-hardware.org/?probe=a9e5bb7556) | May 28, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Archcraft Rolling | 29        | 78.38%  |
| Archcraft         | 8         | 21.62%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| Archcraft | 37        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 6.2.13-arch1-1         | 2         | 5%      |
| 5.18.16-arch1-1        | 2         | 5%      |
| 5.12.7-arch1-1         | 2         | 5%      |
| 6.4.7-arch1-1          | 1         | 2.5%    |
| 6.4.4-zen1-1-zen       | 1         | 2.5%    |
| 6.4.4-arch1-1          | 1         | 2.5%    |
| 6.4.10-zen2-1-zen      | 1         | 2.5%    |
| 6.4.10-arch1-1         | 1         | 2.5%    |
| 6.4.1-arch2-1          | 1         | 2.5%    |
| 6.3.9-arch1-1          | 1         | 2.5%    |
| 6.3.6-arch1-1          | 1         | 2.5%    |
| 6.2.8-zen1-1-zen       | 1         | 2.5%    |
| 6.2.2-arch1-1          | 1         | 2.5%    |
| 6.2.12-arch1-1         | 1         | 2.5%    |
| 6.1.7-arch1-1          | 1         | 2.5%    |
| 6.1.4-x64v1-xanmod1-1  | 1         | 2.5%    |
| 6.1.1-arch1-1          | 1         | 2.5%    |
| 6.0.7-arch1-1          | 1         | 2.5%    |
| 6.0.2-arch1-1          | 1         | 2.5%    |
| 6.0.10-x64v1-xanmod1-1 | 1         | 2.5%    |
| 5.19.7-arch1-1         | 1         | 2.5%    |
| 5.19.6-arch1-1         | 1         | 2.5%    |
| 5.19.3-arch1-1         | 1         | 2.5%    |
| 5.18.6-arch1-1         | 1         | 2.5%    |
| 5.18.14-zen1-1-zen     | 1         | 2.5%    |
| 5.17.9-arch1-1         | 1         | 2.5%    |
| 5.17.6-arch1-1         | 1         | 2.5%    |
| 5.17.5-arch1-1         | 1         | 2.5%    |
| 5.16.8-arch1-1         | 1         | 2.5%    |
| 5.16.7-arch1-1         | 1         | 2.5%    |
| 5.16.4-arch1-1         | 1         | 2.5%    |
| 5.16.1-arch1-1         | 1         | 2.5%    |
| 5.15.43-1-lts          | 1         | 2.5%    |
| 5.14.15-arch1-1        | 1         | 2.5%    |
| 5.12.9-arch1-1         | 1         | 2.5%    |
| 5.12.12-arch1-1        | 1         | 2.5%    |
| 5.10.54-1-lts          | 1         | 2.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.4.4   | 2         | 5%      |
| 6.4.10  | 2         | 5%      |
| 6.2.13  | 2         | 5%      |
| 5.18.16 | 2         | 5%      |
| 5.12.7  | 2         | 5%      |
| 6.4.7   | 1         | 2.5%    |
| 6.4.1   | 1         | 2.5%    |
| 6.3.9   | 1         | 2.5%    |
| 6.3.6   | 1         | 2.5%    |
| 6.2.8   | 1         | 2.5%    |
| 6.2.2   | 1         | 2.5%    |
| 6.2.12  | 1         | 2.5%    |
| 6.1.7   | 1         | 2.5%    |
| 6.1.4   | 1         | 2.5%    |
| 6.1.1   | 1         | 2.5%    |
| 6.0.7   | 1         | 2.5%    |
| 6.0.2   | 1         | 2.5%    |
| 6.0.10  | 1         | 2.5%    |
| 5.19.7  | 1         | 2.5%    |
| 5.19.6  | 1         | 2.5%    |
| 5.19.3  | 1         | 2.5%    |
| 5.18.6  | 1         | 2.5%    |
| 5.18.14 | 1         | 2.5%    |
| 5.17.9  | 1         | 2.5%    |
| 5.17.6  | 1         | 2.5%    |
| 5.17.5  | 1         | 2.5%    |
| 5.16.8  | 1         | 2.5%    |
| 5.16.7  | 1         | 2.5%    |
| 5.16.4  | 1         | 2.5%    |
| 5.16.1  | 1         | 2.5%    |
| 5.15.43 | 1         | 2.5%    |
| 5.14.15 | 1         | 2.5%    |
| 5.12.9  | 1         | 2.5%    |
| 5.12.12 | 1         | 2.5%    |
| 5.10.54 | 1         | 2.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.4     | 5         | 13.16%  |
| 6.2     | 5         | 13.16%  |
| 5.18    | 4         | 10.53%  |
| 5.12    | 4         | 10.53%  |
| 6.1     | 3         | 7.89%   |
| 6.0     | 3         | 7.89%   |
| 5.19    | 3         | 7.89%   |
| 5.17    | 3         | 7.89%   |
| 5.16    | 3         | 7.89%   |
| 6.3     | 2         | 5.26%   |
| 5.15    | 1         | 2.63%   |
| 5.14    | 1         | 2.63%   |
| 5.10    | 1         | 2.63%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 37        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| openbox  | 17        | 45.95%  |
| XFCE     | 9         | 24.32%  |
| bspwm    | 4         | 10.81%  |
| GNOME    | 2         | 5.41%   |
| sway     | 1         | 2.7%    |
| LXDE     | 1         | 2.7%    |
| i3       | 1         | 2.7%    |
| Hyprland | 1         | 2.7%    |
| Unknown  | 1         | 2.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 35        | 94.59%  |
| Wayland | 2         | 5.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 23        | 60.53%  |
| Unknown | 8         | 21.05%  |
| LXDM    | 5         | 13.16%  |
| Ly      | 1         | 2.63%   |
| LightDM | 1         | 2.63%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 16        | 43.24%  |
| es_MX | 5         | 13.51%  |
| en_IN | 3         | 8.11%   |
| es_ES | 2         | 5.41%   |
| en_ZA | 2         | 5.41%   |
| en_SG | 2         | 5.41%   |
| tr_TR | 1         | 2.7%    |
| pl_PL | 1         | 2.7%    |
| it_IT | 1         | 2.7%    |
| fr_FR | 1         | 2.7%    |
| en_PH | 1         | 2.7%    |
| en_GB | 1         | 2.7%    |
| de_AT | 1         | 2.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 26        | 70.27%  |
| BIOS | 11        | 29.73%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Ext4  | 31        | 83.78%  |
| Btrfs | 6         | 16.22%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 26        | 70.27%  |
| Unknown | 7         | 18.92%  |
| MBR     | 4         | 10.81%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 33        | 89.19%  |
| Yes       | 4         | 10.81%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 26        | 70.27%  |
| Yes       | 11        | 29.73%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 8         | 21.62%  |
| Dell                | 7         | 18.92%  |
| MSI                 | 4         | 10.81%  |
| HUAWEI              | 3         | 8.11%   |
| ASUSTek Computer    | 2         | 5.41%   |
| Apple               | 2         | 5.41%   |
| Acer                | 2         | 5.41%   |
| Standard            | 1         | 2.7%    |
| Positivo            | 1         | 2.7%    |
| Lenovo              | 1         | 2.7%    |
| Infinix             | 1         | 2.7%    |
| Google              | 1         | 2.7%    |
| Framework           | 1         | 2.7%    |
| eMachines           | 1         | 2.7%    |
| Chuwi               | 1         | 2.7%    |
| AXDIA International | 1         | 2.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Positivo CHT14B                | 1         | 2.7%    |
| MSI Katana GF66 11UE           | 1         | 2.7%    |
| MSI GL65 Leopard 10SFK         | 1         | 2.7%    |
| MSI GF63 Thin 10SC             | 1         | 2.7%    |
| MSI Alpha 15 B5EEK             | 1         | 2.7%    |
| Lenovo ThinkPad T430 2351AK9   | 1         | 2.7%    |
| Infinix INBook X1 Pro          | 1         | 2.7%    |
| HUAWEI NBD-WXX9                | 1         | 2.7%    |
| HUAWEI HLYL-WXX9               | 1         | 2.7%    |
| HUAWEI BOHB-WAX9               | 1         | 2.7%    |
| HP Stream Laptop 11-ak0xxx     | 1         | 2.7%    |
| HP Pavilion Laptop 15-eh0xxx   | 1         | 2.7%    |
| HP Pavilion Laptop 15-cc1xx    | 1         | 2.7%    |
| HP Pavilion g4                 | 1         | 2.7%    |
| HP Notebook                    | 1         | 2.7%    |
| HP Laptop 15q-bu1xx            | 1         | 2.7%    |
| HP Laptop 15-dy2xxx            | 1         | 2.7%    |
| HP Laptop 15-dw0xxx            | 1         | 2.7%    |
| Google Kindred                 | 1         | 2.7%    |
| Framework Laptop               | 1         | 2.7%    |
| eMachines eME730               | 1         | 2.7%    |
| Dell Vostro 3401               | 1         | 2.7%    |
| Dell Latitude E7250            | 1         | 2.7%    |
| Dell Latitude E6420            | 1         | 2.7%    |
| Dell Latitude E5420            | 1         | 2.7%    |
| Dell Latitude 5490             | 1         | 2.7%    |
| Dell Inspiron 7559             | 1         | 2.7%    |
| Dell Inspiron 3542             | 1         | 2.7%    |
| Chuwi GemiBook Pro             | 1         | 2.7%    |
| AXDIA International WINPAD V10 | 1         | 2.7%    |
| ASUS X441SA                    | 1         | 2.7%    |
| ASUS ROG Strix G513RC_G513RC   | 1         | 2.7%    |
| Apple MacBookAir4,1            | 1         | 2.7%    |
| Apple MacBook4,1               | 1         | 2.7%    |
| Acer Swift SF113-31            | 1         | 2.7%    |
| Acer Aspire E5-573             | 1         | 2.7%    |
| Unknown                        | 1         | 2.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Dell Latitude              | 4         | 10.81%  |
| HP Pavilion                | 3         | 8.11%   |
| HP Laptop                  | 3         | 8.11%   |
| Dell Inspiron              | 2         | 5.41%   |
| Positivo CHT14B            | 1         | 2.7%    |
| MSI Katana                 | 1         | 2.7%    |
| MSI GL65                   | 1         | 2.7%    |
| MSI GF63                   | 1         | 2.7%    |
| MSI Alpha                  | 1         | 2.7%    |
| Lenovo ThinkPad            | 1         | 2.7%    |
| Infinix INBook             | 1         | 2.7%    |
| HUAWEI NBD-WXX9            | 1         | 2.7%    |
| HUAWEI HLYL-WXX9           | 1         | 2.7%    |
| HUAWEI BOHB-WAX9           | 1         | 2.7%    |
| HP Stream                  | 1         | 2.7%    |
| HP Notebook                | 1         | 2.7%    |
| Google Kindred             | 1         | 2.7%    |
| Framework Laptop           | 1         | 2.7%    |
| eMachines eME730           | 1         | 2.7%    |
| Dell Vostro                | 1         | 2.7%    |
| Chuwi GemiBook             | 1         | 2.7%    |
| AXDIA International WINPAD | 1         | 2.7%    |
| ASUS X441SA                | 1         | 2.7%    |
| ASUS ROG                   | 1         | 2.7%    |
| Apple MacBookAir4          | 1         | 2.7%    |
| Apple MacBook4             | 1         | 2.7%    |
| Acer Swift                 | 1         | 2.7%    |
| Acer Aspire                | 1         | 2.7%    |
| Unknown                    | 1         | 2.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 11        | 29.73%  |
| 2020 | 4         | 10.81%  |
| 2011 | 4         | 10.81%  |
| 2017 | 3         | 8.11%   |
| 2014 | 3         | 8.11%   |
| 2018 | 2         | 5.41%   |
| 2016 | 2         | 5.41%   |
| 2015 | 2         | 5.41%   |
| 2012 | 2         | 5.41%   |
| 2022 | 1         | 2.7%    |
| 2019 | 1         | 2.7%    |
| 2010 | 1         | 2.7%    |
| 2008 | 1         | 2.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 37        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 37        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 36        | 97.3%   |
| Yes  | 1         | 2.7%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 10        | 27.03%  |
| 3.01-4.0   | 8         | 21.62%  |
| 8.01-16.0  | 7         | 18.92%  |
| 16.01-24.0 | 5         | 13.51%  |
| 32.01-64.0 | 3         | 8.11%   |
| 1.01-2.0   | 3         | 8.11%   |
| 24.01-32.0 | 1         | 2.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 15        | 39.47%  |
| 2.01-3.0 | 11        | 28.95%  |
| 4.01-8.0 | 5         | 13.16%  |
| 3.01-4.0 | 4         | 10.53%  |
| 0.51-1.0 | 3         | 7.89%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 23        | 62.16%  |
| 2      | 13        | 35.14%  |
| 3      | 1         | 2.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 29        | 78.38%  |
| Yes       | 8         | 21.62%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 64.86%  |
| No        | 13        | 35.14%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 94.74%  |
| No        | 2         | 5.26%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 81.08%  |
| No        | 7         | 18.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| India              | 5         | 13.51%  |
| USA                | 4         | 10.81%  |
| Mexico             | 4         | 10.81%  |
| Uruguay            | 2         | 5.41%   |
| UK                 | 2         | 5.41%   |
| Spain              | 2         | 5.41%   |
| South Africa       | 2         | 5.41%   |
| Malaysia           | 2         | 5.41%   |
| Vietnam            | 1         | 2.7%    |
| Turkey             | 1         | 2.7%    |
| Thailand           | 1         | 2.7%    |
| Russia             | 1         | 2.7%    |
| Philippines        | 1         | 2.7%    |
| Italy              | 1         | 2.7%    |
| Indonesia          | 1         | 2.7%    |
| France             | 1         | 2.7%    |
| Finland            | 1         | 2.7%    |
| Dominican Republic | 1         | 2.7%    |
| Brazil             | 1         | 2.7%    |
| Belarus            | 1         | 2.7%    |
| Austria            | 1         | 2.7%    |
| Argentina          | 1         | 2.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Seremban           | 2         | 5.26%   |
| New Delhi          | 2         | 5.26%   |
| Montevideo         | 2         | 5.26%   |
| Cape Town          | 2         | 5.26%   |
| Welwyn Garden City | 1         | 2.63%   |
| Vienna             | 1         | 2.63%   |
| Valencia           | 1         | 2.63%   |
| Torreón           | 1         | 2.63%   |
| Tirunelveli        | 1         | 2.63%   |
| Stevens Point      | 1         | 2.63%   |
| Sao Paulo          | 1         | 2.63%   |
| Santo Domingo Este | 1         | 2.63%   |
| Santa Rosa         | 1         | 2.63%   |
| Rocca di Papa      | 1         | 2.63%   |
| Monterrey          | 1         | 2.63%   |
| Mazatlán          | 1         | 2.63%   |
| Mar del Plata      | 1         | 2.63%   |
| Mangalore          | 1         | 2.63%   |
| Malang             | 1         | 2.63%   |
| Madrid             | 1         | 2.63%   |
| Loskutova          | 1         | 2.63%   |
| London             | 1         | 2.63%   |
| Lannion            | 1         | 2.63%   |
| Jorge Negrete      | 1         | 2.63%   |
| Istanbul           | 1         | 2.63%   |
| Helsinki           | 1         | 2.63%   |
| Hanoi              | 1         | 2.63%   |
| Gebze              | 1         | 2.63%   |
| Clifton Park       | 1         | 2.63%   |
| Bhubaneswar        | 1         | 2.63%   |
| Bangkok            | 1         | 2.63%   |
| Babruysk           | 1         | 2.63%   |
| Austin             | 1         | 2.63%   |
| Arlington          | 1         | 2.63%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Unknown                     | 6         | 12     | 12.77%  |
| WDC                         | 5         | 5      | 10.64%  |
| Seagate                     | 3         | 4      | 6.38%   |
| Sandisk                     | 3         | 3      | 6.38%   |
| Samsung Electronics         | 3         | 3      | 6.38%   |
| Phison Electronics          | 3         | 3      | 6.38%   |
| Toshiba                     | 2         | 2      | 4.26%   |
| SK hynix                    | 2         | 2      | 4.26%   |
| KIOXIA                      | 2         | 2      | 4.26%   |
| Hitachi                     | 2         | 2      | 4.26%   |
| Unknown                     | 2         | 2      | 4.26%   |
| Yangtze Memory Technologies | 1         | 1      | 2.13%   |
| Phison                      | 1         | 1      | 2.13%   |
| Netac                       | 1         | 1      | 2.13%   |
| Mushkin                     | 1         | 2      | 2.13%   |
| Micron/Crucial Technology   | 1         | 1      | 2.13%   |
| Kingston Technology Company | 1         | 2      | 2.13%   |
| Kingston                    | 1         | 1      | 2.13%   |
| KingFast                    | 1         | 2      | 2.13%   |
| Intel                       | 1         | 1      | 2.13%   |
| Initio                      | 1         | 1      | 2.13%   |
| HGST                        | 1         | 1      | 2.13%   |
| Gigabyte Technology         | 1         | 2      | 2.13%   |
| Crucial                     | 1         | 1      | 2.13%   |
| Apple                       | 1         | 1      | 2.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                              | 2         | 3.85%   |
| Seagate ST500LM030-2E717D 500GB                     | 2         | 3.85%   |
| Phison PS5013 E13 NVMe Controller 512GB             | 2         | 3.85%   |
| Unknown                                             | 2         | 3.85%   |
| Yangtze Memory YMTC PC005 256GB                     | 1         | 1.92%   |
| WDC WDS500G2B0C-00PXH0 500GB                        | 1         | 1.92%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1         | 1.92%   |
| WDC WD10SPZX-75Z10T3 1TB                            | 1         | 1.92%   |
| WDC WD10SPZX-24Z10T0 1TB                            | 1         | 1.92%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 1         | 1.92%   |
| Unknown SD/MMC/MS PRO 1GB                           | 1         | 1.92%   |
| Unknown SC128  128GB                                | 1         | 1.92%   |
| Unknown MMC Card  64GB                              | 1         | 1.92%   |
| Unknown MMC Card  16GB                              | 1         | 1.92%   |
| Unknown MMC Card  128GB                             | 1         | 1.92%   |
| Unknown Essentiel B 1TB                             | 1         | 1.92%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 1.92%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 1.92%   |
| SK hynix NVMe SSD Drive 128GB                       | 1         | 1.92%   |
| SK hynix HFS128G39TND-N210A 128GB SSD               | 1         | 1.92%   |
| Seagate ST1000LM048-2E7172 1TB                      | 1         | 1.92%   |
| Seagate Expansion 2TB                               | 1         | 1.92%   |
| Sandisk WD PC SN735 SDBPNHH-512G-1002 512GB         | 1         | 1.92%   |
| Sandisk WD Blue SN570 1TB                           | 1         | 1.92%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 512GB     | 1         | 1.92%   |
| Samsung SSD PM871 mSATA 256GB                       | 1         | 1.92%   |
| Samsung SSD 860 EVO 1TB                             | 1         | 1.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 1         | 1.92%   |
| Phison Sabrent Rocket 4.0 Plus 4TB                  | 1         | 1.92%   |
| Phison E16 PCIe4 NVMe Controller 1TB                | 1         | 1.92%   |
| Netac S535N8/256 256GB                              | 1         | 1.92%   |
| Mushkin MKNSSDPE500GB-D8                            | 1         | 1.92%   |
| Mushkin MKNSSDPE1TB-D8                              | 1         | 1.92%   |
| Micron/Crucial NVMe SSD Drive 2TB                   | 1         | 1.92%   |
| KIOXIA KBG40ZNV512G 512GB                           | 1         | 1.92%   |
| KIOXIA KBG40ZNV256G 256GB                           | 1         | 1.92%   |
| Kingston Company SNV2S1000G 1TB                     | 1         | 1.92%   |
| Kingston Company OM3PDP3 NVMe SSD 256GB             | 1         | 1.92%   |
| Kingston SA400S37480G 480GB SSD                     | 1         | 1.92%   |
| KingFast 240GB                                      | 1         | 1.92%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 21.43%  |
| Seagate | 3         | 4      | 21.43%  |
| Unknown | 2         | 3      | 14.29%  |
| Toshiba | 2         | 2      | 14.29%  |
| Hitachi | 2         | 2      | 14.29%  |
| Initio  | 1         | 1      | 7.14%   |
| HGST    | 1         | 1      | 7.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 18.18%  |
| Unknown             | 2         | 2      | 18.18%  |
| WDC                 | 1         | 1      | 9.09%   |
| SK hynix            | 1         | 1      | 9.09%   |
| Netac               | 1         | 1      | 9.09%   |
| Kingston            | 1         | 1      | 9.09%   |
| Intel               | 1         | 1      | 9.09%   |
| Gigabyte Technology | 1         | 2      | 9.09%   |
| Apple               | 1         | 1      | 9.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 16        | 19     | 34.78%  |
| HDD     | 13        | 16     | 28.26%  |
| SSD     | 11        | 12     | 23.91%  |
| MMC     | 5         | 9      | 10.87%  |
| Unknown | 1         | 2      | 2.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 21        | 25     | 45.65%  |
| NVMe | 16        | 19     | 34.78%  |
| MMC  | 5         | 9      | 10.87%  |
| SAS  | 4         | 5      | 8.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 16        | 18     | 61.54%  |
| 0.51-1.0   | 9         | 9      | 34.62%  |
| 1.01-2.0   | 1         | 1      | 3.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 12        | 32.43%  |
| 251-500        | 10        | 27.03%  |
| 501-1000       | 5         | 13.51%  |
| 1001-2000      | 3         | 8.11%   |
| 51-100         | 3         | 8.11%   |
| More than 3000 | 2         | 5.41%   |
| 21-50          | 1         | 2.7%    |
| Unknown        | 1         | 2.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 21-50    | 14        | 36.84%  |
| 1-20     | 9         | 23.68%  |
| 51-100   | 6         | 15.79%  |
| 251-500  | 3         | 7.89%   |
| 501-1000 | 3         | 7.89%   |
| 101-250  | 2         | 5.26%   |
| Unknown  | 1         | 2.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST1000LM048-2E7172 1TB | 1         | 1      | 33.33%  |
| Hitachi HTS545032A7E380 320GB  | 1         | 1      | 33.33%  |
| HGST HTS545050A7E680 500GB     | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 33.33%  |
| Hitachi | 1         | 1      | 33.33%  |
| HGST    | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 33.33%  |
| Hitachi | 1         | 1      | 33.33%  |
| HGST    | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 100%    |

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
| Works    | 24        | 31     | 60%     |
| Detected | 13        | 24     | 32.5%   |
| Malfunc  | 3         | 3      | 7.5%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 26        | 60.47%  |
| SanDisk                     | 4         | 9.3%    |
| Phison Electronics          | 3         | 6.98%   |
| Micron/Crucial Technology   | 2         | 4.65%   |
| KIOXIA                      | 2         | 4.65%   |
| Yangtze Memory Technologies | 1         | 2.33%   |
| SK hynix                    | 1         | 2.33%   |
| Silicon Motion              | 1         | 2.33%   |
| Samsung Electronics         | 1         | 2.33%   |
| Kingston Technology Company | 1         | 2.33%   |
| AMD                         | 1         | 2.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 8.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 3         | 6.52%   |
| Phison PS5013 E13 NVMe Controller                                                | 2         | 4.35%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 2         | 4.35%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 2         | 4.35%   |
| Intel Tiger Lake SATA AHCI Controller                                            | 2         | 4.35%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 4.35%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 4.35%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 4.35%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 4.35%   |
| Yangtze Memory PC005 NVMe SSD                                                    | 1         | 2.17%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 2.17%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 2.17%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                               | 1         | 2.17%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 2.17%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 2.17%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                            | 1         | 2.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 2.17%   |
| Phison E18 PCIe4 NVMe Controller                                                 | 1         | 2.17%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 2.17%   |
| Kingston Company Company Non-Volatile memory controller                          | 1         | 2.17%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 1         | 2.17%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 2.17%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 2.17%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 2.17%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 2.17%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 2.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 2.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 2.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 2.17%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 1         | 2.17%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 2.17%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 1         | 2.17%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 22        | 50%     |
| NVMe | 16        | 36.36%  |
| RAID | 5         | 11.36%  |
| IDE  | 1         | 2.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 32        | 86.49%  |
| AMD    | 5         | 13.51%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz         | 2         | 5.41%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz   | 2         | 5.41%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz   | 2         | 5.41%   |
| Intel Pentium CPU N4200 @ 1.10GHz         | 1         | 2.7%    |
| Intel Core i7-8565U CPU @ 1.80GHz         | 1         | 2.7%    |
| Intel Core i7-8550U CPU @ 1.80GHz         | 1         | 2.7%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz        | 1         | 2.7%    |
| Intel Core i7-4510U CPU @ 2.00GHz         | 1         | 2.7%    |
| Intel Core i7-10750H CPU @ 2.60GHz        | 1         | 2.7%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz        | 1         | 2.7%    |
| Intel Core i5-5300U CPU @ 2.30GHz         | 1         | 2.7%    |
| Intel Core i5-3320M CPU @ 2.60GHz         | 1         | 2.7%    |
| Intel Core i5-2540M CPU @ 2.60GHz         | 1         | 2.7%    |
| Intel Core i5-2467M CPU @ 1.60GHz         | 1         | 2.7%    |
| Intel Core i5-10300H CPU @ 2.50GHz        | 1         | 2.7%    |
| Intel Core i5-10210U CPU @ 1.60GHz        | 1         | 2.7%    |
| Intel Core i3-5005U CPU @ 2.00GHz         | 1         | 2.7%    |
| Intel Core i3-2310M CPU @ 2.10GHz         | 1         | 2.7%    |
| Intel Core i3-10110U CPU @ 2.10GHz        | 1         | 2.7%    |
| Intel Core i3-1005G1 CPU @ 1.20GHz        | 1         | 2.7%    |
| Intel Core i3 CPU M 350 @ 2.27GHz         | 1         | 2.7%    |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz      | 1         | 2.7%    |
| Intel Celeron N4020 CPU @ 1.10GHz         | 1         | 2.7%    |
| Intel Celeron J4125 CPU @ 2.00GHz         | 1         | 2.7%    |
| Intel Celeron CPU N3060 @ 1.60GHz         | 1         | 2.7%    |
| Intel Celeron 2957U @ 1.40GHz             | 1         | 2.7%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz         | 1         | 2.7%    |
| Intel Atom CPU Z3735F @ 1.33GHz           | 1         | 2.7%    |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz   | 1         | 2.7%    |
| AMD Ryzen 7 6800H with Radeon Graphics    | 1         | 2.7%    |
| AMD Ryzen 7 5800H with Radeon Graphics    | 1         | 2.7%    |
| AMD Ryzen 5 4600H with Radeon Graphics    | 1         | 2.7%    |
| AMD Ryzen 5 4500U with Radeon Graphics    | 1         | 2.7%    |
| AMD A4-3330MX APU with Radeon HD Graphics | 1         | 2.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 8         | 21.62%  |
| Intel Core i7    | 6         | 16.22%  |
| Other            | 5         | 13.51%  |
| Intel Core i3    | 5         | 13.51%  |
| Intel Celeron    | 4         | 10.81%  |
| Intel Atom       | 2         | 5.41%   |
| AMD Ryzen 7      | 2         | 5.41%   |
| AMD Ryzen 5      | 2         | 5.41%   |
| Intel Pentium    | 1         | 2.7%    |
| Intel Core 2 Duo | 1         | 2.7%    |
| AMD A4           | 1         | 2.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 16        | 43.24%  |
| 4      | 14        | 37.84%  |
| 8      | 4         | 10.81%  |
| 6      | 3         | 8.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 37        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 27        | 72.97%  |
| 1      | 10        | 27.03%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 37        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 17        | 45.95%  |
| 0xa0652    | 2         | 5.41%   |
| 0x806d1    | 2         | 5.41%   |
| 0x706a8    | 2         | 5.41%   |
| 0x206a7    | 2         | 5.41%   |
| 0x806ec    | 1         | 2.7%    |
| 0x806ea    | 1         | 2.7%    |
| 0x506e3    | 1         | 2.7%    |
| 0x506c9    | 1         | 2.7%    |
| 0x406c4    | 1         | 2.7%    |
| 0x40651    | 1         | 2.7%    |
| 0x306d4    | 1         | 2.7%    |
| 0x306a9    | 1         | 2.7%    |
| 0x0a404102 | 1         | 2.7%    |
| 0x08600106 | 1         | 2.7%    |
| 0x08600104 | 1         | 2.7%    |
| 0x03000027 | 1         | 2.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 6         | 16.22%  |
| IceLake       | 4         | 10.81%  |
| TigerLake     | 3         | 8.11%   |
| Silvermont    | 3         | 8.11%   |
| SandyBridge   | 3         | 8.11%   |
| Zen 2         | 2         | 5.41%   |
| Haswell       | 2         | 5.41%   |
| Goldmont plus | 2         | 5.41%   |
| CometLake     | 2         | 5.41%   |
| Broadwell     | 2         | 5.41%   |
| Zen 3         | 1         | 2.7%    |
| Westmere      | 1         | 2.7%    |
| Skylake       | 1         | 2.7%    |
| Penryn        | 1         | 2.7%    |
| K10 Llano     | 1         | 2.7%    |
| IvyBridge     | 1         | 2.7%    |
| Goldmont      | 1         | 2.7%    |
| Unknown       | 1         | 2.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 32        | 66.67%  |
| Nvidia | 9         | 18.75%  |
| AMD    | 7         | 14.58%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 3         | 6%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 6%      |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 4%      |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 4%      |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 4%      |
| Intel HD Graphics 5500                                                                   | 2         | 4%      |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 4%      |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 4%      |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 4%      |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 4%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 4%      |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 4%      |
| AMD Renoir                                                                               | 2         | 4%      |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 2%      |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 2%      |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 2%      |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 2%      |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 2%      |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 2%      |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 2%      |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 2%      |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 1         | 2%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 2%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 2%      |
| Intel Iris Plus Graphics G7                                                              | 1         | 2%      |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 2%      |
| Intel HD Graphics 530                                                                    | 1         | 2%      |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 2%      |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 2%      |
| Intel Apollo Lake [HD Graphics 505]                                                      | 1         | 2%      |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 2%      |
| AMD Sumo [Radeon HD 6480G]                                                               | 1         | 2%      |
| AMD Rembrandt [Radeon 680M]                                                              | 1         | 2%      |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 1         | 2%      |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 1         | 2%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 22        | 59.46%  |
| Intel + Nvidia | 8         | 21.62%  |
| 1 x AMD        | 3         | 8.11%   |
| Intel + AMD    | 2         | 5.41%   |
| 2 x AMD        | 1         | 2.7%    |
| AMD + Nvidia   | 1         | 2.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 29        | 78.38%  |
| Proprietary | 8         | 21.62%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 83.78%  |
| 0.01-0.5   | 4         | 10.81%  |
| 7.01-8.0   | 1         | 2.7%    |
| 5.01-6.0   | 1         | 2.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Chimei Innolux      | 10        | 25%     |
| BOE                 | 7         | 17.5%   |
| LG Display          | 6         | 15%     |
| AU Optronics        | 6         | 15%     |
| Samsung Electronics | 3         | 7.5%    |
| PANDA               | 2         | 5%      |
| Apple               | 2         | 5%      |
| Lenovo              | 1         | 2.5%    |
| HJC                 | 1         | 2.5%    |
| Dell                | 1         | 2.5%    |
| ASUSTek Computer    | 1         | 2.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch          | 2         | 5%      |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch          | 2         | 5%      |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 2         | 5%      |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch    | 1         | 2.5%    |
| Samsung Electronics LCD Monitor SEC335A 1366x768 309x174mm 14.0-inch | 1         | 2.5%    |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch | 1         | 2.5%    |
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch              | 1         | 2.5%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 1         | 2.5%    |
| LG Display LCD Monitor LGD04B9 1920x1080 344x194mm 15.5-inch         | 1         | 2.5%    |
| LG Display LCD Monitor LGD04B1 1366x768 310x174mm 14.0-inch          | 1         | 2.5%    |
| Lenovo LEN T2054pC LEN60D9 1440x900 419x262mm 19.5-inch              | 1         | 2.5%    |
| HJC LCD Monitor HJC003D 1920x1080 309x174mm 14.0-inch                | 1         | 2.5%    |
| Dell AW2518HF DELA101 1920x1080 540x300mm 24.3-inch                  | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 355x199mm 16.0-inch     | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN15E3 1920x1080 344x193mm 15.5-inch     | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN1541 1366x768 344x193mm 15.5-inch      | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 309x173mm 13.9-inch     | 1         | 2.5%    |
| Chimei Innolux LCD Monitor CMN1147 1366x768 256x144mm 11.6-inch      | 1         | 2.5%    |
| Chimei Innolux HJ140BB-02A CMN8C03 2160x1440 296x197mm 14.0-inch     | 1         | 2.5%    |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                | 1         | 2.5%    |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 1         | 2.5%    |
| BOE LCD Monitor BOE07FF 1920x1080 344x194mm 15.5-inch                | 1         | 2.5%    |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 1         | 2.5%    |
| BOE LCD Monitor BOE0644 1366x768 309x173mm 13.9-inch                 | 1         | 2.5%    |
| AU Optronics LCD Monitor AUOB78F 1920x1080 344x194mm 15.5-inch       | 1         | 2.5%    |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch       | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO80ED 1920x1080 344x193mm 15.5-inch       | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch        | 1         | 2.5%    |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 1         | 2.5%    |
| ASUSTek Computer VG245 AUS24A1 1920x1080 531x299mm 24.0-inch         | 1         | 2.5%    |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch               | 1         | 2.5%    |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                 | 1         | 2.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 18        | 45%     |
| 1366x768 (WXGA)  | 14        | 35%     |
| 2256x1504        | 2         | 5%      |
| 3840x2160 (4K)   | 1         | 2.5%    |
| 2560x1440 (QHD)  | 1         | 2.5%    |
| 2160x1440        | 1         | 2.5%    |
| 1600x900 (HD+)   | 1         | 2.5%    |
| 1440x900 (WXGA+) | 1         | 2.5%    |
| 1280x800 (WXGA)  | 1         | 2.5%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 17        | 42.5%   |
| 13     | 8         | 20%     |
| 14     | 7         | 17.5%   |
| 24     | 2         | 5%      |
| 11     | 2         | 5%      |
| 27     | 1         | 2.5%    |
| 19     | 1         | 2.5%    |
| 16     | 1         | 2.5%    |
| 12     | 1         | 2.5%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 27        | 67.5%   |
| 201-300     | 8         | 20%     |
| 501-600     | 2         | 5%      |
| 601-700     | 1         | 2.5%    |
| 401-500     | 1         | 2.5%    |
| 351-400     | 1         | 2.5%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 33        | 86.84%  |
| 3/2   | 3         | 7.89%   |
| 16/10 | 2         | 5.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 18        | 45%     |
| 81-90          | 14        | 35%     |
| 51-60          | 2         | 5%      |
| 71-80          | 1         | 2.5%    |
| 61-70          | 1         | 2.5%    |
| 301-350        | 1         | 2.5%    |
| 251-300        | 1         | 2.5%    |
| 201-250        | 1         | 2.5%    |
| 151-200        | 1         | 2.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 20        | 50%     |
| 101-120 | 12        | 30%     |
| 161-240 | 5         | 12.5%   |
| 51-100  | 3         | 7.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 33        | 89.19%  |
| 2     | 4         | 10.81%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 22        | 40%     |
| Intel                    | 17        | 30.91%  |
| Qualcomm Atheros         | 5         | 9.09%   |
| Ralink Technology        | 3         | 5.45%   |
| Broadcom                 | 3         | 5.45%   |
| MediaTek                 | 2         | 3.64%   |
| TP-Link                  | 1         | 1.82%   |
| Marvell Technology Group | 1         | 1.82%   |
| Broadcom Limited         | 1         | 1.82%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10        | 16.13%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 6.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 6.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 3.23%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 3.23%   |
| Ralink MT7601U Wireless Adapter                                   | 2         | 3.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 3.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 3.23%   |
| Intel Wireless 7265                                               | 2         | 3.23%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 3.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 3.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 3.23%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 3.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 3.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.23%   |
| TP-Link 802.11ac WLAN Adapter                                     | 1         | 1.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 1.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 1.61%   |
| Realtek 802.11ac NIC                                              | 1         | 1.61%   |
| Ralink RT5572 Wireless Adapter                                    | 1         | 1.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.61%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 1         | 1.61%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1         | 1.61%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.61%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 1.61%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.61%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 1         | 1.61%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.61%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.61%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 1.61%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.61%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 1.61%   |
| Broadcom BCM43225 802.11b/g/n                                     | 1         | 1.61%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 1         | 1.61%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 1         | 1.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 16        | 41.03%  |
| Realtek Semiconductor | 9         | 23.08%  |
| Qualcomm Atheros      | 5         | 12.82%  |
| Ralink Technology     | 3         | 7.69%   |
| Broadcom              | 3         | 7.69%   |
| MediaTek              | 2         | 5.13%   |
| TP-Link               | 1         | 2.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 4         | 10.26%  |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 2         | 5.13%   |
| Ralink MT7601U Wireless Adapter                               | 2         | 5.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 2         | 5.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 2         | 5.13%   |
| Intel Wireless 7265                                           | 2         | 5.13%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 2         | 5.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 2         | 5.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 2         | 5.13%   |
| Intel Comet Lake PCH CNVi WiFi                                | 2         | 5.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 2         | 5.13%   |
| TP-Link 802.11ac WLAN Adapter                                 | 1         | 2.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 1         | 2.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 1         | 2.56%   |
| Realtek 802.11ac NIC                                          | 1         | 2.56%   |
| Ralink RT5572 Wireless Adapter                                | 1         | 2.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 1         | 2.56%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 1         | 2.56%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 1         | 2.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 1         | 2.56%   |
| Intel Wi-Fi 6 AX201                                           | 1         | 2.56%   |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 1         | 2.56%   |
| Intel Centrino Ultimate-N 6300                                | 1         | 2.56%   |
| Broadcom BCM43225 802.11b/g/n                                 | 1         | 2.56%   |
| Broadcom BCM43224 802.11a/b/g/n                               | 1         | 2.56%   |
| Broadcom BCM4321 802.11a/b/g/n                                | 1         | 2.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 16        | 69.57%  |
| Intel                    | 4         | 17.39%  |
| Marvell Technology Group | 1         | 4.35%   |
| Broadcom Limited         | 1         | 4.35%   |
| Broadcom                 | 1         | 4.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10        | 43.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 17.39%  |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 8.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 8.7%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 4.35%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 4.35%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 4.35%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 4.35%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 4.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 36        | 61.02%  |
| Ethernet | 23        | 38.98%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 32        | 84.21%  |
| Ethernet | 6         | 15.79%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 21        | 56.76%  |
| 1     | 14        | 37.84%  |
| 0     | 2         | 5.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 22        | 59.46%  |
| Yes  | 15        | 40.54%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 13        | 43.33%  |
| Realtek Semiconductor           | 5         | 16.67%  |
| Qualcomm Atheros Communications | 3         | 10%     |
| Apple                           | 2         | 6.67%   |
| Realtek                         | 1         | 3.33%   |
| MediaTek                        | 1         | 3.33%   |
| Lite-On Technology              | 1         | 3.33%   |
| IMC Networks                    | 1         | 3.33%   |
| Foxconn / Hon Hai               | 1         | 3.33%   |
| Cambridge Silicon Radio         | 1         | 3.33%   |
| Broadcom                        | 1         | 3.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 7         | 23.33%  |
| Realtek Bluetooth Radio                             | 4         | 13.33%  |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 6.67%   |
| Intel Bluetooth wireless interface                  | 2         | 6.67%   |
| Intel Bluetooth Device                              | 2         | 6.67%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 3.33%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 3.33%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 3.33%   |
| MediaTek Wireless_Device                            | 1         | 3.33%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 3.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 3.33%   |
| Intel AX210 Bluetooth                               | 1         | 3.33%   |
| IMC Networks Bluetooth Device                       | 1         | 3.33%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 3.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.33%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 3.33%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 3.33%   |
| Apple Bluetooth HCI                                 | 1         | 3.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 30        | 76.92%  |
| AMD    | 5         | 12.82%  |
| Nvidia | 4         | 10.26%  |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 4         | 8.51%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 6.38%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 6.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 6.38%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 6.38%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 4.26%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 4.26%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 4.26%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 4.26%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 4.26%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 4.26%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 4.26%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 4.26%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 4.26%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 2.13%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 2.13%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 2.13%   |
| Nvidia Audio device                                                                               | 1         | 2.13%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 2.13%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 2.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.13%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 2.13%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1         | 2.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 2.13%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 2.13%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 1         | 2.13%   |
| AMD FCH Azalia Controller                                                                         | 1         | 2.13%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 10        | 27.03%  |
| SK hynix            | 8         | 21.62%  |
| Micron Technology   | 6         | 16.22%  |
| Kingston            | 5         | 13.51%  |
| Crucial             | 3         | 8.11%   |
| Unknown (ABCD)      | 1         | 2.7%    |
| Unknown             | 1         | 2.7%    |
| Nanya Technology    | 1         | 2.7%    |
| ChangXin Memory     | 1         | 2.7%    |
| Unknown             | 1         | 2.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 5%      |
| Kingston RAM KF2933C17S4/16G 16GB SODIMM DDR4 2933MT/s           | 2         | 5%      |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 2.5%    |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 1         | 2.5%    |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.5%    |
| SK hynix RAM HMT451S6CFR6A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 2.5%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.5%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 2.5%    |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.5%    |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s     | 1         | 2.5%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 2.5%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 2.5%    |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 2.5%    |
| Samsung RAM M474A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 1         | 2.5%    |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 1         | 2.5%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 2.5%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.5%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.5%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 2.5%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 2.5%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.5%    |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 1         | 2.5%    |
| Samsung RAM K4A8G165WC-BCTD 4GB Row Of Chips DDR4 2667MT/s       | 1         | 2.5%    |
| Nanya RAM Module 1GB SODIMM DDR2 667MT/s                         | 1         | 2.5%    |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s          | 1         | 2.5%    |
| Micron RAM Module 2GB SODIMM DDR3 1866MT/s                       | 1         | 2.5%    |
| Micron RAM K4A8G165WB-BCRC 8GB Row Of Chips LPDDR4 3333MT/s      | 1         | 2.5%    |
| Micron RAM 8KTF25664HZ-1G6M1 2GB SODIMM DDR3 1600MT/s            | 1         | 2.5%    |
| Micron RAM 4ATF51264HZ-3G2R1 4GB SODIMM DDR4 3200MT/s            | 1         | 2.5%    |
| Micron RAM 16ATF2G64HZ-2G3E1 16384MB SODIMM DDR4 2667MT/s        | 1         | 2.5%    |
| Kingston RAM KN2M64-ETB 8GB SODIMM DDR3 1600MT/s                 | 1         | 2.5%    |
| Kingston RAM ACR16D3LS1KNG/4G 4GB SODIMM DDR3 1600MT/s           | 1         | 2.5%    |
| Kingston RAM 9905625-004.A03LF 16GB SODIMM DDR4 3200MT/s         | 1         | 2.5%    |
| Crucial RAM CT8G4SFRA32A.C8FP 8192MB SODIMM DDR4 3200MT/s        | 1         | 2.5%    |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 1         | 2.5%    |
| Crucial RAM BL16G32C16S4B.16FE 16GB SODIMM DDR4 3200MT/s         | 1         | 2.5%    |
| ChangXin Memory RAM DB4ABAM-MK 1GB Row Of Chips LPDDR4 3733MT/s  | 1         | 2.5%    |
| Unknown                                                          | 1         | 2.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 15        | 46.88%  |
| DDR3   | 12        | 37.5%   |
| LPDDR4 | 3         | 9.38%   |
| DDR5   | 1         | 3.13%   |
| DDR2   | 1         | 3.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 27        | 87.1%   |
| Row Of Chips | 4         | 12.9%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 12        | 34.29%  |
| 4096  | 9         | 25.71%  |
| 16384 | 7         | 20%     |
| 2048  | 5         | 14.29%  |
| 1024  | 2         | 5.71%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 8         | 22.22%  |
| 2667  | 7         | 19.44%  |
| 3200  | 6         | 16.67%  |
| 1333  | 4         | 11.11%  |
| 2933  | 2         | 5.56%   |
| 4800  | 1         | 2.78%   |
| 3733  | 1         | 2.78%   |
| 3333  | 1         | 2.78%   |
| 2400  | 1         | 2.78%   |
| 2133  | 1         | 2.78%   |
| 1866  | 1         | 2.78%   |
| 1334  | 1         | 2.78%   |
| 1067  | 1         | 2.78%   |
| 667   | 1         | 2.78%   |

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
| Chicony Electronics                    | 7         | 24.14%  |
| Microdia                               | 4         | 13.79%  |
| Bison Electronics                      | 3         | 10.34%  |
| Realtek Semiconductor                  | 2         | 6.9%    |
| Quanta                                 | 2         | 6.9%    |
| IMC Networks                           | 2         | 6.9%    |
| Cheng Uei Precision Industry (Foxlink) | 2         | 6.9%    |
| Apple                                  | 2         | 6.9%    |
| Suyin                                  | 1         | 3.45%   |
| Sunplus Innovation Technology          | 1         | 3.45%   |
| Ricoh                                  | 1         | 3.45%   |
| Luxvisions Innotech Limited            | 1         | 3.45%   |
| Alcor Micro                            | 1         | 3.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                   | 3         | 10.34%  |
| Quanta ov9734_techfront_camera                                  | 2         | 6.9%    |
| Bison HD Webcam                                                 | 2         | 6.9%    |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)     | 1         | 3.45%   |
| Sunplus Integrated_Webcam_HD                                    | 1         | 3.45%   |
| Ricoh Laptop_Integrated_Webcam_FHD                              | 1         | 3.45%   |
| Realtek HP Webcam                                               | 1         | 3.45%   |
| Realtek HD Webcam - Realtek                                     | 1         | 3.45%   |
| Microdia Webcam Vitade AF                                       | 1         | 3.45%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 1         | 3.45%   |
| IMC Networks HP TrueVision HD Camera                            | 1         | 3.45%   |
| IMC Networks HD Camera                                          | 1         | 3.45%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 1         | 3.45%   |
| Chicony Integrated IR Camera                                    | 1         | 3.45%   |
| Chicony Integrated HD WebCam                                    | 1         | 3.45%   |
| Chicony HP Wide Vision HD Camera                                | 1         | 3.45%   |
| Chicony HP Truevision HD                                        | 1         | 3.45%   |
| Chicony HD Webcam                                               | 1         | 3.45%   |
| Chicony HD User Facing                                          | 1         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 1         | 3.45%   |
| Bison Integrated Camera                                         | 1         | 3.45%   |
| Apple FaceTime Camera                                           | 1         | 3.45%   |
| Apple Built-in iSight [Micron]                                  | 1         | 3.45%   |
| Alcor Micro USB 2.0 PC cam                                      | 1         | 3.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 2         | 40%     |
| Elan Microelectronics      | 2         | 40%     |
| LighTuning Technology      | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Elan ELAN:ARM-M4                            | 2         | 40%     |
| Shenzhen Goodix  Fingerprint Device         | 1         | 20%     |
| Shenzhen Goodix Fingerprint Reader          | 1         | 20%     |
| LighTuning EgisTec Touch Fingerprint Sensor | 1         | 20%     |

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


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 26        | 70.27%  |
| 1     | 9         | 24.32%  |
| 2     | 2         | 5.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 5         | 38.46%  |
| Storage               | 2         | 15.38%  |
| Net/wireless          | 2         | 15.38%  |
| Graphics card         | 2         | 15.38%  |
| Multimedia controller | 1         | 7.69%   |
| Chipcard              | 1         | 7.69%   |

