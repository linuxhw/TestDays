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

Total: 49

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T480 20L6S2S800    | [8ab4a35e8c](https://linux-hardware.org/?probe=8ab4a35e8c) | Apr 26, 2023 |
| HP            | ProBook 4540s               | [854f17fcac](https://linux-hardware.org/?probe=854f17fcac) | Apr 23, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [8152bff1b3](https://linux-hardware.org/?probe=8152bff1b3) | Apr 13, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | [54cda388d8](https://linux-hardware.org/?probe=54cda388d8) | Mar 22, 2023 |
| Lenovo        | G510 20238                  | [2dd6ac17cf](https://linux-hardware.org/?probe=2dd6ac17cf) | Feb 26, 2023 |
| Lenovo        | G510 20238                  | [2954f1a3c5](https://linux-hardware.org/?probe=2954f1a3c5) | Feb 25, 2023 |
| Lenovo        | G50-45 80E3                 | [05070bdc72](https://linux-hardware.org/?probe=05070bdc72) | Dec 29, 2022 |
| Toshiba       | Satellite C660              | [5d14354a02](https://linux-hardware.org/?probe=5d14354a02) | Dec 16, 2022 |
| Acer          | Aspire A515-41G             | [fb7da9e239](https://linux-hardware.org/?probe=fb7da9e239) | Dec 10, 2022 |
| Toshiba       | Satellite C660              | [27f508f09e](https://linux-hardware.org/?probe=27f508f09e) | Dec 07, 2022 |
| Toshiba       | Satellite C660              | [ca7c59284c](https://linux-hardware.org/?probe=ca7c59284c) | Nov 28, 2022 |
| Toshiba       | Satellite C660              | [9da0a974dd](https://linux-hardware.org/?probe=9da0a974dd) | Nov 27, 2022 |
| Olidata       | T7700                       | [d8220596fc](https://linux-hardware.org/?probe=d8220596fc) | Nov 19, 2022 |
| HP            | 530                         | [337ff0c5ea](https://linux-hardware.org/?probe=337ff0c5ea) | Nov 15, 2022 |
| Olidata       | T7700                       | [488f74cf4b](https://linux-hardware.org/?probe=488f74cf4b) | Nov 14, 2022 |
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
| Pardus 21.4   | 6         | 15.79%  |
| Pardus 21.3   | 5         | 13.16%  |
| Pardus 21.1   | 5         | 13.16%  |
| Pardus 21.2   | 4         | 10.53%  |
| Pardus 21.0   | 3         | 7.89%   |
| Pardus 19.5   | 3         | 7.89%   |
| Pardus 19.3   | 3         | 7.89%   |
| Pardus 19.4-1 | 2         | 5.26%   |
| Pardus 19.2   | 2         | 5.26%   |
| Pardus 19.1   | 2         | 5.26%   |
| Pardus 19.0   | 2         | 5.26%   |
| Pardus 19.4   | 1         | 2.63%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Pardus | 36        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Notebooks | Percent |
|---------------------------|-----------|---------|
| 5.10.0-21-amd64           | 5         | 12.82%  |
| 5.10.0-19-amd64           | 3         | 7.69%   |
| 5.10.0-13-amd64           | 3         | 7.69%   |
| 5.10.0-11-amd64           | 3         | 7.69%   |
| 4.19.0-6-amd64            | 3         | 7.69%   |
| 4.19.0-10-amd64           | 3         | 7.69%   |
| 5.10.0-9-amd64            | 2         | 5.13%   |
| 5.10.0-10-amd64           | 2         | 5.13%   |
| 4.19.0-13-amd64           | 2         | 5.13%   |
| 6.0.11-x64v2-rt14-xanmod1 | 1         | 2.56%   |
| 5.9.0-0.bpo.2-amd64       | 1         | 2.56%   |
| 5.4.0-0.bpo.3-amd64       | 1         | 2.56%   |
| 5.10.0-8-amd64            | 1         | 2.56%   |
| 5.10.0-20-amd64           | 1         | 2.56%   |
| 5.10.0-17-amd64           | 1         | 2.56%   |
| 5.10.0-16-amd64           | 1         | 2.56%   |
| 5.10.0-14-amd64           | 1         | 2.56%   |
| 5.10.0-0.bpo.8-amd64      | 1         | 2.56%   |
| 4.19.0-8-amd64            | 1         | 2.56%   |
| 4.19.0-5-amd64            | 1         | 2.56%   |
| 4.19.0-19-amd64           | 1         | 2.56%   |
| 4.19.0-16-amd64           | 1         | 2.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 23        | 62.16%  |
| 4.19.0  | 11        | 29.73%  |
| 6.0.11  | 1         | 2.7%    |
| 5.9.0   | 1         | 2.7%    |
| 5.4.0   | 1         | 2.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 23        | 62.16%  |
| 4.19    | 11        | 29.73%  |
| 6.0     | 1         | 2.7%    |
| 5.9     | 1         | 2.7%    |
| 5.4     | 1         | 2.7%    |

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


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| XFCE    | 23        | 63.89%  |
| GNOME   | 10        | 27.78%  |
| Unknown | 2         | 5.56%   |
| KDE5    | 1         | 2.78%   |

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
| Unknown | 22        | 61.11%  |
| TDM     | 6         | 16.67%  |
| LightDM | 4         | 11.11%  |
| GDM     | 4         | 11.11%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| tr_TR   | 27        | 75%     |
| Unknown | 3         | 8.33%   |
| en_US   | 2         | 5.56%   |
| pt_BR   | 1         | 2.78%   |
| hu_HU   | 1         | 2.78%   |
| fur_IT  | 1         | 2.78%   |
| en_GB   | 1         | 2.78%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 24        | 64.86%  |
| EFI  | 13        | 35.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 35        | 97.22%  |
| Overlay | 1         | 2.78%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 23        | 63.89%  |
| GPT     | 11        | 30.56%  |
| MBR     | 2         | 5.56%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 33        | 91.67%  |
| Yes       | 3         | 8.33%   |

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


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 11        | 30.56%  |
| Hewlett-Packard     | 6         | 16.67%  |
| Toshiba             | 3         | 8.33%   |
| Sony                | 2         | 5.56%   |
| Packard Bell        | 2         | 5.56%   |
| Dell                | 2         | 5.56%   |
| ASUSTek Computer    | 2         | 5.56%   |
| Acer                | 2         | 5.56%   |
| TUXEDO              | 1         | 2.78%   |
| Samsung Electronics | 1         | 2.78%   |
| Philco              | 1         | 2.78%   |
| Olidata             | 1         | 2.78%   |
| HUAWEI              | 1         | 2.78%   |
| Clevo               | 1         | 2.78%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Toshiba Satellite C855-1VM                 | 1         | 2.78%   |
| Toshiba Satellite C660                     | 1         | 2.78%   |
| Toshiba PORTEGE M780                       | 1         | 2.78%   |
| Sony SVF1521QSTB                           | 1         | 2.78%   |
| Sony SVE14A2V2ES                           | 1         | 2.78%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 2.78%   |
| Philco 14F                                 | 1         | 2.78%   |
| Packard Bell EasyNote_GN45                 | 1         | 2.78%   |
| Packard Bell EasyNote ENTG81BA             | 1         | 2.78%   |
| Olidata T7700                              | 1         | 2.78%   |
| Lenovo V145-15AST 81MT                     | 1         | 2.78%   |
| Lenovo V110-15ISK 80TL                     | 1         | 2.78%   |
| Lenovo ThinkPad T480 20L6S2S800            | 1         | 2.78%   |
| Lenovo ThinkPad T450 20BUS39Y00            | 1         | 2.78%   |
| Lenovo ThinkPad S1 Yoga 20CD0034TX         | 1         | 2.78%   |
| Lenovo ThinkPad E15 Gen 2 20TD0047TX       | 1         | 2.78%   |
| Lenovo IdeaPad-510-15IKB 80SV              | 1         | 2.78%   |
| Lenovo IdeaPad 320-15IKB 81BT              | 1         | 2.78%   |
| Lenovo IdeaPad 100-15IBD 80QQ              | 1         | 2.78%   |
| Lenovo G510 20238                          | 1         | 2.78%   |
| Lenovo G50-45 80E3                         | 1         | 2.78%   |
| HUAWEI KLVL-WXXW                           | 1         | 2.78%   |
| HP ProBook 4540s                           | 1         | 2.78%   |
| HP Pavilion 15                             | 1         | 2.78%   |
| HP Laptop 15-dw3xxx                        | 1         | 2.78%   |
| HP 530                                     | 1         | 2.78%   |
| HP 250 G3                                  | 1         | 2.78%   |
| HP 15                                      | 1         | 2.78%   |
| Dell Latitude E6540                        | 1         | 2.78%   |
| Dell G5 5587                               | 1         | 2.78%   |
| Clevo W251EFQ/W270EFQ                      | 1         | 2.78%   |
| ASUS X555YI                                | 1         | 2.78%   |
| ASUS E402BP                                | 1         | 2.78%   |
| Acer Aspire A515-41G                       | 1         | 2.78%   |
| Acer Aspire 5742G                          | 1         | 2.78%   |
| Unknown                                    | 1         | 2.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 4         | 11.11%  |
| Toshiba Satellite        | 2         | 5.56%   |
| Packard Bell EasyNote    | 2         | 5.56%   |
| Lenovo IdeaPad           | 2         | 5.56%   |
| Acer Aspire              | 2         | 5.56%   |
| Toshiba PORTEGE          | 1         | 2.78%   |
| Sony SVF1521QSTB         | 1         | 2.78%   |
| Sony SVE14A2V2ES         | 1         | 2.78%   |
| Samsung 300E4A           | 1         | 2.78%   |
| Philco 14F               | 1         | 2.78%   |
| Olidata T7700            | 1         | 2.78%   |
| Lenovo V145-15AST        | 1         | 2.78%   |
| Lenovo V110-15ISK        | 1         | 2.78%   |
| Lenovo IdeaPad-510-15IKB | 1         | 2.78%   |
| Lenovo G510              | 1         | 2.78%   |
| Lenovo G50-45            | 1         | 2.78%   |
| HUAWEI KLVL-WXXW         | 1         | 2.78%   |
| HP ProBook               | 1         | 2.78%   |
| HP Pavilion              | 1         | 2.78%   |
| HP Laptop                | 1         | 2.78%   |
| HP 530                   | 1         | 2.78%   |
| HP 250                   | 1         | 2.78%   |
| HP 15                    | 1         | 2.78%   |
| Dell Latitude            | 1         | 2.78%   |
| Dell G5                  | 1         | 2.78%   |
| Clevo W251EFQ            | 1         | 2.78%   |
| ASUS X555YI              | 1         | 2.78%   |
| ASUS E402BP              | 1         | 2.78%   |
| Unknown                  | 1         | 2.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 7         | 19.44%  |
| 2018 | 5         | 13.89%  |
| 2015 | 4         | 11.11%  |
| 2014 | 3         | 8.33%   |
| 2010 | 3         | 8.33%   |
| 2020 | 2         | 5.56%   |
| 2019 | 2         | 5.56%   |
| 2012 | 2         | 5.56%   |
| 2011 | 2         | 5.56%   |
| 2021 | 1         | 2.78%   |
| 2017 | 1         | 2.78%   |
| 2016 | 1         | 2.78%   |
| 2008 | 1         | 2.78%   |
| 2007 | 1         | 2.78%   |
| 2006 | 1         | 2.78%   |

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
| Disabled | 36        | 100%    |

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


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 13        | 36.11%  |
| 4.01-8.0   | 9         | 25%     |
| 8.01-16.0  | 6         | 16.67%  |
| 16.01-24.0 | 5         | 13.89%  |
| 1.01-2.0   | 2         | 5.56%   |
| 2.01-3.0   | 1         | 2.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 17        | 44.74%  |
| 2.01-3.0 | 12        | 31.58%  |
| 3.01-4.0 | 6         | 15.79%  |
| 4.01-8.0 | 2         | 5.26%   |
| 0.51-1.0 | 1         | 2.63%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 25        | 69.44%  |
| 2      | 10        | 27.78%  |
| 3      | 1         | 2.78%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 19        | 52.78%  |
| No        | 17        | 47.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 33        | 91.67%  |
| No        | 3         | 8.33%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 83.33%  |
| No        | 6         | 16.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Turkey  | 30        | 83.33%  |
| Germany | 2         | 5.56%   |
| UK      | 1         | 2.78%   |
| Sweden  | 1         | 2.78%   |
| Italy   | 1         | 2.78%   |
| Brazil  | 1         | 2.78%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Istanbul             | 12        | 31.58%  |
| Ankara               | 5         | 13.16%  |
| Izmir                | 4         | 10.53%  |
| Çanakkale           | 2         | 5.26%   |
| Serik                | 1         | 2.63%   |
| Sao Gabriel          | 1         | 2.63%   |
| London               | 1         | 2.63%   |
| Landskrona           | 1         | 2.63%   |
| Konya                | 1         | 2.63%   |
| Kirchheim unter Teck | 1         | 2.63%   |
| Gaziantep            | 1         | 2.63%   |
| Esenyurt             | 1         | 2.63%   |
| Castrop-Rauxel       | 1         | 2.63%   |
| Bursa                | 1         | 2.63%   |
| Bolzano              | 1         | 2.63%   |
| Balıkesir           | 1         | 2.63%   |
| Aydin                | 1         | 2.63%   |
| Artvin               | 1         | 2.63%   |
| Antalya              | 1         | 2.63%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 8         | 10     | 17.78%  |
| Seagate                     | 7         | 7      | 15.56%  |
| Samsung Electronics         | 6         | 6      | 13.33%  |
| SanDisk                     | 4         | 4      | 8.89%   |
| Toshiba                     | 2         | 3      | 4.44%   |
| SK hynix                    | 2         | 2      | 4.44%   |
| Kingston                    | 2         | 3      | 4.44%   |
| Hitachi                     | 2         | 2      | 4.44%   |
| HGST                        | 2         | 2      | 4.44%   |
| SPCC                        | 1         | 1      | 2.22%   |
| Silicon Motion              | 1         | 1      | 2.22%   |
| Phison                      | 1         | 1      | 2.22%   |
| Micron Technology           | 1         | 2      | 2.22%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 2.22%   |
| Lexar                       | 1         | 1      | 2.22%   |
| KingSpec                    | 1         | 1      | 2.22%   |
| Intenso                     | 1         | 2      | 2.22%   |
| addlink                     | 1         | 1      | 2.22%   |
| Unknown                     | 1         | 1      | 2.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| HGST HTS545050A7E680 500GB                       | 2         | 4.35%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD                 | 1         | 2.17%   |
| WDC WD5000LPVX-55V0TT0 500GB                     | 1         | 2.17%   |
| WDC WD5000LPCX-60VHAT0 500GB                     | 1         | 2.17%   |
| WDC WD5000LPCX-21VHAT0 500GB                     | 1         | 2.17%   |
| WDC WD3200BPVT-35JJ5T0 320GB                     | 1         | 2.17%   |
| WDC WD2500BEVS-00UST0 250GB                      | 1         | 2.17%   |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 2.17%   |
| WDC WD10JPCX-24UE4T0 1TB                         | 1         | 2.17%   |
| Toshiba MQ01ABD075 752GB                         | 1         | 2.17%   |
| Toshiba MK6475GSX 640GB                          | 1         | 2.17%   |
| SPCC Solid State Disk 512GB                      | 1         | 2.17%   |
| SK hynix SC311 SATA 256GB SSD                    | 1         | 2.17%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB          | 1         | 2.17%   |
| Silicon Motion Longline SSD 512GB                | 1         | 2.17%   |
| Seagate ST9500325AS 500GB                        | 1         | 2.17%   |
| Seagate ST9120822AS 120GB                        | 1         | 2.17%   |
| Seagate ST750LM022 HN-M750MBB 752GB              | 1         | 2.17%   |
| Seagate ST500LM000-1EJ162 500GB                  | 1         | 2.17%   |
| Seagate ST1000LM035-1RK172 970GB                 | 1         | 2.17%   |
| Seagate Expansion 4TB                            | 1         | 2.17%   |
| Seagate BarraCuda Q1 SSD ZA480CV10001 480GB      | 1         | 2.17%   |
| SanDisk SSD U110 16GB                            | 1         | 2.17%   |
| SanDisk SSD PLUS 240GB                           | 1         | 2.17%   |
| SanDisk SSD PLUS 120GB                           | 1         | 2.17%   |
| SanDisk SDSSDA480G 480GB                         | 1         | 2.17%   |
| Samsung SSD 860 EVO 500GB                        | 1         | 2.17%   |
| Samsung SSD 850 PRO 256GB                        | 1         | 2.17%   |
| Samsung MZALQ256HAJD-000L1 256GB                 | 1         | 2.17%   |
| Samsung MZ7LN128HAHQ-000L2 128GB SSD             | 1         | 2.17%   |
| Samsung MZ7LF192HCGS-000L1 192GB SSD             | 1         | 2.17%   |
| Samsung HM250HI 250GB                            | 1         | 2.17%   |
| Phison 311CD0512GB                               | 1         | 2.17%   |
| Micron 1300_MTFDDAK512TDL 512GB SSD              | 1         | 2.17%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 1TB | 1         | 2.17%   |
| Lexar 120GB SSD                                  | 1         | 2.17%   |
| Kingston SHFS37A120G 120GB SSD                   | 1         | 2.17%   |
| Kingston SA400S37240G 240GB SSD                  | 1         | 2.17%   |
| KingSpec P3-128 128GB                            | 1         | 2.17%   |
| Intenso SSD 128GB                                | 1         | 2.17%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 9      | 35%     |
| Seagate             | 6         | 6      | 30%     |
| Toshiba             | 2         | 3      | 10%     |
| Hitachi             | 2         | 2      | 10%     |
| HGST                | 2         | 2      | 10%     |
| Samsung Electronics | 1         | 1      | 5%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 4         | 4      | 22.22%  |
| Samsung Electronics | 4         | 4      | 22.22%  |
| Kingston            | 2         | 3      | 11.11%  |
| WDC                 | 1         | 1      | 5.56%   |
| SPCC                | 1         | 1      | 5.56%   |
| SK hynix            | 1         | 1      | 5.56%   |
| Seagate             | 1         | 1      | 5.56%   |
| Micron Technology   | 1         | 2      | 5.56%   |
| Lexar               | 1         | 1      | 5.56%   |
| KingSpec            | 1         | 1      | 5.56%   |
| Intenso             | 1         | 2      | 5.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 20        | 23     | 48.78%  |
| SSD     | 15        | 21     | 36.59%  |
| NVMe    | 4         | 5      | 9.76%   |
| Unknown | 2         | 2      | 4.88%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 32        | 45     | 86.49%  |
| NVMe | 4         | 5      | 10.81%  |
| SAS  | 1         | 1      | 2.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 25        | 31     | 73.53%  |
| 0.51-1.0   | 8         | 12     | 23.53%  |
| 3.01-4.0   | 1         | 1      | 2.94%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 17        | 45.95%  |
| 251-500    | 12        | 32.43%  |
| 501-1000   | 4         | 10.81%  |
| 21-50      | 2         | 5.41%   |
| 51-100     | 2         | 5.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 18        | 48.65%  |
| 21-50   | 8         | 21.62%  |
| 51-100  | 6         | 16.22%  |
| 101-250 | 4         | 10.81%  |
| 251-500 | 1         | 2.7%    |

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

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 23        | 33     | 62.16%  |
| Works    | 11        | 15     | 29.73%  |
| Malfunc  | 2         | 2      | 5.41%   |
| Failed   | 1         | 1      | 2.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 27        | 71.05%  |
| AMD                         | 6         | 15.79%  |
| SK hynix                    | 1         | 2.63%   |
| Silicon Motion              | 1         | 2.63%   |
| Samsung Electronics         | 1         | 2.63%   |
| Phison Electronics          | 1         | 2.63%   |
| MAXIO Technology (Hangzhou) | 1         | 2.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 6         | 14.29%  |
| AMD FCH SATA Controller [AHCI mode]                                                    | 5         | 11.9%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 3         | 7.14%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 3         | 7.14%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 2         | 4.76%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 2         | 4.76%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 2         | 4.76%   |
| SK hynix BC511                                                                         | 1         | 2.38%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 1         | 2.38%   |
| Samsung NVMe SSD Controller 980                                                        | 1         | 2.38%   |
| Phison PS5013 E13 NVMe Controller                                                      | 1         | 2.38%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                           | 1         | 2.38%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 1         | 2.38%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 1         | 2.38%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 1         | 2.38%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 1         | 2.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 1         | 2.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 1         | 2.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 1         | 2.38%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 2.38%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 2.38%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 1         | 2.38%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 1         | 2.38%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 30        | 76.92%  |
| NVMe | 4         | 10.26%  |
| IDE  | 4         | 10.26%  |
| RAID | 1         | 2.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 29        | 80.56%  |
| AMD    | 7         | 19.44%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-3630QM CPU @ 2.40GHz              | 2         | 5.56%   |
| Intel Core i3 CPU M 370 @ 2.40GHz               | 2         | 5.56%   |
| Intel Pentium CPU B960 @ 2.20GHz                | 1         | 2.78%   |
| Intel Pentium CPU B950 @ 2.10GHz                | 1         | 2.78%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 1         | 2.78%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 2.78%   |
| Intel Core i7-5500U CPU @ 2.40GHz               | 1         | 2.78%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz              | 1         | 2.78%   |
| Intel Core i7-3632QM CPU @ 2.20GHz              | 1         | 2.78%   |
| Intel Core i5-8350U CPU @ 1.70GHz               | 1         | 2.78%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 1         | 2.78%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 1         | 2.78%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 1         | 2.78%   |
| Intel Core i5-4200M CPU @ 2.50GHz               | 1         | 2.78%   |
| Intel Core i5-3230M CPU @ 2.60GHz               | 1         | 2.78%   |
| Intel Core i3-6006U CPU @ 2.00GHz               | 1         | 2.78%   |
| Intel Core i3-5005U CPU @ 2.00GHz               | 1         | 2.78%   |
| Intel Core i3-4010U CPU @ 1.70GHz               | 1         | 2.78%   |
| Intel Core i3-4005U CPU @ 1.70GHz               | 1         | 2.78%   |
| Intel Core i3-3227U CPU @ 1.90GHz               | 1         | 2.78%   |
| Intel Core i3-2310M CPU @ 2.10GHz               | 1         | 2.78%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz            | 1         | 2.78%   |
| Intel Core 2 CPU T5600 @ 1.83GHz                | 1         | 2.78%   |
| Intel Core 2 CPU T5200 @ 1.60GHz                | 1         | 2.78%   |
| Intel Celeron CPU N3050 @ 1.60GHz               | 1         | 2.78%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 1         | 2.78%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz         | 1         | 2.78%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 1         | 2.78%   |
| AMD C-50 Processor                              | 1         | 2.78%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G    | 1         | 2.78%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G    | 1         | 2.78%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics     | 1         | 2.78%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics     | 1         | 2.78%   |
| AMD A10-9620P RADEON R5, 10 COMPUTE CORES 4C+6G | 1         | 2.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i3    | 8         | 22.22%  |
| Intel Core i7    | 7         | 19.44%  |
| Intel Core i5    | 6         | 16.67%  |
| Other            | 4         | 11.11%  |
| Intel Pentium    | 2         | 5.56%   |
| Intel Core 2     | 2         | 5.56%   |
| AMD A8           | 2         | 5.56%   |
| Intel Core 2 Duo | 1         | 2.78%   |
| Intel Celeron    | 1         | 2.78%   |
| AMD Ryzen 5      | 1         | 2.78%   |
| AMD C-50         | 1         | 2.78%   |
| AMD A10          | 1         | 2.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 24        | 66.67%  |
| 4      | 10        | 27.78%  |
| 6      | 2         | 5.56%   |

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
| 2      | 25        | 69.44%  |
| 1      | 11        | 30.56%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 36        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 61.11%  |
| 0x306a9    | 3         | 8.33%   |
| 0x07030105 | 2         | 5.56%   |
| 0x906ea    | 1         | 2.78%   |
| 0x806c1    | 1         | 2.78%   |
| 0x6f6      | 1         | 2.78%   |
| 0x406e3    | 1         | 2.78%   |
| 0x306d4    | 1         | 2.78%   |
| 0x08608102 | 1         | 2.78%   |
| 0x06006705 | 1         | 2.78%   |
| 0x0600611a | 1         | 2.78%   |
| 0x05000029 | 1         | 2.78%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 5         | 13.89%  |
| IvyBridge   | 5         | 13.89%  |
| Haswell     | 4         | 11.11%  |
| SandyBridge | 3         | 8.33%   |
| Excavator   | 3         | 8.33%   |
| Core        | 3         | 8.33%   |
| Broadwell   | 3         | 8.33%   |
| Westmere    | 2         | 5.56%   |
| TigerLake   | 2         | 5.56%   |
| Puma        | 2         | 5.56%   |
| Skylake     | 1         | 2.78%   |
| Silvermont  | 1         | 2.78%   |
| Bobcat      | 1         | 2.78%   |
| Unknown     | 1         | 2.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 27        | 58.7%   |
| AMD    | 12        | 26.09%  |
| Nvidia | 7         | 15.22%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 9.26%   |
| Intel HD Graphics 5500                                                                   | 3         | 5.56%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 3.7%    |
| Intel UHD Graphics 620                                                                   | 2         | 3.7%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 3.7%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 3.7%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 3.7%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 3.7%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 3.7%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 3.7%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 3.7%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 3.7%    |
| Nvidia GT218M [GeForce 315M]                                                             | 1         | 1.85%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 1.85%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 1.85%   |
| Nvidia GF108M [GeForce GT 635M]                                                          | 1         | 1.85%   |
| Nvidia GF108M [GeForce GT 420M]                                                          | 1         | 1.85%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.85%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 1.85%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 1         | 1.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.85%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 1.85%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.85%   |
| Intel HD Graphics 620                                                                    | 1         | 1.85%   |
| Intel HD Graphics 520                                                                    | 1         | 1.85%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.85%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.85%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1         | 1.85%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 1.85%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 1         | 1.85%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 1.85%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                         | 1         | 1.85%   |
| AMD Mars XTX [Radeon HD 8790M]                                                           | 1         | 1.85%   |
| AMD Lucienne                                                                             | 1         | 1.85%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 1         | 1.85%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520/610 Mobile]                         | 1         | 1.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 17        | 47.22%  |
| 2 x AMD        | 5         | 13.89%  |
| Intel + Nvidia | 5         | 13.89%  |
| Intel + AMD    | 5         | 13.89%  |
| 1 x Nvidia     | 2         | 5.56%   |
| 1 x AMD        | 2         | 5.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver | Notebooks | Percent |
|--------|-----------|---------|
| Free   | 36        | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 27        | 75%     |
| 0.01-0.5   | 5         | 13.89%  |
| 0.51-1.0   | 2         | 5.56%   |
| 5.01-6.0   | 1         | 2.78%   |
| 1.01-2.0   | 1         | 2.78%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 9         | 25.71%  |
| Chimei Innolux          | 6         | 17.14%  |
| BOE                     | 5         | 14.29%  |
| Samsung Electronics     | 4         | 11.43%  |
| AU Optronics            | 4         | 11.43%  |
| LG Philips              | 2         | 5.71%   |
| Chi Mei Optoelectronics | 2         | 5.71%   |
| Lenovo                  | 1         | 2.86%   |
| Goldstar                | 1         | 2.86%   |
| AOC                     | 1         | 2.86%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch     | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch     | 1         | 2.78%   |
| LG Philips LCD Monitor LPLDB00 1280x800 331x207mm 15.4-inch              | 1         | 2.78%   |
| LG Philips LCD Monitor LPL1146 1280x800 331x207mm 15.4-inch              | 1         | 2.78%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 1         | 2.78%   |
| LG Display LCD Monitor LGD0470 1920x1080 345x194mm 15.6-inch             | 1         | 2.78%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch              | 1         | 2.78%   |
| LG Display LCD Monitor LGD0414 1920x1080 276x156mm 12.5-inch             | 1         | 2.78%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 1         | 2.78%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch              | 1         | 2.78%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch              | 1         | 2.78%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 1         | 2.78%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch              | 1         | 2.78%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 1         | 2.78%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                   | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x193mm 15.5-inch          | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 1         | 2.78%   |
| Chi Mei Optoelectronics LCD Monitor CMO1703 1440x900 367x230mm 17.1-inch | 1         | 2.78%   |
| Chi Mei Optoelectronics LCD Monitor CMO15AB 1366x768 340x190mm 15.3-inch | 1         | 2.78%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 1         | 2.78%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 1         | 2.78%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 1         | 2.78%   |
| BOE LCD Monitor BOE0661 1366x768 344x194mm 15.5-inch                     | 1         | 2.78%   |
| BOE LCD Monitor BOE065E 1920x1080 344x194mm 15.5-inch                    | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch           | 1         | 2.78%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 1         | 2.78%   |
| AOC 2260WG5 AOC2260 1920x1080 477x268mm 21.5-inch                        | 1         | 2.78%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 19        | 54.29%  |
| 1920x1080 (FHD)  | 10        | 28.57%  |
| 1280x800 (WXGA)  | 2         | 5.71%   |
| 2160x1440        | 1         | 2.86%   |
| 1600x900 (HD+)   | 1         | 2.86%   |
| 1440x900 (WXGA+) | 1         | 2.86%   |
| 1280x1024 (SXGA) | 1         | 2.86%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 25        | 69.44%  |
| 14     | 3         | 8.33%   |
| 13     | 3         | 8.33%   |
| 17     | 2         | 5.56%   |
| 23     | 1         | 2.78%   |
| 22     | 1         | 2.78%   |
| 12     | 1         | 2.78%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 30        | 85.71%  |
| 201-300     | 2         | 5.71%   |
| 501-600     | 1         | 2.86%   |
| 401-500     | 1         | 2.86%   |
| 351-400     | 1         | 2.86%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 30        | 83.33%  |
| 16/10 | 4         | 11.11%  |
| 5/4   | 1         | 2.78%   |
| 3/2   | 1         | 2.78%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 25        | 69.44%  |
| 81-90          | 6         | 16.67%  |
| 201-250        | 2         | 5.56%   |
| 61-70          | 1         | 2.78%   |
| 141-150        | 1         | 2.78%   |
| 131-140        | 1         | 2.78%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 17        | 47.22%  |
| 121-160 | 9         | 25%     |
| 51-100  | 8         | 22.22%  |
| 161-240 | 2         | 5.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 34        | 94.44%  |
| 2     | 2         | 5.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 26        | 44.83%  |
| Intel                 | 14        | 24.14%  |
| Qualcomm Atheros      | 6         | 10.34%  |
| Broadcom              | 4         | 6.9%    |
| Ralink                | 3         | 5.17%   |
| ASUSTek Computer      | 2         | 3.45%   |
| Xiaomi                | 1         | 1.72%   |
| Ralink Technology     | 1         | 1.72%   |
| JMicron Technology    | 1         | 1.72%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 17        | 22.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 7         | 9.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 3         | 4%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 3         | 4%      |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 3         | 4%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 2         | 2.67%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 2         | 2.67%   |
| Intel Wireless 8265 / 8275                                           | 2         | 2.67%   |
| Broadcom BCM43142 802.11b/g/n                                        | 2         | 2.67%   |
| Xiaomi Mi/Redmi series (RNDIS)                                       | 1         | 1.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 1         | 1.33%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 1         | 1.33%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                      | 1         | 1.33%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                               | 1         | 1.33%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 1         | 1.33%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 1         | 1.33%   |
| Realtek RTL8152 Fast Ethernet Adapter                                | 1         | 1.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 1         | 1.33%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 1         | 1.33%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                            | 1         | 1.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 1         | 1.33%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                               | 1         | 1.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 1         | 1.33%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller               | 1         | 1.33%   |
| Intel Wireless 7265                                                  | 1         | 1.33%   |
| Intel Wireless 7260                                                  | 1         | 1.33%   |
| Intel Wi-Fi 6 AX201                                                  | 1         | 1.33%   |
| Intel Ethernet Connection I217-LM                                    | 1         | 1.33%   |
| Intel Ethernet Connection (4) I219-LM                                | 1         | 1.33%   |
| Intel Ethernet Connection (3) I218-V                                 | 1         | 1.33%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 1         | 1.33%   |
| Intel Centrino Wireless-N 2230                                       | 1         | 1.33%   |
| Intel Centrino Wireless-N 130                                        | 1         | 1.33%   |
| Intel Centrino Ultimate-N 6300                                       | 1         | 1.33%   |
| Intel Centrino Advanced-N 6200                                       | 1         | 1.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 1         | 1.33%   |
| Intel 82577LC Gigabit Network Connection                             | 1         | 1.33%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile | 1         | 1.33%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                      | 1         | 1.33%   |
| Broadcom BCM43225 802.11b/g/n                                        | 1         | 1.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 14        | 35%     |
| Realtek Semiconductor | 11        | 27.5%   |
| Qualcomm Atheros      | 5         | 12.5%   |
| Broadcom              | 4         | 10%     |
| Ralink                | 3         | 7.5%    |
| ASUSTek Computer      | 2         | 5%      |
| Ralink Technology     | 1         | 2.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 7.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 3         | 7.5%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 7.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 5%      |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 5%      |
| Intel Wireless 8265 / 8275                                     | 2         | 5%      |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 5%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.5%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.5%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 2.5%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 2.5%    |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 2.5%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 2.5%    |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 2.5%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 2.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 2.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 2.5%    |
| Intel Wireless 7265                                            | 1         | 2.5%    |
| Intel Wireless 7260                                            | 1         | 2.5%    |
| Intel Wi-Fi 6 AX201                                            | 1         | 2.5%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 2.5%    |
| Intel Centrino Wireless-N 2230                                 | 1         | 2.5%    |
| Intel Centrino Wireless-N 130                                  | 1         | 2.5%    |
| Intel Centrino Ultimate-N 6300                                 | 1         | 2.5%    |
| Intel Centrino Advanced-N 6200                                 | 1         | 2.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 2.5%    |
| Broadcom BCM43225 802.11b/g/n                                  | 1         | 2.5%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 2.5%    |
| ASUS Realtek 8188EUS [USB-N10 Nano]                            | 1         | 2.5%    |
| ASUS 802.11ac NIC                                              | 1         | 2.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 25        | 73.53%  |
| Intel                 | 5         | 14.71%  |
| Xiaomi                | 1         | 2.94%   |
| Qualcomm Atheros      | 1         | 2.94%   |
| JMicron Technology    | 1         | 2.94%   |
| Broadcom              | 1         | 2.94%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 17        | 48.57%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 7         | 20%     |
| Xiaomi Mi/Redmi series (RNDIS)                                       | 1         | 2.86%   |
| Realtek RTL8152 Fast Ethernet Adapter                                | 1         | 2.86%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 1         | 2.86%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                               | 1         | 2.86%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller               | 1         | 2.86%   |
| Intel Ethernet Connection I217-LM                                    | 1         | 2.86%   |
| Intel Ethernet Connection (4) I219-LM                                | 1         | 2.86%   |
| Intel Ethernet Connection (3) I218-V                                 | 1         | 2.86%   |
| Intel 82577LC Gigabit Network Connection                             | 1         | 2.86%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile | 1         | 2.86%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                      | 1         | 2.86%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 36        | 52.17%  |
| Ethernet | 33        | 47.83%  |

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
| 2     | 33        | 91.67%  |
| 1     | 3         | 8.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 33        | 91.67%  |
| Yes  | 3         | 8.33%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 9         | 30%     |
| Realtek Semiconductor           | 6         | 20%     |
| Toshiba                         | 2         | 6.67%   |
| Ralink                          | 2         | 6.67%   |
| Qualcomm Atheros Communications | 2         | 6.67%   |
| Lite-On Technology              | 2         | 6.67%   |
| Cambridge Silicon Radio         | 2         | 6.67%   |
| Realtek                         | 1         | 3.33%   |
| IMC Networks                    | 1         | 3.33%   |
| Foxconn International           | 1         | 3.33%   |
| Foxconn / Hon Hai               | 1         | 3.33%   |
| Broadcom                        | 1         | 3.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 5         | 16.67%  |
| Realtek Bluetooth Radio                             | 4         | 13.33%  |
| Ralink RT3290 Bluetooth                             | 2         | 6.67%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 6.67%   |
| Toshiba RT Bluetooth Radio                          | 1         | 3.33%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 3.33%   |
| Realtek RTL8821A Bluetooth                          | 1         | 3.33%   |
| Realtek RTL8723B Bluetooth                          | 1         | 3.33%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 3.33%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 3.33%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 3.33%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 3.33%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 3.33%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 3.33%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 3.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 3.33%   |
| Intel AX201 Bluetooth                               | 1         | 3.33%   |
| IMC Networks Bluetooth Device                       | 1         | 3.33%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 3.33%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 3.33%   |
| Broadcom HP Portable Valentine                      | 1         | 3.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 29        | 72.5%   |
| AMD                   | 7         | 17.5%   |
| Nvidia                | 3         | 7.5%    |
| Barco Display Systems | 1         | 2.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 11.32%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 4         | 7.55%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 5.66%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 5.66%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 5.66%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 5.66%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 3.77%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 3.77%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 3.77%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 3.77%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 3.77%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 3.77%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 3.77%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 3.77%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 3.77%   |
| AMD High Definition Audio Controller                                                              | 2         | 3.77%   |
| AMD FCH Azalia Controller                                                                         | 2         | 3.77%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 1.89%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.89%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.89%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.89%   |
| Barco Display Systems USBGH520-ENC                                                                | 1         | 1.89%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.89%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 1.89%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.89%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 6         | 40%     |
| SK hynix            | 3         | 20%     |
| Unknown (0x4509)    | 1         | 6.67%   |
| Unknown             | 1         | 6.67%   |
| Micron Technology   | 1         | 6.67%   |
| Kingston            | 1         | 6.67%   |
| Kingmax             | 1         | 6.67%   |
| A-DATA Technology   | 1         | 6.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR2                              | 1         | 6.67%   |
| Unknown (0x4509) RAM GKE800SO102408-2666A 8GB SODIMM DDR4 2133MT/s | 1         | 6.67%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s             | 1         | 6.67%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s       | 1         | 6.67%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s             | 1         | 6.67%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s              | 1         | 6.67%   |
| Samsung RAM M471B5773CHS-CH9 2GB DIMM DDR3 1333MT/s                | 1         | 6.67%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s              | 1         | 6.67%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s              | 1         | 6.67%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s              | 1         | 6.67%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s              | 1         | 6.67%   |
| Micron RAM 8KTF51264HDZ-1G6E1 4GB SODIMM DDR3 1600MT/s             | 1         | 6.67%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s            | 1         | 6.67%   |
| Kingmax RAM FSFE85F-C8KL9 2GB DIMM DDR3 1333MT/s                   | 1         | 6.67%   |
| A-DATA RAM AO1P21FC8T1-BSKS 8GB SODIMM DDR4 2133MT/s               | 1         | 6.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Notebooks | Percent |
|-------|-----------|---------|
| DDR4  | 7         | 50%     |
| DDR3  | 5         | 35.71%  |
| SDRAM | 1         | 7.14%   |
| DDR2  | 1         | 7.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 11        | 84.62%  |
| Row Of Chips | 1         | 7.69%   |
| DIMM         | 1         | 7.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 8192 | 7         | 50%     |
| 4096 | 4         | 28.57%  |
| 2048 | 3         | 21.43%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 4         | 30.77%  |
| 3200    | 3         | 23.08%  |
| 2667    | 2         | 15.38%  |
| 2133    | 2         | 15.38%  |
| 1333    | 1         | 7.69%   |
| Unknown | 1         | 7.69%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Canon PIXMA MX340    | 1         | 50%     |
| Canon LBP6030w/6018w | 1         | 50%     |

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
| Chicony Electronics                    | 12        | 40%     |
| Realtek Semiconductor                  | 3         | 10%     |
| IMC Networks                           | 3         | 10%     |
| Microdia                               | 2         | 6.67%   |
| Luxvisions Innotech Limited            | 2         | 6.67%   |
| Suyin                                  | 1         | 3.33%   |
| Silicon Motion                         | 1         | 3.33%   |
| Lite-On Technology                     | 1         | 3.33%   |
| Foxconn / Hon Hai                      | 1         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.33%   |
| Bison Electronics                      | 1         | 3.33%   |
| ALi                                    | 1         | 3.33%   |
| Acer                                   | 1         | 3.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Lenovo EasyCamera                           | 2         | 6.67%   |
| Chicony Integrated Camera                           | 2         | 6.67%   |
| Chicony EasyCamera                                  | 2         | 6.67%   |
| Suyin HP Webcam                                     | 1         | 3.33%   |
| Silicon Motion WebCam SC-0311139N                   | 1         | 3.33%   |
| Realtek HP Truevision HD integrated webcam          | 1         | 3.33%   |
| Microdia Laptop_Integrated_Webcam_HD                | 1         | 3.33%   |
| Microdia Integrated_Webcam_HD                       | 1         | 3.33%   |
| Luxvisions Innotech Limited Integrated Camera       | 1         | 3.33%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 3.33%   |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 3.33%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 3.33%   |
| IMC Networks Lenovo EasyCamera                      | 1         | 3.33%   |
| IMC Networks EasyCamera                             | 1         | 3.33%   |
| Foxconn / Hon Hai USB2.0 Camera                     | 1         | 3.33%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 3.33%   |
| Chicony USB2.0 Camera                               | 1         | 3.33%   |
| Chicony USB 2.0 Camera                              | 1         | 3.33%   |
| Chicony HP Truevision HD                            | 1         | 3.33%   |
| Chicony Gateway USB 2.0 Webcam                      | 1         | 3.33%   |
| Chicony Front Camera                                | 1         | 3.33%   |
| Chicony CNF9055 Toshiba Webcam                      | 1         | 3.33%   |
| Chicony CNA7157                                     | 1         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 1         | 3.33%   |
| Bison SunplusIT Integrated Camera                   | 1         | 3.33%   |
| ALi Gateway Webcam                                  | 1         | 3.33%   |
| Acer EasyCamera                                     | 1         | 3.33%   |

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
| 0     | 28        | 75.68%  |
| 1     | 7         | 18.92%  |
| 2     | 2         | 5.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Graphics card      | 3         | 27.27%  |
| Fingerprint reader | 3         | 27.27%  |
| Bluetooth          | 2         | 18.18%  |
| Net/wireless       | 1         | 9.09%   |
| Chipcard           | 1         | 9.09%   |
| Camera             | 1         | 9.09%   |

