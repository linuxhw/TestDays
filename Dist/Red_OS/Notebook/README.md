Red OS - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Red OS.

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

Total: 57

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Digma         | EVE 15 P417 ES5063EW        | [a584c678b5](https://linux-hardware.org/?probe=a584c678b5) | Jul 27, 2022 |
| Digma         | EVE 15 C407 ES5054EW        | [4fd01756b2](https://linux-hardware.org/?probe=4fd01756b2) | Jul 27, 2022 |
| Digma         | EVE 15 C407 ES5054EW        | [008b02cc92](https://linux-hardware.org/?probe=008b02cc92) | Jul 26, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [413949a727](https://linux-hardware.org/?probe=413949a727) | Jul 25, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [2ea5a4f753](https://linux-hardware.org/?probe=2ea5a4f753) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [3bfcedd5c8](https://linux-hardware.org/?probe=3bfcedd5c8) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [c49282206c](https://linux-hardware.org/?probe=c49282206c) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [d598c4587d](https://linux-hardware.org/?probe=d598c4587d) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [5b1e962751](https://linux-hardware.org/?probe=5b1e962751) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [4e120b3b63](https://linux-hardware.org/?probe=4e120b3b63) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [2d5bedf224](https://linux-hardware.org/?probe=2d5bedf224) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [297ce5144e](https://linux-hardware.org/?probe=297ce5144e) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [84b7cd1115](https://linux-hardware.org/?probe=84b7cd1115) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [a92b6c5d73](https://linux-hardware.org/?probe=a92b6c5d73) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [51ebd271c8](https://linux-hardware.org/?probe=51ebd271c8) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [44ad7f7d47](https://linux-hardware.org/?probe=44ad7f7d47) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [49068a26b5](https://linux-hardware.org/?probe=49068a26b5) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [62ce596bf3](https://linux-hardware.org/?probe=62ce596bf3) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [812db8ad6f](https://linux-hardware.org/?probe=812db8ad6f) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [d4c2b5ffad](https://linux-hardware.org/?probe=d4c2b5ffad) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [4c0179b60e](https://linux-hardware.org/?probe=4c0179b60e) | Jul 22, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [8601888983](https://linux-hardware.org/?probe=8601888983) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [1d505390d6](https://linux-hardware.org/?probe=1d505390d6) | Jul 22, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [d481776a74](https://linux-hardware.org/?probe=d481776a74) | Jul 21, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [ef738973d3](https://linux-hardware.org/?probe=ef738973d3) | Jul 20, 2022 |
| HONOR         | NBR-WAX9                    | [5b3340311a](https://linux-hardware.org/?probe=5b3340311a) | Jul 20, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [154c254eac](https://linux-hardware.org/?probe=154c254eac) | Jul 19, 2022 |
| Gigabyte      | G5 GD                       | [60921a7ff6](https://linux-hardware.org/?probe=60921a7ff6) | Jul 19, 2022 |
| Gigabyte      | G5 GD                       | [c24f8b4ba6](https://linux-hardware.org/?probe=c24f8b4ba6) | Jul 19, 2022 |
| HONOR         | NBR-WAX9                    | [fe971bb8c3](https://linux-hardware.org/?probe=fe971bb8c3) | Jul 08, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [2835672840](https://linux-hardware.org/?probe=2835672840) | Jul 07, 2022 |
| Kraftway      | ACCORD                      | [24e49bc011](https://linux-hardware.org/?probe=24e49bc011) | Jun 27, 2022 |
| Kraftway      | ACCORD                      | [39e3c55e89](https://linux-hardware.org/?probe=39e3c55e89) | Jun 27, 2022 |
| Aquarius      | NS685U                      | [ecedc7cbb6](https://linux-hardware.org/?probe=ecedc7cbb6) | Jun 08, 2022 |
| ICL           | Unknown                     | [4dc89fc689](https://linux-hardware.org/?probe=4dc89fc689) | Jun 07, 2022 |
| mtech         | MTL1578                     | [bf25c26ea0](https://linux-hardware.org/?probe=bf25c26ea0) | May 11, 2022 |
| HUAWEI        | BOD-WXX9                    | [e2e025dd4f](https://linux-hardware.org/?probe=e2e025dd4f) | Apr 15, 2022 |
| Acer          | TravelMate P215-53          | [124fdb3b64](https://linux-hardware.org/?probe=124fdb3b64) | Apr 14, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [be41efbec8](https://linux-hardware.org/?probe=be41efbec8) | Apr 05, 2022 |
| Aquarius      | NS585 R32                   | [582389ca98](https://linux-hardware.org/?probe=582389ca98) | Mar 24, 2022 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [56f9ebba91](https://linux-hardware.org/?probe=56f9ebba91) | Mar 22, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [e18b80073c](https://linux-hardware.org/?probe=e18b80073c) | Mar 21, 2022 |
| 3Logic Gro... | APM Graviton A15i-K2        | [e93bcf2f42](https://linux-hardware.org/?probe=e93bcf2f42) | Mar 09, 2022 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [227a2658d0](https://linux-hardware.org/?probe=227a2658d0) | Feb 15, 2022 |
| HP            | Laptop 15s-eq1xxx           | [7ed7e139d8](https://linux-hardware.org/?probe=7ed7e139d8) | Dec 20, 2021 |
| HP            | Laptop 15s-eq1xxx           | [55ab1c9ab8](https://linux-hardware.org/?probe=55ab1c9ab8) | Dec 20, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [5bb21d6bf6](https://linux-hardware.org/?probe=5bb21d6bf6) | Dec 13, 2021 |
| ICL           | RAYbook Si1514              | [9ddc61deba](https://linux-hardware.org/?probe=9ddc61deba) | Sep 13, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [4f59992d0f](https://linux-hardware.org/?probe=4f59992d0f) | Sep 11, 2021 |
| HP            | Laptop 15-dw3xxx            | [d8b35044ab](https://linux-hardware.org/?probe=d8b35044ab) | Jul 29, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [9b2c758081](https://linux-hardware.org/?probe=9b2c758081) | Jun 10, 2021 |
| ASUSTek       | X75VD                       | [95ea9551da](https://linux-hardware.org/?probe=95ea9551da) | Apr 05, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [916d4b225b](https://linux-hardware.org/?probe=916d4b225b) | Mar 30, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [ebfafc7409](https://linux-hardware.org/?probe=ebfafc7409) | Mar 26, 2021 |
| HUAWEI        | BOHL-WXX9                   | [cf5559d576](https://linux-hardware.org/?probe=cf5559d576) | Mar 26, 2021 |
| HP            | Pavilion g6                 | [1ca79b1950](https://linux-hardware.org/?probe=1ca79b1950) | Mar 26, 2021 |
| Pegatron      | A35                         | [9923a21e8c](https://linux-hardware.org/?probe=9923a21e8c) | Mar 04, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Red OS 7.3.1 | 29        | 63.04%  |
| Red OS 7.3   | 17        | 36.96%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Red OS | 45        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.15.10-1.el7.x86_64   | 13        | 27.66%  |
| 5.10.29-1.el7.x86_64   | 9         | 19.15%  |
| 5.15.35-4.el7.3.x86_64 | 6         | 12.77%  |
| 5.15.35-1.el7.3.x86_64 | 6         | 12.77%  |
| 5.10.1-1.el7.x86_64    | 3         | 6.38%   |
| 5.15.10-4.el7.x86_64   | 2         | 4.26%   |
| 5.10.24-2.el7.x86_64   | 2         | 4.26%   |
| 5.18.1-1.el7.x86_64    | 1         | 2.13%   |
| 5.15.10-3.el7.x86_64   | 1         | 2.13%   |
| 5.15.10-2.el7.x86_64   | 1         | 2.13%   |
| 5.13.15-1.el7.x86_64   | 1         | 2.13%   |
| 5.10.29-3.el7.x86_64   | 1         | 2.13%   |
| 5.10.24-1.el7.x86_64   | 1         | 2.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.10 | 17        | 36.17%  |
| 5.15.35 | 12        | 25.53%  |
| 5.10.29 | 10        | 21.28%  |
| 5.10.24 | 3         | 6.38%   |
| 5.10.1  | 3         | 6.38%   |
| 5.18.1  | 1         | 2.13%   |
| 5.13.15 | 1         | 2.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 29        | 63.04%  |
| 5.10    | 15        | 32.61%  |
| 5.18    | 1         | 2.17%   |
| 5.13    | 1         | 2.17%   |

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


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| MATE     | 36        | 80%     |
| Cinnamon | 9         | 20%     |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 41        | 89.13%  |
| Wayland | 5         | 10.87%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| GDM  | 43        | 95.56%  |
| SDDM | 2         | 4.44%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 44        | 97.78%  |
| en_US   | 1         | 2.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 40        | 86.96%  |
| BIOS | 6         | 13.04%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Ext4  | 45        | 97.83%  |
| Btrfs | 1         | 2.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 41        | 91.11%  |
| MBR  | 4         | 8.89%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 41        | 91.11%  |
| Yes       | 4         | 8.89%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 33        | 71.74%  |
| Yes       | 13        | 28.26%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 24        | 53.33%  |
| HUAWEI              | 3         | 6.67%   |
| Hewlett-Packard     | 3         | 6.67%   |
| ICL                 | 2         | 4.44%   |
| Digma               | 2         | 4.44%   |
| ASUSTek Computer    | 2         | 4.44%   |
| Aquarius            | 2         | 4.44%   |
| Pegatron            | 1         | 2.22%   |
| mtech               | 1         | 2.22%   |
| Kraftway            | 1         | 2.22%   |
| HONOR               | 1         | 2.22%   |
| Gigabyte Technology | 1         | 2.22%   |
| Acer                | 1         | 2.22%   |
| 3Logic Group        | 1         | 2.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Lenovo V15-IWL 81YE               | 17        | 37.78%  |
| Pegatron A35                      | 1         | 2.22%   |
| mtech MTL1578                     | 1         | 2.22%   |
| Lenovo ThinkBook 15 G3 ACL 21A4   | 1         | 2.22%   |
| Lenovo ThinkBook 14-IIL 20SL      | 1         | 2.22%   |
| Lenovo IdeaPad L340-15IWL 81LG    | 1         | 2.22%   |
| Lenovo IdeaPad L340-15API 81LW    | 1         | 2.22%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7  | 1         | 2.22%   |
| Lenovo IdeaPad 5 15ARE05 81YQ     | 1         | 2.22%   |
| Lenovo IdeaPad 3 15ITL05 81X8     | 1         | 2.22%   |
| Kraftway ACCORD                   | 1         | 2.22%   |
| ICL RAYbook Si1514                | 1         | 2.22%   |
| HUAWEI NBLK-WAX9X                 | 1         | 2.22%   |
| HUAWEI BOHL-WXX9                  | 1         | 2.22%   |
| HUAWEI BOD-WXX9                   | 1         | 2.22%   |
| HONOR NBR-WAX9                    | 1         | 2.22%   |
| HP Pavilion g6                    | 1         | 2.22%   |
| HP Laptop 15s-eq1xxx              | 1         | 2.22%   |
| HP Laptop 15-dw3xxx               | 1         | 2.22%   |
| Gigabyte G5 GD                    | 1         | 2.22%   |
| Digma EVE 15 P417 ES5063EW        | 1         | 2.22%   |
| Digma EVE 15 C407 ES5054EW        | 1         | 2.22%   |
| ASUS X75VD                        | 1         | 2.22%   |
| ASUS TUF Gaming FX705DT_FX705DT   | 1         | 2.22%   |
| Aquarius NS685U                   | 1         | 2.22%   |
| Aquarius NS585 R32                | 1         | 2.22%   |
| Acer TravelMate P215-53           | 1         | 2.22%   |
| 3Logic Group APM Graviton A15i-K2 | 1         | 2.22%   |
| Unknown                           | 1         | 2.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo V15-IWL    | 17        | 37.78%  |
| Lenovo IdeaPad    | 5         | 11.11%  |
| Lenovo ThinkBook  | 2         | 4.44%   |
| HP Laptop         | 2         | 4.44%   |
| Digma EVE         | 2         | 4.44%   |
| Pegatron A35      | 1         | 2.22%   |
| mtech MTL1578     | 1         | 2.22%   |
| Kraftway ACCORD   | 1         | 2.22%   |
| ICL RAYbook       | 1         | 2.22%   |
| HUAWEI NBLK-WAX9X | 1         | 2.22%   |
| HUAWEI BOHL-WXX9  | 1         | 2.22%   |
| HUAWEI BOD-WXX9   | 1         | 2.22%   |
| HONOR NBR-WAX9    | 1         | 2.22%   |
| HP Pavilion       | 1         | 2.22%   |
| Gigabyte G5       | 1         | 2.22%   |
| ASUS X75VD        | 1         | 2.22%   |
| ASUS TUF          | 1         | 2.22%   |
| Aquarius NS685U   | 1         | 2.22%   |
| Aquarius NS585    | 1         | 2.22%   |
| Acer TravelMate   | 1         | 2.22%   |
| 3Logic Group APM  | 1         | 2.22%   |
| Unknown           | 1         | 2.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 23        | 51.11%  |
| 2021 | 13        | 28.89%  |
| 2020 | 5         | 11.11%  |
| 2012 | 2         | 4.44%   |
| 2022 | 1         | 2.22%   |
| 2011 | 1         | 2.22%   |

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
| Disabled | 45        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 45        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 34        | 75.56%  |
| 16.01-24.0 | 4         | 8.89%   |
| 8.01-16.0  | 4         | 8.89%   |
| 3.01-4.0   | 3         | 6.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 25        | 55.56%  |
| 2.01-3.0 | 10        | 22.22%  |
| 0.51-1.0 | 5         | 11.11%  |
| 3.01-4.0 | 4         | 8.89%   |
| 4.01-8.0 | 1         | 2.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 39        | 84.78%  |
| 2      | 4         | 8.7%    |
| 3      | 3         | 6.52%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 40        | 88.89%  |
| Yes       | 5         | 11.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 26        | 57.78%  |
| Yes       | 19        | 42.22%  |

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
| Yes       | 38        | 84.44%  |
| No        | 7         | 15.56%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Russia  | 44        | 97.78%  |
| Ukraine | 1         | 2.22%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Salekhard     | 18        | 40%     |
| Murom         | 9         | 20%     |
| Moscow        | 5         | 11.11%  |
| Vladimir      | 2         | 4.44%   |
| Novy Urengoy  | 2         | 4.44%   |
| Kursk         | 2         | 4.44%   |
| Yekaterinburg | 1         | 2.22%   |
| Yaroslavl     | 1         | 2.22%   |
| Sevastopol    | 1         | 2.22%   |
| Perm          | 1         | 2.22%   |
| Novosibirsk   | 1         | 2.22%   |
| Krasnodar     | 1         | 2.22%   |
| Belgorod      | 1         | 2.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 21        | 21     | 39.62%  |
| WDC                 | 8         | 10     | 15.09%  |
| Toshiba             | 3         | 3      | 5.66%   |
| A-DATA Technology   | 3         | 3      | 5.66%   |
| Unknown             | 2         | 2      | 3.77%   |
| SK hynix            | 2         | 2      | 3.77%   |
| Phison              | 2         | 2      | 3.77%   |
| UMIS                | 1         | 1      | 1.89%   |
| Transcend           | 1         | 1      | 1.89%   |
| Seagate             | 1         | 1      | 1.89%   |
| SanDisk             | 1         | 1      | 1.89%   |
| Micron Technology   | 1         | 3      | 1.89%   |
| Kingston            | 1         | 1      | 1.89%   |
| JMicron Technology  | 1         | 1      | 1.89%   |
| ITHOO               | 1         | 1      | 1.89%   |
| Gigabyte Technology | 1         | 1      | 1.89%   |
| Foxline             | 1         | 1      | 1.89%   |
| Crucial             | 1         | 1      | 1.89%   |
| Apacer              | 1         | 1      | 1.89%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Samsung MZALQ256HAJD-000L2 256GB          | 17        | 32.08%  |
| WDC WD5000BPVT-55HXZT3 500GB              | 1         | 1.89%   |
| WDC WD10SPZX-24Z10 1TB                    | 1         | 1.89%   |
| WDC WD10SPZX-00Z10T0 1TB                  | 1         | 1.89%   |
| WDC PC SN530 SDBPNPZ-512G-1114 512GB      | 1         | 1.89%   |
| WDC PC SN530 SDBPNPZ-512G-1027 512GB      | 1         | 1.89%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB      | 1         | 1.89%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB      | 1         | 1.89%   |
| WDC PC SN520 SDAPMUW-512G-1101 512GB      | 1         | 1.89%   |
| Unknown SLD128  128GB                     | 1         | 1.89%   |
| Unknown 58K722  128GB                     | 1         | 1.89%   |
| UMIS RPJTJ512MEE1OWX 512GB                | 1         | 1.89%   |
| Transcend TS240GMTS820S 240GB SSD         | 1         | 1.89%   |
| Toshiba MQ01ABF050 500GB                  | 1         | 1.89%   |
| Toshiba KXG60ZNV512G 512GB                | 1         | 1.89%   |
| Toshiba KXG60ZNV256G 256GB                | 1         | 1.89%   |
| SK hynix SKHynix_HFM256GDHTNI-87A0B 256GB | 1         | 1.89%   |
| SK hynix SKHynix_HFM256GD3HX015N 256GB    | 1         | 1.89%   |
| Seagate ST750LM022 HN-M750MBB 752GB       | 1         | 1.89%   |
| SanDisk SD8SBAT256G1122 256GB SSD         | 1         | 1.89%   |
| Samsung SSD 860 EVO M.2 250GB             | 1         | 1.89%   |
| Samsung MZVLQ256HAJD-000H1 256GB          | 1         | 1.89%   |
| Samsung MZALQ512HBLU-00BL2 512GB          | 1         | 1.89%   |
| Samsung MZALQ512HALU-000L2 512GB          | 1         | 1.89%   |
| Phison ESR512GTLG-E6GBTNB4 512GB          | 1         | 1.89%   |
| Phison 311CD0512GB                        | 1         | 1.89%   |
| Micron 2200V_MTFDHBA512TCK 512GB          | 1         | 1.89%   |
| Kingston SNVS500G 500GB                   | 1         | 1.89%   |
| JMicron Generic 2TB                       | 1         | 1.89%   |
| ITHOO Tech 250GB                          | 1         | 1.89%   |
| Gigabyte GP-GSM2NE3256GNTD 256GB          | 1         | 1.89%   |
| Foxline FLSSD256M80E13TCX5 256GB          | 1         | 1.89%   |
| Crucial CT250MX500SSD4 250GB              | 1         | 1.89%   |
| Apacer AS350 256GB SSD                    | 1         | 1.89%   |
| A-DATA SX6000LNP 256GB                    | 1         | 1.89%   |
| A-DATA SU800 256GB SSD                    | 1         | 1.89%   |
| A-DATA SU650 240GB SSD                    | 1         | 1.89%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 5      | 60%     |
| Toshiba | 1         | 1      | 20%     |
| Seagate | 1         | 1      | 20%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| A-DATA Technology   | 2         | 2      | 28.57%  |
| Transcend           | 1         | 1      | 14.29%  |
| SanDisk             | 1         | 1      | 14.29%  |
| Samsung Electronics | 1         | 1      | 14.29%  |
| Crucial             | 1         | 1      | 14.29%  |
| Apacer              | 1         | 1      | 14.29%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 36        | 40     | 70.59%  |
| SSD     | 7         | 7      | 13.73%  |
| HDD     | 5         | 7      | 9.8%    |
| MMC     | 2         | 2      | 3.92%   |
| Unknown | 1         | 1      | 1.96%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 36        | 39     | 69.23%  |
| SATA | 12        | 14     | 23.08%  |
| SAS  | 2         | 2      | 3.85%   |
| MMC  | 2         | 2      | 3.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 9         | 9      | 75%     |
| 0.51-1.0   | 3         | 5      | 25%     |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 26        | 56.52%  |
| 251-500    | 9         | 19.57%  |
| 1001-2000  | 3         | 6.52%   |
| 501-1000   | 3         | 6.52%   |
| 51-100     | 3         | 6.52%   |
| 21-50      | 1         | 2.17%   |
| 1-20       | 1         | 2.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 33        | 71.74%  |
| 21-50    | 4         | 8.7%    |
| 101-250  | 4         | 8.7%    |
| 251-500  | 2         | 4.35%   |
| 51-100   | 2         | 4.35%   |
| 501-1000 | 1         | 2.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD10SPZX-24Z10 1TB              | 1         | 1      | 25%     |
| Toshiba MQ01ABF050 500GB            | 1         | 1      | 25%     |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1      | 25%     |
| A-DATA Technology SU800 256GB SSD   | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 1         | 1      | 25%     |
| Toshiba           | 1         | 1      | 25%     |
| Seagate           | 1         | 1      | 25%     |
| A-DATA Technology | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Toshiba | 1         | 1      | 33.33%  |
| Seagate | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 75%     |
| SSD  | 1         | 1      | 25%     |

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
| Works    | 42        | 49     | 85.71%  |
| Malfunc  | 4         | 4      | 8.16%   |
| Detected | 3         | 4      | 6.12%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 36        | 46.75%  |
| Samsung Electronics          | 20        | 25.97%  |
| SanDisk                      | 5         | 6.49%   |
| Phison Electronics           | 4         | 5.19%   |
| AMD                          | 4         | 5.19%   |
| Toshiba America Info Systems | 2         | 2.6%    |
| SK hynix                     | 2         | 2.6%    |
| Union Memory (Shenzhen)      | 1         | 1.3%    |
| Realtek Semiconductor        | 1         | 1.3%    |
| Micron Technology            | 1         | 1.3%    |
| Kingston Technology Company  | 1         | 1.3%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 23        | 29.11%  |
| Samsung NVMe SSD Controller 980                                                  | 20        | 25.32%  |
| Intel Tiger Lake-LP SATA Controller                                              | 4         | 5.06%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 4         | 5.06%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 3         | 3.8%    |
| Phison PS5013 E13 NVMe Controller                                                | 3         | 3.8%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 3         | 3.8%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 2.53%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 2.53%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 1.27%   |
| SK hynix Gold P31 SSD                                                            | 1         | 1.27%   |
| SK hynix BC511                                                                   | 1         | 1.27%   |
| SanDisk PC SN520 NVMe SSD                                                        | 1         | 1.27%   |
| SanDisk Non-Volatile memory controller                                           | 1         | 1.27%   |
| Realtek Realtek Non-Volatile memory controller                                   | 1         | 1.27%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 1.27%   |
| Micron Non-Volatile memory controller                                            | 1         | 1.27%   |
| Kingston Company Company Non-Volatile memory controller                          | 1         | 1.27%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 1.27%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.27%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.27%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1         | 1.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.27%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 1         | 1.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 40        | 51.28%  |
| NVMe | 36        | 46.15%  |
| RAID | 2         | 2.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 37        | 82.22%  |
| AMD    | 8         | 17.78%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8265U CPU @ 1.60GHz             | 18        | 40%     |
| Intel Core i5-8279U CPU @ 2.40GHz             | 3         | 6.67%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 2         | 4.44%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 4.44%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 4.44%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 4.44%   |
| Intel Pentium CPU J3710 @ 1.60GHz             | 1         | 2.22%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 2.22%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 2.22%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 2.22%   |
| Intel Core i3-9300 CPU @ 3.70GHz              | 1         | 2.22%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 1         | 2.22%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 1         | 2.22%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 1         | 2.22%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 2.22%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz       | 1         | 2.22%   |
| Intel 11th Gen Core i3-1125G4 @ 2.00GHz       | 1         | 2.22%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 2.22%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 1         | 2.22%   |
| AMD Ryzen 5 5600U with Radeon Graphics        | 1         | 2.22%   |
| AMD Ryzen 3 5300U with Radeon Graphics        | 1         | 2.22%   |
| AMD Ryzen 3 4300U with Radeon Graphics        | 1         | 2.22%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Intel Core i5 | 26        | 57.78%  |
| Other         | 6         | 13.33%  |
| AMD Ryzen 5   | 5         | 11.11%  |
| Intel Core i3 | 3         | 6.67%   |
| AMD Ryzen 3   | 2         | 4.44%   |
| Intel Pentium | 1         | 2.22%   |
| Intel Celeron | 1         | 2.22%   |
| AMD Ryzen 7   | 1         | 2.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 35        | 77.78%  |
| 2      | 6         | 13.33%  |
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
| 2      | 39        | 86.67%  |
| 1      | 6         | 13.33%  |

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
| 0x806ec    | 19        | 42.22%  |
| 0x806ea    | 5         | 11.11%  |
| 0x806c1    | 5         | 11.11%  |
| 0x206a7    | 2         | 4.44%   |
| 0x08600106 | 2         | 4.44%   |
| 0x08108102 | 2         | 4.44%   |
| 0x906eb    | 1         | 2.22%   |
| 0x806d1    | 1         | 2.22%   |
| 0x706e5    | 1         | 2.22%   |
| 0x506ca    | 1         | 2.22%   |
| 0x406c4    | 1         | 2.22%   |
| 0x306a9    | 1         | 2.22%   |
| 0x0a50000c | 1         | 2.22%   |
| 0x08608103 | 1         | 2.22%   |
| 0x08600104 | 1         | 2.22%   |
| 0x08108109 | 1         | 2.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 25        | 55.56%  |
| TigerLake   | 5         | 11.11%  |
| Zen+        | 3         | 6.67%   |
| Zen 2       | 3         | 6.67%   |
| SandyBridge | 2         | 4.44%   |
| Icelake     | 2         | 4.44%   |
| Zen 3       | 1         | 2.22%   |
| Silvermont  | 1         | 2.22%   |
| IvyBridge   | 1         | 2.22%   |
| Goldmont    | 1         | 2.22%   |
| Unknown     | 1         | 2.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 37        | 72.55%  |
| AMD    | 9         | 17.65%  |
| Nvidia | 5         | 9.8%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 18        | 35.29%  |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 5         | 9.8%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 5.88%   |
| AMD Renoir                                                                               | 3         | 5.88%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 5.88%   |
| Intel Tiger Lake UHD Graphics                                                            | 2         | 3.92%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 3.92%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.96%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 1.96%   |
| Nvidia GF119M [GeForce 610M]                                                             | 1         | 1.96%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 1.96%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 1.96%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 1.96%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 1.96%   |
| Intel HD Graphics 500                                                                    | 1         | 1.96%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.96%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 1.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.96%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 1.96%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 1.96%   |
| AMD Lucienne                                                                             | 1         | 1.96%   |
| AMD Cezanne                                                                              | 1         | 1.96%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 32        | 71.11%  |
| 1 x AMD        | 7         | 15.56%  |
| Intel + Nvidia | 4         | 8.89%   |
| Intel + AMD    | 1         | 2.22%   |
| AMD + Nvidia   | 1         | 2.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 45        | 97.83%  |
| Proprietary | 1         | 2.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 32        | 68.09%  |
| 1.01-2.0   | 5         | 10.64%  |
| 0.51-1.0   | 4         | 8.51%   |
| 3.01-4.0   | 3         | 6.38%   |
| 0.01-0.5   | 3         | 6.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| BOE                  | 27        | 55.1%   |
| Chimei Innolux       | 6         | 12.24%  |
| Samsung Electronics  | 4         | 8.16%   |
| LG Display           | 4         | 8.16%   |
| AU Optronics         | 4         | 8.16%   |
| PANDA                | 2         | 4.08%   |
| Iiyama               | 1         | 2.04%   |
| Ancor Communications | 1         | 2.04%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                   | 17        | 34.69%  |
| BOE LCD Monitor BOE09C5 1920x1080 341x192mm 15.4-inch                   | 3         | 6.12%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 2         | 4.08%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch        | 2         | 4.08%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                   | 2         | 4.08%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                   | 2         | 4.08%   |
| AU Optronics LCD Monitor AUO28ED 1920x1080 344x193mm 15.5-inch          | 2         | 4.08%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch    | 1         | 2.04%   |
| Samsung Electronics LCD Monitor SEC314F 1600x900 382x215mm 17.3-inch    | 1         | 2.04%   |
| Samsung Electronics LCD Monitor SAM71B4 3840x2160 1872x1053mm 84.6-inch | 1         | 2.04%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1872x1053mm 84.6-inch | 1         | 2.04%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch                 | 1         | 2.04%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                 | 1         | 2.04%   |
| LG Display LCD Monitor LGD063B 1920x1080 382x215mm 17.3-inch            | 1         | 2.04%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch            | 1         | 2.04%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch            | 1         | 2.04%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 1         | 2.04%   |
| Iiyama PL2493H IVM6148 1920x1080 527x296mm 23.8-inch                    | 1         | 2.04%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch        | 1         | 2.04%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 1         | 2.04%   |
| BOE LCD Monitor BOE097A 1920x1080 309x174mm 14.0-inch                   | 1         | 2.04%   |
| BOE LCD Monitor BOE0936 1920x1080 344x194mm 15.5-inch                   | 1         | 2.04%   |
| BOE LCD Monitor BOE0931 2240x1400 302x189mm 14.0-inch                   | 1         | 2.04%   |
| AU Optronics LCD Monitor AUODF87 1920x1080 344x193mm 15.5-inch          | 1         | 2.04%   |
| AU Optronics LCD Monitor AUO20ED 1920x1080 344x193mm 15.5-inch          | 1         | 2.04%   |
| Ancor Communications VE228 ACI22FA 1920x1080 477x268mm 21.5-inch        | 1         | 2.04%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 42        | 87.5%   |
| 3840x2160 (4K)  | 2         | 4.17%   |
| 1366x768 (WXGA) | 2         | 4.17%   |
| 2240x1400       | 1         | 2.08%   |
| 1600x900 (HD+)  | 1         | 2.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 38        | 77.55%  |
| 13     | 3         | 6.12%   |
| 84     | 2         | 4.08%   |
| 24     | 2         | 4.08%   |
| 17     | 2         | 4.08%   |
| 14     | 2         | 4.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 43        | 87.76%  |
| 501-600     | 2         | 4.08%   |
| 351-400     | 2         | 4.08%   |
| 1501-2000   | 2         | 4.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 44        | 97.78%  |
| 16/10 | 1         | 2.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 38        | 77.55%  |
| 81-90          | 5         | 10.2%   |
| More than 1000 | 2         | 4.08%   |
| 201-250        | 2         | 4.08%   |
| 121-130        | 2         | 4.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 41        | 83.67%  |
| 51-100  | 4         | 8.16%   |
| 101-120 | 3         | 6.12%   |
| 161-240 | 1         | 2.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 41        | 91.11%  |
| 2     | 4         | 8.89%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 35        | 62.5%   |
| Intel                 | 12        | 21.43%  |
| Qualcomm Atheros      | 3         | 5.36%   |
| TP-Link               | 1         | 1.79%   |
| Samsung Electronics   | 1         | 1.79%   |
| Ralink                | 1         | 1.79%   |
| OKB SAPR              | 1         | 1.79%   |
| MediaTek              | 1         | 1.79%   |
| Broadcom              | 1         | 1.79%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 21        | 31.34%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 16.42%  |
| Intel Ethernet Connection (6) I219-V                              | 4         | 5.97%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 4.48%   |
| Intel Wireless 7265                                               | 3         | 4.48%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 4.48%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 2         | 2.99%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 2.99%   |
| TP-Link 802.11n NIC                                               | 1         | 1.49%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.49%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 1.49%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 1.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.49%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 1.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 1.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 1.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.49%   |
| OKB SAPR Ethernet controller                                      | 1         | 1.49%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 1.49%   |
| Intel Wireless 3165                                               | 1         | 1.49%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 1.49%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 1         | 1.49%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.49%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.49%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 1         | 1.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 28        | 60.87%  |
| Intel                 | 12        | 26.09%  |
| Qualcomm Atheros      | 2         | 4.35%   |
| TP-Link               | 1         | 2.17%   |
| Ralink                | 1         | 2.17%   |
| MediaTek              | 1         | 2.17%   |
| Broadcom              | 1         | 2.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 21        | 45.65%  |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 3         | 6.52%   |
| Intel Wireless 7265                                           | 3         | 6.52%   |
| Intel Wi-Fi 6 AX201                                           | 3         | 6.52%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                    | 2         | 4.35%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 2         | 4.35%   |
| TP-Link 802.11n NIC                                           | 1         | 2.17%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 1         | 2.17%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 1         | 2.17%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                     | 1         | 2.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 1         | 2.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 1         | 2.17%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 1         | 2.17%   |
| Intel Wireless 3165                                           | 1         | 2.17%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 1         | 2.17%   |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 1         | 2.17%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 1         | 2.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 1         | 2.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 13        | 61.9%   |
| Intel                 | 5         | 23.81%  |
| Samsung Electronics   | 1         | 4.76%   |
| Qualcomm Atheros      | 1         | 4.76%   |
| OKB SAPR              | 1         | 4.76%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11        | 52.38%  |
| Intel Ethernet Connection (6) I219-V                              | 4         | 19.05%  |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 4.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 4.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 4.76%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 4.76%   |
| OKB SAPR Ethernet controller                                      | 1         | 4.76%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 4.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 45        | 70.31%  |
| Ethernet | 19        | 29.69%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 33        | 75%     |
| Ethernet | 11        | 25%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 25        | 55.56%  |
| 2     | 18        | 40%     |
| 0     | 2         | 4.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 42        | 93.33%  |
| Yes  | 3         | 6.67%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 21        | 55.26%  |
| Intel                           | 10        | 26.32%  |
| Realtek                         | 2         | 5.26%   |
| Ralink                          | 1         | 2.63%   |
| Qualcomm Atheros Communications | 1         | 2.63%   |
| IMC Networks                    | 1         | 2.63%   |
| Foxconn / Hon Hai               | 1         | 2.63%   |
| Broadcom                        | 1         | 2.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                        | 20        | 52.63%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 4         | 10.53%  |
| Intel Bluetooth wireless interface             | 3         | 7.89%   |
| Intel AX201 Bluetooth                          | 3         | 7.89%   |
| Realtek Bluetooth Radio                        | 2         | 5.26%   |
| Realtek  Bluetooth 4.2 Adapter                 | 1         | 2.63%   |
| Ralink RT3290 Bluetooth                        | 1         | 2.63%   |
| Qualcomm Atheros  Bluetooth Device             | 1         | 2.63%   |
| IMC Networks Bluetooth Radio                   | 1         | 2.63%   |
| Foxconn / Hon Hai Wireless_Device              | 1         | 2.63%   |
| Broadcom HP Portable Valentine                 | 1         | 2.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel                | 37        | 75.51%  |
| AMD                  | 8         | 16.33%  |
| Nvidia               | 3         | 6.12%   |
| MosArt Semiconductor | 1         | 2.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Cannon Point-LP High Definition Audio Controller                                            | 23        | 41.07%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 8         | 14.29%  |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 8.93%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 8.93%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 3         | 5.36%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 3.57%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 1.79%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.79%   |
| Nvidia Audio device                                                                               | 1         | 1.79%   |
| MosArt Semiconductor MosArt USB Audio Device                                                      | 1         | 1.79%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 1.79%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 1.79%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 1.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.79%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 23        | 47.92%  |
| SK hynix            | 7         | 14.58%  |
| Micron Technology   | 4         | 8.33%   |
| Ramaxel Technology  | 3         | 6.25%   |
| Foxline             | 3         | 6.25%   |
| Crucial             | 3         | 6.25%   |
| Elpida              | 2         | 4.17%   |
| Unknown (ABCD)      | 1         | 2.08%   |
| Unknown             | 1         | 2.08%   |
| Kingston            | 1         | 2.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 17        | 34.69%  |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 2         | 4.08%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 4.08%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 4.08%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 4.08%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                        | 1         | 2.04%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 1         | 2.04%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.04%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 2.04%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 2.04%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 2.04%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 1         | 2.04%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 2.04%   |
| Samsung RAM M471A1K43EB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 1         | 2.04%   |
| Ramaxel RAM RMSA3310MJ86H9F-3200 4GB SODIMM DDR4 3200MT/s        | 1         | 2.04%   |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s       | 1         | 2.04%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 1         | 2.04%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 1         | 2.04%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 1         | 2.04%   |
| Kingston RAM HP32D4S2S1ME-4 4GB SODIMM DDR4 3200MT/s             | 1         | 2.04%   |
| Foxline RAM FL2666D4S19-8G 8GB SODIMM DDR4 2667MT/s              | 1         | 2.04%   |
| Foxline RAM FL2400D4S17S-8G 8GB SODIMM DDR4 2400MT/s             | 1         | 2.04%   |
| Foxline RAM FL2400D4S17-8G 8GB SODIMM DDR4 2400MT/s              | 1         | 2.04%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 1         | 2.04%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4096MB SODIMM DDR3 1600MT/s         | 1         | 2.04%   |
| Elpida RAM EBJ20UF8BCS0-DJ-F 2GB SODIMM DDR3 1334MT/s            | 1         | 2.04%   |
| Crucial RAM CT8G4SFRA32A.C8FN 8GB SODIMM DDR4 3200MT/s           | 1         | 2.04%   |
| Crucial RAM CT8G4SFRA266.C8FJ 8GB SODIMM DDR4 2667MT/s           | 1         | 2.04%   |
| Crucial RAM CB8GS2666.C8ET 8GB SODIMM DDR4 2667MT/s              | 1         | 2.04%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 39        | 88.64%  |
| DDR3   | 4         | 9.09%   |
| LPDDR4 | 1         | 2.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 39        | 84.78%  |
| Row Of Chips | 6         | 13.04%  |
| DIMM         | 1         | 2.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 29        | 63.04%  |
| 4096  | 12        | 26.09%  |
| 2048  | 3         | 6.52%   |
| 16384 | 2         | 4.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 26        | 57.78%  |
| 3200  | 11        | 24.44%  |
| 2400  | 3         | 6.67%   |
| 1600  | 2         | 4.44%   |
| 3266  | 1         | 2.22%   |
| 1334  | 1         | 2.22%   |
| 1066  | 1         | 2.22%   |

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
| Syntek                                 | 18        | 40%     |
| Chicony Electronics                    | 8         | 17.78%  |
| IMC Networks                           | 6         | 13.33%  |
| Acer                                   | 4         | 8.89%   |
| USB Camera CS                          | 2         | 4.44%   |
| Sunplus Innovation Technology          | 2         | 4.44%   |
| SunplusIT                              | 1         | 2.22%   |
| Quanta                                 | 1         | 2.22%   |
| Microdia                               | 1         | 2.22%   |
| Luxvisions Innotech Limited            | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.22%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                                      | 18        | 40%     |
| Chicony USB camera                                            | 3         | 6.67%   |
| Acer Integrated Camera                                        | 3         | 6.67%   |
| USB Camera CS USB Camera CS                                   | 2         | 4.44%   |
| IMC Networks ov9734_azurewave_camera                          | 2         | 4.44%   |
| IMC Networks Integrated Camera                                | 2         | 4.44%   |
| SunplusIT MTD camera                                          | 1         | 2.22%   |
| Sunplus Integrated Camera                                     | 1         | 2.22%   |
| Sunplus ASUS USB2.0 Webcam                                    | 1         | 2.22%   |
| Quanta HD Camera                                              | 1         | 2.22%   |
| Microdia HDP Webcam USB                                       | 1         | 2.22%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera           | 1         | 2.22%   |
| IMC Networks USB2.0 HD UVC WebCam                             | 1         | 2.22%   |
| IMC Networks HD Camera                                        | 1         | 2.22%   |
| Chicony USB2.0 Camera                                         | 1         | 2.22%   |
| Chicony Integrated Camera                                     | 1         | 2.22%   |
| Chicony HP Webcam-50                                          | 1         | 2.22%   |
| Chicony HP TrueVision HD Camera                               | 1         | 2.22%   |
| Chicony HD User Facing                                        | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M Webcam | 1         | 2.22%   |
| Acer BisonCam, NB Pro                                         | 1         | 2.22%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 4         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device | 4         | 100%    |

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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 39        | 84.78%  |
| 1     | 6         | 13.04%  |
| 2     | 1         | 2.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 4         | 50%     |
| Net/wireless       | 1         | 12.5%   |
| Net/ethernet       | 1         | 12.5%   |
| Graphics card      | 1         | 12.5%   |
| Bluetooth          | 1         | 12.5%   |

