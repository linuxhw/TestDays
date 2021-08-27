Zorin 16 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for Zorin 16 (Beta test).

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=zorin-16

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
| Dell          | XPS 13 9310                 | [08009ad892](https://linux-hardware.org/?probe=08009ad892) | Aug 26, 2021 |
| Acer          | AO722                       | [e303d0c046](https://linux-hardware.org/?probe=e303d0c046) | Aug 25, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [2199b6e642](https://linux-hardware.org/?probe=2199b6e642) | Aug 25, 2021 |
| Dell          | Inspiron 7520               | [1798e6404c](https://linux-hardware.org/?probe=1798e6404c) | Aug 25, 2021 |
| Unknown       | Unknown                     | [e18bc8fe09](https://linux-hardware.org/?probe=e18bc8fe09) | Aug 25, 2021 |
| Acer          | Aspire ES1-512              | [48b43bd242](https://linux-hardware.org/?probe=48b43bd242) | Aug 25, 2021 |
| Unknown       | Unknown                     | [e576736426](https://linux-hardware.org/?probe=e576736426) | Aug 25, 2021 |
| TianBei       | TB-H7                       | [455dce9834](https://linux-hardware.org/?probe=455dce9834) | Aug 25, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [a64e3a0513](https://linux-hardware.org/?probe=a64e3a0513) | Aug 25, 2021 |
| LG Electro... | S460-G.BG31P1               | [99df59aebd](https://linux-hardware.org/?probe=99df59aebd) | Aug 24, 2021 |
| HP            | ENVY Sleekbook 4 PC         | [3d58cb6ce0](https://linux-hardware.org/?probe=3d58cb6ce0) | Aug 24, 2021 |
| Acer          | Aspire 7715Z                | [4de4de1a31](https://linux-hardware.org/?probe=4de4de1a31) | Aug 24, 2021 |
| Lenovo        | G50-30 80G0                 | [27cdfce14b](https://linux-hardware.org/?probe=27cdfce14b) | Aug 24, 2021 |
| LG Electro... | A410-K.BE47P1               | [bfc75c9c3d](https://linux-hardware.org/?probe=bfc75c9c3d) | Aug 24, 2021 |
| Acer          | Aspire 8940G                | [24ff3cf596](https://linux-hardware.org/?probe=24ff3cf596) | Aug 23, 2021 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [b0830bd154](https://linux-hardware.org/?probe=b0830bd154) | Aug 23, 2021 |
| Dell          | Inspiron 5566               | [c56758deca](https://linux-hardware.org/?probe=c56758deca) | Aug 23, 2021 |
| Dell          | Inspiron 5566               | [eaef6e8392](https://linux-hardware.org/?probe=eaef6e8392) | Aug 23, 2021 |
| Dell          | Precision M4800             | [9766c85e7d](https://linux-hardware.org/?probe=9766c85e7d) | Aug 23, 2021 |
| Dell          | Precision M4800             | [cd3dbe3a32](https://linux-hardware.org/?probe=cd3dbe3a32) | Aug 23, 2021 |
| Unknown       | Unknown                     | [b1587c998f](https://linux-hardware.org/?probe=b1587c998f) | Aug 23, 2021 |
| TianBei       | TB-H7                       | [2d1b3b2756](https://linux-hardware.org/?probe=2d1b3b2756) | Aug 23, 2021 |
| ASUSTek       | X550LD                      | [04365cbbbf](https://linux-hardware.org/?probe=04365cbbbf) | Aug 22, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1CH0... | [43f252f22a](https://linux-hardware.org/?probe=43f252f22a) | Aug 22, 2021 |
| Apple         | MacBookPro11,5              | [814f16635c](https://linux-hardware.org/?probe=814f16635c) | Aug 22, 2021 |
| HP            | ProBook 450 G2              | [99f47f1645](https://linux-hardware.org/?probe=99f47f1645) | Aug 21, 2021 |
| Lenovo        | IdeaPad S540-14API 81NH     | [7b1954838a](https://linux-hardware.org/?probe=7b1954838a) | Aug 21, 2021 |
| HP            | Notebook                    | [2586dc3a41](https://linux-hardware.org/?probe=2586dc3a41) | Aug 21, 2021 |
| Lenovo        | G50-30 80G0                 | [afbefeb6d3](https://linux-hardware.org/?probe=afbefeb6d3) | Aug 21, 2021 |
| Lenovo        | ThinkPad X131e 3371AL2      | [1963322393](https://linux-hardware.org/?probe=1963322393) | Aug 21, 2021 |
| ASUSTek       | GR8                         | [88416da5e8](https://linux-hardware.org/?probe=88416da5e8) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | [ad6e3e064f](https://linux-hardware.org/?probe=ad6e3e064f) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | [9a5653e44d](https://linux-hardware.org/?probe=9a5653e44d) | Aug 21, 2021 |
| Sony          | VGN-SR5                     | [3bbd8b33f0](https://linux-hardware.org/?probe=3bbd8b33f0) | Aug 20, 2021 |
| HP            | ENVY 14                     | [34f9505762](https://linux-hardware.org/?probe=34f9505762) | Aug 20, 2021 |
| Lenovo        | G50-70 20351                | [40249b1ea8](https://linux-hardware.org/?probe=40249b1ea8) | Aug 20, 2021 |
| HP            | ENVY Sleekbook 4 PC         | [231e17454e](https://linux-hardware.org/?probe=231e17454e) | Aug 19, 2021 |
| Dell          | Inspiron N5040              | [0554d06022](https://linux-hardware.org/?probe=0554d06022) | Aug 19, 2021 |
| LG Electro... | 17U70N-R.AAS7U1             | [fd3572c46a](https://linux-hardware.org/?probe=fd3572c46a) | Aug 19, 2021 |
| Acer          | Nitro AN515-55              | [3a47dca146](https://linux-hardware.org/?probe=3a47dca146) | Aug 18, 2021 |
| HP            | ProBook 450 G2              | [a3e170c339](https://linux-hardware.org/?probe=a3e170c339) | Aug 17, 2021 |
| Acer          | Swift SF114-34              | [0a37eed9e8](https://linux-hardware.org/?probe=0a37eed9e8) | Aug 15, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [fcfd1e5ba9](https://linux-hardware.org/?probe=fcfd1e5ba9) | Aug 15, 2021 |
| HP            | ProBook 430 G6              | [c5467376e9](https://linux-hardware.org/?probe=c5467376e9) | Aug 13, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [9718804b4a](https://linux-hardware.org/?probe=9718804b4a) | Aug 12, 2021 |
| HP            | ProBook 450 G2              | [67956ca49e](https://linux-hardware.org/?probe=67956ca49e) | Aug 10, 2021 |
| Acer          | Aspire E1-571               | [146f910c76](https://linux-hardware.org/?probe=146f910c76) | Aug 09, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [c7a0820fe0](https://linux-hardware.org/?probe=c7a0820fe0) | Aug 09, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [950d41dbb8](https://linux-hardware.org/?probe=950d41dbb8) | Aug 09, 2021 |
| Dell          | Inspiron 7537               | [7a35ed5eb1](https://linux-hardware.org/?probe=7a35ed5eb1) | Aug 03, 2021 |
| Dell          | Inspiron 7537               | [3c865e72d1](https://linux-hardware.org/?probe=3c865e72d1) | Aug 03, 2021 |
| Acer          | Aspire E5-551G              | [519515ce84](https://linux-hardware.org/?probe=519515ce84) | Jul 15, 2021 |
| Dell          | XPS L501X                   | [a3d8e737a5](https://linux-hardware.org/?probe=a3d8e737a5) | Jul 08, 2021 |
| Dell          | G3 3579                     | [92a8136dc4](https://linux-hardware.org/?probe=92a8136dc4) | Jul 03, 2021 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [1196d6821c](https://linux-hardware.org/?probe=1196d6821c) | Jul 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [d63c7755ee](https://linux-hardware.org/?probe=d63c7755ee) | Jun 29, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [369a214905](https://linux-hardware.org/?probe=369a214905) | Jun 25, 2021 |
| Dell          | Inspiron 3576               | [849d571ef0](https://linux-hardware.org/?probe=849d571ef0) | Jun 24, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [9957b51bea](https://linux-hardware.org/?probe=9957b51bea) | Jun 24, 2021 |
| Dell          | Inspiron 3582               | [e2cd9a9c36](https://linux-hardware.org/?probe=e2cd9a9c36) | Jun 20, 2021 |
| Dell          | XPS 13 9370                 | [9e3a58b257](https://linux-hardware.org/?probe=9e3a58b257) | Jun 12, 2021 |
| Dell          | XPS 13 9370                 | [2aa1efb008](https://linux-hardware.org/?probe=2aa1efb008) | Jun 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [01cf29ba72](https://linux-hardware.org/?probe=01cf29ba72) | Jun 10, 2021 |
| HP            | 15                          | [f2132922af](https://linux-hardware.org/?probe=f2132922af) | Jun 08, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [a1dd6df8e7](https://linux-hardware.org/?probe=a1dd6df8e7) | Jun 07, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [957048adbb](https://linux-hardware.org/?probe=957048adbb) | Jun 06, 2021 |
| Dell          | Inspiron 3582               | [229600e417](https://linux-hardware.org/?probe=229600e417) | Jun 06, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [719041c9d4](https://linux-hardware.org/?probe=719041c9d4) | Jun 04, 2021 |
| HP            | ProBook 650 G2              | [bb92ab2244](https://linux-hardware.org/?probe=bb92ab2244) | May 30, 2021 |
| HP            | Unknown                     | [e6e060ca51](https://linux-hardware.org/?probe=e6e060ca51) | May 29, 2021 |
| HP            | Unknown                     | [324d49aba6](https://linux-hardware.org/?probe=324d49aba6) | May 29, 2021 |
| Razer         | Book 13 - RZ09-0357         | [c1cc1fcf2e](https://linux-hardware.org/?probe=c1cc1fcf2e) | May 27, 2021 |
| Dell          | Vostro 5490                 | [9d8401675e](https://linux-hardware.org/?probe=9d8401675e) | May 18, 2021 |
| Dell          | Vostro 5490                 | [3f02204090](https://linux-hardware.org/?probe=3f02204090) | May 18, 2021 |
| Acer          | Swift SF313-51              | [2b27dc30ac](https://linux-hardware.org/?probe=2b27dc30ac) | May 17, 2021 |
| ASUSTek       | X406UAR                     | [5c50159b19](https://linux-hardware.org/?probe=5c50159b19) | May 16, 2021 |
| ASUSTek       | X406UAR                     | [e3be0eaa69](https://linux-hardware.org/?probe=e3be0eaa69) | May 16, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [b71b291af5](https://linux-hardware.org/?probe=b71b291af5) | May 10, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [157ae0cc83](https://linux-hardware.org/?probe=157ae0cc83) | May 02, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [12081d4e79](https://linux-hardware.org/?probe=12081d4e79) | Apr 25, 2021 |
| Lenovo        | IdeaPad Y570 0862           | [94d22e7673](https://linux-hardware.org/?probe=94d22e7673) | Apr 23, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.11.0-27-generic | 29        | 50%     |
| 5.11.0-25-generic | 7         | 12.07%  |
| 5.8.0-53-generic  | 6         | 10.34%  |
| 5.8.0-59-generic  | 5         | 8.62%   |
| 5.8.0-55-generic  | 5         | 8.62%   |
| 5.8.0-50-generic  | 4         | 6.9%    |
| 5.8.0-63-generic  | 1         | 1.72%   |
| 5.10.0-1044-oem   | 1         | 1.72%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 36        | 62.07%  |
| 5.8.0   | 21        | 36.21%  |
| 5.10.0  | 1         | 1.72%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 36        | 62.07%  |
| 5.8     | 21        | 36.21%  |
| 5.10    | 1         | 1.72%   |

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


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| GNOME | 58        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 56        | 96.55%  |
| Wayland | 2         | 3.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 48        | 82.76%  |
| GDM     | 10        | 17.24%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 15        | 25.86%  |
| de_DE | 8         | 13.79%  |
| en_GB | 7         | 12.07%  |
| en_IN | 6         | 10.34%  |
| pt_BR | 5         | 8.62%   |
| es_ES | 3         | 5.17%   |
| nl_NL | 2         | 3.45%   |
| hu_HU | 2         | 3.45%   |
| ru_UA | 1         | 1.72%   |
| ja_JP | 1         | 1.72%   |
| fr_FR | 1         | 1.72%   |
| es_PE | 1         | 1.72%   |
| es_MX | 1         | 1.72%   |
| en_ZA | 1         | 1.72%   |
| en_PH | 1         | 1.72%   |
| en_NZ | 1         | 1.72%   |
| en_CA | 1         | 1.72%   |
| bg_BG | 1         | 1.72%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 41        | 70.69%  |
| BIOS | 17        | 29.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 55        | 94.83%  |
| Zfs     | 1         | 1.72%   |
| Overlay | 1         | 1.72%   |
| Btrfs   | 1         | 1.72%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 48        | 82.76%  |
| GPT     | 10        | 17.24%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 58        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 52        | 89.66%  |
| Yes       | 6         | 10.34%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 14        | 24.14%  |
| Dell             | 12        | 20.69%  |
| Acer             | 9         | 15.52%  |
| Hewlett-Packard  | 8         | 13.79%  |
| ASUSTek Computer | 5         | 8.62%   |
| LG Electronics   | 3         | 5.17%   |
| Apple            | 2         | 3.45%   |
| TianBei          | 1         | 1.72%   |
| Sony             | 1         | 1.72%   |
| Razer            | 1         | 1.72%   |
| Fujitsu          | 1         | 1.72%   |
| Unknown          | 1         | 1.72%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 2         | 3.45%   |
| TianBei TB-H7                            | 1         | 1.72%   |
| Sony VGN-SR5                             | 1         | 1.72%   |
| Razer Book 13 - RZ09-0357                | 1         | 1.72%   |
| LG S460-G.BG31P1                         | 1         | 1.72%   |
| LG A410-K.BE47P1                         | 1         | 1.72%   |
| LG 17U70N-R.AAS7U1                       | 1         | 1.72%   |
| Lenovo Yoga 3 Pro-1370 80HE              | 1         | 1.72%   |
| Lenovo ThinkPad Yoga 11e 20DAS0SF00      | 1         | 1.72%   |
| Lenovo ThinkPad X131e 3371AL2            | 1         | 1.72%   |
| Lenovo ThinkPad T440p 20AWS1CH00         | 1         | 1.72%   |
| Lenovo ThinkPad E15 Gen 2 20TD000HZA     | 1         | 1.72%   |
| Lenovo IdeaPad Z510 20287                | 1         | 1.72%   |
| Lenovo IdeaPad Y570 0862                 | 1         | 1.72%   |
| Lenovo IdeaPad S540-14API 81NH           | 1         | 1.72%   |
| Lenovo IdeaPad 5 15ALC05 82LN            | 1         | 1.72%   |
| Lenovo IdeaPad 330-15IKB 81DE            | 1         | 1.72%   |
| Lenovo IdeaPad 3 14ADA05 81W0            | 1         | 1.72%   |
| Lenovo IdeaPad 100-15IBD 80QQ            | 1         | 1.72%   |
| Lenovo G50-70 20351                      | 1         | 1.72%   |
| Lenovo G50-30 80G0                       | 1         | 1.72%   |
| HP ProBook 650 G2                        | 1         | 1.72%   |
| HP ProBook 450 G2                        | 1         | 1.72%   |
| HP ProBook 430 G6                        | 1         | 1.72%   |
| HP Notebook                              | 1         | 1.72%   |
| HP ENVY Sleekbook 4 PC                   | 1         | 1.72%   |
| HP ENVY 14                               | 1         | 1.72%   |
| HP 15                                    | 1         | 1.72%   |
| Fujitsu LIFEBOOK AH532                   | 1         | 1.72%   |
| Dell XPS L501X                           | 1         | 1.72%   |
| Dell XPS 13 9370                         | 1         | 1.72%   |
| Dell XPS 13 9310                         | 1         | 1.72%   |
| Dell Vostro 5490                         | 1         | 1.72%   |
| Dell Precision M4800                     | 1         | 1.72%   |
| Dell Inspiron N5040                      | 1         | 1.72%   |
| Dell Inspiron 7537                       | 1         | 1.72%   |
| Dell Inspiron 7520                       | 1         | 1.72%   |
| Dell Inspiron 5566                       | 1         | 1.72%   |
| Dell Inspiron 3582                       | 1         | 1.72%   |
| Dell Inspiron 3576                       | 1         | 1.72%   |
| Dell G3 3579                             | 1         | 1.72%   |
| ASUS X550LD                              | 1         | 1.72%   |
| ASUS X406UAR                             | 1         | 1.72%   |
| ASUS TUF Gaming FX505DT_FX505DT          | 1         | 1.72%   |
| ASUS GR8                                 | 1         | 1.72%   |
| ASUS ASUS TUF Gaming A15 FA506IH_FA506IH | 1         | 1.72%   |
| Apple MacBookPro11,5                     | 1         | 1.72%   |
| Apple MacBook4,1                         | 1         | 1.72%   |
| Acer Swift SF313-51                      | 1         | 1.72%   |
| Acer Swift SF114-34                      | 1         | 1.72%   |
| Acer Nitro AN515-55                      | 1         | 1.72%   |
| Acer Aspire ES1-512                      | 1         | 1.72%   |
| Acer Aspire E5-551G                      | 1         | 1.72%   |
| Acer Aspire E1-571                       | 1         | 1.72%   |
| Acer Aspire 8940G                        | 1         | 1.72%   |
| Acer Aspire 7715Z                        | 1         | 1.72%   |
| Acer AO722                               | 1         | 1.72%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo IdeaPad     | 7         | 12.07%  |
| Dell Inspiron      | 6         | 10.34%  |
| Acer Aspire        | 5         | 8.62%   |
| Lenovo ThinkPad    | 4         | 6.9%    |
| HP ProBook         | 3         | 5.17%   |
| Dell XPS           | 3         | 5.17%   |
| HP ENVY            | 2         | 3.45%   |
| Acer Swift         | 2         | 3.45%   |
| Unknown            | 2         | 3.45%   |
| TianBei TB-H7      | 1         | 1.72%   |
| Sony VGN-SR5       | 1         | 1.72%   |
| Razer Book         | 1         | 1.72%   |
| LG S460-G.BG31P1   | 1         | 1.72%   |
| LG A410-K.BE47P1   | 1         | 1.72%   |
| LG 17U70N-R.AAS7U1 | 1         | 1.72%   |
| Lenovo Yoga        | 1         | 1.72%   |
| Lenovo G50-70      | 1         | 1.72%   |
| Lenovo G50-30      | 1         | 1.72%   |
| HP Notebook        | 1         | 1.72%   |
| HP 15              | 1         | 1.72%   |
| Fujitsu LIFEBOOK   | 1         | 1.72%   |
| Dell Vostro        | 1         | 1.72%   |
| Dell Precision     | 1         | 1.72%   |
| Dell G3            | 1         | 1.72%   |
| ASUS X550LD        | 1         | 1.72%   |
| ASUS X406UAR       | 1         | 1.72%   |
| ASUS TUF           | 1         | 1.72%   |
| ASUS GR8           | 1         | 1.72%   |
| ASUS ASUS          | 1         | 1.72%   |
| Apple MacBookPro11 | 1         | 1.72%   |
| Apple MacBook4     | 1         | 1.72%   |
| Acer Nitro         | 1         | 1.72%   |
| Acer AO722         | 1         | 1.72%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 13        | 22.41%  |
| 2019 | 9         | 15.52%  |
| 2020 | 8         | 13.79%  |
| 2014 | 7         | 12.07%  |
| 2018 | 5         | 8.62%   |
| 2011 | 5         | 8.62%   |
| 2008 | 3         | 5.17%   |
| 2015 | 2         | 3.45%   |
| 2012 | 2         | 3.45%   |
| 2016 | 1         | 1.72%   |
| 2013 | 1         | 1.72%   |
| 2010 | 1         | 1.72%   |
| 2009 | 1         | 1.72%   |

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
| Disabled | 46        | 79.31%  |
| Enabled  | 12        | 20.69%  |

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
| 3.01-4.0   | 19        | 32.76%  |
| 4.01-8.0   | 17        | 29.31%  |
| 16.01-24.0 | 10        | 17.24%  |
| 8.01-16.0  | 10        | 17.24%  |
| 32.01-64.0 | 2         | 3.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 23        | 39.66%  |
| 2.01-3.0 | 19        | 32.76%  |
| 3.01-4.0 | 11        | 18.97%  |
| 4.01-8.0 | 4         | 6.9%    |
| 0.51-1.0 | 1         | 1.72%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 42        | 72.41%  |
| 2      | 14        | 24.14%  |
| 3      | 2         | 3.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 34        | 58.62%  |
| Yes       | 24        | 41.38%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 49        | 84.48%  |
| No        | 9         | 15.52%  |

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
| Yes       | 46        | 79.31%  |
| No        | 12        | 20.69%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| Germany      | 10        | 17.24%  |
| India        | 7         | 12.07%  |
| Brazil       | 7         | 12.07%  |
| USA          | 6         | 10.34%  |
| UK           | 6         | 10.34%  |
| Spain        | 3         | 5.17%   |
| Netherlands  | 2         | 3.45%   |
| Mexico       | 2         | 3.45%   |
| Hungary      | 2         | 3.45%   |
| Vietnam      | 1         | 1.72%   |
| Ukraine      | 1         | 1.72%   |
| South Africa | 1         | 1.72%   |
| Romania      | 1         | 1.72%   |
| Philippines  | 1         | 1.72%   |
| New Zealand  | 1         | 1.72%   |
| Madagascar   | 1         | 1.72%   |
| Japan        | 1         | 1.72%   |
| France       | 1         | 1.72%   |
| Colombia     | 1         | 1.72%   |
| Canada       | 1         | 1.72%   |
| Bulgaria     | 1         | 1.72%   |
| Austria      | 1         | 1.72%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Hyderabad                | 2         | 3.45%   |
| Yokohama                 | 1         | 1.72%   |
| Vienna                   | 1         | 1.72%   |
| Vancouver                | 1         | 1.72%   |
| Taboao da Serra          | 1         | 1.72%   |
| Sutton Coldfield         | 1         | 1.72%   |
| Stadskanaal              | 1         | 1.72%   |
| Spremberg                | 1         | 1.72%   |
| Seville                  | 1         | 1.72%   |
| S??o Lu?�s               | 1         | 1.72%   |
| S??o Jo??o del Rei       | 1         | 1.72%   |
| Sant Carles de la Rapita | 1         | 1.72%   |
| San Francisco            | 1         | 1.72%   |
| Sainte-Marie             | 1         | 1.72%   |
| R??sselsheim am Main     | 1         | 1.72%   |
| Quezon City              | 1         | 1.72%   |
| Pretoria                 | 1         | 1.72%   |
| Ohmbach                  | 1         | 1.72%   |
| Nyiregyhaza              | 1         | 1.72%   |
| Nottingham               | 1         | 1.72%   |
| Noblesville              | 1         | 1.72%   |
| Mérida                  | 1         | 1.72%   |
| Mumbai                   | 1         | 1.72%   |
| Morro do Chapeu          | 1         | 1.72%   |
| Montana                  | 1         | 1.72%   |
| Mexico City              | 1         | 1.72%   |
| Manchester               | 1         | 1.72%   |
| Madrid                   | 1         | 1.72%   |
| Macei??                  | 1         | 1.72%   |
| London                   | 1         | 1.72%   |
| Lathen                   | 1         | 1.72%   |
| Landshut                 | 1         | 1.72%   |
| Kyiv                     | 1         | 1.72%   |
| Kolkata                  | 1         | 1.72%   |
| Knoxville                | 1         | 1.72%   |
| Kingston                 | 1         | 1.72%   |
| Kelkheim (Taunus)        | 1         | 1.72%   |
| Ho Chi Minh City         | 1         | 1.72%   |
| Hartheim                 | 1         | 1.72%   |
| Hamm (Sieg)              | 1         | 1.72%   |
| Galgamacsa               | 1         | 1.72%   |
| Fortaleza                | 1         | 1.72%   |
| Finchley                 | 1         | 1.72%   |
| Ernakulam                | 1         | 1.72%   |
| Dudley                   | 1         | 1.72%   |
| Concord                  | 1         | 1.72%   |
| Chennai                  | 1         | 1.72%   |
| Charlotte                | 1         | 1.72%   |
| Bogot??                  | 1         | 1.72%   |
| Blankenrath              | 1         | 1.72%   |
| Berlin                   | 1         | 1.72%   |
| Belo Horizonte           | 1         | 1.72%   |
| Auckland                 | 1         | 1.72%   |
| Arad                     | 1         | 1.72%   |
| Antananarivo             | 1         | 1.72%   |
| Amsterdam                | 1         | 1.72%   |
| Ahmedabad                | 1         | 1.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 13     | 18.57%  |
| Seagate             | 12        | 12     | 17.14%  |
| Toshiba             | 7         | 7      | 10%     |
| SanDisk             | 7         | 7      | 10%     |
| WDC                 | 5         | 5      | 7.14%   |
| Kingston            | 3         | 4      | 4.29%   |
| HGST                | 3         | 3      | 4.29%   |
| Unknown             | 2         | 2      | 2.86%   |
| LITEONIT            | 2         | 3      | 2.86%   |
| Intel               | 2         | 2      | 2.86%   |
| Fujitsu             | 2         | 2      | 2.86%   |
| A-DATA Technology   | 2         | 2      | 2.86%   |
| Vaseky              | 1         | 1      | 1.43%   |
| SK Hynix            | 1         | 1      | 1.43%   |
| Phison              | 1         | 1      | 1.43%   |
| KIOXIA              | 1         | 1      | 1.43%   |
| KingSpec            | 1         | 1      | 1.43%   |
| Intenso             | 1         | 1      | 1.43%   |
| Crucial             | 1         | 1      | 1.43%   |
| China               | 1         | 1      | 1.43%   |
| BUFFALO             | 1         | 1      | 1.43%   |
| Apple               | 1         | 1      | 1.43%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB           | 3         | 4.23%   |
| Unknown SD/MMC/MS PRO 64GB               | 2         | 2.82%   |
| Toshiba MQ01ABF050 500GB                 | 2         | 2.82%   |
| Seagate ST9500325AS 500GB                | 2         | 2.82%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 2         | 2.82%   |
| SanDisk SSD PLUS 480GB                   | 2         | 2.82%   |
| Sandisk NVMe SSD Drive 256GB             | 2         | 2.82%   |
| Samsung NVMe SSD Drive 512GB             | 2         | 2.82%   |
| Kingston SA400S37480G 480GB SSD          | 2         | 2.82%   |
| HGST HTS725050A7E630 500GB               | 2         | 2.82%   |
| WDC WD5000LPVT-22G33T0 500GB             | 1         | 1.41%   |
| WDC WD5000BPVT-22HXZT3 500GB             | 1         | 1.41%   |
| WDC WD10JPVX-60JC3T1 1TB                 | 1         | 1.41%   |
| WDC WD10JPVX-22JC3T0 1TB                 | 1         | 1.41%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB     | 1         | 1.41%   |
| Vaseky V820/256G 256GB                   | 1         | 1.41%   |
| Toshiba THNSNJ128GCSU 128GB SSD          | 1         | 1.41%   |
| Toshiba MQ02ABD100H 1TB                  | 1         | 1.41%   |
| Toshiba MK3265GSX 320GB                  | 1         | 1.41%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD  | 1         | 1.41%   |
| Toshiba KBG40ZMT128G MEMORY 128GB        | 1         | 1.41%   |
| SK Hynix NVMe SSD Drive 512GB            | 1         | 1.41%   |
| Seagate USB 120GB                        | 1         | 1.41%   |
| Seagate ST500LM030-1RK17D 500GB          | 1         | 1.41%   |
| Seagate ST500LM021-1KJ152 500GB          | 1         | 1.41%   |
| Seagate ST320LM001 HN-M320MBB 320GB      | 1         | 1.41%   |
| Seagate ST1000LM014-1EJ1 1TB             | 1         | 1.41%   |
| SanDisk SSD PLUS 1000GB                  | 1         | 1.41%   |
| SanDisk SD8SN8U256G1002 256GB SSD        | 1         | 1.41%   |
| Sandisk NVMe SSD Drive 128GB             | 1         | 1.41%   |
| Samsung SSD SM841N mSATA 256GB SED       | 1         | 1.41%   |
| Samsung SSD PM830 2.5 7mm 128GB          | 1         | 1.41%   |
| Samsung SSD 860 PRO 256GB                | 1         | 1.41%   |
| Samsung SSD 860 EVO 1TB                  | 1         | 1.41%   |
| Samsung SSD 840 EVO 250GB                | 1         | 1.41%   |
| Samsung NVMe SSD Drive 2TB               | 1         | 1.41%   |
| Samsung MZVLB512HBJQ-00A00 512GB         | 1         | 1.41%   |
| Samsung MZALQ512HBLU-00BL2 512GB         | 1         | 1.41%   |
| Samsung HM640JJ 640GB                    | 1         | 1.41%   |
| Samsung HM321HI 320GB                    | 1         | 1.41%   |
| Samsung HM160HI 160GB                    | 1         | 1.41%   |
| Phison NVMe SSD Drive 2TB                | 1         | 1.41%   |
| LITEONIT LMS-32L6M mSATA 32GB SSD        | 1         | 1.41%   |
| LITEONIT LCT-512L9S-11 2.5 7mm 512GB SSD | 1         | 1.41%   |
| LITEONIT LCS-512M6S 2.5 7mm 512GB SSD    | 1         | 1.41%   |
| KIOXIA NVMe SSD Drive 512GB              | 1         | 1.41%   |
| Kingston SA400S37960G 960GB SSD          | 1         | 1.41%   |
| KingSpec NT-64 64GB                      | 1         | 1.41%   |
| Intenso SSD SATAIII 960GB                | 1         | 1.41%   |
| Intel SSDSC2KW256G8L 256GB               | 1         | 1.41%   |
| Intel SSDPEKNW512G8 512GB                | 1         | 1.41%   |
| HGST HTS721010A9E630 1TB                 | 1         | 1.41%   |
| Fujitsu MHZ2320BH G1 320GB               | 1         | 1.41%   |
| Fujitsu MHY2250BH 250GB                  | 1         | 1.41%   |
| Crucial CT480BX500SSD1 480GB             | 1         | 1.41%   |
| China SH00R480GB                         | 1         | 1.41%   |
| BUFFALO SSD-PUT/N 256GB                  | 1         | 1.41%   |
| Apple SSD SM0512G 500GB                  | 1         | 1.41%   |
| A-DATA SX900 256GB SSD                   | 1         | 1.41%   |
| A-DATA SX8200PNP 512GB                   | 1         | 1.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 11     | 40.74%  |
| WDC                 | 4         | 4      | 14.81%  |
| Toshiba             | 4         | 4      | 14.81%  |
| Samsung Electronics | 3         | 3      | 11.11%  |
| HGST                | 3         | 3      | 11.11%  |
| Fujitsu             | 2         | 2      | 7.41%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 5      | 20.83%  |
| SanDisk             | 4         | 4      | 16.67%  |
| Kingston            | 3         | 4      | 12.5%   |
| Toshiba             | 2         | 2      | 8.33%   |
| LITEONIT            | 2         | 3      | 8.33%   |
| KingSpec            | 1         | 1      | 4.17%   |
| Intenso             | 1         | 1      | 4.17%   |
| Intel               | 1         | 1      | 4.17%   |
| Crucial             | 1         | 1      | 4.17%   |
| China               | 1         | 1      | 4.17%   |
| BUFFALO             | 1         | 1      | 4.17%   |
| Apple               | 1         | 1      | 4.17%   |
| A-DATA Technology   | 1         | 1      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 27        | 27     | 40.91%  |
| SSD     | 20        | 26     | 30.3%   |
| NVMe    | 15        | 15     | 22.73%  |
| Unknown | 4         | 4      | 6.06%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 45        | 52     | 69.23%  |
| NVMe | 15        | 15     | 23.08%  |
| SAS  | 5         | 5      | 7.69%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 32        | 36     | 68.09%  |
| 0.51-1.0   | 15        | 17     | 31.91%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 25        | 43.1%   |
| 101-250    | 16        | 27.59%  |
| 501-1000   | 7         | 12.07%  |
| 51-100     | 5         | 8.62%   |
| 1001-2000  | 3         | 5.17%   |
| 21-50      | 1         | 1.72%   |
| Unknown    | 1         | 1.72%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 31        | 53.45%  |
| 21-50    | 15        | 25.86%  |
| 101-250  | 4         | 6.9%    |
| 51-100   | 3         | 5.17%   |
| 251-500  | 2         | 3.45%   |
| 501-1000 | 2         | 3.45%   |
| Unknown  | 1         | 1.72%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                      | Notebooks | Drives | Percent |
|----------------------------|-----------|--------|---------|
| Toshiba MQ02ABD100H 1TB    | 1         | 1      | 50%     |
| HGST HTS725050A7E630 500GB | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 50%     |
| HGST    | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 50%     |
| HGST    | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 2      | 100%    |

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
| Detected | 48        | 61     | 82.76%  |
| Works    | 8         | 9      | 13.79%  |
| Malfunc  | 2         | 2      | 3.45%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 41        | 63.08%  |
| AMD                              | 8         | 12.31%  |
| Samsung Electronics              | 6         | 9.23%   |
| Sandisk                          | 4         | 6.15%   |
| KIOXIA                           | 2         | 3.08%   |
| SK Hynix                         | 1         | 1.54%   |
| Silicon Integrated Systems [SiS] | 1         | 1.54%   |
| Phison Electronics               | 1         | 1.54%   |
| ADATA Technology                 | 1         | 1.54%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 7         | 10.14%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 7.25%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 5         | 7.25%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 5.8%    |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 3         | 4.35%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 4.35%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 4.35%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 4.35%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 4.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 2.9%    |
| Samsung NVMe Controller                                                        | 2         | 2.9%    |
| KIOXIA Non-Volatile memory controller                                          | 2         | 2.9%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 2.9%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 2.9%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 2.9%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 2.9%    |
| SK Hynix BC511                                                                 | 1         | 1.45%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 1         | 1.45%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 1         | 1.45%   |
| Sandisk PC SN520 NVMe SSD                                                      | 1         | 1.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 1.45%   |
| Samsung Electronics SATA controller                                            | 1         | 1.45%   |
| Phison E12 NVMe Controller                                                     | 1         | 1.45%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 1.45%   |
| Intel SSD 660P Series                                                          | 1         | 1.45%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 1.45%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.45%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.45%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]  | 1         | 1.45%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile     | 1         | 1.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 1.45%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.45%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 1.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 1.45%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1         | 1.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 44        | 65.67%  |
| NVMe | 15        | 22.39%  |
| RAID | 4         | 5.97%   |
| IDE  | 4         | 5.97%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 48        | 82.76%  |
| AMD    | 10        | 17.24%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 5.17%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 5.17%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 3.45%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 3.45%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 3.45%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 3.45%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 3.45%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 3.45%   |
| Intel Processor 5Y70 CPU @ 1.10GHz            | 1         | 1.72%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 1.72%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 1.72%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 1.72%   |
| Intel Pentium CPU 3550M @ 2.30GHz             | 1         | 1.72%   |
| Intel Core i7-4940MX CPU @ 3.10GHz            | 1         | 1.72%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz            | 1         | 1.72%   |
| Intel Core i7-4600M CPU @ 2.90GHz             | 1         | 1.72%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 1.72%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 1.72%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 1.72%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 1.72%   |
| Intel Core i7 CPU Q 740 @ 1.73GHz             | 1         | 1.72%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 1.72%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.72%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 1.72%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.72%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 1         | 1.72%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.72%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 1         | 1.72%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 1         | 1.72%   |
| Intel Core i3-6100U CPU @ 2.30GHz             | 1         | 1.72%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 1         | 1.72%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 1         | 1.72%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 1         | 1.72%   |
| Intel Core 2 Duo CPU T5450 @ 1.66GHz          | 1         | 1.72%   |
| Intel Core 2 Duo CPU P8800 @ 2.66GHz          | 1         | 1.72%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 1         | 1.72%   |
| Intel Celeron CPU N2940 @ 1.83GHz             | 1         | 1.72%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 1         | 1.72%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 1         | 1.72%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 1         | 1.72%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 1         | 1.72%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 1         | 1.72%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 1         | 1.72%   |
| AMD FX-7500 Radeon R7, 10 Compute Cores 4C+6G | 1         | 1.72%   |
| AMD E2-7110 APU with AMD Radeon R2 Graphics   | 1         | 1.72%   |
| AMD E-300 APU with Radeon HD Graphics         | 1         | 1.72%   |
| AMD C-60 APU with Radeon HD Graphics          | 1         | 1.72%   |
| AMD Athlon Gold 3150U with Radeon Graphics    | 1         | 1.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 17        | 29.31%  |
| Intel Core i7           | 11        | 18.97%  |
| Other                   | 4         | 6.9%    |
| Intel Core i3           | 4         | 6.9%    |
| Intel Core 2 Duo        | 4         | 6.9%    |
| Intel Celeron           | 4         | 6.9%    |
| AMD Ryzen 5             | 4         | 6.9%    |
| Intel Pentium           | 2         | 3.45%   |
| Intel Pentium Silver    | 1         | 1.72%   |
| Intel Pentium Dual-Core | 1         | 1.72%   |
| AMD Ryzen 7             | 1         | 1.72%   |
| AMD FX                  | 1         | 1.72%   |
| AMD E2                  | 1         | 1.72%   |
| AMD E                   | 1         | 1.72%   |
| AMD C-60                | 1         | 1.72%   |
| AMD Athlon              | 1         | 1.72%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 31        | 53.45%  |
| 4      | 25        | 43.1%   |
| 8      | 1         | 1.72%   |
| 6      | 1         | 1.72%   |

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
| 2      | 42        | 72.41%  |
| 1      | 16        | 27.59%  |

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
| 0x806ea    | 5         | 8.62%   |
| 0x40651    | 5         | 8.62%   |
| 0x306a9    | 5         | 8.62%   |
| 0x306d4    | 4         | 6.9%    |
| 0x806ec    | 3         | 5.17%   |
| 0x806c1    | 3         | 5.17%   |
| 0x306c3    | 3         | 5.17%   |
| 0x30678    | 3         | 5.17%   |
| 0x08108109 | 3         | 5.17%   |
| Unknown    | 3         | 5.17%   |
| 0x20655    | 2         | 3.45%   |
| 0x1067a    | 2         | 3.45%   |
| 0x05000119 | 2         | 3.45%   |
| 0xa0652    | 1         | 1.72%   |
| 0x906ea    | 1         | 1.72%   |
| 0x906c0    | 1         | 1.72%   |
| 0x706a1    | 1         | 1.72%   |
| 0x6fd      | 1         | 1.72%   |
| 0x6fb      | 1         | 1.72%   |
| 0x40661    | 1         | 1.72%   |
| 0x206a7    | 1         | 1.72%   |
| 0x106e5    | 1         | 1.72%   |
| 0x10676    | 1         | 1.72%   |
| 0x08608102 | 1         | 1.72%   |
| 0x08600104 | 1         | 1.72%   |
| 0x08108102 | 1         | 1.72%   |
| 0x07030106 | 1         | 1.72%   |
| 0x06003106 | 1         | 1.72%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 10        | 17.24%  |
| Haswell       | 9         | 15.52%  |
| IvyBridge     | 5         | 8.62%   |
| Zen+          | 4         | 6.9%    |
| Broadwell     | 4         | 6.9%    |
| TigerLake     | 3         | 5.17%   |
| Silvermont    | 3         | 5.17%   |
| Penryn        | 3         | 5.17%   |
| Westmere      | 2         | 3.45%   |
| Nehalem       | 2         | 3.45%   |
| Core          | 2         | 3.45%   |
| Bobcat        | 2         | 3.45%   |
| Zen 2         | 1         | 1.72%   |
| Tremont       | 1         | 1.72%   |
| Steamroller   | 1         | 1.72%   |
| Skylake       | 1         | 1.72%   |
| SandyBridge   | 1         | 1.72%   |
| Puma          | 1         | 1.72%   |
| Goldmont plus | 1         | 1.72%   |
| CometLake     | 1         | 1.72%   |
| Unknown       | 1         | 1.72%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 41        | 56.16%  |
| Nvidia                           | 16        | 21.92%  |
| AMD                              | 15        | 20.55%  |
| Silicon Integrated Systems [SiS] | 1         | 1.37%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                    | 5         | 6.67%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 5         | 6.67%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 5         | 6.67%   |
| AMD Picasso                                                               | 4         | 5.33%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 3         | 4%      |
| Intel HD Graphics 5500                                                    | 3         | 4%      |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 3         | 4%      |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 2.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 2.67%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter         | 1         | 1.33%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 1.33%   |
| Nvidia TU117M                                                             | 1         | 1.33%   |
| Nvidia GT218M [GeForce 310M]                                              | 1         | 1.33%   |
| Nvidia GT216M [GeForce GT 240M]                                           | 1         | 1.33%   |
| Nvidia GP108M [GeForce MX250]                                             | 1         | 1.33%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 1.33%   |
| Nvidia GM107M [GeForce GTX 860M]                                          | 1         | 1.33%   |
| Nvidia GK208M [GeForce GT 740M]                                           | 1         | 1.33%   |
| Nvidia GK208BM [GeForce 920M]                                             | 1         | 1.33%   |
| Nvidia GK107M [GeForce GT 750M]                                           | 1         | 1.33%   |
| Nvidia GK107GLM [Quadro K1100M]                                           | 1         | 1.33%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 1         | 1.33%   |
| Nvidia GF108M [GeForce GT 555M]                                           | 1         | 1.33%   |
| Nvidia GF108M [GeForce GT 435M]                                           | 1         | 1.33%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 1         | 1.33%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 1.33%   |
| Intel Mobile GME965/GLE960 Integrated Graphics Controller                 | 1         | 1.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 1         | 1.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 1         | 1.33%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 1.33%   |
| Intel JasperLake [UHD Graphics]                                           | 1         | 1.33%   |
| Intel HD Graphics 620                                                     | 1         | 1.33%   |
| Intel HD Graphics 5300                                                    | 1         | 1.33%   |
| Intel Haswell Integrated Graphics Controller                              | 1         | 1.33%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 1         | 1.33%   |
| Intel Core Processor Integrated Graphics Controller                       | 1         | 1.33%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 1         | 1.33%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 1         | 1.33%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 1         | 1.33%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1         | 1.33%   |
| AMD Wrestler [Radeon HD 6310]                                             | 1         | 1.33%   |
| AMD Wrestler [Radeon HD 6290]                                             | 1         | 1.33%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                           | 1         | 1.33%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                    | 1         | 1.33%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                         | 1         | 1.33%   |
| AMD Renoir                                                                | 1         | 1.33%   |
| AMD Opal XT [Radeon R7 M265/M365X/M465]                                   | 1         | 1.33%   |
| AMD Mullins [Radeon R3 Graphics]                                          | 1         | 1.33%   |
| AMD Lucienne                                                              | 1         | 1.33%   |
| AMD Kaveri [Radeon R6/R7 Graphics]                                        | 1         | 1.33%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]              | 1         | 1.33%   |
| AMD Chelsea LP [Radeon HD 7730M]                                          | 1         | 1.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 28        | 48.28%  |
| Intel + Nvidia | 10        | 17.24%  |
| 1 x AMD        | 9         | 15.52%  |
| 1 x Nvidia     | 4         | 6.9%    |
| Intel + AMD    | 3         | 5.17%   |
| AMD + Nvidia   | 2         | 3.45%   |
| 2 x AMD        | 1         | 1.72%   |
| 1 x SiS        | 1         | 1.72%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 46        | 79.31%  |
| Proprietary | 11        | 18.97%  |
| Unknown     | 1         | 1.72%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 33        | 56.9%   |
| 1.01-2.0   | 13        | 22.41%  |
| 0.01-0.5   | 6         | 10.34%  |
| 3.01-4.0   | 4         | 6.9%    |
| 0.51-1.0   | 2         | 3.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 13        | 21.31%  |
| Chimei Innolux          | 11        | 18.03%  |
| LG Display              | 8         | 13.11%  |
| BOE                     | 7         | 11.48%  |
| Samsung Electronics     | 5         | 8.2%    |
| Sharp                   | 3         | 4.92%   |
| PANDA                   | 2         | 3.28%   |
| Chi Mei Optoelectronics | 2         | 3.28%   |
| Apple                   | 2         | 3.28%   |
| Acer                    | 2         | 3.28%   |
| LGD                     | 1         | 1.64%   |
| Lenovo                  | 1         | 1.64%   |
| Hewlett-Packard         | 1         | 1.64%   |
| Dell                    | 1         | 1.64%   |
| BenQ                    | 1         | 1.64%   |
| AOC                     | 1         | 1.64%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15C6 1366x768 340x190mm 15.3-inch           | 2         | 3.23%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch             | 2         | 3.23%   |
| Sharp LQ134R1JX48 SHP1528 3840x2400 288x180mm 13.4-inch                   | 1         | 1.61%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                   | 1         | 1.61%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                   | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 344x194mm 15.5-inch      | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SEC3143 1366x768 256x144mm 11.6-inch      | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 409x230mm 18.5-inch     | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SDC4852 3840x2160 340x190mm 15.3-inch     | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 293x165mm 13.2-inch     | 1         | 1.61%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 1         | 1.61%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                   | 1         | 1.61%   |
| LGD LCD Monitor 3840x1200                                                 | 1         | 1.61%   |
| LG Display LCD Monitor LGD05F8 2560x1600 366x229mm 17.0-inch              | 1         | 1.61%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch              | 1         | 1.61%   |
| LG Display LCD Monitor LGD0468 1366x768 340x190mm 15.3-inch               | 1         | 1.61%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch               | 1         | 1.61%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch               | 1         | 1.61%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch               | 1         | 1.61%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch               | 1         | 1.61%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 1         | 1.61%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 1         | 1.61%   |
| Hewlett-Packard LCD Monitor E241i                                         | 1         | 1.61%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                         | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 340x190mm 15.3-inch          | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 340x190mm 15.3-inch           | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15BD 1366x768 344x194mm 15.5-inch           | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 350x190mm 15.7-inch           | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch          | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 309x174mm 14.0-inch           | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN139E 1920x1080 293x165mm 13.2-inch          | 1         | 1.61%   |
| Chi Mei Optoelectronics LCD Monitor CMO1807 1920x1080 408x230mm 18.4-inch | 1         | 1.61%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A4 1366x768 344x194mm 15.5-inch  | 1         | 1.61%   |
| BOE LCD Monitor BOE08F2 1920x1080 310x174mm 14.0-inch                     | 1         | 1.61%   |
| BOE LCD Monitor BOE082E 1920x1080 309x174mm 14.0-inch                     | 1         | 1.61%   |
| BOE LCD Monitor BOE07DD 1920x1080 293x165mm 13.2-inch                     | 1         | 1.61%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                     | 1         | 1.61%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                     | 1         | 1.61%   |
| BOE LCD Monitor BOE0700 1920x1080 340x190mm 15.3-inch                     | 1         | 1.61%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                      | 1         | 1.61%   |
| BOE LCD Monitor BOE05E9 1366x768 256x144mm 11.6-inch                      | 1         | 1.61%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                         | 1         | 1.61%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch            | 1         | 1.61%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch             | 1         | 1.61%   |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch            | 1         | 1.61%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 340x190mm 15.3-inch             | 1         | 1.61%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch            | 1         | 1.61%   |
| AU Optronics LCD Monitor AUO325C 1366x768 256x144mm 11.6-inch             | 1         | 1.61%   |
| AU Optronics LCD Monitor AUO253C 1366x768 310x170mm 13.9-inch             | 1         | 1.61%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 1         | 1.61%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch             | 1         | 1.61%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 1         | 1.61%   |
| AU Optronics LCD Monitor 1366x768                                         | 1         | 1.61%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                    | 1         | 1.61%   |
| Apple Color LCD APPA02E 2880x1800 331x207mm 15.4-inch                     | 1         | 1.61%   |
| AOC Q2577W AOC2577 2560x1440 553x311mm 25.0-inch                          | 1         | 1.61%   |
| Acer SA270 ACR0580 1920x1080 598x336mm 27.0-inch                          | 1         | 1.61%   |
| Acer ED273 ACR0575 1920x1080 531x299mm 24.0-inch                          | 1         | 1.61%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 25        | 42.37%  |
| 1920x1080 (FHD)  | 21        | 35.59%  |
| 3840x2400        | 2         | 3.39%   |
| 3840x2160 (4K)   | 2         | 3.39%   |
| 1280x800 (WXGA)  | 2         | 3.39%   |
| 3840x1200        | 1         | 1.69%   |
| 3200x1800 (QHD+) | 1         | 1.69%   |
| 2880x1800        | 1         | 1.69%   |
| 2560x1600        | 1         | 1.69%   |
| 2560x1440 (QHD)  | 1         | 1.69%   |
| 1600x900 (HD+)   | 1         | 1.69%   |
| Unknown          | 1         | 1.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 28        | 46.67%  |
| 13      | 13        | 21.67%  |
| 14      | 6         | 10%     |
| 24      | 3         | 5%      |
| 18      | 2         | 3.33%   |
| 17      | 2         | 3.33%   |
| 11      | 2         | 3.33%   |
| Unknown | 2         | 3.33%   |
| 27      | 1         | 1.67%   |
| 25      | 1         | 1.67%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 39        | 65%     |
| 201-300     | 10        | 16.67%  |
| 501-600     | 5         | 8.33%   |
| 401-500     | 2         | 3.33%   |
| 351-400     | 2         | 3.33%   |
| Unknown     | 2         | 3.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 48        | 85.71%  |
| 16/10   | 6         | 10.71%  |
| Unknown | 2         | 3.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 28        | 45.9%   |
| 81-90          | 12        | 19.67%  |
| 71-80          | 7         | 11.48%  |
| 201-250        | 3         | 4.92%   |
| 51-60          | 2         | 3.28%   |
| 141-150        | 2         | 3.28%   |
| 121-130        | 2         | 3.28%   |
| Unknown        | 2         | 3.28%   |
| 301-350        | 1         | 1.64%   |
| 251-300        | 1         | 1.64%   |
| 91-100         | 1         | 1.64%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 27        | 45%     |
| 121-160       | 17        | 28.33%  |
| 51-100        | 6         | 10%     |
| More than 240 | 4         | 6.67%   |
| 161-240       | 4         | 6.67%   |
| Unknown       | 2         | 3.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 51        | 87.93%  |
| 2     | 6         | 10.34%  |
| 0     | 1         | 1.72%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 36        | 36.73%  |
| Intel                            | 28        | 28.57%  |
| Qualcomm Atheros                 | 12        | 12.24%  |
| Broadcom                         | 8         | 8.16%   |
| Broadcom Limited                 | 4         | 4.08%   |
| Marvell Technology Group         | 2         | 2.04%   |
| Silicon Integrated Systems [SiS] | 1         | 1.02%   |
| Samsung Electronics              | 1         | 1.02%   |
| Ralink                           | 1         | 1.02%   |
| Qualcomm                         | 1         | 1.02%   |
| OnePlus                          | 1         | 1.02%   |
| DisplayLink                      | 1         | 1.02%   |
| D-Link System                    | 1         | 1.02%   |
| ASIX Electronics                 | 1         | 1.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 23        | 20.91%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 7         | 6.36%   |
| Intel Wireless 7260                                                  | 5         | 4.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 4         | 3.64%   |
| Intel WiFi Link 5100                                                 | 3         | 2.73%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 2         | 1.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 2         | 1.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 2         | 1.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2         | 1.82%   |
| Intel Wi-Fi 6 AX201                                                  | 2         | 1.82%   |
| Intel Ethernet Connection I217-LM                                    | 2         | 1.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 2         | 1.82%   |
| Intel Centrino Wireless-N 2230                                       | 2         | 1.82%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                         | 2         | 1.82%   |
| Broadcom BCM43142 802.11b/g/n                                        | 2         | 1.82%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter        | 1         | 0.91%   |
| Samsung Galaxy series, misc. (tethering mode)                        | 1         | 0.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.91%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1         | 0.91%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                      | 1         | 0.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 1         | 0.91%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                      | 1         | 0.91%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                           | 1         | 0.91%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 1         | 0.91%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 1         | 0.91%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 1         | 0.91%   |
| Realtek Realtek Network controller                                   | 1         | 0.91%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                     | 1         | 0.91%   |
| Realtek 802.11ac NIC                                                 | 1         | 0.91%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 1         | 0.91%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]          | 1         | 0.91%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                             | 1         | 0.91%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                           | 1         | 0.91%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                | 1         | 0.91%   |
| OnePlus SM8150-MTP _SN:79FDB63C                                      | 1         | 0.91%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller              | 1         | 0.91%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                 | 1         | 0.91%   |
| Intel Wireless 8260                                                  | 1         | 0.91%   |
| Intel Wireless 7265                                                  | 1         | 0.91%   |
| Intel Wireless 3160                                                  | 1         | 0.91%   |
| Intel Wi-Fi 6 AX201 160MHz                                           | 1         | 0.91%   |
| Intel Ethernet Connection I219-V                                     | 1         | 0.91%   |
| Intel Ethernet Connection I218-V                                     | 1         | 0.91%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 1         | 0.91%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 1         | 0.91%   |
| Intel Centrino Wireless-N 130                                        | 1         | 0.91%   |
| Intel Centrino Wireless-N 105                                        | 1         | 0.91%   |
| Intel Centrino Ultimate-N 6300                                       | 1         | 0.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 1         | 0.91%   |
| Intel 82562GT 10/100 Network Connection                              | 1         | 0.91%   |
| DisplayLink Dell Universal Dock D6000                                | 1         | 0.91%   |
| D-Link System DWA-140 RangeBooster N Adapter(rev.B1) [Ralink RT2870] | 1         | 0.91%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                      | 1         | 0.91%   |
| Broadcom Limited NetLink BCM5784M Gigabit Ethernet PCIe              | 1         | 0.91%   |
| Broadcom Limited NetLink BCM57781 Gigabit Ethernet PCIe              | 1         | 0.91%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter           | 1         | 0.91%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter          | 1         | 0.91%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                          | 1         | 0.91%   |
| Broadcom BCM43225 802.11b/g/n                                        | 1         | 0.91%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 1         | 0.91%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 26        | 44.07%  |
| Realtek Semiconductor | 11        | 18.64%  |
| Qualcomm Atheros      | 10        | 16.95%  |
| Broadcom              | 7         | 11.86%  |
| Broadcom Limited      | 2         | 3.39%   |
| Ralink                | 1         | 1.69%   |
| Qualcomm              | 1         | 1.69%   |
| D-Link System         | 1         | 1.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                                  | 5         | 8.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 4         | 6.67%   |
| Intel WiFi Link 5100                                                 | 3         | 5%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 2         | 3.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 2         | 3.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 2         | 3.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2         | 3.33%   |
| Intel Wi-Fi 6 AX201                                                  | 2         | 3.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 2         | 3.33%   |
| Intel Centrino Wireless-N 2230                                       | 2         | 3.33%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                         | 2         | 3.33%   |
| Broadcom BCM43142 802.11b/g/n                                        | 2         | 3.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 1         | 1.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1         | 1.67%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                      | 1         | 1.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 1         | 1.67%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                      | 1         | 1.67%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                           | 1         | 1.67%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 1         | 1.67%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 1         | 1.67%   |
| Realtek Realtek Network controller                                   | 1         | 1.67%   |
| Realtek 802.11ac NIC                                                 | 1         | 1.67%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 1         | 1.67%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]          | 1         | 1.67%   |
| Intel Wireless 8260                                                  | 1         | 1.67%   |
| Intel Wireless 7265                                                  | 1         | 1.67%   |
| Intel Wireless 3160                                                  | 1         | 1.67%   |
| Intel Wi-Fi 6 AX201 160MHz                                           | 1         | 1.67%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 1         | 1.67%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 1         | 1.67%   |
| Intel Centrino Wireless-N 130                                        | 1         | 1.67%   |
| Intel Centrino Wireless-N 105                                        | 1         | 1.67%   |
| Intel Centrino Ultimate-N 6300                                       | 1         | 1.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 1         | 1.67%   |
| D-Link System DWA-140 RangeBooster N Adapter(rev.B1) [Ralink RT2870] | 1         | 1.67%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter           | 1         | 1.67%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter          | 1         | 1.67%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                          | 1         | 1.67%   |
| Broadcom BCM43225 802.11b/g/n                                        | 1         | 1.67%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 1         | 1.67%   |
| Broadcom BCM4321 802.11a/b/g/n                                       | 1         | 1.67%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                    | 1         | 1.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 32        | 64%     |
| Intel                            | 5         | 10%     |
| Qualcomm Atheros                 | 3         | 6%      |
| Marvell Technology Group         | 2         | 4%      |
| Broadcom Limited                 | 2         | 4%      |
| Silicon Integrated Systems [SiS] | 1         | 2%      |
| Samsung Electronics              | 1         | 2%      |
| OnePlus                          | 1         | 2%      |
| DisplayLink                      | 1         | 2%      |
| Broadcom                         | 1         | 2%      |
| ASIX Electronics                 | 1         | 2%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 23        | 46%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 14%     |
| Intel Ethernet Connection I217-LM                                 | 2         | 4%      |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 2%      |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 2%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2%      |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 2%      |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 2%      |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 2%      |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 2%      |
| OnePlus SM8150-MTP _SN:79FDB63C                                   | 1         | 2%      |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 2%      |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 2%      |
| Intel Ethernet Connection I219-V                                  | 1         | 2%      |
| Intel Ethernet Connection I218-V                                  | 1         | 2%      |
| Intel 82562GT 10/100 Network Connection                           | 1         | 2%      |
| DisplayLink Dell Universal Dock D6000                             | 1         | 2%      |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 2%      |
| Broadcom Limited NetLink BCM5784M Gigabit Ethernet PCIe           | 1         | 2%      |
| Broadcom Limited NetLink BCM57781 Gigabit Ethernet PCIe           | 1         | 2%      |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 2%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 57        | 53.77%  |
| Ethernet | 49        | 46.23%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 50        | 53.19%  |
| Ethernet | 44        | 46.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 43        | 74.14%  |
| 1     | 15        | 25.86%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 41        | 70.69%  |
| Yes  | 17        | 29.31%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 19        | 41.3%   |
| Realtek Semiconductor           | 5         | 10.87%  |
| Qualcomm Atheros Communications | 5         | 10.87%  |
| IMC Networks                    | 4         | 8.7%    |
| Foxconn / Hon Hai               | 3         | 6.52%   |
| Broadcom                        | 3         | 6.52%   |
| Lite-On Technology              | 2         | 4.35%   |
| Apple                           | 2         | 4.35%   |
| Ralink                          | 1         | 2.17%   |
| Foxconn International           | 1         | 2.17%   |
| Alps Electric                   | 1         | 2.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 9         | 19.57%  |
| Intel Bluetooth Device                            | 6         | 13.04%  |
| Realtek Bluetooth Radio                           | 4         | 8.7%    |
| Qualcomm Atheros  Bluetooth Device                | 3         | 6.52%   |
| Intel Centrino Bluetooth Wireless Transceiver     | 2         | 4.35%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 2         | 4.35%   |
| IMC Networks Bluetooth Radio                      | 2         | 4.35%   |
| Realtek  Bluetooth 4.2 Adapter                    | 1         | 2.17%   |
| Ralink RT3290 Bluetooth                           | 1         | 2.17%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 1         | 2.17%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 1         | 2.17%   |
| Lite-On BCM43142A0                                | 1         | 2.17%   |
| Lite-On Atheros AR3012 Bluetooth                  | 1         | 2.17%   |
| IMC Networks Bluetooth Device                     | 1         | 2.17%   |
| IMC Networks Bluetooth                            | 1         | 2.17%   |
| Foxconn International BCM43142A0 Bluetooth module | 1         | 2.17%   |
| Foxconn / Hon Hai Bluetooth Device                | 1         | 2.17%   |
| Foxconn / Hon Hai BCM20702A0                      | 1         | 2.17%   |
| Foxconn / Hon Hai Acer Bluetooth module           | 1         | 2.17%   |
| Broadcom BRCM2070 BT 2.1 + HS USB Module          | 1         | 2.17%   |
| Broadcom Bluetooth                                | 1         | 2.17%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR              | 1         | 2.17%   |
| Apple Bluetooth Host Controller                   | 1         | 2.17%   |
| Apple Bluetooth HCI                               | 1         | 2.17%   |
| Alps Electric BCM2046 Bluetooth Device            | 1         | 2.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 47        | 67.14%  |
| AMD                              | 12        | 17.14%  |
| Nvidia                           | 10        | 14.29%  |
| Silicon Integrated Systems [SiS] | 1         | 1.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 7         | 7.78%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 6         | 6.67%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 5.56%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 5.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 5.56%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 4.44%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 4.44%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 4.44%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 4.44%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 3.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 3.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 3.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 3.33%   |
| AMD FCH Azalia Controller                                                  | 3         | 3.33%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 2.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 2.22%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 2.22%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 2.22%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 2.22%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 2.22%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 2.22%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1         | 1.11%   |
| Nvidia High Definition Audio Controller                                    | 1         | 1.11%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 1.11%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.11%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.11%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 1.11%   |
| Intel Jasper Lake HD Graphics SGPC                                         | 1         | 1.11%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.11%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.11%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.11%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1.11%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 1.11%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.11%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1         | 1.11%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 1.11%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 1         | 1.11%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.11%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 6         | 40%     |
| Micron Technology   | 4         | 26.67%  |
| SK Hynix            | 1         | 6.67%   |
| Ramaxel Technology  | 1         | 6.67%   |
| Kingston            | 1         | 6.67%   |
| Crucial             | 1         | 6.67%   |
| A-DATA Technology   | 1         | 6.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s            | 1         | 5.88%   |
| Samsung RAM UBE3D4AA-MGCR 2048MB Row Of Chips LPDDR4 4267MT/s     | 1         | 5.88%   |
| Samsung RAM M471B5773EB0-CK0 2048MB SODIMM DDR3 1600MT/s          | 1         | 5.88%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s          | 1         | 5.88%   |
| Samsung RAM M471B5273CH0-CK0 4096MB SODIMM DDR3 1600MT/s          | 1         | 5.88%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s             | 1         | 5.88%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s             | 1         | 5.88%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s       | 1         | 5.88%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 2667MT/s          | 1         | 5.88%   |
| Ramaxel RAM Module 8GB SODIMM DDR4 2667MT/s                       | 1         | 5.88%   |
| Micron RAM MT52L512M32D2PF-10 4096MB Row Of Chips LPDDR3 1867MT/s | 1         | 5.88%   |
| Micron RAM 4ATF51264HZ-2G6E1 4096MB SODIMM DDR4 2667MT/s          | 1         | 5.88%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s        | 1         | 5.88%   |
| Micron RAM 16KTF51264HZ-1G6M1 4096MB SODIMM DDR3 1600MT/s         | 1         | 5.88%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s            | 1         | 5.88%   |
| Crucial RAM CT8G4SFRA266.C8FJ 8GB SODIMM DDR4 2667MT/s            | 1         | 5.88%   |
| A-DATA RAM AE4S240038G17-BHYA 8192MB SODIMM DDR4 2400MT/s         | 1         | 5.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 6         | 42.86%  |
| DDR3   | 5         | 35.71%  |
| SDRAM  | 1         | 7.14%   |
| LPDDR4 | 1         | 7.14%   |
| LPDDR3 | 1         | 7.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 10        | 71.43%  |
| Row Of Chips | 4         | 28.57%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 4096 | 7         | 50%     |
| 8192 | 5         | 35.71%  |
| 2048 | 2         | 14.29%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 5         | 33.33%  |
| 2667  | 4         | 26.67%  |
| 3200  | 2         | 13.33%  |
| 4267  | 1         | 6.67%   |
| 4199  | 1         | 6.67%   |
| 2400  | 1         | 6.67%   |
| 1867  | 1         | 6.67%   |

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
| IMC Networks                           | 7         | 13.46%  |
| Realtek Semiconductor                  | 6         | 11.54%  |
| Microdia                               | 6         | 11.54%  |
| Chicony Electronics                    | 6         | 11.54%  |
| Acer                                   | 6         | 11.54%  |
| Sunplus Innovation Technology          | 5         | 9.62%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 7.69%   |
| Quanta                                 | 3         | 5.77%   |
| Syntek                                 | 2         | 3.85%   |
| Suyin                                  | 2         | 3.85%   |
| Samsung Electronics                    | 1         | 1.92%   |
| Ricoh                                  | 1         | 1.92%   |
| Lite-On Technology                     | 1         | 1.92%   |
| Generalplus Technology                 | 1         | 1.92%   |
| ALi                                    | 1         | 1.92%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                        | 3         | 5.77%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 3         | 5.77%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 3.85%   |
| Quanta HD User Facing                               | 2         | 3.85%   |
| Microdia Integrated_Webcam_HD                       | 2         | 3.85%   |
| IMC Networks Integrated Camera                      | 2         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 2         | 3.85%   |
| Acer Lenovo EasyCamera                              | 2         | 3.85%   |
| Acer Integrated Camera                              | 2         | 3.85%   |
| Syntek USB Camera Device                            | 1         | 1.92%   |
| Syntek Integrated Camera                            | 1         | 1.92%   |
| Suyin HD Video WebCam                               | 1         | 1.92%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 1         | 1.92%   |
| Sunplus Integrated Webcam                           | 1         | 1.92%   |
| Sunplus HD Webcam                                   | 1         | 1.92%   |
| Sunplus HD User Facing                              | 1         | 1.92%   |
| Samsung Galaxy series, misc. (MTP mode)             | 1         | 1.92%   |
| Ricoh Visual Communication Camera VGP-VCC9 [R5U870] | 1         | 1.92%   |
| Realtek USB Camera                                  | 1         | 1.92%   |
| Realtek Lenovo EasyCamera                           | 1         | 1.92%   |
| Realtek Integrated Webcam                           | 1         | 1.92%   |
| Quanta Laptop_Integrated_Webcam_2HDM                | 1         | 1.92%   |
| Microdia USB Camera                                 | 1         | 1.92%   |
| Microdia Lenovo EasyCamera                          | 1         | 1.92%   |
| Microdia Integrated Webcam                          | 1         | 1.92%   |
| Microdia Integrated HD Webcam                       | 1         | 1.92%   |
| Lite-On HP HD Camera                                | 1         | 1.92%   |
| IMC Networks Lenovo EasyCamera                      | 1         | 1.92%   |
| IMC Networks EasyCamera                             | 1         | 1.92%   |
| Generalplus GENERAL WEBCAM                          | 1         | 1.92%   |
| Chicony VGA Webcam                                  | 1         | 1.92%   |
| Chicony LG HD WebCam                                | 1         | 1.92%   |
| Chicony Integrated Camera                           | 1         | 1.92%   |
| Chicony HP TrueVision HD                            | 1         | 1.92%   |
| Chicony HD WebCam                                   | 1         | 1.92%   |
| Chicony FJ Camera                                   | 1         | 1.92%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 1         | 1.92%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 1         | 1.92%   |
| ALi Gateway Webcam                                  | 1         | 1.92%   |
| Acer SunplusIT INC. Integrated Camera               | 1         | 1.92%   |
| Acer Lenovo EasyCamera integrated webcam            | 1         | 1.92%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 36.36%  |
| Shenzhen Goodix Technology | 3         | 27.27%  |
| LighTuning Technology      | 2         | 18.18%  |
| Upek                       | 1         | 9.09%   |
| Focal-systems.Corp         | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 9.09%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 9.09%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 9.09%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 9.09%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 9.09%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 9.09%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 9.09%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 9.09%   |
| LighTuning Fingerprint Reader                                              | 1         | 9.09%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 9.09%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 9.09%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 38        | 65.52%  |
| 1     | 14        | 24.14%  |
| 2     | 6         | 10.34%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 11        | 40.74%  |
| Graphics card         | 5         | 18.52%  |
| Net/wireless          | 4         | 14.81%  |
| Multimedia controller | 2         | 7.41%   |
| Chipcard              | 2         | 7.41%   |
| Net/ethernet          | 1         | 3.7%    |
| Dvb card              | 1         | 3.7%    |
| Bluetooth             | 1         | 3.7%    |

