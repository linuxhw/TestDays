SteamOS - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for SteamOS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/SteamOS/Desktop/README.md) and [notebooks](/Dist/SteamOS/Notebook/README.md).

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

Total: 88

| Vendor    | Model                       | Form-Factor | Probe                                                      | Date         |
|-----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Valve     | Jupiter                     | Notebook    | [c591d23b4d](https://linux-hardware.org/?probe=c591d23b4d) | Jul 01, 2022 |
| Gigabyte  | X570 I AORUS PRO WIFI       | Desktop     | [d82f88e20c](https://linux-hardware.org/?probe=d82f88e20c) | Jul 01, 2022 |
| Valve     | Jupiter                     | Notebook    | [bee9822ef6](https://linux-hardware.org/?probe=bee9822ef6) | Jun 30, 2022 |
| Valve     | Jupiter                     | Notebook    | [e98c07bc79](https://linux-hardware.org/?probe=e98c07bc79) | Jun 29, 2022 |
| Valve     | Jupiter                     | Notebook    | [261590e542](https://linux-hardware.org/?probe=261590e542) | Jun 29, 2022 |
| Valve     | Jupiter                     | Notebook    | [7c233f0a07](https://linux-hardware.org/?probe=7c233f0a07) | Jun 29, 2022 |
| HP        | x2 210 G2                   | Tablet      | [812530aed8](https://linux-hardware.org/?probe=812530aed8) | Jun 28, 2022 |
| Valve     | Jupiter                     | Notebook    | [e80815c8d4](https://linux-hardware.org/?probe=e80815c8d4) | Jun 27, 2022 |
| Valve     | Jupiter                     | Notebook    | [65e5ab29fd](https://linux-hardware.org/?probe=65e5ab29fd) | Jun 26, 2022 |
| Valve     | Jupiter                     | Notebook    | [e51f5d8645](https://linux-hardware.org/?probe=e51f5d8645) | Jun 26, 2022 |
| Alienware | 02XRCM A01                  | Desktop     | [c70647bab0](https://linux-hardware.org/?probe=c70647bab0) | Jun 26, 2022 |
| Valve     | Jupiter                     | Notebook    | [b4dd19f939](https://linux-hardware.org/?probe=b4dd19f939) | Jun 25, 2022 |
| AZW       | SER V01                     | Mini pc     | [295a32d26e](https://linux-hardware.org/?probe=295a32d26e) | Jun 24, 2022 |
| Valve     | Jupiter                     | Notebook    | [c9ed3cf311](https://linux-hardware.org/?probe=c9ed3cf311) | Jun 23, 2022 |
| ASUSTek   | H61M-K                      | Desktop     | [1a568c2e5f](https://linux-hardware.org/?probe=1a568c2e5f) | Jun 23, 2022 |
| ASUSTek   | Q524UQK                     | Convertible | [fd5f128747](https://linux-hardware.org/?probe=fd5f128747) | Jun 23, 2022 |
| Dell      | G15 5510                    | Notebook    | [9c5777f505](https://linux-hardware.org/?probe=9c5777f505) | Jun 23, 2022 |
| Valve     | Jupiter                     | Notebook    | [213fbe4dd2](https://linux-hardware.org/?probe=213fbe4dd2) | Jun 22, 2022 |
| Valve     | Jupiter                     | Notebook    | [262a7f0cd4](https://linux-hardware.org/?probe=262a7f0cd4) | Jun 22, 2022 |
| Valve     | Jupiter                     | Notebook    | [f8722866b2](https://linux-hardware.org/?probe=f8722866b2) | Jun 22, 2022 |
| Valve     | Jupiter                     | Notebook    | [aa18022bce](https://linux-hardware.org/?probe=aa18022bce) | Jun 22, 2022 |
| Valve     | Jupiter                     | Notebook    | [000682313d](https://linux-hardware.org/?probe=000682313d) | Jun 20, 2022 |
| Valve     | Jupiter                     | Notebook    | [363ab9e4ea](https://linux-hardware.org/?probe=363ab9e4ea) | Jun 20, 2022 |
| Valve     | Jupiter                     | Notebook    | [dd5765a418](https://linux-hardware.org/?probe=dd5765a418) | Jun 18, 2022 |
| Valve     | Jupiter                     | Notebook    | [8e293bb4b1](https://linux-hardware.org/?probe=8e293bb4b1) | Jun 17, 2022 |
| Valve     | Jupiter                     | Notebook    | [ff0ce08944](https://linux-hardware.org/?probe=ff0ce08944) | Jun 16, 2022 |
| Valve     | Jupiter                     | Notebook    | [68a581ae0b](https://linux-hardware.org/?probe=68a581ae0b) | Jun 12, 2022 |
| HP        | Pavilion Gaming Laptop 1... | Notebook    | [df3f1b5d8f](https://linux-hardware.org/?probe=df3f1b5d8f) | Jun 11, 2022 |
| Valve     | Jupiter                     | Notebook    | [2353bf0f9d](https://linux-hardware.org/?probe=2353bf0f9d) | Jun 11, 2022 |
| Valve     | Jupiter                     | Notebook    | [17406c8741](https://linux-hardware.org/?probe=17406c8741) | Jun 11, 2022 |
| Apple     | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [7ccfe2d3a7](https://linux-hardware.org/?probe=7ccfe2d3a7) | Jun 10, 2022 |
| Valve     | Jupiter                     | Notebook    | [715e914cba](https://linux-hardware.org/?probe=715e914cba) | Jun 10, 2022 |
| Valve     | Jupiter                     | Notebook    | [cc0a20bb93](https://linux-hardware.org/?probe=cc0a20bb93) | Jun 06, 2022 |
| Valve     | Jupiter                     | Notebook    | [2fb1bfad12](https://linux-hardware.org/?probe=2fb1bfad12) | Jun 04, 2022 |
| Valve     | Jupiter                     | Notebook    | [322bdc2ce3](https://linux-hardware.org/?probe=322bdc2ce3) | Jun 03, 2022 |
| Valve     | Jupiter                     | Notebook    | [780d6b923a](https://linux-hardware.org/?probe=780d6b923a) | Jun 02, 2022 |
| ASUSTek   | ROG STRIX B550-F GAMING     | Desktop     | [b3a08001ed](https://linux-hardware.org/?probe=b3a08001ed) | Jun 01, 2022 |
| ASRock    | B550 PG Velocita            | Desktop     | [0d7f71a24d](https://linux-hardware.org/?probe=0d7f71a24d) | May 30, 2022 |
| ASRock    | B365M Pro4-F                | Desktop     | [afc161c6fb](https://linux-hardware.org/?probe=afc161c6fb) | May 30, 2022 |
| Valve     | Jupiter                     | Notebook    | [f3910c9796](https://linux-hardware.org/?probe=f3910c9796) | May 29, 2022 |
| Valve     | Jupiter                     | Notebook    | [e415de106f](https://linux-hardware.org/?probe=e415de106f) | May 29, 2022 |
| Valve     | Jupiter                     | Notebook    | [0af4b9c805](https://linux-hardware.org/?probe=0af4b9c805) | May 29, 2022 |
| Valve     | Jupiter                     | Notebook    | [06b56d54d4](https://linux-hardware.org/?probe=06b56d54d4) | May 28, 2022 |
| Gigabyte  | B560M AORUS PRO             | Desktop     | [31f246f96e](https://linux-hardware.org/?probe=31f246f96e) | May 27, 2022 |
| Gigabyte  | B560M AORUS PRO             | Desktop     | [1d381d6ec9](https://linux-hardware.org/?probe=1d381d6ec9) | May 27, 2022 |
| Valve     | Jupiter                     | Notebook    | [1e966da4f8](https://linux-hardware.org/?probe=1e966da4f8) | May 27, 2022 |
| Valve     | Jupiter                     | Notebook    | [c716690aa2](https://linux-hardware.org/?probe=c716690aa2) | May 27, 2022 |
| Valve     | Jupiter                     | Notebook    | [43f315aa0c](https://linux-hardware.org/?probe=43f315aa0c) | May 27, 2022 |
| Valve     | Jupiter                     | Notebook    | [643322d821](https://linux-hardware.org/?probe=643322d821) | May 26, 2022 |
| Gigabyte  | Z170XP-SLI-CF               | Desktop     | [d4bef1e450](https://linux-hardware.org/?probe=d4bef1e450) | May 26, 2022 |
| HP        | Pavilion Gaming Laptop 1... | Notebook    | [b672eefb50](https://linux-hardware.org/?probe=b672eefb50) | May 25, 2022 |
| Valve     | Jupiter                     | Notebook    | [dee0bbedd1](https://linux-hardware.org/?probe=dee0bbedd1) | May 25, 2022 |
| HP        | 8158 A01                    | Mini pc     | [0d32a2b2e3](https://linux-hardware.org/?probe=0d32a2b2e3) | May 24, 2022 |
| ASUSTek   | PN50                        | Mini pc     | [da9b5c2be2](https://linux-hardware.org/?probe=da9b5c2be2) | May 24, 2022 |
| Valve     | Jupiter                     | Notebook    | [c34173715a](https://linux-hardware.org/?probe=c34173715a) | May 24, 2022 |
| Valve     | Jupiter                     | Notebook    | [6ca95b630c](https://linux-hardware.org/?probe=6ca95b630c) | May 23, 2022 |
| Valve     | Jupiter                     | Notebook    | [7d3f9c0a5f](https://linux-hardware.org/?probe=7d3f9c0a5f) | May 23, 2022 |
| Acer      | Aspire A315-23              | Notebook    | [b5d37bf4f2](https://linux-hardware.org/?probe=b5d37bf4f2) | May 22, 2022 |
| Samsung   | 950XDB/951XDB/950XDY        | Notebook    | [fc970670a8](https://linux-hardware.org/?probe=fc970670a8) | May 22, 2022 |
| Valve     | Jupiter                     | Notebook    | [595b06f6c9](https://linux-hardware.org/?probe=595b06f6c9) | May 22, 2022 |
| Valve     | Jupiter                     | Notebook    | [d706d00651](https://linux-hardware.org/?probe=d706d00651) | May 21, 2022 |
| Valve     | Jupiter                     | Notebook    | [317e492fa3](https://linux-hardware.org/?probe=317e492fa3) | May 21, 2022 |
| Valve     | Jupiter                     | Notebook    | [f849597120](https://linux-hardware.org/?probe=f849597120) | May 18, 2022 |
| Valve     | Jupiter                     | Notebook    | [48df6e5c71](https://linux-hardware.org/?probe=48df6e5c71) | May 18, 2022 |
| Valve     | Jupiter                     | Notebook    | [9cf4d23a81](https://linux-hardware.org/?probe=9cf4d23a81) | May 13, 2022 |
| Valve     | Jupiter                     | Notebook    | [79f6db1d69](https://linux-hardware.org/?probe=79f6db1d69) | May 08, 2022 |
| Valve     | Jupiter                     | Notebook    | [771539d18d](https://linux-hardware.org/?probe=771539d18d) | May 03, 2022 |
| Valve     | Jupiter                     | Notebook    | [19d2c51aa6](https://linux-hardware.org/?probe=19d2c51aa6) | May 01, 2022 |
| Valve     | Jupiter                     | Notebook    | [1c826aed5e](https://linux-hardware.org/?probe=1c826aed5e) | Apr 30, 2022 |
| Valve     | Jupiter                     | Notebook    | [4c43342014](https://linux-hardware.org/?probe=4c43342014) | Apr 24, 2022 |
| Valve     | Jupiter                     | Notebook    | [8564bded7f](https://linux-hardware.org/?probe=8564bded7f) | Apr 21, 2022 |
| Valve     | Jupiter                     | Notebook    | [d761657c3a](https://linux-hardware.org/?probe=d761657c3a) | Apr 21, 2022 |
| Valve     | Jupiter                     | Notebook    | [f2e59fcb97](https://linux-hardware.org/?probe=f2e59fcb97) | Apr 20, 2022 |
| Valve     | Jupiter                     | Notebook    | [4f23fab4fd](https://linux-hardware.org/?probe=4f23fab4fd) | Apr 17, 2022 |
| Valve     | Jupiter                     | Notebook    | [ed07e93435](https://linux-hardware.org/?probe=ed07e93435) | Apr 16, 2022 |
| Valve     | Jupiter                     | Notebook    | [48aacdeee8](https://linux-hardware.org/?probe=48aacdeee8) | Apr 15, 2022 |
| Valve     | Jupiter                     | Notebook    | [6a042646dd](https://linux-hardware.org/?probe=6a042646dd) | Apr 14, 2022 |
| Valve     | Jupiter                     | Notebook    | [d4c9dba2a1](https://linux-hardware.org/?probe=d4c9dba2a1) | Apr 14, 2022 |
| Valve     | Jupiter                     | Notebook    | [852b6fb53a](https://linux-hardware.org/?probe=852b6fb53a) | Apr 08, 2022 |
| Valve     | Jupiter                     | Notebook    | [6129b15fb5](https://linux-hardware.org/?probe=6129b15fb5) | Apr 05, 2022 |
| Valve     | Jupiter                     | Notebook    | [ec05067a1d](https://linux-hardware.org/?probe=ec05067a1d) | Apr 03, 2022 |
| Valve     | Jupiter                     | Notebook    | [180c84c856](https://linux-hardware.org/?probe=180c84c856) | Apr 02, 2022 |
| Valve     | Jupiter                     | Notebook    | [d8625616de](https://linux-hardware.org/?probe=d8625616de) | Mar 30, 2022 |
| Valve     | Jupiter                     | Notebook    | [d181a912af](https://linux-hardware.org/?probe=d181a912af) | Mar 23, 2022 |
| Valve     | Jupiter                     | Notebook    | [0b6a21cf35](https://linux-hardware.org/?probe=0b6a21cf35) | Mar 18, 2022 |
| Valve     | Jupiter                     | Notebook    | [85328e8f3d](https://linux-hardware.org/?probe=85328e8f3d) | Mar 17, 2022 |
| Valve     | Jupiter                     | Notebook    | [023aea75e1](https://linux-hardware.org/?probe=023aea75e1) | Mar 14, 2022 |
| Valve     | Jupiter                     | Notebook    | [c7f6388908](https://linux-hardware.org/?probe=c7f6388908) | Mar 11, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| SteamOS 3.2                  | 31        | 40.26%  |
| SteamOS Snapshot             | 26        | 33.77%  |
| SteamOS 3.2 (steamdeck-main) | 10        | 12.99%  |
| SteamOS 3.1                  | 8         | 10.39%  |
| SteamOS Rolling              | 1         | 1.3%    |
| SteamOS 3.4                  | 1         | 1.3%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SteamOS | 75        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                            | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| 5.13.0-valve15-1-neptune-02197-gf6ec7ad3762a       | 26        | 33.77%  |
| 5.13.0-valve10.1-2-neptune-dri-02144-g7fffaf925dfb | 18        | 23.38%  |
| 5.13.0-valve10.1-1-neptune-02144-g7fffaf925dfb     | 16        | 20.78%  |
| 5.13.0-valve10.3-1-neptune-02176-g5fe416c4acd8     | 10        | 12.99%  |
| 5.13.0-valve14-1-neptune-02195-g5b0f749d00fa       | 5         | 6.49%   |
| 5.16.2-arch1-1                                     | 1         | 1.3%    |
| 5.13.0-valve20-1-neptune-02207-gbd986a7e1c7f       | 1         | 1.3%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13.0  | 74        | 98.67%  |
| 5.16.2  | 1         | 1.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13    | 74        | 98.67%  |
| 5.16    | 1         | 1.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 75        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| KDE5    | 74        | 98.67%  |
| Unknown | 1         | 1.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 75        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 74        | 98.67%  |
| SDDM    | 1         | 1.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 63        | 84%     |
| fr_FR | 3         | 4%      |
| en_GB | 2         | 2.67%   |
| pt_PT | 1         | 1.33%   |
| pt_BR | 1         | 1.33%   |
| it_IT | 1         | 1.33%   |
| es_ES | 1         | 1.33%   |
| en_IE | 1         | 1.33%   |
| en_DE | 1         | 1.33%   |
| an_ES | 1         | 1.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 73        | 97.33%  |
| EFI  | 2         | 2.67%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 75        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 73        | 97.33%  |
| GPT     | 2         | 2.67%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 74        | 98.67%  |
| Yes       | 1         | 1.33%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 74        | 98.67%  |
| Yes       | 1         | 1.33%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Valve               | 56        | 74.67%  |
| Hewlett-Packard     | 4         | 5.33%   |
| ASUSTek Computer    | 4         | 5.33%   |
| Gigabyte Technology | 3         | 4%      |
| ASRock              | 2         | 2.67%   |
| Samsung Electronics | 1         | 1.33%   |
| Dell                | 1         | 1.33%   |
| AZW                 | 1         | 1.33%   |
| Apple               | 1         | 1.33%   |
| Alienware           | 1         | 1.33%   |
| Acer                | 1         | 1.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Valve Jupiter                       | 56        | 74.67%  |
| Samsung 950XDB/951XDB/950XDY        | 1         | 1.33%   |
| HP x2 210 G2                        | 1         | 1.33%   |
| HP t630 Thin Client                 | 1         | 1.33%   |
| HP Pavilion Gaming Laptop 15-ec2xxx | 1         | 1.33%   |
| HP Pavilion Gaming Laptop 15-dk0xxx | 1         | 1.33%   |
| Gigabyte X570 I AORUS PRO WIFI      | 1         | 1.33%   |
| Gigabyte MBB-670016                 | 1         | 1.33%   |
| Gigabyte B560M AORUS PRO            | 1         | 1.33%   |
| Dell G15 5510                       | 1         | 1.33%   |
| AZW SER                             | 1         | 1.33%   |
| ASUS ROG STRIX B550-F GAMING        | 1         | 1.33%   |
| ASUS Q524UQK                        | 1         | 1.33%   |
| ASUS MINIPC PN50                    | 1         | 1.33%   |
| ASUS H61M-K                         | 1         | 1.33%   |
| ASRock B550 PG Velocita             | 1         | 1.33%   |
| ASRock B365M Pro4-F                 | 1         | 1.33%   |
| Apple Macmini7,1                    | 1         | 1.33%   |
| Alienware Aurora R8                 | 1         | 1.33%   |
| Acer Aspire A315-23                 | 1         | 1.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Valve Jupiter       | 56        | 74.67%  |
| HP Pavilion         | 2         | 2.67%   |
| Samsung 950XDB      | 1         | 1.33%   |
| HP x2               | 1         | 1.33%   |
| HP t630             | 1         | 1.33%   |
| Gigabyte X570       | 1         | 1.33%   |
| Gigabyte MBB-670016 | 1         | 1.33%   |
| Gigabyte B560M      | 1         | 1.33%   |
| Dell G15            | 1         | 1.33%   |
| AZW SER             | 1         | 1.33%   |
| ASUS ROG            | 1         | 1.33%   |
| ASUS Q524UQK        | 1         | 1.33%   |
| ASUS MINIPC         | 1         | 1.33%   |
| ASUS H61M-K         | 1         | 1.33%   |
| ASRock B550         | 1         | 1.33%   |
| ASRock B365M        | 1         | 1.33%   |
| Apple Macmini7      | 1         | 1.33%   |
| Alienware Aurora    | 1         | 1.33%   |
| Acer Aspire         | 1         | 1.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2022    | 46        | 61.33%  |
| Unknown | 12        | 16%     |
| 2020    | 5         | 6.67%   |
| 2021    | 3         | 4%      |
| 2019    | 3         | 4%      |
| 2016    | 2         | 2.67%   |
| 2018    | 1         | 1.33%   |
| 2017    | 1         | 1.33%   |
| 2015    | 1         | 1.33%   |
| 2013    | 1         | 1.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 61        | 81.33%  |
| Desktop     | 8         | 10.67%  |
| Mini pc     | 4         | 5.33%   |
| Tablet      | 1         | 1.33%   |
| Convertible | 1         | 1.33%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 75        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 75        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 59        | 78.67%  |
| 4.01-8.0   | 5         | 6.67%   |
| 16.01-24.0 | 5         | 6.67%   |
| 32.01-64.0 | 3         | 4%      |
| 24.01-32.0 | 2         | 2.67%   |
| 3.01-4.0   | 1         | 1.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 35        | 44.87%  |
| 3.01-4.0 | 20        | 25.64%  |
| 4.01-8.0 | 14        | 17.95%  |
| 1.01-2.0 | 9         | 11.54%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 2      | 42        | 55.26%  |
| 1      | 25        | 32.89%  |
| 3      | 5         | 6.58%   |
| 4      | 3         | 3.95%   |
| 7      | 1         | 1.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 73        | 97.33%  |
| Yes       | 2         | 2.67%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 49        | 65.33%  |
| Yes       | 26        | 34.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 73        | 97.33%  |
| No        | 2         | 2.67%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 69        | 92%     |
| No        | 6         | 8%      |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 34        | 45.33%  |
| UK          | 9         | 12%     |
| Germany     | 9         | 12%     |
| France      | 4         | 5.33%   |
| Netherlands | 3         | 4%      |
| Spain       | 2         | 2.67%   |
| Australia   | 2         | 2.67%   |
| Slovakia    | 1         | 1.33%   |
| Portugal    | 1         | 1.33%   |
| Poland      | 1         | 1.33%   |
| Latvia      | 1         | 1.33%   |
| Italy       | 1         | 1.33%   |
| Ireland     | 1         | 1.33%   |
| Hungary     | 1         | 1.33%   |
| Greece      | 1         | 1.33%   |
| Czechia     | 1         | 1.33%   |
| Canada      | 1         | 1.33%   |
| Brazil      | 1         | 1.33%   |
| Austria     | 1         | 1.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Colorado Springs | 2         | 2.63%   |
| Wokingham        | 1         | 1.32%   |
| Whitley Bay      | 1         | 1.32%   |
| Washington       | 1         | 1.32%   |
| Warsaw           | 1         | 1.32%   |
| Tuam             | 1         | 1.32%   |
| Treviso          | 1         | 1.32%   |
| Torre del Mar    | 1         | 1.32%   |
| Tilburg          | 1         | 1.32%   |
| Thessaloniki     | 1         | 1.32%   |
| Temecula         | 1         | 1.32%   |
| St Louis         | 1         | 1.32%   |
| Spanish Fork     | 1         | 1.32%   |
| South Holland    | 1         | 1.32%   |
| Shepperton       | 1         | 1.32%   |
| Seattle          | 1         | 1.32%   |
| San Diego        | 1         | 1.32%   |
| Sacramento       | 1         | 1.32%   |
| Rueil-Malmaison  | 1         | 1.32%   |
| Rohnert Park     | 1         | 1.32%   |
| Riga             | 1         | 1.32%   |
| Reignier-Esery   | 1         | 1.32%   |
| Portland         | 1         | 1.32%   |
| Phoenix          | 1         | 1.32%   |
| Perth            | 1         | 1.32%   |
| Palatine         | 1         | 1.32%   |
| Odenton          | 1         | 1.32%   |
| Oakham           | 1         | 1.32%   |
| Nuremberg        | 1         | 1.32%   |
| Noble Park       | 1         | 1.32%   |
| Newberg          | 1         | 1.32%   |
| Nashville        | 1         | 1.32%   |
| Mooresville      | 1         | 1.32%   |
| Maplewood        | 1         | 1.32%   |
| Manchester       | 1         | 1.32%   |
| Lodi             | 1         | 1.32%   |
| Leicester        | 1         | 1.32%   |
| Knoxville        | 1         | 1.32%   |
| Klagenfurt       | 1         | 1.32%   |
| Kenosha          | 1         | 1.32%   |
| Kansas City      | 1         | 1.32%   |
| Ivry-sur-Seine   | 1         | 1.32%   |
| Iserlohn         | 1         | 1.32%   |
| Hornsea          | 1         | 1.32%   |
| Heerhugowaard    | 1         | 1.32%   |
| Hanau            | 1         | 1.32%   |
| Goochland        | 1         | 1.32%   |
| Germantown       | 1         | 1.32%   |
| Fort Myers       | 1         | 1.32%   |
| Fenton           | 1         | 1.32%   |
| Eaubonne         | 1         | 1.32%   |
| Dresden          | 1         | 1.32%   |
| Detroit          | 1         | 1.32%   |
| Dallas           | 1         | 1.32%   |
| Charlotte        | 1         | 1.32%   |
| Buffalo          | 1         | 1.32%   |
| Budapest         | 1         | 1.32%   |
| Bromley          | 1         | 1.32%   |
| Brno             | 1         | 1.32%   |
| Bremen           | 1         | 1.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Unknown                        | 30        | 31     | 22.56%  |
| Kingston                       | 26        | 28     | 19.55%  |
| Phison                         | 20        | 20     | 15.04%  |
| Samsung Electronics            | 10        | 15     | 7.52%   |
| Unknown                        | 10        | 11     | 7.52%   |
| O2 Micro                       | 8         | 8      | 6.02%   |
| WDC                            | 4         | 5      | 3.01%   |
| Seagate                        | 4         | 6      | 3.01%   |
| Silicon Motion                 | 3         | 3      | 2.26%   |
| Toshiba                        | 2         | 3      | 1.5%    |
| SK hynix                       | 2         | 2      | 1.5%    |
| PNY                            | 2         | 2      | 1.5%    |
| Union Memory (Shenzhen)        | 1         | 1      | 0.75%   |
| Solid State Storage Technology | 1         | 1      | 0.75%   |
| SanDisk                        | 1         | 1      | 0.75%   |
| Lexar 25                       | 1         | 1      | 0.75%   |
| JMicron Technology             | 1         | 1      | 0.75%   |
| Intel                          | 1         | 1      | 0.75%   |
| HP Phison                      | 1         | 1      | 0.75%   |
| External                       | 1         | 2      | 0.75%   |
| Crucial                        | 1         | 1      | 0.75%   |
| ASMT                           | 1         | 1      | 0.75%   |
| ADATA Technology               | 1         | 1      | 0.75%   |
| A-DATA Technology              | 1         | 1      | 0.75%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Kingston NVMe SSD Drive 512GB                | 15        | 10.64%  |
| Unknown MMC Card  512GB                      | 13        | 9.22%   |
| Phison NVMe SSD Drive 512GB                  | 10        | 7.09%   |
| Unknown                                      | 10        | 7.09%   |
| Kingston NVMe SSD Drive 256GB                | 9         | 6.38%   |
| O2 Micro NVMe SSD Drive 64GB                 | 8         | 5.67%   |
| Phison NVMe SSD Drive 256GB                  | 7         | 4.96%   |
| Unknown MMC Card  64GB                       | 3         | 2.13%   |
| Unknown MMC Card  256GB                      | 3         | 2.13%   |
| Unknown MMC Card  128GB                      | 3         | 2.13%   |
| Silicon Motion NVMe SSD Drive 256GB          | 3         | 2.13%   |
| Samsung NVMe SSD Drive 512GB                 | 3         | 2.13%   |
| Unknown MMC Card  393GB                      | 2         | 1.42%   |
| SK hynix NVMe SSD Drive 256GB                | 2         | 1.42%   |
| Samsung SSD 860 EVO 250GB                    | 2         | 1.42%   |
| Samsung NVMe SSD Drive 1TB                   | 2         | 1.42%   |
| WDC WD7500BPVT-80HXZT3 752GB                 | 1         | 0.71%   |
| WDC WD5000BPKT-60PK4T0 500GB                 | 1         | 0.71%   |
| WDC WD10SPZX-75Z10T2 1TB                     | 1         | 0.71%   |
| WDC WD10EURX-83UY4Y0 1TB                     | 1         | 0.71%   |
| WDC CH SN530 SDBPTPZ-1T00-1024 930GB         | 1         | 0.71%   |
| Unknown MMC Card  7GB                        | 1         | 0.71%   |
| Unknown MMC Card  498GB                      | 1         | 0.71%   |
| Unknown MMC Card  32GB                       | 1         | 0.71%   |
| Unknown MMC Card  248GB                      | 1         | 0.71%   |
| Unknown MMC Card  1TB                        | 1         | 0.71%   |
| Unknown MMC Card  196GB                      | 1         | 0.71%   |
| Unknown MMC Card  1048GB                     | 1         | 0.71%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 0.71%   |
| Toshiba MQ01ABD100 1TB                       | 1         | 0.71%   |
| Toshiba MK3275GSX 320GB                      | 1         | 0.71%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD          | 1         | 0.71%   |
| Solid State Storage NVMe SSD Drive 128GB     | 1         | 0.71%   |
| Seagate ST9320325AS 320GB                    | 1         | 0.71%   |
| Seagate ST6000DM003-2CY186 6TB               | 1         | 0.71%   |
| Seagate ST4000DM004-2CV104 4TB               | 1         | 0.71%   |
| Seagate ST3500413AS 500GB                    | 1         | 0.71%   |
| Seagate ST3160318AS 160GB                    | 1         | 0.71%   |
| Seagate ST2000DM008-2FR102 2TB               | 1         | 0.71%   |
| SanDisk NVMe SSD Drive 512GB                 | 1         | 0.71%   |
| Samsung SSD 870 QVO 2TB                      | 1         | 0.71%   |
| Samsung SSD 860 EVO 500GB                    | 1         | 0.71%   |
| Samsung SSD 850 EVO mSATA 500GB              | 1         | 0.71%   |
| Samsung SSD 850 EVO 250GB                    | 1         | 0.71%   |
| Samsung SSD 840 EVO 250GB                    | 1         | 0.71%   |
| Samsung NVMe SSD Drive 1024GB                | 1         | 0.71%   |
| PNY CS1311 240GB SSD                         | 1         | 0.71%   |
| PNY CS1211 240GB SSD 754D117-820             | 1         | 0.71%   |
| Phison NVMe SSD Drive 250GB                  | 1         | 0.71%   |
| Phison NVMe SSD Drive 128GB                  | 1         | 0.71%   |
| Phison NVMe SSD Drive 1024GB                 | 1         | 0.71%   |
| Lexar 25 6GB SSD                             | 1         | 0.71%   |
| Kingston SA400S37480G 480GB SSD              | 1         | 0.71%   |
| Kingston SA400M8240G 240GB SSD               | 1         | 0.71%   |
| JMicron Generic 2TB                          | 1         | 0.71%   |
| Intel SSDPEKNW512G8 512GB                    | 1         | 0.71%   |
| HP Phison PSSBN032GA27MC1 32GB               | 1         | 0.71%   |
| External USB3.0 120GB                        | 1         | 0.71%   |
| Crucial CT525MX300SSD1 528GB                 | 1         | 0.71%   |
| ASMT ASM1156-PM 3TB                          | 1         | 0.71%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Computers | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 4         | 6      | 40%     |
| WDC                | 3         | 4      | 30%     |
| Toshiba            | 1         | 2      | 10%     |
| JMicron Technology | 1         | 1      | 10%     |
| ASMT               | 1         | 1      | 10%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 7      | 42.86%  |
| PNY                 | 2         | 2      | 14.29%  |
| Kingston            | 2         | 2      | 14.29%  |
| Lexar 25            | 1         | 1      | 7.14%   |
| HP Phison           | 1         | 1      | 7.14%   |
| Crucial             | 1         | 1      | 7.14%   |
| A-DATA Technology   | 1         | 1      | 7.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 70        | 76     | 54.26%  |
| MMC  | 39        | 42     | 30.23%  |
| SSD  | 12        | 15     | 9.3%    |
| HDD  | 8         | 14     | 6.2%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 70        | 74     | 55.12%  |
| MMC  | 39        | 42     | 30.71%  |
| SATA | 14        | 26     | 11.02%  |
| SAS  | 4         | 5      | 3.15%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 12        | 18     | 54.55%  |
| 0.51-1.0   | 4         | 5      | 18.18%  |
| 1.01-2.0   | 3         | 3      | 13.64%  |
| 3.01-4.0   | 1         | 1      | 4.55%   |
| 2.01-3.0   | 1         | 1      | 4.55%   |
| 4.01-10.0  | 1         | 1      | 4.55%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 29        | 38.67%  |
| 101-250        | 26        | 34.67%  |
| 501-1000       | 8         | 10.67%  |
| 51-100         | 7         | 9.33%   |
| 1001-2000      | 3         | 4%      |
| More than 3000 | 1         | 1.33%   |
| 21-50          | 1         | 1.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 28        | 36.36%  |
| 21-50          | 13        | 16.88%  |
| 1-20           | 13        | 16.88%  |
| 251-500        | 12        | 15.58%  |
| 51-100         | 7         | 9.09%   |
| 501-1000       | 3         | 3.9%    |
| More than 3000 | 1         | 1.3%    |

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
| Detected | 74        | 144    | 97.37%  |
| Works    | 2         | 3      | 2.63%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Kingston Technology Company    | 24        | 27.91%  |
| Phison Electronics             | 20        | 23.26%  |
| Intel                          | 9         | 10.47%  |
| O2 Micro                       | 8         | 9.3%    |
| AMD                            | 8         | 9.3%    |
| Samsung Electronics            | 6         | 6.98%   |
| Silicon Motion                 | 3         | 3.49%   |
| SK hynix                       | 2         | 2.33%   |
| SanDisk                        | 2         | 2.33%   |
| Union Memory (Shenzhen)        | 1         | 1.16%   |
| Toshiba America Info Systems   | 1         | 1.16%   |
| Solid State Storage Technology | 1         | 1.16%   |
| ADATA Technology               | 1         | 1.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Kingston Company OM3PDP3 NVMe SSD                                             | 23        | 26.44%  |
| Phison PS5013 E13 NVMe Controller                                             | 18        | 20.69%  |
| O2 Micro Non-Volatile memory controller                                       | 8         | 9.2%    |
| AMD FCH SATA Controller [AHCI mode]                                           | 6         | 6.9%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                               | 3         | 3.45%   |
| Samsung NVMe SSD Controller 980                                               | 3         | 3.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 2         | 2.3%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 2         | 2.3%    |
| AMD 500 Series Chipset SATA Controller                                        | 2         | 2.3%    |
| Union Memory (Shenzhen) Non-Volatile memory controller                        | 1         | 1.15%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                          | 1         | 1.15%   |
| Solid State Storage Non-Volatile memory controller                            | 1         | 1.15%   |
| SK hynix Non-Volatile memory controller                                       | 1         | 1.15%   |
| SK hynix Gold P31 SSD                                                         | 1         | 1.15%   |
| SanDisk PC SN530 NVMe SSD                                                     | 1         | 1.15%   |
| SanDisk Non-Volatile memory controller                                        | 1         | 1.15%   |
| Samsung NVMe SSD Controller SM951/PM951                                       | 1         | 1.15%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 1         | 1.15%   |
| Phison Electronics Non-Volatile memory controller                             | 1         | 1.15%   |
| Phison E12 NVMe Controller                                                    | 1         | 1.15%   |
| Kingston Company Company Non-Volatile memory controller                       | 1         | 1.15%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 1         | 1.15%   |
| Intel SSD 660P Series                                                         | 1         | 1.15%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1         | 1.15%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 1         | 1.15%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 1         | 1.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 1         | 1.15%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                          | 1         | 1.15%   |
| ADATA Non-Volatile memory controller                                          | 1         | 1.15%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 70        | 81.4%   |
| SATA | 15        | 17.44%  |
| RAID | 1         | 1.16%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| AMD    | 64        | 85.33%  |
| Intel  | 11        | 14.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Custom APU 0405                           | 56        | 74.67%  |
| AMD Ryzen 9 3900X 12-Core Processor           | 2         | 2.67%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.33%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1         | 1.33%   |
| Intel Core i7-4578U CPU @ 3.00GHz             | 1         | 1.33%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 1.33%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 1         | 1.33%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 1.33%   |
| Intel Core i5-8500T CPU @ 2.10GHz             | 1         | 1.33%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 1         | 1.33%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 1         | 1.33%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 1.33%   |
| Intel 11th Gen Core i5-11400F @ 2.60GHz       | 1         | 1.33%   |
| AMD Ryzen 7 4800U with Radeon Graphics        | 1         | 1.33%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 1         | 1.33%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 1         | 1.33%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 1         | 1.33%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 1.33%   |
| AMD Embedded G-Series GX-420GI Radeon R7E     | 1         | 1.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Computers | Percent |
|---------------|-----------|---------|
| Other         | 58        | 77.33%  |
| Intel Core i7 | 4         | 5.33%   |
| Intel Core i5 | 4         | 5.33%   |
| AMD Ryzen 5   | 3         | 4%      |
| AMD Ryzen 9   | 2         | 2.67%   |
| AMD Ryzen 7   | 2         | 2.67%   |
| Intel Atom    | 1         | 1.33%   |
| AMD Embedded  | 1         | 1.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 62        | 82.67%  |
| 6      | 5         | 6.67%   |
| 8      | 3         | 4%      |
| 2      | 3         | 4%      |
| 12     | 2         | 2.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 75        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 70        | 93.33%  |
| 1      | 5         | 6.67%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 75        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 73        | 97.33%  |
| 0x08900201 | 1         | 1.33%   |
| 0x08600106 | 1         | 1.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 57        | 76%     |
| Zen 2       | 5         | 6.67%   |
| KabyLake    | 4         | 5.33%   |
| Zen+        | 1         | 1.33%   |
| Zen 3       | 1         | 1.33%   |
| TigerLake   | 1         | 1.33%   |
| Skylake     | 1         | 1.33%   |
| Silvermont  | 1         | 1.33%   |
| SandyBridge | 1         | 1.33%   |
| Haswell     | 1         | 1.33%   |
| Excavator   | 1         | 1.33%   |
| CometLake   | 1         | 1.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| AMD    | 68        | 82.93%  |
| Intel  | 8         | 9.76%   |
| Nvidia | 6         | 7.32%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 56        | 68.29%  |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 2.44%   |
| AMD Renoir                                                                               | 2         | 2.44%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 2         | 2.44%   |
| Nvidia TU117M                                                                            | 1         | 1.22%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1         | 1.22%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 1.22%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 1.22%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 1.22%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1.22%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 1.22%   |
| Intel HD Graphics 620                                                                    | 1         | 1.22%   |
| Intel HD Graphics 530                                                                    | 1         | 1.22%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.22%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.22%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.22%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 1.22%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 1.22%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 1         | 1.22%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 1         | 1.22%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 1         | 1.22%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1         | 1.22%   |
| AMD Cezanne                                                                              | 1         | 1.22%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                                       | 1         | 1.22%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 67        | 89.33%  |
| Intel + Nvidia | 3         | 4%      |
| 1 x Nvidia     | 2         | 2.67%   |
| 1 x Intel      | 2         | 2.67%   |
| AMD + Nvidia   | 1         | 1.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 70        | 93.33%  |
| Proprietary | 5         | 6.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 71        | 94.67%  |
| 5.01-6.0   | 2         | 2.67%   |
| 0.51-1.0   | 1         | 1.33%   |
| 0.01-0.5   | 1         | 1.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| ANX                  | 54        | 60.67%  |
| Samsung Electronics  | 5         | 5.62%   |
| Goldstar             | 4         | 4.49%   |
| Philips              | 3         | 3.37%   |
| BOE                  | 3         | 3.37%   |
| AU Optronics         | 3         | 3.37%   |
| Acer                 | 2         | 2.25%   |
| ___                  | 1         | 1.12%   |
| ZSC                  | 1         | 1.12%   |
| YTH                  | 1         | 1.12%   |
| ViewSonic            | 1         | 1.12%   |
| Unknown              | 1         | 1.12%   |
| TCL                  | 1         | 1.12%   |
| Sceptre Tech         | 1         | 1.12%   |
| MSI                  | 1         | 1.12%   |
| Microsoft            | 1         | 1.12%   |
| Hewlett-Packard      | 1         | 1.12%   |
| EXP                  | 1         | 1.12%   |
| Denver               | 1         | 1.12%   |
| Dell                 | 1         | 1.12%   |
| AOC                  | 1         | 1.12%   |
| Ancor Communications | 1         | 1.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| ANX ANX7530 U ANX7539 800x1280                                         | 54        | 60%     |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                 | 2         | 2.22%   |
| ___ LCDTV16 ___9000 1360x768                                           | 1         | 1.11%   |
| ZSC FHD HDR ZSCBC32 1920x1080 344x195mm 15.6-inch                      | 1         | 1.11%   |
| YTH HS133PC YTH1330 1920x1080 255x220mm 13.3-inch                      | 1         | 1.11%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch             | 1         | 1.11%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                     | 1         | 1.11%   |
| TCL SMART TV TCL6586 3840x2160 1209x680mm 54.6-inch                    | 1         | 1.11%   |
| Sceptre Tech E22 SPT08D5 1920x1080 409x230mm 18.5-inch                 | 1         | 1.11%   |
| Samsung Electronics T24C300 SAM0A9B 1920x1080 531x299mm 24.0-inch      | 1         | 1.11%   |
| Samsung Electronics SMB2330 SAM0643 1920x1080 510x287mm 23.0-inch      | 1         | 1.11%   |
| Samsung Electronics S27HG5x SAM0E10 2560x1440 598x336mm 27.0-inch      | 1         | 1.11%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch  | 1         | 1.11%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch    | 1         | 1.11%   |
| Philips PHL 345B1C PHL093D 3440x1440 797x334mm 34.0-inch               | 1         | 1.11%   |
| Philips PHL 326M6V PHLC193 3840x2160 698x398mm 31.6-inch               | 1         | 1.11%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 1         | 1.11%   |
| MSI MPG321QRF-QD MSI3DB8 2560x1440 708x399mm 32.0-inch                 | 1         | 1.11%   |
| Microsoft Xbox One MSH0001 1920x1080 1210x680mm 54.6-inch              | 1         | 1.11%   |
| Hewlett-Packard 25x HPN357F 1920x1080 544x303mm 24.5-inch              | 1         | 1.11%   |
| Goldstar ULTRAWIDE GSM5AFB 2560x1080 798x334mm 34.1-inch               | 1         | 1.11%   |
| Goldstar LG ULTRAGEAR GSM775B 1920x1080 700x390mm 31.5-inch            | 1         | 1.11%   |
| Goldstar 27GN7 GSM5B8D 1920x1080 610x360mm 27.9-inch                   | 1         | 1.11%   |
| EXP EPDP17.1127 EXP9632 1920x1080 1150x650mm 52.0-inch                 | 1         | 1.11%   |
| Denver 274K144IGHUCA LHC2700 3840x2160 597x336mm 27.0-inch             | 1         | 1.11%   |
| Dell U2715H DELD069 2560x1440 597x336mm 27.0-inch                      | 1         | 1.11%   |
| BOE LCD Monitor BOE094D 1920x1080 344x194mm 15.5-inch                  | 1         | 1.11%   |
| BOE LCD Monitor BOE0852 1920x1080 344x194mm 15.5-inch                  | 1         | 1.11%   |
| BOE LCD Monitor BOE065F 1920x1080 344x194mm 15.5-inch                  | 1         | 1.11%   |
| AU Optronics LCD Monitor AUOED8F 1920x1080 344x193mm 15.5-inch         | 1         | 1.11%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch          | 1         | 1.11%   |
| AU Optronics LCD Monitor AUO18D4 1280x800 216x135mm 10.0-inch          | 1         | 1.11%   |
| AOC AG352UCG6 AOC3525 3440x1440 819x346mm 35.0-inch                    | 1         | 1.11%   |
| Ancor Communications ASUS VH242H ACI24F3 1920x1080 521x293mm 23.5-inch | 1         | 1.11%   |
| Acer VG240Y S ACR0750 1920x1080 527x296mm 23.8-inch                    | 1         | 1.11%   |
| Acer H236HL ACR0318 1920x1080 509x286mm 23.0-inch                      | 1         | 1.11%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 800x1280         | 54        | 60.67%  |
| 1920x1080 (FHD)  | 18        | 20.22%  |
| 3840x2160 (4K)   | 5         | 5.62%   |
| 2560x1440 (QHD)  | 4         | 4.49%   |
| 3440x1440        | 2         | 2.25%   |
| 3840x1080        | 1         | 1.12%   |
| 2560x1080        | 1         | 1.12%   |
| 1440x900 (WXGA+) | 1         | 1.12%   |
| 1366x768 (WXGA)  | 1         | 1.12%   |
| 1360x768         | 1         | 1.12%   |
| 1280x800 (WXGA)  | 1         | 1.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 55        | 62.5%   |
| 15      | 7         | 7.95%   |
| 27      | 4         | 4.55%   |
| 72      | 3         | 3.41%   |
| 31      | 3         | 3.41%   |
| 24      | 3         | 3.41%   |
| 23      | 3         | 3.41%   |
| 34      | 2         | 2.27%   |
| 54      | 1         | 1.14%   |
| 52      | 1         | 1.14%   |
| 48      | 1         | 1.14%   |
| 35      | 1         | 1.14%   |
| 32      | 1         | 1.14%   |
| 21      | 1         | 1.14%   |
| 13      | 1         | 1.14%   |
| 10      | 1         | 1.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 55        | 62.5%   |
| 501-600     | 9         | 10.23%  |
| 301-350     | 7         | 7.95%   |
| 601-700     | 4         | 4.55%   |
| 701-800     | 3         | 3.41%   |
| 1501-2000   | 3         | 3.41%   |
| 1001-1500   | 3         | 3.41%   |
| 201-300     | 2         | 2.27%   |
| 801-900     | 1         | 1.14%   |
| 401-500     | 1         | 1.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 0.62  | 54        | 62.79%  |
| 16/9  | 27        | 31.4%   |
| 21/9  | 3         | 3.49%   |
| 32/9  | 1         | 1.16%   |
| 16/10 | 1         | 1.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 55        | 62.5%   |
| 351-500        | 7         | 7.95%   |
| 101-110        | 7         | 7.95%   |
| 201-250        | 6         | 6.82%   |
| More than 1000 | 5         | 5.68%   |
| 301-350        | 4         | 4.55%   |
| 71-80          | 1         | 1.14%   |
| 41-50          | 1         | 1.14%   |
| 251-300        | 1         | 1.14%   |
| 501-1000       | 1         | 1.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| Unknown | 55        | 62.5%   |
| 51-100  | 14        | 15.91%  |
| 121-160 | 8         | 9.09%   |
| 101-120 | 7         | 7.95%   |
| 1-50    | 3         | 3.41%   |
| 161-240 | 1         | 1.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 61        | 81.33%  |
| 2     | 13        | 17.33%  |
| 3     | 1         | 1.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 65        | 71.43%  |
| Intel                         | 11        | 12.09%  |
| ASIX Electronics              | 4         | 4.4%    |
| Qualcomm Atheros              | 2         | 2.2%    |
| Microsoft                     | 2         | 2.2%    |
| OnePlus Technology (Shenzhen) | 1         | 1.1%    |
| MediaTek                      | 1         | 1.1%    |
| Google                        | 1         | 1.1%    |
| DisplayLink                   | 1         | 1.1%    |
| Broadcom Limited              | 1         | 1.1%    |
| Broadcom                      | 1         | 1.1%    |
| AVM                           | 1         | 1.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 56        | 53.85%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 6.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 5.77%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 4.81%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 3.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 1.92%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.92%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.92%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.96%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.96%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.96%   |
| Realtek 802.11ac NIC                                              | 1         | 0.96%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.96%   |
| OnePlus (Shenzhen) SM8150-MTP _SN:63F1CF71                        | 1         | 0.96%   |
| Microsoft XBOX ACC                                                | 1         | 0.96%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1         | 0.96%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1         | 0.96%   |
| Intel Wireless 8260                                               | 1         | 0.96%   |
| Intel Wireless 7265                                               | 1         | 0.96%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 0.96%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.96%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 0.96%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 0.96%   |
| DisplayLink USB-C Dual-4K Dock                                    | 1         | 0.96%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 0.96%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 1         | 0.96%   |
| AVM FRITZ!WLAN AC 860                                             | 1         | 0.96%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 59        | 78.67%  |
| Intel                 | 9         | 12%     |
| Qualcomm Atheros      | 2         | 2.67%   |
| Microsoft             | 2         | 2.67%   |
| MediaTek              | 1         | 1.33%   |
| Broadcom Limited      | 1         | 1.33%   |
| AVM                   | 1         | 1.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 56        | 74.67%  |
| Intel Wi-Fi 6 AX200                                        | 5         | 6.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 2         | 2.67%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter   | 1         | 1.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1         | 1.33%   |
| Realtek 802.11ac NIC                                       | 1         | 1.33%   |
| Microsoft XBOX ACC                                         | 1         | 1.33%   |
| Microsoft Xbox 360 Wireless Adapter                        | 1         | 1.33%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                    | 1         | 1.33%   |
| Intel Wireless 8260                                        | 1         | 1.33%   |
| Intel Wireless 7265                                        | 1         | 1.33%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 1         | 1.33%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1         | 1.33%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter | 1         | 1.33%   |
| AVM FRITZ!WLAN AC 860                                      | 1         | 1.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 14        | 50%     |
| Intel                         | 5         | 17.86%  |
| ASIX Electronics              | 4         | 14.29%  |
| Qualcomm Atheros              | 1         | 3.57%   |
| OnePlus Technology (Shenzhen) | 1         | 3.57%   |
| Google                        | 1         | 3.57%   |
| DisplayLink                   | 1         | 3.57%   |
| Broadcom                      | 1         | 3.57%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 24.14%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 20.69%  |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 13.79%  |
| Intel Ethernet Controller I225-V                                  | 2         | 6.9%    |
| Intel Ethernet Connection (2) I219-V                              | 2         | 6.9%    |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 3.45%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 3.45%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 3.45%   |
| OnePlus (Shenzhen) SM8150-MTP _SN:63F1CF71                        | 1         | 3.45%   |
| Intel I211 Gigabit Network Connection                             | 1         | 3.45%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 3.45%   |
| DisplayLink USB-C Dual-4K Dock                                    | 1         | 3.45%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 3.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 73        | 73.74%  |
| Ethernet | 26        | 26.26%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 64        | 80%     |
| Ethernet | 16        | 20%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 63        | 84%     |
| 2     | 12        | 16%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 51        | 67.11%  |
| Yes  | 25        | 32.89%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| IMC Networks                    | 56        | 81.16%  |
| Intel                           | 8         | 11.59%  |
| Realtek Semiconductor           | 2         | 2.9%    |
| Qualcomm Atheros Communications | 1         | 1.45%   |
| Lite-On Technology              | 1         | 1.45%   |
| Apple                           | 1         | 1.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| IMC Networks Bluetooth Radio               | 56        | 81.16%  |
| Intel AX200 Bluetooth                      | 4         | 5.8%    |
| Intel Bluetooth wireless interface         | 2         | 2.9%    |
| Realtek  Bluetooth 4.2 Adapter             | 1         | 1.45%   |
| Realtek Bluetooth Radio                    | 1         | 1.45%   |
| Qualcomm Atheros  Bluetooth Device         | 1         | 1.45%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth | 1         | 1.45%   |
| Intel Bluetooth Device                     | 1         | 1.45%   |
| Intel AX210 Bluetooth                      | 1         | 1.45%   |
| Apple Bluetooth Host Controller            | 1         | 1.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| AMD                         | 69        | 73.4%   |
| Intel                       | 10        | 10.64%  |
| Nvidia                      | 6         | 6.38%   |
| Kingston Technology         | 2         | 2.13%   |
| C-Media Electronics         | 2         | 2.13%   |
| Tenx Technology             | 1         | 1.06%   |
| Logitech                    | 1         | 1.06%   |
| FiiO Electronics Technology | 1         | 1.06%   |
| Blue Microphones            | 1         | 1.06%   |
| Apple                       | 1         | 1.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Rembrandt Radeon High Definition Audio Controller                      | 56        | 56%     |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 4%      |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 3%      |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3         | 3%      |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 2%      |
| Intel 200 Series PCH HD Audio                                              | 2         | 2%      |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 2%      |
| Tenx Technology USB AUDIO                                                  | 1         | 1%      |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1%      |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1%      |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 1%      |
| Nvidia Audio device                                                        | 1         | 1%      |
| Logitech Blue Microphones                                                  | 1         | 1%      |
| Kingston Technology HyperX Quadcast                                        | 1         | 1%      |
| Kingston Technology HyperX Cloud Alpha S                                   | 1         | 1%      |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 1%      |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1%      |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 1%      |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1%      |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 1%      |
| Intel 8 Series HD Audio Controller                                         | 1         | 1%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 1%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1%      |
| FiiO Electronics Technology K3                                             | 1         | 1%      |
| C-Media Electronics Blue Snowball                                          | 1         | 1%      |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1         | 1%      |
| Blue Microphones Yeti Stereo Microphone                                    | 1         | 1%      |
| Apple USB-C to 3.5mm Headphone Jack Adapter                                | 1         | 1%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1%      |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 1%      |
| AMD Navi 10 HDMI Audio                                                     | 1         | 1%      |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1%      |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 1%      |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1         | 1%      |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1         | 1%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Crucial | 1         | 50%     |
| Unknown | 1         | 50%     |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Crucial RAM CT8G4SFS832A.C8FR 8GB SODIMM DDR4 3200MT/s | 1         | 50%     |
| Unknown                                                | 1         | 50%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1         | 50%     |
| Unknown | 1         | 50%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 2         | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Computers | Percent |
|------|-----------|---------|
| 8192 | 1         | 50%     |
| 4096 | 1         | 50%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 4266  | 1         | 50%     |
| 3200  | 1         | 50%     |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| HP Laserjet CP1525nw | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 210 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2         | 18.18%  |
| Quanta                                 | 2         | 18.18%  |
| Unknown                                | 1         | 9.09%   |
| Sunplus Innovation Technology          | 1         | 9.09%   |
| Magic Control Technology               | 1         | 9.09%   |
| Luxvisions Innotech Limited            | 1         | 9.09%   |
| Logitech                               | 1         | 9.09%   |
| Chicony Electronics                    | 1         | 9.09%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 9.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Unknown 720p HD Camera                                  | 1         | 9.09%   |
| Sunplus USB 2.0 Camera                                  | 1         | 9.09%   |
| Realtek WEB CAMERA M9 Pro                               | 1         | 9.09%   |
| Realtek Integrated_Webcam_HD                            | 1         | 9.09%   |
| Quanta VGA WebCam                                       | 1         | 9.09%   |
| Quanta HP Wide Vision HD Camera                         | 1         | 9.09%   |
| Magic Control j5 WebCam JVCU100                         | 1         | 9.09%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 1         | 9.09%   |
| Logitech CrystalCam                                     | 1         | 9.09%   |
| Chicony USB2.0 HD UVC WebCam                            | 1         | 9.09%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 1         | 9.09%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

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

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 67        | 89.33%  |
| 1     | 7         | 9.33%   |
| 2     | 1         | 1.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 4         | 44.44%  |
| Multimedia controller | 3         | 33.33%  |
| Net/ethernet          | 1         | 11.11%  |
| Graphics card         | 1         | 11.11%  |

