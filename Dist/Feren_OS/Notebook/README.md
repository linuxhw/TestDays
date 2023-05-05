Feren OS - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for Feren OS.

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

Total: 63

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| HP        | Stream Notebook PC 13       | [455c6b5e28](https://linux-hardware.org/?probe=455c6b5e28) | Apr 23, 2023 |
| ASUSTek   | ZenBook UX425UA_UM425UA     | [787dfaa7d4](https://linux-hardware.org/?probe=787dfaa7d4) | Mar 15, 2023 |
| ASUSTek   | ZenBook UX425UA_UM425UA     | [fa9427d71f](https://linux-hardware.org/?probe=fa9427d71f) | Feb 22, 2023 |
| Acer      | Aspire E5-773               | [d8d1898a3b](https://linux-hardware.org/?probe=d8d1898a3b) | Dec 17, 2022 |
| Apple     | MacBookAir6,2               | [0d098f7432](https://linux-hardware.org/?probe=0d098f7432) | Nov 29, 2022 |
| HP        | Pavilion Laptop 14-bf0xx    | [79144ee806](https://linux-hardware.org/?probe=79144ee806) | Oct 25, 2022 |
| HP        | Pavilion Laptop 14-bf0xx    | [866d1ad750](https://linux-hardware.org/?probe=866d1ad750) | Oct 07, 2022 |
| ASUSTek   | N750JV                      | [04cc8b4e36](https://linux-hardware.org/?probe=04cc8b4e36) | Sep 24, 2022 |
| ASUSTek   | VivoBook_ASUSLaptop M350... | [b2b969b0e3](https://linux-hardware.org/?probe=b2b969b0e3) | Aug 01, 2022 |
| HP        | Pavilion Laptop 14-bf0xx    | [1449b21f55](https://linux-hardware.org/?probe=1449b21f55) | Jul 24, 2022 |
| MSI       | GS66 Stealth 10SE           | [fbdc7a2279](https://linux-hardware.org/?probe=fbdc7a2279) | Jun 17, 2022 |
| Dell      | Latitude E5570              | [f132300275](https://linux-hardware.org/?probe=f132300275) | Feb 23, 2022 |
| ASUSTek   | S400CA                      | [3d2d24d90e](https://linux-hardware.org/?probe=3d2d24d90e) | Jan 15, 2022 |
| ASUSTek   | ROG Zephyrus M16 GU603HE... | [a53f185048](https://linux-hardware.org/?probe=a53f185048) | Dec 22, 2021 |
| ASUSTek   | ROG Zephyrus M16 GU603HE... | [21ea8cfa3b](https://linux-hardware.org/?probe=21ea8cfa3b) | Dec 16, 2021 |
| ASUSTek   | ROG Zephyrus M16 GU603HE... | [cd47b9ae21](https://linux-hardware.org/?probe=cd47b9ae21) | Dec 05, 2021 |
| ASUSTek   | P552LJ                      | [6dbe422798](https://linux-hardware.org/?probe=6dbe422798) | Nov 29, 2021 |
| MSI       | GP72 7RDX                   | [502ad3be8e](https://linux-hardware.org/?probe=502ad3be8e) | Nov 29, 2021 |
| MSI       | GE66 Raider 11UG            | [fe677aa4e9](https://linux-hardware.org/?probe=fe677aa4e9) | Nov 20, 2021 |
| ASUSTek   | ROG Zephyrus M16 GU603HE... | [6d92264040](https://linux-hardware.org/?probe=6d92264040) | Nov 14, 2021 |
| ASUSTek   | ROG Zephyrus M16 GU603HE... | [b3836e81d2](https://linux-hardware.org/?probe=b3836e81d2) | Nov 13, 2021 |
| MSI       | Traveller 1591              | [46430a6e00](https://linux-hardware.org/?probe=46430a6e00) | Oct 04, 2021 |
| Dell      | Latitude E5430 vPro         | [8c45da134f](https://linux-hardware.org/?probe=8c45da134f) | Aug 01, 2021 |
| Lenovo    | ThinkPad X230 2325AT6       | [f0a5e0cbb6](https://linux-hardware.org/?probe=f0a5e0cbb6) | Jun 13, 2021 |
| ASUSTek   | VivoBook_ASUS Laptop E21... | [676f8cfa11](https://linux-hardware.org/?probe=676f8cfa11) | Jun 12, 2021 |
| Unknown   | Unknown                     | [16d75c0003](https://linux-hardware.org/?probe=16d75c0003) | Jun 11, 2021 |
| Lenovo    | ThinkPad X230 2325AT6       | [049671564e](https://linux-hardware.org/?probe=049671564e) | May 27, 2021 |
| Lenovo    | ThinkPad X230 2325AT6       | [cb5051e015](https://linux-hardware.org/?probe=cb5051e015) | May 27, 2021 |
| Lenovo    | XiaoXin Air 12 80UN         | [210f81171b](https://linux-hardware.org/?probe=210f81171b) | May 08, 2021 |
| HP        | Pavilion Gaming Laptop 1... | [6654328a0f](https://linux-hardware.org/?probe=6654328a0f) | May 05, 2021 |
| Lenovo    | Legion Y7000P 81LD          | [e3b22a36fb](https://linux-hardware.org/?probe=e3b22a36fb) | Apr 22, 2021 |
| Lenovo    | Legion Y7000P 81LD          | [f5715022b7](https://linux-hardware.org/?probe=f5715022b7) | Apr 22, 2021 |
| Sony      | VPCEE4J1E                   | [d919affcfd](https://linux-hardware.org/?probe=d919affcfd) | Jan 14, 2021 |
| Lenovo    | XiaoXin Air 12 80UN         | [7339b28f1b](https://linux-hardware.org/?probe=7339b28f1b) | Dec 26, 2020 |
| Lenovo    | XiaoXin Air 12 80UN         | [06c54d29ce](https://linux-hardware.org/?probe=06c54d29ce) | Dec 26, 2020 |
| Acer      | NG-VX5-591G-52AT            | [304a828df3](https://linux-hardware.org/?probe=304a828df3) | Nov 20, 2020 |
| HP        | ProBook 6560b               | [1e12011c45](https://linux-hardware.org/?probe=1e12011c45) | Nov 05, 2020 |
| ASUSTek   | X541NA                      | [fa42a090b5](https://linux-hardware.org/?probe=fa42a090b5) | Nov 03, 2020 |
| Sony      | SVF15318SNB                 | [600b06bc21](https://linux-hardware.org/?probe=600b06bc21) | Oct 15, 2020 |
| Lenovo    | ThinkPad X230 2325AT6       | [fb75c1edd7](https://linux-hardware.org/?probe=fb75c1edd7) | Oct 05, 2020 |
| Lenovo    | G550 2958                   | [6c33f8ea14](https://linux-hardware.org/?probe=6c33f8ea14) | Sep 13, 2020 |
| Lenovo    | ThinkPad X230 2325AT6       | [59ed33b893](https://linux-hardware.org/?probe=59ed33b893) | Sep 06, 2020 |
| HUAWEI    | BOHK-WAX9X                  | [58c99091e7](https://linux-hardware.org/?probe=58c99091e7) | Aug 29, 2020 |
| Toshiba   | Satellite T135D             | [e59691cfe7](https://linux-hardware.org/?probe=e59691cfe7) | Aug 28, 2020 |
| ASUSTek   | X550CA                      | [7f2bf35eb8](https://linux-hardware.org/?probe=7f2bf35eb8) | Jun 30, 2020 |
| ASUSTek   | X550CA                      | [fe533b45dd](https://linux-hardware.org/?probe=fe533b45dd) | Jun 17, 2020 |
| ASUSTek   | X550CA                      | [e07d0dce49](https://linux-hardware.org/?probe=e07d0dce49) | Jun 17, 2020 |
| Lenovo    | ThinkPad X230 2325AT6       | [b7b58ba2d6](https://linux-hardware.org/?probe=b7b58ba2d6) | Jun 10, 2020 |
| HP        | EliteBook Folio 1040 G1     | [c7abaff76b](https://linux-hardware.org/?probe=c7abaff76b) | Jun 02, 2020 |
| Lenovo    | ThinkPad X230 2325AT6       | [f3c754042c](https://linux-hardware.org/?probe=f3c754042c) | May 16, 2020 |
| Lenovo    | ThinkPad X230 2325AT6       | [cfa1314238](https://linux-hardware.org/?probe=cfa1314238) | May 04, 2020 |
| Apple     | MacBookPro8,1               | [b2b19968b0](https://linux-hardware.org/?probe=b2b19968b0) | May 03, 2020 |
| Lenovo    | ThinkPad X240 20AMS72901    | [ad1e10654b](https://linux-hardware.org/?probe=ad1e10654b) | Apr 30, 2020 |
| Fujitsu   | LIFEBOOK E554               | [bb918daf7b](https://linux-hardware.org/?probe=bb918daf7b) | Mar 29, 2020 |
| Acer      | Aspire 5733Z                | [ebca80c932](https://linux-hardware.org/?probe=ebca80c932) | Jan 04, 2020 |
| Acer      | Aspire 5733Z                | [05ef4a2f12](https://linux-hardware.org/?probe=05ef4a2f12) | Jan 02, 2020 |
| Acer      | Aspire 5733Z                | [b1af19a6ad](https://linux-hardware.org/?probe=b1af19a6ad) | Jan 02, 2020 |
| Dell      | Inspiron 3421               | [17f334232d](https://linux-hardware.org/?probe=17f334232d) | Jan 01, 2020 |
| Panasonic | CF-J10YYBHR                 | [e00043a374](https://linux-hardware.org/?probe=e00043a374) | Sep 27, 2019 |
| Panasonic | CF-J10YYBHR                 | [0005e1a411](https://linux-hardware.org/?probe=0005e1a411) | Aug 21, 2019 |
| Exo       | CloudbookE15                | [9a16d4a087](https://linux-hardware.org/?probe=9a16d4a087) | Aug 19, 2019 |
| Lenovo    | G50-45 80E3                 | [440ce358c0](https://linux-hardware.org/?probe=440ce358c0) | May 04, 2019 |
| Lenovo    | G50-45 80E3                 | [fa158b6a96](https://linux-hardware.org/?probe=fa158b6a96) | Apr 16, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Feren OS 20.04 | 25        | 59.52%  |
| Feren OS 18.04 | 17        | 40.48%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Feren OS | 41        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.11.0-37-generic       | 4         | 7.69%   |
| 5.8.0-55-generic        | 3         | 5.77%   |
| 5.3.0-51-generic        | 3         | 5.77%   |
| 5.8.0-50-generic        | 2         | 3.85%   |
| 5.4.0-52-generic        | 2         | 3.85%   |
| 5.4.0-42-generic        | 2         | 3.85%   |
| 5.3.0-53-generic        | 2         | 3.85%   |
| 5.15.0-48-generic       | 2         | 3.85%   |
| 5.0.0-37-generic        | 2         | 3.85%   |
| 5.8.0-53-generic        | 1         | 1.92%   |
| 5.8.0-48-generic        | 1         | 1.92%   |
| 5.8.0-36-generic        | 1         | 1.92%   |
| 5.4.0-58-generic        | 1         | 1.92%   |
| 5.4.0-54-generic        | 1         | 1.92%   |
| 5.4.0-51-generic        | 1         | 1.92%   |
| 5.4.0-48-generic        | 1         | 1.92%   |
| 5.4.0-47-generic        | 1         | 1.92%   |
| 5.4.0-45-generic        | 1         | 1.92%   |
| 5.3.0-59-generic        | 1         | 1.92%   |
| 5.3.0-42-generic        | 1         | 1.92%   |
| 5.17.5-76051705-generic | 1         | 1.92%   |
| 5.15.6-051506-generic   | 1         | 1.92%   |
| 5.15.0-69-generic       | 1         | 1.92%   |
| 5.15.0-67-generic       | 1         | 1.92%   |
| 5.15.0-60-generic       | 1         | 1.92%   |
| 5.15.0-56-generic       | 1         | 1.92%   |
| 5.15.0-53-generic       | 1         | 1.92%   |
| 5.15.0-41-generic       | 1         | 1.92%   |
| 5.13.0-40-generic       | 1         | 1.92%   |
| 5.13.0-30-generic       | 1         | 1.92%   |
| 5.13.0-22-generic       | 1         | 1.92%   |
| 5.13.0-21-generic       | 1         | 1.92%   |
| 5.11.0-40-generic       | 1         | 1.92%   |
| 5.11.0-16-generic       | 1         | 1.92%   |
| 5.0.0-29-generic        | 1         | 1.92%   |
| 5.0.0-25-generic        | 1         | 1.92%   |
| 4.15.0-58-generic       | 1         | 1.92%   |
| 4.15.0-48-generic       | 1         | 1.92%   |
| 4.15.0-47-generic       | 1         | 1.92%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 9         | 20.45%  |
| 5.8.0   | 7         | 15.91%  |
| 5.3.0   | 6         | 13.64%  |
| 5.15.0  | 6         | 13.64%  |
| 5.11.0  | 6         | 13.64%  |
| 5.13.0  | 3         | 6.82%   |
| 5.0.0   | 3         | 6.82%   |
| 4.15.0  | 2         | 4.55%   |
| 5.17.5  | 1         | 2.27%   |
| 5.15.6  | 1         | 2.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 9         | 20.45%  |
| 5.8     | 7         | 15.91%  |
| 5.15    | 7         | 15.91%  |
| 5.3     | 6         | 13.64%  |
| 5.11    | 6         | 13.64%  |
| 5.13    | 3         | 6.82%   |
| 5.0     | 3         | 6.82%   |
| 4.15    | 2         | 4.55%   |
| 5.17    | 1         | 2.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 41        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KDE        | 20        | 46.51%  |
| KDE5       | 17        | 39.53%  |
| Unknown    | 4         | 9.3%    |
| X-Cinnamon | 1         | 2.33%   |
| GNOME      | 1         | 2.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 41        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 30        | 73.17%  |
| LightDM | 10        | 24.39%  |
| TDM     | 1         | 2.44%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 11        | 26.19%  |
| en_GB   | 8         | 19.05%  |
| de_CH   | 4         | 9.52%   |
| en_IN   | 3         | 7.14%   |
| de_DE   | 3         | 7.14%   |
| Unknown | 3         | 7.14%   |
| nl_BE   | 1         | 2.38%   |
| fi_FI   | 1         | 2.38%   |
| es_VE   | 1         | 2.38%   |
| es_UY   | 1         | 2.38%   |
| es_ES   | 1         | 2.38%   |
| es_CL   | 1         | 2.38%   |
| en_CA   | 1         | 2.38%   |
| en_AU   | 1         | 2.38%   |
| en_AG   | 1         | 2.38%   |
| de_AT   | 1         | 2.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 27        | 65.85%  |
| BIOS | 14        | 34.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 37        | 88.1%   |
| Btrfs   | 2         | 4.76%   |
| Unknown | 2         | 4.76%   |
| Overlay | 1         | 2.38%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 33        | 80.49%  |
| GPT     | 8         | 19.51%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 40        | 97.56%  |
| Yes       | 1         | 2.44%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 32        | 78.05%  |
| Yes       | 9         | 21.95%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| ASUSTek Computer | 10        | 24.39%  |
| Lenovo           | 6         | 14.63%  |
| Hewlett-Packard  | 5         | 12.2%   |
| MSI              | 4         | 9.76%   |
| Dell             | 3         | 7.32%   |
| Acer             | 3         | 7.32%   |
| Sony             | 2         | 4.88%   |
| Apple            | 2         | 4.88%   |
| Toshiba          | 1         | 2.44%   |
| Panasonic        | 1         | 2.44%   |
| HUAWEI           | 1         | 2.44%   |
| Fujitsu          | 1         | 2.44%   |
| Exo              | 1         | 2.44%   |
| Unknown          | 1         | 2.44%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| ASUS ROG Zephyrus M16 GU603HE_GU603HE    | 2         | 4.88%   |
| Toshiba Satellite T135D                  | 1         | 2.44%   |
| Sony VPCEE4J1E                           | 1         | 2.44%   |
| Sony SVF15318SNB                         | 1         | 2.44%   |
| Panasonic CF-J10YYBHR                    | 1         | 2.44%   |
| MSI Traveller 1591                       | 1         | 2.44%   |
| MSI GS66 Stealth 10SE                    | 1         | 2.44%   |
| MSI GP72 7RDX                            | 1         | 2.44%   |
| MSI GE66 Raider 11UG                     | 1         | 2.44%   |
| Lenovo XiaoXin Air 12 80UN               | 1         | 2.44%   |
| Lenovo ThinkPad X240 20AMS72901          | 1         | 2.44%   |
| Lenovo ThinkPad X230 2325AT6             | 1         | 2.44%   |
| Lenovo Legion Y7000P 81LD                | 1         | 2.44%   |
| Lenovo G550 2958                         | 1         | 2.44%   |
| Lenovo G50-45 80E3                       | 1         | 2.44%   |
| HUAWEI BOHK-WAX9X                        | 1         | 2.44%   |
| HP Stream Notebook PC 13                 | 1         | 2.44%   |
| HP ProBook 6560b                         | 1         | 2.44%   |
| HP Pavilion Laptop 14-bf0xx              | 1         | 2.44%   |
| HP Pavilion Gaming Laptop 15-cx0xxx      | 1         | 2.44%   |
| HP EliteBook Folio 1040 G1               | 1         | 2.44%   |
| Fujitsu LIFEBOOK E554                    | 1         | 2.44%   |
| Exo CloudbookE15                         | 1         | 2.44%   |
| Dell Latitude E5570                      | 1         | 2.44%   |
| Dell Latitude E5430 vPro                 | 1         | 2.44%   |
| Dell Inspiron 3421                       | 1         | 2.44%   |
| ASUS ZenBook UX425UA_UM425UA             | 1         | 2.44%   |
| ASUS X550CA                              | 1         | 2.44%   |
| ASUS X541NA                              | 1         | 2.44%   |
| ASUS VivoBook_ASUSLaptop M3500QC_M3500QC | 1         | 2.44%   |
| ASUS VivoBook_ASUS Laptop E210MA_E210MA  | 1         | 2.44%   |
| ASUS S400CA                              | 1         | 2.44%   |
| ASUS P552LJ                              | 1         | 2.44%   |
| ASUS N750JV                              | 1         | 2.44%   |
| Apple MacBookPro8,1                      | 1         | 2.44%   |
| Apple MacBookAir6,2                      | 1         | 2.44%   |
| Acer NG-VX5-591G-52AT                    | 1         | 2.44%   |
| Acer Aspire E5-773                       | 1         | 2.44%   |
| Acer Aspire 5733Z                        | 1         | 2.44%   |
| Unknown                                  | 1         | 2.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 2         | 4.88%   |
| HP Pavilion           | 2         | 4.88%   |
| Dell Latitude         | 2         | 4.88%   |
| ASUS VivoBook         | 2         | 4.88%   |
| ASUS ROG              | 2         | 4.88%   |
| Acer Aspire           | 2         | 4.88%   |
| Toshiba Satellite     | 1         | 2.44%   |
| Sony VPCEE4J1E        | 1         | 2.44%   |
| Sony SVF15318SNB      | 1         | 2.44%   |
| Panasonic CF-J10YYBHR | 1         | 2.44%   |
| MSI Traveller         | 1         | 2.44%   |
| MSI GS66              | 1         | 2.44%   |
| MSI GP72              | 1         | 2.44%   |
| MSI GE66              | 1         | 2.44%   |
| Lenovo XiaoXin        | 1         | 2.44%   |
| Lenovo Legion         | 1         | 2.44%   |
| Lenovo G550           | 1         | 2.44%   |
| Lenovo G50-45         | 1         | 2.44%   |
| HUAWEI BOHK-WAX9X     | 1         | 2.44%   |
| HP Stream             | 1         | 2.44%   |
| HP ProBook            | 1         | 2.44%   |
| HP EliteBook          | 1         | 2.44%   |
| Fujitsu LIFEBOOK      | 1         | 2.44%   |
| Exo CloudbookE15      | 1         | 2.44%   |
| Dell Inspiron         | 1         | 2.44%   |
| ASUS ZenBook          | 1         | 2.44%   |
| ASUS X550CA           | 1         | 2.44%   |
| ASUS X541NA           | 1         | 2.44%   |
| ASUS S400CA           | 1         | 2.44%   |
| ASUS P552LJ           | 1         | 2.44%   |
| ASUS N750JV           | 1         | 2.44%   |
| Apple MacBookPro8     | 1         | 2.44%   |
| Apple MacBookAir6     | 1         | 2.44%   |
| Acer NG-VX5-591G-52AT | 1         | 2.44%   |
| Unknown               | 1         | 2.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 5         | 12.2%   |
| 2013 | 5         | 12.2%   |
| 2012 | 5         | 12.2%   |
| 2017 | 4         | 9.76%   |
| 2016 | 4         | 9.76%   |
| 2011 | 4         | 9.76%   |
| 2020 | 3         | 7.32%   |
| 2019 | 3         | 7.32%   |
| 2014 | 3         | 7.32%   |
| 2018 | 2         | 4.88%   |
| 2009 | 2         | 4.88%   |
| 2008 | 1         | 2.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 41        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 36        | 85.71%  |
| Enabled  | 6         | 14.29%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 41        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 11        | 25.58%  |
| 3.01-4.0    | 10        | 23.26%  |
| 8.01-16.0   | 10        | 23.26%  |
| 16.01-24.0  | 8         | 18.6%   |
| 1.01-2.0    | 2         | 4.65%   |
| 32.01-64.0  | 1         | 2.33%   |
| 64.01-256.0 | 1         | 2.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 21        | 44.68%  |
| 2.01-3.0 | 15        | 31.91%  |
| 3.01-4.0 | 6         | 12.77%  |
| 4.01-8.0 | 4         | 8.51%   |
| 0.51-1.0 | 1         | 2.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 29        | 69.05%  |
| 2      | 10        | 23.81%  |
| 3      | 3         | 7.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 28        | 66.67%  |
| Yes       | 14        | 33.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 82.93%  |
| No        | 7         | 17.07%  |

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
| Yes       | 30        | 71.43%  |
| No        | 12        | 28.57%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 7         | 17.07%  |
| UK          | 4         | 9.76%   |
| Switzerland | 4         | 9.76%   |
| Germany     | 4         | 9.76%   |
| India       | 3         | 7.32%   |
| Turkey      | 2         | 4.88%   |
| Poland      | 2         | 4.88%   |
| Australia   | 2         | 4.88%   |
| Venezuela   | 1         | 2.44%   |
| Uruguay     | 1         | 2.44%   |
| UAE         | 1         | 2.44%   |
| Spain       | 1         | 2.44%   |
| Japan       | 1         | 2.44%   |
| Guam        | 1         | 2.44%   |
| Greece      | 1         | 2.44%   |
| Finland     | 1         | 2.44%   |
| Chile       | 1         | 2.44%   |
| Canada      | 1         | 2.44%   |
| Bulgaria    | 1         | 2.44%   |
| Belgium     | 1         | 2.44%   |
| Argentina   | 1         | 2.44%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Oberwil-Lieli      | 3         | 6.82%   |
| Leicester          | 2         | 4.55%   |
| Istanbul           | 2         | 4.55%   |
| Escondido          | 2         | 4.55%   |
| Zurich             | 1         | 2.27%   |
| Ypsilanti          | 1         | 2.27%   |
| Yigo Village       | 1         | 2.27%   |
| Winterthur         | 1         | 2.27%   |
| Varna              | 1         | 2.27%   |
| Surat              | 1         | 2.27%   |
| Stuttgart          | 1         | 2.27%   |
| Santiago           | 1         | 2.27%   |
| Saitama            | 1         | 2.27%   |
| Plymouth           | 1         | 2.27%   |
| Phoenix            | 1         | 2.27%   |
| Montevideo         | 1         | 2.27%   |
| Moncton            | 1         | 2.27%   |
| Mieres             | 1         | 2.27%   |
| Maracay            | 1         | 2.27%   |
| Lancefield         | 1         | 2.27%   |
| Lafayette          | 1         | 2.27%   |
| Krakow             | 1         | 2.27%   |
| Kloten             | 1         | 2.27%   |
| Karlsruhe          | 1         | 2.27%   |
| Hyderabad          | 1         | 2.27%   |
| Hickory            | 1         | 2.27%   |
| Hämeenlinna       | 1         | 2.27%   |
| Gdynia             | 1         | 2.27%   |
| Gdansk             | 1         | 2.27%   |
| Ernakulam          | 1         | 2.27%   |
| Delmenhorst        | 1         | 2.27%   |
| Corpus Christi     | 1         | 2.27%   |
| Brisbane           | 1         | 2.27%   |
| Birstein           | 1         | 2.27%   |
| Banda del Rio Sali | 1         | 2.27%   |
| Ballymena          | 1         | 2.27%   |
| Athens             | 1         | 2.27%   |
| Al Ain City        | 1         | 2.27%   |
| Aartselaar         | 1         | 2.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Samsung Electronics   | 10        | 12     | 17.54%  |
| Unknown               | 7         | 10     | 12.28%  |
| SanDisk               | 5         | 6      | 8.77%   |
| Intel                 | 4         | 5      | 7.02%   |
| HGST                  | 4         | 4      | 7.02%   |
| Toshiba               | 3         | 5      | 5.26%   |
| Seagate               | 3         | 3      | 5.26%   |
| Hitachi               | 3         | 3      | 5.26%   |
| SK hynix              | 2         | 3      | 3.51%   |
| Phison                | 2         | 2      | 3.51%   |
| OCZ                   | 2         | 2      | 3.51%   |
| Kingston              | 2         | 2      | 3.51%   |
| A-DATA Technology     | 2         | 2      | 3.51%   |
| WDC                   | 1         | 1      | 1.75%   |
| Realtek Semiconductor | 1         | 1      | 1.75%   |
| PNY                   | 1         | 1      | 1.75%   |
| LITEON                | 1         | 1      | 1.75%   |
| KIOXIA                | 1         | 1      | 1.75%   |
| Crucial               | 1         | 4      | 1.75%   |
| China                 | 1         | 1      | 1.75%   |
| Apple                 | 1         | 1      | 1.75%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Seagate ST500LT012-9WS142 500GB                   | 2         | 3.39%   |
| Phison NVMe SSD Drive 1TB                         | 2         | 3.39%   |
| Intel NVMe SSD Drive 512GB                        | 2         | 3.39%   |
| HGST HTS721010A9E630 1TB                          | 2         | 3.39%   |
| WDC WD2500BPVT-00JJ5T0 250GB                      | 1         | 1.69%   |
| Unknown SDW32G  32GB                              | 1         | 1.69%   |
| Unknown SD/MMC/MS PRO 249GB                       | 1         | 1.69%   |
| Unknown SB128  128GB                              | 1         | 1.69%   |
| Unknown SA04G  4GB                                | 1         | 1.69%   |
| Unknown MMC Card  32GB                            | 1         | 1.69%   |
| Unknown MMC Card  256GB                           | 1         | 1.69%   |
| Unknown MMC Card  128GB                           | 1         | 1.69%   |
| Unknown APPSD  134GB                              | 1         | 1.69%   |
| Toshiba THNSNC128GNSJ 128GB SSD                   | 1         | 1.69%   |
| Toshiba Q300. 240GB SSD                           | 1         | 1.69%   |
| Toshiba MQ01ABD100 1TB                            | 1         | 1.69%   |
| SK hynix HFS128G32TND-N210A 128GB SSD             | 1         | 1.69%   |
| SK hynix HFM001TD3JX013N 1024GB                   | 1         | 1.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 1         | 1.69%   |
| SanDisk SSD U100 24GB                             | 1         | 1.69%   |
| SanDisk SD9SB8W256G1002 256GB SSD                 | 1         | 1.69%   |
| SanDisk SD8SN8U-128G-1006 128GB SSD               | 1         | 1.69%   |
| SanDisk SD6SN1M-256G-1006 256GB SSD               | 1         | 1.69%   |
| SanDisk NVMe SSD Drive 256GB                      | 1         | 1.69%   |
| Samsung SSD 860 EVO 250GB                         | 1         | 1.69%   |
| Samsung SSD 840 Series 120GB                      | 1         | 1.69%   |
| Samsung Portable SSD T5 500GB                     | 1         | 1.69%   |
| Samsung NVMe SSD Drive 256GB                      | 1         | 1.69%   |
| Samsung NVMe SSD Drive 1TB                        | 1         | 1.69%   |
| Samsung NVMe SSD Drive 1024GB                     | 1         | 1.69%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 1         | 1.69%   |
| Samsung MZVLW256HEHP-000H1 256GB                  | 1         | 1.69%   |
| Samsung MZVLW128HEGR-00000 128GB                  | 1         | 1.69%   |
| Samsung MZNTY128HDHP-000L2 128GB SSD              | 1         | 1.69%   |
| Realtek NVMe SSD Drive 512GB                      | 1         | 1.69%   |
| PNY CS900 500GB SSD                               | 1         | 1.69%   |
| OCZ VERTEX2 90GB SSD                              | 1         | 1.69%   |
| OCZ AGILITY3 120GB SSD                            | 1         | 1.69%   |
| LITEON IT LCS-128L9S-HP 128GB SSD                 | 1         | 1.69%   |
| KIOXIA KBG40ZNS256G NVMe 256GB                    | 1         | 1.69%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HGST    | 4         | 4      | 30.77%  |
| Seagate | 3         | 3      | 23.08%  |
| Hitachi | 3         | 3      | 23.08%  |
| WDC     | 1         | 1      | 7.69%   |
| Unknown | 1         | 1      | 7.69%   |
| Toshiba | 1         | 2      | 7.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 4         | 5      | 17.39%  |
| Samsung Electronics | 4         | 5      | 17.39%  |
| Toshiba             | 2         | 3      | 8.7%    |
| OCZ                 | 2         | 2      | 8.7%    |
| Kingston            | 2         | 2      | 8.7%    |
| A-DATA Technology   | 2         | 2      | 8.7%    |
| SK hynix            | 1         | 2      | 4.35%   |
| PNY                 | 1         | 1      | 4.35%   |
| LITEON              | 1         | 1      | 4.35%   |
| Intel               | 1         | 1      | 4.35%   |
| Crucial             | 1         | 4      | 4.35%   |
| China               | 1         | 1      | 4.35%   |
| Apple               | 1         | 1      | 4.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 20        | 30     | 38.46%  |
| NVMe | 13        | 17     | 25%     |
| HDD  | 13        | 14     | 25%     |
| MMC  | 6         | 9      | 11.54%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 28        | 41     | 56%     |
| NVMe | 13        | 17     | 26%     |
| MMC  | 6         | 9      | 12%     |
| SAS  | 3         | 3      | 6%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 24        | 36     | 77.42%  |
| 0.51-1.0   | 7         | 8      | 22.58%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 16        | 36.36%  |
| 251-500    | 10        | 22.73%  |
| 501-1000   | 6         | 13.64%  |
| 51-100     | 5         | 11.36%  |
| 1001-2000  | 4         | 9.09%   |
| 21-50      | 2         | 4.55%   |
| 1-20       | 1         | 2.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 21-50    | 19        | 41.3%   |
| 1-20     | 8         | 17.39%  |
| 51-100   | 8         | 17.39%  |
| 101-250  | 5         | 10.87%  |
| 251-500  | 3         | 6.52%   |
| 501-1000 | 3         | 6.52%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB          | 1         | 1      | 33.33%  |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 1         | 1      | 33.33%  |
| Samsung Electronics SSD 840 Series 120GB | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2         | 2      | 66.67%  |
| Samsung Electronics | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 2      | 66.67%  |
| SSD  | 1         | 1      | 33.33%  |

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
| Detected | 35        | 56     | 77.78%  |
| Works    | 7         | 11     | 15.56%  |
| Malfunc  | 3         | 3      | 6.67%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 29        | 61.7%   |
| Samsung Electronics   | 7         | 14.89%  |
| AMD                   | 4         | 8.51%   |
| Phison Electronics    | 2         | 4.26%   |
| SK hynix              | 1         | 2.13%   |
| SanDisk               | 1         | 2.13%   |
| Realtek Semiconductor | 1         | 2.13%   |
| Nvidia                | 1         | 2.13%   |
| KIOXIA                | 1         | 2.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 7.84%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 7.84%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 3         | 5.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 3.92%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 3.92%   |
| Phison E12 NVMe Controller                                                     | 2         | 3.92%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 3.92%   |
| Intel Non-Volatile memory controller                                           | 2         | 3.92%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 3.92%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 3.92%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 3.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 3.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 3.92%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 2         | 3.92%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 1         | 1.96%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 1.96%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 1.96%   |
| Samsung NVMe SSD Controller 980                                                | 1         | 1.96%   |
| Samsung Electronics SATA controller                                            | 1         | 1.96%   |
| Realtek NVMe Controller                                                        | 1         | 1.96%   |
| Nvidia nForce SATA Controller                                                  | 1         | 1.96%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 1         | 1.96%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.96%   |
| Intel SSD 600P Series                                                          | 1         | 1.96%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 1.96%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.96%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 1.96%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.96%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 1         | 1.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 31        | 63.27%  |
| NVMe | 13        | 26.53%  |
| RAID | 4         | 8.16%   |
| IDE  | 1         | 2.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 34        | 82.93%  |
| AMD    | 7         | 17.07%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 7.32%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 2         | 4.88%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 4.88%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 2.44%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 2.44%   |
| Intel Pentium CPU 4415U @ 2.30GHz             | 1         | 2.44%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz              | 1         | 2.44%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 2.44%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 2.44%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 2.44%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 1         | 2.44%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 2.44%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 2.44%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 2.44%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 2.44%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 2.44%   |
| Intel Core i5-4260U CPU @ 1.40GHz             | 1         | 2.44%   |
| Intel Core i5-4210M CPU @ 2.60GHz             | 1         | 2.44%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 2.44%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 2.44%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 2.44%   |
| Intel Core i5-2435M CPU @ 2.40GHz             | 1         | 2.44%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 2.44%   |
| Intel Core i3-2375M CPU @ 1.50GHz             | 1         | 2.44%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 2.44%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1         | 2.44%   |
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz   | 1         | 2.44%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 1         | 2.44%   |
| Intel Celeron CPU 1007U @ 1.50GHz             | 1         | 2.44%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 1         | 2.44%   |
| AMD Turion Neo X2 Dual Core Processor L625    | 1         | 2.44%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 1         | 2.44%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 1         | 2.44%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 2.44%   |
| AMD Athlon X2 Dual-Core QL-60                 | 1         | 2.44%   |
| AMD Athlon II P360 Dual-Core Processor        | 1         | 2.44%   |
| AMD A6-6310 APU with AMD Radeon R4 Graphics   | 1         | 2.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 14        | 34.15%  |
| Intel Core i7           | 5         | 12.2%   |
| Intel Celeron           | 4         | 9.76%   |
| Other                   | 3         | 7.32%   |
| Intel Pentium           | 3         | 7.32%   |
| Intel Core i3           | 2         | 4.88%   |
| Intel Core m3           | 1         | 2.44%   |
| Intel Celeron Dual-Core | 1         | 2.44%   |
| Intel Atom              | 1         | 2.44%   |
| AMD Turion Neo X2       | 1         | 2.44%   |
| AMD Ryzen 9             | 1         | 2.44%   |
| AMD Ryzen 7             | 1         | 2.44%   |
| AMD Ryzen 5             | 1         | 2.44%   |
| AMD Athlon X2           | 1         | 2.44%   |
| AMD Athlon II           | 1         | 2.44%   |
| AMD A6                  | 1         | 2.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 25        | 60.98%  |
| 4      | 10        | 24.39%  |
| 8      | 6         | 14.63%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 41        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 28        | 68.29%  |
| 1      | 13        | 31.71%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 39        | 95.12%  |
| Unknown        | 2         | 4.88%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x40651    | 4         | 9.76%   |
| 0x206a7    | 4         | 9.76%   |
| 0x806d1    | 3         | 7.32%   |
| 0x406e3    | 3         | 7.32%   |
| 0x306a9    | 3         | 7.32%   |
| 0x906e9    | 2         | 4.88%   |
| 0x706a8    | 2         | 4.88%   |
| 0x306c3    | 2         | 4.88%   |
| Unknown    | 2         | 4.88%   |
| 0xa0652    | 1         | 2.44%   |
| 0x906ea    | 1         | 2.44%   |
| 0x806ea    | 1         | 2.44%   |
| 0x806e9    | 1         | 2.44%   |
| 0x506c9    | 1         | 2.44%   |
| 0x406c4    | 1         | 2.44%   |
| 0x406c3    | 1         | 2.44%   |
| 0x306d4    | 1         | 2.44%   |
| 0x20655    | 1         | 2.44%   |
| 0x1067a    | 1         | 2.44%   |
| 0x0a50000c | 1         | 2.44%   |
| 0x08608103 | 1         | 2.44%   |
| 0x08108109 | 1         | 2.44%   |
| 0x07030105 | 1         | 2.44%   |
| 0x02000032 | 1         | 2.44%   |
| 0x010000c8 | 1         | 2.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Haswell         | 6         | 14.63%  |
| KabyLake        | 5         | 12.2%   |
| SandyBridge     | 4         | 9.76%   |
| IvyBridge       | 4         | 9.76%   |
| Skylake         | 3         | 7.32%   |
| Icelake         | 3         | 7.32%   |
| Silvermont      | 2         | 4.88%   |
| Goldmont plus   | 2         | 4.88%   |
| Zen+            | 1         | 2.44%   |
| Zen 3           | 1         | 2.44%   |
| Westmere        | 1         | 2.44%   |
| Puma            | 1         | 2.44%   |
| Penryn          | 1         | 2.44%   |
| K8 Hammer       | 1         | 2.44%   |
| K8 & K10 hybrid | 1         | 2.44%   |
| K10             | 1         | 2.44%   |
| Goldmont        | 1         | 2.44%   |
| CometLake       | 1         | 2.44%   |
| Broadwell       | 1         | 2.44%   |
| Unknown         | 1         | 2.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 33        | 62.26%  |
| Nvidia | 13        | 24.53%  |
| AMD    | 7         | 13.21%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 7.55%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 7.55%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 7.55%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 5.66%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 5.66%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 3.77%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 3.77%   |
| Intel HD Graphics 630                                                                    | 2         | 3.77%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 3.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 3.77%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 3.77%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 1.89%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.89%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 1.89%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 1.89%   |
| Nvidia GK107M [GeForce GT 750M]                                                          | 1         | 1.89%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 1.89%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 1.89%   |
| Nvidia C77 [GeForce 9100M G]                                                             | 1         | 1.89%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.89%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.89%   |
| Intel HD Graphics 610                                                                    | 1         | 1.89%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.89%   |
| Intel HD Graphics 515                                                                    | 1         | 1.89%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.89%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.89%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 1         | 1.89%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 1.89%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 1         | 1.89%   |
| AMD RS780M [Mobility Radeon HD 3200]                                                     | 1         | 1.89%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 1.89%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 1.89%   |
| AMD Lucienne                                                                             | 1         | 1.89%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 1         | 1.89%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 22        | 53.66%  |
| Intel + Nvidia | 10        | 24.39%  |
| 1 x AMD        | 5         | 12.2%   |
| 1 x Nvidia     | 2         | 4.88%   |
| Intel + AMD    | 1         | 2.44%   |
| AMD + Nvidia   | 1         | 2.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 34        | 82.93%  |
| Proprietary | 7         | 17.07%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 59.52%  |
| 1.01-2.0   | 5         | 11.9%   |
| 0.01-0.5   | 5         | 11.9%   |
| 3.01-4.0   | 3         | 7.14%   |
| 0.51-1.0   | 2         | 4.76%   |
| 7.01-8.0   | 1         | 2.38%   |
| 5.01-6.0   | 1         | 2.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 10        | 23.26%  |
| AU Optronics            | 9         | 20.93%  |
| BOE                     | 7         | 16.28%  |
| Chimei Innolux          | 4         | 9.3%    |
| Sharp                   | 2         | 4.65%   |
| Samsung Electronics     | 2         | 4.65%   |
| Apple                   | 2         | 4.65%   |
| Toshiba                 | 1         | 2.33%   |
| Sony                    | 1         | 2.33%   |
| Philips                 | 1         | 2.33%   |
| PANDA                   | 1         | 2.33%   |
| Panasonic               | 1         | 2.33%   |
| Chi Mei Optoelectronics | 1         | 2.33%   |
| Acer                    | 1         | 2.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUOC199 2560x1600 344x215mm 16.0-inch           | 2         | 4.55%   |
| Toshiba LCD Monitor LCD0905 1366x768 295x166mm 13.3-inch                 | 1         | 2.27%   |
| Sony AVAMP SNYF400 1920x1080 1440x810mm 65.0-inch                        | 1         | 2.27%   |
| Sharp LQ156T1JW04 SHP153C 2560x1440 344x194mm 15.5-inch                  | 1         | 2.27%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 1         | 2.27%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 1         | 2.27%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch    | 1         | 2.27%   |
| Philips 220EW PHL0861 1680x1050 434x270mm 20.1-inch                      | 1         | 2.27%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 1         | 2.27%   |
| Panasonic TV MEIC301 1920x1080 698x392mm 31.5-inch                       | 1         | 2.27%   |
| LG Display LCD Monitor LGD049B 1920x1080 344x194mm 15.5-inch             | 1         | 2.27%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch              | 1         | 2.27%   |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch             | 1         | 2.27%   |
| LG Display LCD Monitor LGD040A 1920x1080 309x175mm 14.0-inch             | 1         | 2.27%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch              | 1         | 2.27%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 1         | 2.27%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch              | 1         | 2.27%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch              | 1         | 2.27%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 1         | 2.27%   |
| LG Display LCD Monitor LGD02CA 1366x768 345x194mm 15.6-inch              | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch         | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch          | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 1         | 2.27%   |
| Chi Mei Optoelectronics LCD Monitor CMO1557 1366x768 344x193mm 15.5-inch | 1         | 2.27%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 1         | 2.27%   |
| BOE LCD Monitor BOE0854 1920x1080 344x194mm 15.5-inch                    | 1         | 2.27%   |
| BOE LCD Monitor BOE07A1 1920x1080 344x193mm 15.5-inch                    | 1         | 2.27%   |
| BOE LCD Monitor BOE072B 1920x1080 309x173mm 13.9-inch                    | 1         | 2.27%   |
| BOE LCD Monitor BOE06FB 1920x1080 344x194mm 15.5-inch                    | 1         | 2.27%   |
| BOE LCD Monitor BOE06A6 1366x768 293x165mm 13.2-inch                     | 1         | 2.27%   |
| BOE LCD Monitor BOE0582 1366x768 344x193mm 15.5-inch                     | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO48EC 1366x768 344x193mm 15.5-inch            | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x165mm 13.2-inch            | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch            | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch           | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 1         | 2.27%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                   | 1         | 2.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 19        | 45.24%  |
| 1920x1080 (FHD)    | 15        | 35.71%  |
| 2560x1600          | 2         | 4.76%   |
| 1680x1050 (WSXGA+) | 2         | 4.76%   |
| 2560x1440 (QHD)    | 1         | 2.38%   |
| 1600x900 (HD+)     | 1         | 2.38%   |
| 1440x900 (WXGA+)   | 1         | 2.38%   |
| 1280x800 (WXGA)    | 1         | 2.38%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 22        | 51.16%  |
| 13     | 6         | 13.95%  |
| 17     | 3         | 6.98%   |
| 14     | 3         | 6.98%   |
| 22     | 2         | 4.65%   |
| 16     | 2         | 4.65%   |
| 12     | 2         | 4.65%   |
| 65     | 1         | 2.33%   |
| 31     | 1         | 2.33%   |
| 11     | 1         | 2.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 28        | 65.12%  |
| 201-300     | 7         | 16.28%  |
| 351-400     | 4         | 9.3%    |
| 401-500     | 2         | 4.65%   |
| 601-700     | 1         | 2.33%   |
| 1001-1500   | 1         | 2.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 35        | 85.37%  |
| 16/10 | 6         | 14.63%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 22        | 51.16%  |
| 81-90          | 7         | 16.28%  |
| 121-130        | 3         | 6.98%   |
| 71-80          | 2         | 4.65%   |
| 61-70          | 2         | 4.65%   |
| 201-250        | 2         | 4.65%   |
| 111-120        | 2         | 4.65%   |
| More than 1000 | 1         | 2.33%   |
| 51-60          | 1         | 2.33%   |
| 351-500        | 1         | 2.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 18        | 42.86%  |
| 101-120 | 15        | 35.71%  |
| 51-100  | 5         | 11.9%   |
| 161-240 | 3         | 7.14%   |
| 1-50    | 1         | 2.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 40        | 93.02%  |
| 2     | 2         | 4.65%   |
| 3     | 1         | 2.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 23        | 34.85%  |
| Intel                 | 16        | 24.24%  |
| Qualcomm Atheros      | 8         | 12.12%  |
| Broadcom              | 5         | 7.58%   |
| TP-Link               | 3         | 4.55%   |
| MediaTek              | 3         | 4.55%   |
| Sierra Wireless       | 2         | 3.03%   |
| Research In Motion    | 1         | 1.52%   |
| Ralink Technology     | 1         | 1.52%   |
| Ralink                | 1         | 1.52%   |
| Qualcomm              | 1         | 1.52%   |
| Motorola PCS          | 1         | 1.52%   |
| Broadcom Limited      | 1         | 1.52%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 15        | 18.52%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 4         | 4.94%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 3         | 3.7%    |
| Intel Wireless 7260                                                                           | 3         | 3.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 3         | 3.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 2         | 2.47%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 2         | 2.47%   |
| Realtek PCIe GbE Family Controller                                                            | 2         | 2.47%   |
| Intel Ethernet Connection I218-LM                                                             | 2         | 2.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2         | 2.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 2         | 2.47%   |
| Broadcom BCM43142 802.11b/g/n                                                                 | 2         | 2.47%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                        | 1         | 1.23%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 1         | 1.23%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1         | 1.23%   |
| Sierra Wireless EM7345 4G LTE                                                                 | 1         | 1.23%   |
| Sierra Wireless EM7305 Modem                                                                  | 1         | 1.23%   |
| Research In Motion BlackBerry                                                                 | 1         | 1.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.23%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.23%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                    | 1         | 1.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 1         | 1.23%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                                   | 1         | 1.23%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 1.23%   |
| Realtek Killer E3000 2.5GbE Controller                                                        | 1         | 1.23%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 1.23%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                                     | 1         | 1.23%   |
| Qualcomm Nokia XR20                                                                           | 1         | 1.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1         | 1.23%   |
| Qualcomm Atheros QCA6164 802.11ac Wireless Network Adapter                                    | 1         | 1.23%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                                     | 1         | 1.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1         | 1.23%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                                      | 1         | 1.23%   |
| Motorola PCS motorola razr 2022                                                               | 1         | 1.23%   |
| Intel Wireless 8265 / 8275                                                                    | 1         | 1.23%   |
| Intel Wireless 8260                                                                           | 1         | 1.23%   |
| Intel WiMAX Connection 2400m                                                                  | 1         | 1.23%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 1         | 1.23%   |
| Intel Wi-Fi 6 AX200                                                                           | 1         | 1.23%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                       | 1         | 1.23%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 16        | 36.36%  |
| Realtek Semiconductor | 8         | 18.18%  |
| Qualcomm Atheros      | 7         | 15.91%  |
| TP-Link               | 3         | 6.82%   |
| MediaTek              | 3         | 6.82%   |
| Broadcom              | 3         | 6.82%   |
| Sierra Wireless       | 1         | 2.27%   |
| Ralink Technology     | 1         | 2.27%   |
| Ralink                | 1         | 2.27%   |
| Broadcom Limited      | 1         | 2.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 4         | 9.09%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 3         | 6.82%   |
| Intel Wireless 7260                                                                           | 3         | 6.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 3         | 6.82%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 2         | 4.55%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2         | 4.55%   |
| Broadcom BCM43142 802.11b/g/n                                                                 | 2         | 4.55%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                        | 1         | 2.27%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 1         | 2.27%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1         | 2.27%   |
| Sierra Wireless EM7305 Modem                                                                  | 1         | 2.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 2.27%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 2.27%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                    | 1         | 2.27%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 1         | 2.27%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                                   | 1         | 2.27%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 2.27%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 2.27%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                                     | 1         | 2.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1         | 2.27%   |
| Qualcomm Atheros QCA6164 802.11ac Wireless Network Adapter                                    | 1         | 2.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1         | 2.27%   |
| Intel Wireless 8265 / 8275                                                                    | 1         | 2.27%   |
| Intel Wireless 8260                                                                           | 1         | 2.27%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 1         | 2.27%   |
| Intel Wi-Fi 6 AX200                                                                           | 1         | 2.27%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                       | 1         | 2.27%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                               | 1         | 2.27%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 1         | 2.27%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                                          | 1         | 2.27%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                                    | 1         | 2.27%   |
| Broadcom BCM4331 802.11a/b/g/n                                                                | 1         | 2.27%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 20        | 54.05%  |
| Intel                 | 8         | 21.62%  |
| Broadcom              | 3         | 8.11%   |
| Qualcomm Atheros      | 2         | 5.41%   |
| Sierra Wireless       | 1         | 2.7%    |
| Research In Motion    | 1         | 2.7%    |
| Qualcomm              | 1         | 2.7%    |
| Motorola PCS          | 1         | 2.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 15        | 40.54%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 5.41%   |
| Realtek PCIe GbE Family Controller                                | 2         | 5.41%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 5.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 5.41%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 2.7%    |
| Research In Motion BlackBerry                                     | 1         | 2.7%    |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 2.7%    |
| Qualcomm Nokia XR20                                               | 1         | 2.7%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 2.7%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 2.7%    |
| Motorola PCS motorola razr 2022                                   | 1         | 2.7%    |
| Intel WiMAX Connection 2400m                                      | 1         | 2.7%    |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller               | 1         | 2.7%    |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.7%    |
| Intel 82579V Gigabit Network Connection                           | 1         | 2.7%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 2.7%    |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 2.7%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 39        | 53.42%  |
| Ethernet | 34        | 46.58%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 33        | 78.57%  |
| Ethernet | 9         | 21.43%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 30        | 73.17%  |
| 1     | 9         | 21.95%  |
| 0     | 2         | 4.88%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 34        | 80.95%  |
| Yes  | 8         | 19.05%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 35.48%  |
| IMC Networks                    | 4         | 12.9%   |
| Realtek Semiconductor           | 3         | 9.68%   |
| Cambridge Silicon Radio         | 3         | 9.68%   |
| Realtek                         | 2         | 6.45%   |
| Broadcom                        | 2         | 6.45%   |
| Apple                           | 2         | 6.45%   |
| Qualcomm Atheros Communications | 1         | 3.23%   |
| Lite-On Technology              | 1         | 3.23%   |
| Hewlett-Packard                 | 1         | 3.23%   |
| Foxconn / Hon Hai               | 1         | 3.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 6         | 19.35%  |
| IMC Networks Wireless_Device                        | 3         | 9.68%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 9.68%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 6.45%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 3.23%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 3.23%   |
| Realtek Bluetooth Radio                             | 1         | 3.23%   |
| Realtek Bluetooth Radio                             | 1         | 3.23%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 3.23%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 3.23%   |
| Lite-On Bluetooth Device                            | 1         | 3.23%   |
| Intel AX210 Bluetooth                               | 1         | 3.23%   |
| Intel AX201 Bluetooth                               | 1         | 3.23%   |
| Intel AX200 Bluetooth                               | 1         | 3.23%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 3.23%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 3.23%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 3.23%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 3.23%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 3.23%   |
| Apple Bluetooth USB Host Controller                 | 1         | 3.23%   |
| Apple Bluetooth Host Controller                     | 1         | 3.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor            | Notebooks | Percent |
|-------------------|-----------|---------|
| Intel             | 33        | 67.35%  |
| Nvidia            | 8         | 16.33%  |
| AMD               | 6         | 12.24%  |
| Texas Instruments | 1         | 2.04%   |
| Logitech          | 1         | 2.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 8.06%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 8.06%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 6.45%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 6.45%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 4.84%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 4.84%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 4.84%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 3.23%   |
| Nvidia Audio device                                                                               | 2         | 3.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 3.23%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 3.23%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 3.23%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 3.23%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 3.23%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 3.23%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 1.61%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.61%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1         | 1.61%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 1.61%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 1.61%   |
| Logitech Headset H390                                                                             | 1         | 1.61%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 1.61%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.61%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.61%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.61%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 1.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.61%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 1.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 1.61%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 1.61%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                                            | 1         | 1.61%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.61%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.61%   |
| AMD FCH Azalia Controller                                                                         | 1         | 1.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Micron Technology   | 5         | 29.41%  |
| Samsung Electronics | 3         | 17.65%  |
| Crucial             | 3         | 17.65%  |
| SK hynix            | 2         | 11.76%  |
| Kingston            | 2         | 11.76%  |
| Unknown             | 1         | 5.88%   |
| A-DATA Technology   | 1         | 5.88%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 2         | 10.53%  |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s       | 2         | 10.53%  |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s       | 2         | 10.53%  |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                | 1         | 5.26%   |
| Samsung RAM Module 2048MB SODIMM LPDDR3 1867MT/s           | 1         | 5.26%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s      | 1         | 5.26%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s      | 1         | 5.26%   |
| Micron RAM Module 2048MB Row Of Chips DDR3 1600MT/s        | 1         | 5.26%   |
| Micron RAM 8JTF5126 4HZ1G6D 1 4GB SODIMM DDR3 1600MT/s     | 1         | 5.26%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8192MB SODIMM DDR3 1600MT/s   | 1         | 5.26%   |
| Kingston RAM MSI24D4S7D8MH-16 16384MB SODIMM DDR4 2400MT/s | 1         | 5.26%   |
| Kingston RAM ASU16D3LS1KBG/4G 4GB SODIMM DDR3 1600MT/s     | 1         | 5.26%   |
| Crucial RAM Module 4096MB SODIMM DDR3 1600MT/s             | 1         | 5.26%   |
| Crucial RAM CT51264BF160BJ.C8F 4GB SODIMM DDR3 1600MT/s    | 1         | 5.26%   |
| Crucial RAM CT16G4SFD824A.C16FP 16GB SODIMM DDR4 2400MT/s  | 1         | 5.26%   |
| A-DATA RAM AM1U16BC4P2-B19H 4GB SODIMM DDR3 1600MT/s       | 1         | 5.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 7         | 50%     |
| DDR4   | 6         | 42.86%  |
| LPDDR3 | 1         | 7.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 13        | 92.86%  |
| Row Of Chips | 1         | 7.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 6         | 40%     |
| 8192  | 5         | 33.33%  |
| 16384 | 2         | 13.33%  |
| 2048  | 2         | 13.33%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 7         | 50%     |
| 3200  | 3         | 21.43%  |
| 2400  | 2         | 14.29%  |
| 2667  | 1         | 7.14%   |
| 1867  | 1         | 7.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| HP Laser 107w | 1         | 100%    |

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
| Chicony Electronics                    | 9         | 24.32%  |
| IMC Networks                           | 8         | 21.62%  |
| Realtek Semiconductor                  | 4         | 10.81%  |
| Bison Electronics                      | 3         | 8.11%   |
| Sunplus Innovation Technology          | 2         | 5.41%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 5.41%   |
| Acer                                   | 2         | 5.41%   |
| Samsung Electronics                    | 1         | 2.7%    |
| Pixart Imaging                         | 1         | 2.7%    |
| Microdia                               | 1         | 2.7%    |
| Lite-On Technology                     | 1         | 2.7%    |
| GEMBIRD                                | 1         | 2.7%    |
| Apple                                  | 1         | 2.7%    |
| Alcor Micro                            | 1         | 2.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                       | 4         | 10.81%  |
| IMC Networks USB2.0 VGA UVC WebCam                      | 2         | 5.41%   |
| Bison Lenovo EasyCamera                                 | 2         | 5.41%   |
| Sunplus HP HD Webcam [Fixed]                            | 1         | 2.7%    |
| Sunplus Asus Webcam                                     | 1         | 2.7%    |
| Samsung Galaxy series, misc. (MTP mode)                 | 1         | 2.7%    |
| Realtek USB Camera                                      | 1         | 2.7%    |
| Realtek Integrated_Webcam_HD                            | 1         | 2.7%    |
| Realtek HP Wide Vision HD Camera                        | 1         | 2.7%    |
| Realtek HD WebCam                                       | 1         | 2.7%    |
| Pixart Imaging GE 1.3 MP MiniCam Pro                    | 1         | 2.7%    |
| Microdia Integrated Webcam                              | 1         | 2.7%    |
| Lite-On Integrated Camera                               | 1         | 2.7%    |
| IMC Networks USB2.0 UVC HD Webcam                       | 1         | 2.7%    |
| IMC Networks ov9734_azurewave_camera                    | 1         | 2.7%    |
| GEMBIRD USB2.0 PC CAMERA                                | 1         | 2.7%    |
| Chicony WebCam                                          | 1         | 2.7%    |
| Chicony USB2.0 HD UVC WebCam                            | 1         | 2.7%    |
| Chicony USB 2.0 Camera                                  | 1         | 2.7%    |
| Chicony Sony Visual Communication Camera                | 1         | 2.7%    |
| Chicony Integrated Camera (1280x720@30)                 | 1         | 2.7%    |
| Chicony Integrated Camera                               | 1         | 2.7%    |
| Chicony HP Wide Vision HD Camera                        | 1         | 2.7%    |
| Chicony HD WebCam                                       | 1         | 2.7%    |
| Chicony FJ Camera                                       | 1         | 2.7%    |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 1         | 2.7%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam     | 1         | 2.7%    |
| Bison HD Camera                                         | 1         | 2.7%    |
| Apple FaceTime HD Camera                                | 1         | 2.7%    |
| Alcor Micro SHUNCCM2MP                                  | 1         | 2.7%    |
| Acer Lenovo EasyCamera                                  | 1         | 2.7%    |
| Acer Integrated Camera                                  | 1         | 2.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 80%     |
| Shenzhen Goodix Technology | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader | 1         | 20%     |
| Validity Sensors VFS471 Fingerprint Reader | 1         | 20%     |
| Validity Sensors VFS Fingerprint sensor    | 1         | 20%     |
| Validity Sensors Swipe Fingerprint Sensor  | 1         | 20%     |
| Shenzhen Goodix  Fingerprint Device        | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| OmniKey  | 1         | 50%     |
| Broadcom | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| OmniKey CardMan 4321 | 1         | 50%     |
| Broadcom 5880        | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 26        | 60.47%  |
| 1     | 16        | 37.21%  |
| 2     | 1         | 2.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 5         | 29.41%  |
| Graphics card         | 4         | 23.53%  |
| Net/wireless          | 3         | 17.65%  |
| Multimedia controller | 2         | 11.76%  |
| Chipcard              | 2         | 11.76%  |
| Net/ethernet          | 1         | 5.88%   |

