UbuntuDDE - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for UbuntuDDE.

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

Total: 63

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Samsung   | 355V4C/356V4C/3445VC/354... | [65a009e9dd](https://linux-hardware.org/?probe=65a009e9dd) | Apr 20, 2023 |
| Dell      | Latitude E6430              | [7fe3f11f56](https://linux-hardware.org/?probe=7fe3f11f56) | Dec 22, 2022 |
| Dell      | Latitude E6430              | [60832751d1](https://linux-hardware.org/?probe=60832751d1) | Nov 16, 2022 |
| HP        | Notebook                    | [9c04c0776d](https://linux-hardware.org/?probe=9c04c0776d) | Mar 10, 2022 |
| Dell      | Inspiron N4030              | [ac4c492fcf](https://linux-hardware.org/?probe=ac4c492fcf) | Mar 05, 2022 |
| Dell      | Inspiron N4030              | [e5e17e5138](https://linux-hardware.org/?probe=e5e17e5138) | Mar 05, 2022 |
| HP        | ProBook 650 G3              | [32fcb78172](https://linux-hardware.org/?probe=32fcb78172) | Jan 23, 2022 |
| Framework | Laptop                      | [081416685c](https://linux-hardware.org/?probe=081416685c) | Jan 18, 2022 |
| Dell      | XPS 15 9570                 | [b8d4a9ee87](https://linux-hardware.org/?probe=b8d4a9ee87) | Jan 17, 2022 |
| Google    | Banon                       | [a6febddf28](https://linux-hardware.org/?probe=a6febddf28) | Jan 06, 2022 |
| ASUSTek   | G550JK                      | [b26b378274](https://linux-hardware.org/?probe=b26b378274) | Jan 01, 2022 |
| ASUSTek   | VivoBook_ASUSLaptop X421... | [b2a9183e6d](https://linux-hardware.org/?probe=b2a9183e6d) | Oct 09, 2021 |
| Lenovo    | IdeaPad 510-15IKB 80SV      | [71958172cf](https://linux-hardware.org/?probe=71958172cf) | Oct 08, 2021 |
| Dell      | XPS 15 9570                 | [661937dcfa](https://linux-hardware.org/?probe=661937dcfa) | Sep 12, 2021 |
| Dell      | XPS 15 9570                 | [a950c391ee](https://linux-hardware.org/?probe=a950c391ee) | Sep 12, 2021 |
| Lenovo    | ThinkPad E15 Gen 2 20TDS... | [f3199bc88b](https://linux-hardware.org/?probe=f3199bc88b) | Jul 25, 2021 |
| MSI       | GS60 2QE                    | [7ef8c79c08](https://linux-hardware.org/?probe=7ef8c79c08) | May 24, 2021 |
| MSI       | GS60 2QE                    | [1660ac34ec](https://linux-hardware.org/?probe=1660ac34ec) | May 24, 2021 |
| Acer      | Predator PH317-52           | [5737732bb0](https://linux-hardware.org/?probe=5737732bb0) | May 15, 2021 |
| HP        | OMEN by Laptop 17-cb1xxx    | [ca2397cddf](https://linux-hardware.org/?probe=ca2397cddf) | May 12, 2021 |
| HP        | EliteBook 2540p             | [506fb4d003](https://linux-hardware.org/?probe=506fb4d003) | May 02, 2021 |
| ASUSTek   | S551LN                      | [1c51e0899d](https://linux-hardware.org/?probe=1c51e0899d) | Apr 06, 2021 |
| ASUSTek   | S551LN                      | [d03bb12703](https://linux-hardware.org/?probe=d03bb12703) | Apr 06, 2021 |
| Dell      | Latitude E6320              | [8e7c6ced02](https://linux-hardware.org/?probe=8e7c6ced02) | Dec 15, 2020 |
| ASUSTek   | VivoBook 15_ASUS Laptop ... | [e070ae2fd4](https://linux-hardware.org/?probe=e070ae2fd4) | Oct 19, 2020 |
| ASUSTek   | X555QG                      | [ae5665efc4](https://linux-hardware.org/?probe=ae5665efc4) | Oct 02, 2020 |
| Dell      | Inspiron 5447               | [a316ca39ef](https://linux-hardware.org/?probe=a316ca39ef) | Sep 25, 2020 |
| HP        | Pavilion dm4                | [7ab3fbd60d](https://linux-hardware.org/?probe=7ab3fbd60d) | Aug 26, 2020 |
| HP        | Pavilion dm4                | [f3f1ea6d44](https://linux-hardware.org/?probe=f3f1ea6d44) | Aug 26, 2020 |
| HUAWEI    | MACH-WX9                    | [b7c774660b](https://linux-hardware.org/?probe=b7c774660b) | Aug 23, 2020 |
| HUAWEI    | MACH-WX9                    | [08bdddfbb1](https://linux-hardware.org/?probe=08bdddfbb1) | Aug 23, 2020 |
| Dell      | System XPS L502X            | [caa5473285](https://linux-hardware.org/?probe=caa5473285) | Aug 13, 2020 |
| Lenovo    | G480 20150                  | [4531dd50a5](https://linux-hardware.org/?probe=4531dd50a5) | Aug 11, 2020 |
| Lenovo    | G480 20150                  | [8e51b2cb2d](https://linux-hardware.org/?probe=8e51b2cb2d) | Aug 11, 2020 |
| Dell      | System XPS L502X            | [019fc71c57](https://linux-hardware.org/?probe=019fc71c57) | Aug 05, 2020 |
| ASUSTek   | TP300LA                     | [4cb4390fa3](https://linux-hardware.org/?probe=4cb4390fa3) | Aug 01, 2020 |
| ASUSTek   | TP300LA                     | [e273444401](https://linux-hardware.org/?probe=e273444401) | Aug 01, 2020 |
| Acer      | Aspire 5750                 | [19876e9920](https://linux-hardware.org/?probe=19876e9920) | Jul 25, 2020 |
| Dell      | G7 7588                     | [34805cf5b8](https://linux-hardware.org/?probe=34805cf5b8) | Jul 24, 2020 |
| Toshiba   | Satellite S55t-B            | [01aa2bca69](https://linux-hardware.org/?probe=01aa2bca69) | Jun 28, 2020 |
| Toshiba   | Satellite S55t-B            | [71ae60ebc0](https://linux-hardware.org/?probe=71ae60ebc0) | Jun 27, 2020 |
| Lenovo    | IdeaPad 520-15IKB 81BF      | [2a82822b1d](https://linux-hardware.org/?probe=2a82822b1d) | Jun 24, 2020 |
| Lenovo    | IdeaPad 520-15IKB 81BF      | [9f58b08659](https://linux-hardware.org/?probe=9f58b08659) | Jun 24, 2020 |
| Dell      | Inspiron 1525               | [f01a10328b](https://linux-hardware.org/?probe=f01a10328b) | Jun 17, 2020 |
| HP        | Presario CQ56               | [211a5c9ec1](https://linux-hardware.org/?probe=211a5c9ec1) | Jun 17, 2020 |
| Acer      | Aspire V5-471               | [346de9f5d8](https://linux-hardware.org/?probe=346de9f5d8) | Jun 14, 2020 |
| Unknown   | Unknown                     | [1da538b1cf](https://linux-hardware.org/?probe=1da538b1cf) | Jun 04, 2020 |
| Unknown   | Unknown                     | [950be7ae19](https://linux-hardware.org/?probe=950be7ae19) | Jun 04, 2020 |
| Lenovo    | ThinkPad T430 2349DS5       | [77d17289e7](https://linux-hardware.org/?probe=77d17289e7) | May 31, 2020 |
| HP        | Laptop 15-dy1xxx            | [ea23c3bbdb](https://linux-hardware.org/?probe=ea23c3bbdb) | May 16, 2020 |
| HP        | Laptop 15-dy1xxx            | [d55c3ee4b0](https://linux-hardware.org/?probe=d55c3ee4b0) | May 16, 2020 |
| Acer      | Aspire 5733                 | [42424919ae](https://linux-hardware.org/?probe=42424919ae) | May 14, 2020 |
| HP        | 250 G4 Notebook PC          | [2406267563](https://linux-hardware.org/?probe=2406267563) | May 12, 2020 |
| HP        | 250 G4 Notebook PC          | [7e8fdf4b86](https://linux-hardware.org/?probe=7e8fdf4b86) | May 11, 2020 |
| Toshiba   | Satellite C55-B             | [2a1a979433](https://linux-hardware.org/?probe=2a1a979433) | May 11, 2020 |
| HP        | Pavilion 14                 | [f366f5c4e4](https://linux-hardware.org/?probe=f366f5c4e4) | May 11, 2020 |
| Lenovo    | G550 2958                   | [cfd6e82a6f](https://linux-hardware.org/?probe=cfd6e82a6f) | May 11, 2020 |
| Lenovo    | ThinkPad X200 Tablet 744... | [6c9138359f](https://linux-hardware.org/?probe=6c9138359f) | May 10, 2020 |
| Dell      | Inspiron N7010              | [2568ca0355](https://linux-hardware.org/?probe=2568ca0355) | May 07, 2020 |
| HP        | Pavilion dv6                | [46c69aad2a](https://linux-hardware.org/?probe=46c69aad2a) | Apr 30, 2020 |
| HP        | Laptop 15-da0xxx            | [1dc3e83e11](https://linux-hardware.org/?probe=1dc3e83e11) | Apr 18, 2020 |
| ASUSTek   | N750JK                      | [f38f6111a4](https://linux-hardware.org/?probe=f38f6111a4) | Apr 07, 2020 |
| Dell      | Latitude E5440              | [6c3cb81d00](https://linux-hardware.org/?probe=6c3cb81d00) | Aug 01, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| UbuntuDDE 20.04 | 31        | 68.89%  |
| UbuntuDDE 21.04 | 5         | 11.11%  |
| UbuntuDDE 21.10 | 4         | 8.89%   |
| UbuntuDDE 22.04 | 2         | 4.44%   |
| UbuntuDDE 20.10 | 2         | 4.44%   |
| UbuntuDDE 18.10 | 1         | 2.22%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| UbuntuDDE | 45        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 7         | 14.89%  |
| 5.4.0-29-generic  | 7         | 14.89%  |
| 5.4.0-37-generic  | 4         | 8.51%   |
| 5.4.0-48-generic  | 2         | 4.26%   |
| 5.4.0-21-generic  | 2         | 4.26%   |
| 5.11.0-17-generic | 2         | 4.26%   |
| 5.8.0-33-generic  | 1         | 2.13%   |
| 5.8.0-23-generic  | 1         | 2.13%   |
| 5.6.0-1008-oem    | 1         | 2.13%   |
| 5.4.0-96-generic  | 1         | 2.13%   |
| 5.4.0-94-generic  | 1         | 2.13%   |
| 5.4.0-88-generic  | 1         | 2.13%   |
| 5.4.0-84-generic  | 1         | 2.13%   |
| 5.4.0-70-generic  | 1         | 2.13%   |
| 5.4.0-52-generic  | 1         | 2.13%   |
| 5.4.0-39-generic  | 1         | 2.13%   |
| 5.4.0-34-generic  | 1         | 2.13%   |
| 5.4.0-33-generic  | 1         | 2.13%   |
| 5.19.0-38-generic | 1         | 2.13%   |
| 5.15.0-57-generic | 1         | 2.13%   |
| 5.15.0-53-generic | 1         | 2.13%   |
| 5.13.0-30-generic | 1         | 2.13%   |
| 5.13.0-23-generic | 1         | 2.13%   |
| 5.13.0-22-generic | 1         | 2.13%   |
| 5.13.0-21-generic | 1         | 2.13%   |
| 5.11.0-46-generic | 1         | 2.13%   |
| 5.11.0-25-generic | 1         | 2.13%   |
| 5.11.0-16-generic | 1         | 2.13%   |
| 4.15.0-29-generic | 1         | 2.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 30        | 66.67%  |
| 5.11.0  | 5         | 11.11%  |
| 5.13.0  | 4         | 8.89%   |
| 5.8.0   | 2         | 4.44%   |
| 5.6.0   | 1         | 2.22%   |
| 5.19.0  | 1         | 2.22%   |
| 5.15.0  | 1         | 2.22%   |
| 4.15.0  | 1         | 2.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 30        | 66.67%  |
| 5.11    | 5         | 11.11%  |
| 5.13    | 4         | 8.89%   |
| 5.8     | 2         | 4.44%   |
| 5.6     | 1         | 2.22%   |
| 5.19    | 1         | 2.22%   |
| 5.15    | 1         | 2.22%   |
| 4.15    | 1         | 2.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 45        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Deepin | 45        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 43        | 95.56%  |
| Wayland | 2         | 4.44%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 25        | 54.35%  |
| LightDM | 10        | 21.74%  |
| GDM     | 8         | 17.39%  |
| TDM     | 1         | 2.17%   |
| SDDM    | 1         | 2.17%   |
| GDM3    | 1         | 2.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 11        | 24.44%  |
| pt_BR   | 6         | 13.33%  |
| es_ES   | 3         | 6.67%   |
| de_DE   | 3         | 6.67%   |
| C       | 3         | 6.67%   |
| ru_RU   | 2         | 4.44%   |
| fr_FR   | 2         | 4.44%   |
| es_AR   | 2         | 4.44%   |
| en_GB   | 2         | 4.44%   |
| sr_RS   | 1         | 2.22%   |
| nl_NL   | 1         | 2.22%   |
| it_IT   | 1         | 2.22%   |
| id_ID   | 1         | 2.22%   |
| es_MX   | 1         | 2.22%   |
| es_CO   | 1         | 2.22%   |
| en_ZA   | 1         | 2.22%   |
| en_IN   | 1         | 2.22%   |
| en_BW   | 1         | 2.22%   |
| en_AU   | 1         | 2.22%   |
| Unknown | 1         | 2.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 25        | 54.35%  |
| EFI  | 21        | 45.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 39        | 86.67%  |
| Overlay | 3         | 6.67%   |
| Zfs     | 1         | 2.22%   |
| Tmpfs   | 1         | 2.22%   |
| Ext2    | 1         | 2.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 28        | 62.22%  |
| GPT     | 15        | 33.33%  |
| MBR     | 2         | 4.44%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 38        | 84.44%  |
| Yes       | 7         | 15.56%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 55.56%  |
| No        | 20        | 44.44%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 11        | 24.44%  |
| Dell                | 10        | 22.22%  |
| Lenovo              | 6         | 13.33%  |
| ASUSTek Computer    | 6         | 13.33%  |
| Acer                | 4         | 8.89%   |
| Toshiba             | 2         | 4.44%   |
| Samsung Electronics | 1         | 2.22%   |
| MSI                 | 1         | 2.22%   |
| HUAWEI              | 1         | 2.22%   |
| Google              | 1         | 2.22%   |
| Framework           | 1         | 2.22%   |
| Unknown             | 1         | 2.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Toshiba Satellite S55t-B                | 1         | 2.22%   |
| Toshiba Satellite C55-B                 | 1         | 2.22%   |
| Samsung 355V4C/356V4C/3445VC/3545VC     | 1         | 2.22%   |
| MSI GS60 2QE                            | 1         | 2.22%   |
| Lenovo ThinkPad X200 Tablet 7449FWG     | 1         | 2.22%   |
| Lenovo ThinkPad T430 2349DS5            | 1         | 2.22%   |
| Lenovo ThinkPad E15 Gen 2 20TDS0A300    | 1         | 2.22%   |
| Lenovo IdeaPad 520-15IKB 81BF           | 1         | 2.22%   |
| Lenovo IdeaPad 510-15IKB 80SV           | 1         | 2.22%   |
| Lenovo G480 20150                       | 1         | 2.22%   |
| HUAWEI MACH-WX9                         | 1         | 2.22%   |
| HP ProBook 650 G3                       | 1         | 2.22%   |
| HP Presario CQ56                        | 1         | 2.22%   |
| HP Pavilion dv6                         | 1         | 2.22%   |
| HP Pavilion dm4                         | 1         | 2.22%   |
| HP Pavilion 14                          | 1         | 2.22%   |
| HP OMEN by Laptop 17-cb1xxx             | 1         | 2.22%   |
| HP Notebook                             | 1         | 2.22%   |
| HP Laptop 15-dy1xxx                     | 1         | 2.22%   |
| HP Laptop 15-da0xxx                     | 1         | 2.22%   |
| HP EliteBook 2540p                      | 1         | 2.22%   |
| HP 250 G4 Notebook PC                   | 1         | 2.22%   |
| Google Banon                            | 1         | 2.22%   |
| Framework Laptop                        | 1         | 2.22%   |
| Dell XPS 15 9570                        | 1         | 2.22%   |
| Dell System XPS L502X                   | 1         | 2.22%   |
| Dell Latitude E6430                     | 1         | 2.22%   |
| Dell Latitude E6320                     | 1         | 2.22%   |
| Dell Latitude E5440                     | 1         | 2.22%   |
| Dell Inspiron N7010                     | 1         | 2.22%   |
| Dell Inspiron N4030                     | 1         | 2.22%   |
| Dell Inspiron 5447                      | 1         | 2.22%   |
| Dell Inspiron 1525                      | 1         | 2.22%   |
| Dell G7 7588                            | 1         | 2.22%   |
| ASUS X555QG                             | 1         | 2.22%   |
| ASUS VivoBook_ASUSLaptop X421JAY_X413JA | 1         | 2.22%   |
| ASUS VivoBook 15_ASUS Laptop X560UD     | 1         | 2.22%   |
| ASUS TP300LA                            | 1         | 2.22%   |
| ASUS S551LN                             | 1         | 2.22%   |
| ASUS G550JK                             | 1         | 2.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Dell Inspiron     | 4         | 8.89%   |
| Lenovo ThinkPad   | 3         | 6.67%   |
| HP Pavilion       | 3         | 6.67%   |
| Dell Latitude     | 3         | 6.67%   |
| Acer Aspire       | 3         | 6.67%   |
| Toshiba Satellite | 2         | 4.44%   |
| Lenovo IdeaPad    | 2         | 4.44%   |
| HP Laptop         | 2         | 4.44%   |
| ASUS VivoBook     | 2         | 4.44%   |
| Samsung 355V4C    | 1         | 2.22%   |
| MSI GS60          | 1         | 2.22%   |
| Lenovo G480       | 1         | 2.22%   |
| HUAWEI MACH-WX9   | 1         | 2.22%   |
| HP ProBook        | 1         | 2.22%   |
| HP Presario       | 1         | 2.22%   |
| HP OMEN           | 1         | 2.22%   |
| HP Notebook       | 1         | 2.22%   |
| HP EliteBook      | 1         | 2.22%   |
| HP 250            | 1         | 2.22%   |
| Google Banon      | 1         | 2.22%   |
| Framework Laptop  | 1         | 2.22%   |
| Dell XPS          | 1         | 2.22%   |
| Dell System       | 1         | 2.22%   |
| Dell G7           | 1         | 2.22%   |
| ASUS X555QG       | 1         | 2.22%   |
| ASUS TP300LA      | 1         | 2.22%   |
| ASUS S551LN       | 1         | 2.22%   |
| ASUS G550JK       | 1         | 2.22%   |
| Acer Predator     | 1         | 2.22%   |
| Unknown           | 1         | 2.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2014 | 7         | 15.56%  |
| 2018 | 6         | 13.33%  |
| 2010 | 5         | 11.11%  |
| 2012 | 4         | 8.89%   |
| 2011 | 4         | 8.89%   |
| 2021 | 3         | 6.67%   |
| 2020 | 3         | 6.67%   |
| 2013 | 3         | 6.67%   |
| 2008 | 3         | 6.67%   |
| 2017 | 2         | 4.44%   |
| 2016 | 2         | 4.44%   |
| 2019 | 1         | 2.22%   |
| 2015 | 1         | 2.22%   |
| 2009 | 1         | 2.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 45        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 40        | 86.96%  |
| Enabled  | 6         | 13.04%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 44        | 97.78%  |
| Yes  | 1         | 2.22%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 14        | 31.11%  |
| 3.01-4.0   | 12        | 26.67%  |
| 16.01-24.0 | 9         | 20%     |
| 8.01-16.0  | 6         | 13.33%  |
| 32.01-64.0 | 2         | 4.44%   |
| 2.01-3.0   | 1         | 2.22%   |
| 1.01-2.0   | 1         | 2.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 19        | 40.43%  |
| 1.01-2.0  | 17        | 36.17%  |
| 4.01-8.0  | 5         | 10.64%  |
| 3.01-4.0  | 5         | 10.64%  |
| 8.01-16.0 | 1         | 2.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 32        | 71.11%  |
| 2      | 13        | 28.89%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 26        | 57.78%  |
| Yes       | 19        | 42.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 84.44%  |
| No        | 7         | 15.56%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 35        | 77.78%  |
| No        | 10        | 22.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| Brazil       | 8         | 17.39%  |
| USA          | 6         | 13.04%  |
| Germany      | 4         | 8.7%    |
| India        | 3         | 6.52%   |
| Ukraine      | 2         | 4.35%   |
| Spain        | 2         | 4.35%   |
| Hungary      | 2         | 4.35%   |
| France       | 2         | 4.35%   |
| Argentina    | 2         | 4.35%   |
| Thailand     | 1         | 2.17%   |
| South Africa | 1         | 2.17%   |
| Serbia       | 1         | 2.17%   |
| Portugal     | 1         | 2.17%   |
| Poland       | 1         | 2.17%   |
| Netherlands  | 1         | 2.17%   |
| Mexico       | 1         | 2.17%   |
| Jamaica      | 1         | 2.17%   |
| Indonesia    | 1         | 2.17%   |
| Hong Kong    | 1         | 2.17%   |
| Costa Rica   | 1         | 2.17%   |
| Colombia     | 1         | 2.17%   |
| Austria      | 1         | 2.17%   |
| Australia    | 1         | 2.17%   |
| Algeria      | 1         | 2.17%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Budapest                    | 2         | 4.35%   |
| Zaporizhzhia                | 1         | 2.17%   |
| Wolfheze                    | 1         | 2.17%   |
| Villahermosa                | 1         | 2.17%   |
| Vienna                      | 1         | 2.17%   |
| Tuen Mun                    | 1         | 2.17%   |
| Tiete                       | 1         | 2.17%   |
| Surabaya                    | 1         | 2.17%   |
| Siquirres                   | 1         | 2.17%   |
| Seville                     | 1         | 2.17%   |
| Sao Jose do Rio Preto       | 1         | 2.17%   |
| San Nicolás de los Arroyos | 1         | 2.17%   |
| Salvador                    | 1         | 2.17%   |
| Ratingen                    | 1         | 2.17%   |
| Quilmes                     | 1         | 2.17%   |
| Patna                       | 1         | 2.17%   |
| Paris                       | 1         | 2.17%   |
| Nanterre                    | 1         | 2.17%   |
| Nakhon Pathom               | 1         | 2.17%   |
| Midlothian                  | 1         | 2.17%   |
| Melbourne                   | 1         | 2.17%   |
| Manaus                      | 1         | 2.17%   |
| Maitland                    | 1         | 2.17%   |
| Luhansk                     | 1         | 2.17%   |
| Lisbon                      | 1         | 2.17%   |
| Krakow                      | 1         | 2.17%   |
| Kingston                    | 1         | 2.17%   |
| Johannesburg                | 1         | 2.17%   |
| Decatur                     | 1         | 2.17%   |
| Dearborn Heights            | 1         | 2.17%   |
| Charlottesville             | 1         | 2.17%   |
| Caxias                      | 1         | 2.17%   |
| Capim Grosso                | 1         | 2.17%   |
| Brooklyn                    | 1         | 2.17%   |
| Bonn                        | 1         | 2.17%   |
| Bogotá                     | 1         | 2.17%   |
| Bhopal                      | 1         | 2.17%   |
| Betim                       | 1         | 2.17%   |
| Berlin                      | 1         | 2.17%   |
| Belo Horizonte              | 1         | 2.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 13     | 21.43%  |
| Toshiba             | 8         | 8      | 14.29%  |
| WDC                 | 7         | 7      | 12.5%   |
| Samsung Electronics | 5         | 5      | 8.93%   |
| Micron Technology   | 3         | 3      | 5.36%   |
| Kingston            | 3         | 3      | 5.36%   |
| Crucial             | 3         | 3      | 5.36%   |
| Unknown             | 2         | 2      | 3.57%   |
| SanDisk             | 2         | 2      | 3.57%   |
| HGST                | 2         | 2      | 3.57%   |
| Fujitsu             | 2         | 2      | 3.57%   |
| XrayDisk            | 1         | 1      | 1.79%   |
| SK hynix            | 1         | 3      | 1.79%   |
| KingSpec            | 1         | 1      | 1.79%   |
| Intenso             | 1         | 1      | 1.79%   |
| Hitachi             | 1         | 1      | 1.79%   |
| China               | 1         | 1      | 1.79%   |
| A-DATA Technology   | 1         | 1      | 1.79%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB     | 3         | 5.26%   |
| Toshiba MQ01ABF050 500GB               | 2         | 3.51%   |
| Seagate ST9500325AS 500GB              | 2         | 3.51%   |
| Seagate ST2000LM007-1R8174 2TB         | 2         | 3.51%   |
| XrayDisk 240GB                         | 1         | 1.75%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 1         | 1.75%   |
| WDC WDS100T3X0C-00SJG0 1TB             | 1         | 1.75%   |
| WDC WD20SPZX-00CRAT0 2TB               | 1         | 1.75%   |
| WDC WD1200BEVS-00UST0 120GB            | 1         | 1.75%   |
| WDC WD10SPZX-75Z10T2 1TB               | 1         | 1.75%   |
| WDC WD10SPZX-24Z10 1TB                 | 1         | 1.75%   |
| WDC WD10JPLX-00MBPT0 1TB               | 1         | 1.75%   |
| Unknown SD16G  16GB                    | 1         | 1.75%   |
| Unknown HAG4a2  16GB                   | 1         | 1.75%   |
| Toshiba NVMe SSD Drive 256GB           | 1         | 1.75%   |
| Toshiba MQ04ABF100 1TB                 | 1         | 1.75%   |
| Toshiba MQ01ABD100 1TB                 | 1         | 1.75%   |
| Toshiba MQ01ABD075 752GB               | 1         | 1.75%   |
| Toshiba MK7559GSXP 752GB               | 1         | 1.75%   |
| Toshiba MK5059GSXP 500GB               | 1         | 1.75%   |
| SK hynix PC401 NVMe 1TB                | 1         | 1.75%   |
| SK hynix NVMe SSD Drive 1024GB         | 1         | 1.75%   |
| Seagate ST500LT015-1DJ142 500GB        | 1         | 1.75%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 1         | 1.75%   |
| Seagate ST1000LM035-1RK172 970GB       | 1         | 1.75%   |
| Seagate ST1000LM014-1EJ164 1TB         | 1         | 1.75%   |
| Seagate NVMe SSD Drive 250GB           | 1         | 1.75%   |
| SanDisk Ultra II 480GB SSD             | 1         | 1.75%   |
| SanDisk SSD PLUS 240GB                 | 1         | 1.75%   |
| Samsung SSD 850 PRO 256GB              | 1         | 1.75%   |
| Samsung NVMe SSD Drive 512GB           | 1         | 1.75%   |
| Samsung MZVLQ256HAJD-00000 256GB       | 1         | 1.75%   |
| Samsung MZALQ512HALU-000L1 512GB       | 1         | 1.75%   |
| Samsung HM321HI 320GB                  | 1         | 1.75%   |
| Micron MTFDHBA1T0TDV-1AZ1AABHA 1TB     | 1         | 1.75%   |
| Micron 1100_MTFDDAV512TBN 512GB SSD    | 1         | 1.75%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD    | 1         | 1.75%   |
| Kingston SV300S37A120G 120GB SSD       | 1         | 1.75%   |
| Kingston SA400S37120G 120GB SSD        | 1         | 1.75%   |
| Kingston RBU-SNS8100S3128GD1 128GB SSD | 1         | 1.75%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 12     | 37.93%  |
| Toshiba             | 7         | 7      | 24.14%  |
| WDC                 | 5         | 5      | 17.24%  |
| HGST                | 2         | 2      | 6.9%    |
| Fujitsu             | 2         | 2      | 6.9%    |
| Samsung Electronics | 1         | 1      | 3.45%   |
| Hitachi             | 1         | 1      | 3.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 3         | 3      | 20%     |
| SanDisk             | 2         | 2      | 13.33%  |
| Micron Technology   | 2         | 2      | 13.33%  |
| Crucial             | 2         | 2      | 13.33%  |
| WDC                 | 1         | 1      | 6.67%   |
| Samsung Electronics | 1         | 1      | 6.67%   |
| KingSpec            | 1         | 1      | 6.67%   |
| Intenso             | 1         | 1      | 6.67%   |
| China               | 1         | 1      | 6.67%   |
| A-DATA Technology   | 1         | 1      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 27        | 30     | 51.92%  |
| SSD     | 14        | 15     | 26.92%  |
| NVMe    | 8         | 11     | 15.38%  |
| MMC     | 2         | 2      | 3.85%   |
| Unknown | 1         | 1      | 1.92%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 36        | 46     | 78.26%  |
| NVMe | 8         | 11     | 17.39%  |
| MMC  | 2         | 2      | 4.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 24        | 26     | 57.14%  |
| 0.51-1.0   | 15        | 16     | 35.71%  |
| 1.01-2.0   | 3         | 3      | 7.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 21        | 46.67%  |
| 251-500    | 7         | 15.56%  |
| 501-1000   | 6         | 13.33%  |
| 51-100     | 4         | 8.89%   |
| 1-20       | 3         | 6.67%   |
| 1001-2000  | 2         | 4.44%   |
| 21-50      | 1         | 2.22%   |
| Unknown    | 1         | 2.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 23        | 48.94%  |
| 21-50     | 9         | 19.15%  |
| 101-250   | 6         | 12.77%  |
| 51-100    | 4         | 8.51%   |
| 251-500   | 3         | 6.38%   |
| 1001-2000 | 1         | 2.13%   |
| Unknown   | 1         | 2.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST1000LM014-1EJ164 1TB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1         | 1      | 100%    |

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
| Detected | 32        | 40     | 68.09%  |
| Works    | 14        | 18     | 29.79%  |
| Malfunc  | 1         | 1      | 2.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 37        | 75.51%  |
| Samsung Electronics              | 3         | 6.12%   |
| AMD                              | 2         | 4.08%   |
| Toshiba America Info Systems     | 1         | 2.04%   |
| SK hynix                         | 1         | 2.04%   |
| Silicon Integrated Systems [SiS] | 1         | 2.04%   |
| Seagate Technology               | 1         | 2.04%   |
| SanDisk                          | 1         | 2.04%   |
| Micron/Crucial Technology        | 1         | 2.04%   |
| Micron Technology                | 1         | 2.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 8         | 15.69%  |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 7.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 7.84%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 5.88%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 5.88%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 5.88%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 5.88%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 5.88%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 3.92%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 3.92%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 2         | 3.92%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 1         | 1.96%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 1         | 1.96%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 1         | 1.96%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 1         | 1.96%   |
| Seagate FireCuda 510 SSD                                                       | 1         | 1.96%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 1.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 1.96%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1         | 1.96%   |
| Micron NVMe Storage Controller                                                 | 1         | 1.96%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 1.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 1         | 1.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 1         | 1.96%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.96%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 31        | 63.27%  |
| RAID | 8         | 16.33%  |
| NVMe | 8         | 16.33%  |
| IDE  | 2         | 4.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 43        | 95.56%  |
| AMD    | 2         | 4.44%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz               | 2         | 4.44%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 2         | 4.44%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 4.44%   |
| Intel Core i5-2410M CPU @ 2.30GHz               | 2         | 4.44%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz              | 2         | 4.44%   |
| Intel Core i3 CPU M 370 @ 2.40GHz               | 2         | 4.44%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 2         | 4.44%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz          | 1         | 2.22%   |
| Intel Pentium CPU B980 @ 2.40GHz                | 1         | 2.22%   |
| Intel Core i9-8950HK CPU @ 2.90GHz              | 1         | 2.22%   |
| Intel Core i7-5500U CPU @ 2.40GHz               | 1         | 2.22%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz              | 1         | 2.22%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz              | 1         | 2.22%   |
| Intel Core i7-4510U CPU @ 2.00GHz               | 1         | 2.22%   |
| Intel Core i7-4500U CPU @ 1.80GHz               | 1         | 2.22%   |
| Intel Core i7-2670QM CPU @ 2.20GHz              | 1         | 2.22%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 1         | 2.22%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 1         | 2.22%   |
| Intel Core i5-4310U CPU @ 2.00GHz               | 1         | 2.22%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 1         | 2.22%   |
| Intel Core i5-3360M CPU @ 2.80GHz               | 1         | 2.22%   |
| Intel Core i5-3337U CPU @ 1.80GHz               | 1         | 2.22%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 1         | 2.22%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 1         | 2.22%   |
| Intel Core i5-2430M CPU @ 2.40GHz               | 1         | 2.22%   |
| Intel Core i5 CPU M 540 @ 2.53GHz               | 1         | 2.22%   |
| Intel Core i3-7020U CPU @ 2.30GHz               | 1         | 2.22%   |
| Intel Core i3-5020U CPU @ 2.20GHz               | 1         | 2.22%   |
| Intel Core i3-5005U CPU @ 2.00GHz               | 1         | 2.22%   |
| Intel Core i3-4030U CPU @ 1.90GHz               | 1         | 2.22%   |
| Intel Core i3 CPU M 380 @ 2.53GHz               | 1         | 2.22%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz            | 1         | 2.22%   |
| Intel Core 2 Duo CPU L9400 @ 1.86GHz            | 1         | 2.22%   |
| Intel Celeron Dual-Core CPU T3500 @ 2.10GHz     | 1         | 2.22%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 1         | 2.22%   |
| Intel Celeron CPU N2840 @ 2.16GHz               | 1         | 2.22%   |
| AMD A8-4500M APU with Radeon HD Graphics        | 1         | 2.22%   |
| AMD A10-9620P RADEON R5, 10 COMPUTE CORES 4C+6G | 1         | 2.22%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 13        | 28.89%  |
| Intel Core i7           | 11        | 24.44%  |
| Intel Core i3           | 9         | 20%     |
| Other                   | 2         | 4.44%   |
| Intel Core 2 Duo        | 2         | 4.44%   |
| Intel Celeron           | 2         | 4.44%   |
| Intel Pentium Dual      | 1         | 2.22%   |
| Intel Pentium           | 1         | 2.22%   |
| Intel Core i9           | 1         | 2.22%   |
| Intel Celeron Dual-Core | 1         | 2.22%   |
| AMD A8                  | 1         | 2.22%   |
| AMD A10                 | 1         | 2.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 33        | 73.33%  |
| 4      | 8         | 17.78%  |
| 6      | 4         | 8.89%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 45        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 38        | 84.44%  |
| 1      | 7         | 15.56%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 45        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 10        | 21.74%  |
| 0x206a7    | 6         | 13.04%  |
| 0x40651    | 4         | 8.7%    |
| 0x906ea    | 3         | 6.52%   |
| 0x806ea    | 3         | 6.52%   |
| 0x806c1    | 2         | 4.35%   |
| 0x706e5    | 2         | 4.35%   |
| 0x306d4    | 2         | 4.35%   |
| 0x306a9    | 2         | 4.35%   |
| 0x20655    | 2         | 4.35%   |
| 0x1067a    | 2         | 4.35%   |
| 0xa0652    | 1         | 2.17%   |
| 0x806e9    | 1         | 2.17%   |
| 0x6fd      | 1         | 2.17%   |
| 0x406c4    | 1         | 2.17%   |
| 0x306c3    | 1         | 2.17%   |
| 0x30678    | 1         | 2.17%   |
| 0x10676    | 1         | 2.17%   |
| 0x0600611a | 1         | 2.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 9         | 20%     |
| Haswell     | 7         | 15.56%  |
| SandyBridge | 6         | 13.33%  |
| Westmere    | 4         | 8.89%   |
| Penryn      | 3         | 6.67%   |
| IvyBridge   | 3         | 6.67%   |
| Broadwell   | 3         | 6.67%   |
| TigerLake   | 2         | 4.44%   |
| Silvermont  | 2         | 4.44%   |
| IceLake     | 2         | 4.44%   |
| Piledriver  | 1         | 2.22%   |
| Excavator   | 1         | 2.22%   |
| Core        | 1         | 2.22%   |
| CometLake   | 1         | 2.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 41        | 67.21%  |
| Nvidia                           | 14        | 22.95%  |
| AMD                              | 5         | 8.2%    |
| Silicon Integrated Systems [SiS] | 1         | 1.64%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 9.38%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 7.81%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 6.25%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 4.69%   |
| Intel UHD Graphics 620                                                                   | 3         | 4.69%   |
| Intel HD Graphics 620                                                                    | 3         | 4.69%   |
| Intel HD Graphics 5500                                                                   | 3         | 4.69%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 4.69%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 4.69%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 3.13%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 3.13%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 3.13%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 3.13%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 3.13%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 1.56%   |
| Nvidia TU104BM [GeForce RTX 2070 SUPER Mobile / Max-Q]                                   | 1         | 1.56%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 1.56%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 1.56%   |
| Nvidia GM204M [GeForce GTX 960 OEM / 970M]                                               | 1         | 1.56%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.56%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 1.56%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 1.56%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 1.56%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 1.56%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.56%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 1.56%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 1         | 1.56%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 1.56%   |
| AMD Trinity [Radeon HD 7640G]                                                            | 1         | 1.56%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 1.56%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 1.56%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 1.56%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 1.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 25        | 55.56%  |
| Intel + Nvidia | 13        | 28.89%  |
| Intel + AMD    | 3         | 6.67%   |
| 2 x AMD        | 2         | 4.44%   |
| 1 x SiS        | 1         | 2.22%   |
| 1 x Nvidia     | 1         | 2.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 34        | 73.91%  |
| Proprietary | 9         | 19.57%  |
| Unknown     | 3         | 6.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 67.39%  |
| 3.01-4.0   | 6         | 13.04%  |
| 1.01-2.0   | 5         | 10.87%  |
| 0.51-1.0   | 2         | 4.35%   |
| 7.01-8.0   | 1         | 2.17%   |
| 2.01-3.0   | 1         | 2.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 14        | 28.57%  |
| AU Optronics            | 9         | 18.37%  |
| BOE                     | 8         | 16.33%  |
| LG Display              | 7         | 14.29%  |
| Chimei Innolux          | 2         | 4.08%   |
| Chi Mei Optoelectronics | 2         | 4.08%   |
| Sharp                   | 1         | 2.04%   |
| MSI                     | 1         | 2.04%   |
| Lenovo                  | 1         | 2.04%   |
| JDI                     | 1         | 2.04%   |
| Goldstar                | 1         | 2.04%   |
| Eizo                    | 1         | 2.04%   |
| AOC                     | 1         | 2.04%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch    | 2         | 3.92%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                  | 1         | 1.96%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch        | 1         | 1.96%   |
| Samsung Electronics T22B300 SAM092D 1920x1080 477x268mm 21.5-inch        | 1         | 1.96%   |
| Samsung Electronics S27E500 SAM0D0D 1920x1080 598x336mm 27.0-inch        | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SEC454C 1366x768 309x174mm 14.0-inch     | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SEC4542 1280x800 303x190mm 14.1-inch     | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SEC3942 1366x768 309x174mm 14.0-inch     | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 303x190mm 14.1-inch     | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch     | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch     | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch     | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SDC4146 1366x768 344x194mm 15.5-inch     | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SDC344A 1366x768 344x194mm 15.5-inch     | 1         | 1.96%   |
| MSI MAG341CQ MSI1462 3440x1440 797x333mm 34.0-inch                       | 1         | 1.96%   |
| LG Display LCD Monitor LGD0611 1920x1080 382x215mm 17.3-inch             | 1         | 1.96%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch             | 1         | 1.96%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 1         | 1.96%   |
| LG Display LCD Monitor LGD037C 1366x768 310x174mm 14.0-inch              | 1         | 1.96%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 1         | 1.96%   |
| LG Display LCD Monitor LGD02AC 1366x768 344x194mm 15.5-inch              | 1         | 1.96%   |
| LG Display LCD Monitor LGD024F 1280x800 260x160mm 12.0-inch              | 1         | 1.96%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 1         | 1.96%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                    | 1         | 1.96%   |
| Goldstar M2380A GSM57EE 1920x1080 509x286mm 23.0-inch                    | 1         | 1.96%   |
| Eizo EV2450 ENC2532 1920x1080 528x297mm 23.9-inch                        | 1         | 1.96%   |
| Eizo EV2450 ENC2531 1920x1080 528x297mm 23.9-inch                        | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN1489 1366x768 309x173mm 13.9-inch          | 1         | 1.96%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 1         | 1.96%   |
| Chi Mei Optoelectronics LCD Monitor CMO1469 1366x768 309x174mm 14.0-inch | 1         | 1.96%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 1         | 1.96%   |
| BOE LCD Monitor BOE0897 1366x768 344x194mm 15.5-inch                     | 1         | 1.96%   |
| BOE LCD Monitor BOE085E 1920x1080 344x194mm 15.5-inch                    | 1         | 1.96%   |
| BOE LCD Monitor BOE06C6 1920x1080 344x194mm 15.5-inch                    | 1         | 1.96%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 1         | 1.96%   |
| BOE LCD Monitor BOE065E 1920x1080 344x194mm 15.5-inch                    | 1         | 1.96%   |
| BOE LCD Monitor BOE05F1 1366x768 309x173mm 13.9-inch                     | 1         | 1.96%   |
| BOE LCD Monitor BOE05DF 1366x768 290x160mm 13.0-inch                     | 1         | 1.96%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 23        | 46.94%  |
| 1920x1080 (FHD)  | 17        | 34.69%  |
| 1600x900 (HD+)   | 2         | 4.08%   |
| 1280x800 (WXGA)  | 2         | 4.08%   |
| 3840x2160 (4K)   | 1         | 2.04%   |
| 3440x1440        | 1         | 2.04%   |
| 3000x2000        | 1         | 2.04%   |
| 2256x1504        | 1         | 2.04%   |
| 1440x900 (WXGA+) | 1         | 2.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 25        | 49.02%  |
| 14     | 8         | 15.69%  |
| 17     | 4         | 7.84%   |
| 13     | 4         | 7.84%   |
| 23     | 3         | 5.88%   |
| 12     | 2         | 3.92%   |
| 34     | 1         | 1.96%   |
| 31     | 1         | 1.96%   |
| 27     | 1         | 1.96%   |
| 24     | 1         | 1.96%   |
| 21     | 1         | 1.96%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 32        | 64%     |
| 351-400     | 6         | 12%     |
| 201-300     | 5         | 10%     |
| 501-600     | 4         | 8%      |
| 701-800     | 1         | 2%      |
| 601-700     | 1         | 2%      |
| 401-500     | 1         | 2%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 39        | 84.78%  |
| 3/2   | 3         | 6.52%   |
| 16/10 | 3         | 6.52%   |
| 21/9  | 1         | 2.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 25        | 50%     |
| 81-90          | 11        | 22%     |
| 201-250        | 4         | 8%      |
| 121-130        | 4         | 8%      |
| 61-70          | 2         | 4%      |
| 351-500        | 2         | 4%      |
| 71-80          | 1         | 2%      |
| 301-350        | 1         | 2%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 24        | 48.98%  |
| 121-160       | 16        | 32.65%  |
| 51-100        | 7         | 14.29%  |
| More than 240 | 1         | 2.04%   |
| 161-240       | 1         | 2.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 36        | 80%     |
| 2     | 6         | 13.33%  |
| 0     | 2         | 4.44%   |
| 3     | 1         | 2.22%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 22        | 30.14%  |
| Intel                            | 22        | 30.14%  |
| Qualcomm Atheros                 | 16        | 21.92%  |
| Broadcom                         | 5         | 6.85%   |
| Xiaomi                           | 1         | 1.37%   |
| Silicon Integrated Systems [SiS] | 1         | 1.37%   |
| Ralink Technology                | 1         | 1.37%   |
| Ralink                           | 1         | 1.37%   |
| Marvell Technology Group         | 1         | 1.37%   |
| Dell                             | 1         | 1.37%   |
| Broadcom Limited                 | 1         | 1.37%   |
| ASUSTek Computer                 | 1         | 1.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 15        | 17.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 5         | 5.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 5.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 4.6%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 3.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3         | 3.45%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 2.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 2.3%    |
| Intel Wireless 7265                                                     | 2         | 2.3%    |
| Intel Wireless 3160                                                     | 2         | 2.3%    |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 2.3%    |
| Intel Centrino Advanced-N 6200                                          | 2         | 2.3%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 2.3%    |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 1.15%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 1.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.15%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 1.15%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 1.15%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.15%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 1         | 1.15%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller               | 1         | 1.15%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 1         | 1.15%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 1.15%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                              | 1         | 1.15%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1         | 1.15%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.15%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 1         | 1.15%   |
| Intel Wireless 8265 / 8275                                              | 1         | 1.15%   |
| Intel Wireless 7260                                                     | 1         | 1.15%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 1.15%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 1.15%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 1.15%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 1.15%   |
| Intel Ethernet Connection I218-LM                                       | 1         | 1.15%   |
| Intel Ethernet Connection (4) I219-V                                    | 1         | 1.15%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 1.15%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 1.15%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 21        | 43.75%  |
| Qualcomm Atheros      | 13        | 27.08%  |
| Realtek Semiconductor | 5         | 10.42%  |
| Broadcom              | 4         | 8.33%   |
| Ralink Technology     | 1         | 2.08%   |
| Ralink                | 1         | 2.08%   |
| Dell                  | 1         | 2.08%   |
| Broadcom Limited      | 1         | 2.08%   |
| ASUSTek Computer      | 1         | 2.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 10.42%  |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 8.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 6.25%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 4.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 4.17%   |
| Intel Wireless 7265                                                     | 2         | 4.17%   |
| Intel Wireless 3160                                                     | 2         | 4.17%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 4.17%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 4.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 4.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 2.08%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 2.08%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 2.08%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 2.08%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 2.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 2.08%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 2.08%   |
| Intel Wireless 8265 / 8275                                              | 1         | 2.08%   |
| Intel Wireless 7260                                                     | 1         | 2.08%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 2.08%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 2.08%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 2.08%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 2.08%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 2.08%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 2.08%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 2.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1         | 2.08%   |
| Dell Wireless 5630 (EVDO-HSPA) Mobile Broadband Mini-Card               | 1         | 2.08%   |
| Broadcom Limited BCM4311 802.11a/b/g                                    | 1         | 2.08%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 2.08%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 2.08%   |
| ASUS USB-AC56 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU]     | 1         | 2.08%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 21        | 53.85%  |
| Intel                            | 7         | 17.95%  |
| Qualcomm Atheros                 | 6         | 15.38%  |
| Broadcom                         | 2         | 5.13%   |
| Xiaomi                           | 1         | 2.56%   |
| Silicon Integrated Systems [SiS] | 1         | 2.56%   |
| Marvell Technology Group         | 1         | 2.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 15        | 38.46%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 12.82%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 7.69%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 2.56%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 2.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 2.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 2.56%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 2.56%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 2.56%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 2.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 2.56%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 2.56%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.56%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 2.56%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.56%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.56%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 2.56%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 45        | 54.22%  |
| Ethernet | 38        | 45.78%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 42        | 80.77%  |
| Ethernet | 10        | 19.23%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 37        | 82.22%  |
| 1     | 8         | 17.78%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 38        | 84.44%  |
| Yes  | 7         | 15.56%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 14        | 40%     |
| Qualcomm Atheros Communications | 6         | 17.14%  |
| Realtek Semiconductor           | 3         | 8.57%   |
| IMC Networks                    | 3         | 8.57%   |
| Dell                            | 2         | 5.71%   |
| Broadcom                        | 2         | 5.71%   |
| Toshiba                         | 1         | 2.86%   |
| Ralink Technology               | 1         | 2.86%   |
| Hewlett-Packard                 | 1         | 2.86%   |
| Foxconn / Hon Hai               | 1         | 2.86%   |
| Cambridge Silicon Radio         | 1         | 2.86%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 7         | 20%     |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 8.57%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 8.57%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 5.71%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 5.71%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 5.71%   |
| Intel AX201 Bluetooth                               | 2         | 5.71%   |
| IMC Networks Bluetooth Radio                        | 2         | 5.71%   |
| Toshiba Bluetooth Device                            | 1         | 2.86%   |
| Realtek Bluetooth Radio                             | 1         | 2.86%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 2.86%   |
| Intel AX210 Bluetooth                               | 1         | 2.86%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 2.86%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 2.86%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 2.86%   |
| Dell Wireless 355 Bluetooth                         | 1         | 2.86%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 2.86%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.86%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 2.86%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 2.86%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 42        | 80.77%  |
| Nvidia                                          | 4         | 7.69%   |
| AMD                                             | 2         | 3.85%   |
| Silicon Integrated Systems [SiS]                | 1         | 1.92%   |
| Razer USA                                       | 1         | 1.92%   |
| Logitech                                        | 1         | 1.92%   |
| Licensed by Sony Computer Entertainment America | 1         | 1.92%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 6         | 9.38%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 7.81%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 7.81%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 7.81%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 6.25%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 6.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 4.69%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 4.69%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 4.69%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 3.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 3.13%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 3.13%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 3.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 3.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 3.13%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 1.56%   |
| Razer USA Kraken 7.1 V2                                                                           | 1         | 1.56%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 1.56%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.56%   |
| Logitech Speaker Lapdesk N700                                                                     | 1         | 1.56%   |
| Licensed by Sony Computer Entertainment America Wireless Stereo Headset                           | 1         | 1.56%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 1.56%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.56%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 1.56%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.56%   |
| AMD FCH Azalia Controller                                                                         | 1         | 1.56%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 1.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 10        | 40%     |
| SK hynix            | 6         | 24%     |
| Micron Technology   | 4         | 16%     |
| Kingston            | 2         | 8%      |
| Teikon              | 1         | 4%      |
| Ramaxel Technology  | 1         | 4%      |
| Crucial             | 1         | 4%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s      | 2         | 8%      |
| Teikon RAM TMT251S6CFR8C-PBHC 4GB SODIMM DDR3 1600MT/s     | 1         | 4%      |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 1         | 4%      |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 1         | 4%      |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 1         | 4%      |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s     | 1         | 4%      |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s     | 1         | 4%      |
| SK hynix RAM H9CCNNN8GTMLAR-NUD 2GB LPDDR3 1600MT/s        | 1         | 4%      |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s      | 1         | 4%      |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s      | 1         | 4%      |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s      | 1         | 4%      |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s      | 1         | 4%      |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s      | 1         | 4%      |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s     | 1         | 4%      |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s      | 1         | 4%      |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s      | 1         | 4%      |
| Ramaxel RAM RMSA3270MB86H9F2400 4GB SODIMM DDR4 2400MT/s   | 1         | 4%      |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                 | 1         | 4%      |
| Micron RAM 8ATF1G64HZ-2G1B1 8GB SODIMM DDR4 2400MT/s       | 1         | 4%      |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s      | 1         | 4%      |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s     | 1         | 4%      |
| Kingston RAM KHX2133C13S4/4G 4GB SODIMM DDR4 2133MT/s      | 1         | 4%      |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s      | 1         | 4%      |
| Crucial RAM CT16G4SFRA32A.M16FRS 16GB SODIMM DDR4 3200MT/s | 1         | 4%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 10        | 52.63%  |
| DDR3   | 8         | 42.11%  |
| LPDDR3 | 1         | 5.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SODIMM  | 18        | 94.74%  |
| Unknown | 1         | 5.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 8         | 40%     |
| 4096  | 8         | 40%     |
| 16384 | 3         | 15%     |
| 2048  | 1         | 5%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 9         | 40.91%  |
| 2667  | 5         | 22.73%  |
| 3200  | 3         | 13.64%  |
| 2400  | 3         | 13.64%  |
| 2133  | 1         | 4.55%   |
| 1334  | 1         | 4.55%   |

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
| Chicony Electronics           | 10        | 25.64%  |
| Microdia                      | 6         | 15.38%  |
| Suyin                         | 4         | 10.26%  |
| Sunplus Innovation Technology | 3         | 7.69%   |
| Realtek Semiconductor         | 3         | 7.69%   |
| Quanta                        | 3         | 7.69%   |
| IMC Networks                  | 3         | 7.69%   |
| Bison Electronics             | 3         | 7.69%   |
| Silicon Motion                | 2         | 5.13%   |
| Importek                      | 1         | 2.56%   |
| Acer                          | 1         | 2.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                  | 2         | 5.13%   |
| Microdia Integrated Webcam                     | 2         | 5.13%   |
| Suyin WebCam                                   | 1         | 2.56%   |
| Suyin HP Truevision HD                         | 1         | 2.56%   |
| Suyin Asus Integrated Webcam                   | 1         | 2.56%   |
| Suyin 1.3M HD WebCam                           | 1         | 2.56%   |
| Sunplus Laptop_Integrated_Webcam_HD            | 1         | 2.56%   |
| Sunplus Integrated_Webcam_HD                   | 1         | 2.56%   |
| Sunplus HD WebCam                              | 1         | 2.56%   |
| Silicon Motion WebCam SC-13HDL11939N           | 1         | 2.56%   |
| Silicon Motion HP Webcam-101 Integrated Camera | 1         | 2.56%   |
| Realtek USB2.0 VGA UVC WebCam                  | 1         | 2.56%   |
| Realtek Laptop Camera                          | 1         | 2.56%   |
| Realtek HP Truevision HD                       | 1         | 2.56%   |
| Quanta Laptop_Integrated_Webcam_2HDM           | 1         | 2.56%   |
| Quanta HP TrueVision HD Camera                 | 1         | 2.56%   |
| Quanta HD Webcam                               | 1         | 2.56%   |
| Microdia Sonix 1.3 MP Laptop Integrated Webcam | 1         | 2.56%   |
| Microdia Laptop_Integrated_Webcam_0.3M         | 1         | 2.56%   |
| Importek HP Truevision HD Integrated Webcam    | 1         | 2.56%   |
| IMC Networks USB2.0 VGA UVC WebCam             | 1         | 2.56%   |
| IMC Networks USB2.0 UVC HD Webcam              | 1         | 2.56%   |
| IMC Networks USB2.0 HD UVC WebCam              | 1         | 2.56%   |
| Chicony USB 2.0 Camera                         | 1         | 2.56%   |
| Chicony TOSHIBA Web Camera - HD                | 1         | 2.56%   |
| Chicony Lenovo EasyCamera                      | 1         | 2.56%   |
| Chicony Integrated Camera                      | 1         | 2.56%   |
| Chicony HP Wide Vision HD Camera               | 1         | 2.56%   |
| Chicony HP Webcam [2 MP Macro]                 | 1         | 2.56%   |
| Chicony HP Webcam                              | 1         | 2.56%   |
| Chicony HP HD Camera                           | 1         | 2.56%   |
| Chicony HD WebCam                              | 1         | 2.56%   |
| Chicony EasyCamera                             | 1         | 2.56%   |
| Bison Integrated Camera                        | 1         | 2.56%   |
| Bison HP TrueVision HD Webcam                  | 1         | 2.56%   |
| Bison EasyCamera                               | 1         | 2.56%   |
| Acer BisonCam, NB Pro                          | 1         | 2.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 60%     |
| Shenzhen Goodix Technology | 1         | 20%     |
| AuthenTec                  | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors Fingerprint scanner       | 2         | 40%     |
| Validity Sensors VFS495 Fingerprint Reader | 1         | 20%     |
| Shenzhen Goodix  FingerPrint Device        | 1         | 20%     |
| AuthenTec AES2810                          | 1         | 20%     |

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


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 50%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 32        | 71.11%  |
| 1     | 12        | 26.67%  |
| 2     | 1         | 2.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 5         | 41.67%  |
| Graphics card      | 4         | 33.33%  |
| Chipcard           | 2         | 16.67%  |
| Net/ethernet       | 1         | 8.33%   |

