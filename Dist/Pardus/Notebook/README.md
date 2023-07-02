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

Total: 52

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Toshiba       | Satellite L755              | [eea8633642](https://linux-hardware.org/?probe=eea8633642) | Jun 21, 2023 |
| Dell          | Vostro 5502                 | [5d42ac567c](https://linux-hardware.org/?probe=5d42ac567c) | Jun 13, 2023 |
| Lenovo        | ThinkPad T480 20L6S2S800    | [7ffc12366e](https://linux-hardware.org/?probe=7ffc12366e) | May 03, 2023 |
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
| Pardus 21.4   | 6         | 15%     |
| Pardus 21.3   | 5         | 12.5%   |
| Pardus 21.1   | 5         | 12.5%   |
| Pardus 21.2   | 4         | 10%     |
| Pardus 21.0   | 3         | 7.5%    |
| Pardus 19.5   | 3         | 7.5%    |
| Pardus 19.3   | 3         | 7.5%    |
| Pardus 21.5   | 2         | 5%      |
| Pardus 19.4-1 | 2         | 5%      |
| Pardus 19.2   | 2         | 5%      |
| Pardus 19.1   | 2         | 5%      |
| Pardus 19.0   | 2         | 5%      |
| Pardus 19.4   | 1         | 2.5%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Pardus | 38        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Notebooks | Percent |
|---------------------------|-----------|---------|
| 5.10.0-21-amd64           | 5         | 12.2%   |
| 5.10.0-19-amd64           | 4         | 9.76%   |
| 5.10.0-13-amd64           | 3         | 7.32%   |
| 5.10.0-11-amd64           | 3         | 7.32%   |
| 4.19.0-6-amd64            | 3         | 7.32%   |
| 4.19.0-10-amd64           | 3         | 7.32%   |
| 5.10.0-9-amd64            | 2         | 4.88%   |
| 5.10.0-10-amd64           | 2         | 4.88%   |
| 4.19.0-13-amd64           | 2         | 4.88%   |
| 6.0.11-x64v2-rt14-xanmod1 | 1         | 2.44%   |
| 5.9.0-0.bpo.2-amd64       | 1         | 2.44%   |
| 5.4.0-0.bpo.3-amd64       | 1         | 2.44%   |
| 5.10.0-8-amd64            | 1         | 2.44%   |
| 5.10.0-23-amd64           | 1         | 2.44%   |
| 5.10.0-20-amd64           | 1         | 2.44%   |
| 5.10.0-17-amd64           | 1         | 2.44%   |
| 5.10.0-16-amd64           | 1         | 2.44%   |
| 5.10.0-14-amd64           | 1         | 2.44%   |
| 5.10.0-0.bpo.8-amd64      | 1         | 2.44%   |
| 4.19.0-8-amd64            | 1         | 2.44%   |
| 4.19.0-5-amd64            | 1         | 2.44%   |
| 4.19.0-19-amd64           | 1         | 2.44%   |
| 4.19.0-16-amd64           | 1         | 2.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 25        | 64.1%   |
| 4.19.0  | 11        | 28.21%  |
| 6.0.11  | 1         | 2.56%   |
| 5.9.0   | 1         | 2.56%   |
| 5.4.0   | 1         | 2.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 25        | 64.1%   |
| 4.19    | 11        | 28.21%  |
| 6.0     | 1         | 2.56%   |
| 5.9     | 1         | 2.56%   |
| 5.4     | 1         | 2.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 38        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| XFCE    | 24        | 63.16%  |
| GNOME   | 11        | 28.95%  |
| Unknown | 2         | 5.26%   |
| KDE5    | 1         | 2.63%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 38        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 24        | 63.16%  |
| TDM     | 6         | 15.79%  |
| LightDM | 4         | 10.53%  |
| GDM     | 4         | 10.53%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| tr_TR   | 29        | 76.32%  |
| Unknown | 3         | 7.89%   |
| en_US   | 2         | 5.26%   |
| pt_BR   | 1         | 2.63%   |
| hu_HU   | 1         | 2.63%   |
| fur_IT  | 1         | 2.63%   |
| en_GB   | 1         | 2.63%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 26        | 66.67%  |
| EFI  | 13        | 33.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 37        | 97.37%  |
| Overlay | 1         | 2.63%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 25        | 65.79%  |
| GPT     | 11        | 28.95%  |
| MBR     | 2         | 5.26%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 35        | 92.11%  |
| Yes       | 3         | 7.89%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 31        | 81.58%  |
| Yes       | 7         | 18.42%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 11        | 28.95%  |
| Hewlett-Packard     | 6         | 15.79%  |
| Toshiba             | 4         | 10.53%  |
| Dell                | 3         | 7.89%   |
| Sony                | 2         | 5.26%   |
| Packard Bell        | 2         | 5.26%   |
| ASUSTek Computer    | 2         | 5.26%   |
| Acer                | 2         | 5.26%   |
| TUXEDO              | 1         | 2.63%   |
| Samsung Electronics | 1         | 2.63%   |
| Philco              | 1         | 2.63%   |
| Olidata             | 1         | 2.63%   |
| HUAWEI              | 1         | 2.63%   |
| Clevo               | 1         | 2.63%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Toshiba Satellite L755                     | 1         | 2.63%   |
| Toshiba Satellite C855-1VM                 | 1         | 2.63%   |
| Toshiba Satellite C660                     | 1         | 2.63%   |
| Toshiba PORTEGE M780                       | 1         | 2.63%   |
| Sony SVF1521QSTB                           | 1         | 2.63%   |
| Sony SVE14A2V2ES                           | 1         | 2.63%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 2.63%   |
| Philco 14F                                 | 1         | 2.63%   |
| Packard Bell EasyNote_GN45                 | 1         | 2.63%   |
| Packard Bell EasyNote ENTG81BA             | 1         | 2.63%   |
| Olidata T7700                              | 1         | 2.63%   |
| Lenovo V145-15AST 81MT                     | 1         | 2.63%   |
| Lenovo V110-15ISK 80TL                     | 1         | 2.63%   |
| Lenovo ThinkPad T480 20L6S2S800            | 1         | 2.63%   |
| Lenovo ThinkPad T450 20BUS39Y00            | 1         | 2.63%   |
| Lenovo ThinkPad S1 Yoga 20CD0034TX         | 1         | 2.63%   |
| Lenovo ThinkPad E15 Gen 2 20TD0047TX       | 1         | 2.63%   |
| Lenovo IdeaPad-510-15IKB 80SV              | 1         | 2.63%   |
| Lenovo IdeaPad 320-15IKB 81BT              | 1         | 2.63%   |
| Lenovo IdeaPad 100-15IBD 80QQ              | 1         | 2.63%   |
| Lenovo G510 20238                          | 1         | 2.63%   |
| Lenovo G50-45 80E3                         | 1         | 2.63%   |
| HUAWEI KLVL-WXXW                           | 1         | 2.63%   |
| HP ProBook 4540s                           | 1         | 2.63%   |
| HP Pavilion 15                             | 1         | 2.63%   |
| HP Laptop 15-dw3xxx                        | 1         | 2.63%   |
| HP 530                                     | 1         | 2.63%   |
| HP 250 G3                                  | 1         | 2.63%   |
| HP 15                                      | 1         | 2.63%   |
| Dell Vostro 5502                           | 1         | 2.63%   |
| Dell Latitude E6540                        | 1         | 2.63%   |
| Dell G5 5587                               | 1         | 2.63%   |
| Clevo W251EFQ/W270EFQ                      | 1         | 2.63%   |
| ASUS X555YI                                | 1         | 2.63%   |
| ASUS E402BP                                | 1         | 2.63%   |
| Acer Aspire A515-41G                       | 1         | 2.63%   |
| Acer Aspire 5742G                          | 1         | 2.63%   |
| Unknown                                    | 1         | 2.63%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 4         | 10.53%  |
| Toshiba Satellite        | 3         | 7.89%   |
| Packard Bell EasyNote    | 2         | 5.26%   |
| Lenovo IdeaPad           | 2         | 5.26%   |
| Acer Aspire              | 2         | 5.26%   |
| Toshiba PORTEGE          | 1         | 2.63%   |
| Sony SVF1521QSTB         | 1         | 2.63%   |
| Sony SVE14A2V2ES         | 1         | 2.63%   |
| Samsung 300E4A           | 1         | 2.63%   |
| Philco 14F               | 1         | 2.63%   |
| Olidata T7700            | 1         | 2.63%   |
| Lenovo V145-15AST        | 1         | 2.63%   |
| Lenovo V110-15ISK        | 1         | 2.63%   |
| Lenovo IdeaPad-510-15IKB | 1         | 2.63%   |
| Lenovo G510              | 1         | 2.63%   |
| Lenovo G50-45            | 1         | 2.63%   |
| HUAWEI KLVL-WXXW         | 1         | 2.63%   |
| HP ProBook               | 1         | 2.63%   |
| HP Pavilion              | 1         | 2.63%   |
| HP Laptop                | 1         | 2.63%   |
| HP 530                   | 1         | 2.63%   |
| HP 250                   | 1         | 2.63%   |
| HP 15                    | 1         | 2.63%   |
| Dell Vostro              | 1         | 2.63%   |
| Dell Latitude            | 1         | 2.63%   |
| Dell G5                  | 1         | 2.63%   |
| Clevo W251EFQ            | 1         | 2.63%   |
| ASUS X555YI              | 1         | 2.63%   |
| ASUS E402BP              | 1         | 2.63%   |
| Unknown                  | 1         | 2.63%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 7         | 18.42%  |
| 2018 | 5         | 13.16%  |
| 2014 | 4         | 10.53%  |
| 2015 | 3         | 7.89%   |
| 2011 | 3         | 7.89%   |
| 2010 | 3         | 7.89%   |
| 2021 | 2         | 5.26%   |
| 2020 | 2         | 5.26%   |
| 2019 | 2         | 5.26%   |
| 2012 | 2         | 5.26%   |
| 2017 | 1         | 2.63%   |
| 2016 | 1         | 2.63%   |
| 2008 | 1         | 2.63%   |
| 2007 | 1         | 2.63%   |
| 2006 | 1         | 2.63%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 38        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 38        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 38        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 13        | 34.21%  |
| 4.01-8.0   | 10        | 26.32%  |
| 8.01-16.0  | 7         | 18.42%  |
| 16.01-24.0 | 5         | 13.16%  |
| 1.01-2.0   | 2         | 5.26%   |
| 2.01-3.0   | 1         | 2.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 19        | 46.34%  |
| 2.01-3.0 | 13        | 31.71%  |
| 3.01-4.0 | 6         | 14.63%  |
| 4.01-8.0 | 2         | 4.88%   |
| 0.51-1.0 | 1         | 2.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 26        | 68.42%  |
| 2      | 11        | 28.95%  |
| 3      | 1         | 2.63%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 52.63%  |
| No        | 18        | 47.37%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 35        | 92.11%  |
| No        | 3         | 7.89%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 84.21%  |
| No        | 6         | 15.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| Turkey     | 31        | 81.58%  |
| Germany    | 2         | 5.26%   |
| UK         | 1         | 2.63%   |
| Sweden     | 1         | 2.63%   |
| Italy      | 1         | 2.63%   |
| Brazil     | 1         | 2.63%   |
| Azerbaijan | 1         | 2.63%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Istanbul             | 13        | 32.5%   |
| Ankara               | 5         | 12.5%   |
| Izmir                | 4         | 10%     |
| Çanakkale           | 2         | 5%      |
| Serik                | 1         | 2.5%    |
| Sao Gabriel          | 1         | 2.5%    |
| London               | 1         | 2.5%    |
| Landskrona           | 1         | 2.5%    |
| Konya                | 1         | 2.5%    |
| Kirchheim unter Teck | 1         | 2.5%    |
| Gaziantep            | 1         | 2.5%    |
| Esenyurt             | 1         | 2.5%    |
| Castrop-Rauxel       | 1         | 2.5%    |
| Bursa                | 1         | 2.5%    |
| Bolzano              | 1         | 2.5%    |
| Balıkesir           | 1         | 2.5%    |
| Baku                 | 1         | 2.5%    |
| Aydin                | 1         | 2.5%    |
| Artvin               | 1         | 2.5%    |
| Antalya              | 1         | 2.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 8         | 10     | 17.02%  |
| Seagate                     | 7         | 7      | 14.89%  |
| Samsung Electronics         | 7         | 7      | 14.89%  |
| SanDisk                     | 4         | 4      | 8.51%   |
| Toshiba                     | 2         | 3      | 4.26%   |
| SK hynix                    | 2         | 2      | 4.26%   |
| Kingston                    | 2         | 3      | 4.26%   |
| Hitachi                     | 2         | 2      | 4.26%   |
| HGST                        | 2         | 2      | 4.26%   |
| SPCC                        | 1         | 1      | 2.13%   |
| Silicon Motion              | 1         | 1      | 2.13%   |
| Phison                      | 1         | 1      | 2.13%   |
| Micron Technology           | 1         | 2      | 2.13%   |
| MAXIO Technology (Hangzhou) | 1         | 2      | 2.13%   |
| Lexar                       | 1         | 1      | 2.13%   |
| Kingston Technology Company | 1         | 1      | 2.13%   |
| KingSpec                    | 1         | 1      | 2.13%   |
| Intenso                     | 1         | 2      | 2.13%   |
| addlink                     | 1         | 1      | 2.13%   |
| Unknown                     | 1         | 1      | 2.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| HGST HTS545050A7E680 500GB                         | 2         | 4.17%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD                   | 1         | 2.08%   |
| WDC WD5000LPVX-55V0TT0 500GB                       | 1         | 2.08%   |
| WDC WD5000LPCX-60VHAT0 500GB                       | 1         | 2.08%   |
| WDC WD5000LPCX-21VHAT0 500GB                       | 1         | 2.08%   |
| WDC WD3200BPVT-35JJ5T0 320GB                       | 1         | 2.08%   |
| WDC WD2500BEVS-00UST0 250GB                        | 1         | 2.08%   |
| WDC WD10JPVX-60JC3T0 1TB                           | 1         | 2.08%   |
| WDC WD10JPCX-24UE4T0 1TB                           | 1         | 2.08%   |
| Toshiba MQ01ABD075 752GB                           | 1         | 2.08%   |
| Toshiba MK6475GSX 640GB                            | 1         | 2.08%   |
| SPCC Solid State Disk 512GB                        | 1         | 2.08%   |
| SK hynix SC311 SATA 256GB SSD                      | 1         | 2.08%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB            | 1         | 2.08%   |
| Silicon Motion Longline SSD 512GB                  | 1         | 2.08%   |
| Seagate ST9500325AS 500GB                          | 1         | 2.08%   |
| Seagate ST9120822AS 120GB                          | 1         | 2.08%   |
| Seagate ST750LM022 HN-M750MBB 752GB                | 1         | 2.08%   |
| Seagate ST500LM000-1EJ162 500GB                    | 1         | 2.08%   |
| Seagate ST1000LM035-1RK172 1TB                     | 1         | 2.08%   |
| Seagate Expansion 1TB                              | 1         | 2.08%   |
| Seagate BarraCuda Q1 SSD ZA480CV10001 480GB        | 1         | 2.08%   |
| SanDisk SSD U110 16GB                              | 1         | 2.08%   |
| SanDisk SSD PLUS 240GB                             | 1         | 2.08%   |
| SanDisk SSD PLUS 120GB                             | 1         | 2.08%   |
| SanDisk SDSSDA480G 480GB                           | 1         | 2.08%   |
| Samsung SSD 860 EVO 500GB                          | 1         | 2.08%   |
| Samsung SSD 850 PRO 256GB                          | 1         | 2.08%   |
| Samsung MZMTD256HAGM-000L1 256GB SSD               | 1         | 2.08%   |
| Samsung MZALQ256HAJD-000L1 256GB                   | 1         | 2.08%   |
| Samsung MZ7LN128HAHQ-000L2 128GB SSD               | 1         | 2.08%   |
| Samsung MZ7LF192HCGS-000L1 192GB SSD               | 1         | 2.08%   |
| Samsung HM250HI 250GB                              | 1         | 2.08%   |
| Phison 311CD0512GB                                 | 1         | 2.08%   |
| Micron 1300_MTFDDAK512TDL 512GB SSD                | 1         | 2.08%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 512GB | 1         | 2.08%   |
| Lexar 120GB SSD                                    | 1         | 2.08%   |
| Kingston Company OM3PDP3 NVMe SSD 256GB            | 1         | 2.08%   |
| Kingston SHFS37A120G 120GB SSD                     | 1         | 2.08%   |
| Kingston SA400S37240G 240GB SSD                    | 1         | 2.08%   |

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
| Samsung Electronics | 5         | 5      | 26.32%  |
| SanDisk             | 4         | 4      | 21.05%  |
| Kingston            | 2         | 3      | 10.53%  |
| WDC                 | 1         | 1      | 5.26%   |
| SPCC                | 1         | 1      | 5.26%   |
| SK hynix            | 1         | 1      | 5.26%   |
| Seagate             | 1         | 1      | 5.26%   |
| Micron Technology   | 1         | 2      | 5.26%   |
| Lexar               | 1         | 1      | 5.26%   |
| KingSpec            | 1         | 1      | 5.26%   |
| Intenso             | 1         | 2      | 5.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 20        | 23     | 46.51%  |
| SSD     | 16        | 22     | 37.21%  |
| NVMe    | 5         | 7      | 11.63%  |
| Unknown | 2         | 2      | 4.65%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 33        | 46     | 84.62%  |
| NVMe | 5         | 7      | 12.82%  |
| SAS  | 1         | 1      | 2.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 26        | 32     | 74.29%  |
| 0.51-1.0   | 9         | 13     | 25.71%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 19        | 48.72%  |
| 251-500    | 12        | 30.77%  |
| 501-1000   | 4         | 10.26%  |
| 21-50      | 2         | 5.13%   |
| 51-100     | 2         | 5.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 18        | 46.15%  |
| 21-50   | 8         | 20.51%  |
| 51-100  | 8         | 20.51%  |
| 101-250 | 4         | 10.26%  |
| 251-500 | 1         | 2.56%   |

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
| Detected | 25        | 36     | 64.1%   |
| Works    | 11        | 15     | 28.21%  |
| Malfunc  | 2         | 2      | 5.13%   |
| Failed   | 1         | 1      | 2.56%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 28        | 70%     |
| AMD                         | 6         | 15%     |
| SK hynix                    | 1         | 2.5%    |
| Silicon Motion              | 1         | 2.5%    |
| Samsung Electronics         | 1         | 2.5%    |
| Phison Electronics          | 1         | 2.5%    |
| MAXIO Technology (Hangzhou) | 1         | 2.5%    |
| Kingston Technology Company | 1         | 2.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 6         | 13.64%  |
| AMD FCH SATA Controller [AHCI mode]                                                    | 5         | 11.36%  |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 3         | 6.82%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 3         | 6.82%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 2         | 4.55%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 2         | 4.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 2         | 4.55%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 2         | 4.55%   |
| SK hynix BC511 NVMe SSD                                                                | 1         | 2.27%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 1         | 2.27%   |
| Samsung NVMe SSD Controller 980                                                        | 1         | 2.27%   |
| Phison PS5013 E13 NVMe Controller                                                      | 1         | 2.27%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                           | 1         | 2.27%   |
| Kingston Company OM3PDP3 NVMe SSD                                                      | 1         | 2.27%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 1         | 2.27%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 1         | 2.27%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 1         | 2.27%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 1         | 2.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 1         | 2.27%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 1         | 2.27%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 1         | 2.27%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 2.27%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 2.27%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 2.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 1         | 2.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 31        | 75.61%  |
| NVMe | 5         | 12.2%   |
| IDE  | 4         | 9.76%   |
| RAID | 1         | 2.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 31        | 81.58%  |
| AMD    | 7         | 18.42%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-3630QM CPU @ 2.40GHz              | 2         | 5.26%   |
| Intel Core i3 CPU M 370 @ 2.40GHz               | 2         | 5.26%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 2         | 5.26%   |
| Intel Pentium CPU B960 @ 2.20GHz                | 1         | 2.63%   |
| Intel Pentium CPU B950 @ 2.10GHz                | 1         | 2.63%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 1         | 2.63%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 2.63%   |
| Intel Core i7-5500U CPU @ 2.40GHz               | 1         | 2.63%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz              | 1         | 2.63%   |
| Intel Core i7-3632QM CPU @ 2.20GHz              | 1         | 2.63%   |
| Intel Core i7-2670QM CPU @ 2.20GHz              | 1         | 2.63%   |
| Intel Core i5-8350U CPU @ 1.70GHz               | 1         | 2.63%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 1         | 2.63%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 1         | 2.63%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 1         | 2.63%   |
| Intel Core i5-4200M CPU @ 2.50GHz               | 1         | 2.63%   |
| Intel Core i5-3230M CPU @ 2.60GHz               | 1         | 2.63%   |
| Intel Core i3-6006U CPU @ 2.00GHz               | 1         | 2.63%   |
| Intel Core i3-5005U CPU @ 2.00GHz               | 1         | 2.63%   |
| Intel Core i3-4010U CPU @ 1.70GHz               | 1         | 2.63%   |
| Intel Core i3-4005U CPU @ 1.70GHz               | 1         | 2.63%   |
| Intel Core i3-3227U CPU @ 1.90GHz               | 1         | 2.63%   |
| Intel Core i3-2310M CPU @ 2.10GHz               | 1         | 2.63%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz            | 1         | 2.63%   |
| Intel Core 2 CPU T5600 @ 1.83GHz                | 1         | 2.63%   |
| Intel Core 2 CPU T5200 @ 1.60GHz                | 1         | 2.63%   |
| Intel Celeron CPU N3050 @ 1.60GHz               | 1         | 2.63%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz         | 1         | 2.63%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 1         | 2.63%   |
| AMD C-50 Processor                              | 1         | 2.63%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G    | 1         | 2.63%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G    | 1         | 2.63%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics     | 1         | 2.63%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics     | 1         | 2.63%   |
| AMD A10-9620P RADEON R5, 10 COMPUTE CORES 4C+6G | 1         | 2.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 8         | 21.05%  |
| Intel Core i3    | 8         | 21.05%  |
| Intel Core i5    | 6         | 15.79%  |
| Other            | 5         | 13.16%  |
| Intel Pentium    | 2         | 5.26%   |
| Intel Core 2     | 2         | 5.26%   |
| AMD A8           | 2         | 5.26%   |
| Intel Core 2 Duo | 1         | 2.63%   |
| Intel Celeron    | 1         | 2.63%   |
| AMD Ryzen 5      | 1         | 2.63%   |
| AMD C-50         | 1         | 2.63%   |
| AMD A10          | 1         | 2.63%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 24        | 63.16%  |
| 4      | 12        | 31.58%  |
| 6      | 2         | 5.26%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 38        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 27        | 71.05%  |
| 1      | 11        | 28.95%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 38        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 23        | 60.53%  |
| 0x306a9    | 3         | 7.89%   |
| 0x07030105 | 2         | 5.26%   |
| 0x906ea    | 1         | 2.63%   |
| 0x806c1    | 1         | 2.63%   |
| 0x6f6      | 1         | 2.63%   |
| 0x406e3    | 1         | 2.63%   |
| 0x306d4    | 1         | 2.63%   |
| 0x206a7    | 1         | 2.63%   |
| 0x08608102 | 1         | 2.63%   |
| 0x06006705 | 1         | 2.63%   |
| 0x0600611a | 1         | 2.63%   |
| 0x05000029 | 1         | 2.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 5         | 13.16%  |
| IvyBridge   | 5         | 13.16%  |
| SandyBridge | 4         | 10.53%  |
| Haswell     | 4         | 10.53%  |
| TigerLake   | 3         | 7.89%   |
| Excavator   | 3         | 7.89%   |
| Core        | 3         | 7.89%   |
| Broadwell   | 3         | 7.89%   |
| Westmere    | 2         | 5.26%   |
| Puma        | 2         | 5.26%   |
| Skylake     | 1         | 2.63%   |
| Silvermont  | 1         | 2.63%   |
| Bobcat      | 1         | 2.63%   |
| Unknown     | 1         | 2.63%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 28        | 58.33%  |
| AMD    | 12        | 25%     |
| Nvidia | 8         | 16.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 8.93%   |
| Intel HD Graphics 5500                                                                   | 3         | 5.36%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 3.57%   |
| Intel UHD Graphics 620                                                                   | 2         | 3.57%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 3.57%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 3.57%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 3.57%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 3.57%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 3.57%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 3.57%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 3.57%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 3.57%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 3.57%   |
| Nvidia GT218M [GeForce 315M]                                                             | 1         | 1.79%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 1.79%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 1.79%   |
| Nvidia GF108M [GeForce GT 635M]                                                          | 1         | 1.79%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 1.79%   |
| Nvidia GF108M [GeForce GT 420M]                                                          | 1         | 1.79%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.79%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 1         | 1.79%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.79%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.79%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 1.79%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.79%   |
| Intel HD Graphics 620                                                                    | 1         | 1.79%   |
| Intel HD Graphics 520                                                                    | 1         | 1.79%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.79%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.79%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1         | 1.79%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 1.79%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 1         | 1.79%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 1.79%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                         | 1         | 1.79%   |
| AMD Mars XTX [Radeon HD 8790M]                                                           | 1         | 1.79%   |
| AMD Lucienne                                                                             | 1         | 1.79%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 1         | 1.79%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520/610 Mobile]                         | 1         | 1.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 18        | 47.37%  |
| 2 x AMD        | 5         | 13.16%  |
| Intel + Nvidia | 5         | 13.16%  |
| Intel + AMD    | 5         | 13.16%  |
| 1 x Nvidia     | 3         | 7.89%   |
| 1 x AMD        | 2         | 5.26%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver | Notebooks | Percent |
|--------|-----------|---------|
| Free   | 38        | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 28        | 73.68%  |
| 0.01-0.5   | 5         | 13.16%  |
| 0.51-1.0   | 3         | 7.89%   |
| 5.01-6.0   | 1         | 2.63%   |
| 1.01-2.0   | 1         | 2.63%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 10        | 27.03%  |
| Chimei Innolux          | 6         | 16.22%  |
| BOE                     | 5         | 13.51%  |
| Samsung Electronics     | 4         | 10.81%  |
| AU Optronics            | 4         | 10.81%  |
| LG Philips              | 2         | 5.41%   |
| Chi Mei Optoelectronics | 2         | 5.41%   |
| PANDA                   | 1         | 2.7%    |
| Lenovo                  | 1         | 2.7%    |
| Goldstar                | 1         | 2.7%    |
| AOC                     | 1         | 2.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch     | 1         | 2.63%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 1         | 2.63%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 1         | 2.63%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 1         | 2.63%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch     | 1         | 2.63%   |
| PANDA LCD Monitor NCP006E 1920x1080 344x194mm 15.5-inch                  | 1         | 2.63%   |
| LG Philips LCD Monitor LPLDB00 1280x800 331x207mm 15.4-inch              | 1         | 2.63%   |
| LG Philips LCD Monitor LPL1146 1280x800 331x207mm 15.4-inch              | 1         | 2.63%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 1         | 2.63%   |
| LG Display LCD Monitor LGD0470 1920x1080 345x194mm 15.6-inch             | 1         | 2.63%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch              | 1         | 2.63%   |
| LG Display LCD Monitor LGD0414 1920x1080 276x156mm 12.5-inch             | 1         | 2.63%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 1         | 2.63%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch              | 1         | 2.63%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch              | 1         | 2.63%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 1         | 2.63%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 1         | 2.63%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch              | 1         | 2.63%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 1         | 2.63%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                   | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x193mm 15.5-inch          | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 1         | 2.63%   |
| Chi Mei Optoelectronics LCD Monitor CMO1703 1440x900 367x230mm 17.1-inch | 1         | 2.63%   |
| Chi Mei Optoelectronics LCD Monitor CMO15AB 1366x768 340x190mm 15.3-inch | 1         | 2.63%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 1         | 2.63%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 1         | 2.63%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 1         | 2.63%   |
| BOE LCD Monitor BOE0661 1366x768 344x194mm 15.5-inch                     | 1         | 2.63%   |
| BOE LCD Monitor BOE065E 1920x1080 344x194mm 15.5-inch                    | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch           | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 1         | 2.63%   |
| AOC 2260WG5 AOC2260 1920x1080 477x268mm 21.5-inch                        | 1         | 2.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 20        | 54.05%  |
| 1920x1080 (FHD)  | 11        | 29.73%  |
| 1280x800 (WXGA)  | 2         | 5.41%   |
| 2160x1440        | 1         | 2.7%    |
| 1600x900 (HD+)   | 1         | 2.7%    |
| 1440x900 (WXGA+) | 1         | 2.7%    |
| 1280x1024 (SXGA) | 1         | 2.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 27        | 71.05%  |
| 14     | 3         | 7.89%   |
| 13     | 3         | 7.89%   |
| 17     | 2         | 5.26%   |
| 23     | 1         | 2.63%   |
| 22     | 1         | 2.63%   |
| 12     | 1         | 2.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 32        | 86.49%  |
| 201-300     | 2         | 5.41%   |
| 501-600     | 1         | 2.7%    |
| 401-500     | 1         | 2.7%    |
| 351-400     | 1         | 2.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 32        | 84.21%  |
| 16/10 | 4         | 10.53%  |
| 5/4   | 1         | 2.63%   |
| 3/2   | 1         | 2.63%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 27        | 71.05%  |
| 81-90          | 6         | 15.79%  |
| 201-250        | 2         | 5.26%   |
| 61-70          | 1         | 2.63%   |
| 141-150        | 1         | 2.63%   |
| 131-140        | 1         | 2.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 18        | 47.37%  |
| 121-160 | 10        | 26.32%  |
| 51-100  | 8         | 21.05%  |
| 161-240 | 2         | 5.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 36        | 94.74%  |
| 2     | 2         | 5.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 27        | 44.26%  |
| Intel                 | 14        | 22.95%  |
| Qualcomm Atheros      | 8         | 13.11%  |
| Broadcom              | 4         | 6.56%   |
| Ralink                | 3         | 4.92%   |
| ASUSTek Computer      | 2         | 3.28%   |
| Xiaomi                | 1         | 1.64%   |
| Ralink Technology     | 1         | 1.64%   |
| JMicron Technology    | 1         | 1.64%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 18        | 22.78%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 7         | 8.86%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 3         | 3.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 3         | 3.8%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 3         | 3.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 2         | 2.53%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 2         | 2.53%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 2         | 2.53%   |
| Intel Wireless 8265 / 8275                                           | 2         | 2.53%   |
| Broadcom BCM43142 802.11b/g/n                                        | 2         | 2.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                       | 1         | 1.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 1         | 1.27%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 1         | 1.27%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                      | 1         | 1.27%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                               | 1         | 1.27%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 1         | 1.27%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 1         | 1.27%   |
| Realtek RTL8152 Fast Ethernet Adapter                                | 1         | 1.27%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 1         | 1.27%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 1         | 1.27%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                            | 1         | 1.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 1         | 1.27%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                               | 1         | 1.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 1         | 1.27%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                        | 1         | 1.27%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller               | 1         | 1.27%   |
| Intel Wireless 7265                                                  | 1         | 1.27%   |
| Intel Wireless 7260                                                  | 1         | 1.27%   |
| Intel Wi-Fi 6 AX201                                                  | 1         | 1.27%   |
| Intel Ethernet Connection I217-LM                                    | 1         | 1.27%   |
| Intel Ethernet Connection (4) I219-LM                                | 1         | 1.27%   |
| Intel Ethernet Connection (3) I218-V                                 | 1         | 1.27%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 1         | 1.27%   |
| Intel Centrino Wireless-N 2230                                       | 1         | 1.27%   |
| Intel Centrino Wireless-N 130                                        | 1         | 1.27%   |
| Intel Centrino Ultimate-N 6300                                       | 1         | 1.27%   |
| Intel Centrino Advanced-N 6200                                       | 1         | 1.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 1         | 1.27%   |
| Intel 82577LC Gigabit Network Connection                             | 1         | 1.27%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile | 1         | 1.27%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 14        | 33.33%  |
| Realtek Semiconductor | 11        | 26.19%  |
| Qualcomm Atheros      | 7         | 16.67%  |
| Broadcom              | 4         | 9.52%   |
| Ralink                | 3         | 7.14%   |
| ASUSTek Computer      | 2         | 4.76%   |
| Ralink Technology     | 1         | 2.38%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 7.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 3         | 7.14%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 7.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 4.76%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 4.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 4.76%   |
| Intel Wireless 8265 / 8275                                     | 2         | 4.76%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 4.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.38%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.38%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 2.38%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 2.38%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 2.38%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 2.38%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 2.38%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 2.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 2.38%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 2.38%   |
| Intel Wireless 7265                                            | 1         | 2.38%   |
| Intel Wireless 7260                                            | 1         | 2.38%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 2.38%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 2.38%   |
| Intel Centrino Wireless-N 2230                                 | 1         | 2.38%   |
| Intel Centrino Wireless-N 130                                  | 1         | 2.38%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 2.38%   |
| Intel Centrino Advanced-N 6200                                 | 1         | 2.38%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 2.38%   |
| Broadcom BCM43225 802.11b/g/n                                  | 1         | 2.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 2.38%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                            | 1         | 2.38%   |
| ASUS 802.11ac NIC                                              | 1         | 2.38%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 26        | 72.22%  |
| Intel                 | 5         | 13.89%  |
| Qualcomm Atheros      | 2         | 5.56%   |
| Xiaomi                | 1         | 2.78%   |
| JMicron Technology    | 1         | 2.78%   |
| Broadcom              | 1         | 2.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 18        | 48.65%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 7         | 18.92%  |
| Xiaomi Mi/Redmi series (RNDIS)                                       | 1         | 2.7%    |
| Realtek RTL8152 Fast Ethernet Adapter                                | 1         | 2.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 1         | 2.7%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                               | 1         | 2.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                        | 1         | 2.7%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller               | 1         | 2.7%    |
| Intel Ethernet Connection I217-LM                                    | 1         | 2.7%    |
| Intel Ethernet Connection (4) I219-LM                                | 1         | 2.7%    |
| Intel Ethernet Connection (3) I218-V                                 | 1         | 2.7%    |
| Intel 82577LC Gigabit Network Connection                             | 1         | 2.7%    |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile | 1         | 2.7%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                      | 1         | 2.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 38        | 52.05%  |
| Ethernet | 35        | 47.95%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 34        | 82.93%  |
| Ethernet | 7         | 17.07%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 35        | 92.11%  |
| 1     | 3         | 7.89%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 35        | 92.11%  |
| Yes  | 3         | 7.89%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 9         | 28.13%  |
| Realtek Semiconductor           | 6         | 18.75%  |
| Qualcomm Atheros Communications | 4         | 12.5%   |
| Toshiba                         | 2         | 6.25%   |
| Ralink                          | 2         | 6.25%   |
| Lite-On Technology              | 2         | 6.25%   |
| Cambridge Silicon Radio         | 2         | 6.25%   |
| Realtek                         | 1         | 3.13%   |
| IMC Networks                    | 1         | 3.13%   |
| Foxconn International           | 1         | 3.13%   |
| Foxconn / Hon Hai               | 1         | 3.13%   |
| Broadcom                        | 1         | 3.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 5         | 15.63%  |
| Realtek Bluetooth Radio                             | 4         | 12.5%   |
| Ralink RT3290 Bluetooth                             | 2         | 6.25%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 6.25%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 6.25%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 6.25%   |
| Toshiba RT Bluetooth Radio                          | 1         | 3.13%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 3.13%   |
| Realtek RTL8821A Bluetooth                          | 1         | 3.13%   |
| Realtek RTL8723B Bluetooth                          | 1         | 3.13%   |
| Realtek Bluetooth Radio                             | 1         | 3.13%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 3.13%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 3.13%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 3.13%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 3.13%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 3.13%   |
| Intel AX201 Bluetooth                               | 1         | 3.13%   |
| IMC Networks Bluetooth Device                       | 1         | 3.13%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 3.13%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 3.13%   |
| Broadcom HP Portable Valentine                      | 1         | 3.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 31        | 72.09%  |
| AMD                   | 7         | 16.28%  |
| Nvidia                | 4         | 9.3%    |
| Barco Display Systems | 1         | 2.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 10.71%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 4         | 7.14%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 5.36%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 5.36%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 5.36%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 5.36%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 5.36%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 5.36%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 5.36%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 3.57%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 3.57%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 3.57%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 3.57%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 3.57%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 3.57%   |
| AMD High Definition Audio Controller                                                              | 2         | 3.57%   |
| AMD FCH Azalia Controller                                                                         | 2         | 3.57%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 1.79%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.79%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.79%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.79%   |
| Barco Display Systems USBGH520-ENC                                                                | 1         | 1.79%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.79%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 1.79%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.79%   |

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
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s          | 1         | 6.67%   |
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


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 7         | 50%     |
| 4096  | 3         | 21.43%  |
| 2048  | 3         | 21.43%  |
| 16384 | 1         | 7.14%   |

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
| Chicony Electronics                    | 12        | 37.5%   |
| Realtek Semiconductor                  | 3         | 9.38%   |
| Microdia                               | 3         | 9.38%   |
| IMC Networks                           | 3         | 9.38%   |
| Luxvisions Innotech Limited            | 2         | 6.25%   |
| Suyin                                  | 1         | 3.13%   |
| Silicon Motion                         | 1         | 3.13%   |
| Lite-On Technology                     | 1         | 3.13%   |
| Foxconn / Hon Hai                      | 1         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.13%   |
| Bison Electronics                      | 1         | 3.13%   |
| ALi                                    | 1         | 3.13%   |
| Alcor Micro                            | 1         | 3.13%   |
| Acer                                   | 1         | 3.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Lenovo EasyCamera                           | 2         | 6.25%   |
| Microdia Integrated_Webcam_HD                       | 2         | 6.25%   |
| Chicony Integrated Camera                           | 2         | 6.25%   |
| Chicony EasyCamera                                  | 2         | 6.25%   |
| Suyin HP Webcam                                     | 1         | 3.13%   |
| Silicon Motion WebCam SC-0311139N                   | 1         | 3.13%   |
| Realtek HP Truevision HD integrated webcam          | 1         | 3.13%   |
| Microdia Laptop_Integrated_Webcam_HD                | 1         | 3.13%   |
| Luxvisions Innotech Limited Integrated Camera       | 1         | 3.13%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 3.13%   |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 3.13%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 3.13%   |
| IMC Networks Lenovo EasyCamera                      | 1         | 3.13%   |
| IMC Networks EasyCamera                             | 1         | 3.13%   |
| Foxconn / Hon Hai USB2.0 Camera                     | 1         | 3.13%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 3.13%   |
| Chicony USB2.0 Camera                               | 1         | 3.13%   |
| Chicony USB 2.0 Camera                              | 1         | 3.13%   |
| Chicony HP Truevision HD                            | 1         | 3.13%   |
| Chicony Gateway USB 2.0 Webcam                      | 1         | 3.13%   |
| Chicony Front Camera                                | 1         | 3.13%   |
| Chicony CNF9055 Toshiba Webcam                      | 1         | 3.13%   |
| Chicony CNA7157                                     | 1         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 1         | 3.13%   |
| Bison SunplusIT Integrated Camera                   | 1         | 3.13%   |
| ALi Gateway Webcam                                  | 1         | 3.13%   |
| Alcor Micro TOSHIBA Web Camera - MP                 | 1         | 3.13%   |
| Acer EasyCamera                                     | 1         | 3.13%   |

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
| 0     | 29        | 74.36%  |
| 1     | 7         | 17.95%  |
| 2     | 3         | 7.69%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Graphics card      | 3         | 23.08%  |
| Fingerprint reader | 3         | 23.08%  |
| Bluetooth          | 3         | 23.08%  |
| Camera             | 2         | 15.38%  |
| Net/wireless       | 1         | 7.69%   |
| Chipcard           | 1         | 7.69%   |

