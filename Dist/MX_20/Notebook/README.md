MX 20 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for MX 20.

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

Total: 48

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| UMAX     | VisionBook-N12R             | [9ccb1f57ab](https://linux-hardware.org/?probe=9ccb1f57ab) | Jul 16, 2022 |
| HP       | 2000                        | [5d64fe5b92](https://linux-hardware.org/?probe=5d64fe5b92) | Jan 01, 2022 |
| Unknown  | Unknown                     | [381b31199f](https://linux-hardware.org/?probe=381b31199f) | Nov 18, 2021 |
| Dell     | Inspiron 3576               | [ad9fb758a6](https://linux-hardware.org/?probe=ad9fb758a6) | Nov 09, 2021 |
| Lenovo   | ThinkPad L520 78595VG       | [4aff5a6a0c](https://linux-hardware.org/?probe=4aff5a6a0c) | Oct 24, 2021 |
| Lenovo   | ThinkPad T530 2394CJ9       | [b36a94241d](https://linux-hardware.org/?probe=b36a94241d) | Oct 05, 2021 |
| Lenovo   | ThinkPad X1 Carbon 5th 2... | [c86e0b677e](https://linux-hardware.org/?probe=c86e0b677e) | Oct 03, 2021 |
| Lenovo   | ThinkPad L490 20Q5S0PR00    | [bbf6b89f02](https://linux-hardware.org/?probe=bbf6b89f02) | Oct 01, 2021 |
| Acer     | Aspire 4820T                | [a91911ca90](https://linux-hardware.org/?probe=a91911ca90) | Oct 01, 2021 |
| Lenovo   | ThinkPad P51 20HJS0TP00     | [2774c819ea](https://linux-hardware.org/?probe=2774c819ea) | Sep 18, 2021 |
| Lenovo   | B40-45 20394                | [627672a7ec](https://linux-hardware.org/?probe=627672a7ec) | Sep 16, 2021 |
| HP       | Pavilion Laptop 15-eg0xx... | [e76ffa7805](https://linux-hardware.org/?probe=e76ffa7805) | Sep 06, 2021 |
| Dell     | Latitude 3340               | [c47b83476b](https://linux-hardware.org/?probe=c47b83476b) | Jul 12, 2021 |
| Acer     | Aspire one                  | [2c266e91ae](https://linux-hardware.org/?probe=2c266e91ae) | Jul 09, 2021 |
| Irbis    | TW94                        | [dc56e23810](https://linux-hardware.org/?probe=dc56e23810) | May 15, 2021 |
| Dell     | Latitude E6320              | [fa8bcef5a9](https://linux-hardware.org/?probe=fa8bcef5a9) | May 09, 2021 |
| Lenovo   | ThinkPad T440s 20AQ007SG... | [73f2bd0075](https://linux-hardware.org/?probe=73f2bd0075) | Apr 16, 2021 |
| Lenovo   | ThinkPad T440s 20AQ007SG... | [75e60ebdf4](https://linux-hardware.org/?probe=75e60ebdf4) | Apr 16, 2021 |
| Lenovo   | ThinkPad E480 20KNCTO1WW    | [7159579bb8](https://linux-hardware.org/?probe=7159579bb8) | Apr 12, 2021 |
| ASUSTek  | G751JT                      | [4f88289a8c](https://linux-hardware.org/?probe=4f88289a8c) | Apr 08, 2021 |
| HP       | Falco                       | [9bb0bf9ac8](https://linux-hardware.org/?probe=9bb0bf9ac8) | Apr 07, 2021 |
| HP       | ZBook 17 G6                 | [046176e590](https://linux-hardware.org/?probe=046176e590) | Mar 16, 2021 |
| Lenovo   | ThinkPad E425 1198CTO       | [67304f1ffa](https://linux-hardware.org/?probe=67304f1ffa) | Feb 22, 2021 |
| HP       | Mini 110-3500               | [bb5cf4031b](https://linux-hardware.org/?probe=bb5cf4031b) | Feb 13, 2021 |
| HP       | Notebook                    | [69f70d7a09](https://linux-hardware.org/?probe=69f70d7a09) | Feb 10, 2021 |
| Apple    | MacBook7,1                  | [a6324a9e06](https://linux-hardware.org/?probe=a6324a9e06) | Feb 05, 2021 |
| Clevo    | P170EM                      | [eff7a04dad](https://linux-hardware.org/?probe=eff7a04dad) | Feb 02, 2021 |
| HP       | Mini 110-3500               | [3c2a01636e](https://linux-hardware.org/?probe=3c2a01636e) | Jan 19, 2021 |
| HP       | ENVY Laptop 13-ba0xxx       | [32692a5980](https://linux-hardware.org/?probe=32692a5980) | Nov 18, 2020 |
| Acer     | Aspire E5-571G              | [7f5f7e9fff](https://linux-hardware.org/?probe=7f5f7e9fff) | Nov 17, 2020 |
| Lenovo   | IdeaPad 110-15IBR 80T7      | [470c0ca72b](https://linux-hardware.org/?probe=470c0ca72b) | Oct 23, 2020 |
| HP       | Compaq 8510p (KM229AV)      | [30634ffde6](https://linux-hardware.org/?probe=30634ffde6) | Oct 12, 2020 |
| HP       | Pavilion 15                 | [8e6632f1a3](https://linux-hardware.org/?probe=8e6632f1a3) | Oct 06, 2020 |
| Lenovo   | ThinkPad T400 2768WGB       | [995b1a3a3d](https://linux-hardware.org/?probe=995b1a3a3d) | Sep 29, 2020 |
| Lenovo   | ThinkPad T60 20085TG        | [31cd0f06c2](https://linux-hardware.org/?probe=31cd0f06c2) | Sep 16, 2020 |
| Samsung  | 350V5C/351V5C/3540VC/344... | [356bacc97a](https://linux-hardware.org/?probe=356bacc97a) | Aug 27, 2020 |
| Acer     | Aspire A114-32              | [7f178a7089](https://linux-hardware.org/?probe=7f178a7089) | Aug 20, 2020 |
| Samsung  | 350V5C/351V5C/3540VC/344... | [9b4d2c057e](https://linux-hardware.org/?probe=9b4d2c057e) | Aug 19, 2020 |
| ASUSTek  | VivoBook 15_ASUS Laptop ... | [57e274292b](https://linux-hardware.org/?probe=57e274292b) | Aug 16, 2020 |
| HP       | ProBook 650 G1              | [9a488079c3](https://linux-hardware.org/?probe=9a488079c3) | Jul 23, 2020 |
| Lenovo   | ThinkPad T440s 20AQ006HU... | [54a69351ae](https://linux-hardware.org/?probe=54a69351ae) | Jun 17, 2020 |
| Sony     | VGN-NR310FH                 | [c774d0a51a](https://linux-hardware.org/?probe=c774d0a51a) | Jun 05, 2020 |
| Acer     | Aspire A315-41              | [665b2837c7](https://linux-hardware.org/?probe=665b2837c7) | May 27, 2020 |
| ASUSTek  | VivoBook_ASUSLaptop X712... | [c85746245d](https://linux-hardware.org/?probe=c85746245d) | May 26, 2020 |
| Lenovo   | B590 20206                  | [8f4a7e2b6e](https://linux-hardware.org/?probe=8f4a7e2b6e) | May 26, 2020 |
| ASUSTek  | X455LAB                     | [4a5174a726](https://linux-hardware.org/?probe=4a5174a726) | Mar 24, 2020 |
| Notebook | W65_W67RZ1                  | [aaffd10ebf](https://linux-hardware.org/?probe=aaffd10ebf) | Mar 24, 2020 |
| Medion   | Akoya E1318T                | [d6be35c8af](https://linux-hardware.org/?probe=d6be35c8af) | Mar 20, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Notebooks | Percent |
|---------------------------|-----------|---------|
| 4.19.0-6-amd64            | 8         | 18.6%   |
| 5.10.0-5mx-amd64          | 6         | 13.95%  |
| 5.8.0-3-amd64             | 4         | 9.3%    |
| 4.19.0-16-amd64           | 3         | 6.98%   |
| 4.19.0-11-amd64           | 3         | 6.98%   |
| 4.19.0-17-amd64           | 2         | 4.65%   |
| 5.8.16-antix.1-amd64-smp  | 1         | 2.33%   |
| 5.6.0-2-amd64             | 1         | 2.33%   |
| 5.6.0-15.2-liquorix-amd64 | 1         | 2.33%   |
| 5.6.0-12.1-liquorix-amd64 | 1         | 2.33%   |
| 5.5.0-9.1-liquorix-amd64  | 1         | 2.33%   |
| 5.4.0-3-amd64             | 1         | 2.33%   |
| 5.10.0-8mx-amd64          | 1         | 2.33%   |
| 5.10.0-6.2-liquorix-amd64 | 1         | 2.33%   |
| 4.19.174                  | 1         | 2.33%   |
| 4.19.0-9-amd64            | 1         | 2.33%   |
| 4.19.0-17-686-pae         | 1         | 2.33%   |
| 4.19.0-16-686-pae         | 1         | 2.33%   |
| 4.19.0-14-amd64           | 1         | 2.33%   |
| 4.19.0-13-amd64           | 1         | 2.33%   |
| 4.19.0-12-amd64           | 1         | 2.33%   |
| 4.19.0-10-amd64           | 1         | 2.33%   |
| 4.19.0-10-686-pae         | 1         | 2.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 4.19.0   | 24        | 55.81%  |
| 5.10.0   | 8         | 18.6%   |
| 5.8.0    | 4         | 9.3%    |
| 5.6.0    | 3         | 6.98%   |
| 5.8.16   | 1         | 2.33%   |
| 5.5.0    | 1         | 2.33%   |
| 5.4.0    | 1         | 2.33%   |
| 4.19.174 | 1         | 2.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.19    | 25        | 58.14%  |
| 5.10    | 8         | 18.6%   |
| 5.8     | 5         | 11.63%  |
| 5.6     | 3         | 6.98%   |
| 5.5     | 1         | 2.33%   |
| 5.4     | 1         | 2.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 40        | 93.02%  |
| i686   | 3         | 6.98%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| XFCE     | 34        | 79.07%  |
| KDE5     | 4         | 9.3%    |
| i3       | 2         | 4.65%   |
| Trinity  | 1         | 2.33%   |
| spectrwm | 1         | 2.33%   |
| Budgie   | 1         | 2.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 42        | 97.67%  |
| Tty  | 1         | 2.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 35        | 81.4%   |
| TDM     | 4         | 9.3%    |
| SDDM    | 4         | 9.3%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 24        | 55.81%  |
| en_US   | 10        | 23.26%  |
| es_ES   | 2         | 4.65%   |
| en_GB   | 2         | 4.65%   |
| de_DE   | 2         | 4.65%   |
| es_VE   | 1         | 2.33%   |
| es_CO   | 1         | 2.33%   |
| en_IE   | 1         | 2.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 22        | 51.16%  |
| BIOS | 21        | 48.84%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 37        | 86.05%  |
| Overlay | 4         | 9.3%    |
| Xfs     | 1         | 2.33%   |
| Btrfs   | 1         | 2.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 24        | 55.81%  |
| MBR  | 19        | 44.19%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 37        | 84.09%  |
| Yes       | 7         | 15.91%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 31        | 72.09%  |
| Yes       | 12        | 27.91%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 14        | 32.56%  |
| Hewlett-Packard  | 10        | 23.26%  |
| Acer             | 5         | 11.63%  |
| Dell             | 3         | 6.98%   |
| ASUSTek Computer | 3         | 6.98%   |
| UMAX             | 1         | 2.33%   |
| Sony             | 1         | 2.33%   |
| Notebook         | 1         | 2.33%   |
| Medion           | 1         | 2.33%   |
| Irbis            | 1         | 2.33%   |
| Clevo            | 1         | 2.33%   |
| Apple            | 1         | 2.33%   |
| Unknown          | 1         | 2.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| UMAX VisionBook-N12R                     | 1         | 2.33%   |
| Sony VGN-NR310FH                         | 1         | 2.33%   |
| Notebook W65_W67RZ1                      | 1         | 2.33%   |
| Medion Akoya E1318T                      | 1         | 2.33%   |
| Lenovo ThinkPad X1 Carbon 5th 20HR0013AU | 1         | 2.33%   |
| Lenovo ThinkPad T60 20085TG              | 1         | 2.33%   |
| Lenovo ThinkPad T530 2394CJ9             | 1         | 2.33%   |
| Lenovo ThinkPad T440s 20AQ007SGE         | 1         | 2.33%   |
| Lenovo ThinkPad T440s 20AQ006HUS         | 1         | 2.33%   |
| Lenovo ThinkPad T400 2768WGB             | 1         | 2.33%   |
| Lenovo ThinkPad P51 20HJS0TP00           | 1         | 2.33%   |
| Lenovo ThinkPad L520 78595VG             | 1         | 2.33%   |
| Lenovo ThinkPad L490 20Q5S0PR00          | 1         | 2.33%   |
| Lenovo ThinkPad E480 20KNCTO1WW          | 1         | 2.33%   |
| Lenovo ThinkPad E425 1198CTO             | 1         | 2.33%   |
| Lenovo IdeaPad 110-15IBR 80T7            | 1         | 2.33%   |
| Lenovo B590 20206                        | 1         | 2.33%   |
| Lenovo B40-45 20394                      | 1         | 2.33%   |
| Irbis TW94                               | 1         | 2.33%   |
| HP ZBook 17 G6                           | 1         | 2.33%   |
| HP ProBook 650 G1                        | 1         | 2.33%   |
| HP Pavilion Laptop 15-eg0xxx             | 1         | 2.33%   |
| HP Pavilion 15                           | 1         | 2.33%   |
| HP Notebook                              | 1         | 2.33%   |
| HP Mini 110-3500                         | 1         | 2.33%   |
| HP Falco                                 | 1         | 2.33%   |
| HP ENVY Laptop 13-ba0xxx                 | 1         | 2.33%   |
| HP Compaq 8510p (KM229AV)                | 1         | 2.33%   |
| HP 2000                                  | 1         | 2.33%   |
| Dell Latitude E6320                      | 1         | 2.33%   |
| Dell Latitude 3340                       | 1         | 2.33%   |
| Dell Inspiron 3576                       | 1         | 2.33%   |
| Clevo P170EM                             | 1         | 2.33%   |
| ASUS X455LAB                             | 1         | 2.33%   |
| ASUS VivoBook_ASUSLaptop X712DA_M712DA   | 1         | 2.33%   |
| ASUS VivoBook 15_ASUS Laptop X542UF      | 1         | 2.33%   |
| Apple MacBook7,1                         | 1         | 2.33%   |
| Acer Aspire one                          | 1         | 2.33%   |
| Acer Aspire E5-571G                      | 1         | 2.33%   |
| Acer Aspire A315-41                      | 1         | 2.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 11        | 25.58%  |
| Acer Aspire          | 5         | 11.63%  |
| HP Pavilion          | 2         | 4.65%   |
| Dell Latitude        | 2         | 4.65%   |
| ASUS VivoBook        | 2         | 4.65%   |
| UMAX VisionBook-N12R | 1         | 2.33%   |
| Sony VGN-NR310FH     | 1         | 2.33%   |
| Notebook W65         | 1         | 2.33%   |
| Medion Akoya         | 1         | 2.33%   |
| Lenovo IdeaPad       | 1         | 2.33%   |
| Lenovo B590          | 1         | 2.33%   |
| Lenovo B40-45        | 1         | 2.33%   |
| Irbis TW94           | 1         | 2.33%   |
| HP ZBook             | 1         | 2.33%   |
| HP ProBook           | 1         | 2.33%   |
| HP Notebook          | 1         | 2.33%   |
| HP Mini              | 1         | 2.33%   |
| HP Falco             | 1         | 2.33%   |
| HP ENVY              | 1         | 2.33%   |
| HP Compaq            | 1         | 2.33%   |
| HP 2000              | 1         | 2.33%   |
| Dell Inspiron        | 1         | 2.33%   |
| Clevo P170EM         | 1         | 2.33%   |
| ASUS X455LAB         | 1         | 2.33%   |
| Apple MacBook7       | 1         | 2.33%   |
| Unknown              | 1         | 2.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 6         | 13.95%  |
| 2014 | 5         | 11.63%  |
| 2019 | 4         | 9.3%    |
| 2018 | 4         | 9.3%    |
| 2017 | 4         | 9.3%    |
| 2012 | 3         | 6.98%   |
| 2011 | 3         | 6.98%   |
| 2010 | 3         | 6.98%   |
| 2008 | 3         | 6.98%   |
| 2020 | 2         | 4.65%   |
| 2016 | 2         | 4.65%   |
| 2021 | 1         | 2.33%   |
| 2015 | 1         | 2.33%   |
| 2009 | 1         | 2.33%   |
| 2006 | 1         | 2.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 43        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 43        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 42        | 97.67%  |
| Yes  | 1         | 2.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 13        | 30.23%  |
| 4.01-8.0   | 11        | 25.58%  |
| 8.01-16.0  | 6         | 13.95%  |
| 1.01-2.0   | 5         | 11.63%  |
| 16.01-24.0 | 3         | 6.98%   |
| 32.01-64.0 | 2         | 4.65%   |
| 2.01-3.0   | 2         | 4.65%   |
| 24.01-32.0 | 1         | 2.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 19        | 43.18%  |
| 3.01-4.0  | 9         | 20.45%  |
| 2.01-3.0  | 9         | 20.45%  |
| 0.51-1.0  | 5         | 11.36%  |
| 4.01-8.0  | 1         | 2.27%   |
| 8.01-16.0 | 1         | 2.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 37        | 86.05%  |
| 2      | 3         | 6.98%   |
| 3      | 2         | 4.65%   |
| 4      | 1         | 2.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 24        | 55.81%  |
| Yes       | 19        | 44.19%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 88.37%  |
| No        | 5         | 11.63%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 42        | 97.67%  |
| No        | 1         | 2.33%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 67.44%  |
| No        | 14        | 32.56%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 6         | 13.95%  |
| Germany     | 6         | 13.95%  |
| Spain       | 3         | 6.98%   |
| India       | 3         | 6.98%   |
| Russia      | 2         | 4.65%   |
| Netherlands | 2         | 4.65%   |
| Mexico      | 2         | 4.65%   |
| Canada      | 2         | 4.65%   |
| Vietnam     | 1         | 2.33%   |
| Venezuela   | 1         | 2.33%   |
| UK          | 1         | 2.33%   |
| Turkey      | 1         | 2.33%   |
| Syria       | 1         | 2.33%   |
| Slovakia    | 1         | 2.33%   |
| Portugal    | 1         | 2.33%   |
| Poland      | 1         | 2.33%   |
| Norway      | 1         | 2.33%   |
| Hungary     | 1         | 2.33%   |
| France      | 1         | 2.33%   |
| Finland     | 1         | 2.33%   |
| Czechia     | 1         | 2.33%   |
| Colombia    | 1         | 2.33%   |
| Brazil      | 1         | 2.33%   |
| Australia   | 1         | 2.33%   |
| Angola      | 1         | 2.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Patna             | 2         | 4.65%   |
| Munich            | 2         | 4.65%   |
| Madrid            | 2         | 4.65%   |
| Trivandrum        | 1         | 2.33%   |
| Tampa             | 1         | 2.33%   |
| Siegen            | 1         | 2.33%   |
| Rusko             | 1         | 2.33%   |
| Rensselaer        | 1         | 2.33%   |
| Prague            | 1         | 2.33%   |
| Porto             | 1         | 2.33%   |
| Perm              | 1         | 2.33%   |
| Newmarket         | 1         | 2.33%   |
| Münster          | 1         | 2.33%   |
| Montreal          | 1         | 2.33%   |
| Monterrey         | 1         | 2.33%   |
| Mexico City       | 1         | 2.33%   |
| Madison           | 1         | 2.33%   |
| Lublin            | 1         | 2.33%   |
| Luanda            | 1         | 2.33%   |
| Los Angeles       | 1         | 2.33%   |
| Lobnya            | 1         | 2.33%   |
| Lille             | 1         | 2.33%   |
| Leipzig           | 1         | 2.33%   |
| Krupina           | 1         | 2.33%   |
| Kartal            | 1         | 2.33%   |
| Ho Chi Minh City  | 1         | 2.33%   |
| Geelong           | 1         | 2.33%   |
| Gargan            | 1         | 2.33%   |
| Damascus          | 1         | 2.33%   |
| Cowfold           | 1         | 2.33%   |
| Cedar Rapids      | 1         | 2.33%   |
| Carl Junction     | 1         | 2.33%   |
| Caracas           | 1         | 2.33%   |
| Budapest          | 1         | 2.33%   |
| Breedenbroek      | 1         | 2.33%   |
| Bogotá           | 1         | 2.33%   |
| Bergisch Gladbach | 1         | 2.33%   |
| Arujá            | 1         | 2.33%   |
| Arroyomolinos     | 1         | 2.33%   |
| Amsterdam         | 1         | 2.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 8      | 14.58%  |
| Samsung Electronics | 7         | 10     | 14.58%  |
| Seagate             | 5         | 6      | 10.42%  |
| SanDisk             | 4         | 4      | 8.33%   |
| Kingston            | 4         | 4      | 8.33%   |
| Toshiba             | 3         | 3      | 6.25%   |
| Hitachi             | 3         | 3      | 6.25%   |
| HGST                | 3         | 3      | 6.25%   |
| Yeyian              | 1         | 1      | 2.08%   |
| Unknown             | 1         | 1      | 2.08%   |
| SPCC                | 1         | 1      | 2.08%   |
| SK hynix            | 1         | 1      | 2.08%   |
| Lenovo              | 1         | 1      | 2.08%   |
| Intenso             | 1         | 1      | 2.08%   |
| Intel               | 1         | 1      | 2.08%   |
| Indilinx            | 1         | 2      | 2.08%   |
| HUAWEI              | 1         | 1      | 2.08%   |
| Fujitsu             | 1         | 1      | 2.08%   |
| Crucial             | 1         | 1      | 2.08%   |
| Unknown             | 1         | 1      | 2.08%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB            | 2         | 3.85%   |
| Yeyian VALK 1000 120GB SSD           | 1         | 1.92%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 1.92%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 1         | 1.92%   |
| WDC WD3200LPVT-08G33T1 320GB         | 1         | 1.92%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 1         | 1.92%   |
| WDC WD10SPZX-80Z10T2 1TB             | 1         | 1.92%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 1         | 1.92%   |
| WDC PC SN520 SDAPNUW-512G-1006 512GB | 1         | 1.92%   |
| WDC PC SN520 SDAPNUW-256G-1102 256GB | 1         | 1.92%   |
| Unknown 064G30  64GB                 | 1         | 1.92%   |
| Toshiba THNSFJ256GCSU 256GB SSD      | 1         | 1.92%   |
| Toshiba MQ01ACF050 500GB             | 1         | 1.92%   |
| Toshiba KXG60ZNV512G KIOXIA 512GB    | 1         | 1.92%   |
| SPCC Solid State Disk 240GB          | 1         | 1.92%   |
| SK hynix SC311 SATA 256GB SSD        | 1         | 1.92%   |
| Seagate ST9500420AS 500GB            | 1         | 1.92%   |
| Seagate ST9500325AS 500GB            | 1         | 1.92%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 1         | 1.92%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 1.92%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 1         | 1.92%   |
| Seagate BUP BK 4TB                   | 1         | 1.92%   |
| SanDisk SSD PLUS 480G                | 1         | 1.92%   |
| SanDisk SDSSDHII120G 120GB           | 1         | 1.92%   |
| SanDisk SDSSDA120G 120GB             | 1         | 1.92%   |
| SanDisk DF4064  64GB                 | 1         | 1.92%   |
| Samsung SSD 860 EVO mSATA 500GB      | 1         | 1.92%   |
| Samsung SSD 850 EVO 500GB            | 1         | 1.92%   |
| Samsung SSD 840 Series 500GB         | 1         | 1.92%   |
| Samsung SSD 840 EVO 250GB            | 1         | 1.92%   |
| Samsung MZVLW512HMJP-000L7 512GB     | 1         | 1.92%   |
| Samsung MZVKW512HMJP-000L7 512GB     | 1         | 1.92%   |
| Samsung MZAPF032HCFV-000H1 32GB SSD  | 1         | 1.92%   |
| Lenovo LENSE20256GMSP34MEAT2TA 256GB | 1         | 1.92%   |
| Kingston SMS200S3120G 120GB SSD      | 1         | 1.92%   |
| Kingston SA400S37480G 480GB SSD      | 1         | 1.92%   |
| Kingston SA400S37240G 240GB SSD      | 1         | 1.92%   |
| Kingston SA400M8240G 240GB SSD       | 1         | 1.92%   |
| Intenso SSD Sata III 256GB           | 1         | 1.92%   |
| Intel SSDPEKNW512G8H 512GB           | 1         | 1.92%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 5      | 27.78%  |
| Seagate | 5         | 6      | 27.78%  |
| Hitachi | 3         | 3      | 16.67%  |
| HGST    | 3         | 3      | 16.67%  |
| Toshiba | 1         | 1      | 5.56%   |
| Fujitsu | 1         | 1      | 5.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 8      | 26.32%  |
| Kingston            | 4         | 4      | 21.05%  |
| SanDisk             | 3         | 3      | 15.79%  |
| Yeyian              | 1         | 1      | 5.26%   |
| Toshiba             | 1         | 1      | 5.26%   |
| SPCC                | 1         | 1      | 5.26%   |
| SK hynix            | 1         | 1      | 5.26%   |
| Intenso             | 1         | 1      | 5.26%   |
| Indilinx            | 1         | 2      | 5.26%   |
| Crucial             | 1         | 1      | 5.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 18        | 19     | 38.3%   |
| SSD     | 17        | 23     | 36.17%  |
| NVMe    | 8         | 8      | 17.02%  |
| MMC     | 3         | 3      | 6.38%   |
| Unknown | 1         | 1      | 2.13%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 33        | 41     | 71.74%  |
| NVMe | 8         | 8      | 17.39%  |
| MMC  | 3         | 3      | 6.52%   |
| SAS  | 2         | 2      | 4.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 29        | 36     | 82.86%  |
| 0.51-1.0   | 4         | 4      | 11.43%  |
| 3.01-4.0   | 1         | 1      | 2.86%   |
| 1.01-2.0   | 1         | 1      | 2.86%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 13        | 29.55%  |
| 101-250        | 12        | 27.27%  |
| 51-100         | 6         | 13.64%  |
| 21-50          | 5         | 11.36%  |
| 501-1000       | 5         | 11.36%  |
| 1-20           | 2         | 4.55%   |
| More than 3000 | 1         | 2.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 15        | 34.88%  |
| 21-50          | 10        | 23.26%  |
| 51-100         | 8         | 18.6%   |
| 101-250        | 5         | 11.63%  |
| 251-500        | 3         | 6.98%   |
| More than 3000 | 1         | 2.33%   |
| 501-1000       | 1         | 2.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Notebooks | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WD1600BEVT-22ZCT0 160GB      | 1         | 1      | 11.11%  |
| Seagate ST9500420AS 500GB        | 1         | 1      | 11.11%  |
| Seagate ST9500325AS 500GB        | 1         | 1      | 11.11%  |
| Seagate ST1000LM035-1RK172 1TB   | 1         | 1      | 11.11%  |
| Indilinx IND-S325S120G 120GB SSD | 1         | 2      | 11.11%  |
| Hitachi HTS542516K9SA00 160GB    | 1         | 1      | 11.11%  |
| HGST HTS545050A7E680 500GB       | 1         | 1      | 11.11%  |
| HGST HTS545032A7E380 320GB       | 1         | 1      | 11.11%  |
| Fujitsu MHZ2160BH G2 160GB       | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 3         | 3      | 33.33%  |
| HGST     | 2         | 2      | 22.22%  |
| WDC      | 1         | 1      | 11.11%  |
| Indilinx | 1         | 2      | 11.11%  |
| Hitachi  | 1         | 1      | 11.11%  |
| Fujitsu  | 1         | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 37.5%   |
| HGST    | 2         | 2      | 25%     |
| WDC     | 1         | 1      | 12.5%   |
| Hitachi | 1         | 1      | 12.5%   |
| Fujitsu | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 8      | 88.89%  |
| SSD  | 1         | 2      | 11.11%  |

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
| Works    | 32        | 38     | 68.09%  |
| Malfunc  | 9         | 10     | 19.15%  |
| Detected | 6         | 6      | 12.77%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 30        | 66.67%  |
| AMD                          | 7         | 15.56%  |
| SanDisk                      | 3         | 6.67%   |
| Samsung Electronics          | 2         | 4.44%   |
| Toshiba America Info Systems | 1         | 2.22%   |
| Nvidia                       | 1         | 2.22%   |
| Lenovo                       | 1         | 2.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 7         | 13.73%  |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4         | 7.84%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 3         | 5.88%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 2         | 3.92%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 3.92%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 3.92%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 3.92%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 3.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 3.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 3.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 3.92%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 3.92%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 3.92%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 3.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 3.92%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 1.96%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 1.96%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 1         | 1.96%   |
| Lenovo Non-Volatile memory controller                                            | 1         | 1.96%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 1.96%   |
| Intel SSD 660P Series                                                            | 1         | 1.96%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1         | 1.96%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                      | 1         | 1.96%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 1.96%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 1.96%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1         | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 1         | 1.96%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 1.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 35        | 70%     |
| NVMe | 8         | 16%     |
| IDE  | 4         | 8%      |
| RAID | 3         | 6%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 36        | 83.72%  |
| AMD    | 7         | 16.28%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 4.65%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 4.65%   |
| Intel Core i3-4000M CPU @ 2.40GHz             | 2         | 4.65%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 4.65%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 2.33%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 2.33%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 1         | 2.33%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 2.33%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 2.33%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 2.33%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 2.33%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 2.33%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 2.33%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 2.33%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 2.33%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 2.33%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 2.33%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 2.33%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz            | 1         | 2.33%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 1         | 2.33%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 1         | 2.33%   |
| Intel Core Duo CPU T2500 @ 2.00GHz            | 1         | 2.33%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 1         | 2.33%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 2.33%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 1         | 2.33%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 1         | 2.33%   |
| Intel Celeron CPU 550 @ 2.00GHz               | 1         | 2.33%   |
| Intel Celeron 2955U @ 1.40GHz                 | 1         | 2.33%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 1         | 2.33%   |
| Intel Atom CPU N550 @ 1.50GHz                 | 1         | 2.33%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 1         | 2.33%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 2.33%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 2.33%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 1         | 2.33%   |
| AMD E1-6010 APU with AMD Radeon R2 Graphics   | 1         | 2.33%   |
| AMD E-300 APU with Radeon HD Graphics         | 1         | 2.33%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics   | 1         | 2.33%   |
| AMD A4-3300M APU with Radeon HD Graphics      | 1         | 2.33%   |
| AMD A4-1200 APU with Radeon HD Graphics       | 1         | 2.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 10        | 23.26%  |
| Intel Core i5    | 7         | 16.28%  |
| Intel Celeron    | 5         | 11.63%  |
| Intel Core i3    | 4         | 9.3%    |
| Intel Core 2 Duo | 3         | 6.98%   |
| Intel Atom       | 3         | 6.98%   |
| Intel Pentium    | 2         | 4.65%   |
| AMD A4           | 2         | 4.65%   |
| Other            | 1         | 2.33%   |
| Intel Core Duo   | 1         | 2.33%   |
| AMD Ryzen 7      | 1         | 2.33%   |
| AMD Ryzen 5      | 1         | 2.33%   |
| AMD E1           | 1         | 2.33%   |
| AMD E            | 1         | 2.33%   |
| AMD A8           | 1         | 2.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 26        | 60.47%  |
| 4      | 14        | 32.56%  |
| 1      | 2         | 4.65%   |
| 6      | 1         | 2.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 43        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 26        | 60.47%  |
| 1      | 17        | 39.53%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 41        | 95.35%  |
| 32-bit         | 2         | 4.65%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x40651    | 4         | 9.3%    |
| Unknown    | 4         | 9.3%    |
| 0x306a9    | 3         | 6.98%   |
| 0x806ea    | 2         | 4.65%   |
| 0x406c4    | 2         | 4.65%   |
| 0x306d4    | 2         | 4.65%   |
| 0x306c3    | 2         | 4.65%   |
| 0x206a7    | 2         | 4.65%   |
| 0x1067a    | 2         | 4.65%   |
| 0x906ed    | 1         | 2.33%   |
| 0x906e9    | 1         | 2.33%   |
| 0x806e9    | 1         | 2.33%   |
| 0x806c1    | 1         | 2.33%   |
| 0x706e5    | 1         | 2.33%   |
| 0x706a8    | 1         | 2.33%   |
| 0x706a1    | 1         | 2.33%   |
| 0x6ec      | 1         | 2.33%   |
| 0x20652    | 1         | 2.33%   |
| 0x106ca    | 1         | 2.33%   |
| 0x106c2    | 1         | 2.33%   |
| 0x10676    | 1         | 2.33%   |
| 0x10661    | 1         | 2.33%   |
| 0x08108102 | 1         | 2.33%   |
| 0x0810100b | 1         | 2.33%   |
| 0x07030105 | 1         | 2.33%   |
| 0x07030104 | 1         | 2.33%   |
| 0x0700010f | 1         | 2.33%   |
| 0x0500010d | 1         | 2.33%   |
| 0x03000027 | 1         | 2.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 7         | 16.28%  |
| Haswell       | 6         | 13.95%  |
| Silvermont    | 3         | 6.98%   |
| Penryn        | 3         | 6.98%   |
| IvyBridge     | 3         | 6.98%   |
| SandyBridge   | 2         | 4.65%   |
| Puma          | 2         | 4.65%   |
| Goldmont plus | 2         | 4.65%   |
| Broadwell     | 2         | 4.65%   |
| Bonnell       | 2         | 4.65%   |
| Zen+          | 1         | 2.33%   |
| Zen           | 1         | 2.33%   |
| Westmere      | 1         | 2.33%   |
| TigerLake     | 1         | 2.33%   |
| Skylake       | 1         | 2.33%   |
| P6            | 1         | 2.33%   |
| K10 Llano     | 1         | 2.33%   |
| Jaguar        | 1         | 2.33%   |
| IceLake       | 1         | 2.33%   |
| Core          | 1         | 2.33%   |
| Bobcat        | 1         | 2.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 33        | 63.46%  |
| AMD    | 12        | 23.08%  |
| Nvidia | 7         | 13.46%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 7.41%   |
| Intel UHD Graphics 620                                                                   | 3         | 5.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 5.56%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 5.56%   |
| Intel HD Graphics 5500                                                                   | 2         | 3.7%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 3.7%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 3.7%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 3.7%    |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 1.85%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                                         | 1         | 1.85%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 1.85%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 1         | 1.85%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 1.85%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1.85%   |
| Nvidia GF114M [GeForce GTX 675M]                                                         | 1         | 1.85%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.85%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 1.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.85%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 1.85%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.85%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                                   | 1         | 1.85%   |
| Intel HD Graphics 630                                                                    | 1         | 1.85%   |
| Intel HD Graphics 620                                                                    | 1         | 1.85%   |
| Intel HD Graphics 530                                                                    | 1         | 1.85%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.85%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.85%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 1.85%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 1.85%   |
| AMD Sumo [Radeon HD 6480G]                                                               | 1         | 1.85%   |
| AMD RV630/M76 [Mobility Radeon HD 2600]                                                  | 1         | 1.85%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 1         | 1.85%   |
| AMD RV515/M54 [Mobility Radeon X1400]                                                    | 1         | 1.85%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 1.85%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 1.85%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 1.85%   |
| AMD Mullins [Radeon R2 Graphics]                                                         | 1         | 1.85%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 1         | 1.85%   |
| AMD Kabini [Radeon HD 8180]                                                              | 1         | 1.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 24        | 55.81%  |
| 1 x AMD        | 9         | 20.93%  |
| Intel + Nvidia | 6         | 13.95%  |
| Intel + AMD    | 3         | 6.98%   |
| 1 x Nvidia     | 1         | 2.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 42        | 97.67%  |
| Unknown | 1         | 2.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 32        | 74.42%  |
| 0.01-0.5   | 7         | 16.28%  |
| 1.01-2.0   | 2         | 4.65%   |
| 0.51-1.0   | 2         | 4.65%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 8         | 17.39%  |
| BOE                     | 8         | 17.39%  |
| AU Optronics            | 8         | 17.39%  |
| Chimei Innolux          | 4         | 8.7%    |
| Chi Mei Optoelectronics | 4         | 8.7%    |
| Lenovo                  | 3         | 6.52%   |
| Samsung Electronics     | 2         | 4.35%   |
| HannStar                | 2         | 4.35%   |
| Philips                 | 1         | 2.17%   |
| PANDA                   | 1         | 2.17%   |
| LG Philips              | 1         | 2.17%   |
| InfoVision              | 1         | 2.17%   |
| Goldstar                | 1         | 2.17%   |
| Dell                    | 1         | 2.17%   |
| Apple                   | 1         | 2.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch  | 2         | 4.35%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 1         | 2.17%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch      | 1         | 2.17%   |
| Philips PHL BDM4350 PHL08FA 3840x2160 953x543mm 43.2-inch                 | 1         | 2.17%   |
| PANDA LM116LF3L01 NCP000A 1920x1080 256x144mm 11.6-inch                   | 1         | 2.17%   |
| LG Philips LCD Monitor LPL1901 1680x1050 331x207mm 15.4-inch              | 1         | 2.17%   |
| LG Display LP156WH2-TLE1 LGDCF01 1366x768 344x194mm 15.5-inch             | 1         | 2.17%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch              | 1         | 2.17%   |
| LG Display LCD Monitor LGD059E 1920x1080 382x215mm 17.3-inch              | 1         | 2.17%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 1         | 2.17%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch              | 1         | 2.17%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch               | 1         | 2.17%   |
| LG Display LCD Monitor LGD040A 1920x1080 309x175mm 14.0-inch              | 1         | 2.17%   |
| LG Display LCD Monitor LGD03B8 1366x768 310x174mm 14.0-inch               | 1         | 2.17%   |
| Lenovo LEN L27i-28 LEN65E0 1920x1080 600x340mm 27.2-inch                  | 1         | 2.17%   |
| Lenovo LCD Monitor LEN4043 1400x1050 305x228mm 15.0-inch                  | 1         | 2.17%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x189mm 14.1-inch                   | 1         | 2.17%   |
| InfoVision LCD Monitor IVO03FA 1366x768 223x125mm 10.1-inch               | 1         | 2.17%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                  | 1         | 2.17%   |
| HannStar HL161ABB HSD61C7 1366x768 344x193mm 15.5-inch                    | 1         | 2.17%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                   | 1         | 2.17%   |
| Dell S2409W DELA039 1920x1080 531x298mm 24.0-inch                         | 1         | 2.17%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 1         | 2.17%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x193mm 15.5-inch           | 1         | 2.17%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch          | 1         | 2.17%   |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch           | 1         | 2.17%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 2.17%   |
| Chi Mei Optoelectronics LCD Monitor CMO1467 1366x768 309x174mm 14.0-inch  | 1         | 2.17%   |
| BOE LCD Monitor BOE089D 1280x800 261x163mm 12.1-inch                      | 1         | 2.17%   |
| BOE LCD Monitor BOE084E 1920x1080 382x215mm 17.3-inch                     | 1         | 2.17%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                     | 1         | 2.17%   |
| BOE LCD Monitor BOE0791 1920x1080 309x173mm 13.9-inch                     | 1         | 2.17%   |
| BOE LCD Monitor BOE0742 1920x1080 309x173mm 13.9-inch                     | 1         | 2.17%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                      | 1         | 2.17%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                      | 1         | 2.17%   |
| BOE LCD Monitor BOE05DF 1366x768 293x165mm 13.2-inch                      | 1         | 2.17%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 1         | 2.17%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch             | 1         | 2.17%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 344x193mm 15.5-inch            | 1         | 2.17%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch            | 1         | 2.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 20        | 44.44%  |
| 1920x1080 (FHD)    | 17        | 37.78%  |
| 1024x600           | 2         | 4.44%   |
| 3840x2160 (4K)     | 1         | 2.22%   |
| 2560x1080          | 1         | 2.22%   |
| 1680x1050 (WSXGA+) | 1         | 2.22%   |
| 1440x900 (WXGA+)   | 1         | 2.22%   |
| 1400x1050          | 1         | 2.22%   |
| 1280x800 (WXGA)    | 1         | 2.22%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 19        | 42.22%  |
| 13     | 8         | 17.78%  |
| 14     | 7         | 15.56%  |
| 17     | 3         | 6.67%   |
| 10     | 3         | 6.67%   |
| 43     | 1         | 2.22%   |
| 34     | 1         | 2.22%   |
| 27     | 1         | 2.22%   |
| 24     | 1         | 2.22%   |
| 11     | 1         | 2.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 30        | 66.67%  |
| 201-300     | 7         | 15.56%  |
| 351-400     | 4         | 8.89%   |
| 501-600     | 2         | 4.44%   |
| 701-800     | 1         | 2.22%   |
| 901-1000    | 1         | 2.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 37        | 88.1%   |
| 16/10 | 3         | 7.14%   |
| 4/3   | 1         | 2.38%   |
| 21/9  | 1         | 2.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 19        | 42.22%  |
| 81-90          | 13        | 28.89%  |
| 41-50          | 3         | 6.67%   |
| 121-130        | 3         | 6.67%   |
| 71-80          | 2         | 4.44%   |
| 51-60          | 1         | 2.22%   |
| 351-500        | 1         | 2.22%   |
| 301-350        | 1         | 2.22%   |
| 201-250        | 1         | 2.22%   |
| 501-1000       | 1         | 2.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 20        | 43.48%  |
| 121-160 | 17        | 36.96%  |
| 51-100  | 7         | 15.22%  |
| 161-240 | 2         | 4.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 37        | 86.05%  |
| 2     | 5         | 11.63%  |
| 0     | 1         | 2.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 23        | 32.86%  |
| Intel                    | 21        | 30%     |
| Qualcomm Atheros         | 11        | 15.71%  |
| Broadcom                 | 7         | 10%     |
| Sierra Wireless          | 2         | 2.86%   |
| TP-Link                  | 1         | 1.43%   |
| Nvidia                   | 1         | 1.43%   |
| Marvell Technology Group | 1         | 1.43%   |
| Huawei Technologies      | 1         | 1.43%   |
| Hewlett-Packard          | 1         | 1.43%   |
| Google                   | 1         | 1.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 12        | 13.64%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 7         | 7.95%   |
| Intel Wireless 8265 / 8275                                              | 3         | 3.41%   |
| Intel Wireless 7260                                                     | 3         | 3.41%   |
| Intel Ethernet Connection I218-LM                                       | 3         | 3.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 2.27%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 2.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2         | 2.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 2.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 2.27%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 2.27%   |
| Intel Wireless 3165                                                     | 2         | 2.27%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 2.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 2.27%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 2.27%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 2.27%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 1.14%   |
| Sierra Wireless EM7430 Qualcomm Snapdragon X7 LTE-A                     | 1         | 1.14%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 1.14%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.14%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 1.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.14%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 1.14%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 1.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 1.14%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 1.14%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 1.14%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 1         | 1.14%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                           | 1         | 1.14%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 1.14%   |
| Nvidia MCP89 Ethernet                                                   | 1         | 1.14%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                    | 1         | 1.14%   |
| Intel Wireless-AC 9260                                                  | 1         | 1.14%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 1.14%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 1.14%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 1.14%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 1.14%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 1.14%   |
| Intel Ethernet Connection I217-V                                        | 1         | 1.14%   |
| Intel Ethernet Connection (7) I219-LM                                   | 1         | 1.14%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 18        | 38.3%   |
| Realtek Semiconductor | 9         | 19.15%  |
| Qualcomm Atheros      | 9         | 19.15%  |
| Broadcom              | 7         | 14.89%  |
| Sierra Wireless       | 2         | 4.26%   |
| TP-Link               | 1         | 2.13%   |
| Hewlett-Packard       | 1         | 2.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 3         | 6.38%   |
| Intel Wireless 7260                                                     | 3         | 6.38%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 4.26%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 4.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 4.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 4.26%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 4.26%   |
| Intel Wireless 3165                                                     | 2         | 4.26%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 4.26%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 4.26%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 4.26%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 2.13%   |
| Sierra Wireless EM7430 Qualcomm Snapdragon X7 LTE-A                     | 1         | 2.13%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 2.13%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 2.13%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 2.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 2.13%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 2.13%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 2.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 2.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 2.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 2.13%   |
| Intel Wireless-AC 9260                                                  | 1         | 2.13%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 2.13%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 2.13%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 2.13%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 2.13%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 2.13%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 2.13%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 2.13%   |
| HP lt4112 Gobi 4G Module Network Device                                 | 1         | 2.13%   |
| Broadcom BCM43225 802.11b/g/n                                           | 1         | 2.13%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 1         | 2.13%   |
| Broadcom BCM4311 802.11a/b/g                                            | 1         | 2.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 20        | 52.63%  |
| Intel                    | 13        | 34.21%  |
| Qualcomm Atheros         | 3         | 7.89%   |
| Nvidia                   | 1         | 2.63%   |
| Marvell Technology Group | 1         | 2.63%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12        | 30.77%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 17.95%  |
| Intel Ethernet Connection I218-LM                                 | 3         | 7.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 5.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 5.13%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 2.56%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 2.56%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 2.56%   |
| Nvidia MCP89 Ethernet                                             | 1         | 2.56%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 2.56%   |
| Intel Ethernet Connection I217-V                                  | 1         | 2.56%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 2.56%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 2.56%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 2.56%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 2.56%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 2.56%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.56%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 2.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 42        | 51.22%  |
| Ethernet | 38        | 46.34%  |
| Modem    | 1         | 1.22%   |
| Unknown  | 1         | 1.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 32        | 74.42%  |
| Ethernet | 10        | 23.26%  |
| Unknown  | 1         | 2.33%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 36        | 83.72%  |
| 1     | 5         | 11.63%  |
| 0     | 2         | 4.65%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 38        | 88.37%  |
| Yes  | 5         | 11.63%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 13        | 44.83%  |
| Broadcom                        | 5         | 17.24%  |
| Realtek Semiconductor           | 2         | 6.9%    |
| Qualcomm Atheros Communications | 2         | 6.9%    |
| Lite-On Technology              | 2         | 6.9%    |
| IMC Networks                    | 2         | 6.9%    |
| Hewlett-Packard                 | 1         | 3.45%   |
| Cambridge Silicon Radio         | 1         | 3.45%   |
| Apple                           | 1         | 3.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 9         | 31.03%  |
| Intel AX201 Bluetooth                               | 2         | 6.9%    |
| Realtek RTL8821A Bluetooth                          | 1         | 3.45%   |
| Realtek Bluetooth Radio                             | 1         | 3.45%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 3.45%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 3.45%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 3.45%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 3.45%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 3.45%   |
| Intel AX200 Bluetooth                               | 1         | 3.45%   |
| IMC Networks Bluetooth Radio                        | 1         | 3.45%   |
| IMC Networks Bluetooth Device                       | 1         | 3.45%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 3.45%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.45%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 3.45%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 3.45%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 3.45%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 3.45%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 3.45%   |
| Apple Bluetooth Host Controller                     | 1         | 3.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 34        | 69.39%  |
| AMD                 | 8         | 16.33%  |
| Nvidia              | 4         | 8.16%   |
| SteelSeries ApS     | 1         | 2.04%   |
| Mark of the Unicorn | 1         | 2.04%   |
| GN Netcom           | 1         | 2.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH Azalia Controller                                                                         | 5         | 7.81%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 4         | 6.25%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 6.25%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 6.25%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 4.69%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 3         | 4.69%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 4.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 3.13%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 3.13%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 3.13%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 3.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 3.13%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 3.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 3.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 3.13%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 3.13%   |
| SteelSeries ApS SteelSeries Arctis 7                                                              | 1         | 1.56%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.56%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 1.56%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 1.56%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 1         | 1.56%   |
| Mark of the Unicorn M Series                                                                      | 1         | 1.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 1.56%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 1.56%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 1.56%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.56%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.56%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 1.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 1.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.56%   |
| GN Netcom Jabra Link 370                                                                          | 1         | 1.56%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.56%   |
| AMD RV630 HDMI Audio [Radeon HD 2600 PRO/XT / HD 3610]                                            | 1         | 1.56%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 1         | 1.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 11        | 22.45%  |
| Samsung Electronics | 9         | 18.37%  |
| Kingston            | 7         | 14.29%  |
| Micron Technology   | 6         | 12.24%  |
| Crucial             | 4         | 8.16%   |
| Ramaxel Technology  | 3         | 6.12%   |
| Unknown             | 2         | 4.08%   |
| Nanya Technology    | 2         | 4.08%   |
| Unknown (ABCD)      | 1         | 2.04%   |
| Transcend           | 1         | 2.04%   |
| Teikon              | 1         | 2.04%   |
| Smart               | 1         | 2.04%   |
| A-DATA Technology   | 1         | 2.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT851S6AMR6A-PB 4GB Chip DDR3 1600MT/s             | 2         | 3.92%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 2         | 3.92%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 1         | 1.96%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 1.96%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 1.96%   |
| Transcend RAM JM1333KSN-4G 4096MB SODIMM DDR3 1334MT/s           | 1         | 1.96%   |
| Teikon RAM TMT451S6BFR8A-PBHJ 4GB SODIMM DDR3 1600MT/s           | 1         | 1.96%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 1         | 1.96%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 800MT/s                   | 1         | 1.96%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 2667MT/s                 | 1         | 1.96%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.96%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.96%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.96%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1334MT/s           | 1         | 1.96%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 1.96%   |
| SK hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 1.96%   |
| SK hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 1.96%   |
| SK hynix RAM H5AN8G6NCJR-XNC 4GB SODIMM DDR4 3200MT/s            | 1         | 1.96%   |
| Samsung RAM Module 2048MB SODIMM DDR2 533MT/s                    | 1         | 1.96%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s            | 1         | 1.96%   |
| Samsung RAM M471B5674EB0-YK0 2GB SODIMM DDR3 1600MT/s            | 1         | 1.96%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 1         | 1.96%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 1         | 1.96%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.96%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.96%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 1         | 1.96%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 1         | 1.96%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.96%   |
| Ramaxel RAM RMT3150ED58E8W1600 2GB SODIMM DDR3 1600MT/s          | 1         | 1.96%   |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s       | 1         | 1.96%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 1         | 1.96%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 1         | 1.96%   |
| Nanya RAM NT1GT64UH8D0FN-3C 1024MB SODIMM DDR2 667MT/s           | 1         | 1.96%   |
| Micron RAM Module 4096MB SODIMM DDR4 2400MT/s                    | 1         | 1.96%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                    | 1         | 1.96%   |
| Micron RAM Module 1024MB SODIMM DDR3 1067MT/s                    | 1         | 1.96%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8192MB SODIMM DDR4 2400MT/s          | 1         | 1.96%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2667MT/s            | 1         | 1.96%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 1         | 1.96%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s                 | 1         | 1.96%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 23        | 56.1%   |
| DDR4   | 12        | 29.27%  |
| DDR2   | 4         | 9.76%   |
| LPDDR4 | 1         | 2.44%   |
| LPDDR3 | 1         | 2.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 40        | 93.02%  |
| Chip         | 2         | 4.65%   |
| Row Of Chips | 1         | 2.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 15        | 32.61%  |
| 8192  | 13        | 28.26%  |
| 2048  | 11        | 23.91%  |
| 16384 | 4         | 8.7%    |
| 1024  | 3         | 6.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 15        | 35.71%  |
| 2667    | 6         | 14.29%  |
| 2400    | 4         | 9.52%   |
| 1334    | 4         | 9.52%   |
| 3200    | 2         | 4.76%   |
| 2133    | 2         | 4.76%   |
| 1067    | 2         | 4.76%   |
| Unknown | 2         | 4.76%   |
| 1867    | 1         | 2.38%   |
| 1333    | 1         | 2.38%   |
| 800     | 1         | 2.38%   |
| 667     | 1         | 2.38%   |
| 533     | 1         | 2.38%   |

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
| Chicony Electronics                    | 8         | 24.24%  |
| Acer                                   | 7         | 21.21%  |
| Cheng Uei Precision Industry (Foxlink) | 3         | 9.09%   |
| Sunplus Innovation Technology          | 2         | 6.06%   |
| Realtek Semiconductor                  | 2         | 6.06%   |
| Quanta                                 | 2         | 6.06%   |
| Lite-On Technology                     | 2         | 6.06%   |
| IMC Networks                           | 2         | 6.06%   |
| USB Camera                             | 1         | 3.03%   |
| Suyin                                  | 1         | 3.03%   |
| Luxvisions Innotech Limited            | 1         | 3.03%   |
| Lenovo                                 | 1         | 3.03%   |
| Apple                                  | 1         | 3.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 3         | 9.09%   |
| Quanta VGA WebCam                                           | 2         | 6.06%   |
| Lite-On Integrated Camera                                   | 2         | 6.06%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 2         | 6.06%   |
| Acer Lenovo Integrated Webcam                               | 2         | 6.06%   |
| Acer BisonCam, NB Pro                                       | 2         | 6.06%   |
| USB Camera USB Camera                                       | 1         | 3.03%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 3.03%   |
| Sunplus Laptop_Integrated_Webcam_HD                         | 1         | 3.03%   |
| Sunplus Integrated_Webcam_HD                                | 1         | 3.03%   |
| Realtek USB Camera                                          | 1         | 3.03%   |
| Realtek HD WebCam                                           | 1         | 3.03%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera        | 1         | 3.03%   |
| Lenovo Integrated Webcam                                    | 1         | 3.03%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 1         | 3.03%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 3.03%   |
| Chicony Webcam                                              | 1         | 3.03%   |
| Chicony USB 2.0 Camera                                      | 1         | 3.03%   |
| Chicony Integrated Camera (1280x720@30)                     | 1         | 3.03%   |
| Chicony HP Truevision HD                                    | 1         | 3.03%   |
| Chicony HP Full-HD Camera                                   | 1         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) Webcam               | 1         | 3.03%   |
| Apple Built-in iSight                                       | 1         | 3.03%   |
| Acer Lenovo EasyCamera                                      | 1         | 3.03%   |
| Acer Integrated Camera                                      | 1         | 3.03%   |
| Acer EasyCamera                                             | 1         | 3.03%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 30%     |
| Synaptics                  | 3         | 30%     |
| Upek                       | 1         | 10%     |
| STMicroelectronics         | 1         | 10%     |
| Shenzhen Goodix Technology | 1         | 10%     |
| AuthenTec                  | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                            | 2         | 20%     |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 10%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 1         | 10%     |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 10%     |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 10%     |
| STMicroelectronics Fingerprint Reader                      | 1         | 10%     |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 10%     |
| AuthenTec AES2501 Fingerprint Sensor                       | 1         | 10%     |
| Unknown                                                    | 1         | 10%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Lenovo      | 2         | 50%     |
| Broadcom    | 1         | 25%     |
| Alcor Micro | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Lenovo Integrated Smart Card Reader            | 2         | 50%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 25%     |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 26        | 60.47%  |
| 1     | 12        | 27.91%  |
| 2     | 5         | 11.63%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 10        | 43.48%  |
| Graphics card      | 9         | 39.13%  |
| Chipcard           | 4         | 17.39%  |

