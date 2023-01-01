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

Total: 60

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
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
| Feren OS 20.04 | 23        | 57.5%   |
| Feren OS 18.04 | 17        | 42.5%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Feren OS | 39        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.11.0-37-generic       | 4         | 8.16%   |
| 5.8.0-55-generic        | 3         | 6.12%   |
| 5.3.0-51-generic        | 3         | 6.12%   |
| 5.8.0-50-generic        | 2         | 4.08%   |
| 5.4.0-52-generic        | 2         | 4.08%   |
| 5.4.0-42-generic        | 2         | 4.08%   |
| 5.3.0-53-generic        | 2         | 4.08%   |
| 5.15.0-48-generic       | 2         | 4.08%   |
| 5.0.0-37-generic        | 2         | 4.08%   |
| 5.8.0-53-generic        | 1         | 2.04%   |
| 5.8.0-48-generic        | 1         | 2.04%   |
| 5.8.0-36-generic        | 1         | 2.04%   |
| 5.4.0-58-generic        | 1         | 2.04%   |
| 5.4.0-54-generic        | 1         | 2.04%   |
| 5.4.0-51-generic        | 1         | 2.04%   |
| 5.4.0-48-generic        | 1         | 2.04%   |
| 5.4.0-47-generic        | 1         | 2.04%   |
| 5.4.0-45-generic        | 1         | 2.04%   |
| 5.3.0-59-generic        | 1         | 2.04%   |
| 5.3.0-42-generic        | 1         | 2.04%   |
| 5.17.5-76051705-generic | 1         | 2.04%   |
| 5.15.6-051506-generic   | 1         | 2.04%   |
| 5.15.0-56-generic       | 1         | 2.04%   |
| 5.15.0-53-generic       | 1         | 2.04%   |
| 5.15.0-41-generic       | 1         | 2.04%   |
| 5.13.0-40-generic       | 1         | 2.04%   |
| 5.13.0-30-generic       | 1         | 2.04%   |
| 5.13.0-22-generic       | 1         | 2.04%   |
| 5.13.0-21-generic       | 1         | 2.04%   |
| 5.11.0-40-generic       | 1         | 2.04%   |
| 5.11.0-16-generic       | 1         | 2.04%   |
| 5.0.0-29-generic        | 1         | 2.04%   |
| 5.0.0-25-generic        | 1         | 2.04%   |
| 4.15.0-58-generic       | 1         | 2.04%   |
| 4.15.0-48-generic       | 1         | 2.04%   |
| 4.15.0-47-generic       | 1         | 2.04%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 9         | 21.43%  |
| 5.8.0   | 7         | 16.67%  |
| 5.3.0   | 6         | 14.29%  |
| 5.11.0  | 6         | 14.29%  |
| 5.15.0  | 4         | 9.52%   |
| 5.13.0  | 3         | 7.14%   |
| 5.0.0   | 3         | 7.14%   |
| 4.15.0  | 2         | 4.76%   |
| 5.17.5  | 1         | 2.38%   |
| 5.15.6  | 1         | 2.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 9         | 21.43%  |
| 5.8     | 7         | 16.67%  |
| 5.3     | 6         | 14.29%  |
| 5.11    | 6         | 14.29%  |
| 5.15    | 5         | 11.9%   |
| 5.13    | 3         | 7.14%   |
| 5.0     | 3         | 7.14%   |
| 4.15    | 2         | 4.76%   |
| 5.17    | 1         | 2.38%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 39        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KDE        | 20        | 48.78%  |
| KDE5       | 15        | 36.59%  |
| Unknown    | 4         | 9.76%   |
| X-Cinnamon | 1         | 2.44%   |
| GNOME      | 1         | 2.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 39        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 29        | 74.36%  |
| LightDM | 9         | 23.08%  |
| TDM     | 1         | 2.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 11        | 27.5%   |
| en_GB   | 7         | 17.5%   |
| de_CH   | 4         | 10%     |
| en_IN   | 3         | 7.5%    |
| de_DE   | 3         | 7.5%    |
| Unknown | 3         | 7.5%    |
| nl_BE   | 1         | 2.5%    |
| fi_FI   | 1         | 2.5%    |
| es_VE   | 1         | 2.5%    |
| es_UY   | 1         | 2.5%    |
| es_ES   | 1         | 2.5%    |
| es_CL   | 1         | 2.5%    |
| en_CA   | 1         | 2.5%    |
| en_AG   | 1         | 2.5%    |
| de_AT   | 1         | 2.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 25        | 64.1%   |
| BIOS | 14        | 35.9%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 35        | 87.5%   |
| Btrfs   | 2         | 5%      |
| Unknown | 2         | 5%      |
| Overlay | 1         | 2.5%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 32        | 82.05%  |
| GPT     | 7         | 17.95%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 39        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 31        | 79.49%  |
| Yes       | 8         | 20.51%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| ASUSTek Computer | 9         | 23.08%  |
| Lenovo           | 6         | 15.38%  |
| MSI              | 4         | 10.26%  |
| Hewlett-Packard  | 4         | 10.26%  |
| Dell             | 3         | 7.69%   |
| Acer             | 3         | 7.69%   |
| Sony             | 2         | 5.13%   |
| Apple            | 2         | 5.13%   |
| Toshiba          | 1         | 2.56%   |
| Panasonic        | 1         | 2.56%   |
| HUAWEI           | 1         | 2.56%   |
| Fujitsu          | 1         | 2.56%   |
| Exo              | 1         | 2.56%   |
| Unknown          | 1         | 2.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| ASUS ROG Zephyrus M16 GU603HE_GU603HE    | 2         | 5.13%   |
| Toshiba Satellite T135D                  | 1         | 2.56%   |
| Sony VPCEE4J1E                           | 1         | 2.56%   |
| Sony SVF15318SNB                         | 1         | 2.56%   |
| Panasonic CF-J10YYBHR                    | 1         | 2.56%   |
| MSI Traveller 1591                       | 1         | 2.56%   |
| MSI GS66 Stealth 10SE                    | 1         | 2.56%   |
| MSI GP72 7RDX                            | 1         | 2.56%   |
| MSI GE66 Raider 11UG                     | 1         | 2.56%   |
| Lenovo XiaoXin Air 12 80UN               | 1         | 2.56%   |
| Lenovo ThinkPad X240 20AMS72901          | 1         | 2.56%   |
| Lenovo ThinkPad X230 2325AT6             | 1         | 2.56%   |
| Lenovo Legion Y7000P 81LD                | 1         | 2.56%   |
| Lenovo G550 2958                         | 1         | 2.56%   |
| Lenovo G50-45 80E3                       | 1         | 2.56%   |
| HUAWEI BOHK-WAX9X                        | 1         | 2.56%   |
| HP ProBook 6560b                         | 1         | 2.56%   |
| HP Pavilion Laptop 14-bf0xx              | 1         | 2.56%   |
| HP Pavilion Gaming Laptop 15-cx0xxx      | 1         | 2.56%   |
| HP EliteBook Folio 1040 G1               | 1         | 2.56%   |
| Fujitsu LIFEBOOK E554                    | 1         | 2.56%   |
| Exo CloudbookE15                         | 1         | 2.56%   |
| Dell Latitude E5570                      | 1         | 2.56%   |
| Dell Latitude E5430 vPro                 | 1         | 2.56%   |
| Dell Inspiron 3421                       | 1         | 2.56%   |
| ASUS X550CA                              | 1         | 2.56%   |
| ASUS X541NA                              | 1         | 2.56%   |
| ASUS VivoBook_ASUSLaptop M3500QC_M3500QC | 1         | 2.56%   |
| ASUS VivoBook_ASUS Laptop E210MA_E210MA  | 1         | 2.56%   |
| ASUS S400CA                              | 1         | 2.56%   |
| ASUS P552LJ                              | 1         | 2.56%   |
| ASUS N750JV                              | 1         | 2.56%   |
| Apple MacBookPro8,1                      | 1         | 2.56%   |
| Apple MacBookAir6,2                      | 1         | 2.56%   |
| Acer NG-VX5-591G-52AT                    | 1         | 2.56%   |
| Acer Aspire E5-773                       | 1         | 2.56%   |
| Acer Aspire 5733Z                        | 1         | 2.56%   |
| Unknown                                  | 1         | 2.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 2         | 5.13%   |
| HP Pavilion           | 2         | 5.13%   |
| Dell Latitude         | 2         | 5.13%   |
| ASUS VivoBook         | 2         | 5.13%   |
| ASUS ROG              | 2         | 5.13%   |
| Acer Aspire           | 2         | 5.13%   |
| Toshiba Satellite     | 1         | 2.56%   |
| Sony VPCEE4J1E        | 1         | 2.56%   |
| Sony SVF15318SNB      | 1         | 2.56%   |
| Panasonic CF-J10YYBHR | 1         | 2.56%   |
| MSI Traveller         | 1         | 2.56%   |
| MSI GS66              | 1         | 2.56%   |
| MSI GP72              | 1         | 2.56%   |
| MSI GE66              | 1         | 2.56%   |
| Lenovo XiaoXin        | 1         | 2.56%   |
| Lenovo Legion         | 1         | 2.56%   |
| Lenovo G550           | 1         | 2.56%   |
| Lenovo G50-45         | 1         | 2.56%   |
| HUAWEI BOHK-WAX9X     | 1         | 2.56%   |
| HP ProBook            | 1         | 2.56%   |
| HP EliteBook          | 1         | 2.56%   |
| Fujitsu LIFEBOOK      | 1         | 2.56%   |
| Exo CloudbookE15      | 1         | 2.56%   |
| Dell Inspiron         | 1         | 2.56%   |
| ASUS X550CA           | 1         | 2.56%   |
| ASUS X541NA           | 1         | 2.56%   |
| ASUS S400CA           | 1         | 2.56%   |
| ASUS P552LJ           | 1         | 2.56%   |
| ASUS N750JV           | 1         | 2.56%   |
| Apple MacBookPro8     | 1         | 2.56%   |
| Apple MacBookAir6     | 1         | 2.56%   |
| Acer NG-VX5-591G-52AT | 1         | 2.56%   |
| Unknown               | 1         | 2.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 5         | 12.82%  |
| 2012 | 5         | 12.82%  |
| 2021 | 4         | 10.26%  |
| 2017 | 4         | 10.26%  |
| 2016 | 4         | 10.26%  |
| 2011 | 4         | 10.26%  |
| 2020 | 3         | 7.69%   |
| 2019 | 3         | 7.69%   |
| 2018 | 2         | 5.13%   |
| 2014 | 2         | 5.13%   |
| 2009 | 2         | 5.13%   |
| 2008 | 1         | 2.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 39        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 34        | 85%     |
| Enabled  | 6         | 15%     |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 39        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 11        | 26.83%  |
| 3.01-4.0    | 10        | 24.39%  |
| 8.01-16.0   | 9         | 21.95%  |
| 16.01-24.0  | 8         | 19.51%  |
| 32.01-64.0  | 1         | 2.44%   |
| 64.01-256.0 | 1         | 2.44%   |
| 1.01-2.0    | 1         | 2.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 20        | 44.44%  |
| 2.01-3.0 | 14        | 31.11%  |
| 3.01-4.0 | 6         | 13.33%  |
| 4.01-8.0 | 4         | 8.89%   |
| 0.51-1.0 | 1         | 2.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 29        | 72.5%   |
| 2      | 9         | 22.5%   |
| 3      | 2         | 5%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 25        | 64.1%   |
| Yes       | 14        | 35.9%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 33        | 84.62%  |
| No        | 6         | 15.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 37        | 94.87%  |
| No        | 2         | 5.13%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 72.5%   |
| No        | 11        | 27.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 7         | 17.95%  |
| Switzerland | 4         | 10.26%  |
| Germany     | 4         | 10.26%  |
| UK          | 3         | 7.69%   |
| India       | 3         | 7.69%   |
| Turkey      | 2         | 5.13%   |
| Poland      | 2         | 5.13%   |
| Venezuela   | 1         | 2.56%   |
| Uruguay     | 1         | 2.56%   |
| UAE         | 1         | 2.56%   |
| Spain       | 1         | 2.56%   |
| Japan       | 1         | 2.56%   |
| Guam        | 1         | 2.56%   |
| Greece      | 1         | 2.56%   |
| Finland     | 1         | 2.56%   |
| Chile       | 1         | 2.56%   |
| Canada      | 1         | 2.56%   |
| Bulgaria    | 1         | 2.56%   |
| Belgium     | 1         | 2.56%   |
| Australia   | 1         | 2.56%   |
| Argentina   | 1         | 2.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Oberwil-Lieli      | 3         | 7.14%   |
| Istanbul           | 2         | 4.76%   |
| Escondido          | 2         | 4.76%   |
| Zurich             | 1         | 2.38%   |
| Ypsilanti          | 1         | 2.38%   |
| Yigo Village       | 1         | 2.38%   |
| Winterthur         | 1         | 2.38%   |
| Varna              | 1         | 2.38%   |
| Surat              | 1         | 2.38%   |
| Stuttgart          | 1         | 2.38%   |
| Santiago           | 1         | 2.38%   |
| Saitama            | 1         | 2.38%   |
| Plymouth           | 1         | 2.38%   |
| Phoenix            | 1         | 2.38%   |
| Montevideo         | 1         | 2.38%   |
| Moncton            | 1         | 2.38%   |
| Mieres             | 1         | 2.38%   |
| Maracay            | 1         | 2.38%   |
| Leicester          | 1         | 2.38%   |
| Lafayette          | 1         | 2.38%   |
| Krakow             | 1         | 2.38%   |
| Kloten             | 1         | 2.38%   |
| Karlsruhe          | 1         | 2.38%   |
| Hyderabad          | 1         | 2.38%   |
| Hickory            | 1         | 2.38%   |
| Hämeenlinna       | 1         | 2.38%   |
| Gdynia             | 1         | 2.38%   |
| Gdansk             | 1         | 2.38%   |
| Ernakulam          | 1         | 2.38%   |
| Delmenhorst        | 1         | 2.38%   |
| Corpus Christi     | 1         | 2.38%   |
| Brisbane           | 1         | 2.38%   |
| Birstein           | 1         | 2.38%   |
| Banda del Rio Sali | 1         | 2.38%   |
| Ballymena          | 1         | 2.38%   |
| Athens             | 1         | 2.38%   |
| Al Ain City        | 1         | 2.38%   |
| Aartselaar         | 1         | 2.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Samsung Electronics   | 9         | 10     | 16.98%  |
| Unknown               | 5         | 6      | 9.43%   |
| SanDisk               | 5         | 6      | 9.43%   |
| Intel                 | 4         | 5      | 7.55%   |
| HGST                  | 4         | 4      | 7.55%   |
| Toshiba               | 3         | 5      | 5.66%   |
| Seagate               | 3         | 3      | 5.66%   |
| Hitachi               | 3         | 3      | 5.66%   |
| SK hynix              | 2         | 3      | 3.77%   |
| Phison                | 2         | 2      | 3.77%   |
| OCZ                   | 2         | 2      | 3.77%   |
| Kingston              | 2         | 2      | 3.77%   |
| A-DATA Technology     | 2         | 2      | 3.77%   |
| WDC                   | 1         | 1      | 1.89%   |
| Realtek Semiconductor | 1         | 1      | 1.89%   |
| PNY                   | 1         | 1      | 1.89%   |
| LITEON                | 1         | 1      | 1.89%   |
| Crucial               | 1         | 4      | 1.89%   |
| China                 | 1         | 1      | 1.89%   |
| Apple                 | 1         | 1      | 1.89%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST500LT012-9WS142 500GB        | 2         | 3.7%    |
| Phison NVMe SSD Drive 1TB              | 2         | 3.7%    |
| Intel NVMe SSD Drive 512GB             | 2         | 3.7%    |
| HGST HTS721010A9E630 1TB               | 2         | 3.7%    |
| WDC WD2500BPVT-00JJ5T0 250GB           | 1         | 1.85%   |
| Unknown SD/MMC/MS PRO 64GB             | 1         | 1.85%   |
| Unknown SB128  128GB                   | 1         | 1.85%   |
| Unknown SA04G  4GB                     | 1         | 1.85%   |
| Unknown MMC Card  32GB                 | 1         | 1.85%   |
| Unknown MMC Card  128GB                | 1         | 1.85%   |
| Toshiba THNSNC128GNSJ 128GB SSD        | 1         | 1.85%   |
| Toshiba Q300. 240GB SSD                | 1         | 1.85%   |
| Toshiba MQ01ABD100 1TB                 | 1         | 1.85%   |
| SK hynix HFS128G32TND-N210A 128GB SSD  | 1         | 1.85%   |
| SK hynix HFM001TD3JX013N 1TB           | 1         | 1.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 1         | 1.85%   |
| SanDisk SSD U100 24GB                  | 1         | 1.85%   |
| SanDisk SD9SB8W256G1002 256GB SSD      | 1         | 1.85%   |
| SanDisk SD8SN8U-128G-1006 128GB SSD    | 1         | 1.85%   |
| SanDisk SD6SN1M-256G-1006 256GB SSD    | 1         | 1.85%   |
| SanDisk NVMe SSD Drive 256GB           | 1         | 1.85%   |
| Samsung SSD 860 EVO 250GB              | 1         | 1.85%   |
| Samsung SSD 840 Series 120GB           | 1         | 1.85%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 1         | 1.85%   |
| Samsung Portable SSD T5 500GB          | 1         | 1.85%   |
| Samsung NVMe SSD Drive 1TB             | 1         | 1.85%   |
| Samsung NVMe SSD Drive 1024GB          | 1         | 1.85%   |
| Samsung MZVLW256HEHP-000H1 256GB       | 1         | 1.85%   |
| Samsung MZVLW128HEGR-00000 128GB       | 1         | 1.85%   |
| Samsung MZNTY128HDHP-000L2 128GB SSD   | 1         | 1.85%   |
| Realtek NVMe SSD Drive 512GB           | 1         | 1.85%   |
| PNY CS900 500GB SSD                    | 1         | 1.85%   |
| OCZ VERTEX2 90GB SSD                   | 1         | 1.85%   |
| OCZ AGILITY3 120GB SSD                 | 1         | 1.85%   |
| LITEON IT LCS-128L9S-HP 128GB SSD      | 1         | 1.85%   |
| Kingston SV300S37A120G 120GB SSD       | 1         | 1.85%   |
| Kingston SA400S37240G 240GB SSD        | 1         | 1.85%   |
| Intel SSDSC2BF240A4L 240GB             | 1         | 1.85%   |
| Intel NVMe SSD Drive 256GB             | 1         | 1.85%   |
| Hitachi HTS723232A7A364 320GB          | 1         | 1.85%   |

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
| SSD  | 20        | 30     | 41.67%  |
| HDD  | 13        | 14     | 27.08%  |
| NVMe | 11        | 14     | 22.92%  |
| MMC  | 4         | 5      | 8.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 28        | 41     | 60.87%  |
| NVMe | 11        | 14     | 23.91%  |
| MMC  | 4         | 5      | 8.7%    |
| SAS  | 3         | 3      | 6.52%   |

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
| 101-250    | 16        | 38.1%   |
| 251-500    | 10        | 23.81%  |
| 501-1000   | 6         | 14.29%  |
| 51-100     | 4         | 9.52%   |
| 1001-2000  | 3         | 7.14%   |
| 21-50      | 2         | 4.76%   |
| 1-20       | 1         | 2.38%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 21-50    | 17        | 39.53%  |
| 1-20     | 8         | 18.6%   |
| 51-100   | 8         | 18.6%   |
| 101-250  | 5         | 11.63%  |
| 251-500  | 3         | 6.98%   |
| 501-1000 | 2         | 4.65%   |

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
| Detected | 33        | 50     | 78.57%  |
| Works    | 6         | 10     | 14.29%  |
| Malfunc  | 3         | 3      | 7.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 29        | 64.44%  |
| Samsung Electronics   | 6         | 13.33%  |
| AMD                   | 4         | 8.89%   |
| Phison Electronics    | 2         | 4.44%   |
| SK hynix              | 1         | 2.22%   |
| SanDisk               | 1         | 2.22%   |
| Realtek Semiconductor | 1         | 2.22%   |
| Nvidia                | 1         | 2.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 8.16%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 8.16%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 6.12%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 3         | 6.12%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 4.08%   |
| Phison E12 NVMe Controller                                                     | 2         | 4.08%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 4.08%   |
| Intel Non-Volatile memory controller                                           | 2         | 4.08%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 4.08%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 4.08%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 4.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 4.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 4.08%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 2         | 4.08%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 1         | 2.04%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 2.04%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 2.04%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 2.04%   |
| Samsung NVMe SSD Controller 980                                                | 1         | 2.04%   |
| Samsung Electronics SATA controller                                            | 1         | 2.04%   |
| Realtek Realtek Non-Volatile memory controller                                 | 1         | 2.04%   |
| Nvidia nForce SATA Controller                                                  | 1         | 2.04%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 2.04%   |
| Intel SSD 600P Series                                                          | 1         | 2.04%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 2.04%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 2.04%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 2.04%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 2.04%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 1         | 2.04%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 31        | 65.96%  |
| NVMe | 11        | 23.4%   |
| RAID | 4         | 8.51%   |
| IDE  | 1         | 2.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 33        | 84.62%  |
| AMD    | 6         | 15.38%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 7.69%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 2         | 5.13%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 5.13%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 2.56%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 2.56%   |
| Intel Pentium CPU 4415U @ 2.30GHz             | 1         | 2.56%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz              | 1         | 2.56%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 2.56%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 2.56%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 2.56%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 1         | 2.56%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 2.56%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 2.56%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 2.56%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 2.56%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 2.56%   |
| Intel Core i5-4260U CPU @ 1.40GHz             | 1         | 2.56%   |
| Intel Core i5-4210M CPU @ 2.60GHz             | 1         | 2.56%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 2.56%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 2.56%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 2.56%   |
| Intel Core i5-2435M CPU @ 2.40GHz             | 1         | 2.56%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 2.56%   |
| Intel Core i3-2375M CPU @ 1.50GHz             | 1         | 2.56%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 2.56%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1         | 2.56%   |
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz   | 1         | 2.56%   |
| Intel Celeron CPU 1007U @ 1.50GHz             | 1         | 2.56%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 1         | 2.56%   |
| AMD Turion Neo X2 Dual Core Processor L625    | 1         | 2.56%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 1         | 2.56%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 2.56%   |
| AMD Athlon X2 Dual-Core QL-60                 | 1         | 2.56%   |
| AMD Athlon II P360 Dual-Core Processor        | 1         | 2.56%   |
| AMD A6-6310 APU with AMD Radeon R4 Graphics   | 1         | 2.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 14        | 35.9%   |
| Intel Core i7           | 5         | 12.82%  |
| Other                   | 3         | 7.69%   |
| Intel Pentium           | 3         | 7.69%   |
| Intel Celeron           | 3         | 7.69%   |
| Intel Core i3           | 2         | 5.13%   |
| Intel Core m3           | 1         | 2.56%   |
| Intel Celeron Dual-Core | 1         | 2.56%   |
| Intel Atom              | 1         | 2.56%   |
| AMD Turion Neo X2       | 1         | 2.56%   |
| AMD Ryzen 9             | 1         | 2.56%   |
| AMD Ryzen 5             | 1         | 2.56%   |
| AMD Athlon X2           | 1         | 2.56%   |
| AMD Athlon II           | 1         | 2.56%   |
| AMD A6                  | 1         | 2.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 24        | 61.54%  |
| 4      | 10        | 25.64%  |
| 8      | 5         | 12.82%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 39        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 27        | 69.23%  |
| 1      | 12        | 30.77%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 37        | 94.87%  |
| Unknown        | 2         | 5.13%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x40651    | 4         | 10.26%  |
| 0x206a7    | 4         | 10.26%  |
| 0x806d1    | 3         | 7.69%   |
| 0x406e3    | 3         | 7.69%   |
| 0x306a9    | 3         | 7.69%   |
| 0x906e9    | 2         | 5.13%   |
| 0x706a8    | 2         | 5.13%   |
| 0x306c3    | 2         | 5.13%   |
| Unknown    | 2         | 5.13%   |
| 0xa0652    | 1         | 2.56%   |
| 0x906ea    | 1         | 2.56%   |
| 0x806ea    | 1         | 2.56%   |
| 0x806e9    | 1         | 2.56%   |
| 0x506c9    | 1         | 2.56%   |
| 0x406c4    | 1         | 2.56%   |
| 0x306d4    | 1         | 2.56%   |
| 0x20655    | 1         | 2.56%   |
| 0x1067a    | 1         | 2.56%   |
| 0x0a50000c | 1         | 2.56%   |
| 0x08108109 | 1         | 2.56%   |
| 0x07030105 | 1         | 2.56%   |
| 0x02000032 | 1         | 2.56%   |
| 0x010000c8 | 1         | 2.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Haswell         | 6         | 15.38%  |
| KabyLake        | 5         | 12.82%  |
| SandyBridge     | 4         | 10.26%  |
| IvyBridge       | 4         | 10.26%  |
| Skylake         | 3         | 7.69%   |
| Icelake         | 3         | 7.69%   |
| Goldmont plus   | 2         | 5.13%   |
| Zen+            | 1         | 2.56%   |
| Zen 3           | 1         | 2.56%   |
| Westmere        | 1         | 2.56%   |
| Silvermont      | 1         | 2.56%   |
| Puma            | 1         | 2.56%   |
| Penryn          | 1         | 2.56%   |
| K8 Hammer       | 1         | 2.56%   |
| K8 & K10 hybrid | 1         | 2.56%   |
| K10             | 1         | 2.56%   |
| Goldmont        | 1         | 2.56%   |
| CometLake       | 1         | 2.56%   |
| Broadwell       | 1         | 2.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 32        | 62.75%  |
| Nvidia | 13        | 25.49%  |
| AMD    | 6         | 11.76%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 7.84%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 7.84%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 7.84%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 5.88%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 5.88%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 3.92%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 3.92%   |
| Intel HD Graphics 630                                                                    | 2         | 3.92%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 3.92%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 3.92%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 1.96%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.96%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 1.96%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 1.96%   |
| Nvidia GK107M [GeForce GT 750M]                                                          | 1         | 1.96%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 1.96%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 1.96%   |
| Nvidia C77 [GeForce 9100M G]                                                             | 1         | 1.96%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.96%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.96%   |
| Intel HD Graphics 610                                                                    | 1         | 1.96%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.96%   |
| Intel HD Graphics 515                                                                    | 1         | 1.96%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.96%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.96%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 1         | 1.96%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 1.96%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 1         | 1.96%   |
| AMD RS780M [Mobility Radeon HD 3200]                                                     | 1         | 1.96%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 1.96%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 1.96%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 1         | 1.96%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 21        | 53.85%  |
| Intel + Nvidia | 10        | 25.64%  |
| 1 x AMD        | 4         | 10.26%  |
| 1 x Nvidia     | 2         | 5.13%   |
| Intel + AMD    | 1         | 2.56%   |
| AMD + Nvidia   | 1         | 2.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 32        | 82.05%  |
| Proprietary | 7         | 17.95%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 60%     |
| 1.01-2.0   | 5         | 12.5%   |
| 0.01-0.5   | 4         | 10%     |
| 3.01-4.0   | 3         | 7.5%    |
| 0.51-1.0   | 2         | 5%      |
| 7.01-8.0   | 1         | 2.5%    |
| 5.01-6.0   | 1         | 2.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 10        | 24.39%  |
| AU Optronics            | 8         | 19.51%  |
| BOE                     | 7         | 17.07%  |
| Chimei Innolux          | 4         | 9.76%   |
| Sharp                   | 2         | 4.88%   |
| Samsung Electronics     | 2         | 4.88%   |
| Apple                   | 2         | 4.88%   |
| Toshiba                 | 1         | 2.44%   |
| Sony                    | 1         | 2.44%   |
| Philips                 | 1         | 2.44%   |
| Panasonic               | 1         | 2.44%   |
| Chi Mei Optoelectronics | 1         | 2.44%   |
| Acer                    | 1         | 2.44%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUOC199 2560x1600 344x215mm 16.0-inch           | 2         | 4.76%   |
| Toshiba LCD Monitor LCD0905 1366x768 295x166mm 13.3-inch                 | 1         | 2.38%   |
| Sony AVAMP SNYF400 1920x1080 700x390mm 31.5-inch                         | 1         | 2.38%   |
| Sharp LQ156T1JW04 SHP153C 2560x1440 344x194mm 15.5-inch                  | 1         | 2.38%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 1         | 2.38%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 1         | 2.38%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch    | 1         | 2.38%   |
| Philips 220EW PHL0861 1680x1050 434x270mm 20.1-inch                      | 1         | 2.38%   |
| Panasonic TV MEIC301 1920x1080 698x392mm 31.5-inch                       | 1         | 2.38%   |
| LG Display LCD Monitor LGD049B 1920x1080 344x194mm 15.5-inch             | 1         | 2.38%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch              | 1         | 2.38%   |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch             | 1         | 2.38%   |
| LG Display LCD Monitor LGD040A 1920x1080 309x175mm 14.0-inch             | 1         | 2.38%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch              | 1         | 2.38%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 1         | 2.38%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch              | 1         | 2.38%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch              | 1         | 2.38%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 1         | 2.38%   |
| LG Display LCD Monitor LGD02CA 1366x768 345x194mm 15.6-inch              | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch         | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch          | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 1         | 2.38%   |
| Chi Mei Optoelectronics LCD Monitor CMO1557 1366x768 344x193mm 15.5-inch | 1         | 2.38%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 1         | 2.38%   |
| BOE LCD Monitor BOE0854 1920x1080 344x194mm 15.5-inch                    | 1         | 2.38%   |
| BOE LCD Monitor BOE07A1 1920x1080 344x193mm 15.5-inch                    | 1         | 2.38%   |
| BOE LCD Monitor BOE072B 1920x1080 309x173mm 13.9-inch                    | 1         | 2.38%   |
| BOE LCD Monitor BOE06FB 1920x1080 344x194mm 15.5-inch                    | 1         | 2.38%   |
| BOE LCD Monitor BOE06A6 1366x768 293x165mm 13.2-inch                     | 1         | 2.38%   |
| BOE LCD Monitor BOE0582 1366x768 344x193mm 15.5-inch                     | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO48EC 1366x768 344x193mm 15.5-inch            | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch            | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch           | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 1         | 2.38%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                   | 1         | 2.38%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                     | 1         | 2.38%   |
| Acer X223W ACR000D 1680x1050 470x300mm 22.0-inch                         | 1         | 2.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 18        | 45%     |
| 1920x1080 (FHD)    | 14        | 35%     |
| 2560x1600          | 2         | 5%      |
| 1680x1050 (WSXGA+) | 2         | 5%      |
| 2560x1440 (QHD)    | 1         | 2.5%    |
| 1600x900 (HD+)     | 1         | 2.5%    |
| 1440x900 (WXGA+)   | 1         | 2.5%    |
| 1280x800 (WXGA)    | 1         | 2.5%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 21        | 52.5%   |
| 13     | 5         | 12.5%   |
| 17     | 3         | 7.5%    |
| 14     | 3         | 7.5%    |
| 22     | 2         | 5%      |
| 16     | 2         | 5%      |
| 12     | 2         | 5%      |
| 31     | 1         | 2.5%    |
| 11     | 1         | 2.5%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 27        | 67.5%   |
| 201-300     | 6         | 15%     |
| 351-400     | 4         | 10%     |
| 401-500     | 2         | 5%      |
| 601-700     | 1         | 2.5%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 33        | 84.62%  |
| 16/10 | 6         | 15.38%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 21        | 52.5%   |
| 81-90          | 7         | 17.5%   |
| 121-130        | 3         | 7.5%    |
| 61-70          | 2         | 5%      |
| 201-250        | 2         | 5%      |
| 111-120        | 2         | 5%      |
| 71-80          | 1         | 2.5%    |
| 51-60          | 1         | 2.5%    |
| 351-500        | 1         | 2.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 17        | 43.59%  |
| 101-120 | 14        | 35.9%   |
| 51-100  | 5         | 12.82%  |
| 161-240 | 3         | 7.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 38        | 92.68%  |
| 2     | 2         | 4.88%   |
| 3     | 1         | 2.44%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 23        | 36.51%  |
| Intel                 | 15        | 23.81%  |
| Qualcomm Atheros      | 8         | 12.7%   |
| Broadcom              | 5         | 7.94%   |
| MediaTek              | 3         | 4.76%   |
| TP-Link               | 2         | 3.17%   |
| Sierra Wireless       | 2         | 3.17%   |
| Ralink Technology     | 1         | 1.59%   |
| Ralink                | 1         | 1.59%   |
| Qualcomm              | 1         | 1.59%   |
| Motorola PCS          | 1         | 1.59%   |
| Broadcom Limited      | 1         | 1.59%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 15        | 19.23%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 4         | 5.13%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 3         | 3.85%   |
| Intel Wireless 7260                                                                           | 3         | 3.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 3         | 3.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 2         | 2.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 2         | 2.56%   |
| Realtek Realtek Ethernet controller                                                           | 2         | 2.56%   |
| Intel Ethernet Connection I218-LM                                                             | 2         | 2.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2         | 2.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 2         | 2.56%   |
| Broadcom BCM43142 802.11b/g/n                                                                 | 2         | 2.56%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 1         | 1.28%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1         | 1.28%   |
| Sierra Wireless EM7345 4G LTE                                                                 | 1         | 1.28%   |
| Sierra Wireless EM7305 Modem                                                                  | 1         | 1.28%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.28%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.28%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 1         | 1.28%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                                   | 1         | 1.28%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 1.28%   |
| Realtek Killer E3000 2.5GbE Controller                                                        | 1         | 1.28%   |
| Realtek 802.11n WLAN Adapter                                                                  | 1         | 1.28%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 1.28%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                                     | 1         | 1.28%   |
| Qualcomm MegaFon M150-4                                                                       | 1         | 1.28%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1         | 1.28%   |
| Qualcomm Atheros QCA6164 802.11ac Wireless Network Adapter                                    | 1         | 1.28%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                                     | 1         | 1.28%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1         | 1.28%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                                      | 1         | 1.28%   |
| Motorola PCS moto g(9) play                                                                   | 1         | 1.28%   |
| Intel Wireless 8265 / 8275                                                                    | 1         | 1.28%   |
| Intel Wireless 8260                                                                           | 1         | 1.28%   |
| Intel WiMAX Connection 2400m                                                                  | 1         | 1.28%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 1         | 1.28%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                       | 1         | 1.28%   |
| Intel Ethernet controller                                                                     | 1         | 1.28%   |
| Intel Ethernet Connection I219-LM                                                             | 1         | 1.28%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                               | 1         | 1.28%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 15        | 34.88%  |
| Realtek Semiconductor | 8         | 18.6%   |
| Qualcomm Atheros      | 7         | 16.28%  |
| MediaTek              | 3         | 6.98%   |
| Broadcom              | 3         | 6.98%   |
| TP-Link               | 2         | 4.65%   |
| Sierra Wireless       | 2         | 4.65%   |
| Ralink Technology     | 1         | 2.33%   |
| Ralink                | 1         | 2.33%   |
| Broadcom Limited      | 1         | 2.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 4         | 9.3%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 3         | 6.98%   |
| Intel Wireless 7260                                                                           | 3         | 6.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 3         | 6.98%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 2         | 4.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2         | 4.65%   |
| Broadcom BCM43142 802.11b/g/n                                                                 | 2         | 4.65%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 1         | 2.33%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1         | 2.33%   |
| Sierra Wireless EM7345 4G LTE                                                                 | 1         | 2.33%   |
| Sierra Wireless EM7305 Modem                                                                  | 1         | 2.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 2.33%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 2.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 1         | 2.33%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                                   | 1         | 2.33%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 2.33%   |
| Realtek 802.11n WLAN Adapter                                                                  | 1         | 2.33%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 2.33%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                                     | 1         | 2.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1         | 2.33%   |
| Qualcomm Atheros QCA6164 802.11ac Wireless Network Adapter                                    | 1         | 2.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 1         | 2.33%   |
| Intel Wireless 8265 / 8275                                                                    | 1         | 2.33%   |
| Intel Wireless 8260                                                                           | 1         | 2.33%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 1         | 2.33%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                       | 1         | 2.33%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                               | 1         | 2.33%   |
| Intel Comet Lake PCH CNVi WiFi                                                                | 1         | 2.33%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                                          | 1         | 2.33%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                                    | 1         | 2.33%   |
| Broadcom BCM4331 802.11a/b/g/n                                                                | 1         | 2.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 20        | 57.14%  |
| Intel                 | 8         | 22.86%  |
| Broadcom              | 3         | 8.57%   |
| Qualcomm Atheros      | 2         | 5.71%   |
| Qualcomm              | 1         | 2.86%   |
| Motorola PCS          | 1         | 2.86%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 15        | 42.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 5.71%   |
| Realtek Realtek Ethernet controller                               | 2         | 5.71%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 5.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 5.71%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 2.86%   |
| Qualcomm MegaFon M150-4                                           | 1         | 2.86%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 2.86%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 2.86%   |
| Motorola PCS moto g(9) play                                       | 1         | 2.86%   |
| Intel WiMAX Connection 2400m                                      | 1         | 2.86%   |
| Intel Ethernet controller                                         | 1         | 2.86%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.86%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 2.86%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 2.86%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 2.86%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.86%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 37        | 52.86%  |
| Ethernet | 33        | 47.14%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 31        | 77.5%   |
| Ethernet | 9         | 22.5%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 30        | 76.92%  |
| 1     | 8         | 20.51%  |
| 0     | 1         | 2.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 32        | 80%     |
| Yes  | 8         | 20%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 10        | 33.33%  |
| IMC Networks                    | 4         | 13.33%  |
| Realtek Semiconductor           | 3         | 10%     |
| Cambridge Silicon Radio         | 3         | 10%     |
| Realtek                         | 2         | 6.67%   |
| Broadcom                        | 2         | 6.67%   |
| Apple                           | 2         | 6.67%   |
| Qualcomm Atheros Communications | 1         | 3.33%   |
| Lite-On Technology              | 1         | 3.33%   |
| Hewlett-Packard                 | 1         | 3.33%   |
| Foxconn / Hon Hai               | 1         | 3.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 6         | 20%     |
| IMC Networks Wireless_Device                        | 3         | 10%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 10%     |
| Realtek Bluetooth Radio                             | 2         | 6.67%   |
| Realtek Bluetooth Radio                             | 2         | 6.67%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 6.67%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 3.33%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 3.33%   |
| Lite-On Bluetooth Device                            | 1         | 3.33%   |
| Intel AX210 Bluetooth                               | 1         | 3.33%   |
| Intel AX201 Bluetooth                               | 1         | 3.33%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 3.33%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 3.33%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 3.33%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 3.33%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 3.33%   |
| Apple Bluetooth USB Host Controller                 | 1         | 3.33%   |
| Apple Bluetooth Host Controller                     | 1         | 3.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor            | Notebooks | Percent |
|-------------------|-----------|---------|
| Intel             | 32        | 68.09%  |
| Nvidia            | 8         | 17.02%  |
| AMD               | 5         | 10.64%  |
| Texas Instruments | 1         | 2.13%   |
| Logitech          | 1         | 2.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 5         | 8.47%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 8.47%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 6.78%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 6.78%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 5.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 5.08%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 3.39%   |
| Nvidia Audio device                                                        | 2         | 3.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 3.39%   |
| Intel CM238 HD Audio Controller                                            | 2         | 3.39%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 3.39%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 3.39%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 3.39%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 3.39%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 1.69%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 1.69%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                  | 1         | 1.69%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.69%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 1.69%   |
| Logitech Headset H390                                                      | 1         | 1.69%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 1.69%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 1.69%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.69%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 1.69%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.69%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 1.69%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1         | 1.69%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                     | 1         | 1.69%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 1.69%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1.69%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.69%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Micron Technology   | 4         | 25%     |
| Samsung Electronics | 3         | 18.75%  |
| Crucial             | 3         | 18.75%  |
| SK hynix            | 2         | 12.5%   |
| Kingston            | 2         | 12.5%   |
| Unknown             | 1         | 6.25%   |
| A-DATA Technology   | 1         | 6.25%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 2         | 11.11%  |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s       | 2         | 11.11%  |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s       | 2         | 11.11%  |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                | 1         | 5.56%   |
| Samsung RAM Module 2048MB SODIMM LPDDR3 1867MT/s           | 1         | 5.56%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s      | 1         | 5.56%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s      | 1         | 5.56%   |
| Micron RAM 8JTF5126 4HZ1G6D 1 4GB SODIMM DDR3 1600MT/s     | 1         | 5.56%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s      | 1         | 5.56%   |
| Kingston RAM MSI24D4S7D8MH-16 16384MB SODIMM DDR4 2400MT/s | 1         | 5.56%   |
| Kingston RAM ASU16D3LS1KBG/4G 4096MB SODIMM DDR3 1600MT/s  | 1         | 5.56%   |
| Crucial RAM Module 4096MB SODIMM DDR3 1600MT/s             | 1         | 5.56%   |
| Crucial RAM CT51264BF160BJ.C8F 4GB SODIMM DDR3             | 1         | 5.56%   |
| Crucial RAM CT16G4SFD824A.C16FP 16GB SODIMM DDR4 2400MT/s  | 1         | 5.56%   |
| A-DATA RAM AM1U16BC4P2-B19H 4GB SODIMM DDR3 1600MT/s       | 1         | 5.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 6         | 46.15%  |
| DDR3   | 6         | 46.15%  |
| LPDDR3 | 1         | 7.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 13        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 6         | 42.86%  |
| 8192  | 5         | 35.71%  |
| 16384 | 2         | 14.29%  |
| 2048  | 1         | 7.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 6         | 46.15%  |
| 3200  | 3         | 23.08%  |
| 2400  | 2         | 15.38%  |
| 2667  | 1         | 7.69%   |
| 1867  | 1         | 7.69%   |

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
| HP Laser 107a | 1         | 100%    |

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
| Chicony Electronics                    | 9         | 25.71%  |
| IMC Networks                           | 7         | 20%     |
| Acer                                   | 5         | 14.29%  |
| Realtek Semiconductor                  | 4         | 11.43%  |
| Sunplus Innovation Technology          | 2         | 5.71%   |
| Samsung Electronics                    | 1         | 2.86%   |
| Pixart Imaging                         | 1         | 2.86%   |
| Microdia                               | 1         | 2.86%   |
| Lite-On Technology                     | 1         | 2.86%   |
| GEMBIRD                                | 1         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.86%   |
| Apple                                  | 1         | 2.86%   |
| Alcor Micro                            | 1         | 2.86%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                   | 3         | 8.57%   |
| Acer Lenovo EasyCamera                              | 3         | 8.57%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 2         | 5.71%   |
| Sunplus HP HD Webcam [Fixed]                        | 1         | 2.86%   |
| Sunplus Asus Webcam                                 | 1         | 2.86%   |
| Samsung Galaxy A5 (MTP)                             | 1         | 2.86%   |
| Realtek USB Camera                                  | 1         | 2.86%   |
| Realtek Integrated_Webcam_HD                        | 1         | 2.86%   |
| Realtek HP Wide Vision HD Camera                    | 1         | 2.86%   |
| Realtek HD WebCam                                   | 1         | 2.86%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                | 1         | 2.86%   |
| Microdia Integrated Webcam                          | 1         | 2.86%   |
| Lite-On Integrated Camera                           | 1         | 2.86%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 1         | 2.86%   |
| IMC Networks ov9734_azurewave_camera                | 1         | 2.86%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]   | 1         | 2.86%   |
| Chicony WebCam                                      | 1         | 2.86%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 2.86%   |
| Chicony USB 2.0 Camera                              | 1         | 2.86%   |
| Chicony Sony Visual Communication Camera            | 1         | 2.86%   |
| Chicony Integrated Camera (1280x720@30)             | 1         | 2.86%   |
| Chicony Integrated Camera                           | 1         | 2.86%   |
| Chicony HP Wide Vision HD Camera                    | 1         | 2.86%   |
| Chicony HD WebCam                                   | 1         | 2.86%   |
| Chicony FJ Camera                                   | 1         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 1         | 2.86%   |
| Apple FaceTime HD Camera                            | 1         | 2.86%   |
| Alcor Micro USB 2.0 Camera                          | 1         | 2.86%   |
| Acer Integrated Camera                              | 1         | 2.86%   |
| Acer HD Camera                                      | 1         | 2.86%   |

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
| 0     | 25        | 60.98%  |
| 1     | 15        | 36.59%  |
| 2     | 1         | 2.44%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 5         | 31.25%  |
| Net/wireless          | 3         | 18.75%  |
| Graphics card         | 3         | 18.75%  |
| Multimedia controller | 2         | 12.5%   |
| Chipcard              | 2         | 12.5%   |
| Net/ethernet          | 1         | 6.25%   |

