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

Total: 46

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Pardus 21.3   | 5         | 14.29%  |
| Pardus 21.1   | 5         | 14.29%  |
| Pardus 21.2   | 4         | 11.43%  |
| Pardus 21.4   | 3         | 8.57%   |
| Pardus 21.0   | 3         | 8.57%   |
| Pardus 19.5   | 3         | 8.57%   |
| Pardus 19.3   | 3         | 8.57%   |
| Pardus 19.4-1 | 2         | 5.71%   |
| Pardus 19.2   | 2         | 5.71%   |
| Pardus 19.1   | 2         | 5.71%   |
| Pardus 19.0   | 2         | 5.71%   |
| Pardus 19.4   | 1         | 2.86%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Pardus | 33        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Notebooks | Percent |
|---------------------------|-----------|---------|
| 5.10.0-19-amd64           | 3         | 8.33%   |
| 5.10.0-13-amd64           | 3         | 8.33%   |
| 5.10.0-11-amd64           | 3         | 8.33%   |
| 4.19.0-6-amd64            | 3         | 8.33%   |
| 4.19.0-10-amd64           | 3         | 8.33%   |
| 5.10.0-9-amd64            | 2         | 5.56%   |
| 5.10.0-21-amd64           | 2         | 5.56%   |
| 5.10.0-10-amd64           | 2         | 5.56%   |
| 4.19.0-13-amd64           | 2         | 5.56%   |
| 6.0.11-x64v2-rt14-xanmod1 | 1         | 2.78%   |
| 5.9.0-0.bpo.2-amd64       | 1         | 2.78%   |
| 5.4.0-0.bpo.3-amd64       | 1         | 2.78%   |
| 5.10.0-8-amd64            | 1         | 2.78%   |
| 5.10.0-20-amd64           | 1         | 2.78%   |
| 5.10.0-17-amd64           | 1         | 2.78%   |
| 5.10.0-16-amd64           | 1         | 2.78%   |
| 5.10.0-14-amd64           | 1         | 2.78%   |
| 5.10.0-0.bpo.8-amd64      | 1         | 2.78%   |
| 4.19.0-8-amd64            | 1         | 2.78%   |
| 4.19.0-5-amd64            | 1         | 2.78%   |
| 4.19.0-19-amd64           | 1         | 2.78%   |
| 4.19.0-16-amd64           | 1         | 2.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 20        | 58.82%  |
| 4.19.0  | 11        | 32.35%  |
| 6.0.11  | 1         | 2.94%   |
| 5.9.0   | 1         | 2.94%   |
| 5.4.0   | 1         | 2.94%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 20        | 58.82%  |
| 4.19    | 11        | 32.35%  |
| 6.0     | 1         | 2.94%   |
| 5.9     | 1         | 2.94%   |
| 5.4     | 1         | 2.94%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 33        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| XFCE    | 22        | 66.67%  |
| GNOME   | 8         | 24.24%  |
| Unknown | 2         | 6.06%   |
| KDE5    | 1         | 3.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 33        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 20        | 60.61%  |
| TDM     | 6         | 18.18%  |
| GDM     | 4         | 12.12%  |
| LightDM | 3         | 9.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| tr_TR   | 24        | 72.73%  |
| Unknown | 3         | 9.09%   |
| en_US   | 2         | 6.06%   |
| pt_BR   | 1         | 3.03%   |
| hu_HU   | 1         | 3.03%   |
| fur_IT  | 1         | 3.03%   |
| en_GB   | 1         | 3.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 23        | 67.65%  |
| EFI  | 11        | 32.35%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 32        | 96.97%  |
| Overlay | 1         | 3.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 21        | 63.64%  |
| GPT     | 10        | 30.3%   |
| MBR     | 2         | 6.06%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 31        | 93.94%  |
| Yes       | 2         | 6.06%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 26        | 78.79%  |
| Yes       | 7         | 21.21%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 10        | 30.3%   |
| Hewlett-Packard     | 5         | 15.15%  |
| Toshiba             | 3         | 9.09%   |
| Sony                | 2         | 6.06%   |
| Packard Bell        | 2         | 6.06%   |
| Dell                | 2         | 6.06%   |
| ASUSTek Computer    | 2         | 6.06%   |
| Acer                | 2         | 6.06%   |
| TUXEDO              | 1         | 3.03%   |
| Samsung Electronics | 1         | 3.03%   |
| Philco              | 1         | 3.03%   |
| Olidata             | 1         | 3.03%   |
| HUAWEI              | 1         | 3.03%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Toshiba Satellite C855-1VM                 | 1         | 3.03%   |
| Toshiba Satellite C660                     | 1         | 3.03%   |
| Toshiba PORTEGE M780                       | 1         | 3.03%   |
| Sony SVF1521QSTB                           | 1         | 3.03%   |
| Sony SVE14A2V2ES                           | 1         | 3.03%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 3.03%   |
| Philco 14F                                 | 1         | 3.03%   |
| Packard Bell EasyNote_GN45                 | 1         | 3.03%   |
| Packard Bell EasyNote ENTG81BA             | 1         | 3.03%   |
| Olidata T7700                              | 1         | 3.03%   |
| Lenovo V145-15AST 81MT                     | 1         | 3.03%   |
| Lenovo V110-15ISK 80TL                     | 1         | 3.03%   |
| Lenovo ThinkPad T450 20BUS39Y00            | 1         | 3.03%   |
| Lenovo ThinkPad S1 Yoga 20CD0034TX         | 1         | 3.03%   |
| Lenovo ThinkPad E15 Gen 2 20TD0047TX       | 1         | 3.03%   |
| Lenovo IdeaPad-510-15IKB 80SV              | 1         | 3.03%   |
| Lenovo IdeaPad 320-15IKB 81BT              | 1         | 3.03%   |
| Lenovo IdeaPad 100-15IBD 80QQ              | 1         | 3.03%   |
| Lenovo G510 20238                          | 1         | 3.03%   |
| Lenovo G50-45 80E3                         | 1         | 3.03%   |
| HUAWEI KLVL-WXXW                           | 1         | 3.03%   |
| HP Pavilion 15                             | 1         | 3.03%   |
| HP Laptop 15-dw3xxx                        | 1         | 3.03%   |
| HP 530                                     | 1         | 3.03%   |
| HP 250 G3                                  | 1         | 3.03%   |
| HP 15                                      | 1         | 3.03%   |
| Dell Latitude E6540                        | 1         | 3.03%   |
| Dell G5 5587                               | 1         | 3.03%   |
| ASUS X555YI                                | 1         | 3.03%   |
| ASUS E402BP                                | 1         | 3.03%   |
| Acer Aspire A515-41G                       | 1         | 3.03%   |
| Acer Aspire 5742G                          | 1         | 3.03%   |
| Unknown                                    | 1         | 3.03%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 3         | 9.09%   |
| Toshiba Satellite        | 2         | 6.06%   |
| Packard Bell EasyNote    | 2         | 6.06%   |
| Lenovo IdeaPad           | 2         | 6.06%   |
| Acer Aspire              | 2         | 6.06%   |
| Toshiba PORTEGE          | 1         | 3.03%   |
| Sony SVF1521QSTB         | 1         | 3.03%   |
| Sony SVE14A2V2ES         | 1         | 3.03%   |
| Samsung 300E4A           | 1         | 3.03%   |
| Philco 14F               | 1         | 3.03%   |
| Olidata T7700            | 1         | 3.03%   |
| Lenovo V145-15AST        | 1         | 3.03%   |
| Lenovo V110-15ISK        | 1         | 3.03%   |
| Lenovo IdeaPad-510-15IKB | 1         | 3.03%   |
| Lenovo G510              | 1         | 3.03%   |
| Lenovo G50-45            | 1         | 3.03%   |
| HUAWEI KLVL-WXXW         | 1         | 3.03%   |
| HP Pavilion              | 1         | 3.03%   |
| HP Laptop                | 1         | 3.03%   |
| HP 530                   | 1         | 3.03%   |
| HP 250                   | 1         | 3.03%   |
| HP 15                    | 1         | 3.03%   |
| Dell Latitude            | 1         | 3.03%   |
| Dell G5                  | 1         | 3.03%   |
| ASUS X555YI              | 1         | 3.03%   |
| ASUS E402BP              | 1         | 3.03%   |
| Unknown                  | 1         | 3.03%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 7         | 21.21%  |
| 2018 | 4         | 12.12%  |
| 2015 | 4         | 12.12%  |
| 2014 | 3         | 9.09%   |
| 2010 | 3         | 9.09%   |
| 2020 | 2         | 6.06%   |
| 2019 | 2         | 6.06%   |
| 2011 | 2         | 6.06%   |
| 2021 | 1         | 3.03%   |
| 2017 | 1         | 3.03%   |
| 2016 | 1         | 3.03%   |
| 2008 | 1         | 3.03%   |
| 2007 | 1         | 3.03%   |
| 2006 | 1         | 3.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 33        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 33        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 33        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 13        | 39.39%  |
| 4.01-8.0   | 8         | 24.24%  |
| 8.01-16.0  | 5         | 15.15%  |
| 16.01-24.0 | 4         | 12.12%  |
| 1.01-2.0   | 2         | 6.06%   |
| 2.01-3.0   | 1         | 3.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 17        | 48.57%  |
| 2.01-3.0 | 11        | 31.43%  |
| 3.01-4.0 | 4         | 11.43%  |
| 4.01-8.0 | 2         | 5.71%   |
| 0.51-1.0 | 1         | 2.86%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 23        | 69.7%   |
| 2      | 9         | 27.27%  |
| 3      | 1         | 3.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 18        | 54.55%  |
| No        | 15        | 45.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 90.91%  |
| No        | 3         | 9.09%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 33        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 27        | 81.82%  |
| No        | 6         | 18.18%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Turkey  | 28        | 84.85%  |
| UK      | 1         | 3.03%   |
| Sweden  | 1         | 3.03%   |
| Italy   | 1         | 3.03%   |
| Germany | 1         | 3.03%   |
| Brazil  | 1         | 3.03%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Istanbul             | 11        | 31.43%  |
| Ankara               | 5         | 14.29%  |
| Izmir                | 4         | 11.43%  |
| Çanakkale           | 2         | 5.71%   |
| Serik                | 1         | 2.86%   |
| Sao Gabriel          | 1         | 2.86%   |
| London               | 1         | 2.86%   |
| Landskrona           | 1         | 2.86%   |
| Konya                | 1         | 2.86%   |
| Kirchheim unter Teck | 1         | 2.86%   |
| Gaziantep            | 1         | 2.86%   |
| Esenyurt             | 1         | 2.86%   |
| Bursa                | 1         | 2.86%   |
| Bolzano              | 1         | 2.86%   |
| Aydin                | 1         | 2.86%   |
| Artvin               | 1         | 2.86%   |
| Antalya              | 1         | 2.86%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 10     | 19.51%  |
| Seagate             | 6         | 6      | 14.63%  |
| Samsung Electronics | 6         | 6      | 14.63%  |
| SanDisk             | 3         | 3      | 7.32%   |
| SK hynix            | 2         | 2      | 4.88%   |
| Kingston            | 2         | 3      | 4.88%   |
| Hitachi             | 2         | 2      | 4.88%   |
| HGST                | 2         | 2      | 4.88%   |
| Toshiba             | 1         | 2      | 2.44%   |
| SPCC                | 1         | 1      | 2.44%   |
| Silicon Motion      | 1         | 1      | 2.44%   |
| Phison              | 1         | 1      | 2.44%   |
| Micron Technology   | 1         | 2      | 2.44%   |
| Lexar               | 1         | 1      | 2.44%   |
| KingSpec            | 1         | 1      | 2.44%   |
| Intenso             | 1         | 2      | 2.44%   |
| addlink             | 1         | 1      | 2.44%   |
| Unknown             | 1         | 1      | 2.44%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| HGST HTS545050A7E680 500GB                  | 2         | 4.76%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD            | 1         | 2.38%   |
| WDC WD5000LPVX-55V0TT0 500GB                | 1         | 2.38%   |
| WDC WD5000LPCX-60VHAT0 500GB                | 1         | 2.38%   |
| WDC WD5000LPCX-21VHAT0 500GB                | 1         | 2.38%   |
| WDC WD3200BPVT-35JJ5T0 320GB                | 1         | 2.38%   |
| WDC WD2500BEVS-00UST0 250GB                 | 1         | 2.38%   |
| WDC WD10JPVX-60JC3T0 1TB                    | 1         | 2.38%   |
| WDC WD10JPCX-24UE4T0 1TB                    | 1         | 2.38%   |
| Toshiba MK6475GSX 640GB                     | 1         | 2.38%   |
| SPCC Solid State Disk 512GB                 | 1         | 2.38%   |
| SK hynix SC311 SATA 256GB SSD               | 1         | 2.38%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB     | 1         | 2.38%   |
| Silicon Motion Longline SSD 512GB           | 1         | 2.38%   |
| Seagate ST9500325AS 500GB                   | 1         | 2.38%   |
| Seagate ST9120822AS 120GB                   | 1         | 2.38%   |
| Seagate ST500LM000-1EJ162 500GB             | 1         | 2.38%   |
| Seagate ST1000LM035-1RK172 1TB              | 1         | 2.38%   |
| Seagate Expansion+ 2TB                      | 1         | 2.38%   |
| Seagate BarraCuda Q1 SSD ZA480CV10001 480GB | 1         | 2.38%   |
| SanDisk SSD U110 16GB                       | 1         | 2.38%   |
| SanDisk SSD PLUS 240GB                      | 1         | 2.38%   |
| SanDisk SDSSDA480G 480GB                    | 1         | 2.38%   |
| Samsung SSD 860 EVO 500GB                   | 1         | 2.38%   |
| Samsung SSD 850 PRO 256GB                   | 1         | 2.38%   |
| Samsung MZALQ256HAJD-000L1 256GB            | 1         | 2.38%   |
| Samsung MZ7LN128HAHQ-000L2 128GB SSD        | 1         | 2.38%   |
| Samsung MZ7LF192HCGS-000L1 192GB SSD        | 1         | 2.38%   |
| Samsung HM250HI 250GB                       | 1         | 2.38%   |
| Phison 311CD0512GB                          | 1         | 2.38%   |
| Micron 1300_MTFDDAK512TDL 512GB SSD         | 1         | 2.38%   |
| Lexar 120GB SSD                             | 1         | 2.38%   |
| Kingston SHFS37A120G 120GB SSD              | 1         | 2.38%   |
| Kingston SA400S37240G 240GB SSD             | 1         | 2.38%   |
| KingSpec P3-128 128GB SSD                   | 1         | 2.38%   |
| Intenso SSD 128GB                           | 1         | 2.38%   |
| Intenso SSD 120GB                           | 1         | 2.38%   |
| Hitachi HTS545025B9A300 250GB               | 1         | 2.38%   |
| Hitachi HTS542512K9A300 120GB               | 1         | 2.38%   |
| addlink S10 960GB                           | 1         | 2.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 9      | 38.89%  |
| Seagate             | 5         | 5      | 27.78%  |
| Hitachi             | 2         | 2      | 11.11%  |
| HGST                | 2         | 2      | 11.11%  |
| Toshiba             | 1         | 2      | 5.56%   |
| Samsung Electronics | 1         | 1      | 5.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 23.53%  |
| SanDisk             | 3         | 3      | 17.65%  |
| Kingston            | 2         | 3      | 11.76%  |
| WDC                 | 1         | 1      | 5.88%   |
| SPCC                | 1         | 1      | 5.88%   |
| SK hynix            | 1         | 1      | 5.88%   |
| Seagate             | 1         | 1      | 5.88%   |
| Micron Technology   | 1         | 2      | 5.88%   |
| Lexar               | 1         | 1      | 5.88%   |
| KingSpec            | 1         | 1      | 5.88%   |
| Intenso             | 1         | 2      | 5.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 18        | 21     | 48.65%  |
| SSD     | 14        | 20     | 37.84%  |
| NVMe    | 3         | 4      | 8.11%   |
| Unknown | 2         | 2      | 5.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 30        | 42     | 88.24%  |
| NVMe | 3         | 4      | 8.82%   |
| SAS  | 1         | 1      | 2.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 24        | 30     | 77.42%  |
| 0.51-1.0   | 6         | 10     | 19.35%  |
| 1.01-2.0   | 1         | 1      | 3.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 16        | 47.06%  |
| 251-500    | 11        | 32.35%  |
| 501-1000   | 3         | 8.82%   |
| 21-50      | 2         | 5.88%   |
| 51-100     | 2         | 5.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 17        | 50%     |
| 21-50   | 7         | 20.59%  |
| 51-100  | 5         | 14.71%  |
| 101-250 | 4         | 11.76%  |
| 251-500 | 1         | 2.94%   |

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
| Detected | 21        | 30     | 61.76%  |
| Works    | 11        | 15     | 32.35%  |
| Malfunc  | 2         | 2      | 5.88%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 25        | 71.43%  |
| AMD                 | 6         | 17.14%  |
| SK hynix            | 1         | 2.86%   |
| Silicon Motion      | 1         | 2.86%   |
| Samsung Electronics | 1         | 2.86%   |
| Phison Electronics  | 1         | 2.86%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 5         | 12.82%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 4         | 10.26%  |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 3         | 7.69%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 3         | 7.69%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 2         | 5.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 2         | 5.13%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 2         | 5.13%   |
| SK hynix BC511                                                                         | 1         | 2.56%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 1         | 2.56%   |
| Samsung NVMe SSD Controller 980                                                        | 1         | 2.56%   |
| Phison PS5013 E13 NVMe Controller                                                      | 1         | 2.56%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 1         | 2.56%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 1         | 2.56%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 1         | 2.56%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 1         | 2.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 1         | 2.56%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 1         | 2.56%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 1         | 2.56%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 2.56%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 2.56%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 1         | 2.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 1         | 2.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
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

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 26        | 78.79%  |
| AMD    | 7         | 21.21%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i3 CPU M 370 @ 2.40GHz               | 2         | 6.06%   |
| Intel Pentium CPU B960 @ 2.20GHz                | 1         | 3.03%   |
| Intel Pentium CPU B950 @ 2.10GHz                | 1         | 3.03%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 1         | 3.03%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 3.03%   |
| Intel Core i7-5500U CPU @ 2.40GHz               | 1         | 3.03%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz              | 1         | 3.03%   |
| Intel Core i7-3630QM CPU @ 2.40GHz              | 1         | 3.03%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 1         | 3.03%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 1         | 3.03%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 1         | 3.03%   |
| Intel Core i5-4200M CPU @ 2.50GHz               | 1         | 3.03%   |
| Intel Core i5-3230M CPU @ 2.60GHz               | 1         | 3.03%   |
| Intel Core i3-6006U CPU @ 2.00GHz               | 1         | 3.03%   |
| Intel Core i3-5005U CPU @ 2.00GHz               | 1         | 3.03%   |
| Intel Core i3-4010U CPU @ 1.70GHz               | 1         | 3.03%   |
| Intel Core i3-4005U CPU @ 1.70GHz               | 1         | 3.03%   |
| Intel Core i3-3227U CPU @ 1.90GHz               | 1         | 3.03%   |
| Intel Core i3-2310M CPU @ 2.10GHz               | 1         | 3.03%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz            | 1         | 3.03%   |
| Intel Core 2 CPU T5600 @ 1.83GHz                | 1         | 3.03%   |
| Intel Core 2 CPU T5200 @ 1.60GHz                | 1         | 3.03%   |
| Intel Celeron CPU N3050 @ 1.60GHz               | 1         | 3.03%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 1         | 3.03%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz         | 1         | 3.03%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 1         | 3.03%   |
| AMD C-50 Processor                              | 1         | 3.03%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G    | 1         | 3.03%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G    | 1         | 3.03%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics     | 1         | 3.03%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics     | 1         | 3.03%   |
| AMD A10-9620P RADEON R5, 10 COMPUTE CORES 4C+6G | 1         | 3.03%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i3    | 8         | 24.24%  |
| Intel Core i7    | 5         | 15.15%  |
| Intel Core i5    | 5         | 15.15%  |
| Other            | 4         | 12.12%  |
| Intel Pentium    | 2         | 6.06%   |
| Intel Core 2     | 2         | 6.06%   |
| AMD A8           | 2         | 6.06%   |
| Intel Core 2 Duo | 1         | 3.03%   |
| Intel Celeron    | 1         | 3.03%   |
| AMD Ryzen 5      | 1         | 3.03%   |
| AMD C-50         | 1         | 3.03%   |
| AMD A10          | 1         | 3.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 24        | 72.73%  |
| 4      | 7         | 21.21%  |
| 6      | 2         | 6.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 33        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 22        | 66.67%  |
| 1      | 11        | 33.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 33        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 63.64%  |
| 0x07030105 | 2         | 6.06%   |
| 0x906ea    | 1         | 3.03%   |
| 0x806c1    | 1         | 3.03%   |
| 0x6f6      | 1         | 3.03%   |
| 0x406e3    | 1         | 3.03%   |
| 0x306d4    | 1         | 3.03%   |
| 0x306a9    | 1         | 3.03%   |
| 0x08608102 | 1         | 3.03%   |
| 0x06006705 | 1         | 3.03%   |
| 0x0600611a | 1         | 3.03%   |
| 0x05000029 | 1         | 3.03%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 4         | 12.12%  |
| Haswell     | 4         | 12.12%  |
| SandyBridge | 3         | 9.09%   |
| IvyBridge   | 3         | 9.09%   |
| Excavator   | 3         | 9.09%   |
| Core        | 3         | 9.09%   |
| Broadwell   | 3         | 9.09%   |
| Westmere    | 2         | 6.06%   |
| TigerLake   | 2         | 6.06%   |
| Puma        | 2         | 6.06%   |
| Skylake     | 1         | 3.03%   |
| Silvermont  | 1         | 3.03%   |
| Bobcat      | 1         | 3.03%   |
| Unknown     | 1         | 3.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 24        | 58.54%  |
| AMD    | 11        | 26.83%  |
| Nvidia | 6         | 14.63%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 5500                                                                   | 3         | 6.12%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 6.12%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 4.08%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 4.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 4.08%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 4.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 4.08%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 4.08%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 4.08%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 4.08%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 4.08%   |
| Nvidia GT218M [GeForce 315M]                                                             | 1         | 2.04%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 2.04%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 2.04%   |
| Nvidia GF108M [GeForce GT 420M]                                                          | 1         | 2.04%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 2.04%   |
| Intel UHD Graphics 620                                                                   | 1         | 2.04%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 2.04%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 1         | 2.04%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 2.04%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 2.04%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 2.04%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 2.04%   |
| Intel HD Graphics 620                                                                    | 1         | 2.04%   |
| Intel HD Graphics 520                                                                    | 1         | 2.04%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 2.04%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 2.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.04%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1         | 2.04%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 2.04%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 2.04%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                         | 1         | 2.04%   |
| AMD Mars XTX [Radeon HD 8790M]                                                           | 1         | 2.04%   |
| AMD Lucienne                                                                             | 1         | 2.04%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 1         | 2.04%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520/610 Mobile]                         | 1         | 2.04%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 16        | 48.48%  |
| 2 x AMD        | 5         | 15.15%  |
| Intel + Nvidia | 4         | 12.12%  |
| Intel + AMD    | 4         | 12.12%  |
| 1 x Nvidia     | 2         | 6.06%   |
| 1 x AMD        | 2         | 6.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver | Notebooks | Percent |
|--------|-----------|---------|
| Free   | 33        | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 26        | 78.79%  |
| 0.01-0.5   | 5         | 15.15%  |
| 5.01-6.0   | 1         | 3.03%   |
| 0.51-1.0   | 1         | 3.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 7         | 21.88%  |
| Chimei Innolux          | 5         | 15.63%  |
| BOE                     | 5         | 15.63%  |
| Samsung Electronics     | 4         | 12.5%   |
| AU Optronics            | 4         | 12.5%   |
| LG Philips              | 2         | 6.25%   |
| Chi Mei Optoelectronics | 2         | 6.25%   |
| Lenovo                  | 1         | 3.13%   |
| Goldstar                | 1         | 3.13%   |
| AOC                     | 1         | 3.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch     | 1         | 3.03%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 1         | 3.03%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 1         | 3.03%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 1         | 3.03%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch     | 1         | 3.03%   |
| LG Philips LCD Monitor LPLDB00 1280x800 331x207mm 15.4-inch              | 1         | 3.03%   |
| LG Philips LCD Monitor LPL1146 1280x800 331x207mm 15.4-inch              | 1         | 3.03%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 1         | 3.03%   |
| LG Display LCD Monitor LGD0470 1920x1080 345x194mm 15.6-inch             | 1         | 3.03%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch              | 1         | 3.03%   |
| LG Display LCD Monitor LGD0414 1920x1080 276x156mm 12.5-inch             | 1         | 3.03%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch              | 1         | 3.03%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch              | 1         | 3.03%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 1         | 3.03%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 1         | 3.03%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                   | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x193mm 15.5-inch          | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 1         | 3.03%   |
| Chi Mei Optoelectronics LCD Monitor CMO1703 1440x900 367x230mm 17.1-inch | 1         | 3.03%   |
| Chi Mei Optoelectronics LCD Monitor CMO15AB 1366x768 340x190mm 15.3-inch | 1         | 3.03%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 1         | 3.03%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 1         | 3.03%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 1         | 3.03%   |
| BOE LCD Monitor BOE0661 1366x768 344x194mm 15.5-inch                     | 1         | 3.03%   |
| BOE LCD Monitor BOE065E 1920x1080 344x194mm 15.5-inch                    | 1         | 3.03%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 1         | 3.03%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 1         | 3.03%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch           | 1         | 3.03%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 1         | 3.03%   |
| AOC 2260W AOC2260 1920x1080 477x268mm 21.5-inch                          | 1         | 3.03%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 17        | 53.13%  |
| 1920x1080 (FHD)  | 9         | 28.13%  |
| 1280x800 (WXGA)  | 2         | 6.25%   |
| 2160x1440        | 1         | 3.13%   |
| 1600x900 (HD+)   | 1         | 3.13%   |
| 1440x900 (WXGA+) | 1         | 3.13%   |
| 1280x1024 (SXGA) | 1         | 3.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 23        | 69.7%   |
| 14     | 3         | 9.09%   |
| 17     | 2         | 6.06%   |
| 13     | 2         | 6.06%   |
| 23     | 1         | 3.03%   |
| 22     | 1         | 3.03%   |
| 12     | 1         | 3.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 27        | 84.38%  |
| 201-300     | 2         | 6.25%   |
| 501-600     | 1         | 3.13%   |
| 401-500     | 1         | 3.13%   |
| 351-400     | 1         | 3.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 27        | 81.82%  |
| 16/10 | 4         | 12.12%  |
| 5/4   | 1         | 3.03%   |
| 3/2   | 1         | 3.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 23        | 69.7%   |
| 81-90          | 5         | 15.15%  |
| 201-250        | 2         | 6.06%   |
| 61-70          | 1         | 3.03%   |
| 141-150        | 1         | 3.03%   |
| 131-140        | 1         | 3.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 16        | 48.48%  |
| 121-160 | 8         | 24.24%  |
| 51-100  | 7         | 21.21%  |
| 161-240 | 2         | 6.06%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 31        | 93.94%  |
| 2     | 2         | 6.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 24        | 44.44%  |
| Intel                 | 13        | 24.07%  |
| Qualcomm Atheros      | 6         | 11.11%  |
| Broadcom              | 4         | 7.41%   |
| Ralink                | 2         | 3.7%    |
| ASUSTek Computer      | 2         | 3.7%    |
| Xiaomi                | 1         | 1.85%   |
| Ralink Technology     | 1         | 1.85%   |
| JMicron Technology    | 1         | 1.85%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 15        | 22.06%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 7         | 10.29%  |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 3         | 4.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 3         | 4.41%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 3         | 4.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 2         | 2.94%   |
| Broadcom BCM43142 802.11b/g/n                                        | 2         | 2.94%   |
| Xiaomi Mi/Redmi series (RNDIS)                                       | 1         | 1.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 1         | 1.47%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 1         | 1.47%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                      | 1         | 1.47%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 1         | 1.47%   |
| Realtek RTL8152 Fast Ethernet Adapter                                | 1         | 1.47%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 1         | 1.47%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 1         | 1.47%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 1         | 1.47%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                            | 1         | 1.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 1         | 1.47%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                               | 1         | 1.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 1         | 1.47%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller               | 1         | 1.47%   |
| Intel Wireless 8265 / 8275                                           | 1         | 1.47%   |
| Intel Wireless 7265                                                  | 1         | 1.47%   |
| Intel Wireless 7260                                                  | 1         | 1.47%   |
| Intel Wi-Fi 6 AX201                                                  | 1         | 1.47%   |
| Intel Ethernet Connection I217-LM                                    | 1         | 1.47%   |
| Intel Ethernet Connection (3) I218-V                                 | 1         | 1.47%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 1         | 1.47%   |
| Intel Centrino Wireless-N 2230                                       | 1         | 1.47%   |
| Intel Centrino Wireless-N 130                                        | 1         | 1.47%   |
| Intel Centrino Ultimate-N 6300                                       | 1         | 1.47%   |
| Intel Centrino Advanced-N 6200                                       | 1         | 1.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 1         | 1.47%   |
| Intel 82577LC Gigabit Network Connection                             | 1         | 1.47%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile | 1         | 1.47%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                      | 1         | 1.47%   |
| Broadcom BCM43225 802.11b/g/n                                        | 1         | 1.47%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 1         | 1.47%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                                  | 1         | 1.47%   |
| ASUS 802.11ac NIC                                                    | 1         | 1.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 13        | 36.11%  |
| Realtek Semiconductor | 9         | 25%     |
| Qualcomm Atheros      | 5         | 13.89%  |
| Broadcom              | 4         | 11.11%  |
| Ralink                | 2         | 5.56%   |
| ASUSTek Computer      | 2         | 5.56%   |
| Ralink Technology     | 1         | 2.78%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 8.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 3         | 8.33%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 8.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 5.56%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 5.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.78%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.78%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 2.78%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 2.78%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 2.78%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 2.78%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 2.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 2.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 2.78%   |
| Intel Wireless 8265 / 8275                                     | 1         | 2.78%   |
| Intel Wireless 7265                                            | 1         | 2.78%   |
| Intel Wireless 7260                                            | 1         | 2.78%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 2.78%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 2.78%   |
| Intel Centrino Wireless-N 2230                                 | 1         | 2.78%   |
| Intel Centrino Wireless-N 130                                  | 1         | 2.78%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 2.78%   |
| Intel Centrino Advanced-N 6200                                 | 1         | 2.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 2.78%   |
| Broadcom BCM43225 802.11b/g/n                                  | 1         | 2.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 2.78%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                            | 1         | 2.78%   |
| ASUS 802.11ac NIC                                              | 1         | 2.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 23        | 74.19%  |
| Intel                 | 4         | 12.9%   |
| Xiaomi                | 1         | 3.23%   |
| Qualcomm Atheros      | 1         | 3.23%   |
| JMicron Technology    | 1         | 3.23%   |
| Broadcom              | 1         | 3.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 15        | 46.88%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 7         | 21.88%  |
| Xiaomi Mi/Redmi series (RNDIS)                                       | 1         | 3.13%   |
| Realtek RTL8152 Fast Ethernet Adapter                                | 1         | 3.13%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 1         | 3.13%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                               | 1         | 3.13%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller               | 1         | 3.13%   |
| Intel Ethernet Connection I217-LM                                    | 1         | 3.13%   |
| Intel Ethernet Connection (3) I218-V                                 | 1         | 3.13%   |
| Intel 82577LC Gigabit Network Connection                             | 1         | 3.13%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile | 1         | 3.13%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                      | 1         | 3.13%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 33        | 52.38%  |
| Ethernet | 30        | 47.62%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 29        | 82.86%  |
| Ethernet | 6         | 17.14%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 30        | 90.91%  |
| 1     | 3         | 9.09%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 31        | 93.94%  |
| Yes  | 2         | 6.06%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 8         | 29.63%  |
| Realtek Semiconductor           | 6         | 22.22%  |
| Toshiba                         | 2         | 7.41%   |
| Qualcomm Atheros Communications | 2         | 7.41%   |
| Lite-On Technology              | 2         | 7.41%   |
| Realtek                         | 1         | 3.7%    |
| Ralink                          | 1         | 3.7%    |
| IMC Networks                    | 1         | 3.7%    |
| Foxconn International           | 1         | 3.7%    |
| Foxconn / Hon Hai               | 1         | 3.7%    |
| Cambridge Silicon Radio         | 1         | 3.7%    |
| Broadcom                        | 1         | 3.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 4         | 14.81%  |
| Intel Bluetooth wireless interface                  | 4         | 14.81%  |
| Toshiba RT Bluetooth Radio                          | 1         | 3.7%    |
| Toshiba Integrated Bluetooth HCI                    | 1         | 3.7%    |
| Realtek RTL8821A Bluetooth                          | 1         | 3.7%    |
| Realtek RTL8723B Bluetooth                          | 1         | 3.7%    |
| Realtek Bluetooth Radio                             | 1         | 3.7%    |
| Ralink RT3290 Bluetooth                             | 1         | 3.7%    |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 3.7%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 3.7%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 3.7%    |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 3.7%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 3.7%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 3.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 3.7%    |
| Intel AX201 Bluetooth                               | 1         | 3.7%    |
| IMC Networks Bluetooth Device                       | 1         | 3.7%    |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 3.7%    |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 3.7%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.7%    |
| Broadcom HP Portable Valentine                      | 1         | 3.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 26        | 72.22%  |
| AMD                   | 7         | 19.44%  |
| Nvidia                | 2         | 5.56%   |
| Barco Display Systems | 1         | 2.78%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 8.16%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 6.12%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 6.12%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 6.12%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 6.12%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 6.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 4.08%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 4.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 4.08%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 4.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 4.08%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 4.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 4.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 4.08%   |
| AMD High Definition Audio Controller                                                              | 2         | 4.08%   |
| AMD FCH Azalia Controller                                                                         | 2         | 4.08%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 2.04%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 2.04%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 2.04%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 2.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.04%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 2.04%   |
| Barco Display Systems USBGH520-ENC                                                                | 1         | 2.04%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 2.04%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 2.04%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 2.04%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 5         | 38.46%  |
| SK hynix            | 2         | 15.38%  |
| Unknown (0x4509)    | 1         | 7.69%   |
| Unknown             | 1         | 7.69%   |
| Micron Technology   | 1         | 7.69%   |
| Kingston            | 1         | 7.69%   |
| Kingmax             | 1         | 7.69%   |
| A-DATA Technology   | 1         | 7.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR2                              | 1         | 7.69%   |
| Unknown (0x4509) RAM GKE800SO102408-2666A 8GB SODIMM DDR4 2133MT/s | 1         | 7.69%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s       | 1         | 7.69%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s             | 1         | 7.69%   |
| Samsung RAM M471B5773CHS-CH9 2GB DIMM DDR3 1333MT/s                | 1         | 7.69%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s              | 1         | 7.69%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s              | 1         | 7.69%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s              | 1         | 7.69%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s              | 1         | 7.69%   |
| Micron RAM 8KTF51264HDZ-1G6E1 4GB SODIMM DDR3 1600MT/s             | 1         | 7.69%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s            | 1         | 7.69%   |
| Kingmax RAM FSFE85F-C8KL9 2GB DIMM DDR3 1333MT/s                   | 1         | 7.69%   |
| A-DATA RAM AO1P21FC8T1-BSKS 8GB SODIMM DDR4 2133MT/s               | 1         | 7.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Notebooks | Percent |
|-------|-----------|---------|
| DDR4  | 7         | 53.85%  |
| DDR3  | 4         | 30.77%  |
| SDRAM | 1         | 7.69%   |
| DDR2  | 1         | 7.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 10        | 83.33%  |
| Row Of Chips | 1         | 8.33%   |
| DIMM         | 1         | 8.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 8192 | 7         | 58.33%  |
| 4096 | 3         | 25%     |
| 2048 | 2         | 16.67%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 3         | 25%     |
| 1600    | 3         | 25%     |
| 2667    | 2         | 16.67%  |
| 2133    | 2         | 16.67%  |
| 1333    | 1         | 8.33%   |
| Unknown | 1         | 8.33%   |

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
| Chicony Electronics                    | 11        | 39.29%  |
| Realtek Semiconductor                  | 3         | 10.71%  |
| IMC Networks                           | 3         | 10.71%  |
| Microdia                               | 2         | 7.14%   |
| Luxvisions Innotech Limited            | 2         | 7.14%   |
| Suyin                                  | 1         | 3.57%   |
| Silicon Motion                         | 1         | 3.57%   |
| Lite-On Technology                     | 1         | 3.57%   |
| Foxconn / Hon Hai                      | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.57%   |
| ALi                                    | 1         | 3.57%   |
| Acer                                   | 1         | 3.57%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Lenovo EasyCamera                           | 2         | 7.14%   |
| Chicony Integrated Camera                           | 2         | 7.14%   |
| Chicony EasyCamera                                  | 2         | 7.14%   |
| Suyin HP Webcam                                     | 1         | 3.57%   |
| Silicon Motion WebCam SC-0311139N                   | 1         | 3.57%   |
| Realtek HP Truevision HD integrated webcam          | 1         | 3.57%   |
| Microdia Laptop_Integrated_Webcam_HD                | 1         | 3.57%   |
| Microdia Integrated_Webcam_HD                       | 1         | 3.57%   |
| Luxvisions Innotech Limited Integrated Camera       | 1         | 3.57%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 3.57%   |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 3.57%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 3.57%   |
| IMC Networks Lenovo EasyCamera                      | 1         | 3.57%   |
| IMC Networks EasyCamera                             | 1         | 3.57%   |
| Foxconn / Hon Hai USB2.0 Camera                     | 1         | 3.57%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 3.57%   |
| Chicony USB2.0 Camera                               | 1         | 3.57%   |
| Chicony HP Truevision HD                            | 1         | 3.57%   |
| Chicony Gateway USB 2.0 Webcam                      | 1         | 3.57%   |
| Chicony Front Camera                                | 1         | 3.57%   |
| Chicony CNF9055 Toshiba Webcam                      | 1         | 3.57%   |
| Chicony CNA7157                                     | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 1         | 3.57%   |
| ALi Gateway Webcam                                  | 1         | 3.57%   |
| Acer EasyCamera                                     | 1         | 3.57%   |

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
| 0     | 26        | 76.47%  |
| 1     | 6         | 17.65%  |
| 2     | 2         | 5.88%   |

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

