Fedora 36 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Fedora 36.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 63

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | Modern 14 B4MW              | [5d8e6ca082](https://linux-hardware.org/?probe=5d8e6ca082) | Apr 16, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [6f75f679f9](https://linux-hardware.org/?probe=6f75f679f9) | Apr 16, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [5bff5642ba](https://linux-hardware.org/?probe=5bff5642ba) | Apr 15, 2022 |
| Toshiba       | Satellite U840              | [9468123a43](https://linux-hardware.org/?probe=9468123a43) | Apr 15, 2022 |
| Dell          | Studio 1537                 | [56c84908d2](https://linux-hardware.org/?probe=56c84908d2) | Apr 15, 2022 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [7436528d4f](https://linux-hardware.org/?probe=7436528d4f) | Apr 14, 2022 |
| Dell          | Inspiron 3505               | [719a1712f2](https://linux-hardware.org/?probe=719a1712f2) | Apr 14, 2022 |
| Dell          | Inspiron 3505               | [5781ceb5ca](https://linux-hardware.org/?probe=5781ceb5ca) | Apr 14, 2022 |
| Dell          | Inspiron 5548               | [77a3c1a7ce](https://linux-hardware.org/?probe=77a3c1a7ce) | Apr 14, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [9dd2675f34](https://linux-hardware.org/?probe=9dd2675f34) | Apr 14, 2022 |
| Dell          | XPS 13 9370                 | [0175e41474](https://linux-hardware.org/?probe=0175e41474) | Apr 14, 2022 |
| Dell          | XPS 13 9305                 | [48c7781b77](https://linux-hardware.org/?probe=48c7781b77) | Apr 14, 2022 |
| Dell          | Precision 7540              | [2aff9a81ff](https://linux-hardware.org/?probe=2aff9a81ff) | Apr 13, 2022 |
| Toshiba       | Satellite U840              | [c6fe138c8f](https://linux-hardware.org/?probe=c6fe138c8f) | Apr 13, 2022 |
| HP            | Laptop 15-dw3xxx            | [95cff2fbb1](https://linux-hardware.org/?probe=95cff2fbb1) | Apr 13, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [8421f0505f](https://linux-hardware.org/?probe=8421f0505f) | Apr 13, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [c3d7c67155](https://linux-hardware.org/?probe=c3d7c67155) | Apr 12, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [73bb0eeab0](https://linux-hardware.org/?probe=73bb0eeab0) | Apr 12, 2022 |
| Intel         | W7650                       | [4bd778e810](https://linux-hardware.org/?probe=4bd778e810) | Apr 11, 2022 |
| MSI           | GS66 Stealth 10UH           | [5589b339ed](https://linux-hardware.org/?probe=5589b339ed) | Apr 11, 2022 |
| Dell          | Studio 1537                 | [048fceac96](https://linux-hardware.org/?probe=048fceac96) | Apr 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [5a60603c45](https://linux-hardware.org/?probe=5a60603c45) | Apr 11, 2022 |
| HP            | Pavilion 15                 | [c913cb5a4a](https://linux-hardware.org/?probe=c913cb5a4a) | Apr 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [ff93a4d2f5](https://linux-hardware.org/?probe=ff93a4d2f5) | Apr 08, 2022 |
| Lenovo        | ThinkPad T495 20NJ000XIX    | [f00fb05977](https://linux-hardware.org/?probe=f00fb05977) | Apr 07, 2022 |
| MSI           | GS66 Stealth 10UH           | [bd6f031bc8](https://linux-hardware.org/?probe=bd6f031bc8) | Apr 06, 2022 |
| Acer          | Swift SF114-32              | [3947799e36](https://linux-hardware.org/?probe=3947799e36) | Apr 05, 2022 |
| MSI           | Prestige 14Evo A11M         | [29b43c3e27](https://linux-hardware.org/?probe=29b43c3e27) | Apr 05, 2022 |
| Acer          | Swift SF314-41              | [564cfd1f31](https://linux-hardware.org/?probe=564cfd1f31) | Apr 04, 2022 |
| Acer          | Aspire A515-45              | [eb69a7978b](https://linux-hardware.org/?probe=eb69a7978b) | Apr 04, 2022 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | [8444b44333](https://linux-hardware.org/?probe=8444b44333) | Apr 04, 2022 |
| Chuwi         | Hi10 Go                     | [cfa6610288](https://linux-hardware.org/?probe=cfa6610288) | Apr 04, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [8c1841d2d0](https://linux-hardware.org/?probe=8c1841d2d0) | Apr 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [5eef69398a](https://linux-hardware.org/?probe=5eef69398a) | Apr 03, 2022 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [ba4863a7bb](https://linux-hardware.org/?probe=ba4863a7bb) | Apr 02, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | [cd942b0305](https://linux-hardware.org/?probe=cd942b0305) | Apr 02, 2022 |
| Dell          | Inspiron 5548               | [9e35cab29a](https://linux-hardware.org/?probe=9e35cab29a) | Apr 02, 2022 |
| Dell          | XPS 13 9333                 | [f4fb42182f](https://linux-hardware.org/?probe=f4fb42182f) | Apr 01, 2022 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [4c0c1422e7](https://linux-hardware.org/?probe=4c0c1422e7) | Mar 31, 2022 |
| Lenovo        | ThinkPad X260 20F5S0HK1J    | [a83d3cbe5f](https://linux-hardware.org/?probe=a83d3cbe5f) | Mar 31, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [cc95f0e3ab](https://linux-hardware.org/?probe=cc95f0e3ab) | Mar 31, 2022 |
| VALE          | Notebook Slim S132          | [138a4f1d68](https://linux-hardware.org/?probe=138a4f1d68) | Mar 31, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | [05c02cbe41](https://linux-hardware.org/?probe=05c02cbe41) | Mar 31, 2022 |
| Avell High... | B.ON                        | [697fc1d4ec](https://linux-hardware.org/?probe=697fc1d4ec) | Mar 29, 2022 |
| Framework     | Laptop                      | [a22656afee](https://linux-hardware.org/?probe=a22656afee) | Mar 28, 2022 |
| Dell          | XPS 17 9710                 | [461d175c44](https://linux-hardware.org/?probe=461d175c44) | Mar 28, 2022 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | [16ac712c84](https://linux-hardware.org/?probe=16ac712c84) | Mar 24, 2022 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [1b57f1f410](https://linux-hardware.org/?probe=1b57f1f410) | Mar 13, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [917a6b65a8](https://linux-hardware.org/?probe=917a6b65a8) | Mar 10, 2022 |
| Sony          | VGN-FW21E                   | [930ce5581f](https://linux-hardware.org/?probe=930ce5581f) | Feb 25, 2022 |
| Unknown       | Unknown                     | [033354ee53](https://linux-hardware.org/?probe=033354ee53) | Jan 02, 2022 |
| Unknown       | Unknown                     | [809200ad60](https://linux-hardware.org/?probe=809200ad60) | Jan 02, 2022 |
| Unknown       | Unknown                     | [ea795a97e1](https://linux-hardware.org/?probe=ea795a97e1) | Dec 26, 2021 |
| Unknown       | Unknown                     | [2b26e185d0](https://linux-hardware.org/?probe=2b26e185d0) | Dec 06, 2021 |
| Unknown       | Unknown                     | [f09a7c7125](https://linux-hardware.org/?probe=f09a7c7125) | Dec 06, 2021 |
| Positivo      | CHT12CP                     | [53054c8f7a](https://linux-hardware.org/?probe=53054c8f7a) | Nov 20, 2021 |
| Lenovo        | IdeaPadFlex 14 20308        | [1734da4566](https://linux-hardware.org/?probe=1734da4566) | Nov 13, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [2da0673527](https://linux-hardware.org/?probe=2da0673527) | Nov 01, 2021 |
| Notebook      | PCx0Dx                      | [b1a527acdc](https://linux-hardware.org/?probe=b1a527acdc) | Oct 11, 2021 |
| Notebook      | PCx0Dx                      | [90d4556fdf](https://linux-hardware.org/?probe=90d4556fdf) | Oct 11, 2021 |
| Unknown       | Unknown                     | [af4bbffabf](https://linux-hardware.org/?probe=af4bbffabf) | Sep 27, 2021 |
| Unknown       | Unknown                     | [81fd834473](https://linux-hardware.org/?probe=81fd834473) | Sep 26, 2021 |
| HP            | ProBook 4740s               | [77b2eed991](https://linux-hardware.org/?probe=77b2eed991) | Sep 22, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                                       | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| 5.17.1-300.fc36.x86_64                                        | 16        | 31.37%  |
| 5.17.2-300.fc36.x86_64                                        | 11        | 21.57%  |
| 5.17.0-0.rc7.116.fc36.x86_64                                  | 10        | 19.61%  |
| 5.17.0-300.fc36.x86_64                                        | 3         | 5.88%   |
| 5.17.0-0.rc5.102.fc36.x86_64                                  | 2         | 3.92%   |
| 5.16.9-200.fc35.x86_64                                        | 1         | 1.96%   |
| 5.16.16-200.fc35.x86_64                                       | 1         | 1.96%   |
| 5.16.0-0.rc7.20211231git4f3d93c6eaff.52.vanilla.1.fc36.x86_64 | 1         | 1.96%   |
| 5.15.0-0.rc7.20211028git1fc596a56b33.56.fc36.x86_64           | 1         | 1.96%   |
| 5.15.0-0.rc4.20211008git1da38549dd64.36.fc36.x86_64           | 1         | 1.96%   |
| 5.15.0-0.rc2.20210923git58e2cf5d7946.21.vanilla.1.fc36.x86_64 | 1         | 1.96%   |
| 5.15.0-0.rc2.18.fc36.x86_64                                   | 1         | 1.96%   |
| 5.14.14-300.fc35.x86_64                                       | 1         | 1.96%   |
| 5.14.10-300.fc35.x86_64                                       | 1         | 1.96%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.17.1  | 16        | 31.37%  |
| 5.17.0  | 15        | 29.41%  |
| 5.17.2  | 11        | 21.57%  |
| 5.15.0  | 4         | 7.84%   |
| 5.16.9  | 1         | 1.96%   |
| 5.16.16 | 1         | 1.96%   |
| 5.16.0  | 1         | 1.96%   |
| 5.14.14 | 1         | 1.96%   |
| 5.14.10 | 1         | 1.96%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.17    | 41        | 82%     |
| 5.15    | 4         | 8%      |
| 5.16    | 3         | 6%      |
| 5.14    | 2         | 4%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 49        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GNOME   | 42        | 84%     |
| KDE5    | 4         | 8%      |
| Unknown | 3         | 6%      |
| i3      | 1         | 2%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 41        | 83.67%  |
| X11     | 6         | 12.24%  |
| Unknown | 2         | 4.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM     | 29        | 59.18%  |
| Unknown | 14        | 28.57%  |
| SDDM    | 4         | 8.16%   |
| LightDM | 2         | 4.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 30        | 61.22%  |
| en_GB | 4         | 8.16%   |
| pl_PL | 3         | 6.12%   |
| pt_BR | 2         | 4.08%   |
| es_ES | 2         | 4.08%   |
| de_DE | 2         | 4.08%   |
| pt_PT | 1         | 2.04%   |
| hu_HU | 1         | 2.04%   |
| hr_HR | 1         | 2.04%   |
| fr_FR | 1         | 2.04%   |
| es_UY | 1         | 2.04%   |
| cs_CZ | 1         | 2.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 44        | 89.8%   |
| BIOS | 5         | 10.2%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 35        | 71.43%  |
| Ext4  | 12        | 24.49%  |
| Xfs   | 2         | 4.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 33        | 66%     |
| Unknown | 15        | 30%     |
| MBR     | 2         | 4%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 36        | 73.47%  |
| Yes       | 13        | 26.53%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 33        | 67.35%  |
| Yes       | 16        | 32.65%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 18        | 36.73%  |
| Dell                   | 8         | 16.33%  |
| Hewlett-Packard        | 5         | 10.2%   |
| MSI                    | 3         | 6.12%   |
| ASUSTek Computer       | 3         | 6.12%   |
| Acer                   | 3         | 6.12%   |
| VALE                   | 1         | 2.04%   |
| Toshiba                | 1         | 2.04%   |
| Sony                   | 1         | 2.04%   |
| Positivo               | 1         | 2.04%   |
| Notebook               | 1         | 2.04%   |
| Framework              | 1         | 2.04%   |
| Chuwi                  | 1         | 2.04%   |
| Avell High Performance | 1         | 2.04%   |
| Unknown                | 1         | 2.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| VALE Notebook Slim S132                     | 1         | 2.04%   |
| Toshiba Satellite U840                      | 1         | 2.04%   |
| Sony VGN-FW21E                              | 1         | 2.04%   |
| Positivo CHT12CP                            | 1         | 2.04%   |
| Notebook PCx0Dx                             | 1         | 2.04%   |
| MSI Prestige 14Evo A11M                     | 1         | 2.04%   |
| MSI Modern 14 B4MW                          | 1         | 2.04%   |
| MSI GS66 Stealth 10UH                       | 1         | 2.04%   |
| Lenovo ThinkPad X260 20F5S0HK1J             | 1         | 2.04%   |
| Lenovo ThinkPad X1 Carbon 7th 20R1S05B00    | 1         | 2.04%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS23S0P    | 1         | 2.04%   |
| Lenovo ThinkPad T495 20NJ000XIX             | 1         | 2.04%   |
| Lenovo ThinkPad P15 Gen 1 20STS0J500        | 1         | 2.04%   |
| Lenovo ThinkPad P14s Gen 1 20Y1000SUK       | 1         | 2.04%   |
| Lenovo ThinkPad L14 Gen 2 20X10044EQ        | 1         | 2.04%   |
| Lenovo ThinkPad L13 Gen 2 20VJS0HB00        | 1         | 2.04%   |
| Lenovo ThinkBook 15 G2 ITL 20VE             | 1         | 2.04%   |
| Lenovo ThinkBook 14 G3 ACL 21A2             | 1         | 2.04%   |
| Lenovo ThinkBook 13s G3 ACN 20YA            | 1         | 2.04%   |
| Lenovo Legion Y540-15IRH 81SX               | 1         | 2.04%   |
| Lenovo IdeaPadFlex 14 20308                 | 1         | 2.04%   |
| Lenovo IdeaPad Yoga 13 20175                | 1         | 2.04%   |
| Lenovo IdeaPad L340-15IRH Gaming 81TR       | 1         | 2.04%   |
| Lenovo IdeaPad 530S-14IKB 81EU              | 1         | 2.04%   |
| Lenovo IdeaPad 530S-14ARR 81H1              | 1         | 2.04%   |
| Lenovo IdeaPad 320S-13IKB 81AK              | 1         | 2.04%   |
| HP ZBook Fury 15 G7 Mobile Workstation      | 1         | 2.04%   |
| HP ProBook 4740s                            | 1         | 2.04%   |
| HP ProBook 455 G8 Notebook PC               | 1         | 2.04%   |
| HP Pavilion 15                              | 1         | 2.04%   |
| HP Laptop 15-dw3xxx                         | 1         | 2.04%   |
| Framework Laptop                            | 1         | 2.04%   |
| Dell XPS 17 9710                            | 1         | 2.04%   |
| Dell XPS 13 9370                            | 1         | 2.04%   |
| Dell XPS 13 9333                            | 1         | 2.04%   |
| Dell XPS 13 9305                            | 1         | 2.04%   |
| Dell Studio 1537                            | 1         | 2.04%   |
| Dell Precision 7540                         | 1         | 2.04%   |
| Dell Inspiron 5548                          | 1         | 2.04%   |
| Dell Inspiron 3505                          | 1         | 2.04%   |
| Chuwi Hi10 Go                               | 1         | 2.04%   |
| Avell High Performance B.ON                 | 1         | 2.04%   |
| ASUS VivoBook_ASUSLaptop X512DA_F512DA      | 1         | 2.04%   |
| ASUS VivoBook_ASUSLaptop X421FAY_K413FA     | 1         | 2.04%   |
| ASUS ROG Zephyrus Duo 15 SE GX551QS_GX551QS | 1         | 2.04%   |
| Acer Swift SF314-41                         | 1         | 2.04%   |
| Acer Swift SF114-32                         | 1         | 2.04%   |
| Acer Aspire A515-45                         | 1         | 2.04%   |
| Unknown                                     | 1         | 2.04%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Lenovo ThinkPad             | 8         | 16.33%  |
| Lenovo IdeaPad              | 5         | 10.2%   |
| Dell XPS                    | 4         | 8.16%   |
| Lenovo ThinkBook            | 3         | 6.12%   |
| HP ProBook                  | 2         | 4.08%   |
| Dell Inspiron               | 2         | 4.08%   |
| ASUS VivoBook               | 2         | 4.08%   |
| Acer Swift                  | 2         | 4.08%   |
| VALE Notebook               | 1         | 2.04%   |
| Toshiba Satellite           | 1         | 2.04%   |
| Sony VGN-FW21E              | 1         | 2.04%   |
| Positivo CHT12CP            | 1         | 2.04%   |
| Notebook PCx0Dx             | 1         | 2.04%   |
| MSI Prestige                | 1         | 2.04%   |
| MSI Modern                  | 1         | 2.04%   |
| MSI GS66                    | 1         | 2.04%   |
| Lenovo Legion               | 1         | 2.04%   |
| Lenovo IdeaPadFlex          | 1         | 2.04%   |
| HP ZBook                    | 1         | 2.04%   |
| HP Pavilion                 | 1         | 2.04%   |
| HP Laptop                   | 1         | 2.04%   |
| Framework Laptop            | 1         | 2.04%   |
| Dell Studio                 | 1         | 2.04%   |
| Dell Precision              | 1         | 2.04%   |
| Chuwi Hi10                  | 1         | 2.04%   |
| Avell High Performance B.ON | 1         | 2.04%   |
| ASUS ROG                    | 1         | 2.04%   |
| Acer Aspire                 | 1         | 2.04%   |
| Unknown                     | 1         | 2.04%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 14        | 28.57%  |
| 2020 | 10        | 20.41%  |
| 2019 | 7         | 14.29%  |
| 2018 | 6         | 12.24%  |
| 2013 | 3         | 6.12%   |
| 2012 | 3         | 6.12%   |
| 2017 | 2         | 4.08%   |
| 2008 | 2         | 4.08%   |
| 2016 | 1         | 2.04%   |
| 2015 | 1         | 2.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 49        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 35        | 71.43%  |
| Enabled  | 14        | 28.57%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 49        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 13        | 26.53%  |
| 16.01-24.0  | 12        | 24.49%  |
| 8.01-16.0   | 9         | 18.37%  |
| 32.01-64.0  | 8         | 16.33%  |
| 3.01-4.0    | 5         | 10.2%   |
| 24.01-32.0  | 1         | 2.04%   |
| 64.01-256.0 | 1         | 2.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 4.01-8.0 | 17        | 33.33%  |
| 3.01-4.0 | 17        | 33.33%  |
| 2.01-3.0 | 12        | 23.53%  |
| 1.01-2.0 | 5         | 9.8%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 34        | 68%     |
| 2      | 13        | 26%     |
| 3      | 3         | 6%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 45        | 91.84%  |
| Yes       | 4         | 8.16%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 59.18%  |
| No        | 20        | 40.82%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 48        | 97.96%  |
| No        | 1         | 2.04%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 87.76%  |
| No        | 6         | 12.24%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 7         | 14.29%  |
| UK           | 5         | 10.2%   |
| Brazil       | 4         | 8.16%   |
| Poland       | 3         | 6.12%   |
| Italy        | 3         | 6.12%   |
| Germany      | 3         | 6.12%   |
| Russia       | 2         | 4.08%   |
| Romania      | 2         | 4.08%   |
| Norway       | 2         | 4.08%   |
| France       | 2         | 4.08%   |
| Uzbekistan   | 1         | 2.04%   |
| Turkey       | 1         | 2.04%   |
| Sweden       | 1         | 2.04%   |
| Spain        | 1         | 2.04%   |
| Slovakia     | 1         | 2.04%   |
| Saudi Arabia | 1         | 2.04%   |
| Portugal     | 1         | 2.04%   |
| Netherlands  | 1         | 2.04%   |
| Nepal        | 1         | 2.04%   |
| Latvia       | 1         | 2.04%   |
| Iceland      | 1         | 2.04%   |
| Hungary      | 1         | 2.04%   |
| Estonia      | 1         | 2.04%   |
| Czechia      | 1         | 2.04%   |
| Croatia      | 1         | 2.04%   |
| Austria      | 1         | 2.04%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Warsaw                        | 2         | 4.08%   |
| Sao Paulo                     | 2         | 4.08%   |
| Moscow                        | 2         | 4.08%   |
| Zagreb                        | 1         | 2.04%   |
| Warrington                    | 1         | 2.04%   |
| Vegarshei                     | 1         | 2.04%   |
| Trzciel                       | 1         | 2.04%   |
| Trier                         | 1         | 2.04%   |
| Tashkent                      | 1         | 2.04%   |
| Tallinn                       | 1         | 2.04%   |
| Solihull                      | 1         | 2.04%   |
| Scorrano                      | 1         | 2.04%   |
| Rozmital pod Tremsinem        | 1         | 2.04%   |
| Riga                          | 1         | 2.04%   |
| Reykjavik                     | 1         | 2.04%   |
| Princeton                     | 1         | 2.04%   |
| Porto                         | 1         | 2.04%   |
| Oslo                          | 1         | 2.04%   |
| Newport                       | 1         | 2.04%   |
| Mölten                       | 1         | 2.04%   |
| Meitingen                     | 1         | 2.04%   |
| Marseille                     | 1         | 2.04%   |
| Macaiba                       | 1         | 2.04%   |
| Lyme                          | 1         | 2.04%   |
| Leiderdorp                    | 1         | 2.04%   |
| Las Vegas                     | 1         | 2.04%   |
| Kathmandu                     | 1         | 2.04%   |
| Kasten bei Boeheimkirchen     | 1         | 2.04%   |
| Joinville                     | 1         | 2.04%   |
| Istanbul                      | 1         | 2.04%   |
| Iasi                          | 1         | 2.04%   |
| Holmes Chapel                 | 1         | 2.04%   |
| Halstead                      | 1         | 2.04%   |
| Gyomro                        | 1         | 2.04%   |
| Fort Collins                  | 1         | 2.04%   |
| Folsom                        | 1         | 2.04%   |
| Enebyberg                     | 1         | 2.04%   |
| El Segundo                    | 1         | 2.04%   |
| Córdoba                      | 1         | 2.04%   |
| Châteauneuf-du-Pape          | 1         | 2.04%   |
| Caldaro sulla Strada del Vino | 1         | 2.04%   |
| Bucharest                     | 1         | 2.04%   |
| Bratislava                    | 1         | 2.04%   |
| Berlin                        | 1         | 2.04%   |
| Beaverton                     | 1         | 2.04%   |
| Al Qatif                      | 1         | 2.04%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 18     | 24.62%  |
| WDC                 | 6         | 6      | 9.23%   |
| Unknown             | 6         | 8      | 9.23%   |
| SK Hynix            | 4         | 4      | 6.15%   |
| Kingston            | 4         | 7      | 6.15%   |
| A-DATA Technology   | 4         | 4      | 6.15%   |
| Sandisk             | 3         | 3      | 4.62%   |
| Toshiba             | 2         | 2      | 3.08%   |
| PNY                 | 2         | 3      | 3.08%   |
| Phison              | 2         | 2      | 3.08%   |
| Unknown             | 2         | 2      | 3.08%   |
| XPG                 | 1         | 1      | 1.54%   |
| WDC WDS2            | 1         | 1      | 1.54%   |
| Transcend           | 1         | 1      | 1.54%   |
| Silicon Motion      | 1         | 1      | 1.54%   |
| Seagate             | 1         | 1      | 1.54%   |
| Micron Technology   | 1         | 1      | 1.54%   |
| Mass                | 1         | 1      | 1.54%   |
| Leven               | 1         | 1      | 1.54%   |
| KIOXIA              | 1         | 2      | 1.54%   |
| KingDian            | 1         | 1      | 1.54%   |
| Hitachi             | 1         | 1      | 1.54%   |
| Fujitsu             | 1         | 1      | 1.54%   |
| EAGET               | 1         | 1      | 1.54%   |
| Crucial             | 1         | 1      | 1.54%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Sandisk NVMe SSD Drive 512GB         | 2         | 2.99%   |
| Samsung SSD 980 1TB                  | 2         | 2.99%   |
| Samsung SSD 860 EVO 250GB            | 2         | 2.99%   |
| Samsung NVMe SSD Drive 1TB           | 2         | 2.99%   |
| Phison Sabrent 1TB                   | 2         | 2.99%   |
| Unknown                              | 2         | 2.99%   |
| XPG NVMe SSD Drive 1024GB            | 1         | 1.49%   |
| WDC WDS500G1X0E-00AFY0 500GB         | 1         | 1.49%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 1.49%   |
| WDC WDS2 40G2G0B-00EP 240GB SSD      | 1         | 1.49%   |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 1         | 1.49%   |
| WDC WD10SPZX-24Z10 1TB               | 1         | 1.49%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB | 1         | 1.49%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB | 1         | 1.49%   |
| Unknown SU32G  32GB                  | 1         | 1.49%   |
| Unknown SM32G  32GB                  | 1         | 1.49%   |
| Unknown MMC64G  64GB                 | 1         | 1.49%   |
| Unknown MMC Card  64GB               | 1         | 1.49%   |
| Unknown MMC Card  32GB               | 1         | 1.49%   |
| Unknown ED2S5  128GB                 | 1         | 1.49%   |
| Transcend TS240GMTS420S 240GB SSD    | 1         | 1.49%   |
| Toshiba NVMe SSD Drive 512GB         | 1         | 1.49%   |
| Toshiba KXG6AZNV512G 512GB           | 1         | 1.49%   |
| SK Hynix PC401 NVMe 256GB            | 1         | 1.49%   |
| SK Hynix NVMe SSD Drive 512GB        | 1         | 1.49%   |
| SK Hynix NVMe SSD Drive 256GB        | 1         | 1.49%   |
| SK Hynix HFM256GDHTNG-8310A 256GB    | 1         | 1.49%   |
| Silicon Motion NE-128 128GB          | 1         | 1.49%   |
| Seagate Expansion 1TB                | 1         | 1.49%   |
| SanDisk DF4032  32GB                 | 1         | 1.49%   |
| Samsung SSD 970 EVO Plus 500GB       | 1         | 1.49%   |
| Samsung SSD 970 EVO 500GB            | 1         | 1.49%   |
| Samsung SSD 860 EVO mSATA 500GB      | 1         | 1.49%   |
| Samsung PM9A1 NVMe 512GB             | 1         | 1.49%   |
| Samsung NVMe SSD Drive 500GB         | 1         | 1.49%   |
| Samsung NVMe SSD Drive 1024GB        | 1         | 1.49%   |
| Samsung MZVLQ512HALU-000H1 512GB     | 1         | 1.49%   |
| Samsung MZVLQ512HALU-00000 512GB     | 1         | 1.49%   |
| Samsung MZVLQ256HAJD-00000 256GB     | 1         | 1.49%   |
| Samsung MZMPC128HBFU-000L1 128GB SSD | 1         | 1.49%   |
| Samsung MZALQ512HBLU-00BL2 512GB     | 1         | 1.49%   |
| PNY CS3040 4TB SSD                   | 1         | 1.49%   |
| PNY CS1311 240GB SSD                 | 1         | 1.49%   |
| Micron 2200S NVMe 256GB              | 1         | 1.49%   |
| Mass Mass Storage 8MB                | 1         | 1.49%   |
| Leven JAJS600M256C 256GB             | 1         | 1.49%   |
| KIOXIA KXG60ZNV1T02 1TB              | 1         | 1.49%   |
| Kingston SUV500MS240G 240GB SSD      | 1         | 1.49%   |
| Kingston SNVS1000G 1TB               | 1         | 1.49%   |
| Kingston SA400S37960G 960GB SSD      | 1         | 1.49%   |
| Kingston OM8PCP31024F-AI1 1TB        | 1         | 1.49%   |
| Kingston NVMe SSD Drive 1TB          | 1         | 1.49%   |
| KingDian M280 240GB                  | 1         | 1.49%   |
| Hitachi HTS543232A7A384 320GB        | 1         | 1.49%   |
| Fujitsu MJA2500BH G1 500GB           | 1         | 1.49%   |
| EAGET S606 SSD 120GB                 | 1         | 1.49%   |
| Crucial CT1000P2SSD8 1TB             | 1         | 1.49%   |
| A-DATA SX8200PNP 512GB               | 1         | 1.49%   |
| A-DATA SU800 1024GB SSD              | 1         | 1.49%   |
| A-DATA IM2P33F8ABR2-256GB            | 1         | 1.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 25%     |
| Seagate | 1         | 1      | 25%     |
| Hitachi | 1         | 1      | 25%     |
| Fujitsu | 1         | 1      | 25%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 28.57%  |
| WDC                 | 2         | 2      | 14.29%  |
| Kingston            | 2         | 4      | 14.29%  |
| WDC WDS2            | 1         | 1      | 7.14%   |
| Transcend           | 1         | 1      | 7.14%   |
| PNY                 | 1         | 1      | 7.14%   |
| Leven               | 1         | 1      | 7.14%   |
| EAGET               | 1         | 1      | 7.14%   |
| A-DATA Technology   | 1         | 1      | 7.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 35        | 41     | 57.38%  |
| SSD     | 12        | 16     | 19.67%  |
| MMC     | 8         | 11     | 13.11%  |
| HDD     | 4         | 4      | 6.56%   |
| Unknown | 2         | 2      | 3.28%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 35        | 41     | 57.38%  |
| SATA | 15        | 19     | 24.59%  |
| MMC  | 8         | 11     | 13.11%  |
| SAS  | 3         | 3      | 4.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 12        | 15     | 70.59%  |
| 0.51-1.0   | 4         | 4      | 23.53%  |
| 1.01-2.0   | 1         | 1      | 5.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 15        | 30.61%  |
| 251-500    | 12        | 24.49%  |
| 501-1000   | 7         | 14.29%  |
| 1001-2000  | 6         | 12.24%  |
| 101-250    | 5         | 10.2%   |
| 51-100     | 3         | 6.12%   |
| 21-50      | 1         | 2.04%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 29        | 59.18%  |
| 21-50    | 6         | 12.24%  |
| 51-100   | 5         | 10.2%   |
| 251-500  | 4         | 8.16%   |
| 101-250  | 3         | 6.12%   |
| 501-1000 | 2         | 4.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                      | Notebooks | Drives | Percent |
|----------------------------|-----------|--------|---------|
| Fujitsu MJA2500BH G1 500GB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Fujitsu | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Fujitsu | 1         | 1      | 100%    |

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
| Works    | 33        | 38     | 58.93%  |
| Detected | 22        | 35     | 39.29%  |
| Malfunc  | 1         | 1      | 1.79%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 22        | 35.48%  |
| Samsung Electronics          | 12        | 19.35%  |
| Sandisk                      | 5         | 8.06%   |
| SK Hynix                     | 4         | 6.45%   |
| AMD                          | 4         | 6.45%   |
| ADATA Technology             | 4         | 6.45%   |
| Toshiba America Info Systems | 3         | 4.84%   |
| Phison Electronics           | 3         | 4.84%   |
| Kingston Technology Company  | 2         | 3.23%   |
| Silicon Motion               | 1         | 1.61%   |
| Micron/Crucial Technology    | 1         | 1.61%   |
| Micron Technology            | 1         | 1.61%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller 980                                          | 7         | 10.77%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                            | 4         | 6.15%   |
| AMD FCH SATA Controller [AHCI mode]                                      | 4         | 6.15%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                     | 3         | 4.62%   |
| Intel Volume Management Device NVMe RAID Controller                      | 3         | 4.62%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                        | 3         | 4.62%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                             | 3         | 4.62%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                              | 2         | 3.08%   |
| SK Hynix BC501 NVMe Solid State Drive                                    | 2         | 3.08%   |
| Sandisk Non-Volatile memory controller                                   | 2         | 3.08%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                           | 2         | 3.08%   |
| Phison E12 NVMe Controller                                               | 2         | 3.08%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                          | 2         | 3.08%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                       | 2         | 3.08%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                   | 2         | 3.08%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]    | 2         | 3.08%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]         | 2         | 3.08%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive              | 2         | 3.08%   |
| ADATA Non-Volatile memory controller                                     | 2         | 3.08%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                          | 1         | 1.54%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                               | 1         | 1.54%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                | 1         | 1.54%   |
| Sandisk PC SN520 NVMe SSD                                                | 1         | 1.54%   |
| Phison E16 PCIe4 NVMe Controller                                         | 1         | 1.54%   |
| Micron/Crucial P2 NVMe PCIe SSD                                          | 1         | 1.54%   |
| Micron Non-Volatile memory controller                                    | 1         | 1.54%   |
| Kingston Company Company Non-Volatile memory controller                  | 1         | 1.54%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                       | 1         | 1.54%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                       | 1         | 1.54%   |
| Intel Jasper Lake SATA AHCI Controller                                   | 1         | 1.54%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller | 1         | 1.54%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                           | 1         | 1.54%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                     | 1         | 1.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 35        | 55.56%  |
| SATA | 24        | 38.1%   |
| RAID | 4         | 6.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 37        | 75.51%  |
| AMD    | 12        | 24.49%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 4         | 8.16%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 3         | 6.12%   |
| Intel Core i7-10870H CPU @ 2.20GHz              | 2         | 4.08%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 2         | 4.08%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 2         | 4.08%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz        | 1         | 2.04%   |
| Intel Pentium 3556U @ 1.70GHz                   | 1         | 2.04%   |
| Intel Core i7-9850H CPU @ 2.60GHz               | 1         | 2.04%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 1         | 2.04%   |
| Intel Core i7-8650U CPU @ 1.90GHz               | 1         | 2.04%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 1         | 2.04%   |
| Intel Core i7-4510U CPU @ 2.00GHz               | 1         | 2.04%   |
| Intel Core i7-3632QM CPU @ 2.20GHz              | 1         | 2.04%   |
| Intel Core i7-10875H CPU @ 2.30GHz              | 1         | 2.04%   |
| Intel Core i7-10850H CPU @ 2.70GHz              | 1         | 2.04%   |
| Intel Core i7-10710U CPU @ 1.10GHz              | 1         | 2.04%   |
| Intel Core i5-9300H CPU @ 2.40GHz               | 1         | 2.04%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 1         | 2.04%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 1         | 2.04%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 1         | 2.04%   |
| Intel Core i5-3337U CPU @ 1.80GHz               | 1         | 2.04%   |
| Intel Core i5-3317U CPU @ 1.70GHz               | 1         | 2.04%   |
| Intel Core i3-10110U CPU @ 2.10GHz              | 1         | 2.04%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz            | 1         | 2.04%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz            | 1         | 2.04%   |
| Intel Celeron N5100 @ 1.10GHz                   | 1         | 2.04%   |
| Intel Celeron N4020 CPU @ 1.10GHz               | 1         | 2.04%   |
| Intel Celeron CPU J3455 @ 1.50GHz               | 1         | 2.04%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz               | 1         | 2.04%   |
| Intel 11th Gen Core i9-11900H @ 2.50GHz         | 1         | 2.04%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz         | 1         | 2.04%   |
| AMD Ryzen 9 5900HX with Radeon Graphics         | 1         | 2.04%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics      | 1         | 2.04%   |
| AMD Ryzen 7 5800U with Radeon Graphics          | 1         | 2.04%   |
| AMD Ryzen 7 5700U with Radeon Graphics          | 1         | 2.04%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 1         | 2.04%   |
| AMD Ryzen 5 PRO 3500U w/ Radeon Vega Mobile Gfx | 1         | 2.04%   |
| AMD Ryzen 5 5600U with Radeon Graphics          | 1         | 2.04%   |
| AMD Ryzen 5 3450U with Radeon Vega Mobile Gfx   | 1         | 2.04%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx   | 1         | 2.04%   |
| AMD Ryzen 3 5300U with Radeon Graphics          | 1         | 2.04%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i7        | 11        | 22.45%  |
| Other                | 9         | 18.37%  |
| Intel Core i5        | 8         | 16.33%  |
| AMD Ryzen 5          | 5         | 10.2%   |
| Intel Celeron        | 3         | 6.12%   |
| AMD Ryzen 7          | 3         | 6.12%   |
| Intel Core 2 Duo     | 2         | 4.08%   |
| Intel Pentium Silver | 1         | 2.04%   |
| Intel Pentium        | 1         | 2.04%   |
| Intel Core i3        | 1         | 2.04%   |
| Intel Atom           | 1         | 2.04%   |
| AMD Ryzen 9          | 1         | 2.04%   |
| AMD Ryzen 7 PRO      | 1         | 2.04%   |
| AMD Ryzen 5 PRO      | 1         | 2.04%   |
| AMD Ryzen 3          | 1         | 2.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 24        | 48.98%  |
| 2      | 11        | 22.45%  |
| 8      | 9         | 18.37%  |
| 6      | 5         | 10.2%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 49        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 39        | 79.59%  |
| 1      | 10        | 20.41%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 49        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806c1    | 7         | 14.29%  |
| 0xa0652    | 4         | 8.16%   |
| 0x806ea    | 4         | 8.16%   |
| 0x40651    | 3         | 6.12%   |
| 0x306a9    | 3         | 6.12%   |
| 0x0a50000c | 3         | 6.12%   |
| 0x08108109 | 3         | 6.12%   |
| 0x906ea    | 2         | 4.08%   |
| 0x706a8    | 2         | 4.08%   |
| 0x10676    | 2         | 4.08%   |
| 0xa0660    | 1         | 2.04%   |
| 0x906ed    | 1         | 2.04%   |
| 0x906c0    | 1         | 2.04%   |
| 0x806ec    | 1         | 2.04%   |
| 0x806d1    | 1         | 2.04%   |
| 0x506c9    | 1         | 2.04%   |
| 0x406e3    | 1         | 2.04%   |
| 0x406c4    | 1         | 2.04%   |
| 0x306d4    | 1         | 2.04%   |
| 0x08608103 | 1         | 2.04%   |
| 0x08608102 | 1         | 2.04%   |
| 0x08600106 | 1         | 2.04%   |
| 0x08600104 | 1         | 2.04%   |
| 0x08108102 | 1         | 2.04%   |
| 0x0810100b | 1         | 2.04%   |
| Unknown    | 1         | 2.04%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| TigerLake     | 8         | 16.33%  |
| KabyLake      | 8         | 16.33%  |
| CometLake     | 5         | 10.2%   |
| Zen+          | 4         | 8.16%   |
| Zen 3         | 3         | 6.12%   |
| IvyBridge     | 3         | 6.12%   |
| Haswell       | 3         | 6.12%   |
| Zen 2         | 2         | 4.08%   |
| Penryn        | 2         | 4.08%   |
| Goldmont plus | 2         | 4.08%   |
| Unknown       | 2         | 4.08%   |
| Zen           | 1         | 2.04%   |
| Tremont       | 1         | 2.04%   |
| Skylake       | 1         | 2.04%   |
| Silvermont    | 1         | 2.04%   |
| Icelake       | 1         | 2.04%   |
| Goldmont      | 1         | 2.04%   |
| Broadwell     | 1         | 2.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 35        | 57.38%  |
| AMD    | 15        | 24.59%  |
| Nvidia | 11        | 18.03%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 8         | 13.11%  |
| Intel UHD Graphics 620                                                                   | 4         | 6.56%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 6.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 6.56%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 4.92%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 4.92%   |
| AMD Cezanne                                                                              | 3         | 4.92%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 2         | 3.28%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 3.28%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 2         | 3.28%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 3.28%   |
| AMD Renoir                                                                               | 2         | 3.28%   |
| AMD Lucienne                                                                             | 2         | 3.28%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 1.64%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 1.64%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 1.64%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 1.64%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 1.64%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 1.64%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 1.64%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.64%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 1.64%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.64%   |
| Intel HD Graphics 500                                                                    | 1         | 1.64%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 1.64%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.64%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.64%   |
| Intel Comet Lake UHD Graphics                                                            | 1         | 1.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.64%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 1         | 1.64%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 1         | 1.64%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 1.64%   |
| AMD Lexa XT [Radeon PRO WX 3200]                                                         | 1         | 1.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 24        | 48.98%  |
| 1 x AMD        | 12        | 24.49%  |
| Intel + Nvidia | 9         | 18.37%  |
| Intel + AMD    | 2         | 4.08%   |
| 1 x Nvidia     | 1         | 2.04%   |
| AMD + Nvidia   | 1         | 2.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 47        | 94%     |
| Proprietary | 2         | 4%      |
| Unknown     | 1         | 2%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 27        | 55.1%   |
| 1.01-2.0   | 10        | 20.41%  |
| 0.01-0.5   | 7         | 14.29%  |
| 3.01-4.0   | 3         | 6.12%   |
| 5.01-6.0   | 1         | 2.04%   |
| 2.01-3.0   | 1         | 2.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 13        | 23.21%  |
| BOE                  | 9         | 16.07%  |
| LG Display           | 8         | 14.29%  |
| Chimei Innolux       | 7         | 12.5%   |
| Sharp                | 3         | 5.36%   |
| Samsung Electronics  | 3         | 5.36%   |
| InfoVision           | 3         | 5.36%   |
| Ancor Communications | 2         | 3.57%   |
| Vizio                | 1         | 1.79%   |
| Philips              | 1         | 1.79%   |
| PANDA                | 1         | 1.79%   |
| Lenovo               | 1         | 1.79%   |
| Insignia             | 1         | 1.79%   |
| Hewlett-Packard      | 1         | 1.79%   |
| Dell                 | 1         | 1.79%   |
| Aosiman              | 1         | 1.79%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch         | 2         | 3.45%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 2         | 3.45%   |
| Vizio M260VA VIZ0067 1360x768 575x323mm 26.0-inch                    | 1         | 1.72%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch              | 1         | 1.72%   |
| Sharp LQ156M1JW23 SHP1514 1920x1080 344x194mm 15.5-inch              | 1         | 1.72%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch              | 1         | 1.72%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch    | 1         | 1.72%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch | 1         | 1.72%   |
| Samsung Electronics LCD Monitor SEC3554 1600x900 382x215mm 17.3-inch | 1         | 1.72%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 1         | 1.72%   |
| Philips PHL BDM3470UP PHL08DA 3440x1440 800x335mm 34.1-inch          | 1         | 1.72%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch              | 1         | 1.72%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch         | 1         | 1.72%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch         | 1         | 1.72%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 1         | 1.72%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch         | 1         | 1.72%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch          | 1         | 1.72%   |
| LG Display LCD Monitor LGD0360 1600x900 294x166mm 13.3-inch          | 1         | 1.72%   |
| Lenovo M14 LEN61DD 1920x1080 309x174mm 14.0-inch                     | 1         | 1.72%   |
| Lenovo LEN T32h-20 LEN61F1 2560x1440 698x393mm 31.5-inch             | 1         | 1.72%   |
| Insignia DX-19L150A11 BBY1911 1360x768 410x230mm 18.5-inch           | 1         | 1.72%   |
| InfoVision LCD Monitor IVO854A 1920x1200 286x179mm 13.3-inch         | 1         | 1.72%   |
| InfoVision LCD Monitor IVO3D40 1920x1080 344x194mm 15.5-inch         | 1         | 1.72%   |
| InfoVision LCD Monitor IVO0536 1920x1080 294x165mm 13.3-inch         | 1         | 1.72%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 527x296mm 23.8-inch           | 1         | 1.72%   |
| Dell U2415 DELA0B8 1920x1200 518x324mm 24.1-inch                     | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN1512 1920x1080 344x193mm 15.5-inch     | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN150C 1920x1080 344x193mm 15.5-inch     | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch     | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch     | 1         | 1.72%   |
| Chimei Innolux LCD Monitor CMN1345 1920x1080 293x165mm 13.2-inch     | 1         | 1.72%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 1         | 1.72%   |
| BOE LCD Monitor BOE0922 1920x550                                     | 1         | 1.72%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                | 1         | 1.72%   |
| BOE LCD Monitor BOE08F5 1920x1080 344x194mm 15.5-inch                | 1         | 1.72%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                | 1         | 1.72%   |
| BOE LCD Monitor BOE0819 1920x1080 344x194mm 15.5-inch                | 1         | 1.72%   |
| BOE LCD Monitor BOE06FB 1920x1080 344x194mm 15.5-inch                | 1         | 1.72%   |
| BOE LCD Monitor BOE06FA 1920x1080 294x165mm 13.3-inch                | 1         | 1.72%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                | 1         | 1.72%   |
| AU Optronics LCD Monitor AUO623D 1920x1080 309x174mm 14.0-inch       | 1         | 1.72%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch       | 1         | 1.72%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch       | 1         | 1.72%   |
| AU Optronics LCD Monitor AUO502D 1920x1080 293x162mm 13.2-inch       | 1         | 1.72%   |
| AU Optronics LCD Monitor AUO4999 1920x1080 344x193mm 15.5-inch       | 1         | 1.72%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch        | 1         | 1.72%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 1         | 1.72%   |
| AU Optronics LCD Monitor AUO33ED 1920x1080 344x193mm 15.5-inch       | 1         | 1.72%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch        | 1         | 1.72%   |
| AU Optronics LCD Monitor AUO24ED 1920x1080 344x194mm 15.5-inch       | 1         | 1.72%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 1         | 1.72%   |
| AU Optronics LCD Monitor AUO11EC 1366x768 344x193mm 15.5-inch        | 1         | 1.72%   |
| AU Optronics LCD Monitor AUO103C 1366x768 309x173mm 13.9-inch        | 1         | 1.72%   |
| Aosiman ASM-156UC ASM1560 3840x2160 300x260mm 15.6-inch              | 1         | 1.72%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch     | 1         | 1.72%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch     | 1         | 1.72%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 36        | 67.92%  |
| 1366x768 (WXGA)   | 6         | 11.32%  |
| 1920x1200 (WUXGA) | 2         | 3.77%   |
| 1600x900 (HD+)    | 2         | 3.77%   |
| 3840x2400         | 1         | 1.89%   |
| 3840x2160 (4K)    | 1         | 1.89%   |
| 3440x1440         | 1         | 1.89%   |
| 2560x1440 (QHD)   | 1         | 1.89%   |
| 2256x1504         | 1         | 1.89%   |
| 1920x550          | 1         | 1.89%   |
| 1360x768          | 1         | 1.89%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 18        | 31.58%  |
| 13      | 15        | 26.32%  |
| 14      | 9         | 15.79%  |
| 24      | 4         | 7.02%   |
| 31      | 2         | 3.51%   |
| 17      | 2         | 3.51%   |
| 34      | 1         | 1.75%   |
| 27      | 1         | 1.75%   |
| 23      | 1         | 1.75%   |
| 18      | 1         | 1.75%   |
| 12      | 1         | 1.75%   |
| 11      | 1         | 1.75%   |
| Unknown | 1         | 1.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 32        | 57.14%  |
| 201-300     | 10        | 17.86%  |
| 501-600     | 6         | 10.71%  |
| 351-400     | 3         | 5.36%   |
| 601-700     | 2         | 3.57%   |
| 701-800     | 1         | 1.79%   |
| 401-500     | 1         | 1.79%   |
| Unknown     | 1         | 1.79%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 43        | 87.76%  |
| 16/10 | 3         | 6.12%   |
| 32/9  | 1         | 2.04%   |
| 3/2   | 1         | 2.04%   |
| 21/9  | 1         | 2.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 18        | 32.14%  |
| 81-90          | 17        | 30.36%  |
| 71-80          | 7         | 12.5%   |
| 201-250        | 4         | 7.14%   |
| 351-500        | 2         | 3.57%   |
| 121-130        | 2         | 3.57%   |
| 61-70          | 1         | 1.79%   |
| 51-60          | 1         | 1.79%   |
| 301-350        | 1         | 1.79%   |
| 251-300        | 1         | 1.79%   |
| 141-150        | 1         | 1.79%   |
| Unknown        | 1         | 1.79%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 32        | 58.18%  |
| 161-240       | 8         | 14.55%  |
| 51-100        | 8         | 14.55%  |
| 101-120       | 5         | 9.09%   |
| More than 240 | 1         | 1.82%   |
| Unknown       | 1         | 1.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 40        | 80%     |
| 2     | 5         | 10%     |
| 0     | 3         | 6%      |
| 5     | 1         | 2%      |
| 4     | 1         | 2%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 35        | 51.47%  |
| Realtek Semiconductor    | 20        | 29.41%  |
| Qualcomm Atheros         | 6         | 8.82%   |
| MEDIATEK                 | 2         | 2.94%   |
| Broadcom                 | 2         | 2.94%   |
| Marvell Technology Group | 1         | 1.47%   |
| DisplayLink              | 1         | 1.47%   |
| Belkin Components        | 1         | 1.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 13        | 16.05%  |
| Intel Wi-Fi 6 AX200                                                | 6         | 7.41%   |
| Intel Wi-Fi 6 AX201                                                | 4         | 4.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 3         | 3.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 3         | 3.7%    |
| Intel Comet Lake PCH CNVi WiFi                                     | 3         | 3.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter           | 2         | 2.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 2         | 2.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 2         | 2.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 2         | 2.47%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter      | 2         | 2.47%   |
| Intel Wireless 8265 / 8275                                         | 2         | 2.47%   |
| Intel Wireless 7260                                                | 2         | 2.47%   |
| Intel Wireless 3165                                                | 2         | 2.47%   |
| Intel WiFi Link 5100                                               | 2         | 2.47%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                             | 2         | 2.47%   |
| Intel Ethernet Connection (13) I219-V                              | 2         | 2.47%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                    | 2         | 2.47%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                  | 2         | 2.47%   |
| Realtek RTL8723AU 802.11n WLAN Adapter                             | 1         | 1.23%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter              | 1         | 1.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 1         | 1.23%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                         | 1         | 1.23%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller            | 1         | 1.23%   |
| Intel Wireless-AC 9260                                             | 1         | 1.23%   |
| Intel Wireless 8260                                                | 1         | 1.23%   |
| Intel Wireless 3160                                                | 1         | 1.23%   |
| Intel Tiger Lake PCH CNVi WiFi                                     | 1         | 1.23%   |
| Intel Gemini Lake PCH CNVi WiFi                                    | 1         | 1.23%   |
| Intel Ethernet controller                                          | 1         | 1.23%   |
| Intel Ethernet Connection I219-LM                                  | 1         | 1.23%   |
| Intel Ethernet Connection (7) I219-LM                              | 1         | 1.23%   |
| Intel Ethernet Connection (4) I219-LM                              | 1         | 1.23%   |
| Intel Ethernet Connection (11) I219-LM                             | 1         | 1.23%   |
| Intel Ethernet Connection (10) I219-V                              | 1         | 1.23%   |
| Intel Ethernet Connection (10) I219-LM                             | 1         | 1.23%   |
| Intel Centrino Wireless-N 2230                                     | 1         | 1.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                    | 1         | 1.23%   |
| DisplayLink GIQ Triple-display Mini Docking station                | 1         | 1.23%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                    | 1         | 1.23%   |
| Broadcom BCM43142 802.11b/g/n                                      | 1         | 1.23%   |
| Belkin Components F5D7050 Wireless G Adapter v4000 [Zydas ZD1211B] | 1         | 1.23%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 34        | 68%     |
| Realtek Semiconductor | 7         | 14%     |
| Qualcomm Atheros      | 5         | 10%     |
| MEDIATEK              | 2         | 4%      |
| Broadcom              | 1         | 2%      |
| Belkin Components     | 1         | 2%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                | 6         | 12%     |
| Intel Wi-Fi 6 AX201                                                | 4         | 8%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 3         | 6%      |
| Intel Comet Lake PCH CNVi WiFi                                     | 3         | 6%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter           | 2         | 4%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 2         | 4%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 2         | 4%      |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter      | 2         | 4%      |
| Intel Wireless 8265 / 8275                                         | 2         | 4%      |
| Intel Wireless 7260                                                | 2         | 4%      |
| Intel Wireless 3165                                                | 2         | 4%      |
| Intel WiFi Link 5100                                               | 2         | 4%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                             | 2         | 4%      |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                    | 2         | 4%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                  | 2         | 4%      |
| Realtek RTL8723AU 802.11n WLAN Adapter                             | 1         | 2%      |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter              | 1         | 2%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 1         | 2%      |
| Intel Wireless-AC 9260                                             | 1         | 2%      |
| Intel Wireless 8260                                                | 1         | 2%      |
| Intel Wireless 3160                                                | 1         | 2%      |
| Intel Tiger Lake PCH CNVi WiFi                                     | 1         | 2%      |
| Intel Gemini Lake PCH CNVi WiFi                                    | 1         | 2%      |
| Intel Centrino Wireless-N 2230                                     | 1         | 2%      |
| Intel Cannon Lake PCH CNVi WiFi                                    | 1         | 2%      |
| Broadcom BCM43142 802.11b/g/n                                      | 1         | 2%      |
| Belkin Components F5D7050 Wireless G Adapter v4000 [Zydas ZD1211B] | 1         | 2%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 17        | 56.67%  |
| Intel                    | 9         | 30%     |
| Qualcomm Atheros         | 1         | 3.33%   |
| Marvell Technology Group | 1         | 3.33%   |
| DisplayLink              | 1         | 3.33%   |
| Broadcom                 | 1         | 3.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 41.94%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 9.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 6.45%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 6.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 3.23%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 3.23%   |
| Intel Ethernet controller                                         | 1         | 3.23%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 3.23%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 3.23%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 3.23%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 3.23%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 3.23%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 3.23%   |
| DisplayLink GIQ Triple-display Mini Docking station               | 1         | 3.23%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 3.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 48        | 62.34%  |
| Ethernet | 29        | 37.66%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 45        | 88.24%  |
| Ethernet | 6         | 11.76%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 26        | 53.06%  |
| 1     | 19        | 38.78%  |
| 3     | 2         | 4.08%   |
| 0     | 2         | 4.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 37        | 75.51%  |
| Yes  | 12        | 24.49%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 30        | 69.77%  |
| Realtek Semiconductor           | 3         | 6.98%   |
| Qualcomm Atheros Communications | 3         | 6.98%   |
| Lite-On Technology              | 2         | 4.65%   |
| Foxconn / Hon Hai               | 2         | 4.65%   |
| IMC Networks                    | 1         | 2.33%   |
| Dell                            | 1         | 2.33%   |
| Broadcom                        | 1         | 2.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 9         | 20.93%  |
| Intel Bluetooth Device                         | 8         | 18.6%   |
| Intel AX200 Bluetooth                          | 6         | 13.95%  |
| Realtek Bluetooth Radio                        | 3         | 6.98%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 3         | 6.98%   |
| Qualcomm Atheros  Bluetooth Device             | 2         | 4.65%   |
| Intel AX210 Bluetooth                          | 2         | 4.65%   |
| Qualcomm Atheros Bluetooth USB Host Controller | 1         | 2.33%   |
| Lite-On Wireless_Device                        | 1         | 2.33%   |
| Lite-On Bluetooth Device                       | 1         | 2.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 1         | 2.33%   |
| Intel Centrino Bluetooth Wireless Transceiver  | 1         | 2.33%   |
| IMC Networks Bluetooth Radio                   | 1         | 2.33%   |
| Foxconn / Hon Hai Wireless_Device              | 1         | 2.33%   |
| Foxconn / Hon Hai Bluetooth Device             | 1         | 2.33%   |
| Dell Wireless 370 Bluetooth Mini-card          | 1         | 2.33%   |
| Broadcom BCM43142A0 Bluetooth Device           | 1         | 2.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel                | 35        | 56.45%  |
| AMD                  | 14        | 22.58%  |
| Nvidia               | 8         | 12.9%   |
| C-Media Electronics  | 2         | 3.23%   |
| Texas Instruments    | 1         | 1.61%   |
| Plantronics          | 1         | 1.61%   |
| fifinemicrophone.com | 1         | 1.61%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                              | 12        | 15.58%  |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 8         | 10.39%  |
| AMD Renoir Radeon High Definition Audio Controller                  | 6         | 7.79%   |
| Intel Sunrise Point-LP HD Audio                                     | 5         | 6.49%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 5         | 6.49%   |
| Intel Haswell-ULT HD Audio Controller                               | 3         | 3.9%    |
| Intel Comet Lake PCH cAVS                                           | 3         | 3.9%    |
| Intel Cannon Lake PCH cAVS                                          | 3         | 3.9%    |
| Intel 8 Series HD Audio Controller                                  | 3         | 3.9%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 3         | 3.9%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller      | 2         | 2.6%    |
| Nvidia GA104 High Definition Audio Controller                       | 2         | 2.6%    |
| Nvidia Audio device                                                 | 2         | 2.6%    |
| Intel Comet Lake PCH-LP cAVS                                        | 2         | 2.6%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio        | 2         | 2.6%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                      | 2         | 2.6%    |
| Texas Instruments PCM2903B Audio CODEC                              | 1         | 1.3%    |
| Plantronics Blackwire 325.1                                         | 1         | 1.3%    |
| Nvidia TU106 High Definition Audio Controller                       | 1         | 1.3%    |
| Nvidia GP107GL High Definition Audio Controller                     | 1         | 1.3%    |
| Intel Wildcat Point-LP High Definition Audio Controller             | 1         | 1.3%    |
| Intel Tiger Lake-H HD Audio Controller                              | 1         | 1.3%    |
| Intel Jasper Lake HD Audio                                          | 1         | 1.3%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster   | 1         | 1.3%    |
| Intel Broadwell-U Audio Controller                                  | 1         | 1.3%    |
| fifinemicrophone.com FIFINE Microphone                              | 1         | 1.3%    |
| C-Media Electronics USB Audio Device                                | 1         | 1.3%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                   | 1         | 1.3%    |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                | 1         | 1.3%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]        | 1         | 1.3%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 12        | 26.67%  |
| SK Hynix            | 8         | 17.78%  |
| Micron Technology   | 6         | 13.33%  |
| Crucial             | 6         | 13.33%  |
| Unknown             | 3         | 6.67%   |
| Kingston            | 3         | 6.67%   |
| Unknown (ABCD)      | 2         | 4.44%   |
| Silicon Power       | 1         | 2.22%   |
| Sesame              | 1         | 2.22%   |
| Patriot             | 1         | 2.22%   |
| Hikvision           | 1         | 2.22%   |
| A-DATA Technology   | 1         | 2.22%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 4.26%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 2         | 4.26%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 4.26%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 2         | 4.26%   |
| Unknown RAM Module 4GB SODIMM DDR3 1066MT/s                         | 1         | 2.13%   |
| Unknown RAM Module 2GB SODIMM DDR2                                  | 1         | 2.13%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                 | 1         | 2.13%   |
| SK Hynix RAM Module 32GB SODIMM DDR4 2667MT/s                       | 1         | 2.13%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 2.13%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 2.13%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 2.13%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2400MT/s           | 1         | 2.13%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 2.13%   |
| SK Hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 2.13%   |
| SK Hynix RAM H5TC8G63AMR-PBR 4GB SODIMM DDR3 1600MT/s               | 1         | 2.13%   |
| Silicon Power RAM SP016GBSFU266B02 16GB SODIMM DDR4 2667MT/s        | 1         | 2.13%   |
| Sesame RAM S939A2SGS-ITR 8GB SODIMM DDR3 1600MT/s                   | 1         | 2.13%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s                 | 1         | 2.13%   |
| Samsung RAM M474A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s              | 1         | 2.13%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s               | 1         | 2.13%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 2.13%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 1         | 2.13%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 2.13%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s        | 1         | 2.13%   |
| Samsung RAM K4E6E304EB-EGCF 4GB Row Of Chips LPDDR3 1867MT/s        | 1         | 2.13%   |
| Patriot RAM PSD38G1600L2S 8GB SODIMM DDR3 1600MT/s                  | 1         | 2.13%   |
| Micron RAM MT53E512M32D2NP-046 4GB Row Of Chips LPDDR4 4267MT/s     | 1         | 2.13%   |
| Micron RAM Module 3GB Row Of Chips LPDDR4 1867MT/s                  | 1         | 2.13%   |
| Micron RAM 8ATF2G64HZ-3G2E2 16GB SODIMM DDR4 3200MT/s               | 1         | 2.13%   |
| Micron RAM 53E1G32D4NQ-046 2GB Row Of Chips LPDDR4 4267MT/s         | 1         | 2.13%   |
| Kingston RAM KHYXPX-MIE 8GB SODIMM DDR4 2667MT/s                    | 1         | 2.13%   |
| Kingston RAM HP16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s               | 1         | 2.13%   |
| Kingston RAM 99U5428-101.A00LF 8GB SODIMM DDR3 1600MT/s             | 1         | 2.13%   |
| Kingston RAM 9905700-072.A01G 16GB SODIMM DDR4 3200MT/s             | 1         | 2.13%   |
| Hikvision RAM HKED4162DAA1D0MA1 16GB SODIMM DDR4 2667MT/s           | 1         | 2.13%   |
| Crucial RAM CT32G4SFD832A.C16FB 32GB SODIMM DDR4 3200MT/s           | 1         | 2.13%   |
| Crucial RAM CT16G4SFRA32A.M16FRS 16GB SODIMM DDR4 3200MT/s          | 1         | 2.13%   |
| Crucial RAM CT16G4SFD8266.M16FJ 16GB SODIMM DDR4 2667MT/s           | 1         | 2.13%   |
| Crucial RAM CT16G4SFD824A.M16FJ 16GB SODIMM DDR4 2400MT/s           | 1         | 2.13%   |
| Crucial RAM CT16G4SFD824A.C8FDD1 16384MB SODIMM DDR4 2400MT/s       | 1         | 2.13%   |
| Crucial RAM CB16GS2666.C8ET 16384MB SODIMM DDR4 2667MT/s            | 1         | 2.13%   |
| A-DATA RAM AD4S3200J4G22-B 4GB SODIMM DDR4 3200MT/s                 | 1         | 2.13%   |
| A-DATA RAM 4JQA-0622AC 4096MB SODIMM DDR4 3200MT/s                  | 1         | 2.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 20        | 55.56%  |
| LPDDR4 | 7         | 19.44%  |
| DDR3   | 5         | 13.89%  |
| LPDDR3 | 3         | 8.33%   |
| DDR2   | 1         | 2.78%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 28        | 75.68%  |
| Row Of Chips | 9         | 24.32%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 15        | 34.88%  |
| 4096  | 13        | 30.23%  |
| 16384 | 8         | 18.6%   |
| 32768 | 3         | 6.98%   |
| 2048  | 3         | 6.98%   |
| 3072  | 1         | 2.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 11        | 28.21%  |
| 2667    | 7         | 17.95%  |
| 4267    | 4         | 10.26%  |
| 2400    | 4         | 10.26%  |
| 1600    | 4         | 10.26%  |
| 2133    | 3         | 7.69%   |
| 3266    | 2         | 5.13%   |
| 1867    | 2         | 5.13%   |
| 1066    | 1         | 2.56%   |
| Unknown | 1         | 2.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Chicony Electronics         | 11        | 23.91%  |
| Realtek Semiconductor       | 6         | 13.04%  |
| IMC Networks                | 6         | 13.04%  |
| Acer                        | 6         | 13.04%  |
| Syntek                      | 3         | 6.52%   |
| Microdia                    | 3         | 6.52%   |
| Ricoh                       | 2         | 4.35%   |
| Quanta                      | 2         | 4.35%   |
| Lite-On Technology          | 2         | 4.35%   |
| USB Camera                  | 1         | 2.17%   |
| Samsung Electronics         | 1         | 2.17%   |
| Primax Electronics          | 1         | 2.17%   |
| Luxvisions Innotech Limited | 1         | 2.17%   |
| Alcor Micro                 | 1         | 2.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 5         | 10.64%  |
| Realtek Integrated_Webcam_HD             | 3         | 6.38%   |
| Microdia Integrated_Webcam_HD            | 3         | 6.38%   |
| IMC Networks Integrated Camera           | 3         | 6.38%   |
| Syntek Integrated Camera                 | 2         | 4.26%   |
| Lite-On Integrated Camera                | 2         | 4.26%   |
| IMC Networks USB2.0 HD UVC WebCam        | 2         | 4.26%   |
| Chicony HP TrueVision HD Camera          | 2         | 4.26%   |
| Chicony HD WebCam                        | 2         | 4.26%   |
| Acer Integrated Camera                   | 2         | 4.26%   |
| USB Camera USB Camera                    | 1         | 2.13%   |
| Syntek Lenovo EasyCamera                 | 1         | 2.13%   |
| Samsung Galaxy A5 (MTP)                  | 1         | 2.13%   |
| Ricoh Sony Vaio Integrated Webcam        | 1         | 2.13%   |
| Ricoh Integrated Webcam                  | 1         | 2.13%   |
| Realtek Thronmax Stream Go Pro Webcam    | 1         | 2.13%   |
| Realtek Integrated Webcam                | 1         | 2.13%   |
| Realtek Front Camera                     | 1         | 2.13%   |
| Realtek Back Camera                      | 1         | 2.13%   |
| Quanta HP HD Camera                      | 1         | 2.13%   |
| Quanta HD User Facing                    | 1         | 2.13%   |
| Primax HP HD Webcam [Fixed]              | 1         | 2.13%   |
| Luxvisions Innotech Limited HP HD Camera | 1         | 2.13%   |
| IMC Networks EasyCamera                  | 1         | 2.13%   |
| Chicony TOSHIBA Web Camera - MP          | 1         | 2.13%   |
| Chicony Integrated Camera (1280x720@30)  | 1         | 2.13%   |
| Alcor Micro USB 2.0 Web Camera           | 1         | 2.13%   |
| Acer Lenovo EasyCamera                   | 1         | 2.13%   |
| Acer HD Webcam                           | 1         | 2.13%   |
| Acer HD Camera                           | 1         | 2.13%   |
| Acer BisonCam,NB Pro                     | 1         | 2.13%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 9         | 56.25%  |
| Shenzhen Goodix Technology | 3         | 18.75%  |
| LighTuning Technology      | 2         | 12.5%   |
| Validity Sensors           | 1         | 6.25%   |
| Elan Microelectronics      | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 5         | 31.25%  |
| Shenzhen Goodix  Fingerprint Device                       | 2         | 12.5%   |
| LighTuning EgisTec Touch Fingerprint Sensor               | 2         | 12.5%   |
| Unknown                                                   | 2         | 12.5%   |
| Validity Sensors VFS 5011 fingerprint sensor              | 1         | 6.25%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 6.25%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 1         | 6.25%   |
| Shenzhen Goodix Fingerprint Reader                        | 1         | 6.25%   |
| Elan ELAN:Fingerprint                                     | 1         | 6.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 4         | 80%     |
| Broadcom    | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 4         | 80%     |
| Broadcom 58200                      | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 25        | 50%     |
| 1     | 18        | 36%     |
| 2     | 4         | 8%      |
| 3     | 3         | 6%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 15        | 48.39%  |
| Graphics card         | 8         | 25.81%  |
| Multimedia controller | 3         | 9.68%   |
| Net/wireless          | 2         | 6.45%   |
| Sound                 | 1         | 3.23%   |
| Card reader           | 1         | 3.23%   |
| Bluetooth             | 1         | 3.23%   |

