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

Total: 70

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| HP        | 250 G3                      | [784033212e](https://linux-hardware.org/?probe=784033212e) | Oct 29, 2023 |
| HP        | 250 G3                      | [43fbeb0886](https://linux-hardware.org/?probe=43fbeb0886) | Oct 26, 2023 |
| Lenovo    | 100-14IBY 80R7              | [f6389f0244](https://linux-hardware.org/?probe=f6389f0244) | Oct 06, 2023 |
| Dell      | Latitude E7450              | [d7a8f0a599](https://linux-hardware.org/?probe=d7a8f0a599) | Jul 22, 2023 |
| Apple     | MacBookPro12,1              | [fc6e3f084f](https://linux-hardware.org/?probe=fc6e3f084f) | Jun 04, 2023 |
| Apple     | MacBookPro12,1              | [a9c6f5e0e6](https://linux-hardware.org/?probe=a9c6f5e0e6) | Jun 04, 2023 |
| Acer      | Aspire A317-53              | [406fc17c32](https://linux-hardware.org/?probe=406fc17c32) | Jun 04, 2023 |
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
| UbuntuDDE 20.04 | 31        | 64.58%  |
| UbuntuDDE 21.04 | 5         | 10.42%  |
| UbuntuDDE 22.04 | 4         | 8.33%   |
| UbuntuDDE 21.10 | 4         | 8.33%   |
| UbuntuDDE 20.10 | 2         | 4.17%   |
| UbuntuDDE 23.04 | 1         | 2.08%   |
| UbuntuDDE 18.10 | 1         | 2.08%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| UbuntuDDE | 48        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 7         | 14%     |
| 5.4.0-29-generic  | 7         | 14%     |
| 5.4.0-37-generic  | 4         | 8%      |
| 5.4.0-48-generic  | 2         | 4%      |
| 5.4.0-21-generic  | 2         | 4%      |
| 5.11.0-17-generic | 2         | 4%      |
| 6.2.0-34-generic  | 1         | 2%      |
| 5.8.0-33-generic  | 1         | 2%      |
| 5.8.0-23-generic  | 1         | 2%      |
| 5.6.0-1008-oem    | 1         | 2%      |
| 5.4.0-96-generic  | 1         | 2%      |
| 5.4.0-94-generic  | 1         | 2%      |
| 5.4.0-88-generic  | 1         | 2%      |
| 5.4.0-84-generic  | 1         | 2%      |
| 5.4.0-70-generic  | 1         | 2%      |
| 5.4.0-52-generic  | 1         | 2%      |
| 5.4.0-39-generic  | 1         | 2%      |
| 5.4.0-34-generic  | 1         | 2%      |
| 5.4.0-33-generic  | 1         | 2%      |
| 5.19.0-38-generic | 1         | 2%      |
| 5.15.0-88-generic | 1         | 2%      |
| 5.15.0-57-generic | 1         | 2%      |
| 5.15.0-53-generic | 1         | 2%      |
| 5.15.0-48-generic | 1         | 2%      |
| 5.13.0-30-generic | 1         | 2%      |
| 5.13.0-23-generic | 1         | 2%      |
| 5.13.0-22-generic | 1         | 2%      |
| 5.13.0-21-generic | 1         | 2%      |
| 5.11.0-46-generic | 1         | 2%      |
| 5.11.0-25-generic | 1         | 2%      |
| 5.11.0-16-generic | 1         | 2%      |
| 4.15.0-29-generic | 1         | 2%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 30        | 62.5%   |
| 5.11.0  | 5         | 10.42%  |
| 5.13.0  | 4         | 8.33%   |
| 5.15.0  | 3         | 6.25%   |
| 5.8.0   | 2         | 4.17%   |
| 6.2.0   | 1         | 2.08%   |
| 5.6.0   | 1         | 2.08%   |
| 5.19.0  | 1         | 2.08%   |
| 4.15.0  | 1         | 2.08%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 30        | 62.5%   |
| 5.11    | 5         | 10.42%  |
| 5.13    | 4         | 8.33%   |
| 5.15    | 3         | 6.25%   |
| 5.8     | 2         | 4.17%   |
| 6.2     | 1         | 2.08%   |
| 5.6     | 1         | 2.08%   |
| 5.19    | 1         | 2.08%   |
| 4.15    | 1         | 2.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 48        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Deepin | 48        | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 46        | 95.83%  |
| Wayland | 2         | 4.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 26        | 53.06%  |
| LightDM | 12        | 24.49%  |
| GDM     | 8         | 16.33%  |
| TDM     | 1         | 2.04%   |
| SDDM    | 1         | 2.04%   |
| GDM3    | 1         | 2.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 12        | 25%     |
| pt_BR   | 6         | 12.5%   |
| es_ES   | 3         | 6.25%   |
| de_DE   | 3         | 6.25%   |
| C       | 3         | 6.25%   |
| ru_RU   | 2         | 4.17%   |
| fr_FR   | 2         | 4.17%   |
| es_MX   | 2         | 4.17%   |
| es_AR   | 2         | 4.17%   |
| en_GB   | 2         | 4.17%   |
| sr_RS   | 1         | 2.08%   |
| nl_NL   | 1         | 2.08%   |
| it_IT   | 1         | 2.08%   |
| id_ID   | 1         | 2.08%   |
| es_CO   | 1         | 2.08%   |
| en_ZA   | 1         | 2.08%   |
| en_IN   | 1         | 2.08%   |
| en_BW   | 1         | 2.08%   |
| en_AU   | 1         | 2.08%   |
| cs_CZ   | 1         | 2.08%   |
| Unknown | 1         | 2.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 28        | 57.14%  |
| EFI  | 21        | 42.86%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 40        | 83.33%  |
| Tmpfs   | 3         | 6.25%   |
| Overlay | 3         | 6.25%   |
| Zfs     | 1         | 2.08%   |
| Ext2    | 1         | 2.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 29        | 60.42%  |
| GPT     | 17        | 35.42%  |
| MBR     | 2         | 4.17%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 41        | 85.42%  |
| Yes       | 7         | 14.58%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 52.08%  |
| No        | 23        | 47.92%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 12        | 25%     |
| Dell                | 11        | 22.92%  |
| Lenovo              | 7         | 14.58%  |
| ASUSTek Computer    | 6         | 12.5%   |
| Acer                | 4         | 8.33%   |
| Toshiba             | 2         | 4.17%   |
| Samsung Electronics | 1         | 2.08%   |
| MSI                 | 1         | 2.08%   |
| HUAWEI              | 1         | 2.08%   |
| Google              | 1         | 2.08%   |
| Framework           | 1         | 2.08%   |
| Unknown             | 1         | 2.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Toshiba Satellite S55t-B                | 1         | 2.08%   |
| Toshiba Satellite C55-B                 | 1         | 2.08%   |
| Samsung 355V4C/356V4C/3445VC/3545VC     | 1         | 2.08%   |
| MSI GS60 2QE                            | 1         | 2.08%   |
| Lenovo ThinkPad X200 Tablet 7449FWG     | 1         | 2.08%   |
| Lenovo ThinkPad T430 2349DS5            | 1         | 2.08%   |
| Lenovo ThinkPad E15 Gen 2 20TDS0A300    | 1         | 2.08%   |
| Lenovo IdeaPad 520-15IKB 81BF           | 1         | 2.08%   |
| Lenovo IdeaPad 510-15IKB 80SV           | 1         | 2.08%   |
| Lenovo G480 20150                       | 1         | 2.08%   |
| Lenovo 100-14IBY 80R7                   | 1         | 2.08%   |
| HUAWEI MACH-WX9                         | 1         | 2.08%   |
| HP ProBook 650 G3                       | 1         | 2.08%   |
| HP Presario CQ56                        | 1         | 2.08%   |
| HP Pavilion dv6                         | 1         | 2.08%   |
| HP Pavilion dm4                         | 1         | 2.08%   |
| HP Pavilion 14                          | 1         | 2.08%   |
| HP OMEN by Laptop 17-cb1xxx             | 1         | 2.08%   |
| HP Notebook                             | 1         | 2.08%   |
| HP Laptop 15-dy1xxx                     | 1         | 2.08%   |
| HP Laptop 15-da0xxx                     | 1         | 2.08%   |
| HP EliteBook 2540p                      | 1         | 2.08%   |
| HP 250 G4 Notebook PC                   | 1         | 2.08%   |
| HP 250 G3                               | 1         | 2.08%   |
| Google Banon                            | 1         | 2.08%   |
| Framework Laptop                        | 1         | 2.08%   |
| Dell XPS 15 9570                        | 1         | 2.08%   |
| Dell System XPS L502X                   | 1         | 2.08%   |
| Dell Latitude E7450                     | 1         | 2.08%   |
| Dell Latitude E6430                     | 1         | 2.08%   |
| Dell Latitude E6320                     | 1         | 2.08%   |
| Dell Latitude E5440                     | 1         | 2.08%   |
| Dell Inspiron N7010                     | 1         | 2.08%   |
| Dell Inspiron N4030                     | 1         | 2.08%   |
| Dell Inspiron 5447                      | 1         | 2.08%   |
| Dell Inspiron 1525                      | 1         | 2.08%   |
| Dell G7 7588                            | 1         | 2.08%   |
| ASUS X555QG                             | 1         | 2.08%   |
| ASUS VivoBook_ASUSLaptop X421JAY_X413JA | 1         | 2.08%   |
| ASUS VivoBook 15_ASUS Laptop X560UD     | 1         | 2.08%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Dell Latitude     | 4         | 8.33%   |
| Dell Inspiron     | 4         | 8.33%   |
| Lenovo ThinkPad   | 3         | 6.25%   |
| HP Pavilion       | 3         | 6.25%   |
| Acer Aspire       | 3         | 6.25%   |
| Toshiba Satellite | 2         | 4.17%   |
| Lenovo IdeaPad    | 2         | 4.17%   |
| HP Laptop         | 2         | 4.17%   |
| HP 250            | 2         | 4.17%   |
| ASUS VivoBook     | 2         | 4.17%   |
| Samsung 355V4C    | 1         | 2.08%   |
| MSI GS60          | 1         | 2.08%   |
| Lenovo G480       | 1         | 2.08%   |
| Lenovo 100-14IBY  | 1         | 2.08%   |
| HUAWEI MACH-WX9   | 1         | 2.08%   |
| HP ProBook        | 1         | 2.08%   |
| HP Presario       | 1         | 2.08%   |
| HP OMEN           | 1         | 2.08%   |
| HP Notebook       | 1         | 2.08%   |
| HP EliteBook      | 1         | 2.08%   |
| Google Banon      | 1         | 2.08%   |
| Framework Laptop  | 1         | 2.08%   |
| Dell XPS          | 1         | 2.08%   |
| Dell System       | 1         | 2.08%   |
| Dell G7           | 1         | 2.08%   |
| ASUS X555QG       | 1         | 2.08%   |
| ASUS TP300LA      | 1         | 2.08%   |
| ASUS S551LN       | 1         | 2.08%   |
| ASUS G550JK       | 1         | 2.08%   |
| Acer Predator     | 1         | 2.08%   |
| Unknown           | 1         | 2.08%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2014 | 9         | 18.75%  |
| 2018 | 6         | 12.5%   |
| 2010 | 5         | 10.42%  |
| 2012 | 4         | 8.33%   |
| 2011 | 4         | 8.33%   |
| 2021 | 3         | 6.25%   |
| 2020 | 3         | 6.25%   |
| 2013 | 3         | 6.25%   |
| 2008 | 3         | 6.25%   |
| 2017 | 2         | 4.17%   |
| 2016 | 2         | 4.17%   |
| 2015 | 2         | 4.17%   |
| 2019 | 1         | 2.08%   |
| 2009 | 1         | 2.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 48        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 43        | 87.76%  |
| Enabled  | 6         | 12.24%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 47        | 97.92%  |
| Yes  | 1         | 2.08%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 14        | 29.17%  |
| 3.01-4.0   | 14        | 29.17%  |
| 16.01-24.0 | 10        | 20.83%  |
| 8.01-16.0  | 6         | 12.5%   |
| 32.01-64.0 | 2         | 4.17%   |
| 2.01-3.0   | 1         | 2.08%   |
| 1.01-2.0   | 1         | 2.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 20        | 40%     |
| 1.01-2.0  | 19        | 38%     |
| 4.01-8.0  | 5         | 10%     |
| 3.01-4.0  | 5         | 10%     |
| 8.01-16.0 | 1         | 2%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 35        | 72.92%  |
| 2      | 13        | 27.08%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 29        | 60.42%  |
| Yes       | 19        | 39.58%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 41        | 85.42%  |
| No        | 7         | 14.58%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 48        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 79.17%  |
| No        | 10        | 20.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| Brazil       | 8         | 16.33%  |
| USA          | 6         | 12.24%  |
| Germany      | 4         | 8.16%   |
| India        | 3         | 6.12%   |
| Argentina    | 3         | 6.12%   |
| Ukraine      | 2         | 4.08%   |
| Spain        | 2         | 4.08%   |
| Mexico       | 2         | 4.08%   |
| Hungary      | 2         | 4.08%   |
| France       | 2         | 4.08%   |
| Thailand     | 1         | 2.04%   |
| South Africa | 1         | 2.04%   |
| Serbia       | 1         | 2.04%   |
| Portugal     | 1         | 2.04%   |
| Poland       | 1         | 2.04%   |
| Netherlands  | 1         | 2.04%   |
| Jamaica      | 1         | 2.04%   |
| Indonesia    | 1         | 2.04%   |
| Hong Kong    | 1         | 2.04%   |
| Czechia      | 1         | 2.04%   |
| Costa Rica   | 1         | 2.04%   |
| Colombia     | 1         | 2.04%   |
| Austria      | 1         | 2.04%   |
| Australia    | 1         | 2.04%   |
| Algeria      | 1         | 2.04%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Budapest                    | 2         | 4.08%   |
| Zaporizhzhia                | 1         | 2.04%   |
| Zapopan                     | 1         | 2.04%   |
| Wolfheze                    | 1         | 2.04%   |
| Villahermosa                | 1         | 2.04%   |
| Vienna                      | 1         | 2.04%   |
| Tuen Mun                    | 1         | 2.04%   |
| Tiete                       | 1         | 2.04%   |
| Surabaya                    | 1         | 2.04%   |
| Siquirres                   | 1         | 2.04%   |
| Seville                     | 1         | 2.04%   |
| Sao Jose do Rio Preto       | 1         | 2.04%   |
| San Nicolás de los Arroyos | 1         | 2.04%   |
| Salvador                    | 1         | 2.04%   |
| Ratingen                    | 1         | 2.04%   |
| Quilmes                     | 1         | 2.04%   |
| Patna                       | 1         | 2.04%   |
| Paris                       | 1         | 2.04%   |
| Ostrava                     | 1         | 2.04%   |
| Nanterre                    | 1         | 2.04%   |
| Nakhon Pathom               | 1         | 2.04%   |
| Midlothian                  | 1         | 2.04%   |
| Melbourne                   | 1         | 2.04%   |
| Manaus                      | 1         | 2.04%   |
| Maitland                    | 1         | 2.04%   |
| Luhansk                     | 1         | 2.04%   |
| Lisbon                      | 1         | 2.04%   |
| Krakow                      | 1         | 2.04%   |
| Kingston                    | 1         | 2.04%   |
| Johannesburg                | 1         | 2.04%   |
| Decatur                     | 1         | 2.04%   |
| Dearborn Heights            | 1         | 2.04%   |
| Charlottesville             | 1         | 2.04%   |
| Caxias                      | 1         | 2.04%   |
| Capim Grosso                | 1         | 2.04%   |
| Brooklyn                    | 1         | 2.04%   |
| Bonn                        | 1         | 2.04%   |
| Bogotá                     | 1         | 2.04%   |
| Bhopal                      | 1         | 2.04%   |
| Betim                       | 1         | 2.04%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 13     | 20.34%  |
| WDC                 | 8         | 8      | 13.56%  |
| Toshiba             | 8         | 8      | 13.56%  |
| Samsung Electronics | 6         | 6      | 10.17%  |
| Micron Technology   | 3         | 3      | 5.08%   |
| Kingston            | 3         | 3      | 5.08%   |
| HGST                | 3         | 3      | 5.08%   |
| Crucial             | 3         | 3      | 5.08%   |
| Unknown             | 2         | 2      | 3.39%   |
| SanDisk             | 2         | 2      | 3.39%   |
| Fujitsu             | 2         | 2      | 3.39%   |
| XrayDisk            | 1         | 1      | 1.69%   |
| SK hynix            | 1         | 3      | 1.69%   |
| KingSpec            | 1         | 1      | 1.69%   |
| Intenso             | 1         | 1      | 1.69%   |
| Hitachi             | 1         | 1      | 1.69%   |
| China               | 1         | 1      | 1.69%   |
| A-DATA Technology   | 1         | 1      | 1.69%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB  | 3         | 5%      |
| Toshiba MQ01ABF050 500GB            | 2         | 3.33%   |
| Seagate ST9500325AS 500GB           | 2         | 3.33%   |
| Seagate ST2000LM007-1R8174 2TB      | 2         | 3.33%   |
| XrayDisk 240GB                      | 1         | 1.67%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1         | 1.67%   |
| WDC WDS100T3X0C-00SJG0 1TB          | 1         | 1.67%   |
| WDC WD5000LPCX-24VHAT0 500GB        | 1         | 1.67%   |
| WDC WD20SPZX-00CRAT0 2TB            | 1         | 1.67%   |
| WDC WD1200BEVS-00UST0 120GB         | 1         | 1.67%   |
| WDC WD10SPZX-75Z10T2 1TB            | 1         | 1.67%   |
| WDC WD10SPZX-24Z10 1TB              | 1         | 1.67%   |
| WDC WD10JPLX-00MBPT0 1TB            | 1         | 1.67%   |
| Unknown SD16G  16GB                 | 1         | 1.67%   |
| Unknown HAG4a2  16GB                | 1         | 1.67%   |
| Toshiba NVMe SSD Drive 256GB        | 1         | 1.67%   |
| Toshiba MQ04ABF100 1TB              | 1         | 1.67%   |
| Toshiba MQ01ABD100 1TB              | 1         | 1.67%   |
| Toshiba MQ01ABD075 752GB            | 1         | 1.67%   |
| Toshiba MK7559GSXP 752GB            | 1         | 1.67%   |
| Toshiba MK5059GSXP 500GB            | 1         | 1.67%   |
| SK hynix PC401 NVMe 1TB             | 1         | 1.67%   |
| SK hynix NVMe SSD Drive 1024GB      | 1         | 1.67%   |
| Seagate ST500LT015-1DJ142 500GB     | 1         | 1.67%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1.67%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1.67%   |
| Seagate ST1000LM014-1EJ164 1TB      | 1         | 1.67%   |
| Seagate NVMe SSD Drive 250GB        | 1         | 1.67%   |
| SanDisk Ultra II 480GB SSD          | 1         | 1.67%   |
| SanDisk SSD PLUS 240GB              | 1         | 1.67%   |
| Samsung SSD 850 PRO 256GB           | 1         | 1.67%   |
| Samsung SSD 850 EVO mSATA 1TB       | 1         | 1.67%   |
| Samsung NVMe SSD Drive 512GB        | 1         | 1.67%   |
| Samsung MZVLQ256HAJD-00000 256GB    | 1         | 1.67%   |
| Samsung MZALQ512HALU-000L1 512GB    | 1         | 1.67%   |
| Samsung HM321HI 320GB               | 1         | 1.67%   |
| Micron MTFDHBA1T0TDV-1AZ1AABHA 1TB  | 1         | 1.67%   |
| Micron 1100_MTFDDAV512TBN 512GB SSD | 1         | 1.67%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD | 1         | 1.67%   |
| Kingston SV300S37A120G 120GB SSD    | 1         | 1.67%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 12     | 35.48%  |
| Toshiba             | 7         | 7      | 22.58%  |
| WDC                 | 6         | 6      | 19.35%  |
| HGST                | 3         | 3      | 9.68%   |
| Fujitsu             | 2         | 2      | 6.45%   |
| Samsung Electronics | 1         | 1      | 3.23%   |
| Hitachi             | 1         | 1      | 3.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 3         | 3      | 18.75%  |
| SanDisk             | 2         | 2      | 12.5%   |
| Samsung Electronics | 2         | 2      | 12.5%   |
| Micron Technology   | 2         | 2      | 12.5%   |
| Crucial             | 2         | 2      | 12.5%   |
| WDC                 | 1         | 1      | 6.25%   |
| KingSpec            | 1         | 1      | 6.25%   |
| Intenso             | 1         | 1      | 6.25%   |
| China               | 1         | 1      | 6.25%   |
| A-DATA Technology   | 1         | 1      | 6.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 29        | 32     | 52.73%  |
| SSD     | 15        | 16     | 27.27%  |
| NVMe    | 8         | 11     | 14.55%  |
| MMC     | 2         | 2      | 3.64%   |
| Unknown | 1         | 1      | 1.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 39        | 49     | 79.59%  |
| NVMe | 8         | 11     | 16.33%  |
| MMC  | 2         | 2      | 4.08%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 26        | 28     | 57.78%  |
| 0.51-1.0   | 16        | 17     | 35.56%  |
| 1.01-2.0   | 3         | 3      | 6.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 21        | 43.75%  |
| 251-500    | 9         | 18.75%  |
| 501-1000   | 7         | 14.58%  |
| 51-100     | 4         | 8.33%   |
| 1-20       | 3         | 6.25%   |
| 1001-2000  | 2         | 4.17%   |
| 21-50      | 1         | 2.08%   |
| Unknown    | 1         | 2.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 24        | 48%     |
| 21-50     | 11        | 22%     |
| 101-250   | 6         | 12%     |
| 51-100    | 4         | 8%      |
| 251-500   | 3         | 6%      |
| 1001-2000 | 1         | 2%      |
| Unknown   | 1         | 2%      |

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
| Detected | 35        | 43     | 70%     |
| Works    | 14        | 18     | 28%     |
| Malfunc  | 1         | 1      | 2%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 40        | 76.92%  |
| Samsung Electronics              | 3         | 5.77%   |
| AMD                              | 2         | 3.85%   |
| Toshiba America Info Systems     | 1         | 1.92%   |
| SK hynix                         | 1         | 1.92%   |
| Silicon Integrated Systems [SiS] | 1         | 1.92%   |
| Seagate Technology               | 1         | 1.92%   |
| SanDisk                          | 1         | 1.92%   |
| Micron/Crucial Technology        | 1         | 1.92%   |
| Micron Technology                | 1         | 1.92%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 9         | 16.67%  |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 7.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 7.41%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 5.56%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 5.56%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 5.56%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 5.56%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 5.56%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 5.56%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 2         | 3.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 3.7%    |
| AMD FCH SATA Controller [AHCI mode]                                            | 2         | 3.7%    |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 1         | 1.85%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 1         | 1.85%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 1         | 1.85%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 1         | 1.85%   |
| Seagate FireCuda/IronWolf 510 SSD                                              | 1         | 1.85%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 1         | 1.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 1.85%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1         | 1.85%   |
| Micron 2300 NVMe SSD [Santana]                                                 | 1         | 1.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 1         | 1.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 1         | 1.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.85%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 33        | 63.46%  |
| RAID | 9         | 17.31%  |
| NVMe | 8         | 15.38%  |
| IDE  | 2         | 3.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 46        | 95.83%  |
| AMD    | 2         | 4.17%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz               | 3         | 6.25%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 2         | 4.17%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 2         | 4.17%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 4.17%   |
| Intel Core i5-2410M CPU @ 2.30GHz               | 2         | 4.17%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz              | 2         | 4.17%   |
| Intel Core i3 CPU M 370 @ 2.40GHz               | 2         | 4.17%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 2         | 4.17%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz          | 1         | 2.08%   |
| Intel Pentium CPU B980 @ 2.40GHz                | 1         | 2.08%   |
| Intel Core i9-8950HK CPU @ 2.90GHz              | 1         | 2.08%   |
| Intel Core i7-5600U CPU @ 2.60GHz               | 1         | 2.08%   |
| Intel Core i7-5500U CPU @ 2.40GHz               | 1         | 2.08%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz              | 1         | 2.08%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz              | 1         | 2.08%   |
| Intel Core i7-4510U CPU @ 2.00GHz               | 1         | 2.08%   |
| Intel Core i7-4500U CPU @ 1.80GHz               | 1         | 2.08%   |
| Intel Core i7-2670QM CPU @ 2.20GHz              | 1         | 2.08%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 1         | 2.08%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 1         | 2.08%   |
| Intel Core i5-4310U CPU @ 2.00GHz               | 1         | 2.08%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 1         | 2.08%   |
| Intel Core i5-3360M CPU @ 2.80GHz               | 1         | 2.08%   |
| Intel Core i5-3337U CPU @ 1.80GHz               | 1         | 2.08%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 1         | 2.08%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 1         | 2.08%   |
| Intel Core i5-2430M CPU @ 2.40GHz               | 1         | 2.08%   |
| Intel Core i5 CPU M 540 @ 2.53GHz               | 1         | 2.08%   |
| Intel Core i3-7020U CPU @ 2.30GHz               | 1         | 2.08%   |
| Intel Core i3-5020U CPU @ 2.20GHz               | 1         | 2.08%   |
| Intel Core i3-5005U CPU @ 2.00GHz               | 1         | 2.08%   |
| Intel Core i3-4030U CPU @ 1.90GHz               | 1         | 2.08%   |
| Intel Core i3 CPU M 380 @ 2.53GHz               | 1         | 2.08%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz            | 1         | 2.08%   |
| Intel Core 2 Duo CPU L9400 @ 1.86GHz            | 1         | 2.08%   |
| Intel Celeron Dual-Core CPU T3500 @ 2.10GHz     | 1         | 2.08%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 1         | 2.08%   |
| AMD A8-4500M APU with Radeon HD Graphics        | 1         | 2.08%   |
| AMD A10-9620P RADEON R5, 10 COMPUTE CORES 4C+6G | 1         | 2.08%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 13        | 27.08%  |
| Intel Core i7           | 12        | 25%     |
| Intel Core i3           | 9         | 18.75%  |
| Intel Celeron           | 4         | 8.33%   |
| Other                   | 2         | 4.17%   |
| Intel Core 2 Duo        | 2         | 4.17%   |
| Intel Pentium Dual      | 1         | 2.08%   |
| Intel Pentium           | 1         | 2.08%   |
| Intel Core i9           | 1         | 2.08%   |
| Intel Celeron Dual-Core | 1         | 2.08%   |
| AMD A8                  | 1         | 2.08%   |
| AMD A10                 | 1         | 2.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 36        | 75%     |
| 4      | 8         | 16.67%  |
| 6      | 4         | 8.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 48        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 39        | 81.25%  |
| 1      | 9         | 18.75%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 48        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 13        | 26.53%  |
| 0x206a7    | 6         | 12.24%  |
| 0x40651    | 4         | 8.16%   |
| 0x906ea    | 3         | 6.12%   |
| 0x806ea    | 3         | 6.12%   |
| 0x806c1    | 2         | 4.08%   |
| 0x706e5    | 2         | 4.08%   |
| 0x306d4    | 2         | 4.08%   |
| 0x306a9    | 2         | 4.08%   |
| 0x20655    | 2         | 4.08%   |
| 0x1067a    | 2         | 4.08%   |
| 0xa0652    | 1         | 2.04%   |
| 0x806e9    | 1         | 2.04%   |
| 0x6fd      | 1         | 2.04%   |
| 0x406c4    | 1         | 2.04%   |
| 0x306c3    | 1         | 2.04%   |
| 0x30678    | 1         | 2.04%   |
| 0x10676    | 1         | 2.04%   |
| 0x0600611a | 1         | 2.04%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 9         | 18.75%  |
| Haswell     | 7         | 14.58%  |
| SandyBridge | 6         | 12.5%   |
| Westmere    | 4         | 8.33%   |
| Silvermont  | 4         | 8.33%   |
| Broadwell   | 4         | 8.33%   |
| Penryn      | 3         | 6.25%   |
| IvyBridge   | 3         | 6.25%   |
| TigerLake   | 2         | 4.17%   |
| IceLake     | 2         | 4.17%   |
| Piledriver  | 1         | 2.08%   |
| Excavator   | 1         | 2.08%   |
| Core        | 1         | 2.08%   |
| CometLake   | 1         | 2.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 44        | 68.75%  |
| Nvidia                           | 14        | 21.88%  |
| AMD                              | 5         | 7.81%   |
| Silicon Integrated Systems [SiS] | 1         | 1.56%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 8.96%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 7.46%   |
| Intel HD Graphics 5500                                                                   | 4         | 5.97%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 5.97%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 4.48%   |
| Intel UHD Graphics 620                                                                   | 3         | 4.48%   |
| Intel HD Graphics 620                                                                    | 3         | 4.48%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 4.48%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 4.48%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 4.48%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 2.99%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 2.99%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 2.99%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 2.99%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 2.99%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 1.49%   |
| Nvidia TU104BM [GeForce RTX 2070 SUPER Mobile / Max-Q]                                   | 1         | 1.49%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 1.49%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 1.49%   |
| Nvidia GM204M [GeForce GTX 960 OEM / 970M]                                               | 1         | 1.49%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.49%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 1.49%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 1.49%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 1.49%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 1.49%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.49%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.49%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 1         | 1.49%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 1.49%   |
| AMD Trinity [Radeon HD 7640G]                                                            | 1         | 1.49%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 1.49%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 1.49%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 1.49%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 1.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 28        | 58.33%  |
| Intel + Nvidia | 13        | 27.08%  |
| Intel + AMD    | 3         | 6.25%   |
| 2 x AMD        | 2         | 4.17%   |
| 1 x SiS        | 1         | 2.08%   |
| 1 x Nvidia     | 1         | 2.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 37        | 75.51%  |
| Proprietary | 9         | 18.37%  |
| Unknown     | 3         | 6.12%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 34        | 69.39%  |
| 3.01-4.0   | 6         | 12.24%  |
| 1.01-2.0   | 5         | 10.2%   |
| 0.51-1.0   | 2         | 4.08%   |
| 7.01-8.0   | 1         | 2.04%   |
| 2.01-3.0   | 1         | 2.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 14        | 26.42%  |
| LG Display              | 9         | 16.98%  |
| AU Optronics            | 9         | 16.98%  |
| BOE                     | 8         | 15.09%  |
| Chimei Innolux          | 2         | 3.77%   |
| Chi Mei Optoelectronics | 2         | 3.77%   |
| Sharp                   | 1         | 1.89%   |
| MSI                     | 1         | 1.89%   |
| Lenovo                  | 1         | 1.89%   |
| JDI                     | 1         | 1.89%   |
| InfoVision              | 1         | 1.89%   |
| Goldstar                | 1         | 1.89%   |
| Eizo                    | 1         | 1.89%   |
| AOC                     | 1         | 1.89%   |
| Ancor Communications    | 1         | 1.89%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch    | 2         | 3.64%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                  | 1         | 1.82%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch        | 1         | 1.82%   |
| Samsung Electronics T22B300 SAM092D 1920x1080 477x268mm 21.5-inch        | 1         | 1.82%   |
| Samsung Electronics S27E500 SAM0D0D 1920x1080 598x336mm 27.0-inch        | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SEC454C 1366x768 309x174mm 14.0-inch     | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch     | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SEC3942 1280x800 261x163mm 12.1-inch     | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 303x190mm 14.1-inch     | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 309x174mm 14.0-inch     | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch     | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch     | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SDC4146 1366x768 344x194mm 15.5-inch     | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SDC344A 1366x768 344x194mm 15.5-inch     | 1         | 1.82%   |
| MSI MAG341CQ MSI1462 3440x1440 797x333mm 34.0-inch                       | 1         | 1.82%   |
| LG Display LCD Monitor LGD0611 1920x1080 382x215mm 17.3-inch             | 1         | 1.82%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch             | 1         | 1.82%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch             | 1         | 1.82%   |
| LG Display LCD Monitor LGD046B 1366x768 344x194mm 15.5-inch              | 1         | 1.82%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 1         | 1.82%   |
| LG Display LCD Monitor LGD037C 1366x768 310x174mm 14.0-inch              | 1         | 1.82%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 1         | 1.82%   |
| LG Display LCD Monitor LGD02AC 1366x768 344x194mm 15.5-inch              | 1         | 1.82%   |
| LG Display LCD Monitor LGD024F 1280x800 260x160mm 12.0-inch              | 1         | 1.82%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 1         | 1.82%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                    | 1         | 1.82%   |
| InfoVision LCD Monitor IVO057C 1366x768 309x174mm 14.0-inch              | 1         | 1.82%   |
| Goldstar M2380A GSM57EE 1920x1080 509x286mm 23.0-inch                    | 1         | 1.82%   |
| Eizo EV2450 ENC2532 1920x1080 528x297mm 23.9-inch                        | 1         | 1.82%   |
| Eizo EV2450 ENC2531 1920x1080 528x297mm 23.9-inch                        | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN1489 1366x768 309x173mm 13.9-inch          | 1         | 1.82%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 1         | 1.82%   |
| Chi Mei Optoelectronics LCD Monitor CMO1469 1366x768 309x174mm 14.0-inch | 1         | 1.82%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 1         | 1.82%   |
| BOE LCD Monitor BOE0897 1366x768 344x194mm 15.5-inch                     | 1         | 1.82%   |
| BOE LCD Monitor BOE085E 1920x1080 344x194mm 15.5-inch                    | 1         | 1.82%   |
| BOE LCD Monitor BOE06C6 1920x1080 344x194mm 15.5-inch                    | 1         | 1.82%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 1         | 1.82%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 25        | 47.17%  |
| 1920x1080 (FHD)  | 18        | 33.96%  |
| 1600x900 (HD+)   | 2         | 3.77%   |
| 1440x900 (WXGA+) | 2         | 3.77%   |
| 1280x800 (WXGA)  | 2         | 3.77%   |
| 3840x2160 (4K)   | 1         | 1.89%   |
| 3440x1440        | 1         | 1.89%   |
| 3000x2000        | 1         | 1.89%   |
| 2256x1504        | 1         | 1.89%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 26        | 48.15%  |
| 14     | 10        | 18.52%  |
| 17     | 4         | 7.41%   |
| 13     | 4         | 7.41%   |
| 23     | 2         | 3.7%    |
| 12     | 2         | 3.7%    |
| 34     | 1         | 1.85%   |
| 31     | 1         | 1.85%   |
| 27     | 1         | 1.85%   |
| 24     | 1         | 1.85%   |
| 21     | 1         | 1.85%   |
| 19     | 1         | 1.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 35        | 64.81%  |
| 351-400     | 6         | 11.11%  |
| 201-300     | 5         | 9.26%   |
| 501-600     | 4         | 7.41%   |
| 401-500     | 2         | 3.7%    |
| 701-800     | 1         | 1.85%   |
| 601-700     | 1         | 1.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 42        | 84%     |
| 16/10 | 4         | 8%      |
| 3/2   | 3         | 6%      |
| 21/9  | 1         | 2%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 26        | 48.15%  |
| 81-90          | 13        | 24.07%  |
| 201-250        | 4         | 7.41%   |
| 121-130        | 4         | 7.41%   |
| 61-70          | 2         | 3.7%    |
| 351-500        | 2         | 3.7%    |
| 71-80          | 1         | 1.85%   |
| 301-350        | 1         | 1.85%   |
| 151-200        | 1         | 1.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 26        | 49.06%  |
| 121-160       | 17        | 32.08%  |
| 51-100        | 8         | 15.09%  |
| More than 240 | 1         | 1.89%   |
| 161-240       | 1         | 1.89%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 38        | 79.17%  |
| 2     | 7         | 14.58%  |
| 0     | 2         | 4.17%   |
| 3     | 1         | 2.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 24        | 31.17%  |
| Intel                            | 23        | 29.87%  |
| Qualcomm Atheros                 | 16        | 20.78%  |
| Broadcom                         | 5         | 6.49%   |
| Ralink                           | 2         | 2.6%    |
| Xiaomi                           | 1         | 1.3%    |
| Silicon Integrated Systems [SiS] | 1         | 1.3%    |
| Ralink Technology                | 1         | 1.3%    |
| Marvell Technology Group         | 1         | 1.3%    |
| Dell                             | 1         | 1.3%    |
| Broadcom Limited                 | 1         | 1.3%    |
| ASUSTek Computer                 | 1         | 1.3%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 15        | 16.13%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 7         | 7.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 5.38%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 4.3%    |
| Intel Wireless 7265                                                     | 3         | 3.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 3.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3         | 3.23%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 2.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 2.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 2.15%   |
| Intel Wireless 3160                                                     | 2         | 2.15%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 2.15%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 2.15%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 2.15%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 1.08%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 1.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.08%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 1.08%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 1.08%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.08%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.08%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 1         | 1.08%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller               | 1         | 1.08%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 1         | 1.08%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 1.08%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                              | 1         | 1.08%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1         | 1.08%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.08%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 1         | 1.08%   |
| Intel Wireless 8265 / 8275                                              | 1         | 1.08%   |
| Intel Wireless 7260                                                     | 1         | 1.08%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 1         | 1.08%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 1.08%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 1.08%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 1.08%   |
| Intel Ethernet Connection I218-LM                                       | 1         | 1.08%   |
| Intel Ethernet Connection (4) I219-V                                    | 1         | 1.08%   |
| Intel Ethernet Connection (3) I218-LM                                   | 1         | 1.08%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 22        | 43.14%  |
| Qualcomm Atheros      | 13        | 25.49%  |
| Realtek Semiconductor | 6         | 11.76%  |
| Broadcom              | 4         | 7.84%   |
| Ralink                | 2         | 3.92%   |
| Ralink Technology     | 1         | 1.96%   |
| Dell                  | 1         | 1.96%   |
| Broadcom Limited      | 1         | 1.96%   |
| ASUSTek Computer      | 1         | 1.96%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 9.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 7.84%   |
| Intel Wireless 7265                                                     | 3         | 5.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 5.88%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 3.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 3.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 3.92%   |
| Intel Wireless 3160                                                     | 2         | 3.92%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 3.92%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 3.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 3.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.96%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.96%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 1.96%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.96%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.96%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.96%   |
| Intel Wireless 8265 / 8275                                              | 1         | 1.96%   |
| Intel Wireless 7260                                                     | 1         | 1.96%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 1         | 1.96%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 1.96%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 1.96%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 1.96%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 1.96%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 1.96%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 1.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1         | 1.96%   |
| Dell Wireless 5630 (EVDO-HSPA) Mobile Broadband Mini-Card               | 1         | 1.96%   |
| Broadcom Limited BCM4311 802.11a/b/g                                    | 1         | 1.96%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 1.96%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 1.96%   |
| ASUS USB-AC56 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU]     | 1         | 1.96%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 23        | 54.76%  |
| Intel                            | 8         | 19.05%  |
| Qualcomm Atheros                 | 6         | 14.29%  |
| Broadcom                         | 2         | 4.76%   |
| Xiaomi                           | 1         | 2.38%   |
| Silicon Integrated Systems [SiS] | 1         | 2.38%   |
| Marvell Technology Group         | 1         | 2.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 15        | 35.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 7         | 16.67%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 7.14%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 2.38%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1         | 2.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1         | 2.38%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 2.38%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1         | 2.38%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 2.38%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 2.38%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 1         | 2.38%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 2.38%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 2.38%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 2.38%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 2.38%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 2.38%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 2.38%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 2.38%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 1         | 2.38%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 2.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 48        | 53.93%  |
| Ethernet | 41        | 46.07%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 44        | 80%     |
| Ethernet | 11        | 20%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 40        | 83.33%  |
| 1     | 8         | 16.67%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 40        | 83.33%  |
| Yes  | 8         | 16.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 15        | 39.47%  |
| Qualcomm Atheros Communications | 6         | 15.79%  |
| Realtek Semiconductor           | 4         | 10.53%  |
| IMC Networks                    | 3         | 7.89%   |
| Dell                            | 2         | 5.26%   |
| Broadcom                        | 2         | 5.26%   |
| Toshiba                         | 1         | 2.63%   |
| Ralink Technology               | 1         | 2.63%   |
| Ralink                          | 1         | 2.63%   |
| Hewlett-Packard                 | 1         | 2.63%   |
| Foxconn / Hon Hai               | 1         | 2.63%   |
| Cambridge Silicon Radio         | 1         | 2.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 8         | 21.05%  |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 7.89%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 5.26%   |
| Realtek Bluetooth Radio                             | 2         | 5.26%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 5.26%   |
| Intel Bluetooth Device                              | 2         | 5.26%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 5.26%   |
| Intel AX201 Bluetooth                               | 2         | 5.26%   |
| IMC Networks Bluetooth Radio                        | 2         | 5.26%   |
| Toshiba Bluetooth Device                            | 1         | 2.63%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 2.63%   |
| Ralink RT3290 Bluetooth                             | 1         | 2.63%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 2.63%   |
| Intel AX210 Bluetooth                               | 1         | 2.63%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 2.63%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 2.63%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 2.63%   |
| Dell Wireless 355 Bluetooth                         | 1         | 2.63%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 2.63%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.63%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 2.63%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 2.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 45        | 81.82%  |
| Nvidia                                          | 4         | 7.27%   |
| AMD                                             | 2         | 3.64%   |
| Silicon Integrated Systems [SiS]                | 1         | 1.82%   |
| Razer USA                                       | 1         | 1.82%   |
| Logitech                                        | 1         | 1.82%   |
| Licensed by Sony Computer Entertainment America | 1         | 1.82%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 6         | 8.82%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 7.35%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 7.35%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 7.35%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 5.88%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 5.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 5.88%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 5.88%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 4.41%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 4.41%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 2.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 2.94%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 2.94%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 2.94%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 2.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 2.94%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 1.47%   |
| Razer USA Kraken 7.1 V2                                                                           | 1         | 1.47%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 1.47%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.47%   |
| Logitech Speaker Lapdesk N700                                                                     | 1         | 1.47%   |
| Licensed by Sony Computer Entertainment America Wireless Stereo Headset                           | 1         | 1.47%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.47%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.47%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 1.47%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.47%   |
| AMD FCH Azalia Controller                                                                         | 1         | 1.47%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 1.47%   |

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
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s  | 1         | 4%      |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s     | 1         | 4%      |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s     | 1         | 4%      |
| SK hynix RAM H9CCNNN8GTMLAR-NUD 2GB LPDDR3 1600MT/s        | 1         | 4%      |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s   | 1         | 4%      |
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
| Chicony Electronics           | 11        | 26.19%  |
| Microdia                      | 6         | 14.29%  |
| Suyin                         | 4         | 9.52%   |
| Sunplus Innovation Technology | 4         | 9.52%   |
| Realtek Semiconductor         | 3         | 7.14%   |
| Quanta                        | 3         | 7.14%   |
| IMC Networks                  | 3         | 7.14%   |
| Silicon Motion                | 2         | 4.76%   |
| Bison Electronics             | 2         | 4.76%   |
| Acer                          | 2         | 4.76%   |
| Syntek                        | 1         | 2.38%   |
| Importek                      | 1         | 2.38%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                   | 2         | 4.76%   |
| Microdia Integrated_Webcam_HD                  | 2         | 4.76%   |
| Microdia Integrated Webcam                     | 2         | 4.76%   |
| Chicony HP Webcam                              | 2         | 4.76%   |
| Syntek Lenovo EasyCamera                       | 1         | 2.38%   |
| Suyin WebCam                                   | 1         | 2.38%   |
| Suyin HP Truevision HD                         | 1         | 2.38%   |
| Suyin Asus Integrated Webcam                   | 1         | 2.38%   |
| Suyin 1.3M HD WebCam                           | 1         | 2.38%   |
| Sunplus Laptop_Integrated_Webcam_HD            | 1         | 2.38%   |
| Sunplus HD WebCam                              | 1         | 2.38%   |
| Silicon Motion WebCam SC-13HDL11939N           | 1         | 2.38%   |
| Silicon Motion HP Webcam-101 Integrated Camera | 1         | 2.38%   |
| Realtek USB2.0 VGA UVC WebCam                  | 1         | 2.38%   |
| Realtek Laptop Camera                          | 1         | 2.38%   |
| Realtek HP Truevision HD                       | 1         | 2.38%   |
| Quanta Laptop_Integrated_Webcam_2HDM           | 1         | 2.38%   |
| Quanta HP TrueVision HD Camera                 | 1         | 2.38%   |
| Quanta HD Webcam                               | 1         | 2.38%   |
| Microdia Sonix 1.3 MP Laptop Integrated Webcam | 1         | 2.38%   |
| Microdia Laptop_Integrated_Webcam_0.3M         | 1         | 2.38%   |
| Importek HP Truevision HD Integrated Webcam    | 1         | 2.38%   |
| IMC Networks USB2.0 VGA UVC WebCam             | 1         | 2.38%   |
| IMC Networks USB2.0 UVC HD Webcam              | 1         | 2.38%   |
| IMC Networks USB2.0 HD UVC WebCam              | 1         | 2.38%   |
| Chicony USB 2.0 Camera                         | 1         | 2.38%   |
| Chicony TOSHIBA Web Camera - HD                | 1         | 2.38%   |
| Chicony Lenovo EasyCamera                      | 1         | 2.38%   |
| Chicony Integrated Camera                      | 1         | 2.38%   |
| Chicony HP Wide Vision HD Camera               | 1         | 2.38%   |
| Chicony HP Webcam [2 MP Macro]                 | 1         | 2.38%   |
| Chicony HP HD Camera                           | 1         | 2.38%   |
| Chicony HD WebCam                              | 1         | 2.38%   |
| Chicony EasyCamera                             | 1         | 2.38%   |
| Bison HP TrueVision HD Webcam                  | 1         | 2.38%   |
| Bison EasyCamera                               | 1         | 2.38%   |
| Acer Integrated Camera                         | 1         | 2.38%   |
| Acer BisonCam, NB Pro                          | 1         | 2.38%   |

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
| Broadcom | 2         | 66.67%  |
| Upek     | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 66.67%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 33        | 68.75%  |
| 1     | 14        | 29.17%  |
| 2     | 1         | 2.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 5         | 35.71%  |
| Graphics card      | 4         | 28.57%  |
| Chipcard           | 3         | 21.43%  |
| Net/ethernet       | 1         | 7.14%   |
| Bluetooth          | 1         | 7.14%   |

