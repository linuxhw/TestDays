Pardus - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Pardus.

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

Total: 34

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| TUXEDO        | Unknown                     | [52ddc219ae](https://linux-hardware.org/?probe=52ddc219ae) | Sep 23, 2022 |
| HUAWEI        | KLVL-WXXW                   | [60ebd510a4](https://linux-hardware.org/?probe=60ebd510a4) | Sep 07, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [bcbbd7f228](https://linux-hardware.org/?probe=bcbbd7f228) | Jul 05, 2022 |
| Sony          | SVE14A2V2ES                 | [59435d662a](https://linux-hardware.org/?probe=59435d662a) | May 11, 2022 |
| Acer          | Aspire 5742G                | [b3cef97540](https://linux-hardware.org/?probe=b3cef97540) | Apr 12, 2022 |
| Sony          | SVE14A2V2ES                 | [b2695cc80d](https://linux-hardware.org/?probe=b2695cc80d) | Mar 13, 2022 |
| Sony          | SVE14A2V2ES                 | [4b2203862a](https://linux-hardware.org/?probe=4b2203862a) | Mar 11, 2022 |
| Sony          | SVE14A2V2ES                 | [1575f2f0be](https://linux-hardware.org/?probe=1575f2f0be) | Mar 11, 2022 |
| Sony          | SVE14A2V2ES                 | [ef603529f2](https://linux-hardware.org/?probe=ef603529f2) | Mar 08, 2022 |
| Sony          | SVE14A2V2ES                 | [35fe0c18bc](https://linux-hardware.org/?probe=35fe0c18bc) | Mar 07, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [e60367127e](https://linux-hardware.org/?probe=e60367127e) | Mar 07, 2022 |
| Sony          | SVF1521QSTB                 | [f74068fef9](https://linux-hardware.org/?probe=f74068fef9) | Feb 14, 2022 |
| HP            | Pavilion 15                 | [fe001e576b](https://linux-hardware.org/?probe=fe001e576b) | Feb 13, 2022 |
| Packard Be... | EasyNote ENTG81BA           | [10f68b4c82](https://linux-hardware.org/?probe=10f68b4c82) | Jan 31, 2022 |
| Lenovo        | V145-15AST 81MT             | [121a750c5b](https://linux-hardware.org/?probe=121a750c5b) | Jan 03, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | [16efe9685d](https://linux-hardware.org/?probe=16efe9685d) | Dec 17, 2021 |
| Toshiba       | PORTEGE M780                | [c68379ab38](https://linux-hardware.org/?probe=c68379ab38) | Nov 30, 2021 |
| HP            | Laptop 15-dw3xxx            | [1cf8a783be](https://linux-hardware.org/?probe=1cf8a783be) | Oct 21, 2021 |
| HP            | Laptop 15-dw3xxx            | [20a54c9779](https://linux-hardware.org/?probe=20a54c9779) | Oct 21, 2021 |
| Lenovo        | IdeaPad-510-15IKB 80SV      | [1a343f3596](https://linux-hardware.org/?probe=1a343f3596) | Sep 02, 2021 |
| Philco        | 14F                         | [343861b100](https://linux-hardware.org/?probe=343861b100) | Jun 20, 2021 |
| Toshiba       | Satellite C855-1VM          | [dab32c2669](https://linux-hardware.org/?probe=dab32c2669) | Jan 24, 2021 |
| Lenovo        | ThinkPad T450 20BUS39Y00    | [579099bf91](https://linux-hardware.org/?probe=579099bf91) | Dec 26, 2020 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [39f1d96886](https://linux-hardware.org/?probe=39f1d96886) | Dec 16, 2020 |
| ASUSTek       | X555YI                      | [d210c4b901](https://linux-hardware.org/?probe=d210c4b901) | Sep 26, 2020 |
| Packard Be... | EasyNote_GN45               | [210b740311](https://linux-hardware.org/?probe=210b740311) | Sep 24, 2020 |
| Dell          | Latitude E6540              | [d2337e32c1](https://linux-hardware.org/?probe=d2337e32c1) | Sep 05, 2020 |
| ASUSTek       | E402BP                      | [d531d0fe45](https://linux-hardware.org/?probe=d531d0fe45) | Jun 01, 2020 |
| HP            | 15                          | [36d90829ee](https://linux-hardware.org/?probe=36d90829ee) | May 02, 2020 |
| HP            | 15                          | [06393a1175](https://linux-hardware.org/?probe=06393a1175) | Apr 27, 2020 |
| HP            | 15                          | [e21973794b](https://linux-hardware.org/?probe=e21973794b) | Feb 02, 2020 |
| Dell          | G5 5587                     | [1742540bc9](https://linux-hardware.org/?probe=1742540bc9) | Nov 27, 2019 |
| Lenovo        | V110-15ISK 80TL             | [dd8de8c9a2](https://linux-hardware.org/?probe=dd8de8c9a2) | Oct 18, 2019 |
| HP            | 250 G3                      | [e82ead9af0](https://linux-hardware.org/?probe=e82ead9af0) | Oct 13, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Pardus 21.1   | 5         | 17.86%  |
| Pardus 21.2   | 4         | 14.29%  |
| Pardus 21.0   | 3         | 10.71%  |
| Pardus 19.5   | 3         | 10.71%  |
| Pardus 19.3   | 3         | 10.71%  |
| Pardus 19.4-1 | 2         | 7.14%   |
| Pardus 19.2   | 2         | 7.14%   |
| Pardus 19.1   | 2         | 7.14%   |
| Pardus 19.0   | 2         | 7.14%   |
| Pardus 21.3   | 1         | 3.57%   |
| Pardus 19.4   | 1         | 3.57%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Pardus | 26        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 5.10.0-13-amd64      | 3         | 10.71%  |
| 5.10.0-11-amd64      | 3         | 10.71%  |
| 4.19.0-6-amd64       | 3         | 10.71%  |
| 4.19.0-10-amd64      | 3         | 10.71%  |
| 5.10.0-9-amd64       | 2         | 7.14%   |
| 5.10.0-10-amd64      | 2         | 7.14%   |
| 4.19.0-13-amd64      | 2         | 7.14%   |
| 5.9.0-0.bpo.2-amd64  | 1         | 3.57%   |
| 5.4.0-0.bpo.3-amd64  | 1         | 3.57%   |
| 5.10.0-8-amd64       | 1         | 3.57%   |
| 5.10.0-17-amd64      | 1         | 3.57%   |
| 5.10.0-14-amd64      | 1         | 3.57%   |
| 5.10.0-0.bpo.8-amd64 | 1         | 3.57%   |
| 4.19.0-8-amd64       | 1         | 3.57%   |
| 4.19.0-5-amd64       | 1         | 3.57%   |
| 4.19.0-19-amd64      | 1         | 3.57%   |
| 4.19.0-16-amd64      | 1         | 3.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 14        | 51.85%  |
| 4.19.0  | 11        | 40.74%  |
| 5.9.0   | 1         | 3.7%    |
| 5.4.0   | 1         | 3.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 14        | 51.85%  |
| 4.19    | 11        | 40.74%  |
| 5.9     | 1         | 3.7%    |
| 5.4     | 1         | 3.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 26        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| XFCE    | 18        | 69.23%  |
| GNOME   | 5         | 19.23%  |
| Unknown | 2         | 7.69%   |
| KDE5    | 1         | 3.85%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 26        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 15        | 57.69%  |
| TDM     | 6         | 23.08%  |
| GDM     | 3         | 11.54%  |
| LightDM | 2         | 7.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| tr_TR   | 19        | 73.08%  |
| Unknown | 3         | 11.54%  |
| en_US   | 2         | 7.69%   |
| pt_BR   | 1         | 3.85%   |
| en_GB   | 1         | 3.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 18        | 66.67%  |
| EFI  | 9         | 33.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 25        | 96.15%  |
| Overlay | 1         | 3.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 16        | 61.54%  |
| GPT     | 8         | 30.77%  |
| MBR     | 2         | 7.69%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 24        | 92.31%  |
| Yes       | 2         | 7.69%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 19        | 73.08%  |
| Yes       | 7         | 26.92%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 7         | 26.92%  |
| Hewlett-Packard     | 4         | 15.38%  |
| Toshiba             | 2         | 7.69%   |
| Sony                | 2         | 7.69%   |
| Packard Bell        | 2         | 7.69%   |
| Dell                | 2         | 7.69%   |
| ASUSTek Computer    | 2         | 7.69%   |
| TUXEDO              | 1         | 3.85%   |
| Samsung Electronics | 1         | 3.85%   |
| Philco              | 1         | 3.85%   |
| HUAWEI              | 1         | 3.85%   |
| Acer                | 1         | 3.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Toshiba Satellite C855-1VM                 | 1         | 3.85%   |
| Toshiba PORTEGE M780                       | 1         | 3.85%   |
| Sony SVF1521QSTB                           | 1         | 3.85%   |
| Sony SVE14A2V2ES                           | 1         | 3.85%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 3.85%   |
| Philco 14F                                 | 1         | 3.85%   |
| Packard Bell EasyNote_GN45                 | 1         | 3.85%   |
| Packard Bell EasyNote ENTG81BA             | 1         | 3.85%   |
| Lenovo V145-15AST 81MT                     | 1         | 3.85%   |
| Lenovo V110-15ISK 80TL                     | 1         | 3.85%   |
| Lenovo ThinkPad T450 20BUS39Y00            | 1         | 3.85%   |
| Lenovo ThinkPad E15 Gen 2 20TD0047TX       | 1         | 3.85%   |
| Lenovo IdeaPad-510-15IKB 80SV              | 1         | 3.85%   |
| Lenovo IdeaPad 320-15IKB 81BT              | 1         | 3.85%   |
| Lenovo IdeaPad 100-15IBD 80QQ              | 1         | 3.85%   |
| HUAWEI KLVL-WXXW                           | 1         | 3.85%   |
| HP Pavilion 15                             | 1         | 3.85%   |
| HP Laptop 15-dw3xxx                        | 1         | 3.85%   |
| HP 250 G3                                  | 1         | 3.85%   |
| HP 15                                      | 1         | 3.85%   |
| Dell Latitude E6540                        | 1         | 3.85%   |
| Dell G5 5587                               | 1         | 3.85%   |
| ASUS X555YI                                | 1         | 3.85%   |
| ASUS E402BP                                | 1         | 3.85%   |
| Acer Aspire 5742G                          | 1         | 3.85%   |
| Unknown                                    | 1         | 3.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Packard Bell EasyNote    | 2         | 7.69%   |
| Lenovo ThinkPad          | 2         | 7.69%   |
| Lenovo IdeaPad           | 2         | 7.69%   |
| Toshiba Satellite        | 1         | 3.85%   |
| Toshiba PORTEGE          | 1         | 3.85%   |
| Sony SVF1521QSTB         | 1         | 3.85%   |
| Sony SVE14A2V2ES         | 1         | 3.85%   |
| Samsung 300E4A           | 1         | 3.85%   |
| Philco 14F               | 1         | 3.85%   |
| Lenovo V145-15AST        | 1         | 3.85%   |
| Lenovo V110-15ISK        | 1         | 3.85%   |
| Lenovo IdeaPad-510-15IKB | 1         | 3.85%   |
| HUAWEI KLVL-WXXW         | 1         | 3.85%   |
| HP Pavilion              | 1         | 3.85%   |
| HP Laptop                | 1         | 3.85%   |
| HP 250                   | 1         | 3.85%   |
| HP 15                    | 1         | 3.85%   |
| Dell Latitude            | 1         | 3.85%   |
| Dell G5                  | 1         | 3.85%   |
| ASUS X555YI              | 1         | 3.85%   |
| ASUS E402BP              | 1         | 3.85%   |
| Acer Aspire              | 1         | 3.85%   |
| Unknown                  | 1         | 3.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 6         | 23.08%  |
| 2018 | 4         | 15.38%  |
| 2015 | 4         | 15.38%  |
| 2020 | 2         | 7.69%   |
| 2019 | 2         | 7.69%   |
| 2011 | 2         | 7.69%   |
| 2010 | 2         | 7.69%   |
| 2021 | 1         | 3.85%   |
| 2016 | 1         | 3.85%   |
| 2014 | 1         | 3.85%   |
| 2006 | 1         | 3.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 26        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 26        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 26        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 9         | 34.62%  |
| 4.01-8.0   | 7         | 26.92%  |
| 16.01-24.0 | 4         | 15.38%  |
| 8.01-16.0  | 4         | 15.38%  |
| 1.01-2.0   | 2         | 7.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 12        | 44.44%  |
| 2.01-3.0 | 8         | 29.63%  |
| 3.01-4.0 | 4         | 14.81%  |
| 4.01-8.0 | 2         | 7.41%   |
| 0.51-1.0 | 1         | 3.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 20        | 76.92%  |
| 2      | 5         | 19.23%  |
| 3      | 1         | 3.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 14        | 53.85%  |
| No        | 12        | 46.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 92.31%  |
| No        | 2         | 7.69%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 21        | 80.77%  |
| No        | 5         | 19.23%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Turkey  | 23        | 88.46%  |
| UK      | 1         | 3.85%   |
| Sweden  | 1         | 3.85%   |
| Brazil  | 1         | 3.85%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City        | Notebooks | Percent |
|-------------|-----------|---------|
| Istanbul    | 9         | 32.14%  |
| Ankara      | 4         | 14.29%  |
| Izmir       | 3         | 10.71%  |
| Çanakkale  | 2         | 7.14%   |
| Sao Gabriel | 1         | 3.57%   |
| London      | 1         | 3.57%   |
| Landskrona  | 1         | 3.57%   |
| Konya       | 1         | 3.57%   |
| Gaziantep   | 1         | 3.57%   |
| Esenyurt    | 1         | 3.57%   |
| Bursa       | 1         | 3.57%   |
| Aydin       | 1         | 3.57%   |
| Artvin      | 1         | 3.57%   |
| Antalya     | 1         | 3.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 8      | 18.75%  |
| Seagate             | 5         | 5      | 15.63%  |
| Samsung Electronics | 4         | 4      | 12.5%   |
| SK hynix            | 2         | 2      | 6.25%   |
| SanDisk             | 2         | 2      | 6.25%   |
| Kingston            | 2         | 3      | 6.25%   |
| HGST                | 2         | 2      | 6.25%   |
| SPCC                | 1         | 1      | 3.13%   |
| Silicon Motion      | 1         | 1      | 3.13%   |
| Phison              | 1         | 1      | 3.13%   |
| Micron Technology   | 1         | 2      | 3.13%   |
| Lexar               | 1         | 1      | 3.13%   |
| KingSpec            | 1         | 1      | 3.13%   |
| Hitachi             | 1         | 1      | 3.13%   |
| addlink             | 1         | 1      | 3.13%   |
| Unknown             | 1         | 1      | 3.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| HGST HTS545050A7E680 500GB                  | 2         | 6.25%   |
| WDC WD5000LPVX-55V0TT0 500GB                | 1         | 3.13%   |
| WDC WD5000LPCX-60VHAT0 500GB                | 1         | 3.13%   |
| WDC WD5000LPCX-21VHAT0 500GB                | 1         | 3.13%   |
| WDC WD3200BPVT-35JJ5T0 320GB                | 1         | 3.13%   |
| WDC WD10JPVX-60JC3T0 1TB                    | 1         | 3.13%   |
| WDC WD10JPCX-24UE4T0 1TB                    | 1         | 3.13%   |
| SPCC Solid State Disk 512GB                 | 1         | 3.13%   |
| SK hynix SC311 SATA 256GB SSD               | 1         | 3.13%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB     | 1         | 3.13%   |
| Silicon Motion Longline SSD 512GB           | 1         | 3.13%   |
| Seagate ST9500325AS 500GB                   | 1         | 3.13%   |
| Seagate ST9120822AS 120GB                   | 1         | 3.13%   |
| Seagate ST1000LM035-1RK172 1TB              | 1         | 3.13%   |
| Seagate Expansion 1TB                       | 1         | 3.13%   |
| Seagate BarraCuda Q1 SSD ZA480CV10001 480GB | 1         | 3.13%   |
| SanDisk SSD PLUS 240GB                      | 1         | 3.13%   |
| SanDisk SDSSDA480G 480GB                    | 1         | 3.13%   |
| Samsung SSD 860 EVO 500GB                   | 1         | 3.13%   |
| Samsung MZALQ256HAJD-000L1 256GB            | 1         | 3.13%   |
| Samsung MZ7LN128HAHQ-000L2 128GB SSD        | 1         | 3.13%   |
| Samsung MZ7LF192HCGS-000L1 192GB SSD        | 1         | 3.13%   |
| Phison 311CD0512GB                          | 1         | 3.13%   |
| Micron 1300_MTFDDAK512TDL 512GB SSD         | 1         | 3.13%   |
| Lexar 120GB SSD                             | 1         | 3.13%   |
| Kingston SHFS37A120G 120GB SSD              | 1         | 3.13%   |
| Kingston SA400S37240G 240GB SSD             | 1         | 3.13%   |
| KingSpec P3-128 128GB                       | 1         | 3.13%   |
| Hitachi HTS545025B9A300 250GB               | 1         | 3.13%   |
| addlink S10 960GB                           | 1         | 3.13%   |
| Unknown                                     | 1         | 3.13%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 6         | 8      | 46.15%  |
| Seagate | 4         | 4      | 30.77%  |
| HGST    | 2         | 2      | 15.38%  |
| Hitachi | 1         | 1      | 7.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 23.08%  |
| SanDisk             | 2         | 2      | 15.38%  |
| Kingston            | 2         | 3      | 15.38%  |
| SPCC                | 1         | 1      | 7.69%   |
| SK hynix            | 1         | 1      | 7.69%   |
| Seagate             | 1         | 1      | 7.69%   |
| Micron Technology   | 1         | 2      | 7.69%   |
| Lexar               | 1         | 1      | 7.69%   |
| KingSpec            | 1         | 1      | 7.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 13        | 15     | 44.83%  |
| SSD     | 11        | 15     | 37.93%  |
| NVMe    | 3         | 4      | 10.34%  |
| Unknown | 2         | 2      | 6.9%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 23        | 31     | 85.19%  |
| NVMe | 3         | 4      | 11.11%  |
| SAS  | 1         | 1      | 3.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 18        | 21     | 75%     |
| 0.51-1.0   | 6         | 9      | 25%     |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 11        | 40.74%  |
| 251-500    | 10        | 37.04%  |
| 21-50      | 2         | 7.41%   |
| 501-1000   | 2         | 7.41%   |
| 51-100     | 2         | 7.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 12        | 44.44%  |
| 21-50   | 7         | 25.93%  |
| 51-100  | 4         | 14.81%  |
| 101-250 | 3         | 11.11%  |
| 251-500 | 1         | 3.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                        | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD5000LPCX-60VHAT0 500GB | 1         | 1      | 50%     |
| Seagate ST9120822AS 120GB    | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 2      | 100%    |

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
| Detected | 16        | 23     | 59.26%  |
| Works    | 9         | 11     | 33.33%  |
| Malfunc  | 2         | 2      | 7.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 20        | 71.43%  |
| AMD                 | 4         | 14.29%  |
| SK hynix            | 1         | 3.57%   |
| Silicon Motion      | 1         | 3.57%   |
| Samsung Electronics | 1         | 3.57%   |
| Phison Electronics  | 1         | 3.57%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 13.79%  |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 10.34%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 3         | 10.34%  |
| AMD FCH SATA Controller [AHCI mode]                                              | 3         | 10.34%  |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 6.9%    |
| SK hynix BC511                                                                   | 1         | 3.45%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 3.45%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 3.45%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 3.45%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 3.45%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 3.45%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 3.45%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 3.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 3.45%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 3.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 3.45%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 1         | 3.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 3.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 23        | 82.14%  |
| NVMe | 3         | 10.71%  |
| RAID | 1         | 3.57%   |
| IDE  | 1         | 3.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 21        | 80.77%  |
| AMD    | 5         | 19.23%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel Core i3 CPU M 370 @ 2.40GHz            | 2         | 7.69%   |
| Intel Pentium CPU B960 @ 2.20GHz             | 1         | 3.85%   |
| Intel Pentium CPU B950 @ 2.10GHz             | 1         | 3.85%   |
| Intel Core i7-8750H CPU @ 2.20GHz            | 1         | 3.85%   |
| Intel Core i7-8565U CPU @ 1.80GHz            | 1         | 3.85%   |
| Intel Core i7-5500U CPU @ 2.40GHz            | 1         | 3.85%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz           | 1         | 3.85%   |
| Intel Core i7-3630QM CPU @ 2.40GHz           | 1         | 3.85%   |
| Intel Core i5-8250U CPU @ 1.60GHz            | 1         | 3.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz            | 1         | 3.85%   |
| Intel Core i5-5200U CPU @ 2.20GHz            | 1         | 3.85%   |
| Intel Core i5-3230M CPU @ 2.60GHz            | 1         | 3.85%   |
| Intel Core i3-6006U CPU @ 2.00GHz            | 1         | 3.85%   |
| Intel Core i3-5005U CPU @ 2.00GHz            | 1         | 3.85%   |
| Intel Core i3-4005U CPU @ 1.70GHz            | 1         | 3.85%   |
| Intel Core i3-3227U CPU @ 1.90GHz            | 1         | 3.85%   |
| Intel Core 2 CPU T5600 @ 1.83GHz             | 1         | 3.85%   |
| Intel Celeron CPU N3050 @ 1.60GHz            | 1         | 3.85%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz      | 1         | 3.85%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz      | 1         | 3.85%   |
| AMD Ryzen 5 5500U with Radeon Graphics       | 1         | 3.85%   |
| AMD C-50 Processor                           | 1         | 3.85%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G | 1         | 3.85%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G | 1         | 3.85%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics  | 1         | 3.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Intel Core i3 | 6         | 23.08%  |
| Intel Core i7 | 5         | 19.23%  |
| Other         | 4         | 15.38%  |
| Intel Core i5 | 4         | 15.38%  |
| Intel Pentium | 2         | 7.69%   |
| Intel Core 2  | 1         | 3.85%   |
| Intel Celeron | 1         | 3.85%   |
| AMD Ryzen 5   | 1         | 3.85%   |
| AMD C-50      | 1         | 3.85%   |
| AMD A8        | 1         | 3.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 18        | 69.23%  |
| 4      | 6         | 23.08%  |
| 6      | 2         | 7.69%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 26        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 18        | 69.23%  |
| 1      | 8         | 30.77%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 26        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 16        | 61.54%  |
| 0x906ea    | 1         | 3.85%   |
| 0x806c1    | 1         | 3.85%   |
| 0x6f6      | 1         | 3.85%   |
| 0x406e3    | 1         | 3.85%   |
| 0x306d4    | 1         | 3.85%   |
| 0x306a9    | 1         | 3.85%   |
| 0x08608102 | 1         | 3.85%   |
| 0x07030105 | 1         | 3.85%   |
| 0x06006705 | 1         | 3.85%   |
| 0x05000029 | 1         | 3.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 4         | 15.38%  |
| IvyBridge   | 3         | 11.54%  |
| Broadwell   | 3         | 11.54%  |
| Westmere    | 2         | 7.69%   |
| TigerLake   | 2         | 7.69%   |
| SandyBridge | 2         | 7.69%   |
| Haswell     | 2         | 7.69%   |
| Excavator   | 2         | 7.69%   |
| Skylake     | 1         | 3.85%   |
| Silvermont  | 1         | 3.85%   |
| Puma        | 1         | 3.85%   |
| Core        | 1         | 3.85%   |
| Bobcat      | 1         | 3.85%   |
| Unknown     | 1         | 3.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 20        | 60.61%  |
| AMD    | 8         | 24.24%  |
| Nvidia | 5         | 15.15%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 5500                                                                   | 3         | 8.11%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 8.11%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 5.41%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 5.41%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 5.41%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 5.41%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 2.7%    |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 2.7%    |
| Nvidia GF108M [GeForce GT 420M]                                                          | 1         | 2.7%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 2.7%    |
| Intel UHD Graphics 620                                                                   | 1         | 2.7%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 2.7%    |
| Intel Tiger Lake UHD Graphics                                                            | 1         | 2.7%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 2.7%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 2.7%    |
| Intel HD Graphics 620                                                                    | 1         | 2.7%    |
| Intel HD Graphics 520                                                                    | 1         | 2.7%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 2.7%    |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 2.7%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 2.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.7%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 2.7%    |
| AMD Wrestler [Radeon HD 6250]                                                            | 1         | 2.7%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 2.7%    |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 2.7%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 2.7%    |
| AMD Mars XTX [Radeon HD 8790M]                                                           | 1         | 2.7%    |
| AMD Lucienne                                                                             | 1         | 2.7%    |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 1         | 2.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 13        | 50%     |
| Intel + Nvidia | 4         | 15.38%  |
| 2 x AMD        | 3         | 11.54%  |
| Intel + AMD    | 3         | 11.54%  |
| 1 x AMD        | 2         | 7.69%   |
| 1 x Nvidia     | 1         | 3.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver | Notebooks | Percent |
|--------|-----------|---------|
| Free   | 26        | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 80.77%  |
| 0.01-0.5   | 4         | 15.38%  |
| 5.01-6.0   | 1         | 3.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 5         | 20%     |
| LG Display              | 4         | 16%     |
| BOE                     | 4         | 16%     |
| AU Optronics            | 4         | 16%     |
| Samsung Electronics     | 3         | 12%     |
| LG Philips              | 1         | 4%      |
| Lenovo                  | 1         | 4%      |
| Goldstar                | 1         | 4%      |
| Chi Mei Optoelectronics | 1         | 4%      |
| AOC                     | 1         | 4%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch     | 1         | 3.85%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 1         | 3.85%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 1         | 3.85%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch     | 1         | 3.85%   |
| LG Philips LCD Monitor LPL1146 1280x800 331x207mm 15.4-inch              | 1         | 3.85%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 1         | 3.85%   |
| LG Display LCD Monitor LGD0470 1920x1080 345x194mm 15.6-inch             | 1         | 3.85%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch              | 1         | 3.85%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch              | 1         | 3.85%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 1         | 3.85%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                   | 1         | 3.85%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 3.85%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 1         | 3.85%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x193mm 15.5-inch          | 1         | 3.85%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 1         | 3.85%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 1         | 3.85%   |
| Chi Mei Optoelectronics LCD Monitor CMO15AB 1366x768 340x190mm 15.3-inch | 1         | 3.85%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 1         | 3.85%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 1         | 3.85%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 1         | 3.85%   |
| BOE LCD Monitor BOE065E 1920x1080 344x194mm 15.5-inch                    | 1         | 3.85%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 1         | 3.85%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 1         | 3.85%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch           | 1         | 3.85%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 1         | 3.85%   |
| AOC 2260W AOC2260 1920x1080 477x268mm 21.5-inch                          | 1         | 3.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 13        | 52%     |
| 1920x1080 (FHD)  | 8         | 32%     |
| 2160x1440        | 1         | 4%      |
| 1600x900 (HD+)   | 1         | 4%      |
| 1280x800 (WXGA)  | 1         | 4%      |
| 1280x1024 (SXGA) | 1         | 4%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 18        | 69.23%  |
| 14     | 3         | 11.54%  |
| 13     | 2         | 7.69%   |
| 23     | 1         | 3.85%   |
| 22     | 1         | 3.85%   |
| 17     | 1         | 3.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 22        | 88%     |
| 501-600     | 1         | 4%      |
| 401-500     | 1         | 4%      |
| 201-300     | 1         | 4%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 22        | 84.62%  |
| 16/10 | 2         | 7.69%   |
| 5/4   | 1         | 3.85%   |
| 3/2   | 1         | 3.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 18        | 69.23%  |
| 81-90          | 5         | 19.23%  |
| 201-250        | 2         | 7.69%   |
| 141-150        | 1         | 3.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 12        | 46.15%  |
| 121-160 | 8         | 30.77%  |
| 51-100  | 5         | 19.23%  |
| 161-240 | 1         | 3.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 24        | 92.31%  |
| 2     | 2         | 7.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 20        | 47.62%  |
| Intel                 | 10        | 23.81%  |
| Qualcomm Atheros      | 3         | 7.14%   |
| Broadcom              | 3         | 7.14%   |
| Ralink                | 2         | 4.76%   |
| ASUSTek Computer      | 2         | 4.76%   |
| Xiaomi                | 1         | 2.38%   |
| JMicron Technology    | 1         | 2.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 24.07%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 9.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 3.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 3.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 3.7%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.85%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.85%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 1.85%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 1.85%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.85%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.85%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 1.85%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1         | 1.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.85%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.85%   |
| Intel Wireless 8265 / 8275                                        | 1         | 1.85%   |
| Intel Wireless 7265                                               | 1         | 1.85%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.85%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 1.85%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.85%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 1.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 1.85%   |
| Intel Centrino Wireless-N 2230                                    | 1         | 1.85%   |
| Intel Centrino Wireless-N 130                                     | 1         | 1.85%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 1.85%   |
| Intel Centrino Advanced-N 6200                                    | 1         | 1.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 1.85%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 1.85%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.85%   |
| Broadcom BCM43225 802.11b/g/n                                     | 1         | 1.85%   |
| Broadcom BCM43142 802.11b/g/n                                     | 1         | 1.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 1         | 1.85%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                               | 1         | 1.85%   |
| ASUS 802.11ac NIC                                                 | 1         | 1.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 10        | 35.71%  |
| Realtek Semiconductor | 8         | 28.57%  |
| Qualcomm Atheros      | 3         | 10.71%  |
| Broadcom              | 3         | 10.71%  |
| Ralink                | 2         | 7.14%   |
| ASUSTek Computer      | 2         | 7.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 2         | 7.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 2         | 7.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 2         | 7.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 3.57%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter   | 1         | 3.57%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter            | 1         | 3.57%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 1         | 3.57%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                  | 1         | 3.57%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                  | 1         | 3.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1         | 3.57%   |
| Intel Wireless 8265 / 8275                                 | 1         | 3.57%   |
| Intel Wireless 7265                                        | 1         | 3.57%   |
| Intel Wi-Fi 6 AX201                                        | 1         | 3.57%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection      | 1         | 3.57%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth            | 1         | 3.57%   |
| Intel Centrino Wireless-N 2230                             | 1         | 3.57%   |
| Intel Centrino Wireless-N 130                              | 1         | 3.57%   |
| Intel Centrino Ultimate-N 6300                             | 1         | 3.57%   |
| Intel Centrino Advanced-N 6200                             | 1         | 3.57%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 1         | 3.57%   |
| Broadcom BCM43225 802.11b/g/n                              | 1         | 3.57%   |
| Broadcom BCM43142 802.11b/g/n                              | 1         | 3.57%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter        | 1         | 3.57%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                        | 1         | 3.57%   |
| ASUS 802.11ac NIC                                          | 1         | 3.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 19        | 76%     |
| Intel                 | 3         | 12%     |
| Xiaomi                | 1         | 4%      |
| JMicron Technology    | 1         | 4%      |
| Broadcom              | 1         | 4%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 50%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 19.23%  |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 3.85%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 3.85%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 3.85%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 3.85%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 3.85%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 3.85%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 3.85%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 3.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 26        | 52%     |
| Ethernet | 24        | 48%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 22        | 78.57%  |
| Ethernet | 6         | 21.43%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 24        | 92.31%  |
| 1     | 2         | 7.69%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 26        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 7         | 33.33%  |
| Realtek Semiconductor           | 5         | 23.81%  |
| Toshiba                         | 2         | 9.52%   |
| Realtek                         | 1         | 4.76%   |
| Ralink                          | 1         | 4.76%   |
| Qualcomm Atheros Communications | 1         | 4.76%   |
| Lite-On Technology              | 1         | 4.76%   |
| IMC Networks                    | 1         | 4.76%   |
| Foxconn / Hon Hai               | 1         | 4.76%   |
| Broadcom                        | 1         | 4.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                          | 5         | 23.81%  |
| Intel Bluetooth wireless interface               | 3         | 14.29%  |
| Toshiba RT Bluetooth Radio                       | 1         | 4.76%   |
| Toshiba Integrated Bluetooth HCI                 | 1         | 4.76%   |
| Realtek Bluetooth Radio                          | 1         | 4.76%   |
| Ralink RT3290 Bluetooth                          | 1         | 4.76%   |
| Qualcomm Atheros  Bluetooth Device               | 1         | 4.76%   |
| Lite-On Atheros AR3012 Bluetooth                 | 1         | 4.76%   |
| Intel Centrino Bluetooth Wireless Transceiver    | 1         | 4.76%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 1         | 4.76%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 1         | 4.76%   |
| Intel AX201 Bluetooth                            | 1         | 4.76%   |
| IMC Networks Bluetooth Device                    | 1         | 4.76%   |
| Foxconn / Hon Hai BCM43142A0                     | 1         | 4.76%   |
| Broadcom HP Portable Valentine                   | 1         | 4.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 21        | 75%     |
| AMD                   | 5         | 17.86%  |
| Nvidia                | 1         | 3.57%   |
| Barco Display Systems | 1         | 3.57%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 10.81%  |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 8.11%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 8.11%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 8.11%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 5.41%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 5.41%   |
| AMD High Definition Audio Controller                                                              | 2         | 5.41%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 5.41%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 2.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 2.7%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 2.7%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 2.7%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 2.7%    |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 2.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.7%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 2.7%    |
| Intel 8 Series HD Audio Controller                                                                | 1         | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 2.7%    |
| Barco Display Systems USBGH520-ENC                                                                | 1         | 2.7%    |
| AMD Wrestler HDMI Audio                                                                           | 1         | 2.7%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 2.7%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 2.7%    |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 2.7%    |
| AMD FCH Azalia Controller                                                                         | 1         | 2.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 4         | 36.36%  |
| SK hynix            | 2         | 18.18%  |
| Unknown (0x4509)    | 1         | 9.09%   |
| Unknown             | 1         | 9.09%   |
| Micron Technology   | 1         | 9.09%   |
| Kingston            | 1         | 9.09%   |
| Kingmax             | 1         | 9.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR2                              | 1         | 9.09%   |
| Unknown (0x4509) RAM GKE800SO102408-2666A 8GB SODIMM DDR4 2133MT/s | 1         | 9.09%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s       | 1         | 9.09%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s          | 1         | 9.09%   |
| Samsung RAM M471B5773CHS-CH9 2GB DIMM DDR3 1333MT/s                | 1         | 9.09%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s              | 1         | 9.09%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s              | 1         | 9.09%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s           | 1         | 9.09%   |
| Micron RAM 8KTF51264HDZ-1G6E1 4GB SODIMM DDR3 1600MT/s             | 1         | 9.09%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s            | 1         | 9.09%   |
| Kingmax RAM FSFE85F-C8KL9 2GB DIMM DDR3 1333MT/s                   | 1         | 9.09%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Notebooks | Percent |
|-------|-----------|---------|
| DDR4  | 6         | 54.55%  |
| DDR3  | 3         | 27.27%  |
| SDRAM | 1         | 9.09%   |
| DDR2  | 1         | 9.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 8         | 80%     |
| Row Of Chips | 1         | 10%     |
| DIMM         | 1         | 10%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 8192 | 5         | 50%     |
| 4096 | 3         | 30%     |
| 2048 | 2         | 20%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 3         | 30%     |
| 2667    | 2         | 20%     |
| 1600    | 2         | 20%     |
| 2133    | 1         | 10%     |
| 1333    | 1         | 10%     |
| Unknown | 1         | 10%     |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Canon LBP6030w/6018w | 1         | 100%    |

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
| Chicony Electronics                    | 8         | 34.78%  |
| IMC Networks                           | 3         | 13.04%  |
| Microdia                               | 2         | 8.7%    |
| Luxvisions Innotech Limited            | 2         | 8.7%    |
| Suyin                                  | 1         | 4.35%   |
| Silicon Motion                         | 1         | 4.35%   |
| Realtek Semiconductor                  | 1         | 4.35%   |
| Lite-On Technology                     | 1         | 4.35%   |
| Foxconn / Hon Hai                      | 1         | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 4.35%   |
| ALi                                    | 1         | 4.35%   |
| Acer                                   | 1         | 4.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony EasyCamera                                  | 2         | 8.7%    |
| Suyin HP Webcam                                     | 1         | 4.35%   |
| Silicon Motion WebCam SC-0311139N                   | 1         | 4.35%   |
| Realtek HP Truevision HD integrated webcam          | 1         | 4.35%   |
| Microdia Laptop_Integrated_Webcam_HD                | 1         | 4.35%   |
| Microdia Integrated_Webcam_HD                       | 1         | 4.35%   |
| Luxvisions Innotech Limited Integrated Camera       | 1         | 4.35%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 4.35%   |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 4.35%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 4.35%   |
| IMC Networks Lenovo EasyCamera                      | 1         | 4.35%   |
| IMC Networks EasyCamera                             | 1         | 4.35%   |
| Foxconn / Hon Hai USB2.0 Camera                     | 1         | 4.35%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 4.35%   |
| Chicony USB2.0 Camera                               | 1         | 4.35%   |
| Chicony Integrated Camera                           | 1         | 4.35%   |
| Chicony HP Truevision HD                            | 1         | 4.35%   |
| Chicony Front Camera                                | 1         | 4.35%   |
| Chicony CNA7157                                     | 1         | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 1         | 4.35%   |
| ALi Gateway Webcam                                  | 1         | 4.35%   |
| Acer EasyCamera                                     | 1         | 4.35%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 1         | 33.33%  |
| Shenzhen Goodix Technology | 1         | 33.33%  |
| AuthenTec                  | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor | 1         | 33.33%  |
| Shenzhen Goodix  Fingerprint Device          | 1         | 33.33%  |
| AuthenTec AES1600                            | 1         | 33.33%  |

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


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 19        | 70.37%  |
| 1     | 6         | 22.22%  |
| 2     | 2         | 7.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Graphics card      | 3         | 30%     |
| Fingerprint reader | 3         | 30%     |
| Net/wireless       | 1         | 10%     |
| Chipcard           | 1         | 10%     |
| Camera             | 1         | 10%     |
| Bluetooth          | 1         | 10%     |

