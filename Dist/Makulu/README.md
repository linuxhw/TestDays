Makulu - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Makulu.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Makulu/Desktop/README.md) and [notebooks](/Dist/Makulu/Notebook/README.md).

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

| Vendor    | Model                       | Form-Factor | Probe                                                      | Date         |
|-----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell      | Latitude 3540               | Notebook    | [6fb057646a](https://linux-hardware.org/?probe=6fb057646a) | Feb 25, 2022 |
| Samsung   | R580                        | Notebook    | [b796f42cc3](https://linux-hardware.org/?probe=b796f42cc3) | Jan 31, 2022 |
| Gigabyte  | Z390 AORUS ULTRA-CF         | Desktop     | [5d298b8068](https://linux-hardware.org/?probe=5d298b8068) | Jan 04, 2022 |
| HP        | Pavilion Laptop 15z-cw10... | Notebook    | [c014435339](https://linux-hardware.org/?probe=c014435339) | Dec 29, 2021 |
| HP        | Pavilion Laptop 15z-cw10... | Notebook    | [97cfd9951b](https://linux-hardware.org/?probe=97cfd9951b) | Dec 29, 2021 |
| Lenovo    | V14-IIL 82C4                | Notebook    | [cb48d8f436](https://linux-hardware.org/?probe=cb48d8f436) | Dec 28, 2021 |
| HUAWEI    | KPL-W0X                     | Notebook    | [0551e72ef6](https://linux-hardware.org/?probe=0551e72ef6) | Dec 27, 2021 |
| HUAWEI    | KPL-W0X                     | Notebook    | [64d4de98ff](https://linux-hardware.org/?probe=64d4de98ff) | Dec 27, 2021 |
| Lenovo    | V14-IIL 82C4                | Notebook    | [e3873f9847](https://linux-hardware.org/?probe=e3873f9847) | Dec 23, 2021 |
| Dell      | 0DPRF9 A00                  | All in one  | [b3559aeec4](https://linux-hardware.org/?probe=b3559aeec4) | Dec 20, 2021 |
| ASUSTek   | M5A97 R2.0                  | Desktop     | [d3dc0d2eec](https://linux-hardware.org/?probe=d3dc0d2eec) | Nov 04, 2021 |
| ASUSTek   | N55SL                       | Notebook    | [11ed4def95](https://linux-hardware.org/?probe=11ed4def95) | Oct 24, 2021 |
| Dell      | 0TP406                      | Desktop     | [df97b29e2e](https://linux-hardware.org/?probe=df97b29e2e) | Oct 23, 2021 |
| Dell      | 0TP406                      | Desktop     | [5e3ac96715](https://linux-hardware.org/?probe=5e3ac96715) | Oct 22, 2021 |
| MSI       | Boston                      | Desktop     | [c45a00b3d6](https://linux-hardware.org/?probe=c45a00b3d6) | Oct 22, 2021 |
| Gigabyte  | 990FXA-UD5                  | Desktop     | [f3168dad1b](https://linux-hardware.org/?probe=f3168dad1b) | Oct 21, 2021 |
| Acer      | Nitro N50-600 V:1.1         | Desktop     | [d3c50b3461](https://linux-hardware.org/?probe=d3c50b3461) | Sep 26, 2021 |
| Lenovo    | IdeaPad Y530                | Notebook    | [6ca5521110](https://linux-hardware.org/?probe=6ca5521110) | Sep 24, 2021 |
| MSI       | Boston                      | Desktop     | [d95f0de735](https://linux-hardware.org/?probe=d95f0de735) | Sep 21, 2021 |
| MSI       | Boston                      | Desktop     | [50f3ed26ef](https://linux-hardware.org/?probe=50f3ed26ef) | Sep 21, 2021 |
| Dell      | 0WR7PY A02                  | Desktop     | [b5e3a47db9](https://linux-hardware.org/?probe=b5e3a47db9) | Sep 06, 2021 |
| Dell      | Inspiron 3521               | Notebook    | [9787940762](https://linux-hardware.org/?probe=9787940762) | Aug 29, 2021 |
| ELSA      | EA H410M-E                  | Desktop     | [b67c732be6](https://linux-hardware.org/?probe=b67c732be6) | Jul 19, 2021 |
| ELSA      | EA H410M-E                  | Desktop     | [97d82b0054](https://linux-hardware.org/?probe=97d82b0054) | Jul 19, 2021 |
| Dell      | 0MWYPT A00                  | Desktop     | [3577268e97](https://linux-hardware.org/?probe=3577268e97) | Jul 14, 2021 |
| Gigabyte  | B85M-HD3                    | Desktop     | [0da2654313](https://linux-hardware.org/?probe=0da2654313) | Jun 21, 2021 |
| Alienware | 02XRCM A01                  | Desktop     | [42fb24801d](https://linux-hardware.org/?probe=42fb24801d) | Jun 18, 2021 |
| Alienware | 02XRCM A01                  | Desktop     | [929ffb30b7](https://linux-hardware.org/?probe=929ffb30b7) | Jun 18, 2021 |
| Apple     | MacBookAir6,2               | Notebook    | [66f7c33d00](https://linux-hardware.org/?probe=66f7c33d00) | Jun 08, 2021 |
| Apple     | MacBookAir6,2               | Notebook    | [57385ac440](https://linux-hardware.org/?probe=57385ac440) | Jun 03, 2021 |
| Apple     | MacBookAir6,2               | Notebook    | [1ce8c5e2c7](https://linux-hardware.org/?probe=1ce8c5e2c7) | Jun 03, 2021 |
| Dell      | 0XFWHV A00                  | Desktop     | [e318737297](https://linux-hardware.org/?probe=e318737297) | May 02, 2021 |
| Lenovo    | Board                       | Desktop     | [cfee2604e5](https://linux-hardware.org/?probe=cfee2604e5) | Apr 30, 2021 |
| HP        | ENVY Notebook               | Notebook    | [61cb15af98](https://linux-hardware.org/?probe=61cb15af98) | Apr 28, 2021 |
| ASUSTek   | K55VD                       | Notebook    | [b9086bf814](https://linux-hardware.org/?probe=b9086bf814) | Apr 14, 2021 |
| ASUSTek   | K55VD                       | Notebook    | [10987a7dec](https://linux-hardware.org/?probe=10987a7dec) | Apr 13, 2021 |
| HP        | Compaq 15                   | Notebook    | [455bc50dc9](https://linux-hardware.org/?probe=455bc50dc9) | Mar 15, 2021 |
| Dell      | 0XCR8D A01                  | Desktop     | [3ed805ccdf](https://linux-hardware.org/?probe=3ed805ccdf) | Feb 26, 2021 |
| HP        | ENVY Notebook               | Notebook    | [f71898211e](https://linux-hardware.org/?probe=f71898211e) | Feb 25, 2021 |
| Dell      | 0XCR8D A01                  | Desktop     | [4f32c299db](https://linux-hardware.org/?probe=4f32c299db) | Feb 21, 2021 |
| Gigabyte  | GA-880GM-UD2H               | Desktop     | [61834d7ebf](https://linux-hardware.org/?probe=61834d7ebf) | Dec 03, 2020 |
| Gigabyte  | GA-880GM-UD2H               | Desktop     | [80ed244689](https://linux-hardware.org/?probe=80ed244689) | Dec 02, 2020 |
| Lenovo    | ThinkPad T420 4236W1W       | Notebook    | [3c3ff4f10e](https://linux-hardware.org/?probe=3c3ff4f10e) | Dec 02, 2020 |
| ASUSTek   | PRIME B450M-A               | Desktop     | [c588dc3be6](https://linux-hardware.org/?probe=c588dc3be6) | Nov 27, 2020 |
| Dell      | 0C2KJT A00                  | Desktop     | [b27a626476](https://linux-hardware.org/?probe=b27a626476) | Oct 03, 2020 |
| Lenovo    | ThinkPad T420 4236W1W       | Notebook    | [73279e52cd](https://linux-hardware.org/?probe=73279e52cd) | Oct 01, 2020 |
| Dell      | 0C2KJT A00                  | Desktop     | [2c1d312296](https://linux-hardware.org/?probe=2c1d312296) | Sep 30, 2020 |
| Dell      | 0C2KJT A00                  | Desktop     | [c8a79a4b9f](https://linux-hardware.org/?probe=c8a79a4b9f) | Sep 30, 2020 |
| HP        | Pavilion 17                 | Notebook    | [a6aa670ab4](https://linux-hardware.org/?probe=a6aa670ab4) | Sep 02, 2020 |
| HP        | Pavilion 17                 | Notebook    | [03171f4dbe](https://linux-hardware.org/?probe=03171f4dbe) | Aug 30, 2020 |
| Gigabyte  | GA-MA785GM-US2H             | Desktop     | [585646c033](https://linux-hardware.org/?probe=585646c033) | Feb 25, 2018 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.10.0-8-amd64         | 4         | 11.76%  |
| 5.8.0-44-generic       | 3         | 8.82%   |
| 5.4.0-42-generic       | 3         | 8.82%   |
| 5.11.0-43-generic      | 3         | 8.82%   |
| 5.11.0-41-generic      | 3         | 8.82%   |
| 5.8.0-50-generic       | 2         | 5.88%   |
| 5.14.0-2-amd64         | 2         | 5.88%   |
| 5.8.0-59-generic       | 1         | 2.94%   |
| 5.8.0-49-generic       | 1         | 2.94%   |
| 5.8.0-38-generic       | 1         | 2.94%   |
| 5.8.0-23-generic       | 1         | 2.94%   |
| 5.4.0-54-generic       | 1         | 2.94%   |
| 5.4.0-48-generic       | 1         | 2.94%   |
| 5.15.10-051510-generic | 1         | 2.94%   |
| 5.12.11-051211-generic | 1         | 2.94%   |
| 5.11.0-38-generic      | 1         | 2.94%   |
| 5.11.0-36-generic      | 1         | 2.94%   |
| 5.11.0-27-generic      | 1         | 2.94%   |
| 5.10.0-7-amd64         | 1         | 2.94%   |
| 5.10.0-3-amd64         | 1         | 2.94%   |
| 4.14.0-041400-generic  | 1         | 2.94%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.8.0   | 9         | 26.47%  |
| 5.11.0  | 9         | 26.47%  |
| 5.10.0  | 6         | 17.65%  |
| 5.4.0   | 5         | 14.71%  |
| 5.14.0  | 2         | 5.88%   |
| 5.15.10 | 1         | 2.94%   |
| 5.12.11 | 1         | 2.94%   |
| 4.14.0  | 1         | 2.94%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.8     | 9         | 26.47%  |
| 5.11    | 9         | 26.47%  |
| 5.10    | 6         | 17.65%  |
| 5.4     | 5         | 14.71%  |
| 5.14    | 2         | 5.88%   |
| 5.15    | 1         | 2.94%   |
| 5.12    | 1         | 2.94%   |
| 4.14    | 1         | 2.94%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 33        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 24        | 72.73%  |
| X-Cinnamon | 7         | 21.21%  |
| Core       | 1         | 3.03%   |
| Cinnamon   | 1         | 3.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 33        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 29        | 87.88%  |
| TDM     | 2         | 6.06%   |
| MDM     | 1         | 3.03%   |
| LightDM | 1         | 3.03%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 11        | 32.35%  |
| en_CA   | 5         | 14.71%  |
| de_DE   | 5         | 14.71%  |
| en_GB   | 4         | 11.76%  |
| pt_BR   | 2         | 5.88%   |
| it_IT   | 2         | 5.88%   |
| tr_TR   | 1         | 2.94%   |
| pl_PL   | 1         | 2.94%   |
| nl_NL   | 1         | 2.94%   |
| en_AU   | 1         | 2.94%   |
| Unknown | 1         | 2.94%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 24        | 70.59%  |
| EFI  | 10        | 29.41%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 31        | 91.18%  |
| Btrfs | 2         | 5.88%   |
| Tmpfs | 1         | 2.94%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 30        | 90.91%  |
| MBR     | 2         | 6.06%   |
| GPT     | 1         | 3.03%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 31        | 93.94%  |
| Yes       | 2         | 6.06%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 33        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 9         | 27.27%  |
| Gigabyte Technology | 5         | 15.15%  |
| Lenovo              | 4         | 12.12%  |
| Hewlett-Packard     | 4         | 12.12%  |
| ASUSTek Computer    | 4         | 12.12%  |
| Samsung Electronics | 1         | 3.03%   |
| MSI                 | 1         | 3.03%   |
| HUAWEI              | 1         | 3.03%   |
| ELSA                | 1         | 3.03%   |
| Apple               | 1         | 3.03%   |
| Alienware           | 1         | 3.03%   |
| Acer                | 1         | 3.03%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung R580                 | 1         | 3.03%   |
| MSI PPPPPPP-CCC#MMMMMMMM     | 1         | 3.03%   |
| Lenovo V14-IIL 82C4          | 1         | 3.03%   |
| Lenovo ThinkPad T420 4236W1W | 1         | 3.03%   |
| Lenovo IdeaPad Y530          | 1         | 3.03%   |
| Lenovo IdeaCentre K430       | 1         | 3.03%   |
| HUAWEI KPL-W0X               | 1         | 3.03%   |
| HP Pavilion Laptop 15z-cw100 | 1         | 3.03%   |
| HP Pavilion 17               | 1         | 3.03%   |
| HP ENVY Notebook             | 1         | 3.03%   |
| HP Compaq 15                 | 1         | 3.03%   |
| Gigabyte Z390 AORUS ULTRA    | 1         | 3.03%   |
| Gigabyte GA-MA785GM-US2H     | 1         | 3.03%   |
| Gigabyte GA-880GM-UD2H       | 1         | 3.03%   |
| Gigabyte B85M-HD3            | 1         | 3.03%   |
| Gigabyte 990FXA-UD5          | 1         | 3.03%   |
| ELSA EA H410M-E              | 1         | 3.03%   |
| Dell XPS420                  | 1         | 3.03%   |
| Dell Precision Tower 3620    | 1         | 3.03%   |
| Dell OptiPlex 9020           | 1         | 3.03%   |
| Dell OptiPlex 7010           | 1         | 3.03%   |
| Dell Latitude 3540           | 1         | 3.03%   |
| Dell Inspiron One 2305       | 1         | 3.03%   |
| Dell Inspiron 660s           | 1         | 3.03%   |
| Dell Inspiron 580            | 1         | 3.03%   |
| Dell Inspiron 3521           | 1         | 3.03%   |
| ASUS PRIME B450M-A           | 1         | 3.03%   |
| ASUS N55SL                   | 1         | 3.03%   |
| ASUS M5A97 R2.0              | 1         | 3.03%   |
| ASUS K55VD                   | 1         | 3.03%   |
| Apple MacBookAir6,2          | 1         | 3.03%   |
| Alienware Aurora R8          | 1         | 3.03%   |
| Acer Nitro N50-600           | 1         | 3.03%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Dell Inspiron            | 4         | 12.12%  |
| HP Pavilion              | 2         | 6.06%   |
| Dell OptiPlex            | 2         | 6.06%   |
| Samsung R580             | 1         | 3.03%   |
| MSI PPPPPPP-CCC#MMMMMMMM | 1         | 3.03%   |
| Lenovo V14-IIL           | 1         | 3.03%   |
| Lenovo ThinkPad          | 1         | 3.03%   |
| Lenovo IdeaPad           | 1         | 3.03%   |
| Lenovo IdeaCentre        | 1         | 3.03%   |
| HUAWEI KPL-W0X           | 1         | 3.03%   |
| HP ENVY                  | 1         | 3.03%   |
| HP Compaq                | 1         | 3.03%   |
| Gigabyte Z390            | 1         | 3.03%   |
| Gigabyte GA-MA785GM-US2H | 1         | 3.03%   |
| Gigabyte GA-880GM-UD2H   | 1         | 3.03%   |
| Gigabyte B85M-HD3        | 1         | 3.03%   |
| Gigabyte 990FXA-UD5      | 1         | 3.03%   |
| ELSA EA                  | 1         | 3.03%   |
| Dell XPS420              | 1         | 3.03%   |
| Dell Precision           | 1         | 3.03%   |
| Dell Latitude            | 1         | 3.03%   |
| ASUS PRIME               | 1         | 3.03%   |
| ASUS N55SL               | 1         | 3.03%   |
| ASUS M5A97               | 1         | 3.03%   |
| ASUS K55VD               | 1         | 3.03%   |
| Apple MacBookAir6        | 1         | 3.03%   |
| Alienware Aurora         | 1         | 3.03%   |
| Acer Nitro               | 1         | 3.03%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2013 | 7         | 21.21%  |
| 2012 | 5         | 15.15%  |
| 2018 | 4         | 12.12%  |
| 2020 | 3         | 9.09%   |
| 2010 | 3         | 9.09%   |
| 2009 | 3         | 9.09%   |
| 2019 | 2         | 6.06%   |
| 2011 | 2         | 6.06%   |
| 2015 | 1         | 3.03%   |
| 2014 | 1         | 3.03%   |
| 2008 | 1         | 3.03%   |
| 2007 | 1         | 3.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Desktop    | 18        | 54.55%  |
| Notebook   | 14        | 42.42%  |
| All in one | 1         | 3.03%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 33        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 33        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 12        | 35.29%  |
| 4.01-8.0   | 9         | 26.47%  |
| 8.01-16.0  | 7         | 20.59%  |
| 32.01-64.0 | 5         | 14.71%  |
| 16.01-24.0 | 1         | 2.94%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 16        | 44.44%  |
| 1.01-2.0 | 16        | 44.44%  |
| 4.01-8.0 | 2         | 5.56%   |
| 3.01-4.0 | 2         | 5.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 22        | 64.71%  |
| 4      | 4         | 11.76%  |
| 3      | 4         | 11.76%  |
| 2      | 4         | 11.76%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 19        | 57.58%  |
| No        | 14        | 42.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 87.88%  |
| No        | 4         | 12.12%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 73.53%  |
| No        | 9         | 26.47%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 18        | 54.55%  |
| Yes       | 15        | 45.45%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 9         | 27.27%  |
| UK          | 5         | 15.15%  |
| Germany     | 5         | 15.15%  |
| Canada      | 4         | 12.12%  |
| Italy       | 2         | 6.06%   |
| Brazil      | 2         | 6.06%   |
| Australia   | 2         | 6.06%   |
| Uganda      | 1         | 3.03%   |
| Turkey      | 1         | 3.03%   |
| Poland      | 1         | 3.03%   |
| Netherlands | 1         | 3.03%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Dallas            | 2         | 6.06%   |
| Wanzleben         | 1         | 3.03%   |
| Sydney            | 1         | 3.03%   |
| Roaring River     | 1         | 3.03%   |
| Pinhalzinho       | 1         | 3.03%   |
| Palmopolis        | 1         | 3.03%   |
| Munich            | 1         | 3.03%   |
| Melbourne         | 1         | 3.03%   |
| Mayen             | 1         | 3.03%   |
| Manitouwadge      | 1         | 3.03%   |
| Manchester        | 1         | 3.03%   |
| Los Angeles       | 1         | 3.03%   |
| Lodz              | 1         | 3.03%   |
| Leatherhead       | 1         | 3.03%   |
| Kitchener         | 1         | 3.03%   |
| Kampala           | 1         | 3.03%   |
| Izmir             | 1         | 3.03%   |
| Imperia           | 1         | 3.03%   |
| Hillegom          | 1         | 3.03%   |
| Hamilton          | 1         | 3.03%   |
| Freisbach         | 1         | 3.03%   |
| Edmonton          | 1         | 3.03%   |
| Chester           | 1         | 3.03%   |
| Chalfont St Giles | 1         | 3.03%   |
| Brugherio         | 1         | 3.03%   |
| Berlin            | 1         | 3.03%   |
| Beaverton         | 1         | 3.03%   |
| Ballygowan        | 1         | 3.03%   |
| Atlanta           | 1         | 3.03%   |
| Arroyo Grande     | 1         | 3.03%   |
| Anniston          | 1         | 3.03%   |
| Alexandria        | 1         | 3.03%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 12        | 14     | 23.08%  |
| Samsung Electronics       | 7         | 10     | 13.46%  |
| WDC                       | 6         | 8      | 11.54%  |
| Sandisk                   | 5         | 5      | 9.62%   |
| Toshiba                   | 3         | 3      | 5.77%   |
| Hitachi                   | 3         | 3      | 5.77%   |
| JMicron                   | 2         | 2      | 3.85%   |
| Unknown                   | 1         | 1      | 1.92%   |
| Transcend                 | 1         | 1      | 1.92%   |
| T-FORCE                   | 1         | 1      | 1.92%   |
| SK Hynix                  | 1         | 1      | 1.92%   |
| Origin                    | 1         | 1      | 1.92%   |
| Micron/Crucial Technology | 1         | 1      | 1.92%   |
| LITEON                    | 1         | 2      | 1.92%   |
| Leven                     | 1         | 1      | 1.92%   |
| KIOXIA                    | 1         | 1      | 1.92%   |
| Kingston                  | 1         | 1      | 1.92%   |
| HGST                      | 1         | 1      | 1.92%   |
| China                     | 1         | 1      | 1.92%   |
| ASMT                      | 1         | 1      | 1.92%   |
| Apple                     | 1         | 1      | 1.92%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB              | 2         | 3.64%   |
| Sandisk NVMe SSD Drive 500GB                 | 2         | 3.64%   |
| Samsung NVMe SSD Drive 1TB                   | 2         | 3.64%   |
| WDC WDS100T2B0A-00SM50 1TB SSD               | 1         | 1.82%   |
| WDC WD7501AAES-75W7A0 752GB                  | 1         | 1.82%   |
| WDC WD5000AADS-00L4B1 500GB                  | 1         | 1.82%   |
| WDC WD3200AAKS-75L9A0 320GB                  | 1         | 1.82%   |
| WDC WD1600AAJS-22PSA0 160GB                  | 1         | 1.82%   |
| WDC WD10EZEX-00KUWA0 1TB                     | 1         | 1.82%   |
| Unknown SD/MMC/MS PRO 64GB                   | 1         | 1.82%   |
| Transcend TS64GMSA230S 64GB SSD              | 1         | 1.82%   |
| Toshiba NVMe SSD Drive 512GB                 | 1         | 1.82%   |
| Toshiba MQ01ABF050M 500GB                    | 1         | 1.82%   |
| Toshiba MQ01ABD100 1TB                       | 1         | 1.82%   |
| T-FORCE 1TB                                  | 1         | 1.82%   |
| SK Hynix NVMe SSD Drive 512GB                | 1         | 1.82%   |
| Seagate ST940210AS 40GB                      | 1         | 1.82%   |
| Seagate ST9320325AS 320GB                    | 1         | 1.82%   |
| Seagate ST500DM002-1BD142 500GB              | 1         | 1.82%   |
| Seagate ST3500418AS 500GB                    | 1         | 1.82%   |
| Seagate ST3320820AS 320GB                    | 1         | 1.82%   |
| Seagate ST3320620AS 320GB                    | 1         | 1.82%   |
| Seagate ST31000524AS 1TB                     | 1         | 1.82%   |
| Seagate ST250DM000-1BD141 250GB              | 1         | 1.82%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1.82%   |
| Seagate Expansion Desk 8TB                   | 1         | 1.82%   |
| Seagate BarraCuda 120 SSD ZA500CM10003 500GB | 1         | 1.82%   |
| SanDisk SSD PLUS 480GB                       | 1         | 1.82%   |
| SanDisk SSD PLUS 1000GB                      | 1         | 1.82%   |
| Sandisk NVMe SSD Drive 512GB                 | 1         | 1.82%   |
| Samsung SSD 870 QVO 2TB                      | 1         | 1.82%   |
| Samsung SSD 860 EVO mSATA 500GB              | 1         | 1.82%   |
| Samsung NVMe SSD Drive 250GB                 | 1         | 1.82%   |
| Samsung NVMe SSD Drive 1024GB                | 1         | 1.82%   |
| Samsung MZMPC064HBDR-000L1 64GB SSD          | 1         | 1.82%   |
| Samsung MZ7TD128HAFV-000L1 128GB SSD         | 1         | 1.82%   |
| Samsung HM500JI 500GB                        | 1         | 1.82%   |
| Origin Inception TLC830 SSD 256GB            | 1         | 1.82%   |
| Micron/Crucial NVMe SSD Drive 500GB          | 1         | 1.82%   |
| LITEON L8H-256V2G-HP 256GB SSD               | 1         | 1.82%   |
| Leven JAJS600M512C 512GB SSD                 | 1         | 1.82%   |
| KIOXIA NVMe SSD Drive 256GB                  | 1         | 1.82%   |
| Kingston SA400S37240G 240GB SSD              | 1         | 1.82%   |
| JMicron Tech 250GB                           | 1         | 1.82%   |
| JMicron Generic 2TB                          | 1         | 1.82%   |
| Hitachi HTS545025B9A300 250GB                | 1         | 1.82%   |
| Hitachi HDS728080PLA380 82GB                 | 1         | 1.82%   |
| Hitachi HDS721010CLA332 1TB                  | 1         | 1.82%   |
| HGST HTS721010A9E630 1TB                     | 1         | 1.82%   |
| China SATA SSD 120GB                         | 1         | 1.82%   |
| ASMT USB 3.0 Destop H 1050GB                 | 1         | 1.82%   |
| Apple SSD SM0256F 256GB                      | 1         | 1.82%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 13     | 44%     |
| WDC                 | 5         | 7      | 20%     |
| Hitachi             | 3         | 3      | 12%     |
| Toshiba             | 2         | 2      | 8%      |
| Unknown             | 1         | 1      | 4%      |
| Samsung Electronics | 1         | 1      | 4%      |
| HGST                | 1         | 1      | 4%      |
| ASMT                | 1         | 1      | 4%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 5      | 26.67%  |
| SanDisk             | 2         | 2      | 13.33%  |
| WDC                 | 1         | 1      | 6.67%   |
| Transcend           | 1         | 1      | 6.67%   |
| Seagate             | 1         | 1      | 6.67%   |
| Origin              | 1         | 1      | 6.67%   |
| LITEON              | 1         | 2      | 6.67%   |
| Leven               | 1         | 1      | 6.67%   |
| Kingston            | 1         | 1      | 6.67%   |
| China               | 1         | 1      | 6.67%   |
| Apple               | 1         | 1      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 21        | 29     | 48.84%  |
| SSD     | 12        | 17     | 27.91%  |
| NVMe    | 8         | 12     | 18.6%   |
| Unknown | 2         | 2      | 4.65%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 30        | 44     | 73.17%  |
| NVMe | 7         | 11     | 17.07%  |
| SAS  | 4         | 5      | 9.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 23        | 32     | 63.89%  |
| 0.51-1.0   | 10        | 11     | 27.78%  |
| 1.01-2.0   | 2         | 2      | 5.56%   |
| 4.01-10.0  | 1         | 1      | 2.78%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 14        | 41.18%  |
| 501-1000       | 7         | 20.59%  |
| 251-500        | 5         | 14.71%  |
| More than 3000 | 2         | 5.88%   |
| 21-50          | 2         | 5.88%   |
| 51-100         | 2         | 5.88%   |
| 1001-2000      | 1         | 2.94%   |
| 1-20           | 1         | 2.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 15        | 40.54%  |
| 21-50          | 9         | 24.32%  |
| 51-100         | 6         | 16.22%  |
| 251-500        | 4         | 10.81%  |
| More than 3000 | 2         | 5.41%   |
| 101-250        | 1         | 2.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD3200AAKS-75L9A0 320GB | 1         | 2      | 50%     |
| Seagate ST31000524AS 1TB    | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 2      | 50%     |
| Seagate | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 2      | 50%     |
| Seagate | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 3      | 100%    |

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
| Detected | 30        | 55     | 88.24%  |
| Malfunc  | 2         | 3      | 5.88%   |
| Works    | 2         | 2      | 5.88%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 22        | 51.16%  |
| AMD                          | 9         | 20.93%  |
| Samsung Electronics          | 4         | 9.3%    |
| Sandisk                      | 3         | 6.98%   |
| Toshiba America Info Systems | 1         | 2.33%   |
| SK Hynix                     | 1         | 2.33%   |
| Micron/Crucial Technology    | 1         | 2.33%   |
| Marvell Technology Group     | 1         | 2.33%   |
| KIOXIA                       | 1         | 2.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4         | 8.51%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 4         | 8.51%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3         | 6.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 4.26%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 4.26%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 4.26%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 4.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 4.26%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2         | 4.26%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 2.13%   |
| SK Hynix SC300 512GB M.2 2280 SATA Solid State Drive                           | 1         | 2.13%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 1         | 2.13%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 2.13%   |
| Sandisk Non-Volatile memory controller                                         | 1         | 2.13%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 2.13%   |
| Samsung Apple PCIe SSD                                                         | 1         | 2.13%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1         | 2.13%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1         | 2.13%   |
| KIOXIA Non-Volatile memory controller                                          | 1         | 2.13%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 1         | 2.13%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 2.13%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1         | 2.13%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 2.13%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 2.13%   |
| Intel 8 Series/C220 Series Chipset Family IDE-r Controller                     | 1         | 2.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 2.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 2.13%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 1         | 2.13%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 2.13%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 2.13%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 1         | 2.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 1         | 2.13%   |
| AMD 400 Series Chipset SATA Controller                                         | 1         | 2.13%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 28        | 66.67%  |
| NVMe | 7         | 16.67%  |
| IDE  | 5         | 11.9%   |
| RAID | 2         | 4.76%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 23        | 69.7%   |
| AMD    | 10        | 30.3%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 1         | 3.03%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 1         | 3.03%   |
| Intel Pentium CPU G2030 @ 3.00GHz             | 1         | 3.03%   |
| Intel Core i7-9700 CPU @ 3.00GHz              | 1         | 3.03%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 1         | 3.03%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1         | 3.03%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 1         | 3.03%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 1         | 3.03%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 3.03%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 3.03%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 1         | 3.03%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 3.03%   |
| Intel Core i5-4260U CPU @ 1.40GHz             | 1         | 3.03%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 1         | 3.03%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 3.03%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 1         | 3.03%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 3.03%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 1         | 3.03%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 1         | 3.03%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 3.03%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 1         | 3.03%   |
| Intel Core i3 CPU 550 @ 3.20GHz               | 1         | 3.03%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 1         | 3.03%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 1         | 3.03%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 3.03%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 1         | 3.03%   |
| AMD Phenom II X4 955 Processor                | 1         | 3.03%   |
| AMD Phenom 9750 Quad-Core Processor           | 1         | 3.03%   |
| AMD FX-9590 Eight-Core Processor              | 1         | 3.03%   |
| AMD FX-4300 Quad-Core Processor               | 1         | 3.03%   |
| AMD E1-2100 APU with Radeon HD Graphics       | 1         | 3.03%   |
| AMD Athlon II X2 250u Processor               | 1         | 3.03%   |
| AMD A4-5000 APU with Radeon HD Graphics       | 1         | 3.03%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 7         | 21.21%  |
| Intel Core i5           | 7         | 21.21%  |
| Intel Core i3           | 5         | 15.15%  |
| Intel Pentium Dual-Core | 2         | 6.06%   |
| AMD Ryzen 7             | 2         | 6.06%   |
| AMD FX                  | 2         | 6.06%   |
| Intel Pentium           | 1         | 3.03%   |
| Intel Core 2 Quad       | 1         | 3.03%   |
| AMD Ryzen 5             | 1         | 3.03%   |
| AMD Phenom II X4        | 1         | 3.03%   |
| AMD Phenom              | 1         | 3.03%   |
| AMD E1                  | 1         | 3.03%   |
| AMD Athlon II X2        | 1         | 3.03%   |
| AMD A4                  | 1         | 3.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 15        | 45.45%  |
| 4      | 13        | 39.39%  |
| 6      | 3         | 9.09%   |
| 8      | 2         | 6.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 33        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 21        | 63.64%  |
| 1      | 12        | 36.36%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 33        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 11        | 31.43%  |
| 0x306a9    | 4         | 11.43%  |
| 0x40651    | 2         | 5.71%   |
| 0x206a7    | 2         | 5.71%   |
| 0x906ed    | 1         | 2.86%   |
| 0x506e3    | 1         | 2.86%   |
| 0x406e3    | 1         | 2.86%   |
| 0x306c3    | 1         | 2.86%   |
| 0x20655    | 1         | 2.86%   |
| 0x20652    | 1         | 2.86%   |
| 0x1067a    | 1         | 2.86%   |
| 0x08701021 | 1         | 2.86%   |
| 0x08108102 | 1         | 2.86%   |
| 0x08101007 | 1         | 2.86%   |
| 0x07000110 | 1         | 2.86%   |
| 0x0700010f | 1         | 2.86%   |
| 0x06000852 | 1         | 2.86%   |
| 0x010000c9 | 1         | 2.86%   |
| 0x010000c8 | 1         | 2.86%   |
| 0x010000c7 | 1         | 2.86%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| IvyBridge   | 5         | 15.15%  |
| Haswell     | 4         | 12.12%  |
| KabyLake    | 3         | 9.09%   |
| K10         | 3         | 9.09%   |
| Westmere    | 2         | 6.06%   |
| Skylake     | 2         | 6.06%   |
| SandyBridge | 2         | 6.06%   |
| Piledriver  | 2         | 6.06%   |
| Penryn      | 2         | 6.06%   |
| Jaguar      | 2         | 6.06%   |
| Zen+        | 1         | 3.03%   |
| Zen 2       | 1         | 3.03%   |
| Zen         | 1         | 3.03%   |
| IceLake     | 1         | 3.03%   |
| Core        | 1         | 3.03%   |
| CometLake   | 1         | 3.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 16        | 41.03%  |
| AMD    | 12        | 30.77%  |
| Nvidia | 11        | 28.21%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 5.13%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 2         | 5.13%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 2         | 5.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 5.13%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]     | 2         | 5.13%   |
| Nvidia GT218 [GeForce 210]                                                | 1         | 2.56%   |
| Nvidia GT216M [GeForce GT 330M]                                           | 1         | 2.56%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                       | 1         | 2.56%   |
| Nvidia GM204GL [Quadro M4000]                                             | 1         | 2.56%   |
| Nvidia GK208B [GeForce GT 710]                                            | 1         | 2.56%   |
| Nvidia GK107 [GeForce GT 640]                                             | 1         | 2.56%   |
| Nvidia GK107 [GeForce GT 630 OEM]                                         | 1         | 2.56%   |
| Nvidia GF119M [GeForce 610M]                                              | 1         | 2.56%   |
| Nvidia GF116M [GeForce GT 555M/635M]                                      | 1         | 2.56%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                         | 1         | 2.56%   |
| Nvidia G96CM [GeForce 9600M GS]                                           | 1         | 2.56%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller          | 1         | 2.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 2.56%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                    | 1         | 2.56%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 1         | 2.56%   |
| Intel HD Graphics 530                                                     | 1         | 2.56%   |
| Intel Core Processor Integrated Graphics Controller                       | 1         | 2.56%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                  | 1         | 2.56%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller | 1         | 2.56%   |
| AMD RV730 PRO [Radeon HD 4650]                                            | 1         | 2.56%   |
| AMD RV710 [Radeon HD 4350/4550]                                           | 1         | 2.56%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                 | 1         | 2.56%   |
| AMD RS880 [Radeon HD 4200]                                                | 1         | 2.56%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 1         | 2.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1         | 2.56%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                   | 1         | 2.56%   |
| AMD Kabini [Radeon HD 8330]                                               | 1         | 2.56%   |
| AMD Kabini [Radeon HD 8210]                                               | 1         | 2.56%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                          | 1         | 2.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 12        | 35.29%  |
| 1 x Intel      | 11        | 32.35%  |
| 1 x Nvidia     | 8         | 23.53%  |
| Intel + Nvidia | 3         | 8.82%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 30        | 90.91%  |
| Proprietary | 3         | 9.09%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 15        | 45.45%  |
| 1.01-2.0   | 7         | 21.21%  |
| 0.01-0.5   | 6         | 18.18%  |
| 0.51-1.0   | 3         | 9.09%   |
| 7.01-8.0   | 1         | 3.03%   |
| 5.01-6.0   | 1         | 3.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 4         | 12.9%   |
| Dell                    | 4         | 12.9%   |
| LG Display              | 3         | 9.68%   |
| Goldstar                | 3         | 9.68%   |
| Hewlett-Packard         | 2         | 6.45%   |
| Chimei Innolux          | 2         | 6.45%   |
| BOE                     | 2         | 6.45%   |
| AOC                     | 2         | 6.45%   |
| Toshiba                 | 1         | 3.23%   |
| Sony                    | 1         | 3.23%   |
| LG Electronics          | 1         | 3.23%   |
| HannStar                | 1         | 3.23%   |
| Element                 | 1         | 3.23%   |
| Chi Mei Optoelectronics | 1         | 3.23%   |
| AU Optronics            | 1         | 3.23%   |
| Apple                   | 1         | 3.23%   |
| Acer                    | 1         | 3.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Toshiba LCD Monitor TV 1920x1080                                         | 1         | 3.13%   |
| Sony TV SNYDC01 1360x768 1600x900mm 72.3-inch                            | 1         | 3.13%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 1         | 3.13%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch     | 1         | 3.13%   |
| Samsung Electronics LCD Monitor SDC415A 3200x1800 293x165mm 13.2-inch    | 1         | 3.13%   |
| Samsung Electronics LCD Monitor SDC3654 1600x900 382x215mm 17.3-inch     | 1         | 3.13%   |
| LG Electronics LCD Monitor LG IPS FULLHD                                 | 1         | 3.13%   |
| LG Electronics LCD Monitor LG HDR 4K 7360x2160                           | 1         | 3.13%   |
| LG Display LCD Monitor LGD062B 1920x1080 344x194mm 15.5-inch             | 1         | 3.13%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch              | 1         | 3.13%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 1         | 3.13%   |
| Hewlett-Packard LCD Monitor w1907 3120x1050                              | 1         | 3.13%   |
| Hewlett-Packard LCD Monitor 2009                                         | 1         | 3.13%   |
| HannStar Hanns.G HH241 HSD2275 1920x1080 521x293mm 23.5-inch             | 1         | 3.13%   |
| Goldstar W2261 GSM56CE 1920x1080 477x268mm 21.5-inch                     | 1         | 3.13%   |
| Goldstar TV SSCR GSM8080 3840x2160 1600x900mm 72.3-inch                  | 1         | 3.13%   |
| Goldstar E2050 GSM4EAD 1600x900 443x249mm 20.0-inch                      | 1         | 3.13%   |
| Element ELSFWC321 ELE6308 1366x768 700x390mm 31.5-inch                   | 1         | 3.13%   |
| Dell P2314H DEL4098 1920x1080 509x286mm 23.0-inch                        | 1         | 3.13%   |
| Dell P2217H DELA0D7 1920x1080 476x267mm 21.5-inch                        | 1         | 3.13%   |
| Dell LCD Monitor E228WFP                                                 | 1         | 3.13%   |
| Dell INSPIRON ONE DELB123 1920x1080 510x287mm 23.0-inch                  | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN15B8 1366x768 344x194mm 15.5-inch          | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 1         | 3.13%   |
| Chi Mei Optoelectronics LCD Monitor CMO1680 1366x768 344x193mm 15.5-inch | 1         | 3.13%   |
| BOE LCD Monitor BOE083C 1920x1080 309x173mm 13.9-inch                    | 1         | 3.13%   |
| BOE LCD Monitor BOE07D3 1920x1080 309x174mm 14.0-inch                    | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO9274 1280x800 331x207mm 15.4-inch            | 1         | 3.13%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                     | 1         | 3.13%   |
| AOC L19W931 AOC1993 1360x768 410x256mm 19.0-inch                         | 1         | 3.13%   |
| AOC 2243W AOC2243 1920x1080 477x268mm 21.5-inch                          | 1         | 3.13%   |
| Acer G226HQL ACR02EA 1920x1080 477x268mm 21.5-inch                       | 1         | 3.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 13        | 41.94%  |
| 1366x768 (WXGA)  | 6         | 19.35%  |
| 1600x900 (HD+)   | 2         | 6.45%   |
| 1360x768         | 2         | 6.45%   |
| Unknown          | 2         | 6.45%   |
| 7360x2160        | 1         | 3.23%   |
| 3840x2160 (4K)   | 1         | 3.23%   |
| 3200x1800 (QHD+) | 1         | 3.23%   |
| 3120x1050        | 1         | 3.23%   |
| 1440x900 (WXGA+) | 1         | 3.23%   |
| 1280x800 (WXGA)  | 1         | 3.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 9         | 31.03%  |
| 23      | 4         | 13.79%  |
| 21      | 3         | 10.34%  |
| 13      | 3         | 10.34%  |
| Unknown | 3         | 10.34%  |
| 72      | 2         | 6.9%    |
| 61      | 1         | 3.45%   |
| 20      | 1         | 3.45%   |
| 19      | 1         | 3.45%   |
| 17      | 1         | 3.45%   |
| 14      | 1         | 3.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 9         | 31.03%  |
| 401-500     | 5         | 17.24%  |
| 501-600     | 4         | 13.79%  |
| 351-400     | 3         | 10.34%  |
| Unknown     | 3         | 10.34%  |
| 201-300     | 2         | 6.9%    |
| 1501-2000   | 2         | 6.9%    |
| 1001-1500   | 1         | 3.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 23        | 79.31%  |
| 16/10   | 3         | 10.34%  |
| Unknown | 3         | 10.34%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 9         | 31.03%  |
| 201-250        | 5         | 17.24%  |
| 151-200        | 4         | 13.79%  |
| More than 1000 | 3         | 10.34%  |
| 81-90          | 3         | 10.34%  |
| Unknown        | 3         | 10.34%  |
| 71-80          | 1         | 3.45%   |
| 121-130        | 1         | 3.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 12        | 41.38%  |
| 101-120       | 7         | 24.14%  |
| 121-160       | 4         | 13.79%  |
| Unknown       | 3         | 10.34%  |
| 1-50          | 2         | 6.9%    |
| More than 240 | 1         | 3.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 31        | 93.94%  |
| 3     | 1         | 3.03%   |
| 2     | 1         | 3.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 18        | 33.96%  |
| Intel                           | 12        | 22.64%  |
| Qualcomm Atheros                | 7         | 13.21%  |
| Broadcom                        | 4         | 7.55%   |
| Qualcomm Atheros Communications | 2         | 3.77%   |
| Broadcom Limited                | 2         | 3.77%   |
| TP-Link                         | 1         | 1.89%   |
| Ralink Technology               | 1         | 1.89%   |
| Ralink                          | 1         | 1.89%   |
| MediaTek                        | 1         | 1.89%   |
| Marvell Technology Group        | 1         | 1.89%   |
| Edimax Technology               | 1         | 1.89%   |
| D-Link System                   | 1         | 1.89%   |
| D-Link                          | 1         | 1.89%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                | Computers | Percent |
|--------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                    | 13        | 22.03%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                | 4         | 6.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 3         | 5.08%   |
| Intel Wireless-AC 9260                                                               | 2         | 3.39%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 2         | 3.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                | 2         | 3.39%   |
| TP-Link 802.11ac WLAN Adapter                                                        | 1         | 1.69%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                      | 1         | 1.69%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                               | 1         | 1.69%   |
| Realtek RTL8188EE Wireless Network Adapter                                           | 1         | 1.69%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                           | 1         | 1.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                | 1         | 1.69%   |
| Ralink RT5370 Wireless Adapter                                                       | 1         | 1.69%   |
| Ralink RT2561/RT61 802.11g PCI                                                       | 1         | 1.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 1         | 1.69%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                            | 1         | 1.69%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1         | 1.69%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 1         | 1.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 1         | 1.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                        | 1         | 1.69%   |
| MediaTek WiFi                                                                        | 1         | 1.69%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB]       | 1         | 1.69%   |
| Intel Wireless 7265                                                                  | 1         | 1.69%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                              | 1         | 1.69%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                      | 1         | 1.69%   |
| Intel Ethernet Connection I217-LM                                                    | 1         | 1.69%   |
| Intel Ethernet Connection (7) I219-V                                                 | 1         | 1.69%   |
| Intel Ethernet Connection (2) I219-LM                                                | 1         | 1.69%   |
| Intel Centrino Ultimate-N 6300                                                       | 1         | 1.69%   |
| Intel 82566DC-2 Gigabit Network Connection                                           | 1         | 1.69%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT2870]                             | 1         | 1.69%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]                 | 1         | 1.69%   |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]                        | 1         | 1.69%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                                      | 1         | 1.69%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express                          | 1         | 1.69%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                           | 1         | 1.69%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                   | 1         | 1.69%   |
| Broadcom BCM43142 802.11b/g/n                                                        | 1         | 1.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                  | 1         | 1.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 8         | 27.59%  |
| Qualcomm Atheros                | 5         | 17.24%  |
| Realtek Semiconductor           | 3         | 10.34%  |
| Broadcom                        | 3         | 10.34%  |
| Qualcomm Atheros Communications | 2         | 6.9%    |
| TP-Link                         | 1         | 3.45%   |
| Ralink Technology               | 1         | 3.45%   |
| Ralink                          | 1         | 3.45%   |
| MediaTek                        | 1         | 3.45%   |
| Edimax Technology               | 1         | 3.45%   |
| D-Link System                   | 1         | 3.45%   |
| D-Link                          | 1         | 3.45%   |
| Broadcom Limited                | 1         | 3.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Computers | Percent |
|--------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 3         | 10%     |
| Intel Wireless-AC 9260                                                               | 2         | 6.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 2         | 6.67%   |
| TP-Link 802.11ac WLAN Adapter                                                        | 1         | 3.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                      | 1         | 3.33%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                               | 1         | 3.33%   |
| Realtek RTL8188EE Wireless Network Adapter                                           | 1         | 3.33%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                           | 1         | 3.33%   |
| Ralink RT5370 Wireless Adapter                                                       | 1         | 3.33%   |
| Ralink RT2561/RT61 802.11g PCI                                                       | 1         | 3.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 1         | 3.33%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1         | 3.33%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 1         | 3.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 1         | 3.33%   |
| MediaTek WiFi                                                                        | 1         | 3.33%   |
| Intel Wireless 7265                                                                  | 1         | 3.33%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                              | 1         | 3.33%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                      | 1         | 3.33%   |
| Intel Centrino Ultimate-N 6300                                                       | 1         | 3.33%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT2870]                             | 1         | 3.33%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]                 | 1         | 3.33%   |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]                        | 1         | 3.33%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                           | 1         | 3.33%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                   | 1         | 3.33%   |
| Broadcom BCM43142 802.11b/g/n                                                        | 1         | 3.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                  | 1         | 3.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 18        | 62.07%  |
| Intel                    | 6         | 20.69%  |
| Qualcomm Atheros         | 2         | 6.9%    |
| Marvell Technology Group | 1         | 3.45%   |
| Broadcom Limited         | 1         | 3.45%   |
| Broadcom                 | 1         | 3.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 13        | 44.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 13.79%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2         | 6.9%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 3.45%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 3.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 3.45%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 3.45%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 3.45%   |
| Intel Ethernet Connection (7) I219-V                                           | 1         | 3.45%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 3.45%   |
| Intel 82566DC-2 Gigabit Network Connection                                     | 1         | 3.45%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                                | 1         | 3.45%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express                    | 1         | 3.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 29        | 53.7%   |
| WiFi     | 25        | 46.3%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 28        | 54.9%   |
| WiFi     | 23        | 45.1%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 17        | 51.52%  |
| 1     | 16        | 48.48%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 27        | 81.82%  |
| Yes  | 6         | 18.18%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 5         | 31.25%  |
| Broadcom                        | 5         | 31.25%  |
| Realtek Semiconductor           | 2         | 12.5%   |
| Qualcomm Atheros Communications | 1         | 6.25%   |
| IMC Networks                    | 1         | 6.25%   |
| Dell                            | 1         | 6.25%   |
| Apple                           | 1         | 6.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                            | 3         | 18.75%  |
| Realtek  Bluetooth 4.2 Adapter                    | 1         | 6.25%   |
| Realtek Bluetooth Radio                           | 1         | 6.25%   |
| Qualcomm Atheros AR9462 Bluetooth                 | 1         | 6.25%   |
| Intel Wireless-AC 9260 Bluetooth Adapter          | 1         | 6.25%   |
| Intel Bluetooth wireless interface                | 1         | 6.25%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter | 1         | 6.25%   |
| Dell BT Mini-Receiver                             | 1         | 6.25%   |
| Broadcom Bluetooth 2.1 Device                     | 1         | 6.25%   |
| Broadcom BCM43142 Bluetooth 4.0                   | 1         | 6.25%   |
| Broadcom BCM20702A0 Bluetooth 4.0                 | 1         | 6.25%   |
| Broadcom BCM2046 Bluetooth Device                 | 1         | 6.25%   |
| Broadcom BCM2045B (BDC-2.1)                       | 1         | 6.25%   |
| Apple Bluetooth USB Host Controller               | 1         | 6.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 23        | 50%     |
| AMD    | 14        | 30.43%  |
| Nvidia | 9         | 19.57%  |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 9.09%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5         | 9.09%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 3.64%   |
| Nvidia GF116 High Definition Audio Controller                              | 2         | 3.64%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 3.64%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 3.64%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 3.64%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 3.64%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 3.64%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 3.64%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2         | 3.64%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 3.64%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2         | 3.64%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 3.64%   |
| AMD FCH Azalia Controller                                                  | 2         | 3.64%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 3.64%   |
| Nvidia High Definition Audio Controller                                    | 1         | 1.82%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 1.82%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 1.82%   |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 1.82%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.82%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 1.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 1.82%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.82%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 1.82%   |
| Intel Comet Lake PCH-V cAVS                                                | 1         | 1.82%   |
| Intel 200 Series PCH HD Audio                                              | 1         | 1.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.82%   |
| AMD Starship/Matisse HD Audio Controller                                   | 1         | 1.82%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1         | 1.82%   |
| AMD Navi 10 HDMI Audio                                                     | 1         | 1.82%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1         | 1.82%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Unknown  | 1         | 33.33%  |
| Smart    | 1         | 33.33%  |
| SK Hynix | 1         | 33.33%  |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM 1066MT/s              | 1         | 33.33%  |
| Smart RAM SH564568FH8N6PHSFG 2GB DIMM DDR3 1333MT/s  | 1         | 33.33%  |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s | 1         | 33.33%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 2         | 66.67%  |
| Unknown | 1         | 33.33%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| DIMM | 3         | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size | Computers | Percent |
|------|-----------|---------|
| 2048 | 2         | 66.67%  |
| 4096 | 1         | 33.33%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1800  | 1         | 33.33%  |
| 1333  | 1         | 33.33%  |
| 1066  | 1         | 33.33%  |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Omnidirectional Control Technology | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Omnidirectional Control USB-Parallel Bridge | 1         | 100%    |

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
| Chicony Electronics                    | 4         | 28.57%  |
| Suyin                                  | 3         | 21.43%  |
| Microdia                               | 2         | 14.29%  |
| Cheng Uei Precision Industry (Foxlink) | 2         | 14.29%  |
| Z-Star Microelectronics                | 1         | 7.14%   |
| Sonix Technology                       | 1         | 7.14%   |
| Lite-On Technology                     | 1         | 7.14%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 2         | 14.29%  |
| Z-Star WebCam SCB-1900N                                 | 1         | 7.14%   |
| Suyin UVC HD Webcam                                     | 1         | 7.14%   |
| Suyin Laptop_Integrated_Webcam_HD                       | 1         | 7.14%   |
| Suyin HP Truevision HD                                  | 1         | 7.14%   |
| Sonix USB 2.0 Camera                                    | 1         | 7.14%   |
| Microdia Integrated Camera                              | 1         | 7.14%   |
| Microdia Dell Laptop Integrated Webcam HD               | 1         | 7.14%   |
| Lite-On HP Wide Vision HD Camera                        | 1         | 7.14%   |
| Chicony UVC 1.00 device HD UVC WebCam                   | 1         | 7.14%   |
| Chicony Lenovo EasyCamera                               | 1         | 7.14%   |
| Chicony Laptop_Integrated_Webcam_2M                     | 1         | 7.14%   |
| Chicony Integrated Camera                               | 1         | 7.14%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 1         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Validity Sensors Swipe Fingerprint Sensor | 1         | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 30        | 90.91%  |
| 1     | 3         | 9.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 1         | 33.33%  |
| Multimedia controller | 1         | 33.33%  |
| Fingerprint reader    | 1         | 33.33%  |

