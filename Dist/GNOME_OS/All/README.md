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

Total: 68

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T480s 20L8S6P20... | Notebook    | [4f3a1c8208](https://linux-hardware.org/?probe=4f3a1c8208) | Sep 24, 2023 |
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
| GNOME OS Nightly | 39        | 73.58%  |
| GNOME OS 3.38    | 7         | 13.21%  |
| GNOME OS 43      | 3         | 5.66%   |
| GNOME OS 41      | 2         | 3.77%   |
| GNOME OS 42      | 1         | 1.89%   |
| GNOME OS 40      | 1         | 1.89%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| GNOME OS | 53        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.7.14  | 8         | 14.55%  |
| 5.11.10 | 8         | 14.55%  |
| 5.14.18 | 7         | 12.73%  |
| 5.19.17 | 6         | 10.91%  |
| 5.13.9  | 5         | 9.09%   |
| 5.19.16 | 3         | 5.45%   |
| 5.18.19 | 3         | 5.45%   |
| 5.11.2  | 3         | 5.45%   |
| 5.18.16 | 2         | 3.64%   |
| 5.14.4  | 2         | 3.64%   |
| 5.13.8  | 2         | 3.64%   |
| 6.5.0   | 1         | 1.82%   |
| 6.4.0   | 1         | 1.82%   |
| 5.18.10 | 1         | 1.82%   |
| 5.14.11 | 1         | 1.82%   |
| 5.12.12 | 1         | 1.82%   |
| 5.11.0  | 1         | 1.82%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.7.14  | 8         | 14.55%  |
| 5.11.10 | 8         | 14.55%  |
| 5.14.18 | 7         | 12.73%  |
| 5.19.17 | 6         | 10.91%  |
| 5.13.9  | 5         | 9.09%   |
| 5.19.16 | 3         | 5.45%   |
| 5.18.19 | 3         | 5.45%   |
| 5.11.2  | 3         | 5.45%   |
| 5.18.16 | 2         | 3.64%   |
| 5.14.4  | 2         | 3.64%   |
| 5.13.8  | 2         | 3.64%   |
| 6.5.0   | 1         | 1.82%   |
| 6.4.0   | 1         | 1.82%   |
| 5.18.10 | 1         | 1.82%   |
| 5.14.11 | 1         | 1.82%   |
| 5.12.12 | 1         | 1.82%   |
| 5.11.0  | 1         | 1.82%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 12        | 22.22%  |
| 5.19    | 9         | 16.67%  |
| 5.14    | 9         | 16.67%  |
| 5.7     | 8         | 14.81%  |
| 5.13    | 7         | 12.96%  |
| 5.18    | 6         | 11.11%  |
| 6.5     | 1         | 1.85%   |
| 6.4     | 1         | 1.85%   |
| 5.12    | 1         | 1.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 53        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GNOME   | 53        | 98.15%  |
| Unknown | 1         | 1.85%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 53        | 98.15%  |
| Unknown | 1         | 1.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 53        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 23        | 43.4%   |
| pt_BR | 5         | 9.43%   |
| ru_RU | 4         | 7.55%   |
| it_IT | 3         | 5.66%   |
| fr_FR | 3         | 5.66%   |
| es_ES | 3         | 5.66%   |
| hu_HU | 2         | 3.77%   |
| de_DE | 2         | 3.77%   |
| cs_CZ | 2         | 3.77%   |
| sv_SE | 1         | 1.89%   |
| sk_SK | 1         | 1.89%   |
| ru_UA | 1         | 1.89%   |
| nl_NL | 1         | 1.89%   |
| es_CL | 1         | 1.89%   |
| en_IN | 1         | 1.89%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 52        | 98.11%  |
| BIOS | 1         | 1.89%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ext4 | 53        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 53        | 98.15%  |
| GPT     | 1         | 1.85%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 53        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 53        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 9         | 16.98%  |
| ASUSTek Computer    | 9         | 16.98%  |
| Lenovo              | 7         | 13.21%  |
| Apple               | 7         | 13.21%  |
| Dell                | 5         | 9.43%   |
| Acer                | 4         | 7.55%   |
| Gigabyte Technology | 3         | 5.66%   |
| Intel               | 2         | 3.77%   |
| Chuwi               | 2         | 3.77%   |
| Toshiba             | 1         | 1.89%   |
| MSI                 | 1         | 1.89%   |
| Gateway             | 1         | 1.89%   |
| Colorful Technology | 1         | 1.89%   |
| Unknown             | 1         | 1.89%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| HP Pavilion 17                         | 2         | 3.77%   |
| Apple iMac8,1                          | 2         | 3.77%   |
| Toshiba Satellite C55-A-1F5            | 1         | 1.89%   |
| MSI MS-7918                            | 1         | 1.89%   |
| Lenovo Yoga Slim 7 14ARE05 82A2        | 1         | 1.89%   |
| Lenovo ThinkPad T480s 20L8S6P200       | 1         | 1.89%   |
| Lenovo ThinkPad Edge E531 68851P6      | 1         | 1.89%   |
| Lenovo IdeaPadFlex 5 14IIL05 81X1      | 1         | 1.89%   |
| Lenovo IdeaPad S340-14API 81NB         | 1         | 1.89%   |
| Lenovo IdeaPad S145-15IWL 81S9         | 1         | 1.89%   |
| Lenovo IdeaCentre 3 07IMB05 90NB0020IN | 1         | 1.89%   |
| Intel X79                              | 1         | 1.89%   |
| Intel H61                              | 1         | 1.89%   |
| HP ProBook 430 G3                      | 1         | 1.89%   |
| HP Pavilion Notebook                   | 1         | 1.89%   |
| HP Pavilion Gaming Laptop 15-ec0xxx    | 1         | 1.89%   |
| HP Pavilion Gaming Desktop TG01-1xxx   | 1         | 1.89%   |
| HP Pavilion Desktop PC 570-p0xx        | 1         | 1.89%   |
| HP Pavilion 15                         | 1         | 1.89%   |
| HP Laptop 14-dk1xxx                    | 1         | 1.89%   |
| Gigabyte Z97X-Gaming 7                 | 1         | 1.89%   |
| Gigabyte X570 GAMING X                 | 1         | 1.89%   |
| Gigabyte B450M S2H V2                  | 1         | 1.89%   |
| Gateway NE71B                          | 1         | 1.89%   |
| Dell Precision M6800                   | 1         | 1.89%   |
| Dell Latitude 7490                     | 1         | 1.89%   |
| Dell Inspiron 5566                     | 1         | 1.89%   |
| Dell Inspiron 3584                     | 1         | 1.89%   |
| Dell Inspiron 3542                     | 1         | 1.89%   |
| Colorful BATTLE-AX B660M-HD DELUXE     | 1         | 1.89%   |
| Chuwi LarkBox                          | 1         | 1.89%   |
| Chuwi HeroBook                         | 1         | 1.89%   |
| ASUS X555LD                            | 1         | 1.89%   |
| ASUS X550LC                            | 1         | 1.89%   |
| ASUS SABERTOOTH X79                    | 1         | 1.89%   |
| ASUS PRIME H410M-K                     | 1         | 1.89%   |
| ASUS PRIME A320M-K                     | 1         | 1.89%   |
| ASUS M5A97 R2.0                        | 1         | 1.89%   |
| ASUS H61M-A/BR                         | 1         | 1.89%   |
| ASUS GL553VE                           | 1         | 1.89%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| HP Pavilion          | 7         | 13.21%  |
| Dell Inspiron        | 3         | 5.66%   |
| Lenovo ThinkPad      | 2         | 3.77%   |
| Lenovo IdeaPad       | 2         | 3.77%   |
| ASUS PRIME           | 2         | 3.77%   |
| Apple iMac8          | 2         | 3.77%   |
| Acer Aspire          | 2         | 3.77%   |
| Toshiba Satellite    | 1         | 1.89%   |
| MSI MS-7918          | 1         | 1.89%   |
| Lenovo Yoga          | 1         | 1.89%   |
| Lenovo IdeaPadFlex   | 1         | 1.89%   |
| Lenovo IdeaCentre    | 1         | 1.89%   |
| Intel X79            | 1         | 1.89%   |
| Intel H61            | 1         | 1.89%   |
| HP ProBook           | 1         | 1.89%   |
| HP Laptop            | 1         | 1.89%   |
| Gigabyte Z97X-Gaming | 1         | 1.89%   |
| Gigabyte X570        | 1         | 1.89%   |
| Gigabyte B450M       | 1         | 1.89%   |
| Gateway NE71B        | 1         | 1.89%   |
| Dell Precision       | 1         | 1.89%   |
| Dell Latitude        | 1         | 1.89%   |
| Colorful BATTLE-AX   | 1         | 1.89%   |
| Chuwi LarkBox        | 1         | 1.89%   |
| Chuwi HeroBook       | 1         | 1.89%   |
| ASUS X555LD          | 1         | 1.89%   |
| ASUS X550LC          | 1         | 1.89%   |
| ASUS SABERTOOTH      | 1         | 1.89%   |
| ASUS M5A97           | 1         | 1.89%   |
| ASUS H61M-A          | 1         | 1.89%   |
| ASUS GL553VE         | 1         | 1.89%   |
| ASUS E202SA          | 1         | 1.89%   |
| Apple Macmini5       | 1         | 1.89%   |
| Apple MacBookPro8    | 1         | 1.89%   |
| Apple MacBookPro10   | 1         | 1.89%   |
| Apple iMac7          | 1         | 1.89%   |
| Apple iMac16         | 1         | 1.89%   |
| Acer Iconia          | 1         | 1.89%   |
| Acer ChiefRiver      | 1         | 1.89%   |
| Unknown              | 1         | 1.89%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2013 | 8         | 15.09%  |
| 2020 | 7         | 13.21%  |
| 2019 | 7         | 13.21%  |
| 2017 | 7         | 13.21%  |
| 2012 | 6         | 11.32%  |
| 2014 | 5         | 9.43%   |
| 2018 | 3         | 5.66%   |
| 2016 | 2         | 3.77%   |
| 2015 | 2         | 3.77%   |
| 2008 | 2         | 3.77%   |
| 2022 | 1         | 1.89%   |
| 2021 | 1         | 1.89%   |
| 2011 | 1         | 1.89%   |
| 2007 | 1         | 1.89%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 29        | 54.72%  |
| Desktop     | 17        | 32.08%  |
| All in one  | 4         | 7.55%   |
| Mini pc     | 2         | 3.77%   |
| Convertible | 1         | 1.89%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 53        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 53        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 19        | 35.85%  |
| 8.01-16.0  | 12        | 22.64%  |
| 3.01-4.0   | 11        | 20.75%  |
| 16.01-24.0 | 7         | 13.21%  |
| 32.01-64.0 | 3         | 5.66%   |
| 1.01-2.0   | 1         | 1.89%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 36        | 66.67%  |
| 2.01-3.0 | 8         | 14.81%  |
| 4.01-8.0 | 4         | 7.41%   |
| 3.01-4.0 | 3         | 5.56%   |
| 0.51-1.0 | 3         | 5.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 37        | 69.81%  |
| 2      | 12        | 22.64%  |
| 4      | 2         | 3.77%   |
| 3      | 2         | 3.77%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 39        | 73.58%  |
| Yes       | 14        | 26.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 88.68%  |
| No        | 6         | 11.32%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 86.79%  |
| No        | 7         | 13.21%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 75.47%  |
| No        | 13        | 24.53%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 10        | 18.87%  |
| Brazil      | 7         | 13.21%  |
| Ukraine     | 3         | 5.66%   |
| Italy       | 3         | 5.66%   |
| France      | 3         | 5.66%   |
| Spain       | 2         | 3.77%   |
| Russia      | 2         | 3.77%   |
| India       | 2         | 3.77%   |
| Germany     | 2         | 3.77%   |
| Czechia     | 2         | 3.77%   |
| Chile       | 2         | 3.77%   |
| Canada      | 2         | 3.77%   |
| UAE         | 1         | 1.89%   |
| Thailand    | 1         | 1.89%   |
| Sweden      | 1         | 1.89%   |
| Slovakia    | 1         | 1.89%   |
| Serbia      | 1         | 1.89%   |
| Netherlands | 1         | 1.89%   |
| Latvia      | 1         | 1.89%   |
| Iraq        | 1         | 1.89%   |
| Iran        | 1         | 1.89%   |
| Hungary     | 1         | 1.89%   |
| Greece      | 1         | 1.89%   |
| Finland     | 1         | 1.89%   |
| El Salvador | 1         | 1.89%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Vancouver             | 2         | 3.77%   |
| Santiago              | 2         | 3.77%   |
| Waldachtal            | 1         | 1.89%   |
| Verden an der Aller   | 1         | 1.89%   |
| Västerås            | 1         | 1.89%   |
| Uruguaiana            | 1         | 1.89%   |
| Tyumen                | 1         | 1.89%   |
| Tehran                | 1         | 1.89%   |
| Talence               | 1         | 1.89%   |
| Skydra                | 1         | 1.89%   |
| Si Racha              | 1         | 1.89%   |
| Shreveport            | 1         | 1.89%   |
| Sesto Fiorentino      | 1         | 1.89%   |
| Sao Luís             | 1         | 1.89%   |
| Sao Bernardo do Campo | 1         | 1.89%   |
| San Salvador          | 1         | 1.89%   |
| Rio de Janeiro        | 1         | 1.89%   |
| Riga                  | 1         | 1.89%   |
| Prague                | 1         | 1.89%   |
| Pori                  | 1         | 1.89%   |
| Parempuyre            | 1         | 1.89%   |
| Ottawa                | 1         | 1.89%   |
| Novoyavorovske        | 1         | 1.89%   |
| Novi Sad              | 1         | 1.89%   |
| Millers Creek         | 1         | 1.89%   |
| Milan                 | 1         | 1.89%   |
| Mariupol              | 1         | 1.89%   |
| Madrid                | 1         | 1.89%   |
| Levis                 | 1         | 1.89%   |
| Lelystad              | 1         | 1.89%   |
| Lehighton             | 1         | 1.89%   |
| Kyiv                  | 1         | 1.89%   |
| Krasnoyarsk           | 1         | 1.89%   |
| Kolkata               | 1         | 1.89%   |
| Kalispell             | 1         | 1.89%   |
| Juazeiro do Norte     | 1         | 1.89%   |
| Hyderabad             | 1         | 1.89%   |
| Gig Harbor            | 1         | 1.89%   |
| Getxo                 | 1         | 1.89%   |
| Foz do Iguaçu        | 1         | 1.89%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 16     | 22.22%  |
| WDC                 | 10        | 10     | 13.89%  |
| Kingston            | 9         | 10     | 12.5%   |
| Samsung Electronics | 7         | 9      | 9.72%   |
| Toshiba             | 5         | 5      | 6.94%   |
| SanDisk             | 4         | 5      | 5.56%   |
| SK hynix            | 3         | 4      | 4.17%   |
| HGST                | 3         | 3      | 4.17%   |
| PNY                 | 2         | 2      | 2.78%   |
| Micron Technology   | 2         | 2      | 2.78%   |
| Apple               | 2         | 2      | 2.78%   |
| Transcend           | 1         | 1      | 1.39%   |
| SSSTC               | 1         | 1      | 1.39%   |
| Phison Electronics  | 1         | 1      | 1.39%   |
| Patriot             | 1         | 1      | 1.39%   |
| Intel               | 1         | 1      | 1.39%   |
| HECTRON             | 1         | 1      | 1.39%   |
| Crucial             | 1         | 1      | 1.39%   |
| Apacer              | 1         | 1      | 1.39%   |
| AirDisk             | 1         | 1      | 1.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| SK hynix NVMe SSD Drive 512GB                       | 2         | 2.67%   |
| Seagate ST9500325AS 500GB                           | 2         | 2.67%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 2         | 2.67%   |
| Seagate ST1000LM035-1RK172 1TB                      | 2         | 2.67%   |
| Seagate ST1000DM003-1SB102 1TB                      | 2         | 2.67%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 2         | 2.67%   |
| PNY CS900 240GB SSD                                 | 2         | 2.67%   |
| Kingston SA400S37120G 120GB SSD                     | 2         | 2.67%   |
| HGST HTS541010A9E680 1TB                            | 2         | 2.67%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 1.33%   |
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 1.33%   |
| WDC WD5000LPVX-08V0TT5 500GB                        | 1         | 1.33%   |
| WDC WD5000AAKX-003CA0 500GB                         | 1         | 1.33%   |
| WDC WD3200LPVX-08V0TT5 320GB                        | 1         | 1.33%   |
| WDC WD20SPZX-11UA7T0 2TB                            | 1         | 1.33%   |
| WDC WD1600AAJS-22L7A0 160GB                         | 1         | 1.33%   |
| WDC WD10SPZX-24Z10 1TB                              | 1         | 1.33%   |
| WDC WD10SPZX-22Z10T0 1TB                            | 1         | 1.33%   |
| WDC WD10EALX-009BA0 1TB                             | 1         | 1.33%   |
| Transcend TS64GMTS400 64GB SSD                      | 1         | 1.33%   |
| Toshiba MQ04ABF100 1TB                              | 1         | 1.33%   |
| Toshiba MQ01ABD032 320GB                            | 1         | 1.33%   |
| Toshiba HDWD120 2TB                                 | 1         | 1.33%   |
| Toshiba DT01ACA100 1TB                              | 1         | 1.33%   |
| Toshiba DT01ACA050 500GB                            | 1         | 1.33%   |
| SSSTC CVB-8D128-HP 128GB                            | 1         | 1.33%   |
| SK hynix SKHynix_HFS512GD9TNG-L3A0B 512GB           | 1         | 1.33%   |
| SK hynix HFS128G39TND-N210A 128GB SSD               | 1         | 1.33%   |
| Seagate ST9500420AS 500GB                           | 1         | 1.33%   |
| Seagate ST8000DM004-2CX188 8TB                      | 1         | 1.33%   |
| Seagate ST500DM002-1BD142 500GB                     | 1         | 1.33%   |
| Seagate ST4000DX001-1CE168 4TB                      | 1         | 1.33%   |
| Seagate ST3500312CS 500GB                           | 1         | 1.33%   |
| Seagate ST2000DM001-1ER164 2TB                      | 1         | 1.33%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1         | 1.33%   |
| Seagate ST1000DM003-1CH162 1TB                      | 1         | 1.33%   |
| SanDisk X300 MSATA 128GB SSD                        | 1         | 1.33%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD 1TB | 1         | 1.33%   |
| SanDisk SD8SN8U512G1002 512GB SSD                   | 1         | 1.33%   |
| SanDisk NVMe SSD Drive 500GB                        | 1         | 1.33%   |

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
| HDD     | 31        | 34     | 44.93%  |
| SSD     | 27        | 30     | 39.13%  |
| NVMe    | 10        | 12     | 14.49%  |
| Unknown | 1         | 1      | 1.45%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 48        | 65     | 82.76%  |
| NVMe | 10        | 12     | 17.24%  |

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
| 101-250    | 21        | 39.62%  |
| 251-500    | 14        | 26.42%  |
| 501-1000   | 13        | 24.53%  |
| 51-100     | 3         | 5.66%   |
| 1001-2000  | 2         | 3.77%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 43        | 79.63%  |
| 21-50    | 6         | 11.11%  |
| 101-250  | 2         | 3.7%    |
| 251-500  | 1         | 1.85%   |
| 501-1000 | 1         | 1.85%   |
| 51-100   | 1         | 1.85%   |

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
| Detected | 53        | 76     | 98.15%  |
| Works    | 1         | 1      | 1.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 39        | 62.9%   |
| AMD                         | 10        | 16.13%  |
| Samsung Electronics         | 4         | 6.45%   |
| SK hynix                    | 2         | 3.23%   |
| SanDisk                     | 2         | 3.23%   |
| Marvell Technology Group    | 2         | 3.23%   |
| Phison Electronics          | 1         | 1.61%   |
| Kingston Technology Company | 1         | 1.61%   |
| ASMedia Technology          | 1         | 1.61%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 9         | 13.04%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 5         | 7.25%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 5         | 7.25%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 4         | 5.8%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3         | 4.35%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 3         | 4.35%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 3         | 4.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 2.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2         | 2.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 2         | 2.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2         | 2.9%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2         | 2.9%    |
| SK hynix PC601 NVMe Solid State Drive                                                   | 1         | 1.45%   |
| SK hynix BC511 NVMe SSD                                                                 | 1         | 1.45%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1         | 1.45%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1         | 1.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1         | 1.45%   |
| Samsung NVMe SSD Controller 980                                                         | 1         | 1.45%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1         | 1.45%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 1         | 1.45%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 1         | 1.45%   |
| Kingston Company NV1 NVMe SSD                                                           | 1         | 1.45%   |
| Intel SATA Controller [RAID mode]                                                       | 1         | 1.45%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1         | 1.45%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 1         | 1.45%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1         | 1.45%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1         | 1.45%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1         | 1.45%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1         | 1.45%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1         | 1.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1         | 1.45%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 1.45%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 1.45%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1         | 1.45%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1         | 1.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1         | 1.45%   |
| AMD FCH SATA Controller D                                                               | 1         | 1.45%   |
| AMD FCH IDE Controller                                                                  | 1         | 1.45%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1         | 1.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 47        | 74.6%   |
| NVMe | 10        | 15.87%  |
| IDE  | 5         | 7.94%   |
| RAID | 1         | 1.59%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 41        | 77.36%  |
| AMD    | 12        | 22.64%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel Core i5-2415M CPU @ 2.30GHz      | 2         | 3.77%   |
| Intel Core i3-6006U CPU @ 2.00GHz      | 2         | 3.77%   |
| Intel Core i3-3110M CPU @ 2.40GHz      | 2         | 3.77%   |
| Intel Core 2 Duo CPU E8135 @ 2.40GHz   | 2         | 3.77%   |
| Intel Xeon CPU E5-2660 0 @ 2.20GHz     | 1         | 1.89%   |
| Intel Pentium CPU J4205 @ 1.50GHz      | 1         | 1.89%   |
| Intel Core i7-8650U CPU @ 1.90GHz      | 1         | 1.89%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz     | 1         | 1.89%   |
| Intel Core i7-4930K CPU @ 3.40GHz      | 1         | 1.89%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 1         | 1.89%   |
| Intel Core i7-3820QM CPU @ 2.70GHz     | 1         | 1.89%   |
| Intel Core i5-8350U CPU @ 1.70GHz      | 1         | 1.89%   |
| Intel Core i5-8265U CPU @ 1.60GHz      | 1         | 1.89%   |
| Intel Core i5-7400 CPU @ 3.00GHz       | 1         | 1.89%   |
| Intel Core i5-6200U CPU @ 2.30GHz      | 1         | 1.89%   |
| Intel Core i5-5675R CPU @ 3.10GHz      | 1         | 1.89%   |
| Intel Core i5-4690K CPU @ 3.50GHz      | 1         | 1.89%   |
| Intel Core i5-4210U CPU @ 1.70GHz      | 1         | 1.89%   |
| Intel Core i5-4200U CPU @ 1.60GHz      | 1         | 1.89%   |
| Intel Core i5-4200M CPU @ 2.50GHz      | 1         | 1.89%   |
| Intel Core i5-3337U CPU @ 1.80GHz      | 1         | 1.89%   |
| Intel Core i5-10400 CPU @ 2.90GHz      | 1         | 1.89%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz     | 1         | 1.89%   |
| Intel Core i3-7100 CPU @ 3.90GHz       | 1         | 1.89%   |
| Intel Core i3-7020U CPU @ 2.30GHz      | 1         | 1.89%   |
| Intel Core i3-4030U CPU @ 1.90GHz      | 1         | 1.89%   |
| Intel Core i3-3240 CPU @ 3.40GHz       | 1         | 1.89%   |
| Intel Core i3-2375M CPU @ 1.50GHz      | 1         | 1.89%   |
| Intel Core i3-10100F CPU @ 3.60GHz     | 1         | 1.89%   |
| Intel Core i3-10100 CPU @ 3.60GHz      | 1         | 1.89%   |
| Intel Core 2 Duo CPU T7700 @ 2.40GHz   | 1         | 1.89%   |
| Intel Celeron J4115 CPU @ 1.80GHz      | 1         | 1.89%   |
| Intel Celeron CPU N3050 @ 1.60GHz      | 1         | 1.89%   |
| Intel Celeron CPU G530 @ 2.40GHz       | 1         | 1.89%   |
| Intel Celeron 2957U @ 1.40GHz          | 1         | 1.89%   |
| Intel Atom x5-E8000 CPU @ 1.04GHz      | 1         | 1.89%   |
| Intel 12th Gen Core i3-12100           | 1         | 1.89%   |
| AMD Ryzen 7 4700U with Radeon Graphics | 1         | 1.89%   |
| AMD Ryzen 5 5600X 6-Core Processor     | 1         | 1.89%   |
| AMD Ryzen 5 3600X 6-Core Processor     | 1         | 1.89%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 14        | 26.42%  |
| Intel Core i3    | 11        | 20.75%  |
| Intel Core i7    | 5         | 9.43%   |
| AMD Ryzen 5      | 5         | 9.43%   |
| Intel Celeron    | 4         | 7.55%   |
| Intel Core 2 Duo | 3         | 5.66%   |
| AMD A8           | 2         | 3.77%   |
| Other            | 1         | 1.89%   |
| Intel Xeon       | 1         | 1.89%   |
| Intel Pentium    | 1         | 1.89%   |
| Intel Atom       | 1         | 1.89%   |
| AMD Ryzen 7      | 1         | 1.89%   |
| AMD FX           | 1         | 1.89%   |
| AMD E1           | 1         | 1.89%   |
| AMD Athlon       | 1         | 1.89%   |
| AMD A10          | 1         | 1.89%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 26        | 49.06%  |
| 4      | 20        | 37.74%  |
| 6      | 4         | 7.55%   |
| 8      | 2         | 3.77%   |
| 3      | 1         | 1.89%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 53        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 37        | 69.81%  |
| 1      | 16        | 30.19%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 53        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306a9    | 5         | 9.43%   |
| 0x40651    | 4         | 7.55%   |
| 0x206a7    | 4         | 7.55%   |
| 0x08108109 | 4         | 7.55%   |
| 0xa0653    | 3         | 5.66%   |
| 0x406e3    | 3         | 5.66%   |
| Unknown    | 3         | 5.66%   |
| 0x906e9    | 2         | 3.77%   |
| 0x306c3    | 2         | 3.77%   |
| 0x10676    | 2         | 3.77%   |
| 0x06001119 | 2         | 3.77%   |
| 0x90675    | 1         | 1.89%   |
| 0x806ec    | 1         | 1.89%   |
| 0x806ea    | 1         | 1.89%   |
| 0x806e9    | 1         | 1.89%   |
| 0x706e5    | 1         | 1.89%   |
| 0x706a1    | 1         | 1.89%   |
| 0x6fb      | 1         | 1.89%   |
| 0x506c9    | 1         | 1.89%   |
| 0x406c4    | 1         | 1.89%   |
| 0x406c3    | 1         | 1.89%   |
| 0x40671    | 1         | 1.89%   |
| 0x306e4    | 1         | 1.89%   |
| 0x206d7    | 1         | 1.89%   |
| 0x0a201009 | 1         | 1.89%   |
| 0x08701021 | 1         | 1.89%   |
| 0x08600106 | 1         | 1.89%   |
| 0x07030105 | 1         | 1.89%   |
| 0x06000822 | 1         | 1.89%   |
| 0x0500010d | 1         | 1.89%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 7         | 13.21%  |
| Haswell          | 7         | 13.21%  |
| IvyBridge        | 6         | 11.32%  |
| SandyBridge      | 5         | 9.43%   |
| Zen+             | 4         | 7.55%   |
| Skylake          | 3         | 5.66%   |
| Piledriver       | 3         | 5.66%   |
| CometLake        | 3         | 5.66%   |
| Zen 2            | 2         | 3.77%   |
| Silvermont       | 2         | 3.77%   |
| Penryn           | 2         | 3.77%   |
| Zen 3            | 1         | 1.89%   |
| Puma             | 1         | 1.89%   |
| IceLake          | 1         | 1.89%   |
| Goldmont plus    | 1         | 1.89%   |
| Goldmont         | 1         | 1.89%   |
| Core             | 1         | 1.89%   |
| Broadwell        | 1         | 1.89%   |
| Bobcat           | 1         | 1.89%   |
| Alderlake Hybrid | 1         | 1.89%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 29        | 46.03%  |
| Nvidia | 19        | 30.16%  |
| AMD    | 15        | 23.81%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 6.15%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 6.15%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 6.15%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 6.15%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 3         | 4.62%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 4.62%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 3.08%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 3.08%   |
| Intel UHD Graphics 620                                                                   | 2         | 3.08%   |
| Intel HD Graphics 630                                                                    | 2         | 3.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 3.08%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 3.08%   |
| AMD RV610/M74 [Mobility Radeon HD 2400 XT]                                               | 2         | 3.08%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1         | 1.54%   |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 1         | 1.54%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.54%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 1.54%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 1.54%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1         | 1.54%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 1.54%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 1.54%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 1.54%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 1.54%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                              | 1         | 1.54%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 1.54%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.54%   |
| Intel Iris Pro Graphics 6200                                                             | 1         | 1.54%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 1.54%   |
| Intel HD Graphics 620                                                                    | 1         | 1.54%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.54%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 1.54%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 1         | 1.54%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.54%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 1         | 1.54%   |
| AMD Saturn XT [FirePro M6100]                                                            | 1         | 1.54%   |
| AMD RV630/M76 [Mobility Radeon HD 2600 XT/2700]                                          | 1         | 1.54%   |
| AMD Richland [Radeon HD 8610G]                                                           | 1         | 1.54%   |
| AMD Richland [Radeon HD 8550G]                                                           | 1         | 1.54%   |
| AMD Renoir                                                                               | 1         | 1.54%   |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                                 | 1         | 1.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 20        | 37.74%  |
| 1 x AMD        | 11        | 20.75%  |
| 1 x Nvidia     | 10        | 18.87%  |
| Intel + Nvidia | 8         | 15.09%  |
| 2 x AMD        | 2         | 3.77%   |
| Intel + AMD    | 1         | 1.89%   |
| AMD + Nvidia   | 1         | 1.89%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver | Computers | Percent |
|--------|-----------|---------|
| Free   | 53        | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 39.62%  |
| 1.01-2.0   | 9         | 16.98%  |
| 0.51-1.0   | 6         | 11.32%  |
| 0.01-0.5   | 6         | 11.32%  |
| 2.01-3.0   | 4         | 7.55%   |
| 3.01-4.0   | 3         | 5.66%   |
| 7.01-8.0   | 2         | 3.77%   |
| 5.01-6.0   | 2         | 3.77%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 14.81%  |
| AU Optronics        | 7         | 12.96%  |
| LG Display          | 6         | 11.11%  |
| Chimei Innolux      | 6         | 11.11%  |
| Apple               | 6         | 11.11%  |
| BOE                 | 5         | 9.26%   |
| Goldstar            | 4         | 7.41%   |
| AOC                 | 3         | 5.56%   |
| Acer                | 2         | 3.7%    |
| Viotek              | 1         | 1.85%   |
| Sony                | 1         | 1.85%   |
| Philips             | 1         | 1.85%   |
| Insignia            | 1         | 1.85%   |
| InfoVision          | 1         | 1.85%   |
| Dell                | 1         | 1.85%   |
| BenQ                | 1         | 1.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 2         | 3.64%   |
| Apple Color LCD APP9C6B 1680x1050 433x270mm 20.1-inch                | 2         | 3.64%   |
| Viotek GN34CW VTK3400 3440x1440 795x334mm 33.9-inch                  | 1         | 1.82%   |
| Sony TV SNY4803 1920x1080 930x523mm 42.0-inch                        | 1         | 1.82%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch  | 1         | 1.82%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch   | 1         | 1.82%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch    | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 382x215mm 17.3-inch | 1         | 1.82%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch    | 1         | 1.82%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 1         | 1.82%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch              | 1         | 1.82%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch         | 1         | 1.82%   |
| LG Display LCD Monitor LGD04B3 1920x1080 345x194mm 15.6-inch         | 1         | 1.82%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch          | 1         | 1.82%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch          | 1         | 1.82%   |
| LG Display LCD Monitor LGD0372 1600x900 382x215mm 17.3-inch          | 1         | 1.82%   |
| LG Display LCD Monitor LGD02DA 1920x1080 382x215mm 17.3-inch         | 1         | 1.82%   |
| Insignia BBY LCD BBY0032 1920x540                                    | 1         | 1.82%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 1         | 1.82%   |
| Goldstar W1752 GSM4490 1440x900 370x232mm 17.2-inch                  | 1         | 1.82%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                               | 1         | 1.82%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 476x268mm 21.5-inch             | 1         | 1.82%   |
| Goldstar 24GL600F GSM5B73 1920x1080 531x298mm 24.0-inch              | 1         | 1.82%   |
| Dell P2421D DELD0FF 2560x1440 527x296mm 23.8-inch                    | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15D6 1920x1080 344x193mm 15.5-inch     | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15BB 1920x1080 344x194mm 15.5-inch     | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch     | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN1130 1366x768 256x144mm 11.6-inch      | 1         | 1.82%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                | 1         | 1.82%   |
| BOE LCD Monitor BOE07B5 1366x768 309x173mm 13.9-inch                 | 1         | 1.82%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                 | 1         | 1.82%   |
| BOE LCD Monitor BOE065F 1920x1080 344x194mm 15.5-inch                | 1         | 1.82%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                 | 1         | 1.82%   |
| BenQ LCD BNQ8024 2560x1440 600x340mm 27.2-inch                       | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch       | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO48EC 1366x768 344x193mm 15.5-inch        | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO305D 1920x1080 256x144mm 11.6-inch       | 1         | 1.82%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 25        | 48.08%  |
| 1366x768 (WXGA)    | 12        | 23.08%  |
| 1680x1050 (WSXGA+) | 3         | 5.77%   |
| 1600x900 (HD+)     | 3         | 5.77%   |
| 3840x2160 (4K)     | 2         | 3.85%   |
| 2560x1440 (QHD)    | 2         | 3.85%   |
| 3440x1440          | 1         | 1.92%   |
| 2880x1800          | 1         | 1.92%   |
| 1920x540           | 1         | 1.92%   |
| 1440x900 (WXGA+)   | 1         | 1.92%   |
| 1280x800 (WXGA)    | 1         | 1.92%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 12        | 22.22%  |
| 13     | 6         | 11.11%  |
| 21     | 5         | 9.26%   |
| 17     | 5         | 9.26%   |
| 14     | 5         | 9.26%   |
| 24     | 3         | 5.56%   |
| 23     | 3         | 5.56%   |
| 20     | 3         | 5.56%   |
| 40     | 2         | 3.7%    |
| 11     | 2         | 3.7%    |
| 72     | 1         | 1.85%   |
| 60     | 1         | 1.85%   |
| 48     | 1         | 1.85%   |
| 34     | 1         | 1.85%   |
| 31     | 1         | 1.85%   |
| 27     | 1         | 1.85%   |
| 22     | 1         | 1.85%   |
| 18     | 1         | 1.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 21        | 39.62%  |
| 401-500     | 10        | 18.87%  |
| 501-600     | 6         | 11.32%  |
| 351-400     | 5         | 9.43%   |
| 201-300     | 4         | 7.55%   |
| 801-900     | 2         | 3.77%   |
| 1001-1500   | 2         | 3.77%   |
| 701-800     | 1         | 1.89%   |
| 601-700     | 1         | 1.89%   |
| 1501-2000   | 1         | 1.89%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 43        | 82.69%  |
| 16/10 | 7         | 13.46%  |
| 21/9  | 1         | 1.92%   |
| 1.96  | 1         | 1.92%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 12        | 22.64%  |
| 81-90          | 10        | 18.87%  |
| 201-250        | 10        | 18.87%  |
| 151-200        | 4         | 7.55%   |
| 121-130        | 4         | 7.55%   |
| 501-1000       | 3         | 5.66%   |
| More than 1000 | 2         | 3.77%   |
| 51-60          | 2         | 3.77%   |
| 351-500        | 2         | 3.77%   |
| 71-80          | 1         | 1.89%   |
| 301-350        | 1         | 1.89%   |
| 141-150        | 1         | 1.89%   |
| 131-140        | 1         | 1.89%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 18        | 33.96%  |
| 51-100  | 16        | 30.19%  |
| 121-160 | 14        | 26.42%  |
| 161-240 | 3         | 5.66%   |
| 1-50    | 2         | 3.77%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 49        | 92.45%  |
| 2     | 4         | 7.55%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 31        | 36.9%   |
| Intel                           | 17        | 20.24%  |
| Qualcomm Atheros                | 12        | 14.29%  |
| Broadcom                        | 9         | 10.71%  |
| Marvell Technology Group        | 3         | 3.57%   |
| Broadcom Limited                | 3         | 3.57%   |
| Google                          | 2         | 2.38%   |
| Xiaomi                          | 1         | 1.19%   |
| TP-Link                         | 1         | 1.19%   |
| Samsung Electronics             | 1         | 1.19%   |
| Ralink Technology               | 1         | 1.19%   |
| Ralink                          | 1         | 1.19%   |
| Qualcomm Atheros Communications | 1         | 1.19%   |
| Motorola PCS                    | 1         | 1.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20        | 20.2%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 8.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 4.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 3.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 3.03%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 3.03%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 3         | 3.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 2.02%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 2.02%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 2.02%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 2.02%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.02%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 2.02%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 2         | 2.02%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 2.02%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.01%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.01%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.01%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.01%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1         | 1.01%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 1.01%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.01%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 1.01%   |
| Ralink RT2770 Wireless Adapter                                    | 1         | 1.01%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 1.01%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.01%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1         | 1.01%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.01%   |
| Motorola PCS moto g power (2022)                                  | 1         | 1.01%   |
| Intel Wireless-AC 9260                                            | 1         | 1.01%   |
| Intel Wireless 8265 / 8275                                        | 1         | 1.01%   |
| Intel Wireless 8260                                               | 1         | 1.01%   |
| Intel Wireless 7265                                               | 1         | 1.01%   |
| Intel Wireless 3165                                               | 1         | 1.01%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 1         | 1.01%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 1         | 1.01%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.01%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.01%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 12        | 26.09%  |
| Realtek Semiconductor           | 11        | 23.91%  |
| Qualcomm Atheros                | 9         | 19.57%  |
| Broadcom                        | 8         | 17.39%  |
| Broadcom Limited                | 3         | 6.52%   |
| Ralink Technology               | 1         | 2.17%   |
| Ralink                          | 1         | 2.17%   |
| Qualcomm Atheros Communications | 1         | 2.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 4         | 8.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 3         | 6.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 3         | 6.52%   |
| Broadcom BCM4321 802.11a/b/g/n                             | 3         | 6.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 2         | 4.35%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 2         | 4.35%   |
| Intel Wi-Fi 6 AX200                                        | 2         | 4.35%   |
| Broadcom BCM4331 802.11a/b/g/n                             | 2         | 4.35%   |
| Broadcom BCM43142 802.11b/g/n                              | 2         | 4.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 2.17%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter   | 1         | 2.17%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter            | 1         | 2.17%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 1         | 2.17%   |
| Realtek 802.11n WLAN Adapter                               | 1         | 2.17%   |
| Ralink RT2770 Wireless Adapter                             | 1         | 2.17%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                  | 1         | 2.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 2.17%   |
| Qualcomm Atheros AR9271 802.11n                            | 1         | 2.17%   |
| Intel Wireless-AC 9260                                     | 1         | 2.17%   |
| Intel Wireless 8265 / 8275                                 | 1         | 2.17%   |
| Intel Wireless 8260                                        | 1         | 2.17%   |
| Intel Wireless 7265                                        | 1         | 2.17%   |
| Intel Wireless 3165                                        | 1         | 2.17%   |
| Intel Ice Lake-LP PCH CNVi WiFi                            | 1         | 2.17%   |
| Intel Gemini Lake PCH CNVi WiFi                            | 1         | 2.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 1         | 2.17%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth            | 1         | 2.17%   |
| Intel Centrino Wireless-N 105                              | 1         | 2.17%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter | 1         | 2.17%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                     | 1         | 2.17%   |
| Broadcom Limited BCM43142 802.11b/g/n                      | 1         | 2.17%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                | 1         | 2.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 29        | 56.86%  |
| Intel                    | 6         | 11.76%  |
| Qualcomm Atheros         | 4         | 7.84%   |
| Broadcom                 | 4         | 7.84%   |
| Marvell Technology Group | 3         | 5.88%   |
| Google                   | 2         | 3.92%   |
| Xiaomi                   | 1         | 1.96%   |
| TP-Link                  | 1         | 1.96%   |
| Samsung Electronics      | 1         | 1.96%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20        | 38.46%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 15.38%  |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 5.77%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 3.85%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 3.85%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 3.85%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.92%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.92%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.92%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.92%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.92%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.92%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.92%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.92%   |
| Intel Ethernet Connection (17) I219-V                             | 1         | 1.92%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.92%   |
| Google Pixel 7 Pro                                                | 1         | 1.92%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 1.92%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.92%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.92%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 1.92%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 47        | 50%     |
| WiFi     | 46        | 48.94%  |
| Unknown  | 1         | 1.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 29        | 58%     |
| WiFi     | 21        | 42%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 35        | 66.04%  |
| 1     | 16        | 30.19%  |
| 3     | 1         | 1.89%   |
| 0     | 1         | 1.89%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 42        | 77.78%  |
| Yes  | 12        | 22.22%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 10        | 24.39%  |
| Realtek Semiconductor           | 8         | 19.51%  |
| Apple                           | 7         | 17.07%  |
| Qualcomm Atheros Communications | 5         | 12.2%   |
| Lite-On Technology              | 4         | 9.76%   |
| Broadcom                        | 2         | 4.88%   |
| Toshiba                         | 1         | 2.44%   |
| Ralink                          | 1         | 2.44%   |
| Dell                            | 1         | 2.44%   |
| Cambridge Silicon Radio         | 1         | 2.44%   |
| ASUSTek Computer                | 1         | 2.44%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 5         | 12.2%   |
| Realtek Bluetooth Radio                             | 4         | 9.76%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 9.76%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 7.32%   |
| Apple Bluetooth Host Controller                     | 3         | 7.32%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 4.88%   |
| Apple Bluetooth HCI                                 | 2         | 4.88%   |
| Toshiba Bluetooth Device                            | 1         | 2.44%   |
| Realtek RTL8821A Bluetooth                          | 1         | 2.44%   |
| Ralink RT3290 Bluetooth                             | 1         | 2.44%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 2.44%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 2.44%   |
| Lite-On Bluetooth Device                            | 1         | 2.44%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 2.44%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.44%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 2.44%   |
| Intel AX201 Bluetooth                               | 1         | 2.44%   |
| Intel AX200 Bluetooth                               | 1         | 2.44%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1         | 2.44%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.44%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 2.44%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 2.44%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 2.44%   |
| Apple Bluetooth USB Host Controller                 | 1         | 2.44%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 1         | 2.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 41        | 56.16%  |
| AMD                 | 14        | 19.18%  |
| Nvidia              | 13        | 17.81%  |
| C-Media Electronics | 2         | 2.74%   |
| Huawei Technologies | 1         | 1.37%   |
| Guillemot           | 1         | 1.37%   |
| Creative Labs       | 1         | 1.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 6         | 6.82%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 5         | 5.68%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 5.68%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 5.68%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 5.68%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 4.55%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 4.55%   |
| AMD FCH Azalia Controller                                                                         | 4         | 4.55%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3         | 3.41%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 3.41%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 3.41%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 2.27%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 2         | 2.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 2.27%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 2.27%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 2.27%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 1.14%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 1.14%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 1.14%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 1.14%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 1.14%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.14%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 1.14%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.14%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 1.14%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.14%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.14%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.14%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1         | 1.14%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 1.14%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 1         | 1.14%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.14%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 1.14%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.14%   |
| Huawei Technologies USB-C HEADSET                                                                 | 1         | 1.14%   |
| Guillemot Hercules DJ Console 4-Mx                                                                | 1         | 1.14%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                                        | 1         | 1.14%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                                               | 1         | 1.14%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 1.14%   |

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
| Chicony Electronics                    | 8         | 22.86%  |
| Apple                                  | 6         | 17.14%  |
| Realtek Semiconductor                  | 5         | 14.29%  |
| Suyin                                  | 3         | 8.57%   |
| Syntek                                 | 2         | 5.71%   |
| Sunplus Innovation Technology          | 2         | 5.71%   |
| Microdia                               | 2         | 5.71%   |
| Logitech                               | 2         | 5.71%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 5.71%   |
| webcamvendor                           | 1         | 2.86%   |
| Quanta                                 | 1         | 2.86%   |
| IMC Networks                           | 1         | 2.86%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Suyin HP Truevision HD                           | 3         | 8.33%   |
| Apple Built-in iSight                            | 3         | 8.33%   |
| Syntek Integrated Camera                         | 2         | 5.56%   |
| Realtek USB Camera                               | 2         | 5.56%   |
| Chicony Integrated Camera                        | 2         | 5.56%   |
| Apple FaceTime HD Camera (Built-in)              | 2         | 5.56%   |
| webcamvendor webcamproduct                       | 1         | 2.78%   |
| Sunplus Integrated_Webcam_HD                     | 1         | 2.78%   |
| Sunplus HD WebCam                                | 1         | 2.78%   |
| Realtek USB2.0 HD UVC WebCam                     | 1         | 2.78%   |
| Realtek Integrated_Webcam_HD                     | 1         | 2.78%   |
| Realtek Integrated Camera                        | 1         | 2.78%   |
| Quanta HD Webcam                                 | 1         | 2.78%   |
| Microdia Integrated_Webcam_HD                    | 1         | 2.78%   |
| Microdia Integrated Webcam HD                    | 1         | 2.78%   |
| Logitech Webcam C270                             | 1         | 2.78%   |
| Logitech HD Pro Webcam C920                      | 1         | 2.78%   |
| IMC Networks HP TrueVision HD Camera             | 1         | 2.78%   |
| Chicony USB2.0 VGA UVC WebCam                    | 1         | 2.78%   |
| Chicony USB2.0 HD UVC WebCam                     | 1         | 2.78%   |
| Chicony TOSHIBA Web Camera - HD                  | 1         | 2.78%   |
| Chicony Integrated Camera (1280x720@30)          | 1         | 2.78%   |
| Chicony HP HD Camera                             | 1         | 2.78%   |
| Chicony HD WebCam                                | 1         | 2.78%   |
| Chicony 5M Cam                                   | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) Webcam    | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 1         | 2.78%   |
| Apple FaceTime HD Camera                         | 1         | 2.78%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Synaptics        | 2         | 66.67%  |
| Validity Sensors | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader      | 1         | 33.33%  |
| Synaptics WBDI                                   | 1         | 33.33%  |
| Synaptics Metallica MIS Touch Fingerprint Reader | 1         | 33.33%  |

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
| 1     | 19        | 35.85%  |
| 2     | 16        | 30.19%  |
| 0     | 8         | 15.09%  |
| 3     | 7         | 13.21%  |
| 4     | 3         | 5.66%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 34        | 40%     |
| Net/wireless             | 19        | 22.35%  |
| Graphics card            | 6         | 7.06%   |
| Bluetooth                | 6         | 7.06%   |
| Card reader              | 5         | 5.88%   |
| Net/ethernet             | 4         | 4.71%   |
| Multimedia controller    | 4         | 4.71%   |
| Fingerprint reader       | 3         | 3.53%   |
| Firewire controller      | 2         | 2.35%   |
| Storage/ide              | 1         | 1.18%   |
| Chipcard                 | 1         | 1.18%   |

