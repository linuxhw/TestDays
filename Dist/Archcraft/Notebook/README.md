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

Total: 42

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| HUAWEI    | NBD-WXX9                    | [61c1703e67](https://linux-hardware.org/?probe=61c1703e67) | Jun 10, 2023 |
| HUAWEI    | NBD-WXX9                    | [321ad38786](https://linux-hardware.org/?probe=321ad38786) | Jun 10, 2023 |
| HUAWEI    | BOHB-WAX9                   | [08eb3979f4](https://linux-hardware.org/?probe=08eb3979f4) | May 19, 2023 |
| Dell      | Latitude 5490               | [2ce70b7a2c](https://linux-hardware.org/?probe=2ce70b7a2c) | May 04, 2023 |
| ASUSTek   | ROG Strix G513RC_G513RC     | [eeef579322](https://linux-hardware.org/?probe=eeef579322) | Apr 28, 2023 |
| MSI       | Alpha 15 B5EEK              | [c7f5eaf3f1](https://linux-hardware.org/?probe=c7f5eaf3f1) | Mar 28, 2023 |
| eMachines | eME730                      | [0e1683ee34](https://linux-hardware.org/?probe=0e1683ee34) | Mar 08, 2023 |
| eMachines | eME730                      | [db15f88805](https://linux-hardware.org/?probe=db15f88805) | Mar 08, 2023 |
| MSI       | Katana GF66 11UE            | [aead8d4d18](https://linux-hardware.org/?probe=aead8d4d18) | Jan 26, 2023 |
| HP        | Stream Laptop 11-ak0xxx     | [6f3b4fc131](https://linux-hardware.org/?probe=6f3b4fc131) | Jan 16, 2023 |
| HP        | Stream Laptop 11-ak0xxx     | [b33bedc4c2](https://linux-hardware.org/?probe=b33bedc4c2) | Jan 15, 2023 |
| HP        | Stream Laptop 11-ak0xxx     | [806da9b386](https://linux-hardware.org/?probe=806da9b386) | Jan 12, 2023 |
| HP        | Stream Laptop 11-ak0xxx     | [29e6fcfd32](https://linux-hardware.org/?probe=29e6fcfd32) | Jan 12, 2023 |
| Dell      | Inspiron 7559               | [52cf8ddc0f](https://linux-hardware.org/?probe=52cf8ddc0f) | Dec 22, 2022 |
| HP        | Stream Laptop 11-ak0xxx     | [d2c04dd7cd](https://linux-hardware.org/?probe=d2c04dd7cd) | Dec 01, 2022 |
| Chuwi     | GemiBook Pro                | [315d8b6ff7](https://linux-hardware.org/?probe=315d8b6ff7) | Nov 08, 2022 |
| MSI       | GF63 Thin 10SC              | [2b22722ce8](https://linux-hardware.org/?probe=2b22722ce8) | Oct 27, 2022 |
| Dell      | Latitude E6420              | [3ea84baba3](https://linux-hardware.org/?probe=3ea84baba3) | Sep 09, 2022 |
| Dell      | Latitude E6420              | [78fd24b713](https://linux-hardware.org/?probe=78fd24b713) | Sep 09, 2022 |
| Apple     | MacBook4,1                  | [500d050ad6](https://linux-hardware.org/?probe=500d050ad6) | Sep 06, 2022 |
| Apple     | MacBook4,1                  | [01b8531ddf](https://linux-hardware.org/?probe=01b8531ddf) | Sep 04, 2022 |
| Apple     | MacBook4,1                  | [9e4c1bc292](https://linux-hardware.org/?probe=9e4c1bc292) | Sep 04, 2022 |
| HP        | Notebook                    | [b0b97c0ea3](https://linux-hardware.org/?probe=b0b97c0ea3) | Aug 30, 2022 |
| HP        | Laptop 15-dw0xxx            | [8bb62c2062](https://linux-hardware.org/?probe=8bb62c2062) | Aug 24, 2022 |
| ASUSTek   | X441SA                      | [cb26c73037](https://linux-hardware.org/?probe=cb26c73037) | Aug 16, 2022 |
| Acer      | Swift SF113-31              | [1c4298ff33](https://linux-hardware.org/?probe=1c4298ff33) | Aug 08, 2022 |
| Acer      | Swift SF113-31              | [0f1ad8ccf7](https://linux-hardware.org/?probe=0f1ad8ccf7) | Aug 08, 2022 |
| Dell      | Latitude E7250              | [2dd83a16c7](https://linux-hardware.org/?probe=2dd83a16c7) | Aug 01, 2022 |
| Acer      | Aspire E5-573               | [01f3150f60](https://linux-hardware.org/?probe=01f3150f60) | Jul 01, 2022 |
| Positivo  | CHT14B                      | [95566d3625](https://linux-hardware.org/?probe=95566d3625) | Jun 05, 2022 |
| Framework | Laptop                      | [f8790adbf2](https://linux-hardware.org/?probe=f8790adbf2) | May 25, 2022 |
| Standard  | Unknown                     | [74971ae227](https://linux-hardware.org/?probe=74971ae227) | May 04, 2022 |
| HP        | Pavilion Laptop 15-eh0xx... | [c8c2ede566](https://linux-hardware.org/?probe=c8c2ede566) | Feb 11, 2022 |
| Dell      | Inspiron 3542               | [f3f3b08d89](https://linux-hardware.org/?probe=f3f3b08d89) | Feb 09, 2022 |
| Dell      | Inspiron 3542               | [e975782c15](https://linux-hardware.org/?probe=e975782c15) | Jan 31, 2022 |
| Lenovo    | ThinkPad T430 2351AK9       | [19f50b09d5](https://linux-hardware.org/?probe=19f50b09d5) | Jan 21, 2022 |
| Apple     | MacBookAir4,1               | [ecc4515014](https://linux-hardware.org/?probe=ecc4515014) | Nov 01, 2021 |
| Google    | Kindred                     | [c2631a9488](https://linux-hardware.org/?probe=c2631a9488) | Jul 29, 2021 |
| HP        | Laptop 15q-bu1xx            | [af9f2a95ec](https://linux-hardware.org/?probe=af9f2a95ec) | Jun 28, 2021 |
| HP        | Pavilion Laptop 15-cc1xx    | [5e0e7e2b80](https://linux-hardware.org/?probe=5e0e7e2b80) | Jun 25, 2021 |
| HP        | Pavilion g4                 | [6a3471480a](https://linux-hardware.org/?probe=6a3471480a) | May 29, 2021 |
| MSI       | GL65 Leopard 10SFK          | [a9e5bb7556](https://linux-hardware.org/?probe=a9e5bb7556) | May 28, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Archcraft Rolling | 25        | 80.65%  |
| Archcraft         | 6         | 19.35%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| Archcraft | 31        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 6.2.13-arch1-1         | 2         | 6.06%   |
| 5.18.16-arch1-1        | 2         | 6.06%   |
| 5.12.7-arch1-1         | 2         | 6.06%   |
| 6.3.6-arch1-1          | 1         | 3.03%   |
| 6.2.8-zen1-1-zen       | 1         | 3.03%   |
| 6.2.2-arch1-1          | 1         | 3.03%   |
| 6.2.12-arch1-1         | 1         | 3.03%   |
| 6.1.7-arch1-1          | 1         | 3.03%   |
| 6.1.4-x64v1-xanmod1-1  | 1         | 3.03%   |
| 6.1.1-arch1-1          | 1         | 3.03%   |
| 6.0.7-arch1-1          | 1         | 3.03%   |
| 6.0.2-arch1-1          | 1         | 3.03%   |
| 6.0.10-x64v1-xanmod1-1 | 1         | 3.03%   |
| 5.19.7-arch1-1         | 1         | 3.03%   |
| 5.19.6-arch1-1         | 1         | 3.03%   |
| 5.19.3-arch1-1         | 1         | 3.03%   |
| 5.18.6-arch1-1         | 1         | 3.03%   |
| 5.18.14-zen1-1-zen     | 1         | 3.03%   |
| 5.17.9-arch1-1         | 1         | 3.03%   |
| 5.17.6-arch1-1         | 1         | 3.03%   |
| 5.17.5-arch1-1         | 1         | 3.03%   |
| 5.16.8-arch1-1         | 1         | 3.03%   |
| 5.16.7-arch1-1         | 1         | 3.03%   |
| 5.16.4-arch1-1         | 1         | 3.03%   |
| 5.16.1-arch1-1         | 1         | 3.03%   |
| 5.15.43-1-lts          | 1         | 3.03%   |
| 5.14.15-arch1-1        | 1         | 3.03%   |
| 5.12.9-arch1-1         | 1         | 3.03%   |
| 5.12.12-arch1-1        | 1         | 3.03%   |
| 5.10.54-1-lts          | 1         | 3.03%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2.13  | 2         | 6.06%   |
| 5.18.16 | 2         | 6.06%   |
| 5.12.7  | 2         | 6.06%   |
| 6.3.6   | 1         | 3.03%   |
| 6.2.8   | 1         | 3.03%   |
| 6.2.2   | 1         | 3.03%   |
| 6.2.12  | 1         | 3.03%   |
| 6.1.7   | 1         | 3.03%   |
| 6.1.4   | 1         | 3.03%   |
| 6.1.1   | 1         | 3.03%   |
| 6.0.7   | 1         | 3.03%   |
| 6.0.2   | 1         | 3.03%   |
| 6.0.10  | 1         | 3.03%   |
| 5.19.7  | 1         | 3.03%   |
| 5.19.6  | 1         | 3.03%   |
| 5.19.3  | 1         | 3.03%   |
| 5.18.6  | 1         | 3.03%   |
| 5.18.14 | 1         | 3.03%   |
| 5.17.9  | 1         | 3.03%   |
| 5.17.6  | 1         | 3.03%   |
| 5.17.5  | 1         | 3.03%   |
| 5.16.8  | 1         | 3.03%   |
| 5.16.7  | 1         | 3.03%   |
| 5.16.4  | 1         | 3.03%   |
| 5.16.1  | 1         | 3.03%   |
| 5.15.43 | 1         | 3.03%   |
| 5.14.15 | 1         | 3.03%   |
| 5.12.9  | 1         | 3.03%   |
| 5.12.12 | 1         | 3.03%   |
| 5.10.54 | 1         | 3.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2     | 5         | 15.63%  |
| 5.18    | 4         | 12.5%   |
| 5.12    | 4         | 12.5%   |
| 6.1     | 3         | 9.38%   |
| 6.0     | 3         | 9.38%   |
| 5.19    | 3         | 9.38%   |
| 5.17    | 3         | 9.38%   |
| 5.16    | 3         | 9.38%   |
| 6.3     | 1         | 3.13%   |
| 5.15    | 1         | 3.13%   |
| 5.14    | 1         | 3.13%   |
| 5.10    | 1         | 3.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 31        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| openbox  | 13        | 41.94%  |
| XFCE     | 7         | 22.58%  |
| bspwm    | 4         | 12.9%   |
| GNOME    | 2         | 6.45%   |
| sway     | 1         | 3.23%   |
| LXDE     | 1         | 3.23%   |
| i3       | 1         | 3.23%   |
| Hyprland | 1         | 3.23%   |
| Unknown  | 1         | 3.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 29        | 93.55%  |
| Wayland | 2         | 6.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 19        | 61.29%  |
| Unknown | 6         | 19.35%  |
| LXDM    | 5         | 16.13%  |
| Ly      | 1         | 3.23%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 15        | 48.39%  |
| es_MX | 3         | 9.68%   |
| en_ZA | 2         | 6.45%   |
| en_IN | 2         | 6.45%   |
| tr_TR | 1         | 3.23%   |
| pl_PL | 1         | 3.23%   |
| it_IT | 1         | 3.23%   |
| fr_FR | 1         | 3.23%   |
| es_ES | 1         | 3.23%   |
| en_SG | 1         | 3.23%   |
| en_PH | 1         | 3.23%   |
| en_GB | 1         | 3.23%   |
| de_AT | 1         | 3.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 22        | 70.97%  |
| BIOS | 9         | 29.03%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Ext4  | 26        | 83.87%  |
| Btrfs | 5         | 16.13%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 22        | 70.97%  |
| Unknown | 5         | 16.13%  |
| MBR     | 4         | 12.9%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 27        | 87.1%   |
| Yes       | 4         | 12.9%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 20        | 64.52%  |
| Yes       | 11        | 35.48%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 7         | 22.58%  |
| Dell             | 5         | 16.13%  |
| MSI              | 4         | 12.9%   |
| HUAWEI           | 2         | 6.45%   |
| ASUSTek Computer | 2         | 6.45%   |
| Apple            | 2         | 6.45%   |
| Acer             | 2         | 6.45%   |
| Standard         | 1         | 3.23%   |
| Positivo         | 1         | 3.23%   |
| Lenovo           | 1         | 3.23%   |
| Google           | 1         | 3.23%   |
| Framework        | 1         | 3.23%   |
| eMachines        | 1         | 3.23%   |
| Chuwi            | 1         | 3.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Positivo CHT14B              | 1         | 3.23%   |
| MSI Katana GF66 11UE         | 1         | 3.23%   |
| MSI GL65 Leopard 10SFK       | 1         | 3.23%   |
| MSI GF63 Thin 10SC           | 1         | 3.23%   |
| MSI Alpha 15 B5EEK           | 1         | 3.23%   |
| Lenovo ThinkPad T430 2351AK9 | 1         | 3.23%   |
| HUAWEI NBD-WXX9              | 1         | 3.23%   |
| HUAWEI BOHB-WAX9             | 1         | 3.23%   |
| HP Stream Laptop 11-ak0xxx   | 1         | 3.23%   |
| HP Pavilion Laptop 15-eh0xxx | 1         | 3.23%   |
| HP Pavilion Laptop 15-cc1xx  | 1         | 3.23%   |
| HP Pavilion g4               | 1         | 3.23%   |
| HP Notebook                  | 1         | 3.23%   |
| HP Laptop 15q-bu1xx          | 1         | 3.23%   |
| HP Laptop 15-dw0xxx          | 1         | 3.23%   |
| Google Kindred               | 1         | 3.23%   |
| Framework Laptop             | 1         | 3.23%   |
| eMachines eME730             | 1         | 3.23%   |
| Dell Latitude E7250          | 1         | 3.23%   |
| Dell Latitude E6420          | 1         | 3.23%   |
| Dell Latitude 5490           | 1         | 3.23%   |
| Dell Inspiron 7559           | 1         | 3.23%   |
| Dell Inspiron 3542           | 1         | 3.23%   |
| Chuwi GemiBook Pro           | 1         | 3.23%   |
| ASUS X441SA                  | 1         | 3.23%   |
| ASUS ROG Strix G513RC_G513RC | 1         | 3.23%   |
| Apple MacBookAir4,1          | 1         | 3.23%   |
| Apple MacBook4,1             | 1         | 3.23%   |
| Acer Swift SF113-31          | 1         | 3.23%   |
| Acer Aspire E5-573           | 1         | 3.23%   |
| Unknown                      | 1         | 3.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| HP Pavilion       | 3         | 9.68%   |
| Dell Latitude     | 3         | 9.68%   |
| HP Laptop         | 2         | 6.45%   |
| Dell Inspiron     | 2         | 6.45%   |
| Positivo CHT14B   | 1         | 3.23%   |
| MSI Katana        | 1         | 3.23%   |
| MSI GL65          | 1         | 3.23%   |
| MSI GF63          | 1         | 3.23%   |
| MSI Alpha         | 1         | 3.23%   |
| Lenovo ThinkPad   | 1         | 3.23%   |
| HUAWEI NBD-WXX9   | 1         | 3.23%   |
| HUAWEI BOHB-WAX9  | 1         | 3.23%   |
| HP Stream         | 1         | 3.23%   |
| HP Notebook       | 1         | 3.23%   |
| Google Kindred    | 1         | 3.23%   |
| Framework Laptop  | 1         | 3.23%   |
| eMachines eME730  | 1         | 3.23%   |
| Chuwi GemiBook    | 1         | 3.23%   |
| ASUS X441SA       | 1         | 3.23%   |
| ASUS ROG          | 1         | 3.23%   |
| Apple MacBookAir4 | 1         | 3.23%   |
| Apple MacBook4    | 1         | 3.23%   |
| Acer Swift        | 1         | 3.23%   |
| Acer Aspire       | 1         | 3.23%   |
| Unknown           | 1         | 3.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 8         | 25.81%  |
| 2017 | 3         | 9.68%   |
| 2011 | 3         | 9.68%   |
| 2022 | 2         | 6.45%   |
| 2020 | 2         | 6.45%   |
| 2018 | 2         | 6.45%   |
| 2016 | 2         | 6.45%   |
| 2015 | 2         | 6.45%   |
| 2014 | 2         | 6.45%   |
| 2012 | 2         | 6.45%   |
| 2019 | 1         | 3.23%   |
| 2010 | 1         | 3.23%   |
| 2008 | 1         | 3.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 31        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 31        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 30        | 96.77%  |
| Yes  | 1         | 3.23%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 9         | 29.03%  |
| 3.01-4.0   | 6         | 19.35%  |
| 8.01-16.0  | 6         | 19.35%  |
| 16.01-24.0 | 4         | 12.9%   |
| 32.01-64.0 | 3         | 9.68%   |
| 1.01-2.0   | 2         | 6.45%   |
| 24.01-32.0 | 1         | 3.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 12        | 37.5%   |
| 2.01-3.0 | 9         | 28.13%  |
| 4.01-8.0 | 5         | 15.63%  |
| 3.01-4.0 | 4         | 12.5%   |
| 0.51-1.0 | 2         | 6.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 18        | 58.06%  |
| 2      | 12        | 38.71%  |
| 3      | 1         | 3.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 24        | 77.42%  |
| Yes       | 7         | 22.58%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 70.97%  |
| No        | 9         | 29.03%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 96.77%  |
| No        | 1         | 3.23%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 83.87%  |
| No        | 5         | 16.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 4         | 12.9%   |
| Mexico             | 4         | 12.9%   |
| India              | 4         | 12.9%   |
| UK                 | 2         | 6.45%   |
| South Africa       | 2         | 6.45%   |
| Vietnam            | 1         | 3.23%   |
| Turkey             | 1         | 3.23%   |
| Thailand           | 1         | 3.23%   |
| Spain              | 1         | 3.23%   |
| Russia             | 1         | 3.23%   |
| Philippines        | 1         | 3.23%   |
| Malaysia           | 1         | 3.23%   |
| Italy              | 1         | 3.23%   |
| Indonesia          | 1         | 3.23%   |
| France             | 1         | 3.23%   |
| Finland            | 1         | 3.23%   |
| Dominican Republic | 1         | 3.23%   |
| Brazil             | 1         | 3.23%   |
| Austria            | 1         | 3.23%   |
| Argentina          | 1         | 3.23%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| New Delhi          | 2         | 6.25%   |
| Cape Town          | 2         | 6.25%   |
| Welwyn Garden City | 1         | 3.13%   |
| Vienna             | 1         | 3.13%   |
| Torreón           | 1         | 3.13%   |
| Tirunelveli        | 1         | 3.13%   |
| Stevens Point      | 1         | 3.13%   |
| Seremban           | 1         | 3.13%   |
| Sao Paulo          | 1         | 3.13%   |
| Santo Domingo Este | 1         | 3.13%   |
| Santa Rosa         | 1         | 3.13%   |
| Rocca di Papa      | 1         | 3.13%   |
| Monterrey          | 1         | 3.13%   |
| Mazatlán          | 1         | 3.13%   |
| Mar del Plata      | 1         | 3.13%   |
| Malang             | 1         | 3.13%   |
| Madrid             | 1         | 3.13%   |
| Loskutova          | 1         | 3.13%   |
| London             | 1         | 3.13%   |
| Lannion            | 1         | 3.13%   |
| Jorge Negrete      | 1         | 3.13%   |
| Istanbul           | 1         | 3.13%   |
| Helsinki           | 1         | 3.13%   |
| Hanoi              | 1         | 3.13%   |
| Gebze              | 1         | 3.13%   |
| Clifton Park       | 1         | 3.13%   |
| Bhubaneswar        | 1         | 3.13%   |
| Bangkok            | 1         | 3.13%   |
| Austin             | 1         | 3.13%   |
| Arlington          | 1         | 3.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Unknown                     | 5         | 8      | 12.2%   |
| WDC                         | 4         | 4      | 9.76%   |
| Seagate                     | 3         | 4      | 7.32%   |
| Sandisk                     | 3         | 3      | 7.32%   |
| Toshiba                     | 2         | 2      | 4.88%   |
| SK hynix                    | 2         | 2      | 4.88%   |
| Samsung Electronics         | 2         | 2      | 4.88%   |
| Phison Electronics          | 2         | 2      | 4.88%   |
| Unknown                     | 2         | 2      | 4.88%   |
| Yangtze Memory Technologies | 1         | 1      | 2.44%   |
| Phison                      | 1         | 1      | 2.44%   |
| Netac                       | 1         | 1      | 2.44%   |
| Mushkin                     | 1         | 2      | 2.44%   |
| Micron/Crucial Technology   | 1         | 1      | 2.44%   |
| KIOXIA                      | 1         | 1      | 2.44%   |
| Kingston Technology Company | 1         | 2      | 2.44%   |
| Kingston                    | 1         | 1      | 2.44%   |
| KingFast                    | 1         | 2      | 2.44%   |
| Intel                       | 1         | 1      | 2.44%   |
| Initio                      | 1         | 1      | 2.44%   |
| Hitachi                     | 1         | 1      | 2.44%   |
| HGST                        | 1         | 1      | 2.44%   |
| Gigabyte Technology         | 1         | 2      | 2.44%   |
| Crucial                     | 1         | 1      | 2.44%   |
| Apple                       | 1         | 1      | 2.44%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Seagate ST500LM030-2E717D 500GB                 | 2         | 4.44%   |
| Unknown                                         | 2         | 4.44%   |
| Yangtze Memory YMTC PC005 256GB                 | 1         | 2.22%   |
| WDC WDS500G2B0C-00PXH0 500GB                    | 1         | 2.22%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                | 1         | 2.22%   |
| WDC WD10SPZX-24Z10T0 1TB                        | 1         | 2.22%   |
| WDC WD10JPVX-22JC3T0 1TB                        | 1         | 2.22%   |
| Unknown SD/MMC/MS PRO 64GB                      | 1         | 2.22%   |
| Unknown SC128  128GB                            | 1         | 2.22%   |
| Unknown MMC Card  64GB                          | 1         | 2.22%   |
| Unknown MMC Card  32GB                          | 1         | 2.22%   |
| Unknown MMC Card  16GB                          | 1         | 2.22%   |
| Unknown Essentiel B 1TB                         | 1         | 2.22%   |
| Toshiba MQ01ABF050 500GB                        | 1         | 2.22%   |
| Toshiba MQ01ABD100 1TB                          | 1         | 2.22%   |
| SK hynix NVMe SSD Drive 128GB                   | 1         | 2.22%   |
| SK hynix HFS128G39TND-N210A 128GB SSD           | 1         | 2.22%   |
| Seagate ST1000LM048-2E7172 1TB                  | 1         | 2.22%   |
| Seagate Expansion 1TB                           | 1         | 2.22%   |
| Sandisk WD PC SN735 SDBPNHH-512G-1002 512GB     | 1         | 2.22%   |
| Sandisk WD Blue SN570 1TB                       | 1         | 2.22%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 512GB | 1         | 2.22%   |
| Samsung SSD PM871 mSATA 256GB                   | 1         | 2.22%   |
| Samsung SSD 860 EVO 1TB                         | 1         | 2.22%   |
| Phison Sabrent Rocket 4.0 Plus 4TB              | 1         | 2.22%   |
| Phison PS5013 E13 NVMe Controller 512GB         | 1         | 2.22%   |
| Phison E16 PCIe4 NVMe Controller 1TB            | 1         | 2.22%   |
| Netac S535N8/256 256GB SSD                      | 1         | 2.22%   |
| Mushkin MKNSSDPE500GB-D8                        | 1         | 2.22%   |
| Mushkin MKNSSDPE1TB-D8                          | 1         | 2.22%   |
| Micron/Crucial NVMe SSD Drive 2TB               | 1         | 2.22%   |
| KIOXIA KBG40ZNV512G 512GB                       | 1         | 2.22%   |
| Kingston Company SNV2S1000G 1TB                 | 1         | 2.22%   |
| Kingston Company OM3PDP3 NVMe SSD 256GB         | 1         | 2.22%   |
| Kingston SA400S37480G 480GB SSD                 | 1         | 2.22%   |
| KingFast 240GB                                  | 1         | 2.22%   |
| Intel SSDSC2BW180A3L 180GB                      | 1         | 2.22%   |
| Initio 3639S 1TB                                | 1         | 2.22%   |
| Hitachi HTS545032A7E380 320GB                   | 1         | 2.22%   |
| HGST HTS545050A7E680 500GB                      | 1         | 2.22%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 4      | 27.27%  |
| WDC     | 2         | 2      | 18.18%  |
| Unknown | 2         | 3      | 18.18%  |
| Toshiba | 2         | 2      | 18.18%  |
| Hitachi | 1         | 1      | 9.09%   |
| HGST    | 1         | 1      | 9.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 16.67%  |
| Unknown             | 2         | 2      | 16.67%  |
| WDC                 | 1         | 1      | 8.33%   |
| SK hynix            | 1         | 1      | 8.33%   |
| Netac               | 1         | 1      | 8.33%   |
| Kingston            | 1         | 1      | 8.33%   |
| Intel               | 1         | 1      | 8.33%   |
| Initio              | 1         | 1      | 8.33%   |
| Gigabyte Technology | 1         | 2      | 8.33%   |
| Apple               | 1         | 1      | 8.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 13        | 16     | 32.5%   |
| SSD     | 12        | 13     | 30%     |
| HDD     | 10        | 13     | 25%     |
| MMC     | 4         | 5      | 10%     |
| Unknown | 1         | 2      | 2.5%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 19        | 23     | 47.5%   |
| NVMe | 13        | 16     | 32.5%   |
| SAS  | 4         | 5      | 10%     |
| MMC  | 4         | 5      | 10%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 15        | 17     | 65.22%  |
| 0.51-1.0   | 8         | 9      | 34.78%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 10        | 32.26%  |
| 251-500        | 7         | 22.58%  |
| 501-1000       | 4         | 12.9%   |
| 1001-2000      | 3         | 9.68%   |
| 51-100         | 3         | 9.68%   |
| More than 3000 | 2         | 6.45%   |
| 21-50          | 1         | 3.23%   |
| Unknown        | 1         | 3.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 21-50    | 10        | 32.26%  |
| 1-20     | 8         | 25.81%  |
| 51-100   | 5         | 16.13%  |
| 251-500  | 3         | 9.68%   |
| 501-1000 | 3         | 9.68%   |
| 101-250  | 1         | 3.23%   |
| Unknown  | 1         | 3.23%   |

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
| Works    | 21        | 28     | 61.76%  |
| Detected | 10        | 18     | 29.41%  |
| Malfunc  | 3         | 3      | 8.82%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 23        | 62.16%  |
| SanDisk                     | 4         | 10.81%  |
| Phison Electronics          | 2         | 5.41%   |
| Micron/Crucial Technology   | 2         | 5.41%   |
| Yangtze Memory Technologies | 1         | 2.7%    |
| SK hynix                    | 1         | 2.7%    |
| Silicon Motion              | 1         | 2.7%    |
| KIOXIA                      | 1         | 2.7%    |
| Kingston Technology Company | 1         | 2.7%    |
| AMD                         | 1         | 2.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 3         | 7.5%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 2         | 5%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 5%      |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 5%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 5%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 5%      |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 2         | 5%      |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 5%      |
| Yangtze Memory Non-Volatile memory controller                                    | 1         | 2.5%    |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 2.5%    |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 2.5%    |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                               | 1         | 2.5%    |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 2.5%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 2.5%    |
| SanDisk Non-Volatile memory controller                                           | 1         | 2.5%    |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 2.5%    |
| Phison E18 PCIe4 NVMe Controller                                                 | 1         | 2.5%    |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 2.5%    |
| KIOXIA NVMe SSD Controller BG4                                                   | 1         | 2.5%    |
| Kingston Company Company Non-Volatile memory controller                          | 1         | 2.5%    |
| Kingston Company OM3PDP3 NVMe SSD                                                | 1         | 2.5%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 2.5%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 2.5%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 2.5%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 2.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 2.5%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 2.5%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 2.5%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 1         | 2.5%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 2.5%    |
| AMD FCH SATA Controller [AHCI mode]                                              | 1         | 2.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 21        | 55.26%  |
| NVMe | 13        | 34.21%  |
| RAID | 3         | 7.89%   |
| IDE  | 1         | 2.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 27        | 87.1%   |
| AMD    | 4         | 12.9%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz         | 2         | 6.45%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz   | 2         | 6.45%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz   | 2         | 6.45%   |
| Intel Pentium CPU N4200 @ 1.10GHz         | 1         | 3.23%   |
| Intel Core i7-8565U CPU @ 1.80GHz         | 1         | 3.23%   |
| Intel Core i7-8550U CPU @ 1.80GHz         | 1         | 3.23%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz        | 1         | 3.23%   |
| Intel Core i7-4510U CPU @ 2.00GHz         | 1         | 3.23%   |
| Intel Core i7-10750H CPU @ 2.60GHz        | 1         | 3.23%   |
| Intel Core i5-5300U CPU @ 2.30GHz         | 1         | 3.23%   |
| Intel Core i5-3320M CPU @ 2.60GHz         | 1         | 3.23%   |
| Intel Core i5-2540M CPU @ 2.60GHz         | 1         | 3.23%   |
| Intel Core i5-2467M CPU @ 1.60GHz         | 1         | 3.23%   |
| Intel Core i5-10300H CPU @ 2.50GHz        | 1         | 3.23%   |
| Intel Core i5-10210U CPU @ 1.60GHz        | 1         | 3.23%   |
| Intel Core i3-5005U CPU @ 2.00GHz         | 1         | 3.23%   |
| Intel Core i3-10110U CPU @ 2.10GHz        | 1         | 3.23%   |
| Intel Core i3 CPU M 350 @ 2.27GHz         | 1         | 3.23%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz      | 1         | 3.23%   |
| Intel Celeron N4020 CPU @ 1.10GHz         | 1         | 3.23%   |
| Intel Celeron J4125 CPU @ 2.00GHz         | 1         | 3.23%   |
| Intel Celeron CPU N3060 @ 1.60GHz         | 1         | 3.23%   |
| Intel Celeron 2957U @ 1.40GHz             | 1         | 3.23%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz         | 1         | 3.23%   |
| AMD Ryzen 7 6800H with Radeon Graphics    | 1         | 3.23%   |
| AMD Ryzen 7 5800H with Radeon Graphics    | 1         | 3.23%   |
| AMD Ryzen 5 4500U with Radeon Graphics    | 1         | 3.23%   |
| AMD A4-3330MX APU with Radeon HD Graphics | 1         | 3.23%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 8         | 25.81%  |
| Intel Core i7    | 5         | 16.13%  |
| Other            | 4         | 12.9%   |
| Intel Celeron    | 4         | 12.9%   |
| Intel Core i3    | 3         | 9.68%   |
| AMD Ryzen 7      | 2         | 6.45%   |
| Intel Pentium    | 1         | 3.23%   |
| Intel Core 2 Duo | 1         | 3.23%   |
| Intel Atom       | 1         | 3.23%   |
| AMD Ryzen 5      | 1         | 3.23%   |
| AMD A4           | 1         | 3.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 13        | 41.94%  |
| 4      | 12        | 38.71%  |
| 8      | 4         | 12.9%   |
| 6      | 2         | 6.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 31        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 22        | 70.97%  |
| 1      | 9         | 29.03%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 31        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 12        | 38.71%  |
| 0xa0652    | 2         | 6.45%   |
| 0x806d1    | 2         | 6.45%   |
| 0x706a8    | 2         | 6.45%   |
| 0x206a7    | 2         | 6.45%   |
| 0x806ec    | 1         | 3.23%   |
| 0x806ea    | 1         | 3.23%   |
| 0x506e3    | 1         | 3.23%   |
| 0x506c9    | 1         | 3.23%   |
| 0x406c4    | 1         | 3.23%   |
| 0x40651    | 1         | 3.23%   |
| 0x306d4    | 1         | 3.23%   |
| 0x306a9    | 1         | 3.23%   |
| 0x0a404102 | 1         | 3.23%   |
| 0x08600106 | 1         | 3.23%   |
| 0x03000027 | 1         | 3.23%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 6         | 19.35%  |
| TigerLake     | 2         | 6.45%   |
| Silvermont    | 2         | 6.45%   |
| SandyBridge   | 2         | 6.45%   |
| Icelake       | 2         | 6.45%   |
| Haswell       | 2         | 6.45%   |
| Goldmont plus | 2         | 6.45%   |
| CometLake     | 2         | 6.45%   |
| Broadwell     | 2         | 6.45%   |
| Zen 3         | 1         | 3.23%   |
| Zen 2         | 1         | 3.23%   |
| Westmere      | 1         | 3.23%   |
| Skylake       | 1         | 3.23%   |
| Penryn        | 1         | 3.23%   |
| K10 Llano     | 1         | 3.23%   |
| IvyBridge     | 1         | 3.23%   |
| Goldmont      | 1         | 3.23%   |
| Unknown       | 1         | 3.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 27        | 64.29%  |
| Nvidia | 9         | 21.43%  |
| AMD    | 6         | 14.29%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 3         | 6.82%   |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 4.55%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 4.55%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 4.55%   |
| Intel HD Graphics 5500                                                                   | 2         | 4.55%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 4.55%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 4.55%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 4.55%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 4.55%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 4.55%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 4.55%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 4.55%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 2.27%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 2.27%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 2.27%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 2.27%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 2.27%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 2.27%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 2.27%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 2.27%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 2.27%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 2.27%   |
| Intel HD Graphics 530                                                                    | 1         | 2.27%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 2.27%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 1         | 2.27%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 2.27%   |
| AMD Sumo [Radeon HD 6480G]                                                               | 1         | 2.27%   |
| AMD Renoir                                                                               | 1         | 2.27%   |
| AMD Rembrandt [Radeon 680M]                                                              | 1         | 2.27%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 1         | 2.27%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 1         | 2.27%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 17        | 54.84%  |
| Intel + Nvidia | 8         | 25.81%  |
| Intel + AMD    | 2         | 6.45%   |
| 1 x AMD        | 2         | 6.45%   |
| 2 x AMD        | 1         | 3.23%   |
| AMD + Nvidia   | 1         | 3.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 23        | 74.19%  |
| Proprietary | 8         | 25.81%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 26        | 83.87%  |
| 0.01-0.5   | 3         | 9.68%   |
| 7.01-8.0   | 1         | 3.23%   |
| 5.01-6.0   | 1         | 3.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Chimei Innolux      | 7         | 20%     |
| BOE                 | 7         | 20%     |
| AU Optronics        | 6         | 17.14%  |
| LG Display          | 5         | 14.29%  |
| Samsung Electronics | 3         | 8.57%   |
| PANDA               | 2         | 5.71%   |
| Apple               | 2         | 5.71%   |
| Lenovo              | 1         | 2.86%   |
| Dell                | 1         | 2.86%   |
| ASUSTek Computer    | 1         | 2.86%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch          | 2         | 5.71%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 2         | 5.71%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch    | 1         | 2.86%   |
| Samsung Electronics LCD Monitor SEC335A 1366x768 309x174mm 14.0-inch | 1         | 2.86%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch | 1         | 2.86%   |
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch              | 1         | 2.86%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 1         | 2.86%   |
| LG Display LCD Monitor LGD04B9 1920x1080 344x194mm 15.5-inch         | 1         | 2.86%   |
| LG Display LCD Monitor LGD04B1 1366x768 310x174mm 14.0-inch          | 1         | 2.86%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch          | 1         | 2.86%   |
| Lenovo LEN T2054pC LEN60D9 1440x900 419x262mm 19.5-inch              | 1         | 2.86%   |
| Dell AW2518HF DELA101 1920x1080 540x300mm 24.3-inch                  | 1         | 2.86%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C03 2160x1440 296x197mm 14.0-inch     | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN15E3 1920x1080 344x193mm 15.5-inch     | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 309x173mm 13.9-inch     | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN1147 1366x768 256x144mm 11.6-inch      | 1         | 2.86%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                | 1         | 2.86%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 1         | 2.86%   |
| BOE LCD Monitor BOE07FF 1920x1080 344x194mm 15.5-inch                | 1         | 2.86%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 1         | 2.86%   |
| BOE LCD Monitor BOE0644 1366x768 309x173mm 13.9-inch                 | 1         | 2.86%   |
| AU Optronics LCD Monitor AUOB78F 1920x1080 344x194mm 15.5-inch       | 1         | 2.86%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch       | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 344x194mm 15.5-inch       | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch        | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 1         | 2.86%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 531x299mm 24.0-inch         | 1         | 2.86%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch               | 1         | 2.86%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                 | 1         | 2.86%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 15        | 42.86%  |
| 1366x768 (WXGA)  | 12        | 34.29%  |
| 2256x1504        | 2         | 5.71%   |
| 3840x2160 (4K)   | 1         | 2.86%   |
| 2560x1440 (QHD)  | 1         | 2.86%   |
| 2160x1440        | 1         | 2.86%   |
| 1600x900 (HD+)   | 1         | 2.86%   |
| 1440x900 (WXGA+) | 1         | 2.86%   |
| 1280x800 (WXGA)  | 1         | 2.86%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 16        | 45.71%  |
| 13     | 7         | 20%     |
| 14     | 5         | 14.29%  |
| 24     | 2         | 5.71%   |
| 11     | 2         | 5.71%   |
| 27     | 1         | 2.86%   |
| 19     | 1         | 2.86%   |
| 12     | 1         | 2.86%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 23        | 65.71%  |
| 201-300     | 8         | 22.86%  |
| 501-600     | 2         | 5.71%   |
| 601-700     | 1         | 2.86%   |
| 401-500     | 1         | 2.86%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 28        | 84.85%  |
| 3/2   | 3         | 9.09%   |
| 16/10 | 2         | 6.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 16        | 45.71%  |
| 81-90          | 11        | 31.43%  |
| 51-60          | 2         | 5.71%   |
| 71-80          | 1         | 2.86%   |
| 61-70          | 1         | 2.86%   |
| 301-350        | 1         | 2.86%   |
| 251-300        | 1         | 2.86%   |
| 201-250        | 1         | 2.86%   |
| 151-200        | 1         | 2.86%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 17        | 48.57%  |
| 101-120 | 10        | 28.57%  |
| 161-240 | 5         | 14.29%  |
| 51-100  | 3         | 8.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 27        | 87.1%   |
| 2     | 4         | 12.9%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 18        | 38.3%   |
| Intel                    | 15        | 31.91%  |
| Qualcomm Atheros         | 4         | 8.51%   |
| Ralink Technology        | 3         | 6.38%   |
| Broadcom                 | 3         | 6.38%   |
| MediaTek                 | 2         | 4.26%   |
| TP-Link                  | 1         | 2.13%   |
| Marvell Technology Group | 1         | 2.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9         | 16.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 7.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 5.56%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 3.7%    |
| Ralink MT7601U Wireless Adapter                                   | 2         | 3.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 3.7%    |
| Intel Wireless 7265                                               | 2         | 3.7%    |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 3.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 3.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 3.7%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 3.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 3.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.7%    |
| TP-Link 802.11ac WLAN Adapter                                     | 1         | 1.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 1.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 1.85%   |
| Ralink RT5572 Wireless Adapter                                    | 1         | 1.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 1.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.85%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 1         | 1.85%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1         | 1.85%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.85%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 1.85%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.85%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.85%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.85%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.85%   |
| Broadcom BCM43225 802.11b/g/n                                     | 1         | 1.85%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 1         | 1.85%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 1         | 1.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 14        | 42.42%  |
| Realtek Semiconductor | 6         | 18.18%  |
| Qualcomm Atheros      | 4         | 12.12%  |
| Ralink Technology     | 3         | 9.09%   |
| Broadcom              | 3         | 9.09%   |
| MediaTek              | 2         | 6.06%   |
| TP-Link               | 1         | 3.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 3         | 9.09%   |
| Ralink MT7601U Wireless Adapter                               | 2         | 6.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 2         | 6.06%   |
| Intel Wireless 7265                                           | 2         | 6.06%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 2         | 6.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 2         | 6.06%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 2         | 6.06%   |
| Intel Comet Lake PCH CNVi WiFi                                | 2         | 6.06%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 2         | 6.06%   |
| TP-Link 802.11ac WLAN Adapter                                 | 1         | 3.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 1         | 3.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 1         | 3.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 1         | 3.03%   |
| Ralink RT5572 Wireless Adapter                                | 1         | 3.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 1         | 3.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 1         | 3.03%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 1         | 3.03%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 1         | 3.03%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 1         | 3.03%   |
| Intel Wi-Fi 6 AX201                                           | 1         | 3.03%   |
| Broadcom BCM43225 802.11b/g/n                                 | 1         | 3.03%   |
| Broadcom BCM43224 802.11a/b/g/n                               | 1         | 3.03%   |
| Broadcom BCM4321 802.11a/b/g/n                                | 1         | 3.03%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 15        | 71.43%  |
| Intel                    | 4         | 19.05%  |
| Marvell Technology Group | 1         | 4.76%   |
| Broadcom                 | 1         | 4.76%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9         | 42.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 19.05%  |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 9.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 9.52%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 4.76%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 4.76%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 4.76%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 4.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 30        | 58.82%  |
| Ethernet | 21        | 41.18%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 26        | 81.25%  |
| Ethernet | 6         | 18.75%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 19        | 61.29%  |
| 1     | 11        | 35.48%  |
| 0     | 1         | 3.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 20        | 64.52%  |
| Yes  | 11        | 35.48%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 12        | 46.15%  |
| Realtek Semiconductor           | 4         | 15.38%  |
| Qualcomm Atheros Communications | 2         | 7.69%   |
| Apple                           | 2         | 7.69%   |
| MediaTek                        | 1         | 3.85%   |
| Lite-On Technology              | 1         | 3.85%   |
| IMC Networks                    | 1         | 3.85%   |
| Foxconn / Hon Hai               | 1         | 3.85%   |
| Cambridge Silicon Radio         | 1         | 3.85%   |
| Broadcom                        | 1         | 3.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 6         | 23.08%  |
| Realtek Bluetooth Radio                             | 3         | 11.54%  |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 7.69%   |
| Intel Bluetooth wireless interface                  | 2         | 7.69%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 3.85%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 3.85%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 3.85%   |
| MediaTek Wireless_Device                            | 1         | 3.85%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 3.85%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 3.85%   |
| Intel AX210 Bluetooth                               | 1         | 3.85%   |
| IMC Networks Bluetooth Device                       | 1         | 3.85%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 3.85%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.85%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 3.85%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 3.85%   |
| Apple Bluetooth HCI                                 | 1         | 3.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 26        | 76.47%  |
| Nvidia | 4         | 11.76%  |
| AMD    | 4         | 11.76%  |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 7.32%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 7.32%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 4.88%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 4.88%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 4.88%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 4.88%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 4.88%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 4.88%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 4.88%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 4.88%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 4.88%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 4.88%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 4.88%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 2.44%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 2.44%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 2.44%   |
| Nvidia Audio device                                                                               | 1         | 2.44%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 2.44%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 2.44%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.44%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 2.44%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1         | 2.44%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 2.44%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 2.44%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 1         | 2.44%   |
| AMD FCH Azalia Controller                                                                         | 1         | 2.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 10        | 30.3%   |
| SK hynix            | 7         | 21.21%  |
| Kingston            | 5         | 15.15%  |
| Micron Technology   | 4         | 12.12%  |
| Crucial             | 3         | 9.09%   |
| Unknown (ABCD)      | 1         | 3.03%   |
| Nanya Technology    | 1         | 3.03%   |
| ChangXin Memory     | 1         | 3.03%   |
| Unknown             | 1         | 3.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 5.56%   |
| Kingston RAM KF2933C17S4/16G 16GB SODIMM DDR4 2933MT/s           | 2         | 5.56%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 2.78%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.78%   |
| SK hynix RAM HMT451S6CFR6A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 2.78%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.78%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 2.78%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.78%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 2.78%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 2.78%   |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 2.78%   |
| Samsung RAM M474A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 1         | 2.78%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 1         | 2.78%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 2.78%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.78%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.78%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 2.78%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 2.78%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.78%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 1         | 2.78%   |
| Samsung RAM K4A8G165WC-BCTD 4GB Row Of Chips DDR4 2667MT/s       | 1         | 2.78%   |
| Nanya RAM Module 1GB SODIMM DDR2 667MT/s                         | 1         | 2.78%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s          | 1         | 2.78%   |
| Micron RAM Module 2GB SODIMM DDR3 1866MT/s                       | 1         | 2.78%   |
| Micron RAM 8KTF25664HZ-1G6M1 2GB SODIMM DDR3 1600MT/s            | 1         | 2.78%   |
| Micron RAM 16ATF2G64HZ-2G3E1 16GB SODIMM DDR4 2667MT/s           | 1         | 2.78%   |
| Kingston RAM KN2M64-ETB 8GB SODIMM DDR3 1600MT/s                 | 1         | 2.78%   |
| Kingston RAM ACR16D3LS1KNG/4G 4GB SODIMM DDR3 1600MT/s           | 1         | 2.78%   |
| Kingston RAM 9905625-004.A03LF 8GB SODIMM DDR4 3200MT/s          | 1         | 2.78%   |
| Crucial RAM CT8G4SFRA32A.C8FP 8GB SODIMM DDR4 3200MT/s           | 1         | 2.78%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 1         | 2.78%   |
| Crucial RAM BL16G32C16S4B.16FE 16GB SODIMM DDR4 3200MT/s         | 1         | 2.78%   |
| ChangXin Memory RAM DB4ABAM-MK 1GB Row Of Chips LPDDR4 3733MT/s  | 1         | 2.78%   |
| Unknown                                                          | 1         | 2.78%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 13        | 46.43%  |
| DDR3   | 11        | 39.29%  |
| LPDDR4 | 2         | 7.14%   |
| DDR5   | 1         | 3.57%   |
| DDR2   | 1         | 3.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 25        | 92.59%  |
| Row Of Chips | 2         | 7.41%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 11        | 35.48%  |
| 4096  | 8         | 25.81%  |
| 16384 | 6         | 19.35%  |
| 2048  | 4         | 12.9%   |
| 1024  | 2         | 6.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 8         | 25%     |
| 2667  | 6         | 18.75%  |
| 3200  | 5         | 15.63%  |
| 1333  | 3         | 9.38%   |
| 2933  | 2         | 6.25%   |
| 4800  | 1         | 3.13%   |
| 3733  | 1         | 3.13%   |
| 2400  | 1         | 3.13%   |
| 2133  | 1         | 3.13%   |
| 1866  | 1         | 3.13%   |
| 1334  | 1         | 3.13%   |
| 1067  | 1         | 3.13%   |
| 667   | 1         | 3.13%   |

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
| Chicony Electronics                    | 7         | 26.92%  |
| Microdia                               | 3         | 11.54%  |
| Acer                                   | 3         | 11.54%  |
| Realtek Semiconductor                  | 2         | 7.69%   |
| IMC Networks                           | 2         | 7.69%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 7.69%   |
| Apple                                  | 2         | 7.69%   |
| Suyin                                  | 1         | 3.85%   |
| Sunplus Innovation Technology          | 1         | 3.85%   |
| Ricoh                                  | 1         | 3.85%   |
| Quanta                                 | 1         | 3.85%   |
| Alcor Micro                            | 1         | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                   | 2         | 7.69%   |
| Chicony HD WebCam                                               | 2         | 7.69%   |
| Acer HD Webcam                                                  | 2         | 7.69%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)     | 1         | 3.85%   |
| Sunplus Integrated_Webcam_HD                                    | 1         | 3.85%   |
| Ricoh Laptop_Integrated_Webcam_FHD                              | 1         | 3.85%   |
| Realtek HP Webcam                                               | 1         | 3.85%   |
| Realtek HD Webcam - Realtek                                     | 1         | 3.85%   |
| Quanta ov9734_techfront_camera                                  | 1         | 3.85%   |
| Microdia Webcam Vitade AF                                       | 1         | 3.85%   |
| IMC Networks HP TrueVision HD Camera                            | 1         | 3.85%   |
| IMC Networks HD Camera                                          | 1         | 3.85%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 1         | 3.85%   |
| Chicony Integrated IR Camera                                    | 1         | 3.85%   |
| Chicony HP Wide Vision HD Camera                                | 1         | 3.85%   |
| Chicony HP Truevision HD                                        | 1         | 3.85%   |
| Chicony HD User Facing                                          | 1         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 1         | 3.85%   |
| Apple FaceTime Camera                                           | 1         | 3.85%   |
| Apple Built-in iSight [Micron]                                  | 1         | 3.85%   |
| Alcor Micro USB 2.0 Camera                                      | 1         | 3.85%   |
| Acer Integrated Camera                                          | 1         | 3.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Elan Microelectronics      | 2         | 50%     |
| Shenzhen Goodix Technology | 1         | 25%     |
| LighTuning Technology      | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Elan ELAN:ARM-M4                            | 2         | 50%     |
| Shenzhen Goodix  Fingerprint Device         | 1         | 25%     |
| LighTuning EgisTec Touch Fingerprint Sensor | 1         | 25%     |

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
| 0     | 23        | 74.19%  |
| 1     | 6         | 19.35%  |
| 2     | 2         | 6.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 4         | 40%     |
| Net/wireless          | 2         | 20%     |
| Storage               | 1         | 10%     |
| Multimedia controller | 1         | 10%     |
| Graphics card         | 1         | 10%     |
| Chipcard              | 1         | 10%     |

