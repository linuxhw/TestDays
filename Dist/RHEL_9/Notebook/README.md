RHEL 9 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for RHEL 9.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 58

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Precision 7540              | [4703617413](https://linux-hardware.org/?probe=4703617413) | May 07, 2024 |
| Dell          | Precision 7540              | [37638500df](https://linux-hardware.org/?probe=37638500df) | May 07, 2024 |
| MSI           | Modern 15 A5M               | [e591b9e544](https://linux-hardware.org/?probe=e591b9e544) | Feb 04, 2024 |
| Dell          | Inspiron N5040              | [7cd09c7dde](https://linux-hardware.org/?probe=7cd09c7dde) | Jan 25, 2024 |
| LG Electro... | 15Z95P-GRLGL                | [ce6c983048](https://linux-hardware.org/?probe=ce6c983048) | Jan 24, 2024 |
| LG Electro... | 15Z95P-GRLGL                | [9dcc8bbc45](https://linux-hardware.org/?probe=9dcc8bbc45) | Jan 24, 2024 |
| Dell          | Precision M4800             | [dccdba8512](https://linux-hardware.org/?probe=dccdba8512) | Jan 21, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [d4e6e0ae3e](https://linux-hardware.org/?probe=d4e6e0ae3e) | Jan 19, 2024 |
| MSI           | Katana GF76 12UC            | [73c3208c03](https://linux-hardware.org/?probe=73c3208c03) | Jan 10, 2024 |
| MSI           | Katana GF76 12UC            | [15db2ea112](https://linux-hardware.org/?probe=15db2ea112) | Jan 10, 2024 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [2bb251ffbb](https://linux-hardware.org/?probe=2bb251ffbb) | Jan 09, 2024 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [1abf742848](https://linux-hardware.org/?probe=1abf742848) | Jan 09, 2024 |
| Dell          | Precision 3480              | [e81f3e856b](https://linux-hardware.org/?probe=e81f3e856b) | Jan 03, 2024 |
| Dell          | Precision 7530              | [e75b16ca5e](https://linux-hardware.org/?probe=e75b16ca5e) | Dec 03, 2023 |
| Lenovo        | ThinkPad L480 20LS0015UK    | [5f786955fc](https://linux-hardware.org/?probe=5f786955fc) | Nov 26, 2023 |
| Lenovo        | IdeaPad 330S-14IKB U 81F... | [0b06f82d9d](https://linux-hardware.org/?probe=0b06f82d9d) | Nov 19, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [1c3bf8f6ef](https://linux-hardware.org/?probe=1c3bf8f6ef) | Oct 19, 2023 |
| System76      | Galago Pro                  | [fbdb665814](https://linux-hardware.org/?probe=fbdb665814) | Oct 03, 2023 |
| Dell          | Inspiron N5010              | [fe6b9d4c65](https://linux-hardware.org/?probe=fe6b9d4c65) | Oct 01, 2023 |
| Dell          | G16 7620                    | [cd30e51d53](https://linux-hardware.org/?probe=cd30e51d53) | Sep 27, 2023 |
| Dell          | Precision 7720              | [8cae4c9a31](https://linux-hardware.org/?probe=8cae4c9a31) | Sep 25, 2023 |
| Lenovo        | ThinkPad T490 20N3S77601    | [b659e310c9](https://linux-hardware.org/?probe=b659e310c9) | Sep 02, 2023 |
| MSI           | Katana GF66 12UC            | [6651fbd434](https://linux-hardware.org/?probe=6651fbd434) | Aug 22, 2023 |
| HP            | EliteBook 2570p             | [68734d9dfa](https://linux-hardware.org/?probe=68734d9dfa) | Aug 04, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [49ecdacd71](https://linux-hardware.org/?probe=49ecdacd71) | May 14, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | [6e086ec096](https://linux-hardware.org/?probe=6e086ec096) | May 07, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [5938e62d47](https://linux-hardware.org/?probe=5938e62d47) | Apr 17, 2023 |
| Dell          | Precision 7510              | [f68123c20a](https://linux-hardware.org/?probe=f68123c20a) | Apr 13, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | [de656b2182](https://linux-hardware.org/?probe=de656b2182) | Apr 06, 2023 |
| HP            | ProBook 640 G2              | [9439371137](https://linux-hardware.org/?probe=9439371137) | Mar 18, 2023 |
| HP            | ProBook 640 G2              | [c968526666](https://linux-hardware.org/?probe=c968526666) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [bc39bd2ce5](https://linux-hardware.org/?probe=bc39bd2ce5) | Mar 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C2S... | [6772403b62](https://linux-hardware.org/?probe=6772403b62) | Feb 20, 2023 |
| Dell          | Precision 7560              | [7ed10eebe9](https://linux-hardware.org/?probe=7ed10eebe9) | Feb 16, 2023 |
| MSI           | GP75 Leopard 9SD            | [1f2a5b1def](https://linux-hardware.org/?probe=1f2a5b1def) | Feb 11, 2023 |
| Dell          | Latitude 9420               | [3fd325486b](https://linux-hardware.org/?probe=3fd325486b) | Jan 18, 2023 |
| Dell          | Latitude 3410               | [0a4720ef85](https://linux-hardware.org/?probe=0a4720ef85) | Jan 02, 2023 |
| MSI           | GE72VR 7RF                  | [f5384e68dd](https://linux-hardware.org/?probe=f5384e68dd) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | [7c17c479b7](https://linux-hardware.org/?probe=7c17c479b7) | Dec 03, 2022 |
| HP            | Laptop 14s-dk0xxx           | [c1d2a02024](https://linux-hardware.org/?probe=c1d2a02024) | Nov 30, 2022 |
| Dell          | Latitude E7450              | [1fba71c904](https://linux-hardware.org/?probe=1fba71c904) | Nov 15, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [00e77b8815](https://linux-hardware.org/?probe=00e77b8815) | Oct 26, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [94d1c333ac](https://linux-hardware.org/?probe=94d1c333ac) | Oct 26, 2022 |
| ASUSTek       | Z450LA                      | [ba00eb6516](https://linux-hardware.org/?probe=ba00eb6516) | Oct 18, 2022 |
| ASUSTek       | Z450LA                      | [6042d84470](https://linux-hardware.org/?probe=6042d84470) | Oct 17, 2022 |
| HP            | 340S G7                     | [7baf4edd11](https://linux-hardware.org/?probe=7baf4edd11) | Oct 09, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | [c1457e4e02](https://linux-hardware.org/?probe=c1457e4e02) | Sep 21, 2022 |
| Dell          | Precision 7510              | [cd8482ea72](https://linux-hardware.org/?probe=cd8482ea72) | Aug 08, 2022 |
| Dell          | Inspiron 5559               | [aaaaef108a](https://linux-hardware.org/?probe=aaaaef108a) | Jul 03, 2022 |
| Lenovo        | ThinkPad E14 20RA001MMZ     | [4bf795762d](https://linux-hardware.org/?probe=4bf795762d) | Jul 02, 2022 |
| Lenovo        | ThinkPad Edge E431 62771... | [ef8cc06070](https://linux-hardware.org/?probe=ef8cc06070) | Jun 09, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [48c983a184](https://linux-hardware.org/?probe=48c983a184) | May 15, 2022 |
| Dell          | XPS 17 9710                 | [919abd9078](https://linux-hardware.org/?probe=919abd9078) | May 13, 2022 |
| Dell          | XPS 17 9710                 | [15bc7f6757](https://linux-hardware.org/?probe=15bc7f6757) | May 13, 2022 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [604488642b](https://linux-hardware.org/?probe=604488642b) | Apr 25, 2022 |
| Samsung       | 730QCJ/730QCR               | [24b05b96d7](https://linux-hardware.org/?probe=24b05b96d7) | Jan 19, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [b6b4df52d0](https://linux-hardware.org/?probe=b6b4df52d0) | Dec 25, 2021 |
| Gigabyte      | AERO 15 KD                  | [cfa38b921a](https://linux-hardware.org/?probe=cfa38b921a) | Nov 22, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 5.14.0-284.30.1.el9_2.x86_64 | 6         | 12.77%  |
| 5.14.0-162.6.1.el9_1.x86_64  | 4         | 8.51%   |
| 5.14.0-162.12.1.el9_1.x86_64 | 4         | 8.51%   |
| 5.14.0-70.5.1.el9_0.x86_64   | 3         | 6.38%   |
| 5.14.0-70.26.1.el9_0.x86_64  | 3         | 6.38%   |
| 5.14.0-362.8.1.el9_3.x86_64  | 3         | 6.38%   |
| 5.14.0-362.13.1.el9_3.x86_64 | 3         | 6.38%   |
| 5.14.0-284.25.1.el9_2.x86_64 | 3         | 6.38%   |
| 5.14.0-162.23.1.el9_1.x86_64 | 3         | 6.38%   |
| 5.14.0-70.17.1.el9_0.x86_64  | 2         | 4.26%   |
| 5.14.0-70.13.1.el9_0.x86_64  | 2         | 4.26%   |
| 5.14.0-362.18.1.el9_3.x86_64 | 2         | 4.26%   |
| 5.14.0-162.18.1.el9_1.x86_64 | 2         | 4.26%   |
| 6.7.1-1.el9.elrepo.x86_64    | 1         | 2.13%   |
| 6.5.2-1.el9.elrepo.x86_64    | 1         | 2.13%   |
| 5.14.0-70.30.1.el9_0.x86_64  | 1         | 2.13%   |
| 5.14.0-427.13.1.el9_4.x86_64 | 1         | 2.13%   |
| 5.14.0-39.el9.x86_64         | 1         | 2.13%   |
| 5.14.0-284.11.1.el9_2.x86_64 | 1         | 2.13%   |
| 5.14.0-1.7.1.el9.x86_64      | 1         | 2.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.0  | 43        | 95.56%  |
| 6.7.1   | 1         | 2.22%   |
| 6.5.2   | 1         | 2.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 43        | 95.56%  |
| 6.7     | 1         | 2.22%   |
| 6.5     | 1         | 2.22%   |

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


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 42        | 91.3%   |
| XFCE            | 1         | 2.17%   |
| KDE5            | 1         | 2.17%   |
| GNOME Flashback | 1         | 2.17%   |
| GNOME Classic   | 1         | 2.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 35        | 77.78%  |
| X11     | 10        | 22.22%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 30        | 66.67%  |
| GDM     | 15        | 33.33%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 33        | 73.33%  |
| en_GB | 4         | 8.89%   |
| pt_BR | 2         | 4.44%   |
| cs_CZ | 2         | 4.44%   |
| ro_RO | 1         | 2.22%   |
| ko_KR | 1         | 2.22%   |
| en_IN | 1         | 2.22%   |
| C     | 1         | 2.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 43        | 95.56%  |
| BIOS | 2         | 4.44%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Xfs  | 43        | 95.56%  |
| Ext4 | 2         | 4.44%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 30        | 66.67%  |
| GPT     | 15        | 33.33%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 42        | 93.33%  |
| Yes       | 3         | 6.67%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 41        | 91.11%  |
| Yes       | 4         | 8.89%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 14        | 31.11%  |
| Lenovo              | 13        | 28.89%  |
| MSI                 | 5         | 11.11%  |
| Hewlett-Packard     | 5         | 11.11%  |
| ASUSTek Computer    | 3         | 6.67%   |
| System76            | 1         | 2.22%   |
| Samsung Electronics | 1         | 2.22%   |
| Razer               | 1         | 2.22%   |
| LG Electronics      | 1         | 2.22%   |
| Gigabyte Technology | 1         | 2.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| System76 Galago Pro                         | 1         | 2.22%   |
| Samsung 730QCJ/730QCR                       | 1         | 2.22%   |
| Razer Blade 15 Mid 2019-Base                | 1         | 2.22%   |
| MSI Modern 15 A5M                           | 1         | 2.22%   |
| MSI Katana GF76 12UC                        | 1         | 2.22%   |
| MSI Katana GF66 12UC                        | 1         | 2.22%   |
| MSI GP75 Leopard 9SD                        | 1         | 2.22%   |
| MSI GE72VR 7RF                              | 1         | 2.22%   |
| LG 15Z95P-GRLGL                             | 1         | 2.22%   |
| Lenovo ThinkPad X1 Nano Gen 2 21E80012US    | 1         | 2.22%   |
| Lenovo ThinkPad X1 Carbon Gen 11 21HMS1V900 | 1         | 2.22%   |
| Lenovo ThinkPad T490 20N3S77601             | 1         | 2.22%   |
| Lenovo ThinkPad S1 Yoga 12 20DK001YMC       | 1         | 2.22%   |
| Lenovo ThinkPad P17 Gen 2i 20YU002KUS       | 1         | 2.22%   |
| Lenovo ThinkPad L480 20LS0015UK             | 1         | 2.22%   |
| Lenovo ThinkPad L14 Gen 3 21C2S1EE00        | 1         | 2.22%   |
| Lenovo ThinkPad Edge E431 62771L7           | 1         | 2.22%   |
| Lenovo ThinkPad E14 20RA001MMZ              | 1         | 2.22%   |
| Lenovo ThinkBook 14-IIL 20SL                | 1         | 2.22%   |
| Lenovo ThinkBook 13s-IWL 20R9               | 1         | 2.22%   |
| Lenovo IdeaPad 330S-14IKB U 81F4            | 1         | 2.22%   |
| Lenovo IdeaPad 320-15IKB 80XL               | 1         | 2.22%   |
| HP ProBook 640 G2                           | 1         | 2.22%   |
| HP Laptop 14s-dk0xxx                        | 1         | 2.22%   |
| HP EliteBook 855 G7 Notebook PC             | 1         | 2.22%   |
| HP EliteBook 2570p                          | 1         | 2.22%   |
| HP 340S G7                                  | 1         | 2.22%   |
| Gigabyte AERO 15 KD                         | 1         | 2.22%   |
| Dell XPS 17 9710                            | 1         | 2.22%   |
| Dell Precision M4800                        | 1         | 2.22%   |
| Dell Precision 7720                         | 1         | 2.22%   |
| Dell Precision 7560                         | 1         | 2.22%   |
| Dell Precision 7540                         | 1         | 2.22%   |
| Dell Precision 7530                         | 1         | 2.22%   |
| Dell Precision 7510                         | 1         | 2.22%   |
| Dell Precision 3480                         | 1         | 2.22%   |
| Dell Latitude E7450                         | 1         | 2.22%   |
| Dell Latitude 3410                          | 1         | 2.22%   |
| Dell Inspiron N5040                         | 1         | 2.22%   |
| Dell Inspiron N5010                         | 1         | 2.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo ThinkPad  | 9         | 20%     |
| Dell Precision   | 7         | 15.56%  |
| Dell Inspiron    | 3         | 6.67%   |
| MSI Katana       | 2         | 4.44%   |
| Lenovo ThinkBook | 2         | 4.44%   |
| Lenovo IdeaPad   | 2         | 4.44%   |
| HP EliteBook     | 2         | 4.44%   |
| Dell Latitude    | 2         | 4.44%   |
| System76 Galago  | 1         | 2.22%   |
| Samsung 730QCJ   | 1         | 2.22%   |
| Razer Blade      | 1         | 2.22%   |
| MSI Modern       | 1         | 2.22%   |
| MSI GP75         | 1         | 2.22%   |
| MSI GE72VR       | 1         | 2.22%   |
| LG 15Z95P-GRLGL  | 1         | 2.22%   |
| HP ProBook       | 1         | 2.22%   |
| HP Laptop        | 1         | 2.22%   |
| HP 340S          | 1         | 2.22%   |
| Gigabyte AERO    | 1         | 2.22%   |
| Dell XPS         | 1         | 2.22%   |
| Dell G16         | 1         | 2.22%   |
| ASUS Z450LA      | 1         | 2.22%   |
| ASUS VivoBook    | 1         | 2.22%   |
| ASUS TUF         | 1         | 2.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 10        | 22.22%  |
| 2021 | 8         | 17.78%  |
| 2020 | 5         | 11.11%  |
| 2023 | 3         | 6.67%   |
| 2022 | 3         | 6.67%   |
| 2017 | 3         | 6.67%   |
| 2015 | 3         | 6.67%   |
| 2018 | 2         | 4.44%   |
| 2014 | 2         | 4.44%   |
| 2013 | 2         | 4.44%   |
| 2016 | 1         | 2.22%   |
| 2012 | 1         | 2.22%   |
| 2011 | 1         | 2.22%   |
| 2010 | 1         | 2.22%   |

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
| Disabled | 35        | 76.09%  |
| Enabled  | 11        | 23.91%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 44        | 97.78%  |
| Yes  | 1         | 2.22%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 19        | 42.22%  |
| 4.01-8.0    | 13        | 28.89%  |
| 32.01-64.0  | 5         | 11.11%  |
| 3.01-4.0    | 3         | 6.67%   |
| 64.01-256.0 | 3         | 6.67%   |
| 16.01-24.0  | 2         | 4.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 15        | 31.91%  |
| 2.01-3.0   | 14        | 29.79%  |
| 3.01-4.0   | 11        | 23.4%   |
| 8.01-16.0  | 4         | 8.51%   |
| 1.01-2.0   | 2         | 4.26%   |
| 32.01-64.0 | 1         | 2.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 29        | 61.7%   |
| 2      | 12        | 25.53%  |
| 3      | 5         | 10.64%  |
| 4      | 1         | 2.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 37        | 82.22%  |
| Yes       | 8         | 17.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 75.56%  |
| No        | 11        | 24.44%  |

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
| Yes       | 37        | 80.43%  |
| No        | 9         | 19.57%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 12        | 26.67%  |
| India       | 4         | 8.89%   |
| UK          | 2         | 4.44%   |
| Turkey      | 2         | 4.44%   |
| Italy       | 2         | 4.44%   |
| Guatemala   | 2         | 4.44%   |
| Czechia     | 2         | 4.44%   |
| Chile       | 2         | 4.44%   |
| Brazil      | 2         | 4.44%   |
| Vietnam     | 1         | 2.22%   |
| Switzerland | 1         | 2.22%   |
| Sri Lanka   | 1         | 2.22%   |
| South Korea | 1         | 2.22%   |
| Slovakia    | 1         | 2.22%   |
| Russia      | 1         | 2.22%   |
| Romania     | 1         | 2.22%   |
| Norway      | 1         | 2.22%   |
| Netherlands | 1         | 2.22%   |
| Kenya       | 1         | 2.22%   |
| Jordan      | 1         | 2.22%   |
| Indonesia   | 1         | 2.22%   |
| Finland     | 1         | 2.22%   |
| Egypt       | 1         | 2.22%   |
| Canada      | 1         | 2.22%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Santiago            | 2         | 4.26%   |
| Guatemala City      | 2         | 4.26%   |
| Zlín               | 1         | 2.13%   |
| Whiteley            | 1         | 2.13%   |
| Valbrembo           | 1         | 2.13%   |
| Stratham            | 1         | 2.13%   |
| Skien               | 1         | 2.13%   |
| Seoul               | 1         | 2.13%   |
| Sao Paulo           | 1         | 2.13%   |
| Saint Paul          | 1         | 2.13%   |
| Râmnicu Vâlcea    | 1         | 2.13%   |
| Providence          | 1         | 2.13%   |
| Prairieville        | 1         | 2.13%   |
| Piracicaba          | 1         | 2.13%   |
| Parker              | 1         | 2.13%   |
| Nuenen              | 1         | 2.13%   |
| Newcastle upon Tyne | 1         | 2.13%   |
| New Delhi           | 1         | 2.13%   |
| Nairobi             | 1         | 2.13%   |
| Montgomery          | 1         | 2.13%   |
| Milano              | 1         | 2.13%   |
| Maltepe             | 1         | 2.13%   |
| Liberec             | 1         | 2.13%   |
| Kolkata             | 1         | 2.13%   |
| Kemerovo            | 1         | 2.13%   |
| Jaipur              | 1         | 2.13%   |
| Houston             | 1         | 2.13%   |
| Ho Chi Minh City    | 1         | 2.13%   |
| Helsinki            | 1         | 2.13%   |
| Fort Collins        | 1         | 2.13%   |
| Denizli             | 1         | 2.13%   |
| Corona              | 1         | 2.13%   |
| Colombo             | 1         | 2.13%   |
| Christiansburg      | 1         | 2.13%   |
| Chicago             | 1         | 2.13%   |
| Chennai             | 1         | 2.13%   |
| Cairo               | 1         | 2.13%   |
| Bratislava          | 1         | 2.13%   |
| Brampton            | 1         | 2.13%   |
| Bern                | 1         | 2.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 17        | 20     | 26.15%  |
| Seagate                     | 5         | 6      | 7.69%   |
| Sandisk                     | 5         | 6      | 7.69%   |
| Toshiba                     | 4         | 4      | 6.15%   |
| Micron Technology           | 4         | 4      | 6.15%   |
| KIOXIA                      | 4         | 5      | 6.15%   |
| WDC                         | 3         | 3      | 4.62%   |
| Unknown                     | 3         | 3      | 4.62%   |
| SK hynix                    | 3         | 3      | 4.62%   |
| Micron/Crucial Technology   | 2         | 3      | 3.08%   |
| Kingston                    | 2         | 2      | 3.08%   |
| Intel                       | 2         | 3      | 3.08%   |
| SSSTC                       | 1         | 1      | 1.54%   |
| SABRENT                     | 1         | 1      | 1.54%   |
| Plextor                     | 1         | 1      | 1.54%   |
| Phison                      | 1         | 1      | 1.54%   |
| Kingston Technology Company | 1         | 1      | 1.54%   |
| KingSpec                    | 1         | 1      | 1.54%   |
| Kingmax                     | 1         | 1      | 1.54%   |
| HGST                        | 1         | 1      | 1.54%   |
| Golden                      | 1         | 1      | 1.54%   |
| China                       | 1         | 1      | 1.54%   |
| A-DATA Technology           | 1         | 1      | 1.54%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 4         | 5.97%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 3         | 4.48%   |
| Unknown MMC Card  256GB                            | 2         | 2.99%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 512GB    | 2         | 2.99%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB   | 2         | 2.99%   |
| Micron 2400_MTFDKBA512QFM 512GB                    | 2         | 2.99%   |
| KIOXIA KBG5AZNT1T02 LA 1TB                         | 2         | 2.99%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 1         | 1.49%   |
| WDC WDBNCE5000PNC 500GB SSD                        | 1         | 1.49%   |
| WDC WD10SPZX-60Z10T0 1TB                           | 1         | 1.49%   |
| Unknown MMC Card  512GB                            | 1         | 1.49%   |
| Toshiba MQ01ACF050 500GB                           | 1         | 1.49%   |
| Toshiba MQ01ABF050 500GB                           | 1         | 1.49%   |
| Toshiba MQ01ABF032 320GB                           | 1         | 1.49%   |
| Toshiba MQ01ABD100 1TB                             | 1         | 1.49%   |
| SSSTC CL1-3D512-Q11 NVMe 512GB                     | 1         | 1.49%   |
| SK hynix SHGP31-1000GM 1TB                         | 1         | 1.49%   |
| SK hynix NVMe SSD Drive 1024GB                     | 1         | 1.49%   |
| SK hynix HFM256GD3JX013N 256GB                     | 1         | 1.49%   |
| Seagate ST500LT012-9WS142 500GB                    | 1         | 1.49%   |
| Seagate ST1000LM049-2GH172 1TB                     | 1         | 1.49%   |
| Seagate ST1000LM035-1RK172 1TB                     | 1         | 1.49%   |
| Seagate BUP Slim BK 2TB                            | 1         | 1.49%   |
| Seagate Backup+ Hub BK 8TB                         | 1         | 1.49%   |
| Sandisk WD Blue SN570 500GB                        | 1         | 1.49%   |
| SanDisk NVMe SSD Drive 1TB                         | 1         | 1.49%   |
| Samsung SSD PM851 2.5 7mm 256GB                    | 1         | 1.49%   |
| Samsung SSD PM830 2.5 7mm 128GB                    | 1         | 1.49%   |
| Samsung SSD 980 1TB                                | 1         | 1.49%   |
| Samsung SSD 883 DCT 960GB                          | 1         | 1.49%   |
| Samsung SSD 870 EVO 1TB                            | 1         | 1.49%   |
| Samsung SSD 860 EVO 1TB                            | 1         | 1.49%   |
| Samsung NVMe SSD Drive 2TB                         | 1         | 1.49%   |
| Samsung NVMe SSD Drive 1TB                         | 1         | 1.49%   |
| Samsung MZALQ256HBJD-00BL2 256GB                   | 1         | 1.49%   |
| Samsung MZALQ256HAJD-000L2 256GB                   | 1         | 1.49%   |
| Samsung MZ7LN256HAJQ-000L7 256GB SSD               | 1         | 1.49%   |
| SABRENT Disk 1TB                                   | 1         | 1.49%   |
| Plextor PX-128S1G 128GB SSD                        | 1         | 1.49%   |
| Phison NVMe SSD Drive 960GB                        | 1         | 1.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 6      | 41.67%  |
| Toshiba | 4         | 4      | 33.33%  |
| WDC     | 1         | 1      | 8.33%   |
| SABRENT | 1         | 1      | 8.33%   |
| HGST    | 1         | 1      | 8.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 6      | 46.15%  |
| WDC                 | 2         | 2      | 15.38%  |
| Plextor             | 1         | 1      | 7.69%   |
| KingSpec            | 1         | 1      | 7.69%   |
| Kingmax             | 1         | 1      | 7.69%   |
| Intel               | 1         | 2      | 7.69%   |
| China               | 1         | 1      | 7.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 33        | 42     | 54.1%   |
| SSD     | 12        | 14     | 19.67%  |
| HDD     | 12        | 13     | 19.67%  |
| MMC     | 3         | 3      | 4.92%   |
| Unknown | 1         | 1      | 1.64%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 33        | 42     | 55.93%  |
| SATA | 20        | 24     | 33.9%   |
| SAS  | 3         | 4      | 5.08%   |
| MMC  | 3         | 3      | 5.08%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 11        | 12     | 47.83%  |
| 0.01-0.5   | 10        | 12     | 43.48%  |
| 1.01-2.0   | 1         | 1      | 4.35%   |
| 4.01-10.0  | 1         | 2      | 4.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 15        | 32.61%  |
| 501-1000       | 9         | 19.57%  |
| 251-500        | 8         | 17.39%  |
| 1001-2000      | 6         | 13.04%  |
| 51-100         | 3         | 6.52%   |
| 21-50          | 2         | 4.35%   |
| More than 3000 | 1         | 2.17%   |
| 2001-3000      | 1         | 2.17%   |
| Unknown        | 1         | 2.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 16        | 34.78%  |
| 21-50     | 12        | 26.09%  |
| 51-100    | 7         | 15.22%  |
| 251-500   | 4         | 8.7%    |
| 101-250   | 4         | 8.7%    |
| 1001-2000 | 2         | 4.35%   |
| Unknown   | 1         | 2.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB                | 1         | 1      | 25%     |
| Seagate ST1000LM035-1RK172 1TB                 | 1         | 1      | 25%     |
| Micron/Crucial Technology P1 NVMe PCIe SSD 1TB | 1         | 1      | 25%     |
| Intel SSDSC2BA800G4R 800GB                     | 1         | 2      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 2         | 2      | 50%     |
| Micron/Crucial Technology | 1         | 1      | 25%     |
| Intel                     | 1         | 2      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 2      | 50%     |
| NVMe | 1         | 1      | 25%     |
| SSD  | 1         | 2      | 25%     |

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
| Detected | 33        | 50     | 67.35%  |
| Works    | 12        | 18     | 24.49%  |
| Malfunc  | 4         | 5      | 8.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 31        | 46.97%  |
| Samsung Electronics         | 11        | 16.67%  |
| SanDisk                     | 5         | 7.58%   |
| Micron Technology           | 4         | 6.06%   |
| KIOXIA                      | 4         | 6.06%   |
| SK hynix                    | 3         | 4.55%   |
| Kingston Technology Company | 3         | 4.55%   |
| Micron/Crucial Technology   | 2         | 3.03%   |
| Phison Electronics          | 1         | 1.52%   |
| AMD                         | 1         | 1.52%   |
| ADATA Technology            | 1         | 1.52%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 7.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 5.88%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 5.88%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 4.41%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 3         | 4.41%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                     | 3         | 4.41%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 4.41%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 4.41%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 4.41%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 2         | 2.94%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 2         | 2.94%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 2         | 2.94%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 2.94%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 2.94%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 2         | 2.94%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 2.94%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 2.94%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 1.47%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 1         | 1.47%   |
| Phison E12 NVMe Controller                                                     | 1         | 1.47%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1         | 1.47%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                      | 1         | 1.47%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 1         | 1.47%   |
| Micron 2200S NVMe SSD [Cassandra]                                              | 1         | 1.47%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 1         | 1.47%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 1         | 1.47%   |
| Kingston Company NV2 NVMe SSD E21T (DRAM-less)                                 | 1         | 1.47%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                             | 1         | 1.47%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 1.47%   |
| Intel SSD 660P Series                                                          | 1         | 1.47%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 1.47%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 1.47%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.47%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.47%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.47%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 1.47%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 1         | 1.47%   |
| ADATA IM2P33F3 NVMe SSD (DRAM-less)                                            | 1         | 1.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 32        | 50%     |
| SATA | 26        | 40.63%  |
| RAID | 6         | 9.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 42        | 93.33%  |
| AMD    | 3         | 6.67%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 6.67%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 6.67%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 4.44%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 4.44%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 4.44%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 2         | 4.44%   |
| Intel 12th Gen Core i7-12700H                 | 2         | 4.44%   |
| Intel Xeon W-11855M CPU @ 3.20GHz             | 1         | 2.22%   |
| Intel Core i9-8950HK CPU @ 2.90GHz            | 1         | 2.22%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 2.22%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 2.22%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 2.22%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 1         | 2.22%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 2.22%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 2.22%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 2.22%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 2.22%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 2.22%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 1         | 2.22%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 2.22%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 2.22%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 1         | 2.22%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 2.22%   |
| Intel 13th Gen Core i7-1355U                  | 1         | 2.22%   |
| Intel 13th Gen Core i5-1335U                  | 1         | 2.22%   |
| Intel 12th Gen Core i9-12900K                 | 1         | 2.22%   |
| Intel 12th Gen Core i7-1260P                  | 1         | 2.22%   |
| Intel 12th Gen Core i5-12450H                 | 1         | 2.22%   |
| Intel 12th Gen Core i5-1235U                  | 1         | 2.22%   |
| Intel 11th Gen Core i9-11950H @ 2.60GHz       | 1         | 2.22%   |
| Intel 11th Gen Core i9-11900H @ 2.50GHz       | 1         | 2.22%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 1         | 2.22%   |
| Intel 11th Gen Core i5-1155G7 @ 2.50GHz       | 1         | 2.22%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 1         | 2.22%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 1         | 2.22%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 2.22%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i5   | 13        | 28.89%  |
| Other           | 12        | 26.67%  |
| Intel Core i7   | 11        | 24.44%  |
| Intel Core i3   | 3         | 6.67%   |
| AMD Ryzen 5     | 2         | 4.44%   |
| Intel Xeon      | 1         | 2.22%   |
| Intel Core i9   | 1         | 2.22%   |
| Intel Celeron   | 1         | 2.22%   |
| AMD Ryzen 7 PRO | 1         | 2.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 16        | 35.56%  |
| 2      | 11        | 24.44%  |
| 8      | 6         | 13.33%  |
| 6      | 6         | 13.33%  |
| 10     | 3         | 6.67%   |
| 14     | 2         | 4.44%   |
| 12     | 1         | 2.22%   |

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
| 2      | 42        | 93.33%  |
| 1      | 3         | 6.67%   |

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
| Unknown    | 10        | 22.22%  |
| 0x806ec    | 6         | 13.33%  |
| 0x806d1    | 4         | 8.89%   |
| 0x906a3    | 3         | 6.67%   |
| 0x706e5    | 2         | 4.44%   |
| 0x506e3    | 2         | 4.44%   |
| 0x406e3    | 2         | 4.44%   |
| 0x306a9    | 2         | 4.44%   |
| 0x906ed    | 1         | 2.22%   |
| 0x906ea    | 1         | 2.22%   |
| 0x906e9    | 1         | 2.22%   |
| 0x906a4    | 1         | 2.22%   |
| 0x90672    | 1         | 2.22%   |
| 0x806ea    | 1         | 2.22%   |
| 0x706a8    | 1         | 2.22%   |
| 0x40651    | 1         | 2.22%   |
| 0x306d4    | 1         | 2.22%   |
| 0x306c3    | 1         | 2.22%   |
| 0x20655    | 1         | 2.22%   |
| 0x08608103 | 1         | 2.22%   |
| 0x08600106 | 1         | 2.22%   |
| 0x08108109 | 1         | 2.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 14        | 31.11%  |
| Alderlake Hybrid | 8         | 17.78%  |
| Icelake          | 6         | 13.33%  |
| Skylake          | 4         | 8.89%   |
| Westmere         | 2         | 4.44%   |
| IvyBridge        | 2         | 4.44%   |
| Haswell          | 2         | 4.44%   |
| Broadwell        | 2         | 4.44%   |
| Zen+             | 1         | 2.22%   |
| Zen 2            | 1         | 2.22%   |
| TigerLake        | 1         | 2.22%   |
| Goldmont plus    | 1         | 2.22%   |
| Unknown          | 1         | 2.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 37        | 66.07%  |
| Nvidia | 13        | 23.21%  |
| AMD    | 6         | 10.71%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel CometLake-U GT2 [UHD Graphics]                                          | 4         | 7.14%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 4         | 7.14%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 3         | 5.36%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                     | 3         | 5.36%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 2         | 3.57%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 2         | 3.57%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 2         | 3.57%   |
| Intel UHD Graphics 620                                                        | 2         | 3.57%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 2         | 3.57%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 2         | 3.57%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                        | 2         | 3.57%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 2         | 3.57%   |
| Intel HD Graphics 5500                                                        | 2         | 3.57%   |
| Intel Core Processor Integrated Graphics Controller                           | 2         | 3.57%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 2         | 3.57%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                            | 1         | 1.79%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 1         | 1.79%   |
| Nvidia GP104GLM [Quadro P3000 Mobile]                                         | 1         | 1.79%   |
| Nvidia GK107GLM [Quadro K1100M]                                               | 1         | 1.79%   |
| Nvidia GA104GLM [RTX A5000 Mobile]                                            | 1         | 1.79%   |
| Nvidia GA102 [GeForce RTX 3090]                                               | 1         | 1.79%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 1         | 1.79%   |
| Intel HD Graphics 630                                                         | 1         | 1.79%   |
| Intel HD Graphics 620                                                         | 1         | 1.79%   |
| Intel HD Graphics 530                                                         | 1         | 1.79%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 1         | 1.79%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 1         | 1.79%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                   | 1         | 1.79%   |
| Intel Alder Lake-P GT1 [UHD Graphics]                                         | 1         | 1.79%   |
| AMD Venus XTX [Radeon HD 8890M / R9 M275X/M375X]                              | 1         | 1.79%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 1         | 1.79%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                 | 1         | 1.79%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 1         | 1.79%   |
| AMD Lucienne                                                                  | 1         | 1.79%   |
| AMD Lexa XT [Radeon PRO WX 3200]                                              | 1         | 1.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 26        | 57.78%  |
| Intel + Nvidia | 8         | 17.78%  |
| 1 x Nvidia     | 5         | 11.11%  |
| Intel + AMD    | 3         | 6.67%   |
| 1 x AMD        | 3         | 6.67%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 39        | 86.67%  |
| Proprietary | 5         | 11.11%  |
| Unknown     | 1         | 2.22%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 28        | 62.22%  |
| 5.01-6.0   | 5         | 11.11%  |
| 1.01-2.0   | 5         | 11.11%  |
| 3.01-4.0   | 2         | 4.44%   |
| 0.01-0.5   | 2         | 4.44%   |
| 2.01-3.0   | 1         | 2.22%   |
| 16.01-24.0 | 1         | 2.22%   |
| 8.01-16.0  | 1         | 2.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| BOE                  | 10        | 16.67%  |
| LG Display           | 9         | 15%     |
| AU Optronics         | 8         | 13.33%  |
| Chimei Innolux       | 7         | 11.67%  |
| Samsung Electronics  | 4         | 6.67%   |
| Hewlett-Packard      | 3         | 5%      |
| Goldstar             | 3         | 5%      |
| Dell                 | 3         | 5%      |
| Sharp                | 2         | 3.33%   |
| Lenovo               | 2         | 3.33%   |
| CSO                  | 2         | 3.33%   |
| Vizio                | 1         | 1.67%   |
| InfoVision           | 1         | 1.67%   |
| Gigabyte Technology  | 1         | 1.67%   |
| CEX                  | 1         | 1.67%   |
| BOE Technology Group | 1         | 1.67%   |
| ASUSTek Computer     | 1         | 1.67%   |
| AOC                  | 1         | 1.67%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Vizio E500i-A1 VIZ1004 1920x1080 1095x616mm 49.5-inch                 | 1         | 1.64%   |
| Sharp LCD Monitor SHP1518 1920x1200 366x229mm 17.0-inch               | 1         | 1.64%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch               | 1         | 1.64%   |
| Samsung Electronics S24E450 SAM0C9B 1920x1080 521x293mm 23.5-inch     | 1         | 1.64%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch  | 1         | 1.64%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 1         | 1.64%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch | 1         | 1.64%   |
| LG Display LCD Monitor LGD0753 1920x1080 309x174mm 14.0-inch          | 1         | 1.64%   |
| LG Display LCD Monitor LGD0645 1920x1080 344x194mm 15.5-inch          | 1         | 1.64%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch          | 1         | 1.64%   |
| LG Display LCD Monitor LGD0613 1920x1080 309x174mm 14.0-inch          | 1         | 1.64%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch          | 1         | 1.64%   |
| LG Display LCD Monitor LGD0540 1920x1080 344x194mm 15.5-inch          | 1         | 1.64%   |
| LG Display LCD Monitor LGD0486 1920x1080 309x174mm 14.0-inch          | 1         | 1.64%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch          | 1         | 1.64%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch           | 1         | 1.64%   |
| Lenovo LEN P24h-20 LEN61F4 2560x1440 527x296mm 23.8-inch              | 1         | 1.64%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch            | 1         | 1.64%   |
| Lenovo LEN LT2323pwA LEN0BD0 1920x1080 510x287mm 23.0-inch            | 1         | 1.64%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 1         | 1.64%   |
| Hewlett-Packard LP2465 HWP2676 1920x1200 519x324mm 24.1-inch          | 1         | 1.64%   |
| Hewlett-Packard LCD Monitor Pavilion32                                | 1         | 1.64%   |
| Hewlett-Packard E271i HWP3106 1920x1080 600x340mm 27.2-inch           | 1         | 1.64%   |
| Goldstar UltraFine GSM5B11 2560x2880 600x340mm 27.2-inch              | 1         | 1.64%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                   | 1         | 1.64%   |
| Goldstar LG ULTRAGEAR GSM5B80 2560x1440 600x340mm 27.2-inch           | 1         | 1.64%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch        | 1         | 1.64%   |
| Dell P2422H DELA1C4 1920x1080 530x300mm 24.0-inch                     | 1         | 1.64%   |
| Dell P2419HC DELA11D 1920x1080 527x296mm 23.8-inch                    | 1         | 1.64%   |
| Dell E2218HN DELF09E 1920x1080 476x268mm 21.5-inch                    | 1         | 1.64%   |
| CSO LCD Monitor CSO1404 1920x1200 302x189mm 14.0-inch                 | 1         | 1.64%   |
| CSO LCD Monitor CSO1303 2160x1350 280x175mm 13.0-inch                 | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN1760 1920x1080 381x214mm 17.2-inch      | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN1512 1920x1080 344x193mm 15.5-inch      | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 1         | 1.64%   |
| CEX CX60B CEX1560 1920x1080 600x330mm 27.0-inch                       | 1         | 1.64%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 28        | 52.83%  |
| 1366x768 (WXGA)   | 9         | 16.98%  |
| 3840x2160 (4K)    | 5         | 9.43%   |
| 2560x1440 (QHD)   | 3         | 5.66%   |
| 1920x1200 (WUXGA) | 3         | 5.66%   |
| Unknown           | 2         | 3.77%   |
| 5120x1440         | 1         | 1.89%   |
| 2560x1600         | 1         | 1.89%   |
| 2160x1350         | 1         | 1.89%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 13        | 22.41%  |
| 13      | 13        | 22.41%  |
| 14      | 8         | 13.79%  |
| 27      | 4         | 6.9%    |
| 17      | 4         | 6.9%    |
| 24      | 3         | 5.17%   |
| 23      | 3         | 5.17%   |
| 31      | 2         | 3.45%   |
| Unknown | 2         | 3.45%   |
| 72      | 1         | 1.72%   |
| 54      | 1         | 1.72%   |
| 21      | 1         | 1.72%   |
| 18      | 1         | 1.72%   |
| 16      | 1         | 1.72%   |
| 12      | 1         | 1.72%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 31        | 54.39%  |
| 501-600     | 9         | 15.79%  |
| 201-300     | 5         | 8.77%   |
| 351-400     | 4         | 7.02%   |
| 601-700     | 2         | 3.51%   |
| 401-500     | 2         | 3.51%   |
| Unknown     | 2         | 3.51%   |
| 1501-2000   | 1         | 1.75%   |
| 1001-1500   | 1         | 1.75%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 38        | 82.61%  |
| 16/10   | 6         | 13.04%  |
| Unknown | 2         | 4.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 17        | 28.81%  |
| 101-110        | 13        | 22.03%  |
| 201-250        | 6         | 10.17%  |
| 71-80          | 4         | 6.78%   |
| 301-350        | 4         | 6.78%   |
| 121-130        | 4         | 6.78%   |
| More than 1000 | 2         | 3.39%   |
| 351-500        | 2         | 3.39%   |
| 251-300        | 2         | 3.39%   |
| Unknown        | 2         | 3.39%   |
| 61-70          | 1         | 1.69%   |
| 141-150        | 1         | 1.69%   |
| 111-120        | 1         | 1.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 22        | 40%     |
| 101-120       | 12        | 21.82%  |
| 51-100        | 8         | 14.55%  |
| 161-240       | 7         | 12.73%  |
| More than 240 | 3         | 5.45%   |
| Unknown       | 2         | 3.64%   |
| 1-50          | 1         | 1.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 32        | 69.57%  |
| 2     | 10        | 21.74%  |
| 3     | 2         | 4.35%   |
| 5     | 1         | 2.17%   |
| 4     | 1         | 2.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 37        | 52.86%  |
| Realtek Semiconductor | 22        | 31.43%  |
| Qualcomm Atheros      | 6         | 8.57%   |
| Ralink Technology     | 1         | 1.43%   |
| MediaTek              | 1         | 1.43%   |
| DisplayLink           | 1         | 1.43%   |
| Broadcom Limited      | 1         | 1.43%   |
| Broadcom              | 1         | 1.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 10        | 11.63%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 6         | 6.98%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 5         | 5.81%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4         | 4.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 4         | 4.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 2         | 2.33%   |
| Intel Wireless 8265 / 8275                                             | 2         | 2.33%   |
| Intel Wireless 8260                                                    | 2         | 2.33%   |
| Intel Wireless 7265                                                    | 2         | 2.33%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 2         | 2.33%   |
| Intel Wi-Fi 6 AX200                                                    | 2         | 2.33%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 2         | 2.33%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 2         | 2.33%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 2.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 2         | 2.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2         | 2.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1         | 1.16%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 1         | 1.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1         | 1.16%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 1.16%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 1.16%   |
| Ralink MT7601U Wireless Adapter                                        | 1         | 1.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1         | 1.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 1         | 1.16%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 1.16%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 1.16%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 1         | 1.16%   |
| Intel Wireless 7260                                                    | 1         | 1.16%   |
| Intel Wireless 3160                                                    | 1         | 1.16%   |
| Intel Wi-Fi 6 AX201                                                    | 1         | 1.16%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 1         | 1.16%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 1         | 1.16%   |
| Intel Ethernet Controller I225-V                                       | 1         | 1.16%   |
| Intel Ethernet Controller I225-LM                                      | 1         | 1.16%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 1.16%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 1.16%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 1.16%   |
| Intel Ethernet Connection (5) I219-LM                                  | 1         | 1.16%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 1.16%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 1.16%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 35        | 76.09%  |
| Qualcomm Atheros      | 4         | 8.7%    |
| Realtek Semiconductor | 3         | 6.52%   |
| Ralink Technology     | 1         | 2.17%   |
| MediaTek              | 1         | 2.17%   |
| Broadcom Limited      | 1         | 2.17%   |
| Broadcom              | 1         | 2.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P PCH CNVi WiFi                            | 5         | 10.87%  |
| Intel Comet Lake PCH-LP CNVi WiFi                           | 4         | 8.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter  | 2         | 4.35%   |
| Intel Wireless 8265 / 8275                                  | 2         | 4.35%   |
| Intel Wireless 8260                                         | 2         | 4.35%   |
| Intel Wireless 7265                                         | 2         | 4.35%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]   | 2         | 4.35%   |
| Intel Wi-Fi 6 AX200                                         | 2         | 4.35%   |
| Intel Raptor Lake PCH CNVi WiFi                             | 2         | 4.35%   |
| Intel Ice Lake-LP PCH CNVi WiFi                             | 2         | 4.35%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                    | 2         | 4.35%   |
| Intel Cannon Lake PCH CNVi WiFi                             | 2         | 4.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter    | 1         | 2.17%   |
| Realtek RTL8723DE Wireless Network Adapter                  | 1         | 2.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter             | 1         | 2.17%   |
| Ralink MT7601U Wireless Adapter                             | 1         | 2.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter  | 1         | 2.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter  | 1         | 2.17%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                     | 1         | 2.17%   |
| Intel Wireless 7260                                         | 1         | 2.17%   |
| Intel Wireless 3160                                         | 1         | 2.17%   |
| Intel Wi-Fi 6 AX201                                         | 1         | 2.17%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]     | 1         | 2.17%   |
| Intel Tiger Lake PCH CNVi WiFi                              | 1         | 2.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]            | 1         | 2.17%   |
| Intel Centrino Wireless-N 2230                              | 1         | 2.17%   |
| Intel Alder Lake-S PCH CNVi WiFi                            | 1         | 2.17%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter | 1         | 2.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter         | 1         | 2.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 21        | 53.85%  |
| Intel                 | 15        | 38.46%  |
| Qualcomm Atheros      | 2         | 5.13%   |
| DisplayLink           | 1         | 2.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 10        | 25%     |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 6         | 15%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4         | 10%     |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 5%      |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 2.5%    |
| Realtek Killer E2600 GbE Controller                                    | 1         | 2.5%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 2.5%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 2.5%    |
| Intel Ethernet Controller I225-V                                       | 1         | 2.5%    |
| Intel Ethernet Controller I225-LM                                      | 1         | 2.5%    |
| Intel Ethernet Connection I219-LM                                      | 1         | 2.5%    |
| Intel Ethernet Connection I217-LM                                      | 1         | 2.5%    |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 2.5%    |
| Intel Ethernet Connection (5) I219-LM                                  | 1         | 2.5%    |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 2.5%    |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 2.5%    |
| Intel Ethernet Connection (23) I219-LM                                 | 1         | 2.5%    |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 2.5%    |
| Intel Ethernet Connection (16) I219-V                                  | 1         | 2.5%    |
| Intel Ethernet Connection (14) I219-LM                                 | 1         | 2.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 1         | 2.5%    |
| DisplayLink Dell D3100 Docking Station                                 | 1         | 2.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 45        | 56.96%  |
| Ethernet | 34        | 43.04%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 38        | 77.55%  |
| Ethernet | 11        | 22.45%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 33        | 73.33%  |
| 1     | 12        | 26.67%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 33        | 73.33%  |
| Yes  | 12        | 26.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 27        | 71.05%  |
| Qualcomm Atheros Communications | 3         | 7.89%   |
| Broadcom                        | 3         | 7.89%   |
| Realtek Semiconductor           | 2         | 5.26%   |
| MediaTek                        | 1         | 2.63%   |
| IMC Networks                    | 1         | 2.63%   |
| ASUSTek Computer                | 1         | 2.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                          | 9         | 23.68%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 5         | 13.16%  |
| Qualcomm Atheros  Bluetooth Device             | 3         | 7.89%   |
| Intel AX211 Bluetooth                          | 3         | 7.89%   |
| Intel Bluetooth wireless interface             | 2         | 5.26%   |
| Intel Bluetooth Device                         | 2         | 5.26%   |
| Intel AX210 Bluetooth                          | 2         | 5.26%   |
| Intel AX200 Bluetooth                          | 2         | 5.26%   |
| Realtek  Bluetooth 4.2 Adapter                 | 1         | 2.63%   |
| Realtek Bluetooth Radio                        | 1         | 2.63%   |
| MediaTek Wireless_Device                       | 1         | 2.63%   |
| Intel Wireless-AC 3168 Bluetooth               | 1         | 2.63%   |
| Intel Centrino Bluetooth Wireless Transceiver  | 1         | 2.63%   |
| IMC Networks Bluetooth Radio                   | 1         | 2.63%   |
| Broadcom HP Portable SoftSailing               | 1         | 2.63%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR           | 1         | 2.63%   |
| Broadcom BCM2045B (BDC-2.1)                    | 1         | 2.63%   |
| ASUS ASUS USB-BT500                            | 1         | 2.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 42        | 60%     |
| Nvidia                  | 11        | 15.71%  |
| AMD                     | 5         | 7.14%   |
| Texas Instruments       | 3         | 4.29%   |
| Realtek Semiconductor   | 3         | 4.29%   |
| SteelSeries ApS         | 1         | 1.43%   |
| Sony                    | 1         | 1.43%   |
| LG Electronics          | 1         | 1.43%   |
| Hewlett-Packard         | 1         | 1.43%   |
| Corsair                 | 1         | 1.43%   |
| BEHRINGER International | 1         | 1.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                     | 5         | 6.58%   |
| Intel Alder Lake PCH-P High Definition Audio Controller             | 5         | 6.58%   |
| Intel Tiger Lake-H HD Audio Controller                              | 4         | 5.26%   |
| Intel Comet Lake PCH-LP cAVS                                        | 4         | 5.26%   |
| Intel Cannon Lake PCH cAVS                                          | 4         | 5.26%   |
| Realtek Semiconductor USB Audio                                     | 3         | 3.95%   |
| Nvidia GA106 High Definition Audio Controller                       | 3         | 3.95%   |
| AMD Family 17h/19h HD Audio Controller                              | 3         | 3.95%   |
| Texas Instruments PCM2902 Audio Codec                               | 2         | 2.63%   |
| Nvidia TU116 High Definition Audio Controller                       | 2         | 2.63%   |
| Intel Wildcat Point-LP High Definition Audio Controller             | 2         | 2.63%   |
| Intel Raptor Lake-P/U/H cAVS                                        | 2         | 2.63%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller           | 2         | 2.63%   |
| Intel CM238 HD Audio Controller                                     | 2         | 2.63%   |
| Intel Cannon Point-LP High Definition Audio Controller              | 2         | 2.63%   |
| Intel Broadwell-U Audio Controller                                  | 2         | 2.63%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 2         | 2.63%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio            | 2         | 2.63%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 2         | 2.63%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                   | 1         | 1.32%   |
| SteelSeries ApS SteelSeries Arctis 1 Wireless                       | 1         | 1.32%   |
| Sony DualSense wireless controller (PS5)                            | 1         | 1.32%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller      | 1         | 1.32%   |
| Nvidia GP106 High Definition Audio Controller                       | 1         | 1.32%   |
| Nvidia GP104 High Definition Audio Controller                       | 1         | 1.32%   |
| Nvidia GK107 HDMI Audio Controller                                  | 1         | 1.32%   |
| Nvidia GA104 High Definition Audio Controller                       | 1         | 1.32%   |
| Nvidia GA102 High Definition Audio Controller                       | 1         | 1.32%   |
| LG Electronics USB Audio                                            | 1         | 1.32%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 1         | 1.32%   |
| Intel Haswell-ULT HD Audio Controller                               | 1         | 1.32%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio        | 1         | 1.32%   |
| Intel Alder Lake-S HD Audio Controller                              | 1         | 1.32%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 1         | 1.32%   |
| Intel 8 Series HD Audio Controller                                  | 1         | 1.32%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 1         | 1.32%   |
| Hewlett-Packard USB Audio                                           | 1         | 1.32%   |
| Corsair HS65 SURROUND                                               | 1         | 1.32%   |
| BEHRINGER International UMC404HD 192k                               | 1         | 1.32%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 1         | 1.32%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 4         | 26.67%  |
| SK hynix            | 3         | 20%     |
| Kingston            | 3         | 20%     |
| Crucial             | 2         | 13.33%  |
| Smart               | 1         | 6.67%   |
| Micron Technology   | 1         | 6.67%   |
| Elpida              | 1         | 6.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s        | 1         | 6.25%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 6.25%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 6.25%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s      | 1         | 6.25%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 6.25%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 1         | 6.25%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 1         | 6.25%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 6.25%   |
| Samsung RAM K3LK7K7@BM-BGCP 2GB Row Of Chips LPDDR5 6400MT/s | 1         | 6.25%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 3200MT/s        | 1         | 6.25%   |
| Kingston RAM X74R9W-MIE 8GB SODIMM DDR4 2933MT/s             | 1         | 6.25%   |
| Kingston RAM MSI24D4S7S8MB-8 8GB SODIMM DDR4 2667MT/s        | 1         | 6.25%   |
| Kingston RAM 9905744-108.A00G 16GB SODIMM DDR4 3200MT/s      | 1         | 6.25%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s        | 1         | 6.25%   |
| Crucial RAM CT4G4SFS824A.M8FE 4GB SODIMM DDR4 2400MT/s       | 1         | 6.25%   |
| Crucial RAM CT16G4SFD824A.C16FDD 16GB SODIMM DDR4 2400MT/s   | 1         | 6.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 9         | 75%     |
| DDR3   | 2         | 16.67%  |
| LPDDR5 | 1         | 8.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 11        | 91.67%  |
| Row Of Chips | 1         | 8.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 5         | 35.71%  |
| 16384 | 4         | 28.57%  |
| 4096  | 3         | 21.43%  |
| 32768 | 1         | 7.14%   |
| 2048  | 1         | 7.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 4         | 26.67%  |
| 3200  | 3         | 20%     |
| 2400  | 2         | 13.33%  |
| 2133  | 2         | 13.33%  |
| 1600  | 2         | 13.33%  |
| 6400  | 1         | 6.67%   |
| 2933  | 1         | 6.67%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| Seiko Epson L3210 Series | 1         | 100%    |

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
| Chicony Electronics                    | 9         | 20.45%  |
| Microdia                               | 6         | 13.64%  |
| Bison Electronics                      | 5         | 11.36%  |
| IMC Networks                           | 4         | 9.09%   |
| Sunplus Innovation Technology          | 3         | 6.82%   |
| Realtek Semiconductor                  | 3         | 6.82%   |
| Luxvisions Innotech Limited            | 2         | 4.55%   |
| Lite-On Technology                     | 2         | 4.55%   |
| Syntek                                 | 1         | 2.27%   |
| Suyin                                  | 1         | 2.27%   |
| Sonix Technology                       | 1         | 2.27%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 2.27%   |
| Samsung Electronics                    | 1         | 2.27%   |
| Remo Tech                              | 1         | 2.27%   |
| Quanta                                 | 1         | 2.27%   |
| Microsoft                              | 1         | 2.27%   |
| LG Electronics                         | 1         | 2.27%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.27%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                             | 3         | 6.82%   |
| Sunplus Integrated_Webcam_HD                                          | 2         | 4.55%   |
| Realtek Integrated_Webcam_HD                                          | 2         | 4.55%   |
| Microdia Integrated_Webcam_HD                                         | 2         | 4.55%   |
| IMC Networks Integrated Camera                                        | 2         | 4.55%   |
| Bison HD Webcam                                                       | 2         | 4.55%   |
| Syntek Integrated Camera                                              | 1         | 2.27%   |
| Suyin Integrated_Webcam_HD                                            | 1         | 2.27%   |
| Sunplus Integrated Camera                                             | 1         | 2.27%   |
| Sonix USB2.0 HD UVC WebCam                                            | 1         | 2.27%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera                       | 1         | 2.27%   |
| Samsung Galaxy series, misc. (MTP mode)                               | 1         | 2.27%   |
| Remo Tech OBSBOT Tiny 4K                                              | 1         | 2.27%   |
| Realtek Integrated Webcam_HD                                          | 1         | 2.27%   |
| Quanta HP TrueVision HD Camera                                        | 1         | 2.27%   |
| Microsoft LifeCam VX-2000                                             | 1         | 2.27%   |
| Microdia Laptop_Integrated_Webcam_7645BB9590586C77DC683CD9114697FF.3M | 1         | 2.27%   |
| Microdia Integrated_Webcam_FHD                                        | 1         | 2.27%   |
| Microdia Integrated Webcam                                            | 1         | 2.27%   |
| Microdia 1.3 MPixel Integrated Webcam                                 | 1         | 2.27%   |
| Luxvisions Innotech Limited Integrated RGB Camera                     | 1         | 2.27%   |
| Luxvisions Innotech Limited Integrated Camera                         | 1         | 2.27%   |
| Lite-On Integrated Camera                                             | 1         | 2.27%   |
| Lite-On HP HD Camera                                                  | 1         | 2.27%   |
| LG LG UltraFine Display Camera                                        | 1         | 2.27%   |
| IMC Networks USB2.0 HD UVC WebCam                                     | 1         | 2.27%   |
| IMC Networks USB Camera                                               | 1         | 2.27%   |
| Chicony USB2.0 VGA UVC WebCam                                         | 1         | 2.27%   |
| Chicony ThinkPad T490 Webcam                                          | 1         | 2.27%   |
| Chicony LG Camera                                                     | 1         | 2.27%   |
| Chicony HP HD Webcam [Fixed]                                          | 1         | 2.27%   |
| Chicony HP HD Camera                                                  | 1         | 2.27%   |
| Chicony HD Webcam                                                     | 1         | 2.27%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera        | 1         | 2.27%   |
| Bison Integrated Camera                                               | 1         | 2.27%   |
| Bison EasyCamera                                                      | 1         | 2.27%   |
| Bison BisonCam, NB Pro                                                | 1         | 2.27%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 4         | 44.44%  |
| Validity Sensors           | 2         | 22.22%  |
| Shenzhen Goodix Technology | 2         | 22.22%  |
| Samsung Electronics        | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 3         | 33.33%  |
| Shenzhen Goodix  FingerPrint Device                       | 2         | 22.22%  |
| Validity Sensors VFS5011 Fingerprint Reader               | 1         | 11.11%  |
| Validity Sensors VFS491                                   | 1         | 11.11%  |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 11.11%  |
| Samsung Fingerprint Sensor Device - 730B                  | 1         | 11.11%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 7         | 87.5%   |
| Alcor Micro | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 5880                                  | 3         | 37.5%   |
| Broadcom BCM5880 Secure Applications Processor | 2         | 25%     |
| Broadcom 58200                                 | 2         | 25%     |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 27        | 60%     |
| 1     | 17        | 37.78%  |
| 2     | 1         | 2.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 9         | 42.86%  |
| Chipcard              | 4         | 19.05%  |
| Multimedia controller | 3         | 14.29%  |
| Graphics card         | 3         | 14.29%  |
| Net/wireless          | 1         | 4.76%   |
| Card reader           | 1         | 4.76%   |

