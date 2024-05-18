Q4OS - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------

A project to collect tested hardware configurations for Q4OS.

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire V5-121               | [ee7af6bc3d](https://linux-hardware.org/?probe=ee7af6bc3d) | May 09, 2024 |
| Samsung       | N150P/N210P/N220P           | [d6fca9f7f5](https://linux-hardware.org/?probe=d6fca9f7f5) | Apr 13, 2024 |
| HP            | ProBook 650 G1              | [d81b4ee2e3](https://linux-hardware.org/?probe=d81b4ee2e3) | Apr 03, 2024 |
| Panasonic     | CF-S10CWHDS                 | [a4c273ab7b](https://linux-hardware.org/?probe=a4c273ab7b) | Mar 19, 2024 |
| MSI           | Alpha 17 C7VF               | [d22dedc33d](https://linux-hardware.org/?probe=d22dedc33d) | Mar 12, 2024 |
| Dell          | Latitude D530               | [0885268edd](https://linux-hardware.org/?probe=0885268edd) | Feb 20, 2024 |
| Dell          | Latitude D530               | [e4d1a73b6e](https://linux-hardware.org/?probe=e4d1a73b6e) | Feb 20, 2024 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [c246a6b564](https://linux-hardware.org/?probe=c246a6b564) | Jan 30, 2024 |
| HP            | Pavilion dv1000 (EW489EA... | [ea4b49f529](https://linux-hardware.org/?probe=ea4b49f529) | Jan 17, 2024 |
| Matsushita... | CF-29LAQGZBM                | [433fd9b78e](https://linux-hardware.org/?probe=433fd9b78e) | Jan 11, 2024 |
| Toshiba       | Satellite L515              | [a7ec902190](https://linux-hardware.org/?probe=a7ec902190) | Jan 10, 2024 |
| Irbis         | NB264                       | [b7da9b39c3](https://linux-hardware.org/?probe=b7da9b39c3) | Dec 31, 2023 |
| IBM           | ThinkPad T43 1875DMU        | [a33e9f7b0d](https://linux-hardware.org/?probe=a33e9f7b0d) | Dec 31, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [f526bc07cf](https://linux-hardware.org/?probe=f526bc07cf) | Nov 25, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [7b53c24f1e](https://linux-hardware.org/?probe=7b53c24f1e) | Nov 25, 2023 |
| Dell          | Latitude E6430              | [ac45698de6](https://linux-hardware.org/?probe=ac45698de6) | Nov 13, 2023 |
| Apple         | MacBook4,1                  | [efc04e4b27](https://linux-hardware.org/?probe=efc04e4b27) | Oct 01, 2023 |
| Acer          | Aspire one                  | [d040844540](https://linux-hardware.org/?probe=d040844540) | Sep 27, 2023 |
| Acer          | Aspire 1700                 | [a76fb24570](https://linux-hardware.org/?probe=a76fb24570) | Aug 31, 2023 |
| MSI           | U90/U100                    | [015b95ba2a](https://linux-hardware.org/?probe=015b95ba2a) | Jul 31, 2023 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [8424587178](https://linux-hardware.org/?probe=8424587178) | Jul 27, 2023 |
| ASUSTek       | K53SJ                       | [922c017262](https://linux-hardware.org/?probe=922c017262) | Jun 26, 2023 |
| Dell          | Latitude D630               | [ead768adbd](https://linux-hardware.org/?probe=ead768adbd) | May 27, 2023 |
| Sony          | VGN-FW21Z                   | [aac218a1e0](https://linux-hardware.org/?probe=aac218a1e0) | May 20, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3505     | [2b0f3e8867](https://linux-hardware.org/?probe=2b0f3e8867) | Mar 25, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3505     | [8bb2484825](https://linux-hardware.org/?probe=8bb2484825) | Mar 25, 2023 |
| Google        | Reks                        | [be1a98408d](https://linux-hardware.org/?probe=be1a98408d) | Feb 28, 2023 |
| HP            | ProBook 650 G1              | [4e6687829e](https://linux-hardware.org/?probe=4e6687829e) | Feb 19, 2023 |
| Lenovo        | IdeaPad 5 14IAL7 82SD       | [cd5e470881](https://linux-hardware.org/?probe=cd5e470881) | Feb 17, 2023 |
| IBM           | ThinkPad T42 2378FVU        | [ce2f3fb897](https://linux-hardware.org/?probe=ce2f3fb897) | Dec 21, 2022 |
| IBM           | ThinkPad T42 2378FVU        | [50f1d0a765](https://linux-hardware.org/?probe=50f1d0a765) | Dec 19, 2022 |
| IBM           | ThinkPad T42 2378FVU        | [fe6bdea3fd](https://linux-hardware.org/?probe=fe6bdea3fd) | Dec 19, 2022 |
| Google        | Cave                        | [ce7f60e0ee](https://linux-hardware.org/?probe=ce7f60e0ee) | Nov 06, 2022 |
| Google        | Cave                        | [63e06049da](https://linux-hardware.org/?probe=63e06049da) | Nov 06, 2022 |
| Medion        | P6620                       | [e5db2a930b](https://linux-hardware.org/?probe=e5db2a930b) | Aug 22, 2022 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | [ee35a21db4](https://linux-hardware.org/?probe=ee35a21db4) | Jun 30, 2022 |
| Sony          | VGN-P11Z_Q                  | [e51be2b6a4](https://linux-hardware.org/?probe=e51be2b6a4) | Jun 16, 2022 |
| Toshiba       | Satellite M70               | [61617a3561](https://linux-hardware.org/?probe=61617a3561) | Jun 05, 2022 |
| HP            | 250 G5 Notebook PC          | [0e5792fc9f](https://linux-hardware.org/?probe=0e5792fc9f) | May 15, 2022 |
| ASUSTek       | A6U                         | [4a8ad00e5e](https://linux-hardware.org/?probe=4a8ad00e5e) | May 12, 2022 |
| Toshiba       | Satellite Pro L500          | [5b72ea9a47](https://linux-hardware.org/?probe=5b72ea9a47) | May 02, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [8cdcd8d130](https://linux-hardware.org/?probe=8cdcd8d130) | Apr 08, 2022 |
| Acer          | AO751h                      | [23737182d1](https://linux-hardware.org/?probe=23737182d1) | Mar 21, 2022 |
| AMI           | Intel                       | [6d581b03a6](https://linux-hardware.org/?probe=6d581b03a6) | Mar 19, 2022 |
| ASUSTek       | X540YA                      | [0cd3840828](https://linux-hardware.org/?probe=0cd3840828) | Mar 14, 2022 |
| Visual Lan... | Premier 10                  | [64450e11a3](https://linux-hardware.org/?probe=64450e11a3) | Feb 04, 2022 |
| HP            | Presario CQ56               | [8d03d80424](https://linux-hardware.org/?probe=8d03d80424) | Jan 14, 2022 |
| HP            | Presario CQ56               | [a0bc0364a8](https://linux-hardware.org/?probe=a0bc0364a8) | Jan 08, 2022 |
| MSI           | U210                        | [24eb05a4d9](https://linux-hardware.org/?probe=24eb05a4d9) | Dec 29, 2021 |
| Toshiba       | Satellite C660              | [b159811d48](https://linux-hardware.org/?probe=b159811d48) | Dec 12, 2021 |
| Toshiba       | Satellite C660              | [2197770fd0](https://linux-hardware.org/?probe=2197770fd0) | Dec 12, 2021 |
| ASUSTek       | T12Eg                       | [115e8b584f](https://linux-hardware.org/?probe=115e8b584f) | Dec 11, 2021 |
| Toshiba       | Satellite C660              | [64521297e2](https://linux-hardware.org/?probe=64521297e2) | Dec 07, 2021 |
| Toshiba       | Satellite C660              | [b6a5bb8982](https://linux-hardware.org/?probe=b6a5bb8982) | Dec 06, 2021 |
| Phoenix/Si... | M720SR                      | [f92c7e8c3e](https://linux-hardware.org/?probe=f92c7e8c3e) | Oct 09, 2021 |
| HP            | Laptop 15s-fq2xxx           | [cfa6202518](https://linux-hardware.org/?probe=cfa6202518) | Sep 14, 2021 |
| HP            | Laptop 15s-fq2xxx           | [726c3230ef](https://linux-hardware.org/?probe=726c3230ef) | Sep 14, 2021 |
| Chuwi         | GemiBook Pro                | [ebe8d67a10](https://linux-hardware.org/?probe=ebe8d67a10) | Sep 04, 2021 |
| HP            | ProBook 450 G2              | [dbba9b9771](https://linux-hardware.org/?probe=dbba9b9771) | Jul 30, 2021 |
| JVC           | J3N                         | [f8da57e850](https://linux-hardware.org/?probe=f8da57e850) | Jul 09, 2021 |
| HP            | ProBook 6550b               | [b192718656](https://linux-hardware.org/?probe=b192718656) | Mar 13, 2021 |
| HP            | 2000                        | [736561e497](https://linux-hardware.org/?probe=736561e497) | Mar 07, 2021 |
| ASUSTek       | A6JC                        | [b04f51dd1c](https://linux-hardware.org/?probe=b04f51dd1c) | Jan 29, 2021 |
| ASUSTek       | A6JC                        | [097dd7f151](https://linux-hardware.org/?probe=097dd7f151) | Jan 29, 2021 |
| Lenovo        | ThinkPad 11e 20DAS0PS00     | [2d618b7420](https://linux-hardware.org/?probe=2d618b7420) | Dec 14, 2020 |
| Packard Be... | EasyNote LM81               | [d6b0c23c18](https://linux-hardware.org/?probe=d6b0c23c18) | Nov 23, 2020 |
| Qilive        | QW19141AMSP                 | [b8f3486ae1](https://linux-hardware.org/?probe=b8f3486ae1) | Aug 27, 2020 |
| HP            | OmniBook PC                 | [5e33febbc1](https://linux-hardware.org/?probe=5e33febbc1) | Jul 10, 2020 |
| Medion        | Unknown                     | [6a06a14f6a](https://linux-hardware.org/?probe=6a06a14f6a) | May 07, 2020 |
| Philco        | 14I                         | [bf4c449b31](https://linux-hardware.org/?probe=bf4c449b31) | Apr 14, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Q4OS 4 | 27        | 46.55%  |
| Q4OS 5 | 17        | 29.31%  |
| Q4OS 3 | 11        | 18.97%  |
| Q4OS 2 | 3         | 5.17%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| Q4OS | 58        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 6.1.0-18-amd64       | 4         | 6.9%    |
| 5.10.0-23-amd64      | 4         | 6.9%    |
| 5.10.0-21-amd64      | 3         | 5.17%   |
| 5.10.0-12-amd64      | 3         | 5.17%   |
| 4.19.0-17-amd64      | 3         | 5.17%   |
| 6.1.0-17-686-pae     | 2         | 3.45%   |
| 6.1.0-13-amd64       | 2         | 3.45%   |
| 5.10.0-8-amd64       | 2         | 3.45%   |
| 5.10.0-14-686-pae    | 2         | 3.45%   |
| 6.6.8-x64v1-xanmod1  | 1         | 1.72%   |
| 6.5.0-4-amd64        | 1         | 1.72%   |
| 6.1.0-21-amd64       | 1         | 1.72%   |
| 6.1.0-17-amd64       | 1         | 1.72%   |
| 6.1.0-16-686-pae     | 1         | 1.72%   |
| 6.1.0-12-amd64       | 1         | 1.72%   |
| 6.1.0-12-686-pae     | 1         | 1.72%   |
| 6.1.0-11-686-pae     | 1         | 1.72%   |
| 6.1.0-10-686-pae     | 1         | 1.72%   |
| 5.9.0-5-amd64        | 1         | 1.72%   |
| 5.6.0-1-amd64        | 1         | 1.72%   |
| 5.18.0-0.bpo.1-amd64 | 1         | 1.72%   |
| 5.10.0-9-amd64       | 1         | 1.72%   |
| 5.10.0-8-686-pae     | 1         | 1.72%   |
| 5.10.0-21-686-pae    | 1         | 1.72%   |
| 5.10.0-20-686        | 1         | 1.72%   |
| 5.10.0-17-amd64      | 1         | 1.72%   |
| 5.10.0-15-686-pae    | 1         | 1.72%   |
| 5.10.0-13-amd64      | 1         | 1.72%   |
| 5.10.0-12-686-pae    | 1         | 1.72%   |
| 5.10.0-11-686-pae    | 1         | 1.72%   |
| 5.10.0-10-686-pae    | 1         | 1.72%   |
| 4.9.0-8-amd64        | 1         | 1.72%   |
| 4.9.0-14-686-pae     | 1         | 1.72%   |
| 4.9.0-12-686-pae     | 1         | 1.72%   |
| 4.19.0-22-amd64      | 1         | 1.72%   |
| 4.19.0-20-amd64      | 1         | 1.72%   |
| 4.19.0-18-amd64      | 1         | 1.72%   |
| 4.19.0-17-686        | 1         | 1.72%   |
| 4.19.0-14-amd64      | 1         | 1.72%   |
| 4.19.0-13-amd64      | 1         | 1.72%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 24        | 41.38%  |
| 6.1.0   | 15        | 25.86%  |
| 4.19.0  | 11        | 18.97%  |
| 4.9.0   | 3         | 5.17%   |
| 6.6.8   | 1         | 1.72%   |
| 6.5.0   | 1         | 1.72%   |
| 5.9.0   | 1         | 1.72%   |
| 5.6.0   | 1         | 1.72%   |
| 5.18.0  | 1         | 1.72%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 24        | 41.38%  |
| 6.1     | 15        | 25.86%  |
| 4.19    | 11        | 18.97%  |
| 4.9     | 3         | 5.17%   |
| 6.6     | 1         | 1.72%   |
| 6.5     | 1         | 1.72%   |
| 5.9     | 1         | 1.72%   |
| 5.6     | 1         | 1.72%   |
| 5.18    | 1         | 1.72%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 40        | 68.97%  |
| i686   | 18        | 31.03%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| KDE5     | 29        | 50%     |
| trinity  | 27        | 46.55%  |
| KDE      | 1         | 1.72%   |
| Cinnamon | 1         | 1.72%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 56        | 96.55%  |
| Wayland | 1         | 1.72%   |
| Tty     | 1         | 1.72%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SDDM | 31        | 53.45%  |
| TDM  | 27        | 46.55%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 29        | 50%     |
| en_GB   | 5         | 8.62%   |
| de_DE   | 4         | 6.9%    |
| it_IT   | 3         | 5.17%   |
| es_ES   | 3         | 5.17%   |
| ru_RU   | 2         | 3.45%   |
| hu_HU   | 2         | 3.45%   |
| fr_FR   | 2         | 3.45%   |
| sv_SE   | 1         | 1.72%   |
| sl_SI   | 1         | 1.72%   |
| pl_PL   | 1         | 1.72%   |
| hr_HR   | 1         | 1.72%   |
| es_VE   | 1         | 1.72%   |
| en_SG   | 1         | 1.72%   |
| C       | 1         | 1.72%   |
| Unknown | 1         | 1.72%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 38        | 65.52%  |
| EFI  | 20        | 34.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 56        | 96.55%  |
| Overlay | 2         | 3.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 38        | 65.52%  |
| GPT     | 19        | 32.76%  |
| Unknown | 1         | 1.72%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 51        | 87.93%  |
| Yes       | 7         | 12.07%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 42        | 72.41%  |
| Yes       | 16        | 27.59%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Hewlett-Packard                | 10        | 17.24%  |
| Lenovo                         | 6         | 10.34%  |
| Toshiba                        | 5         | 8.62%   |
| ASUSTek Computer               | 5         | 8.62%   |
| Acer                           | 4         | 6.9%    |
| MSI                            | 3         | 5.17%   |
| Dell                           | 3         | 5.17%   |
| Sony                           | 2         | 3.45%   |
| Medion                         | 2         | 3.45%   |
| IBM                            | 2         | 3.45%   |
| Google                         | 2         | 3.45%   |
| Visual Land                    | 1         | 1.72%   |
| Qilive                         | 1         | 1.72%   |
| Phoenix/SiS                    | 1         | 1.72%   |
| Philco                         | 1         | 1.72%   |
| Panasonic                      | 1         | 1.72%   |
| Packard Bell                   | 1         | 1.72%   |
| Matsushita Electric Industrial | 1         | 1.72%   |
| JVC                            | 1         | 1.72%   |
| Irbis                          | 1         | 1.72%   |
| Fujitsu Siemens                | 1         | 1.72%   |
| Framework                      | 1         | 1.72%   |
| Chuwi                          | 1         | 1.72%   |
| Apple                          | 1         | 1.72%   |
| AMI                            | 1         | 1.72%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Toshiba Satellite C660                      | 2         | 3.45%   |
| HP ProBook 650 G1                           | 2         | 3.45%   |
| Visual Land Premier 10                      | 1         | 1.72%   |
| Toshiba Satellite Pro L500                  | 1         | 1.72%   |
| Toshiba Satellite M70                       | 1         | 1.72%   |
| Toshiba Satellite L515                      | 1         | 1.72%   |
| Sony VGN-P11Z_Q                             | 1         | 1.72%   |
| Sony VGN-FW21Z                              | 1         | 1.72%   |
| Qilive QW19141AMSP                          | 1         | 1.72%   |
| Phoenix/SiS M720SR                          | 1         | 1.72%   |
| Philco 14I                                  | 1         | 1.72%   |
| Panasonic CF-S10CWHDS                       | 1         | 1.72%   |
| Packard Bell EasyNote LM81                  | 1         | 1.72%   |
| MSI U90/U100                                | 1         | 1.72%   |
| MSI U210                                    | 1         | 1.72%   |
| MSI Alpha 17 C7VF                           | 1         | 1.72%   |
| Medion P6620                                | 1         | 1.72%   |
| Matsushita Electric Industrial CF-29LAQGZBM | 1         | 1.72%   |
| Lenovo ThinkPad T495 20NKS0PG00             | 1         | 1.72%   |
| Lenovo ThinkPad 11e 20DAS0PS00              | 1         | 1.72%   |
| Lenovo IdeaPad S145-15AST 81N3              | 1         | 1.72%   |
| Lenovo IdeaPad 5 14IAL7 82SD                | 1         | 1.72%   |
| Lenovo IdeaPad 330S-14IKB 81F4              | 1         | 1.72%   |
| Lenovo IdeaPad 330-15IGM 81D1               | 1         | 1.72%   |
| JVC J3N                                     | 1         | 1.72%   |
| Irbis NB264                                 | 1         | 1.72%   |
| IBM ThinkPad T43 1875DMU                    | 1         | 1.72%   |
| IBM ThinkPad T42 2378FVU                    | 1         | 1.72%   |
| HP ProBook 6550b                            | 1         | 1.72%   |
| HP ProBook 450 G2                           | 1         | 1.72%   |
| HP Presario CQ56                            | 1         | 1.72%   |
| HP Pavilion dv1000 (EW489EA#ABZ)            | 1         | 1.72%   |
| HP OmniBook PC                              | 1         | 1.72%   |
| HP Laptop 15s-fq2xxx                        | 1         | 1.72%   |
| HP 250 G5 Notebook PC                       | 1         | 1.72%   |
| HP 2000                                     | 1         | 1.72%   |
| Google Reks                                 | 1         | 1.72%   |
| Google Cave                                 | 1         | 1.72%   |
| Fujitsu Siemens AMILO Pro Edition V3505     | 1         | 1.72%   |
| Framework Laptop 13 (AMD Ryzen 7040Series)  | 1         | 1.72%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Toshiba Satellite                           | 5         | 8.62%   |
| Lenovo IdeaPad                              | 4         | 6.9%    |
| HP ProBook                                  | 4         | 6.9%    |
| Dell Latitude                               | 3         | 5.17%   |
| Acer Aspire                                 | 3         | 5.17%   |
| Lenovo ThinkPad                             | 2         | 3.45%   |
| IBM ThinkPad                                | 2         | 3.45%   |
| Visual Land Premier                         | 1         | 1.72%   |
| Sony VGN-P11Z                               | 1         | 1.72%   |
| Sony VGN-FW21Z                              | 1         | 1.72%   |
| Qilive QW19141AMSP                          | 1         | 1.72%   |
| Phoenix/SiS M720SR                          | 1         | 1.72%   |
| Philco 14I                                  | 1         | 1.72%   |
| Panasonic CF-S10CWHDS                       | 1         | 1.72%   |
| Packard Bell EasyNote                       | 1         | 1.72%   |
| MSI U90                                     | 1         | 1.72%   |
| MSI U210                                    | 1         | 1.72%   |
| MSI Alpha                                   | 1         | 1.72%   |
| Medion P6620                                | 1         | 1.72%   |
| Matsushita Electric Industrial CF-29LAQGZBM | 1         | 1.72%   |
| JVC J3N                                     | 1         | 1.72%   |
| Irbis NB264                                 | 1         | 1.72%   |
| HP Presario                                 | 1         | 1.72%   |
| HP Pavilion                                 | 1         | 1.72%   |
| HP OmniBook                                 | 1         | 1.72%   |
| HP Laptop                                   | 1         | 1.72%   |
| HP 250                                      | 1         | 1.72%   |
| HP 2000                                     | 1         | 1.72%   |
| Google Reks                                 | 1         | 1.72%   |
| Google Cave                                 | 1         | 1.72%   |
| Fujitsu Siemens AMILO                       | 1         | 1.72%   |
| Framework Laptop                            | 1         | 1.72%   |
| Chuwi GemiBook                              | 1         | 1.72%   |
| ASUS X540YA                                 | 1         | 1.72%   |
| ASUS T12Eg                                  | 1         | 1.72%   |
| ASUS K53SJ                                  | 1         | 1.72%   |
| ASUS A6U                                    | 1         | 1.72%   |
| ASUS A6JC                                   | 1         | 1.72%   |
| Apple MacBook4                              | 1         | 1.72%   |
| AMI Intel                                   | 1         | 1.72%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2009    | 7         | 12.07%  |
| 2010    | 5         | 8.62%   |
| 2008    | 4         | 6.9%    |
| 2005    | 4         | 6.9%    |
| 2023    | 3         | 5.17%   |
| 2020    | 3         | 5.17%   |
| 2019    | 3         | 5.17%   |
| 2018    | 3         | 5.17%   |
| 2012    | 3         | 5.17%   |
| 2007    | 3         | 5.17%   |
| 2022    | 2         | 3.45%   |
| 2016    | 2         | 3.45%   |
| 2014    | 2         | 3.45%   |
| 2013    | 2         | 3.45%   |
| 2011    | 2         | 3.45%   |
| 2006    | 2         | 3.45%   |
| 2004    | 2         | 3.45%   |
| Unknown | 2         | 3.45%   |
| 2021    | 1         | 1.72%   |
| 2017    | 1         | 1.72%   |
| 2015    | 1         | 1.72%   |
| 2003    | 1         | 1.72%   |

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
| Disabled | 55        | 94.83%  |
| Enabled  | 3         | 5.17%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 56        | 96.55%  |
| Yes  | 2         | 3.45%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 21        | 36.21%  |
| 4.01-8.0   | 9         | 15.52%  |
| 2.01-3.0   | 8         | 13.79%  |
| 1.01-2.0   | 7         | 12.07%  |
| 0.01-0.5   | 4         | 6.9%    |
| 8.01-16.0  | 3         | 5.17%   |
| 0.51-1.0   | 3         | 5.17%   |
| 16.01-24.0 | 2         | 3.45%   |
| 24.01-32.0 | 1         | 1.72%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 26        | 44.83%  |
| 0.51-1.0 | 11        | 18.97%  |
| 2.01-3.0 | 10        | 17.24%  |
| 0.01-0.5 | 7         | 12.07%  |
| 4.01-8.0 | 2         | 3.45%   |
| 3.01-4.0 | 2         | 3.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 47        | 81.03%  |
| 2      | 9         | 15.52%  |
| 3      | 2         | 3.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 33        | 56.9%   |
| No        | 25        | 43.1%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 81.03%  |
| No        | 11        | 18.97%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 55        | 94.83%  |
| No        | 3         | 5.17%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 32        | 55.17%  |
| Yes       | 26        | 44.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 13        | 22.41%  |
| UK           | 5         | 8.62%   |
| Italy        | 4         | 6.9%    |
| Germany      | 4         | 6.9%    |
| Spain        | 3         | 5.17%   |
| Kenya        | 3         | 5.17%   |
| Slovenia     | 2         | 3.45%   |
| Russia       | 2         | 3.45%   |
| Romania      | 2         | 3.45%   |
| Poland       | 2         | 3.45%   |
| Hungary      | 2         | 3.45%   |
| Croatia      | 2         | 3.45%   |
| Venezuela    | 1         | 1.72%   |
| Turkey       | 1         | 1.72%   |
| Switzerland  | 1         | 1.72%   |
| Sweden       | 1         | 1.72%   |
| Singapore    | 1         | 1.72%   |
| Saudi Arabia | 1         | 1.72%   |
| Qatar        | 1         | 1.72%   |
| Mexico       | 1         | 1.72%   |
| France       | 1         | 1.72%   |
| Canada       | 1         | 1.72%   |
| Brazil       | 1         | 1.72%   |
| Belgium      | 1         | 1.72%   |
| Belarus      | 1         | 1.72%   |
| Algeria      | 1         | 1.72%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Jacksonville          | 5         | 8.62%   |
| Nairobi               | 3         | 5.17%   |
| Swindon               | 2         | 3.45%   |
| Mesa                  | 2         | 3.45%   |
| Ljubljana             | 2         | 3.45%   |
| Drobeta-Turnu Severin | 2         | 3.45%   |
| Budapest              | 2         | 3.45%   |
| Zagreb                | 1         | 1.72%   |
| West Corinth          | 1         | 1.72%   |
| Volgograd             | 1         | 1.72%   |
| Tenbury Wells         | 1         | 1.72%   |
| Tellico Plains        | 1         | 1.72%   |
| Sosnowiec             | 1         | 1.72%   |
| Sint-Pieters-Leeuw    | 1         | 1.72%   |
| Singapore             | 1         | 1.72%   |
| Sétif                | 1         | 1.72%   |
| Schermbeck            | 1         | 1.72%   |
| Salsomaggiore Terme   | 1         | 1.72%   |
| Rostock               | 1         | 1.72%   |
| Rijeka                | 1         | 1.72%   |
| Puerto Cumarebo       | 1         | 1.72%   |
| Moscow                | 1         | 1.72%   |
| Morelia               | 1         | 1.72%   |
| Mooresville           | 1         | 1.72%   |
| Moirans               | 1         | 1.72%   |
| Mogilev               | 1         | 1.72%   |
| Milano                | 1         | 1.72%   |
| Mannheim              | 1         | 1.72%   |
| Londrina              | 1         | 1.72%   |
| Little Current        | 1         | 1.72%   |
| Leipzig               | 1         | 1.72%   |
| Lausanne              | 1         | 1.72%   |
| Las Vegas             | 1         | 1.72%   |
| Klaudyn               | 1         | 1.72%   |
| Jönköping           | 1         | 1.72%   |
| Indianapolis          | 1         | 1.72%   |
| Giussano              | 1         | 1.72%   |
| Gijón                | 1         | 1.72%   |
| Fulham                | 1         | 1.72%   |
| Fayetteville          | 1         | 1.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 7      | 11.11%  |
| Unknown             | 7         | 7      | 11.11%  |
| Seagate             | 7         | 7      | 11.11%  |
| Samsung Electronics | 7         | 8      | 11.11%  |
| Toshiba             | 5         | 5      | 7.94%   |
| Kingston            | 5         | 5      | 7.94%   |
| Hitachi             | 5         | 5      | 7.94%   |
| SanDisk             | 3         | 3      | 4.76%   |
| Fujitsu             | 3         | 3      | 4.76%   |
| KESU                | 2         | 2      | 3.17%   |
| HGST                | 2         | 2      | 3.17%   |
| China               | 2         | 2      | 3.17%   |
| A-DATA Technology   | 2         | 2      | 3.17%   |
| Silicon Motion      | 1         | 1      | 1.59%   |
| PNY                 | 1         | 1      | 1.59%   |
| Phison              | 1         | 1      | 1.59%   |
| KingSpec            | 1         | 1      | 1.59%   |
| KBG40ZNV            | 1         | 1      | 1.59%   |
| Unknown             | 1         | 1      | 1.59%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB            | 2         | 3.17%   |
| Kingston SA400S37240G 240GB SSD      | 2         | 3.17%   |
| KESU USB 3.1 256GB                   | 2         | 3.17%   |
| A-DATA SU630 240GB SSD               | 2         | 3.17%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 1.59%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 1.59%   |
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 1.59%   |
| WDC WD3200BEKT-75PVMT1 320GB         | 1         | 1.59%   |
| WDC WD2500BEVT-60A23T0 250GB         | 1         | 1.59%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 1         | 1.59%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 1.59%   |
| Unknown USDU1  32GB                  | 1         | 1.59%   |
| Unknown SLD64G  64GB                 | 1         | 1.59%   |
| Unknown SD/MMC/MS PRO 128GB          | 1         | 1.59%   |
| Unknown S0J59X  128GB                | 1         | 1.59%   |
| Unknown MMC Card  64GB               | 1         | 1.59%   |
| Unknown HAG2e  16GB                  | 1         | 1.59%   |
| Unknown 064G38  64GB                 | 1         | 1.59%   |
| Toshiba MK8032GAX 80GB               | 1         | 1.59%   |
| Toshiba MK8025GAS 80GB               | 1         | 1.59%   |
| Toshiba MK6028GAL 64GB               | 1         | 1.59%   |
| Toshiba MK3276GSX 320GB              | 1         | 1.59%   |
| Toshiba MK3252GSX 320GB              | 1         | 1.59%   |
| Silicon Motion NVME SSD 512GB        | 1         | 1.59%   |
| Seagate ST96812AS 64GB               | 1         | 1.59%   |
| Seagate ST9500325AS 500GB            | 1         | 1.59%   |
| Seagate ST9120822AS 120GB            | 1         | 1.59%   |
| Seagate ST380012A 80GB               | 1         | 1.59%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 1.59%   |
| Seagate BUP RD 5TB                   | 1         | 1.59%   |
| Seagate Backup+ SL 1TB               | 1         | 1.59%   |
| SanDisk SDCFX-032G SSD               | 1         | 1.59%   |
| SanDisk SD8SN8U1T001122 1TB SSD      | 1         | 1.59%   |
| SanDisk NVMe SSD Drive 250GB         | 1         | 1.59%   |
| Samsung MZVL21T0HCLR-00B00 1TB       | 1         | 1.59%   |
| Samsung MZALQ256HBJD-00BL1 256GB     | 1         | 1.59%   |
| Samsung MZAL4512HBLU-00BL2 512GB     | 1         | 1.59%   |
| Samsung HM080GC 80GB                 | 1         | 1.59%   |
| Samsung AWMB3R  16GB                 | 1         | 1.59%   |
| PNY 1TB SATA SSD                     | 1         | 1.59%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 6      | 20.69%  |
| Seagate             | 6         | 6      | 20.69%  |
| Toshiba             | 5         | 5      | 17.24%  |
| Hitachi             | 5         | 5      | 17.24%  |
| Fujitsu             | 3         | 3      | 10.34%  |
| HGST                | 2         | 2      | 6.9%    |
| Unknown             | 1         | 1      | 3.45%   |
| Samsung Electronics | 1         | 1      | 3.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 5         | 5      | 31.25%  |
| SanDisk             | 2         | 2      | 12.5%   |
| Samsung Electronics | 2         | 2      | 12.5%   |
| China               | 2         | 2      | 12.5%   |
| A-DATA Technology   | 2         | 2      | 12.5%   |
| PNY                 | 1         | 1      | 6.25%   |
| KingSpec            | 1         | 1      | 6.25%   |
| Unknown             | 1         | 1      | 6.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 28        | 29     | 46.67%  |
| SSD     | 16        | 16     | 26.67%  |
| MMC     | 7         | 7      | 11.67%  |
| NVMe    | 6         | 9      | 10%     |
| Unknown | 3         | 3      | 5%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 43        | 43     | 69.35%  |
| MMC  | 7         | 7      | 11.29%  |
| SAS  | 6         | 6      | 9.68%   |
| NVMe | 6         | 8      | 9.68%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 39        | 40     | 88.64%  |
| 0.51-1.0   | 4         | 4      | 9.09%   |
| 4.01-10.0  | 1         | 1      | 2.27%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 15        | 25.86%  |
| 51-100     | 14        | 24.14%  |
| 251-500    | 12        | 20.69%  |
| 1-20       | 6         | 10.34%  |
| 21-50      | 5         | 8.62%   |
| 501-1000   | 3         | 5.17%   |
| 1001-2000  | 2         | 3.45%   |
| Unknown    | 1         | 1.72%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 42        | 72.41%  |
| 21-50    | 7         | 12.07%  |
| 51-100   | 4         | 6.9%    |
| 251-500  | 3         | 5.17%   |
| 501-1000 | 1         | 1.72%   |
| Unknown  | 1         | 1.72%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Notebooks | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WD2500BEVT-60A23T0 250GB     | 1         | 1      | 7.69%   |
| Toshiba MK3252GSX 320GB          | 1         | 1      | 7.69%   |
| Seagate ST9500325AS 500GB        | 1         | 1      | 7.69%   |
| Seagate ST9120822AS 120GB        | 1         | 1      | 7.69%   |
| Samsung Electronics HM080GC 80GB | 1         | 1      | 7.69%   |
| PNY 1TB SATA SSD                 | 1         | 1      | 7.69%   |
| Hitachi HTS545032B9A300 320GB    | 1         | 1      | 7.69%   |
| Hitachi HTS543225L9SA00 250GB    | 1         | 1      | 7.69%   |
| Hitachi DK23CA-20 20GB           | 1         | 1      | 7.69%   |
| HGST HTS725050A7E630 500GB       | 1         | 1      | 7.69%   |
| HGST HTS541075A9E680 752GB       | 1         | 1      | 7.69%   |
| Fujitsu MHZ2160BH G2 160GB       | 1         | 1      | 7.69%   |
| Fujitsu MHY2080BH 80GB           | 1         | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 3         | 3      | 23.08%  |
| Seagate             | 2         | 2      | 15.38%  |
| HGST                | 2         | 2      | 15.38%  |
| Fujitsu             | 2         | 2      | 15.38%  |
| WDC                 | 1         | 1      | 7.69%   |
| Toshiba             | 1         | 1      | 7.69%   |
| Samsung Electronics | 1         | 1      | 7.69%   |
| PNY                 | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 3         | 3      | 25%     |
| Seagate             | 2         | 2      | 16.67%  |
| HGST                | 2         | 2      | 16.67%  |
| Fujitsu             | 2         | 2      | 16.67%  |
| WDC                 | 1         | 1      | 8.33%   |
| Toshiba             | 1         | 1      | 8.33%   |
| Samsung Electronics | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 12     | 92.31%  |
| SSD  | 1         | 1      | 7.69%   |

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
| Works    | 34        | 37     | 56.67%  |
| Detected | 13        | 14     | 21.67%  |
| Malfunc  | 13        | 13     | 21.67%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 39        | 68.42%  |
| AMD                              | 8         | 14.04%  |
| Silicon Integrated Systems [SiS] | 3         | 5.26%   |
| Samsung Electronics              | 3         | 5.26%   |
| SanDisk                          | 2         | 3.51%   |
| Silicon Motion                   | 1         | 1.75%   |
| Phison Electronics               | 1         | 1.75%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 7.58%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 5         | 7.58%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 6.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 4         | 6.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 4         | 6.06%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 3         | 4.55%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 4.55%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 3         | 4.55%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 3         | 4.55%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 3         | 4.55%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                       | 2         | 3.03%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 2         | 3.03%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 3.03%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 1         | 1.52%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 1.52%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD          | 1         | 1.52%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 1         | 1.52%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                    | 1         | 1.52%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 1.52%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 1         | 1.52%   |
| Phison E12 NVMe Controller                                                       | 1         | 1.52%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 1.52%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 1         | 1.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.52%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 1.52%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 1         | 1.52%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 1.52%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 1         | 1.52%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 1         | 1.52%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                    | 1         | 1.52%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 1.52%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 1.52%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 1         | 1.52%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 1.52%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 1         | 1.52%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 1         | 1.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 34        | 54.84%  |
| IDE  | 20        | 32.26%  |
| NVMe | 6         | 9.68%   |
| RAID | 2         | 3.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 46        | 79.31%  |
| AMD    | 12        | 20.69%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Pentium M processor 1.70GHz           | 2         | 3.45%   |
| Intel Core i5-4210M CPU @ 2.60GHz           | 2         | 3.45%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 2         | 3.45%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 2         | 3.45%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 2         | 3.45%   |
| Intel Atom CPU Z520 @ 1.33GHz               | 2         | 3.45%   |
| Intel Atom CPU N270 @ 1.60GHz               | 2         | 3.45%   |
| AMD C-70 APU with Radeon HD Graphics        | 2         | 3.45%   |
| Intel Pentium M processor 1000MHz           | 1         | 1.72%   |
| Intel Pentium M processor 1.73GHz           | 1         | 1.72%   |
| Intel Pentium M processor 1.60GHz           | 1         | 1.72%   |
| Intel Pentium III (Coppermine)              | 1         | 1.72%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 1.72%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 1.72%   |
| Intel Pentium CPU 4415U @ 2.30GHz           | 1         | 1.72%   |
| Intel Pentium 4 CPU 2.66GHz                 | 1         | 1.72%   |
| Intel Genuine CPU T2300 @ 1.66GHz           | 1         | 1.72%   |
| Intel Genuine CPU T2050 @ 1.60GHz           | 1         | 1.72%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz            | 1         | 1.72%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1         | 1.72%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.72%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.72%   |
| Intel Core i5 CPU M 450 @ 2.40GHz           | 1         | 1.72%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 1         | 1.72%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz        | 1         | 1.72%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz        | 1         | 1.72%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz        | 1         | 1.72%   |
| Intel Core 2 Duo CPU T6670 @ 2.20GHz        | 1         | 1.72%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz        | 1         | 1.72%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz        | 1         | 1.72%   |
| Intel Core 2 CPU T5500 @ 1.66GHz            | 1         | 1.72%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 1         | 1.72%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 1         | 1.72%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 1         | 1.72%   |
| Intel Celeron J4115 CPU @ 1.80GHz           | 1         | 1.72%   |
| Intel Celeron CPU N2940 @ 1.83GHz           | 1         | 1.72%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz           | 1         | 1.72%   |
| Intel Atom CPU Z3735G @ 1.33GHz             | 1         | 1.72%   |
| Intel 12th Gen Core i5-1240P                | 1         | 1.72%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 1         | 1.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core 2 Duo        | 8         | 13.79%  |
| Intel Celeron           | 7         | 12.07%  |
| Intel Core i5           | 6         | 10.34%  |
| Intel Atom              | 6         | 10.34%  |
| Intel Pentium M         | 5         | 8.62%   |
| Intel Core i3           | 3         | 5.17%   |
| Other                   | 2         | 3.45%   |
| Intel Pentium Dual-Core | 2         | 3.45%   |
| Intel Genuine           | 2         | 3.45%   |
| AMD C-70                | 2         | 3.45%   |
| Intel Pentium III       | 1         | 1.72%   |
| Intel Pentium 4         | 1         | 1.72%   |
| Intel Pentium           | 1         | 1.72%   |
| Intel Core m3           | 1         | 1.72%   |
| Intel Core 2            | 1         | 1.72%   |
| AMD V120                | 1         | 1.72%   |
| AMD Ryzen 9             | 1         | 1.72%   |
| AMD Ryzen 7 PRO         | 1         | 1.72%   |
| AMD Ryzen 7             | 1         | 1.72%   |
| AMD Mobile Sempron      | 1         | 1.72%   |
| AMD E                   | 1         | 1.72%   |
| AMD Athlon Neo          | 1         | 1.72%   |
| AMD A8                  | 1         | 1.72%   |
| AMD A6                  | 1         | 1.72%   |
| AMD A4                  | 1         | 1.72%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 33        | 56.9%   |
| 1      | 14        | 24.14%  |
| 4      | 8         | 13.79%  |
| 16     | 1         | 1.72%   |
| 12     | 1         | 1.72%   |
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
| 1      | 39        | 67.24%  |
| 2      | 19        | 32.76%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 44        | 75.86%  |
| 32-bit         | 14        | 24.14%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 8         | 13.79%  |
| 0x206a7    | 4         | 6.9%    |
| 0x1067a    | 4         | 6.9%    |
| 0x6fd      | 3         | 5.17%   |
| 0x106c2    | 3         | 5.17%   |
| 0x706a1    | 2         | 3.45%   |
| 0x6e8      | 2         | 3.45%   |
| 0x406c4    | 2         | 3.45%   |
| 0x306c3    | 2         | 3.45%   |
| 0x30678    | 2         | 3.45%   |
| 0x10676    | 2         | 3.45%   |
| 0x05000119 | 2         | 3.45%   |
| 0xf27      | 1         | 1.72%   |
| 0x906a3    | 1         | 1.72%   |
| 0x806e9    | 1         | 1.72%   |
| 0x806c1    | 1         | 1.72%   |
| 0x706a8    | 1         | 1.72%   |
| 0x6fb      | 1         | 1.72%   |
| 0x6f6      | 1         | 1.72%   |
| 0x6d8      | 1         | 1.72%   |
| 0x6d6      | 1         | 1.72%   |
| 0x695      | 1         | 1.72%   |
| 0x68a      | 1         | 1.72%   |
| 0x406e3    | 1         | 1.72%   |
| 0x40651    | 1         | 1.72%   |
| 0x306a9    | 1         | 1.72%   |
| 0x20655    | 1         | 1.72%   |
| 0x0a704103 | 1         | 1.72%   |
| 0x0a601203 | 1         | 1.72%   |
| 0x08108102 | 1         | 1.72%   |
| 0x07030106 | 1         | 1.72%   |
| 0x06006705 | 1         | 1.72%   |
| 0x0500010d | 1         | 1.72%   |
| 0x010000c8 | 1         | 1.72%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| P6            | 8         | 13.79%  |
| Penryn        | 6         | 10.34%  |
| Silvermont    | 5         | 8.62%   |
| Core          | 5         | 8.62%   |
| SandyBridge   | 4         | 6.9%    |
| Goldmont plus | 4         | 6.9%    |
| Bonnell       | 4         | 6.9%    |
| Haswell       | 3         | 5.17%   |
| Bobcat        | 3         | 5.17%   |
| Unknown       | 3         | 5.17%   |
| K8 Hammer     | 2         | 3.45%   |
| Excavator     | 2         | 3.45%   |
| Zen+          | 1         | 1.72%   |
| Westmere      | 1         | 1.72%   |
| TigerLake     | 1         | 1.72%   |
| Skylake       | 1         | 1.72%   |
| Puma          | 1         | 1.72%   |
| NetBurst      | 1         | 1.72%   |
| KabyLake      | 1         | 1.72%   |
| K10           | 1         | 1.72%   |
| IvyBridge     | 1         | 1.72%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 37        | 60.66%  |
| AMD                              | 16        | 26.23%  |
| Nvidia                           | 4         | 6.56%   |
| Silicon Integrated Systems [SiS] | 3         | 4.92%   |
| S3 Graphics                      | 1         | 1.64%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                      | Notebooks | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                        | 4         | 5.8%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                          | 4         | 5.8%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller              | 4         | 5.8%    |
| Intel GeminiLake [UHD Graphics 600]                                                        | 4         | 5.8%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 4         | 5.8%    |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                  | 3         | 4.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller   | 3         | 4.35%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                        | 2         | 2.9%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                                 | 2         | 2.9%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                  | 2         | 2.9%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                               | 2         | 2.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                               | 2         | 2.9%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                                | 2         | 2.9%    |
| AMD Wrestler [Radeon HD 7290]                                                              | 2         | 2.9%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                   | 2         | 2.9%    |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                          | 1         | 1.45%   |
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 1         | 1.45%   |
| Silicon Integrated Systems [SiS] 65x/M650/740 PCI/AGP VGA Display Adapter                  | 1         | 1.45%   |
| S3 Graphics 86C270-294 [SavageIX-MV]                                                       | 1         | 1.45%   |
| Nvidia GF119M [GeForce GT 520M]                                                            | 1         | 1.45%   |
| Nvidia G96CM [GeForce GT 220M]                                                             | 1         | 1.45%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                              | 1         | 1.45%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                                            | 1         | 1.45%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                  | 1         | 1.45%   |
| Intel HD Graphics 610                                                                      | 1         | 1.45%   |
| Intel HD Graphics 515                                                                      | 1         | 1.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                                           | 1         | 1.45%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                  | 1         | 1.45%   |
| Intel 82852/855GM Integrated Graphics Device                                               | 1         | 1.45%   |
| Intel 3rd Gen Core processor Graphics Controller                                           | 1         | 1.45%   |
| AMD Wrestler [Radeon HD 6310]                                                              | 1         | 1.45%   |
| AMD Topaz PRO [Radeon R5 M255]                                                             | 1         | 1.45%   |
| AMD RV711/M93 [Mobility Radeon HD 4350/4550/530v/540v/545v / FirePro RG220]                | 1         | 1.45%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/5145/530v/540v/545v]                           | 1         | 1.45%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                                    | 1         | 1.45%   |
| AMD RV350/M10 / RV360/M11 [Mobility Radeon 9600 (PRO) / 9700]                              | 1         | 1.45%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                  | 1         | 1.45%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                  | 1         | 1.45%   |
| AMD Raphael                                                                                | 1         | 1.45%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                       | 1         | 1.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 26        | 44.83%  |
| 1 x AMD         | 14        | 24.14%  |
| 2 x Intel       | 8         | 13.79%  |
| 1 x SiS         | 3         | 5.17%   |
| 1 x Nvidia      | 2         | 3.45%   |
| Other           | 1         | 1.72%   |
| 1 x S3 Graphics | 1         | 1.72%   |
| Intel + Nvidia  | 1         | 1.72%   |
| Intel + AMD     | 1         | 1.72%   |
| AMD + Nvidia    | 1         | 1.72%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 50        | 86.21%  |
| Unknown     | 5         | 8.62%   |
| Proprietary | 3         | 5.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 41        | 70.69%  |
| 0.01-0.5   | 15        | 25.86%  |
| 1.01-2.0   | 2         | 3.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 11        | 22.45%  |
| Samsung Electronics     | 8         | 16.33%  |
| Chimei Innolux          | 8         | 16.33%  |
| LG Display              | 6         | 12.24%  |
| BOE                     | 3         | 6.12%   |
| HannStar                | 2         | 4.08%   |
| Dell                    | 2         | 4.08%   |
| CPT                     | 2         | 4.08%   |
| MQP                     | 1         | 2.04%   |
| LG Philips              | 1         | 2.04%   |
| InfoVision              | 1         | 2.04%   |
| Hewlett-Packard         | 1         | 2.04%   |
| CSO                     | 1         | 2.04%   |
| Chi Mei Optoelectronics | 1         | 2.04%   |
| Apple                   | 1         | 2.04%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 4.08%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 2         | 4.08%   |
| Samsung Electronics LF24T450F SAM7095 1920x1080 527x296mm 23.8-inch      | 1         | 2.04%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch     | 1         | 2.04%   |
| Samsung Electronics LCD Monitor SEC3242 1024x600 223x125mm 10.1-inch     | 1         | 2.04%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch     | 1         | 2.04%   |
| Samsung Electronics LCD Monitor SEC3051 1600x900 390x230mm 17.8-inch     | 1         | 2.04%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch     | 1         | 2.04%   |
| Samsung Electronics LCD Monitor SDC4851 1366x768 344x194mm 15.5-inch     | 1         | 2.04%   |
| Samsung Electronics LCD Monitor SAM069B 1920x1080 890x500mm 40.2-inch    | 1         | 2.04%   |
| MQP MultiQ MQ212 MQP0212 800x600 246x185mm 12.1-inch                     | 1         | 2.04%   |
| LG Philips LCD Monitor LPL0C01 1280x800 304x190mm 14.1-inch              | 1         | 2.04%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch             | 1         | 2.04%   |
| LG Display LCD Monitor LGD0500 1366x768 256x144mm 11.6-inch              | 1         | 2.04%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch              | 1         | 2.04%   |
| LG Display LCD Monitor LGD01E6 1366x768 310x170mm 13.9-inch              | 1         | 2.04%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch             | 1         | 2.04%   |
| Hewlett-Packard Z24i HWP3100 1920x1200 520x320mm 24.0-inch               | 1         | 2.04%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 1         | 2.04%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                 | 1         | 2.04%   |
| Dell UP2715K DEL40B6 2560x1440 600x340mm 27.2-inch                       | 1         | 2.04%   |
| Dell U2415 DELA0BC 1920x1200 518x324mm 24.1-inch                         | 1         | 2.04%   |
| CSO MNH301CA3-1 CSO1702 2560x1440 380x210mm 17.1-inch                    | 1         | 2.04%   |
| CPT LCD Monitor CPT13B1 1280x800 330x210mm 15.4-inch                     | 1         | 2.04%   |
| CPT LCD Monitor CPT13B0 1280x800 331x207mm 15.4-inch                     | 1         | 2.04%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch         | 1         | 2.04%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 2.04%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 1         | 2.04%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 1         | 2.04%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch          | 1         | 2.04%   |
| Chimei Innolux LCD Monitor CMN1118 1366x768 256x144mm 11.6-inch          | 1         | 2.04%   |
| Chi Mei Optoelectronics LCD Monitor CMO1004 1024x600 222x125mm 10.0-inch | 1         | 2.04%   |
| BOE LCD Monitor BOE0BCA 2256x1504 285x190mm 13.5-inch                    | 1         | 2.04%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                     | 1         | 2.04%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                     | 1         | 2.04%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch           | 1         | 2.04%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 344x193mm 15.5-inch           | 1         | 2.04%   |
| AU Optronics LCD Monitor AUO315D 1920x1080 256x144mm 11.6-inch           | 1         | 2.04%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch            | 1         | 2.04%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 1         | 2.04%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 18        | 37.5%   |
| 1920x1080 (FHD)   | 12        | 25%     |
| 1280x800 (WXGA)   | 6         | 12.5%   |
| 1600x900 (HD+)    | 3         | 6.25%   |
| 1920x1200 (WUXGA) | 2         | 4.17%   |
| 1024x600          | 2         | 4.17%   |
| 800x600           | 1         | 2.08%   |
| 2560x1440 (QHD)   | 1         | 2.08%   |
| 2256x1504         | 1         | 2.08%   |
| 2160x1440         | 1         | 2.08%   |
| 1024x768 (XGA)    | 1         | 2.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 21        | 42.86%  |
| 13     | 6         | 12.24%  |
| 14     | 5         | 10.2%   |
| 11     | 4         | 8.16%   |
| 12     | 3         | 6.12%   |
| 17     | 2         | 4.08%   |
| 10     | 2         | 4.08%   |
| 46     | 1         | 2.04%   |
| 40     | 1         | 2.04%   |
| 27     | 1         | 2.04%   |
| 24     | 1         | 2.04%   |
| 23     | 1         | 2.04%   |
| 18     | 1         | 2.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 28        | 58.33%  |
| 201-300     | 11        | 22.92%  |
| 351-400     | 4         | 8.33%   |
| 501-600     | 3         | 6.25%   |
| 801-900     | 1         | 2.08%   |
| 1001-1500   | 1         | 2.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 35        | 76.09%  |
| 16/10 | 7         | 15.22%  |
| 4/3   | 2         | 4.35%   |
| 3/2   | 2         | 4.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 21        | 42.86%  |
| 81-90          | 11        | 22.45%  |
| 51-60          | 4         | 8.16%   |
| 61-70          | 2         | 4.08%   |
| 41-50          | 2         | 4.08%   |
| 121-130        | 2         | 4.08%   |
| 501-1000       | 2         | 4.08%   |
| 71-80          | 1         | 2.04%   |
| 301-350        | 1         | 2.04%   |
| 251-300        | 1         | 2.04%   |
| 201-250        | 1         | 2.04%   |
| 141-150        | 1         | 2.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 23        | 46.94%  |
| 51-100  | 10        | 20.41%  |
| 121-160 | 9         | 18.37%  |
| 161-240 | 5         | 10.2%   |
| 1-50    | 2         | 4.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 50        | 86.21%  |
| 2     | 4         | 6.9%    |
| 0     | 4         | 6.9%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 30        | 30.93%  |
| Intel                            | 22        | 22.68%  |
| Qualcomm Atheros                 | 16        | 16.49%  |
| Broadcom                         | 8         | 8.25%   |
| Marvell Technology Group         | 5         | 5.15%   |
| Silicon Integrated Systems [SiS] | 3         | 3.09%   |
| Broadcom Limited                 | 3         | 3.09%   |
| Ralink Technology                | 2         | 2.06%   |
| Xiaomi                           | 1         | 1.03%   |
| Qualcomm Technologies            | 1         | 1.03%   |
| Motorola PCS                     | 1         | 1.03%   |
| MediaTek                         | 1         | 1.03%   |
| LG Electronics                   | 1         | 1.03%   |
| JMicron Technology               | 1         | 1.03%   |
| D-Link System                    | 1         | 1.03%   |
| Accton Technology                | 1         | 1.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 11        | 9.82%   |
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 8         | 7.14%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 3.57%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 3.57%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 3.57%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 4         | 3.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 3         | 2.68%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller        | 3         | 2.68%   |
| Silicon Integrated Systems [SiS] AC'97 Modem Controller                 | 2         | 1.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.79%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 2         | 1.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 1.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 1.79%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.79%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 2         | 1.79%   |
| Intel Wireless 7265                                                     | 2         | 1.79%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 1.79%   |
| Intel Ethernet Connection I217-V                                        | 2         | 1.79%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 2         | 1.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 1.79%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 1.79%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.89%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet               | 1         | 0.89%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 0.89%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.89%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.89%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.89%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 0.89%   |
| Realtek RTL8187B Wireless Adapter                                       | 1         | 0.89%   |
| Realtek RTL8125 2.5GbE Controller                                       | 1         | 0.89%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                              | 1         | 0.89%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.89%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                       | 1         | 0.89%   |
| Qualcomm WCN785x Wi-Fi 7(802.11be) 320MHz 2x2 [FastConnect 7800]        | 1         | 0.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 0.89%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 0.89%   |
| Motorola PCS moto g(7) power                                            | 1         | 0.89%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.89%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                 | 1         | 0.89%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 19        | 33.33%  |
| Qualcomm Atheros      | 15        | 26.32%  |
| Realtek Semiconductor | 11        | 19.3%   |
| Broadcom              | 5         | 8.77%   |
| Ralink Technology     | 2         | 3.51%   |
| Broadcom Limited      | 2         | 3.51%   |
| Qualcomm Technologies | 1         | 1.75%   |
| MediaTek              | 1         | 1.75%   |
| D-Link System         | 1         | 1.75%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 4         | 7.02%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 4         | 7.02%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 4         | 7.02%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                    | 4         | 7.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 2         | 3.51%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                  | 2         | 3.51%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 2         | 3.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 2         | 3.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 2         | 3.51%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 2         | 3.51%   |
| Intel Wireless 7265                                                         | 2         | 3.51%   |
| Intel Wi-Fi 6 AX200                                                         | 2         | 3.51%   |
| Broadcom BCM43228 802.11a/b/g/n                                             | 2         | 3.51%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                 | 1         | 1.75%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1         | 1.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 1         | 1.75%   |
| Realtek RTL8187SE Wireless LAN Controller                                   | 1         | 1.75%   |
| Realtek RTL8187B Wireless Adapter                                           | 1         | 1.75%   |
| Ralink RT5370 Wireless Adapter                                              | 1         | 1.75%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                           | 1         | 1.75%   |
| Qualcomm WCN785x Wi-Fi 7(802.11be) 320MHz 2x2 [FastConnect 7800]            | 1         | 1.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 1         | 1.75%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter               | 1         | 1.75%   |
| Intel Wireless 3165                                                         | 1         | 1.75%   |
| Intel WiFi Link 5100                                                        | 1         | 1.75%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                   | 1         | 1.75%   |
| Intel Gemini Lake PCH CNVi WiFi                                             | 1         | 1.75%   |
| Intel Centrino Ultimate-N 6300                                              | 1         | 1.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 1         | 1.75%   |
| Intel Alder Lake-P PCH CNVi WiFi                                            | 1         | 1.75%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]  | 1         | 1.75%   |
| Broadcom Limited BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1         | 1.75%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                   | 1         | 1.75%   |
| Broadcom BCM4321 802.11a/b/g/n                                              | 1         | 1.75%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 1         | 1.75%   |
| Broadcom BCM4311 802.11b/g WLAN                                             | 1         | 1.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 24        | 50%     |
| Intel                            | 7         | 14.58%  |
| Marvell Technology Group         | 5         | 10.42%  |
| Broadcom                         | 3         | 6.25%   |
| Silicon Integrated Systems [SiS] | 2         | 4.17%   |
| Xiaomi                           | 1         | 2.08%   |
| Qualcomm Atheros                 | 1         | 2.08%   |
| Motorola PCS                     | 1         | 2.08%   |
| LG Electronics                   | 1         | 2.08%   |
| JMicron Technology               | 1         | 2.08%   |
| Broadcom Limited                 | 1         | 2.08%   |
| Accton Technology                | 1         | 2.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 11        | 22.92%  |
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 8         | 16.67%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3         | 6.25%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 2         | 4.17%   |
| Intel Ethernet Connection I217-V                                       | 2         | 4.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 4.17%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 2.08%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet              | 1         | 2.08%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1         | 2.08%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 2.08%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 1         | 2.08%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 2.08%   |
| Motorola PCS moto g(7) power                                           | 1         | 2.08%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 1         | 2.08%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 1         | 2.08%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 2.08%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)                    | 1         | 2.08%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1         | 2.08%   |
| Intel PRO/100 VE Network Connection                                    | 1         | 2.08%   |
| Intel 82577LC Gigabit Network Connection                               | 1         | 2.08%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                     | 1         | 2.08%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express               | 1         | 2.08%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express               | 1         | 2.08%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 2.08%   |
| Broadcom Limited NetXtreme BCM5755M Gigabit Ethernet PCI Express       | 1         | 2.08%   |
| Accton EN-1216 Ethernet Adapter                                        | 1         | 2.08%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 55        | 50.46%  |
| Ethernet | 47        | 43.12%  |
| Modem    | 7         | 6.42%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 42        | 72.41%  |
| Ethernet | 16        | 27.59%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 39        | 67.24%  |
| 1     | 15        | 25.86%  |
| 0     | 3         | 5.17%   |
| 3     | 1         | 1.72%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 45        | 77.59%  |
| Yes  | 13        | 22.41%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros Communications | 6         | 23.08%  |
| Intel                           | 6         | 23.08%  |
| Realtek Semiconductor           | 4         | 15.38%  |
| Alps Electric                   | 2         | 7.69%   |
| Toshiba                         | 1         | 3.85%   |
| MediaTek                        | 1         | 3.85%   |
| Hewlett-Packard                 | 1         | 3.85%   |
| Foxconn / Hon Hai               | 1         | 3.85%   |
| Dell                            | 1         | 3.85%   |
| Broadcom                        | 1         | 3.85%   |
| ASUSTek Computer                | 1         | 3.85%   |
| Apple                           | 1         | 3.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                        | 4         | 15.38%  |
| Qualcomm Atheros AR3011 Bluetooth              | 4         | 15.38%  |
| Intel Bluetooth wireless interface             | 3         | 11.54%  |
| Qualcomm Atheros  Bluetooth Device             | 2         | 7.69%   |
| Intel AX200 Bluetooth                          | 2         | 7.69%   |
| Alps Electric BCM2046 Bluetooth Device         | 2         | 7.69%   |
| Toshiba Askey for                              | 1         | 3.85%   |
| MediaTek Wireless_Device                       | 1         | 3.85%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1         | 3.85%   |
| HP Broadcom 2070 Bluetooth Combo               | 1         | 3.85%   |
| Foxconn / Hon Hai Bluetooth Device             | 1         | 3.85%   |
| Dell Wireless 360 Bluetooth                    | 1         | 3.85%   |
| Broadcom HP Portable Bumble Bee                | 1         | 3.85%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter          | 1         | 3.85%   |
| Apple Bluetooth HCI                            | 1         | 3.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 40        | 67.8%   |
| AMD                              | 14        | 23.73%  |
| Silicon Integrated Systems [SiS] | 3         | 5.08%   |
| Nvidia                           | 1         | 1.69%   |
| ESS Technology                   | 1         | 1.69%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 6.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 6.85%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 5.48%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 5.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 5.48%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 3         | 4.11%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 4.11%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 4.11%   |
| AMD FCH Azalia Controller                                                                         | 3         | 4.11%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 4.11%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 2         | 2.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 2.74%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 2         | 2.74%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 2         | 2.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 2.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 2.74%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 2.74%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 2         | 2.74%   |
| AMD High Definition Audio Controller                                                              | 2         | 2.74%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 2.74%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 1.37%   |
| Nvidia Audio device                                                                               | 1         | 1.37%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 1.37%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1.37%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 1.37%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 1.37%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 1         | 1.37%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 1.37%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1         | 1.37%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 1.37%   |
| ESS Technology ES1988 Allegro-1                                                                   | 1         | 1.37%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 1         | 1.37%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 1.37%   |
| AMD RS690 HDMI Audio [Radeon Xpress 1200 Series]                                                  | 1         | 1.37%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.37%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 1.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 20        | 32.79%  |
| Samsung Electronics | 15        | 24.59%  |
| SK hynix            | 7         | 11.48%  |
| Kingston            | 5         | 8.2%    |
| Unknown (ABCD)      | 3         | 4.92%   |
| Micron Technology   | 2         | 3.28%   |
| Elpida              | 2         | 3.28%   |
| A-DATA Technology   | 2         | 3.28%   |
| Toshiba             | 1         | 1.64%   |
| Team                | 1         | 1.64%   |
| Ramaxel Technology  | 1         | 1.64%   |
| Crucial             | 1         | 1.64%   |
| Corsair             | 1         | 1.64%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2                               | 6         | 9.23%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 4.62%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 4.62%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 3.08%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 3.08%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 3.08%   |
| Unknown RAM Module 512MB SODIMM SDRAM                            | 1         | 1.54%   |
| Unknown RAM Module 512MB SODIMM DRAM                             | 1         | 1.54%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 1.54%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 1.54%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 1.54%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 1.54%   |
| Unknown RAM Module 2GB SODIMM DDR                                | 1         | 1.54%   |
| Unknown RAM Module 256MB SODIMM SDRAM                            | 1         | 1.54%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 1         | 1.54%   |
| Unknown RAM Module 1GB SODIMM DRAM                               | 1         | 1.54%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 1.54%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 1.54%   |
| Unknown RAM Module 1GB SODIMM DDR 266MT/s                        | 1         | 1.54%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 1.54%   |
| Unknown RAM Module 1GB DIMM DDR3 1333MT/s                        | 1         | 1.54%   |
| Unknown RAM CL19-19-19 D4-2666 8GB SODIMM DDR4 2133MT/s          | 1         | 1.54%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s               | 1         | 1.54%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 1066MT/s             | 1         | 1.54%   |
| Team RAM Elite-800 2GB SODIMM DDR 667MT/s                        | 1         | 1.54%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                  | 1         | 1.54%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 1         | 1.54%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.54%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.54%   |
| SK hynix RAM HMCG66AGBSA092N 8GB SODIMM DDR5 5600MT/s            | 1         | 1.54%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 1         | 1.54%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2400MT/s           | 1         | 1.54%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 1         | 1.54%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.54%   |
| Samsung RAM M471B1G73QHO-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.54%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 1.54%   |
| Samsung RAM M4 70T5663QZ3-CE6 2GB SODIMM DDR2 667MT/s            | 1         | 1.54%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR2 975MT/s            | 1         | 1.54%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s                  | 1         | 1.54%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 1         | 1.54%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 16        | 28.57%  |
| DDR2   | 15        | 26.79%  |
| DDR4   | 7         | 12.5%   |
| DDR    | 5         | 8.93%   |
| SDRAM  | 4         | 7.14%   |
| LPDDR4 | 3         | 5.36%   |
| LPDDR3 | 2         | 3.57%   |
| DRAM   | 2         | 3.57%   |
| DDR5   | 2         | 3.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 51        | 92.73%  |
| Unknown      | 2         | 3.64%   |
| Row Of Chips | 1         | 1.82%   |
| DIMM         | 1         | 1.82%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 20        | 33.33%  |
| 4096  | 16        | 26.67%  |
| 8192  | 10        | 16.67%  |
| 1024  | 7         | 11.67%  |
| 512   | 4         | 6.67%   |
| 32768 | 1         | 1.67%   |
| 16384 | 1         | 1.67%   |
| 256   | 1         | 1.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 14        | 24.56%  |
| 1600    | 8         | 14.04%  |
| 667     | 5         | 8.77%   |
| 2400    | 4         | 7.02%   |
| 1334    | 4         | 7.02%   |
| 3200    | 3         | 5.26%   |
| 1067    | 3         | 5.26%   |
| 5600    | 2         | 3.51%   |
| 3266    | 2         | 3.51%   |
| 2667    | 2         | 3.51%   |
| 1867    | 2         | 3.51%   |
| 1333    | 2         | 3.51%   |
| 4199    | 1         | 1.75%   |
| 2048    | 1         | 1.75%   |
| 1066    | 1         | 1.75%   |
| 800     | 1         | 1.75%   |
| 533     | 1         | 1.75%   |
| 266     | 1         | 1.75%   |

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
| Bison Electronics                      | 5         | 15.15%  |
| Microdia                               | 4         | 12.12%  |
| IMC Networks                           | 4         | 12.12%  |
| Chicony Electronics                    | 4         | 12.12%  |
| Cheng Uei Precision Industry (Foxlink) | 4         | 12.12%  |
| Ricoh                                  | 3         | 9.09%   |
| Suyin                                  | 2         | 6.06%   |
| USB Camera CS                          | 1         | 3.03%   |
| Silicon Motion                         | 1         | 3.03%   |
| Realtek Semiconductor                  | 1         | 3.03%   |
| Quanta                                 | 1         | 3.03%   |
| Luxvisions Innotech Limited            | 1         | 3.03%   |
| ALi                                    | 1         | 3.03%   |
| Alcor Micro                            | 1         | 3.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Microdia Sonix USB 2.0 Camera                               | 2         | 6.06%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 2         | 6.06%   |
| Bison Integrated Camera                                     | 2         | 6.06%   |
| USB Camera CS USB Camera CS                                 | 1         | 3.03%   |
| Suyin HD WebCam                                             | 1         | 3.03%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 3.03%   |
| Silicon Motion 300k Pixel Camera                            | 1         | 3.03%   |
| Ricoh Webcam 1000                                           | 1         | 3.03%   |
| Ricoh Sony Visual Communication Camera                      | 1         | 3.03%   |
| Ricoh Sony Vaio Integrated Webcam                           | 1         | 3.03%   |
| Realtek USB2.0 VGA UVC WebCam                               | 1         | 3.03%   |
| Quanta Chromebook HD Camera                                 | 1         | 3.03%   |
| Microdia Webcam Vitade AF                                   | 1         | 3.03%   |
| Microdia Laptop_Integrated_Webcam_E4HD                      | 1         | 3.03%   |
| Luxvisions Innotech Limited Integrated Camera               | 1         | 3.03%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 3.03%   |
| IMC Networks USB 2.0 Camera                                 | 1         | 3.03%   |
| IMC Networks Integrated Camera                              | 1         | 3.03%   |
| IMC Networks HP TrueVision HD Camera                        | 1         | 3.03%   |
| Chicony USB2.0 UVC WebCam                                   | 1         | 3.03%   |
| Chicony Integrated Camera                                   | 1         | 3.03%   |
| Chicony HP Webcam                                           | 1         | 3.03%   |
| Chicony HP HD Webcam                                        | 1         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) Webcam (UVC)         | 1         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 1         | 3.03%   |
| Bison HP Webcam-101                                         | 1         | 3.03%   |
| Bison HD Webcam                                             | 1         | 3.03%   |
| Bison EasyCamera                                            | 1         | 3.03%   |
| ALi M5603 Video Camera Controller                           | 1         | 3.03%   |
| Alcor Micro USB 2.0 PC cam                                  | 1         | 3.03%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 2         | 40%     |
| Synaptics                  | 1         | 20%     |
| STMicroelectronics         | 1         | 20%     |
| Shenzhen Goodix Technology | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 20%     |
| Validity Sensors VFS451 Fingerprint Reader        | 1         | 20%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 20%     |
| STMicroelectronics Fingerprint Reader             | 1         | 20%     |
| Shenzhen Goodix  FingerPrint Device               | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| O2 Micro    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader  | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 42        | 72.41%  |
| 1     | 9         | 15.52%  |
| 2     | 6         | 10.34%  |
| 4     | 1         | 1.72%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 10        | 40%     |
| Fingerprint reader       | 5         | 20%     |
| Net/wireless             | 2         | 8%      |
| Flash memory             | 2         | 8%      |
| Communication controller | 2         | 8%      |
| Chipcard                 | 2         | 8%      |
| Camera                   | 2         | 8%      |

