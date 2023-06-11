Archcraft - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Archcraft.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Archcraft/Desktop/README.md) and [notebooks](/Dist/Archcraft/Notebook/README.md).

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

Total: 58

| Vendor    | Model                       | Form-Factor | Probe                                                      | Date         |
|-----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HUAWEI    | NBD-WXX9                    | Notebook    | [61c1703e67](https://linux-hardware.org/?probe=61c1703e67) | Jun 10, 2023 |
| HUAWEI    | NBD-WXX9                    | Notebook    | [321ad38786](https://linux-hardware.org/?probe=321ad38786) | Jun 10, 2023 |
| ASRock    | B550M Pro4                  | Desktop     | [8529d01687](https://linux-hardware.org/?probe=8529d01687) | May 27, 2023 |
| ASRock    | B550M Pro4                  | Desktop     | [8301ca5155](https://linux-hardware.org/?probe=8301ca5155) | May 27, 2023 |
| HUAWEI    | BOHB-WAX9                   | Notebook    | [08eb3979f4](https://linux-hardware.org/?probe=08eb3979f4) | May 19, 2023 |
| Dell      | Latitude 5490               | Notebook    | [2ce70b7a2c](https://linux-hardware.org/?probe=2ce70b7a2c) | May 04, 2023 |
| ASUSTek   | ROG Strix G513RC_G513RC     | Notebook    | [eeef579322](https://linux-hardware.org/?probe=eeef579322) | Apr 28, 2023 |
| MSI       | Alpha 15 B5EEK              | Notebook    | [c7f5eaf3f1](https://linux-hardware.org/?probe=c7f5eaf3f1) | Mar 28, 2023 |
| eMachines | eME730                      | Notebook    | [0e1683ee34](https://linux-hardware.org/?probe=0e1683ee34) | Mar 08, 2023 |
| eMachines | eME730                      | Notebook    | [db15f88805](https://linux-hardware.org/?probe=db15f88805) | Mar 08, 2023 |
| ASUSTek   | PRIME X470-PRO              | Desktop     | [f9df27503f](https://linux-hardware.org/?probe=f9df27503f) | Feb 03, 2023 |
| MSI       | Katana GF66 11UE            | Notebook    | [aead8d4d18](https://linux-hardware.org/?probe=aead8d4d18) | Jan 26, 2023 |
| HP        | Stream Laptop 11-ak0xxx     | Notebook    | [6f3b4fc131](https://linux-hardware.org/?probe=6f3b4fc131) | Jan 16, 2023 |
| HP        | Stream Laptop 11-ak0xxx     | Notebook    | [b33bedc4c2](https://linux-hardware.org/?probe=b33bedc4c2) | Jan 15, 2023 |
| HP        | Stream Laptop 11-ak0xxx     | Notebook    | [806da9b386](https://linux-hardware.org/?probe=806da9b386) | Jan 12, 2023 |
| HP        | Stream Laptop 11-ak0xxx     | Notebook    | [29e6fcfd32](https://linux-hardware.org/?probe=29e6fcfd32) | Jan 12, 2023 |
| Dell      | Inspiron 7559               | Notebook    | [52cf8ddc0f](https://linux-hardware.org/?probe=52cf8ddc0f) | Dec 22, 2022 |
| ASUSTek   | H110M-E/M.2                 | Desktop     | [82584d7e83](https://linux-hardware.org/?probe=82584d7e83) | Dec 20, 2022 |
| HP        | Stream Laptop 11-ak0xxx     | Notebook    | [d2c04dd7cd](https://linux-hardware.org/?probe=d2c04dd7cd) | Dec 01, 2022 |
| Chuwi     | GemiBook Pro                | Notebook    | [315d8b6ff7](https://linux-hardware.org/?probe=315d8b6ff7) | Nov 08, 2022 |
| MSI       | GF63 Thin 10SC              | Notebook    | [2b22722ce8](https://linux-hardware.org/?probe=2b22722ce8) | Oct 27, 2022 |
| ASUSTek   | H110M-E/M.2                 | Desktop     | [fb73fb5efc](https://linux-hardware.org/?probe=fb73fb5efc) | Oct 18, 2022 |
| ASUSTek   | H110M-E/M.2                 | Desktop     | [77fd87ca91](https://linux-hardware.org/?probe=77fd87ca91) | Oct 18, 2022 |
| Gigabyte  | B550I AORUS PRO AX          | Desktop     | [704da5b600](https://linux-hardware.org/?probe=704da5b600) | Oct 07, 2022 |
| Gigabyte  | F2A68HM-DS2                 | Desktop     | [98e8df2d3d](https://linux-hardware.org/?probe=98e8df2d3d) | Sep 21, 2022 |
| Dell      | Latitude E6420              | Notebook    | [3ea84baba3](https://linux-hardware.org/?probe=3ea84baba3) | Sep 09, 2022 |
| Dell      | Latitude E6420              | Notebook    | [78fd24b713](https://linux-hardware.org/?probe=78fd24b713) | Sep 09, 2022 |
| Apple     | MacBook4,1                  | Notebook    | [500d050ad6](https://linux-hardware.org/?probe=500d050ad6) | Sep 06, 2022 |
| Apple     | MacBook4,1                  | Notebook    | [01b8531ddf](https://linux-hardware.org/?probe=01b8531ddf) | Sep 04, 2022 |
| Apple     | MacBook4,1                  | Notebook    | [9e4c1bc292](https://linux-hardware.org/?probe=9e4c1bc292) | Sep 04, 2022 |
| HP        | Notebook                    | Notebook    | [b0b97c0ea3](https://linux-hardware.org/?probe=b0b97c0ea3) | Aug 30, 2022 |
| HP        | Laptop 15-dw0xxx            | Notebook    | [8bb62c2062](https://linux-hardware.org/?probe=8bb62c2062) | Aug 24, 2022 |
| ASUSTek   | X441SA                      | Notebook    | [cb26c73037](https://linux-hardware.org/?probe=cb26c73037) | Aug 16, 2022 |
| Acer      | Swift SF113-31              | Notebook    | [1c4298ff33](https://linux-hardware.org/?probe=1c4298ff33) | Aug 08, 2022 |
| Acer      | Swift SF113-31              | Notebook    | [0f1ad8ccf7](https://linux-hardware.org/?probe=0f1ad8ccf7) | Aug 08, 2022 |
| Lenovo    | 3111 SDK0J40705 WIN 3425... | Desktop     | [543fe6b6a7](https://linux-hardware.org/?probe=543fe6b6a7) | Aug 07, 2022 |
| Dell      | XPS 13 9310 2-in-1          | Convertible | [9ac134681b](https://linux-hardware.org/?probe=9ac134681b) | Aug 06, 2022 |
| Dell      | Latitude E7250              | Notebook    | [2dd83a16c7](https://linux-hardware.org/?probe=2dd83a16c7) | Aug 01, 2022 |
| Medion    | E3223                       | Convertible | [8d78a4424e](https://linux-hardware.org/?probe=8d78a4424e) | Jul 06, 2022 |
| Acer      | Aspire E5-573               | Notebook    | [01f3150f60](https://linux-hardware.org/?probe=01f3150f60) | Jul 01, 2022 |
| Positivo  | CHT14B                      | Notebook    | [95566d3625](https://linux-hardware.org/?probe=95566d3625) | Jun 05, 2022 |
| MSI       | MAG B550 TOMAHAWK           | Desktop     | [bede15789b](https://linux-hardware.org/?probe=bede15789b) | Jun 02, 2022 |
| Framework | Laptop                      | Notebook    | [f8790adbf2](https://linux-hardware.org/?probe=f8790adbf2) | May 25, 2022 |
| Standard  | Unknown                     | Notebook    | [74971ae227](https://linux-hardware.org/?probe=74971ae227) | May 04, 2022 |
| HP        | Pavilion Laptop 15-eh0xx... | Notebook    | [c8c2ede566](https://linux-hardware.org/?probe=c8c2ede566) | Feb 11, 2022 |
| Dell      | Inspiron 3542               | Notebook    | [f3f3b08d89](https://linux-hardware.org/?probe=f3f3b08d89) | Feb 09, 2022 |
| Dell      | Inspiron 3542               | Notebook    | [e975782c15](https://linux-hardware.org/?probe=e975782c15) | Jan 31, 2022 |
| ECS       | G31T-M                      | Desktop     | [3820396d91](https://linux-hardware.org/?probe=3820396d91) | Jan 29, 2022 |
| Lenovo    | ThinkPad T430 2351AK9       | Notebook    | [19f50b09d5](https://linux-hardware.org/?probe=19f50b09d5) | Jan 21, 2022 |
| ASRock    | H97M Pro4                   | Desktop     | [232f2dad91](https://linux-hardware.org/?probe=232f2dad91) | Dec 15, 2021 |
| Apple     | MacBookAir4,1               | Notebook    | [ecc4515014](https://linux-hardware.org/?probe=ecc4515014) | Nov 01, 2021 |
| ASUSTek   | ROG DOMINUS EXTREME         | Desktop     | [0adc8fc04d](https://linux-hardware.org/?probe=0adc8fc04d) | Oct 12, 2021 |
| ASUSTek   | ROG DOMINUS EXTREME         | Desktop     | [b977489e9c](https://linux-hardware.org/?probe=b977489e9c) | Oct 12, 2021 |
| Google    | Kindred                     | Notebook    | [c2631a9488](https://linux-hardware.org/?probe=c2631a9488) | Jul 29, 2021 |
| HP        | Laptop 15q-bu1xx            | Notebook    | [af9f2a95ec](https://linux-hardware.org/?probe=af9f2a95ec) | Jun 28, 2021 |
| HP        | Pavilion Laptop 15-cc1xx    | Notebook    | [5e0e7e2b80](https://linux-hardware.org/?probe=5e0e7e2b80) | Jun 25, 2021 |
| HP        | Pavilion g4                 | Notebook    | [6a3471480a](https://linux-hardware.org/?probe=6a3471480a) | May 29, 2021 |
| MSI       | GL65 Leopard 10SFK          | Notebook    | [a9e5bb7556](https://linux-hardware.org/?probe=a9e5bb7556) | May 28, 2021 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Archcraft Rolling | 36        | 83.72%  |
| Archcraft         | 7         | 16.28%  |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Archcraft | 43        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.18.16-arch1-1        | 4         | 8.7%    |
| 6.2.13-arch1-1         | 2         | 4.35%   |
| 5.19.13-arch1-1        | 2         | 4.35%   |
| 5.12.7-arch1-1         | 2         | 4.35%   |
| 6.3.6-arch1-1          | 1         | 2.17%   |
| 6.3.4-arch1-1          | 1         | 2.17%   |
| 6.2.8-zen1-1-zen       | 1         | 2.17%   |
| 6.2.2-arch1-1          | 1         | 2.17%   |
| 6.2.12-arch1-1         | 1         | 2.17%   |
| 6.1.9-x64v1-xanmod1-1  | 1         | 2.17%   |
| 6.1.7-arch1-1          | 1         | 2.17%   |
| 6.1.4-x64v1-xanmod1-1  | 1         | 2.17%   |
| 6.1.1-arch1-1          | 1         | 2.17%   |
| 6.0.7-arch1-1          | 1         | 2.17%   |
| 6.0.2-arch1-1          | 1         | 2.17%   |
| 6.0.12-arch1-1         | 1         | 2.17%   |
| 6.0.10-x64v1-xanmod1-1 | 1         | 2.17%   |
| 5.19.9-arch1-1         | 1         | 2.17%   |
| 5.19.7-arch1-1         | 1         | 2.17%   |
| 5.19.6-arch1-1         | 1         | 2.17%   |
| 5.19.3-arch1-1         | 1         | 2.17%   |
| 5.18.9-zen1-1-zen      | 1         | 2.17%   |
| 5.18.6-arch1-1         | 1         | 2.17%   |
| 5.18.14-zen1-1-zen     | 1         | 2.17%   |
| 5.18.0-arch1-1         | 1         | 2.17%   |
| 5.17.9-arch1-1         | 1         | 2.17%   |
| 5.17.6-arch1-1         | 1         | 2.17%   |
| 5.17.5-arch1-1         | 1         | 2.17%   |
| 5.16.8-arch1-1         | 1         | 2.17%   |
| 5.16.7-arch1-1         | 1         | 2.17%   |
| 5.16.4-arch1-1         | 1         | 2.17%   |
| 5.16.3-arch1-1         | 1         | 2.17%   |
| 5.16.1-arch1-1         | 1         | 2.17%   |
| 5.15.7-zen1-1-zen      | 1         | 2.17%   |
| 5.15.43-1-lts          | 1         | 2.17%   |
| 5.14.15-arch1-1        | 1         | 2.17%   |
| 5.14.10-arch1-1        | 1         | 2.17%   |
| 5.12.9-arch1-1         | 1         | 2.17%   |
| 5.12.12-arch1-1        | 1         | 2.17%   |
| 5.10.54-1-lts          | 1         | 2.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.18.16 | 4         | 8.7%    |
| 6.2.13  | 2         | 4.35%   |
| 5.19.13 | 2         | 4.35%   |
| 5.12.7  | 2         | 4.35%   |
| 6.3.6   | 1         | 2.17%   |
| 6.3.4   | 1         | 2.17%   |
| 6.2.8   | 1         | 2.17%   |
| 6.2.2   | 1         | 2.17%   |
| 6.2.12  | 1         | 2.17%   |
| 6.1.9   | 1         | 2.17%   |
| 6.1.7   | 1         | 2.17%   |
| 6.1.4   | 1         | 2.17%   |
| 6.1.1   | 1         | 2.17%   |
| 6.0.7   | 1         | 2.17%   |
| 6.0.2   | 1         | 2.17%   |
| 6.0.12  | 1         | 2.17%   |
| 6.0.10  | 1         | 2.17%   |
| 5.19.9  | 1         | 2.17%   |
| 5.19.7  | 1         | 2.17%   |
| 5.19.6  | 1         | 2.17%   |
| 5.19.3  | 1         | 2.17%   |
| 5.18.9  | 1         | 2.17%   |
| 5.18.6  | 1         | 2.17%   |
| 5.18.14 | 1         | 2.17%   |
| 5.18.0  | 1         | 2.17%   |
| 5.17.9  | 1         | 2.17%   |
| 5.17.6  | 1         | 2.17%   |
| 5.17.5  | 1         | 2.17%   |
| 5.16.8  | 1         | 2.17%   |
| 5.16.7  | 1         | 2.17%   |
| 5.16.4  | 1         | 2.17%   |
| 5.16.3  | 1         | 2.17%   |
| 5.16.1  | 1         | 2.17%   |
| 5.15.7  | 1         | 2.17%   |
| 5.15.43 | 1         | 2.17%   |
| 5.14.15 | 1         | 2.17%   |
| 5.14.10 | 1         | 2.17%   |
| 5.12.9  | 1         | 2.17%   |
| 5.12.12 | 1         | 2.17%   |
| 5.10.54 | 1         | 2.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.18    | 8         | 17.78%  |
| 5.19    | 6         | 13.33%  |
| 6.2     | 5         | 11.11%  |
| 6.1     | 4         | 8.89%   |
| 6.0     | 4         | 8.89%   |
| 5.16    | 4         | 8.89%   |
| 5.12    | 4         | 8.89%   |
| 5.17    | 3         | 6.67%   |
| 6.3     | 2         | 4.44%   |
| 5.15    | 2         | 4.44%   |
| 5.14    | 2         | 4.44%   |
| 5.10    | 1         | 2.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 43        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Openbox  | 17        | 39.53%  |
| XFCE     | 9         | 20.93%  |
| bspwm    | 5         | 11.63%  |
| KDE5     | 2         | 4.65%   |
| GNOME    | 2         | 4.65%   |
| Unknown  | 2         | 4.65%   |
| sway     | 1         | 2.33%   |
| qtile    | 1         | 2.33%   |
| LXDE     | 1         | 2.33%   |
| i3       | 1         | 2.33%   |
| Hyprland | 1         | 2.33%   |
| dwm      | 1         | 2.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 39        | 90.7%   |
| Wayland | 4         | 9.3%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 29        | 67.44%  |
| Unknown | 7         | 16.28%  |
| LXDM    | 5         | 11.63%  |
| Ly      | 1         | 2.33%   |
| LightDM | 1         | 2.33%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 21        | 48.84%  |
| es_MX | 4         | 9.3%    |
| en_GB | 4         | 9.3%    |
| en_ZA | 2         | 4.65%   |
| en_IN | 2         | 4.65%   |
| tr_TR | 1         | 2.33%   |
| pt_BR | 1         | 2.33%   |
| pl_PL | 1         | 2.33%   |
| it_IT | 1         | 2.33%   |
| fr_FR | 1         | 2.33%   |
| es_ES | 1         | 2.33%   |
| en_SG | 1         | 2.33%   |
| en_PH | 1         | 2.33%   |
| de_DE | 1         | 2.33%   |
| de_AT | 1         | 2.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 31        | 72.09%  |
| BIOS | 12        | 27.91%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 31        | 72.09%  |
| Btrfs | 11        | 25.58%  |
| Xfs   | 1         | 2.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 32        | 74.42%  |
| Unknown | 6         | 13.95%  |
| MBR     | 5         | 11.63%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 36        | 83.72%  |
| Yes       | 7         | 16.28%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 25        | 58.14%  |
| Yes       | 18        | 41.86%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 7         | 16.28%  |
| Dell                | 6         | 13.95%  |
| MSI                 | 5         | 11.63%  |
| ASUSTek Computer    | 5         | 11.63%  |
| Lenovo              | 2         | 4.65%   |
| HUAWEI              | 2         | 4.65%   |
| Gigabyte Technology | 2         | 4.65%   |
| ASRock              | 2         | 4.65%   |
| Apple               | 2         | 4.65%   |
| Acer                | 2         | 4.65%   |
| Standard            | 1         | 2.33%   |
| Positivo            | 1         | 2.33%   |
| Medion              | 1         | 2.33%   |
| Google              | 1         | 2.33%   |
| Framework           | 1         | 2.33%   |
| eMachines           | 1         | 2.33%   |
| ECS                 | 1         | 2.33%   |
| Chuwi               | 1         | 2.33%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Positivo CHT14B                     | 1         | 2.33%   |
| MSI MS-7C91                         | 1         | 2.33%   |
| MSI Katana GF66 11UE                | 1         | 2.33%   |
| MSI GL65 Leopard 10SFK              | 1         | 2.33%   |
| MSI GF63 Thin 10SC                  | 1         | 2.33%   |
| MSI Alpha 15 B5EEK                  | 1         | 2.33%   |
| Medion E3223                        | 1         | 2.33%   |
| Lenovo ThinkPad T430 2351AK9        | 1         | 2.33%   |
| Lenovo ThinkCentre M710q 10MR0047US | 1         | 2.33%   |
| HUAWEI NBD-WXX9                     | 1         | 2.33%   |
| HUAWEI BOHB-WAX9                    | 1         | 2.33%   |
| HP Stream Laptop 11-ak0xxx          | 1         | 2.33%   |
| HP Pavilion Laptop 15-eh0xxx        | 1         | 2.33%   |
| HP Pavilion Laptop 15-cc1xx         | 1         | 2.33%   |
| HP Pavilion g4                      | 1         | 2.33%   |
| HP Notebook                         | 1         | 2.33%   |
| HP Laptop 15q-bu1xx                 | 1         | 2.33%   |
| HP Laptop 15-dw0xxx                 | 1         | 2.33%   |
| Google Kindred                      | 1         | 2.33%   |
| Gigabyte F2A68HM-DS2                | 1         | 2.33%   |
| Gigabyte B550I AORUS PRO AX         | 1         | 2.33%   |
| Framework Laptop                    | 1         | 2.33%   |
| eMachines eME730                    | 1         | 2.33%   |
| ECS G31T-M                          | 1         | 2.33%   |
| Dell XPS 13 9310 2-in-1             | 1         | 2.33%   |
| Dell Latitude E7250                 | 1         | 2.33%   |
| Dell Latitude E6420                 | 1         | 2.33%   |
| Dell Latitude 5490                  | 1         | 2.33%   |
| Dell Inspiron 7559                  | 1         | 2.33%   |
| Dell Inspiron 3542                  | 1         | 2.33%   |
| Chuwi GemiBook Pro                  | 1         | 2.33%   |
| ASUS X441SA                         | 1         | 2.33%   |
| ASUS ROG Strix G513RC_G513RC        | 1         | 2.33%   |
| ASUS ROG DOMINUS EXTREME            | 1         | 2.33%   |
| ASUS PRIME X470-PRO                 | 1         | 2.33%   |
| ASUS H110M-E/M.2                    | 1         | 2.33%   |
| ASRock H97M Pro4                    | 1         | 2.33%   |
| ASRock B550M Pro4                   | 1         | 2.33%   |
| Apple MacBookAir4,1                 | 1         | 2.33%   |
| Apple MacBook4,1                    | 1         | 2.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| HP Pavilion          | 3         | 6.98%   |
| Dell Latitude        | 3         | 6.98%   |
| HP Laptop            | 2         | 4.65%   |
| Dell Inspiron        | 2         | 4.65%   |
| ASUS ROG             | 2         | 4.65%   |
| Positivo CHT14B      | 1         | 2.33%   |
| MSI MS-7C91          | 1         | 2.33%   |
| MSI Katana           | 1         | 2.33%   |
| MSI GL65             | 1         | 2.33%   |
| MSI GF63             | 1         | 2.33%   |
| MSI Alpha            | 1         | 2.33%   |
| Medion E3223         | 1         | 2.33%   |
| Lenovo ThinkPad      | 1         | 2.33%   |
| Lenovo ThinkCentre   | 1         | 2.33%   |
| HUAWEI NBD-WXX9      | 1         | 2.33%   |
| HUAWEI BOHB-WAX9     | 1         | 2.33%   |
| HP Stream            | 1         | 2.33%   |
| HP Notebook          | 1         | 2.33%   |
| Google Kindred       | 1         | 2.33%   |
| Gigabyte F2A68HM-DS2 | 1         | 2.33%   |
| Gigabyte B550I       | 1         | 2.33%   |
| Framework Laptop     | 1         | 2.33%   |
| eMachines eME730     | 1         | 2.33%   |
| ECS G31T-M           | 1         | 2.33%   |
| Dell XPS             | 1         | 2.33%   |
| Chuwi GemiBook       | 1         | 2.33%   |
| ASUS X441SA          | 1         | 2.33%   |
| ASUS PRIME           | 1         | 2.33%   |
| ASUS H110M-E         | 1         | 2.33%   |
| ASRock H97M          | 1         | 2.33%   |
| ASRock B550M         | 1         | 2.33%   |
| Apple MacBookAir4    | 1         | 2.33%   |
| Apple MacBook4       | 1         | 2.33%   |
| Acer Swift           | 1         | 2.33%   |
| Acer Aspire          | 1         | 2.33%   |
| Unknown              | 1         | 2.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 8         | 18.6%   |
| 2020 | 7         | 16.28%  |
| 2017 | 4         | 9.3%    |
| 2014 | 4         | 9.3%    |
| 2018 | 3         | 6.98%   |
| 2016 | 3         | 6.98%   |
| 2011 | 3         | 6.98%   |
| 2022 | 2         | 4.65%   |
| 2019 | 2         | 4.65%   |
| 2015 | 2         | 4.65%   |
| 2012 | 2         | 4.65%   |
| 2010 | 1         | 2.33%   |
| 2008 | 1         | 2.33%   |
| 2007 | 1         | 2.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 31        | 72.09%  |
| Desktop     | 10        | 23.26%  |
| Convertible | 2         | 4.65%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 43        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 42        | 97.67%  |
| Yes  | 1         | 2.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 13        | 30.23%  |
| 32.01-64.0  | 8         | 18.6%   |
| 3.01-4.0    | 7         | 16.28%  |
| 8.01-16.0   | 6         | 13.95%  |
| 16.01-24.0  | 5         | 11.63%  |
| 1.01-2.0    | 2         | 4.65%   |
| 24.01-32.0  | 1         | 2.33%   |
| 64.01-256.0 | 1         | 2.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 14        | 31.11%  |
| 1.01-2.0  | 14        | 31.11%  |
| 4.01-8.0  | 7         | 15.56%  |
| 3.01-4.0  | 7         | 15.56%  |
| 0.51-1.0  | 2         | 4.44%   |
| 8.01-16.0 | 1         | 2.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 21        | 48.84%  |
| 2      | 15        | 34.88%  |
| 3      | 3         | 6.98%   |
| 5      | 2         | 4.65%   |
| 4      | 2         | 4.65%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 35        | 81.4%   |
| Yes       | 8         | 18.6%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 74.42%  |
| No        | 11        | 25.58%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 37        | 86.05%  |
| No        | 6         | 13.95%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 74.42%  |
| No        | 11        | 25.58%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 7         | 16.28%  |
| Mexico             | 5         | 11.63%  |
| UK                 | 4         | 9.3%    |
| India              | 4         | 9.3%    |
| South Africa       | 2         | 4.65%   |
| Germany            | 2         | 4.65%   |
| Brazil             | 2         | 4.65%   |
| Vietnam            | 1         | 2.33%   |
| Turkey             | 1         | 2.33%   |
| Thailand           | 1         | 2.33%   |
| Spain              | 1         | 2.33%   |
| Slovakia           | 1         | 2.33%   |
| Russia             | 1         | 2.33%   |
| Philippines        | 1         | 2.33%   |
| Malaysia           | 1         | 2.33%   |
| Italy              | 1         | 2.33%   |
| Indonesia          | 1         | 2.33%   |
| Hungary            | 1         | 2.33%   |
| France             | 1         | 2.33%   |
| Finland            | 1         | 2.33%   |
| Dominican Republic | 1         | 2.33%   |
| Czechia            | 1         | 2.33%   |
| Austria            | 1         | 2.33%   |
| Argentina          | 1         | 2.33%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| New Delhi          | 2         | 4.55%   |
| Cape Town          | 2         | 4.55%   |
| Welwyn Garden City | 1         | 2.27%   |
| Vienna             | 1         | 2.27%   |
| Ulm                | 1         | 2.27%   |
| Torreón           | 1         | 2.27%   |
| Tirunelveli        | 1         | 2.27%   |
| Tábor             | 1         | 2.27%   |
| Stevens Point      | 1         | 2.27%   |
| Seremban           | 1         | 2.27%   |
| Sao Paulo          | 1         | 2.27%   |
| Santo Domingo Este | 1         | 2.27%   |
| Santa Rosa         | 1         | 2.27%   |
| Rocca di Papa      | 1         | 2.27%   |
| Osasco             | 1         | 2.27%   |
| Monterrey          | 1         | 2.27%   |
| Milton Keynes      | 1         | 2.27%   |
| Mazatlán          | 1         | 2.27%   |
| Mar del Plata      | 1         | 2.27%   |
| Manchester         | 1         | 2.27%   |
| Malang             | 1         | 2.27%   |
| Madrid             | 1         | 2.27%   |
| Loskutova          | 1         | 2.27%   |
| London             | 1         | 2.27%   |
| Lannion            | 1         | 2.27%   |
| Jorge Negrete      | 1         | 2.27%   |
| Istanbul           | 1         | 2.27%   |
| Ibbenbueren        | 1         | 2.27%   |
| Helsinki           | 1         | 2.27%   |
| Hanoi              | 1         | 2.27%   |
| Guadalajara        | 1         | 2.27%   |
| Gebze              | 1         | 2.27%   |
| Frisco             | 1         | 2.27%   |
| Clifton Park       | 1         | 2.27%   |
| Čadca             | 1         | 2.27%   |
| Budapest           | 1         | 2.27%   |
| Bhubaneswar        | 1         | 2.27%   |
| Bangkok            | 1         | 2.27%   |
| Austin             | 1         | 2.27%   |
| Atlanta            | 1         | 2.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 8         | 8      | 11.59%  |
| Seagate                     | 7         | 11     | 10.14%  |
| Unknown                     | 5         | 8      | 7.25%   |
| Samsung Electronics         | 5         | 5      | 7.25%   |
| Sandisk                     | 4         | 4      | 5.8%    |
| Phison Electronics          | 4         | 4      | 5.8%    |
| Toshiba                     | 3         | 3      | 4.35%   |
| Kingston                    | 3         | 3      | 4.35%   |
| Intel                       | 3         | 6      | 4.35%   |
| SK hynix                    | 2         | 2      | 2.9%    |
| Phison                      | 2         | 2      | 2.9%    |
| KIOXIA                      | 2         | 2      | 2.9%    |
| Hitachi                     | 2         | 2      | 2.9%    |
| Crucial                     | 2         | 2      | 2.9%    |
| Unknown                     | 2         | 2      | 2.9%    |
| Yangtze Memory Technologies | 1         | 1      | 1.45%   |
| ROG                         | 1         | 1      | 1.45%   |
| Patriot                     | 1         | 1      | 1.45%   |
| Netac                       | 1         | 1      | 1.45%   |
| Mushkin                     | 1         | 2      | 1.45%   |
| Micron/Crucial Technology   | 1         | 1      | 1.45%   |
| Kingston Technology Company | 1         | 2      | 1.45%   |
| KingFast                    | 1         | 2      | 1.45%   |
| Initio                      | 1         | 1      | 1.45%   |
| HGST                        | 1         | 1      | 1.45%   |
| Gigabyte Technology         | 1         | 2      | 1.45%   |
| China                       | 1         | 2      | 1.45%   |
| Apple                       | 1         | 1      | 1.45%   |
| Apacer                      | 1         | 1      | 1.45%   |
| A-DATA Technology           | 1         | 2      | 1.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST500LM030-2E717D 500GB                     | 2         | 2.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 2         | 2.7%    |
| Phison E16 PCIe4 NVMe Controller 1TB                | 2         | 2.7%    |
| Unknown                                             | 2         | 2.7%    |
| Yangtze Memory YMTC PC005 256GB                     | 1         | 1.35%   |
| WDC WDS500G2B0C-00PXH0 500GB                        | 1         | 1.35%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1         | 1.35%   |
| WDC WD5000AAKX-75U6AA0 500GB                        | 1         | 1.35%   |
| WDC WD5000AAKX-08U6AA0 500GB                        | 1         | 1.35%   |
| WDC WD3200BPVT-22JJ5T0 320GB                        | 1         | 1.35%   |
| WDC WD10SPZX-24Z10T0 1TB                            | 1         | 1.35%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 1         | 1.35%   |
| WDC WD10EZEX-22RKKA0 1TB                            | 1         | 1.35%   |
| Unknown SD/MMC/MS PRO 64GB                          | 1         | 1.35%   |
| Unknown SC128  128GB                                | 1         | 1.35%   |
| Unknown MMC Card  64GB                              | 1         | 1.35%   |
| Unknown MMC Card  32GB                              | 1         | 1.35%   |
| Unknown MMC Card  16GB                              | 1         | 1.35%   |
| Unknown Essentiel B 1TB                             | 1         | 1.35%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 1.35%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 1.35%   |
| Toshiba DT01ACA200 2TB                              | 1         | 1.35%   |
| SK hynix NVMe SSD Drive 128GB                       | 1         | 1.35%   |
| SK hynix HFS128G39TND-N210A 128GB SSD               | 1         | 1.35%   |
| Seagate ST6000DM003-2CY186 6TB                      | 1         | 1.35%   |
| Seagate ST3500410AS 500GB                           | 1         | 1.35%   |
| Seagate ST320LM001 HN-M320MBB 320GB                 | 1         | 1.35%   |
| Seagate ST31500341AS 1TB                            | 1         | 1.35%   |
| Seagate ST1000LM048-2E7172 1TB                      | 1         | 1.35%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1         | 1.35%   |
| Seagate Expansion 1TB                               | 1         | 1.35%   |
| Sandisk WD_BLACK SN770 1TB                          | 1         | 1.35%   |
| Sandisk WD PC SN735 SDBPNHH-512G-1002 512GB         | 1         | 1.35%   |
| Sandisk WD Blue SN570 1TB                           | 1         | 1.35%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 512GB     | 1         | 1.35%   |
| Samsung SSD PM871 mSATA 256GB                       | 1         | 1.35%   |
| Samsung SSD 970 EVO Plus 1TB                        | 1         | 1.35%   |
| Samsung SSD 860 EVO 1TB                             | 1         | 1.35%   |
| ROG ESD-S1C 1TB                                     | 1         | 1.35%   |
| Phison Sabrent Rocket 4.0 Plus 4TB                  | 1         | 1.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 11     | 33.33%  |
| WDC     | 6         | 6      | 28.57%  |
| Toshiba | 3         | 3      | 14.29%  |
| Unknown | 2         | 3      | 9.52%   |
| Hitachi | 2         | 2      | 9.52%   |
| HGST    | 1         | 1      | 4.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 10%     |
| Kingston            | 2         | 2      | 10%     |
| Intel               | 2         | 2      | 10%     |
| Unknown             | 2         | 2      | 10%     |
| WDC                 | 1         | 1      | 5%      |
| SK hynix            | 1         | 1      | 5%      |
| Phison              | 1         | 1      | 5%      |
| Patriot             | 1         | 1      | 5%      |
| Netac               | 1         | 1      | 5%      |
| Initio              | 1         | 1      | 5%      |
| Gigabyte Technology | 1         | 2      | 5%      |
| Crucial             | 1         | 1      | 5%      |
| China               | 1         | 2      | 5%      |
| Apple               | 1         | 1      | 5%      |
| Apacer              | 1         | 1      | 5%      |
| A-DATA Technology   | 1         | 2      | 5%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 20        | 28     | 32.79%  |
| SSD     | 18        | 23     | 29.51%  |
| HDD     | 17        | 26     | 27.87%  |
| MMC     | 4         | 5      | 6.56%   |
| Unknown | 2         | 3      | 3.28%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 28        | 46     | 49.12%  |
| NVMe | 20        | 28     | 35.09%  |
| SAS  | 5         | 6      | 8.77%   |
| MMC  | 4         | 5      | 7.02%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 22        | 31     | 59.46%  |
| 0.51-1.0   | 13        | 16     | 35.14%  |
| 1.01-2.0   | 1         | 1      | 2.7%    |
| 4.01-10.0  | 1         | 1      | 2.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 11        | 25.58%  |
| 251-500        | 9         | 20.93%  |
| 1001-2000      | 7         | 16.28%  |
| 501-1000       | 6         | 13.95%  |
| More than 3000 | 3         | 6.98%   |
| 51-100         | 3         | 6.98%   |
| Unknown        | 2         | 4.65%   |
| 21-50          | 1         | 2.33%   |
| 2001-3000      | 1         | 2.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 21-50     | 11        | 25.58%  |
| 1-20      | 9         | 20.93%  |
| 51-100    | 7         | 16.28%  |
| 251-500   | 6         | 13.95%  |
| 101-250   | 4         | 9.3%    |
| 501-1000  | 3         | 6.98%   |
| Unknown   | 2         | 4.65%   |
| 1001-2000 | 1         | 2.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-75U6AA0 500GB   | 1         | 1      | 25%     |
| Seagate ST1000LM048-2E7172 1TB | 1         | 1      | 25%     |
| Hitachi HTS545032A7E380 320GB  | 1         | 1      | 25%     |
| HGST HTS545050A7E680 500GB     | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 25%     |
| Seagate | 1         | 1      | 25%     |
| Hitachi | 1         | 1      | 25%     |
| HGST    | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 25%     |
| Seagate | 1         | 1      | 25%     |
| Hitachi | 1         | 1      | 25%     |
| HGST    | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 4      | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST3500410AS 500GB | 1         | 2      | 50%     |
| Seagate ST31500341AS 1TB  | 1         | 2      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 4      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 32        | 56     | 65.31%  |
| Detected | 12        | 21     | 24.49%  |
| Malfunc  | 4         | 4      | 8.16%   |
| Failed   | 1         | 4      | 2.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 29        | 50.88%  |
| AMD                         | 6         | 10.53%  |
| SanDisk                     | 5         | 8.77%   |
| Phison Electronics          | 4         | 7.02%   |
| Samsung Electronics         | 3         | 5.26%   |
| Micron/Crucial Technology   | 2         | 3.51%   |
| KIOXIA                      | 2         | 3.51%   |
| Kingston Technology Company | 2         | 3.51%   |
| Yangtze Memory Technologies | 1         | 1.75%   |
| SK hynix                    | 1         | 1.75%   |
| Silicon Motion              | 1         | 1.75%   |
| ASMedia Technology          | 1         | 1.75%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 4.69%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 3         | 4.69%   |
| AMD 500 Series Chipset SATA Controller                                           | 3         | 4.69%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 2         | 3.13%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 2         | 3.13%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 2         | 3.13%   |
| Kingston Company Company Non-Volatile memory controller                          | 2         | 3.13%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 3.13%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 3.13%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 3.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 3.13%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 2         | 3.13%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 3.13%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 2         | 3.13%   |
| Yangtze Memory Non-Volatile memory controller                                    | 1         | 1.56%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 1.56%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 1.56%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                               | 1         | 1.56%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 1.56%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 1.56%   |
| SanDisk WD Black SN770 NVMe SSD                                                  | 1         | 1.56%   |
| SanDisk Non-Volatile memory controller                                           | 1         | 1.56%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 1.56%   |
| Phison E18 PCIe4 NVMe Controller                                                 | 1         | 1.56%   |
| Phison E12 NVMe Controller                                                       | 1         | 1.56%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 1         | 1.56%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 1.56%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 1.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 1.56%   |
| Intel Optane SSD 900P Series                                                     | 1         | 1.56%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 1.56%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 1.56%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.56%   |
| Intel C620 Series Chipset Family IDE Redirection                                 | 1         | 1.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.56%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 1         | 1.56%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 1.56%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 1.56%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 1.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 31        | 53.45%  |
| NVMe | 20        | 34.48%  |
| RAID | 4         | 6.9%    |
| IDE  | 3         | 5.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 34        | 79.07%  |
| AMD    | 9         | 20.93%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz              | 2         | 4.65%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz        | 2         | 4.65%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 2         | 4.65%   |
| Intel Xeon W-3175X CPU @ 3.10GHz               | 1         | 2.33%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz       | 1         | 2.33%   |
| Intel Pentium CPU N4200 @ 1.10GHz              | 1         | 2.33%   |
| Intel Core i7-8565U CPU @ 1.80GHz              | 1         | 2.33%   |
| Intel Core i7-8550U CPU @ 1.80GHz              | 1         | 2.33%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz             | 1         | 2.33%   |
| Intel Core i7-4510U CPU @ 2.00GHz              | 1         | 2.33%   |
| Intel Core i7-10750H CPU @ 2.60GHz             | 1         | 2.33%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 1         | 2.33%   |
| Intel Core i5-6500T CPU @ 2.50GHz              | 1         | 2.33%   |
| Intel Core i5-5300U CPU @ 2.30GHz              | 1         | 2.33%   |
| Intel Core i5-4690K CPU @ 3.50GHz              | 1         | 2.33%   |
| Intel Core i5-3320M CPU @ 2.60GHz              | 1         | 2.33%   |
| Intel Core i5-2540M CPU @ 2.60GHz              | 1         | 2.33%   |
| Intel Core i5-2467M CPU @ 1.60GHz              | 1         | 2.33%   |
| Intel Core i5-10300H CPU @ 2.50GHz             | 1         | 2.33%   |
| Intel Core i5-10210U CPU @ 1.60GHz             | 1         | 2.33%   |
| Intel Core i3-5005U CPU @ 2.00GHz              | 1         | 2.33%   |
| Intel Core i3-10110U CPU @ 2.10GHz             | 1         | 2.33%   |
| Intel Core i3 CPU M 350 @ 2.27GHz              | 1         | 2.33%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz           | 1         | 2.33%   |
| Intel Core 2 Duo CPU E4600 @ 2.40GHz           | 1         | 2.33%   |
| Intel Celeron N4020 CPU @ 1.10GHz              | 1         | 2.33%   |
| Intel Celeron J4125 CPU @ 2.00GHz              | 1         | 2.33%   |
| Intel Celeron CPU N3060 @ 1.60GHz              | 1         | 2.33%   |
| Intel Celeron 2957U @ 1.40GHz                  | 1         | 2.33%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz              | 1         | 2.33%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz        | 1         | 2.33%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 1         | 2.33%   |
| AMD Ryzen 7 6800H with Radeon Graphics         | 1         | 2.33%   |
| AMD Ryzen 7 5800H with Radeon Graphics         | 1         | 2.33%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 1         | 2.33%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 1         | 2.33%   |
| AMD Ryzen 5 4500U with Radeon Graphics         | 1         | 2.33%   |
| AMD Ryzen 5 3600 6-Core Processor              | 1         | 2.33%   |
| AMD A4-3330MX APU with Radeon HD Graphics      | 1         | 2.33%   |
| AMD A10-7800 Radeon R7, 12 Compute Cores 4C+8G | 1         | 2.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 11        | 25.58%  |
| Other                | 5         | 11.63%  |
| Intel Core i7        | 5         | 11.63%  |
| Intel Celeron        | 4         | 9.3%    |
| Intel Core i3        | 3         | 6.98%   |
| AMD Ryzen 7          | 3         | 6.98%   |
| AMD Ryzen 5          | 3         | 6.98%   |
| Intel Core 2 Duo     | 2         | 4.65%   |
| Intel Xeon           | 1         | 2.33%   |
| Intel Pentium Silver | 1         | 2.33%   |
| Intel Pentium        | 1         | 2.33%   |
| Intel Atom           | 1         | 2.33%   |
| AMD Ryzen 9          | 1         | 2.33%   |
| AMD A4               | 1         | 2.33%   |
| AMD A10              | 1         | 2.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 17        | 39.53%  |
| 2      | 15        | 34.88%  |
| 8      | 5         | 11.63%  |
| 6      | 4         | 9.3%    |
| 28     | 1         | 2.33%   |
| 12     | 1         | 2.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 43        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 29        | 67.44%  |
| 1      | 14        | 32.56%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 43        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 15        | 34.88%  |
| 0xa0652    | 2         | 4.65%   |
| 0x806d1    | 2         | 4.65%   |
| 0x706a8    | 2         | 4.65%   |
| 0x506e3    | 2         | 4.65%   |
| 0x206a7    | 2         | 4.65%   |
| 0x906e9    | 1         | 2.33%   |
| 0x806ec    | 1         | 2.33%   |
| 0x806ea    | 1         | 2.33%   |
| 0x806c1    | 1         | 2.33%   |
| 0x6fd      | 1         | 2.33%   |
| 0x506c9    | 1         | 2.33%   |
| 0x50654    | 1         | 2.33%   |
| 0x406c4    | 1         | 2.33%   |
| 0x40651    | 1         | 2.33%   |
| 0x306d4    | 1         | 2.33%   |
| 0x306c3    | 1         | 2.33%   |
| 0x306a9    | 1         | 2.33%   |
| 0x0a404102 | 1         | 2.33%   |
| 0x0a201016 | 1         | 2.33%   |
| 0x0a201009 | 1         | 2.33%   |
| 0x08701021 | 1         | 2.33%   |
| 0x08600106 | 1         | 2.33%   |
| 0x03000027 | 1         | 2.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 7         | 16.28%  |
| Zen 3         | 3         | 6.98%   |
| TigerLake     | 3         | 6.98%   |
| Skylake       | 3         | 6.98%   |
| Haswell       | 3         | 6.98%   |
| Goldmont plus | 3         | 6.98%   |
| Zen 2         | 2         | 4.65%   |
| Silvermont    | 2         | 4.65%   |
| SandyBridge   | 2         | 4.65%   |
| Icelake       | 2         | 4.65%   |
| CometLake     | 2         | 4.65%   |
| Broadwell     | 2         | 4.65%   |
| Zen+          | 1         | 2.33%   |
| Westmere      | 1         | 2.33%   |
| Steamroller   | 1         | 2.33%   |
| Penryn        | 1         | 2.33%   |
| K10 Llano     | 1         | 2.33%   |
| IvyBridge     | 1         | 2.33%   |
| Goldmont      | 1         | 2.33%   |
| Core          | 1         | 2.33%   |
| Unknown       | 1         | 2.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 31        | 55.36%  |
| Nvidia | 15        | 26.79%  |
| AMD    | 10        | 17.86%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 3         | 5.08%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 5.08%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 3.39%   |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 3.39%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 3.39%   |
| Intel HD Graphics 5500                                                                   | 2         | 3.39%   |
| Intel HD Graphics 530                                                                    | 2         | 3.39%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 3.39%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 3.39%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 3.39%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 3.39%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 3.39%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 3.39%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 3.39%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 3.39%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 1.69%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 1         | 1.69%   |
| Nvidia TU102 [TITAN RTX]                                                                 | 1         | 1.69%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 1.69%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.69%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 1.69%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 1.69%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 1.69%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1.69%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 1         | 1.69%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 1.69%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.69%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.69%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.69%   |
| Intel HD Graphics 630                                                                    | 1         | 1.69%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 1.69%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.69%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 1         | 1.69%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 1.69%   |
| AMD Sumo [Radeon HD 6480G]                                                               | 1         | 1.69%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 1         | 1.69%   |
| AMD Renoir                                                                               | 1         | 1.69%   |
| AMD Rembrandt [Radeon 680M]                                                              | 1         | 1.69%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 1         | 1.69%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 1         | 1.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 20        | 46.51%  |
| Intel + Nvidia | 9         | 20.93%  |
| 1 x Nvidia     | 4         | 9.3%    |
| 1 x AMD        | 4         | 9.3%    |
| 2 x AMD        | 2         | 4.65%   |
| Intel + AMD    | 2         | 4.65%   |
| AMD + Nvidia   | 2         | 4.65%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 31        | 70.45%  |
| Proprietary | 13        | 29.55%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 70.45%  |
| 7.01-8.0   | 4         | 9.09%   |
| 0.01-0.5   | 3         | 6.82%   |
| 5.01-6.0   | 2         | 4.55%   |
| 3.01-4.0   | 1         | 2.27%   |
| 16.01-24.0 | 1         | 2.27%   |
| 8.01-16.0  | 1         | 2.27%   |
| 0.51-1.0   | 1         | 2.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Chimei Innolux       | 7         | 14.29%  |
| BOE                  | 7         | 14.29%  |
| AU Optronics         | 6         | 12.24%  |
| LG Display           | 5         | 10.2%   |
| Samsung Electronics  | 4         | 8.16%   |
| PANDA                | 3         | 6.12%   |
| Dell                 | 3         | 6.12%   |
| ASUSTek Computer     | 2         | 4.08%   |
| Apple                | 2         | 4.08%   |
| Ancor Communications | 2         | 4.08%   |
| Sharp                | 1         | 2.04%   |
| Lenovo               | 1         | 2.04%   |
| Hewlett-Packard      | 1         | 2.04%   |
| Goldstar             | 1         | 2.04%   |
| BenQ                 | 1         | 2.04%   |
| AGO                  | 1         | 2.04%   |
| Acer                 | 1         | 2.04%   |
| Unknown              | 1         | 2.04%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch              | 2         | 3.92%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch          | 2         | 3.92%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 2         | 3.92%   |
| Sharp LCD Monitor SHP14F8 3840x2400 288x180mm 13.4-inch              | 1         | 1.96%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch    | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SEC335A 1366x768 309x174mm 14.0-inch | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch | 1         | 1.96%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 1         | 1.96%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 1         | 1.96%   |
| LG Display LCD Monitor LGD04B9 1920x1080 344x194mm 15.5-inch         | 1         | 1.96%   |
| LG Display LCD Monitor LGD04B1 1366x768 310x174mm 14.0-inch          | 1         | 1.96%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch          | 1         | 1.96%   |
| Lenovo LEN T2054pC LEN60D9 1440x900 419x262mm 19.5-inch              | 1         | 1.96%   |
| Hewlett-Packard V320 HPN3363 1920x1080 698x393mm 31.5-inch           | 1         | 1.96%   |
| Goldstar L1742 GSM449C 1280x1024 338x270mm 17.0-inch                 | 1         | 1.96%   |
| Dell SE2417HG DELD08E 1920x1080 521x293mm 23.5-inch                  | 1         | 1.96%   |
| Dell SE2417HG DELD08D 1920x1080 521x293mm 23.5-inch                  | 1         | 1.96%   |
| Dell S2421NX DEL41FB 1920x1080 527x296mm 23.8-inch                   | 1         | 1.96%   |
| Dell AW2518HF DELA101 1920x1080 540x300mm 24.3-inch                  | 1         | 1.96%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C03 2160x1440 296x197mm 14.0-inch     | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15E3 1920x1080 344x193mm 15.5-inch     | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 309x173mm 13.9-inch     | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN1147 1366x768 256x144mm 11.6-inch      | 1         | 1.96%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                | 1         | 1.96%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 1         | 1.96%   |
| BOE LCD Monitor BOE07FF 1920x1080 344x194mm 15.5-inch                | 1         | 1.96%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 1         | 1.96%   |
| BOE LCD Monitor BOE0644 1366x768 309x173mm 13.9-inch                 | 1         | 1.96%   |
| BenQ BL3200 BNQ8017 2560x1440 708x398mm 32.0-inch                    | 1         | 1.96%   |
| AU Optronics LCD Monitor AUOB78F 1920x1080 344x194mm 15.5-inch       | 1         | 1.96%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch       | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 344x194mm 15.5-inch       | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch        | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 1         | 1.96%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 531x299mm 24.0-inch         | 1         | 1.96%   |
| ASUSTek Computer ROG PG65UQ AUS65A1 3840x2160 1430x800mm 64.5-inch   | 1         | 1.96%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 21        | 43.75%  |
| 1366x768 (WXGA)  | 12        | 25%     |
| 3840x2160 (4K)   | 2         | 4.17%   |
| 2560x1440 (QHD)  | 2         | 4.17%   |
| 2256x1504        | 2         | 4.17%   |
| 3840x2400        | 1         | 2.08%   |
| 3440x1440        | 1         | 2.08%   |
| 3200x1080        | 1         | 2.08%   |
| 2160x1440        | 1         | 2.08%   |
| 1600x900 (HD+)   | 1         | 2.08%   |
| 1440x900 (WXGA+) | 1         | 2.08%   |
| 1280x800 (WXGA)  | 1         | 2.08%   |
| 1280x1024 (SXGA) | 1         | 2.08%   |
| Unknown          | 1         | 2.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 16        | 32%     |
| 13      | 9         | 18%     |
| 14      | 6         | 12%     |
| 24      | 4         | 8%      |
| 23      | 2         | 4%      |
| 12      | 2         | 4%      |
| 11      | 2         | 4%      |
| 64      | 1         | 2%      |
| 34      | 1         | 2%      |
| 32      | 1         | 2%      |
| 31      | 1         | 2%      |
| 27      | 1         | 2%      |
| 21      | 1         | 2%      |
| 19      | 1         | 2%      |
| 17      | 1         | 2%      |
| Unknown | 1         | 2%      |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 24        | 48.98%  |
| 201-300     | 11        | 22.45%  |
| 501-600     | 6         | 12.24%  |
| 701-800     | 2         | 4.08%   |
| 601-700     | 2         | 4.08%   |
| 401-500     | 2         | 4.08%   |
| 1001-1500   | 1         | 2.04%   |
| Unknown     | 1         | 2.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 36        | 78.26%  |
| 3/2     | 3         | 6.52%   |
| 16/10   | 3         | 6.52%   |
| 5/4     | 1         | 2.17%   |
| 4/3     | 1         | 2.17%   |
| 21/9    | 1         | 2.17%   |
| Unknown | 1         | 2.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 17        | 34%     |
| 81-90          | 11        | 22%     |
| 201-250        | 5         | 10%     |
| 71-80          | 4         | 8%      |
| 351-500        | 3         | 6%      |
| 51-60          | 2         | 4%      |
| 251-300        | 2         | 4%      |
| More than 1000 | 1         | 2%      |
| 61-70          | 1         | 2%      |
| 301-350        | 1         | 2%      |
| 151-200        | 1         | 2%      |
| 141-150        | 1         | 2%      |
| Unknown        | 1         | 2%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 18        | 36%     |
| 101-120       | 12        | 24%     |
| 51-100        | 11        | 22%     |
| 161-240       | 7         | 14%     |
| More than 240 | 1         | 2%      |
| Unknown       | 1         | 2%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 34        | 79.07%  |
| 2     | 9         | 20.93%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 25        | 39.68%  |
| Intel                    | 22        | 34.92%  |
| Ralink Technology        | 4         | 6.35%   |
| Qualcomm Atheros         | 4         | 6.35%   |
| Broadcom                 | 3         | 4.76%   |
| MediaTek                 | 2         | 3.17%   |
| TP-Link                  | 1         | 1.59%   |
| Marvell Technology Group | 1         | 1.59%   |
| Aquantia                 | 1         | 1.59%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 17.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 6.67%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 5.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 4%      |
| Ralink MT7601U Wireless Adapter                                   | 3         | 4%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 2.67%   |
| Intel Wireless 7265                                               | 2         | 2.67%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 2.67%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 2.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 2.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 2.67%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 2.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 2.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.67%   |
| TP-Link 802.11ac WLAN Adapter                                     | 1         | 1.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.33%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 1.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 1.33%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.33%   |
| Realtek 802.11ac NIC                                              | 1         | 1.33%   |
| Ralink RT5572 Wireless Adapter                                    | 1         | 1.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 1.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.33%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 1         | 1.33%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1         | 1.33%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.33%   |
| Intel Wireless-AC 9260                                            | 1         | 1.33%   |
| Intel Wireless 8265 / 8275                                        | 1         | 1.33%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 1.33%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 1.33%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.33%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 1         | 1.33%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.33%   |
| Intel Ethernet Connection (3) I219-LM                             | 1         | 1.33%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.33%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.33%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.33%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.33%   |
| Broadcom BCM43225 802.11b/g/n                                     | 1         | 1.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 19        | 47.5%   |
| Realtek Semiconductor | 7         | 17.5%   |
| Ralink Technology     | 4         | 10%     |
| Qualcomm Atheros      | 4         | 10%     |
| Broadcom              | 3         | 7.5%    |
| MediaTek              | 2         | 5%      |
| TP-Link               | 1         | 2.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 3         | 7.32%   |
| Ralink MT7601U Wireless Adapter                               | 3         | 7.32%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 2         | 4.88%   |
| Intel Wireless 7265                                           | 2         | 4.88%   |
| Intel Wi-Fi 6 AX201                                           | 2         | 4.88%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 2         | 4.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 2         | 4.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 2         | 4.88%   |
| Intel Comet Lake PCH CNVi WiFi                                | 2         | 4.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 2         | 4.88%   |
| TP-Link 802.11ac WLAN Adapter                                 | 1         | 2.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 1         | 2.44%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 1         | 2.44%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 1         | 2.44%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 1         | 2.44%   |
| Realtek 802.11ac NIC                                          | 1         | 2.44%   |
| Ralink RT5572 Wireless Adapter                                | 1         | 2.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 1         | 2.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 1         | 2.44%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 1         | 2.44%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 1         | 2.44%   |
| Intel Wireless-AC 9260                                        | 1         | 2.44%   |
| Intel Wireless 8265 / 8275                                    | 1         | 2.44%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 1         | 2.44%   |
| Intel Wi-Fi 6 AX200                                           | 1         | 2.44%   |
| Intel Gemini Lake PCH CNVi WiFi                               | 1         | 2.44%   |
| Broadcom BCM43225 802.11b/g/n                                 | 1         | 2.44%   |
| Broadcom BCM43224 802.11a/b/g/n                               | 1         | 2.44%   |
| Broadcom BCM4321 802.11a/b/g/n                                | 1         | 2.44%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 21        | 65.63%  |
| Intel                    | 8         | 25%     |
| Marvell Technology Group | 1         | 3.13%   |
| Broadcom                 | 1         | 3.13%   |
| Aquantia                 | 1         | 3.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 38.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 14.71%  |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 11.76%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 5.88%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 2.94%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 2.94%   |
| Intel I211 Gigabit Network Connection                             | 1         | 2.94%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.94%   |
| Intel Ethernet Connection (3) I219-LM                             | 1         | 2.94%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2.94%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 2.94%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 2.94%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.94%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 2.94%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 37        | 54.41%  |
| Ethernet | 31        | 45.59%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 30        | 68.18%  |
| Ethernet | 14        | 31.82%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 24        | 55.81%  |
| 1     | 17        | 39.53%  |
| 3     | 1         | 2.33%   |
| 0     | 1         | 2.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 29        | 67.44%  |
| Yes  | 14        | 32.56%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 17        | 53.13%  |
| Realtek Semiconductor           | 4         | 12.5%   |
| Qualcomm Atheros Communications | 2         | 6.25%   |
| Cambridge Silicon Radio         | 2         | 6.25%   |
| Apple                           | 2         | 6.25%   |
| MediaTek                        | 1         | 3.13%   |
| Lite-On Technology              | 1         | 3.13%   |
| IMC Networks                    | 1         | 3.13%   |
| Foxconn / Hon Hai               | 1         | 3.13%   |
| Broadcom                        | 1         | 3.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 7         | 21.88%  |
| Realtek Bluetooth Radio                             | 3         | 9.38%   |
| Intel Bluetooth wireless interface                  | 3         | 9.38%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 6.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 6.25%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 6.25%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 3.13%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 3.13%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 3.13%   |
| MediaTek Wireless_Device                            | 1         | 3.13%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 3.13%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 3.13%   |
| Intel AX210 Bluetooth                               | 1         | 3.13%   |
| Intel AX200 Bluetooth                               | 1         | 3.13%   |
| IMC Networks Bluetooth Device                       | 1         | 3.13%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 3.13%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 3.13%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 3.13%   |
| Apple Bluetooth HCI                                 | 1         | 3.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 33        | 54.1%   |
| AMD                 | 11        | 18.03%  |
| Nvidia              | 10        | 16.39%  |
| Logitech            | 2         | 3.28%   |
| C-Media Electronics | 2         | 3.28%   |
| Texas Instruments   | 1         | 1.64%   |
| Oculus VR           | 1         | 1.64%   |
| Kingston Technology | 1         | 1.64%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 4.23%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 4.23%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 4.23%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 4.23%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 4.23%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 2.82%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 2.82%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 2.82%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 2.82%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 2.82%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 2.82%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 2.82%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 2.82%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 2.82%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 2.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 2.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 2.82%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 2.82%   |
| AMD FCH Azalia Controller                                                                         | 2         | 2.82%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 2.82%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 1.41%   |
| Oculus VR Rift CV1 Audio                                                                          | 1         | 1.41%   |
| Nvidia TU102 High Definition Audio Controller                                                     | 1         | 1.41%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 1.41%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 1.41%   |
| Nvidia Audio device                                                                               | 1         | 1.41%   |
| Logitech H390 headset with microphone                                                             | 1         | 1.41%   |
| Logitech G432 Gaming Headset                                                                      | 1         | 1.41%   |
| Kingston Technology HyperX Quadcast                                                               | 1         | 1.41%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 1.41%   |
| Intel Lewisburg MROM 0                                                                            | 1         | 1.41%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.41%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.41%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1         | 1.41%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1         | 1.41%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 1.41%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 1.41%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 1.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 11        | 24.44%  |
| SK hynix            | 7         | 15.56%  |
| Kingston            | 6         | 13.33%  |
| Micron Technology   | 4         | 8.89%   |
| Crucial             | 4         | 8.89%   |
| Unknown (ABCD)      | 2         | 4.44%   |
| Unknown             | 2         | 4.44%   |
| Corsair             | 2         | 4.44%   |
| A-DATA Technology   | 2         | 4.44%   |
| Team                | 1         | 2.22%   |
| Nanya Technology    | 1         | 2.22%   |
| G.Skill             | 1         | 2.22%   |
| ChangXin Memory     | 1         | 2.22%   |
| Unknown             | 1         | 2.22%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 4.08%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 4.08%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 4.08%   |
| Kingston RAM KF2933C17S4/16G 16GB SODIMM DDR4 2933MT/s           | 2         | 4.08%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s              | 1         | 2.04%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1         | 2.04%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 1         | 2.04%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s              | 1         | 2.04%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.04%   |
| SK hynix RAM HMT451S6CFR6A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 2.04%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.04%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 2.04%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.04%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 2.04%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 2.04%   |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 2.04%   |
| Samsung RAM M474A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 1         | 2.04%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 1         | 2.04%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 2.04%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.04%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.04%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 2.04%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.04%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 1         | 2.04%   |
| Samsung RAM K4A8G165WC-BCTD 4GB Row Of Chips DDR4 2667MT/s       | 1         | 2.04%   |
| Nanya RAM Module 1GB SODIMM DDR2 667MT/s                         | 1         | 2.04%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s          | 1         | 2.04%   |
| Micron RAM Module 2GB SODIMM DDR3 1866MT/s                       | 1         | 2.04%   |
| Micron RAM 8KTF25664HZ-1G6M1 2GB SODIMM DDR3 1600MT/s            | 1         | 2.04%   |
| Micron RAM 16ATF2G64HZ-2G3E1 16GB SODIMM DDR4 2667MT/s           | 1         | 2.04%   |
| Kingston RAM KN2M64-ETB 8GB SODIMM DDR3 1600MT/s                 | 1         | 2.04%   |
| Kingston RAM KF3600C16D4/16GX 16384MB DIMM DDR4 3600MT/s         | 1         | 2.04%   |
| Kingston RAM ACR16D3LS1KNG/4G 4GB SODIMM DDR3 1600MT/s           | 1         | 2.04%   |
| Kingston RAM 9905625-004.A03LF 8GB SODIMM DDR4 3200MT/s          | 1         | 2.04%   |
| G.Skill RAM F4-3000C16-8GTZR 8GB DIMM DDR4 3200MT/s              | 1         | 2.04%   |
| Crucial RAM CT8G4SFRA32A.C8FP 8GB SODIMM DDR4 3200MT/s           | 1         | 2.04%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 1         | 2.04%   |
| Crucial RAM BL8G36C16U4B.M8FE1 8GB DIMM DDR4 3733MT/s            | 1         | 2.04%   |
| Crucial RAM BL16G32C16S4B.16FE 16GB SODIMM DDR4 3200MT/s         | 1         | 2.04%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s            | 1         | 2.04%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 20        | 51.28%  |
| DDR3   | 12        | 30.77%  |
| LPDDR4 | 4         | 10.26%  |
| SDRAM  | 1         | 2.56%   |
| DDR5   | 1         | 2.56%   |
| DDR2   | 1         | 2.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 27        | 71.05%  |
| DIMM         | 8         | 21.05%  |
| Row Of Chips | 3         | 7.89%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 18        | 41.86%  |
| 4096  | 9         | 20.93%  |
| 16384 | 7         | 16.28%  |
| 2048  | 5         | 11.63%  |
| 1024  | 3         | 6.98%   |
| 32768 | 1         | 2.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 9         | 20.45%  |
| 2667    | 8         | 18.18%  |
| 3200    | 6         | 13.64%  |
| 2133    | 3         | 6.82%   |
| 1333    | 3         | 6.82%   |
| 3733    | 2         | 4.55%   |
| 2933    | 2         | 4.55%   |
| 2400    | 2         | 4.55%   |
| 4800    | 1         | 2.27%   |
| 4267    | 1         | 2.27%   |
| 3800    | 1         | 2.27%   |
| 3600    | 1         | 2.27%   |
| 1866    | 1         | 2.27%   |
| 1334    | 1         | 2.27%   |
| 1067    | 1         | 2.27%   |
| 667     | 1         | 2.27%   |
| Unknown | 1         | 2.27%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| HP DeskJet 4720 series | 1         | 100%    |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 7         | 23.33%  |
| Microdia                               | 4         | 13.33%  |
| Acer                                   | 3         | 10%     |
| Realtek Semiconductor                  | 2         | 6.67%   |
| IMC Networks                           | 2         | 6.67%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 6.67%   |
| Apple                                  | 2         | 6.67%   |
| Alcor Micro                            | 2         | 6.67%   |
| Suyin                                  | 1         | 3.33%   |
| Sunplus Innovation Technology          | 1         | 3.33%   |
| Ricoh                                  | 1         | 3.33%   |
| Quanta                                 | 1         | 3.33%   |
| Logitech                               | 1         | 3.33%   |
| Generalplus Technology                 | 1         | 3.33%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                   | 3         | 10%     |
| Chicony HD WebCam                                               | 2         | 6.67%   |
| Alcor Micro USB 2.0 Camera                                      | 2         | 6.67%   |
| Acer HD Webcam                                                  | 2         | 6.67%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)     | 1         | 3.33%   |
| Sunplus Integrated_Webcam_HD                                    | 1         | 3.33%   |
| Ricoh Laptop_Integrated_Webcam_FHD                              | 1         | 3.33%   |
| Realtek HP Webcam                                               | 1         | 3.33%   |
| Realtek HD Webcam - Realtek                                     | 1         | 3.33%   |
| Quanta ov9734_techfront_camera                                  | 1         | 3.33%   |
| Microdia Webcam Vitade AF                                       | 1         | 3.33%   |
| Logitech HD Pro Webcam C920                                     | 1         | 3.33%   |
| IMC Networks HP TrueVision HD Camera                            | 1         | 3.33%   |
| IMC Networks HD Camera                                          | 1         | 3.33%   |
| Generalplus GENERAL WEBCAM                                      | 1         | 3.33%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 1         | 3.33%   |
| Chicony Integrated IR Camera                                    | 1         | 3.33%   |
| Chicony HP Wide Vision HD Camera                                | 1         | 3.33%   |
| Chicony HP Truevision HD                                        | 1         | 3.33%   |
| Chicony HD User Facing                                          | 1         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 1         | 3.33%   |
| Apple FaceTime Camera                                           | 1         | 3.33%   |
| Apple Built-in iSight [Micron]                                  | 1         | 3.33%   |
| Acer Integrated Camera                                          | 1         | 3.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Elan Microelectronics      | 2         | 50%     |
| Shenzhen Goodix Technology | 1         | 25%     |
| LighTuning Technology      | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Elan ELAN:ARM-M4                            | 2         | 50%     |
| Shenzhen Goodix  Fingerprint Device         | 1         | 25%     |
| LighTuning EgisTec Touch Fingerprint Sensor | 1         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 33        | 76.74%  |
| 1     | 7         | 16.28%  |
| 2     | 3         | 6.98%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 4         | 33.33%  |
| Net/wireless          | 2         | 16.67%  |
| Graphics card         | 2         | 16.67%  |
| Unassigned class      | 1         | 8.33%   |
| Storage               | 1         | 8.33%   |
| Multimedia controller | 1         | 8.33%   |
| Chipcard              | 1         | 8.33%   |

