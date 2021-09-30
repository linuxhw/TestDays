Elementary 6 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for Elementary 6.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=elementary-6

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

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo    | ThinkPad T430 2342A19       | [32c58fa2f6](https://linux-hardware.org/?probe=32c58fa2f6) | Sep 30, 2021 |
| Dell      | XPS 13 9350                 | [c1dc59d33f](https://linux-hardware.org/?probe=c1dc59d33f) | Sep 29, 2021 |
| Lenovo    | IdeaPad 5 15ARE05 81YQ      | [c28700cfda](https://linux-hardware.org/?probe=c28700cfda) | Sep 26, 2021 |
| Lenovo    | Yoga 300-11IBR 80M1         | [fbcf277174](https://linux-hardware.org/?probe=fbcf277174) | Sep 26, 2021 |
| Lenovo    | G50-45 80E3                 | [59224ec754](https://linux-hardware.org/?probe=59224ec754) | Sep 26, 2021 |
| Apple     | MacBookPro10,2              | [25c8a26c00](https://linux-hardware.org/?probe=25c8a26c00) | Sep 24, 2021 |
| Lenovo    | IdeaPad S145-15AST 81N3     | [c1b8f22fa6](https://linux-hardware.org/?probe=c1b8f22fa6) | Sep 22, 2021 |
| Dell      | Precision M4800             | [736b482dc3](https://linux-hardware.org/?probe=736b482dc3) | Sep 22, 2021 |
| eMachines | G525                        | [8e8d037369](https://linux-hardware.org/?probe=8e8d037369) | Sep 21, 2021 |
| HUAWEI    | NBLB-WAX9N                  | [9d25d0c5c7](https://linux-hardware.org/?probe=9d25d0c5c7) | Sep 21, 2021 |
| Lenovo    | ThinkPad W700 2758MVG       | [66c8ecbaa1](https://linux-hardware.org/?probe=66c8ecbaa1) | Sep 20, 2021 |
| Dell      | XPS 13 9350                 | [b01438543e](https://linux-hardware.org/?probe=b01438543e) | Sep 20, 2021 |
| Apple     | MacBookPro10,2              | [0e44f5011a](https://linux-hardware.org/?probe=0e44f5011a) | Sep 20, 2021 |
| Lenovo    | ThinkPad X1 Carbon 3448B... | [2bec640695](https://linux-hardware.org/?probe=2bec640695) | Sep 20, 2021 |
| Lenovo    | IdeaPad 5 15ARE05 81YQ      | [d2511347b4](https://linux-hardware.org/?probe=d2511347b4) | Sep 19, 2021 |
| HP        | ENVY 15                     | [ba9a8e1d7a](https://linux-hardware.org/?probe=ba9a8e1d7a) | Sep 19, 2021 |
| Lenovo    | V330-15IKB 81AX             | [9d10bffde2](https://linux-hardware.org/?probe=9d10bffde2) | Sep 18, 2021 |
| Lenovo    | ThinkPad X250 20CLS32H00    | [15981e12f3](https://linux-hardware.org/?probe=15981e12f3) | Sep 18, 2021 |
| Lenovo    | ThinkPad X250 20CLS32H00    | [bcdb4d552d](https://linux-hardware.org/?probe=bcdb4d552d) | Sep 18, 2021 |
| HP        | ENVY 15                     | [d2d607895f](https://linux-hardware.org/?probe=d2d607895f) | Sep 18, 2021 |
| Alienware | 17                          | [c97b201719](https://linux-hardware.org/?probe=c97b201719) | Sep 17, 2021 |
| Acer      | Aspire V3-572G              | [addf12cb05](https://linux-hardware.org/?probe=addf12cb05) | Sep 16, 2021 |
| TUXEDO    | InfinityBook S 14 Gen6      | [0c206818b9](https://linux-hardware.org/?probe=0c206818b9) | Sep 15, 2021 |
| Acer      | Aspire VX5-591G             | [c7d5407b29](https://linux-hardware.org/?probe=c7d5407b29) | Sep 15, 2021 |
| Dell      | Latitude E7440              | [fc9f25eecb](https://linux-hardware.org/?probe=fc9f25eecb) | Sep 14, 2021 |
| Toshiba   | Satellite P100              | [bc5b605920](https://linux-hardware.org/?probe=bc5b605920) | Sep 13, 2021 |
| HP        | Pavilion Notebook           | [591ba7a77c](https://linux-hardware.org/?probe=591ba7a77c) | Sep 12, 2021 |
| Dell      | Inspiron 3583               | [49b4db94c6](https://linux-hardware.org/?probe=49b4db94c6) | Sep 12, 2021 |
| ASUSTek   | UX303LA                     | [1a67d956de](https://linux-hardware.org/?probe=1a67d956de) | Sep 11, 2021 |
| HP        | Pavilion Notebook           | [f373a049e2](https://linux-hardware.org/?probe=f373a049e2) | Sep 10, 2021 |
| HP        | Pavilion Notebook           | [6e97abfd44](https://linux-hardware.org/?probe=6e97abfd44) | Sep 09, 2021 |
| Lenovo    | ThinkPad X201 3249CTO       | [7b3432fcf6](https://linux-hardware.org/?probe=7b3432fcf6) | Sep 08, 2021 |
| HP        | Laptop 14-dq1xxx            | [0614925ee7](https://linux-hardware.org/?probe=0614925ee7) | Sep 08, 2021 |
| Gateway   | NV54 Series                 | [fcf57528ed](https://linux-hardware.org/?probe=fcf57528ed) | Sep 08, 2021 |
| Sony      | Serie VJC14                 | [27828e1dfb](https://linux-hardware.org/?probe=27828e1dfb) | Sep 07, 2021 |
| Sony      | Serie VJC14                 | [4c1200e7cf](https://linux-hardware.org/?probe=4c1200e7cf) | Sep 07, 2021 |
| Lenovo    | V330-15IKB 81AX             | [797db05baf](https://linux-hardware.org/?probe=797db05baf) | Sep 06, 2021 |
| HP        | Laptop 15-bs1xx             | [91ecd39f66](https://linux-hardware.org/?probe=91ecd39f66) | Sep 05, 2021 |
| Medion    | AKOYA THE TOUCH 10          | [d49d62a2f5](https://linux-hardware.org/?probe=d49d62a2f5) | Sep 04, 2021 |
| Apple     | MacBookPro8,1               | [da332ba09e](https://linux-hardware.org/?probe=da332ba09e) | Sep 01, 2021 |
| HP        | EliteBook Folio 9470m       | [adbb6a690a](https://linux-hardware.org/?probe=adbb6a690a) | Sep 01, 2021 |
| Dell      | Latitude 3580               | [2befbbba9e](https://linux-hardware.org/?probe=2befbbba9e) | Aug 31, 2021 |
| HP        | Pavilion g6                 | [7dba3c201c](https://linux-hardware.org/?probe=7dba3c201c) | Aug 31, 2021 |
| HP        | Pavilion Aero Laptop 13-... | [48c720456a](https://linux-hardware.org/?probe=48c720456a) | Aug 30, 2021 |
| HP        | ProBook 4320s               | [94f189cea1](https://linux-hardware.org/?probe=94f189cea1) | Aug 29, 2021 |
| eMachines | G525                        | [d64e29475f](https://linux-hardware.org/?probe=d64e29475f) | Aug 29, 2021 |
| Lenovo    | ThinkPad X201 3249CTO       | [0a9bdb4827](https://linux-hardware.org/?probe=0a9bdb4827) | Aug 27, 2021 |
| Acer      | Aspire A515-51G             | [df0d3e8ac4](https://linux-hardware.org/?probe=df0d3e8ac4) | Aug 26, 2021 |
| HP        | Laptop 15-bs0xx             | [fae546f5cb](https://linux-hardware.org/?probe=fae546f5cb) | Aug 20, 2021 |
| Apple     | MacBookPro9,1               | [e9bec90506](https://linux-hardware.org/?probe=e9bec90506) | Aug 19, 2021 |
| Acer      | Aspire F5-573G              | [9d7628068c](https://linux-hardware.org/?probe=9d7628068c) | Aug 19, 2021 |
| Dell      | XPS L321X                   | [34d7fb6cbb](https://linux-hardware.org/?probe=34d7fb6cbb) | Aug 18, 2021 |
| HP        | ProBook 450 G8 Notebook ... | [f30480d463](https://linux-hardware.org/?probe=f30480d463) | Aug 17, 2021 |
| HP        | Notebook                    | [a3058005e3](https://linux-hardware.org/?probe=a3058005e3) | Aug 16, 2021 |
| HP        | Notebook                    | [7800ef9623](https://linux-hardware.org/?probe=7800ef9623) | Aug 16, 2021 |
| Lenovo    | IdeaPad 330-15IKB 81FE      | [fa6c69671f](https://linux-hardware.org/?probe=fa6c69671f) | Aug 16, 2021 |
| Apple     | MacBookPro9,1               | [a6b2c12401](https://linux-hardware.org/?probe=a6b2c12401) | Aug 14, 2021 |
| Dell      | Precision 5760              | [824e5e7dad](https://linux-hardware.org/?probe=824e5e7dad) | Aug 14, 2021 |
| Acer      | Aspire A514-54              | [dcfc87a32f](https://linux-hardware.org/?probe=dcfc87a32f) | Aug 14, 2021 |
| Acer      | Aspire A514-54              | [e354646c04](https://linux-hardware.org/?probe=e354646c04) | Aug 13, 2021 |
| HP        | Pavilion Gaming Laptop 1... | [4e6f050b43](https://linux-hardware.org/?probe=4e6f050b43) | Aug 10, 2021 |
| Toshiba   | Satellite L500              | [76a8d2c20a](https://linux-hardware.org/?probe=76a8d2c20a) | Jul 29, 2021 |
| Google    | Cave                        | [e2617f0c2d](https://linux-hardware.org/?probe=e2617f0c2d) | Jul 25, 2021 |
| Toshiba   | Satellite L500              | [7124417642](https://linux-hardware.org/?probe=7124417642) | Jul 22, 2021 |
| HP        | Stream Laptop 14-cb1xxx     | [0447155931](https://linux-hardware.org/?probe=0447155931) | Jul 02, 2021 |
| Acer      | Swift SF314-55G             | [c371b46cbe](https://linux-hardware.org/?probe=c371b46cbe) | Jun 30, 2021 |
| Acer      | Swift SF315-41              | [8df5e13fc0](https://linux-hardware.org/?probe=8df5e13fc0) | Jun 18, 2021 |
| Acer      | Swift SF314-55G             | [4e5cf8aa1e](https://linux-hardware.org/?probe=4e5cf8aa1e) | Jun 13, 2021 |
| Acer      | ConceptD CN315-71P          | [5ecea84320](https://linux-hardware.org/?probe=5ecea84320) | May 15, 2021 |
| Apple     | MacBookPro8,2               | [e87a073ae8](https://linux-hardware.org/?probe=e87a073ae8) | Mar 18, 2021 |
| HP        | EliteBook 840 G3            | [1e31858e51](https://linux-hardware.org/?probe=1e31858e51) | Mar 09, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Notebooks | Percent |
|-----------------------|-----------|---------|
| 5.11.0-27-generic     | 25        | 42.37%  |
| 5.11.0-34-generic     | 12        | 20.34%  |
| 5.11.0-25-generic     | 10        | 16.95%  |
| 5.8.0-55-generic      | 2         | 3.39%   |
| 5.11.0-37-generic     | 2         | 3.39%   |
| 5.11.0-36-generic     | 2         | 3.39%   |
| 5.8.0-63-generic      | 1         | 1.69%   |
| 5.8.0-53-generic      | 1         | 1.69%   |
| 5.8.0-50-generic      | 1         | 1.69%   |
| 5.8.0-44-generic      | 1         | 1.69%   |
| 5.14.7-xanmod1-cacule | 1         | 1.69%   |
| 5.11.0-051100-generic | 1         | 1.69%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 51        | 87.93%  |
| 5.8.0   | 6         | 10.34%  |
| 5.14.7  | 1         | 1.72%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 51        | 87.93%  |
| 5.8     | 6         | 10.34%  |
| 5.14    | 1         | 1.72%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 58        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Pantheon   | 51        | 87.93%  |
| Unknown    | 5         | 8.62%   |
| X-Cinnamon | 1         | 1.72%   |
| GNOME      | 1         | 1.72%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 58        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 45        | 77.59%  |
| LightDM | 7         | 12.07%  |
| TDM     | 4         | 6.9%    |
| GDM     | 2         | 3.45%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 31        | 53.45%  |
| de_DE | 5         | 8.62%   |
| es_ES | 4         | 6.9%    |
| ru_RU | 3         | 5.17%   |
| fr_FR | 3         | 5.17%   |
| zh_CN | 2         | 3.45%   |
| pt_BR | 2         | 3.45%   |
| en_GB | 2         | 3.45%   |
| en_CA | 2         | 3.45%   |
| vi_VN | 1         | 1.72%   |
| it_IT | 1         | 1.72%   |
| en_AU | 1         | 1.72%   |
| cs_CZ | 1         | 1.72%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 38        | 65.52%  |
| BIOS | 20        | 34.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 54        | 93.1%   |
| Overlay | 3         | 5.17%   |
| Btrfs   | 1         | 1.72%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 45        | 77.59%  |
| GPT     | 10        | 17.24%  |
| MBR     | 3         | 5.17%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 55        | 94.83%  |
| Yes       | 3         | 5.17%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 53        | 91.38%  |
| Yes       | 5         | 8.62%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 15        | 25.86%  |
| Lenovo           | 11        | 18.97%  |
| Dell             | 8         | 13.79%  |
| Acer             | 8         | 13.79%  |
| Apple            | 6         | 10.34%  |
| Toshiba          | 2         | 3.45%   |
| TUXEDO           | 1         | 1.72%   |
| Sony             | 1         | 1.72%   |
| Medion           | 1         | 1.72%   |
| HUAWEI           | 1         | 1.72%   |
| Gateway          | 1         | 1.72%   |
| eMachines        | 1         | 1.72%   |
| ASUSTek Computer | 1         | 1.72%   |
| Alienware        | 1         | 1.72%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| HP Pavilion Notebook                | 2         | 3.45%   |
| Dell XPS 13 9350                    | 2         | 3.45%   |
| Apple MacBookPro9,1                 | 2         | 3.45%   |
| Apple MacBookPro10,2                | 2         | 3.45%   |
| TUXEDO InfinityBook S 14 Gen6       | 1         | 1.72%   |
| Toshiba Satellite P100              | 1         | 1.72%   |
| Toshiba Satellite L500              | 1         | 1.72%   |
| Sony Serie VJC14                    | 1         | 1.72%   |
| Medion AKOYA THE TOUCH 10           | 1         | 1.72%   |
| Lenovo Yoga 300-11IBR 80M1          | 1         | 1.72%   |
| Lenovo V330-15IKB 81AX              | 1         | 1.72%   |
| Lenovo ThinkPad X250 20CLS32H00     | 1         | 1.72%   |
| Lenovo ThinkPad X201 3249CTO        | 1         | 1.72%   |
| Lenovo ThinkPad X1 Carbon 3448B86   | 1         | 1.72%   |
| Lenovo ThinkPad W700 2758MVG        | 1         | 1.72%   |
| Lenovo ThinkPad T430 2342A19        | 1         | 1.72%   |
| Lenovo IdeaPad S145-15AST 81N3      | 1         | 1.72%   |
| Lenovo IdeaPad 5 15ARE05 81YQ       | 1         | 1.72%   |
| Lenovo IdeaPad 330-15IKB 81FE       | 1         | 1.72%   |
| Lenovo G50-45 80E3                  | 1         | 1.72%   |
| HUAWEI NBLB-WAX9N                   | 1         | 1.72%   |
| HP Stream Laptop 14-cb1xxx          | 1         | 1.72%   |
| HP ProBook 450 G8 Notebook PC       | 1         | 1.72%   |
| HP ProBook 4320s                    | 1         | 1.72%   |
| HP Pavilion Gaming Laptop 15-ec0xxx | 1         | 1.72%   |
| HP Pavilion g6                      | 1         | 1.72%   |
| HP Pavilion Aero Laptop 13-be0xxx   | 1         | 1.72%   |
| HP Notebook                         | 1         | 1.72%   |
| HP Laptop 15-bs1xx                  | 1         | 1.72%   |
| HP Laptop 15-bs0xx                  | 1         | 1.72%   |
| HP Laptop 14-dq1xxx                 | 1         | 1.72%   |
| HP ENVY 15                          | 1         | 1.72%   |
| HP EliteBook Folio 9470m            | 1         | 1.72%   |
| HP EliteBook 840 G3                 | 1         | 1.72%   |
| Gateway NV54 Series                 | 1         | 1.72%   |
| eMachines G525                      | 1         | 1.72%   |
| Dell XPS L321X                      | 1         | 1.72%   |
| Dell Precision M4800                | 1         | 1.72%   |
| Dell Precision 5760                 | 1         | 1.72%   |
| Dell Latitude E7440                 | 1         | 1.72%   |
| Dell Latitude 3580                  | 1         | 1.72%   |
| Dell Inspiron 3583                  | 1         | 1.72%   |
| ASUS UX303LA                        | 1         | 1.72%   |
| Apple MacBookPro8,2                 | 1         | 1.72%   |
| Apple MacBookPro8,1                 | 1         | 1.72%   |
| Alienware 17                        | 1         | 1.72%   |
| Acer Swift SF315-41                 | 1         | 1.72%   |
| Acer Swift SF314-55G                | 1         | 1.72%   |
| Acer ConceptD CN315-71P             | 1         | 1.72%   |
| Acer Aspire VX5-591G                | 1         | 1.72%   |
| Acer Aspire V3-572G                 | 1         | 1.72%   |
| Acer Aspire F5-573G                 | 1         | 1.72%   |
| Acer Aspire A515-51G                | 1         | 1.72%   |
| Acer Aspire A514-54                 | 1         | 1.72%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 5         | 8.62%   |
| HP Pavilion         | 5         | 8.62%   |
| Acer Aspire         | 5         | 8.62%   |
| Lenovo IdeaPad      | 3         | 5.17%   |
| HP Laptop           | 3         | 5.17%   |
| Dell XPS            | 3         | 5.17%   |
| Toshiba Satellite   | 2         | 3.45%   |
| HP ProBook          | 2         | 3.45%   |
| HP EliteBook        | 2         | 3.45%   |
| Dell Precision      | 2         | 3.45%   |
| Dell Latitude       | 2         | 3.45%   |
| Apple MacBookPro9   | 2         | 3.45%   |
| Apple MacBookPro8   | 2         | 3.45%   |
| Apple MacBookPro10  | 2         | 3.45%   |
| Acer Swift          | 2         | 3.45%   |
| TUXEDO InfinityBook | 1         | 1.72%   |
| Sony Serie          | 1         | 1.72%   |
| Medion AKOYA        | 1         | 1.72%   |
| Lenovo Yoga         | 1         | 1.72%   |
| Lenovo V330-15IKB   | 1         | 1.72%   |
| Lenovo G50-45       | 1         | 1.72%   |
| HUAWEI NBLB-WAX9N   | 1         | 1.72%   |
| HP Stream           | 1         | 1.72%   |
| HP Notebook         | 1         | 1.72%   |
| HP ENVY             | 1         | 1.72%   |
| Gateway NV54        | 1         | 1.72%   |
| eMachines G525      | 1         | 1.72%   |
| Dell Inspiron       | 1         | 1.72%   |
| ASUS UX303LA        | 1         | 1.72%   |
| Alienware 17        | 1         | 1.72%   |
| Acer ConceptD       | 1         | 1.72%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 13        | 22.41%  |
| 2019    | 8         | 13.79%  |
| 2018    | 8         | 13.79%  |
| 2020    | 6         | 10.34%  |
| 2015    | 6         | 10.34%  |
| 2012    | 4         | 6.9%    |
| 2017    | 3         | 5.17%   |
| 2014    | 3         | 5.17%   |
| 2010    | 3         | 5.17%   |
| 2013    | 2         | 3.45%   |
| 2009    | 1         | 1.72%   |
| Unknown | 1         | 1.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 58        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 44        | 75.86%  |
| Enabled  | 14        | 24.14%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 58        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 24        | 41.38%  |
| 3.01-4.0   | 12        | 20.69%  |
| 16.01-24.0 | 9         | 15.52%  |
| 8.01-16.0  | 7         | 12.07%  |
| 32.01-64.0 | 4         | 6.9%    |
| 24.01-32.0 | 1         | 1.72%   |
| 1.01-2.0   | 1         | 1.72%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 22        | 36.67%  |
| 1.01-2.0 | 18        | 30%     |
| 3.01-4.0 | 11        | 18.33%  |
| 4.01-8.0 | 9         | 15%     |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 43        | 74.14%  |
| 2      | 13        | 22.41%  |
| 4      | 1         | 1.72%   |
| 3      | 1         | 1.72%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 41        | 70.69%  |
| Yes       | 17        | 29.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 44        | 75.86%  |
| No        | 14        | 24.14%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 57        | 98.28%  |
| No        | 1         | 1.72%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 54        | 91.53%  |
| No        | 5         | 8.47%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 8         | 13.79%  |
| Germany     | 7         | 12.07%  |
| India       | 6         | 10.34%  |
| Russia      | 4         | 6.9%    |
| France      | 3         | 5.17%   |
| Brazil      | 3         | 5.17%   |
| Argentina   | 3         | 5.17%   |
| UK          | 2         | 3.45%   |
| Guatemala   | 2         | 3.45%   |
| Canada      | 2         | 3.45%   |
| Vietnam     | 1         | 1.72%   |
| Serbia      | 1         | 1.72%   |
| Netherlands | 1         | 1.72%   |
| Myanmar     | 1         | 1.72%   |
| Morocco     | 1         | 1.72%   |
| Mexico      | 1         | 1.72%   |
| Latvia      | 1         | 1.72%   |
| Kazakhstan  | 1         | 1.72%   |
| Japan       | 1         | 1.72%   |
| Italy       | 1         | 1.72%   |
| Indonesia   | 1         | 1.72%   |
| Guyana      | 1         | 1.72%   |
| Estonia     | 1         | 1.72%   |
| Denmark     | 1         | 1.72%   |
| Czechia     | 1         | 1.72%   |
| China       | 1         | 1.72%   |
| Belgium     | 1         | 1.72%   |
| Australia   | 1         | 1.72%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Moscow           | 2         | 3.39%   |
| Guatemala City   | 2         | 3.39%   |
| Buenos Aires     | 2         | 3.39%   |
| Wriezen          | 1         | 1.69%   |
| Wiefelstede      | 1         | 1.69%   |
| Villeurbanne     | 1         | 1.69%   |
| Vernon           | 1         | 1.69%   |
| Toledo           | 1         | 1.69%   |
| Tokyo            | 1         | 1.69%   |
| Thousand Oaks    | 1         | 1.69%   |
| Tallinn          | 1         | 1.69%   |
| Taganrog         | 1         | 1.69%   |
| Surabaya         | 1         | 1.69%   |
| Stevenage        | 1         | 1.69%   |
| Sinop            | 1         | 1.69%   |
| S??o Pedro       | 1         | 1.69%   |
| Santa Monica     | 1         | 1.69%   |
| Sakai            | 1         | 1.69%   |
| Sacramento       | 1         | 1.69%   |
| Rostov-on-Don    | 1         | 1.69%   |
| Quer?©taro City  | 1         | 1.69%   |
| Plesnois         | 1         | 1.69%   |
| Pfullingen       | 1         | 1.69%   |
| Perth            | 1         | 1.69%   |
| Peekskill        | 1         | 1.69%   |
| Patna            | 1         | 1.69%   |
| Paris            | 1         | 1.69%   |
| Odense           | 1         | 1.69%   |
| Northridge       | 1         | 1.69%   |
| Naaldwijk        | 1         | 1.69%   |
| Mumbai           | 1         | 1.69%   |
| Moss Point       | 1         | 1.69%   |
| Montreal         | 1         | 1.69%   |
| Monheim am Rhein | 1         | 1.69%   |
| Milan            | 1         | 1.69%   |
| Mandalay         | 1         | 1.69%   |
| Lucknow          | 1         | 1.69%   |
| Len?«nskoe       | 1         | 1.69%   |
| Lanaken          | 1         | 1.69%   |
| Kovin            | 1         | 1.69%   |
| Koraput          | 1         | 1.69%   |
| Jaunmarupe       | 1         | 1.69%   |
| Jalandhar        | 1         | 1.69%   |
| Horovice         | 1         | 1.69%   |
| Hollern          | 1         | 1.69%   |
| Georgetown       | 1         | 1.69%   |
| Eislingen        | 1         | 1.69%   |
| Curitiba         | 1         | 1.69%   |
| Chattanooga      | 1         | 1.69%   |
| C??rdoba         | 1         | 1.69%   |
| Casablanca       | 1         | 1.69%   |
| Camberwell       | 1         | 1.69%   |
| Bien Hoa         | 1         | 1.69%   |
| Bhopal           | 1         | 1.69%   |
| Berlin           | 1         | 1.69%   |
| Beijing          | 1         | 1.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 14        | 15     | 18.18%  |
| Samsung Electronics       | 13        | 13     | 16.88%  |
| Seagate                   | 7         | 9      | 9.09%   |
| Sandisk                   | 6         | 6      | 7.79%   |
| Unknown                   | 4         | 4      | 5.19%   |
| Hitachi                   | 4         | 4      | 5.19%   |
| Crucial                   | 4         | 4      | 5.19%   |
| Toshiba                   | 3         | 3      | 3.9%    |
| Kingston                  | 3         | 4      | 3.9%    |
| HGST                      | 3         | 3      | 3.9%    |
| SK Hynix                  | 2         | 2      | 2.6%    |
| LITEONIT                  | 2         | 2      | 2.6%    |
| Apple                     | 2         | 2      | 2.6%    |
| Union Memory              | 1         | 1      | 1.3%    |
| Phison                    | 1         | 1      | 1.3%    |
| Micron/Crucial Technology | 1         | 1      | 1.3%    |
| Micron Technology         | 1         | 1      | 1.3%    |
| Mercury                   | 1         | 1      | 1.3%    |
| LITEON                    | 1         | 1      | 1.3%    |
| Intel                     | 1         | 1      | 1.3%    |
| HUAWEI                    | 1         | 1      | 1.3%    |
| Gigabyte Technology       | 1         | 1      | 1.3%    |
| CLOVER                    | 1         | 1      | 1.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| WDC WDS500G2B0A-00SM50 500GB SSD      | 2         | 2.56%   |
| WDC WD10SPZX-21Z10T0 1TB              | 2         | 2.56%   |
| WDC WD10JPVX-22JC3T0 1TB              | 2         | 2.56%   |
| SK Hynix NVMe SSD Drive 512GB         | 2         | 2.56%   |
| Seagate ST1000LM035-1RK172 1TB        | 2         | 2.56%   |
| Kingston SA400S37240G 240GB SSD       | 2         | 2.56%   |
| HGST HTS541010A9E680 1TB              | 2         | 2.56%   |
| Apple SSD SD128E 121GB                | 2         | 2.56%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 1.28%   |
| WDC WD5000BPKT-75PK4T0 500GB          | 1         | 1.28%   |
| WDC WD20SPZX-21UA7T0 2TB              | 1         | 1.28%   |
| WDC WD10SPZX-24Z10T0 1TB              | 1         | 1.28%   |
| WDC WD10SPZX-22Z10T1 1TB              | 1         | 1.28%   |
| WDC WD10JPVX-60JC3T1 1TB              | 1         | 1.28%   |
| WDC PC SN720 SDAPNTW-256G-1014 256GB  | 1         | 1.28%   |
| WDC PC SN530 SDBPNPZ-256G-1114 256GB  | 1         | 1.28%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB  | 1         | 1.28%   |
| Unknown xD/SD/M.S.                    | 1         | 1.28%   |
| Unknown TA2964  64GB                  | 1         | 1.28%   |
| Unknown MMC Card  64GB                | 1         | 1.28%   |
| Unknown MMC Card  128GB               | 1         | 1.28%   |
| Union Memory RTOTJ256VGD2MYX 256GB    | 1         | 1.28%   |
| Toshiba MQ01ABD100V -63 1TB           | 1         | 1.28%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1.28%   |
| Toshiba MK5065GSXF 500GB              | 1         | 1.28%   |
| Seagate ST9250315AS 250GB             | 1         | 1.28%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 1.28%   |
| Seagate ST320LT020-9YG142 320GB       | 1         | 1.28%   |
| Seagate ST1000LM049-2GH172 1TB        | 1         | 1.28%   |
| Seagate ST1000LM048-2E7172 1TB        | 1         | 1.28%   |
| SanDisk SDSSDA480G 480GB              | 1         | 1.28%   |
| SanDisk SDSSDA120G 120GB              | 1         | 1.28%   |
| SanDisk SD7SB3Q256G1002 256GB SSD     | 1         | 1.28%   |
| SanDisk SD7SB3Q128G1001 128GB SSD     | 1         | 1.28%   |
| Sandisk NVMe SSD Drive 512GB          | 1         | 1.28%   |
| Sandisk NVMe SSD Drive 256GB          | 1         | 1.28%   |
| Samsung SSD SM841 mSATA 128GB         | 1         | 1.28%   |
| Samsung SSD 970 EVO Plus 250GB        | 1         | 1.28%   |
| Samsung SSD 860 EVO 2TB               | 1         | 1.28%   |
| Samsung SSD 860 EVO 250GB             | 1         | 1.28%   |
| Samsung SSD 840 EVO 250GB             | 1         | 1.28%   |
| Samsung SSD 840 EVO 120GB mSATA       | 1         | 1.28%   |
| Samsung NVMe SSD Drive 512GB          | 1         | 1.28%   |
| Samsung NVMe SSD Drive 500GB          | 1         | 1.28%   |
| Samsung NVMe SSD Drive 256GB          | 1         | 1.28%   |
| Samsung MZVLW256HEHP-000L2 256GB      | 1         | 1.28%   |
| Samsung MZNTY128HDHP-000H1 128GB SSD  | 1         | 1.28%   |
| Samsung MZNLN128HAHQ-000H1 128GB SSD  | 1         | 1.28%   |
| Samsung HM321HI 320GB                 | 1         | 1.28%   |
| Phison NVMe SSD Drive 2TB             | 1         | 1.28%   |
| Micron/Crucial NVMe SSD Drive 500GB   | 1         | 1.28%   |
| Micron NVMe SSD Drive 512GB           | 1         | 1.28%   |
| Mercury Electra 3G SSD                | 1         | 1.28%   |
| LITEONIT LMT-256M3M 256GB SSD         | 1         | 1.28%   |
| LITEONIT LCS-512M6S 2.5 7mm 512GB SSD | 1         | 1.28%   |
| LITEON CV1-8B256-HP 256GB SSD         | 1         | 1.28%   |
| Kingston SA400S37120G 120GB SSD       | 1         | 1.28%   |
| Intel SSDSCMMW240A3L 240GB            | 1         | 1.28%   |
| HUAWEI SD Storage 2GB                 | 1         | 1.28%   |
| Hitachi HTS725032A9A364 320GB         | 1         | 1.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 10     | 35.71%  |
| Seagate             | 7         | 9      | 25%     |
| Hitachi             | 4         | 4      | 14.29%  |
| Toshiba             | 3         | 3      | 10.71%  |
| HGST                | 3         | 3      | 10.71%  |
| Samsung Electronics | 1         | 1      | 3.57%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 7      | 25.93%  |
| SanDisk             | 4         | 4      | 14.81%  |
| Crucial             | 4         | 4      | 14.81%  |
| Kingston            | 3         | 4      | 11.11%  |
| WDC                 | 2         | 2      | 7.41%   |
| LITEONIT            | 2         | 2      | 7.41%   |
| Apple               | 2         | 2      | 7.41%   |
| Mercury             | 1         | 1      | 3.7%    |
| LITEON              | 1         | 1      | 3.7%    |
| Intel               | 1         | 1      | 3.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 28        | 30     | 38.36%  |
| SSD     | 24        | 28     | 32.88%  |
| NVMe    | 14        | 16     | 19.18%  |
| Unknown | 4         | 4      | 5.48%   |
| MMC     | 3         | 3      | 4.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 47        | 60     | 71.21%  |
| NVMe | 14        | 16     | 21.21%  |
| MMC  | 3         | 3      | 4.55%   |
| SAS  | 2         | 2      | 3.03%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 30        | 38     | 61.22%  |
| 0.51-1.0   | 17        | 18     | 34.69%  |
| 1.01-2.0   | 2         | 2      | 4.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 27        | 45.76%  |
| 251-500    | 13        | 22.03%  |
| 501-1000   | 8         | 13.56%  |
| 1001-2000  | 4         | 6.78%   |
| 51-100     | 4         | 6.78%   |
| 1-20       | 2         | 3.39%   |
| 2001-3000  | 1         | 1.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 32        | 55.17%  |
| 21-50     | 9         | 15.52%  |
| 51-100    | 8         | 13.79%  |
| 101-250   | 4         | 6.9%    |
| 251-500   | 2         | 3.45%   |
| 1001-2000 | 2         | 3.45%   |
| 501-1000  | 1         | 1.72%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD5000BPKT-75PK4T0 500GB      | 1         | 1      | 33.33%  |
| Seagate ST320LT020-9YG142 320GB   | 1         | 1      | 33.33%  |
| SanDisk SD7SB3Q256G1002 256GB SSD | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Seagate | 1         | 1      | 33.33%  |
| SanDisk | 1         | 1      | 33.33%  |

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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 47        | 65     | 78.33%  |
| Works    | 10        | 13     | 16.67%  |
| Malfunc  | 3         | 3      | 5%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 49        | 69.01%  |
| AMD                       | 6         | 8.45%   |
| Sandisk                   | 5         | 7.04%   |
| Samsung Electronics       | 5         | 7.04%   |
| SK Hynix                  | 2         | 2.82%   |
| Phison Electronics        | 2         | 2.82%   |
| Micron/Crucial Technology | 1         | 1.41%   |
| Micron Technology         | 1         | 1.41%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 9         | 12.33%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 6         | 8.22%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 6         | 8.22%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 5         | 6.85%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 3         | 4.11%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 4.11%   |
| Sandisk WD Blue SN550 NVMe SSD                                                         | 2         | 2.74%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 2         | 2.74%   |
| Samsung NVMe SSD Controller 980                                                        | 2         | 2.74%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 2         | 2.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 2         | 2.74%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 2         | 2.74%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 2         | 2.74%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 2         | 2.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 2         | 2.74%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 2         | 2.74%   |
| SK Hynix Gold P31 SSD                                                                  | 1         | 1.37%   |
| SK Hynix BC511                                                                         | 1         | 1.37%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 1         | 1.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 1         | 1.37%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 1.37%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 1         | 1.37%   |
| Phison PS5013 E13 NVMe Controller                                                      | 1         | 1.37%   |
| Phison E12 NVMe Controller                                                             | 1         | 1.37%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                        | 1         | 1.37%   |
| Micron Non-Volatile memory controller                                                  | 1         | 1.37%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 1         | 1.37%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                        | 1         | 1.37%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 1         | 1.37%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 1         | 1.37%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 1         | 1.37%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 1         | 1.37%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 1.37%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 1         | 1.37%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 1         | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 1         | 1.37%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 42        | 60%     |
| NVMe | 14        | 20%     |
| RAID | 9         | 12.86%  |
| IDE  | 5         | 7.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 51        | 87.93%  |
| AMD    | 7         | 12.07%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz             | 4         | 6.9%    |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 2         | 3.45%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 3.45%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 3.45%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 2         | 3.45%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 3.45%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 3.45%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 3.45%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 3.45%   |
| Intel Xeon W-11855M CPU @ 3.20GHz             | 1         | 1.72%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 1.72%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 1.72%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.72%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 1.72%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 1.72%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 1.72%   |
| Intel Core i7-3687U CPU @ 2.10GHz             | 1         | 1.72%   |
| Intel Core i7-3667U CPU @ 2.00GHz             | 1         | 1.72%   |
| Intel Core i7-3615QM CPU @ 2.30GHz            | 1         | 1.72%   |
| Intel Core i7-2637M CPU @ 1.70GHz             | 1         | 1.72%   |
| Intel Core i7-2635QM CPU @ 2.00GHz            | 1         | 1.72%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 1.72%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.72%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.72%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.72%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 1.72%   |
| Intel Core i5-2435M CPU @ 2.40GHz             | 1         | 1.72%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz            | 1         | 1.72%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 1.72%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 1.72%   |
| Intel Core i3-6100U CPU @ 2.30GHz             | 1         | 1.72%   |
| Intel Core i3-5010U CPU @ 2.10GHz             | 1         | 1.72%   |
| Intel Core i3 CPU M 350 @ 2.27GHz             | 1         | 1.72%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz          | 1         | 1.72%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz          | 1         | 1.72%   |
| Intel Core 2 CPU T5500 @ 1.66GHz              | 1         | 1.72%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 1         | 1.72%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 1         | 1.72%   |
| Intel Celeron CPU N2807 @ 1.58GHz             | 1         | 1.72%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 1.72%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 1.72%   |
| AMD Ryzen 5 5600U with Radeon Graphics        | 1         | 1.72%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 1         | 1.72%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 1         | 1.72%   |
| AMD Phenom II N660 Dual-Core Processor        | 1         | 1.72%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics   | 1         | 1.72%   |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G  | 1         | 1.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 18        | 31.03%  |
| Intel Core i5           | 17        | 29.31%  |
| Other                   | 3         | 5.17%   |
| Intel Core i3           | 3         | 5.17%   |
| Intel Celeron           | 3         | 5.17%   |
| AMD Ryzen 5             | 3         | 5.17%   |
| Intel Pentium Dual-Core | 2         | 3.45%   |
| Intel Core 2 Duo        | 2         | 3.45%   |
| Intel Xeon              | 1         | 1.72%   |
| Intel Pentium           | 1         | 1.72%   |
| Intel Core 2            | 1         | 1.72%   |
| AMD Ryzen 7             | 1         | 1.72%   |
| AMD Phenom II           | 1         | 1.72%   |
| AMD A8                  | 1         | 1.72%   |
| AMD A6                  | 1         | 1.72%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 32        | 55.17%  |
| 4      | 22        | 37.93%  |
| 6      | 3         | 5.17%   |
| 8      | 1         | 1.72%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 58        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 45        | 77.59%  |
| 1      | 13        | 22.41%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 58        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x306a9    | 7         | 12.07%  |
| Unknown    | 7         | 12.07%  |
| 0x406e3    | 5         | 8.62%   |
| 0x806ea    | 4         | 6.9%    |
| 0x806c1    | 3         | 5.17%   |
| 0x40651    | 3         | 5.17%   |
| 0x306c3    | 3         | 5.17%   |
| 0x1067a    | 3         | 5.17%   |
| 0x906e9    | 2         | 3.45%   |
| 0x806eb    | 2         | 3.45%   |
| 0x806e9    | 2         | 3.45%   |
| 0x406c3    | 2         | 3.45%   |
| 0x206a7    | 2         | 3.45%   |
| 0x20652    | 2         | 3.45%   |
| 0x806ec    | 1         | 1.72%   |
| 0x706e5    | 1         | 1.72%   |
| 0x706a8    | 1         | 1.72%   |
| 0x6fd      | 1         | 1.72%   |
| 0x306d4    | 1         | 1.72%   |
| 0x30678    | 1         | 1.72%   |
| 0x0a50000c | 1         | 1.72%   |
| 0x08101007 | 1         | 1.72%   |
| 0x07030105 | 1         | 1.72%   |
| 0x06006705 | 1         | 1.72%   |
| 0x010000c8 | 1         | 1.72%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 12        | 20.69%  |
| IvyBridge     | 7         | 12.07%  |
| Skylake       | 6         | 10.34%  |
| Haswell       | 6         | 10.34%  |
| TigerLake     | 3         | 5.17%   |
| Silvermont    | 3         | 5.17%   |
| SandyBridge   | 3         | 5.17%   |
| Penryn        | 3         | 5.17%   |
| Westmere      | 2         | 3.45%   |
| Core          | 2         | 3.45%   |
| Zen+          | 1         | 1.72%   |
| Zen 3         | 1         | 1.72%   |
| Zen 2         | 1         | 1.72%   |
| Zen           | 1         | 1.72%   |
| Puma          | 1         | 1.72%   |
| K10           | 1         | 1.72%   |
| IceLake       | 1         | 1.72%   |
| Goldmont plus | 1         | 1.72%   |
| Excavator     | 1         | 1.72%   |
| Broadwell     | 1         | 1.72%   |
| Unknown       | 1         | 1.72%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 47        | 64.38%  |
| Nvidia | 17        | 23.29%  |
| AMD    | 9         | 12.33%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 9.33%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 8%      |
| Intel UHD Graphics 620                                                                   | 4         | 5.33%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 4%      |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 4%      |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 2.67%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                              | 2         | 2.67%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 2.67%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 2.67%   |
| Intel HD Graphics 630                                                                    | 2         | 2.67%   |
| Intel HD Graphics 620                                                                    | 2         | 2.67%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 2.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 2.67%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 2.67%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 2.67%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 2.67%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.33%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 1.33%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 1         | 1.33%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.33%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 1.33%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 1.33%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 1.33%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 1.33%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 1.33%   |
| Nvidia GK106M [GeForce GTX 770M]                                                         | 1         | 1.33%   |
| Nvidia GA104GLM [RTX A3000 Mobile]                                                       | 1         | 1.33%   |
| Nvidia G94GLM [Quadro FX 2700M]                                                          | 1         | 1.33%   |
| Nvidia G73M [GeForce Go 7600]                                                            | 1         | 1.33%   |
| Intel VGA compatible controller                                                          | 1         | 1.33%   |
| Intel Tiger Lake UHD Graphics                                                            | 1         | 1.33%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                                   | 1         | 1.33%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.33%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.33%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.33%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 1.33%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 1.33%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 1.33%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 1         | 1.33%   |
| AMD Renoir                                                                               | 1         | 1.33%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 1.33%   |
| AMD Picasso                                                                              | 1         | 1.33%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 1.33%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 1         | 1.33%   |
| AMD Cezanne                                                                              | 1         | 1.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 33        | 56.9%   |
| Intel + Nvidia | 13        | 22.41%  |
| 1 x AMD        | 5         | 8.62%   |
| 1 x Nvidia     | 3         | 5.17%   |
| 2 x AMD        | 2         | 3.45%   |
| Intel + AMD    | 1         | 1.72%   |
| AMD + Nvidia   | 1         | 1.72%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 49        | 84.48%  |
| Proprietary | 7         | 12.07%  |
| Unknown     | 2         | 3.45%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 43        | 74.14%  |
| 1.01-2.0   | 5         | 8.62%   |
| 0.51-1.0   | 4         | 6.9%    |
| 0.01-0.5   | 4         | 6.9%    |
| 3.01-4.0   | 1         | 1.72%   |
| 2.01-3.0   | 1         | 1.72%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 15        | 24.59%  |
| LG Display              | 9         | 14.75%  |
| AU Optronics            | 9         | 14.75%  |
| BOE                     | 7         | 11.48%  |
| Apple                   | 6         | 9.84%   |
| Samsung Electronics     | 4         | 6.56%   |
| Sharp                   | 3         | 4.92%   |
| Lenovo                  | 2         | 3.28%   |
| AOC                     | 2         | 3.28%   |
| ViewSonic               | 1         | 1.64%   |
| Seiko/Epson             | 1         | 1.64%   |
| Goldstar                | 1         | 1.64%   |
| Chi Mei Optoelectronics | 1         | 1.64%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 340x190mm 15.3-inch         | 2         | 3.28%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch           | 2         | 3.28%   |
| Apple Color LCD APPA014 2560x1600 286x179mm 13.3-inch                    | 2         | 3.28%   |
| Apple Color LCD APP9CA4 1440x900 331x207mm 15.4-inch                     | 2         | 3.28%   |
| ViewSonic VA2445 SERIES VSC712E 1920x1080 521x293mm 23.5-inch            | 1         | 1.64%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 1.64%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 1         | 1.64%   |
| Sharp LCD Monitor SHP1420 1920x1080 290x170mm 13.2-inch                  | 1         | 1.64%   |
| Seiko/Epson LCD Monitor 1920x1080                                        | 1         | 1.64%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch     | 1         | 1.64%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 340x190mm 15.3-inch     | 1         | 1.64%   |
| Samsung Electronics LCD Monitor SDC4E42 1366x768 309x174mm 14.0-inch     | 1         | 1.64%   |
| Samsung Electronics C27F591 SAM0D36 1920x1080 598x336mm 27.0-inch        | 1         | 1.64%   |
| LG Display LP156WH2-TLE1 LGDCF01 1366x768 344x194mm 15.5-inch            | 1         | 1.64%   |
| LG Display LCD Monitor LGD06AD 2560x1600 286x179mm 13.3-inch             | 1         | 1.64%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch             | 1         | 1.64%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 1         | 1.64%   |
| LG Display LCD Monitor LGD0382 1600x900 310x170mm 13.9-inch              | 1         | 1.64%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch              | 1         | 1.64%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch             | 1         | 1.64%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 1         | 1.64%   |
| LG Display LCD Monitor LGD022C 1366x768 294x166mm 13.3-inch              | 1         | 1.64%   |
| Lenovo LCD Monitor LEN4067 1920x1200 370x230mm 17.2-inch                 | 1         | 1.64%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 1         | 1.64%   |
| Goldstar MP59HT GSM5B44 1920x1080 480x270mm 21.7-inch                    | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN15E0 1920x1080 344x193mm 15.5-inch         | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN15D3 1920x1080 344x193mm 15.5-inch         | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 340x190mm 15.3-inch          | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 344x193mm 15.5-inch         | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN1514 1920x1080 344x193mm 15.5-inch         | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN1512 1920x1080 344x193mm 15.5-inch         | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN1477 1366x768 309x174mm 14.0-inch          | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN1361 1920x1080 290x170mm 13.2-inch         | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN1338 1366x768 293x164mm 13.2-inch          | 1         | 1.64%   |
| Chi Mei Optoelectronics LCD Monitor CMO1711 1600x900 382x215mm 17.3-inch | 1         | 1.64%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 1         | 1.64%   |
| BOE LCD Monitor BOE0726 1920x1080 344x193mm 15.5-inch                    | 1         | 1.64%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                    | 1         | 1.64%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 1         | 1.64%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 1         | 1.64%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 1         | 1.64%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 1         | 1.64%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch            | 1         | 1.64%   |
| AU Optronics LCD Monitor AUO623D 1920x1080 309x174mm 14.0-inch           | 1         | 1.64%   |
| AU Optronics LCD Monitor AUO413D 1920x1080 309x173mm 13.9-inch           | 1         | 1.64%   |
| AU Optronics LCD Monitor AUO32ED 1920x1080 344x193mm 15.5-inch           | 1         | 1.64%   |
| AU Optronics LCD Monitor AUO235C 1366x768 260x140mm 11.6-inch            | 1         | 1.64%   |
| AU Optronics LCD Monitor AUO12D4 1280x800 216x135mm 10.0-inch            | 1         | 1.64%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 1         | 1.64%   |
| Apple Color LCD APP9CC7 1280x800 290x180mm 13.4-inch                     | 1         | 1.64%   |
| Apple Color LCD APP9CB7 1680x1050 331x207mm 15.4-inch                    | 1         | 1.64%   |
| AOC e2752Vq AOC2752 1920x1080 598x336mm 27.0-inch                        | 1         | 1.64%   |
| AOC 22V2WG5 AOC2202 1920x1080 476x268mm 21.5-inch                        | 1         | 1.64%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 23        | 41.07%  |
| 1366x768 (WXGA)    | 20        | 35.71%  |
| 2560x1600          | 3         | 5.36%   |
| 1280x800 (WXGA)    | 3         | 5.36%   |
| 1600x900 (HD+)     | 2         | 3.57%   |
| 1440x900 (WXGA+)   | 2         | 3.57%   |
| 3840x2400          | 1         | 1.79%   |
| 1920x1200 (WUXGA)  | 1         | 1.79%   |
| 1680x1050 (WSXGA+) | 1         | 1.79%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 27        | 44.26%  |
| 13      | 15        | 24.59%  |
| 14      | 6         | 9.84%   |
| 17      | 3         | 4.92%   |
| 27      | 2         | 3.28%   |
| 21      | 2         | 3.28%   |
| 12      | 2         | 3.28%   |
| 23      | 1         | 1.64%   |
| 11      | 1         | 1.64%   |
| 10      | 1         | 1.64%   |
| Unknown | 1         | 1.64%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 38        | 63.33%  |
| 201-300     | 13        | 21.67%  |
| 351-400     | 4         | 6.67%   |
| 501-600     | 2         | 3.33%   |
| 401-500     | 2         | 3.33%   |
| Unknown     | 1         | 1.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 44        | 78.57%  |
| 16/10   | 10        | 17.86%  |
| 3/2     | 1         | 1.79%   |
| Unknown | 1         | 1.79%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inchÂ² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 27        | 44.26%  |
| 81-90          | 13        | 21.31%  |
| 71-80          | 8         | 13.11%  |
| 61-70          | 2         | 3.28%   |
| 301-350        | 2         | 3.28%   |
| 201-250        | 2         | 3.28%   |
| 131-140        | 2         | 3.28%   |
| 51-60          | 1         | 1.64%   |
| 41-50          | 1         | 1.64%   |
| 151-200        | 1         | 1.64%   |
| 121-130        | 1         | 1.64%   |
| Unknown        | 1         | 1.64%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 26        | 43.33%  |
| 101-120       | 23        | 38.33%  |
| 161-240       | 6         | 10%     |
| 51-100        | 3         | 5%      |
| More than 240 | 1         | 1.67%   |
| Unknown       | 1         | 1.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 53        | 91.38%  |
| 3     | 2         | 3.45%   |
| 0     | 2         | 3.45%   |
| 2     | 1         | 1.72%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 31        | 32.98%  |
| Intel                             | 29        | 30.85%  |
| Broadcom                          | 12        | 12.77%  |
| Qualcomm Atheros                  | 9         | 9.57%   |
| MEDIATEK                          | 2         | 2.13%   |
| TP-Link                           | 1         | 1.06%   |
| Samsung Electronics               | 1         | 1.06%   |
| Ralink Technology                 | 1         | 1.06%   |
| Ralink                            | 1         | 1.06%   |
| Qualcomm                          | 1         | 1.06%   |
| OPPO                              | 1         | 1.06%   |
| NEC Computers                     | 1         | 1.06%   |
| Huawei Technologies               | 1         | 1.06%   |
| Ericsson Business Mobile Networks | 1         | 1.06%   |
| DisplayLink                       | 1         | 1.06%   |
| Broadcom Limited                  | 1         | 1.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20        | 17.7%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 6         | 5.31%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 4.42%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 4.42%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 3.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 2.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 2.65%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 1.77%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 1.77%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 2         | 1.77%   |
| Intel Wireless 8260                                               | 2         | 1.77%   |
| Intel Wireless 7265                                               | 2         | 1.77%   |
| Intel Wireless 7260                                               | 2         | 1.77%   |
| Intel Wireless 3165                                               | 2         | 1.77%   |
| Intel Wireless 3160                                               | 2         | 1.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 1.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.77%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 1.77%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 1.77%   |
| TP-Link TL-WN722N v2                                              | 1         | 0.88%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.88%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.88%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.88%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.88%   |
| Qualcomm Smart Ultra 6                                            | 1         | 0.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.88%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.88%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1         | 0.88%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.88%   |
| OPPO SDM665-IDP _SN:6A6C23F9                                      | 1         | 0.88%   |
| NEC Computers WiMAX Mobile Router                                 | 1         | 0.88%   |
| MediaTek Titan                                                    | 1         | 0.88%   |
| MEDIATEK Network controller                                       | 1         | 0.88%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 0.88%   |
| Intel Ultimate N WiFi Link 5300                                   | 1         | 0.88%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 0.88%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 0.88%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.88%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.88%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.88%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.88%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 0.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 0.88%   |
| Intel Centrino Wireless-N 2230                                    | 1         | 0.88%   |
| Intel Centrino Advanced-N 6235                                    | 1         | 0.88%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                     | 1         | 0.88%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 0.88%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.88%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.88%   |
| Huawei Broadband stick                                            | 1         | 0.88%   |
| Ericsson Business Mobile Networks N5321 gw                        | 1         | 0.88%   |
| DisplayLink StarTech.com Universal Dock                           | 1         | 0.88%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 0.88%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.88%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter        | 1         | 0.88%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 1         | 0.88%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 27        | 45%     |
| Broadcom              | 11        | 18.33%  |
| Realtek Semiconductor | 9         | 15%     |
| Qualcomm Atheros      | 8         | 13.33%  |
| TP-Link               | 1         | 1.67%   |
| Ralink Technology     | 1         | 1.67%   |
| Ralink                | 1         | 1.67%   |
| MEDIATEK              | 1         | 1.67%   |
| Broadcom Limited      | 1         | 1.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Broadcom BCM4331 802.11a/b/g/n                             | 6         | 10%     |
| Intel Wi-Fi 6 AX200                                        | 5         | 8.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 3         | 5%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 3         | 5%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 2         | 3.33%   |
| Realtek RTL8723DE Wireless Network Adapter                 | 2         | 3.33%   |
| Realtek RTL8191SEvB Wireless LAN Controller                | 2         | 3.33%   |
| Intel Wireless 8260                                        | 2         | 3.33%   |
| Intel Wireless 7265                                        | 2         | 3.33%   |
| Intel Wireless 7260                                        | 2         | 3.33%   |
| Intel Wireless 3165                                        | 2         | 3.33%   |
| Intel Wireless 3160                                        | 2         | 3.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]               | 2         | 3.33%   |
| Broadcom BCM43142 802.11b/g/n                              | 2         | 3.33%   |
| TP-Link TL-WN722N v2                                       | 1         | 1.67%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter   | 1         | 1.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 1.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1         | 1.67%   |
| Ralink RT5370 Wireless Adapter                             | 1         | 1.67%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                  | 1         | 1.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 1.67%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter           | 1         | 1.67%   |
| MEDIATEK Network controller                                | 1         | 1.67%   |
| Intel Wi-Fi 6 AX201                                        | 1         | 1.67%   |
| Intel Ultimate N WiFi Link 5300                            | 1         | 1.67%   |
| Intel Tiger Lake PCH CNVi WiFi                             | 1         | 1.67%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection      | 1         | 1.67%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth            | 1         | 1.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 1         | 1.67%   |
| Intel Centrino Wireless-N 2230                             | 1         | 1.67%   |
| Intel Centrino Advanced-N 6235                             | 1         | 1.67%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]              | 1         | 1.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                   | 1         | 1.67%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter | 1         | 1.67%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter         | 1         | 1.67%   |
| Broadcom BCM43228 802.11a/b/g/n                            | 1         | 1.67%   |
| Broadcom BCM4312 802.11b/g LP-PHY                          | 1         | 1.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 26        | 53.06%  |
| Intel                 | 9         | 18.37%  |
| Broadcom              | 7         | 14.29%  |
| Qualcomm Atheros      | 2         | 4.08%   |
| Samsung Electronics   | 1         | 2.04%   |
| Qualcomm              | 1         | 2.04%   |
| OPPO                  | 1         | 2.04%   |
| MediaTek              | 1         | 2.04%   |
| DisplayLink           | 1         | 2.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20        | 40%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 10%     |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 8%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 4%      |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 4%      |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 2%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2%      |
| Qualcomm Smart Ultra 6                                            | 1         | 2%      |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 2%      |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 2%      |
| OPPO SDM665-IDP _SN:6A6C23F9                                      | 1         | 2%      |
| MediaTek Titan                                                    | 1         | 2%      |
| Intel PRO/100 VE Network Connection                               | 1         | 2%      |
| Intel Ethernet Connection I219-LM                                 | 1         | 2%      |
| Intel Ethernet Connection I218-LM                                 | 1         | 2%      |
| Intel Ethernet Connection I217-LM                                 | 1         | 2%      |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2%      |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2%      |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2%      |
| DisplayLink StarTech.com Universal Dock                           | 1         | 2%      |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 2%      |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 2%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 57        | 54.81%  |
| Ethernet | 44        | 42.31%  |
| Modem    | 2         | 1.92%   |
| Unknown  | 1         | 0.96%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 51        | 57.95%  |
| Ethernet | 37        | 42.05%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 41        | 70.69%  |
| 1     | 16        | 27.59%  |
| 3     | 1         | 1.72%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 46        | 79.31%  |
| Yes  | 12        | 20.69%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 23        | 43.4%   |
| Realtek Semiconductor           | 7         | 13.21%  |
| Apple                           | 6         | 11.32%  |
| Broadcom                        | 5         | 9.43%   |
| Lite-On Technology              | 4         | 7.55%   |
| Qualcomm Atheros Communications | 3         | 5.66%   |
| Foxconn / Hon Hai               | 2         | 3.77%   |
| Ralink                          | 1         | 1.89%   |
| IMC Networks                    | 1         | 1.89%   |
| Dell                            | 1         | 1.89%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                             | 11        | 20.75%  |
| Intel Bluetooth wireless interface                 | 6         | 11.32%  |
| Intel AX200 Bluetooth                              | 5         | 9.43%   |
| Apple Bluetooth Host Controller                    | 4         | 7.55%   |
| Realtek Bluetooth Radio                            | 3         | 5.66%   |
| Realtek 802.11n WLAN Adapter                       | 2         | 3.77%   |
| Qualcomm Atheros  Bluetooth Device                 | 2         | 3.77%   |
| Lite-On Bluetooth Device                           | 2         | 3.77%   |
| Broadcom BCM43142A0 Bluetooth 4.0                  | 2         | 3.77%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]         | 2         | 3.77%   |
| Apple Bluetooth USB Host Controller                | 2         | 3.77%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter            | 1         | 1.89%   |
| Realtek  Bluetooth 4.2 Adapter                     | 1         | 1.89%   |
| Ralink RT3290 Bluetooth                            | 1         | 1.89%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0              | 1         | 1.89%   |
| Lite-On Wireless_Device                            | 1         | 1.89%   |
| Lite-On Qualcomm Atheros Bluetooth                 | 1         | 1.89%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter   | 1         | 1.89%   |
| IMC Networks BCM20702A0                            | 1         | 1.89%   |
| Foxconn / Hon Hai Bluetooth Device                 | 1         | 1.89%   |
| Foxconn / Hon Hai BCM20702A0                       | 1         | 1.89%   |
| Dell Broadcom BCM20702A0 Bluetooth                 | 1         | 1.89%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 1.89%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 51        | 73.91%  |
| Nvidia | 9         | 13.04%  |
| AMD    | 8         | 11.59%  |
| TEAC   | 1         | 1.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 12        | 14.63%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 8.54%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 4.88%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 4         | 4.88%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 3.66%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 3.66%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 3.66%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 3.66%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 3.66%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 3.66%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 2.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 2.44%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 2.44%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 2.44%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 2.44%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 2.44%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 2.44%   |
| TEAC TASCAM iXR                                                                                   | 1         | 1.22%   |
| Nvidia stereo controller                                                                          | 1         | 1.22%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.22%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 1.22%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 1.22%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 1.22%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 1.22%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 1.22%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 1.22%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 1.22%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 1.22%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.22%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.22%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 1.22%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 1.22%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 1.22%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 1.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.22%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.22%   |
| AMD High Definition Audio Controller                                                              | 1         | 1.22%   |
| AMD FCH Azalia Controller                                                                         | 1         | 1.22%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 1.22%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 1.22%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 25.81%  |
| SK Hynix            | 6         | 19.35%  |
| Micron Technology   | 6         | 19.35%  |
| Kingston            | 5         | 16.13%  |
| Ramaxel Technology  | 2         | 6.45%   |
| Crucial             | 2         | 6.45%   |
| Toshiba             | 1         | 3.23%   |
| Qimonda             | 1         | 3.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA851S6CJR6N-VK 4096MB SODIMM DDR4 2667MT/s     | 2         | 6.25%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s         | 2         | 6.25%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s      | 2         | 6.25%   |
| Toshiba RAM 8HTF12864HDY-800G1 4GB SODIMM 1066MT/s            | 1         | 3.13%   |
| Toshiba RAM 64T128020EDL2.5C2 4GB SODIMM 1066MT/s             | 1         | 3.13%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s     | 1         | 3.13%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 1         | 3.13%   |
| SK Hynix RAM HMT325S6CFR8C-PB 2048MB SODIMM DDR3 1600MT/s     | 1         | 3.13%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s     | 1         | 3.13%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                | 1         | 3.13%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s      | 1         | 3.13%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s         | 1         | 3.13%   |
| Samsung RAM M4 70T5663EH3-CF7 2048MB SODIMM DDR2 2048MT/s     | 1         | 3.13%   |
| Ramaxel RAM RMT3170EF68F9W1600 4096MB SODIMM DDR3 1600MT/s    | 1         | 3.13%   |
| Ramaxel RAM RMSA3310NA86H9F-2666 4GB SODIMM DDR4 2667MT/s     | 1         | 3.13%   |
| Qimonda RAM 64T256020EDL2.5C2 2048MB SODIMM DDR2 2048MT/s     | 1         | 3.13%   |
| Micron RAM MT41K256M16LY 2GB SODIMM DDR3 1600MT/s             | 1         | 3.13%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                 | 1         | 3.13%   |
| Micron RAM Module 2048MB SODIMM DDR3 1600MT/s                 | 1         | 3.13%   |
| Micron RAM 4ATF51264HZ-2G6E3 4GB SODIMM DDR4 2667MT/s         | 1         | 3.13%   |
| Micron RAM 16JSF25664HZ-1G4F1 2GB SODIMM DDR3 1334MT/s        | 1         | 3.13%   |
| Micron RAM 16ATF2G64HZ-3G2J1 16384MB SODIMM DDR4 3200MT/s     | 1         | 3.13%   |
| Kingston RAM KHX2666C15S4/8G 8192MB SODIMM DDR4 2667MT/s      | 1         | 3.13%   |
| Kingston RAM HP16D3LS1KBG/8G 8192MB SODIMM DDR3 1600MT/s      | 1         | 3.13%   |
| Kingston RAM ACR16D3LS1KFG/8G 8192MB SODIMM DDR3 1600MT/s     | 1         | 3.13%   |
| Kingston RAM 9905700-070.A01G 16GB SODIMM DDR4 2667MT/s       | 1         | 3.13%   |
| Kingston RAM 9905700-026.A00G 8GB SODIMM DDR4 2667MT/s        | 1         | 3.13%   |
| Crucial RAM CT16G4SFRA32A.M16FRS 16384MB SODIMM DDR4 3200MT/s | 1         | 3.13%   |
| Crucial RAM CT16G4SFD824A.C16FDD 16GB SODIMM DDR4 2400MT/s    | 1         | 3.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Notebooks | Percent |
|-------|-----------|---------|
| DDR4  | 10        | 47.62%  |
| DDR3  | 9         | 42.86%  |
| SDRAM | 1         | 4.76%   |
| DDR2  | 1         | 4.76%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 21        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 11        | 44%     |
| 8192  | 6         | 24%     |
| 2048  | 5         | 20%     |
| 16384 | 3         | 12%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 9         | 37.5%   |
| 1600  | 8         | 33.33%  |
| 3200  | 2         | 8.33%   |
| 2400  | 1         | 4.17%   |
| 2133  | 1         | 4.17%   |
| 2048  | 1         | 4.17%   |
| 1334  | 1         | 4.17%   |
| 1066  | 1         | 4.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Brother Industries | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model             | Notebooks | Percent |
|-------------------|-----------|---------|
| Brother MFC-T800W | 1         | 100%    |

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
| Chicony Electronics                    | 12        | 22.64%  |
| Apple                                  | 7         | 13.21%  |
| Quanta                                 | 5         | 9.43%   |
| Microdia                               | 4         | 7.55%   |
| Acer                                   | 4         | 7.55%   |
| Suyin                                  | 3         | 5.66%   |
| Sunplus Innovation Technology          | 3         | 5.66%   |
| Realtek Semiconductor                  | 3         | 5.66%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 5.66%   |
| Syntek                                 | 2         | 3.77%   |
| SHENZHEN Fullhan                       | 1         | 1.89%   |
| Primax Electronics                     | 1         | 1.89%   |
| Luxvisions Innotech Limited            | 1         | 1.89%   |
| Lite-On Technology                     | 1         | 1.89%   |
| Lenovo                                 | 1         | 1.89%   |
| Importek                               | 1         | 1.89%   |
| DJKCVA1BIDQ8CL                         | 1         | 1.89%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Apple FaceTime HD Camera                                        | 4         | 7.55%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                        | 2         | 3.77%   |
| Realtek HD WebCam                                               | 2         | 3.77%   |
| Quanta HP TrueVision HD Camera                                  | 2         | 3.77%   |
| Microdia Integrated Webcam HD                                   | 2         | 3.77%   |
| Chicony integrated camera                                       | 2         | 3.77%   |
| Chicony HP Truevision HD                                        | 2         | 3.77%   |
| Chicony HD WebCam                                               | 2         | 3.77%   |
| Apple FaceTime HD Camera (Built-in)                             | 2         | 3.77%   |
| Acer Lenovo EasyCamera                                          | 2         | 3.77%   |
| Syntek Integrated Camera                                        | 1         | 1.89%   |
| Syntek EasyCamera                                               | 1         | 1.89%   |
| Suyin Asus Integrated Webcam                                    | 1         | 1.89%   |
| Sunplus Laptop_Integrated_Webcam_HD                             | 1         | 1.89%   |
| Sunplus Laptop_Integrated_Webcam_1.3M                           | 1         | 1.89%   |
| Sunplus Laptop Integrated WebCam HD                             | 1         | 1.89%   |
| SHENZHEN Fullhan webcam                                         | 1         | 1.89%   |
| Realtek Integrated_Webcam_HD                                    | 1         | 1.89%   |
| Quanta HP Webcam                                                | 1         | 1.89%   |
| Quanta HD User Facing                                           | 1         | 1.89%   |
| Quanta HD Camera                                                | 1         | 1.89%   |
| Primax Villem                                                   | 1         | 1.89%   |
| Microdia Laptop_Integrated_Webcam_FHD                           | 1         | 1.89%   |
| Microdia Integrated Webcam                                      | 1         | 1.89%   |
| Luxvisions Innotech Limited HP HD Camera                        | 1         | 1.89%   |
| Lite-On Integrated Camera                                       | 1         | 1.89%   |
| Lenovo Integrated Webcam                                        | 1         | 1.89%   |
| Importek Webcam HD                                              | 1         | 1.89%   |
| DJKCVA1BIDQ8CL HP TrueVision HD Camera                          | 1         | 1.89%   |
| Chicony USB2.0 Camera                                           | 1         | 1.89%   |
| Chicony HP Wide Vision HD                                       | 1         | 1.89%   |
| Chicony HP Webcam                                               | 1         | 1.89%   |
| Chicony HP Integrated Webcam                                    | 1         | 1.89%   |
| Chicony HP HD Webcam [Fixed]                                    | 1         | 1.89%   |
| Chicony HD User Facing                                          | 1         | 1.89%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 1         | 1.89%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 1         | 1.89%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera             | 1         | 1.89%   |
| Apple iPhone5/5C/5S/6                                           | 1         | 1.89%   |
| Acer SunplusIT Integrated Camera                                | 1         | 1.89%   |
| Acer Integrated Camera                                          | 1         | 1.89%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| LighTuning Technology | 3         | 37.5%   |
| Validity Sensors      | 2         | 25%     |
| Synaptics             | 1         | 12.5%   |
| STMicroelectronics    | 1         | 12.5%   |
| AuthenTec             | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| LighTuning EgisTec Touch Fingerprint Sensor | 3         | 37.5%   |
| Validity Sensors VFS495 Fingerprint Reader  | 1         | 12.5%   |
| Validity Sensors Swipe Fingerprint Sensor   | 1         | 12.5%   |
| Synaptics  WBDI                             | 1         | 12.5%   |
| STMicroelectronics Fingerprint Reader       | 1         | 12.5%   |
| AuthenTec AES2810                           | 1         | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Upek     | 1         | 50%     |
| Broadcom | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 50%     |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 36        | 62.07%  |
| 1     | 17        | 29.31%  |
| 2     | 5         | 8.62%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 8         | 28.57%  |
| Graphics card         | 6         | 21.43%  |
| Net/wireless          | 5         | 17.86%  |
| Net/ethernet          | 2         | 7.14%   |
| Multimedia controller | 2         | 7.14%   |
| Chipcard              | 2         | 7.14%   |
| Sound                 | 1         | 3.57%   |
| Camera                | 1         | 3.57%   |
| Bluetooth             | 1         | 3.57%   |

