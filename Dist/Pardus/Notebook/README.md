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

Total: 59

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 830 G5            | [c9ac7b8022](https://linux-hardware.org/?probe=c9ac7b8022) | Dec 28, 2023 |
| HP            | EliteBook 820 G2            | [a32eb9fe02](https://linux-hardware.org/?probe=a32eb9fe02) | Sep 28, 2023 |
| Casper        | EXCALIBUR G770              | [9224e20101](https://linux-hardware.org/?probe=9224e20101) | Sep 01, 2023 |
| Toshiba       | Satellite L755              | [9e9caad8ea](https://linux-hardware.org/?probe=9e9caad8ea) | Jul 31, 2023 |
| ASUSTek       | X550DP                      | [4cfcff7d7e](https://linux-hardware.org/?probe=4cfcff7d7e) | Jul 10, 2023 |
| Toshiba       | Satellite L755              | [d1a5adf1ef](https://linux-hardware.org/?probe=d1a5adf1ef) | Jul 06, 2023 |
| Toshiba       | Satellite L755              | [cda93de5a6](https://linux-hardware.org/?probe=cda93de5a6) | Jul 05, 2023 |
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
| Pardus 21.4   | 6         | 13.64%  |
| Pardus 21.3   | 5         | 11.36%  |
| Pardus 21.1   | 5         | 11.36%  |
| Pardus 21.5   | 4         | 9.09%   |
| Pardus 21.2   | 4         | 9.09%   |
| Pardus 21.0   | 3         | 6.82%   |
| Pardus 19.5   | 3         | 6.82%   |
| Pardus 19.3   | 3         | 6.82%   |
| Pardus 23.0   | 2         | 4.55%   |
| Pardus 19.4-1 | 2         | 4.55%   |
| Pardus 19.2   | 2         | 4.55%   |
| Pardus 19.1   | 2         | 4.55%   |
| Pardus 19.0   | 2         | 4.55%   |
| Pardus 19.4   | 1         | 2.27%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Pardus | 42        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Notebooks | Percent |
|---------------------------|-----------|---------|
| 5.10.0-21-amd64           | 5         | 11.11%  |
| 5.10.0-19-amd64           | 4         | 8.89%   |
| 5.10.0-13-amd64           | 3         | 6.67%   |
| 5.10.0-11-amd64           | 3         | 6.67%   |
| 4.19.0-6-amd64            | 3         | 6.67%   |
| 4.19.0-10-amd64           | 3         | 6.67%   |
| 5.10.0-9-amd64            | 2         | 4.44%   |
| 5.10.0-23-amd64           | 2         | 4.44%   |
| 5.10.0-10-amd64           | 2         | 4.44%   |
| 4.19.0-13-amd64           | 2         | 4.44%   |
| 6.1.0-13-amd64            | 1         | 2.22%   |
| 6.1.0-11-amd64            | 1         | 2.22%   |
| 6.0.11-x64v2-rt14-xanmod1 | 1         | 2.22%   |
| 5.9.0-0.bpo.2-amd64       | 1         | 2.22%   |
| 5.4.0-0.bpo.3-amd64       | 1         | 2.22%   |
| 5.10.0-8-amd64            | 1         | 2.22%   |
| 5.10.0-25-amd64           | 1         | 2.22%   |
| 5.10.0-20-amd64           | 1         | 2.22%   |
| 5.10.0-17-amd64           | 1         | 2.22%   |
| 5.10.0-16-amd64           | 1         | 2.22%   |
| 5.10.0-14-amd64           | 1         | 2.22%   |
| 5.10.0-0.bpo.8-amd64      | 1         | 2.22%   |
| 4.19.0-8-amd64            | 1         | 2.22%   |
| 4.19.0-5-amd64            | 1         | 2.22%   |
| 4.19.0-19-amd64           | 1         | 2.22%   |
| 4.19.0-16-amd64           | 1         | 2.22%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 27        | 62.79%  |
| 4.19.0  | 11        | 25.58%  |
| 6.1.0   | 2         | 4.65%   |
| 6.0.11  | 1         | 2.33%   |
| 5.9.0   | 1         | 2.33%   |
| 5.4.0   | 1         | 2.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 27        | 62.79%  |
| 4.19    | 11        | 25.58%  |
| 6.1     | 2         | 4.65%   |
| 6.0     | 1         | 2.33%   |
| 5.9     | 1         | 2.33%   |
| 5.4     | 1         | 2.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 42        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| XFCE    | 25        | 59.52%  |
| GNOME   | 14        | 33.33%  |
| Unknown | 2         | 4.76%   |
| KDE5    | 1         | 2.38%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 42        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 26        | 61.9%   |
| TDM     | 6         | 14.29%  |
| LightDM | 5         | 11.9%   |
| GDM     | 4         | 9.52%   |
| GDM3    | 1         | 2.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| tr_TR   | 32        | 76.19%  |
| en_US   | 3         | 7.14%   |
| Unknown | 3         | 7.14%   |
| pt_BR   | 1         | 2.38%   |
| hu_HU   | 1         | 2.38%   |
| fur_IT  | 1         | 2.38%   |
| en_GB   | 1         | 2.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 30        | 69.77%  |
| EFI  | 13        | 30.23%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 40        | 95.24%  |
| Overlay | 2         | 4.76%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 27        | 64.29%  |
| GPT     | 12        | 28.57%  |
| MBR     | 3         | 7.14%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 38        | 90.48%  |
| Yes       | 4         | 9.52%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 34        | 80.95%  |
| Yes       | 8         | 19.05%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 11        | 26.19%  |
| Hewlett-Packard     | 8         | 19.05%  |
| Toshiba             | 4         | 9.52%   |
| Dell                | 3         | 7.14%   |
| ASUSTek Computer    | 3         | 7.14%   |
| Sony                | 2         | 4.76%   |
| Packard Bell        | 2         | 4.76%   |
| Acer                | 2         | 4.76%   |
| TUXEDO              | 1         | 2.38%   |
| Samsung Electronics | 1         | 2.38%   |
| Philco              | 1         | 2.38%   |
| Olidata             | 1         | 2.38%   |
| HUAWEI              | 1         | 2.38%   |
| Clevo               | 1         | 2.38%   |
| Casper              | 1         | 2.38%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Toshiba Satellite L755                     | 1         | 2.38%   |
| Toshiba Satellite C855-1VM                 | 1         | 2.38%   |
| Toshiba Satellite C660                     | 1         | 2.38%   |
| Toshiba PORTEGE M780                       | 1         | 2.38%   |
| Sony SVF1521QSTB                           | 1         | 2.38%   |
| Sony SVE14A2V2ES                           | 1         | 2.38%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 2.38%   |
| Philco 14F                                 | 1         | 2.38%   |
| Packard Bell EasyNote_GN45                 | 1         | 2.38%   |
| Packard Bell EasyNote ENTG81BA             | 1         | 2.38%   |
| Olidata T7700                              | 1         | 2.38%   |
| Lenovo V145-15AST 81MT                     | 1         | 2.38%   |
| Lenovo V110-15ISK 80TL                     | 1         | 2.38%   |
| Lenovo ThinkPad T480 20L6S2S800            | 1         | 2.38%   |
| Lenovo ThinkPad T450 20BUS39Y00            | 1         | 2.38%   |
| Lenovo ThinkPad S1 Yoga 20CD0034TX         | 1         | 2.38%   |
| Lenovo ThinkPad E15 Gen 2 20TD0047TX       | 1         | 2.38%   |
| Lenovo IdeaPad-510-15IKB 80SV              | 1         | 2.38%   |
| Lenovo IdeaPad 320-15IKB 81BT              | 1         | 2.38%   |
| Lenovo IdeaPad 100-15IBD 80QQ              | 1         | 2.38%   |
| Lenovo G510 20238                          | 1         | 2.38%   |
| Lenovo G50-45 80E3                         | 1         | 2.38%   |
| HUAWEI KLVL-WXXW                           | 1         | 2.38%   |
| HP ProBook 4540s                           | 1         | 2.38%   |
| HP Pavilion 15                             | 1         | 2.38%   |
| HP Laptop 15-dw3xxx                        | 1         | 2.38%   |
| HP EliteBook 830 G5                        | 1         | 2.38%   |
| HP EliteBook 820 G2                        | 1         | 2.38%   |
| HP 530                                     | 1         | 2.38%   |
| HP 250 G3                                  | 1         | 2.38%   |
| HP 15                                      | 1         | 2.38%   |
| Dell Vostro 5502                           | 1         | 2.38%   |
| Dell Latitude E6540                        | 1         | 2.38%   |
| Dell G5 5587                               | 1         | 2.38%   |
| Clevo W251EFQ/W270EFQ                      | 1         | 2.38%   |
| Casper EXCALIBUR G770                      | 1         | 2.38%   |
| ASUS X555YI                                | 1         | 2.38%   |
| ASUS X550DP                                | 1         | 2.38%   |
| ASUS E402BP                                | 1         | 2.38%   |
| Acer Aspire A515-41G                       | 1         | 2.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 4         | 9.52%   |
| Toshiba Satellite        | 3         | 7.14%   |
| Packard Bell EasyNote    | 2         | 4.76%   |
| Lenovo IdeaPad           | 2         | 4.76%   |
| HP EliteBook             | 2         | 4.76%   |
| Acer Aspire              | 2         | 4.76%   |
| Toshiba PORTEGE          | 1         | 2.38%   |
| Sony SVF1521QSTB         | 1         | 2.38%   |
| Sony SVE14A2V2ES         | 1         | 2.38%   |
| Samsung 300E4A           | 1         | 2.38%   |
| Philco 14F               | 1         | 2.38%   |
| Olidata T7700            | 1         | 2.38%   |
| Lenovo V145-15AST        | 1         | 2.38%   |
| Lenovo V110-15ISK        | 1         | 2.38%   |
| Lenovo IdeaPad-510-15IKB | 1         | 2.38%   |
| Lenovo G510              | 1         | 2.38%   |
| Lenovo G50-45            | 1         | 2.38%   |
| HUAWEI KLVL-WXXW         | 1         | 2.38%   |
| HP ProBook               | 1         | 2.38%   |
| HP Pavilion              | 1         | 2.38%   |
| HP Laptop                | 1         | 2.38%   |
| HP 530                   | 1         | 2.38%   |
| HP 250                   | 1         | 2.38%   |
| HP 15                    | 1         | 2.38%   |
| Dell Vostro              | 1         | 2.38%   |
| Dell Latitude            | 1         | 2.38%   |
| Dell G5                  | 1         | 2.38%   |
| Clevo W251EFQ            | 1         | 2.38%   |
| Casper EXCALIBUR         | 1         | 2.38%   |
| ASUS X555YI              | 1         | 2.38%   |
| ASUS X550DP              | 1         | 2.38%   |
| ASUS E402BP              | 1         | 2.38%   |
| Unknown                  | 1         | 2.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 8         | 19.05%  |
| 2018 | 5         | 11.9%   |
| 2015 | 4         | 9.52%   |
| 2014 | 4         | 9.52%   |
| 2020 | 3         | 7.14%   |
| 2011 | 3         | 7.14%   |
| 2010 | 3         | 7.14%   |
| 2021 | 2         | 4.76%   |
| 2019 | 2         | 4.76%   |
| 2017 | 2         | 4.76%   |
| 2012 | 2         | 4.76%   |
| 2016 | 1         | 2.38%   |
| 2008 | 1         | 2.38%   |
| 2007 | 1         | 2.38%   |
| 2006 | 1         | 2.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 42        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 42        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 42        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 13        | 30.95%  |
| 3.01-4.0   | 13        | 30.95%  |
| 8.01-16.0  | 8         | 19.05%  |
| 16.01-24.0 | 5         | 11.9%   |
| 1.01-2.0   | 2         | 4.76%   |
| 2.01-3.0   | 1         | 2.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 20        | 43.48%  |
| 2.01-3.0 | 13        | 28.26%  |
| 3.01-4.0 | 8         | 17.39%  |
| 4.01-8.0 | 4         | 8.7%    |
| 0.51-1.0 | 1         | 2.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 28        | 66.67%  |
| 2      | 12        | 28.57%  |
| 3      | 2         | 4.76%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 21        | 50%     |
| No        | 21        | 50%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 92.86%  |
| No        | 3         | 7.14%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 42        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 35        | 83.33%  |
| No        | 7         | 16.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| Turkey     | 34        | 80.95%  |
| Germany    | 2         | 4.76%   |
| UK         | 1         | 2.38%   |
| Sweden     | 1         | 2.38%   |
| Poland     | 1         | 2.38%   |
| Italy      | 1         | 2.38%   |
| Brazil     | 1         | 2.38%   |
| Azerbaijan | 1         | 2.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Istanbul             | 14        | 31.82%  |
| Ankara               | 6         | 13.64%  |
| Izmir                | 5         | 11.36%  |
| Çanakkale           | 2         | 4.55%   |
| Serik                | 1         | 2.27%   |
| Sao Gabriel          | 1         | 2.27%   |
| London               | 1         | 2.27%   |
| Landskrona           | 1         | 2.27%   |
| Kołobrzeg           | 1         | 2.27%   |
| Konya                | 1         | 2.27%   |
| Kirchheim unter Teck | 1         | 2.27%   |
| Gaziantep            | 1         | 2.27%   |
| Esenyurt             | 1         | 2.27%   |
| Castrop-Rauxel       | 1         | 2.27%   |
| Bursa                | 1         | 2.27%   |
| Bolzano              | 1         | 2.27%   |
| Balıkesir           | 1         | 2.27%   |
| Baku                 | 1         | 2.27%   |
| Aydin                | 1         | 2.27%   |
| Artvin               | 1         | 2.27%   |
| Antalya              | 1         | 2.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 8         | 10     | 14.81%  |
| Seagate                     | 8         | 8      | 14.81%  |
| Samsung Electronics         | 8         | 9      | 14.81%  |
| SanDisk                     | 4         | 4      | 7.41%   |
| Toshiba                     | 2         | 3      | 3.7%    |
| SK hynix                    | 2         | 2      | 3.7%    |
| Kingston                    | 2         | 3      | 3.7%    |
| Hitachi                     | 2         | 2      | 3.7%    |
| HGST                        | 2         | 2      | 3.7%    |
| USB3.0                      | 1         | 1      | 1.85%   |
| SPCC                        | 1         | 1      | 1.85%   |
| Silicon Motion              | 1         | 1      | 1.85%   |
| Phison                      | 1         | 1      | 1.85%   |
| Micron/Crucial Technology   | 1         | 1      | 1.85%   |
| Micron Technology           | 1         | 2      | 1.85%   |
| MAXIO Technology (Hangzhou) | 1         | 2      | 1.85%   |
| LITEON                      | 1         | 1      | 1.85%   |
| Lexar                       | 1         | 1      | 1.85%   |
| KIOXIA-EXCERIA              | 1         | 1      | 1.85%   |
| Kingston Technology Company | 1         | 1      | 1.85%   |
| KingSpec                    | 1         | 1      | 1.85%   |
| Intenso                     | 1         | 2      | 1.85%   |
| Initio                      | 1         | 1      | 1.85%   |
| addlink                     | 1         | 1      | 1.85%   |
| Unknown                     | 1         | 1      | 1.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| HGST HTS545050A7E680 500GB                         | 2         | 3.64%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD                   | 1         | 1.82%   |
| WDC WD5000LPVX-55V0TT0 500GB                       | 1         | 1.82%   |
| WDC WD5000LPCX-60VHAT0 500GB                       | 1         | 1.82%   |
| WDC WD5000LPCX-21VHAT0 500GB                       | 1         | 1.82%   |
| WDC WD3200BPVT-35JJ5T0 320GB                       | 1         | 1.82%   |
| WDC WD2500BEVS-00UST0 250GB                        | 1         | 1.82%   |
| WDC WD10JPVX-60JC3T0 1TB                           | 1         | 1.82%   |
| WDC WD10JPCX-24UE4T0 1TB                           | 1         | 1.82%   |
| USB3.0 Super Speed 1TB                             | 1         | 1.82%   |
| Toshiba MQ01ABD075 752GB                           | 1         | 1.82%   |
| Toshiba MK6475GSX 640GB                            | 1         | 1.82%   |
| SPCC Solid State Disk 512GB                        | 1         | 1.82%   |
| SK hynix SC311 SATA 256GB SSD                      | 1         | 1.82%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB            | 1         | 1.82%   |
| Silicon Motion Longline SSD 512GB                  | 1         | 1.82%   |
| Seagate ST9500325AS 500GB                          | 1         | 1.82%   |
| Seagate ST9120822AS 120GB                          | 1         | 1.82%   |
| Seagate ST750LM022 HN-M750MBB 752GB                | 1         | 1.82%   |
| Seagate ST500LM000-1EJ162 500GB                    | 1         | 1.82%   |
| Seagate ST1000LM035-1RK172 1TB                     | 1         | 1.82%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 1         | 1.82%   |
| Seagate Expansion 2TB                              | 1         | 1.82%   |
| Seagate BarraCuda Q1 SSD ZA480CV10001 480GB        | 1         | 1.82%   |
| SanDisk SSD U110 16GB                              | 1         | 1.82%   |
| SanDisk SSD PLUS 240GB                             | 1         | 1.82%   |
| SanDisk SSD PLUS 120GB                             | 1         | 1.82%   |
| SanDisk SDSSDA480G 480GB                           | 1         | 1.82%   |
| Samsung SSD 860 EVO 500GB                          | 1         | 1.82%   |
| Samsung SSD 850 PRO 256GB                          | 1         | 1.82%   |
| Samsung MZVLB256HAHQ-000H1 256GB                   | 1         | 1.82%   |
| Samsung MZMTD256HAGM-000L1 256GB SSD               | 1         | 1.82%   |
| Samsung MZALQ256HAJD-000L1 256GB                   | 1         | 1.82%   |
| Samsung MZ7LN128HAHQ-000L2 128GB SSD               | 1         | 1.82%   |
| Samsung MZ7LF192HCGS-000L1 192GB SSD               | 1         | 1.82%   |
| Samsung HM250HI 250GB                              | 1         | 1.82%   |
| Phison 311CD0512GB                                 | 1         | 1.82%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                | 1         | 1.82%   |
| Micron 1300_MTFDDAK512TDL 512GB SSD                | 1         | 1.82%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 256GB | 1         | 1.82%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 9      | 30.43%  |
| Seagate             | 7         | 7      | 30.43%  |
| Toshiba             | 2         | 3      | 8.7%    |
| Hitachi             | 2         | 2      | 8.7%    |
| HGST                | 2         | 2      | 8.7%    |
| USB3.0              | 1         | 1      | 4.35%   |
| Samsung Electronics | 1         | 1      | 4.35%   |
| Initio              | 1         | 1      | 4.35%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 6      | 23.81%  |
| SanDisk             | 4         | 4      | 19.05%  |
| Kingston            | 2         | 3      | 9.52%   |
| WDC                 | 1         | 1      | 4.76%   |
| SPCC                | 1         | 1      | 4.76%   |
| SK hynix            | 1         | 1      | 4.76%   |
| Seagate             | 1         | 1      | 4.76%   |
| Micron Technology   | 1         | 2      | 4.76%   |
| LITEON              | 1         | 1      | 4.76%   |
| Lexar               | 1         | 1      | 4.76%   |
| KIOXIA-EXCERIA      | 1         | 1      | 4.76%   |
| KingSpec            | 1         | 1      | 4.76%   |
| Intenso             | 1         | 2      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 22        | 26     | 44.9%   |
| SSD     | 18        | 25     | 36.73%  |
| NVMe    | 7         | 9      | 14.29%  |
| Unknown | 2         | 2      | 4.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 36        | 50     | 80%     |
| NVMe | 7         | 9      | 15.56%  |
| SAS  | 2         | 3      | 4.44%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 29        | 36     | 72.5%   |
| 0.51-1.0   | 10        | 14     | 25%     |
| 1.01-2.0   | 1         | 1      | 2.5%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 20        | 46.51%  |
| 251-500    | 13        | 30.23%  |
| 501-1000   | 6         | 13.95%  |
| 21-50      | 2         | 4.65%   |
| 51-100     | 2         | 4.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 18        | 41.86%  |
| 21-50   | 10        | 23.26%  |
| 51-100  | 9         | 20.93%  |
| 101-250 | 5         | 11.63%  |
| 251-500 | 1         | 2.33%   |

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
| Detected | 28        | 41     | 63.64%  |
| Works    | 13        | 18     | 29.55%  |
| Malfunc  | 2         | 2      | 4.55%   |
| Failed   | 1         | 1      | 2.27%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 30        | 66.67%  |
| AMD                         | 7         | 15.56%  |
| Samsung Electronics         | 2         | 4.44%   |
| SK hynix                    | 1         | 2.22%   |
| Silicon Motion              | 1         | 2.22%   |
| Phison Electronics          | 1         | 2.22%   |
| Micron/Crucial Technology   | 1         | 2.22%   |
| MAXIO Technology (Hangzhou) | 1         | 2.22%   |
| Kingston Technology Company | 1         | 2.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 6         | 12.24%  |
| AMD FCH SATA Controller [AHCI mode]                                                    | 6         | 12.24%  |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 4         | 8.16%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 3         | 6.12%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 2         | 4.08%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 2         | 4.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 2         | 4.08%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 2         | 4.08%   |
| SK hynix BC511 NVMe SSD                                                                | 1         | 2.04%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                      | 1         | 2.04%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 1         | 2.04%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                            | 1         | 2.04%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                    | 1         | 2.04%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                   | 1         | 2.04%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                           | 1         | 2.04%   |
| Kingston Company OM3PDP3 NVMe SSD                                                      | 1         | 2.04%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 1         | 2.04%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 1         | 2.04%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 1         | 2.04%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 1         | 2.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 1         | 2.04%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 1         | 2.04%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 1         | 2.04%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 2.04%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 2.04%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 2.04%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 2.04%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 2.04%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 1         | 2.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 1         | 2.04%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 34        | 73.91%  |
| NVMe | 7         | 15.22%  |
| IDE  | 4         | 8.7%    |
| RAID | 1         | 2.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 34        | 80.95%  |
| AMD    | 8         | 19.05%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-3630QM CPU @ 2.40GHz              | 2         | 4.76%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 2         | 4.76%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 2         | 4.76%   |
| Intel Core i3 CPU M 370 @ 2.40GHz               | 2         | 4.76%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 2         | 4.76%   |
| Intel Pentium CPU B960 @ 2.20GHz                | 1         | 2.38%   |
| Intel Pentium CPU B950 @ 2.10GHz                | 1         | 2.38%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 1         | 2.38%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 2.38%   |
| Intel Core i7-5500U CPU @ 2.40GHz               | 1         | 2.38%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz              | 1         | 2.38%   |
| Intel Core i7-3632QM CPU @ 2.20GHz              | 1         | 2.38%   |
| Intel Core i7-2670QM CPU @ 2.20GHz              | 1         | 2.38%   |
| Intel Core i5-8350U CPU @ 1.70GHz               | 1         | 2.38%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 1         | 2.38%   |
| Intel Core i5-4200M CPU @ 2.50GHz               | 1         | 2.38%   |
| Intel Core i5-3230M CPU @ 2.60GHz               | 1         | 2.38%   |
| Intel Core i5-10300H CPU @ 2.50GHz              | 1         | 2.38%   |
| Intel Core i3-6006U CPU @ 2.00GHz               | 1         | 2.38%   |
| Intel Core i3-5005U CPU @ 2.00GHz               | 1         | 2.38%   |
| Intel Core i3-4010U CPU @ 1.70GHz               | 1         | 2.38%   |
| Intel Core i3-4005U CPU @ 1.70GHz               | 1         | 2.38%   |
| Intel Core i3-3227U CPU @ 1.90GHz               | 1         | 2.38%   |
| Intel Core i3-2310M CPU @ 2.10GHz               | 1         | 2.38%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz            | 1         | 2.38%   |
| Intel Core 2 CPU T5600 @ 1.83GHz                | 1         | 2.38%   |
| Intel Core 2 CPU T5200 @ 1.60GHz                | 1         | 2.38%   |
| Intel Celeron CPU N3050 @ 1.60GHz               | 1         | 2.38%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz         | 1         | 2.38%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 1         | 2.38%   |
| AMD C-50 Processor                              | 1         | 2.38%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G    | 1         | 2.38%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G    | 1         | 2.38%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics     | 1         | 2.38%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics     | 1         | 2.38%   |
| AMD A10-9620P RADEON R5, 10 COMPUTE CORES 4C+6G | 1         | 2.38%   |
| AMD A10-5750M APU with Radeon HD Graphics       | 1         | 2.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 9         | 21.43%  |
| Intel Core i7    | 8         | 19.05%  |
| Intel Core i3    | 8         | 19.05%  |
| Other            | 5         | 11.9%   |
| Intel Pentium    | 2         | 4.76%   |
| Intel Core 2     | 2         | 4.76%   |
| AMD A8           | 2         | 4.76%   |
| AMD A10          | 2         | 4.76%   |
| Intel Core 2 Duo | 1         | 2.38%   |
| Intel Celeron    | 1         | 2.38%   |
| AMD Ryzen 5      | 1         | 2.38%   |
| AMD C-50         | 1         | 2.38%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 26        | 61.9%   |
| 4      | 14        | 33.33%  |
| 6      | 2         | 4.76%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 42        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 31        | 73.81%  |
| 1      | 11        | 26.19%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 42        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 59.52%  |
| 0x306a9    | 3         | 7.14%   |
| 0x306d4    | 2         | 4.76%   |
| 0x07030105 | 2         | 4.76%   |
| 0x906ea    | 1         | 2.38%   |
| 0x806ea    | 1         | 2.38%   |
| 0x806c1    | 1         | 2.38%   |
| 0x6f6      | 1         | 2.38%   |
| 0x406e3    | 1         | 2.38%   |
| 0x206a7    | 1         | 2.38%   |
| 0x08608102 | 1         | 2.38%   |
| 0x06006705 | 1         | 2.38%   |
| 0x0600611a | 1         | 2.38%   |
| 0x05000029 | 1         | 2.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 6         | 14.29%  |
| IvyBridge   | 5         | 11.9%   |
| SandyBridge | 4         | 9.52%   |
| Haswell     | 4         | 9.52%   |
| Broadwell   | 4         | 9.52%   |
| TigerLake   | 3         | 7.14%   |
| Excavator   | 3         | 7.14%   |
| Core        | 3         | 7.14%   |
| Westmere    | 2         | 4.76%   |
| Puma        | 2         | 4.76%   |
| Skylake     | 1         | 2.38%   |
| Silvermont  | 1         | 2.38%   |
| Piledriver  | 1         | 2.38%   |
| CometLake   | 1         | 2.38%   |
| Bobcat      | 1         | 2.38%   |
| Unknown     | 1         | 2.38%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 31        | 58.49%  |
| AMD    | 13        | 24.53%  |
| Nvidia | 9         | 16.98%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 8.06%   |
| Intel HD Graphics 5500                                                                   | 4         | 6.45%   |
| Intel UHD Graphics 620                                                                   | 3         | 4.84%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 4.84%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 3.23%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 3.23%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 3.23%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 3.23%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 3.23%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 3.23%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 3.23%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 3.23%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 3.23%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 1.61%   |
| Nvidia GT218M [GeForce 315M]                                                             | 1         | 1.61%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 1.61%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 1.61%   |
| Nvidia GF108M [GeForce GT 635M]                                                          | 1         | 1.61%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 1.61%   |
| Nvidia GF108M [GeForce GT 420M]                                                          | 1         | 1.61%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.61%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 1         | 1.61%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.61%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.61%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 1.61%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.61%   |
| Intel HD Graphics 620                                                                    | 1         | 1.61%   |
| Intel HD Graphics 520                                                                    | 1         | 1.61%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.61%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.61%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.61%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1         | 1.61%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 1.61%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 1         | 1.61%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 1.61%   |
| AMD Richland [Radeon HD 8650G]                                                           | 1         | 1.61%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                         | 1         | 1.61%   |
| AMD Mars XTX [Radeon HD 8790M]                                                           | 1         | 1.61%   |
| AMD Lucienne                                                                             | 1         | 1.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 20        | 47.62%  |
| 2 x AMD        | 6         | 14.29%  |
| Intel + Nvidia | 6         | 14.29%  |
| Intel + AMD    | 5         | 11.9%   |
| 1 x Nvidia     | 3         | 7.14%   |
| 1 x AMD        | 2         | 4.76%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver | Notebooks | Percent |
|--------|-----------|---------|
| Free   | 42        | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 33        | 76.74%  |
| 0.01-0.5   | 5         | 11.63%  |
| 0.51-1.0   | 3         | 6.98%   |
| 5.01-6.0   | 1         | 2.33%   |
| 1.01-2.0   | 1         | 2.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 11        | 26.83%  |
| Chimei Innolux          | 7         | 17.07%  |
| BOE                     | 6         | 14.63%  |
| AU Optronics            | 5         | 12.2%   |
| Samsung Electronics     | 4         | 9.76%   |
| LG Philips              | 2         | 4.88%   |
| Chi Mei Optoelectronics | 2         | 4.88%   |
| PANDA                   | 1         | 2.44%   |
| Lenovo                  | 1         | 2.44%   |
| Goldstar                | 1         | 2.44%   |
| AOC                     | 1         | 2.44%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM01B7 1280x1024 340x270mm 17.1-inch     | 1         | 2.38%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 1         | 2.38%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 1         | 2.38%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 1         | 2.38%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch     | 1         | 2.38%   |
| PANDA LCD Monitor NCP006E 1920x1080 344x194mm 15.5-inch                  | 1         | 2.38%   |
| LG Philips LCD Monitor LPLDB00 1280x800 331x207mm 15.4-inch              | 1         | 2.38%   |
| LG Philips LCD Monitor LPL1146 1280x800 331x207mm 15.4-inch              | 1         | 2.38%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 1         | 2.38%   |
| LG Display LCD Monitor LGD048A 1920x1080 276x156mm 12.5-inch             | 1         | 2.38%   |
| LG Display LCD Monitor LGD0470 1920x1080 345x194mm 15.6-inch             | 1         | 2.38%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch              | 1         | 2.38%   |
| LG Display LCD Monitor LGD0414 1920x1080 276x156mm 12.5-inch             | 1         | 2.38%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 1         | 2.38%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch              | 1         | 2.38%   |
| LG Display LCD Monitor LGD033F 1366x768 309x174mm 14.0-inch              | 1         | 2.38%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 1         | 2.38%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 1         | 2.38%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch              | 1         | 2.38%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 1         | 2.38%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                   | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x194mm 15.5-inch          | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 1         | 2.38%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 1         | 2.38%   |
| Chi Mei Optoelectronics LCD Monitor CMO1703 1440x900 367x230mm 17.1-inch | 1         | 2.38%   |
| Chi Mei Optoelectronics LCD Monitor CMO15AB 1366x768 340x190mm 15.3-inch | 1         | 2.38%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 1         | 2.38%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 1         | 2.38%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 1         | 2.38%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 1         | 2.38%   |
| BOE LCD Monitor BOE0661 1366x768 344x194mm 15.5-inch                     | 1         | 2.38%   |
| BOE LCD Monitor BOE065E 1920x1080 344x194mm 15.5-inch                    | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO472D 1920x1080 293x165mm 13.2-inch           | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 1         | 2.38%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch           | 1         | 2.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 21        | 51.22%  |
| 1920x1080 (FHD)  | 14        | 34.15%  |
| 1280x800 (WXGA)  | 2         | 4.88%   |
| 2160x1440        | 1         | 2.44%   |
| 1600x900 (HD+)   | 1         | 2.44%   |
| 1440x900 (WXGA+) | 1         | 2.44%   |
| 1280x1024 (SXGA) | 1         | 2.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 29        | 69.05%  |
| 13     | 4         | 9.52%   |
| 14     | 3         | 7.14%   |
| 17     | 2         | 4.76%   |
| 12     | 2         | 4.76%   |
| 23     | 1         | 2.38%   |
| 22     | 1         | 2.38%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 34        | 82.93%  |
| 201-300     | 4         | 9.76%   |
| 501-600     | 1         | 2.44%   |
| 401-500     | 1         | 2.44%   |
| 351-400     | 1         | 2.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 36        | 85.71%  |
| 16/10 | 4         | 9.52%   |
| 5/4   | 1         | 2.38%   |
| 3/2   | 1         | 2.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 29        | 69.05%  |
| 81-90          | 6         | 14.29%  |
| 61-70          | 2         | 4.76%   |
| 201-250        | 2         | 4.76%   |
| 71-80          | 1         | 2.38%   |
| 141-150        | 1         | 2.38%   |
| 131-140        | 1         | 2.38%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 18        | 42.86%  |
| 121-160 | 11        | 26.19%  |
| 51-100  | 9         | 21.43%  |
| 161-240 | 4         | 9.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 40        | 95.24%  |
| 2     | 2         | 4.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 29        | 43.28%  |
| Intel                 | 17        | 25.37%  |
| Qualcomm Atheros      | 9         | 13.43%  |
| Broadcom              | 4         | 5.97%   |
| Ralink                | 3         | 4.48%   |
| ASUSTek Computer      | 2         | 2.99%   |
| Xiaomi                | 1         | 1.49%   |
| Ralink Technology     | 1         | 1.49%   |
| JMicron Technology    | 1         | 1.49%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20        | 22.99%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 8.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 3.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 3.45%   |
| Intel Wireless 8265 / 8275                                        | 3         | 3.45%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 3.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 2.3%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 2.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 2.3%    |
| Intel Wireless 7265                                               | 2         | 2.3%    |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 2.3%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.15%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.15%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 1.15%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 1.15%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 1.15%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 1.15%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.15%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.15%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 1.15%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1         | 1.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.15%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.15%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 1.15%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.15%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.15%   |
| Intel Wireless 7260                                               | 1         | 1.15%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.15%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.15%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.15%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.15%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 1.15%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.15%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 1.15%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.15%   |
| Intel Centrino Wireless-N 2230                                    | 1         | 1.15%   |
| Intel Centrino Wireless-N 130                                     | 1         | 1.15%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 1.15%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 17        | 36.96%  |
| Realtek Semiconductor | 11        | 23.91%  |
| Qualcomm Atheros      | 8         | 17.39%  |
| Broadcom              | 4         | 8.7%    |
| Ralink                | 3         | 6.52%   |
| ASUSTek Computer      | 2         | 4.35%   |
| Ralink Technology     | 1         | 2.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 6.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 3         | 6.52%   |
| Intel Wireless 8265 / 8275                                     | 3         | 6.52%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 6.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 4.35%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 4.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 4.35%   |
| Intel Wireless 7265                                            | 2         | 4.35%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 4.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.17%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.17%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 2.17%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 2.17%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 2.17%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 2.17%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 2.17%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 2.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 2.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 2.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 2.17%   |
| Intel Wireless 7260                                            | 1         | 2.17%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 2.17%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 2.17%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 2.17%   |
| Intel Centrino Wireless-N 2230                                 | 1         | 2.17%   |
| Intel Centrino Wireless-N 130                                  | 1         | 2.17%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 2.17%   |
| Intel Centrino Advanced-N 6200                                 | 1         | 2.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 2.17%   |
| Broadcom BCM43225 802.11b/g/n                                  | 1         | 2.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 2.17%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                            | 1         | 2.17%   |
| ASUS 802.11ac NIC                                              | 1         | 2.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 28        | 70%     |
| Intel                 | 7         | 17.5%   |
| Qualcomm Atheros      | 2         | 5%      |
| Xiaomi                | 1         | 2.5%    |
| JMicron Technology    | 1         | 2.5%    |
| Broadcom              | 1         | 2.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 20        | 48.78%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 7         | 17.07%  |
| Xiaomi Mi/Redmi series (RNDIS)                                       | 1         | 2.44%   |
| Realtek RTL8152 Fast Ethernet Adapter                                | 1         | 2.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 1         | 2.44%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                               | 1         | 2.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                        | 1         | 2.44%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller               | 1         | 2.44%   |
| Intel Ethernet Connection I217-LM                                    | 1         | 2.44%   |
| Intel Ethernet Connection (4) I219-V                                 | 1         | 2.44%   |
| Intel Ethernet Connection (4) I219-LM                                | 1         | 2.44%   |
| Intel Ethernet Connection (3) I218-V                                 | 1         | 2.44%   |
| Intel Ethernet Connection (3) I218-LM                                | 1         | 2.44%   |
| Intel 82577LC Gigabit Network Connection                             | 1         | 2.44%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile | 1         | 2.44%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                      | 1         | 2.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 42        | 51.85%  |
| Ethernet | 39        | 48.15%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 38        | 84.44%  |
| Ethernet | 7         | 15.56%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 39        | 92.86%  |
| 1     | 3         | 7.14%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 38        | 90.48%  |
| Yes  | 4         | 9.52%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 12        | 34.29%  |
| Realtek Semiconductor           | 6         | 17.14%  |
| Qualcomm Atheros Communications | 4         | 11.43%  |
| Toshiba                         | 2         | 5.71%   |
| Ralink                          | 2         | 5.71%   |
| Lite-On Technology              | 2         | 5.71%   |
| Cambridge Silicon Radio         | 2         | 5.71%   |
| Realtek                         | 1         | 2.86%   |
| IMC Networks                    | 1         | 2.86%   |
| Foxconn International           | 1         | 2.86%   |
| Foxconn / Hon Hai               | 1         | 2.86%   |
| Broadcom                        | 1         | 2.86%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 7         | 20%     |
| Realtek Bluetooth Radio                             | 4         | 11.43%  |
| Ralink RT3290 Bluetooth                             | 2         | 5.71%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 5.71%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 5.71%   |
| Intel Bluetooth Device                              | 2         | 5.71%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 5.71%   |
| Toshiba RT Bluetooth Radio                          | 1         | 2.86%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 2.86%   |
| Realtek RTL8821A Bluetooth                          | 1         | 2.86%   |
| Realtek RTL8723B Bluetooth                          | 1         | 2.86%   |
| Realtek Bluetooth Radio                             | 1         | 2.86%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 2.86%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 2.86%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.86%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 2.86%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 2.86%   |
| IMC Networks Bluetooth Device                       | 1         | 2.86%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 2.86%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 2.86%   |
| Broadcom HP Portable Valentine                      | 1         | 2.86%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 34        | 70.83%  |
| AMD                   | 8         | 16.67%  |
| Nvidia                | 5         | 10.42%  |
| Barco Display Systems | 1         | 2.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 9.52%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 7.94%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 6.35%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 6.35%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 4.76%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 4.76%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 4.76%   |
| AMD FCH Azalia Controller                                                                         | 3         | 4.76%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 4.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 3.17%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 3.17%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 3.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 3.17%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 3.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 3.17%   |
| AMD High Definition Audio Controller                                                              | 2         | 3.17%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 1.59%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 1.59%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.59%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.59%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.59%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.59%   |
| Barco Display Systems USBGH520-ENC                                                                | 1         | 1.59%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.59%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 1.59%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 1.59%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 41.18%  |
| SK hynix            | 4         | 23.53%  |
| Unknown (0x4509)    | 1         | 5.88%   |
| Unknown             | 1         | 5.88%   |
| Micron Technology   | 1         | 5.88%   |
| Kingston            | 1         | 5.88%   |
| Kingmax             | 1         | 5.88%   |
| A-DATA Technology   | 1         | 5.88%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR2                              | 1         | 5.88%   |
| Unknown (0x4509) RAM GKE800SO102408-2666A 8GB SODIMM DDR4 2133MT/s | 1         | 5.88%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                       | 1         | 5.88%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s             | 1         | 5.88%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s       | 1         | 5.88%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s             | 1         | 5.88%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s              | 1         | 5.88%   |
| Samsung RAM M471B5773CHS-CH9 2GB DIMM DDR3 1333MT/s                | 1         | 5.88%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s              | 1         | 5.88%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s              | 1         | 5.88%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s              | 1         | 5.88%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s           | 1         | 5.88%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s              | 1         | 5.88%   |
| Micron RAM 8KTF51264HDZ-1G6E1 4GB SODIMM DDR3 1600MT/s             | 1         | 5.88%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s            | 1         | 5.88%   |
| Kingmax RAM FSFE85F-C8KL9 2GB DIMM DDR3 1333MT/s                   | 1         | 5.88%   |
| A-DATA RAM AO1P21FC8T1-BSKS 8GB SODIMM DDR4 2133MT/s               | 1         | 5.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Notebooks | Percent |
|-------|-----------|---------|
| DDR4  | 8         | 50%     |
| DDR3  | 6         | 37.5%   |
| SDRAM | 1         | 6.25%   |
| DDR2  | 1         | 6.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 13        | 86.67%  |
| Row Of Chips | 1         | 6.67%   |
| DIMM         | 1         | 6.67%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 9         | 56.25%  |
| 4096  | 3         | 18.75%  |
| 2048  | 3         | 18.75%  |
| 16384 | 1         | 6.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 4         | 26.67%  |
| 3200    | 3         | 20%     |
| 2667    | 3         | 20%     |
| 2133    | 2         | 13.33%  |
| 2400    | 1         | 6.67%   |
| 1333    | 1         | 6.67%   |
| Unknown | 1         | 6.67%   |

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
| Chicony Electronics                    | 13        | 36.11%  |
| Realtek Semiconductor                  | 4         | 11.11%  |
| Microdia                               | 3         | 8.33%   |
| IMC Networks                           | 3         | 8.33%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 5.56%   |
| Bison Electronics                      | 2         | 5.56%   |
| Suyin                                  | 1         | 2.78%   |
| Silicon Motion                         | 1         | 2.78%   |
| Quanta                                 | 1         | 2.78%   |
| Luxvisions Innotech Limited            | 1         | 2.78%   |
| Lite-On Technology                     | 1         | 2.78%   |
| Foxconn / Hon Hai                      | 1         | 2.78%   |
| ALi                                    | 1         | 2.78%   |
| Alcor Micro                            | 1         | 2.78%   |
| 8SSC20F27114V1SR0BK1X4S                | 1         | 2.78%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Realtek Lenovo EasyCamera                                                | 2         | 5.56%   |
| Microdia Integrated_Webcam_HD                                            | 2         | 5.56%   |
| Chicony Integrated Camera                                                | 2         | 5.56%   |
| Chicony EasyCamera                                                       | 2         | 5.56%   |
| Suyin HP Webcam                                                          | 1         | 2.78%   |
| Silicon Motion WebCam SC-0311139N                                        | 1         | 2.78%   |
| Realtek HP Truevision HD integrated webcam                               | 1         | 2.78%   |
| Realtek Asus laptop camera                                               | 1         | 2.78%   |
| Quanta USB HD Webcam                                                     | 1         | 2.78%   |
| Microdia Laptop_Integrated_Webcam_HD                                     | 1         | 2.78%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                      | 1         | 2.78%   |
| Lite-On TOSHIBA Web Camera - HD                                          | 1         | 2.78%   |
| IMC Networks USB2.0 VGA UVC WebCam                                       | 1         | 2.78%   |
| IMC Networks Lenovo EasyCamera                                           | 1         | 2.78%   |
| IMC Networks EasyCamera                                                  | 1         | 2.78%   |
| Foxconn / Hon Hai USB2.0 Camera                                          | 1         | 2.78%   |
| Chicony USB2.0 VGA UVC WebCam                                            | 1         | 2.78%   |
| Chicony USB2.0 Camera                                                    | 1         | 2.78%   |
| Chicony USB 2.0 Camera                                                   | 1         | 2.78%   |
| Chicony HP Truevision HD                                                 | 1         | 2.78%   |
| Chicony HP HD Camera                                                     | 1         | 2.78%   |
| Chicony Gateway USB 2.0 Webcam                                           | 1         | 2.78%   |
| Chicony Front Camera                                                     | 1         | 2.78%   |
| Chicony CNF9055 Toshiba Webcam                                           | 1         | 2.78%   |
| Chicony CNA7157                                                          | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                         | 1         | 2.78%   |
| Bison SunplusIT Integrated Camera                                        | 1         | 2.78%   |
| Bison EasyCamera                                                         | 1         | 2.78%   |
| ALi Gateway Webcam                                                       | 1         | 2.78%   |
| Alcor Micro USB 2.0 Camera                                               | 1         | 2.78%   |
| 8SSC20F27114V1SR0BK1X4S Integrated Camera                                | 1         | 2.78%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 60%     |
| Shenzhen Goodix Technology | 1         | 20%     |
| AuthenTec                  | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 20%     |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 20%     |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 20%     |
| Shenzhen Goodix  Fingerprint Device                                        | 1         | 20%     |
| AuthenTec AES1600                                                          | 1         | 20%     |

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
| 0     | 30        | 69.77%  |
| 1     | 10        | 23.26%  |
| 2     | 3         | 6.98%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 5         | 31.25%  |
| Graphics card      | 4         | 25%     |
| Bluetooth          | 3         | 18.75%  |
| Camera             | 2         | 12.5%   |
| Net/wireless       | 1         | 6.25%   |
| Chipcard           | 1         | 6.25%   |

