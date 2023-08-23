GNOME OS - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for GNOME OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/GNOME_OS/Desktop/README.md) and [notebooks](/Dist/GNOME_OS/Notebook/README.md).

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

Total: 67

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | Z97 GAMING 3                | Desktop     | [c8c107c355](https://linux-hardware.org/?probe=c8c107c355) | Jul 15, 2023 |
| MSI           | Z97 GAMING 3                | Desktop     | [3841eb7ba0](https://linux-hardware.org/?probe=3841eb7ba0) | Jul 15, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [624fca7465](https://linux-hardware.org/?probe=624fca7465) | Jul 07, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [2bd22135e0](https://linux-hardware.org/?probe=2bd22135e0) | Jun 20, 2023 |
| Intel         | H61                         | Desktop     | [ac7abe7025](https://linux-hardware.org/?probe=ac7abe7025) | Jun 16, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [074de9621d](https://linux-hardware.org/?probe=074de9621d) | Mar 21, 2023 |
| ASUSTek       | X550LC                      | Notebook    | [5f73fa5db7](https://linux-hardware.org/?probe=5f73fa5db7) | Mar 18, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [0a83a62b1c](https://linux-hardware.org/?probe=0a83a62b1c) | Mar 13, 2023 |
| Colorful T... | BATTLE-AX B660M-HD DELUX... | Desktop     | [8b2c5b902c](https://linux-hardware.org/?probe=8b2c5b902c) | Mar 10, 2023 |
| Colorful T... | BATTLE-AX B660M-HD DELUX... | Desktop     | [3a0c1c2237](https://linux-hardware.org/?probe=3a0c1c2237) | Mar 10, 2023 |
| HP            | 82F2 A01                    | Desktop     | [b6cb9447df](https://linux-hardware.org/?probe=b6cb9447df) | Nov 19, 2022 |
| Unknown       | 1.0                         | Desktop     | [d07852e419](https://linux-hardware.org/?probe=d07852e419) | Nov 11, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [1b5ab725ab](https://linux-hardware.org/?probe=1b5ab725ab) | Nov 09, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [abbb3295c8](https://linux-hardware.org/?probe=abbb3295c8) | Oct 14, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [f19e981e03](https://linux-hardware.org/?probe=f19e981e03) | Oct 14, 2022 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [c2f80d89da](https://linux-hardware.org/?probe=c2f80d89da) | Sep 26, 2022 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [8d0067a198](https://linux-hardware.org/?probe=8d0067a198) | Sep 26, 2022 |
| Dell          | Inspiron 3584               | Notebook    | [626c79c116](https://linux-hardware.org/?probe=626c79c116) | Sep 24, 2022 |
| HP            | Pavilion 15                 | Notebook    | [56a10ce74c](https://linux-hardware.org/?probe=56a10ce74c) | Sep 21, 2022 |
| ASUSTek       | GL553VE                     | Notebook    | [4d93da1983](https://linux-hardware.org/?probe=4d93da1983) | Sep 20, 2022 |
| ASUSTek       | GL553VE                     | Notebook    | [27b8d384a2](https://linux-hardware.org/?probe=27b8d384a2) | Sep 19, 2022 |
| Gigabyte      | Z97X-Gaming 7               | Desktop     | [1c993db964](https://linux-hardware.org/?probe=1c993db964) | Aug 30, 2022 |
| Gigabyte      | Z97X-Gaming 7               | Desktop     | [91438fc6b5](https://linux-hardware.org/?probe=91438fc6b5) | Aug 30, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [4856a5fefb](https://linux-hardware.org/?probe=4856a5fefb) | Jul 22, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [a90e6b2be7](https://linux-hardware.org/?probe=a90e6b2be7) | Apr 30, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [1bbdbe7117](https://linux-hardware.org/?probe=1bbdbe7117) | Apr 04, 2022 |
| Acer          | Iconia W700                 | Notebook    | [604cdabab4](https://linux-hardware.org/?probe=604cdabab4) | Mar 23, 2022 |
| Lenovo        | ThinkPad Edge E531 68851... | Notebook    | [54269ad944](https://linux-hardware.org/?probe=54269ad944) | Feb 18, 2022 |
| Gateway       | NE71B                       | Notebook    | [ac3dc96ccf](https://linux-hardware.org/?probe=ac3dc96ccf) | Feb 02, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [c604eec754](https://linux-hardware.org/?probe=c604eec754) | Jan 27, 2022 |
| Chuwi         | HeroBook                    | Notebook    | [67990dbe7f](https://linux-hardware.org/?probe=67990dbe7f) | Jan 19, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [e53f2b7fd5](https://linux-hardware.org/?probe=e53f2b7fd5) | Nov 03, 2021 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [922c058537](https://linux-hardware.org/?probe=922c058537) | Nov 03, 2021 |
| Gigabyte      | B450M S2H V2                | Desktop     | [cd6b701253](https://linux-hardware.org/?probe=cd6b701253) | Nov 03, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [594815bb9d](https://linux-hardware.org/?probe=594815bb9d) | Oct 17, 2021 |
| ASUSTek       | X555LD                      | Notebook    | [2560d8b5a0](https://linux-hardware.org/?probe=2560d8b5a0) | Sep 27, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [11c23a1f37](https://linux-hardware.org/?probe=11c23a1f37) | Sep 26, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b33430e135](https://linux-hardware.org/?probe=b33430e135) | Sep 26, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [c248e4551a](https://linux-hardware.org/?probe=c248e4551a) | Sep 25, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [835f183d57](https://linux-hardware.org/?probe=835f183d57) | Sep 17, 2021 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [73b5c289e2](https://linux-hardware.org/?probe=73b5c289e2) | Sep 04, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [35c20c8cde](https://linux-hardware.org/?probe=35c20c8cde) | Aug 30, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [5a54384297](https://linux-hardware.org/?probe=5a54384297) | Aug 11, 2021 |
| HP            | 8767 A                      | Desktop     | [926ac56be9](https://linux-hardware.org/?probe=926ac56be9) | Aug 10, 2021 |
| Gigabyte      | X570 GAMING X               | Desktop     | [b751f6615d](https://linux-hardware.org/?probe=b751f6615d) | Jul 17, 2021 |
| Gigabyte      | B450M S2H V2                | Desktop     | [d8886335b1](https://linux-hardware.org/?probe=d8886335b1) | Jul 10, 2021 |
| Intel         | X79                         | Desktop     | [9f19896285](https://linux-hardware.org/?probe=9f19896285) | May 13, 2021 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [35876a09ad](https://linux-hardware.org/?probe=35876a09ad) | May 09, 2021 |
| HP            | ProBook 430 G3              | Notebook    | [c3acaeb030](https://linux-hardware.org/?probe=c3acaeb030) | Apr 26, 2021 |
| HP            | ProBook 430 G3              | Notebook    | [de3298645e](https://linux-hardware.org/?probe=de3298645e) | Apr 26, 2021 |
| Toshiba       | Satellite C55-A-1F5         | Notebook    | [d7b4bf2642](https://linux-hardware.org/?probe=d7b4bf2642) | Apr 15, 2021 |
| Toshiba       | Satellite C55-A-1F5         | Notebook    | [aa32e3693a](https://linux-hardware.org/?probe=aa32e3693a) | Apr 14, 2021 |
| Lenovo        | 317E NOK                    | Desktop     | [2ce2a68735](https://linux-hardware.org/?probe=2ce2a68735) | Apr 14, 2021 |
| HP            | Pavilion 17                 | Notebook    | [220bf859f8](https://linux-hardware.org/?probe=220bf859f8) | Mar 28, 2021 |
| HP            | Pavilion 17                 | Notebook    | [a5a6941b23](https://linux-hardware.org/?probe=a5a6941b23) | Mar 28, 2021 |
| Dell          | Latitude 7490               | Notebook    | [ce86510d2b](https://linux-hardware.org/?probe=ce86510d2b) | Mar 28, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [517406f8b6](https://linux-hardware.org/?probe=517406f8b6) | Mar 21, 2021 |
| ASUSTek       | PRIME H410M-K               | Desktop     | [f685fefbec](https://linux-hardware.org/?probe=f685fefbec) | Mar 04, 2021 |
| Unknown       | Unknown                     | Notebook    | [1c5ed732c5](https://linux-hardware.org/?probe=1c5ed732c5) | Mar 01, 2021 |
| Dell          | Precision M6800             | Notebook    | [95fa029c09](https://linux-hardware.org/?probe=95fa029c09) | Jan 14, 2021 |
| Dell          | Inspiron 5566               | Notebook    | [a3fd17119a](https://linux-hardware.org/?probe=a3fd17119a) | Nov 03, 2020 |
| Chuwi         | LarkBox                     | Mini pc     | [c7f6fd9a66](https://linux-hardware.org/?probe=c7f6fd9a66) | Oct 21, 2020 |
| HP            | Pavilion 17                 | Notebook    | [edc8ed595b](https://linux-hardware.org/?probe=edc8ed595b) | Oct 12, 2020 |
| Acer          | Aspire GX-781               | Desktop     | [159afb32c1](https://linux-hardware.org/?probe=159afb32c1) | Oct 10, 2020 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [17acfc90d4](https://linux-hardware.org/?probe=17acfc90d4) | Oct 07, 2020 |
| ASUSTek       | E202SA                      | Notebook    | [a226259559](https://linux-hardware.org/?probe=a226259559) | Sep 24, 2020 |
| Acer          | ChiefRiver Platform         | Notebook    | [23e2162b8e](https://linux-hardware.org/?probe=23e2162b8e) | Sep 20, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME OS Nightly | 38        | 73.08%  |
| GNOME OS 3.38    | 7         | 13.46%  |
| GNOME OS 43      | 3         | 5.77%   |
| GNOME OS 41      | 2         | 3.85%   |
| GNOME OS 42      | 1         | 1.92%   |
| GNOME OS 40      | 1         | 1.92%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| GNOME OS | 52        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.7.14  | 8         | 14.81%  |
| 5.11.10 | 8         | 14.81%  |
| 5.14.18 | 7         | 12.96%  |
| 5.19.17 | 6         | 11.11%  |
| 5.13.9  | 5         | 9.26%   |
| 5.19.16 | 3         | 5.56%   |
| 5.18.19 | 3         | 5.56%   |
| 5.11.2  | 3         | 5.56%   |
| 5.18.16 | 2         | 3.7%    |
| 5.14.4  | 2         | 3.7%    |
| 5.13.8  | 2         | 3.7%    |
| 6.4.0   | 1         | 1.85%   |
| 5.18.10 | 1         | 1.85%   |
| 5.14.11 | 1         | 1.85%   |
| 5.12.12 | 1         | 1.85%   |
| 5.11.0  | 1         | 1.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.7.14  | 8         | 14.81%  |
| 5.11.10 | 8         | 14.81%  |
| 5.14.18 | 7         | 12.96%  |
| 5.19.17 | 6         | 11.11%  |
| 5.13.9  | 5         | 9.26%   |
| 5.19.16 | 3         | 5.56%   |
| 5.18.19 | 3         | 5.56%   |
| 5.11.2  | 3         | 5.56%   |
| 5.18.16 | 2         | 3.7%    |
| 5.14.4  | 2         | 3.7%    |
| 5.13.8  | 2         | 3.7%    |
| 6.4.0   | 1         | 1.85%   |
| 5.18.10 | 1         | 1.85%   |
| 5.14.11 | 1         | 1.85%   |
| 5.12.12 | 1         | 1.85%   |
| 5.11.0  | 1         | 1.85%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 12        | 22.64%  |
| 5.19    | 9         | 16.98%  |
| 5.14    | 9         | 16.98%  |
| 5.7     | 8         | 15.09%  |
| 5.13    | 7         | 13.21%  |
| 5.18    | 6         | 11.32%  |
| 6.4     | 1         | 1.89%   |
| 5.12    | 1         | 1.89%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 52        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GNOME   | 52        | 98.11%  |
| Unknown | 1         | 1.89%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 52        | 98.11%  |
| Unknown | 1         | 1.89%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 52        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 22        | 42.31%  |
| pt_BR | 5         | 9.62%   |
| ru_RU | 4         | 7.69%   |
| it_IT | 3         | 5.77%   |
| fr_FR | 3         | 5.77%   |
| es_ES | 3         | 5.77%   |
| hu_HU | 2         | 3.85%   |
| de_DE | 2         | 3.85%   |
| cs_CZ | 2         | 3.85%   |
| sv_SE | 1         | 1.92%   |
| sk_SK | 1         | 1.92%   |
| ru_UA | 1         | 1.92%   |
| nl_NL | 1         | 1.92%   |
| es_CL | 1         | 1.92%   |
| en_IN | 1         | 1.92%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 51        | 98.08%  |
| BIOS | 1         | 1.92%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ext4 | 52        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 52        | 98.11%  |
| GPT     | 1         | 1.89%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 52        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 52        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 9         | 17.31%  |
| ASUSTek Computer    | 9         | 17.31%  |
| Apple               | 7         | 13.46%  |
| Lenovo              | 6         | 11.54%  |
| Dell                | 5         | 9.62%   |
| Acer                | 4         | 7.69%   |
| Gigabyte Technology | 3         | 5.77%   |
| Intel               | 2         | 3.85%   |
| Chuwi               | 2         | 3.85%   |
| Toshiba             | 1         | 1.92%   |
| MSI                 | 1         | 1.92%   |
| Gateway             | 1         | 1.92%   |
| Colorful Technology | 1         | 1.92%   |
| Unknown             | 1         | 1.92%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| HP Pavilion 17                         | 2         | 3.85%   |
| Apple iMac8,1                          | 2         | 3.85%   |
| Toshiba Satellite C55-A-1F5            | 1         | 1.92%   |
| MSI MS-7918                            | 1         | 1.92%   |
| Lenovo Yoga Slim 7 14ARE05 82A2        | 1         | 1.92%   |
| Lenovo ThinkPad Edge E531 68851P6      | 1         | 1.92%   |
| Lenovo IdeaPadFlex 5 14IIL05 81X1      | 1         | 1.92%   |
| Lenovo IdeaPad S340-14API 81NB         | 1         | 1.92%   |
| Lenovo IdeaPad S145-15IWL 81S9         | 1         | 1.92%   |
| Lenovo IdeaCentre 3 07IMB05 90NB0020IN | 1         | 1.92%   |
| Intel X79                              | 1         | 1.92%   |
| Intel H61                              | 1         | 1.92%   |
| HP ProBook 430 G3                      | 1         | 1.92%   |
| HP Pavilion Notebook                   | 1         | 1.92%   |
| HP Pavilion Gaming Laptop 15-ec0xxx    | 1         | 1.92%   |
| HP Pavilion Gaming Desktop TG01-1xxx   | 1         | 1.92%   |
| HP Pavilion Desktop PC 570-p0xx        | 1         | 1.92%   |
| HP Pavilion 15                         | 1         | 1.92%   |
| HP Laptop 14-dk1xxx                    | 1         | 1.92%   |
| Gigabyte Z97X-Gaming 7                 | 1         | 1.92%   |
| Gigabyte X570 GAMING X                 | 1         | 1.92%   |
| Gigabyte B450M S2H V2                  | 1         | 1.92%   |
| Gateway NE71B                          | 1         | 1.92%   |
| Dell Precision M6800                   | 1         | 1.92%   |
| Dell Latitude 7490                     | 1         | 1.92%   |
| Dell Inspiron 5566                     | 1         | 1.92%   |
| Dell Inspiron 3584                     | 1         | 1.92%   |
| Dell Inspiron 3542                     | 1         | 1.92%   |
| Colorful BATTLE-AX B660M-HD DELUXE     | 1         | 1.92%   |
| Chuwi LarkBox                          | 1         | 1.92%   |
| Chuwi HeroBook                         | 1         | 1.92%   |
| ASUS X555LD                            | 1         | 1.92%   |
| ASUS X550LC                            | 1         | 1.92%   |
| ASUS SABERTOOTH X79                    | 1         | 1.92%   |
| ASUS PRIME H410M-K                     | 1         | 1.92%   |
| ASUS PRIME A320M-K                     | 1         | 1.92%   |
| ASUS M5A97 R2.0                        | 1         | 1.92%   |
| ASUS H61M-A/BR                         | 1         | 1.92%   |
| ASUS GL553VE                           | 1         | 1.92%   |
| ASUS E202SA                            | 1         | 1.92%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| HP Pavilion          | 7         | 13.46%  |
| Dell Inspiron        | 3         | 5.77%   |
| Lenovo IdeaPad       | 2         | 3.85%   |
| ASUS PRIME           | 2         | 3.85%   |
| Apple iMac8          | 2         | 3.85%   |
| Acer Aspire          | 2         | 3.85%   |
| Toshiba Satellite    | 1         | 1.92%   |
| MSI MS-7918          | 1         | 1.92%   |
| Lenovo Yoga          | 1         | 1.92%   |
| Lenovo ThinkPad      | 1         | 1.92%   |
| Lenovo IdeaPadFlex   | 1         | 1.92%   |
| Lenovo IdeaCentre    | 1         | 1.92%   |
| Intel X79            | 1         | 1.92%   |
| Intel H61            | 1         | 1.92%   |
| HP ProBook           | 1         | 1.92%   |
| HP Laptop            | 1         | 1.92%   |
| Gigabyte Z97X-Gaming | 1         | 1.92%   |
| Gigabyte X570        | 1         | 1.92%   |
| Gigabyte B450M       | 1         | 1.92%   |
| Gateway NE71B        | 1         | 1.92%   |
| Dell Precision       | 1         | 1.92%   |
| Dell Latitude        | 1         | 1.92%   |
| Colorful BATTLE-AX   | 1         | 1.92%   |
| Chuwi LarkBox        | 1         | 1.92%   |
| Chuwi HeroBook       | 1         | 1.92%   |
| ASUS X555LD          | 1         | 1.92%   |
| ASUS X550LC          | 1         | 1.92%   |
| ASUS SABERTOOTH      | 1         | 1.92%   |
| ASUS M5A97           | 1         | 1.92%   |
| ASUS H61M-A          | 1         | 1.92%   |
| ASUS GL553VE         | 1         | 1.92%   |
| ASUS E202SA          | 1         | 1.92%   |
| Apple Macmini5       | 1         | 1.92%   |
| Apple MacBookPro8    | 1         | 1.92%   |
| Apple MacBookPro10   | 1         | 1.92%   |
| Apple iMac7          | 1         | 1.92%   |
| Apple iMac16         | 1         | 1.92%   |
| Acer Iconia          | 1         | 1.92%   |
| Acer ChiefRiver      | 1         | 1.92%   |
| Unknown              | 1         | 1.92%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2013 | 8         | 15.38%  |
| 2020 | 7         | 13.46%  |
| 2019 | 7         | 13.46%  |
| 2017 | 7         | 13.46%  |
| 2012 | 6         | 11.54%  |
| 2014 | 5         | 9.62%   |
| 2018 | 2         | 3.85%   |
| 2016 | 2         | 3.85%   |
| 2015 | 2         | 3.85%   |
| 2008 | 2         | 3.85%   |
| 2022 | 1         | 1.92%   |
| 2021 | 1         | 1.92%   |
| 2011 | 1         | 1.92%   |
| 2007 | 1         | 1.92%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 28        | 53.85%  |
| Desktop     | 17        | 32.69%  |
| All in one  | 4         | 7.69%   |
| Mini pc     | 2         | 3.85%   |
| Convertible | 1         | 1.92%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 52        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 52        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 19        | 36.54%  |
| 8.01-16.0  | 12        | 23.08%  |
| 3.01-4.0   | 11        | 21.15%  |
| 16.01-24.0 | 6         | 11.54%  |
| 32.01-64.0 | 3         | 5.77%   |
| 1.01-2.0   | 1         | 1.92%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 36        | 67.92%  |
| 2.01-3.0 | 8         | 15.09%  |
| 4.01-8.0 | 3         | 5.66%   |
| 3.01-4.0 | 3         | 5.66%   |
| 0.51-1.0 | 3         | 5.66%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 36        | 69.23%  |
| 2      | 12        | 23.08%  |
| 4      | 2         | 3.85%   |
| 3      | 2         | 3.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 38        | 73.08%  |
| Yes       | 14        | 26.92%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 88.46%  |
| No        | 6         | 11.54%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 86.54%  |
| No        | 7         | 13.46%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 75%     |
| No        | 13        | 25%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 9         | 17.31%  |
| Brazil      | 7         | 13.46%  |
| Ukraine     | 3         | 5.77%   |
| Italy       | 3         | 5.77%   |
| France      | 3         | 5.77%   |
| Spain       | 2         | 3.85%   |
| Russia      | 2         | 3.85%   |
| India       | 2         | 3.85%   |
| Germany     | 2         | 3.85%   |
| Czechia     | 2         | 3.85%   |
| Chile       | 2         | 3.85%   |
| Canada      | 2         | 3.85%   |
| UAE         | 1         | 1.92%   |
| Thailand    | 1         | 1.92%   |
| Sweden      | 1         | 1.92%   |
| Slovakia    | 1         | 1.92%   |
| Serbia      | 1         | 1.92%   |
| Netherlands | 1         | 1.92%   |
| Latvia      | 1         | 1.92%   |
| Iraq        | 1         | 1.92%   |
| Iran        | 1         | 1.92%   |
| Hungary     | 1         | 1.92%   |
| Greece      | 1         | 1.92%   |
| Finland     | 1         | 1.92%   |
| El Salvador | 1         | 1.92%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Vancouver             | 2         | 3.85%   |
| Santiago              | 2         | 3.85%   |
| Waldachtal            | 1         | 1.92%   |
| Verden an der Aller   | 1         | 1.92%   |
| Västerås            | 1         | 1.92%   |
| Uruguaiana            | 1         | 1.92%   |
| Tyumen                | 1         | 1.92%   |
| Tehran                | 1         | 1.92%   |
| Talence               | 1         | 1.92%   |
| Skydra                | 1         | 1.92%   |
| Si Racha              | 1         | 1.92%   |
| Sesto Fiorentino      | 1         | 1.92%   |
| Sao Luís             | 1         | 1.92%   |
| Sao Bernardo do Campo | 1         | 1.92%   |
| San Salvador          | 1         | 1.92%   |
| Rio de Janeiro        | 1         | 1.92%   |
| Riga                  | 1         | 1.92%   |
| Prague                | 1         | 1.92%   |
| Pori                  | 1         | 1.92%   |
| Parempuyre            | 1         | 1.92%   |
| Ottawa                | 1         | 1.92%   |
| Novoyavorovske        | 1         | 1.92%   |
| Novi Sad              | 1         | 1.92%   |
| Millers Creek         | 1         | 1.92%   |
| Milan                 | 1         | 1.92%   |
| Mariupol              | 1         | 1.92%   |
| Madrid                | 1         | 1.92%   |
| Levis                 | 1         | 1.92%   |
| Lelystad              | 1         | 1.92%   |
| Lehighton             | 1         | 1.92%   |
| Kyiv                  | 1         | 1.92%   |
| Krasnoyarsk           | 1         | 1.92%   |
| Kolkata               | 1         | 1.92%   |
| Kalispell             | 1         | 1.92%   |
| Juazeiro do Norte     | 1         | 1.92%   |
| Hyderabad             | 1         | 1.92%   |
| Gig Harbor            | 1         | 1.92%   |
| Getxo                 | 1         | 1.92%   |
| Foz do Iguaçu        | 1         | 1.92%   |
| Del Valle             | 1         | 1.92%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 16     | 22.54%  |
| WDC                 | 10        | 10     | 14.08%  |
| Kingston            | 9         | 10     | 12.68%  |
| Samsung Electronics | 7         | 9      | 9.86%   |
| Toshiba             | 5         | 5      | 7.04%   |
| SK hynix            | 3         | 4      | 4.23%   |
| SanDisk             | 3         | 4      | 4.23%   |
| HGST                | 3         | 3      | 4.23%   |
| PNY                 | 2         | 2      | 2.82%   |
| Micron Technology   | 2         | 2      | 2.82%   |
| Apple               | 2         | 2      | 2.82%   |
| Transcend           | 1         | 1      | 1.41%   |
| SSSTC               | 1         | 1      | 1.41%   |
| Phison Electronics  | 1         | 1      | 1.41%   |
| Patriot             | 1         | 1      | 1.41%   |
| Intel               | 1         | 1      | 1.41%   |
| HECTRON             | 1         | 1      | 1.41%   |
| Crucial             | 1         | 1      | 1.41%   |
| Apacer              | 1         | 1      | 1.41%   |
| AirDisk             | 1         | 1      | 1.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| SK hynix NVMe SSD Drive 512GB             | 2         | 2.7%    |
| Seagate ST9500325AS 500GB                 | 2         | 2.7%    |
| Seagate ST500LM012 HN-M500MBB 500GB       | 2         | 2.7%    |
| Seagate ST1000LM035-1RK172 1TB            | 2         | 2.7%    |
| Seagate ST1000DM003-1SB102 1TB            | 2         | 2.7%    |
| Samsung NVMe SSD Drive 256GB              | 2         | 2.7%    |
| PNY CS900 240GB SSD                       | 2         | 2.7%    |
| Kingston SA400S37120G 120GB SSD           | 2         | 2.7%    |
| HGST HTS541010A9E680 1TB                  | 2         | 2.7%    |
| WDC WDS240G2G0A-00JH30 240GB SSD          | 1         | 1.35%   |
| WDC WD5000LPVX-75V0TT0 500GB              | 1         | 1.35%   |
| WDC WD5000LPVX-08V0TT5 500GB              | 1         | 1.35%   |
| WDC WD5000AAKX-003CA0 500GB               | 1         | 1.35%   |
| WDC WD3200LPVX-08V0TT5 320GB              | 1         | 1.35%   |
| WDC WD20SPZX-11UA7T0 2TB                  | 1         | 1.35%   |
| WDC WD1600AAJS-22L7A0 160GB               | 1         | 1.35%   |
| WDC WD10SPZX-24Z10 1TB                    | 1         | 1.35%   |
| WDC WD10SPZX-22Z10T0 1TB                  | 1         | 1.35%   |
| WDC WD10EALX-009BA0 1TB                   | 1         | 1.35%   |
| Transcend TS64GMTS400 64GB SSD            | 1         | 1.35%   |
| Toshiba MQ04ABF100 1TB                    | 1         | 1.35%   |
| Toshiba MQ01ABD032 320GB                  | 1         | 1.35%   |
| Toshiba HDWD120 2TB                       | 1         | 1.35%   |
| Toshiba DT01ACA100 1TB                    | 1         | 1.35%   |
| Toshiba DT01ACA050 500GB                  | 1         | 1.35%   |
| SSSTC CVB-8D128-HP 128GB SSD              | 1         | 1.35%   |
| SK hynix SKHynix_HFS512GD9TNG-L3A0B 512GB | 1         | 1.35%   |
| SK hynix HFS128G39TND-N210A 128GB SSD     | 1         | 1.35%   |
| Seagate ST9500420AS 500GB                 | 1         | 1.35%   |
| Seagate ST8000DM004-2CX188 8TB            | 1         | 1.35%   |
| Seagate ST500DM002-1BD142 500GB           | 1         | 1.35%   |
| Seagate ST4000DX001-1CE168 4TB            | 1         | 1.35%   |
| Seagate ST3500312CS 500GB                 | 1         | 1.35%   |
| Seagate ST2000DM001-1ER164 2TB            | 1         | 1.35%   |
| Seagate ST1000DM010-2EP102 1TB            | 1         | 1.35%   |
| Seagate ST1000DM003-1CH162 1TB            | 1         | 1.35%   |
| SanDisk X300 MSATA 128GB SSD              | 1         | 1.35%   |
| SanDisk SD8SN8U512G1002 512GB SSD         | 1         | 1.35%   |
| SanDisk NVMe SSD Drive 500GB              | 1         | 1.35%   |
| Samsung SSD 860 QVO 1TB                   | 1         | 1.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 16        | 16     | 47.06%  |
| WDC     | 9         | 9      | 26.47%  |
| Toshiba | 5         | 5      | 14.71%  |
| HGST    | 3         | 3      | 8.82%   |
| Apple   | 1         | 1      | 2.94%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 9         | 9      | 31.03%  |
| Samsung Electronics | 4         | 5      | 13.79%  |
| SanDisk             | 2         | 2      | 6.9%    |
| PNY                 | 2         | 2      | 6.9%    |
| Micron Technology   | 2         | 2      | 6.9%    |
| WDC                 | 1         | 1      | 3.45%   |
| Transcend           | 1         | 1      | 3.45%   |
| SSSTC               | 1         | 1      | 3.45%   |
| SK hynix            | 1         | 1      | 3.45%   |
| Patriot             | 1         | 1      | 3.45%   |
| Intel               | 1         | 1      | 3.45%   |
| Crucial             | 1         | 1      | 3.45%   |
| Apple               | 1         | 1      | 3.45%   |
| Apacer              | 1         | 1      | 3.45%   |
| AirDisk             | 1         | 1      | 3.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 31        | 34     | 45.59%  |
| SSD     | 27        | 30     | 39.71%  |
| NVMe    | 9         | 11     | 13.24%  |
| Unknown | 1         | 1      | 1.47%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 48        | 65     | 84.21%  |
| NVMe | 9         | 11     | 15.79%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 33        | 40     | 58.93%  |
| 0.51-1.0   | 18        | 19     | 32.14%  |
| 1.01-2.0   | 3         | 3      | 5.36%   |
| 3.01-4.0   | 1         | 1      | 1.79%   |
| 4.01-10.0  | 1         | 1      | 1.79%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 21        | 40.38%  |
| 251-500    | 13        | 25%     |
| 501-1000   | 13        | 25%     |
| 51-100     | 3         | 5.77%   |
| 1001-2000  | 2         | 3.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 42        | 79.25%  |
| 21-50    | 6         | 11.32%  |
| 101-250  | 2         | 3.77%   |
| 251-500  | 1         | 1.89%   |
| 501-1000 | 1         | 1.89%   |
| 51-100   | 1         | 1.89%   |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 52        | 75     | 98.11%  |
| Works    | 1         | 1      | 1.89%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 39        | 63.93%  |
| AMD                         | 10        | 16.39%  |
| Samsung Electronics         | 4         | 6.56%   |
| SK hynix                    | 2         | 3.28%   |
| Marvell Technology Group    | 2         | 3.28%   |
| SanDisk                     | 1         | 1.64%   |
| Phison Electronics          | 1         | 1.64%   |
| Kingston Technology Company | 1         | 1.64%   |
| ASMedia Technology          | 1         | 1.64%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 9         | 13.24%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 5         | 7.35%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 5         | 7.35%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 4         | 5.88%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3         | 4.41%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 3         | 4.41%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 3         | 4.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 2.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2         | 2.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 2         | 2.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2         | 2.94%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2         | 2.94%   |
| SK hynix PC601 NVMe Solid State Drive                                                   | 1         | 1.47%   |
| SK hynix BC511 NVMe SSD                                                                 | 1         | 1.47%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1         | 1.47%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1         | 1.47%   |
| Samsung NVMe SSD Controller 980                                                         | 1         | 1.47%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1         | 1.47%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 1         | 1.47%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 1         | 1.47%   |
| Kingston Company NV1 NVMe SSD                                                           | 1         | 1.47%   |
| Intel SATA Controller [RAID mode]                                                       | 1         | 1.47%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1         | 1.47%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 1         | 1.47%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1         | 1.47%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1         | 1.47%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1         | 1.47%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1         | 1.47%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1         | 1.47%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1         | 1.47%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 1.47%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 1.47%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1         | 1.47%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1         | 1.47%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1         | 1.47%   |
| AMD FCH SATA Controller D                                                               | 1         | 1.47%   |
| AMD FCH IDE Controller                                                                  | 1         | 1.47%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1         | 1.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 47        | 75.81%  |
| NVMe | 9         | 14.52%  |
| IDE  | 5         | 8.06%   |
| RAID | 1         | 1.61%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 40        | 76.92%  |
| AMD    | 12        | 23.08%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-2415M CPU @ 2.30GHz             | 2         | 3.85%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 3.85%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 3.85%   |
| Intel Core 2 Duo CPU E8135 @ 2.40GHz          | 2         | 3.85%   |
| Intel Xeon CPU E5-2660 0 @ 2.20GHz            | 1         | 1.92%   |
| Intel Pentium CPU J4205 @ 1.50GHz             | 1         | 1.92%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 1.92%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 1.92%   |
| Intel Core i7-4930K CPU @ 3.40GHz             | 1         | 1.92%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 1         | 1.92%   |
| Intel Core i7-3820QM CPU @ 2.70GHz            | 1         | 1.92%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 1.92%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 1         | 1.92%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 1.92%   |
| Intel Core i5-5675R CPU @ 3.10GHz             | 1         | 1.92%   |
| Intel Core i5-4690K CPU @ 3.50GHz             | 1         | 1.92%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.92%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 1.92%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 1.92%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 1.92%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 1         | 1.92%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 1.92%   |
| Intel Core i3-7100 CPU @ 3.90GHz              | 1         | 1.92%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 1         | 1.92%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 1         | 1.92%   |
| Intel Core i3-3240 CPU @ 3.40GHz              | 1         | 1.92%   |
| Intel Core i3-2375M CPU @ 1.50GHz             | 1         | 1.92%   |
| Intel Core i3-10100F CPU @ 3.60GHz            | 1         | 1.92%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 1         | 1.92%   |
| Intel Core 2 Duo CPU T7700 @ 2.40GHz          | 1         | 1.92%   |
| Intel Celeron J4115 CPU @ 1.80GHz             | 1         | 1.92%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 1         | 1.92%   |
| Intel Celeron CPU G530 @ 2.40GHz              | 1         | 1.92%   |
| Intel Celeron 2957U @ 1.40GHz                 | 1         | 1.92%   |
| Intel Atom x5-E8000 CPU @ 1.04GHz             | 1         | 1.92%   |
| Intel 12th Gen Core i3-12100                  | 1         | 1.92%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 1.92%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 1         | 1.92%   |
| AMD Ryzen 5 3600X 6-Core Processor            | 1         | 1.92%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 1         | 1.92%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 13        | 25%     |
| Intel Core i3    | 11        | 21.15%  |
| Intel Core i7    | 5         | 9.62%   |
| AMD Ryzen 5      | 5         | 9.62%   |
| Intel Celeron    | 4         | 7.69%   |
| Intel Core 2 Duo | 3         | 5.77%   |
| AMD A8           | 2         | 3.85%   |
| Other            | 1         | 1.92%   |
| Intel Xeon       | 1         | 1.92%   |
| Intel Pentium    | 1         | 1.92%   |
| Intel Atom       | 1         | 1.92%   |
| AMD Ryzen 7      | 1         | 1.92%   |
| AMD FX           | 1         | 1.92%   |
| AMD E1           | 1         | 1.92%   |
| AMD Athlon       | 1         | 1.92%   |
| AMD A10          | 1         | 1.92%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 26        | 50%     |
| 4      | 19        | 36.54%  |
| 6      | 4         | 7.69%   |
| 8      | 2         | 3.85%   |
| 3      | 1         | 1.92%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 52        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 36        | 69.23%  |
| 1      | 16        | 30.77%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 52        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306a9    | 5         | 9.62%   |
| 0x40651    | 4         | 7.69%   |
| 0x206a7    | 4         | 7.69%   |
| 0x08108109 | 4         | 7.69%   |
| 0xa0653    | 3         | 5.77%   |
| 0x406e3    | 3         | 5.77%   |
| 0x906e9    | 2         | 3.85%   |
| 0x306c3    | 2         | 3.85%   |
| 0x10676    | 2         | 3.85%   |
| 0x06001119 | 2         | 3.85%   |
| Unknown    | 2         | 3.85%   |
| 0x90675    | 1         | 1.92%   |
| 0x806ec    | 1         | 1.92%   |
| 0x806ea    | 1         | 1.92%   |
| 0x806e9    | 1         | 1.92%   |
| 0x706e5    | 1         | 1.92%   |
| 0x706a1    | 1         | 1.92%   |
| 0x6fb      | 1         | 1.92%   |
| 0x506c9    | 1         | 1.92%   |
| 0x406c4    | 1         | 1.92%   |
| 0x406c3    | 1         | 1.92%   |
| 0x40671    | 1         | 1.92%   |
| 0x306e4    | 1         | 1.92%   |
| 0x206d7    | 1         | 1.92%   |
| 0x0a201009 | 1         | 1.92%   |
| 0x08701021 | 1         | 1.92%   |
| 0x08600106 | 1         | 1.92%   |
| 0x07030105 | 1         | 1.92%   |
| 0x06000822 | 1         | 1.92%   |
| 0x0500010d | 1         | 1.92%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Haswell          | 7         | 13.46%  |
| KabyLake         | 6         | 11.54%  |
| IvyBridge        | 6         | 11.54%  |
| SandyBridge      | 5         | 9.62%   |
| Zen+             | 4         | 7.69%   |
| Skylake          | 3         | 5.77%   |
| Piledriver       | 3         | 5.77%   |
| CometLake        | 3         | 5.77%   |
| Zen 2            | 2         | 3.85%   |
| Silvermont       | 2         | 3.85%   |
| Penryn           | 2         | 3.85%   |
| Zen 3            | 1         | 1.92%   |
| Puma             | 1         | 1.92%   |
| IceLake          | 1         | 1.92%   |
| Goldmont plus    | 1         | 1.92%   |
| Goldmont         | 1         | 1.92%   |
| Core             | 1         | 1.92%   |
| Broadwell        | 1         | 1.92%   |
| Bobcat           | 1         | 1.92%   |
| Alderlake Hybrid | 1         | 1.92%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 28        | 45.16%  |
| Nvidia | 19        | 30.65%  |
| AMD    | 15        | 24.19%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 6.25%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 6.25%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 6.25%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 6.25%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 3         | 4.69%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 4.69%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 3.13%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 3.13%   |
| Intel HD Graphics 630                                                                    | 2         | 3.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 3.13%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 3.13%   |
| AMD RV610/M74 [Mobility Radeon HD 2400 XT]                                               | 2         | 3.13%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1         | 1.56%   |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 1         | 1.56%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.56%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 1.56%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 1.56%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1         | 1.56%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 1.56%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 1.56%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 1.56%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 1.56%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                              | 1         | 1.56%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 1.56%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.56%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.56%   |
| Intel Iris Pro Graphics 6200                                                             | 1         | 1.56%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 1.56%   |
| Intel HD Graphics 620                                                                    | 1         | 1.56%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.56%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 1.56%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 1         | 1.56%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.56%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 1         | 1.56%   |
| AMD Saturn XT [FirePro M6100]                                                            | 1         | 1.56%   |
| AMD RV630/M76 [Mobility Radeon HD 2600 XT/2700]                                          | 1         | 1.56%   |
| AMD Richland [Radeon HD 8610G]                                                           | 1         | 1.56%   |
| AMD Richland [Radeon HD 8550G]                                                           | 1         | 1.56%   |
| AMD Renoir                                                                               | 1         | 1.56%   |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                                 | 1         | 1.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 19        | 36.54%  |
| 1 x AMD        | 11        | 21.15%  |
| 1 x Nvidia     | 10        | 19.23%  |
| Intel + Nvidia | 8         | 15.38%  |
| 2 x AMD        | 2         | 3.85%   |
| Intel + AMD    | 1         | 1.92%   |
| AMD + Nvidia   | 1         | 1.92%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver | Computers | Percent |
|--------|-----------|---------|
| Free   | 52        | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 20        | 38.46%  |
| 1.01-2.0   | 9         | 17.31%  |
| 0.51-1.0   | 6         | 11.54%  |
| 0.01-0.5   | 6         | 11.54%  |
| 2.01-3.0   | 4         | 7.69%   |
| 3.01-4.0   | 3         | 5.77%   |
| 7.01-8.0   | 2         | 3.85%   |
| 5.01-6.0   | 2         | 3.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 15.09%  |
| AU Optronics        | 7         | 13.21%  |
| LG Display          | 6         | 11.32%  |
| Apple               | 6         | 11.32%  |
| Chimei Innolux      | 5         | 9.43%   |
| BOE                 | 5         | 9.43%   |
| Goldstar            | 4         | 7.55%   |
| AOC                 | 3         | 5.66%   |
| Acer                | 2         | 3.77%   |
| Viotek              | 1         | 1.89%   |
| Sony                | 1         | 1.89%   |
| Philips             | 1         | 1.89%   |
| Insignia            | 1         | 1.89%   |
| InfoVision          | 1         | 1.89%   |
| Dell                | 1         | 1.89%   |
| BenQ                | 1         | 1.89%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 2         | 3.7%    |
| Apple Color LCD APP9C6B 1680x1050 433x270mm 20.1-inch                | 2         | 3.7%    |
| Viotek GN34CW VTK3400 3440x1440 795x334mm 33.9-inch                  | 1         | 1.85%   |
| Sony TV SNY4803 1920x1080 1107x623mm 50.0-inch                       | 1         | 1.85%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch  | 1         | 1.85%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch   | 1         | 1.85%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch    | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch | 1         | 1.85%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 382x215mm 17.3-inch | 1         | 1.85%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 700x390mm 31.5-inch    | 1         | 1.85%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 1         | 1.85%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch              | 1         | 1.85%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch         | 1         | 1.85%   |
| LG Display LCD Monitor LGD04B3 1920x1080 345x194mm 15.6-inch         | 1         | 1.85%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch          | 1         | 1.85%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch          | 1         | 1.85%   |
| LG Display LCD Monitor LGD0372 1600x900 382x215mm 17.3-inch          | 1         | 1.85%   |
| LG Display LCD Monitor LGD02DA 1920x1080 382x215mm 17.3-inch         | 1         | 1.85%   |
| Insignia BBY LCD BBY0032 1920x540                                    | 1         | 1.85%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 1         | 1.85%   |
| Goldstar W1752 GSM4490 1440x900 370x232mm 17.2-inch                  | 1         | 1.85%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                               | 1         | 1.85%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch             | 1         | 1.85%   |
| Goldstar 24GL600F GSM5B73 1920x1080 531x298mm 24.0-inch              | 1         | 1.85%   |
| Dell P2421D DELD0FF 2560x1440 527x296mm 23.8-inch                    | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN15D6 1920x1080 344x193mm 15.5-inch     | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN15BB 1920x1080 344x194mm 15.5-inch     | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch     | 1         | 1.85%   |
| Chimei Innolux LCD Monitor CMN1130 1366x768 256x144mm 11.6-inch      | 1         | 1.85%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                | 1         | 1.85%   |
| BOE LCD Monitor BOE07B5 1366x768 309x173mm 13.9-inch                 | 1         | 1.85%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                 | 1         | 1.85%   |
| BOE LCD Monitor BOE065F 1920x1080 344x194mm 15.5-inch                | 1         | 1.85%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                 | 1         | 1.85%   |
| BenQ LCD BNQ8024 2560x1440 597x336mm 27.0-inch                       | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch       | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO48EC 1366x768 344x193mm 15.5-inch        | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO305D 1920x1080 256x144mm 11.6-inch       | 1         | 1.85%   |
| AU Optronics LCD Monitor AUO233C 1366x768 309x173mm 13.9-inch        | 1         | 1.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 24        | 47.06%  |
| 1366x768 (WXGA)    | 12        | 23.53%  |
| 1680x1050 (WSXGA+) | 3         | 5.88%   |
| 1600x900 (HD+)     | 3         | 5.88%   |
| 3840x2160 (4K)     | 2         | 3.92%   |
| 2560x1440 (QHD)    | 2         | 3.92%   |
| 3440x1440          | 1         | 1.96%   |
| 2880x1800          | 1         | 1.96%   |
| 1920x540           | 1         | 1.96%   |
| 1440x900 (WXGA+)   | 1         | 1.96%   |
| 1280x800 (WXGA)    | 1         | 1.96%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 12        | 22.64%  |
| 21     | 5         | 9.43%   |
| 17     | 5         | 9.43%   |
| 14     | 5         | 9.43%   |
| 13     | 5         | 9.43%   |
| 24     | 3         | 5.66%   |
| 23     | 3         | 5.66%   |
| 20     | 3         | 5.66%   |
| 40     | 2         | 3.77%   |
| 11     | 2         | 3.77%   |
| 72     | 1         | 1.89%   |
| 60     | 1         | 1.89%   |
| 48     | 1         | 1.89%   |
| 34     | 1         | 1.89%   |
| 31     | 1         | 1.89%   |
| 27     | 1         | 1.89%   |
| 22     | 1         | 1.89%   |
| 18     | 1         | 1.89%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 20        | 38.46%  |
| 401-500     | 10        | 19.23%  |
| 501-600     | 6         | 11.54%  |
| 351-400     | 5         | 9.62%   |
| 201-300     | 4         | 7.69%   |
| 801-900     | 2         | 3.85%   |
| 1001-1500   | 2         | 3.85%   |
| 701-800     | 1         | 1.92%   |
| 601-700     | 1         | 1.92%   |
| 1501-2000   | 1         | 1.92%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 42        | 82.35%  |
| 16/10 | 7         | 13.73%  |
| 21/9  | 1         | 1.96%   |
| 1.96  | 1         | 1.96%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 12        | 23.08%  |
| 201-250        | 10        | 19.23%  |
| 81-90          | 9         | 17.31%  |
| 151-200        | 4         | 7.69%   |
| 121-130        | 4         | 7.69%   |
| 501-1000       | 3         | 5.77%   |
| More than 1000 | 2         | 3.85%   |
| 51-60          | 2         | 3.85%   |
| 351-500        | 2         | 3.85%   |
| 71-80          | 1         | 1.92%   |
| 301-350        | 1         | 1.92%   |
| 141-150        | 1         | 1.92%   |
| 131-140        | 1         | 1.92%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 18        | 34.62%  |
| 51-100  | 16        | 30.77%  |
| 121-160 | 13        | 25%     |
| 161-240 | 3         | 5.77%   |
| 1-50    | 2         | 3.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 48        | 92.31%  |
| 2     | 4         | 7.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 31        | 37.35%  |
| Intel                           | 16        | 19.28%  |
| Qualcomm Atheros                | 12        | 14.46%  |
| Broadcom                        | 9         | 10.84%  |
| Marvell Technology Group        | 3         | 3.61%   |
| Broadcom Limited                | 3         | 3.61%   |
| Google                          | 2         | 2.41%   |
| Xiaomi                          | 1         | 1.2%    |
| TP-Link                         | 1         | 1.2%    |
| Samsung Electronics             | 1         | 1.2%    |
| Ralink Technology               | 1         | 1.2%    |
| Ralink                          | 1         | 1.2%    |
| Qualcomm Atheros Communications | 1         | 1.2%    |
| Motorola PCS                    | 1         | 1.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20        | 20.62%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 8.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 4.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 3.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 3.09%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 3.09%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 3         | 3.09%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 2.06%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 2.06%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 2.06%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 2.06%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 2.06%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 2         | 2.06%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 2.06%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.03%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.03%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.03%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.03%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 1         | 1.03%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1         | 1.03%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 1.03%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.03%   |
| Ralink RT2770 Wireless Adapter                                    | 1         | 1.03%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 1.03%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.03%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1         | 1.03%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.03%   |
| Motorola PCS Moto G Play                                          | 1         | 1.03%   |
| Intel Wireless-AC 9260                                            | 1         | 1.03%   |
| Intel Wireless 8260                                               | 1         | 1.03%   |
| Intel Wireless 7265                                               | 1         | 1.03%   |
| Intel Wireless 3165                                               | 1         | 1.03%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 1         | 1.03%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 1         | 1.03%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.03%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.03%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.03%   |
| Intel Ethernet Connection (17) I219-V                             | 1         | 1.03%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 11        | 24.44%  |
| Intel                           | 11        | 24.44%  |
| Qualcomm Atheros                | 9         | 20%     |
| Broadcom                        | 8         | 17.78%  |
| Broadcom Limited                | 3         | 6.67%   |
| Ralink Technology               | 1         | 2.22%   |
| Ralink                          | 1         | 2.22%   |
| Qualcomm Atheros Communications | 1         | 2.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 4         | 8.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 3         | 6.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 3         | 6.67%   |
| Broadcom BCM4321 802.11a/b/g/n                             | 3         | 6.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 2         | 4.44%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 2         | 4.44%   |
| Intel Wi-Fi 6 AX200                                        | 2         | 4.44%   |
| Broadcom BCM4331 802.11a/b/g/n                             | 2         | 4.44%   |
| Broadcom BCM43142 802.11b/g/n                              | 2         | 4.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 2.22%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter   | 1         | 2.22%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                 | 1         | 2.22%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter            | 1         | 2.22%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 1         | 2.22%   |
| Ralink RT2770 Wireless Adapter                             | 1         | 2.22%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                  | 1         | 2.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 2.22%   |
| Qualcomm Atheros AR9271 802.11n                            | 1         | 2.22%   |
| Intel Wireless-AC 9260                                     | 1         | 2.22%   |
| Intel Wireless 8260                                        | 1         | 2.22%   |
| Intel Wireless 7265                                        | 1         | 2.22%   |
| Intel Wireless 3165                                        | 1         | 2.22%   |
| Intel Ice Lake-LP PCH CNVi WiFi                            | 1         | 2.22%   |
| Intel Gemini Lake PCH CNVi WiFi                            | 1         | 2.22%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 1         | 2.22%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth            | 1         | 2.22%   |
| Intel Centrino Wireless-N 105                              | 1         | 2.22%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter | 1         | 2.22%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                     | 1         | 2.22%   |
| Broadcom Limited BCM43142 802.11b/g/n                      | 1         | 2.22%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                | 1         | 2.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 29        | 58%     |
| Intel                    | 5         | 10%     |
| Qualcomm Atheros         | 4         | 8%      |
| Broadcom                 | 4         | 8%      |
| Marvell Technology Group | 3         | 6%      |
| Google                   | 2         | 4%      |
| Xiaomi                   | 1         | 2%      |
| TP-Link                  | 1         | 2%      |
| Samsung Electronics      | 1         | 2%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20        | 39.22%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 15.69%  |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 5.88%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 3.92%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 3.92%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.96%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.96%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.96%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.96%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.96%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.96%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.96%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.96%   |
| Intel Ethernet Connection (17) I219-V                             | 1         | 1.96%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.96%   |
| Google Pixel 7                                                    | 1         | 1.96%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 1.96%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.96%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.96%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 1.96%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 46        | 50%     |
| WiFi     | 45        | 48.91%  |
| Unknown  | 1         | 1.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 29        | 59.18%  |
| WiFi     | 20        | 40.82%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 34        | 65.38%  |
| 1     | 16        | 30.77%  |
| 3     | 1         | 1.92%   |
| 0     | 1         | 1.92%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 41        | 77.36%  |
| Yes  | 12        | 22.64%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 9         | 22.5%   |
| Realtek Semiconductor           | 8         | 20%     |
| Apple                           | 7         | 17.5%   |
| Qualcomm Atheros Communications | 5         | 12.5%   |
| Lite-On Technology              | 4         | 10%     |
| Broadcom                        | 2         | 5%      |
| Toshiba                         | 1         | 2.5%    |
| Ralink                          | 1         | 2.5%    |
| Dell                            | 1         | 2.5%    |
| Cambridge Silicon Radio         | 1         | 2.5%    |
| ASUSTek Computer                | 1         | 2.5%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 4         | 10%     |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 10%     |
| Intel Bluetooth wireless interface                  | 4         | 10%     |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 7.5%    |
| Apple Bluetooth Host Controller                     | 3         | 7.5%    |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 5%      |
| Apple Bluetooth HCI                                 | 2         | 5%      |
| Toshiba Bluetooth Device                            | 1         | 2.5%    |
| Realtek RTL8821A Bluetooth                          | 1         | 2.5%    |
| Ralink RT3290 Bluetooth                             | 1         | 2.5%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 2.5%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 2.5%    |
| Lite-On Bluetooth Device                            | 1         | 2.5%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 2.5%    |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.5%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 2.5%    |
| Intel AX201 Bluetooth                               | 1         | 2.5%    |
| Intel AX200 Bluetooth                               | 1         | 2.5%    |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1         | 2.5%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.5%    |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 2.5%    |
| Broadcom BCM2045 Bluetooth                          | 1         | 2.5%    |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 2.5%    |
| Apple Bluetooth USB Host Controller                 | 1         | 2.5%    |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 1         | 2.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 40        | 55.56%  |
| AMD                 | 14        | 19.44%  |
| Nvidia              | 13        | 18.06%  |
| C-Media Electronics | 2         | 2.78%   |
| Huawei Technologies | 1         | 1.39%   |
| Guillemot           | 1         | 1.39%   |
| Creative Labs       | 1         | 1.39%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia GP106 High Definition Audio Controller                                                     | 5         | 5.75%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 5.75%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 5.75%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 5.75%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 5.75%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 4.6%    |
| Intel 8 Series HD Audio Controller                                                                | 4         | 4.6%    |
| AMD FCH Azalia Controller                                                                         | 4         | 4.6%    |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3         | 3.45%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 3.45%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 3.45%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 2.3%    |
| Intel Comet Lake PCH-V cAVS                                                                       | 2         | 2.3%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 2.3%    |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 2.3%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 2.3%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 1.15%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.15%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 1.15%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 1.15%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 1.15%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.15%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 1.15%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.15%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 1.15%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.15%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.15%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.15%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1         | 1.15%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 1.15%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 1         | 1.15%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.15%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 1.15%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.15%   |
| Huawei Technologies USB-C HEADSET                                                                 | 1         | 1.15%   |
| Guillemot Hercules DJ Console 4-Mx                                                                | 1         | 1.15%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                                        | 1         | 1.15%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                                               | 1         | 1.15%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 1.15%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Micron Technology | 1         | 100%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Micron RAM MT53E1G32D4NQ-046WTE 4GB Row Of Chips LPDDR4 4266MT/s | 1         | 100%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| LPDDR4 | 1         | 100%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Row Of Chips | 1         | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Computers | Percent |
|------|-----------|---------|
| 8192 | 1         | 100%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 4266  | 1         | 100%    |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 7         | 20.59%  |
| Apple                                  | 6         | 17.65%  |
| Realtek Semiconductor                  | 5         | 14.71%  |
| Suyin                                  | 3         | 8.82%   |
| Syntek                                 | 2         | 5.88%   |
| Sunplus Innovation Technology          | 2         | 5.88%   |
| Microdia                               | 2         | 5.88%   |
| Logitech                               | 2         | 5.88%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 5.88%   |
| Quanta                                 | 1         | 2.94%   |
| IMC Networks                           | 1         | 2.94%   |
| 2M UVC CAMERA                          | 1         | 2.94%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Suyin HP Truevision HD                           | 3         | 8.57%   |
| Apple Built-in iSight                            | 3         | 8.57%   |
| Syntek Integrated Camera                         | 2         | 5.71%   |
| Realtek USB Camera                               | 2         | 5.71%   |
| Chicony Integrated Camera                        | 2         | 5.71%   |
| Apple FaceTime HD Camera (Built-in)              | 2         | 5.71%   |
| Sunplus Integrated_Webcam_HD                     | 1         | 2.86%   |
| Sunplus HD WebCam                                | 1         | 2.86%   |
| Realtek USB2.0 HD UVC WebCam                     | 1         | 2.86%   |
| Realtek Integrated_Webcam_HD                     | 1         | 2.86%   |
| Realtek Integrated Camera                        | 1         | 2.86%   |
| Quanta HD Webcam                                 | 1         | 2.86%   |
| Microdia Integrated_Webcam_HD                    | 1         | 2.86%   |
| Microdia Integrated Webcam HD                    | 1         | 2.86%   |
| Logitech Webcam C270                             | 1         | 2.86%   |
| Logitech HD Pro Webcam C920                      | 1         | 2.86%   |
| IMC Networks HP TrueVision HD Camera             | 1         | 2.86%   |
| Chicony USB2.0 VGA UVC WebCam                    | 1         | 2.86%   |
| Chicony USB2.0 HD UVC WebCam                     | 1         | 2.86%   |
| Chicony TOSHIBA Web Camera - HD                  | 1         | 2.86%   |
| Chicony HP HD Camera                             | 1         | 2.86%   |
| Chicony HD WebCam                                | 1         | 2.86%   |
| Chicony 5M Cam                                   | 1         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) Webcam    | 1         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 1         | 2.86%   |
| Apple FaceTime HD Camera                         | 1         | 2.86%   |
| 2M UVC CAMERA Web Camera                         | 1         | 2.86%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 1         | 50%     |
| Synaptics        | 1         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader | 1         | 50%     |
| Synaptics WBDI                              | 1         | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 19        | 36.54%  |
| 2     | 15        | 28.85%  |
| 0     | 8         | 15.38%  |
| 3     | 7         | 13.46%  |
| 4     | 3         | 5.77%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 33        | 39.76%  |
| Net/wireless             | 19        | 22.89%  |
| Graphics card            | 6         | 7.23%   |
| Bluetooth                | 6         | 7.23%   |
| Card reader              | 5         | 6.02%   |
| Net/ethernet             | 4         | 4.82%   |
| Multimedia controller    | 4         | 4.82%   |
| Firewire controller      | 2         | 2.41%   |
| Fingerprint reader       | 2         | 2.41%   |
| Storage/ide              | 1         | 1.2%    |
| Chipcard                 | 1         | 1.2%    |

