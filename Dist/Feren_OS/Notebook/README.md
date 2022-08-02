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

Total: 56

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek   | VivoBook_ASUSLaptop M350... | [b2b969b0e3](https://linux-hardware.org/?probe=b2b969b0e3) | Aug 01, 2022 |
| HP        | Pavilion Laptop 14-bf0xx    | [54c42c649d](https://linux-hardware.org/?probe=54c42c649d) | Jul 24, 2022 |
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
| Feren OS 20.04 | 20        | 54.05%  |
| Feren OS 18.04 | 17        | 45.95%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Feren OS | 36        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.11.0-37-generic       | 4         | 8.89%   |
| 5.8.0-55-generic        | 3         | 6.67%   |
| 5.3.0-51-generic        | 3         | 6.67%   |
| 5.8.0-50-generic        | 2         | 4.44%   |
| 5.4.0-52-generic        | 2         | 4.44%   |
| 5.4.0-42-generic        | 2         | 4.44%   |
| 5.3.0-53-generic        | 2         | 4.44%   |
| 5.0.0-37-generic        | 2         | 4.44%   |
| 5.8.0-53-generic        | 1         | 2.22%   |
| 5.8.0-48-generic        | 1         | 2.22%   |
| 5.8.0-36-generic        | 1         | 2.22%   |
| 5.4.0-58-generic        | 1         | 2.22%   |
| 5.4.0-54-generic        | 1         | 2.22%   |
| 5.4.0-51-generic        | 1         | 2.22%   |
| 5.4.0-48-generic        | 1         | 2.22%   |
| 5.4.0-47-generic        | 1         | 2.22%   |
| 5.4.0-45-generic        | 1         | 2.22%   |
| 5.3.0-59-generic        | 1         | 2.22%   |
| 5.3.0-42-generic        | 1         | 2.22%   |
| 5.17.5-76051705-generic | 1         | 2.22%   |
| 5.15.6-051506-generic   | 1         | 2.22%   |
| 5.15.0-41-generic       | 1         | 2.22%   |
| 5.13.0-40-generic       | 1         | 2.22%   |
| 5.13.0-30-generic       | 1         | 2.22%   |
| 5.13.0-22-generic       | 1         | 2.22%   |
| 5.13.0-21-generic       | 1         | 2.22%   |
| 5.11.0-40-generic       | 1         | 2.22%   |
| 5.11.0-16-generic       | 1         | 2.22%   |
| 5.0.0-29-generic        | 1         | 2.22%   |
| 5.0.0-25-generic        | 1         | 2.22%   |
| 4.15.0-58-generic       | 1         | 2.22%   |
| 4.15.0-48-generic       | 1         | 2.22%   |
| 4.15.0-47-generic       | 1         | 2.22%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 9         | 23.08%  |
| 5.8.0   | 7         | 17.95%  |
| 5.3.0   | 6         | 15.38%  |
| 5.11.0  | 6         | 15.38%  |
| 5.13.0  | 3         | 7.69%   |
| 5.0.0   | 3         | 7.69%   |
| 4.15.0  | 2         | 5.13%   |
| 5.17.5  | 1         | 2.56%   |
| 5.15.6  | 1         | 2.56%   |
| 5.15.0  | 1         | 2.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 9         | 23.08%  |
| 5.8     | 7         | 17.95%  |
| 5.3     | 6         | 15.38%  |
| 5.11    | 6         | 15.38%  |
| 5.13    | 3         | 7.69%   |
| 5.0     | 3         | 7.69%   |
| 5.15    | 2         | 5.13%   |
| 4.15    | 2         | 5.13%   |
| 5.17    | 1         | 2.56%   |

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


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KDE        | 20        | 52.63%  |
| KDE5       | 12        | 31.58%  |
| Unknown    | 4         | 10.53%  |
| X-Cinnamon | 1         | 2.63%   |
| GNOME      | 1         | 2.63%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 36        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 28        | 77.78%  |
| LightDM | 7         | 19.44%  |
| TDM     | 1         | 2.78%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 11        | 29.73%  |
| en_GB   | 7         | 18.92%  |
| en_IN   | 3         | 8.11%   |
| de_CH   | 3         | 8.11%   |
| Unknown | 3         | 8.11%   |
| de_DE   | 2         | 5.41%   |
| nl_BE   | 1         | 2.7%    |
| fi_FI   | 1         | 2.7%    |
| es_VE   | 1         | 2.7%    |
| es_UY   | 1         | 2.7%    |
| es_ES   | 1         | 2.7%    |
| es_CL   | 1         | 2.7%    |
| en_CA   | 1         | 2.7%    |
| de_AT   | 1         | 2.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 22        | 61.11%  |
| BIOS | 14        | 38.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 33        | 89.19%  |
| Unknown | 2         | 5.41%   |
| Overlay | 1         | 2.7%    |
| Btrfs   | 1         | 2.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 31        | 86.11%  |
| GPT     | 5         | 13.89%  |

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
| No        | 29        | 80.56%  |
| Yes       | 7         | 19.44%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| ASUSTek Computer | 8         | 22.22%  |
| Lenovo           | 6         | 16.67%  |
| MSI              | 4         | 11.11%  |
| Hewlett-Packard  | 4         | 11.11%  |
| Dell             | 3         | 8.33%   |
| Sony             | 2         | 5.56%   |
| Acer             | 2         | 5.56%   |
| Toshiba          | 1         | 2.78%   |
| Panasonic        | 1         | 2.78%   |
| HUAWEI           | 1         | 2.78%   |
| Fujitsu          | 1         | 2.78%   |
| Exo              | 1         | 2.78%   |
| Apple            | 1         | 2.78%   |
| Unknown          | 1         | 2.78%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| ASUS ROG Zephyrus M16 GU603HE_GU603HE    | 2         | 5.56%   |
| Toshiba Satellite T135D                  | 1         | 2.78%   |
| Sony VPCEE4J1E                           | 1         | 2.78%   |
| Sony SVF15318SNB                         | 1         | 2.78%   |
| Panasonic CF-J10YYBHR                    | 1         | 2.78%   |
| MSI Traveller 1591                       | 1         | 2.78%   |
| MSI GS66 Stealth 10SE                    | 1         | 2.78%   |
| MSI GP72 7RDX                            | 1         | 2.78%   |
| MSI GE66 Raider 11UG                     | 1         | 2.78%   |
| Lenovo XiaoXin Air 12 80UN               | 1         | 2.78%   |
| Lenovo ThinkPad X240 20AMS72901          | 1         | 2.78%   |
| Lenovo ThinkPad X230 2325AT6             | 1         | 2.78%   |
| Lenovo Legion Y7000P 81LD                | 1         | 2.78%   |
| Lenovo G550 2958                         | 1         | 2.78%   |
| Lenovo G50-45 80E3                       | 1         | 2.78%   |
| HUAWEI BOHK-WAX9X                        | 1         | 2.78%   |
| HP ProBook 6560b                         | 1         | 2.78%   |
| HP Pavilion Laptop 14-bf0xx              | 1         | 2.78%   |
| HP Pavilion Gaming Laptop 15-cx0xxx      | 1         | 2.78%   |
| HP EliteBook Folio 1040 G1               | 1         | 2.78%   |
| Fujitsu LIFEBOOK E554                    | 1         | 2.78%   |
| Exo CloudbookE15                         | 1         | 2.78%   |
| Dell Latitude E5570                      | 1         | 2.78%   |
| Dell Latitude E5430 vPro                 | 1         | 2.78%   |
| Dell Inspiron 3421                       | 1         | 2.78%   |
| ASUS X550CA                              | 1         | 2.78%   |
| ASUS X541NA                              | 1         | 2.78%   |
| ASUS VivoBook_ASUSLaptop M3500QC_M3500QC | 1         | 2.78%   |
| ASUS VivoBook_ASUS Laptop E210MA_E210MA  | 1         | 2.78%   |
| ASUS S400CA                              | 1         | 2.78%   |
| ASUS P552LJ                              | 1         | 2.78%   |
| Apple MacBookPro8,1                      | 1         | 2.78%   |
| Acer NG-VX5-591G-52AT                    | 1         | 2.78%   |
| Acer Aspire 5733Z                        | 1         | 2.78%   |
| Unknown                                  | 1         | 2.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 2         | 5.56%   |
| HP Pavilion           | 2         | 5.56%   |
| Dell Latitude         | 2         | 5.56%   |
| ASUS VivoBook         | 2         | 5.56%   |
| ASUS ROG              | 2         | 5.56%   |
| Toshiba Satellite     | 1         | 2.78%   |
| Sony VPCEE4J1E        | 1         | 2.78%   |
| Sony SVF15318SNB      | 1         | 2.78%   |
| Panasonic CF-J10YYBHR | 1         | 2.78%   |
| MSI Traveller         | 1         | 2.78%   |
| MSI GS66              | 1         | 2.78%   |
| MSI GP72              | 1         | 2.78%   |
| MSI GE66              | 1         | 2.78%   |
| Lenovo XiaoXin        | 1         | 2.78%   |
| Lenovo Legion         | 1         | 2.78%   |
| Lenovo G550           | 1         | 2.78%   |
| Lenovo G50-45         | 1         | 2.78%   |
| HUAWEI BOHK-WAX9X     | 1         | 2.78%   |
| HP ProBook            | 1         | 2.78%   |
| HP EliteBook          | 1         | 2.78%   |
| Fujitsu LIFEBOOK      | 1         | 2.78%   |
| Exo CloudbookE15      | 1         | 2.78%   |
| Dell Inspiron         | 1         | 2.78%   |
| ASUS X550CA           | 1         | 2.78%   |
| ASUS X541NA           | 1         | 2.78%   |
| ASUS S400CA           | 1         | 2.78%   |
| ASUS P552LJ           | 1         | 2.78%   |
| Apple MacBookPro8     | 1         | 2.78%   |
| Acer NG-VX5-591G-52AT | 1         | 2.78%   |
| Acer Aspire           | 1         | 2.78%   |
| Unknown               | 1         | 2.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 5         | 13.89%  |
| 2021 | 4         | 11.11%  |
| 2017 | 4         | 11.11%  |
| 2011 | 4         | 11.11%  |
| 2020 | 3         | 8.33%   |
| 2019 | 3         | 8.33%   |
| 2016 | 3         | 8.33%   |
| 2013 | 3         | 8.33%   |
| 2018 | 2         | 5.56%   |
| 2014 | 2         | 5.56%   |
| 2009 | 2         | 5.56%   |
| 2008 | 1         | 2.78%   |

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
| Disabled | 32        | 86.49%  |
| Enabled  | 5         | 13.51%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 36        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 10        | 26.32%  |
| 3.01-4.0    | 9         | 23.68%  |
| 16.01-24.0  | 8         | 21.05%  |
| 8.01-16.0   | 8         | 21.05%  |
| 32.01-64.0  | 1         | 2.63%   |
| 64.01-256.0 | 1         | 2.63%   |
| 1.01-2.0    | 1         | 2.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 18        | 43.9%   |
| 2.01-3.0 | 12        | 29.27%  |
| 3.01-4.0 | 6         | 14.63%  |
| 4.01-8.0 | 4         | 9.76%   |
| 0.51-1.0 | 1         | 2.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 27        | 72.97%  |
| 2      | 9         | 24.32%  |
| 3      | 1         | 2.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 24        | 66.67%  |
| Yes       | 12        | 33.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 86.11%  |
| No        | 5         | 13.89%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 35        | 97.22%  |
| No        | 1         | 2.78%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 27        | 72.97%  |
| No        | 10        | 27.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 7         | 19.44%  |
| UK          | 3         | 8.33%   |
| Switzerland | 3         | 8.33%   |
| India       | 3         | 8.33%   |
| Germany     | 3         | 8.33%   |
| Turkey      | 2         | 5.56%   |
| Poland      | 2         | 5.56%   |
| Venezuela   | 1         | 2.78%   |
| Uruguay     | 1         | 2.78%   |
| UAE         | 1         | 2.78%   |
| Spain       | 1         | 2.78%   |
| Japan       | 1         | 2.78%   |
| Greece      | 1         | 2.78%   |
| Finland     | 1         | 2.78%   |
| Chile       | 1         | 2.78%   |
| Canada      | 1         | 2.78%   |
| Bulgaria    | 1         | 2.78%   |
| Belgium     | 1         | 2.78%   |
| Australia   | 1         | 2.78%   |
| Argentina   | 1         | 2.78%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Oberwil-Lieli      | 3         | 7.69%   |
| Istanbul           | 2         | 5.13%   |
| Escondido          | 2         | 5.13%   |
| Ypsilanti          | 1         | 2.56%   |
| Winterthur         | 1         | 2.56%   |
| Varna              | 1         | 2.56%   |
| Surat              | 1         | 2.56%   |
| Stuttgart          | 1         | 2.56%   |
| Santiago           | 1         | 2.56%   |
| Saitama            | 1         | 2.56%   |
| Plymouth           | 1         | 2.56%   |
| Phoenix            | 1         | 2.56%   |
| Montevideo         | 1         | 2.56%   |
| Moncton            | 1         | 2.56%   |
| Mieres             | 1         | 2.56%   |
| Maracay            | 1         | 2.56%   |
| Leicester          | 1         | 2.56%   |
| Lafayette          | 1         | 2.56%   |
| Krakow             | 1         | 2.56%   |
| Kloten             | 1         | 2.56%   |
| Karlsruhe          | 1         | 2.56%   |
| Hyderabad          | 1         | 2.56%   |
| Hickory            | 1         | 2.56%   |
| Hämeenlinna       | 1         | 2.56%   |
| Gdynia             | 1         | 2.56%   |
| Gdansk             | 1         | 2.56%   |
| Ernakulam          | 1         | 2.56%   |
| Delmenhorst        | 1         | 2.56%   |
| Corpus Christi     | 1         | 2.56%   |
| Brisbane           | 1         | 2.56%   |
| Banda del Rio Sali | 1         | 2.56%   |
| Ballymena          | 1         | 2.56%   |
| Athens             | 1         | 2.56%   |
| Al Ain City        | 1         | 2.56%   |
| Aartselaar         | 1         | 2.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Samsung Electronics   | 7         | 8      | 14.89%  |
| SanDisk               | 5         | 5      | 10.64%  |
| Unknown               | 4         | 5      | 8.51%   |
| Intel                 | 4         | 5      | 8.51%   |
| HGST                  | 4         | 4      | 8.51%   |
| Hitachi               | 3         | 3      | 6.38%   |
| Toshiba               | 2         | 4      | 4.26%   |
| SK hynix              | 2         | 3      | 4.26%   |
| Seagate               | 2         | 2      | 4.26%   |
| Phison                | 2         | 2      | 4.26%   |
| OCZ                   | 2         | 2      | 4.26%   |
| Kingston              | 2         | 2      | 4.26%   |
| A-DATA Technology     | 2         | 2      | 4.26%   |
| WDC                   | 1         | 1      | 2.13%   |
| Realtek Semiconductor | 1         | 1      | 2.13%   |
| PNY                   | 1         | 1      | 2.13%   |
| LITEON                | 1         | 1      | 2.13%   |
| Crucial               | 1         | 4      | 2.13%   |
| China                 | 1         | 1      | 2.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Seagate ST500LT012-9WS142 500GB       | 2         | 4.17%   |
| Phison NVMe SSD Drive 1TB             | 2         | 4.17%   |
| Intel NVMe SSD Drive 512GB            | 2         | 4.17%   |
| HGST HTS721010A9E630 1TB              | 2         | 4.17%   |
| WDC WD2500BPVT-00JJ5T0 250GB          | 1         | 2.08%   |
| Unknown SB128  128GB                  | 1         | 2.08%   |
| Unknown SA04G  4GB                    | 1         | 2.08%   |
| Unknown MMC Card  32GB                | 1         | 2.08%   |
| Unknown MMC Card  128GB               | 1         | 2.08%   |
| Toshiba THNSNC128GNSJ 128GB SSD       | 1         | 2.08%   |
| Toshiba MQ01ABD100 1TB                | 1         | 2.08%   |
| SK hynix HFS128G32TND-N210A 128GB SSD | 1         | 2.08%   |
| SK hynix HFM001TD3JX013N 1TB          | 1         | 2.08%   |
| SanDisk SSD U100 24GB                 | 1         | 2.08%   |
| SanDisk SD9SB8W256G1002 256GB SSD     | 1         | 2.08%   |
| SanDisk SD8SN8U-128G-1006 128GB SSD   | 1         | 2.08%   |
| SanDisk SD6SN1M-256G-1006 256GB SSD   | 1         | 2.08%   |
| SanDisk NVMe SSD Drive 256GB          | 1         | 2.08%   |
| Samsung SSD 860 EVO 250GB             | 1         | 2.08%   |
| Samsung NVMe SSD Drive 256GB          | 1         | 2.08%   |
| Samsung NVMe SSD Drive 1TB            | 1         | 2.08%   |
| Samsung NVMe SSD Drive 1024GB         | 1         | 2.08%   |
| Samsung MZVLW256HEHP-000H1 256GB      | 1         | 2.08%   |
| Samsung MZVLW128HEGR-00000 128GB      | 1         | 2.08%   |
| Samsung MZNTY128HDHP-000L2 128GB SSD  | 1         | 2.08%   |
| Realtek NVMe SSD Drive 512GB          | 1         | 2.08%   |
| PNY CS900 500GB SSD                   | 1         | 2.08%   |
| OCZ VERTEX2 90GB SSD                  | 1         | 2.08%   |
| OCZ AGILITY3 120GB SSD                | 1         | 2.08%   |
| LITEON IT LCS-128L9S-HP 128GB SSD     | 1         | 2.08%   |
| Kingston SV300S37A120G 120GB SSD      | 1         | 2.08%   |
| Kingston SA400S37240G 240GB SSD       | 1         | 2.08%   |
| Intel SSDSC2BF240A4L 240GB            | 1         | 2.08%   |
| Intel NVMe SSD Drive 256GB            | 1         | 2.08%   |
| Hitachi HTS723232A7A364 320GB         | 1         | 2.08%   |
| Hitachi HTS547550A9E384 500GB         | 1         | 2.08%   |
| Hitachi HDS721050CLA362 500GB         | 1         | 2.08%   |
| HGST HTS541010A9E680 1TB              | 1         | 2.08%   |
| HGST HTS541010A7E630 1TB              | 1         | 2.08%   |
| Crucial CT250MX500SSD1 250GB          | 1         | 2.08%   |
| Crucial CT120M500SSD1 120GB           | 1         | 2.08%   |
| China SSD 256GB                       | 1         | 2.08%   |
| A-DATA SU800 512GB SSD                | 1         | 2.08%   |
| A-DATA SU630 240GB SSD                | 1         | 2.08%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HGST    | 4         | 4      | 36.36%  |
| Hitachi | 3         | 3      | 27.27%  |
| Seagate | 2         | 2      | 18.18%  |
| WDC     | 1         | 1      | 9.09%   |
| Toshiba | 1         | 2      | 9.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 4         | 4      | 21.05%  |
| Samsung Electronics | 2         | 3      | 10.53%  |
| OCZ                 | 2         | 2      | 10.53%  |
| Kingston            | 2         | 2      | 10.53%  |
| A-DATA Technology   | 2         | 2      | 10.53%  |
| Toshiba             | 1         | 2      | 5.26%   |
| SK hynix            | 1         | 2      | 5.26%   |
| PNY                 | 1         | 1      | 5.26%   |
| LITEON              | 1         | 1      | 5.26%   |
| Intel               | 1         | 1      | 5.26%   |
| Crucial             | 1         | 4      | 5.26%   |
| China               | 1         | 1      | 5.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 17        | 25     | 39.53%  |
| NVMe | 11        | 14     | 25.58%  |
| HDD  | 11        | 12     | 25.58%  |
| MMC  | 4         | 5      | 9.3%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 25        | 36     | 60.98%  |
| NVMe | 11        | 14     | 26.83%  |
| MMC  | 4         | 5      | 9.76%   |
| SAS  | 1         | 1      | 2.44%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 21        | 30     | 77.78%  |
| 0.51-1.0   | 6         | 7      | 22.22%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 14        | 35.9%   |
| 251-500    | 10        | 25.64%  |
| 501-1000   | 6         | 15.38%  |
| 51-100     | 4         | 10.26%  |
| 21-50      | 2         | 5.13%   |
| 1001-2000  | 2         | 5.13%   |
| 1-20       | 1         | 2.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 21-50    | 16        | 41.03%  |
| 1-20     | 7         | 17.95%  |
| 51-100   | 7         | 17.95%  |
| 101-250  | 5         | 12.82%  |
| 251-500  | 3         | 7.69%   |
| 501-1000 | 1         | 2.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1         | 1      | 100%    |

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
| Detected | 32        | 47     | 84.21%  |
| Works    | 5         | 8      | 13.16%  |
| Malfunc  | 1         | 1      | 2.63%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 27        | 64.29%  |
| Samsung Electronics   | 5         | 11.9%   |
| AMD                   | 4         | 9.52%   |
| Phison Electronics    | 2         | 4.76%   |
| SK hynix              | 1         | 2.38%   |
| SanDisk               | 1         | 2.38%   |
| Realtek Semiconductor | 1         | 2.38%   |
| Nvidia                | 1         | 2.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 8.7%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 6.52%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 6.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 3         | 6.52%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 4.35%   |
| Phison E12 NVMe Controller                                                     | 2         | 4.35%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 4.35%   |
| Intel Non-Volatile memory controller                                           | 2         | 4.35%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 4.35%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 4.35%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 4.35%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 4.35%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 2         | 4.35%   |
| SK hynix Gold P31 SSD                                                          | 1         | 2.17%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 2.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 2.17%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 2.17%   |
| Samsung NVMe SSD Controller 980                                                | 1         | 2.17%   |
| Realtek Realtek Non-Volatile memory controller                                 | 1         | 2.17%   |
| Nvidia nForce SATA Controller                                                  | 1         | 2.17%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 2.17%   |
| Intel SSD 600P Series                                                          | 1         | 2.17%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 2.17%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 2.17%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 2.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 2.17%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 2.17%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 1         | 2.17%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 28        | 63.64%  |
| NVMe | 11        | 25%     |
| RAID | 4         | 9.09%   |
| IDE  | 1         | 2.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 30        | 83.33%  |
| AMD    | 6         | 16.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 8.33%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 2         | 5.56%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 5.56%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 2.78%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 2.78%   |
| Intel Pentium CPU 4415U @ 2.30GHz             | 1         | 2.78%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz              | 1         | 2.78%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 2.78%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 2.78%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 2.78%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 2.78%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 2.78%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 2.78%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 2.78%   |
| Intel Core i5-4210M CPU @ 2.60GHz             | 1         | 2.78%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 2.78%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 2.78%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 2.78%   |
| Intel Core i5-2435M CPU @ 2.40GHz             | 1         | 2.78%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 2.78%   |
| Intel Core i3-2375M CPU @ 1.50GHz             | 1         | 2.78%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 2.78%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1         | 2.78%   |
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz   | 1         | 2.78%   |
| Intel Celeron CPU 1007U @ 1.50GHz             | 1         | 2.78%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 1         | 2.78%   |
| AMD Turion Neo X2 Dual Core Processor L625    | 1         | 2.78%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 1         | 2.78%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 2.78%   |
| AMD Athlon X2 Dual-Core QL-60                 | 1         | 2.78%   |
| AMD Athlon II P360 Dual-Core Processor        | 1         | 2.78%   |
| AMD A6-6310 APU with AMD Radeon R4 Graphics   | 1         | 2.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 12        | 33.33%  |
| Intel Core i7           | 4         | 11.11%  |
| Other                   | 3         | 8.33%   |
| Intel Pentium           | 3         | 8.33%   |
| Intel Celeron           | 3         | 8.33%   |
| Intel Core i3           | 2         | 5.56%   |
| Intel Core m3           | 1         | 2.78%   |
| Intel Celeron Dual-Core | 1         | 2.78%   |
| Intel Atom              | 1         | 2.78%   |
| AMD Turion Neo X2       | 1         | 2.78%   |
| AMD Ryzen 9             | 1         | 2.78%   |
| AMD Ryzen 5             | 1         | 2.78%   |
| AMD Athlon X2           | 1         | 2.78%   |
| AMD Athlon II           | 1         | 2.78%   |
| AMD A6                  | 1         | 2.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 22        | 61.11%  |
| 4      | 9         | 25%     |
| 8      | 5         | 13.89%  |

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
| 2      | 24        | 66.67%  |
| 1      | 12        | 33.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 34        | 94.44%  |
| Unknown        | 2         | 5.56%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 4         | 11.11%  |
| 0x806d1    | 3         | 8.33%   |
| 0x40651    | 3         | 8.33%   |
| 0x306a9    | 3         | 8.33%   |
| 0x906e9    | 2         | 5.56%   |
| 0x706a8    | 2         | 5.56%   |
| 0x406e3    | 2         | 5.56%   |
| Unknown    | 2         | 5.56%   |
| 0xa0652    | 1         | 2.78%   |
| 0x906ea    | 1         | 2.78%   |
| 0x806ea    | 1         | 2.78%   |
| 0x806e9    | 1         | 2.78%   |
| 0x506c9    | 1         | 2.78%   |
| 0x406c4    | 1         | 2.78%   |
| 0x306d4    | 1         | 2.78%   |
| 0x306c3    | 1         | 2.78%   |
| 0x20655    | 1         | 2.78%   |
| 0x1067a    | 1         | 2.78%   |
| 0x0a50000c | 1         | 2.78%   |
| 0x08108109 | 1         | 2.78%   |
| 0x07030105 | 1         | 2.78%   |
| 0x02000032 | 1         | 2.78%   |
| 0x010000c8 | 1         | 2.78%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 5         | 13.89%  |
| SandyBridge     | 4         | 11.11%  |
| IvyBridge       | 4         | 11.11%  |
| Haswell         | 4         | 11.11%  |
| Icelake         | 3         | 8.33%   |
| Skylake         | 2         | 5.56%   |
| Goldmont plus   | 2         | 5.56%   |
| Zen+            | 1         | 2.78%   |
| Zen 3           | 1         | 2.78%   |
| Westmere        | 1         | 2.78%   |
| Silvermont      | 1         | 2.78%   |
| Puma            | 1         | 2.78%   |
| Penryn          | 1         | 2.78%   |
| K8 Hammer       | 1         | 2.78%   |
| K8 & K10 hybrid | 1         | 2.78%   |
| K10             | 1         | 2.78%   |
| Goldmont        | 1         | 2.78%   |
| CometLake       | 1         | 2.78%   |
| Broadwell       | 1         | 2.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 29        | 61.7%   |
| Nvidia | 12        | 25.53%  |
| AMD    | 6         | 12.77%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 8.51%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 8.51%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 6.38%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 6.38%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 6.38%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 4.26%   |
| Intel HD Graphics 630                                                                    | 2         | 4.26%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 4.26%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 2.13%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 2.13%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 2.13%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 2.13%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 2.13%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 2.13%   |
| Nvidia C77 [GeForce 9100M G]                                                             | 1         | 2.13%   |
| Intel UHD Graphics 620                                                                   | 1         | 2.13%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 2.13%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 2.13%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 1         | 2.13%   |
| Intel HD Graphics 5500                                                                   | 1         | 2.13%   |
| Intel HD Graphics 515                                                                    | 1         | 2.13%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 2.13%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 2.13%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 1         | 2.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.13%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 2.13%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 2.13%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 1         | 2.13%   |
| AMD RS780M [Mobility Radeon HD 3200]                                                     | 1         | 2.13%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 2.13%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 2.13%   |
| AMD Cezanne                                                                              | 1         | 2.13%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 19        | 52.78%  |
| Intel + Nvidia | 9         | 25%     |
| 1 x AMD        | 4         | 11.11%  |
| 1 x Nvidia     | 2         | 5.56%   |
| Intel + AMD    | 1         | 2.78%   |
| AMD + Nvidia   | 1         | 2.78%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 30        | 83.33%  |
| Proprietary | 6         | 16.67%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 59.46%  |
| 1.01-2.0   | 4         | 10.81%  |
| 0.01-0.5   | 4         | 10.81%  |
| 3.01-4.0   | 3         | 8.11%   |
| 0.51-1.0   | 2         | 5.41%   |
| 7.01-8.0   | 1         | 2.7%    |
| 5.01-6.0   | 1         | 2.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 10        | 26.32%  |
| BOE                     | 7         | 18.42%  |
| AU Optronics            | 7         | 18.42%  |
| Chimei Innolux          | 3         | 7.89%   |
| Sharp                   | 2         | 5.26%   |
| Samsung Electronics     | 2         | 5.26%   |
| Toshiba                 | 1         | 2.63%   |
| Sony                    | 1         | 2.63%   |
| Philips                 | 1         | 2.63%   |
| Panasonic               | 1         | 2.63%   |
| Chi Mei Optoelectronics | 1         | 2.63%   |
| Apple                   | 1         | 2.63%   |
| Acer                    | 1         | 2.63%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUOC199 2560x1600 344x215mm 16.0-inch           | 2         | 5.13%   |
| Toshiba LCD Monitor LCD0905 1366x768 295x166mm 13.3-inch                 | 1         | 2.56%   |
| Sony AVAMP SNYF400 1920x1080 700x390mm 31.5-inch                         | 1         | 2.56%   |
| Sharp LQ156T1JW04 SHP153C 2560x1440 344x194mm 15.5-inch                  | 1         | 2.56%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 1         | 2.56%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 1         | 2.56%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch    | 1         | 2.56%   |
| Philips 220EW PHL0861 1680x1050 434x270mm 20.1-inch                      | 1         | 2.56%   |
| Panasonic TV MEIC301 1920x1080 698x392mm 31.5-inch                       | 1         | 2.56%   |
| LG Display LCD Monitor LGD049B 1920x1080 344x194mm 15.5-inch             | 1         | 2.56%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch              | 1         | 2.56%   |
| LG Display LCD Monitor LGD044F 1920x1080 344x194mm 15.5-inch             | 1         | 2.56%   |
| LG Display LCD Monitor LGD040A 1920x1080 309x175mm 14.0-inch             | 1         | 2.56%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch              | 1         | 2.56%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 1         | 2.56%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch              | 1         | 2.56%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch              | 1         | 2.56%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 1         | 2.56%   |
| LG Display LCD Monitor LGD02CA 1366x768 345x194mm 15.6-inch              | 1         | 2.56%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch         | 1         | 2.56%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 1         | 2.56%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 1         | 2.56%   |
| Chi Mei Optoelectronics LCD Monitor CMO1557 1366x768 344x193mm 15.5-inch | 1         | 2.56%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 1         | 2.56%   |
| BOE LCD Monitor BOE0854 1920x1080 344x194mm 15.5-inch                    | 1         | 2.56%   |
| BOE LCD Monitor BOE07A1 1920x1080 344x193mm 15.5-inch                    | 1         | 2.56%   |
| BOE LCD Monitor BOE072B 1920x1080 309x173mm 13.9-inch                    | 1         | 2.56%   |
| BOE LCD Monitor BOE06FB 1920x1080 344x194mm 15.5-inch                    | 1         | 2.56%   |
| BOE LCD Monitor BOE06A6 1366x768 309x174mm 14.0-inch                     | 1         | 2.56%   |
| BOE LCD Monitor BOE0582 1366x768 344x193mm 15.5-inch                     | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO48EC 1366x768 344x193mm 15.5-inch            | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch            | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 1         | 2.56%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                   | 1         | 2.56%   |
| Acer X223W ACR000D 1680x1050 474x296mm 22.0-inch                         | 1         | 2.56%   |
| Acer X223W ACR0009 1680x1050 473x296mm 22.0-inch                         | 1         | 2.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 18        | 48.65%  |
| 1920x1080 (FHD)    | 13        | 35.14%  |
| 2560x1600          | 2         | 5.41%   |
| 1680x1050 (WSXGA+) | 2         | 5.41%   |
| 2560x1440 (QHD)    | 1         | 2.7%    |
| 1280x800 (WXGA)    | 1         | 2.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 21        | 56.76%  |
| 13     | 4         | 10.81%  |
| 14     | 3         | 8.11%   |
| 22     | 2         | 5.41%   |
| 16     | 2         | 5.41%   |
| 12     | 2         | 5.41%   |
| 31     | 1         | 2.7%    |
| 17     | 1         | 2.7%    |
| 11     | 1         | 2.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 27        | 72.97%  |
| 201-300     | 5         | 13.51%  |
| 401-500     | 2         | 5.41%   |
| 351-400     | 2         | 5.41%   |
| 601-700     | 1         | 2.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 31        | 86.11%  |
| 16/10 | 5         | 13.89%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 21        | 56.76%  |
| 81-90          | 6         | 16.22%  |
| 61-70          | 2         | 5.41%   |
| 201-250        | 2         | 5.41%   |
| 111-120        | 2         | 5.41%   |
| 71-80          | 1         | 2.7%    |
| 51-60          | 1         | 2.7%    |
| 351-500        | 1         | 2.7%    |
| 121-130        | 1         | 2.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 15        | 41.67%  |
| 101-120 | 13        | 36.11%  |
| 51-100  | 5         | 13.89%  |
| 161-240 | 3         | 8.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 35        | 92.11%  |
| 2     | 2         | 5.26%   |
| 3     | 1         | 2.63%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 21        | 35.59%  |
| Intel                 | 15        | 25.42%  |
| Qualcomm Atheros      | 7         | 11.86%  |
| Broadcom              | 5         | 8.47%   |
| MediaTek              | 3         | 5.08%   |
| TP-Link               | 2         | 3.39%   |
| Sierra Wireless       | 2         | 3.39%   |
| Ralink Technology     | 1         | 1.69%   |
| Ralink                | 1         | 1.69%   |
| Qualcomm              | 1         | 1.69%   |
| Motorola PCS          | 1         | 1.69%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 13        | 17.57%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 3         | 4.05%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 3         | 4.05%   |
| Intel Wireless 7260                                                                           | 3         | 4.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 3         | 4.05%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 2         | 2.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 2         | 2.7%    |
| Realtek Realtek Ethernet controller                                                           | 2         | 2.7%    |
| Intel Ethernet Connection I218-LM                                                             | 2         | 2.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2         | 2.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 2         | 2.7%    |
| Broadcom BCM43142 802.11b/g/n                                                                 | 2         | 2.7%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 1         | 1.35%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1         | 1.35%   |
| Sierra Wireless EM7345 4G LTE                                                                 | 1         | 1.35%   |
| Sierra Wireless EM7305 Modem                                                                  | 1         | 1.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.35%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.35%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                    | 1         | 1.35%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 1         | 1.35%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                                   | 1         | 1.35%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 1.35%   |
| Realtek Killer E3000 2.5GbE Controller                                                        | 1         | 1.35%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 1.35%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                                     | 1         | 1.35%   |
| Qualcomm BENGAL-QRD _SN:C5464635                                                              | 1         | 1.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1         | 1.35%   |
| Qualcomm Atheros QCA6164 802.11ac Wireless Network Adapter                                    | 1         | 1.35%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                                     | 1         | 1.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1         | 1.35%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                                      | 1         | 1.35%   |
| Motorola PCS moto g(9) play                                                                   | 1         | 1.35%   |
| Intel Wireless 8265 / 8275                                                                    | 1         | 1.35%   |
| Intel Wireless 8260                                                                           | 1         | 1.35%   |
| Intel WiMAX Connection 2400m                                                                  | 1         | 1.35%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 1         | 1.35%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                       | 1         | 1.35%   |
| Intel Ethernet controller                                                                     | 1         | 1.35%   |
| Intel Ethernet Connection I219-LM                                                             | 1         | 1.35%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                               | 1         | 1.35%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 1         | 1.35%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                                          | 1         | 1.35%   |
| Intel 82579V Gigabit Network Connection                                                       | 1         | 1.35%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                                             | 1         | 1.35%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                                           | 1         | 1.35%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                               | 1         | 1.35%   |
| Broadcom BCM4331 802.11a/b/g/n                                                                | 1         | 1.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 15        | 36.59%  |
| Realtek Semiconductor | 8         | 19.51%  |
| Qualcomm Atheros      | 6         | 14.63%  |
| MediaTek              | 3         | 7.32%   |
| Broadcom              | 3         | 7.32%   |
| TP-Link               | 2         | 4.88%   |
| Sierra Wireless       | 2         | 4.88%   |
| Ralink Technology     | 1         | 2.44%   |
| Ralink                | 1         | 2.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 3         | 7.32%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 3         | 7.32%   |
| Intel Wireless 7260                                                                           | 3         | 7.32%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 3         | 7.32%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 2         | 4.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2         | 4.88%   |
| Broadcom BCM43142 802.11b/g/n                                                                 | 2         | 4.88%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 1         | 2.44%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1         | 2.44%   |
| Sierra Wireless EM7345 4G LTE                                                                 | 1         | 2.44%   |
| Sierra Wireless EM7305 Modem                                                                  | 1         | 2.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 2.44%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 2.44%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                    | 1         | 2.44%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 1         | 2.44%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                                   | 1         | 2.44%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 2.44%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 2.44%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                                     | 1         | 2.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1         | 2.44%   |
| Qualcomm Atheros QCA6164 802.11ac Wireless Network Adapter                                    | 1         | 2.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1         | 2.44%   |
| Intel Wireless 8265 / 8275                                                                    | 1         | 2.44%   |
| Intel Wireless 8260                                                                           | 1         | 2.44%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 1         | 2.44%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                       | 1         | 2.44%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                               | 1         | 2.44%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 1         | 2.44%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                                          | 1         | 2.44%   |
| Broadcom BCM4331 802.11a/b/g/n                                                                | 1         | 2.44%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 18        | 54.55%  |
| Intel                 | 8         | 24.24%  |
| Broadcom              | 3         | 9.09%   |
| Qualcomm Atheros      | 2         | 6.06%   |
| Qualcomm              | 1         | 3.03%   |
| Motorola PCS          | 1         | 3.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 39.39%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 6.06%   |
| Realtek Realtek Ethernet controller                               | 2         | 6.06%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 6.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 6.06%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 3.03%   |
| Qualcomm BENGAL-QRD _SN:C5464635                                  | 1         | 3.03%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 3.03%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 3.03%   |
| Motorola PCS moto g(9) play                                       | 1         | 3.03%   |
| Intel WiMAX Connection 2400m                                      | 1         | 3.03%   |
| Intel Ethernet controller                                         | 1         | 3.03%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 3.03%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 3.03%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 3.03%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 3.03%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 3.03%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 35        | 53.03%  |
| Ethernet | 31        | 46.97%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 30        | 81.08%  |
| Ethernet | 7         | 18.92%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 29        | 80.56%  |
| 1     | 6         | 16.67%  |
| 0     | 1         | 2.78%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 30        | 81.08%  |
| Yes  | 7         | 18.92%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 10        | 35.71%  |
| Realtek Semiconductor           | 3         | 10.71%  |
| IMC Networks                    | 3         | 10.71%  |
| Cambridge Silicon Radio         | 3         | 10.71%  |
| Realtek                         | 2         | 7.14%   |
| Broadcom                        | 2         | 7.14%   |
| Qualcomm Atheros Communications | 1         | 3.57%   |
| Lite-On Technology              | 1         | 3.57%   |
| Hewlett-Packard                 | 1         | 3.57%   |
| Foxconn / Hon Hai               | 1         | 3.57%   |
| Apple                           | 1         | 3.57%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 6         | 21.43%  |
| IMC Networks Wireless_Device                        | 3         | 10.71%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 10.71%  |
| Realtek Bluetooth Radio                             | 2         | 7.14%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 7.14%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 3.57%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 3.57%   |
| Realtek Bluetooth Radio                             | 1         | 3.57%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 3.57%   |
| Lite-On Bluetooth Device                            | 1         | 3.57%   |
| Intel AX210 Bluetooth                               | 1         | 3.57%   |
| Intel AX201 Bluetooth                               | 1         | 3.57%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 3.57%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 3.57%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 3.57%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 3.57%   |
| Apple Bluetooth Host Controller                     | 1         | 3.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor            | Notebooks | Percent |
|-------------------|-----------|---------|
| Intel             | 29        | 65.91%  |
| Nvidia            | 8         | 18.18%  |
| AMD               | 5         | 11.36%  |
| Texas Instruments | 1         | 2.27%   |
| Logitech          | 1         | 2.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 9.26%   |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 7.41%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 5.56%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 5.56%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 5.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 5.56%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 3.7%    |
| Nvidia Audio device                                                        | 2         | 3.7%    |
| Intel CM238 HD Audio Controller                                            | 2         | 3.7%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 3.7%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 3.7%    |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 3.7%    |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 1.85%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 1.85%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                  | 1         | 1.85%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.85%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 1.85%   |
| Logitech Headset H390                                                      | 1         | 1.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.85%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 1.85%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.85%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.85%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 1.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.85%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 1.85%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 1.85%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1         | 1.85%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                     | 1         | 1.85%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 1.85%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1.85%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.85%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Micron Technology   | 4         | 28.57%  |
| Samsung Electronics | 3         | 21.43%  |
| Crucial             | 3         | 21.43%  |
| Unknown             | 1         | 7.14%   |
| SK hynix            | 1         | 7.14%   |
| Kingston            | 1         | 7.14%   |
| A-DATA Technology   | 1         | 7.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s       | 2         | 12.5%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s       | 2         | 12.5%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                | 1         | 6.25%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 1         | 6.25%   |
| Samsung RAM Module 2048MB SODIMM LPDDR3 1867MT/s           | 1         | 6.25%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s      | 1         | 6.25%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s   | 1         | 6.25%   |
| Micron RAM 8JTF5126 4HZ1G6D 1 4096MB SODIMM DDR3 1600MT/s  | 1         | 6.25%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s      | 1         | 6.25%   |
| Kingston RAM MSI24D4S7D8MH-16 16384MB SODIMM DDR4 2400MT/s | 1         | 6.25%   |
| Crucial RAM Module 4096MB SODIMM DDR3 1600MT/s             | 1         | 6.25%   |
| Crucial RAM CT51264BF160BJ.C8F 4096MB SODIMM DDR3 1600MT/s | 1         | 6.25%   |
| Crucial RAM CT16G4SFD824A.C16FP 16GB SODIMM DDR4 2400MT/s  | 1         | 6.25%   |
| A-DATA RAM AM1U16BC4P2-B19H 4GB SODIMM DDR3 1600MT/s       | 1         | 6.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 6         | 54.55%  |
| DDR3   | 4         | 36.36%  |
| LPDDR3 | 1         | 9.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 11        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 5         | 41.67%  |
| 4096  | 4         | 33.33%  |
| 16384 | 2         | 16.67%  |
| 2048  | 1         | 8.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 4         | 36.36%  |
| 3200  | 3         | 27.27%  |
| 2400  | 2         | 18.18%  |
| 2667  | 1         | 9.09%   |
| 1867  | 1         | 9.09%   |

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
| Chicony Electronics                    | 8         | 24.24%  |
| IMC Networks                           | 6         | 18.18%  |
| Acer                                   | 5         | 15.15%  |
| Realtek Semiconductor                  | 4         | 12.12%  |
| Sunplus Innovation Technology          | 2         | 6.06%   |
| Samsung Electronics                    | 1         | 3.03%   |
| Pixart Imaging                         | 1         | 3.03%   |
| Microdia                               | 1         | 3.03%   |
| Lite-On Technology                     | 1         | 3.03%   |
| GEMBIRD                                | 1         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.03%   |
| Apple                                  | 1         | 3.03%   |
| Alcor Micro                            | 1         | 3.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                   | 3         | 9.09%   |
| Acer Lenovo EasyCamera                              | 3         | 9.09%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 2         | 6.06%   |
| Sunplus HP HD Webcam [Fixed]                        | 1         | 3.03%   |
| Sunplus ASUS USB2.0 Webcam                          | 1         | 3.03%   |
| Samsung Galaxy A5 (MTP)                             | 1         | 3.03%   |
| Realtek USB Camera                                  | 1         | 3.03%   |
| Realtek Integrated_Webcam_HD                        | 1         | 3.03%   |
| Realtek HP Wide Vision HD Camera                    | 1         | 3.03%   |
| Realtek HD WebCam                                   | 1         | 3.03%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                | 1         | 3.03%   |
| Microdia Integrated Webcam                          | 1         | 3.03%   |
| Lite-On Integrated Camera                           | 1         | 3.03%   |
| IMC Networks ov9734_azurewave_camera                | 1         | 3.03%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]   | 1         | 3.03%   |
| Chicony WebCam                                      | 1         | 3.03%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 3.03%   |
| Chicony USB 2.0 Camera                              | 1         | 3.03%   |
| Chicony Sony Visual Communication Camera            | 1         | 3.03%   |
| Chicony Integrated Camera (1280x720@30)             | 1         | 3.03%   |
| Chicony Integrated Camera                           | 1         | 3.03%   |
| Chicony HP Wide Vision HD Camera                    | 1         | 3.03%   |
| Chicony FJ Camera                                   | 1         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 1         | 3.03%   |
| Apple FaceTime HD Camera                            | 1         | 3.03%   |
| Alcor Micro USB 2.0 PC cam                          | 1         | 3.03%   |
| Acer Integrated Camera                              | 1         | 3.03%   |
| Acer HD Camera                                      | 1         | 3.03%   |

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
| 0     | 24        | 63.16%  |
| 1     | 13        | 34.21%  |
| 2     | 1         | 2.63%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 5         | 35.71%  |
| Graphics card         | 3         | 21.43%  |
| Net/wireless          | 2         | 14.29%  |
| Chipcard              | 2         | 14.29%  |
| Net/ethernet          | 1         | 7.14%   |
| Multimedia controller | 1         | 7.14%   |

