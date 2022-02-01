openSUSE Leap-15.3 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

A project to collect tested hardware configurations for openSUSE Leap-15.3.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

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

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Notebook | PCx0Dx                      | [07b8344de7](https://linux-hardware.org/?probe=07b8344de7) | Jan 21, 2022 |
| Notebook | PCx0Dx                      | [3bdae5c5ac](https://linux-hardware.org/?probe=3bdae5c5ac) | Jan 21, 2022 |
| Toshiba  | AS 1301                     | [8617f80de9](https://linux-hardware.org/?probe=8617f80de9) | Jan 01, 2022 |
| Dell     | XPS 15 9510                 | [5f594735cc](https://linux-hardware.org/?probe=5f594735cc) | Dec 28, 2021 |
| Lenovo   | ThinkPad L512 44444WG       | [113b39ddbc](https://linux-hardware.org/?probe=113b39ddbc) | Dec 25, 2021 |
| Acer     | Aspire E1-571               | [8b94542162](https://linux-hardware.org/?probe=8b94542162) | Dec 22, 2021 |
| Acer     | Aspire E1-571               | [842eae5b1d](https://linux-hardware.org/?probe=842eae5b1d) | Dec 22, 2021 |
| Dell     | Inspiron N4030              | [f5b5166d80](https://linux-hardware.org/?probe=f5b5166d80) | Dec 20, 2021 |
| Acer     | Aspire E1-571               | [27923678bd](https://linux-hardware.org/?probe=27923678bd) | Dec 16, 2021 |
| Lenovo   | ThinkPad T14 Gen 1 20UES... | [ecc22ad350](https://linux-hardware.org/?probe=ecc22ad350) | Dec 12, 2021 |
| Lenovo   | G500 20236                  | [dab30215a2](https://linux-hardware.org/?probe=dab30215a2) | Dec 05, 2021 |
| HUAWEI   | KLVL-WXX9                   | [34898be259](https://linux-hardware.org/?probe=34898be259) | Nov 28, 2021 |
| Lenovo   | ThinkPad T490s 20NYS1XK0... | [aef7318ff6](https://linux-hardware.org/?probe=aef7318ff6) | Nov 27, 2021 |
| Acer     | Aspire E1-772G              | [d49a3f3160](https://linux-hardware.org/?probe=d49a3f3160) | Nov 26, 2021 |
| Lenovo   | G50-45 80E3                 | [43f110e082](https://linux-hardware.org/?probe=43f110e082) | Nov 20, 2021 |
| Acer     | Aspire E1-772G              | [ec97cd08d4](https://linux-hardware.org/?probe=ec97cd08d4) | Nov 09, 2021 |
| Acer     | Aspire E1-772G              | [be0c106296](https://linux-hardware.org/?probe=be0c106296) | Nov 09, 2021 |
| Lenovo   | IdeaPad 330-15IKB 81DC      | [9a632ea5d1](https://linux-hardware.org/?probe=9a632ea5d1) | Nov 08, 2021 |
| Acer     | Aspire 5820TG               | [d8ae1a4109](https://linux-hardware.org/?probe=d8ae1a4109) | Nov 03, 2021 |
| Acer     | Aspire 5820TG               | [c79617751e](https://linux-hardware.org/?probe=c79617751e) | Nov 03, 2021 |
| Acer     | Aspire E1-772G              | [2ffccc532e](https://linux-hardware.org/?probe=2ffccc532e) | Oct 24, 2021 |
| Acer     | Nitro AN515-54              | [b6be115eec](https://linux-hardware.org/?probe=b6be115eec) | Oct 23, 2021 |
| Acer     | Aspire 5560                 | [39fd26f895](https://linux-hardware.org/?probe=39fd26f895) | Oct 22, 2021 |
| TUXEDO   | Aura 15 Gen1                | [627c62ae00](https://linux-hardware.org/?probe=627c62ae00) | Oct 21, 2021 |
| Medion   | E6436 MD61150               | [1edd4700fd](https://linux-hardware.org/?probe=1edd4700fd) | Oct 17, 2021 |
| Medion   | E6436 MD61150               | [2eaa34b93e](https://linux-hardware.org/?probe=2eaa34b93e) | Oct 17, 2021 |
| HP       | Laptop 15s-eq0xxx           | [fc4da04b79](https://linux-hardware.org/?probe=fc4da04b79) | Oct 16, 2021 |
| HP       | Laptop 17-ca1xxx            | [ae1811a242](https://linux-hardware.org/?probe=ae1811a242) | Oct 13, 2021 |
| Lenovo   | ThinkPad T490s 20NYS1XK0... | [d3700d8667](https://linux-hardware.org/?probe=d3700d8667) | Oct 13, 2021 |
| Lenovo   | ThinkPad L15 Gen 1 20U4S... | [3bb6121afa](https://linux-hardware.org/?probe=3bb6121afa) | Oct 13, 2021 |
| Lenovo   | ThinkPad X1 Carbon Gen 9... | [f3c6229102](https://linux-hardware.org/?probe=f3c6229102) | Oct 06, 2021 |
| Lenovo   | ThinkPad T550 20CJS1VD01    | [390b9a8a74](https://linux-hardware.org/?probe=390b9a8a74) | Oct 01, 2021 |
| MSI      | GP63 Leopard 8RD            | [21189bb3e0](https://linux-hardware.org/?probe=21189bb3e0) | Oct 01, 2021 |
| Dell     | Precision M6700             | [0d8cf3bf1c](https://linux-hardware.org/?probe=0d8cf3bf1c) | Sep 21, 2021 |
| Lenovo   | ThinkPad X1 Carbon 4th 2... | [44d0412dd3](https://linux-hardware.org/?probe=44d0412dd3) | Aug 27, 2021 |
| Samsung  | 600B4B/600B5B               | [200275bbd6](https://linux-hardware.org/?probe=200275bbd6) | Aug 27, 2021 |
| Dell     | Precision M6700             | [191db00b83](https://linux-hardware.org/?probe=191db00b83) | Aug 26, 2021 |
| Lenovo   | V330-15IKB 81AX             | [4b5a1af4dd](https://linux-hardware.org/?probe=4b5a1af4dd) | Aug 26, 2021 |
| Lenovo   | G500 20236                  | [73a5085a79](https://linux-hardware.org/?probe=73a5085a79) | Aug 24, 2021 |
| Dell     | Latitude 5480               | [a2110d9601](https://linux-hardware.org/?probe=a2110d9601) | Aug 24, 2021 |
| Dell     | Latitude 5480               | [64e1f3e16c](https://linux-hardware.org/?probe=64e1f3e16c) | Aug 19, 2021 |
| Lenovo   | ThinkPad T61 8895W9U        | [424c5f3e75](https://linux-hardware.org/?probe=424c5f3e75) | Aug 19, 2021 |
| Dell     | Inspiron 3521               | [c68ce33d52](https://linux-hardware.org/?probe=c68ce33d52) | Aug 11, 2021 |
| Dell     | Inspiron 3521               | [9a422a10d3](https://linux-hardware.org/?probe=9a422a10d3) | Aug 11, 2021 |
| Dell     | Inspiron 7460               | [f954aa3826](https://linux-hardware.org/?probe=f954aa3826) | Aug 10, 2021 |
| Samsung  | 600B4B/600B5B               | [0a650b495e](https://linux-hardware.org/?probe=0a650b495e) | Aug 09, 2021 |
| Lenovo   | ThinkPad T460 20FMS75800    | [1a1c3f469d](https://linux-hardware.org/?probe=1a1c3f469d) | Aug 07, 2021 |
| Lenovo   | ThinkPad X1 Carbon 4th 2... | [5953bc46ad](https://linux-hardware.org/?probe=5953bc46ad) | Aug 06, 2021 |
| Lenovo   | ThinkPad X1 Carbon 4th 2... | [fafaeed466](https://linux-hardware.org/?probe=fafaeed466) | Aug 06, 2021 |
| HP       | Stream Notebook PC 11       | [a612aa5d15](https://linux-hardware.org/?probe=a612aa5d15) | Jul 20, 2021 |
| Lenovo   | ThinkPad T450s 20BWA06J0... | [e4cd39ef75](https://linux-hardware.org/?probe=e4cd39ef75) | Jul 09, 2021 |
| Lenovo   | ThinkPad T450s 20BWA06J0... | [5565f4e4fe](https://linux-hardware.org/?probe=5565f4e4fe) | Jul 09, 2021 |
| Fujitsu  | LIFEBOOK E754               | [e7923c27f1](https://linux-hardware.org/?probe=e7923c27f1) | Jul 08, 2021 |
| ASUSTek  | G771JW                      | [8e6c4ddee8](https://linux-hardware.org/?probe=8e6c4ddee8) | Jun 24, 2021 |
| HP       | ZBook 17 G2                 | [3342d4d378](https://linux-hardware.org/?probe=3342d4d378) | Jun 17, 2021 |
| HP       | OMEN by HP Laptop 15-dc1... | [0c01b21401](https://linux-hardware.org/?probe=0c01b21401) | Jun 15, 2021 |
| Sony     | VPCSB15GB                   | [43a9d38ca0](https://linux-hardware.org/?probe=43a9d38ca0) | Jun 03, 2021 |
| Sony     | VGN-Z570AN                  | [13d58b8d90](https://linux-hardware.org/?probe=13d58b8d90) | May 21, 2021 |
| Sony     | VGN-Z570AN                  | [e6c7882e05](https://linux-hardware.org/?probe=e6c7882e05) | May 21, 2021 |
| MSI      | GS60 6QE                    | [93c6fd8911](https://linux-hardware.org/?probe=93c6fd8911) | May 18, 2021 |
| MSI      | GS60 6QE                    | [41fe777475](https://linux-hardware.org/?probe=41fe777475) | May 18, 2021 |
| ASUSTek  | VivoBook 12_ASUS Laptop ... | [184bedf2fd](https://linux-hardware.org/?probe=184bedf2fd) | May 01, 2021 |
| HP       | Pavilion dx6500             | [091cc2c616](https://linux-hardware.org/?probe=091cc2c616) | Apr 13, 2021 |
| HP       | Pavilion dx6500             | [6ad0d5c87f](https://linux-hardware.org/?probe=6ad0d5c87f) | Apr 13, 2021 |
| Dell     | Inspiron 15 7000 Gaming     | [97a7246099](https://linux-hardware.org/?probe=97a7246099) | Mar 01, 2021 |
| Dell     | Inspiron 15 7000 Gaming     | [b1e186207c](https://linux-hardware.org/?probe=b1e186207c) | Feb 28, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| 5.3.18-59.27-default                | 8         | 18.18%  |
| 5.3.18-59.19-default                | 5         | 11.36%  |
| 5.3.18-59.16-default                | 5         | 11.36%  |
| 5.3.18-57-default                   | 5         | 11.36%  |
| 5.3.18-59.37-default                | 4         | 9.09%   |
| 5.3.18-59.5-default                 | 2         | 4.55%   |
| 5.3.18-59.34-default                | 2         | 4.55%   |
| 5.3.18-59.24-default                | 2         | 4.55%   |
| 5.3.18-59.10-default                | 2         | 4.55%   |
| 5.3.18-59.34-preempt                | 1         | 2.27%   |
| 5.3.18-59.19-preempt                | 1         | 2.27%   |
| 5.3.18-59.13-default                | 1         | 2.27%   |
| 5.3.18-57-preempt                   | 1         | 2.27%   |
| 5.3.18-56-default                   | 1         | 2.27%   |
| 5.3.18-52-default                   | 1         | 2.27%   |
| 5.3.18-46-default                   | 1         | 2.27%   |
| 5.16.0-rc2-lp153.2.g696d453-default | 1         | 2.27%   |
| 5.15.11-lp153.3.g730a488-default    | 1         | 2.27%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.3.18  | 40        | 95.24%  |
| 5.16.0  | 1         | 2.38%   |
| 5.15.11 | 1         | 2.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.3     | 40        | 95.24%  |
| 5.16    | 1         | 2.38%   |
| 5.15    | 1         | 2.38%   |

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


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KDE5       | 16        | 36.36%  |
| KDE        | 8         | 18.18%  |
| GNOME      | 8         | 18.18%  |
| XFCE       | 6         | 13.64%  |
| Unknown    | 3         | 6.82%   |
| X-Cinnamon | 2         | 4.55%   |
| MATE       | 1         | 2.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 34        | 80.95%  |
| Wayland | 8         | 19.05%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 21        | 50%     |
| SDDM    | 9         | 21.43%  |
| LightDM | 9         | 21.43%  |
| XDM     | 2         | 4.76%   |
| GDM     | 1         | 2.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 15        | 35.71%  |
| de_DE   | 8         | 19.05%  |
| POSIX   | 3         | 7.14%   |
| fr_FR   | 3         | 7.14%   |
| ru_RU   | 2         | 4.76%   |
| pt_BR   | 2         | 4.76%   |
| es_ES   | 2         | 4.76%   |
| zh_CN   | 1         | 2.38%   |
| sv_SE   | 1         | 2.38%   |
| pt_PT   | 1         | 2.38%   |
| hu_HU   | 1         | 2.38%   |
| en_GB   | 1         | 2.38%   |
| cs_CZ   | 1         | 2.38%   |
| Unknown | 1         | 2.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 25        | 59.52%  |
| EFI  | 17        | 40.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 30        | 71.43%  |
| Ext4  | 11        | 26.19%  |
| Xfs   | 1         | 2.38%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 20        | 47.62%  |
| GPT     | 19        | 45.24%  |
| MBR     | 3         | 7.14%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 41        | 97.62%  |
| Yes       | 1         | 2.38%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 28        | 66.67%  |
| Yes       | 14        | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 12        | 28.57%  |
| Dell                | 7         | 16.67%  |
| Hewlett-Packard     | 6         | 14.29%  |
| Acer                | 5         | 11.9%   |
| Sony                | 2         | 4.76%   |
| MSI                 | 2         | 4.76%   |
| ASUSTek Computer    | 2         | 4.76%   |
| TUXEDO              | 1         | 2.38%   |
| Semp Toshiba        | 1         | 2.38%   |
| Samsung Electronics | 1         | 2.38%   |
| Medion              | 1         | 2.38%   |
| HUAWEI              | 1         | 2.38%   |
| Fujitsu             | 1         | 2.38%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| TUXEDO Aura 15 Gen1                         | 1         | 2.38%   |
| Sony VPCSB15GB                              | 1         | 2.38%   |
| Sony VGN-Z570AN                             | 1         | 2.38%   |
| Semp Toshiba AS 1301                        | 1         | 2.38%   |
| Samsung 600B4B/600B5B                       | 1         | 2.38%   |
| MSI GS60 6QE                                | 1         | 2.38%   |
| MSI GP63 Leopard 8RD                        | 1         | 2.38%   |
| Medion E6436 MD61150                        | 1         | 2.38%   |
| Lenovo V330-15IKB 81AX                      | 1         | 2.38%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW00A7TH  | 1         | 2.38%   |
| Lenovo ThinkPad X1 Carbon 4th 20FB002UMC    | 1         | 2.38%   |
| Lenovo ThinkPad T61 8895W9U                 | 1         | 2.38%   |
| Lenovo ThinkPad T490s 20NYS1XK00            | 1         | 2.38%   |
| Lenovo ThinkPad T460 20FMS75800             | 1         | 2.38%   |
| Lenovo ThinkPad T450s 20BWA06J00            | 1         | 2.38%   |
| Lenovo ThinkPad T14 Gen 1 20UES47F00        | 1         | 2.38%   |
| Lenovo ThinkPad L15 Gen 1 20U4S88000        | 1         | 2.38%   |
| Lenovo IdeaPad 330-15IKB 81DC               | 1         | 2.38%   |
| Lenovo G500 20236                           | 1         | 2.38%   |
| Lenovo G50-45 80E3                          | 1         | 2.38%   |
| HUAWEI KLVL-WXX9                            | 1         | 2.38%   |
| HP ZBook 17 G2                              | 1         | 2.38%   |
| HP Stream Notebook PC 11                    | 1         | 2.38%   |
| HP Pavilion dx6500                          | 1         | 2.38%   |
| HP OMEN by HP Laptop 15-dc1xxx              | 1         | 2.38%   |
| HP Laptop 17-ca1xxx                         | 1         | 2.38%   |
| HP Laptop 15s-eq0xxx                        | 1         | 2.38%   |
| Fujitsu LIFEBOOK E754                       | 1         | 2.38%   |
| Dell XPS 15 9510                            | 1         | 2.38%   |
| Dell Precision M6700                        | 1         | 2.38%   |
| Dell Latitude 5480                          | 1         | 2.38%   |
| Dell Inspiron N4030                         | 1         | 2.38%   |
| Dell Inspiron 7460                          | 1         | 2.38%   |
| Dell Inspiron 3521                          | 1         | 2.38%   |
| Dell Inspiron 15 7000 Gaming                | 1         | 2.38%   |
| ASUS VivoBook 12_ASUS Laptop E203MAS_E203MA | 1         | 2.38%   |
| ASUS G771JW                                 | 1         | 2.38%   |
| Acer Nitro AN515-54                         | 1         | 2.38%   |
| Acer Aspire E1-772G                         | 1         | 2.38%   |
| Acer Aspire E1-571                          | 1         | 2.38%   |
| Acer Aspire 5820TG                          | 1         | 2.38%   |
| Acer Aspire 5560                            | 1         | 2.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 8         | 19.05%  |
| Dell Inspiron     | 4         | 9.52%   |
| Acer Aspire       | 4         | 9.52%   |
| HP Laptop         | 2         | 4.76%   |
| TUXEDO Aura       | 1         | 2.38%   |
| Sony VPCSB15GB    | 1         | 2.38%   |
| Sony VGN-Z570AN   | 1         | 2.38%   |
| Semp Toshiba AS   | 1         | 2.38%   |
| Samsung 600B4B    | 1         | 2.38%   |
| MSI GS60          | 1         | 2.38%   |
| MSI GP63          | 1         | 2.38%   |
| Medion E6436      | 1         | 2.38%   |
| Lenovo V330-15IKB | 1         | 2.38%   |
| Lenovo IdeaPad    | 1         | 2.38%   |
| Lenovo G500       | 1         | 2.38%   |
| Lenovo G50-45     | 1         | 2.38%   |
| HUAWEI KLVL-WXX9  | 1         | 2.38%   |
| HP ZBook          | 1         | 2.38%   |
| HP Stream         | 1         | 2.38%   |
| HP Pavilion       | 1         | 2.38%   |
| HP OMEN           | 1         | 2.38%   |
| Fujitsu LIFEBOOK  | 1         | 2.38%   |
| Dell XPS          | 1         | 2.38%   |
| Dell Precision    | 1         | 2.38%   |
| Dell Latitude     | 1         | 2.38%   |
| ASUS VivoBook     | 1         | 2.38%   |
| ASUS G771JW       | 1         | 2.38%   |
| Acer Nitro        | 1         | 2.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 5         | 11.9%   |
| 2017 | 5         | 11.9%   |
| 2012 | 5         | 11.9%   |
| 2020 | 4         | 9.52%   |
| 2014 | 4         | 9.52%   |
| 2018 | 3         | 7.14%   |
| 2016 | 3         | 7.14%   |
| 2021 | 2         | 4.76%   |
| 2015 | 2         | 4.76%   |
| 2013 | 2         | 4.76%   |
| 2011 | 2         | 4.76%   |
| 2010 | 2         | 4.76%   |
| 2007 | 2         | 4.76%   |
| 2008 | 1         | 2.38%   |

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
| Disabled | 36        | 85.71%  |
| Enabled  | 6         | 14.29%  |

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


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 11        | 26.19%  |
| 3.01-4.0    | 8         | 19.05%  |
| 16.01-24.0  | 8         | 19.05%  |
| 8.01-16.0   | 8         | 19.05%  |
| 32.01-64.0  | 3         | 7.14%   |
| 1.01-2.0    | 2         | 4.76%   |
| 2.01-3.0    | 1         | 2.38%   |
| 64.01-256.0 | 1         | 2.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 14        | 32.56%  |
| 1.01-2.0  | 14        | 32.56%  |
| 4.01-8.0  | 9         | 20.93%  |
| 3.01-4.0  | 4         | 9.3%    |
| 8.01-16.0 | 1         | 2.33%   |
| 0.51-1.0  | 1         | 2.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 25        | 59.52%  |
| 2      | 17        | 40.48%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 25        | 59.52%  |
| Yes       | 17        | 40.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 37        | 88.1%   |
| No        | 5         | 11.9%   |

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
| Yes       | 33        | 76.74%  |
| No        | 10        | 23.26%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Germany     | 8         | 19.05%  |
| Brazil      | 6         | 14.29%  |
| France      | 4         | 9.52%   |
| USA         | 2         | 4.76%   |
| Spain       | 2         | 4.76%   |
| Russia      | 2         | 4.76%   |
| Nicaragua   | 2         | 4.76%   |
| India       | 2         | 4.76%   |
| Greece      | 2         | 4.76%   |
| Czechia     | 2         | 4.76%   |
| Thailand    | 1         | 2.38%   |
| Sweden      | 1         | 2.38%   |
| Sudan       | 1         | 2.38%   |
| Romania     | 1         | 2.38%   |
| Portugal    | 1         | 2.38%   |
| Netherlands | 1         | 2.38%   |
| Mexico      | 1         | 2.38%   |
| Hungary     | 1         | 2.38%   |
| China       | 1         | 2.38%   |
| Canada      | 1         | 2.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| São Paulo     | 2         | 4.65%   |
| Prague         | 2         | 4.65%   |
| Managua        | 2         | 4.65%   |
| Vaennaesby     | 1         | 2.33%   |
| The Hague      | 1         | 2.33%   |
| Teresina       | 1         | 2.33%   |
| Sehnde         | 1         | 2.33%   |
| S??o Paulo     | 1         | 2.33%   |
| Sartrouville   | 1         | 2.33%   |
| Rockville      | 1         | 2.33%   |
| Pringy         | 1         | 2.33%   |
| Petrozavodsk   | 1         | 2.33%   |
| Palanpur       | 1         | 2.33%   |
| Nuremberg      | 1         | 2.33%   |
| Moscow         | 1         | 2.33%   |
| Monterrey      | 1         | 2.33%   |
| Moelan-sur-Mer | 1         | 2.33%   |
| Leiria         | 1         | 2.33%   |
| Le??n          | 1         | 2.33%   |
| Khartoum       | 1         | 2.33%   |
| Kehl           | 1         | 2.33%   |
| Kathu          | 1         | 2.33%   |
| Isernhagen     | 1         | 2.33%   |
| Howick         | 1         | 2.33%   |
| Heraklion      | 1         | 2.33%   |
| Guangzhou      | 1         | 2.33%   |
| Gevelsberg     | 1         | 2.33%   |
| Esztergom      | 1         | 2.33%   |
| Dunkirk        | 1         | 2.33%   |
| Dahme          | 1         | 2.33%   |
| Concarneau     | 1         | 2.33%   |
| Cologne        | 1         | 2.33%   |
| Chapec??       | 1         | 2.33%   |
| Cestona        | 1         | 2.33%   |
| Bucharest      | 1         | 2.33%   |
| Bremen         | 1         | 2.33%   |
| Bengaluru      | 1         | 2.33%   |
| Bebedouro      | 1         | 2.33%   |
| Atlanta        | 1         | 2.33%   |
| Athens         | 1         | 2.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 12     | 17.24%  |
| WDC                 | 8         | 8      | 13.79%  |
| Seagate             | 7         | 9      | 12.07%  |
| Kingston            | 6         | 6      | 10.34%  |
| SanDisk             | 4         | 4      | 6.9%    |
| Hitachi             | 3         | 4      | 5.17%   |
| HGST                | 3         | 3      | 5.17%   |
| Unknown             | 2         | 2      | 3.45%   |
| Toshiba             | 2         | 3      | 3.45%   |
| SK Hynix            | 2         | 2      | 3.45%   |
| Silicon Motion      | 2         | 2      | 3.45%   |
| Micron Technology   | 2         | 2      | 3.45%   |
| PLEXTOR             | 1         | 2      | 1.72%   |
| Phison              | 1         | 1      | 1.72%   |
| LITEON              | 1         | 1      | 1.72%   |
| Intenso             | 1         | 1      | 1.72%   |
| Fujitsu             | 1         | 1      | 1.72%   |
| Crucial             | 1         | 1      | 1.72%   |
| China               | 1         | 1      | 1.72%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Silicon Motion NVMe SSD Drive 512GB     | 2         | 3.45%   |
| Seagate ST1000LM035-1RK172 1TB          | 2         | 3.45%   |
| HGST HTS721010A9E630 1TB                | 2         | 3.45%   |
| WDC WDS480G2G0A-00JH30 480GB SSD        | 1         | 1.72%   |
| WDC WD800BEVS-60RST0 80GB               | 1         | 1.72%   |
| WDC WD5000LPVX-00V0TT0 500GB            | 1         | 1.72%   |
| WDC WD5000LPLX-66ZNTT1 500GB            | 1         | 1.72%   |
| WDC WD10SPZX-60Z10T0 1TB                | 1         | 1.72%   |
| WDC WD10SPZX-24Z10 1TB                  | 1         | 1.72%   |
| WDC WD10SPZX-17Z10T0 1TB                | 1         | 1.72%   |
| WDC PC SN730 SDBPNTY-512G-1006 512GB    | 1         | 1.72%   |
| Unknown USD00  256GB                    | 1         | 1.72%   |
| Unknown DA4064  64GB                    | 1         | 1.72%   |
| Toshiba THNSNJ256G8NU 256GB SSD         | 1         | 1.72%   |
| Toshiba MQ01ABD075 752GB                | 1         | 1.72%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD   | 1         | 1.72%   |
| SK Hynix HBG4e  32GB                    | 1         | 1.72%   |
| Seagate ST9320325AS 320GB               | 1         | 1.72%   |
| Seagate ST500LT012-9WS142 500GB         | 1         | 1.72%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 1         | 1.72%   |
| Seagate ST500LM000-SSHD-8GB             | 1         | 1.72%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 1         | 1.72%   |
| SanDisk SSD PLUS 1000GB                 | 1         | 1.72%   |
| SanDisk SDSSDH3 1T00 1TB                | 1         | 1.72%   |
| SanDisk SD9SN8W256G 256GB SSD           | 1         | 1.72%   |
| SanDisk SD8TB8U512G1001 512GB SSD       | 1         | 1.72%   |
| Samsung SSD 970 EVO 1TB                 | 1         | 1.72%   |
| Samsung SSD 860 EVO 1TB                 | 1         | 1.72%   |
| Samsung SSD 850 EVO 250GB               | 1         | 1.72%   |
| Samsung PM9A1 NVMe 1024GB               | 1         | 1.72%   |
| Samsung NVMe SSD Drive 500GB            | 1         | 1.72%   |
| Samsung NVMe SSD Drive 1TB              | 1         | 1.72%   |
| Samsung MZVLB512HAJQ-000H1 512GB        | 1         | 1.72%   |
| Samsung MZVL21T0HCLR-00BL7 1TB          | 1         | 1.72%   |
| Samsung MZALQ256HAJD-000L1 256GB        | 1         | 1.72%   |
| Samsung MZ7LN256HCHP-000L7 256GB SSD    | 1         | 1.72%   |
| PLEXTOR PX-512M5Pro 512GB SSD           | 1         | 1.72%   |
| Phison 311CD0512GB                      | 1         | 1.72%   |
| Micron NVMe SSD Drive 512GB             | 1         | 1.72%   |
| Micron MTFDHBA512TDV 512GB              | 1         | 1.72%   |
| LITEON CX1-JB256-HP 256GB SSD           | 1         | 1.72%   |
| Kingston SNA-DC/U3 1TB SSD              | 1         | 1.72%   |
| Kingston SM2280S3G2480G 480GB SSD       | 1         | 1.72%   |
| Kingston SA400S37240G 240GB SSD         | 1         | 1.72%   |
| Kingston SA2000M81000G 1TB              | 1         | 1.72%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD | 1         | 1.72%   |
| Kingston RBU-SC100S37128GD 128GB SSD    | 1         | 1.72%   |
| Intenso SSD 512GB                       | 1         | 1.72%   |
| Hitachi HTS727550A9E365 500GB           | 1         | 1.72%   |
| Hitachi HTS547575A9E384 752GB           | 1         | 1.72%   |
| Hitachi HTS542525K9SA00 250GB           | 1         | 1.72%   |
| HGST HTS541010A9E680 1TB                | 1         | 1.72%   |
| Fujitsu MHW2120BH 120GB                 | 1         | 1.72%   |
| Crucial CT500MX500SSD1 500GB            | 1         | 1.72%   |
| China SSD 64GB                          | 1         | 1.72%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 9      | 33.33%  |
| WDC     | 6         | 6      | 28.57%  |
| Hitachi | 3         | 4      | 14.29%  |
| HGST    | 3         | 3      | 14.29%  |
| Toshiba | 1         | 2      | 4.76%   |
| Fujitsu | 1         | 1      | 4.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 5         | 5      | 25%     |
| SanDisk             | 4         | 4      | 20%     |
| Samsung Electronics | 3         | 3      | 15%     |
| WDC                 | 1         | 1      | 5%      |
| Toshiba             | 1         | 1      | 5%      |
| SK Hynix            | 1         | 1      | 5%      |
| PLEXTOR             | 1         | 2      | 5%      |
| LITEON              | 1         | 1      | 5%      |
| Intenso             | 1         | 1      | 5%      |
| Crucial             | 1         | 1      | 5%      |
| China               | 1         | 1      | 5%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 19        | 21     | 34.55%  |
| HDD  | 19        | 25     | 34.55%  |
| NVMe | 14        | 16     | 25.45%  |
| MMC  | 3         | 3      | 5.45%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 31        | 45     | 63.27%  |
| NVMe | 14        | 16     | 28.57%  |
| MMC  | 3         | 3      | 6.12%   |
| SAS  | 1         | 1      | 2.04%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 20        | 25     | 52.63%  |
| 0.51-1.0   | 18        | 21     | 47.37%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 1001-2000      | 10        | 23.26%  |
| 501-1000       | 9         | 20.93%  |
| More than 3000 | 7         | 16.28%  |
| 2001-3000      | 7         | 16.28%  |
| 251-500        | 5         | 11.63%  |
| 51-100         | 4         | 9.3%    |
| Unknown        | 1         | 2.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 51-100    | 10        | 21.74%  |
| 101-250   | 9         | 19.57%  |
| 251-500   | 8         | 17.39%  |
| 501-1000  | 5         | 10.87%  |
| 21-50     | 4         | 8.7%    |
| 1001-2000 | 4         | 8.7%    |
| 1-20      | 3         | 6.52%   |
| 2001-3000 | 2         | 4.35%   |
| Unknown   | 1         | 2.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-00V0TT0 500GB   | 1         | 1      | 33.33%  |
| Seagate ST1000LM035-1RK172 1TB | 1         | 1      | 33.33%  |
| Phison 311CD0512GB             | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Seagate | 1         | 1      | 33.33%  |
| Phison  | 1         | 1      | 33.33%  |

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
| HDD  | 2         | 2      | 66.67%  |
| NVMe | 1         | 1      | 33.33%  |

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
| Detected | 24        | 40     | 53.33%  |
| Works    | 18        | 22     | 40%     |
| Malfunc  | 3         | 3      | 6.67%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 28        | 60.87%  |
| Samsung Electronics         | 6         | 13.04%  |
| AMD                         | 4         | 8.7%    |
| Silicon Motion              | 2         | 4.35%   |
| Micron Technology           | 2         | 4.35%   |
| Sandisk                     | 1         | 2.17%   |
| Phison Electronics          | 1         | 2.17%   |
| Lite-On Technology          | 1         | 2.17%   |
| Kingston Technology Company | 1         | 2.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 12.5%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 8.33%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 6.25%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 3         | 6.25%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 2         | 4.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 4.17%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 4.17%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 4.17%   |
| Micron Non-Volatile memory controller                                          | 2         | 4.17%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 4.17%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 4.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 4.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 4.17%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 4.17%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 2.08%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 2.08%   |
| Lite-On SATA controller                                                        | 1         | 2.08%   |
| Kingston Company A2000 NVMe SSD                                                | 1         | 2.08%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 2.08%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 2.08%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 2.08%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 2.08%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 2.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 2.08%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 30        | 63.83%  |
| NVMe | 13        | 27.66%  |
| RAID | 2         | 4.26%   |
| IDE  | 2         | 4.26%   |

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


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 7.14%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 4.76%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 2.38%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 2.38%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 2.38%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 2.38%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 2.38%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 1         | 2.38%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 2.38%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 2.38%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 2.38%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 2.38%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 2.38%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 1         | 2.38%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 2.38%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 1         | 2.38%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 2.38%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 2.38%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 2.38%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 2.38%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 2.38%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 1         | 2.38%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 1         | 2.38%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 1         | 2.38%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 1         | 2.38%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz          | 1         | 2.38%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 1         | 2.38%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 1         | 2.38%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 1         | 2.38%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 1         | 2.38%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 2.38%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 1         | 2.38%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 1         | 2.38%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 2.38%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 2.38%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 1         | 2.38%   |
| AMD C-50 Processor                            | 1         | 2.38%   |
| AMD A6-6310 APU with AMD Radeon R4 Graphics   | 1         | 2.38%   |
| AMD A6-3420M APU with Radeon HD Graphics      | 1         | 2.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 13        | 30.95%  |
| Intel Core i7    | 11        | 26.19%  |
| Intel Core i3    | 3         | 7.14%   |
| Intel Core 2 Duo | 3         | 7.14%   |
| Other            | 2         | 4.76%   |
| Intel Celeron    | 2         | 4.76%   |
| AMD Ryzen 7      | 2         | 4.76%   |
| AMD A6           | 2         | 4.76%   |
| AMD Ryzen 7 PRO  | 1         | 2.38%   |
| AMD Ryzen 5      | 1         | 2.38%   |
| AMD Ryzen 3      | 1         | 2.38%   |
| AMD C-50         | 1         | 2.38%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 23        | 54.76%  |
| 4      | 12        | 28.57%  |
| 8      | 4         | 9.52%   |
| 6      | 3         | 7.14%   |

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
| Unknown    | 17        | 39.53%  |
| 0x806e9    | 3         | 6.98%   |
| 0x08600106 | 3         | 6.98%   |
| 0x906ea    | 2         | 4.65%   |
| 0x6fd      | 2         | 4.65%   |
| 0x406e3    | 2         | 4.65%   |
| 0x806ec    | 1         | 2.33%   |
| 0x806d1    | 1         | 2.33%   |
| 0x806c1    | 1         | 2.33%   |
| 0x706a1    | 1         | 2.33%   |
| 0x506e3    | 1         | 2.33%   |
| 0x306d4    | 1         | 2.33%   |
| 0x306c3    | 1         | 2.33%   |
| 0x306a9    | 1         | 2.33%   |
| 0x30678    | 1         | 2.33%   |
| 0x206a7    | 1         | 2.33%   |
| 0x20655    | 1         | 2.33%   |
| 0x10676    | 1         | 2.33%   |
| 0x08108109 | 1         | 2.33%   |
| 0x07030105 | 1         | 2.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 11        | 26.19%  |
| IvyBridge     | 4         | 9.52%   |
| Haswell       | 4         | 9.52%   |
| Zen 2         | 3         | 7.14%   |
| Skylake       | 3         | 7.14%   |
| Zen+          | 2         | 4.76%   |
| Westmere      | 2         | 4.76%   |
| SandyBridge   | 2         | 4.76%   |
| Core          | 2         | 4.76%   |
| TigerLake     | 1         | 2.38%   |
| Silvermont    | 1         | 2.38%   |
| Puma          | 1         | 2.38%   |
| Penryn        | 1         | 2.38%   |
| K10 Llano     | 1         | 2.38%   |
| Icelake       | 1         | 2.38%   |
| Goldmont plus | 1         | 2.38%   |
| Broadwell     | 1         | 2.38%   |
| Bobcat        | 1         | 2.38%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 34        | 57.63%  |
| AMD    | 13        | 22.03%  |
| Nvidia | 12        | 20.34%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                 | 4         | 6.56%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 4         | 6.56%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 4         | 6.56%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 3         | 4.92%   |
| AMD Renoir                                                                            | 3         | 4.92%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 2         | 3.28%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 2         | 3.28%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 2         | 3.28%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 2         | 3.28%   |
| Intel Core Processor Integrated Graphics Controller                                   | 2         | 3.28%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 2         | 3.28%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 2         | 3.28%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 1         | 1.64%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                           | 1         | 1.64%   |
| Nvidia GM204M [GeForce GTX 980M]                                                      | 1         | 1.64%   |
| Nvidia GM204M [GeForce GTX 970M]                                                      | 1         | 1.64%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 1         | 1.64%   |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 1         | 1.64%   |
| Nvidia GK104GLM [Quadro K3000M]                                                       | 1         | 1.64%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 1         | 1.64%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 1         | 1.64%   |
| Nvidia G98M [GeForce 9300M GS]                                                        | 1         | 1.64%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 1         | 1.64%   |
| Intel UHD Graphics 620                                                                | 1         | 1.64%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 1         | 1.64%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 1         | 1.64%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 1         | 1.64%   |
| Intel HD Graphics 630                                                                 | 1         | 1.64%   |
| Intel HD Graphics 5500                                                                | 1         | 1.64%   |
| Intel HD Graphics 530                                                                 | 1         | 1.64%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 1         | 1.64%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 1         | 1.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 1         | 1.64%   |
| AMD Wrestler [Radeon HD 6250]                                                         | 1         | 1.64%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 1.64%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                             | 1         | 1.64%   |
| AMD Sun PRO [Radeon HD 8570A/8570M]                                                   | 1         | 1.64%   |
| AMD Sumo [Radeon HD 6520G]                                                            | 1         | 1.64%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                            | 1         | 1.64%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                   | 1         | 1.64%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                              | 1         | 1.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 18        | 42.86%  |
| Intel + Nvidia | 11        | 26.19%  |
| 1 x AMD        | 8         | 19.05%  |
| Intel + AMD    | 5         | 11.9%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 37        | 88.1%   |
| Proprietary | 5         | 11.9%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 32        | 76.19%  |
| 0.01-0.5   | 5         | 11.9%   |
| 1.01-2.0   | 2         | 4.76%   |
| 7.01-8.0   | 1         | 2.38%   |
| 3.01-4.0   | 1         | 2.38%   |
| 0.51-1.0   | 1         | 2.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 12        | 23.53%  |
| Chimei Innolux      | 11        | 21.57%  |
| AU Optronics        | 8         | 15.69%  |
| Goldstar            | 4         | 7.84%   |
| Samsung Electronics | 3         | 5.88%   |
| Lenovo              | 2         | 3.92%   |
| Hewlett-Packard     | 2         | 3.92%   |
| Sony                | 1         | 1.96%   |
| Sharp               | 1         | 1.96%   |
| LG Philips          | 1         | 1.96%   |
| InfoVision          | 1         | 1.96%   |
| Iiyama              | 1         | 1.96%   |
| Dell                | 1         | 1.96%   |
| CSO                 | 1         | 1.96%   |
| CPT                 | 1         | 1.96%   |
| BOE                 | 1         | 1.96%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 2         | 3.85%   |
| Hewlett-Packard LV1911 HWP3005 1366x768 410x230mm 18.5-inch             | 2         | 3.85%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                 | 2         | 3.85%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch    | 1         | 1.92%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                 | 1         | 1.92%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch       | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SEC3449 1366x768 309x174mm 14.0-inch    | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SDC424B 3840x2160 344x194mm 15.5-inch   | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1872x1053mm 84.6-inch | 1         | 1.92%   |
| LG Philips LCD Monitor LPLDB00 1280x800 331x207mm 15.4-inch             | 1         | 1.92%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch            | 1         | 1.92%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch            | 1         | 1.92%   |
| LG Display LCD Monitor LGD059E 1920x1080 382x215mm 17.3-inch            | 1         | 1.92%   |
| LG Display LCD Monitor LGD053C 1920x1080 309x174mm 14.0-inch            | 1         | 1.92%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch            | 1         | 1.92%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch            | 1         | 1.92%   |
| LG Display LCD Monitor LGD04A9 1920x1080 309x174mm 14.0-inch            | 1         | 1.92%   |
| LG Display LCD Monitor LGD046C 1920x1080 382x215mm 17.3-inch            | 1         | 1.92%   |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch            | 1         | 1.92%   |
| LG Display LCD Monitor LGD02DA 1920x1080 380x220mm 17.3-inch            | 1         | 1.92%   |
| Lenovo LEN P27q-10 LEN61A8 2560x1440 597x336mm 27.0-inch                | 1         | 1.92%   |
| Lenovo LCD Monitor LEN4020 1024x768 286x214mm 14.1-inch                 | 1         | 1.92%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch             | 1         | 1.92%   |
| Iiyama PL2492H IVM612F 1920x1080 527x296mm 23.8-inch                    | 1         | 1.92%   |
| Goldstar LG FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch               | 1         | 1.92%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch                | 1         | 1.92%   |
| Dell U2410 DELF017 1920x1200 518x324mm 24.1-inch                        | 1         | 1.92%   |
| CSO LCD Monitor CSO1404 1920x1200 302x189mm 14.0-inch                   | 1         | 1.92%   |
| CPT LCD Monitor CPT17D8 1366x768 293x165mm 13.2-inch                    | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch        | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN15F6 1920x1080 344x193mm 15.5-inch        | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 344x193mm 15.5-inch        | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch         | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch         | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch        | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch         | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN14F5 1920x1080 309x173mm 13.9-inch        | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch         | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch         | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN1136 1366x768 256x144mm 11.6-inch         | 1         | 1.92%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                   | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch          | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch          | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch           | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO225C 1366x768 256x144mm 11.6-inch           | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch          | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch          | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch           | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch           | 1         | 1.92%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 20        | 42.55%  |
| 1366x768 (WXGA)   | 13        | 27.66%  |
| 1920x1200 (WUXGA) | 3         | 6.38%   |
| 3840x2160 (4K)    | 2         | 4.26%   |
| 2560x1080         | 2         | 4.26%   |
| 1600x900 (HD+)    | 2         | 4.26%   |
| 3840x2400         | 1         | 2.13%   |
| 2560x1440 (QHD)   | 1         | 2.13%   |
| 2160x1440         | 1         | 2.13%   |
| 1280x800 (WXGA)   | 1         | 2.13%   |
| 1024x768 (XGA)    | 1         | 2.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 20        | 38.46%  |
| 14     | 9         | 17.31%  |
| 17     | 6         | 11.54%  |
| 13     | 4         | 7.69%   |
| 34     | 2         | 3.85%   |
| 27     | 2         | 3.85%   |
| 18     | 2         | 3.85%   |
| 11     | 2         | 3.85%   |
| 84     | 1         | 1.92%   |
| 26     | 1         | 1.92%   |
| 24     | 1         | 1.92%   |
| 23     | 1         | 1.92%   |
| 21     | 1         | 1.92%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 30        | 57.69%  |
| 351-400     | 6         | 11.54%  |
| 201-300     | 5         | 9.62%   |
| 501-600     | 4         | 7.69%   |
| 401-500     | 3         | 5.77%   |
| 701-800     | 2         | 3.85%   |
| 601-700     | 1         | 1.92%   |
| 1501-2000   | 1         | 1.92%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 37        | 82.22%  |
| 16/10 | 4         | 8.89%   |
| 21/9  | 2         | 4.44%   |
| 4/3   | 1         | 2.22%   |
| 3/2   | 1         | 2.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 20        | 38.46%  |
| 81-90          | 11        | 21.15%  |
| 121-130        | 6         | 11.54%  |
| 301-350        | 3         | 5.77%   |
| 201-250        | 3         | 5.77%   |
| 51-60          | 2         | 3.85%   |
| 351-500        | 2         | 3.85%   |
| 141-150        | 2         | 3.85%   |
| More than 1000 | 1         | 1.92%   |
| 71-80          | 1         | 1.92%   |
| 91-100         | 1         | 1.92%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 22        | 43.14%  |
| 101-120       | 15        | 29.41%  |
| 51-100        | 10        | 19.61%  |
| More than 240 | 2         | 3.92%   |
| 161-240       | 2         | 3.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 32        | 76.19%  |
| 2     | 10        | 23.81%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 25        | 37.88%  |
| Realtek Semiconductor | 20        | 30.3%   |
| Qualcomm Atheros      | 10        | 15.15%  |
| Broadcom              | 5         | 7.58%   |
| Broadcom Limited      | 2         | 3.03%   |
| Samsung Electronics   | 1         | 1.52%   |
| Manta                 | 1         | 1.52%   |
| Lenovo                | 1         | 1.52%   |
| ASIX Electronics      | 1         | 1.52%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14        | 16.87%  |
| Intel Wi-Fi 6 AX200                                               | 4         | 4.82%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 2.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 2.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 2.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 2.41%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 2.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 2.41%   |
| Intel Wireless 8265 / 8275                                        | 2         | 2.41%   |
| Intel Wireless 8260                                               | 2         | 2.41%   |
| Intel Wireless 7260                                               | 2         | 2.41%   |
| Intel Wireless 3165                                               | 2         | 2.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.41%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 2.41%   |
| Samsung Kiera                                                     | 1         | 1.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.2%    |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 1.2%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 1.2%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.2%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.2%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 1.2%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.2%    |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 1.2%    |
| Manta MM812                                                       | 1         | 1.2%    |
| Lenovo OneLink+ Giga                                              | 1         | 1.2%    |
| Intel Wireless 7265                                               | 1         | 1.2%    |
| Intel WiFi Link 5100                                              | 1         | 1.2%    |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.2%    |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 1.2%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 1         | 1.2%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 1.2%    |
| Intel Gemini Lake PCH CNVi WiFi                                   | 1         | 1.2%    |
| Intel Ethernet Connection I219-V                                  | 1         | 1.2%    |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.2%    |
| Intel Ethernet Connection I217-V                                  | 1         | 1.2%    |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.2%    |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.2%    |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.2%    |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.2%    |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.2%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 1         | 1.2%    |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                     | 1         | 1.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 1.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 1.2%    |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.2%    |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.2%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.2%    |
| Broadcom Limited NetLink BCM57785 Gigabit Ethernet PCIe           | 1         | 1.2%    |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 1.2%    |
| Broadcom BCM43228 802.11a/b/g/n                                   | 1         | 1.2%    |
| Broadcom BCM43227 802.11b/g/n                                     | 1         | 1.2%    |
| Broadcom BCM43225 802.11b/g/n                                     | 1         | 1.2%    |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.2%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 23        | 54.76%  |
| Realtek Semiconductor | 8         | 19.05%  |
| Qualcomm Atheros      | 6         | 14.29%  |
| Broadcom              | 5         | 11.9%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 4         | 9.52%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 2         | 4.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 2         | 4.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 2         | 4.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 2         | 4.76%   |
| Intel Wireless 8265 / 8275                                    | 2         | 4.76%   |
| Intel Wireless 8260                                           | 2         | 4.76%   |
| Intel Wireless 7260                                           | 2         | 4.76%   |
| Intel Wireless 3165                                           | 2         | 4.76%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 2         | 4.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 1         | 2.38%   |
| Realtek RTL8191SEvB Wireless LAN Controller                   | 1         | 2.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 1         | 2.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 1         | 2.38%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 1         | 2.38%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 1         | 2.38%   |
| Intel Wireless 7265                                           | 1         | 2.38%   |
| Intel WiFi Link 5100                                          | 1         | 2.38%   |
| Intel Wi-Fi 6 AX201                                           | 1         | 2.38%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 1         | 2.38%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection | 1         | 2.38%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection         | 1         | 2.38%   |
| Intel Gemini Lake PCH CNVi WiFi                               | 1         | 2.38%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                  | 1         | 2.38%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                 | 1         | 2.38%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 1         | 2.38%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 1         | 2.38%   |
| Broadcom BCM43228 802.11a/b/g/n                               | 1         | 2.38%   |
| Broadcom BCM43227 802.11b/g/n                                 | 1         | 2.38%   |
| Broadcom BCM43225 802.11b/g/n                                 | 1         | 2.38%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 16        | 41.03%  |
| Intel                 | 12        | 30.77%  |
| Qualcomm Atheros      | 5         | 12.82%  |
| Broadcom Limited      | 2         | 5.13%   |
| Samsung Electronics   | 1         | 2.56%   |
| Lenovo                | 1         | 2.56%   |
| Broadcom              | 1         | 2.56%   |
| ASIX Electronics      | 1         | 2.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14        | 35%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 5%      |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 5%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 5%      |
| Samsung Kiera                                                     | 1         | 2.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.5%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 2.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 2.5%    |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 2.5%    |
| Lenovo OneLink+ Giga                                              | 1         | 2.5%    |
| Intel Ethernet Connection I219-V                                  | 1         | 2.5%    |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.5%    |
| Intel Ethernet Connection I217-V                                  | 1         | 2.5%    |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.5%    |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 2.5%    |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.5%    |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2.5%    |
| Intel Ethernet Connection (10) I219-V                             | 1         | 2.5%    |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.5%    |
| Intel 82566MM Gigabit Network Connection                          | 1         | 2.5%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 2.5%    |
| Broadcom Limited NetLink BCM57785 Gigabit Ethernet PCIe           | 1         | 2.5%    |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 2.5%    |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 2.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 42        | 52.5%   |
| Ethernet | 37        | 46.25%  |
| Unknown  | 1         | 1.25%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 39        | 54.93%  |
| Ethernet | 32        | 45.07%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 35        | 83.33%  |
| 1     | 6         | 14.29%  |
| 3     | 1         | 2.38%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 30        | 71.43%  |
| Yes  | 12        | 28.57%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 13        | 39.39%  |
| Realtek Semiconductor           | 6         | 18.18%  |
| Qualcomm Atheros Communications | 4         | 12.12%  |
| Foxconn / Hon Hai               | 2         | 6.06%   |
| Broadcom                        | 2         | 6.06%   |
| Realtek                         | 1         | 3.03%   |
| Lite-On Technology              | 1         | 3.03%   |
| IMC Networks                    | 1         | 3.03%   |
| Dell                            | 1         | 3.03%   |
| Cambridge Silicon Radio         | 1         | 3.03%   |
| Alps Electric                   | 1         | 3.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                                              | 10        | 30.3%   |
| Realtek Bluetooth Radio                                                             | 3         | 9.09%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 6.06%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 2         | 6.06%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 2         | 6.06%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 3.03%   |
| Realtek Bluetooth Radio                                                             | 1         | 3.03%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 3.03%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 3.03%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 3.03%   |
| Intel Bluetooth wireless interface                                                  | 1         | 3.03%   |
| IMC Networks Bluetooth Device                                                       | 1         | 3.03%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 3.03%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 1         | 3.03%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 3.03%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 3.03%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 1         | 3.03%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 3.03%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 3.03%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor    | Notebooks | Percent |
|-----------|-----------|---------|
| Intel     | 34        | 65.38%  |
| AMD       | 9         | 17.31%  |
| Nvidia    | 3         | 5.77%   |
| Logitech  | 2         | 3.85%   |
| Lenovo    | 2         | 3.85%   |
| JMTek     | 1         | 1.92%   |
| GN Netcom | 1         | 1.92%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 7         | 11.11%  |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 6.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 6.35%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 4         | 6.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 4.76%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 4.76%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 4.76%   |
| Logitech Headset H390                                                      | 2         | 3.17%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 3.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 3.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 3.17%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 3.17%   |
| AMD FCH Azalia Controller                                                  | 2         | 3.17%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.59%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.59%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 1.59%   |
| Lenovo ThinkPad Thunderbolt 4 Dock USB Audio                               | 1         | 1.59%   |
| Lenovo ThinkPad OneLink Plus Dock Audio                                    | 1         | 1.59%   |
| JMTek audio controller                                                     | 1         | 1.59%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 1.59%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 1.59%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.59%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.59%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.59%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.59%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.59%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 1.59%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 1.59%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.59%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.59%   |
| GN Netcom Jabra UC VOICE 150a MS                                           | 1         | 1.59%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 1.59%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.59%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1         | 1.59%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.59%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]        | 1         | 1.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 11        | 37.93%  |
| SK Hynix            | 6         | 20.69%  |
| Unknown             | 4         | 13.79%  |
| Kingston            | 2         | 6.9%    |
| Smart               | 1         | 3.45%   |
| Ramaxel Technology  | 1         | 3.45%   |
| Micron Technology   | 1         | 3.45%   |
| GOODRAM             | 1         | 3.45%   |
| Corsair             | 1         | 3.45%   |
| A-DATA Technology   | 1         | 3.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                  | 1         | 3.03%   |
| Unknown RAM Module 4096MB SODIMM DDR3                       | 1         | 3.03%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                  | 1         | 3.03%   |
| Unknown RAM Module 2048MB SODIMM 1067MT/s                   | 1         | 3.03%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                  | 1         | 3.03%   |
| Unknown RAM Module 1024MB SODIMM 1067MT/s                   | 1         | 3.03%   |
| Smart RAM SH564568FH8NWPHSFG 2GB SODIMM DDR3 1333MT/s       | 1         | 3.03%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                | 1         | 3.03%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s      | 1         | 3.03%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s   | 1         | 3.03%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s     | 1         | 3.03%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s   | 1         | 3.03%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s   | 1         | 3.03%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s   | 1         | 3.03%   |
| Samsung RAM M471B5673EH1-CH9 2048MB SODIMM DDR3 1334MT/s    | 1         | 3.03%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s    | 1         | 3.03%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s    | 1         | 3.03%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s    | 1         | 3.03%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s      | 1         | 3.03%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s      | 1         | 3.03%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s      | 1         | 3.03%   |
| Samsung RAM M471A1K43EB1-CWE 8192MB SODIMM DDR4 3200MT/s    | 1         | 3.03%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 1         | 3.03%   |
| Samsung RAM K4F6E3S4HM-MGCJ 4GB SODIMM LPDDR4 3733MT/s      | 1         | 3.03%   |
| Samsung RAM K4E6E304EE-EGCF 4GB SODIMM LPDDR3 1867MT/s      | 1         | 3.03%   |
| Samsung RAM K4E6E304EE-EGCF 4GB Chip LPDDR3 1867MT/s        | 1         | 3.03%   |
| Ramaxel RAM RMT3170ME68F9F1600 4096MB SODIMM DDR3 1600MT/s  | 1         | 3.03%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s | 1         | 3.03%   |
| Kingston RAM MSI26D4S9S8ME-8 8192MB SODIMM DDR4 2667MT/s    | 1         | 3.03%   |
| Kingston RAM ACR16D3LS1KFG/8G 8GB SODIMM DDR3 1600MT/s      | 1         | 3.03%   |
| GOODRAM RAM IR2400S464L15S/8G 8192MB SODIMM DDR4 2133MT/s   | 1         | 3.03%   |
| Corsair RAM CMSX8GX4M1A2400C16 8GB SODIMM DDR4 2400MT/s     | 1         | 3.03%   |
| A-DATA RAM Module 8192MB SODIMM DDR4 2133MT/s               | 1         | 3.03%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 12        | 44.44%  |
| DDR3    | 8         | 29.63%  |
| LPDDR4  | 3         | 11.11%  |
| DDR2    | 2         | 7.41%   |
| LPDDR3  | 1         | 3.7%    |
| Unknown | 1         | 3.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 24        | 88.89%  |
| Row Of Chips | 2         | 7.41%   |
| Chip         | 1         | 3.7%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 11        | 34.38%  |
| 4096  | 10        | 31.25%  |
| 2048  | 5         | 15.63%  |
| 16384 | 3         | 9.38%   |
| 1024  | 2         | 6.25%   |
| 32768 | 1         | 3.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 6         | 20.69%  |
| 1600    | 6         | 20.69%  |
| 3200    | 5         | 17.24%  |
| 2133    | 2         | 6.9%    |
| 667     | 2         | 6.9%    |
| 4267    | 1         | 3.45%   |
| 3733    | 1         | 3.45%   |
| 2400    | 1         | 3.45%   |
| 1867    | 1         | 3.45%   |
| 1334    | 1         | 3.45%   |
| 1333    | 1         | 3.45%   |
| 1067    | 1         | 3.45%   |
| Unknown | 1         | 3.45%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Prolific Technology | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port | 1         | 100%    |

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
| Chicony Electronics                    | 7         | 18.42%  |
| Acer                                   | 5         | 13.16%  |
| Sunplus Innovation Technology          | 4         | 10.53%  |
| Realtek Semiconductor                  | 4         | 10.53%  |
| Quanta                                 | 3         | 7.89%   |
| Microdia                               | 3         | 7.89%   |
| IMC Networks                           | 3         | 7.89%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 7.89%   |
| Syntek                                 | 1         | 2.63%   |
| Silicon Motion                         | 1         | 2.63%   |
| Ricoh                                  | 1         | 2.63%   |
| Luxvisions Innotech Limited            | 1         | 2.63%   |
| Lite-On Technology                     | 1         | 2.63%   |
| ALi                                    | 1         | 2.63%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                | 4         | 10.26%  |
| Sunplus HD WebCam                                                        | 2         | 5.13%   |
| Microdia Integrated_Webcam_HD                                            | 2         | 5.13%   |
| Acer Integrated Camera                                                   | 2         | 5.13%   |
| Syntek Lenovo EasyCamera                                                 | 1         | 2.56%   |
| Sunplus Integrated_Webcam_HD                                             | 1         | 2.56%   |
| Sunplus 1.3M HD WebCam                                                   | 1         | 2.56%   |
| Silicon Motion WebCam SC-13HDN10939N                                     | 1         | 2.56%   |
| Ricoh Sony Vaio Integrated Webcam                                        | 1         | 2.56%   |
| Realtek USB Camera                                                       | 1         | 2.56%   |
| Realtek Lenovo EasyCamera                                                | 1         | 2.56%   |
| Realtek Laptop_Integrated_Webcam_HD                                      | 1         | 2.56%   |
| Realtek Integrated_Webcam_HD                                             | 1         | 2.56%   |
| Realtek Integrated Webcam HD                                             | 1         | 2.56%   |
| Quanta HP Wide Vision HD Camera                                          | 1         | 2.56%   |
| Quanta HP TrueVision HD Camera                                           | 1         | 2.56%   |
| Quanta HD User Facing                                                    | 1         | 2.56%   |
| Microdia Laptop_Integrated_Webcam_0.3M                                   | 1         | 2.56%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                      | 1         | 2.56%   |
| Lite-On Integrated Camera                                                | 1         | 2.56%   |
| IMC Networks USB2.0 VGA UVC WebCam                                       | 1         | 2.56%   |
| IMC Networks USB2.0 UVC HD Webcam                                        | 1         | 2.56%   |
| IMC Networks Integrated Camera                                           | 1         | 2.56%   |
| Chicony VGA 24fps UVC Webcam                                             | 1         | 2.56%   |
| Chicony USB2.0 Camera                                                    | 1         | 2.56%   |
| Chicony EasyCamera                                                       | 1         | 2.56%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                            | 1         | 2.56%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 1         | 2.56%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                         | 1         | 2.56%   |
| ALi Gateway Webcam                                                       | 1         | 2.56%   |
| Acer HD Webcam                                                           | 1         | 2.56%   |
| Acer BisonCam,NB Pro                                                     | 1         | 2.56%   |
| Acer BisonCam, NB Pro                                                    | 1         | 2.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 36.36%  |
| Synaptics                  | 4         | 36.36%  |
| Upek                       | 1         | 9.09%   |
| Shenzhen Goodix Technology | 1         | 9.09%   |
| AuthenTec                  | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 2         | 18.18%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 18.18%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 9.09%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 9.09%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 9.09%   |
| Synaptics  WBDI                                        | 1         | 9.09%   |
| Shenzhen Goodix  Fingerprint Device                    | 1         | 9.09%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 1         | 9.09%   |
| Unknown                                                | 1         | 9.09%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 2         | 40%     |
| O2 Micro              | 1         | 20%     |
| Gemalto (was Gemplus) | 1         | 20%     |
| Broadcom              | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader               | 2         | 40%     |
| O2 Micro OZ776 CCID Smartcard Reader              | 1         | 20%     |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor    | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 25        | 58.14%  |
| 1     | 14        | 32.56%  |
| 2     | 4         | 9.3%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 11        | 47.83%  |
| Chipcard           | 6         | 26.09%  |
| Graphics card      | 3         | 13.04%  |
| Net/wireless       | 2         | 8.7%    |
| Camera             | 1         | 4.35%   |

