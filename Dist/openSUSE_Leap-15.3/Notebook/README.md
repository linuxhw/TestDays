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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | CX600                       | [bbd815a6e9](https://linux-hardware.org/?probe=bbd815a6e9) | Feb 17, 2022 |
| LG Electro... | C400-G.BC22P1               | [e202260efb](https://linux-hardware.org/?probe=e202260efb) | Feb 14, 2022 |
| Acer          | Nitro AN515-52              | [51a06ffad3](https://linux-hardware.org/?probe=51a06ffad3) | Feb 05, 2022 |
| Acer          | Aspire VN7-792G             | [20e910e73b](https://linux-hardware.org/?probe=20e910e73b) | Feb 05, 2022 |
| Notebook      | PCx0Dx                      | [07b8344de7](https://linux-hardware.org/?probe=07b8344de7) | Jan 21, 2022 |
| Notebook      | PCx0Dx                      | [3bdae5c5ac](https://linux-hardware.org/?probe=3bdae5c5ac) | Jan 21, 2022 |
| Toshiba       | AS 1301                     | [8617f80de9](https://linux-hardware.org/?probe=8617f80de9) | Jan 01, 2022 |
| Dell          | XPS 15 9510                 | [5f594735cc](https://linux-hardware.org/?probe=5f594735cc) | Dec 28, 2021 |
| Lenovo        | ThinkPad L512 44444WG       | [113b39ddbc](https://linux-hardware.org/?probe=113b39ddbc) | Dec 25, 2021 |
| Acer          | Aspire E1-571               | [8b94542162](https://linux-hardware.org/?probe=8b94542162) | Dec 22, 2021 |
| Acer          | Aspire E1-571               | [842eae5b1d](https://linux-hardware.org/?probe=842eae5b1d) | Dec 22, 2021 |
| Dell          | Inspiron N4030              | [f5b5166d80](https://linux-hardware.org/?probe=f5b5166d80) | Dec 20, 2021 |
| Acer          | Aspire E1-571               | [27923678bd](https://linux-hardware.org/?probe=27923678bd) | Dec 16, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [ecc22ad350](https://linux-hardware.org/?probe=ecc22ad350) | Dec 12, 2021 |
| Lenovo        | G500 20236                  | [dab30215a2](https://linux-hardware.org/?probe=dab30215a2) | Dec 05, 2021 |
| HUAWEI        | KLVL-WXX9                   | [34898be259](https://linux-hardware.org/?probe=34898be259) | Nov 28, 2021 |
| Lenovo        | ThinkPad T490s 20NYS1XK0... | [aef7318ff6](https://linux-hardware.org/?probe=aef7318ff6) | Nov 27, 2021 |
| Acer          | Aspire E1-772G              | [d49a3f3160](https://linux-hardware.org/?probe=d49a3f3160) | Nov 26, 2021 |
| Lenovo        | G50-45 80E3                 | [43f110e082](https://linux-hardware.org/?probe=43f110e082) | Nov 20, 2021 |
| Acer          | Aspire E1-772G              | [ec97cd08d4](https://linux-hardware.org/?probe=ec97cd08d4) | Nov 09, 2021 |
| Acer          | Aspire E1-772G              | [be0c106296](https://linux-hardware.org/?probe=be0c106296) | Nov 09, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [9a632ea5d1](https://linux-hardware.org/?probe=9a632ea5d1) | Nov 08, 2021 |
| Acer          | Aspire 5820TG               | [d8ae1a4109](https://linux-hardware.org/?probe=d8ae1a4109) | Nov 03, 2021 |
| Acer          | Aspire 5820TG               | [c79617751e](https://linux-hardware.org/?probe=c79617751e) | Nov 03, 2021 |
| Acer          | Aspire E1-772G              | [2ffccc532e](https://linux-hardware.org/?probe=2ffccc532e) | Oct 24, 2021 |
| Acer          | Nitro AN515-54              | [b6be115eec](https://linux-hardware.org/?probe=b6be115eec) | Oct 23, 2021 |
| Acer          | Aspire 5560                 | [39fd26f895](https://linux-hardware.org/?probe=39fd26f895) | Oct 22, 2021 |
| TUXEDO        | Aura 15 Gen1                | [627c62ae00](https://linux-hardware.org/?probe=627c62ae00) | Oct 21, 2021 |
| Medion        | E6436 MD61150               | [1edd4700fd](https://linux-hardware.org/?probe=1edd4700fd) | Oct 17, 2021 |
| Medion        | E6436 MD61150               | [2eaa34b93e](https://linux-hardware.org/?probe=2eaa34b93e) | Oct 17, 2021 |
| HP            | Laptop 15s-eq0xxx           | [fc4da04b79](https://linux-hardware.org/?probe=fc4da04b79) | Oct 16, 2021 |
| HP            | Laptop 17-ca1xxx            | [ae1811a242](https://linux-hardware.org/?probe=ae1811a242) | Oct 13, 2021 |
| Lenovo        | ThinkPad T490s 20NYS1XK0... | [d3700d8667](https://linux-hardware.org/?probe=d3700d8667) | Oct 13, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | [3bb6121afa](https://linux-hardware.org/?probe=3bb6121afa) | Oct 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [f3c6229102](https://linux-hardware.org/?probe=f3c6229102) | Oct 06, 2021 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | [390b9a8a74](https://linux-hardware.org/?probe=390b9a8a74) | Oct 01, 2021 |
| MSI           | GP63 Leopard 8RD            | [21189bb3e0](https://linux-hardware.org/?probe=21189bb3e0) | Oct 01, 2021 |
| Dell          | Precision M6700             | [0d8cf3bf1c](https://linux-hardware.org/?probe=0d8cf3bf1c) | Sep 21, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [44d0412dd3](https://linux-hardware.org/?probe=44d0412dd3) | Aug 27, 2021 |
| Samsung       | 600B4B/600B5B               | [200275bbd6](https://linux-hardware.org/?probe=200275bbd6) | Aug 27, 2021 |
| Dell          | Precision M6700             | [191db00b83](https://linux-hardware.org/?probe=191db00b83) | Aug 26, 2021 |
| Lenovo        | V330-15IKB 81AX             | [4b5a1af4dd](https://linux-hardware.org/?probe=4b5a1af4dd) | Aug 26, 2021 |
| Lenovo        | G500 20236                  | [73a5085a79](https://linux-hardware.org/?probe=73a5085a79) | Aug 24, 2021 |
| Dell          | Latitude 5480               | [a2110d9601](https://linux-hardware.org/?probe=a2110d9601) | Aug 24, 2021 |
| Dell          | Latitude 5480               | [64e1f3e16c](https://linux-hardware.org/?probe=64e1f3e16c) | Aug 19, 2021 |
| Lenovo        | ThinkPad T61 8895W9U        | [424c5f3e75](https://linux-hardware.org/?probe=424c5f3e75) | Aug 19, 2021 |
| Dell          | Inspiron 3521               | [c68ce33d52](https://linux-hardware.org/?probe=c68ce33d52) | Aug 11, 2021 |
| Dell          | Inspiron 3521               | [9a422a10d3](https://linux-hardware.org/?probe=9a422a10d3) | Aug 11, 2021 |
| Dell          | Inspiron 7460               | [f954aa3826](https://linux-hardware.org/?probe=f954aa3826) | Aug 10, 2021 |
| Samsung       | 600B4B/600B5B               | [0a650b495e](https://linux-hardware.org/?probe=0a650b495e) | Aug 09, 2021 |
| Lenovo        | ThinkPad T460 20FMS75800    | [1a1c3f469d](https://linux-hardware.org/?probe=1a1c3f469d) | Aug 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [5953bc46ad](https://linux-hardware.org/?probe=5953bc46ad) | Aug 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [fafaeed466](https://linux-hardware.org/?probe=fafaeed466) | Aug 06, 2021 |
| HP            | Stream Notebook PC 11       | [a612aa5d15](https://linux-hardware.org/?probe=a612aa5d15) | Jul 20, 2021 |
| Lenovo        | ThinkPad T450s 20BWA06J0... | [e4cd39ef75](https://linux-hardware.org/?probe=e4cd39ef75) | Jul 09, 2021 |
| Lenovo        | ThinkPad T450s 20BWA06J0... | [5565f4e4fe](https://linux-hardware.org/?probe=5565f4e4fe) | Jul 09, 2021 |
| Fujitsu       | LIFEBOOK E754               | [e7923c27f1](https://linux-hardware.org/?probe=e7923c27f1) | Jul 08, 2021 |
| ASUSTek       | G771JW                      | [8e6c4ddee8](https://linux-hardware.org/?probe=8e6c4ddee8) | Jun 24, 2021 |
| HP            | ZBook 17 G2                 | [3342d4d378](https://linux-hardware.org/?probe=3342d4d378) | Jun 17, 2021 |
| HP            | OMEN by HP Laptop 15-dc1... | [0c01b21401](https://linux-hardware.org/?probe=0c01b21401) | Jun 15, 2021 |
| Sony          | VPCSB15GB                   | [43a9d38ca0](https://linux-hardware.org/?probe=43a9d38ca0) | Jun 03, 2021 |
| Sony          | VGN-Z570AN                  | [13d58b8d90](https://linux-hardware.org/?probe=13d58b8d90) | May 21, 2021 |
| Sony          | VGN-Z570AN                  | [e6c7882e05](https://linux-hardware.org/?probe=e6c7882e05) | May 21, 2021 |
| MSI           | GS60 6QE                    | [93c6fd8911](https://linux-hardware.org/?probe=93c6fd8911) | May 18, 2021 |
| MSI           | GS60 6QE                    | [41fe777475](https://linux-hardware.org/?probe=41fe777475) | May 18, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [184bedf2fd](https://linux-hardware.org/?probe=184bedf2fd) | May 01, 2021 |
| HP            | Pavilion dx6500             | [091cc2c616](https://linux-hardware.org/?probe=091cc2c616) | Apr 13, 2021 |
| HP            | Pavilion dx6500             | [6ad0d5c87f](https://linux-hardware.org/?probe=6ad0d5c87f) | Apr 13, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [97a7246099](https://linux-hardware.org/?probe=97a7246099) | Mar 01, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [b1e186207c](https://linux-hardware.org/?probe=b1e186207c) | Feb 28, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| 5.3.18-59.27-default                | 8         | 17.02%  |
| 5.3.18-59.37-default                | 5         | 10.64%  |
| 5.3.18-59.19-default                | 5         | 10.64%  |
| 5.3.18-59.16-default                | 5         | 10.64%  |
| 5.3.18-57-default                   | 5         | 10.64%  |
| 5.3.18-59.5-default                 | 2         | 4.26%   |
| 5.3.18-59.34-default                | 2         | 4.26%   |
| 5.3.18-59.24-default                | 2         | 4.26%   |
| 5.3.18-59.10-default                | 2         | 4.26%   |
| 5.3.18-59.34-preempt                | 1         | 2.13%   |
| 5.3.18-59.19-preempt                | 1         | 2.13%   |
| 5.3.18-59.13-default                | 1         | 2.13%   |
| 5.3.18-57-preempt                   | 1         | 2.13%   |
| 5.3.18-56-default                   | 1         | 2.13%   |
| 5.3.18-52-default                   | 1         | 2.13%   |
| 5.3.18-46-default                   | 1         | 2.13%   |
| 5.3.18-150300.59.43-default         | 1         | 2.13%   |
| 5.16.0-rc2-lp153.2.g696d453-default | 1         | 2.13%   |
| 5.15.11-lp153.3.g730a488-default    | 1         | 2.13%   |
| 4.12.14-197.105-vanilla             | 1         | 2.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.3.18  | 42        | 93.33%  |
| 5.16.0  | 1         | 2.22%   |
| 5.15.11 | 1         | 2.22%   |
| 4.12.14 | 1         | 2.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.3     | 42        | 93.33%  |
| 5.16    | 1         | 2.22%   |
| 5.15    | 1         | 2.22%   |
| 4.12    | 1         | 2.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 45        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KDE5       | 18        | 38.3%   |
| KDE        | 8         | 17.02%  |
| GNOME      | 8         | 17.02%  |
| XFCE       | 7         | 14.89%  |
| Unknown    | 3         | 6.38%   |
| X-Cinnamon | 2         | 4.26%   |
| MATE       | 1         | 2.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 37        | 82.22%  |
| Wayland | 8         | 17.78%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 21        | 46.67%  |
| LightDM | 11        | 24.44%  |
| SDDM    | 10        | 22.22%  |
| XDM     | 2         | 4.44%   |
| GDM     | 1         | 2.22%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 15        | 33.33%  |
| de_DE   | 9         | 20%     |
| POSIX   | 4         | 8.89%   |
| fr_FR   | 3         | 6.67%   |
| ru_RU   | 2         | 4.44%   |
| pt_BR   | 2         | 4.44%   |
| es_ES   | 2         | 4.44%   |
| zh_CN   | 1         | 2.22%   |
| sv_SE   | 1         | 2.22%   |
| pt_PT   | 1         | 2.22%   |
| it_IT   | 1         | 2.22%   |
| hu_HU   | 1         | 2.22%   |
| en_GB   | 1         | 2.22%   |
| cs_CZ   | 1         | 2.22%   |
| Unknown | 1         | 2.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 26        | 57.78%  |
| EFI  | 19        | 42.22%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 32        | 71.11%  |
| Ext4  | 12        | 26.67%  |
| Xfs   | 1         | 2.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 21        | 46.67%  |
| Unknown | 20        | 44.44%  |
| MBR     | 4         | 8.89%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 44        | 97.78%  |
| Yes       | 1         | 2.22%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 28        | 62.22%  |
| Yes       | 17        | 37.78%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 12        | 26.67%  |
| Dell                | 7         | 15.56%  |
| Acer                | 7         | 15.56%  |
| Hewlett-Packard     | 6         | 13.33%  |
| MSI                 | 3         | 6.67%   |
| Sony                | 2         | 4.44%   |
| ASUSTek Computer    | 2         | 4.44%   |
| TUXEDO              | 1         | 2.22%   |
| Semp Toshiba        | 1         | 2.22%   |
| Samsung Electronics | 1         | 2.22%   |
| Medion              | 1         | 2.22%   |
| HUAWEI              | 1         | 2.22%   |
| Fujitsu             | 1         | 2.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| TUXEDO Aura 15 Gen1                         | 1         | 2.22%   |
| Sony VPCSB15GB                              | 1         | 2.22%   |
| Sony VGN-Z570AN                             | 1         | 2.22%   |
| Semp Toshiba AS 1301                        | 1         | 2.22%   |
| Samsung 600B4B/600B5B                       | 1         | 2.22%   |
| MSI GS60 6QE                                | 1         | 2.22%   |
| MSI GP63 Leopard 8RD                        | 1         | 2.22%   |
| MSI CX600                                   | 1         | 2.22%   |
| Medion E6436 MD61150                        | 1         | 2.22%   |
| Lenovo V330-15IKB 81AX                      | 1         | 2.22%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW00A7TH  | 1         | 2.22%   |
| Lenovo ThinkPad X1 Carbon 4th 20FB002UMC    | 1         | 2.22%   |
| Lenovo ThinkPad T61 8895W9U                 | 1         | 2.22%   |
| Lenovo ThinkPad T490s 20NYS1XK00            | 1         | 2.22%   |
| Lenovo ThinkPad T460 20FMS75800             | 1         | 2.22%   |
| Lenovo ThinkPad T450s 20BWA06J00            | 1         | 2.22%   |
| Lenovo ThinkPad T14 Gen 1 20UES47F00        | 1         | 2.22%   |
| Lenovo ThinkPad L15 Gen 1 20U4S88000        | 1         | 2.22%   |
| Lenovo IdeaPad 330-15IKB 81DC               | 1         | 2.22%   |
| Lenovo G500 20236                           | 1         | 2.22%   |
| Lenovo G50-45 80E3                          | 1         | 2.22%   |
| HUAWEI KLVL-WXX9                            | 1         | 2.22%   |
| HP ZBook 17 G2                              | 1         | 2.22%   |
| HP Stream Notebook PC 11                    | 1         | 2.22%   |
| HP Pavilion dx6500                          | 1         | 2.22%   |
| HP OMEN by HP Laptop 15-dc1xxx              | 1         | 2.22%   |
| HP Laptop 17-ca1xxx                         | 1         | 2.22%   |
| HP Laptop 15s-eq0xxx                        | 1         | 2.22%   |
| Fujitsu LIFEBOOK E754                       | 1         | 2.22%   |
| Dell XPS 15 9510                            | 1         | 2.22%   |
| Dell Precision M6700                        | 1         | 2.22%   |
| Dell Latitude 5480                          | 1         | 2.22%   |
| Dell Inspiron N4030                         | 1         | 2.22%   |
| Dell Inspiron 7460                          | 1         | 2.22%   |
| Dell Inspiron 3521                          | 1         | 2.22%   |
| Dell Inspiron 15 7000 Gaming                | 1         | 2.22%   |
| ASUS VivoBook 12_ASUS Laptop E203MAS_E203MA | 1         | 2.22%   |
| ASUS G771JW                                 | 1         | 2.22%   |
| Acer Nitro AN515-54                         | 1         | 2.22%   |
| Acer Nitro AN515-52                         | 1         | 2.22%   |
| Acer Aspire VN7-792G                        | 1         | 2.22%   |
| Acer Aspire E1-772G                         | 1         | 2.22%   |
| Acer Aspire E1-571                          | 1         | 2.22%   |
| Acer Aspire 5820TG                          | 1         | 2.22%   |
| Acer Aspire 5560                            | 1         | 2.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 8         | 17.78%  |
| Acer Aspire       | 5         | 11.11%  |
| Dell Inspiron     | 4         | 8.89%   |
| HP Laptop         | 2         | 4.44%   |
| Acer Nitro        | 2         | 4.44%   |
| TUXEDO Aura       | 1         | 2.22%   |
| Sony VPCSB15GB    | 1         | 2.22%   |
| Sony VGN-Z570AN   | 1         | 2.22%   |
| Semp Toshiba AS   | 1         | 2.22%   |
| Samsung 600B4B    | 1         | 2.22%   |
| MSI GS60          | 1         | 2.22%   |
| MSI GP63          | 1         | 2.22%   |
| MSI CX600         | 1         | 2.22%   |
| Medion E6436      | 1         | 2.22%   |
| Lenovo V330-15IKB | 1         | 2.22%   |
| Lenovo IdeaPad    | 1         | 2.22%   |
| Lenovo G500       | 1         | 2.22%   |
| Lenovo G50-45     | 1         | 2.22%   |
| HUAWEI KLVL-WXX9  | 1         | 2.22%   |
| HP ZBook          | 1         | 2.22%   |
| HP Stream         | 1         | 2.22%   |
| HP Pavilion       | 1         | 2.22%   |
| HP OMEN           | 1         | 2.22%   |
| Fujitsu LIFEBOOK  | 1         | 2.22%   |
| Dell XPS          | 1         | 2.22%   |
| Dell Precision    | 1         | 2.22%   |
| Dell Latitude     | 1         | 2.22%   |
| ASUS VivoBook     | 1         | 2.22%   |
| ASUS G771JW       | 1         | 2.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 5         | 11.11%  |
| 2017 | 5         | 11.11%  |
| 2012 | 5         | 11.11%  |
| 2020 | 4         | 8.89%   |
| 2018 | 4         | 8.89%   |
| 2014 | 4         | 8.89%   |
| 2016 | 3         | 6.67%   |
| 2015 | 3         | 6.67%   |
| 2021 | 2         | 4.44%   |
| 2013 | 2         | 4.44%   |
| 2011 | 2         | 4.44%   |
| 2010 | 2         | 4.44%   |
| 2007 | 2         | 4.44%   |
| 2009 | 1         | 2.22%   |
| 2008 | 1         | 2.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 45        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 37        | 82.22%  |
| Enabled  | 8         | 17.78%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 45        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 11        | 24.44%  |
| 3.01-4.0    | 9         | 20%     |
| 16.01-24.0  | 9         | 20%     |
| 8.01-16.0   | 9         | 20%     |
| 32.01-64.0  | 3         | 6.67%   |
| 1.01-2.0    | 2         | 4.44%   |
| 2.01-3.0    | 1         | 2.22%   |
| 64.01-256.0 | 1         | 2.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 15        | 32.61%  |
| 1.01-2.0  | 15        | 32.61%  |
| 4.01-8.0  | 10        | 21.74%  |
| 3.01-4.0  | 4         | 8.7%    |
| 8.01-16.0 | 1         | 2.17%   |
| 0.51-1.0  | 1         | 2.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 26        | 57.78%  |
| 2      | 19        | 42.22%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 25        | 55.56%  |
| Yes       | 20        | 44.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 88.89%  |
| No        | 5         | 11.11%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 35        | 76.09%  |
| No        | 11        | 23.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Germany     | 9         | 20%     |
| Brazil      | 6         | 13.33%  |
| France      | 4         | 8.89%   |
| USA         | 2         | 4.44%   |
| Spain       | 2         | 4.44%   |
| Russia      | 2         | 4.44%   |
| Nicaragua   | 2         | 4.44%   |
| India       | 2         | 4.44%   |
| Greece      | 2         | 4.44%   |
| Czechia     | 2         | 4.44%   |
| Thailand    | 1         | 2.22%   |
| Sweden      | 1         | 2.22%   |
| Sudan       | 1         | 2.22%   |
| Romania     | 1         | 2.22%   |
| Portugal    | 1         | 2.22%   |
| Netherlands | 1         | 2.22%   |
| Mexico      | 1         | 2.22%   |
| Italy       | 1         | 2.22%   |
| Hungary     | 1         | 2.22%   |
| China       | 1         | 2.22%   |
| Canada      | 1         | 2.22%   |
| Belgium     | 1         | 2.22%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| SГЈo Paulo   | 2         | 4.35%   |
| Prague         | 2         | 4.35%   |
| Managua        | 2         | 4.35%   |
| Vaennaesby     | 1         | 2.17%   |
| The Hague      | 1         | 2.17%   |
| Teresina       | 1         | 2.17%   |
| Sehnde         | 1         | 2.17%   |
| SÃ£o Paulo   | 1         | 2.17%   |
| Sartrouville   | 1         | 2.17%   |
| Saalfeld       | 1         | 2.17%   |
| Rockville      | 1         | 2.17%   |
| Pringy         | 1         | 2.17%   |
| Petrozavodsk   | 1         | 2.17%   |
| Palanpur       | 1         | 2.17%   |
| Nuremberg      | 1         | 2.17%   |
| Moscow         | 1         | 2.17%   |
| Monterrey      | 1         | 2.17%   |
| Moelan-sur-Mer | 1         | 2.17%   |
| Leiria         | 1         | 2.17%   |
| LeÃ³n        | 1         | 2.17%   |
| Khartoum       | 1         | 2.17%   |
| Kehl           | 1         | 2.17%   |
| Kathu          | 1         | 2.17%   |
| Isernhagen     | 1         | 2.17%   |
| Howick         | 1         | 2.17%   |
| Heraklion      | 1         | 2.17%   |
| Guangzhou      | 1         | 2.17%   |
| Gevelsberg     | 1         | 2.17%   |
| Esztergom      | 1         | 2.17%   |
| Dunkirk        | 1         | 2.17%   |
| Dahme          | 1         | 2.17%   |
| Concarneau     | 1         | 2.17%   |
| Cologne        | 1         | 2.17%   |
| ChapecÃ³     | 1         | 2.17%   |
| Cestona        | 1         | 2.17%   |
| Bucharest      | 1         | 2.17%   |
| Bremen         | 1         | 2.17%   |
| Bologna        | 1         | 2.17%   |
| Bengaluru      | 1         | 2.17%   |
| Bebedouro      | 1         | 2.17%   |
| Atlanta        | 1         | 2.17%   |
| Athens         | 1         | 2.17%   |
| Antwerp        | 1         | 2.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 13     | 17.46%  |
| WDC                 | 9         | 9      | 14.29%  |
| Seagate             | 8         | 10     | 12.7%   |
| Kingston            | 6         | 6      | 9.52%   |
| SanDisk             | 4         | 4      | 6.35%   |
| Toshiba             | 3         | 4      | 4.76%   |
| SK Hynix            | 3         | 3      | 4.76%   |
| Hitachi             | 3         | 4      | 4.76%   |
| HGST                | 3         | 3      | 4.76%   |
| Unknown             | 2         | 2      | 3.17%   |
| Silicon Motion      | 2         | 2      | 3.17%   |
| Micron Technology   | 2         | 2      | 3.17%   |
| PLEXTOR             | 1         | 2      | 1.59%   |
| Phison              | 1         | 1      | 1.59%   |
| LITEON              | 1         | 1      | 1.59%   |
| Intenso             | 1         | 1      | 1.59%   |
| Fujitsu             | 1         | 1      | 1.59%   |
| Crucial             | 1         | 1      | 1.59%   |
| China               | 1         | 1      | 1.59%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| SK Hynix HFS128G39TND-N210A 128GB SSD   | 2         | 3.17%   |
| Silicon Motion NVMe SSD Drive 512GB     | 2         | 3.17%   |
| Seagate ST1000LM035-1RK172 1TB          | 2         | 3.17%   |
| HGST HTS721010A9E630 1TB                | 2         | 3.17%   |
| WDC WDS480G2G0A-00JH30 480GB SSD        | 1         | 1.59%   |
| WDC WD800BEVS-60RST0 80GB               | 1         | 1.59%   |
| WDC WD5000LPVX-00V0TT0 500GB            | 1         | 1.59%   |
| WDC WD5000LPLX-66ZNTT1 500GB            | 1         | 1.59%   |
| WDC WD3200BEVT-22ZCT0 320GB             | 1         | 1.59%   |
| WDC WD10SPZX-60Z10T0 1TB                | 1         | 1.59%   |
| WDC WD10SPZX-24Z10 1TB                  | 1         | 1.59%   |
| WDC WD10SPZX-17Z10T0 1TB                | 1         | 1.59%   |
| WDC PC SN730 SDBPNTY-512G-1006 512GB    | 1         | 1.59%   |
| Unknown USD00  256GB                    | 1         | 1.59%   |
| Unknown DA4064  64GB                    | 1         | 1.59%   |
| Toshiba THNSNJ256G8NU 256GB SSD         | 1         | 1.59%   |
| Toshiba MQ04ABF100 1TB                  | 1         | 1.59%   |
| Toshiba MQ01ABD075 752GB                | 1         | 1.59%   |
| SK Hynix HBG4e  32GB                    | 1         | 1.59%   |
| Seagate ST9320325AS 320GB               | 1         | 1.59%   |
| Seagate ST500LT012-9WS142 500GB         | 1         | 1.59%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 1         | 1.59%   |
| Seagate ST500LM000-SSHD-8GB             | 1         | 1.59%   |
| Seagate ST2000LM003 HN-M201RAD 2TB      | 1         | 1.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 1         | 1.59%   |
| SanDisk SSD PLUS 1000GB                 | 1         | 1.59%   |
| SanDisk SDSSDH3 1T00 1TB                | 1         | 1.59%   |
| SanDisk SD9SN8W256G 256GB SSD           | 1         | 1.59%   |
| SanDisk SD8TB8U512G1001 512GB SSD       | 1         | 1.59%   |
| Samsung SSD 970 EVO 1TB                 | 1         | 1.59%   |
| Samsung SSD 860 EVO 1TB                 | 1         | 1.59%   |
| Samsung SSD 850 EVO 250GB               | 1         | 1.59%   |
| Samsung PM9A1 NVMe 1024GB               | 1         | 1.59%   |
| Samsung NVMe SSD Drive 500GB            | 1         | 1.59%   |
| Samsung NVMe SSD Drive 1TB              | 1         | 1.59%   |
| Samsung MZVLB512HAJQ-000H1 512GB        | 1         | 1.59%   |
| Samsung MZVL21T0HCLR-00BL7 1TB          | 1         | 1.59%   |
| Samsung MZNLF128HCHP-00000 128GB SSD    | 1         | 1.59%   |
| Samsung MZALQ256HAJD-000L1 256GB        | 1         | 1.59%   |
| Samsung MZ7LN256HCHP-000L7 256GB SSD    | 1         | 1.59%   |
| PLEXTOR PX-512M5Pro 512GB SSD           | 1         | 1.59%   |
| Phison 311CD0512GB                      | 1         | 1.59%   |
| Micron NVMe SSD Drive 512GB             | 1         | 1.59%   |
| Micron MTFDHBA512TDV 512GB              | 1         | 1.59%   |
| LITEON CX1-JB256-HP 256GB SSD           | 1         | 1.59%   |
| Kingston SNA-DC/U3 1TB SSD              | 1         | 1.59%   |
| Kingston SM2280S3G2480G 480GB SSD       | 1         | 1.59%   |
| Kingston SA400S37240G 240GB SSD         | 1         | 1.59%   |
| Kingston SA2000M81000G 1TB              | 1         | 1.59%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD | 1         | 1.59%   |
| Kingston RBU-SC100S37128GD 128GB SSD    | 1         | 1.59%   |
| Intenso SSD 512GB                       | 1         | 1.59%   |
| Hitachi HTS727550A9E365 500GB           | 1         | 1.59%   |
| Hitachi HTS547575A9E384 752GB           | 1         | 1.59%   |
| Hitachi HTS542525K9SA00 250GB           | 1         | 1.59%   |
| HGST HTS541010A9E680 1TB                | 1         | 1.59%   |
| Fujitsu MHW2120BH 120GB                 | 1         | 1.59%   |
| Crucial CT500MX500SSD1 500GB            | 1         | 1.59%   |
| China SSD 64GB                          | 1         | 1.59%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 10     | 33.33%  |
| WDC     | 7         | 7      | 29.17%  |
| Hitachi | 3         | 4      | 12.5%   |
| HGST    | 3         | 3      | 12.5%   |
| Toshiba | 2         | 3      | 8.33%   |
| Fujitsu | 1         | 1      | 4.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 5         | 5      | 22.73%  |
| SanDisk             | 4         | 4      | 18.18%  |
| Samsung Electronics | 4         | 4      | 18.18%  |
| SK Hynix            | 2         | 2      | 9.09%   |
| WDC                 | 1         | 1      | 4.55%   |
| Toshiba             | 1         | 1      | 4.55%   |
| PLEXTOR             | 1         | 2      | 4.55%   |
| LITEON              | 1         | 1      | 4.55%   |
| Intenso             | 1         | 1      | 4.55%   |
| Crucial             | 1         | 1      | 4.55%   |
| China               | 1         | 1      | 4.55%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 22        | 28     | 36.67%  |
| SSD  | 21        | 23     | 35%     |
| NVMe | 14        | 16     | 23.33%  |
| MMC  | 3         | 3      | 5%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 34        | 50     | 65.38%  |
| NVMe | 14        | 16     | 26.92%  |
| MMC  | 3         | 3      | 5.77%   |
| SAS  | 1         | 1      | 1.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 23        | 28     | 53.49%  |
| 0.51-1.0   | 19        | 22     | 44.19%  |
| 1.01-2.0   | 1         | 1      | 2.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 1001-2000      | 11        | 23.91%  |
| 501-1000       | 9         | 19.57%  |
| 2001-3000      | 8         | 17.39%  |
| More than 3000 | 7         | 15.22%  |
| 251-500        | 5         | 10.87%  |
| 51-100         | 4         | 8.7%    |
| 101-250        | 1         | 2.17%   |
| Unknown        | 1         | 2.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 51-100    | 10        | 20.41%  |
| 101-250   | 9         | 18.37%  |
| 251-500   | 8         | 16.33%  |
| 501-1000  | 6         | 12.24%  |
| 1001-2000 | 5         | 10.2%   |
| 21-50     | 4         | 8.16%   |
| 1-20      | 4         | 8.16%   |
| 2001-3000 | 2         | 4.08%   |
| Unknown   | 1         | 2.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-00V0TT0 500GB          | 1         | 1      | 25%     |
| SK Hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 25%     |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 25%     |
| Phison 311CD0512GB                    | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 1         | 1      | 25%     |
| SK Hynix | 1         | 1      | 25%     |
| Seagate  | 1         | 1      | 25%     |
| Phison   | 1         | 1      | 25%     |

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
| HDD  | 2         | 2      | 50%     |
| NVMe | 1         | 1      | 25%     |
| SSD  | 1         | 1      | 25%     |

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
| Detected | 24        | 40     | 48.98%  |
| Works    | 21        | 26     | 42.86%  |
| Malfunc  | 4         | 4      | 8.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 30        | 61.22%  |
| Samsung Electronics              | 6         | 12.24%  |
| AMD                              | 4         | 8.16%   |
| Silicon Motion                   | 2         | 4.08%   |
| Micron Technology                | 2         | 4.08%   |
| Silicon Integrated Systems [SiS] | 1         | 2.04%   |
| Sandisk                          | 1         | 2.04%   |
| Phison Electronics               | 1         | 2.04%   |
| Lite-On Technology               | 1         | 2.04%   |
| Kingston Technology Company      | 1         | 2.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 11.54%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 7.69%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 5.77%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 5.77%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 5.77%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 3         | 5.77%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 2         | 3.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 3.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 3.85%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 3.85%   |
| Micron Non-Volatile memory controller                                          | 2         | 3.85%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 3.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 3.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 3.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 3.85%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 1         | 1.92%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 1         | 1.92%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 1.92%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 1.92%   |
| Lite-On SATA controller                                                        | 1         | 1.92%   |
| Kingston Company A2000 NVMe SSD                                                | 1         | 1.92%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.92%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 1.92%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 1.92%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 1.92%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 1.92%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 31        | 62%     |
| NVMe | 13        | 26%     |
| RAID | 3         | 6%      |
| IDE  | 3         | 6%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 37        | 82.22%  |
| AMD    | 8         | 17.78%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 6.67%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 4.44%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 2.22%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 2.22%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 2.22%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 2.22%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 2.22%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 2.22%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 1         | 2.22%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 2.22%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 2.22%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 2.22%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 2.22%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 2.22%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 1         | 2.22%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 2.22%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 1         | 2.22%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 2.22%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 1         | 2.22%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 2.22%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 2.22%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 2.22%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 2.22%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 2.22%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 1         | 2.22%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 1         | 2.22%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 1         | 2.22%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 1         | 2.22%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz          | 1         | 2.22%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 1         | 2.22%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 1         | 2.22%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 1         | 2.22%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 1         | 2.22%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 2.22%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 1         | 2.22%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 1         | 2.22%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 2.22%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 2.22%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 1         | 2.22%   |
| AMD C-50 Processor                            | 1         | 2.22%   |
| AMD A6-6310 APU with AMD Radeon R4 Graphics   | 1         | 2.22%   |
| AMD A6-3420M APU with Radeon HD Graphics      | 1         | 2.22%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 15        | 33.33%  |
| Intel Core i7           | 11        | 24.44%  |
| Intel Core i3           | 3         | 6.67%   |
| Intel Core 2 Duo        | 3         | 6.67%   |
| Other                   | 2         | 4.44%   |
| Intel Celeron           | 2         | 4.44%   |
| AMD Ryzen 7             | 2         | 4.44%   |
| AMD A6                  | 2         | 4.44%   |
| Intel Pentium Dual-Core | 1         | 2.22%   |
| AMD Ryzen 7 PRO         | 1         | 2.22%   |
| AMD Ryzen 5             | 1         | 2.22%   |
| AMD Ryzen 3             | 1         | 2.22%   |
| AMD C-50                | 1         | 2.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 24        | 53.33%  |
| 4      | 14        | 31.11%  |
| 8      | 4         | 8.89%   |
| 6      | 3         | 6.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 45        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 32        | 71.11%  |
| 1      | 13        | 28.89%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 45        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 17        | 36.96%  |
| 0x906ea    | 3         | 6.52%   |
| 0x806e9    | 3         | 6.52%   |
| 0x08600106 | 3         | 6.52%   |
| 0x6fd      | 2         | 4.35%   |
| 0x506e3    | 2         | 4.35%   |
| 0x406e3    | 2         | 4.35%   |
| 0x806ec    | 1         | 2.17%   |
| 0x806d1    | 1         | 2.17%   |
| 0x806c1    | 1         | 2.17%   |
| 0x706a1    | 1         | 2.17%   |
| 0x306d4    | 1         | 2.17%   |
| 0x306c3    | 1         | 2.17%   |
| 0x306a9    | 1         | 2.17%   |
| 0x30678    | 1         | 2.17%   |
| 0x206a7    | 1         | 2.17%   |
| 0x20655    | 1         | 2.17%   |
| 0x1067a    | 1         | 2.17%   |
| 0x10676    | 1         | 2.17%   |
| 0x08108109 | 1         | 2.17%   |
| 0x07030105 | 1         | 2.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 12        | 26.67%  |
| Skylake       | 4         | 8.89%   |
| IvyBridge     | 4         | 8.89%   |
| Haswell       | 4         | 8.89%   |
| Zen 2         | 3         | 6.67%   |
| Zen+          | 2         | 4.44%   |
| Westmere      | 2         | 4.44%   |
| SandyBridge   | 2         | 4.44%   |
| Penryn        | 2         | 4.44%   |
| Core          | 2         | 4.44%   |
| TigerLake     | 1         | 2.22%   |
| Silvermont    | 1         | 2.22%   |
| Puma          | 1         | 2.22%   |
| K10 Llano     | 1         | 2.22%   |
| Icelake       | 1         | 2.22%   |
| Goldmont plus | 1         | 2.22%   |
| Broadwell     | 1         | 2.22%   |
| Bobcat        | 1         | 2.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 36        | 56.25%  |
| Nvidia | 14        | 21.88%  |
| AMD    | 14        | 21.88%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                 | 4         | 6.06%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 4         | 6.06%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 4         | 6.06%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 4         | 6.06%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 3         | 4.55%   |
| AMD Renoir                                                                            | 3         | 4.55%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 2         | 3.03%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 2         | 3.03%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 2         | 3.03%   |
| Intel HD Graphics 530                                                                 | 2         | 3.03%   |
| Intel Core Processor Integrated Graphics Controller                                   | 2         | 3.03%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 2         | 3.03%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 2         | 3.03%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 1         | 1.52%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                           | 1         | 1.52%   |
| Nvidia GM204M [GeForce GTX 980M]                                                      | 1         | 1.52%   |
| Nvidia GM204M [GeForce GTX 970M]                                                      | 1         | 1.52%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 1         | 1.52%   |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 1         | 1.52%   |
| Nvidia GM107M [GeForce GTX 950M]                                                      | 1         | 1.52%   |
| Nvidia GK104GLM [Quadro K3000M]                                                       | 1         | 1.52%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 1         | 1.52%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 1         | 1.52%   |
| Nvidia G98M [GeForce 9300M GS]                                                        | 1         | 1.52%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 1         | 1.52%   |
| Intel UHD Graphics 620                                                                | 1         | 1.52%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 1         | 1.52%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 1         | 1.52%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 1         | 1.52%   |
| Intel HD Graphics 630                                                                 | 1         | 1.52%   |
| Intel HD Graphics 5500                                                                | 1         | 1.52%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 1         | 1.52%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 1         | 1.52%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 1         | 1.52%   |
| AMD Wrestler [Radeon HD 6250]                                                         | 1         | 1.52%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 1.52%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                             | 1         | 1.52%   |
| AMD Sun PRO [Radeon HD 8570A/8570M]                                                   | 1         | 1.52%   |
| AMD Sumo [Radeon HD 6520G]                                                            | 1         | 1.52%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                            | 1         | 1.52%   |
| AMD RV710/M92 [Mobility Radeon HD 4330/4350/4550]                                     | 1         | 1.52%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                   | 1         | 1.52%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                              | 1         | 1.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 18        | 40%     |
| Intel + Nvidia | 13        | 28.89%  |
| 1 x AMD        | 9         | 20%     |
| Intel + AMD    | 5         | 11.11%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 40        | 88.89%  |
| Proprietary | 5         | 11.11%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 32        | 71.11%  |
| 0.01-0.5   | 6         | 13.33%  |
| 3.01-4.0   | 3         | 6.67%   |
| 1.01-2.0   | 2         | 4.44%   |
| 7.01-8.0   | 1         | 2.22%   |
| 0.51-1.0   | 1         | 2.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 13        | 24.07%  |
| Chimei Innolux      | 11        | 20.37%  |
| AU Optronics        | 9         | 16.67%  |
| Samsung Electronics | 4         | 7.41%   |
| Goldstar            | 4         | 7.41%   |
| Lenovo              | 2         | 3.7%    |
| Hewlett-Packard     | 2         | 3.7%    |
| Sony                | 1         | 1.85%   |
| Sharp               | 1         | 1.85%   |
| LG Philips          | 1         | 1.85%   |
| InfoVision          | 1         | 1.85%   |
| Iiyama              | 1         | 1.85%   |
| Dell                | 1         | 1.85%   |
| CSO                 | 1         | 1.85%   |
| CPT                 | 1         | 1.85%   |
| BOE                 | 1         | 1.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 2         | 3.64%   |
| Hewlett-Packard LV1911 HWP3005 1366x768 410x230mm 18.5-inch             | 2         | 3.64%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                 | 2         | 3.64%   |
| Sony LCD SNY06FA 1600x900 291x164mm 13.2-inch                           | 1         | 1.82%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                 | 1         | 1.82%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch       | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SEC3449 1366x768 309x174mm 14.0-inch    | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch    | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SDC424B 3840x2160 344x194mm 15.5-inch   | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1872x1053mm 84.6-inch | 1         | 1.82%   |
| LG Philips LCD Monitor LPLDB00 1280x800 331x207mm 15.4-inch             | 1         | 1.82%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch            | 1         | 1.82%   |
| LG Display LCD Monitor LGD05D8 1920x1080 344x194mm 15.5-inch            | 1         | 1.82%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch            | 1         | 1.82%   |
| LG Display LCD Monitor LGD059E 1920x1080 382x215mm 17.3-inch            | 1         | 1.82%   |
| LG Display LCD Monitor LGD053C 1920x1080 309x174mm 14.0-inch            | 1         | 1.82%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch            | 1         | 1.82%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch            | 1         | 1.82%   |
| LG Display LCD Monitor LGD04A9 1920x1080 309x174mm 14.0-inch            | 1         | 1.82%   |
| LG Display LCD Monitor LGD046C 1920x1080 382x215mm 17.3-inch            | 1         | 1.82%   |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch            | 1         | 1.82%   |
| LG Display LCD Monitor LGD02DA 1920x1080 380x220mm 17.3-inch            | 1         | 1.82%   |
| Lenovo LEN P27q-10 LEN61A8 2560x1440 597x336mm 27.0-inch                | 1         | 1.82%   |
| Lenovo LCD Monitor LEN4020 1024x768 286x214mm 14.1-inch                 | 1         | 1.82%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch             | 1         | 1.82%   |
| Iiyama PL2492H IVM612F 1920x1080 530x300mm 24.0-inch                    | 1         | 1.82%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                  | 1         | 1.82%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch                | 1         | 1.82%   |
| Dell U2410 DELF017 1920x1200 518x324mm 24.1-inch                        | 1         | 1.82%   |
| CSO LCD Monitor CSO1404 1920x1200 302x189mm 14.0-inch                   | 1         | 1.82%   |
| CPT LCD Monitor CPT17D8 1366x768 293x165mm 13.2-inch                    | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch        | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15F6 1920x1080 344x193mm 15.5-inch        | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 344x193mm 15.5-inch        | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch         | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch         | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch        | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch         | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN14F5 1920x1080 309x173mm 13.9-inch        | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch         | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch         | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN1136 1366x768 256x144mm 11.6-inch         | 1         | 1.82%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                   | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch          | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch          | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch           | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO225C 1366x768 256x144mm 11.6-inch           | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch          | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch          | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch           | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch           | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch          | 1         | 1.82%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 23        | 46%     |
| 1366x768 (WXGA)   | 13        | 26%     |
| 1920x1200 (WUXGA) | 3         | 6%      |
| 3840x2160 (4K)    | 2         | 4%      |
| 2560x1080         | 2         | 4%      |
| 1600x900 (HD+)    | 2         | 4%      |
| 3840x2400         | 1         | 2%      |
| 2560x1440 (QHD)   | 1         | 2%      |
| 2160x1440         | 1         | 2%      |
| 1280x800 (WXGA)   | 1         | 2%      |
| 1024x768 (XGA)    | 1         | 2%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 22        | 40%     |
| 14     | 9         | 16.36%  |
| 17     | 7         | 12.73%  |
| 13     | 4         | 7.27%   |
| 34     | 2         | 3.64%   |
| 27     | 2         | 3.64%   |
| 18     | 2         | 3.64%   |
| 11     | 2         | 3.64%   |
| 84     | 1         | 1.82%   |
| 26     | 1         | 1.82%   |
| 24     | 1         | 1.82%   |
| 23     | 1         | 1.82%   |
| 21     | 1         | 1.82%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 31        | 56.36%  |
| 351-400     | 8         | 14.55%  |
| 201-300     | 5         | 9.09%   |
| 501-600     | 4         | 7.27%   |
| 401-500     | 3         | 5.45%   |
| 701-800     | 2         | 3.64%   |
| 601-700     | 1         | 1.82%   |
| 1501-2000   | 1         | 1.82%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 40        | 83.33%  |
| 16/10 | 4         | 8.33%   |
| 21/9  | 2         | 4.17%   |
| 4/3   | 1         | 2.08%   |
| 3/2   | 1         | 2.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 22        | 40%     |
| 81-90          | 11        | 20%     |
| 121-130        | 7         | 12.73%  |
| 301-350        | 3         | 5.45%   |
| 201-250        | 3         | 5.45%   |
| 51-60          | 2         | 3.64%   |
| 351-500        | 2         | 3.64%   |
| 141-150        | 2         | 3.64%   |
| More than 1000 | 1         | 1.82%   |
| 71-80          | 1         | 1.82%   |
| 91-100         | 1         | 1.82%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 24        | 44.44%  |
| 101-120       | 15        | 27.78%  |
| 51-100        | 11        | 20.37%  |
| More than 240 | 2         | 3.7%    |
| 161-240       | 2         | 3.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 35        | 77.78%  |
| 2     | 10        | 22.22%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 26        | 36.11%  |
| Realtek Semiconductor            | 22        | 30.56%  |
| Qualcomm Atheros                 | 11        | 15.28%  |
| Broadcom                         | 5         | 6.94%   |
| Broadcom Limited                 | 2         | 2.78%   |
| Silicon Integrated Systems [SiS] | 1         | 1.39%   |
| Samsung Electronics              | 1         | 1.39%   |
| Ralink                           | 1         | 1.39%   |
| Manta                            | 1         | 1.39%   |
| Lenovo                           | 1         | 1.39%   |
| ASIX Electronics                 | 1         | 1.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 17.98%  |
| Intel Wi-Fi 6 AX200                                               | 4         | 4.49%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 2.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 2.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 2.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 2.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 2.25%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 2.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 2.25%   |
| Intel Wireless 8265 / 8275                                        | 2         | 2.25%   |
| Intel Wireless 8260                                               | 2         | 2.25%   |
| Intel Wireless 7260                                               | 2         | 2.25%   |
| Intel Wireless 3165                                               | 2         | 2.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 2.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.25%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 2.25%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.12%   |
| Samsung Kiera                                                     | 1         | 1.12%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.12%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 1.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.12%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1         | 1.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 1.12%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.12%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 1.12%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.12%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 1.12%   |
| Manta MM812                                                       | 1         | 1.12%   |
| Lenovo OneLink+ Giga                                              | 1         | 1.12%   |
| Intel Wireless 7265                                               | 1         | 1.12%   |
| Intel WiFi Link 5100                                              | 1         | 1.12%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.12%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 1.12%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 1         | 1.12%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 1.12%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 1         | 1.12%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.12%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.12%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.12%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.12%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.12%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.12%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.12%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.12%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 1         | 1.12%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                     | 1         | 1.12%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 1.12%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.12%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.12%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.12%   |
| Broadcom Limited NetLink BCM57785 Gigabit Ethernet PCIe           | 1         | 1.12%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 1.12%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 1         | 1.12%   |
| Broadcom BCM43227 802.11b/g/n                                     | 1         | 1.12%   |
| Broadcom BCM43225 802.11b/g/n                                     | 1         | 1.12%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.12%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 24        | 53.33%  |
| Realtek Semiconductor | 8         | 17.78%  |
| Qualcomm Atheros      | 7         | 15.56%  |
| Broadcom              | 5         | 11.11%  |
| Ralink                | 1         | 2.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 4         | 8.89%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 2         | 4.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 2         | 4.44%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 2         | 4.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 2         | 4.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 2         | 4.44%   |
| Intel Wireless 8265 / 8275                                    | 2         | 4.44%   |
| Intel Wireless 8260                                           | 2         | 4.44%   |
| Intel Wireless 7260                                           | 2         | 4.44%   |
| Intel Wireless 3165                                           | 2         | 4.44%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 2         | 4.44%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 2         | 4.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 1         | 2.22%   |
| Realtek RTL8191SEvB Wireless LAN Controller                   | 1         | 2.22%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                     | 1         | 2.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 1         | 2.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 1         | 2.22%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 1         | 2.22%   |
| Intel Wireless 7265                                           | 1         | 2.22%   |
| Intel WiFi Link 5100                                          | 1         | 2.22%   |
| Intel Wi-Fi 6 AX201                                           | 1         | 2.22%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 1         | 2.22%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection | 1         | 2.22%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection         | 1         | 2.22%   |
| Intel Gemini Lake PCH CNVi WiFi                               | 1         | 2.22%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                  | 1         | 2.22%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                 | 1         | 2.22%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 1         | 2.22%   |
| Broadcom BCM43228 802.11a/b/g/n                               | 1         | 2.22%   |
| Broadcom BCM43227 802.11b/g/n                                 | 1         | 2.22%   |
| Broadcom BCM43225 802.11b/g/n                                 | 1         | 2.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 18        | 43.9%   |
| Intel                            | 12        | 29.27%  |
| Qualcomm Atheros                 | 5         | 12.2%   |
| Broadcom Limited                 | 2         | 4.88%   |
| Silicon Integrated Systems [SiS] | 1         | 2.44%   |
| Lenovo                           | 1         | 2.44%   |
| Broadcom                         | 1         | 2.44%   |
| ASIX Electronics                 | 1         | 2.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 38.1%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 4.76%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 4.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 4.76%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 2.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.38%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 2.38%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 2.38%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 2.38%   |
| Lenovo OneLink+ Giga                                              | 1         | 2.38%   |
| Intel Ethernet Connection I219-V                                  | 1         | 2.38%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.38%   |
| Intel Ethernet Connection I217-V                                  | 1         | 2.38%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.38%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 2.38%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.38%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2.38%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 2.38%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.38%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 2.38%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 2.38%   |
| Broadcom Limited NetLink BCM57785 Gigabit Ethernet PCIe           | 1         | 2.38%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 2.38%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 2.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 45        | 51.72%  |
| Ethernet | 40        | 45.98%  |
| Modem    | 1         | 1.15%   |
| Unknown  | 1         | 1.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 42        | 54.55%  |
| Ethernet | 34        | 44.16%  |
| Modem    | 1         | 1.3%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 38        | 84.44%  |
| 1     | 6         | 13.33%  |
| 3     | 1         | 2.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 32        | 71.11%  |
| Yes  | 13        | 28.89%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 14        | 38.89%  |
| Realtek Semiconductor           | 6         | 16.67%  |
| Qualcomm Atheros Communications | 3         | 8.33%   |
| Lite-On Technology              | 2         | 5.56%   |
| IMC Networks                    | 2         | 5.56%   |
| Foxconn / Hon Hai               | 2         | 5.56%   |
| Broadcom                        | 2         | 5.56%   |
| Realtek                         | 1         | 2.78%   |
| Qualcomm Atheros                | 1         | 2.78%   |
| Dell                            | 1         | 2.78%   |
| Cambridge Silicon Radio         | 1         | 2.78%   |
| Alps Electric                   | 1         | 2.78%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 5         | 13.89%  |
| Realtek Bluetooth Radio                                                             | 4         | 11.11%  |
| Intel Bluetooth Device                                                              | 4         | 11.11%  |
| Intel AX200 Bluetooth                                                               | 3         | 8.33%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 5.56%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 2         | 5.56%   |
| Intel AX201 Bluetooth                                                               | 2         | 5.56%   |
| IMC Networks Bluetooth Device                                                       | 2         | 5.56%   |
| Realtek Bluetooth Radio                                                             | 1         | 2.78%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 2.78%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 2.78%   |
| Lite-On Bluetooth Device                                                            | 1         | 2.78%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 2.78%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 2.78%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 1         | 2.78%   |
| Dell BCM20702A0                                                                     | 1         | 2.78%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 2.78%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 1         | 2.78%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 2.78%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 2.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 36        | 64.29%  |
| AMD                              | 9         | 16.07%  |
| Nvidia                           | 4         | 7.14%   |
| Logitech                         | 2         | 3.57%   |
| Lenovo                           | 2         | 3.57%   |
| Silicon Integrated Systems [SiS] | 1         | 1.79%   |
| JMTek                            | 1         | 1.79%   |
| GN Netcom                        | 1         | 1.79%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 7         | 10.45%  |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 5.97%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 5.97%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 5.97%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 5.97%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 4.48%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 4.48%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 2.99%   |
| Logitech Headset H390                                                      | 2         | 2.99%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 2.99%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 2.99%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 2.99%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 2.99%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.99%   |
| AMD FCH Azalia Controller                                                  | 2         | 2.99%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1         | 1.49%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.49%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 1.49%   |
| Lenovo ThinkPad Thunderbolt 4 Dock USB Audio                               | 1         | 1.49%   |
| Lenovo ThinkPad OneLink Plus Dock Audio                                    | 1         | 1.49%   |
| JMTek audio controller                                                     | 1         | 1.49%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 1.49%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 1.49%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.49%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.49%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.49%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.49%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.49%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 1.49%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 1.49%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.49%   |
| GN Netcom Jabra UC VOICE 150a MS                                           | 1         | 1.49%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 1.49%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.49%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1         | 1.49%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.49%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]        | 1         | 1.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 11        | 33.33%  |
| SK Hynix            | 8         | 24.24%  |
| Unknown             | 4         | 12.12%  |
| Micron Technology   | 2         | 6.06%   |
| Kingston            | 2         | 6.06%   |
| Smart               | 1         | 3.03%   |
| Ramaxel Technology  | 1         | 3.03%   |
| GOODRAM             | 1         | 3.03%   |
| Crucial             | 1         | 3.03%   |
| Corsair             | 1         | 3.03%   |
| A-DATA Technology   | 1         | 3.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                     | 1         | 2.7%    |
| Unknown RAM Module 4096MB SODIMM DDR3                          | 1         | 2.7%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1         | 2.7%    |
| Unknown RAM Module 2048MB SODIMM 1067MT/s                      | 1         | 2.7%    |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                     | 1         | 2.7%    |
| Unknown RAM Module 1024MB SODIMM 1067MT/s                      | 1         | 2.7%    |
| Smart RAM SH564568FH8NWPHSFG 2048MB SODIMM DDR3 1333MT/s       | 1         | 2.7%    |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                   | 1         | 2.7%    |
| SK Hynix RAM HYMP125S64CP8-S6 2048MB SODIMM SDRAM              | 1         | 2.7%    |
| SK Hynix RAM HMT425S6AFR6A-PB 2048MB SODIMM DDR3 1600MT/s      | 1         | 2.7%    |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s      | 1         | 2.7%    |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s        | 1         | 2.7%    |
| SK Hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s         | 1         | 2.7%    |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s         | 1         | 2.7%    |
| SK Hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s         | 1         | 2.7%    |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s         | 1         | 2.7%    |
| Samsung RAM M471B5673EH1-CH9 2GB SODIMM DDR3 1334MT/s          | 1         | 2.7%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s          | 1         | 2.7%    |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s       | 1         | 2.7%    |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s       | 1         | 2.7%    |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s         | 1         | 2.7%    |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s         | 1         | 2.7%    |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s         | 1         | 2.7%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 2.7%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s    | 1         | 2.7%    |
| Samsung RAM K4F6E3S4HM-MGCJ 4GB SODIMM LPDDR4 3733MT/s         | 1         | 2.7%    |
| Samsung RAM K4E6E304EE-EGCF 4GB SODIMM LPDDR3 1867MT/s         | 1         | 2.7%    |
| Samsung RAM K4E6E304EE-EGCF 4GB Chip LPDDR3 1867MT/s           | 1         | 2.7%    |
| Ramaxel RAM RMT3170ME68F9F1600 4096MB SODIMM DDR3 1600MT/s     | 1         | 2.7%    |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s           | 1         | 2.7%    |
| Micron RAM 53E1G32D2NP-046 2048MB Row Of Chips LPDDR4 4267MT/s | 1         | 2.7%    |
| Kingston RAM MSI26D4S9S8ME-8 8192MB SODIMM DDR4 2667MT/s       | 1         | 2.7%    |
| Kingston RAM ACR16D3LS1KFG/8G 8GB SODIMM DDR3 1600MT/s         | 1         | 2.7%    |
| GOODRAM RAM IR2400S464L15S/8G 8GB SODIMM DDR4 2133MT/s         | 1         | 2.7%    |
| Crucial RAM BLS8G4S26BFSDK.8FD 8GB SODIMM DDR4 2667MT/s        | 1         | 2.7%    |
| Corsair RAM CMSX8GX4M1A2400C16 8GB SODIMM DDR4 2400MT/s        | 1         | 2.7%    |
| A-DATA RAM Module 8192MB SODIMM DDR4 2133MT/s                  | 1         | 2.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 14        | 46.67%  |
| DDR3    | 8         | 26.67%  |
| LPDDR4  | 3         | 10%     |
| DDR2    | 2         | 6.67%   |
| SDRAM   | 1         | 3.33%   |
| LPDDR3  | 1         | 3.33%   |
| Unknown | 1         | 3.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 27        | 90%     |
| Row Of Chips | 2         | 6.67%   |
| Chip         | 1         | 3.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 12        | 34.29%  |
| 4096  | 11        | 31.43%  |
| 2048  | 6         | 17.14%  |
| 16384 | 3         | 8.57%   |
| 1024  | 2         | 5.71%   |
| 32768 | 1         | 2.86%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 7         | 21.88%  |
| 1600    | 6         | 18.75%  |
| 3200    | 5         | 15.63%  |
| 2133    | 3         | 9.38%   |
| 667     | 2         | 6.25%   |
| 4267    | 1         | 3.13%   |
| 3733    | 1         | 3.13%   |
| 2400    | 1         | 3.13%   |
| 2048    | 1         | 3.13%   |
| 1867    | 1         | 3.13%   |
| 1334    | 1         | 3.13%   |
| 1333    | 1         | 3.13%   |
| 1067    | 1         | 3.13%   |
| Unknown | 1         | 3.13%   |

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
| Chicony Electronics                    | 8         | 19.51%  |
| Acer                                   | 6         | 14.63%  |
| Sunplus Innovation Technology          | 4         | 9.76%   |
| Realtek Semiconductor                  | 4         | 9.76%   |
| Quanta                                 | 4         | 9.76%   |
| Microdia                               | 3         | 7.32%   |
| IMC Networks                           | 3         | 7.32%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 7.32%   |
| Syntek                                 | 1         | 2.44%   |
| Silicon Motion                         | 1         | 2.44%   |
| Ricoh                                  | 1         | 2.44%   |
| Luxvisions Innotech Limited            | 1         | 2.44%   |
| Lite-On Technology                     | 1         | 2.44%   |
| ALi                                    | 1         | 2.44%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                | 4         | 9.52%   |
| Sunplus HD WebCam                                                        | 2         | 4.76%   |
| Microdia Integrated_Webcam_HD                                            | 2         | 4.76%   |
| Acer BisonCam, NB Pro                                                    | 2         | 4.76%   |
| Syntek Lenovo EasyCamera                                                 | 1         | 2.38%   |
| Sunplus Integrated_Webcam_HD                                             | 1         | 2.38%   |
| Sunplus 1.3M HD WebCam                                                   | 1         | 2.38%   |
| Silicon Motion WebCam SC-13HDN10939N                                     | 1         | 2.38%   |
| Ricoh Sony Vaio Integrated Webcam                                        | 1         | 2.38%   |
| Realtek USB2.0 HD UVC WebCam                                             | 1         | 2.38%   |
| Realtek USB Camera                                                       | 1         | 2.38%   |
| Realtek Lenovo EasyCamera                                                | 1         | 2.38%   |
| Realtek Integrated_Webcam_HD                                             | 1         | 2.38%   |
| Realtek Integrated Webcam HD                                             | 1         | 2.38%   |
| Quanta HP Wide Vision HD Camera                                          | 1         | 2.38%   |
| Quanta HP TrueVision HD Camera                                           | 1         | 2.38%   |
| Quanta HD Webcam                                                         | 1         | 2.38%   |
| Quanta HD User Facing                                                    | 1         | 2.38%   |
| Microdia Laptop_Integrated_Webcam_0.3M                                   | 1         | 2.38%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                      | 1         | 2.38%   |
| Lite-On Integrated Camera                                                | 1         | 2.38%   |
| IMC Networks USB2.0 VGA UVC WebCam                                       | 1         | 2.38%   |
| IMC Networks USB2.0 UVC HD Webcam                                        | 1         | 2.38%   |
| IMC Networks Integrated Camera                                           | 1         | 2.38%   |
| Chicony VGA 24fps UVC Webcam                                             | 1         | 2.38%   |
| Chicony USB2.0 Camera                                                    | 1         | 2.38%   |
| Chicony HD WebCam                                                        | 1         | 2.38%   |
| Chicony EasyCamera                                                       | 1         | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                            | 1         | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 1         | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                         | 1         | 2.38%   |
| ALi Gateway Webcam                                                       | 1         | 2.38%   |
| Acer ThinkPad P50 Integrated Camera                                      | 1         | 2.38%   |
| Acer Integrated Camera                                                   | 1         | 2.38%   |
| Acer HD Webcam                                                           | 1         | 2.38%   |
| Acer BisonCam,NB Pro                                                     | 1         | 2.38%   |

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
| 0     | 28        | 60.87%  |
| 1     | 14        | 30.43%  |
| 2     | 4         | 8.7%    |

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

