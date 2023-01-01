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

Total: 64

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | G50-45 80E3                 | Notebook    | [05070bdc72](https://linux-hardware.org/?probe=05070bdc72) | Dec 29, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [5d14354a02](https://linux-hardware.org/?probe=5d14354a02) | Dec 16, 2022 |
| Acer          | Aspire A515-41G             | Notebook    | [fb7da9e239](https://linux-hardware.org/?probe=fb7da9e239) | Dec 10, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [27f508f09e](https://linux-hardware.org/?probe=27f508f09e) | Dec 07, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [ca7c59284c](https://linux-hardware.org/?probe=ca7c59284c) | Nov 28, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [9da0a974dd](https://linux-hardware.org/?probe=9da0a974dd) | Nov 27, 2022 |
| Olidata       | T7700                       | Notebook    | [d8220596fc](https://linux-hardware.org/?probe=d8220596fc) | Nov 19, 2022 |
| HP            | 530                         | Notebook    | [337ff0c5ea](https://linux-hardware.org/?probe=337ff0c5ea) | Nov 15, 2022 |
| Olidata       | T7700                       | Notebook    | [488f74cf4b](https://linux-hardware.org/?probe=488f74cf4b) | Nov 14, 2022 |
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
| Pardus 21.2   | 9         | 18.37%  |
| Pardus 21.3   | 8         | 16.33%  |
| Pardus 21.1   | 6         | 12.24%  |
| Pardus 19.5   | 5         | 10.2%   |
| Pardus 21.0   | 4         | 8.16%   |
| Pardus 19.4-1 | 3         | 6.12%   |
| Pardus 19.4   | 3         | 6.12%   |
| Pardus 19.3   | 3         | 6.12%   |
| Pardus 19.2   | 3         | 6.12%   |
| Pardus 19.1   | 2         | 4.08%   |
| Pardus 19.0   | 2         | 4.08%   |
| Pardus 21.4   | 1         | 2.04%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Pardus | 47        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 5.10.0-13-amd64           | 6         | 12%     |
| 5.10.0-19-amd64           | 4         | 8%      |
| 5.10.0-11-amd64           | 3         | 6%      |
| 4.19.0-6-amd64            | 3         | 6%      |
| 4.19.0-13-amd64           | 3         | 6%      |
| 4.19.0-10-amd64           | 3         | 6%      |
| 5.9.0-0.bpo.2-amd64       | 2         | 4%      |
| 5.10.0-9-amd64            | 2         | 4%      |
| 5.10.0-8-amd64            | 2         | 4%      |
| 5.10.0-16-amd64           | 2         | 4%      |
| 5.10.0-14-amd64           | 2         | 4%      |
| 5.10.0-10-amd64           | 2         | 4%      |
| 4.19.0-8-amd64            | 2         | 4%      |
| 6.0.11-x64v2-rt14-xanmod1 | 1         | 2%      |
| 5.4.0-0.bpo.3-amd64       | 1         | 2%      |
| 5.10.0-20-amd64           | 1         | 2%      |
| 5.10.0-18-amd64           | 1         | 2%      |
| 5.10.0-17-amd64           | 1         | 2%      |
| 5.10.0-15-amd64           | 1         | 2%      |
| 5.10.0-12-amd64           | 1         | 2%      |
| 5.10.0-0.bpo.8-amd64      | 1         | 2%      |
| 4.19.0-5-amd64            | 1         | 2%      |
| 4.19.0-19-amd64           | 1         | 2%      |
| 4.19.0-18-amd64           | 1         | 2%      |
| 4.19.0-17-amd64           | 1         | 2%      |
| 4.19.0-16-amd64           | 1         | 2%      |
| 4.19.0-12-amd64           | 1         | 2%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 28        | 58.33%  |
| 4.19.0  | 16        | 33.33%  |
| 5.9.0   | 2         | 4.17%   |
| 6.0.11  | 1         | 2.08%   |
| 5.4.0   | 1         | 2.08%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 28        | 58.33%  |
| 4.19    | 16        | 33.33%  |
| 5.9     | 2         | 4.17%   |
| 6.0     | 1         | 2.08%   |
| 5.4     | 1         | 2.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 47        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| XFCE       | 30        | 63.83%  |
| GNOME      | 12        | 25.53%  |
| KDE5       | 2         | 4.26%   |
| Unknown    | 2         | 4.26%   |
| X-Cinnamon | 1         | 2.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 47        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 30        | 63.83%  |
| TDM     | 6         | 12.77%  |
| LightDM | 5         | 10.64%  |
| GDM     | 5         | 10.64%  |
| SDDM    | 1         | 2.13%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| tr_TR   | 37        | 78.72%  |
| Unknown | 3         | 6.38%   |
| en_US   | 2         | 4.26%   |
| pt_BR   | 1         | 2.13%   |
| hu_HU   | 1         | 2.13%   |
| fur_IT  | 1         | 2.13%   |
| fr_FR   | 1         | 2.13%   |
| en_GB   | 1         | 2.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 36        | 75%     |
| EFI  | 12        | 25%     |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 46        | 97.87%  |
| Overlay | 1         | 2.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 33        | 70.21%  |
| GPT     | 12        | 25.53%  |
| MBR     | 2         | 4.26%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 44        | 93.62%  |
| Yes       | 3         | 6.38%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 39        | 82.98%  |
| Yes       | 8         | 17.02%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 10        | 21.28%  |
| MSI                 | 6         | 12.77%  |
| Hewlett-Packard     | 6         | 12.77%  |
| ASUSTek Computer    | 6         | 12.77%  |
| Toshiba             | 3         | 6.38%   |
| Acer                | 3         | 6.38%   |
| Sony                | 2         | 4.26%   |
| Packard Bell        | 2         | 4.26%   |
| Gigabyte Technology | 2         | 4.26%   |
| Dell                | 2         | 4.26%   |
| TUXEDO              | 1         | 2.13%   |
| Samsung Electronics | 1         | 2.13%   |
| Philco              | 1         | 2.13%   |
| Olidata             | 1         | 2.13%   |
| HUAWEI              | 1         | 2.13%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| MSI MS-7360                                | 3         | 6.38%   |
| Toshiba Satellite C855-1VM                 | 1         | 2.13%   |
| Toshiba Satellite C660                     | 1         | 2.13%   |
| Toshiba PORTEGE M780                       | 1         | 2.13%   |
| Sony SVF1521QSTB                           | 1         | 2.13%   |
| Sony SVE14A2V2ES                           | 1         | 2.13%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 2.13%   |
| Philco 14F                                 | 1         | 2.13%   |
| Packard Bell EasyNote_GN45                 | 1         | 2.13%   |
| Packard Bell EasyNote ENTG81BA             | 1         | 2.13%   |
| Olidata T7700                              | 1         | 2.13%   |
| MSI MS-7C09                                | 1         | 2.13%   |
| MSI MS-7A65                                | 1         | 2.13%   |
| MSI MS-7817                                | 1         | 2.13%   |
| Lenovo Yoga 310-11IAP 80U2                 | 1         | 2.13%   |
| Lenovo V145-15AST 81MT                     | 1         | 2.13%   |
| Lenovo V110-15ISK 80TL                     | 1         | 2.13%   |
| Lenovo ThinkPad T450 20BUS39Y00            | 1         | 2.13%   |
| Lenovo ThinkPad E15 Gen 2 20TD0047TX       | 1         | 2.13%   |
| Lenovo ThinkCentre M920t 10SGS62900        | 1         | 2.13%   |
| Lenovo IdeaPad-510-15IKB 80SV              | 1         | 2.13%   |
| Lenovo IdeaPad 320-15IKB 81BT              | 1         | 2.13%   |
| Lenovo IdeaPad 100-15IBD 80QQ              | 1         | 2.13%   |
| Lenovo G50-45 80E3                         | 1         | 2.13%   |
| HUAWEI KLVL-WXXW                           | 1         | 2.13%   |
| HP Pavilion 15                             | 1         | 2.13%   |
| HP Laptop 15-dw3xxx                        | 1         | 2.13%   |
| HP All-in-One 24-f0xx                      | 1         | 2.13%   |
| HP 530                                     | 1         | 2.13%   |
| HP 250 G3                                  | 1         | 2.13%   |
| HP 15                                      | 1         | 2.13%   |
| Gigabyte A320M-S2H                         | 1         | 2.13%   |
| Gigabyte A320M-H                           | 1         | 2.13%   |
| Dell Latitude E6540                        | 1         | 2.13%   |
| Dell G5 5587                               | 1         | 2.13%   |
| ASUS X555YI                                | 1         | 2.13%   |
| ASUS V230IC-DDR4                           | 1         | 2.13%   |
| ASUS P7H55-M LX                            | 1         | 2.13%   |
| ASUS P5G41C-M LX                           | 1         | 2.13%   |
| ASUS E402BP                                | 1         | 2.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| MSI MS-7360              | 3         | 6.38%   |
| Toshiba Satellite        | 2         | 4.26%   |
| Packard Bell EasyNote    | 2         | 4.26%   |
| Lenovo ThinkPad          | 2         | 4.26%   |
| Lenovo IdeaPad           | 2         | 4.26%   |
| Acer Aspire              | 2         | 4.26%   |
| Toshiba PORTEGE          | 1         | 2.13%   |
| Sony SVF1521QSTB         | 1         | 2.13%   |
| Sony SVE14A2V2ES         | 1         | 2.13%   |
| Samsung 300E4A           | 1         | 2.13%   |
| Philco 14F               | 1         | 2.13%   |
| Olidata T7700            | 1         | 2.13%   |
| MSI MS-7C09              | 1         | 2.13%   |
| MSI MS-7A65              | 1         | 2.13%   |
| MSI MS-7817              | 1         | 2.13%   |
| Lenovo Yoga              | 1         | 2.13%   |
| Lenovo V145-15AST        | 1         | 2.13%   |
| Lenovo V110-15ISK        | 1         | 2.13%   |
| Lenovo ThinkCentre       | 1         | 2.13%   |
| Lenovo IdeaPad-510-15IKB | 1         | 2.13%   |
| Lenovo G50-45            | 1         | 2.13%   |
| HUAWEI KLVL-WXXW         | 1         | 2.13%   |
| HP Pavilion              | 1         | 2.13%   |
| HP Laptop                | 1         | 2.13%   |
| HP All-in-One            | 1         | 2.13%   |
| HP 530                   | 1         | 2.13%   |
| HP 250                   | 1         | 2.13%   |
| HP 15                    | 1         | 2.13%   |
| Gigabyte A320M-S2H       | 1         | 2.13%   |
| Gigabyte A320M-H         | 1         | 2.13%   |
| Dell Latitude            | 1         | 2.13%   |
| Dell G5                  | 1         | 2.13%   |
| ASUS X555YI              | 1         | 2.13%   |
| ASUS V230IC-DDR4         | 1         | 2.13%   |
| ASUS P7H55-M             | 1         | 2.13%   |
| ASUS P5G41C-M            | 1         | 2.13%   |
| ASUS E402BP              | 1         | 2.13%   |
| ASUS All                 | 1         | 2.13%   |
| Acer Veriton             | 1         | 2.13%   |
| Unknown                  | 1         | 2.13%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2013 | 8         | 17.02%  |
| 2018 | 7         | 14.89%  |
| 2010 | 5         | 10.64%  |
| 2017 | 4         | 8.51%   |
| 2015 | 4         | 8.51%   |
| 2007 | 4         | 8.51%   |
| 2020 | 3         | 6.38%   |
| 2021 | 2         | 4.26%   |
| 2019 | 2         | 4.26%   |
| 2016 | 2         | 4.26%   |
| 2014 | 2         | 4.26%   |
| 2011 | 2         | 4.26%   |
| 2008 | 1         | 2.13%   |
| 2006 | 1         | 2.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 31        | 65.96%  |
| Desktop     | 13        | 27.66%  |
| All in one  | 2         | 4.26%   |
| Convertible | 1         | 2.13%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 47        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 47        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 18        | 38.3%   |
| 4.01-8.0   | 11        | 23.4%   |
| 8.01-16.0  | 7         | 14.89%  |
| 16.01-24.0 | 6         | 12.77%  |
| 2.01-3.0   | 2         | 4.26%   |
| 1.01-2.0   | 2         | 4.26%   |
| 32.01-64.0 | 1         | 2.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 22        | 43.14%  |
| 2.01-3.0   | 16        | 31.37%  |
| 3.01-4.0   | 7         | 13.73%  |
| 4.01-8.0   | 3         | 5.88%   |
| 24.01-32.0 | 1         | 1.96%   |
| 8.01-16.0  | 1         | 1.96%   |
| 0.51-1.0   | 1         | 1.96%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 30        | 63.83%  |
| 2      | 14        | 29.79%  |
| 3      | 2         | 4.26%   |
| 4      | 1         | 2.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 27        | 57.45%  |
| No        | 20        | 42.55%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 95.74%  |
| No        | 2         | 4.26%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 80.85%  |
| No        | 9         | 19.15%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 63.83%  |
| No        | 17        | 36.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Turkey  | 41        | 87.23%  |
| UK      | 1         | 2.13%   |
| Sweden  | 1         | 2.13%   |
| Italy   | 1         | 2.13%   |
| Germany | 1         | 2.13%   |
| France  | 1         | 2.13%   |
| Brazil  | 1         | 2.13%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Istanbul             | 14        | 28%     |
| Bursa                | 6         | 12%     |
| Ankara               | 5         | 10%     |
| Izmir                | 4         | 8%      |
| Aydin                | 4         | 8%      |
| Konya                | 2         | 4%      |
| Çanakkale           | 2         | 4%      |
| Yaman                | 1         | 2%      |
| Soleymieu            | 1         | 2%      |
| Sao Gabriel          | 1         | 2%      |
| Samsun               | 1         | 2%      |
| Malatya              | 1         | 2%      |
| London               | 1         | 2%      |
| Landskrona           | 1         | 2%      |
| Kirchheim unter Teck | 1         | 2%      |
| Gaziantep            | 1         | 2%      |
| Esenyurt             | 1         | 2%      |
| Bolzano              | 1         | 2%      |
| Artvin               | 1         | 2%      |
| Antalya              | 1         | 2%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 14        | 17     | 21.88%  |
| Samsung Electronics | 8         | 10     | 12.5%   |
| Seagate             | 7         | 8      | 10.94%  |
| SanDisk             | 4         | 4      | 6.25%   |
| Kingston            | 3         | 4      | 4.69%   |
| A-DATA Technology   | 3         | 3      | 4.69%   |
| Unknown             | 2         | 3      | 3.13%   |
| Toshiba             | 2         | 3      | 3.13%   |
| SK hynix            | 2         | 2      | 3.13%   |
| KIOXIA-EXCERIA      | 2         | 2      | 3.13%   |
| Hitachi             | 2         | 2      | 3.13%   |
| HGST                | 2         | 2      | 3.13%   |
| China               | 2         | 2      | 3.13%   |
| Team                | 1         | 1      | 1.56%   |
| SPCC                | 1         | 1      | 1.56%   |
| Silicon Motion      | 1         | 1      | 1.56%   |
| Phison              | 1         | 1      | 1.56%   |
| Micron Technology   | 1         | 2      | 1.56%   |
| Lexar               | 1         | 1      | 1.56%   |
| KingSpec            | 1         | 1      | 1.56%   |
| Intenso             | 1         | 2      | 1.56%   |
| Corsair             | 1         | 1      | 1.56%   |
| addlink             | 1         | 1      | 1.56%   |
| Unknown             | 1         | 1      | 1.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| WDC WD6402AAEX-00Y9A0 640GB                 | 3         | 4.55%   |
| A-DATA SU650 120GB SSD                      | 3         | 4.55%   |
| SanDisk SSD PLUS 240GB                      | 2         | 3.03%   |
| HGST HTS545050A7E680 500GB                  | 2         | 3.03%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD            | 1         | 1.52%   |
| WDC WD5000LPVX-55V0TT0 500GB                | 1         | 1.52%   |
| WDC WD5000LPCX-60VHAT0 500GB                | 1         | 1.52%   |
| WDC WD5000LPCX-21VHAT0 500GB                | 1         | 1.52%   |
| WDC WD5000AAKX-00ERMA0 500GB                | 1         | 1.52%   |
| WDC WD3200BPVT-35JJ5T0 320GB                | 1         | 1.52%   |
| WDC WD3200AAJB-00WGA0 320GB                 | 1         | 1.52%   |
| WDC WD2500BEVS-00UST0 250GB                 | 1         | 1.52%   |
| WDC WD10JPVX-60JC3T0 1TB                    | 1         | 1.52%   |
| WDC WD10JPCX-24UE4T0 1TB                    | 1         | 1.52%   |
| WDC WD10EZEX-60WN4A0 1TB                    | 1         | 1.52%   |
| Unknown SD/MMC/MS PRO 64GB                  | 1         | 1.52%   |
| Unknown MMC Card  64GB                      | 1         | 1.52%   |
| Toshiba MK6475GSX 640GB                     | 1         | 1.52%   |
| Toshiba DT01ACA100 1TB                      | 1         | 1.52%   |
| Team T253X1240G 240GB SSD                   | 1         | 1.52%   |
| SPCC Solid State Disk 512GB                 | 1         | 1.52%   |
| SK hynix SC311 SATA 256GB SSD               | 1         | 1.52%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB     | 1         | 1.52%   |
| Silicon Motion Longline SSD 512GB           | 1         | 1.52%   |
| Seagate ST9500325AS 500GB                   | 1         | 1.52%   |
| Seagate ST9120822AS 120GB                   | 1         | 1.52%   |
| Seagate ST3160318AS 160GB                   | 1         | 1.52%   |
| Seagate ST2000DM008-2FR102 2TB              | 1         | 1.52%   |
| Seagate ST1000LM035-1RK172 1TB              | 1         | 1.52%   |
| Seagate Expansion 4TB                       | 1         | 1.52%   |
| Seagate BarraCuda Q1 SSD ZA480CV10001 480GB | 1         | 1.52%   |
| SanDisk Ultra II 240GB SSD                  | 1         | 1.52%   |
| SanDisk SDSSDA480G 480GB                    | 1         | 1.52%   |
| Samsung SSD 860 EVO 500GB                   | 1         | 1.52%   |
| Samsung NVMe SSD Drive 512GB                | 1         | 1.52%   |
| Samsung MZALQ256HAJD-000L1 256GB            | 1         | 1.52%   |
| Samsung MZ7LN128HAHQ-000L2 128GB SSD        | 1         | 1.52%   |
| Samsung MZ7LF192HCGS-000L1 192GB SSD        | 1         | 1.52%   |
| Samsung HM250HI 250GB                       | 1         | 1.52%   |
| Samsung HD501LJ 500GB                       | 1         | 1.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 13        | 16     | 44.83%  |
| Seagate             | 6         | 7      | 20.69%  |
| Samsung Electronics | 3         | 4      | 10.34%  |
| Toshiba             | 2         | 3      | 6.9%    |
| Hitachi             | 2         | 2      | 6.9%    |
| HGST                | 2         | 2      | 6.9%    |
| Unknown             | 1         | 2      | 3.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 4         | 4      | 14.81%  |
| Samsung Electronics | 3         | 3      | 11.11%  |
| Kingston            | 3         | 4      | 11.11%  |
| A-DATA Technology   | 3         | 3      | 11.11%  |
| KIOXIA-EXCERIA      | 2         | 2      | 7.41%   |
| China               | 2         | 2      | 7.41%   |
| WDC                 | 1         | 1      | 3.7%    |
| Team                | 1         | 1      | 3.7%    |
| SPCC                | 1         | 1      | 3.7%    |
| SK hynix            | 1         | 1      | 3.7%    |
| Seagate             | 1         | 1      | 3.7%    |
| Micron Technology   | 1         | 2      | 3.7%    |
| Lexar               | 1         | 1      | 3.7%    |
| KingSpec            | 1         | 1      | 3.7%    |
| Intenso             | 1         | 2      | 3.7%    |
| Corsair             | 1         | 1      | 3.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 26        | 36     | 46.43%  |
| SSD     | 23        | 30     | 41.07%  |
| NVMe    | 4         | 6      | 7.14%   |
| Unknown | 2         | 2      | 3.57%   |
| MMC     | 1         | 1      | 1.79%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 43        | 65     | 86%     |
| NVMe | 4         | 6      | 8%      |
| SAS  | 2         | 3      | 4%      |
| MMC  | 1         | 1      | 2%      |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 35        | 46     | 71.43%  |
| 0.51-1.0   | 12        | 17     | 24.49%  |
| 3.01-4.0   | 1         | 1      | 2.04%   |
| 1.01-2.0   | 1         | 2      | 2.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 23        | 47.92%  |
| 251-500    | 12        | 25%     |
| 501-1000   | 6         | 12.5%   |
| 51-100     | 4         | 8.33%   |
| 21-50      | 2         | 4.17%   |
| 2001-3000  | 1         | 2.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 19        | 39.58%  |
| 21-50    | 12        | 25%     |
| 51-100   | 9         | 18.75%  |
| 101-250  | 6         | 12.5%   |
| 251-500  | 1         | 2.08%   |
| 501-1000 | 1         | 2.08%   |

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
| Detected | 33        | 54     | 67.35%  |
| Works    | 13        | 18     | 26.53%  |
| Malfunc  | 3         | 3      | 6.12%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 37        | 69.81%  |
| AMD                      | 8         | 15.09%  |
| Marvell Technology Group | 3         | 5.66%   |
| Samsung Electronics      | 2         | 3.77%   |
| SK hynix                 | 1         | 1.89%   |
| Silicon Motion           | 1         | 1.89%   |
| Phison Electronics       | 1         | 1.89%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 7         | 10.94%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 4         | 6.25%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 4         | 6.25%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                  | 3         | 4.69%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 3         | 4.69%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                 | 3         | 4.69%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                           | 3         | 4.69%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 4.69%   |
| Samsung NVMe SSD Controller 980                                                        | 2         | 3.13%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 2         | 3.13%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 2         | 3.13%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                       | 2         | 3.13%   |
| AMD FCH SATA Controller D                                                              | 2         | 3.13%   |
| SK hynix BC511                                                                         | 1         | 1.56%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 1         | 1.56%   |
| Phison PS5013 E13 NVMe Controller                                                      | 1         | 1.56%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 1         | 1.56%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 1         | 1.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 1.56%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 1         | 1.56%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 1         | 1.56%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 1         | 1.56%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                             | 1         | 1.56%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 1         | 1.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 1         | 1.56%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 1         | 1.56%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 1         | 1.56%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 1.56%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 1.56%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 1         | 1.56%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.56%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 1         | 1.56%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 1         | 1.56%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 1         | 1.56%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 1         | 1.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 1         | 1.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 37        | 72.55%  |
| IDE  | 9         | 17.65%  |
| NVMe | 4         | 7.84%   |
| RAID | 1         | 1.96%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 38        | 80.85%  |
| AMD    | 9         | 19.15%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 3         | 6.38%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 4.26%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 4.26%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 2.13%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 1         | 2.13%   |
| Intel Core i9-9900 CPU @ 3.10GHz              | 1         | 2.13%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 2.13%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 2.13%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 2.13%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 1         | 2.13%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 2.13%   |
| Intel Core i5-7600 CPU @ 3.50GHz              | 1         | 2.13%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 2.13%   |
| Intel Core i5-6400T CPU @ 2.20GHz             | 1         | 2.13%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 2.13%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 1         | 2.13%   |
| Intel Core i5-4440 CPU @ 3.10GHz              | 1         | 2.13%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 2.13%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 1         | 2.13%   |
| Intel Core i3-9100F CPU @ 3.60GHz             | 1         | 2.13%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 2.13%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 2.13%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 1         | 2.13%   |
| Intel Core i3-3227U CPU @ 1.90GHz             | 1         | 2.13%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 1         | 2.13%   |
| Intel Core i3 CPU 540 @ 3.07GHz               | 1         | 2.13%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz         | 1         | 2.13%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz          | 1         | 2.13%   |
| Intel Core 2 CPU T5600 @ 1.83GHz              | 1         | 2.13%   |
| Intel Core 2 CPU T5200 @ 1.60GHz              | 1         | 2.13%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 1         | 2.13%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 1         | 2.13%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 2.13%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 2.13%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 1         | 2.13%   |
| AMD Ryzen 5 3500X 6-Core Processor            | 1         | 2.13%   |
| AMD C-50 Processor                            | 1         | 2.13%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 1         | 2.13%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G  | 1         | 2.13%   |
| AMD A8-9600 RADEON R7, 10 COMPUTE CORES 4C+6G | 1         | 2.13%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 10        | 21.28%  |
| Intel Core i3     | 9         | 19.15%  |
| Intel Core i7     | 5         | 10.64%  |
| Other             | 4         | 8.51%   |
| Intel Core 2 Quad | 4         | 8.51%   |
| AMD A8            | 3         | 6.38%   |
| Intel Pentium     | 2         | 4.26%   |
| Intel Core 2      | 2         | 4.26%   |
| Intel Celeron     | 2         | 4.26%   |
| AMD Ryzen 5       | 2         | 4.26%   |
| Intel Core i9     | 1         | 2.13%   |
| Intel Core 2 Duo  | 1         | 2.13%   |
| AMD C-50          | 1         | 2.13%   |
| AMD A10           | 1         | 2.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 25        | 53.19%  |
| 4      | 17        | 36.17%  |
| 6      | 4         | 8.51%   |
| 8      | 1         | 2.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 47        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 25        | 53.19%  |
| 1      | 22        | 46.81%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 47        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 29        | 61.7%   |
| 0x07030105 | 2         | 4.26%   |
| 0x906eb    | 1         | 2.13%   |
| 0x906ea    | 1         | 2.13%   |
| 0x906e9    | 1         | 2.13%   |
| 0x806ea    | 1         | 2.13%   |
| 0x806c1    | 1         | 2.13%   |
| 0x6f6      | 1         | 2.13%   |
| 0x506e3    | 1         | 2.13%   |
| 0x406e3    | 1         | 2.13%   |
| 0x306d4    | 1         | 2.13%   |
| 0x306c3    | 1         | 2.13%   |
| 0x306a9    | 1         | 2.13%   |
| 0x20655    | 1         | 2.13%   |
| 0x08608102 | 1         | 2.13%   |
| 0x06006705 | 1         | 2.13%   |
| 0x0600611a | 1         | 2.13%   |
| 0x05000029 | 1         | 2.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 8         | 17.02%  |
| Core        | 6         | 12.77%  |
| Haswell     | 4         | 8.51%   |
| Excavator   | 4         | 8.51%   |
| Westmere    | 3         | 6.38%   |
| SandyBridge | 3         | 6.38%   |
| IvyBridge   | 3         | 6.38%   |
| Broadwell   | 3         | 6.38%   |
| TigerLake   | 2         | 4.26%   |
| Skylake     | 2         | 4.26%   |
| Puma        | 2         | 4.26%   |
| Zen 2       | 1         | 2.13%   |
| Silvermont  | 1         | 2.13%   |
| Penryn      | 1         | 2.13%   |
| Goldmont    | 1         | 2.13%   |
| CometLake   | 1         | 2.13%   |
| Bobcat      | 1         | 2.13%   |
| Unknown     | 1         | 2.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 29        | 50.88%  |
| AMD    | 15        | 26.32%  |
| Nvidia | 13        | 22.81%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia GT200 [GeForce GTX 260]                                                           | 3         | 4.62%   |
| Intel HD Graphics 5500                                                                   | 3         | 4.62%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 4.62%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 3.08%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 3.08%   |
| Intel UHD Graphics 620                                                                   | 2         | 3.08%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 3.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 3.08%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 3.08%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 3.08%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 3.08%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 3.08%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 3.08%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 1         | 1.54%   |
| Nvidia GT218M [GeForce 315M]                                                             | 1         | 1.54%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 1.54%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 1.54%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 1.54%   |
| Nvidia GF108M [GeForce GT 420M]                                                          | 1         | 1.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 1.54%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.54%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 1.54%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 1         | 1.54%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.54%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.54%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 1.54%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.54%   |
| Intel HD Graphics 630                                                                    | 1         | 1.54%   |
| Intel HD Graphics 620                                                                    | 1         | 1.54%   |
| Intel HD Graphics 530                                                                    | 1         | 1.54%   |
| Intel HD Graphics 520                                                                    | 1         | 1.54%   |
| Intel HD Graphics 500                                                                    | 1         | 1.54%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1.54%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.54%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 1.54%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 1.54%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.54%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.54%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1         | 1.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 19        | 40.43%  |
| 1 x Nvidia     | 9         | 19.15%  |
| 1 x AMD        | 7         | 14.89%  |
| 2 x AMD        | 5         | 10.64%  |
| Intel + Nvidia | 4         | 8.51%   |
| Intel + AMD    | 3         | 6.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 46        | 97.87%  |
| Proprietary | 1         | 2.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 36        | 76.6%   |
| 0.01-0.5   | 6         | 12.77%  |
| 0.51-1.0   | 3         | 6.38%   |
| 5.01-6.0   | 1         | 2.13%   |
| 1.01-2.0   | 1         | 2.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 6         | 12.77%  |
| Goldstar                | 6         | 12.77%  |
| LG Display              | 5         | 10.64%  |
| Chimei Innolux          | 5         | 10.64%  |
| BOE                     | 5         | 10.64%  |
| AU Optronics            | 5         | 10.64%  |
| LG Philips              | 2         | 4.26%   |
| Dell                    | 2         | 4.26%   |
| Chi Mei Optoelectronics | 2         | 4.26%   |
| Acer                    | 2         | 4.26%   |
| SAC                     | 1         | 2.13%   |
| Lenovo                  | 1         | 2.13%   |
| Iiyama                  | 1         | 2.13%   |
| Hewlett-Packard         | 1         | 2.13%   |
| Beko                    | 1         | 2.13%   |
| AOC                     | 1         | 2.13%   |
| AGO                     | 1         | 2.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Goldstar W2242 GSM5678 1680x1050 474x296mm 22.0-inch                     | 3         | 6.25%   |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch        | 1         | 2.08%   |
| Samsung Electronics SyncMaster SAM0599 1600x900 443x249mm 20.0-inch      | 1         | 2.08%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch     | 1         | 2.08%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 1         | 2.08%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 1         | 2.08%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 1         | 2.08%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch     | 1         | 2.08%   |
| SAC Casper SAC3219 1366x768 304x228mm 15.0-inch                          | 1         | 2.08%   |
| LG Philips LCD Monitor LPLDB00 1280x800 331x207mm 15.4-inch              | 1         | 2.08%   |
| LG Philips LCD Monitor LPL1146 1280x800 331x207mm 15.4-inch              | 1         | 2.08%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 1         | 2.08%   |
| LG Display LCD Monitor LGD0470 1920x1080 345x194mm 15.6-inch             | 1         | 2.08%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch              | 1         | 2.08%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch              | 1         | 2.08%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch              | 1         | 2.08%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 1         | 2.08%   |
| Iiyama PLX2380H IVM5621 1920x1080 509x286mm 23.0-inch                    | 1         | 2.08%   |
| Hewlett-Packard Contino HPN4018 1920x1080 527x296mm 23.8-inch            | 1         | 2.08%   |
| Goldstar L1753T GSM4476 1280x1024 338x270mm 17.0-inch                    | 1         | 2.08%   |
| Goldstar E2242 GSM58BE 1920x1080 477x268mm 21.5-inch                     | 1         | 2.08%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                   | 1         | 2.08%   |
| Dell P2717H DEL40F6 1920x1080 598x336mm 27.0-inch                        | 1         | 2.08%   |
| Dell E2421HN DELF129 1920x1080 527x296mm 23.8-inch                       | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x193mm 15.5-inch          | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 1         | 2.08%   |
| Chi Mei Optoelectronics LCD Monitor CMO1703 1440x900 367x230mm 17.1-inch | 1         | 2.08%   |
| Chi Mei Optoelectronics LCD Monitor CMO15AB 1366x768 340x190mm 15.3-inch | 1         | 2.08%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 1         | 2.08%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 1         | 2.08%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 1         | 2.08%   |
| BOE LCD Monitor BOE0661 1366x768 344x194mm 15.5-inch                     | 1         | 2.08%   |
| BOE LCD Monitor BOE065E 1920x1080 344x194mm 15.5-inch                    | 1         | 2.08%   |
| Beko BK WUXGA BEK4448 1920x1080                                          | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 1         | 2.08%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch           | 1         | 2.08%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 18        | 39.13%  |
| 1920x1080 (FHD)    | 15        | 32.61%  |
| 1680x1050 (WSXGA+) | 3         | 6.52%   |
| 1600x900 (HD+)     | 3         | 6.52%   |
| 1280x800 (WXGA)    | 2         | 4.35%   |
| 1280x1024 (SXGA)   | 2         | 4.35%   |
| 3840x2160 (4K)     | 1         | 2.17%   |
| 2160x1440          | 1         | 2.17%   |
| 1440x900 (WXGA+)   | 1         | 2.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 23        | 47.92%  |
| 23     | 7         | 14.58%  |
| 17     | 3         | 6.25%   |
| 14     | 3         | 6.25%   |
| 21     | 2         | 4.17%   |
| 13     | 2         | 4.17%   |
| 72     | 1         | 2.08%   |
| 31     | 1         | 2.08%   |
| 27     | 1         | 2.08%   |
| 22     | 1         | 2.08%   |
| 20     | 1         | 2.08%   |
| 19     | 1         | 2.08%   |
| 12     | 1         | 2.08%   |
| 11     | 1         | 2.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 28        | 59.57%  |
| 401-500     | 8         | 17.02%  |
| 501-600     | 5         | 10.64%  |
| 201-300     | 3         | 6.38%   |
| 601-700     | 1         | 2.13%   |
| 351-400     | 1         | 2.13%   |
| 1501-2000   | 1         | 2.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 34        | 73.91%  |
| 3/2   | 4         | 8.7%    |
| 16/10 | 4         | 8.7%    |
| 5/4   | 2         | 4.35%   |
| 4/3   | 2         | 4.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 23        | 47.92%  |
| 201-250        | 10        | 20.83%  |
| 81-90          | 5         | 10.42%  |
| 151-200        | 2         | 4.17%   |
| 141-150        | 2         | 4.17%   |
| More than 1000 | 1         | 2.08%   |
| 71-80          | 1         | 2.08%   |
| 51-60          | 1         | 2.08%   |
| 351-500        | 1         | 2.08%   |
| 301-350        | 1         | 2.08%   |
| 131-140        | 1         | 2.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 18        | 37.5%   |
| 51-100  | 17        | 35.42%  |
| 121-160 | 10        | 20.83%  |
| 161-240 | 2         | 4.17%   |
| 1-50    | 1         | 2.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 42        | 89.36%  |
| 2     | 4         | 8.51%   |
| 0     | 1         | 2.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 38        | 53.52%  |
| Intel                 | 15        | 21.13%  |
| Qualcomm Atheros      | 6         | 8.45%   |
| Broadcom              | 3         | 4.23%   |
| Ralink Technology     | 2         | 2.82%   |
| Ralink                | 2         | 2.82%   |
| ASUSTek Computer      | 2         | 2.82%   |
| ZyXEL Communications  | 1         | 1.41%   |
| Xiaomi                | 1         | 1.41%   |
| JMicron Technology    | 1         | 1.41%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 29        | 32.95%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 7         | 7.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 4         | 4.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 3         | 3.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 3         | 3.41%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 3         | 3.41%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 2         | 2.27%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 2         | 2.27%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]         | 1         | 1.14%   |
| Xiaomi Mi/Redmi series (RNDIS)                                       | 1         | 1.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 1         | 1.14%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                      | 1         | 1.14%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                               | 1         | 1.14%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 1         | 1.14%   |
| Realtek RTL8152 Fast Ethernet Adapter                                | 1         | 1.14%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 1         | 1.14%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 1         | 1.14%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                            | 1         | 1.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 1         | 1.14%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 1         | 1.14%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller               | 1         | 1.14%   |
| Intel Wireless 8265 / 8275                                           | 1         | 1.14%   |
| Intel Wireless 7265                                                  | 1         | 1.14%   |
| Intel Wi-Fi 6 AX201                                                  | 1         | 1.14%   |
| Intel Wi-Fi 6 AX200                                                  | 1         | 1.14%   |
| Intel Ethernet Connection I217-LM                                    | 1         | 1.14%   |
| Intel Ethernet Connection (7) I219-LM                                | 1         | 1.14%   |
| Intel Ethernet Connection (3) I218-V                                 | 1         | 1.14%   |
| Intel Ethernet Connection (2) I219-V                                 | 1         | 1.14%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 1         | 1.14%   |
| Intel Centrino Wireless-N 2230                                       | 1         | 1.14%   |
| Intel Centrino Wireless-N 130                                        | 1         | 1.14%   |
| Intel Centrino Ultimate-N 6300                                       | 1         | 1.14%   |
| Intel Centrino Advanced-N 6200                                       | 1         | 1.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 1         | 1.14%   |
| Intel 82577LC Gigabit Network Connection                             | 1         | 1.14%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile | 1         | 1.14%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                      | 1         | 1.14%   |
| Broadcom BCM43225 802.11b/g/n                                        | 1         | 1.14%   |
| Broadcom BCM43142 802.11b/g/n                                        | 1         | 1.14%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 13        | 31.71%  |
| Realtek Semiconductor | 12        | 29.27%  |
| Qualcomm Atheros      | 6         | 14.63%  |
| Broadcom              | 3         | 7.32%   |
| Ralink Technology     | 2         | 4.88%   |
| Ralink                | 2         | 4.88%   |
| ASUSTek Computer      | 2         | 4.88%   |
| ZyXEL Communications  | 1         | 2.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 9.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 3         | 7.32%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 7.32%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 7.32%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 4.88%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 2         | 4.88%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]   | 1         | 2.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.44%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 2.44%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 2.44%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 2.44%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 2.44%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 2.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 2.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 2.44%   |
| Intel Wireless 8265 / 8275                                     | 1         | 2.44%   |
| Intel Wireless 7265                                            | 1         | 2.44%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 2.44%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 2.44%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 2.44%   |
| Intel Centrino Wireless-N 2230                                 | 1         | 2.44%   |
| Intel Centrino Wireless-N 130                                  | 1         | 2.44%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 2.44%   |
| Intel Centrino Advanced-N 6200                                 | 1         | 2.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 2.44%   |
| Broadcom BCM43225 802.11b/g/n                                  | 1         | 2.44%   |
| Broadcom BCM43142 802.11b/g/n                                  | 1         | 2.44%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 2.44%   |
| ASUS 802.11n NIC                                               | 1         | 2.44%   |
| ASUS 802.11ac NIC                                              | 1         | 2.44%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 37        | 80.43%  |
| Intel                 | 6         | 13.04%  |
| Xiaomi                | 1         | 2.17%   |
| JMicron Technology    | 1         | 2.17%   |
| Broadcom              | 1         | 2.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 29        | 61.7%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 7         | 14.89%  |
| Xiaomi Mi/Redmi series (RNDIS)                                       | 1         | 2.13%   |
| Realtek RTL8152 Fast Ethernet Adapter                                | 1         | 2.13%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 1         | 2.13%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller               | 1         | 2.13%   |
| Intel Ethernet Connection I217-LM                                    | 1         | 2.13%   |
| Intel Ethernet Connection (7) I219-LM                                | 1         | 2.13%   |
| Intel Ethernet Connection (3) I218-V                                 | 1         | 2.13%   |
| Intel Ethernet Connection (2) I219-V                                 | 1         | 2.13%   |
| Intel 82577LC Gigabit Network Connection                             | 1         | 2.13%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile | 1         | 2.13%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                      | 1         | 2.13%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 45        | 54.22%  |
| WiFi     | 38        | 45.78%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 32        | 64%     |
| Ethernet | 18        | 36%     |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 33        | 70.21%  |
| 1     | 14        | 29.79%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 44        | 93.62%  |
| Yes  | 3         | 6.38%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 8         | 26.67%  |
| Realtek Semiconductor           | 7         | 23.33%  |
| Qualcomm Atheros Communications | 3         | 10%     |
| Toshiba                         | 2         | 6.67%   |
| Lite-On Technology              | 2         | 6.67%   |
| IMC Networks                    | 2         | 6.67%   |
| Cambridge Silicon Radio         | 2         | 6.67%   |
| Realtek                         | 1         | 3.33%   |
| Ralink                          | 1         | 3.33%   |
| Foxconn / Hon Hai               | 1         | 3.33%   |
| Broadcom                        | 1         | 3.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 4         | 13.33%  |
| Intel Bluetooth wireless interface                  | 3         | 10%     |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 6.67%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 6.67%   |
| Toshiba RT Bluetooth Radio                          | 1         | 3.33%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 3.33%   |
| Realtek RTL8821A Bluetooth                          | 1         | 3.33%   |
| Realtek RTL8723B Bluetooth                          | 1         | 3.33%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 3.33%   |
| Realtek Bluetooth Radio                             | 1         | 3.33%   |
| Ralink RT3290 Bluetooth                             | 1         | 3.33%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 3.33%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 3.33%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 3.33%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 3.33%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 3.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 3.33%   |
| Intel AX201 Bluetooth                               | 1         | 3.33%   |
| Intel AX200 Bluetooth                               | 1         | 3.33%   |
| IMC Networks Bluetooth Radio                        | 1         | 3.33%   |
| IMC Networks Bluetooth Device                       | 1         | 3.33%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 3.33%   |
| Broadcom HP Portable Valentine                      | 1         | 3.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 38        | 66.67%  |
| AMD                   | 12        | 21.05%  |
| Nvidia                | 5         | 8.77%   |
| Kingston Technology   | 1         | 1.75%   |
| Barco Display Systems | 1         | 1.75%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 4         | 5.71%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 5.71%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 5.71%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 5.71%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 4.29%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 4.29%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 4.29%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 4.29%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 4.29%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 4.29%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 2.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 2.86%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 2.86%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 2.86%   |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 2.86%   |
| AMD High Definition Audio Controller                                                              | 2         | 2.86%   |
| AMD FCH Azalia Controller                                                                         | 2         | 2.86%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.43%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.43%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.43%   |
| Kingston Technology HyperX QuadCast S                                                             | 1         | 1.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.43%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1.43%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 1.43%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.43%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.43%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.43%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 1.43%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.43%   |
| Barco Display Systems USBGH520-ENC                                                                | 1         | 1.43%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.43%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                                                | 1         | 1.43%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1         | 1.43%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 1.43%   |
| AMD RV630 HDMI Audio [Radeon HD 2600 PRO/XT / HD 3610]                                            | 1         | 1.43%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 1.43%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 1         | 1.43%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 1         | 1.43%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 6         | 35.29%  |
| SK hynix            | 2         | 11.76%  |
| Kingston            | 2         | 11.76%  |
| A-DATA Technology   | 2         | 11.76%  |
| Unknown (0x4509)    | 1         | 5.88%   |
| Unknown             | 1         | 5.88%   |
| Micron Technology   | 1         | 5.88%   |
| Kingmax             | 1         | 5.88%   |
| G.Skill             | 1         | 5.88%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR2                              | 1         | 5.56%   |
| Unknown (0x4509) RAM GKE800SO102408-2666A 8GB SODIMM DDR4 2133MT/s | 1         | 5.56%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s       | 1         | 5.56%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s             | 1         | 5.56%   |
| Samsung RAM M471B5773CHS-CH9 2GB DIMM DDR3 1333MT/s                | 1         | 5.56%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s              | 1         | 5.56%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s              | 1         | 5.56%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s              | 1         | 5.56%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s              | 1         | 5.56%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s              | 1         | 5.56%   |
| Micron RAM 8KTF51264HDZ-1G6E1 4GB SODIMM DDR3 1600MT/s             | 1         | 5.56%   |
| Kingston RAM KHX3000C15D4/8GX 8GB DIMM DDR4 3400MT/s               | 1         | 5.56%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s                  | 1         | 5.56%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s            | 1         | 5.56%   |
| Kingmax RAM FSFE85F-C8KL9 2GB DIMM DDR3 1333MT/s                   | 1         | 5.56%   |
| G.Skill RAM F4-2133C15-4GIS 4GB DIMM DDR4 2133MT/s                 | 1         | 5.56%   |
| A-DATA RAM Module 8GB DIMM DDR4 2667MT/s                           | 1         | 5.56%   |
| A-DATA RAM AO1P21FC8T1-BSKS 8GB SODIMM DDR4 2133MT/s               | 1         | 5.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind  | Computers | Percent |
|-------|-----------|---------|
| DDR4  | 11        | 64.71%  |
| DDR3  | 4         | 23.53%  |
| SDRAM | 1         | 5.88%   |
| DDR2  | 1         | 5.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 11        | 68.75%  |
| DIMM         | 4         | 25%     |
| Row Of Chips | 1         | 6.25%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size | Computers | Percent |
|------|-----------|---------|
| 8192 | 9         | 56.25%  |
| 4096 | 5         | 31.25%  |
| 2048 | 2         | 12.5%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2133    | 4         | 23.53%  |
| 3200    | 3         | 17.65%  |
| 2667    | 3         | 17.65%  |
| 1600    | 3         | 17.65%  |
| 3400    | 1         | 5.88%   |
| 2400    | 1         | 5.88%   |
| 1333    | 1         | 5.88%   |
| Unknown | 1         | 5.88%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Zebra           | 3         | 42.86%  |
| Canon           | 3         | 42.86%  |
| Hewlett-Packard | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Zebra TLP2844                    | 2         | 28.57%  |
| Zebra Zebra GC420d Label Printer | 1         | 14.29%  |
| HP LaserJet P1102                | 1         | 14.29%  |
| Canon PIXMA MX340                | 1         | 14.29%  |
| Canon LBP6030w/6018w             | 1         | 14.29%  |
| Canon LBP6000                    | 1         | 14.29%  |

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
| Chicony Electronics                    | 12        | 37.5%   |
| Microdia                               | 3         | 9.38%   |
| IMC Networks                           | 3         | 9.38%   |
| Realtek Semiconductor                  | 2         | 6.25%   |
| Luxvisions Innotech Limited            | 2         | 6.25%   |
| Acer                                   | 2         | 6.25%   |
| Suyin                                  | 1         | 3.13%   |
| Silicon Motion                         | 1         | 3.13%   |
| MacroSilicon                           | 1         | 3.13%   |
| Lite-On Technology                     | 1         | 3.13%   |
| Foxconn / Hon Hai                      | 1         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.13%   |
| Arkmicro Technologies                  | 1         | 3.13%   |
| ALi                                    | 1         | 3.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony EasyCamera                                  | 2         | 6.25%   |
| Acer EasyCamera                                     | 2         | 6.25%   |
| Suyin HP Webcam                                     | 1         | 3.13%   |
| Silicon Motion WebCam SC-0311139N                   | 1         | 3.13%   |
| Realtek Lenovo EasyCamera                           | 1         | 3.13%   |
| Realtek HP Truevision HD integrated webcam          | 1         | 3.13%   |
| Microdia Laptop_Integrated_Webcam_HD                | 1         | 3.13%   |
| Microdia Integrated_Webcam_HD                       | 1         | 3.13%   |
| Microdia Integrated Camera                          | 1         | 3.13%   |
| MacroSilicon USB Video                              | 1         | 3.13%   |
| Luxvisions Innotech Limited Integrated Camera       | 1         | 3.13%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 3.13%   |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 3.13%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 3.13%   |
| IMC Networks Lenovo EasyCamera                      | 1         | 3.13%   |
| IMC Networks EasyCamera                             | 1         | 3.13%   |
| Foxconn / Hon Hai USB2.0 Camera                     | 1         | 3.13%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 3.13%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 3.13%   |
| Chicony USB2.0 Camera                               | 1         | 3.13%   |
| Chicony Integrated Camera                           | 1         | 3.13%   |
| Chicony HP Truevision HD                            | 1         | 3.13%   |
| Chicony HP High Definition 1MP Webcam               | 1         | 3.13%   |
| Chicony Gateway USB 2.0 Webcam                      | 1         | 3.13%   |
| Chicony Front Camera                                | 1         | 3.13%   |
| Chicony CNF9055 Toshiba Webcam                      | 1         | 3.13%   |
| Chicony CNA7157                                     | 1         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 1         | 3.13%   |
| Arkmicro USB2.0 PC CAMERA                           | 1         | 3.13%   |
| ALi Gateway Webcam                                  | 1         | 3.13%   |

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
| 0     | 37        | 75.51%  |
| 1     | 9         | 18.37%  |
| 2     | 3         | 6.12%   |

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

