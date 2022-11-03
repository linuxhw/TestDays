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

Total: 55

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | H81M-PLUS                   | Desktop     | [ffe63e6795](https://linux-hardware.org/?probe=ffe63e6795) | Oct 25, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [b0700ec521](https://linux-hardware.org/?probe=b0700ec521) | Oct 24, 2022 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [517cb3cb75](https://linux-hardware.org/?probe=517cb3cb75) | Oct 11, 2022 |
| TUXEDO        | Unknown                     | Notebook    | [52ddc219ae](https://linux-hardware.org/?probe=52ddc219ae) | Sep 23, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [60ebd510a4](https://linux-hardware.org/?probe=60ebd510a4) | Sep 07, 2022 |
| Acer          | Veriton ES2740G V:1.0       | Desktop     | [e14aeaaca3](https://linux-hardware.org/?probe=e14aeaaca3) | Jul 25, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [bcbbd7f228](https://linux-hardware.org/?probe=bcbbd7f228) | Jul 05, 2022 |
| HP            | 84DE                        | All in one  | [8af29f9d6c](https://linux-hardware.org/?probe=8af29f9d6c) | Jul 04, 2022 |
| HP            | 84DE                        | All in one  | [edb267564a](https://linux-hardware.org/?probe=edb267564a) | Jun 27, 2022 |
| MSI           | B250M GAMING PRO            | Desktop     | [052965926e](https://linux-hardware.org/?probe=052965926e) | Jun 26, 2022 |
| MSI           | MS-7360                     | Desktop     | [1ca1d835ad](https://linux-hardware.org/?probe=1ca1d835ad) | May 22, 2022 |
| Sony          | SVE14A2V2ES                 | Notebook    | [59435d662a](https://linux-hardware.org/?probe=59435d662a) | May 11, 2022 |
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
| Pardus 21.2   | 9         | 20.45%  |
| Pardus 21.1   | 6         | 13.64%  |
| Pardus 19.5   | 5         | 11.36%  |
| Pardus 21.3   | 4         | 9.09%   |
| Pardus 21.0   | 4         | 9.09%   |
| Pardus 19.4-1 | 3         | 6.82%   |
| Pardus 19.4   | 3         | 6.82%   |
| Pardus 19.3   | 3         | 6.82%   |
| Pardus 19.2   | 3         | 6.82%   |
| Pardus 19.1   | 2         | 4.55%   |
| Pardus 19.0   | 2         | 4.55%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Pardus | 42        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 5.10.0-13-amd64      | 6         | 13.64%  |
| 5.10.0-11-amd64      | 3         | 6.82%   |
| 4.19.0-6-amd64       | 3         | 6.82%   |
| 4.19.0-13-amd64      | 3         | 6.82%   |
| 4.19.0-10-amd64      | 3         | 6.82%   |
| 5.9.0-0.bpo.2-amd64  | 2         | 4.55%   |
| 5.10.0-9-amd64       | 2         | 4.55%   |
| 5.10.0-8-amd64       | 2         | 4.55%   |
| 5.10.0-14-amd64      | 2         | 4.55%   |
| 5.10.0-10-amd64      | 2         | 4.55%   |
| 4.19.0-8-amd64       | 2         | 4.55%   |
| 5.4.0-0.bpo.3-amd64  | 1         | 2.27%   |
| 5.10.0-19-amd64      | 1         | 2.27%   |
| 5.10.0-18-amd64      | 1         | 2.27%   |
| 5.10.0-17-amd64      | 1         | 2.27%   |
| 5.10.0-16-amd64      | 1         | 2.27%   |
| 5.10.0-15-amd64      | 1         | 2.27%   |
| 5.10.0-12-amd64      | 1         | 2.27%   |
| 5.10.0-0.bpo.8-amd64 | 1         | 2.27%   |
| 4.19.0-5-amd64       | 1         | 2.27%   |
| 4.19.0-19-amd64      | 1         | 2.27%   |
| 4.19.0-18-amd64      | 1         | 2.27%   |
| 4.19.0-17-amd64      | 1         | 2.27%   |
| 4.19.0-16-amd64      | 1         | 2.27%   |
| 4.19.0-12-amd64      | 1         | 2.27%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 24        | 55.81%  |
| 4.19.0  | 16        | 37.21%  |
| 5.9.0   | 2         | 4.65%   |
| 5.4.0   | 1         | 2.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 24        | 55.81%  |
| 4.19    | 16        | 37.21%  |
| 5.9     | 2         | 4.65%   |
| 5.4     | 1         | 2.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 42        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| XFCE       | 27        | 64.29%  |
| GNOME      | 10        | 23.81%  |
| KDE5       | 2         | 4.76%   |
| Unknown    | 2         | 4.76%   |
| X-Cinnamon | 1         | 2.38%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 42        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 27        | 64.29%  |
| TDM     | 6         | 14.29%  |
| LightDM | 4         | 9.52%   |
| GDM     | 4         | 9.52%   |
| SDDM    | 1         | 2.38%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| tr_TR   | 34        | 80.95%  |
| Unknown | 3         | 7.14%   |
| en_US   | 2         | 4.76%   |
| pt_BR   | 1         | 2.38%   |
| fr_FR   | 1         | 2.38%   |
| en_GB   | 1         | 2.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 33        | 76.74%  |
| EFI  | 10        | 23.26%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 41        | 97.62%  |
| Overlay | 1         | 2.38%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 30        | 71.43%  |
| GPT     | 10        | 23.81%  |
| MBR     | 2         | 4.76%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 39        | 92.86%  |
| Yes       | 3         | 7.14%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 34        | 80.95%  |
| Yes       | 8         | 19.05%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 9         | 21.43%  |
| MSI                 | 6         | 14.29%  |
| ASUSTek Computer    | 6         | 14.29%  |
| Hewlett-Packard     | 5         | 11.9%   |
| Toshiba             | 2         | 4.76%   |
| Sony                | 2         | 4.76%   |
| Packard Bell        | 2         | 4.76%   |
| Gigabyte Technology | 2         | 4.76%   |
| Dell                | 2         | 4.76%   |
| Acer                | 2         | 4.76%   |
| TUXEDO              | 1         | 2.38%   |
| Samsung Electronics | 1         | 2.38%   |
| Philco              | 1         | 2.38%   |
| HUAWEI              | 1         | 2.38%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| MSI MS-7360                                | 3         | 7.14%   |
| Toshiba Satellite C855-1VM                 | 1         | 2.38%   |
| Toshiba PORTEGE M780                       | 1         | 2.38%   |
| Sony SVF1521QSTB                           | 1         | 2.38%   |
| Sony SVE14A2V2ES                           | 1         | 2.38%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 2.38%   |
| Philco 14F                                 | 1         | 2.38%   |
| Packard Bell EasyNote_GN45                 | 1         | 2.38%   |
| Packard Bell EasyNote ENTG81BA             | 1         | 2.38%   |
| MSI MS-7C09                                | 1         | 2.38%   |
| MSI MS-7A65                                | 1         | 2.38%   |
| MSI MS-7817                                | 1         | 2.38%   |
| Lenovo Yoga 310-11IAP 80U2                 | 1         | 2.38%   |
| Lenovo V145-15AST 81MT                     | 1         | 2.38%   |
| Lenovo V110-15ISK 80TL                     | 1         | 2.38%   |
| Lenovo ThinkPad T450 20BUS39Y00            | 1         | 2.38%   |
| Lenovo ThinkPad E15 Gen 2 20TD0047TX       | 1         | 2.38%   |
| Lenovo ThinkCentre M920t 10SGS62900        | 1         | 2.38%   |
| Lenovo IdeaPad-510-15IKB 80SV              | 1         | 2.38%   |
| Lenovo IdeaPad 320-15IKB 81BT              | 1         | 2.38%   |
| Lenovo IdeaPad 100-15IBD 80QQ              | 1         | 2.38%   |
| HUAWEI KLVL-WXXW                           | 1         | 2.38%   |
| HP Pavilion 15                             | 1         | 2.38%   |
| HP Laptop 15-dw3xxx                        | 1         | 2.38%   |
| HP All-in-One 24-f0xx                      | 1         | 2.38%   |
| HP 250 G3                                  | 1         | 2.38%   |
| HP 15                                      | 1         | 2.38%   |
| Gigabyte A320M-S2H                         | 1         | 2.38%   |
| Gigabyte A320M-H                           | 1         | 2.38%   |
| Dell Latitude E6540                        | 1         | 2.38%   |
| Dell G5 5587                               | 1         | 2.38%   |
| ASUS X555YI                                | 1         | 2.38%   |
| ASUS V230IC-DDR4                           | 1         | 2.38%   |
| ASUS P7H55-M LX                            | 1         | 2.38%   |
| ASUS P5G41C-M LX                           | 1         | 2.38%   |
| ASUS E402BP                                | 1         | 2.38%   |
| ASUS All Series                            | 1         | 2.38%   |
| Acer Veriton ES2740G                       | 1         | 2.38%   |
| Acer Aspire 5742G                          | 1         | 2.38%   |
| Unknown                                    | 1         | 2.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| MSI MS-7360              | 3         | 7.14%   |
| Packard Bell EasyNote    | 2         | 4.76%   |
| Lenovo ThinkPad          | 2         | 4.76%   |
| Lenovo IdeaPad           | 2         | 4.76%   |
| Toshiba Satellite        | 1         | 2.38%   |
| Toshiba PORTEGE          | 1         | 2.38%   |
| Sony SVF1521QSTB         | 1         | 2.38%   |
| Sony SVE14A2V2ES         | 1         | 2.38%   |
| Samsung 300E4A           | 1         | 2.38%   |
| Philco 14F               | 1         | 2.38%   |
| MSI MS-7C09              | 1         | 2.38%   |
| MSI MS-7A65              | 1         | 2.38%   |
| MSI MS-7817              | 1         | 2.38%   |
| Lenovo Yoga              | 1         | 2.38%   |
| Lenovo V145-15AST        | 1         | 2.38%   |
| Lenovo V110-15ISK        | 1         | 2.38%   |
| Lenovo ThinkCentre       | 1         | 2.38%   |
| Lenovo IdeaPad-510-15IKB | 1         | 2.38%   |
| HUAWEI KLVL-WXXW         | 1         | 2.38%   |
| HP Pavilion              | 1         | 2.38%   |
| HP Laptop                | 1         | 2.38%   |
| HP All-in-One            | 1         | 2.38%   |
| HP 250                   | 1         | 2.38%   |
| HP 15                    | 1         | 2.38%   |
| Gigabyte A320M-S2H       | 1         | 2.38%   |
| Gigabyte A320M-H         | 1         | 2.38%   |
| Dell Latitude            | 1         | 2.38%   |
| Dell G5                  | 1         | 2.38%   |
| ASUS X555YI              | 1         | 2.38%   |
| ASUS V230IC-DDR4         | 1         | 2.38%   |
| ASUS P7H55-M             | 1         | 2.38%   |
| ASUS P5G41C-M            | 1         | 2.38%   |
| ASUS E402BP              | 1         | 2.38%   |
| ASUS All                 | 1         | 2.38%   |
| Acer Veriton             | 1         | 2.38%   |
| Acer Aspire              | 1         | 2.38%   |
| Unknown                  | 1         | 2.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2013 | 8         | 19.05%  |
| 2018 | 7         | 16.67%  |
| 2015 | 4         | 9.52%   |
| 2010 | 4         | 9.52%   |
| 2020 | 3         | 7.14%   |
| 2017 | 3         | 7.14%   |
| 2007 | 3         | 7.14%   |
| 2021 | 2         | 4.76%   |
| 2019 | 2         | 4.76%   |
| 2016 | 2         | 4.76%   |
| 2011 | 2         | 4.76%   |
| 2014 | 1         | 2.38%   |
| 2006 | 1         | 2.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 26        | 61.9%   |
| Desktop     | 13        | 30.95%  |
| All in one  | 2         | 4.76%   |
| Convertible | 1         | 2.38%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 42        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 42        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 16        | 38.1%   |
| 4.01-8.0   | 10        | 23.81%  |
| 16.01-24.0 | 6         | 14.29%  |
| 8.01-16.0  | 6         | 14.29%  |
| 1.01-2.0   | 2         | 4.76%   |
| 32.01-64.0 | 1         | 2.38%   |
| 2.01-3.0   | 1         | 2.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 18        | 40%     |
| 2.01-3.0   | 14        | 31.11%  |
| 3.01-4.0   | 7         | 15.56%  |
| 4.01-8.0   | 3         | 6.67%   |
| 24.01-32.0 | 1         | 2.22%   |
| 8.01-16.0  | 1         | 2.22%   |
| 0.51-1.0   | 1         | 2.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 28        | 66.67%  |
| 2      | 11        | 26.19%  |
| 3      | 2         | 4.76%   |
| 4      | 1         | 2.38%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 57.14%  |
| No        | 18        | 42.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 95.24%  |
| No        | 2         | 4.76%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 33        | 78.57%  |
| No        | 9         | 21.43%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 61.9%   |
| No        | 16        | 38.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Turkey  | 38        | 90.48%  |
| UK      | 1         | 2.38%   |
| Sweden  | 1         | 2.38%   |
| France  | 1         | 2.38%   |
| Brazil  | 1         | 2.38%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City        | Computers | Percent |
|-------------|-----------|---------|
| Istanbul    | 12        | 26.67%  |
| Bursa       | 6         | 13.33%  |
| Ankara      | 5         | 11.11%  |
| Aydin       | 4         | 8.89%   |
| Izmir       | 3         | 6.67%   |
| Konya       | 2         | 4.44%   |
| Çanakkale  | 2         | 4.44%   |
| Yaman       | 1         | 2.22%   |
| Soleymieu   | 1         | 2.22%   |
| Sao Gabriel | 1         | 2.22%   |
| Samsun      | 1         | 2.22%   |
| Malatya     | 1         | 2.22%   |
| London      | 1         | 2.22%   |
| Landskrona  | 1         | 2.22%   |
| Gaziantep   | 1         | 2.22%   |
| Esenyurt    | 1         | 2.22%   |
| Artvin      | 1         | 2.22%   |
| Antalya     | 1         | 2.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 15     | 20.69%  |
| Seagate             | 7         | 8      | 12.07%  |
| Samsung Electronics | 7         | 9      | 12.07%  |
| SanDisk             | 4         | 4      | 6.9%    |
| Kingston            | 3         | 4      | 5.17%   |
| A-DATA Technology   | 3         | 3      | 5.17%   |
| Unknown             | 2         | 3      | 3.45%   |
| SK hynix            | 2         | 2      | 3.45%   |
| KIOXIA-EXCERIA      | 2         | 2      | 3.45%   |
| HGST                | 2         | 2      | 3.45%   |
| China               | 2         | 2      | 3.45%   |
| Toshiba             | 1         | 1      | 1.72%   |
| Team                | 1         | 1      | 1.72%   |
| SPCC                | 1         | 1      | 1.72%   |
| Silicon Motion      | 1         | 1      | 1.72%   |
| Phison              | 1         | 1      | 1.72%   |
| Micron Technology   | 1         | 2      | 1.72%   |
| Lexar               | 1         | 1      | 1.72%   |
| KingSpec            | 1         | 1      | 1.72%   |
| Hitachi             | 1         | 1      | 1.72%   |
| Corsair             | 1         | 1      | 1.72%   |
| addlink             | 1         | 1      | 1.72%   |
| Unknown             | 1         | 1      | 1.72%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| WDC WD6402AAEX-00Y9A0 640GB                 | 3         | 5.08%   |
| A-DATA SU650 120GB SSD                      | 3         | 5.08%   |
| SanDisk SSD PLUS 240GB                      | 2         | 3.39%   |
| HGST HTS545050A7E680 500GB                  | 2         | 3.39%   |
| WDC WD5000LPVX-55V0TT0 500GB                | 1         | 1.69%   |
| WDC WD5000LPCX-60VHAT0 500GB                | 1         | 1.69%   |
| WDC WD5000LPCX-21VHAT0 500GB                | 1         | 1.69%   |
| WDC WD5000AAKX-00ERMA0 500GB                | 1         | 1.69%   |
| WDC WD3200BPVT-35JJ5T0 320GB                | 1         | 1.69%   |
| WDC WD3200AAJB-00WGA0 320GB                 | 1         | 1.69%   |
| WDC WD10JPVX-60JC3T0 1TB                    | 1         | 1.69%   |
| WDC WD10JPCX-24UE4T0 1TB                    | 1         | 1.69%   |
| WDC WD10EZEX-60WN4A0 1TB                    | 1         | 1.69%   |
| Unknown SD/MMC/MS PRO 1TB                   | 1         | 1.69%   |
| Unknown MMC Card  64GB                      | 1         | 1.69%   |
| Toshiba DT01ACA100 1TB                      | 1         | 1.69%   |
| Team T253X1240G 240GB SSD                   | 1         | 1.69%   |
| SPCC Solid State Disk 512GB                 | 1         | 1.69%   |
| SK hynix SC311 SATA 256GB SSD               | 1         | 1.69%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB     | 1         | 1.69%   |
| Silicon Motion Longline SSD 512GB           | 1         | 1.69%   |
| Seagate ST9500325AS 500GB                   | 1         | 1.69%   |
| Seagate ST9120822AS 120GB                   | 1         | 1.69%   |
| Seagate ST3160318AS 160GB                   | 1         | 1.69%   |
| Seagate ST2000DM008-2FR102 2TB              | 1         | 1.69%   |
| Seagate ST1000LM035-1RK172 1TB              | 1         | 1.69%   |
| Seagate Expansion 2TB                       | 1         | 1.69%   |
| Seagate BarraCuda Q1 SSD ZA480CV10001 480GB | 1         | 1.69%   |
| SanDisk Ultra II 240GB SSD                  | 1         | 1.69%   |
| SanDisk SDSSDA480G 480GB                    | 1         | 1.69%   |
| Samsung SSD 860 EVO 500GB                   | 1         | 1.69%   |
| Samsung NVMe SSD Drive 512GB                | 1         | 1.69%   |
| Samsung MZALQ256HAJD-000L1 256GB            | 1         | 1.69%   |
| Samsung MZ7LN128HAHQ-000L2 128GB SSD        | 1         | 1.69%   |
| Samsung MZ7LF192HCGS-000L1 192GB SSD        | 1         | 1.69%   |
| Samsung HD501LJ 500GB                       | 1         | 1.69%   |
| Samsung HD160HJ 160GB                       | 1         | 1.69%   |
| Samsung HD103SJ 1TB                         | 1         | 1.69%   |
| Phison 311CD0512GB                          | 1         | 1.69%   |
| Micron 1300_MTFDDAK512TDL 512GB SSD         | 1         | 1.69%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 15     | 48%     |
| Seagate             | 6         | 7      | 24%     |
| Samsung Electronics | 2         | 3      | 8%      |
| HGST                | 2         | 2      | 8%      |
| Unknown             | 1         | 2      | 4%      |
| Toshiba             | 1         | 1      | 4%      |
| Hitachi             | 1         | 1      | 4%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 4         | 4      | 16%     |
| Samsung Electronics | 3         | 3      | 12%     |
| Kingston            | 3         | 4      | 12%     |
| A-DATA Technology   | 3         | 3      | 12%     |
| KIOXIA-EXCERIA      | 2         | 2      | 8%      |
| China               | 2         | 2      | 8%      |
| Team                | 1         | 1      | 4%      |
| SPCC                | 1         | 1      | 4%      |
| SK hynix            | 1         | 1      | 4%      |
| Seagate             | 1         | 1      | 4%      |
| Micron Technology   | 1         | 2      | 4%      |
| Lexar               | 1         | 1      | 4%      |
| KingSpec            | 1         | 1      | 4%      |
| Corsair             | 1         | 1      | 4%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 22        | 31     | 44%     |
| SSD     | 21        | 27     | 42%     |
| NVMe    | 4         | 6      | 8%      |
| Unknown | 2         | 2      | 4%      |
| MMC     | 1         | 1      | 2%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 38        | 57     | 84.44%  |
| NVMe | 4         | 6      | 8.89%   |
| SAS  | 2         | 3      | 4.44%   |
| MMC  | 1         | 1      | 2.22%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 30        | 38     | 69.77%  |
| 0.51-1.0   | 11        | 17     | 25.58%  |
| 1.01-2.0   | 2         | 3      | 4.65%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 19        | 44.19%  |
| 251-500    | 12        | 27.91%  |
| 501-1000   | 5         | 11.63%  |
| 51-100     | 4         | 9.3%    |
| 21-50      | 2         | 4.65%   |
| 2001-3000  | 1         | 2.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 15        | 34.88%  |
| 21-50    | 12        | 27.91%  |
| 51-100   | 8         | 18.6%   |
| 101-250  | 6         | 13.95%  |
| 251-500  | 1         | 2.33%   |
| 501-1000 | 1         | 2.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WD5000LPCX-60VHAT0 500GB     | 1         | 1      | 33.33%  |
| Seagate ST9120822AS 120GB        | 1         | 1      | 33.33%  |
| Kingston SV300S37A120G 120GB SSD | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 1         | 1      | 33.33%  |
| Seagate  | 1         | 1      | 33.33%  |
| Kingston | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 30        | 50     | 68.18%  |
| Works    | 11        | 14     | 25%     |
| Malfunc  | 3         | 3      | 6.82%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 34        | 70.83%  |
| AMD                      | 6         | 12.5%   |
| Marvell Technology Group | 3         | 6.25%   |
| Samsung Electronics      | 2         | 4.17%   |
| SK hynix                 | 1         | 2.08%   |
| Silicon Motion           | 1         | 2.08%   |
| Phison Electronics       | 1         | 2.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 5         | 8.93%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 4         | 7.14%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 7.14%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                            | 3         | 5.36%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 5.36%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                           | 3         | 5.36%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                     | 3         | 5.36%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 5.36%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 3.57%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 3.57%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 2         | 3.57%   |
| AMD FCH SATA Controller D                                                        | 2         | 3.57%   |
| SK hynix BC511                                                                   | 1         | 1.79%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 1.79%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 1.79%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 1.79%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 1.79%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 1.79%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 1.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.79%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 1.79%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1         | 1.79%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 1.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.79%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 1.79%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 1.79%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 1.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 1         | 1.79%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 1         | 1.79%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 1         | 1.79%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 1         | 1.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 1.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 34        | 75.56%  |
| IDE  | 6         | 13.33%  |
| NVMe | 4         | 8.89%   |
| RAID | 1         | 2.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 35        | 83.33%  |
| AMD    | 7         | 16.67%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 3         | 7.14%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 4.76%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 4.76%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 2.38%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 1         | 2.38%   |
| Intel Core i9-9900 CPU @ 3.10GHz              | 1         | 2.38%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 2.38%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 2.38%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 2.38%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 1         | 2.38%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 2.38%   |
| Intel Core i5-7600 CPU @ 3.50GHz              | 1         | 2.38%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 2.38%   |
| Intel Core i5-6400T CPU @ 2.20GHz             | 1         | 2.38%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 2.38%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 1         | 2.38%   |
| Intel Core i5-4440 CPU @ 3.10GHz              | 1         | 2.38%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 2.38%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 1         | 2.38%   |
| Intel Core i3-9100F CPU @ 3.60GHz             | 1         | 2.38%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 2.38%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 2.38%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 1         | 2.38%   |
| Intel Core i3-3227U CPU @ 1.90GHz             | 1         | 2.38%   |
| Intel Core i3 CPU 540 @ 3.07GHz               | 1         | 2.38%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz         | 1         | 2.38%   |
| Intel Core 2 CPU T5600 @ 1.83GHz              | 1         | 2.38%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 1         | 2.38%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 1         | 2.38%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 2.38%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 2.38%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 1         | 2.38%   |
| AMD Ryzen 5 3500X 6-Core Processor            | 1         | 2.38%   |
| AMD C-50 Processor                            | 1         | 2.38%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 1         | 2.38%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G  | 1         | 2.38%   |
| AMD A8-9600 RADEON R7, 10 COMPUTE CORES 4C+6G | 1         | 2.38%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 1         | 2.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 10        | 23.81%  |
| Intel Core i3     | 8         | 19.05%  |
| Intel Core i7     | 5         | 11.9%   |
| Other             | 4         | 9.52%   |
| Intel Core 2 Quad | 4         | 9.52%   |
| Intel Pentium     | 2         | 4.76%   |
| Intel Celeron     | 2         | 4.76%   |
| AMD Ryzen 5       | 2         | 4.76%   |
| AMD A8            | 2         | 4.76%   |
| Intel Core i9     | 1         | 2.38%   |
| Intel Core 2      | 1         | 2.38%   |
| AMD C-50          | 1         | 2.38%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 21        | 50%     |
| 4      | 16        | 38.1%   |
| 6      | 4         | 9.52%   |
| 8      | 1         | 2.38%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 42        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 23        | 54.76%  |
| 1      | 19        | 45.24%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 42        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 26        | 61.9%   |
| 0x906eb    | 1         | 2.38%   |
| 0x906ea    | 1         | 2.38%   |
| 0x906e9    | 1         | 2.38%   |
| 0x806ea    | 1         | 2.38%   |
| 0x806c1    | 1         | 2.38%   |
| 0x6f6      | 1         | 2.38%   |
| 0x506e3    | 1         | 2.38%   |
| 0x406e3    | 1         | 2.38%   |
| 0x306d4    | 1         | 2.38%   |
| 0x306c3    | 1         | 2.38%   |
| 0x306a9    | 1         | 2.38%   |
| 0x20655    | 1         | 2.38%   |
| 0x08608102 | 1         | 2.38%   |
| 0x07030105 | 1         | 2.38%   |
| 0x06006705 | 1         | 2.38%   |
| 0x05000029 | 1         | 2.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 8         | 19.05%  |
| Haswell     | 4         | 9.52%   |
| Core        | 4         | 9.52%   |
| Westmere    | 3         | 7.14%   |
| IvyBridge   | 3         | 7.14%   |
| Excavator   | 3         | 7.14%   |
| Broadwell   | 3         | 7.14%   |
| TigerLake   | 2         | 4.76%   |
| Skylake     | 2         | 4.76%   |
| SandyBridge | 2         | 4.76%   |
| Zen 2       | 1         | 2.38%   |
| Silvermont  | 1         | 2.38%   |
| Puma        | 1         | 2.38%   |
| Penryn      | 1         | 2.38%   |
| Goldmont    | 1         | 2.38%   |
| CometLake   | 1         | 2.38%   |
| Bobcat      | 1         | 2.38%   |
| Unknown     | 1         | 2.38%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 27        | 51.92%  |
| AMD    | 13        | 25%     |
| Nvidia | 12        | 23.08%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia GT200 [GeForce GTX 260]                                                           | 3         | 5.36%   |
| Intel HD Graphics 5500                                                                   | 3         | 5.36%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 5.36%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 3.57%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 3.57%   |
| Intel UHD Graphics 620                                                                   | 2         | 3.57%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 3.57%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 3.57%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 3.57%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 1         | 1.79%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 1.79%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 1.79%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 1.79%   |
| Nvidia GF108M [GeForce GT 420M]                                                          | 1         | 1.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 1.79%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.79%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 1.79%   |
| Intel Tiger Lake UHD Graphics                                                            | 1         | 1.79%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.79%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.79%   |
| Intel HD Graphics 630                                                                    | 1         | 1.79%   |
| Intel HD Graphics 620                                                                    | 1         | 1.79%   |
| Intel HD Graphics 530                                                                    | 1         | 1.79%   |
| Intel HD Graphics 520                                                                    | 1         | 1.79%   |
| Intel HD Graphics 500                                                                    | 1         | 1.79%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1.79%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.79%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 1.79%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 1.79%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.79%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.79%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1         | 1.79%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 1.79%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 1.79%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 1.79%   |
| AMD RV630 PRO [Radeon HD 2600 PRO]                                                       | 1         | 1.79%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 1.79%   |
| AMD Mars XTX [Radeon HD 8790M]                                                           | 1         | 1.79%   |
| AMD Lucienne                                                                             | 1         | 1.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 17        | 40.48%  |
| 1 x Nvidia     | 8         | 19.05%  |
| 1 x AMD        | 7         | 16.67%  |
| Intel + Nvidia | 4         | 9.52%   |
| 2 x AMD        | 3         | 7.14%   |
| Intel + AMD    | 3         | 7.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 41        | 97.62%  |
| Proprietary | 1         | 2.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 33        | 78.57%  |
| 0.01-0.5   | 5         | 11.9%   |
| 0.51-1.0   | 2         | 4.76%   |
| 5.01-6.0   | 1         | 2.38%   |
| 1.01-2.0   | 1         | 2.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Goldstar                | 6         | 14.29%  |
| Samsung Electronics     | 5         | 11.9%   |
| Chimei Innolux          | 5         | 11.9%   |
| AU Optronics            | 5         | 11.9%   |
| LG Display              | 4         | 9.52%   |
| BOE                     | 4         | 9.52%   |
| Dell                    | 2         | 4.76%   |
| Acer                    | 2         | 4.76%   |
| SAC                     | 1         | 2.38%   |
| LG Philips              | 1         | 2.38%   |
| Lenovo                  | 1         | 2.38%   |
| Iiyama                  | 1         | 2.38%   |
| Hewlett-Packard         | 1         | 2.38%   |
| Chi Mei Optoelectronics | 1         | 2.38%   |
| Beko                    | 1         | 2.38%   |
| AOC                     | 1         | 2.38%   |
| AGO                     | 1         | 2.38%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Goldstar W2242 GSM5678 1680x1050 474x296mm 22.0-inch                     | 3         | 6.98%   |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch        | 1         | 2.33%   |
| Samsung Electronics SyncMaster SAM0599 1600x900 443x249mm 20.0-inch      | 1         | 2.33%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 340x270mm 17.1-inch     | 1         | 2.33%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 1         | 2.33%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 1         | 2.33%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch     | 1         | 2.33%   |
| SAC Casper SAC3219 1366x768 304x228mm 15.0-inch                          | 1         | 2.33%   |
| LG Philips LCD Monitor LPL1146 1280x800 331x207mm 15.4-inch              | 1         | 2.33%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 1         | 2.33%   |
| LG Display LCD Monitor LGD0470 1920x1080 345x194mm 15.6-inch             | 1         | 2.33%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch              | 1         | 2.33%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch              | 1         | 2.33%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 1         | 2.33%   |
| Iiyama PLX2380H IVM5621 1920x1080 509x286mm 23.0-inch                    | 1         | 2.33%   |
| Hewlett-Packard Contino HPN4018 1920x1080 527x296mm 23.8-inch            | 1         | 2.33%   |
| Goldstar L1753T GSM4476 1280x1024 340x270mm 17.1-inch                    | 1         | 2.33%   |
| Goldstar E2242 GSM58BE 1920x1080 477x268mm 21.5-inch                     | 1         | 2.33%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                   | 1         | 2.33%   |
| Dell P2717H DEL40F6 1920x1080 598x336mm 27.0-inch                        | 1         | 2.33%   |
| Dell E2421HN DELF129 1920x1080 527x296mm 23.8-inch                       | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x193mm 15.5-inch          | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 1         | 2.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO15AB 1366x768 340x190mm 15.3-inch | 1         | 2.33%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 1         | 2.33%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 1         | 2.33%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 1         | 2.33%   |
| BOE LCD Monitor BOE065E 1920x1080 344x194mm 15.5-inch                    | 1         | 2.33%   |
| Beko BK WUXGA BEK4448 1920x1080 1600x900mm 72.3-inch                     | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch           | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 1         | 2.33%   |
| AOC 2260WG5 AOC2260 1920x1080 477x268mm 21.5-inch                        | 1         | 2.33%   |
| AGO LCD Monitor AGO0001 1920x1080 256x192mm 12.6-inch                    | 1         | 2.33%   |
| Acer V226HQL ACR032D 1920x1080 477x268mm 21.5-inch                       | 1         | 2.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 15        | 36.59%  |
| 1366x768 (WXGA)    | 15        | 36.59%  |
| 1680x1050 (WSXGA+) | 3         | 7.32%   |
| 1600x900 (HD+)     | 3         | 7.32%   |
| 1280x1024 (SXGA)   | 2         | 4.88%   |
| 3840x2160 (4K)     | 1         | 2.44%   |
| 2160x1440          | 1         | 2.44%   |
| 1280x800 (WXGA)    | 1         | 2.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 19        | 44.19%  |
| 23     | 7         | 16.28%  |
| 14     | 3         | 6.98%   |
| 21     | 2         | 4.65%   |
| 17     | 2         | 4.65%   |
| 13     | 2         | 4.65%   |
| 72     | 1         | 2.33%   |
| 31     | 1         | 2.33%   |
| 27     | 1         | 2.33%   |
| 22     | 1         | 2.33%   |
| 20     | 1         | 2.33%   |
| 19     | 1         | 2.33%   |
| 12     | 1         | 2.33%   |
| 11     | 1         | 2.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 24        | 57.14%  |
| 401-500     | 8         | 19.05%  |
| 501-600     | 5         | 11.9%   |
| 201-300     | 3         | 7.14%   |
| 601-700     | 1         | 2.38%   |
| 1501-2000   | 1         | 2.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 31        | 75.61%  |
| 3/2   | 4         | 9.76%   |
| 5/4   | 2         | 4.88%   |
| 4/3   | 2         | 4.88%   |
| 16/10 | 2         | 4.88%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 19        | 44.19%  |
| 201-250        | 10        | 23.26%  |
| 81-90          | 5         | 11.63%  |
| 151-200        | 2         | 4.65%   |
| 141-150        | 2         | 4.65%   |
| More than 1000 | 1         | 2.33%   |
| 71-80          | 1         | 2.33%   |
| 51-60          | 1         | 2.33%   |
| 351-500        | 1         | 2.33%   |
| 301-350        | 1         | 2.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 15        | 34.88%  |
| 51-100  | 15        | 34.88%  |
| 121-160 | 10        | 23.26%  |
| 161-240 | 2         | 4.65%   |
| 1-50    | 1         | 2.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 37        | 88.1%   |
| 2     | 4         | 9.52%   |
| 0     | 1         | 2.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 34        | 54.84%  |
| Intel                 | 13        | 20.97%  |
| Qualcomm Atheros      | 4         | 6.45%   |
| Broadcom              | 3         | 4.84%   |
| Ralink                | 2         | 3.23%   |
| ASUSTek Computer      | 2         | 3.23%   |
| ZyXEL Communications  | 1         | 1.61%   |
| Xiaomi                | 1         | 1.61%   |
| Ralink Technology     | 1         | 1.61%   |
| JMicron Technology    | 1         | 1.61%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 27        | 35.06%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 6.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 3.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 3.9%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 2.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 2.6%    |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]      | 1         | 1.3%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.3%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 1.3%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 1.3%    |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 1.3%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.3%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.3%    |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 1.3%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 1.3%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1         | 1.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.3%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.3%    |
| Intel Wireless 8265 / 8275                                        | 1         | 1.3%    |
| Intel Wireless 7265                                               | 1         | 1.3%    |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.3%    |
| Intel Wi-Fi 6 AX200                                               | 1         | 1.3%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 1.3%    |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.3%    |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.3%    |
| Intel Ethernet Connection (3) I218-V                              | 1         | 1.3%    |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.3%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 1.3%    |
| Intel Centrino Wireless-N 2230                                    | 1         | 1.3%    |
| Intel Centrino Wireless-N 130                                     | 1         | 1.3%    |
| Intel Centrino Ultimate-N 6300                                    | 1         | 1.3%    |
| Intel Centrino Advanced-N 6200                                    | 1         | 1.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 1.3%    |
| Intel 82577LC Gigabit Network Connection                          | 1         | 1.3%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.3%    |
| Broadcom BCM43225 802.11b/g/n                                     | 1         | 1.3%    |
| Broadcom BCM43142 802.11b/g/n                                     | 1         | 1.3%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 1         | 1.3%    |
| ASUS Realtek 8188EUS [USB-N10 Nano]                               | 1         | 1.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 11        | 31.43%  |
| Intel                 | 11        | 31.43%  |
| Qualcomm Atheros      | 4         | 11.43%  |
| Broadcom              | 3         | 8.57%   |
| Ralink                | 2         | 5.71%   |
| ASUSTek Computer      | 2         | 5.71%   |
| ZyXEL Communications  | 1         | 2.86%   |
| Ralink Technology     | 1         | 2.86%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter     | 3         | 8.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter   | 3         | 8.57%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter     | 2         | 5.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter              | 2         | 5.71%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU] | 1         | 2.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter     | 1         | 2.86%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter              | 1         | 2.86%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                       | 1         | 2.86%   |
| Realtek RTL8188EE Wireless Network Adapter                   | 1         | 2.86%   |
| Ralink RT2870/RT3070 Wireless Adapter                        | 1         | 2.86%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                    | 1         | 2.86%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                    | 1         | 2.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter   | 1         | 2.86%   |
| Intel Wireless 8265 / 8275                                   | 1         | 2.86%   |
| Intel Wireless 7265                                          | 1         | 2.86%   |
| Intel Wi-Fi 6 AX201                                          | 1         | 2.86%   |
| Intel Wi-Fi 6 AX200                                          | 1         | 2.86%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection        | 1         | 2.86%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth              | 1         | 2.86%   |
| Intel Centrino Wireless-N 2230                               | 1         | 2.86%   |
| Intel Centrino Wireless-N 130                                | 1         | 2.86%   |
| Intel Centrino Ultimate-N 6300                               | 1         | 2.86%   |
| Intel Centrino Advanced-N 6200                               | 1         | 2.86%   |
| Intel Cannon Lake PCH CNVi WiFi                              | 1         | 2.86%   |
| Broadcom BCM43225 802.11b/g/n                                | 1         | 2.86%   |
| Broadcom BCM43142 802.11b/g/n                                | 1         | 2.86%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter          | 1         | 2.86%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                          | 1         | 2.86%   |
| ASUS 802.11ac NIC                                            | 1         | 2.86%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 33        | 80.49%  |
| Intel                 | 5         | 12.2%   |
| Xiaomi                | 1         | 2.44%   |
| JMicron Technology    | 1         | 2.44%   |
| Broadcom              | 1         | 2.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 27        | 64.29%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 11.9%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 2.38%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 2.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 2.38%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 2.38%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.38%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 2.38%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 2.38%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 2.38%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 2.38%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 40        | 54.79%  |
| WiFi     | 33        | 45.21%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 27        | 60%     |
| Ethernet | 18        | 40%     |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 28        | 66.67%  |
| 1     | 14        | 33.33%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 41        | 97.62%  |
| Yes  | 1         | 2.38%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 8         | 30.77%  |
| Realtek Semiconductor           | 6         | 23.08%  |
| Toshiba                         | 2         | 7.69%   |
| Qualcomm Atheros Communications | 2         | 7.69%   |
| IMC Networks                    | 2         | 7.69%   |
| Realtek                         | 1         | 3.85%   |
| Ralink                          | 1         | 3.85%   |
| Lite-On Technology              | 1         | 3.85%   |
| Foxconn / Hon Hai               | 1         | 3.85%   |
| Cambridge Silicon Radio         | 1         | 3.85%   |
| Broadcom                        | 1         | 3.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 4         | 15.38%  |
| Intel Bluetooth wireless interface                  | 3         | 11.54%  |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 7.69%   |
| Toshiba RT Bluetooth Radio                          | 1         | 3.85%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 3.85%   |
| Realtek RTL8821A Bluetooth                          | 1         | 3.85%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 3.85%   |
| Realtek Bluetooth Radio                             | 1         | 3.85%   |
| Ralink RT3290 Bluetooth                             | 1         | 3.85%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 3.85%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 3.85%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 3.85%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 3.85%   |
| Intel AX201 Bluetooth                               | 1         | 3.85%   |
| Intel AX200 Bluetooth                               | 1         | 3.85%   |
| IMC Networks Bluetooth Radio                        | 1         | 3.85%   |
| IMC Networks Bluetooth Device                       | 1         | 3.85%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 3.85%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.85%   |
| Broadcom HP Portable Valentine                      | 1         | 3.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 35        | 68.63%  |
| AMD                   | 10        | 19.61%  |
| Nvidia                | 4         | 7.84%   |
| Kingston Technology   | 1         | 1.96%   |
| Barco Display Systems | 1         | 1.96%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 4         | 6.45%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 6.45%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 4.84%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 4.84%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 4.84%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 4.84%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 4.84%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 4.84%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 3.23%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 3.23%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 3.23%   |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 3.23%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 3.23%   |
| AMD High Definition Audio Controller                                                              | 2         | 3.23%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.61%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 1.61%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.61%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.61%   |
| Kingston Technology HyperX QuadCast S                                                             | 1         | 1.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.61%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1.61%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 1.61%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.61%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.61%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 1.61%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 1.61%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.61%   |
| Barco Display Systems USBGH520-ENC                                                                | 1         | 1.61%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.61%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                                                | 1         | 1.61%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1         | 1.61%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 1.61%   |
| AMD RV630 HDMI Audio [Radeon HD 2600 PRO/XT / HD 3610]                                            | 1         | 1.61%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.61%   |
| AMD FCH Azalia Controller                                                                         | 1         | 1.61%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 1         | 1.61%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 1         | 1.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 5         | 33.33%  |
| SK hynix            | 2         | 13.33%  |
| Kingston            | 2         | 13.33%  |
| Unknown (0x4509)    | 1         | 6.67%   |
| Unknown             | 1         | 6.67%   |
| Micron Technology   | 1         | 6.67%   |
| Kingmax             | 1         | 6.67%   |
| G.Skill             | 1         | 6.67%   |
| A-DATA Technology   | 1         | 6.67%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR2                              | 1         | 6.25%   |
| Unknown (0x4509) RAM GKE800SO102408-2666A 8GB SODIMM DDR4 2133MT/s | 1         | 6.25%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s       | 1         | 6.25%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s             | 1         | 6.25%   |
| Samsung RAM M471B5773CHS-CH9 2GB DIMM DDR3 1333MT/s                | 1         | 6.25%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s              | 1         | 6.25%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s              | 1         | 6.25%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s              | 1         | 6.25%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s              | 1         | 6.25%   |
| Micron RAM 8KTF51264HDZ-1G6E1 4GB SODIMM DDR3 1600MT/s             | 1         | 6.25%   |
| Kingston RAM KHX3000C15D4/8GX 8192MB DIMM DDR4 3400MT/s            | 1         | 6.25%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s                  | 1         | 6.25%   |
| Kingston RAM 99U5428-018.A00LF 8192MB SODIMM DDR3 1600MT/s         | 1         | 6.25%   |
| Kingmax RAM FSFE85F-C8KL9 2GB DIMM DDR3 1333MT/s                   | 1         | 6.25%   |
| G.Skill RAM F4-2133C15-4GIS 4GB DIMM DDR4 2133MT/s                 | 1         | 6.25%   |
| A-DATA RAM Module 8GB DIMM DDR4 2667MT/s                           | 1         | 6.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind  | Computers | Percent |
|-------|-----------|---------|
| DDR4  | 10        | 66.67%  |
| DDR3  | 3         | 20%     |
| SDRAM | 1         | 6.67%   |
| DDR2  | 1         | 6.67%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 9         | 64.29%  |
| DIMM         | 4         | 28.57%  |
| Row Of Chips | 1         | 7.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size | Computers | Percent |
|------|-----------|---------|
| 8192 | 7         | 50%     |
| 4096 | 5         | 35.71%  |
| 2048 | 2         | 14.29%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 3         | 20%     |
| 2667    | 3         | 20%     |
| 2133    | 3         | 20%     |
| 1600    | 2         | 13.33%  |
| 3400    | 1         | 6.67%   |
| 2400    | 1         | 6.67%   |
| 1333    | 1         | 6.67%   |
| Unknown | 1         | 6.67%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Zebra           | 3         | 50%     |
| Canon           | 2         | 33.33%  |
| Hewlett-Packard | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Zebra TLP2844                    | 2         | 33.33%  |
| Zebra Zebra GC420d Label Printer | 1         | 16.67%  |
| HP LaserJet P1102                | 1         | 16.67%  |
| Canon LBP6030w/6018w             | 1         | 16.67%  |
| Canon LBP6000                    | 1         | 16.67%  |

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
| Chicony Electronics                    | 10        | 34.48%  |
| Microdia                               | 3         | 10.34%  |
| IMC Networks                           | 3         | 10.34%  |
| Luxvisions Innotech Limited            | 2         | 6.9%    |
| Acer                                   | 2         | 6.9%    |
| Suyin                                  | 1         | 3.45%   |
| Silicon Motion                         | 1         | 3.45%   |
| Realtek Semiconductor                  | 1         | 3.45%   |
| MacroSilicon                           | 1         | 3.45%   |
| Lite-On Technology                     | 1         | 3.45%   |
| Foxconn / Hon Hai                      | 1         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.45%   |
| Arkmicro Technologies                  | 1         | 3.45%   |
| ALi                                    | 1         | 3.45%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony EasyCamera                                  | 2         | 6.9%    |
| Acer EasyCamera                                     | 2         | 6.9%    |
| Suyin HP Webcam                                     | 1         | 3.45%   |
| Silicon Motion WebCam SC-0311139N                   | 1         | 3.45%   |
| Realtek HP Truevision HD integrated webcam          | 1         | 3.45%   |
| Microdia Laptop_Integrated_Webcam_HD                | 1         | 3.45%   |
| Microdia Integrated_Webcam_HD                       | 1         | 3.45%   |
| Microdia Integrated Camera                          | 1         | 3.45%   |
| MacroSilicon USB Video                              | 1         | 3.45%   |
| Luxvisions Innotech Limited Integrated Camera       | 1         | 3.45%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 3.45%   |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 3.45%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 3.45%   |
| IMC Networks Lenovo EasyCamera                      | 1         | 3.45%   |
| IMC Networks EasyCamera                             | 1         | 3.45%   |
| Foxconn / Hon Hai USB2.0 Camera                     | 1         | 3.45%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 3.45%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 3.45%   |
| Chicony USB2.0 Camera                               | 1         | 3.45%   |
| Chicony Integrated Camera                           | 1         | 3.45%   |
| Chicony HP Truevision HD                            | 1         | 3.45%   |
| Chicony HP High Definition 1MP Webcam               | 1         | 3.45%   |
| Chicony Front Camera                                | 1         | 3.45%   |
| Chicony CNA7157                                     | 1         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 1         | 3.45%   |
| Arkmicro USB2.0 PC CAMERA                           | 1         | 3.45%   |
| ALi Gateway Webcam                                  | 1         | 3.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 1         | 33.33%  |
| Shenzhen Goodix Technology | 1         | 33.33%  |
| AuthenTec                  | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor | 1         | 33.33%  |
| Shenzhen Goodix  Fingerprint Device          | 1         | 33.33%  |
| AuthenTec AES1600                            | 1         | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Advanced Card Systems | 2         | 66.67%  |
| Broadcom              | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Advanced Card Systems ACR38 SmartCard Reader                                 | 2         | 66.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 32        | 72.73%  |
| 1     | 9         | 20.45%  |
| 2     | 3         | 6.82%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 3         | 21.43%  |
| Fingerprint reader       | 3         | 21.43%  |
| Communication controller | 2         | 14.29%  |
| Chipcard                 | 2         | 14.29%  |
| Camera                   | 2         | 14.29%  |
| Net/wireless             | 1         | 7.14%   |
| Bluetooth                | 1         | 7.14%   |

