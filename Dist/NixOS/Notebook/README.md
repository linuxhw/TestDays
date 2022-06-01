NixOS - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for NixOS.

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

Total: 40

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Apple         | MacBookPro11,5              | [5cd59453b1](https://linux-hardware.org/?probe=5cd59453b1) | Apr 15, 2022 |
| Framework     | Laptop                      | [4997cab79b](https://linux-hardware.org/?probe=4997cab79b) | Apr 14, 2022 |
| HP            | ProBook 450 G4              | [2cb837e17f](https://linux-hardware.org/?probe=2cb837e17f) | Apr 14, 2022 |
| Lenovo        | ThinkPad T490 20N2000LUK    | [a394ce9693](https://linux-hardware.org/?probe=a394ce9693) | Apr 13, 2022 |
| HP            | ProBook 450 G4              | [fb5bcd7c77](https://linux-hardware.org/?probe=fb5bcd7c77) | Apr 13, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [502a8c9d32](https://linux-hardware.org/?probe=502a8c9d32) | Apr 13, 2022 |
| Lenovo        | ThinkPad X260 20F5S4BY00    | [729b19eda3](https://linux-hardware.org/?probe=729b19eda3) | Apr 13, 2022 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [4c96d9df2f](https://linux-hardware.org/?probe=4c96d9df2f) | Apr 02, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [5570a879d3](https://linux-hardware.org/?probe=5570a879d3) | Mar 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [d6cae900dc](https://linux-hardware.org/?probe=d6cae900dc) | Mar 13, 2022 |
| GPD           | MicroPC                     | [a572eb2b39](https://linux-hardware.org/?probe=a572eb2b39) | Mar 11, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [f031fb1a5a](https://linux-hardware.org/?probe=f031fb1a5a) | Mar 11, 2022 |
| Lenovo        | ThinkPad T540p 20BE005YM... | [6d0cd0f4b9](https://linux-hardware.org/?probe=6d0cd0f4b9) | Mar 10, 2022 |
| Lenovo        | ThinkPad X260 20F5S6MF02    | [5e026c07c0](https://linux-hardware.org/?probe=5e026c07c0) | Mar 10, 2022 |
| MSI           | Bravo 15 B5DD               | [273737b3d7](https://linux-hardware.org/?probe=273737b3d7) | Feb 25, 2022 |
| OBSIDIAN-P... | N13_N140ZU                  | [9f2fdbfce5](https://linux-hardware.org/?probe=9f2fdbfce5) | Feb 25, 2022 |
| Dell          | Latitude 7420               | [64178dcbb7](https://linux-hardware.org/?probe=64178dcbb7) | Feb 08, 2022 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | [cf3fa03922](https://linux-hardware.org/?probe=cf3fa03922) | Jan 08, 2022 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | [d62840031f](https://linux-hardware.org/?probe=d62840031f) | Jan 08, 2022 |
| Lenovo        | Legion 5 17ARH05H 82GN      | [9e022a2288](https://linux-hardware.org/?probe=9e022a2288) | Dec 26, 2021 |
| Lenovo        | Legion 5 17ARH05H 82GN      | [8ff8fb5efd](https://linux-hardware.org/?probe=8ff8fb5efd) | Dec 26, 2021 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | [5fb4f1b6a6](https://linux-hardware.org/?probe=5fb4f1b6a6) | Nov 29, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [dbe8d36249](https://linux-hardware.org/?probe=dbe8d36249) | Nov 04, 2021 |
| Lenovo        | ThinkPad X250 20CLS18S0T    | [0151eadf78](https://linux-hardware.org/?probe=0151eadf78) | Oct 06, 2021 |
| HP            | ProBook 445 G7              | [36c94af49d](https://linux-hardware.org/?probe=36c94af49d) | Aug 09, 2021 |
| HP            | ProBook 445 G7              | [87a418ce6c](https://linux-hardware.org/?probe=87a418ce6c) | Aug 09, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [3df83086ef](https://linux-hardware.org/?probe=3df83086ef) | Aug 07, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [052ccd7a40](https://linux-hardware.org/?probe=052ccd7a40) | Aug 07, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [48fd4d3b89](https://linux-hardware.org/?probe=48fd4d3b89) | Aug 06, 2021 |
| Dell          | Latitude 7420               | [0624aeffd1](https://linux-hardware.org/?probe=0624aeffd1) | Jul 19, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | [d14e0ef395](https://linux-hardware.org/?probe=d14e0ef395) | Jun 18, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [fc12f446bb](https://linux-hardware.org/?probe=fc12f446bb) | May 23, 2021 |
| HP            | ZBook Studio G5             | [d323a9cfbf](https://linux-hardware.org/?probe=d323a9cfbf) | Apr 23, 2021 |
| Lenovo        | ThinkPad T460p 20FWCTO1W... | [38ab65a49b](https://linux-hardware.org/?probe=38ab65a49b) | Mar 18, 2021 |
| Lenovo        | ThinkPad T580 20L90024PB    | [8dc60fafaa](https://linux-hardware.org/?probe=8dc60fafaa) | Oct 13, 2020 |
| Dell          | XPS 15 9550                 | [5656cda6a4](https://linux-hardware.org/?probe=5656cda6a4) | Sep 01, 2020 |
| Dell          | XPS 15 9550                 | [550264c421](https://linux-hardware.org/?probe=550264c421) | Aug 22, 2020 |
| Lenovo        | ThinkPad T15 Gen 1 20S6C... | [71029187b1](https://linux-hardware.org/?probe=71029187b1) | Jul 03, 2020 |
| Acer          | Aspire E5-576G              | [c126c8b2fd](https://linux-hardware.org/?probe=c126c8b2fd) | Apr 15, 2020 |
| Gigabyte      | Sabre 15                    | [4f92cff461](https://linux-hardware.org/?probe=4f92cff461) | Jul 14, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| NixOS 22.05                      | 9         | 28.13%  |
| NixOS 21.11                      | 9         | 28.13%  |
| NixOS                            | 2         | 6.25%   |
| NixOS 21.11pre302265.c6c4a3d45ab | 1         | 3.13%   |
| NixOS 21.11.20210606.fbfb794     | 1         | 3.13%   |
| NixOS 21.05.4384.4f37689c8a2     | 1         | 3.13%   |
| NixOS 21.05.3443.ee90403e147     | 1         | 3.13%   |
| NixOS 21.05.2132.733682c3292     | 1         | 3.13%   |
| NixOS 21.05.20210423.c21475e     | 1         | 3.13%   |
| NixOS 21.03.20200927.84d74ae     | 1         | 3.13%   |
| NixOS 20.09pre-git               | 1         | 3.13%   |
| NixOS 20.03.2351.f8248ab6d9e     | 1         | 3.13%   |
| NixOS 19.09.2522.75f4ba05c63     | 1         | 3.13%   |
| NixOS 19.09.2220.92231f4f32f     | 1         | 3.13%   |
| NixOS 19.03.173054.754763ff4ba   | 1         | 3.13%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| NixOS | 31        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version         | Notebooks | Percent |
|-----------------|-----------|---------|
| 5.16.15         | 2         | 6.06%   |
| 5.15.26         | 2         | 6.06%   |
| 5.13.7          | 2         | 6.06%   |
| 5.8.4           | 1         | 3.03%   |
| 5.8.16-hardened | 1         | 3.03%   |
| 5.8.11          | 1         | 3.03%   |
| 5.7.4           | 1         | 3.03%   |
| 5.7.17          | 1         | 3.03%   |
| 5.4.24          | 1         | 3.03%   |
| 5.4.187         | 1         | 3.03%   |
| 5.17.1          | 1         | 3.03%   |
| 5.17.0          | 1         | 3.03%   |
| 5.16.8-zen1     | 1         | 3.03%   |
| 5.16.7          | 1         | 3.03%   |
| 5.16.3          | 1         | 3.03%   |
| 5.16.10         | 1         | 3.03%   |
| 5.15.4          | 1         | 3.03%   |
| 5.15.32         | 1         | 3.03%   |
| 5.15.3          | 1         | 3.03%   |
| 5.15.25         | 1         | 3.03%   |
| 5.15.22         | 1         | 3.03%   |
| 5.15.12         | 1         | 3.03%   |
| 5.15.0          | 1         | 3.03%   |
| 5.13.2          | 1         | 3.03%   |
| 5.12.7          | 1         | 3.03%   |
| 5.10.69         | 1         | 3.03%   |
| 5.10.30         | 1         | 3.03%   |
| 5.10.109        | 1         | 3.03%   |
| 4.19.57         | 1         | 3.03%   |
| 4.19.116        | 1         | 3.03%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.16.15  | 2         | 6.06%   |
| 5.15.26  | 2         | 6.06%   |
| 5.13.7   | 2         | 6.06%   |
| 5.8.4    | 1         | 3.03%   |
| 5.8.16   | 1         | 3.03%   |
| 5.8.11   | 1         | 3.03%   |
| 5.7.4    | 1         | 3.03%   |
| 5.7.17   | 1         | 3.03%   |
| 5.4.24   | 1         | 3.03%   |
| 5.4.187  | 1         | 3.03%   |
| 5.17.1   | 1         | 3.03%   |
| 5.17.0   | 1         | 3.03%   |
| 5.16.8   | 1         | 3.03%   |
| 5.16.7   | 1         | 3.03%   |
| 5.16.3   | 1         | 3.03%   |
| 5.16.10  | 1         | 3.03%   |
| 5.15.4   | 1         | 3.03%   |
| 5.15.32  | 1         | 3.03%   |
| 5.15.3   | 1         | 3.03%   |
| 5.15.25  | 1         | 3.03%   |
| 5.15.22  | 1         | 3.03%   |
| 5.15.12  | 1         | 3.03%   |
| 5.15.0   | 1         | 3.03%   |
| 5.13.2   | 1         | 3.03%   |
| 5.12.7   | 1         | 3.03%   |
| 5.10.69  | 1         | 3.03%   |
| 5.10.30  | 1         | 3.03%   |
| 5.10.109 | 1         | 3.03%   |
| 4.19.57  | 1         | 3.03%   |
| 4.19.116 | 1         | 3.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 9         | 27.27%  |
| 5.16    | 6         | 18.18%  |
| 5.8     | 3         | 9.09%   |
| 5.13    | 3         | 9.09%   |
| 5.10    | 3         | 9.09%   |
| 5.7     | 2         | 6.06%   |
| 5.4     | 2         | 6.06%   |
| 5.17    | 2         | 6.06%   |
| 4.19    | 2         | 6.06%   |
| 5.12    | 1         | 3.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 31        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Unknown     | 25        | 80.65%  |
| GNOME       | 2         | 6.45%   |
| XFCE        | 1         | 3.23%   |
| sway        | 1         | 3.23%   |
| none+xmonad | 1         | 3.23%   |
| KDE         | 1         | 3.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 24        | 77.42%  |
| X11     | 3         | 9.68%   |
| Wayland | 3         | 9.68%   |
| Tty     | 1         | 3.23%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 29        | 93.55%  |
| LightDM | 1         | 3.23%   |
| GDM     | 1         | 3.23%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 22        | 70.97%  |
| en_US   | 6         | 19.35%  |
| ru_RU   | 1         | 3.23%   |
| ro_RO   | 1         | 3.23%   |
| en_DK   | 1         | 3.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 26        | 83.87%  |
| BIOS | 5         | 16.13%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 20        | 62.5%   |
| Tmpfs   | 4         | 12.5%   |
| Btrfs   | 4         | 12.5%   |
| Unknown | 3         | 9.38%   |
| Zfs     | 1         | 3.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 28        | 90.32%  |
| Unknown | 3         | 9.68%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 23        | 74.19%  |
| Yes       | 8         | 25.81%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 23        | 74.19%  |
| Yes       | 8         | 25.81%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 14        | 45.16%  |
| Hewlett-Packard     | 4         | 12.9%   |
| ASUSTek Computer    | 4         | 12.9%   |
| Dell                | 2         | 6.45%   |
| OBSIDIAN-PC         | 1         | 3.23%   |
| MSI                 | 1         | 3.23%   |
| GPD                 | 1         | 3.23%   |
| Gigabyte Technology | 1         | 3.23%   |
| Framework           | 1         | 3.23%   |
| Apple               | 1         | 3.23%   |
| Acer                | 1         | 3.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| OBSIDIAN-PC N13_N140ZU                | 1         | 3.23%   |
| MSI Bravo 15 B5DD                     | 1         | 3.23%   |
| Lenovo Yoga Slim 7 13ACN5 82CY        | 1         | 3.23%   |
| Lenovo ThinkPad X390 20Q0CTO1WW       | 1         | 3.23%   |
| Lenovo ThinkPad X260 20F5S6MF02       | 1         | 3.23%   |
| Lenovo ThinkPad X260 20F5S4BY00       | 1         | 3.23%   |
| Lenovo ThinkPad X250 20CLS18S0T       | 1         | 3.23%   |
| Lenovo ThinkPad T580 20L90024PB       | 1         | 3.23%   |
| Lenovo ThinkPad T540p 20BE005YMH      | 1         | 3.23%   |
| Lenovo ThinkPad T490 20N2000LUK       | 1         | 3.23%   |
| Lenovo ThinkPad T480 20L5CTO1WW       | 1         | 3.23%   |
| Lenovo ThinkPad T460p 20FWCTO1WW      | 1         | 3.23%   |
| Lenovo ThinkPad T15 Gen 1 20S6CTO1WW  | 1         | 3.23%   |
| Lenovo ThinkPad T14s Gen 1 20UH001AUK | 1         | 3.23%   |
| Lenovo ThinkPad T14 Gen 1 20UD0013RT  | 1         | 3.23%   |
| Lenovo Legion 5 17ARH05H 82GN         | 1         | 3.23%   |
| HP ZBook Studio G5                    | 1         | 3.23%   |
| HP ProBook 450 G4                     | 1         | 3.23%   |
| HP ProBook 445 G7                     | 1         | 3.23%   |
| HP EliteBook 845 G8 Notebook PC       | 1         | 3.23%   |
| GPD MicroPC                           | 1         | 3.23%   |
| Gigabyte Sabre 15                     | 1         | 3.23%   |
| Framework Laptop                      | 1         | 3.23%   |
| Dell XPS 15 9550                      | 1         | 3.23%   |
| Dell Latitude 7420                    | 1         | 3.23%   |
| ASUS ZenBook UX391FA_UX391FA          | 1         | 3.23%   |
| ASUS ROG Zephyrus G14 GA401QM_GA401QM | 1         | 3.23%   |
| ASUS ROG Strix G533QR_G533QR          | 1         | 3.23%   |
| ASUS ROG Flow X13 GV301QE_GV301QE     | 1         | 3.23%   |
| Apple MacBookPro11,5                  | 1         | 3.23%   |
| Acer Aspire E5-576G                   | 1         | 3.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 12        | 38.71%  |
| ASUS ROG           | 3         | 9.68%   |
| HP ProBook         | 2         | 6.45%   |
| OBSIDIAN-PC N13    | 1         | 3.23%   |
| MSI Bravo          | 1         | 3.23%   |
| Lenovo Yoga        | 1         | 3.23%   |
| Lenovo Legion      | 1         | 3.23%   |
| HP ZBook           | 1         | 3.23%   |
| HP EliteBook       | 1         | 3.23%   |
| GPD MicroPC        | 1         | 3.23%   |
| Gigabyte Sabre     | 1         | 3.23%   |
| Framework Laptop   | 1         | 3.23%   |
| Dell XPS           | 1         | 3.23%   |
| Dell Latitude      | 1         | 3.23%   |
| ASUS ZenBook       | 1         | 3.23%   |
| Apple MacBookPro11 | 1         | 3.23%   |
| Acer Aspire        | 1         | 3.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 7         | 22.58%  |
| 2021 | 6         | 19.35%  |
| 2016 | 5         | 16.13%  |
| 2019 | 4         | 12.9%   |
| 2018 | 4         | 12.9%   |
| 2017 | 2         | 6.45%   |
| 2015 | 2         | 6.45%   |
| 2013 | 1         | 3.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 31        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 31        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 31        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 11        | 35.48%  |
| 32.01-64.0  | 10        | 32.26%  |
| 8.01-16.0   | 6         | 19.35%  |
| 4.01-8.0    | 2         | 6.45%   |
| 24.01-32.0  | 1         | 3.23%   |
| 64.01-256.0 | 1         | 3.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 13        | 39.39%  |
| 8.01-16.0  | 7         | 21.21%  |
| 3.01-4.0   | 5         | 15.15%  |
| 2.01-3.0   | 3         | 9.09%   |
| 24.01-32.0 | 2         | 6.06%   |
| 1.01-2.0   | 2         | 6.06%   |
| 32.01-64.0 | 1         | 3.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 23        | 74.19%  |
| 2      | 8         | 25.81%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 30        | 96.77%  |
| Yes       | 1         | 3.23%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 75%     |
| No        | 8         | 25%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 96.77%  |
| No        | 1         | 3.23%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 28        | 87.5%   |
| No        | 4         | 12.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| UK          | 4         | 12.9%   |
| Ukraine     | 3         | 9.68%   |
| Poland      | 3         | 9.68%   |
| Russia      | 2         | 6.45%   |
| Germany     | 2         | 6.45%   |
| France      | 2         | 6.45%   |
| Canada      | 2         | 6.45%   |
| Belgium     | 2         | 6.45%   |
| USA         | 1         | 3.23%   |
| Uruguay     | 1         | 3.23%   |
| Switzerland | 1         | 3.23%   |
| Sweden      | 1         | 3.23%   |
| Spain       | 1         | 3.23%   |
| Romania     | 1         | 3.23%   |
| Portugal    | 1         | 3.23%   |
| Netherlands | 1         | 3.23%   |
| Iran        | 1         | 3.23%   |
| Colombia    | 1         | 3.23%   |
| Austria     | 1         | 3.23%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Marki              | 2         | 6.45%   |
| London             | 2         | 6.45%   |
| Woodford           | 1         | 3.23%   |
| Vienna             | 1         | 3.23%   |
| Verneuil-sur-Seine | 1         | 3.23%   |
| Valpacos           | 1         | 3.23%   |
| Tottenham          | 1         | 3.23%   |
| Tolyatti           | 1         | 3.23%   |
| Tehran             | 1         | 3.23%   |
| Stockholm          | 1         | 3.23%   |
| South Deerfield    | 1         | 3.23%   |
| Ottawa             | 1         | 3.23%   |
| Mykolayiv          | 1         | 3.23%   |
| Montevideo         | 1         | 3.23%   |
| Mons               | 1         | 3.23%   |
| Melsele            | 1         | 3.23%   |
| Lehrte             | 1         | 3.23%   |
| Krakow             | 1         | 3.23%   |
| Kiel               | 1         | 3.23%   |
| Kharkiv            | 1         | 3.23%   |
| Irpin              | 1         | 3.23%   |
| Getafe             | 1         | 3.23%   |
| Enschede           | 1         | 3.23%   |
| Cluj-Napoca        | 1         | 3.23%   |
| Chelyabinsk        | 1         | 3.23%   |
| Cergy              | 1         | 3.23%   |
| Cartagena          | 1         | 3.23%   |
| Bedford            | 1         | 3.23%   |
| Allschwil          | 1         | 3.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 15     | 34.21%  |
| WDC                 | 5         | 5      | 13.16%  |
| SK Hynix            | 3         | 4      | 7.89%   |
| Transcend           | 2         | 2      | 5.26%   |
| Toshiba             | 2         | 2      | 5.26%   |
| Micron Technology   | 2         | 2      | 5.26%   |
| Kingston            | 2         | 2      | 5.26%   |
| Crucial             | 2         | 3      | 5.26%   |
| Seagate             | 1         | 1      | 2.63%   |
| KIOXIA              | 1         | 1      | 2.63%   |
| Intel               | 1         | 1      | 2.63%   |
| INNOVATION IT       | 1         | 1      | 2.63%   |
| HGST                | 1         | 1      | 2.63%   |
| BIWIN               | 1         | 1      | 2.63%   |
| Apple               | 1         | 1      | 2.63%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| WDC WDS480G2G0B-00EPW0 480GB SSD     | 1         | 2.56%   |
| WDC WDS200T1X0E-00AFY0 2TB           | 1         | 2.56%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB   | 1         | 2.56%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB | 1         | 2.56%   |
| WDC PC SN530 SDBPTPZ-1T00-1002 1TB   | 1         | 2.56%   |
| Transcend TS256GMTS800 256GB SSD     | 1         | 2.56%   |
| Transcend TS256GMTS430S 256GB SSD    | 1         | 2.56%   |
| Toshiba MQ01ABD100 1TB               | 1         | 2.56%   |
| Toshiba KXG6AZNV512G 512GB           | 1         | 2.56%   |
| SK Hynix PC711 HFS512GDE9X073N 512GB | 1         | 2.56%   |
| SK Hynix NVMe SSD Drive 1TB          | 1         | 2.56%   |
| SK Hynix NVMe SSD Drive 1024GB       | 1         | 2.56%   |
| SK Hynix HFM001TD3JX013N 1TB         | 1         | 2.56%   |
| Seagate ST2000LM007-1R8174 2TB       | 1         | 2.56%   |
| Samsung SSD 970 EVO 500GB            | 1         | 2.56%   |
| Samsung SSD 870 EVO 500GB            | 1         | 2.56%   |
| Samsung SSD 860 EVO 1TB              | 1         | 2.56%   |
| Samsung Portable SSD T5 500GB        | 1         | 2.56%   |
| Samsung PM9A1 NVMe 1024GB            | 1         | 2.56%   |
| Samsung NVMe SSD Drive 512GB         | 1         | 2.56%   |
| Samsung MZVLB512HBJQ-000L7 512GB     | 1         | 2.56%   |
| Samsung MZVLB512HAJQ-000H1 512GB     | 1         | 2.56%   |
| Samsung MZVLB512HAJQ-00000 512GB     | 1         | 2.56%   |
| Samsung MZVLB256HAHQ-000L7 256GB     | 1         | 2.56%   |
| Samsung MZVLB1T0HBLR-000L7 1TB       | 1         | 2.56%   |
| Samsung MZVLB1T0HBLR-000L2 1TB       | 1         | 2.56%   |
| Samsung MZ7LN512HMJP-000L7 512GB SSD | 1         | 2.56%   |
| Micron MTFDHBA512TDV 512GB           | 1         | 2.56%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD  | 1         | 2.56%   |
| KIOXIA NVMe SSD Drive 256GB          | 1         | 2.56%   |
| Kingston SA400S37960G 960GB SSD      | 1         | 2.56%   |
| Kingston OM8PCP3512F-AI1 512GB       | 1         | 2.56%   |
| Intel SSDPEKKF010T8L 1TB             | 1         | 2.56%   |
| INNOVATION IT IT 240GB SSD           | 1         | 2.56%   |
| HGST HTS721010A9E630 1TB             | 1         | 2.56%   |
| Crucial CT250MX500SSD1 250GB         | 1         | 2.56%   |
| Crucial CT1000MX500SSD1 1TB          | 1         | 2.56%   |
| BIWIN SSD 128GB                      | 1         | 2.56%   |
| Apple SSD SM0512G 500GB              | 1         | 2.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 33.33%  |
| Seagate | 1         | 1      | 33.33%  |
| HGST    | 1         | 1      | 33.33%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 28.57%  |
| Transcend           | 2         | 2      | 14.29%  |
| Crucial             | 2         | 3      | 14.29%  |
| WDC                 | 1         | 1      | 7.14%   |
| Micron Technology   | 1         | 1      | 7.14%   |
| Kingston            | 1         | 1      | 7.14%   |
| INNOVATION IT       | 1         | 1      | 7.14%   |
| BIWIN               | 1         | 1      | 7.14%   |
| Apple               | 1         | 1      | 7.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 21        | 24     | 58.33%  |
| SSD  | 12        | 15     | 33.33%  |
| HDD  | 3         | 3      | 8.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 21        | 24     | 61.76%  |
| SATA | 12        | 17     | 35.29%  |
| SAS  | 1         | 1      | 2.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 9         | 10     | 56.25%  |
| 0.51-1.0   | 6         | 7      | 37.5%   |
| 1.01-2.0   | 1         | 1      | 6.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 23        | 74.19%  |
| 1-20           | 4         | 12.9%   |
| More than 3000 | 1         | 3.23%   |
| 251-500        | 1         | 3.23%   |
| 1001-2000      | 1         | 3.23%   |
| 501-1000       | 1         | 3.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| Unknown   | 23        | 74.19%  |
| 1-20      | 4         | 12.9%   |
| 101-250   | 2         | 6.45%   |
| 251-500   | 1         | 3.23%   |
| 1001-2000 | 1         | 3.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 33.33%  |
| SK Hynix PC711 HFS512GDE9X073N 512GB           | 1         | 1      | 33.33%  |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 1         | 1      | 33.33%  |
| SK Hynix          | 1         | 1      | 33.33%  |
| Micron Technology | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 1         | 1      | 33.33%  |
| SSD  | 1         | 1      | 33.33%  |
| HDD  | 1         | 1      | 33.33%  |

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
| Works    | 27        | 33     | 79.41%  |
| Detected | 4         | 6      | 11.76%  |
| Malfunc  | 3         | 3      | 8.82%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 13        | 36.11%  |
| Samsung Electronics          | 10        | 27.78%  |
| Sandisk                      | 4         | 11.11%  |
| SK Hynix                     | 3         | 8.33%   |
| AMD                          | 2         | 5.56%   |
| Toshiba America Info Systems | 1         | 2.78%   |
| Micron Technology            | 1         | 2.78%   |
| KIOXIA                       | 1         | 2.78%   |
| Kingston Technology Company  | 1         | 2.78%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7         | 19.44%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 11.11%  |
| SK Hynix Gold P31 SSD                                                          | 3         | 8.33%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 8.33%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 2         | 5.56%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 2.78%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 2.78%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 2.78%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 2.78%   |
| Sandisk Non-Volatile memory controller                                         | 1         | 2.78%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 2.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 2.78%   |
| Samsung Electronics SATA controller                                            | 1         | 2.78%   |
| Micron Non-Volatile memory controller                                          | 1         | 2.78%   |
| KIOXIA Non-Volatile memory controller                                          | 1         | 2.78%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 2.78%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 2.78%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 2.78%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 2.78%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 2.78%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 2.78%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 2.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 21        | 58.33%  |
| SATA | 15        | 41.67%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 21        | 67.74%  |
| AMD    | 10        | 32.26%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz          | 3         | 9.68%   |
| Intel Core i7-8550U CPU @ 1.80GHz          | 3         | 9.68%   |
| Intel Core i5-6300U CPU @ 2.40GHz          | 2         | 6.45%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 2         | 6.45%   |
| AMD Ryzen 7 5800H with Radeon Graphics     | 2         | 6.45%   |
| Intel Xeon E-2176M CPU @ 2.70GHz           | 1         | 3.23%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 1         | 3.23%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 1         | 3.23%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz         | 1         | 3.23%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 1         | 3.23%   |
| Intel Core i7-5600U CPU @ 2.60GHz          | 1         | 3.23%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz         | 1         | 3.23%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz         | 1         | 3.23%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 1         | 3.23%   |
| Intel Core i5-8265U CPU @ 1.60GHz          | 1         | 3.23%   |
| Intel Celeron N4100 CPU @ 1.10GHz          | 1         | 3.23%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz    | 1         | 3.23%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 1         | 3.23%   |
| AMD Ryzen 9 5900HS with Radeon Graphics    | 1         | 3.23%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics | 1         | 3.23%   |
| AMD Ryzen 7 5800U with Radeon Graphics     | 1         | 3.23%   |
| AMD Ryzen 7 5800HS with Radeon Graphics    | 1         | 3.23%   |
| AMD Ryzen 7 4800H with Radeon Graphics     | 1         | 3.23%   |
| AMD Ryzen 7 4700U with Radeon Graphics     | 1         | 3.23%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i7   | 14        | 45.16%  |
| AMD Ryzen 7     | 6         | 19.35%  |
| Intel Core i5   | 3         | 9.68%   |
| AMD Ryzen 7 PRO | 3         | 9.68%   |
| Other           | 2         | 6.45%   |
| Intel Xeon      | 1         | 3.23%   |
| Intel Celeron   | 1         | 3.23%   |
| AMD Ryzen 9     | 1         | 3.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 16        | 51.61%  |
| 8      | 10        | 32.26%  |
| 2      | 4         | 12.9%   |
| 6      | 1         | 3.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 31        | 100%    |

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
| 32-bit, 64-bit | 31        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x0a50000c | 5         | 16.13%  |
| Unknown    | 4         | 12.9%   |
| 0x806ea    | 3         | 9.68%   |
| 0x08600106 | 3         | 9.68%   |
| 0x806ec    | 2         | 6.45%   |
| 0x806eb    | 2         | 6.45%   |
| 0x406e3    | 2         | 6.45%   |
| 0x906ea    | 1         | 3.23%   |
| 0x906e9    | 1         | 3.23%   |
| 0x806e9    | 1         | 3.23%   |
| 0x806c1    | 1         | 3.23%   |
| 0x706a1    | 1         | 3.23%   |
| 0x506e3    | 1         | 3.23%   |
| 0x306d4    | 1         | 3.23%   |
| 0x306c3    | 1         | 3.23%   |
| 0x0a50000b | 1         | 3.23%   |
| 0x08600104 | 1         | 3.23%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 11        | 35.48%  |
| Zen 3         | 6         | 19.35%  |
| Zen 2         | 4         | 12.9%   |
| Skylake       | 4         | 12.9%   |
| TigerLake     | 2         | 6.45%   |
| Haswell       | 2         | 6.45%   |
| Goldmont plus | 1         | 3.23%   |
| Broadwell     | 1         | 3.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 19        | 45.24%  |
| Nvidia | 12        | 28.57%  |
| AMD    | 11        | 26.19%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| AMD Cezanne                                                 | 6         | 13.95%  |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                  | 4         | 9.3%    |
| AMD Renoir                                                  | 4         | 9.3%    |
| Intel UHD Graphics 620                                      | 3         | 6.98%   |
| Nvidia GP108M [GeForce MX150]                               | 2         | 4.65%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                   | 2         | 4.65%   |
| Intel Skylake GT2 [HD Graphics 520]                         | 2         | 4.65%   |
| Intel HD Graphics 530                                       | 2         | 4.65%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                  | 1         | 2.33%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                  | 1         | 2.33%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                       | 1         | 2.33%   |
| Nvidia GM108M [GeForce 940MX]                               | 1         | 2.33%   |
| Nvidia GM108M [GeForce 930MX]                               | 1         | 2.33%   |
| Nvidia GM107M [GeForce GTX 960M]                            | 1         | 2.33%   |
| Nvidia GK208M [GeForce GT 730M]                             | 1         | 2.33%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                  | 1         | 2.33%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]             | 1         | 2.33%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]             | 1         | 2.33%   |
| Intel HD Graphics 630                                       | 1         | 2.33%   |
| Intel HD Graphics 620                                       | 1         | 2.33%   |
| Intel HD Graphics 5500                                      | 1         | 2.33%   |
| Intel GeminiLake [UHD Graphics 600]                         | 1         | 2.33%   |
| Intel CometLake-U GT2 [UHD Graphics]                        | 1         | 2.33%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller | 1         | 2.33%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]             | 1         | 2.33%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]              | 1         | 2.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 12        | 38.71%  |
| Intel + Nvidia | 7         | 22.58%  |
| 1 x AMD        | 6         | 19.35%  |
| AMD + Nvidia   | 4         | 12.9%   |
| 2 x AMD        | 1         | 3.23%   |
| 1 x Nvidia     | 1         | 3.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 27        | 87.1%   |
| Proprietary | 4         | 12.9%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 16        | 51.61%  |
| 0.01-0.5   | 8         | 25.81%  |
| 1.01-2.0   | 4         | 12.9%   |
| 3.01-4.0   | 2         | 6.45%   |
| 0.51-1.0   | 1         | 3.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 6         | 15.38%  |
| AU Optronics        | 5         | 12.82%  |
| Chimei Innolux      | 4         | 10.26%  |
| Samsung Electronics | 3         | 7.69%   |
| PANDA               | 3         | 7.69%   |
| Dell                | 3         | 7.69%   |
| BOE                 | 3         | 7.69%   |
| Sharp               | 2         | 5.13%   |
| InfoVision          | 2         | 5.13%   |
| Panasonic           | 1         | 2.56%   |
| Lenovo              | 1         | 2.56%   |
| JDI                 | 1         | 2.56%   |
| Hewlett-Packard     | 1         | 2.56%   |
| Eizo                | 1         | 2.56%   |
| ASUSTek Computer    | 1         | 2.56%   |
| Apple               | 1         | 2.56%   |
| AOC                 | 1         | 2.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch           | 1         | 2.56%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch           | 1         | 2.56%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch | 1         | 2.56%   |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch | 1         | 2.56%   |
| Samsung Electronics C32F39M SAM100B 1920x1080 698x393mm 31.5-inch | 1         | 2.56%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch           | 1         | 2.56%   |
| PANDA LCD Monitor NCP0062 1920x1080 309x174mm 14.0-inch           | 1         | 2.56%   |
| PANDA LCD Monitor NCP005E 1920x1080 309x174mm 14.0-inch           | 1         | 2.56%   |
| Panasonic VVX16T029D00 MEI96A2 2880x1620 344x193mm 15.5-inch      | 1         | 2.56%   |
| LG Display LCD Monitor LGD0649 2560x1600 286x179mm 13.3-inch      | 1         | 2.56%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch      | 1         | 2.56%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch      | 1         | 2.56%   |
| LG Display LCD Monitor LGD0504 1366x768 344x194mm 15.5-inch       | 1         | 2.56%   |
| LG Display LCD Monitor LGD049A 2560x1440 310x174mm 14.0-inch      | 1         | 2.56%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch      | 1         | 2.56%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch          | 1         | 2.56%   |
| JDI LCD Monitor JDI385A 3840x2160 294x165mm 13.3-inch             | 1         | 2.56%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch      | 1         | 2.56%   |
| InfoVision LCD Monitor IVO04E5 1366x768 276x155mm 12.5-inch       | 1         | 2.56%   |
| Hewlett-Packard Z27 HPN3535 3840x2160 597x336mm 27.0-inch         | 1         | 2.56%   |
| Eizo L568 ENC1734 1280x1024 338x270mm 17.0-inch                   | 1         | 2.56%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                 | 1         | 2.56%   |
| Dell P2715Q DEL40BD 3840x2160 597x336mm 27.0-inch                 | 1         | 2.56%   |
| Dell P2418D DELD0C2 2560x1440 526x296mm 23.8-inch                 | 1         | 2.56%   |
| Chimei Innolux LCD Monitor CMN175C 1920x1080 381x214mm 17.2-inch  | 1         | 2.56%   |
| Chimei Innolux LCD Monitor CMN152A 2560x1440 344x193mm 15.5-inch  | 1         | 2.56%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch  | 1         | 2.56%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch  | 1         | 2.56%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch             | 1         | 2.56%   |
| BOE LCD Monitor BOE0957 1920x1080 344x194mm 15.5-inch             | 1         | 2.56%   |
| BOE LCD Monitor BOE08D8 1920x1080 344x194mm 15.5-inch             | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO5A2D 1920x1080 293x165mm 13.2-inch    | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch    | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO4A90 1920x1080 309x174mm 14.0-inch    | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO2336 2560x1440 309x174mm 14.0-inch    | 1         | 2.56%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 276x155mm 12.5-inch    | 1         | 2.56%   |
| ASUSTek Computer VP28U AUS28B1 3840x2160 620x340mm 27.8-inch      | 1         | 2.56%   |
| Apple Color LCD APPA02E 2880x1800 331x207mm 15.4-inch             | 1         | 2.56%   |
| AOC 2770G4 AOC2770 1920x1080 598x336mm 27.0-inch                  | 1         | 2.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 18        | 48.65%  |
| 3840x2160 (4K)    | 6         | 16.22%  |
| 2560x1440 (QHD)   | 5         | 13.51%  |
| 1366x768 (WXGA)   | 2         | 5.41%   |
| 3440x1440         | 1         | 2.7%    |
| 2880x1800         | 1         | 2.7%    |
| 2560x1600         | 1         | 2.7%    |
| 2256x1504         | 1         | 2.7%    |
| 1920x1200 (WUXGA) | 1         | 2.7%    |
| 1280x1024 (SXGA)  | 1         | 2.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 9         | 23.08%  |
| 14     | 8         | 20.51%  |
| 13     | 7         | 17.95%  |
| 27     | 5         | 12.82%  |
| 17     | 3         | 7.69%   |
| 12     | 3         | 7.69%   |
| 34     | 1         | 2.56%   |
| 31     | 1         | 2.56%   |
| 24     | 1         | 2.56%   |
| 23     | 1         | 2.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 19        | 50%     |
| 201-300     | 8         | 21.05%  |
| 501-600     | 6         | 15.79%  |
| 601-700     | 2         | 5.26%   |
| 351-400     | 2         | 5.26%   |
| 701-800     | 1         | 2.63%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 25        | 80.65%  |
| 16/10 | 3         | 9.68%   |
| 5/4   | 1         | 3.23%   |
| 3/2   | 1         | 3.23%   |
| 21/9  | 1         | 3.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 11        | 28.21%  |
| 101-110        | 9         | 23.08%  |
| 301-350        | 5         | 12.82%  |
| 71-80          | 4         | 10.26%  |
| 61-70          | 3         | 7.69%   |
| 351-500        | 2         | 5.13%   |
| 201-250        | 2         | 5.13%   |
| 121-130        | 2         | 5.13%   |
| 141-150        | 1         | 2.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 15        | 41.67%  |
| 161-240       | 11        | 30.56%  |
| 51-100        | 4         | 11.11%  |
| More than 240 | 3         | 8.33%   |
| 101-120       | 3         | 8.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 21        | 65.63%  |
| 2     | 8         | 25%     |
| 0     | 2         | 6.25%   |
| 3     | 1         | 3.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 28        | 57.14%  |
| Realtek Semiconductor             | 17        | 34.69%  |
| Microsoft                         | 1         | 2.04%   |
| Fibocom                           | 1         | 2.04%   |
| Ericsson Business Mobile Networks | 1         | 2.04%   |
| Broadcom                          | 1         | 2.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 17.74%  |
| Intel Wi-Fi 6 AX200                                               | 8         | 12.9%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 11.29%  |
| Intel Wireless 8260                                               | 3         | 4.84%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 4.84%   |
| Intel Wireless-AC 9260                                            | 2         | 3.23%   |
| Intel Wireless 8265 / 8275                                        | 2         | 3.23%   |
| Intel Wireless 7265                                               | 2         | 3.23%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 3.23%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 3.23%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 3.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 3.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.61%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1         | 1.61%   |
| Intel Wireless 7260                                               | 1         | 1.61%   |
| Intel Wireless 3165                                               | 1         | 1.61%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 1.61%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.61%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.61%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.61%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.61%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.61%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.61%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 1.61%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                 | 1         | 1.61%   |
| Ericsson Business Mobile Networks N5321 gw                        | 1         | 1.61%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1         | 1.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 28        | 87.5%   |
| Realtek Semiconductor | 1         | 3.13%   |
| Microsoft             | 1         | 3.13%   |
| Fibocom               | 1         | 3.13%   |
| Broadcom              | 1         | 3.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                      | 8         | 25%     |
| Intel Wireless 8260                                      | 3         | 9.38%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                 | 3         | 9.38%   |
| Intel Wireless-AC 9260                                   | 2         | 6.25%   |
| Intel Wireless 8265 / 8275                               | 2         | 6.25%   |
| Intel Wireless 7265                                      | 2         | 6.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]         | 2         | 6.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter | 1         | 3.13%   |
| Microsoft Xbox 360 Wireless Adapter                      | 1         | 3.13%   |
| Intel Wireless 7260                                      | 1         | 3.13%   |
| Intel Wireless 3165                                      | 1         | 3.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                   | 1         | 3.13%   |
| Intel Wi-Fi 6 AX201                                      | 1         | 3.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                        | 1         | 3.13%   |
| Intel Cannon Lake PCH CNVi WiFi                          | 1         | 3.13%   |
| Fibocom L830-EB-00 LTE WWAN Modem                        | 1         | 3.13%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC              | 1         | 3.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 16        | 61.54%  |
| Intel                 | 10        | 38.46%  |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 37.93%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 24.14%  |
| Intel Ethernet Connection I219-LM                                 | 2         | 6.9%    |
| Intel Ethernet Connection (6) I219-V                              | 2         | 6.9%    |
| Intel Ethernet Connection (4) I219-V                              | 2         | 6.9%    |
| Intel I210 Gigabit Network Connection                             | 1         | 3.45%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 3.45%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 3.45%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 3.45%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 3.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 30        | 54.55%  |
| Ethernet | 24        | 43.64%  |
| Modem    | 1         | 1.82%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 28        | 75.68%  |
| Ethernet | 9         | 24.32%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 19        | 61.29%  |
| 1     | 11        | 35.48%  |
| 3     | 1         | 3.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 27        | 87.1%   |
| Yes  | 4         | 12.9%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 27        | 96.43%  |
| Realtek Semiconductor | 1         | 3.57%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 8         | 28.57%  |
| Intel AX200 Bluetooth                          | 8         | 28.57%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 4         | 14.29%  |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 2         | 7.14%   |
| Intel Wireless-AC 3168 Bluetooth               | 2         | 7.14%   |
| Intel AX201 Bluetooth                          | 2         | 7.14%   |
| Realtek 802.11ac WLAN Adapter                  | 1         | 3.57%   |
| Intel AX210 Bluetooth                          | 1         | 3.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 21        | 50%     |
| AMD                       | 11        | 26.19%  |
| Nvidia                    | 3         | 7.14%   |
| Trust                     | 1         | 2.38%   |
| Sennheiser Communications | 1         | 2.38%   |
| Realtek Semiconductor     | 1         | 2.38%   |
| Lenovo                    | 1         | 2.38%   |
| Kingston Technology       | 1         | 2.38%   |
| Corsair                   | 1         | 2.38%   |
| C-Media Electronics       | 1         | 2.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                  | 10        | 18.52%  |
| AMD Renoir Radeon High Definition Audio Controller                      | 9         | 16.67%  |
| Intel Sunrise Point-LP HD Audio                                         | 6         | 11.11%  |
| Intel Cannon Point-LP High Definition Audio Controller                  | 4         | 7.41%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller             | 2         | 3.7%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 2         | 3.7%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller         | 2         | 3.7%    |
| Trust USB microphone                                                    | 1         | 1.85%   |
| Sennheiser Communications Headset [PC 8]                                | 1         | 1.85%   |
| Realtek Semiconductor USB Audio                                         | 1         | 1.85%   |
| Nvidia GP107GL High Definition Audio Controller                         | 1         | 1.85%   |
| Nvidia GA104 High Definition Audio Controller                           | 1         | 1.85%   |
| Nvidia Audio device                                                     | 1         | 1.85%   |
| Lenovo ThinkPad Thunderbolt 4 Dock USB Audio                            | 1         | 1.85%   |
| Kingston Technology HyperX 7.1 Audio                                    | 1         | 1.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller        | 1         | 1.85%   |
| Intel Wildcat Point-LP High Definition Audio Controller                 | 1         | 1.85%   |
| Intel Comet Lake PCH-LP cAVS                                            | 1         | 1.85%   |
| Intel CM238 HD Audio Controller                                         | 1         | 1.85%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio            | 1         | 1.85%   |
| Intel Cannon Lake PCH cAVS                                              | 1         | 1.85%   |
| Intel Broadwell-U Audio Controller                                      | 1         | 1.85%   |
| Corsair HS70 Pro Wireless Gaming Headset                                | 1         | 1.85%   |
| C-Media Electronics USB Advanced Audio Device                           | 1         | 1.85%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 1         | 1.85%   |
| AMD Navi 10 HDMI Audio                                                  | 1         | 1.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 13        | 38.24%  |
| Micron Technology   | 7         | 20.59%  |
| Crucial             | 4         | 11.76%  |
| SK Hynix            | 2         | 5.88%   |
| Kingston            | 2         | 5.88%   |
| Unknown (ABCD)      | 1         | 2.94%   |
| GOODRAM             | 1         | 2.94%   |
| G.Skill             | 1         | 2.94%   |
| Corsair             | 1         | 2.94%   |
| Avant               | 1         | 2.94%   |
| AMD                 | 1         | 2.94%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 5.41%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 5.41%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM DDR4 2400MT/s   | 1         | 2.7%    |
| SK Hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 1         | 2.7%    |
| SK Hynix RAM H9HCNNNCPMMLXR-NEE 8GB Row Of Chips LPDDR4 4266MT/s | 1         | 2.7%    |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 2.7%    |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                  | 1         | 2.7%    |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                  | 1         | 2.7%    |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 1         | 2.7%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 2.7%    |
| Samsung RAM M471A2K43CB1-CRC 16384MB SODIMM DDR4 2667MT/s        | 1         | 2.7%    |
| Samsung RAM M471A2K43BB1-CPB 16GB Chip DDR4 2133MT/s             | 1         | 2.7%    |
| Samsung RAM M471A2K43BB1-CPB 16384MB SODIMM DDR4 2133MT/s        | 1         | 2.7%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.7%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 2.7%    |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 2.7%    |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 1         | 2.7%    |
| Micron RAM MT53E1G32D2NP-046 8GB SODIMM LPDDR4 4266MT/s          | 1         | 2.7%    |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 1         | 2.7%    |
| Micron RAM 53E2G32D4NQ-046 4096MB Row Of Chips LPDDR4 4267MT/s   | 1         | 2.7%    |
| Micron RAM 4ATS1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s          | 1         | 2.7%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 1         | 2.7%    |
| Micron RAM 16KTF2G64HZ-1G6A1 16GB SODIMM DDR3 1600MT/s           | 1         | 2.7%    |
| Micron RAM 16KTF1G64HZ-1G6E1 8192MB SODIMM DDR3 1600MT/s         | 1         | 2.7%    |
| Kingston RAM ACR16D3LS1KBGR/8G 8192MB SODIMM DDR3 1600MT/s       | 1         | 2.7%    |
| Kingston RAM 9905744-035.A00G 16GB SODIMM DDR4 3200MT/s          | 1         | 2.7%    |
| GOODRAM RAM GR2400S464L17S/8G 8GB SODIMM DDR4 2400MT/s           | 1         | 2.7%    |
| G.Skill RAM F4-2400C16-16GRS 16GB SODIMM DDR4 2667MT/s           | 1         | 2.7%    |
| Crucial RAM CT32G4SFD832A.M16FF 32GB SODIMM DDR4 3200MT/s        | 1         | 2.7%    |
| Crucial RAM CT16G4SFD824A.C16FBD 16384MB SODIMM DDR4 2667MT/s    | 1         | 2.7%    |
| Crucial RAM CT16G4SFD8213.M16FB 16GB SODIMM DDR4 2133MT/s        | 1         | 2.7%    |
| Crucial RAM CB16GS2666.C8ET 16GB SODIMM DDR4 2667MT/s            | 1         | 2.7%    |
| Corsair RAM CMSO8GX3M1A1600C11 8GB SODIMM DDR3 1600MT/s          | 1         | 2.7%    |
| Avant RAM J642GU42J2320NQ 16384MB SODIMM DDR4 3200MT/s           | 1         | 2.7%    |
| AMD RAM R9432G3206S2S 32GB SODIMM DDR4 3200MT/s                  | 1         | 2.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 20        | 68.97%  |
| LPDDR4 | 4         | 13.79%  |
| DDR3   | 4         | 13.79%  |
| LPDDR3 | 1         | 3.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 26        | 86.67%  |
| Row Of Chips | 3         | 10%     |
| Chip         | 1         | 3.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 15        | 46.88%  |
| 16384 | 12        | 37.5%   |
| 32768 | 3         | 9.38%   |
| 4096  | 2         | 6.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 9         | 30%     |
| 2667  | 7         | 23.33%  |
| 2133  | 5         | 16.67%  |
| 1600  | 4         | 13.33%  |
| 4266  | 2         | 6.67%   |
| 2400  | 2         | 6.67%   |
| 4267  | 1         | 3.33%   |

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


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 10        | 38.46%  |
| IMC Networks                  | 5         | 19.23%  |
| Acer                          | 4         | 15.38%  |
| Microdia                      | 2         | 7.69%   |
| Sunplus Innovation Technology | 1         | 3.85%   |
| Realtek Semiconductor         | 1         | 3.85%   |
| Quanta                        | 1         | 3.85%   |
| Logitech                      | 1         | 3.85%   |
| Lite-On Technology            | 1         | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Chicony Integrated Camera           | 6         | 22.22%  |
| IMC Networks Integrated Camera      | 3         | 11.11%  |
| Chicony HP HD Camera                | 3         | 11.11%  |
| IMC Networks USB2.0 HD UVC WebCam   | 2         | 7.41%   |
| Sunplus Integrated_Webcam_FHD       | 1         | 3.7%    |
| Realtek Laptop Camera               | 1         | 3.7%    |
| Quanta HD WebCam                    | 1         | 3.7%    |
| Microdia USB 2.0 Camera             | 1         | 3.7%    |
| Microdia Integrated_Webcam_HD       | 1         | 3.7%    |
| Logitech Webcam C310                | 1         | 3.7%    |
| Lite-On HP HD Camera                | 1         | 3.7%    |
| Chicony USB2.0 Camera               | 1         | 3.7%    |
| Acer ThinkPad P50 Integrated Camera | 1         | 3.7%    |
| Acer SunplusIT Integrated Camera    | 1         | 3.7%    |
| Acer Integrated IR Camera           | 1         | 3.7%    |
| Acer Integrated Camera              | 1         | 3.7%    |
| Acer HD Webcam                      | 1         | 3.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 6         | 54.55%  |
| Validity Sensors           | 4         | 36.36%  |
| Shenzhen Goodix Technology | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 4         | 36.36%  |
| Validity Sensors VFS 5011 fingerprint sensor      | 2         | 18.18%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 9.09%   |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 9.09%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 9.09%   |
| Shenzhen Goodix Fingerprint Reader                | 1         | 9.09%   |
| Unknown                                           | 1         | 9.09%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 8         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 8         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 11        | 35.48%  |
| 0     | 11        | 35.48%  |
| 2     | 8         | 25.81%  |
| 4     | 1         | 3.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 10        | 32.26%  |
| Chipcard              | 7         | 22.58%  |
| Graphics card         | 6         | 19.35%  |
| Multimedia controller | 5         | 16.13%  |
| Network               | 1         | 3.23%   |
| Net/wireless          | 1         | 3.23%   |
| Camera                | 1         | 3.23%   |

