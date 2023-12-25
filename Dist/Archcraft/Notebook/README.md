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

Total: 55

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | ROG Strix G513QY_G513QY     | [de15a66a8b](https://linux-hardware.org/?probe=de15a66a8b) | Oct 22, 2023 |
| Packard Be... | EasyNote TK85               | [0c62f48dda](https://linux-hardware.org/?probe=0c62f48dda) | Sep 30, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [a579fd2872](https://linux-hardware.org/?probe=a579fd2872) | Sep 23, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [1322cd195f](https://linux-hardware.org/?probe=1322cd195f) | Sep 15, 2023 |
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
| Archcraft Rolling | 32        | 80%     |
| Archcraft         | 8         | 20%     |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| Archcraft | 40        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 6.2.13-arch1-1         | 2         | 4.65%   |
| 5.18.16-arch1-1        | 2         | 4.65%   |
| 5.12.7-arch1-1         | 2         | 4.65%   |
| 6.5.5-zen1-1-zen       | 1         | 2.33%   |
| 6.4.7-arch1-1          | 1         | 2.33%   |
| 6.4.4-zen1-1-zen       | 1         | 2.33%   |
| 6.4.4-arch1-1          | 1         | 2.33%   |
| 6.4.10-zen2-1-zen      | 1         | 2.33%   |
| 6.4.10-arch1-1         | 1         | 2.33%   |
| 6.4.1-arch2-1          | 1         | 2.33%   |
| 6.3.9-arch1-1          | 1         | 2.33%   |
| 6.3.7-arch1-1-vfio     | 1         | 2.33%   |
| 6.3.6-arch1-1          | 1         | 2.33%   |
| 6.2.8-zen1-1-zen       | 1         | 2.33%   |
| 6.2.2-arch1-1          | 1         | 2.33%   |
| 6.2.12-arch1-1         | 1         | 2.33%   |
| 6.1.7-arch1-1          | 1         | 2.33%   |
| 6.1.4-x64v1-xanmod1-1  | 1         | 2.33%   |
| 6.1.1-arch1-1          | 1         | 2.33%   |
| 6.0.7-arch1-1          | 1         | 2.33%   |
| 6.0.2-arch1-1          | 1         | 2.33%   |
| 6.0.10-x64v1-xanmod1-1 | 1         | 2.33%   |
| 5.19.7-arch1-1         | 1         | 2.33%   |
| 5.19.6-arch1-1         | 1         | 2.33%   |
| 5.19.3-arch1-1         | 1         | 2.33%   |
| 5.19.13-arch1-1        | 1         | 2.33%   |
| 5.18.6-arch1-1         | 1         | 2.33%   |
| 5.18.14-zen1-1-zen     | 1         | 2.33%   |
| 5.17.9-arch1-1         | 1         | 2.33%   |
| 5.17.6-arch1-1         | 1         | 2.33%   |
| 5.17.5-arch1-1         | 1         | 2.33%   |
| 5.16.8-arch1-1         | 1         | 2.33%   |
| 5.16.7-arch1-1         | 1         | 2.33%   |
| 5.16.4-arch1-1         | 1         | 2.33%   |
| 5.16.1-arch1-1         | 1         | 2.33%   |
| 5.15.43-1-lts          | 1         | 2.33%   |
| 5.14.15-arch1-1        | 1         | 2.33%   |
| 5.12.9-arch1-1         | 1         | 2.33%   |
| 5.12.12-arch1-1        | 1         | 2.33%   |
| 5.10.54-1-lts          | 1         | 2.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.4.4   | 2         | 4.65%   |
| 6.4.10  | 2         | 4.65%   |
| 6.2.13  | 2         | 4.65%   |
| 5.18.16 | 2         | 4.65%   |
| 5.12.7  | 2         | 4.65%   |
| 6.5.5   | 1         | 2.33%   |
| 6.4.7   | 1         | 2.33%   |
| 6.4.1   | 1         | 2.33%   |
| 6.3.9   | 1         | 2.33%   |
| 6.3.7   | 1         | 2.33%   |
| 6.3.6   | 1         | 2.33%   |
| 6.2.8   | 1         | 2.33%   |
| 6.2.2   | 1         | 2.33%   |
| 6.2.12  | 1         | 2.33%   |
| 6.1.7   | 1         | 2.33%   |
| 6.1.4   | 1         | 2.33%   |
| 6.1.1   | 1         | 2.33%   |
| 6.0.7   | 1         | 2.33%   |
| 6.0.2   | 1         | 2.33%   |
| 6.0.10  | 1         | 2.33%   |
| 5.19.7  | 1         | 2.33%   |
| 5.19.6  | 1         | 2.33%   |
| 5.19.3  | 1         | 2.33%   |
| 5.19.13 | 1         | 2.33%   |
| 5.18.6  | 1         | 2.33%   |
| 5.18.14 | 1         | 2.33%   |
| 5.17.9  | 1         | 2.33%   |
| 5.17.6  | 1         | 2.33%   |
| 5.17.5  | 1         | 2.33%   |
| 5.16.8  | 1         | 2.33%   |
| 5.16.7  | 1         | 2.33%   |
| 5.16.4  | 1         | 2.33%   |
| 5.16.1  | 1         | 2.33%   |
| 5.15.43 | 1         | 2.33%   |
| 5.14.15 | 1         | 2.33%   |
| 5.12.9  | 1         | 2.33%   |
| 5.12.12 | 1         | 2.33%   |
| 5.10.54 | 1         | 2.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.4     | 5         | 12.2%   |
| 6.2     | 5         | 12.2%   |
| 5.19    | 4         | 9.76%   |
| 5.18    | 4         | 9.76%   |
| 5.12    | 4         | 9.76%   |
| 6.3     | 3         | 7.32%   |
| 6.1     | 3         | 7.32%   |
| 6.0     | 3         | 7.32%   |
| 5.17    | 3         | 7.32%   |
| 5.16    | 3         | 7.32%   |
| 6.5     | 1         | 2.44%   |
| 5.15    | 1         | 2.44%   |
| 5.14    | 1         | 2.44%   |
| 5.10    | 1         | 2.44%   |

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


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| openbox  | 17        | 42.5%   |
| XFCE     | 12        | 30%     |
| bspwm    | 4         | 10%     |
| GNOME    | 2         | 5%      |
| sway     | 1         | 2.5%    |
| LXDE     | 1         | 2.5%    |
| i3       | 1         | 2.5%    |
| Hyprland | 1         | 2.5%    |
| Unknown  | 1         | 2.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 38        | 95%     |
| Wayland | 2         | 5%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 26        | 63.41%  |
| Unknown | 8         | 19.51%  |
| LXDM    | 5         | 12.2%   |
| Ly      | 1         | 2.44%   |
| LightDM | 1         | 2.44%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 17        | 42.5%   |
| es_MX | 5         | 12.5%   |
| es_ES | 4         | 10%     |
| en_IN | 3         | 7.5%    |
| en_ZA | 2         | 5%      |
| en_SG | 2         | 5%      |
| tr_TR | 1         | 2.5%    |
| pl_PL | 1         | 2.5%    |
| it_IT | 1         | 2.5%    |
| fr_FR | 1         | 2.5%    |
| en_PH | 1         | 2.5%    |
| en_GB | 1         | 2.5%    |
| de_AT | 1         | 2.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 28        | 70%     |
| BIOS | 12        | 30%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Ext4  | 33        | 82.5%   |
| Btrfs | 6         | 15%     |
| Xfs   | 1         | 2.5%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 28        | 70%     |
| Unknown | 7         | 17.5%   |
| MBR     | 5         | 12.5%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 35        | 87.5%   |
| Yes       | 5         | 12.5%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 27        | 67.5%   |
| Yes       | 13        | 32.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 8         | 20%     |
| Dell                | 7         | 17.5%   |
| MSI                 | 4         | 10%     |
| HUAWEI              | 3         | 7.5%    |
| ASUSTek Computer    | 3         | 7.5%    |
| Lenovo              | 2         | 5%      |
| Apple               | 2         | 5%      |
| Acer                | 2         | 5%      |
| Standard            | 1         | 2.5%    |
| Positivo            | 1         | 2.5%    |
| Packard Bell        | 1         | 2.5%    |
| Infinix             | 1         | 2.5%    |
| Google              | 1         | 2.5%    |
| Framework           | 1         | 2.5%    |
| eMachines           | 1         | 2.5%    |
| Chuwi               | 1         | 2.5%    |
| AXDIA International | 1         | 2.5%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Positivo CHT14B                | 1         | 2.5%    |
| Packard Bell EasyNote TK85     | 1         | 2.5%    |
| MSI Katana GF66 11UE           | 1         | 2.5%    |
| MSI GL65 Leopard 10SFK         | 1         | 2.5%    |
| MSI GF63 Thin 10SC             | 1         | 2.5%    |
| MSI Alpha 15 B5EEK             | 1         | 2.5%    |
| Lenovo ThinkPad T430 2351AK9   | 1         | 2.5%    |
| Lenovo IdeaPad 3 15IGL05 81WQ  | 1         | 2.5%    |
| Infinix INBook X1 Pro          | 1         | 2.5%    |
| HUAWEI NBD-WXX9                | 1         | 2.5%    |
| HUAWEI HLYL-WXX9               | 1         | 2.5%    |
| HUAWEI BOHB-WAX9               | 1         | 2.5%    |
| HP Stream Laptop 11-ak0xxx     | 1         | 2.5%    |
| HP Pavilion Laptop 15-eh0xxx   | 1         | 2.5%    |
| HP Pavilion Laptop 15-cc1xx    | 1         | 2.5%    |
| HP Pavilion g4                 | 1         | 2.5%    |
| HP Notebook                    | 1         | 2.5%    |
| HP Laptop 15q-bu1xx            | 1         | 2.5%    |
| HP Laptop 15-dy2xxx            | 1         | 2.5%    |
| HP Laptop 15-dw0xxx            | 1         | 2.5%    |
| Google Kindred                 | 1         | 2.5%    |
| Framework Laptop               | 1         | 2.5%    |
| eMachines eME730               | 1         | 2.5%    |
| Dell Vostro 3401               | 1         | 2.5%    |
| Dell Latitude E7250            | 1         | 2.5%    |
| Dell Latitude E6420            | 1         | 2.5%    |
| Dell Latitude E5420            | 1         | 2.5%    |
| Dell Latitude 5490             | 1         | 2.5%    |
| Dell Inspiron 7559             | 1         | 2.5%    |
| Dell Inspiron 3542             | 1         | 2.5%    |
| Chuwi GemiBook Pro             | 1         | 2.5%    |
| AXDIA International WINPAD V10 | 1         | 2.5%    |
| ASUS X441SA                    | 1         | 2.5%    |
| ASUS ROG Strix G513RC_G513RC   | 1         | 2.5%    |
| ASUS ROG Strix G513QY_G513QY   | 1         | 2.5%    |
| Apple MacBookAir4,1            | 1         | 2.5%    |
| Apple MacBook4,1               | 1         | 2.5%    |
| Acer Swift SF113-31            | 1         | 2.5%    |
| Acer Aspire E5-573             | 1         | 2.5%    |
| Unknown                        | 1         | 2.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Dell Latitude              | 4         | 10%     |
| HP Pavilion                | 3         | 7.5%    |
| HP Laptop                  | 3         | 7.5%    |
| Dell Inspiron              | 2         | 5%      |
| ASUS ROG                   | 2         | 5%      |
| Positivo CHT14B            | 1         | 2.5%    |
| Packard Bell EasyNote      | 1         | 2.5%    |
| MSI Katana                 | 1         | 2.5%    |
| MSI GL65                   | 1         | 2.5%    |
| MSI GF63                   | 1         | 2.5%    |
| MSI Alpha                  | 1         | 2.5%    |
| Lenovo ThinkPad            | 1         | 2.5%    |
| Lenovo IdeaPad             | 1         | 2.5%    |
| Infinix INBook             | 1         | 2.5%    |
| HUAWEI NBD-WXX9            | 1         | 2.5%    |
| HUAWEI HLYL-WXX9           | 1         | 2.5%    |
| HUAWEI BOHB-WAX9           | 1         | 2.5%    |
| HP Stream                  | 1         | 2.5%    |
| HP Notebook                | 1         | 2.5%    |
| Google Kindred             | 1         | 2.5%    |
| Framework Laptop           | 1         | 2.5%    |
| eMachines eME730           | 1         | 2.5%    |
| Dell Vostro                | 1         | 2.5%    |
| Chuwi GemiBook             | 1         | 2.5%    |
| AXDIA International WINPAD | 1         | 2.5%    |
| ASUS X441SA                | 1         | 2.5%    |
| Apple MacBookAir4          | 1         | 2.5%    |
| Apple MacBook4             | 1         | 2.5%    |
| Acer Swift                 | 1         | 2.5%    |
| Acer Aspire                | 1         | 2.5%    |
| Unknown                    | 1         | 2.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 12        | 30%     |
| 2020 | 5         | 12.5%   |
| 2011 | 4         | 10%     |
| 2017 | 3         | 7.5%    |
| 2014 | 3         | 7.5%    |
| 2018 | 2         | 5%      |
| 2016 | 2         | 5%      |
| 2015 | 2         | 5%      |
| 2012 | 2         | 5%      |
| 2010 | 2         | 5%      |
| 2022 | 1         | 2.5%    |
| 2019 | 1         | 2.5%    |
| 2008 | 1         | 2.5%    |

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


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 11        | 27.5%   |
| 3.01-4.0   | 9         | 22.5%   |
| 8.01-16.0  | 8         | 20%     |
| 16.01-24.0 | 5         | 12.5%   |
| 32.01-64.0 | 3         | 7.5%    |
| 1.01-2.0   | 3         | 7.5%    |
| 24.01-32.0 | 1         | 2.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 15        | 36.59%  |
| 2.01-3.0 | 12        | 29.27%  |
| 4.01-8.0 | 6         | 14.63%  |
| 3.01-4.0 | 4         | 9.76%   |
| 0.51-1.0 | 4         | 9.76%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 25        | 62.5%   |
| 2      | 14        | 35%     |
| 3      | 1         | 2.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 31        | 77.5%   |
| Yes       | 9         | 22.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 65%     |
| No        | 14        | 35%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 95.12%  |
| No        | 2         | 4.88%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 33        | 82.5%   |
| No        | 7         | 17.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| India              | 5         | 12.5%   |
| USA                | 4         | 10%     |
| Spain              | 4         | 10%     |
| Mexico             | 4         | 10%     |
| Uruguay            | 2         | 5%      |
| UK                 | 2         | 5%      |
| South Africa       | 2         | 5%      |
| Malaysia           | 2         | 5%      |
| Vietnam            | 1         | 2.5%    |
| Turkey             | 1         | 2.5%    |
| Thailand           | 1         | 2.5%    |
| Russia             | 1         | 2.5%    |
| Philippines        | 1         | 2.5%    |
| Italy              | 1         | 2.5%    |
| Indonesia          | 1         | 2.5%    |
| France             | 1         | 2.5%    |
| Finland            | 1         | 2.5%    |
| Dominican Republic | 1         | 2.5%    |
| Colombia           | 1         | 2.5%    |
| Brazil             | 1         | 2.5%    |
| Belarus            | 1         | 2.5%    |
| Austria            | 1         | 2.5%    |
| Argentina          | 1         | 2.5%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Seremban           | 2         | 4.88%   |
| New Delhi          | 2         | 4.88%   |
| Montevideo         | 2         | 4.88%   |
| Madrid             | 2         | 4.88%   |
| Cape Town          | 2         | 4.88%   |
| Welwyn Garden City | 1         | 2.44%   |
| Vienna             | 1         | 2.44%   |
| Valencia           | 1         | 2.44%   |
| Torreón           | 1         | 2.44%   |
| Tirunelveli        | 1         | 2.44%   |
| Stevens Point      | 1         | 2.44%   |
| Sao Paulo          | 1         | 2.44%   |
| Santo Domingo Este | 1         | 2.44%   |
| Santa Rosa         | 1         | 2.44%   |
| Rocca di Papa      | 1         | 2.44%   |
| Monterrey          | 1         | 2.44%   |
| Mazatlán          | 1         | 2.44%   |
| Mar del Plata      | 1         | 2.44%   |
| Mangalore          | 1         | 2.44%   |
| Malang             | 1         | 2.44%   |
| Loskutova          | 1         | 2.44%   |
| London             | 1         | 2.44%   |
| Lannion            | 1         | 2.44%   |
| Jorge Negrete      | 1         | 2.44%   |
| Istanbul           | 1         | 2.44%   |
| Helsinki           | 1         | 2.44%   |
| Hanoi              | 1         | 2.44%   |
| Gebze              | 1         | 2.44%   |
| Clifton Park       | 1         | 2.44%   |
| Bhubaneswar        | 1         | 2.44%   |
| Barranquilla       | 1         | 2.44%   |
| Barcelona          | 1         | 2.44%   |
| Bangkok            | 1         | 2.44%   |
| Babruysk           | 1         | 2.44%   |
| Austin             | 1         | 2.44%   |
| Arlington          | 1         | 2.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Unknown                     | 6         | 12     | 11.76%  |
| WDC                         | 5         | 5      | 9.8%    |
| Samsung Electronics         | 4         | 4      | 7.84%   |
| Seagate                     | 3         | 4      | 5.88%   |
| Sandisk                     | 3         | 3      | 5.88%   |
| Phison Electronics          | 3         | 3      | 5.88%   |
| Toshiba                     | 2         | 2      | 3.92%   |
| SK hynix                    | 2         | 2      | 3.92%   |
| KIOXIA                      | 2         | 2      | 3.92%   |
| Kingston                    | 2         | 2      | 3.92%   |
| Hitachi                     | 2         | 2      | 3.92%   |
| Crucial                     | 2         | 2      | 3.92%   |
| Unknown                     | 2         | 2      | 3.92%   |
| Yangtze Memory Technologies | 1         | 1      | 1.96%   |
| Solid State Storage         | 1         | 1      | 1.96%   |
| Phison                      | 1         | 1      | 1.96%   |
| Netac                       | 1         | 1      | 1.96%   |
| Mushkin                     | 1         | 2      | 1.96%   |
| Micron/Crucial Technology   | 1         | 1      | 1.96%   |
| Kingston Technology Company | 1         | 2      | 1.96%   |
| KingFast                    | 1         | 2      | 1.96%   |
| Intel                       | 1         | 1      | 1.96%   |
| Initio                      | 1         | 1      | 1.96%   |
| HGST                        | 1         | 1      | 1.96%   |
| Gigabyte Technology         | 1         | 2      | 1.96%   |
| Apple                       | 1         | 1      | 1.96%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                              | 2         | 3.57%   |
| Seagate ST500LM030-2E717D 500GB                     | 2         | 3.57%   |
| Phison PS5013 E13 NVMe Controller 512GB             | 2         | 3.57%   |
| Unknown                                             | 2         | 3.57%   |
| Yangtze Memory YMTC PC005 256GB                     | 1         | 1.79%   |
| WDC WDS500G2B0C-00PXH0 500GB                        | 1         | 1.79%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1         | 1.79%   |
| WDC WD10SPZX-75Z10T3 1TB                            | 1         | 1.79%   |
| WDC WD10SPZX-24Z10T0 1TB                            | 1         | 1.79%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 1         | 1.79%   |
| Unknown SD/MMC/MS PRO 128GB                         | 1         | 1.79%   |
| Unknown SC128  128GB                                | 1         | 1.79%   |
| Unknown MMC Card  64GB                              | 1         | 1.79%   |
| Unknown MMC Card  16GB                              | 1         | 1.79%   |
| Unknown MMC Card  128GB                             | 1         | 1.79%   |
| Unknown Essentiel B 1TB                             | 1         | 1.79%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 1.79%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 1.79%   |
| Solid State Storage SSSTC CL1-4D256 256GB           | 1         | 1.79%   |
| SK hynix NVMe SSD Drive 128GB                       | 1         | 1.79%   |
| SK hynix HFS128G39TND-N210A 128GB SSD               | 1         | 1.79%   |
| Seagate ST1000LM048-2E7172 1TB                      | 1         | 1.79%   |
| Seagate Expansion 1TB                               | 1         | 1.79%   |
| Sandisk WD PC SN735 SDBPNHH-512G-1002 512GB         | 1         | 1.79%   |
| Sandisk WD Blue SN570 1TB                           | 1         | 1.79%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 500GB     | 1         | 1.79%   |
| Samsung SSD PM871 mSATA 256GB                       | 1         | 1.79%   |
| Samsung SSD 860 EVO 1TB                             | 1         | 1.79%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 1         | 1.79%   |
| Samsung MZVLQ512HBLU-00B00 512GB                    | 1         | 1.79%   |
| Phison Sabrent Rocket 4.0 Plus 1TB                  | 1         | 1.79%   |
| Phison E16 PCIe4 NVMe Controller 500GB              | 1         | 1.79%   |
| Netac S535N8/256 256GB SSD                          | 1         | 1.79%   |
| Mushkin MKNSSDPE500GB-D8                            | 1         | 1.79%   |
| Mushkin MKNSSDPE1TB-D8                              | 1         | 1.79%   |
| Micron/Crucial NVMe SSD Drive 2TB                   | 1         | 1.79%   |
| KIOXIA KBG40ZNV512G 512GB                           | 1         | 1.79%   |
| KIOXIA KBG40ZNV256G 256GB                           | 1         | 1.79%   |
| Kingston Company SNV2S1000G 1TB                     | 1         | 1.79%   |
| Kingston Company OM3PDP3 NVMe SSD 256GB             | 1         | 1.79%   |

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
| Samsung Electronics | 2         | 2      | 16.67%  |
| Unknown             | 2         | 2      | 16.67%  |
| WDC                 | 1         | 1      | 8.33%   |
| SK hynix            | 1         | 1      | 8.33%   |
| Netac               | 1         | 1      | 8.33%   |
| Kingston            | 1         | 1      | 8.33%   |
| Intel               | 1         | 1      | 8.33%   |
| Gigabyte Technology | 1         | 2      | 8.33%   |
| Crucial             | 1         | 1      | 8.33%   |
| Apple               | 1         | 1      | 8.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 18        | 22     | 36.73%  |
| HDD     | 13        | 16     | 26.53%  |
| SSD     | 12        | 13     | 24.49%  |
| MMC     | 5         | 9      | 10.2%   |
| Unknown | 1         | 2      | 2.04%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 22        | 26     | 44.9%   |
| NVMe | 18        | 22     | 36.73%  |
| MMC  | 5         | 9      | 10.2%   |
| SAS  | 4         | 5      | 8.16%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 16        | 18     | 61.54%  |
| 0.51-1.0   | 10        | 11     | 38.46%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 13        | 32.5%   |
| 251-500        | 11        | 27.5%   |
| 501-1000       | 5         | 12.5%   |
| 1001-2000      | 3         | 7.5%    |
| 51-100         | 3         | 7.5%    |
| More than 3000 | 2         | 5%      |
| 21-50          | 2         | 5%      |
| Unknown        | 1         | 2.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 21-50    | 14        | 34.15%  |
| 1-20     | 10        | 24.39%  |
| 51-100   | 7         | 17.07%  |
| 251-500  | 4         | 9.76%   |
| 501-1000 | 3         | 7.32%   |
| 101-250  | 2         | 4.88%   |
| Unknown  | 1         | 2.44%   |

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
| Works    | 27        | 35     | 62.79%  |
| Detected | 13        | 24     | 30.23%  |
| Malfunc  | 3         | 3      | 6.98%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 28        | 58.33%  |
| SanDisk                        | 4         | 8.33%   |
| Phison Electronics             | 3         | 6.25%   |
| Samsung Electronics            | 2         | 4.17%   |
| Micron/Crucial Technology      | 2         | 4.17%   |
| KIOXIA                         | 2         | 4.17%   |
| Kingston Technology Company    | 2         | 4.17%   |
| Yangtze Memory Technologies    | 1         | 2.08%   |
| Solid State Storage Technology | 1         | 2.08%   |
| SK hynix                       | 1         | 2.08%   |
| Silicon Motion                 | 1         | 2.08%   |
| AMD                            | 1         | 2.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 7.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 3         | 5.88%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 2         | 3.92%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 2         | 3.92%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 2         | 3.92%   |
| Intel Tiger Lake SATA AHCI Controller                                            | 2         | 3.92%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 3.92%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 3.92%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 3.92%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 3.92%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 3.92%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 3.92%   |
| Yangtze Memory PC005 NVMe SSD                                                    | 1         | 1.96%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                   | 1         | 1.96%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 1.96%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 1.96%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 1         | 1.96%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                            | 1         | 1.96%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 1         | 1.96%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                            | 1         | 1.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 1.96%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 1         | 1.96%   |
| Phison E18 PCIe4 NVMe Controller                                                 | 1         | 1.96%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 1.96%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 1         | 1.96%   |
| Kingston Company NV2 NVMe SSD SM2267XT                                           | 1         | 1.96%   |
| Kingston Company NV1 NVMe SSD SM2263XT                                           | 1         | 1.96%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 1.96%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 1.96%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 1.96%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 1.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 1.96%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 1         | 1.96%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 1         | 1.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 24        | 50%     |
| NVMe | 18        | 37.5%   |
| RAID | 5         | 10.42%  |
| IDE  | 1         | 2.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 34        | 85%     |
| AMD    | 6         | 15%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz         | 2         | 5%      |
| Intel Celeron N4020 CPU @ 1.10GHz         | 2         | 5%      |
| Intel 11th Gen Core i7-11800H @ 2.30GHz   | 2         | 5%      |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz   | 2         | 5%      |
| Intel Pentium CPU N4200 @ 1.10GHz         | 1         | 2.5%    |
| Intel Core i7-8565U CPU @ 1.80GHz         | 1         | 2.5%    |
| Intel Core i7-8550U CPU @ 1.80GHz         | 1         | 2.5%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz        | 1         | 2.5%    |
| Intel Core i7-4510U CPU @ 2.00GHz         | 1         | 2.5%    |
| Intel Core i7-10750H CPU @ 2.60GHz        | 1         | 2.5%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz        | 1         | 2.5%    |
| Intel Core i5-5300U CPU @ 2.30GHz         | 1         | 2.5%    |
| Intel Core i5-3320M CPU @ 2.60GHz         | 1         | 2.5%    |
| Intel Core i5-2540M CPU @ 2.60GHz         | 1         | 2.5%    |
| Intel Core i5-2467M CPU @ 1.60GHz         | 1         | 2.5%    |
| Intel Core i5-10300H CPU @ 2.50GHz        | 1         | 2.5%    |
| Intel Core i5-10210U CPU @ 1.60GHz        | 1         | 2.5%    |
| Intel Core i5 CPU M 450 @ 2.40GHz         | 1         | 2.5%    |
| Intel Core i3-5005U CPU @ 2.00GHz         | 1         | 2.5%    |
| Intel Core i3-2310M CPU @ 2.10GHz         | 1         | 2.5%    |
| Intel Core i3-10110U CPU @ 2.10GHz        | 1         | 2.5%    |
| Intel Core i3-1005G1 CPU @ 1.20GHz        | 1         | 2.5%    |
| Intel Core i3 CPU M 350 @ 2.27GHz         | 1         | 2.5%    |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz      | 1         | 2.5%    |
| Intel Celeron J4125 CPU @ 2.00GHz         | 1         | 2.5%    |
| Intel Celeron CPU N3060 @ 1.60GHz         | 1         | 2.5%    |
| Intel Celeron 2957U @ 1.40GHz             | 1         | 2.5%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz         | 1         | 2.5%    |
| Intel Atom CPU Z3735F @ 1.33GHz           | 1         | 2.5%    |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz   | 1         | 2.5%    |
| AMD Ryzen 9 5900HX with Radeon Graphics   | 1         | 2.5%    |
| AMD Ryzen 7 6800H with Radeon Graphics    | 1         | 2.5%    |
| AMD Ryzen 7 5800H with Radeon Graphics    | 1         | 2.5%    |
| AMD Ryzen 5 4600H with Radeon Graphics    | 1         | 2.5%    |
| AMD Ryzen 5 4500U with Radeon Graphics    | 1         | 2.5%    |
| AMD A4-3330MX APU with Radeon HD Graphics | 1         | 2.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 9         | 22.5%   |
| Intel Core i7    | 6         | 15%     |
| Other            | 5         | 12.5%   |
| Intel Core i3    | 5         | 12.5%   |
| Intel Celeron    | 5         | 12.5%   |
| Intel Atom       | 2         | 5%      |
| AMD Ryzen 7      | 2         | 5%      |
| AMD Ryzen 5      | 2         | 5%      |
| Intel Pentium    | 1         | 2.5%    |
| Intel Core 2 Duo | 1         | 2.5%    |
| AMD Ryzen 9      | 1         | 2.5%    |
| AMD A4           | 1         | 2.5%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 18        | 45%     |
| 4      | 14        | 35%     |
| 8      | 5         | 12.5%   |
| 6      | 3         | 7.5%    |

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
| 2      | 29        | 72.5%   |
| 1      | 11        | 27.5%   |

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


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 18        | 45%     |
| 0x706a8    | 3         | 7.5%    |
| 0xa0652    | 2         | 5%      |
| 0x806d1    | 2         | 5%      |
| 0x206a7    | 2         | 5%      |
| 0x806ec    | 1         | 2.5%    |
| 0x806ea    | 1         | 2.5%    |
| 0x506e3    | 1         | 2.5%    |
| 0x506c9    | 1         | 2.5%    |
| 0x406c4    | 1         | 2.5%    |
| 0x40651    | 1         | 2.5%    |
| 0x306d4    | 1         | 2.5%    |
| 0x306a9    | 1         | 2.5%    |
| 0x0a50000c | 1         | 2.5%    |
| 0x0a404102 | 1         | 2.5%    |
| 0x08600106 | 1         | 2.5%    |
| 0x08600104 | 1         | 2.5%    |
| 0x03000027 | 1         | 2.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 6         | 15%     |
| Icelake       | 4         | 10%     |
| TigerLake     | 3         | 7.5%    |
| Silvermont    | 3         | 7.5%    |
| SandyBridge   | 3         | 7.5%    |
| Goldmont plus | 3         | 7.5%    |
| Zen 3         | 2         | 5%      |
| Zen 2         | 2         | 5%      |
| Westmere      | 2         | 5%      |
| Haswell       | 2         | 5%      |
| CometLake     | 2         | 5%      |
| Broadwell     | 2         | 5%      |
| Skylake       | 1         | 2.5%    |
| Penryn        | 1         | 2.5%    |
| K10 Llano     | 1         | 2.5%    |
| IvyBridge     | 1         | 2.5%    |
| Goldmont      | 1         | 2.5%    |
| Unknown       | 1         | 2.5%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 33        | 64.71%  |
| Nvidia | 9         | 17.65%  |
| AMD    | 9         | 17.65%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 3         | 5.56%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 5.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 5.56%   |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 3.7%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 3.7%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 3.7%    |
| Intel HD Graphics 5500                                                                   | 2         | 3.7%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 3.7%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 3.7%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 3.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 3.7%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 3.7%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 2         | 3.7%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 3.7%    |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 1.85%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.85%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 1.85%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 1.85%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 1.85%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1.85%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 1.85%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.85%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 1         | 1.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.85%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 1.85%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 1.85%   |
| Intel HD Graphics 530                                                                    | 1         | 1.85%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 1.85%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 1         | 1.85%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 1.85%   |
| AMD Sumo [Radeon HD 6480G]                                                               | 1         | 1.85%   |
| AMD Rembrandt [Radeon 680M]                                                              | 1         | 1.85%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 1         | 1.85%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 1         | 1.85%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 1         | 1.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 23        | 57.5%   |
| Intel + Nvidia | 8         | 20%     |
| 1 x AMD        | 4         | 10%     |
| 2 x AMD        | 2         | 5%      |
| Intel + AMD    | 2         | 5%      |
| AMD + Nvidia   | 1         | 2.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 32        | 80%     |
| Proprietary | 8         | 20%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 32        | 80%     |
| 0.01-0.5   | 5         | 12.5%   |
| 7.01-8.0   | 1         | 2.5%    |
| 5.01-6.0   | 1         | 2.5%    |
| 8.01-16.0  | 1         | 2.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Chimei Innolux      | 10        | 23.81%  |
| BOE                 | 7         | 16.67%  |
| AU Optronics        | 7         | 16.67%  |
| LG Display          | 6         | 14.29%  |
| Samsung Electronics | 3         | 7.14%   |
| PANDA               | 2         | 4.76%   |
| Apple               | 2         | 4.76%   |
| Sharp               | 1         | 2.38%   |
| Lenovo              | 1         | 2.38%   |
| HJC                 | 1         | 2.38%   |
| Dell                | 1         | 2.38%   |
| ASUSTek Computer    | 1         | 2.38%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch          | 2         | 4.76%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch          | 2         | 4.76%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 2         | 4.76%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch              | 1         | 2.38%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch    | 1         | 2.38%   |
| Samsung Electronics LCD Monitor SEC335A 1366x768 309x174mm 14.0-inch | 1         | 2.38%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch | 1         | 2.38%   |
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch              | 1         | 2.38%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 1         | 2.38%   |
| LG Display LCD Monitor LGD04B9 1920x1080 344x194mm 15.5-inch         | 1         | 2.38%   |
| LG Display LCD Monitor LGD04B1 1366x768 310x174mm 14.0-inch          | 1         | 2.38%   |
| Lenovo LEN T2054pC LEN60D9 1440x900 419x262mm 19.5-inch              | 1         | 2.38%   |
| HJC LCD Monitor HJC003D 1920x1080 309x174mm 14.0-inch                | 1         | 2.38%   |
| Dell AW2518HF DELA101 1920x1080 544x303mm 24.5-inch                  | 1         | 2.38%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C03 2160x1440 296x197mm 14.0-inch     | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 355x199mm 16.0-inch     | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN15E3 1920x1080 344x193mm 15.5-inch     | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN1541 1366x768 344x193mm 15.5-inch      | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 309x173mm 13.9-inch     | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN1147 1366x768 256x144mm 11.6-inch      | 1         | 2.38%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                | 1         | 2.38%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 1         | 2.38%   |
| BOE LCD Monitor BOE07FF 1920x1080 344x194mm 15.5-inch                | 1         | 2.38%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 1         | 2.38%   |
| BOE LCD Monitor BOE0644 1366x768 309x173mm 13.9-inch                 | 1         | 2.38%   |
| AU Optronics LCD Monitor AUOB78F 1920x1080 344x194mm 15.5-inch       | 1         | 2.38%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch       | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 344x193mm 15.5-inch       | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch        | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 1         | 2.38%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 531x299mm 24.0-inch         | 1         | 2.38%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch               | 1         | 2.38%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                 | 1         | 2.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 20        | 47.62%  |
| 1366x768 (WXGA)  | 14        | 33.33%  |
| 2256x1504        | 2         | 4.76%   |
| 3840x2160 (4K)   | 1         | 2.38%   |
| 2560x1440 (QHD)  | 1         | 2.38%   |
| 2160x1440        | 1         | 2.38%   |
| 1600x900 (HD+)   | 1         | 2.38%   |
| 1440x900 (WXGA+) | 1         | 2.38%   |
| 1280x800 (WXGA)  | 1         | 2.38%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 19        | 45.24%  |
| 13     | 8         | 19.05%  |
| 14     | 7         | 16.67%  |
| 24     | 2         | 4.76%   |
| 11     | 2         | 4.76%   |
| 27     | 1         | 2.38%   |
| 19     | 1         | 2.38%   |
| 16     | 1         | 2.38%   |
| 12     | 1         | 2.38%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 29        | 69.05%  |
| 201-300     | 8         | 19.05%  |
| 501-600     | 2         | 4.76%   |
| 601-700     | 1         | 2.38%   |
| 401-500     | 1         | 2.38%   |
| 351-400     | 1         | 2.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 35        | 87.5%   |
| 3/2   | 3         | 7.5%    |
| 16/10 | 2         | 5%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 20        | 47.62%  |
| 81-90          | 14        | 33.33%  |
| 51-60          | 2         | 4.76%   |
| 71-80          | 1         | 2.38%   |
| 61-70          | 1         | 2.38%   |
| 301-350        | 1         | 2.38%   |
| 251-300        | 1         | 2.38%   |
| 201-250        | 1         | 2.38%   |
| 151-200        | 1         | 2.38%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 22        | 52.38%  |
| 101-120 | 12        | 28.57%  |
| 161-240 | 5         | 11.9%   |
| 51-100  | 3         | 7.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 36        | 90%     |
| 2     | 4         | 10%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 24        | 40%     |
| Intel                    | 18        | 30%     |
| Qualcomm Atheros         | 5         | 8.33%   |
| Broadcom                 | 4         | 6.67%   |
| Ralink Technology        | 3         | 5%      |
| MediaTek                 | 3         | 5%      |
| TP-Link                  | 1         | 1.67%   |
| Marvell Technology Group | 1         | 1.67%   |
| Broadcom Limited         | 1         | 1.67%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 16.42%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 5.97%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 5.97%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 2.99%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 2.99%   |
| Realtek 802.11ac NIC                                              | 2         | 2.99%   |
| Ralink MT7601U Wireless Adapter                                   | 2         | 2.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 2.99%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 2.99%   |
| Intel Wireless 7265                                               | 2         | 2.99%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 2.99%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 2.99%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 2.99%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 2.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 2.99%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.99%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 2.99%   |
| TP-Link 802.11ac WLAN Adapter                                     | 1         | 1.49%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 1.49%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 1.49%   |
| Ralink RT5572 Wireless Adapter                                    | 1         | 1.49%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.49%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 1         | 1.49%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1         | 1.49%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 1.49%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.49%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 1.49%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.49%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 1         | 1.49%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 1         | 1.49%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.49%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.49%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 1.49%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 1.49%   |
| Broadcom BCM43225 802.11b/g/n                                     | 1         | 1.49%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 1         | 1.49%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 1         | 1.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 17        | 40.48%  |
| Realtek Semiconductor | 10        | 23.81%  |
| Qualcomm Atheros      | 5         | 11.9%   |
| Ralink Technology     | 3         | 7.14%   |
| MediaTek              | 3         | 7.14%   |
| Broadcom              | 3         | 7.14%   |
| TP-Link               | 1         | 2.38%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 4         | 9.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 2         | 4.76%   |
| Realtek 802.11ac NIC                                          | 2         | 4.76%   |
| Ralink MT7601U Wireless Adapter                               | 2         | 4.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 2         | 4.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 2         | 4.76%   |
| Intel Wireless 7265                                           | 2         | 4.76%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 2         | 4.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 2         | 4.76%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 2         | 4.76%   |
| Intel Comet Lake PCH CNVi WiFi                                | 2         | 4.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 2         | 4.76%   |
| TP-Link 802.11ac WLAN Adapter                                 | 1         | 2.38%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 1         | 2.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 1         | 2.38%   |
| Ralink RT5572 Wireless Adapter                                | 1         | 2.38%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 1         | 2.38%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 1         | 2.38%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 1         | 2.38%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 1         | 2.38%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 1         | 2.38%   |
| Intel Wi-Fi 6 AX201                                           | 1         | 2.38%   |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 1         | 2.38%   |
| Intel Gemini Lake PCH CNVi WiFi                               | 1         | 2.38%   |
| Intel Centrino Ultimate-N 6300                                | 1         | 2.38%   |
| Broadcom BCM43225 802.11b/g/n                                 | 1         | 2.38%   |
| Broadcom BCM43224 802.11a/b/g/n                               | 1         | 2.38%   |
| Broadcom BCM4321 802.11a/b/g/n                                | 1         | 2.38%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 17        | 68%     |
| Intel                    | 4         | 16%     |
| Broadcom                 | 2         | 8%      |
| Marvell Technology Group | 1         | 4%      |
| Broadcom Limited         | 1         | 4%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 44%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 16%     |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 8%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 8%      |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 8%      |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 4%      |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 4%      |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 4%      |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 4%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 39        | 60.94%  |
| Ethernet | 25        | 39.06%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 35        | 85.37%  |
| Ethernet | 6         | 14.63%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 22        | 55%     |
| 1     | 16        | 40%     |
| 0     | 2         | 5%      |

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
| Intel                           | 14        | 43.75%  |
| Realtek Semiconductor           | 5         | 15.63%  |
| Qualcomm Atheros Communications | 3         | 9.38%   |
| IMC Networks                    | 2         | 6.25%   |
| Apple                           | 2         | 6.25%   |
| Realtek                         | 1         | 3.13%   |
| MediaTek                        | 1         | 3.13%   |
| Lite-On Technology              | 1         | 3.13%   |
| Foxconn / Hon Hai               | 1         | 3.13%   |
| Cambridge Silicon Radio         | 1         | 3.13%   |
| Broadcom                        | 1         | 3.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 7         | 21.88%  |
| Realtek Bluetooth Radio                             | 3         | 9.38%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 6.25%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 6.25%   |
| Intel Bluetooth wireless interface                  | 2         | 6.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 6.25%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 3.13%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 3.13%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 3.13%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 3.13%   |
| MediaTek Wireless_Device                            | 1         | 3.13%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 3.13%   |
| Intel AX210 Bluetooth                               | 1         | 3.13%   |
| IMC Networks Wireless_Device                        | 1         | 3.13%   |
| IMC Networks Bluetooth Device                       | 1         | 3.13%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 3.13%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.13%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 3.13%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 3.13%   |
| Apple Bluetooth HCI                                 | 1         | 3.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 32        | 74.42%  |
| AMD    | 7         | 16.28%  |
| Nvidia | 4         | 9.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 9.43%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 7.55%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 5.66%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 5.66%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 5.66%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 5.66%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 3.77%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 3.77%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 3.77%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 3.77%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 3.77%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 3.77%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 3.77%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 3.77%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 3.77%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2         | 3.77%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.89%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 1.89%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 1.89%   |
| Nvidia Audio device                                                                               | 1         | 1.89%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.89%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.89%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.89%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1         | 1.89%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.89%   |
| AMD FCH Azalia Controller                                                                         | 1         | 1.89%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 1.89%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 10        | 25%     |
| SK hynix            | 8         | 20%     |
| Micron Technology   | 8         | 20%     |
| Kingston            | 6         | 15%     |
| Crucial             | 3         | 7.5%    |
| Unknown (ABCD)      | 1         | 2.5%    |
| Unknown             | 1         | 2.5%    |
| Nanya Technology    | 1         | 2.5%    |
| ChangXin Memory     | 1         | 2.5%    |
| Unknown             | 1         | 2.5%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 4.65%   |
| Kingston RAM KF2933C17S4/16G 16GB SODIMM DDR4 2933MT/s           | 2         | 4.65%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 2.33%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 2.33%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.33%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.33%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.33%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 2.33%   |
| SK hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 2.33%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s     | 1         | 2.33%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 2.33%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 2.33%   |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 2.33%   |
| Samsung RAM M474A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 1         | 2.33%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 1         | 2.33%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 1         | 2.33%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.33%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.33%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 2.33%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 1         | 2.33%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.33%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM 4800MT/s               | 1         | 2.33%   |
| Samsung RAM K4A8G165WC-BCTD 4GB Row Of Chips DDR4 2667MT/s       | 1         | 2.33%   |
| Nanya RAM Module 1GB SODIMM DDR2 667MT/s                         | 1         | 2.33%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s          | 1         | 2.33%   |
| Micron RAM Module 4GB Row Of Chips DDR4 2400MT/s                 | 1         | 2.33%   |
| Micron RAM Module 2GB SODIMM DDR3 1866MT/s                       | 1         | 2.33%   |
| Micron RAM K4A8G165WB-BCRC 8GB Row Of Chips LPDDR4 3333MT/s      | 1         | 2.33%   |
| Micron RAM 8KTF25664HZ-1G6M1 2GB SODIMM DDR3 1600MT/s            | 1         | 2.33%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 1         | 2.33%   |
| Micron RAM 4ATF51264HZ-3G2R1 4GB SODIMM DDR4 3200MT/s            | 1         | 2.33%   |
| Micron RAM 16ATF2G64HZ-2G3E1 16GB SODIMM DDR4 2667MT/s           | 1         | 2.33%   |
| Kingston RAM KN2M64-ETB 8GB SODIMM DDR3 1600MT/s                 | 1         | 2.33%   |
| Kingston RAM ACR256X64D3S1333C9 2GB SODIMM DDR3 1334MT/s         | 1         | 2.33%   |
| Kingston RAM ACR16D3LS1KNG/4G 4GB SODIMM DDR3 1600MT/s           | 1         | 2.33%   |
| Kingston RAM 9905625-004.A03LF 4GB SODIMM DDR3 3200MT/s          | 1         | 2.33%   |
| Crucial RAM CT8G4SFRA32A.C8FP 8GB SODIMM DDR4 3200MT/s           | 1         | 2.33%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 1         | 2.33%   |
| Crucial RAM BL16G32C16S4B.16FE 16GB SODIMM DDR4 3200MT/s         | 1         | 2.33%   |
| ChangXin Memory RAM DB4ABAM-MK 1GB Row Of Chips LPDDR4 3733MT/s  | 1         | 2.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 17        | 48.57%  |
| DDR3   | 13        | 37.14%  |
| LPDDR4 | 3         | 8.57%   |
| DDR5   | 1         | 2.86%   |
| DDR2   | 1         | 2.86%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 29        | 85.29%  |
| Row Of Chips | 5         | 14.71%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 13        | 34.21%  |
| 4096  | 10        | 26.32%  |
| 16384 | 7         | 18.42%  |
| 2048  | 6         | 15.79%  |
| 1024  | 2         | 5.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 8         | 20.51%  |
| 3200  | 7         | 17.95%  |
| 2667  | 7         | 17.95%  |
| 1333  | 4         | 10.26%  |
| 2933  | 2         | 5.13%   |
| 2400  | 2         | 5.13%   |
| 1334  | 2         | 5.13%   |
| 4800  | 1         | 2.56%   |
| 3733  | 1         | 2.56%   |
| 3333  | 1         | 2.56%   |
| 2133  | 1         | 2.56%   |
| 1866  | 1         | 2.56%   |
| 1067  | 1         | 2.56%   |
| 667   | 1         | 2.56%   |

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
| Chicony Electronics                    | 7         | 22.58%  |
| Microdia                               | 4         | 12.9%   |
| IMC Networks                           | 3         | 9.68%   |
| Suyin                                  | 2         | 6.45%   |
| Realtek Semiconductor                  | 2         | 6.45%   |
| Quanta                                 | 2         | 6.45%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 6.45%   |
| Bison Electronics                      | 2         | 6.45%   |
| Apple                                  | 2         | 6.45%   |
| Sunplus Innovation Technology          | 1         | 3.23%   |
| Ricoh                                  | 1         | 3.23%   |
| Luxvisions Innotech Limited            | 1         | 3.23%   |
| Alcor Micro                            | 1         | 3.23%   |
| Acer                                   | 1         | 3.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                   | 3         | 9.68%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)     | 2         | 6.45%   |
| Quanta ov9734_techfront_camera                                  | 2         | 6.45%   |
| Chicony HD Webcam                                               | 2         | 6.45%   |
| Bison HD Webcam                                                 | 2         | 6.45%   |
| Sunplus Integrated_Webcam_HD                                    | 1         | 3.23%   |
| Ricoh Laptop_Integrated_Webcam_FHD                              | 1         | 3.23%   |
| Realtek HP Webcam                                               | 1         | 3.23%   |
| Realtek HD Webcam - Realtek                                     | 1         | 3.23%   |
| Microdia Webcam Vitade AF                                       | 1         | 3.23%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 1         | 3.23%   |
| IMC Networks Integrated Camera                                  | 1         | 3.23%   |
| IMC Networks HP TrueVision HD Camera                            | 1         | 3.23%   |
| IMC Networks HD Camera                                          | 1         | 3.23%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 1         | 3.23%   |
| Chicony Integrated HD WebCam                                    | 1         | 3.23%   |
| Chicony HP Wide Vision HD Camera                                | 1         | 3.23%   |
| Chicony HP Truevision HD                                        | 1         | 3.23%   |
| Chicony HD User Facing                                          | 1         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 1         | 3.23%   |
| Apple FaceTime Camera                                           | 1         | 3.23%   |
| Apple Built-in iSight [Micron]                                  | 1         | 3.23%   |
| Alcor Micro USB 2.0 Camera                                      | 1         | 3.23%   |
| Acer Integrated Camera                                          | 1         | 3.23%   |

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
| 0     | 30        | 75%     |
| 1     | 8         | 20%     |
| 2     | 2         | 5%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 5         | 41.67%  |
| Storage               | 2         | 16.67%  |
| Net/wireless          | 2         | 16.67%  |
| Multimedia controller | 1         | 8.33%   |
| Graphics card         | 1         | 8.33%   |
| Chipcard              | 1         | 8.33%   |

