Xero - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------

A project to collect tested hardware configurations for Xero.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 40

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Dell     | Precision M3800             | [9fc15d1ae6](https://linux-hardware.org/?probe=9fc15d1ae6) | Mar 31, 2022 |
| MSI      | GF63 Thin 9SCX              | [4501fa1556](https://linux-hardware.org/?probe=4501fa1556) | Mar 25, 2022 |
| Dell     | Latitude 7480               | [bf00ec6a76](https://linux-hardware.org/?probe=bf00ec6a76) | Mar 23, 2022 |
| HUAWEI   | WRT-WX9                     | [70ec26bed6](https://linux-hardware.org/?probe=70ec26bed6) | Mar 22, 2022 |
| Dell     | Latitude 7480               | [1083fec58a](https://linux-hardware.org/?probe=1083fec58a) | Mar 19, 2022 |
| Dell     | Latitude 7480               | [faddba28a8](https://linux-hardware.org/?probe=faddba28a8) | Mar 19, 2022 |
| Apple    | MacBookAir6,2               | [b71110144d](https://linux-hardware.org/?probe=b71110144d) | Mar 19, 2022 |
| HP       | Laptop 15-da0xxx            | [bb9074ccdf](https://linux-hardware.org/?probe=bb9074ccdf) | Mar 18, 2022 |
| Lenovo   | IdeaPad 3 15IML05 81WR      | [918c951cd1](https://linux-hardware.org/?probe=918c951cd1) | Mar 12, 2022 |
| Lenovo   | IdeaPad S145-15IIL 81W8     | [e251c9f079](https://linux-hardware.org/?probe=e251c9f079) | Mar 11, 2022 |
| Dell     | Venue 11 Pro 7130 vPro      | [57b302b119](https://linux-hardware.org/?probe=57b302b119) | Mar 05, 2022 |
| Lenovo   | ThinkPad T460 20FMS1XX00    | [78e82c6674](https://linux-hardware.org/?probe=78e82c6674) | Feb 24, 2022 |
| Dell     | Latitude E6430              | [e1de4e80fe](https://linux-hardware.org/?probe=e1de4e80fe) | Feb 15, 2022 |
| Lenovo   | Legion 5 15ARH05H 82B1      | [a3c5f00a2a](https://linux-hardware.org/?probe=a3c5f00a2a) | Feb 10, 2022 |
| Lenovo   | Legion 5 15ARH05H 82B1      | [e53fb31614](https://linux-hardware.org/?probe=e53fb31614) | Feb 10, 2022 |
| Lenovo   | Legion Y740-15IRHg 81UH     | [b0cc5e0cbc](https://linux-hardware.org/?probe=b0cc5e0cbc) | Jan 29, 2022 |
| Acer     | Aspire A315-58G             | [cb4f253c1c](https://linux-hardware.org/?probe=cb4f253c1c) | Jan 28, 2022 |
| Dell     | Latitude E6520              | [ee96960cec](https://linux-hardware.org/?probe=ee96960cec) | Jan 25, 2022 |
| HP       | Laptop 15s-eq0xxx           | [0df160c245](https://linux-hardware.org/?probe=0df160c245) | Jan 21, 2022 |
| Lenovo   | Legion Y540-15IRH-PG0 81... | [3df8a1c560](https://linux-hardware.org/?probe=3df8a1c560) | Jan 08, 2022 |
| Dell     | Vostro 3590                 | [9e77a2584c](https://linux-hardware.org/?probe=9e77a2584c) | Dec 30, 2021 |
| ASUSTek  | ASUS EXPERTBOOK B9400CEA... | [78e3fbdf6a](https://linux-hardware.org/?probe=78e3fbdf6a) | Dec 28, 2021 |
| HP       | Notebook                    | [c14ea64659](https://linux-hardware.org/?probe=c14ea64659) | Dec 23, 2021 |
| ASUSTek  | X510UNR                     | [0733a05806](https://linux-hardware.org/?probe=0733a05806) | Dec 21, 2021 |
| ASUSTek  | ASUS EXPERTBOOK B9400CEA... | [b4425de4a6](https://linux-hardware.org/?probe=b4425de4a6) | Dec 17, 2021 |
| ASUSTek  | ASUS TUF Gaming F15 FX50... | [6f3bd18b3f](https://linux-hardware.org/?probe=6f3bd18b3f) | Dec 06, 2021 |
| Pegatron | D15K                        | [eaeaad8d39](https://linux-hardware.org/?probe=eaeaad8d39) | Nov 29, 2021 |
| MSI      | GP73 Leopard 8RD            | [5bafb43f78](https://linux-hardware.org/?probe=5bafb43f78) | Nov 21, 2021 |
| Acer     | Aspire A315-58G             | [911895fcf2](https://linux-hardware.org/?probe=911895fcf2) | Nov 19, 2021 |
| Acer     | Aspire A315-58G             | [5748b3cd05](https://linux-hardware.org/?probe=5748b3cd05) | Nov 12, 2021 |
| Lenovo   | ThinkPad W530 24384CU       | [d18d3495e0](https://linux-hardware.org/?probe=d18d3495e0) | Nov 05, 2021 |
| Acer     | Aspire A315-58G             | [905fce5118](https://linux-hardware.org/?probe=905fce5118) | Oct 29, 2021 |
| HP       | ENVY Sleekbook 4            | [ebea056239](https://linux-hardware.org/?probe=ebea056239) | Oct 29, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop X509... | [2a54689fb3](https://linux-hardware.org/?probe=2a54689fb3) | Oct 24, 2021 |
| ASUSTek  | VivoBook_ASUS Laptop E41... | [fb95cbb063](https://linux-hardware.org/?probe=fb95cbb063) | Oct 19, 2021 |
| Lenovo   | IdeaPad 5 15ITL05 82FG      | [6cd76dfa2a](https://linux-hardware.org/?probe=6cd76dfa2a) | Oct 13, 2021 |
| ASUSTek  | ASUS TUF Gaming F15 FX50... | [e3a8d1ca32](https://linux-hardware.org/?probe=e3a8d1ca32) | Oct 11, 2021 |
| ASUSTek  | ASUS TUF Gaming F15 FX50... | [c7c4a74bb8](https://linux-hardware.org/?probe=c7c4a74bb8) | Oct 11, 2021 |
| ASUSTek  | ASUS TUF Gaming F15 FX50... | [68865693c7](https://linux-hardware.org/?probe=68865693c7) | Oct 09, 2021 |
| Lenovo   | Y520-15IKBN 80WK            | [e804a59920](https://linux-hardware.org/?probe=e804a59920) | Oct 02, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Xero Rolling | 26        | 83.87%  |
| Xero         | 5         | 16.13%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| Xero | 30        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 5.16.15-arch1-1              | 4         | 12.12%  |
| 5.16.8-arch1-1               | 2         | 6.06%   |
| 5.16.2-arch1-1               | 2         | 6.06%   |
| 5.16.1-arch1-1               | 2         | 6.06%   |
| 5.14.14-arch1-1              | 2         | 6.06%   |
| 5.17.1-arch1-1               | 1         | 3.03%   |
| 5.16.16-arch1-1              | 1         | 3.03%   |
| 5.16.14-arch1-1              | 1         | 3.03%   |
| 5.16.13-arch1-1              | 1         | 3.03%   |
| 5.16.10-arch1-1              | 1         | 3.03%   |
| 5.15.8-zen1-1-zen            | 1         | 3.03%   |
| 5.15.26-1-lts                | 1         | 3.03%   |
| 5.15.13-arch1-1              | 1         | 3.03%   |
| 5.15.11-arch2-1              | 1         | 3.03%   |
| 5.15.10-arch1-1              | 1         | 3.03%   |
| 5.14.8-zen1-1-zen            | 1         | 3.03%   |
| 5.14.8-arch1-1               | 1         | 3.03%   |
| 5.14.16-zen1-1-zen           | 1         | 3.03%   |
| 5.14.16-arch1-2-surface      | 1         | 3.03%   |
| 5.14.16-arch1-1              | 1         | 3.03%   |
| 5.14.14-zen1-1-zen           | 1         | 3.03%   |
| 5.14.12-arch1-1              | 1         | 3.03%   |
| 5.14.11-hardened1-1-hardened | 1         | 3.03%   |
| 5.10.88-1-lts                | 1         | 3.03%   |
| 5.10.80-1-lts                | 1         | 3.03%   |
| 5.10.71-1-lts                | 1         | 3.03%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.16.15 | 4         | 12.12%  |
| 5.14.16 | 3         | 9.09%   |
| 5.14.14 | 3         | 9.09%   |
| 5.16.8  | 2         | 6.06%   |
| 5.16.2  | 2         | 6.06%   |
| 5.16.1  | 2         | 6.06%   |
| 5.14.8  | 2         | 6.06%   |
| 5.17.1  | 1         | 3.03%   |
| 5.16.16 | 1         | 3.03%   |
| 5.16.14 | 1         | 3.03%   |
| 5.16.13 | 1         | 3.03%   |
| 5.16.10 | 1         | 3.03%   |
| 5.15.8  | 1         | 3.03%   |
| 5.15.26 | 1         | 3.03%   |
| 5.15.13 | 1         | 3.03%   |
| 5.15.11 | 1         | 3.03%   |
| 5.15.10 | 1         | 3.03%   |
| 5.14.12 | 1         | 3.03%   |
| 5.14.11 | 1         | 3.03%   |
| 5.10.88 | 1         | 3.03%   |
| 5.10.80 | 1         | 3.03%   |
| 5.10.71 | 1         | 3.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.16    | 14        | 43.75%  |
| 5.14    | 9         | 28.13%  |
| 5.15    | 5         | 15.63%  |
| 5.10    | 3         | 9.38%   |
| 5.17    | 1         | 3.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 30        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| KDE5  | 28        | 90.32%  |
| XFCE  | 2         | 6.45%   |
| GNOME | 1         | 3.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 23        | 76.67%  |
| Wayland | 7         | 23.33%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 18        | 54.55%  |
| LightDM | 10        | 30.3%   |
| Unknown | 5         | 15.15%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 19        | 61.29%  |
| en_IN | 4         | 12.9%   |
| pl_PL | 2         | 6.45%   |
| it_IT | 2         | 6.45%   |
| C     | 2         | 6.45%   |
| en_AU | 1         | 3.23%   |
| de_DE | 1         | 3.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 22        | 70.97%  |
| BIOS | 9         | 29.03%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 26        | 83.87%  |
| Ext4    | 3         | 9.68%   |
| Overlay | 2         | 6.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 23        | 74.19%  |
| Unknown | 5         | 16.13%  |
| MBR     | 3         | 9.68%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 29        | 90.63%  |
| Yes       | 3         | 9.38%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 21        | 70%     |
| Yes       | 9         | 30%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 9         | 30%     |
| Dell             | 6         | 20%     |
| ASUSTek Computer | 5         | 16.67%  |
| Hewlett-Packard  | 4         | 13.33%  |
| MSI              | 2         | 6.67%   |
| Pegatron         | 1         | 3.33%   |
| HUAWEI           | 1         | 3.33%   |
| Apple            | 1         | 3.33%   |
| Acer             | 1         | 3.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Pegatron D15K                            | 1         | 3.33%   |
| MSI GP73 Leopard 8RD                     | 1         | 3.33%   |
| MSI GF63 Thin 9SCX                       | 1         | 3.33%   |
| Lenovo Y520-15IKBN 80WK                  | 1         | 3.33%   |
| Lenovo ThinkPad W530 24384CU             | 1         | 3.33%   |
| Lenovo ThinkPad T460 20FMS1XX00          | 1         | 3.33%   |
| Lenovo Legion Y740-15IRHg 81UH           | 1         | 3.33%   |
| Lenovo Legion Y540-15IRH-PG0 81SY        | 1         | 3.33%   |
| Lenovo Legion 5 15ARH05H 82B1            | 1         | 3.33%   |
| Lenovo IdeaPad S145-15IIL 81W8           | 1         | 3.33%   |
| Lenovo IdeaPad 5 15ITL05 82FG            | 1         | 3.33%   |
| Lenovo IdeaPad 3 15IML05 81WR            | 1         | 3.33%   |
| HUAWEI WRT-WX9                           | 1         | 3.33%   |
| HP Notebook                              | 1         | 3.33%   |
| HP Laptop 15s-eq0xxx                     | 1         | 3.33%   |
| HP Laptop 15-da0xxx                      | 1         | 3.33%   |
| HP ENVY Sleekbook 4                      | 1         | 3.33%   |
| Dell Vostro 3590                         | 1         | 3.33%   |
| Dell Venue 11 Pro 7130 vPro              | 1         | 3.33%   |
| Dell Precision M3800                     | 1         | 3.33%   |
| Dell Latitude E6520                      | 1         | 3.33%   |
| Dell Latitude E6430                      | 1         | 3.33%   |
| Dell Latitude 7480                       | 1         | 3.33%   |
| ASUS X510UNR                             | 1         | 3.33%   |
| ASUS VivoBook_ASUSLaptop X509FJ_X509FJ   | 1         | 3.33%   |
| ASUS VivoBook_ASUS Laptop E410MA_E410MA  | 1         | 3.33%   |
| ASUS ASUS TUF Gaming F15 FX506LU_FX506LU | 1         | 3.33%   |
| ASUS ASUS EXPERTBOOK B9400CEA_B9450CEA   | 1         | 3.33%   |
| Apple MacBookAir6,2                      | 1         | 3.33%   |
| Acer Aspire A315-58G                     | 1         | 3.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo Legion      | 3         | 10%     |
| Lenovo IdeaPad     | 3         | 10%     |
| Dell Latitude      | 3         | 10%     |
| Lenovo ThinkPad    | 2         | 6.67%   |
| HP Laptop          | 2         | 6.67%   |
| ASUS VivoBook      | 2         | 6.67%   |
| ASUS ASUS          | 2         | 6.67%   |
| Pegatron D15K      | 1         | 3.33%   |
| MSI GP73           | 1         | 3.33%   |
| MSI GF63           | 1         | 3.33%   |
| Lenovo Y520-15IKBN | 1         | 3.33%   |
| HUAWEI WRT-WX9     | 1         | 3.33%   |
| HP Notebook        | 1         | 3.33%   |
| HP ENVY            | 1         | 3.33%   |
| Dell Vostro        | 1         | 3.33%   |
| Dell Venue         | 1         | 3.33%   |
| Dell Precision     | 1         | 3.33%   |
| ASUS X510UNR       | 1         | 3.33%   |
| Apple MacBookAir6  | 1         | 3.33%   |
| Acer Aspire        | 1         | 3.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 7         | 23.33%  |
| 2019 | 7         | 23.33%  |
| 2017 | 3         | 10%     |
| 2012 | 3         | 10%     |
| 2021 | 2         | 6.67%   |
| 2018 | 2         | 6.67%   |
| 2016 | 2         | 6.67%   |
| 2015 | 1         | 3.33%   |
| 2014 | 1         | 3.33%   |
| 2013 | 1         | 3.33%   |
| 2011 | 1         | 3.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 30        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 30        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 30        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 13        | 43.33%  |
| 16.01-24.0 | 6         | 20%     |
| 3.01-4.0   | 5         | 16.67%  |
| 8.01-16.0  | 4         | 13.33%  |
| 24.01-32.0 | 2         | 6.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 12        | 36.36%  |
| 1.01-2.0 | 9         | 27.27%  |
| 4.01-8.0 | 7         | 21.21%  |
| 3.01-4.0 | 4         | 12.12%  |
| 0.51-1.0 | 1         | 3.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 19        | 63.33%  |
| 2      | 11        | 36.67%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 25        | 83.33%  |
| Yes       | 5         | 16.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 23        | 76.67%  |
| No        | 7         | 23.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 96.67%  |
| No        | 1         | 3.33%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 27        | 90%     |
| No        | 3         | 10%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country               | Notebooks | Percent |
|-----------------------|-----------|---------|
| India                 | 6         | 20%     |
| USA                   | 5         | 16.67%  |
| Poland                | 2         | 6.67%   |
| Italy                 | 2         | 6.67%   |
| Greece                | 2         | 6.67%   |
| France                | 2         | 6.67%   |
| Turkey                | 1         | 3.33%   |
| Palestinian Territory | 1         | 3.33%   |
| Pakistan              | 1         | 3.33%   |
| Norway                | 1         | 3.33%   |
| Morocco               | 1         | 3.33%   |
| Mongolia              | 1         | 3.33%   |
| Malaysia              | 1         | 3.33%   |
| Hungary               | 1         | 3.33%   |
| Germany               | 1         | 3.33%   |
| Canada                | 1         | 3.33%   |
| Australia             | 1         | 3.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Vannes          | 1         | 3.23%   |
| Ulan Bator      | 1         | 3.23%   |
| Toronto         | 1         | 3.23%   |
| Taranto         | 1         | 3.23%   |
| Ramallah        | 1         | 3.23%   |
| Poznan          | 1         | 3.23%   |
| Panchkula       | 1         | 3.23%   |
| Oslo            | 1         | 3.23%   |
| Neu-Ulm         | 1         | 3.23%   |
| Mumbai          | 1         | 3.23%   |
| Melbourne       | 1         | 3.23%   |
| Madurai         | 1         | 3.23%   |
| Lucknow         | 1         | 3.23%   |
| Longmont        | 1         | 3.23%   |
| Lamia           | 1         | 3.23%   |
| Kuala Lumpur    | 1         | 3.23%   |
| Istanbul        | 1         | 3.23%   |
| Islamabad       | 1         | 3.23%   |
| Genoa           | 1         | 3.23%   |
| Gdansk          | 1         | 3.23%   |
| East Malvern    | 1         | 3.23%   |
| Dunkirk         | 1         | 3.23%   |
| Denver          | 1         | 3.23%   |
| Danville        | 1         | 3.23%   |
| Chennai         | 1         | 3.23%   |
| Casablanca      | 1         | 3.23%   |
| Budapest        | 1         | 3.23%   |
| Blairsville     | 1         | 3.23%   |
| Bhubaneswar     | 1         | 3.23%   |
| Athens          | 1         | 3.23%   |
| Aix-en-Provence | 1         | 3.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 13     | 24.39%  |
| Samsung Electronics | 7         | 7      | 17.07%  |
| WDC                 | 5         | 6      | 12.2%   |
| Toshiba             | 4         | 4      | 9.76%   |
| Micron Technology   | 2         | 3      | 4.88%   |
| Unknown             | 1         | 1      | 2.44%   |
| Sandisk             | 1         | 1      | 2.44%   |
| PLEXTOR             | 1         | 1      | 2.44%   |
| Phison              | 1         | 1      | 2.44%   |
| LITEON              | 1         | 1      | 2.44%   |
| KIOXIA              | 1         | 1      | 2.44%   |
| Kingston            | 1         | 2      | 2.44%   |
| Intenso             | 1         | 1      | 2.44%   |
| Intel               | 1         | 1      | 2.44%   |
| GOODRAM             | 1         | 1      | 2.44%   |
| Crucial             | 1         | 1      | 2.44%   |
| Apple               | 1         | 1      | 2.44%   |
| Apacer              | 1         | 1      | 2.44%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Seagate ST1000LM049-2GH172 1TB             | 2         | 4.76%   |
| Seagate ST1000LM035-1RK172 1TB             | 2         | 4.76%   |
| WDC WDS100T1X0E-00AFY0 1TB                 | 1         | 2.38%   |
| WDC PC SN720 SDAPNTW-512G-1027 512GB       | 1         | 2.38%   |
| WDC PC SN530 SDBPNPZ-256G-1114 256GB       | 1         | 2.38%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB       | 1         | 2.38%   |
| WDC PC SN520 SDAPMUW-256G-1101 256GB       | 1         | 2.38%   |
| Unknown G1J38E  64GB                       | 1         | 2.38%   |
| Toshiba MQ04ABF100 1TB                     | 1         | 2.38%   |
| Toshiba MQ01ABF050M 500GB                  | 1         | 2.38%   |
| Toshiba KBG40ZNT512G MEMORY 512GB          | 1         | 2.38%   |
| Toshiba KBG30ZMV256G 256GB                 | 1         | 2.38%   |
| Seagate ST9500325AS 500GB                  | 1         | 2.38%   |
| Seagate ST500LT012-9WS142 500GB            | 1         | 2.38%   |
| Seagate ST500LM000-SSHD-8GB                | 1         | 2.38%   |
| Seagate ST1000LM048-2E7172 1TB             | 1         | 2.38%   |
| Seagate One Touch HDD 5TB                  | 1         | 2.38%   |
| Seagate FireCuda 510 SSD ZP1000GM30031 1TB | 1         | 2.38%   |
| Seagate Expansion 320GB                    | 1         | 2.38%   |
| Sandisk NVMe SSD Drive 256GB               | 1         | 2.38%   |
| Samsung SSD 860 EVO 250GB                  | 1         | 2.38%   |
| Samsung SSD 860 EVO 1TB                    | 1         | 2.38%   |
| Samsung PM961 NVMe 1024GB                  | 1         | 2.38%   |
| Samsung MZVLB1T0HBLR-00000 1TB             | 1         | 2.38%   |
| Samsung MZVLB1T0HALR-000L2 1TB             | 1         | 2.38%   |
| Samsung MZALQ128HBHQ-000L2 128GB           | 1         | 2.38%   |
| Samsung MZ7LF128HCHP-000L1 128GB SSD       | 1         | 2.38%   |
| PLEXTOR PX-128M5M 128GB SSD                | 1         | 2.38%   |
| Phison Sabrent 1TB                         | 1         | 2.38%   |
| Micron MTFDHBA1T0TCK 1TB                   | 1         | 2.38%   |
| Micron 2210_MTFDHBA512QFD 512GB            | 1         | 2.38%   |
| LITEON LJH-128V2G-11 M.2 2260 128GB SSD    | 1         | 2.38%   |
| KIOXIA KBG30ZMV256G 256GB                  | 1         | 2.38%   |
| Kingston RBUSNS8154P3256GJ1 256GB          | 1         | 2.38%   |
| Intenso JAJMS600M1TB 1024GB                | 1         | 2.38%   |
| Intel SSDPEKNW512G8 512GB                  | 1         | 2.38%   |
| GOODRAM SSD 240GB                          | 1         | 2.38%   |
| Crucial M4-CT512M4SSD1 512GB               | 1         | 2.38%   |
| Apple SSD SM0512F 500GB                    | 1         | 2.38%   |
| Apacer AS350 256GB SSD                     | 1         | 2.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 10        | 12     | 83.33%  |
| Toshiba | 2         | 2      | 16.67%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 33.33%  |
| PLEXTOR             | 1         | 1      | 11.11%  |
| LITEON              | 1         | 1      | 11.11%  |
| GOODRAM             | 1         | 1      | 11.11%  |
| Crucial             | 1         | 1      | 11.11%  |
| Apple               | 1         | 1      | 11.11%  |
| Apacer              | 1         | 1      | 11.11%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 16        | 22     | 41.03%  |
| HDD     | 12        | 14     | 30.77%  |
| SSD     | 9         | 9      | 23.08%  |
| MMC     | 1         | 1      | 2.56%   |
| Unknown | 1         | 1      | 2.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 18        | 22     | 48.65%  |
| NVMe | 16        | 22     | 43.24%  |
| SAS  | 2         | 2      | 5.41%   |
| MMC  | 1         | 1      | 2.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 10        | 12     | 52.63%  |
| 0.51-1.0   | 8         | 10     | 42.11%  |
| 4.01-10.0  | 1         | 1      | 5.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 1001-2000      | 10        | 31.25%  |
| More than 3000 | 7         | 21.88%  |
| Unknown        | 4         | 12.5%   |
| 251-500        | 3         | 9.38%   |
| 501-1000       | 2         | 6.25%   |
| 51-100         | 2         | 6.25%   |
| 21-50          | 1         | 3.13%   |
| 2001-3000      | 1         | 3.13%   |
| 101-250        | 1         | 3.13%   |
| 1-20           | 1         | 3.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 10        | 31.25%  |
| 51-100         | 10        | 31.25%  |
| Unknown        | 4         | 12.5%   |
| 1-20           | 3         | 9.38%   |
| 501-1000       | 3         | 9.38%   |
| More than 3000 | 1         | 3.13%   |
| 21-50          | 1         | 3.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Toshiba MQ01ABF050M 500GB      | 1         | 1      | 20%     |
| Seagate ST9500325AS 500GB      | 1         | 1      | 20%     |
| Seagate ST500LM000-SSHD-8GB    | 1         | 1      | 20%     |
| Seagate ST1000LM049-2GH172 1TB | 1         | 1      | 20%     |
| Seagate ST1000LM048-2E7172 1TB | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 80%     |
| Toshiba | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 80%     |
| Toshiba | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 5      | 100%    |

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
| Works    | 23        | 32     | 65.71%  |
| Detected | 7         | 10     | 20%     |
| Malfunc  | 5         | 5      | 14.29%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 25        | 56.82%  |
| Sandisk                      | 5         | 11.36%  |
| Samsung Electronics          | 5         | 11.36%  |
| Toshiba America Info Systems | 2         | 4.55%   |
| Micron Technology            | 2         | 4.55%   |
| Seagate Technology           | 1         | 2.27%   |
| Phison Electronics           | 1         | 2.27%   |
| KIOXIA                       | 1         | 2.27%   |
| Kingston Technology Company  | 1         | 2.27%   |
| AMD                          | 1         | 2.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 8.7%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 8.7%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 6.52%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 4.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 4.35%   |
| Micron Non-Volatile memory controller                                          | 2         | 4.35%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 4.35%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                | 2         | 4.35%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 4.35%   |
| Seagate FireCuda 510 SSD                                                       | 1         | 2.17%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 2.17%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 1         | 2.17%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 2.17%   |
| Sandisk PC SN520 NVMe SSD                                                      | 1         | 2.17%   |
| Sandisk Non-Volatile memory controller                                         | 1         | 2.17%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 2.17%   |
| Samsung NVMe SSD Controller 980                                                | 1         | 2.17%   |
| Samsung Apple PCIe SSD                                                         | 1         | 2.17%   |
| Phison E12 NVMe Controller                                                     | 1         | 2.17%   |
| KIOXIA Non-Volatile memory controller                                          | 1         | 2.17%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 2.17%   |
| Intel SSD 660P Series                                                          | 1         | 2.17%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 2.17%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 2.17%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 2.17%   |
| Intel Comet Lake PCH-LP SATA RAID Premium Controller                           | 1         | 2.17%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 2.17%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 2.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 2.17%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 2.17%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 2.17%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 1         | 2.17%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 22        | 50%     |
| NVMe | 16        | 36.36%  |
| RAID | 6         | 13.64%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 28        | 93.33%  |
| AMD    | 2         | 6.67%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 6.67%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 6.67%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 6.67%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 6.67%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 3.33%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 3.33%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 3.33%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 3.33%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 3.33%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 3.33%   |
| Intel Core i7-4712HQ CPU @ 2.30GHz            | 1         | 3.33%   |
| Intel Core i7-4650U CPU @ 1.70GHz             | 1         | 3.33%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 3.33%   |
| Intel Core i7-2760QM CPU @ 2.40GHz            | 1         | 3.33%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 3.33%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 3.33%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 3.33%   |
| Intel Core i5-4300Y CPU @ 1.60GHz             | 1         | 3.33%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 1         | 3.33%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 3.33%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 3.33%   |
| Intel Core i3-6100U CPU @ 2.30GHz             | 1         | 3.33%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 3.33%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 3.33%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 1         | 3.33%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 1         | 3.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Intel Core i7 | 13        | 43.33%  |
| Intel Core i5 | 10        | 33.33%  |
| Other         | 3         | 10%     |
| Intel Core i3 | 1         | 3.33%   |
| Intel Celeron | 1         | 3.33%   |
| AMD Ryzen 7   | 1         | 3.33%   |
| AMD Ryzen 3   | 1         | 3.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 15        | 50%     |
| 2      | 11        | 36.67%  |
| 8      | 2         | 6.67%   |
| 6      | 2         | 6.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 30        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 29        | 93.55%  |
| 1      | 2         | 6.45%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 30        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 7         | 21.88%  |
| 0x906ea    | 3         | 9.38%   |
| 0x806ec    | 3         | 9.38%   |
| 0x806e9    | 3         | 9.38%   |
| 0x806c1    | 3         | 9.38%   |
| 0x306a9    | 2         | 6.25%   |
| 0xa0652    | 1         | 3.13%   |
| 0x906ed    | 1         | 3.13%   |
| 0x906e9    | 1         | 3.13%   |
| 0x806eb    | 1         | 3.13%   |
| 0x706e5    | 1         | 3.13%   |
| 0x706a8    | 1         | 3.13%   |
| 0x406e3    | 1         | 3.13%   |
| 0x40651    | 1         | 3.13%   |
| 0x206a7    | 1         | 3.13%   |
| 0x08600106 | 1         | 3.13%   |
| 0x08108109 | 1         | 3.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 14        | 46.67%  |
| TigerLake     | 3         | 10%     |
| IvyBridge     | 3         | 10%     |
| Haswell       | 3         | 10%     |
| Zen+          | 1         | 3.33%   |
| Zen 2         | 1         | 3.33%   |
| Skylake       | 1         | 3.33%   |
| SandyBridge   | 1         | 3.33%   |
| IceLake       | 1         | 3.33%   |
| Goldmont plus | 1         | 3.33%   |
| CometLake     | 1         | 3.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 28        | 58.33%  |
| Nvidia | 16        | 33.33%  |
| AMD    | 4         | 8.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 4         | 8.33%   |
| Intel HD Graphics 620                                                                 | 3         | 6.25%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 3         | 6.25%   |
| Nvidia GP108M [GeForce MX150]                                                         | 2         | 4.17%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 2         | 4.17%   |
| Intel UHD Graphics 620                                                                | 2         | 4.17%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 2         | 4.17%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 2         | 4.17%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 1         | 2.08%   |
| Nvidia TU117M                                                                         | 1         | 2.08%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 1         | 2.08%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 1         | 2.08%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                                      | 1         | 2.08%   |
| Nvidia GP108M [GeForce MX230]                                                         | 1         | 2.08%   |
| Nvidia GP107M [GeForce MX350]                                                         | 1         | 2.08%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 1         | 2.08%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 1         | 2.08%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 1         | 2.08%   |
| Nvidia GK107GLM [Quadro K1100M]                                                       | 1         | 2.08%   |
| Nvidia GK107GLM [Quadro K1000M]                                                       | 1         | 2.08%   |
| Nvidia GF119M [NVS 4200M]                                                             | 1         | 2.08%   |
| Nvidia GF108GLM [NVS 5200M]                                                           | 1         | 2.08%   |
| Intel Tiger Lake UHD Graphics                                                         | 1         | 2.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 1         | 2.08%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 1         | 2.08%   |
| Intel HD Graphics 630                                                                 | 1         | 2.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 1         | 2.08%   |
| Intel Haswell-ULT High Definition Audio Controller [HD Graphics]                      | 1         | 2.08%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 1         | 2.08%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 1         | 2.08%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 1         | 2.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 1         | 2.08%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 2.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 1         | 2.08%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                      | 1         | 2.08%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                          | 1         | 2.08%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 15        | 50%     |
| 1 x Intel      | 10        | 33.33%  |
| Intel + AMD    | 3         | 10%     |
| 1 x Nvidia     | 1         | 3.33%   |
| 1 x AMD        | 1         | 3.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 19        | 61.29%  |
| Proprietary | 12        | 38.71%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 23        | 74.19%  |
| 1.01-2.0   | 4         | 12.9%   |
| 5.01-6.0   | 2         | 6.45%   |
| 0.01-0.5   | 2         | 6.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| BOE                 | 8         | 22.86%  |
| AU Optronics        | 7         | 20%     |
| Chimei Innolux      | 6         | 17.14%  |
| Samsung Electronics | 4         | 11.43%  |
| LG Display          | 4         | 11.43%  |
| Apple               | 2         | 5.71%   |
| Sceptre Tech        | 1         | 2.86%   |
| PANDA               | 1         | 2.86%   |
| Lenovo              | 1         | 2.86%   |
| Dell                | 1         | 2.86%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 2         | 5.71%   |
| Sceptre Tech C27 SPT0ADD 1920x1080 598x336mm 27.0-inch                  | 1         | 2.86%   |
| Samsung Electronics SMBX2450L SAM071F 1920x1080 521x293mm 23.5-inch     | 1         | 2.86%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 309x174mm 14.0-inch   | 1         | 2.86%   |
| Samsung Electronics LCD Monitor SDC200F 1366x768 344x193mm 15.5-inch    | 1         | 2.86%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 1         | 2.86%   |
| PANDA LCD Monitor NCP0063 1920x1080 344x194mm 15.5-inch                 | 1         | 2.86%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch            | 1         | 2.86%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch             | 1         | 2.86%   |
| LG Display LCD Monitor LGD03D7 1366x768 310x174mm 14.0-inch             | 1         | 2.86%   |
| LG Display LCD Monitor LGD03AD 1366x768 309x174mm 14.0-inch             | 1         | 2.86%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch                | 1         | 2.86%   |
| Dell U2913WM DEL408A 2560x1080 673x284mm 28.8-inch                      | 1         | 2.86%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch        | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch        | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch        | 1         | 2.86%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 1         | 2.86%   |
| BOE LCD Monitor BOE08E7 1920x1080 344x193mm 15.5-inch                   | 1         | 2.86%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                   | 1         | 2.86%   |
| BOE LCD Monitor BOE083B 1920x1080 344x193mm 15.5-inch                   | 1         | 2.86%   |
| BOE LCD Monitor BOE0816 1366x768 344x193mm 15.5-inch                    | 1         | 2.86%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                   | 1         | 2.86%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                   | 1         | 2.86%   |
| BOE LCD Monitor BOE06D1 1366x768 309x173mm 13.9-inch                    | 1         | 2.86%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                   | 1         | 2.86%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch          | 1         | 2.86%   |
| AU Optronics LCD Monitor AUOA48F 1920x1080 309x174mm 14.0-inch          | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch          | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch           | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch          | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch          | 1         | 2.86%   |
| AU Optronics LCD Monitor AUO11ED 1920x1080 344x193mm 15.5-inch          | 1         | 2.86%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                    | 1         | 2.86%   |
| Apple Cinema HD APP9223 1920x1200 490x310mm 22.8-inch                   | 1         | 2.86%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 22        | 64.71%  |
| 1366x768 (WXGA)   | 6         | 17.65%  |
| 3840x2160 (4K)    | 1         | 2.94%   |
| 2560x1080         | 1         | 2.94%   |
| 2160x1440         | 1         | 2.94%   |
| 1920x1200 (WUXGA) | 1         | 2.94%   |
| 1600x900 (HD+)    | 1         | 2.94%   |
| 1440x900 (WXGA+)  | 1         | 2.94%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 20        | 58.82%  |
| 14     | 4         | 11.76%  |
| 13     | 4         | 11.76%  |
| 84     | 1         | 2.94%   |
| 31     | 1         | 2.94%   |
| 28     | 1         | 2.94%   |
| 23     | 1         | 2.94%   |
| 18     | 1         | 2.94%   |
| 17     | 1         | 2.94%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 26        | 74.29%  |
| 601-700     | 2         | 5.71%   |
| 401-500     | 2         | 5.71%   |
| 201-300     | 2         | 5.71%   |
| 501-600     | 1         | 2.86%   |
| 351-400     | 1         | 2.86%   |
| 1501-2000   | 1         | 2.86%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 28        | 87.5%   |
| 16/10 | 2         | 6.25%   |
| 3/2   | 1         | 3.13%   |
| 21/9  | 1         | 3.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 20        | 58.82%  |
| 81-90          | 7         | 20.59%  |
| More than 1000 | 1         | 2.94%   |
| 71-80          | 1         | 2.94%   |
| 351-500        | 1         | 2.94%   |
| 251-300        | 1         | 2.94%   |
| 201-250        | 1         | 2.94%   |
| 141-150        | 1         | 2.94%   |
| 121-130        | 1         | 2.94%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 22        | 64.71%  |
| 101-120 | 7         | 20.59%  |
| 51-100  | 4         | 11.76%  |
| 161-240 | 1         | 2.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 26        | 86.67%  |
| 2     | 3         | 10%     |
| 3     | 1         | 3.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 22        | 50%     |
| Realtek Semiconductor | 16        | 36.36%  |
| Broadcom Limited      | 2         | 4.55%   |
| ASIX Electronics      | 2         | 4.55%   |
| Samsung Electronics   | 1         | 2.27%   |
| Qualcomm Atheros      | 1         | 2.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 20.75%  |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 7.55%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 5.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 5.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 5.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 3.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 3.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 3.77%   |
| Intel Wireless 8265 / 8275                                        | 2         | 3.77%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 3.77%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 3.77%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 3.77%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.89%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 1.89%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.89%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.89%   |
| Intel Wireless-AC 9260                                            | 1         | 1.89%   |
| Intel Wireless 8260                                               | 1         | 1.89%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 1.89%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 1         | 1.89%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.89%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.89%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.89%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.89%   |
| Intel Centrino Wireless-N 2230                                    | 1         | 1.89%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 1         | 1.89%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter        | 1         | 1.89%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 22        | 75.86%  |
| Realtek Semiconductor | 5         | 17.24%  |
| Broadcom Limited      | 2         | 6.9%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Cannon Lake PCH CNVi WiFi                            | 4         | 13.79%  |
| Intel Wi-Fi 6 AX201                                        | 3         | 10.34%  |
| Intel Centrino Advanced-N 6205 [Taylor Peak]               | 3         | 10.34%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 2         | 6.9%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 2         | 6.9%    |
| Intel Wireless 8265 / 8275                                 | 2         | 6.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 2         | 6.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                   | 2         | 6.9%    |
| Realtek RTL8723DE Wireless Network Adapter                 | 1         | 3.45%   |
| Intel Wireless-AC 9260                                     | 1         | 3.45%   |
| Intel Wireless 8260                                        | 1         | 3.45%   |
| Intel Wi-Fi 6 AX200                                        | 1         | 3.45%   |
| Intel Ice Lake-LP PCH CNVi WiFi                            | 1         | 3.45%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1         | 3.45%   |
| Intel Centrino Wireless-N 2230                             | 1         | 3.45%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter | 1         | 3.45%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter | 1         | 3.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 14        | 58.33%  |
| Intel                 | 6         | 25%     |
| ASIX Electronics      | 2         | 8.33%   |
| Samsung Electronics   | 1         | 4.17%   |
| Qualcomm Atheros      | 1         | 4.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 45.83%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 12.5%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 8.33%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 8.33%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 4.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 4.17%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 4.17%   |
| Intel Ethernet Connection I219-V                                  | 1         | 4.17%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 4.17%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 4.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 29        | 55.77%  |
| Ethernet | 23        | 44.23%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 26        | 78.79%  |
| Ethernet | 7         | 21.21%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 19        | 63.33%  |
| 1     | 10        | 33.33%  |
| 0     | 1         | 3.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 22        | 73.33%  |
| Yes  | 8         | 26.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 18        | 66.67%  |
| Realtek Semiconductor | 3         | 11.11%  |
| IMC Networks          | 2         | 7.41%   |
| Broadcom              | 2         | 7.41%   |
| Dell                  | 1         | 3.7%    |
| Apple                 | 1         | 3.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 10        | 37.04%  |
| Intel AX201 Bluetooth                          | 3         | 11.11%  |
| Realtek  Bluetooth 4.2 Adapter                 | 2         | 7.41%   |
| Intel Bluetooth wireless interface             | 2         | 7.41%   |
| IMC Networks Bluetooth Radio                   | 2         | 7.41%   |
| Realtek Bluetooth Radio                        | 1         | 3.7%    |
| Intel Centrino Bluetooth Wireless Transceiver  | 1         | 3.7%    |
| Intel Bluetooth Device                         | 1         | 3.7%    |
| Intel AX200 Bluetooth                          | 1         | 3.7%    |
| Dell BCM20702A0 Bluetooth Module               | 1         | 3.7%    |
| Broadcom BCM20702A0 Bluetooth                  | 1         | 3.7%    |
| Broadcom BCM2045A0                             | 1         | 3.7%    |
| Apple Bluetooth USB Host Controller            | 1         | 3.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 28        | 73.68%  |
| Nvidia              | 7         | 18.42%  |
| AMD                 | 2         | 5.26%   |
| Samsung Electronics | 1         | 2.63%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 6         | 14.29%  |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 9.52%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 7.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 7.14%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 4.76%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 4.76%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 4.76%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 4.76%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 4.76%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 4.76%   |
| Samsung Electronics USBC Headset                                           | 1         | 2.38%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 2.38%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 2.38%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 2.38%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 2.38%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 2.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 2.38%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 2.38%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 2.38%   |
| Intel CM238 HD Audio Controller                                            | 1         | 2.38%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 2.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 2.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 2.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 12        | 34.29%  |
| Samsung Electronics | 11        | 31.43%  |
| Micron Technology   | 4         | 11.43%  |
| Kingston            | 3         | 8.57%   |
| Ramaxel Technology  | 2         | 5.71%   |
| Crucial             | 2         | 5.71%   |
| Corsair             | 1         | 2.86%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 5.56%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 2         | 5.56%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.78%   |
| SK Hynix RAM HMT41GS6MFR8C-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 2.78%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 2.78%   |
| SK Hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 2.78%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 2.78%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s        | 1         | 2.78%   |
| SK Hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 2.78%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 2.78%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 2.78%   |
| SK Hynix RAM HMA81GS6DJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 1         | 2.78%   |
| SK Hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s | 1         | 2.78%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 2.78%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 2.78%   |
| Samsung RAM M471B1G73CB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 2.78%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 2.78%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.78%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 1         | 2.78%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 1         | 2.78%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 2.78%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 2.78%   |
| Ramaxel RAM RMT3020EC58E9F1333 4GB SODIMM DDR3 4199MT/s          | 1         | 2.78%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 1         | 2.78%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 2.78%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 1         | 2.78%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB Row Of Chips DDR4 2667MT/s      | 1         | 2.78%   |
| Micron RAM 4ATF51264HZ-2G3E1 4096MB SODIMM DDR4 2667MT/s         | 1         | 2.78%   |
| Kingston RAM KHYXPX-MID 8GB SODIMM DDR4 2667MT/s                 | 1         | 2.78%   |
| Kingston RAM HP16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s            | 1         | 2.78%   |
| Kingston RAM 99U5428-069.A00LF 8GB SODIMM DDR3 1600MT/s          | 1         | 2.78%   |
| Crucial RAM CT51264BF160BJ.M8F 4GB SODIMM DDR3 1600MT/s          | 1         | 2.78%   |
| Crucial RAM CT16G4SFD824A.C16FDD 16GB SODIMM DDR4 2400MT/s       | 1         | 2.78%   |
| Corsair RAM CMSO16GX4M2A2133C15 8GB SODIMM DDR4 2667MT/s         | 1         | 2.78%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 18        | 66.67%  |
| DDR3   | 6         | 22.22%  |
| SDRAM  | 1         | 3.7%    |
| LPDDR4 | 1         | 3.7%    |
| LPDDR3 | 1         | 3.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 23        | 82.14%  |
| Row Of Chips | 5         | 17.86%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 16        | 53.33%  |
| 4096  | 12        | 40%     |
| 16384 | 2         | 6.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 14        | 43.75%  |
| 3200  | 6         | 18.75%  |
| 1600  | 6         | 18.75%  |
| 3266  | 2         | 6.25%   |
| 4267  | 1         | 3.13%   |
| 4199  | 1         | 3.13%   |
| 2400  | 1         | 3.13%   |
| 2133  | 1         | 3.13%   |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| IMC Networks                           | 6         | 20.69%  |
| Realtek Semiconductor                  | 4         | 13.79%  |
| Chicony Electronics                    | 4         | 13.79%  |
| Quanta                                 | 3         | 10.34%  |
| Acer                                   | 3         | 10.34%  |
| Syntek                                 | 2         | 6.9%    |
| Sunplus Innovation Technology          | 2         | 6.9%    |
| Microdia                               | 2         | 6.9%    |
| Lite-On Technology                     | 1         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.45%   |
| Alpha Imaging Technology               | 1         | 3.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                         | 2         | 6.9%    |
| Quanta HP TrueVision HD Camera                   | 2         | 6.9%    |
| IMC Networks USB2.0 VGA UVC WebCam               | 2         | 6.9%    |
| IMC Networks USB2.0 HD UVC WebCam                | 2         | 6.9%    |
| Chicony Integrated Camera                        | 2         | 6.9%    |
| Sunplus Laptop_Integrated_Webcam_FHD             | 1         | 3.45%   |
| Sunplus HP Truevision HD                         | 1         | 3.45%   |
| Realtek Integrated_Webcam_HD                     | 1         | 3.45%   |
| Realtek Integrated Webcam_HD                     | 1         | 3.45%   |
| Realtek Integrated Webcam                        | 1         | 3.45%   |
| Realtek Built-In Video Camera                    | 1         | 3.45%   |
| Quanta HD User Facing                            | 1         | 3.45%   |
| Microdia Integrated_Webcam_HD                    | 1         | 3.45%   |
| Microdia Dell Integrated HD Webcam               | 1         | 3.45%   |
| Lite-On Integrated Camera                        | 1         | 3.45%   |
| IMC Networks VGA UVC WebCam                      | 1         | 3.45%   |
| IMC Networks Integrated Camera                   | 1         | 3.45%   |
| Chicony HP Webcam                                | 1         | 3.45%   |
| Chicony EasyCamera                               | 1         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera | 1         | 3.45%   |
| Alpha Imaging Integrated_Webcam_8M               | 1         | 3.45%   |
| Acer ThinkPad Integrated Camera                  | 1         | 3.45%   |
| Acer SunplusIT Integrated Camera                 | 1         | 3.45%   |
| Acer HD Webcam                                   | 1         | 3.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 1         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device | 1         | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 2         | 66.67%  |
| Upek     | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor             | 2         | 66.67%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 22        | 70.97%  |
| 1     | 7         | 22.58%  |
| 2     | 2         | 6.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Chipcard              | 3         | 27.27%  |
| Graphics card         | 2         | 18.18%  |
| Camera                | 2         | 18.18%  |
| Storage               | 1         | 9.09%   |
| Network               | 1         | 9.09%   |
| Multimedia controller | 1         | 9.09%   |
| Fingerprint reader    | 1         | 9.09%   |

