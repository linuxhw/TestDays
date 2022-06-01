Xero - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------

A project to collect tested hardware configurations for Xero.

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

Total: 47

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Dell     | Inspiron 1545               | [ce0e24a314](https://linux-hardware.org/?probe=ce0e24a314) | May 28, 2022 |
| Lenovo   | IdeaPad 330-17IKB 81DM      | [53475a6004](https://linux-hardware.org/?probe=53475a6004) | May 24, 2022 |
| ASUSTek  | VivoBook_ASUSLaptop X350... | [80d32848bf](https://linux-hardware.org/?probe=80d32848bf) | May 21, 2022 |
| Dell     | Precision M3800             | [7b63874768](https://linux-hardware.org/?probe=7b63874768) | Apr 25, 2022 |
| Dell     | Precision M3800             | [fbabacd835](https://linux-hardware.org/?probe=fbabacd835) | Apr 24, 2022 |
| Lenovo   | ThinkPad X230 2325HR9       | [a9d9d3fbb2](https://linux-hardware.org/?probe=a9d9d3fbb2) | Apr 21, 2022 |
| Acer     | Aspire A515-54G             | [52b660d8fb](https://linux-hardware.org/?probe=52b660d8fb) | Apr 11, 2022 |
| Dell     | Precision M3800             | [1ef57b39a7](https://linux-hardware.org/?probe=1ef57b39a7) | Apr 10, 2022 |
| Dell     | Precision M3800             | [9fc15d1ae6](https://linux-hardware.org/?probe=9fc15d1ae6) | Mar 31, 2022 |
| MSI      | GF63 Thin 9SCX              | [4501fa1556](https://linux-hardware.org/?probe=4501fa1556) | Mar 25, 2022 |
| Dell     | Latitude 7480               | [bf00ec6a76](https://linux-hardware.org/?probe=bf00ec6a76) | Mar 23, 2022 |
| HUAWEI   | WRT-WX9                     | [70ec26bed6](https://linux-hardware.org/?probe=70ec26bed6) | Mar 22, 2022 |
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
| Xero Rolling | 30        | 78.95%  |
| Xero         | 8         | 21.05%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| Xero | 37        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 5.16.15-arch1-1              | 4         | 10%     |
| 5.17.9-arch1-1               | 2         | 5%      |
| 5.16.8-arch1-1               | 2         | 5%      |
| 5.16.2-arch1-1               | 2         | 5%      |
| 5.16.1-arch1-1               | 2         | 5%      |
| 5.15.33-1-lts                | 2         | 5%      |
| 5.14.14-arch1-1              | 2         | 5%      |
| 5.17.7-arch1-1               | 1         | 2.5%    |
| 5.17.1-arch1-1               | 1         | 2.5%    |
| 5.16.16-arch1-1              | 1         | 2.5%    |
| 5.16.14-arch1-1              | 1         | 2.5%    |
| 5.16.13-arch1-1              | 1         | 2.5%    |
| 5.16.10-arch1-1              | 1         | 2.5%    |
| 5.15.8-zen1-1-zen            | 1         | 2.5%    |
| 5.15.6-arch2-1               | 1         | 2.5%    |
| 5.15.35-1-lts                | 1         | 2.5%    |
| 5.15.26-1-lts                | 1         | 2.5%    |
| 5.15.13-arch1-1              | 1         | 2.5%    |
| 5.15.11-arch2-1              | 1         | 2.5%    |
| 5.15.10-arch1-1              | 1         | 2.5%    |
| 5.14.8-zen1-1-zen            | 1         | 2.5%    |
| 5.14.8-arch1-1               | 1         | 2.5%    |
| 5.14.16-zen1-1-zen           | 1         | 2.5%    |
| 5.14.16-arch1-2-surface      | 1         | 2.5%    |
| 5.14.16-arch1-1              | 1         | 2.5%    |
| 5.14.14-zen1-1-zen           | 1         | 2.5%    |
| 5.14.12-arch1-1              | 1         | 2.5%    |
| 5.14.11-hardened1-1-hardened | 1         | 2.5%    |
| 5.10.88-1-lts                | 1         | 2.5%    |
| 5.10.80-1-lts                | 1         | 2.5%    |
| 5.10.71-1-lts                | 1         | 2.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.16.15 | 4         | 10%     |
| 5.14.16 | 3         | 7.5%    |
| 5.14.14 | 3         | 7.5%    |
| 5.17.9  | 2         | 5%      |
| 5.16.8  | 2         | 5%      |
| 5.16.2  | 2         | 5%      |
| 5.16.1  | 2         | 5%      |
| 5.15.33 | 2         | 5%      |
| 5.14.8  | 2         | 5%      |
| 5.17.7  | 1         | 2.5%    |
| 5.17.1  | 1         | 2.5%    |
| 5.16.16 | 1         | 2.5%    |
| 5.16.14 | 1         | 2.5%    |
| 5.16.13 | 1         | 2.5%    |
| 5.16.10 | 1         | 2.5%    |
| 5.15.8  | 1         | 2.5%    |
| 5.15.6  | 1         | 2.5%    |
| 5.15.35 | 1         | 2.5%    |
| 5.15.26 | 1         | 2.5%    |
| 5.15.13 | 1         | 2.5%    |
| 5.15.11 | 1         | 2.5%    |
| 5.15.10 | 1         | 2.5%    |
| 5.14.12 | 1         | 2.5%    |
| 5.14.11 | 1         | 2.5%    |
| 5.10.88 | 1         | 2.5%    |
| 5.10.80 | 1         | 2.5%    |
| 5.10.71 | 1         | 2.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.16    | 14        | 35.9%   |
| 5.15    | 9         | 23.08%  |
| 5.14    | 9         | 23.08%  |
| 5.17    | 4         | 10.26%  |
| 5.10    | 3         | 7.69%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 37        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| KDE5  | 35        | 92.11%  |
| XFCE  | 2         | 5.26%   |
| GNOME | 1         | 2.63%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 29        | 78.38%  |
| Wayland | 8         | 21.62%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 22        | 55%     |
| LightDM | 10        | 25%     |
| Unknown | 8         | 20%     |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 24        | 63.16%  |
| en_IN | 4         | 10.53%  |
| pl_PL | 3         | 7.89%   |
| C     | 3         | 7.89%   |
| it_IT | 2         | 5.26%   |
| en_AU | 1         | 2.63%   |
| de_DE | 1         | 2.63%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 24        | 63.16%  |
| BIOS | 14        | 36.84%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 30        | 78.95%  |
| Ext4    | 4         | 10.53%  |
| Overlay | 3         | 7.89%   |
| Xfs     | 1         | 2.63%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 25        | 65.79%  |
| Unknown | 8         | 21.05%  |
| MBR     | 5         | 13.16%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 32        | 82.05%  |
| Yes       | 7         | 17.95%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 28        | 75.68%  |
| Yes       | 9         | 24.32%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 11        | 29.73%  |
| Dell             | 9         | 24.32%  |
| ASUSTek Computer | 6         | 16.22%  |
| Hewlett-Packard  | 4         | 10.81%  |
| MSI              | 2         | 5.41%   |
| Acer             | 2         | 5.41%   |
| Pegatron         | 1         | 2.7%    |
| HUAWEI           | 1         | 2.7%    |
| Apple            | 1         | 2.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Dell Precision M3800                     | 3         | 8.11%   |
| Pegatron D15K                            | 1         | 2.7%    |
| MSI GP73 Leopard 8RD                     | 1         | 2.7%    |
| MSI GF63 Thin 9SCX                       | 1         | 2.7%    |
| Lenovo Y520-15IKBN 80WK                  | 1         | 2.7%    |
| Lenovo ThinkPad X230 2325HR9             | 1         | 2.7%    |
| Lenovo ThinkPad W530 24384CU             | 1         | 2.7%    |
| Lenovo ThinkPad T460 20FMS1XX00          | 1         | 2.7%    |
| Lenovo Legion Y740-15IRHg 81UH           | 1         | 2.7%    |
| Lenovo Legion Y540-15IRH-PG0 81SY        | 1         | 2.7%    |
| Lenovo Legion 5 15ARH05H 82B1            | 1         | 2.7%    |
| Lenovo IdeaPad S145-15IIL 81W8           | 1         | 2.7%    |
| Lenovo IdeaPad 5 15ITL05 82FG            | 1         | 2.7%    |
| Lenovo IdeaPad 330-17IKB 81DM            | 1         | 2.7%    |
| Lenovo IdeaPad 3 15IML05 81WR            | 1         | 2.7%    |
| HUAWEI WRT-WX9                           | 1         | 2.7%    |
| HP Notebook                              | 1         | 2.7%    |
| HP Laptop 15s-eq0xxx                     | 1         | 2.7%    |
| HP Laptop 15-da0xxx                      | 1         | 2.7%    |
| HP ENVY Sleekbook 4                      | 1         | 2.7%    |
| Dell Vostro 3590                         | 1         | 2.7%    |
| Dell Venue 11 Pro 7130 vPro              | 1         | 2.7%    |
| Dell Latitude E6520                      | 1         | 2.7%    |
| Dell Latitude E6430                      | 1         | 2.7%    |
| Dell Latitude 7480                       | 1         | 2.7%    |
| Dell Inspiron 1545                       | 1         | 2.7%    |
| ASUS X510UNR                             | 1         | 2.7%    |
| ASUS VivoBook_ASUSLaptop X509FJ_X509FJ   | 1         | 2.7%    |
| ASUS VivoBook_ASUSLaptop X3500PC_K3500PC | 1         | 2.7%    |
| ASUS VivoBook_ASUS Laptop E410MA_E410MA  | 1         | 2.7%    |
| ASUS ASUS TUF Gaming F15 FX506LU_FX506LU | 1         | 2.7%    |
| ASUS ASUS EXPERTBOOK B9400CEA_B9450CEA   | 1         | 2.7%    |
| Apple MacBookAir6,2                      | 1         | 2.7%    |
| Acer Aspire A515-54G                     | 1         | 2.7%    |
| Acer Aspire A315-58G                     | 1         | 2.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo IdeaPad     | 4         | 10.81%  |
| Lenovo ThinkPad    | 3         | 8.11%   |
| Lenovo Legion      | 3         | 8.11%   |
| Dell Precision     | 3         | 8.11%   |
| Dell Latitude      | 3         | 8.11%   |
| ASUS VivoBook      | 3         | 8.11%   |
| HP Laptop          | 2         | 5.41%   |
| ASUS ASUS          | 2         | 5.41%   |
| Acer Aspire        | 2         | 5.41%   |
| Pegatron D15K      | 1         | 2.7%    |
| MSI GP73           | 1         | 2.7%    |
| MSI GF63           | 1         | 2.7%    |
| Lenovo Y520-15IKBN | 1         | 2.7%    |
| HUAWEI WRT-WX9     | 1         | 2.7%    |
| HP Notebook        | 1         | 2.7%    |
| HP ENVY            | 1         | 2.7%    |
| Dell Vostro        | 1         | 2.7%    |
| Dell Venue         | 1         | 2.7%    |
| Dell Inspiron      | 1         | 2.7%    |
| ASUS X510UNR       | 1         | 2.7%    |
| Apple MacBookAir6  | 1         | 2.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 8         | 21.62%  |
| 2019 | 8         | 21.62%  |
| 2012 | 4         | 10.81%  |
| 2018 | 3         | 8.11%   |
| 2017 | 3         | 8.11%   |
| 2014 | 3         | 8.11%   |
| 2021 | 2         | 5.41%   |
| 2016 | 2         | 5.41%   |
| 2015 | 1         | 2.7%    |
| 2013 | 1         | 2.7%    |
| 2011 | 1         | 2.7%    |
| 2008 | 1         | 2.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 37        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 37        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 37        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 15        | 40.54%  |
| 16.01-24.0 | 9         | 24.32%  |
| 8.01-16.0  | 6         | 16.22%  |
| 3.01-4.0   | 5         | 13.51%  |
| 24.01-32.0 | 2         | 5.41%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 16        | 40%     |
| 1.01-2.0 | 11        | 27.5%   |
| 4.01-8.0 | 7         | 17.5%   |
| 3.01-4.0 | 5         | 12.5%   |
| 0.51-1.0 | 1         | 2.5%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 23        | 62.16%  |
| 2      | 12        | 32.43%  |
| 4      | 1         | 2.7%    |
| 3      | 1         | 2.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 30        | 81.08%  |
| Yes       | 7         | 18.92%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 28        | 75.68%  |
| No        | 9         | 24.32%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 97.3%   |
| No        | 1         | 2.7%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 91.89%  |
| No        | 3         | 8.11%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country               | Notebooks | Percent |
|-----------------------|-----------|---------|
| USA                   | 9         | 24.32%  |
| India                 | 6         | 16.22%  |
| Poland                | 3         | 8.11%   |
| Germany               | 3         | 8.11%   |
| Italy                 | 2         | 5.41%   |
| Greece                | 2         | 5.41%   |
| France                | 2         | 5.41%   |
| Turkey                | 1         | 2.7%    |
| Palestinian Territory | 1         | 2.7%    |
| Pakistan              | 1         | 2.7%    |
| Norway                | 1         | 2.7%    |
| Morocco               | 1         | 2.7%    |
| Mongolia              | 1         | 2.7%    |
| Malaysia              | 1         | 2.7%    |
| Hungary               | 1         | 2.7%    |
| Canada                | 1         | 2.7%    |
| Australia             | 1         | 2.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Longmont        | 3         | 8.11%   |
| Madurai         | 2         | 5.41%   |
| Ulan Bator      | 1         | 2.7%    |
| Toronto         | 1         | 2.7%    |
| Taranto         | 1         | 2.7%    |
| Stuttgart       | 1         | 2.7%    |
| Ramallah        | 1         | 2.7%    |
| Pune            | 1         | 2.7%    |
| Poznan          | 1         | 2.7%    |
| Pirmasens       | 1         | 2.7%    |
| Pavia           | 1         | 2.7%    |
| Oslo            | 1         | 2.7%    |
| Neu-Ulm         | 1         | 2.7%    |
| Mumbai          | 1         | 2.7%    |
| Melbourne       | 1         | 2.7%    |
| Lucknow         | 1         | 2.7%    |
| Lublin          | 1         | 2.7%    |
| Longvic         | 1         | 2.7%    |
| Lamia           | 1         | 2.7%    |
| Kuala Lumpur    | 1         | 2.7%    |
| Istanbul        | 1         | 2.7%    |
| Islamabad       | 1         | 2.7%    |
| Ioannina        | 1         | 2.7%    |
| Gdansk          | 1         | 2.7%    |
| Dunkirk         | 1         | 2.7%    |
| Denver          | 1         | 2.7%    |
| Danville        | 1         | 2.7%    |
| Clearfield      | 1         | 2.7%    |
| Casablanca      | 1         | 2.7%    |
| Buffalo         | 1         | 2.7%    |
| Budapest        | 1         | 2.7%    |
| Blairsville     | 1         | 2.7%    |
| Bhubaneswar     | 1         | 2.7%    |
| Aix-en-Provence | 1         | 2.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 15     | 22.64%  |
| Samsung Electronics | 10        | 10     | 18.87%  |
| WDC                 | 6         | 7      | 11.32%  |
| Toshiba             | 4         | 4      | 7.55%   |
| Kingston            | 3         | 4      | 5.66%   |
| Unknown             | 2         | 2      | 3.77%   |
| Micron Technology   | 2         | 3      | 3.77%   |
| HGST                | 2         | 2      | 3.77%   |
| Sandisk             | 1         | 1      | 1.89%   |
| PLEXTOR             | 1         | 1      | 1.89%   |
| Phison              | 1         | 1      | 1.89%   |
| LITEONIT            | 1         | 1      | 1.89%   |
| LITEON              | 1         | 1      | 1.89%   |
| KIOXIA              | 1         | 1      | 1.89%   |
| Intenso             | 1         | 1      | 1.89%   |
| Intel               | 1         | 1      | 1.89%   |
| GOODRAM             | 1         | 1      | 1.89%   |
| Crucial             | 1         | 1      | 1.89%   |
| Apple               | 1         | 1      | 1.89%   |
| Apacer              | 1         | 1      | 1.89%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Seagate One Touch HDD 5TB                  | 3         | 5.56%   |
| Seagate ST1000LM049-2GH172 1TB             | 2         | 3.7%    |
| Seagate ST1000LM035-1RK172 1TB             | 2         | 3.7%    |
| WDC WDS100T1X0E-00AFY0 1TB                 | 1         | 1.85%   |
| WDC WDBNCE0010PNC 1TB SSD                  | 1         | 1.85%   |
| WDC PC SN720 SDAPNTW-512G-1027 512GB       | 1         | 1.85%   |
| WDC PC SN530 SDBPNPZ-256G-1114 256GB       | 1         | 1.85%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB       | 1         | 1.85%   |
| WDC PC SN520 SDAPMUW-256G-1101 256GB       | 1         | 1.85%   |
| Unknown MMC Card  64GB                     | 1         | 1.85%   |
| Unknown G1J38E  64GB                       | 1         | 1.85%   |
| Toshiba MQ04ABF100 1TB                     | 1         | 1.85%   |
| Toshiba MQ01ABF050M 500GB                  | 1         | 1.85%   |
| Toshiba KBG40ZNT512G MEMORY 512GB          | 1         | 1.85%   |
| Toshiba KBG30ZMV256G 256GB                 | 1         | 1.85%   |
| Seagate ST9500325AS 500GB                  | 1         | 1.85%   |
| Seagate ST500LT012-9WS142 500GB            | 1         | 1.85%   |
| Seagate ST500LM000-SSHD-8GB                | 1         | 1.85%   |
| Seagate ST1000LM048-2E7172 1TB             | 1         | 1.85%   |
| Seagate FireCuda 510 SSD ZP1000GM30031 1TB | 1         | 1.85%   |
| Seagate Expansion 4TB                      | 1         | 1.85%   |
| Sandisk NVMe SSD Drive 256GB               | 1         | 1.85%   |
| Samsung SSD SM841 mSATA 128GB              | 1         | 1.85%   |
| Samsung SSD 980 1TB                        | 1         | 1.85%   |
| Samsung SSD 860 EVO 250GB                  | 1         | 1.85%   |
| Samsung SSD 860 EVO 1TB                    | 1         | 1.85%   |
| Samsung SSD 850 EVO 250GB                  | 1         | 1.85%   |
| Samsung PM961 NVMe 1024GB                  | 1         | 1.85%   |
| Samsung MZVLB1T0HBLR-00000 1TB             | 1         | 1.85%   |
| Samsung MZVLB1T0HALR-000L2 1TB             | 1         | 1.85%   |
| Samsung MZALQ128HBHQ-000L2 128GB           | 1         | 1.85%   |
| Samsung MZ7LF128HCHP-000L1 128GB SSD       | 1         | 1.85%   |
| PLEXTOR PX-128M5M 128GB SSD                | 1         | 1.85%   |
| Phison Sabrent 1TB                         | 1         | 1.85%   |
| Micron MTFDHBA1T0TCK 1TB                   | 1         | 1.85%   |
| Micron 2210_MTFDHBA512QFD 512GB            | 1         | 1.85%   |
| LITEONIT LMT-128L9M-11 MSATA 128GB SSD     | 1         | 1.85%   |
| LITEON LJH-128V2G-11 M.2 2260 128GB SSD    | 1         | 1.85%   |
| KIOXIA KBG30ZMV256G 256GB                  | 1         | 1.85%   |
| Kingston SA400S37480G 480GB SSD            | 1         | 1.85%   |
| Kingston RBUSNS8154P3512GJ1 512GB          | 1         | 1.85%   |
| Kingston RBUSNS8154P3256GJ1 256GB          | 1         | 1.85%   |
| Intenso JAJMS600M1TB 1024GB                | 1         | 1.85%   |
| Intel SSDPEKNW512G8 512GB                  | 1         | 1.85%   |
| HGST HTS725032A7E630 320GB                 | 1         | 1.85%   |
| HGST HTS545050A7E680 500GB                 | 1         | 1.85%   |
| GOODRAM SSD 240GB                          | 1         | 1.85%   |
| Crucial M4-CT512M4SSD1 512GB               | 1         | 1.85%   |
| Apple SSD SM0512F 500GB                    | 1         | 1.85%   |
| Apacer AS350 256GB SSD                     | 1         | 1.85%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 12        | 14     | 75%     |
| Toshiba | 2         | 2      | 12.5%   |
| HGST    | 2         | 2      | 12.5%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 5      | 35.71%  |
| WDC                 | 1         | 1      | 7.14%   |
| PLEXTOR             | 1         | 1      | 7.14%   |
| LITEONIT            | 1         | 1      | 7.14%   |
| LITEON              | 1         | 1      | 7.14%   |
| Kingston            | 1         | 1      | 7.14%   |
| GOODRAM             | 1         | 1      | 7.14%   |
| Crucial             | 1         | 1      | 7.14%   |
| Apple               | 1         | 1      | 7.14%   |
| Apacer              | 1         | 1      | 7.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 18        | 24     | 36.73%  |
| HDD     | 15        | 18     | 30.61%  |
| SSD     | 13        | 14     | 26.53%  |
| MMC     | 2         | 2      | 4.08%   |
| Unknown | 1         | 1      | 2.04%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 23        | 29     | 48.94%  |
| NVMe | 18        | 24     | 38.3%   |
| SAS  | 4         | 4      | 8.51%   |
| MMC  | 2         | 2      | 4.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 14        | 17     | 51.85%  |
| 0.51-1.0   | 9         | 11     | 33.33%  |
| 4.01-10.0  | 3         | 3      | 11.11%  |
| 3.01-4.0   | 1         | 1      | 3.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| More than 3000 | 10        | 25.64%  |
| 1001-2000      | 10        | 25.64%  |
| Unknown        | 4         | 10.26%  |
| 251-500        | 3         | 7.69%   |
| 101-250        | 3         | 7.69%   |
| 501-1000       | 3         | 7.69%   |
| 1-20           | 2         | 5.13%   |
| 51-100         | 2         | 5.13%   |
| 21-50          | 1         | 2.56%   |
| 2001-3000      | 1         | 2.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 11        | 28.21%  |
| 51-100         | 11        | 28.21%  |
| 1-20           | 4         | 10.26%  |
| Unknown        | 4         | 10.26%  |
| 501-1000       | 3         | 7.69%   |
| 251-500        | 2         | 5.13%   |
| 21-50          | 2         | 5.13%   |
| More than 3000 | 1         | 2.56%   |
| 2001-3000      | 1         | 2.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Toshiba MQ01ABF050M 500GB      | 1         | 1      | 16.67%  |
| Seagate ST9500325AS 500GB      | 1         | 1      | 16.67%  |
| Seagate ST500LM000-SSHD-8GB    | 1         | 1      | 16.67%  |
| Seagate ST1000LM049-2GH172 1TB | 1         | 1      | 16.67%  |
| Seagate ST1000LM048-2E7172 1TB | 1         | 1      | 16.67%  |
| HGST HTS725032A7E630 320GB     | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 66.67%  |
| Toshiba | 1         | 1      | 16.67%  |
| HGST    | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 66.67%  |
| Toshiba | 1         | 1      | 16.67%  |
| HGST    | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 6      | 100%    |

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
| Works    | 26        | 35     | 61.9%   |
| Detected | 10        | 18     | 23.81%  |
| Malfunc  | 6         | 6      | 14.29%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 32        | 60.38%  |
| Samsung Electronics          | 6         | 11.32%  |
| Sandisk                      | 5         | 9.43%   |
| Toshiba America Info Systems | 2         | 3.77%   |
| Micron Technology            | 2         | 3.77%   |
| Kingston Technology Company  | 2         | 3.77%   |
| Seagate Technology           | 1         | 1.89%   |
| Phison Electronics           | 1         | 1.89%   |
| KIOXIA                       | 1         | 1.89%   |
| AMD                          | 1         | 1.89%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 9.09%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 7.27%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 5.45%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 5.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 5.45%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 5.45%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 3.64%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 3.64%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 3.64%   |
| Micron Non-Volatile memory controller                                          | 2         | 3.64%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 2         | 3.64%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                | 2         | 3.64%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 3.64%   |
| Seagate FireCuda 510 SSD                                                       | 1         | 1.82%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 1.82%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 1         | 1.82%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 1.82%   |
| Sandisk PC SN520 NVMe SSD                                                      | 1         | 1.82%   |
| Sandisk Non-Volatile memory controller                                         | 1         | 1.82%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.82%   |
| Samsung Apple PCIe SSD                                                         | 1         | 1.82%   |
| Phison E12 NVMe Controller                                                     | 1         | 1.82%   |
| KIOXIA Non-Volatile memory controller                                          | 1         | 1.82%   |
| Intel SSD 660P Series                                                          | 1         | 1.82%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 1.82%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.82%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 1.82%   |
| Intel Comet Lake PCH-LP SATA RAID Premium Controller                           | 1         | 1.82%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.82%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 1.82%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1         | 1.82%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 1.82%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 1         | 1.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 28        | 52.83%  |
| NVMe | 18        | 33.96%  |
| RAID | 7         | 13.21%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 35        | 94.59%  |
| AMD    | 2         | 5.41%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 5.41%   |
| Intel Core i7-4712HQ CPU @ 2.30GHz            | 2         | 5.41%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 5.41%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 5.41%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 5.41%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 5.41%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 5.41%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 2.7%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 2.7%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 2.7%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 2.7%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 2.7%    |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 2.7%    |
| Intel Core i7-4702HQ CPU @ 2.20GHz            | 1         | 2.7%    |
| Intel Core i7-4650U CPU @ 1.70GHz             | 1         | 2.7%    |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 2.7%    |
| Intel Core i7-2760QM CPU @ 2.40GHz            | 1         | 2.7%    |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 2.7%    |
| Intel Core i5-4300Y CPU @ 1.60GHz             | 1         | 2.7%    |
| Intel Core i5-3340M CPU @ 2.70GHz             | 1         | 2.7%    |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 2.7%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 2.7%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 2.7%    |
| Intel Core i3-6100U CPU @ 2.30GHz             | 1         | 2.7%    |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 1         | 2.7%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 2.7%    |
| Intel 11th Gen Core i5-11300H @ 3.10GHz       | 1         | 2.7%    |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 2.7%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 1         | 2.7%    |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 1         | 2.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 15        | 40.54%  |
| Intel Core i5    | 13        | 35.14%  |
| Other            | 4         | 10.81%  |
| Intel Core i3    | 1         | 2.7%    |
| Intel Core 2 Duo | 1         | 2.7%    |
| Intel Celeron    | 1         | 2.7%    |
| AMD Ryzen 7      | 1         | 2.7%    |
| AMD Ryzen 3      | 1         | 2.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 20        | 54.05%  |
| 2      | 13        | 35.14%  |
| 8      | 2         | 5.41%   |
| 6      | 2         | 5.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 37        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 35        | 92.11%  |
| 1      | 3         | 7.89%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 37        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 10        | 25.64%  |
| 0x806ec    | 4         | 10.26%  |
| 0x806c1    | 4         | 10.26%  |
| 0x906ea    | 3         | 7.69%   |
| 0x806e9    | 3         | 7.69%   |
| 0x306a9    | 3         | 7.69%   |
| 0xa0652    | 1         | 2.56%   |
| 0x906ed    | 1         | 2.56%   |
| 0x906e9    | 1         | 2.56%   |
| 0x806eb    | 1         | 2.56%   |
| 0x706e5    | 1         | 2.56%   |
| 0x706a8    | 1         | 2.56%   |
| 0x406e3    | 1         | 2.56%   |
| 0x40651    | 1         | 2.56%   |
| 0x206a7    | 1         | 2.56%   |
| 0x1067a    | 1         | 2.56%   |
| 0x08600106 | 1         | 2.56%   |
| 0x08108109 | 1         | 2.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 16        | 43.24%  |
| Haswell       | 5         | 13.51%  |
| TigerLake     | 4         | 10.81%  |
| IvyBridge     | 4         | 10.81%  |
| Zen+          | 1         | 2.7%    |
| Zen 2         | 1         | 2.7%    |
| Skylake       | 1         | 2.7%    |
| SandyBridge   | 1         | 2.7%    |
| Penryn        | 1         | 2.7%    |
| IceLake       | 1         | 2.7%    |
| Goldmont plus | 1         | 2.7%    |
| CometLake     | 1         | 2.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 35        | 59.32%  |
| Nvidia | 20        | 33.9%   |
| AMD    | 4         | 6.78%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 4         | 6.78%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 4         | 6.78%   |
| Nvidia GK107GLM [Quadro K1100M]                                                       | 3         | 5.08%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 3         | 5.08%   |
| Intel UHD Graphics 620                                                                | 3         | 5.08%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 3         | 5.08%   |
| Intel HD Graphics 620                                                                 | 3         | 5.08%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 3         | 5.08%   |
| Nvidia GP108M [GeForce MX150]                                                         | 2         | 3.39%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 2         | 3.39%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 1         | 1.69%   |
| Nvidia TU117M                                                                         | 1         | 1.69%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 1         | 1.69%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 1         | 1.69%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                                      | 1         | 1.69%   |
| Nvidia GP108M [GeForce MX250]                                                         | 1         | 1.69%   |
| Nvidia GP108M [GeForce MX230]                                                         | 1         | 1.69%   |
| Nvidia GP107M [GeForce MX350]                                                         | 1         | 1.69%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 1         | 1.69%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 1         | 1.69%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 1         | 1.69%   |
| Nvidia GK107GLM [Quadro K1000M]                                                       | 1         | 1.69%   |
| Nvidia GF119M [NVS 4200M]                                                             | 1         | 1.69%   |
| Nvidia GF108GLM [NVS 5200M]                                                           | 1         | 1.69%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 1         | 1.69%   |
| Intel Tiger Lake UHD Graphics                                                         | 1         | 1.69%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 1         | 1.69%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 1         | 1.69%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 1         | 1.69%   |
| Intel HD Graphics 630                                                                 | 1         | 1.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 1         | 1.69%   |
| Intel Haswell-ULT High Definition Audio Controller [HD Graphics]                      | 1         | 1.69%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 1         | 1.69%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 1         | 1.69%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 1         | 1.69%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 1.69%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 1         | 1.69%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                      | 1         | 1.69%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                          | 1         | 1.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 19        | 51.35%  |
| 1 x Intel      | 12        | 32.43%  |
| Intel + AMD    | 3         | 8.11%   |
| 2 x Intel      | 1         | 2.7%    |
| 1 x Nvidia     | 1         | 2.7%    |
| 1 x AMD        | 1         | 2.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 24        | 63.16%  |
| Proprietary | 14        | 36.84%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 27        | 71.05%  |
| 1.01-2.0   | 6         | 15.79%  |
| 5.01-6.0   | 2         | 5.26%   |
| 0.01-0.5   | 2         | 5.26%   |
| 3.01-4.0   | 1         | 2.63%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| BOE                 | 9         | 20%     |
| AU Optronics        | 8         | 17.78%  |
| Samsung Electronics | 7         | 15.56%  |
| LG Display          | 6         | 13.33%  |
| Chimei Innolux      | 6         | 13.33%  |
| Sharp               | 2         | 4.44%   |
| Apple               | 2         | 4.44%   |
| Sceptre Tech        | 1         | 2.22%   |
| PANDA               | 1         | 2.22%   |
| Lenovo              | 1         | 2.22%   |
| Goldstar            | 1         | 2.22%   |
| Dell                | 1         | 2.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SAM0F14 3840x2160 1872x1053mm 84.6-inch | 2         | 4.44%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 2         | 4.44%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch          | 2         | 4.44%   |
| Sharp LCD Monitor SHP1431 3840x2160 350x190mm 15.7-inch                 | 1         | 2.22%   |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch                 | 1         | 2.22%   |
| Sceptre Tech C27 SPT0ADD 1920x1080 598x336mm 27.0-inch                  | 1         | 2.22%   |
| Samsung Electronics SMBX2450L SAM071F 1920x1080 521x293mm 23.5-inch     | 1         | 2.22%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch   | 1         | 2.22%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch   | 1         | 2.22%   |
| Samsung Electronics LCD Monitor SDC200F 1366x768 344x193mm 15.5-inch    | 1         | 2.22%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 1         | 2.22%   |
| PANDA LCD Monitor NCP0063 1920x1080 344x194mm 15.5-inch                 | 1         | 2.22%   |
| LG Display LCD Monitor LGD6E01 1366x768 344x194mm 15.5-inch             | 1         | 2.22%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch            | 1         | 2.22%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch             | 1         | 2.22%   |
| LG Display LCD Monitor LGD03D7 1366x768 310x174mm 14.0-inch             | 1         | 2.22%   |
| LG Display LCD Monitor LGD03AD 1366x768 309x174mm 14.0-inch             | 1         | 2.22%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch             | 1         | 2.22%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                | 1         | 2.22%   |
| Goldstar 27EA63 GSM598B 1920x1080 600x340mm 27.2-inch                   | 1         | 2.22%   |
| Dell U2913WM DEL408A 2560x1080 673x284mm 28.8-inch                      | 1         | 2.22%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch        | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch        | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch        | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 1         | 2.22%   |
| BOE LCD Monitor BOE08E7 1920x1080 344x193mm 15.5-inch                   | 1         | 2.22%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                   | 1         | 2.22%   |
| BOE LCD Monitor BOE083B 1920x1080 344x193mm 15.5-inch                   | 1         | 2.22%   |
| BOE LCD Monitor BOE0816 1366x768 344x193mm 15.5-inch                    | 1         | 2.22%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                   | 1         | 2.22%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                   | 1         | 2.22%   |
| BOE LCD Monitor BOE06D1 1366x768 309x173mm 13.9-inch                    | 1         | 2.22%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                   | 1         | 2.22%   |
| BOE LCD Monitor BOE0685 1600x900 382x215mm 17.3-inch                    | 1         | 2.22%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch          | 1         | 2.22%   |
| AU Optronics LCD Monitor AUOA48F 1920x1080 309x174mm 14.0-inch          | 1         | 2.22%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch          | 1         | 2.22%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch           | 1         | 2.22%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x193mm 15.5-inch          | 1         | 2.22%   |
| AU Optronics LCD Monitor AUO11ED 1920x1080 344x193mm 15.5-inch          | 1         | 2.22%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                    | 1         | 2.22%   |
| Apple Cinema HD APP9223 1920x1200 495x310mm 23.0-inch                   | 1         | 2.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 25        | 58.14%  |
| 1366x768 (WXGA)   | 8         | 18.6%   |
| 3840x2160 (4K)    | 3         | 6.98%   |
| 1600x900 (HD+)    | 2         | 4.65%   |
| 3200x1800 (QHD+)  | 1         | 2.33%   |
| 2560x1080         | 1         | 2.33%   |
| 2160x1440         | 1         | 2.33%   |
| 1920x1200 (WUXGA) | 1         | 2.33%   |
| 1440x900 (WXGA+)  | 1         | 2.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 25        | 56.82%  |
| 14     | 4         | 9.09%   |
| 13     | 4         | 9.09%   |
| 84     | 3         | 6.82%   |
| 17     | 2         | 4.55%   |
| 31     | 1         | 2.27%   |
| 28     | 1         | 2.27%   |
| 27     | 1         | 2.27%   |
| 23     | 1         | 2.27%   |
| 18     | 1         | 2.27%   |
| 12     | 1         | 2.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 31        | 68.89%  |
| 201-300     | 3         | 6.67%   |
| 1501-2000   | 3         | 6.67%   |
| 601-700     | 2         | 4.44%   |
| 501-600     | 2         | 4.44%   |
| 401-500     | 2         | 4.44%   |
| 351-400     | 2         | 4.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 35        | 89.74%  |
| 16/10 | 2         | 5.13%   |
| 3/2   | 1         | 2.56%   |
| 21/9  | 1         | 2.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 25        | 56.82%  |
| 81-90          | 7         | 15.91%  |
| More than 1000 | 3         | 6.82%   |
| 121-130        | 2         | 4.55%   |
| 71-80          | 1         | 2.27%   |
| 61-70          | 1         | 2.27%   |
| 351-500        | 1         | 2.27%   |
| 301-350        | 1         | 2.27%   |
| 251-300        | 1         | 2.27%   |
| 201-250        | 1         | 2.27%   |
| 141-150        | 1         | 2.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 25        | 56.82%  |
| 101-120       | 9         | 20.45%  |
| 51-100        | 7         | 15.91%  |
| 161-240       | 2         | 4.55%   |
| More than 240 | 1         | 2.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 30        | 81.08%  |
| 2     | 6         | 16.22%  |
| 3     | 1         | 2.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 26        | 46.43%  |
| Realtek Semiconductor             | 18        | 32.14%  |
| Broadcom Limited                  | 3         | 5.36%   |
| ASIX Electronics                  | 3         | 5.36%   |
| Qualcomm Atheros                  | 2         | 3.57%   |
| Samsung Electronics               | 1         | 1.79%   |
| MEDIATEK                          | 1         | 1.79%   |
| Marvell Technology Group          | 1         | 1.79%   |
| Ericsson Business Mobile Networks | 1         | 1.79%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 13        | 19.4%   |
| Intel Cannon Lake PCH CNVi WiFi                                    | 4         | 5.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 4         | 5.97%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 3         | 4.48%   |
| Intel Wi-Fi 6 AX201                                                | 3         | 4.48%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                       | 3         | 4.48%   |
| ASIX AX88179 Gigabit Ethernet                                      | 3         | 4.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 2         | 2.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                    | 2         | 2.99%   |
| Intel Wireless 8265 / 8275                                         | 2         | 2.99%   |
| Intel Wireless 7260                                                | 2         | 2.99%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                  | 2         | 2.99%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                           | 2         | 2.99%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter         | 2         | 2.99%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)        | 1         | 1.49%   |
| Realtek RTL8723DE Wireless Network Adapter                         | 1         | 1.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 1         | 1.49%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 1         | 1.49%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller          | 1         | 1.49%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter      | 1         | 1.49%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller               | 1         | 1.49%   |
| Intel Wireless-AC 9260                                             | 1         | 1.49%   |
| Intel Wireless 8260                                                | 1         | 1.49%   |
| Intel Wi-Fi 6 AX200                                                | 1         | 1.49%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                    | 1         | 1.49%   |
| Intel Ethernet Connection I219-V                                   | 1         | 1.49%   |
| Intel Ethernet Connection (4) I219-LM                              | 1         | 1.49%   |
| Intel Ethernet Connection (13) I219-V                              | 1         | 1.49%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                    | 1         | 1.49%   |
| Intel Comet Lake PCH CNVi WiFi                                     | 1         | 1.49%   |
| Intel Centrino Wireless-N 2230                                     | 1         | 1.49%   |
| Intel Centrino Wireless-N 2200                                     | 1         | 1.49%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module | 1         | 1.49%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter         | 1         | 1.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 26        | 72.22%  |
| Realtek Semiconductor | 5         | 13.89%  |
| Broadcom Limited      | 3         | 8.33%   |
| Qualcomm Atheros      | 1         | 2.78%   |
| MEDIATEK              | 1         | 2.78%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Cannon Lake PCH CNVi WiFi                               | 4         | 11.11%  |
| Intel Wi-Fi 6 AX201                                           | 3         | 8.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 3         | 8.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 2         | 5.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 2         | 5.56%   |
| Intel Wireless 8265 / 8275                                    | 2         | 5.56%   |
| Intel Wireless 7260                                           | 2         | 5.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 2         | 5.56%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 2         | 5.56%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter    | 2         | 5.56%   |
| Realtek RTL8723DE Wireless Network Adapter                    | 1         | 2.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 1         | 2.78%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter | 1         | 2.78%   |
| Intel Wireless-AC 9260                                        | 1         | 2.78%   |
| Intel Wireless 8260                                           | 1         | 2.78%   |
| Intel Wi-Fi 6 AX200                                           | 1         | 2.78%   |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 1         | 2.78%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 1         | 2.78%   |
| Intel Comet Lake PCH CNVi WiFi                                | 1         | 2.78%   |
| Intel Centrino Wireless-N 2230                                | 1         | 2.78%   |
| Intel Centrino Wireless-N 2200                                | 1         | 2.78%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter    | 1         | 2.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 16        | 55.17%  |
| Intel                    | 7         | 24.14%  |
| ASIX Electronics         | 3         | 10.34%  |
| Samsung Electronics      | 1         | 3.45%   |
| Qualcomm Atheros         | 1         | 3.45%   |
| Marvell Technology Group | 1         | 3.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 43.33%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 13.33%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 10%     |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 10%     |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 3.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 3.33%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 3.33%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 3.33%   |
| Intel Ethernet Connection I219-V                                  | 1         | 3.33%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 3.33%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 3.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 36        | 55.38%  |
| Ethernet | 28        | 43.08%  |
| Modem    | 1         | 1.54%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 33        | 82.5%   |
| Ethernet | 7         | 17.5%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 23        | 62.16%  |
| 1     | 13        | 35.14%  |
| 0     | 1         | 2.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 25        | 67.57%  |
| Yes  | 12        | 32.43%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 21        | 61.76%  |
| Broadcom              | 4         | 11.76%  |
| Realtek Semiconductor | 3         | 8.82%   |
| IMC Networks          | 3         | 8.82%   |
| Lite-On Technology    | 1         | 2.94%   |
| Dell                  | 1         | 2.94%   |
| Apple                 | 1         | 2.94%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 10        | 29.41%  |
| Intel Bluetooth wireless interface             | 5         | 14.71%  |
| Intel AX201 Bluetooth                          | 3         | 8.82%   |
| Realtek  Bluetooth 4.2 Adapter                 | 2         | 5.88%   |
| IMC Networks Bluetooth Radio                   | 2         | 5.88%   |
| Broadcom BCM20702A0 Bluetooth                  | 2         | 5.88%   |
| Realtek Bluetooth Radio                        | 1         | 2.94%   |
| Lite-On Bluetooth Device                       | 1         | 2.94%   |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 1         | 2.94%   |
| Intel Centrino Bluetooth Wireless Transceiver  | 1         | 2.94%   |
| Intel AX200 Bluetooth                          | 1         | 2.94%   |
| IMC Networks Wireless_Device                   | 1         | 2.94%   |
| Dell BCM20702A0 Bluetooth Module               | 1         | 2.94%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 1         | 2.94%   |
| Broadcom BCM2045A0                             | 1         | 2.94%   |
| Apple Bluetooth USB Host Controller            | 1         | 2.94%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 35        | 76.09%  |
| Nvidia                | 7         | 15.22%  |
| AMD                   | 2         | 4.35%   |
| Samsung Electronics   | 1         | 2.17%   |
| Realtek Semiconductor | 1         | 2.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 7         | 13.46%  |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 7.69%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 7.69%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 7.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 5.77%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 5.77%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 5.77%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 3.85%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 3.85%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 3.85%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 3.85%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 3.85%   |
| Samsung Electronics USBC Headset                                           | 1         | 1.92%   |
| Realtek Semiconductor USB Audio                                            | 1         | 1.92%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 1.92%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.92%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 1.92%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 1.92%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 1.92%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.92%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.92%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.92%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.92%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.92%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 1.92%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1.92%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 13        | 33.33%  |
| Samsung Electronics | 12        | 30.77%  |
| Micron Technology   | 5         | 12.82%  |
| Kingston            | 3         | 7.69%   |
| Crucial             | 3         | 7.69%   |
| Ramaxel Technology  | 2         | 5.13%   |
| Corsair             | 1         | 2.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 7.5%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 5%      |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.5%    |
| SK Hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 2.5%    |
| SK Hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 2.5%    |
| SK Hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 2.5%    |
| SK Hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 2.5%    |
| SK Hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s        | 1         | 2.5%    |
| SK Hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 2.5%    |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 2.5%    |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s       | 1         | 2.5%    |
| SK Hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 2.5%    |
| SK Hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s | 1         | 2.5%    |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 2.5%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 2.5%    |
| Samsung RAM M471B1G73CB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 1         | 2.5%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 2.5%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.5%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.5%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 2.5%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 2.5%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 2.5%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.5%    |
| Ramaxel RAM RMT3020EC58E9F1333 4096MB SODIMM DDR3 4199MT/s       | 1         | 2.5%    |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 1         | 2.5%    |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 2.5%    |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 1         | 2.5%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB Row Of Chips DDR4 2667MT/s      | 1         | 2.5%    |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2667MT/s            | 1         | 2.5%    |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 1         | 2.5%    |
| Kingston RAM KHYXPX-MID 8192MB SODIMM DDR4 2667MT/s              | 1         | 2.5%    |
| Kingston RAM HP16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s            | 1         | 2.5%    |
| Kingston RAM 99U5428-069.A00LF 8GB SODIMM DDR3 1600MT/s          | 1         | 2.5%    |
| Crucial RAM Module 4GB SODIMM DDR 800MT/s                        | 1         | 2.5%    |
| Crucial RAM CT51264BF160BJ.M8F 4GB SODIMM DDR3 1600MT/s          | 1         | 2.5%    |
| Crucial RAM CT16G4SFD824A.C16FDD 16384MB SODIMM DDR4 2400MT/s    | 1         | 2.5%    |
| Corsair RAM CMSO16GX4M2A2133C15 8GB SODIMM DDR4 2667MT/s         | 1         | 2.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 20        | 64.52%  |
| DDR3   | 7         | 22.58%  |
| SDRAM  | 1         | 3.23%   |
| LPDDR4 | 1         | 3.23%   |
| LPDDR3 | 1         | 3.23%   |
| DDR    | 1         | 3.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 27        | 84.38%  |
| Row Of Chips | 5         | 15.63%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 18        | 52.94%  |
| 4096  | 14        | 41.18%  |
| 16384 | 2         | 5.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 15        | 41.67%  |
| 3200  | 7         | 19.44%  |
| 1600  | 7         | 19.44%  |
| 3266  | 2         | 5.56%   |
| 4267  | 1         | 2.78%   |
| 4199  | 1         | 2.78%   |
| 2400  | 1         | 2.78%   |
| 2133  | 1         | 2.78%   |
| 800   | 1         | 2.78%   |

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
| IMC Networks                           | 8         | 22.22%  |
| Realtek Semiconductor                  | 6         | 16.67%  |
| Chicony Electronics                    | 5         | 13.89%  |
| Acer                                   | 4         | 11.11%  |
| Quanta                                 | 3         | 8.33%   |
| Syntek                                 | 2         | 5.56%   |
| Sunplus Innovation Technology          | 2         | 5.56%   |
| Microdia                               | 2         | 5.56%   |
| Ricoh                                  | 1         | 2.78%   |
| Lite-On Technology                     | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.78%   |
| Alpha Imaging Technology               | 1         | 2.78%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                     | 3         | 8.33%   |
| IMC Networks USB2.0 HD UVC WebCam                | 3         | 8.33%   |
| Syntek Integrated Camera                         | 2         | 5.56%   |
| Quanta HP TrueVision HD Camera                   | 2         | 5.56%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 2         | 5.56%   |
| Chicony Integrated Camera                        | 2         | 5.56%   |
| Acer ThinkPad Integrated Camera                  | 2         | 5.56%   |
| Sunplus Laptop_Integrated_Webcam_FHD             | 1         | 2.78%   |
| Sunplus HP Truevision HD                         | 1         | 2.78%   |
| Ricoh Integrated Webcam                          | 1         | 2.78%   |
| Realtek Integrated Webcam_HD                     | 1         | 2.78%   |
| Realtek Integrated Webcam                        | 1         | 2.78%   |
| Realtek Built-In Video Camera                    | 1         | 2.78%   |
| Quanta HD User Facing                            | 1         | 2.78%   |
| Microdia Integrated_Webcam_HD                    | 1         | 2.78%   |
| Microdia Dell Integrated HD Webcam               | 1         | 2.78%   |
| Lite-On Integrated Camera                        | 1         | 2.78%   |
| IMC Networks VGA UVC WebCam                      | 1         | 2.78%   |
| IMC Networks Integrated Camera                   | 1         | 2.78%   |
| IMC Networks EasyCamera                          | 1         | 2.78%   |
| Chicony HP Webcam                                | 1         | 2.78%   |
| Chicony HD User Facing                           | 1         | 2.78%   |
| Chicony EasyCamera                               | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera | 1         | 2.78%   |
| Alpha Imaging Integrated_Webcam_8M               | 1         | 2.78%   |
| Acer SunplusIT Integrated Camera                 | 1         | 2.78%   |
| Acer HD Webcam                                   | 1         | 2.78%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 1         | 50%     |
| Elan Microelectronics      | 1         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device | 1         | 50%     |
| Elan ELAN:Fingerprint               | 1         | 50%     |

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
| 0     | 27        | 71.05%  |
| 1     | 8         | 21.05%  |
| 2     | 3         | 7.89%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 4         | 28.57%  |
| Chipcard              | 3         | 21.43%  |
| Fingerprint reader    | 2         | 14.29%  |
| Camera                | 2         | 14.29%  |
| Storage               | 1         | 7.14%   |
| Network               | 1         | 7.14%   |
| Multimedia controller | 1         | 7.14%   |

