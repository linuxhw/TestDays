Pardus - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Pardus.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Pardus/Desktop/README.md) and [notebooks](/Dist/Pardus/Notebook/README.md).

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

Total: 43

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [0d897cd79c](https://linux-hardware.org/?probe=0d897cd79c) | Apr 15, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [b3cef97540](https://linux-hardware.org/?probe=b3cef97540) | Apr 12, 2022 |
| MSI           | MS-7360                     | Desktop     | [34c10f0508](https://linux-hardware.org/?probe=34c10f0508) | Apr 10, 2022 |
| MSI           | H81M-P33                    | Desktop     | [2b0d95df2e](https://linux-hardware.org/?probe=2b0d95df2e) | Apr 02, 2022 |
| MSI           | MS-7360                     | Desktop     | [8efb24e401](https://linux-hardware.org/?probe=8efb24e401) | Mar 21, 2022 |
| MSI           | MS-7360                     | Desktop     | [99ac168204](https://linux-hardware.org/?probe=99ac168204) | Mar 18, 2022 |
| Sony          | SVE14A2V2ES                 | Notebook    | [b2695cc80d](https://linux-hardware.org/?probe=b2695cc80d) | Mar 13, 2022 |
| Sony          | SVE14A2V2ES                 | Notebook    | [4b2203862a](https://linux-hardware.org/?probe=4b2203862a) | Mar 11, 2022 |
| Sony          | SVE14A2V2ES                 | Notebook    | [1575f2f0be](https://linux-hardware.org/?probe=1575f2f0be) | Mar 11, 2022 |
| Sony          | SVE14A2V2ES                 | Notebook    | [ef603529f2](https://linux-hardware.org/?probe=ef603529f2) | Mar 08, 2022 |
| Sony          | SVE14A2V2ES                 | Notebook    | [35fe0c18bc](https://linux-hardware.org/?probe=35fe0c18bc) | Mar 07, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [e60367127e](https://linux-hardware.org/?probe=e60367127e) | Mar 07, 2022 |
| Sony          | SVF1521QSTB                 | Notebook    | [f74068fef9](https://linux-hardware.org/?probe=f74068fef9) | Feb 14, 2022 |
| HP            | Pavilion 15                 | Notebook    | [fe001e576b](https://linux-hardware.org/?probe=fe001e576b) | Feb 13, 2022 |
| Packard Be... | EasyNote ENTG81BA           | Notebook    | [10f68b4c82](https://linux-hardware.org/?probe=10f68b4c82) | Jan 31, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [fcde789242](https://linux-hardware.org/?probe=fcde789242) | Jan 24, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [dd92029684](https://linux-hardware.org/?probe=dd92029684) | Jan 21, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [121a750c5b](https://linux-hardware.org/?probe=121a750c5b) | Jan 03, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | Notebook    | [16efe9685d](https://linux-hardware.org/?probe=16efe9685d) | Dec 17, 2021 |
| Toshiba       | PORTEGE M780                | Notebook    | [c68379ab38](https://linux-hardware.org/?probe=c68379ab38) | Nov 30, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [1cf8a783be](https://linux-hardware.org/?probe=1cf8a783be) | Oct 21, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [20a54c9779](https://linux-hardware.org/?probe=20a54c9779) | Oct 21, 2021 |
| Lenovo        | 3132 NOK                    | Desktop     | [9d1ef122f7](https://linux-hardware.org/?probe=9d1ef122f7) | Oct 11, 2021 |
| Lenovo        | 3132 NOK                    | Desktop     | [5802651f49](https://linux-hardware.org/?probe=5802651f49) | Sep 15, 2021 |
| Lenovo        | IdeaPad-510-15IKB 80SV      | Notebook    | [1a343f3596](https://linux-hardware.org/?probe=1a343f3596) | Sep 02, 2021 |
| Philco        | 14F                         | Notebook    | [343861b100](https://linux-hardware.org/?probe=343861b100) | Jun 20, 2021 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [9149be671f](https://linux-hardware.org/?probe=9149be671f) | Jan 30, 2021 |
| Toshiba       | Satellite C855-1VM          | Notebook    | [dab32c2669](https://linux-hardware.org/?probe=dab32c2669) | Jan 24, 2021 |
| Lenovo        | ThinkPad T450 20BUS39Y00    | Notebook    | [579099bf91](https://linux-hardware.org/?probe=579099bf91) | Dec 26, 2020 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [39f1d96886](https://linux-hardware.org/?probe=39f1d96886) | Dec 16, 2020 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [33cdf15439](https://linux-hardware.org/?probe=33cdf15439) | Dec 15, 2020 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [6cd7c2a8a6](https://linux-hardware.org/?probe=6cd7c2a8a6) | Dec 11, 2020 |
| ASUSTek       | X555YI                      | Notebook    | [d210c4b901](https://linux-hardware.org/?probe=d210c4b901) | Sep 26, 2020 |
| Packard Be... | EasyNote_GN45               | Notebook    | [210b740311](https://linux-hardware.org/?probe=210b740311) | Sep 24, 2020 |
| Dell          | Latitude E6540              | Notebook    | [d2337e32c1](https://linux-hardware.org/?probe=d2337e32c1) | Sep 05, 2020 |
| ASUSTek       | V230IC-DDR4                 | All in one  | [c410333e82](https://linux-hardware.org/?probe=c410333e82) | Jun 11, 2020 |
| ASUSTek       | E402BP                      | Notebook    | [d531d0fe45](https://linux-hardware.org/?probe=d531d0fe45) | Jun 01, 2020 |
| HP            | 15                          | Notebook    | [36d90829ee](https://linux-hardware.org/?probe=36d90829ee) | May 02, 2020 |
| HP            | 15                          | Notebook    | [06393a1175](https://linux-hardware.org/?probe=06393a1175) | Apr 27, 2020 |
| HP            | 15                          | Notebook    | [e21973794b](https://linux-hardware.org/?probe=e21973794b) | Feb 02, 2020 |
| Dell          | G5 5587                     | Notebook    | [1742540bc9](https://linux-hardware.org/?probe=1742540bc9) | Nov 27, 2019 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [dd8de8c9a2](https://linux-hardware.org/?probe=dd8de8c9a2) | Oct 18, 2019 |
| HP            | 250 G3                      | Notebook    | [e82ead9af0](https://linux-hardware.org/?probe=e82ead9af0) | Oct 13, 2019 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Pardus 21.1   | 6         | 17.65%  |
| Pardus 21.2   | 4         | 11.76%  |
| Pardus 21.0   | 4         | 11.76%  |
| Pardus 19.5   | 4         | 11.76%  |
| Pardus 19.4-1 | 3         | 8.82%   |
| Pardus 19.4   | 3         | 8.82%   |
| Pardus 19.3   | 3         | 8.82%   |
| Pardus 19.2   | 3         | 8.82%   |
| Pardus 19.1   | 2         | 5.88%   |
| Pardus 19.0   | 2         | 5.88%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Pardus | 33        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 5.10.0-13-amd64      | 4         | 11.76%  |
| 5.10.0-11-amd64      | 3         | 8.82%   |
| 4.19.0-6-amd64       | 3         | 8.82%   |
| 4.19.0-13-amd64      | 3         | 8.82%   |
| 4.19.0-10-amd64      | 3         | 8.82%   |
| 5.9.0-0.bpo.2-amd64  | 2         | 5.88%   |
| 5.10.0-9-amd64       | 2         | 5.88%   |
| 5.10.0-8-amd64       | 2         | 5.88%   |
| 5.10.0-10-amd64      | 2         | 5.88%   |
| 4.19.0-8-amd64       | 2         | 5.88%   |
| 5.4.0-0.bpo.3-amd64  | 1         | 2.94%   |
| 5.10.0-12-amd64      | 1         | 2.94%   |
| 5.10.0-0.bpo.8-amd64 | 1         | 2.94%   |
| 4.19.0-5-amd64       | 1         | 2.94%   |
| 4.19.0-19-amd64      | 1         | 2.94%   |
| 4.19.0-18-amd64      | 1         | 2.94%   |
| 4.19.0-16-amd64      | 1         | 2.94%   |
| 4.19.0-12-amd64      | 1         | 2.94%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 15        | 45.45%  |
| 4.19.0  | 15        | 45.45%  |
| 5.9.0   | 2         | 6.06%   |
| 5.4.0   | 1         | 3.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 15        | 45.45%  |
| 4.19    | 15        | 45.45%  |
| 5.9     | 2         | 6.06%   |
| 5.4     | 1         | 3.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 33        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| XFCE    | 23        | 69.7%   |
| GNOME   | 7         | 21.21%  |
| Unknown | 2         | 6.06%   |
| KDE5    | 1         | 3.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 33        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 22        | 66.67%  |
| TDM     | 6         | 18.18%  |
| LightDM | 3         | 9.09%   |
| GDM     | 2         | 6.06%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| tr_TR   | 26        | 78.79%  |
| Unknown | 3         | 9.09%   |
| pt_BR   | 1         | 3.03%   |
| fr_FR   | 1         | 3.03%   |
| en_US   | 1         | 3.03%   |
| en_GB   | 1         | 3.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 26        | 78.79%  |
| EFI  | 7         | 21.21%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ext4 | 33        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 24        | 72.73%  |
| GPT     | 7         | 21.21%  |
| MBR     | 2         | 6.06%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 32        | 96.97%  |
| Yes       | 1         | 3.03%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 28        | 84.85%  |
| Yes       | 5         | 15.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 8         | 24.24%  |
| MSI                 | 4         | 12.12%  |
| Hewlett-Packard     | 4         | 12.12%  |
| ASUSTek Computer    | 4         | 12.12%  |
| Toshiba             | 2         | 6.06%   |
| Sony                | 2         | 6.06%   |
| Packard Bell        | 2         | 6.06%   |
| Gigabyte Technology | 2         | 6.06%   |
| Dell                | 2         | 6.06%   |
| Samsung Electronics | 1         | 3.03%   |
| Philco              | 1         | 3.03%   |
| Acer                | 1         | 3.03%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| MSI MS-7360                                | 2         | 6.06%   |
| Toshiba Satellite C855-1VM                 | 1         | 3.03%   |
| Toshiba PORTEGE M780                       | 1         | 3.03%   |
| Sony SVF1521QSTB                           | 1         | 3.03%   |
| Sony SVE14A2V2ES                           | 1         | 3.03%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 3.03%   |
| Philco 14F                                 | 1         | 3.03%   |
| Packard Bell EasyNote_GN45                 | 1         | 3.03%   |
| Packard Bell EasyNote ENTG81BA             | 1         | 3.03%   |
| MSI MS-7C09                                | 1         | 3.03%   |
| MSI MS-7817                                | 1         | 3.03%   |
| Lenovo Yoga 310-11IAP 80U2                 | 1         | 3.03%   |
| Lenovo V145-15AST 81MT                     | 1         | 3.03%   |
| Lenovo V110-15ISK 80TL                     | 1         | 3.03%   |
| Lenovo ThinkPad T450 20BUS39Y00            | 1         | 3.03%   |
| Lenovo ThinkPad E15 Gen 2 20TD0047TX       | 1         | 3.03%   |
| Lenovo ThinkCentre M920t 10SGS62900        | 1         | 3.03%   |
| Lenovo IdeaPad-510-15IKB 80SV              | 1         | 3.03%   |
| Lenovo IdeaPad 320-15IKB 81BT              | 1         | 3.03%   |
| HP Pavilion 15                             | 1         | 3.03%   |
| HP Laptop 15-dw3xxx                        | 1         | 3.03%   |
| HP 250 G3                                  | 1         | 3.03%   |
| HP 15                                      | 1         | 3.03%   |
| Gigabyte A320M-S2H                         | 1         | 3.03%   |
| Gigabyte A320M-H                           | 1         | 3.03%   |
| Dell Latitude E6540                        | 1         | 3.03%   |
| Dell G5 5587                               | 1         | 3.03%   |
| ASUS X555YI                                | 1         | 3.03%   |
| ASUS V230IC-DDR4                           | 1         | 3.03%   |
| ASUS P5G41C-M LX                           | 1         | 3.03%   |
| ASUS E402BP                                | 1         | 3.03%   |
| Acer Aspire 5742G                          | 1         | 3.03%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Packard Bell EasyNote    | 2         | 6.06%   |
| MSI MS-7360              | 2         | 6.06%   |
| Lenovo ThinkPad          | 2         | 6.06%   |
| Toshiba Satellite        | 1         | 3.03%   |
| Toshiba PORTEGE          | 1         | 3.03%   |
| Sony SVF1521QSTB         | 1         | 3.03%   |
| Sony SVE14A2V2ES         | 1         | 3.03%   |
| Samsung 300E4A           | 1         | 3.03%   |
| Philco 14F               | 1         | 3.03%   |
| MSI MS-7C09              | 1         | 3.03%   |
| MSI MS-7817              | 1         | 3.03%   |
| Lenovo Yoga              | 1         | 3.03%   |
| Lenovo V145-15AST        | 1         | 3.03%   |
| Lenovo V110-15ISK        | 1         | 3.03%   |
| Lenovo ThinkCentre       | 1         | 3.03%   |
| Lenovo IdeaPad-510-15IKB | 1         | 3.03%   |
| Lenovo IdeaPad           | 1         | 3.03%   |
| HP Pavilion              | 1         | 3.03%   |
| HP Laptop                | 1         | 3.03%   |
| HP 250                   | 1         | 3.03%   |
| HP 15                    | 1         | 3.03%   |
| Gigabyte A320M-S2H       | 1         | 3.03%   |
| Gigabyte A320M-H         | 1         | 3.03%   |
| Dell Latitude            | 1         | 3.03%   |
| Dell G5                  | 1         | 3.03%   |
| ASUS X555YI              | 1         | 3.03%   |
| ASUS V230IC-DDR4         | 1         | 3.03%   |
| ASUS P5G41C-M            | 1         | 3.03%   |
| ASUS E402BP              | 1         | 3.03%   |
| Acer Aspire              | 1         | 3.03%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2013 | 7         | 21.21%  |
| 2018 | 6         | 18.18%  |
| 2015 | 3         | 9.09%   |
| 2010 | 3         | 9.09%   |
| 2020 | 2         | 6.06%   |
| 2017 | 2         | 6.06%   |
| 2016 | 2         | 6.06%   |
| 2011 | 2         | 6.06%   |
| 2007 | 2         | 6.06%   |
| 2021 | 1         | 3.03%   |
| 2019 | 1         | 3.03%   |
| 2014 | 1         | 3.03%   |
| 2006 | 1         | 3.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 23        | 69.7%   |
| Desktop     | 8         | 24.24%  |
| Convertible | 1         | 3.03%   |
| All in one  | 1         | 3.03%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 33        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 33        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 13        | 39.39%  |
| 4.01-8.0   | 9         | 27.27%  |
| 16.01-24.0 | 4         | 12.12%  |
| 8.01-16.0  | 3         | 9.09%   |
| 1.01-2.0   | 2         | 6.06%   |
| 32.01-64.0 | 1         | 3.03%   |
| 2.01-3.0   | 1         | 3.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 15        | 44.12%  |
| 2.01-3.0   | 8         | 23.53%  |
| 3.01-4.0   | 6         | 17.65%  |
| 4.01-8.0   | 2         | 5.88%   |
| 24.01-32.0 | 1         | 2.94%   |
| 8.01-16.0  | 1         | 2.94%   |
| 0.51-1.0   | 1         | 2.94%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 23        | 69.7%   |
| 2      | 8         | 24.24%  |
| 4      | 1         | 3.03%   |
| 3      | 1         | 3.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 19        | 57.58%  |
| No        | 14        | 42.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 96.97%  |
| No        | 1         | 3.03%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 78.79%  |
| No        | 7         | 21.21%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 66.67%  |
| No        | 11        | 33.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Turkey  | 30        | 90.91%  |
| UK      | 1         | 3.03%   |
| France  | 1         | 3.03%   |
| Brazil  | 1         | 3.03%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Istanbul      | 9         | 26.47%  |
| Bursa         | 6         | 17.65%  |
| Izmir         | 3         | 8.82%   |
| Ankara        | 3         | 8.82%   |
| Aydin         | 2         | 5.88%   |
| Г‡anakkale | 1         | 2.94%   |
| Soleymieu     | 1         | 2.94%   |
| Porto Alegre  | 1         | 2.94%   |
| Mersin        | 1         | 2.94%   |
| Malatya       | 1         | 2.94%   |
| London        | 1         | 2.94%   |
| Kosekoy       | 1         | 2.94%   |
| Konya         | 1         | 2.94%   |
| Gaziantep     | 1         | 2.94%   |
| Artvin        | 1         | 2.94%   |
| Antalya       | 1         | 2.94%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 11     | 20.45%  |
| Seagate             | 7         | 8      | 15.91%  |
| Samsung Electronics | 7         | 9      | 15.91%  |
| SK Hynix            | 2         | 2      | 4.55%   |
| Kingston            | 2         | 2      | 4.55%   |
| HGST                | 2         | 2      | 4.55%   |
| A-DATA Technology   | 2         | 2      | 4.55%   |
| Unknown             | 1         | 1      | 2.27%   |
| Toshiba             | 1         | 1      | 2.27%   |
| Team                | 1         | 1      | 2.27%   |
| SPCC                | 1         | 1      | 2.27%   |
| Silicon Motion      | 1         | 1      | 2.27%   |
| SanDisk             | 1         | 1      | 2.27%   |
| Micron Technology   | 1         | 1      | 2.27%   |
| Lexar               | 1         | 1      | 2.27%   |
| KingSpec            | 1         | 1      | 2.27%   |
| Hitachi             | 1         | 1      | 2.27%   |
| Corsair             | 1         | 1      | 2.27%   |
| China               | 1         | 1      | 2.27%   |
| addlink             | 1         | 1      | 2.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| WDC WD6402AAEX-00Y9A0 640GB                 | 2         | 4.44%   |
| HGST HTS545050A7E680 500GB                  | 2         | 4.44%   |
| A-DATA SU650 120GB SSD                      | 2         | 4.44%   |
| WDC WD5000LPVX-55V0TT0 500GB                | 1         | 2.22%   |
| WDC WD5000LPCX-21VHAT0 500GB                | 1         | 2.22%   |
| WDC WD5000AAKX-00ERMA0 500GB                | 1         | 2.22%   |
| WDC WD3200BPVT-35JJ5T0 320GB                | 1         | 2.22%   |
| WDC WD3200AAJB-00WGA0 320GB                 | 1         | 2.22%   |
| WDC WD10JPVX-60JC3T0 1TB                    | 1         | 2.22%   |
| WDC WD10JPCX-24UE4T0 1TB                    | 1         | 2.22%   |
| Unknown MMC Card  64GB                      | 1         | 2.22%   |
| Toshiba DT01ACA100 1TB                      | 1         | 2.22%   |
| Team T253X1240G 240GB SSD                   | 1         | 2.22%   |
| SPCC Solid State Disk 512GB                 | 1         | 2.22%   |
| SK Hynix SC311 SATA 256GB SSD               | 1         | 2.22%   |
| SK Hynix BC511 HFM256GDJTNI-82A0A 256GB     | 1         | 2.22%   |
| Silicon Motion Longline SSD 512GB           | 1         | 2.22%   |
| Seagate ST9500325AS 500GB                   | 1         | 2.22%   |
| Seagate ST9120822AS 120GB                   | 1         | 2.22%   |
| Seagate ST3160318AS 160GB                   | 1         | 2.22%   |
| Seagate ST2000DM008-2FR102 2TB              | 1         | 2.22%   |
| Seagate ST1000LM035-1RK172 1TB              | 1         | 2.22%   |
| Seagate Expansion+ 2TB                      | 1         | 2.22%   |
| Seagate BarraCuda Q1 SSD ZA480CV10001 480GB | 1         | 2.22%   |
| SanDisk SDSSDA480G 480GB                    | 1         | 2.22%   |
| Samsung SSD 860 EVO 500GB                   | 1         | 2.22%   |
| Samsung NVMe SSD Drive 512GB                | 1         | 2.22%   |
| Samsung MZALQ256HAJD-000L1 256GB            | 1         | 2.22%   |
| Samsung MZ7LN128HAHQ-000L2 128GB SSD        | 1         | 2.22%   |
| Samsung MZ7LF192HCGS-000L1 192GB SSD        | 1         | 2.22%   |
| Samsung HD501LJ 500GB                       | 1         | 2.22%   |
| Samsung HD160HJ 160GB                       | 1         | 2.22%   |
| Samsung HD103SJ 1TB                         | 1         | 2.22%   |
| Micron 1300_MTFDDAK512TDL 512GB SSD         | 1         | 2.22%   |
| Lexar 120GB SSD                             | 1         | 2.22%   |
| Kingston SHFS37A120G 120GB SSD              | 1         | 2.22%   |
| Kingston SA400S37240G 240GB SSD             | 1         | 2.22%   |
| KingSpec P3-128 128GB SSD                   | 1         | 2.22%   |
| Hitachi HTS545025B9A300 250GB               | 1         | 2.22%   |
| Corsair Force LS SSD 64GB                   | 1         | 2.22%   |
| China SATA SSD 120GB                        | 1         | 2.22%   |
| addlink S10 120GB                           | 1         | 2.22%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 11     | 42.86%  |
| Seagate             | 6         | 7      | 28.57%  |
| Samsung Electronics | 2         | 3      | 9.52%   |
| HGST                | 2         | 2      | 9.52%   |
| Toshiba             | 1         | 1      | 4.76%   |
| Hitachi             | 1         | 1      | 4.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 17.65%  |
| Kingston            | 2         | 2      | 11.76%  |
| A-DATA Technology   | 2         | 2      | 11.76%  |
| Team                | 1         | 1      | 5.88%   |
| SPCC                | 1         | 1      | 5.88%   |
| SK Hynix            | 1         | 1      | 5.88%   |
| Seagate             | 1         | 1      | 5.88%   |
| SanDisk             | 1         | 1      | 5.88%   |
| Micron Technology   | 1         | 1      | 5.88%   |
| Lexar               | 1         | 1      | 5.88%   |
| KingSpec            | 1         | 1      | 5.88%   |
| Corsair             | 1         | 1      | 5.88%   |
| China               | 1         | 1      | 5.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 19        | 25     | 48.72%  |
| SSD     | 15        | 17     | 38.46%  |
| NVMe    | 3         | 5      | 7.69%   |
| MMC     | 1         | 1      | 2.56%   |
| Unknown | 1         | 1      | 2.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 30        | 42     | 85.71%  |
| NVMe | 3         | 5      | 8.57%   |
| SAS  | 1         | 1      | 2.86%   |
| MMC  | 1         | 1      | 2.86%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 24        | 28     | 68.57%  |
| 0.51-1.0   | 9         | 11     | 25.71%  |
| 1.01-2.0   | 2         | 3      | 5.71%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 13        | 39.39%  |
| 251-500    | 10        | 30.3%   |
| 501-1000   | 4         | 12.12%  |
| 51-100     | 3         | 9.09%   |
| 21-50      | 2         | 6.06%   |
| 2001-3000  | 1         | 3.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 12        | 36.36%  |
| 21-50    | 9         | 27.27%  |
| 51-100   | 6         | 18.18%  |
| 101-250  | 4         | 12.12%  |
| 251-500  | 1         | 3.03%   |
| 501-1000 | 1         | 3.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST9120822AS 120GB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 24        | 38     | 72.73%  |
| Works    | 8         | 10     | 24.24%  |
| Malfunc  | 1         | 1      | 3.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 26        | 68.42%  |
| AMD                      | 6         | 15.79%  |
| Samsung Electronics      | 2         | 5.26%   |
| Marvell Technology Group | 2         | 5.26%   |
| SK Hynix                 | 1         | 2.63%   |
| Silicon Motion           | 1         | 2.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 5         | 11.36%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 9.09%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 3         | 6.82%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 4.55%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                            | 2         | 4.55%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 4.55%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                           | 2         | 4.55%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                     | 2         | 4.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 4.55%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 4.55%   |
| AMD FCH SATA Controller D                                                        | 2         | 4.55%   |
| SK Hynix BC511                                                                   | 1         | 2.27%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 2.27%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 2.27%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 1         | 2.27%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 2.27%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 2.27%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 2.27%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1         | 2.27%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 2.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 2.27%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 2.27%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 2.27%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 1         | 2.27%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 1         | 2.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 2.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 28        | 77.78%  |
| IDE  | 4         | 11.11%  |
| NVMe | 3         | 8.33%   |
| RAID | 1         | 2.78%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 27        | 81.82%  |
| AMD    | 6         | 18.18%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 6.06%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 2         | 6.06%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 3.03%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 1         | 3.03%   |
| Intel Core i9-9900 CPU @ 3.10GHz              | 1         | 3.03%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 3.03%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 3.03%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 1         | 3.03%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 3.03%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 3.03%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 3.03%   |
| Intel Core i5-6400T CPU @ 2.20GHz             | 1         | 3.03%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 3.03%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 1         | 3.03%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 3.03%   |
| Intel Core i3-9100F CPU @ 3.60GHz             | 1         | 3.03%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 3.03%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 1         | 3.03%   |
| Intel Core i3-3227U CPU @ 1.90GHz             | 1         | 3.03%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz         | 1         | 3.03%   |
| Intel Core 2 CPU T5600 @ 1.83GHz              | 1         | 3.03%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 1         | 3.03%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 1         | 3.03%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 3.03%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 3.03%   |
| AMD Ryzen 5 3500X 6-Core Processor            | 1         | 3.03%   |
| AMD C-50 Processor                            | 1         | 3.03%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 1         | 3.03%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G  | 1         | 3.03%   |
| AMD A8-9600 RADEON R7, 10 COMPUTE CORES 4C+6G | 1         | 3.03%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 1         | 3.03%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 6         | 18.18%  |
| Intel Core i3     | 6         | 18.18%  |
| Other             | 4         | 12.12%  |
| Intel Core i7     | 4         | 12.12%  |
| Intel Core 2 Quad | 3         | 9.09%   |
| Intel Pentium     | 2         | 6.06%   |
| Intel Celeron     | 2         | 6.06%   |
| AMD A8            | 2         | 6.06%   |
| Intel Core i9     | 1         | 3.03%   |
| Intel Core 2      | 1         | 3.03%   |
| AMD Ryzen 5       | 1         | 3.03%   |
| AMD C-50          | 1         | 3.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 19        | 57.58%  |
| 4      | 11        | 33.33%  |
| 6      | 2         | 6.06%   |
| 8      | 1         | 3.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 33        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 17        | 51.52%  |
| 1      | 16        | 48.48%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 33        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 66.67%  |
| 0x906eb    | 1         | 3.03%   |
| 0x906ea    | 1         | 3.03%   |
| 0x806c1    | 1         | 3.03%   |
| 0x6f6      | 1         | 3.03%   |
| 0x506e3    | 1         | 3.03%   |
| 0x406e3    | 1         | 3.03%   |
| 0x306c3    | 1         | 3.03%   |
| 0x306a9    | 1         | 3.03%   |
| 0x07030105 | 1         | 3.03%   |
| 0x06006705 | 1         | 3.03%   |
| 0x05000029 | 1         | 3.03%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 5         | 15.15%  |
| IvyBridge   | 3         | 9.09%   |
| Haswell     | 3         | 9.09%   |
| Excavator   | 3         | 9.09%   |
| Core        | 3         | 9.09%   |
| Westmere    | 2         | 6.06%   |
| TigerLake   | 2         | 6.06%   |
| Skylake     | 2         | 6.06%   |
| SandyBridge | 2         | 6.06%   |
| Broadwell   | 2         | 6.06%   |
| Zen 2       | 1         | 3.03%   |
| Silvermont  | 1         | 3.03%   |
| Puma        | 1         | 3.03%   |
| Penryn      | 1         | 3.03%   |
| Goldmont    | 1         | 3.03%   |
| Bobcat      | 1         | 3.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 22        | 52.38%  |
| Nvidia | 10        | 23.81%  |
| AMD    | 10        | 23.81%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 6.52%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 4.35%   |
| Nvidia GT200 [GeForce GTX 260]                                                           | 2         | 4.35%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 4.35%   |
| Intel HD Graphics 5500                                                                   | 2         | 4.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 4.35%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 4.35%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 4.35%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 2.17%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 2.17%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 2.17%   |
| Nvidia GF108M [GeForce GT 420M]                                                          | 1         | 2.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 2.17%   |
| Intel UHD Graphics 620                                                                   | 1         | 2.17%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 2.17%   |
| Intel Tiger Lake UHD Graphics                                                            | 1         | 2.17%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 2.17%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 2.17%   |
| Intel HD Graphics 620                                                                    | 1         | 2.17%   |
| Intel HD Graphics 530                                                                    | 1         | 2.17%   |
| Intel HD Graphics 520                                                                    | 1         | 2.17%   |
| Intel HD Graphics 500                                                                    | 1         | 2.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 2.17%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 2.17%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 2.17%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 2.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.17%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 2.17%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1         | 2.17%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 2.17%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 2.17%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 2.17%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 2.17%   |
| AMD Mars XTX [Radeon HD 8790M]                                                           | 1         | 2.17%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 1         | 2.17%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1         | 2.17%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 1         | 2.17%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 13        | 39.39%  |
| 1 x Nvidia     | 6         | 18.18%  |
| Intel + Nvidia | 4         | 12.12%  |
| 1 x AMD        | 4         | 12.12%  |
| 2 x AMD        | 3         | 9.09%   |
| Intel + AMD    | 3         | 9.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 32        | 96.97%  |
| Proprietary | 1         | 3.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 27        | 81.82%  |
| 0.01-0.5   | 3         | 9.09%   |
| 0.51-1.0   | 2         | 6.06%   |
| 5.01-6.0   | 1         | 3.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 5         | 15.63%  |
| AU Optronics            | 5         | 15.63%  |
| LG Display              | 4         | 12.5%   |
| Goldstar                | 3         | 9.38%   |
| Chimei Innolux          | 3         | 9.38%   |
| BOE                     | 3         | 9.38%   |
| SAC                     | 1         | 3.13%   |
| LG Philips              | 1         | 3.13%   |
| Lenovo                  | 1         | 3.13%   |
| Iiyama                  | 1         | 3.13%   |
| Chi Mei Optoelectronics | 1         | 3.13%   |
| Beko                    | 1         | 3.13%   |
| AOC                     | 1         | 3.13%   |
| AGO                     | 1         | 3.13%   |
| Acer                    | 1         | 3.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Goldstar W2242 GSM5678 1680x1050 474x296mm 22.0-inch                     | 2         | 6.06%   |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch        | 1         | 3.03%   |
| Samsung Electronics SyncMaster SAM0599 1600x900 443x249mm 20.0-inch      | 1         | 3.03%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch     | 1         | 3.03%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 1         | 3.03%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 1         | 3.03%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch     | 1         | 3.03%   |
| SAC Casper SAC3219 1366x768 304x228mm 15.0-inch                          | 1         | 3.03%   |
| LG Philips LCD Monitor LPL1146 1280x800 331x207mm 15.4-inch              | 1         | 3.03%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 1         | 3.03%   |
| LG Display LCD Monitor LGD0470 1920x1080 345x194mm 15.6-inch             | 1         | 3.03%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch              | 1         | 3.03%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch              | 1         | 3.03%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 1         | 3.03%   |
| Iiyama PLX2380H IVM5621 1920x1080 509x286mm 23.0-inch                    | 1         | 3.03%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                   | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x193mm 15.5-inch          | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 1         | 3.03%   |
| Chi Mei Optoelectronics LCD Monitor CMO15AB 1366x768 340x190mm 15.3-inch | 1         | 3.03%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 1         | 3.03%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 1         | 3.03%   |
| BOE LCD Monitor BOE065E 1920x1080 344x194mm 15.5-inch                    | 1         | 3.03%   |
| Beko BK WUXGA BEK4448 1920x1080 1600x900mm 72.3-inch                     | 1         | 3.03%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 1         | 3.03%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 1         | 3.03%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch           | 1         | 3.03%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 1         | 3.03%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 1         | 3.03%   |
| AOC 2260W AOC2260 1920x1080 477x268mm 21.5-inch                          | 1         | 3.03%   |
| AGO LCD Monitor AGO0001 1920x1080 256x192mm 12.6-inch                    | 1         | 3.03%   |
| Acer G206HQL ACR0327 1600x900 432x239mm 19.4-inch                        | 1         | 3.03%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 14        | 43.75%  |
| 1920x1080 (FHD)    | 10        | 31.25%  |
| 1600x900 (HD+)     | 3         | 9.38%   |
| 1680x1050 (WSXGA+) | 2         | 6.25%   |
| 3840x2160 (4K)     | 1         | 3.13%   |
| 1280x800 (WXGA)    | 1         | 3.13%   |
| 1280x1024 (SXGA)   | 1         | 3.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 18        | 54.55%  |
| 23     | 4         | 12.12%  |
| 14     | 2         | 6.06%   |
| 72     | 1         | 3.03%   |
| 31     | 1         | 3.03%   |
| 22     | 1         | 3.03%   |
| 20     | 1         | 3.03%   |
| 19     | 1         | 3.03%   |
| 17     | 1         | 3.03%   |
| 13     | 1         | 3.03%   |
| 12     | 1         | 3.03%   |
| 11     | 1         | 3.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 21        | 65.63%  |
| 401-500     | 5         | 15.63%  |
| 501-600     | 2         | 6.25%   |
| 201-300     | 2         | 6.25%   |
| 601-700     | 1         | 3.13%   |
| 1501-2000   | 1         | 3.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 25        | 78.13%  |
| 4/3   | 2         | 6.25%   |
| 3/2   | 2         | 6.25%   |
| 16/10 | 2         | 6.25%   |
| 5/4   | 1         | 3.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 18        | 54.55%  |
| 201-250        | 5         | 15.15%  |
| 81-90          | 3         | 9.09%   |
| 151-200        | 2         | 6.06%   |
| More than 1000 | 1         | 3.03%   |
| 71-80          | 1         | 3.03%   |
| 51-60          | 1         | 3.03%   |
| 351-500        | 1         | 3.03%   |
| 141-150        | 1         | 3.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 12        | 36.36%  |
| 51-100  | 10        | 30.3%   |
| 121-160 | 9         | 27.27%  |
| 1-50    | 1         | 3.03%   |
| 161-240 | 1         | 3.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 29        | 87.88%  |
| 2     | 3         | 9.09%   |
| 0     | 1         | 3.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 26        | 52%     |
| Intel                 | 10        | 20%     |
| Qualcomm Atheros      | 4         | 8%      |
| Broadcom              | 3         | 6%      |
| Ralink                | 2         | 4%      |
| ASUSTek Computer      | 2         | 4%      |
| ZyXEL Communications  | 1         | 2%      |
| Xiaomi                | 1         | 2%      |
| JMicron Technology    | 1         | 2%      |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21        | 33.87%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 6.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 4.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 3.23%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 3.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 3.23%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]      | 1         | 1.61%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.61%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 1.61%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.61%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 1.61%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1         | 1.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.61%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.61%   |
| Intel Wireless 7265                                               | 1         | 1.61%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.61%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 1.61%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.61%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.61%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 1.61%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 1.61%   |
| Intel Centrino Wireless-N 2230                                    | 1         | 1.61%   |
| Intel Centrino Wireless-N 130                                     | 1         | 1.61%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 1.61%   |
| Intel Centrino Advanced-N 6200                                    | 1         | 1.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 1.61%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 1.61%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.61%   |
| Broadcom BCM43225 802.11b/g/n                                     | 1         | 1.61%   |
| Broadcom BCM43142 802.11b/g/n                                     | 1         | 1.61%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 1         | 1.61%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                               | 1         | 1.61%   |
| ASUS 802.11ac NIC                                                 | 1         | 1.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 9         | 32.14%  |
| Realtek Semiconductor | 7         | 25%     |
| Qualcomm Atheros      | 4         | 14.29%  |
| Broadcom              | 3         | 10.71%  |
| Ralink                | 2         | 7.14%   |
| ASUSTek Computer      | 2         | 7.14%   |
| ZyXEL Communications  | 1         | 3.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter   | 3         | 10.71%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter     | 2         | 7.14%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter     | 2         | 7.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter              | 2         | 7.14%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU] | 1         | 3.57%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter              | 1         | 3.57%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                    | 1         | 3.57%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                    | 1         | 3.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter   | 1         | 3.57%   |
| Intel Wireless 7265                                          | 1         | 3.57%   |
| Intel Wi-Fi 6 AX201                                          | 1         | 3.57%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection        | 1         | 3.57%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth              | 1         | 3.57%   |
| Intel Centrino Wireless-N 2230                               | 1         | 3.57%   |
| Intel Centrino Wireless-N 130                                | 1         | 3.57%   |
| Intel Centrino Ultimate-N 6300                               | 1         | 3.57%   |
| Intel Centrino Advanced-N 6200                               | 1         | 3.57%   |
| Intel Cannon Lake PCH CNVi WiFi                              | 1         | 3.57%   |
| Broadcom BCM43225 802.11b/g/n                                | 1         | 3.57%   |
| Broadcom BCM43142 802.11b/g/n                                | 1         | 3.57%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter          | 1         | 3.57%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                          | 1         | 3.57%   |
| ASUS 802.11ac NIC                                            | 1         | 3.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 26        | 78.79%  |
| Intel                 | 4         | 12.12%  |
| Xiaomi                | 1         | 3.03%   |
| JMicron Technology    | 1         | 3.03%   |
| Broadcom              | 1         | 3.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21        | 61.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 11.76%  |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 2.94%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 2.94%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 2.94%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 2.94%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.94%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 2.94%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 2.94%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 2.94%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.94%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 32        | 55.17%  |
| WiFi     | 26        | 44.83%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 26        | 53.06%  |
| WiFi     | 23        | 46.94%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 24        | 72.73%  |
| 1     | 9         | 27.27%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 32        | 96.97%  |
| Yes  | 1         | 3.03%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 6         | 27.27%  |
| Realtek Semiconductor           | 5         | 22.73%  |
| Toshiba                         | 2         | 9.09%   |
| Qualcomm Atheros Communications | 2         | 9.09%   |
| IMC Networks                    | 2         | 9.09%   |
| Ralink                          | 1         | 4.55%   |
| Lite-On Technology              | 1         | 4.55%   |
| Foxconn / Hon Hai               | 1         | 4.55%   |
| Cambridge Silicon Radio         | 1         | 4.55%   |
| Broadcom                        | 1         | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 4         | 18.18%  |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 9.09%   |
| Intel Bluetooth wireless interface                  | 2         | 9.09%   |
| Toshiba RT Bluetooth Radio                          | 1         | 4.55%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 4.55%   |
| Realtek RTL8821A Bluetooth                          | 1         | 4.55%   |
| Ralink RT3290 Bluetooth                             | 1         | 4.55%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 4.55%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 4.55%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 4.55%   |
| Intel Bluetooth Device                              | 1         | 4.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 4.55%   |
| IMC Networks Bluetooth Radio                        | 1         | 4.55%   |
| IMC Networks Bluetooth Device                       | 1         | 4.55%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 4.55%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 4.55%   |
| Broadcom HP Portable Valentine                      | 1         | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 27        | 71.05%  |
| AMD                   | 7         | 18.42%  |
| Nvidia                | 3         | 7.89%   |
| Barco Display Systems | 1         | 2.63%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 8.33%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 6.25%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 6.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 4.17%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 4.17%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 4.17%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 4.17%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 4.17%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 4.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 4.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 4.17%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 4.17%   |
| AMD High Definition Audio Controller                                                              | 2         | 4.17%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 2.08%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 2.08%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 2.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 2.08%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 2.08%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 2.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.08%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 2.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 2.08%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 2.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 2.08%   |
| Barco Display Systems USBGH520-ENC                                                                | 1         | 2.08%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 2.08%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1         | 2.08%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 2.08%   |
| AMD FCH Azalia Controller                                                                         | 1         | 2.08%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 1         | 2.08%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 1         | 2.08%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 5         | 45.45%  |
| Unknown (0x4509)    | 1         | 9.09%   |
| Unknown             | 1         | 9.09%   |
| SK Hynix            | 1         | 9.09%   |
| Micron Technology   | 1         | 9.09%   |
| Kingmax             | 1         | 9.09%   |
| G.Skill             | 1         | 9.09%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR2                              | 1         | 9.09%   |
| Unknown (0x4509) RAM GKE800SO102408-2666A 8GB SODIMM DDR4 2133MT/s | 1         | 9.09%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s          | 1         | 9.09%   |
| Samsung RAM M471B5773CHS-CH9 2GB DIMM DDR3 1333MT/s                | 1         | 9.09%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s              | 1         | 9.09%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s              | 1         | 9.09%   |
| Samsung RAM M471A5143EB0-CPB 4096MB SODIMM DDR4 2133MT/s           | 1         | 9.09%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s           | 1         | 9.09%   |
| Micron RAM 8KTF51264HDZ-1G6E1 4GB SODIMM DDR3 1600MT/s             | 1         | 9.09%   |
| Kingmax RAM FSFE85F-C8KL9 2GB DIMM DDR3 1333MT/s                   | 1         | 9.09%   |
| G.Skill RAM F4-2133C15-4GIS 4GB DIMM DDR4 2133MT/s                 | 1         | 9.09%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind  | Computers | Percent |
|-------|-----------|---------|
| DDR4  | 7         | 63.64%  |
| DDR3  | 2         | 18.18%  |
| SDRAM | 1         | 9.09%   |
| DDR2  | 1         | 9.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 8         | 80%     |
| DIMM   | 2         | 20%     |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size | Computers | Percent |
|------|-----------|---------|
| 4096 | 5         | 50%     |
| 8192 | 3         | 30%     |
| 2048 | 2         | 20%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2133    | 3         | 30%     |
| 3200    | 2         | 20%     |
| 2667    | 2         | 20%     |
| 1600    | 1         | 10%     |
| 1333    | 1         | 10%     |
| Unknown | 1         | 10%     |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Zebra  | 2         | 66.67%  |
| Canon  | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Zebra Zebra GC420d Label Printer | 1         | 33.33%  |
| Zebra TLP2844                    | 1         | 33.33%  |
| Canon LBP6030/6030B/6018L        | 1         | 33.33%  |

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


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Chicony Electronics         | 8         | 33.33%  |
| Microdia                    | 3         | 12.5%   |
| Luxvisions Innotech Limited | 2         | 8.33%   |
| IMC Networks                | 2         | 8.33%   |
| Acer                        | 2         | 8.33%   |
| Suyin                       | 1         | 4.17%   |
| Silicon Motion              | 1         | 4.17%   |
| Realtek Semiconductor       | 1         | 4.17%   |
| Lite-On Technology          | 1         | 4.17%   |
| Foxconn / Hon Hai           | 1         | 4.17%   |
| Arkmicro Technologies       | 1         | 4.17%   |
| ALi                         | 1         | 4.17%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony EasyCamera                                  | 2         | 8.33%   |
| Acer EasyCamera                                     | 2         | 8.33%   |
| Suyin HP Webcam                                     | 1         | 4.17%   |
| Silicon Motion WebCam SC-0311139N                   | 1         | 4.17%   |
| Realtek HP Truevision HD integrated webcam          | 1         | 4.17%   |
| Microdia Laptop_Integrated_Webcam_HD                | 1         | 4.17%   |
| Microdia Laptop_Integrated_Webcam_FHD               | 1         | 4.17%   |
| Microdia Integrated_Webcam_HD                       | 1         | 4.17%   |
| Luxvisions Innotech Limited Integrated Camera       | 1         | 4.17%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 4.17%   |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 4.17%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 4.17%   |
| IMC Networks EasyCamera                             | 1         | 4.17%   |
| Foxconn / Hon Hai USB2.0 Camera                     | 1         | 4.17%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 4.17%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 4.17%   |
| Chicony Integrated Camera                           | 1         | 4.17%   |
| Chicony HP Truevision HD                            | 1         | 4.17%   |
| Chicony Front Camera                                | 1         | 4.17%   |
| Chicony CNA7157                                     | 1         | 4.17%   |
| Arkmicro USB2.0 PC CAMERA                           | 1         | 4.17%   |
| ALi Gateway Webcam                                  | 1         | 4.17%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 1         | 50%     |
| AuthenTec        | 1         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor | 1         | 50%     |
| AuthenTec AES1600                            | 1         | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 1         | 50%     |
| Advanced Card Systems | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 50%     |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 24        | 70.59%  |
| 1     | 7         | 20.59%  |
| 2     | 3         | 8.82%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 3         | 25%     |
| Fingerprint reader       | 2         | 16.67%  |
| Chipcard                 | 2         | 16.67%  |
| Camera                   | 2         | 16.67%  |
| Net/wireless             | 1         | 8.33%   |
| Communication controller | 1         | 8.33%   |
| Bluetooth                | 1         | 8.33%   |

