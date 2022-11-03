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

Total: 81

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad L340-15API 81LW     | [d653658a53](https://linux-hardware.org/?probe=d653658a53) | Oct 28, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [b9ab6b9cf2](https://linux-hardware.org/?probe=b9ab6b9cf2) | Oct 28, 2022 |
| Acer          | Aspire A517-52              | [1ee47a3ab6](https://linux-hardware.org/?probe=1ee47a3ab6) | Oct 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [14537f243b](https://linux-hardware.org/?probe=14537f243b) | Oct 24, 2022 |
| THUNDEROBO... | 911AirD                     | [f471a1c9db](https://linux-hardware.org/?probe=f471a1c9db) | Oct 23, 2022 |
| Acer          | Aspire A517-52              | [7515d53b5d](https://linux-hardware.org/?probe=7515d53b5d) | Oct 21, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [3fc175d4a0](https://linux-hardware.org/?probe=3fc175d4a0) | Oct 20, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [fe184c8f5b](https://linux-hardware.org/?probe=fe184c8f5b) | Oct 19, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [0db79bc085](https://linux-hardware.org/?probe=0db79bc085) | Oct 19, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [1cdde90662](https://linux-hardware.org/?probe=1cdde90662) | Oct 13, 2022 |
| Acer          | Aspire 2920                 | [c588bacc95](https://linux-hardware.org/?probe=c588bacc95) | Oct 08, 2022 |
| Acer          | Aspire 2920                 | [34b41a4e67](https://linux-hardware.org/?probe=34b41a4e67) | Oct 08, 2022 |
| ASUSTek       | X540NV                      | [31e4464fea](https://linux-hardware.org/?probe=31e4464fea) | Oct 07, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [7f8e650618](https://linux-hardware.org/?probe=7f8e650618) | Oct 06, 2022 |
| Acer          | Aspire 2920                 | [538f7a6e26](https://linux-hardware.org/?probe=538f7a6e26) | Oct 05, 2022 |
| HP            | OMEN by Laptop              | [0a8238a876](https://linux-hardware.org/?probe=0a8238a876) | Oct 05, 2022 |
| THUNDEROBO... | 911AirD                     | [69a9650652](https://linux-hardware.org/?probe=69a9650652) | Oct 03, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [89b48cd98e](https://linux-hardware.org/?probe=89b48cd98e) | Oct 03, 2022 |
| Digma         | EVE 11 C408                 | [b5c7ac8ed3](https://linux-hardware.org/?probe=b5c7ac8ed3) | Sep 30, 2022 |
| THUNDEROBO... | 911AirD                     | [99f1b7e253](https://linux-hardware.org/?probe=99f1b7e253) | Sep 29, 2022 |
| ICL           | RAYbook Si1512              | [0b610b66a9](https://linux-hardware.org/?probe=0b610b66a9) | Sep 20, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [713797403a](https://linux-hardware.org/?probe=713797403a) | Sep 09, 2022 |
| IP3 Techno... | ACN30                       | [af9694cea8](https://linux-hardware.org/?probe=af9694cea8) | Sep 06, 2022 |
| IP3 Techno... | ACN30                       | [03f14a115d](https://linux-hardware.org/?probe=03f14a115d) | Sep 05, 2022 |
| MSI           | FX610                       | [a822818a58](https://linux-hardware.org/?probe=a822818a58) | Sep 03, 2022 |
| IP3 Techno... | ACN30                       | [e25ed534c0](https://linux-hardware.org/?probe=e25ed534c0) | Aug 18, 2022 |
| ICL           | RAYbook Si1512              | [a42c4dc65a](https://linux-hardware.org/?probe=a42c4dc65a) | Aug 09, 2022 |
| Digma         | EVE 15 P417 ES5063EW        | [a584c678b5](https://linux-hardware.org/?probe=a584c678b5) | Jul 27, 2022 |
| Digma         | EVE 15 C407 ES5054EW        | [4fd01756b2](https://linux-hardware.org/?probe=4fd01756b2) | Jul 27, 2022 |
| Digma         | EVE 15 C407 ES5054EW        | [008b02cc92](https://linux-hardware.org/?probe=008b02cc92) | Jul 26, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [413949a727](https://linux-hardware.org/?probe=413949a727) | Jul 25, 2022 |
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
| Red OS 7.3.1 | 40        | 67.8%   |
| Red OS 7.3   | 17        | 28.81%  |
| Red OS 7.3.2 | 2         | 3.39%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Red OS | 57        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.15.10-1.el7.x86_64   | 21        | 33.87%  |
| 5.15.35-4.el7.3.x86_64 | 10        | 16.13%  |
| 5.10.29-1.el7.x86_64   | 9         | 14.52%  |
| 5.15.35-1.el7.3.x86_64 | 6         | 9.68%   |
| 5.10.1-1.el7.x86_64    | 3         | 4.84%   |
| 5.15.35-5.el7.3.x86_64 | 2         | 3.23%   |
| 5.15.10-4.el7.x86_64   | 2         | 3.23%   |
| 5.10.24-2.el7.x86_64   | 2         | 3.23%   |
| 5.18.1-1.el7.x86_64    | 1         | 1.61%   |
| 5.15.72-1.el7.3.x86_64 | 1         | 1.61%   |
| 5.15.10-3.el7.x86_64   | 1         | 1.61%   |
| 5.15.10-2.el7.x86_64   | 1         | 1.61%   |
| 5.13.15-1.el7.x86_64   | 1         | 1.61%   |
| 5.10.29-3.el7.x86_64   | 1         | 1.61%   |
| 5.10.24-1.el7.x86_64   | 1         | 1.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.10 | 25        | 40.98%  |
| 5.15.35 | 17        | 27.87%  |
| 5.10.29 | 10        | 16.39%  |
| 5.10.24 | 3         | 4.92%   |
| 5.10.1  | 3         | 4.92%   |
| 5.18.1  | 1         | 1.64%   |
| 5.15.72 | 1         | 1.64%   |
| 5.13.15 | 1         | 1.64%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 41        | 70.69%  |
| 5.10    | 15        | 25.86%  |
| 5.18    | 1         | 1.72%   |
| 5.13    | 1         | 1.72%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 57        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| MATE       | 46        | 79.31%  |
| Cinnamon   | 11        | 18.97%  |
| X-Cinnamon | 1         | 1.72%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 53        | 91.38%  |
| Wayland | 5         | 8.62%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM     | 53        | 92.98%  |
| SDDM    | 3         | 5.26%   |
| Unknown | 1         | 1.75%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 55        | 96.49%  |
| ru_RU   | 1         | 1.75%   |
| en_US   | 1         | 1.75%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 50        | 86.21%  |
| BIOS | 8         | 13.79%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Ext4  | 57        | 98.28%  |
| Btrfs | 1         | 1.72%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 51        | 89.47%  |
| MBR     | 5         | 8.77%   |
| Unknown | 1         | 1.75%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 52        | 91.23%  |
| Yes       | 5         | 8.77%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 41        | 70.69%  |
| Yes       | 17        | 29.31%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 25        | 43.86%  |
| ICL                 | 4         | 7.02%   |
| Hewlett-Packard     | 4         | 7.02%   |
| HUAWEI              | 3         | 5.26%   |
| Digma               | 3         | 5.26%   |
| ASUSTek Computer    | 3         | 5.26%   |
| Acer                | 3         | 5.26%   |
| IP3 Technology      | 2         | 3.51%   |
| Aquarius            | 2         | 3.51%   |
| THUNDEROBOT         | 1         | 1.75%   |
| Pegatron            | 1         | 1.75%   |
| mtech               | 1         | 1.75%   |
| MSI                 | 1         | 1.75%   |
| Kraftway            | 1         | 1.75%   |
| HONOR               | 1         | 1.75%   |
| Gigabyte Technology | 1         | 1.75%   |
| 3Logic Group        | 1         | 1.75%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Lenovo V15-IWL 81YE               | 17        | 29.82%  |
| Lenovo ThinkBook 15 G3 ACL 21A4   | 2         | 3.51%   |
| IP3 ACN30                         | 2         | 3.51%   |
| ICL RAYbook Si1512                | 2         | 3.51%   |
| THUNDEROBOT 911AirD               | 1         | 1.75%   |
| Pegatron A35                      | 1         | 1.75%   |
| mtech MTL1578                     | 1         | 1.75%   |
| MSI FX610                         | 1         | 1.75%   |
| Lenovo ThinkBook 14-IIL 20SL      | 1         | 1.75%   |
| Lenovo IdeaPad L340-15IWL 81LG    | 1         | 1.75%   |
| Lenovo IdeaPad L340-15API 81LW    | 1         | 1.75%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7  | 1         | 1.75%   |
| Lenovo IdeaPad 5 15ARE05 81YQ     | 1         | 1.75%   |
| Lenovo IdeaPad 3 15ITL05 81X8     | 1         | 1.75%   |
| Kraftway ACCORD                   | 1         | 1.75%   |
| ICL RAYbook Si1514                | 1         | 1.75%   |
| HUAWEI NBLK-WAX9X                 | 1         | 1.75%   |
| HUAWEI BOHL-WXX9                  | 1         | 1.75%   |
| HUAWEI BOD-WXX9                   | 1         | 1.75%   |
| HONOR NBR-WAX9                    | 1         | 1.75%   |
| HP Pavilion g6                    | 1         | 1.75%   |
| HP OMEN by Laptop                 | 1         | 1.75%   |
| HP Laptop 15s-eq1xxx              | 1         | 1.75%   |
| HP Laptop 15-dw3xxx               | 1         | 1.75%   |
| Gigabyte G5 GD                    | 1         | 1.75%   |
| Digma EVE 15 P417 ES5063EW        | 1         | 1.75%   |
| Digma EVE 15 C407 ES5054EW        | 1         | 1.75%   |
| Digma EVE 11 C408                 | 1         | 1.75%   |
| ASUS X75VD                        | 1         | 1.75%   |
| ASUS X540NV                       | 1         | 1.75%   |
| ASUS TUF Gaming FX705DT_FX705DT   | 1         | 1.75%   |
| Aquarius NS685U                   | 1         | 1.75%   |
| Aquarius NS585 R32                | 1         | 1.75%   |
| Acer TravelMate P215-53           | 1         | 1.75%   |
| Acer Aspire A517-52               | 1         | 1.75%   |
| Acer Aspire 2920                  | 1         | 1.75%   |
| 3Logic Group APM Graviton A15i-K2 | 1         | 1.75%   |
| Unknown                           | 1         | 1.75%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo V15-IWL      | 17        | 29.82%  |
| Lenovo IdeaPad      | 5         | 8.77%   |
| Lenovo ThinkBook    | 3         | 5.26%   |
| ICL RAYbook         | 3         | 5.26%   |
| Digma EVE           | 3         | 5.26%   |
| IP3 ACN30           | 2         | 3.51%   |
| HP Laptop           | 2         | 3.51%   |
| Acer Aspire         | 2         | 3.51%   |
| THUNDEROBOT 911AirD | 1         | 1.75%   |
| Pegatron A35        | 1         | 1.75%   |
| mtech MTL1578       | 1         | 1.75%   |
| MSI FX610           | 1         | 1.75%   |
| Kraftway ACCORD     | 1         | 1.75%   |
| HUAWEI NBLK-WAX9X   | 1         | 1.75%   |
| HUAWEI BOHL-WXX9    | 1         | 1.75%   |
| HUAWEI BOD-WXX9     | 1         | 1.75%   |
| HONOR NBR-WAX9      | 1         | 1.75%   |
| HP Pavilion         | 1         | 1.75%   |
| HP OMEN             | 1         | 1.75%   |
| Gigabyte G5         | 1         | 1.75%   |
| ASUS X75VD          | 1         | 1.75%   |
| ASUS X540NV         | 1         | 1.75%   |
| ASUS TUF            | 1         | 1.75%   |
| Aquarius NS685U     | 1         | 1.75%   |
| Aquarius NS585      | 1         | 1.75%   |
| Acer TravelMate     | 1         | 1.75%   |
| 3Logic Group APM    | 1         | 1.75%   |
| Unknown             | 1         | 1.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 25        | 43.86%  |
| 2021 | 15        | 26.32%  |
| 2020 | 8         | 14.04%  |
| 2022 | 3         | 5.26%   |
| 2012 | 2         | 3.51%   |
| 2017 | 1         | 1.75%   |
| 2011 | 1         | 1.75%   |
| 2010 | 1         | 1.75%   |
| 2007 | 1         | 1.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 57        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 57        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 57        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 40        | 70.18%  |
| 3.01-4.0   | 6         | 10.53%  |
| 16.01-24.0 | 5         | 8.77%   |
| 8.01-16.0  | 5         | 8.77%   |
| 2.01-3.0   | 1         | 1.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 33        | 56.9%   |
| 2.01-3.0 | 12        | 20.69%  |
| 3.01-4.0 | 6         | 10.34%  |
| 0.51-1.0 | 6         | 10.34%  |
| 4.01-8.0 | 1         | 1.72%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 48        | 82.76%  |
| 2      | 7         | 12.07%  |
| 3      | 3         | 5.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 50        | 87.72%  |
| Yes       | 7         | 12.28%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 52.63%  |
| No        | 27        | 47.37%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 56        | 98.25%  |
| No        | 1         | 1.75%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 48        | 84.21%  |
| No        | 9         | 15.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Russia  | 56        | 98.25%  |
| Ukraine | 1         | 1.75%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Salekhard        | 18        | 31.03%  |
| Murom            | 12        | 20.69%  |
| Moscow           | 7         | 12.07%  |
| Ryazan           | 3         | 5.17%   |
| Vladimir         | 2         | 3.45%   |
| Novy Urengoy     | 2         | 3.45%   |
| Kursk            | 2         | 3.45%   |
| Yekaterinburg    | 1         | 1.72%   |
| Yaroslavl        | 1         | 1.72%   |
| Ulyanovsk        | 1         | 1.72%   |
| Sevastopol       | 1         | 1.72%   |
| Saratov          | 1         | 1.72%   |
| Perm             | 1         | 1.72%   |
| Novosibirsk      | 1         | 1.72%   |
| Nizhniy Novgorod | 1         | 1.72%   |
| Krasnoyarsk      | 1         | 1.72%   |
| Krasnodar        | 1         | 1.72%   |
| Kaluga           | 1         | 1.72%   |
| Belgorod         | 1         | 1.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 21        | 24     | 31.34%  |
| WDC                 | 10        | 12     | 14.93%  |
| Toshiba             | 4         | 6      | 5.97%   |
| A-DATA Technology   | 4         | 4      | 5.97%   |
| SK hynix            | 3         | 3      | 4.48%   |
| Foxline             | 3         | 3      | 4.48%   |
| Unknown             | 2         | 2      | 2.99%   |
| Silicon Motion      | 2         | 2      | 2.99%   |
| Seagate             | 2         | 2      | 2.99%   |
| Phison              | 2         | 2      | 2.99%   |
| HGST                | 2         | 2      | 2.99%   |
| UMIS                | 1         | 1      | 1.49%   |
| Transcend           | 1         | 1      | 1.49%   |
| SanDisk             | 1         | 1      | 1.49%   |
| Micron Technology   | 1         | 3      | 1.49%   |
| Kingston            | 1         | 1      | 1.49%   |
| Kimtigo             | 1         | 2      | 1.49%   |
| JMicron Technology  | 1         | 1      | 1.49%   |
| ITHOO               | 1         | 1      | 1.49%   |
| Gigabyte Technology | 1         | 1      | 1.49%   |
| Crucial             | 1         | 1      | 1.49%   |
| Apacer              | 1         | 1      | 1.49%   |
| Unknown             | 1         | 1      | 1.49%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Samsung MZALQ256HAJD-000L2 256GB          | 17        | 25.37%  |
| Foxline FLSSD256M80E13TCX5 256GB          | 3         | 4.48%   |
| WDC PC SN530 SDBPNPZ-512G-1114 512GB      | 2         | 2.99%   |
| SK hynix SKHynix_HFM256GD3HX015N 256GB    | 2         | 2.99%   |
| Silicon Motion Wodposit NVMe SSD 256GB    | 2         | 2.99%   |
| A-DATA SU650 240GB SSD                    | 2         | 2.99%   |
| WDC WDS500G2B0B-00YS70 500GB SSD          | 1         | 1.49%   |
| WDC WD5000BPVT-55HXZT3 500GB              | 1         | 1.49%   |
| WDC WD10SPZX-24Z10 1TB                    | 1         | 1.49%   |
| WDC WD10SPZX-00Z10T0 1TB                  | 1         | 1.49%   |
| WDC PC SN530 SDBPNPZ-512G-1027 512GB      | 1         | 1.49%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB      | 1         | 1.49%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB      | 1         | 1.49%   |
| WDC PC SN520 SDAPMUW-512G-1101 512GB      | 1         | 1.49%   |
| Unknown SLD128  128GB                     | 1         | 1.49%   |
| Unknown 58K722  128GB                     | 1         | 1.49%   |
| UMIS RPJTJ512MEE1OWX 512GB                | 1         | 1.49%   |
| Transcend TS240GMTS820S 240GB SSD         | 1         | 1.49%   |
| Toshiba MQ01ABF050 500GB                  | 1         | 1.49%   |
| Toshiba MK5059GSXP 500GB                  | 1         | 1.49%   |
| Toshiba KXG60ZNV512G 512GB                | 1         | 1.49%   |
| Toshiba KXG60ZNV256G 256GB                | 1         | 1.49%   |
| SK hynix SKHynix_HFM256GDHTNI-87A0B 256GB | 1         | 1.49%   |
| Seagate ST750LM022 HN-M750MBB 752GB       | 1         | 1.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 1         | 1.49%   |
| SanDisk SD8SBAT256G1122 256GB SSD         | 1         | 1.49%   |
| Samsung SSD 860 EVO M.2 250GB             | 1         | 1.49%   |
| Samsung MZVLQ256HAJD-000H1 256GB          | 1         | 1.49%   |
| Samsung MZALQ512HBLU-00BL2 512GB          | 1         | 1.49%   |
| Samsung MZALQ512HALU-000L2 512GB          | 1         | 1.49%   |
| Phison ESR512GTLG-E6GBTNB4 512GB          | 1         | 1.49%   |
| Phison 311CD0512GB                        | 1         | 1.49%   |
| Micron 2200V_MTFDHBA512TCK 512GB          | 1         | 1.49%   |
| Kingston SNVS500G 500GB                   | 1         | 1.49%   |
| Kimtigo SSD 256GB                         | 1         | 1.49%   |
| JMicron Generic 500GB                     | 1         | 1.49%   |
| ITHOO Tech 250GB                          | 1         | 1.49%   |
| HGST HTS721010A9E630 1TB                  | 1         | 1.49%   |
| HGST HTS545050B7E660 500GB                | 1         | 1.49%   |
| Gigabyte GP-GSM2NE3256GNTD 256GB          | 1         | 1.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 5      | 33.33%  |
| Toshiba | 2         | 4      | 22.22%  |
| Seagate | 2         | 2      | 22.22%  |
| HGST    | 2         | 2      | 22.22%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| A-DATA Technology   | 3         | 3      | 33.33%  |
| WDC                 | 1         | 1      | 11.11%  |
| Transcend           | 1         | 1      | 11.11%  |
| SanDisk             | 1         | 1      | 11.11%  |
| Samsung Electronics | 1         | 1      | 11.11%  |
| Crucial             | 1         | 1      | 11.11%  |
| Apacer              | 1         | 1      | 11.11%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 43        | 51     | 66.15%  |
| SSD     | 9         | 9      | 13.85%  |
| HDD     | 9         | 13     | 13.85%  |
| MMC     | 3         | 3      | 4.62%   |
| Unknown | 1         | 1      | 1.54%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 43        | 50     | 66.15%  |
| SATA | 17        | 22     | 26.15%  |
| MMC  | 3         | 3      | 4.62%   |
| SAS  | 2         | 2      | 3.08%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 13        | 15     | 72.22%  |
| 0.51-1.0   | 5         | 7      | 27.78%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 35        | 60.34%  |
| 251-500    | 10        | 17.24%  |
| 501-1000   | 4         | 6.9%    |
| 51-100     | 4         | 6.9%    |
| 1001-2000  | 3         | 5.17%   |
| 21-50      | 1         | 1.72%   |
| 1-20       | 1         | 1.72%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 43        | 72.88%  |
| 21-50    | 6         | 10.17%  |
| 101-250  | 4         | 6.78%   |
| 251-500  | 2         | 3.39%   |
| 501-1000 | 2         | 3.39%   |
| 51-100   | 2         | 3.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD10SPZX-24Z10 1TB              | 1         | 1      | 16.67%  |
| Toshiba MQ01ABF050 500GB            | 1         | 3      | 16.67%  |
| Toshiba MK5059GSXP 500GB            | 1         | 1      | 16.67%  |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1      | 16.67%  |
| HGST HTS721010A9E630 1TB            | 1         | 1      | 16.67%  |
| A-DATA Technology SU800 256GB SSD   | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 2         | 4      | 33.33%  |
| WDC               | 1         | 1      | 16.67%  |
| Seagate           | 1         | 1      | 16.67%  |
| HGST              | 1         | 1      | 16.67%  |
| A-DATA Technology | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 4      | 40%     |
| WDC     | 1         | 1      | 20%     |
| Seagate | 1         | 1      | 20%     |
| HGST    | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 7      | 83.33%  |
| SSD  | 1         | 1      | 16.67%  |

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
| Works    | 51        | 63     | 82.26%  |
| Malfunc  | 6         | 8      | 9.68%   |
| Detected | 5         | 6      | 8.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 44        | 46.81%  |
| Samsung Electronics          | 20        | 21.28%  |
| SanDisk                      | 6         | 6.38%   |
| Phison Electronics           | 6         | 6.38%   |
| AMD                          | 6         | 6.38%   |
| SK hynix                     | 3         | 3.19%   |
| Toshiba America Info Systems | 2         | 2.13%   |
| Silicon Motion               | 2         | 2.13%   |
| Union Memory (Shenzhen)      | 1         | 1.06%   |
| Realtek Semiconductor        | 1         | 1.06%   |
| Micron Technology            | 1         | 1.06%   |
| Kingston Technology Company  | 1         | 1.06%   |
| Unknown                      | 1         | 1.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 25        | 25.25%  |
| Samsung NVMe SSD Controller 980                                                  | 20        | 20.2%   |
| Phison PS5013 E13 NVMe Controller                                                | 5         | 5.05%   |
| Intel Tiger Lake-LP SATA Controller                                              | 5         | 5.05%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 5         | 5.05%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 4         | 4.04%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 3.03%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 3.03%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 3         | 3.03%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 2.02%   |
| SK hynix Gold P31 SSD                                                            | 2         | 2.02%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 2         | 2.02%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 2         | 2.02%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 1.01%   |
| SK hynix BC511                                                                   | 1         | 1.01%   |
| SanDisk PC SN520 NVMe SSD                                                        | 1         | 1.01%   |
| SanDisk Non-Volatile memory controller                                           | 1         | 1.01%   |
| Realtek Realtek Non-Volatile memory controller                                   | 1         | 1.01%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 1.01%   |
| Micron Non-Volatile memory controller                                            | 1         | 1.01%   |
| Kingston Company Company Non-Volatile memory controller                          | 1         | 1.01%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 1.01%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 1.01%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.01%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1         | 1.01%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.01%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 1.01%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 1.01%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 1.01%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 1         | 1.01%   |
| Unknown                                                                          | 1         | 1.01%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 50        | 51.02%  |
| NVMe | 43        | 43.88%  |
| RAID | 3         | 3.06%   |
| IDE  | 2         | 2.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 45        | 78.95%  |
| AMD    | 12        | 21.05%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8265U CPU @ 1.60GHz             | 18        | 31.58%  |
| Intel Core i5-8279U CPU @ 2.40GHz             | 5         | 8.77%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 5.26%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 2         | 3.51%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 2         | 3.51%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 3.51%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 3.51%   |
| AMD Ryzen 3 5400U with Radeon Graphics        | 2         | 3.51%   |
| AMD Ryzen 3 5300U with Radeon Graphics        | 2         | 3.51%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 1.75%   |
| Intel Pentium CPU J3710 @ 1.60GHz             | 1         | 1.75%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 1.75%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.75%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 1.75%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 1.75%   |
| Intel Core i3-9300 CPU @ 3.70GHz              | 1         | 1.75%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 1         | 1.75%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 1         | 1.75%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 1         | 1.75%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 1.75%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz       | 1         | 1.75%   |
| Intel 11th Gen Core i5-11260H @ 2.60GHz       | 1         | 1.75%   |
| Intel 11th Gen Core i3-1125G4 @ 2.00GHz       | 1         | 1.75%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 1.75%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 1         | 1.75%   |
| AMD Ryzen 5 5600U with Radeon Graphics        | 1         | 1.75%   |
| AMD Ryzen 3 4300U with Radeon Graphics        | 1         | 1.75%   |
| AMD Phenom II P820 Triple-Core Processor      | 1         | 1.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 29        | 50.88%  |
| Other            | 8         | 14.04%  |
| AMD Ryzen 5      | 5         | 8.77%   |
| AMD Ryzen 3      | 5         | 8.77%   |
| Intel Core i3    | 3         | 5.26%   |
| Intel Pentium    | 2         | 3.51%   |
| Intel Celeron    | 2         | 3.51%   |
| Intel Core 2 Duo | 1         | 1.75%   |
| AMD Ryzen 7      | 1         | 1.75%   |
| AMD Phenom II    | 1         | 1.75%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 43        | 75.44%  |
| 2      | 8         | 14.04%  |
| 6      | 5         | 8.77%   |
| 3      | 1         | 1.75%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 57        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 46        | 80.7%   |
| 1      | 11        | 19.3%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 57        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ec    | 19        | 32.76%  |
| 0x806ea    | 7         | 12.07%  |
| 0x806c1    | 6         | 10.34%  |
| 0x0a50000c | 3         | 5.17%   |
| 0x806d1    | 2         | 3.45%   |
| 0x506ca    | 2         | 3.45%   |
| 0x206a7    | 2         | 3.45%   |
| 0x08608103 | 2         | 3.45%   |
| 0x08600106 | 2         | 3.45%   |
| 0x08108102 | 2         | 3.45%   |
| 0x906eb    | 1         | 1.72%   |
| 0x906e9    | 1         | 1.72%   |
| 0x706e5    | 1         | 1.72%   |
| 0x6fa      | 1         | 1.72%   |
| 0x506c9    | 1         | 1.72%   |
| 0x406c4    | 1         | 1.72%   |
| 0x306a9    | 1         | 1.72%   |
| 0x0a50000d | 1         | 1.72%   |
| 0x08600104 | 1         | 1.72%   |
| 0x08108109 | 1         | 1.72%   |
| 0x010000c8 | 1         | 1.72%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 28        | 49.12%  |
| TigerLake   | 6         | 10.53%  |
| Zen+        | 3         | 5.26%   |
| Zen 3       | 3         | 5.26%   |
| Zen 2       | 3         | 5.26%   |
| Icelake     | 3         | 5.26%   |
| Goldmont    | 3         | 5.26%   |
| SandyBridge | 2         | 3.51%   |
| Unknown     | 2         | 3.51%   |
| Silvermont  | 1         | 1.75%   |
| K10         | 1         | 1.75%   |
| IvyBridge   | 1         | 1.75%   |
| Core        | 1         | 1.75%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 45        | 68.18%  |
| AMD    | 13        | 19.7%   |
| Nvidia | 8         | 12.12%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 18        | 26.47%  |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 7         | 10.29%  |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 5.88%   |
| AMD Renoir                                                                               | 3         | 4.41%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 4.41%   |
| AMD Cezanne                                                                              | 3         | 4.41%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 2.94%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 2.94%   |
| Intel Tiger Lake UHD Graphics                                                            | 2         | 2.94%   |
| Intel HD Graphics 500                                                                    | 2         | 2.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 2.94%   |
| AMD Lucienne                                                                             | 2         | 2.94%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 1.47%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 1.47%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 1.47%   |
| Nvidia GF119M [GeForce 610M]                                                             | 1         | 1.47%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 1.47%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 1.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.47%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 1.47%   |
| Intel HD Graphics 630                                                                    | 1         | 1.47%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.47%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 1.47%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 1         | 1.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.47%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 1.47%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 1.47%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 1         | 1.47%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 1         | 1.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 37        | 64.91%  |
| 1 x AMD        | 10        | 17.54%  |
| Intel + Nvidia | 7         | 12.28%  |
| 2 x AMD        | 1         | 1.75%   |
| Intel + AMD    | 1         | 1.75%   |
| AMD + Nvidia   | 1         | 1.75%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 55        | 93.22%  |
| Proprietary | 2         | 3.39%   |
| Unknown     | 2         | 3.39%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 39        | 66.1%   |
| 1.01-2.0   | 7         | 11.86%  |
| 3.01-4.0   | 5         | 8.47%   |
| 0.51-1.0   | 4         | 6.78%   |
| 0.01-0.5   | 4         | 6.78%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| BOE                  | 31        | 47.69%  |
| Chimei Innolux       | 7         | 10.77%  |
| LG Display           | 6         | 9.23%   |
| Samsung Electronics  | 5         | 7.69%   |
| AU Optronics         | 4         | 6.15%   |
| PANDA                | 3         | 4.62%   |
| Philips              | 2         | 3.08%   |
| ViewSonic            | 1         | 1.54%   |
| Toshiba              | 1         | 1.54%   |
| RGT                  | 1         | 1.54%   |
| Iiyama               | 1         | 1.54%   |
| HUAWEI               | 1         | 1.54%   |
| Ancor Communications | 1         | 1.54%   |
| Acer                 | 1         | 1.54%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                   | 17        | 26.15%  |
| BOE LCD Monitor BOE09C5 1920x1080 341x192mm 15.4-inch                   | 5         | 7.69%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch        | 3         | 4.62%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                   | 3         | 4.62%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 2         | 3.08%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                   | 2         | 3.08%   |
| AU Optronics LCD Monitor AUO28ED 1920x1080 344x193mm 15.5-inch          | 2         | 3.08%   |
| ViewSonic PJ VSC9B34 1920x1080                                          | 1         | 1.54%   |
| Toshiba LCD Monitor LCD58EB 1280x800 261x163mm 12.1-inch                | 1         | 1.54%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch    | 1         | 1.54%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch    | 1         | 1.54%   |
| Samsung Electronics LCD Monitor SEC314F 1600x900 382x215mm 17.3-inch    | 1         | 1.54%   |
| Samsung Electronics LCD Monitor SAM71B4 3840x2160 1872x1053mm 84.6-inch | 1         | 1.54%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch   | 1         | 1.54%   |
| RGT LCD Monitor RGT1352 1920x1080 480x270mm 21.7-inch                   | 1         | 1.54%   |
| Philips 227E4Q PHLC0A9 1920x1080 477x268mm 21.5-inch                    | 1         | 1.54%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                     | 1         | 1.54%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch                 | 1         | 1.54%   |
| PANDA LM116LF3L02 NCP000A 1920x1080 256x144mm 11.6-inch                 | 1         | 1.54%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                 | 1         | 1.54%   |
| LG Display LCD Monitor LGD0671 1920x1080 382x215mm 17.3-inch            | 1         | 1.54%   |
| LG Display LCD Monitor LGD063B 1920x1080 382x215mm 17.3-inch            | 1         | 1.54%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch            | 1         | 1.54%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch            | 1         | 1.54%   |
| LG Display LCD Monitor LGD0532 1920x1080 344x194mm 15.5-inch            | 1         | 1.54%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 1         | 1.54%   |
| Iiyama PL2493H IVM6148 1920x1080 527x296mm 23.8-inch                    | 1         | 1.54%   |
| HUAWEI ZQE-CBA HWV6A25 3440x1440 797x334mm 34.0-inch                    | 1         | 1.54%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch        | 1         | 1.54%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 1         | 1.54%   |
| BOE LCD Monitor BOE097A 1920x1080 309x174mm 14.0-inch                   | 1         | 1.54%   |
| BOE LCD Monitor BOE0936 1920x1080 344x194mm 15.5-inch                   | 1         | 1.54%   |
| BOE LCD Monitor BOE0931 2240x1400 302x189mm 14.0-inch                   | 1         | 1.54%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                    | 1         | 1.54%   |
| AU Optronics LCD Monitor AUODF87 1920x1080 344x193mm 15.5-inch          | 1         | 1.54%   |
| AU Optronics LCD Monitor AUO20ED 1920x1080 344x194mm 15.5-inch          | 1         | 1.54%   |
| Ancor Communications VE228 ACI22FA 1920x1080 477x268mm 21.5-inch        | 1         | 1.54%   |
| Acer AL1916 ACRAD49 1280x1024 376x301mm 19.0-inch                       | 1         | 1.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 50        | 81.97%  |
| 1366x768 (WXGA)  | 4         | 6.56%   |
| 3840x2160 (4K)   | 2         | 3.28%   |
| 3440x1440        | 1         | 1.64%   |
| 2240x1400        | 1         | 1.64%   |
| 1600x900 (HD+)   | 1         | 1.64%   |
| 1280x800 (WXGA)  | 1         | 1.64%   |
| 1280x1024 (SXGA) | 1         | 1.64%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 45        | 70.31%  |
| 17      | 3         | 4.69%   |
| 13      | 3         | 4.69%   |
| 84      | 2         | 3.13%   |
| 24      | 2         | 3.13%   |
| 21      | 2         | 3.13%   |
| 14      | 2         | 3.13%   |
| 34      | 1         | 1.56%   |
| 19      | 1         | 1.56%   |
| 12      | 1         | 1.56%   |
| 11      | 1         | 1.56%   |
| Unknown | 1         | 1.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 50        | 78.13%  |
| 351-400     | 4         | 6.25%   |
| 501-600     | 2         | 3.13%   |
| 401-500     | 2         | 3.13%   |
| 201-300     | 2         | 3.13%   |
| 1501-2000   | 2         | 3.13%   |
| 701-800     | 1         | 1.56%   |
| Unknown     | 1         | 1.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 54        | 93.1%   |
| 16/10 | 2         | 3.45%   |
| 5/4   | 1         | 1.72%   |
| 21/9  | 1         | 1.72%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 45        | 70.31%  |
| 81-90          | 5         | 7.81%   |
| 201-250        | 4         | 6.25%   |
| 121-130        | 3         | 4.69%   |
| More than 1000 | 2         | 3.13%   |
| 61-70          | 1         | 1.56%   |
| 51-60          | 1         | 1.56%   |
| 351-500        | 1         | 1.56%   |
| 151-200        | 1         | 1.56%   |
| Unknown        | 1         | 1.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 48        | 76.19%  |
| 101-120 | 8         | 12.7%   |
| 51-100  | 4         | 6.35%   |
| 161-240 | 2         | 3.17%   |
| Unknown | 1         | 1.59%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 49        | 85.96%  |
| 2     | 6         | 10.53%  |
| 0     | 2         | 3.51%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 42        | 56%     |
| Intel                 | 19        | 25.33%  |
| Qualcomm Atheros      | 3         | 4%      |
| MediaTek              | 3         | 4%      |
| TP-Link               | 2         | 2.67%   |
| Broadcom              | 2         | 2.67%   |
| Xiaomi                | 1         | 1.33%   |
| Samsung Electronics   | 1         | 1.33%   |
| Ralink                | 1         | 1.33%   |
| OKB SAPR              | 1         | 1.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 22        | 23.4%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 17.02%  |
| Intel Wireless 7265                                               | 6         | 6.38%   |
| Intel Ethernet Connection (6) I219-V                              | 6         | 6.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 3.19%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 3.19%   |
| Intel Wireless 3165                                               | 3         | 3.19%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 3.19%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 2.13%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 2         | 2.13%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 2.13%   |
| Intel Ethernet Controller I225-V                                  | 2         | 2.13%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 2.13%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.06%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1         | 1.06%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 1.06%   |
| TP-Link 802.11n NIC                                               | 1         | 1.06%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.06%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.06%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 1.06%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 1.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 1.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 1.06%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.06%   |
| OKB SAPR Ethernet controller                                      | 1         | 1.06%   |
| MediaTek moto e(7) power                                          | 1         | 1.06%   |
| Intel Wireless 8265 / 8275                                        | 1         | 1.06%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 1.06%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 1.06%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 1         | 1.06%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.06%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.06%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.06%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 1         | 1.06%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 32        | 54.24%  |
| Intel                 | 19        | 32.2%   |
| TP-Link               | 2         | 3.39%   |
| Qualcomm Atheros      | 2         | 3.39%   |
| MediaTek              | 2         | 3.39%   |
| Ralink                | 1         | 1.69%   |
| Broadcom              | 1         | 1.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 22        | 36.07%  |
| Intel Wireless 7265                                           | 6         | 9.84%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 3         | 4.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 3         | 4.92%   |
| Intel Wireless 3165                                           | 3         | 4.92%   |
| Intel Wi-Fi 6 AX201                                           | 3         | 4.92%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 2         | 3.28%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                    | 2         | 3.28%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 2         | 3.28%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 2         | 3.28%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                           | 1         | 1.64%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]    | 1         | 1.64%   |
| TP-Link 802.11n NIC                                           | 1         | 1.64%   |
| Realtek 802.11n WLAN Adapter                                  | 1         | 1.64%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                     | 1         | 1.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 1         | 1.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 1         | 1.64%   |
| Intel Wireless 8265 / 8275                                    | 1         | 1.64%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 1         | 1.64%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection         | 1         | 1.64%   |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 1         | 1.64%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 1         | 1.64%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 1         | 1.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 18        | 54.55%  |
| Intel                 | 9         | 27.27%  |
| Xiaomi                | 1         | 3.03%   |
| Samsung Electronics   | 1         | 3.03%   |
| Qualcomm Atheros      | 1         | 3.03%   |
| OKB SAPR              | 1         | 3.03%   |
| MediaTek              | 1         | 3.03%   |
| Broadcom              | 1         | 3.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 48.48%  |
| Intel Ethernet Connection (6) I219-V                              | 6         | 18.18%  |
| Intel Ethernet Controller I225-V                                  | 2         | 6.06%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 3.03%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 3.03%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 3.03%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 3.03%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 3.03%   |
| OKB SAPR Ethernet controller                                      | 1         | 3.03%   |
| MediaTek moto e(7) power                                          | 1         | 3.03%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 3.03%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 3.03%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 56        | 65.12%  |
| Ethernet | 30        | 34.88%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 37        | 66.07%  |
| Ethernet | 19        | 33.93%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 27        | 47.37%  |
| 1     | 27        | 47.37%  |
| 0     | 3         | 5.26%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 55        | 94.83%  |
| Yes  | 3         | 5.17%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 22        | 45.83%  |
| Intel                           | 16        | 33.33%  |
| Realtek                         | 2         | 4.17%   |
| IMC Networks                    | 2         | 4.17%   |
| Broadcom                        | 2         | 4.17%   |
| Ralink                          | 1         | 2.08%   |
| Qualcomm Atheros Communications | 1         | 2.08%   |
| Lite-On Technology              | 1         | 2.08%   |
| Foxconn / Hon Hai               | 1         | 2.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                        | 21        | 43.75%  |
| Intel Bluetooth wireless interface             | 9         | 18.75%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 4         | 8.33%   |
| Intel AX201 Bluetooth                          | 3         | 6.25%   |
| Realtek Bluetooth Radio                        | 2         | 4.17%   |
| IMC Networks Bluetooth Radio                   | 2         | 4.17%   |
| Realtek  Bluetooth 4.2 Adapter                 | 1         | 2.08%   |
| Ralink RT3290 Bluetooth                        | 1         | 2.08%   |
| Qualcomm Atheros  Bluetooth Device             | 1         | 2.08%   |
| Lite-On Wireless_Device                        | 1         | 2.08%   |
| Foxconn / Hon Hai Wireless_Device              | 1         | 2.08%   |
| Broadcom HP Portable Valentine                 | 1         | 2.08%   |
| Broadcom BCM2045 Bluetooth                     | 1         | 2.08%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel                | 45        | 71.43%  |
| AMD                  | 12        | 19.05%  |
| Nvidia               | 5         | 7.94%   |
| MosArt Semiconductor | 1         | 1.59%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Cannon Point-LP High Definition Audio Controller                                            | 25        | 33.78%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 11        | 14.86%  |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 10.81%  |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 8.11%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 4.05%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 3         | 4.05%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 2.7%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 2.7%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 2.7%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.35%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.35%   |
| Nvidia Audio device                                                                               | 1         | 1.35%   |
| MosArt Semiconductor MosArt USB Audio Device                                                      | 1         | 1.35%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 1.35%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 1.35%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 1.35%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 1.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.35%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 1.35%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 1.35%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 1.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 25        | 40.98%  |
| SK hynix            | 8         | 13.11%  |
| Micron Technology   | 5         | 8.2%    |
| Foxline             | 5         | 8.2%    |
| Crucial             | 5         | 8.2%    |
| Ramaxel Technology  | 3         | 4.92%   |
| Unknown (ABCD)      | 2         | 3.28%   |
| Unknown             | 2         | 3.28%   |
| Elpida              | 2         | 3.28%   |
| Qumo                | 1         | 1.64%   |
| Kingston            | 1         | 1.64%   |
| King Tiger          | 1         | 1.64%   |
| Unknown             | 1         | 1.64%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 17        | 27.42%  |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 3         | 4.84%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 3         | 4.84%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 3.23%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 3.23%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 3.23%   |
| Foxline RAM FL3200D4S22-8G 8GB SODIMM DDR4 3200MT/s              | 2         | 3.23%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 1.61%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                        | 1         | 1.61%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.61%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.61%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.61%   |
| Samsung RAM M471B5773DH0-CK0 2048MB SODIMM DDR3 1600MT/s         | 1         | 1.61%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.61%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.61%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 1.61%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.61%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.61%   |
| Ramaxel RAM RMSA3310MJ86H9F-3200 4GB SODIMM DDR4 3200MT/s        | 1         | 1.61%   |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s       | 1         | 1.61%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 1         | 1.61%   |
| Qumo RAM QUM4S-8G3200P22 8GB SODIMM DDR4 3200MT/s                | 1         | 1.61%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 1         | 1.61%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 1         | 1.61%   |
| Kingston RAM HP32D4S2S1ME-4 4096MB SODIMM DDR4 3200MT/s          | 1         | 1.61%   |
| King Tiger RAM KT8GS4AE8 8GB SODIMM DDR4 3200MT/s                | 1         | 1.61%   |
| Foxline RAM FL2666D4S19-8G 8GB SODIMM DDR4 2667MT/s              | 1         | 1.61%   |
| Foxline RAM FL2400D4S17S-8G 8GB SODIMM DDR4 2400MT/s             | 1         | 1.61%   |
| Foxline RAM FL2400D4S17-8G 8GB SODIMM DDR4 2400MT/s              | 1         | 1.61%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 1         | 1.61%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s            | 1         | 1.61%   |
| Elpida RAM EBJ20UF8BCS0-DJ-F 2GB SODIMM DDR3 1334MT/s            | 1         | 1.61%   |
| Crucial RAM CT8G4SFS832A.M8FR 8GB SODIMM DDR4 3200MT/s           | 1         | 1.61%   |
| Crucial RAM CT8G4SFS832A.C8FN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.61%   |
| Crucial RAM CT8G4SFRA32A.C8FN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.61%   |
| Crucial RAM CT8G4SFRA266.C8FJ 8GB SODIMM DDR4 2667MT/s           | 1         | 1.61%   |
| Crucial RAM CB8GS2666.C8ET 8GB SODIMM DDR4 2667MT/s              | 1         | 1.61%   |
| Unknown                                                          | 1         | 1.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 47        | 85.45%  |
| DDR3   | 5         | 9.09%   |
| LPDDR4 | 2         | 3.64%   |
| DDR2   | 1         | 1.82%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 50        | 86.21%  |
| Row Of Chips | 7         | 12.07%  |
| DIMM         | 1         | 1.72%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 37        | 63.79%  |
| 4096  | 14        | 24.14%  |
| 2048  | 4         | 6.9%    |
| 16384 | 2         | 3.45%   |
| 1024  | 1         | 1.72%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 27        | 48.21%  |
| 3200  | 18        | 32.14%  |
| 2400  | 4         | 7.14%   |
| 1600  | 2         | 3.57%   |
| 3266  | 1         | 1.79%   |
| 1866  | 1         | 1.79%   |
| 1334  | 1         | 1.79%   |
| 1066  | 1         | 1.79%   |
| 667   | 1         | 1.79%   |

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
| Syntek                                 | 18        | 32.14%  |
| Chicony Electronics                    | 13        | 23.21%  |
| IMC Networks                           | 8         | 14.29%  |
| Acer                                   | 4         | 7.14%   |
| USB Camera CS                          | 2         | 3.57%   |
| Sunplus Innovation Technology          | 2         | 3.57%   |
| Quanta                                 | 2         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.57%   |
| Suyin                                  | 1         | 1.79%   |
| SunplusIT                              | 1         | 1.79%   |
| Microdia                               | 1         | 1.79%   |
| Luxvisions Innotech Limited            | 1         | 1.79%   |
| Alcor Micro                            | 1         | 1.79%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                                                   | 18        | 32.14%  |
| Chicony USB camera                                                         | 7         | 12.5%   |
| IMC Networks Integrated Camera                                             | 3         | 5.36%   |
| Acer Integrated Camera                                                     | 3         | 5.36%   |
| USB Camera CS USB Camera CS                                                | 2         | 3.57%   |
| IMC Networks ov9734_azurewave_camera                                       | 2         | 3.57%   |
| Chicony HD User Facing                                                     | 2         | 3.57%   |
| Suyin Acer CrystalEye Webcam                                               | 1         | 1.79%   |
| SunplusIT USB camera                                                       | 1         | 1.79%   |
| Sunplus BKX Usb FHD Camera                                                 | 1         | 1.79%   |
| Sunplus Asus Webcam                                                        | 1         | 1.79%   |
| Quanta USB HD Webcam                                                       | 1         | 1.79%   |
| Quanta HD Camera                                                           | 1         | 1.79%   |
| Microdia USB Live camera                                                   | 1         | 1.79%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 1         | 1.79%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 1         | 1.79%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 1.79%   |
| IMC Networks HD Camera                                                     | 1         | 1.79%   |
| Chicony USB2.0 Camera                                                      | 1         | 1.79%   |
| Chicony Integrated Camera                                                  | 1         | 1.79%   |
| Chicony HP Webcam-50                                                       | 1         | 1.79%   |
| Chicony HP TrueVision HD Camera                                            | 1         | 1.79%   |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M Webcam              | 1         | 1.79%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 1         | 1.79%   |
| Alcor Micro USB 2.0 WebCamera                                              | 1         | 1.79%   |
| Acer BisonCam, NB Pro                                                      | 1         | 1.79%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 5         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device | 5         | 100%    |

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
| 0     | 46        | 77.97%  |
| 1     | 11        | 18.64%  |
| 2     | 2         | 3.39%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Net/wireless       | 5         | 33.33%  |
| Fingerprint reader | 5         | 33.33%  |
| Graphics card      | 3         | 20%     |
| Net/ethernet       | 1         | 6.67%   |
| Bluetooth          | 1         | 6.67%   |

